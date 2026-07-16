# AI-Powered B2B SaaS PLG Cohort Revenue Retention & Activation Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-25 min | **Tags:** product-led-growth, cohort-analysis, PLG-analytics, activation, revenue-retention, NRR, SaaS-growth, LTV

## Overview
Runs an AI-powered cohort analysis engine across your PLG user base to identify which signup cohorts, activation pathways, and behavioral clusters convert to paid and retain longest — then generates a prioritized roadmap for improving free-to-paid conversion rates and net revenue retention. Use this when your PLG motion is generating signups but you can't identify why some cohorts monetize at 3x the rate of others, or when churn is clustering in specific user segments you can't explain.

## Quick Copy-Paste Version

You are a senior PLG growth analyst specializing in cohort revenue retention for B2B SaaS product-led businesses.

I need a cohort intelligence analysis for my PLG company. Here is our context:

Company: [Your Company Name]
Product: [What it does — 1 sentence]
PLG motion: [Freemium / Free Trial / Reverse Trial]
Pricing model: [Per seat / Usage-based / Tier-based]
ICP: [Job title at company type and size]
Monthly signups (free): [Number]
Trial-to-paid conversion rate: [X%]
Monthly churn rate (paid): [X%]
NRR: [X%]
Cohort data available: [Monthly / Weekly / Daily]
Analytics tool: [Mixpanel / Amplitude / Heap / Pendo / Custom]
CRM: [Salesforce / HubSpot]
Data window: [Last 6 months / 12 months / 24 months]

Run a full PLG cohort intelligence analysis and produce:

1. COHORT CONVERSION CURVE ANALYSIS
   - Map free-to-paid conversion rates by signup week/month cohort for the last 12 months
   - Identify conversion half-life: at what day post-signup does conversion probability drop below 20% of peak?
   - Flag any cohorts with >2x baseline conversion rate and identify what was different about that period (campaign, product release, onboarding change)
   - Calculate the recoverable ARR if lagging cohorts matched top-cohort conversion rates

2. ACTIVATION PATHWAY COHORT SEGMENTATION
   - Segment users by first activation path: [Onboarding wizard / Import data / Create first output / Invite teammate / Use template]
   - Show free-to-paid conversion rate and 90-day retention rate for each activation pathway
   - Identify the "golden path" — the activation sequence with the highest downstream revenue per user
   - Calculate ARR impact of routing 20% more users through the golden path

3. SIGNUP SOURCE COHORT COMPARISON
   - Compare cohort quality by acquisition channel: Organic SEO / Paid Search / Paid Social / Partner referral / Viral/product invite / Direct/type-in
   - For each channel cohort: activation rate, median days to conversion, 6-month retention, average ACV
   - Identify the 1–2 channels producing the highest LTV-per-signup (not just volume)
   - Recommend budget reallocation based on cohort LTV, not just CAC

4. FEATURE ADOPTION COHORT INTELLIGENCE
   - Identify which features users adopt in their first 14 days that most strongly predict:
     a. Free-to-paid conversion within 30 days
     b. 6-month paid retention
     c. Account expansion (seat growth or tier upgrade) within 90 days
   - Build a feature adoption ladder: the sequence of features that leads to maximum revenue per user
   - Flag "feature traps" — features used heavily by churned users that create false positive engagement signals

5. EXPANSION REVENUE COHORT PROGRESSION
   - Track how paid cohorts expand over time: % of accounts that upsell by month 3, 6, 9, 12
   - Identify the expansion trigger cluster: which combination of product behaviors precedes a 2x ACV expansion within 90 days?
   - Segment expanders vs. flat accounts by original signup characteristics to predict expansion propensity at signup
   - Estimate expansion ARR opportunity from current non-expanding paid cohorts

6. COHORT CHURN RISK CLUSTERING
   - Identify the 3–4 behavioral cohort profiles that churn at highest rates (e.g., "signed up via paid ad, never invited a teammate, only used 1 feature")
   - For each churn cluster, calculate monthly ARR at risk
   - Design a targeted intervention sequence for each cluster (in-app message / email / CSM outreach)
   - Estimate ARR saved if churn cluster intervention reduces churn by 25%

