# AI-Powered B2B SaaS Community-Led Expansion Revenue Architecture & Champion Network Net Revenue Retention Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** community-led-growth, expansion-revenue, net-revenue-retention, nrr, champion-network, customer-marketing, clg, b2b-saas

## Overview

Designs a full AI-powered system that converts community engagement signals from existing customers into measurable expansion revenue — surfacing upsell triggers, building champion networks, detecting churn risk through disengagement, and orchestrating automated NRR programs. Use this when you have an active community and want to make it your highest-ROI expansion revenue channel.

## Quick Copy-Paste Version

You are a B2B SaaS Community-Led Expansion Revenue strategist. Design a complete system that turns our existing customer community into a net revenue retention (NRR) and expansion revenue engine.

Company: [Your Company Name]
Product: [What you sell — e.g., "workflow automation platform for RevOps teams"]
Current community platform: [Slack / Discord / Circle / Discourse / LinkedIn Group]
Total paying customers: [Number]
Community members who are paying customers: [Number or %]
Current NRR: [e.g., 105%]
NRR target: [e.g., 120%]
Primary expansion motion: [Seat expansion / Usage-based / Tier upgrade / Cross-sell new products]
Average contract value: [e.g., $24,000 ARR]
Renewal cycle: [Monthly / Annual / Multi-year]

Deliver:

1. COMMUNITY EXPANSION SIGNAL MATRIX
   - Behavioral signals that predict upsell readiness (post types, question patterns, usage language)
   - Signals that indicate cross-sell opportunity (mentions of adjacent pain points, integration questions)
   - Early churn warning signals (reduced posting frequency, negative sentiment, competitor mentions)
   - Champion identification signals (content creation, peer teaching, product advocacy behaviors)
   - Priority scoring formula for each signal type (weight by ARR impact potential)

2. CHAMPION NETWORK ARCHITECTURE
   - Champion identification criteria (role seniority + community engagement + product depth)
   - Champion development track (3 stages: Emerging → Active → Executive)
   - Exclusive champion benefits (early access, advisory board, co-marketing, direct PM access)
   - Champion-to-expansion revenue playbook (how champions drive internal buying decisions)
   - Champion health monitoring system (engagement score + relationship strength index)

3. AI-POWERED EXPANSION PLAYBOOK (by scenario)
   - Scenario A — Seat/License Expansion: trigger signals → AI-drafted outreach → CS handoff template
   - Scenario B — Tier Upgrade: feature usage thresholds → upgrade messaging → in-community nudge
   - Scenario C — Cross-Sell New Product: adjacent pain detection → champion briefing → pilot offer
   - Scenario D — Renewal Acceleration: renewal -90 days → champion mobilization → deal risk scoring
   - Scenario E — At-Risk Account Recovery: disengagement alert → re-engagement program → escalation

4. COMMUNITY HEALTH → ACCOUNT HEALTH INTEGRATION
   - Map community engagement score to CRM account health field
   - Bi-directional sync: community platform ↔ Salesforce/HubSpot (field mapping)
   - Weekly community health digest auto-sent to CS team with expansion opportunity flags
   - Segment at-risk accounts by community disengagement level (Green/Yellow/Red)

5. NRR ATTRIBUTION MODEL
   - How to credit community-influenced expansion vs. product-driven vs. CS-driven
   - Community-Influenced Expansion ARR tracking methodology
   - Monthly NRR contribution report template (community sourced + influenced)
   - 12-month NRR forecast model driven by community health leading indicators

6. AUTOMATION WORKFLOWS
   - Champion activity → automatic CRM task created for AE/CS
   - Upsell signal detected → Slack alert to CS + AI-drafted expansion email
   - Community disengagement (7+ days inactive) → automated re-engagement sequence
   - New product announcement → champion briefing auto-deployed 48 hours before public launch

Output for each section: specific trigger criteria, message templates, workflow logic, and success metrics.

## Advanced Customizable Version

