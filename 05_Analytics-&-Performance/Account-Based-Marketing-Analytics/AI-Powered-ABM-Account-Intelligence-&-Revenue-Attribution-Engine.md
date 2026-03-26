# AI-Powered ABM Account Intelligence & Revenue Attribution Engine - Measure, Optimize, and Scale Account-Based Marketing ROI

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** abm, account-based-marketing, attribution, revenue-intelligence, b2b, pipeline, analytics, intent-data

## Overview
This prompt builds a comprehensive ABM analytics system that measures account engagement across the buying committee, attributes pipeline and revenue to ABM investments, identifies which account segments and plays are generating ROI, and produces the account-level intelligence needed to optimize spend and scale what's working. Use it when you need to justify ABM investment, diagnose underperforming programs, or design a measurement framework from scratch.

## Quick Copy-Paste Version

You are a senior B2B revenue analytics strategist specializing in account-based marketing measurement. Build a complete ABM intelligence and revenue attribution system for my program.

Company: [Your Company Name]
Product: [What you sell]
ABM tiers: [e.g., Tier 1 (1:1) = 50 accounts, Tier 2 (1:few) = 200 accounts, Tier 3 (1:many) = 500 accounts]
ICP: [e.g., VP/C-Suite at 500-5,000 employee SaaS companies]
Buying committee size: [e.g., 5-8 stakeholders per account]
Average deal size: [$X ARR]
Sales cycle: [X months]
ABM channels active: [e.g., LinkedIn Ads, direct mail, personalized email, events, content syndication]
Current CRM/MAP stack: [e.g., Salesforce + HubSpot + 6sense]
Monthly ABM budget: [$X]

Build the following:

1. ACCOUNT ENGAGEMENT SCORING MODEL
Design a composite account engagement score (0-100) that aggregates signals across the buying committee. Include: intent signal weighting (first-party vs. third-party), persona coverage score (% of buying committee engaged), channel engagement breadth, content consumption depth, and recency decay factors. Specify the exact formula and how to calculate it in Salesforce or HubSpot.

2. ABM PIPELINE ATTRIBUTION FRAMEWORK
Build a multi-touch attribution model specific to ABM programs that answers: which ABM plays generated pipeline, what is the account velocity from target → engaged → MQA → opportunity → closed-won, and what percentage of closed-won revenue was ABM-influenced vs. ABM-sourced. Define the attribution windows and logic for each tier.

3. ACCOUNT HEALTH & PROGRESSION ANALYTICS
Create a dashboard showing account movement through the ABM funnel stages: Identified → Targeted → Engaged → Marketing Qualified Account (MQA) → Sales Accepted → Opportunity → Closed. For each stage transition, define: conversion rate benchmarks, average time-in-stage, drop-off signals, and the trigger that moves accounts forward.

4. PROGRAM ROI ANALYSIS BY TIER AND PLAY
Produce an ROI breakdown that compares: ABM tier performance (Tier 1 vs. 2 vs. 3), play performance (which specific campaigns drove the most pipeline per dollar), channel performance within ABM (which channels move accounts fastest), and segment performance (which ICP segments convert at the highest rates).

5. PREDICTIVE ACCOUNT PRIORITIZATION
Using engagement score + firmographic data + intent signals, identify: the top 20% of accounts most likely to convert in the next 90 days, accounts showing buying committee expansion signals (new stakeholders engaging), and accounts that are at risk of going dark and need re-engagement plays.

Output as structured tables, scoring formulas, and a prioritized action plan the team can implement this week.

## Advanced Customizable Version

ROLE: You are a principal-level B2B revenue analytics architect with 15+ years designing ABM measurement systems for enterprise SaaS companies. You have deep expertise in multi-touch attribution (Bizible/Marketo Measure, Salesforce attribution), intent data providers (6sense, Bombora, G2 Buyer Intent), account engagement platforms (Demandbase, Terminus, RollWorks), and revenue operations analytics. You combine rigorous statistical methodology with practical GTM intuition to produce measurement systems that both practitioners and CFOs trust.

