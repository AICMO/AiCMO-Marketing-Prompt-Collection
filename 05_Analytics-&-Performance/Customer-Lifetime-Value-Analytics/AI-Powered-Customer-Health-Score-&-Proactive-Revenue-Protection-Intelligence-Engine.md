# AI-Powered Customer Health Score & Proactive Revenue Protection Intelligence Engine - Predict Churn Before It Happens and Protect NRR

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, saas, analytics, churn-prevention, customer-health, nrr, retention, automation, gainsight, ltv

## Overview
Builds a comprehensive AI-powered customer health scoring model using product usage, engagement, support, and relationship signals — then designs automated alert workflows and intervention playbooks to protect net revenue retention. Use this when you need to systematically identify at-risk accounts 60–90 days before renewal, scale your CS team's capacity, or reduce reactive firefighting with a proactive revenue protection system.

## Quick Copy-Paste Version

You are a senior Customer Success and Revenue Analytics expert. I need a complete Customer Health Scoring system to protect my recurring revenue.

Here is my data:
- Product/service: [brief description]
- ARR: [$X] with [X] customers
- Current annual churn rate: [X%]
- Net Revenue Retention: [X%]
- CS team size: [X CSMs managing X accounts each]
- Tools available: [CRM (HubSpot/Salesforce), product analytics (Amplitude/Mixpanel/Pendo), support (Zendesk/Intercom), CS platform (Gainsight/Totango/ChurnZero/Spreadsheet)]
- Customer segments: [e.g., SMB (<$10K ARR), Mid-Market ($10K-$100K ARR), Enterprise (>$100K ARR)]
- Key product actions that indicate value: [e.g., reports generated, integrations connected, seats active, API calls made]

Please deliver:
1. Health score model with 5-7 weighted signals across four dimensions: product usage, engagement, support health, and relationship strength
2. Scoring formula: weighted 0-100 score with Green (70-100), Yellow (40-69), Red (0-39) thresholds
3. Top 3 leading indicators that predict churn 60+ days out (based on my product data)
4. Automated alert triggers: what signals should fire a CS alert, what fires an executive escalation
5. Intervention playbook by risk tier: what CS should do in the first 48 hours when an account turns red
6. Expansion signal identification: which health patterns predict upsell/expansion readiness
7. Monthly health score review cadence and reporting format for CMO/CRO dashboard
8. 30-day implementation roadmap to go from zero to live health scoring

Format with tables where useful. Flag any data gaps.

## Advanced Customizable Version

ROLE: You are a VP of Customer Success Strategy and Revenue Analytics with 15+ years of B2B SaaS experience. You specialize in building health scoring frameworks, proactive churn prevention programs, and CS-to-marketing revenue loops. You have deep expertise in Gainsight, Totango, ChurnZero, Salesforce, HubSpot, Amplitude, Pendo, Mixpanel, and Zendesk. You understand the math of NRR, GRR, logo churn, and revenue churn and how health scoring directly impacts these metrics.

COMPANY CONTEXT:
- Company: [Company Name]
- Stage: [Series A / B / C / Growth / Public]
- ARR: [$X] | MRR: [$X]
- Total customers: [X] logos
- Average contract value (ACV): [$X]
- Contract type: [Annual / Month-to-month / Multi-year]
- Average renewal cycle: [X months notice required before renewal date]
- Current annual logo churn: [X%]
- Current annual revenue churn: [X%]
- Net Revenue Retention (NRR): [X%]
- Gross Revenue Retention (GRR): [X%]
- CS team: [X CSMs], ratio: [X:1 accounts per CSM]
- CS platform: [Gainsight / Totango / ChurnZero / HubSpot / Spreadsheet / None]

CUSTOMER SEGMENTS:
Segment 1: [Name, e.g., SMB] — ARR range: [$X–$X], CS model: [Digital / Low-touch]
Segment 2: [Name, e.g., Mid-Market] — ARR range: [$X–$X], CS model: [Pooled / Named CSM]
Segment 3: [Name, e.g., Enterprise] — ARR range: [$X–$X], CS model: [Dedicated CSM + AE]

