# AI-Powered B2B SaaS Pipeline Coverage Analytics & Quarterly Revenue Gap Intelligence Engine - Know Exactly When You're Undershooting Your Number Before It's Too Late

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** pipeline coverage, revenue forecasting, pipeline gap analysis, quota attainment, revenue operations, marketing planning, demand generation, pipeline health, RevOps, forecast accuracy, B2B SaaS, pipeline analytics, CMO reporting

## Overview
Deploys an AI-powered pipeline coverage analysis and gap intelligence system that tells marketing exactly how much pipeline they need to generate — broken down by territory, segment, and quarter — and automatically triggers the right demand generation programs when coverage ratios fall below safe thresholds. Use this when you need to move from reactive pipeline panic to proactive coverage management, or when the CMO needs to own a credible revenue forecast conversation with the CRO.

## Quick Copy-Paste Version

You are a B2B SaaS revenue operations and marketing analytics expert. Analyze our pipeline coverage and build an intelligent gap detection and response system.

COMPANY CONTEXT:
- Company: [e.g., "Northbeam Analytics — AI-powered attribution platform for mid-market and enterprise DTC brands"]
- Fiscal year structure: [e.g., "Q4 ends December 31. We are currently in Week 6 of Q3."]
- Revenue target: [e.g., "$18M ARR target for FY2026. Q3 target is $4.2M new ARR. Q4 target is $5.1M new ARR."]
- Current pipeline: [e.g., "Total open pipeline: $14.8M. Stage 1-2 (Early): $6.2M. Stage 3-4 (Mid): $5.1M. Stage 5-6 (Late): $3.5M. Avg win rate: 24%. Avg sales cycle: 82 days."]
- Sales segments: [e.g., "SMB ($0-50K ACV), Mid-Market ($50K-150K ACV), Enterprise ($150K+ ACV). Three AE territories: East, West, Strategic."]
- Marketing programs available: [e.g., "Webinars, content syndication, paid LinkedIn, partner co-marketing, events, ABM campaigns, cold outbound via SDR team"]

BUILD THIS PIPELINE COVERAGE INTELLIGENCE SYSTEM:
1. COVERAGE RATIO CALCULATION: Compute current pipeline coverage ratio by quarter and segment using formula (Open Pipeline × Stage-Weighted Win Rate ÷ Revenue Target). Flag segments where coverage falls below 3x (warning) and 2.5x (critical) thresholds. Show me where I'm exposed.
2. GAP QUANTIFICATION: Calculate the net-new pipeline I must generate to close the gap to safe coverage, accounting for pipeline aging decay (deals >60 days in stage lose 15% win probability per 30 days), expected pipeline attrition (historical push/slip rate), and average time-to-qualify for new pipeline entering this quarter.
3. TERRITORY AND SEGMENT BREAKDOWN: Decompose coverage gaps by territory (East/West/Strategic), deal size segment (SMB/Mid-Market/Enterprise), and pipeline stage. Identify which specific gaps are coverage gaps (not enough deals) vs. conversion gaps (enough deals but low win rate) vs. velocity gaps (deals moving too slowly to close in quarter).
4. MARKETING RESPONSE PLAYBOOK: For each gap type and segment, prescribe the optimal marketing response — which programs generate qualified pipeline fastest for each segment, estimated pipeline contribution per program, lead time to pipeline from each program type, and required investment to close the gap.
5. WEEKLY COVERAGE MONITOR: Design the monitoring cadence and alert logic — what triggers an automatic marketing response escalation, who is alerted, and what actions are pre-approved to deploy within 48 hours when coverage drops to warning threshold.
6. FORECAST CONFIDENCE MODEL: Build a coverage-adjusted revenue forecast that shows the CMO and CRO the range of likely outcomes (base case, upside, downside) based on current pipeline coverage, average win rate volatility, and historical quarter-end pipeline conversion rates.

OUTPUT FORMAT:
- Coverage ratio dashboard by quarter, segment, and territory (table with RAG status)
- Net-new pipeline gap calculation with confidence intervals
- Gap type classification (coverage vs. conversion vs. velocity) per segment
- Marketing response menu with pipeline contribution estimates and lead times
- Coverage alert thresholds and escalation decision tree
- Revenue forecast scenarios with coverage-adjusted probability ranges
- 12-week marketing execution calendar to close identified gaps

