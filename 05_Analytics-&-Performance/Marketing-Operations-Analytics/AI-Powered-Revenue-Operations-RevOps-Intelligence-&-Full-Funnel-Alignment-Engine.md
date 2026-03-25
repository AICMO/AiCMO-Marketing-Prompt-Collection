# AI-Powered Revenue Operations (RevOps) Intelligence & Full-Funnel Alignment Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** revops, revenue-operations, full-funnel, pipeline-alignment, marketing-ops, sales-ops, cs-ops, b2b, saas, analytics, handoffs

## Overview

Audits the structural alignment between marketing operations, sales operations, and customer success operations to expose the handoff gaps, metric disagreements, and process breaks that silently drain pipeline velocity and expansion revenue — then produces a unified RevOps operating model with shared KPIs, tiered SLA agreements, governance cadence, and a live revenue intelligence dashboard that gives every revenue function a single source of truth.

## Quick Copy-Paste Version

You are a senior Revenue Operations strategist. Audit our go-to-market alignment and build a unified RevOps operating model.

Current state:
- Business model: [B2B SaaS / sales-led / PLG / hybrid]
- ARR: [$XM] | ACV: [$X] | Sales cycle: [X days]
- Marketing team owns: [MQL definition, pipeline sourcing %, budget]
- Sales team owns: [SDR/AE split, quota structure, CRM hygiene]
- CS team owns: [renewal rate, NRR target, expansion quota]
- Where we feel misaligned: [e.g., "sales says leads are garbage, marketing says sales doesn't follow up, CS isn't looped in until 30 days before renewal"]
- Current shared metrics: [e.g., "we all report pipeline but on different slides with different numbers"]
- CRM: [Salesforce / HubSpot / other] | MAP: [Marketo / HubSpot / Pardot]

Produce:
1. Revenue Funnel Diagnostic — map every handoff from anonymous visitor to closed-won to renewed customer, identify where accountability breaks down and revenue leaks
2. Unified Metrics Framework — define 10 shared KPIs that every revenue function agrees to own, with calculation methodology, data source, and owner
3. SLA Stack — design a tiered handoff SLA for MQL→SQL→SAL→Close→Onboard→Expand with response time standards, escalation rules, and automated enforcement mechanisms
4. RevOps Governance Model — weekly/monthly/quarterly meeting cadence with agenda templates, attendee matrix, and escalation path
5. Revenue Intelligence Dashboard Blueprint — specify every tile, metric, filter, and data source for a single cross-functional dashboard that eliminates the "different numbers" problem
6. 90-Day RevOps Activation Roadmap — prioritized actions to move from current misalignment to functional RevOps in 90 days without a dedicated RevOps hire

Output as a structured, actionable report. All recommendations must include the specific tool, field, or workflow to configure — no abstract advice.

## Advanced Customizable Version

ROLE: You are a world-class Revenue Operations architect who has built unified RevOps functions at 40+ B2B SaaS companies from Series A through IPO. You specialize in diagnosing funnel misalignment, designing shared accountability frameworks, and building the operational infrastructure that turns fragmented marketing/sales/CS silos into a single, data-driven revenue machine. You know that most pipeline problems are actually process and data problems in disguise — and you fix both simultaneously.

CONTEXT:
Company: [Company name and stage]
Business model: [B2B SaaS / PLG / sales-led / hybrid / marketplace]
ARR: [$XM] | Monthly recurring revenue: [$XM] | Growth rate: [X% YoY]
ACV: [$X] | ASP: [$X] | Sales cycle median length: [X days]
ICP: [Company size, industry, persona — be specific]

Revenue team structure:
- Marketing: [headcount, key roles, owns what part of the funnel]
- Sales Development (SDR/BDR): [headcount, inbound vs. outbound split, reports to marketing/sales/RevOps]
- Account Executive: [headcount, segments covered — SMB/Mid/Enterprise]
- Customer Success: [headcount, structure — high-touch / pooled / digital CS, owns renewal/expansion]
- RevOps (if exists): [headcount, current scope — often just one person or none]

