# Marketing-Sales Revenue Alignment & SLA Engine - Funnel Definition, Lead Handoff, and Joint Pipeline Accountability System

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** revenue-alignment, sla, marketing-sales, pipeline, mql, sql, funnel-definition, revops, b2b, lead-scoring, handoff-criteria

## Overview
Builds a complete, mathematically grounded Marketing-Sales Service Level Agreement — including agreed funnel stage definitions, MQL/SQL/SAL criteria, lead scoring thresholds, conversion rate benchmarks, response time commitments, and joint pipeline accountability metrics. Use this when marketing and sales are blaming each other for missed pipeline targets, when "lead quality" debates are happening in every QBR, or when you're building a RevOps function from scratch and need a shared language for pipeline creation.

## Quick Copy-Paste Version

You are a senior Revenue Operations strategist. I need you to build a complete Marketing-Sales SLA document for my B2B company that eliminates ambiguity around lead handoffs, funnel stage definitions, and pipeline accountability.

**Company Context:**
- B2B SaaS | ACV: $52,000 | Sales cycle: 65 days | Team: 4 AEs, 3 SDRs, 5-person marketing team
- CRM: HubSpot | Current MQL volume: ~180/month | Current SQL conversion rate from MQL: ~22%
- Current pipeline coverage ratio: 2.8x | Quarterly revenue target: $1,950,000
- Known tension point: Sales says MQLs are low quality; Marketing says sales ignores leads too slowly

**Current Funnel (messy, needs formalization):**
- We define MQL as: "contact who downloaded something or attended a webinar"
- We define SQL as: "MQL that sales has called" (no qualification criteria)
- Average sales response time to new MQL: 4.2 business days
- Lead routing: Round-robin to all 4 AEs regardless of company size or vertical

Using this context, build a complete Marketing-Sales SLA that includes:

1. **Revised Funnel Stage Definitions** — define MQL, SAL (Sales Accepted Lead), SQL, and Opportunity with specific, measurable criteria for each stage
2. **Lead Scoring Framework** — behavioral score thresholds (what actions = what points) and demographic/firmographic fit score (ICP match = what score) to determine MQL threshold
3. **Lead Handoff SLA** — marketing's commitment to lead quality (minimum score, minimum data completeness), sales' commitment to response time and disposition timeline by lead tier (Hot/Warm/Cold)
4. **Funnel Math Validation** — work backward from $1,950,000 quarterly target to show how many Opportunities, SQLs, SALs, and MQLs are required at current conversion rates
5. **Joint Accountability Metrics** — which metrics marketing owns, which sales owns, which are shared (disagree-to-agree metrics with no blame game)
6. **Feedback Loop Protocol** — how sales rejects an MQL (with specific rejection reason codes), and how marketing uses rejection data to improve lead scoring within 30 days
7. **Executive Summary** — 1-page version of the SLA suitable for presenting to CRO and CMO jointly

## Advanced Customizable Version

ROLE: You are a VP of Revenue Operations with 12+ years aligning marketing and sales at high-growth B2B companies from Series A through IPO. You have broken the "lead quality vs. lead follow-up speed" blame cycle at six companies by replacing subjective arguments with math, definitions, and mutual accountability frameworks. You know that most marketing-sales misalignment is not a relationship problem — it is a definitional problem: nobody agreed on what an "MQL" means before counting them. You produce SLA documents that hold up in QBRs, board meetings, and M&A due diligence.

COMPANY CONTEXT:
Company name: [Company Name]
Business model: [B2B SaaS / B2B Services / Marketplace / Enterprise Software]
ACV or deal size: $[X] | Average sales cycle: [X days]
Revenue target (quarterly): $[X] | Current attainment: [X%]
Marketing team size: [X] | Sales team: [X AEs] + [X SDRs/BDRs]
CRM platform: [HubSpot / Salesforce / Other]
Current pipeline coverage ratio: [X]x (pipeline / quarterly target)
Current MQL volume: [X/month] | Current MQL-to-SQL conversion rate: [X%]
Current SQL-to-Opportunity rate: [X%] | Current Opportunity-to-Close rate: [X%]
Average sales response time to new MQL: [X hours/days]
Current alignment pain points: [Describe top 2-3 tensions between marketing and sales]
ICP definition (for demographic scoring): [Industry, company size, title, geography, tech stack]
Lead sources in current mix: [Organic / Paid / Outbound SDR / Event / Partner / Referral — % of each]

