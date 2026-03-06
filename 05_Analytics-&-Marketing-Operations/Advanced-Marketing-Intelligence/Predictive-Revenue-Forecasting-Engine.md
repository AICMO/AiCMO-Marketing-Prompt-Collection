# Predictive Revenue Forecasting Engine - AI-Powered Pipeline & Revenue Forecasting for Marketing Teams

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** analytics, forecasting, revenue, pipeline, b2b, saas, data-driven, operations

## Overview
This prompt transforms your historical marketing and sales data into a rolling revenue forecast with pipeline health diagnostics, scenario modeling, and channel-level revenue contribution projections. Use it at the start of each quarter, after a major campaign, or when leadership demands a data-backed revenue outlook.

## Quick Copy-Paste Version

You are a revenue operations analyst and marketing data scientist. I need a complete revenue forecast and pipeline analysis based on the data below.

My business context:
- Business model: [B2B SaaS / B2C ecommerce / D2C / professional services]
- Current ARR/monthly revenue: $[X]
- Target for next quarter: $[X]
- Primary sales motion: [inbound-led / outbound-led / product-led / channel]

Marketing pipeline inputs (last 90 days):
- MQLs generated: [X]
- MQL-to-SQL conversion rate: [X]%
- SQL-to-opportunity conversion rate: [X]%
- Average deal size: $[X]
- Average sales cycle length: [X] days
- Win rate from opportunity: [X]%
- Open pipeline value today: $[X]

Channel breakdown of MQL sources:
- Paid search: [X]%
- Paid social: [X]%
- Organic/SEO: [X]%
- Email/nurture: [X]%
- Events/webinars: [X]%
- Partner/referral: [X]%

Current monthly marketing spend: $[X]

Please deliver:
1. A 90-day revenue forecast with confidence range (bear / base / bull scenarios)
2. Pipeline coverage ratio and whether current pipeline is sufficient to hit target
3. The top 3 funnel stages where conversion rates are creating revenue drag
4. Channel-level revenue contribution ranked by closed revenue influence
5. An "intervention plan" — the specific marketing actions that would move the needle most in the next 30 days
6. A lead volume requirement to hit target given current conversion rates

## Advanced Customizable Version

ROLE:
You are a VP of Revenue Operations and Marketing Analytics with 12+ years of experience scaling B2B SaaS companies from $5M to $100M ARR. You use data from CRM systems (Salesforce, HubSpot), marketing automation platforms, and BI tools to build rolling forecasts that finance and the board can rely on. You apply time-series analysis, cohort-based conversion modeling, and regression-driven attribution.

OBJECTIVE:
Build a comprehensive, boardroom-ready revenue forecast with scenario analysis, pipeline health scoring, and a prescriptive action plan for marketing to influence near-term revenue outcomes.

CONTEXT — COMPANY & PIPELINE DATA:

Business profile:
- Company: [Company Name], a [B2B SaaS / D2C / marketplace / services] business
- Stage: [Seed / Series A / Series B / Growth / Public]
- Industry: [Fintech / HR Tech / DevTools / Healthcare / eCommerce / other]
- Business model: [subscription / transactional / usage-based / project-based]
- Current ARR or monthly revenue: $[X]
- Revenue target for next quarter: $[X]
- Revenue target for next fiscal year: $[X]

Historical revenue data (past 6-12 months):
[Paste monthly revenue figures, e.g.: Jan: $420K, Feb: $445K, Mar: $510K, Apr: $498K, May: $530K, Jun: $575K]

Pipeline data (current snapshot):
- Total open pipeline value: $[X]
- Pipeline by stage:
  - Stage 1 (Awareness/MQL): $[X] value, [X] deals
  - Stage 2 (Discovery/SQL): $[X] value, [X] deals
  - Stage 3 (Evaluation/Demo): $[X] value, [X] deals
  - Stage 4 (Proposal/Negotiation): $[X] value, [X] deals
  - Stage 5 (Closed/Won): $[X] value, [X] deals this quarter
- Average time in each stage: [X] days per stage
- Average deal size by segment: SMB $[X], Mid-Market $[X], Enterprise $[X]

