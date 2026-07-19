# AI-Powered B2B SaaS Predictive Churn Intelligence & Marketing-Led Retention Revenue Recovery Analytics Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** churn-prediction, retention-analytics, customer-health, nrr, b2b-saas, revenue-recovery, marketing-automation, customer-success, cohort-analysis, predictive-analytics

## Overview

Deploys an AI analytics engine to predict customer churn 60–90 days before it happens by synthesizing product usage decay signals, support ticket sentiment, NPS trajectory, stakeholder engagement patterns, and contract renewal timelines — then generates a segmented, marketing-led intervention playbook that assigns every at-risk account to the right recovery motion (executive re-engagement, product adoption campaign, competitive lock-in content, or value realization sequence) and tracks revenue saved as a measurable marketing KPI. Use this when your NRR is below 110%, when CS is firefighting renewals reactively, or when marketing has no defined role in customer retention despite owning customer lifecycle data.

## Quick Copy-Paste Version

You are a senior customer retention analytics strategist specializing in B2B SaaS churn prediction and marketing-led revenue recovery.

I need a predictive churn intelligence system for my company that identifies at-risk accounts early, assigns the correct intervention, and measures marketing's contribution to retained revenue. Here is our situation:

Company: [Your Company Name]
Product: [What it does in 1 sentence]
ACV range: [e.g., $18K–$120K ARR]
Customer base: [X total customers, Y managed by CS, Z in low-touch/digital tier]
Renewal frequency: [Monthly / Annual / Multi-year]
Current NRR: [e.g., 98%]
Target NRR: [e.g., 115%]
CS platform: [Gainsight / ChurnZero / Totango / Planhat / Spreadsheets]
CRM: [Salesforce / HubSpot]
Product analytics: [Mixpanel / Amplitude / Heap / Pendo / None]
Primary churn reasons (anecdotally): [e.g., "low adoption, budget cuts, champion departure"]

Analyze our customer data and produce:

1. CHURN PREDICTION MODEL DESIGN
   - Define the 10 leading indicators that, when combined, predict churn with the highest accuracy for our business model. Include: product usage metrics (DAU/MAU ratio, feature adoption rate, login frequency decline), support signals (ticket volume spike, unresolved issues >7 days, CSAT drop), stakeholder signals (champion job change, executive sponsor disengagement, new economic buyer detected), and contract signals (renewal date proximity, QBR skipped, expansion conversation declined)
   - Assign a predictive weight to each signal based on its correlation with historical churn: high-weight (3 pts each), medium-weight (2 pts each), low-weight (1 pt each)
   - Build a Customer Health Score formula: sum of weighted signals on a 0–100 scale where 0–39 = Critical, 40–59 = At-Risk, 60–79 = Neutral, 80–100 = Healthy
   - Define the "Early Warning Window": the average number of days before renewal when health score drops below 60 in churned accounts

