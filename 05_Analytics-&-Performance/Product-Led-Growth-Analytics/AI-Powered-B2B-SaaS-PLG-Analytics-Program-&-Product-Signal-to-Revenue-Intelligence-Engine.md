# AI-Powered B2B SaaS PLG Analytics Program & Product Signal-to-Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** product-led-growth, PLG, PQL, activation, free-to-paid, expansion-revenue, SaaS-analytics, product-analytics

## Overview
Deploys an AI analytics engine to ingest product usage telemetry, activation event logs, conversion cohorts, and revenue data to surface the precise product signals that predict trial-to-paid conversion, expansion revenue, and churn — then auto-generates a prioritized action plan for growth, product, and marketing teams. Use this when free-to-paid conversion rates are stalling, activation rates are below 40%, or your PLG motion is generating signups but not revenue.

## Quick Copy-Paste Version

You are a senior PLG analytics strategist specializing in B2B SaaS product-led growth revenue intelligence.

I need a comprehensive PLG analytics audit for my company. Here is our situation:

Company: [Your Company Name]
Product: [What it does in 1 sentence]
PLG motion: [Free trial / Freemium / Reverse trial]
Trial/free plan length: [14 days / 30 days / Unlimited freemium]
Primary ICP: [Job title at company size, e.g., "Head of Ops at 50–500 person SaaS"]
Current free signup to paid conversion rate: [X%]
Target conversion rate: [Y%]
Average time-to-first-value (aha moment): [X days]
Current monthly active users on free: [Number]
Data available: [Mixpanel / Amplitude / Heap / Product Analytics tool / Segment / Custom]

Analyze my PLG motion and produce:

1. ACTIVATION FUNNEL BREAKDOWN
   - Map the activation sequence: Signup → Account Setup → First Core Action → Repeated Use → Aha Moment → Conversion Intent
   - Identify the biggest drop-off stage with % fallout
   - Calculate the activation rate (users who reach aha moment ÷ total signups)
   - Flag the single highest-impact intervention to improve activation

2. PQL SCORING MODEL
   - Define the 5–8 product behaviors that correlate most strongly with paid conversion
   - Build a PQL score formula using weighted behavioral signals
   - Segment users into: Cold (score 0–30), Warming (31–60), Hot PQL (61–85), Sales-Ready PQL (86–100)
   - Recommend the handoff trigger from product-led to sales-assisted

3. FREE-TO-PAID CONVERSION ANALYSIS
   - Conversion rate broken down by: signup source, ICP segment, activation depth, time-to-first-value, # of seats/users invited
   - Identify the conversion half-life: how many days after signup does conversion probability drop by 50%?
   - List the top 3 in-app moments where conversion probability spikes
   - Design 2 conversion nudge sequences triggered by these moments

4. EXPANSION REVENUE SIGNALS
   - Which product usage behaviors predict upsell within 90 days?
   - Which features are most correlated with seat expansion vs. tier upgrade?
   - Identify the "expansion trigger cluster" — the combination of events that reliably precedes a customer expanding ARR by 2x
   - Generate an expansion health score for your current customer base

5. CHURN RISK DETECTION
   - Build a 30-day churn risk model using product engagement signals
   - Identify the "silent churn" pattern: users who appear active but are disengaging
   - Flag the usage decline curve that predicts cancellation 45+ days in advance
   - Design 1 automated re-engagement sequence triggered by early churn signals

6. PRIORITIZED GROWTH ACTION PLAN
   - 3 immediate actions for the product team (fix activation blockers)
   - 3 immediate actions for growth/marketing (improve PQL conversion)
   - 3 immediate actions for sales (prioritize high-signal PLG accounts)
   - 1 A/B test to run immediately with expected conversion lift

Format as a PLG Revenue Intelligence Brief with a PQL scoring rubric, conversion funnel visualization (text-based), and a 90-day action roadmap. Prioritize every action by estimated ARR impact.

## Advanced Customizable Version

ROLE: You are an AI-powered PLG Revenue Intelligence Engine. You combine the analytical rigor of a product analytics expert, the revenue focus of a growth marketer, and the precision of a data scientist. Your outputs are consumed simultaneously by the CEO, CPO, VP Growth, VP Sales, and Head of Revenue Operations.

