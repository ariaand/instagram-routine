# Setup Guide — Install the Toolkit as Claude Projects & ChatGPT GPTs

**Balance Operations Co. AI Bookkeeper Toolkit™**

This pack turns each of the six agents into a **reusable assistant** you set up once and
use forever — as a **Claude Project** or a **ChatGPT custom GPT**. After setup, you just
start a chat and paste the job's inputs; the assistant already knows its role.

> **One-time setup, ~10 minutes per agent.** Do the ones you'll use most first (Onboarding,
> Month-End Close, and Communication are the daily drivers).

---

## What's in this folder

| File | What it's for |
|------|---------------|
| `README.md` | This guide |
| `agent-instructions/1-client-onboarding.md` | Paste-ready instructions for Module 1 |
| `agent-instructions/2-month-end-close.md` | Module 2 |
| `agent-instructions/3-client-communication.md` | Module 3 |
| `agent-instructions/4-cleanup-project.md` | Module 4 |
| `agent-instructions/5-sop-builder.md` | Module 5 |
| `agent-instructions/6-proposal-generator.md` | Module 6 |

Each `agent-instructions/*.md` contains: **(1)** the exact instructions to paste, **(2)** the
knowledge files to attach, and **(3)** what to paste in each new chat.

---

## Option A — Claude Projects (recommended)

Claude Projects let you set custom instructions and attach reference files ("Project
knowledge") that every chat in the project can see.

1. In Claude, click **Projects → Create Project**. Name it after the agent, e.g.
   **"Client Onboarding Agent."**
2. Open the project's **custom instructions** (set/edit instructions).
3. Open the matching `agent-instructions/<n>-*.md`, copy **everything inside the
   "Instructions to paste" code block**, and paste it into the custom instructions. Save.
4. **Add knowledge:** upload the files listed under "Recommended knowledge files to
   attach" (the module's input/output templates) so the agent matches your formats.
5. *(Optional)* Add a line to the instructions with your firm name, voice, rates, and
   sign-off so output is on-brand. (See "Personalize" below.)
6. **Use it:** start a new chat in the project and paste the job's inputs (item 3 in the
   agent file). The agent asks its clarifying questions, then produces the deliverables.

Repeat for each agent you want. Six projects = your whole firm's AI back office.

---

## Option B — ChatGPT custom GPTs

1. In ChatGPT, go to **Explore GPTs → Create** (or **My GPTs → Create a GPT**).
2. In the **Configure** tab, set a name (e.g., "Cleanup Project Agent").
3. Paste the "Instructions to paste" block into the **Instructions** field.
4. Under **Knowledge**, upload the recommended template files for that agent.
5. *(Optional)* Personalize with your firm details. Save (Only me is fine).
6. **Use it:** open the GPT and paste the job's inputs into a new chat.

> No Projects/GPTs? You can still paste an `agent-instructions` block at the top of any
> normal chat, then paste your inputs underneath. Setup just makes it reusable.

---

## Personalize each agent (optional but worth it)

Add a short block like this to the end of any agent's instructions so output is on-brand
and on-price:

```text
# FIRM PROFILE (use this in all output)
- Firm name: {{Balance Operations Co.}}
- Voice: {{warm, sharp, no-nonsense}}
- Sign-off: {{Aria, Balance Operations Co.}}
- Default pricing model: {{e.g., tiered fixed-fee; target effective rate $75/hr}}
- Tools we use: {{QBO, Gusto, Keeper, ClickUp}}
```

For the **Client Communication Agent**, also paste 2–3 of your real client emails and add
"Match this voice in everything you draft." It makes every draft sound like you.

---

## ⚠️ Privacy reminders for client data
- **Anonymize** before pasting: no full SSNs/EINs, account numbers, or passwords.
- **Summarize, don't dump** the general ledger — balances, statuses, and notes are enough.
- Use a **business/team** Claude or ChatGPT account with data-retention controls for real
  client work.
- The agents **draft and suggest** — you review, verify, and post/send. (The Month-End
  Close Agent never posts to QBO.)

---

## Suggested setup order
1. **Month-End Close Agent** — you'll use it every month, for every client.
2. **Client Communication Agent** — used constantly; biggest daily time-saver.
3. **Client Onboarding Agent** — for every new client.
4. **Cleanup Project Agent** + **Proposal Generator** — your sales engine.
5. **SOP Builder Agent** — when you're ready to document and delegate.

Once set up, your workflow is simply: *open the right agent → paste the inputs → review →
send/post.*
