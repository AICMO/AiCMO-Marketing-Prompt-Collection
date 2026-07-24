# AI-Powered B2B SaaS Intent Data Orchestration & Buying Signal Campaign Trigger Architecture Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, intent-data, signal-based-gtm, marketing-operations, demand-gen, account-based, pipeline, automation

## Overview
This prompt engineers a complete intent data orchestration system for B2B SaaS companies — connecting third-party intent signals (6sense, Bombora, G2 Buyer Intent, LinkedIn), first-party behavioral data, and product usage signals into a unified account-level scoring model that automatically triggers the right marketing play, at the right time, for the right account. The output is a deployable signal-to-campaign architecture that eliminates wasted spend on unready accounts and accelerates pipeline from in-market buyers.

## Quick Copy-Paste Version

You are a senior B2B SaaS marketing operations architect specializing in intent data strategy and signal-based GTM execution. Design a complete intent data orchestration system for the company below.

Company: [Your Company Name]
Product: [What your SaaS does — one sentence]
ACV: [Average Contract Value — e.g., $24,000]
Sales cycle: [Typical length — e.g., 90 days]
ICP: [Ideal customer profile — industry, company size, buyer role]
Intent tools available: [e.g., 6sense, Bombora, G2 Buyer Intent, LinkedIn Sales Navigator — list what you have or are evaluating]
CRM: [HubSpot / Salesforce / other]
Marketing automation: [HubSpot / Marketo / Pardot / other]
Current state: [Describe how you currently use intent data, or "not using yet"]

Deliver the following:

1. SIGNAL TAXONOMY
- Define 3 signal tiers: Tier 1 (high urgency, buy now), Tier 2 (active research, 30-90 day window), Tier 3 (early awareness, 90-180 day window)
- For each tier: list 5-8 specific signals to track, the data source for each signal, and the confidence weight (1-10)
- Include both third-party signals (intent data providers) and first-party signals (website behavior, email engagement, product usage, CRM activity)
- Flag signals that require integration work vs. signals available today

2. ACCOUNT-LEVEL INTENT SCORING MODEL
- Build a composite intent score (0-100) formula using weighted signal inputs
- Define score thresholds: Hot (70-100), Warm (40-69), Cold (0-39)
- Specify how scores decay over time (signal freshness logic)
- Explain how to handle conflicting signals (e.g., high Bombora intent + no website visits)
- Include ICP fit overlay: how ICP fit score multiplies or gates intent score

3. CAMPAIGN TRIGGER PLAYBOOK
For each intent tier, define the automated campaign response:
- Trigger condition (score threshold + signal type)
- Channel mix and sequence (ads, email, direct mail, SDR outreach, executive engagement)
- Message angle (what pain/urgency drives each tier)
- Content to serve (specific asset types and topics)
- Sales notification: what to tell the SDR/AE and when
- Exclusion logic (active deals, existing customers, recently contacted)

4. TECHNICAL ARCHITECTURE
- Data flow diagram (in text): how signals flow from source → enrichment → scoring → CRM → campaign trigger
- CRM field requirements: which custom fields, objects, or properties to create
- Marketing automation workflow logic: trigger conditions, branch logic, suppression lists
- Integration requirements: APIs, native connectors, or Zapier/Make.com webhooks needed
- Data refresh cadence: how often scores update and campaigns re-evaluate

5. MEASUREMENT FRAMEWORK
- Define 5 KPIs that prove the system is working
- Attribution model: how to credit intent-triggered campaigns in pipeline
- A/B test design: how to prove intent-triggered campaigns outperform batch campaigns
- Monthly reporting template: what to review in your intent data review meeting

Output everything as structured tables, numbered lists, and workflow logic that can be directly handed to a marketing ops engineer to build.

## Advanced Customizable Version

ROLE: You are the world's foremost B2B SaaS marketing operations architect, combining expertise in intent data strategy, revenue operations, and AI-native GTM systems. You have designed signal-based marketing architectures for companies from Series B ($10M ARR) to pre-IPO ($200M ARR), consistently achieving 3-5x improvement in SDR connect rates and 40-60% reduction in wasted outbound sequence touches by targeting only in-market accounts.

