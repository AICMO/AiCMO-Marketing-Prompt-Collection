# AI-Powered B2B SaaS Demand Generation Budget Allocation & Channel Mix Optimization Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** demand generation, budget allocation, channel mix, analytics, revenue operations, CMO, B2B SaaS

## Overview
This prompt builds a data-driven demand generation budget allocation engine that analyzes channel-level performance, models portfolio optimization scenarios, and outputs an AI-ready reallocation plan with specific dollar amounts by channel, quarter, and segment. Use it when entering a new fiscal year, after a QBR, or any time pipeline coverage drops below target.

## Quick Copy-Paste Version

You are a senior demand generation analyst with deep expertise in B2B SaaS marketing mix optimization. Analyze the following channel performance data and produce an optimized budget allocation plan.

CURRENT BUDGET & PERFORMANCE DATA:
- Total DG budget: [e.g., $2.4M annually / $600K quarterly]
- Current channel breakdown: [e.g., Paid Search 30%, LinkedIn Ads 25%, Events 20%, Content/SEO 15%, SDR Outbound 10%]
- Pipeline goal: [e.g., $18M pipeline per quarter, 3x coverage]
- Average deal size: [e.g., $48K ACV]
- Sales cycle: [e.g., 90 days]
- Current MQL-to-pipeline rate by channel: [e.g., Paid Search 22%, LinkedIn 18%, Events 31%, Content 12%, Outbound 28%]
- Cost per pipeline opportunity by channel: [e.g., Paid Search $4,200, LinkedIn $5,800, Events $3,100, Content $6,400, Outbound $2,900]
- Win rate by channel: [e.g., Paid Search 19%, LinkedIn 21%, Events 26%, Content 16%, Outbound 24%]

BUSINESS CONTEXT:
- ICP: [e.g., Series B+ SaaS companies, 200-2000 employees, RevOps/Sales Ops buyers]
- Primary segments: [e.g., Segment A: mid-market $25-75K ACV, Segment B: enterprise $75K+ ACV]
- Key constraint: [e.g., headcount frozen, must stay within current budget envelope]
- Strategic priority: [e.g., accelerate enterprise segment, reduce CAC payback from 18 to 14 months]

Perform:
1. Channel efficiency analysis: rank channels by pipeline ROI, win-rate-weighted CAC, and velocity contribution
2. Reallocation scenario: redistribute budget to maximize pipeline at target coverage ratio
3. Portfolio risk assessment: identify over-concentration and hedge recommendations
4. 90-day reallocation plan: phased budget shifts with specific dollar amounts
5. Expected outcome: projected pipeline delta, new CAC payback, coverage improvement

Output as a structured executive brief with a budget table (channel, current $, proposed $, delta %, rationale) and 3 scenario models (conservative, base, aggressive).

## Advanced Customizable Version

ROLE: You are the AI demand generation intelligence engine for [Company Name], a B2B SaaS company serving [ICP description]. Act as a senior Revenue Marketing Analyst reporting to the CMO, combining the analytical rigor of a McKinsey consultant with the executional expertise of a VP Demand Generation who has managed $5M+ marketing budgets.

OBJECTIVE: Analyze our current demand generation channel portfolio and produce a mathematically-grounded budget reallocation recommendation that maximizes pipeline coverage at our target cost efficiency, with full scenario modeling.

---

## SECTION 1: CHANNEL PERFORMANCE INPUT

Paste your channel data in this format (add/remove channels as needed):

CHANNEL PERFORMANCE MATRIX (Last 2 Quarters Combined):
| Channel | Budget $ | MQLs | CPL $ | Opps Created | CPO $ | Pipe $ | Win Rate | Won ARR $ | CAC $ |
|---------|---------|------|-------|-------------|-------|--------|---------|----------|-------|
| Paid Search (Google) | | | | | | | | | |
| LinkedIn Ads | | | | | | | | | |
| Content Marketing / SEO | | | | | | | | | |
| Field Events & Tradeshows | | | | | | | | | |
| Webinars / Virtual Events | | | | | | | | | |
| SDR Outbound (marketing-sourced) | | | | | | | | | |
| Partner / Channel | | | | | | | | | |
| ABM Display / Intent | | | | | | | | | |
| [Other] | | | | | | | | | |
| **TOTAL** | | | | | | | | | |

---

## SECTION 2: BUSINESS OBJECTIVES & CONSTRAINTS