## Advanced Customizable Version

ROLE: You are a senior B2B SaaS revenue operations strategist and CMO advisor with 17+ years building pipeline forecasting and coverage management systems at companies ranging from $5M to $500M ARR. You have operated in high-growth environments where marketing owned a defined pipeline coverage commitment to the CRO — not just a "sourcing" percentage, but a specific dollar amount of healthy, stage-appropriate pipeline, maintained at defined coverage ratios throughout the quarter. You've seen the pattern repeatedly: companies that manage pipeline coverage proactively (monitoring ratios weekly, triggering programs at the first warning signal) consistently outperform companies that react to pipeline gaps in the final four weeks of the quarter when there is no longer time to generate qualified pipeline from scratch. You understand the mathematics of pipeline health — how stage-weighted win rates, aging decay curves, attrition rates, and time-to-qualify constraints compound to create revenue variance — and how to translate that math into specific, time-bounded marketing actions. You've built these systems in Salesforce, HubSpot, and custom BI tools, and you know which levers marketing can realistically pull in a 6-week window vs. a 12-week window.

OBJECTIVE: Design a production-ready pipeline coverage analytics and gap intelligence system that:
- Establishes mathematically rigorous coverage ratio baselines with stage-weighted win rate adjustments that reflect actual close probability, not CRM stage labels
- Decomposes coverage gaps into their root cause (insufficient volume, insufficient conversion rate, insufficient velocity) so marketing deploys the right program for the right problem
- Builds a territory and segment-level coverage view that gives the CMO credible visibility into which parts of the business are at risk and which are healthy
- Creates an early-warning alert system that triggers pre-approved marketing responses at defined coverage thresholds before gaps become unrecoverable
- Generates a coverage-adjusted revenue forecast that can withstand a rigorous CRO review — showing base case, upside scenario, and downside risk with the specific assumptions behind each
- Produces a marketing program response menu calibrated to actual pipeline contribution rates and realistic lead times for each program type and segment

CONTEXT VARIABLES (fill in before running):

COMPANY FUNDAMENTALS:
- Company name and product: [e.g., "Corvia — B2B data enrichment platform for revenue operations teams at Series A-C SaaS companies"]
- Revenue model: [ARR/MRR, new logo vs. expansion split, average ACV by segment]
- Fiscal year and current position: [e.g., "FY runs Jan-Dec. Currently Week 8 of Q3 (mid-August)"]
- Q3 target: [$ new ARR], Q4 target: [$ new ARR], full-year target: [$ new ARR]
- How targets are structured: [by AE territory, by segment, by product line, or combined]

CURRENT PIPELINE STATE:
- Total open pipeline by stage: [Stage 1: $X, Stage 2: $X, Stage 3: $X, Stage 4: $X, Stage 5: $X]
- Stage definitions: [e.g., "Stage 1: Discovery call scheduled, Stage 2: Discovery completed/demo booked, Stage 3: Demo completed/proposal sent, Stage 4: Procurement/legal review, Stage 5: Verbal commit/contract out"]
- Historical win rates by stage: [e.g., "Stage 1: 12%, Stage 2: 22%, Stage 3: 38%, Stage 4: 67%, Stage 5: 88%"]
- Average days-in-stage by stage: [e.g., "Stage 1: 14d, Stage 2: 18d, Stage 3: 21d, Stage 4: 19d, Stage 5: 8d"]
- Historical pipeline attrition rate: [e.g., "Q2 historical: 18% of pipeline at Week 8 slips to following quarter"]
- Historical aging decay: [e.g., "Deals >90 days old close at 40% of their predicted win rate"]

PIPELINE SEGMENTS:
- Geographic territories: [e.g., "North America East (AE1), North America West (AE2), EMEA (AE3), Strategic Accounts (AE4/AE5)"]
- Deal size segments with ACV ranges: [e.g., "SMB: $8K-$25K ACV, Mid-Market: $25K-$80K ACV, Enterprise: $80K+ ACV"]
- Current pipeline by territory and segment: [populate the matrix]
- Win rates by segment: [e.g., "SMB: 31%, Mid-Market: 24%, Enterprise: 19%"]
- Average sales cycle by segment: [e.g., "SMB: 45 days, Mid-Market: 72 days, Enterprise: 110 days"]

