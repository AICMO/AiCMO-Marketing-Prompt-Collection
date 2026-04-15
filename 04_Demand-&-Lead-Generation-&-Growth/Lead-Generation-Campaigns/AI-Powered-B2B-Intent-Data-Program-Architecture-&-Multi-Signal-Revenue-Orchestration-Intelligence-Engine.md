# AI-Powered B2B Intent Data Program Architecture & Multi-Signal Revenue Orchestration Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** intent-data, demand-generation, b2b, abm, revenue-intelligence, signal-based-gtm

## Overview

Designs and operationalizes a full-stack B2B intent data program: vendor selection, signal taxonomy, composite scoring models, CRM/MAP integration architecture, and cross-channel activation playbooks. Use this when building or scaling a signal-based GTM motion to identify in-market buyers before they raise their hand.

## Quick Copy-Paste Version

You are a B2B revenue intelligence architect with deep expertise in intent data programs, buyer signal orchestration, and signal-based GTM motions.

Build a complete intent data program for my company using the following context:

Company: [Your Company Name]
Product/Service: [What you sell]
ICP: [Target customer profile - industry, size, titles]
Current stack: [CRM, MAP, ABM platform, data tools you use]
Monthly pipeline target: [Pipeline goal]
Current intent data tools (if any): [Tools or "none"]

Deliver:

1. INTENT DATA STACK RECOMMENDATION
   - First-party signals to capture (website, product, email engagement)
   - Second-party signals (G2, TrustRadius, review site intent)
   - Third-party intent vendors to evaluate (Bombora, TechTarget, G2 Buyer Intent, 6sense, Demandbase, etc.)
   - Stack prioritization by ROI-per-dollar

2. SIGNAL TAXONOMY & SCORING MODEL
   - Categorize signals by stage (awareness, consideration, purchase)
   - Assign point values (1-10 scale) with decay curves
   - Define composite account intent score thresholds (cold/warm/hot/urgent)
   - Identify surge signals that override normal thresholds

3. ACTIVATION PLAYBOOKS BY SIGNAL TIER
   For each signal tier (cold/warm/hot/urgent), define:
   - Notification routing (marketing/SDR/AE)
   - Channel activation sequence (email, ads, direct mail, phone)
   - Content/offer to serve at each stage
   - Response SLA for sales follow-up

4. CRM/MAP INTEGRATION BLUEPRINT
   - Field mapping for intent scores in Salesforce/HubSpot
   - Automation triggers and workflow logic
   - Account-level vs. contact-level signal aggregation
   - Data hygiene and signal freshness rules

5. ROI MEASUREMENT FRAMEWORK
   - Leading indicators (account coverage, signal velocity)
   - Lagging indicators (pipeline from intent-sourced accounts, win rate lift)
   - A/B test design to isolate intent data contribution

Output as a structured program document ready to hand to a marketing ops team for implementation.

## Advanced Customizable Version

ROLE: You are a senior B2B revenue intelligence architect and demand generation strategist with 15+ years building intent data programs at high-growth SaaS companies. You have hands-on experience with 6sense, Demandbase, Bombora, TechTarget Priority Engine, G2 Buyer Intent, ZoomInfo Intent, and first-party CDP architectures.

OBJECTIVE: Design a production-ready B2B Intent Data Program Architecture that drives a signal-based GTM motion, enabling marketing and sales to prioritize in-market accounts and activate the right channel at the right time.

COMPANY CONTEXT:
- Company: [COMPANY_NAME]
- Product category: [PRODUCT_CATEGORY] (e.g., "enterprise data security platform")
- ACV range: [ACV] (e.g., "$85K-$400K")
- Sales cycle: [LENGTH] (e.g., "6-9 months")
- ICP firmographics: [INDUSTRY, EMPLOYEE_COUNT, REVENUE_RANGE]
- ICP buyer titles: [PRIMARY_BUYER] and [SECONDARY_INFLUENCERS]
- TAM accounts: [NUMBER] (e.g., "12,000 accounts")
- Current tech stack: [CRM], [MAP], [ABM_PLATFORM], [CDP/DATA_WAREHOUSE]
- Monthly MQL target: [NUMBER]
- Monthly pipeline target: [DOLLAR_AMOUNT]

CURRENT STATE ASSESSMENT:
- Intent data maturity: [none / basic (1 vendor) / intermediate (2-3 vendors) / advanced (full stack)]
- First-party tracking quality: [poor/moderate/strong]
- Sales-marketing alignment on signals: [misaligned/developing/aligned]
- Known gaps: [GAPS]

