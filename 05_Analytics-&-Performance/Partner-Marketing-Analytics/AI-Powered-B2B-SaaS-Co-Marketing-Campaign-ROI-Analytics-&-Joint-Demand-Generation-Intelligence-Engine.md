# AI-Powered B2B SaaS Co-Marketing Campaign ROI Analytics & Joint Demand Generation Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** partner-analytics, co-marketing, joint-demand-generation, mdf-roi, partner-mql, campaign-analytics, channel-marketing, b2b-saas, revenue-operations, partner-enablement

## Overview

This engine equips B2B SaaS partner marketing and revenue operations teams to systematically measure, compare, and optimize joint demand generation campaigns run in partnership with technology partners, channel resellers, and strategic alliance partners. Use it when you need to move beyond activity-based co-marketing reporting ("we ran 6 webinars with partners") to revenue-connected analytics that answer the questions CFOs and CROs actually care about: which partner marketing investments generate qualified pipeline, how does co-generated MQL quality compare to direct demand gen, and how should the co-marketing budget be reallocated next quarter to maximize partner-sourced ARR.

## Quick Copy-Paste Version

You are a B2B SaaS partner marketing analytics expert. I need a complete framework to measure and optimize the ROI of our co-marketing campaigns with partners.

Company context:
- Company: [Company Name]
- Product: [e.g., "Revenue intelligence platform for mid-market B2B sales teams"]
- Partner types running co-marketing: [e.g., "15 technology integration partners, 8 channel resellers, 3 strategic alliance partners"]
- Co-marketing activities: [e.g., "Co-branded webinars, joint content (ebooks/reports), partner-sponsored field events, email list swaps, joint ABM campaigns"]
- Annual co-marketing budget: [e.g., "$600K MDF/co-marketing funds — $350K partner-initiated, $250K company-initiated"]
- Current measurement: [e.g., "We track registrations and MQLs per webinar but have no consistent way to compare partner campaign ROI across activity types or attribute partner-generated pipeline downstream"]

Build me a complete co-marketing campaign ROI analytics framework covering:

1. CO-MARKETING CAMPAIGN TAXONOMY & MEASUREMENT ARCHITECTURE
   Define a standardized measurement framework for each campaign type: co-branded webinars, joint content/gated assets, partner field events, email database swaps, and joint ABM campaigns. For each type, specify: primary KPIs, data capture requirements, attribution methodology, and benchmark targets.

2. PARTNER MQL QUALITY SCORING
   Build a Partner MQL Quality Score (0-100) that evaluates co-generated leads against: ICP fit, engagement depth, pipeline conversion rate, and sales cycle impact. Compare partner MQL quality by partner, by campaign type, and against direct demand gen MQL benchmarks.

3. CO-MARKETING CAMPAIGN ROI CALCULATION
   Design a unified ROI formula for all co-marketing activities that accounts for: MDF investment, internal labor costs, pipeline generated (with partner attribution), and closed-won revenue from each campaign. Include cost-per-partner-MQL, cost-per-partner-opportunity, and partner-campaign pipeline-to-close rate metrics.

4. PARTNER DEMAND GEN CONTRIBUTION DASHBOARD
   Specify the weekly/monthly reporting dashboard structure that shows each partner's co-marketing contribution: campaigns run, MQLs generated, pipeline created, deals closed, and MDF ROI — with trend lines and tier benchmarks.

5. CO-MARKETING BUDGET ALLOCATION OPTIMIZATION
   Provide a data-driven framework for reallocating co-marketing budget quarterly based on partner performance, campaign type ROI, and pipeline opportunity — including a prioritization matrix for next quarter's co-marketing investments.

Output: Complete analytics framework with metric definitions, scoring algorithms, dashboard specs, and a 90-day implementation roadmap.

## Advanced Customizable Version

ROLE: You are a senior revenue operations architect and partner marketing analytics specialist who has built co-marketing measurement infrastructure for 12+ B2B SaaS companies at Series B through pre-IPO stages. You specialize in connecting joint demand generation activity to downstream revenue outcomes with the attribution rigor that satisfies both partner managers wanting credit and CFOs demanding provable ROI.