MARKETING PROGRAM INVENTORY:
- Active programs and their pipeline contribution rates: [e.g., "Webinars: $280K pipeline/event on 8-week lag, Paid LinkedIn: $95K pipeline/month on 6-week lag, Content syndication: $140K pipeline/quarter on 10-week lag"]
- Programs that can be spun up in <2 weeks: [list]
- Programs that require 4-6 week lead time: [list]
- Programs with 6-12 week lead time to pipeline: [list]
- Current Q budget remaining and approved programs: [e.g., "$180K remaining Q3 budget, no new budget approvals needed for programs under $40K"]
- SDR capacity: [e.g., "4 SDRs, current utilization 78%, can absorb up to 40% more inbound MQLs without headcount change"]

COVERAGE THRESHOLDS (define your risk tolerance):
- Safe coverage ratio: [e.g., "3.5x for SMB (fast cycle, high volume), 3.0x for Mid-Market, 4.0x for Enterprise (long cycle, high variance)"]
- Warning threshold (triggers marketing response): [e.g., "Below 2.8x for SMB, 2.5x for Mid-Market, 3.2x for Enterprise"]
- Critical threshold (triggers escalation to CMO/CRO): [e.g., "Below 2.2x for any segment"]
- Pipeline freshness requirement: [e.g., "No more than 30% of pipeline can be >60 days old at any stage"]

ANALYTICAL FRAMEWORK — EXECUTE THESE ANALYSES:

PHASE 1: COVERAGE BASELINE CONSTRUCTION
1. Stage-Weighted Pipeline Value: Calculate the risk-adjusted value of each pipeline stage using stage-specific win rates (not face value). Build the weighted pipeline table by territory × segment × stage.
2. Coverage Ratio by Dimension: Calculate coverage ratios for (a) Q3 close target, (b) Q4 close target, (c) combined H2 target. Flag each dimension with RAG status based on thresholds above.
3. Pipeline Age Audit: Identify the % of pipeline in each segment and stage that exceeds the aging threshold. Apply the aging decay factor to calculate effective weighted pipeline (vs. nominal weighted pipeline). Show the gap between nominal and effective pipeline.
4. Attrition Adjustment: Apply historical attrition rates to project expected end-of-quarter pipeline survival. Show the adjusted pipeline available for in-quarter close vs. the target.

PHASE 2: GAP ROOT CAUSE ANALYSIS
5. Gap Type Classification: For each segment where coverage is below threshold, classify the gap as:
   - VOLUME GAP: Insufficient number of deals entering pipeline (fix: top-of-funnel demand programs)
   - CONVERSION GAP: Enough deals but too many are lost at specific stages (fix: sales enablement, proof content, stage-specific intervention)
   - VELOCITY GAP: Enough deals at right win rates but moving too slowly to close in quarter (fix: deal acceleration content, executive engagement, urgency creation)
   - QUALITY GAP: Deal volume looks OK but win rates are below historical benchmarks (fix: ICP tightening, lead scoring recalibration, discovery improvement)
6. Gap Severity Scoring: For each identified gap, calculate (a) $ pipeline gap to reach safe coverage, (b) weeks remaining in quarter, (c) lead time for available programs, (d) $ pipeline achievable within time constraint = RECOVERABLE vs. UNRECOVERABLE gap.

PHASE 3: MARKETING RESPONSE DESIGN
7. Program Selection Matrix: For each gap type and segment, select the optimal marketing response from the program inventory based on:
   - Pipeline contribution rate vs. gap size
   - Lead time to pipeline vs. weeks remaining
   - Budget requirement vs. available budget
   - SDR capacity to work inbound leads generated
8. Response Prioritization: Rank recommended programs by expected ROI (pipeline generated ÷ cost × urgency factor). Show the optimized program mix that closes the maximum recoverable gap with available budget.
9. Pre-Approved Response Playbook: Design three pre-approved response packages — (a) Warning Protocol ($0-$25K investment, <2 week deployment), (b) Escalation Protocol ($25K-$75K, <4 week deployment), (c) Crisis Protocol ($75K+, <6 week deployment) — with specific program recipes for each segment.

