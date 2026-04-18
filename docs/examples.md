# Examples — Good Neighbor Protocol

These examples show what a request looks like before and after applying the CASSEROLE framework.

The goal isn't to turn every request into a formal document. The goal is to show how much useful information is often missing — and how quickly it can be added.

---

## Example 1: The Design Request

### Before

> "Hey, can you update the homepage? The CEO wants it to feel more modern. Thanks."

### What's missing

- **Clarity:** "Feel more modern" is not actionable. What does modern mean in this context?
- **Scope:** Is this the whole homepage or a specific section? Does it include copy changes or just visuals?
- **Expectations:** What format is the deliverable — a mockup, a live update, a Figma file?
- **Safety:** Is there anything on the homepage that shouldn't change?
- **Reasonability:** When is this needed? What resources are available?
- **Ownership:** Who approves the change before it goes live?
- **Explain Why:** Why now? What's driving this?

### After (CASSEROLE applied)

> "Can you update the hero section of the homepage to feel cleaner and less cluttered? The CEO mentioned that the current version feels dated compared to our competitors — specifically [Competitor A] and [Competitor B].
>
> In scope: the hero section only (headline, subhead, and hero image). Out of scope: the navigation, footer, and any copy below the fold.
>
> Please don't touch the email signup form — we're running an A/B test on it and any changes would break the test.
>
> Deliverable: a Figma mockup for review, not a live change. Quality bar: it should look intentional and consistent with the updated brand guidelines in [link].
>
> Deadline: first draft by end of day Thursday so the CEO can review Friday morning.
>
> Owner of approval: [Name]. You should flag [Name] if you hit any blockers.
>
> Why this matters: we have an investor meeting next week and the CEO wants the site to not feel embarrassing."

---

## Example 2: The Data Request

### Before

> "Can you pull the numbers on last quarter and send them over?"

### What's missing

- **Clarity:** What numbers? Which data source?
- **Scope:** "Last quarter" — by whose calendar?
- **Expectations:** In what format? A spreadsheet? A summary email? A slide?
- **Ownership:** Who is this going to, and who needs to approve it before it goes out?
- **Explain Why:** What decision is this informing?

### After (CASSEROLE applied)

> "Can you pull our Q1 2026 revenue by region from the Salesforce dashboard (not from the spreadsheet — that one has known errors) and format it as a one-page summary table?
>
> Include: total revenue, revenue by region, and comparison to Q1 2025. Don't include individual deal data or anything at the rep level — we only need the rollup.
>
> Deliverable: a Google Doc with a clean table, sent directly to me by Wednesday at noon. I'll review and send it to the board myself — you don't need to send it anywhere else.
>
> Why this matters: we have a board call Thursday afternoon and they'll ask about regional performance. I need to be able to answer without looking surprised."

---

## Example 3: The Engineering Request

### Before

> "Can you fix the login issue? A few people are complaining."

### What's missing

- **Clarity:** What login issue? What's the actual symptom?
- **Safety:** What does a "fix" touch? Could changes affect other auth flows?
- **Expectations:** Fix in production? Or a fix that goes through staging first?
- **Reasonability:** Is there a sense of urgency, or is this a nice-to-have?
- **Explain Why:** Who is affected and how badly?

### After (CASSEROLE applied)

> "We're seeing reports from three enterprise customers that the SSO login is timing out on the first attempt. They can refresh and it works on the second try, but it's causing friction and one customer mentioned it in their renewal conversation.
>
> The issue appears to be in the SSO handoff — specifically the redirect timing after the IdP response. Our initial suspicion is a race condition but we haven't confirmed that yet.
>
> Please investigate and propose a fix. Don't push anything directly to production — any fix should go through staging and be reviewed before it ships.
>
> Don't touch the email/password login flow. That's working and we don't want to risk it.
>
> Timeline: we'd like a root cause identified by end of this week and a fix staged by early next week.
>
> Owner: [Engineering Lead] has final approval on the fix before it ships.
>
> Why this matters: this is showing up in an enterprise renewal conversation and we need it resolved before that call."

---

## A Note on These Examples

None of these examples required a long meeting or a formal intake process. They required someone to slow down for five minutes and ask: *what does the person receiving this actually need to know?*

That's what CASSEROLE is for.

---

*Use the [CASSEROLE Checklist](casserole-checklist.md) to apply this framework to your own requests.*
