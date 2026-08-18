# AI-Powered B2B SaaS Marketing Revenue Operations Architecture & CMO-Led Revenue Accountability Intelligence Engine - Build the MRevOps Function That Turns Marketing from a Cost Center into a Revenue Engine

**Difficulty:** Advanced | **Time:** 30-45 min | **Tags:** b2b-saas, marketing-operations, revenue-operations, revops, pipeline-accountability, cmo-strategy, marketing-finance, mrevops

## Overview
Designs a complete Marketing Revenue Operations (MRevOps) function — including org structure, data infrastructure, pipeline ownership model, revenue attribution governance, operational cadence, and CMO-level accountability metrics — so marketing operates with the same revenue rigor as sales. Use this when your CMO is being asked to own a pipeline number, when marketing and sales disagree on attribution, when your board wants clearer marketing ROI, or when you're transitioning from marketing-as-cost-center to marketing-as-revenue-function.

## Quick Copy-Paste Version

You are a senior B2B SaaS GTM architect specializing in Marketing Revenue Operations. Design a complete MRevOps function for my company.

**My company:**
- Stage: [e.g., Series B, $15M ARR, scaling from $1M to $3M ARR/quarter in new logo]
- Sales motion: [e.g., sales-led with PLG free trial / pure enterprise sales-led / product-led growth]
- Average ACV: [e.g., $28,000]
- Current marketing team size: [e.g., 12 people, no dedicated marketing ops]
- Current RevOps owner: [e.g., RevOps team of 3 sitting under CRO / no RevOps function yet]
- CRM: [Salesforce / HubSpot]
- Marketing automation: [Marketo / HubSpot / Pardot]
- What's broken: [e.g., "Sales disputes every marketing pipeline number. Board asks for marketing ROI and we give them MQLs. CMO has no credible pipeline forecast."]

Build me:

1. **MRevOps Function Design** — Role definitions, hiring sequence, and reporting structure (should MRevOps sit under CMO, CRO, or standalone?)

2. **Marketing Revenue Data Model** — The 7 core data objects marketing must own in CRM (Lead, Contact, Account, Campaign, Opportunity, Attribution Touch, Marketing Activity) with field-level requirements for revenue accountability

3. **Pipeline Ownership Model** — Clear definition of what counts as "marketing-sourced" vs. "marketing-influenced" vs. "sales-sourced" pipeline, with rules that sales will actually accept and finance will approve for board reporting

4. **Marketing Revenue P&L** — A single-page marketing revenue statement showing: total marketing investment by channel → pipeline generated → pipeline converted to revenue → customer acquisition cost by source → payback period by cohort → LTV:CAC ratio by segment

5. **MRevOps Operating Cadence** — Weekly, monthly, and quarterly review rhythms with agenda templates and the 5 KPIs reviewed at each cadence level

6. **Attribution Governance Charter** — A written agreement between marketing, sales, and finance defining attribution methodology, dispute resolution process, and how pipeline credit is allocated when multiple channels touch a deal

Output as a complete MRevOps design document with implementation sequencing (what to build in weeks 1-4, months 2-3, and months 4-6).

## Advanced Customizable Version

[ROLE]
You are a B2B SaaS Marketing Revenue Operations architect with 18 years of experience building marketing-led revenue functions at companies including Salesforce, HubSpot, Marketo, Gainsight, and 60+ VC-backed growth-stage companies. You have designed MRevOps functions that helped CMOs move from "defending MQL counts" to "owning pipeline and revenue with the same credibility as the CRO." You specialize in the intersection of marketing operations, revenue operations, and finance — building the data models, process frameworks, and organizational structures that give marketing boards-level revenue accountability. You have led attribution model redesigns that increased marketing's recognized pipeline contribution by 40-80% without changing marketing spend, simply by fixing how contribution is measured and credited.

[CONTEXT]

**Company Revenue Profile:**
- Current ARR: [e.g., $18M]
- ARR growth target (next 12 months): [e.g., $36M — 2x growth]
- New logo ARR target: [e.g., $15M new logo / $3M expansion from marketing-sourced leads]
- Average ACV (new logo): [e.g., $32,000]
- Average ACV (expansion): [e.g., $18,000 incremental ARR per expansion]
- Average sales cycle (new logo): [e.g., 45 days SMB / 90 days mid-market / 180 days enterprise]
- Win rate (overall): [e.g., 22%]
- Win rate (marketing-sourced): [e.g., unknown — this is one of the problems]

