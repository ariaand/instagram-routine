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
| 2 | Month-End Close Agent | Planned |
| 3 | Client Communication Agent | Planned |
| **4** | **Cleanup Project Agent** | ✅ Built |
| 5 | SOP Builder Agent | Planned |
| 6 | Proposal Generator | Planned |
| Bonus | QuickBooks Cleanup Toolkit · Content Engine · Discovery Call Assistant | Planned |

We're building **one module at a time**. Modules 1 and 4 form the spine of the MVP:
onboard a client and diagnose the books, then turn that diagnosis into a sellable,
profitable cleanup engagement.

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