PIPELINE GOALS (next 2 quarters):
- Pipeline coverage target: [e.g., 4x]
- Total pipeline required: $[X]M
- Marketing-sourced pipeline % target: [e.g., 55%]
- Current marketing-sourced pipeline %: [e.g., 42%]

STRATEGIC PRIORITIES (rank 1-3):
1. [e.g., Accelerate enterprise pipeline (>$75K ACV deals)]
2. [e.g., Reduce blended CAC from $28K to $22K within 2 quarters]
3. [e.g., Expand into [new vertical/geo]]

HARD CONSTRAINTS:
- Total budget ceiling: $[X] (cannot exceed)
- Budget floor by channel (if any): [e.g., Events minimum $150K due to committed contracts]
- Headcount limitations: [e.g., No new hires; SDR team capped at 8]
- Technology constraints: [e.g., HubSpot + Salesforce stack, no new MarTech until Q3]

COMPANY CONTEXT:
- ARR: $[X]M | Growth target: [X]%
- Average ACV: $[X]K | Target ACV: $[X]K
- Median sales cycle: [X] days
- LTV:CAC ratio target: [X]x
- CAC payback target: [X] months

---

## SECTION 3: ANALYTICAL FRAMEWORK

Apply the following frameworks in sequence:

**Framework 1: Channel Efficiency Scoring (weighted composite)**
Score each channel on:
- Pipeline ROI = (Won ARR / Budget) × 100 [weight: 35%]
- Velocity Score = 1 / (median days from MQL to close) [weight: 25%]
- Volume Scalability = marginal efficiency at 2x spend [weight: 20%]
- Strategic Fit = ICP match rate × ACV alignment [weight: 20%]

**Framework 2: Portfolio Optimization (Markowitz-inspired)**
- Identify the efficient frontier: maximum pipeline per dollar at given risk levels
- Flag over-concentrated channels (>30% of budget, <2 channels)
- Recommend minimum diversification: 3 channels each >15% of budget

**Framework 3: Demand Waterfall Alignment (Sirius Decisions / LeanData model)**
Map budget to funnel stages:
- Awareness/Demand Creation channels: target 40% of budget
- Demand Capture channels: target 35% of budget
- Pipeline Acceleration channels: target 25% of budget

**Framework 4: Segment-Level Allocation**
Break allocation by buyer segment:
- Mid-market ([ACV range]): [%] of budget, channels optimized for velocity
- Enterprise ([ACV range]): [%] of budget, channels optimized for quality/ACV

---

## SECTION 4: OUTPUT REQUIREMENTS

Produce the following deliverables:

### OUTPUT A: EXECUTIVE BUDGET REALLOCATION TABLE
| Channel | Current Budget | Current % | Proposed Budget | Proposed % | Change $ | Change % | Rationale (1 sentence) |

### OUTPUT B: THREE SCENARIO MODELS
For each scenario, show: total pipeline generated, pipeline coverage ratio, blended CAC, CAC payback period, win-rate-weighted ROI

**Scenario 1 — Conservative (shift ≤15% of budget)**
- Risk: Low. Incremental optimization within existing channel weights.
- Timeline: Implementable in Q1

**Scenario 2 — Base Case (shift 15-30% of budget)**
- Risk: Medium. Meaningful reallocation with 60-day ramp period.
- Timeline: Implementable Q1-Q2

**Scenario 3 — Aggressive (shift >30% of budget)**
- Risk: High. Channel deprecations and new channel bets.
- Timeline: Q2-Q3 with parallel tracking

### OUTPUT C: 90-DAY IMPLEMENTATION ROADMAP
Week-by-week actions:
- Weeks 1-2: Budget reallocation approvals, vendor/agency briefings
- Weeks 3-6: New channel ramp, creative production, tracking setup
- Weeks 7-10: Performance baselining, first optimization cycle
- Weeks 11-13: Mid-quarter reforecast, budget rebalance triggers

### OUTPUT D: CHANNEL DEPRECATION / INVESTMENT PLAN
For any channel receiving >20% budget cut: provide transition plan
For any channel receiving >20% budget increase: provide scaling playbook with ramp curve

### OUTPUT E: TRACKING DASHBOARD SPEC
List the 8 leading indicators to monitor weekly to confirm reallocation is working:
(Format: Metric | Target | Alert Threshold | Data Source | Owner)

### OUTPUT F: BOARD-READY SUMMARY (3 bullet points)
Translate the recommendation into business outcome language for the CEO/CFO:
- Investment: $X reallocated from Y to Z
- Expected return: $X incremental pipeline, $X CAC improvement
- Risk: What could go wrong and how we'll detect it early