COMPANY CONTEXT:
- Company: [Company Name]
- Stage: [Series B / Series C / Public / $X ARR]
- Product category: [e.g., "AI-powered supply chain optimization platform"]
- ICP definition: [Buyer title + company size + industry + tech stack indicators]
- Buying committee: [List all personas: economic buyer, champion, technical evaluator, legal, etc.]
- Average contract value: [$X ARR]
- Sales cycle length: [X months]
- Win rate: [X%]
- Current pipeline coverage ratio: [X:1]
- ABM program age: [X months/years]
- ABM tiers and account counts: [Tier 1: X accounts, Tier 2: X accounts, Tier 3: X accounts]
- Active ABM channels: [List all channels and monthly spend per channel]
- Total ABM budget: [$X/month]
- MarTech stack: [CRM / MAP / ABM Platform / Intent Provider / BI Tool]
- Current attribution model: [First-touch / Last-touch / Linear / Custom]
- Top 3 ABM measurement challenges: [e.g., dark funnel attribution, committee coverage gaps, long sales cycles]

SECTION 1: ACCOUNT ENGAGEMENT INTELLIGENCE ARCHITECTURE

Build a tiered account engagement scoring system using the "Buying Committee Signal Pyramid":

Layer 1 — ACCOUNT-LEVEL INTENT SIGNALS (Weight: 40%)
For each intent data source, specify:
a) Signal type: [Bombora surge topics / G2 profile views / 6sense model scores / website visit patterns]
b) Signal scoring: How to normalize disparate intent signals to a 0-10 scale
c) Signal decay: Time-weighted scoring that reduces signal value after 7/14/30 days
d) Threshold triggers: What score triggers a Tier upgrade or sales alert
e) Data ingestion: How to pull signals into Salesforce/HubSpot via API or native integration

Layer 2 — BUYING COMMITTEE COVERAGE SCORE (Weight: 35%)
Design a committee coverage model that tracks:
a) Known contacts as % of target committee (e.g., 3 of 7 personas engaged = 43% coverage)
b) Persona gap analysis: Which roles are unengaged and what content/channel activates them
c) Multi-threaded deal scoring: Accounts with 4+ engaged personas score 2x higher
d) Champion identification signals: Who is sharing content, requesting demos, or sponsoring the evaluation
e) Executive sponsor detection: How to identify and track C-suite engagement separately

Layer 3 — BEHAVIORAL ENGAGEMENT DEPTH (Weight: 25%)
Track content consumption and channel engagement with precision:
a) Content engagement scoring: [Whitepaper download = 5pts / Webinar attendance = 8pts / Demo request = 20pts / Pricing page visit = 15pts / Case study view = 7pts]
b) Channel breadth bonus: Accounts engaged across 3+ channels receive a 1.25x multiplier
c) Recency score: Engagement in last 7 days = full value; 8-14 days = 75%; 15-30 days = 50%; 31+ days = 25%
d) Negative signals: Track and penalize unsubscribes, spam reports, or content blocking

COMPOSITE ACCOUNT SCORE FORMULA:
Account Score = [(Intent Signal Score × 0.40) + (Committee Coverage Score × 0.35) + (Behavioral Depth Score × 0.25)] × Recency Multiplier × Tier Weight

Output the formula as a Salesforce formula field and a Google Sheets version.

SECTION 2: ABM REVENUE ATTRIBUTION METHODOLOGY

Build a custom ABM attribution model that accounts for the unique characteristics of account-based programs:

A. SOURCE vs. INFLUENCE ATTRIBUTION
Define clear rules for:
- ABM-Sourced Pipeline: Opportunities where the first meaningful engagement was an ABM touch (define "meaningful": not just an ad impression, but a content download, event attendance, or direct response)
- ABM-Influenced Pipeline: Opportunities where ABM touches occurred within [X days] of the opportunity creation date or during the active sales cycle
- ABM Acceleration Attribution: Measure whether ABM-touched deals close faster and at higher ACV than non-ABM deals
- Methodology: Use control group analysis — compare ABM-targeted accounts vs. lookalike accounts not in the ABM program to calculate true lift

B. MULTI-TOUCH ATTRIBUTION WITHIN ABM
For Tier 1 (1:1) accounts, implement contact-level attribution:
- Map every marketing touch to a specific contact and their role in the buying committee
- Assign fractional credit using a W-shaped model: 30% to first touch, 30% to opportunity creation touch, 30% to closed-won touch, 10% distributed across middle touches
- Build a "last ABM touch before opportunity creation" report to identify which plays are converting accounts

