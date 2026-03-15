# ABM Campaign Orchestration & Account Intelligence Engine - Run Surgical Multi-Channel Campaigns Against Your Best-Fit Accounts

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** abm, account-based-marketing, b2b, demand-gen, intent-data, personalization, enterprise, pipeline, ai-automation, orchestration

## Overview
Designs and orchestrates end-to-end Account-Based Marketing campaigns against a defined target account list — from account tiering and buying committee mapping through personalized multi-channel activation, intent signal monitoring, and revenue attribution. Use this when you need to focus marketing investment on specific high-value accounts rather than broad-based demand generation, or when your ACV exceeds $50K and sales is asking marketing to "work the accounts we care about."

## Quick Copy-Paste Version

You are a senior ABM strategist with deep expertise in B2B enterprise pipeline generation. I need to design and run a complete Account-Based Marketing campaign for my company.

My context:
- Company: [e.g., Vanta AI — B2B SaaS for AI governance and compliance automation]
- ICP and target accounts: [e.g., 50 enterprise accounts: Fortune 1000 financial services and healthcare companies with active AI initiatives, $5B+ revenue]
- Average deal size: [e.g., $180K ACV]
- Sales cycle: [e.g., 6-9 months, 8-12 stakeholders in buying committee]
- Core value prop: [e.g., automates AI risk assessments and regulatory compliance workflows for companies deploying LLMs in regulated industries]
- Current ABM maturity: [e.g., we run some LinkedIn ads against named accounts but have no formal program]
- Available signals/data: [e.g., 6sense intent data, Salesforce CRM, HubSpot marketing automation, ZoomInfo for contacts]
- Sales + marketing alignment: [e.g., aligned on top 50 accounts; weekly pipeline reviews]

Please build me a complete ABM Campaign Orchestration System:

1. ACCOUNT TIERING & PRIORITIZATION
   - Tier 1/2/3 account segmentation criteria based on fit score + intent signals + pipeline stage
   - Engagement scoring model: which account behaviors trigger tier upgrade vs. downgrade
   - Buying committee map template: the 6-10 roles to identify per account (champion, economic buyer, legal/security, end users, IT, procurement)
   - Account intelligence brief template: what to research per account before launching activation

2. MULTI-CHANNEL CAMPAIGN ARCHITECTURE
   - Channel mix per tier: what to run for Tier 1 vs. Tier 2 vs. Tier 3 accounts (LinkedIn ads, programmatic display, direct mail, personalized video, executive events, cold outreach)
   - Campaign sequence: the 90-day activation cadence from first touch to sales-ready signal
   - Message-to-persona mapping: how to customize messaging for each buying committee role
   - Personalization depth framework: account-level vs. persona-level vs. individual-level personalization and when to invest in each

3. CONTENT & CREATIVE STRATEGY
   - Content mapping by buyer stage and persona: what assets work for awareness vs. consideration vs. decision
   - Account-specific personalization templates: how to adapt hero messaging, case studies, and landing pages for each target vertical
   - Executive engagement content: C-level specific formats (benchmark reports, exec roundtable invites, custom ROI models)
   - Intent-activated content triggers: which content to serve when 6sense shows an account researching specific topics

4. SALES + MARKETING ORCHESTRATION
   - Account hand-off criteria: what "marketing-ready" looks like before SDR outreach
   - Account engagement score → SDR sequence trigger automation
   - Weekly ABM sync template: what data marketing shares with sales on each target account
   - Warm outbound play: how to use marketing engagement data to help SDRs personalize their first touchpoints

5. MEASUREMENT & ATTRIBUTION
   - ABM-specific KPIs: account engagement rate, pipeline influence %, deal velocity, win rate for ABM vs. non-ABM accounts
   - 90-day milestone targets for a new ABM program
   - Attribution model: how to credit ABM touches in a long, multi-stakeholder deal cycle
   - Executive ABM report template: what the CRO and CMO need to see monthly

Output in structured markdown with specific templates, sequences, and copy I can use immediately.