**GTM Motion:**
- Primary sales motion: [Sales-led / PLG + sales-assist / Channel / Hybrid — describe your dominant motion]
- SDR model: [Inbound only / outbound only / blended]
- Marketing channels currently running: [e.g., paid search, LinkedIn ads, organic content, webinars, ABM direct mail, partner co-marketing]
- Number of active campaigns generating pipeline: [e.g., 12 campaigns running simultaneously]

**Current Marketing Operations State:**
- Marketing ops headcount: [e.g., 1 marketing ops manager + 1 contractor]
- RevOps headcount and reporting line: [e.g., 2 RevOps analysts reporting to VP Sales]
- Marketing automation platform: [Marketo / HubSpot / Pardot / Eloqua]
- CRM: [Salesforce / HubSpot CRM]
- Attribution tool: [Bizible/Marketo Measure / LeanData / HubSpot Attribution / None — using UTM parameters only]
- BI/analytics: [Tableau / Looker / Power BI / Salesforce dashboards only]
- Intent data: [Bombora / 6sense / G2 Buyer Intent / None]

**Revenue Attribution Current State:**
- Current attribution model used for board reporting: [e.g., First-touch only / Last-touch only / Linear multi-touch / No consistent model]
- Biggest attribution dispute with sales: [e.g., "Sales says they sourced deals that came through our ABM campaigns. We get credit for nothing."]
- Marketing pipeline metric currently used in board deck: [e.g., MQL volume / SAL volume / marketing-sourced pipeline $ / marketing-influenced pipeline $ / unknown]
- Finance's view of marketing ROI: [e.g., "Finance treats marketing as pure cost center. No linkage between marketing spend and revenue outcomes in their model."]

**Organizational Dynamics:**
- CMO tenure: [e.g., New CMO, 6 months in / Established CMO, 3 years]
- CMO's relationship with CRO: [e.g., Strong alignment / Active tension over pipeline attribution]
- CMO's relationship with CFO: [e.g., CFO skeptical of marketing ROI / CFO is an ally who wants better measurement]
- Does marketing currently own a pipeline number? [Yes, $X pipeline / No, only MQL targets]
- Sales team size: [e.g., 18 AEs + 8 SDRs]

[OBJECTIVE]

Produce a complete Marketing Revenue Operations (MRevOps) Architecture including all of the following sections:

---

**SECTION 1: MREVOPS ORGANIZATIONAL DESIGN**

Design the org structure for a formal MRevOps function:

*Role Architecture:*
- Define 3-5 roles needed for a fully functional MRevOps team (from startup with 1 person to scale-up with a full team)
- For each role: title, core responsibilities, key deliverables, required skills, and hiring priority (hire now / hire at $X ARR)
- Recommended reporting line with explicit rationale: Why MRevOps should report to CMO (vs. CRO vs. standalone VP RevOps) — include the political and operational argument for each option

*Hiring Sequence:*
- Phase 1 (Now, $10-25M ARR): What the first MRevOps hire must own — the single most important capability to establish
- Phase 2 ($25-50M ARR): How to expand the function as complexity grows
- Phase 3 ($50M+ ARR or pre-IPO): What a mature MRevOps function looks like with dedicated sub-teams

*Embedded vs. Centralized Model:*
- Evaluate whether MRevOps should be a centralized function or have dedicated resources embedded in each marketing channel team (e.g., demand gen ops, content ops, field marketing ops)
- Recommend one model for this company's stage with explicit rationale

---

**SECTION 2: MARKETING REVENUE DATA MODEL**

Define the authoritative data architecture marketing must control to produce credible revenue reporting:

*The 7 Core Marketing Data Objects in CRM:*

For each of the following, define: required fields, field ownership (marketing-owned vs. sales-owned vs. system-populated), data quality rules, and the revenue reporting use case it enables:

1. **Campaign Object** — How campaigns are structured in CRM so marketing spend can be tied to pipeline. Include required fields: Campaign Name taxonomy (Channel > Tactic > Asset > Date), Campaign Type, Budget, Actual Spend, Expected ROI, Campaign Owner, Start/End Date, and 5 custom fields for attribution

2. **Lead/Contact Object** — Fields required to track a prospect from first anonymous visit through MQL → SQL → Opportunity handoff. Include: Original Source, Original Source Detail, SFDC Lead Source, Marketing Qualified Date, SDR Accepted Date, Disqualification Reason, Re-engagement Date

3. **Opportunity Object** — Fields marketing must populate on every opportunity to enable attribution: Marketing Sourced (Y/N), Marketing Influenced (Y/N), First Marketing Touch Campaign, Most Recent Marketing Touch Campaign, Number of Marketing Touches (pre-opportunity), Content Assets Engaged, Webinars Attended, Marketing Investment Credited ($)

4. **Attribution Touch Object** — The custom object (or native Bizible record) that stores every marketing touchpoint: Touch Date, Touch Channel, Touch Campaign, Touch Asset, Touch Position (first/middle/last), Contact at Touch, Account at Touch, Deal Stage at Touch

5. **Marketing Activity Object** — Log of all marketing interactions: Email Opens/Clicks, Content Downloads, Webinar Attendances, Paid Ad Clicks, Website Page Views (key pages), Form Submissions, Chat Interactions — linked to Contact and Account for ABM scoring

6. **Account Engagement Score Object** — Composite account-level engagement score combining: individual contact activities, intent data signals, firmographic fit, and sales engagement — used to prioritize MQA (Marketing Qualified Accounts) for SDR follow-up

7. **Marketing P&L Object** — Custom reporting object that rolls up: Channel Spend → Pipeline Generated → Pipeline Converted → Influenced Revenue → CAC by Source → Payback Period by Cohort → LTV:CAC by Segment

*Data Quality Governance:*
- Define 5 data quality rules that must be enforced at the point of entry (e.g., "No opportunity can be created without a Campaign Source field populated")
- Define the weekly data quality audit process MRevOps runs to keep attribution data clean
- Identify the 3 most common data quality failures that corrupt marketing attribution and the system controls to prevent each

---

**SECTION 3: PIPELINE OWNERSHIP MODEL AND ATTRIBUTION GOVERNANCE**

Design an attribution model that marketing, sales, and finance will all accept:

*Pipeline Category Definitions (write these as board-ready, legally precise definitions):*

**Marketing-Sourced Pipeline (MS-Pipeline):**
- Definition: An opportunity is Marketing-Sourced if the first meaningful engagement that created the relationship was a marketing-owned touchpoint, AND marketing touched the account before any sales outreach was logged
- Counting rule: Credit the campaign that generated the first ICP-fit contact engagement OR the campaign that drove the account's first visit to a key conversion page (demo, pricing, trial)
- Dispute resolution: If sales logged a prospecting activity to the same account within 14 days of the first marketing touch, apply shared-source credit split (50/50 MS/SS)
- Board metric: "Marketing-Sourced Pipeline (MSP)" reported as total pipeline value of MSP opportunities created in the period

**Marketing-Influenced Pipeline (MI-Pipeline):**
- Definition: An opportunity is Marketing-Influenced if marketing touched ≥1 contact at the account ≥1 time during the 90 days preceding opportunity creation OR during the open sales cycle
- Counting rule: All pipeline where at least one marketing touchpoint exists in the attribution window
- Note: An opportunity can be both MS and MI; MS is a subset of MI
- Board metric: "Marketing-Influenced Pipeline (MIP)" — always larger than MSP; useful for demonstrating marketing's role in the full funnel

**Sales-Sourced Pipeline (SS-Pipeline):**
- Definition: All other pipeline — pure outbound cold prospecting with no prior marketing engagement, referrals from existing customers with no marketing campaign involvement, inbound from non-marketing sources (direct relationship, conference floor conversation)

*Attribution Model Selection:*
Present three attribution models with pros/cons and a recommendation for which to use for each reporting use case:

| Attribution Model | Best Used For | Weights | Advantages | Disadvantages |
|---|---|---|---|---|
| First-Touch | Understanding what created awareness / new logo acquisition | 100% to first touch | Simple, unambiguous | Ignores nurture and late-stage marketing |
| Last-Touch | Understanding what triggered conversion / closed deals | 100% to last touch | Simple, sales friendly | Ignores top-of-funnel marketing |
| W-Shaped (30/30/30/10) | Board-level pipeline attribution | 30% first touch, 30% MQL creation touch, 30% opportunity creation touch, 10% distributed to middle touches | Balances awareness and conversion | Requires multi-touch attribution tool |
| Data-Driven / Algorithmic | Optimizing budget allocation across channels | ML-derived weights based on historical conversion correlation | Most accurate, eliminates bias | Requires 12+ months of clean data, hard to explain to executives |

**Recommended implementation:**
- Board reporting: W-Shaped attribution for MS-Pipeline, First-Touch for new logo awareness reporting
- Budget optimization: Data-driven attribution (once 18+ months of clean data exist)
- Sales/marketing dispute resolution: First-Touch for sourcing credit; W-Shaped for influence credit

*Attribution Governance Charter:*
Draft the written charter between Marketing, Sales, and Finance that governs attribution. Include:

1. **Parties and authority**: Who signs the charter (CMO, CRO, CFO) and who owns dispute resolution (VP RevOps or dedicated Revenue Arbitration Committee)

2. **Definitions**: Verbatim definitions of MS-Pipeline, MI-Pipeline, SS-Pipeline, Marketing Touch, Attribution Window, Campaign Source

3. **Data entry obligations**: What marketing must log within 24 hours of a campaign launch; what sales must log within 24 hours of any account contact; what the system must auto-populate at form submission

4. **Dispute resolution process**: 3-step process (flag in CRM → automated data review → human review with 5-day SLA) for any opportunity where attribution is contested

5. **Review cadence**: Monthly attribution audit, quarterly attribution model review, annual methodology refresh (tied to board reporting cycle)

6. **Escalation path**: What happens when CMO and CRO disagree — who makes the final call (ideally CFO or CEO as neutral arbiter)

---

**SECTION 4: MARKETING REVENUE P&L**

Design a single-page Marketing Revenue P&L that gives the board a complete financial view of marketing's contribution:

*Marketing Revenue Income Statement Format:*

MARKETING REVENUE P&L — Q[X] [Year]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

MARKETING INVESTMENT
  Total Marketing Spend (excl. headcount)     $[X]
  Marketing Headcount Loaded Cost             $[X]
  Total Loaded Marketing Investment           $[X]
  ─────────────────────────────────────────
  Investment as % of Revenue                  [X]%
  (Benchmark: 8-15% revenue-stage SaaS)

PIPELINE GENERATED (This Quarter)
  Marketing-Sourced Pipeline (MS-Pipeline)   $[X]
  MS-Pipeline Coverage Ratio                  [X]x quarterly revenue target
  Pipeline-to-Investment Ratio               $[X] pipeline per $1 invested
  ─────────────────────────────────────────
  [Breakdown by channel: Paid Search / LinkedIn Ads / Content / Events / ABM / etc.]

PIPELINE CONVERTED (Deals Closed This Quarter from Marketing Sources)
  MS-Pipeline Won                            $[X] ARR
  MI-Pipeline Won (marketing influenced)     $[X] ARR
  MS Win Rate vs. Overall Win Rate           [X]% vs. [X]%
  MS Average Sales Cycle vs. Overall        [X] days vs. [X] days
  MS Average ACV vs. Overall                $[X] vs. $[X]
  ─────────────────────────────────────────
  Marketing-Sourced Revenue Contribution     [X]% of new logo ARR

UNIT ECONOMICS
  Blended CAC (new logo, marketing + sales)  $[X]
  Marketing-Sourced CAC (marketing-only)     $[X]
  ─────────────────────────────────────────
  CAC Payback Period (months)                [X] months
  LTV (using 3-year retention model)         $[X]
  LTV:CAC Ratio                              [X]x
  (Benchmark: >3x for healthy SaaS growth)

