# AI-Powered B2B SaaS Revenue Signal Command Center Architecture & Cross-Source Buying Intent Autonomous Campaign Intelligence Engine - Build Your Always-On Demand Response Machine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** demand gen ops, intent data, signal-based GTM, autonomous marketing, pipeline, B2B SaaS, RevOps, buyer signals, campaign automation

## Overview
Designs a unified revenue signal command center that aggregates buying intent signals from 8+ first-party and third-party data sources, scores accounts using composite signal weighting, and automatically fires personalized multi-stakeholder campaign playbooks without human intervention. Use this when you need to evolve from reactive demand generation (running campaigns on a calendar) to a proactive, always-on demand engine that responds to real-time buyer behavior.

## Quick Copy-Paste Version

You are a senior B2B SaaS demand generation architect specializing in signal-based GTM motions. Design a complete Revenue Signal Command Center for my company that consolidates buying intent signals from multiple sources, scores accounts automatically, and triggers the right marketing campaign for each account based on signal combination and strength.

COMPANY CONTEXT:
- Company: [e.g., "Vaultix — B2B SaaS data governance and compliance platform for regulated industries"]
- ICP: [e.g., "VP/Director of IT Compliance and Chief Data Officers at financial services, healthcare, and insurance companies, 500-5,000 employees"]
- ACV: [e.g., "$65,000 average, 5-8 month sales cycle"]
- Target account list size: [e.g., "1,200 named accounts across Tier 1, 2, and 3"]
- Current signal sources available: [e.g., "HubSpot (email + web), Salesforce CRM, Bombora intent data, G2 profile traffic, LinkedIn Matched Audiences — no product usage data yet (not PLG)"]
- Sales motion: [e.g., "Enterprise SLG — 6 AEs, 4 SDRs, field SE team"]

DELIVERABLES:

1. SIGNAL TAXONOMY
Define 5-8 distinct buying signal categories with:
- Signal name and data source
- What behavior it indicates (early awareness / active research / evaluation-stage / late-stage decision)
- Where this signal is captured and how it surfaces in our martech stack
- Recommended signal weight (1-10 scale for composite scoring)

2. COMPOSITE ACCOUNT SIGNAL SCORE MODEL
Build a scoring model that:
- Assigns a 0-100 score to each target account based on all signals firing simultaneously
- Defines score tiers: Cold (0-25), Warming (26-50), Hot (51-75), Surging (76-100)
- Specifies decay logic (how quickly does a signal lose weight if behavior stops?)
- Handles accounts where only 1-2 signals fire vs. 4+ signals firing together

3. CAMPAIGN PLAYBOOK TRIGGER MAP
For each score tier AND for specific high-value signal combinations, define:
- Campaign name and description
- Target personas within the account (who gets what)
- Channel sequence (paid, email, direct mail, SDR outreach, LinkedIn)
- Content assets to use at each touch
- Duration and cadence of the campaign
- Escalation rules (when does marketing hand off to SDR?)

4. AUTONOMOUS TRIGGER ARCHITECTURE
Describe the technical workflow:
- Where the composite score lives (CRM field, MAP, or CDP)
- How score changes automatically trigger campaign enrollment in HubSpot/Marketo/Salesforce
- Alert logic for SDRs and AEs when an account surges into "Hot" tier
- Deduplication rules so accounts don't receive conflicting campaigns simultaneously

5. SIGNAL-TO-PIPELINE ATTRIBUTION MODEL
Define how to measure whether the command center is working:
- Metrics to track weekly, monthly, and quarterly
- How to measure "signal-influenced pipeline" vs. "signal-sourced pipeline"
- A/B test design to prove the model works (control group methodology)

Output using clear headers and tables for the scoring model and campaign trigger map.

## Advanced Customizable Version

ROLE: You are a Principal Demand Generation Architect with 18+ years of experience building signal-based GTM motions for B2B SaaS companies from Series B through post-IPO. You have deep expertise in intent data platforms (Bombora, G2, TechTarget, 6sense, Demandbase), marketing automation orchestration (HubSpot, Marketo, Pardot), CDP architecture, and RevOps alignment. You understand how to translate fragmented buying signals into coordinated, autonomous marketing responses that accelerate pipeline without inflating headcount.

