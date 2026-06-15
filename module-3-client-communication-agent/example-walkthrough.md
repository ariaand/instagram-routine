# Example Walkthrough — Client Communication Agent

**Module 3 — Balance Operations Co. AI Bookkeeper Toolkit™**

Three real situations from the same fictional client world
([Brightwave Café](../module-1-client-onboarding-agent/example-walkthrough.md)) run
through the Client Communication Agent. Each shows the input and the finished email.

---

## Situation 1 — Chasing a document mid-close

**What we told the Agent:**
```text
EMAIL TYPE / GOAL: Ask the client what a $1,200 charge was for so I can finish the June close.
CONTEXT: Brightwave Café, owner Sam, long-time easygoing client. Charge: 6/14, $1,200,
merchant "SQ *NORTHSIDE". Sitting in Ask My Accountant.
TONE: friendly
CONSTRAINTS: very short. Sign-off Aria, Balance Operations Co.
```

**The Agent's draft:**

> **Subject:** Quick question on a June charge
>
> Hi Sam,
>
> I'm wrapping up your June books and hit one charge I want to categorize correctly:
>
> **6/14 — $1,200 — "SQ \*NORTHSIDE"**
>
> What was this one for? A quick word (supplies, equipment, personal?) and you're all set.
>
> Thanks!
> Aria · Balance Operations Co.

---

## Situation 2 — Late-payment ladder (first → final)

**What we told the Agent:**
```text
EMAIL TYPE / GOAL: Late-payment reminders for invoice 1042, $750, due June 1. Give me
first, second, and final versions.
CONTEXT: Brightwave Café, Sam. Good client, just forgetful. Payment link: pay.balanceops.co/1042.
TONE: warm-professional, escalating to firm on the final.
CONSTRAINTS: short. Final notice should mention work pausing per our agreement.
```

**The Agent's drafts (abbreviated):**

> **First (June 8) — Subject: Invoice 1042 — a quick reminder**
> Hi Sam, friendly heads-up that invoice 1042 for $750 (due June 1) looks outstanding —
> easy to miss! Pay here: pay.balanceops.co/1042. If it's already on its way, ignore me. — Aria
>
> **Second (June 18) — Subject: Second notice: invoice 1042 (17 days past due)**
> Hi Sam, following up on invoice 1042 for $750, now 17 days past due. Want to make sure
> it didn't get buried. Status or payment via pay.balanceops.co/1042? Happy to help if
> something's holding it up. — Aria
>
> **Final (June 28) — Subject: Action needed: invoice 1042 past due**
> Hi Sam, I've reached out a couple of times about invoice 1042 ($750), now 27 days
> overdue. Please arrange payment via pay.balanceops.co/1042 by July 3, or reply and
> we'll work out a plan. If I don't hear back, work on your account will pause until the
> balance clears, per our agreement. I value working with you and want to keep things on
> track. — Aria

*Saved as a sequence — reusable for any client with placeholders.*

---

## Situation 3 — Delivering a so-so month

**What we told the Agent:**
```text
EMAIL TYPE / GOAL: Deliver June report. Revenue was down ~12% vs May; I don't want to
alarm Sam but should be honest.
CONTEXT: Brightwave Café. Checking $18,200, card $4,650. June sales ~$52k vs ~$59k in
May (seasonal dip — summer slow for them historically).
TONE: warm-professional, reassuring.
CONSTRAINTS: short, end with offer to call. Sign-off Aria, Balance Operations Co.
```

**The Agent's draft:**

> **Subject:** Your June books are closed 📊
>
> Hi Sam,
>
> June is reconciled and closed. Quick recap:
>
> **Cash:** Checking $18,200 · card balance $4,650.
>
> **The month:** Sales came in around $52k, down about 12% from May — which lines up with
> the summer slowdown you usually see this time of year, so nothing to worry about. Costs
> stayed in line.
>
> Reports are in your portal. If you'd like, we can hop on a quick call to look at the
> seasonal trend and plan for it — just say the word.
>
> Thanks,
> Aria · Balance Operations Co.

---

## What this took

Each email: one short prompt, one pass, ready to send after a quick read — **seconds
instead of the 5–10 minutes** these messages usually take to get right (especially the
awkward ones). Teaching the Agent Aria's voice once made every draft sound like her.

> The Agent drafts; the bookkeeper reads and sends. Nothing goes out unreviewed.