EFFICIENCY TRENDS (QoQ)
  Marketing-Sourced Pipeline vs. Q-1         +/-[X]%
  Marketing CAC vs. Q-1                      +/-[X]%
  MS Win Rate vs. Q-1                        +/-[X] pts
  Pipeline Coverage vs. Q-1                  +/-[X]x

FORWARD LOOK (Next Quarter Forecast)
  Expected MS-Pipeline in flight (open opps) $[X]
  Expected MS-Pipeline to create (campaigns) $[X]
  Total Expected MS-Pipeline Next Quarter    $[X]
  Gap to MS-Pipeline Target                  $[X] / [X]%
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

For each metric, define:
- Calculation formula (what goes in numerator/denominator)
- Data source (which CRM report/dashboard populates this)
- Benchmark range (what good looks like for Series B vs. Series D SaaS)
- Red/yellow/green threshold (when should a CMO escalate this metric to the board?)

---

**SECTION 5: MREVOPS OPERATING CADENCE**

Define the complete operational rhythm of MRevOps:

**Weekly MRevOps Pulse (45 minutes, Monday 9am):**
- Attendees: CMO, VP Demand Gen, MRevOps Lead, (optional) VP Sales
- The 5 metrics reviewed: (1) Pipeline created last week vs. target, (2) MQL volume and MQL-to-SQL conversion rate, (3) Pipeline velocity — average days in each funnel stage, (4) Channel budget pacing — spend vs. plan, (5) Top 3 at-risk campaigns (underperforming against pipeline target)
- Decision rights: MRevOps Lead has authority to pause any campaign spending <$10K/month if pipeline contribution is <50% of target for 2 consecutive weeks
- Output: Weekly pipeline flash report (1 page) shared to CMO + CRO by EOD Monday

**Monthly Marketing Revenue Review (90 minutes, first week of month):**
- Attendees: CMO, all marketing channel leads, MRevOps Lead, Finance Business Partner
- Agenda: (1) Prior month MS-Pipeline actuals vs. target (15 min), (2) Pipeline quality review — win rates, cycle length, ACV by source (20 min), (3) Channel ROI ranking — which channels are producing the best quality pipeline per dollar (20 min), (4) Budget reallocation decisions for current month (15 min), (5) Forward forecast: projected MS-Pipeline for next 30/60/90 days (20 min)
- Output: Marketing Revenue Dashboard update + 1-page executive summary to CMO for board prep

**Quarterly Business Review — Marketing Revenue (3 hours, week 2 of new quarter):**
- Attendees: CMO, CRO, CFO (30-min section), all marketing VPs, MRevOps Lead, Revenue Operations Lead
- Agenda: (1) Prior quarter Marketing P&L walkthrough vs. plan (45 min), (2) Attribution model audit — are the numbers we're claiming accurate? (30 min), (3) Win/loss analysis — what drove marketing-sourced wins and losses (30 min), (4) CFO section: marketing efficiency vs. board targets, CAC trend, payback period (30 min), (5) Next quarter pipeline forecast by channel with confidence intervals (45 min)
- Output: Quarterly Marketing Revenue Review deck (10 slides max) presented to board or CEO-staff

**Annual MRevOps Planning Session (2 days, Q4):**
- Attendees: CMO + direct reports + MRevOps Lead + Finance
- Year 1 deliverables: Annual pipeline capacity plan (how much pipeline does each channel need to generate to hit ARR targets), Headcount model, Tech stack budget, Attribution methodology refresh
- Output: Annual Marketing Revenue Plan submitted alongside CFO's operating plan

---

**SECTION 6: MREVOPS TECHNOLOGY STACK**

Specify the minimum viable tech stack for MRevOps at each company stage:

**Stage 1: $5M-$20M ARR (MRevOps team of 1)**
- CRM: Salesforce or HubSpot (already have)
- Marketing Automation: Marketo or HubSpot (already have)
- Attribution (MVP): HubSpot multi-touch attribution OR Salesforce Pardot B2B MA with campaign reporting — use native tools first before buying dedicated attribution
- Reporting: Salesforce dashboards or HubSpot reporting + Google Sheets marketing P&L model
- Intent data: Not required at this stage; focus on first-party behavioral data
- **Total incremental MRevOps tech investment: $0-$500/month** (use what you have)