CONTEXT:
Company: [Company Name]
Product category: [e.g., "AI-powered contract lifecycle management platform for enterprise legal and procurement teams"]
ARR stage: [e.g., "$38M ARR, 70% YoY growth, targeting $65M ARR this fiscal year"]
Partner ecosystem composition:
- Technology integration partners running co-marketing: [e.g., "8 active — Salesforce, DocuSign, NetSuite, SAP, Ironclad, Coupa, Workday, ServiceNow — varying co-marketing commitment levels"]
- Channel/reseller partners running co-marketing: [e.g., "6 active — 2 Platinum (Deloitte, PwC), 3 Gold (regional VARs), 1 Silver"]
- Strategic alliance partners: [e.g., "2 active — one hyperscaler co-sell partner (AWS Marketplace), one consulting firm white-label arrangement"]
Annual co-marketing investment: [e.g., "$780K total — $480K MDF issued to partners, $300K company-funded joint campaigns"]
Campaign volume: [e.g., "~45 co-marketing campaigns per year — 18 webinars, 9 joint content pieces, 8 field events, 6 email database collaborations, 4 joint ABM campaigns"]
Current MarTech stack: [e.g., "Salesforce CRM + HubSpot MAP + PartnerStack (referral tracking) + Crossbeam (account mapping/overlap) + Splash (event management) + ON24 (webinars) + Looker (BI/dashboards)"]
Current measurement gaps: [e.g., "1) MDF is allocated based on partner tier, not campaign performance data. 2) We issue MDF but can't prove which partner investments generated pipeline vs. just activity. 3) Partner webinar MQLs look worse than direct webinar MQLs in our scoring, but we suspect that's because partner leads are earlier-stage prospects we wouldn't otherwise reach. 4) Sales team disputes whether partner-generated leads need different nurture sequences."]

OBJECTIVE: Build a production-ready co-marketing campaign analytics architecture that:
1. Standardizes measurement across all co-marketing campaign types with comparable ROI metrics
2. Evaluates partner MQL quality in context (pipeline conversion, not just scoring thresholds)
3. Connects MDF investment to closed-won revenue with defensible attribution
4. Produces a monthly co-marketing performance report that drives MDF reallocation decisions
5. Gives partner managers the data they need to have ROI conversations with partner contacts

FRAMEWORK ARCHITECTURE:

PHASE 1 — CO-MARKETING CAMPAIGN MEASUREMENT FOUNDATION (Days 1-30)

A. Campaign Taxonomy & Standardized Tracking Architecture

Define five campaign archetypes with standardized measurement for each:

ARCHETYPE 1: CO-BRANDED WEBINAR
Definition: Joint live or on-demand webinar where both companies promote to their respective audiences and co-present content. Can be partner-led (partner is primary host, your company is featured) or company-led (your company hosts, partner is featured guest/sponsor).

Primary KPIs:
- Registration rate by list source (partner list vs. your house list vs. paid promotion)
- Show rate by registration source
- Engagement score (questions asked, polls completed, resources downloaded, time watched)
- MQL conversion rate within 48 hours post-event
- Pipeline created within 60 days from attendee list
- Partner list registrant-to-pipeline conversion rate vs. house list conversion rate

Data capture requirements:
- UTM parameters: utm_source=partner_[partner_slug] / utm_medium=co-webinar / utm_campaign=[campaign_name]_[YYYYQQ]
- Registration form fields: company, title, intent question ("What is your primary challenge with [use case]?")
- ON24/webinar platform: engagement score export by registrant
- HubSpot: "Co-Marketing Campaign" field on Contact, "Partner Webinar Attendee" workflow trigger
- Salesforce: Campaign object with partner attribution field + Campaign Member status tracking

Benchmark targets (calibrate against your historical data):
- Show rate: 40-55% for co-branded vs. 35-50% for house list-only webinars
- MQL conversion (within 48 hours): 15-30% depending on topic specificity
- Pipeline creation (60 days): 5-12% of attendee list should create opportunities
- Cost-per-attendee target: $35-80 for MDF-funded webinars at your stage

ARCHETYPE 2: JOINT GATED CONTENT (EBOOK / RESEARCH REPORT / GUIDE)
Definition: Co-authored and co-branded content asset where both companies contribute expertise, share promotion responsibility, and jointly capture leads via a shared or separately-gated landing page.

Primary KPIs:
- Total downloads by promotion source (partner email, your email, paid syndication, organic)
- Lead quality score by acquisition source
- MQL conversion rate by source within 30 days
- Pipeline influence rate (percentage of content leads who appear in an opportunity within 90 days)
- Asset longevity: download velocity decay curve over 90 days post-launch

