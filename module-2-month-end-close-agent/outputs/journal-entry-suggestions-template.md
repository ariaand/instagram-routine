# Output 2 — Journal Entry Suggestions (Template)

**Module 2 output format — Balance Operations Co. AI Bookkeeper Toolkit™**

**How to use:** The Agent fills this automatically. **These are suggestions for your
review — verify every amount and account against the live books before posting in QBO.**
This is an internal working document.

> ⚠️ The Agent cannot see the books and does not post. Amounts shown as
> `{{… — confirm}}` must be filled from source before posting.

---

## Suggested Journal Entries — {{CLIENT_NAME}} · {{MONTH}}
**Prepared by:** {{FIRM_NAME}}  **Date:** {{DATE}}  **Status:** DRAFT — review before posting

---

### JE 1 — {{Record monthly depreciation}}
*Reasoning: {{straight-line depreciation per fixed-asset schedule}}.*

| Account | Debit | Credit |
|---------|------:|-------:|
| Depreciation Expense | {{$300}} | |
| Accumulated Depreciation | | {{$300}} |

Reversing: No · Date: {{MONTH end}}

---

### JE 2 — {{Amortize prepaid insurance}}
*Reasoning: {{recognize 1 month of the 12-month prepaid policy}}.*

| Account | Debit | Credit |
|---------|------:|-------:|
| Insurance Expense | {{$150}} | |
| Prepaid Insurance | | {{$150}} |

Reversing: No · Date: {{MONTH end}}

---

### JE 3 — {{Split Toast June payout}}
*Reasoning: {{gross sales recorded net of fees/tips/tax — reclass to correct accounts}}.*

| Account | Debit | Credit |
|---------|------:|-------:|
| Merchant Fees Expense | {{AMOUNT — confirm}} | |
| Tips Payable | | {{AMOUNT — confirm}} |
| Sales Tax Payable | | {{AMOUNT — confirm}} |
| Sales Revenue | | {{AMOUNT — confirm}} |

Reversing: No · Date: {{date of payout}}
> Confirm split totals tie to the Toast payout report before posting.

---

### JE 4 — {{Correct duplicate supplies charge}}
*Reasoning: {{$260 CC difference appears to be a duplicate — verify, then reverse if confirmed}}.*

| Account | Debit | Credit |
|---------|------:|-------:|
| {{Accounts Payable / CC Liability}} | {{$260}} | |
| Supplies Expense | | {{$260}} |

Reversing: No · Date: {{MONTH end}}
> ⚠ Only post if confirmed a duplicate; otherwise resolve the reconciliation difference first.

---

## Discrepancies & open items to resolve before locking
- ⚠ {{Credit card did not reconcile — $260 difference (likely duplicate; confirm)}}
- ⚠ {{$1,200 in "Ask My Accountant" — awaiting client answer on classification}}
- {{Any unexplained variance vs. prior month}}

> ASSUMPTION: {{amounts pulled from recurring schedule; confirm against live books}}
> → Refer to CPA/attorney for: {{any entry with tax treatment implications}}