ROLE: You are a Senior Community-Led Growth Architect specializing in Post-Sale Revenue Expansion with 15+ years of experience building customer community programs that directly drive measurable NRR improvement. You have scaled CLG-to-expansion programs at B2B SaaS companies from Series B through public company stages. You understand the David Spinks Orbit Model, the Gainsight Community Health framework, and how to build AI-powered listening systems that surface revenue signals from community engagement data before CS teams would otherwise detect them. You know that the most efficient expansion revenue comes from champions who are already evangelizing — your job is to make that evangelism visible, measurable, and sales-activatable.

CONTEXT:
Company: [COMPANY_NAME]
Product category: [CATEGORY — e.g., "Revenue Intelligence," "Legal Operations," "Engineering Collaboration"]
Product description: [2-3 sentences on what you do, the core workflow you own, and the outcome you deliver]
ICP (primary buyer): [ECONOMIC_BUYER_ROLE] at [COMPANY_TYPE/SIZE] in [INDUSTRY]
ICP (primary user): [END_USER_ROLE] — the practitioner who lives in your product daily
Current NRR: [NUMBER]%
NRR target (12 months): [NUMBER]%
Primary expansion levers: [Seat growth / Usage tiers / Module add-ons / Professional services / New products]
Community platform: [PLATFORM] — [AGE] old, [MEMBER_COUNT] members, [CUSTOMER_%]% are paying customers
Community engagement rate: [e.g., "28% monthly active members"]
CS team structure: [e.g., "8 CSMs covering 400 accounts, ratio 50:1"]
CRM: [Salesforce / HubSpot / Other]
Customer success platform: [Gainsight / Totango / ChurnZero / Planhat / None]
Renewal cycle: [MONTHLY / ANNUAL / MULTI-YEAR]
Average days to expansion decision: [e.g., "60-90 days from CS discovery to closed expansion"]

OBJECTIVE: Design a complete AI-powered Community-Led Expansion Revenue system that:
1. Turns community engagement data into predictive expansion signals processed before CS teams detect them
2. Builds and operationalizes a tiered champion network that drives internal purchasing authority
3. Creates automated expansion playbooks triggered by community behavior — without adding CS headcount
4. Integrates community health scores directly into the CRM account health model
5. Produces a defensible NRR attribution model that proves community ROI to CFO/Board

CONSTRAINTS:
- All workflows must integrate with [CRM_PLATFORM] and [COMMUNITY_PLATFORM] via native API or Zapier/Make
- Champion programs must deliver genuine member value (not just extraction) — no fake advisory boards
- Attribution methodology must survive finance scrutiny — conservative multi-touch model preferred
- Expansion motions must be CS-approved before activation — not autonomous cold outreach
- Community disengagement alerts must include context, not just flags — CS needs enough to act intelligently

OUTPUT FORMAT: For each section below, provide (a) strategic design rationale, (b) specific implementation specification with field-level detail, (c) AI prompt templates for automated messaging, (d) success metrics with target benchmarks, and (e) 30/60/90-day rollout milestones.

SECTION 1 — COMMUNITY EXPANSION SIGNAL INTELLIGENCE SYSTEM

Design the AI listening layer that monitors [COMMUNITY_PLATFORM] for revenue signals:

A. UPSELL SIGNAL TAXONOMY
Build a complete taxonomy of community behaviors that predict expansion, organized by signal strength:

Strong Signals (Sales-Ready, route to CS within 48 hours):
- [Specific post pattern]: e.g., "I need this to work for 50 more people on my team"
- [Specific question type]: e.g., "Do you support SSO/SAML for enterprise?" (signals security review)
- [Specific complaint]: e.g., "We're hitting the 10,000 record limit" (usage ceiling = upsell)
- [Integration ask]: e.g., "[Competitor Product] integration" (signals adjacent tool consolidation)

Medium Signals (Nurture track, CS awareness, follow in 2 weeks):
- High-frequency posting in product-use-case threads (power user behavior)
- Tagging colleagues who aren't community members ("you should check this out")
- Asking for feature comparison between their current plan and higher tier
- Requesting roadmap preview access (high engagement, expansion-minded)

Weak Signals (Monitor, do not activate):
- Asking basic onboarding questions (still in activation phase, not expansion-ready)
- Complaining about missing features (could be churn risk OR expansion opportunity — need triage)
- Mentioning competitor products in general discussion (benchmark signal, not necessarily churn)

