# AI-Powered ABM Expansion Revenue & Customer Account Growth Intelligence Engine - Measure, Predict, and Scale Upsell and Cross-Sell Revenue Across Your Customer Base

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** abm, expansion-revenue, upsell, cross-sell, customer-marketing, land-and-expand, net-revenue-retention, analytics, b2b-saas

## Overview
This prompt builds a full-stack ABM analytics system specifically for expansion revenue — measuring whitespace opportunity across existing accounts, predicting which customers are ready for upsell or cross-sell, attributing marketing plays to expansion pipeline, and designing the account-level intelligence that lets CS and sales teams act fast. Use it when expansion revenue is a material part of your ARR growth target and you need a rigorous, automatable measurement system to prove and scale it.

## Quick Copy-Paste Version

You are a senior B2B revenue analytics strategist specializing in expansion revenue and customer-led growth. Build a complete ABM expansion intelligence system for my existing customer base.

Company: [Your Company Name]
Product/platform: [What you sell — note if it has multiple products, modules, or tiers]
Current customer count: [X customers]
Average initial contract: [$X ARR]
Expansion revenue target: [$X or X% of total ARR growth]
Typical expansion types: [e.g., seat expansion, module upsell, tier upgrade, geographic expansion]
Customer health scoring tool: [e.g., Gainsight, Totango, ChurnZero, or manual]
CRM/MAP stack: [e.g., Salesforce + Marketo + HubSpot]
CS-to-sales handoff model: [e.g., CS owns expansion < $50K, sales owns > $50K]

Build the following:

1. EXPANSION SIGNAL SCORING MODEL
Design a composite expansion readiness score (0-100) that combines product usage signals, support sentiment, engagement breadth, and contract indicators. Specify the exact formula, data inputs, and how to calculate it in Salesforce or your CS platform.

2. WHITESPACE ANALYSIS FRAMEWORK
For each customer account, map current product adoption against total addressable wallet. Identify specific upsell and cross-sell opportunities by product module, user segment, and department.

3. EXPANSION ABM ATTRIBUTION MODEL
Define how to attribute marketing touches (customer webinars, newsletters, executive briefings, in-product campaigns) to expansion pipeline and closed-won expansion ARR.

4. PREDICTIVE EXPANSION PRIORITIZATION
Using usage signals + contract data + engagement patterns, rank customers by expansion propensity in the next 60-90 days. Define the top signals that indicate imminent expansion readiness.

5. EXPANSION REVENUE DASHBOARD
Design a three-tier reporting structure: executive (NRR and expansion ARR), program manager (campaign performance and account scoring), and account-level (CS/AE view of specific expansion plays and next best actions).

Output as structured tables, scoring formulas, and a prioritized action plan ready to implement in your CRM and CS platform.

## Advanced Customizable Version

ROLE: You are a principal-level B2B revenue analytics architect with 15+ years designing expansion revenue and customer marketing measurement systems for enterprise SaaS companies. You specialize in net revenue retention optimization, customer-led growth analytics, and ABM programs applied to existing customer bases. You understand the intersection of Customer Success, product analytics, and demand generation — and you build measurement systems that CS leaders, CROs, and CFOs trust to drive capital allocation decisions.

COMPANY CONTEXT:
- Company: [Company Name]
- Stage: [Series B / Series C / Public / $X ARR]
- Product: [Platform with modules? Single product with tiers? Multi-product portfolio?]
- Current NRR: [X%] Target NRR: [X%]
- Expansion revenue as % of total ARR: [X%] Target: [X%]
- Customer segments: [Enterprise / Mid-Market / SMB — counts and average ACV per segment]
- Typical expansion motions: [Seat growth / module adoption / tier upgrade / subsidiary expansion / geographic rollout]
- Average time from initial land to first expansion: [X months]
- CS team structure: [X CSMs covering X accounts each; coverage model: high-touch / tech-touch / hybrid]
- CS-to-sales handoff threshold: [$X opportunity size or deal type]
- Current CS platform: [Gainsight / Totango / ChurnZero / Salesforce native / spreadsheet]
- Product analytics tool: [Mixpanel / Amplitude / Heap / Pendo / none]
- CRM: [Salesforce / HubSpot]
- MAP: [Marketo / HubSpot / Pardot]
- Current expansion attribution methodology: [First-touch / Last-touch / None / Custom]
- Top 3 expansion measurement challenges: [e.g., CS-to-marketing attribution gap, product signal data silos, long expansion cycles with no clear trigger]

