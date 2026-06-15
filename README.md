# Balance Operations Co. AI Bookkeeper Toolkit™

**The AI Operating System for Modern Bookkeepers**

A complete system that helps professional bookkeepers make money, save time, and look
smarter to clients — by showing them *exactly* how to use Claude and ChatGPT to run
their firm. Not "a bunch of prompts": a set of reusable AI **agents**, the inputs they
need, and the client-ready outputs they produce.

---

## The full product (roadmap)

| Module | Name | Status |
|--------|------|:------:|
| **1** | **Client Onboarding Agent** | ✅ Built |
| **2** | **Month-End Close Agent** | ✅ Built |
| **3** | **Client Communication Agent** | ✅ Built |
| **4** | **Cleanup Project Agent** | ✅ Built |
| **5** | **SOP Builder Agent** | ✅ Built |
| **6** | **Proposal Generator** | ✅ Built |
| **Bonus** | **QuickBooks Cleanup Toolkit · Content Engine · Discovery Call Assistant** | ✅ Built |

**All six core agents are built** — plus the three bonus toolkits. Together they run the
full client journey: onboard and diagnose the books (1) → sell the one-time cleanup (4) →
sell the recurring monthly engagement (6) → deliver the monthly close (2) → communicate at
every touchpoint (3) → document and delegate the whole thing (5).

---

## ▶ Module 1 — Client Onboarding Agent (available now)

Turn three inputs (client questionnaire, prior financials, industry type) into four
client-ready deliverables (cleanup plan, missing-documents list, risk assessment,
onboarding checklist).

**Start here → [`module-1-client-onboarding-agent/README.md`](./module-1-client-onboarding-agent/README.md)**

```
module-1-client-onboarding-agent/
├── README.md                         ← module overview + quick start
├── client-onboarding-agent.md        ← THE copy-paste Agent prompt
├── example-walkthrough.md            ← full worked example (Brightwave Café)
├── inputs/
│   ├── client-onboarding-questionnaire.md
│   ├── prior-financials-checklist.md
│   └── industry-profiles.md
└── outputs/
    ├── cleanup-plan-template.md
    ├── missing-documents-list-template.md
    ├── risk-assessment-template.md
    └── onboarding-checklist-template.md
```

---

## ▶ Module 4 — Cleanup Project Agent (available now)

Turn what you know about a messy set of books (ideally Module 1's Cleanup Plan + Risk
Assessment) into a sellable, profitable engagement: scope, client-ready proposal with
tiered options, phased timeline, and an internal pricing build-up.

**Start here → [`module-4-cleanup-project-agent/README.md`](./module-4-cleanup-project-agent/README.md)**

```
module-4-cleanup-project-agent/
├── README.md                         ← module overview + quick start
├── cleanup-project-agent.md          ← THE copy-paste Agent prompt
├── example-walkthrough.md            ← worked example (Brightwave Café cleanup)
├── inputs/
│   ├── cleanup-intake-checklist.md   (the cost drivers)
│   └── pricing-models.md             (per-account / hourly / fixed / tiered)
└── outputs/
    ├── cleanup-scope-template.md
    ├── cleanup-proposal-template.md
    ├── cleanup-timeline-template.md
    └── pricing-estimate-template.md
```

> 🔗 Module 1 → Module 4: feed Module 1's **Cleanup Plan** and **Risk Assessment**
> straight into the Cleanup Project Agent.

---

## ▶ Module 6 — Proposal Generator (available now)

Price the **recurring monthly** engagement (where Module 4 prices the one-time cleanup).
Three inputs — industry, revenue, complexity — become a recommended service package, a
client-ready proposal, and an internal pricing recommendation.

**Start here → [`module-6-proposal-generator/README.md`](./module-6-proposal-generator/README.md)**

```
module-6-proposal-generator/
├── README.md                         ← module overview + quick start
├── proposal-generator-agent.md       ← THE copy-paste Agent prompt
├── example-walkthrough.md            ← worked example (Brightwave Café monthly)
├── inputs/
│   ├── proposal-intake-checklist.md  (industry, revenue, complexity)
│   └── service-packages-and-pricing.md (Starter / Growth / Premium tiers)
└── outputs/
    ├── service-package-template.md
    ├── monthly-proposal-template.md
    └── pricing-recommendation-template.md
```

> 🔗 Module 1 → Module 6: feed Module 1's **Risk Assessment** in as the complexity
> input. And Module 6 is the natural "Option C" that follows a Module 4 cleanup.

---

## ▶ Module 2 — Month-End Close Agent (available now)

The recurring delivery engine. Each month, turn bank/CC balances + reconciliation notes
into a tailored month-end checklist, suggested journal entries (for your review — the
Agent never posts), and a client-ready summary.

**Start here → [`module-2-month-end-close-agent/README.md`](./module-2-month-end-close-agent/README.md)**

```
module-2-month-end-close-agent/
├── README.md                         ← module overview + quick start
├── month-end-close-agent.md          ← THE copy-paste Agent prompt
├── example-walkthrough.md            ← worked example (Brightwave Café, June close)
├── inputs/
│   └── close-intake-checklist.md     (balances, recon notes, recurring items)
└── outputs/
    ├── month-end-checklist-template.md
    ├── journal-entry-suggestions-template.md
    └── client-summary-template.md
```

