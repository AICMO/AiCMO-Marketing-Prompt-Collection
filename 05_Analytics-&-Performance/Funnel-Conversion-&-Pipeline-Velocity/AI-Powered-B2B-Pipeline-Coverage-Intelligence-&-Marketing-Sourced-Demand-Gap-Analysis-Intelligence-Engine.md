# AI-Powered B2B Pipeline Coverage Intelligence & Marketing-Sourced Demand Gap Analysis Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, pipeline, revenue-ops, demand-gen, analytics, forecasting, strategy

## Overview

Calculates pipeline coverage ratios by segment, territory, product line, and time horizon; identifies marketing-sourced demand gaps vs. quota requirements; and prescribes specific, volume-targeted demand generation actions to close coverage shortfalls before the quarter closes. Use this every Monday for weekly pipeline reviews and 8+ weeks before quarter-end to course-correct proactively.

## Quick Copy-Paste Version

You are a B2B revenue intelligence analyst. Analyze the following pipeline data and produce a pipeline coverage intelligence report with prescriptive demand generation actions.

PIPELINE INPUTS (paste your data):
- Total quota for current quarter: $[X]M
- Marketing-sourced pipeline open: $[X]M
- Sales-sourced pipeline open: $[X]M
- Average deal size: $[X]K
- Average win rate: [X]%
- Average sales cycle: [X] days
- Weeks remaining in quarter: [X]
- Pipeline by stage (provide breakdown): [Paste stage breakdown]
- Pipeline by segment (Enterprise/Mid-Market/SMB): [Paste segment breakdown]
- Historical quarter coverage ratio at this stage: [X]x

ANALYSIS TASKS:
1. Calculate current coverage ratio by segment and source (marketing vs. sales-sourced)
2. Identify coverage gap in dollars and in number of deals needed
3. Flag pipeline at risk (late-stage deals stalled >30 days, single-threaded deals)
4. Calculate the demand generation volume required (leads, MQLs, SQLs) to hit coverage target assuming current conversion rates
5. Prescribe 3-5 specific, executable marketing actions ranked by impact and speed-to-pipeline
6. Flag which segment/territory has the most critical gap requiring immediate action

Output a structured report with: Executive Summary (3 bullets), Coverage Scorecard (table), Gap Analysis, Risk Flags, and Prescriptive Action Plan with owners and timelines.

## Advanced Customizable Version

# ROLE & CONTEXT
You are a senior Revenue Operations and Demand Generation Intelligence Analyst embedded within the marketing operations function of a [B2B SaaS / B2B Technology / B2B Services] company targeting [Enterprise / Mid-Market / SMB or mixed]. You have deep expertise in pipeline math, coverage modeling, funnel economics, and prescriptive demand generation planning. You think in ratios, conversion rates, and dollar amounts — never vague strategies.

# OBJECTIVE
Produce a complete Pipeline Coverage Intelligence Report that:
1. Diagnoses the current health of the marketing-sourced pipeline vs. quota requirements
2. Identifies specific coverage gaps by segment, territory, and product line
3. Calculates the exact demand generation volume required to close each gap
4. Prescribes ranked, executable marketing actions with expected pipeline contribution and timeline
5. Surfaces pipeline risk factors that could erode the existing coverage ratio

# PIPELINE DATA INPUTS

## Company Context
- Company: [Company Name] — [one sentence description of product/market]
- Current Quarter: [Q3 FY2026 / etc.]
- Fiscal Quarter End Date: [Date]
- Weeks Remaining in Quarter: [X]
- Target Coverage Ratio: [3x / 4x / other — your standard]

## Quota & Bookings Targets
- Total Bookings Quota (Current Quarter): $[X]M
  - Enterprise (>1000 employees): $[X]M
  - Mid-Market (100-999 employees): $[X]M
  - SMB (<100 employees): $[X]M
- New Logo vs. Expansion Split: [X]% new logo / [X]% expansion

## Open Pipeline (Current State)
Provide a breakdown across these dimensions:

### By Source
- Marketing-Sourced (MQL/inbound originated): $[X]M | [X] deals
- Sales-Sourced (SDR/AE outbound): $[X]M | [X] deals
- Partner/Channel-Sourced: $[X]M | [X] deals
- Customer-Sourced (referral, expansion): $[X]M | [X] deals

