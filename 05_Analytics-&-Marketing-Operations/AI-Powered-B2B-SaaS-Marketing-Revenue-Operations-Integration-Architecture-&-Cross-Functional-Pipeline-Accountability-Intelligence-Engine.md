# AI-Powered B2B SaaS Marketing Revenue Operations Integration Architecture & Cross-Functional Pipeline Accountability Intelligence Engine - Build the Full-Stack MOps-RevOps Integration That Makes Marketing's Revenue Contribution Undeniable, Automated, and Board-Ready

**Difficulty:** Advanced | **Time:** 45-60 min | **Tags:** revenue operations, RevOps, marketing operations, pipeline attribution, funnel governance, CRM integration, marketing-sales alignment, CMO, pipeline accountability, HubSpot, Salesforce, marketing attribution, demand generation, B2B SaaS, data infrastructure

## Overview
Designs the complete technical and process architecture for integrating marketing operations with revenue operations—defining canonical funnel metrics, automating marketing-to-CRM data flows, building a shared attribution model that sales, marketing, and CS all agree on, and creating the governance model that makes marketing's pipeline contribution undeniable in any board or CRO conversation. Use this when your CMO gets challenged on pipeline contribution numbers, when sales and marketing argue over MQL quality, or when your company is scaling past $10M ARR and needs a professional RevOps foundation that can carry you to Series C and beyond.

## Quick Copy-Paste Version

You are a B2B SaaS revenue operations architect with deep expertise in marketing-RevOps integration. Design a complete Marketing-RevOps integration architecture for a B2B SaaS company.

COMPANY CONTEXT:
- Company: [e.g., "Vantara — AI-powered procurement intelligence platform for enterprise finance and procurement teams"]
- ARR and stage: [e.g., "$18M ARR, Series B, 65% YoY growth, targeting $40M ARR in 18 months"]
- Current biggest RevOps pain: [e.g., "Sales says marketing MQLs are garbage. Marketing says sales doesn't follow up. Nobody agrees on how much revenue marketing actually sources. CFO asked CMO to justify $3.2M marketing budget with board-credible attribution data and it took 3 weeks to compile a number that the CRO immediately challenged."]
- CRM: [Salesforce / HubSpot]
- Marketing automation: [Marketo / HubSpot / Pardot / ActiveCampaign]
- Current attribution approach: [e.g., "Last touch in Salesforce, but we also have HubSpot attribution that tells a completely different story. We use whichever number looks better in the meeting."]
- Sales motion: [e.g., "Inbound-led with SDR follow-up for ICP MQLs; outbound SDR motion for enterprise accounts; some PLG self-serve"]
- Marketing team structure: [e.g., "12 people: 1 CMO, 2 demand gen, 2 content, 1 PMM, 1 SEO, 1 paid media, 1 ABM, 1 marketing ops, 1 customer marketing, 1 events"]

OUTPUT REQUIRED:
1. CANONICAL FUNNEL DEFINITION: The single agreed-upon definition of every funnel stage from anonymous visitor to closed-won revenue — with entry criteria, exit criteria, ownership, and SLA for each stage
2. CRM DATA ARCHITECTURE: The exact Salesforce/HubSpot field mapping, object relationships, and automation rules that make marketing attribution work without manual intervention
3. SHARED ATTRIBUTION MODEL: The attribution methodology that sales, marketing, and CS leadership will all agree to sign off on — with the governance process for resolving attribution disputes
4. MARKETING-REVOPS OPERATING RHYTHM: The weekly, monthly, and quarterly meeting cadence, reporting structure, and decision authority between marketing and RevOps
5. PIPELINE ACCOUNTABILITY SCORECARD: The board-ready dashboard showing marketing's exact contribution to every dollar of pipeline and revenue — with the confidence intervals and methodology footnotes that withstand CFO scrutiny
6. IMPLEMENTATION ROADMAP: A 90-day plan to go from "everyone argues about numbers" to "one authoritative source everyone trusts"

## Advanced Customizable Version

ROLE: You are a senior revenue operations architect with 16+ years of experience building Marketing-RevOps integration infrastructure at B2B SaaS companies from $5M to $500M ARR. You have served as VP of Marketing Operations at three public SaaS companies and as RevOps advisor to 12 Series A-C companies. You have built attribution models that CFOs presented to boards without modification, and you have mediated the "what is an MQL?" debate in over 40 companies — you know the politics as well as the technology. You understand that Marketing-RevOps integration fails 80% of the time not because of bad tooling, but because of three things: (1) no agreed-upon funnel definition signed off by both marketing and sales leadership before any technical implementation begins; (2) attribution models built by marketing for marketing, rather than built to answer the questions the CFO and CRO are actually asking; and (3) governance gaps that let everyone pull different numbers from different tools and call them all "right." You design systems where the single source of truth is so obviously correct and so operationally convenient that no one has any incentive to pull a competing number anywhere else. You use MEDDPICC, Demand Unit waterfall methodology, and SiriusDecisions (now Forrester B2B) funnel frameworks. You are equally comfortable writing SQL, configuring Salesforce workflow rules, designing Marketo program structures, and facilitating a VP-level alignment conversation about pipeline ownership.

OBJECTIVE: Design a complete, production-ready Marketing-RevOps integration architecture that:
- Establishes a single canonical definition of every funnel stage — from anonymous web visitor through closed-won revenue and customer expansion — with explicit entry criteria, exit criteria, time-in-stage SLAs, and unambiguous ownership boundaries between marketing, SDRs, AEs, and CS
- Creates the technical data infrastructure that automatically captures, deduplicates, and syncs every marketing touchpoint into CRM without manual intervention, with complete audit trail
- Builds a shared attribution model that allocates pipeline and revenue credit to marketing programs in a way that sales, finance, and marketing leadership all formally endorse — including the dispute resolution process
- Generates fully automated pipeline contribution reports that answer the CFO's exact questions: "How much pipeline did marketing source this quarter? How much of that converted? What was the CAC by channel? How does marketing-sourced pipeline compare to sales-sourced and partner-sourced pipeline in win rate and average deal size?"
- Establishes a Marketing-RevOps governance cadence that prevents metric fragmentation, resolves attribution disputes within defined SLAs, and continuously improves funnel performance through structured experimentation
- Scales from current state to IPO-ready without requiring a full rearchitecture — built on Salesforce and industry-standard data models that any subsequent RevOps hire will recognize immediately

