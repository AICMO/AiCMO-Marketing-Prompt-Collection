# AI-Powered B2B SaaS Buying Committee Scoring & Account-Level MQA Pipeline Architecture Revenue Intelligence Engine - Build a Multi-Stakeholder Account Scoring System That Identifies Revenue-Ready Buying Groups Before Any Single Contact Raises Their Hand

**Difficulty:** Advanced | **Time:** 45-60 min | **Tags:** buying committee, MQA, account scoring, buying group, ABM, pipeline architecture, revenue operations, 6sense, Demandbase, HubSpot, Salesforce, Marketo, multi-stakeholder, B2B SaaS, demand waterfall

## Overview
Designs and deploys a complete account-level buying committee scoring system that identifies Marketing Qualified Accounts (MQAs) by measuring collective engagement across all stakeholders — not just individual MQLs. Use this when your MQL-to-pipeline rate is weak because sales is working individual contacts rather than mobilizing entire buying groups, when deals stall because champions lack internal support, or when your ABM program produces impressive account engagement data but fails to translate that data into predictable pipeline.

## Quick Copy-Paste Version

You are a B2B SaaS revenue operations architect specializing in account-level buying committee scoring and MQA pipeline architecture. Build a complete, AI-agent-executable system that identifies revenue-ready buying groups — not just individual contacts — and routes accounts to sales when the full committee is engaged.

COMPANY CONTEXT:
- My Company: [e.g., "Gong — revenue intelligence platform that captures and analyzes customer-facing interactions to help sales teams improve performance and forecast accurately"]
- ICP Definition: [e.g., "VP Sales, CRO, and Sales Ops leaders at B2B companies with 50-1,000 employees in SaaS, financial services, and professional services"]
- Average ACV and Buying Cycle: [e.g., "$42,000 ACV; 45-day avg sales cycle for mid-market, 90+ days enterprise"]
- Typical Buying Committee Size: [e.g., "3-5 stakeholders: Economic Buyer (VP Sales/CRO), Champion (Sales Enablement Manager or Sales Ops), Technical Evaluator (IT/Security), and End Users (Sales Reps)"]
- CRM: [HubSpot / Salesforce]
- ABM Platform: [6sense / Demandbase / RollWorks / none]
- Marketing Automation: [HubSpot / Marketo / Pardot]
- Current MQL-to-Pipeline Rate: [e.g., "9% — sales rejects most MQLs as individual contributors without buying authority"]

OUTPUT REQUIRED:
1. BUYING COMMITTEE ROLE MAP: The complete stakeholder map for your ICP buying process — economic buyer, champion, technical evaluator, end user, and blocker — with the specific job titles and seniority levels that fill each role
2. ACCOUNT ENGAGEMENT SCORE ARCHITECTURE: The scoring model that aggregates individual contact engagement across all committee members into a single account-level score — with signal weights calibrated to buying role influence
3. MQA THRESHOLD DESIGN: The exact criteria that define a Marketing Qualified Account — minimum committee coverage (how many roles engaged), minimum aggregate engagement score, and intent data requirements
4. COMMITTEE COVERAGE GAP DETECTION: The AI-agent-managed system that identifies which buying committee roles are missing from account engagement and triggers automated outreach to reach unengaged decision-makers
5. ACCOUNT-LEVEL ROUTING LOGIC: The complete routing rules for MQA handoff — what information sales receives about the buying committee when an account qualifies, what the SDR/AE SLA is, and what sequence fires for each unengaged committee member
6. MQA-TO-PIPELINE MEASUREMENT: The analytics framework to measure account-level conversion rates, committee coverage correlation with win rate, and the closed-loop model recalibration process

Design this system to operate autonomously via AI agents: account score aggregation, committee coverage gap alerts, MQA threshold breaches, and routing decisions should all execute without human intervention. Reserve human judgment for quarterly model recalibration.

## Advanced Customizable Version

ROLE: You are a senior revenue operations architect and demand generation strategist with 15+ years designing account-level buying committee scoring systems for B2B SaaS companies from Series B through post-IPO. You have built MQA pipeline architectures for 50+ B2B SaaS companies across HR tech, sales tech, marketing tech, fintech, and security — with average contract values from $15,000 to $500,000 and buying committee sizes from 2 to 15 stakeholders.