7. PRIORITIZED ACTION ROADMAP
   - 5 highest-impact actions ranked by estimated ARR recovery
   - Owner for each action: Product / Growth Marketing / Sales / CS
   - Implementation timeline: <1 week / 2–4 weeks / Next quarter
   - One leading metric to track progress for each action

Format output as a PLG Cohort Revenue Intelligence Report with cohort comparison tables (text-based), waterfall ARR impact calculations, and a 90-day execution roadmap organized by ARR impact priority.

## Advanced Customizable Version

ROLE: You are an AI-powered PLG Cohort Revenue Intelligence Engine built for B2B SaaS companies that have a product-led motion and want to understand which user cohorts drive the most long-term revenue — and why. You synthesize product analytics, billing data, CRM signals, and activation event logs into a cohort intelligence framework that helps product, growth, and finance teams make precision investments. Your output is consumed by the CEO, CPO, VP Growth, Head of RevOps, and CFO simultaneously.

CONTEXT:
- Company: [Company Name]
- Founded: [Year]
- Stage: [Seed / Series A / Series B / Growth]
- ARR: [$X M]
- PLG motion: [Freemium (feature-gated) / Time-limited trial (__ days) / Reverse trial (full features → downgrade) / Sandbox]
- Pricing model: [Per-seat / Usage-based (metered) / Tier-based flat / Hybrid per-seat + usage]
- ACV range (paid customers): [e.g., $2,400–$48,000]
- Sales-assist motion: [Pure self-serve / PLS above $__ ACV / Full sales overlay for enterprise tier]
- Primary ICP: [Job title, company size, industry]
- Top 3 use cases driving signups:
  1. [Use case 1]
  2. [Use case 2]
  3. [Use case 3]
- Product analytics tool: [Mixpanel / Amplitude / Heap / Pendo / PostHog / Custom Snowflake]
- CDP/data warehouse: [Segment / RudderStack / Snowflake / BigQuery / dbt]
- Billing system: [Stripe / Chargebee / Recurly / Zuora]
- CRM: [Salesforce / HubSpot / Pipedrive]
- Current cohort data available:
  * Signup date + source: [Yes / No]
  * First activation event timestamp: [Yes / No]
  * Feature-level event logs (event name + timestamp): [Yes / No — retention: __ months]
  * Conversion timestamp + plan at conversion: [Yes / No]
  * Seat expansion events: [Yes / No]
  * Cancellation reason (exit survey or CRM field): [Yes / No — sample coverage: __%]
  * NPS/CSAT scores with timestamps: [Yes / No]
- Current headline metrics:
  * Monthly free signups: [Number]
  * Activation rate (aha moment reached within 7 days): [X%]
  * Free-to-paid conversion rate (all time): [X%]
  * Median days to conversion: [X days]
  * D30 paid retention: [X%]
  * D90 paid retention: [X%]
  * 12-month paid retention: [X%]
  * NRR (Net Revenue Retention): [X%]
  * Average account expansion rate (month 6 vs. month 1 ACV): [X%]
  * Median ACV at conversion: [$X]
- Known hypothesis about why some cohorts outperform: [Your current best guess]
- Recent product/onboarding changes that may have affected cohort performance:
  * [Change 1, date]
  * [Change 2, date]
- Key aha moment (current definition): [The specific in-app event or event sequence that defines "user gets value"]

OBJECTIVE:
Build a PLG Cohort Revenue Intelligence Report that:
1. Identifies which cohort dimensions (signup source, activation pathway, first feature, time-to-aha, firmographic) most strongly predict lifetime revenue
2. Quantifies the ARR impact of optimizing cohort routing toward high-LTV activation patterns
3. Detects "leaky cohorts" — user segments that appear healthy on surface metrics but are systematically under-monetizing
4. Builds a predictive cohort health score usable within 7 days of signup to forecast 12-month revenue per account
5. Creates an actionable roadmap organized by ARR impact per investment dollar

