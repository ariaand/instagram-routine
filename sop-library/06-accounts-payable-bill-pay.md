# SOP: Accounts Payable / Bill Pay

| | |
|---|---|
| **Purpose** | Record vendor bills accurately, route them for client approval, pay approved bills on time, and keep A/P and cash correct — without ever moving the client's money without authorization. |
| **Owner / Role** | {{Staff Bookkeeper}} (records & schedules); {{Client}} (approves & funds) |
| **Frequency** | Weekly bill-pay run on {{day of week}}; bill entry ongoing |
| **Tools** | QBO (Accounts Payable / Bills), {{BILLPAY_APP}} (e.g., Bill.com/Melio) if used, {{PORTAL}}, client profile |
| **Estimated time** | 30–90 minutes per weekly run |
| **Version** | 1.0 |

## Overview
This procedure governs how vendor bills enter the books, get approved, get paid,
and get reconciled. The firm's role is to record and schedule accurately and
maintain controls; the client (or an authorized approver) approves what gets paid
and how the account is funded.

## Prerequisites
- Client profile defines vendors, default expense accounts, approval authority,
  payment methods, and any spending limits.
- A clear, documented approval rule (who approves, threshold for owner sign-off).
- Access to the bill source (vendor portal, {{PORTAL}} inbox, email forward) and
  the payment tool in use.

## Procedure

**Phase 1 — Capture & enter bills**
1. Collect incoming bills from the agreed source ({{PORTAL}}, forwarded email,
   vendor portals). Confirm each is a genuine bill, not a statement, quote, or
   duplicate.
2. In QBO, enter each via **+ New → Bill**: select the vendor (create per the
   client profile if new), enter bill date, due date, bill number, amount, and the
   correct expense or item account. Attach the source document to the bill.
3. **If** the bill should be billed back to a customer, mark it **billable** and
   tag the customer/project. **If** it covers a future period (e.g., annual
   insurance), code to prepaid and note it for amortization at close.
4. Check for duplicates by vendor + bill number + amount before saving. Never
   enter the same bill twice.

**Phase 2 — Approve & schedule**
5. Build the proposed payment run: in QBO **Expenses → Bills** (or the bill-pay
   app), list bills due within the next cycle, sorted by due date, and note early-
   payment discounts.
6. Send the proposed run to the client/approver for sign-off. **Do not pay
   anything without documented approval.** Capture the approval (email, app
   approval, portal) and retain it.
7. **If** a bill exceeds the client's approval threshold or looks unusual
   (new vendor, large amount, changed bank details), hold it and confirm directly
   with the client — this is the control against payment fraud.

**Phase 3 — Pay & record**
8. Pay approved bills via the authorized method using **+ New → Pay bills** (or
   the bill-pay app), on the funding the client authorized. Record the payment
   against the open bill so A/P clears — never as a separate expense, which would
   double-count.
9. For payments made in the bill-pay app, ensure the sync posts correctly to QBO
   (bill marked paid, cash/clearing reduced); reconcile the app's clearing
   account at close.
10. File remittance confirmations and update {{PM_TOOL}} that the run is complete.

**Phase 4 — Maintain A/P**
11. Run the **A/P Aging Summary** at least monthly. Investigate negative balances
    (vendor credits/overpayments), stale bills that should be paid or voided, and
    anything past due that wasn't approved.
12. At month-end, confirm A/P on the Balance Sheet ties to the aging report and
    that no paid bills remain open (and no open bills are missing).

## Quality checks
- [ ] Every bill has the source document attached.
- [ ] No duplicate bills entered (vendor + number + amount checked).
- [ ] Documented approval exists for every payment made.
- [ ] Payments recorded against bills (A/P clears), not as standalone expenses.
- [ ] Billable/prepaid items flagged correctly.
- [ ] A/P aging reviewed; negatives and stale items resolved.
- [ ] A/P ties to the aging report at month-end.

## Common issues & how to handle them
| Issue | How to handle |
|-------|---------------|
| Statement entered as a bill | Enter only the underlying invoices; reconcile to the statement, don't double-pay. |
| Vendor requests changed bank details | Stop. Verify by phone using a known number before paying — classic fraud vector. |
| Bill paid but A/P still shows open | Match the payment to the open bill; remove the duplicate expense entry. |
| Negative A/P balance | Identify the vendor credit/overpayment; apply it to future bills or request a refund. |
| Client hasn't approved a due bill | Notify the client of the deadline; do not pay without approval. |

## Escalation
- Flag the firm owner when: a payment request looks fraudulent, a vendor changes
  banking details, an approver is unreachable for a time-sensitive bill, or a
  client pressures you to pay without proper authorization.
- → Refer to the CPA for: questions about deductibility, contractor-vs-employee
  classification of a payee, or sales/use tax on a purchase. We record per
  guidance; we do not rule on tax treatment.

## Revision log
| Date | Version | Change | Author |
|------|---------|--------|--------|
| 2026-06-15 | 1.0 | Initial SOP | {{AUTHOR}} |
