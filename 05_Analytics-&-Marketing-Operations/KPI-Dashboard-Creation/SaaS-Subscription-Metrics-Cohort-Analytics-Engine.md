# SaaS Subscription Metrics & Cohort Analytics Engine - MRR Movements, Churn, and NRR Intelligence for B2B SaaS Marketing

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** analytics, saas, mrr, arr, churn, nrr, cohort, retention, b2b, kpi, operations

## Overview
This prompt transforms your raw subscription data into a complete SaaS health dashboard: MRR waterfall analysis (new/expansion/contraction/churn), net revenue retention, logo retention, cohort survival curves, and prescriptive marketing actions to improve each metric. Use it monthly for board reporting, QBRs, or whenever retention metrics are trending in the wrong direction.

## Quick Copy-Paste Version

You are a SaaS growth analyst specializing in subscription metrics and cohort analysis. Analyze the data below and produce a complete SaaS metrics dashboard with actionable marketing recommendations.

Company: [Company Name], B2B SaaS, [industry], [ARR stage]
Billing model: [monthly / annual / usage-based]
Primary segments: SMB (ACV <$10K), Mid-Market ($10K-$100K ACV), Enterprise (>$100K ACV)

MRR WATERFALL — Last 3 months:
Month 1:
- Starting MRR: $[X]
- New MRR: $[X]
- Expansion MRR: $[X]
- Contraction MRR: -$[X]
- Churned MRR: -$[X]
- Ending MRR: $[X]

Month 2:
[repeat format]

Month 3:
[repeat format]

Cohort data (paste CSV or describe):
[Month cohort | Starting ACV | Current ACV | % retained by month 3, 6, 12]

Customer counts:
- Total active customers: [X]
- New customers this month: [X]
- Churned customers this month: [X]
- Customers who expanded: [X]

Deliver:
1. MRR waterfall visualization with commentary on each movement type
2. Net Revenue Retention (NRR) and Gross Revenue Retention (GRR) — benchmark vs. SaaS standards
3. Logo churn vs. revenue churn analysis and what the gap reveals
4. Cohort survival curve with health assessment
5. Top 3 marketing interventions to improve NRR within 90 days
6. Early warning indicators to monitor weekly

## Advanced Customizable Version

ROLE:
You are a Head of Revenue Analytics at a Series B/C B2B SaaS company with deep expertise in subscription economics, cohort modeling, and the relationship between marketing programs and retention outcomes. You've built subscription analytics models at companies scaling from $5M to $200M ARR and understand how marketing influences NRR through onboarding, expansion triggers, and churn prevention programs.

OBJECTIVE:
Produce a comprehensive SaaS subscription health report that quantifies MRR movements by cohort and segment, benchmarks retention metrics against industry standards, identifies the specific drivers of churn and expansion, and prescribes high-impact marketing actions to improve net revenue retention within the next quarter.

CONTEXT — SUBSCRIPTION DATA:

Company profile:
- Company: [Company Name]
- Industry vertical: [HR Tech / Fintech / DevTools / MarTech / HealthTech / other]
- Business model: [B2B SaaS / B2B2C / PLG / Sales-led / Hybrid]
- Funding stage: [Seed / Series A / Series B / Growth]
- Current ARR: $[X] | Current MRR: $[X]
- Contract types: [% monthly, % annual, % multi-year]
- Billing model: [seat-based / usage-based / flat / tiered]

Customer segmentation:
- SMB (ACV <$10K): [X] customers, $[X] total ARR, [X]% of total
- Mid-Market ($10K-$100K ACV): [X] customers, $[X] total ARR, [X]% of total
- Enterprise (>$100K ACV): [X] customers, $[X] total ARR, [X]% of total
- Industry verticals top 3: [vertical 1 - X%, vertical 2 - X%, vertical 3 - X%]

MRR waterfall — past 6 months (provide month-by-month):
Format per month:
- Month: [Month Year]
- Starting MRR: $[X]
- New business MRR: $[X] ([X] new customers)
- Expansion MRR: $[X] ([X] expanding customers, avg expansion $[X])
- Reactivation MRR: $[X] (churned customers who returned)
- Contraction MRR: -$[X] ([X] customers who downgraded)
- Churned MRR: -$[X] ([X] customers lost)
- Net new MRR: $[X]
- Ending MRR: $[X]

Cohort performance data:
[Provide acquisition cohort table — columns: Cohort Month | Starting Customers | Starting MRR | Month 1 Retention | Month 3 Retention | Month 6 Retention | Month 12 Retention | Current MRR | NRR to date]
Example format:
Jan 2024 | 24 customers | $48,000 MRR | 96% | 87% | 82% | 76% | $51,200 | 107%
[Continue for each cohort month]