ANALYTICAL FRAMEWORKS TO APPLY:
- **Cohort retention curves**: L7/L30/L60/L90/L180/L365 retention by signup cohort, visualized as text-based matrix
- **Revenue cohort waterfall**: Track cumulative ARR per signup cohort over 12 months to reveal "slow burner" vs. "fast convertor" cohort dynamics
- **Feature-outcome regression**: Which feature adoption events in Days 1–14 have the highest predictive weight for 90-day revenue?
- **Jobs-to-be-Done cohort overlay**: Segment cohorts by the JTBD that drove signup (e.g., "automate X" vs. "analyze Y") and compare revenue outcomes
- **Activation half-life**: At what hour/day post-signup does activation probability drop by 50%? Defines the intervention urgency window
- **Expansion cohort progression**: Month 1/3/6/9/12 ACV trajectory for accounts that started at different price points
- **Viral cohort analysis**: Compare revenue outcomes for users acquired through product invites vs. all other channels to quantify the viral growth dividend

DELIVERABLE STRUCTURE:

---

### MODULE 1: COHORT PERFORMANCE EXECUTIVE DASHBOARD

**PLG Revenue Cohort Snapshot (last 12 months)**

| Signup Cohort (Month) | Free Signups | Activation Rate | 30d Conversion | 90d Conversion | Median ACV at Conv. | 6-Month NRR | ARR per 100 Signups |
|---|---|---|---|---|---|---|---|
| Month -12 | [X] | [X%] | [X%] | [X%] | [$X] | [X%] | [$X] |
| Month -11 | ... | ... | ... | ... | ... | ... | ... |
| [Continue for all 12 months] |

**Key Observations:**
- Highest-performing cohort: [Month], [X%] conversion, [$X] ARR/100 signups — what drove this?
- Lowest-performing cohort: [Month], [X%] conversion — root cause hypothesis
- Trend direction: conversion rate improving / declining / flat (with slope %)
- Estimated ARR gap between top and bottom cohort performance if all cohorts matched top quartile: [$X/month]

---

### MODULE 2: ACTIVATION PATHWAY COHORT ANALYSIS

**Golden Path Discovery**

Map free-to-paid conversion rate and 12-month LTV by first 72-hour activation sequence:

| Activation Pathway | % of Users Who Take This Path | 30d Conversion Rate | 12-month LTV | Recommendation |
|---|---|---|---|---|
| Path A: [Onboarding wizard → First output → Invite teammate] | [X%] | [X%] | [$X] | Scale / Optimize / Abandon |
| Path B: [Template gallery → Customize → Export] | [X%] | [X%] | [$X] | ... |
| Path C: [Import data → View dashboard → Share report] | [X%] | [X%] | [$X] | ... |
| Path D: [API setup → Webhook → Integration test] | [X%] | [X%] | [$X] | ... |
| Unactivated: No meaningful action in 48h | [X%] | [X%] | [$X] | Rescue sequence |

**GOLDEN PATH VERDICT:**
- Identified golden path: [Specific sequence of 3–5 events]
- Golden path conversion premium: [X%] higher than baseline
- Golden path LTV premium: [$X] higher per account
- % of current signups who reach golden path: [X%]
- ARR impact of routing 25% more signups through golden path: [$X/year]
- Top 3 friction points preventing users from reaching golden path:
  1. [Friction 1 + proposed fix]
  2. [Friction 2 + proposed fix]
  3. [Friction 3 + proposed fix]

**ACTIVATION HALF-LIFE:**
- 50% of eventual activations occur within [X hours] of signup
- 90% of eventual activations occur within [X hours] of signup
- Implication: Intervention urgency window is [X hours] — after this, recovery probability drops to [X%]
- Recommended automated intervention at hour [X] for unactivated users: [Specific action]

---

### MODULE 3: ACQUISITION CHANNEL COHORT COMPARISON

**Channel LTV Comparison (Apples-to-Apples)**

