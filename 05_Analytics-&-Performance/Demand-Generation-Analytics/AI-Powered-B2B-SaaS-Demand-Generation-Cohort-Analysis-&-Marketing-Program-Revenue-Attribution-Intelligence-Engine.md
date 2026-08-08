# AI-Powered B2B SaaS Demand Generation Cohort Analysis & Marketing Program Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** demand-gen, analytics, cohort-analysis, revenue-attribution, lagged-attribution, pipeline-velocity, b2b-saas, marketing-roi, cfo-reporting, program-measurement

## Overview

This prompt builds an AI analytics engine that groups demand generation leads by acquisition cohort (by program, campaign, or time period), tracks their full journey from first touch to closed revenue, and calculates the true lagged ROI of every marketing investment — even across 90–180 day sales cycles. Use it when your CMO needs to prove to a CFO that marketing spending from Q3 is driving Q4 and Q1 revenue, or when you need to identify which demand gen programs have the strongest long-term pipeline and revenue contribution vs. short-term MQL inflation.

## Quick Copy-Paste Version

You are a senior B2B SaaS demand generation analytics strategist specializing in cohort-based program attribution. My company sells [PRODUCT] to [ICP, e.g., "VP of Finance at Series B-D SaaS companies with 50-500 employees"]. Our average contract value is [$X ARR], average sales cycle is [X days], and our fiscal year runs [calendar/non-calendar].

Analyze our demand generation program performance using cohort methodology and produce a complete Marketing Program Revenue Attribution Report. Here is our data:

**Company Context:**
- CRM: [HubSpot / Salesforce / Other]
- Marketing automation: [HubSpot / Marketo / Pardot / Other]
- Attribution model currently used: [First-touch / Last-touch / Multi-touch / None]
- Average sales cycle: [X days]
- Revenue target this fiscal year: [$X ARR]

**Demand Generation Cohorts to Analyze (past 4 quarters):**

Q[X-3] Cohort (oldest):
- Leads generated: [X]
- Primary programs: [e.g., "Q1 webinar series, LinkedIn ABM campaign, outbound SDR sequence"]
- Total program spend: [$X]
- Leads still in active pipeline: [X]
- Leads closed-won: [X]
- Closed-won revenue: [$X ARR]
- Leads closed-lost or disqualified: [X]
- Average days to close (for closed-won): [X]

Q[X-2] Cohort:
- Leads generated: [X]
- Primary programs: [list]
- Total program spend: [$X]
- Leads still in active pipeline: [X]
- Leads closed-won: [X]
- Closed-won revenue: [$X ARR]
- Leads closed-lost or disqualified: [X]
- Average days to close (for closed-won): [X]

Q[X-1] Cohort:
- Leads generated: [X]
- Primary programs: [list]
- Total program spend: [$X]
- Leads still in active pipeline: [X]
- Leads closed-won: [X]
- Closed-won revenue: [$X ARR]
- Leads closed-lost or disqualified: [X]
- Average days to close (for closed-won): [X]

Q[X] Cohort (most recent, expect low closed-won):
- Leads generated: [X]
- Primary programs: [list]
- Total program spend: [$X]
- Leads still in active pipeline: [X]
- Leads closed-won: [X]
- Closed-won revenue: [$X ARR]

Produce the following analysis:

1. COHORT MATURITY CURVES — For each cohort, calculate: (a) % of leads closed-won by month 1, 3, 6, 9 after acquisition, (b) revenue recognized by quarter since acquisition, (c) pipeline still outstanding as projected future revenue. Identify the typical "revenue recognition peak" — what month after acquisition generates the most closed-won revenue.

2. TRUE PROGRAM ROI BY COHORT — For each quarter cohort, calculate: (a) Closed-won revenue to date, (b) Projected final revenue (closed + in-pipeline × win rate), (c) Program ROI = (Projected revenue − Program spend) ÷ Program spend × 100, (d) Payback period in months, (e) Revenue per dollar spent. Flag any cohort with negative or below-benchmark ROI and diagnose why.

3. LAGGED ATTRIBUTION ANALYSIS — Show the revenue recognized THIS quarter by cohort origin: how much of Q[X] revenue came from Q[X-3] leads vs. Q[X-2] leads vs. Q[X-1] leads vs. Q[X] leads. Calculate the revenue "lag factor" — the average number of quarters between lead acquisition and revenue recognition. If using first/last-touch attribution, show what multi-touch cohort attribution reveals that current model misses.

