# Month-End Close & Reconciliation

Quick, single-task prompts for the recurring monthly grind — close checklists, reconciliations that won't tie, adjusting entries, variance reviews, and the client summary that wraps it all up.

*Prompts 11–20 of 50.*

> **Privacy first:** anonymize client/customer/vendor names before pasting, and never paste full account numbers, SSNs, or EINs. Summarize the numbers you need — don't dump the whole GL.

---

### 1. Build a month-end close checklist

**When to use:** You want a tailored, repeatable close checklist for a specific client instead of a generic one.

```text
You are an experienced U.S. bookkeeper who runs monthly closes in QuickBooks Online. Build me a month-end close checklist tailored to this client.

Client context:
- Industry: {{INDUSTRY}}
- Accounting basis: {{CASH OR ACCRUAL}}
- Bank/credit-card accounts to reconcile: {{LIST, e.g., 1 checking, 2 credit cards}}
- Has payroll: {{YES/NO — and provider if yes}}
- Has sales tax: {{YES/NO — and state(s)}}
- Other complications: {{e.g., Stripe payouts, inventory, loans, owner draws}}

Produce a checklist organized in the order I'd actually work: (1) Pre-close data gathering, (2) Reconciliations, (3) Categorization & cleanup, (4) Adjusting/recurring journal entries, (5) Review (P&L, Balance Sheet, AR/AP aging), (6) Reporting & client communication, (7) Lock/close the period. Format as checkboxes I can reuse every month. For any step that depends on this client's specifics above, add a short note. Flag any step that may need their CPA.
```

---

### 2. Suggest recurring and adjusting journal entries

**When to use:** You want a list of likely accruals, prepaids, and depreciation entries for the month so nothing gets missed.

```text
You are a bookkeeper preparing month-end adjusting entries in QuickBooks Online for a {{INDUSTRY}} client on an accrual basis, for {{MONTH/YEAR}}.

Based on the context I give you, suggest the recurring and adjusting journal entries I likely need this month. Cover at minimum: prepaid expenses to amortize (insurance, software, rent), accrued expenses (unpaid wages, interest, utilities), depreciation, deferred/unearned revenue, and any monthly accruals specific to this industry.

Context / what I know:
{{NOTES — e.g., paid annual insurance of $X in Jan, financed equipment, prepaid rent, etc.}}

For each suggested entry, give me: Description | Debit account | Credit account | How to calculate the amount | Frequency (one-time/monthly). Use standard QBO chart-of-accounts naming. Where you don't have enough info to compute an amount, say exactly what number you need from me. Do not give tax advice — flag depreciation method/useful-life decisions for the client's CPA.
```

---

### 3. Troubleshoot a reconciliation that won't tie out

**When to use:** A bank or credit-card reconciliation is off by an amount and you want a prioritized list of likely causes.

```text
You are a QuickBooks Online reconciliation specialist. Help me find why a reconciliation is off.

Details:
- Account: {{BANK OR CREDIT CARD}}
- Statement period: {{START}} to {{END}}
- Statement ending balance: {{STATEMENT BALANCE}}
- QBO cleared balance: {{QBO BALANCE}}
- Difference (amount and sign): {{DIFFERENCE}}
- What I've already checked: {{NOTES, OR "nothing yet"}}

Give me a prioritized checklist of likely causes for a difference of this size and sign, specific to QBO: uncleared or duplicate transactions, transactions dated outside the statement window, a previously reconciled transaction that was edited or deleted, a wrong opening/beginning balance, transfers entered twice or as two expenses, and bank fees/interest not yet recorded. For each, tell me exactly where to look in QBO and what would confirm or rule it out. End with the single most likely cause given the amount and sign.
```

---

### 4. Draft a month-end client summary

**When to use:** The close is done and you need a clear, plain-English summary email/report for the client.

```text
You are a bookkeeper writing the month-end summary for a client who is a busy business owner, not an accountant. Tone: {{FRIENDLY/PROFESSIONAL — pick or describe}}.

Client: {{CLIENT_NAME or "Client A"}}, industry {{INDUSTRY}}, month {{MONTH/YEAR}}.

Using the figures I paste below, write a short summary covering:
1. Headline: revenue, expenses, and net profit for the month (with the numbers).
2. How that compares to last month / prior period (up or down, and by roughly how much).
3. 2–3 things worth noting in plain English (a big expense, a slow-paying customer, a strong month).
4. Anything I need from them or any open question (in a clear "Action needed" line, or "Nothing needed this month").

Keep it under ~200 words, skimmable, no jargon. Don't give tax advice. End with a warm sign-off placeholder [Your name].

Figures:
{{PASTE KEY NUMBERS — revenue, expenses, net income, this month vs last; AR/AP highlights}}
```

---

### 5. Run a month-over-month variance analysis

**When to use:** You want to understand and explain why the numbers moved versus the prior period.

```text
You are a bookkeeper doing a month-over-month variance review in QuickBooks Online for a {{INDUSTRY}} client.

I'll paste a comparative P&L (current month vs prior month, or vs same month last year — I'll tell you which). Identify the most significant variances and help me explain them.

Output a table: Account | Current | Prior | $ Change | % Change | Likely explanation / what to verify. Sort by largest absolute dollar change. Then write a short "what this means" paragraph in plain English. Distinguish between (a) normal business fluctuation, (b) timing differences, and (c) things that look like a possible bookkeeping error I should investigate. Don't speculate beyond the data — where you need more info, say so.

Comparative P&L:
{{PASTE COMPARATIVE P&L}}
```

