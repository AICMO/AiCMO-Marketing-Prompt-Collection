# AI-Powered B2B SaaS RevOps Capacity Planning & Quota Architecture Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** revenue-operations, revops, capacity-planning, quota-setting, headcount-planning, pipeline-coverage, sales-math, gtm-strategy, b2b, saas, arp-planning, sdr-productivity

## Overview
Builds a complete revenue capacity planning model — working backwards from ARR targets to determine exact SDR, AE, and marketing investment requirements — including quota architecture, productivity ramp curves, pipeline coverage ratios, and territory design. Use this when building your Annual Operating Plan (AOP), when board or CFO asks "what do you need to hit the number," or when GTM leaders disagree on whether current headcount and pipeline are sufficient to close the year.

## Quick Copy-Paste Version

You are a senior RevOps strategist and revenue modeling expert specializing in B2B SaaS GTM capacity planning. I need a complete revenue capacity model that works backwards from my ARR target to tell me exactly what headcount, pipeline, and marketing investment I need.

My company details:
- Product: [What your software does]
- Current ARR: [e.g., $18M]
- ARR Target (next 12 months): [e.g., $30M]
- New logo ARR needed: [e.g., $8M]
- Expansion/upsell ARR needed: [e.g., $4M]
- Average ACV (new logo): [e.g., $45,000]
- Average ACV (expansion): [e.g., $18,000]
- Current win rate (from SQL to Closed-Won): [e.g., 22%]
- Average sales cycle: [e.g., 75 days]
- Current pipeline coverage ratio: [e.g., 3.2x]
- AE quota (annual): [e.g., $800,000]
- SDR quota (SQLs per month): [e.g., 8 SQLs/month]
- AE ramp time (months to full productivity): [e.g., 4 months]
- SDR ramp time: [e.g., 3 months]
- Current AE headcount: [e.g., 6 AEs]
- Current SDR headcount: [e.g., 4 SDRs]
- Marketing-sourced pipeline %: [e.g., 60%]
- Sales-sourced pipeline %: [e.g., 40%]

Build me the following capacity planning system:

1. REVENUE MATH DECOMPOSITION
   - Calculate exactly how many new logo deals I need to close to hit my new logo ARR target
   - Calculate how many SQLs I need (accounting for win rate)
   - Calculate how many MQLs I need (accounting for MQL-to-SQL conversion rate)
   - Calculate how many website visitors/inquiries I need at the top of funnel
   - Show the full "revenue math waterfall" as a table

2. AE HEADCOUNT CAPACITY MODEL
   - Given my ACV and quota, calculate how many AEs I need at full productivity to close the new logo target
   - Account for ramp: model productivity at months 1-4 vs. full productivity
   - Calculate "effective AEs" (total AEs × blended productivity based on tenure mix)
   - Tell me: do I have enough AE capacity? If not, when do I need to hire to hit the annual target?

3. SDR CAPACITY & PIPELINE COVERAGE MODEL
   - Calculate how much pipeline I need to maintain (target ARR ÷ win rate = required pipeline)
   - Split pipeline requirement by marketing-sourced vs. sales-sourced
   - Calculate SDR-required pipeline contribution (SQLs/month × ACV × win rate adjustment)
   - Tell me if my SDR headcount is sufficient; if not, how many I need and when to hire
   - Design the pipeline coverage ratio: what's the right coverage multiple given my win rate and sales cycle?

4. QUOTA ARCHITECTURE DESIGN
   - Validate whether my current AE quota is achievable given market conditions, ACV, and sales cycle length
   - Calculate the "quota coverage gap": how much total quota capacity (all AEs × quota) vs. my new logo target
   - Recommend quota structure: should I use annual quota, quarterly quota, or ramped quota by month?
   - Design a quota attainment distribution model: what % of reps should hit 100%+, 80-100%, <80%?