SECTION 1: EXPANSION SIGNAL ARCHITECTURE & SCORING MODEL

Build a composite Expansion Readiness Score (ERS) using the "Customer Growth Signal Stack":

LAYER 1 — PRODUCT USAGE SIGNALS (Weight: 45%)
For each usage signal, specify:
a) Signal type: Daily/weekly active users (DAU/WAU), feature adoption depth, API call volume, data volume processed, workflow automation count, integrations activated
b) Usage trajectory scoring: Trending up (last 30 days vs. prior 30 days) = +10 pts; Plateau = 0 pts; Declining = -10 pts
c) Capacity utilization: % of licensed seats/usage limits consumed. Thresholds: >80% utilization = strong expansion signal (+20 pts); 60-80% = moderate (+10 pts); <60% = watch
d) Power user concentration: If >50% of usage comes from <20% of users = expansion opportunity (new teams/departments not yet on platform)
e) Feature whitespace: Track which core features have <30% adoption — these are expansion conversation starters, not red flags

EXPANSION USAGE SCORING TABLE:
| Signal | Threshold | Points |
|---|---|---|
| Seat utilization >85% | Any plan | +25 |
| WAU growth >20% MoM | Any plan | +20 |
| New department/team using product | Detected via new user domain/org | +15 |
| API volume growth >30% | Developer/API plan | +20 |
| Premium feature trial initiated | In-product | +25 |
| 3+ integrations activated | Any plan | +10 |
| Power users forwarding content or inviting colleagues | Referral signal | +15 |

LAYER 2 — CONTRACT & COMMERCIAL SIGNALS (Weight: 30%)
Track and score:
a) Contract approaching renewal: 90-day window = +15 pts; 60-day window = +25 pts; 30-day window = +30 pts (also triggers urgency flag)
b) Multi-year contract with expansion clause: Existing contractual commitment to expand = +10 pts
c) ACV vs. ICP benchmark: If current ACV is <40% of typical ACV for comparable companies = significant whitespace (+20 pts)
d) Budget cycle alignment: Enterprise accounts in Q4 budget planning (August-October) = +15 pts due to budget availability
e) Historical expansion pattern: Previous expansion within 12 months = +20 pts (strongest predictor of future expansion)

LAYER 3 — ENGAGEMENT & SENTIMENT SIGNALS (Weight: 25%)
a) Executive engagement score: C-suite or VP-level contacts who attended executive briefing, QBR, or customer advisory board = +20 pts
b) Support health: NPS > 50 = +10 pts; CSAT > 4.5 = +10 pts; open critical support tickets = -20 pts; escalations in last 90 days = -30 pts
c) Community and content engagement: Active in customer community, attending webinars, consuming product update content = +5-10 pts
d) Reference/advocacy signals: Customer agreed to be a reference, submitted G2/Gartner review, participated in case study = +15 pts (highly satisfied customers expand)
e) Champion turnover: Key champion departed = -30 pts + trigger "new champion identification" play immediately

COMPOSITE EXPANSION READINESS SCORE FORMULA:
ERS = [(Usage Score × 0.45) + (Commercial Score × 0.30) + (Engagement Score × 0.25)] × Health Multiplier

Health Multiplier:
- Green health (no open escalations, NPS > 40): × 1.0
- Yellow health (minor issues, NPS 20-40): × 0.75
- Red health (active escalation or churn risk): × 0.25 (do not pursue expansion until resolved)

Output as a Salesforce formula field, a Gainsight/Totango rule set, and a Google Sheets template.

SECTION 2: WHITESPACE ANALYSIS & EXPANSION OPPORTUNITY MAPPING

Build a systematic whitespace analysis for each customer account:

WHITESPACE DIMENSION 1 — USER/SEAT EXPANSION
For each account:
- Calculate: Current licensed seats ÷ Total employees (or target department size)
- Benchmark: What % of employees at similar companies use the platform?
- Gap analysis: If benchmark is 45% adoption and customer is at 22%, there is a 2x seat expansion opportunity
- Identify: Which departments or office locations are NOT on the platform yet?
- Outreach trigger: When seat utilization crosses 75%, auto-trigger CS outreach about seat upgrade