CONTEXT:
Company: [Company Name]
Stage: [e.g., Series D, 340 employees, $42M ARR, targeting $75M by EOY]
Product: [e.g., AI-native procurement intelligence and supplier risk management platform]
ICP Primary Segment: [e.g., Chief Procurement Officers and VP Supply Chain at manufacturing, CPG, and retail companies, 1,000-15,000 employees]
Buying Committee Composition: [e.g., CPO (economic buyer, 40% influence), VP Supply Chain (champion, 35%), IT Security (technical validator, 15%), Legal/Compliance (risk reviewer, 10%)]
ACV: [e.g., $110,000 net new; $165,000 expansion including services]
Sales motion: [e.g., Enterprise SLG — AE + SC + SDR pod, 7-month average sales cycle, multi-stakeholder consensus required]
Named target account list: [e.g., 2,400 Tier 1-3 accounts globally, 850 in North America priority segment]

AVAILABLE SIGNAL SOURCES (list what you have):
First-Party Signals:
- Website visitor intelligence: [e.g., "6sense de-anonymizes 60-70% of B2B visitors; we track page visits by topic cluster (pricing, ROI, vs-competitor, solutions)"]
- Email engagement: [e.g., "HubSpot tracks opens/clicks by persona and content topic across 4 nurture streams"]
- CRM activity data: [e.g., "Salesforce logs all AE/SDR touches, meeting outcomes, stage history, and re-engagement dates"]
- Product usage signals: [e.g., "N/A — not PLG; no product usage data pre-sale"]
- Event and webinar engagement: [e.g., "ON24 tracks webinar attendance, poll responses, and content downloads by attendee"]
- Direct response signals: [e.g., "Demo requests, ROI calculator completions, pricing page visits >2 minutes, competitor comparison page visits"]

Third-Party Signals:
- Intent data platform: [e.g., "Bombora — tracking 42 company surge topics related to procurement transformation, supply chain risk, ESG supplier compliance"]
- Review site signals: [e.g., "G2 — tracking category page visits (Procurement Software, Supplier Risk Management), product profile visits, competitor profile visits"]
- Technographic changes: [e.g., "Datanyze/BuiltWith — tracking when accounts add or remove competitive/adjacent technologies (Coupa, Jaggaer, SAP Ariba)"]
- News and trigger events: [e.g., "NewsAPI monitoring for supply chain disruption news, regulatory compliance announcements, M&A activity in target accounts"]

LinkedIn Data:
- [e.g., "LinkedIn Sales Navigator — tracking champion persona job changes, company growth/headcount signals, executive LinkedIn activity on supply chain topics"]
- [e.g., "LinkedIn Matched Audiences — tracking engagement rates with sponsored content by account and persona"]

Firmographic Trigger Events:
- [e.g., "Funding announcements (Series C+), IPO activity, executive hiring (new CPO/VP Supply Chain), geographic expansion announcements"]
- [e.g., "Supply chain disruption events affecting target accounts' industries (tariffs, logistics crises, ESG regulation changes)"]

MARTECH STACK:
- CRM: [e.g., Salesforce Sales Cloud Enterprise]
- Marketing Automation: [e.g., HubSpot Marketing Hub Enterprise]
- ABM Platform: [e.g., 6sense Revenue AI]
- Intent Data: [e.g., Bombora]
- Sales Engagement: [e.g., Outreach]
- Data Enrichment: [e.g., Clearbit + ZoomInfo]
- CDP: [e.g., None currently — building case for Segment]
- Analytics: [e.g., Salesforce Reports + Tableau]
- Workflow Automation: [e.g., Zapier for lightweight triggers, custom Salesforce Flows for complex orchestration]

OBJECTIVE: Design a complete Revenue Signal Command Center that:
1. Consolidates all available signals into a unified account intelligence layer
2. Scores accounts in real time using a composite weighted model
3. Automatically assigns accounts to campaign playbooks based on signal pattern and score tier
4. Enables personalized, multi-stakeholder campaign execution without human review for standard plays
5. Provides measurable signal-to-pipeline attribution to prove and improve the model over time

FRAMEWORK REQUIREMENTS:

A. SIGNAL TAXONOMY AND WEIGHTING