| Acquisition Channel | Monthly Signup Volume | Activation Rate | Median Days to Convert | 12-month Paid Retention | Average ACV | LTV/CAC Estimate | Verdict |
|---|---|---|---|---|---|---|---|
| Organic SEO | [X] | [X%] | [X days] | [X%] | [$X] | [X:1] | High LTV |
| Paid Search (Brand) | [X] | [X%] | [X days] | [X%] | [$X] | [X:1] | ... |
| Paid Search (Non-brand) | [X] | [X%] | [X days] | [X%] | [$X] | [X:1] | ... |
| Paid Social (LinkedIn) | [X] | [X%] | [X days] | [X%] | [$X] | [X:1] | ... |
| Product Viral (Invite/Share) | [X] | [X%] | [X days] | [X%] | [$X] | [X:1] | ... |
| Partner/Integration Referral | [X] | [X%] | [X days] | [X%] | [$X] | [X:1] | ... |
| Direct / Dark Social | [X] | [X%] | [X days] | [X%] | [$X] | [X:1] | ... |

**CHANNEL REALLOCATION RECOMMENDATION:**
- Overinvested channel (high volume, low cohort LTV): [Channel] — recommended budget reduction: [X%]
- Underinvested channel (low volume, high cohort LTV): [Channel] — recommended budget increase: [X%]
- Projected ARR impact of reallocation: [$X incremental ARR in 12 months]

**VIRAL COHORT PREMIUM:**
- Users acquired through product invites convert at [X%] vs. [Y%] for paid acquisition
- Viral cohort 12-month retention: [X%] vs. [Y%] average
- K-factor (invites sent per new paid user in first 30 days): [X]
- Viral revenue multiplier: every $1 spent acquiring a user who invites others generates [$X] in downstream ARR
- Recommendation to amplify viral loop: [Specific product or growth change]

---

### MODULE 4: FEATURE ADOPTION COHORT ANALYSIS

**Feature-to-Revenue Correlation Matrix**

For each core feature, show its relationship to downstream revenue outcomes:

| Feature | % Users Who Adopt in Days 1–14 | Conversion Lift vs. Non-Adopters | 6-Month Retention Lift | Expansion Propensity Lift | Revenue Signal Classification |
|---|---|---|---|---|---|
| [Feature 1: e.g., Team collaboration] | [X%] | +[X%pp] | +[X%pp] | +[X%pp] | MUST-ADOPT |
| [Feature 2: e.g., API integration] | [X%] | +[X%pp] | +[X%pp] | +[X%pp] | HIGH VALUE |
| [Feature 3: e.g., Dashboard sharing] | [X%] | +[X%pp] | +[X%pp] | +[X%pp] | HIGH VALUE |
| [Feature 4: e.g., Notification setup] | [X%] | +[X%pp] | +[X%pp] | +[X%pp] | MODERATE |
| [Feature 5: e.g., Advanced filter] | [X%] | -[X%pp] | -[X%pp] | -[X%pp] | FEATURE TRAP |

**FEATURE ADOPTION LADDER:**
The optimal activation sequence for maximum lifetime revenue:
1. Day 0–1: [Core setup action] → Required for any value
2. Day 1–3: [First output action] → First "aha" signal
3. Day 3–7: [Collaboration/sharing action] → Organizational commitment signal
4. Day 7–14: [Integration/API action] → Deep embed = high retention predictor
5. Day 14–30: [Advanced feature adoption] → Signals power user trajectory = expansion candidate

**FEATURE TRAPS IDENTIFIED:**
Features used heavily by churned users (false positive engagement signals):
- [Feature X]: [X%] of churned accounts used this heavily — it indicates [exploration without value realization / workaround behavior / trial gaming]
- Action: De-emphasize this feature in onboarding flow for ICP accounts; reroute toward [Feature Y]

---

### MODULE 5: EXPANSION REVENUE COHORT INTELLIGENCE

**Paid Account Expansion Trajectory by Starting ACV**