## Advanced Customizable Version

ROLE: You are a B2B ABM architect and revenue strategist with 15+ years of experience designing account-based programs for enterprise SaaS companies. You have run ABM programs that generated 3-5x higher win rates and 40-60% larger deal sizes compared to traditional demand gen. You understand both the strategic architecture (how to design a scalable, tiered ABM system) and the tactical execution (how to personalize LinkedIn ads, orchestrate SDR + marketing sequences, and attribute revenue across a 9-month deal cycle with 10 stakeholders).

CONTEXT:
Company name and description: [Company name — 1-sentence product description]
Target market: [Industry verticals, company size, geography]
ICP definition: [Job title of primary buyer, company characteristics, triggering event]
Average contract value: [ACV]
Sales cycle length: [Average days/months to close]
Buying committee: [Number of stakeholders typically involved; key roles]
Current pipeline sources: [% of pipeline from inbound, outbound, events, referral]
ABM maturity today: [None / Early (named account lists) / Developing (some personalization) / Advanced (full orchestration)]
Tech stack available: [CRM, MAP, intent data provider, ABM platform, ad platforms, sales engagement]
Target account list size: [Number of total target accounts]
Sales team structure: [Enterprise AEs, SDRs/BDRs, CSMs, SEs — relevant to orchestration design]
Revenue target this year: [Total pipeline target; ABM-influenced pipeline target if known]
Biggest ABM challenge: [e.g., "sales won't use the content we create" / "no intent data" / "can't personalize at scale" / "no buy-in from execs on target accounts"]

OBJECTIVE: Design a complete Account-Based Marketing orchestration system that:
1. Segments and prioritizes target accounts using fit + intent + engagement scoring
2. Maps full buying committees and identifies personalization requirements per account tier
3. Orchestrates synchronized, personalized multi-channel campaigns per account
4. Creates a tightly integrated sales + marketing activation sequence
5. Measures pipeline influence and revenue attribution across the full deal cycle

ABM ARCHITECTURE FRAMEWORK:

LAYER 1: ACCOUNT INTELLIGENCE & TIERING
Apply the "Account Fit × Intent × Engagement" (FIE) scoring model:

Fit Score (0-100) — how closely the account matches your ICP:
□ Firmographic fit: industry, revenue, employee count, geography — weight 30%
□ Technographic fit: current tech stack, incumbent vendors, integration potential — weight 25%
□ Strategic fit: active digital transformation initiatives, funding events, regulatory pressures — weight 25%
□ Historical fit: similar companies already won, expansion potential, reference-ability — weight 20%

Intent Score (0-100) — signals the account is in-market:
□ First-party intent: website visits, content downloads, pricing page views, demo requests from account domain
□ Third-party intent: G2 category research (Bombora, G2 Buyer Intent), review site comparisons, industry publication consumption
□ Trigger events: new funding, leadership hire in buyer role, job postings for your category, earnings call keywords, press releases
□ Competitive intent: researching or using named competitors (via 6sense, Bombora, G2)

Engagement Score (0-100) — depth of current relationship:
□ Contact coverage: % of buying committee identified and contacted in CRM
□ Multi-thread depth: number of distinct stakeholders engaged in last 90 days
□ Recency and velocity: time since last meaningful interaction; are engagements accelerating?
□ Content consumption depth: top-of-funnel awareness vs. bottom-of-funnel evaluation content consumed

Tier Assignment:
□ Tier 1 (1:1 ABM): FIE composite score >80; treat like an individual micro-campaign; fully personalized content, dedicated budget, AE + SDR + marketing pod assigned; 15-25 accounts max per AE
□ Tier 2 (1:Few ABM): FIE score 60-79; cluster 10-20 accounts by vertical/use case and run semi-personalized campaigns; shared playbooks with account-level customization layer
□ Tier 3 (1:Many ABM): FIE score 40-59; programmatic ABM using audience targeting and vertical-level messaging; automated sequences with light personalization tokens