4. PIPELINE VINTAGE HEALTH — Analyze current open pipeline by acquisition vintage: (a) Leads acquired >180 days ago still in pipeline — calculate % likelihood of closing vs. expected attrition, (b) Leads acquired 90-180 days ago — identify stalled deals and root cause patterns, (c) Leads acquired <90 days ago — forecast revenue recognition timing. Flag pipeline that should be risk-adjusted in the revenue forecast.

5. PROGRAM EFFICIENCY BENCHMARKS — Compare each cohort against these B2B SaaS benchmarks: Lead-to-Opportunity rate ≥15%, Opportunity win rate ≥20%, Average sales cycle ≤90 days (mid-market), Cost per Closed-Won ≤3× ACV. Identify which programs and cohorts are above/below benchmark and what drove the variance.

6. CFO-READY NARRATIVE — Write a 5-bullet executive summary explaining: (a) total marketing investment across all 4 cohorts, (b) revenue recognized to date from those cohorts, (c) projected total revenue when all current pipeline closes, (d) overall marketing ROI and payback period, (e) the top 2 program types that generated the highest-quality pipeline. Make it boardroom-ready with specific numbers.

## Advanced Customizable Version

ROLE: You are an AI-powered demand generation analytics system with expertise in cohort-based revenue attribution, B2B SaaS unit economics, and CFO-level marketing ROI reporting. You have deep knowledge of HubSpot, Salesforce, and BI tool reporting methodologies.

COMPANY CONTEXT:
- Company: [Name]
- Product: [What it does]
- ICP: [Who buys it]
- ACV: [$X]
- Sales cycle (median): [X days]
- GTM motion: [Inbound / Outbound / PLG / ABM / Hybrid]
- Marketing team size: [X people]
- Marketing budget (annual): [$X]

OBJECTIVE: Build a comprehensive demand generation cohort attribution model that demonstrates true marketing ROI to a skeptical CFO, identifies the highest-leverage programs for future investment, and creates a revenue forecasting model from current pipeline.

SECTION 1 — COHORT CONSTRUCTION METHODOLOGY
Define the cohort grouping logic for this company:
- Primary cohort dimension: [Acquisition quarter / Campaign type / Channel / ICP segment]
- Lead creation date vs. MQL date vs. opportunity creation date — specify which to use as cohort anchor
- How to handle multi-touch attribution across cohorts (which program "owns" the lead?)
- Define "revenue recognition" for cohort purposes: contract signature date vs. payment date vs. ARR start date

COHORT DATA INPUTS (complete for each cohort period analyzed):

[COHORT PERIOD — e.g., Q1 2025]
Programs included:
- Program 1: [Name, type, spend [$X], leads generated [X], channel]
- Program 2: [Name, type, spend [$X], leads generated [X], channel]
- [Add more as needed]

Pipeline journey data:
- Leads created: [X]
- MQLs: [X] (conversion rate [X%])
- SQLs / Sales-accepted: [X] (MQL-to-SQL rate [X%])
- Opportunities created: [X] (SQL-to-Opp rate [X%])
- Opportunities closed-won: [X] (win rate [X%])
- Revenue closed-won: [$X ARR]
- Average days from lead to close: [X]
- Open pipeline remaining: [$X ARR]
- Opportunities closed-lost: [X] (average deal size [$X], primary loss reason [X])

[Repeat for each additional cohort period]

SECTION 2 — ANALYSIS MODULES

MODULE A — COHORT MATURITY & REVENUE RECOGNITION CURVES
For each cohort, produce:
1. Monthly revenue recognition waterfall: how much revenue closed in month 1, 2, 3... 12+ after cohort creation
2. Cumulative revenue curve showing the S-curve of revenue realization over time
3. "Revenue maturity" assessment: what % of eventual total revenue has been recognized at 3/6/9/12 months
4. Identification of the "long tail" — leads still converting 12+ months after acquisition
5. Comparison across cohorts: is the revenue curve accelerating or decelerating? What does this signal about sales cycle length trends?

MODULE B — PROGRAM-LEVEL ROI DECOMPOSITION
For each major program type across all cohorts:
- Total spend: [$X across all cohorts where program was active]
- Total leads contributed: [X]
- Total revenue attributed (closed): [$X]
- Revenue-in-pipeline attributed: [$X projected, adjusted for win rate]
- Total expected revenue: [$X]
- Program ROI: [(Expected revenue − Spend) ÷ Spend × 100]%
- Cost per closed-won customer: [$X]
- Revenue multiple (revenue ÷ spend): [X×]
- Ranking vs. other programs: [1st/2nd/3rd]

