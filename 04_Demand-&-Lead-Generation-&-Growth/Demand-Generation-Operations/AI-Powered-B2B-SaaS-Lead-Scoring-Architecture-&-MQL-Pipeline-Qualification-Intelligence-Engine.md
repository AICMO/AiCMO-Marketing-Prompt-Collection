# AI-Powered B2B SaaS Lead Scoring Architecture & MQL Pipeline Qualification Intelligence Engine - Build a Predictive Scoring Model That Routes the Right Leads to the Right Motion

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** lead scoring, MQL, marketing ops, RevOps, pipeline qualification, intent data, B2B SaaS, demand gen operations

## Overview
Builds a complete AI-powered lead scoring system for B2B SaaS — combining ICP fit scoring, behavioral engagement scoring, and intent signal weighting into a unified model that auto-qualifies MQLs, routes leads to the right sales motion, and reduces SDR time wasted on low-fit prospects. Use this when your MQL-to-opportunity conversion rate is below 20%, sales is rejecting too many marketing leads, or you're scaling past a point where manual scoring is feasible.

## Quick Copy-Paste Version

You are a B2B SaaS marketing operations architect specializing in revenue operations and lead qualification systems. Design a complete lead scoring model for my company.

COMPANY CONTEXT:
- Company: [e.g., "Krato — B2B SaaS enterprise data governance platform"]
- ICP: [e.g., "VP/Director of Data Engineering, Chief Data Officers at enterprises 1,000+ employees in financial services, healthcare, and tech"]
- ACV: [e.g., "$72,000 with 9-12 month sales cycle"]
- CRM/MAP: [e.g., "HubSpot + Salesforce"]
- Monthly leads volume: [e.g., "1,400 raw leads, targeting 120 MQLs"]
- Current MQL-to-SQL conversion: [e.g., "18% — sales rejects ~40% of MQLs as low fit"]

SCORING DIMENSIONS:
Build a two-axis scoring model (Fit Score + Engagement Score) using the following:

FIT SCORE (firmographic + technographic ICP match, 0-100):
- Company size: [define your ICP tiers — e.g., "1,000-5,000 employees = 25 pts, 5,000+ = 30 pts, <500 = 5 pts"]
- Industry vertical: [e.g., "Financial services = 25 pts, Healthcare = 22 pts, Retail = 10 pts"]
- Tech stack signals: [e.g., "Uses Snowflake or Databricks = +15 pts, AWS/Azure = +10 pts"]
- Job title/seniority: [e.g., "C-suite/VP = 25 pts, Director = 20 pts, Manager = 10 pts, IC = 3 pts"]
- Geography: [e.g., "US/Canada = 10 pts, EMEA = 8 pts, APAC = 5 pts"]

ENGAGEMENT SCORE (behavioral signals, 0-100):
- High-intent actions: [e.g., "Demo request = 40 pts, Pricing page view = 25 pts, ROI calculator = 20 pts"]
- Mid-intent content: [e.g., "Case study download = 12 pts, Webinar attendance = 10 pts, Blog 3+ pages = 8 pts"]
- Low-intent: [e.g., "Newsletter open = 2 pts, Single page visit = 1 pt"]
- Recency decay: [e.g., "Engagement older than 30 days decays 50%, older than 90 days decays 90%"]
- Negative signals: [e.g., "Unsubscribe = -30 pts, Competitor domain = -50 pts, Personal email = -15 pts"]

OUTPUT REQUIRED:
1. SCORING MATRIX: Complete two-axis grid with MQL threshold, SQL threshold, and routing rules
2. SALES MOTION ROUTING: Which score combinations go to AE direct, SDR-qualified, low-touch nurture, or disqualify
3. THRESHOLD CALIBRATION: Recommended MQL threshold and rationale based on target MQL volume
4. SLA FRAMEWORK: Time-to-contact SLAs by lead tier (Tier 1/2/3)
5. MODEL VALIDATION: 3 test scenarios with specific lead profiles and expected scores/routing
6. IMPLEMENTATION CHECKLIST: Step-by-step MAP/CRM configuration tasks with field names
7. DECAY & REFRESH RULES: Automated rules for score recalculation triggers