Data capture requirements:
- Separate landing pages per promotion source with distinct UTMs, or a shared LP with hidden field capturing lead source
- Progressive profiling if using your MAP: don't re-ask fields already known for house list contacts
- Partner-captured leads: define data sharing protocol upfront — who receives the full lead list, what data fields are shared, CAN-SPAM/GDPR consent language that covers both companies
- Content syndication: if co-promoting via third-party content networks, track separately as "co-syndication" budget line

Benchmark targets:
- Download-to-MQL: 8-20% (joint reports with original data perform at upper end)
- 90-day pipeline influence: 3-8% of download list
- Partner list contribution: partners should contribute ≥30% of total downloads to justify MDF

ARCHETYPE 3: JOINT FIELD EVENT / DINNER / ROUNDTABLE
Definition: In-person event co-funded and co-hosted with one or more partners, targeting specific account lists with executive-level programming.

Primary KPIs:
- Target account coverage: % of attendees from your Tier 1/Tier 2 target account list
- Executive attendance rate: % of attendees who are VP+ or economic buyer title
- Meeting-to-pipeline conversion: % of attendee accounts that create or advance opportunities within 30 days
- Cost-per-attendee vs. cost-per-opportunity created
- Partner account overlap: % of attendees who are also active in partner's pipeline (measure with Crossbeam)

Data capture requirements:
- Splash (or event platform): capture full attendee record with title, company, arrival/departure time
- Post-event survey (24-hour send): one question — "What is your most pressing challenge with [use case] in the next 6 months?"
- Salesforce: create Campaign, add all attendees as Campaign Members, set status to "Attended"
- Follow-up task auto-created for owning AE/SDR within 2 hours of event end

Benchmark targets:
- Target account representation: ≥60% of attendees from named account list
- 30-day meeting booking rate from attendees: 25-40% for exec dinners; 15-25% for larger events
- 60-day pipeline creation from attendee list: 8-15%

ARCHETYPE 4: EMAIL DATABASE COLLABORATION
Definition: Partner promotes your content/offer to their email list, and/or you promote their content/offer to yours. No lead list sharing — traffic is directed to landing pages controlled by each company individually.

Primary KPIs:
- Partner list send size and deliverability (open rate, click rate)
- Landing page conversion rate from partner traffic vs. benchmark
- Cost-per-click and cost-per-lead from partner promotion
- Lead quality: MQL conversion rate from partner-driven leads
- Reciprocal value: if you're promoting partner content, what is your list's conversion rate to their LP?

Data capture requirements:
- Partner-specific UTM parameters on all inbound links from partner email
- Separate landing page variant (or UTM-tracked variant) to isolate partner email traffic
- Partner provides send metrics: list size sent, open rate, click rate — for mutual reporting

Benchmark targets:
- Partner email click-to-lead conversion: 15-35% (varies significantly by offer quality and list relevance)
- Partner-driven MQL rate: typically 5-15 percentage points below house list MQL rate (list is colder; this is expected and acceptable)

ARCHETYPE 5: JOINT ABM CAMPAIGN
Definition: Coordinated, account-specific marketing campaign targeting a shared set of named accounts with personalized multi-channel outreach — ads, content, outbound, event invites — orchestrated jointly with one or more partners.

Primary KPIs:
- Target account engagement rate: % of named accounts showing ≥2 tracked touchpoints within campaign window
- Account progression: % of target accounts that advance pipeline stage during campaign
- Partner touchpoint attribution: which partner activities correlate with account engagement acceleration
- Crossbeam overlap utilization: % of campaign accounts that appear in partner's pipeline (measure pre- and post-campaign)
- Net-new opportunities created from previously-cold target accounts

Data capture requirements:
- Crossbeam: configure account overlap sharing with partner before campaign launch; measure overlap % pre-campaign
- 6sense/Bombora/G2 intent data: pull intent signal baseline for all target accounts pre-campaign; measure lift during campaign
- Salesforce: tag all campaign accounts with "ABM Campaign Name" field; track stage progression throughout campaign window
- LinkedIn Campaign Manager: use Matched Audience lists targeting employees at named accounts; separate campaigns for partner-co-branded creative vs. direct creative

