# AI-Powered B2B SaaS Net Revenue Retention (NRR) Marketing Analytics & Expansion Revenue Attribution Intelligence Engine - Build an AI Agent That Decomposes Your NRR Waterfall, Attributes Marketing's Contribution to Expansion Revenue, and Generates Compounding Retention Playbooks

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** nrr, net-revenue-retention, expansion-revenue, churn-prevention, marketing-attribution, b2b-saas, revenue-analytics, customer-lifetime-value

## Overview

This prompt engineers an AI system that takes your NRR waterfall (starting ARR + expansion - contraction - churn = ending ARR) and reverse-engineers exactly how much of each component marketing-owned activities are responsible for — then builds a closed-loop feedback system to optimize where to invest next. Use it when your board is asking "what did marketing do for NRR this quarter?" and you can't answer, when your expansion pipeline is underpowered, or when you want to build the analytics infrastructure to prove marketing's contribution to the most important SaaS metric investors track.

## Quick Copy-Paste Version

You are a senior B2B SaaS revenue analytics architect specializing in net revenue retention (NRR) measurement and marketing attribution. Build me a complete NRR marketing analytics system for [Your Company].

Our current metrics:
- Gross Retention Rate: [e.g., 87%]
- Net Revenue Retention: [e.g., 108%]
- Starting ARR: [e.g., $24M]
- Expansion Revenue (upsell + cross-sell): [e.g., $4.2M]
- Contraction (downsell): [e.g., $800K]
- Churned ARR: [e.g., $3.1M]
- Marketing's tracked expansion pipeline: [e.g., $0 — we don't measure it]

Step 1 — NRR WATERFALL DECOMPOSITION
Decompose our NRR into its four components and calculate:
- Expansion Rate: expansion ARR / beginning ARR
- Contraction Rate: contraction ARR / beginning ARR
- Churn Rate: churned ARR / beginning ARR
- NRR: (beginning ARR + expansion - contraction - churn) / beginning ARR

For each component, identify the top 3 marketing levers that move that number, with specific examples of campaigns or programs that affect each.

Step 2 — MARKETING ATTRIBUTION FRAMEWORK
Build an attribution model that credits marketing activities with expansion revenue impact across these motion types:
a) Campaign-originated expansion: customer attended marketing event → AE added expansion opportunity (direct attribution)
b) Content-influenced expansion: customer consumed case study or feature content before expansion discussion (first/last-touch)
c) Community/advocacy-originated: customer shared with peer who became expansion champion (network attribution)
d) In-product/in-app marketing: in-app notification or email triggered upgrade (in-product attribution)
e) Churn prevention save: marketing intervention kept an account that was canceling (retention attribution)

For each motion type, define: data capture method, attribution window, revenue credit percentage, and the tool/system that tracks it.

Step 3 — EXPANSION REVENUE ANALYTICS ENGINE
Design an analytics model that:
- Identifies which customer cohorts have the highest expansion propensity by segment, vertical, and ACV tier
- Surfaces "expansion-ready" signals: which behaviors predict a customer is 60-90 days from being ready for an upsell conversation
- Calculates marketing's contribution to expansion pipeline by motion type (quarterly and rolling 12-month)
- Benchmarks our expansion rate against SaaS industry medians by ARR band

Step 4 — MARKETING-LED NRR IMPROVEMENT PLAYBOOK
Based on the waterfall analysis, build a 90-day marketing-led NRR improvement playbook with:
- The highest-leverage intervention (which waterfall component has worst performance and best marketing fix)
- A campaign calendar showing which programs to run, in which order, for which segments
- The MQL-to-expansion and save-to-churn-prevented conversion metrics to track
- The financial model showing what moving each component by 2-5 percentage points means in ARR impact

Output the complete analytics framework and 90-day playbook as a board-ready document.

## Advanced Customizable Version

ROLE: You are a Revenue Analytics Architect with 15 years of experience in B2B SaaS marketing analytics and revenue operations. You specialize in building NRR attribution frameworks that give CMOs defensible credit for expansion revenue, and you understand the nuances of multi-touch attribution, cohort analysis, and SaaS unit economics at the CFO level.

COMPANY CONTEXT:
- Company: [Your company name and product category]
- Business model: [Seat-based / usage-based / land-and-expand / platform licensing]
- Total customers: [Number of active accounts]
- Customer segments: [Enterprise / Mid-Market / SMB — specify ACV ranges and customer count per tier]
- Average contract term: [Monthly / Annual / Multi-year — and typical expansion deal size]
- Key expansion products/SKUs: [List the 2-4 things customers typically expand into]
- CRM: [Salesforce / HubSpot / other] | CS Platform: [Gainsight / Totango / ChurnZero / other]
- Product analytics tool: [Amplitude / Mixpanel / Heap / Pendo / none]
- Marketing automation: [Marketo / HubSpot / Eloqua / other]