5. MARKETING INVESTMENT REQUIREMENTS
   - Given my marketing-sourced pipeline %, calculate the MQLs marketing must deliver monthly
   - Calculate the cost-per-MQL and cost-per-SQL I can afford given my CAC target
   - Build the marketing budget requirement: if my target CAC payback is [X months], what is my maximum allowable CAC, and therefore what is my marketing + sales budget ceiling?
   - Identify the 3 biggest capacity risks: what happens if win rates drop 5 points? If sales cycle extends 15 days? If marketing delivers 20% fewer MQLs?

Format output as: executive summary, detailed model tables for each section, and a "capacity risk dashboard" showing green/yellow/red status for each GTM lever.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Operations with 12+ years of B2B SaaS GTM experience, specializing in capacity planning models for companies scaling from $10M to $100M ARR. You have built revenue models for Series B through pre-IPO companies and have deep expertise in quota design, territory architecture, and pipeline mathematics.

CONTEXT:
Company: [Company name and one-line description]
Stage: [Series A/B/C/pre-IPO/public]
GTM Motion: [Enterprise field sales / Mid-market inside sales / SMB velocity / PLG + sales assist / hybrid]
Current ARR: $[X]M
ARR Target (fiscal year): $[X]M
ARR Target breakdown:
  - New logo ARR: $[X]M
  - Expansion/upsell ARR: $[X]M
  - Renewal/retention ARR: $[X]M (target churn rate: [X]%)

CURRENT GTM METRICS:
ACV (new logo): $[X]
ACV (expansion): $[X]
Win rate (SQL to close): [X]%
Sales cycle (days, new logo): [X]
Sales cycle (days, expansion): [X]
Pipeline coverage currently maintained: [X]x
MQL-to-SQL conversion rate: [X]%
SQL-to-Opportunity conversion rate: [X]%
Lead response time (median hours): [X]

CURRENT HEADCOUNT:
AEs: [X] (breakdown: [X] enterprise / [X] mid-market / [X] SMB if applicable)
SDRs/BDRs: [X] (inbound vs. outbound split: [X]% / [X]%)
Sales engineers/solutions consultants: [X]
Customer success managers (expansion-responsible): [X]
Marketing team: [X] total, [X] demand gen focused

QUOTA & PRODUCTIVITY:
AE annual quota: $[X]
AE average attainment last 12 months: [X]%
SDR SQL quota (per month): [X]
SDR average attainment: [X]%
AE ramp duration (months to 100% productivity): [X]
New AE hires planned: [X] (start dates: [list])
Average AE tenure: [X] months
Attrition rate (annualized): [X]%

PIPELINE DATA:
Marketing-sourced pipeline %: [X]%
Sales/SDR-sourced pipeline %: [X]%
Partner-sourced pipeline %: [X]%
Current open pipeline: $[X]M
Pipeline created last quarter: $[X]M
Planned pipeline coverage ratio target: [X]x

CONSTRAINTS:
Hiring budget available: [X] net new AE hires, [X] net new SDR hires in H1; [X] AE, [X] SDR in H2
Marketing budget: $[X]M annual
CAC payback target: [X] months
Gross margin: [X]%

OBJECTIVE: Build a board-ready revenue capacity model that tells me: (1) whether my current GTM capacity is sufficient to hit my ARR target, (2) exactly what gaps exist and when they become critical, (3) what investments close the gaps, and (4) what risks would blow up the model.

DELIVERABLE 1 — REVENUE MATH WATERFALL
Build a top-to-bottom model showing exactly how many of each are needed:
- Annual recurring revenue target → new logo deals needed
- New logo deals → SQLs needed (÷ win rate)
- SQLs → MQLs needed (÷ MQL-to-SQL conversion)
- MQLs → inquiries/visitors needed (÷ inquiry-to-MQL rate)
- Add SDR-sourced pipeline layer separately
- Show monthly pacing: how many of each must I hit per month to stay on track?
- Flag seasonal considerations: do you push more pipeline in Q1/Q3, or is it back-half weighted?

Format as: a waterfall table with monthly breakdown, plus a "where do I stand today vs. where I need to be" gap column.