Conversion funnel (trailing 90-day actuals):
- Visitor-to-lead rate: [X]%
- Lead-to-MQL rate: [X]%
- MQL-to-SQL rate: [X]%
- SQL-to-Opportunity rate: [X]%
- Opportunity-to-Close rate: [X]%
- Average sales cycle: [X] days
- Churn rate (if subscription): [X]% monthly / [X]% annual

Marketing channel performance:
[For each channel provide: MQLs generated, Cost per MQL, estimated % of closed revenue influenced]
- Paid Search: [data]
- Paid Social: [data]
- SEO/Organic: [data]
- Email/nurture: [data]
- Webinars/Events: [data]
- Partner/Affiliate: [data]
- Direct/Dark Social: [data]

Expansion revenue data (if applicable):
- Average NRR (Net Revenue Retention): [X]%
- Expansion revenue as % of new ARR: [X]%
- Top upsell triggers: [list behaviors or milestones]

CONSTRAINTS:
- Forecast must be explainable to a non-technical CFO and board
- Distinguish between marketing-influenced pipeline and sales-sourced pipeline
- Flag assumptions clearly so they can be stress-tested
- All scenarios must be internally consistent — no cherry-picking
- Action plan must be executable within 30 days, not aspirational

OUTPUT STRUCTURE — DELIVER ALL SECTIONS:

**1. Revenue Forecast: 90-Day Outlook**
- Base case: revenue projection with key assumptions listed
- Bull case: what would need to be true (+20% upside scenario)
- Bear case: downside risk scenario with trigger conditions
- Confidence interval explanation (what data gaps create uncertainty)
- Month-by-month breakdown for the quarter

**2. Pipeline Coverage Analysis**
- Pipeline coverage ratio (open pipeline / quarterly target)
- Industry benchmark comparison (3x coverage is typical for B2B SaaS)
- Stage-weighted pipeline value (apply historical win rates by stage)
- "Commit" vs. "Best Case" vs. "Pipeline" segmentation
- Warning flags: deals at risk, stale opportunities, stage skipping

**3. Funnel Conversion Diagnostics**
- Visualize the full funnel with drop-off percentages at each stage
- Identify the single biggest conversion bottleneck (constraint theory applied to revenue)
- Benchmark each conversion rate against SaaS industry standards
- Quantify the revenue impact of a 10% improvement at each funnel stage
- Root cause hypotheses for the top 2 underperforming stages

**4. Channel Revenue Attribution**
- Rank channels by closed-won revenue influenced (first-touch, last-touch, and multi-touch)
- Calculate blended CAC per channel
- Identify highest-ROI channels vs. highest-volume channels
- Flag channels with degrading efficiency (rising CPL, falling conversion)
- Recommend budget reallocation to optimize for revenue per dollar spent

**5. Scenario: "What Would It Take?" Analysis**
- To hit the bull case, how many additional MQLs/SQLs are needed?
- If paid spend increased 30%, what incremental revenue would be expected?
- If MQL-to-SQL conversion improved by 5 points, what is the pipeline impact?
- What is the revenue impact of cutting 1 week from the average sales cycle?

**6. 30-Day Marketing Intervention Plan**
- Prioritized list of 5 specific actions marketing can take now to improve near-term revenue
- For each action: expected impact, effort level (Low/Medium/High), and success metric
- Flag any actions that require cross-functional alignment (sales, product, CS)

**7. Leading Indicator Dashboard (Weekly Tracking)**
- The 5 KPIs marketing should track weekly to predict next quarter's revenue
- Alert thresholds: "If X drops below Y, take action Z"
- Recommended review cadence and stakeholder reporting format

## Example Input/Output

**Input Example:**
- Company: Vertex AI (fictional), B2B SaaS HR tech, Series B
- Current ARR: $8.4M ($700K MRR)
- Q3 target: $2.4M in new ARR
- Open pipeline: $6.1M total
- MQL-to-SQL: 22%, SQL-to-close: 28%, avg deal $42K, avg cycle 74 days
- Top channels: SEO (38% of MQLs), Paid Search (27%), Outbound (20%), Events (15%)
- Monthly churn: 1.2%, NRR: 112%

**Output Example (abbreviated):**