PHASE 4: FORECASTING AND REPORTING
10. Coverage-Adjusted Revenue Forecast: Build the three-scenario forecast model:
    - Base Case: Current pipeline × stage-weighted win rates × attrition factor + planned new pipeline from approved programs
    - Upside: Base Case + 15% win rate improvement from sales enablement actions + 20% more pipeline if Warning Protocol activated immediately
    - Downside: Base Case − 20% (historical worst-case attrition) − 10% win rate degradation (competitive pressure)
11. CMO-CRO Reporting Package: Design the weekly coverage report that the CMO brings to the CRO — coverage ratios by segment, gap breakdown, marketing response actions taken, expected pipeline contribution on 4-week and 8-week horizons, and 90-day forecast confidence band.
12. Alert Automation Spec: Define the CRM report and alert logic — which Salesforce reports and dashboard views to configure, what triggers an automated Slack/email alert, and the escalation chain (Marketing Ops → Demand Gen Manager → CMO → CRO).

OUTPUTS — PRODUCE THESE DELIVERABLES:
1. Pipeline Coverage Dashboard (table): Territory × Segment × Stage matrix with nominal pipeline, stage-weighted pipeline, effective (aging-adjusted) pipeline, coverage ratio, and RAG status
2. Gap Analysis Summary: Gap type classification (Volume/Conversion/Velocity/Quality) with $ gap amount, recoverability assessment (Yes/Partial/No based on time remaining), and confidence in gap estimate
3. Marketing Response Menu: Prioritized program recommendations by gap type with expected pipeline contribution, deployment timeline, investment required, and capacity requirements
4. Pre-Approved Response Playbooks: Three-tier playbook (Warning/Escalation/Crisis) with specific program recipes per segment
5. Coverage-Adjusted Revenue Forecast: Three-scenario model (Base/Upside/Downside) with key assumptions made explicit
6. CMO-CRO Weekly Report Template: One-page format covering coverage health, gap trend (improving/stable/deteriorating), marketing actions, and outlook
7. Alert Specification: CRM query logic, threshold values, alert triggers, and escalation chain for automated monitoring

CONSTRAINTS:
- Every recommendation must respect the realistic lead time from program launch to qualified pipeline creation — do not recommend programs that cannot materially contribute to in-quarter pipeline given weeks remaining
- Account for SDR capacity when recommending inbound demand programs — pipeline that can't be worked is not recoverable pipeline
- Flag any assumptions made about conversion rates, attrition rates, or program contribution rates — and provide sensitivity analysis showing how the gap changes if key assumptions are off by ±20%
- Distinguish sharply between pipeline that can close this quarter and pipeline that can close next quarter — do not mix Q3 and Q4 pipeline in the same coverage calculation without labeling clearly

FORMATTING:
- Lead with the coverage dashboard table — the most time-pressed reader (CRO in a pipeline review meeting) must be able to read the health status in 30 seconds
- Use RAG color coding (🔴 Critical / 🟡 Warning / 🟢 Healthy) throughout
- Present the gap analysis as a ranked list by severity and recoverability
- Format program recommendations as a decision matrix, not a paragraph
- The forecast should show ranges, not point estimates — confidence bands communicate honesty about uncertainty

## Example Input/Output

**Input Example:**
- Company: Meridian HRTech — AI-powered workforce planning platform for CHROs at enterprise companies (2,000+ employees)
- Current position: Week 7 of Q3, FY ends December 31
- Q3 target: $3.8M new ARR; Q4 target: $4.6M new ARR
- Pipeline: Stage 1: $4.2M / Stage 2: $3.1M / Stage 3: $2.8M / Stage 4: $1.4M / Stage 5: $0.6M (total $12.1M nominal)
- Stage win rates: 8% / 19% / 36% / 71% / 92%
- Segments: SMB ($15K-40K ACV, 55-day cycle), Mid-Market ($40K-120K ACV, 85-day cycle), Enterprise ($120K+ ACV, 130-day cycle)
- Available programs: Quarterly CHRO executive roundtables (6-week lead, $180K pipeline/event), LinkedIn paid (4-week lead, $65K/month pipeline contribution), ABM cluster campaigns for named accounts (3-week lead, $95K pipeline per cluster), partner co-marketing with HRIS platforms (8-week lead, $220K pipeline per activation)
- Budget remaining: $95K approved, $180K available with CRO sign-off

**Output Example (excerpt):**