C. ATTRIBUTION WINDOWS BY TIER
- Tier 1 accounts: 18-month attribution window (long enterprise sales cycles)
- Tier 2 accounts: 12-month attribution window
- Tier 3 accounts: 6-month attribution window
- Justify the windows using your actual average sales cycle data

D. REVENUE CONTRIBUTION CALCULATION
Build this executive-ready formula:
ABM Revenue Contribution = (ABM-Sourced Closed Won) + (ABM-Influenced Closed Won × Influence Credit %)
Influence Credit % = [engagement touchpoints by ABM] ÷ [total marketing touchpoints in deal]
Report separately: Pipeline Generated ($), Pipeline Influenced ($), Closed Won ($), ACV Lift vs. Non-ABM Deals (%), Sales Cycle Acceleration (days faster)

SECTION 3: ABM FUNNEL ANALYTICS & STAGE PROGRESSION

Build a full ABM funnel with stage definitions, conversion benchmarks, and diagnostic triggers:

STAGE 1: TARGET ACCOUNT IDENTIFIED
- Definition: Account meets ICP criteria and has been added to ABM program
- Entry criteria: Firmographic match score > 75%, intent signal detected, or sales nominated
- Exit trigger: First marketing-qualified engagement detected
- Benchmark: Industry standard shows 15-25% of target accounts engage within 60 days
- Diagnostic: Accounts stuck here > 60 days → review if ICP criteria is too broad or content is not reaching the right personas

STAGE 2: ACCOUNT ENGAGED
- Definition: At least one buying committee member has had a meaningful interaction (content download, ad click leading to 2+ page sessions, event registration)
- Entry criteria: Account Engagement Score > 20
- Exit trigger: MQA threshold reached
- Benchmark: 40-60% of engaged accounts reach MQA within 90 days
- Diagnostic: Low MQA conversion → analyze which content assets and channels drive highest engagement-to-MQA rates

STAGE 3: MARKETING QUALIFIED ACCOUNT (MQA)
- Definition: Account demonstrates sufficient buying signal to warrant sales engagement
- Entry criteria: Account Score > 60 AND (committee coverage ≥ 3 personas OR executive-level engagement OR pricing/demo page visit)
- Handoff SLA: Sales must conduct first outreach within 24 hours of MQA designation
- Exit trigger: Sales Accepted Lead (SAL) created in CRM
- Benchmark: 25-35% of MQAs convert to sales-accepted opportunities
- Diagnostic: Low SAL rate → sales/marketing misalignment on MQA definition; run a cohort analysis of MQAs that sales rejected and identify pattern

STAGE 4: SALES ACCEPTED → OPPORTUNITY → CLOSED
- Track: Time from SAL to opportunity, opportunity to closed-won, and overall velocity vs. non-ABM deals
- Report: Win rate for ABM-sourced vs. ABM-influenced vs. non-ABM opportunities
- ACV analysis: Compare average contract value across ABM tiers — Tier 1 should show 2-3x higher ACV

SECTION 4: PROGRAM ROI DASHBOARD DESIGN

Build a three-level reporting structure:

LEVEL 1: EXECUTIVE DASHBOARD (CMO/CRO, weekly)
Metrics: Pipeline generated by ABM ($), Pipeline influenced by ABM ($), MQA volume and conversion rate, ABM win rate vs. company win rate, ABM ACV vs. company ACV, Top 10 accounts by engagement score

LEVEL 2: PROGRAM MANAGER DASHBOARD (Demand Gen/ABM team, daily)
Metrics: Account engagement score distribution, Accounts upgraded/downgraded this week, Stage progression velocity, Play performance by campaign type, Channel performance (CPE = cost per engaged account), Committee coverage gaps by tier

LEVEL 3: ACCOUNT-LEVEL INTELLIGENCE (Sales/SDR, per account)
Metrics: Individual account score and trend (up/down/flat), Engaged contacts with last touch date and asset, Missing personas with recommended outreach plays, Next best action recommendation, Competitor intelligence signals for this account