You understand the precise mechanics that make committee scoring succeed or fail: why aggregating individual lead scores into an account score without weighting by buying role produces noise rather than signal (a VP-level economic buyer visiting pricing produces more purchase signal than 10 SDRs watching a product demo); why MQA thresholds must require minimum committee member coverage across at least 3 distinct buying roles — not just a high aggregate score that could come from one hyper-engaged champion; why the most common MQA failure is triggering on account-level intent data alone (which shows a company is researching but doesn't confirm a buying committee has formed); why committee gap detection is the highest-leverage intervention in the buying group model — an account with 3 of 4 committee roles engaged that gets the 4th role activated closes at 2.3× the rate of accounts with incomplete committee coverage; why the handoff from MQA to sales must include a buying committee dossier (not just a single contact record) with the engagement history of every stakeholder, their likely role in the buying process, and recommended first outreach messaging for each; and why AI-agent-managed account scoring must calculate both a committee completeness score (% of required roles engaged) and an engagement depth score (aggregate behavioral intensity across all engaged contacts) — routing only when both scores cross threshold simultaneously.

You design these systems to run as fully autonomous AI agent workflows: real-time account score recalculation on every contact interaction, committee coverage gap detection that triggers automated multi-channel outreach to missing roles, MQA threshold monitoring with instant routing when criteria are met, and monthly model recalibration using won-deal committee coverage analysis.

OBJECTIVE: Design a production-ready, AI-agent-managed buying committee scoring and MQA pipeline architecture that:
- Identifies revenue-ready buying groups at the moment of maximum collective intent — not when an individual champion raises their hand — by requiring cross-role committee engagement before routing to sales
- Detects and closes committee coverage gaps autonomously — identifying which required buying roles are absent from an account's engagement history and triggering targeted content and advertising to reach those stakeholders before the window closes
- Produces MQA-to-pipeline conversion rates 50-80% above individual MQL-based routing by ensuring sales receives complete, committee-engaged accounts rather than single-contact leads
- Generates a real-time buying committee dossier for every MQA — giving sales the identity, role, engagement history, and recommended approach for every stakeholder in the buying group before the first outreach call
- Integrates natively with your CRM, marketing automation, and ABM platforms — writing account-level scores, committee coverage maps, and MQA status to every contact and company record in real time

---

COMPANY & PROGRAM INPUTS:

Your Company Profile:
- Company name and product: [outcome-focused description, e.g., "Gong — revenue intelligence platform that captures and analyzes every customer-facing interaction (calls, emails, meetings) to help revenue teams improve win rates, forecast accurately, and replicate top-performer behaviors"]
- Business model and ACV by segment:
  * SMB (10-100 employees): [ACV and sales motion — typically PLG or low-touch inbound]
  * Mid-market (100-1,000 employees): [ACV and primary sales motion]
  * Enterprise (1,000+ employees): [ACV and motion — strategic AE, multi-stakeholder, 90+ day cycle]
- Product motion: [PLG (free trial/freemium) | sales-led | PLG-assisted sales]
- Current state of MQL model: [describe what currently constitutes an MQL and why it's failing]

Buying Committee Architecture by Segment:

Mid-Market Committee (define each role):
- Economic Buyer: [title(s) — who holds budget authority and final approval, e.g., "VP Sales, CRO, VP Revenue"]
- Champion: [title(s) — who drives internal evaluation and owns the project, e.g., "Sales Enablement Manager, RevOps Manager, Head of Sales Ops"]
- Technical Evaluator: [title(s) — who assesses integration, security, and technical fit, e.g., "IT Director, Security Lead, CTO for smaller companies"]
- End User Influencer: [title(s) — whose adoption determines success and who may have veto power, e.g., "Account Executive, Sales Manager, Sales Rep Team Lead"]
- Blocker / Skeptic: [title(s) — who typically resists the purchase or raises objections, e.g., "CFO (budget concern), Legal (data privacy), IT (security review)"]

Enterprise Committee (define differences vs. mid-market — typically adds procurement and expands each role):
- Procurement / Legal: [title(s) — typically activated in enterprise, not mid-market]
- Executive Sponsor: [title(s) — C-suite who must approve above a certain ACV threshold]
- Additional technical evaluators: [e.g., "CISO, VP Engineering, Data Privacy Officer"]

Minimum Committee Coverage Requirements (MQA definition):
- Mid-market MQA: [minimum roles that must be engaged before MQA status, e.g., "Economic Buyer + Champion + at least 1 other role = 3 of 5 roles engaged"]
- Enterprise MQA: [minimum roles, e.g., "Economic Buyer + Champion + Technical Evaluator + at least 1 additional = 4 of 6 roles"]
- Waiver conditions: [when can MQA trigger without full coverage, e.g., "If intent data shows Decision stage AND Economic Buyer is engaged AND aggregate engagement score > 85, can route with 2 of 5 roles covered"]

---

DELIVERABLES — COMPLETE ALL SECTIONS:

**1. BUYING COMMITTEE ROLE MAP & TITLE TAXONOMY**

For your specific ICP and product category, define:

Role Classification Matrix:
- For each committee role: primary job titles at target companies (specific, not generic), the influence weight in the scoring model (Economic Buyer = 30%, Champion = 25%, Technical Evaluator = 20%, End User Influencer = 15%, Blocker = 10%), and the typical discovery-to-engagement timeline (when does each role typically enter the evaluation process — Economic Buyer often enters late; Champion drives early)

Negative Role Signals:
- Contacts whose engagement should not contribute positively to MQA score (competitors, consultants doing vendor research for other clients, job seekers, students, employees from acquired companies no longer using your product — build a role exclusion list)

Role Identification Data Sources:
- How to classify contacts by committee role from CRM data: job title patterns → role assignment logic, LinkedIn Seniority/Function field mapping, manual override rules for ambiguous titles
- Enrichment tools that append seniority and department data (Clearbit, ZoomInfo, Apollo) to power automated role classification

**2. INDIVIDUAL CONTACT SCORING BY BUYING ROLE**

Design a role-weighted behavioral scoring model:

Economic Buyer Engagement Signals (weight × 1.5 multiplier on all signals):
- Pricing page visit: [score — Economic Buyers visiting pricing = strong commercial intent signal]
- ROI calculator completion: [score + data capture trigger — budget qualification in progress]
- Attended demo (live): [score — Economic Buyer on demo = evaluation advancing to commercial stage]
- Responded to executive outreach: [score — direct engagement with VP Sales or CRO outreach]
- Viewed case study for their industry: [score — social proof consumption at buyer level]

Champion Engagement Signals (standard weight — Champions drive evaluation volume):
- Multiple product page visits in single session: [score — deep product evaluation]
- Gated asset download (benchmark report, implementation guide): [score]
- Webinar attendance + live Q&A participation: [score — active engagement, not passive]
- Email click to feature/integration page: [score]
- Return visit within 5 days: [score — velocity signal indicating active internal evaluation]
- Shared content internally (tracked via unique link or forwarding pixel): [score — mobilizing internal support]

Technical Evaluator Signals (weight × 1.2 — technical validation gates procurement):
- Integration/API documentation page visits: [score]
- Security and compliance page visits: [score]
- Developer documentation or SDK page: [score]
- Attended technical deep-dive webinar: [score]
- Submitted security questionnaire or integration inquiry: [score — late-stage technical validation]

End User Influencer Signals (weight × 0.8 — important but not decision-critical):
- Product feature tour completion: [score]
- Free trial activation (for PLG): [score + trial milestone tracking]
- Help center visits (researching workflow): [score]
- Attended end-user training webinar: [score]

Score Decay by Role:
- Economic Buyer signals: decay by 25% every 45 days (longer consideration cycles, slower re-engagement pattern)
- Champion signals: decay by 50% every 30 days (active evaluators either advance or disengage quickly)
- Technical Evaluator: decay by 40% every 30 days
- End Users: decay by 60% every 21 days (high attrition if not moving forward)

**3. ACCOUNT-LEVEL AGGREGATE SCORE ARCHITECTURE**

From individual contact scores to account-level MQA score:

Account Engagement Score Formula:
- Account Score = Σ(Contact Score × Role Weight × Coverage Multiplier)
- Coverage Multiplier: increases the account score bonus as more distinct roles engage:
  * 1 role engaged: multiplier = 1.0 (baseline — could be a single researcher)
  * 2 roles engaged: multiplier = 1.25 (signal of coordinated evaluation beginning)
  * 3 roles engaged: multiplier = 1.6 (buying committee formation confirmed)
  * 4+ roles engaged: multiplier = 2.0 (full committee evaluation underway — highest priority)

Committee Completeness Score (0-100%, separate from engagement score):
- Formula: (Distinct buying roles with at least 1 engaged contact / Total required roles for segment) × 100
- Example: Mid-market with Economic Buyer + Champion + Technical Evaluator engaged out of 5 required roles = 60% completeness
- MQA requires both Committee Completeness ≥ 60% AND Account Engagement Score above threshold

Third-Party Intent Overlay:
- 6sense or Demandbase buying stage "Awareness" or "Consideration": no MQA impact but flag account for nurture sequence targeting all identified decision-maker personas
- Buying stage "Decision" or "Purchase": add 25 points to Account Engagement Score AND reduce Committee Completeness requirement from 60% to 40% (intent data compensates for incomplete coverage)
- G2 competitor profile visits by known contacts: add 20 points per committee member who visits G2, flag account as "competitive evaluation in progress" in CRM

**4. MQA THRESHOLD DESIGN BY SEGMENT**

Mid-Market MQA Criteria (trigger routing when ALL conditions met):
- Committee Completeness Score ≥ 60% (at least 3 of 5 roles engaged)
- Account Engagement Score ≥ 70 (aggregate engagement above conversion-predictive threshold)
- At least 1 high-intent signal from Economic Buyer in last 30 days (prevents false positives from Champion-only high engagement)
- Account not currently in active deal (check CRM for open opportunities — route to AE for expansion tracking if existing opportunity exists)

Enterprise MQA Criteria (more stringent due to longer cycle and higher investment):
- Committee Completeness Score ≥ 70% (at least 4 of 6 roles engaged)
- Account Engagement Score ≥ 80
- Economic Buyer signal in last 21 days (tighter recency window — enterprise evaluation windows move fast once Economic Buyer engages)
- 6sense or Demandbase buying stage "Consideration" or "Decision" (intent data confirmation required for enterprise threshold to prevent wasting strategic AE capacity)

Override Conditions (trigger MQA immediately regardless of completeness):
- Any committee member submits demo request or requests pricing conversation: immediate MQA regardless of committee coverage (explicit hand-raise overrides scoring model)
- 6sense "Decision" stage + Economic Buyer engagement score > 40 in last 14 days: route immediately with coverage waiver (closing window detected)
- Competitive signal: known competitor contract renewal within 90 days (from technographic data) + any 2 committee members engaged: route with urgency flag

**5. COMMITTEE COVERAGE GAP DETECTION & AUTONOMOUS ACTIVATION**

Define the AI-agent-managed gap detection workflow:

Gap Detection Logic:
- Trigger: account engagement score crosses 40 (evaluation likely underway) but Committee Completeness < 60%
- Action: identify which required buying roles have NO engaged contacts at the account
- Resolution: autonomous multi-channel activation targeting missing roles at that specific account

Activation Playbook by Missing Role:

Missing Economic Buyer (highest priority gap — deals stall without budget authority):
- LinkedIn ABM campaign: serve personalized ads to VP/C-level titles at target account with Executive-relevant messaging (ROI, strategic impact, peer benchmark data)
- Executive email sequence: from your CEO or VP Sales (not marketing email) — direct, peer-to-peer outreach with a compelling business case hook
- SDR outreach: alert assigned SDR that Economic Buyer is not yet engaged — provide specific messaging for reaching this persona
- Content targeting: retarget all company domain visitors with Economic Buyer-specific content (analyst reports, ROI calculators, executive case studies)

Missing Technical Evaluator (blocks procurement):
- Serve technical content ads: integration documentation, security white papers, compliance certifications
- SDR request: "Can you connect me with your IT/Security team?" outreach to Champion contact
- Email: send Champion a technical evaluation kit (security questionnaire template, API documentation, integration guide) with instructions for sharing internally

Missing End User Influencers (needed for adoption success messaging):
- In-product viral loop activation (if PLG trial exists): invite existing trial users to share with their team
- Email to Champion: "Share this quick-start guide with your [Sales/CS/Marketing] team" — warm introduction to end user stakeholders
- Targeted ads: end-user-specific messaging (ease of use, time savings, individual productivity gains) to individual contributor titles at target account

Gap Closure Tracking:
- Update Committee Completeness Score in real time as new contacts from target account engage
- Alert SDR/AE when previously missing committee member first engages: "New stakeholder identified at [Account]: [Name], [Title] just viewed [Content] — recommend reaching out today"

**6. MQA ROUTING & BUYING COMMITTEE DOSSIER**

What sales receives when an account reaches MQA status:

Buying Committee Dossier (auto-generated at MQA trigger):
- Account overview: company name, industry, size, tech stack (from enrichment), intent data summary
- Committee map: every identified stakeholder with their role classification, engagement history (top 5 behavioral signals with timestamps), and last activity date
- Engagement narrative: "This account has been actively evaluating [Your Product] for 23 days. The Champion ([Name], [Title]) has visited the pricing page twice and attended your [Webinar]. The Economic Buyer ([Name], [Title]) viewed the ROI calculator last Thursday. Technical evaluation appears to be underway — [Technical Evaluator Name] accessed the API documentation page and the security compliance page."
- Recommended first outreach: per stakeholder, a specific opening message based on their engagement history ("Reference that [Economic Buyer Name] viewed the ROI calculator — lead with a personalized ROI analysis for their company")
- Competitive context: any competitive signals detected (competitor comparison page visits, G2 activity), recommended competitive messaging
- Relevant case studies: 2-3 customer success stories pre-selected for their industry and company size

Routing Rules:
- Mid-market MQA with ACV < $50K: route to SDR for qualification call → AE. SDR SLA: 2-hour acknowledgment, contact attempt within 4 hours
- Mid-market MQA with ACV $50K-$150K: route directly to senior AE + notify SDR for support. AE SLA: 1-hour acknowledgment, same-day outreach to Champion contact
- Enterprise MQA: route to Enterprise AE + notify VP Sales for strategic support. AE SLA: 30-minute acknowledgment, AE + SDR coordinated account-level outreach within 2 hours
- Existing customer: route to CSM for expansion conversation, flag for marketing-assisted expansion campaign

**7. AI AGENT AUTOMATION ARCHITECTURE**

Real-Time Account Score Agent:
- Trigger: any contact at a known company record engages (page visit, form fill, email click, demo registration)
- Action: identify contact's buying role, apply role-weighted score, recalculate account engagement score and committee completeness, check MQA threshold, trigger routing if criteria met
- Latency: account score update within 60 seconds of triggering event

Committee Gap Detection Agent (runs continuously):
- Trigger: account engagement score crosses 40 AND committee completeness < 60%
- Action: identify missing roles, launch gap-specific ad campaigns (update audience in 6sense/LinkedIn Campaign Manager), queue SDR alert with recommended gap-closing talk track
- Monitoring: re-check committee completeness daily; close gap activation when missing role first engages

MQA Routing Agent:
- Trigger: account crosses MQA threshold (completeness + engagement score + recency requirements all met)
- Action: generate buying committee dossier, create CRM opportunity or MQA task, assign to correct AE/SDR based on routing rules, send routing notification with dossier attached, create individual tasks for reaching each uncontacted committee member
- SLA tracking: monitor first response time; escalate to manager if SLA missed

Monthly Model Recalibration Agent:
- Input: MQA-to-closed-won deals from prior 90 days with full committee coverage and engagement score history
- Analysis: which committee configurations (role combinations) correlated with highest win rates; which roles were most predictive of close; what engagement score thresholds predicted conversion
- Output: recommended adjustments to role weights, MQA thresholds, and coverage requirements; auto-apply adjustments within ±10% of current values; flag larger changes for quarterly review

**8. MEASUREMENT & CLOSED-LOOP ANALYTICS FRAMEWORK**

Primary MQA Performance KPIs (weekly):
- MQA volume by segment (mid-market vs. enterprise) and coverage tier (how many roles engaged)
- MQA-to-opportunity conversion rate by committee completeness score band
- MQA-to-closed-won rate by committee configuration (which role combinations win most)
- Average committee completeness score at time of close vs. time of MQA
- Gap activation effectiveness: % of accounts where gap detection activated a missing role within 30 days

Secondary KPIs (monthly):
- Committee coverage vs. deal velocity: accounts with 4+ roles engaged close X days faster than 2-role accounts
- Role-specific influence: which committee role's engagement is most predictive of MQA-to-close conversion
- Intent data lift: MQA accounts with 6sense "Decision" stage convert at what rate vs. non-intent-confirmed MQAs
- False positive rate: MQAs that sales rejected or never advanced to opportunity

Quarterly Model Audit:
- Win-deal committee analysis: map full committee engagement history of all closed-won deals from prior quarter; identify which role configurations correlated with highest win rates
- Lost-deal analysis: identify committee patterns in closed-lost deals — which roles were NOT engaged that might have changed outcome
- Threshold recalibration: adjust MQA completeness and engagement thresholds based on current conversion data
- New role identification: identify emerging buyer personas at won accounts (new titles appearing in buying process) and add to committee taxonomy

---

## Example Input/Output

**Input Example:**

Company: Chorus.ai (acquired by ZoomInfo) — conversation intelligence platform for sales teams
ACV: $28,000 mid-market, $120,000 enterprise
Buying Cycle: 38 days mid-market, 95 days enterprise
Typical Committee: VP Sales (Economic Buyer), Sales Enablement Manager (Champion), IT Director (Technical Evaluator), 3-5 Account Executives (End User Influencers)
Current State: 8% MQL-to-pipeline rate; sales rejects "most MQLs because they're individual AEs downloading content — no budget authority, no urgency"

**Output Example (excerpt):**

**Buying Committee Role Map for Chorus.ai:**

Economic Buyer Titles (weight multiplier: 1.5×):
- VP Sales, SVP Sales, Chief Revenue Officer, Chief Sales Officer, VP Revenue
- At SMB (<100 employees): Head of Sales, Director of Sales, Sales Manager (often dual-role as Champion)
- Score their engagement 50% higher than identical signals from non-Economic Buyer contacts

Champion Titles (standard weight):
- Sales Enablement Manager, Director of Sales Enablement, VP Sales Enablement
- Sales Operations Manager, Revenue Operations Manager, VP Sales Operations
- These contacts typically discover Chorus through peer communities (Pavilion, RevGenius) and drive internal evaluation

Technical Evaluator Titles (weight multiplier: 1.2×):
- IT Director, VP IT, CTO (at smaller companies), CISO
- Data Privacy Officer (GDPR/CCPA compliance review — critical at European companies)
- Security Engineer or IT Security Lead

Root Cause of 8% MQL-to-Pipeline Rate:
Current model routes individual AE contacts (end user influencers with zero budget authority) as MQLs the moment they download a template. Fix: implement committee completeness gate. No account routes to sales unless Economic Buyer is engaged. Result: MQL volume will drop by ~55%, but expected MQA-to-pipeline rate should reach 35-45% — producing more total opportunities from fewer, better-qualified accounts.

MQA Threshold Recommendation for Chorus.ai (mid-market):
- Minimum: VP Sales OR CRO engaged (Economic Buyer required — hard gate) + 1 additional committee member
- Standard MQA: VP Sales + Sales Enablement/Sales Ops + 1 other role = 3 roles, Aggregate Score ≥ 65
- Priority MQA: VP Sales + Sales Enablement + IT Director + 1+ AE influencer = 4 roles, Aggregate Score ≥ 80 — route directly to senior AE, skip SDR

Buying Committee Dossier Example (at MQA trigger):
> **Account: Acme Tech (Salesforce, 350 employees, B2B SaaS, Chicago)**
> Committee Status: 3 of 5 roles engaged | Aggregate Score: 74 | MQA Tier: Standard
>
> | Stakeholder | Role | Last Activity | Engagement Score |
> |------------|------|--------------|-----------------|
> | Jennifer Walsh, VP Sales | Economic Buyer | Viewed ROI Calculator 3 days ago | 38 |
> | Marcus Rivera, Sales Ops Manager | Champion | Downloaded "2025 Sales Coaching Benchmark Report," attended Dec webinar | 52 |
> | (Not yet identified) | IT Director | — | — |
>
> **Missing Role Alert:** IT Director not yet engaged. SDR to request connection via Marcus Rivera: "Marcus, who handles IT security review for software evaluation at Acme? I'd love to get them the compliance documentation early so it doesn't slow down your evaluation."
>
> **Recommended First Outreach (Jennifer Walsh, VP Sales):**
> Reference: "Jennifer, Marcus has been exploring how Acme could use call intelligence to improve new rep ramp time. I noticed you visited our ROI calculator — happy to run a customized analysis based on your team size. Companies your size typically see 28% improvement in quota attainment in the first 6 months."

## Success Metrics

**MQA Model Performance:**
- MQA-to-opportunity conversion rate ≥ 30% within 60 days of deployment (vs. typical MQL-to-pipeline of 8-15%)
- Sales team MQA accept rate ≥ 85% (AEs accept the account-level handoff vs. returning to marketing as unqualified)
- Average committee completeness score at closed-won ≥ 70% (confirms higher-coverage accounts close more reliably)
- Gap activation success rate ≥ 35%: accounts where gap detection fires should show missing role engaged within 30 days in at least 35% of cases

**Revenue Impact:**
- Deal velocity: accounts entering pipeline as MQA (vs. historical MQL) close 20-35% faster due to higher committee alignment at handoff
- Win rate: accounts with 4+ committee roles engaged win at 2× the rate of 2-role accounts — track this correlation monthly
- Pipeline value: despite fewer MQAs than historical MQLs, total pipeline value generated should equal or exceed prior baseline within 90 days due to higher conversion rate

**Model Health (monthly):**
- Committee completeness distribution: monitor that MQAs are not clustering at the minimum threshold (60%) — healthy model should show average completeness at 72-78%
- False positive rate ≤ 20%: MQAs that sales never advances to opportunity within 60 days
- Coverage multiplier effectiveness: account scores in the 1.6× and 2.0× multiplier tiers should convert at meaningfully higher rates than 1.0× accounts — confirms coverage multiplier is calibrated correctly

## Related Prompts
- [AI-Powered B2B SaaS Predictive Lead Scoring Architecture & Revenue-Qualified Pipeline Management Intelligence Engine](./AI-Powered-B2B-SaaS-Predictive-Lead-Scoring-Architecture-&-Revenue-Qualified-Pipeline-Management-Intelligence-Engine.md)
- [AI-Powered B2B SaaS MQL-to-MQA Transformation & Account-Based Pipeline Qualification Revenue Intelligence Engine](../Account-Based-Marketing/AI-Powered-B2B-SaaS-MQL-to-MQA-Transformation-&-Account-Based-Pipeline-Qualification-Revenue-Intelligence-Engine.md)
- [ABM Intent Data Activation & Buying Signal Prioritization Engine](../Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [AI-Powered B2B SaaS Sales Marketing Revenue Alignment Architecture & Closed-Loop Lead Intelligence Engine](./AI-Powered-B2B-SaaS-Sales-Marketing-Revenue-Alignment-Architecture-&-Closed-Loop-Lead-Intelligence-Engine.md)

## Integration Tips

**Salesforce Integration:**
- Create custom Account fields: `Committee_Completeness_Score` (percent), `Account_Engagement_Score` (number), `MQA_Status` (picklist: Not Qualified / Coverage Gap / MQA Standard / MQA Priority), `MQA_Date` (date/time), `Committee_Roles_Engaged` (multi-select picklist)
- Create custom Contact field: `Buying_Committee_Role` (picklist: Economic Buyer / Champion / Technical Evaluator / End User Influencer / Blocker / Unknown) — populate via Apex trigger using title-matching logic or enrichment tool API
- Build Salesforce Flow triggered when `Account_Engagement_Score` crosses MQA threshold: create MQA Task, assign to correct AE/SDR, attach Committee Dossier via Chatter post with tagged stakeholders
- Use Salesforce Einstein Account Insights or a custom Analytics dashboard to track committee coverage vs. deal velocity correlation monthly

**HubSpot Integration:**
- Use HubSpot Company properties to store Committee Completeness Score, Account Engagement Score, and MQA Status
- Build Contact property for Buying Committee Role using Lists/Workflows: create active lists for each role based on job title contains logic (e.g., "Job Title contains 'VP Sales' OR 'CRO' OR 'Chief Revenue'" → assign Economic Buyer role)
- Build HubSpot Workflow triggered on company score threshold: create Deal (or associated MQA task), rotate to correct sales team using owner rotation, enroll all contacts at company in role-specific post-MQA sequences
- Use HubSpot's Account-Based Marketing tool to track committee engagement at the account level on the Company record timeline

**6sense Integration:**
- Map 6sense buying stage data to your MQA threshold logic: use 6sense's native Salesforce/HubSpot integration to write Buying Stage and Account Score to CRM company record nightly
- Build automation: 6sense "Decision" stage + Committee Completeness ≥ 40% → trigger Priority MQA regardless of engagement score threshold (intent data override)
- Use 6sense Segments to build LinkedIn/G-Display audiences for committee gap activation: create segments for "accounts with Economic Buyer not yet engaged" → serve Economic Buyer persona ads only to VP/C-level titles at those specific accounts
- Leverage 6sense's People Intelligence to identify uncontacted contacts at target accounts who match missing buying committee role personas — import to CRM for gap-closing outreach

**Demandbase Integration:**
- Use Demandbase Orchestration to trigger gap-closing campaign enrollment when account engagement crosses threshold but completeness is below MQA
- Connect Demandbase Account Journeys to your MQA framework: map Demandbase journey stages (Awareness → Consideration → Decision) to your committee completeness requirements (e.g., "Consideration" stage requires Champion engagement; "Decision" stage requires Economic Buyer)
- Use Demandbase Advertising to serve committee-role-specific creative to missing committee member personas at target accounts automatically

**Clay / GTM Engineering Integration:**
- Build a Clay workflow that runs weekly on accounts with Engagement Score > 40 and Committee Completeness < 60%: enrich account with ZoomInfo company data, identify likely Economic Buyer and Technical Evaluator contacts not yet in CRM, push new contacts to CRM with Buying Committee Role pre-assigned, enroll in gap-closing outreach sequence via Outreach.io or Salesloft

## Troubleshooting

**Problem: MQA volume is extremely low after implementing committee completeness requirements — sales pipeline is now empty.**
Solution: Committee completeness thresholds are almost certainly too strict. Pull a cohort of your last 30 closed-won deals and trace back how many distinct buying committee roles engaged before they became an opportunity (not before they closed). For most B2B SaaS companies with ACVs under $75K, the actual purchase decision involved 2-3 engaged contacts, not 4-5. Recalibrate your "minimum roles engaged" requirement to match your won-deal reality, not an idealized buying committee model. If your won deals show 2.3 average engaged roles at opportunity creation, set your MQA completeness minimum at 2 roles (40% for a 5-role committee) and raise the engagement score threshold to compensate.

**Problem: The Economic Buyer role is never engaging — all activity comes from Champions and end users, so accounts never reach MQA.**
Solution: This is the most common failure mode. Economic Buyers don't consume marketing content the same way Champions do — they rely on internal recommendations, peer referrals, and point-in-time research. Fix in three ways: (1) Lower the Economic Buyer engagement score required to "count" for committee completeness — any single high-intent signal from an Economic Buyer title (pricing page, ROI calculator, case study for their industry) counts as "engaged" even if their overall score is low. (2) Implement executive ABM advertising targeting VP/C-level titles at your MQA-candidate accounts with point-in-time research-style content (benchmark reports, analyst findings). (3) Enable Champion-to-Economic-Buyer internal referral tracking — when a Champion downloads your "How to Build the Business Case for [Your Product]" document, they are actively working to bring their Economic Buyer into the evaluation. Score that signal as a partial Economic Buyer engagement signal for the account.

**Problem: Sales is receiving MQA alerts but not acting on them — accept rate is below 50%.**
Solution: The buying committee dossier is not actionable enough or the committee completeness definition is wrong for your market. First, interview 5 AEs who rejected recent MQAs: ask specifically what information was missing that would have made them engage immediately. Common answers: "I didn't know who to call first," "The account looked similar to one I'd already tried 6 months ago," "The committee coverage data wasn't specific enough — I didn't know if the 'Champion' was a decision-influencer or just a researcher." Fix: redesign the dossier to answer these specific questions. Second, check if your role taxonomy is mapping correctly — if "Champion" is being assigned to individual contributors who have no internal selling authority, MQAs will systematically look less compelling than they should be. Tighten your title-to-role mapping rules.

## Version History
- v1.0: Initial creation (auto-generated)
