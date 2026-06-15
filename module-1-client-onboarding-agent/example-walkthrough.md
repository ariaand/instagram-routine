# Example Walkthrough — Brightwave Café

**Module 1 — Balance Operations Co. AI Bookkeeper Toolkit™**

A complete, realistic run of the Client Onboarding Agent for a fictional client,
**Brightwave Café**. It shows the three inputs, the Agent's clarifying questions, and
abbreviated versions of all four deliverables. (Numbers are illustrative.)

---

## The inputs we gave the Agent

**CLIENT QUESTIONNAIRE (summary of client's answers):**
```text
Legal name: Brightwave Coffee LLC (DBA Brightwave Café). Single-member LLC, TX.
Single-location café, started 2021. 6 employees incl. tipped baristas. Also sells
retail bags of beans. ~$640k revenue last year. ~450 transactions/month.
Software: QuickBooks Online (Simple Start). Not sure if cash or accrual.
Last reconciled: "I think my old bookkeeper did the checking account in February."
Prior bookkeeper left in March; no clean handoff. POS: Toast. Collects TX sales tax.
Payroll: Gusto, 6 employees. Biggest frustration: "I have no idea if I'm profitable
and my CPA is asking for clean books for the 2024 return." Goal in 6 months: trust
the numbers, file 2024 on time.
```

**PRIOR FINANCIALS SUMMARY:**
```text
QBO Simple Start. Likely cash basis but not confirmed.
Checking reconciled through Feb; Toast deposits booked as single income lines (net of
fees, tips, and sales tax — not split). Business credit card never reconciled (~9 mo).
~$31k sitting in "Uncategorized Expense" + "Ask My Accountant."
Opening Balance Equity ~$11,200, never cleared.
Chart of accounts ~160 accounts with duplicates (Meals, Meals & Ent, Meal Exp).
Payroll posted as lump-sum Gusto transfers, not mapped to wages/taxes.
Sales tax: collected via Toast; unclear if QBO liability ties to TX filings.
2023 return filed; 2024 not filed. No IRS/state notices reported.
```

**INDUSTRY TYPE:**
```text
Restaurant (single-location café) + small retail (coffee beans). Toast POS.
Tipped employees. TX sales tax.
```

---

## The Agent's clarifying questions (Step 1)

> Before producing deliverables, I need to confirm a few things that affect scope,
> risk, and pricing:
>
> 1. How many bank and credit-card accounts total need reconciling, and over what date range?
> 2. Confirm the cleanup period — are we cleaning all of 2024 (Jan–Dec) for the tax return, or also catching up 2025 YTD?
> 3. Cash or accrual basis for the 2024 return — has the CPA specified?
> 4. Is inventory (coffee beans/retail) tracked in QBO, or expensed as purchased?
> 5. Are Toast payout reports (gross sales, fees, tips, sales tax) available for the full period?
> 6. Has TX sales tax actually been filed and remitted for 2024, or only collected?
> 7. Were any owner personal expenses run through the business accounts?

**Our answers:** 1 checking + 1 credit card, full year 2024 + 2025 YTD (June).
Cash basis per CPA. Beans expensed, not tracked as inventory. Toast reports available.
Sales tax filed quarterly but never tied to QBO. Yes, some personal expenses mixed in.

---

## Deliverable 1 — Cleanup Plan (abbreviated)

**Current state:** Books are unreliable for 2024–2025 YTD. Cash account reconciled
only through Feb 2024; credit card unreconciled ~9 months. ~$31k uncategorized. Toast
deposits are booked net (fees, tips, and sales tax buried in income), so revenue and
sales-tax liability are both misstated. Payroll is posted as lump-sum transfers.

| # | Issue | Why it matters | Severity | Est. effort |
|---|-------|----------------|----------|-------------|
| 1 | Credit card unreconciled ~9 mo | Expenses understated, balance unreliable | High | ~4 hrs |
| 2 | Toast deposits booked net | Revenue & sales-tax liability misstated | High | ~5 hrs |
| 3 | $31k uncategorized / Ask My Accountant | P&L meaningless until cleared | High | ~5 hrs |
| 4 | Payroll as lump-sum transfers | Wages/taxes not visible; P&L wrong | Medium | ~2 hrs |
| 5 | Personal expenses mixed in | Distorts P&L; owner-draw cleanup | Medium | ~2 hrs |
| 6 | OBE ~$11,200 uncleared | Balance sheet won't tie | Medium | ~1 hr |
| 7 | ~160-account COA with duplicates | Inconsistent reporting | Low | ~1.5 hrs |

**Phase 1 — Foundation:** Reconcile checking (Mar 2024→present) and credit card
(full period). Tie beginning balances to the 2023 return.
**Phase 2 — Categorize & correct:** Build a Toast deposit-splitting routine (gross
sales / merchant fees / tips payable / sales tax payable); clear uncategorized; map
Gusto payroll to wage & tax accounts; reclass personal spend to owner's draw; clean COA.
**Phase 3 — Refine & verify:** Tie sales-tax liability to filed TX returns; clear OBE;
run comparative P&L; lock periods; hand clean 2024 to CPA.

**What "done" looks like:** Both accounts reconciled with $0 unexplained difference;
$0 uncategorized; OBE cleared; revenue/sales tax/tips correctly split; 2024 ready for filing.

ASSUMPTION: Beans are expensed (no inventory tracking) per client.
→ Refer to CPA: confirmation of cash basis and whether any 2024 sales-tax amendments are needed.

---

## Deliverable 2 — Missing Documents List (abbreviated, client-facing)

**Access & logins**
- [ ] [REQUIRED] Accountant invite to QuickBooks Online — *to work in your books*
- [ ] [REQUIRED] View access to Gusto — *to map payroll correctly*
- [ ] [REQUIRED] Toast reporting access — *to split sales, fees, tips & tax*

**Bank & credit card**
- [ ] [REQUIRED] Checking statements Mar 2024 → present
- [ ] [REQUIRED] Credit-card statements full period (last ~12 mo)

**Tax & compliance**
- [ ] [REQUIRED] 2023 business tax return — *for beginning balances*
- [ ] [NEEDED] TX sales-tax returns filed for 2024–2025 — *to tie out liability*

**Other**
- [ ] [NEEDED] Note which recurring charges are personal vs. business

---

## Deliverable 3 — Risk Assessment (abbreviated, internal)

| Risk area | Likelihood | Impact | Mitigation |
|-----------|:---:|:---:|------------|
| Reconciliation backlog (9+ mo CC) | H | H | Phase 1; fixed fee per account |
| Revenue misstatement (Toast net) | H | H | Build deposit-split routine before P&L review |
| Sales-tax tie-out | M | H | Reconcile QBO liability to filed TX returns; → CPA if amendment |
| Payroll mapping | M | M | Map Gusto to wage/tax accounts |
| Personal/business commingling | H | M | Reclass to owner's draw; set go-forward rule |
| Tax deadline pressure (2024 unfiled) | H | H | Stage work to deliver clean 2024 first |

**Overall engagement risk: Moderate–High.**
**Pricing implication:** Recommend fixed-fee cleanup billed in 3 phases plus a 15%
contingency. Quote 2024 cleanup first (deadline-driven), then 2025 YTD. Do not give a
single flat number until credit-card statements confirm the backlog volume.

---

## Deliverable 4 — Onboarding Checklist (abbreviated)

**Engagement setup**
- [ ] Send engagement letter (fixed-fee, phased) and collect first payment
- [ ] Confirm cash basis + cleanup period (2024 full + 2025 YTD) in writing

**Access & tools**
- [ ] Accept QBO accountant invite; get Gusto + Toast access
- [ ] Confirm bank/CC feeds connected

**Books foundation**
- [ ] Tie beginning balances to 2023 return; clean chart of accounts

**Cleanup kickoff**
- [ ] Send Missing Documents List; start Phase 1 (reconcile cash)
- [ ] Build Toast deposit-splitting template

**Communication**
- [ ] Kickoff call: set 2024-first timeline, SLA, and monthly reporting format

---

## What this took

Inputs gathered from the questionnaire + a quick look at the books. The Agent
produced all four deliverables in one pass after seven clarifying questions — roughly
**10 minutes of AI time replacing 1–2 hours** of manual scoping write-up. The
bookkeeper reviewed, tightened the numbers, and sent the client-facing pieces the same day.