COMPANY PROFILE:
- Company name and one-sentence product description: [name + product + ICP in one sentence]
- Current ARR, growth rate, and growth stage: [ARR | % YoY growth | Series A/B/C/growth]
- Revenue targets for next 12 months: [ARR target | pipeline coverage ratio requirement | marketing's pipeline sourcing % goal]
- ICP definition: [firmographics: industry, company size, geography | technographics: existing tools they use | behavioral: triggers that indicate readiness to buy]
- Primary buying motions: [inbound-led / outbound / PLG / partner-sourced / ABM / event-driven — and % of pipeline each currently sources]
- Average selling environment: [deal size | sales cycle length | buying committee size | typical stakeholders in deal]
- Go-to-market team structure: [marketing headcount and roles | SDR team: size and reporting structure (marketing vs. sales) | AE team: size and segment split | CS: headcount and expansion ownership]

CURRENT STATE ASSESSMENT — answer each question with brutal honesty:
- Funnel definition status: [Does a written, leadership-signed funnel definition exist? If yes, when was it last updated? If no, what is the informal understanding that different teams operate from?]
- Attribution current state: [What is the current attribution model? Where does attribution data live (CRM campaign influence / MAP attribution / manual spreadsheet / nowhere)? What is the biggest attribution dispute that happened in the last 6 months?]
- CRM data quality: [What % of leads have complete UTM source data? What % of opportunities have a marketing source? Are there duplicate contacts? How long does it take to manually pull a marketing pipeline contribution report?]
- Marketing-sales relationship: [How does the marketing-sales relationship feel right now? What is the most common criticism sales makes of marketing MQLs? What does marketing's data say about MQL follow-up rate by the SDR team?]
- RevOps team: [Does a formal RevOps function exist? Who owns CRM administration? Who owns marketing attribution? Where do RevOps and marketing ops report (same leader or different leaders)?]

TECH STACK — provide complete detail for each:
- CRM: [Salesforce (edition + key customizations) / HubSpot (tier) — include relevant custom objects, fields, and campaign structure]
- Marketing automation: [Marketo / HubSpot / Pardot / ActiveCampaign — include program structure, lead scoring model, lifecycle stage model]
- SDR/sales engagement: [Salesloft / Outreach / Apollo / HubSpot Sequences — include how it syncs to CRM]
- ABM/intent data: [6sense / Demandbase / Bombora / Rollworks / none — what signals are captured and where]
- Call intelligence: [Gong / Chorus / none — what data flows to CRM]
- Data enrichment: [Clearbit / ZoomInfo / Apollo / none — what enriches the CRM record]
- Analytics/BI: [Salesforce reporting / HubSpot reporting / Looker / Tableau / Metabase / Google Sheets — where do stakeholders currently pull reports]
- Data warehouse: [Snowflake / BigQuery / Redshift / none]

---

STEP 1 — CANONICAL FUNNEL DEFINITION:

Define every funnel stage as a formal contract between marketing, sales, and CS leadership. Each stage definition must be specific enough that two different people, shown the same lead record, would independently agree on its correct stage without discussion.

STAGE 1 — ANONYMOUS VISITOR (Pre-funnel):
- Definition: Any individual who interacts with owned digital property (website, content, ad landing page) before identity resolution
- Tracking mechanism: [GA4 anonymous session + device fingerprinting via 6sense/Clearbit Reveal for company-level identification | IP-to-company resolution threshold: minimum X page views or Y minutes on site before company is flagged as "engaged"]
- Key data captured: [company (via IP resolution), pages visited, session duration, content consumed, traffic source (UTM parameters), device, geography]
- Exit criteria (to Named Account): [Company is identified + matches ICP firmographic criteria + has accumulated account engagement score ≥ [threshold in your ABM platform]]
- Owner: Marketing (unilateral ownership — no sales involvement required at this stage)
- SLA: N/A (no human action required)

STAGE 2 — KNOWN CONTACT / NAMED ACCOUNT (Top of funnel):
- Definition: Individual has provided identity information (form fill, event registration, content download, demo request) OR company has been identified via IP resolution AND has been manually added to the target account list by SDR/marketing alignment
- Entry criteria: [(A) Form submission with valid business email domain OR (B) CRM contact record created by any source (import, sales prospecting, event scan, inbound referral) OR (C) Account manually added to target account list with ICP validation]
- Key data required at entry: [First name, Last name, Business email, Company (verified against ICP), Lead source (REQUIRED — no contact enters CRM without a source), UTM parameters captured if web-sourced]
- Disqualification criteria: [Personal email domains (gmail, yahoo, hotmail, etc. — unless B2C/SMB segment), company size outside ICP threshold, industry outside ICP, geography outside territories, competitor domain]
- Exit criteria (to MQL): [Lead score reaches MQL threshold AND behavioral trigger is active AND account passes ICP fit check]
- Owner: Marketing (inbound form fills, content downloads, event registration) / SDRs (manual prospecting adds) — source field determines owner
- SLA: All inbound form fills must be reviewed within [4 business hours] — if no SDR action within SLA, Slack alert fires to SDR manager

STAGE 3 — MARKETING QUALIFIED LEAD (MQL):
- Definition: An individual contact who has demonstrated sufficient behavioral intent AND fits ICP criteria to justify immediate SDR outreach. An MQL is a MARKETING CLAIM that this lead is worth a sales conversation — not a guarantee that a sales conversation will happen.
- Entry criteria (ALL must be true simultaneously):
  - Lead score ≥ [X points] in [Marketo / HubSpot] based on the following scoring model:
    - Behavioral signals: [Demo request page view = 25 pts | Pricing page view = 20 pts | Case study download = 10 pts | Blog post read = 3 pts | Webinar attendance = 15 pts | Trade show lead scan = 10 pts | Email click = 2 pts | Webinar registration no-show = 0 pts]
    - Firmographic fit multiplier: [ICP Tier 1 account = 1.5x behavioral score | ICP Tier 2 = 1.0x | ICP Tier 3 = 0.5x | Non-ICP = 0x — lead never reaches MQL status regardless of behavior]
    - Negative signals that reset score: [Unsubscribe = -50 pts | Competitor domain = -100 pts (permanent disqualification) | Job title = student/intern = -100 pts]
  - Contact record completeness: [first name, last name, business email, company name, country all populated]
  - No active opportunity in CRM for this contact's account (if open opportunity exists, lead routes directly to owning AE as "AE Alert" — does not enter MQL queue)
  - Account not in "customer" or "former customer" stage (routes to customer success or customer marketing — not MQL queue)
- MQL routing logic: [SDR receives Salesforce task + Salesloft/Outreach cadence triggers automatically within 15 minutes of MQL status assignment | Routing based on: account owner (if assigned) → territory (by geography/industry/company size) → round-robin if unassigned territory]
- Critical governance rule: The MQL threshold is reviewed quarterly by a committee of [CMO, VP Sales, SDR Manager]. The threshold is never unilaterally changed by marketing. Changes require sign-off from all three parties.
- Exit criteria (to SAL): [SDR marks lead as "Sales Accepted" within the response SLA after outreach attempt AND documents reason for acceptance in qualification notes field]
- Exit criteria (to Recycled): [SDR marks lead as "Not Qualified — Recycle" with required disqualification reason code | Lead re-enters marketing nurture | Not counted as marketing failure unless disqualification rate exceeds [15% benchmark]]
- Exit criteria (to Disqualified): [SDR marks lead as "Disqualified" with required reason code | Lead permanently exits funnel | Counted in marketing quality report as failed MQL]
- Owner: Marketing sources MQL | SDR owns response SLA
- SDR Response SLA: [First outreach attempt within 15 minutes of MQL assignment (business hours) | 3 attempts over 5 business days minimum | If no response after complete cadence: status changes to "MQL — No Contact" for marketing review]

STAGE 4 — SALES ACCEPTED LEAD (SAL):
- Definition: SDR has confirmed that the lead is a real person at an ICP company who is potentially interested in a conversation. SAL is the SDR's acknowledgment that they accept the lead as worth pursuing — NOT that qualification is complete.
- Entry criteria: [SDR has made at least 1 successful contact (conversation, positive email reply, or LinkedIn message response) AND updated CRM with contact attempt log AND has not found a disqualifying reason to recycle or disqualify]
- SAL to SQL conversion benchmark: [Track this as the primary MQL quality metric — if SAL → SQL conversion falls below [35%], it is the SDR's job to surface why; if MQL → SAL conversion falls below [60%], it is marketing's job to surface why]
- Owner: SDR (with revenue operations oversight)
- SLA: SAL stage maximum duration [5 business days] before required update — if no update, Salesforce task fires to SDR manager

STAGE 5 — SALES QUALIFIED LEAD / OPPORTUNITY (SQL/Opportunity):
- Definition: SDR has completed MEDDPICC qualification (at minimum: Metrics identified, Economic buyer identified or accessible, Decision process understood, Champion identified) AND opportunity has been created in CRM with a close date and ACV
- Entry criteria: [Salesforce Opportunity created | Stage = "Qualified" | Close date populated | ACV populated | Lead source (inherited from originating contact record) populated | Marketing campaign (at least 1 campaign association) populated]
- This is the primary hand-off from sales development to account executives. The opportunity creation event is the most important event in the funnel from a marketing attribution standpoint — all upstream marketing touches MUST be associated to this opportunity before this point.
- Attribution capture at opportunity creation: [Automated Salesforce flow runs at opportunity creation and captures: (1) First marketing touch — campaign and channel that created the original lead record; (2) Last marketing touch — most recent campaign interaction before opportunity creation; (3) All campaign associations — every campaign member record where the contact was a member with any status ≥ "responded"]
- Owner: Account Executive (AE inherits from SDR upon opportunity creation)
- SLA: Opportunity stage advancement check weekly in pipeline review

STAGE 6 — CLOSED WON / CLOSED LOST:
- Definition: AE has recorded a final outcome for every qualified opportunity
- Closed Won: Contract signed, subscription created, billing initiated. Revenue is recognized per accounting policy.
- Closed Lost: AE has documented (1) the primary reason for loss [price / competitor / no decision / timing / wrong ICP / champion left] (2) the specific competitor won by (if applicable) (3) the contact's assessment of the evaluation criteria weighting
- Marketing attribution frozen at close: When opportunity stage changes to Closed Won or Closed Lost, all marketing attribution data is frozen and becomes the permanent historical record. No retroactive attribution changes allowed without RevOps sign-off.
- Owner: AE / Revenue Operations (AE executes, RevOps audits)

---

STEP 2 — CRM DATA ARCHITECTURE:

Design the technical infrastructure that makes marketing attribution automatic, complete, and auditable:

LEAD OBJECT ARCHITECTURE (Salesforce) / CONTACT OBJECT (HubSpot):

Required custom fields — create all of these before any marketing campaigns run:
- `Lead_Source_Original__c`: The very first source that created this lead record. NEVER overwritten. Set once at record creation by automated workflow. Values: [Web Organic | Paid Search | Paid Social | Content Download | Webinar | Event | Partner | SDR Prospecting | Customer Referral | Direct | Other — document full taxonomy here]
- `Lead_Source_Most_Recent__c`: Updated by automation on every inbound interaction. Reflects the most recent source that re-engaged the lead.
- `UTM_Source__c`, `UTM_Medium__c`, `UTM_Campaign__c`, `UTM_Content__c`, `UTM_Term__c`: Captured from URL parameters on first web touch. Set once — never overwritten (first-touch UTM preservation).
- `UTM_Source_Recent__c`, `UTM_Medium_Recent__c`, `UTM_Campaign_Recent__c`: Updated on every new web interaction (last-touch UTM capture).
- `Lead_Score__c`: Current behavioral lead score synced from marketing automation
- `Lead_Score_Behavioral__c`, `Lead_Score_Fit__c`: Component scores for diagnosis and debugging
- `MQL_Date__c`: Timestamp when contact first reached MQL threshold. Set once, never overwritten. Used for MQL-to-SQL velocity calculations.
- `SAL_Date__c`: Timestamp when SDR accepted lead. Set once.
- `SQL_Date__c`: Timestamp when opportunity created from this contact. Set once.
- `Days_MQL_to_SAL__c`: Formula field: `SAL_Date__c - MQL_Date__c`
- `Days_SAL_to_SQL__c`: Formula field: `SQL_Date__c - SAL_Date__c`
- `MQL_Disqualification_Reason__c`: Picklist — required when status set to Recycled or Disqualified: [Timing — Not Ready | Budget — Insufficient | Authority — Wrong Contact | Need — No Problem Fit | Competitor — Currently Under Contract | Bad Data — Unreachable | Duplicate | Not ICP — Company Size | Not ICP — Industry | Not ICP — Geography | SDR Prospecting — Not Interested]
- `First_Meaningful_Engagement__c`: Checkbox field set by automation when contact takes a "high-intent" action (demo request, pricing page view, ROI calculator completion) — separates high-intent MQLs from lead-score-inflated low-intent contacts

CAMPAIGN OBJECT ARCHITECTURE:

Campaign naming convention (enforce via Salesforce validation rule — no campaign saves without this format):
`[Year]-[Quarter]-[Channel]-[Campaign Type]-[Audience]-[Campaign Name]`
Example: `2026-Q1-LinkedIn-Webinar-VP-Eng-AI-Automated-Testing-Trends`

Required campaign fields:
- `Campaign_Channel__c`: Primary channel picklist [Paid Search | Paid Social | Organic Social | Email | Webinar | Virtual Event | Field Event | Trade Show | Content Syndication | Partner | Referral | Direct Mail | PR]
- `Campaign_Type__c`: [Brand Awareness | Demand Generation | Lead Nurturing | Sales Acceleration | Customer Marketing | Partner Marketing]
- `Target_ICP_Segment__c`: [Enterprise | Mid-Market | SMB | All | Named Accounts]
- `Campaign_Budget__c`: Budget allocated to this campaign (currency field)
- `Campaign_Spend_Actual__c`: Actual spend — synced from paid media platforms where possible, manually updated for non-digital campaigns
- `Campaign_Goal__c`: [MQLs / Pipeline Created / Revenue Influenced / Registrations / Attendees]
- `Campaign_Target_MQLs__c`, `Campaign_Target_Pipeline__c`: Goal fields for reporting
- `Campaign_Actual_MQLs__c`, `Campaign_Actual_Pipeline_Created__c`, `Campaign_Actual_Pipeline_Influenced__c`: Actual results (auto-calculated from CRM associations)
- `Campaign_ROAS__c`: Formula: `Campaign_Actual_Pipeline_Created__c / Campaign_Spend_Actual__c`
- `Campaign_Status__c`: [Planning | Active | Completed | Archived]

OPPORTUNITY ATTRIBUTION ARCHITECTURE:

Campaign Influence model — use Salesforce Campaign Influence (Customizable) configured as follows:
- Attribution window: [Contact must have had a campaign interaction within 90 days before or after opportunity creation date — any interaction outside this window is excluded]
- Minimum response status for influence: [Campaign member status must be "Responded" or higher — "Sent" status (passive email delivery) does NOT qualify for pipeline influence attribution]
- Attribution model selected: [Recommend "Even Distribution" (also called "Linear Attribution") as the primary model — splits pipeline credit equally across all campaigns in the attribution window. This is the most defensible model for cross-functional agreement because it does not privilege any specific channel, and the methodology is transparent and easy to explain.]
- Secondary attribution model (for analysis, not official reporting): [First Touch — for understanding which channels create new demand | Last Touch — for understanding which channels close demand | Time Decay (50% to last 30 days, 25% to prior 30 days, 25% to all earlier touches)]
- Multi-model reporting: Build a Salesforce report that shows all four attribution models side by side. This enables the conversation: "Our primary model shows $X pipeline from LinkedIn, but first-touch shows $Y — meaning LinkedIn creates a lot of new demand that other channels close."

AUTOMATION RULES (Salesforce Flows — replace triggers with flows for auditability):

Flow 1 — "MQL Status Set":
Trigger: Lead score field update ≥ MQL threshold AND Lead ICP Fit Score ≥ minimum
Actions: (1) Set `Lead_Status__c` = MQL; (2) Set `MQL_Date__c` = today; (3) Create SDR task with high priority and 4-hour due time; (4) Add contact to Salesloft/Outreach cadence via API call; (5) Log MQL event to activity timeline with source and score details; (6) Post Slack notification to SDR queue channel with lead name, company, ICP score, lead score, most recent behavioral trigger, and link to CRM record

Flow 2 — "MQL Response SLA Monitoring":
Trigger: Scheduled flow runs every 2 hours during business hours
Actions: Query all leads in MQL status with MQL_Date more than 4 hours ago and zero logged activities. For each: (1) Send Slack escalation to SDR manager with lead list; (2) If MQL_Date more than 24 hours ago with zero activity, escalate to VP Sales

Flow 3 — "Opportunity Created — Attribution Capture":
Trigger: Opportunity record created (Stage = Qualified)
Actions: (1) Find the Contact Role on this Opportunity; (2) Copy `Lead_Source_Original__c` from Contact to Opportunity `Lead_Source__c`; (3) Copy `UTM_Source__c` through `UTM_Term__c` from Contact to Opportunity custom fields; (4) Copy `MQL_Date__c` and `SQL_Date__c` from Contact to Opportunity for velocity tracking; (5) Log audit record: "Attribution captured at opportunity creation on [timestamp] from contact [ID]"

Flow 4 — "Closed Won Revenue Attribution Lock":
Trigger: Opportunity Stage changed to "Closed Won"
Actions: (1) Write final attribution snapshot to custom historical attribution object (preserves attribution even if contact/campaign records later changed); (2) Calculate and write `Marketing_Attribution_Confidence__c` = [High if UTM + campaign associations present | Medium if only lead source present | Low if lead source = "Unknown" or "Direct"]

---

STEP 3 — SHARED ATTRIBUTION MODEL & GOVERNANCE:

Define the attribution methodology that all revenue leaders will formally endorse:

THE ATTRIBUTION TREATY (present this as a formal document, get signatures):

WHAT WE ARE MEASURING:
Marketing will report three distinct pipeline metrics in every executive report — these are NOT interchangeable:
1. Marketing-Sourced Pipeline: Opportunities where the FIRST touchpoint that created the lead record was a marketing program. This is the metric marketing "owns" and is accountable for.
2. Marketing-Influenced Pipeline: Opportunities where at least one marketing touchpoint appears in the attribution window (within 90 days of opportunity creation), regardless of who first created the lead. This is ALWAYS larger than marketing-sourced pipeline.
3. Marketing-Assisted Pipeline: Opportunities where marketing provided support (content delivered, event attended, ad impressions served) but the contact was originally sourced by SDR outbound or partner. This is the most inclusive metric.

WHAT WE ARE NOT MEASURING (and why):
- We will not debate whether inbound MQLs are "really" marketing-sourced when an AE had a prior relationship with the contact. Once a contact submits an inbound form, it is marketing-sourced regardless of prior relationship — the prior relationship is accounted for in the win rate differential (which is why inbound from known contacts closes faster and at higher rates).
- We will not retroactively reclassify pipeline attribution after an opportunity closes. Attribution is fixed at opportunity creation. If we had wrong source data at creation, that is a data quality problem to solve prospectively.

ATTRIBUTION DISPUTE RESOLUTION PROCESS:
- Any VP or above who challenges a pipeline attribution number must submit a formal query to Revenue Operations within 5 business days of the report date
- RevOps has 10 business days to investigate and produce a written attribution audit showing the original lead source data, every campaign touchpoint in the window, and the CRM audit trail
- If the attribution is found to be incorrect due to data error: attribution is corrected in the current report AND the data quality failure is documented and added to the quarterly data quality report
- If the attribution is found to be correct and the challenge is methodological: the challenger documents their alternative methodology proposal, which is reviewed by the Attribution Governance Committee at the next quarterly meeting
- THE ATTRIBUTION GOVERNANCE COMMITTEE meets quarterly and consists of: CMO (marketing chair), VP Sales / CRO (sales chair), CFO or VP Finance (finance chair), VP RevOps (neutral facilitator). This committee has sole authority to change the attribution model. All other attribution decisions are made by RevOps with the mandate of this committee.

QUARTERLY ATTRIBUTION CALIBRATION:
At each quarterly calibration, the committee reviews:
1. Win rate comparison: Marketing-sourced pipeline win rate vs. SDR-outbound win rate vs. partner-sourced win rate — if marketing-sourced leads close at lower rates, the MQL quality definition needs tightening
2. ACV comparison: Average deal size by pipeline source — if marketing sources smaller deals, ICP targeting may need adjustment or pipeline weighting may need adjustment
3. Velocity comparison: Average days MQL → Close Won by source — faster closes from marketing-sourced leads indicate higher quality intent
4. Attribution model sensitivity analysis: Run all four attribution models, see how the story changes — present to committee

---

STEP 4 — MARKETING-REVOPS OPERATING RHYTHM:

Define the standing meeting cadence and decision authority:

WEEKLY: Marketing-SDR Pipeline Review (45 minutes — every Tuesday):
Participants: Demand Gen Lead, Marketing Ops, SDR Manager, BDR Team Lead
Agenda: (1) MQL volume last 7 days vs. pacing target [15 min]; (2) MQL → SAL conversion rate and notable disqualifications [15 min]; (3) SDR follow-up SLA compliance — any MQLs past 4-hour SLA [10 min]; (4) Top 5 high-intent accounts showing engagement but no MQL yet — should SDRs proactively sequence? [5 min]
Decision authority: SDR Manager can request marketing to accelerate nurture on specific accounts; Demand Gen Lead can flag SDR capacity constraints that are holding pipeline from advancing
Output: Weekly MQL quality scorecard (automated — sent by MOps by EOD Tuesday)

WEEKLY: Revenue Operations Pipeline Call (60 minutes — every Thursday):
Participants: RevOps, CMO, VP Sales, VP CS, CFO (monthly, not weekly)
Agenda: Pipeline creation vs. weekly target; stage-by-stage velocity; marketing pipeline pacing vs. quarterly target; open opportunities needing marketing support (decision support content, references, competitive intelligence)
Marketing MOps role: Attend and present the marketing pipeline contribution numbers — own the data, defend the methodology

MONTHLY: Marketing-RevOps Data Quality Review (30 minutes — last week of month):
Participants: Marketing Ops, RevOps
Agenda: (1) Lead source completeness rate (target >95% of CRM contacts have valid source); (2) Campaign association completeness rate (target >85% of opportunities have at least 1 campaign association); (3) UTM capture rate (target >80% of web-sourced leads have UTM data); (4) Duplicate contact rate; (5) MQL disqualification reason code completeness (target 100% of recycled/disqualified leads have reason code)
Output: Monthly Data Quality Scorecard shared with CMO and VP Sales

QUARTERLY: Attribution Governance Committee (90 minutes):
Participants: CMO, VP Sales/CRO, CFO, VP RevOps
Agenda: Review quarterly attribution results; sensitivity analysis across attribution models; win rate/ACV/velocity comparison by source; MQL quality score calibration; attribution model changes (if any); next quarter pipeline targets by source
Output: Signed attribution model endorsement document for board reporting

---

STEP 5 — PIPELINE ACCOUNTABILITY SCORECARD:

Design the board-ready marketing revenue contribution report:

REPORT STRUCTURE — MARKETING PIPELINE CONTRIBUTION (Quarterly):

SECTION 1 — HEADLINE METRICS (Lead slide — answers CFO's 3 questions):
- Marketing-Sourced Pipeline Created This Quarter: $[X]M | % of Total Company Pipeline Created: [X%] | vs. Prior Quarter: [+/-X%]
- Marketing-Sourced Pipeline → Closed Won This Quarter: $[X]M | Win Rate on Marketing-Sourced Pipeline: [X%] | vs. SDR-Sourced Win Rate: [X%]
- Marketing-Influenced Pipeline → Closed Won This Quarter: $[X]M | Marketing-Influenced % of Total Revenue: [X%]
- Blended Marketing CAC (Marketing Spend / Marketing-Sourced New Logos): $[X] | vs. Prior Quarter: [+/-X%] | vs. Company CAC Benchmark: [above/below]

SECTION 2 — CHANNEL CONTRIBUTION BREAKDOWN:
[Table: Channel | Pipeline Sourced | Pipeline Influenced | Spend | Pipeline ROAS | Win Rate | Avg ACV | Avg Days to Close]
Channels: Paid Search | Paid Social - LinkedIn | Paid Social - Meta | Organic/Content | Webinars/Events | Content Syndication | Partner/Referral | Community | Direct/Brand

SECTION 3 — FUNNEL EFFICIENCY METRICS:
[Table: Stage | Volume | Conversion to Next Stage | Avg Days in Stage | QoQ Change]
Stages: Anonymous Visitors → Known Contacts → MQLs → SALs → SQLs → Opportunities → Closed Won

SECTION 4 — MQL QUALITY SCORECARD:
- MQL Volume vs. Target: [actual] / [target] ([X%] to target)
- MQL → SAL Conversion Rate: [X%] | Benchmark: [35-45% for healthy B2B SaaS] | Trend: [improving/declining]
- MQL → SQL Conversion Rate: [X%] | Benchmark: [20-30% for healthy B2B SaaS] | Trend: [improving/declining]
- Top 3 Disqualification Reasons This Quarter (% of disqualified MQLs): [1. Timing — Not Ready: X% | 2. Not ICP — Company Size: X% | 3. Competitor Contract: X%]
- Insight: "The [X%] disqualification rate for 'Timing — Not Ready' suggests strong awareness-stage demand that isn't converting. Recommendation: Launch 6-month re-engagement nurture sequence targeting this cohort with quarterly value-building touches."

SECTION 5 — ATTRIBUTION METHODOLOGY FOOTNOTE (for CFO/board):
"Pipeline attribution uses Linear Multi-Touch attribution, crediting all marketing programs that had an engaged interaction with any contact at the opportunity account within 90 days of opportunity creation. 'Marketing-Sourced' is defined as opportunities where the lead record was created by a marketing program (inbound form fill, event registration, content download, or paid media click-to-form). 'Marketing-Influenced' includes all opportunities where at least one marketing touchpoint appears regardless of pipeline source. All attribution data is captured automatically in Salesforce at opportunity creation, audited monthly by Revenue Operations, and reviewed quarterly by the Attribution Governance Committee. Historical attribution data is immutable once an opportunity closes."

---

STEP 6 — 90-DAY IMPLEMENTATION ROADMAP:

DAYS 1-30 — FOUNDATION:
Week 1: Funnel definition workshop — full-day session with CMO, VP Sales, SDR Manager, RevOps to align on stage definitions. Output: signed funnel definition document.
Week 2: CRM audit — RevOps and Marketing Ops audit CRM data completeness. Document: % of contacts with source, % of opportunities with campaign association, UTM capture rate. This is the "before" baseline.
Week 3: Build custom fields — create all required custom fields in CRM per the architecture above. Do NOT run any campaigns or change any processes yet.
Week 4: Configure flows and automation — build Salesforce Flows for MQL automation, opportunity attribution capture, and SLA monitoring. Test with 20 synthetic records before activating in production.

DAYS 31-60 — INFRASTRUCTURE:
Week 5-6: Campaign object cleanup — rename all existing active campaigns to match naming convention. Archive campaigns from >6 months ago that have no associated pipeline. Create Q3 campaign structure from scratch using the new naming convention.
Week 7: Attribution model configuration — configure Salesforce Campaign Influence model per the architecture above. Run attribution report for the previous 2 quarters using the new model. Compare to old numbers to understand the delta before presenting to leadership.
Week 8: Stakeholder alignment — present the new attribution numbers alongside the old numbers to CMO, VP Sales, CFO. Explain every difference. Get formal sign-off on the new model. Document the signed endorsement.

DAYS 61-90 — OPERATIONALIZATION:
Week 9-10: Launch operating cadences — first weekly marketing-SDR review, first monthly data quality review. Establish Slack alert channels. Train SDR team on new MQL response protocol.
Week 11: First pipeline contribution report — produce the full SECTION 1-5 pipeline scorecard for the just-completed quarter using the new methodology. Present to RevOps committee before sharing with board.
Week 12: 90-day retrospective — compare data quality metrics (source completeness, campaign association rate, UTM capture rate) to the Day 1 baseline. Document improvements. Identify remaining gaps. Set 180-day improvement targets.

## Example Input/Output

**Scenario:** Syndara — AI-powered contract intelligence platform for mid-market legal and procurement teams. $22M ARR, growing 55% YoY, Series B. 10-person marketing team. CRO just told the board that "marketing MQLs convert at less than 15% to opportunities and marketing is spending $2.8M to source pipeline that closes at half the rate of outbound." CMO has different numbers and a three-week-old spreadsheet to back them up. Attribution dispute has become a weekly argument.

**Sample Output — The Attribution Treaty Signed Metrics:**

After running this prompt and implementing the architecture:

Pre-implementation discovery revealed:
- Source field blank on 31% of CRM contacts (no one knew where they came from)
- 67% of opportunities had zero campaign associations — marketing was not getting attribution credit for deals it influenced
- SDR team logging "SDR Prospecting" as the source for inbound MQLs they worked (inflating outbound numbers, deflating marketing numbers)
- Win rate comparison was apples-to-oranges: CRO was comparing enterprise outbound ACV ($180K) to all marketing MQLs including SMB ($47K average ACV)

Corrected attribution revealed:
- Marketing-sourced pipeline win rate by segment: Enterprise (ICP Tier 1) = 24% — statistically identical to enterprise outbound. SMB = 11% — lower, but also $62K CAC vs. $144K for outbound
- When campaign influence was properly tracked, 73% of Closed Won deals had at least 1 marketing touchpoint — up from 22% in the old reporting
- The 15% MQL-to-opportunity conversion the CRO cited included 8 months of MQLs before the MQL threshold was recalibrated in March — after March, conversion rate was 28%

The Attribution Treaty resolved the dispute: Marketing owns enterprise-segment pipeline contribution reporting. The comparison point is enterprise outbound pipeline, not blended total. Marketing CAC for enterprise segment is $89K — vs. $144K outbound. Both motions are valuable; outbound creates demand, marketing captures and nurtures it.

**Board slide headline after implementation:** "Q3 2026: Marketing sourced $8.4M in marketing-qualified pipeline (38% of company total), converting at 23% to Closed Won — ahead of company average win rate of 21%. Blended marketing CAC: $94K, down 12% QoQ due to content and organic scaling. Attribution methodology reviewed and endorsed by CMO, CRO, and CFO in July 2026."

## Success Metrics

**Data Quality Metrics:**
- Lead source completeness rate: >95% of all CRM contacts have valid, non-"Unknown" source field
- Campaign association completeness rate: >80% of closed-won opportunities have at least 1 campaign association
- UTM capture rate: >78% of web-sourced leads have complete UTM data (source, medium, campaign)
- Attribution audit pass rate: >90% of quarterly attribution challenges resolved within SLA with no material error found

**Alignment Metrics:**
- Attribution dispute frequency: <2 formal attribution challenges per quarter (down from [X] informal disputes monthly pre-implementation)
- CMO board prep time for pipeline attribution slide: <2 hours (down from >20 hours pre-implementation)
- Time to answer "how much pipeline did marketing source last quarter?": <5 minutes via Salesforce report (down from days or weeks)
- RevOps endorsement: Attribution model signed by CMO, CRO, and CFO — documented annually

**Business Impact Metrics:**
- MQL → SQL conversion rate improvement: Target 5+ percentage point improvement within 6 months of implementing proper stage definitions and SDR SLA monitoring
- Marketing CAC accuracy: Marketing-sourced CAC can be calculated by channel (not just blended) — enabling reallocation of budget from high-CAC to low-CAC channels
- Pipeline coverage ratio: Quarterly marketing-sourced pipeline target achievable and measurable in real time (no end-of-quarter surprises)

## Related Prompts

- [AI-Powered B2B SaaS Marketing Operations Real-Time KPI Dashboard & Autonomous Performance Reporting Revenue Intelligence Engine](./AI-Powered-B2B-SaaS-Marketing-Operations-Real-Time-KPI-Dashboard-&-Autonomous-Performance-Reporting-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Lead Routing & Marketing Sales Handoff Architecture Revenue Operations Governance Intelligence Engine](./AI-Powered-B2B-SaaS-Lead-Routing-&-Marketing-Sales-Handoff-Architecture-Revenue-Operations-Governance-Intelligence-Engine.md)
- [AI-Powered B2B Marketing Attribution Audit & Revenue Proof of Contribution Intelligence Engine](../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-B2B-Marketing-Attribution-Audit-&-Revenue-Proof-of-Contribution-Intelligence-Engine.md)
- [AI-Powered CMO Revenue Forecast Modeling & Predictive Pipeline Intelligence Engine](../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-CMO-Revenue-Forecast-Modeling-&-Predictive-Pipeline-Intelligence-Engine.md)

## Integration Tips

**Salesforce:**
- Use Salesforce's native Campaign Influence (Customizable) — not the standard Campaign Influence model. The customizable version allows you to define your own attribution window and response status requirements, which is critical for a defensible model.
- Build all automation as Record-Triggered Flows (not Process Builder, not Workflow Rules — both are being deprecated). Flows have a full execution log accessible in Salesforce's Automation Debugger, making attribution audits possible without custom development.
- Create a dedicated "Marketing Operations" Integration User in Salesforce with a unique profile — all automated field updates and flow actions should run as this user, making it easy to identify programmatic changes vs. manual user changes in the audit trail.
- Enable Field History Tracking on Lead Status, MQL Date, Lead Source, and all key opportunity attribution fields — this creates an immutable audit log directly in Salesforce that requires no additional infrastructure.

**HubSpot:**
- If using HubSpot as both CRM and MAP, configure the Contact lifecycle stage using Custom Properties (not the default lifecycle stage field) — this gives you the timestamp history and conditional branching logic required for the funnel tracking described above.
- Use HubSpot's "Original Source" and "Original Source Data 1/2" properties as your first-touch capture — these are populated automatically and cannot be overwritten by users (use them as your `Lead_Source_Original` equivalent).
- Build a Salesforce-HubSpot integration (if running both) with HubSpot as the MAP and Salesforce as the CRM: sync direction should be HubSpot → Salesforce for contact behavior data; Salesforce → HubSpot for lifecycle stage updates. Do NOT sync bidirectionally on lifecycle stage fields without careful deduplication logic — circular sync loops are the #1 cause of bad funnel data.

**Marketo:**
- Build your Marketo Program hierarchy to mirror the Salesforce Campaign naming convention exactly — each Marketo Program should create exactly one Salesforce Campaign. Avoid many-to-one mapping (many Marketo programs → one Salesforce campaign) which destroys attribution granularity.
- Use Marketo's Program Member custom fields to capture behavioral context that doesn't exist natively in Salesforce — e.g., "Content Asset Downloaded," "Webinar Session Attended," "Demo Type Requested" — these enrich the attribution story in your pipeline contribution report.
- Configure Marketo's RCA (Revenue Cycle Analytics) or build equivalent reporting using Marketo's Program Performance report to get the Program-level pipeline and revenue contribution data that feeds your Channel Contribution Breakdown (Section 2 of the Scorecard).

**Salesloft / Outreach:**
- Configure the Salesloft → Salesforce sync to log every email send, call attempt, and connected conversation as a Salesforce Activity on the Lead or Contact record. This is the data that proves SDR follow-up SLA compliance in the weekly marketing-SDR review.
- Add a "MQL Cadence" tag to all cadences triggered by marketing MQLs — this allows you to separately analyze SDR activity on marketing MQLs vs. outbound prospecting cadences, which is essential for the MQL quality scorecard.
- Configure Salesloft disposition mapping so every call outcome (connected, left voicemail, wrong number, email bounce) writes a standardized disposition value to the CRM record. This enables the disqualification reason analysis in Section 4 of the scorecard.

**Looker / BI Tools:**
- Build the pipeline attribution model logic in dbt (if using a data warehouse) rather than in Salesforce APEX or Looker calculated fields. dbt models are version-controlled, testable, and documented — making your attribution methodology auditable and portable if you switch BI tools.
- Create a "Certified" dashboard folder in Looker/Tableau containing only the Attribution Governance Committee-endorsed reports. Any report outside the Certified folder is unofficial and should be labeled "Draft / Internal Analysis Only."
- Build the board scorecard as a Looker Look (not a Dashboard) — Looks generate cleaner PDFs for board export, and the Looker Scheduled Deliver feature can auto-generate and email the PDF to the CMO on the 1st of each month before the board meeting.

## Troubleshooting

**Problem 1: SDR team is setting inbound MQLs to "SDR Prospecting" as the lead source, deflating marketing attribution numbers.**
Fix: This is a cultural problem masking a technical gap. (1) Conduct an audit: pull all contacts created in the last 6 months with Lead Source = "SDR Prospecting" and cross-reference against web analytics to identify contacts who had a prior web interaction — these are misclassified inbound contacts; (2) Implement a technical lock: build a Salesforce validation rule that prevents any user from manually changing the `Lead_Source_Original__c` field once it is populated. The original source field should only be writable by the Marketing Operations integration user. If a user attempts to overwrite it, the validation rule blocks the save and displays: "Original Source is set automatically and cannot be manually changed. Contact Marketing Operations if you believe this record is misclassified."; (3) Train the SDR team on the policy at the next sales kickoff: the source field describes how the lead was CREATED, not how the SDR found them. If a lead submitted an inbound form, the source is inbound — even if the SDR also had the person in their prospecting sequence.

**Problem 2: Quarterly attribution report is complete and data is clean, but the CRO still doesn't trust the numbers and presents competing data in board prep meetings.**
Fix: The attribution treaty is not working because it was never formally endorsed. (1) Do not fight the competing data in the meeting — instead, say: "I'd like to understand the methodology behind those numbers so we can reconcile them. Can RevOps schedule 30 minutes with both of us to compare the underlying data?" This moves the dispute from political (marketing vs. sales) to analytical (let's find where the numbers diverge); (2) Run the attribution sensitivity analysis: pull the same pipeline cohort through all four attribution models (first-touch, last-touch, linear, time-decay) and present the range. "Depending on the model, marketing's contribution ranges from $X (first-touch) to $Y (last-touch), with our endorsed linear model at $Z. Here's why we chose linear." This shows rigor and takes away the "you're just choosing the model that makes marketing look best" argument; (3) Escalate to the Attribution Governance Committee. The committee's quarterly meeting is the formal venue for resolving methodology disputes — bring the competing methodology as an agenda item and require the CRO to formally present it there, not in a board prep meeting.

**Problem 3: The funnel stage definitions were agreed upon in the workshop, but 3 months later different teams are reverting to their own informal interpretations.**
Fix: Definitions drift when they are not operationalized with technical enforcement. (1) Audit every funnel stage to verify that Salesforce workflow/flow automation is enforcing the entry and exit criteria — if a stage requires an SDR to log a contact attempt before moving to SAL, there should be a validation rule preventing the stage change without the activity; (2) Add the funnel definition compliance check to the monthly data quality review: count the number of SAL records with zero logged activities, the number of SQL/Opportunity records with blank attribution fields, and the number of MQL records with no SDR follow-up task; (3) Run a quarterly "funnel definition refresh" — a 30-minute session with SDR Manager and VP Sales to review any ambiguous cases that have come up in the past quarter and update the written definition if needed. Post the updated definition in the company wiki and send a summary to the full revenue team. Stage definitions should be living documents with version history, not static one-time agreements.

## Version History
- v1.0: Initial creation (auto-generated)
