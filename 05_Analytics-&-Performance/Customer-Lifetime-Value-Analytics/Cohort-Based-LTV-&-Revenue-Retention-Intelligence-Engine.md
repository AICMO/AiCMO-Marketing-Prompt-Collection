# Cohort-Based LTV & Revenue Retention Intelligence Engine - Unlock the True Value of Every Customer Cohort

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** ltv, cohort-analysis, retention, revenue-intelligence, b2b-saas, subscription, unit-economics, churn, expansion-revenue

## Overview

Analyzes customer cohort data to reveal how lifetime value, retention curves, and expansion revenue evolve over time — segmented by acquisition channel, plan tier, geography, or any other dimension. Use this when you need to understand which cohorts are your best customers, where LTV is degrading, and what drives durable revenue retention versus fast churn.

## Quick Copy-Paste Version

You are a senior SaaS revenue analytics expert. Analyze the following customer cohort data and produce a complete LTV and retention intelligence report.

COHORT DATA:
[Paste your cohort table — rows = cohort month, columns = Month 0, 1, 2, 3, 6, 12, 18, 24 retention % or revenue. Include ARR, customer count, and any segmentation available.]

CONTEXT:
- Product: [Your SaaS product name and category]
- ACV/ARPU: [Average contract value or revenue per user]
- Billing: [Monthly/Annual]
- Segments available: [e.g., SMB vs Enterprise, channel, plan tier]

DELIVER:

1. RETENTION CURVE ANALYSIS
   - Plot and interpret the retention curve shape (fast-decay, slow-decay, flattening, resurrection)
   - Identify the "critical window" — the month range with the steepest drop
   - Compare cohort-over-cohort trend: are newer cohorts retaining better or worse?

2. LTV BY COHORT SEGMENT
   - Calculate realized LTV at Month 12 and projected LTV at Month 24/36 using a retention-extrapolation model
   - Rank cohorts by LTV: which acquisition months produced your best customers?
   - If segmentation data exists, show LTV delta between segments (e.g., Enterprise vs SMB, Paid vs Organic)

3. EXPANSION REVENUE ANALYSIS
   - Calculate Net Revenue Retention (NRR) for each cohort
   - Identify cohorts with NRR > 100% (expansion outpacing churn) vs cohorts in revenue decline
   - Pinpoint which cohort vintage crossed the NRR breakeven and what changed

4. CHURN PATTERN DIAGNOSIS
   - Classify churn type: early (Month 0-3), mid-lifecycle (Month 4-12), late (Month 13+)
   - Surface any "cliff" events — sudden drops that suggest product, pricing, or market-fit issues
   - Correlate churn timing with product lifecycle events if data allows

5. ACTIONABLE RECOMMENDATIONS
   - 3 specific interventions to improve retention in the critical window
   - 2 expansion revenue plays for cohorts showing high engagement signals
   - 1 acquisition channel shift recommendation based on cohort LTV differences
   - Prioritized by revenue impact (quantify the uplift for each recommendation)

6. INVESTOR-GRADE METRICS SUMMARY
   - LTV:CAC ratio by cohort (if CAC data provided)
   - CAC payback period trend (improving or degrading?)
   - Projected 36-month cumulative revenue per cohort
   - Quick-ratio implication (is growth efficient or leaky?)

Format output as an executive summary first (5 bullet points), then detailed sections. Include a data table for each major metric.

## Advanced Customizable Version

ROLE: You are a revenue intelligence analyst specializing in subscription business cohort economics. You combine the rigor of a quant analyst with the business judgment of a CFO advisor. You have deep expertise in SaaS metrics, retention modeling, and expansion revenue optimization.

BUSINESS CONTEXT:
- Company: [Company name]
- Stage: [Seed/Series A/Series B/Growth/Public]
- Product category: [e.g., marketing automation, DevOps tooling, HR software]
- GTM motion: [PLG / Sales-led / Hybrid]
- Primary buyer: [SMB / Mid-Market / Enterprise]
- Current ARR: [$X]
- Current NRR: [X%]
- Primary growth challenge: [e.g., high early churn, stagnant expansion, declining new logo LTV]

COHORT DATA INPUT:
[Provide one or more of the following:]
A) Raw cohort retention table (customers or revenue): rows = cohort month (Jan 2023, Feb 2023...), columns = Month 0, 1, 3, 6, 12, 18, 24 survival rates
B) MRR cohort table: same structure but with dollar amounts per cohort per month
C) Segment-split cohort data: same cohort table duplicated for each segment (channel, plan, geo, industry)

