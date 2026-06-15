# Client Communication & Emails

Quick, single-task prompts for the words part of the job — chasing documents, reminding about payments, explaining the numbers, and keeping clients warm from welcome to offboarding.

*Prompts 21–30 of 50.*

> **Privacy first:** anonymize names before pasting any context, and never paste full account numbers, SSNs, or passwords. The AI drafts the email — you read it before it sends.

---

### 1. Request missing documents or info

**When to use:** You're blocked waiting on receipts, statements, or answers and need a polite-but-clear nudge.

```text
You are writing on behalf of a U.S. bookkeeping firm to a client. Tone: friendly, clear, professional — never naggy. Match this voice if I paste a sample below.

Write a short email requesting the documents/info I need to keep their books moving. Use a clear bulleted list so it's easy to act on.

Details:
- Client name: {{CLIENT_NAME}}
- What I'm working on: {{e.g., May close, cleanup, year-end}}
- What I need from them: {{LIST — e.g., March bank statement, 3 receipt clarifications, confirm a $X charge}}
- Deadline / why it matters: {{DATE or reason}}

Keep it under ~150 words. Open warmly, list the items, give a clear deadline, and offer to hop on a quick call if easier. Add a one-line reminder to upload to our secure portal rather than emailing sensitive documents. End with a sign-off placeholder [Your name].
```

---

### 2. Send a late-payment reminder

**When to use:** A client's invoice (your fee) or one of their customer invoices is overdue and you need a reminder, with an escalation path.

```text
You are writing a payment reminder on behalf of a bookkeeping firm. Tone: polite, professional, firm — protect the relationship but be clear money is owed.

Details:
- Who owes / what for: {{e.g., client owes my monthly fee / client's customer owes an invoice}}
- Amount: {{AMOUNT}}
- Original due date: {{DATE}}
- Days overdue: {{NUMBER}}
- Late fee policy, if any: {{DESCRIBE or "none"}}

Write THREE versions at escalating firmness so I can pick based on how overdue it is:
1. Gentle nudge (first reminder, recently past due).
2. Firm follow-up (a couple weeks past due — reference the original due date and any late fee).
3. Final notice (significantly overdue — clear about next steps, e.g., pausing work, while staying professional).

Each under ~120 words with a clear payment CTA. Add a short note advising me which version fits which situation. End each with [Your name].
```

---

### 3. Send the monthly report email

**When to use:** You've finished the close and want a clean cover email to deliver the monthly reports.

```text
You are a bookkeeper sending a client their monthly financial reports. Tone: warm, professional, plain-English (the client is a business owner, not an accountant).

Details:
- Client: {{CLIENT_NAME}}, industry {{INDUSTRY}}
- Month: {{MONTH/YEAR}}
- Reports attached: {{e.g., P&L, Balance Sheet, AR aging}}
- 2–3 highlights or notes I want to surface: {{NOTES — e.g., revenue up, one big customer slow to pay, nothing unusual}}
- Anything I need from them: {{ACTION or "nothing this month"}}

Write a short cover email: a warm opener, a 2–3 bullet plain-English summary of how the month went, what's attached, any action needed (clearly labeled), and an offer to walk through it on a call. Under ~180 words. No jargon, no tax advice. End with [Your name].
```

---

### 4. Follow up after a discovery call

**When to use:** You just had a prospect call and want to send a recap that moves them toward a proposal.

```text
You are a bookkeeping firm owner following up after a discovery call with a prospect. Tone: professional, helpful, lightly persuasive — not pushy.

What I learned on the call:
{{NOTES — their business, pain points, what they need, what's behind, timeline, budget signals}}

Write a follow-up email that: (1) thanks them and shows I listened by reflecting back their specific situation and goals, (2) briefly frames how I'd help (in their words, not jargon), (3) tells them the next step (I'll send a proposal by {{DATE}} / let's book a follow-up), and (4) keeps momentum without being salesy. Under ~180 words. End with [Your name]. If anything they mentioned is a tax or legal question, include one line noting I'll flag it to a CPA/attorney rather than advising on it myself.
```

---

### 5. Announce a price increase

**When to use:** You're raising a client's rate and need to communicate it confidently and keep them.

```text
You are a bookkeeping firm owner notifying an existing client of a price increase. Tone: confident, appreciative, professional — no apologizing, no over-explaining.

Details:
- Client: {{CLIENT_NAME}}
- Current fee: {{CURRENT}} → New fee: {{NEW}}
- Effective date: {{DATE}}
- Reasons (pick what's true): {{e.g., scope has grown, first increase in X years, added services, rising costs}}
- Anything I'm adding/improving for them: {{NEW VALUE or "none"}}

Write a short, warm email that states the new rate and effective date plainly, briefly grounds it in value (not cost-cutting), thanks them for the relationship, and invites questions. Don't bury the number or over-justify. Under ~160 words. End with [Your name]. Give me one alternate opening line in case the relationship is sensitive.
```

