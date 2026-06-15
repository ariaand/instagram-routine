# SOP: Cleanup / Catch-Up Project

| | |
|---|---|
| **Purpose** | Take a disorganized or behind set of books and bring them to a clean, reconciled, report-ready state for a defined historical period — as a scoped, fixed-fee project separate from ongoing monthly work. |
| **Owner / Role** | {{Senior Bookkeeper}} (leads); {{Owner}} (scopes & reviews) |
| **Frequency** | Per engagement (one-time project, often before ongoing work begins) |
| **Tools** | QBO, {{PM_TOOL}}, bank/CC/loan statements for the full period, prior tax return, client profile |
| **Estimated time** | Project-based; scope drives hours (commonly 10–60+ hours) |
| **Version** | 1.0 |

## Overview
A cleanup/catch-up project repairs historical books over a bounded date range so
they can be relied on for reporting and tax. Unlike monthly close, the period is
in the past and usually messy, so the work is sequenced: scope it, set a solid
starting point, then move forward month by month to a clean finish line.

## Prerequisites
- Signed engagement (or change order) defining the cleanup period, scope, and fee
  — separate from any monthly retainer.
- Bank, credit-card, and loan statements for the **entire** cleanup period
  (start through end).
- Prior-year tax return and last set of CPA-prepared/known-good financials, if
  any, to anchor opening balances.
- Onboarding access complete (SOP 01).

## Procedure

**Phase 1 — Scope & baseline**
1. Define the boundaries in writing: start date, end date, accounts in scope, and
   the deliverable (e.g., "reconciled books and accrual financials for FY2025").
   Confirm the accounting basis with the client/CPA.
2. Assess the damage: run a **Balance Sheet** and **P&L** for the full period,
   review the Chart of Accounts, check **Banking** feed history, and run
   reconciliation reports to find the last reconciled date per account. Log every
   problem in {{PM_TOOL}}.
3. Establish the opening position. **If** a prior tax return or CPA financials
   exist, anchor opening balances to the last known-good date (tie ending equity,
   fixed assets, loans, AR/AP). **If** nothing reliable exists, flag the
   opening-balance approach to the owner/CPA before proceeding.

**Phase 2 — Rebuild, oldest first**
4. Fix the Chart of Accounts before transactions: merge duplicates, rename vague
   accounts, and set up the structure you'll keep. Do this deliberately, not in
   bulk.
5. Import missing transactions. Use the bank feed where history is available;
   otherwise import via CSV/QBO bank-import using the statements. Avoid creating
   duplicates — check existing data before importing.
6. Work **oldest month to newest**. For each month: categorize every transaction
   (per the client profile and tax return mapping), match transfers between
   accounts, and clear **Undeposited Funds**.
7. Reconcile each account month by month against the statements, in order. Do not
   skip ahead — an early error cascades. Resolve discrepancies as you go rather
   than batching them.
8. Resolve clearing/suspense balances: drive **Opening Balance Equity** to $0,
   empty **Uncategorized** and **Ask My Accountant**, and reconcile loan/CC
   control accounts to statements.

**Phase 3 — Adjust, review, finalize**
9. Book historical accruals and adjustments per the CPA's guidance: depreciation,
   amortization, loan interest/principal splits, payroll true-ups. Document each
   journal entry.
10. Review the full-period **P&L** and **Balance Sheet** for reasonableness
    against the tax return and any prior financials; investigate and explain
    material variances.
11. Build a cleanup summary: what was wrong, what you changed, assumptions made,
    open questions, and items routed to the CPA. This protects the firm and
    informs the tax preparer.
12. Set the **closing date** (with password) at the cleanup end date, hand off any
    CPA items (SOP 10), and transition the client to ongoing monthly work (SOP 04)
    starting the month after cleanup ends.

## Quality checks
- [ ] Cleanup period and scope confirmed in writing.
- [ ] Opening balances anchored to a known-good source or flagged.
- [ ] Every in-scope account reconciled, oldest-to-newest, to $0.00 difference.
- [ ] Opening Balance Equity, uncategorized, and clearing accounts resolved.
- [ ] Adjustments booked per CPA guidance and documented.
- [ ] Full-period financials reviewed and reconcile to support.
- [ ] Cleanup summary written; CPA items handed off.
- [ ] Closing date set; ongoing start date confirmed.

## Common issues & how to handle them
| Issue | How to handle |
|-------|---------------|
| Missing statements for part of the period | Request from client/bank; document gaps; don't fabricate balances. |
| No reliable opening balance | Flag to owner/CPA; agree an approach in writing before booking. |
| Duplicate transactions from prior imports | Identify and delete duplicates before reconciling; reconcile only after data is clean. |
| Scope balloons mid-project | Pause, issue a change order, get sign-off — don't absorb unscoped hours. |
| Prior bookkeeper's entries make no sense | Document, don't preserve errors; reconstruct from source statements. |

## Escalation
- Flag the firm owner when: scope materially exceeds the estimate, source
  documents are unavailable, you find evidence of fraud or commingling, or the
  opening position can't be established reliably.
- → Refer to the CPA for: opening-balance treatment, prior-period adjustments
  with tax impact, depreciation/amortization, and whether amended returns are
  needed. We surface the issue and provide the numbers; the CPA decides treatment.

## Revision log
| Date | Version | Change | Author |
|------|---------|--------|--------|
| 2026-06-15 | 1.0 | Initial SOP | {{AUTHOR}} |
