# QuickBooks Cleanup Toolkit

**Bonus — Balance Operations Co. AI Bookkeeper Toolkit™**

## What this is / who it's for

A complete, standalone system for diagnosing and fixing a messy QuickBooks Online (QBO)
file. It's built for professional bookkeepers who take on cleanup/catch-up work — the
highest-margin service in the business and the easiest to do inconsistently.

Three parts:
1. **Diagnostic questionnaire** — sent to the client to understand the mess.
2. **Audit checklist** — your systematic review of the file to find every problem.
3. **Cleanup workflow** — the phased process to fix it, in the right order.

> Use this alongside **Module 4 (Cleanup Project Agent)** to scope, price, and propose
> the engagement once your audit is done. This toolkit is the *technical* how-to; Module 4
> is the *sell-it* layer.

---

## Part 1 — Diagnostic Client Questionnaire

Send this before you start, so your audit is informed. (Pairs with Module 1's broader
onboarding questionnaire — this one is cleanup-specific.)

1. How far back do you think the books need fixing? (months/years)
2. When were the books last reconciled or reviewed by a professional?
3. Who's been doing the bookkeeping, and what's their experience level?
4. What accounting software/version and plan are you on?
5. Have you switched software or charts of accounts at any point? When?
6. Are all bank/credit-card accounts connected to the bank feed?
7. Are there any accounts NOT in QBO that should be? (PayPal, Stripe, a card, a loan)
8. Do you run payroll? Through what? Is it recorded in QBO?
9. Do you collect/file sales tax? In which states?
10. Have business and personal funds ever been mixed?
11. Is there a tax return filed for the most recent year? Does it match the books?
12. What's driving the cleanup — a deadline, a loan, a sale, peace of mind?
13. Anything you already know is wrong or worried about?

**AI prompt — summarize the questionnaire into a cleanup brief:**
```text
You are a senior bookkeeper. Summarize these cleanup-client questionnaire answers into a
one-page brief: (1) likely scope (period + accounts), (2) the top risks to investigate,
(3) what to confirm during the file audit, (4) questions still unanswered. Be concise and
specific. Flag anything needing a CPA. Answers:
{{PASTE ANSWERS}}
```

---

## Part 2 — The QBO Audit Checklist

Work top to bottom. Note findings as you go — they become your cleanup scope.

### A. Company setup & chart of accounts
- [ ] Confirm fiscal year, accounting method (cash/accrual), and tax form match the entity
- [ ] Review chart of accounts for **duplicates** (e.g., "Meals", "Meals & Ent", "Meal Exp")
- [ ] Look for vague catch-alls ("Misc", "Other Expense") hiding real activity
- [ ] Check for accounts with wrong **type** (e.g., an expense set up as an asset)
- [ ] Inactive/duplicate accounts that should be merged

### B. Cash accounts (the foundation)
- [ ] Every bank & credit-card account connected and feeding
- [ ] **Reconciliation status** for each account — when was each last reconciled?
- [ ] Reconciliation discrepancies report — any forced/unexplained differences?
- [ ] Outstanding/uncleared transactions that are stale (months old)
- [ ] **Undeposited Funds** balance — should usually be near $0; investigate a buildup

