# AI-Powered B2B SaaS RevOps Weekly Pipeline Health Monitor & Real-Time Revenue Operations Diagnostic Intelligence Engine - Automated Weekly Pulse Analytics for Revenue Operations Teams

**Difficulty:** Advanced | **Time:** 15-25 min | **Tags:** revops, pipeline, analytics, revenue-operations, weekly-reporting, pipeline-health, forecasting, anomaly-detection, b2b-saas

## Overview
Generates a concise, action-oriented weekly pipeline health report for Revenue Operations teams — surfacing anomalies, stalled deals, coverage gaps, and channel performance shifts before they become quarter-end problems. Run every Monday morning to set the week's operational priorities and coordinate marketing, sales, and CS responses in real-time.

## Quick Copy-Paste Version

You are a Revenue Operations analyst running the weekly pipeline health monitor for a B2B SaaS company. Analyze the data below and produce an action-oriented brief for the RevOps team covering pipeline health, anomalies, and this week's priority interventions.

**Company context:**
- ARR: [e.g., $28M]
- ACV: [e.g., $32,000]
- Sales cycle: [e.g., 4 months]
- Quarterly new ARR target: [$X]
- Weeks remaining in quarter: [#]

**This week's pipeline snapshot:**
- Total pipeline value: [$X]
- Required pipeline coverage for target: [X× coverage ratio, e.g., 3×]
- New pipeline created this week: [$X from # opportunities]
- Pipeline lost/disqualified this week: [$X from # opportunities]
- Net pipeline change week-over-week: [+/- $X]

**Stage-by-stage breakdown:**
- Stage 1 (Discovery): [$X, # opps]
- Stage 2 (Evaluation/Demo): [$X, # opps]
- Stage 3 (Proposal/Pricing): [$X, # opps]
- Stage 4 (Negotiation/Legal): [$X, # opps]
- Stage 5 (Closed Won): [$X this week]
- Stage 5 (Closed Lost): [$X this week, top loss reasons: X, Y, Z]

**Velocity signals:**
- Average days in current stage vs. benchmark: [e.g., Stage 2 avg 18 days vs. 12-day benchmark]
- Deals with no activity in 14+ days: [# deals, $X pipeline]
- Deals with expected close date in past (stale): [# deals, $X pipeline]

**Marketing contribution (this week):**
- Marketing-sourced MQLs created: [#]
- MQLs accepted by sales (SAL): [#, % acceptance rate]
- Marketing-sourced pipeline created: [$X]
- Top-performing demand gen channel: [Channel, $X pipeline]

**Forecast:**
- Commit (sales rep forecast): [$X]
- Best case (all likely deals): [$X]
- Gap to quarterly target: [$X]
- Most likely outcome (your estimate): [$X]

Produce:
1. **Pipeline Health Score** (0-100) with RAG status and the 2-3 biggest risks this week
2. **Anomaly Alerts** — any stage velocity, coverage, or conversion rate that's more than 15% off from the prior 4-week average
3. **Stalled Deal Hit List** — top 5 deals by value with no activity in 14+ days and a specific recommended action for each
4. **Coverage Gap Analysis** — how many additional deals need to enter the pipeline this week to maintain target coverage
5. **Marketing-Sales Handoff Quality Score** — MQL acceptance rate trend and top reasons for rejection
6. **This Week's Priority Actions** — 5 specific, owner-assigned actions with expected impact on pipeline or forecast

Be specific. Tell me which deals, which reps, which channels. A vague recommendation is useless.

## Advanced Customizable Version

### Role & Context
You are the embedded Revenue Operations Intelligence System for a B2B SaaS company. You run every Monday morning at 7am, ingest all CRM, MAP, and engagement data updated over the weekend, and produce the weekly pipeline diagnostic used to open the RevOps Monday sync meeting. Your output directly drives tactical decisions for the week: which deals get CEO attention, which marketing channels get emergency budget, which SDRs need coaching, and whether the current quarter is on track or at risk.

**Company profile:**
- Company name: [Company]
- Industry: [e.g., B2B SaaS / FinTech / HR Tech]
- ARR: [$X] | Growth stage: [e.g., Series B / $50M ARR growth-stage]
- ACV: [$X] | ASP (average selling price with discounts): [$X]
- Sales cycle: [X months average] | Range: [X–X months]
- Team: [# AEs, # SDRs/BDRs, # CSMs]
- CRM: [Salesforce / HubSpot / Pipedrive]
- MAP: [Marketo / HubSpot / Pardot]
- Forecast methodology: [Weighted pipeline / Stage-based / Manager commit / AI forecast]

**Quarter context:**
- Current quarter: [Q#, Year]
- Weeks elapsed: [#] | Weeks remaining: [#]
- Quarterly new ARR target: [$X]
- Quarterly new logo target: [# customers]
- Required pipeline coverage: [X× — typically 3–4× for SaaS]
- Prior quarter performance: [% of target, $X closed]

**Full pipeline snapshot (this Monday):**
- Total open pipeline: [$X across # opportunities]
- Pipeline by segment: [SMB: $X / Mid-Market: $X / Enterprise: $X]
- Pipeline by product line: [Product A: $X / Product B: $X]
- Pipeline by region: [Region 1: $X / Region 2: $X]
- Pipeline by rep: [Rep 1: $X / Rep 2: $X / ...] *(optional — paste rep-level breakdown)*

**Stage-by-stage analysis:**
- Stage 1 – Discovery/Qualification: [$X, # opps, avg days in stage: X vs. benchmark: Y]
- Stage 2 – Demo/Technical Evaluation: [$X, # opps, avg days: X vs. benchmark: Y]
- Stage 3 – Business Case/Champion Development: [$X, # opps, avg days: X vs. benchmark: Y]
- Stage 4 – Proposal/Commercial: [$X, # opps, avg days: X vs. benchmark: Y]
- Stage 5 – Negotiation/Security Review/Legal: [$X, # opps, avg days: X vs. benchmark: Y]

**Closed Won this week:**
- Deals closed: [# deals, $X ARR]
- Average discount applied: [%]
- Notable wins: [Brief — deal name, size, segment, winning factor]

**Closed Lost this week:**
- Deals lost: [# deals, $X ARR]
- Loss reasons: [Reason 1: # deals / Reason 2: # deals / No decision: # deals]
- Notable losses: [Brief — deal name, size, lost to whom/why]

**Pipeline creation and destruction this week:**
- New opportunities created: [# opps, $X ARR]
- Pipeline sourced by marketing: [$X] | By SDR/BDR: [$X] | By inbound self-serve: [$X] | By referral: [$X]
- Opportunities disqualified or deleted: [# opps, $X ARR, primary reasons]
- Net pipeline change vs. last week: [+/- $X, +/- %]

**Activity and velocity data:**
- Deals with ZERO sales activity in past 14 days: [# deals, $X pipeline value, rep assignments]
- Deals with close date in past (not updated): [# deals, $X pipeline]
- Deals with missing next steps or no meeting scheduled: [# deals, $X pipeline]
- Average time since last buyer-side engagement (email open, meeting attended, link click): [X days]
- Multi-threading health: [% of Stage 3+ deals with 2+ contacts engaged from buying org]

**Marketing contribution (trailing 7 days):**
- MQLs created: [# by channel — Paid: X / Organic: X / Events: X / Outbound: X / Partner: X]
- MQL-to-SAL conversion rate: [%] vs. prior 4-week average: [%]
- Top MQL rejection reasons from sales: [Reason 1: #, Reason 2: #, Reason 3: #]
- Marketing-sourced pipeline created: [$X]
- Marketing-influenced pipeline (touched marketing touchpoint in last 90 days): [$X]
- Highest-performing marketing channel by pipeline created: [Channel, $/MQL, pipeline contribution]

**Forecast data:**
- Sales manager commit: [$X]
- Best case (all likely): [$X]
- AI forecast (if available): [$X]
- Sandbagging risk: [# deals sales has in "Commit" that RevOps flags as at-risk]
- Pull-forward risk: [# deals slated to close in Q+1 that could move to current quarter with push]

**Competitive signals this week:**
- Competitive mentions in active deals: [Competitor A: # deals / Competitor B: # deals]
- Win rate vs. top competitor (trailing 30 days): [%]
- Deals where competitor is shortlisted: [$X pipeline at risk]

**CS and expansion signals:**
- Renewal opportunities in-quarter: [# accounts, $X ARR, % with confirmed renewal]
- Expansion opportunities created this week: [$X]
- At-risk accounts flagged by CS (health score < 50): [# accounts, $X ARR]
- Churn confirmed or likely this quarter: [$X ARR]

### Analysis Framework

**Module 1: Pipeline Health Score & RAG Dashboard**
Score the overall pipeline health on a 0–100 scale using weighted inputs:
- Coverage ratio score (30%): Current pipeline ÷ remaining target × required coverage multiple
- Velocity health score (25%): Weighted average of stage-level velocity vs. benchmarks, penalized for stalled deals
- Quality score (25%): ICP fit %, multi-threading %, marketing-influenced %, days since last buyer activity
- Forecast confidence score (20%): Gap between AI forecast and commit, % of commit supported by Stage 4+

Produce a RAG status: 🟢 Green (score 75+, on track), 🟡 Yellow (50–74, intervention needed), 🔴 Red (below 50, crisis mode).

Identify the 3 biggest risks to this quarter's number with specific evidence: e.g., "34% of Stage 3 pipeline has had no buyer engagement in 14+ days — equivalent to $890K at-risk ARR if velocity benchmarks aren't recovered by end of week 8."

**Module 2: Anomaly Detection**
Compare every material metric to the prior 4-week rolling average. Flag anomalies that are ≥15% outside of the trend baseline. For each anomaly, provide:
- What changed: Specific metric and magnitude of change
- Probable cause: 1–2 hypothesis with supporting data
- Response recommendation: Specific action this week to address or investigate

Priority anomaly categories to check:
- Stage conversion rates (any stage dropping significantly signals messaging or qualification issues)
- Pipeline creation rate by source (sudden drop in a channel = demand problem)
- Average days in stage (acceleration = positive; deceleration = blocker or disengagement)
- MQL acceptance rate by sales (drop signals ICP/qualification drift)
- Win rate vs. specific competitors (sudden decline = competitive threat to investigate)

**Module 3: Stalled Deal Triage**
For each deal with 14+ days of no activity:
- Deal context: Size, stage, buyer contact, expected close
- Last action taken (by marketing or sales)
- Risk level: Low (early stage), Medium (Stage 2-3), High (Stage 4-5, late stage stall is disqualifying)
- Recommended action: One specific, immediate action — not "follow up" but "send the Gartner peer review comparison doc to the CFO referencing the security objection raised in the Feb 3 call"
- Owner assignment: AE, SDR, marketing, or exec sponsor

Sort triage list by (stage × deal value) — late-stage large deals first.

**Module 4: Coverage Gap Analysis**
Calculate the specific pipeline creation needed this week to maintain target coverage:
- Current pipeline: [$X]
- Required pipeline for [X×] coverage of remaining target: [$X]
- Gap: [$X] — requires [# new opportunities] at average ACV to fill
- Breakdown by source: How much gap should marketing fill vs. SDR/BDR vs. AE self-sourcing?
- Recommendation: Which specific marketing programs or SDR campaigns should be accelerated this week to hit the pipeline creation number?

**Module 5: Marketing-Sales Handoff Quality Report**
Analyze MQL flow and handoff health:
- MQL acceptance rate this week vs. 4-week average vs. target
- Volume by channel vs. plan
- Top rejection reasons from sales + what each reason signals about lead quality
- Time from MQL creation to sales first activity (benchmark: ≤4 business hours for hot leads)
- Recommendations: Which lead quality issues require immediate fix (targeting, scoring, copy) vs. systemic fixes (ICP re-calibration, scoring model rebuild)

**Module 6: Forecast Confidence Calibration**
Stress-test the sales forecast:
- For each deal in Commit: Has the deal shown buyer-side forward progress in the last 7 days? If not, flag as At-Risk.
- Calculate: Forecast confidence band — based on current stage distribution and historical close rates, what's the 80% probability range for end-of-quarter outcome?
- Pull-forward opportunity: Identify Stage 4+ deals from next quarter that have executive engagement and a business case in place — these are candidates for acceleration
- Sandbag detection: Flag any deals where sales has downgraded the stage or push-out the close date in the last 2 weeks without a clear buyer-driven reason

**Module 7: This Week's Priority Action List**
Produce 5–7 owner-assigned actions. Each action must include:
- Action (specific, not vague): What to do, with whom, by when
- Expected outcome: What metric moves if this is executed
- Owner: AE name / SDR team / marketing / RevOps / CEO/exec
- Deadline: Day of the week (Monday–Friday)
- Priority: P1 (must-do today), P2 (complete by Wednesday), P3 (complete by Friday)

### Output Format
Structure the weekly report as:

**RevOps Weekly Pulse — [Date]**
1. Pipeline Health Score + RAG Status
2. Executive Summary (5 bullets: health score, top risk, top opportunity, week's #1 action, forecast range)
3. Anomaly Alert Log (table: metric | this week | 4-week avg | delta | root cause hypothesis | action)
4. Stalled Deal Triage (ranked table with specific actions)
5. Coverage Gap Dashboard
6. Marketing-Sales Handoff Quality
7. Forecast Confidence Calibration
8. This Week's Priority Actions (owner-assigned table)

Target length: 600–800 words of output (excluding tables). Designed to be reviewed in 15 minutes at the Monday morning RevOps sync.

## Example Input/Output

**Input (Sample Data):**
Company: Delvara (B2B SaaS, Procurement Tech, $34M ARR, Series B)
ACV: $41,000 | Sales cycle: 4.5 months
Q2 target: $2.8M new ARR | 7 weeks remaining | Required 3× coverage = $5.4M needed
Current pipeline: $4.2M (12% below required coverage)

Stage breakdown: S1: $820K (22 opps) | S2: $1.3M (18 opps, avg 21 days vs. 14-day benchmark) | S3: $980K (13 opps) | S4: $740K (7 opps) | S5 in flight: $360K (3 opps)

Closed Won this week: 2 deals, $88K ARR
Closed Lost this week: 3 deals, $195K ARR — reasons: budget freeze (2), chose competitor Vendrix (1)

Activity signals: 9 deals with no activity 14+ days ($1.1M pipeline), 4 deals with stale close dates ($480K)
MQLs created this week: 34 | SAL rate: 47% (vs. 61% prior 4-week avg) | Top rejection: "not ICP" (8 MQLs)
Marketing-sourced pipeline created: $220K
Forecast: commit $1.9M | best case $2.4M | gap to target: $400K

**Output (Sample):**

**RevOps Weekly Pulse — Monday, June 23, 2026**

**Pipeline Health Score: 52/100 🟡 YELLOW — Intervention Required**

**Executive Summary:**
- Pipeline coverage is $1.2M short of 3× requirement with 7 weeks remaining; Stage 2 velocity is 50% slower than benchmark — equivalent to $390K at risk of quarter slippage
- MQL acceptance rate dropped 14 points to 47% this week; 24% of rejections cite "not ICP" — likely a targeting drift from Q1 campaign expansion targeting
- $1.1M in 9 deals has gone dark for 14+ days; 5 of these are Stage 3+ and require immediate exec engagement
- Pull-forward opportunity: 2 Stage 4 deals from Q3 pipeline (Meridian Corp $120K, Oxbow Analytics $85K) show active buyer engagement — acceleration feasible
- Forecast range: $1.7M–$2.2M (80% confidence band); $400K gap to $2.8M target requires both pipeline acceleration AND pull-forward execution

**Anomaly Alert Log:**

| Metric | This Week | 4-Wk Avg | Delta | Root Cause Hypothesis | Action |
|---|---|---|---|---|---|
| SAL acceptance rate | 47% | 61% | -14pts | Q1 campaign targeting broadened to adjacent personas (IT Ops) outside core procurement buyer | ICP targeting audit: pause IT Ops audiences, reallocate $8K/week to VP Procurement list-based targeting |
| Stage 2 avg days | 21 days | 14 days | +50% | 3 large deals ($620K combined) blocked on security reviews — no security liaison assigned | Assign RevOps to coordinate security review track; loop in SE and CISO reference customer |
| Pipeline created | $220K | $340K/wk avg | -35% | Paid search volume dropped after Q1 budget reallocation; SEO traffic dip (Google algo update) | Emergency: reallocate $12K from LinkedIn brand spend to high-intent Google search this week |

**Stalled Deal Triage (Top 5 by Stage × Value):**

| Deal | Size | Stage | Days Dark | Recommended Action | Owner | Deadline |
|---|---|---|---|---|---|---|
| Cascade Financial | $185K | S4 | 19 days | Legal redline stalled — send VP Procurement a mutual close plan with specific legal resolution milestones; loop in CEO for executive-to-executive outreach | AE (Marcus) + CEO | Tuesday |
| Northpoint Holdings | $140K | S3 | 22 days | Champion went quiet after pricing call — send ROI re-framing email referencing Cascade Financial customer story; request 20-min call with CFO | AE (Priya) | Monday |
| Orion Manufacturing | $98K | S2 | 17 days | No second stakeholder engaged — multi-thread immediately to VP Operations using LinkedIn Sales Navigator; send VP-specific use case deck | SDR (Jordan) | Monday |
| Stellar Logistics | $72K | S2 | 15 days | Demo completed but no next step set — send Gartner peer review with personalized ROI calculator pre-filled with their logistics spend data | AE (Chen) | Tuesday |
| Brightway Insurance | $61K | S1 | 18 days | Initial discovery call done but no follow-up — disqualify or send a single re-engagement email with a specific ROI stat for insurance verticals; if no response in 3 days, move to marketing nurture | AE (Marcus) | Wednesday |

## Success Metrics

A high-quality output will:
- Produce a specific pipeline health score (not just "pipeline looks healthy") with evidence-backed sub-scores
- Surface at least 3 concrete anomalies with data-supported root cause hypotheses — not "may be due to seasonality"
- Generate a stalled deal triage list where every recommended action is specific enough to execute without additional research
- Quantify the coverage gap in dollars AND the specific number of new opportunities required to close it
- Deliver a forecast confidence band (not a point estimate) with clear identification of which deals are over-forecast and which are sandbagged
- Produce priority actions with named owners and weekday deadlines — not "AE team should follow up"

**Benchmark thresholds for healthy RevOps metrics (B2B SaaS):**
- Pipeline coverage: 3.0–3.5× remaining target minimum
- Stage 2 average duration: ≤ 14 days (benchmarks vary by ACV; Enterprise = up to 30 days)
- SAL acceptance rate: ≥ 55%
- Deals dark 14+ days: ≤ 10% of pipeline value
- Forecast commit accuracy: Within 10% of actual close (trailing 4 quarters)
- Speed-to-lead (MQL first contact): ≤ 4 business hours

## Related Prompts

- `../../05_Analytics-&-Performance/Revenue-Operations-Analytics/AI-Powered-B2B-SaaS-Marketing-Pipeline-Quality-Intelligence-&-MQL-to-Revenue-Accountability-Engine.md` — deep-dive MQL quality analysis to root-cause the marketing handoff issues flagged in Module 5
- `../../05_Analytics-&-Performance/Revenue-Operations-Analytics/AI-Powered-B2B-SaaS-Revenue-Leakage-Detection-&-Pipeline-Hygiene-Intelligence-Engine.md` — for quarterly revenue leakage audits triggered when this weekly monitor shows sustained coverage decline
- `../../05_Analytics-&-Performance/Funnel-Conversion-&-Pipeline-Velocity/AI-Powered-B2B-Pipeline-Coverage-Intelligence-&-Marketing-Sourced-Demand-Gap-Analysis-Intelligence-Engine.md` — for building the pipeline coverage model used in Module 4
- `../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-CMO-Weekly-Strategic-Intelligence-Brief-&-Revenue-Signal-Synthesis-Intelligence-Engine.md` — for translating this week's RevOps pulse into the CMO's strategic weekly brief

## Integration Tips

**Salesforce:**
- Schedule a weekly Salesforce report to auto-export Monday morning: Active pipeline by stage (with owner, close date, last activity date, next step), deals modified in last 7 days, and closed won/lost with primary loss reason. Feed this directly into the Quick Copy-Paste version
- Create a Salesforce Dashboard with three widgets: (1) Pipeline Coverage Gauge vs. 3× target, (2) Stalled Deals table (last activity > 14 days, filtered to open opps), (3) Stage Velocity Bar Chart (average days per stage, current week vs. 4-week rolling)
- Use Einstein Activity Capture or Gong/Chorus integration to auto-populate "last buyer-side engagement" data — this eliminates rep self-reporting bias

**HubSpot:**
- Use HubSpot's "Report" tool to build a Deal Velocity report showing time-in-stage distributions by week — export as CSV and paste into the Advanced prompt
- Create a HubSpot workflow: Deal stage unchanged for 14 days → notify RevOps + AE manager via Slack → flag deal with "Stalled" tag for inclusion in Monday's triage
- HubSpot's Forecast tool integrates natively with the prompt's "Forecast Confidence" module — use the AI-generated forecast number as your baseline and run the stress-test against it

**Gong / Chorus:**
- Pull the "Deal Risk" feed every Monday: Gong's deal risk score + the specific risk factors cited (multi-threading score, next steps quality, competitor mentions) directly populate Module 3's stalled deal analysis
- Use Gong's Mutual Action Plan analytics to flag deals where the MAP hasn't been updated in 7+ days — these are high-probability stall candidates

**Slack + Zapier Automation:**
- Build a weekly Zap: Every Monday at 7am → pull Salesforce pipeline export → format as structured input → send to Claude API with this prompt → post the formatted report to #revenue-ops-weekly Slack channel with @mentions for deal owners
- Create a follow-up Zap: RevOps team reacts with ✅ on each priority action as completed → log completion to a Google Sheet → track execution rate week-over-week to measure RevOps team effectiveness

**Google Sheets / Looker Studio:**
- Maintain a rolling 13-week RevOps metrics tracker: pipeline coverage, stage conversion rates, SAL acceptance, forecast accuracy — this becomes the "4-week rolling average" baseline that makes anomaly detection meaningful over time
- Build a Looker Studio dashboard pulling from your CRM's BigQuery export — configure the dashboard to auto-refresh Sunday night so the weekly RevOps pulse can be run fresh every Monday morning

## Troubleshooting

**Problem:** Stage velocity data isn't available from CRM — average days in stage aren't tracked or are unreliable because reps manually move deals without updating dates.
**Fix:** Use "last activity date" as a proxy for stage velocity — it's natively available in all major CRMs and doesn't require custom field setup. Configure a required field on stage transition: "Next step + next meeting date" must be populated before stage can advance. This creates the behavioral data needed for reliable velocity tracking within 2-3 weeks of implementation.

**Problem:** MQL rejection reasons from sales are inconsistent — reps mark deals as "not ICP" or "bad timing" without specifics, making it impossible to diagnose whether lead quality is actually declining.
**Fix:** Implement a 3-question microform that fires when a sales rep marks an MQL as rejected in CRM: (1) Which ICP criterion did this lead fail? [dropdown: title / company size / industry / budget / not actively evaluating], (2) Who referred this lead or what channel created it?, (3) Optional: any buyer context that would make this worth re-engaging in 90 days? This takes 45 seconds per rejection and transforms vague rejection data into actionable targeting intelligence within 4 weeks.

**Problem:** The forecast confidence band produced by the prompt is too wide to be useful for leadership reporting — ranges like "$1.4M–$2.6M" on a $2.8M target aren't actionable.
**Fix:** The band is correctly reflecting your data uncertainty — a wide band means your pipeline has high risk concentration in a small number of large deals. The correct response is not to narrow the band artificially, but to use the band to communicate decision options: "At $1.4M, here's what we cut. At $2.2M, we're on plan. At $2.6M, we invest in Q3 demand gen. What's the board's comfort level with each scenario?" Treat forecast uncertainty as a strategic input, not a number to hide.

## Version History
- v1.0: Initial creation (auto-generated)