EXISTING FUNNEL DATA (if available):
Current MQL definition in use: [What marketing currently calls an MQL]
Current SQL definition in use: [What sales currently calls an SQL]
Lead routing rules: [How leads are currently assigned to reps]
Lead scoring system: [Exists / Does not exist / Partially implemented]
Marketing automation platform: [HubSpot / Marketo / Pardot / ActiveCampaign / None]
SDR/BDR role: [Exists — does first qualification / Does not exist — AEs take all MQLs directly]

STEP 1: FUNNEL STAGE DEFINITION FRAMEWORK

Define each funnel stage with precision. Every definition must be:
- MEASURABLE: Based on data in CRM/MAP, not human judgment
- AGREED: Could be read by marketing and sales and produce the same outcome for the same contact
- BINARY: A contact either qualifies or does not — no gray zone

FUNNEL STAGE DEFINITIONS TO BUILD:

SUBSCRIBER / KNOWN CONTACT:
- Definition: Any person in CRM database with at minimum [email + first name + company]. No engagement threshold required.
- Marketing commitment: Contact is spam-scrubbed, duplicate-deduplicated, and GDPR-compliant within 24 hours of capture.
- Volume expectation: [X] new contacts/month from [channel breakdown]

ENGAGED / NURTURE PROSPECT:
- Definition: Contact who has performed at least [X] behavioral actions above threshold [Y points] but has not yet reached MQL threshold.
- Not yet assigned to sales. Marketing owns this contact fully.
- Marketing SLA: Contact receives [X] automated nurture touches within first [Y days] of reaching Engaged status.

MARKETING QUALIFIED LEAD (MQL):
- Trigger: Combined lead score ≥ [X] points AND demographic/firmographic fit score ≥ [Y] points
- Hard STOP criteria (disqualify regardless of score): Competitor domain, student email, geography outside [target markets], company size < [X employees] or > [X employees] if outside ICP range
- Required data completeness before MQL is triggered: [e.g., First name + Last name + Business email + Company + Job Title must all be populated]
- Marketing SLA upon MQL trigger: Contact record must include [list minimum data fields], lead source attribution recorded, last 5 activity events logged in CRM timeline

SALES ACCEPTED LEAD (SAL) — optional stage for teams with SDR function:
- Definition: MQL that an SDR/BDR has reviewed and confirmed meets minimum qualification criteria within [X hours] of MQL trigger
- SDR SLA: Every MQL must be reviewed (accepted or rejected with reason code) within [X] business hours of assignment
- Acceptance criteria: [Confirm ICP fit verified via LinkedIn/company website + no active opportunity already in system + contact is reachable at submitted details]
- Rejection criteria with codes:
  * R1 — Competitor employee
  * R2 — Wrong title / no buying authority (describe reachable threshold)
  * R3 — Duplicate (existing active opportunity)
  * R4 — Outside ICP geography
  * R5 — Data unverifiable (phone/email bounced, LinkedIn profile does not match)
  * R6 — Timing not right (contact explicitly stated not evaluating for > [X months])
- Note: Rejected SALs must include a reason code within the SLA window. Unworked leads left pending > [X] business hours auto-route to SDR manager for review.

SALES QUALIFIED LEAD (SQL):
- Definition: SAL that has passed initial SDR conversation AND meets MEDDIC/BANT minimum criteria:
  * MEDDIC path: Metrics (can articulate a business problem with measurable impact) + Economic buyer identified or reachable + Decision process confirmed (active evaluation or planned within [X months]) + Identify Champion (contact willing to advocate internally)
  * BANT path (for SMB): Budget confirmed OR Budget authority confirmed + Active Need confirmed + Timeline within [X months]
- SQL creation action: SDR/BDR logs qualification notes in CRM and creates Opportunity, OR AE directly creates Opportunity from hot inbound MQL after qualification call
- Marketing is NOT responsible for SQL conversion rate — this is a joint metric

OPPORTUNITY:
- Definition: SQL where AE has completed discovery call AND confirmed next step with a date on the calendar
- Opportunity stage 1 (Discovery Complete): AE documented business problem, key stakeholders, and proposed solution fit
- Opportunity stage 2 (Proposal/Evaluation): Formal proposal or POC/trial in progress
- Opportunity stage 3 (Commit): Verbal commit, legal/procurement engaged
- Closed Won / Closed Lost: Final disposition with mandatory close reason recorded

