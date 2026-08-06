# AI-Powered B2B SaaS Account-Level Lead Scoring Intelligence & Buying Group Completion Revenue Analytics Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** b2b, mqa, mql, account-scoring, buying-group, lead-quality, pipeline-analytics, abm, revenue-attribution, saas-metrics

## Overview
This prompt builds a full account-level lead scoring and buying group completion analytics system that moves beyond individual MQL tracking to score accounts based on multi-stakeholder engagement depth, persona coverage, and buying signal density. Use it to replace legacy MQL scoring models with MQA (Marketing Qualified Account) intelligence, surface which accounts have complete buying committees engaged, and prove marketing's contribution to high-quality pipeline at the account level.

## Quick Copy-Paste Version

You are a senior B2B SaaS revenue analytics expert specializing in account-level lead scoring, buying group intelligence, and MQA pipeline analytics. Build a comprehensive account-level scoring and buying group completion analytics system that helps us move from individual MQL tracking to account-level pipeline qualification.

Here is our current state:

COMPANY PROFILE:
- Average ACV: $[amount]
- Sales cycle length: [months]
- Primary ICP: [describe — industry, company size, revenue range]
- GTM motion: [Enterprise sales-led / Mid-market hybrid / PLG + sales]

BUYING COMMITTEE DEFINITION:
- Economic buyer: [title, e.g., CFO, VP Finance]
- Technical evaluator: [title, e.g., VP Engineering, Head of Security]
- Business champion: [title, e.g., VP Marketing, Director of Operations]
- End user influencer: [title, e.g., Marketing Manager, Analyst]
- Procurement/legal: [title, when applicable]

CURRENT DATA AVAILABLE:
- CRM contacts per target account: [average number]
- Marketing-engaged contacts per account (last 90 days): [average number]
- Engagement channels tracked: [email opens, content downloads, webinar attendance, ad clicks, website visits, intent data]
- Intent data provider: [Bombora / G2 / 6sense / Demandbase / none]

CURRENT SCORING MODEL:
- Today we score: [individuals / accounts / both]
- MQL threshold: [score or activity criteria]
- Primary scoring signals used: [list current signals]

Please provide:
1. An MQA scoring framework — define what score thresholds constitute a Marketing Qualified Account, Marketing Engaged Account, and Marketing Aware Account based on buying group completeness and aggregate engagement
2. A buying group completion scorecard — for each buying committee persona, define what engagement signals constitute "covered" (minimally touched), "engaged" (actively engaging), and "activated" (high-intent behavior demonstrated)
3. Account engagement density formula — a weighted score that combines persona coverage percentage, aggregate engagement volume, engagement recency decay, and intent signal strength into a single account score
4. MQA-to-pipeline conversion benchmarks — expected conversion rates from MQA to SQL, SQL to opportunity, and opportunity to close for accounts with complete vs. incomplete buying groups
5. A "buying group gap analysis" report template — for each account in pipeline, surface which personas are missing, which are cold, and what marketing plays should be triggered to fill the gaps
6. Marketing-to-sales handoff intelligence brief — the data package marketing should deliver to sales for each MQA, including engagement timeline, content consumed per persona, and recommended conversation openers
7. Board-ready MQA metrics dashboard — the 5 KPIs that replace legacy MQL metrics in a modern account-based measurement framework

Format as an analytics blueprint with a scoring matrix, formula definitions, and example account scorecard.

## Advanced Customizable Version

ROLE: You are a Revenue Analytics Architect with 16+ years of B2B SaaS GTM experience, specializing in account-based measurement systems, buying group intelligence design, and pipeline quality optimization. You have built MQA scoring models for companies from Series B through post-IPO and have deep expertise in the mathematics of buying committee engagement: signal weighting, recency decay functions, persona coverage gap analysis, and the causal relationship between buying group completeness and win rates. You understand that the shift from MQL to MQA is not just a metric change — it's a fundamental transformation of how marketing proves revenue contribution. You communicate in the language of propensity models, engagement density curves, cohort win rates, and account health scores. You are equally fluent in Salesforce, Marketo/HubSpot, 6sense/Bombora, and Snowflake/BigQuery architectures.

