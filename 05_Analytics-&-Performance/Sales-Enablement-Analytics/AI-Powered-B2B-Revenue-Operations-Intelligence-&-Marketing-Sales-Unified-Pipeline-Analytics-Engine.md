# AI-Powered B2B Revenue Operations Intelligence & Marketing-Sales Unified Pipeline Analytics Engine - Unified RevOps Dashboards, Pipeline Coverage Modeling, Marketing-to-Sales Handoff Analytics, and Revenue Waterfall Attribution for B2B SaaS

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** revenue-operations, revops, pipeline-analytics, marketing-sales-alignment, funnel-conversion, revenue-attribution, pipeline-coverage, forecasting, crm-analytics, demand-waterfall

## Overview

Architects a complete Revenue Operations analytics system that unifies marketing, sales, and customer success data into a single pipeline intelligence layer — giving CROs, CMOs, and RevOps leaders a shared revenue model where every stage of the buyer journey is measured, attributed, and optimized. Use when your marketing and sales teams are reporting different pipeline numbers, when your CFO questions marketing's pipeline contribution, or when you're scaling from founder-led sales and need a data-driven RevOps function that connects marketing spend to closed revenue with zero ambiguity.

## Quick Copy-Paste Version

You are a Revenue Operations analytics architect. Build a complete RevOps intelligence system for the following B2B SaaS company.

**Company Context:**
- Company: [e.g., "Prism Analytics — AI-powered financial close automation for mid-market CFOs ($30M–$300M revenue), targeting VP Finance, Controller, and CFO"]
- CRM: [e.g., "Salesforce with HubSpot Marketing Hub"]
- Current Pipeline Problem: [e.g., "Marketing says it sources 60% of pipeline; Sales says marketing contributes 20%. We have no agreed single source of truth. CFO is cutting marketing budget based on sales' number."]
- Monthly Lead Volume: [e.g., "~850 MQLs/month across all channels"]
- ACV: [e.g., "$42,000"]
- Sales Cycle: [e.g., "75 days average MQL-to-close"]
- Monthly Pipeline Target: [e.g., "$3.2M gross new pipeline per month to support $640K revenue target at 5× pipeline coverage"]
- Current Close Rate (SQL-to-Closed-Won): [e.g., "27%"]
- Team: [e.g., "4 AEs, 3 SDRs, 1 RevOps Manager, CMO and CRO both reporting to CEO"]

Build a complete Revenue Operations analytics architecture including:

1. **UNIFIED REVENUE DATA MODEL** — Define the single source of truth for all revenue metrics. Map which data lives in which system (CRM, MAP, data warehouse, BI tool), what field-level definitions must be agreed upon by marketing and sales before any reporting is built, and the governance model for maintaining data integrity. Include the 6 field definitions that must be locked before pipeline reporting is trustworthy: Lead Source, MQL Definition, SQL Definition, Pipeline Stage Definitions, Opportunity Source, and Revenue Attribution Model.

2. **DEMAND WATERFALL ANALYTICS** — Build the full revenue waterfall from anonymous website visitor to closed revenue with conversion rates, volume benchmarks, and leak detection at every stage. Stages: Visitor → Known Lead → Inquiry (raw form fill) → MQL (marketing-qualified) → SAL (sales-accepted lead) → SQL (sales-qualified) → Discovery/Demo Held → Proposal → Negotiation → Closed Won. For each stage transition: current conversion rate, B2B SaaS benchmark, gap analysis, and the single most impactful lever to improve that conversion.

3. **PIPELINE COVERAGE MODEL** — Calculate the pipeline coverage requirement for the current revenue target. Model: revenue target ÷ historical win rate = required pipeline. Then forecast forward: given current MQL volume, lead-to-SQL rate, and average deal size, what will pipeline coverage be in 30, 60, and 90 days? Identify coverage gaps by segment, channel, and rep before they become missed quarters.

4. **MARKETING-TO-SALES HANDOFF SLA ANALYTICS** — Define and measure the SLA between marketing and sales at every handoff point. Key SLAs: MQL-to-SDR contact attempt time (target: < 5 minutes), SDR-to-SAL conversion rate (target: > 65%), SAL-to-SQL conversion rate (target: > 45%), MQL rejection rate with rejection reason tracking (if > 20% rejected, marketing-sales ICP alignment is broken). Build a weekly SLA compliance dashboard with rep-level and channel-level breakdowns.

5. **REVENUE ATTRIBUTION MODEL ARCHITECTURE** — Define the marketing attribution model that both the CMO and CRO will agree on. Present three models side-by-side: (a) First-Touch Attribution (gives 100% credit to the channel that generated the original lead — favors top-of-funnel programs), (b) Last-Touch Attribution (100% credit to the final touchpoint before demo/form — favors BOFU programs), (c) Multi-Touch W-Shaped Attribution (distributes credit: 30% to first touch, 30% to lead creation touch, 30% to opportunity creation touch, 10% across all middle touches — most accurate for complex B2B buying). Recommend which model to use as the primary attribution model for the revenue board and why. Build the campaign-level attribution report that every marketing channel manager runs weekly.

6. **REVOPS KPI DASHBOARD ARCHITECTURE** — Design the three RevOps dashboards: (a) CEO/Board Dashboard (10 metrics, weekly, focuses on revenue and pipeline health), (b) CMO Dashboard (15 metrics, daily, focuses on demand generation, pipeline contribution, CAC, and channel efficiency), (c) CRO/Sales Dashboard (12 metrics, daily, focuses on pipeline velocity, rep productivity, and forecast accuracy). For each dashboard: exact metric definitions, data sources, refresh cadence, and alert thresholds.

