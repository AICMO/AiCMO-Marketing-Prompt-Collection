# Marketing Pipeline Coverage & Revenue Gap Intelligence Engine - Real-Time Pipeline Health & Marketing Action Planner

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** b2b, analytics, pipeline, revenue, forecasting, demand-gen

## Overview
Analyzes your current marketing-sourced pipeline against revenue targets, calculates coverage ratios by stage, identifies revenue gaps, and generates a prioritized marketing action plan to close those gaps before quarter end. Use this weekly during pipeline reviews or whenever pipeline coverage drops below your target multiple.

## Quick Copy-Paste Version

You are a B2B revenue marketing analyst. Analyze this pipeline data and produce an actionable gap-close plan:

CURRENT QUARTER TARGETS & PIPELINE:
- Revenue target: [e.g., $2.4M ARR new business]
- Marketing-sourced pipeline needed (at your close rate): [e.g., $9.6M at 25% close rate = 4x coverage]
- Current marketing-sourced pipeline: [e.g., $5.8M]
- Pipeline by stage: [Stage 1/Discovery: $X | Stage 2/Demo: $X | Stage 3/Evaluation: $X | Stage 4/Negotiation: $X]
- Average days remaining in quarter: [e.g., 47 days]
- Average sales cycle length: [e.g., 68 days]
- Current close rate by stage: [Stage 1: 12% | Stage 2: 28% | Stage 3: 52% | Stage 4: 78%]
- Marketing-sourced vs. sales-sourced split: [e.g., 58% marketing / 42% sales]

Produce:
1. PIPELINE HEALTH SCORECARD — coverage ratio, weighted pipeline, gap to target, days-adjusted risk score
2. STAGE-BY-STAGE GAP ANALYSIS — which stages are under-supplied and by how much
3. REVENUE AT RISK — deals in late stages that could slip, valued by probability-weighted ARR
4. 30-DAY MARKETING ACTION PLAN — specific campaigns, channels, and plays to generate the missing pipeline, with expected contribution
5. PIPELINE ACCELERATION PLAYS — tactics to advance existing pipeline faster (not just generate new)
6. LEADING INDICATORS TO WATCH — the 3-5 metrics that will tell you if you're on track to close the gap

Format as an executive-ready pipeline review document.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Marketing and pipeline analytics expert with deep expertise in B2B SaaS go-to-market operations. You combine the analytical precision of a RevOps leader with the execution instincts of a demand generation strategist.

CONTEXT:
Company: [Company name]
Segment: [e.g., Mid-Market B2B SaaS, $15K-$80K ACV, 6-week sales cycle]
Quarter: [e.g., Q2 2026, ending June 30]
Days remaining in quarter: [e.g., 52 days]
Primary ICP: [e.g., VP Engineering / CTO at Series B-D SaaS companies, 50-500 employees]

PIPELINE DATA INPUT:
New Business Revenue Target: $[X]
Required pipeline coverage multiple: [e.g., 4x] (based on [X]% blended close rate)
Pipeline required: $[X]

Current Marketing-Sourced Pipeline:
- Total: $[X]
- Stage 1 (MQL → SAL, avg 0-14 days to close): $[X] ([X] deals, avg ACV $[X])
- Stage 2 (Discovery/Demo, avg 15-30 days to close): $[X] ([X] deals, avg ACV $[X])
- Stage 3 (Evaluation/POC, avg 31-50 days to close): $[X] ([X] deals, avg ACV $[X])
- Stage 4 (Negotiation/Legal, avg 51+ days to close): $[X] ([X] deals, avg ACV $[X])

Historical close rates by stage:
- Stage 1 to Close: [X]%
- Stage 2 to Close: [X]%
- Stage 3 to Close: [X]%
- Stage 4 to Close: [X]%

Current Sales-Sourced Pipeline: $[X]
Average deal ACV: $[X]
Top 3 deal sources this quarter: [e.g., inbound SEO, outbound SDR, events]
Current quarter MQL volume vs. target: [X] actual vs. [X] target ([X]% attainment)

COMPETITIVE/MARKET CONTEXT:
[Any external factors affecting pipeline: new competitor, macro headwinds, seasonality, recent product launch]

AVAILABLE MARKETING LEVERS (next 30 days):
Budget available for gap-close: $[X]
Active campaigns: [list]
Events/webinars planned: [list]
SDR capacity: [X] reps, [X] sequences/day
Paid media budget remaining: $[X]/channel
Content/sales assets in flight: [list]

ANALYSIS REQUIRED:

**MODULE 1: PIPELINE HEALTH SCORECARD**
Calculate and display:
- Weighted pipeline (probability-adjusted by stage)
- Coverage ratio: current vs. required
- Revenue gap: weighted pipeline vs. Q target
- Time-adjusted gap (accounting for remaining days vs. avg cycle length)
- Slippage risk score: % of pipeline with close dates beyond quarter end
- Marketing contribution percentage vs. company benchmark
- Pipeline velocity: avg days in each stage vs. historical benchmark
- Forecast range: bear / base / bull case with confidence intervals