Benchmark targets:
- Target account engagement: ≥40% of named accounts show ≥2 touchpoints within 90-day campaign window
- Pipeline creation: 10-20% of target accounts generate new or advanced opportunities
- Crossbeam-identified accounts (already in partner pipeline) should show ≥2× pipeline progression rate vs. non-overlap accounts

PHASE 2 — PARTNER MQL QUALITY SCORING & BENCHMARK COMPARISON (Days 30-60)

A. Partner MQL Quality Score (PMQS) Architecture

Design a 100-point composite score that evaluates every co-generated lead across four dimensions and produces a comparable quality signal regardless of campaign type or partner:

ICP Fit (30 points):
- Company size match to ICP: 0-10 points
  • Exact ICP employee range: 10 pts
  • Adjacent range (within 50% of ICP target): 6 pts
  • Outside ICP range: 2 pts
- Industry vertical match: 0-10 points
  • Top 3 target verticals: 10 pts
  • Secondary verticals: 6 pts
  • Low-priority verticals: 2 pts
- Buyer title match: 0-10 points
  • Economic buyer / VP+ with budget ownership: 10 pts
  • Technical evaluator / manager-level: 6 pts
  • Practitioner / end-user: 2 pts

Engagement Depth (25 points):
- Campaign engagement actions taken: 0-15 points
  • 3+ engagement actions (attended + asked question + downloaded resource): 15 pts
  • 2 engagement actions: 10 pts
  • 1 engagement action: 5 pts
- Time investment signals: 0-10 points
  • Webinar: stayed ≥75% of session: 10 pts
  • Content: spent ≥3 minutes on LP post-download: 5 pts
  • Event: stayed through dinner/full session: 8 pts

Behavioral Signals (25 points):
- Follow-up email open + click within 72 hours: 0-10 points
  • Opens + clicks follow-up within 48 hours: 10 pts
  • Opens only: 5 pts
  • No opens: 0 pts
- Website sessions after event (within 14 days): 0-10 points
  • ≥3 website sessions, including pricing or demo page: 10 pts
  • 1-2 sessions on product pages: 5 pts
  • No website activity: 0 pts
- Intent data signal at time of lead capture: 0-5 points
  • High intent on your category (6sense/Bombora): 5 pts
  • Medium intent: 2 pts
  • No signal: 0 pts

Pipeline & Sales Conversion (20 points — calculated retrospectively at 90 days):
Note: This dimension is scored at 90 days post-capture and used to recalibrate scoring model quarterly.
- Converted to SQL within 30 days: 20 pts
- Engaged in sales discovery (not yet SQL): 10 pts
- Enrolled in nurture sequence (active): 5 pts
- No engagement or unsubscribed: 0 pts

PMQS Interpretation:
- 80-100: Partner Champion Lead — fast-track to SDR outreach within 24 hours
- 60-79: Partner Qualified Lead — SLA: SDR contact within 48 hours; enroll in accelerated nurture
- 40-59: Partner Aware Lead — enroll in partner co-branded nurture sequence; SDR outreach at day 7
- Below 40: Long-nurture lead — content-only nurture; re-score at 60-day engagement gate

B. Benchmark Comparison: Partner-Generated vs. Direct Demand Gen

Build a monthly comparison dashboard that shows the following for each lead source:

Metric | Partner Co-Marketing | Direct Demand Gen | Delta | Trend
Average PMQS at capture | [data] | [data] | [data] | ↑/↓
SQL conversion rate (30 days) | [data] | [data] | [data] | ↑/↓
Pipeline creation rate (60 days) | [data] | [data] | [data] | ↑/↓
Average ACV of pipeline created | [data] | [data] | [data] | ↑/↓
Sales cycle length | [data] | [data] | [data] | ↑/↓
Win rate (closed-won vs. lost) | [data] | [data] | [data] | ↑/↓
Cost per MQL | [data] | [data] | [data] | ↑/↓
Cost per opportunity | [data] | [data] | [data] | ↑/↓

Critical interpretation rule: Partner-generated leads frequently score lower on initial PMQS (because partner lists are colder and less familiar with your solution) but may show superior pipeline conversion and ACV if the partner relationship creates buying trust. Do NOT disqualify co-marketing investments based solely on PMQS at capture — pipeline conversion and ACV are the decisive metrics.

