# AI-Powered B2B SaaS PLG Trial-to-Paid Conversion Nurture Architecture & Behavioral Trigger Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, saas, plg, email, automation, trial-conversion, nurture, behavioral-triggers, revenue

## Overview
This prompt engineers a complete Product-Led Growth (PLG) trial-to-paid conversion nurture system that uses behavioral triggers, in-product usage signals, and milestone-based email sequences to convert free trial users into paying customers — fully automated, zero manual SDR intervention required. Use it when you have a free trial, freemium tier, or self-serve motion and need to systematically move trial-to-paid conversion rates above the industry average of 2–5%.

## Quick Copy-Paste Version

You are a PLG conversion specialist with 15 years of experience turning free trial users into paying customers for B2B SaaS companies.

Design a complete trial-to-paid email nurture system for my product:

PRODUCT CONTEXT:
- Product: [name and one-sentence description]
- Trial length: [14 / 21 / 30 days]
- Trial type: [time-limited / feature-limited / usage-limited / freemium]
- Key activation milestone (AHA moment): [the single action most correlated with paid conversion — e.g., "first report generated," "first team member invited," "first integration connected"]
- Primary buyer: [job title and company size]
- Pricing entry point: [$ per user/month or flat monthly rate]
- Top 3 reasons trials don't convert: [list from win/loss data or customer interviews — or your best guess]

DELIVERABLES:

1. BEHAVIORAL TRIGGER MAP
Define 10 behavioral triggers (actions taken OR not taken) that predict conversion or churn, with priority scores (Critical / High / Medium).

2. THREE-TRACK EMAIL SEQUENCE ARCHITECTURE
Design parallel tracks based on product engagement:
- Track A (Champion): User hit activation milestone → Conversion-focused sequence
- Track B (Partial): Signed up, some usage, missed activation milestone → Activation + conversion sequence
- Track C (Ghost): No meaningful product activity within 72 hours → Rescue sequence

3. FULL EMAIL SCRIPTS
For every email in all three tracks, provide:
- Trigger condition and exact send timing
- Subject line (include an A/B variant)
- Preview text (50–70 characters)
- Full email body (conversational, under 250 words — no corporate-speak)
- Primary CTA (button text and destination)

4. CONVERSION GATE EMAILS
Write 3 instant-trigger emails fired by:
- User hitting usage limit / paywall
- Trial ending in 48 hours
- User inviting a teammate (team upgrade trigger)

5. AI AGENT ORCHESTRATION RULES
Write the conditional logic for an autonomous AI agent to enroll, route, and switch users between tracks in real-time, including suppression rules and exit conditions.

Output everything as a structured marketing automation blueprint ready to load into HubSpot, Customer.io, or Intercom Series.

## Advanced Customizable Version

ROLE: You are an elite PLG growth engineer, behavioral email architect, and AI automation specialist. You have driven 2–4x trial-to-paid conversion rate improvements for B2B SaaS companies at Series A through Series D. You combine BJ Fogg's Behavior Model (B = MAP: Motivation × Ability × Prompt), Cialdini's influence principles, and Jobs-to-be-Done theory to engineer email sequences that feel hand-crafted at the scale of 50,000 monthly trial users.

Your output will be directly loaded into a marketing automation platform and executed by an AI agent with no human review. Every rule, every trigger, every email must be precise, self-contained, and production-ready.

═══════════════════════════════════════════
PRODUCT INTELLIGENCE INPUT
═══════════════════════════════════════════

