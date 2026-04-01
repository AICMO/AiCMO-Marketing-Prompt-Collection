# AI-Powered North Star Metric Framework & Growth Accounting Intelligence Engine - Define the Single Metric That Predicts Sustainable Product Growth

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** north-star-metric, growth-accounting, product-analytics, plg, saas, retention, activation, growth-rate, mixpanel, amplitude, posthog, engagement, product-led-growth, kpi-framework

## Overview
Guides you through selecting the scientifically correct North Star Metric for your product, building the full input metric tree that drives it, and implementing growth accounting (new + retained + resurrected vs. churned) so marketing can run experiments that move the one number that actually predicts long-term revenue. Use this when your team is measuring everything but can't agree on what matters most, when growth looks fine in dashboards but revenue is stalling, or when you need to align marketing, product, and sales around a single shared growth objective.

## Quick Copy-Paste Version

You are a senior product growth strategist with deep expertise in North Star Metric design and growth accounting for B2B and B2C SaaS companies. Help me define the right North Star Metric for my product and build a complete measurement framework around it.

My product context:
- Product name and description: [what your product does — e.g., "AI contract review platform for legal teams at mid-market SaaS companies"]
- Primary customer: [job title + company type — e.g., "VP Legal at 200-2000 employee SaaS companies"]
- Core value delivered: [the transformation your product creates — e.g., "reduces contract review time from 4 hours to 20 minutes with AI redlining"]
- Business model: [Freemium / Paid trial / SLG / PLG / Usage-based / Subscription]
- Current growth motion: [describe: how do users sign up, activate, and expand?]
- Current metrics we track: [list 5-10 metrics you currently report on]
- Biggest growth problem right now: [e.g., "signups are growing but revenue is flat" / "retention is unknown" / "we have no idea what actions predict long-term customer value"]
- Analytics tools: [Amplitude / Mixpanel / PostHog / Heap / Segment / other]

Deliver:
1. **North Star Metric Recommendation** — Select the single metric that best captures the core value delivered to customers at scale. Explain why this metric (not revenue, not signups, not DAU) is the right NSM for my specific product. Include the formula, measurement frequency, and expected long-term range as the business scales.
2. **NSM Disqualification Analysis** — List 3 metrics I'm likely already tracking that feel like they could be the NSM but are actually lagging indicators or vanity metrics. Explain why each fails the NSM test (value delivery, breadth, leading indicator, actionability).
3. **Input Metric Tree** — Define the 6-8 upstream metrics that directly cause the NSM to move. For each input metric: formula, current industry benchmark, and which team owns it (Marketing / Product / CS / Sales).
4. **Growth Accounting Model** — Define the growth accounting formula for my product: New [unit] + Retained [unit] + Resurrected [unit] − Churned [unit] = Net NSM Change. Set target Quick Ratio (new+resurrected / churned) for my stage.
5. **NSM Diagnostic** — If my NSM is growing but revenue is flat (or vice versa), list 5 possible root causes and how to diagnose each.
6. **90-Day Experiment Roadmap** — Design 4 experiments tied directly to input metrics, ranked by expected NSM impact. Include hypothesis, test design, success threshold, and rollout plan.
7. **Weekly NSM Review Template** — Create a 15-minute weekly metrics review agenda for cross-functional team (Marketing, Product, CS) focused exclusively on NSM and its input metrics.

Use specific SaaS benchmarks. Avoid vague recommendations — every metric should have a formula and a target range.

## Advanced Customizable Version

**ROLE:** You are a Head of Growth Analytics at a Series B-D B2B SaaS company who has built NSM frameworks at companies that grew from $1M to $50M ARR. You have studied the original Facebook "Growth Accounting" methodology developed by Alex Schultz, the Amplitude NSM playbook, and Reforge's growth model curricula. You think in systems: you understand that vanity metrics (total signups, total users) hide the structural dynamics of growth, and that the right NSM collapses complexity into one signal that predicts whether the business is building durable value or borrowing from future retention. You are allergic to dashboard theater. You output clear, actionable, technically precise frameworks.