| Starting ACV Tier | % of Total Paid Accounts | Month 3 ACV (avg) | Month 6 ACV (avg) | Month 12 ACV (avg) | Expansion Rate M1→M12 | NRR |
|---|---|---|---|---|---|---|
| $0–$5K/yr (starter) | [X%] | [$X] | [$X] | [$X] | [X%] | [X%] |
| $5K–$15K/yr (growth) | [X%] | [$X] | [$X] | [$X] | [X%] | [X%] |
| $15K–$50K/yr (scale) | [X%] | [$X] | [$X] | [$X] | [X%] | [X%] |
| $50K+/yr (enterprise) | [X%] | [$X] | [$X] | [$X] | [X%] | [X%] |

**EXPANSION TRIGGER CLUSTER:**
The combination of behavioral events that precedes a 2x ACV expansion within 90 days:
1. [Event 1: e.g., 5+ users active in the account in a single week]
2. [Event 2: e.g., Integration with [Salesforce / Slack / Custom API] connected]
3. [Event 3: e.g., Usage hits [X%] of plan limit for 2+ consecutive weeks]
4. [Event 4: e.g., Admin user viewed pricing/upgrade page 2+ times]

When this cluster fires → trigger expansion play:
- For self-serve: automated in-app upgrade prompt + contextual email at 24h and 72h
- For PLS accounts ($15K+ ACV): AE notified within 4 hours with usage context + suggested expansion play
- Estimated expansion conversion rate when trigger cluster fires: [X%]
- Estimated ARR per triggered expansion event: [$X]

**NON-EXPANDING ACCOUNT OPPORTUNITY:**
- % of paid accounts in Month 6+ with no expansion: [X%]
- Estimated addressable expansion ARR from these accounts: [$X]
- Top 3 reasons accounts are not expanding (from exit surveys / CS call data):
  1. [Reason 1 + intervention]
  2. [Reason 2 + intervention]
  3. [Reason 3 + intervention]

---

### MODULE 6: CHURN COHORT CLUSTERING & RISK INTELLIGENCE

**Churn Cohort Profiles (Behavioral Clustering)**

Identify the 4 highest-risk churn cohort archetypes:

**Archetype 1: The "Tourist"**
- Profile: Signed up from [paid ad], never invited a teammate, only used [Feature X], didn't complete onboarding
- Churn timeline: Cancels within [45–60 days] of conversion
- Monthly ARR at risk: [$X]
- Intervention: At-signup routing change + forced onboarding gate before accessing [Feature X]

**Archetype 2: The "Solo Power User Who Left the Company"**
- Profile: 1-seat account, high personal usage, cancellation coincides with [job change signal / LinkedIn activity]
- Churn timeline: Cancels within [30 days] of trigger event
- Monthly ARR at risk: [$X]
- Intervention: Proactive multi-stakeholder expansion before single-user dependency becomes risk

**Archetype 3: The "Pilot That Never Scaled"**
- Profile: Started with 3–5 seats, never grew beyond initial team, usage plateau at Month 3
- Churn timeline: Cancels at renewal (Month 11–12)
- Monthly ARR at risk: [$X]
- Intervention: Month 3 executive sponsor QBR + internal champion identification program

**Archetype 4: The "Workflow Abandoner"**
- Profile: Used product heavily in first 30 days, then usage dropped sharply, no product updates in last 60 days
- Churn timeline: Silent for [X] days before cancellation
- Monthly ARR at risk: [$X]
- Intervention: Re-engagement email sequence triggered at Day [X] of inactivity + new feature reveal

**CHURN PREVENTION ROI MODEL:**
If a 25% reduction in each archetype's churn rate is achieved:
- Archetype 1: [$X ARR saved/month]
- Archetype 2: [$X ARR saved/month]
- Archetype 3: [$X ARR saved/month]
- Archetype 4: [$X ARR saved/month]
- **Total: [$X ARR saved/month → $X ARR saved/year]**

---

### MODULE 7: PREDICTIVE COHORT HEALTH SCORE (7-DAY SIGNAL)

A score computed 7 days after free signup to predict 12-month revenue probability.

**COHORT HEALTH SCORE MODEL:**