STEP 2: LEAD SCORING MODEL CONSTRUCTION

BUILD TWO SEPARATE SCORES:

BEHAVIORAL SCORE (Intent & Engagement):
Assign point values to behaviors. Higher intent = more points. Score resets on inactivity > [X days].

Tier 1 — High Intent (15-25 points each):
- Requested a demo or free trial: [X] points
- Attended a live product webinar: [X] points
- Viewed pricing page 2+ times in 7 days: [X] points
- Downloaded bottom-of-funnel asset (ROI calculator, vendor comparison guide): [X] points
- Clicked "Contact Sales" or "Talk to an Expert" CTA (did not complete form): [X] points

Tier 2 — Medium Intent (8-14 points each):
- Attended on-demand webinar replay: [X] points
- Downloaded gated MOFU content (guide, playbook, template): [X] points
- Visited /use-case/ or /solutions/ pages 2+ times: [X] points
- Completed interactive assessment or ROI calculator: [X] points
- Opened 4+ marketing emails in 14-day window: [X] points

Tier 3 — Low Intent / Awareness (2-7 points each):
- Downloaded TOFU content (industry report, checklist): [X] points
- Attended industry event where company sponsored: [X] points
- Visited home page or blog 3+ times in 14 days: [X] points
- Subscribed to newsletter: [X] points
- Social media click-through to website: [X] points

BEHAVIORAL SCORE DECAY:
- No website activity for 30 days: Score decays [X]%
- No email engagement for 60 days: Score decays [X]%
- No activity for 90 days: Score returns to 0, contact moves to Re-Engagement nurture track

DEMOGRAPHIC / FIRMOGRAPHIC FIT SCORE (ICP Match):
Assign points based on how closely contact matches ICP. This score does NOT decay.

A-Score (Perfect ICP — 80-100 points):
- Industry: [Target Industry 1], [Target Industry 2]: [X] points
- Company size: [X-X employees] or [X-XM ARR]: [X] points
- Title: VP/Director/C-Suite in [specific function]: [X] points
- Geography: [Target regions]: [X] points
- Technology stack signals (uses [competitor/complementary tool]): [X] points

B-Score (Good ICP Fit — 50-79 points):
- Industry: Adjacent or secondary market: [X] points
- Company size: Just outside primary range but still viable: [X] points
- Title: Manager level in target function OR VP in non-primary function: [X] points

C-Score (Poor ICP Fit — < 50 points):
- Industry: Outside target markets: [0 points]
- Company size: Too small (< [X employees]) or too large for current motion: [0 or negative points]
- Title: Individual contributor with no buying authority: [negative X] points

MQL THRESHOLD RULE:
Contact triggers MQL status when:
- Behavioral Score ≥ [X] points AND Demographic Score ≥ [Y] points
- OR Behavioral Score ≥ [Z] (very high single-event intent, e.g., demo request) regardless of demographic score — route to SDR for fit verification

STEP 3: LEAD HANDOFF SLA MATRIX

MARKETING COMMITMENTS (what marketing owes sales when routing an MQL):
1. Lead record completeness: Minimum fields populated — [list required fields: First Name, Last Name, Business Email, Company, Title, Phone (if available), Lead Source, Lead Source Detail, Last Behavior that triggered MQL, Score at handoff, ICP tier (A/B/C)]
2. Account-level research appended (for A-score leads): Company LinkedIn URL, employee count (verified), estimated ARR range, recent company news (if major event — funding, merger, new executive hire)
3. Intent context note: 2-3 sentence description of what the contact did to trigger MQL and what they likely care about based on content consumed

SALES COMMITMENTS (what sales owes marketing once an MQL is routed):
Lead Tier definitions and response SLAs:

HOT (Demo request, pricing page 3+ visits, trial start, score ≥ [X] with A-ICP):
- First outreach attempt: Within [2] business hours of assignment
- Full sequence initiated: Within [4] business hours
- SAL accept/reject decision: Within [4] business hours
- If no connect after [3] attempts: Alert SDR manager; do NOT let lead go dark