CONTEXT:
Company: [COMPANY_NAME]
Product category: [CATEGORY — e.g., "revenue intelligence platform", "HR tech", "cybersecurity"]
ACV: $[ACV] | Sales cycle: [LENGTH] days | Win rate: [WIN_RATE]%
ICP firmographics: [INDUSTRY], [EMPLOYEE_COUNT] employees, [REVENUE_RANGE] revenue
ICP buying committee: [CHAMPION_TITLE], [ECONOMIC_BUYER_TITLE], [TECHNICAL_EVALUATOR_TITLE]
Primary pain points: [PAIN_1], [PAIN_2], [PAIN_3]
Intent data stack (current or planned): [TOOLS — e.g., "6sense Tier 2, G2 Buyer Intent, Bombora, LinkedIn Sales Insights"]
First-party data sources: [SOURCES — e.g., "HubSpot CRM, website analytics via GA4, product usage via Mixpanel, support tickets via Zendesk"]
CRM: [CRM_PLATFORM] | Marketing automation: [MAP_PLATFORM] | Enrichment: [ENRICHMENT_TOOL — e.g., Clay, Apollo, Clearbit]
Pipeline goal: $[PIPELINE_GOAL] per quarter | Current pipeline coverage: [COVERAGE_RATIO]x
Intent maturity: [MATURITY — "greenfield/no intent program", "have data but not activated", "have system but underperforming"]

PRIMARY OBJECTIVE:
Design a production-ready intent data orchestration architecture that enables [COMPANY_NAME] to detect, score, prioritize, and automatically engage the [NUMBER] highest-probability in-market accounts every week, resulting in measurable improvement in pipeline velocity, SDR efficiency, and marketing-sourced pipeline contribution within 90 days of deployment.

---

PHASE 1 — SIGNAL ARCHITECTURE

1.1 First-Party Signal Inventory
For each first-party signal category, define the specific events to capture, the data source, the CRM/MAP field to write it to, and its intent weight:

Website Signals (weighted 1-10):
- High-intent page visits (pricing, demo request, ROI calculator, comparison pages)
- Engagement depth (scroll depth, time on page, repeat visits, return visits after 7+ days gap)
- Content downloads and gated asset consumption patterns
- Chatbot interactions and intent expressed in chat transcripts
- Job listing tracker visits (if applicable)

Product Signals (if applicable — weighted 1-10):
- Free trial activation and day-1 activation events
- Feature adoption milestones that correlate with conversion
- Usage frequency changes (sudden increase = expansion signal; sudden decrease = churn/competitive evaluation signal)
- Admin portal activity (user provisioning = expansion intent)
- API usage patterns (technical evaluation signals)

CRM/Sales Signals (weighted 1-10):
- Closed-lost account reopening triggers (time since loss, competitor contract end dates)
- Executive relationship changes at target accounts (new buyer title joins)
- Deal velocity changes in current pipeline (stalled deals = needs marketing assist)
- Champion job change alerts (champion left = risk; champion joined new company = new opportunity)
- Support ticket escalation patterns (unhappy = competitive vulnerability signal)

Email/Content Engagement Signals (weighted 1-10):
- Email open patterns (3+ opens in 7 days = active engagement signal)
- Newsletter click behavior on specific topic clusters
- Webinar registration and attendance (especially for competitor comparison topics)
- Content series completion (sequential consumption = research mode)

1.2 Third-Party Signal Inventory
For each intent data provider, define: which specific intent topics to track, how to interpret surge scores, the confidence weighting, and how to validate against first-party data.

[INTENT_PROVIDER_1 — e.g., Bombora]:
- Intent topics mapped to your category: [list 10-15 specific Bombora topics most predictive of in-market behavior for your category]
- Surge threshold that indicates active research (e.g., score > 60 with 2-week surge)
- How to weight Bombora surge when combined with website activity
- Known weaknesses and false positive patterns in your category

[INTENT_PROVIDER_2 — e.g., 6sense]:
- Buying stage definitions and how they map to your internal intent tiers
- Which 6sense segments to build for each ICP firmographic segment
- 6sense predictive scoring model calibration recommendations
- How to pass 6sense scores into CRM for sales visibility

[INTENT_PROVIDER_3 — e.g., G2 Buyer Intent]:
- Specific G2 categories and competitor pages to monitor
- How to interpret category research vs. competitor research vs. your own profile visits
- Buyer contact identification from G2 data (if available)
- G2 signal freshness decay logic

[INTENT_PROVIDER_4 — e.g., LinkedIn Sales Insights]:
- Job posting signals: which titles and keywords indicate buying committee expansion
- Organic content engagement: how to detect engagement with your content vs. competitors
- Connection network signals: new connections between your team and target account contacts

