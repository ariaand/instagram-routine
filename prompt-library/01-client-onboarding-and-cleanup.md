# Client Onboarding & Cleanup

Quick, single-task prompts for getting a new client in the door and the books clean — categorizing the mess, finding the errors, and building the plan to fix it.

*Prompts 1–10 of 50.*

> **Privacy first:** anonymize client/customer/vendor names before pasting, and never paste full account numbers, SSNs, or EINs. Summarize — don't dump the whole GL.

---

### 1. Categorize a batch of messy transactions

**When to use:** You have a pile of uncategorized or miscategorized bank/credit-card transactions and want a fast first-pass with the correct QBO accounts.

```text
You are an experienced U.S. bookkeeper working in QuickBooks Online for a client in the {{INDUSTRY}} industry, on a {{CASH OR ACCRUAL}} basis.

I'm going to paste a list of bank/credit-card transactions (date, description/payee, amount). For each one, suggest the most likely QBO category/account using standard chart-of-accounts naming.

Rules:
- Return a table: Date | Payee | Amount | Suggested Account | Confidence (High/Med/Low) | Note.
- Use "Med" or "Low" confidence and a clarifying question in the Note for anything ambiguous (e.g., personal vs business, owner's draw vs expense, capitalize vs expense).
- Flag any transaction that looks like an owner's draw, a transfer between accounts, a loan/credit-card payment (not an expense), or a possible personal expense.
- Do NOT invent payees or amounts. If a description is unreadable, say so.
- At the end, list any transactions you'd want me to confirm before booking.

Here are the transactions:
{{PASTE TRANSACTIONS}}
```

---

### 2. Find duplicate or double-booked transactions

**When to use:** You suspect duplicate entries inflating expenses or income during a cleanup.

```text
You are a meticulous bookkeeper reviewing a transaction register in QuickBooks Online for possible duplicates.

I'll paste a list of transactions (date, payee/description, amount, account). Identify likely duplicates and near-duplicates.

Look for:
- Identical amount + same/similar payee within a {{NUMBER}}-day window.
- A bank-feed transaction that may duplicate a manually entered bill/expense or a transfer.
- Same vendor, same amount, booked to two different accounts.

Output a table: Possible Duplicate Group | Transactions involved (date/payee/amount) | Why I flagged it | What to check in QBO. Rank groups most-to-least likely. Do not delete anything — I'll review and resolve in QBO.

Transactions:
{{PASTE TRANSACTIONS}}
```

---

### 3. Explain a reconciliation discrepancy

**When to use:** A bank or credit-card reconciliation won't tie out and you need a structured list of likely causes.

```text
You are a QuickBooks Online reconciliation specialist. Help me troubleshoot a reconciliation that is off.

Details:
- Account: {{BANK OR CREDIT CARD}}
- Statement ending date: {{DATE}}
- Statement ending balance: {{STATEMENT BALANCE}}
- QBO ending/cleared balance: {{QBO BALANCE}}
- Difference: {{DIFFERENCE AMOUNT}}
- What I've already checked: {{NOTES, OR "nothing yet"}}

Give me a prioritized checklist of the most likely causes of a difference of this size and sign, specific to QBO. Cover at minimum: uncleared/duplicate transactions, transactions dated outside the statement period, a changed/deleted previously reconciled transaction, incorrect opening balance, transfers booked twice, and bank fees/interest not yet entered. For each, tell me exactly where to look in QBO and what would confirm or rule it out. End with the single most likely cause given the amount.
```

---

### 4. Draft a cleanup plan from my notes

**When to use:** You've done a discovery review and have rough notes; you want a structured cleanup project plan.

```text
You are a bookkeeping firm owner who scopes and runs QBO cleanup/catch-up projects.

From my messy discovery notes below, produce a structured cleanup plan for a {{INDUSTRY}} client whose books cover {{TIME PERIOD / NUMBER OF MONTHS}}.

Output:
1. Summary of the current state of the books (2–3 sentences).
2. Cleanup plan organized by phase: (a) Foundation (chart of accounts, opening balances, connect feeds), (b) Reconciliations, (c) Categorization & cleanup, (d) Review & adjusting entries, (e) Handoff/close. Under each phase list concrete tasks.
3. A list of open questions / info I need from the client before I can finish.
4. A rough estimate of effort by phase (Low/Med/High) so I can price it.

Flag anything that may need the client's CPA (e.g., prior-year adjustments, tax elections, depreciation method).

My notes:
{{PASTE DISCOVERY NOTES}}
```

---

### 5. Build a client document-request list

**When to use:** A new client just signed and you need the standard "send me these" list, tailored to their situation.

```text
You are onboarding a new bookkeeping client in QuickBooks Online. Generate a clear, friendly document-and-access request list I can send them.

Client context:
- Industry: {{INDUSTRY}}
- Entity type: {{SOLE PROP / LLC / S-CORP / OTHER}}
- Services I'm providing: {{e.g., monthly bookkeeping + cleanup of prior 8 months}}
- Has payroll: {{YES/NO}}
- Has sales tax obligations: {{YES/NO}}

Produce a categorized checklist (Access, Bank & Credit, Sales/Revenue, Expenses & Bills, Payroll, Tax, Prior Records). For each item, one short line on why I need it. Use plain language a non-accountant understands. Add a note reminding them NOT to send full account numbers or passwords over email and to use our secure portal instead. Keep it skimmable.
```

