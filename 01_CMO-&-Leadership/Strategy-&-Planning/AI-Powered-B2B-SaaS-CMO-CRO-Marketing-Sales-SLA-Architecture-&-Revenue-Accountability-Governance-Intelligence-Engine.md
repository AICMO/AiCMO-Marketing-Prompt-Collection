# AI-Powered B2B SaaS CMO-CRO Marketing-Sales SLA Architecture & Revenue Accountability Governance Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b-saas, cmo-strategy, sales-alignment, revenue-operations, sla, pipeline-governance, marketing-sales-alignment, revenue-accountability, mql-sql, cro-partnership

## Overview

Designs a formal, AI-monitored Marketing-Sales Service Level Agreement (SLA) that transforms the perennial marketing-vs-sales blame cycle into a shared revenue accountability system. Use this when your CMO-CRO relationship is strained by disagreements over lead quality, follow-up speed, or pipeline contribution — or when you're scaling past $10M ARR and informal alignment no longer holds. This engine produces the complete SLA contract, real-time monitoring dashboard, escalation protocols, and quarterly review cadences that make marketing and sales genuinely accountable to each other and to revenue.

## Quick Copy-Paste Version

You are a senior B2B SaaS Revenue Operations strategist who specializes in designing Marketing-Sales Service Level Agreements that hold both functions accountable to shared revenue outcomes. My company sells [PRODUCT — e.g., AI-powered contract management software] to [ICP — e.g., General Counsel and VP Legal at enterprise companies with 1,000+ employees]. We're at [ARR — e.g., $22M ARR, Series B], have [MARKETING TEAM SIZE — e.g., 12-person marketing team] and [SALES TEAM SIZE — e.g., 18 AEs + 8 SDRs], and the CMO-CRO relationship is strained by [CORE TENSION — e.g., "Sales says MQL quality is poor; Marketing says Sales doesn't follow up fast enough"].

Design a complete Marketing-Sales SLA architecture. Produce:

1. **MARKETING COMMITMENTS TO SALES**: The exact volume, quality, and timing commitments marketing will make to the sales team — including monthly MQL/MQA targets by segment, lead score minimums, data completeness requirements, and handoff documentation standards. Specify what sales can reject and what constitutes a legitimate "return" to marketing.

2. **SALES COMMITMENTS TO MARKETING**: The exact follow-up speed, attempt cadence, and disposition requirements sales commits to for marketing-sourced leads — including first response time SLA (e.g., "all MQLs contacted within 4 business hours"), minimum contact attempts before recycling, and required CRM fields sales must complete when disqualifying a lead.

3. **SHARED REVENUE METRICS**: The 5-7 metrics that both teams are jointly accountable for, measured weekly — including marketing-sourced pipeline coverage ratio, MQL-to-SQL conversion rate, marketing-influenced win rate, and average time-to-first-contact.

4. **SLA VIOLATION ESCALATION PROTOCOL**: The exact escalation chain when either side misses SLA — who gets notified at 24 hours, 72 hours, and 1 week of non-compliance, and what the remediation process looks like.

5. **QUARTERLY SLA REVIEW FRAMEWORK**: The agenda and data package for the CMO-CRO quarterly SLA review — including which metrics trigger renegotiation vs. which require root-cause investigation.

Output as a complete SLA document ready for CMO-CRO signature, plus a 30/60/90-day implementation roadmap.

## Advanced Customizable Version

### ROLE & CONTEXT

You are a Revenue Operations Executive with 18+ years designing marketing-sales alignment systems for B2B SaaS companies from Series A through IPO. You've served as interim CMO or CRO at three companies and have designed Marketing-Sales SLAs at companies including $15M ARR Series A startups scaling their first sales team, $80M ARR Series C companies entering enterprise motion, and post-IPO public companies rationalizing their GTM operating model.

You understand the five failure modes that destroy Marketing-Sales SLAs:

- **Vanity-metric SLAs**: SLAs written around MQL volume rather than pipeline quality, so marketing optimizes for lead count while sales drowns in low-intent contacts. The CMO hits the SLA; the CRO misses quota. Both are technically correct and both are furious.
- **Asymmetric accountability**: Marketing commits to lead volume and quality; sales commits to nothing measurable. When pipeline misses, it's always marketing's fault by default because marketing's commitments are written down and sales's aren't. The fix: mutual accountability or no accountability.
- **Lagging measurement**: SLA compliance is reviewed quarterly, meaning a 60-day lead follow-up failure isn't caught until it's 90 days old. By then the lead is cold, the deal is lost, and the argument is academic. SLA monitoring must be real-time or near-real-time to be corrective rather than punitive.
- **Definition warfare**: Marketing and sales have different definitions of "qualified," "contacted," "recycled," and "disqualified" — and they've never written them down. The SLA references "MQLs" and both sides silently interpret the term differently. Every quarterly review devolves into definitional arguments rather than strategic ones.
- **No-fault recycling**: Sales disqualifies leads without completing required CRM fields, making it impossible for marketing to understand why leads are returned or improve lead quality. Marketing therefore has no learning signal. Lead quality doesn't improve. The cycle repeats every quarter.

You design SLAs around four principles:

- **Revenue-back commitments**: Every SLA commitment is derived backward from the revenue target, not forward from marketing's production capacity. If the company needs $8M in new ARR from marketing-sourced pipeline, the SLA specifies exactly what volume and stage-conversion rates are required to produce that pipeline — and both marketing and sales are held to the conversion math, not arbitrary lead counts.
- **Bi-directional accountability**: Marketing commits to volume, quality, and handoff standards. Sales commits to follow-up speed, attempt cadence, disposition accuracy, and CRM hygiene. Both sides have binding commitments with named owners, measurement cadences, and escalation consequences.
- **Real-time signal loops**: SLA compliance is monitored via automated dashboards refreshed daily, not quarterly reviews. A sales rep who hasn't contacted a marketing-sourced MQL in 48 hours triggers an automated Slack alert to their manager and the RevOps team — not a polite mention in the monthly meeting.
- **Constructive failure protocols**: When SLAs are missed, the response is root-cause investigation before blame assignment. Marketing misses MQL targets: was it a campaign failure, a market signal, or a pipeline model that was never realistic? Sales misses follow-up SLAs: was it rep bandwidth, CRM routing failure, or territory mismatch? The SLA architecture must make the root cause diagnosable within 48 hours.

---

### COMPANY & GTM CONTEXT

**Company Profile:**
- Company name & product: [e.g., Apex Legal — AI-powered contract lifecycle management for enterprise legal and procurement teams]
- ARR and growth stage: [e.g., $22M ARR, Series B, growing 80% YoY]
- ICP: [e.g., General Counsel, VP Legal, and VP Procurement at companies with 500–5,000 employees in financial services, healthcare, and technology]
- ACV range: [e.g., $35,000–$180,000/year; average 5.5-month sales cycle]
- CRM platform: [e.g., Salesforce Sales Cloud]
- Marketing automation platform: [e.g., Marketo Engage]
- Revenue intelligence platform: [e.g., Gong.io for call recording; 6sense for intent data]

**Sales Organization:**
- Total AE headcount: [e.g., 14 AEs — 4 Enterprise (>1,000 employees), 8 Mid-Market (200–1,000), 2 SMB (<200)]
- SDR/BDR headcount: [e.g., 6 SDRs — all inbound-focused on marketing-sourced leads]
- Sales regions or territories: [e.g., North America split by West/East; 2 EMEA AEs added in Q1]
- Sales leader: [e.g., CRO joined 8 months ago; previously VP Sales at a competitor; highly data-driven]
- Current follow-up process: [e.g., SDRs have informal "try to contact within same business day" norm; no formal SLA exists; CRM shows average first-contact at 31 hours after MQL creation]

