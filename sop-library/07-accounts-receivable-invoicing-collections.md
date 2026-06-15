# SOP: Accounts Receivable / Invoicing & Collections

| | |
|---|---|
| **Purpose** | Create accurate customer invoices, apply payments correctly so A/R stays clean, and run a consistent collections cadence so the client gets paid on time. |
| **Owner / Role** | {{Staff Bookkeeper}} (invoices & applies payments); {{Client}} (approves write-offs & escalated collections) |
| **Frequency** | Invoicing per client cycle (e.g., weekly/on-completion); A/R review weekly; aging at month-end |
| **Tools** | QBO (Sales / Invoices / Receive Payment), payment processor, {{PORTAL}}, client profile |
| **Estimated time** | 30–60 minutes per weekly cycle |
| **Version** | 1.0 |

## Overview
This procedure covers the receivables cycle: raising invoices from approved
source data, applying incoming payments to the right invoices, and following a
defined collections cadence on overdue balances. The aim is an A/R aging that
always reflects reality.

## Prerequisites
- Client profile defines customers, products/services, payment terms, invoice
  approval process, and collections cadence/tone.
- Source of billable activity available (signed work, time, contracts, billable
  expenses from SOP 06).
- Payment processor (if any) connected so deposits and fees post correctly.

## Procedure

**Phase 1 — Invoice**
1. Gather billable activity per the client's cycle. Confirm what's actually
   billable and approved before invoicing — don't bill speculative or disputed
   amounts.
2. In QBO, create each invoice via **+ New → Invoice**: select the customer,
   correct product/service items (which drive the income account), quantities,
   rates, terms, and due date. Apply **sales tax** only per the client's
   configured rates/obligations.
3. **If** there are billable expenses or unbilled time, add them from the
   right-hand drawer so reimbursables are captured.
4. Review for accuracy (amounts, customer, terms), then send via QBO or the
   client's preferred channel. Confirm the invoice is recorded to A/R.

**Phase 2 — Receive & apply payments**
5. When payment arrives, use **+ New → Receive payment** and apply it to the
   specific open invoice(s). Never record customer payments as generic income —
   that double-counts and leaves A/R overstated.
6. For card/ACH payments through a processor, record the gross payment and the
   processor **fee** separately (expense), so the net deposit reconciles to the
   bank. Route through **Undeposited Funds** only when grouping multiple receipts
   into one bank deposit.
7. **If** a payment is partial, apply it and leave the remaining balance open.
   **If** a customer overpays, record the credit and note it for application or
   refund.
8. Match deposits in **Banking** to the recorded payments so A/R and cash both
   clear cleanly.

**Phase 3 — Collections**
9. Run the **A/R Aging Summary** weekly. Identify invoices entering 30/60/90-day
   buckets.
10. Follow the documented collections cadence: e.g., friendly reminder at due +
    {{X}} days, firmer notice at 30, phone/escalation at 60. Use the client's
    approved tone and templates; log each contact.
11. **If** a balance reaches the client's escalation point or is disputed, hand it
    to the client with a summary — we surface and report; we don't pursue legal
    collection.
12. Write off uncollectible amounts only with **documented client approval**, via
    a credit memo or bad-debt entry per the client profile; never write off
    unilaterally.

## Quality checks
- [ ] Invoices use correct customer, items/income accounts, terms, and sales tax.
- [ ] Payments applied to specific invoices (not booked as raw income).
- [ ] Processor fees recorded; net deposits reconcile to the bank.
- [ ] A/R aging reviewed weekly; collections cadence followed and logged.
- [ ] Overpayments/credits identified and tracked.
- [ ] Write-offs only with documented client approval.
- [ ] A/R ties to the aging report at month-end.

## Common issues & how to handle them
| Issue | How to handle |
|-------|---------------|
| Customer payment booked as income | Reverse and re-apply via Receive payment to the open invoice. |
| Deposit doesn't match invoice (fees) | Split the deposit: gross to invoice, fee to expense; net ties to bank. |
| Negative A/R / unapplied credit | Apply the credit to an open/future invoice or process a refund per client. |
| Duplicate or disputed invoice | Confirm with client; void or issue a credit memo — don't just delete history. |
| Sales tax rate looks wrong | Don't guess; confirm the client's configured obligations or flag to the CPA. |

## Escalation
- Flag the firm owner / client when: a balance hits the escalation threshold, an
  invoice is disputed, or a customer is unresponsive past the cadence.
- → Refer to the CPA / attorney for: sales-tax nexus and rate questions, revenue-
  recognition treatment, and any legal collection action. We invoice and report;
  we do not advise on tax or pursue legal remedies.

## Revision log
| Date | Version | Change | Author |
|------|---------|--------|--------|
| 2026-06-15 | 1.0 | Initial SOP | {{AUTHOR}} |