DELIVERABLE 2 — AE CAPACITY MODEL (DETAILED)
Section A: Fully-ramped capacity
- Current AEs × quota = total quota capacity
- Total quota capacity × average attainment = expected production
- Gap: expected production vs. new logo ARR target
- Recommendation: how many additional AEs needed, and what start date do they need to hit their first full-productivity quarter?

Section B: Ramp-adjusted capacity model
- For each AE hire cohort (current tenure segments: 0-3 months, 4-6 months, 7-12 months, 12+ months), assign a productivity multiplier (e.g., 0%, 30%, 70%, 100%)
- Calculate "effective AEs" = sum of (headcount per cohort × productivity multiplier)
- Show total ramped production capacity by quarter through end of fiscal year
- Identify "productivity cliff months" — months where new hire cohorts are still ramping and capacity dips

Section C: Attrition modeling
- At [X]% annualized attrition, how many AEs will leave this year?
- Backfill hiring timeline: if an AE leaves, how long until their replacement is at full productivity?
- Calculate the "attrition productivity tax" — revenue lost during the ramp gap

DELIVERABLE 3 — PIPELINE COVERAGE ARCHITECTURE
Define the right pipeline coverage ratio for my specific context:
- Start with the "coverage formula": required pipeline = ARR target ÷ expected win rate, adjusted for pipeline decay rate and sales cycle duration
- Model three coverage scenarios: Conservative (4x), Target (3.2x), Aggressive (2.5x)
- For each scenario, calculate: monthly pipeline creation requirement, MQL requirement, SDR SQL requirement
- Design pipeline coverage by stage: what % of my pipeline should be in each stage (Early / Active / Late / Verbal) at any given time for a healthy funnel?
- Build a "pipeline health dashboard" with weekly targets by stage

DELIVERABLE 4 — QUOTA ARCHITECTURE & DESIGN
Evaluate and redesign quota structure:
- Is my current AE quota appropriate? Compare to SaaS benchmarks for similar ACV and GTM motion
- Calculate quota attainment distribution target (recommended: 60-70% of reps at 100%+, 20% at 80-99%, max 10-15% below 80%)
- Design quota by segment (if applicable): enterprise quota vs. mid-market quota vs. SMB quota
- Build a "quota coverage ratio": total quota × expected attainment rate vs. ARR target — what's the buffer?
- Recommendation on variable compensation structure: what % of OTE should be base vs. commission, and what's the accelerator structure above 100%?

For SDR quota:
- Validate SQL quota against industry benchmarks (inbound-heavy vs. outbound-heavy, ACV-adjusted)
- Design MQL-to-SQL conversion SLA: within how many hours should SDRs follow up on inbound MQLs?
- Build SDR productivity model: account for prospecting time, admin time, meetings attended — what's realistic SQL output per headcount?

DELIVERABLE 5 — MARKETING CAPACITY REQUIREMENTS
Translate headcount model into marketing investment requirements:
- MQLs required from marketing (from waterfall model) × target cost-per-MQL = minimum marketing program spend required
- Build cost-per-MQL targets by channel: content/SEO, paid search, paid social, events, partner
- Calculate allowable CAC: if CAC payback target is [X] months and ACV is $[X], what is the maximum total CAC (marketing + sales fully-loaded)?
- Translate allowable CAC into a marketing budget ceiling
- Design marketing's "pipeline contribution SLA": how many MQLs, pipeline dollars, and influenced ARR must marketing deliver monthly to fulfill AE capacity?

DELIVERABLE 6 — SENSITIVITY & RISK ANALYSIS
Build a sensitivity model for the 5 highest-risk variables:
1. Win rate: what if win rate drops from [X]% to [X-5]%? Impact on new logo ARR
2. Sales cycle: what if cycle extends by 15 days? Impact on Q4 close rates
3. SDR productivity: what if SDRs hit 80% of quota? MQL gap created
4. AE ramp: what if new AE hires take 2 months longer to ramp? Revenue shortfall
5. Marketing pipeline: what if marketing delivers 20% fewer MQLs in H1? Recovery options