**Stage 2: $20M-$50M ARR (MRevOps team of 2-3)**
- Attribution: Bizible/Marketo Measure ($2,500-$4,000/month) OR LeanData for routing + attribution
- BI: Tableau or Looker connected to Salesforce (if data volume justifies; otherwise continue with SFDC dashboards)
- Intent data: Bombora ($2,000-$4,000/month) or G2 Buyer Intent for high-ACV products
- Data enrichment: Clearbit or Apollo for lead enrichment at point of conversion
- Pipeline intelligence: Clari or Gong for pipeline visibility and forecast accuracy
- **Total incremental MRevOps tech investment: $5,000-$12,000/month**

**Stage 3: $50M+ ARR or Pre-IPO (MRevOps team of 4-6)**
- Attribution: Bizible/Marketo Measure + custom data-driven model built on Snowflake
- Data warehouse: Snowflake or Databricks as single source of truth for marketing data
- BI: Looker or Tableau with Marketing Revenue P&L as certified data model
- Intent data: 6sense or Bombora enterprise
- Revenue intelligence: Clari enterprise + Gong for call/deal intelligence
- Reverse ETL: Census or Hightouch to sync warehouse segments back to MAP and CRM
- **Total incremental MRevOps tech investment: $20,000-$50,000/month**

---

**SECTION 7: MREVOPS IMPLEMENTATION ROADMAP**

Sequence the build in achievable phases:

**Weeks 1-4: Foundation (The Must-Do-Now List)**
- [ ] Audit current CRM data quality: % of opportunities with Campaign Source populated; % of campaigns with budget loaded; % of contacts with Original Source populated — set baseline
- [ ] Define and document the Pipeline Ownership Model (MS vs. MI vs. SS) and get CMO + CRO written sign-off
- [ ] Implement mandatory Campaign Source field on all new opportunities — SDRs cannot create an opportunity without selecting a source
- [ ] Create the first Marketing Revenue Dashboard in CRM: 5 metrics, weekly refresh, shared to CMO + CRO by Monday 9am
- [ ] Draft the Attribution Governance Charter and schedule the first cross-functional review

**Months 2-3: Measurement Infrastructure**
- [ ] Implement or configure multi-touch attribution — either native (HubSpot/SFDC) or Bizible if budget allows
- [ ] Build the Marketing Revenue P&L model in Google Sheets or Tableau — connect to CRM export for weekly refresh
- [ ] Launch the Weekly MRevOps Pulse meeting and Monthly Marketing Revenue Review cadence
- [ ] Create the first Marketing CAC analysis by channel using prior 12 months of data
- [ ] Complete the first formal Attribution Audit to validate that attribution data is clean and credible

**Months 4-6: Optimization and Governance**
- [ ] Run the first Quarterly Business Review using the new Marketing P&L format — include CFO in 30-minute segment
- [ ] Build the forward pipeline forecast model: project next quarter's MS-Pipeline by channel using historical conversion rates + current campaign activity
- [ ] Implement the Attribution Governance Charter as a living document with quarterly review
- [ ] Hire MRevOps role #2 if not already done — first hire should now own data quality; second hire owns reporting and forecasting
- [ ] Present the Marketing Revenue P&L to the board for the first time — replace MQL slide with pipeline and revenue slide

[CONSTRAINTS]
- All metrics and definitions must survive a CFO audit — no marketing-friendly definitions that don't hold up under scrutiny
- Attribution model must be explainable in one sentence to a skeptical CRO: "Marketing gets credit for X when Y happens"
- Data model must be implementable without a custom data engineering team — use native CRM capabilities first
- Operating cadence must respect the fact that marketing leaders are already in too many meetings — maximum 3 recurring MRevOps meetings, each with a hard agenda and decision-forcing close
- Implementation roadmap must produce visible results within 90 days, before the next board meeting

[OUTPUT FORMAT]
Produce the complete MRevOps Architecture as a formatted document with:
- Clear section headers matching the 7 sections above
- Tables where comparison or scoring is involved
- Bullet lists for requirements and checklists
- Template copy (in quotation marks or code blocks) for any written artifacts (charter, P&L, dashboard)
- Explicit "hire/don't hire yet" recommendations for each role based on ARR stage
- A 1-page executive summary at the end formatted as a CMO memo to the CEO explaining why MRevOps is needed and what it will produce in 12 months

