# AI-Powered B2B SaaS Customer Lifetime Value Prediction & Expansion Revenue Opportunity Scoring Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** clv, customer-lifetime-value, expansion-revenue, revenue-intelligence, predictive-analytics, upsell, cross-sell, customer-success, b2b-saas, revenue-operations

## Overview
This prompt deploys an AI agent to build a full CLV prediction and expansion revenue scoring system for B2B SaaS portfolios — ingesting CRM, product usage, support, and billing data to produce per-account LTV forecasts, expansion propensity scores, and prioritized outreach sequences that marketing and CS can execute immediately without analyst intervention.

## Quick Copy-Paste Version

You are a Senior Revenue Intelligence Analyst with 15+ years in B2B SaaS customer economics. I need you to build a Customer Lifetime Value prediction and expansion revenue scoring system for my SaaS business.

Here is my customer data summary:
- Total customers: [e.g., 1,200 accounts]
- ARR range: [e.g., $5K–$250K per account]
- Average contract length: [e.g., 24 months]
- Product lines: [e.g., Core Platform, Analytics Add-on, API Access, Enterprise Support]
- Key usage signals available: [e.g., DAU/MAU ratio, feature adoption %, support tickets, API calls/month]
- CRM data available: [e.g., HubSpot — account size, industry, contract start date, renewal date, NPS score, QBR attendance]

Produce the following outputs:

1. **CLV Prediction Model Framework**
   - Formula for 12-month, 24-month, and 36-month LTV by customer segment
   - Churn probability weight table based on behavioral signals
   - Revenue expansion multiplier logic (expansion ARR potential per tier)
   - Contraction and churn risk discount factors

2. **Expansion Revenue Opportunity Score (EROS)**
   - 0–100 composite score per account
   - Weighted inputs: product adoption depth (30%), seat utilization (25%), support health (15%), engagement recency (20%), contract headroom (10%)
   - Tier classification: Hot (80–100), Warm (60–79), Nurture (40–59), At-Risk (<40)

3. **Prioritized Account List**
   - Top 20 expansion targets with EROS score, expansion vector (upsell vs. cross-sell vs. seat expansion), estimated expansion ARR, and recommended next action

4. **Marketing Activation Playbook**
   - Personalized campaign sequence for each EROS tier
   - Messaging framework per expansion vector
   - Trigger-based automation logic for HubSpot/Salesforce

5. **Executive Dashboard Template**
   - Weekly CLV movement summary
   - Expansion pipeline forecast
   - Leading indicators to watch

Format all outputs as structured tables and templates ready to import into Google Sheets or CRM. No vague recommendations — every output must be directly actionable by a marketing manager without additional analysis.

## Advanced Customizable Version

ROLE & EXPERTISE
You are a Principal Revenue Intelligence Architect specializing in B2B SaaS customer economics, predictive lifetime value modeling, and expansion revenue orchestration. You combine quantitative modeling rigor (cohort analysis, survival curve analysis, probabilistic forecasting) with practical marketing automation knowledge. Your frameworks have been deployed at Series B through public SaaS companies managing $10M–$500M ARR portfolios.

BUSINESS CONTEXT
Company: [COMPANY_NAME]
ARR: [TOTAL_ARR] across [CUSTOMER_COUNT] accounts
Segments: [e.g., SMB (<$10K ARR), Mid-Market ($10K–$75K ARR), Enterprise (>$75K ARR)]
Churn rate (gross): [e.g., 8% annually]
Net Revenue Retention (NRR): [e.g., 112%]
Average contract length: [e.g., 18 months]
Primary expansion motions: [e.g., seat-based expansion, product add-ons, usage-based overages, tier upgrades]
CRM: [HubSpot / Salesforce / Pipedrive]
Product analytics: [Mixpanel / Amplitude / Heap / custom BI]
CS platform: [Gainsight / ChurnZero / Totango / None]

AVAILABLE DATA SIGNALS
Behavioral signals:
- [e.g., Daily/Weekly/Monthly active users ratio]
- [e.g., Core feature adoption rate (% of available features used)]
- [e.g., Advanced feature adoption (power user behaviors)]
- [e.g., API call volume and growth trend]
- [e.g., Data volume processed/stored]