---

## SECTION 5: CHANNEL-SPECIFIC SCALING GUIDANCE

For the top 3 channels in the recommended allocation, provide:
- Marginal efficiency curve: what happens at 1.5x, 2x, 3x current spend
- Tactical levers to activate within 30 days (no new vendor relationships required)
- Leading metric that signals this channel is working BEFORE pipeline data arrives (6-8 week lag)
- Integration: how to sync this channel's data into HubSpot/Salesforce for closed-loop reporting

---

## CONSTRAINTS & QUALITY RULES
- All dollar amounts must be specific (no "approximately" or ranges without rationale)
- Every reallocation must have a data-backed rationale citing at least one metric from the input
- Flag any data gaps that would change the recommendation
- Do not recommend channels not currently in the company's portfolio without explicit justification and 90-day test plan
- Identify the single biggest risk to the recommendation and provide a mitigation plan

## Example Input/Output

**Input (Fictional Company: Nexlayer — B2B SaaS revenue intelligence platform):**

- Total DG budget: $1.8M annually ($450K/quarter)
- Pipeline goal: $12M/quarter, 4x coverage
- Average ACV: $62K, Sales cycle: 95 days
- Channel breakdown & performance:

| Channel | Budget | Opps | CPO | Win Rate | Won ARR |
|---------|--------|------|-----|---------|---------|
| Google Ads | $135K | 28 | $4,821 | 18% | $312K |
| LinkedIn Ads | $112K | 19 | $5,895 | 22% | $259K |
| Field Events | $90K | 31 | $2,903 | 29% | $558K |
| Content/SEO | $67K | 11 | $6,090 | 15% | $102K |
| Outbound SDR | $46K | 17 | $2,706 | 26% | $275K |

**Output (Abbreviated):**

**Executive Finding:** Nexlayer's events channel delivers 2.3x the pipeline ROI of LinkedIn Ads and 1.8x of Google Ads, yet receives only 20% of the budget. Meanwhile, Content/SEO shows the lowest win rate (15%) and highest CPO ($6,090) at a stage where organic is not yet contributing meaningful volume.

**Recommended Reallocation (Base Case):**

| Channel | Current | Proposed | Change | Rationale |
|---------|---------|---------|--------|-----------|
| Field Events | $90K | $148K | +$58K (+64%) | Highest win rate + CPO efficiency; scale to 3 additional regional dinners |
| SDR Outbound | $46K | $78K | +$32K (+70%) | Best CPO at $2,706; add 2 BDR headcount or agency SDRs |
| Google Ads | $135K | $135K | $0 | Maintain volume during ramp; optimize to branded + competitor terms |
| LinkedIn Ads | $112K | $71K | -$41K (-37%) | Reallocate to events/SDR; retain for enterprise retargeting only |
| Content/SEO | $67K | $18K | -$49K (-73%) | Shift to maintenance mode; redirect writing budget to event assets |

**Projected Outcome (Base Case):**
- Pipeline generated: $14.2M/quarter (+$2.2M vs. current)
- Coverage ratio: 4.7x (vs. 4.0x target)
- Blended CAC: $21,400 (vs. $24,800 current, -14%)
- CAC payback: 13.8 months (vs. 17.2 current)

**Leading Indicators to Watch (weeks 1-6):**
1. Event registration rate per invite sent: target >28%
2. SDR connect rate: target >12% (signals list quality)
3. LinkedIn CPM: watch for >20% increase (indicates audience saturation)

## Success Metrics

Rate this prompt's output as high-quality if it delivers:

- **Specificity:** Every channel has exact dollar amounts, not percentages only
- **Traceability:** Every recommendation cites an input metric
- **Actionability:** A junior demand gen manager could implement week 1 actions without additional guidance
- **Risk awareness:** At least 2 "what if we're wrong" scenarios are addressed
- **Executive readability:** Board-ready summary translates to business outcomes, not marketing jargon
- **Completeness:** All 6 output sections are present and populated

Benchmark CPO ranges for B2B SaaS (use to validate outputs):
- Paid Search: $3K-$8K (mid-market), $6K-$18K (enterprise)
- LinkedIn Ads: $5K-$12K (mid-market), $10K-$25K (enterprise)
- Field Events: $2K-$6K (if well-targeted)
- Content/SEO: $4K-$15K (depends on maturity)
- Outbound SDR: $1.5K-$5K (depends on ACV and cycle)