AVAILABLE DATA SIGNALS (check all that apply and provide field names):
Product Usage:
- [ ] Daily/weekly/monthly active users (DAU/WAU/MAU): [field name]
- [ ] Feature adoption breadth (# features used): [field name]
- [ ] Core value action completions (define your "aha moment" action): [field name]
- [ ] Seat utilization (seats used / seats licensed): [field name]
- [ ] API call volume or integration activity: [field name]
- [ ] Session frequency and depth: [field name]
- [ ] Mobile vs. desktop activity: [field name]

Engagement:
- [ ] Executive sponsor engagement (C-suite login or attendance): [field name]
- [ ] Training completion rate: [field name]
- [ ] Community/forum participation: [field name]
- [ ] Email open/click rates for CS communications: [field name]
- [ ] QBR / business review attendance: [field name]
- [ ] NPS score and recency: [field name]
- [ ] CSAT score: [field name]

Support Health:
- [ ] Open critical/high tickets: [field name]
- [ ] Ticket volume trend (MoM): [field name]
- [ ] Average ticket resolution time: [field name]
- [ ] Escalations to engineering or leadership: [field name]
- [ ] Bug reports filed: [field name]

Relationship Strength:
- [ ] CSM sentiment score (manual input): [field name]
- [ ] Champion status (defined, confirmed): [field name]
- [ ] Executive sponsor status: [field name]
- [ ] Contract signed date (age of relationship): [field name]
- [ ] Last meaningful CSM touchpoint: [field name]
- [ ] Renewal signed in advance: [field name]

Financial Signals:
- [ ] Days to renewal: [field name]
- [ ] Outstanding invoices / late payments: [field name]
- [ ] Expansion signals (added seats, new modules evaluated): [field name]
- [ ] Downsell risk (requested seat reduction or plan downgrade): [field name]

ANALYSIS REQUESTED:

**1. HEALTH SCORE MODEL DESIGN**

For each of the four health dimensions, design a weighted sub-score:

Dimension A — Product Adoption (recommended weight: 35%):
- Select the 2-3 most predictive signals from the product usage list above
- Define scoring rubric for each signal: what constitutes a 10/10 vs. 5/10 vs. 0/10
- Show calculation formula
- Explain why these signals predict retention vs. churn (use Jobs-to-be-Done logic: are they getting the core job done?)

Dimension B — Engagement (recommended weight: 25%):
- Select the 2-3 most predictive engagement signals
- Define "healthy engagement" thresholds by segment (SMB vs. Enterprise thresholds differ)
- Penalize heavily for: no executive sponsor, no QBR in 90+ days, NPS detractor (0-6) with no follow-up

Dimension C — Support Health (recommended weight: 20%):
- Flag: >2 critical open tickets = automatic Yellow floor
- Flag: any escalation to engineering or executive = automatic Red floor
- Ticket velocity trend matters more than absolute volume: 3 tickets this month vs. 1/month average = warning

Dimension D — Relationship Strength (recommended weight: 20%):
- Champion strength is the most important single signal in this dimension
- Losing a champion (job change, departure) should trigger immediate CSM alert regardless of other scores
- CSM sentiment acts as an override: if CSM marks "At Risk," score floors at Yellow even if data says Green

COMPOSITE SCORING:
- Composite Health Score = (Adoption × 0.35) + (Engagement × 0.25) + (Support × 0.20) + (Relationship × 0.20)
- Score range: 0–100
- Green Zone: 70–100 (Healthy — focus on expansion)
- Yellow Zone: 40–69 (Neutral — monitor and proactively engage)
- Red Zone: 0–39 (At Risk — immediate intervention required)
- Critical Flag: Any single dimension score of 0–15 triggers Red regardless of composite (e.g., catastrophic support crisis)

**2. CHURN PREDICTION SIGNALS (LEADING INDICATORS)**

Using the data signals provided, identify:

Early Warning Pattern #1 (30-day signal):
- Signal description: [What changes in the data?]
- How far before churn does this appear on average?
- What % of churned accounts showed this pattern? (target: >60% to be a useful signal)
- What % of healthy accounts showed this pattern? (target: <20% to avoid false positives)
- Recommended automated alert: [Slack notification to CSM / Email to CS team / CRM task created]

Early Warning Pattern #2 (60-day signal):
[Same format]

Early Warning Pattern #3 (90-day signal):
[Same format]

Expansion Readiness Pattern:
- Signal description: [What data patterns indicate a customer is ready for upsell?]
- Recommended expansion trigger: [Automated task for CSM / AE notification / In-app expansion prompt]

**3. AUTOMATED ALERT SYSTEM DESIGN**

Design a three-tier alert system:

Tier 1 — CSM Alert (self-managed):
Trigger conditions: [e.g., score drops 10+ points in 14 days, DAU drops >30% week-over-week, NPS detractor submitted]
Notification: Slack DM to CSM + Gainsight/CRM task created
CSM response SLA: [X hours / X business days]
Required action: [e.g., CSM logs a "Save Play" and schedules discovery call within 48 hours]

Tier 2 — CS Manager Escalation:
Trigger conditions: [e.g., score in Red Zone for 14+ consecutive days, high-ARR account ($100K+) drops to Yellow, champion departure detected, renewal within 60 days with Red score]
Notification: Slack alert to CSM + CS Manager tag + CRM escalation flag
Response SLA: [CS Manager must review within 24 hours and approve intervention plan]
Required action: [Executive sponsor outreach, internal account strategy meeting]

Tier 3 — Executive Escalation:
Trigger conditions: [e.g., strategic account (>$250K ARR) in Red Zone, customer threatens cancellation via support or CSM, contract non-renewal communicated]
Notification: Slack alert to CRO + VP CS + Account Executive
Response SLA: [Same business day]
Required action: [CRO call within 48 hours, executive-to-executive outreach, emergency QBR offer]

**4. INTERVENTION PLAYBOOKS BY RISK TIER**

Yellow Zone Playbook (Proactive):
Step 1 (Day 0–2): CSM completes internal account review — review last 90 days of product usage, support history, and relationship notes
Step 2 (Day 2–5): CSM sends personalized check-in email referencing specific value metrics and invites to next business review
Step 3 (Day 5–14): If no response or continued decline, CSM calls champion — goal is discovery, not pitch
Step 4 (Day 14–30): If still declining, involve CS Manager, consider bringing in a product specialist for a value realization session
Success metric: Account returns to Green Zone within 30 days of triggering Yellow alert

Red Zone Playbook (Emergency Save):
Step 1 (Day 0–24 hours): CSM calls champion and executive sponsor — discovery questions: "What's changed? What's getting in the way?"
Step 2 (Day 1–3): Internal war room: CSM + CS Manager + AE + Product review account. Identify root cause (adoption gap, unresolved technical issue, business change, competitive displacement, budget)
Step 3 (Day 3–7): Design customized recovery plan based on root cause. If adoption gap → assign onboarding specialist. If technical → priority engineering ticket. If competitive → bring in competitive playbook + executive sponsor
Step 4 (Day 7–30): Weekly check-ins, track health score weekly, escalate to Tier 3 if score does not improve ≥10 points in 14 days
Step 5 (Day 30): Go / No-Go decision: if save is unlikely, initiate graceful offboarding to protect referenceability; if save is likely, extend recovery timeline and document learnings

Champion Departure Emergency Playbook:
Trigger: LinkedIn data / ZoomInfo / champion notifies CSM of departure
Step 1 (Day 0–48 hours): Ask departing champion for warm introduction to successor and internal champion
Step 2 (Day 3–7): CS Manager reaches out directly to VP/Director of new champion's team
Step 3 (Day 7–30): Schedule onboarding session for new champion; send "New Leader Business Review" showing value delivered to their team
Success metric: New champion confirmed and engaged within 30 days

**5. EXPANSION IDENTIFICATION SYSTEM**

Expansion Readiness Score (separate from health score):
- Composite score 0–100 combining: product breadth utilization >80%, high DAU/seat ratio (>75%), NPS ≥8, no open critical tickets, contract age >9 months
- Score ≥70: Trigger AE + CSM expansion play
- Specific expansion signals to monitor:
  - Seats near cap (>85% utilization) → automatic seat expansion prompt
  - Power users using features outside their licensed tier → upgrade conversation
  - Multi-department usage (beyond original buying center) → new department expansion play
  - Executive using product personally (not just report recipients) → executive expansion conversation

**6. CMO/CRO HEALTH SCORE DASHBOARD**

Weekly Revenue Protection Metrics:
| Metric | This Week | Last Week | 30-Day Trend | Target |
|--------|-----------|-----------|--------------|--------|
| % Customers in Green Zone | | | | >70% |
| % Customers in Yellow Zone | | | | <20% |
| % Customers in Red Zone | | | | <10% |
| ARR in Red Zone ($) | | | | <5% of total ARR |
| Accounts turned Red this week | | | | |
| Saves completed this month | | | | |
| Save rate (saves / Red accounts) | | | | >60% |
| Early expansion pipeline from health signals | | | | |

Monthly Executive Metrics:
- Projected logo churn next 90 days (Red accounts at risk)
- Projected revenue churn next 90 days (ARR of Red accounts × probability of churn)
- NRR trend (rolling 12-month)
- Health score distribution change MoM
- Intervention ROI: ARR saved from Yellow/Red interventions vs. cost of CS team

**7. IMPLEMENTATION ROADMAP**

Phase 1 — Foundation (Days 1–14):
- [ ] Map all available data signals to the four dimensions above
- [ ] Agree on segment-specific scoring thresholds (SMB vs. Enterprise behave differently)
- [ ] Configure health score formula in your CS platform or build in Google Sheets/Notion
- [ ] Backfill 90 days of data to score current accounts immediately
- [ ] Define escalation routing and notification channels (Slack channels, CRM owners)

Phase 2 — Activation (Days 15–30):
- [ ] Train all CSMs on playbooks — run tabletop exercise with one real at-risk account
- [ ] Configure automated alerts in Gainsight / Totango / Zapier
- [ ] Launch weekly health score review in CS team standup
- [ ] Create CMO/CRO dashboard in Salesforce, HubSpot, or Notion
- [ ] Identify top 10 highest-ARR accounts in Yellow/Red — assign as immediate action items

Phase 3 — Optimization (Days 31–90):
- [ ] Run first month-end health score retrospective: which signals were most predictive?
- [ ] Calibrate scoring weights based on observed outcomes
- [ ] Add expansion signals to dashboard — identify first expansion plays triggered by health data
- [ ] Automate champion departure detection via LinkedIn Sales Navigator or ZoomInfo alerts
- [ ] Share NRR improvement results with board/investors

OUTPUT FORMAT: Use tables for all scoring models and dashboards. Bold critical thresholds and alert conditions. Provide copy-paste ready alert message templates for each escalation tier. Flag data gaps as [DATA GAP: X would improve accuracy]. End with a 30-60-90 day action plan.

## Example Input/Output

**Input Example:**

Company: Veridian Workflows (B2B SaaS, Series B)
Product: AI-powered operations automation platform for logistics companies
ARR: $8.2M, 147 customers
ACV: $55,800 average
NRR: 108%, Annual logo churn: 12%
CS team: 4 CSMs, ~37 accounts each
CS platform: HubSpot CRM + Gainsight (recently deployed)
Segments: SMB (<$25K ARR, 89 accounts), Mid-Market ($25K-$150K ARR, 47 accounts), Enterprise (>$150K ARR, 11 accounts)
Key value actions: workflow automations built, routes optimized per week, integrations connected, dispatch users active daily

---

**Output Example (condensed):**

**Health Score Model for Veridian Workflows:**

| Dimension | Weight | Key Signals | Green (7-10) | Yellow (4-6) | Red (0-3) |
|-----------|--------|-------------|--------------|--------------|-----------|
| Product Adoption | 35% | Automations built + routes/week | ≥5 automations active, ≥50 routes/week | 2-4 automations, 20-49 routes | <2 automations OR <20 routes |
| Engagement | 25% | Dispatch DAU/seat ratio + QBR attendance | ≥75% DAU ratio, QBR in <60 days | 40-74% DAU, QBR 60-120 days | <40% DAU OR QBR >120 days ago |
| Support Health | 20% | Open critical tickets + ticket trend | 0 critical tickets, stable volume | 1 critical OR 50%+ ticket spike | 2+ critical OR escalation to eng |
| Relationship | 20% | Champion confirmed + CSM sentiment | Champion identified, CSM = confident | Champion unclear, CSM = neutral | Champion departed OR CSM = concerned |

**Composite Score = (Adoption × 0.35) + (Engagement × 0.25) + (Support × 0.20) + (Relationship × 0.20)**

**Current Account Distribution (backfilled):**
- Green (70-100): 91 accounts = 62% of logos / $5.1M ARR
- Yellow (40-69): 38 accounts = 26% of logos / $2.2M ARR
- Red (0-39): 18 accounts = 12% of logos / $0.9M ARR

**Critical Finding: 18 Red accounts represent $900K ARR at elevated churn risk. At 12% historical logo churn, expected revenue loss without intervention = ~$540K ARR. CS team capacity to run full Red Zone playbook: 4 CSMs × 3 active saves each = 12 simultaneous saves. Priority triage: focus saves on 12 highest-ARR Red accounts first (~$680K ARR).**

**Top 3 Churn Prediction Signals (from Veridian's cohort data):**

1. **Routes optimized drops below 15/week for 3 consecutive weeks** → appears 74 days before churn on average; present in 71% of churned accounts, only 11% of healthy accounts → Trigger: Auto-create Gainsight CTA for CSM same day
2. **Dispatch DAU/seat ratio falls below 30% for 14+ days** → appears 52 days before churn; present in 68% of churned accounts → Trigger: Automated email to champion from CSM offering "Adoption Health Check" session
3. **No QBR held in 120+ days AND NPS not collected in 90+ days** → appears 61 days before churn; "dark account" pattern → Trigger: CS Manager escalation + executive outreach attempt

**Tier 1 Alert Template (CSM Slack notification):**
> 🟡 **YELLOW ALERT — Hartfield Transport ($42K ARR)**
> Health Score dropped from 74 → 48 in the last 14 days.
> Key driver: Routes/week fell from 67 → 18 (-73%). DAU ratio now 31%.
> **Action required:** Log Save Play in Gainsight and schedule discovery call within 48 hours.
> Last CSM touchpoint: 34 days ago. Renewal date: 127 days.

**Expansion Signal Identified:**
- 14 accounts show seat utilization >85% + health score >70 + contract age >9 months
- Combined ARR: $1.1M. Average expansion opportunity: $12,400/account
- **Recommended action:** AE + CSM joint expansion play targeting top 5 accounts first (~$320K expansion ARR pipeline)

**30-Day Implementation Plan:**
- [ ] Week 1: Backfill 90-day score for all 147 accounts in Gainsight using dispatch DAU + automation data
- [ ] Week 1: Triage 18 Red accounts; assign each to a CSM; schedule internal war room for top 5 by ARR
- [ ] Week 2: Configure Gainsight CTAs for the 3 alert triggers above; test with 10 accounts before full rollout
- [ ] Week 2: Train 4 CSMs on Yellow/Red playbooks; run tabletop exercise with Hartfield Transport scenario
- [ ] Week 3: Launch weekly health score review in Monday CS standup; add Red ARR to CRO weekly report
- [ ] Week 4: First retrospective — which of 18 Red accounts responded to intervention? Calibrate scoring weights

## Success Metrics

- Red Zone ARR falls below 5% of total ARR within 90 days of implementation
- Save rate (accounts rescued from churn via intervention) exceeds 55% within 6 months
- NRR improves by ≥3 percentage points within 12 months of deploying health scoring
- Champion departure response time reduces to <48 hours from alert detection
- CS team spends ≥40% of capacity on proactive Green/Yellow accounts (vs. reactive Red firefighting) within 60 days
- Expansion pipeline sourced from health score signals represents ≥15% of total upsell pipeline by Month 6

## Related Prompts

- [`../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/Customer-Lifetime-Value-Prediction-&-Acquisition-Investment-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/Customer-Lifetime-Value-Prediction-&-Acquisition-Investment-Intelligence-Engine.md) — Use health score tiers to refine LTV predictions by segment; Red accounts should be excluded from expansion LTV calculations
- [`../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/Cohort-Based-LTV-&-Revenue-Retention-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/Cohort-Based-LTV-&-Revenue-Retention-Intelligence-Engine.md) — Correlate health score cohorts with LTV retention curves to validate scoring model accuracy
- [`../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-Churn-Prediction-&-Proactive-Retention-Marketing-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-Churn-Prediction-&-Proactive-Retention-Marketing-Engine.md) — Feed Red Zone accounts into marketing re-engagement campaigns when CSM outreach fails
- [`../../05_Analytics-&-Performance/Customer-Segmentation-&-Behavioral-Analytics/AI-Powered-Next-Best-Action-Intelligence-&-Revenue-Moment-Personalization-Engine.md`](../../05_Analytics-&-Performance/Customer-Segmentation-&-Behavioral-Analytics/AI-Powered-Next-Best-Action-Intelligence-&-Revenue-Moment-Personalization-Engine.md) — Apply health score tiers as segmentation input for personalized in-app and email next-best-action recommendations

## Integration Tips

- **Gainsight:** Map each of the four health dimensions to a Gainsight Scorecard dimension. Use Gainsight Rules Engine to auto-calculate scores daily from Salesforce and product data sync. Configure Calls-to-Action (CTAs) to fire automatically when composite score crosses Yellow/Red thresholds. Use Cockpit for CSM task management tied to each playbook step.
- **Totango / ChurnZero:** Build a custom SuccessPlay triggered by score drops. Map Green/Yellow/Red health tiers to Totango Segments for bulk CSM actions. ChurnZero's "ChurnScore" can be supplemented with custom signals via their API — push product usage data from Amplitude or Mixpanel directly.
- **Salesforce / HubSpot:** Create a custom `Health_Score` number field and `Health_Tier` picklist (Green/Yellow/Red) on the Account object. Populate via nightly workflow from your CS platform sync. Build a list view for CSMs showing "My Red Accounts" sorted by ARR. Add `Health_Tier` to renewal opportunity records so AEs see risk context.
- **Amplitude / Pendo / Mixpanel:** Build behavioral cohorts for each churn prediction signal (e.g., "users with <15 routes/week for 3 consecutive weeks"). Export as a CSV and schedule a weekly sync to your CRM health score field via Zapier or a native integration.
- **Zapier / Make:** Automate the alert pipeline: when Salesforce Health_Tier changes to "Red" → post to #cs-alerts Slack channel → create CRM task for CSM → add to "Active Saves" Notion database → notify CS Manager if ARR > $50K.
- **LinkedIn Sales Navigator:** Set up alerts on champion contacts. When a champion views a new company page or updates their title → trigger champion departure emergency playbook via a Zapier/HubSpot automation to notify CSM within 24 hours.

## Troubleshooting

**Problem: Health scores look inaccurate — accounts I know are at risk are scoring Green, and healthy accounts are scoring Red.**
Solution: Your scoring weights are miscalibrated for your product. Run a retrospective on 10–15 churned accounts from the past 12 months and 10–15 retained accounts. For each, score them as if the health system existed 90 days before the outcome. Adjust dimension weights until the model correctly classifies ≥70% of churned accounts as Red/Yellow and ≥80% of retained accounts as Green/Yellow. The most common fix: product adoption is underweighted relative to engagement — adoption signals (are they getting value?) usually predict churn better than relationship signals alone.

**Problem: CSMs are ignoring health score alerts because they get too many false positives.**
Solution: Tighten trigger thresholds and add duration requirements. Instead of alerting on any score drop, require the score to be in Yellow/Red for 7+ consecutive days before firing a CSM alert (instant alerts only for Tier 2/3 escalations). Also audit your signal quality — if a signal fires false positives >25% of the time, remove it from the model or lower its weight. Alert fatigue kills adoption; fewer, higher-confidence alerts outperform high-volume noisy ones.

**Problem: No product usage data available — only CRM and support data.**
Solution: Build a relationship-heavy scoring model temporarily using engagement signals you do have: email response rates, meeting attendance, NPS scores, support ticket sentiment, and CSM sentiment. Set a 90-day milestone to instrument your product with at least one usage tracking tool (even simple login frequency via your auth provider). A relationship-only health score is better than no health score — it will catch 40–50% of at-risk accounts vs. 70–80% with full product data. Communicate the model's current limitations to your CS team so they supplement with manual judgment.

## Version History
- v1.0: Initial creation (auto-generated)