CURRENT NRR BASELINE:
- Beginning ARR (last 12 months): [Amount]
- Ending ARR: [Amount]
- Gross Retention Rate: [%] | NRR: [%]
- Expansion ARR (upsell + cross-sell): [Amount]
- Contraction ARR (downgrades + seat reductions): [Amount]
- Churned ARR (logo churn × average ACV): [Amount]
- Marketing-attributed expansion: [Amount — or "unmeasured" if unknown]
- Marketing-attributed saves: [Amount — or "unmeasured" if unknown]

STRATEGIC CONTEXT:
- Why NRR matters now: [Board pressure / investor metrics / growth efficiency focus / other]
- Current marketing investment in retention/expansion: [Budget amount or % of total marketing budget]
- Biggest NRR problem: [High logo churn / low expansion rate / high contraction / all three]
- Next board/investor review: [Date — impacts urgency and reporting requirements]

OBJECTIVE: Build a comprehensive AI-powered NRR marketing analytics engine that delivers:

MODULE 1: NRR DIAGNOSTIC INTELLIGENCE
Perform a complete NRR waterfall analysis:
a) Calculate each NRR component as a rate and benchmark against industry data — provide specific SaaS benchmarks by ARR band using OpenView, Bessemer, or SaaStr data as reference points
b) Identify the single highest-impact NRR improvement opportunity based on where we are furthest from benchmark
c) Build a "NRR sensitivity table" showing what a 3, 5, and 10 percentage point improvement in each component means in ending ARR impact
d) Decompose expansion by motion (self-serve upgrade, marketing-assisted, sales-led, partner-referred) and by product/SKU
e) Identify the customer cohorts with the best and worst NRR performance by: acquisition cohort month, acquisition channel, ICP fit score, initial ACV tier, industry vertical

MODULE 2: EXPANSION REVENUE ATTRIBUTION FRAMEWORK
Build a rigorous, CFO-defensible attribution model:

2a) Attribution Methodology Selection
For each expansion motion type, recommend and justify the attribution methodology:
- Upsell to marketing email sequence → first-touch + last-touch split (explain why)
- Expansion after executive event attendance → single-touch (explain why)
- Upgrade driven by in-app message → in-product attribution (define data requirements)
- Referral-sourced expansion → network attribution (define rules)
- Account-penetration cross-sell → account-level vs. contact-level attribution (resolve the tension)

2b) Data Infrastructure Requirements
For each attribution model to work end-to-end, specify:
- The exact data fields needed in CRM (Salesforce opportunity + contact fields)
- The campaign tracking taxonomy (UTM structure, campaign naming conventions)
- The marketing-to-expansion handoff workflow (when does an expansion opportunity get a marketing campaign tag?)
- The Salesforce/HubSpot report or dashboard that captures this data automatically

2c) Marketing Expansion Pipeline Definition
Define a "Marketing Expansion Pipeline" metric:
- Which expansion opportunities qualify as "marketing-influenced" vs. "marketing-sourced"
- The minimum attribution evidence required for credit (to prevent gaming)
- The time window for attribution credit (e.g., 90-day look-back)
- How to handle "self-generated" renewals vs. marketing-assisted renewals

MODULE 3: EXPANSION PROPENSITY ANALYTICS ENGINE

3a) Expansion-Ready Customer Identification
Build a predictive model that identifies which customers are "expansion-ready" in the next 90 days. Define the behavioral signals that predict readiness with example weights:
- Product signal: greater than 80% feature adoption in primary module (weight: 25%)
- Engagement signal: Champion engagement score in top quartile (weight: 20%)
- Business outcome signal: Customer-reported ROI milestone achieved (weight: 20%)
- Growth signal: Headcount or company growth detected via intent data sources (weight: 15%)
- Timing signal: 9-12 months post-onboarding (weight: 10%)
- Relationship signal: Executive sponsor is actively engaged (weight: 10%)

Assign a composite score (0-100) and define the threshold for "expansion conversation ready" (e.g., above 65 triggers SDR or AE outreach with marketing content package).

3b) Segment-Level Expansion Rate Analysis
Build a cohort analysis that shows expansion rate by:
- ICP tier (Tier 1 / 2 / 3 customers)
- Acquisition channel (paid search / ABM / content / outbound / referral)
- Onboarding type (self-serve / white-glove / partner-led)
- Product seat usage at 90 days (under 50% / 50-80% / over 80%)
- Initial deal size (SMB under $10K ACV / Mid-Market $10-50K / Enterprise over $50K)