For each scenario:
- Quantify the ARR impact
- Identify the earliest leading indicator that would signal this risk materializing
- Recommend the specific mitigation action if the signal appears

DELIVERABLE 7 — 90-DAY REVOPS ACTION PLAN
Based on the model, produce a prioritized action plan:
- Top 3 gaps requiring immediate action (with specific owner: CEO / CRO / CMO / VP RevOps)
- Hiring decision deadlines: "If we don't hire [role] by [date], we cannot hit [target] in [quarter]"
- Pipeline creation milestones: weekly/monthly MQL and SQL targets for the next 90 days
- Quota and territory changes to implement before next quarter
- One RevOps dashboard to build that makes this model self-updating

OUTPUT FORMAT:
1. Executive Summary (5-6 bullets, board-ready language)
2. Revenue Math Waterfall Table
3. AE Capacity Model (tables + quarter-by-quarter projection)
4. Pipeline Coverage Architecture (target coverage model by stage)
5. Quota Architecture Scorecard (current vs. recommended)
6. Marketing Requirements Summary
7. Sensitivity Dashboard (green/yellow/red by variable)
8. 90-Day Action Plan (prioritized, with owners and deadlines)

## Example Input/Output

**Input Example:**
- Company: Vaultify — B2B SaaS contract intelligence platform (AI-powered contract analytics for enterprise legal and procurement teams)
- Stage: Series B
- Current ARR: $14M
- ARR Target: $24M (net new target: $10M)
- New logo ARR needed: $7M, Expansion: $3M
- ACV (new logo): $52,000
- Win rate: 21%
- Sales cycle: 82 days
- Current AE headcount: 5 AEs
- AE quota: $900,000
- SDR headcount: 3 SDRs
- Marketing-sourced pipeline: 62%
- Current open pipeline: $4.2M

**Output Example (abbreviated):**

*Executive Summary:*
Vaultify needs 135 new logo SQLs in the next 12 months (11.3/month) to close 29 new logo deals averaging $241K each in ARR. Current AE capacity at blended 78% attainment delivers $3.51M vs. $7M target — a $3.49M capacity gap. You need 4 additional AEs hired by Q2 to be productive by Q3 close season. Marketing must deliver 315 MQLs at a 43% MQL-to-SQL rate — current pace is 18 MQLs/month vs. 26 required. Pipeline coverage at $4.2M open vs. $9.5M required is critically under-covered at 2.1x vs. 3.5x target.

*Revenue Math Waterfall:*

| Metric | Annual Needed | Monthly Target | Current Run Rate | Gap |
|---|---|---|---|---|
| New Logo ARR | $7,000,000 | $583,333 | $350,000 | -$233,333 |
| Deals to Close | 135 | 11.3 | 8.1 | -3.2/mo |
| SQLs Required | 643 | 53.6 | 34 | -19.6/mo |
| MQLs Required | 1,495 | 124.6 | 78 | -46.6/mo |
| Pipeline Required ($) | $30.5M | $2.54M | $1.4M | -$1.14M/mo |

*Capacity Gap Analysis:*
At current 5 AEs × $900K quota × 78% attainment = $3.51M expected new logo production. Target is $7M. Capacity gap: $3.49M. To close gap with AEs alone: need 4 additional AEs. Last hire date to reach full productivity before Q4 close season: April 30, 2026.

*Top 3 Priority Actions:*
1. **Hire 4 AEs by April 30** — CRO owns. Delay of 30 days costs ~$350K in Q4 revenue.
2. **Increase marketing MQL delivery from 78/month to 125/month** — CMO owns. Requires $180K additional demand gen investment or channel reallocation.
3. **Pipeline coverage emergency: source $5.3M in new pipeline in 90 days** — RevOps + Marketing joint sprint. Immediate actions: reactivate 90-day stalled deals, launch competitive displacement campaign targeting top 30 named accounts.