Revenue Forecast: Q3

| Scenario | New ARR | Total MRR Exit | Key Assumption |
|----------|---------|----------------|----------------|
| Bear | $1.82M | $851K | Win rate drops to 22%, pipeline slips |
| Base | $2.31M | $892K | Current rates hold, pipeline converts on schedule |
| Bull | $2.78M | $931K | SQL conversion improves to 33%, 2 enterprise deals close |

Pipeline Coverage: 6.1M / 2.4M = 2.54x — BELOW the recommended 3x minimum. Marketing needs to generate ~$1.2M in additional pipeline in the next 30 days to be on track.

Top Bottleneck: MQL-to-SQL conversion at 22% (industry median: 31%). Fixing this single stage delivers $380K in additional pipeline per 100 MQLs — the highest-leverage intervention in the funnel.

30-Day Priority Actions:
1. Launch SQL re-qualification campaign for 90-day stale MQLs (est. +$240K pipeline, Low effort)
2. Deploy 3-touch LinkedIn retargeting for Stage 2 opportunities (est. 15% stage velocity increase)
3. Add ROI calculator to demo booking page (est. +8% demo-to-SQL conversion)
4. Run win/loss interviews on last 15 lost deals to identify objection patterns for sales enablement
5. Accelerate 3 enterprise deals with custom business case documents (est. +$420K pipeline pull-forward)

## Success Metrics
- Forecast accuracy: base case within +/- 15% of actual result
- Pipeline coverage rises to 3x or above within 30 days of intervention
- Top bottleneck conversion rate improves by at least 5 percentage points within 60 days
- Marketing-sourced pipeline as a % of total pipeline is tracked and growing
- CFO/CEO review meeting uses this output as primary revenue planning input

## Related Prompts
- [Marketing Mix Modeling Framework](./Marketing-Mix-Modeling-Framework.md)
- [Funnel Performance Diagnostics](../Campaign-Performance-Analysis/Funnel-Performance-Diagnostics.md)
- [Marketing Attribution ROI Engine](../Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md)
- [Marketing OKR Goal Setting Framework](../KPI-Dashboard-Creation/Marketing-OKR-Goal-Setting-Framework.md)

## Integration Tips
- **HubSpot / Salesforce:** Export pipeline data via "Deals by Stage" report. Paste stage values, counts, and avg deal age directly into the prompt. Run monthly and compare against the prior forecast.
- **Google Sheets:** Paste the output forecast table into a shared Sheet. Use a formula to track actuals vs. projected weekly — trigger a Slack alert via Zapier if actuals fall below the bear case threshold.
- **Notion:** Create a "Revenue Forecasting" database. Store each quarterly run as a linked page with the full output. Tag by scenario and link to the OKR tracker.
- **Looker / Tableau:** Use the channel attribution output to validate or challenge your BI attribution model. Treat the AI forecast as a sanity check layer on top of your existing dashboards.
- **Clari / Gong:** If you use a dedicated forecasting tool, run this prompt in parallel. Compare the AI's stage-weighted pipeline math against Clari's AI — discrepancies reveal data hygiene issues.
- **Zapier automation:** Set a recurring monthly Zap to export HubSpot pipeline data to a Google Sheet row, then trigger a webhook that sends that row to Claude API with this prompt — producing a fresh forecast without manual input.

## Troubleshooting

**Issue: Forecast range is too wide to be useful (bear vs. bull spread is >50%)**
Fix: Your conversion rates are inconsistent month-to-month, which inflates uncertainty. Provide 6 months of monthly conversion data instead of a single average. The model will identify trend direction and tighten the confidence interval.

**Issue: The intervention plan recommends actions that are already in flight**
Fix: Add a "what we're currently doing" section to your context (e.g., "We already run weekly webinars and have an active retargeting campaign"). The prompt will then skip those and focus on untapped levers.

**Issue: Channel attribution doesn't match your CRM data**
Fix: AI attribution is based on the percentages you provide, not raw CRM data. If your CRM shows different revenue influence, use the CRM data as ground truth and ask the AI to "explain the discrepancy between these two attribution views and recommend which to use for planning."

## Version History
- v1.0: Initial creation (auto-generated)
