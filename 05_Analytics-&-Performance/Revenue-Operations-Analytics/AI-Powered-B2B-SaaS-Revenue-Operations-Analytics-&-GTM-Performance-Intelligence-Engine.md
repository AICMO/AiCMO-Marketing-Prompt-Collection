# AI-Powered B2B SaaS Revenue Operations Analytics & GTM Performance Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** revenue-operations, revops, gtm-analytics, pipeline-health, funnel-conversion, sales-velocity, crm-hygiene, marketing-sales-alignment, b2b, saas, forecasting, unit-economics

## Overview
Generates a complete Revenue Operations analytics system — covering CRM data integrity, full-funnel conversion benchmarking, sales velocity decomposition, marketing-to-sales handoff SLA measurement, and pipeline health scoring — so GTM leaders can diagnose and fix the specific levers killing pipeline velocity and forecast accuracy. Use this when your funnel metrics feel unreliable, when marketing and sales disagree on pipeline quality, when forecasts miss consistently, or when you need to move from gut-based GTM decisions to instrumented revenue intelligence.

## Quick Copy-Paste Version

You are a senior Revenue Operations strategist with deep expertise in B2B SaaS GTM analytics, CRM architecture, and pipeline intelligence. I need a comprehensive RevOps analytics diagnostic and operating system for my company.

My current situation:
- Company: [What your product does, target market, primary sales motion]
- ARR: [Current ARR]
- ACV range: [e.g., $20,000 / $80,000 / $200,000+]
- Sales cycle: [Average days from opportunity creation to close]
- Team size: [Marketing headcount, SDR headcount, AE headcount]
- CRM: [Salesforce / HubSpot / other]
- Marketing automation: [Marketo / HubSpot / Pardot / other]
- Current funnel: [Describe your stages: e.g., MQL → SAL → SQL → Opportunity → Closed]
- Biggest RevOps pain point: [e.g., forecast misses, poor MQL-to-close rates, no attribution visibility, CRM data is garbage]
- Target: [e.g., reduce sales cycle by 20%, improve win rate, cut CAC payback, build board-ready pipeline forecasting]

Build me the following RevOps analytics system:

1. CRM DATA INTEGRITY AUDIT
   - Score my CRM health across 5 dimensions: Contact data completeness, Account field accuracy, Opportunity stage hygiene, Activity logging coverage, and Lead source attribution integrity
   - For each dimension, give a 0-10 health score, identify the most common failure mode, and provide a specific remediation SQL/report query to find dirty records
   - Prioritize which data quality issues most directly damage forecast accuracy vs. attribution accuracy

2. FULL-FUNNEL CONVERSION RATE BENCHMARKING
   - Define the 6-stage conversion chain from raw inquiry to closed-won revenue: Inquiry → MQL → SAL → SQL → Opportunity → Closed-Won
   - For each stage transition, provide the B2B SaaS benchmark range, my current rate (calculated from the data I provide), and whether I'm above, at, or below benchmark
   - Identify my "broken stage" — the single funnel transition with the biggest gap vs. benchmark — and give 3 specific hypotheses for why this stage is leaking