SECTION 5: PREDICTIVE ACCOUNT PRIORITIZATION MODEL

Build a propensity-to-convert model using these input signals:

POSITIVE SIGNALS (Increase priority score):
- Account score jumped 20+ points in last 7 days: +25 priority points
- New executive-level contact identified and engaged: +20 priority points
- Competitor product research detected via intent data: +15 priority points
- Pricing or ROI calculator page visited: +20 priority points
- Champion has forwarded content or CC'd new stakeholders: +15 priority points
- Two or more MQA criteria met simultaneously: +30 priority points
- Account in active contract renewal cycle with competitor: +25 priority points

NEGATIVE SIGNALS (Decrease priority score or trigger re-engagement play):
- No engagement in 30 days from previously engaged account: -20 points + auto-trigger re-engagement sequence
- Unsubscribes or contact opt-outs: -30 points + alert sales
- Key champion departed company (job change detected): -40 points + trigger "new champion identification" play
- Negative sentiment in intent data topics: -15 points

PRIORITIZATION OUTPUT:
Produce a weekly "ABM Hot List" segmented as:
1. STRIKE NOW (Score 80+, trending up): Immediate sales outreach required within 24 hours
2. NURTURE INTENSIVELY (Score 50-79): Marketing-led plays with sales on standby
3. RE-ENGAGE (Score 20-49, declining): Specific re-engagement campaign triggered
4. WATCH LIST (Score < 20): Low-frequency awareness touches only

## Example Input/Output

**Input Example:**

Company: Velociti (B2B SaaS — AI-powered fleet management platform)
ABM Tiers: Tier 1 = 40 accounts (Fortune 1000 logistics/transportation), Tier 2 = 150 accounts (mid-market fleets 500+ vehicles), Tier 3 = 600 accounts (regional operators)
Buying committee: Fleet VP (economic buyer), IT Director (technical), CFO (financial approval), Safety Manager (champion), Procurement (legal/contracts)
ACV: $180,000
Sales cycle: 7 months
ABM spend: $85,000/month across LinkedIn Ads ($30K), direct mail ($15K), events ($20K), content syndication ($10K), intent data ($10K)
Stack: Salesforce + Pardot + 6sense + Demandbase + Tableau

**Output Example:**

ACCOUNT ENGAGEMENT SCORE — SAMPLE OUTPUT FOR ACCOUNT: "Apex Freight Solutions"

| Signal Category | Score | Weight | Weighted Score |
|---|---|---|---|
| Intent Signal (6sense model score: 82/100) | 8.2 | 40% | 3.28 |
| Committee Coverage (4/5 personas engaged) | 8.0 | 35% | 2.80 |
| Behavioral Depth (3 webinars + pricing page + demo request) | 9.5 | 25% | 2.38 |
| **Raw Score** | | | **8.46/10** |
| Recency Multiplier (fleet VP engaged yesterday) | | | × 1.0 |
| Tier Weight (Tier 1) | | | × 1.0 |
| **FINAL ACCOUNT SCORE** | | | **84.6 / 100** |

**Status: STRIKE NOW — Alert sent to AE Sarah Chen at 9:14 AM**

MQA THRESHOLD BREACHED: ✅ Score > 60 ✅ 4 personas engaged ✅ Pricing page visited (Fleet VP, 3 pages, 6:47 PM Tuesday)
MISSING PERSONA: Procurement (Maria Santos) — Recommended play: Send AE personalized "compliance and vendor approval" one-pager via LinkedIn message

---

PROGRAM ROI — Q1 SNAPSHOT (Velociti):

| Metric | Tier 1 | Tier 2 | Tier 3 | Total |
|---|---|---|---|---|
| Pipeline Generated | $4.2M | $2.1M | $0.8M | $7.1M |
| Pipeline Influenced | $6.8M | $3.4M | $1.2M | $11.4M |
| Closed Won (Sourced) | $1.4M | $0.6M | $0.2M | $2.2M |
| Win Rate | 38% | 29% | 21% | 29% |
| ACV (ABM) vs. ACV (Non-ABM) | $195K vs. $122K | $143K vs. $98K | $82K vs. $71K | +56% lift |
| Cost per MQA | $4,200 | $1,800 | $420 | $1,680 |
| Blended ROAS | 8.4x | 6.7x | 4.9x | 6.8x |