## Success Metrics

- Revenue math waterfall is internally consistent: every metric traces back to ARR target through the funnel math
- AE capacity model accounts for ramp curve, not just headcount × quota
- Sensitivity analysis identifies which single variable has highest ARR leverage
- Hiring deadlines are specific (not "Q2" but "by April 30") with impact quantified for missing them
- Marketing investment requirements connect directly to headcount model (not standalone)
- Output is boardroom-ready: a CRO could present this to a board without additional translation

## Related Prompts

- [Revenue Operations Analytics & GTM Performance](./AI-Powered-B2B-SaaS-Revenue-Operations-Analytics-&-GTM-Performance-Intelligence-Engine.md)
- [Demand Generation Program Analytics & Pipeline Coverage](../../05_Analytics-&-Performance/Demand-Generation-Program-Analytics/AI-Powered-B2B-SaaS-Demand-Generation-Program-Analytics-&-Pipeline-Coverage-Intelligence-Engine.md)
- [CAC Payback & Unit Economics Intelligence](../../05_Analytics-&-Performance/CAC-Payback-&-Unit-Economics-Analytics/CAC-Payback-&-Unit-Economics-Intelligence-Engine.md)
- [AI-Powered CMO Revenue Forecast Modeling & Predictive Pipeline Intelligence](../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-CMO-Revenue-Forecast-Modeling-&-Predictive-Pipeline-Intelligence-Engine.md)

## Integration Tips

- **Salesforce / HubSpot:** Map each waterfall metric to a native report. Create a "Revenue Math Dashboard" in your CRM with monthly targets for: SQLs created, pipeline created, opportunities opened, and pipeline coverage ratio. Set up automated alerts when any metric drops below 85% of monthly target.
- **Google Sheets / Excel:** The capacity model is best maintained in a live spreadsheet. Build it once from this prompt, then update inputs monthly. Key tabs: Revenue Math, AE Capacity, SDR Capacity, Pipeline Coverage, Sensitivity Analysis. Link to CRM data via Salesforce connector or HubSpot API export.
- **Gong / Chorus:** Use conversation intelligence data to validate ramp time assumptions. If your model assumes 4-month ramp but Gong shows new reps don't achieve consistent discovery call scores until month 5, update the ramp curve accordingly.
- **Clari / Bowtie:** Feed the pipeline coverage targets from this model into your forecasting tool as category thresholds. Pipeline coverage <2.5x = red; 2.5-3.2x = yellow; >3.2x = green.
- **Lattice / Workday:** Export quota targets and attainment distributions into your performance management system to align OKRs with the capacity model assumptions.
- **Board Reporting:** Export the executive summary and sensitivity dashboard as a PDF. The waterfall table and capacity gap analysis are standard board asks in any GTM review — run this model at least 60 days before your quarterly board meeting.

## Troubleshooting

- **Problem:** Model shows I need far more AEs than budget allows.
  **Solution:** Re-examine the quota architecture. If you can increase ACV by 15% (through better discovery, land-and-expand, or packaging), the number of deals needed drops proportionally. Also run the sensitivity analysis on win rate — a 5-point improvement in win rate often has more impact than one additional AE hire.

- **Problem:** Marketing pipeline contribution requirement looks impossibly high.
  **Solution:** Break down the MQL-to-SQL conversion rate by source. If paid channels convert at 18% but organic/content converts at 52%, reallocating budget toward content/SEO dramatically improves the math without increasing total MQL volume. Also investigate whether SDR outbound can absorb more of the pipeline gap if marketing contribution is capped.

- **Problem:** Ramp model shows critical productivity gaps in Q3 but hiring is constrained.
  **Solution:** Model the impact of investing in AE ramp acceleration programs (better onboarding, sales training, SE support) vs. hiring. Reducing ramp from 4 months to 3 months on 5 existing new hires can unlock more Q3 capacity than one incremental hire that starts in April.

## Version History
- v1.0: Initial creation (auto-generated)