B. CHURN EARLY WARNING SIGNAL MATRIX
Build detection logic for at-risk signals:

Critical Warning (CS contact within 24 hours required):
- [Community disengagement pattern]: e.g., "Was top 10% active, now 30+ days silent"
- [Negative sentiment keywords]: list 10-15 specific phrases to monitor
- [Competitor evaluation signals]: e.g., "[Competitor Name] vs [Your Product]" thread started
- [Economic signals]: e.g., "budget freeze," "headcount reduction," "tool consolidation"

C. CHAMPION BEHAVIOR IDENTIFICATION SIGNALS
Define the behavioral fingerprint of a high-value champion:

Tier 1 Champion (Executive Sponsor):
- Budget authority language in posts ("our procurement team," "I approved the contract")
- Strategic use case framing (connects product to business outcomes, not just features)
- Actively defends the product when competitors are mentioned unprompted
- Refers colleagues at peer companies ("I told our CEO at [Other Company] about this")

Tier 2 Champion (Power User / Internal Evangelist):
- Produces tutorial content, templates, or workflow guides for community peers
- Answers other members' questions faster than the support team does
- Requests beta access to new features and provides detailed feedback
- Has been with the company >12 months, high product usage (top 20% by seats used)

D. AI SIGNAL PROCESSING SPECIFICATION
Specify the AI system for monitoring and scoring:

Monitoring frequency: [Real-time for keyword triggers / Daily batch for engagement scoring]
AI model for sentiment analysis: [GPT-4o / Claude / Anthropic API / Gainsight Einstein]
Signal scoring algorithm:
  Score = (Signal_Strength_Weight × 0.4) + (Account_ARR_Weight × 0.3) + (Engagement_Trend × 0.2) + (Role_Seniority × 0.1)
  Threshold for CS alert: Score ≥ 75
Output format for CS alert: [Specific Slack message template with account name, signal, account ARR, renewal date, CSM owner, recommended next action]

SECTION 2 — TIERED CHAMPION NETWORK ARCHITECTURE

Design the champion program that converts community advocates into expansion revenue drivers:

A. CHAMPION IDENTIFICATION AND RECRUITMENT

Identification process:
1. AI-powered scan of community engagement data — identify accounts with >3 Tier 2 champion signals in last 90 days
2. CS review and confirmation — CSM validates behavior and confirms account health (Green accounts only)
3. Outreach sequence — [Provide 3-message sequence from CSM or Community Manager]:
   Message 1 (Day 1 — Personal recognition email): [Template with specific personalization fields]
   Message 2 (Day 3 — Program invitation): [Template with specific benefits listed]
   Message 3 (Day 7 — Onboarding call invite): [Template]

B. THREE-TIER CHAMPION STRUCTURE

Tier 1: Emerging Champion (0-3 months in program)
Eligibility: Identified via signal scoring, CS-approved, account in Green health
Benefits:
  - Private Slack channel with Product team for early feature previews
  - "Community Expert" badge and profile recognition
  - Quarterly virtual roundtable with CPO/VP Product (10-person max)
  - Free certification course + LinkedIn badge
Commitments:
  - 2 community posts per month sharing product use cases
  - 1 customer story interview for marketing (written or video, their choice)
  - 1 peer referral introduction per quarter (warm intro to colleague at ICP company)

Tier 2: Active Champion (3-12 months, meets engagement criteria)
Eligibility: Tier 1 graduation + expansion event OR peer referral that converted
Benefits:
  - Named on public Champion Spotlight page (SEO + career visibility)
  - Speaking opportunity at next user conference or virtual summit
  - Direct access to Product Roadmap preview 60 days before announcement
  - Complimentary seat for 1 colleague (expansion activation, not cost)
  - Beta access to all new features with direct PM relationship
Commitments:
  - Monthly community AMA hosting (30 min, company-supported with prep materials)
  - 1 case study (written or video) per 6 months with quantified ROI metrics
  - Advisory call with Product team quarterly (genuine input, not theater)
  - 2 peer referrals per quarter (warm intros, no cold outreach required)