## Example Input/Output

**Input Example:**

Company: Pragma Analytics — B2B SaaS revenue intelligence platform
Stage: Series B, $22M ARR, targeting $45M next year
ACV: $48,000
Sales motion: Sales-led with SDR team (6 inbound SDRs, 4 outbound SDRs)
Marketing team: 14 people, 1 marketing ops person
RevOps: 2 RevOps analysts reporting to VP Sales (CRO)
CRM: Salesforce
Marketing automation: Marketo
Attribution: UTM parameters only, no multi-touch attribution
Current problem: "CMO owns an MQL target of 400/quarter. Sales says 60% of our MQLs are junk. Finance says marketing spend increased 40% but pipeline only grew 15%. CRO gets the pipeline credit for deals that marketing clearly sourced through ABM campaigns."

**Output Example (abbreviated):**

*MRevOps Design for Pragma Analytics:*

**Immediate hire (Week 1): Senior Marketing Revenue Operations Manager**
- Salary: $130-155K + equity
- First 90-day deliverables: (1) Campaign Source data quality remediation in Salesforce — mandate 100% population on all open opportunities, (2) Pipeline ownership model documented and signed by CMO + CRO, (3) First Marketing Revenue Dashboard live in SFDC, (4) Bizible evaluation and implementation kickoff

**Pipeline Ownership Decision (to resolve CMO/CRO dispute):**
"At Pragma, any account where marketing logged a Campaign Touch before the SDR's first outbound activity is Marketing-Sourced. Given 6 inbound SDRs, this likely reclassifies 35-50% of 'sales-sourced' pipeline as 'marketing-sourced.' This single definition change — properly implemented in Salesforce — will show the board that marketing's contribution has been systematically undercounted."

**Month 1 Marketing Revenue P&L Baseline:**
- Total marketing investment: $1.2M/quarter
- Current MS-Pipeline (estimated, first-touch): $4.8M
- Implied pipeline per dollar invested: $4.00
- Industry benchmark for Series B SaaS: $5.00-$8.00 per dollar
- Gap: Pragma is underperforming on marketing efficiency OR undercounting marketing's pipeline contribution — MRevOps will determine which

**Attribution Model Recommendation:**
"Implement W-Shaped attribution in Bizible ($3,200/month). This will likely show that Pragma's ABM campaigns are touching 70%+ of all closed-won deals, giving the CMO a credible 'marketing-influenced pipeline' number that should run 4-6x the marketing-sourced number. Use this for the next board deck while the CMO builds the case for W-Shaped as the primary attribution model."

## Success Metrics

- Marketing-Sourced Pipeline accurately captured in CRM within 90 days of implementing MRevOps data model (target: 90%+ opportunity field population rate)
- CMO presents a Marketing Revenue P&L (not an MQL dashboard) at the next board meeting
- Attribution dispute rate between marketing and sales decreases below 5% of opportunities per quarter (from baseline of 20-40% at most companies)
- Marketing CAC by channel is calculated and agreed upon by CMO, CRO, and CFO within 6 months
- Board asks "what is marketing's pipeline contribution?" — CMO answers in dollars, not MQLs
- LTV:CAC ratio is above 3x for marketing-sourced customers (benchmark for efficient growth-stage SaaS)
- Forward pipeline forecast accuracy: MRevOps pipeline forecast for next quarter is within ±15% of actual MS-Pipeline created

## Related Prompts

- [CMO Pipeline Gap Diagnosis & Revenue Sprint](../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-B2B-CMO-Pipeline-Gap-Diagnosis-&-Revenue-Sprint-Marketing-Intelligence-Engine.md)
- [CMO-CRO Revenue Partnership Architecture](../../01_CMO-&-Leadership/Strategy-&-Planning/AI-Powered-B2B-SaaS-CMO-CRO-Revenue-Partnership-Architecture-&-Unified-GTM-Leadership-Intelligence-Engine.md)
- [Marketing Attribution Audit & Revenue Proof](../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-B2B-Marketing-Attribution-Audit-&-Revenue-Proof-of-Contribution-Intelligence-Engine.md)
- [Marketing-Sales Pipeline Attribution Governance](../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-B2B-SaaS-Marketing-Sales-Pipeline-Attribution-Governance-&-Revenue-Credit-Consensus-Intelligence-Engine.md)