OPTIONAL ENRICHMENT DATA:
- CAC by acquisition channel and cohort quarter: [data]
- Feature adoption flags by cohort (e.g., % using feature X by Month 3): [data]
- Support ticket volume by cohort month: [data]
- NPS or CSAT scores by cohort age: [data]

ANALYSIS FRAMEWORK — apply all relevant sections:

**SECTION 1: RETENTION CURVE MODELING**
Objective: Understand the fundamental retention shape and trajectory

1.1 Retention Curve Classification
    - Apply the Power Law retention model to identify if your curve follows: 
      * Fast decay (consumer-style, steep Month 0-3 dropoff then plateau)
      * S-curve (slow start, acceleration, plateau — typical enterprise)
      * Resurrection pattern (lapsed cohort reactivation spike)
      * Healthy SaaS (Month 12+ retention > 80% for SMB, > 90% for Enterprise)
    - Benchmark against industry standards:
      * Best-in-class SMB SaaS: Month 12 retention > 75%
      * Best-in-class Enterprise SaaS: Month 12 retention > 90%
      * Median SaaS: Month 12 retention 60-70%

1.2 Critical Window Identification
    - Calculate month-over-month retention delta for each cohort
    - Identify the "danger zone" (months with >10% MoM retention drop)
    - Flag any "cliff" events (>15% single-month drop across multiple cohorts — suggests systemic issue)

1.3 Cohort-Over-Cohort Trend
    - Compare Month 3, 6, and 12 retention rates across cohort vintages
    - Apply a linear regression to identify if retention is improving, stable, or degrading over time
    - Highlight breakpoint cohorts — vintages that significantly outperform or underperform neighbors

**SECTION 2: LTV COMPUTATION AND PROJECTION**
Objective: Calculate true and projected lifetime value with uncertainty bounds

2.1 Realized LTV (Observed)
    Method: Sum of monthly revenue per customer from Month 0 through the latest observed month
    Formula: Realized LTV₁₂ = Σ(ARPU × Retention Rate at Month t) for t=0 to 12
    Apply for: Month 6, 12, 18, 24 realized LTV per cohort

2.2 Projected LTV (Forward-Looking)
    Method: Fit retention curve to a modified exponential decay model, project forward
    Conservative scenario: Current retention rate trend continues
    Base scenario: Retention stabilizes at Month 12 level
    Optimistic scenario: 10% retention improvement from planned interventions
    Output: LTV range at Month 36 with confidence intervals

2.3 LTV Segmentation Analysis (if segment data provided)
    - Calculate LTV index for each segment (segment LTV / blended LTV)
    - Rank segments by: highest LTV, fastest LTV accumulation, strongest NRR
    - Identify the "ideal customer profile" based on LTV data, not just deal size

**SECTION 3: NET REVENUE RETENTION DEEP DIVE**
Objective: Decompose NRR into its causal components

3.1 NRR Waterfall Decomposition
    For each cohort, calculate:
    - Starting MRR (Month 0)
    - Contraction MRR (downgrades, plan reductions)
    - Churn MRR (full cancellations)
    - Expansion MRR (upsells, seat additions, usage growth)
    - Ending MRR = Starting - Contraction - Churn + Expansion
    - NRR = Ending MRR / Starting MRR × 100

3.2 NRR Trend and Inflection Points
    - Plot NRR by cohort vintage to identify improvement/degradation trend
    - Find the "NRR inflection cohort" — the vintage where NRR crossed 100%
    - Correlate with: pricing changes, product launches, GTM motion changes, market conditions

3.3 Expansion Revenue Engine Analysis
    - Calculate time-to-first-expansion for each cohort (median months to first upsell)
    - Identify the "expansion trigger window" — the month range where most expansion occurs
    - Calculate expansion velocity: average MRR expansion per surviving customer per month

**SECTION 4: CHURN CAUSAL ANALYSIS**
Objective: Diagnose root cause and timing of churn patterns

4.1 Churn Timing Classification
    Apply the Three Buckets framework:
    - Early churn (Month 0-3): Onboarding failure, poor fit, wrong buyer — acquisition problem
    - Mid-lifecycle churn (Month 4-12): Value realization gap, competitive loss, champion departure
    - Late churn (Month 13+): Budget cuts, consolidation, product roadmap misalignment

4.2 Cohort Anomaly Detection
    - Flag cohorts with churn rates > 1.5 standard deviations above mean
    - Cross-reference anomaly timing with known events (pricing changes, product outages, competitor launches)
    - Recommend investigation priority: which anomalies have largest revenue impact