### By Funnel Stage
- Stage 1 — Discovery/Qualified: $[X]M | [X] deals
- Stage 2 — Evaluation/Demo Completed: $[X]M | [X] deals
- Stage 3 — Proposal/Technical Validation: $[X]M | [X] deals
- Stage 4 — Negotiation/Legal Review: $[X]M | [X] deals
- Stage 5 — Verbal Commit/Closed Won Pending: $[X]M | [X] deals

### By Segment
- Enterprise: $[X]M open | $[X]M quota
- Mid-Market: $[X]M open | $[X]M quota
- SMB: $[X]M open | $[X]M quota

### By Product Line (if applicable)
- [Product A]: $[X]M
- [Product B]: $[X]M

## Funnel Conversion Rates (Historical Actuals)
- Lead-to-MQL: [X]%
- MQL-to-SQL: [X]%
- SQL-to-Opportunity: [X]%
- Opportunity-to-Closed Won (Win Rate): [X]%
  - Enterprise Win Rate: [X]%
  - Mid-Market Win Rate: [X]%
  - SMB Win Rate: [X]%
- Average Sales Cycle (days): [X] days total | [X] Enterprise | [X] MM | [X] SMB
- Average Deal Size: $[X]K total | $[X]K Enterprise | $[X]K MM | $[X]K SMB

## Pipeline Risk Signals
- Deals with no activity in >30 days: [X] deals / $[X]M
- Single-threaded deals (only 1 contact engaged): [X] deals / $[X]M
- Deals with close dates in current quarter but in Stage 1-2: [X] deals / $[X]M
- Deals missing economic buyer contact: [X] deals / $[X]M
- Deals where champion has churned/left: [X] deals / $[X]M

## Active Marketing Programs (Current Quarter)
List current demand generation programs and their expected pipeline contribution:
- [Program 1 — e.g., Webinar Series]: Expected MQLs: [X] | Expected Pipeline: $[X]M
- [Program 2 — e.g., ABM Tier 1 Outreach]: Expected MQLs: [X] | Expected Pipeline: $[X]M
- [Continue for all active programs]

## Historical Benchmarks
- Last Quarter Coverage Ratio at Same Point: [X]x
- Last Quarter Win Rate: [X]%
- Marketing-Sourced Pipeline % of Total (Historical): [X]%
- Marketing-Sourced Pipeline % of Closed Won (Historical): [X]%

# ANALYSIS FRAMEWORK

## Step 1: Coverage Ratio Calculation
For each segment and overall:
- Calculate: Coverage Ratio = Total Open Pipeline / Remaining Quota
- Calculate: Marketing-Sourced Coverage Ratio = Marketing-Sourced Pipeline / Marketing Quota Contribution Target
- Compare to historical benchmarks and target coverage ratio
- Flag any segment below [2.5x] as CRITICAL, [2.5x-3.5x] as AT RISK, [3.5x+] as HEALTHY

## Step 2: Gap Quantification
- Calculate: Pipeline Gap = (Target Coverage Ratio × Remaining Quota) — Total Open Pipeline
- Calculate: Deal Gap = Pipeline Gap / Average Deal Size
- Calculate: MQL Gap = Deal Gap / (MQL-to-Close conversion rate)
- Account for pipeline velocity — deals created after [X weeks before quarter-end] will NOT close this quarter
- Identify the "Point of No Return" date: last date new opportunities can realistically close this quarter

## Step 3: Risk-Adjusted Pipeline
Apply probability-based adjustments:
- Stage 1-2 deals: Apply [20-30]% close probability
- Stage 3 deals: Apply [50-60]% close probability
- Stage 4-5 deals: Apply [75-90]% close probability
- Apply additional risk haircut to: single-threaded deals (-20%), no-activity deals (-30%), champion-churned deals (-50%)
- Calculate: Risk-Adjusted Coverage Ratio

## Step 4: Demand Generation Volume Requirements
Given the gap and current conversion rates, calculate required volume:
- MQLs needed to fill gap: Gap / (MQL-to-Close rate)
- Leads needed: MQLs / (Lead-to-MQL rate)
- By channel if historical channel attribution data is provided
- Flag whether required volume is achievable in the time remaining