Program types to analyze (use actual programs from your data):
- Content/SEO organic
- Paid search (Google Ads)
- Paid social (LinkedIn Ads)
- Email nurture / marketing automation
- Webinars / virtual events
- Field events / trade shows
- Outbound SDR sequences
- Partner/referral programs
- Community / organic social
- Account-based marketing (ABM)

MODULE C — PIPELINE VINTAGE RISK MODEL
For current open pipeline, stratify by acquisition vintage:

Vintage bucket analysis:
>180 days in pipeline: [X opportunities, $X ARR]
- Win probability adjustment: Apply 0.5× multiplier to standard win rate (stalled deals rarely close at benchmark rates)
- Risk-adjusted pipeline value: [$X]
- Recommended action: [Re-qualify, executive outreach, re-demo, or close-lost]

90-180 days in pipeline: [X opportunities, $X ARR]
- Win probability at benchmark
- Stall indicators to flag: [no activity in 30+ days, champion went dark, procurement hold]
- Risk-adjusted pipeline value: [$X]

<90 days in pipeline: [X opportunities, $X ARR]
- Standard win rate applies
- Expected close timing based on average sales cycle
- Which cohort programs generated these — are high-quality programs represented?

Total risk-adjusted pipeline: [$X]
Expected Q[next] revenue from existing pipeline: [$X]
Pipeline gap to Q[next] target: [$X] (requiring [$X/average ACV] new wins)

MODULE D — PREDICTIVE DEMAND GENERATION INVESTMENT MODEL
Based on cohort performance data, build a forward-looking model:

Input: Revenue target for next 4 quarters: [$X per quarter]
Current pipeline coverage ratio: [X× — target is 3-4×]

Working backwards:
- To close [$X revenue] with a [X%] win rate: need [$X × (1/win rate)] in Opportunity pipeline
- To generate [$X in opportunity pipeline] with [$X ACV] average deal: need [X] opportunities
- To generate [X] opportunities with [X%] SQL-to-Opp rate: need [X] SQLs
- To generate [X] SQLs with [X%] MQL-to-SQL rate: need [X] MQLs
- To generate [X] MQLs with [X%] session-to-MQL rate: need [X] sessions OR [X] outbound touches
- Budget required: [$X] based on current cost-per-MQL by channel