Relationship signals:
- [e.g., NPS score and trend (last 3 surveys)]
- [e.g., QBR attendance and engagement score]
- [e.g., Executive sponsor engagement (email open rate, meeting attendance)]
- [e.g., Support ticket volume, severity mix, CSAT]
- [e.g., Champion role stability (job changes, LinkedIn signal)]

Commercial signals:
- [e.g., Current ARR vs. contract maximum (headroom)]
- [e.g., Seat utilization rate]
- [e.g., Renewal date proximity (days to renewal)]
- [e.g., Payment history (on-time %, disputes)]
- [e.g., Multi-year vs. annual contract]

OBJECTIVE
Build a complete CLV Prediction & Expansion Revenue Opportunity Scoring (EROS) system that:
1. Forecasts 12/24/36-month LTV per account and per segment
2. Scores every account on expansion propensity (EROS: 0–100)
3. Classifies accounts into actionable expansion tiers
4. Generates marketing activation campaigns per tier and expansion vector
5. Creates a self-updating intelligence loop for CS + Marketing alignment

DELIVERABLE 1: CLV PREDICTION MODEL
Build a three-horizon LTV model using the following structure:

Base LTV Formula:
LTV(t) = ARR × GrossMargin × (1 / ChurnProbability(t)) × ExpansionMultiplier(t)

Where:
- GrossMargin = [e.g., 78%]
- ChurnProbability(t) = derived from behavioral signal decay model (specify weights for each signal)
- ExpansionMultiplier(t) = estimated expansion ARR as % of current ARR over period t

Output:
- Segment-level LTV benchmarks (P25/P50/P75) for 12/24/36 months
- Per-account LTV estimate template (10 fields, importable to CRM)
- Churn probability decay table: map each behavioral signal to churn risk weight
- Expansion multiplier lookup table by segment and expansion vector
- LTV confidence interval methodology (account for data completeness)

DELIVERABLE 2: EXPANSION REVENUE OPPORTUNITY SCORE (EROS)
Design a 0–100 composite scoring model:

Scoring Dimensions (customize weights based on your expansion motion):
1. Product Adoption Depth (suggested: 30 pts)
   - Core feature adoption: 0–10 pts (>80% = 10, 60-80% = 7, 40-60% = 4, <40% = 1)
   - Advanced feature adoption: 0–10 pts
   - Usage growth trend (MoM): 0–10 pts

2. Seat/License Utilization (suggested: 25 pts)
   - Current utilization rate: 0–15 pts (>90% = 15, 75-90% = 10, 50-75% = 5, <50% = 0)
   - Historical utilization growth: 0–10 pts

3. Relationship Health (suggested: 15 pts)
   - NPS score: 0–5 pts (Promoter=5, Passive=3, Detractor=0)
   - QBR engagement: 0–5 pts
   - Executive sponsor stability: 0–5 pts

4. Engagement Recency (suggested: 20 pts)
   - Last meaningful product action: 0–10 pts (within 7 days=10, 14 days=7, 30 days=4, >30 days=0)
   - Marketing engagement (email, content, events): 0–10 pts

5. Commercial Headroom (suggested: 10 pts)
   - Contract headroom (seats/usage vs. ceiling): 0–5 pts
   - Renewal timing (>6 months = opportunity window open): 0–5 pts

Output:
- Scoring rubric table (all dimensions, all values, all point assignments)
- Tier classification rules:
  - HOT (80–100): Immediate expansion outreach, CS-led with marketing support
  - WARM (60–79): Marketing-led nurture into expansion conversation
  - NURTURE (40–59): Engagement re-activation before expansion pitch
  - AT-RISK (<40): Retention priority — hold, then assess expansion potential
- EROS calculation template (Google Sheets formula-ready)
- Score interpretation guide for CS and Marketing teams

DELIVERABLE 3: PRIORITIZED EXPANSION ACCOUNT INTELLIGENCE BRIEF
For the top 30 expansion targets, produce a structured brief per account containing:

Account Intelligence Card (template):
- Account name | Industry | ARR | Segment | Renewal date
- EROS score | Tier | Primary expansion vector | Estimated expansion ARR
- Top 3 behavioral signals driving score
- Champion name | Role | Engagement status
- Recommended next action | Owner (CS or Marketing) | Timing
- Personalized expansion hook (1 sentence, based on their specific usage pattern)

Expansion Vector Classification:
- SEAT EXPANSION: Utilization >85%, growing team signals (LinkedIn headcount growth >10% YoY)
- TIER UPGRADE: Advanced feature trial usage >3 sessions, feature gate hits >5/month
- ADD-ON CROSS-SELL: Core product mature (adoption >75%), adjacent use case unlocked
- USAGE-BASED OVERAGE: API/data consumption approaching tier ceiling (>80% of limit)
- MULTI-YEAR CONVERSION: Annual contract, NPS Promoter, >18 months as customer, stable champion

DELIVERABLE 4: MARKETING ACTIVATION PLAYBOOK BY TIER
Design campaign sequences for each EROS tier and expansion vector:

HOT ACCOUNTS (EROS 80–100) — CS-Led with Marketing Air Cover:
- Week 1: CS sends personalized expansion video (Loom/Vidyard) referencing specific usage milestone
- Week 2: Marketing deploys executive case study (same industry/use case) via 1:1 email from CMO
- Week 3: CS proposes expansion QBR agenda — Marketing sends relevant ROI calculator pre-read
- Week 4: CS closes or escalates; Marketing activates executive sponsor outreach if stalled

WARM ACCOUNTS (EROS 60–79) — Marketing-Led Nurture:
- Email 1 (Day 1): "You're using [Feature X] heavily — here's how [Similar Company] expanded their results"
- Email 2 (Day 8): Product tip demonstrating adjacent capability they haven't unlocked
- Email 3 (Day 15): ROI benchmark report for their segment — invite to peer benchmark webinar
- Email 4 (Day 22): Direct ask — "Would a 30-minute conversation about [Expansion Vector] be valuable?"

NURTURE ACCOUNTS (EROS 40–59) — Re-Engagement Before Pitch:
- Month 1: Deliver quick win (feature tutorial, optimization audit, usage health report)
- Month 2: Invite to user community, product roadmap preview, customer advisory board
- Month 3: Reassess EROS — promote to WARM if score improves, flag for CS health check if stable

AT-RISK ACCOUNTS (EROS <40) — Retention First:
- Immediate CS outreach for health check
- Marketing PAUSES expansion outreach (do not trigger upsell to at-risk accounts — brands as tone-deaf)
- Recovery playbook: executive check-in, product success audit, SLA review
- Reassess in 60 days — if EROS improves to >50, graduate to NURTURE tier

For each email in sequences: provide subject line, preview text, body template (150–200 words), and CTA.

DELIVERABLE 5: SELF-UPDATING INTELLIGENCE LOOP
Design the operational framework for keeping CLV and EROS data current:

Weekly Automation (Zapier/Make/HubSpot Workflow):
- Pull product usage data via API → calculate feature adoption delta → update EROS dimension scores
- Sync NPS survey results → update relationship health score
- Check seat utilization via CRM → flag utilization threshold alerts
- Recalculate EROS for all accounts → promote/demote tiers automatically → notify CS and Marketing Slack channel of tier changes

Monthly Intelligence Review:
- CLV model recalibration (update churn probability weights based on actual churn events)
- Cohort analysis: compare LTV prediction accuracy to actuals
- Expansion hit rate by tier and vector (closed expansion ARR / expansion opportunities by tier)
- Identify new behavioral signals worth adding to EROS model

Executive Dashboard (Weekly):
- Total expansion pipeline (sum of estimated expansion ARR for HOT + WARM accounts)
- Tier distribution shift (MoM change in HOT/WARM/NURTURE/AT-RISK counts)
- EROS score trend by segment
- Top 5 expansion wins this week
- Top 5 accounts that dropped tiers (requires attention)

CONSTRAINTS & QUALITY STANDARDS
- Every formula, weight, and threshold must be immediately implementable — no "tune this for your business" cop-outs without specifying how
- Email templates must be ready to send with [bracket] fills only for account-specific variables
- All scoring logic must be expressible as spreadsheet formulas or CRM workflow logic
- Expansion ARR estimates must use a defined methodology (not "estimated" without basis)
- The system must function with incomplete data — specify default scores when signals are missing
- Flag any assumption that materially affects output accuracy