DELIVERABLE 1: INTENT SIGNAL UNIVERSE MAP

Map every buyer signal across three layers:

FIRST-PARTY SIGNALS (signals you own):
For each signal, specify: signal name | data source | collection method | what it indicates | point value (1-10) | decay window
Include at minimum:
- Website behavioral signals (page visits by topic cluster, time on site, return visits, pricing/demo page views)
- Product signals (free trial actions, in-app feature engagement, usage spikes, seat expansion)
- Email engagement signals (topic-specific open/click patterns, reply sentiment)
- Sales engagement signals (meeting attendance, deck views, proposal opens)
- CRM signals (stage progression velocity, multi-threaded contact adds, legal/procurement involvement)

SECOND-PARTY SIGNALS (signals from partner data):
- G2/TrustRadius/Capterra product views and category searches
- LinkedIn company page engagement
- Industry media site engagement (relevant trade publications)
- Review site competitive comparisons (your product vs. competitors)

THIRD-PARTY INTENT SIGNALS (signals from intent data vendors):
- Bombora Company Surge® topics relevant to [PRODUCT_CATEGORY]
- TechTarget Priority Engine in-market accounts
- G2 Buyer Intent accounts actively researching your category
- 6sense predictive buying stage scores (if applicable)
- Technographic signals (tools being added/removed that indicate buying readiness)
- Job posting signals (hiring patterns indicating [RELEVANT_INITIATIVES])
- News/trigger events (funding rounds, leadership changes, M&A, compliance mandates)

DELIVERABLE 2: COMPOSITE INTENT SCORE ARCHITECTURE

Design a 4-tier account intent scoring model:

SCORING FORMULA:
Composite Intent Score = (First-Party Score × 0.45) + (Second-Party Score × 0.20) + (Third-Party Score × 0.35)

For each tier, specify:
- Score threshold range
- Signal pattern that defines this tier
- Estimated percentage of TAM in this tier at any given time
- Recommended GTM motion
- Expected pipeline conversion rate from this tier

TIER DEFINITIONS:
- COLD (0-29): Define characteristics, signal absence patterns, nurture strategy
- WARM (30-54): Define characteristics, early engagement triggers, marketing-led activation
- HOT (55-79): Define characteristics, sales-assist motion, SLA for SDR outreach
- URGENT (80-100): Define characteristics, AE-direct motion, executive engagement triggers

SIGNAL DECAY MODEL:
Define decay curves for each signal category:
- High-frequency web signals: decay to 50% in [X] days
- Intent topic surges: decay window [X] weeks
- Product trial activity: [X] days until score reset
Include formula for recency-weighted scoring.

SURGE SIGNAL OVERRIDES:
Define 5-7 specific signal combinations that auto-escalate an account regardless of composite score (e.g., pricing page + G2 category search + job posting for relevant role = instant HOT designation).

DELIVERABLE 3: ACTIVATION PLAYBOOKS BY TIER

For each intent tier, design a complete cross-channel activation playbook:

COLD TIER PLAYBOOK:
- Goal: Build awareness and capture first-party signals
- Channel sequence: [Specify timing and channel order]
- Content strategy: [What to serve, not direct sales content]
- Budget allocation per account per month: [Estimate]
- Success metric: Movement from Cold → Warm within [X] weeks

WARM TIER PLAYBOOK:
- Goal: Accelerate consideration and generate MQLs
- Channel sequence: [Specify - typically programmatic + LinkedIn + email nurture]
- Personalization inputs: [Which intent signals drive which content]
- SDR notification: [Trigger for SDR awareness without full sequence]
- Content: [Peer comparison content, ROI calculators, case studies by use case]

HOT TIER PLAYBOOK:
- Goal: Convert to meeting/demo, accelerate pipeline
- SLA: SDR outreach within [X] hours of tier entry
- Multi-channel sequence: [Day 1: email + LinkedIn | Day 2: call | Day 3: direct mail trigger | etc.]
- Personalization depth: [How to use intent topics to personalize outreach]
- AE notification threshold: [When AE gets looped in]
- Air cover: Increase programmatic frequency to [X] impressions/week

URGENT TIER PLAYBOOK:
- Goal: Immediate revenue capture, prevent competitive loss
- Executive involvement: [When and how to involve AE/VP Sales/CEO]
- Channel escalation: [All channels simultaneously with custom messaging]
- Competitive defense: [If competitive intent detected, activate battle card content]
- Response window: [Maximum hours before escalation protocol]

