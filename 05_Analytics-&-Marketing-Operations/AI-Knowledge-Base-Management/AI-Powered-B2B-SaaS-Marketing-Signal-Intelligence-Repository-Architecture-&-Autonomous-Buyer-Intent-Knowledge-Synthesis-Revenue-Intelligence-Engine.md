# AI-Powered B2B SaaS Marketing Signal Intelligence Repository Architecture & Autonomous Buyer Intent Knowledge Synthesis Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, saas, intent-data, marketing-operations, knowledge-management, automation, analytics, revenue-intelligence

## Overview

This prompt designs and operationalizes a centralized marketing signal intelligence repository that continuously ingests, synthesizes, and activates buyer intent signals across all first-party and third-party data sources — transforming raw behavioral signals into structured, queryable knowledge that AI agents can act on autonomously to accelerate pipeline and revenue.

## Quick Copy-Paste Version

You are a senior marketing intelligence architect specializing in B2B SaaS intent data systems. Build a complete buyer signal intelligence repository for [Company Name], a [product description] serving [ICP description].

Design a marketing signal intelligence architecture that:

1. SIGNAL INVENTORY: Map every buyer intent signal we collect across:
   - First-party: website visits, content downloads, demo requests, product usage, email engagement, webinar attendance, chat conversations
   - Second-party: partner data, review site activity (G2, Capterra), community engagement, event participation
   - Third-party: intent data vendors (Bombora, G2 Buyer Intent, Demandbase), technographic signals, job posting intelligence, LinkedIn engagement

2. SIGNAL TAXONOMY: Create a structured classification system for each signal including:
   - Signal type (behavioral, contextual, predictive)
   - Buyer journey stage (awareness, consideration, decision, expansion)
   - Stakeholder persona (economic buyer, technical evaluator, end user, champion)
   - Signal strength score (1-10 with decay rate)
   - Time-to-action window (hours, days, weeks)

3. KNOWLEDGE SYNTHESIS RULES: Define AI synthesis logic to:
   - Cluster co-occurring signals into buying intent patterns
   - Identify account-level vs. contact-level buying momentum
   - Flag dark social and unattributed demand signals
   - Detect competitive evaluation signals (competitor content consumption, review site comparison pages)
   - Score buying committee coverage (% of key stakeholders showing intent)

4. ACTIVATION PLAYBOOKS: Map each signal cluster to an automated response:
   - Immediate (0-4 hours): SDR alert, AI-personalized outreach sequence
   - Short-term (1-3 days): Content personalization, ad retargeting activation
   - Medium-term (1-2 weeks): ABM campaign trigger, executive engagement request
   - Long-term (2-4 weeks): Nurture sequence adjustment, pipeline review meeting

5. REPOSITORY SCHEMA: Design the data structure for storing and querying signals:
   - Account-level signal history (rolling 90 days)
   - Contact-level engagement timeline
   - Competitive activity log
   - Signal-to-pipeline attribution records

Output: Complete signal intelligence repository blueprint with taxonomy tables, synthesis rules, activation playbooks, and a data schema ready for implementation in HubSpot, Salesforce, or a CDP.

## Advanced Customizable Version

ROLE: You are a Principal Marketing Intelligence Architect with 15+ years designing buyer intent systems for enterprise B2B SaaS companies. You combine deep expertise in data engineering, behavioral psychology, and revenue operations.

COMPANY CONTEXT:
- Company: [Company Name]
- Product: [Brief product description — what it does, core value prop]
- ICP: [Ideal Customer Profile — industry, company size, key personas]
- ACV: [Average Contract Value — e.g., $50K–$200K]
- Sales cycle: [Length — e.g., 60–120 days]
- Current GTM motion: [Inbound/Outbound/PLG/ABM/Partner-led]
- Existing data sources: [List current tools — e.g., HubSpot, Salesforce, Bombora, G2, Clearbit, 6sense]
- Buying committee: [Key stakeholders — e.g., VP Marketing, CTO, CFO, IT Director]

