# Module 2 — Month-End Close Agent

**Balance Operations Co. AI Bookkeeper Toolkit™**
*The AI Operating System for Modern Bookkeepers*

---

## What this module does

Onboarding (Module 1) and cleanup (Module 4) get a client in the door. **The monthly
close is what they actually pay you for, forever.** It's also the most repetitive part
of the job — the same checklist, the same accruals, the same "here's how the month went"
email, every client, every month.

The **Month-End Close Agent** turns your raw close data into three things that make the
close faster and more consistent.

```
   INPUTS                         AGENT                       OUTPUTS
┌──────────────────────┐                            ┌─────────────────────────────┐
│ Bank/CC balances     │                            │ 1. Month-End Checklist      │
│ Reconciliation notes │  ──► Month-End Close ────►  │ 2. Journal Entry Suggestions│
│ (client/industry)    │      Agent (Claude / GPT)   │ 3. Client Summary           │
└──────────────────────┘                            └─────────────────────────────┘
```

This is the engine of the recurring engagement you sold in **Module 6**. Run it every
month, for every client.

> ⚠️ The Agent **suggests** journal entries and flags discrepancies — it does not post
> to QBO and is not a substitute for your professional review. You verify and post.

---

## Who it's for

Professional bookkeepers (QuickBooks Online ecosystem) who:

- Run recurring monthly closes and want a **consistent, faster** process.
- Want a **client-ready monthly summary** drafted in seconds, not 30 minutes.
- Want a second set of eyes that **flags discrepancies and suggests the usual accruals**.

---

## What's in this folder

| File | What it is | When you use it |
|------|------------|-----------------|
| `README.md` | This overview + quick-start | Start here |
| `month-end-close-agent.md` | **The core copy-paste Agent prompt** + setup | Every monthly close |
| `inputs/close-intake-checklist.md` | The data the Agent needs (balances, recon notes, flags) | Before running the Agent |
| `outputs/month-end-checklist-template.md` | Format for Output 1 | Process / QA |
| `outputs/journal-entry-suggestions-template.md` | Format for Output 2 (review before posting) | Internal review |
| `outputs/client-summary-template.md` | Format for Output 3 (client-facing) | Send to client |
| `example-walkthrough.md` | Full worked example (Brightwave Café, June close) | Learn by example |

---

## Quick start (5 steps)

1. **Set up the Agent once.** Copy the prompt in `month-end-close-agent.md` into a
   Claude Project or ChatGPT custom GPT (instructions inside).
2. **Pull your close data.** Bank/CC ending balances, what reconciled (and what didn't),
   and any notes — see `inputs/close-intake-checklist.md`.
3. **Run the Agent.** It asks clarifying questions, then produces the checklist, JE
   suggestions, and a client summary.
4. **Review and post.** You verify every suggested JE and reconciliation item, then post
   in QBO. The Agent never touches the books.
5. **Send the summary.** Tidy the client summary in your voice and send it.

---

## ⚠️ Client-data privacy reminder

- **Anonymize identifiers** — no full SSNs/EINs, account numbers, or logins.
- **Summarize, don't dump** — ending balances, reconciliation status, and notes are
  enough. You don't need to paste the full register.
- **Use a business/team AI account** with data-retention controls for real client work.
- **You verify and post.** The Agent's JEs are suggestions for your review, not entries.

---

## How this fits the bigger toolkit

- It's the **monthly delivery engine** for the recurring engagement priced in **Module 6**.
- The **Client Summary** can be sent via **Module 3** (Client Communication Agent).
- Turn the **Month-End Checklist** into a firm-wide recurring template with **Module 5** (SOP Builder).
- After a **Module 4** cleanup establishes a clean cutoff, this is what keeps the books current.

Standalone today; the recurring heartbeat of the whole system.
