# Module 3 — Client Communication Agent

**Balance Operations Co. AI Bookkeeper Toolkit™**
*The AI Operating System for Modern Bookkeepers*

---

## What this module does

Bookkeeping is a communication business as much as a numbers business. The clients who
churn usually aren't unhappy with the books — they're unhappy with the silence, the
awkward "you owe me money" email, or the report that arrives with no explanation. And
writing those messages well, every time, is a quiet daily tax on your time.

The **Client Communication Agent** writes the everyday client emails for you — in your
voice, professional, and ready to send.

```
            AGENT                           OUTPUTS (on demand)
┌──────────────────────────┐        ┌──────────────────────────────────┐
│                          │        │ • Missing-document requests       │
│   Client Communication   │  ───►  │ • Late-payment reminders (3 levels)│
│   Agent (Claude / GPT)   │        │ • Monthly report / summary emails │
│                          │        │ • Discovery-call follow-ups       │
└──────────────────────────┘        │ • + welcome, price increase, etc. │
                                     └──────────────────────────────────┘
```

You get two things: a **ready-to-use template library** (grab and fill) and a
**generator prompt** (describe the situation, get a tailored email in seconds).

---

## Who it's for

Professional bookkeepers (QuickBooks Online ecosystem) who:

- Want **professional, consistent client emails** without writing each one from scratch.
- Dread the **awkward ones** (late payment, price increase, chasing documents) and want
  them handled with the right tone.
- Want to **respond faster** and look polished at every client touchpoint.

---

## What's in this folder

| File | What it is | When you use it |
|------|------------|-----------------|
| `README.md` | This overview + quick-start | Start here |
| `client-communication-agent.md` | **The core copy-paste Agent prompt** + setup | When you want a tailored email |
| `outputs/email-template-library.md` | **12 ready-to-send templates** with subject lines | Grab, fill, send |
| `inputs/communication-intake-checklist.md` | What to tell the Agent to get a great email | Before generating |
| `example-walkthrough.md` | Worked examples (a few real situations → emails) | Learn by example |

---

## Quick start (two ways to use it)

**Fast path — template library:** open `outputs/email-template-library.md`, find the
email you need, fill the `{{PLACEHOLDERS}}`, send. Done in under a minute.

**Tailored path — the Agent:**
1. **Set up the Agent once.** Copy the prompt in `client-communication-agent.md` into a
   Claude Project or ChatGPT custom GPT.
2. **Describe the situation** (who, what, tone, any specifics) — see
   `inputs/communication-intake-checklist.md`.
3. **Get 1–2 versions**, pick one, tweak, and send.

---

## ⚠️ Client-data privacy reminder

- **Anonymize identifiers** — you don't need to include account numbers or sensitive
  detail in an email draft; use `{{PLACEHOLDERS}}`.
- **Use a business/team AI account** with data-retention controls for real client work.
- **Read before you send.** The Agent drafts; you're responsible for what goes out.

---

## How this fits the bigger toolkit

- The **missing-document request** pairs with Module 1's Missing Documents List and
  Module 4's cleanup doc requests.
- The **monthly report email** delivers Module 2's Client Summary.
- The **discovery-call follow-up** and **proposal follow-up** support Module 4 and
  Module 6 sales.
- Standardize your client comms into firm SOPs with Module 5.

Standalone today; the voice of your firm across every other module.