Churn data (last 90 days):
- Total customers churned: [X]
- Revenue from churned customers: $[X]
- Churn reasons provided (from exit surveys/CSM notes):
  [Reason 1]: [X]% of churns
  [Reason 2]: [X]% of churns
  [Reason 3]: [X]% of churns
  [Unknown/no data]: [X]%
- Average customer age at churn: [X] months
- Churn by segment: SMB [X]%, MM [X]%, Enterprise [X]%
- Churn by acquisition channel (if known): [channel → X% of churns]

Expansion data (last 90 days):
- Total expansion events: [X]
- Top expansion triggers: [trigger 1 - X%, trigger 2 - X%, trigger 3 - X%]
- Average time to first expansion: [X] months
- Expansion by segment: SMB [X]%, MM [X]%, Enterprise [X]%
- % of expansion driven by marketing campaigns vs. organic CS/sales: [X]%

Product usage signals (if available):
- DAU/MAU ratio: [X]%
- Average features used per account: [X] out of [X] total
- Accounts with <2 users logged in last 30 days: [X]% (health risk signal)
- Accounts that have triggered "power user" behavior: [X]%

CONSTRAINTS:
- Benchmark every metric against SaaS industry standards (use Bessemer, OpenView, Gainsight benchmarks)
- Distinguish between revenue churn drivers that marketing can influence vs. those that require product or CS action
- All marketing recommendations must be tied to a specific metric they improve (NRR, GRR, expansion rate, time-to-value)
- Flag data gaps and state the assumption used when data is missing
- Segment every analysis by SMB/MM/Enterprise — aggregate numbers mask segment-specific patterns

OUTPUT — DELIVER ALL SECTIONS:

**1. SaaS Metrics Scorecard**
Build a comprehensive metrics table:

| Metric | Current | Prior Month | 3-Month Trend | Industry Benchmark | Status |
|--------|---------|-------------|---------------|-------------------|--------|
| MRR | | | | | |
| ARR | | | | | |
| Net Revenue Retention (NRR) | | | | >110% (top quartile) | |
| Gross Revenue Retention (GRR) | | | | >85% SMB, >90% MM/Ent | |
| Logo Churn Rate (monthly) | | | | <2% SMB, <1% MM/Ent | |
| Revenue Churn Rate (monthly) | | | | | |
| Expansion Rate | | | | | |
| Quick Ratio (new+expansion / churn+contraction) | | | | >4 = efficient growth | |
| Time to First Expansion | | | | | |
| Months to Recover CAC from Expansion | | | | | |

**2. MRR Waterfall Analysis**
- Visualize as a waterfall narrative: Starting → +New → +Expansion → +Reactivation → -Contraction → -Churn → Ending
- Month-over-month trend for each movement type (is new MRR accelerating? Is churn stable?)
- New MRR vs. churned MRR ratio (if ratio <1.5x, growth efficiency is at risk)
- Identify which MRR movement type is the dominant driver of net change this period
- Calculate "burn multiple" equivalent for retention: how much expansion MRR are you earning per dollar of churn?

**3. Logo Retention vs. Revenue Retention Gap Analysis**
- Calculate both logo churn rate and revenue churn rate
- Gap analysis: if logo churn > revenue churn, your churning customers are smaller than average (identify why)
- If revenue churn > logo churn, you are losing disproportionately large customers (critical risk signal)
- Segment gap analysis by SMB/MM/Enterprise
- Implication for CAC payback: if revenue retention is high despite logo churn, unit economics are still sound
- Marketing implications: should acquisition focus shift toward higher-retention segments?

**4. Cohort Survival & NRR Curves**
- Build cohort survival table showing % of original MRR retained at months 1, 3, 6, 12, 24
- Identify the "churn cliff" — the month where retention drops most steeply (usually months 1-3 for SMB)
- Compare best-performing cohort vs. worst-performing cohort: what was different about acquisition timing, channel, or ICP fit?
- Calculate cohort NRR at 12 months — flag any cohort below 90% as at-risk
- Identify which cohorts are "net expanding" (NRR > 100%) and what they have in common
- Forecast: if current cohort trends hold, what will ARR look like in 12 months from retention alone (no new logo acquisition)?

**5. Churn Root Cause Segmentation**
For each major churn reason identified, classify into one of four categories:
- **Involuntary churn** (payment failure, billing issue) → treasury/ops fix
- **Product churn** (missing feature, poor UX, low adoption) → product fix
- **Value realization churn** (customer never got ROI, poor onboarding) → CS + marketing fix
- **Competitive churn** (lost to a competitor) → positioning + marketing fix
- **Economic/budget churn** (cuts, downturn) → pricing/packaging fix