---

### 6. Suggest a chart-of-accounts cleanup

**When to use:** The QBO chart of accounts is bloated, duplicated, or miscategorized and you want a tidy-up plan.

```text
You are a QuickBooks Online expert standardizing a client's chart of accounts.

I'll paste the current chart of accounts (account name, type/detail type). The client is in the {{INDUSTRY}} industry.

Recommend a cleanup:
- Identify duplicate or overlapping accounts to merge.
- Identify accounts with the wrong account type or detail type.
- Identify vague/junk accounts ("Misc", "Ask My Accountant" buildup, "Uncategorized") and suggest where their activity likely belongs.
- Suggest a clean, industry-appropriate structure (grouping income, COGS, expenses).

Output a table: Current Account | Issue | Recommended Action (Keep / Merge into X / Rename / Reclass type / Make inactive) | Reason. Don't merge anything with reconciled history without flagging the risk. End with 3–5 accounts you'd suggest ADDING for this industry.

Current chart of accounts:
{{PASTE CHART OF ACCOUNTS}}
```

---

### 7. Spot red flags on a balance sheet

**When to use:** You want a fast second set of eyes on a balance sheet during onboarding or cleanup review.

```text
You are a senior bookkeeper reviewing a client's QuickBooks Online Balance Sheet for red flags before I take over the books.

I'll paste a Balance Sheet (accrual basis unless I note otherwise) for {{CLIENT/INDUSTRY}} as of {{DATE}}.

Flag anything that suggests an error or cleanup need, including but not limited to:
- A non-zero or large Opening Balance Equity balance.
- Negative balances where they shouldn't be (e.g., negative bank, negative A/R, negative liabilities).
- Undeposited Funds sitting with a stale balance.
- Suspense/clearing/Uncategorized Asset balances.
- Loan/credit-card balances that look off or unreconciled.
- Accumulated depreciation missing or out of step with fixed assets.
- Retained earnings or owner's equity that looks unusual.

Output: Flag | Account & Amount | Why it's a concern | What to investigate in QBO. Rank by severity. Note which items may need the client's CPA. This is a review for cleanup purposes, not tax advice.

Balance Sheet:
{{PASTE BALANCE SHEET}}
```

---

### 8. Draft onboarding questions for an industry

**When to use:** You're onboarding a client in an industry you want to ask smart, specific questions about.

```text
You are an expert bookkeeper who specializes in serving {{INDUSTRY}} businesses.

Write me a set of onboarding discovery questions tailored to this industry that go beyond generic bookkeeping intake. Cover how this type of business typically makes money, how it gets paid (and through what platforms/processors), its common COGS and expense categories, inventory/job-costing considerations if relevant, sales tax exposure, common owner-comingling issues, and the bookkeeping mistakes this industry usually makes.

Group the questions under clear headings. Keep each question short and answerable by a busy owner. Aim for 20–30 questions total. Add a short "watch out for" note at the end listing the 3 things I should double-check first in this industry's books.
```

---

### 9. Summarize prior financials

**When to use:** You inherited prior-period financials and want a quick, plain-English read before the kickoff call.

```text
You are a bookkeeper preparing for a client kickoff call. Read the financials I paste and give me a concise summary.

The client is in {{INDUSTRY}}; the statements cover {{PERIOD}} on a {{CASH/ACCRUAL}} basis.

Provide:
1. A 3–4 sentence plain-English summary of how the business is doing (revenue trend, profitability, cash position).
2. Top 5 expense categories by size and anything that looks unusually high/low for this industry.
3. Anything that looks like a bookkeeping error vs. a real business issue (be clear which is which).
4. 3–5 smart questions I should ask the client based on what I see.

Be specific and cite the numbers you're reacting to. Don't give tax advice — flag tax-flavored items for their CPA.

Financials:
{{PASTE P&L AND/OR BALANCE SHEET}}
```

---

### 10. Create a catch-up project task list

**When to use:** You sold a catch-up engagement and need a month-by-month task list to actually execute it.

```text
You are running a QBO catch-up bookkeeping project. Build me an execution task list.

Scope:
- Client industry: {{INDUSTRY}}
- Months behind / period to catch up: {{e.g., Jan–Aug 2026}}
- Accounts to reconcile each month: {{LIST, e.g., 1 checking, 2 credit cards}}
- Known complications: {{e.g., Stripe payouts, payroll via Gusto, sales tax, owner draws}}

Produce a month-by-month task list (one block per month) covering: import/verify transactions, categorize, reconcile each account, record recurring/adjusting entries, and a month-end review check. Then add a "project-level" section for one-time tasks (opening balances, chart of accounts setup, prior-year tie-out). Format as checkboxes I can drop into my project tool. Flag steps where I should pause and confirm with the client or their CPA.
```