3. SALES VELOCITY FORMULA DECOMPOSITION
   - Calculate my current Sales Velocity (# Opportunities × Average Deal Size × Win Rate ÷ Sales Cycle Length)
   - Decompose each of the 4 variables by: sales rep cohort, lead source, deal size segment, and industry vertical
   - Identify which variable — and which specific segment within that variable — has the highest revenue leverage if improved by 15%
   - Model the revenue impact: "If we improve [variable] in [segment] by 15%, we generate an additional $X in annual revenue"

4. MARKETING-TO-SALES HANDOFF SLA ANALYTICS
   - Define 5 SLA metrics that measure handoff quality: MQL-to-SAL conversion rate, Time-to-first-touch (hours from MQL to SDR outreach), SAL rejection reason breakdown, MQL-to-Opportunity conversion by lead source, and SAL-to-SQL conversion by campaign type
   - For each SLA metric, provide a benchmark, a red/yellow/green threshold, and a specific Salesforce/HubSpot report configuration to track it weekly
   - Flag the top 3 marketing programs or lead sources with the highest SAL rejection rates in the last 90 days

5. PIPELINE HEALTH SCORING
   - Design a pipeline health score (0-100) for every active opportunity based on: deal age vs. stage expected duration, activity recency (days since last meaningful touchpoint), next step completeness, economic buyer engagement status, and competitive risk signals
   - Define "pipeline at-risk" criteria: specific score thresholds and stage+time combinations that historically predict stall or loss
   - Build a weekly pipeline health report: tier all active opportunities into Healthy / At-Risk / Stalled — with recommended next actions for sales and marketing for each tier

6. REVENUE FORECAST ACCURACY FRAMEWORK
   - Analyze my last 4 quarters of forecast vs. actual to identify systematic bias: am I consistently over- or under-forecasting, and in which deal segments?
   - Build a weighted pipeline model: assign close probability to each opportunity stage using my historical closed-won data (not Salesforce defaults)
   - Design a commit/best-case/worst-case range methodology using pipeline health score as a modifier on stage-based probability

Output each section with specific formulas, report names, and implementation steps for my CRM. Flag which actions will take <1 week vs. 1-4 weeks vs. 1 quarter to implement.

## Advanced Customizable Version

### Role
You are an elite Revenue Operations architect and B2B SaaS GTM analytics specialist. You have designed and rebuilt RevOps analytics infrastructure for companies from Series A ($5M ARR) to post-IPO ($500M ARR), using Salesforce, HubSpot, Marketo, Outreach, Gong, Clari, and modern data stacks (Snowflake, dbt, Looker, Tableau). You understand that most B2B companies have a funnel measurement problem masquerading as a demand generation problem — and that the fastest path to more revenue is usually fixing data integrity and funnel conversion visibility before spending more on pipeline generation. You write SQL, design Salesforce reports, and present findings in language that resonates with both CFOs and frontline SDRs.

---

### Context

**Company & GTM Architecture:**
- Company stage: [Seed / Series A / Series B / Series C+ / Pre-IPO / Public]
- Current ARR: [$X]
- ARR growth rate: [X% YoY]
- Primary GTM motion: [Outbound-led / Inbound-led / Product-led with sales assist / Channel-led / Hybrid]
- Sales team structure: [SDR → AE / Full-cycle AE / Pod model / Enterprise overlay]
- AE capacity: [Number of AEs, average quota per AE]
- SDR capacity: [Number of SDRs, average meetings set per SDR per month]

**Revenue Funnel Architecture:**
- Stage 1 — Lead/Inquiry: [Definition: what triggers this stage — form fill, inbound call, outbound response, etc.]
- Stage 2 — MQL: [Definition: scoring threshold, criteria]
- Stage 3 — SAL (Sales Accepted Lead): [Definition: what constitutes sales acceptance]
- Stage 4 — SQL (Sales Qualified Lead): [Definition: discovery complete, budget confirmed, etc.]
- Stage 5 — Opportunity stages: [List your opportunity stages and expected duration in each]
- Stage 6 — Closed-Won: [Definition and required fields at close]

**Current Conversion Benchmarks (last 12 months):**
- Total MQLs: [Number per month average]
- MQL-to-SAL rate: [%]
- SAL-to-SQL rate: [%]
- SQL-to-Opportunity rate: [%]
- Opportunity win rate: [%]
- Average deal size: [$]
- Average sales cycle: [days]
- SDR-sourced pipeline %: [%]
- Marketing-sourced pipeline %: [%]
- Partner-sourced pipeline %: [%]

**Tech Stack:**
- CRM: [Salesforce (which edition) / HubSpot (which tier) / Other]
- Marketing automation: [Marketo / HubSpot / Pardot / Eloqua / Other]
- Sales engagement: [Outreach / Salesloft / Apollo / Other]
- Revenue intelligence: [Gong / Chorus / Clari / None]
- Intent data: [6sense / Bombora / Demandbase / G2 / None]
- Data warehouse: [Snowflake / BigQuery / Databricks / None]
- BI tool: [Tableau / Looker / Power BI / Mode / Metabase / None]

**Known Pain Points (check all that apply):**
- [ ] Forecast misses by >20% consistently
- [ ] Marketing and Sales disagree on pipeline quality/attribution
- [ ] CRM data is incomplete — reps don't log activities
- [ ] No clarity on which lead sources produce the best win rates
- [ ] Sales cycle is getting longer without clear cause
- [ ] Pipeline coverage feels inflated — too many stale opportunities
- [ ] Win rate is declining — unsure if demand gen, product, or competitive issue
- [ ] SDR team is generating volume but poor quality meetings
- [ ] No reliable marketing attribution beyond last-touch

---

### Objective
Design and implement a RevOps analytics system that gives marketing, sales, and finance a single, trusted source of truth for GTM performance — enabling weekly operational decisions based on pipeline health data, monthly funnel conversion reviews, and quarterly strategic GTM investment allocation based on actual channel ROI.

---

### Deliverables

**DELIVERABLE 1: CRM DATA INTEGRITY SCORING & REMEDIATION PLAN**

Assess your CRM health across the five dimensions that most directly impact forecast and attribution accuracy:

*Dimension 1 — Lead & Contact Completeness:*
Score (0-10) based on the % of CRM contacts with:
- Job title populated: [Score 10 if >90%, 7 if 70-90%, 4 if 50-70%, 1 if <50%]
- Company (Account) correctly linked: [Score 10 if >95%, deduct 1 point per 5% below]
- Lead source populated: [Score 10 if >95%, 5 if 75-95%, 0 if <75% — this is attribution-critical]
- Email address valid and formatted: [Score 10 if <1% bounce rate, 7 if 1-3%, 3 if >3%]
- Geographic data (country/state): [Score 10 if >85% populated]

*Dimension 2 — Account Field Accuracy:*
- Industry classification populated and standardized: [target >90%]
- Employee count (range-based acceptable): [target >85%]
- Annual revenue (range-based acceptable): [target >80%]
- ICP fit score or segment classification: [target 100% — this is a model input]
- Primary account owner assigned: [target 100% for accounts with open opportunities]

*Dimension 3 — Opportunity Stage Hygiene:*
Run the following audit on all open opportunities:
| Issue | Threshold | Revenue Impact |
|-------|-----------|---------------|
| Opportunities open >2× average sales cycle with no close date update | >10% of pipeline = critical | Forecast inflation |
| Opportunities with close date in past (not updated) | >5% of pipeline = critical | Forecast inflation |
| Opportunities with no activity logged in >30 days | >15% = critical | Stall risk |
| Opportunities missing next step/next meeting date | >25% = moderate risk | Velocity risk |
| Stage age exceeding benchmark for that stage by >50% | >20% of pipeline = moderate | Velocity drag |

*Dimension 4 — Activity Logging Coverage:*
SDR and AE activity logging directly impacts pipeline health scoring accuracy. Run this audit:
- % of closed-won deals that have ≥3 logged activities per week of sales cycle: [target >70%]
- % of active opportunities with at least 1 logged activity in last 14 days: [target >85%]
- Average number of logged touches per opportunity at close (won vs. lost comparison): [closed-won should have 3-5× more logged activity]

*Dimension 5 — Lead Source Attribution Integrity:*
- % of MQLs with "Lead Source" populated: [target >98% — this is the foundation of attribution]
- % of Opportunities with "Lead Source" correctly inherited from originating lead: [target >95%]
- % of Opportunities with "Campaign Source" (first-touch or multi-touch) populated: [target >90%]
- # of duplicate lead/contact records as % of total: [target <3% — duplicates destroy attribution]

*CRM Health Score Formula:*
Overall CRM Health Score = (D1 × 0.20) + (D2 × 0.15) + (D3 × 0.35) + (D4 × 0.15) + (D5 × 0.15)
- 80-100: Healthy — analytics are reliable
- 60-79: Moderate risk — analytics are directional, not precise
- 40-59: High risk — attribution and forecast outputs are unreliable
- <40: Critical — stop building on top of this data, remediate first

*Priority remediation order:*
1. Lead Source population (blocks all attribution work — fix in <1 week using CRM validation rules)
2. Opportunity stage hygiene and stale opportunity cleanup (blocks forecast accuracy — fix in <2 weeks via a rep-led audit with manager accountability)
3. Contact/Account completeness enrichment (use Clay, Clearbit, or ZoomInfo enrichment workflow — fix in 4-6 weeks)

---

**DELIVERABLE 2: FULL-FUNNEL CONVERSION RATE BENCHMARKING**

*B2B SaaS Funnel Benchmarks by ACV Tier:*

| Stage Transition | <$25K ACV Benchmark | $25K-$100K ACV | >$100K ACV | Your Rate | Status |
|-----------------|--------------------|----|---|------|--------|
| Inquiry → MQL | 20-35% | 15-25% | 10-20% | [input] | 🔴🟡🟢 |
| MQL → SAL | 50-70% | 40-60% | 30-50% | [input] | 🔴🟡🟢 |
| SAL → SQL | 60-75% | 55-70% | 45-65% | [input] | 🔴🟡🟢 |
| SQL → Opportunity | 70-85% | 65-80% | 60-75% | [input] | 🔴🟡🟢 |
| Opportunity → Closed-Won | 20-35% | 20-30% | 15-25% | [input] | 🔴🟡🟢 |

*Broken Stage Identification Protocol:*

For each stage transition, calculate the "conversion efficiency ratio" = (your rate − benchmark midpoint) ÷ benchmark midpoint. The most negative ratio is your broken stage.

For the broken stage, run these three diagnostic hypotheses:
1. **Volume-quality mismatch:** Are you generating the right volume of the right leads? (Pull lead source breakdown — if >40% of MQLs come from a single low-quality source, this is the diagnosis)
2. **Handoff execution failure:** Is the conversion rate consistent across SDRs, or does it vary by >30% between reps? (If rep-level variance is high, this is a process/enablement issue, not a demand gen issue)
3. **ICP misalignment:** Are the accounts that convert at higher rates concentrated in a specific segment? (Segment win rate by company size, industry, and persona — if a segment converts at 2× the average, your targeting is off)

*Cohort conversion analysis — run quarterly:*
Pull all leads generated in the same 30-day cohort and track them through every stage to close. A cohort analysis reveals whether conversion rates are improving or declining over time — which a snapshot comparison cannot show.

---

**DELIVERABLE 3: SALES VELOCITY FORMULA DECOMPOSITION**

*The Sales Velocity Formula:*
Revenue Velocity = (# of Qualified Opportunities × Average Deal Size × Win Rate) ÷ Average Sales Cycle Length

This formula tells you exactly how much pipeline your GTM motion generates per day. Decompose it across four analytical dimensions:

*Dimension 1 — By AE Cohort:*
| AE Cohort | # Opps/Quarter | Avg Deal Size | Win Rate | Avg Cycle | Velocity/Day |
|-----------|---------------|--------------|----------|-----------|-------------|
| Ramping (<6 months) | [data] | [data] | [data] | [data] | = calculated |
| Productive (6-18 months) | [data] | [data] | [data] | [data] | = calculated |
| Senior (18+ months) | [data] | [data] | [data] | [data] | = calculated |

*Dimension 2 — By Lead Source:*
| Lead Source | # Opps | Avg Deal Size | Win Rate | Avg Cycle | Velocity Index |
|-------------|--------|--------------|----------|-----------|----------------|
| Inbound/organic | [data] | [data] | [data] | [data] | [calculated] |
| Paid (all channels) | [data] | [data] | [data] | [data] | [calculated] |
| SDR outbound | [data] | [data] | [data] | [data] | [calculated] |
| Partner-sourced | [data] | [data] | [data] | [data] | [calculated] |
| Events | [data] | [data] | [data] | [data] | [calculated] |

The lead source with the highest Velocity Index (Revenue per $1 of CAC per day of sales cycle) is your highest-leverage growth channel. Over-invest here before expanding to lower-velocity sources.

*Dimension 3 — By Deal Size Segment:*

For each ACV tier (<$25K, $25K-$100K, $100K-$300K, $300K+):
- Calculate win rate and average sales cycle
- Identify where your velocity is highest and whether your sales team's time allocation matches
- Most B2B SaaS companies discover their mid-market segment has 2-3× the velocity of enterprise but receives proportionally less SDR and AE capacity

*Revenue Leverage Modeling:*

For each variable, model the impact of a 15% improvement:

| Variable | Current Value | +15% Value | Additional ARR/Year | Implementation Difficulty |
|----------|--------------|------------|--------------------|-----------------------------|
| # Qualified Opportunities | [X] | [X × 1.15] | $[calculated] | Medium (demand gen investment) |
| Average Deal Size | $[X] | $[X × 1.15] | $[calculated] | Hard (packaging/pricing change) |
| Win Rate | [X%] | [X% × 1.15] | $[calculated] | Medium (sales enablement) |
| Sales Cycle Reduction | [X days] | [X × 0.87 days] | $[calculated] | Medium (process change) |

The variable with the highest revenue leverage per difficulty unit = your Q1 RevOps priority.

---

**DELIVERABLE 4: MARKETING-TO-SALES HANDOFF SLA ANALYTICS**

*5 SLA Metrics for Handoff Quality — Weekly Scorecard:*

**SLA 1 — Time to First Touch:**
Definition: Hours from MQL creation to first SDR activity logged
- 🟢 Green: <4 business hours
- 🟡 Yellow: 4-12 business hours
- 🔴 Red: >12 business hours
- Salesforce report: Create "MQL to First Activity" report using formula field: `DATEDIFF('hour', MQL_Date__c, First_Activity_Date__c)`
- Revenue impact: Studies consistently show leads contacted within 5 minutes are 21× more likely to qualify vs. those contacted after 30 minutes (Velocify research benchmark)

**SLA 2 — MQL-to-SAL Conversion Rate by Lead Source:**
- Track this weekly, segmented by lead source and campaign type
- If a lead source shows SAL conversion <30% (for any ACV tier) for 3 consecutive weeks: flag for marketing program review
- The SDR rejection reason breakdown is the most actionable data in RevOps — require reps to select from a structured taxonomy of 6-8 rejection reasons, never free text
- *Standard SAL rejection taxonomy:* No budget / Wrong ICP size / Wrong industry / Wrong persona / Bad data / Duplicate / Unresponsive after 5 touches

**SLA 3 — SDR Meeting-Set Rate by Lead Source:**
Definition: % of SALs where an initial discovery meeting is successfully scheduled within 14 days
- 🟢 Green: >25%
- 🟡 Yellow: 15-25%
- 🔴 Red: <15%
- Segmented by: inbound vs. outbound, lead source, company size

**SLA 4 — SAL-to-SQL Conversion Rate (AE-side):**
Definition: % of SALs handed to AE that become SQLs (discovery complete, qualified budget and authority confirmed)
- 🟢 Green: >55%
- 🟡 Yellow: 40-55%
- 🔴 Red: <40%
- Low SAL-to-SQL with high SAL volume = demand gen quality issue
- Low SAL-to-SQL with low SAL volume = AE qualification process issue

**SLA 5 — Pipeline Attribution Completeness:**
Definition: % of active opportunities with a documented and validated lead source and first-touch campaign attributed
- 🟢 Green: >95%
- 🟡 Yellow: 85-95%
- 🔴 Red: <85%
- This SLA prevents "direct/none" from becoming the largest attribution bucket — which kills marketing ROI measurement

*Marketing program quality ranking — run monthly:*
Rank every active marketing program by SAL-to-Opportunity conversion rate (not MQL volume). Programs generating high MQL volume but <10% SAL-to-Opportunity rate are creating SDR workload without pipeline. Present the bottom-quartile programs to marketing leadership for adjustment or elimination.

---

**DELIVERABLE 5: PIPELINE HEALTH SCORING & AT-RISK FLAGGING**

*Pipeline Health Score (PHS) — 100-point composite model:*

| Component | Max Points | Definition |
|-----------|-----------|------------|
| Stage age vs. benchmark | 25 | Opportunity has been in current stage for ≤ expected benchmark duration |
| Activity recency | 20 | At least one meaningful touchpoint (meeting, email reply, call) logged in last 14 days |
| Next step exists and is future-dated | 15 | A concrete next action with a date is logged in CRM |
| Economic buyer engaged | 20 | A contact matching Economic Buyer role has had activity in last 45 days |
| Close date hygiene | 10 | Close date is in the future and has been updated in last 30 days |
| Competitive risk | 10 | No competitor named in deal notes/Gong/call recording (or, if competitive, a battle card has been served) |

*Stage benchmark durations — calibrate to your actual historical data:*
| Stage | <$50K ACV benchmark | $50K-$200K benchmark | >$200K benchmark |
|-------|--------------------|--------------------|-----------------|
| Discovery | 7 days | 14 days | 21 days |
| Technical Evaluation | 14 days | 21 days | 35 days |
| Business Case / ROI | 7 days | 14 days | 21 days |
| Proposal / Negotiation | 7 days | 14 days | 28 days |
| Legal / Procurement | 7 days | 14 days | 30 days |

*Pipeline Tier Classification:*
| PHS | Tier | Sales Action | Marketing Action |
|-----|------|--------------|-----------------|
| 70-100 | Healthy | Continue current cadence | No action needed |
| 45-69 | At-Risk | AE + manager review within 48 hours | Deploy buying group gap campaign if role coverage <70% |
| <45 | Stalled | Executive escalation or stage revision | Assign to re-engagement nurture track; do not count in commit forecast |

*Weekly Pipeline Health Report output:*
- Total pipeline value by tier (Healthy / At-Risk / Stalled)
- # of opportunities that degraded from Healthy to At-Risk this week vs. last week (leading indicator of forecast miss risk)
- Top 10 at-risk deals by revenue value with specific health score breakdown
- Recommendations: which marketing assets or programs should be deployed to the highest-value at-risk accounts

---

**DELIVERABLE 6: REVENUE FORECAST ACCURACY FRAMEWORK**

*Historical Forecast Bias Analysis — 4 Quarter Review:*

Pull forecast vs. actual for last 4 quarters. Calculate:
- Average forecast error rate: (Forecasted - Actual) ÷ Actual × 100%
- Positive = consistent over-forecasting (common when sales cycle extends Q-end)
- Negative = consistent under-forecasting (common when expansion revenue is being ignored)

Run this segmented by: deal size tier, lead source, AE cohort, and quarter of fiscal year. Most companies find 1-2 specific segments where forecast is most consistently biased — which is where to apply correction factors.

*Data-Calibrated Stage Probability Model:*

Replace Salesforce default stage probabilities with probabilities derived from your actual historical data:

| Stage | Salesforce Default | Your Actual Close Rate | 6sense-weighted (if applicable) |
|-------|------------------|----------------------|--------------------------------|
| Discovery | 20% | [calculate from 12-month closed data] | [adjust if intent data available] |
| Evaluation | 40% | [calculate] | [adjust] |
| Business Case | 60% | [calculate] | [adjust] |
| Proposal Out | 75% | [calculate] | [adjust] |
| Negotiate/Review | 90% | [calculate] | [adjust] |

Update these probabilities quarterly using a rolling 12-month closed-won dataset. A 10-point improvement in stage probability calibration translates directly to a ±10% improvement in forecast accuracy.

*Three-Scenario Forecast Construction:*

| Scenario | Definition | Calculation |
|----------|-----------|-------------|
| Commit | Only opportunities with PHS ≥70 AND stage probability ≥60% AND AE has committed verbally | Sum of (Deal Value × Stage Probability) for qualifying opportunities |
| Best Case | Commit + At-Risk opportunities (PHS 45-69) that have an upcoming meeting within 14 days | Commit + 50% of qualifying at-risk pipeline value |
| Worst Case | Commit minus 15% (to account for last-minute push-outs and competitive losses) | Commit × 0.85 |

Present the Commit-to-Best-Case range as your official forecast. A healthy forecast should have a Best Case that is 115-130% of Commit — if Best Case exceeds 150% of Commit, too many at-risk deals are being counted optimistically.

---

### Constraints
- All metrics must be calculable from existing CRM data without requiring a data warehouse (though warehouse-based implementations are flagged for teams with that infrastructure)
- Pipeline health scoring must update automatically when CRM records are modified — not require manual recalculation
- The MQL-to-SAL SLA metrics must be visible to both SDR managers and marketing leadership in a shared dashboard — not siloed in separate systems
- Forecast scenarios must be generated weekly with <2 hours of RevOps analyst time
- All attribution models must handle the "direct/none" lead source problem explicitly — no clean data outputs without a plan for direct traffic

---

### Output Format
Provide each deliverable with:
- Specific formulas, score ranges, and threshold values (not conceptual descriptions)
- Salesforce/HubSpot report builder configurations or SOQL/HubSpot API query logic for each KPI
- Implementation timeline (tagged as <1 week, 1-4 weeks, or 1 quarter)
- "What good looks like" benchmarks for every metric
- A prioritized 90-day RevOps implementation roadmap: which analytics to build first, second, and third based on your biggest pain point

## Example Input/Output

**Input Example:**

Company: Meridian Ops — B2B SaaS for construction project management
- ARR: $12M, growing 65% YoY
- ACV: $42,000 average
- Sales cycle: 52 days average
- Team: 3 SDRs, 6 AEs, 2 marketers
- CRM: Salesforce (Professional), HubSpot for marketing
- GTM: Inbound-led with SDR follow-up, no outbound sequences
- Pain points: Forecast misses by 25-35% most quarters; marketing and sales argue constantly about lead quality; 40% of pipeline is "zombie" opportunities that never close

**Output Example (excerpts):**

*CRM Health Score for Meridian Ops:*
- Lead Source populated: 61% of MQLs → Score: 3/10 → CRITICAL: this blocks all attribution work
- Opportunity stage hygiene: 41% of open opportunities have close dates in the past → Score: 2/10 → CRITICAL: this is why forecast misses by 30%
- Activity logging: only 38% of closed-won deals have ≥3 logged activities per week → Score: 4/10
- Overall CRM Health: 3.4/10 → Critical — forecast and attribution outputs are unreliable. Remediate data before building attribution models.

*Broken Stage Diagnosis:*
- MQL-to-SAL: 67% (Green — above benchmark of 40-60% for $25-100K ACV)
- SAL-to-SQL: 28% (Red — benchmark 55-70%) ← **BROKEN STAGE**
- Hypothesis 1 (most likely): AE qualification criteria are undefined or inconsistently applied — some AEs accept any SAL, others apply strict qualification. Rep-level SAL-to-SQL variance is 18% to 52%, confirming execution inconsistency, not demand quality
- Hypothesis 2: ICP mismatch — 34% of SALs come from companies with <25 employees, which never convert to SQL. If SDRs excluded sub-25-employee leads from SAL routing, SAL-to-SQL would jump to ~44%
- Recommended fix: (1) Define written SQL criteria in Salesforce with required fields at stage advance, (2) Add ICP size filter to MQL scoring — companies <25 employees never qualify at Meridian's ACV

*Sales Velocity Decomposition — Lead Source:*
- Inbound organic: 38 opps/quarter, $44K ACV, 26% win rate, 48 days cycle → Velocity: $10,100/day
- Paid digital: 22 opps/quarter, $38K ACV, 18% win rate, 61 days cycle → Velocity: $2,470/day
- Events: 14 opps/quarter, $58K ACV, 31% win rate, 44 days cycle → Velocity: $5,750/day

→ **Insight:** Inbound organic has 4× the velocity of paid digital per dollar spent. Meridian should double down on SEO and content before scaling paid. Event-sourced pipeline has the highest ACV and short cycle — a prioritized investment in 2 field events per quarter would generate disproportionate returns.

*Revenue Leverage Modeling:*
If Meridian improves SAL-to-SQL conversion from 28% to 40% (matching low end of benchmark):
- Additional SQLs per quarter: +12
- Additional opportunities per year (assuming 75% SQL-to-Opp): +36
- Additional ARR at current ACV/win rate: +$399,000/year
- Implementation cost: SDR/AE alignment session + ICP filter update — <$5,000 in RevOps time
- ROI: 80× in Year 1

## Success Metrics

**Proving the RevOps system is working:**
- **Forecast accuracy:** Quarter-over-quarter forecast error rate should decrease from current baseline to <15% within 2 quarters
- **Broken stage conversion:** The single weakest funnel conversion rate should improve by ≥15% within 90 days of targeted intervention
- **CRM health score:** Should reach ≥70/100 within 60 days of remediation program (minimum threshold for reliable attribution)
- **Pipeline health distribution:** Stalled pipeline (PHS <45) should represent <15% of total pipeline value within 1 quarter
- **Marketing-sales alignment:** SAL rejection rate should decrease by ≥20%, indicating improved marketing targeting quality
- **Time-to-first-touch:** ≥80% of MQLs contacted within 4 business hours (from current baseline)

**Red flags indicating model needs adjustment:**
- Forecast accuracy doesn't improve despite stage probability recalibration → check for data entry gaming (reps advancing stages prematurely to look good)
- Pipeline health scores look high but win rate is still low → PHS component weights need recalibration against actual closed-won data
- SAL rejection rates stay flat after marketing adjusts programs → rejection taxonomy is too vague — reps are not using it properly
- Lead source attribution improves on paper but marketing ROI still unclear → "direct/none" bucket is still too large — need UTM enforcement and HubSpot/Salesforce contact source mapping audit

## Related Prompts
- [AI-Powered B2B SaaS Buying Group Scoring & MQA-to-Pipeline Conversion Analytics](../Lead-Quality-&-Conversion-Analytics/AI-Powered-B2B-SaaS-Buying-Group-Scoring-&-MQA-Pipeline-Conversion-Analytics-Intelligence-Engine.md)
- [AI-Powered B2B Marketing Pipeline Influence Scoring & Revenue Acceleration Attribution](../Attribution-&-Revenue-Analytics/AI-Powered-B2B-Marketing-Pipeline-Influence-Scoring-&-Revenue-Acceleration-Attribution-Intelligence-Engine.md)
- [AI-Powered Deal Health Scoring & Pipeline Risk Early Warning](../Funnel-Conversion-&-Pipeline-Velocity/AI-Powered-Deal-Health-Scoring-&-Pipeline-Risk-Early-Warning-Intelligence-Engine.md)
- [AI-Powered B2B Revenue Attribution Model Architecture & Unified Measurement Framework](../Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md)

## Integration Tips

**Salesforce Implementation:**
- Build a custom Opportunity score field using Salesforce Formula Fields that combines stage age, last activity date, and close date hygiene into a real-time PHS (no Apex required for basic implementation)
- Create a Salesforce Dashboard with 5 components: (1) Pipeline by health tier this week, (2) MQL-to-SAL conversion by lead source, (3) Sales velocity by AE cohort, (4) Forecast by stage with calibrated probabilities, (5) Average days in each opportunity stage vs. benchmark
- Use Salesforce Flow (formerly Process Builder) to auto-flag opportunities when PHS drops below 45 — send a Slack notification to the AE and their manager
- For forecast accuracy: build a custom "Forecast Snapshot" object that captures committed pipeline value every Friday — creates a time-series you can compare against actuals at quarter close

**HubSpot Implementation:**
- Use HubSpot's Custom Properties to replicate the PHS scoring dimensions — create calculated properties that score each component automatically
- HubSpot Workflows can trigger internal notifications to SDR managers when MQL-to-first-touch exceeds 12 hours
- Use HubSpot's Attribution Report (multi-touch) to get lead source breakdown by deal stage — the "Sessions" object in HubSpot CRM captures all UTM parameters if properly set up
- Pipeline Health: HubSpot's Deal Forecast tool can be configured with custom stage probabilities derived from your historical data via the Properties settings

**Gong/Chorus Integration:**
- Map Gong call topics (competitor mentions, pricing discussions, next steps confirmed) as a RevOps signal into Salesforce opportunity fields — this makes competitive risk flagging in PHS automated
- Use Gong Analytics → "Deals at Risk" as a validation layer for your PHS model — if Gong flags a deal as at-risk that your PHS scores as healthy, investigate the disconnect

**Data Warehouse / BI Layer:**
- Push Salesforce opportunity history (daily snapshots) to Snowflake/BigQuery using Fivetran or Census
- In dbt, build the funnel conversion rate model, sales velocity model, and forecast accuracy model as separate marts that are rebuilt nightly
- Expose via Looker/Tableau with row-level security so AEs see their own pipeline, managers see their team, and executives see company-wide
- Run the cohort conversion analysis automatically as a scheduled dbt model — output as a weekly email summary to the RevOps and marketing leadership team

## Troubleshooting

**Problem: Pipeline health scores are calculated, but AEs and managers don't use them or trust them.**
Solution: This is a change management problem, not a data problem. The fastest path to adoption is making PHS visible in the AE's daily workflow — not in a separate dashboard they have to navigate to. Embed the health score as a column in the default Salesforce "My Open Opportunities" list view, color-coded red/yellow/green. When reps see the score next to every deal every time they open Salesforce, it becomes part of their mental model within 2-3 weeks. Additionally, have sales managers reference PHS in weekly 1:1 pipeline reviews — "Your PHS on this deal dropped to 38 this week, what's your plan to get activity back?" creates behavioral accountability.

**Problem: Lead source attribution is broken — 50%+ of pipeline shows as "Direct / None" with no campaign source.**
Solution: This is a UTM hygiene and Salesforce-to-HubSpot sync problem, and it must be fixed at the source rather than retroactively assigned. Implement three changes in the same sprint: (1) UTM parameter enforcement on all paid campaigns and outbound links using a UTM builder and mandatory review in campaign launch checklist; (2) HubSpot form hidden field that captures `utm_source`, `utm_medium`, `utm_campaign` and syncs to Salesforce Lead Source on form submission; (3) Add a Salesforce validation rule that prevents a Lead from being converted to MQL status without a Lead Source value. Within 30 days, new MQL attribution will be near-100%. Retroactive cleanup requires manual enrichment or rule-based assignment for historical records — prioritize only the last 12 months for closed-won deals (for historical attribution analysis), and move on.

**Problem: The revenue leverage model says to focus on win rate improvement, but leadership wants to focus on pipeline volume.**
Solution: Use the Sales Velocity formula to quantify the tradeoff in concrete dollar terms. If win rate improvement generates $X more ARR at the same cost as pipeline volume increase but generates $0.5X, present this calculation explicitly to leadership with your CRM data backing it up. Often the preference for pipeline volume is driven by the visibility of activity metrics (meetings set, MQLs generated) vs. the invisibility of conversion rate metrics. The most persuasive argument: "We can generate 50 more MQLs per month with a $50K investment in paid media, adding $200K ARR. Or we can invest $30K in sales enablement that moves win rate from 22% to 27%, adding $380K ARR from our existing pipeline. The ROI on win rate improvement is 3× higher with 40% less investment." Show the math, and leadership will reconsider.

## Version History
- v1.0: Initial creation (auto-generated)