---

### 6. Flag anomalies in a P&L

**When to use:** You want a fast sanity check on a profit & loss statement before you finalize the close.

```text
You are a senior bookkeeper reviewing a QuickBooks Online Profit & Loss for {{CLIENT/INDUSTRY}} for {{PERIOD}} ({{CASH/ACCRUAL}}) before I close the month.

Scan the P&L I paste and flag anything that looks like an error or needs a second look, including: negative balances in accounts that shouldn't be negative, expenses booked to income (or vice versa), unusually large "Miscellaneous"/"Uncategorized"/"Ask My Accountant" balances, a category that's wildly different from a normal month, duplicate-looking expense lines, missing expected costs (e.g., no rent or no payroll for a business that should have them), and anything inconsistent with the {{INDUSTRY}} norm.

Output: Flag | Account & Amount | Why it's odd | What to check in QBO. Rank by how likely it is to be a real error. This is a bookkeeping review, not tax advice.

P&L:
{{PASTE P&L}}
```

---

### 7. Split a POS / Stripe / merchant payout

**When to use:** A lump payout (Stripe, Square, PayPal, etc.) hit the bank and you need to break it into sales, fees, and refunds correctly.

```text
You are a bookkeeper recording merchant-processor payouts in QuickBooks Online. Help me break a lump deposit into its correct components.

Processor: {{STRIPE / SQUARE / PAYPAL / OTHER}}
Net amount that hit the bank: {{NET DEPOSIT}}
Accounting basis: {{CASH/ACCRUAL}}

I'll paste the payout detail (gross sales, processing fees, refunds, chargebacks, etc.). Show me how to record this in QBO so the bank deposit reconciles to the net amount. Give me the journal entry or deposit breakdown: line | account (gross sales to income, fees to merchant fee expense, refunds, etc.) | debit/credit | amount. Confirm the lines net to the actual deposit. If sales tax is collected through the processor, flag how that should be handled separately. Note anything I should verify against the QBO bank feed.

Payout detail:
{{PASTE PAYOUT BREAKDOWN}}
```

---

### 8. Review AR and AP aging

**When to use:** You want a quick read on what's overdue and what to flag to the client at month-end.

```text
You are a bookkeeper reviewing accounts receivable and/or accounts payable aging in QuickBooks Online for {{CLIENT_NAME or "Client A"}} as of {{DATE}}.

I'll paste an AR aging and/or AP aging summary (by customer/vendor and bucket: current, 1–30, 31–60, 61–90, 90+). Give me:
1. AR: total outstanding, total overdue (31+ days), and the specific customers/amounts I should flag to the client for collection. Note any stale or possibly uncollectible balances.
2. AP: total owed, anything overdue, and any bills that look like they may be duplicates or already paid.
3. Anything that looks like a bookkeeping issue (e.g., a credit balance, a negative receivable, a very old open item that may need writing off — flagged, not actioned).
4. A short "talk to the client about" list in plain English.

Anonymize is fine — use Customer A, Vendor 1, etc. This is a review, not collection or legal advice.

Aging:
{{PASTE AR AND/OR AP AGING}}
```

---

### 9. Tie out the sales tax liability

**When to use:** You want to sanity-check the sales tax payable balance against what was collected before filing/remitting.

```text
You are a bookkeeper helping reconcile the sales tax liability in QuickBooks Online for a {{INDUSTRY}} client in {{STATE}} for the period {{PERIOD}}.

I'll give you: the sales tax collected per the QBO sales tax report, the current balance in the Sales Tax Payable account, and any payments/remittances made during the period. Help me tie these out:
1. Walk through the expected math: prior balance + tax collected − remittances = expected ending payable.
2. Compare to the actual QBO Sales Tax Payable balance and quantify any difference.
3. List likely causes of a difference (tax recorded to the wrong account, manual JEs, a payment not applied against the liability, taxable vs non-taxable misclassification, rounding).
4. Tell me where to check each in QBO.

Numbers:
{{PASTE: prior payable balance, tax collected this period, remittances, current payable balance}}

Important: this is a reconciliation aid only. Filing positions, nexus, and taxability determinations go to the client's CPA or tax advisor — flag anything that crosses that line.
```

---

### 10. Build a year-end and 1099 prep checklist

**When to use:** It's year-end (or close) and you need the wrap-up and 1099 task list for a client.

```text
You are a bookkeeper preparing a client's books for year-end and 1099 filing in QuickBooks Online.

Client context:
- Industry: {{INDUSTRY}}
- Entity type: {{SOLE PROP / LLC / S-CORP / PARTNERSHIP}}
- Tax year: {{YEAR}}
- Has contractors who may need 1099-NEC: {{YES/NO}}
- Has payroll: {{YES/NO}}

Produce two checklists:
1. Year-end close prep — reconcile all accounts through December, clear Undeposited Funds, confirm loan balances to statements, review fixed assets/depreciation, zero out or explain Opening Balance Equity, review owner draws/contributions, and prepare a clean trial balance for the CPA.
2. 1099 prep — identify which vendors likely need a 1099-NEC (threshold, payment type, exclude credit-card payments), confirm W-9s on file, verify vendor TIN/address completeness, and the steps to run 1099s in QBO.

Format as checkboxes. For each 1099 judgment call (who's reportable, contractor vs employee classification), flag it as a decision to confirm with the client's CPA — do not make the final determination. This is prep support, not tax advice.
```