CONTEXT:
Company: [Company name]
Industry vertical: [B2B SaaS vertical — e.g., HR Tech, Security, FinTech, MarTech, DevTools, Data Infrastructure, RevOps]
Business model: [Pure subscription SaaS / Usage-based + subscription / Hybrid PLG + enterprise]
Stage: [Series B / Series C / Series D+ / Public]
Target market: [Enterprise-only >$1B revenue / Mid-market $50M–$1B / SMB <$50M / Multi-segment]
Average ACV: $[amount] | Average sales cycle: [months] | Average deal size range: $[min]–$[max]
GTM motions in play: [Enterprise sales-led / Outbound SDR / Inbound demand gen / ABM / PLG self-serve / Ecosystem partner]
CRM: [Salesforce / HubSpot / other] | Version/edition: [Enterprise / Professional / other]
Marketing automation: [Marketo / HubSpot Marketing / Pardot / Eloqua / Customer.io / other]
ABM/intent platform: [6sense / Demandbase / Bombora / G2 Buyer Intent / Rollworks / none]
Data warehouse: [Snowflake / BigQuery / Redshift / Databricks / none]
BI tool: [Looker / Tableau / Power BI / Metabase / other]
Sales development: [SDR team size: X reps / No SDR team — AE-driven outbound]
Marketing ops team size: [headcount]

CURRENT MQL STATE:
Today's MQL definition: [describe — e.g., "score of 100+ based on email engagement and content downloads"]
Monthly MQL volume: [number]
MQL-to-SQL conversion rate: [%]
SQL-to-opportunity conversion rate: [%]
Marketing-sourced pipeline as % of total: [%]
Known problems with current MQL model: [list pain points — e.g., "sales ignores MQLs," "too many low-intent MQLs," "single contact scoring misses buying committee," "no account-level view"]

BUYING COMMITTEE DEFINITION — ENTERPRISE:
Define all buying committee personas for your primary ICP:
Persona 1 (Economic Buyer): Title(s): [e.g., CFO, VP Finance, Chief Revenue Officer] | Primary concern: [ROI, risk, budget authority] | Typical stage of engagement: [late — signs off on final approval]
Persona 2 (Technical Evaluator): Title(s): [e.g., CTO, VP Engineering, Head of IT/Security] | Primary concern: [security, integration, scalability, implementation] | Typical stage: [mid — evaluates technical fit]
Persona 3 (Business Champion/Initiator): Title(s): [e.g., VP Marketing, VP Sales, Director of Operations] | Primary concern: [workflow improvement, team productivity, business outcomes] | Typical stage: [early-to-mid — initiates and champions]
Persona 4 (End User/Practitioner): Title(s): [e.g., Marketing Manager, Sales Ops, Analyst] | Primary concern: [usability, features, day-to-day workflow] | Typical stage: [early — tests and validates]
Persona 5 (Procurement/Legal — if applicable): Title(s): [e.g., Procurement Manager, Legal Counsel, Vendor Management] | Primary concern: [contract terms, compliance, vendor risk] | Typical stage: [late — finalizes terms]

ENGAGEMENT SIGNAL INVENTORY (all signals your systems can track):
High-intent signals (weight: 5x): [e.g., pricing page visit, demo request, trial start, ROI calculator completion, "contact sales" form fill]
Mid-intent signals (weight: 3x): [e.g., bottom-funnel content download (case studies, ROI reports), webinar attendance, competitive comparison page visit, product feature page depth visit]
Low-intent signals (weight: 1x): [e.g., blog read, email open, ad impression/click, LinkedIn video view, newsletter subscription]
Third-party intent signals: Provider: [6sense / Bombora / G2] | Signals surfaced: [topic clusters / review activity / category surge] | How mapped to accounts: [domain / IP / CRM account match]
Offline signals: [event attendance, field marketing interaction, sales conversation notes captured in CRM]

ACCOUNT UNIVERSE:
Total ICP accounts in your TAM: [number]
Named target account list (Tier 1 ABM): [number of accounts]
Active CRM accounts with ≥1 contact: [number]
Average contacts per account in CRM: [number]
Average contacts per account who are marketing-engaged (last 180 days): [number]

