# SOP: Weekly Transaction Categorization

| | |
|---|---|
| **Purpose** | Keep each client's books current by reviewing and correctly categorizing all bank-feed activity every week, so month-end close is fast and the financials are reliable between closes. |
| **Owner / Role** | {{Staff Bookkeeper}} |
| **Frequency** | Weekly — every {{DAY_OF_WEEK}} |
| **Tools** | QBO (Transactions / Banking), {{PM_TOOL}}, client question log, client profile |
| **Estimated time** | 20–45 min per client |
| **Version** | 1.0 |

## Overview
Each week the bookkeeper clears the QBO bank feed: matching, categorizing, and
adding transactions according to the client's documented rules. Done well, this
prevents a month-end backlog and keeps a running list of open questions for the
client instead of one big surprise.

## Prerequisites
- Bank and credit-card feeds connected and updating.
- The client profile (vendor-to-account mappings and conventions) is available.
- The prior week's questions have been sent and any answers recorded.

## Procedure
1. Open **Transactions → Bank transactions** (Banking) in QBO. Confirm each
   connected account shows recent activity and the feed is current. **If** a feed
   has not updated in several days, refresh/reconnect it and note any gap.
2. Work one account at a time, starting on the **For review** tab. Sort by date so
   you process chronologically.
3. **Review QBO's suggested matches first.** Where QBO proposes a match to an
   existing invoice, bill, or recorded transaction, verify the amount and date,
   then accept. Do not accept a match you can't verify.
4. For transactions that are transfers between the client's own accounts (e.g.,
   checking → savings, or a credit-card payment), use **Record as transfer** to
   the correct account. Never book a transfer as income or expense.
5. Categorize the remaining transactions to the correct account on the chart of
   accounts, following the client profile's vendor mappings. Assign the payee/
   vendor name consistently, and add class/location if the client uses them.
6. Apply or refine **bank rules** for recurring, unambiguous transactions to speed
   future weeks — but only for transactions you're confident about. Review
   rule-applied items rather than auto-confirming blindly.
7. Handle owner activity per the client profile: owner draws/contributions to
   **Owner's Draw / Owner's Equity** (not expense), and personal charges on a
   business card to the appropriate equity/due-to-owner account — never as a
   business expense.
8. For payments received, confirm they land correctly. **If** the client uses
   Undeposited Funds, make sure received payments are grouped into the actual
   bank deposit so Undeposited Funds clears.
9. For anything you can't categorize with confidence, post it to **Ask My
   Accountant** (or your firm's holding account) and add a specific line to the
   client question log — include the date, amount, payee, and your best guess.
10. Watch for duplicates (same amount/date appearing twice, often from a manual
    entry plus a feed entry). **If** you find a likely duplicate, verify against
    the statement or source before excluding/deleting — don't delete on a hunch.
11. When the feed is clear, the **For review** count should be zero (or only items
    intentionally left for the client). Spot-check the **Categorized** tab for
    obvious miscategorizations.
12. Send the client the week's questions through {{PORTAL}}/{{PM_TOOL}}, record
    answers as they arrive, and mark the weekly task complete in {{PM_TOOL}}.

## Quality checks
- [ ] Every account's **For review** tab is at zero (or only intentional holds).
- [ ] No transfers booked as income or expense.
- [ ] No unverified QBO matches accepted.
- [ ] Owner draws/contributions hit equity, not expense.
- [ ] Undeposited Funds is clearing, not accumulating.
- [ ] No unresolved duplicates.
- [ ] Client question log updated and sent.

## Common issues & how to handle them
| Issue | How to handle |
|-------|---------------|
| Unknown transaction | Post to Ask My Accountant; add a specific question to the log. |
| Bank feed not updating | Refresh/reconnect; if persistent more than {{N}} days, note and notify owner. |
| Possible duplicate | Verify against statement/source before excluding; never delete on a guess. |
| Personal charge on business card | Code to owner equity/due-to-owner per profile, not to expense. |
| A bank rule miscoded items | Fix the affected transactions, then correct or delete the rule. |

## Escalation
- Flag the firm owner when: a transaction over {{$THRESHOLD}} is unexplained, you
  suspect missing accounts or fraud, or the client is unresponsive on questions
  past {{N}} days.
- → Refer to the CPA for: how a specific item should be treated for tax, or any
  deductibility question. We categorize per books and firm policy, not tax law.

## Revision log
| Date | Version | Change | Author |
|------|---------|--------|--------|
| 2026-06-15 | 1.0 | Initial SOP | {{AUTHOR}} |