For each signal source, define:
- Signal Name: [Short, descriptive name]
- Data Source & Capture Mechanism: [Where does it live and how is it ingested?]
- Buyer Stage Indicator: [What does this signal tell us about where the account is in the buying journey?]
- Persona Relevance: [Which buying committee members does this signal most likely represent?]
- Signal Weight (1-10): [How predictive is this signal of purchase intent at this ACV?]
- Signal Decay Rate: [How long does this signal remain "active" before decaying? — e.g., "G2 profile visit: 21-day active window, then decays 10% per week"]
- Deduplication Rule: [If the same signal fires multiple times in one week, count as 1x or multiply?]

Signal Weight Philosophy:
- High-weight signals (8-10): Signals that require active research behavior — demo request, competitor comparison page visit, G2 competitor profile visit, pricing page >3 min, Bombora topic surge >70 on high-intent topics
- Mid-weight signals (5-7): Signals that indicate awareness and learning — blog article reads, webinar attendance, email click-through to solution pages, LinkedIn ad engagement, technology stack change
- Low-weight signals (1-4): Passive engagement — single email open, one website visit, firmographic trigger event alone

B. COMPOSITE ACCOUNT SIGNAL SCORE (CASS) MODEL

CASS Formula Framework:
CASS = Σ(Signal Weight × Signal Frequency Multiplier × Persona Breadth Multiplier × Recency Multiplier)

Define:
- Signal Frequency Multiplier: e.g., "Signal fires once = 1.0x; fires 3-5 times = 1.5x; fires 6+ times = 2.0x"
- Persona Breadth Multiplier: e.g., "Signal from 1 persona = 1.0x; signals from 2 different personas = 1.3x; 3+ personas = 1.6x (multi-threaded signal)"
- Recency Multiplier: e.g., "Signal in last 7 days = 1.0x; 8-21 days = 0.8x; 22-45 days = 0.5x; 46+ days = 0.2x"

Score Tier Definitions:
- Tier 0 — Cold (CASS 0-20): No meaningful buying activity; receive brand awareness content only; no SDR outreach
- Tier 1 — Warming (CASS 21-40): Early awareness signals; eligible for nurture campaigns; marketing-only, no SDR touch yet
- Tier 2 — Active (CASS 41-60): Multiple signals in multiple categories; SDR alert issued; light outreach + marketing campaign simultaneously
- Tier 3 — Hot (CASS 61-80): High-intent signal combination; priority SDR outreach + executive-level ABM campaign; marketing accelerates all touchpoints
- Tier 4 — Surging (CASS 81-100): Near-term purchase intent evident; immediate AE notification; C-suite outreach + custom proof package triggered

Score Change Alert Rules:
- Tier upgrade (any tier jump): Alert assigned SDR + AE in Salesforce Chatter within 2 hours
- Surge event (CASS jumps 20+ points in 72 hours): Immediate Slack alert to AE + SDR + marketing; qualify for "Surge Response" campaign
- Tier downgrade (account drops 2+ tiers in 14 days): Alert AE; review whether opportunity should be pushed back in pipeline

C. CAMPAIGN PLAYBOOK TRIGGER MAP

For each CASS tier AND for 3-4 high-value signal combination triggers, design a complete campaign playbook:

Campaign Elements for Each Playbook:
1. Campaign Name & Objective
2. Target Personas (who receives which content — by role in buying committee)
3. Channel Sequence with Timing:
   - Day 1: [Channel + Content + Message Frame]
   - Day 3: [Channel + Content + Message Frame]
   - Day 7: [Channel + Content + Message Frame]
   - Day 14: [Channel + Content + Message Frame]
   - Ongoing: [Channel + Cadence]
4. Content Assets Required (map to your existing content library or flag gaps)
5. SDR Outreach Script Guidance (what angle to use given this signal combination)
6. Escalation Trigger (what signal/action escalates from marketing to AE-led pursuit?)
7. Campaign Duration and Exit Criteria (when does an account exit this playbook?)

Special Combination Trigger Campaigns:
Design specific campaigns for high-value signal combinations:
- "Competitive Surround" Trigger: Account visits competitor comparison page + competitor G2 profile + Bombora surge on competitive topics simultaneously → Trigger competitive displacement campaign immediately
- "Executive Activation" Trigger: New C-suite hire (CPO/VP Supply Chain) at target account → Trigger 90-day new executive onboarding awareness sequence
- "Funding Reaction" Trigger: Target account announces Series C+ funding or M&A activity → Trigger "growth and scale" messaging campaign within 48 hours
- "Technology Stack Change" Trigger: Account adds or removes a competitive/adjacent technology → Trigger integration story or displacement campaign

