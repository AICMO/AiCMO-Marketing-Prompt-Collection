# AI-Powered B2B SaaS Lead Scoring Model & Predictive MQL-to-Pipeline Conversion Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** b2b, saas, lead-scoring, demand-gen, automation, analytics, conversion, crm

## Overview
Builds a fully automated, AI-driven lead scoring system that combines firmographic fit, behavioral engagement signals, and intent data to predict which leads will convert to pipeline — then outputs a dynamic scoring rubric, threshold recommendations, and sales routing logic ready to deploy in your MAP/CRM stack.

## Quick Copy-Paste Version

You are a senior B2B demand generation strategist specializing in predictive lead scoring. I need you to build a complete lead scoring model for my business.

Company context:
- Product: [SaaS product category, e.g., "revenue intelligence platform for B2B sales teams"]
- ACV: [e.g., "$45K"]
- Sales cycle: [e.g., "45–90 days"]
- ICP: [e.g., "VP/Director of Sales at 100–1000 employee B2B SaaS companies in North America"]
- Current MQL-to-SQL conversion rate: [e.g., "22%"]
- Top 3 closed-won customer profiles: [describe briefly or say "unknown"]

Build me:
1. A demographic/firmographic scoring rubric (0–100 points) with specific point values for job title, company size, industry, funding stage, and tech stack signals
2. A behavioral engagement scoring rubric with point values for website pages visited, content downloads, email opens/clicks, webinar attendance, free trial activity, pricing page visits, and repeat visits
3. An intent signal scoring layer (G2 reviews, Bombora/6sense categories, LinkedIn ad engagement)
4. MQL threshold recommendation: the minimum score to pass a lead to sales, with rationale
5. Sales routing logic: score ranges mapped to SDR vs. AE vs. automated nurture
6. A lead decay model: how much to subtract per week of inactivity and why
7. A scoring audit checklist: monthly actions to recalibrate the model

Output everything as structured tables and numbered rules that can be directly entered into HubSpot, Salesforce, or Marketo. No vague recommendations — every data point should have a specific point value.

## Advanced Customizable Version

ROLE: You are a revenue operations architect with 15 years building predictive lead scoring models for B2B SaaS companies from Series A through public company. You have deployed scoring systems in HubSpot, Salesforce Pardot, Marketo, and 6sense that improved MQL-to-SQL conversion by 30–60%. You think in data models, not marketing platitudes.

OBJECTIVE: Design a production-ready, AI-augmented lead scoring model for [COMPANY NAME] that maximizes the predictive accuracy of MQL designation and minimizes wasted sales capacity on low-fit leads.

COMPANY CONTEXT:
- Product/Category: [e.g., "workforce analytics platform helping HR leaders reduce attrition"]
- Target ACV: [e.g., "$72K"]
- Average sales cycle: [e.g., "60 days"]
- Primary ICP: [e.g., "CHRO/VP People at 500–5,000 employee companies in financial services, healthcare, and tech"]
- Secondary ICP: [e.g., "Director HR Operations at same firmographics"]
- Anti-ICP (disqualifiers): [e.g., "SMB < 100 employees, government, non-profit"]
- Current funnel: [e.g., "8,000 MQLs/year, 18% MQL-to-SQL, 28% SQL-to-close, $3.2M pipeline from MQLs"]
- Top 5 closed-won signals (if known): [e.g., "visited pricing page 2+ times, attended live demo, downloaded ROI calculator"]
- Primary MAP/CRM: [e.g., "HubSpot Enterprise + Salesforce"]
- Intent data available: [e.g., "Bombora, G2 Buyer Intent"]

SCORING ARCHITECTURE:

**SECTION 1 — DEMOGRAPHIC/FIRMOGRAPHIC FIT SCORE (Max 40 points)**

Build a detailed rubric with exact point values for:
- Job title/seniority alignment to ICP (break into: exact match, one-level off, irrelevant)
- Company employee count (tier into 5 ranges against ICP)
- Industry vertical alignment (tier into: perfect fit, adjacent, poor fit)
- Company revenue or funding stage proxy
- Geography (if geo-specific)
- Known tech stack signals (e.g., Salesforce user = +8 pts if it indicates enterprise)
- Buying trigger firmographics (recent funding, headcount growth, leadership change)

**SECTION 2 — BEHAVIORAL ENGAGEMENT SCORE (Max 40 points)**

Build a behavioral scoring rubric with exact point values for:
- High-intent pages: pricing, ROI calculator, competitor comparison, demo request
- Mid-intent pages: case studies, product feature pages, integration pages
- Low-intent pages: blog, homepage, about us
- Content downloads by type (ROI calculator > white paper > blog ebook)
- Email engagement (click through > open > soft bounce handling)
- Webinar/event attendance (live > replay > registered no-show)
- Free trial or freemium product activity signals
- Repeat visits within 7 days (strong buying signal)
- LinkedIn ad engagement (if trackable via matched audiences)