---

### 6. Resolve an "Ask My Accountant" item

**When to use:** You have transactions parked in "Ask My Accountant" and need a clean clarification email to the client.

```text
You are a bookkeeper who needs the client to clarify some transactions before you can categorize them correctly in QuickBooks Online. Tone: friendly, concise, easy to answer fast.

I'll paste a short list of transactions I have questions about (date, payee, amount). For each, the client just needs to tell me what it was for or how to treat it.

Write an email that lists each one with a simple, specific question (e.g., "Was this a business meal, and who was it with?" / "Is this a personal expense or business?"). Make it skimmable and quick to answer — number the items so they can reply "1: business, 2: personal," etc. Keep my questions plain-English; don't make them feel quizzed. Under ~160 words plus the list. End with [Your name].

Transactions:
{{PASTE ITEMS}}
```

---

### 7. Welcome a new client

**When to use:** A client just signed and you want to kick off the relationship warmly and set expectations.

```text
You are a bookkeeping firm owner sending a welcome email to a brand-new client. Tone: warm, confident, organized — make them feel they made a great decision.

Details:
- Client: {{CLIENT_NAME}}, industry {{INDUSTRY}}
- Services they signed up for: {{e.g., monthly bookkeeping + 6-month cleanup}}
- First steps for them: {{e.g., accept QBO invite, upload docs to portal, book kickoff call}}
- How/when we communicate: {{e.g., monthly reports by the 15th, email for questions}}

Write a welcome email that: thanks them and reaffirms why working together will help, lays out the first 2–3 things they need to do (clear and numbered), sets expectations for how and when we'll work together, and tells them how to reach me. Include a one-line secure-data reminder (use the portal, don't email sensitive docs). Warm but organized, under ~200 words. End with [Your name].
```

---

### 8. Follow up on a proposal

**When to use:** You sent a proposal and haven't heard back; you want a nudge that doesn't feel desperate.

```text
You are a bookkeeping firm owner following up on a proposal a prospect hasn't responded to. Tone: confident, helpful, no desperation.

Details:
- Prospect: {{NAME}}
- Proposal sent: {{DATE}} ({{DAYS}} ago)
- What I proposed: {{e.g., $X/mo monthly bookkeeping + cleanup}}
- Any context: {{e.g., they were comparing options, busy season, etc.}}

Write a short follow-up that: gently reopens the conversation, restates one concrete benefit/outcome they'd get, makes it easy to say where they stand (offer to answer questions or adjust scope), and includes a soft deadline or next step without pressure. Under ~130 words. Give me 2 versions — one slightly warmer/relationship-led, one slightly more direct/decision-led. End each with [Your name].
```

---

### 9. Offboard a departing client

**When to use:** A client is leaving (or you're parting ways) and you want a professional, complete handoff email.

```text
You are a bookkeeping firm owner offboarding a client who is leaving. Tone: gracious, professional, leave-the-door-open — no matter the reason.

Details:
- Client: {{CLIENT_NAME}}
- Last period I'm handling: {{PERIOD}}
- What I'm handing off: {{e.g., QBO access transfer, final reports, document return}}
- Anything outstanding: {{e.g., final invoice, pending docs, the in-progress month}}

Write a professional offboarding email that: thanks them sincerely for the relationship, clearly states what I'll deliver and by when (final reports, access handoff, records), lists anything I need from them to wrap up cleanly (e.g., final payment, access changes), confirms the effective end date, and leaves the door open to return. Add a short checklist of the handoff items at the bottom. Under ~200 words. End with [Your name].
```

---

### 10. Turn a financial summary into plain-English talking points

**When to use:** You have the numbers and need to explain them to a non-accountant client on a call or in a note.

```text
You are a bookkeeper who needs to explain a client's financials to them in plain English. The client is a {{INDUSTRY}} business owner with no accounting background.

I'll paste a financial summary (P&L figures, key balances, trends). Translate it into clear talking points I can use on a call or in an email.

Give me:
1. The big picture in 2–3 sentences (are they making money, is cash okay, what's the trend) — no jargon.
2. 3–5 bullet talking points, each explaining one number in everyday language and why it matters to them.
3. 1–2 plain questions or suggestions I can raise (e.g., a rising cost to watch, a slow-paying customer).

Avoid accounting terms unless you immediately explain them. Be encouraging but honest. No tax advice — if a tax question comes up, note I'll route it to their CPA.

Summary:
{{PASTE FINANCIAL SUMMARY}}
```