LAYER 2: BUYING COMMITTEE ARCHITECTURE
For each target account, map and engage all stakeholders before the deal formally opens:

Standard Enterprise Buying Committee (8-10 roles):
□ Economic Buyer (CFO, CEO, or functional VP): owns budget approval; cares about ROI, risk reduction, strategic alignment
□ Champion (primary internal advocate): usually the pain owner; cares about solving their problem and career advancement
□ Technical Evaluator (IT, Security, Engineering lead): cares about integration, security, scalability, implementation risk
□ End User Persona (practitioners who will use the product daily): cares about workflow fit, ease of use, training burden
□ Legal / Compliance / Risk: cares about regulatory compliance, data handling, contractual terms
□ Procurement / Sourcing: cares about pricing, vendor risk, contract flexibility
□ Executive Sponsor (optional): C-suite who blesses the project; usually engaged late unless you can create top-down pull
□ IT / RevOps / Data (depending on product): cares about integration complexity, data pipeline, admin burden
□ Influencer / Internal champion ally: peer of champion who adds credibility; often a department peer who has already evaluated you
□ Blocker: role you must identify and neutralize (often incumbent vendor ally, budget holder in different priority, or skeptical peer)

Buying Committee Intelligence Brief (per Tier 1 account):
□ Account overview: company strategy, recent news, key initiatives relevant to your category (from 10-K, earnings, press releases, LinkedIn, Glassdoor)
□ Stakeholder-level intelligence per role: name, LinkedIn URL, tenure, past companies, published content/takes, likely pain points
□ Current vendor landscape: what tools they use today in your category (from LinkedIn job postings, BuiltWith, G2 stack)
□ Relationship map: who does the AE know? who has engaged marketing? who is a mutual connection?
□ Personalization angle: the 1-2 unique insights about this account that should anchor all outreach and content

LAYER 3: MULTI-CHANNEL CAMPAIGN ORCHESTRATION
Design the synchronized activation sequence across all channels simultaneously:

Tier 1 (1:1) 90-Day Campaign Architecture:

Days 1-30 (Awareness & Intelligence Gathering):
□ Programmatic display + LinkedIn ads targeting all identified buying committee members (account-level audience)
□ SDR sends introductory LinkedIn connection requests to Champion and Technical Evaluator with personalized note referencing account-specific insight
□ Marketing delivers account-specific landing page (custom URL, company logo, industry-specific messaging, relevant case study)
□ Executive sends personalized video or handwritten note to Economic Buyer referencing specific company initiative
□ Intent monitoring activated: 6sense/Bombora alerts configured for when account researches category keywords

Days 31-60 (Engagement & Multi-Threading):
□ Invite Economic Buyer and Champion to exclusive executive roundtable or advisory dinner in their metro
□ SDR escalates outreach to 3-4 additional buying committee members based on Days 1-30 engagement signals
□ Retargeting ads shift from awareness to consideration: case study ads, ROI calculator CTAs, demo request
□ Account-specific content delivered: custom benchmark report, industry-specific use case brief, or personalized ROI model
□ Sales and marketing sync: review account engagement data, identify hot contacts, adjust outreach personalization

Days 61-90 (Decision Acceleration):
□ Activate customer reference from a similar company for peer validation call
□ Champion enablement: provide internal business case template, ROI model, and objection-handling guides for internal selling
□ Economic Buyer engagement: CFO-to-CFO call or executive briefing on financial impact model
□ Procurement & Legal early engagement: proactively send security documentation, standard contract terms, and compliance certifications
□ SDR and AE co-sell: AE takes over primary relationship while SDR continues multi-threading to ensure no stakeholder goes cold

LAYER 4: CONTENT & PERSONALIZATION MATRIX
Map content to persona × buying stage × account tier:

Content by Persona:
□ Economic Buyer: ROI models, CFO case study (same industry), board-level trend reports, peer benchmarks, risk/compliance narratives
□ Champion: detailed use case content, product deep-dives, implementation guides, practitioner case studies, comparison guides vs. incumbents
□ Technical Evaluator: security documentation, integration architecture diagrams, API docs, technical white papers, pentest reports
□ End Users: product walkthroughs, before/after workflow videos, user community examples, training and onboarding previews
□ Procurement: pricing tiers overview, ROI calculator, total cost of ownership model, contract flexibility documentation

Content by Account Tier:
□ Tier 1: fully custom (account name in hero, industry-specific case study, account-referenced ROI model, AE signature on email content)
□ Tier 2: semi-custom (vertical-specific landing pages, industry persona-matched case studies, personalization tokens in ad copy and email)
□ Tier 3: vertical-level (industry-segmented ad creative, persona-based email copy variants, playbook-driven SDR templates)

Intent Signal → Content Trigger Mapping:
□ Competitor research signal → serve competitive displacement content within 48 hours
□ Pricing page visit → SDR outreach trigger + ROI calculator ad served + pricing-specific email sequence
□ Security documentation download → IT/Security persona follow-up sequence + CSO case study ad
□ "Alternatives to [incumbent]" search signal → displacement one-pager + migration guide delivered via email
□ Multiple stakeholders visiting site in same week → account engagement spike alert to AE + acceleration sequence triggered

LAYER 5: SALES + MARKETING ORCHESTRATION
Design the handoff and collaboration protocol between ABM marketing and sales:

Account Readiness Thresholds (Marketing → Sales trigger):
□ MQA (Marketing Qualified Account) criteria: minimum score thresholds on intent + engagement + contact coverage before SDR activation
□ "Hot Account" alert protocol: when 3+ buying committee members engage in a 7-day window, immediate AE notification
□ Pipeline stage → marketing support map: what campaigns run in each CRM stage (Prospecting → Discovery → Demo → POC → Proposal → Close)

Weekly ABM Account Review (Sales + Marketing):
□ Account engagement report: top 10 most-engaged accounts this week (ranked by FIE score change)
□ New intent signals detected: accounts newly researching your category or competitors this week
□ Stakeholder coverage gaps: accounts where buying committee mapping is <50% complete
□ Content consumed this week: which personas at which accounts consumed what, and recommended follow-up
□ Blockers and deal risks: accounts where engagement has dropped or competitive intent has spiked

LAYER 6: MEASUREMENT & ATTRIBUTION
Define the metrics framework for ABM program performance:

Leading Indicators (weekly/monthly):
□ Account engagement rate: % of target accounts with at least 1 meaningful engagement in last 30 days
□ Buying committee coverage: average % of buying committee identified and engaged per Tier 1 account
□ Intent score trends: average intent score movement across Tier 1 accounts (up/flat/declining)
□ Multi-thread depth: average number of active stakeholders per account engaged in last 30 days
□ Content consumption velocity: content pieces consumed per account per month

Lagging Indicators (quarterly):
□ MQA to opportunity conversion rate: % of MQAs that become active sales opportunities within 90 days
□ ABM pipeline influence: $ pipeline influenced by ABM touches vs. non-ABM accounts
□ ABM vs. non-ABM win rate: compare win rate and ACV for accounts in ABM program vs. control group
□ Deal velocity: average sales cycle length for ABM accounts vs. non-ABM
□ Pipeline ROI: ABM-attributed pipeline / total ABM program spend

Revenue Attribution Model for ABM:
□ Multi-touch account-level attribution: every marketing touch that occurred during the deal cycle gets credited (not person-level last-touch)
□ Influence vs. source distinction: separate "ABM sourced" (marketing created the opportunity) from "ABM influenced" (marketing accelerated an existing opportunity)
□ Control group methodology: run 10-20% of Tier 2/3 accounts with no ABM marketing to measure lift vs. control
□ Time-to-pipeline measurement: track how long it takes accounts to move from MQA to opportunity vs. non-ABM accounts