**SECTION 3 — INTENT DATA SCORE (Max 20 points)**

If intent data is available:
- 3rd-party intent spike for relevant topics (Bombora)
- G2 profile views / comparison behavior
- Competitor research activity
- Review site activity

**SECTION 4 — NEGATIVE SCORING / DISQUALIFIERS**

Explicit point deductions for:
- Student/personal email domains
- Competitor employee indicators
- Anti-ICP job titles (intern, coordinator, student)
- Anti-ICP company types
- Unsubscribed from all communications
- No activity for 30/60/90 days (decay model)

**SECTION 5 — THRESHOLDS AND ROUTING LOGIC**

Based on the scoring rubric above, define:
- MQL threshold (minimum score to route to sales) with statistical rationale
- Score bands:
  - 80–100: Route immediately to AE (high-fit, high-intent)
  - 60–79: Route to SDR for qualification call within 24 hours
  - 40–59: Enter high-velocity nurture sequence, re-evaluate in 14 days
  - Below 40: Standard long-cycle nurture, no sales touch
- SLA commitments per band (SDR response time, follow-up cadence)

**SECTION 6 — LEAD DECAY MODEL**

Define:
- Weekly decay rate for inactive leads (recommended: -2 to -5 points/week after 14 days of no activity)
- Re-engagement triggers that restore or boost score
- Recycle logic: when to return an SQL to MQL status

**SECTION 7 — MODEL GOVERNANCE**

Provide:
- Monthly scoring audit checklist (5–7 specific actions)
- Quarterly model recalibration criteria (when to add/remove scoring signals)
- Win/loss feedback loop: how closed-won data should inform score weight adjustments
- Stakeholder alignment template: how to present model changes to sales leadership

**OUTPUT FORMAT REQUIREMENTS:**
- Present all scoring as structured tables with exact point values
- Include a summary scoring card (single-page visual description)
- Flag any assumptions you're making about the ICP or buyer behavior
- For each score threshold, provide the business rationale
- Deliver all output in a format directly importable to HubSpot Property Scoring or Salesforce Lead Score fields

CONSTRAINTS:
- No vague ranges like "5–15 points" — commit to specific values
- Do not recommend "consult your data team" without first providing a working hypothesis the team can validate
- Model must be operable on day 1 with available data, not dependent on 6 months of historical analysis
- All behavioral triggers must be achievable with standard MAP tracking (UTM, cookie, form fill, email click)

## Example Input/Output

**Input Example:**

Company: Claros AI — AI-powered contract intelligence for procurement teams
ACV: $58K | Sales cycle: 55 days
ICP: VP/Director Procurement, CPO, or Head of Legal Operations at 200–2,000 employee B2B companies
Top closed-won signals: Pricing page visit + ROI calculator download, visited 3+ times in 14 days, Director+ title
Current MQL-to-SQL: 19% | Goal: 35%

**Output Example (excerpt):**

**FIRMOGRAPHIC FIT SCORE (Max 40 pts)**

| Signal | Exact Match | Partial Match | No Match |
|---|---|---|---|
| Job Title: VP/Dir Procurement, CPO, Head Legal Ops | +20 | +10 (Manager level) | 0 |
| Job Title: CFO, COO, VP Finance (economic buyer) | +15 | +7 | 0 |
| Company Size: 200–2,000 employees | +10 | +5 (2,001–5,000) | -5 (<50 or >10,000) |
| Industry: SaaS, FinServ, Pharma, Manufacturing | +8 | +4 (adjacent: logistics) | -3 (government, nonprofit) |
| Tech Stack: Salesforce, SAP Ariba, Coupa detected | +5 | — | 0 |
| Funding signal: Series B+ or profitable SMB | +3 | — | 0 |

**BEHAVIORAL SCORE (Max 40 pts)**

| Behavior | Points | Notes |
|---|---|---|
| ROI Calculator download | +15 | Single strongest predictor |
| Pricing page visit | +12 | Deduped: only counts once per 7 days |
| Demo request form start (abandoned) | +10 | Captured via partial form fill |
| Case study download (2+ downloads) | +8 | Single download: +4 |
| Feature pages (3+ unique) | +6 | |
| Webinar attendance (live) | +8 | Replay: +4 |
| Email click-through (non-unsubscribe) | +3 per email | Cap at +9 |
| Repeat site visit within 7 days | +5 | Strong recency signal |
| Blog only, no conversion page | +1 | Low intent |