4.3 Feature Adoption Correlation (if data provided)
    - Calculate Pearson correlation between Month 3 feature adoption rate and Month 12 retention
    - Identify "sticky features" — adoption of which features most strongly predicts retention
    - Calculate the "activation threshold" — minimum feature engagement level that correlates with >80% Month 12 retention

**SECTION 5: STRATEGIC RECOMMENDATIONS**
Objective: Convert analytics into prioritized, revenue-quantified action

5.1 Retention Intervention Playbook
    For each recommendation, provide:
    - The intervention (specific, actionable, AI-automatable)
    - Target cohort segment
    - Expected retention lift (%)
    - Projected incremental ARR impact
    - Implementation complexity (Low/Medium/High)
    - Leading indicator to track within 30 days

5.2 Expansion Revenue Acceleration Plays
    - Identify the highest-expansion-potential customer segments
    - Design 2-3 specific expansion triggers (usage thresholds, behavior signals, lifecycle milestones)
    - Recommend pricing/packaging changes to unlock natural expansion paths
    - Calculate incremental NRR uplift if expansion velocity improves by 20%

5.3 Acquisition Channel Reallocation
    - Rank acquisition channels by cohort LTV (not just volume or initial conversion)
    - Calculate LTV:CAC efficiency by channel
    - Recommend budget reallocation: shift X% from lowest-LTV channel to highest-LTV channel
    - Project revenue impact of reallocation over 12 months

**SECTION 6: BOARD-READY METRICS PACKAGE**
- Magic Number and Quick Ratio trend
- Rule of 40 implication from LTV/NRR data
- LTV:CAC ratio by cohort quarter (with payback period)
- Projected ARR from existing customer base alone (NRR-driven growth floor)
- Cohort revenue concentration risk (% of ARR from top 3 cohort vintages)

OUTPUT FORMAT:
1. Executive Summary (5 bullets, board-presentation ready)
2. Key Findings Table (metric | current | benchmark | gap | priority)
3. Detailed section analyses with supporting data tables
4. Recommendation Scorecard (intervention | impact | effort | timeline)
5. 30/60/90-day action plan with owner assignments and success metrics

## Example Input/Output

**Example Company:** Fieldglass AI — B2B SaaS workforce management platform, $8M ARR, Series A, SMB and mid-market focus, monthly billing, current NRR 94%.

**Example Input Data (simplified cohort retention table):**

| Cohort | M0 | M1 | M3 | M6 | M12 |
|--------|----|----|----|----|-----|
| Jan 2024 | 100% | 82% | 71% | 65% | 58% |
| Feb 2024 | 100% | 84% | 74% | 68% | 61% |
| Mar 2024 | 100% | 88% | 79% | 74% | 67% |
| Apr 2024 | 100% | 86% | 78% | 73% | 66% |
| May 2024 | 100% | 91% | 83% | — | — |
| Jun 2024 | 100% | 89% | 81% | — | — |

**Example Output (excerpts):**

**Executive Summary:**
- Retention is meaningfully improving: Month 12 retention jumped from 58% (Jan cohort) to ~67% (Apr cohort), a 9-point improvement — likely driven by the March onboarding redesign
- The critical churn window is Month 0-1 (losing 12-18% of customers immediately), indicating an activation problem, not a value problem
- NRR at 94% is below the ~105% needed for capital-efficient growth; expansion revenue is the #1 lever to fix this
- Mar-Apr 2024 cohorts are outperforming by 6-9 points — investigate what changed in acquisition or onboarding during this period
- Projecting: if Month 12 retention stabilizes at 67%, blended LTV at 36 months is ~$18,400 per customer vs. current realized $11,200 — a 64% LTV upside exists if retention holds

**Critical Window Analysis:**
The steepest churn occurs in Month 0 → Month 1 (average 13% drop across all cohorts). This is classic early activation failure. Customers who survive Month 1 show dramatically better long-term retention (Month 1→12 survival: 71%), suggesting the product delivers real value — the problem is getting users to that value fast enough.

**NRR Decomposition (blended, trailing 6 months):**
| Component | MRR Impact |
|-----------|------------|
| Starting MRR (cohort average) | $1,200 |
| Churn MRR | -$72 (6.0%) |
| Contraction MRR | -$24 (2.0%) |
| Expansion MRR | +$24 (2.0%) |
| Net NRR | 94% |