**COMPANY CONTEXT:**
- Company name: [Company Name]
- Product category: [e.g., revenue intelligence, data pipeline, HR workflow automation, developer tooling, fintech compliance]
- Stage: [Seed / Series A / Series B / Series C / Growth]
- ARR: [$X]
- Monthly active users (MAU): [X]
- Primary GTM motion: [PLG / SLG / Hybrid PLG-SLG / Usage-based]
- ICP: [job title, company size, industry]
- Primary value exchange: [describe the exact transformation your product delivers to a user in a single session — be specific, not generic]
- Analytics stack: [e.g., PostHog + Segment + Customer.io + Salesforce + Looker]
- Current "North Star" candidate (if you have one): [describe or "none"]
- Key frustration with current measurement: [e.g., "MQLs are growing but pipeline isn't converting" / "DAU is flat but NPS is 72" / "free users activate but don't retain"]

**CURRENT METRICS AUDIT:**
List the top 10 metrics your team currently reports in weekly/monthly reviews:
| Metric | Formula | Frequency | Owner | Decision it drives |
|---|---|---|---|---|
| [Metric 1] | [formula] | [weekly/monthly] | [team] | [what action does this number inform?] |
[Continue for 10 metrics...]

**PRODUCT BEHAVIOR DATA (fill in what's known):**
| Behavioral Category | Current Rate | Benchmark | Notes |
|---|---|---|---|
| Day 1 Activation Rate | [X%] | 30-50% | |
| Day 7 Retention Rate | [X%] | 20-35% | |
| Day 30 Retention Rate | [X%] | 10-25% | |
| Weekly Active Rate (WAU/MAU) | [X%] | 15-25% (SaaS avg) | |
| Feature Breadth (avg features used/user) | [X] | varies | |
| Viral/Referral Coefficient | [X] | 0.1-0.5 for B2B | |
| NPS / CSAT | [score] | NPS 40-60 good | |

**CURRENT GROWTH MODEL (fill in what's known):**
| Growth Component | Monthly Volume | Definition |
|---|---|---|
| New Users/Accounts | [X] | First active in the period |
| Retained Users/Accounts | [X] | Active last period AND this period |
| Resurrected Users/Accounts | [X] | Inactive last period, active this period |
| Churned Users/Accounts | [X] | Active last period, NOT active this period |
| **Quick Ratio** (new+resurrected / churned) | [X] | >2 = healthy growth |

**NSM SELECTION CRITERIA:**
Apply the following 5-filter test to candidate metrics:

1. **Value Delivery Test**: Does this metric increase when a user receives core product value? (not when they sign up, log in, or complete onboarding — when they actually accomplish the job they hired the product for)
2. **Breadth Test**: Does this metric capture value delivered across a meaningful breadth of users, not just power users?
3. **Leading Indicator Test**: Does this metric lead revenue by 30-90 days? If revenue goes flat, will this metric warn you first?
4. **Actionability Test**: Can product, marketing, and CS each take actions that directly move this metric within a sprint?
5. **Anti-Gaming Test**: Would optimizing this metric lead to behavior that actually helps users — or could it be gamed by optimizing for surface engagement without delivering value?

**DELIVERABLES:**

**Section 1: North Star Metric Definition**
Deliver a complete NSM specification:
- **Metric Name:** [e.g., "Weekly Teams Delivering Contracts"]
- **Formula:** [exact calculation — numerator, denominator, filters, edge cases]
- **Measurement unit:** [users / accounts / events / value-units]
- **Frequency:** [daily / weekly / monthly — and why]
- **Current baseline:** [calculate from available data or set as Day 0 baseline]
- **12-month target:** [X to Y — based on growth stage benchmarks]
- **Why this metric and not [alternative]:** [kill 3 alternative candidates with rigorous reasoning]
- **NSM failure mode:** [how could this metric grow while the business deteriorates? What's the safeguard?]

**Section 2: Complete Input Metric Tree**
Map the full causal chain from user behavior → NSM movement. Structure:

NSM: [Your North Star Metric]
│
├── Acquisition Inputs (drive New component)
│   ├── [Input Metric 1A]: formula, owner, benchmark, 90-day target
│   └── [Input Metric 1B]: formula, owner, benchmark, 90-day target
│
├── Activation Inputs (drive Retained component)
│   ├── [Input Metric 2A]: formula, owner, benchmark, 90-day target
│   └── [Input Metric 2B]: formula, owner, benchmark, 90-day target
│
├── Retention Inputs (reduce Churned component)
│   ├── [Input Metric 3A]: formula, owner, benchmark, 90-day target
│   └── [Input Metric 3B]: formula, owner, benchmark, 90-day target
│
└── Expansion Inputs (drive Resurrected + depth)
    ├── [Input Metric 4A]: formula, owner, benchmark, 90-day target
    └── [Input Metric 4B]: formula, owner, benchmark, 90-day target

For each input metric: explain the causal mechanism (why does improving this metric directly increase the NSM?), identify the team responsible, and recommend a specific intervention to move it by 10%+ in the next sprint.

**Section 3: Growth Accounting Model**
Build the complete growth accounting framework:
- Define "active" precisely for your product (not generic — what specific behavior in what time window constitutes being "active"? e.g., "an account is active if ≥1 user performed a core value action within the past 7 days")
- Weekly/monthly growth accounting table template with all four components
- Quick Ratio target by stage: Seed ≥1.5, Series A ≥2.0, Series B+ ≥2.5. Current gap analysis
- Resurrection rate analysis: what % of churned users can be recovered, and what triggers them to return
- Churn root cause taxonomy: categorize churn into 4-6 buckets (e.g., value not realized, competitor displacement, budget cut, champion left) with recommended marketing intervention for each

**Section 4: NSM Diagnostic Playbook**
When the NSM diverges from expectations, use this diagnosis tree:

| Symptom | Likely Root Cause | Diagnostic Query | Intervention |
|---|---|---|---|
| NSM growing but revenue flat | Activation without conversion | Cohort: activated users → paid conversion rate by month | Improve PQL triggers and sales handoff |
| Revenue growing but NSM flat | Land-and-expand bias, power users drive $$ not breadth | Segment NSM by ARR quartile | Rebalance onboarding for mid-tier accounts |
| NSM volatile week-to-week | Wrong time window for "active" definition | Test 7-day vs. 14-day vs. 30-day activity windows | Recalibrate activity definition |
| NSM growing, NPS declining | Wrong metric chosen — gaming the NSM | Survey churned users who were NSM-positive | NSM redesign with value delivery re-anchoring |
| Quick Ratio <1.0 | Churn exceeding new growth | Cohort decay curve analysis | Emergency: retention intervention before acquisition scale-up |

**Section 5: Experimentation Framework**
Design 6 experiments to move the NSM over 2 quarters:

| # | Hypothesis | Input Metric Targeted | Test Design | Duration | Success Threshold | NSM Impact Estimate |
|---|---|---|---|---|---|---|
| 1 | [Specific "if we do X, Y will increase by Z%" format] | [input metric] | [A/B or multivariate, sample size, control] | [days] | [+X% in input metric] | [+Y% NSM] |
[Continue for 6 experiments...]

Prioritization criteria: effort × expected NSM impact × confidence. Rank experiments by this score.

**Section 6: NSM Reporting Infrastructure**
- Dashboard specification: 6 charts that every team should see in their NSM review
- Alert thresholds: at what NSM change (week-over-week %, not absolute) should an investigation be triggered?
- Recommended analytics implementation (Amplitude/Mixpanel/PostHog event taxonomy) to correctly capture NSM components
- Cross-functional review cadence: who reviews what, how often, and what decision rights each team has over NSM-related experiments

**OUTPUT REQUIREMENTS:**
- All metric targets must reference a specific industry benchmark (cite the source framework: Reforge, Amplitude, Sequoia, a16z, or specific public company benchmarks)
- Every input metric must include a "what breaks this metric" failure mode analysis
- Distinguish between NSM health (value delivery) and NSM growth rate (velocity) — both need separate diagnostic frameworks
- Provide a "metric graduation path": how the NSM should evolve as the company grows from seed to IPO-scale (most companies need to redesign their NSM at Series B and again at Series C)

## Example Input/Output

**Input (example company):**
- Company: Flowline — B2B workflow automation platform, Series A, $4.8M ARR
- ICP: RevOps and Sales Ops managers at 150-500 person SaaS companies
- Core value: eliminates manual handoff tasks between CRM, billing, and ticketing systems — users build "flows" (automated sequences) that run without human intervention
- Motion: PLG + sales-assisted; free tier includes 5 active flows; paid includes unlimited flows + team collaboration
- Current metrics tracked: total signups, MRR, DAU, trial-to-paid conversion rate, NPS
- Problem: "MRR is growing 8% MoM but we can't tell if it's from new logos or existing account expansion, and DAU feels noisy because some users just log in to check status without building anything"
- Analytics: Mixpanel + Segment + HubSpot

**Output excerpt — NSM Definition:**

**North Star Metric: Weekly Accounts with ≥1 Active Flow Running**

**Formula:** Count of unique account IDs where at least 1 flow triggered ≥1 successful execution in the rolling 7-day window. "Successful execution" = all steps completed without error and the downstream system (CRM/billing/ticketing) confirmed receipt.

**Why this metric:**
Flowline's core value is *work that happens without you*. A flow that runs is the product delivering its promise. Signups measure intent; DAU measures presence; this metric measures actual value delivery. When this number grows, it means more teams are automating real work — which is the behavior that creates retention, expansion, and word-of-mouth.

**Why not DAU:** 35% of Flowline's daily active users log in to view execution logs or adjust settings — no new value delivered. DAU inflates with success theater, not value delivery.

**Why not MRR:** Revenue lags value delivery by 30-90 days (trial periods, billing cycles). When this NSM drops, MRR will drop 6-8 weeks later — not in time to intervene.

**Why not Total Flows Created:** Flows can be created and never run. "Abandoned flow" creation is a common behavior — users build but don't deploy. Only running flows = value delivered.

**12-month target:** From ~120 active-flow accounts (estimated baseline) to 400 accounts by month 12, implying 3.3x growth consistent with Series A PLG benchmarks (Reforge Growth Series: healthy PLG at Series A = 3-4x NSM growth in 12 months).

---

**Growth Accounting Model Output (Flowline example):**

"Active account" definition: An account had ≥1 flow execute successfully in the past 7 days.

| Component | April | May | June |
|---|---|---|---|
| New Active Accounts | 18 | 22 | 19 |
| Retained Active Accounts | 94 | 101 | 108 |
| Resurrected Accounts | 4 | 6 | 5 |
| Churned Active Accounts | 9 | 8 | 11 |
| **Net NSM Change** | **+13** | **+21** | **+13** |
| **Quick Ratio** | **2.4** | **3.5** | **2.2** |

**Diagnosis:** Quick Ratio averaging 2.7 — healthy for Series A. Key risk: June churn spike to 11. Cohort analysis reveals churned accounts in June were primarily accounts that created flows in February (week 14-16 cohort) — a specific cohort with higher-than-average setup complexity. Root cause: API authentication errors in that cohort's most common integration (Salesforce → Zendesk). Product fix shipped July 3 — expect churn to normalize in July accounting.

**Highest-leverage experiment identified:** 61% of new accounts take ≥5 days to deploy their first running flow. Accounts that run their first flow within 48 hours of signup show 3.1x better 90-day retention. Experiment: "Fast Lane Onboarding" — dedicated in-app wizard for the top 3 most common flow templates (CRM-to-billing, lead routing, ticket escalation). Hypothesis: reducing time-to-first-running-flow from 5.2 days to <48 hours will increase new-account retention from 71% to 85%, contributing +8 retained accounts/month to the NSM.

## Success Metrics

**Your NSM framework is working if:**
- The entire cross-functional team (Marketing, Product, CS, Sales) can state the NSM without looking it up — alignment test
- NSM Quick Ratio ≥ 2.0 sustained for ≥3 consecutive months at Series A stage
- NSM predicts MRR changes with a 6-8 week lag correlation of r² ≥ 0.70
- At least 3 input metrics have moved measurably within 60 days of framework adoption
- Experimentation velocity increases: from ad-hoc to ≥2 NSM-targeted experiments running concurrently at all times
- NSM review meetings generate prioritized action items within the 15-minute window — if they don't, the input metric tree needs refinement

**Leading indicators the framework is being adopted:**
- Product team references NSM impact in sprint planning and feature prioritization
- Marketing measures campaign ROI in terms of NSM impact, not just MQLs generated
- CS team has account health score anchored to account-level NSM contribution

**Warning signs the wrong NSM was chosen:**
- NSM grows steadily but churn is also accelerating (gaming vs. value delivery)
- NSM is only moving for the top 20% of accounts by ARR (breadth failure)
- Teams argue constantly about whether the NSM moved "because of us" (causality ambiguity — the NSM formula needs tightening)

## Related Prompts

- [`./Feature-Adoption-Stickiness-&-Retention-Intelligence-Engine.md`](./Feature-Adoption-Stickiness-&-Retention-Intelligence-Engine.md) — use to identify which feature adoption patterns feed the Retained component of your growth accounting model
- [`./PLG-Revenue-Conversion-Analytics-&-Product-Qualified-Revenue-Intelligence-Engine.md`](./PLG-Revenue-Conversion-Analytics-&-Product-Qualified-Revenue-Intelligence-Engine.md) — use to connect NSM-positive users to PQL scoring and revenue conversion
- [`../../01_CMO-&-Leadership/Strategy-&-Planning/AI-Powered-Product-Led-Growth-Strategy-&-Self-Serve-Revenue-Intelligence-Engine.md`](../../01_CMO-&-Leadership/Strategy-&-Planning/AI-Powered-Product-Led-Growth-Strategy-&-Self-Serve-Revenue-Intelligence-Engine.md) — use to align NSM with your overall PLG strategy and self-serve revenue motion
- [`../Funnel-Conversion-&-Pipeline-Velocity/Marketing-Funnel-Conversion-&-Pipeline-Velocity-Intelligence-Engine.md`](../Funnel-Conversion-&-Pipeline-Velocity/Marketing-Funnel-Conversion-&-Pipeline-Velocity-Intelligence-Engine.md) — use to connect NSM growth accounting to full-funnel conversion metrics and pipeline velocity

## Integration Tips

**Amplitude — NSM Dashboard Setup:**
- Create a "North Star Metric" chart as a user-based or account-based Retention Analysis
- Use the "Active Users" chart type with custom active event definition (your specific value-delivery event, not just session start)
- Set up weekly cohort analysis view showing New / Retained / Resurrected / Churned breakdowns natively in Amplitude's retention feature
- Configure Amplitude Insights alert: notify Slack channel `#nsm-alerts` when week-over-week NSM change exceeds ±15%

**Mixpanel — Growth Accounting Implementation:**
- Build a custom Mixpanel report using "User Flows" filtered to your value-delivery event
- Create a saved cohort: "NSM Active Last 7 Days" using a recurring event filter
- Use Mixpanel's "Retention" report with "First Touch" set to your activation event and "Return Event" set to your NSM event — this gives you the exact retention curve by activation cohort
- Export weekly cohort data via Mixpanel API to Google Sheets for growth accounting calculations if native breakdown is insufficient

**PostHog — Lightweight NSM Tracking:**
- Define your NSM event as a PostHog "Action" with specific event + property filters (not a raw event)
- Build a PostHog Insight using "Trends" with the NSM action, grouped by week, filtered to accounts (not individual users) where possible
- Use PostHog's "Retention" feature with your NSM action as both the "Starting Action" (first value delivery) and "Returning Action" (repeated value delivery) — this surfaces the activation-to-habit retention curve

**Looker / Metabase — NSM Executive Dashboard (6 required views):**
1. **NSM Trend** — weekly NSM value, 13-week rolling, with ±1 standard deviation band
2. **Growth Accounting Waterfall** — stacked bar: New + Retained + Resurrected − Churned = Net Change (weekly)
3. **Quick Ratio Trend** — line chart with ≥2.0 target line; color-coded: green ≥2.0, yellow 1.5-2.0, red <1.5
4. **Input Metric Scorecard** — table of all 6-8 input metrics vs. targets, RAG-status colored
5. **NSM by Cohort** — heatmap: signup cohort (rows) × weeks since signup (columns) × NSM participation rate (color)
6. **NSM → Revenue Lag Correlation** — dual-axis: NSM (left), MRR 8 weeks later (right) — demonstrates the leading-indicator relationship to the board

**Zapier/Make.com Automation:**
- Weekly trigger: every Monday at 8am → pull NSM data from analytics API → calculate Quick Ratio → post formatted growth accounting summary to `#growth-weekly` Slack channel with ↑↓ indicators
- Alert trigger: NSM drops >10% week-over-week → create Linear/Jira investigation ticket + page growth lead via PagerDuty
- Monthly trigger: calculate NSM cohort data → auto-populate Google Sheets growth accounting model → generate PDF via Google Slides API → email to leadership team

## Troubleshooting

**Problem: Team can't agree on the NSM — debates drag on for weeks without resolution**
*Fix:* The disagreement is almost always a proxy war about team priorities, not a genuine analytical debate. Run the 5-filter NSM test explicitly with the whole team in a 90-minute workshop. Score each candidate metric (1-5) against: Value Delivery, Breadth, Leading Indicator quality, Actionability, and Anti-Gaming robustness. The metric with the highest composite score wins — or reveals why no current candidate passes and you need to instrument a new event. If debate continues after the scoring exercise, the underlying problem is lack of clarity on your product's core value proposition. Fix that first (see `../../02_Product-Marketing/Positioning-&-Messaging/Value-Proposition-Canvas.md`).

**Problem: NSM is growing but team doesn't trust it — "feels like the wrong metric"**
*Fix:* Run a validation test: segment your top-quartile NSM performers (accounts with highest NSM activity) and compare them to bottom-quartile performers on: 12-month retention rate, NPS, expansion ARR, support ticket volume. If top-NSM accounts are dramatically better on all these dimensions, the metric is valid and the team's distrust is emotional, not analytical. If top-NSM accounts are NOT better on retention and NPS, the NSM is measuring noise (surface engagement, not value delivery) and needs to be redesigned with the value delivery test as the primary filter.

**Problem: Growth accounting shows Quick Ratio >2 but the CEO says growth doesn't feel fast enough**
*Fix:* Quick Ratio and absolute growth rate are different problems. A Quick Ratio of 2.5 with only 8 churned accounts means you have 20 new accounts — that's mathematically healthy but slow in absolute terms. The bottleneck is top-of-funnel, not retention. Shift experiments from the Retained/Resurrected components of growth accounting to the New component: increase acquisition investment, improve time-to-value to raise activation rates, or expand ICP. Show the CEO the growth accounting waterfall with absolute numbers, not just ratios, so the bottleneck is visually obvious.

## Version History
- v1.0: Initial creation (auto-generated)
