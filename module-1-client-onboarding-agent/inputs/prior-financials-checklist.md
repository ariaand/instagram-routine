# Prior Financials Checklist

**Module 1 input — Balance Operations Co. AI Bookkeeper Toolkit™**

**How to use:** Use this list to collect the financials you're inheriting, then write
a short **summary** to paste into the Client Onboarding Agent as the
`PRIOR FINANCIALS SUMMARY` input.

> 🔒 You almost never need to paste a full general ledger into an AI tool.
> A summary — account names, balances, dates, and reconciliation status — is enough
> for the Agent to build an accurate cleanup plan and risk assessment, and it keeps
> sensitive detail out of the prompt.

---

## What to request from the client / prior bookkeeper

### Core reports (most useful, get these first)
- [ ] **Profit & Loss** — last full fiscal year + year-to-date
- [ ] **Balance Sheet** — as of the most recent month-end
- [ ] **Trial Balance** — most recent
- [ ] **General Ledger** — last 3–12 months (for your own review; summarize for the Agent)

### Reconciliation & cash
- [ ] **Bank reconciliation reports** for each account — most recent
- [ ] **Last bank statement** for each account
- [ ] **Last credit-card statement** for each card
- [ ] Date the books were last reconciled / closed

### Accounts receivable & payable
- [ ] **A/R Aging Summary**
- [ ] **A/P Aging Summary**
- [ ] **Open invoices** and **unpaid bills** list

### Payroll & contractors
- [ ] Most recent **payroll summary / register**
- [ ] List of contractors paid (for 1099 review)
- [ ] Prior-year 1099s filed (yes/no)

### Tax & compliance
- [ ] Most recent **business tax return** (for beginning balances / basis)
- [ ] Sales tax filing history / last return
- [ ] Any IRS / state notices

### Access (request secure access — never raw passwords)
- [ ] Accountant invite to the accounting software
- [ ] View-only or read access to bank/credit-card feeds (or statements)
- [ ] Access to payroll provider
- [ ] Access to any AP/AR tools, POS, e-commerce platforms

---

## How to summarize for the Agent

Paste something like this (numbers anonymized/rounded is fine):

```text
Software: QuickBooks Online, Simple Start plan. Cash basis.
Last reconciled: bank reconciled through Feb; credit card never reconciled.
Last close: no formal month-end close has ever been done.

Accounts:
- Checking (Bank A): book balance ~$12,400; statement balance ~$9,800 (unreconciled difference).
- Credit card (Card B): book balance ~$3,100; ~6 months of feed not categorized.

Chart of accounts: ~140 accounts, lots of duplicates ("Meals", "Meals & Ent", "Meal Exp").
Uncategorized: ~$22k sitting in "Uncategorized Expense" and "Ask My Accountant".
Opening Balance Equity: ~$8,500 (never cleared).
A/R aging: ~$4,200, two invoices 90+ days.
A/P aging: not used in QBO; client pays bills from bank directly.
Payroll: Gusto, 2 employees; payroll posted as lump-sum transfers, not mapped to wage/tax accounts.
Sales tax: collects in TX; unsure if liability account ties to filings.
Last tax return filed: 2023 (2024 not yet filed).
Notices: none reported.
```

That level of detail lets the Agent produce a genuinely useful cleanup plan and a
realistic risk assessment without exposing sensitive raw data.

---

## Red flags to note while you gather (the Agent will weigh these heavily)
- Book balances that don't match statements (unreconciled differences).
- A balance in **Opening Balance Equity** that was never cleared.
- Large balances in **Uncategorized Expense / Income** or **Ask My Accountant**.
- **Negative** asset balances or negative inventory.
- Payroll recorded as lump-sum transfers instead of mapped to wage/tax accounts.
- A bloated chart of accounts with obvious duplicates.
- Personal and business spending mixed in the same accounts.
- Sales tax collected but unclear whether it's filed/remitted.