D. AUTONOMOUS TRIGGER ARCHITECTURE

Technical Orchestration Design:

Signal Ingestion Layer:
- How each signal enters the martech stack (API, native integration, webhook, CSV import)
- Where each signal is stored (CRM field, MAP property, CDP event)
- Refresh frequency for each signal source (real-time, daily, weekly)

CASS Calculation Engine:
- Where the composite score is calculated (Salesforce formula field, HubSpot Score property, 6sense AI score, or custom CDP logic)
- Recalculation trigger (event-based: recalculate when any new signal fires; or scheduled: nightly batch recalculation)
- Score storage location (Account object in Salesforce + synchronized to HubSpot Company record)

Campaign Enrollment Automation:
- Tool to manage enrollment rules (HubSpot Workflows, Marketo Smart Campaigns, Salesforce Flows, or Zapier)
- Enrollment logic: "IF CASS ≥ 61 AND Account Stage ≠ 'Active Opportunity' AND NOT already enrolled in Hot Campaign THEN enroll in Tier-3 Hot Playbook"
- Deduplication and conflict prevention: "An account can only be enrolled in ONE active tier campaign at a time; tier upgrade automatically unenrolls from lower tier and enrolls in higher tier"
- Suppression lists: Active late-stage opportunities, existing customers, recently closed-lost (90 days), opted-out contacts

Alert and Routing Logic:
- SDR alert format (Salesforce Chatter notification + Slack message with: account name, CASS score, top 3 signals firing, recommended outreach angle, link to account in CRM)
- AE notification criteria (Surging accounts only + accounts in existing pipeline that suddenly spike)
- Marketing review exceptions (accounts that require human review before campaign launches: known do-not-contact, complex competitive situations, previously churned customers)

E. SIGNAL-TO-PIPELINE ATTRIBUTION MODEL

Measurement Framework:

Weekly Signal Health Metrics:
- Total accounts by CASS tier (week-over-week change)
- Signal volume by type (are signals increasing or decreasing?)
- Account tier migration rate (accounts moving up vs. down vs. stagnant)
- Campaign enrollment rate by tier (what % of Hot accounts got into the right campaign within 24 hours?)

Monthly Pipeline Attribution Metrics:
- Signal-Influenced Pipeline: Opportunities where the account had CASS ≥ 41 at time of opportunity creation
- Signal-Sourced Pipeline: Opportunities where the SDR alert from CASS score directly triggered the outreach sequence that converted
- Campaign Playbook Win Rate: Close rate for opportunities influenced by each specific campaign playbook vs. non-influenced baseline
- Average CASS Score at Time of Demo Request (track over time — higher = better signal calibration)

Quarterly Calibration:
- Review signal weights: Correlate each signal type with pipeline creation and win rate to validate or adjust weights
- Signal decay recalibration: Are the decay rates accurate? Do buyers who go cold at 21 days actually come back, or should decay be faster?
- Tier threshold review: Are the CASS tier boundaries correctly identifying "real" buying behavior?

A/B Test Design for Model Validation:
- Split target accounts 80/20: 80% receive full signal-triggered campaigns; 20% receive control (calendar-based campaigns only)
- Measure: Pipeline creation rate, time to first meeting, win rate, ACV — comparing test vs. control
- Run for 90 days before drawing conclusions (minimum sample of 50 opportunities per cohort)

OUTPUT STRUCTURE:

**SECTION 1: Executive Summary**
- Signal Command Center philosophy (2-3 sentences for CMO/CRO)
- Expected pipeline impact vs. current state (estimated % improvement with ranges)
- Implementation complexity and timeline summary

**SECTION 2: Signal Taxonomy Table**
| Signal Name | Source | Buyer Stage | Persona | Weight | Decay | Dedup Rule |

**SECTION 3: CASS Model Design**
- Formula documentation
- Score tier definitions with examples
- Worked example: Show a sample account with 4 signals firing and calculate its CASS score step by step

**SECTION 4: Campaign Playbook Library**
One detailed playbook per CASS tier (4 tiers) + 4 special combination trigger campaigns = 8 total playbooks
Format: Campaign Brief format with channel sequence, content map, SDR guidance, escalation rules

**SECTION 5: Automation Architecture Diagram**
- Written description of the technical flow (signal in → score calculation → tier assignment → campaign enrollment → SDR alert → attribution tracking)
- Tool-by-tool responsibility mapping for our specific stack