## Step 5: Prescriptive Action Plan
Recommend 5-7 specific marketing actions, each including:
- Action description (specific program, not general strategy)
- Target segment and account list (if ABM) or audience definition
- Expected pipeline contribution ($M and # deals)
- Time to pipeline impact (days)
- Resources required (budget, headcount, tools)
- Owner (Marketing, SDR, CS, Partner)
- Priority ranking (Impact × Speed-to-Pipeline / Resource Requirement)

Prioritize actions in this order:
1. Acceleration of existing late-stage deals (fastest to revenue)
2. Reactivation of stalled opportunities
3. Multi-threading existing opportunities to reduce single-thread risk
4. ABM campaigns targeting Tier 1 accounts already in pipeline
5. Net-new demand generation for underperforming segments

# OUTPUT FORMAT

## 1. Executive Coverage Summary (3 bullets, CEO/CFO-ready)
## 2. Pipeline Coverage Scorecard (table by segment)
   | Segment | Open Pipeline | Quota | Coverage Ratio | Status | Gap |
## 3. Risk-Adjusted Pipeline Analysis
## 4. Point of No Return Analysis (deadline for new opp creation)
## 5. Demand Generation Volume Requirements (what marketing must produce)
## 6. Prescriptive Action Plan (ranked table with expected pipeline contribution)
## 7. Weekly Monitoring Cadence (3 metrics to track weekly until quarter-end)

# CONSTRAINTS
- Use only the data provided — do not hallucinate pipeline numbers
- All dollar amounts in millions (M) unless specified otherwise
- Flag explicitly when data inputs are missing and state your assumptions
- Actions must be executable within the remaining quarter timeline
- Prioritize speed-to-pipeline over brand/awareness activities
- Include specific HubSpot/Salesforce report recommendations for ongoing monitoring

## Example Input/Output

**Input Example:**
Company: Meridian Security — cloud-native SIEM platform for mid-market financial services
Quarter: Q2 FY2026 | Quarter End: June 30, 2026 | Weeks Remaining: 7

Quota: $4.2M total — Enterprise $1.8M, Mid-Market $1.6M, SMB $0.8M
Open Pipeline: $9.1M total
  - Marketing-sourced: $4.4M (48%)
  - Sales-sourced: $4.2M (46%)
  - Partner-sourced: $0.5M (6%)

By Segment: Enterprise $3.2M | Mid-Market $4.8M | SMB $1.1M

Win Rate: 24% overall | Enterprise 28% | MM 22% | SMB 19%
ADS: $185K Enterprise | $67K MM | $22K SMB
Avg Sales Cycle: 94 days Enterprise | 52 days MM | 28 days SMB

Risk signals: 14 deals / $2.1M no activity >30 days | 22 deals / $3.4M single-threaded

**Output Example:**

**Executive Coverage Summary:**
- **Current coverage: 2.17x overall** — critically below our 3.5x target; Enterprise at 1.78x is the most urgent gap requiring immediate ABM acceleration
- **Risk-adjusted pipeline drops to $5.8M** after applying stage probability and risk haircuts — representing a $9.07M gap against our coverage target
- **We must create 47 net-new qualified opportunities by May 23** (Point of No Return) to have any chance of closing this quarter; current programs project to deliver only 28

**Coverage Scorecard:**
| Segment | Open Pipeline | Quota | Coverage | Status | Gap vs. 3.5x |
|---|---|---|---|---|---|
| Enterprise | $3.2M | $1.8M | 1.78x | 🔴 CRITICAL | -$3.1M |
| Mid-Market | $4.8M | $1.6M | 3.0x | 🟡 AT RISK | -$0.8M |
| SMB | $1.1M | $0.8M | 1.38x | 🔴 CRITICAL | -$1.7M |
| **Total** | **$9.1M** | **$4.2M** | **2.17x** | 🔴 **CRITICAL** | **-$5.6M** |

**Top 3 Prescriptive Actions:**

1. **Enterprise Multi-Threading Campaign** (Impact: $1.8M | Timeline: 2 weeks)
   - Identify economic buyers and board members at 18 single-threaded enterprise deals using LinkedIn Sales Navigator + ZoomInfo
   - Launch personalized executive outreach with custom ROI analysis for financial services compliance
   - Expected: 8 deals re-engaged, 3 accelerated to Stage 4, $1.2M probability-weighted pipeline recovery

2. **"Stalled Deal" Re-Engagement Sequence** (Impact: $0.9M | Timeline: 1 week)
   - 14 deals with no activity get a 3-touch sequence: personalized video (Loom), relevant case study from peer financial institution, offer of executive briefing with CISO
   - Expected: 30% reactivation rate = 4 deals, $0.9M recovered

3. **Mid-Market ABM Acceleration — Top 25 Accounts** (Impact: $1.1M | Timeline: 3 weeks)
   - Select top 25 Tier 1 MM accounts not yet in pipeline using G2 intent + Bombora signal
   - Deploy direct mail + LinkedIn Sponsored Content + personalized SDR sequence
   - Expected: 12 MQLs, 8 SQLs, 5 opportunities at $67K ADS = $335K new pipeline this quarter

## Success Metrics

- **Coverage Ratio Recovery Rate:** Target 0.3x improvement in coverage per week through program execution
- **Stalled Deal Reactivation Rate:** >25% of at-risk deals re-engaged within 10 days
- **New Opportunity Creation Rate:** Tracking daily vs. Point of No Return volume requirement
- **Risk-Adjusted Coverage Improvement:** Target: move from current risk-adjusted ratio to 2.8x+ by Week 10
- **Marketing-Sourced Pipeline %:** Should be tracking to historical 45-50% of total pipeline; alert if dropping below 38%
- **Pipeline Accuracy:** Stage-weighted close probability should align to actual close rate within ±15%

## Related Prompts

- [Marketing Funnel Conversion & Pipeline Velocity Intelligence Engine](./Marketing-Funnel-Conversion-&-Pipeline-Velocity-Intelligence-Engine.md)
- [AI-Powered Deal Health Scoring & Pipeline Risk Early Warning Intelligence Engine](./AI-Powered-Deal-Health-Scoring-&-Pipeline-Risk-Early-Warning-Intelligence-Engine.md)
- [AI-Powered Revenue Operations RevOps Intelligence & Full-Funnel Alignment Engine](../Marketing-Operations-Analytics/AI-Powered-Revenue-Operations-RevOps-Intelligence-&-Full-Funnel-Alignment-Engine.md)
- [AI-Powered B2B Revenue Attribution Model Architecture & Unified Measurement Framework Intelligence Engine](../Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md)

## Integration Tips

- **Salesforce:** Build a custom Pipeline Coverage Dashboard using `Opportunity` + `Campaign Influence` objects; schedule weekly Apex data export to feed this prompt; use Einstein Analytics to automate stage-weighted coverage ratios
- **HubSpot:** Use the `Deals` API + `Pipeline Stage Conversion Rates` report; create a custom property "Marketing Sourced" boolean on every deal; schedule weekly CSV export and feed directly into this prompt
- **Clari / Gong:** Export Clari's risk signal flags (single-threaded, no activity) directly into the Risk Signals input field to get AI-augmented prescriptions on top of Clari's warnings
- **6sense / Bombora:** Pull intent surge accounts weekly and cross-reference against pipeline gaps by segment — inject these accounts directly into the ABM acceleration action plan
- **Google Sheets / Notion:** Build a weekly "Pipeline War Room" dashboard that auto-populates from Salesforce/HubSpot via Zapier and pastes into this prompt every Monday morning at 9am
- **Slack:** Connect Zapier to post the Executive Summary output to your `#revenue-leadership` Slack channel every Monday — 3 bullets, one table, no fluff

## Troubleshooting

- **Problem:** Coverage ratio looks healthy (3x+) but you're still missing quota consistently.
  **Solution:** Run the risk-adjustment step with conservative probability weights (Stage 1: 15%, Stage 2: 25%) — your "headline" coverage may be masking a bloated, low-quality pipeline. Also audit whether marketing-sourced pipeline is being created with accurate close dates.

- **Problem:** The demand generation volume requirement output seems impossibly large (e.g., 300 MQLs in 6 weeks).
  **Solution:** This is the model surfacing a real structural problem — you cannot fill a large coverage gap in a short quarter. Shift the output to focus on (1) accelerating existing pipeline rather than creating new, and (2) recovery/reactivation over net-new prospecting. Flag this to leadership as a Q3 forecasting risk.

- **Problem:** No historical conversion rate data available to calculate MQL-to-close volume requirements.
  **Solution:** Use industry benchmarks as starting assumptions: B2B SaaS MQL-to-Close ≈ 1-3%, adjust by ACV. For enterprise ($100K+ ACV): use 0.8%. For mid-market ($30-100K): use 1.5%. For SMB (<$30K): use 3%. Note your assumptions explicitly in the output.

## Version History
- v1.0: Initial creation (auto-generated)