1.3 Signal Confidence & Weight Matrix
Build a complete signal weight table:
| Signal | Source | Raw Weight (1-10) | Decay Period | Confidence Level | Notes |
For each signal, specify:
- How it combines with other signals (additive vs. multiplicative)
- When it overrides other signals (veto signals — e.g., "active customer" always suppresses prospecting triggers)
- When it is invalidated (e.g., "pricing page visit" is invalidated if contact is an existing customer viewing billing)

---

PHASE 2 — COMPOSITE SCORING MODEL

2.1 Account Intent Score Formula
Design the scoring formula:

Base Intent Score = 
  (Third-Party Intent Score × [WEIGHT]%) +
  (First-Party Engagement Score × [WEIGHT]%) +
  (CRM/Relationship Score × [WEIGHT]%) +
  (Product Signal Score × [WEIGHT]%)

Where each component score is calculated as:
[Provide the sub-formula for each component with specific signal inputs and weights]

ICP Fit Multiplier:
- Perfect ICP fit (all firmographic criteria match): score × 1.3
- Strong ICP fit (3 of 4 criteria match): score × 1.0
- Marginal ICP fit (2 of 4 criteria match): score × 0.7
- Poor ICP fit: suppress from all triggered campaigns regardless of intent score

2.2 Score Tier Definitions
Define exactly what each tier means operationally:

TIER 1 — HOT (Score 70-100):
- Signal interpretation: [what pattern of signals creates a score this high]
- Time to purchase estimate: [days/weeks]
- Recommended SLA: [hours to first human touch]
- Primary action owner: [SDR / AE / both]

TIER 2 — WARM (Score 40-69):
- Signal interpretation: [active research, not yet narrowing to shortlist]
- Time to purchase estimate: [30-90 days]
- Recommended action: [marketing nurture + SDR awareness]
- Escalation trigger: [when to move from warm to hot treatment]

TIER 3 — COLD (Score 0-39):
- Signal interpretation: [early category interest or ICP fit with no active signal]
- Time to purchase estimate: [90-180+ days]
- Recommended action: [awareness content, not SDR time]
- Watch list criteria: [signals that would promote to Tier 2]

2.3 Score Decay Logic
Define how scores decrease over time without new signals:
- Tier 1 score without new signals: decays to Tier 2 within [X] days
- Signal freshness windows by type: [specify per signal category]
- Re-entry logic: [what triggers re-scoring after an account goes cold]

---

PHASE 3 — CAMPAIGN TRIGGER PLAYBOOK

For each trigger scenario, provide a complete automated campaign sequence:

TRIGGER 1: NEW TIER 1 ACCOUNT (score crosses 70 for the first time)
Trigger conditions: [exact score threshold and signal combination]
Exclusion logic: [active customers, current open deals, recently sequenced — define lookback window]
Immediate response (0-2 hours):
  - SDR alert: [Slack/email notification template with account intelligence summary]
  - AE alert (if ACV > $50K): [executive briefing template]
  - Account-based ad activation: [which ad audiences to add the account to, which creatives to serve]
Sequence Day 1-3:
  - Channel: [specify]
  - Message angle: [specific urgency/pain to lead with given their intent signals]
  - Content to attach: [specific asset type and topic]
Sequence Day 4-10:
  - Channel escalation: [add direct mail? exec outreach?]
  - Message pivot: [if no response, which angle to try next]
  - Sales/marketing handoff protocol: [criteria for AE to take over from SDR]
Success criteria: [what outcome within X days defines this trigger as effective]

TRIGGER 2: TIER 2 ACCOUNT SHOWING ACCELERATION (2+ new signals in 7 days)
[Same structure as Trigger 1]

TRIGGER 3: CLOSED-LOST ACCOUNT REACTIVATION (intent signal for previously lost deal)
[Same structure — with specific messaging acknowledging relationship history]

TRIGGER 4: CHAMPION JOB CHANGE (known champion joins new company matching ICP)
[Same structure — leverage relationship + introduce to new company]

TRIGGER 5: COMPETITIVE DISPLACEMENT OPPORTUNITY (G2 competitor profile views from ICP account)
[Same structure — lead with displacement messaging and switch offer]

TRIGGER 6: STALLED PIPELINE ACCOUNT (open deal + fresh external intent signal)
[Marketing assist sequence — designed to help the AE unstick the deal]

---

PHASE 4 — TECHNICAL ARCHITECTURE

4.1 Data Flow Architecture
Design the complete technical data flow:

[Signal Sources] → [Collection Layer] → [Enrichment Layer] → [Scoring Engine] → [Activation Layer]