OBJECTIVE: Design a production-ready Marketing Signal Intelligence Repository that functions as the autonomous "intelligence brain" of your revenue team — continuously learning from buyer behavior and triggering AI-powered actions without human intervention.

═══════════════════════════════════════
SECTION 1: SIGNAL ARCHITECTURE DESIGN
═══════════════════════════════════════

Design the complete signal capture infrastructure:

**A. First-Party Signal Matrix**
For each signal type below, specify: capture method, data fields, freshness SLA, storage location, and enrichment requirements.

| Signal Category | Signal Type | Capture Method | Key Fields | Freshness SLA |
|----------------|-------------|----------------|------------|---------------|
| Website Intent | Page views (pricing, comparison, integrations) | GA4 + Clearbit Reveal | Account ID, URL, timestamp, session depth | Real-time |
| Content Engagement | Asset downloads, video completion % | MAP + HubSpot | Contact ID, asset type, completion %, referral source | < 1 hour |
| Product Signals | Feature usage, trial activation milestones | Product analytics (Mixpanel/Amplitude) | User ID, feature, frequency, recency | Real-time |
| Email Engagement | Open, click, reply, forwarding patterns | HubSpot/Marketo | Contact ID, email ID, engagement type, device | < 30 min |
| [Expand for your specific signals] | | | | |

**B. Second-Party Signal Matrix**
- G2/Capterra: Profile views, competitor comparisons, category browsing — map to account via email domain reverse lookup
- Partner ecosystem: Integration marketplace installs, partner referral signals, co-sell opportunities from ELG tools (Crossbeam, Reveal)
- Review site behavior: Buyer's competitor shortlisting activity (use G2 Buyer Intent API)
- Event signals: Conference attendance, virtual event participation, session selection patterns

**C. Third-Party Intent Signal Matrix**
Evaluate and integrate signals from:
- Bombora: Topic surge scores by account — prioritize topics mapped to our solution category
- Demandbase/6sense: Account-level predictive intent scores, pipeline stage predictions
- LinkedIn Sales Navigator: Job change alerts for champion tracking, company growth signals
- Job posting intelligence: Target accounts hiring roles that indicate our use case (e.g., if we sell RevOps software, track VP Sales + RevOps Manager hires)
- Funding signals: Crunchbase/PitchBook — new funding events indicate budget availability

═══════════════════════════════════════
SECTION 2: SIGNAL TAXONOMY & SCORING
═══════════════════════════════════════

Build a structured taxonomy with the following classification dimensions:

**Signal Strength Scoring Model:**
Assign each signal a base score (1-10) with decay function:

Signal Score = Base Score × Recency Decay Factor × Persona Weight × Stage Multiplier

Where:
- Recency Decay: Score × (0.95)^days_since_signal [exponential decay]
- Persona Weight: Economic buyer = 1.5x, Technical evaluator = 1.2x, Champion = 1.3x, End user = 0.8x
- Stage Multiplier: Pricing/comparison page = 2.0x, ROI calculator = 2.5x, Integration page = 1.5x, Blog = 0.5x

**High-Intent Signal Definitions** (customize thresholds for your business):
- TIER 1 (Score 8-10): Pricing page visit + demo request within 72 hours; competitive comparison page ≥ 3 visits; G2 Buyer Intent spike > 2 standard deviations; ROI calculator completion; trial activation + feature adoption ≥ 60% in 14 days
- TIER 2 (Score 5-7): Content sequence completion (3+ assets in ICP topic cluster); webinar attendance + post-event engagement; champion job change to new account; LinkedIn Sales Navigator alert for company growth signals
- TIER 3 (Score 2-4): Single blog visit; email open without click; industry conference attendance; social follow

**Buying Committee Coverage Score:**
Committee Coverage % = (Engaged Personas / Total Required Personas) × 100

Required personas for [your product]: [list 4-6 required roles]
Engaged = at least one Tier 1 or two Tier 2 signals in past 30 days

Alert thresholds:
- ≥ 80% coverage: Executive engagement + deal desk notification
- 50-79% coverage: Multi-thread campaign activation
- 25-49% coverage: Champion enablement + stakeholder mapping
- < 25%: ICP fit validation + account research sprint