### C. Categorization integrity
- [ ] Balance in **Uncategorized Income / Uncategorized Expense**
- [ ] Balance in **"Ask My Accountant"** / "Ask My Bookkeeper"
- [ ] Transfers between accounts mis-booked as income or expense
- [ ] Owner personal spending booked as business expense (should be Owner's Draw)
- [ ] Duplicate transactions (bank feed + manual entry of the same item)

### D. Balance sheet red flags
- [ ] **Opening Balance Equity** — should be $0 after setup; investigate any balance
- [ ] Negative asset balances (e.g., negative bank, negative inventory)
- [ ] **Accounts Receivable / Payable** on a cash-basis return that shouldn't have balances
- [ ] Old, uncleared **AR/AP aging** items (paid invoices still showing open, etc.)
- [ ] **Retained Earnings** vs. prior-year tax return — do they tie?
- [ ] Loan balances match lender statements; interest vs. principal split correctly

### E. Payroll
- [ ] Payroll recorded as detailed wages/taxes — not lump-sum transfers
- [ ] **Payroll liabilities / clearing** accounts reconcile to the payroll provider
- [ ] Payroll tax payments categorized correctly (not as expense twice)

### F. Sales tax
- [ ] **Sales Tax Payable** ties to what was actually filed/remitted
- [ ] Sales tax collected is a liability, not booked into income

### G. Tie-out & cutoff
- [ ] Prior-year ending balances match the filed tax return (beginning balances)
- [ ] Identify a clean **cutoff date** from which monthly bookkeeping will proceed

**AI prompt — turn audit findings into a prioritized issue list:**
```text
You are a senior bookkeeper reviewing a QBO cleanup. Here are my raw audit findings.
Produce a prioritized issue table: Issue | Why it matters | Severity (High/Med/Low) |
Est. effort | Fix phase (1 Foundation / 2 Categorize / 3 Verify). Then list anything that
needs the client or a CPA. Do not invent issues not in my notes. Findings:
{{PASTE YOUR AUDIT NOTES}}
```

---

## Part 3 — The Cleanup Workflow (phased)

Always fix in this order. Cash first, refinements last.

### Phase 1 — Foundation (get cash right)
1. Connect/repair all bank & credit-card feeds; import any missing history.
2. Verify beginning balances tie to the last filed tax return.
3. Reconcile every bank and credit-card account, oldest month forward, to statements.
4. Resolve reconciliation discrepancies before moving on.

### Phase 2 — Categorize & correct
5. Clear **Uncategorized** and **Ask My Accountant** (use the client question list for unknowns).
6. Rebuild/clean the chart of accounts; merge duplicates; fix account types.
7. Reclass owner personal spend to Owner's Draw; fix mis-booked transfers.
8. Map payroll to wages/taxes; reconcile payroll liabilities.
9. Delete/merge duplicate transactions (verify against statements first).
10. Clear **Opening Balance Equity** to the correct account.

### Phase 3 — Verify & lock
11. Review AR/AP aging; clean up stale items (write-offs with client approval).
12. Tie **Sales Tax Payable** to filings; reconcile loan balances.
13. Run comparative P&L and Balance Sheet; investigate any anomaly or negative balance.
14. Confirm the Balance Sheet ties to source documents.
15. **Lock/close** each cleaned period; document the cutoff date.

### Definition of done
- Every account reconciled with $0 unexplained difference.
- $0 in Uncategorized / Ask My Accountant; Opening Balance Equity cleared.
- Balance Sheet ties to source docs; P&L comparable month-over-month.
- A documented clean cutoff date for go-forward bookkeeping.

**AI prompt — draft the client-facing "what we fixed" summary:**
```text
You are a senior bookkeeper. Write a short, plain-English summary for the client of what
we cleaned up and why it matters to them, based on these completed items. Warm,
non-technical, confidence-building. End with the clean cutoff date and what happens next.
Completed work:
{{PASTE COMPLETED CLEANUP ITEMS}}
```

---

## How to run a cleanup end-to-end with the toolkit
1. **Diagnostic questionnaire** (Part 1) → AI brief.
2. **Audit the file** (Part 2) → AI prioritized issue list.
3. **Scope, price & propose** with **Module 4 (Cleanup Project Agent)**.
4. **Execute** the phased workflow (Part 3).
5. **Summarize & hand off** with the AI summary prompt + **Module 3** email templates.
6. **Transition to monthly** with **Module 6 (Proposal Generator)** + **Module 2 (Close)**.

> Nothing here is tax advice. Refer prior-year amendments, basis changes, and nexus
> questions to the client's CPA.