## Related Prompts

- [`../../05_Analytics-&-Performance/Demand-Generation-Program-Analytics/AI-Powered-B2B-SaaS-Demand-Generation-Program-Analytics-&-Pipeline-Coverage-Intelligence-Engine.md`](./AI-Powered-B2B-SaaS-Demand-Generation-Program-Analytics-&-Pipeline-Coverage-Intelligence-Engine.md) — Pipeline coverage analysis that feeds this budget model
- [`../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md`](../Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md) — Attribution model architecture to validate channel contribution
- [`../../05_Analytics-&-Performance/CAC-Payback-&-Unit-Economics-Analytics/AI-Powered-CAC-Channel-Efficiency-&-Marketing-Investment-Optimization-Intelligence-Engine.md`](../CAC-Payback-&-Unit-Economics-Analytics/AI-Powered-CAC-Channel-Efficiency-&-Marketing-Investment-Optimization-Intelligence-Engine.md) — CAC efficiency analysis by channel
- [`../../01_CMO-&-Leadership/Reporting-&-ROI/`](../../01_CMO-&-Leadership/Reporting-&-ROI/) — Board and executive reporting templates that use these budget outputs

## Integration Tips

**HubSpot:**
- Use Custom Report Builder with "Original Source" + "Deal Source" to pull channel-level pipeline data
- Set up Goal Tracking by source to automate MQL-to-pipeline dashboards
- Create a "Channel Mix" dashboard view with CPO, pipeline, and win rate tiles
- Export channel performance CSVs monthly; paste directly into the SECTION 1 table

**Salesforce:**
- Build an Opportunities by Lead Source report filtered by Created Date to get accurate pipeline attribution
- Use Campaign Hierarchy reporting to aggregate paid media under parent campaign objects
- Create a custom field "DG Channel" on Opportunity for marketing-sourced tracking
- SFDC Einstein Analytics (Tableau CRM): build a "Channel ROI" lens with Budget vs. Pipeline

**Google Sheets / Looker Studio:**
- Template: Create one tab per channel with weekly actuals vs. plan; pull into a summary "Allocation" tab
- Looker Studio: connect Salesforce and Google Ads data sources for automated channel efficiency reporting
- Automate weekly data refresh via Zapier or Fivetran for always-current channel metrics

**Zapier / Make.com Automation:**
- Trigger: Weekly Salesforce report export → append to Google Sheets channel tracker
- Alert: If CPO for any channel exceeds threshold → Slack notification to demand gen lead
- Sync: New won opportunity → update channel performance table → trigger reforecast prompt

**Planning Tools (Allocadia, Plannuh, Uptempo):**
- Import proposed budget table directly into Allocadia as a budget scenario
- Use Plannuh for scenario comparison (conservative vs. aggressive) with team collaboration
- Sync approved allocation to Salesforce Campaign Budget fields for closed-loop measurement

## Troubleshooting

**Problem: Channel win rates look identical or suspiciously similar**
*Cause:* Attribution data is likely using first-touch only, which flattens true channel win rates.
*Fix:* Switch to a position-based (W-shaped) or data-driven attribution model in Salesforce/HubSpot. Pull "Influenced Pipeline" data alongside sourced pipeline. If attribution infrastructure doesn't exist, use cohort analysis: look at opportunities where a specific channel touch occurred in the 90 days before close.

**Problem: The model recommends cutting events, but anecdotally they drive our best customers**
*Cause:* Quantitative CPO/win rate metrics miss qualitative signals like expansion revenue, NPS, and champion relationships built at events.
*Fix:* Add an "Expansion Revenue Contribution" column to your channel matrix — pull post-close ARR expansion from accounts where events were a touchpoint. Also factor in LTV, not just ACV. Events often show 30-40% higher LTV due to relationship quality. Run the model with a "strategic premium" multiplier (1.3x) on event win rates to reflect this.

**Problem: Budget reallocation triggers conflict with the sales team over SDR headcount or event sponsorship commitments**
*Cause:* DG budget is not cleanly separated from sales budget in the P&L; events have pre-committed contracts.
*Fix:* Run the model with hard floors on committed spend first (locked contracts, headcount), then optimize only the discretionary portion. Present to sales as "here's how we maximize pipeline from the same total investment" rather than "we're cutting your events." Include the SDR CPO data showing the ROI case for maintaining or growing that investment.

## Version History
- v1.0: Initial creation (auto-generated)