**MODULE 2: STAGE-BY-STAGE GAP ANALYSIS**
For each pipeline stage:
- Current supply vs. required supply (working backwards from target)
- Gap in number of deals and dollar value
- Time-to-revenue feasibility (can Stage 1 deals close this quarter given cycle length?)
- Which stages are bottlenecks vs. accelerators
- Root cause hypothesis for any stage imbalances

**MODULE 3: DEAL-LEVEL RISK ASSESSMENT**
Identify revenue at risk:
- Deals with stale activity (no touchpoint in [X] days)
- Deals with close dates that conflict with average cycle length
- Deals missing key stakeholders (single-threaded)
- Deals with no mutual action plan or next step
- Competitive displacement risk signals
- Prioritized "save list" with recommended actions per deal

**MODULE 4: 30-DAY MARKETING ACTION PLAN**
For each recommended action provide:
- Specific tactic (not vague categories)
- Target segment and ICP match
- Expected pipeline contribution ($) and timeline
- Resource requirement (budget, headcount, days to launch)
- Historical or benchmark conversion data to support the projection
- Execution owner (marketing, SDR, CS, product)

Prioritize tactics using an ICE framework (Impact × Confidence × Ease) and rank top 5.

Include plays across:
- Net-new pipeline generation (demand capture and demand creation)
- Pipeline acceleration (moving existing deals forward)
- Expansion pipeline (upsell/cross-sell from existing customer base if applicable)
- Competitive displacement (if applicable)

**MODULE 5: PIPELINE ACCELERATION PLAYBOOK**
For deals already in pipeline:
- Personalized nurture sequences by stage and persona
- Executive-to-executive (EE) outreach triggers
- ROI/business case content for evaluation-stage deals
- Social proof and reference programs for negotiation-stage deals
- Urgency creation tactics (without discounting): mutual close plans, implementation scheduling, exec sponsorship
- Specific email subject lines, LinkedIn message templates, or call scripts for the top 3 acceleration plays

**MODULE 6: LEADING INDICATOR DASHBOARD**
Define the weekly "pipeline pulse check":
- 5 metrics to track weekly (not lagging revenue metrics)
- Target ranges for each metric to stay on track
- Alert thresholds that trigger escalation
- The single most important "canary metric" — the first signal of pipeline health or distress
- Recommended Slack/email alert logic for RevOps to implement

**MODULE 7: EXECUTIVE NARRATIVE**
Write a 150-word "state of pipeline" summary for the CMO/CRO weekly revenue review:
- Current position vs. target
- Top 2-3 risks with mitigation status
- Key wins / positive signals
- Ask: what decisions or resources are needed from leadership

OUTPUT FORMAT:
- Start with a 3-line "TL;DR" status box (Green/Yellow/Red rating, coverage ratio, key ask)
- Use tables for scorecards and metrics
- Bullet points for action items with owners and dates
- Bold the single most important insight in each module
- End with a "If we do nothing different" scenario and an "If we execute the action plan" scenario

CONSTRAINTS:
- Every pipeline contribution projection must include an assumption set
- Flag any tactic that requires >2 weeks to show pipeline impact as "Q+1 investment"
- No generic advice — tie every recommendation to the specific data inputs provided
- Identify the 20% of actions likely to produce 80% of the gap-close result

## Example Input/Output

**Input Example:**

Company: Velara AI (B2B SaaS, AI-powered contract management)
Q2 Target: $1.8M new ARR
Required coverage: 4x at 25% close rate = $7.2M pipeline needed
Current marketing-sourced pipeline: $4.1M
Stage breakdown: Stage 1: $1.2M (18 deals) | Stage 2: $1.6M (12 deals) | Stage 3: $900K (7 deals) | Stage 4: $400K (3 deals)
Days remaining: 41 days | Avg sales cycle: 55 days
MQL attainment: 62% of target (187 MQLs vs. 300 target)
Available gap-close budget: $85K | Paid media remaining: $40K Google/LinkedIn

**Output Example (excerpted):**

---
**PIPELINE STATUS: 🔴 CRITICAL**
Coverage ratio: 1.7x (target: 4x) | Weighted pipeline: $892K | Gap to target: $908K | Days-adjusted: Stage 1 and 2 cannot close in 41 days given 55-day cycle

**TL;DR:** Velara AI is $908K weighted-pipeline short of Q2 revenue target. Stage 1 and 2 pipeline ($2.8M) is unlikely to close this quarter given a 55-day average cycle and only 41 days remaining. **Real closeable pipeline is $1.3M (72% of target).** Immediate focus must shift to accelerating Stage 3/4 deals ($1.3M) and running parallel Q3 pipeline generation.