## Integration Tips

**Salesforce integration:**
- Create a custom Marketing Revenue Operations dashboard in SFDC with 5 reports: MS-Pipeline Created (week/month/quarter), Campaign ROI by Channel, MQL-to-SQL conversion rate by source, Marketing CAC by channel (requires custom formula field), Attribution dispute log (custom object to track contested opportunities)
- Use Salesforce Flow to auto-populate Campaign Source on opportunity creation based on Contact's most recent campaign membership — reduces manual data entry by 80%

**HubSpot integration:**
- Enable HubSpot's native multi-touch revenue attribution in reporting (Settings > Account Defaults > Revenue Attribution) — gives W-shaped attribution without Bizible cost at early stage
- Use HubSpot Campaigns tool to log all campaign spend, set ROI goals, and track pipeline contribution per campaign — creates the foundation of the Marketing P&L

**Google Sheets / Looker Studio (free reporting stack):**
- Build the Marketing Revenue P&L in Google Sheets with a weekly data export from Salesforce — functional MRevOps reporting without a BI tool budget until $30M+ ARR
- Use Looker Studio (free) connected to the Google Sheet to create shareable CMO dashboards that update on the CRM export schedule

**Marketo/HubSpot automation:**
- Set up a Marketo program hierarchy (Channel > Sub-Channel > Tactic > Asset) that maps 1:1 to the Salesforce Campaign hierarchy — this is the prerequisite for any accurate multi-touch attribution
- Create a Marketo Revenue Cycle Model to track lead stage transitions and marketing's contribution to each stage conversion — essential for showing marketing's impact beyond MQL generation

**Notion / Confluence:**
- Store the Attribution Governance Charter, Pipeline Ownership Model definitions, and MRevOps operating cadence in a single Notion page accessible to marketing, sales, and finance — call it "The Revenue Rules of Engagement"

## Troubleshooting

**Problem: Sales refuses to accept the Marketing-Sourced Pipeline definition and disputes 30-40% of opportunities.**
Solution: This is a political problem masquerading as a data problem. Do not solve it with more data. Instead: (1) Schedule a 2-hour workshop with CMO, CRO, and CFO to define "Marketing-Sourced" together — the definition that comes out of this room is the one that sticks; (2) Frame it as "the board needs a consistent, auditable definition" — finance neutrality breaks the CMO/CRO stalemate; (3) Accept that the first definition will favor sales (conservative marketing credit) — this builds trust and gives you room to expand credit over time as the model proves accurate.

**Problem: CRM data is too dirty to produce credible attribution — Campaign Source field is blank on 60%+ of opportunities.**
Solution: Declare a "Pipeline Data Amnesty" — stop trying to fix historical data (it's not worth the effort) and start clean from a specific date. (1) Mandate that all opportunities created from [specific date] must have Campaign Source populated — make it a required field in SFDC; (2) Have SDRs/AEs do a 2-week remediation sprint on the most recent 6 months of open pipeline; (3) Accept that your first 3 months of MRevOps reporting will be based on incomplete data and communicate this explicitly to leadership — imperfect data honestly reported is far better than perfect data no one believes.

**Problem: CMO doesn't want to own a pipeline number because marketing can't control what sales does with the leads.**
Solution: This is the right instinct but the wrong conclusion. Solve it by owning the right metric: (1) CMO should own "Marketing-Qualified Pipeline Created" — the dollar value of pipeline created from marketing-sourced opportunities — not "Marketing-Sourced Pipeline Won" (which depends on sales); (2) Separately track MS-Pipeline win rate to show whether the pipeline marketing creates is high quality; (3) Own marketing's contribution metric but make sales accountable for converting it — this gives CMO ownership with appropriate control scope.

## Version History
- v1.0: Initial creation (auto-generated)