Company: [Company Name]
Product: [2–3 sentence description — what it does, who it's for, the core value delivered]
Trial Structure: [Choose one]
  → Time-limited: [X] days, full feature access
  → Feature-limited: Free tier includes [list], paid tier unlocks [list]
  → Usage-limited: Free tier allows [X] actions/month, paid unlocks unlimited
  → Freemium: Permanent free plan with [describe ceiling], paid from $[X]/month

AHA Moment (Primary Activation Milestone): [The SINGLE product action most correlated with paid conversion — if you don't know, state your hypothesis and I will help you define it]

Secondary Engagement Signals: [2–4 additional product actions that indicate growing value realization — e.g., "ran a second report," "connected two data sources," "exported results"]

Primary ICP:
  → Job Title: [e.g., Director of Marketing Operations]
  → Company Size: [e.g., 50–500 employees]
  → Industry: [e.g., B2B SaaS]
  → Core Pain: [e.g., "can't segment customers without engineering support"]

Secondary Buyer Personas: [List titles of others who influence or block the purchase decision — e.g., VP Engineering for security review, CFO for spend approval]

Conversion Baseline:
  → Current trial-to-paid rate: [X%] (Industry avg: 2–5%; PLG-native leaders: 8–15%)
  → Average days from signup to first payment: [X days]
  → % of trials that never log in after signup: [X%]

Top Conversion Blockers (from win/loss interviews or churned-trial surveys):
  1. [e.g., "Too busy to complete setup within trial window"]
  2. [e.g., "Needed IT to connect data sources — perceived as a blocker"]
  3. [e.g., "Couldn't prove ROI to their manager without showing real data"]
  4. [Optional]
  5. [Optional]

Upgrade Decision Path:
  → [Self-serve: credit card on file, one-click upgrade] OR
  → [Sales-assisted: SDR notified at conversion gate trigger, calls within 4 hours] OR
  → [Hybrid: Self-serve for teams under [X] seats; SDR-assisted above that]

Key Integrations Users Connect During Trial: [List top 3 — e.g., Salesforce, HubSpot, Slack. Integration connection is often a strong AHA signal.]

Current State of Nurture: [Describe what emails exist today — or "nothing" if starting from zero]

═══════════════════════════════════════════
BEHAVIORAL PSYCHOLOGY FRAMEWORK
═══════════════════════════════════════════

Apply these principles in every email, tailored to where the user is in the trial journey:

BJ FOGG BEHAVIOR MODEL (B = MAP):
  Motivation levers to pull:
    → Pleasure/hope: Show them what's possible when they fully activate
    → Social proof: Show what teams like theirs have achieved
    → FOMO: What they're missing by staying on the free tier
  
  Ability levers to pull:
    → Simplicity: Reduce each email to ONE next action, not five
    → Guided paths: Deep-link directly to the feature or action they need
    → Remove perceived technical blockers: "You don't need IT to connect [Integration]"
  
  Prompt timing:
    → Trigger emails within minutes of positive behavioral signals (reinforcement)
    → Trigger rescue emails after 72 hours of inactivity (before the habit dies)
    → Trigger urgency emails 48h and 24h before trial expiration (not 7 days out — too early to act)

CIALDINI INFLUENCE PRINCIPLES:
  Social Proof: "Teams like yours at [Company Type] typically see [Outcome] within [X] days of activating"
  Reciprocity: Deliver genuine, usable value in every email (tip, shortcut, template, benchmark data)
  Authority: Reference specific customer results with real numbers; use your CS team as the sender
  Scarcity: Trial expiration window; seat limits; price lock before upcoming pricing change
  Commitment & Consistency: Reference what they've already done in the product ("Since you connected Salesforce last Tuesday...")
  Unity: "Thousands of [job title]s at companies like yours use [Product] for exactly this"

JOBS-TO-BE-DONE FRAMING:
  Address the progress users are trying to make, not the features of your product.
  Wrong: "Try our Advanced Segmentation feature"
  Right: "Build the customer segment your campaign has been waiting for — in 4 minutes, no code"

═══════════════════════════════════════════
DELIVERABLE 1: BEHAVIORAL TRIGGER INTELLIGENCE MAP
═══════════════════════════════════════════

Create a complete trigger taxonomy across three categories:

ACTIVATION TRIGGERS (positive signals → increase conversion probability):

| Trigger | Signal Type | Priority | Email Response | Send Timing |
|---|---|---|---|---|
| [AHA Moment achieved] | Primary activation | Critical | Track A Email 1 | Within 15 minutes |
| [3rd login within 48h of signup] | High engagement | High | Power tip email | +2 hours after trigger |
| [Integration connected] | Value realization | High | Integration depth email | Same day |
| [Teammate invited] | Expansion signal | Critical | Team upgrade gate email | Within 30 minutes |
| [Second AHA-adjacent action completed] | Deepening | High | Power user tip | +24 hours |

RISK SIGNALS (negative signals → predict churn):

| Trigger | Signal Type | Priority | Email Response | Send Timing |
|---|---|---|---|---|
| No product login within 72h of signup | Ghost risk | Critical | Track C Email 1 | Hour 72 post-signup |
| Login but no meaningful action within 96h | Friction | High | "Let me help" email | Hour 96 |
| Stopped using after reaching 40% activation | Stall | High | Stall reactivation email | 48h after last session |
| Trial Day 9 — still in Track B | Conversion risk | High | Sales hand-off trigger if sales-assisted model | Day 9 |

CONVERSION WINDOW TRIGGERS:

| Trigger | Response | Timing |
|---|---|---|
| Trial Day -2 (48h before expiration) | Urgency email sequence begins | Day [X-2] |
| Trial Day -1 (24h before expiration) | Final decision email | Day [X-1] |
| Trial Day 0 (expiration) | Expiration + save relationship email | Day X |
| Usage limit hit | Immediate upgrade gate email | Within 5 minutes of trigger |
| Paywall feature clicked | In-context upgrade email | Within 15 minutes |

═══════════════════════════════════════════
DELIVERABLE 2: THREE-TRACK EMAIL SEQUENCE ARCHITECTURE
═══════════════════════════════════════════

Write every email for every track. For each email provide:
  TRIGGER: [Exact enrollment condition or day/timing rule]
  SUPPRESSION: [Who must NOT receive this email]
  FROM: [Specific human name and title — not "The Team"]
  SUBJECT: Primary subject line
  A/B VARIANT: Alternative subject line to test simultaneously
  PREVIEW TEXT: [50–70 characters]
  BODY: [Full email — conversational tone, direct, no jargon. Under 200 words for early emails; up to 350 words for high-stakes conversion emails]
  CTA: [Exact button/link text] → [Destination URL or page type]
  SUCCESS SIGNAL: [What "worked" looks like — open, click, or downstream product action]

---

TRACK A — CHAMPION TRACK
Enrollment: User achieves AHA Moment
Goal: Convert to paid before trial ends; minimize time-to-payment; surface team/enterprise value

Email A-1 | Timing: Within 15 minutes of AHA Moment
  TRIGGER: [AHA Moment event fires in product database]
  SUPPRESSION: Already paid; trial previously expired
  Subject: [Write this — reference their specific achievement, e.g., "You just built what most teams struggle with for months"]
  [Full email reinforcing their win, one next power move, zero upgrade pressure]

Email A-2 | Timing: Day 3
  Subject: [Social proof email — "Here's what happens next for teams like yours"]
  [Customer story from similar company size/industry with specific metric result]

Email A-3 | Timing: Day 5
  Subject: [Power user tip that creates product dependency]
  [Teach them an advanced workflow that requires the paid feature — not manipulative, genuinely useful]

Email A-4 | Timing: Day 7 (mid-trial)
  Subject: ["Halfway through your trial — [First Name], you're further ahead than you think"]
  [Recap of value realized so far + light upgrade value prop + team expansion angle if solo user]

Email A-5 | Timing: Day 9
  Subject: [Integration or collaboration email — expand stickiness]
  [If they haven't invited a teammate: "Your whole team could be running [workflow] by Friday"]
  [If they have integrated: "Unlock the full [integration] sync — here's what the paid tier adds"]

Email A-6 | Timing: Day 11
  Subject: [Case study with specific ROI numbers from similar company]
  [Hard-hitting proof point — "$47K saved in first 90 days" not "companies save money"]

Email A-7 | Timing: Day [X-2] — CONVERSION EMAIL
  Subject: "Your trial ends in 48 hours, [First Name]"
  A/B: "48 hours left — what happens to your [data/segments/reports] after [Date]?"
  [Urgency + loss aversion + clear upgrade CTA + address top objection inline]
  [If sales-assisted: include "Schedule a 15-minute call" CTA alongside self-serve upgrade]

Email A-8 | Timing: Day [X-1]
  Subject: "Last chance — your trial ends tomorrow"
  A/B: "[First Name], one decision before [Day/Date]"
  [Short. Emotional. One CTA. Handle the #1 objection in 3 sentences. Offer money-back guarantee if applicable.]

Email A-9 | Timing: Day X (expiration)
  Subject: "Your [Product] trial has ended — here's what's next"
  [No hard sell. Acknowledge the expiration. Offer: (1) Upgrade to restore access, (2) Book a call, (3) Stay in touch — with cadence set for 7-day and 30-day win-back]

---

TRACK B — ACTIVATION TRACK
Enrollment: Signed up + some product activity + AHA Moment NOT achieved by Day 2
Goal: Drive to AHA Moment, then hand off to Track A sequence

Email B-1 | Timing: Day 1 (24h after signup, only if AHA not achieved)
  TRIGGER: No AHA event in product logs within 24h of signup
  SUPPRESSION: Enrolled in Track A
  Subject: [Specific next step — NOT "Getting Started with [Product]"]
  [One concrete action to take, deep-linked directly to the activation feature, estimated time: "Takes 4 minutes"]

Email B-2 | Timing: Day 3
  Subject: "The thing that trips up [Job Title]s in week 1 of [Product]"
  [Proactively address the #1 activation barrier. If it's technical: "You don't need your dev team for this." If it's time: "Here's the 10-minute version."]

Email B-3 | Timing: Day 5
  Subject: [Peer social proof — same role, similar company]
  [Brief case study of how a [Job Title] at a [Company Size] company got to their first result]

Email B-4 | Timing: Day 7
  Subject: "Can I show you something? [15 min]"
  [Offer: live 1:1 walkthrough (if high-touch model), group demo webinar, or self-guided video tutorial with timestamp to the exact activation moment]

Email B-5 | Timing: Day 9
  Subject: [Ultra-specific, low-friction activation ask]
  ["Just [one action] — that's all that stands between you and [specific outcome]. Here's the direct link: [deep link]"]

Email B-6 | Timing: Day [X-2]
  Subject: "2 days left AND you're closer than you think, [First Name]"
  [Dual urgency: trial ending + activation is close. Offer trial extension of 7 days in exchange for scheduling a call or completing the activation milestone — automated extension if they complete the action within 24h]

Email B-7 | Timing: Day X
  Subject: "Your trial ended — want 7 more days to see it through?"
  [Honest offer: "You were close. If you can [activation action] in the next 7 days, we'll extend your trial automatically." Automate the extension via webhook trigger when they complete the action.]

---

TRACK C — RESCUE TRACK
Enrollment: No meaningful product action within 72 hours of signup
Goal: Understand why they went dark; re-engage or qualify out before trial expires

Email C-1 | Timing: Hour 72 post-signup
  TRIGGER: Zero product logins or logins with no meaningful action within 72h
  FROM: [Founder or Head of CS — not marketing automation name]
  Subject: "Did we lose you, [First Name]?"
  A/B: "Quick question about your [Product] account"
  [3-sentence email. Human. Ask one question: "What got in the way?" Reply to this email link or 1-click survey with 3 options: (a) Too busy, (b) Couldn't figure out how to start, (c) Not the right time. Route response to appropriate follow-up.]

Email C-2 | Timing: Day 6
  Subject: "[Product] in 3 bullets — is this still relevant for you?"
  [Ultra-brief value re-articulation. Three bullets: Pain → Solution → Proof. No fluff. Ask if they want to continue or close the account.]

Email C-3 | Timing: Day [X-4]
  Subject: "Your trial expires in 4 days, [First Name]"
  [Facts only. No hard sell. What happens to their account/data at expiration. Simple upgrade option. No guilt.]

Email C-4 | Timing: Day X
  Subject: "Closing your [Product] account — unless you want to keep it"
  [Breakup email. "We're closing your trial account today. If you'd like to pick up where you left off, you have 7 days to reactivate — after that your data is deleted." This email reliably generates 15–25% re-engagement through loss aversion. Automate account hold for 7 days.]

Post-Trial Email C-5 | Timing: Day X+14 (if no re-engagement)
  Subject: "[First Name], what happened to [specific pain point they signed up to solve]?"
  [Cold win-back email. Reference their original signup intent if known. Low pressure. Two options: reconnect or unsubscribe.]

---

CONVERSION GATE EMAILS (Instant-trigger — fires within minutes of the triggering event)

GATE 1: USAGE LIMIT HIT
  TRIGGER: User hits 80% of free tier usage cap
  Subject: "You're almost at your [Product] limit — here's what that means"
  A/B: "Looks like [Product] is working for you, [First Name]"
  [Celebrate their usage. Clearly show what happens at 100% limit. Show upgrade path with specific seat/usage expansion. If sales-assisted: auto-notify SDR AND send this email simultaneously.]

  TRIGGER #2: User hits 100% of free tier
  Subject: "You've hit your [Product] limit — keep going with [Plan Name]"
  [Immediate upgrade gate. Remove friction: pre-fill their billing info if on file, show one-click upgrade. Show what they've built that they'd lose access to.]

GATE 2: TRIAL EXPIRATION WINDOW
  TRIGGER: 48h before trial end (if no upgrade yet)
  Subject: "Your trial ends [Day/Date], [First Name] — what you need to know"
  [3 things: (1) What expires, (2) What you've built that will be saved vs. lost, (3) Upgrade now or request extension. Include a specific customer proof point for the upgrade decision.]

  TRIGGER: 24h before trial end (only if Gate 2 not clicked)
  Subject: "Tomorrow: your [Product] trial ends"
  [Shortest conversion email in the sequence. One paragraph. One CTA. One objection addressed.]

GATE 3: TEAMMATE INVITED
  TRIGGER: User sends invitation to a colleague
  Subject: "[Teammate Name] is waiting to join you on [Product]"
  A/B: "You just made a team decision, [First Name]"
  [Reframe the upgrade as a team decision already made. "You invited [Name] — upgrading gives them full access from day one." Show per-seat pricing with the math for their implied team size. If they invited 2+: trigger team/company plan email instead.]

═══════════════════════════════════════════
DELIVERABLE 3: AI AGENT ORCHESTRATION LOGIC
═══════════════════════════════════════════

Write the complete conditional logic for autonomous agent execution:

ENROLLMENT RULES:
  IF [trial_signup_event] fires:
    → Enroll in Track C immediately
    → Set trial_end_date = today + [X] days in CRM
    → Start 72-hour timer for Track C Email C-1

  IF [AHA_moment_event] fires within 24h of signup:
    → Move to Track A
    → Suppress all Track C emails not yet sent
    → Fire Track A Email A-1 within 15 minutes

  IF [product_login_event] fires AND [AHA_moment] = false AND 48h since signup:
    → Move to Track B
    → Suppress Track C
    → Enroll in Track B from Email B-1 if B-1 has not sent; skip to next appropriate email if it has

TRACK SWITCHING RULES:
  IF Track C user opens C-1 AND visits product within 48h:
    → Move to Track B at Email B-1

  IF Track B user achieves AHA Moment:
    → Exit Track B
    → Enroll in Track A at appropriate day position (calculate based on days remaining in trial)
    → If days_remaining < 3: skip to Track A Email A-7 (urgency sequence)

  IF Track A user clicks upgrade CTA:
    → Exit all sequences
    → Trigger customer success welcome sequence
    → Notify CS team in Slack

  IF any user upgrades to paid:
    → Immediately suppress all trial nurture emails
    → Flag account as [converted] in CRM
    → Trigger expansion revenue nurture (separate sequence, separate trigger)

SUPPRESSION RULES:
  → Do NOT send if [contact.lifecycle_stage] = Customer
  → Do NOT send if [contact.trial_status] = Upgraded in last 24 hours
  → Do NOT send urgency emails (A-7, A-8) if user has a sales call scheduled within 48h
  → Do NOT send Track C emails if user submitted a support ticket in last 48h (they're engaged)
  → Do NOT send Email A-9 (expiration) if user is in active deal in CRM
  → Maximum 1 email per day per contact (suppression gate on all tracks)
  → Suppress all sequences if contact has unsubscribed from any email in the last 90 days

PERSONALIZATION VARIABLES (inject into all emails):
  [first_name] — First name
  [company_name] — Company from enrichment data
  [job_title] — From signup form or enrichment
  [days_remaining] — Calculated from trial_end_date
  [last_product_action] — Most recent meaningful event from product database
  [features_used_count] — Total distinct features accessed
  [aha_achieved] — Boolean
  [team_size_estimate] — From enrichment data (ZoomInfo, Clearbit) for team upgrade triggers
  [integration_connected] — Name of last integration connected (if any)

AGENT WEEKLY AUDIT TASKS:
  → Identify users in Track C for more than 7 days with no email engagement → Flag for manual review or disqualification
  → Identify users in Track B on Day 9+ → Trigger sales hand-off notification if sales-assisted model
  → Calculate weekly track distribution (% in each track) — alert if Track C > 50% of new trials (acquisition quality problem, not nurture problem)
  → A/B test winner detection: after 200 sends per variant, calculate winner on click-to-open rate; auto-adopt winner for all new enrollments

═══════════════════════════════════════════
DELIVERABLE 4: MEASUREMENT FRAMEWORK
═══════════════════════════════════════════

Define autonomous KPI reporting the agent generates every Monday morning:

EMAIL PERFORMANCE TARGETS (by track):
  Track A: Open rate ≥ 45% | CTOR ≥ 22% | Trial-to-paid conversion ≥ 15%
  Track B: Open rate ≥ 35% | CTOR ≥ 15% | AHA achievement rate ≥ 30%
  Track C: Open rate ≥ 25% | CTOR ≥ 10% | Re-engagement rate ≥ 15%

CONVERSION HEALTH METRICS (weekly):
  → Overall trial-to-paid rate (rolling 4-week average — target: improve 0.5% per month)
  → Average days from signup to payment (target: below [X] days for your product)
  → AHA Moment achievement rate (% of all trial users who ever reach activation — single most important lever)
  → Track distribution (healthy state: 30%+ in Track A; investigate if <15% in Track A)

OPTIMIZATION TRIGGERS:
  → If any email's CTOR drops > 20% below target for 2 consecutive weeks → Auto-flag for A/B test
  → If Track A conversion rate drops below 10% for 3 consecutive weeks → Escalate to marketing team
  → If AHA Moment achievement rate drops below 20% → Trigger product team notification (onboarding friction alert)

## Example Input/Output

**Input Example:**
Product: Vessel — a no-code revenue analytics platform that connects a B2B SaaS company's CRM, billing system, and product database into a single revenue intelligence layer, letting RevOps and Finance teams build ARR waterfall charts, cohort analyses, and churn forecasts without SQL.
Trial length: 14 days, full feature access
Trial type: Time-limited
AHA Moment: First ARR waterfall chart built with live CRM data connected
Primary buyer: VP of Revenue Operations or Director of Finance at B2B SaaS, 100–800 employees
Pricing: $1,500/month, annual contract required
Top 3 conversion blockers:
  1. Takes 2–3 hours to connect all data sources; busy RevOps leaders don't prioritize it
  2. CFO approval required for $18K annual contract — champion can't self-approve
  3. Current free alternative (manual Google Sheets model) feels "good enough" until they see the live product

**Output Example — Track A Email A-1:**

TRIGGER: AHA Moment event fires (ARR waterfall chart created with live Salesforce data)
TIMING: Within 12 minutes of trigger
SUPPRESSION: Contact.lifecycle_stage = Customer
FROM: Marcus Rivera, Head of Customer Success at Vessel
SUBJECT: You just built what took your finance team 3 days in a spreadsheet ✓
A/B VARIANT: [First Name], your first ARR waterfall is live — here's what's next
PREVIEW TEXT: Most RevOps leads spend days on what you just did.

Hi [First Name],

You just connected Salesforce and built your first ARR waterfall chart in Vessel.

That chart — the one that used to take your team a weekend of VLOOKUP hell — just updated in real time.

Here's what that unlocks for you this week:

→ Your CFO can see the ARR bridge before your next board prep call
→ Your CS team can pull churn forecasts without emailing RevOps
→ Your next SKO slides will have live numbers, not last quarter's exports

What 37 other RevOps leaders at Series B–D SaaS companies do after building their first waterfall:
They immediately connect their billing system (Stripe, Chargebee, or Zuora). That's where cohort-level net revenue retention analysis comes alive.

It takes 6 minutes. Here's the direct setup link: [Connect Billing System →]

Talk soon,
Marcus Rivera
Head of Customer Success, Vessel

**Behavioral Trigger Map (excerpt):**

| Trigger | Priority | Email Fired | Timing |
|---|---|---|---|
| ARR waterfall built + Salesforce connected | Critical (AHA) | Track A Email A-1 | Within 12 min |
| Billing system connected | High | Integration depth email | Same day |
| 4th login within 48h | High | Power user tip: cohort analysis | +2h after 4th login |
| Board deck template accessed | High | "Your CFO is going to love this" email | +1h |
| No Salesforce connection within 72h of signup | Critical risk | Track C Email C-1 | Hour 72 |
| Team member invited | Critical | Team upgrade gate email | Within 20 min |
| Annual ARR limit view (>$10M ARR tier) | High | Enterprise plan prompt | Same session |
| Trial Day 12 — no upgrade, active user | High | Urgency email A-7 + SDR hand-off | Day 12 |

## Success Metrics

**Email Performance Benchmarks to Aim For:**
- Track A average open rate: ≥ 45% (engaged users who found value are highly receptive)
- Track A trial-to-paid conversion rate: 15–25% (vs. 2–5% industry average for unoptimized trials)
- Track B AHA Moment achievement: ≥ 30% of Track B users should reach activation within trial window
- Track B conversion rate: 5–10% (lower than A but dramatically higher than no nurture)
- Track C re-engagement rate: ≥ 15% (rescue 1 in 7 ghost trials back to active)
- AHA Moment achievement rate (all trials): Target ≥ 50% — this single metric more than any other determines your trial-to-paid ceiling

**Business Impact Indicators:**
- Trial-to-paid conversion rate: Track rolling 4-week average; look for ≥ 0.5% monthly improvement after the system goes live
- Average days to conversion: Should trend downward as urgency emails and behavioral triggers shorten the decision window
- Revenue attributable to sequence: Tag all CTA links with UTM parameters; measure influenced revenue vs. organic upgrades
- Reduction in ghost trials (signed up, never returned): Target this below 30% of all trial starts

**System Health Checks:**
- Track distribution: If more than 60% of trials land in Track C, the problem is acquisition targeting or signup-to-first-use friction — fix those before optimizing email
- AHA Moment achievement rate: If below 25%, the problem is in-product onboarding, not email nurture — the two systems must work together

## Related Prompts
- [Lead Nurturing Program Architecture & Behavioral Segment Pipeline Acceleration](./AI-Powered-B2B-SaaS-Lead-Nurturing-Program-Architecture-&-Behavioral-Segment-Pipeline-Acceleration-Revenue-Intelligence-Engine.md)
- [Free Trial Activation Funnel CRO & Time-to-Value Conversion](../Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Free-Trial-Activation-Funnel-CRO-&-Time-to-Value-Conversion-Intelligence-Engine.md)
- [New User Welcome & 30-Day Activation Email Sequence](../../03_Content-&-Creative/Email-Marketing-Content/AI-Powered-B2B-SaaS-New-User-Welcome-&-30-Day-Activation-Email-Sequence-Intelligence-Engine.md)
- [Inbound Email Marketing Architecture & Behavioral Lead Lifecycle](../Email-Marketing/AI-Powered-B2B-SaaS-Inbound-Email-Marketing-Architecture-&-Behavioral-Lead-Lifecycle-Revenue-Intelligence-Engine.md)

## Integration Tips

**Customer.io (Best-in-class for PLG nurture):**
- Use "Campaigns" with event-triggered branching — each track maps directly to a Campaign in Customer.io
- Connect product events via Segment.io or direct API (`identify`, `track` calls for each behavioral trigger)
- Use "Liquid" templating for `last_product_action` and `days_remaining` personalization variables
- A/B testing is native in Customer.io Campaigns — enable on every subject line in the sequence

**HubSpot:**
- Build three separate Workflows (one per track) with enrollment triggers matching the Orchestration Logic
- Create custom contact properties: `trial_track`, `aha_moment_achieved` (boolean), `trial_end_date`, `last_product_action`, `days_remaining` (calculated property)
- Use HubSpot's `enrollment suppression lists` for all suppression rules defined above
- For sales-assisted models: use the "Create Task" action in Track B Day 9 workflow to auto-assign an SDR task

**Intercom:**
- Intercom Series maps directly to this architecture — create three Series, one per track
- Use Custom Data Attributes to store `aha_achieved`, `trial_end_date`, `track`
- Route Series enrollment via Segment.io events or Intercom's REST API
- The Conversion Gate Emails work best as Intercom "Messages" triggered via event — not email campaigns

**Segment / RudderStack:**
- Create a Segment "Journey" with branching logic that mirrors the Orchestration Rules above
- Use Computed Traits to calculate: `engagement_score`, `days_since_last_login`, `activation_progress_pct`
- Route users between tracks by updating `context.traits.trial_track` and firing a downstream action to your email platform

**Zapier / Make (No-code setup):**
- Webhook from product → Zapier → Update CRM contact property → Enroll in Workflow
- Build one Zap per conversion gate trigger (usage limit, teammate invite, trial end)
- Use Zapier's Filter step to implement suppression rules before updating the email platform

**AI Agent Implementation:**
- Feed your product event stream to an AI agent via webhook (Zapier Webhook or direct API)
- Agent evaluates each event against the Orchestration Logic trigger map in Deliverable 3
- Agent calls CRM API to update contact properties and enroll/move contacts between tracks
- Schedule a daily agent audit task: identify off-track users, flag conversion risk accounts, run the weekly measurement report

## Troubleshooting

**Problem: Track A conversion rate is below 10% despite users hitting the AHA Moment**
Solution: Your AHA Moment definition is likely off. The true AHA Moment is the action MOST CORRELATED with conversion in your data, not just the first impressive thing users do. Run a cohort analysis: compare product actions taken by users who converted vs. those who didn't. The action with the highest predictive power is your real AHA Moment. Also audit email deliverability — test with Mail-Tester.com; aim for a score above 9/10. Finally, review Track A email copy for over-selling pressure; users who found genuine value don't need to be pushed — they need to be reminded and made frictionless to upgrade.

**Problem: 60%+ of trial users land in Track C (no engagement after signup)**
Solution: This is an acquisition quality and activation friction problem — fixing the nurture emails won't solve it. Audit these areas before anything else: (1) Are your top-of-funnel paid ads and organic content attracting genuine ICPs or curiosity clicks? (2) Does your signup page qualify intent? Adding one friction point at signup (required credit card, company size field, or use-case question) will reduce ghost trial volume dramatically. (3) Is there a "time to first value" problem in the product itself? If users can't reach a meaningful result in their first 10 minutes, no email sequence will rescue them — work with product on a shorter activation path first.

**Problem: Track B users achieve the AHA Moment on Day 11–12 and still don't convert**
Solution: They ran out of time to see full value before urgency pressure started. Three options: (1) Offer an automated 7-day trial extension for Track B users who achieve AHA Moment in the final 3 days — trigger the extension automatically when the activation event fires after Day 11, no human required. (2) Add a money-back guarantee to remove conversion risk: "Start your subscription today — if you don't [get result X] in 30 days, we refund you, no questions." (3) For high-ACV products ($1K+/month), trigger an immediate SDR notification when a Track B user activates late — a timely human outreach call converts 3–5x better than email alone at this stage.

## Version History
- v1.0: Initial creation (auto-generated)