## Advanced Customizable Version

ROLE: You are a senior Revenue Operations architect with 12+ years designing lead scoring systems for B2B SaaS companies from Series A to post-IPO. You have reduced MQL rejection rates by 40-60% at multiple companies by building fit-first scoring architectures aligned to ICP definitions, sales motion design, and marketing attribution. You think in systems, not point values.

OBJECTIVE: Design a production-ready, AI-augmentable lead scoring architecture that:
- Maximizes MQL-to-SAL conversion rate (target: >30%)
- Reduces SDR time spent on low-fit leads by >50%
- Creates a shared definition of "qualified" between marketing and sales
- Enables dynamic, intent-signal-responsive scoring that updates in real time
- Produces a scoring model that a marketing ops admin can implement in [CRM/MAP] within 2 weeks

COMPANY PROFILE:
- Company name & product: [name + 1-sentence description]
- Business model: [SaaS/usage-based/hybrid + pricing tiers]
- Stage: [Series A/B/C/growth/public]
- ARR target: [e.g., "$8M new logo ARR this year"]
- Sales team structure: [e.g., "6 AEs (enterprise $100K+ ACV), 4 SMB AEs ($25-75K), 8 SDRs, 2 sales engineers"]
- Sales motions: [e.g., "Enterprise: AE-led, 12-month cycle; Mid-market: SDR-to-AE, 60-day cycle; SMB: self-serve trial-to-paid"]

ICP DEFINITION (complete all tiers):
Tier 1 (highest priority):
- Company size: [headcount range]
- Industry verticals: [list top 3]
- Revenue range: [if known]
- Tech stack: [key technologies in their stack that signal fit]
- Job titles: [primary economic buyer + champion + technical evaluator]
- Trigger events: [e.g., "recent funding, compliance change, M&A activity, new executive hire"]

Tier 2 (good fit):
[same structure as Tier 1 but with slightly broader criteria]

Tier 3 (low priority / nurture only):
[criteria that disqualify from immediate sales engagement]