Tier 3: Executive Champion (12+ months, strategic relationship)
Eligibility: Tier 2 + C-Suite or VP-level + account ARR > [THRESHOLD]
Benefits:
  - Seat on formal Customer Advisory Board (quarterly, in-person preferred)
  - Co-author opportunity on original research report or industry benchmark
  - Executive access: quarterly call with CEO or CRO
  - Early exclusivity on major product announcements (embargo briefing)
  - Speaking slot at industry conferences sponsored by [COMPANY_NAME]
  - Priority SLA and dedicated executive sponsor from [COMPANY_NAME] leadership
Commitments:
  - Advisory Board participation (4x/year, 2 hours each)
  - 1 speaking engagement per year at company-organized event
  - Media availability for press opportunities (2-3 per year, coordinated by PR team)
  - Strategic co-sell: willingness to be referenced in enterprise sales cycles

C. CHAMPION-TO-EXPANSION REVENUE PLAYBOOK

Playbook A — Champion-Sourced Referral to Pipeline:
Trigger: Champion signals peer introduction readiness OR provides organic referral in community
Step 1: Community Manager flags introduction in #champion-slack-channel (internal)
Step 2: AE sends champion-personalized outreach to referral within 24 hours
Step 3: Champion receives automated thank-you + program credit + update on referral status
Step 4: CRM tracks referral as "Champion-Sourced" — attributed in community NRR model
Target: 25% of champion referrals convert to qualified opportunity

Playbook B — Champion as Internal Deal Accelerator:
Trigger: CS identifies expansion opportunity in champion's account
Step 1: CSM reviews champion's community activity for recent internal advocacy signals
Step 2: CSM calls champion (not cold — community relationship exists) to brief on expansion
Step 3: Champion receives internal briefing deck + ROI model template to share with economic buyer
Step 4: Champion facilitates introduction to economic buyer (CFO/COO/procurement)
Step 5: AE runs deal with champion as "internal champion" — weekly check-in during sales cycle
Target: Deals with active champion involvement close 40% faster and at 20% higher ACV

Playbook C — Champion as Renewal Insurance:
Trigger: Account enters Yellow/Red health status
Step 1: CS alert: "Champion account at risk"
Step 2: Community Manager identifies champion's recent community sentiment (positive or negative?)
Step 3a: If champion still positive → Escalation call with champion to understand internal dynamics
Step 3b: If champion also disengaged → Executive sponsor engagement + product intervention
Step 4: Champion receives exclusive roadmap preview showing how roadmap addresses their pain
Step 5: Champion-authored internal memo template provided to help champion make internal case
Target: Accounts with active champions renew at 12% higher rate than non-champion accounts

SECTION 3 — AUTOMATED EXPANSION WORKFLOW ARCHITECTURE

Build the automation layer that scales community-led expansion without CS headcount:

A. WORKFLOW 1 — UPSELL SIGNAL DETECTION TO CS ALERT

Trigger: Community platform detects Tier 1 expansion signal
Step 1: AI processes post/message against signal taxonomy (latency: <5 minutes)
Step 2: Signal scored against account data (ARR, health score, days to renewal, CSM owner)
Step 3: If score ≥ 75: Slack alert sent to CSM + AE with full context package
Step 4: CRM task auto-created: "Community expansion signal — [ACCOUNT_NAME] — Action required 48h"
Step 5: AI drafts contextual expansion email for CSM review (not auto-sent — CSM approves first)

AI-drafted email template (for CSM review):
Subject: [Member First Name] — saw your post about [SPECIFIC_PAIN_MENTIONED] in our community
Body: [Template that references the specific community post, validates the pain, and bridges to expansion solution — conversational, not sales-y]

Step 6: CSM sends or modifies email — response tracked in CRM
Step 7: If no response in 5 days → follow-up prompt sent to CSM

B. WORKFLOW 2 — CHAMPION ENGAGEMENT DECAY ALERT