PHASE 3 — MDF ROI CALCULATION & PARTNER CAMPAIGN SCORING (Days 45-75)

A. Standardized Co-Marketing Campaign ROI Formula

For every co-marketing campaign, calculate:

Gross Campaign Investment:
- MDF disbursed to partner: $[amount]
- Your company's in-kind contribution: $[production costs + labor]
  • Content production: designer hours × hourly rate
  • Program management: PM hours × hourly rate
  • Technical setup (landing pages, workflows): $[cost]
- Paid promotion budget (if applicable): $[amount]
Total Gross Investment = Sum of all above

Campaign Revenue Attribution:
Step 1 — Pipeline Created: Sum all Opportunity Amount for opportunities where Campaign Member status = "Responded" AND Opportunity Create Date is within 90 days of campaign date
Step 2 — Apply Time-to-Close Probability: Pipeline Created × (historical win rate for partner-sourced opportunities)
Step 3 — Closed-Won from Campaign: At 12 months, pull actual closed-won from campaign-attributed opportunities

Campaign ROI Metrics:
- Cost per MQL = Total Gross Investment ÷ Campaign MQLs Generated
- Cost per Opportunity Created = Total Gross Investment ÷ Opportunities Created (90-day window)
- Pipeline ROI Ratio = Pipeline Created ÷ Total Gross Investment (target: ≥5× for webinars; ≥8× for field events)
- Realized Revenue ROI = Closed-Won Revenue (12M) ÷ Total Gross Investment (target: ≥2.5× at 12 months)
- Partner Contribution % = Partner-promoted MQLs ÷ Total Campaign MQLs (benchmark: ≥35% for true co-marketing; <20% suggests you're funding a campaign the partner isn't promoting)

B. Partner Campaign Performance Scorecard

Score each partner's co-marketing performance quarterly using this framework:

Campaign Execution Quality (30 points):
- Partner met promotional commitments (email sends, social posts, sales team activation): 0-15 points
- Campaign assets delivered on schedule: 0-10 points
- Lead data delivered per agreed format and SLA: 0-5 points

Demand Generation Output (40 points):
- MQLs generated from partner list as % of total campaign MQLs (target: ≥35%): 0-20 points
- Partner MQL quality (average PMQS from partner-sourced leads vs. benchmark): 0-20 points

Revenue Impact (30 points):
- Pipeline created from partner-attributed leads: 0-15 points (scored against tier-specific pipeline target)
- Closed-won revenue from partner co-marketing campaigns (trailing 12 months): 0-15 points

Score interpretation:
85-100: Tier 1 co-marketing partner — increase MDF allocation; invite to co-develop flagship joint campaign
65-84: Productive partner — maintain investment; work with partner manager to improve one underperforming dimension
45-64: Developing partner — conditional MDF for next quarter contingent on commitment fulfillment improvement
Below 45: On probation — require revised co-marketing plan with specific commitments before renewing MDF

PHASE 4 — CO-MARKETING PERFORMANCE DASHBOARD SPECIFICATION (Days 60-90)

A. Dashboard Architecture (Looker / Salesforce Analytics / Tableau)

Dashboard 1: Co-Marketing Executive Summary (monthly, for CMO/VP Marketing/Head of Partnerships)

