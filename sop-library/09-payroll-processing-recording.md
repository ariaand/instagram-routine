# SOP: Payroll Processing & Recording

| | |
|---|---|
| **Purpose** | Run or verify each payroll accurately and record it correctly in QBO so wages, taxes, and liabilities land in the right accounts and payroll clearing always reconciles — while leaving tax filing decisions to the payroll provider/CPA. |
| **Owner / Role** | {{Staff Bookkeeper}} (processes/verifies & records); {{Client}} (approves hours & pay) |
| **Frequency** | Each pay run (weekly/bi-weekly/semi-monthly per client) |
| **Tools** | {{PAYROLL_SYSTEM}} (e.g., QBO Payroll, Gusto, ADP), QBO, {{PORTAL}}, client profile |
| **Estimated time** | 30–75 minutes per pay run |
| **Version** | 1.0 |

## Overview
This procedure covers gathering and verifying payroll inputs, processing (or
confirming the provider processed) the run, and recording the results in QBO so
gross wages, employer taxes, withholdings, and net pay reconcile. The firm
handles accuracy and bookkeeping; payroll tax filings and rates remain the
provider's/CPA's responsibility.

## Prerequisites
- Client profile defines pay schedule, employees/contractors, pay types, the
  payroll system, and how hours/changes are approved.
- The payroll mapping is set: which QBO accounts receive gross wages, employer
  taxes, and the payroll clearing/liability accounts.
- Client approval of hours and any changes before processing.

## Procedure

**Phase 1 — Gather & verify inputs**
1. Collect approved hours, salaries, commissions, bonuses, and any changes
   (new hires, terminations, rate changes, deductions) from the agreed source.
   Confirm the client approved them.
2. Verify each item against the prior run: flag unusual hours, new pay types, or
   large swings, and confirm before processing.
3. **If** a worker's classification (employee vs contractor) is unclear, do not
   guess — contractors are paid via A/P (SOP 06) and get a 1099 (SOP 10);
   employees go through payroll. Flag classification questions to the client/CPA.

**Phase 2 — Process (or verify) the run**
4. In {{PAYROLL_SYSTEM}}, enter the inputs and review the preview: gross pay,
   employee withholdings, employer taxes, deductions, and net pay. **If** the
   client uses an outside provider, obtain and review the provider's reports
   instead of processing.
5. Submit the run after review (or confirm the provider's run), respecting the
   provider's funding/lead-time deadlines.
6. Retain the payroll register / pay-run report for the period — it is the source
   for the QBO entry and the working papers.

**Phase 3 — Record in QBO**
7. Record payroll per the firm's method:
   - **If** using QBO Payroll, confirm the integrated entries posted to the mapped
     accounts.
   - **If** using an outside provider, book a **journal entry** from the payroll
     register: debit gross wages (and employer payroll-tax expense), credit
     withholdings/employer-tax **liabilities** and net pay / payroll clearing.
8. Record the cash movements: net pay direct deposits and the provider's tax
   drafts/fees as they hit the bank. Route them through payroll clearing so the
   account nets to $0 when fully recorded.
9. Book employer-paid items per the register: payroll taxes, benefits, retirement
   match, garnishments — to the correct expense/liability accounts.

**Phase 4 — Reconcile**
10. After each run (and at month-end), confirm the **payroll clearing** account
    nets to $0 (or the expected in-transit amount) and that wage expense matches
    the registers for the period.
11. Reconcile payroll **liability** balances (withholdings, employer taxes) to the
    provider's records; the provider remits and files — confirm liabilities clear
    as they're paid, and flag any stuck balance.
12. File the register and confirmation, and log the run complete in {{PM_TOOL}}.

## Quality checks
- [ ] Hours/changes approved by the client before processing.
- [ ] Pay run reviewed against the prior period for anomalies.
- [ ] Worker classification confirmed (employee vs contractor).
- [ ] QBO entry matches the payroll register (gross, taxes, withholdings, net).
- [ ] Net pay and tax drafts recorded; payroll clearing nets to $0.
- [ ] Liability accounts reconcile to the provider and clear when paid.
- [ ] Register retained in working papers.

## Common issues & how to handle them
| Issue | How to handle |
|-------|---------------|
| Payroll clearing won't net to zero | Trace each debit/credit to the register and bank; find the missing/duplicate entry. |
| Contractor run through payroll (or vice versa) | Stop; confirm classification with client/CPA and route correctly. |
| Provider entries don't match QBO | Re-derive the JE from the register; correct QBO to match source. |
| Stuck payroll-tax liability balance | Confirm whether the provider remitted; flag unremitted/overdue amounts. |
| Net pay doesn't match bank | Check timing/funding date and any rejected direct deposit; reconcile to the bank. |

## Escalation
- Flag the firm owner when: payroll can't be funded, classification is disputed,
  a liability appears unremitted/overdue, or there's a discrepancy you can't
  resolve from source documents.
- → Refer to the CPA / payroll provider for: tax rates and deposits, payroll tax
  **filings** (941/940, state), worker classification rulings, and benefits/
  garnishment compliance. We record and reconcile; we do not file payroll taxes or
  rule on classification.

## Revision log
| Date | Version | Change | Author |
|------|---------|--------|--------|
| 2026-06-15 | 1.0 | Initial SOP | {{AUTHOR}} |