═══════════════════════════════════════
SECTION 3: KNOWLEDGE SYNTHESIS ENGINE
═══════════════════════════════════════

Design AI synthesis rules that transform raw signals into actionable intelligence patterns:

**Pattern Recognition Rules:**

PATTERN A — "Active Buying Cycle" (highest priority)
- Trigger: Account shows Tier 1 signal within 48 hours of any Tier 2 signal from a different contact
- Inference: Multiple stakeholders independently researching → active evaluation underway
- Confidence score: 85-95%
- Required action: Immediate SDR notification + AI-personalized email to all engaged contacts

PATTERN B — "Competitive Evaluation Risk"
- Trigger: Known customer account visits competitor comparison pages OR G2 Buyer Intent shows competitor surge
- Inference: Active competitive evaluation → churn risk for customers, displacement opportunity for prospects
- Confidence score: 70-85%
- Required action: Competitive intelligence brief to AE + customer success alert for existing accounts

PATTERN C — "Dark Funnel Surfacing"
- Trigger: Account visits pricing page from direct/dark traffic with no prior attributed touchpoint
- Inference: Buyer conducted research through dark social channels (Slack, Reddit, peer conversations) before visible engagement
- Confidence score: 60-75%
- Required action: Immediate content personalization + SDR research sprint to identify champion

PATTERN D — "Champion Activated"
- Trigger: Contact with prior champion history (previous customer, event speaker, case study participant) shows re-engagement signals
- Inference: Warm re-entry → high probability of fast pipeline conversion
- Confidence score: 90%
- Required action: AE direct outreach within 2 hours + C-suite involvement if previous ACV > $100K

PATTERN E — "Expansion Signal"
- Trigger: Existing customer's new department shows first-party intent signals for same use case
- Inference: Organic expansion opportunity → cross-sell or multi-seat expansion
- Confidence score: 80%
- Required action: CSM + AE joint account planning trigger + product-led expansion sequence

**Negative Signal Patterns** (de-prioritization rules):
- Account visits Jobs/Careers page with no other engagement → likely a job seeker, not a buyer
- Email open-only engagement with no clicks across 5+ emails → disengaged contact, suppress from sales outreach
- Trial user showing only onboarding activity with no feature adoption after 21 days → at-risk PQL, route to success motion not sales

═══════════════════════════════════════
SECTION 4: REPOSITORY DATA SCHEMA
═══════════════════════════════════════

Design the canonical data structure for the intelligence repository:

**Account Intelligence Record Schema:**
{
  "account_id": "string",
  "account_name": "string",
  "domain": "string",
  "icp_fit_score": 0-100,
  "last_updated": "ISO8601 timestamp",
  "signal_summary": {
    "overall_intent_score": 0-100,
    "score_trend": "increasing|stable|decreasing",
    "buying_stage_prediction": "awareness|consideration|decision|not_in_market",
    "buying_committee_coverage": 0-100,
    "days_in_current_stage": "integer",
    "competitive_activity": "boolean"
  },
  "active_signals": [
    {
      "signal_id": "string",
      "signal_type": "string",
      "source": "string",
      "contact_id": "string",
      "persona": "string",
      "score": 0-10,
      "timestamp": "ISO8601",
      "decay_adjusted_score": 0-10,
      "pattern_match": ["string"]
    }
  ],
  "pattern_detections": [
    {
      "pattern_name": "string",
      "confidence": 0-100,
      "detected_at": "ISO8601",
      "activated_playbook": "string",
      "playbook_status": "triggered|in_progress|completed"
    }
  ],
  "signal_history_90d": "array of signal objects",
  "attribution_records": "array of pipeline touchpoints"
}

**Contact Intelligence Record Schema:**
{
  "contact_id": "string",
  "account_id": "string",
  "persona": "economic_buyer|technical_evaluator|champion|end_user|influencer",
  "engagement_score": 0-100,
  "engagement_timeline": "array of timestamped engagement events",
  "content_consumed": "array of asset IDs with completion %",
  "topics_of_interest": "array of topic tags derived from content engagement",
  "outreach_history": "array of AE/SDR touchpoints",
  "champion_indicators": {
    "previous_customer": "boolean",
    "case_study_participant": "boolean",
    "event_speaker": "boolean",
    "advocate_program_member": "boolean"
  }
}

