# Module 6 — Proposal Generator

**Balance Operations Co. AI Bookkeeper Toolkit™**
*The AI Operating System for Modern Bookkeepers*

---

## What this module does

Where **Module 4** prices a one-time cleanup, **Module 6** prices the thing that
actually builds your firm: the **recurring monthly engagement**. Most bookkeepers
quote monthly fees by gut feel, undercharge to win the deal, and then resent the
client at month four. This module fixes that.

The **Proposal Generator** takes three simple inputs and turns them into a
right-priced, right-scoped recurring engagement.

```
   INPUTS                       AGENT                        OUTPUTS
┌──────────────────────┐                            ┌─────────────────────────────┐
│ Industry             │                            │ 1. Service Package          │
│ Revenue              │  ──► Proposal Generator ──► │ 2. Customized Proposal      │
│ Complexity           │      (Claude / GPT)         │ 3. Pricing Recommendation   │
└──────────────────────┘                            └─────────────────────────────┘
```

It pairs with the rest of the toolkit: pull **complexity** straight from Module 1's
**Risk Assessment**, and offer it as the "what happens after cleanup" Option C in
Module 4's proposal.

---

## Who it's for

Professional bookkeepers (QuickBooks Online ecosystem) who:

- Want to **price monthly engagements with confidence** instead of guessing.
- Want **productized service tiers** (Starter / Growth / Premium) rather than custom quotes every time.
- Want a **client-ready proposal** that justifies the price and anchors to value, not hours.

---

## What's in this folder

| File | What it is | When you use it |
|------|------------|-----------------|
| `README.md` | This overview + quick-start | Start here |
| `proposal-generator-agent.md` | **The core copy-paste Agent prompt** + setup | Every new monthly deal |
| `inputs/proposal-intake-checklist.md` | The data points that set scope & price | Before running the Agent |
| `inputs/service-packages-and-pricing.md` | Your tier definitions + pricing frameworks to feed the Agent | While running the Agent |
| `outputs/service-package-template.md` | Format for Output 1 (the recommended tier + add-ons) | Reference / internal |
| `outputs/monthly-proposal-template.md` | Format for Output 2 (client-facing proposal) | Send to client |
| `outputs/pricing-recommendation-template.md` | Format for Output 3 (internal price justification) | Internal pricing |
| `example-walkthrough.md` | Full worked example (Brightwave Café monthly) | Learn by example |

---

## Quick start (5 steps)

1. **Set up the Agent once.** Copy the prompt in `proposal-generator-agent.md` into a
   Claude Project or ChatGPT custom GPT (instructions inside).
2. **Gather inputs.** Industry, annual revenue, and complexity — see
   `inputs/proposal-intake-checklist.md`. (If you ran Module 1, complexity is already in your Risk Assessment.)
3. **Set your tiers.** Paste your package definitions and pricing from
   `inputs/service-packages-and-pricing.md` so output matches how you actually sell.
4. **Run the Agent.** It asks clarifying questions, then recommends a package, writes a
   proposal, and justifies the price.
5. **Review and send.** Confirm the fee clears your floor, then send the proposal.
   Keep the pricing recommendation internal.

---

## ⚠️ Client-data privacy reminder

- **Anonymize identifiers** — no full SSNs/EINs, account numbers, or logins.
- **Summarize, don't dump** — revenue band, transaction volume, and complexity flags
  are all the Agent needs.
- **Use a business/team AI account** with data-retention controls for real client work.
- **Pricing is your decision** — the Agent recommends; you set the final number.

---

## How this fits the bigger toolkit

- **Complexity** input comes from **Module 1** (Risk Assessment) — paste it straight in.
- This is the natural **Option C** in **Module 4**'s cleanup proposal (cleanup → monthly).
- Service tiers defined here become recurring delivery templates via **Module 5** (SOP Builder)
  and run through **Module 2** (Month-End Close).

Standalone today; the connective tissue of a productized firm tomorrow.