> ⚠️ The Agent **suggests and flags** — it does not post to QuickBooks. You verify every
> entry and post it yourself.

---

## ▶ Module 3 — Client Communication Agent (available now)

The voice of your firm. A 12-email ready-to-send template library **plus** an on-demand
generator for the everyday client emails: missing-document requests, late-payment
reminders (first/second/final), monthly report delivery, discovery-call follow-ups, and
more.

**Start here → [`module-3-client-communication-agent/README.md`](./module-3-client-communication-agent/README.md)**

```
module-3-client-communication-agent/
├── README.md                         ← module overview + quick start
├── client-communication-agent.md     ← THE copy-paste Agent prompt
├── example-walkthrough.md            ← worked examples (real situations → emails)
├── inputs/
│   └── communication-intake-checklist.md
└── outputs/
    └── email-template-library.md     (12 ready-to-send templates)
```

> 🔗 Delivers Module 2's client summary, supports Module 4 & 6 sales follow-ups, and
> pairs with Module 1's missing-documents list.

---

## ▶ Module 5 — SOP Builder Agent (available now)

How the firm scales beyond you. Describe any workflow (rough is fine) and get back a
full SOP, a working checklist, and a new-hire training document — so you can delegate,
hire, and stay consistent.

**Start here → [`module-5-sop-builder-agent/README.md`](./module-5-sop-builder-agent/README.md)**

```
module-5-sop-builder-agent/
├── README.md                         ← module overview + quick start
├── sop-builder-agent.md              ← THE copy-paste Agent prompt
├── example-walkthrough.md            ← worked example (weekly categorization → 3 docs)
├── starter-sop-library.md            ← the 10 SOPs every firm should build, in order
├── inputs/
│   └── workflow-intake-guide.md
└── outputs/
    ├── sop-template.md
    ├── checklist-template.md
    └── training-document-template.md
```

> 🔗 Turn Modules 1, 2, and 4's checklists into permanent firm SOPs — and document how
> your team runs every agent consistently.

---

## ▶ Bonus Toolkits (available now)

Three standalone products that extend the core agents — each usable on its own or
sellable separately.

**Start here → [`bonus/README.md`](./bonus/README.md)**

- **QuickBooks Cleanup Toolkit** — diagnostic questionnaire, full QBO audit checklist, and a phased cleanup workflow (pairs with Modules 1 & 4).
- **Bookkeeper Content Engine** — content strategy + AI prompts for Instagram posts, carousels, LinkedIn, and newsletters, with 30 ready ideas and written examples (pairs with Module 3).
- **AI Discovery Call Assistant** — call script + note template + prompts that turn raw notes into a scope of work, proposal draft, and follow-up email (pairs with Modules 4 & 6).

---

## ▶ Setup Pack — install as Claude Projects / ChatGPT GPTs (available now)

Turn each agent into a reusable assistant you set up once. Paste-ready instruction files
for all six agents + a step-by-step guide for Claude Projects and ChatGPT custom GPTs.

**Start here → [`setup/README.md`](./setup/README.md)**

```
setup/
├── README.md                     ← Claude Projects + ChatGPT GPT setup guide
└── agent-instructions/
    ├── 1-client-onboarding.md    ← paste-ready instructions (per agent)
    ├── 2-month-end-close.md
    ├── 3-client-communication.md
    ├── 4-cleanup-project.md
    ├── 5-sop-builder.md
    └── 6-proposal-generator.md
```

---

## ▶ Prompt Library — 50 single-task prompts (available now)

Quick, copy-paste prompts for one-off jobs (the module agents are full workflows; the
library is for fast single tasks). 50 prompts across 5 categories.

**Start here → [`prompt-library/README.md`](./prompt-library/README.md)**

- `01` Client onboarding & cleanup · `02` Month-end close & reconciliation · `03` Client communication & emails · `04` Sales, proposals & pricing · `05` Firm operations & marketing — **10 prompts each.**

## ▶ SOP Library — 10 ready-to-adopt SOPs (available now)

Ten fully written standard operating procedures a firm can adopt and customize today
(Module 5 generates *new* SOPs from your workflows; this gives you the core 10 done).

**Start here → [`sop-library/README.md`](./sop-library/README.md)**

- Onboarding · Weekly categorization · Reconciliation · Month-end close · Cleanup · AP/bill pay · AR/invoicing & collections · Client reporting · Payroll · Year-end/1099 & CPA handoff.

---

## Packaging (planned)

- **Starter — $97:** MVP (onboarding + cleanup + proposal agents, 50 prompts, SOP library)
- **Pro — $297:** All 6 agents + templates + bonus toolkits
- **Premium — $497:** Everything + advanced workflows

---

## ⚠️ Using AI with client data — read this

These tools work with sensitive financial information. Before pasting anything into an
AI tool: **anonymize** identifiers (no full SSNs/EINs/account numbers/passwords),
**summarize** rather than dumping full ledgers, use a **business/team AI account** with
data-retention controls, and confirm client **consent** if your engagement requires it.

*Nothing in this toolkit is tax or legal advice. Flag items that need a CPA or attorney.*