DELIVERABLE 4: TECH STACK INTEGRATION BLUEPRINT

MAP INTEGRATION ([YOUR MAP] - Marketo/HubSpot/Pardot/Eloqua):
- Account scoring object structure
- Field mapping: intent vendor data → MAP fields
- Trigger logic for program enrollment based on tier changes
- Dynamic list definitions for each tier
- Suppression logic (existing customers, current opportunities in late stages)

CRM INTEGRATION ([YOUR CRM] - Salesforce/HubSpot):
- Custom fields: Account Intent Score, Intent Tier, Top Intent Topics (3), Last Intent Update Date, Intent Source, Intent Surge Date
- Account view dashboards for SDRs and AEs
- Workflow rules: tier change → task creation → sequence enrollment
- Reporting objects for intent-to-pipeline attribution
- Lead-to-account matching logic for intent data

INTENT DATA VENDOR INTEGRATION:
For each vendor in your recommended stack:
- API vs. CSV integration method
- Refresh frequency (daily/weekly)
- Data normalization rules (company name matching, domain deduplication)
- Field mapping specifics
- Cost per record/signal and budget allocation

FIRST-PARTY DATA ARCHITECTURE:
- Website visitor identification (IP resolution + cookie + reverse IP)
- CDP event tracking requirements (UTM parameters, behavioral events)
- Account-level aggregation logic (multiple contacts → account score)
- Signal freshness and data hygiene rules

DELIVERABLE 5: MEASUREMENT & OPTIMIZATION FRAMEWORK

PROGRAM LAUNCH METRICS (weeks 1-8):
- Coverage rate: % of TAM accounts with intent scores
- Signal velocity: accounts moving tiers week-over-week
- Activation rate: % of HOT/URGENT accounts contacted within SLA
- Data quality: match rate, coverage gaps by segment

PIPELINE IMPACT METRICS (months 2-6):
- Intent-influenced pipeline: opportunities where account was HOT/URGENT at open date
- Intent-sourced pipeline: opportunities opened within 30 days of tier escalation
- Win rate: intent-qualified accounts vs. non-intent accounts
- Sales cycle compression: days from HOT designation to closed-won

A/B TEST DESIGN:
Design a 90-day holdout test to measure incremental pipeline lift from intent data:
- Control group: accounts that qualified for HOT but received no intent-driven activation
- Test group: accounts that received full HOT tier playbook
- Sample size requirement: [Calculate based on your pipeline volume]
- Success criteria: [X]% lift in pipeline creation rate

QUARTERLY OPTIMIZATION CADENCE:
- Monthly: Score threshold calibration based on conversion data
- Quarterly: Vendor ROI review and budget reallocation
- Bi-annual: Signal universe expansion and scoring model rebuild

OUTPUT FORMAT: Deliver as a structured program document with:
1. Executive summary (2 paragraphs)
2. Signal Universe Map (table format)
3. Scoring model with formulas
4. Activation playbooks (one page each)
5. Integration blueprint (technical spec format)
6. 90-day launch roadmap with owners and milestones
7. Investment summary and expected ROI

CONSTRAINTS:
- All recommendations must be achievable with a team of [TEAM_SIZE] in marketing operations
- Prioritize integrations that work with [CURRENT_STACK] natively before custom builds
- Flag any signals that require legal/privacy review before activation
- Provide vendor cost ranges to inform budget planning

## Example Input/Output

**Input Example:**

Company: Dataforma (B2B SaaS)
Product: AI-powered financial close automation platform
ACV: $120K-$600K
Sales cycle: 5-8 months
ICP: CFOs, Controllers, VP Finance at mid-market and enterprise companies (500-10,000 employees) in manufacturing, professional services, and healthcare
TAM: 18,000 accounts
Current stack: Salesforce, Marketo, LinkedIn Campaign Manager, G2 (no intent data yet)
Monthly pipeline target: $2.8M
Intent data maturity: None

---

**Output Example (excerpted):**

**EXECUTIVE SUMMARY**

Dataforma operates in a high-consideration, long-cycle financial technology category where buyers typically begin researching 6-12 months before a purchase decision. A signal-based GTM motion—anchored in a multi-layer intent data program—can compress this window by surfacing in-market accounts 60-90 days earlier than inbound-only approaches, with projected pipeline lift of 35-55% for intent-activated accounts based on comparable financial automation deployments.

