# SOP: Monthly Bank & Credit-Card Reconciliation

| | |
|---|---|
| **Purpose** | Prove that each bank and credit-card account in QBO agrees with the official statement, so the financials are accurate and any discrepancy is found and explained, not carried forward. |
| **Owner / Role** | {{Staff Bookkeeper}} (reviewed by {{Senior Bookkeeper}}) |
| **Frequency** | Monthly, per account, once the statement is available |
| **Tools** | QBO (Reconcile), bank/credit-card statements, {{PM_TOOL}} |
| **Estimated time** | 15–40 min per account |
| **Version** | 1.0 |

## Overview
Reconciliation matches QBO's record of an account to the bank's official
statement for the period. It is the control that confirms nothing is missing,
duplicated, or wrong. This SOP covers checking and savings, credit cards, and any
loan or line-of-credit account with a statement.

## Prerequisites
- The week's transactions are categorized (SOP 02) so the feed is current.
- The official statement (not just feed data) is available for the period.
- The prior month for this account was reconciled and the ending balance carried
  forward correctly.

## Procedure
1. Gather the statement for each account and confirm the statement period and the
   statement **ending balance** and **ending date**.
2. In QBO, go to **Settings (gear) → Reconcile**, choose the account, and confirm
   the **Beginning balance** matches last month's reconciled ending balance.
   **If** the beginning balance does not match, stop and investigate before
   reconciling (a prior reconciled transaction was changed or deleted) — see
   Common issues.
3. Enter the statement **Ending balance** and **Ending date**, plus any service
   charges or interest the bank charged, then start the reconciliation.
4. Work top to bottom, checking off each QBO transaction that appears on the
   statement. Match by date and amount; clear deposits and payments first, then
   individual charges.
5. Investigate any QBO transaction that is **not** on the statement (timing item
   vs error) and any statement item **not** in QBO (a missing transaction —
   categorize it now per SOP 02 rules).
6. Track the **Difference** field. The goal is a difference of **$0.00**. Do not
   force a reconciliation while a difference remains.
7. **If** there's a small unexplained difference, recheck for transposed amounts,
   a transaction with the wrong date, or a missed bank fee. **If** there's a large
   difference, look for a missing deposit, a duplicate, or a transfer recorded on
   only one side.
8. For credit cards, reconcile to the statement the same way; confirm the period's
   **payment** to the card is recorded as a transfer from the paying bank account,
   not as an expense.
9. When **Difference = $0.00**, finish the reconciliation. **Do not** click "finish
   now" / accept an auto-adjustment to force it — an adjusting entry hides the real
   problem.
10. Save/export the **Reconciliation report** for the period to {{PORTAL}} or the
    workpapers folder as evidence.
11. Review the **Uncleared/Outstanding transactions** list. Old uncleared checks or
    deposits that never clear are a red flag — investigate stale items beyond
    {{N}} days.
12. Mark the account reconciled in {{PM_TOOL}} with the statement date and ending
    balance, and note any unresolved item for the close (SOP 04).

## Quality checks
- [ ] Beginning balance matched the prior reconciled ending balance.
- [ ] Reconciled to the official statement, not just the bank feed.
- [ ] Ending difference is exactly $0.00 with no forced adjustment.
- [ ] Credit-card payments recorded as transfers, not expenses.
- [ ] Reconciliation report saved to workpapers.
- [ ] Stale uncleared items reviewed and explained.

## Common issues & how to handle them
| Issue | How to handle |
|-------|---------------|
| Beginning balance won't match | A prior reconciled item was edited/deleted — use the Reconciliation history / audit log to find and restore it; don't reconcile until fixed. |
| Small unexplained difference | Check for transposed digits, wrong dates, missed fees/interest. |
| Large difference | Look for missing deposit, duplicate, or one-sided transfer. |
| Temptation to auto-adjust | Never force-finish; an unresolved difference must be explained, not plugged. |
| Stale uncleared check | Confirm whether it cleared, was voided, or needs to be voided/reissued (coordinate with client). |

## Escalation
- Flag the firm owner when: a difference can't be resolved, a prior period's
  reconciliation was broken, or you find evidence of missing/duplicated funds.
- → Refer to the CPA for: how to treat a voided stale-dated check or any item with
  tax implications.

## Revision log
| Date | Version | Change | Author |
|------|---------|--------|--------|
| 2026-06-15 | 1.0 | Initial SOP | {{AUTHOR}} |