For each segment combination, show: expansion rate, time-to-first-expansion, average expansion ACV, and the recommended marketing program.

3c) Anti-Expansion Signal Detection
Identify the 5 signals that predict a customer will NOT expand (and will likely contract):
- Signal, threshold, lead time before contraction typically occurs
- Marketing intervention playbook for each signal
- Expected save rate and ROI of each intervention

MODULE 4: CHURN PREVENTION REVENUE ATTRIBUTION

4a) Marketing-Saved ARR Calculation
Build the calculation framework for "Marketing-Saved ARR":
- Define what constitutes a "churn risk event" (specific triggers)
- Define what constitutes a "save" (criteria for crediting marketing)
- The attribution period (how far back can marketing claim credit for a save?)
- The financial model: at what confidence threshold does saved ARR count in the board deck?

4b) Churn Prevention Campaign ROI Model
For each marketing churn-prevention program, build the ROI calculation:
- Risk-tier email nurture sequences: cost ($), accounts touched, save rate (%), ARR saved ($), ROI
- Executive re-engagement campaigns: cost, save rate, ARR saved, ROI
- Value realization content programs: cost, save rate, ARR saved, ROI
- Community and event re-engagement: cost, save rate, ARR saved, ROI

Build the formula: Marketing Churn Prevention ROI = (ARR Saved × Gross Margin × Customer LTV Multiple) / Campaign Cost

MODULE 5: CMO-BOARD NRR MARKETING SCORECARD

5a) Monthly NRR Marketing Dashboard — define 10 specific KPIs with formulas:
1. Marketing-Attributed Expansion ARR (month and rolling 12-month)
2. Marketing Expansion Pipeline Coverage (% of expansion ARR target covered by marketing-influenced opportunities)
3. Churn Prevention Save Rate by Risk Tier
4. Expansion-Ready Accounts Identified vs. Converted
5. Marketing-Influenced NRR (what would NRR be without marketing's contribution?)
6. Cost Per Dollar of Expansion ARR Attributed to Marketing
7. Content-to-Expansion Conversion Rate (customers who consumed retention content and subsequently expanded)
8. Time-to-Expansion by Marketing Program Type
9. Expansion Velocity (average days from expansion-ready signal to closed expansion deal)
10. Marketing's Contribution to NRR Improvement vs. Prior Period

5b) Quarterly Board-Ready NRR Marketing Report Structure
Provide the exact narrative structure, 5 required charts, and the "headline metrics" a CMO should present to the board to demonstrate marketing's NRR contribution.

MODULE 6: 90-DAY NRR IMPROVEMENT PLAYBOOK

Based on the diagnostic, build a phased 90-day plan:

Weeks 1-2: Foundation
- Set up attribution tracking in CRM and marketing automation
- Define expansion-ready signal threshold and build the scoring model
- Identify top 20% expansion-ready accounts with marketing outreach plan

Weeks 3-6: Activation
- Launch expansion-ready nurture sequences (email + LinkedIn + in-app)
- Implement churn risk intervention campaigns for Red and Orange tier accounts
- Begin value realization content distribution to key accounts by segment

Weeks 7-10: Optimization
- Review conversion rates by segment and adjust messaging
- A/B test subject lines and content angles in expansion sequences
- Refine the propensity model with actual conversion data

Weeks 11-13: Measurement and Reporting
- Publish first Marketing NRR Attribution Report to CRO and CFO
- Present 90-day results: expansion pipeline influenced, saves attributed, NRR impact
- Build the H2 investment case for marketing's expansion budget

CONSTRAINTS:
- All attribution models must pass CFO review — no inflated or double-counted numbers
- Each recommendation must specify the exact system or tool where data lives and how to extract it
- Prioritize initiatives by: (1) time-to-revenue impact, (2) data availability, (3) cost to implement
- Every metric must have a formula, not just a definition
- Include industry benchmark data for each NRR component to contextualize performance

OUTPUT FORMAT:
Deliver in 6 labeled modules matching the structure above. Each module must be actionable within 30 days with an existing martech stack. Include a master KPI tracking table at the end with: metric name, formula, data source, measurement frequency, and owner (Marketing / RevOps / CS).

## Example Input/Output