7. **PIPELINE VELOCITY FORMULA OPTIMIZATION** — Calculate and optimize the four variables of pipeline velocity: (# of Opportunities) × (Average Deal Value) × (Win Rate) × (1 ÷ Average Sales Cycle Length). For each variable: current performance, improvement levers that marketing controls vs. sales controls, and the multiplier impact of a 10% improvement in each variable on total revenue output.

8. **QUARTERLY REVOPS ALIGNMENT CADENCE** — Define the operating rhythm for the Revenue Operations function: weekly pipeline reviews (format and agenda), monthly marketing-sales calibration sessions (MQL quality scoring, ICP refinement), quarterly full-funnel attribution audits (reconcile marketing and sales pipeline numbers, update attribution model weights), and annual RevOps system architecture review (data model, tech stack, KPI framework refresh).

Output: A complete, execution-ready Revenue Operations analytics architecture with unified data model, dashboard specifications, SLA framework, attribution model recommendation, and a 90-day RevOps buildout roadmap.

## Advanced Customizable Version

ROLE: You are a senior Revenue Operations architect and analytics strategist with 14+ years building RevOps functions at B2B SaaS companies from Series A through IPO. You have stood up RevOps systems at companies with $5M ARR (founder-led sales) through $250M ARR (enterprise, multi-product). You understand that the single biggest driver of revenue inefficiency in B2B SaaS is misalignment between marketing's pipeline number and sales' pipeline number — and that this misalignment stems entirely from undefined data models, not bad intentions. Your job is to build the analytics architecture that ends that debate permanently by creating a unified revenue data model that both the CMO and CRO sign their names to. You are expert in Salesforce reporting, HubSpot analytics, Looker/Tableau/Metabase dashboard design, multi-touch attribution modeling, pipeline coverage forecasting, and SLA compliance tracking. You never build vanity metric dashboards — every metric in your framework connects directly to revenue.

CONTEXT:
Company Name: [Your Company]
Product Category: [e.g., "Financial Close Automation" / "Security Operations Platform" / "HR Workflow SaaS"]
ICP: [Primary buyer title, company size, industry, key pain points]
ACV (Average Contract Value): [e.g., "$42,000"]
Average Sales Cycle (MQL to Close): [e.g., "75 days"]
Monthly MQL Volume (current): [e.g., "~850 MQLs/month"]
Monthly Pipeline Target: [e.g., "$3.2M gross new pipeline/month"]
Monthly New Revenue Target: [e.g., "$640K new ARR/month"]
CRM Platform: [Salesforce / HubSpot / Pipedrive / other]
Marketing Automation Platform: [Marketo / HubSpot / Pardot / other]
BI / Dashboard Tool: [Looker / Tableau / Metabase / Salesforce Reports / Google Looker Studio / other]
Data Warehouse (if any): [Snowflake / BigQuery / Redshift / none]
Current Pipeline Disconnect: [Describe the specific misalignment — e.g., "Marketing reports pipeline influenced; Sales reports pipeline sourced. These are 3× different numbers and we have no agreement on which to use."]
Team Structure: [Number of AEs, SDRs, marketing headcount, RevOps headcount, whether CMO and CRO are aligned or in conflict]
Historical Win Rate (SQL to Closed Won): [e.g., "27%"]
Historical Lead-to-SQL Rate (MQL to SQL): [e.g., "35%"]
Current CAC by Channel: [List if known — e.g., "Content: $1,400, Paid Search: $2,800, Outbound: $3,200, Events: $4,100"]
Current Marketing Attribution Model (if any): [e.g., "Last-touch in Salesforce campaigns — we know it's wrong but haven't fixed it"]
Primary Pain Point: [e.g., "CFO is cutting marketing budget because the pipeline attribution model shows marketing only sources 18% of pipeline, but we know that's wrong — we just can't prove it"]

OBJECTIVE: Build a complete Revenue Operations analytics architecture that creates a single, undeniable source of truth for pipeline and revenue that the CMO, CRO, and CFO all trust — and that gives every function a clear line of sight from their daily activities to the quarterly revenue number.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 1: UNIFIED REVENUE DATA MODEL & FIELD GOVERNANCE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**A. The Six Foundational Field Definitions**

Before any reporting is built, these six definitions must be agreed upon in writing by the CMO, CRO, and Head of RevOps. Any pipeline number produced before these definitions are locked is politically valid but analytically meaningless.

DEFINITION 1 — LEAD SOURCE (the originating channel):
- What it measures: The first channel that created the relationship between the company and the prospect
- Required field values (standardized, no freeform): Organic Search, Paid Search, Paid Social, Content / Organic Social, Outbound SDR, Outbound Marketing, Partner / Channel, Direct / Referral, Event / Webinar, Customer Referral, Product Signups (PLG)
- Governance rule: Lead Source is set once on Contact creation and NEVER overwritten. It captures the origin, not the journey.
- Common mistake to avoid: SDRs manually changing Lead Source to "Outbound" when they call a lead that originally came in through content — this destroys attribution accuracy and inflates outbound pipeline numbers

DEFINITION 2 — MQL (Marketing-Qualified Lead):
- What it measures: A lead that marketing certifies has sufficient quality and intent to warrant sales development time
- Qualification criteria (must be explicitly defined and agreed to): Lead Score threshold (e.g., "100+ points based on fit + behavior scoring model"), or Behavioral trigger (e.g., "Requested demo" / "Pricing page visit × 2 within 7 days" / "Attended webinar AND viewed product page"), or Account-level criteria (e.g., "TAL account with 3+ persona engagements in 30 days")
- SLA trigger: MQL status triggers SDR assignment SLA clock — SDR must contact within [X minutes] or MQL is flagged as SLA breach
- Anti-MQL definition: A lead that is NOT an MQL even if it meets score threshold (e.g., students, competitors, wrong company size, countries outside sales coverage)

DEFINITION 3 — SAL (Sales-Accepted Lead):
- What it measures: An MQL that the SDR/AE has reviewed and agreed meets ICP criteria
- Why it matters: SAL rate reveals whether marketing's MQL definition aligns with sales' ICP. If SAL rate < 65%, marketing is sending sales the wrong leads.
- How to track: CRM lead status field changed from "MQL" to "Sales Accepted" by SDR/AE; timestamp recorded
- Rejection workflow: If SDR rejects MQL, required to select rejection reason from dropdown: Wrong ICP (company size / industry), Wrong Persona (job title), No Budget Authority, Competitor Employee, Already a Customer, Timing (not evaluating for 12+ months), Duplicate Lead
- Analytics output: Weekly MQL rejection rate by rejection reason and by channel — this data drives ICP refinement, not blame assignment

DEFINITION 4 — SQL (Sales-Qualified Lead / Opportunity):
- What it measures: A prospect that sales has confirmed meets MEDDPICC/BANT criteria and warrants a formal opportunity
- Conversion trigger: SQL creation converts lead to Opportunity in CRM with: Opportunity Name, Account, Close Date (estimated), Amount (ACV), Stage, Primary Contact, and Opportunity Source (see Definition 5)
- SQL minimum criteria (define explicitly): Confirmed budget authority, Identified business problem that the product solves, Agreed next step with specific date, Company size and industry match ICP

DEFINITION 5 — OPPORTUNITY SOURCE (for pipeline attribution):
- What it measures: The primary channel credited with creating the opportunity — distinct from Lead Source
- Attribution logic (choose one and lock it): (a) Same as Lead Source (origin attribution — simplest, most marketing-friendly), (b) SDR-Created vs. Marketing-Created (binary — did an SDR create this opp or did marketing generate the lead that became this opp?), (c) Multi-touch (weighted distribution across all campaign touches before opportunity creation — most accurate, most complex)
- Governance rule: Opportunity Source must be set at opportunity creation by the system, not manually by the AE

DEFINITION 6 — PIPELINE CONTRIBUTION METHODOLOGY:
- What it measures: How marketing's contribution to pipeline is calculated
- Three methods (define which the company uses): (a) Pipeline Sourced — opportunities where marketing is the original lead source (the conservative number sales likes), (b) Pipeline Influenced — opportunities where at least one marketing touch occurred in the 90 days before opportunity creation (the larger number marketing likes), (c) Pipeline Attributed (Multi-Touch) — fractional revenue credit distributed across all marketing touches proportional to their weight in the attribution model (the accurate number both functions can defend to the CFO)
- Recommendation: Report all three numbers on the CMO dashboard, but agree on "Pipeline Attributed (Multi-Touch)" as the number used in board reporting and budget justification

**B. CRM Data Architecture Requirements**

Field schema required in CRM for complete RevOps analytics:

On Lead/Contact Object:
- Lead Source (picklist — values defined above)
- Lead Source Detail (free text — for channel sub-categorization, e.g., Lead Source = "Paid Social" → Lead Source Detail = "LinkedIn Ads — BOFU Retargeting Campaign")
- Lead Created Date (system timestamp)
- MQL Date (timestamp set when Lead Score crosses MQL threshold or MQL trigger fires)
- SAL Date (timestamp set when SDR changes status to Sales Accepted)
- MQL Rejection Reason (picklist — values defined above)
- UTM Source / UTM Medium / UTM Campaign / UTM Content / UTM Term (all five UTM parameters mapped to contact on form fill)
- First Page Seen (URL of the first page visited by this contact)
- Last Interesting Moment Date + Description (from MAP sync)

On Opportunity Object:
- Opportunity Source (picklist, system-set at creation — mirrors Lead Source values)
- Marketing Touches Pre-Opportunity (count of marketing campaign responses in 90 days before opp creation)
- First Marketing Touch Date (date of first campaign response ever)
- Last Marketing Touch Before Opp Creation Date
- SDR Who Converted Lead to Opp (lookup)
- Days MQL to SAL (formula field: SAL Date - MQL Date)
- Days SAL to SQL / Opp Creation (formula field: Opportunity Created Date - SAL Date)
- Days Opp Created to Close (formula field: Close Date - Opportunity Created Date)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 2: FULL-FUNNEL DEMAND WATERFALL ANALYTICS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**A. Waterfall Stage Definitions & Conversion Benchmarks**

Build the complete 9-stage revenue waterfall with current-state metrics, industry benchmarks, and leak detection:

STAGE 1: WEBSITE VISITORS → KNOWN LEADS
- Conversion metric: Visitor-to-Lead Rate (typically 1–3% for B2B SaaS)
- Data source: Marketing automation / CDP / website analytics
- Leak signal: If visitor-to-lead rate < 1%, landing page conversion is broken. Primary levers: form optimization, offer relevance, page load speed, mobile UX.
- Marketing's lever: CRO, content quality, offer positioning
- Sales' lever: None (pure marketing stage)

STAGE 2: KNOWN LEADS → MQL
- Conversion metric: Lead-to-MQL Rate (B2B SaaS benchmark: 15–25% of all leads become MQL)
- Data source: CRM + MAP lead scoring model
- Leak signal: If Lead-to-MQL Rate < 12%, lead quality is poor (wrong ICP entering top of funnel) or lead scoring model needs recalibration. If > 35%, MQL threshold is too loose and SDRs will reject high percentage.
- Marketing's lever: Channel mix quality, ICP targeting precision, lead scoring model calibration
- Sales' lever: Feedback on which lead characteristics correlate with closed deals

STAGE 3: MQL → SAL (Sales-Accepted Lead)
- Conversion metric: MQL-to-SAL Rate (B2B SaaS benchmark: 60–75%)
- Data source: CRM lead status history
- Leak signal: If MQL-to-SAL Rate < 55%, marketing and sales have ICP misalignment — sales is rejecting leads that marketing considers qualified. Run a 90-day cohort analysis on rejection reasons. This is the single most important metric for diagnosing marketing-sales misalignment.
- Marketing's lever: ICP definition refinement, channel targeting tightening
- Sales' lever: SDR response time SLA compliance (slow response inflates apparent rejection rate when leads go cold)

STAGE 4: SAL → SQL / OPPORTUNITY
- Conversion metric: SAL-to-SQL Rate (B2B SaaS benchmark: 40–60%)
- Data source: CRM lead-to-opportunity conversion
- Leak signal: If SAL-to-SQL Rate < 35%, SDR discovery quality is poor — SDRs are accepting leads but failing to qualify them to opportunity. This is an SDR coaching issue, not a marketing issue.
- Marketing's lever: Content support for SDR outreach sequences, persona-specific messaging for SDR to use in discovery
- Sales' lever: SDR qualification training, discovery call framework

STAGE 5: SQL / OPPORTUNITY → DEMO / DISCOVERY HELD
- Conversion metric: Opportunity-to-Demo Rate (benchmark: 75–85% — if an opp is created, the demo should almost always happen)
- Data source: CRM activity tracking (meeting held) + opportunity stage progression
- Leak signal: If < 70% of created opportunities hold a demo, no-show rate is high or AEs are creating opportunities prematurely before confirm commitment from prospect.
- Marketing's lever: Pre-demo nurture content to warm up prospect before AE call, reduce no-shows
- Sales' lever: Confirmation email sequences, calendar hold quality

STAGE 6: DEMO → PROPOSAL / EVALUATION
- Conversion metric: Demo-to-Proposal Rate (benchmark: 45–60% for enterprise SaaS, 60–75% for SMB SaaS)
- Data source: CRM opportunity stage history
- Leak signal: If Demo-to-Proposal Rate < 40%, demo quality is poor, ICP alignment is still too loose, or deal size mismatch (AEs pitching $100K solution to $20K budget buyers).
- Marketing's lever: Demo content support, post-demo case studies, ROI calculator tools for AE to use
- Sales' lever: Demo quality, discovery depth, MEDDPICC qualification rigor

STAGE 7: PROPOSAL → NEGOTIATION
- Conversion metric: Proposal-to-Negotiation Rate (benchmark: 50–65%)
- Data source: CRM stage progression
- Leak signal: If < 45%, proposals are not compelling enough or pricing is out-of-range for prospect's budget. Review rejected proposals for common objection patterns.
- Marketing's lever: Proposal templates, competitive comparison materials, ROI case studies
- Sales' lever: Proposal personalization, pricing structure, executive sponsor identification

STAGE 8: NEGOTIATION → CLOSED WON
- Conversion metric: Win Rate from Negotiation Stage (benchmark: 60–75% — at negotiation, you should be near the end)
- Data source: CRM closed won/lost tracking with primary loss reason
- Leak signal: If Negotiation-to-Closed-Won Rate < 50%, procurement or legal are killing deals after sales thinks they're won. Evaluate contract complexity, security review delays, and budget approval processes.
- Marketing's lever: Reference customer program (procurement requires references — having them on-call reduces close time), security documentation library
- Sales' lever: Executive sponsor relationship, legal team coordination, deal desk engagement

OVERALL WATERFALL SUMMARY OUTPUT:
For each company, calculate:
- Visitor-to-Closed Won conversion rate (end-to-end)
- Monthly leads needed to hit revenue target (working backwards from close rate)
- Biggest conversion gap vs. benchmark (the single stage where the most revenue is being lost)
- Revenue impact of a 5% improvement at the weakest stage

**B. Waterfall Cohort Tracking**

Track waterfall metrics by:
- Lead source cohort (how does Content-sourced pipeline convert vs. Paid Search vs. Outbound?)
- ICP segment cohort (Enterprise vs. Mid-Market vs. SMB — different waterfall profiles)
- Time cohort (monthly — are conversion rates improving or declining quarter-over-quarter?)
- AE cohort (which AEs convert SQL-to-Closed Won at benchmark rate? Which need coaching?)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 3: PIPELINE COVERAGE MODEL & FORECASTING
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**A. Pipeline Coverage Calculation**

The pipeline coverage ratio is the most important leading indicator of whether you will hit your revenue target:

Pipeline Coverage Ratio = Open Pipeline Value ÷ Revenue Target for the Period

B2B SaaS benchmarks by sales cycle length:
- 30-day sales cycle: 3–4× pipeline coverage required
- 60-day sales cycle: 4–5× pipeline coverage required
- 90-day sales cycle: 5–6× pipeline coverage required
- 120+ day sales cycle: 6–8× pipeline coverage required

Rationale: Coverage ratio accounts for win rate. If your win rate is 25%, you need 4× pipeline to ensure 100% of revenue target is covered from existing pipeline — assuming all pipeline closes within the quarter.

Pipeline Coverage Alert Thresholds:
- Green (on track): Coverage ≥ 5× target (for 75-day sales cycle)
- Yellow (at risk): Coverage 3–5× target → marketing must accelerate pipeline generation immediately
- Red (miss imminent): Coverage < 3× target → escalate to CEO; both marketing and sales need emergency pipeline sprint

**B. 30/60/90-Day Pipeline Forecast Model**

Build the rolling pipeline forecast using current funnel inputs:

INPUT VARIABLES (pull weekly from CRM):
- Current open MQL volume (MQLs not yet converted to SQL)
- Current MQL-to-SQL conversion rate (trailing 90-day average)
- Average days MQL-to-SQL (trailing 90-day average)
- Current open SQL/Opportunity volume by stage
- Average days per opportunity stage (stage velocity)
- Win rate by stage (probability-weighted pipeline value)
- Average deal size (trailing 6-month average, segmented by ICP tier)

FORECAST CALCULATION:
30-Day Revenue Forecast = (Stage 7 Negotiation Pipeline × Win Rate from Negotiation) + (Stage 6 Proposal Pipeline × Win Rate from Proposal) × [if within average days-to-close window]

60-Day Revenue Forecast = Add Stage 5 Demo Pipeline × staged conversion probabilities

90-Day Revenue Forecast = Add current open MQL × MQL-to-SQL rate × SQL-to-Close rate × average ACV (for MQLs created in last 30 days that will enter pipeline within 60 days)

Coverage Gap Identification:
If 90-day forecast < revenue target:
Coverage Gap = Revenue Target − 90-Day Forecast
Pipeline Needed to Close Gap = Coverage Gap ÷ Win Rate
MQLs Needed to Close Gap = Pipeline Needed ÷ (MQL-to-SQL Rate × ACV)

Output: Tell marketing exactly how many MQLs they need to generate in the next 30 days to close the coverage gap before it becomes a missed quarter.

**C. Pipeline Health Segmentation**

Segment open pipeline by health status:
- Healthy: Last activity within 14 days, close date within 90 days, stage progression in last 30 days
- At Risk: No activity in 15–30 days OR close date pushed more than twice in last 90 days
- Dead (Zombie Pipeline): No activity in 31+ days, close date in the past, no next step logged
- Needs Acceleration: Healthy opportunity but deal velocity is below average for its stage

Alert marketing when pipeline health degrades: marketing should deploy targeted nurture content, executive sponsor touchpoints, or event invitations to accounts with "At Risk" opportunities — marketing can re-engage prospects that sales has gone cold on.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 4: MULTI-TOUCH ATTRIBUTION MODEL
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**A. Attribution Model Selection Framework**

Build and present the three primary attribution models side-by-side for the same pipeline dataset:

MODEL 1 — FIRST-TOUCH (Source Attribution):
- Logic: 100% of pipeline and revenue credit goes to the channel that created the original lead
- Best for: Measuring which channels are best at generating net new relationships
- CMO impact: Favors top-of-funnel investments (SEO, brand, content, paid awareness)
- CRO perception: "Undervalues sales outbound because SDRs convert old content leads that happened to come in first"
- When to use: Planning top-of-funnel budget allocation

MODEL 2 — LAST-TOUCH (Conversion Attribution):
- Logic: 100% of pipeline and revenue credit goes to the final touchpoint before form fill or demo booking
- Best for: Measuring which channels close the deal (capture intent vs. create intent)
- CMO impact: Favors BOFU investments (paid search, retargeting, demo campaigns)
- CRO perception: "Over-credits paid search because it captures intent that content built — we don't need to pay for Google clicks if we already own organic position"
- When to use: Optimizing conversion campaigns and BOFU spend

MODEL 3 — W-SHAPED MULTI-TOUCH (Recommended for board-level reporting):
- Logic: 30% credit to first touch (origin), 30% credit to lead-creation touch (the touchpoint that converted anonymous to known), 30% credit to opportunity-creation touch (what was happening when the deal opened), 10% distributed across all remaining touches
- Best for: Capturing the full buyer journey contribution of marketing without over or under-crediting any single channel
- CMO impact: Balanced — rewards both awareness and conversion investments
- CRO perception: Defensible because it credits the touchpoint that opened the opportunity (often SDR outbound) at 30%
- Board-level case: "Every dollar of pipeline touched at least one marketing activity before the deal opened; this model shows how much of that pipeline is attributable to each marketing motion"

ATTRIBUTION CALCULATION EXAMPLE (use provided company data):
For a $42K ACV opportunity with the following touch history:
- Touch 1 (First): Organic blog post "How to automate financial close" — read 95 days before opp creation
- Touch 2 (Lead Creation): Downloaded "CFO Financial Close Benchmark Report" gated PDF — 82 days before opp creation
- Touch 3 (Middle): Attended webinar "2025 Financial Close Trends" — 45 days before opp creation
- Touch 4 (Middle): LinkedIn Retargeting Ad click — 30 days before opp creation
- Touch 5 (Opp Creation): SDR cold email sequence referencing the benchmark report — 12 days before opp creation, triggered demo booking

W-Shaped Attribution Credit:
- Organic Search (Touch 1 / First Touch): $42K × 30% = $12,600
- Content (Touch 2 / Lead Creation): $42K × 30% = $12,600
- SDR Outbound (Touch 5 / Opp Creation): $42K × 30% = $12,600
- Webinar (Touch 3): $42K × 5% = $2,100
- LinkedIn Ads (Touch 4): $42K × 5% = $2,100

Marketing-Attributed Pipeline from this deal: $29,400 (70% — Organic + Content + Webinar + LinkedIn)
Sales-Attributed Pipeline from this deal: $12,600 (30% — SDR Outbound)

**B. Channel-Level Attribution Report**

Weekly marketing channel attribution report (to be produced every Monday morning and shared with CMO, CRO, and RevOps team):

| Channel | Pipeline Created (W-Shaped) | Pipeline Created (First-Touch) | Pipeline Created (Last-Touch) | Closed Won (W-Shaped) | CAC | Pipeline ROAS |
|---|---|---|---|---|---|---|
| Organic Search | $X | $X | $X | $X | $X | X× |
| Paid Search | $X | $X | $X | $X | $X | X× |
| LinkedIn Ads | $X | $X | $X | $X | $X | X× |
| Content / Blog | $X | $X | $X | $X | $X | X× |
| Outbound SDR | $X | $X | $X | $X | $X | X× |
| Events / Webinars | $X | $X | $X | $X | $X | X× |
| Partner / Channel | $X | $X | $X | $X | $X | X× |
| **TOTAL** | **$X** | **$X** | **$X** | **$X** | **$X** | **X×** |

Purpose: This table ends the "marketing vs. sales pipeline" debate by showing all three models simultaneously. The CMO reports the multi-touch number; sales acknowledges outbound SDR credit appears in all three.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 5: REVOPS KPI DASHBOARD ARCHITECTURE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**A. CEO / Board Dashboard (Weekly, 10 Metrics)**

Purpose: Revenue health at a glance. No marketing jargon, no sales jargon — just money.

| Metric | Definition | Data Source | Alert Threshold |
|---|---|---|---|
| New ARR Booked (MTD) | Closed-Won ACV this month | CRM | < 75% of monthly target by Day 20 |
| Pipeline Coverage Ratio | Open pipeline ÷ revenue target | CRM | < 4× = red alert |
| Pipeline Created (WoW) | New opportunities opened this week vs. 4-week average | CRM | < 80% of 4-week average |
| Win Rate (Trailing 90 Days) | SQL-to-Closed-Won rate | CRM | < 22% = AE coaching needed |
| Average Sales Cycle | Median days MQL to Close | CRM | > 90 days = friction diagnosis required |
| CAC (Blended) | Total Sales + Marketing spend ÷ New logos closed | Finance + CRM | > 3× ACV = unsustainable |
| CAC Payback Period | CAC ÷ (ACV × Gross Margin) in months | Finance + CRM | > 18 months = board flag |
| Magic Number | New ARR added ÷ Prior quarter Sales + Marketing spend | Finance + CRM | < 0.75 = efficiency alarm |
| MQL-to-SQL Rate (Trailing 30 Days) | Marketing-sales alignment health | CRM | < 28% = ICP alignment broken |
| Marketing Pipeline Contribution (%) | Marketing-attributed pipeline ÷ total pipeline (W-Shaped) | CRM + BI | < 35% = marketing investment insufficient |

**B. CMO Dashboard (Daily, 15 Metrics)**

Revenue-connected marketing metrics only — no impressions, no followers, no engagement rate unless tied to pipeline.

DEMAND GENERATION:
- MQLs Created (daily / weekly / monthly vs. target)
- MQL-to-SAL Rate (daily, rolling 14-day average)
- Cost Per MQL by channel (updated weekly)
- Pipeline Created (marketing-attributed, W-shaped, weekly vs. target)
- Pipeline Influenced (touches on all open opportunities, rolling 30-day)

PIPELINE HEALTH:
- Marketing Pipeline Coverage Contribution ($ value of marketing-sourced pipeline that covers this month's revenue target)
- Marketing-Sourced Closed Won ($ ARR closed this month from marketing-sourced opportunities)
- Marketing-Attributed Pipeline-to-Revenue Conversion Rate (trailing 90-day: what % of marketing-attributed pipeline becomes closed won?)

CHANNEL EFFICIENCY:
- Channel ROAS by source (LinkedIn Ads, Google Ads, Content, Events — pipeline ÷ spend, weekly)
- CAC by channel (monthly, compared to prior month)
- Program-Level Attribution (which campaigns are producing qualified pipeline vs. volume leads?)

FUNNEL HEALTH:
- Visitor-to-Lead Rate (weekly, vs. 4-week average)
- MQL Rejection Rate + Primary Rejection Reason (weekly — if rising, ICP calibration is needed)
- Lead Velocity Rate (LVR): Month-over-month growth in qualified leads (leading indicator of revenue growth 2–3 months out)
- Content-to-Pipeline Attribution (which specific content pieces are referenced in won opportunities?)

**C. CRO / Sales Dashboard (Daily, 12 Metrics)**

PIPELINE GENERATION:
- New Opportunities Opened (weekly vs. target, by AE and SDR)
- SDR-Sourced vs. Marketing-Sourced Opportunities (split by creation trigger)
- Pipeline Stage Distribution ($ value by stage — are deals aging in any single stage?)

PIPELINE VELOCITY:
- Average Days Per Stage (how long do deals sit in Discovery vs. Proposal vs. Negotiation?)
- Pipeline Velocity Formula Output (# opps × avg ACV × win rate × 1/cycle length)
- Deal Stage Conversion Rates by AE (who is losing deals at which stage?)

FORECAST:
- Commit Forecast (deals AEs are forecasting to close this month)
- Best Case Forecast (commit + likely deals)
- Pipeline Forecast vs. Revenue Target Gap (how much coverage exists for the rest of the quarter?)
- At-Risk Pipeline (deals with no activity in 14+ days)

PRODUCTIVITY:
- SDR MQL-to-SAL Rate (by SDR — who is accepting the right leads and converting them?)
- AE SQL-to-Demo Rate and Demo-to-Close Rate (identify which AEs need coaching)
- Average ACV by Lead Source (are certain channels producing larger deals?)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 6: PIPELINE VELOCITY OPTIMIZATION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**A. Pipeline Velocity Formula**

Pipeline Velocity ($ per day) = (# of Open Opportunities × Average Deal Value × Win Rate) ÷ Average Sales Cycle in Days

Example calculation:
- Open opportunities: 124
- Average ACV: $42,000
- Win rate: 27%
- Average sales cycle: 75 days
- Pipeline Velocity = (124 × $42,000 × 0.27) ÷ 75 = **$18,749 per day** = $562,470/month

**B. Lever-by-Lever Impact Analysis**

For each of the four pipeline velocity levers, calculate the revenue impact of a 10% improvement:

Lever 1 — Increase Number of Opportunities (10% more opps: 124 → 136):
- New pipeline velocity: (136 × $42,000 × 0.27) ÷ 75 = $20,563/day = +$54,420/month
- Marketing controls: MQL volume, MQL quality, inbound demand generation investment
- Sales controls: SDR conversion rate, outbound prospecting efficiency

Lever 2 — Increase Average Deal Value (10% increase: $42K → $46.2K):
- New pipeline velocity: (124 × $46,200 × 0.27) ÷ 75 = $20,624/day = +$55,650/month
- Marketing controls: ICP targeting precision (are we generating Enterprise vs. SMB deals?), positioning for multi-year contracts, upsell/expansion positioning in demand gen content
- Sales controls: Upsell during initial deal, multi-year discount architecture

Lever 3 — Improve Win Rate (10% improvement: 27% → 29.7%):
- New pipeline velocity: (124 × $42,000 × 0.297) ÷ 75 = $20,624/day = +$55,650/month
- Marketing controls: Case study library quality, competitive battle cards, reference customer availability
- Sales controls: Discovery quality, objection handling, competitive positioning, MEDDPICC execution

Lever 4 — Reduce Sales Cycle (10% reduction: 75 days → 67.5 days):
- New pipeline velocity: (124 × $42,000 × 0.27) ÷ 67.5 = $20,832/day = +$62,490/month (highest ROI lever per unit of improvement)
- Marketing controls: Pre-demo nurture to reduce time-to-commit, deal acceleration content for stuck deals, executive briefing center content for procurement speed
- Sales controls: Demo quality, next-step discipline, multi-threading buying committee

Revenue Impact Summary: Improving all four levers by 10% simultaneously produces approximately +$228K/month in incremental pipeline velocity — without increasing headcount.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 7: REVOPS OPERATING CADENCE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Weekly Pipeline Review (Every Monday, 45 minutes)**

Attendees: CRO, CMO, RevOps Lead, SDR Manager, AE Team Lead
Agenda (strict — no side conversations):
- 10 min: Pipeline coverage dashboard review (where does coverage stand vs. target?)
- 10 min: MQL volume and quality review (last 7 days: volume vs. target, SAL rate, rejection reasons)
- 10 min: Open pipeline stage progression (which deals advanced, which stalled, which need acceleration?)
- 10 min: At-risk pipeline identification (deals with no activity — immediate action items assigned)
- 5 min: Top 5 close candidates this week (AE commit forecast — specific deals with close probability > 80%)

Output: Shared Google Doc with deal-level action items, pipeline gap number, and marketing acceleration requests (e.g., "We have 3 deals stuck in Proposal stage at Acme Inc., Meridian Health, and TeraSoft — send executive case study to all three contacts by Wednesday").

**Monthly Marketing-Sales Calibration (First Wednesday of Each Month, 60 minutes)**

Attendees: CMO, CRO, SDR Manager, one AE representative, RevOps Lead
Agenda:
- 15 min: MQL quality scorecard review (SAL rate, rejection rates by channel, lead quality scores)
- 15 min: ICP refinement session (which closed-won logos don't fit our stated ICP? Which do we wish we had more of? Update ICP scoring model accordingly)
- 15 min: Lead source performance review (which channels are producing the best lead-to-SQL rates? Adjust targeting recommendations)
- 15 min: Attribution model calibration (are there channel contributions being missed by the current model? Review win/loss interviews for unreported marketing influence)

Output: Updated ICP scoring criteria (if any), channel targeting recommendations for next 30 days, updated MQL definition (if SAL rate has shifted significantly).

**Quarterly Full-Funnel Attribution Audit (Last week of each quarter, 2-hour session)**

Attendees: CMO, CRO, CFO, RevOps Lead, Data Analyst
Purpose: Reconcile all pipeline numbers, attribute closed-won revenue across channels, and present the agreed quarterly marketing contribution to the board.
Agenda:
- 30 min: Closed-won cohort analysis (all deals closed this quarter — full attribution waterfall, channel contribution)
- 30 min: Pipeline creation analysis (all opps opened this quarter — channel breakdown, attribution model comparison across all three models)
- 20 min: CAC and CAC Payback by channel (where are we over-investing? Under-investing?)
- 20 min: Next quarter pipeline coverage forecast (do we have enough pipeline entering Q+1?)
- 20 min: Budget reallocation recommendations based on attribution data

Output: Signed quarterly RevOps report that becomes the official record for board reporting and budget justification.

## Example Input/Output

**Input Example:**

Company: Prism Analytics — AI-powered financial close automation platform
ICP: VP Finance and Controller at $30M–$300M revenue B2B companies
ACV: $38,000 | Sales Cycle: 68 days | MQL Volume: 720/month
Pipeline Target: $2.8M/month | Win Rate: 26%
CRM: Salesforce | MAP: HubSpot | BI: Looker
Current problem: "Marketing reports it sources 58% of pipeline. Sales says 21%. CFO about to cut marketing budget by 35% based on the sales number. CMO and CRO have been arguing about attribution for 6 months."

**Output Example (excerpt):**

**ROOT CAUSE DIAGNOSIS:**

The 58% vs. 21% discrepancy is caused by three specific data problems:

Problem 1 — Definition conflict: Marketing is reporting "Pipeline Influenced" (any opportunity touched by marketing) while Sales is reporting "Pipeline Sourced" (opportunities where SDR was not the originating contact). These measure completely different things. Neither number is wrong — they're measuring different concepts. The fix is to agree on "W-Shaped Multi-Touch Pipeline Attribution" as the primary metric, which will produce a number between the two that both functions can defend.

Problem 2 — Missing Opportunity Source field: 34% of opportunities in Salesforce have Opportunity Source = "Unknown" or blank because AEs are not populating it at opportunity creation. This artificially deflates marketing attribution because blank opps are counted as "Sales Sourced" by default. Fix: Make Opportunity Source a required field in Salesforce at opportunity creation; set a system default that traces back to Lead Source if the AE doesn't override it.

Problem 3 — Attribution window: Marketing is counting all touches going back 180 days; sales is only counting touches within 30 days of opportunity creation. Marketing sees a content piece that a prospect read 5 months ago; sales doesn't consider a 5-month-old blog read as a "source." Fix: Standardize attribution window to 90 days pre-opportunity creation for all multi-touch models.

**IMMEDIATE ACTION PLAN (Week 1):**
1. Fix the Opportunity Source required field in Salesforce — today, before any other analysis (this takes 15 minutes in Salesforce Setup)
2. Export all closed-won opportunities from the last 6 months and manually backfill Opportunity Source based on Lead Source on the originating Contact
3. Run the W-Shaped attribution model on this backfilled dataset
4. Present the three attribution models side-by-side to CMO, CRO, and CFO in one meeting — show the range ($21M sourced to $48M influenced, with $32M as the W-shaped attributed number)
5. Agree on $32M as the official marketing pipeline attribution number for this quarter and lock the attribution model going forward

**PIPELINE COVERAGE MODEL (based on Prism inputs):**
- Revenue target this month: $640K
- Required pipeline at 26% win rate: $640K ÷ 0.26 = $2.46M minimum
- Current open pipeline: $3.1M → 4.8× coverage → **Yellow** (adequate but below the 5× target for a 68-day sales cycle)
- 30-day pipeline forecast: 720 MQLs × 35% MQL-to-SQL rate × $38K ACV = $9.6M pipeline entering; at 68-day cycle, ~35% of this month's new pipeline will close within 90 days = $3.4M eligible for this quarter
- Gap identification: Coverage is adequate this month but drops to 3.8× projected for next month if MQL volume doesn't increase. Marketing needs to generate 120 additional MQLs this month to maintain 5× coverage for Q+1.

**DASHBOARD SPEC (CEO Weekly Dashboard — Prism Analytics):**
- New ARR Booked (MTD): $287K / $640K target → 45% attainment at Day 12 → Yellow (should be at 40% by Day 12 — on track)
- Pipeline Coverage: $3.1M / $640K target = 4.8× → Yellow (target is 5×)
- Win Rate (90-day): 26% → Green (benchmark 22–28% for 68-day cycle)
- MQL-to-SQL Rate: 31% → Green (benchmark 28–35%)
- Marketing Pipeline Contribution (W-Shaped): 54% of pipeline has marketing attribution → Green
- CAC Payback: 14 months → Green (target < 18 months)

## Success Metrics

**Green (RevOps System is Working):**
- Marketing and sales agree on pipeline number within 15% of each other
- MQL-to-SAL Rate > 65% (ICP alignment is strong)
- Pipeline Coverage ≥ 5× revenue target (trailing 30 days)
- Attribution model is locked and accepted by CMO, CRO, and CFO
- Weekly pipeline review attendance > 90% (alignment is happening)
- Zero "blank" Opportunity Source fields in CRM (data governance is enforced)

**Yellow (Calibration Required):**
- Marketing-sales pipeline number divergence > 20% (definition or data problem)
- MQL-to-SAL Rate 50–65% (ICP refinement meeting needed)
- Pipeline Coverage 3–5× (marketing acceleration needed)
- CAC by channel not updated in > 30 days (attribution data is stale)

**Red (RevOps System is Broken):**
- Marketing and sales pipeline numbers diverge by > 40% (no shared data model)
- MQL-to-SAL Rate < 50% (fundamental ICP misalignment — SDRs rejecting marketing leads at high rate)
- Pipeline Coverage < 3× (emergency pipeline sprint required, likely a missed quarter)
- RevOps dashboard not used in weekly pipeline reviews (leadership disengaged from data)

## Related Prompts

- [AI-Powered B2B Sales Enablement Program ROI & Enablement-to-Revenue Impact Intelligence Engine](../../05_Analytics-&-Performance/Sales-Enablement-Analytics/AI-Powered-B2B-Sales-Enablement-Program-ROI-&-Enablement-to-Revenue-Impact-Intelligence-Engine.md)
- [Marketing Funnel Conversion & Pipeline Velocity Intelligence Engine](../../05_Analytics-&-Performance/Funnel-Conversion-&-Pipeline-Velocity/Marketing-Funnel-Conversion-&-Pipeline-Velocity-Intelligence-Engine.md)
- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [Marketing-Sales Revenue Alignment & SLA Engine](../../01_CMO-&-Leadership/Strategy-&-Planning/Marketing-Sales-Revenue-Alignment-&-SLA-Engine.md)

## Integration Tips

**Salesforce**: Build the RevOps dashboard natively in Salesforce Reports and Dashboards. Key reports to build: (1) Lead Conversion Funnel report (Lead Status history showing MQL Date, SAL Date, SQL Date for all leads created in last 90 days — requires "Lead History" report type); (2) Opportunity Source Analysis report (Opportunity object, grouped by Opportunity Source with sum of Amount and count of closed won); (3) Pipeline Coverage by Close Month (Opportunity object, summarized by Close Month with Amount column — compare to revenue targets in a dashboard tile); (4) SDR SLA Compliance report (Lead object filtered to MQL status, showing time between MQL Date and First Activity Date by SDR). Use Salesforce Forecasting with Custom Forecast Categories to maintain separate Commit, Best Case, and Pipeline forecasts.

**HubSpot**: Use HubSpot's Revenue Attribution Reports (Marketing Hub Enterprise required). Navigate to Reports → Attribution Reports to access First-Touch, Last-Touch, and Linear multi-touch models natively. Build a Custom Report using the "Deals with associated contacts, marketing activities, and line items" data set — this enables W-shaped attribution calculation manually by exporting and weighting touches in Google Sheets. Use HubSpot's Deal Pipeline Report (grouped by deal stage with sum of amount) for pipeline stage health visualization. Connect HubSpot to Google Looker Studio via the HubSpot Looker Studio connector for custom RevOps dashboards.

**Looker / Tableau / Metabase**: Build three persistent dashboard views: (1) RevOps Command Center (all 10 CEO metrics in a single view, auto-refreshed hourly from CRM data warehouse sync); (2) Marketing Channel Attribution Matrix (the multi-model attribution table with all three models side-by-side, filterable by time period, ICP segment, and deal size); (3) Pipeline Waterfall (funnel visualization showing volume and conversion rate at each waterfall stage, with week-over-week and quarter-over-quarter comparisons). If using Snowflake or BigQuery as your data warehouse, build a dbt model that pre-calculates W-shaped attribution weights at the contact-opportunity level so the BI tool doesn't need to compute attribution on every query.

**Zapier / Make Automation**: Build automated alerts: (1) Pipeline Coverage Alert — run daily at 7am, if pipeline coverage drops below 4×, send Slack message to #revenue-leadership channel with current coverage ratio and MQL gap calculation; (2) MQL SLA Breach Alert — when a Lead is marked MQL in Salesforce/HubSpot and no SDR activity is logged within 5 minutes, send Slack alert to SDR manager with lead name, company, and time since MQL; (3) Zombie Pipeline Alert — every Monday morning, send Slack message to each AE with list of their opportunities with no activity in 14+ days, along with suggested re-engagement content piece from marketing.

**Google Sheets + Looker Studio (no-code RevOps stack)**: For companies without Looker/Tableau: export weekly CRM data to Google Sheets (automate via Zapier or CRM native export schedule), build pipeline coverage model in Google Sheets using formula: =SUMIF(stage_range,"Proposal",amount_range)/revenue_target, and visualize in Looker Studio with Google Sheets as data source. The entire CEO dashboard described above can be built in Looker Studio + Google Sheets in 2–3 hours with no SQL required.

## Troubleshooting

**Problem 1: Marketing and sales pipeline numbers are still diverging after implementing the attribution model**

Cause: Most commonly caused by CRM data quality issues that weren't identified during implementation — specifically, SDRs or AEs retroactively changing Lead Source or Opportunity Source fields after the fact, often to inflate their own channel's contribution or avoid accountability.

Fix: Enable field history tracking in Salesforce for Lead Source, MQL Date, SAL Date, and Opportunity Source fields. Pull a field history report monthly to identify any retroactive field changes — if pattern of SDR changing Lead Source from "Organic Search" to "Outbound" is identified, address in the monthly marketing-sales calibration. Add a validation rule in Salesforce that prevents Opportunity Source from being changed by anyone except RevOps role after opportunity creation date. For HubSpot: use the audit log to identify retroactive property changes on high-value contacts.

**Problem 2: Pipeline coverage ratio looks healthy but the company keeps missing revenue targets**

Cause: The pipeline is "zombie pipeline" — opportunities that are technically open and counting toward coverage but have no real path to close. This inflates coverage ratio without representing real demand. Common signals: average days-since-last-activity > 21 days across the pipeline, high proportion of deals with pushed close dates (2+ times), AE commit forecast significantly lower than total pipeline value.

Fix: Implement pipeline health scoring. Mark every opportunity with a health status (Active, At Risk, Zombie) based on activity recency, close date stability, and stage progression velocity. Remove zombie pipeline from the coverage ratio calculation (or create a "Quality-Adjusted Pipeline Coverage" metric that applies a discount factor: Active opps count at 100%, At Risk at 60%, Zombie at 10%). This gives a more accurate view of whether the pipeline will actually close. Run quarterly pipeline hygiene reviews where RevOps archives all opportunities with no activity in 60+ days and stale close dates.

**Problem 3: The multi-touch attribution model credits marketing but CMO still can't get budget approved because the CFO doesn't trust the model**

Cause: Attribution models are often perceived as marketing's attempt to take credit rather than an objective measurement framework. CFOs who grew up in finance distrust any model they didn't build and can't audit. The problem is usually transparency, not accuracy.

Fix: Bring the CFO into the attribution model construction meeting, not the results presentation. Show the CFO the raw data: pull 20 closed-won deals from the last quarter and manually walk through every marketing and sales touch that occurred before each deal closed. Ask the CFO which touches they believe influenced the deal. Build the weighting model based on that discussion — the CFO is now co-author of the attribution model and will defend it at board level. Additionally, triangulate the marketing attribution number with marketing mix modeling (if applicable) and incrementality testing (e.g., test: turn off LinkedIn Ads for one month in one region and measure pipeline impact — the measured decline proves LinkedIn's contribution without relying on attribution logic).

## Version History
- v1.0: Initial creation (auto-generated)
