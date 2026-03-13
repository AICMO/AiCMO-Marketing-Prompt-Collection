# B2B Marketing Funnel Velocity & Stage-Conversion Intelligence Engine - Real-Time Pipeline Acceleration Dashboard

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** funnel analytics, pipeline velocity, stage conversion, B2B SaaS, marketing ops, revenue operations

## Overview
Builds a comprehensive funnel velocity and stage-conversion intelligence system that measures how fast and efficiently prospects move from anonymous visitor through every pipeline stage to closed-won revenue. Use this when pipeline coverage is a concern, when marketing and sales disagree on lead quality, or when you need to identify where deals are stalling and which channels, segments, or campaigns drive the fastest path to revenue.

## Quick Copy-Paste Version

You are a senior revenue operations analyst. Analyze the B2B marketing and sales funnel for [Company Name], a [industry] company selling [product description] at [ACV range] to [buyer persona] at [company size] companies.

Using the funnel stage data below, produce a complete Funnel Velocity & Stage-Conversion Intelligence Report:

**Funnel Data (paste your numbers):**
- Stage 1 – Anonymous Visitors: [monthly volume]
- Stage 2 – Known Leads / MQLs: [monthly volume, avg days from visitor to MQL]
- Stage 3 – SQLs (Sales Accepted Leads): [monthly volume, avg days from MQL to SQL, MQL-to-SQL conversion %]
- Stage 4 – Opportunities Created: [monthly volume, avg days from SQL to Oppty, SQL-to-Oppty conversion %]
- Stage 5 – Opportunities in Late Stage (Stage 3+): [monthly volume, avg days, conversion %]
- Stage 6 – Closed Won: [monthly volume, avg deal cycle days, win rate %]
- Channel breakdown: [e.g., Paid Search: 30% of MQLs, Content/SEO: 25%, Events: 20%, Outbound: 15%, Partner: 10%]
- Segment breakdown (if available): [Enterprise vs. Mid-Market vs. SMB split]

Produce the following outputs:

**1. Funnel Velocity Scorecard**
Calculate: Monthly Funnel Velocity = (Number of Opportunities × Avg Deal Value × Win Rate) / Avg Sales Cycle Length (days)
Show current velocity, 3-month trend (improving/declining/flat), and velocity by channel.

**2. Stage-by-Stage Conversion Analysis**
For each transition (Visitor→MQL, MQL→SQL, SQL→Oppty, Oppty→Close):
- Current conversion rate vs. B2B SaaS benchmark
- Days-in-stage vs. benchmark
- Red/Yellow/Green status
- Primary bottleneck hypothesis

**3. Leakage Map**
Identify the single stage with the highest volume loss. Quantify the revenue impact of a 10% improvement at that stage. Show the compounding effect across the full funnel.

**4. Channel Velocity Ranking**
Rank each channel by: (1) time-to-MQL, (2) MQL-to-Close conversion rate, (3) average deal size, (4) overall velocity score. Flag which channels are fast-but-thin vs. slow-but-high-value.

**5. Top 5 Acceleration Recommendations**
Specific, executable recommendations to improve velocity at the top 3 bottleneck stages. Each recommendation must include: what to change, expected impact, how to measure it, and which team owns it.

**6. 90-Day Velocity Improvement Roadmap**
Week-by-week action plan with owners (Marketing, Sales, RevOps), KPIs to track, and decision checkpoints.

Format as an executive-ready report with a one-page summary at the top, followed by detailed analysis sections.

## Advanced Customizable Version

ROLE: You are a world-class Revenue Operations strategist with 15+ years optimizing B2B SaaS funnels. You combine the analytical rigor of a McKinsey consultant with the hands-on execution experience of a VP of Marketing Operations. You have deep expertise in funnel economics, attribution modeling, and the psychology of B2B buying committees.

CONTEXT:
Company: [Company Name]
Industry: [e.g., HR Tech, Cybersecurity, FinTech, DevTools]
Business Model: [B2B SaaS / Subscription / Usage-Based / Hybrid]
GTM Motion: [Inbound-led / Outbound-led / PLG / Partner-led / Hybrid]
ACV Range: [e.g., $15K–$80K]
Sales Cycle Target: [e.g., 45–90 days]
ICP: [Title, company size, industry]
CRM: [Salesforce / HubSpot / Pipedrive]
Reporting Period: [e.g., Q1 2026, trailing 90 days]

FUNNEL INPUT DATA:
[Paste your stage-by-stage data in this format:]

