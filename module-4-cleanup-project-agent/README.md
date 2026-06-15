# Module 4 — Cleanup Project Agent

**Balance Operations Co. AI Bookkeeper Toolkit™**
*The AI Operating System for Modern Bookkeepers*

---

## What this module does

Cleanup (and catch-up) is one of the highest-demand, highest-margin services a
bookkeeper sells — and the easiest to under-price. Most bookkeepers eyeball a number,
quote it on a call, and then quietly eat the overage when the "small cleanup" turns
out to be 14 unreconciled months across three accounts.

The **Cleanup Project Agent** turns what you already know about a messy set of books
into a sellable, profitable, defensible engagement.

```
   INPUTS                          AGENT                       OUTPUTS
┌──────────────────────────┐                          ┌──────────────────────────┐
│ Cleanup Plan (Module 1)  │                          │ 1. Cleanup Scope         │
│ Risk Assessment (Mod 1)  │  ──► Cleanup Project ──►  │ 2. Cleanup Proposal      │
│ Volume metrics           │      Agent (Claude/GPT)   │ 3. Project Timeline      │
│ Your pricing model       │                          │ 4. Pricing Estimate      │
└──────────────────────────┘                          └──────────────────────────┘
```

It pairs directly with **Module 1 (Client Onboarding Agent)**: feed Module 1's
Cleanup Plan and Risk Assessment straight in. (You can also run Module 4 standalone
by describing the books yourself.)

---

## Who it's for

Professional bookkeepers (QuickBooks Online ecosystem) who:

- Sell cleanup / catch-up projects and want to **price them so they're profitable**.
- Need a **written scope** that prevents scope creep and "while you're in there..." requests.
- Want a **client-ready proposal** they can send the same day as the discovery call.

---

## What's in this folder

| File | What it is | When you use it |
|------|------------|-----------------|
| `README.md` | This overview + quick-start | Start here |
| `cleanup-project-agent.md` | **The core copy-paste Agent prompt** + setup | Every cleanup deal |
| `inputs/cleanup-intake-checklist.md` | The data points the Agent needs to scope/price accurately | Before running the Agent |
| `inputs/pricing-models.md` | Pricing frameworks (per-account, per-month, hourly, value) to feed the Agent | While running the Agent |
| `outputs/cleanup-scope-template.md` | Format for Output 1 (scope: in/out) | Reference / client-facing |
| `outputs/cleanup-proposal-template.md` | Format for Output 2 (full proposal) | Send to client |
| `outputs/cleanup-timeline-template.md` | Format for Output 3 (phased timeline) | Client + project mgmt |
| `outputs/pricing-estimate-template.md` | Format for Output 4 (internal cost/price build-up) | Internal pricing |
| `example-walkthrough.md` | Full worked example (Brightwave Café cleanup) | Learn by example |

---

## Quick start (5 steps)

1. **Set up the Agent once.** Copy the prompt in `cleanup-project-agent.md` into a
   Claude Project or ChatGPT custom GPT (instructions inside).
2. **Gather inputs.** Bring Module 1's Cleanup Plan + Risk Assessment, plus the volume
   metrics in `inputs/cleanup-intake-checklist.md` (months, accounts, transaction volume).
3. **Pick your pricing model.** Paste the relevant block from `inputs/pricing-models.md`
   so the estimate matches how you actually bill.
4. **Run the Agent.** It asks clarifying questions, then produces scope, proposal,
   timeline, and a pricing estimate with tiered options.
5. **Review and send.** Sanity-check the hours and price (you're the professional),
   then send the proposal. Keep the pricing build-up internal.

---

## ⚠️ Client-data privacy reminder

Same rules as the rest of the toolkit:

- **Anonymize identifiers** — no full SSNs/EINs, account numbers, or logins.
- **Summarize, don't dump** — counts, balances, and reconciliation status are enough
  to scope and price. You never need the full GL in the prompt.
- **Use a business/team AI account** with data-retention controls for real client work.
- Pricing is your business decision — **the Agent estimates; you set the final number.**

---

## How this fits the bigger toolkit

- **Inputs** come from **Module 1** (Cleanup Plan + Risk Assessment).
- The **Pricing Estimate** and **Scope** feed **Module 6** (Proposal Generator) for the
  ongoing monthly engagement that follows cleanup.
- The **Timeline** becomes a recurring project template via **Module 5** (SOP Builder).

Standalone today; even better once you own the modules around it.