**PIPELINE COVERAGE DASHBOARD**

| Segment | Nominal Pipeline | Stage-Weighted | Aging-Adjusted | Q3 Coverage | Status |
|---------|-----------------|----------------|----------------|-------------|--------|
| SMB | $2.8M | $540K | $461K | 1.8x | 🔴 Critical |
| Mid-Market | $5.9M | $1.38M | $1.21M | 2.2x | 🟡 Warning |
| Enterprise | $3.4M | $728K | $618K | 4.1x | 🟢 Healthy |
| **TOTAL** | **$12.1M** | **$2.65M** | **$2.29M** | **2.4x** | **🟡 Warning** |

**Q3 SAFE COVERAGE TARGET: 3.2x weighted → requires $3.8M × 3.2 = $12.2M weighted pipeline**

**RECOVERY MATH:**
- Current effective weighted pipeline: $2.29M
- Safe coverage requires: $3.8M × 3.2x = $12.16M weighted
- Gap in weighted pipeline: $9.87M weighted
- At average Stage 2 win rate (19%): requires ~$52M nominal pipeline to generate gap coverage — NOT ACHIEVABLE in 5 weeks

**RECOVERABLE GAP ANALYSIS:**
SMB Segment — VELOCITY GAP + VOLUME GAP (Critical)
- Root cause: 67% of SMB pipeline is in Stage 1-2 (pre-demo), insufficient to close in Q3 (55-day cycle, only 5 weeks remain)
- Q3 opportunity: Push high-Stage-2 deals to close; remainder feeds Q4 coverage
- Recommended response: (1) SDR-focused acceleration email series for 14 Stage-2 SMB deals + demo follow-up content → target +$280K weighted pipeline converted to Stage 4 within 3 weeks. (2) Launch LinkedIn demand program immediately for Q4 pipeline build.

Mid-Market Segment — CONVERSION GAP (Warning)
- Root cause: Stage 2→3 conversion rate is 31% vs. historical 44% — deals stalling post-discovery before demo
- Root cause hypothesis: Proposal quality or ROI substantiation weakness
- Recommended response: Deploy ROI calculator + CFO-facing business case template to all 22 Stage-2 Mid-Market deals within 72 hours. Expected impact: +6-8 deals advancing to Stage 3 → +$480K weighted pipeline recoverable for Q3.

**PRE-APPROVED WARNING PROTOCOL ACTIVATED (Week 7):**
1. SDR deal acceleration sequence (SMB + Mid-Market Stage 2) — deploy within 48 hours, $0 incremental cost
2. ROI calculator deployment to stalled Stage-2 Mid-Market deals — deploy within 72 hours, $0 incremental cost
3. LinkedIn demand gen increase for Q4 pipeline — activate $45K/month (within approved budget), 4-week lag to Q4 pipeline

**PROJECTED OUTCOME:**
Base Case Q3: $2.6M-$2.9M (68-76% attainment)
Upside Q3: $3.1M-$3.4M (82-89% attainment) if all acceleration actions execute and 50% of protocols generate expected pipeline advance
Q4 forecast: On track at $4.2M-$4.8M if Q4 pipeline build programs activated in Week 7-8

## Success Metrics

- **Coverage ratio accuracy**: Effective (aging-adjusted) coverage ratios predict quarter-end attainment within ±12% at Week 8 of quarter
- **Alert trigger success rate**: Warning protocol activations result in measurable coverage ratio improvement within 21 days in >70% of cases
- **Forecast confidence**: Three-scenario forecast at Week 8 contains actual quarter-end result in >80% of quarters
- **Gap recoverability classification accuracy**: Gaps classified as "recoverable" close at ≥60% of projected rate when recommended programs execute
- **Program contribution accuracy**: Actual pipeline generated by recommended programs vs. estimated contribution within ±25%
- **CMO-CRO alignment**: CRO accepts coverage-adjusted forecast as primary planning tool within 2 quarters of implementation

## Related Prompts