**Top 3 Recommendations:**
1. **30-day activation campaign targeting Month 0-1 cohorts** — automated onboarding sequence triggered by low feature adoption score at Day 7. Expected: +5-8 point Month 1 retention improvement. Revenue impact: +$180K ARR within 12 months.
2. **Seat expansion trigger at 80% capacity utilization** — automated in-app prompt + CSM alert when teams hit seat limits. Expected: NRR +6 points (94% → 100%). Revenue impact: +$480K ARR.
3. **Reallocate 20% of paid social budget to referral/partner channel** — referral cohorts show Month 12 retention of 74% vs. paid social at 61%. Revenue impact: +$140K LTV per 100 new customers acquired.

## Success Metrics

**Analysis Quality Indicators:**
- Retention curve classification matches industry benchmarks for the business model
- LTV projections include both realized and forward-looking figures with scenario ranges
- NRR is decomposed (not just reported as a single number)
- Each recommendation includes quantified revenue impact, not just directional guidance
- At least one "surprising" insight that contradicts conventional wisdom or prior assumptions

**Operational Impact Targets (post-implementation):**
- Month 1 retention rate improves by 5+ points within 90 days of activation intervention
- NRR crosses 100% within 2 quarters of expansion motion launch
- LTV:CAC ratio improves to >3x within 12 months
- Board deck cohort slide requires zero manual editing — AI output is paste-ready

## Related Prompts

- `../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/Customer-Lifetime-Value-Prediction-&-Acquisition-Investment-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Funnel-Conversion-&-Pipeline-Velocity/Pipeline-Stage-Conversion-Optimization-&-Revenue-Leak-Detection-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/B2B-Content-Asset-Attribution-&-Pipeline-Influence-Intelligence-Engine.md`
- `../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/Net-Revenue-Retention-NRR-Forecasting-&-Cohort-Expansion-Intelligence-Engine.md`

## Integration Tips

**HubSpot:** Export contact/deal lifecycle stage dates → build cohort tables in Google Sheets using VLOOKUP on deal close date → paste into prompt. Use HubSpot's "Cohort Analysis" report as input data source.

**Stripe / Chargebee / Recurly:** Export MRR movements report (new, expansion, contraction, churn by month) → pivot by cohort in Google Sheets → feed into the Advanced Version's NRR Waterfall section. Stripe Sigma SQL: `SELECT cohort_month, month_number, SUM(mrr) FROM cohort_mrr GROUP BY 1,2`.

**Salesforce:** Use Revenue Intelligence or Tableau CRM to export cohort retention by opportunity source → enables channel-level LTV analysis in Section 2.3.

**Mixpanel / Amplitude / PostHog:** Export retention cohort reports (users still active at Day 7, 30, 90) → cross-reference with revenue cohorts to identify feature adoption drivers of retention in Section 4.3.

**Notion:** Paste the output's Recommendation Scorecard directly into a Notion database table → add "Owner," "Due Date," and "Status" properties → distribute to team as a living action plan.

**Zapier Automation:** Trigger: monthly Stripe webhook when new MRR data is available → Action: append row to Google Sheets cohort table → Action: send updated table to Claude API with this prompt → Action: post executive summary to Slack #revenue-intelligence channel.

## Troubleshooting

**Problem: Cohort table is incomplete — missing Month 12+ data for recent cohorts.**
Fix: Use the Advanced Version's "projected LTV" methodology — fit a retention curve to the available data points and extrapolate. Explicitly state in output: "Month 12+ data not yet available for [cohort vintages]; projections based on retention curve fit using Months 0-6." Flag uncertainty by providing a range rather than a point estimate.

**Problem: Output recommends generic interventions like "improve onboarding" without specifics.**
Fix: Add more context to the prompt input: paste in 2-3 example customer cancellation reasons, your current onboarding flow steps, and which features have the highest/lowest adoption. The more specific the input, the more surgical the recommendations. Also explicitly instruct: "Do not recommend any intervention that requires more than 2 weeks to implement or that requires manual outreach to more than 10% of the cohort."

**Problem: NRR and churn numbers don't reconcile with what finance reports.**
Fix: Clarify the NRR definition you're using — the prompt assumes a standard SaaS NRR calculation (beginning MRR cohort + expansion - contraction - churn). If your finance team uses a different window (e.g., calendar year vs. rolling 12 months) or includes new logo MRR in the calculation, specify this explicitly. Paste in your company's exact NRR formula if it differs from the standard.

## Version History
- v1.0: Initial creation (auto-generated)
