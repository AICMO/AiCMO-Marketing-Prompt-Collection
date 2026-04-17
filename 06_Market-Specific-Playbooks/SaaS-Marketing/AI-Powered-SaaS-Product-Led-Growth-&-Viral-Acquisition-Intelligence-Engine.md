# AI-Powered SaaS Product-Led Growth & Viral Acquisition Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** saas, plg, product-led-growth, viral-loops, free-to-paid, pql, activation, growth-engineering

## Overview
Design, score, and continuously optimize a full Product-Led Growth engine — from viral acquisition loops and activation milestones through PQL-to-revenue handoff — for any SaaS product. Use this when you need an autonomous AI agent that turns product usage signals into pipeline, not when you already have a managed-onboarding motion.

## Quick Copy-Paste Version

You are a senior PLG growth strategist. Build a complete Product-Led Growth engine for: [YOUR SAAS PRODUCT]

Context:
- Product: [What it does in one sentence]
- Free motion: [Free trial / Freemium / Open-source / Reverse trial]
- ICP: [Company size, role, industry]
- Current free-to-paid conversion: [X%]
- Biggest activation drop-off: [Where users ghost]
- Top 3 features power users love: [List them]

Deliver:
1. Viral loop design — the exact mechanic that makes users invite others as a byproduct of getting value (not a referral program bolt-on)
2. Activation milestone map — the 3–5 "aha moments" that predict 90-day retention; include the in-product trigger and the signal to detect each one
3. PQL scoring model — a weighted formula using behavioral signals (feature depth, frequency, team spread, data commitment) that predicts conversion intent
4. Free-to-paid conversion playbook — personalized upgrade paths by PQL tier, with copy angles, timing, and friction-removal tactics
5. PLG + sales-assist overlay — rules for when to route a PQL to an SDR vs. keep it self-serve, and the exact outreach sequence for sales-assist accounts
6. Growth experiment backlog — 10 prioritized A/B tests with hypothesis, metric, and minimum detectable effect for each

Output each section as an actionable spec an engineer and marketer can implement this week. No vague strategies.

## Advanced Customizable Version

You are a world-class PLG growth architect with deep expertise in self-serve SaaS, viral coefficient engineering, and product-qualified pipeline. You have designed PLG systems for Slack, Figma, Notion, Calendly, and Loom archetypes. Your output is always engineer-ready and metric-grounded.

Build a complete PLG & Viral Acquisition Intelligence Engine for the following product:

---
PRODUCT CONTEXT:
- Product name and category: [e.g., "Kova — async video messaging for remote engineering teams"]
- Core value proposition (Jobs-to-be-Done): [e.g., "Replace synchronous standup meetings with rich async updates that don't get ignored"]
- Free motion type: [Freemium / 14-day full-feature trial / Reverse trial (full features → limited free) / Open-source core]
- Pricing architecture: [e.g., Free: 5 users, unlimited videos; Pro: $12/user/month; Business: $28/user/month with SSO + analytics]
- Current funnel data:
  - Free signups/month: [X]
  - Activation rate (defined as: [your activation event]): [X%]
  - Free-to-paid conversion (90-day): [X%]
  - Viral coefficient (K): [X or "unknown"]
  - Average time-to-conversion: [X days]
- Known activation blockers: [e.g., "Users who don't invite a teammate within 48 hours almost never convert"]
- Top 3 power-user behaviors: [e.g., "Daily video creation, 3+ teammates active, Slack integration connected"]
---

DELIVERABLE 1 — VIRAL LOOP ARCHITECTURE

Design 2–3 viral loops native to product usage (not bolted-on referral programs). For each loop:

a) Loop type: [Collaborative / Viral content / Network effect / Marketplace / Workflow dependency]
b) Trigger: The in-product action that initiates the loop
c) Viral surface: Where a non-user is exposed (e.g., shared artifact, notification email, embedded widget)
d) Conversion hook: What compels the non-user to sign up
e) Viral coefficient calculation:
   - Invites sent per activated user per week (i)
   - Conversion rate of invites to signups (c)
   - K = i × c
   - Target K to achieve (benchmark: K > 0.5 for meaningful viral contribution; K > 1.0 for explosive growth)
f) Implementation spec: Exact product changes needed (feature flags, share flows, email templates)
g) Instrumentation: Events to track in Amplitude/Mixpanel to measure loop health

DELIVERABLE 2 — ACTIVATION MILESTONE MAP

Identify 3–5 sequential "aha moments" that constitute true activation. For each milestone:

a) Milestone name: [e.g., "First Async Standup Completed"]
b) In-product action: The exact event that fires
c) Predictive signal: Data showing this event correlates with 90-day retention (or construct a hypothesis if data unavailable)
d) Time-to-milestone target: [e.g., "within 48 hours of signup"]
e) Intervention if missed: Automated nudge (in-app tooltip, email, Slack notification) with exact copy
f) Drop-off diagnosis prompt: Questions the AI agent asks to diagnose why users miss this milestone in aggregate

Framework: Apply Jobs-to-be-Done lens — each milestone should correspond to a progress the user is trying to make, not a feature the product wants adopted.

DELIVERABLE 3 — PQL SCORING MODEL

Build a Product-Qualified Lead scoring model. Output a weighted formula:

PQL Score = (Feature Depth × W1) + (Usage Frequency × W2) + (Team Spread × W3) + (Data Commitment × W4) + (Integration Depth × W5) + (Support Signals × W6)

For each factor:
- Definition: How it's measured
- Data source: Which product event or property captures it
- Weight rationale: Why this factor predicts conversion intent
- Normalization: How to scale it 0–100

Then define three PQL tiers:
- Hot PQL (score 80–100): Self-serve conversion likely; trigger automated upgrade campaign
- Warm PQL (score 50–79): Sales-assist eligible; route to SDR with usage context
- Cold PQL (score 0–49): Activation-focused nurture; do not attempt sales outreach

Include the SQL query or Segment trait definition an ops team can implement immediately.

DELIVERABLE 4 — FREE-TO-PAID CONVERSION PLAYBOOK

Design personalized upgrade paths for each PQL tier. For each path:

Hot PQL — Self-Serve Conversion Flow:
- Trigger: PQL score crosses 80 threshold
- In-app paywall moment: Which feature gate or usage limit creates natural conversion urgency without feeling punitive
- Upgrade email sequence (3 emails max):
  * Email 1: Sent at trigger. Subject line formula, body structure, primary CTA
  * Email 2: Sent at +3 days if no upgrade. Angle: social proof + ROI quantification
  * Email 3: Sent at +7 days. Angle: urgency + risk reversal (money-back guarantee)
- Pricing page optimization: 3 specific copy/UX changes to reduce checkout abandonment
- Objection-handling copy: Pre-built responses to "too expensive," "need to check with my boss," "not sure we'll use it enough"

Warm PQL — Sales-Assist Sequence:
- Routing logic: PQL score 50–79 + [additional qualifiers: e.g., company size > 50, specific feature usage]
- SDR outreach sequence:
  * Touch 1 (Day 1): Personalized email referencing specific product usage. Template with merge fields.
  * Touch 2 (Day 3): LinkedIn connection + message referencing shared use case
  * Touch 3 (Day 6): Value-add email (relevant case study or ROI benchmark from their industry)
  * Touch 4 (Day 10): Breakup email with soft CTA to self-serve
- SDR briefing card: The 5 data points from the PQL score an SDR must review before reaching out
- Discovery call agenda: 3 questions that reveal expansion potential based on current product usage

Cold PQL — Activation Nurture:
- Goal: Move to Warm PQL within 30 days, not to sell
- Sequence focus: Milestone-based (trigger emails when activation milestones are missed, not on calendar)
- Content: Education, not promotion — how-to guides, use case templates, peer success stories

DELIVERABLE 5 — PLG + SALES-ASSIST ORCHESTRATION

Design the rules engine that governs when product usage routes to self-serve vs. sales-assist:

a) Firmographic override rules: Company size, industry, or geography that auto-routes to sales regardless of PQL score
b) Behavioral override rules: Specific actions (e.g., visiting enterprise pricing page 3+ times) that trigger SDR alert
c) Sales-assist SLA: Maximum hours between PQL qualification and first SDR touch
d) CRM integration spec: HubSpot or Salesforce property mapping for PQL score, tier, and top behavioral signals
e) Hand-back rules: When a sales-assist account stops responding, rules for returning it to self-serve nurture
f) Expansion detection: Product signals that indicate a self-serve account is ready for an account expansion conversation (e.g., 80% seat utilization, power user in a new department)

DELIVERABLE 6 — GROWTH EXPERIMENT BACKLOG

Generate 10 prioritized growth experiments. For each experiment:

| # | Hypothesis | Metric | Baseline | Target | MDE | Test Duration | Effort | Priority |
|---|-----------|--------|----------|--------|-----|---------------|--------|----------|
| 1 | If we [change X], then [metric Y] will increase by [Z%] because [mechanism] | [Primary metric] | [Current value] | [Target value] | [Min detectable effect] | [Days] | [S/M/L] | [H/M/L] |

Rank by: (Impact × Confidence) / Effort using the ICE framework.
Include at least:
- 3 experiments targeting activation rate improvement
- 3 experiments targeting viral coefficient increase
- 2 experiments targeting free-to-paid conversion
- 2 experiments targeting expansion revenue from self-serve accounts

DELIVERABLE 7 — PLG HEALTH DASHBOARD SPEC

Define the 12 metrics that constitute a complete PLG health dashboard:

For each metric:
- Name and definition
- Data source
- Calculation formula
- Weekly target / alert threshold
- Leading or lagging indicator
- Which team owns it (Growth, Product, Sales, CS)

Organize into four quadrants: Acquisition, Activation, Revenue, Retention.

## Example Input/Output

**Input:**
- Product: Kova — async video messaging replacing synchronous standups for distributed engineering teams
- Free motion: Freemium (5 users, unlimited 5-min videos)
- ICP: Engineering managers at 20–500 person tech companies
- Current free-to-paid conversion: 6.2% at 90 days
- Biggest activation drop-off: 71% of signups never invite a teammate
- Power-user behaviors: Daily video creation, 3+ teammates active, Slack integration connected

**Output (Excerpt):**

### Viral Loop #1 — Async Update Loop (Collaborative Virality)

**Loop type:** Collaborative — value requires recipient participation

**Trigger:** User records and sends a video update to a non-Kova-user colleague

**Viral surface:** Recipient receives a branded email preview with thumbnail and waveform animation. Subject line: "[Sender Name] sent you an async update via Kova (30 sec)"

**Conversion hook:** Recipient clicks to watch → lands on frictionless watch page (no signup required for first view) → prompted to "Reply with a video" → account created in reply flow

**K-factor estimate:**
i (invites per activated user per week) = 2.3 (based on avg team size 6, % who send cross-org = 38%)
c (invite-to-signup rate) = 0.19 (benchmark: async tools see 15–22%)
K = 2.3 × 0.19 = 0.44
Target: Increase c to 0.26 by removing email gate on first watch → K = 0.60

**Implementation spec:**
1. Watch page: Remove "sign up to watch" gate for first 3 views per recipient
2. Reply CTA: "Reply with a video" button creates account with Google SSO in <10 seconds
3. Email template: Include video thumbnail (auto-generated at 3s mark), sender name, duration badge
4. Tracking: fire `viral_view_occurred`, `viral_reply_initiated`, `viral_signup_completed` events

---

### PQL Scoring Model

-- Kova PQL Score (0-100)
SELECT
  user_id,
  ROUND(
    (LEAST(video_count_30d / 20.0, 1.0) * 30) +        -- Feature depth (W1=30)
    (LEAST(active_days_30d / 20.0, 1.0) * 25) +         -- Usage frequency (W2=25)
    (LEAST(teammates_active / 4.0, 1.0) * 25) +         -- Team spread (W3=25)
    (CASE WHEN slack_connected THEN 1.0 ELSE 0 END * 15) -- Integration depth (W4=15)
  , 1) AS pql_score,
  CASE
    WHEN pql_score >= 80 THEN 'hot'
    WHEN pql_score >= 50 THEN 'warm'
    ELSE 'cold'
  END AS pql_tier
FROM user_product_metrics
WHERE account_type = 'free'
  AND signup_date >= CURRENT_DATE - 90;

**Tier thresholds (validated against historical conversion data):**
- Hot (80–100): 23.4% convert within 14 days of reaching score — self-serve upgrade flow
- Warm (50–79): 8.1% convert within 30 days; 31% convert when sales-assist touches within 48 hours
- Cold (0–49): 1.2% convert organically — activation nurture only, no sales outreach

---

### Upgrade Email — Hot PQL, Email #1

**Subject:** "Your team is getting async-first — here's what's waiting for you"

**Send trigger:** PQL score crosses 80

**Body:**
Hey [First Name],

[X] videos sent, [Y] teammates active, [Z] hours of meetings your team skipped.

That's what Kova's done for your team in the last 30 days on the free plan.

The teams that stick with Kova long-term do one thing differently: they upgrade before they hit the 5-user wall, not after. (Scrambling to get approvals mid-sprint is not fun.)

Pro gives you unlimited users, searchable video history, and the analytics that tell you which async updates actually got watched.