**SECTION 6: Implementation Roadmap**
- Phase 1 (Weeks 1-4): Foundation — data connections, CASS field creation, Tier 3-4 playbooks only
- Phase 2 (Weeks 5-8): Expansion — Tier 1-2 playbooks, special trigger campaigns, SDR alert automation
- Phase 3 (Weeks 9-16): Optimization — attribution model live, calibration loop running, A/B test in progress

**SECTION 7: Attribution Dashboard Definition**
List the 10 weekly and monthly KPIs the demand gen team should track, including formula, data source, and target benchmark

## Example Input/Output

**Input Example:**
Company: Proxara — B2B SaaS supply chain risk monitoring and ESG compliance platform
ICP: VP Supply Chain and Chief Sustainability Officers at manufacturing companies, 500-5,000 employees
ACV: $78,000 | Sales cycle: 5 months | Team: 5 AEs, 3 SDRs
Signals available: HubSpot web tracking, Salesforce CRM, Bombora (35 topics), G2 profile visits (via G2 Buyer Intent), LinkedIn Sales Navigator job change alerts, basic firmographic data (ZoomInfo)
Named account list: 1,400 accounts

**Output Example (abbreviated):**

---

**SECTION 2: Signal Taxonomy (Top 5 of 9 signals)**

| Signal Name | Source | Buyer Stage | Top Persona | Weight | Decay Window |
|-------------|--------|-------------|-------------|--------|--------------|
| Demo/Trial Request | HubSpot Form | Decision | Champion | 10 | 60 days active |
| G2 Proxara Profile Visit | G2 Buyer Intent | Evaluation | Any | 9 | 21 days active |
| Competitor G2 Visit (3+ competitors) | G2 Buyer Intent | Evaluation | Champion | 8 | 21 days active |
| Bombora Surge: "Supply Chain Risk Software" (score 70+) | Bombora | Active Research | Economic Buyer | 7 | 14 days, decay 15%/wk |
| Pricing Page Visit >2 min | HubSpot Web | Evaluation | Champion | 8 | 14 days active |
| ESG Compliance Regulation Blog (3+ posts) | HubSpot Web | Awareness | Any | 3 | 7 days, decay 50%/wk |
| New VP Supply Chain Hired | ZoomInfo/LinkedIn | Trigger Event | New Persona | 5 | 90 days (full awareness window) |

---

**SECTION 3: CASS Worked Example**

Account: Reston Industrial Group (1,800 employees, manufacturing)
Signals firing this week:
- G2 Proxara profile visit × 2 (Weight 9 × Freq 1.5x × Recency 1.0x × Persona 1.0x) = 13.5
- Bombora surge on "Supply Chain Risk" at 74 (Weight 7 × Freq 1.0x × Recency 1.0x × Persona 1.0x) = 7.0
- Pricing page visit 3.5 min by same account (Weight 8 × Freq 1.0x × Recency 1.0x × Persona 1.3x breadth) = 10.4
- ESG blog: 4 posts (Weight 3 × Freq 1.5x × Recency 0.8x) = 3.6

**CASS Total: 34.5 → Tier 1 (Warming) — close to Tier 2 threshold (41)**

Action: Enroll in "Active Research Nurture" email sequence (Tier 1 playbook). Set score alert: notify SDR if CASS crosses 41 within next 14 days. Flag to AE as "account to watch."

---

**SECTION 4: Sample Campaign Playbook — Tier 3 (Hot, CASS 61-80)**

**Campaign: "Proven ROI Blitz" — For accounts scoring 61-80 with signals from 2+ personas**

Objective: Deliver proof-heavy content to both economic buyer and champion simultaneously; drive demo request within 21 days.

