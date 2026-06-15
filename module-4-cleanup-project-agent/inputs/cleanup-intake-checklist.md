# Cleanup Intake Checklist

**Module 4 input — Balance Operations Co. AI Bookkeeper Toolkit™**

**How to use:** Capture these data points before running the Cleanup Project Agent.
They are the **cost drivers** that determine how long the project takes and what you
should charge. Paste them into the Agent as the `VOLUME METRICS` input. If you ran
Module 1, most of this is already in your Cleanup Plan and Risk Assessment.

> 🔒 You don't need raw data — just counts, balances, dates, and statuses. That's
> enough to scope and price, and it keeps sensitive detail out of the prompt.

---

## The cost drivers (capture all of these)

### Period & basis
- [ ] Cleanup period: from ______ to ______ (how many months total?)
- [ ] Does the period cross fiscal/tax years? (more years = more tie-outs) ______
- [ ] Basis: ☐ Cash ☐ Accrual ☐ Needs to be confirmed by CPA
- [ ] Is a tax deadline driving this? (date) ______

### Accounts to reconcile (the biggest driver)
- [ ] # of bank accounts ______ — months unreconciled each: ______
- [ ] # of credit cards ______ — months unreconciled each: ______
- [ ] # of loans / lines of credit ______
- [ ] Are all statements available for the full period? ☐ Yes ☐ Partial ☐ No

### Transaction volume
- [ ] Approx. transactions per month: ______
- [ ] Approx. $ / # of items in **Uncategorized** + **Ask My Accountant**: ______
- [ ] Estimated # of correcting/reclassifying journal entries: ☐ Low ☐ Medium ☐ High

### Complexity flags
- [ ] Payroll involved? ☐ No ☐ Yes (provider: ______; mapped correctly? ______)
- [ ] Sales tax collected? ☐ No ☐ Yes (state[s]: ______; filed/tied out? ______)
- [ ] 1099 contractors to review? ☐ No ☐ Yes (#: ______)
- [ ] AR/AP aging in use and accurate? ☐ Yes ☐ No ☐ N/A
- [ ] Opening Balance Equity to clear? ☐ Yes ($______) ☐ No
- [ ] Chart of accounts condition: ☐ Clean ☐ Bloated/duplicates ☐ Needs rebuild
- [ ] Inventory tracked? ☐ No ☐ Yes
- [ ] Multiple entities / classes / locations / properties? ☐ No ☐ Yes (#: ______)
- [ ] Personal & business funds commingled? ☐ No ☐ Some ☐ A lot
- [ ] App/integration cleanup needed (POS, e-comm, Stripe payouts)? ☐ No ☐ Yes

### Engagement factors
- [ ] Client responsiveness (best guess): ☐ Fast ☐ Average ☐ Slow/unknown
- [ ] Likelihood of scope creep: ☐ Low ☐ Medium ☐ High
- [ ] Software & plan: ______ (does the plan support needed features?)

---

## How to summarize for the Agent

```text
VOLUME METRICS:
Period: Jan 2024 – Jun 2025 (18 months), crosses 2024/2025 tax years. Cash basis per CPA.
Tax deadline pressure: 2024 return not yet filed.
Accounts: 1 checking (unreconciled since Mar 2024 = ~15 mo), 1 credit card (never
reconciled = ~18 mo). All statements available.
Transaction volume: ~450/month. ~$31k across Uncategorized + Ask My Accountant.
Correcting entries: High (Toast deposits booked net — need monthly split entries).
Payroll: Gusto, 6 employees, posted as lump-sum transfers (needs mapping).
Sales tax: TX, filed quarterly but not tied to QBO.
OBE: ~$11,200 to clear. COA: ~160 accounts, bloated/duplicates.
Commingling: some personal expenses. Responsiveness: average. Scope creep: medium.
Software: QBO Simple Start (may need upgrade for class tracking).
```

That gives the Agent everything it needs to build a defensible hours estimate and price.

---

## Quick reference — what each driver does to price
| Driver ↑ | Effect on hours/price |
|----------|----------------------|
| More months / crossing tax years | More reconciliations + tie-outs |
| More accounts / more months unreconciled each | Linear increase — the #1 driver |
| Higher transaction volume | More categorization time |
| Big Uncategorized / Ask My Accountant balance | More research + correcting entries |
| Payroll, sales tax, 1099, inventory, multi-entity | Each adds a complexity block |
| Missing statements / slow client | Adds risk → contingency, phased billing |