For each layer, specify:
- Tools/platforms used
- Data fields passed between layers
- Error handling and fallback logic
- Data freshness SLA (how often each layer updates)

4.2 CRM Configuration Requirements
Provide the exact CRM fields to create:

Account-Level Fields:
| Field Name | Field Type | Source | Update Frequency | Usage |
- Intent Score (composite)
- Intent Tier (Hot/Warm/Cold)
- Last Score Update Date
- Primary Intent Signal (what drove the score)
- Intent Score History (rolling 90-day log)
- Days at Current Tier
- Competitor Intent Flag (boolean)
- Trigger Campaign Status (which trigger is active)

Contact-Level Fields:
- Individual Engagement Score
- Signal Source Attribution
- Campaign Sequence Enrollment Status

4.3 Marketing Automation Workflow Logic
Define the exact workflow conditions for your MAP:

Workflow: Intent Score Tier Assignment
  Trigger: Account intent score updates
  Branch 1: Score >= 70 → Set Tier = Hot → Trigger Hot Account sequence
  Branch 2: Score 40-69 → Set Tier = Warm → Enroll in Warm nurture
  Branch 3: Score < 40 → Set Tier = Cold → Move to watch list
  Suppression: Active customer = true → Exit all intent workflows
  Suppression: Opt-out = true → Exit all intent workflows
  Suppression: Active deal stage >= [STAGE] → Route to sales-assist workflow only

Provide equivalent workflow logic for each of the 6 campaign triggers defined in Phase 3.

4.4 Integration Requirements
For each integration point, specify:
- Integration method (native connector / Zapier / Make.com / custom API)
- Data fields synced (direction and frequency)
- Authentication requirements
- Estimated implementation effort (hours)
- Priority (P1 = required for launch, P2 = important, P3 = nice to have)

---

PHASE 5 — MEASUREMENT & OPTIMIZATION

5.1 Core KPI Framework
| KPI | Definition | Baseline Target | Stretch Target | Measurement Source |
- Signal coverage rate: % of ICP accounts with at least 1 active intent signal
- Hot account pipeline rate: % of Tier 1 accounts that create pipeline within 60 days
- Intent-influenced win rate: win rate for deals that were Tier 1 at some point in the sales cycle vs. non-intent accounts
- Cost per intent-influenced opportunity: total intent stack cost / intent-influenced opps created
- Signal-to-meeting conversion rate: % of Tier 1 accounts contacted that convert to discovery call
- SDR efficiency ratio: opportunities created per SDR per month (intent-targeted vs. non-targeted cohorts)

5.2 A/B Test Framework
Design a controlled test to prove intent program value:
- Test group: [X]% of Tier 1 accounts receive full intent-triggered sequence
- Control group: [Y]% of same-score accounts receive standard outbound sequence
- Hold-out group: [Z]% of Tier 1 accounts receive NO outreach (pure demand capture)
- Test duration: [minimum duration for statistical significance]
- Success metrics and statistical significance thresholds

5.3 Monthly Intent Review Meeting Agenda
Define a repeatable cadence for optimizing the system:
- Signal performance review: which signals are correlating with pipeline vs. which are false positives
- Score calibration: are Hot accounts actually converting at higher rates? Adjust weights if not
- Campaign performance: which trigger sequences are working? Kill/improve underperformers
- Coverage audit: which high-fit accounts have no intent signal? Expand signal sources
- Competitive intelligence: any new competitor signals appearing in G2/Bombora data?

Output the full architecture as structured tables, workflow pseudocode, and decision trees that a marketing ops engineer can hand to a developer to build within a 2-week sprint.

## Example Input/Output

**Input Example:**

Company: Rivet Analytics — AI-powered financial close management software
Product: Automates the financial close process for mid-market CFOs, reducing close time from 10 days to 3 days
ACV: $48,000 | Sales cycle: 75 days | Win rate: 22%
ICP: Finance/Accounting software companies or mid-market companies (500-5,000 employees, $50M-$500M revenue), buying committee: Controller (champion), CFO (economic buyer), IT Director (technical evaluator)
Intent stack: 6sense (Tier 2 license), G2 Buyer Intent, LinkedIn Sales Insights
CRM: Salesforce | MAP: Marketo | Enrichment: Clay
Pipeline goal: $1.8M per quarter | Pipeline coverage: 2.1x

**Output Example (excerpt):**

**Signal Taxonomy — Tier 1 (Buy Now) Signals:**