WARM (High behavioral score with B-ICP OR medium score with A-ICP):
- First outreach attempt: Within [1] business day of assignment
- Full sequence initiated: Within [1] business day
- SAL accept/reject decision: Within [1] business day

COLD (Low behavioral score, C-ICP, or automated-only engagement signals):
- Routed to SDR nurture sequence, not direct AE
- First outreach attempt: Within [3] business days
- SDR decides within [5] business days: Pursue or return to marketing nurture

DISPOSITION REQUIREMENT:
Every MQL must be dispositioned (SAL-Accepted, SAL-Rejected with reason code, or Active in Sequence) within the SLA window. Undispositioned leads aged > [X] business hours beyond SLA auto-escalate to sales manager.

STEP 4: FUNNEL MATH & PIPELINE VALIDATION

Working backward from revenue target:

TARGET-TO-LEAD WATERFALL CALCULATOR:

Quarterly Revenue Target: $[X]
÷ ACV: $[X]
= Deals Needed: [X]

÷ Opportunity-to-Close Rate: [X]%
= Opportunities Needed: [X]

÷ SQL-to-Opportunity Rate: [X]%
= SQLs Needed: [X]

÷ SAL-to-SQL Rate: [X]%
= SALs Needed: [X]

÷ MQL-to-SAL Rate: [X]%
= MQLs Needed from Marketing: [X/quarter] = [X/month]

Split by source (based on current lead mix):
- MQLs from Inbound/Content: [X/month] → Marketing's responsibility
- MQLs from Paid: [X/month] → Marketing budget responsibility
- SQLs sourced by SDR outbound: [X/month] → Sales Development responsibility
- SQLs from Partner/Referral: [X/month] → Partnership team responsibility

COVERAGE RATIO HEALTH CHECK:
Pipeline Coverage = (Open Opportunities × ACV) / Quarterly Revenue Target
- Healthy range: 3.0x–4.5x
- Below 3.0x: Demand gen intervention required, escalate to CMO
- Above 5.0x: Quality review required — opportunity stage inflation likely

MQL VOLUME SENSITIVITY TABLE:
Show marketing what happens to pipeline if MQL volume changes by ±20%:
| MQL Volume | Expected SQLs | Expected Opps | Expected Revenue (at current rates) |
| Current [X]/month | | | |
| +20% ([X]/month) | | | |
| -20% ([X]/month) | | | |

This table makes the "lead quality vs. lead volume" conversation mathematical: if quality improves (higher MQL-to-SQL conversion) but volume drops, does total pipeline increase or decrease? Show both scenarios.

STEP 5: JOINT ACCOUNTABILITY METRICS FRAMEWORK