Channel investment recommendation:
- Highest ROI channels (double investment): [Programs from Module B ranked #1, #2]
- Maintenance channels (hold budget): [Programs ranked #3, #4]
- Restructure or pause: [Lowest ROI programs]
- New programs to test based on cohort data gaps: [e.g., "ICP accounts with no marketing touch"]

MODULE E — CFO BOARD PRESENTATION NARRATIVE
Produce a concise, data-driven narrative (max 8 bullet points) covering:
1. Total marketing investment committed in past [X] quarters: [$X]
2. Revenue recognized from those cohorts to date: [$X] (ROI = [X%])
3. Revenue still projected from in-pipeline cohort leads: [$X]
4. Total expected return from cohort investments: [$X] ([X×] revenue multiple)
5. Average payback period: [X months]
6. Best-performing program type by revenue multiple: [Program name, X× return]
7. Current pipeline coverage ratio: [X×] against next quarter target
8. Recommended budget adjustment: [+$X to [program], −$X from [program], forecast impact: $X additional revenue]

CONSTRAINTS:
- All ROI calculations must show both "revenue-to-date" and "projected total revenue" views
- Flag any assumption about win rates or pipeline projections clearly
- Do not credit revenue to marketing where sales sourced the opportunity (define marketing-sourced vs. marketing-influenced separately)
- Use conservative (0.8×) multipliers on projected pipeline revenue for board presentations
- Provide a "confidence interval" for projected revenue (low/mid/high scenario based on 60-80-100% of standard win rate)

OUTPUT FORMAT:
- Section 1: Cohort maturity table (cohort × month = revenue recognized)
- Section 2: Program ROI leaderboard with revenue multiples
- Section 3: Pipeline vintage risk dashboard
- Section 4: Forward investment model with channel recommendations
- Section 5: CFO narrative (copy-paste ready for board deck)
- Section 6: Top 3 action items with specific owners and deadlines

## Example Input/Output

**Input Example:**

Company: Axiom Data Platform — sells real-time data infrastructure software to VP/Director of Data Engineering at fintech companies (150-1,500 employees). ACV: $72,000. Median sales cycle: 87 days. GTM: primarily inbound + ABM.

Q1 2025 Cohort: 180 leads, $120K program spend (paid LinkedIn campaign + thought leadership webinar series). 32 MQLs → 14 SQLs → 9 opportunities → 4 closed-won. Closed-won ARR: $288K. 2 opportunities still in pipeline ($144K ARR).

Q2 2025 Cohort: 210 leads, $95K program spend (SEO content push + G2 review campaign). 41 MQLs → 17 SQLs → 11 opportunities → 6 closed-won. Closed-won ARR: $432K. 3 opportunities still in pipeline ($216K ARR).

Q3 2025 Cohort: 195 leads, $110K program spend (ABM account targeting + field event). 38 MQLs → 15 SQLs → 10 opportunities → 3 closed-won. Closed-won ARR: $216K. 5 opportunities still in pipeline ($360K ARR). 2 opportunities stalled >90 days.

Q4 2025 Cohort: 240 leads, $130K spend (holiday webinar + year-end paid search push). 45 MQLs → 18 SQLs → 12 opportunities → 1 closed-won. Closed-won ARR: $72K. 9 opportunities in pipeline ($648K ARR).

**Output Example (abbreviated):**

**COHORT MATURITY ANALYSIS — Axiom Data Platform**

*Revenue Recognition by Cohort (Months Post-Acquisition):*

| Cohort | Month 3 | Month 6 | Month 9 | Projected Final |
|--------|---------|---------|---------|-----------------|
| Q1 2025 | $72K | $216K | $288K | $378K (inc. pipeline) |
| Q2 2025 | $144K | $432K | $504K | $648K (inc. pipeline) |
| Q3 2025 | $72K | $216K | $432K (proj.) | $576K |
| Q4 2025 | $0 | $72K | $504K (proj.) | $720K |

*Revenue recognition peak: Month 6-9 post-acquisition. Q4 2025 pipeline is healthy — 75% of projected revenue has not yet been recognized.*

**PROGRAM ROI LEADERBOARD:**

| Program Type | Total Spend | Revenue Recognized | Projected Total | Revenue Multiple |
|---|---|---|---|---|
| SEO/Content (Q2) | $38K | $432K | $540K | 14.2× |
| ABM Targeting (Q3) | $55K | $216K | $432K | 7.8× |
| LinkedIn Paid (Q1) | $65K | $288K | $378K | 5.8× |
| Webinar Series (Q1/Q4) | $102K | $288K | $720K | 7.1× |
| G2 Review Campaign (Q2) | $22K | $144K | $216K | 9.8× |

**TOP FINDING:** SEO/content investment in Q2 has the highest revenue multiple (14.2×) but longest payback period (6 months). ABM and G2 reviews show strong mid-range ROI with faster velocity. Recommend increasing SEO + G2 investment by 30% in Q1 2026 for Q3/Q4 2026 revenue impact.

**PIPELINE VINTAGE RISK:**

- Q1 2025 vintage still in pipeline (>270 days): 2 opportunities, $144K ARR → Risk-adjusted to $72K (0.5× multiplier). Recommend executive outreach or close-lost decision.
- Q3 2025 stalled deals (2 opportunities, $144K ARR): Likely prospect budget freeze. Flag for Q1 re-engagement sequence.
- Q4 2025 pipeline ($648K ARR): 9 opportunities on-track. Expected close: Q2 2026. Risk-adjusted: $518K.

**CFO NARRATIVE:**

- Total marketing investment (4 cohorts): $455K
- Revenue recognized to date: $1,008K (2.2× return to date)
- Revenue still projected from in-pipeline leads: $1,170K (risk-adjusted: $936K)
- Total expected return from cohort investments: $2,178K — **4.8× revenue multiple**
- Average payback period: 5.2 months from lead acquisition to first revenue
- Best-performing program: SEO/content (14.2× revenue multiple, scales without linear cost increase)
- Pipeline coverage ratio: 3.8× against Q2 2026 target ✅
- Recommendation: Shift $25K from paid LinkedIn to SEO/content and G2 review investment in Q1 2026, projected impact: +$175K incremental revenue in H2 2026

## Success Metrics

**The prompt output is performing well when:**
- Each cohort has a complete revenue recognition timeline with clear maturity stages
- Program ROI calculations distinguish between "revenue recognized" and "projected total revenue" with clear assumptions stated
- Pipeline vintage risk assessment correctly flags deals >180 days as high-risk with specific recommended actions
- The forward investment model produces specific budget recommendations by channel with projected revenue impact
- The CFO narrative passes the "CFO sniff test" — specific numbers, conservative projections, no marketing jargon
- At least 2-3 counterintuitive insights are surfaced (e.g., "the cheapest-looking channel has the best long-term ROI")
- The analysis catches stalled pipeline that would otherwise inflate the pipeline number without closing

**Red flags in output:**
- Win rates higher than your historical actuals (model is being optimistic — push back)
- Revenue projections that don't account for pipeline aging / deal decay
- No distinction between marketing-sourced and marketing-influenced pipeline
- Missing the "lagged attribution" insight — if everything maps to the same quarter, the model isn't doing cohort analysis

## Related Prompts

- [Full-Funnel Demand Generation Analytics & Revenue Pipeline Performance](./AI-Powered-B2B-SaaS-Full-Funnel-Demand-Generation-Analytics-&-Revenue-Pipeline-Performance-Intelligence-Engine.md)
- [ICP Account Coverage Analytics & Demand Generation Targeting](./AI-Powered-B2B-SaaS-ICP-Account-Coverage-Analytics-&-Demand-Generation-Targeting-Revenue-Intelligence-Engine.md)
- [Marketing Pipeline Influence Scoring & Revenue Acceleration Attribution](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-B2B-Marketing-Pipeline-Influence-Scoring-&-Revenue-Acceleration-Attribution-Intelligence-Engine.md)
- [CAC Payback & Unit Economics Intelligence Engine](../../05_Analytics-&-Performance/CAC-Payback-&-Unit-Economics-Analytics/CAC-Payback-&-Unit-Economics-Intelligence-Engine.md)

## Integration Tips

**HubSpot:**
- Use HubSpot's "Create date" and "Original source" fields as cohort anchors
- Build cohort reports in HubSpot's custom report builder: filter deals by "Create date" of associated contact, group by quarter
- Export deal-level data to Google Sheets for the multi-cohort revenue matrix
- Use HubSpot's Revenue Attribution report (Marketing Hub Enterprise) to cross-validate cohort findings

**Salesforce:**
- Use Salesforce Campaigns + Campaign Influence to link opportunities to source programs
- Build cohort reports using Opportunity "Created Date" with Campaign filters
- Salesforce Einstein Analytics can build the maturity curve automatically with the right data model
- Export to Tableau or Looker for the cohort maturity waterfall visualization

**Notion / Google Sheets:**
- Paste the cohort data table into Notion for async sharing with the CFO
- Build the cohort maturity matrix in Google Sheets with conditional formatting (green = above benchmark, red = below) for the board deck
- Use Google Sheets' ARRAYFORMULA to calculate cumulative revenue by cohort-month automatically

**Revenue Operations:**
- Sync cohort attribution data to your data warehouse (Snowflake, BigQuery) monthly
- Build a dbt model that joins marketing program spend to opportunity creation and deal close dates
- Set up a monthly automated report that refreshes cohort data and alerts when a cohort's projected ROI drops below 3×

**Zapier / n8n Automation:**
- Trigger cohort analysis monthly when CRM deal data is updated
- Auto-generate cohort summary report and Slack it to marketing leadership and CFO on the 1st of each month
- Alert revenue ops team when pipeline vintage risk flag is triggered (deals >180 days without activity)

## Troubleshooting

**Problem: Cohort revenue looks artificially low because my sales cycle is longer than one quarter.**
Solution: Run cohort analysis over at least 3-4× your average sales cycle length. If your sales cycle is 90 days, analyze cohorts with at least 12 months of historical data. For the most recent cohort (current quarter), explicitly label revenue as "projected" with a 60/80/100% win rate scenario range rather than reporting actuals.

**Problem: I can't separate marketing-sourced vs. marketing-influenced pipeline in my CRM.**
Solution: Establish a sourcing convention before running the analysis: "Marketing-sourced" = first contact with the company came via a marketing program (inbound form, event registration, content download); "Marketing-influenced" = marketing touched the account before opportunity creation but didn't source it (paid impression, email open, content view). Tag these fields in your CRM retroactively using campaign data, then segment cohort analysis by sourcing type. Even rough segmentation is better than treating all pipeline as equal.

**Problem: My CFO doesn't trust projected revenue numbers — they only want to see realized revenue.**
Solution: Present two views: (1) "Realized ROI" — revenue already closed from each cohort vs. spend (conservatives will trust this), and (2) "Projected ROI" — includes risk-adjusted pipeline with explicit assumptions (e.g., "assumes 22% win rate, consistent with trailing 4-quarter actuals"). Label projected numbers clearly as estimates. Lead with the realized ROI number to establish credibility, then show projected to make the forward investment case. Use the historical cohort data to demonstrate that your win rate assumption has been accurate ±5% over the past 4 quarters.

## Version History
- v1.0: Initial creation (auto-generated)