WHITESPACE DIMENSION 2 — PRODUCT MODULE EXPANSION
Create an "adoption matrix" for each customer showing:
- Products/modules purchased vs. available
- Feature adoption rate per module (% of users using each feature)
- Recommended next module based on use case and industry (propensity model)
- Typical expansion sequence: Document the most common land → expand paths from your own data
  Example: Land on [Core Module] → expand to [Analytics Module] (avg 6 months) → expand to [API/Integration Module] (avg 12 months)

WHITESPACE DIMENSION 3 — GEOGRAPHIC/SUBSIDIARY EXPANSION
For accounts that are divisions of larger enterprises:
- Identify parent company and total subsidiary structure (use ZoomInfo or LinkedIn for org mapping)
- Map which subsidiaries or regions are NOT customers
- Calculate TAW (Total Addressable Wallet): [Benchmark ACV] × [Number of subsidiaries not yet contracted]
- Prioritize subsidiaries where: the champion has cross-org influence, the same use case applies, or there are shared technology infrastructure decisions

WHITESPACE DIMENSION 4 — TIER/PLAN UPGRADE
Track customers approaching plan limits:
- Define limits per plan tier (e.g., Starter: up to 10 users, 100GB data; Professional: up to 50 users, 1TB data; Enterprise: unlimited)
- Alert trigger: 75% of limit reached = CSM outreach + in-product upgrade prompt
- Pricing page visits by existing customers: Track separately from new prospect visits — this is a strong self-serve upgrade signal

WHITESPACE OUTPUT: For each account, produce:
- Expansion Opportunity Score (weighted by deal size potential × ERS)
- Recommended Play Type (seat expansion / module upsell / tier upgrade / subsidiary)
- Estimated expansion ARR potential
- Confidence level (High/Medium/Low) based on signal strength

SECTION 3: EXPANSION ABM ATTRIBUTION METHODOLOGY

Define how marketing touches are attributed to expansion pipeline, separate from new logo attribution:

A. MARKETING TOUCHES THAT DRIVE EXPANSION
Categorize and track these expansion-specific marketing motions:
1. Customer newsletters and product update emails → measure click-through to feature pages, pricing pages, upgrade flows
2. Customer webinars and training content → measure attendance correlation with expansion events
3. Executive Briefing Center (EBC) visits and QBRs → log as marketing-influenced touches if marketing orchestrated
4. In-product notification campaigns → tie directly to plan upgrade or feature activation events
5. Customer conference (user conference/summit) → measure pipeline generated from customer attendees vs. non-attendees
6. Account-specific ABM campaigns for expansion → paid social, direct mail, or digital campaigns targeting new stakeholders within existing accounts

B. EXPANSION ATTRIBUTION MODEL
Use a two-model approach:

MODEL 1: MARKETING-INFLUENCED EXPANSION
- Definition: Any expansion opportunity where a marketing touch occurred within 120 days before opportunity creation
- Attribution window: 120 days (longer than new logo due to slower expansion buying cycles)
- Credit assignment: W-shaped model for expansion — 30% to first post-sale marketing touch, 30% to the touch closest to expansion opportunity creation, 30% to closed-won touch, 10% distributed across middle touches
- Report: Marketing-influenced expansion ARR as % of total expansion ARR (benchmark: 30-50% for mature customer marketing programs)

MODEL 2: MARKETING-SOURCED EXPANSION
- Definition: Expansion opportunities where the direct trigger was a marketing motion (e.g., customer clicked upgrade CTA in newsletter, or expansion discussion began after attending customer summit)
- Track via: UTM parameters on in-product upgrade flows + CSM logging expansion trigger in CRM opportunity notes
- Report separately from influenced to show direct marketing ROI

C. CONTROL GROUP METHODOLOGY
To prove marketing incrementality:
- Split customers with similar ERS scores into two groups: Group A receives proactive customer marketing, Group B receives only CS-led standard touches
- Compare after 6 months: expansion ARR per account, time to expansion, average expansion ACV
- This becomes your ROI proof point for customer marketing investment

SECTION 4: PREDICTIVE EXPANSION PRIORITIZATION

