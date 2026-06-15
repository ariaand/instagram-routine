# AI Discovery Call Assistant

**Bonus — Balance Operations Co. AI Bookkeeper Toolkit™**

## What this is / who it's for

A system to run great discovery calls and turn your messy call notes into three
deliverables in minutes: a **scope of work**, a **proposal draft**, and a **follow-up
email**. For bookkeepers who want to show up prepared, capture the right information, and
follow up the same day — before the prospect goes cold.

Three parts:
1. **Discovery call script** — the questions that surface scope, urgency, and fit.
2. **Note-taking template** — capture answers in a structure the AI can use.
3. **AI prompts** — turn raw notes into a scope of work, proposal, and follow-up.

> Pairs with **Module 4 (Cleanup Project Agent)** and **Module 6 (Proposal Generator)**:
> this captures the inputs; those two build the full priced engagement.

---

## Part 1 — The Discovery Call Script

Keep it conversational — these are prompts, not an interrogation. Aim for ~30 minutes.

### Open (2 min)
- "Before we dive in — what made you start looking for a bookkeeper right now?"
  *(This surfaces the real urgency and the emotional driver.)*

### Understand the business (5 min)
- What does the business do, and how long have you been running it?
- Entity type and roughly what revenue are you doing?
- How many people — employees, contractors?

### Current state of the books (10 min)
- What are you using today (software), and who's been doing the books?
- When were the books last reconciled or closed?
- How many bank and credit-card accounts are involved?
- Payroll? Sales tax? In which states?
- On a scale of 1–10, how confident are you that your numbers are accurate today?
- What's the messiest part, in your opinion?

### Goals & pain (5 min)
- What's this costing you right now — time, stress, missed deductions, bad decisions?
- What would "handled" look like 6 months from now?
- Any hard deadlines? (tax filing, loan, sale, investor)

### Logistics & fit (5 min)
- How do you like to communicate? How responsive can you be with documents/questions?
- Have you worked with a bookkeeper before? What worked / didn't?
- What's your budget comfort zone for getting this solved? *(Optional but useful.)*