CONTEXT:
- Company: [Company Name]
- Stage: [Seed / Series A / Series B / Growth]
- ARR: [Current ARR]
- PLG motion type: [Free Trial (time-limited) / Freemium (feature-limited) / Reverse Trial (full features, then downgrade) / Sandbox/Demo environment]
- Pricing model: [Per seat / Usage-based / Tier-based / Hybrid]
- ACV range (paid customers): [e.g., $6K–$80K]
- Sales-assist motion: [Pure self-serve / Product-led sales (PLS) / Sales-assisted above X ARR threshold]
- Primary ICP: [Job title, company size, industry]
- Secondary ICP: [Job title, company size, industry]
- Product analytics tool: [Mixpanel / Amplitude / Heap / Pendo / Custom / Segment CDP]
- CRM: [Salesforce / HubSpot / Pipedrive]
- Current metrics:
  * Monthly signups: [Number]
  * Trial-to-paid conversion rate: [X%] (industry benchmark for your segment: typically 2–5% freemium, 15–25% time-limited trial)
  * Median time-to-conversion: [X days]
  * Activation rate (aha moment reached): [X%]
  * Monthly expansion revenue %: [X% of MRR]
  * Monthly churn rate: [X%]
  * NRR (Net Revenue Retention): [X%]
  * PQL volume per month: [Number, or "not yet defined"]
- Data available:
  * Event-level product usage data: [Yes/No — retention period: ___ days]
  * CRM closed-won/lost with PLG source tag: [Yes/No]
  * Billing system (Stripe/Chargebee) with plan history: [Yes/No]
  * In-app survey data (Intercom/Appcues): [Yes/No — sample size: ___]
  * Support ticket volume by user segment: [Yes/No]
- Key aha moment hypothesis: [e.g., "User creates their first automated workflow and shares it with a teammate"]
- Core feature set (list 5–10 key features):
  [Feature 1, Feature 2, Feature 3...]
- Known activation blockers: [e.g., "Complex onboarding, requires data import before seeing value"]
- Sales-assist threshold: [e.g., "SDR reaches out when company size >200 and PQL score >70"]

OBJECTIVE:
Produce a PLG Revenue Intelligence Report that:
1. Identifies the exact product behaviors that predict revenue conversion with >75% accuracy
2. Exposes activation drop-off points costing the most recoverable ARR
3. Builds a PQL scoring model the sales team can act on within 48 hours
4. Surfaces expansion revenue signals that currently go undetected
5. Designs an automated signal-to-action system requiring zero manual analysis

ANALYTICAL FRAMEWORKS TO APPLY:
- North Star Metric decomposition: Break the PLG flywheel into leading indicators → lagging revenue outcomes
- Cohort retention curve analysis: Identify which cohorts retain at L30/L60/L90 vs. those that flatline
- Feature-outcome correlation matrix: Map each feature's usage rate against conversion and retention outcomes
- Time-to-value (TTV) optimization: Shorten the path from signup to first "I get it" moment
- Jobs-to-be-Done (JTBD) lens: What job did the user hire this product to do? Are they succeeding?
- Viral coefficient (K-factor) measurement: Track invite-to-join conversion rates to identify organic growth loops

DELIVERABLE STRUCTURE:

### SECTION 1: PLG EXECUTIVE SUMMARY
- Current PLG funnel snapshot: [Signups → Activated → PQL → Converted → Expanded]
- ARR generated from PLG motion (self-serve + PLS combined) vs. direct sales
- % of pipeline sourced from product-led signups
- Estimated recoverable ARR if activation rate improves by 10pp
- Estimated recoverable ARR if free-to-paid conversion improves by 2pp
- One priority recommendation for each function: Product / Growth / Sales / CS

### SECTION 2: ACTIVATION FUNNEL INTELLIGENCE

Map the full activation sequence with conversion rates at each step:

SIGNUP
  ↓ [___% complete]
EMAIL VERIFIED / ACCOUNT SETUP
  ↓ [___% complete]
FIRST CORE ACTION (e.g., created first project / imported data / invited teammate)
  ↓ [___% complete]