The recommended program combines three intent data layers: (1) first-party behavioral signals from Dataforma's website and Marketo engagement; (2) second-party review site intent from G2 Buyer Intent (financial close automation and ERP categories); and (3) third-party topic surge data from Bombora (12 core topics identified below). Expected Year 1 ROI: 4.2x on a $220K annual intent data investment, based on 110 additional qualified accounts entering pipeline monthly at a 6% close rate.

---

**SIGNAL UNIVERSE MAP (Top 10 Signals)**

| Signal | Source | What It Indicates | Score | Decay |
|--------|--------|------------------|-------|-------|
| Pricing page visit (2+ times/week) | Website | Active evaluation | 9 | 7 days |
| G2 "financial close automation" search | G2 BI | Category-level intent | 8 | 14 days |
| Bombora surge: "financial close software" | Bombora | Research phase | 7 | 21 days |
| Marketo: ROI calculator completion | First-party | Late consideration | 10 | 3 days |
| Job post: "Controller, Financial Systems" | LinkedIn | Tech buying signal | 6 | 30 days |
| Demo video watch (>60%) | Website | Demo-ready interest | 9 | 5 days |
| Bombora surge: "audit automation" | Bombora | Adjacent pain signal | 5 | 21 days |
| G2 Dataforma vs. competitor view | G2 BI | Active comparison | 10 | 7 days |
| Funding round ($20M+) | News API | Budget available | 6 | 60 days |
| NetSuite/Sage add-on search | Technographic | Integration buying | 7 | 14 days |

---

**COMPOSITE SCORE THRESHOLDS**

- **COLD (0-29):** ~72% of TAM. Monthly programmatic-only touch. 180-day nurture cadence. Target: 3-4% monthly progression to WARM.
- **WARM (30-54):** ~20% of TAM (~3,600 accounts). LinkedIn + email nurture. SDR awareness alert at 48. Target: 8% monthly progression to HOT.
- **HOT (55-79):** ~6% of TAM (~1,080 accounts). SDR sequence within 4 business hours. 8-touch sequence over 12 days. Personalized by top intent topic. Target: 12% meeting rate.
- **URGENT (80-100):** ~2% of TAM (~360 accounts). AE-direct outreach within 60 minutes. Executive air cover. All channels activated simultaneously. Competitive battle card triggered if competitor intent detected.

**SURGE OVERRIDE EXAMPLE:**
Account triggers: (G2 Dataforma vs. competitor view) + (Bombora "financial close software" surge > 4x baseline) + (job posting: Financial Systems Manager) = Auto-escalate to URGENT regardless of composite score.

---

**90-DAY LAUNCH ROADMAP**

| Week | Milestone | Owner |
|------|-----------|-------|
| 1-2 | First-party event tracking audit; website visitor identification setup | Marketing Ops |
| 3-4 | G2 Buyer Intent contract and Marketo integration | Marketing Ops + Procurement |
| 5-6 | Bombora topic evaluation; contract and Salesforce integration | Marketing Ops |
| 7-8 | Custom fields in SFDC/Marketo; account scoring model built | Marketing Ops + RevOps |
| 9-10 | HOT/URGENT activation playbooks built in Marketo + Salesloft | Demand Gen + SDR Manager |
| 11-12 | Launch; SDR training; holdout test design signed off | Demand Gen + Sales Leadership |

## Success Metrics

**Data Quality (Week 2-4)**
- Intent coverage rate ≥ 80% of TAM accounts have at least one signal score
- Match rate ≥ 85% for third-party intent vendor records to CRM accounts
- Signal freshness: ≤ 48-hour lag between signal capture and score update

**Activation Quality (Month 1-2)**
- HOT/URGENT SLA compliance ≥ 90% of accounts contacted within defined SLA
- Personalization rate ≥ 70% of outbound touches reference a specific intent signal
- Account coverage: ≥ 40% of HOT accounts have active sales engagement

**Pipeline Impact (Month 3-6)**
- Intent-influenced pipeline represents ≥ 25% of total pipeline within 6 months
- Win rate for intent-qualified accounts ≥ 15% higher than non-intent accounts
- Sales cycle compression ≥ 18 days shorter for accounts that entered pipeline from HOT tier

**Program ROI (Month 6-12)**
- Pipeline-to-intent-spend ratio ≥ 8:1 (every $1 of intent data investment generates $8+ in pipeline)
- Intent-sourced closed-won revenue ≥ 3x annual intent data program cost

## Related Prompts

