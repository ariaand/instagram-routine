# Example Walkthrough — Brightwave Café, June Close

**Module 2 — Balance Operations Co. AI Bookkeeper Toolkit™**

This continues the same fictional client from Modules 1, 4, and 6
([Brightwave Café](../module-1-client-onboarding-agent/example-walkthrough.md)). The
cleanup is done and the client is on a monthly Growth engagement — now we run their
**June close** through the Month-End Close Agent. Numbers are illustrative.

---

## The inputs we gave the Agent

**CLIENT/PERIOD:**
```text
Brightwave Café (single-location café + retail). Cash basis. Closing June 2026.
Close target: by the 15th.
```

**BANK & CC BALANCES:**
```text
- Checking: statement $18,200 / book $18,200 — reconciled. ✅
- Credit card: statement $4,650 / book $4,910 — NOT reconciled, difference $260.
```

**RECONCILIATION NOTES:**
```text
Checking clean. CC $260 difference looks like a duplicate supplies charge on June 9 — confirm.
Toast June payouts booked as lump sums; not yet split into sales/fees/tips/sales tax.
One $1,200 charge on June 14 sitting in "Ask My Accountant" — awaiting client answer.
Undeposited funds $0.
```

**RECURRING ITEMS:**
```text
Depreciation $300/mo. Prepaid insurance amortization $150/mo. Payroll recorded via Gusto.
TX sales tax tracked monthly. No rent accrual.
```

---

## The Agent's clarifying questions (Step 1)

> Before I finalize the close, three quick confirmations:
> 1. The $260 credit-card difference — can you confirm the June 9 supplies charge is a duplicate? If so I'll suggest a reversing entry; if not, we resolve the recon first.
> 2. Do you have the Toast June payout report so I can suggest the sales/fees/tips/tax split amounts?
> 3. Any word from the client on the $1,200 June 14 charge, or should I leave it in "Ask My Accountant" and flag it in the summary?

**Our answers:** Confirmed duplicate. Toast report attached (gross sales $52,400; fees
$1,300; tips $3,100; sales tax $4,000). No client answer yet on the $1,200 — flag it.

---

## Deliverable 1 — Month-End Checklist (abbreviated)

**Reconciliations:** ☐ Checking ✅ done · ☐ Credit card — ⚠ resolve $260 duplicate, then reconcile.
**Transaction review:** ☐ Split Toast payout · ☐ "Ask My Accountant" $1,200 — ⚠ BLOCKED on client.
**Accruals:** ☐ Depreciation $300 · ☐ Prepaid insurance $150.
**Payroll & taxes:** ☐ Confirm Gusto payroll recorded · ☐ True-up TX sales-tax liability.
**Reports:** ☐ P&L + Balance Sheet · ☐ compare to May.
**Review & lock:** ☐ Balance Sheet ties · ☐ lock period · ☐ send summary.

---

## Deliverable 2 — Journal Entry Suggestions (abbreviated, for review)

**JE 1 — Depreciation:** DR Depreciation Expense $300 / CR Accumulated Depreciation $300.

**JE 2 — Prepaid insurance:** DR Insurance Expense $150 / CR Prepaid Insurance $150.

**JE 3 — Split Toast June payout** (confirm against report):
| Account | Debit | Credit |
|---------|------:|-------:|
| Merchant Fees Expense | $1,300 | |
| Tips Payable | | $3,100 |
| Sales Tax Payable | | $4,000 |
| Sales Revenue | | (to balance gross $52,400 net of the above vs. recorded net deposit) |

> Confirm the deposit already booked so the reclass nets correctly — don't double-count revenue.

**JE 4 — Reverse duplicate supplies charge:** DR Credit Card Liability $260 / CR Supplies
Expense $260. *(Confirmed duplicate — clears the $260 reconciliation difference.)*

**Discrepancies & open items before locking:**
- ⚠ $1,200 (June 14) in "Ask My Accountant" — awaiting client answer.
- Credit card will reconcile once JE 4 is posted.

---

## Deliverable 3 — Client Summary (abbreviated, client-facing)

> **Subject:** Your June books are closed 📊
>
> Hi Sam,
>
> Your June books are reconciled and closed. Quick recap:
>
> **Cash:** Checking $18,200 · Card balance $4,650.
>
> **How the month went:** June sales ran about $52k through Toast — a solid month. Your
> biggest costs were payroll and supplies, in line with May. Nothing alarming.
>
> **Worth noting:** We caught and removed a duplicate $260 supplies charge on your card,
> and your TX sales tax is tracked and on schedule.
>
> **One thing we need:** Can you confirm what the **$1,200 charge on June 14** was for?
> Once we know, we'll categorize it and you're all set.
>
> Reports are in your portal. Thanks! — Aria, Balance Operations Co.

---

## What this took

Close data pasted in; three clarifying questions; checklist, four reviewed JEs, and a
client-ready summary in one pass — **a few minutes of AI time** versus the usual manual
checklist-running and summary-writing. The bookkeeper verified each JE against QBO,
posted them, locked the period, and sent the summary the same day.

> Reminder: the Agent suggested; the bookkeeper verified and posted. The books were never
> touched by the AI.