REPEATED CORE ACTION (3+ times within 7 days)
  ↓ [___% complete]
AHA MOMENT (specific combination of events that defines "I get it")
  ↓ [___% complete]
CONVERSION INTENT SIGNAL (viewed pricing page / started upgrade flow / invited 3+ users)
  ↓ [___% complete]
PAID CONVERSION

For each stage drop-off, provide:
- The most common reason users exit at this stage (from survey data or behavioral inference)
- The intervention with highest expected lift
- The team responsible for fixing it (Product / Onboarding / Marketing / Sales)
- Implementation complexity: Low (1–3 days) / Medium (1–2 weeks) / High (sprint+)

BIGGEST LEAK STAGE DEEP DIVE:
- Identify the single stage with the highest absolute user volume falling off
- Calculate the ARR impact of recovering 20% of those users
- Design a specific intervention sequence (in-app messaging / email / human touch)

### SECTION 3: PQL SCORING ARCHITECTURE

Define the PQL (Product Qualified Lead) scoring model using a weighted behavioral signal matrix:

**TIER 1 SIGNALS — High Predictive Power (15–25 points each)**
| Signal | Weight | Rationale |
|--------|--------|-----------|
| [Aha moment completed] | 25 pts | Users who reach aha moment convert at 3–4x baseline rate |
| [Invited 2+ teammates] | 20 pts | Viral/collaborative usage signals organizational buy-in |
| [Core feature used 5+ times in 7 days] | 20 pts | Habit formation correlates strongly with retention |
| [Viewed pricing page 2+ times] | 15 pts | High purchase intent signal |

**TIER 2 SIGNALS — Moderate Predictive Power (8–14 points each)**
| Signal | Weight | Rationale |
|--------|--------|-----------|
| [Completed full onboarding checklist] | 12 pts | Setup completion correlates with stickiness |
| [Used product on 3+ distinct calendar days in last 7] | 10 pts | Frequency of use = habit indicator |
| [Integrated with external tool/API] | 10 pts | Integration users churn 60% less |
| [Exported or shared output] | 8 pts | Task completion = value realization |

**TIER 3 SIGNALS — Context / Firmographic Enrichment (3–7 points each)**
| Signal | Weight | Rationale |
|--------|--------|-----------|
| [Company size 100+ employees] | 7 pts | Larger orgs → higher ACV potential |
| [Work email domain (not Gmail/Yahoo)] | 5 pts | B2B vs. individual signal |
| [Signed up with LinkedIn / SSO] | 3 pts | Professional context signal |