Channel Sequence:
- Day 1: LinkedIn Sponsored Content → VP Supply Chain persona → "Supply Chain Risk ROI Calculator" (custom asset by ICP vertical)
- Day 1: LinkedIn Sponsored Content → CSO/Sustainability persona → "ESG Compliance Automation: 3 Proxara Customer Case Studies"
- Day 2: SDR automated Outreach step 1 → Personalized email to champion persona referencing recent Bombora topic surge category (not the tool itself)
- Day 5: HubSpot email → "How [similar-sized manufacturer] reduced supplier risk events by 67% in 90 days" (case study match to account's SIC code)
- Day 7: SDR Outreach step 2 → LinkedIn InMail to economic buyer persona — warm intro email from AE
- Day 10: Retargeting display ads (6sense) → Proxara vs. [Competitor A] and [Competitor B] comparison content
- Day 14: SDR Outreach step 3 → Phone call with voicemail + same-day email (time-sensitive framing)
- Day 21: Escalation review — if no response, AE makes personal reach out to C-suite

Escalation Trigger: Any response to SDR + meeting booked = automatic stage change to SDR Qualified; AE assigned and marketing pauses campaign

Exit Criteria: Demo booked; OR account scores into Tier 4; OR 35 days without any signal fire (account moves back to Tier 2 nurture)

---

**SECTION 1: Executive Summary**

Companies using signal-triggered demand generation report 2.4x higher SDR-to-meeting rates (SiriusDecisions 2025) and 31% shorter sales cycles compared to cadence-only outreach. For Proxara, building this command center is projected to increase marketing-influenced pipeline by 40-55% within two quarters by ensuring the right campaign fires within 24 hours of each account showing intent — rather than waiting for the next scheduled campaign blast.

Implementation complexity is moderate — primarily configuration work in existing tools (HubSpot + Salesforce + Bombora + G2 Buyer Intent). Phase 1 can be live in 28 days with 2-3 hours of marketing ops time per week. Phase 3 full automation requires approximately 60 hours of total setup time across marketing, sales ops, and RevOps.

---

## Success Metrics

**Weekly Signal Health Dashboard:**
- Accounts in Tier 3-4 (Hot + Surging): Target 5-8% of total named account list; alert if <3%
- Tier upgrade rate: % of accounts that moved up one tier this week; target 12-18% of Tier 1-2 accounts
- Campaign enrollment SLA: % of newly Hot accounts enrolled in correct playbook within 24 hours; target >90%
- SDR alert response rate: % of SDR alerts where outreach was initiated within 4 hours; target >80%

**Monthly Pipeline Attribution:**
- Signal-influenced opportunities created: Target 60%+ of all new opportunities had CASS ≥41 at time of creation
- Average CASS at demo request: Should increase quarter-over-quarter as signal model improves lead quality
- Campaign playbook win rate vs. baseline: Hot playbook win rate should outperform standard cadence by ≥15 percentage points
- Signal-to-meeting rate: % of Tier 3-4 accounts that convert to booked meeting within 30 days; benchmark target 12-18%

**Quarterly Model Calibration:**
- Signal weight accuracy: For each signal type, calculate win rate of accounts where that signal was the highest-weight signal firing; adjust weights based on correlation to closed-won
- Tier threshold validation: Are accounts that score 61-80 actually closing at a higher rate than 41-60 accounts? If not, recalibrate thresholds

## Related Prompts

- [ABM Intent Data Activation & Buying Signal Prioritization Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md) — Layer ABM account prioritization on top of CASS scores to refine Tier 1-2 account handling
- [AI-Powered B2B SaaS Third-Party Intent Data Orchestration & Buyer Signal Activation Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Third-Party-Intent-Data-Orchestration-&-Buyer-Signal-Activation-Revenue-Intelligence-Engine.md) — Use this to design your Bombora/G2 intent data layer before building the full command center
- [AI-Powered B2B SaaS Demand Generation Waterfall Architecture & Marketing Funnel Conversion Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Demand-Generation-Waterfall-Architecture-&-Marketing-Funnel-Conversion-Intelligence-Engine.md) — Run a waterfall audit first to understand which funnel stages the command center should optimize most
- [Dark Funnel Unattributed Pipeline Intelligence Engine](../../05_Analytics-&-Marketing-Operations/KPI-Dashboard-Creation/Dark-Funnel-Unattributed-Pipeline-Intelligence-Engine.md) — Use to capture and attribute pipeline from accounts that engaged but never filled out a form — these are prime candidates for CASS signal-triggered activation

## Integration Tips

**HubSpot Marketing Hub:**
- Create a custom Company Property called "CASS Score" (Number type) and "CASS Tier" (Dropdown: Cold/Warming/Active/Hot/Surging). Update these daily via HubSpot Workflow using Property Math actions or via Salesforce sync.
- Build a HubSpot Active List for each CASS tier — e.g., "CASS Hot (61-80)" — and use it as the enrollment trigger for each campaign playbook Workflow. When a company enters the list, enroll all associated contacts in the tier-appropriate sequence.
- Use HubSpot's "Company Score" feature (if on Enterprise) to build a composite score natively from HubSpot web, email, and form events. Sync Bombora and G2 signals via Zapier or native integrations.

**Salesforce CRM:**
- Create an Account field "CASS Score" and "CASS Last Updated" timestamp. Build a Salesforce Flow that fires a Chatter post and Slack message (via Salesforce Slack integration) when CASS Score crosses tier thresholds.
- Add CASS Score to the Account list view for SDRs — sorted by descending score. SDRs should work their outreach queue by CASS order, not alphabetically or by account size alone.
- Build a "Signal Command Center" Account Report showing CASS Score, top signals firing, last SDR touch date, and open opportunity status — review weekly in demand gen standup.

**Bombora / G2 Buyer Intent:**
- Bombora: Create a Weekly Export of Company Surge data filtered to your 35 intent topics. Import to Salesforce via Bombora's native Salesforce integration or via CSV → Salesforce Data Loader. Map surge scores to account records and trigger score recalculation.
- G2: Use G2 Buyer Intent's direct HubSpot or Salesforce integration to push "G2 Profile Visit" and "Competitor Visit" events as Company Timeline Activities. Build a HubSpot Workflow that increments CASS by the G2 signal weight each time a G2 event fires.

**6sense:**
- If using 6sense as your ABM platform, use 6sense's AI-predicted "Buying Stage" (Awareness / Consideration / Decision / Purchase) as a direct input to CASS tier assignment. Map 6sense's Decision stage to CASS Hot, Purchase stage to CASS Surging.
- Use 6sense Segments as the trigger for campaign enrollment instead of HubSpot lists — 6sense native integrations push segment membership changes to Salesforce and Outreach automatically.

**Outreach / Salesloft:**
- Build separate Outreach Sequences for each CASS tier — with messaging aligned to the signal combination. When HubSpot or Salesforce signals a tier upgrade, auto-add the contact to the appropriate Outreach Sequence via Zapier or Salesforce trigger.
- Outreach's "Account AI Score" can be a secondary signal input to CASS — weight it at 3-5 points as a mid-weight signal.

**Zapier / Make (Integromat):**
- Build a Zapier automation: "When Salesforce Account CASS Tier changes to 'Hot' → Send Slack message to #hot-accounts channel with: Account Name, Industry, CASS Score, Top 3 Signals, Assigned SDR, Assigned AE, Link to Salesforce Account."
- Trigger: "When ZoomInfo alerts new VP Supply Chain hire at target account → Update Salesforce Account with trigger event → Increment CASS by 5 points → Add contact to New Executive Awareness campaign in HubSpot."

## Troubleshooting

**Problem: Too many accounts are scoring into "Hot" tier — SDRs are overwhelmed and ignoring alerts.**
Solution: Tighten tier thresholds immediately. If more than 8% of your named accounts are Hot at any time, your weights are too generous. Audit: which signals are firing most often? If "single email open" or "one blog post read" is inflating scores, either remove them from the model or reduce weight to 1-2. Implement a "minimum signals from 2+ different signal categories" rule before any account can score into Tier 3+ — this ensures multi-dimensional buying behavior, not noise.

**Problem: CASS scores aren't correlating to pipeline — Hot accounts are not converting at higher rates than Cold accounts.**
Solution: Run a 90-day cohort analysis: For all opportunities created in the last quarter, what was their CASS score at time of opportunity creation? If there's no meaningful correlation, your signal weights are miscalibrated. Common culprits: (1) Bombora intent topics are too broad/generic — narrow to 10-15 high-specificity topics; (2) Website signals are inflated by competitors and job seekers doing research — add IP filtering to exclude known competitor IP ranges and job-site referral traffic; (3) G2 visits are being triggered by your own team's monitoring — suppress your company's IP addresses from signal capture.

**Problem: Signals from different sources are arriving on different delays — the CASS model is out of sync.**
Solution: Standardize signal ingestion timing. Bombora updates weekly (accept this lag — set decay to account for it). G2 updates daily. HubSpot web and email are real-time. Build your CASS recalculation to run nightly rather than event-triggered — this normalizes all signal inputs into a single daily score update and prevents false "surges" from real-time partial data. Add a "CASS Last Calculated" timestamp field so SDRs know how fresh the score is before acting on it.

## Version History
- v1.0: Initial creation (auto-generated)