- [Pipeline Velocity Analytics & Deal Acceleration](./AI-Powered-B2B-SaaS-Pipeline-Velocity-Analytics-&-Marketing-Led-Deal-Acceleration-Revenue-Intelligence-Engine.md) — companion prompt focused on deal speed rather than coverage quantity
- [CMO Pipeline Gap Diagnosis & Revenue Sprint](../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-B2B-CMO-Pipeline-Gap-Diagnosis-&-Revenue-Sprint-Marketing-Intelligence-Engine.md) — CMO-level strategic response when pipeline is severely undershooting
- [Demand Generation Program Portfolio Management](../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Demand-Generation-Program-Portfolio-Management-&-Autonomous-Revenue-Program-Optimization-Intelligence-Engine.md) — program selection and portfolio optimization
- [Marketing Pipeline Quality Intelligence](../Revenue-Operations-Analytics/AI-Powered-B2B-SaaS-Marketing-Pipeline-Quality-Intelligence-&-MQL-to-Revenue-Accountability-Engine.md) — pipeline quality and MQL accountability companion

## Integration Tips

- **Salesforce**: Build the coverage dashboard as a Salesforce Analytics Studio dashboard. Create three core reports: (1) Pipeline by Stage×Territory×Segment with close date filter, (2) Opportunity Age Report with stage entry date, (3) Stage Conversion Rate Report (rolling 90 days). Set up Einstein Analytics alerts for coverage threshold breaches.
- **HubSpot**: Use Deal Stage report with weighted pipeline value (configure custom property for stage probability × deal amount). Set up HubSpot Workflows to tag deals that have been stage-static for >X days, enabling the aging decay calculation. Use Sequences for automated acceleration outreach when deals hit age threshold.
- **Clari / Gong Forecast**: Export Clari's AI-weighted pipeline data as the baseline for coverage calculations — Clari's deal intelligence already applies aging and engagement signals to probability, giving you more accurate starting values than raw CRM stage data.
- **Looker / Tableau**: Build a coverage monitoring dashboard with weekly snapshots. Key calculated fields: weighted_pipeline = SUM(deal_value × stage_win_rate × aging_factor), coverage_ratio = weighted_pipeline / quarterly_target, gap_to_safe = (target × safe_threshold) - weighted_pipeline. Set up email subscriptions so CMO and Demand Gen team receive the dashboard every Monday morning.
- **Zapier / n8n**: Create an automated alert workflow: trigger when Salesforce coverage_ratio < warning_threshold → post to #revenue-ops Slack channel with coverage summary → create HubSpot task for Demand Gen manager → calendar block CMO/CRO for emergency pipeline review within 48 hours.
- **Google Sheets**: For teams without BI tools, build the coverage model in Google Sheets with: (1) pipeline data pulled via Salesforce API or manual export, (2) stage win rate lookup table (update monthly), (3) aging decay formula applied to days-since-stage-entry, (4) conditional formatting for RAG status. Share weekly with CRO via automated Google Apps Script email.

## Troubleshooting

**Problem: Coverage ratios look healthy in aggregate but individual territories are severely undershooting**
Solution: The aggregate view always masks segment-level problems. Break coverage down to the territory×segment×stage level before drawing conclusions. A healthy Enterprise pipeline can mask a critical SMB gap that affects >40% of deal volume. Run the Phase 1 analysis at the most granular level first, then roll up — never start with the rollup.

**Problem: Programs recommended in the response playbook have lead times that exceed weeks remaining in quarter**
Solution: Separate your analysis into two timeframes: "in-quarter recovery" (actions that can produce closed revenue this quarter) and "forward coverage build" (actions that produce Q+1 and Q+2 pipeline). Most programs with >6-week lead times are Q+1 investments, not Q recovery tools. Honest gap analysis must classify recoverable vs. unrecoverable gaps — trying to recover an unrecoverable gap with 3-week programs wastes budget. Focus in-quarter recovery on deal acceleration of existing pipeline (Stage 2-4), and invest remaining budget in Q+1 pipeline build for programs with appropriate lead times.

**Problem: Win rate assumptions are disputed by sales leadership (they believe win rates are higher than historical data shows)**
Solution: Build two versions of the coverage model — one using historical win rates from CRM data (objective) and one using sales-leadership-projected win rates (optimistic). Show both side by side in the CMO-CRO report. This is not a conflict to avoid but a tension to surface: if sales believes win rates will be higher, that is a falsifiable prediction that can be tracked. Historical data is the more conservative and defensible baseline; use it as your planning model. The optimistic model is the upside scenario, not the base case.

## Version History
- v1.0: Initial creation (auto-generated)