OUTPUT FORMAT
Deliver all 5 deliverables in sequence, clearly labeled. Use tables for all scoring rubrics, formulas for all calculations, and email templates in blockquote format. End each deliverable with a "Implementation Checklist" (5 items) for immediate action.

## Example Input/Output

**Input (Quick Version):**
Company: DataVault AI (data pipeline automation for mid-market ops teams)
Total customers: 847 accounts
ARR range: $8K–$180K per account
Average contract: 18 months
Product lines: Core Pipeline Builder, AI Anomaly Detection Add-on, Enterprise Compliance Pack, Professional Services
Usage signals: DAU/WAU ratio, pipeline run frequency, error rate trend, data volume processed
CRM: HubSpot with Salesforce integration, Mixpanel for product analytics

**Output (Excerpt):**

**EROS Score — DataVault AI Example Accounts:**

| Account | ARR | DAU/WAU | Feature Adoption | NPS | Seat Util | EROS | Tier | Expansion Vector | Est. Expansion ARR |
|---------|-----|---------|-----------------|-----|-----------|------|------|-----------------|-------------------|
| Meridian Logistics | $42K | 0.71 | 82% | Promoter | 94% | 87 | HOT | Seat expansion + AI add-on | +$18K |
| Cascade Health Systems | $95K | 0.68 | 74% | Passive | 78% | 72 | WARM | Compliance Pack cross-sell | +$24K |
| TerraFin Partners | $28K | 0.44 | 51% | Passive | 61% | 52 | NURTURE | Re-engagement needed | — |
| Bellwood Manufacturing | $61K | 0.21 | 38% | Detractor | 42% | 29 | AT-RISK | Retention priority | — |

**Sample HOT Account Outreach — Meridian Logistics:**

*CS Video Script (Week 1):*
"Hi [Champion Name] — I was looking at your DataVault usage this month and wanted to reach out. Your team processed 2.3M records last week — a 40% jump from your baseline. That kind of growth usually means your team is hitting the ceiling of your current seat allocation. I've put together a 3-slide expansion analysis that shows how Meridian could save approximately 6 hours/week with 4 additional seats and the AI Anomaly Detection add-on. Worth 20 minutes to walk through?"

*CLV Calculation — Meridian Logistics:*
- Current ARR: $42,000
- Gross Margin: 78%
- Churn Probability (12-month): 4% (low — DAU/WAU 0.71, Promoter NPS, 94% seat utilization)
- Expansion Multiplier (12-month): 1.43 (seat expansion + AI add-on = +$18K)
- 12-month LTV: $42,000 × 0.78 × (1/0.04) × 1.43 = **$1,173,780**
- 24-month LTV (assuming successful expansion): **$2,056,680**

## Success Metrics

**Model Accuracy:**
- EROS tier accuracy: ≥70% of HOT accounts close expansion within 90 days of tier assignment
- CLV prediction accuracy: Actual 12-month revenue within ±20% of predicted LTV for ≥65% of accounts

**Revenue Impact:**
- Expansion pipeline generated: HOT + WARM account estimated expansion ARR
- Expansion closed rate by tier: Target HOT >35%, WARM >15%, NURTURE >5%
- NRR improvement: 3–5 point NRR lift within 6 months of systematic EROS deployment

**Operational Efficiency:**
- CS time-to-identify expansion opportunity: <24 hours (vs. manual review baseline of 2 weeks)
- Marketing expansion campaign personalization rate: ≥90% of outreach uses account-specific usage data
- EROS model refresh cadence: Weekly automated refresh with <2 hours manual intervention

**Model Health:**
- Signal coverage: ≥85% of accounts have complete data for all 5 EROS dimensions
- Tier distribution sanity check: HOT should be 10–15% of portfolio, AT-RISK <20%
- Score drift alert: Flag if >25% of accounts change tiers in a single week (indicates data quality issue)

## Related Prompts