CURRENT FUNNEL STATE:
- Monthly raw lead volume: [#]
- Current MQL definition: [e.g., "Any form fill with company email" OR describe existing scoring model]
- Current MQL-to-SQL rate: [%]
- SQL-to-opportunity rate: [%]
- Target MQL volume/month: [#]
- Sales complaints about lead quality: [describe specific patterns — e.g., "wrong company size," "wrong persona," "bad timing"]

INTENT DATA SOURCES AVAILABLE:
- First-party behavioral: [e.g., "HubSpot tracking, in-app product signals, webinar attendance, content downloads"]
- Third-party intent: [e.g., "Bombora, G2 Buyer Intent, 6sense" OR "none"]
- Technographic: [e.g., "Clearbit Reveal, BuiltWith enrichment" OR "none"]
- CRM enrichment: [e.g., "Clearbit, ZoomInfo, Clay" OR "none"]

TECH STACK:
- CRM: [Salesforce/HubSpot/other]
- Marketing Automation: [Marketo/HubSpot/Pardot/other]
- Intent data: [tools if any]
- Enrichment: [tools if any]
- Conversational/chat: [Drift/Intercom/other OR none]
- Analytics: [Amplitude/Mixpanel/GA4/other]

CONSTRAINTS & REQUIREMENTS:
- Marketing-sales SLA: [e.g., "Tier 1 leads: SDR contact within 5 minutes; Tier 2: within 4 hours"]
- Compliance requirements: [e.g., "GDPR — no behavioral tracking without consent in EU"]
- Admin capacity: [e.g., "1 part-time marketing ops person, implementation must take <40 hours"]
- Board/CEO pressure: [e.g., "Sales/marketing alignment is a top priority for Q3"]

DELIVERABLES:

PART 1 — FIT SCORING MODEL
Build a 100-point ICP Fit Score with:
- Point values for every firmographic dimension (company size, industry, geography, revenue)
- Point values for technographic signals (tech stack, tools, integrations used)
- Point values for persona signals (job title hierarchy, department, buying authority)
- Negative scoring rules (disqualifying signals that cap fit score regardless of engagement)
- Tier assignment logic: Tier 1 (80-100), Tier 2 (50-79), Tier 3 (<50)
- How to populate each dimension (manual, enrichment, self-reported, inferred)

PART 2 — ENGAGEMENT SCORING MODEL
Build a 100-point Engagement Score with:
- High-intent actions with point values (demo request, pricing, ROI calculator, trial signup, product pages)
- Medium-intent actions (case studies, webinars, comparison pages, email clicks)
- Low-intent actions (blog views, email opens, social)
- Recency decay schedule (30/60/90 day decay percentages)
- Velocity scoring bonus (e.g., "3+ high-intent actions in 7 days = +15 velocity bonus")
- Negative/decay signals (unsubscribes, inactivity, competitor email domain)

PART 3 — COMPOSITE SCORING & ROUTING MATRIX
2x2 matrix with four quadrants:
- High Fit + High Engagement → Route to: [specific motion + SLA]
- High Fit + Low Engagement → Route to: [specific motion + SLA]
- Low Fit + High Engagement → Route to: [specific motion + SLA]  
- Low Fit + Low Engagement → Route to: [specific motion + SLA]

For each quadrant, define:
- Exact composite score thresholds
- Sales motion (AE direct, SDR outbound, inbound sequence, nurture, disqualify)
- Time-to-contact SLA
- Max leads per SDR per day for this tier

PART 4 — MQL DEFINITION & THRESHOLD CALIBRATION
- Recommended MQL composite threshold (with rationale tied to target volume)
- SQL threshold requiring different scoring combination
- PQL (product-qualified lead) definition if product usage data is available
- How to A/B test threshold changes without breaking pipeline reporting
- How to communicate the new MQL definition to sales with a joint agreement template

PART 5 — DYNAMIC SCORING TRIGGERS
Automated workflows that update score in real time:
- Intent surge trigger (e.g., "Bombora surge on relevant topic = +20 instant boost")
- Product usage PQL trigger (if applicable)
- Buying committee expansion trigger (e.g., "Second contact from same account in 14 days = boost account score")
- Competitive comparison trigger (e.g., "Viewed G2 comparison page = high-intent flag")
- Re-engagement trigger (e.g., "Inactive lead visits pricing page = restart engagement score")
- Account-level scoring rollup (individual scores → account-level MQA)

PART 6 — IMPLEMENTATION PLAN
Week-by-week implementation checklist:
- Week 1: Data audit and field mapping (specific CRM fields to create/update)
- Week 2: Scoring rule configuration (specific workflow/automation steps)
- Week 3: Routing rules and SLA setup
- Week 4: Validation testing and sales training

PART 7 — MODEL GOVERNANCE & CALIBRATION CADENCE
- Monthly model review metrics (MQL volume, MQL-to-SQL rate, SAL rejection reasons)
- Quarterly model recalibration process (how to adjust weights based on closed-won patterns)
- How to use won/lost deal data to backtest and improve scoring
- Who owns the model (roles: model owner, sales liaison, RevOps admin)

## Example Input/Output

**Input Example:**

Company: Meridian — B2B SaaS platform for enterprise vendor risk management
ICP: Chief Risk Officers, VP Risk & Compliance at banks, insurance companies, and PE firms (2,500-50,000 employees)
ACV: $95,000 | Sales cycle: 10-14 months
CRM/MAP: Salesforce + Marketo
Monthly leads: 1,800 raw leads | Target: 90 MQLs/month
Current MQL-to-SQL: 14% (sales rejects ~55% citing "wrong size or wrong title")
Intent data: Bombora + G2 Buyer Intent
Enrichment: Clearbit + ZoomInfo

---

**Output Example (Abbreviated):**

**ICP FIT SCORE (0-100 points)**

| Dimension | Signal | Points |
|-----------|--------|--------|
| Company size | 10,000+ employees | 30 |
| Company size | 2,500-9,999 employees | 22 |
| Company size | 500-2,499 employees | 10 |
| Company size | <500 employees | 0 |
| Industry | Banking/Financial Services | 25 |
| Industry | Insurance | 22 |
| Industry | PE/Asset Management | 20 |
| Industry | Healthcare/Pharma | 12 |
| Industry | Other regulated | 5 |
| Tech stack | Uses ServiceNow or Archer | +15 |
| Tech stack | Uses Salesforce or SAP | +8 |
| Job title | CRO / Chief Risk Officer | 20 |
| Job title | VP Risk / VP Compliance | 17 |
| Job title | Director Risk | 12 |
| Job title | Risk Manager | 6 |
| Geography | US, UK, Canada, Australia | 10 |
| Geography | EU (GDPR compliant) | 8 |
| **NEGATIVE SIGNALS** | Competitor domain email | Cap score at 20 |
| **NEGATIVE SIGNALS** | Company <100 employees | Cap score at 15 |

**Fit Score Tiers:** Tier 1 = 80-100 | Tier 2 = 55-79 | Tier 3 = <55

---

**ENGAGEMENT SCORE (0-100 points, with 30-day recency decay)**

High-intent (30+ days decays 50%):
- Demo request submitted: 45 pts
- Pricing page: 2+ visits in 14 days: 30 pts
- ROI calculator completed: 25 pts
- "Request a report" CTA: 20 pts
- Viewed 3+ case studies in 30 days: 15 pts
- Velocity bonus (4+ high-intent actions in 7 days): +15 pts

Medium-intent (30-day decay 40%):
- Webinar attended (live): 12 pts
- Case study download: 8 pts
- Email click (non-pricing): 4 pts
- Blog: 3+ articles in session: 5 pts

Negative signals:
- Email unsubscribe: -35 pts
- No activity >90 days: reset to 0 and move to re-engagement nurture
- Personal email domain (gmail/yahoo): -20 pts fit score

---

**ROUTING MATRIX:**

| Fit Score | Engagement Score | Composite | Route To | SLA |
|-----------|-----------------|-----------|----------|-----|
| Tier 1 (80+) | High (60+) | Priority MQL | AE direct assign | 5-minute email + call attempt |
| Tier 1 (80+) | Medium (30-59) | MQL | SDR outbound sequence | 4-hour response |
| Tier 2 (55-79) | High (60+) | MQL | SDR outbound sequence | Same-day |
| Tier 2 (55-79) | Low (<30) | Nurture | Automated 8-touch nurture | No SDR until score increases |
| Tier 3 (<55) | Any | Disqualify | Archive or self-serve | No SDR contact |

**MQL Threshold Recommendation:** Composite ≥ 110 (Fit + Engagement combined) AND minimum Fit Score of 55
→ At current lead volume, this produces ~88 MQLs/month (vs. target of 90) with projected MQL-to-SQL of 34%

---

**IMPLEMENTATION WEEK 1 CHECKLIST (Salesforce + Marketo):**
- [ ] Create custom field: `ICP_Fit_Score` (number, 0-100) on Lead and Contact objects
- [ ] Create custom field: `Engagement_Score` (number, 0-100) on Lead and Contact object
- [ ] Create custom field: `Lead_Tier` (picklist: T1/T2/T3/Disqualified) on Lead
- [ ] Create custom field: `MQL_Date` (datetime) for SLA tracking
- [ ] Map Clearbit enrichment to company size, industry, tech stack fields
- [ ] Build Marketo Smart Campaign: "Fit Score Calculation" — triggered on lead creation and enrichment update
- [ ] Build Marketo Smart Campaign: "Engagement Score Increment" — triggered on each behavioral event
- [ ] Configure 30/60/90-day decay scheduled batch jobs in Marketo

## Success Metrics

- **MQL-to-SAL conversion rate:** Target ≥30% (improvement from baseline) within 60 days of launch
- **SAL rejection rate:** Sales rejects fewer than 20% of MQLs for "wrong fit" reasons
- **SDR connect rate:** Tier 1 MQLs achieve ≥15% connect-to-conversation rate
- **Time-to-contact:** ≥90% of Tier 1 MQLs contacted within SLA
- **Pipeline quality:** Opportunities sourced from MQL score ≥110 have 2x higher win rate than historical average
- **Model stability:** Scoring model calibration required fewer than 3 major adjustments in first 6 months
- **Monthly MQL volume accuracy:** Actual MQL output within ±15% of target volume

## Related Prompts

- [Demand Generation Waterfall Architecture & Funnel Conversion Engine](./AI-Powered-B2B-SaaS-Demand-Generation-Waterfall-Architecture-&-Marketing-Funnel-Conversion-Intelligence-Engine.md)
- [ABM Intent Data Activation & Buying Signal Prioritization Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [CRM Revenue Operations Intelligence Engine](../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/CRM-Revenue-Operations-Intelligence-Engine.md)
- [Account-Based Marketing Analytics & Revenue Intelligence Engine](../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Account-Based-Marketing-Analytics-&-Revenue-Intelligence-Engine.md)

## Integration Tips

- **HubSpot:** Use HubSpot's native Lead Scoring tool for fit/engagement dimensions; create calculated properties for composite score; use Workflows to trigger routing based on score thresholds and assign to owners
- **Marketo + Salesforce:** Build scoring in Marketo using Smart Campaigns for behavioral triggers and scheduled batch jobs for decay; sync composite score to Salesforce Lead object field; use Salesforce Assignment Rules to route by Lead_Tier field
- **6sense / Bombora:** Map intent surge signals to engagement score via API webhook or native integration; create Marketo Trigger "Intent Surge Detected" → add +20 engagement points + flag for SDR review
- **Clay:** Use Clay to enrich leads with firmographic and technographic signals in real time; map enriched fields back to Salesforce/HubSpot to auto-populate fit score dimensions without manual data entry
- **Salesloft / Outreach:** Configure cadence assignment by Lead_Tier field sync from CRM; Tier 1 → Priority cadence (high-touch, 10 steps, 14 days); Tier 2 → Standard cadence (8 steps, 21 days); Tier 3 → Automated nurture only
- **Zapier / Make:** For lighter stacks, use Zapier to connect form submissions → enrichment API → scoring calculation → CRM update → Slack notification to SDR for Tier 1 leads, all within 60 seconds of form fill
- **Google Sheets (calibration):** Maintain a monthly scoring calibration spreadsheet pulling won/lost deal data from CRM; use VLOOKUP to backtest: "what was the fit score and engagement score of every deal that closed in the last 90 days?" to validate and adjust thresholds

## Troubleshooting

**Problem: Score inflation — too many leads hitting MQL threshold, overwhelming SDRs**
Solution: Tighten the fit score minimum (raise from 55 to 65) before adjusting engagement weights. Score inflation is almost always a fit problem, not an engagement problem — low-fit leads with high web engagement (competitors, students, job seekers) are gaming the engagement side. Add domain-level negative scoring rules first, then recalibrate thresholds.

**Problem: Sales still rejecting MQLs despite new model — claiming leads are "not ready to buy"**
Solution: This is a timing/engagement threshold problem, not a fit problem. If sales is accepting the persona but rejecting the timing, raise the minimum engagement score for MQL (e.g., from 30 to 45) and add a "high-intent action required" rule — no lead can be an MQL without at least one action scoring 20+ points. Also schedule a monthly "MQL rejection review" with sales to categorize rejection reasons (wrong fit vs. wrong timing vs. wrong persona) and use this data to refine.

**Problem: Model working in staging/MAP but composite score not populating in CRM for routing**
Solution: Check field sync direction and object mapping — composite score must exist as a writable field on both Lead AND Contact in Salesforce (not just one), because leads convert to contacts at opportunity creation. Also verify Marketo sync filter isn't excluding records with null field values before score calculation completes. Add a "score calculated" boolean checkbox to confirm the scoring workflow ran successfully before routing rules evaluate.

## Version History
- v1.0: Initial creation (auto-generated)