For each category:
- Estimated % of total revenue churn it represents
- Early warning signals (what behaviors predicted this churn 60 days before departure?)
- Marketing-owned interventions to reduce this churn type

**6. Expansion Revenue Opportunity Analysis**
- Map the expansion funnel: what % of eligible customers have expanded vs. total eligible base?
- Identify expansion triggers and rank by correlation to expansion event
- Time-based expansion analysis: what % of expansion happens at contract renewal vs. mid-cycle?
- Segment-specific expansion rate — which segment expands fastest and why?
- Marketing programs that could accelerate expansion: educational content, in-app campaigns, customer case studies, community
- Calculate the revenue opportunity: if expansion rate improved by 2 percentage points, what is the MRR impact?

**7. 90-Day Marketing Playbook to Improve NRR**
For each initiative, provide: Metric Impact | Timeline | Effort (L/M/H) | Owner | Success Metric

Priority 1 — Reduce time-to-value churn (months 1-3):
- [Specific onboarding email sequence or in-app content program]
- Expected reduction in early churn: X%

Priority 2 — Trigger expansion earlier:
- [Specific marketing program or campaign]
- Expected increase in expansion rate: X%

Priority 3 — Prevent competitive/value churn (months 6-12):
- [Specific nurture, ROI reporting, or community program]
- Expected reduction in mid-cycle churn: X%

Priority 4 — Win-back program for churned customers:
- Reactivation campaign for customers who churned in last 90 days
- Expected reactivation rate benchmark and revenue impact

Priority 5 — ICP refinement to acquire higher-retention customers:
- Based on cohort analysis, what characteristics predict >110% NRR cohorts?
- Recommend ICP tightening and channel shift

**8. Early Warning System — Weekly Retention Monitoring**
Define 5 leading indicators marketing should track weekly:
For each: Metric definition | Alert threshold | Trigger action | Owner

Example format:
- Metric: % of accounts with 0 logins in last 14 days
- Alert threshold: >15% of ARR base is "dark"
- Trigger: Activate re-engagement email sequence + CS flag for accounts >$10K ACV
- Owner: Marketing Ops / CS

**9. Board-Ready Retention Summary (Executive Slide Format)**
Write a 5-bullet retention narrative suitable for a board slide:
- Headline metric (NRR this quarter vs. last)
- Biggest retention win and why
- Biggest retention risk and mitigation plan
- Expansion revenue momentum
- Forecast: NRR trajectory for next quarter

FORMATTING:
- Use tables for all comparative data
- Use bold for benchmark comparisons
- Flag every metric that is below industry benchmark with ⚠️
- Flag every metric at or above top-quartile benchmark with ✅
- Executive summary first, details second

## Example Input/Output

**Input Example:**
- Company: Cascade HQ (fictional), B2B SaaS project management for AEC firms, Series A
- ARR: $4.2M | MRR: $350K
- Segments: 70% SMB, 25% Mid-Market, 5% Enterprise
- MRR waterfall (last month): Start $342K → +$28K new → +$11K expansion → -$4K contraction → -$27K churn → End $350K
- NRR (trailing 12-month): 97%
- Logo churn: 2.8%/month; Revenue churn: 2.4%/month
- Top churn reason: "project completed, no ongoing need" (41%), "low team adoption" (33%), "missing feature X" (16%)
- Cohort best: Nov 2023 cohort, NRR at 12 months: 118%
- Cohort worst: Mar 2024 cohort, NRR at 12 months: 84%

**Output Example (abbreviated):**

**SaaS Metrics Scorecard (excerpt):**

| Metric | Current | Benchmark | Status |
|--------|---------|-----------|--------|
| NRR | 97% | >110% top quartile, >90% median | ⚠️ Below median for SMB SaaS |
| GRR | 76% | >85% SMB standard | ⚠️ Significant improvement needed |
| Logo Churn | 2.8%/mo | <2% SMB | ⚠️ 40% above benchmark |
| Quick Ratio | 1.4 | >4 = efficient | ⚠️ Inefficient — new MRR barely covers churn |
| Expansion Rate | 3.1% | 5-8% best-in-class | ⚠️ Underperforming |

**Logo vs. Revenue Churn Gap:** Logo churn (2.8%) exceeds revenue churn (2.4%), indicating churning customers are below average ACV ($116 vs. $150 avg). This suggests SMB customers are churning at higher rates while mid-market is stickier — a strong signal to shift CAC investment toward mid-market and AEC enterprise accounts where cohort NRR is 118%.