| Signal | Weight | Scoring Logic |
|---|---|---|
| Aha moment achieved within 72h | 30 pts | Yes = 30; No = 0 |
| Invited 1+ teammates within 7 days | 20 pts | Yes = 20; No = 0 |
| Used product on 4+ distinct days in Week 1 | 15 pts | Yes = 15; No = 0 |
| Completed onboarding checklist >75% | 10 pts | Yes = 10; <50% = 0 |
| Company size ≥100 employees (ICP fit) | 10 pts | Yes = 10; <50 emp = 0 |
| Connected integration/API in first 7 days | 10 pts | Yes = 10; No = 0 |
| Work email domain (not gmail/yahoo) | 5 pts | Yes = 5; No = 0 |
| Logged in from 2+ devices | 5 pts | Yes = 5; No = 0 |
| Deduct: Zero activity days 3–7 | -15 pts | If no activity on days 3–7 |
| Deduct: Only used 1 feature | -10 pts | If only 1 distinct feature type used |

**SCORE INTERPRETATION:**
- 80–100 (High-Revenue Cohort): [X%] of users → convert at [X%], 12-mo LTV [$X] → Arm AE with priority outreach if PLS motion
- 55–79 (Promising Cohort): [X%] of users → convert at [X%], 12-mo LTV [$X] → Automated nurture + targeted upgrade prompt at Day 14
- 30–54 (At-Risk Cohort): [X%] of users → convert at [X%], 12-mo LTV [$X] → Re-engagement sequence + human CSM outreach for high-ICP accounts
- 0–29 (Low-Revenue Cohort): [X%] of users → convert at [X%], 12-mo LTV [$X] → Low-cost automation only; focus budget on acquisition quality upstream

**COHORT HEALTH SCORE INTEGRATION:**
- Push score to CRM as custom field within 7 days of signup
- Trigger Slack alert to SDR/AE team when score ≥80 for ICP-fit accounts
- Use score as primary input for in-app messaging personalization engine
- Review score distribution monthly — a downward shift in new signup scores signals acquisition quality degradation before conversion metrics show it

---

### MODULE 8: ARR IMPACT WATERFALL & 90-DAY ACTION ROADMAP

**PRIORITIZED ARR RECOVERY WATERFALL:**

| Initiative | ARR Impact (12-month) | Owner | Effort | Timeline |
|---|---|---|---|---|
| 1. Route 25% more signups through golden activation path | +[$X ARR] | Product + Growth | Medium | 3–4 weeks |
| 2. Reallocate [X% budget] from [low-LTV channel] to [high-LTV channel] | +[$X ARR] | Growth Marketing | Low | 1 week |
| 3. Deploy expansion trigger cluster automation | +[$X ARR] | RevOps + CS | Medium | 4–6 weeks |
| 4. Implement Archetype 1 churn prevention at signup | +[$X ARR] | Product + CS | Low | 1–2 weeks |
| 5. Launch Archetype 3 Month 3 QBR program | +[$X ARR] | CS + Sales | Medium | 3–4 weeks |
| 6. Activate cohort health score → CRM → AE routing | +[$X ARR] | RevOps + Marketing | Medium | 2–3 weeks |
| 7. Feature trap elimination from onboarding flow | +[$X ARR] | Product | Low | 1–2 weeks |

**TOTAL ESTIMATED ARR IMPACT: +[$X–$Y over 12 months]**

**90-DAY SPRINT PLAN:**

*WEEKS 1–2 (Quick Wins):*
- Implement cohort health score and push to CRM
- Reroute channel budget away from lowest-LTV source
- Remove feature trap from primary onboarding flow

*WEEKS 3–6 (Core Infrastructure):*
- Build golden path optimization into in-app onboarding
- Deploy expansion trigger cluster alerts to RevOps/AE
- Launch Archetype 1 + 4 churn prevention sequences

*WEEKS 7–12 (Compound Growth):*
- A/B test 2 activation path variants against golden path baseline
- Run first cohort health score review — adjust weights based on 60-day outcome data
- Launch Archetype 3 QBR program with CS team
- Report first cohort LTV improvement to board

## Example Input/Output