- [ABM Intent Data Activation & Buying Signal Prioritization Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [Signal-Based GTM Automation & Revenue Trigger Engine](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Signal-Based-GTM-Automation-&-Revenue-Trigger-Engine.md)
- [AI-Powered Demand Sensing & Market Signal Intelligence Engine](../../05_Analytics-&-Performance/Demand-Sensing-&-Market-Intelligence/AI-Powered-Demand-Sensing-&-Market-Signal-Intelligence-Engine.md)
- [AI-Powered Revenue Operations RevOps Intelligence & Full-Funnel Alignment Engine](../../05_Analytics-&-Performance/Marketing-Operations-Analytics/AI-Powered-Revenue-Operations-RevOps-Intelligence-&-Full-Funnel-Alignment-Engine.md)

## Integration Tips

**Salesforce Integration**
- Create a custom "Account Intent" object with fields: `Intent_Score__c` (Number), `Intent_Tier__c` (Picklist: Cold/Warm/Hot/Urgent), `Top_Intent_Topics__c` (Long Text), `Intent_Last_Updated__c` (DateTime), `Intent_Surge_Date__c` (Date), `Primary_Intent_Source__c` (Text)
- Build a Salesforce Flow that creates a Task assigned to account owner whenever tier changes from WARM → HOT or HOT → URGENT
- Add Intent Score widget to Account Lightning Page for SDR/AE visibility
- Create a "Intent Pipeline" report showing all open opportunities where account was HOT+ at opportunity creation date

**Marketo Integration**
- Create Account Intent Tier as a Marketo Company field synced from Salesforce
- Build Smart Lists for each tier to enable dynamic list-based campaigns
- Use "Company Data Value Changes" triggers on Intent_Tier__c field to auto-enroll accounts in appropriate nurture programs
- Suppression list: exclude Current Customers (Stage = Closed Won past 12 months) and active Opportunities in Stage 4+

**Bombora Integration**
- Use Bombora's Salesforce native app for direct account-level topic surge scores
- Map 15-20 core Bombora topics to your product category; score each topic with weights reflecting purchase readiness
- Set up weekly CSV export as backup; normalize company names using domain-based matching
- Configure weekly digest email for sales team showing their top 10 highest-surge accounts

**6sense / Demandbase Integration (if applicable)**
- Use AI-predicted buying stage as the primary third-party score input
- Map 6sense's "Decision" and "Purchase" stages directly to HOT/URGENT tiers
- Pull 6sense account data into Salesforce using native connector; update nightly
- Use 6sense segment builder to create LinkedIn matched audiences for air cover advertising

**Zapier / Make.com Workflows**
- Trigger: Account enters URGENT tier → Slack DM to AE and their manager
- Trigger: Account enters HOT tier → Enroll in Salesloft/Outreach cadence (if not already in active sequence)
- Trigger: G2 Competitor comparison viewed → Notify SDR + trigger competitive battle card email
- Trigger: Intent score drops below 30 → Remove from active sequence, move to nurture

## Troubleshooting

**Problem: Low match rates between intent vendors and CRM accounts (below 70%)**
*Solution:* Implement domain-based account matching instead of company name matching. Add `Account_Website_Domain__c` as a normalized field in Salesforce (strip www, lowercase). Work with intent vendor's data team to provide your account list for pre-match before activating signals. For Bombora specifically, use their Company ID matching rather than name-based lookup. Expect 10-15% of accounts to require manual review—focus on highest-ACV targets first.

**Problem: Sales team ignoring intent alerts ("alert fatigue") despite HOT tier escalations**
*Solution:* This is a calibration problem, not a motivation problem. If SDRs are ignoring alerts, your thresholds are too low—too many accounts reach HOT without real buying urgency. Audit the last 30 HOT accounts: what % resulted in a meeting within 14 days? If below 10%, raise the HOT threshold by 10 points and add one additional required signal. Also check that signal personalization is making it into outreach—generic emails triggered by intent alerts train reps to ignore them. Build 3-4 pre-written, intent-specific email templates for SDRs that directly reference the triggering signal.

**Problem: Inability to attribute pipeline to intent data with confidence**
*Solution:* Build attribution in two ways: (1) Correlation analysis—create a Salesforce report showing average Intent Score at opportunity creation date vs. close rate. If intent-high accounts close at a meaningfully higher rate, you have statistical evidence. (2) Holdout test—randomly assign 20% of HOT accounts to a "no intent activation" control group for 90 days. Compare meeting booking rate and pipeline creation rate between test and control. Use a chi-square test with p<0.05 as your significance threshold. Present results to leadership as "lift from intent activation" to justify program investment.

## Version History
- v1.0: Initial creation (auto-generated)