| Signal | Source | Weight | Decay |
|--------|--------|--------|-------|
| G2 profile view: Rivet Analytics | G2 Buyer Intent | 9 | 7 days |
| G2 profile view: FloQast, Blackline (competitors) | G2 Buyer Intent | 8 | 7 days |
| 6sense buying stage: Decision | 6sense | 10 | 14 days |
| Demo request page: 3+ visits in 30 days | Website (GA4) | 9 | 14 days |
| ROI calculator completion | Website (Marketo) | 8 | 21 days |
| Bombora surge: "financial close automation" > 65 | Bombora | 7 | 14 days |
| Job posting: "Financial Systems Administrator" or "NetSuite Admin" | LinkedIn | 6 | 30 days |
| Controller or CFO email: 3+ opens in 7 days | Marketo | 7 | 7 days |

**Composite Score Formula for Rivet Analytics:**
Account Intent Score = 
  (6sense Predictive Score × 0.35) +
  (G2 Buyer Intent Score × 0.25) +
  (First-Party Engagement Score × 0.30) +
  (Job Signal Score × 0.10)

ICP Multiplier:
  - Mid-market (500-5K employees) + Finance/Accounting vertical: × 1.3
  - Mid-market + adjacent vertical (healthcare, manufacturing): × 1.0
  - Outside ICP: × 0.5 (suppress from Tier 1 regardless)

**Trigger 1 Output — New Tier 1 Account (Score ≥ 70):**

Within 2 hours:
- Salesforce alert to assigned SDR: "🔴 HIGH INTENT: [Account Name] just hit Intent Score 78. Signals: G2 profile view (Rivet + BlackLine competitor), 2 pricing page visits this week, 6sense buying stage = Consideration. Controller [Name] opened 4 emails in 5 days. Recommend: personalized video outreach today referencing Q[X] close pain."
- LinkedIn audience: Add account to "Tier 1 In-Market" custom audience → serve "Financial Close Pain" creative sequence (3-ad rotation)

Day 1: SDR sends personalized Loom video (2 min) + calendly link. Subject: "Your Q[Q] close — saw you were researching this week"
Day 3: Marketo email from SDR with CFO benchmark report: "How controllers at [Industry] companies cut their close from 10 days to 3"
Day 5: Direct mail triggered via Postal.io — "Close Faster" themed package to Controller address if available
Day 7: SDR calls using talk track: "We noticed [Company] appears to be evaluating financial close solutions — wanted to share how [Similar Company] reduced their close by 65% in 90 days"
Day 10: AE review: if no response, AE sends 1:1 video to CFO directly (LinkedIn + email)

**Salesforce CRM Fields (exact configuration):**
Object: Account
- Intent_Score__c (Number, 18,0) — Updated by 6sense API nightly
- Intent_Tier__c (Picklist: Hot/Warm/Cold/Suppressed) — Formula based on score
- Intent_Score_Updated__c (DateTime) — Last update timestamp
- Primary_Intent_Signal__c (Text, 255) — Top signal driving score
- Competitor_Research_Flag__c (Checkbox) — True if G2 competitor views detected
- Trigger_Campaign_Active__c (Picklist: Trigger1/Trigger2/.../None)
- Intent_Score_30d_High__c (Number) — Rolling 30-day peak score for trend analysis

## Success Metrics

**System Health Metrics (weeks 1-4):**
- Signal coverage rate target: > 40% of ICP accounts have at least 1 active signal within 60 days of launch
- Data quality: < 5% of Tier 1 accounts flagged as existing customers or incorrect ICP
- Workflow execution rate: > 95% of Tier 1 triggers fire within the defined SLA window

**Pipeline Impact Metrics (months 2-3):**
- Tier 1 → Meeting conversion rate: > 15% (vs. typically 3-5% for unscored outbound)
- Intent-influenced pipeline: 20%+ of new pipeline sourced or influenced by intent-triggered campaigns
- SDR efficiency: 30%+ increase in meetings booked per SDR by replacing random outbound with intent-targeted sequences

**Business Impact Metrics (months 3-6):**
- Intent-influenced win rate: 5+ percentage points higher than non-intent pipeline
- CAC reduction: 15-25% reduction in blended CAC from eliminating wasted touches on non-in-market accounts
- Sales cycle compression: 10-15% shorter sales cycles for intent-sourced vs. non-intent-sourced pipeline

## Related Prompts