### Close (3 min)
- "Here's what I think you need…" (high level — don't quote on the spot).
- "I'll put together a proposal and have it to you by {{DATE}}. Sound good?"
- Confirm best email and next step.

---

## Part 2 — Note-Taking Template

Fill this during/right after the call. Bullet fragments are fine — the AI cleans it up.

```text
DISCOVERY CALL NOTES
Prospect / business: {{}}
Date: {{}}
Industry: {{}}   Entity: {{}}   Revenue: {{}}   Team size: {{}}

WHY NOW (urgency/driver): {{}}
DEADLINE (if any): {{}}

CURRENT BOOKS:
- Software / who does it: {{}}
- Last reconciled / closed: {{}}
- Accounts (bank/CC/loans): {{}}
- Payroll: {{}}   Sales tax (states): {{}}
- Confidence in numbers (1–10): {{}}
- Messiest part: {{}}

GOALS / "handled" looks like: {{}}
PAIN / what it's costing: {{}}

LOGISTICS:
- Communication & responsiveness: {{}}
- Prior bookkeeper experience: {{}}
- Budget signal: {{}}

MY READ:
- Likely needs: {{cleanup? monthly? both?}}
- Risks/flags: {{}}
- Fit (good/maybe/no): {{}}
```

**AI prompt — clean up raw notes into a structured brief:**
```text
You are a senior bookkeeper. Turn these rough discovery-call notes into a clean,
structured brief: business profile, why-now/urgency, current state of the books, goals &
pain, logistics, and a short "my read" with likely services (cleanup / monthly / both),
risks, and any missing info to confirm. Don't invent details. Notes:
{{PASTE NOTES}}
```

---

## Part 3 — Turn notes into deliverables

### (a) Scope of Work
```text
You are a senior bookkeeper. From these discovery-call notes, draft a Scope of Work for a
{{cleanup / monthly / cleanup-then-monthly}} engagement. Include: engagement summary,
what's IN scope (specific), what's OUT of scope (tax filing/advice, prior-year amendments,
audit, anything beyond the period), client responsibilities, and a definition of done.
Keep it client-ready but precise. Flag anything needing a CPA. Label assumptions
"ASSUMPTION:". Notes:
{{PASTE NOTES OR CLEANED BRIEF}}
```
> For a fully scoped + priced cleanup, feed this into **Module 4**. For a monthly
> engagement, feed into **Module 6**.

### (b) Proposal Draft
```text
You are a senior bookkeeper writing a client-ready proposal from these discovery notes.
Warm, confident, benefit-led. Include: a short intro referencing their goal, "what's going
on today" in plain English, "what we'll do," a pricing section with {{2–3}} options (mark
a recommended one), timeline, what you need from them, simple terms, and a clear call to
action. Use {{FIRM_NAME}}. Mark any price I haven't given as "{{PRICE — confirm}}". Notes:
{{PASTE NOTES OR BRIEF}}
```

### (c) Follow-up Email
```text
You are a bookkeeper writing a same-day follow-up email after a discovery call. Warm,
brief, professional. Recap what you heard (their goal + main pain in 1–2 lines), state the
recommended next step, note that a proposal is coming by {{DATE}}, and invite questions.
Use {{FIRM_NAME}} and {{YOUR_NAME}}. Notes:
{{PASTE NOTES OR BRIEF}}
```

---

## Worked example

**Sample notes (rough):**
```text
Prospect: Brightwave Café, owner Sam. Café + retail beans. Single-member LLC, TX. ~$640k.
6 employees. WHY NOW: CPA asked for clean 2024 books, Sam embarrassed books are a mess.
DEADLINE: 2024 return not filed. Software QBO Simple Start, old bookkeeper quit in March.
Last reconciled checking ~Feb 2024, CC never. 1 checking + 1 CC. Payroll Gusto. Sales tax
TX. Confidence: 3/10. Messiest: Toast deposits + uncategorized pile. Goal: trust numbers,
file on time. Pain: no idea if profitable. Budget: didn't say, seems value-focused. Read:
needs cleanup THEN monthly. Risks: deadline, ~$31k uncategorized. Fit: good.
```

**→ Scope of Work (excerpt):** Cleanup of Jan 2024–present (cash basis): reconcile
checking + credit card, clear ~$31k uncategorized, split Toast deposits, map Gusto
payroll, tie TX sales tax, deliver CPA-ready 2024. OUT: tax filing/advice (→ CPA),
amendments, inventory. Done = reconciled, $0 uncategorized, 2024 CPA-ready.

**→ Proposal Draft (excerpt):** "Hi Sam — you mentioned you need clean 2024 books for your
CPA and want to actually trust your numbers. Here's the plan… Options: Essentials
{{PRICE — confirm}} / **Recommended {{PRICE — confirm}}** / Done-for-You + monthly…"

**→ Follow-up Email (excerpt):**
> **Subject:** Great talking with you — next steps for Brightwave
>
> Hi Sam, really enjoyed our chat. To recap: you want clean 2024 books for your CPA and to
> stop guessing whether you're profitable. I'd suggest a focused cleanup to get current,
> then simple monthly bookkeeping so you never fall behind again. I'll have your proposal
> over by Thursday. Any questions in the meantime, just reply. — Aria, Balance Operations Co.

---

## How to run it end-to-end
1. **Before the call:** open the script + note template.
2. **On the call:** take notes in the template.
3. **Right after:** run the cleanup-notes prompt → then scope, proposal, follow-up prompts.
4. **Same day:** send the follow-up email (refine in **Module 3** if you like).
5. **Finalize pricing:** feed the scope into **Module 4** (cleanup) and/or **Module 6**
   (monthly) for proper pricing, then send the polished proposal.

> The AI drafts from your notes — it never invents facts or prices. You confirm everything
> before it goes out. Nothing here is tax advice; refer tax questions to the client's CPA.
