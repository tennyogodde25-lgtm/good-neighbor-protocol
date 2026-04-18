# GPT Intake Assistant — Concept Notes

*This document describes a future feature concept. The GPT Intake Assistant does not currently exist. These are working notes on what it might become.*

---

## The Problem It Solves

The CASSEROLE checklist works well for people who are already motivated to think carefully about their requests. But most people, most of the time, don't want to fill out a checklist. They want to say what they need and have it land.

The GPT Intake Assistant concept is a way to make CASSEROLE feel less like a form and more like a conversation.

---

## What It Would Do

The assistant would accept a request in plain language — the kind of message someone would actually send — and work through CASSEROLE interactively to help fill in the gaps.

**Example interaction:**

> User: "I need a designer to redo the homepage before our product launch."
>
> Assistant: "Got it — let's make sure this lands well. A few questions: When is the launch, and what's the latest the homepage needs to be live? Also, is this the full homepage or a specific section?"

The assistant would not just ask generic questions. It would read what's already in the request and ask specifically about what's missing — based on which CASSEROLE elements are incomplete.

At the end, it would output a structured brief the person could paste directly into whatever tool they use — a Jira ticket, a Notion doc, a Slack message, or an email.

---

## Design Principles for the Assistant

**It should feel like a thoughtful colleague, not a form.**
The conversation should be natural. The checklist is the structure underneath — not the thing the user sees.

**It should not ask for things that aren't needed.**
If scope is already obvious from the request, don't ask about scope. Read what's there and only fill in what's actually missing.

**It should produce something usable.**
The output should be a brief the person can actually hand off — not a longer version of their vague request, just reformatted.

**It should respect the user's time.**
Two to four exchanges should be enough for most requests. If it takes longer than that, the design is wrong.

---

## What It Is Not

- It is not a project management tool
- It is not a replacement for human judgment about whether a request is a good idea
- It is not an AI that builds things — it helps people describe things clearly
- It is not a substitute for the handbook — it is a guided application of it

---

## Current Status

This is a concept. No code has been written. No GPT configuration exists yet.

This document exists to capture the intent clearly enough that when the time comes to build it, the design decisions are already grounded in the framework's values.

---

*See [roadmap.md](roadmap.md) for context on where this fits in the broader development plan.*