---

**MODULE 1 SCORECARD:**

| Metric | Current | Target | Status |
|--------|---------|--------|--------|
| Total Mktg Pipeline | $4.1M | $7.2M | 🔴 57% |
| Weighted Pipeline | $892K | $1.8M | 🔴 50% |
| Coverage Ratio | 1.7x | 4x | 🔴 |
| Stage 3+ (Closeable) | $1.3M | $1.8M | 🟡 72% |
| MQL Attainment | 62% | 100% | 🔴 |
| Pipeline Velocity | 71 days avg | 55 days | 🔴 Slowing |

---

**TOP 5 GAP-CLOSE ACTIONS (ICE Scored):**

1. **Launch "Rapid ROI" ABM sequence for Stage 3 deals** (7 deals, $900K) — ICE: 9/10
   - Tactic: 3-touch sequence (CFO email → ROI calculator → exec reference call) over 10 days
   - Owner: Marketing + AEs
   - Expected contribution: $360K-540K closed (40-60% pull-through)
   - Launch: Day 1-2

2. **Activate 12 "champion gone dark" deals in Stage 2** — ICE: 8/10
   - Tactic: Champion re-engagement via LinkedIn + personalized video (Loom) from AE
   - Expected contribution: $320K pipeline acceleration, 3-4 deals moved to Stage 3
   - Budget: $0 (AE time only)

3. **LinkedIn ABM retargeting for Stage 1 ICP accounts (1,200 targets)** — ICE: 7/10
   - Tactic: Conversation Ads with "book a 15-min ROI session" CTA to Stage 1 contacts
   - Budget: $18K over 3 weeks
   - Expected contribution: 8-12 new Stage 2 entries ($640K-$960K pipeline, Q3 closeable)

---

## Success Metrics

- Coverage ratio reaches or exceeds 3.5x within 3 weeks of executing action plan
- Stage 3+ pipeline increases by at least 20% within 30 days
- Weekly MQL volume returns to ≥90% of target within 2 weeks
- At least 3 "gone dark" Stage 2 deals show activity signal within 14 days
- Weighted pipeline forecast accuracy within 15% of actual close rate

## Related Prompts

- `../../05_Analytics-&-Performance/Revenue-Forecasting-&-Pipeline-Intelligence/Predictive-Revenue-Forecasting-&-Marketing-Pipeline-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Revenue-Backed-Demand-Generation-Planning-&-Campaign-Architecture-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Demand-Generation-Waterfall-&-Pipeline-Coverage-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Funnel-Conversion-&-Pipeline-Velocity/Pipeline-Stage-Conversion-Optimization-&-Revenue-Leak-Detection-Engine.md`

## Integration Tips

- **Salesforce / HubSpot CRM:** Pull Stage, Amount, Close Date, Last Activity Date into a spreadsheet and paste the structured data table directly into the prompt. Run weekly as part of pipeline review prep.
- **Gong / Chorus:** Use call intelligence data to identify "gone dark" deal risk signals before running Module 3.
- **6sense / Bombora:** Feed intent signal data into the ABM sequence recommendations in Module 4 to prioritize which accounts to re-engage.
- **Google Sheets automation:** Create a Zapier/Make workflow that exports CRM pipeline data weekly and triggers this prompt via Claude API, then posts the Module 7 executive summary to Slack #revenue-ops.
- **Tableau / Looker:** Use the Module 6 leading indicator definitions to build a persistent pipeline pulse dashboard with the recommended alert thresholds.
- **Notion / Confluence:** Store Module 4 action plans as recurring sprint tasks with owners and due dates for weekly accountability.

## Troubleshooting

**Issue: The weighted pipeline numbers don't match my CRM's forecast**
Solution: Reconcile close rate assumptions — CRM forecasts often use manager-adjusted probability rather than historical stage close rates. Explicitly input your historical close-by-stage data rather than relying on opportunity probability fields, which are often manually set by reps.

**Issue: The 30-day action plan recommends tactics that require more than 30 days to produce pipeline**
Solution: Add the constraint "only include tactics that can generate Stage 2+ pipeline within [X] days given our [Y]-day sales cycle." For short-quarter scenarios, focus the prompt on pipeline acceleration (existing pipeline) rather than net-new generation, as new MQLs rarely close within the same quarter for mid-market+ deals.

**Issue: Output is too generic and doesn't reflect our specific ICP or market**
Solution: Populate the COMPETITIVE/MARKET CONTEXT field with 2-3 specific details unique to your situation (recent competitor funding round, a macro headwind, a product launch advantage). The more specific the context, the more targeted the recommendations — especially for Module 4 tactic selection.

## Version History
- v1.0: Initial creation (auto-generated)