**NEGATIVE SIGNALS (deduct points)**
| Signal | Deduction | Rationale |
|--------|-----------|-----------|
| [No login in last 7 days] | -15 pts | Engagement decay signal |
| [Only used product once total] | -10 pts | One-and-done pattern |
| [Opened upgrade email but didn't click] | -5 pts | Considered but rejected |

**PQL SEGMENT DEFINITIONS:**
- **Cold (0–30):** Nurture with educational in-app content; no sales reach-out
- **Warming (31–55):** Automated email nudge sequence (3 emails, 7-day cadence); surface feature they haven't tried
- **Hot PQL (56–80):** In-app upgrade prompt + automated SDR email sequence; prioritize for 1:1 outreach within 72 hours
- **Sales-Ready PQL (81–100):** Immediate SDR or AE outreach within 24 hours; arm rep with full usage context from product data

**HANDOFF PROTOCOL:**
When a user reaches Hot/Sales-Ready PQL status, automatically push to CRM with:
- Usage summary (last 7 days of key events)
- PQL score and breakdown
- Recommended opening line based on their specific product behavior
- Suggested outreach channel (email / in-app / phone) based on response history

### SECTION 4: FREE-TO-PAID CONVERSION INTELLIGENCE

**Conversion Rate Segmentation Matrix:**

| Segment | Conversion Rate | vs. Avg | ARR Contribution |
|---------|----------------|---------|-----------------|
| Users who invited 2+ teammates | ___% | ___pp | $___ |
| Users who completed aha moment <7 days | ___% | ___pp | $___ |
| Users from LinkedIn / paid social | ___% | ___pp | $___ |
| Users from organic / SEO | ___% | ___pp | $___ |
| Users with company size 100–500 | ___% | ___pp | $___ |
| Users from partner/integration referral | ___% | ___pp | $___ |
| Users who contacted support in trial | ___% | ___pp | $___ |

Flag in RED any segment converting below 50% of average. These are your priority repair zones.

**CONVERSION HALF-LIFE ANALYSIS:**
- Day 0–7: [___% of eventual converters have converted]
- Day 8–14: [___% of eventual converters have converted]
- Day 15–21: [___% of eventual converters have converted]
- Day 22–30: [___% of eventual converters have converted]
- Day 31+: [___% of eventual converters have converted]

Define the "conversion urgency window" — the period where conversion probability begins to decay. All high-intent interventions must land BEFORE this window closes.

**TOP 3 IN-APP CONVERSION MOMENTS:**
For each moment where upgrade intent spikes (e.g., hitting a usage limit, sharing with external stakeholder, reaching 7-day streak of use):
- Trigger: [Specific event or condition]
- Conversion uplift observed: [___pp above baseline]
- Recommended in-app prompt: [Exact copy for upgrade CTA]
- Recommended email follow-up: [Subject line + 2-line preview]

### SECTION 5: EXPANSION REVENUE INTELLIGENCE

**EXPANSION TRIGGER CLUSTER ANALYSIS:**
Identify the specific combination of product events that reliably precedes account expansion (definition: ARR increase of ≥25% within 90 days):

Primary expansion signals:
1. [Event A] AND [Event B] occurring within [X days] → Expansion probability: [___]%
2. [Event C] with [frequency threshold] → Expansion probability: [___]%
3. [Feature D adoption] crossing [threshold] → Expansion probability: [___]%

**EXPANSION HEALTH SCORE (per account):**

Score = (Seat utilization % × 30) + (Feature adoption breadth × 25) + (Usage frequency trend × 25) + (Shared output volume × 20)

- 80–100: Expansion-ready → Queue for CSM-led expansion conversation + send ROI summary
- 60–79: Growing → Introduce advanced features; plant ROI seeds in product UI
- 40–59: Stable → Maintain engagement; monitor for expansion triggers
- Below 40: At-risk → Proactive intervention required before expansion is possible

**FEATURE ADOPTION → EXPANSION CORRELATION:**

| Feature | Users with feature active | Expansion rate (vs. non-users) | Recommended action |
|---------|--------------------------|-------------------------------|-------------------|
| [Feature A] | ___% | ___x higher | Surface to users who haven't tried it |
| [Feature B] | ___% | ___x higher | Gate behind paid tier / promote in-app |
| [Feature C] | ___% | ___x higher | Build onboarding checklist step |

### SECTION 6: CHURN RISK EARLY WARNING SYSTEM

**30-DAY CHURN PREDICTION MODEL:**

HIGH CHURN SIGNALS (flag for intervention):
- No login in last 14 days AND previously daily active: Churn probability +65%
- Support ticket opened about a core workflow failure: Churn probability +45%
- Only 1 seat active (team product used solo): Churn probability +35%
- Feature that drove conversion no longer in use: Churn probability +55%
- Downgraded plan tier in last 30 days: Churn probability +70%

SILENT CHURN DETECTION — the "ghost user" pattern:
Users who log in but show declining depth of engagement:
- Login frequency: Maintained ✓
- Session length: Declining ↓
- Core feature usage: Declining ↓
- Data/content created: Declining ↓

Flag accounts where login frequency remains high BUT session depth declining for 21+ consecutive days. This is the most dangerous churn pattern — the user "shows up" but has mentally already left.

**AUTOMATED CHURN INTERVENTION SEQUENCES:**

For accounts with churn probability >50%:

*Sequence A — Re-engagement (Days 1–14 of risk signal):*
- Day 1: In-app message from "your account manager" offering a 15-min value review call
- Day 3: Email with personalized "3 things you haven't tried yet" based on their usage profile
- Day 7: Slack/email from assigned CSM with a specific success story from a similar company
- Day 14: Executive-to-executive reach-out if ACV >$25K

*Sequence B — Save Offer (Days 15–30 of risk signal):*
- Day 15: Proactive discount or extended term offer (if justified by LTV)
- Day 21: Case study from a customer who was struggling at the same stage and found the fix
- Day 28: Exit survey to capture loss insight if cancellation is imminent

### SECTION 7: PLG ATTRIBUTION & REVENUE MEASUREMENT

**PLG Attribution Framework:**

Define what counts as "PLG-sourced revenue" vs. "Sales-sourced revenue" for accurate GTM efficiency measurement:

- **Pure self-serve:** User signed up, converted, and expanded with zero sales involvement
- **Product-led sales (PLS):** User signed up via PLG, but AE/SDR assisted the conversion
- **Sales-sourced with product assist:** Enterprise deal sourced by sales, but trial/sandbox played a role in evaluation

Track and report these separately to avoid inflating or deflating PLG ROI.

**KEY PLG PERFORMANCE METRICS — WEEKLY DASHBOARD:**

| Metric | Current | Target | Trend |
|--------|---------|--------|-------|
| New signups (week) | | | |
| Activation rate (aha moment %) | | | |
| Time-to-first-value (median, days) | | | |
| PQL volume generated | | | |
| Free-to-paid conversion rate | | | |
| Median time-to-convert (days) | | | |
| Self-serve ARR (week) | | | |
| PLS ARR (week) | | | |
| Monthly expansion revenue | | | |
| Monthly churn from PLG cohort | | | |
| NRR from PLG-sourced customers | | | |
| Viral coefficient (K-factor) | | | |

**NORTH STAR METRIC DECOMPOSITION:**

If your North Star Metric (NSM) = [e.g., "Weekly active teams completing 5+ workflows"]:

NSM = Signups × Activation Rate × Retention Rate × Teams Invited

To move NSM by 20%, you can either:
- Option A: Improve activation rate from 32% → 40% (+25% relative) → NSM +8pp
- Option B: Improve 7-day retention by 10pp → NSM +12pp
- Option C: Improve viral loop (teams invited per activated user) from 1.2 → 1.8 → NSM adds compounding growth

Run sensitivity analysis on all 4 levers before committing budget.

### SECTION 8: A/B TESTING ROADMAP

Prioritize experiments by expected revenue lift ÷ implementation effort:

**Priority 1 (Run Immediately — High Impact, Low Effort):**
- Test: [Specific in-app change — e.g., "Move the 'Invite teammate' CTA from settings page to the main dashboard"]
- Hypothesis: Users who invite teammates convert at 3.2x the rate of solo users. Surfacing the invite earlier will increase invite rate by 30% and conversion by 8pp.
- Primary metric: Invite rate in first 3 days
- Secondary metric: 14-day conversion rate
- Sample size needed: [___] users per variant
- Expected duration: [___] days

**Priority 2 (Next Sprint — High Impact, Medium Effort):**
- Test: [Second highest-impact experiment]
- Rationale, metrics, and expected lift

**Priority 3 (Next Quarter — Structural Change):**
- Test: [Strategic change such as trial length, pricing page redesign, or onboarding redesign]

### SECTION 9: PRIORITIZED ACTION PLAN

**IMMEDIATE (0–30 days):**

[Product Team]
1. [Specific activation bottleneck to fix with ticket description and expected lift]
2. [In-app experience change with specific copy/UX change and expected impact]
3. [Feature gate or usage limit to reconfigure to improve conversion moment]

[Growth / Marketing Team]
1. [Specific PQL nurture sequence to build with channel, cadence, and messaging brief]
2. [Conversion-moment campaign to launch targeting hot PQL segment]
3. [Onboarding email sequence to A/B test with specific hypothesis]

[Sales / Revenue Operations]
1. [PQL routing rule to configure in CRM with handoff criteria]
2. [SDR outreach template tailored to top 3 PQL behavioral patterns]
3. [Expansion trigger alert to set up with assigned CSM notification protocol]

**MEDIUM-TERM (30–90 days):**
1. [Build or integrate full PQL scoring into CRM as a live field]
2. [Launch quarterly PLG cohort analysis cadence with dashboard in BI tool]
3. [Implement product-led expansion motion: automated in-app upsell flows for accounts hitting expansion trigger cluster]

OUTPUT FORMAT: PLG Revenue Intelligence Brief with a color-coded PQL scoring rubric, text-based funnel visualization, weekly dashboard template, and 90-day prioritized roadmap. All metrics presented with current baseline + target + estimated ARR impact. Flag each insight as: CONFIRMED (from data) / BEHAVIORAL INFERENCE (from usage patterns) / HYPOTHESIS (needs testing).

## Example Input/Output

**Input Example:**

Company: Clairo (B2B SaaS collaborative project management for design agencies)
PLG motion: 14-day free trial, all features unlocked
ICP: Creative Directors at design agencies with 10–100 employees
Current trial-to-paid conversion: 8.4%
Activation rate (defined as: created first project + uploaded 1+ asset + invited 1 teammate): 31%
Average time-to-aha: 4.2 days when it happens, but only 31% reach it
Primary churn signal: Users who complete trial but never invite a teammate (72% of those never convert)
Data: Amplitude event data, Stripe billing, HubSpot CRM

**Output Example (Abbreviated):**

---
**PLG REVENUE INTELLIGENCE SUMMARY — CLAIRO**

**Recoverable ARR opportunity:** $2.8M annually from three fixable activation and conversion gaps

**Critical Finding:** Clairo's 8.4% trial-to-paid rate is suppressed by a single activation bottleneck: only 31% of trial users invite a teammate during the trial window. Among users who DO invite a teammate within the first 3 days, conversion rate jumps to 34% — 4x the baseline. This is the highest-leverage lever in the entire PLG motion.

**Activation Funnel (Current State):**
Trial Signup:         100% (1,000 users/month baseline)
  ↓ 78% complete
Email Verified:       780 users
  ↓ 61% complete
First Project Created: 476 users
  ↓ 65% complete
First Asset Uploaded:  309 users
  ↓ 52% complete   ← BIGGEST LEAK: Teammate Invite
Teammate Invited:      161 users  [31% of signups — below 40% benchmark]
  ↓ 86% complete
Aha Moment Reached:   138 users   [CONFIRMED aha = project shared + feedback received]
  ↓ 61% complete
Paid Conversion:       84 users   [8.4% overall / 61% conditional on aha moment]

**Recoverable ARR if teammate invite step improves from 31% → 50%:**
- Additional activated users: +190/month
- At 61% conditional conversion: +116 additional paying users
- At $280 ARPU: +$32,480 MRR = **+$390K ARR from one activation fix**

**PQL Score for Clairo (Top Signal Profile — "Hot PQL"):**
User who: (a) created 2+ projects, (b) invited 1+ teammate, (c) received and responded to a comment in-product, (d) logged in on 4+ of last 7 days = PQL score 87. This cohort converts at 71%.

**Immediate Priority 1:** Move "Invite your team" from onboarding step 6 of 7 to a post-first-project modal that triggers immediately after the user creates their first project. Add social proof: "Teams with 3+ members complete projects 4x faster." Expected teammate invite rate improvement: +12pp in first 7 days.

**Immediate Priority 2:** Launch a "Day 3 recovery" email for any trial user who has NOT invited a teammate by day 3. Subject: "Your project is waiting for someone." Body: 2-line personalized note + 1-click invite link pre-populated. Expected: +8% invite completion from this cohort.

---

## Success Metrics

- **PQL accuracy:** At least 70% of users scoring 80+ on the PQL model should convert to paid within 30 days of reaching that score
- **Activation lift:** Activation rate (users reaching aha moment) improves by ≥8pp within 60 days of implementing top activation fix
- **Conversion velocity:** Median time-to-convert reduces by ≥15% within 90 days
- **Sales efficiency:** SDR outreach to PLG-sourced PQL closes at ≥25% (vs. cold outbound baseline of 2–4%)
- **Expansion detection:** Expansion trigger cluster identifies 80%+ of accounts that expand within 90 days
- **Churn prediction accuracy:** Churn model flags accounts that cancel with ≥65% precision at 30-day lead time
- **NRR improvement:** PLG-sourced customer NRR improves by ≥10pp within 2 quarters of implementing expansion motion

## Related Prompts

- [PLG New User Onboarding Orchestration](../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/AI-Powered-B2B-SaaS-PLG-New-User-Onboarding-Orchestration-&-Aha-Moment-Acceleration-Revenue-Intelligence-Engine.md)
- [PLG In-App Behavioral Activation](../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/AI-Powered-B2B-SaaS-PLG-In-App-Behavioral-Activation-&-Product-Usage-Triggered-Revenue-Campaign-Intelligence-Engine.md)
- [Product-Led Sales Motion Architecture](../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/AI-Powered-B2B-SaaS-Product-Led-Sales-PLS-Motion-Architecture-&-Product-Signal-to-Revenue-Sales-Assist-Intelligence-Engine.md)
- [Customer Health Score & Revenue Protection](../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/AI-Powered-Customer-Health-Score-&-Proactive-Revenue-Protection-Intelligence-Engine.md)

## Integration Tips

- **Amplitude / Mixpanel:** Export a user property table showing event counts per user for your top 10 core events over the last 30 days → paste as CSV context into the Advanced prompt. Add a "converted" boolean field to enable correlation analysis directly in Claude.
- **Segment (CDP):** Create a computed trait "PQL Score" using Segment's Computed Traits feature, feeding in the weighted event logic from the PQL scoring model above. Push this trait to HubSpot as a Contact Property for SDR routing.
- **HubSpot / Salesforce:** Build a "PLG Source" field and set it via Segment or Zapier when a user's PQL score crosses 60. Create a HubSpot workflow that auto-creates a Deal when PQL score hits 80+, assigns to SDR queue, and populates deal description with the user's top behavioral signals.
- **Stripe / Chargebee:** Merge billing event timestamps (trial-start, upgrade, plan-change, cancellation) with your product analytics events to build the conversion half-life curve. Request this as a SQL join if your data team has a warehouse (Snowflake/BigQuery).
- **Intercom / Appcues:** Trigger the "teammate invite" modal (from Example Output) using Intercom's product tours, fired on the event "first_project_created" with a 30-second delay. Use Appcues for more complex multi-step onboarding checklists.
- **Notion / Google Sheets:** The PQL scoring rubric outputs as a clean table. Paste directly into a Notion database with a "PQL Tier" formula field, or import into Google Sheets as your weekly PLG dashboard template.
- **Slack:** Set up a Zapier or Make automation that posts to #growth-alerts whenever a company with 50+ employees hits PQL score ≥80. Include the user's name, company, top 3 behaviors, and a "View in HubSpot" link. This makes the PLG signal actionable within minutes.

## Troubleshooting

**Problem: "We don't have clean product event data — our analytics is sparse and inconsistent."**
Solution: Start with the 5 events that matter most for the PQL model, not all events. Use the Quick Copy-Paste prompt with just those 5 behaviors. Instrument them properly in Segment or your product tool this sprint. In the meantime, approximate the PQL score using: login frequency (from auth logs) + plan page visits (from your website analytics) + email engagement (from your ESP). This proxy model is 60–70% as accurate as a full behavioral model and can be live in days, not months.

**Problem: "Our conversion rate looks fine at 12%, but we feel like we're leaving money on the table."**
Solution: Aggregate conversion rates hide massive segment variation. Break conversion into cohorts by: (a) signup source, (b) whether teammate was invited Y/N, (c) time-to-first-value bucket (<3 days / 3–7 days / 7+ days). You will almost certainly find one segment converting at 40%+ and another at 3%. The 40% segment is your repeatable playbook — double down on acquiring more users who look like them. Run the Advanced prompt's Section 4 segmentation matrix to surface this.

**Problem: "Sales doesn't trust the PQL score — they think it misses real buyers and surfaces low-quality leads."**
Solution: This is a calibration problem, not a data problem. Run a 30-day retrospective: pull all accounts that converted in the last quarter and calculate their retrospective PQL score at the moment a rep reached out. If most converters were scoring below 60 when sales touched them, your model is missing key signals or your ICP signals need reweighting. Have one SDR shadow the scoring for 2 weeks and flag misses with specific behavioral notes — use those notes to add missing signals to the model. PLG scoring models should be treated as living models, not one-time builds.

## Version History
- v1.0: Initial creation (auto-generated)