**THRESHOLDS:**
- MQL: 55+ total points (up from previous 40 — eliminates ~38% of low-quality MQLs)
- Hot MQL (immediate AE routing): 80+ points with Director+ title
- Estimated impact: MQL-to-SQL improves from 19% → 34% based on fit/intent signal correlation

**DECAY MODEL:**
- Leads with 0 activity for 14 days: -3 points/week
- Re-engagement trigger: any high-intent page visit instantly adds +8 and pauses decay
- Recycle threshold: SQLs that go dark for 45 days with no opportunity created return to nurture at their current score minus 20

## Success Metrics

- **MQL-to-SQL conversion rate improvement**: Target 25–40% lift within 90 days of model deployment
- **SQL-to-close rate (from model-scored MQLs)**: Should exceed historical baseline by ≥10%
- **Sales acceptance rate**: SDR accepts ≥75% of MQLs passed (measures model credibility with sales)
- **Lead decay accuracy**: Reactivated leads (previously decayed) convert at ≥15% MQL-to-SQL
- **Model precision**: At least 65% of leads scoring 80+ should convert to pipeline within 60 days
- **Scoring coverage**: ≥90% of new leads receive a score within 24 hours of first touchpoint

## Related Prompts

- [ABM Intent Data Activation & Buying Signal Prioritization](../Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [AI-Powered In-Market Buyer Capture & Late-Stage Demand Interception](AI-Powered-In-Market-Buyer-Capture-&-Late-Stage-Demand-Interception-Engine.md)
- [ICP Discovery Engine](../../02_Product-Marketing/Customer-&-Market-Research/ICP-Discovery-Engine.md)
- [Predictive Revenue Forecasting Engine](../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Predictive-Revenue-Forecasting-Engine.md)

## Integration Tips

**HubSpot:**
- Use HubSpot's native Lead Scoring (Professional+) or Contact Scoring (Enterprise) — map each rubric item directly to a scoring attribute rule
- Set lifecycle stage automation: score ≥55 triggers `Lifecycle Stage = MQL` and enrolls in a task sequence for SDR
- Use Workflows to fire the decay model: "If last activity date > 14 days, subtract 3 from contact score weekly"
- Connect to Slack via HubSpot workflow notifications: instant Slack alert to SDR when score hits 80+

**Salesforce + Pardot/Marketing Cloud:**
- Use Pardot's Scoring Categories to separate fit score and engagement score, then combine via Salesforce formula field
- Build a `Composite Lead Score` formula field: `Fit_Score__c + Engagement_Score__c + Intent_Score__c`
- Create Lead Assignment Rules based on composite score bands (80+ → AE queue, 55–79 → SDR round-robin)
- Use Einstein Lead Scoring (Sales Cloud) alongside your custom model as a validation layer

**Marketo:**
- Use Marketo's native scoring programs for behavioral points; build a separate "demographic scoring" smart campaign
- Trigger `Sales Alert` email to SDR when score threshold crossed
- Use Program Status changes to track MQL designation date for SLA reporting

**6sense / Bombora integration:**
- Map 6sense account scores to firmographic tier (A/B/C account = point modifier on all leads from that account)
- Bombora surge score ≥60 on target topic = add +15 to all contacts at that account instantly

**Google Sheets / Airtable (early-stage teams):**
- Export lead data weekly; use VLOOKUP/scoring formulas to replicate the rubric manually
- Build a scoring calculator tab: input 10 data fields, auto-calculates composite score and recommended action

## Troubleshooting

**Problem: Sales rejects most MQLs despite high scores**
Solution: Run a 30-day win/loss audit — compare the firmographic and behavioral profiles of accepted vs. rejected MQLs. Likely the fit score weights need rebalancing (e.g., job title is overweighted vs. company size). Add a "Sales Feedback" picklist to SQL records so reps tag rejection reasons; use that data to adjust score weights.

**Problem: Lead scores plateau — most leads stuck in 30–50 range, never crossing MQL threshold**
Solution: Your behavioral scoring may be under-weighting high-intent actions. Check if pricing page, ROI calculator, and demo-request-start are properly tracked (UTM firing, HubSpot/Marketo page tracking installed). Also check if your decay model is too aggressive — a -5/week decay can cancel out genuine engagement signals. Temporarily reduce decay to -2/week and monitor for 30 days.

**Problem: MQL volume drops 60%+ after deploying new threshold**
Solution: This is often correct behavior — you've filtered out low-quality leads. Validate by checking SQL-to-close rate on the remaining MQLs (should increase). If pipeline suffers, temporarily lower the MQL threshold by 5 points and simultaneously increase SDR outbound capacity to compensate for lower inbound MQL volume. Do not lower the threshold back to the old level without data justification.

## Version History
- v1.0: Initial creation (auto-generated)