Section 1 — Co-Marketing Contribution to Pipeline (current quarter):
- Co-marketing MQLs generated: [#] vs. quarterly target [#]
- Pipeline created from co-marketing: [$] vs. quarterly target [$]
- Co-marketing as % of total marketing-sourced pipeline: [%]
- Top 3 performing campaigns by pipeline created: [campaign name | partner | pipeline $]

Section 2 — MDF Efficiency:
- Total MDF disbursed YTD: [$]
- Pipeline generated per $1 of MDF invested: [$]
- Average cost per co-marketing MQL: [$]
- Partners where MDF investment is generating negative ROI (pipeline < 3× MDF invested): [list]

Section 3 — Partner Co-Marketing Leaderboard (quarter-to-date):
| Partner | Campaign MQLs | Avg PMQS | Pipeline Created | MDF Invested | Pipeline ROI |
| [name] | [#] | [score] | [$] | [$] | [ratio] |

Dashboard 2: Campaign-Level Analytics (weekly, for partner marketing team)

For each active campaign in the trailing 90 days:
- Campaign name, type, partner, launch date
- Registration/attendance/download metrics
- MQL count and average PMQS
- SQL conversion rate (at 30 days)
- Pipeline created (at 60 days)
- Gross investment vs. pipeline ROI ratio
- Status: ✅ Above target / ⚠️ At target / 🔴 Below target

Dashboard 3: Partner MQL Quality Comparison (monthly, for demand gen + RevOps)

Side-by-side comparison of lead quality metrics by source:
- Partner co-marketing vs. direct webinars vs. direct content vs. paid media
- PMQS distribution histogram by source
- SQL conversion rate by source (30-day cohort)
- ACV distribution by source
- Win rate by source
- Conclusion: which lead sources produce the best downstream revenue outcomes

B. Data Infrastructure Requirements

Salesforce:
- Campaign object: add fields for "Co-Marketing Partner" (lookup to Account), "MDF Amount Invested" (currency), "Partner Contribution %" (formula), "Co-Marketing Campaign Type" (picklist using five archetypes above)
- Campaign Member: add "Lead Source Granular" (picklist: Partner List, Company List, Paid Promotion, Organic, Partner SDR Outreach) to distinguish within co-marketing leads
- Contact/Lead: "Co-Marketing Campaign Attribution" (lookup to Campaign, populated by first-touch UTM match) and "Partner MQL Score" (number, updated by scoring workflow)

HubSpot / MAP:
- Workflow: when Contact is created with utm_source containing "partner_" prefix, set "Co-Marketing Lead" = true, "Partner Attribution" = [partner slug from UTM], trigger lead scoring workflow for PMQS calculation
- Enrollment: Co-marketing leads routed to partner-specific nurture track (not generic marketing nurture)
- Smart list: "Co-Marketing MQLs - Current Quarter" — filter by MQL date, Co-Marketing Lead = true, PMQS ≥ 40

Crossbeam:
- Configure account overlap reporting with each active co-marketing partner
- Before each joint ABM campaign: pull overlap report to identify accounts already in partner pipeline (prioritize in campaign targeting)
- After each field event: compare attendee list against partner pipeline to identify co-sell acceleration opportunities

PHASE 5 — QUARTERLY BUDGET ALLOCATION OPTIMIZATION

A. Co-Marketing Investment Prioritization Matrix

At the start of each quarter, run this analysis to determine MDF allocation:

Step 1 — Partner Tier Scoring (weight: 40%)
Pull each partner's trailing 12-month Campaign Performance Score and normalize to 0-100

Step 2 — Pipeline ROI Ranking (weight: 35%)
Rank partners by (Closed-Won Revenue from Co-Marketing ÷ MDF Invested) over trailing 12 months

Step 3 — Strategic Value Weight (weight: 25%)
Score 0-10 on: integration marketplace placement quality, Crossbeam overlap with your top 200 target accounts, sales team support for co-sell motions, and partner brand credibility with your ICP

Final Priority Score = (0.4 × Campaign Score) + (0.35 × Pipeline ROI Rank Score) + (0.25 × Strategic Value)

B. Allocation Decision Framework

Tier 1 Partners (Final Priority Score ≥ 75): Increase MDF by 20-30% quarter-over-quarter; co-develop at least one flagship campaign (joint research report, signature field event, or dedicated webinar series)

Tier 2 Partners (Score 55-74): Maintain current MDF level; partner manager should schedule QBR to review campaign commitments and pipeline contribution trends

Tier 3 Partners (Score 35-54): Reduce MDF by 30%; require partner to submit co-marketing plan with specific metrics commitments before next disbursement

Tier 4 Partners (Score < 35): Pause MDF; move to performance-based model (MDF disbursed only after MQL or pipeline targets from prior campaign are verified)

C. Scenario Planning: Budget Redistribution Impact Model

Build a quarterly scenario model showing:
- Current state: MDF allocation by partner, pipeline ROI per partner, total pipeline attributable to MDF
- Optimized state: if budget is reallocated per Priority Score, projected pipeline increase based on top-performer ROI benchmarks applied to additional investment
- Reallocation recommendation: list partners gaining, maintaining, and losing MDF with rationale

Present this model to VP Partnerships and CMO in quarterly planning review.

OUTPUT DELIVERABLES:

Provide the following outputs:

1. CAMPAIGN MEASUREMENT PLAYBOOK
   One-page measurement setup checklist for each of the five co-marketing archetypes — with UTM naming convention, Salesforce/HubSpot field requirements, and launch-week tracking verification steps

2. PARTNER MQL QUALITY REPORT TEMPLATE
   Ready-to-populate monthly report comparing partner-generated MQL quality to direct demand gen benchmarks, with PMQS distribution charts and pipeline conversion cohort analysis

3. CO-MARKETING CAMPAIGN ROI TRACKER
   Spreadsheet structure with one row per campaign, auto-calculating: gross investment, MQLs generated, cost-per-MQL, pipeline created (at 60/90 days), closed-won (at 12 months), pipeline ROI ratio, and closed-won ROI

4. PARTNER CO-MARKETING SCORECARD
   Quarterly scoring framework with 100-point scale for each active co-marketing partner, combining campaign execution, MQL quality, and revenue impact dimensions

5. 90-DAY IMPLEMENTATION ROADMAP
   Week-by-week action plan for standing up the measurement infrastructure: UTM governance, Salesforce field build, HubSpot workflow setup, dashboard creation, and first co-marketing QBR with partners using new data

## Example Input/Output

**Input Example:**

Company: ContractIQ
Product: AI contract analytics platform for enterprise procurement teams
ARR stage: $28M ARR, 80% YoY growth
Partner context:
- 5 active co-marketing partners: Salesforce, DocuSign, Coupa, Deloitte Digital, and a regional VAR called ProcureTech Solutions
- Co-marketing activities: 12 webinars last year, 3 joint ebooks, 2 executive dinners, 1 email list swap with Coupa, 1 joint ABM campaign with Deloitte
- Annual co-marketing budget: $320K total MDF
- Current problem: We think DocuSign is our best co-marketing partner because they have the biggest logo, but our CMO suspects our smaller partners are actually generating better-quality pipeline — we have no data to prove or disprove this

**Output Example (Sample Partner MQL Quality Comparison):**

CONTRACTIQ CO-MARKETING MQL QUALITY REPORT — Q4 2025

Partner MQL Quality Benchmark Comparison (trailing 12 months):

Partner | Co-Mktg MQLs | Avg PMQS | SQL Rate (30d) | Pipeline/MQL | Win Rate | ACV | Pipeline ROI
DocuSign | 182 | 54 | 11% | $18,400 | 22% | $84,000 | 3.2×
Coupa | 94 | 68 | 19% | $31,200 | 31% | $112,000 | 6.8×
Deloitte | 47 | 79 | 26% | $52,800 | 38% | $143,000 | 9.1×
ProcureTech VAR | 31 | 61 | 22% | $28,900 | 29% | $97,000 | 5.4×
Direct Demand Gen | [baseline] | 72 | 24% | $39,400 | 33% | $118,000 | —

KEY FINDING: DocuSign produces the highest MQL volume but lowest pipeline ROI (3.2× vs. 5-9× for other partners). Deloitte Digital co-marketing generates 6× fewer MQLs but 4× higher ACV and highest win rate. CMO hypothesis confirmed: DocuSign brand visibility creates high registration volume but attracts earlier-stage/lower-intent prospects. Recommendation: Rebalance MDF — reduce DocuSign co-marketing budget from $120K to $60K; increase Deloitte Digital from $40K to $90K; add Coupa joint ABM campaign ($30K incremental).

## Success Metrics

- Partner co-marketing pipeline ROI ratio exceeds 5× within 2 quarters of implementation
- MDF budget reallocation decisions are backed by pipeline ROI data for ≥80% of partners
- Co-marketing MQL quality gap vs. direct demand gen narrows to <10 percentage points on SQL conversion rate
- Partner Campaign Performance Scores are produced and reviewed with top partners in quarterly business reviews
- Closed-won revenue from co-marketing campaigns is tracked with <15% attribution error rate (validated by cross-referencing Salesforce campaign attribution with CRM opportunity records)
- Partner managers can self-serve co-marketing ROI data in Looker/BI dashboard without RevOps involvement

## Related Prompts

- [Partner Ecosystem Revenue Analytics & Channel Partner Attribution Intelligence Engine](./AI-Powered-B2B-SaaS-Partner-Ecosystem-Revenue-Analytics-&-Channel-Partner-Attribution-Intelligence-Engine.md)
- [Channel Partner Performance Analytics & Partner-Sourced Revenue Intelligence](../../05_Analytics-&-Performance/Partner-&-Channel-Analytics/AI-Powered-B2B-Channel-Partner-Performance-Analytics-&-Partner-Sourced-Revenue-Intelligence-Engine.md)
- [Partner Program Performance Analytics & Channel Revenue Growth Intelligence Engine](../../02_Product-Marketing/Partner-&-Channel-Marketing/AI-Powered-B2B-SaaS-Partner-Program-Performance-Analytics-&-Channel-Revenue-Growth-Intelligence-Engine.md)
- [Conference Sponsorship Selection & Event Portfolio ROI Maximization Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Event-Marketing/AI-Powered-B2B-SaaS-Conference-Sponsorship-Selection-&-Event-Portfolio-ROI-Maximization-Intelligence-Engine.md)

## Integration Tips

**Salesforce**: Create a Campaign object Custom Report Type in Salesforce that joins Campaign → Campaign Member → Contact/Lead → Opportunity with "Campaign Member Status" and new co-marketing custom fields. Build a Salesforce report scheduled to run the first Monday of each month and auto-email to the partner marketing team.

**HubSpot**: Use HubSpot's UTM tracking + Salesforce Campaigns native sync to map every co-marketing contact back to the originating campaign. Set up a "Co-Marketing MQL" smart list with filters: (Co-Marketing Lead = True) AND (HubSpot Score ≥ 40) AND (Lifecycle Stage = MQL). Connect this to a partner-specific nurture workflow with co-branded email templates.

**Crossbeam**: Before any joint ABM campaign, export your target account list and run it through Crossbeam to identify accounts already in your co-marketing partner's pipeline. These "green accounts" (mutual pipeline overlap) should be tier-1 ABM targets — your partner can make warm introductions that your outbound can't achieve.

**Google Sheets + Looker Studio**: Build a lightweight co-marketing ROI tracker in Google Sheets (one row per campaign, linked to Salesforce data export) and connect to Looker Studio for partner-facing dashboards. Partners can be given view access to their own dashboard without seeing competitive partner data.

**PartnerStack / Alliances / PRM**: If using a PRM, configure MDF request submissions to auto-populate the Campaign fields in Salesforce and trigger a workflow that creates the UTM parameters and HubSpot campaign before funds are disbursed — ensuring tracking is set up correctly before the campaign runs.

**Zapier / Make**: Automate post-campaign MQL quality report emails using Zapier: trigger = Campaign End Date (Salesforce) + 30 days → pull Campaign Member MQL list → calculate average PMQS and pipeline conversion → email partner manager a co-marketing performance summary with comparison to partner's historical average.

## Troubleshooting

**Problem**: Partner claims their email promotion reached 50K subscribers, but your landing page analytics only shows 340 clicks from that source.
**Solution**: This is the most common co-marketing measurement failure. Require partners to share email delivery proof (screenshot from their ESP showing sent count, open count, click count) before MDF payment. If their reported list size isn't backed by performance data, adjust the "Partner Contribution %" metric to reflect actual measured contribution, not claimed list size. For future campaigns, request partner to send using a URL you control (your domain with UTM parameters) so you can independently verify click volume.

**Problem**: Sales team isn't logging partner touchpoints in Salesforce, so partner-influenced pipeline is invisible in the data.
**Solution**: Work with RevOps to add a 1-minute "Partner Involvement" section to the weekly pipeline review template — AEs self-report any deals where a partner made an introduction, provided a reference, or participated in a call. Make this a required field for all Stage 3+ opportunities. Alternatively, use Gong to auto-flag calls where partner names are mentioned and trigger a Salesforce notification for AE to log the partner touchpoint.

**Problem**: Co-marketing MQL quality appears low compared to direct demand gen, and leadership is questioning the ROI of partner programs.
**Solution**: Do not compare MQL quality at the moment of capture — compare pipeline conversion and ACV at 90 days. Partner-generated leads are often from audiences less familiar with your solution (earlier in the buying journey), which depresses initial scoring. Pull the 90-day SQL conversion rate and ACV for partner vs. direct leads. In most cases, partner co-marketing generates fewer but higher-ACV opportunities because the partner relationship creates buying trust that cold direct demand gen can't replicate. Present this 90-day cohort analysis to leadership before any budget decisions are made based on initial MQL quality alone.

## Version History
- v1.0: Initial creation (auto-generated)