Build a propensity-to-expand model that scores all accounts and produces a weekly action list:

TOP EXPANSION TRIGGERS (rank by predictive power based on typical B2B SaaS patterns):

Tier 1 Triggers (Highest predictive value — act within 48 hours):
- Seat utilization crossed 80% threshold
- Customer submitted product feedback requesting a feature they'd need to upgrade to access
- Champion scheduled a call with AE or CSM without a pre-set agenda (indicates they want to discuss something)
- Pricing page visit by existing customer contact (especially VP/C-Suite)
- Customer posted in community asking about features in a higher tier

Tier 2 Triggers (High predictive value — act within 1 week):
- ERS jumped 15+ points in one week
- New department head added as CRM contact (potential new stakeholder/new use case)
- Customer referenced a competitor's product in support ticket or community post (comparison shopping signal)
- QBR showed >40% growth in usage metrics YoY
- Customer referred another company to you (satisfaction level correlates with expansion readiness)

Tier 3 Triggers (Moderate predictive value — route to nurture sequence):
- ERS between 50-65 with positive trend for 30 consecutive days
- Customer attended 2+ webinars or training sessions in last 60 days
- Contract renewal is 90+ days away but no expansion discussion initiated yet

EXPANSION PRIORITY SEGMENTATION (weekly output):
1. **HARVEST NOW** (ERS 80+, Tier 1 trigger active): CSM + AE joint outreach within 48 hours; specific expansion ask with pricing
2. **DEVELOP ACTIVELY** (ERS 60-79, Tier 2 trigger): CSM-led discovery conversations, expansion content delivery, exec alignment plays
3. **NURTURE FOR GROWTH** (ERS 40-59, positive trajectory): Marketing-led programs (webinars, feature announcements), quarterly CSM check-ins
4. **STABILIZE FIRST** (Red health, any ERS): CS-led recovery plays; hold all expansion outreach until health is Green

SECTION 5: EXPANSION REVENUE ANALYTICS DASHBOARD

Build a three-level reporting hierarchy for expansion ABM:

EXECUTIVE DASHBOARD (CMO/CRO/CEO, monthly):
- Net Revenue Retention (NRR) by segment and cohort
- Gross Revenue Retention (GRR) to distinguish expansion from churn offset
- Expansion ARR booked this month/quarter vs. target
- Expansion ARR by motion type (seat growth / module upsell / tier upgrade / subsidiary)
- Marketing-influenced expansion ARR % of total expansion
- Top 10 accounts by expansion ARR potential (ERS × estimated ARR)
- Expansion pipeline coverage ratio: pipeline ÷ quarterly target (target: ≥ 3:1)

PROGRAM MANAGER DASHBOARD (Customer Marketing / Demand Gen, weekly):
- ERS distribution across customer base (how many in each tier)
- Accounts that crossed key ERS thresholds this week
- Campaign performance: expansion pipeline influenced per campaign, cost per expansion opportunity influenced
- Marketing touch → expansion opportunity conversion rate by channel
- Trigger event volume: how many Tier 1 triggers fired this week and what % resulted in expansion outreach within SLA
- Content performance: which assets (case studies, ROI calculators, feature webinars) correlate with expansion decisions

ACCOUNT-LEVEL INTELLIGENCE (CSM/AE, per account):
- Current ERS with trend arrow (↑↓→) and score delta vs. 30 days ago
- Triggered signals this week with recommended play
- Product adoption heatmap: feature usage by user and department
- Whitespace summary: what they don't have that they should
- Expansion ARR potential (low/mid/high estimate)
- Next Best Action: specific, personalized action for CSM or AE to take in next 5 business days
- Marketing touches in last 90 days: what content/campaigns this account has engaged with

## Example Input/Output

**Input Example:**

Company: Meridian Ops (B2B SaaS — workflow automation and process intelligence platform)
Customer base: 380 customers across three tiers (Enterprise: 45, Mid-Market: 180, SMB: 155)
Products: Core (workflow builder), Analytics Add-on ($25K/yr), AI Module ($40K/yr), Enterprise Admin ($15K/yr)
Current NRR: 108% | Target: 118% by end of year
Expansion target: $4.2M in expansion ARR this fiscal year
Stack: Salesforce + Gainsight + Marketo + Amplitude
CS model: Enterprise has named CSMs (1:10 ratio); Mid-Market is pooled (1:40); SMB is tech-touch only

