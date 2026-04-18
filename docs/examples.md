# Examples — Good Neighbor Protocol

These are before/after examples showing what requests look like before and after applying the CASSEROLE framework.

The chaos versions are real. They are the kinds of messages people send every day. The casserole versions are not formal documents — they are the same request with enough shape to actually be carried.

---

## Example 1: Startup Feature Request

### Chaos Version

> "We need a dashboard or something — everyone keeps asking for updates and we can't keep doing this manually."

### What's missing

- **Clarity:** "A dashboard or something" is not a request. What kind of updates? For whom?
- **Alignment:** Is this a reporting problem, a communication problem, a workflow problem, or all three?
- **Scope:** Is this one screen? A new product feature? An internal tool? An external one?
- **Safety:** Who has access? Is any of this data sensitive?
- **Expectations:** What does a successful dashboard look like — what does it show, and to whom?
- **Reasonability:** How complex is the data? Is this a week of work or a quarter?
- **Ownership:** Who is deciding what goes on this dashboard? Who approves it before it ships?
- **Explain-Why:** What is the real problem being solved — what happens if updates keep going out manually?

### Casserole Version

> "We have a visibility problem. Our clients and internal stakeholders keep asking for project status updates, and right now one of us responds manually each time. It is taking up several hours a week and the information is inconsistent.
>
> We need a simple dashboard that shows current project status for each active client — not detailed data, just high-level milestones: what's complete, what's in progress, what's next, and any blockers.
>
> In scope: a read-only view accessible to clients via a link. Out of scope: editing capabilities, payment data, or anything beyond project milestones in this first version.
>
> This is client-facing, so anything involving names, timelines, or project details needs to be treated as confidential.
>
> Success looks like: a client can check their own project status without emailing us. We consider it done when we can turn off the manual update emails for at least 80% of clients.
>
> Constraints: we need a working version within six weeks. We are not ready to build a full product — this can be scrappy as long as it is accurate and accessible.
>
> Owner: [Founder] approves scope and design. [Dev lead] owns delivery.
>
> Why this matters: the manual update process is burning time we don't have, and inconsistent updates are starting to affect client trust."

---

## Example 2: Youth / Community Program Communication Issue

### Chaos Version

> "Can you make some kind of parent portal? Parents are always reaching out in a million different ways and we can't keep track."

### What's missing

- **Clarity:** What problem is the portal solving — information delivery, two-way messaging, scheduling, all of the above?
- **Safety:** This involves minors and their families. Privacy and data handling requirements are significant.
- **Scope:** Is this an announcement board? A messaging system? A document repository? A scheduling tool?
- **Reasonability:** "A parent portal" could be a two-week project or a two-year platform. This needs scoping.
- **Expectations:** What does a working version look like — not the final version, the first version that actually helps?
- **Limits:** What are the compliance requirements (FERPA, COPPA, local regulations)? What tech stack or tools are already in use?

### Casserole Version

> "We run a youth program and parent communication is currently scattered across text messages, emails, phone calls, and social media DMs. Staff are losing time managing multiple channels, and important information is getting missed.
>
> The real problem is: there is no single place for parents to find program announcements, schedule updates, and basic program information.
>
> For a first version, we need a one-way communication channel — a simple way to post announcements that parents can access in one place. We are not asking for two-way messaging or a full portal in this version.
>
> Safety: all families enrolled in the program are parents or guardians of minors. Any solution must comply with our organization's data privacy policy and applicable youth program regulations. No individual child data should be visible to other families.
>
> In scope: announcement posting, accessible by a shareable link or login. Out of scope: direct messaging between parents and staff, payment processing, or enrollment forms in this version.
>
> Success looks like: staff can post one announcement and all enrolled families see it without the team needing to send it through multiple channels.
>
> Constraints: we have a small budget and no dedicated tech staff. Any solution needs to be something non-technical staff can maintain.
>
> Owner: [Program Director] approves content and access. [Operations Lead] owns tool selection and setup.
>
> Why this matters: missed communications have caused confusion at pickup, missed consent forms, and parent frustration. This is affecting trust in the program."

---

## Example 3: Small Business Workflow Fix

### Chaos Version

> "We need to automate our intake because it's getting ridiculous. People are falling through the cracks and I can't keep doing this manually."

### What's missing

- **Clarity:** What is the intake process? What exactly is broken — volume, inconsistency, missing information, follow-up gaps?
- **Current Reality:** What does the existing process look like, step by step?
- **Scope:** Are we automating the whole intake process or just a specific broken part?
- **Expectations:** What does "fixed" look like — fewer dropped leads, consistent data, automatic follow-ups, all of the above?
- **Reasonability:** What tools are already in use? What is the budget and technical capacity?
- **Explain-Why:** What is the real cost of the current situation — lost clients, staff time, reputation?

### Casserole Version

> "Our current client intake process is entirely manual — a mix of email threads, handwritten notes, and follow-up reminders stored in a personal task list. When inquiries come in, the process for collecting information, following up, and scheduling a first call is inconsistent.
>
> The result: some prospective clients fall through without a response, we are collecting different information from different people, and there is no reliable record of who is in the pipeline.
>
> The specific problem we need to solve: intake consistency. Every new inquiry should go through the same process, collect the same basic information, and trigger the same follow-up steps — without someone having to remember to do it manually each time.
>
> In scope: a form for new inquiries that captures contact info, service interest, and timeline; an automatic confirmation to the person who submitted it; and a trigger that notifies the right staff member to follow up. Out of scope: full CRM implementation, payment processing, or scheduling automation in this version.
>
> Success looks like: zero dropped inquiries. If someone submits a form, we know about it and there is a clear next step.
>
> Constraints: we use [existing tools] and do not have budget for a new platform. Any solution needs to work within what we already have or be inexpensive and simple enough for non-technical staff to maintain.
>
> Owner: [Owner/Manager] approves the process design. [Staff Lead] owns daily maintenance.
>
> Why this matters: we have lost at least three confirmed clients in the last two months because follow-up fell through the cracks. That is real revenue and real reputation damage."

---

## A Note on These Examples

None of these required a long meeting or a formal intake process. They required someone to slow down and ask: *what does the person receiving this actually need to know to start?*

That is what CASSEROLE is for.

If a request still feels unclear after applying the framework, that is useful information too. It means the request needs another casserole pass before it goes anywhere.

---

*Use the [CASSEROLE Checklist](casserole-checklist.md) to apply this framework to your own requests.*