═══════════════════════════════════════
SECTION 5: ACTIVATION PLAYBOOK LIBRARY
═══════════════════════════════════════

For each pattern detection, generate a corresponding AI-executed playbook:

**Playbook Template Structure:**
Playbook Name: [Pattern Name] Response
Trigger: [Pattern detection + threshold]
SLA: [Time from detection to first action]

Step 1 (T+0): [Immediate automated action]
Step 2 (T+X hours): [Follow-up automated action]
Step 3 (T+X days): [Human notification or AI-escalated action]
Step 4 (T+X days): [Continued sequence or exit criteria]

Exit Criteria: [Conditions that end the playbook — positive: meeting booked; negative: opt-out or 30 days no engagement]
Attribution: [How to credit this playbook in revenue attribution]

Generate complete playbooks for:
1. Active Buying Cycle (Pattern A)
2. Competitive Evaluation Risk (Pattern B)
3. Dark Funnel Surfacing (Pattern C)
4. Champion Activated (Pattern D)
5. Expansion Signal (Pattern E)
6. High-Intent New Account Discovery
7. Stalled Opportunity Re-engagement
8. Renewal Risk Early Warning

═══════════════════════════════════════
SECTION 6: MEASUREMENT & OPTIMIZATION
═══════════════════════════════════════

Define the KPI framework for repository performance:

**Signal Quality KPIs:**
- Signal-to-opportunity conversion rate by signal type
- Pattern detection precision (% of detected patterns that resulted in real pipeline)
- Signal decay accuracy (are our decay rates calibrated to actual purchase timelines?)
- Buying committee coverage correlation to win rate

**Operational KPIs:**
- Mean time from signal detection to playbook activation (target: < 15 minutes)
- Playbook completion rate by pattern type
- False positive rate (playbooks triggered on non-buyers)
- Signal data freshness (% of account records updated in past 7 days)

**Revenue Impact KPIs:**
- Pipeline sourced from signal-triggered playbooks vs. baseline
- Win rate for accounts with ≥ 50% buying committee coverage at opportunity creation
- Deal velocity improvement (days to close for signal-activated vs. non-activated accounts)
- Revenue attribution to intelligence repository (multi-touch model)

OUTPUT REQUIREMENTS:
Deliver a complete Signal Intelligence Repository Blueprint including:
1. Signal matrix tables (first-party, second-party, third-party) with all specified fields
2. Signal scoring model with decay formula and persona weights calibrated to [your ICP]
3. Synthesis engine pattern definitions with confidence thresholds
4. Full JSON schemas for account and contact intelligence records
5. 8 complete activation playbooks with step-by-step AI execution logic
6. KPI dashboard specification with target benchmarks
7. 90-day implementation roadmap (Phase 1: Signal capture; Phase 2: Synthesis engine; Phase 3: Playbook automation)
8. Tech stack integration map (which tools connect where, API requirements, data flow diagram description)

## Example Input/Output

**Input Example:**

Company: Meridian Analytics — AI-powered revenue forecasting platform for mid-market B2B SaaS ($5M-$50M ARR)
ICP: VP Sales, CRO, VP Finance at SaaS companies 50-500 employees
ACV: $45,000/year
Sales cycle: 45-90 days
Existing stack: HubSpot, Salesforce, Bombora, G2 Buyer Intent, Clearbit, LinkedIn Sales Navigator

**Output Example (Excerpt):**

**Signal Matrix — Tier 1 High-Intent Signals for Meridian Analytics:**