**Output Example:**

EXPANSION READINESS SCORE — SAMPLE ACCOUNT: "Hartwell Financial Group"

| Signal Category | Raw Score | Weight | Weighted Score |
|---|---|---|---|
| Usage Score (WAU up 34% MoM; 87% seat utilization; 4 integrations active) | 88/100 | 45% | 39.6 |
| Commercial Score (renewal in 74 days; ACV at 38% of ICP benchmark; previous expansion 8 months ago) | 72/100 | 30% | 21.6 |
| Engagement Score (CFO attended EBC last month; NPS: 67; 0 open critical tickets; G2 review submitted) | 91/100 | 25% | 22.8 |
| **Raw ERS** | | | **84.0 / 100** |
| Health Multiplier (Green health) | | | × 1.0 |
| **FINAL EXPANSION READINESS SCORE** | | | **84.0 — HARVEST NOW** |

**Trigger Events Active:**
- ✅ Seat utilization crossed 87% (Tier 1 trigger — 48-hour SLA for outreach)
- ✅ CFO Maria Chen visited pricing page on Tuesday (logged via Clearbit + Salesforce visitor tracking)
- ✅ Power user Jake Morales invited 3 colleagues from the Risk Management team (new department signal)

**Whitespace Summary:**
- Analytics Add-on: NOT purchased — 0% feature adoption (0 of 12 analytics features used); Risk Management team's use cases map directly to advanced analytics
- AI Module: NOT purchased — 2 support tickets in last 60 days requesting AI-powered suggestions (in-product feature flag shows 8 users activated AI trial)
- Estimated Expansion ARR: $65,000 (Analytics Add-on $25K + AI Module $40K)

**Next Best Action for CSM (Sarah Park):**
Schedule a 30-minute "Quarterly Impact Review" with Maria Chen (CFO) and Jake Morales (champion). Lead with: "Your Risk Management team is up and running — I want to show you how [Company] companies at your usage level are using our Analytics module to report on workflow ROI directly to the board." Close with a 60-day trial offer for the Analytics Add-on for the Risk team (6 users), converting to paid at renewal.

---

PROGRAM SUMMARY — MERIDIAN OPS EXPANSION PIPELINE (Current Snapshot):

| Tier | Accounts | Avg ERS | HARVEST NOW | Expansion Pipeline | Expansion ARR Won (QTD) |
|---|---|---|---|---|---|
| Enterprise (45) | 45 | 72 | 12 accounts | $2.4M | $680K |
| Mid-Market (180) | 180 | 58 | 31 accounts | $3.1M | $420K |
| SMB (155) | 155 | 41 | 8 accounts | $0.6M | $95K |
| **Total** | **380** | **57** | **51 accounts** | **$6.1M** | **$1.2M** |

Pipeline coverage: 6.1M ÷ $1.05M quarterly target = **5.8x coverage** (exceeds 3:1 minimum)

**Top Marketing-Influenced Expansion This Quarter:**
Customer Summit (Chicago) — 22 Enterprise/Mid-Market customers attended → 14 showed ERS increase of 15+ points within 30 days → 6 expansion opportunities created ($890K pipeline) → 3 closed-won ($310K ARR) — **Summit ROAS: 8.2x on $38K investment**

## Success Metrics

- **ERS accuracy:** Accounts scoring 75+ should convert to expansion opportunity at ≥ 2.5x the rate of accounts scoring below 50
- **Marketing attribution coverage:** ≥ 40% of expansion ARR should have a traceable marketing touch in the 120-day attribution window
- **Trigger-to-outreach SLA:** 100% of Tier 1 expansion triggers receive CS/AE outreach within 48 hours
- **Whitespace capture rate:** Track what % of identified whitespace opportunity is converted to contracted ARR within 12 months (benchmark: 15-25% for mature programs)
- **NRR impact:** Programs with full ERS implementation typically see NRR improvement of 8-15 percentage points within 12 months
- **Expansion pipeline coverage:** Maintain ≥ 3:1 expansion pipeline to quarterly target ratio at all times
- **Customer marketing ROI:** Customer marketing programs (webinars, EBCs, newsletters) should show ≥ 4x expansion pipeline ROI (pipeline influenced ÷ program cost)
- **Time-to-expansion acceleration:** Accounts receiving proactive expansion plays should show 25-35% faster expansion cycle vs. reactive accounts