[Upgrade now — $12/user/month, cancel anytime →]

No credit card traps. No "call sales." Just click.

— The Kova team

---

### Growth Experiment #1 — Remove Watch Gate

| Field | Value |
|-------|-------|
| Hypothesis | If we remove the sign-up gate on the video watch page for first-time recipients, viral signup rate will increase by 35% because friction is the primary drop-off point |
| Primary metric | `viral_signup_completed` / `viral_view_occurred` |
| Baseline | 8.3% |
| Target | 11.2% |
| MDE | 2.5 percentage points |
| Duration | 21 days |
| Effort | S (1 engineer, 1 day) |
| Priority | H — highest leverage, lowest effort in backlog |

## Success Metrics

- **Viral coefficient (K):** Target >0.5 within 60 days of loop implementation (measure weekly via `viral_signup_completed` / `activated_users`)
- **Activation rate:** 40%+ of signups hit Milestone #1 within 48 hours (up from baseline)
- **PQL accuracy:** Calibrate model until Hot PQL tier converts at >20% within 30 days
- **Free-to-paid conversion:** Target >12% at 90 days (2x baseline); measure by cohort
- **Sales-assist lift:** Warm PQL + SDR outreach should convert at 2.5–3x the unassisted rate
- **Time-to-conversion:** Median days from signup to paid should decrease by 25%

## Related Prompts

- [SaaS Customer Lifecycle Automation](./SaaS-Customer-Lifecycle-Automation.md) — Post-signup retention, expansion, and churn prevention once users convert
- [B2B Founder-Led Sales to Marketing-Led Growth Transition](../../02_Product-Marketing/Go-To-Market-Strategy/AI-Powered-B2B-Founder-Led-Sales-to-Marketing-Led-Growth-Transition-Intelligence-Engine.md) — Transition playbook when PLG replaces founder-led deals
- [Enterprise Sales Enablement Engine](../B2B-Marketing/Enterprise-Sales-Enablement-Engine.md) — When PLG self-serve accounts mature into enterprise sales motions

## Integration Tips

- **Segment + Amplitude/Mixpanel:** Instrument every viral loop event (`viral_view_occurred`, `viral_signup_completed`, `milestone_1_achieved`, `pql_tier_changed`); build PQL score as a computed trait that auto-syncs to CRM
- **HubSpot/Salesforce:** Map PQL score to a custom contact property; create workflow that auto-enrolls Hot PQLs in upgrade sequence and creates SDR tasks for Warm PQLs within SLA
- **Intercom/Customer.io:** Trigger in-product messages and emails on milestone miss events, not on calendar — this requires event-based campaigns, not drip sequences
- **Stripe/Paddle:** Fire `conversion_completed` event on first successful charge and feed it back into Amplitude to close the attribution loop on which viral loop source drove paid conversion
- **Clay:** Enrich Warm PQL accounts with firmographic data (headcount, funding, tech stack) before SDR outreach to personalize the first touch without manual research
- **Zapier/Make:** Pipe Hot PQL alerts to Slack (`#growth-signals` channel) with a one-click "send upgrade email now" button so growth team can intervene manually when warranted

## Troubleshooting

**Problem:** PQL score is high but conversion stays flat — lots of "hot" users who never upgrade.
**Fix:** Your scoring weights are measuring engagement, not conversion intent. Audit which specific behaviors your historical paid users exhibited in the 7 days before converting. Common fix: add "visited pricing page" and "invited 3+ teammates" as high-weight signals; reduce weight on raw video-creation frequency (a proxy for engagement, not purchase readiness).

**Problem:** Viral loop instrumented but K-factor is near zero — recipients view the content but don't create accounts.
**Fix:** The conversion hook on the watch page is failing. Test: (1) remove email gate entirely for first view, (2) make "Reply with video" the only prominent CTA (not "Sign up"), (3) pre-populate the reply's send-to field with the original sender so there's zero setup friction. The most common root cause is asking for commitment before delivering the value — flip the order.

**Problem:** SDRs ignore Warm PQL routing because the leads "don't feel ready."
**Fix:** SDRs are conditioned to want BANT-qualified leads. Retrain them on PQL context: the lead IS ready, they just haven't raised their hand. Give each SDR a 1-page brief explaining what the product signals mean in plain language ("this person sent 18 videos last month and invited 4 teammates — they're a power user who hasn't seen a reason to pay yet"). Add the top 3 product behaviors to the CRM task so it's visible before first dial.

## Version History
- v1.0: Initial creation (auto-generated)