- [CAC Payback & Unit Economics Analytics](../CAC-Payback-&-Unit-Economics-Analytics/)
- [Churn Prevention & Retention Analytics](../Churn-Prevention-&-Retention-Analytics/)
- [Customer Lifecycle Marketing Analytics](../Customer-Lifecycle-Marketing-Analytics/)
- [Customer Journey Analytics](../Customer-Journey-Analytics/)

## Integration Tips

**HubSpot:**
- Create custom properties for EROS Score, EROS Tier, Primary Expansion Vector, and Estimated Expansion ARR on the Company object
- Build EROS-based contact lists for each tier (HOT, WARM, NURTURE, AT-RISK)
- Use workflow enrollment triggers on EROS tier changes to auto-enroll accounts in appropriate marketing sequences
- Set up deal stage automation: when EROS crosses 80, auto-create Expansion Opportunity deal in pipeline

**Salesforce:**
- Deploy EROS as a custom Formula Field on the Account object (pulls from custom fields updated via API integration)
- Build Opportunity auto-creation rules: EROS ≥ 80 → create "Expansion" Opportunity at 40% probability
- Use Einstein Analytics or Tableau CRM to build the executive CLV dashboard
- Set up Process Builder/Flow to alert CS rep and Marketing when account EROS changes tier

**Mixpanel/Amplitude:**
- Create behavioral cohorts for each EROS dimension signal (DAU/MAU >0.6, Feature Adoption >75%, etc.)
- Use cohort membership as EROS input via Mixpanel Cohort Sync to HubSpot
- Build retention curves by EROS tier to validate predictive accuracy

**Google Sheets / Looker Studio:**
- EROS calculation template formula: `=MAX(0,MIN(100,(B2*0.3)+(C2*0.25)+(D2*0.15)+(E2*0.20)+(F2*0.10)))` where columns B-F are dimension scores 0–100
- CLV estimation: `=(ARR*GrossMargin*(1/ChurnProb)*ExpansionMultiplier)`
- Connect Looker Studio to BigQuery or Google Sheets for the executive weekly dashboard

**Gainsight / ChurnZero:**
- Map EROS dimensions to existing health score components or create parallel EROS score in CS platform
- Use EROS tier as CTA (Call to Action) trigger: HOT accounts → auto-generate expansion QBR CTA for CS
- Export EROS scores via API to HubSpot/Salesforce for marketing activation

**Zapier / Make:**
- Trigger: Weekly schedule (Monday 6AM) → Pull Mixpanel usage data via API → Calculate EROS delta → Update HubSpot Company properties → Post Slack digest of tier changes to #cs-marketing-alignment channel

## Troubleshooting

**Problem: EROS scores cluster in a narrow range (everyone scores 45–65, no HOT or AT-RISK accounts)**
Fix: Recalibrate dimension breakpoints. If your product has lower DAU/WAU ratios by design (e.g., workflow tools used weekly not daily), adjust the feature adoption dimension to use weekly active users instead of daily. Run the scoring model against your top 10 known churned accounts and top 10 known expansion wins — if scores don't separate these groups clearly, the signal weights need adjustment. Use a regression model (logistic regression in Python/R) on historical churn/expansion data to derive empirical weights instead of using the suggested defaults.

**Problem: Expansion ARR estimates are consistently inaccurate (actuals differ >40% from estimates)**
Fix: Your expansion multiplier table needs calibration to your actual expansion motion. Pull the last 12 months of expansion deals and calculate actual expansion ARR as % of pre-expansion ARR by segment and vector. Replace the theoretical multipliers with empirical medians. Separate seat expansion deals (predictable, usage-driven) from add-on cross-sells (less predictable, relationship-driven) — model them with different confidence intervals.

**Problem: Marketing is triggering expansion campaigns on AT-RISK accounts, damaging relationships**
Fix: Implement a hard gate in HubSpot/Salesforce: any contact or company with EROS < 40 is excluded from all expansion campaign enrollment regardless of list membership. Add a "Retention Hold" flag that CS can set manually to override all marketing automation for sensitive accounts. Build a weekly audit report showing any AT-RISK accounts that received expansion marketing in the prior week so CS can follow up with damage control.

## Version History
- v1.0: Initial creation (auto-generated)
