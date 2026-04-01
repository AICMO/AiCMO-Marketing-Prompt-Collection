# AI-Powered RFM Segmentation & Revenue Lifecycle Intelligence Engine - Automated Customer Value Analysis & Targeted Revenue Recovery

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** customer-segmentation, RFM, lifecycle-marketing, revenue-analytics, retention, personalization

## Overview
This engine automates full RFM (Recency, Frequency, Monetary) segmentation analysis, classifies every customer into actionable lifecycle tiers, and generates targeted campaign playbooks for each segment — turning raw transaction data into prioritized revenue recovery and expansion programs that run end-to-end without human editing.

## Quick Copy-Paste Version

You are a senior marketing analytics strategist with deep expertise in customer lifecycle management and RFM modeling.

I will give you a customer dataset (or description of one). Your job is to:

1. Build an RFM scoring model:
   - Recency: Days since last purchase (score 1–5, where 5 = most recent)
   - Frequency: Number of purchases in the last 12 months (score 1–5)
   - Monetary: Total spend in the last 12 months (score 1–5)

2. Classify customers into these 8 RFM segments:
   - Champions (R5, F5, M5): Your best customers
   - Loyal Customers (R4-5, F3-5, M3-5): Buy regularly, respond to offers
   - Potential Loyalists (R3-5, F1-3, M1-3): Recent buyers with growth potential
   - New Customers (R4-5, F1, M1-2): Bought recently, need activation
   - At-Risk Customers (R2-3, F3-5, M3-5): Used to buy often but haven't recently
   - Can't Lose Them (R1-2, F4-5, M4-5): Made big/frequent purchases but gone dormant
   - Hibernating (R1-2, F2-3, M1-3): Below-average recency and frequency
   - Lost (R1, F1-2, M1-2): Lowest scores, haven't engaged in a long time

3. For each segment, output:
   - Segment size (count and % of total base)
   - Revenue contribution (% of total revenue)
   - Psychological profile: What motivates this buyer?
   - Primary risk: What could cause them to churn or stay dormant?
   - Recommended campaign: 1 specific action (subject line + offer + channel)
   - Automation trigger: What event/signal fires this campaign automatically?
   - Success metric: What KPI tells you the campaign worked?

4. Prioritize segments by revenue recovery potential (highest first).

My product/business: [Your Product — e.g., B2B SaaS project management platform]
Customer data summary: [Describe your dataset — e.g., 12,000 customers, 18-month purchase history, average order $850]
Primary goal: [e.g., Increase NRR, reduce churn, reactivate dormant accounts]

Output as a structured table followed by individual campaign playbooks for each segment.

## Advanced Customizable Version

ROLE: You are a senior revenue analytics strategist and CRM intelligence expert specializing in customer lifecycle value optimization. You combine rigorous RFM modeling with behavioral psychology, predictive churn science, and automated campaign design to build systems that run without human intervention.

CONTEXT:
Company: [Company Name]
Industry: [B2B SaaS / D2C ecommerce / B2C subscription / marketplace / other]
Business model: [Subscription / transactional / usage-based / hybrid]
Customer base size: [Total active customers]
Data available: [CRM fields available — e.g., last purchase date, order count, LTV, product tier, contract value, NPS score, feature usage, support tickets]
Primary GTM motion: [Sales-led / product-led / partner-led]
Current retention rate: [% annually]
Primary revenue goal this quarter: [e.g., Reduce churn by 15%, increase expansion revenue by 20%, reactivate 500 dormant accounts]

OBJECTIVE: Build a complete, AI-executable RFM segmentation system with automated campaign playbooks that can be deployed directly into [HubSpot / Salesforce / Klaviyo / Customer.io / Iterable / Braze] without further editing.

STEP 1 — RFM SCORING FRAMEWORK:
Define scoring thresholds based on the data provided:
- Recency scoring: Assign 5 tiers with specific day ranges based on business model (SaaS = contract cycles, ecommerce = purchase windows)
- Frequency scoring: Assign 5 tiers with specific purchase/login/usage count ranges
- Monetary scoring: Assign 5 tiers with specific revenue/ARR/LTV ranges
- For B2B SaaS: Supplement monetary score with product usage depth (DAU, features activated, seats used)
- Output a scoring rubric table with exact numerical thresholds

STEP 2 — SEGMENT CLASSIFICATION ENGINE:
Apply the RFM framework to classify the customer base into the following segments. For each segment, provide:

**SEGMENT PROFILE (for each of 8 segments)**
- RFM Score Range: [exact score combination]
- Typical customer description: [who they are, buying behavior patterns]
- Revenue contribution: [estimated % of total revenue]
- Churn probability: [low/medium/high with estimated % range]
- Psychological driver: [primary motivation — status, efficiency, fear of loss, habit, value-seeking]
- Engagement pattern: [how they interact with your product/brand]