- [AI-Powered B2B SaaS Inbound Lead Scoring & Revenue Qualified Pipeline Architecture](./AI-Powered-B2B-SaaS-Inbound-Lead-Scoring-&-Revenue-Qualified-Pipeline-Architecture-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Lead Routing & Sales Assignment Architecture](./AI-Powered-B2B-SaaS-Lead-Routing-&-Sales-Assignment-Architecture-&-Revenue-Qualified-Pipeline-Distribution-Intelligence-Engine.md)
- [AI-Powered B2B ABM Intent Data Activation & Buying Signal Prioritization](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [AI-Powered B2B SaaS Signal-Based GTM Transformation (CMO Strategy)](../../01_CMO-&-Leadership/Strategy-&-Planning/AI-Powered-B2B-SaaS-Signal-Based-GTM-Transformation-&-CMO-Led-Revenue-Intelligence-Architecture.md)

## Integration Tips

**6sense Integration:**
- Use 6sense's native Salesforce connector to write account buying stage, segment membership, and predictive scores directly to Account fields
- Set up 6sense Orchestrations to fire webhooks to Marketo/HubSpot when accounts hit buying stage thresholds
- Use 6sense's ad audience sync to automatically add/remove accounts from LinkedIn, Meta, and programmatic display audiences based on intent tier

**Bombora Integration:**
- Sync Bombora Company Surge data weekly via the Bombora Salesforce app or via Clay for enrichment workflows
- Create a Salesforce flow that recalculates the composite intent score whenever Bombora fields update
- Set Bombora topic alerts for your top 10 intent topics to get weekly email digests for manual review

**G2 Buyer Intent Integration:**
- Connect G2's Buyer Intent data to Salesforce or HubSpot via G2's native integrations
- Build separate score fields for "viewed your profile" vs. "viewed competitor profile" signals (different urgency weights)
- Use G2's "buyer insights" to identify which specific contacts at the account are researching — route this to SDR for personalized outreach

**Clay for Enrichment Orchestration:**
- Use Clay as the central enrichment hub: pull 6sense + Bombora + G2 signals into one workflow, enrich with firmographic data from Apollo/Clearbit, then push enriched records to Salesforce and trigger Marketo campaigns
- Build a Clay waterfall that checks LinkedIn job postings for ICP companies weekly, scoring new job postings for buying committee expansion signals

**Marketo/HubSpot Trigger Workflows:**
- Build a "Score Change" trigger: whenever Intent_Score__c changes from below 70 to above 70 in Salesforce, fire a Salesforce Outbound Message to Marketo/HubSpot to enroll the account in the Tier 1 trigger sequence
- Use HubSpot's Operations Hub or Marketo's webhook triggers to keep intent scores in sync in real-time rather than relying on nightly batch syncs

**Postal.io / Sendoso for Direct Mail Triggers:**
- Connect Postal.io to Salesforce via Zapier: when Trigger_Campaign_Active__c = "Trigger1" AND Day_in_Sequence = 5 AND no_reply = true, fire a Postal.io direct mail order automatically

## Troubleshooting

**Problem: Intent scores are high but meeting conversion rates aren't improving**
Solution: Your signal weights are miscalibrated. Run a 60-day retrospective: pull all Tier 1 accounts from the last 60 days and check what % converted to meetings vs. went dark. If < 10% converted, your scoring threshold is too low — raise the Tier 1 floor from 70 to 80, or add a minimum requirement of "at least 1 first-party signal" before an account qualifies as Tier 1 regardless of third-party intent score. Third-party intent without any first-party engagement is a weak signal.

**Problem: SDRs aren't using the intent alerts and are still reaching out to non-intent accounts**
Solution: This is a change management problem, not a technical one. Three fixes: (1) Build the intent score directly into the Salesforce view SDRs use daily — make it impossible to ignore. (2) Create a gamification layer: SDRs who book meetings from Tier 1 accounts get credit at 1.5x the standard rate. (3) Remove non-intent accounts from outbound sequences entirely for a 30-day pilot — force SDRs to work the intent queue. Show them the connect rate data after 30 days.

**Problem: Too many false positives — competitors, students, and analysts are inflating intent scores**
Solution: Build an exclusion list in your intent data provider for known competitor domains, university domains, and analyst firm domains. In Bombora, use the "company type" filter to exclude non-commercial entities. In 6sense, create a "non-ICP" segment that suppresses scoring for any account outside your defined ICP firmographics. Add a "signal validation" step: require at least 2 independent signals from 2 different sources before an account can reach Tier 1 — this filters out single-source noise.

## Version History
- v1.0: Initial creation (auto-generated)