| Signal | Source | Score | Decay Rate | Required Action SLA |
|--------|---------|-------|------------|---------------------|
| Pricing page ≥ 3 visits in 7 days | HubSpot | 9.5 | 15% per day | SDR outreach within 2 hours |
| G2 "Meridian vs. Clari" comparison page view | G2 Buyer Intent | 9.0 | 20% per day | Competitive battle card sent + SDR alert |
| ROI Calculator completion | HubSpot/Website | 10.0 | 10% per day | Immediate AI-personalized email with custom ROI output |
| Bombora Topic Surge: "Revenue Forecasting Accuracy" > 75 | Bombora | 8.0 | 7% per day | ABM campaign activation within 4 hours |
| VP Finance + VP Sales both visit site within 72 hours | HubSpot + Clearbit | 9.8 | 12% per day | Buying committee alert to AE + executive outreach from CEO |

**Pattern Detection Example — "Active Buying Cycle" at Northstar Software:**

Detection Time: 2026-03-15 09:23 UTC

Signals Detected:
- Contact: Jennifer Walsh (VP Sales) → Pricing page (3 visits, 47 min total) — Score: 9.2
- Contact: Marcus Chen (VP Finance) → ROI Calculator completion → downloaded PDF — Score: 10.0
- Contact: Unknown (darkweb IP, Clearbit resolve: Northstar domain) → G2 comparison page — Score: 8.5
- Account-level: Bombora surge on "sales forecasting software" — Score: 8.0

Pattern Match: ACTIVE BUYING CYCLE (Confidence: 91%)
Buying Committee Coverage: 67% (2 of 3 required personas engaged)

Playbook Triggered: Active Buying Cycle Response
  T+0: SDR Marcus Weber notified via Slack with full intelligence brief
  T+45 min: AI-personalized email sent to Jennifer Walsh referencing her specific pricing page views
  T+2 hours: AI-personalized email sent to Marcus Chen with CFO-specific ROI case study (Northstar is FinTech, matched to FinTech CFO case study)
  T+4 hours: LinkedIn outreach from AE to identify third stakeholder (CRO/CEO)
  T+24 hours: If no response, retargeting ads activated for all Northstar employees on LinkedIn

**Revenue Impact (Simulated 90-day results for Meridian Analytics):**
- 47 pattern detections → 31 sales-accepted opportunities (66% precision)
- Average deal velocity: 38 days (vs. 74-day baseline) — 49% improvement
- Win rate for signal-activated accounts: 43% (vs. 27% baseline)
- Pipeline sourced: $2.1M incremental (signal-triggered playbooks vs. no-intelligence baseline)

## Success Metrics

- **Signal Coverage:** ≥ 80% of ICP accounts have active signal data within the past 30 days
- **Pattern Detection Precision:** ≥ 65% of detected patterns result in sales-accepted opportunities within 45 days
- **Playbook Activation Speed:** Median time from signal detection to first automated action < 20 minutes
- **Buying Committee Coverage:** Average opportunity has ≥ 60% committee coverage at creation stage
- **Repository Freshness:** ≥ 90% of account records updated within the past 7 days
- **Revenue Attribution:** ≥ 25% of closed-won revenue has at least one signal-triggered touchpoint in the path
- **Win Rate Lift:** Accounts with Tier 1 signal activation show ≥ 15 percentage point higher win rate vs. non-activated

## Related Prompts