CONSTRAINTS:
- All orchestration sequences must be executable with a 2-4 person ABM team using AI assistance
- Personalization recommendations must be achievable without custom engineering (use marketing automation tokens, templates, and AI copywriting)
- Attribution model must work with standard Salesforce/HubSpot without custom BI build
- Content recommendations must reuse existing library assets where possible before commissioning new work
- Tier 1 investment per account must be justified by deal size (rule of thumb: invest no more than 5-7% of ACV in pre-opportunity marketing per Tier 1 account)
- Sales team must be able to act on marketing intelligence without attending more than 1 additional meeting per week

OUTPUT FORMAT:
Return a complete ABM Campaign Orchestration Playbook with:
- Account tier assignment scorecard (table with scoring criteria and weights)
- Buying committee map template (roles, what they care about, and engagement approach per role)
- 90-day multi-channel activation calendar for a Tier 1 account (week-by-week with channel, message, and responsible owner)
- MQA scoring model with trigger thresholds
- Weekly ABM account review agenda and data template
- Monthly executive ABM report template (for CRO + CMO)
- ABM program launch checklist (30-day setup plan for a new program)

## Example Input/Output

**Input:**
- Company: Meridian Compliance — B2B SaaS for automated regulatory compliance management
- Target accounts: 60 Tier 1-3 accounts across financial services, healthcare, and energy (regulated industries with $500M+ revenue)
- ACV: $220,000
- Sales cycle: 8-11 months, 9-12 stakeholders
- Current ABM maturity: Early — AEs have named account lists in Salesforce, but no coordinated marketing; demand gen team runs broad LinkedIn campaigns
- Tech stack: Salesforce, HubSpot, Bombora intent data, LinkedIn Campaign Manager, Outreach.io, ZoomInfo
- Biggest challenge: Marketing creates content but sales doesn't know what accounts have seen what; no warm outreach happening based on engagement data

**Output (excerpts):**

**Account Tier Scorecard:**

| Scoring Dimension | Tier 1 Threshold | Tier 2 Threshold | Tier 3 Threshold | Weight |
|---|---|---|---|---|
| Industry fit (Financial Services / Healthcare / Energy) | Perfect match | Secondary match | Adjacent industry | 25% |
| Revenue / size fit ($500M–$10B sweet spot) | $500M–$5B | $5B–$20B or $200M–$500M | $50M–$200M | 20% |
| Regulatory exposure score (active compliance mandates) | High (3+ active) | Medium (1-2 active) | Low (awareness stage) | 25% |
| Bombora intent score (compliance automation keywords) | Score 70+ | Score 45-69 | Score 20-44 | 20% |
| Existing relationship / contact coverage | AE knows champion or sponsor | 1 prior touch in CRM | Cold | 10% |

**Tier 1 Target: Pinnacle Financial Group (assigned to AE: Marcus Webb)**

*Account Intelligence Brief:*
- CFO announced Q1 earnings call focus on "regulatory cost reduction and operational automation" — explicit budget signal
- Chief Compliance Officer (CCO) was just hired from JPMorgan 4 months ago — new CCO means active vendor evaluation window
- Job posting: "Compliance Systems Manager" — signals build vs. buy evaluation in progress
- Bombora: 71/100 intent score this week on "compliance automation," "regulatory reporting software," and "GRC platforms" — 3 weeks of consecutive high intent
- Competitive signal: Research on "RegTech alternatives to Thomson Reuters" — active evaluation of incumbent
- AE connection: Marcus knows VP of Technology from a prior company; has not yet been introduced to the compliance team

*90-Day Tier 1 Activation Calendar (Pinnacle Financial):*

Week 1-2 (Intelligence + Awareness):
- LinkedIn Campaign Manager: Upload contact list of all 12 identified buying committee members; activate account-matched audience; run "Regulatory Cost Reduction" awareness ads (financial services creative variant)
- Programmatic display via Bombora: Meridian display ads follow all Pinnacle IP ranges across financial services publisher network
- AE Marcus: LinkedIn connect to VP Technology referencing prior company + congratulatory note on Pinnacle's Q1 earnings mention of compliance investment
- Marketing: Build account-specific landing page at meridiancompliace.com/pinnacle-financial — financial services hero image, Regions Bank case study (similar profile), CCO-specific messaging about "hitting the ground running"