| Stage | Volume | Conversion Rate | Avg Days in Stage | Source Channel Split |
|-------|--------|-----------------|-------------------|---------------------|
| Visitors → MQL | [X] MQLs from [Y] visitors | [Z]% | [N] days | Paid:[%], Organic:[%], Events:[%], Outbound:[%], Partner:[%] |
| MQL → SQL | [X] SQLs | [Z]% | [N] days | [same breakdown] |
| SQL → Opportunity | [X] Opptys | [Z]% | [N] days | [same breakdown] |
| Opportunity → Late Stage | [X] | [Z]% | [N] days | |
| Late Stage → Closed Won | [X] | [Z]% win rate | [N] days | |

Segment Data (if available):
- Enterprise (>500 employees): [conversion rates by stage]
- Mid-Market (50-500): [conversion rates by stage]
- SMB (<50): [conversion rates by stage]

Historical comparison: [3 months ago / 6 months ago / same quarter last year]

OBJECTIVE:
Produce a complete Funnel Velocity & Stage-Conversion Intelligence Report that enables the CMO and VP of Revenue Operations to:
1. Pinpoint exactly where pipeline is being lost or delayed
2. Quantify the revenue opportunity of targeted improvements
3. Compare performance across channels, segments, and time periods
4. Build a data-driven 90-day acceleration roadmap

ANALYSIS FRAMEWORK — Apply ALL of the following:

**A. Funnel Velocity Formula**
Core Velocity = (# Opportunities Created × Avg Deal Value × Win Rate) / Sales Cycle Days
Calculate for: overall funnel, each channel, each segment, this period vs. prior period.

**B. Stage Health Assessment (use these B2B SaaS benchmarks)**
Apply benchmark comparisons from Forrester, Gartner, Pavilion, and SiriusDecisions data:
- Visitor→MQL: Benchmark 1–3% (content-led), 5–15% (paid, high-intent)
- MQL→SQL: Benchmark 20–40% (well-qualified ICP), red flag <15%
- SQL→Opportunity: Benchmark 50–70%, red flag <40%
- Opportunity→Late Stage: Benchmark 40–60%
- Win Rate (Late→Closed Won): Benchmark 20–40% (competitive market)
- Days: Full cycle benchmark by ACV — <$25K: 30–45 days, $25K–100K: 60–90 days, >$100K: 90–180 days

**C. Bottleneck Identification Using Theory of Constraints**
Identify the single biggest constraint in the system (not multiple problems — the one bottleneck that, if improved, would have the greatest downstream impact). Use the Goldratt TOC framework: identify, exploit, subordinate, elevate.

**D. Revenue Leakage Quantification**
For each stage transition, calculate:
- Monthly revenue leak = [volume entering stage] × [industry benchmark conversion rate - actual conversion rate] × [average deal value]
- If you could close 50% of that gap, what is the monthly revenue opportunity?

**E. Channel Efficiency Matrix**
Score each channel on 4 dimensions (1-5 scale):
- Speed (time from channel touchpoint to MQL)
- Quality (MQL-to-Close conversion rate)
- Scale (volume capacity)
- Economics (CAC vs. LTV)
Plot in a 2×2: High Quality/High Speed (double down), High Quality/Low Speed (nurture optimization), Low Quality/High Speed (ICP refinement needed), Low Quality/Low Speed (cut or restructure)

**F. Segment Velocity Analysis**
Compare Enterprise vs. Mid-Market vs. SMB:
- Which segment has the fastest velocity? Highest win rate? Best CAC payback?
- Is the company over-investing in a segment with poor funnel economics?
- Recommended segment investment reallocation

**G. Leading Indicators vs. Lagging Indicators**
Identify 3–5 leading indicators that predict funnel velocity 30–60 days in advance:
- E.g., MQL quality score trends, demo show rate, multi-stakeholder engagement rate, time-to-first-meeting
- Recommend monitoring cadence and alerting thresholds

OUTPUT SECTIONS — Produce each section in full:

**SECTION 1: Executive Summary (1 page)**
- Current funnel velocity score and trend
- Top 3 findings
- Revenue opportunity if top bottleneck is fixed
- Recommended immediate action

**SECTION 2: Funnel Velocity Scorecard**
- Overall velocity metric with period-over-period trend
- Stage-by-stage health (Red/Yellow/Green with benchmark comparison)
- Velocity by channel (ranked)
- Velocity by segment

**SECTION 3: Stage-by-Stage Deep Dive**
For each stage transition, provide:
- Current performance vs. benchmark
- Root cause hypothesis (3 potential causes ranked by likelihood)
- Specific diagnostic questions to validate root cause
- Quick win (implementable in 2 weeks)
- Strategic fix (implementable in 60–90 days)

**SECTION 4: Revenue Leakage Analysis**
- Leakage waterfall diagram (describe in text/table format)
- Top 3 highest-value improvement opportunities ranked by revenue impact
- Sensitivity analysis: What does a 5%, 10%, 20% improvement at each stage mean for monthly revenue?

**SECTION 5: Channel Intelligence**
- Channel efficiency matrix with scoring
- Recommended budget reallocation (% shifts, not just "increase X")
- Channels to double down on, optimize, or sunset

**SECTION 6: 90-Day Velocity Acceleration Roadmap**
Structure as:
- Days 1–30 (Quick Wins): What can be fixed immediately? Owner, KPI, success criteria.
- Days 31–60 (Process & Tooling): What process or system changes are needed?
- Days 61–90 (Strategic): What structural changes to ICP, channel mix, or qualification criteria?

**SECTION 7: Monitoring Framework**
- Weekly metrics to track in CRM dashboard
- Monthly review agenda (15-minute stand-up format)
- Quarterly deep-dive checklist
- Alert thresholds that should trigger immediate investigation

CONSTRAINTS:
- Every recommendation must be executable without a systems overhaul
- Quantify the impact of each recommendation in dollars (not just %)
- Flag assumptions clearly — if you've used benchmark data, note it
- Do not recommend "hire more people" as a primary solution
- All quick wins must be achievable by a team of 3–5 marketers within 2 weeks
- Format tables for easy copy-paste into Google Slides or Notion

OUTPUT FORMAT: Executive report with numbered sections, tables where appropriate, and a separate "Action Items" summary at the end listing every recommended action with owner (Marketing/Sales/RevOps), timeline, and expected impact.

## Example Input/Output

**Example Input:**
Company: Structify (B2B SaaS, construction project management)
GTM: Inbound-led + Outbound hybrid
ACV: $28K
Sales Cycle Target: 60 days

Funnel Data (trailing 90 days):
- Visitors → MQL: 45,000 visitors → 810 MQLs (1.8% conversion, avg 4 days to MQL)
- MQL → SQL: 810 MQLs → 162 SQLs (20% conversion, avg 8 days in MQL stage)
- SQL → Opportunity: 162 SQLs → 73 Opportunities (45% conversion, avg 6 days)
- Opportunity → Late Stage: 73 → 29 (40%, avg 28 days)
- Late Stage → Closed Won: 29 → 12 (41% win rate, avg 22 days)
- Channel split: Paid Search 35% of MQLs, Organic SEO 30%, Outbound SDR 20%, Events 15%
- Segment: 70% Mid-Market ($28K ACV), 30% SMB ($9K ACV)

**Example Output (excerpted):**

**EXECUTIVE SUMMARY**

Current Monthly Funnel Velocity: $187,200/month
(4 deals/month × $28K avg × 41% close rate × 12/68-day cycle = $24,706/month velocity score)
Trend: Declining 12% vs. prior quarter.

**Critical Finding:** The MQL-to-SQL stage is your primary bottleneck. At 20% conversion (benchmark: 30–40%), Structify is losing an estimated $84,000/month in pipeline before it ever reaches sales. This is not a lead quality problem — it's a lead routing and sales acceptance criteria problem.

**Revenue Opportunity:** Improving MQL→SQL conversion from 20% to 30% adds approximately $42,000/month in incremental pipeline value without changing ad spend or traffic.

**Immediate Action:** Within 5 business days, audit MQL rejection reasons in CRM. Our hypothesis: 40–60% of rejected MQLs are being rejected for company-size reasons (SMB being submitted into a Mid-Market pipeline). Fix the routing logic before spending another dollar on demand gen.

---

**SECTION 2: FUNNEL VELOCITY SCORECARD**

| Stage | Volume | Conversion | Benchmark | Days | Benchmark | Status |
|-------|--------|------------|-----------|------|-----------|--------|
| Visitor → MQL | 45K → 810 | 1.8% | 2–5% | 4 days | 3–7 days | 🟡 Yellow |
| MQL → SQL | 810 → 162 | 20% | 30–40% | 8 days | 5–10 days | 🔴 Red |
| SQL → Oppty | 162 → 73 | 45% | 50–70% | 6 days | 3–7 days | 🟡 Yellow |
| Oppty → Late | 73 → 29 | 40% | 40–60% | 28 days | 20–35 days | 🟢 Green |
| Late → Won | 29 → 12 | 41% | 25–45% | 22 days | 15–30 days | 🟢 Green |

**Channel Velocity Ranking:**
1. Organic SEO: Slow to MQL (11 days avg) but 38% MQL→Close rate — highest quality, under-invested
2. Paid Search: Fast (2 days to MQL) but 18% MQL→Close rate — volume-heavy, quality-light
3. Events: 22% MQL→Close, highest ACV ($34K avg) — scale constraint
4. Outbound SDR: 31% MQL→Close, 19-day cycle — strong performer, capacity-constrained

**SECTION 6 (excerpt): 90-Day Roadmap**

**Days 1–30 (Quick Wins — Marketing + RevOps):**
- Day 1–5: Audit 100 rejected MQLs from last 60 days. Tag rejection reason. (RevOps owns)
- Day 5–10: Fix CRM routing to separate SMB ($<15K) into separate queue with different SLA. (RevOps)
- Day 10–20: Implement lead scoring rule: companies >50 employees automatically score +15 points. (Marketing Ops)
- Day 20–30: Launch SDR SLA tracking — any MQL >4 hours without first touch gets Slack alert to manager. (Sales Ops)
Expected impact: MQL→SQL improvement from 20% → 26% within 30 days = +$25K/month pipeline.

## Success Metrics

A high-quality output from this prompt should deliver:
- **Quantified revenue leakage** at each stage (specific dollar amounts, not vague percentages)
- **Benchmarked performance** with explicit source framework (SiriusDecisions, Forrester, or noted as estimate)
- **Single-constraint identification** — one primary bottleneck, not a laundry list
- **Channel ranking** with a recommended budget reallocation that adds up to 100%
- **Actionable 90-day roadmap** where every action has an owner and a measurable KPI
- **Leading indicators** identified that allow the team to see velocity changes 30–60 days before they appear in pipeline

If the output only provides generic advice ("improve lead quality," "align marketing and sales"), the prompt wasn't given sufficient data. Provide real numbers from your CRM and re-run.

## Related Prompts

- [`./Marketing-Performance-Dashboard-Generator.md`](./Marketing-Performance-Dashboard-Generator.md) — Build the full marketing KPI dashboard that houses this velocity data
- [`./Dark-Funnel-Unattributed-Pipeline-Intelligence-Engine.md`](./Dark-Funnel-Unattributed-Pipeline-Intelligence-Engine.md) — Identify pipeline influence that isn't captured in your funnel data
- [`../Campaign-Performance-Analysis/Funnel-Performance-Diagnostics.md`](../Campaign-Performance-Analysis/Funnel-Performance-Diagnostics.md) — Deep-dive diagnostic when the velocity engine flags a broken stage
- [`../Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md`](../Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md) — Understand which campaigns are generating the highest-velocity pipeline

## Integration Tips

**Salesforce:** Build a Salesforce report using "Opportunities with Contact Roles and Campaigns" object. Pull Stage Duration (days in each stage) as a custom field. Export to Google Sheets monthly and paste into this prompt. For automation, use Salesforce Flow to calculate and store stage entry/exit timestamps in custom fields.

**HubSpot:** Use the "Deal Pipeline" report with "Time in Stage" enabled. Export via HubSpot Reports → Custom Reports → Pipeline Stage Duration. For real-time monitoring, connect HubSpot to Databox or Klipfolio for live velocity scoring.

**Google Sheets Velocity Tracker:** Create a master Google Sheet with tabs for each funnel stage. Use IMPORTDATA() to pull CRM exports weekly. Build a SUMPRODUCT formula to calculate monthly velocity score. Share with the Slack channel #revenue-ops for weekly review.

**Notion Operations Hub:** Paste the output directly into a Notion database as a "Quarterly Funnel Review" page. Use Notion AI to auto-summarize the top 3 actions and assign them to team members via Notion tasks.

**Zapier Automation:** Set up a Zap that triggers when a deal has been in the same CRM stage for more than [N] days (configurable). The Zap fires an alert to Slack + creates a HubSpot task for the rep + notifies the marketing manager. This implements the "velocity alert" system recommended in Section 7.

**Looker Studio:** Connect your CRM via native connector. Build a funnel visualization using the Google Funnel Chart in Looker Studio, with date range controls. Embed the report in your weekly CMO dashboard alongside CAC and LTV metrics.

## Troubleshooting

**Problem: The AI gives generic recommendations without specific revenue numbers.**
Fix: You haven't provided actual funnel volume and ACV data. Go to your CRM and pull a report for the last 90 days showing: (1) number of leads entering each stage, (2) number exiting each stage, (3) days in stage for each deal. Without volume + ACV + cycle time, the engine can't run the velocity formula. Even rough estimates (e.g., "approximately 200 MQLs/month") are better than nothing.

**Problem: Benchmark comparisons don't match our business model.**
Fix: Add your business model context explicitly: "We are usage-based pricing, not seat-based SaaS — our deals typically involve a technical champion POC before executive approval." The engine will adjust benchmarks. Usage-based companies often see longer SQL→Oppty stages (technical evaluation) but shorter Oppty→Close (no procurement) — the defaults assume traditional seat-based SaaS.

**Problem: Channel data isn't available by stage (only top-of-funnel attribution).**
Fix: Start with what you have. Provide top-of-funnel channel split and ask the engine to identify which channels are most likely driving quality problems based on their traffic characteristics (intent level, audience targeting, content type). Then implement UTM tracking and CRM campaign influence tracking to get full-funnel channel data within 60 days. The engine will output a "data gaps" section telling you exactly what to instrument.

## Version History
- v1.0: Initial creation (auto-generated 2026-03-13)