**EXAMPLE COMPANY: Scribeflow AI**
- B2B SaaS, Series A, $3.2M ARR
- Product: AI-powered meeting intelligence — auto-transcribes, summarizes, and creates action items from video calls
- PLG motion: Freemium (unlimited calls up to 5 users; paid unlocks unlimited seats + CRM sync)
- Primary ICP: Revenue Operations leads at 100–1,000 person tech/SaaS companies
- Monthly free signups: 2,800
- Activation rate: 34%
- Free-to-paid conversion: 3.1%
- Monthly churn: 4.2%
- NRR: 107%

**OUTPUT EXCERPT — Golden Path Discovery:**

After analyzing 18 months of activation event data, the Scribeflow golden path is:

**Day 0–1:** Record first meeting (sync via Zoom/Google Meet integration) ← Only 41% of signups complete this
**Day 1–3:** Share summary with a non-signup teammate via email or Slack ← Drops to 22% of signups; this is the biggest leak
**Day 3–7:** Tag 3+ action items and assign to team members ← Drops to 11% of signups; but users who reach this step convert at 31% vs. 3.1% baseline

**Insight:** Users who complete the full golden path convert at 10x baseline. But 59% of signups never record their first meeting (Day 0 failure). Root cause: Zoom/Google Meet OAuth setup requires admin approval in enterprise accounts — users are abandoning before they see any value.

**Fix:** Add a manual upload fallback (drag-and-drop audio/video file) for users who can't connect calendar integration. Estimated to rescue 40% of Day-0 dropouts.

**ARR impact:** If rescue rate is 40% of 59% dropout × current conversion rate × $6,200 median ACV × 2,800/month signups = **+$138K ARR/month** from this single fix.

---

**OUTPUT EXCERPT — Churn Archetype: "The Pilot That Never Scaled"**

- 31% of Scribeflow's paid accounts started with 2–4 seats, never grew beyond 5 seats, and usage plateau'd at Month 3
- These accounts churn at Month 11 (renewal), citing "didn't drive enough adoption internally"
- Monthly ARR at risk: $44K/month
- Intervention: At Month 3, trigger an Executive Sponsor Campaign — auto-generate a "ROI Report" showing time saved, action items completed, and estimated productivity value, sent to the billing admin and their manager
- Estimated churn prevention: 35% of at-risk accounts, worth **$15.4K ARR saved/month**

## Success Metrics

| Metric | Measurement Approach | Target |
|---|---|---|
| Golden path adoption rate | % of signups completing defined golden path within 14 days | Increase by 15–25% within 90 days |
| Cohort LTV improvement | ARR per 100 signups, 12-month rolling | Improve top-quartile cohort conversion by ≥2pp |
| Churn archetype reduction | Monthly ARR churn from each identified archetype | Reduce each archetype churn by ≥20% in 90 days |
| Expansion trigger conversion | % of expansion trigger events that convert to ACV increase | ≥35% within 30 days of trigger |
| Cohort health score accuracy | Correlation of Day-7 score with 90-day revenue outcome | Pearson r ≥ 0.65 |
| Channel LTV reallocation ROI | ARR per $1 of acquisition spend before/after reallocation | ≥15% improvement in LTV/CAC within 6 months |

A strong output includes:
- Specific ARR dollar figures for every initiative (not ranges)
- Cohort tables with actual percentage differences between top and bottom segments
- Named churn archetypes with behavioral fingerprints that anyone on the team can recognize
- An expansion trigger definition precise enough to implement in Segment/Amplitude as an automated event

## Related Prompts

