# GNP Intake Assistant

*The GNP Intake Assistant is now live as a companion GPT for the Good Neighbor Protocol.*

**[Try the GNP Intake Assistant →](https://chatgpt.com/g/g-69e55335a8e4819186385d67a74ab6f0-gnp-intake-assistant)**

---

## What It Is

The GNP Intake Assistant is a live companion GPT for the Good Neighbor Protocol — not the future middleware app, and not a replacement for the handbook. It is an early interactive layer that helps people turn vague requests into clearer handoffs through conversation rather than manual checklist completion.

It is a real, working tool. It is not yet the full structured app or middleware vision — that is a longer-term direction. This is the first interactive layer of GNP, and it is here now.

The idea is simple: most people will not fill out a form. But most people will answer a question if someone asks it clearly and calmly.

The assistant is that someone.

---

## The Three Core Modes

### 1. Intake Mode

Helps someone shape a request from scratch.

The person describes what they need — in plain language, the way they would actually say it. The assistant reads what is there, identifies which CASSEROLE elements are missing or unclear, and asks about them one by one.

The result is a structured request the person can hand off directly — pasted into a Jira ticket, a Notion doc, a Slack message, or an email.

**Example:**

> User: "I need someone to redo the onboarding flow before we launch."
>
> Assistant: "Got it. A few things will help shape this clearly. What specifically about the onboarding flow needs to change — is it the steps, the copy, the design, the technical flow, or all of it? And who is doing the redesign?"

The assistant reads what is already in the request and only asks about what is actually missing.

---

### 2. Casserole Readiness Check

Reviews an existing request and checks whether it is casserole-ready.

The person pastes or describes a request they are about to send. The assistant reviews it against the CASSEROLE framework and gives a honest assessment: what is present, what is missing, and whether it is ready to travel.

This mode is especially useful for people who have written a request but are not sure if it is complete — and for teams that want a quick gut check before they hand something off.

**Example output:**

> "This request is solid on Clarity and Scope, but it's missing Ownership — it's not clear who approves the final version. It's also missing Explain-Why. Why is this being built now, and what happens if it isn't? Those two things would make this significantly more carryable."

---

### 3. Another Casserole Pass

Returns a calm, structured response explaining what is missing and what needs more work.

This mode is for the receiving side. When a developer, project manager, or builder receives a request that is not ready — this gives them language for how to respond that is honest, specific, and not adversarial.

Instead of "I don't understand what you're asking," the response is a structured list of what is missing and what another casserole pass would address.

**This is not:**
- A rejection
- An insult
- "Start over"

**This is:**
- A calm, specific list of what needs more shape
- A shared protocol for naming the gap without drama
- A way to protect the receiving side from absorbing fog

---

## Design Principles

**It should feel like a thoughtful colleague, not a form.**
The CASSEROLE framework is the structure underneath — not the thing the user sees. The conversation should feel natural.

**It should not ask for things that are not needed.**
If scope is already obvious, do not ask about scope. Read what is there and fill in what is actually missing.

**It should produce something usable.**
The output of Intake Mode is a brief the person can hand off directly. Not a longer version of the vague request, reformatted.

**It should respect the user's time.**
Two to four exchanges should handle most requests. If it consistently takes more, the design is wrong.

---

## What It Is Not

- Not a project management tool
- Not a replacement for human judgment about whether a request is a good idea
- Not an AI that builds things — it helps people describe things clearly
- Not a substitute for the handbook — it is a guided application of it
- Not the same as the future middleware or app (which would integrate with dev tools directly)

---

## Current Status

The GNP Intake Assistant is live.

**[Try it here: GNP Intake Assistant](https://chatgpt.com/g/g-69e55335a8e4819186385d67a74ab6f0-gnp-intake-assistant)**

It is a working GPT companion — an early interactive layer of GNP. The design decisions documented here are grounded in the framework's values and reflected in how the assistant actually behaves. It is not yet the full structured intake app or middleware vision, but it is real and in use.

---

*See [roadmap.md](roadmap.md) for where this fits in the broader development plan.*