MARKETING OWNS (marketing's OKRs — sales cannot blame marketing for these):
- Total MQL volume vs. target (monthly, by source)
- MQL demographic score distribution (% A-tier vs. B-tier vs. C-tier)
- MQL data completeness score (% of MQLs with all required fields populated)
- Marketing Sourced Pipeline ($) and % of total pipeline
- Cost per MQL by channel (monthly trend)
- MQL rejection rate (% of MQLs rejected by sales, and rejection reason breakdown)

SALES OWNS (sales' OKRs — marketing cannot blame sales for these):
- MQL-to-SAL response time (avg hours by lead tier)
- SAL-to-SQL conversion rate (monthly trend)
- SQL-to-Opportunity conversion rate
- Opportunity-to-Close rate
- Speed through pipeline stages (avg days in each stage)
- Rejection reason code usage rate (are reps providing rejection reasons? Is it > 95%?)

SHARED / JOINT METRICS (both teams own, both teams are accountable):
- Total pipeline created (net-new opportunities × ACV, monthly)
- Pipeline coverage ratio (both fail if this is below 3x)
- Marketing Sourced Revenue (closed won deals where marketing was first touch or key assist)
- MQL-to-Closed-Won conversion rate (the ultimate joint measure of funnel health)
- Average sales cycle length (both teams can influence this)

STEP 6: FEEDBACK LOOP PROTOCOL

REJECTION ANALYSIS CYCLE (monthly):
1. Pull all SAL rejections from CRM for the month — categorize by rejection reason code
2. If R1 (Competitor) > 5% of rejections: Audit lead source exclusion lists; add competitor domains to suppression in marketing automation
3. If R2 (Wrong Title) > 10% of rejections: Audit targeting in paid channels and content gating — are wrong titles being attracted?
4. If R5 (Data unverifiable) > 8% of rejections: Audit form fields and data enrichment process; add phone number or LinkedIn validation to high-tier forms
5. If total rejection rate > 30%: Trigger joint marketing-sales calibration session within 10 business days. Review 5 recent A-tier accepted leads and 5 recent rejected leads together to recalibrate scoring thresholds.

LEAD SCORING RECALIBRATION TRIGGER:
Automatically flag for scoring model review if any of the following occur:
- MQL-to-SQL conversion rate drops below [X]% for 2 consecutive months
- SAL rejection rate exceeds [X]% for 2 consecutive months
- A-tier ICP leads rejected at > [X]% rate
- A closed-won analysis reveals most deals came from leads that were scored below MQL threshold (scoring model is too conservative)

OUTPUT DELIVERY FORMAT:
1. Full SLA Document (shareable Google Doc format, ready for CMO and CRO co-signature)
2. Funnel Math Summary (1-page waterfall showing required volumes from target → closed deal → opportunity → SQL → MQL)
3. Lead Scoring Matrix (table format: behavior/firmographic factor | point value | rationale)
4. Response Time SLA Card (1-page quick reference for sales team: lead tier → required response window → escalation trigger)
5. Joint Accountability Dashboard Spec (list of metrics, owners, data source, reporting cadence)
6. Executive Alignment Summary (1-page: "Here is what we agreed to" — suitable for company all-hands or QBR kickoff)

## Example Input/Output

**Input Example:**

Company: Vaultify — cloud data backup and disaster recovery for mid-market IT teams
ACV: $38,000 | Sales cycle: 72 days | CRM: Salesforce | MAT: HubSpot
Quarterly revenue target: $2,280,000 | Current attainment: 79%
Team: 5 AEs, 4 SDRs | Marketing: 6-person team
Current MQL volume: 220/month | MQL-to-SQL rate: 18% (goal: 28%)
Current pipeline coverage: 2.4x (dangerously low)
Pain points: Sales says "MQLs are IT managers with no budget authority." Marketing says "Sales takes 5+ days to follow up on hot inbound leads." Both are correct — no SLA exists.
ICP: Director of IT / VP Infrastructure / CISO at companies 200-2,000 employees, industries: Financial Services, Healthcare, Manufacturing, Legal

**Output Example:**

**VAULTIFY MARKETING-SALES REVENUE ALIGNMENT SLA**
Effective Date: March 1, 2026 | Review Date: June 1, 2026
Co-signed by: [CMO Name] + [CRO Name]

---

**FUNNEL MATH: FROM TARGET TO MQL**

| Stage | Rate | Required Volume |
|---|---|---|
| Quarterly Revenue Target | — | $2,280,000 |
| Deals Needed | — | 60 deals ($38K ACV) |
| Opportunities Required | 40% close rate | 150 opportunities |
| SQLs Required | 55% SQL-to-Opp rate | 273 SQLs/quarter = 91/month |
| SALs Required | 75% SAL-to-SQL rate | 364 SALs/quarter = 121/month |
| MQLs Required | 80% MQL-to-SAL rate | 455 MQLs/quarter = 152/month |
| Current MQL Volume | — | 220/month (**+68/month surplus — quality problem, not volume problem**) |

**KEY INSIGHT FROM FUNNEL MATH:** Vaultify does not have a lead volume problem. At 220 MQLs/month vs. 152 needed, the issue is a quality and conversion problem. The MQL-to-SQL conversion rate of 18% needs to reach 28% — which means either the scoring model is letting through low-quality contacts, or sales is not working MQLs within SLA. Both are true based on the data. This SLA fixes both.

---

**REVISED FUNNEL STAGE DEFINITIONS**

**MQL (Marketing Qualified Lead):**
A contact in Salesforce who has achieved a combined lead score of ≥ 65 points (Behavioral Score ≥ 40 + Demographic Score ≥ 25) AND meets ALL of the following:
- Business email domain (no gmail/yahoo/hotmail)
- Company employee count: 150–2,500 (enriched via Clearbit or ZoomInfo append)
- Title must contain one of: Director, VP, Head of, Manager, CISO, CTO, IT Lead, Infrastructure, Security, Operations — OR contact explicitly requested a demo (override)
- NOT flagged as competitor domain (suppression list of 140+ vendor domains maintained by Marketing Ops)
- All required CRM fields populated: First Name, Last Name, Email, Company, Title, Lead Source, Lead Source Detail, Behavioral Score, Demographic Score

**SAL (Sales Accepted Lead):**
An MQL that an SDR has reviewed and confirmed within 4 business hours (Hot tier) or 1 business day (Warm tier) and marked "Accepted" in Salesforce Lead Status. Acceptance means SDR has verified: (1) contact title aligns to ICP decision-making level, (2) no duplicate opportunity already active, (3) company size falls within ICP range as verified on LinkedIn, (4) contact is reachable at submitted details.

**SQL (Sales Qualified Lead):**
A SAL where SDR/AE has completed a qualifying conversation and confirmed: (1) Active evaluation underway OR planned start within 90 days, (2) Identified a quantifiable business problem (e.g., "current backup solution failing RTO requirements, causing compliance risk"), (3) Economic buyer identified by name and accessible, (4) No blocker that prevents evaluation (e.g., budget freeze, org restructure). SQL = Opportunity Created in Salesforce.

---

**LEAD SCORING MATRIX**

| Behavior | Points | Rationale |
|---|---|---|
| Demo requested | 40 | Highest intent signal; routes directly |
| Pricing page 3+ visits in 7 days | 30 | Active evaluation behavior |
| Completed DR Readiness Assessment tool | 28 | High-intent interactive engagement |
| Attended live product webinar | 22 | Committed time; near-decision |
| Downloaded Disaster Recovery RFP Template | 20 | Vendor evaluation in progress |
| Viewed /pricing/ or /compare/ page (1x) | 15 | Early evaluation interest |
| Downloaded IT Security Benchmark Report | 12 | Research phase, ICP-aligned topic |
| Attended on-demand webinar replay | 10 | Engaged; less urgent than live |
| Opened 5+ emails in 14 days | 8 | Engaged but early-stage |
| Visited /use-cases/ section | 6 | Solution-aware, early research |
| Blog post read (3+ in 14 days) | 4 | Awareness engagement |
| Newsletter subscription | 2 | Minimal signal |

| Firmographic Factor | Points | Criteria |
|---|---|---|
| Perfect ICP title (Director IT / VP Infra / CISO) | 30 | Exact match to buying committee |
| Strong title (IT Manager / Security Manager) | 20 | Influencer; add to score not disqualify |
| ICP industry (Financial / Healthcare / Legal / Manufacturing) | 20 | Prioritized verticals |
| Adjacent industry (Professional Services / Tech) | 10 | Secondary priority |
| Company size 200–2,000 employees | 20 | Sweet spot |
| Company size 100–199 or 2,001–4,000 | 10 | Evaluatable edge of ICP |
| Company size < 100 or > 4,000 | -20 | Hard disqualifier |
| HQ in North America | 15 | Primary market |
| HQ in EMEA (if EMEA motion launched) | 10 | Secondary |
| Technology signal: uses AWS/Azure/GCP | 10 | Cloud-first = target profile |
| Technology signal: uses [named competitor] | 8 | Competitive displacement opportunity |

**MQL THRESHOLD:** Behavioral ≥ 40 + Demographic ≥ 25 = Total ≥ 65. Any demo request auto-routes regardless of demographic score.

---

**RESPONSE TIME SLA CARD**

| Lead Tier | Definition | First Outreach | Full Sequence | Disposition Deadline |
|---|---|---|---|---|
| HOT | Demo request OR score ≥ 85 with A-ICP | 2 business hours | 4 business hours | 4 business hours |
| WARM | Score 65–84 with A or B-ICP | 1 business day | 1 business day | 1 business day |
| COLD | Score 65+ with C-ICP; routed to SDR | 3 business days | 3 business days | 5 business days |

Escalation: Any HOT lead unworked for > 4 hours auto-alerts SDR Manager + VP Sales in Slack (#lead-alerts channel). Any lead undispositioned beyond SLA triggers Salesforce task escalation to manager.

---

**JOINT ACCOUNTABILITY SCORECARD (reviewed weekly in pipeline meeting)**

| Metric | Owner | Current | Target | Data Source |
|---|---|---|---|---|
| MQL volume | Marketing | 220/mo | 152/mo (on target) | HubSpot |
| MQL demographic score (A-tier %) | Marketing | 34% | 55% | Salesforce |
| MQL response time — HOT tier (avg hrs) | Sales | 27 hrs | < 2 hrs | Salesforce |
| SAL rejection rate | Joint | 38% | < 20% | Salesforce |
| MQL-to-SQL conversion | Joint | 18% | 28% | Salesforce |
| Pipeline coverage ratio | Joint | 2.4x | 3.5x | Salesforce |
| Marketing-sourced pipeline ($) | Joint | $1.1M | $1.9M | Salesforce |

**ROOT CAUSE ANALYSIS FROM SCORECARD:**
The data tells a clear story: Marketing is generating excess volume (220 vs. 152 needed) but only 34% A-tier, meaning 66% of MQLs are IT Managers and non-buyers — explaining sales' "low quality" complaint. Simultaneously, sales is averaging 27 hours to work HOT leads — 13.5x beyond SLA — meaning even the high-quality inbound demos are going cold. The SLA fixes both: Marketing raises demographic scoring criteria (target 55% A-tier), Sales commits to 2-hour HOT response. Expected result: MQL volume decreases 20–25%, MQL-to-SQL rate increases to 26–30%, pipeline coverage recovers to 3.2–3.8x within 60 days.

## Success Metrics
- Marketing-Sales SLA document co-signed by CMO and CRO within 30 days of generation
- MQL-to-SAL response time (HOT tier) measured weekly; below SLA triggers manager escalation, not post-hoc blame
- SAL rejection rate with reason codes reaches > 95% compliance (every rejection coded) within 60 days
- MQL-to-SQL conversion rate improves by ≥ 5 percentage points within 90 days of SLA implementation
- Pipeline coverage ratio improves from below-target to ≥ 3.0x within one full quarter under the new SLA
- Joint pipeline meeting adopts shared scorecard; "lead quality debate" replaced by metric-specific agenda within 30 days

## Related Prompts
- [Annual Marketing Strategy Framework](./Annual-Marketing-Strategy-Framework.md) — Build the annual strategy that defines which ICP segments to pursue; ICP definitions from this prompt feed directly into the demographic scoring model above
- [Marketing Budget Allocation Engine](./Marketing-Budget-Allocation-Engine.md) — Optimize marketing spend allocation across channels using the MQL volume targets and cost-per-MQL benchmarks established in this SLA
- [Marketing Pipeline Velocity Weekly Revenue Intelligence Engine](../Reporting-&-ROI/Marketing-Pipeline-Velocity-Weekly-Revenue-Intelligence-Engine.md) — Run weekly pipeline velocity analysis using the joint accountability metrics and pipeline coverage ratio thresholds defined in this SLA
- [Funnel Performance Diagnostics](../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Funnel-Performance-Diagnostics.md) — Diagnose where the funnel breaks using the stage-by-stage conversion rates formalized in this SLA document

## Integration Tips
- **Salesforce:** Create a custom Lead Status picklist with exact values matching your SLA stage definitions (MQL → SAL-Accepted → SAL-Rejected → SQL → Disqualified). Add custom fields: "Lead Tier" (Hot/Warm/Cold, auto-populated by workflow), "MQL Date/Time" (timestamp when status changed to MQL), "First SDR Activity Date/Time" (auto-stamped on first logged activity after MQL). Build a Salesforce Report: "MQL Response Time Compliance" filtered by MQL Date > [date range] showing MQL Date, First Activity Date, and calculated hours elapsed. Share this report link in weekly sales team standup — public accountability accelerates SLA compliance faster than any policy.
- **HubSpot:** In HubSpot, build the lead scoring model natively under Settings → Lead Scoring. Create two separate scoring properties: "Behavioral Score" and "Demographic Score." Build a workflow: when Behavioral Score + Demographic Score ≥ [threshold] AND required fields populated → set Lifecycle Stage to MQL → assign to SDR round-robin based on territory → send internal Slack/email notification to assigned SDR. Use HubSpot's "Deal Pipeline" sync with Salesforce to ensure lifecycle stage changes are reflected bidirectionally in both systems without manual CRM updates.
- **Slack:** Create a #hot-leads channel. Use Zapier or HubSpot/Salesforce Slack integration to auto-post a notification every time a HOT MQL is created: "@[assigned-SDR] 🔥 HOT LEAD assigned: [First Name] [Last Name] at [Company] | Title: [Title] | Last Action: [Behavior] | Score: [X] | Respond by: [time 2 hours from now]." This creates social accountability — the entire team can see whether HOT leads are being worked within SLA. Faster than any management process.
- **Notion / Confluence (SLA Documentation):** Publish the finalized SLA as a Notion page with these sections: Overview & Signatures, Funnel Stage Definitions, Lead Scoring Matrix, Response Time SLA Table, Rejection Reason Codes, Joint Metrics Scorecard, Feedback Loop Protocol. Link from the Sales team Notion homepage AND the Marketing team Notion homepage — the SLA must be findable by both teams without asking. Set a quarterly calendar reminder to review and update the SLA.
- **Google Sheets (Funnel Math Tracker):** Build a shared Google Sheet with the funnel math waterfall formula from Step 4. Use data validation so that CMO and CRO can update conversion rate assumptions and see real-time impact on required MQL volumes. Share with both teams as "Edit" access. This turns the funnel math from a one-time analysis into a live planning tool — whenever quarterly targets change, both teams can immediately see the downstream MQL volume implications without waiting for a RevOps meeting.
- **Gong / Chorus (Sales Call Intelligence for Scoring Calibration):** Connect your conversation intelligence platform to the feedback loop protocol. When SDRs reject SALs with reason code R2 (Wrong Title), use Gong/Chorus to pull recent call recordings from accepted SQLs and identify: what titles actually have buying authority at your ICP accounts? This qualitative intelligence recalibrates the demographic scoring matrix with real-world evidence rather than assumptions. Do this calibration pass quarterly.

## Troubleshooting

**Problem: Sales leadership agrees to the SLA in the meeting but SDRs/AEs don't follow the response time commitments — HOT lead response averages 18 hours instead of 2 hours.**
Solution: The problem is the SLA exists as a document but not as a system. Three fixes: (1) Make SLA compliance visible without management having to look — set up the #hot-leads Slack channel with automated notifications and public timestamps; when a lead sits unworked for 3 hours, an automated follow-up message tags the assigned rep and their manager. Public visibility changes behavior faster than private coaching. (2) Add SLA compliance rate to the SDR weekly performance scorecard alongside pipeline contribution — reps optimize for what's measured and reported to their manager. (3) Reduce friction: ensure that when a HOT lead notification fires, clicking the link takes the rep directly to the CRM record pre-loaded with the contact's LinkedIn URL, last 5 activities, and a one-click "Start Sequence" button. If it takes 7 clicks to start outreach, reps will avoid it under pressure.

**Problem: Marketing keeps generating MQLs that score highly on behavior but are the wrong title — individual contributor IT staff who will never have budget authority.**
Solution: Your demographic scoring model is under-weighting title and over-relying on behavioral signals. Two fixes: (1) Add a HARD GATE to the MQL trigger: regardless of behavioral score, if contact title contains "Analyst," "Associate," "Specialist," "Coordinator," or "Intern" — do NOT trigger MQL. Route to a long-nurture track and flag for ABM enrichment (is there a Director or VP at this same account already in the database?). (2) Increase the demographic score minimum threshold from [X] to [X+10], which functionally requires title match for almost all contacts. Review what % of closed-won deals had an individual contributor as first touch vs. first decision-maker touch — if ICs never close deals, do not route them as MQLs.

**Problem: We implemented the SLA but three months in, marketing and sales are still arguing — now about whether "pipeline coverage" is being calculated correctly.**
Solution: Disagreements about metric definitions are the same root cause as disagreements about MQL definitions — someone agreed to a label but not to the calculation. Fix: In the SLA documentation, add a "Metric Definitions" appendix that specifies exactly how every shared metric is calculated, from which CRM object, filtered by what date range, and excluding what. For pipeline coverage: "Open Opportunities created in the current quarter (Stage 1 through Stage 3, excluding Stage 4 Commit and Closed) × ACV, divided by Quarterly Revenue Target. Pulled from Salesforce Opportunity Report ID [X] refreshed every Monday at 9am." When two people look at the same saved Salesforce report, there is no argument. The fight was never about culture — it was about undefined numerators and denominators.

## Version History
- v1.0: Initial creation (auto-generated)