Trigger: Champion posts 0 times in 21 days (vs. historical average of 2+ per week)
Step 1: System checks account health score in CRM — is this correlated with account risk?
Step 2: Slack alert to Community Manager + CSM: "Champion [NAME] at [ACCOUNT] has gone quiet — 21 days no activity. Account health: [STATUS]. Renewal in [X] days."
Step 3: AI drafts personalized re-engagement message from Community Manager (not CSM — keep personal)
Message: [Template referencing champion's last post topic, asking for their perspective on something new — not product sales]
Step 4: If no response in 7 days → CSM calls champion directly (community relationship context provided)

C. WORKFLOW 3 — NEW PRODUCT ANNOUNCEMENT → CHAMPION ACTIVATION

Trigger: New product or major feature scheduled for release (set manually 72 hours before launch)
Step 1: System identifies all Tier 2 and Tier 3 champions whose accounts don't have the new product
Step 2: Community Manager sends embargo briefing to champions (48h before public announcement)
Step 3: Champions receive "first look" access to test environment
Step 4: Day of launch: champions post authentic community content about what they're seeing (organic, not scripted — give them talking points, not scripts)
Step 5: CS team receives list of champion accounts that tested + champion feedback summary → expansion call talking points
Step 6: Track expansion deals opened within 90 days of launch that had champion pre-briefing — attribute to champion program

D. WORKFLOW 4 — COMMUNITY HEALTH → CRM ACCOUNT HEALTH SYNC

Integration specification:
Data source: [Community platform] API
Sync frequency: Daily at 6 AM UTC
Fields to sync to CRM:
  - community_engagement_score (0-100, rolling 30-day)
  - community_posts_last_30d (integer)
  - community_sentiment_score (positive/neutral/negative, AI-classified)
  - champion_tier (None/Emerging/Active/Executive)
  - community_expansion_signals_last_30d (count)
  - community_churn_signals_last_30d (count)
  - days_since_last_community_activity (integer)

CRM Account Health Score update logic:
  If community_engagement_score drops >30 points in 14 days → flag account for CS review
  If champion_tier = Active or Executive AND community_engagement_score > 70 → +10 points to account health
  If community_churn_signals_last_30d > 2 → trigger automated CS task

SECTION 4 — NRR ATTRIBUTION MODEL

Build a defensible model that proves community's contribution to expansion revenue:

A. ATTRIBUTION METHODOLOGY (Multi-Touch)

Revenue event types to track:
1. Community-Sourced Expansion: Champion directly referred the expansion opportunity to sales
2. Community-Influenced Expansion: Champion was involved in internal advocacy during the sales cycle
3. Community-Signaled Expansion: CS identified expansion opportunity via community signal → closed within 90 days
4. Community-Accelerated Expansion: Deal already in motion, but champion involvement reduced time-to-close by >20%

Attribution weights (for multi-touch model):
  Community-Sourced: 100% community credit
  Community-Influenced: 50% community credit / 50% CS or Product-led credit
  Community-Signaled: 35% community credit / 65% CS credit
  Community-Accelerated: 20% community credit / 80% CS credit

B. MONTHLY COMMUNITY NRR REPORT TEMPLATE

Report structure (auto-generated from CRM + community platform data):
  Month: [MONTH/YEAR]
  Community Health Summary: [Active members, engagement rate, new champion additions]
  Expansion Revenue Attributed to Community: $[AMOUNT]
    - Sourced: $[AMOUNT] ([N] deals)
    - Influenced: $[AMOUNT] ([N] deals)
    - Signaled: $[AMOUNT] ([N] deals)
  Churn Prevention Attributed to Community: $[ARR SAVED] ([N] accounts where community re-engagement preceded renewal)
  NRR Impact: Community-active accounts NRR = [X]% vs. non-community accounts NRR = [Y]%
  Champion Program Metrics: [Tier breakdown, referrals generated, deals influenced]
  90-Day Forecast: Pipeline from community signals = $[AMOUNT] (based on current signal volume × historical conversion rate)

C. CFO-READY NRR PROOF CASE

Annual community ROI summary (for board/CFO presentation):
  Community Program Cost: $[FULLY LOADED COST — staff + platform + events]
  Community-Attributed Expansion ARR: $[AMOUNT]
  Community-Attributed Churn Prevention ARR: $[AMOUNT]
  Total Community Revenue Impact: $[TOTAL]
  Community Program ROI: [X]x
  Accounts with active champions vs. without: [X]% NRR differential

SECTION 5 — 90-DAY IMPLEMENTATION ROADMAP

Days 1-30 (Signal Infrastructure):
- Week 1: Configure community platform API integration → CRM data sync
- Week 2: Deploy AI signal monitoring with expansion signal taxonomy
- Week 3: Train CS team on signal interpretation and community context
- Week 4: Launch champion identification scoring — first champion outreach batch

Days 31-60 (Champion Program Launch):
- Week 5: Onboard first cohort of Emerging Champions (target: 10-15 accounts)
- Week 6: Launch private champion Slack channel, deliver first exclusive briefing
- Week 7: Deploy automated expansion workflow #1 (signal → CS alert → AI-drafted email)
- Week 8: First champion spotlight published, first community AMA hosted by champion

Days 61-90 (Expansion Revenue Activation):
- Week 9: First champion referral pipeline tracked in CRM
- Week 10: Launch Workflow #3 (new product announcement → champion activation) with upcoming release
- Week 11: First community NRR attribution report published for CS/Sales leadership
- Week 12: 90-day retrospective — expansion revenue attributed, champion program ROI calculated, v2 plan

SUCCESS KPIs (by end of Day 90):
- Champions recruited: [TARGET — typically 5-8% of customer base in first cohort]
- Expansion signals processed: [TARGET — depends on community size]
- CS alerts generated: [TARGET]
- Expansion opportunities opened from community signals: [TARGET]
- Community-attributed expansion ARR in pipeline: $[TARGET]
- Community NRR differential established: Champion accounts vs. non-champion accounts

Output everything above with [Company_Name] = [COMPANY_NAME], using realistic numbers for a [COMPANY_SIZE] B2B SaaS company with [CURRENT_NRR]% NRR targeting [TARGET_NRR]%. Include specific integration setup steps for [CRM_PLATFORM] and [COMMUNITY_PLATFORM].

## Example Input/Output

**Input Example:**

Company: Prismatic
Product: Embedded integration platform for B2B SaaS companies (lets software teams build and deploy integrations to customers 10x faster)
Community platform: Slack — 18 months old, 2,400 members, 65% are paying customers
Total paying customers: 310 accounts
Community members who are paying customers: 201 accounts
Current NRR: 108%
NRR target: 125%
Primary expansion motion: Seat expansion + Usage-based (connector volume)
Average contract value: $38,000 ARR
Renewal cycle: Annual
CS team: 5 CSMs covering 310 accounts
CRM: Salesforce

**Output Example (Section 1 excerpt):**

**UPSELL SIGNAL TAXONOMY — PRISMATIC**

**Strong Signals (Route to CS within 48 hours):**

- Post type: "We're building integrations for [10+ specific customer logos]" — signals connector volume expansion approaching
  → CS alert: "License expansion imminent — account using connectors for 10+ customers, approaching Enterprise tier threshold"
  → Recommended action: CSM to review current connector count vs. plan limit, proactively offer Enterprise preview

- Post type: "Does Prismatic support white-labeling the integration marketplace for [CUSTOMER_NAME]?" — signals platform-level expansion
  → CS alert: "Marketplace feature inquiry — evaluate Embedded Marketplace add-on fit"
  → Recommended action: Product demo of Marketplace module scheduled within 5 business days

- Post type: "We need our enterprise customers to be able to manage their own connector credentials" — signals enterprise customer requirement
  → CS alert: "Enterprise feature requirement — customer has enterprise customers with security/compliance needs"
  → Recommended action: CSM to offer Enterprise tier trial (includes admin delegation feature)

**Champion Identification — Prismatic Context:**

*Tier 2 Active Champion detected: Sarah Chen, Staff Engineer, DataRobot (paying account, $52K ARR, renewal in 8 months)*

Community signals identified (last 60 days):
- Answered 14 questions from other community members about Prismatic component design patterns
- Posted 3 detailed workflow tutorials with screenshots (unprompted)
- Tagged 2 colleagues from other companies who then joined the community (organic referral)
- Requested beta access to new OAuth 2.0 component (approved, provided detailed bug reports)
- Responded to competitor thread: "Tried [Competitor] for 2 weeks, came back — the developer experience is genuinely better here"

**Champion Outreach Sequence (Community Manager → Sarah):**

Message 1 (Day 1):
Subject: Sarah — your Prismatic posts are genuinely helping people
Body: "Hey Sarah, I've been watching you in the community and wanted to reach out personally. Your component design pattern posts have been referenced by 8 different members over the past month — that's real impact. I wanted to say thank you on behalf of our entire team. We notice the members who go above and beyond, and you're in a very small group. Would you be open to a quick 15-minute call? I have something specific I'd like to share with you about how we're thinking about the next 12 months. — [Community Manager Name]"

---

**CHAMPION-TO-EXPANSION DEAL: DataRobot**

Trigger: CS expansion signal detected — DataRobot posted about needing integrations for 15 enterprise customers (strong upsell signal)
Account context: $52K ARR / Enterprise Plus plan / 8 months to renewal / Sarah is Active Champion

Step 1: CS alert to Sarah's CSM (Marcus) via Slack:
"🔔 Expansion Signal — DataRobot (Sarah Chen) — $52K ARR
Signal: Posted in #connector-building asking about high-volume connector management for 15 enterprise customers — approaching Enterprise connector volume limit (currently at 82% capacity)
Champion status: Active (Tier 2) — highly engaged, strong sentiment
Renewal: 8 months out
Recommended next step: Schedule expansion conversation — connector volume upgrade + Embedded Marketplace pitch
AI-drafted email ready for your review: [link]"

Step 2: CSM calls Sarah (not cold — references their community relationship):
"Hey Sarah, Marcus here from Prismatic. Saw your post about managing integrations for your enterprise customers — we've actually just hit a milestone on the new Enterprise Connector Management console that I think is directly relevant to what you're building. Got 30 minutes to see it before we announce it publicly?"

Step 3: Sarah previews Enterprise console → validates fit → offers to demo to DataRobot VP Engineering
Expansion outcome: $52K → $89K ARR (+71% expansion) / Closed in 34 days (vs. 78-day average without champion involvement)

## Success Metrics

**Community Expansion Program KPIs:**

- **Champion Penetration Rate**: % of customer accounts with at least 1 identified champion — Target: 8-12% of accounts in first 6 months
- **Community-Attributed Expansion ARR**: Quarterly expansion revenue with community touch in attribution — Target: 15-25% of total expansion ARR within 12 months
- **Champion Account NRR vs. Non-Champion NRR**: Should show 10-20 percentage point NRR differential within 12 months
- **Signal-to-Opportunity Conversion Rate**: % of CS expansion alerts (triggered by community signals) that result in an open expansion opportunity — Target: >30%
- **Time-to-Expansion with Champion**: Days from expansion signal to closed expansion deal for accounts with Active/Executive champions — Target: 30-40% faster than non-champion accounts
- **Community Re-Engagement Save Rate**: % of at-risk accounts (Yellow/Red health) where community re-engagement preceded renewal — Target: >20%
- **Champion Program ROI**: (Community-attributed expansion ARR + prevented churn ARR) / Community program fully-loaded cost — Target: 5-10x within 18 months

**Output Quality Signals:**
- CS team can take action on any generated expansion alert without additional research
- Champion outreach messages pass "would I open this?" test — personal, specific, non-sales-y
- NRR attribution report can be presented to CFO without additional explanation

## Related Prompts

- [`../../04_Demand-&-Lead-Generation-&-Growth/Community-Led-Growth/AI-Powered-B2B-SaaS-Community-Led-Growth-Architecture-&-Member-to-Pipeline-Revenue-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Community-Led-Growth/AI-Powered-B2B-SaaS-Community-Led-Growth-Architecture-&-Member-to-Pipeline-Revenue-Intelligence-Engine.md) — Community architecture for new customer acquisition (complement this prompt for full CLG motion)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-NPS-Signal-Driven-Customer-Advocacy-Activation-&-Promoter-to-Pipeline-Revenue-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-NPS-Signal-Driven-Customer-Advocacy-Activation-&-Promoter-to-Pipeline-Revenue-Intelligence-Engine.md) — NPS-triggered advocacy (can be fed into champion identification scoring)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Renewal-Marketing-Program-Architecture-&-At-Risk-Account-Churn-Prevention-Revenue-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Renewal-Marketing-Program-Architecture-&-At-Risk-Account-Churn-Prevention-Revenue-Intelligence-Engine.md) — At-risk account playbooks (use champion re-engagement as a churn prevention input)
- [`../../05_Analytics-&-Performance/Customer-Lifecycle-Marketing-Analytics/AI-Powered-B2B-SaaS-Customer-Health-Score-Intelligence-&-Proactive-Marketing-Intervention-Architecture-Engine.md`](../../05_Analytics-&-Performance/Customer-Lifecycle-Marketing-Analytics/AI-Powered-B2B-SaaS-Customer-Health-Score-Intelligence-&-Proactive-Marketing-Intervention-Architecture-Engine.md) — Customer health score analytics (integrate community health score as an input)

## Integration Tips

**Salesforce:**
- Create custom object: `Community_Engagement_Score__c` on Account object, synced daily via API
- Build a custom report type: "Accounts with Active Community Champions" — filterable by champion tier, ARR, renewal date
- Flow builder: Trigger CS task when `Community_Churn_Signal_Count__c` increases by 2+ in 7 days
- Dashboard: "Community-Led Expansion Pipeline" — Opportunities with `Community_Attribution__c` field populated

**HubSpot:**
- Custom property: `community_health_score` (Number, company-level) synced via HubSpot API or Zapier
- Workflow: If `community_health_score` drops by 20+ in 14 days → create CS task + enroll in re-engagement sequence
- Contact list: "Active Champions" — auto-updated based on `champion_tier` custom property

**Gainsight / ChurnZero:**
- Map `community_engagement_score` to Customer Health Score as a contributing factor (weight: 10-15%)
- Create Success Plan template: "Community Champion Development" — auto-assigned to accounts where champion is identified
- Cockpit CTA: "Community Expansion Signal" — triggered when API detects Strong signal from account members

**Community Platforms:**
- Circle: Use Circle API → Zapier/Make → Salesforce for member activity sync
- Slack: Orbit.love or Common Room for community intelligence layer, then push to CRM
- Discord: Common Room natively supports Discord + CRM integration
- Discourse: API-based activity pull, batch sync daily

**AI Tooling for Signal Processing:**
- Common Room: Purpose-built for community signal detection → CRM integration, supports champion scoring
- Orbit.love: Community orbit model scoring, integrates with Salesforce and HubSpot
- Clay: For enriching community member profiles with company data before scoring
- Anthropic API / OpenAI API: For sentiment classification and AI-drafted personalized outreach

## Troubleshooting

**Problem: Champion program feels extractive — members are being asked for more than they receive**
Solution: Audit your benefit-to-commitment ratio for each tier. If Tier 1 asks for 2 posts/month and 1 customer story, benefits must include something genuinely scarce (not just a badge). The CPO call with 10 people and early feature preview are genuinely valuable if the CPO actually engages. Test: would the champion participate if there were zero upsell benefits? If yes, program is designed correctly.

**Problem: CS team isn't acting on community signals — alerts are ignored**
Solution: Signal quality problem, not volume problem. Reduce false positives by tightening signal criteria — only generate alerts when score ≥ 80 AND account health is Green/Yellow AND renewal is <12 months. Include a 2-sentence "why this matters to THIS account" context in each alert, not generic signal language. Run 30-day retrospective: which signal types actually converted to opportunities? Remove low-conversion signal types to increase alert signal:noise ratio.

**Problem: Community NRR attribution is being challenged by finance / sales**
Solution: Switch to the most conservative attribution model (only credit Community-Sourced deals at 100%, everything else at 25-35%) and show the differential: champion accounts vs. non-champion accounts NRR over 12 months. The cohort comparison is harder to dispute than deal-level attribution. Document the methodology in a one-pager reviewed and co-signed by Sales Ops and CS leadership before presenting to finance.

## Version History
- v1.0: Initial creation (auto-generated)