**CAMPAIGN PLAYBOOK (for each segment)**
Using the AIDA framework (Attention → Interest → Desire → Action):
- Campaign name: [descriptive, segment-specific name]
- Channel priority: [primary + secondary channels with reasoning]
- Message angle: [specific psychological trigger to use — e.g., social proof, urgency, exclusivity, education]
- Email subject line: [3 options A/B/C with predicted open rate rationale]
- Email body: [key message structure — 3 sentences max per section: hook, value prop, CTA]
- CTA copy: [exact button/link text]
- Offer/incentive: [specific — % discount, feature unlock, QBR invitation, exclusive content, etc.]
- Automation trigger: [exact event or condition in CRM that fires this sequence]
- Sequence cadence: [timing: Day 0, Day 3, Day 7, Day 14 touch points]
- Suppression rule: [who to exclude from this segment campaign]
- Success KPI: [primary metric + target lift]
- Revenue impact model: [If X% respond → $Y recovered/expanded]

STEP 3 — SEGMENT PRIORITIZATION MATRIX:
Rank all 8 segments by revenue recovery opportunity score, calculated as:
  (Segment Revenue at Risk) × (Reactivation Probability) × (Response to Intervention Rate)
Output as a prioritized list with recommended quarterly focus segments.

STEP 4 — AUTOMATION ARCHITECTURE:
Design the full CRM automation workflow:
- Data sync schedule: [how often RFM scores recalculate — daily/weekly]
- Score degradation logic: [how recency score decays over time automatically]
- Segment migration rules: [what triggers a customer to move between segments]
- Suppression logic: [prevent over-messaging across campaigns]
- Integration map: [CRM → Email platform → Paid retargeting → CS team alert flow]
- Dashboard KPIs: [5 metrics to display on a segment health dashboard]