**Example Input:**
- Company: Flowlytix (B2B SaaS project intelligence platform for enterprise engineering teams)
- ACV range: $35,000–$280,000 | Average: $72,000
- Beginning ARR: $38M | Ending ARR: $41.8M | NRR: 110%
- Expansion ARR: $5.2M (seat expansion 60% / module upsell 40%)
- Contraction: $620K (seat reduction after layoffs at 3 enterprise accounts)
- Churned ARR: $780K (2 logos — one acquisition, one competitive displacement)
- Marketing-attributed expansion: "We think maybe $1.5M but we can't prove it"
- CS Platform: Gainsight | CRM: Salesforce | MAP: Marketo | Product analytics: Amplitude

**Example Output (Module 1 excerpt):**

**NRR Waterfall Diagnostic — Flowlytix**

| Component | Flowlytix | SaaS Benchmark ($25M–$50M ARR) | Gap |
|---|---|---|---|
| Gross Retention | 97.9% | 88–92% | +6pp (excellent) |
| Expansion Rate | 13.7% | 18–22% | -6pp (opportunity) |
| Contraction Rate | 1.6% | 2–3% | +1pp (better than median) |
| NRR | 110% | 110–120% | At median |

**Key Finding:** Flowlytix's NRR problem is not churn — it's expansion underperformance. At $25-50M ARR, best-in-class SaaS companies achieve 18-22% expansion rates. Flowlytix is at 13.7%, suggesting $1.6-$3.1M in unrealized expansion ARR this year.

**Primary Root Cause (Expansion Gap Analysis):**
- Seat expansion is limited to organic hiring growth signals — no marketing-driven seat-expansion campaign exists
- Module upsell is entirely AE-driven with no marketing content or nurture for the Engineering VP persona
- No "expansion-ready" score exists — CS flags accounts manually based on QBR conversations

**NRR Sensitivity Table:**
| Expansion Rate Improvement | ARR Impact |
|---|---|
| +3pp (to 16.7%) | +$1.14M additional ARR |
| +5pp (to 18.7%) | +$1.90M additional ARR |
| +8pp (to 21.7%) | +$3.04M additional ARR |

**Highest-Leverage Action:** Build a marketing-led expansion nurture program targeting "Module 2 Expansion" (project forecasting add-on) for Engineering VPs at accounts with greater than 70% utilization of Module 1. Estimated pipeline impact in 90 days: $2.2M in expansion opportunities.

**Module 2 — Expansion Attribution Setup (Salesforce + Marketo):**

Flowlytix needs 4 new Salesforce fields on the Opportunity object:
1. `Marketing_Campaign_Source__c` (picklist: tracks last marketing touchpoint before expansion opportunity was created)
2. `Marketing_Influenced_Flag__c` (checkbox: auto-set if contact had marketing engagement in the 90 days prior to opportunity creation)
3. `Expansion_Signal_Score__c` (number: pulled from Amplitude via Zapier when propensity score exceeds 65)
4. `Churn_Risk_at_Close__c` (checkbox: was this account in Orange or Red risk tier before expanding?)

Marketo program configuration:
- Create `[Expansion] Engineering VP Module 2 Nurture` program
- Enrollment trigger: Amplitude webhook fires when feature utilization exceeds 75% AND Gainsight health score is above 70
- 6-email sequence over 45 days, CTA = "See how teams like yours expanded to Module 2"
- Opportunity creation trigger: If contact books a demo from email click, Salesforce opportunity is auto-created as Type = "Marketing-Sourced Expansion"

## Success Metrics

A high-quality output from this prompt will produce:

1. **Complete NRR Waterfall with Benchmarks** — every component calculated with industry data comparison, not just your numbers in isolation
2. **Attribution Model with Tool-Level Implementation** — specific Salesforce fields, Marketo program structures, and dashboard configurations, not generic methodology descriptions
3. **Expansion Propensity Score** — a working scoring model with defined thresholds and exact behavioral signals with weights
4. **Financial Impact Model** — the dollar value of improving each NRR component by 3-10 percentage points in ARR terms
5. **90-Day Playbook** — week-by-week actions with owners, systems, and expected conversion rates at each stage
6. **Board-Ready Metrics** — 10 KPIs with formulas that survive CFO scrutiny and give marketing defensible credit for NRR contribution

**Red Flags in Output (Regenerate If):**
- Attribution model does not specify exact CRM fields or system-level implementation steps
- Benchmarks are vague ("industry standard") rather than specific (should cite a named source)
- The 90-day playbook lacks timeline, owners, or expected conversion metrics at each stage
- NRR components are defined but not calculated with explicit formulas

## Related Prompts