## Related Prompts

- [AI-Powered ABM Account Intelligence & Revenue Attribution Engine](./AI-Powered-ABM-Account-Intelligence-&-Revenue-Attribution-Engine.md)
- [ABM Intent Data Activation & Buying Signal Prioritization Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [AI-Powered Net Revenue Retention & Expansion Revenue Intelligence Engine](../Customer-Lifetime-Value-Analytics/AI-Powered-Net-Revenue-Retention-&-Expansion-Revenue-Intelligence-Engine.md)
- [Feature Adoption Stickiness & Retention Intelligence Engine](../Product-Analytics-&-Activation/Feature-Adoption-Stickiness-&-Retention-Intelligence-Engine.md)

## Integration Tips

- **Gainsight:** Build the ERS as a Scorecard in Gainsight using the three-layer model; set up Calls to Action (CTAs) that auto-assign to CSMs when accounts enter HARVEST NOW tier; use Timeline entries to log marketing touches so attribution is visible to CS teams; connect Gainsight to Salesforce so ERS and CTAs sync to Opportunity records
- **Salesforce:** Create a custom Expansion Readiness Score field on the Account object; build an "Expansion Opportunity" record type separate from new logo opportunities for clean attribution tracking; use Flow to auto-create tasks for CSMs/AEs when Tier 1 triggers fire; build a custom "Expansion ABM Dashboard" showing ERS by segment, pipeline, and whitespace
- **Marketo / HubSpot:** Tag all customer communications with a "Customer Marketing" campaign tag to enable clean attribution reporting; build separate nurture tracks for DEVELOP ACTIVELY and NURTURE FOR GROWTH segments; use dynamic content to personalize emails based on which products the customer does NOT yet use
- **Amplitude / Pendo / Mixpanel:** Create product analytics dashboards that feed usage signals directly to Salesforce or Gainsight via API; set up real-time alerts for seat utilization thresholds and feature adoption milestones; use Pendo in-app guides to surface upgrade prompts exactly when users hit usage limits
- **Slack:** Set up a #expansion-signals Slack channel that receives Zapier/webhook alerts for all Tier 1 trigger events; automatically tag the relevant CSM and AE; include the account name, trigger, ERS score, and recommended next action in the message to reduce time-to-response

## Troubleshooting

**Problem:** Expansion ERS scores look high across the board but actual expansion conversions are low.
**Solution:** The most common cause is that usage signals (Layer 1) are dominating the score without being validated against commercial readiness. Add a mandatory "Commercial Gate": no account can enter HARVEST NOW unless it also scores ≥ 50 on the Commercial layer (Layer 2). Usage growth is necessary but not sufficient — you also need budget availability and contract flexibility. Additionally, review whether your Health Multiplier is being applied correctly: Red health accounts should never appear in HARVEST NOW regardless of usage signals.

**Problem:** CS team is not acting on expansion alerts within SLA — signals are firing but pipeline isn't growing.
**Solution:** This is a change management problem, not an analytics problem. Two fixes: (1) integrate alerts directly into the CS workflow tool (Gainsight CTA, Salesforce task, Slack message) rather than expecting CSMs to check a dashboard, and (2) add expansion conversion rate to CSM performance scorecards so there's personal accountability. Run a monthly "Expansion Office Hours" session where CS, Sales, and Marketing review the top 10 HARVEST NOW accounts together and agree on plays — joint ownership creates joint accountability.

**Problem:** Marketing cannot get credit for expansion revenue because CS teams close deals without logging marketing touches in CRM.
**Solution:** Implement a mandatory "Expansion Influence Capture" step in the Salesforce expansion opportunity stage — before an opportunity can move to Closed Won, the CSM must answer: "Were any marketing programs (webinars, emails, events, in-product campaigns) part of this customer's expansion decision?" Add this as a required picklist + notes field. Also ensure all marketing UTMs and event attendance are auto-logged to the Account in Salesforce via your MAP integration so the data exists even if the CSM doesn't manually log it.

## Version History
- v1.0: Initial creation (auto-generated)