Current metric landscape — provide the numbers each team currently reports:
- Marketing reports: [MQLs/month, pipeline sourced, CPL, conversion rate to SQL]
- Sales reports: [SQLs/month, pipeline created, win rate, ACV, sales cycle]
- CS reports: [NRR, gross retention, expansion ARR, health score distribution]
- Leadership sees: [what dashboard does exec team actually review?]

Known dysfunction — describe the last 3 cross-functional friction points:
1. [e.g., "Q3 QBR: marketing showed 420 MQLs, sales showed 180 SQLs, nobody agreed on why the gap was 56%"]
2. [e.g., "CS doesn't find out about expansion opportunities until SDR accidentally calls an existing customer"]
3. [e.g., "Deal slippage blamed on marketing ICP mismatch but nobody has data to prove or disprove it"]

Funnel metrics you can currently pull (list what's measurable today):
[e.g., "We can see MQL count, demo requests, closed-won count, NRR — but we can't see MQL→SQL conversion by source, or time-in-stage for each deal"]

OBJECTIVE: Build a complete Revenue Operations Intelligence Framework with the following modules:

---

MODULE 1: FULL-FUNNEL ACCOUNTABILITY MAP

Reconstruct the end-to-end revenue journey from first anonymous touch to renewed and expanded customer. For each stage, identify:

Stage definition:
- Anonymous Visitor → Marketing Qualified Lead (MQL)
- MQL → Sales Accepted Lead (SAL)
- SAL → Sales Qualified Opportunity (SQO/SQL)
- SQO → Closed-Won
- Closed-Won → Activated Customer (time-to-first-value milestone)
- Activated → Expanded (expansion ARR event)
- Expanded → Renewed (renewal ARR event)

For each stage transition, document:
1. Entry criteria: exact field values, behaviors, or scores that define when a record moves to the next stage (specify CRM field names)
2. Accountable owner: the role responsible for advancing the record — not a team, a specific role title
3. Expected time-in-stage: benchmark + our target (e.g., MQL-to-SAL: industry benchmark 4 hours for Tier 1 intent, our current average: [X])
4. Handoff mechanism: how does the receiving team get notified? (CRM assignment rule, Slack alert, email notification — specify the exact tool and trigger)
5. Rejection protocol: if a record doesn't meet entry criteria or is disqualified, what happens to it? Who owns the recycled/nurture path?
6. Data required at handoff: the minimum fields populated for the handoff to be considered complete (incomplete handoffs are the #1 cause of SDR/CS drop-offs)

Revenue Leak Detection: Calculate the conversion rate and average time-in-stage for each transition. Flag stages where:
- Conversion rate is below category benchmarks (provide benchmarks: MQL→SAL: 50-70% for well-tuned funnel; SAL→SQO: 35-55%; SQO→Close: 20-30% for enterprise, 25-40% for mid-market/SMB)
- Average time-in-stage is 2× the benchmark (indicates stuck deals or process breakdown)
- Attribution data is missing (indicates data capture gap)

Quantify total pipeline at risk: for each leak point, calculate:
(Monthly volume at that stage) × (Gap vs. benchmark conversion %) × (Downstream ACV) = Monthly revenue impact of the leak

---

MODULE 2: UNIFIED REVENUE METRICS FRAMEWORK

Design the 10 non-negotiable shared KPIs that every revenue function must agree to report identically. For each KPI:

1. Metric name and category (Pipeline Health / Velocity / Efficiency / Customer Health)
2. Precise definition: what exactly is counted and what is excluded (e.g., "Pipeline Coverage: total open pipeline value with close date in next 90 days, excluding stalled opportunities with no activity in >21 days, divided by quarterly revenue target")
3. Exact data source: CRM object, field name, report name, filter logic
4. Calculation methodology: write out the formula step by step
5. Owner: the role accountable for the number's accuracy — this person defends the metric in QBR
6. Reporting cadence: weekly (pipeline metrics), monthly (funnel conversion), quarterly (efficiency and growth)
7. Target for current stage: specific number, not a range (e.g., "Pipeline Coverage: 3.5× quarterly target")
8. Alert threshold: the level that triggers cross-functional escalation (e.g., "Pipeline Coverage below 2.5× → automatic RevOps review call within 48 hours")

The 10 metrics MUST include:
- Pipeline Coverage Ratio (rolling 90-day)
- MQL-to-Close Rate by source/channel
- Sales Cycle Velocity by segment and source
- Win Rate by competitive scenario, deal size, and ICP fit score
- Average Contract Value trend (new logo vs. expansion)
- Time-to-Revenue (closed-won to first invoice paid)
- Net Revenue Retention (gross retention × expansion rate)
- Customer Acquisition Cost by channel (fully loaded: marketing spend + SDR + AE time)
- CAC Payback Period by segment
- Expansion Pipeline Coverage (CS-sourced upsell/cross-sell opportunities in flight)

For each metric, write a one-paragraph "Why This Metric Exists" statement suitable for presenting to the board — explaining what business decision it informs, not just what it measures.

---

MODULE 3: TIERED HANDOFF SLA ARCHITECTURE

Design a three-tier SLA system that governs every cross-functional handoff. Tiers are based on revenue signal strength:

**Tier 1 — High Intent Signals (requires fastest response)**
Qualifying signals: Pricing page visit + >2 pages viewed in session, demo request form submitted, free trial activation with product usage signal, high-intent chat conversation, direct "I want to buy" email reply to sequence

Marketing → SDR: Routing time ≤2 minutes (automated CRM assignment rule, Slack/SMS push to assigned SDR)
SDR first outreach: ≤15 minutes during business hours; ≤30 minutes for first business hour next day if after hours
SDR → AE escalation: ≤24 hours if SDR cannot connect after 3 attempts across 2 channels
Escalation path if missed: auto-reassign to next SDR in round-robin + notify SDR manager + log SLA miss in CRM

For Tier 1, specify exact implementation:
- CRM assignment rule logic (field conditions, assignment pool, round-robin vs. ownership rules)
- Slack/SMS notification tool and configuration (e.g., Chili Piper, LeanData, or native Salesforce flow)
- Fallback handling if primary SDR is OOO

**Tier 2 — Mid Intent Signals**
Qualifying signals: MQL score threshold hit via behavioral scoring, attended webinar + viewed specific product page, multiple return visits within 7 days, email click on bottom-of-funnel content

Marketing → SDR: Routing ≤30 minutes
SDR first outreach: ≤2 hours same business day; ≤next business morning if received after 3pm local
Minimum touch sequence before recycling: 5 touches across 3 channels over 10 business days
Recycle path: return to nurture stream with trigger to re-MQL if specific intent signals recur

**Tier 3 — Low Intent Signals**
Qualifying signals: Content download, newsletter subscription, webinar registration (no-show), top-of-funnel ad click-through

SDR awareness: Logged in CRM for context, but no active outreach unless combined with Tier 2+ signal
Nurture responsibility: Marketing automation sequence, no SDR touchpoint
Escalation to Tier 2: if Tier 3 contact triggers a Tier 2 signal within 30 days, auto-promote and notify SDR

**Marketing → CS Expansion Handoff (often the most neglected SLA)**
Trigger: Marketing identifies expansion signal — customer visits upgrade pricing page, attends feature webinar, submits NPS 9-10 with expansion comment, engages with upsell email sequence
CS response: ≤24 hours — CS logs expansion conversation in CRM expansion opportunity record
Escalation: If CS doesn't log activity within 48 hours → auto-alert CS manager + RevOps
Why this matters: Expansion pipeline discovered by marketing but not acted on within 5 business days has 60% lower conversion rate than acted-on within 24 hours (per Gainsight benchmark data)

**SLA Compliance Enforcement Architecture:**
Specify the exact reports, dashboard tiles, and automated alerts needed to monitor SLA compliance without manual tracking:
- Weekly SLA compliance report by tier and SDR (CRM native report)
- Alert: if SLA miss rate for Tier 1 exceeds 15% in any week → auto-notify VP Sales and CMO
- Monthly SLA scorecard in RevOps QBR — show trend, call out teams or individuals below target
- Consequence framework: SLA misses logged in rep performance record for coaching conversations (not punitive; diagnostic)

---

MODULE 4: REVOPS GOVERNANCE MODEL

Design the meeting architecture that drives cross-functional accountability without creating meeting bloat. Each meeting must have:
- Purpose (one sentence — what decision or insight does this generate?)
- Attendees (roles only, not names)
- Frequency
- Duration (strict cap — no RevOps meeting should exceed 60 minutes)
- Pre-work required (what each attendee must prepare before entering)
- Agenda (time-boxed segments)
- Output (what leaves the meeting: decision logged, action item created, dashboard updated)
- Owner (who runs it and is accountable for the output)

**Weekly Revenue Pulse (15 minutes)**
Purpose: Surface pipeline coverage risk for the current quarter and unblock stalled deals before end-of-week
Attendees: VP Sales (or Sales Manager), CMO (or Demand Gen), RevOps lead
Pre-work: Pipeline coverage ratio vs. 3.5× target, deals at risk (>21 days no activity), top 10 open opportunities with next step and close date
Agenda: Pipeline coverage check (5 min) → At-risk deal review (7 min) → Action items (3 min)
Output: 3-5 named deals with specific next steps logged in CRM by EOD

**Monthly Revenue Review (45 minutes)**
Purpose: Diagnose full-funnel conversion performance and identify the single biggest lever to pull in the next 30 days
Attendees: CMO, VP Sales, VP CS, RevOps, Finance/FP&A
Pre-work: 10 shared KPI dashboard reviewed asynchronously; each function submits a 3-slide: (1) What happened, (2) Why it happened, (3) What we'll do differently
Agenda: Metrics review (10 min) → Root cause discussion on the 1-2 metrics that missed target (20 min) → Decision on corrective action and owner (10 min) → 30-day commitments (5 min)
Output: Written decision log with owner and deadline; logged in shared RevOps wiki

**Quarterly Business Review — RevOps Edition (60 minutes)**
Purpose: Assess full-year trajectory, validate ICP and channel ROI assumptions, make resource allocation decisions for the next quarter
Attendees: CEO/CRO, CMO, VP Sales, VP CS, RevOps, Finance
Pre-work: Full RevOps dashboard with YTD vs. plan; win/loss analysis by segment; cohort analysis of customers acquired this quarter (health score at 90 days); pipeline forecast vs. required for next quarter
Agenda: YTD scorecard (10 min) → Win/loss and ICP analysis (15 min) → Next quarter pipeline build plan (20 min) → Resource and investment decisions (15 min)
Output: Q[X+1] demand plan with owned targets by channel; budget reallocation decisions documented; ICP refinements logged for marketing and SDR team

---

MODULE 5: REVENUE INTELLIGENCE DASHBOARD BLUEPRINT

Design the single dashboard that eliminates every team having different numbers. Specify:
- Platform: [Salesforce Einstein Analytics / HubSpot Reports / Looker / Tableau / Metabase — choose based on company's stack]
- Access: all revenue team members view, RevOps edits, CMO/CRO/VP CS are primary consumers

**Section 1: Pipeline Health (top of dashboard)**
Tile 1: Pipeline Coverage Ratio — Current quarter open pipeline / Revenue target. Data: Salesforce Opportunities where Close Date = current quarter AND Stage ≠ Closed. Color: Green >3.5×, Yellow 2.5-3.5×, Red <2.5×
Tile 2: Pipeline by Source — bar chart, this quarter's open pipeline split by Lead Source (Marketing Generated / SDR Outbound / Partner / Customer Referral / Other). Filters: by segment, by rep
Tile 3: New Pipeline Created This Week — Salesforce Opportunities created this week, by source and segment. Trend line vs. prior 4 weeks
Tile 4: Deals at Risk — count of open opportunities with close date in <30 days AND no CRM activity in >14 days. Click-through to deal list

**Section 2: Funnel Conversion (center)**
Tile 5: Full-Funnel Waterfall — Visitors → MQLs → SALs → SQOs → Closed-Won this month vs. prior month vs. same month last year. Conversion rate displayed at each stage
Tile 6: MQL-to-Close Rate by Source — table showing each marketing channel's end-to-end conversion and average ACV. This is THE metric that kills the "marketing says leads are good, sales says they aren't" argument
Tile 7: Time-in-Stage Heatmap — average days in each funnel stage by segment. Flags stuck stages immediately

**Section 3: Velocity and Efficiency (lower)**
Tile 8: Sales Cycle Velocity by Segment and Source — trend by month. Includes: avg days from SQL to Closed-Won, broken down by SMB/Mid/Enterprise and by Lead Source
Tile 9: Win Rate by Competitive Scenario — table: deal won/lost/no-decision × named competitor × segment × ACV band. Refreshes weekly from CRM opportunity records
Tile 10: CAC by Channel — rolling 3-month average. Formula: (Channel spend + SDR time attribution + AE time attribution) / New customers from channel. Data sources: marketing spend tracker, CRM time logs, new customer records

**Section 4: Customer Health and Expansion**
Tile 11: NRR Trend — rolling 12-month, by cohort and segment. Gross retention × expansion rate
Tile 12: Expansion Pipeline — open expansion opportunities (upsell/cross-sell) in CS-owned pipeline, by stage and close date. Compare vs. expansion target
Tile 13: At-Risk Renewal Radar — customers with renewal in next 90 days AND health score below threshold. Owner assigned, escalation status logged

For each tile, specify: exact Salesforce/HubSpot report name, object queried, filters applied, and the insight it generates when actioned.

---

MODULE 6: REVOPS OPERATING MODEL ACTIVATION ROADMAP

**Days 1-14: Alignment and Audit**
- Convene first joint session: CMO, VP Sales, VP CS, RevOps. Present funnel accountability map from Module 1. Ask: "Where do you disagree with this map?" — disagreements reveal the misalignment
- Document current metric definitions in writing — request each team to submit how they calculate their top 3 metrics. Differences will be immediate (e.g., Marketing counts form-fills as MQLs; Sales only counts SQLs with a call booked)
- Baseline the 10 shared KPIs with current actuals — even if methodology changes, document where you start
- Audit CRM data completeness: run a report on all Opportunities created in the last 6 months, check % populated for: Lead Source, Lead Source Detail, Competitor, Close Date accuracy, Stage accuracy, Amount, Contact Role. Any field below 80% populated is a data integrity issue blocking RevOps analytics

**Days 15-45: Infrastructure Build**
- Implement tiered SLA system: configure CRM assignment rules, Slack/SMS alerts, and SLA compliance reports
- Build unified definitions doc: one Google Doc or Notion page with every metric definition, formula, and owner — all three teams sign off
- Begin building Revenue Intelligence Dashboard: start with the 4 most-contested metrics first (Pipeline Coverage, MQL-to-Close by Source, Win Rate, NRR)
- Establish weekly Revenue Pulse cadence — book recurring 15-minute meeting, assign pre-work rules

**Days 46-75: Governance and Adoption**
- Run first Monthly Revenue Review with new format — use the meeting to surface 2-3 decisions that require cross-functional input
- Deploy full Revenue Intelligence Dashboard — give all revenue team members access
- Train SDR/CS teams on SLA expectations and how the monitoring system works — critical that enforcement is seen as coaching, not surveillance
- Implement expansion handoff protocol: configure CS expansion opportunity record in CRM, set up marketing-to-CS alert for expansion signals

**Days 76-90: Optimization and Scale**
- Review first 90 days of SLA compliance data: which SLAs are being missed, by whom, and why? Adjust targets if systemically impossible, fix process if feasible but ignored
- Present RevOps QBR #1: retrospective on the 90-day activation, demonstrate improvement in the metrics that were most broken, set Q[X+1] targets
- Publish the RevOps Operating Manual: governance model, metrics definitions, SLA architecture, dashboard guide — this document survives personnel changes

---

CONSTRAINTS:
- All metric definitions must be written precisely enough that two different analysts pulling from the same CRM produce identical numbers — vagueness is the enemy of alignment
- Every SLA must include an automated enforcement mechanism (CRM rule, alert, report) — SLAs enforced only by human memory fail within 60 days
- The dashboard must be buildable in the company's existing BI/CRM stack — do not design something that requires a $200K data warehouse project
- RevOps governance meetings must replace existing meetings, not add to them — identify which existing meeting each new cadence replaces

OUTPUT FORMAT:
1. Executive Summary (one page): Current funnel health score, top 3 misalignment points with revenue impact in dollars, 90-day activation plan summary
2. Full-Funnel Accountability Map with revenue leak quantification
3. Unified Metrics Framework — the 10 KPIs with full specifications
4. Tiered SLA Architecture with implementation instructions
5. Governance Calendar — visual meeting cadence with agenda templates
6. Dashboard Blueprint — tile-by-tile specifications
7. 90-Day Activation Roadmap with named owners and success metrics

## Example Input/Output

**Input:**
Company: Vantage Cloud (B2B SaaS, Series B, $18M ARR, sales-led)
ACV: $42K | Sales cycle: 68 days median | ICP: 200-2,000 employee companies, VP Ops/IT, financial services and logistics
Marketing: 4-person team (CMO, demand gen, content, MOps). Reports: 310 MQLs/month, $4.2M pipeline sourced
Sales: 6 AEs + 4 SDRs. Reports: 180 SQLs/month, 24% win rate, $48K average deal
CS: 3 CSMs. Reports: 87% gross retention, 108% NRR
Known issues: "Marketing and sales have been in a cold war for two quarters. Marketing says they're hitting MQL targets. Sales says 60% of MQLs are junk. CS says they only find out about upsell opportunities when a customer calls in. Nobody has agreed on what an MQL is."
Current CRM: Salesforce. MAP: HubSpot.

**Output (excerpt):**

**FULL-FUNNEL REVENUE LEAK ANALYSIS — VANTAGE CLOUD**

| Stage | Monthly Volume | Conversion Rate | Benchmark | Gap | Revenue at Risk |
|-------|---------------|-----------------|-----------|-----|-----------------|
| MQL → SAL | 310 → 180 | 58% | 60-70% | 5-12% below | $94,500/mo |
| SAL → SQO | 180 → 94 | 52% | 55-65% | 3-13% below | $126,000/mo |
| SQO → Close | 94 → 22 | 23% | 25-30% | 2-7% below | $84,000/mo |
| **Total pipeline at risk** | | | | | **$304,500/mo** |

*Basis: gaps below benchmark lower end × ACV $42K × stage volume*

---

**ROOT CAUSE: THE MQL DEFINITION CRISIS**

The 310 MQLs Marketing reports vs. 180 SQLs Sales reports is not a 42% drop — it's a definitional mismatch revealing that Marketing and Sales are measuring different objects.

Current Marketing MQL definition (inferred from HubSpot): Lead Score ≥ 60 points, where score is built from email opens (5 pts each), page views (2 pts each), webinar registration (10 pts), form fill (25 pts). No ICP filter applied.

Current Sales SQL definition (inferred from Salesforce): AE or SDR manually marks a lead as SQL after a qualifying call confirming budget, authority, need, and timeline.

The 130-record gap (310 minus 180) is not "junk leads" — it's the leads that Marketing's scoring counts as qualified but which never received SDR outreach because:
(a) 43 were existing customers re-engaging (no ICP filter in MAP)
(b) 31 were from company sizes outside ICP (scored highly but wrong segment)
(c) 56 were legitimate new prospects that never received SDR first contact within SLA window (routing delay of >18 hours average for Tier 1 signals)

**Fix:** Redefine MQL with a joint Marketing/Sales working session to add 3 disqualifying conditions to HubSpot scoring: (1) exclude accounts already in Salesforce as customers, (2) exclude company size <100 employees and >5,000 employees, (3) add ICP industry filter (financial services or logistics only). Estimated outcome: MQLs drop to ~195/month but SQL conversion rises to 72% — resulting in 140 SQLs/month from better-qualified leads vs. 180 from inflated count.

Pipeline impact: 140 SQLs × 25% SQO conversion × 24% win rate × $42K ACV = $352,800 monthly closed-won pipeline vs. current 180 × 52% × 23% × $42K = $454,000 (wait — let me recalculate with the improvement)

Current state: 180 SALs × 52% → 94 SQOs × 23% → 21.6 closes × $42K = $907,200 quarterly
Improved state: 140 SALs × 72% → 101 SQOs × 27% → 27.3 closes × $42K = $1,146,600 quarterly

Fixing the MQL definition alone = **+$239,400 incremental quarterly pipeline without spending a dollar more on demand generation**.

---

**CS EXPANSION HANDOFF: THE $200K PROBLEM**

Current state: CS team discovers expansion opportunities only when customers call in or at scheduled QBR (quarterly for most accounts). Marketing identified 23 expansion signals last quarter (customers visiting upgrade pricing page, clicking upsell email links) — none were routed to CS.

Revenue impact: Expansion pipeline conversion from marketing-sourced signals: 35-45% (Gainsight 2024 benchmark). Vantage Cloud missed expansion opportunities from 23 signals × average expansion ACV $18K × 40% conversion = $165,600 in potential expansion ARR per quarter missed because the handoff protocol does not exist.

Fix implementation (Salesforce):
1. Create Expansion Opportunity record type in Salesforce with required fields: Signal Type, Source, Account, CS Owner, First CS Touch Date
2. Configure HubSpot workflow: Contact triggers expansion signal (pricing page visit OR clicks upsell email link) → create Salesforce Task assigned to CS Account Owner with 24-hour due date → if Task not updated within 24 hours, create Escalation Task assigned to VP CS
3. Build Salesforce report: Expansion Opportunities by Source × Stage × CS Owner, filtered to opportunities created in last 30 days. Add to CS weekly standup deck
4. Implementation time: 3.5 hours for a MOps analyst

---

## Success Metrics

**Green (RevOps operating at full effectiveness):**
- All 10 shared KPIs calculated identically across marketing, sales, and CS dashboards
- Tier 1 SLA compliance ≥90% (SDR first touch ≤15 minutes)
- Tier 2 SLA compliance ≥85%
- Pipeline coverage ratio maintained ≥3.5× quarterly target
- MQL-to-Close rate tracked by channel with ≤2-week data lag
- Monthly Revenue Review held on schedule with all attendees and pre-work completed ≥90% of months

**Yellow (watch):**
- Tier 1 SLA compliance 75-90%
- Pipeline coverage between 2.5× and 3.5×
- Any KPI definition disputed by two or more teams in the same QBR

**Red (act immediately — RevOps breakdown):**
- Tier 1 SLA compliance below 75% (revenue is actively leaking from slow follow-up)
- Pipeline coverage below 2.5× with <45 days left in quarter (demand emergency)
- Marketing and Sales reporting pipeline numbers that differ by >15% (definitional misalignment has re-emerged)
- CS expansion pipeline coverage below 1.5× expansion target (upsell motion is broken)

## Related Prompts

- [AI-Powered Marketing Operations Velocity & Campaign Execution Efficiency Intelligence Engine](../Marketing-Operations-Analytics/AI-Powered-Marketing-Operations-Velocity-&-Campaign-Execution-Efficiency-Intelligence-Engine.md)
- [Marketing Operations Data Quality & CRM Hygiene Intelligence Engine](../Marketing-Operations-Analytics/Marketing-Operations-Data-Quality-&-CRM-Hygiene-Intelligence-Engine.md)
- [Marketing Lead Quality & Sales Handoff Intelligence Engine](../Lead-Quality-&-Conversion-Analytics/Marketing-Lead-Quality-&-Sales-Handoff-Intelligence-Engine.md)
- [Marketing Funnel Conversion & Pipeline Velocity Intelligence Engine](../Funnel-Conversion-&-Pipeline-Velocity/Marketing-Funnel-Conversion-&-Pipeline-Velocity-Intelligence-Engine.md)

## Integration Tips

**Salesforce:**
Build a RevOps Command Center dashboard using Salesforce native reports and Einstein Analytics (or CRM Analytics). Create the Pipeline Coverage tile using a custom report on Opportunities filtered to current quarter close date and open stages, then divide by the ARR target stored in a custom metadata type that RevOps updates each quarter. For the MQL-to-Close by Source tile, create a Salesforce report joining Lead Source (from the first Opportunity Contact Role record) to Closed Won Opportunities — this requires ensuring Lead Source is mapped from the original lead to the opportunity at creation, which is a common CRM hygiene fix.

For SLA enforcement: use Salesforce Flow (Process Builder replacement) to create time-triggered escalation actions. Flow trigger: Opportunity or Lead record created → wait 15 minutes → check if Activity exists in last 15 minutes → if no, send Slack notification via Salesforce Slack integration to assigned SDR plus their manager. This runs automatically without any manual monitoring.

**HubSpot:**
Use HubSpot's Contact Activity timeline and Custom Reports builder to create the funnel waterfall view. Build a Funnel Report with stages mapped to HubSpot lifecycle stages (Lead → MQL → SQL → Customer). For expansion signals, use HubSpot's Smart Lists to create a dynamic "Expansion Signal — Pricing Page" list segmented to existing customers only (Contact property: "Became Customer Date" is known + Page View contains "/pricing/upgrade"). Use this list as the enrollment trigger for an expansion notification workflow to CS.

**Notion / Confluence:**
Build the RevOps Wiki with the following pages: (1) Metric Definitions — the definitive source for how every KPI is calculated, (2) SLA Architecture — tiered handoff standards with screenshots of the automation configurations, (3) Governance Cadence — meeting agendas and attendee guides, (4) Decision Log — every cross-functional decision made in the Monthly Revenue Review, linked to the Salesforce opportunity or campaign affected. Version-control every page and require RevOps sign-off before any definition change.

**Slack:**
Create a #revenue-ops channel with automated posts: weekly pipeline coverage pulse (post every Monday 8am via Salesforce Slack integration), SLA violation alerts (any Tier 1 SLA miss), and the monthly metrics digest. Pin the Revenue Intelligence Dashboard link and the Metric Definitions wiki page in the channel bookmarks. This creates a single, always-current reference point that replaces the "what's our pipeline?" recurring Slack threads.

**Zapier / Make:**
Automate the RevOps meeting prep: scheduled trigger (Sunday 5pm before Monday Revenue Pulse) → pull current pipeline coverage from Salesforce API → pull top 10 at-risk deals (last activity >14 days + close date < 30 days) → format as Slack message → post to #revenue-ops with meeting link. This eliminates 45 minutes of manual report-pulling before every weekly meeting and ensures the data is always current as of Sunday night.

## Troubleshooting

**"Sales and marketing refuse to agree on a shared MQL definition — we've tried before and it always falls apart"**
The disagreement almost always comes from one side trying to protect their numbers (marketing doesn't want to lower MQL count; sales doesn't want to accept leads that look unqualified). Reframe the conversation away from definitions and toward outcomes: "We are not agreeing on what an MQL is. We are agreeing on what a lead that has a 20% chance of closing looks like." Pull the last 12 months of closed-won data from Salesforce and run a backwards analysis — what behaviors, firmographic attributes, and score components were present in the leads that actually closed? Let the data define the MQL, not either team's opinion. Most marketing/sales MQL wars end within two meetings when both sides see the same closed-won cohort analysis.

**"We don't have a dedicated RevOps resource — it's just the MOps person wearing a RevOps hat"**
This is the most common situation for Series A-B companies. The answer is not "hire a RevOps Director first" — it's to establish the governance and metrics infrastructure before making the hire, so the future RevOps hire inherits a working system rather than starting from scratch. Prioritize the shared metrics framework (Module 2) and the weekly Revenue Pulse meeting (Module 4) as the minimum viable RevOps infrastructure that one person can maintain in 4-6 hours per week. The dashboard and full SLA architecture can follow once the governance cadence is proven.

**"Our CRM data is too dirty to trust the funnel metrics — we know the numbers are wrong"**
Do not wait for clean data to start RevOps. Instead, run the RevOps audit in parallel with a CRM hygiene sprint: use the Marketing Operations Data Quality & CRM Hygiene Intelligence Engine to clean the most critical fields (Lead Source, Stage, Close Date, Opportunity Amount) while simultaneously building the RevOps dashboard. Flag every metric on the dashboard as "baseline — data quality improvement in progress" for the first quarter. Stakeholders accept imperfect-but-improving data far better than no data. A dashboard with an asterisk drives faster data quality investment than a spreadsheet that nobody trusts.

## Version History
- v1.0: Initial creation (auto-generated)