STEP 5 — EXECUTIVE SUMMARY:
Produce a 5-bullet executive summary suitable for a CMO or VP of Revenue:
- Total addressable revenue at risk in at-risk/dormant segments
- Top 2 segment interventions with highest ROI
- Recommended 30-day action plan
- Resource requirement: [what's needed to execute — headcount, tools, data]
- Expected outcome at 90 days if playbooks are executed

CONSTRAINTS:
- Every campaign must be deployable autonomously — no "review with the team" steps
- Use behavioral triggers, not calendar-based sends, wherever possible
- All copy must be specific to the business context provided, not generic templates
- Revenue estimates must show calculation methodology
- Flag any data gaps that would improve model accuracy

OUTPUT FORMAT: Executive summary → Scoring rubric → Segment profiles table → Individual campaign playbooks (one per segment, structured identically) → Prioritization matrix → Automation architecture diagram (text-based) → Dashboard KPI definitions

## Example Input/Output

**Input Example:**
Company: Lumentrack
Industry: B2B SaaS — field service management platform
Business model: Annual subscription, usage-based add-ons
Customer base: 3,200 active accounts
Data available: Last login date, contract renewal date, seats used vs. licensed, support ticket volume, feature adoption score (0-100), ARR per account
Primary goal: Reduce logo churn from 18% to 12% this year; expand NRR from 108% to 118%
CRM: Salesforce + Customer.io

**Output Example (excerpt):**

**RFM Scoring Rubric — Lumentrack**

| Dimension | Score 5 | Score 4 | Score 3 | Score 2 | Score 1 |
|-----------|---------|---------|---------|---------|---------|
| Recency (days since last login) | 0–7 | 8–21 | 22–45 | 46–90 | 90+ |
| Frequency (logins/mo avg, last 90d) | 15+ | 10–14 | 6–9 | 3–5 | 0–2 |
| Monetary (ARR) | $25K+ | $10–25K | $5–10K | $2–5K | <$2K |

---

**Segment: Can't Lose Them (RFM: R1-2, F4-5, M4-5)**
- Estimated accounts: ~190 (6% of base)
- ARR at risk: ~$3.1M
- Profile: High-value enterprise accounts that previously logged in daily and paid $15K+ ARR, but haven't engaged in 60+ days. Often signals a champion has left the company, a competing solution is being evaluated, or a product issue went unresolved.
- Psychological driver: Fear of disruption + sunk cost — they've invested in configuration, data, and workflows. The cost of switching is real, but the pain of staying dormant is building.

**Campaign: "Executive Re-Engagement Sprint"**
- Channel: CSM direct outreach (Day 0) → Personalized email from VP of CS (Day 3) → LinkedIn InMail from account executive (Day 7) → Executive sponsor letter with custom ROI summary (Day 14)
- Trigger: Feature adoption score drops below 30 AND last login > 45 days AND ARR > $5K
- Day 0 CSM Task (auto-created in Salesforce): "Re-engagement call — reference last successful use case [field: last_workflow_name]"
- Day 3 Email Subject Lines:
  - A: "We noticed Lumentrack has been quiet at [Company Name] — here's what's changed"
  - B: "[First Name], your team was tracking [X] work orders — what happened?"
  - C: "A personalized ROI summary for [Company Name]: what you've built in Lumentrack"
- CTA: "Schedule a 20-minute account review with your CSM"
- Offer: Complimentary implementation health check + free seat expansion for 90 days
- Success KPI: Account re-engagement rate (target: 35% schedule call within 14 days)
- Revenue model: 190 accounts × 35% re-engaged × 80% retention = ~53 accounts saved × $16K avg ARR = **$848K ARR protected**

---

**Segment: Champions (RFM: R5, F5, M5)**
- Estimated accounts: ~240 (7.5% of base)
- ARR contribution: ~$4.8M (38% of total ARR)
- Profile: Power users who log in daily, use advanced features, and represent your highest-ARR accounts. High NPS, frequently submit feature requests, and willing to be references.
- Campaign: "Champions Expansion Circle" — exclusive beta program invite for new AI scheduling module, co-marketing opportunity (case study + G2 review request), referral incentive ($500 charitable donation per qualified intro)
- Trigger: Adoption score ≥ 80 AND ARR ≥ $20K AND last login ≤ 7 days
- Subject: "[First Name], you've unlocked early access to Lumentrack AI Scheduling — here's your invite"
- Revenue model: 240 accounts × 25% expansion rate × $4K avg upsell = **$240K NRR expansion**

## Success Metrics
- **Segment coverage**: All customers successfully scored and classified (target: 100% of database)
- **At-risk revenue identified**: Total ARR mapped to At-Risk + Can't Lose Them segments
- **Campaign open rate**: At-risk segments should achieve ≥35% open rate (vs. ~22% average) due to personalization
- **Re-engagement rate**: At-risk segments should achieve ≥20% meaningful re-engagement within 30 days
- **Revenue protected**: Track ARR from reactivated accounts at 60 and 90 days
- **Segment migration velocity**: % of dormant accounts that moved to an active segment within 90 days
- **NRR impact**: Expansion revenue sourced from Champions and Loyal Customers campaigns

## Related Prompts
- [AI-Powered Customer Segmentation & Behavioral Cohort Intelligence Engine](./AI-Powered-Customer-Segmentation-&-Behavioral-Cohort-Intelligence-Engine.md)
- [CDP Audience Activation & Omnichannel Personalization Intelligence Engine](./CDP-Audience-Activation-&-Omnichannel-Personalization-Intelligence-Engine.md)
- [Customer Lifetime Value Prediction & Acquisition Investment Intelligence Engine](../Customer-Lifetime-Value-Analytics/Customer-Lifetime-Value-Prediction-&-Acquisition-Investment-Intelligence-Engine.md)
- [AI-Powered Customer Health Score & Early Warning Intelligence Engine](../../06_Customer-Success-&-Retention/Customer-Success-Automation/Customer-Health-Score-&-Early-Warning-Intelligence-Engine.md)

## Integration Tips
- **Salesforce**: Create custom RFM score fields on the Account object. Use Flow Builder to recalculate scores weekly based on Last Activity Date, Closed Won count, and ARR. Use Scoring Rules in Marketing Cloud to auto-segment.
- **HubSpot**: Use custom properties for R, F, M scores. Build workflows with enrollment triggers based on score changes. Use Lists to feed each segment into dedicated email sequences.
- **Klaviyo (ecommerce)**: Native RFM segmentation available in Profiles tab. Use Klaviyo Flows to automate sequences per segment. Connect Shopify order data for automatic M score calculation.
- **Customer.io**: Use data pipelines to push RFM scores as person attributes. Build behavioral campaigns triggered by attribute changes. Use Liquid templating to personalize messages with segment-specific copy.
- **Braze**: Use segment extensions for RFM scoring. Schedule Canvas flows per segment. Use Connected Content to pull real-time account data into email copy for personalization.
- **Google Sheets + Zapier**: Export CRM data → Google Sheets → calculate RFM scores with PERCENTRANK formula → Zapier writes scores back to CRM + triggers email platform enrollment.
- **Data Warehouse (Snowflake/BigQuery)**: Run RFM scoring as a scheduled SQL job → push scores to CRM via reverse ETL (Census, Hightouch) → trigger campaigns automatically.

## Troubleshooting

**Problem: RFM scores don't differentiate well — too many customers land in the same middle tiers (score 2-3)**
Solution: Your scoring thresholds may not match your actual distribution. Run a percentile analysis first: assign scores based on the 20th, 40th, 60th, 80th percentile of your actual data rather than fixed ranges. For B2B SaaS with large ARR variance, use log-scaled monetary thresholds.

**Problem: High-value "Can't Lose Them" segment isn't responding to re-engagement campaigns**
Solution: This segment often signals a champion departure, not disengagement. Before launching email campaigns, run a champion tracking check: has the primary contact changed jobs (use LinkedIn or ZoomInfo alerts)? If yes, route to Sales for new stakeholder mapping before any automated outreach fires.

**Problem: RFM model doesn't reflect true customer health for product-led SaaS (no clear "purchases")**
Solution: Replace Frequency (purchase count) with Product Engagement Frequency (weekly active days or feature interactions per week). Replace Monetary (revenue) with Expansion Signal Score (seats used ÷ seats licensed × contract value × usage trend). This creates a PLG-adapted RFM model that captures real behavioral health.

## Version History
- v1.0: Initial creation (auto-generated)