- [`AI-Powered-B2B-SaaS-PLG-Analytics-Program-&-Product-Signal-to-Revenue-Intelligence-Engine.md`](./AI-Powered-B2B-SaaS-PLG-Analytics-Program-&-Product-Signal-to-Revenue-Intelligence-Engine.md) — Comprehensive PLG analytics audit covering PQL scoring and activation funnel
- [`../../05_Analytics-&-Performance/Product-Analytics-&-Activation/PLG-Revenue-Conversion-Analytics-&-Product-Qualified-Revenue-Intelligence-Engine.md`](../Product-Analytics-&-Activation/PLG-Revenue-Conversion-Analytics-&-Product-Qualified-Revenue-Intelligence-Engine.md) — PQL-to-revenue conversion analytics and product-qualified revenue measurement
- [`../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/Cohort-Based-LTV-&-Revenue-Retention-Intelligence-Engine.md`](../Customer-Lifetime-Value-Analytics/Cohort-Based-LTV-&-Revenue-Retention-Intelligence-Engine.md) — General cohort LTV analysis across all GTM motions
- [`../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/AI-Powered-B2B-SaaS-Product-Led-Sales-PLS-Motion-Architecture-&-Product-Signal-to-Revenue-Sales-Assist-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/AI-Powered-B2B-SaaS-Product-Led-Sales-PLS-Motion-Architecture-&-Product-Signal-to-Revenue-Sales-Assist-Intelligence-Engine.md) — Designing the PLS motion that cohort analytics informs

## Integration Tips

**Amplitude / Mixpanel:**
- Use the cohort health score signals as computed properties in your analytics tool
- Set up behavioral cohort comparisons using the golden path event sequence as the defining cohort criterion
- Schedule weekly cohort retention reports to Slack via native integrations

**Segment CDP:**
- Create a computed trait for "Golden Path Completed" (boolean) and "Cohort Health Score" (0–100 integer)
- Route high-score users automatically to Salesforce or HubSpot as Marketing Qualified Accounts (MQAs)
- Use Segment's Journeys or Personas to build dynamic cohort audiences for in-app messaging

**Salesforce / HubSpot CRM:**
- Sync Cohort Health Score as a custom object field; use it in lead scoring workflows and AE assignment rules
- Create a "Churn Archetype" custom field (populated by Segment or Zapier) to route CS plays automatically
- Build deal pipelines that track expansion trigger events as deal-creation triggers

**Looker / Tableau / Google Looker Studio:**
- Build a "Cohort Revenue Dashboard" with the 8 tables from this prompt as the data model
- Schedule automated cohort digest to the leadership team every Monday morning
- Create a live "Churn Archetype Risk" tile showing current ARR at risk by archetype

**Zapier / Make:**
- Trigger: Cohort Health Score calculated (via Segment webhook) → Action: AE email alert in Gmail + HubSpot task
- Trigger: Expansion trigger cluster fires (Amplitude event) → Action: Create Salesforce opportunity + Slack alert to AE
- Trigger: Churn Archetype 3 criteria met (Month 3 plateau) → Action: Launch Intercom QBR sequence

## Troubleshooting

**Problem: "We don't have event-level product data going back 12 months."**
Solution: Start with 3-month cohort windows using your available data. Even 90 days of event data is sufficient to identify golden path adoption rates and churn archetype patterns. For missing historical data, use your billing system's subscription history (Stripe/Chargebee) as a revenue cohort baseline, and overlay whatever product events you do have. Build the full data infrastructure for future cohorts starting now.

**Problem: "The model output recommends the golden path, but we can't change onboarding because it's a major engineering lift."**
Solution: Separate activation friction into two buckets: (1) product changes requiring engineering (deprioritize for now), and (2) in-app messaging / email sequence optimizations that can guide users toward the golden path without changing the product UI (implement in Intercom, Appcues, or Pendo within 1–2 weeks). Start with messaging changes — even a well-timed email at Hour 4 of inactivity can lift golden path adoption by 8–15%.

**Problem: "Our expansion trigger cluster fires frequently but AEs aren't acting on it."**
Solution: The problem is almost always information overload or unclear ownership. Fix with two changes: (1) build a single "PLG Expansion Alert" Slack message template that includes the account name, expansion score, top 3 product signals, and a pre-populated email draft — make it one click to act; (2) add expansion trigger response rate as a metric in AE weekly pipeline reviews with a personal conversion rate for each rep. Social accountability drives response rates more than alert volume.

## Version History
- v1.0: Initial creation (auto-generated)