Week 3-4 (Champion Identification + Warm Signal):
- SDR Sarah: Research CCO (just joined from JPMorgan) — craft 3-touch sequence referencing: (1) Q1 earnings compliance mention, (2) JPMorgan's regulatory approach that CCO would know well, (3) invite to Meridian's private "New CCO Peer Roundtable" virtual dinner in April
- HubSpot intent alert configured: if any Pinnacle email domain visits pricing page or case studies page, immediate Slack alert to Marcus and Sarah with page visited and contact ID if known
- LinkedIn ads shift to consideration: serve "How Pinnacle-Peer [Regions Bank] Cut Regulatory Reporting Time 67%" case study ad to CCO, CFO, and Chief Risk Officer personas
- Bombora monitoring: weekly score check; if competitor research intensifies, activate displacement sequence

Week 5-8 (Multi-Thread Escalation + Executive Engagement):
- New intent spike detected (Week 6): Bombora shows Pinnacle now researching "GRC implementation timeline" — acceleration trigger
- Marcus requests warm introduction from VP Technology to CCO (relationship bridge)
- SDR multi-threads to: General Counsel (legal/compliance buyer), Head of IT Risk (technical evaluator), VP Operations (end user exec)
- Marketing delivers: Personalized ROI model for Pinnacle based on their public filing data (estimated 340 compliance FTEs × industry average automation savings) — sent from Marcus's email, not marketing automation
- CCO accepts roundtable invite — first confirmed contact in buying committee secured
- Executive Sponsor play: Meridian's CEO sends handwritten note to Pinnacle CFO referencing the Q1 earnings call compliance investment mention; includes physical copy of Meridian's "2026 State of Financial Services Compliance Automation" benchmark report

**MQA Trigger Criteria (marketing → SDR handoff):**
An account reaches MQA status when ALL three conditions are met:
1. Account-level intent score ≥65 (Bombora) on 2+ consecutive weeks
2. At least 2 buying committee members identified in CRM with valid contact data
3. At least 1 of: pricing page visit from account IP, content download by identified contact, or campaign ad click-through to the account-specific landing page

**Weekly ABM Review Agenda (30-minute meeting, sales + marketing):**

*Pre-meeting prep (marketing sends 1hr before):*
- Engagement leaderboard: Top 10 accounts ranked by FIE score change in last 7 days
- New intent spikes: Accounts with Bombora score increase >10 points this week
- Content consumed: Which contacts at which accounts downloaded/viewed what this week
- Competitive signals: Any accounts showing competitor research activity

