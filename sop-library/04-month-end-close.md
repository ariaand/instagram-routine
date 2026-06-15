# SOP: Month-End Close

| | |
|---|---|
| **Purpose** | Close each month to a defensible, report-ready state: every account reconciled, transactions categorized, accruals and adjustments booked, and financials reviewed before they go to the client. |
| **Owner / Role** | {{Staff Bookkeeper}} (prepares); {{Senior Bookkeeper / Owner}} (reviews) |
| **Frequency** | Monthly, target completion by the {{15th}} business day of the following month |
| **Tools** | QBO, {{PM_TOOL}}, client profile, prior-month working papers, password manager |
| **Estimated time** | 1.5–4 hours per client depending on volume and complexity |
| **Version** | 1.0 |

## Overview
Month-end close is the recurring procedure that turns a month of bookkeeping into
finished, trustworthy financials. It assumes weekly categorization (SOP 02) and
reconciliations (SOP 03) are done, then layers on accruals, adjustments, a review
of the financials, and a lock to prevent the period from changing after the fact.

## Prerequisites
- All in-scope bank, credit-card, and loan accounts reconciled through the close
  month (SOP 03 complete).
- Bank/CC feeds fully reviewed — zero items left in **Banking → For review**.
- Open client questions for the month answered, or logged with a documented
  assumption.
- Prior-month financials and working papers available for comparison.

## Procedure

**Phase 1 — Confirm the foundation**
1. In QBO, confirm the **For review** tab is empty for every connected account.
   **If** transactions remain, finish categorization (SOP 02) before continuing.
2. Confirm each account's reconciliation for the close month shows a **$0.00
   difference** and is marked reconciled (Reconcile → reports). **If** any account
   is unreconciled, stop and complete SOP 03 first.
3. Verify **Undeposited Funds** is appropriately clear — only genuinely
   in-transit deposits should remain; anything stale needs to be matched to a
   bank deposit.

**Phase 2 — Adjustments & accruals**
4. Review the **Balance Sheet** as of month-end. Confirm cash matches reconciled
   balances, and investigate any negative asset or contra balance.
5. Book recurring accruals/adjustments per the client profile: depreciation (per
   the CPA's schedule — do not invent a method), prepaid expense amortization,
   loan principal-vs-interest splits, and any deferred revenue. Use **+ New →
   Journal entry** and document each in the memo.
6. Clear suspense/clearing accounts: **Opening Balance Equity** should be $0;
   **Ask My Accountant** / uncategorized accounts should be empty; payroll
   clearing and merchant clearing should net to the expected balance.
7. Reconcile balance-sheet control accounts to support: loan balances to lender
   statements, credit-card balances to statements, and sales-tax liability to the
   sales-tax center.

**Phase 3 — Review the financials**
8. Run the **Profit & Loss** for the month and compare to the prior month and
   prior year. Investigate any line that moved materially (beyond your firm
   threshold) or any unexpected zero. Confirm nothing landed in a catch-all
   account.
9. Run the **Balance Sheet** and confirm AR/AP tie to the **A/R Aging Summary**
   and **A/P Aging Summary**. Investigate negative AR (overpayments/credits) or
   negative AP (vendor prepayments).
10. Check the accounting method matches the engagement (cash vs accrual) when
    running reports; report on the basis the client expects.

**Phase 4 — Lock & document**
11. Record month-end working papers: reconciliation reports, list of journal
    entries booked, questions/assumptions, and anything flagged for the owner or
    CPA.
12. Set/confirm the **closing date** under **Settings → Account and settings →
    Advanced → Accounting → Close the books**, with a password, so the period
    can't be silently changed.
13. Mark the close task complete in {{PM_TOOL}} and hand off to the reviewer (or,
    if you are the reviewer, sign off). Reporting to the client runs under SOP 08.

## Quality checks
- [ ] **For review** is empty for all connected accounts.
- [ ] All accounts reconciled to $0.00 difference for the month.
- [ ] Opening Balance Equity and uncategorized/clearing accounts are $0 or expected.
- [ ] AR/AP on the Balance Sheet tie to the aging reports.
- [ ] Recurring accruals/adjustments booked and documented.
- [ ] P&L and Balance Sheet reviewed against prior period; variances explained.
- [ ] Closing date set with password.
- [ ] Working papers saved and the task signed off.

## Common issues & how to handle them
| Issue | How to handle |
|-------|---------------|
| Reconciliation difference won't clear | Return to SOP 03; do not force-adjust to close. |
| Opening Balance Equity is non-zero | Trace the source (incorrect opening balance / unmatched deposit); correct it, don't plug. |
| Large unexplained P&L swing | Drill into the account detail; confirm with the client before finalizing. |
| Depreciation/amortization method unclear | Use the CPA's schedule; if none exists, flag — do not invent one. |
| Prior period changed after close | Check the audit log; that's why the closing date/password matters — re-lock and note it. |

## Escalation
- Flag the firm owner when: an account can't be reconciled, a material
  unexplained balance appears, the client can't answer questions needed to close,
  or the close will miss the committed deadline.
- → Refer to the CPA for: depreciation/amortization methods, tax provisions,
  accruals with tax consequences, and any treatment that affects the tax return.
  We book per their guidance; we do not decide tax treatment.

## Revision log
| Date | Version | Change | Author |
|------|---------|--------|--------|
| 2026-06-15 | 1.0 | Initial SOP | {{AUTHOR}} |