- `../../05_Analytics-&-Performance/Churn-Prevention-&-Retention-Analytics/AI-Powered-B2B-SaaS-Churn-Signal-Detection-Matrix-&-Marketing-Intervention-Architecture-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Churn-Prevention-&-Retention-Analytics/AI-Powered-B2B-SaaS-Predictive-Churn-Intelligence-&-Marketing-Led-Retention-Revenue-Recovery-Analytics-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Customer-Marketing-Expansion-Revenue-Campaign-Architecture-&-Cross-Sell-Upsell-Pipeline-Intelligence-Engine.md`
- `../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-B2B-SaaS-ARR-Bridge-Analysis-&-Marketing-Contribution-Attribution-Intelligence-Engine.md`

## Integration Tips

**Salesforce:**
- Build an "NRR Marketing Dashboard" using the Report Type: Campaigns with Influenced Opportunities, filtered to Opportunity Type = "Expansion" or "Renewal"
- Set up a Salesforce Flow to auto-populate `Marketing_Influenced_Flag__c` on any expansion opportunity where a related contact has a CampaignMember record created in the past 90 days
- Create a Campaign ROI report segmented by Expansion vs. Churn Prevention campaign type to show marketing's NRR contribution in one view

**Gainsight:**
- Use Journey Orchestrator to trigger Marketo enrollment when a customer's Health Score drops below your risk threshold OR when usage signals cross your expansion-readiness threshold — the same platform handles both retention and expansion
- Set up a Cockpit Success Plan called "Expansion-Ready: Marketing Handoff" that fires when propensity score exceeds 65, notifying the AE with the attached marketing content package and suggested talk track

**Amplitude / Mixpanel:**
- Build a funnel report: Feature Adoption → Expansion-Ready Signal → Expansion Opportunity Created → Closed Won, to measure the full conversion chain
- Create behavioral cohorts (e.g., "Used 4 or more features in last 30 days") and sync to HubSpot or Marketo via native integration for automatic enrollment in expansion nurture sequences

**HubSpot (alternative CRM/MAP):**
- Use HubSpot's Revenue Attribution report (Enterprise tier) to track which marketing assets were last-touched before expansion deals closed
- Create a Workflow: If Contact viewed an "Upgrade" or "Expansion" page AND is associated with a customer company AND no open Expansion deal exists → create an Expansion task assigned to the account AE

**Google Sheets / Looker Studio:**
- Build a monthly NRR Waterfall chart by pulling beginning ARR, expansion, contraction, and churn from Salesforce reports into Sheets via the Salesforce connector
- Create a "Marketing NRR Impact" tab that calculates marketing-attributed expansion plus marketing-saved ARR and compares to prior quarter with percentage change

**Zapier / Make.com:**
- Webhook trigger: When Amplitude sends an expansion-ready signal (score above 65) → Create a Salesforce task for the AE with pre-filled account context → Simultaneously enroll the contact in Marketo expansion nurture sequence
- Automate the monthly NRR attribution report: Salesforce scheduled report exports → Google Sheets → Slack notification to CRO and CMO with the 10 headline KPIs

## Troubleshooting

**Problem: "We can't attribute expansion revenue to marketing because AEs close all expansion deals directly and don't log marketing touchpoints."**
Fix: Switch from sourced attribution to influenced attribution. You do not need to own the deal — you need to prove that a touchpoint occurred. Set a 90-day look-back window: if any marketing campaign touchpoint existed on a contact record before the expansion opportunity was created, mark the opportunity as "Marketing Influenced." This is standard SaaS attribution practice and does not conflict with sales credit. Document the methodology in a one-page "Revenue Attribution Policy," get CRO and CFO sign-off, then automate it in Salesforce Flow so it never depends on AE manual logging.

**Problem: "Our Gainsight health score doesn't correlate with actual expansion — high-health accounts aren't expanding and some low-health accounts are."**
Fix: Your health score was designed to predict retention risk, not expansion propensity — they measure different things and require separate models. Retention health weights relationship and satisfaction signals (NPS, executive engagement, support ticket volume). Expansion propensity should weight product utilization depth, business growth signals, and time-since-onboarding. Run a lookback analysis on your last 24 months of expansion deals and identify which signals at T-90 days actually predicted the expansion. Build your propensity model from observed data, not assumptions.

**Problem: "The CFO rejected our marketing NRR attribution numbers as inflated — now leadership won't trust the metric."**
Fix: Apply the "conservative attribution test" to rebuild credibility: only count an expansion as marketing-influenced if (1) the contact had two or more marketing touchpoints in the 90 days before opportunity creation AND (2) at least one touchpoint was specifically about the expanded product or use case, not general brand content. Never count newsletter opens or event attendance unrelated to the expansion product. Present the CFO with a side-by-side showing "liberal attribution" vs. "conservative attribution" with your methodology for each — then commit to the conservative number. Credibility is worth more than a larger attributed number.

## Version History
- v1.0: Initial creation (auto-generated)