*Meeting sections:*
- 10 min: Hot account reviews (top 3 accounts with highest engagement velocity — what's the next action?)
- 10 min: Stalled accounts (Tier 1 accounts with no engagement in 30+ days — change play or pause?)
- 5 min: New MQAs from Tier 2/3 that graduated to SDR-active this week
- 5 min: Content gaps (what assets does sales need that marketing hasn't built yet?)

## Success Metrics

**Account Penetration:**
- Buying committee coverage rate: >70% of Tier 1 accounts have 5+ identified and engaged buying committee members within 60 days of program launch
- Multi-thread depth: average 3+ active contacts engaged per Tier 1 account (vs. typical 1.2 for non-ABM)
- Account engagement rate: >80% of Tier 1 accounts show at least 1 marketing engagement per month

**Pipeline Generation:**
- MQA-to-opportunity conversion: >35% of MQAs convert to active sales opportunity within 90 days
- ABM-sourced pipeline: ABM program contributes >30% of new pipeline within 6 months of launch
- Tier 1 account pipeline coverage: >60% of Tier 1 accounts have open opportunities within 12 months

**Deal Quality:**
- ABM vs. non-ABM win rate: ABM accounts should show 25-40% higher win rate than comparable non-ABM accounts
- ACV uplift: ABM deals close 15-25% larger than non-ABM deals (due to multi-threaded executive engagement)
- Sales cycle velocity: ABM deals close 20-30% faster than non-ABM (due to pre-educated buying committee)

**Program Efficiency:**
- Cost per opportunity (ABM): Track total ABM program spend ÷ number of new opportunities created; benchmark against CAC for non-ABM inbound
- Pipeline ROI: ABM-influenced pipeline ÷ total ABM spend > 10:1 within 12 months
- Content utilization rate: >70% of ABM content assets used by sales within 30 days of creation

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/Intent-Driven-Account-Prioritization-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/Multi-Channel-Outbound-Sequence-Orchestrator.md`
- `../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Account-Based-Marketing-Analytics-&-Revenue-Intelligence-Engine.md`
- `../../02_Product-Marketing/Sales-Enablement/Sales-Battlecard-&-Competitive-Enablement-Engine.md`

## Integration Tips

**HubSpot:**
- Create a custom "ABM Tier" property on Company object (Tier 1 / Tier 2 / Tier 3 / Not ABM) — this becomes your primary segmentation dimension for ABM campaigns and reporting
- Build a "Buying Committee Coverage" calculated property: count of active contacts per company where Lifecycle Stage = "Sales Qualified Lead" or "Opportunity" divided by target buying committee size (set as a company property)
- Create ABM engagement score workflow: assign points for each account-level engagement (website visit from company IP = 2pts, content download = 5pts, demo request = 20pts, pricing page visit = 10pts) and roll up to Company "ABM Engagement Score" property
- ABM revenue reporting: build a HubSpot report that segments closed-won deals by ABM Tier and shows average ACV, close rate, and sales cycle length per tier — your quarterly ABM ROI proof point
- Warm outbound trigger: create a HubSpot workflow that fires a Slack notification to the assigned AE whenever a contact from a Tier 1 company visits the pricing page or requests a demo, including their name, company, and what content they viewed

**Salesforce:**
- Create a custom "ABM Account Plan" object linked to Account record — stores tier, buying committee map, campaign assignment, and engagement history in one place accessible to AE
- Build "Account Engagement Score" rollup field summing all Campaign Member records with ABM-tagged campaigns in last 90 days
- Create "Buying Committee Coverage %" formula field: (Contacts with ABM role populated ÷ Target buying committee size) × 100
- Opportunity influence tracking: use Salesforce Campaigns with Type = "ABM" to capture every marketing touch on an opportunity, enabling multi-touch influence reporting in the Campaigns tab
- ABM dashboard: build a sales dashboard for AEs showing their Tier 1 account engagement scores ranked, open opportunities, and buying committee coverage gaps — makes ABM data actionable without requiring a separate tool

**6sense / Bombora (Intent Data):**
- Connect intent scores directly to Salesforce/HubSpot Account records via native integration or Zapier — update weekly automatically
- Build automated ABM tier upgrade alert: when a Tier 2 or Tier 3 account's intent score crosses 65, auto-create a Salesforce Task for the assigned AE to review and consider upgrading to Tier 1 treatment
- Intent-activated ad audiences: sync Bombora or 6sense "in-market" account lists directly to LinkedIn Campaign Manager as matched audiences — ensures you're spending media budget only on accounts actively researching your category
- Competitive intent alert: configure a Bombora alert that fires when a target account shows intent on a competitor's brand name — triggers a competitive displacement content sequence within 48 hours

**LinkedIn Campaign Manager:**
- Upload your buying committee contact list (email addresses from Salesforce/HubSpot) as a "Contact List" matched audience — target all identified buying committee members with coordinated ads while SDR sequences run in parallel
- Company-level audience targeting: upload your Tier 1 and Tier 2 account lists as "Company List" audiences — ensures every employee at target companies sees brand awareness campaigns even if individual contacts aren't identified yet
- Campaign structure for ABM: create one LinkedIn campaign per account tier per buyer persona (Tier 1 Economic Buyer, Tier 1 Champion, Tier 2 Technical Evaluator, etc.) — enables persona-specific creative and frequency capping without cross-contamination
- Engagement retargeting: build a LinkedIn retargeting audience of "people who engaged with our company page or ads AND work at a target account" — this is your warmest audience for bottom-of-funnel conversion ads

**Outreach.io / Salesloft (Sales Engagement):**
- Tag sequences by ABM tier: create dedicated Tier 1, Tier 2, and Tier 3 sequences in Outreach with personalization fields that pull account-specific intelligence from Salesforce (company initiative, recent news, marketing content consumed)
- Marketing engagement trigger → Outreach sequence enrollment: use Zapier or native integration to auto-enroll an Outreach prospect in a "warm outbound" sequence when HubSpot fires a high-intent engagement alert
- Sequence coordination protocol: configure Outreach to show marketing campaign membership on each prospect record — SDRs can see which LinkedIn ad, email campaign, or event touchpoints have already occurred before personalizing their first outreach step
- Multi-threading automation: use Outreach's "Account" view to see all active sequences running against contacts at the same company simultaneously — prevents SDR from sending competing messages to different stakeholders at the same account

## Troubleshooting

**Problem: Sales team isn't using the ABM account intelligence marketing provides — they revert to generic outreach and the investment in personalization is wasted**
Fix: The root cause is usually that intelligence is delivered as a PDF report that lives outside the sales workflow. Instead, surface account intelligence directly inside Salesforce/Outreach where reps already work — create a one-paragraph "Marketing Brief" field on the Account record that auto-updates weekly with the top 3 engagement signals and recommended talking point. Build the Tier 1 campaign sequence directly into Outreach as a template sequence so reps just click "start sequence" rather than having to interpret a strategy doc. Run a 30-minute monthly "Deals & Intelligence" call where marketing presents the top 5 engaged accounts with specific outreach recommendations — getting AEs one win from ABM intelligence creates advocates for the program faster than any training.

**Problem: ABM program shows great engagement metrics (clicks, content downloads) but isn't generating pipeline — lots of "awareness" with no opportunities**
Fix: Engagement without pipeline usually means either (1) you're not engaging the right personas (great engagement from end users and practitioners, zero from economic buyers and champions who control budget) or (2) there's no clear path from engagement to a sales conversation. Audit your buying committee coverage: if >60% of engaged contacts are below VP level, your Tier 1 content and outreach is targeting the wrong people. Rebalance LinkedIn ad targeting toward VP+ and C-suite using job seniority filters. Add an explicit CTA for all high-intent engagements — when a contact downloads a CFO-level ROI report, that should trigger a same-day AE outreach with a specific "I noticed you reviewed our ROI framework for companies like yours — I built a 5-minute version for Pinnacle specifically" message rather than a nurture email sequence.

**Problem: ABM program works for the first 30 accounts but can't scale — personalization takes too long and the team is burning out**
Fix: ABM personalization should be applied with precision proportionate to account tier — Tier 1 accounts get 4-6 hours of research and custom content, Tier 2 accounts get 30-45 minutes of personalization using modular templates, Tier 3 accounts get 5-10 minutes using AI-assisted variable substitution. The scaling mistake is applying Tier 1 effort to all accounts. Build a "personalization playbook" with 3 levels: (1) account-specific (custom research, named account content — Tier 1 only), (2) vertical-specific (pre-built content for financial services, healthcare, etc. — Tier 2), (3) persona-specific (role-level messaging templates — Tier 3). Use AI to accelerate Tier 1 research: feed the AI public filings, earnings transcripts, LinkedIn profiles, and recent news, then have it generate the account intelligence brief in 5 minutes rather than 2 hours. This lets your team do Tier 1 treatment for 25 accounts instead of 8.

## Version History
- v1.0: Initial creation (auto-generated)