WIN RATE DATA (if available):
Win rate when [1 persona] is engaged vs. [multiple personas] are engaged: [%] vs. [%]
Win rate when economic buyer is engaged vs. not: [%] vs. [%]
Win rate when buying group is ≥[X]% complete vs. less than [X]% complete: [%] vs. [%]
Average deal size when buying group is complete vs. incomplete: $[amount] vs. $[amount]

OBJECTIVE:
Primary goal: [Replace MQL with MQA and prove to sales leadership that MQA-driven accounts convert at higher rates / Build a buying group analytics layer on top of existing ABM program / Justify ABM program investment to CFO using buying group completeness → win rate correlation]
Secondary goal: [Surface buying group gaps to trigger automated plays / Create account intelligence briefs for SDRs / Build board-ready pipeline quality metrics]
Timeline: [Q3 2026 / H2 2026 / FY2027 planning]

CONSTRAINTS:
Marketing attribution constraint: [We can only claim "influenced" pipeline, not sourced / We have agreed with sales on a shared attribution model / Sales credits all pipeline to AEs regardless of marketing]
Data quality constraint: [Contact-to-account matching is unreliable / We have many duplicate contacts / Job title standardization is inconsistent across CRM]
Tool constraint: [We don't have 6sense or an ABM platform — must use HubSpot + Bombora only / We have Salesforce but no Marketing Cloud]
Organizational constraint: [Sales leadership is skeptical of marketing attribution / We need this to be usable by SDRs without training / This must be board-presentable in 90 days]

OUTPUT REQUIREMENTS:

1. MQA SCORING ARCHITECTURE
Design a three-tier account qualification system:
   - Tier 1 (MQA — Marketing Qualified Account): Define minimum scoring criteria for sales handoff
   - Tier 2 (MEA — Marketing Engaged Account): Warm accounts requiring nurture before handoff
   - Tier 3 (MAA — Marketing Aware Account): Early-stage accounts in top-of-funnel awareness
   
   For each tier, specify:
   - Minimum buying committee coverage required (% of personas touched)
   - Minimum aggregate engagement score threshold
   - Recency requirement (last engagement within X days)
   - Intent signal requirements (if applicable)
   - Recommended next action (immediate SDR outreach / marketing nurture / ABM campaign / no action)

2. BUYING GROUP COMPLETION SCORECARD DESIGN
For each buying committee persona:
   - "Dark" state: No engagement recorded — define detection method and triggered play
   - "Aware" state: Low-intent signal only (1x signals) — define engagement threshold and nurture sequence
   - "Engaged" state: Mid-intent signals (3x) — define engagement threshold and content stage
   - "Activated" state: High-intent signal fired (5x) — define SDR alert criteria and handoff protocol
   
   Define the buying group completeness score formula:
   (Σ persona_state_weight × persona_importance_weight) / max_possible_score × 100
   
   Where persona importance weighting reflects win rate impact of each persona's engagement.

3. ACCOUNT ENGAGEMENT DENSITY SCORE (AEDS) FORMULA
Build the composite account scoring model:
   AEDS = (Engagement Volume Score × 0.35) + (Persona Coverage Score × 0.30) + (Recency Score × 0.20) + (Intent Signal Score × 0.15)
   
   For each component:
   - Define the raw input signals and normalization method
   - Specify the recency decay function (linear, exponential, or step-function)
   - Define score floors and ceilings
   - Specify override rules (e.g., single high-intent signal instantly elevates account regardless of composite score)

4. COHORT WIN RATE CORRELATION ANALYSIS
Build the business case for MQA using historical deal data:
   - Retrospective analysis template: for the last [N] closed-won and closed-lost deals, segment by buying group completeness at time of opportunity creation
   - Win rate by buying group completeness cohort: <25% complete / 25–50% complete / 50–75% complete / >75% complete
   - Average deal cycle length by cohort
   - Average ACV by cohort
   - Expected pipeline ROI of improving average buying group completeness by 10 percentage points

5. BUYING GROUP GAP ANALYSIS REPORT (WEEKLY SALES INTELLIGENCE BRIEF)
Design the weekly report marketing delivers to sales leadership:
   - Accounts in pipeline where buying group is <50% complete (highest risk)
   - Missing personas per account (with LinkedIn-sourced contact suggestions)
   - Recommended marketing plays to fill each gap (targeted ad sequences, direct outreach templates, event invitations, content to send)
   - Staleness alerts: accounts where last engagement was >30 days ago
   - Buying group momentum score (trending up vs. flat vs. declining engagement velocity)

6. MQA-TO-REVENUE TRACKING: MARKETING'S NEW MEASUREMENT FRAMEWORK
Replace legacy MQL metrics with these board-ready KPIs:
   - MQA Volume: Accounts meeting MQA threshold this period (vs. goal and prior period)
   - MQA Quality Score: Average AEDS at time of MQA handoff
   - MQA-to-Opportunity Rate: % of MQA accounts that convert to a CRM opportunity within 90 days
   - MQA Influence Rate: % of pipeline that had ≥1 MQA signal prior to opportunity creation
   - Buying Group Coverage Rate: Average % of buying committee engaged across all in-pipeline accounts
   - Buying Group Win Premium: Win rate lift for accounts with >75% buying group complete vs. <50% complete
   
   For each KPI: define the formula, data source, measurement frequency, and benchmark target.

7. TECHNICAL IMPLEMENTATION BLUEPRINT
Specify implementation requirements for the target tech stack:
   - Salesforce custom object/field requirements for storing account-level engagement scores
   - Marketo/HubSpot program architecture for tracking persona-level engagement per account
   - 6sense/Bombora signal mapping to account scoring model
   - Data warehouse query logic for weekly AEDS calculation (SQL pseudocode)
   - Dashboard requirements for sales (Salesforce reporting) and marketing (BI tool)
   - SDR workflow: how MQA alerts trigger in Outreach/Salesloft and what the rep sees

8. CHANGE MANAGEMENT: TRANSITIONING FROM MQL TO MQA
Design the internal rollout plan:
   - 90-day transition plan (parallel run MQL + MQA before full cutover)
   - Sales leadership buy-in deck (3-slide narrative: problem with MQL, MQA proof of concept, expected win rate lift)
   - SDR training protocol (how to read account intelligence briefs and act on buying group gaps)
   - Marketing → sales SLA redefinition for MQA vs. prior MQL SLA

Format as a complete analytical system design document with scoring formulas, example account scorecards, implementation pseudocode, and a CMO-ready executive summary on why this transformation drives revenue.

## Example Input/Output

**Input Example:**

Company: DataSync AI (enterprise data integration platform)
ACV: $120,000 | Sales cycle: 6 months | ICP: Enterprise companies $500M+ revenue
GTM: Enterprise sales-led + outbound SDR + ABM for Tier 1 accounts
CRM: Salesforce Enterprise | MAP: Marketo | Intent: Bombora
Current MQL: Score of 75+ (email clicks, content downloads) | Monthly MQL volume: 180 | MQL-to-SQL rate: 9%
Pain: Sales team ignores most MQLs. "They're garbage — single contacts who clicked an email, not real buyers."
Buying committee: IT VP (technical), CFO or VP Finance (economic), Head of Data Engineering (champion), Data Analysts ×2 (end users), IT Procurement (legal/vendor)
Win rate data: Single contact deals: 8% win rate. Multi-stakeholder (3+ personas engaged): 31% win rate.

**Output Example (Excerpt):**

**DataSync AI MQA Scoring Architecture:**

**Tier 1 — MQA (Marketing Qualified Account): Immediate SDR Handoff**
Minimum criteria (ALL must be met):
- Business Champion or Economic Buyer has fired ≥1 high-intent signal (5x) in last 30 days
- ≥3 distinct personas engaged across buying committee in last 90 days (≥60% coverage)
- Aggregate AEDS ≥ 72 (top 15% of account engagement universe)
- Bombora intent surge active on ≥2 relevant topics (Data Integration, Cloud Data Warehouse, ETL/ELT)
Expected MQA volume at current engagement baseline: ~22 accounts/month
Expected MQA-to-opportunity rate (based on win rate data): 34% (vs. 9% current MQL-to-SQL)

**Buying Group Completion Scorecard — Sample Account: TechGiant Corp:**

| Persona | Current State | Last Signal | Signal Type | Importance Weight | State Score |
|---|---|---|---|---|---|
| IT VP (Zhang Wei) | ✅ Activated | 3 days ago | Pricing page + demo request | 30% | 5.0/5.0 |
| VP Finance (Sarah Chen) | ⚠️ Aware | 18 days ago | Email open only | 25% | 1.0/5.0 |
| Head of Data Engineering (Marcus Rivera) | ✅ Engaged | 7 days ago | ROI calculator + case study | 25% | 3.5/5.0 |
| Data Analyst ×2 (Unknown) | 🔴 Dark | Never | No signal | 15% | 0.0/5.0 |
| Procurement | ⚪ Not yet expected | — | — | 5% | N/A |

**Buying Group Completeness Score: 58% — MEA (Marketing Engaged Account)**
**Gap plays triggered:**
1. VP Finance (Sarah Chen): Trigger CFO-specific LinkedIn ad sequence (ROI/cost savings messaging). Enroll in "Economic Buyer Nurture" email sequence featuring CFO case studies. SDR: Send personalized email with ROI calculator link.
2. Data Analysts: Find on LinkedIn (search DataTechGiant + "Data Analyst" + "Data Engineer"). Add to Marketo program. Trigger "End User Activation" sequence with product sandbox invite.

**AEDS Score: 64 out of 100**
Engagement Volume: 28/35 | Persona Coverage: 18/30 | Recency: 14/20 | Intent: 4/15 (only 1 Bombora topic active)

**Recommended action:** Escalate to MEA status. SDR warm outreach to IT VP + Head of Data Engineering now. Marketing continue buying group gap fills for 3 more weeks. Re-evaluate for MQA at next weekly score refresh.

---

**MQA vs. MQL Revenue Impact Projection:**
DataSync AI MQL benchmark: 180 MQLs/month × 9% to SQL = 16.2 SQLs/month × 22% SQL-to-close × $120K ACV = $427,680/month in pipeline
DataSync AI MQA projection: 22 MQAs/month × 34% to opportunity = 7.5 opps/month × 38% win rate (buying group complete) × $135K avg ACV (larger deals correlate to complete committees) = $384,750/month in PIPELINE — but only 7.5 opps vs. 16 SQLs from MQL, meaning quality replaces quantity: win rate is 73% higher, average ACV is 12.5% higher, and sales team trust increases because every handed-off account has executive engagement verified.

## Success Metrics

- MQA-to-opportunity conversion rate ≥25% (vs. legacy MQL-to-SQL baseline)
- Buying group completeness score ≥65% average across MQA handoffs
- Win rate for accounts with complete buying groups is ≥20 percentage points higher than incomplete
- Sales team MQA acceptance rate ≥80% (sales pulls the MQA list, doesn't reject it)
- Time-to-first-meeting from MQA handoff ≤5 business days
- Marketing-influenced pipeline with ≥3 personas engaged grows month-over-month
- SDR outreach to MQA accounts results in ≥3x meeting set rate vs. cold outreach baseline

## Related Prompts
- [MQL to MQA Transformation & Account-Based Pipeline Qualification](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-B2B-SaaS-MQL-to-MQA-Transformation-&-Account-Based-Pipeline-Qualification-Revenue-Intelligence-Engine.md)
- [Marketing-to-Sales Lead Handoff Quality & MQL-SQL Revenue Intelligence](../../05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/AI-Powered-B2B-SaaS-Marketing-to-Sales-Lead-Handoff-Quality-&-MQL-SQL-Revenue-Intelligence-Engine.md)
- [ABM Buying Committee Engagement Scoring & Multi-Stakeholder Deal Velocity](../../05_Analytics-&-Performance/Account-Based-Marketing-Analytics/AI-Powered-ABM-Buying-Committee-Engagement-Scoring-&-Multi-Stakeholder-Deal-Velocity-Intelligence-Engine.md)
- [Marketing Pipeline Coverage & Revenue Gap Intelligence](../../05_Analytics-&-Performance/Revenue-Forecasting-&-Pipeline-Intelligence/Marketing-Pipeline-Coverage-&-Revenue-Gap-Intelligence-Engine.md)

## Integration Tips

**Salesforce Integration:**
- Create a custom "Account Engagement Score" (AEDS) field on the Account object updated weekly via a Snowflake → Salesforce sync
- Build a "Buying Group Completeness %" formula field that counts contacts per persona title pattern against total committee size
- Create a Salesforce Report/Dashboard "MQA Pipeline Intelligence" filtered to Accounts where AEDS ≥ 72 and Buying Group Completeness ≥ 60%
- Configure Salesforce Flow to auto-create an SDR task when account crosses MQA threshold for the first time

**Marketo/HubSpot Integration:**
- Build "Buying Committee Persona" custom field on Contact object (dropdown: Economic Buyer / Technical Evaluator / Champion / End User / Procurement)
- Create Smart Lists per persona type filtered to ICP target accounts
- Build engagement scoring programs per persona with separate score tokens that roll up to account-level aggregation via Marketo's Account-Based Marketing feature or a custom Zapier/API flow
- For HubSpot: Use Association Labels to tag contacts as committee personas, then use Lists + custom properties to build account-level engagement summaries

**6sense/Demandbase Integration:**
- Map 6sense buying stage (Awareness / Consideration / Decision / Purchase) as an override signal in your MQA scoring model — accounts in "Decision" or "Purchase" stage instantly qualify as MQA regardless of AEDS
- Use 6sense contact discovery to surface unengaged buying committee personas and add them to Marketo nurture
- Sync 6sense account segments to Salesforce for real-time SDR queue prioritization

**Snowflake/Data Warehouse:**
- Run weekly AEDS calculation as a scheduled dbt model pulling from Salesforce, Marketo, Bombora, and website analytics
- Build a "buying_group_completeness" table joining Contact.persona_type to Account with engagement event counts per persona
- Create an "mqa_alert" table that flags accounts crossing MQA threshold since last week's run for SDR notification

**Outreach/Salesloft Integration:**
- Configure MQA webhook to create a personalized Outreach sequence auto-enrollment for the primary champion contact when MQA threshold is crossed
- Include buying group completeness data in the SDR's account "intelligence panel" via custom field sync
- Set sequence personalization variables to pull the specific content the champion consumed for hyper-relevant first-touch messaging

## Troubleshooting

**Problem: Sales team says buying group personas can't be identified because CRM contacts lack standardized titles.**
Solution: Implement an AI title normalization layer (use the OpenAI API or a tool like Clay) that maps raw job titles to persona buckets. Example: "Sr. Data Engineer," "Analytics Lead," "Head of BI" all map to "Technical Evaluator." Run this as a weekly enrichment job on all CRM contacts linked to target accounts. Build a title taxonomy of 50–100 raw titles per persona category. This alone typically improves buying group completeness identification by 40–60%.

**Problem: MQA volume is too low (only 5–8 accounts/month) and sales says it's not enough to fill pipeline.**
Solution: You likely have thresholds set too high for your current engagement baseline. Start by lowering the persona coverage minimum from 3 personas to 2, and accept MEA (Marketing Engaged Account) accounts into a parallel "sales assist" queue where SDRs make 1 outreach attempt before the account is promoted to MQA. Also audit your contact-to-account matching — if only 30% of engaged contacts are matched to CRM accounts, the missing 70% are suppressing your buying group scores artificially. Fix data matching first, then recalibrate thresholds.

**Problem: No historical win rate data to prove buying group completeness → win rate correlation.**
Solution: Run a 90-day proof-of-concept: tag all accounts in current active pipeline with their buying group completeness score at the time of opportunity creation (retroactively, using Marketo/Salesforce engagement history). At quarter end, pull win rates segmented by completeness score quintile. Even with a small sample, a 15–20 deal set typically shows a statistically meaningful correlation. This becomes your internal business case for the MQA transformation.

## Version History
- v1.0: Initial creation (auto-generated)