**Top Performing Play:** Q1 Executive Roundtable (New York) — 8 Tier 1 accounts attended → 5 MQAs → 3 opportunities → $1.1M pipeline in 60 days ($138K cost = 7.9x pipeline ROI)

## Success Metrics

- **Account score accuracy:** Engaged accounts in top quartile of scores should convert to MQA at 2x the rate of bottom quartile
- **Attribution coverage:** ≥ 85% of closed-won deals in the ABM program should have traceable ABM attribution (no "unknown" gaps)
- **MQA conversion rate:** 25-40% of MQAs should convert to sales-accepted opportunities within 30 days
- **ABM ACV lift:** ABM-sourced deals should show ≥ 30% higher ACV vs. non-ABM inbound deals
- **Sales cycle acceleration:** ABM-touched opportunities should close 20-35% faster than company average
- **Tier 1 engagement rate:** ≥ 60% of Tier 1 target accounts should show meaningful engagement within 90 days
- **Committee coverage:** Average Tier 1 account should have ≥ 60% of buying committee roles engaged at opportunity stage
- **Pipeline ROI:** ABM program should generate ≥ 5x pipeline ROI (pipeline generated ÷ ABM spend)

## Related Prompts

- [ABM Campaign Orchestration & Account Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Campaign-Orchestration-&-Account-Intelligence-Engine.md)
- [ABM Intent Data Activation & Buying Signal Prioritization Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](../Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [Lead Scoring Model Optimization & Predictive Buying Signal Intelligence Engine](../Lead-Quality-&-Conversion-Analytics/Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md)

## Integration Tips

- **Salesforce:** Create a custom Account Score field using the composite formula; use Process Builder or Flow to auto-alert AEs when score crosses MQA threshold (>60); build a custom ABM Pipeline report that segments by Tier and filters to ABM-tagged campaigns
- **HubSpot:** Use custom properties for account score components; set up workflows to enroll contacts in sequences when account score changes; use the ABM module (Enterprise) for native buying-committee tracking and company-level attribution
- **6sense / Bombora:** Pipe intent scores via native Salesforce/HubSpot connectors; set up weekly API pulls to refresh scores; use 6sense's predictive model as an input signal (weight it 30-40% of your intent layer)
- **Demandbase / Terminus / RollWorks:** Use platform-native account engagement data as your behavioral depth input; export weekly account engagement scores to Salesforce via API; leverage platform-native "hot accounts" lists to cross-reference your composite model
- **Tableau / Looker / Power BI:** Build the three-level dashboard hierarchy using Salesforce as the data source; create a live "ABM Hot List" view that refreshes daily; set up email delivery of the executive dashboard every Monday morning at 6 AM
- **Slack:** Use Salesforce/HubSpot webhooks to post real-time alerts to a #abm-hot-accounts Slack channel when account scores cross key thresholds; tag the relevant AE automatically

## Troubleshooting

**Problem:** Account scores are too uniformly high — everyone looks like a priority.
**Solution:** Review signal weighting — intent data providers often score all accounts high to appear valuable. Apply a normalization step: rank accounts by percentile within each tier rather than using absolute scores. Also add a minimum threshold for committee coverage (require at least 2 personas engaged before any account can score above 50).

**Problem:** Sales team doesn't trust or use the ABM hot list.
**Solution:** Run a win/loss cohort analysis showing the correlation between account score at opportunity creation and win rate. Present it as "accounts that scored 70+ at opportunity creation win at 40% vs. 18% for accounts below 50." Involve a top-performing AE in calibrating the score thresholds — when sellers help design the model, they adopt it.

**Problem:** Attribution data is incomplete — many deals show no ABM touches.
**Solution:** This is typically a data hygiene problem: (1) ensure all ABM campaign UTMs are correctly tagged and flowing into the CRM, (2) check that offline touchpoints (events, direct mail) are being logged as activities against the account in Salesforce, (3) audit whether your MAP is correctly associating contacts to the right Account record (duplicate accounts are the #1 culprit). Use a tool like LeanData or Lean Data (Salesforce) or Openprise to standardize account matching.

## Version History
- v1.0: Initial creation (auto-generated)