- [`../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/First-Party-Data-CDP-Strategy-Engine.md`](../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/First-Party-Data-CDP-Strategy-Engine.md) — Design the first-party data foundation that feeds this repository
- [`../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Intent-Data-Vendor-Evaluation-&-Buyer-Signal-Stack-Architecture-Revenue-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Intent-Data-Vendor-Evaluation-&-Buyer-Signal-Stack-Architecture-Revenue-Intelligence-Engine.md) — Evaluate and select the third-party intent data vendors to plug into this repository
- [`../../01_CMO-&-Leadership/Strategy-&-Planning/AI-Powered-B2B-SaaS-CMO-Autonomous-Marketing-Intelligence-Architecture-&-Real-Time-Market-Signal-Command-Revenue-Intelligence-Engine.md`](../../01_CMO-&-Leadership/Strategy-&-Planning/AI-Powered-B2B-SaaS-CMO-Autonomous-Marketing-Intelligence-Architecture-&-Real-Time-Market-Signal-Command-Revenue-Intelligence-Engine.md) — Executive intelligence layer that sits on top of this repository for CMO decision-making
- [`../../05_Analytics-&-Marketing-Operations/AI-Knowledge-Base-Management/Real-Time-Competitive-Intelligence-Monitoring-&-Signal-Detection-Engine.md`](../../05_Analytics-&-Marketing-Operations/AI-Knowledge-Base-Management/Real-Time-Competitive-Intelligence-Monitoring-&-Signal-Detection-Engine.md) — Companion competitive signal layer for the full intelligence repository

## Integration Tips

**HubSpot:**
- Use HubSpot's Custom Properties to store account-level intent scores and pattern detection flags
- Trigger Workflows from intent score thresholds to auto-enroll contacts in sequences
- Build Custom Report dashboards to visualize signal-to-pipeline conversion by signal type
- Use the HubSpot Data Model to create a custom "Signal Event" object linked to both Contact and Company records

**Salesforce:**
- Create a custom "Signal Intelligence" related list on Account and Opportunity objects
- Use Salesforce Flow to trigger tasks and notifications when pattern detections arrive via API
- Store signal history in a custom "Signal Log" object with lookup to Account, Contact, and Opportunity
- Configure Einstein Activity Capture to pull engagement signals directly into the intelligence schema

**Clay / Airtable (Signal Enrichment Layer):**
- Use Clay to enrich account records with job posting intelligence, funding signals, and LinkedIn growth data
- Airtable serves as the lightweight signal repository before graduated migration to a proper CDP

**Zapier / Make (Automation Bridge):**
- Build Zaps that push Bombora intent spikes into HubSpot Company properties in real-time
- Trigger Slack notifications to SDRs the moment a Tier 1 pattern is detected
- Sync G2 Buyer Intent webhook events into Salesforce Signal Log records automatically

**Segment / RudderStack (CDP):**
- Use as the canonical event streaming layer feeding all first-party signals into the repository
- Build Segment Audiences that dynamically update as signal scores change
- Push synthesized audiences to ad platforms (LinkedIn, Google) for real-time retargeting activation

**Snowflake / BigQuery (Data Warehouse):**
- Store 90-day rolling signal history with full attribution records
- Run pattern detection SQL jobs on 15-minute cron schedules
- Power BI or Looker dashboards for repository KPI monitoring

## Troubleshooting

**Problem: Signal scores are too high across too many accounts — the repository is flagging everything as "active buying cycle," overwhelming the sales team.**

Solution: Recalibrate your decay rates and pattern confidence thresholds. Start by pulling a 90-day cohort of accounts that received a TIER 1 signal and check what % converted to pipeline within 45 days. If the conversion rate is < 40%, your Tier 1 threshold is too low. Raise the composite score requirement for pattern detection or add a recency requirement (e.g., signal must be within 14 days, not 30). Also add a "minimum signal diversity" rule — require signals from at least 2 different sources before triggering a sales alert.

**Problem: The repository has excellent signal coverage for inbound-generated accounts but almost no intelligence for cold outbound target accounts.**

Solution: This indicates over-reliance on first-party signals. Prioritize onboarding third-party intent sources (Bombora, G2 Buyer Intent, Demandbase) for your TAL. Additionally, implement a proactive "account warm-up" content strategy: run LinkedIn Thought Leader Ads and content syndication campaigns at your cold target accounts, and the resulting engagement will generate trackable first-party signals within 30-60 days. Also implement job posting monitoring (use Clay or Predictleads API) to capture intent from accounts with no direct engagement.

**Problem: Pattern detection confidence scores are inaccurate — the model says 85% confidence but actual conversion rates are only 30%.**

Solution: Your pattern confidence thresholds are likely derived from assumed correlations rather than historical data. Backfill 12 months of signal data against actual closed-won/lost outcomes and recalibrate confidence scores using logistic regression on your own historical signal-to-outcome pairs. If you don't have 12 months of data, start with a 60-day validation sprint: log every pattern detection in a tracking sheet, monitor the subsequent 45-day outcome, and adjust thresholds when you have 50+ data points per pattern type.

## Version History
- v1.0: Initial creation (auto-generated)
