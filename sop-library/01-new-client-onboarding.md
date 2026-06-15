# SOP: New Client Onboarding

| | |
|---|---|
| **Purpose** | Bring a new monthly client onto {{FIRM_NAME}}'s books cleanly: gain access, assess the starting point, set up the file and our internal tracking, and establish a defensible opening position so ongoing work is reliable. |
| **Owner / Role** | {{Onboarding Lead / Senior Bookkeeper}} |
| **Frequency** | Once per new client (typically within 5 business days of signed engagement) |
| **Tools** | QBO, {{PM_TOOL}}, {{PORTAL}} (secure document portal), password manager, signed engagement letter |
| **Estimated time** | 2–4 hours over the first week (excludes any cleanup, which is a separate project) |
| **Version** | 1.0 |

## Overview
This procedure takes a client from "signed" to "ready for ongoing monthly work."
It establishes access, gathers the documents and context we need, confirms the
QBO file's condition, and sets up our internal workflow. It deliberately does
*not* fix historical books — significant cleanup is scoped and run separately
under SOP 05.

## Prerequisites
- Signed engagement letter on file with scope, deliverables, and fee.
- Client contact name, email, and preferred communication channel captured.
- A {{PORTAL}} folder and a {{PM_TOOL}} client record created.
- Firm payment/billing set up for the client.

## Procedure

**Phase 1 — Access & security**
1. Request access to the client's QBO. Preferred method: have the client invite
   {{FIRM_EMAIL}} as an **Accountant user** (My Accountant → invite), which gives
   accountant tools without consuming a paid seat. If they instead add you as a
   standard user, note it and request accountant access.
2. Confirm the QBO subscription level (Simple Start / Essentials / Plus /
   Advanced) and who pays for it. Record the billing owner.
3. Store all credentials and the QBO Company ID in the password manager. Never
   keep passwords in email, {{PM_TOOL}} notes, or spreadsheets.
4. Request access to connected systems in scope: bank/credit-card portals or
   read-only statement access, payroll provider, point-of-sale, merchant
   processor, AP/AR apps, and any document sources.

**Phase 2 — Gather context & documents**
5. Send the client the onboarding request via {{PORTAL}}: prior-year tax return,
   most recent financial statements, list of bank/credit-card/loan accounts,
   business entity type, sales-tax obligations, payroll setup, and a list of the
   software they use.
6. Hold a kickoff call (30–45 min). Confirm the entity type, accounting basis
   (cash vs accrual) the client expects, fiscal year-end, who their CPA is, and
   how they want to receive reports and ask questions.
7. Capture the CPA's name and contact in {{PM_TOOL}}; we coordinate with the CPA
   for tax matters rather than advising on them ourselves.

**Phase 3 — Assess the QBO file**
8. In QBO, review the Chart of Accounts for duplicates, vague catch-all accounts,
   and obvious miscategorization. Note (don't fix yet) anything that needs
   cleanup.
9. Open **Banking** and confirm which accounts have live bank feeds, the feed
   start dates, and whether there is a backlog of unreviewed transactions.
10. Run a Balance Sheet and check for red flags: a non-zero **Opening Balance
    Equity**, negative cash, **Undeposited Funds** that never clears, or stale
    AR/AP. Run a Reconciliation report per account to see the last reconciled
    date.
11. Decide the starting point. **If** the books are current and clean, set the
    ongoing start date at the first un-reconciled period. **If** they are behind
    or messy, scope a cleanup/catch-up project (SOP 05) and get client sign-off
    before ongoing work begins.

**Phase 4 — Set up our system**
12. Confirm or build the Chart of Accounts to firm standard, and set the QBO
    company settings (accounting method, first month of fiscal year, classes/
    locations if used). Make structural changes deliberately, not in bulk.
13. Create the client's recurring task set in {{PM_TOOL}} (weekly categorization,
    monthly reconciliation, month-end close, reporting) with due dates and the
    assigned bookkeeper.
14. Document client-specific rules in a one-page client profile: vendor-to-account
    mappings, owner-draw vs expense conventions, recurring transactions, and
    anything unusual. This profile is the source of truth for whoever does the work.
15. Send a welcome summary confirming start date, what we'll deliver each month,
    how/when we'll ask questions, and the date of the first deliverable. Mark
    onboarding complete in {{PM_TOOL}}.

## Quality checks
- [ ] Accountant-level QBO access confirmed and working.
- [ ] All credentials stored in the password manager, not in plain text.
- [ ] Accounting method and fiscal year confirmed in QBO settings and with the client.
- [ ] Starting point decided; cleanup scoped separately if needed.
- [ ] Client profile (rules, mappings, conventions) documented.
- [ ] Recurring tasks scheduled in {{PM_TOOL}} with an owner.
- [ ] CPA contact recorded.

## Common issues & how to handle them
| Issue | How to handle |
|-------|---------------|
| Client adds you as a standard user, not accountant | Request the Accountant invite; explain it doesn't use a paid seat. |
| Bank feeds missing or short history | Request statements and/or use a connector; note the gap as cleanup scope. |
| Non-zero Opening Balance Equity | Do not "plug" it; flag for cleanup and resolve to the correct equity/retained-earnings accounts. |
| Client unsure of entity type or basis | Confirm from the prior tax return; coordinate with the CPA, don't guess. |
| Books much worse than the proposal assumed | Pause, re-scope cleanup, and get written sign-off before proceeding. |

## Escalation
- Flag the firm owner when: scope materially exceeds the engagement letter, you
  cannot get access within {{N}} days, or the file shows signs of fraud or large
  unexplained balances.
- → Refer to the CPA/attorney for: entity structure, tax elections, accounting
  basis for tax purposes, and any compliance question. We coordinate; we do not
  advise on these.

## Revision log
| Date | Version | Change | Author |
|------|---------|--------|--------|
| 2026-06-15 | 1.0 | Initial SOP | {{AUTHOR}} |