2. AT-RISK ACCOUNT SEGMENTATION
   - Segment at-risk accounts into 4 intervention tiers based on churn probability × ARR at risk:
     * Tier 1 (Rescue): Health score 0–39, ARR >$50K — requires immediate executive involvement + marketing air cover
     * Tier 2 (Stabilize): Health score 40–59, ARR >$25K — targeted re-engagement campaign + CS-led adoption push
     * Tier 3 (Monitor): Health score 40–59, ARR <$25K — automated digital nurture sequence + product adoption emails
     * Tier 4 (Watch): Health score 60–79 with 2+ deteriorating signals — proactive value content cadence to prevent further decay
   - For each tier, calculate: (# accounts × average ARR) = Revenue at Risk. This is marketing's addressable retention opportunity

3. MARKETING INTERVENTION PLAYBOOK BY TIER
   For each tier, define the specific marketing-led intervention:

   TIER 1 — RESCUE MOTION:
   - Executive sponsor outreach sequence: CMO or VP sends personalized video or email referencing specific ROI metrics from their account
   - Peer proof acceleration: deliver 2 customer case studies from their exact industry/use case within 72 hours
   - Competitive lock-in content: if competitor is in the deal, deliver differentiation assets to the champion and economic buyer simultaneously
   - Success story co-creation offer: invite the account to be featured in a case study, creating reciprocal commitment

   TIER 2 — STABILIZE MOTION:
   - Product adoption campaign: 4-email sequence targeting underutilized features directly correlated with retention (identify which features have 85%+ usage in accounts that renew vs. <30% in churned accounts)
   - Value realization report: auto-generated monthly ROI summary showing realized value vs. potential value unlocked with full feature adoption
   - Champion re-engagement: personalized LinkedIn touchpoint from a senior marketing or CS leader, not a template

   TIER 3 — DIGITAL NURTURE MOTION:
   - Automated 6-touch email sequence: education content on product features with <30% adoption, success stories from similar companies, product tips and tricks cadence
   - In-app personalized messaging: trigger contextual tooltips and feature discovery prompts based on which features are unused
   - Community invitation: invite users to product community or user group to increase stickiness through network effects

   TIER 4 — PROACTIVE VALUE MOTION:
   - Monthly value digest email: automated summary of ROI delivered, benchmarks vs. industry peers, new feature announcements relevant to their use case
   - Upsell content positioning: introduce expansion content early, before the account shows at-risk signals

4. CHURN SIGNAL MONITORING DASHBOARD
   - Design a weekly churn signal dashboard with: total accounts by health tier (count and % of ARR), week-over-week health score movement, top 10 accounts with fastest health score decline, revenue at risk by segment, intervention coverage rate (% of Tier 1+2 accounts with active marketing intervention)
   - Define the "Revenue Recovery Rate": (ARR retained from Tier 1+2 accounts that received intervention) ÷ (total ARR of Tier 1+2 accounts at intervention start) × 100
   - Set monthly targets: Tier 1 recovery rate >65%, Tier 2 recovery rate >80%, Tier 3 churn rate <15%

5. CHAMPION DEPARTURE RESPONSE PROTOCOL
   - When a champion leaves (detected via LinkedIn change or CS notification), trigger within 24 hours: (1) stop all automation to the departed contact, (2) identify the most engaged remaining contact as interim champion, (3) send a senior executive introduction email from the CMO or VP to the new contact, (4) deliver a "value delivered to date" briefing document
   - Design a 30-day "re-onboarding" content sequence for the new champion covering: product value recap, team success stories, upcoming roadmap preview, peer community invitation

6. EXPANSION SIGNAL DETECTION (ANTI-CHURN)
   - Identify the 5 behavioral signals in healthy accounts that predict expansion readiness: high feature adoption rate (>70% of core features used), team expansion (new users added in last 30 days), product usage growth (>20% MAU increase), cross-functional usage (3+ departments using product), QBR engagement (executive attended last review)
   - For accounts showing 3+ expansion signals, trigger an upsell/cross-sell marketing motion: personalized ROI report + expansion proposal from AE + case study from a customer who expanded under similar conditions
   - This converts retention marketing into expansion revenue marketing

7. MARKETING'S CONTRIBUTION TO NRR
   - Define how marketing measures its retention contribution: (ARR saved in Tier 1 accounts with marketing intervention) + (ARR retained in Tier 2 accounts with marketing-sourced re-engagement) + (expansion ARR from marketing-triggered upsell motion) = Marketing-Contributed NRR Impact
   - Set up a monthly "Retention Marketing Revenue Report" showing: revenue at risk at month start, intervention coverage, revenue saved, NRR movement, and marketing's specific contribution vs. CS-only accounts

Format output as a Churn Intelligence Command Center with: a health scoring formula, a tiered intervention matrix, a weekly monitoring dashboard template, and a monthly marketing retention contribution report.

## Advanced Customizable Version

ROLE: You are an AI Predictive Churn Intelligence Engine — a specialized analytics system combining the statistical rigor of a data scientist, the operational depth of a VP of Customer Success, and the revenue attribution expertise of a marketing operations leader. You model churn probability with the precision of an ML system, then translate risk signals into marketing-executable intervention playbooks that save revenue and grow NRR.

CONTEXT:
- Company type: [B2B SaaS / B2B Software / B2B Platform]
- Business model: [Subscription / Usage-based / Hybrid]
- Market segment: [SMB / Mid-Market / Enterprise / Mixed]
- Revenue model: [ARR / MRR / Consumption]
- Customer success model: [High-touch / Tech-touch / Digital / Mixed by segment]
- Current gross revenue retention (GRR): [e.g., 82%]
- Current net revenue retention (NRR): [e.g., 98%]
- Primary churn root causes (from exit interviews): [List top 3]
- Average renewal cycle: [Monthly / Annual / Multi-year]
- Typical champion seniority: [VP / Director / Manager / Individual Contributor]
- Data infrastructure: [CRM + CS Platform + Product Analytics + Data Warehouse]

OBJECTIVE: Design a fully AI-automated churn prediction and marketing-led retention revenue system that:
1. Predicts churn 60–90 days before renewal with >75% accuracy
2. Segments at-risk accounts by revenue impact and recovery probability
3. Assigns every at-risk account to the optimal marketing intervention motion
4. Measures marketing's contribution to retained ARR as a board-level metric
5. Converts the retention engine into an expansion revenue engine for healthy accounts

CHURN PREDICTION MODEL (ADVANCED):

SIGNAL CATEGORY 1 — PRODUCT ENGAGEMENT DECAY (Weight: 40% of health score)
- Primary signal: 30-day rolling average of daily active users (DAU) as % of total licensed seats. Threshold: <15% DAU/seat ratio = HIGH churn risk
- Secondary signal: Core feature adoption rate. Define "core features" as the 3–5 features present in >90% of renewed accounts. Accounts with <40% core feature adoption are 3.2x more likely to churn (benchmark for SaaS industry)
- Tertiary signal: Last login recency. No login in 14 days by any user = amber flag; 30+ days = red flag
- Power user ratio: % of licensed seats that log in 3+ days/week. Accounts with <1 power user per 10 seats churn at 2.4x the rate of accounts with 3+ power users per 10 seats
- Integration depth: Number of active API integrations or connected tools. Accounts with 0 integrations churn at 67% higher rate than accounts with 2+

SIGNAL CATEGORY 2 — SUPPORT & SENTIMENT SIGNALS (Weight: 25% of health score)
- Support ticket velocity: 3x increase in ticket volume in any 30-day period = predictive of churn within 90 days in 58% of cases
- Open critical tickets: Any unresolved P0/P1 ticket >72 hours is a direct churn accelerant
- NPS trajectory: A 20+ point NPS decline over 2 consecutive surveys overrides all other signals — immediate Tier 1 escalation regardless of other health indicators
- CSAT trend: 3 consecutive support CSAT scores below 3.5/5 = health score penalty of 20 points
- Community/forum activity: Accounts with zero community participation in 90 days are 1.8x more likely to churn

SIGNAL CATEGORY 3 — STAKEHOLDER & RELATIONSHIP SIGNALS (Weight: 20% of health score)
- Champion departure detection: LinkedIn job change monitoring on all executive-level contacts. Champion departure without successful relationship transfer = 71% churn probability within 6 months
- QBR attendance rate: Executive sponsor attendance at last 2 QBRs. Zero executive attendance = relationship risk signal
- Outreach response decay: CS email response rate below 40% or 3 consecutive unanswered touchpoints
- Multi-threading depth: Number of unique contacts engaged by CS + marketing in last 90 days. Single-threaded accounts (1 contact) churn at 2.9x rate of multi-threaded accounts (4+ contacts)
- Economic buyer engagement: CFO/VP Finance has never been engaged in an annual contract renewal = financial-risk flag

SIGNAL CATEGORY 4 — BUSINESS CONTEXT SIGNALS (Weight: 15% of health score)
- Renewal date proximity with no renewal conversation started: <90 days to renewal with no expansion discussion = risk signal
- Company-level firmographic changes: Layoff announcements, funding difficulties, acquisition activity, or CEO change all increase churn probability 40–65% depending on context
- Budget cycle pressure: Q4 renewal dates correlate with 23% higher churn rate than Q1/Q2 renewals in B2B SaaS (budget reallocation risk)
- Contract downsell request: Any request to reduce seats or modules — even if accepted — increases full churn probability 3x unless proactively managed

COMPOSITE HEALTH SCORE CALCULATION:
- Raw score = (Product Engagement Decay Score × 0.40) + (Support & Sentiment Score × 0.25) + (Stakeholder Signals Score × 0.20) + (Business Context Score × 0.15)
- Normalize to 0–100 scale
- Apply override rules: Champion departure OR NPS drop >20 points → cap score at 45 regardless of other signals
- Apply bonus rules: 3+ expansion signals present → add 15 point bonus, cap at 100

TIERED INTERVENTION MATRIX (ADVANCED):

TIER 1 — EXECUTIVE RESCUE (Health 0–39 + ARR ≥$50K):
Revenue at risk treatment: CMO/CEO level intervention
- Day 1: CMO sends personalized video email to economic buyer (not champion) — 30-second video acknowledging account relationship, requesting 30-minute strategic conversation. Do NOT send from CS
- Day 3: Marketing delivers "Account Value Intelligence Brief" — a personalized 1-page PDF showing: (1) quantified ROI delivered YTD, (2) peer benchmark comparison (anonymized), (3) 3 specific unrealized value opportunities
- Day 7: Invite to exclusive executive advisory event or VIP roundtable — this creates a reciprocal commitment anchor
- Day 14: Competitive intelligence briefing if competitor is involved — 3-page document addressing specific competitive objections with customer proof
- Day 21: Expansion proposal from AE + marketing brief — reframe the conversation from renewal defense to growth partnership

TIER 2 — PRODUCT ADOPTION STABILIZATION (Health 40–59 + ARR $25K–$49K):
Revenue at risk treatment: Targeted campaign + CSM collaboration
- Week 1: 3-part "Quick Wins" email sequence targeting the highest-impact underutilized features — each email demonstrates one use case with a 90-second video walkthrough and a "do this in 5 minutes" CTA
- Week 2: Personalized product adoption report sent by CS with subject line "[Company Name] — 3 features your competitors are using that you haven't tried yet"
- Week 3: Invitation to a product-use-case webinar with a customer who had similar adoption challenges and now achieves X ROI metric
- Week 4: CS-led adoption review call with marketing-created "feature adoption starter kit" — a tailored guide for their specific use case

TIER 3 — DIGITAL RETENTION NURTURE (Health 40–59 + ARR <$25K):
Revenue at risk treatment: Automated marketing sequence, no human intervention unless escalated
- 8-touch automated email program over 6 weeks:
  * Emails 1–2: "Your [Product] success snapshot" — automated ROI summary using product data
  * Emails 3–4: Feature spotlight series on underused capabilities with embedded 60-second product tours
  * Emails 5–6: Customer success story from identical company size/industry/use case
  * Emails 7–8: Renewal readiness check-in — "What would make [Product] a no-brainer to renew?"
- In-app notification layer: 3 contextual in-app prompts triggered on next login, guiding toward adoption of the top 2 unused features
- Community nudge: automated invitation to relevant community group or upcoming product education webinar

TIER 4 — PROACTIVE VALUE REINFORCEMENT (Health 60–79 with 2+ deteriorating signals):
Revenue at risk treatment: Prevention before escalation
- Monthly automated Value Digest email: auto-generated report showing ROI metrics, peer benchmarks, and new feature announcements relevant to their use case (requires integration with product analytics and CRM)
- Quarterly business value survey: 3-question NPS-adjacent survey asking about realized value, top frustration, and expansion interest — results routed to CS for follow-up within 24 hours of submission
- Roadmap preview content: when relevant product releases are upcoming, send personalized "what's coming for you" email highlighting features that address their known use cases

REVENUE RECOVERY MEASUREMENT FRAMEWORK:

Primary metric — Marketing-Attributed Retained ARR:
- Definition: ARR from accounts that received a Tier 1 or Tier 2 marketing intervention AND renewed within 6 months, where marketing touchpoints were the last engagement before renewal decision
- Tracking: Tag all intervention accounts in CRM with campaign source; measure renewal outcome and ARR value at renewal date
- Target: Marketing-attributed retained ARR ≥ 15% of total ARR renewed in a given quarter

Secondary metric — Intervention Conversion Rate by Tier:
- Tier 1 rescue conversion target: 60–70% of intervened accounts renew at full ARR or higher
- Tier 2 stabilization conversion target: 75–85% of intervened accounts renew
- Tier 3 digital nurture conversion target: 50–65% of intervened accounts renew (self-serve)

Tertiary metric — NRR Marketing Contribution:
- Formula: (Tier 1 ARR retained + Tier 2 ARR retained + expansion ARR from marketing-triggered upsell) ÷ Total NRR movement in period
- Goal: Marketing can claim direct contribution to 20–35% of total NRR improvement

CHAMPION DEPARTURE RESPONSE AUTOMATION (ADVANCED):
- Detection method: LinkedIn Sales Navigator API, Lusha, or ZoomInfo Alerts trigger within 24–72 hours of job change
- Auto-response sequence when champion departure detected:
  * Hour 0: CS receives Slack notification with account health score, revenue at risk, and suggested next action
  * Hour 4: Marketing pauses all automation sequences to the departed contact
  * Hour 24: CMO or VP Marketing sends a "warm introduction" email to the highest-engaged remaining contact OR the person who recently joined in the champion's role (identified via LinkedIn)
  * Day 3: Marketing delivers "What We've Built Together" document — a personalized ROI summary and success story from this account's journey, designed to brief the new contact and create a relationship anchor
  * Day 7: Invitation to a 30-minute "new champion success session" — product education call with a senior CSM and a marketing-curated success story from a peer company

EXPANSION IDENTIFICATION FROM RETENTION DATA:
- Expansion trigger criteria: Health score 80–100 + 3 of the following: (1) DAU/seat ratio >60%, (2) 3+ new users added in 30 days, (3) 5+ support tickets (indicating active use, not frustration), (4) NPS 9–10 in last survey, (5) attended 2+ product webinars in 90 days
- Expansion marketing motion: Personalized "Growth Opportunity Report" showing how similar accounts at their usage level achieved X% ROI increase by expanding to Module Y or Tier Z — include 2 customer proof points from their industry

OUTPUT FORMAT: Produce a Retention Revenue Command Center with:
1. Customer Health Score Formula (weighted, with override rules)
2. At-Risk Account Segmentation Matrix (tier × ARR × intervention motion)
3. Intervention Playbook by Tier (with exact email subject lines, timing, and success criteria)
4. Marketing-Attributed Retained ARR Tracking Dashboard
5. Monthly Retention Marketing Performance Report Template
6. Champion Departure Response SOP
7. Expansion Signal Detection Playbook

## Example Input/Output

**Input Example:**
- Company: Datastream Analytics (B2B SaaS data pipeline tool)
- ACV range: $24K–$180K ARR
- Customer base: 340 accounts; 85 managed (Enterprise), 255 digital-touch (Mid-Market/SMB)
- Current NRR: 96% (GRR: 89%)
- CS platform: Gainsight
- Product analytics: Amplitude
- Top churn reasons: "low adoption by ops teams (not just the buyers), champion moved to new company, 'too complex to implement without more support'"
- Renewal cycle: Annual

**Output Example (condensed):**

**Datastream Analytics — Churn Intelligence Command Center**

**Health Score Formula:**
Score = (Product Engagement: DAU/seat ratio×15 + Feature adoption rate×10 + Power user ratio×10 + Integration depth×5) + (Support: Ticket velocity×10 + Open critical tickets×8 + NPS trajectory×7) + (Stakeholder: Champion status×10 + QBR attendance×5 + Multi-thread depth×5) + (Business Context: Renewal proximity×5 + Firmographic risk×5 + Downsell request×5)

**Priority Interventions — Tier 1 (Critical) Accounts Identified:**
- Apex Manufacturing ($147K ARR) — Health: 28/100. Champion departed 3 weeks ago. New VP Operations just hired. Trigger: CMO outreach + "Value Delivered" brief within 24 hours. Intervention assigned to: CMO Diane Mercer + AE Tom Reyes.
- Pacific Freight Co. ($89K ARR) — Health: 31/100. 0 logins by operations team in 45 days. NPS dropped from 8 to 4. Trigger: Executive rescue motion + product adoption intervention. Assign dedicated implementation specialist for 30-day sprint.

**Revenue at Risk Summary:**
- Tier 1 (9 accounts): $1.24M ARR | Expected recovery at 65%: $806K retained
- Tier 2 (23 accounts): $890K ARR | Expected recovery at 80%: $712K retained
- Tier 3 (41 accounts): $520K ARR | Expected recovery at 58%: $302K retained
- Total marketing-addressable retention opportunity: $2.65M ARR, expected save: $1.82M

**Recommended Immediate Actions:**
1. Launch Tier 1 executive outreach for 9 accounts within 48 hours — assign to CMO + 2 senior executives
2. Activate Tier 2 "3 Quick Wins" email series for 23 accounts starting Monday
3. Configure Gainsight automated alerts for any account dropping below 50 health score with >72hr lag in detection
4. Build monthly "Retention Marketing Contribution Report" measuring ARR saved vs. CS-only cohort

## Success Metrics

- **Prediction accuracy:** Health score model correctly identifies 70%+ of accounts that churn 60+ days before renewal
- **Tier 1 rescue rate:** 60–70% of Tier 1 accounts with full intervention motion renew at full or expanded ARR
- **Revenue recovery:** Marketing-attributed retained ARR covers at least 3x the cost of running retention marketing programs
- **NRR movement:** NRR improves by 5–8 percentage points within 2 renewal cycles of implementing the full system
- **Detection speed:** At-risk accounts identified an average of 75+ days before renewal date (vs. 30-day reactive detection)
- **Champion departure response:** 100% of champion departures receive intervention within 48 hours; new relationship established within 14 days
- **Expansion conversion:** 25%+ of Tier 4 proactive accounts enter an upsell or cross-sell conversation within 90 days

## Related Prompts

- [`../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/AI-Powered-B2B-At-Risk-Account-Marketing-Rescue-&-Churn-Prevention-Campaign-Intelligence-Engine.md`](../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/AI-Powered-B2B-At-Risk-Account-Marketing-Rescue-&-Churn-Prevention-Campaign-Intelligence-Engine.md) — Campaign execution engine for at-risk accounts
- [`../../05_Analytics-&-Performance/Customer-Lifecycle-Marketing-Analytics/AI-Powered-B2B-SaaS-Customer-Health-Score-Intelligence-&-Proactive-Marketing-Intervention-Architecture-Engine.md`](../../05_Analytics-&-Performance/Customer-Lifecycle-Marketing-Analytics/AI-Powered-B2B-SaaS-Customer-Health-Score-Intelligence-&-Proactive-Marketing-Intervention-Architecture-Engine.md) — Health score architecture and proactive intervention design
- [`../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/Customer-Lifetime-Value-Prediction-&-Acquisition-Investment-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/Customer-Lifetime-Value-Prediction-&-Acquisition-Investment-Intelligence-Engine.md) — CLV modeling and acquisition investment optimization
- [`../../05_Analytics-&-Performance/Win-Loss-Analytics/AI-Powered-B2B-SaaS-Deal-Win-Pattern-Intelligence-&-Revenue-Replication-Analytics-Engine.md`](../../05_Analytics-&-Performance/Win-Loss-Analytics/AI-Powered-B2B-SaaS-Deal-Win-Pattern-Intelligence-&-Revenue-Replication-Analytics-Engine.md) — Win pattern analysis to understand what high-retention customers look like at acquisition

## Integration Tips

- **Gainsight / ChurnZero / Totango:** Feed the Health Score formula into your CS platform's native scoring engine. Use Gainsight's Cockpit or ChurnZero's ChurnScore field to surface Tier 1/2 alerts to CSMs in real time. Map each signal to a Gainsight data source (product usage via Gainsight PX, support via Zendesk connector, NPS via Gainsight NPS module)
- **Salesforce:** Create a custom "Retention Risk" field on the Account object with a picklist (Tier 1/2/3/4/Healthy). Use Salesforce Flow to trigger task assignments to AEs when an account enters Tier 1. Build a Retention Revenue dashboard tracking ARR at risk by tier and intervention status
- **HubSpot:** Use HubSpot's Contact Activity and Company properties to track health signals. Create a "Churn Risk" workflow that enrolls accounts into the appropriate intervention sequence based on health score calculation. Use HubSpot's Revenue Analytics to measure retained ARR from intervention campaigns
- **Marketo / Pardot:** Build smart campaigns with multi-criteria enrollment logic — account health tier AND ARR threshold AND last engagement date — to auto-enroll accounts into the correct drip sequence. Use dynamic content to personalize intervention emails with account-specific product usage data pulled via CRM merge fields
- **Amplitude / Mixpanel:** Set up Amplitude's Compass or Mixpanel's Retention report to automatically flag the product engagement signals (DAU/seat, feature adoption, power user ratio) and push scores to your CRM daily via API or Zapier
- **LinkedIn Sales Navigator:** Enable Job Change Alerts on all champion contacts. Route alerts via Slack integration to the CS owner and CMO within 4 hours. Build a Zapier zap: LinkedIn alert → Salesforce task → HubSpot workflow enrollment for champion departure sequence
- **Slack:** Build a #retention-alerts channel that receives automated daily digests from Gainsight or your CRM: "3 accounts dropped below 50 health score today. Total ARR at risk: $287K. CSM assignments: [names]." Include one-click link to account record and intervention playbook

## Troubleshooting

**Problem:** Health score model is flagging too many false positives (accounts show as at-risk but renew without intervention), overwhelming CS and marketing with unnecessary work.
**Solution:** Recalibrate signal weights by running a retrospective analysis on 12 months of churned vs. renewed accounts. Identify which signals had the strongest actual correlation with churn outcomes. Raise the weight threshold for signals that proved most predictive; reduce or remove signals that were noise. Also raise the Tier 1 ARR threshold from $50K to your 75th percentile ACV to narrow executive escalation to only the highest-value accounts.

**Problem:** Marketing doesn't have access to product usage data, so the health score can't be automated — it requires CS to manually update a spreadsheet.
**Solution:** This is a data infrastructure problem, not a strategy problem. Interim fix: export Amplitude/Mixpanel weekly reports as CSV → upload to CRM manually or via Zapier. Long-term fix: instrument a data warehouse (Snowflake, BigQuery) to pull product analytics, CRM, and support data into a unified customer health view, then expose it to HubSpot/Salesforce via reverse ETL (Census, Hightouch). Prioritize this as a Q1 marketing ops investment — without product data, retention marketing is flying blind.

**Problem:** CS team resists marketing involvement in customer accounts, viewing retention as exclusively their domain.
**Solution:** Reframe marketing's role as providing air cover and content, not replacing CS relationships. Start with the assets CS already wants but doesn't have time to create: personalized value reports, industry case studies, executive briefing documents. Prove the model in one renewal cohort: select 20 Tier 2 accounts where marketing runs the intervention alongside CS. Measure renewal rate vs. a CS-only control group of 20 similar accounts. Present the revenue delta to the CRO — this creates internal alignment through data, not persuasion.

## Version History

- v1.0: Initial creation (auto-generated)