**Marketing Organization:**
- Marketing team structure: [e.g., VP Demand Gen, VP Product Marketing, 3 campaign managers, 2 content writers, 1 RevOps/marketing ops, 1 web developer]
- Monthly MQL volume (current): [e.g., 280–340 MQLs per month; 65% inbound, 35% outbound/ABM]
- MQL-to-SQL conversion rate (current): [e.g., 22% — CMO believes this is artificially low because SDRs don't work all MQLs within SLA; CRO believes lead quality is too low]
- Primary demand gen channels: [e.g., Google Search (38%), LinkedIn Ads (24%), organic/SEO (18%), events (12%), content syndication (8%)]
- Lead scoring model: [e.g., Marketo-based; 0–100 score; MQL threshold at 65+; model not updated since Q2 last year]

**Current State of Marketing-Sales Alignment:**
- Formal SLA today: [e.g., None. A verbal agreement from 2022 said "SDRs should contact MQLs within 24 hours" but it's never measured and routinely violated]
- Core conflict points: [e.g., (1) Sales says 40% of MQLs are "too cold" or "wrong ICP"; (2) Marketing has evidence that 65% of MQLs sales marks as "disqualified" have missing CRM data with no reason code; (3) SDRs contact 73% of MQLs within 72 hours but 27% wait 5+ business days or are never contacted]
- Revenue target for next 12 months: [e.g., $38M ARR — requires $18M in net new ARR at current churn rate]
- Marketing's pipeline coverage target: [e.g., CMO has committed to generating 35% of new ARR pipeline; CRO expects marketing-sourced pipeline to cover 3x the marketing portion of quota]
- What a successful SLA looks like for each side: [e.g., CMO wants sales to follow up faster and provide better disqualification data to improve targeting; CRO wants higher MQL-to-opportunity conversion rates and wants marketing to stop counting recycled MQLs as "new"]

---

### REQUIRED SLA OUTPUTS

**PART 1 — REVENUE-BACK SLA MATH**

Build the complete pipeline math that the SLA is derived from:
- Annual new ARR target: [e.g., $18M]
- Marketing's committed share: [e.g., 35% = $6.3M in new ARR]
- Required marketing-sourced closed-won deals: [e.g., at $65K average ACV = 97 closed deals]
- Required marketing-sourced opportunities (at current 28% opportunity-to-close rate): [e.g., 347 opportunities]
- Required MQLs that convert to opportunities (at target 24% MQL-to-SQL conversion): [e.g., 1,446 MQLs per year = 120 MQLs/month]
- Monthly MQL target by channel with confidence interval
- The "math gap": where current trajectory falls short of SLA targets and what both sides must do differently to close it

**PART 2 — MARKETING'S SLA COMMITMENTS TO SALES**

Write the exact, measurable commitments marketing will make, covering:

*Volume Commitments:*
- Monthly MQL target by segment (Enterprise/Mid-Market/SMB) and by lead source
- Monthly MQA (Marketing Qualified Account) target for ABM accounts
- Confidence interval and what triggers a "force majeure" exemption (e.g., Google algorithm change, budget reallocation)

*Quality Commitments:*
- Minimum lead score at MQL handoff (e.g., 72+ on the Marketo model)
- Required data completeness: which fields must be populated at handoff (company name, title, email, phone, company size, industry, country — and the penalty for handing off incomplete records)
- Behavioral context documentation: what minimum qualification evidence marketing must include in the CRM lead record at handoff (e.g., "at minimum: last 3 website pages visited, content downloaded, email engagement score, source attribution, and any intent data signal from 6sense")
- ICP fit score: minimum ICP firmographic match required for a lead to qualify as an MQL

*Timing Commitments:*
- Time from form fill / behavioral trigger to CRM record creation (e.g., "within 15 minutes for inbound form fills; within 2 hours for behavioral triggers")
- Time from CRM record creation to SDR notification (e.g., "within 5 minutes via Slack alert and Salesforce task assignment")
- Content and context package delivered to SDR with each MQL (e.g., "LinkedIn profile link, company summary, intent data summary, recommended email subject line")

*Rejection/Return Policy:*
- Define exactly what constitutes a legitimate MQL return — the specific criteria sales can use to send a lead back to marketing without penalty
- Mandatory CRM fields sales must complete when returning an MQL (at minimum: rejection reason category, supporting evidence, and SDR name)
- Maximum return rate marketing will accept before requiring a joint review (e.g., "if sales rejects >25% of MQLs in any 30-day period, a mandatory joint review meeting is triggered within 5 business days")

**PART 3 — SALES'S SLA COMMITMENTS TO MARKETING**

Write the exact, measurable commitments sales will make, covering:

*Follow-Up Speed SLA:*
- Tier 1 (Enterprise ICP, 6sense high-intent signal, score 85+): First SDR contact attempt within [e.g., 2 business hours] of MQL notification
- Tier 2 (Mid-Market ICP, score 72–84): First SDR contact attempt within [e.g., 6 business hours]
- Tier 3 (SMB or lower intent, score 65–71): First SDR contact attempt within [e.g., 1 business day]
- Definition of "contact attempt": what counts (call + email = 1 attempt; LinkedIn message alone does not count)

*Attempt Cadence Commitment:*
- Minimum number of contact attempts before recycling a lead back to marketing
- Minimum follow-up window before declaring a lead "cold" (e.g., "a minimum of 8 contact attempts over 21 business days before recycling")
- Commitment to use the marketing-supplied email templates and subject lines for first 2 outreach attempts (to test messaging effectiveness before going off-script)

*CRM Hygiene Commitments:*
- Required fields SDRs must complete for every MQL touched (contact date, attempt count, call outcome, email open/reply status, disqualification reason with one of 6 defined categories, and free-text notes)
- Maximum acceptable rate of MQLs with incomplete CRM data (e.g., "no more than 15% of monthly MQLs may have missing required fields at month-end")
- Commit to updating Salesforce opportunity stage within 24 hours of stage change (to maintain attribution accuracy)

*Conversion Rate Commitment:*
- Minimum MQL-to-SQL conversion rate sales commits to (e.g., "sales commits to converting a minimum of 22% of Tier 1 MQLs to opportunities; if conversion falls below 18% for two consecutive months, a joint qualification criteria review is triggered")
- Monthly opportunity creation rate from marketing-sourced leads

**PART 4 — SHARED ACCOUNTABILITY METRICS DASHBOARD**

Design the 7-metric joint scorecard that both CMO and CRO review weekly:

For each metric, specify:
- Metric name and exact calculation formula
- Data source and refresh cadence
- Green/Yellow/Red threshold definitions
- Owner responsible for improvement if metric goes red
- Which SLA trigger it's connected to

Required metrics:
1. Marketing-Sourced Pipeline Coverage Ratio (marketing-sourced open pipeline ÷ marketing's pipeline coverage target × 100)
2. MQL-to-SQL Conversion Rate (by tier and by channel)
3. Average Time-to-First-Contact (hours from MQL notification to first SDR contact attempt)
4. Lead Return Rate (% of MQLs rejected by sales, broken down by rejection reason category)
5. CRM Data Completeness Rate (% of SDR-touched MQLs with all required fields completed)
6. Marketing-Sourced Win Rate (closed-won opportunities sourced by marketing ÷ total marketing-sourced opportunities)
7. Pipeline Contribution Accuracy (marketing-committed pipeline for quarter vs. actual pipeline generated — measured at end of quarter against CMO's Q-start commitment)

**PART 5 — REAL-TIME MONITORING ARCHITECTURE**

Design the AI-powered monitoring system that makes SLA compliance visible before violations become pipeline damage:

*Automated Alerts:*
- Tier 1 MQL not contacted within 2 hours → automated Slack DM to SDR manager + RevOps at Hour 3
- Tier 1 MQL not contacted within 6 hours → Slack alert escalates to CRO and CMO at Hour 7
- Any MQL with no contact attempt after 1 business day → appears on daily RevOps dashboard flagged in red
- Monthly MQL volume tracking at 50%, 75%, and 90% of month completion with forecast vs. target comparison
- Lead return rate exceeds 20% in any 7-day rolling window → automated alert to CMO and CRO with breakdown by SDR and rejection reason

*Weekly Automated Reports:*
- Monday morning: prior week SLA scorecard delivered to CMO, CRO, VP Demand Gen, and SDR manager
- Wednesday: mid-week pipeline coverage forecast update
- Friday: weekly SDR follow-up compliance report with individual SDR performance vs. SLA

*Dashboards:*
- Salesforce/HubSpot + Gong joint dashboard design (what data lives where, how it's surfaced)
- AI-generated weekly SLA narrative: 3-sentence plain-English summary of SLA status, biggest deviations, and recommended actions — auto-generated from CRM data and distributed Monday 7am local time to CMO and CRO

**PART 6 — SLA VIOLATION ESCALATION PROTOCOL**

Define the exact escalation chain for each type of SLA violation:

*Marketing misses MQL volume target by 15%+ in any month:*
- Day 1: CMO self-reports to CRO with root cause hypothesis and recovery plan
- Day 3: CMO presents detailed root cause analysis and revised forecast to CMO + CRO + RevOps
- Day 14: Joint CMO-CRO review of whether pipeline target requires adjustment or whether catch-up is achievable

*Sales follow-up SLA missed for >20% of MQLs in any week:*
- Day 1: RevOps flags to SDR manager and CRO
- Day 3: CRO reviews individual SDR performance data; root cause identified (bandwidth, routing, CRM failure)
- Day 7: CRO presents remediation plan to CMO
- Day 14: Repeat violation → joint CMO-CRO review of whether SDR capacity, territory design, or routing logic needs structural change

*MQL return rate exceeds 25% for two consecutive months:*
- Joint CMO-CRO lead quality review: sample review of 20 returned MQLs with SDR and marketing manager in the room
- Lead scoring model audit triggered within 30 days
- ICP definition review: jointly rewrite the MQL definition if current definition is producing systematic ICP mismatch

**PART 7 — QUARTERLY SLA REVIEW AGENDA & DATA PACKAGE**

Design the 90-minute quarterly CMO-CRO SLA review:

*Pre-read package (distributed 5 business days before meeting):*
- Quarter's SLA scorecard vs. targets for all 7 joint metrics
- Channel-level MQL performance breakdown
- SDR-level follow-up compliance data
- Pipeline coverage accuracy: committed vs. actual
- Top 10 returned MQLs with sales rep notes and marketing rebuttal/agreement
- AI-generated quarterly narrative: 1-page plain-English assessment of what worked, what didn't, and what needs to change

*Meeting agenda:*
- 15 min: Review scorecard — what went green, what went red, no debating causes yet
- 20 min: Root cause deep-dive on the 2 biggest misses (one from each side)
- 15 min: Marketing pipeline math for next quarter — CMO presents bottom-up build of MQL forecast
- 15 min: Sales capacity math for next quarter — CRO presents SDR bandwidth vs. MQL volume commitment
- 10 min: SLA renegotiation — are any commitments no longer realistic and need adjustment?
- 15 min: Shared priorities for next 90 days — what will both sides do differently?

*SLA renegotiation triggers:*
- Market conditions change significantly (recession, category disruption, major competitor launch)
- GTM motion changes (shift from PLG to enterprise sales-assisted, new product line, new segment)
- Sales capacity changes by >30% (rapid hiring or layoffs)
- ACV or sales cycle changes materially (new pricing model, enterprise expansion)

**PART 8 — SLA ROLLOUT PLAN**

Design the 90-day SLA implementation roadmap:

*Days 1–30 (Foundation):*
- Joint CMO-CRO SLA drafting session: 2-hour working meeting to align on all commitments
- RevOps instrumentation: configure Salesforce/Marketo fields, Slack integrations, and dashboard
- SDR enablement: train SDRs on new follow-up standards, CRM fields, and what "good" looks like
- Baseline measurement: establish pre-SLA baseline for all 7 metrics to measure SLA impact

*Days 31–60 (Pilot):*
- SLA goes live for Tier 1 MQLs only (Enterprise segment, highest ACV)
- Weekly CMO-CRO check-in (30 minutes) to catch implementation issues early
- Identify and fix the top 3 process or tooling failures discovered in pilot

*Days 61–90 (Full Rollout):*
- SLA expands to all MQL tiers
- First full monthly SLA review meeting
- RevOps publishes SLA performance report to both marketing and sales org (not just leadership)
- Board reporting: CMO and CRO present joint SLA scorecard to board as evidence of revenue operating discipline

## Example Input/Output

**Input Example:**

Company: **Solvexa** — AI-powered field service management software for commercial HVAC and industrial equipment service companies. $28M ARR, Series B. ICP: VP Field Operations and COO at companies with 50–500 field technicians.

ACV: $42,000–$95,000/year. 4-month average sales cycle.

Current state: 240 MQLs/month. 19% MQL-to-SQL conversion. SDRs average 38 hours to first contact. Sales rejects 31% of MQLs with "not ICP" as the only reason code 72% of the time. Marketing has no visibility into why leads are rejected. CRO says lead quality is "the number-one pipeline problem." CMO says SDRs don't follow up fast enough and don't use CRM properly.

**Output Example (abbreviated):**

**REVENUE-BACK SLA MATH FOR SOLVEXA:**

Solvexa needs $12M in net new ARR. Marketing committed to 40% = $4.8M. At $62,000 average ACV, that's 77 closed deals. At current 31% close rate, that requires 248 marketing-sourced opportunities. At target 26% MQL-to-opportunity conversion (vs. current 19% — achievable if follow-up SLA is met and lead scoring is recalibrated), that requires 954 MQLs per year = **80 MQLs per month**.

Current volume: 240 MQLs/month. Current conversion: 19% = 46 opportunities/month.
Target volume: 80 MQLs/month. Target conversion: 26% = 21 opportunities/month.

**Insight**: Marketing is over-producing MQLs by 3x but under-converting by 7 percentage points. The SLA fix is not more volume — it's quality improvement and follow-up speed. Marketing commits to reduce MQL volume to 80/month but improve average lead score from 68 to 78 and ensure 100% data completeness at handoff. Sales commits to first contact within 4 hours for any score 80+ and to provide specific rejection codes.

---

**MARKETING COMMITMENTS (EXCERPT):**

*Volume:* 80 MQLs/month ± 15% (green threshold: 68–92 MQLs). 20 MQAs/month for ABM named accounts. Force majeure: volume commitment suspended if paid media budget is reduced by CMO outside normal planning cycle.

*Quality:* Minimum score 72 at handoff. Required fields: company name, industry, employee count, title, direct email, direct phone, lead source, last 3 website pages visited, and 6sense intent score (if available). MQL record must include a 2-sentence "SDR context brief" auto-generated by AI from the contact's behavioral history.

*Rejection policy:* Sales may reject MQLs that meet any of 6 defined criteria (wrong ICP industry, non-decision-maker title, active customer contact, active deal contact, marked as competitor, or personal email address). All rejections require CRM reason code + 1-sentence note. Marketing accepts rejection if legitimate; disputes in writing within 48 hours if criteria are not met.

---

**SALES COMMITMENTS (EXCERPT):**

*Follow-up speed:*
- Score 80+: first contact attempt within 4 business hours of Slack notification
- Score 72–79: first contact attempt within 1 business day

*Attempt cadence:* Minimum 7 attempts over 18 business days. Attempt = call AND email on same business day. LinkedIn message optional but not counted.

*CRM hygiene:* 100% of MQL records must have attempt count, last contact date, and outcome (connected/voicemail/no answer/replied/unsubscribed) updated within 24 hours of each attempt.

*Conversion commitment:* Sales commits to 24% MQL-to-SQL conversion on Tier 1 (score 80+) MQLs. If conversion drops below 20% for 2 consecutive months, joint qualification criteria review triggered within 15 days.

---

**WEEK 1 ALERTS FOR SOLVEXA (simulated):**

- Monday 8am: 3 Tier 1 MQLs from last Friday (score 83, 87, 91) have no recorded contact attempt — Slack alert sent to SDR manager Sarah Chen and CRO David Park
- Tuesday 11am: Week 1 MQL volume at 18 of 20-per-week target (90% — yellow)
- Wednesday 3pm: 1 MQL returned by SDR Jake Thompson with reason "not ICP" — no supporting note. CRM hygiene alert sent to Jake and Sarah Chen.
- Friday 5pm: Weekly report — 22 MQLs created, 17 contacted within SLA, 5 missed (22.7% — red). 2 MQLs returned, both with incomplete reason codes. One already disputed by marketing.

## Success Metrics

- **SLA adoption**: >90% of all MQLs contacted within tier-appropriate follow-up window within 60 days of launch
- **CRM data quality**: >92% of SDR-touched MQL records have all required fields completed within 30 days of rollout
- **MQL-to-SQL improvement**: 4–8 percentage point improvement in MQL-to-SQL conversion rate within 90 days of SLA implementation
- **Marketing-sales trust**: Zero "lead quality" escalations reaching the board within 6 months of SLA launch
- **Pipeline forecast accuracy**: Marketing's pipeline contribution forecast within ±12% of actual within 2 quarters of SLA implementation
- **SLA review engagement**: Both CMO and CRO attend all quarterly reviews with pre-read completed — measured by completion of pre-read questions sent 5 days in advance

## Related Prompts

- [AI-Powered B2B SaaS Marketing-Sales Revenue Alignment Architecture & Closed-Loop Lead Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Scoring-&-Pipeline-Management/AI-Powered-B2B-SaaS-Sales-Marketing-Revenue-Alignment-Architecture-&-Closed-Loop-Lead-Intelligence-Engine.md)
- [AI-Powered B2B CMO Pipeline Gap Diagnosis & Revenue Sprint Marketing Intelligence Engine](../Reporting-&-ROI/AI-Powered-B2B-CMO-Pipeline-Gap-Diagnosis-&-Revenue-Sprint-Marketing-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Marketing Sales Pipeline Attribution Governance & Revenue Credit Consensus Intelligence Engine](../Reporting-&-ROI/AI-Powered-B2B-SaaS-Marketing-Sales-Pipeline-Attribution-Governance-&-Revenue-Credit-Consensus-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Predictive Lead Scoring Architecture & Revenue Qualified Pipeline Management Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Scoring-&-Pipeline-Management/AI-Powered-B2B-SaaS-Predictive-Lead-Scoring-Architecture-&-Revenue-Qualified-Pipeline-Management-Intelligence-Engine.md)

## Integration Tips

- **Salesforce**: Create a custom MQL SLA object that tracks handoff time, first contact time, and variance from SLA. Use Process Builder or Flow to auto-assign tasks to SDRs on MQL creation and set automated reminders at 50% of SLA window.
- **HubSpot**: Configure lead rotation workflows with timestamp tracking. Use HubSpot's "Time-in-Stage" reporting to surface leads stuck without contact. Connect HubSpot CRM to Slack via Zapier for real-time follow-up alerts.
- **Marketo**: Build the SLA compliance dashboard as a Marketo Revenue Explorer report. Set up smart campaigns that auto-flag MQLs as "SLA at risk" if contact attempt isn't logged within 80% of the committed window.
- **Gong / Chorus**: Use call intelligence data to audit SDR conversation quality on MQL follow-up calls. Create a Gong scorecard for "MQL first call quality" to ensure SDRs are using the marketing context brief in conversations.
- **Slack**: Build a #mql-sla-alerts channel visible to both CMO and CRO with automated daily summaries. Use separate channels for #mql-tier1-urgent (requires immediate attention) and #mql-sla-weekly-digest.
- **Tableau / Looker**: Build the 7-metric joint scorecard as a Tableau dashboard with automated weekly email distribution to CMO, CRO, VP Demand Gen, SDR manager, and RevOps.

## Troubleshooting

**Problem**: Sales refuses to commit to specific follow-up time SLAs, arguing "it depends on how busy we are."
**Solution**: Reframe as a capacity alignment problem rather than a behavior problem. Use the pipeline math to show exactly how many MQL follow-ups per week each SDR is responsible for, then model whether current SDR headcount can meet the SLA. If it can't, the solution is headcount or ICP prioritization — not abandoning the SLA. Present the math to the CRO: "Here's what we need from sales to hit your ARR number. Does your team have capacity?" The answer becomes a resourcing conversation, not a compliance argument.

**Problem**: Marketing can't meet the MQL volume commitment due to algorithm changes, budget cuts, or seasonal demand fluctuations.
**Solution**: Build explicit force majeure clauses and confidence intervals into the SLA from day one. Define in writing: "The monthly MQL commitment has a ±15% variance threshold. Variance beyond ±15% requires CMO to notify CRO within 5 business days of identifying the miss with a root-cause analysis and recovery plan." This prevents surprises and creates a professional escalation process instead of a crisis conversation.

**Problem**: SDRs are completing required CRM fields but entering generic or meaningless reason codes (e.g., "not interested" for 80% of disqualifications).
**Solution**: Design the rejection reason categories collaboratively with SDR managers to ensure they reflect real disqualification patterns. Limit to 6–8 specific categories (e.g., "Wrong ICP: industry mismatch," "Wrong ICP: company size too small," "Budget: no budget cycle," "Timing: evaluating in 6+ months," "Active customer," "Competitor employee"). Train SDRs that "not interested" is not an acceptable reason code without a supporting category. RevOps spot-check 10% of disqualification records weekly during the first 60 days.

## Version History
- v1.0: Initial creation (auto-generated)