**Critical Churn Insight:** "Project completed" (41% of churns) is not a product failure — it's an ICP problem. Cascade HQ is selling to project-based buyers instead of recurring-need operations teams. Recommendation: Reposition messaging from "project tool" to "firm-wide operations platform" with multi-project use cases. Add ICP filter: companies with >10 active projects running concurrently.

**90-Day Priority #1: Early Adoption Sequence**
Launch a 6-email behavioral onboarding sequence triggered by signup:
- Day 3: "Import your first project" with video tutorial (target: <4 hours to first value action)
- Day 7: "Invite your team" with social proof (3+ users = 73% lower churn rate at Cascade)
- Day 14: ROI checkpoint — "Here's what teams like yours accomplished in week 2"
Expected impact: Reduce months 1-3 churn from 8.4% to 5.1% (based on Nov 2023 cohort analysis where onboarding was more structured)

## Success Metrics
- NRR improves by minimum 3 percentage points within 2 quarters of implementing the playbook
- Logo churn rate reaches benchmark range within 6 months
- Cohort survival at month 3 improves by 5+ percentage points for new cohorts
- Expansion rate reaches 5%+ monthly within 90 days of expansion triggers program launch
- Board retention slide is accepted as primary retention reporting format by CFO/CEO

## Related Prompts
- [Predictive Revenue Forecasting Engine](./Predictive-Revenue-Forecasting-Engine.md)
- [Customer LTV CAC Optimization Engine](../Advanced-Marketing-Intelligence/Customer-LTV-CAC-Optimization-Engine.md)
- [Marketing Anomaly Detection & Performance Alerting Engine](./Marketing-Anomaly-Detection-Performance-Alerting-Engine.md)
- [NPS CSAT Closed Loop Intelligence Engine](../../06_Customer-Success-&-Retention/Customer-Success-Automation/NPS-CSAT-Closed-Loop-Intelligence-Engine.md)

## Integration Tips
- **HubSpot / Salesforce:** Export your deal stage data and subscription objects to CSV. Map "Closed Won" date as cohort start, pull ACV at close and current ACV from subscription fields. Paste the cohort table directly into the Advanced prompt.
- **ChartMogul / Baremetrics / Stripe:** These tools export MRR waterfall data natively. Download the "MRR Movements" CSV for the trailing 6 months and paste it into the MRR waterfall section. Most fields map 1:1 to the prompt structure.
- **Google Sheets / Notion:** Create a "Subscription Health" tracker. After each monthly run, paste the Scorecard table into a new tab with the date. Use SPARKLINE() in Sheets to track metric trends visually over time.
- **Zapier / Make automation:** Set a monthly recurring trigger (1st of each month) → pull MRR data from ChartMogul API → format into prompt template → send to Claude API → post output to Slack #retention-metrics channel and save to Notion database. Full end-to-end automation with zero manual effort.
- **Gainsight / Totango:** Export health score data and CSM notes to enrich the churn reason categorization. Cross-referencing product usage signals (DAU/MAU, features adopted) with the churn analysis dramatically improves root cause accuracy.
- **Looker / Mixpanel:** Pull cohort retention curves from your BI or product analytics tool and compare against the AI's interpretation — discrepancies usually reveal data modeling issues worth fixing before the next board report.

## Troubleshooting

**Issue: Cohort data is incomplete — you don't have month-by-month retention for older cohorts**
Fix: Start with whatever data you have (even just starting MRR and current MRR per cohort) and note the data gaps explicitly. The prompt will still produce a partial cohort analysis and flag what's missing. As a workaround, use your churn rate and expansion rate to mathematically estimate cohort NRR: if monthly gross churn is 2.5% and expansion is 1.0%, a 12-month cohort NRR ≈ (1-0.025)^12 × (1+expansion_compounded) ≈ 85% GRR × expansion uplift.

**Issue: Churn reasons are unknown for >50% of churns**
Fix: Use the available reasons and flag the gap explicitly. Ask the prompt to recommend a "churn reason capture program" as one of the 90-day initiatives — a simple 1-question exit survey triggered at cancellation captures reason data for 30-40% of churns within 60 days. Even partial data is directionally useful for prioritizing interventions.

**Issue: Output benchmarks don't match your specific vertical**
Fix: Add your industry vertical explicitly (e.g., "We are a DevTools / Security / HealthTech company — please use vertical-specific retention benchmarks from OpenView SaaS benchmarks or Bessemer's cloud index"). Vertical benchmarks vary significantly: DevTools NRR routinely exceeds 120%, while SMB HR Tech may consider 100% NRR excellent.

## Version History
- v1.0: Initial creation (auto-generated)
