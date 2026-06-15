# Module 1 — Client Onboarding Agent

**Balance Operations Co. AI Bookkeeper Toolkit™**
*The AI Operating System for Modern Bookkeepers*

---

## What this module does

Onboarding a new bookkeeping client is the highest-stakes, most time-consuming
part of the engagement. Do it well and the relationship runs smoothly for years.
Do it poorly and you inherit a mess you priced wrong, chase documents for months,
and quietly lose money.

The **Client Onboarding Agent** turns three inputs into four client-ready
deliverables in minutes instead of hours.

```
   INPUTS                         AGENT                     OUTPUTS
┌────────────────────┐                              ┌──────────────────────────┐
│ Client questionnaire│                             │ 1. Cleanup Plan          │
│ Prior financials    │  ──►  Client Onboarding ──► │ 2. Missing Documents List│
│ Industry type       │       Agent (Claude/GPT)    │ 3. Risk Assessment       │
└────────────────────┘                              │ 4. Onboarding Checklist  │
                                                     └──────────────────────────┘
```

You stay the professional in charge — the Agent does the drafting, organizing,
and first-pass analysis. You review, adjust, and send.

---

## Who it's for

Professional bookkeepers (QuickBooks Online ecosystem) who:

- Take on new monthly/recurring clients and want a repeatable intake process.
- Inherit messy books and need a fast, defensible cleanup plan.
- Want to look organized and senior from the very first client interaction.

---

## What's in this folder

| File | What it is | When you use it |
|------|------------|-----------------|
| `README.md` | This overview + quick-start | Start here |
| `client-onboarding-agent.md` | **The core copy-paste Agent prompt** + setup instructions | Every new client |
| `inputs/client-onboarding-questionnaire.md` | Intake questionnaire you send the client | Before the kickoff |
| `inputs/prior-financials-checklist.md` | What financials/files to collect & how to feed them to the Agent | Before running the Agent |
| `inputs/industry-profiles.md` | Industry-specific context to paste in for sharper output | While running the Agent |
| `outputs/cleanup-plan-template.md` | Format the Agent fills for Output 1 | Reference / manual edits |
| `outputs/missing-documents-list-template.md` | Format for Output 2 | Reference / send to client |
| `outputs/risk-assessment-template.md` | Format for Output 3 | Internal scoping & pricing |
| `outputs/onboarding-checklist-template.md` | Format for Output 4 | Project management |
| `example-walkthrough.md` | A full worked example (Brightwave Café) start to finish | Learn by example |

---

## Quick start (5 steps)

1. **Set up the Agent once.** Open `client-onboarding-agent.md`, copy the Agent
   prompt into a new Claude Project or ChatGPT custom GPT (instructions inside).
2. **Send the questionnaire.** Email the client `inputs/client-onboarding-questionnaire.md`
   (or a Google Form built from it). Collect their answers.
3. **Gather prior financials.** Use `inputs/prior-financials-checklist.md` to know
   what to ask for.
4. **Run the Agent.** Paste the questionnaire answers, a summary of the prior
   financials, and the industry type. The Agent asks clarifying questions, then
   produces all four deliverables.
5. **Review and send.** Sanity-check the output (you're the professional), then
   send the Missing Documents List and Onboarding Checklist to the client, and
   keep the Cleanup Plan and Risk Assessment for scoping/pricing.

---

## ⚠️ Client-data privacy reminder

You're handling sensitive financial data. Before pasting anything into an AI tool:

- **Anonymize identifiers.** Strip full SSNs/EINs, full bank account and card
  numbers, login credentials, and personal addresses. The Agent doesn't need them.
- **Summarize, don't dump.** You rarely need to paste a full general ledger.
  Paste balances, account names, totals, and notes — that's enough for analysis.
- **Use a business/team AI account** with data-retention controls where available,
  not a free consumer tier, when working with real client data.
- **Get client consent** for using AI tooling if your engagement letter requires it.

---

## How this fits the bigger toolkit

Module 1 is the front door. Its outputs feed directly into later modules:

- The **Cleanup Plan** → Module 4 (Cleanup Project Agent) for full scope/proposal.
- The **Risk Assessment** → Module 6 (Proposal Generator) for pricing.
- The **Onboarding Checklist** → Module 5 (SOP Builder) to standardize your firm's process.

For now, this module stands on its own and delivers value by itself.
