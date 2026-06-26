# AI-Powered B2B SaaS MQL-to-MQA Transformation & Account-Based Pipeline Qualification Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** account-based-marketing, MQA, lead-qualification, demand-generation, pipeline-quality, marketing-operations, sales-alignment, ABM, lead-scoring, revenue-operations

## Overview
Redesigns your entire lead qualification infrastructure from individual MQL scoring to Marketing Qualified Account (MQA) scoring — transforming how marketing generates, qualifies, and hands off pipeline to sales. Use this when MQL volume is high but sales acceptance rates are below 40%, when sales and marketing are chronically misaligned on lead quality, or when you are scaling an ABM motion and need account-level qualification signals that match how enterprise buying committees actually buy.

## Quick Copy-Paste Version

You are a B2B SaaS demand generation and marketing operations expert specializing in account-based pipeline qualification. Redesign the company's qualification framework from MQL to MQA using the inputs below.

COMPANY CONTEXT:
- Company: [Company name and product category]
- Average deal size: [$X — enterprise / mid-market / SMB breakdown if segmented]
- Average sales cycle: [X days]
- Current MQL monthly volume: [X MQLs per month]
- Current MQL-to-SQL acceptance rate: [X% — healthy benchmark: 35–55%]
- Current pipeline coverage ratio: [X:1 — target: 3–5x open quota]
- Top ICP segments (2–3): [Industry, company size, tech stack, geography]
- CRM: [Salesforce / HubSpot / other]
- MAP: [Marketo / HubSpot / Pardot / other]
- Current MQL definition: [Describe current lead scoring model and threshold]
- Sales team feedback on lead quality: [What sales says about the problem]

TRANSFORMATION REQUIRED — produce all seven sections:

1. MQA CRITERIA FRAMEWORK: Define which signals — firmographic fit, buyer intent data, product or trial engagement, behavioral engagement, and relationship warmth — must collectively qualify an account as marketing-ready for sales engagement. Specify what "enough" looks like at each threshold.

2. ACCOUNT SCORING MODEL: Build a weighted composite account score (0–100) using these signal categories with recommended default weights: ICP firmographic fit (30%), behavioral engagement depth (25%), third-party intent signal strength (20%), product or trial engagement (15%), relationship warmth / champion signals (10%). Define specific scoring rules, point values, and decay logic for each signal.

3. ACCOUNT TIER ACTIVATION PLAYBOOK: Create three MQA tiers — Hot (score 70–100), Warm (50–69), Developing (30–49) — and specify the exact sales action, marketing play, SLA, and routing logic for each tier. Hot accounts get immediate AE outreach within 4 hours. Warm accounts enter targeted air-cover plus SDR sequence. Developing accounts stay in automated nurture with intent monitoring.

4. CRM IMPLEMENTATION BLUEPRINT: Define the exact Salesforce or HubSpot fields, scoring workflows, and alert triggers needed to operationalize the MQA model. Include field names (e.g., "MQA_Score__c", "MQA_Tier__c", "Last_Intent_Signal_Date__c"), automation rule logic, and assignment rules.

5. SALES ALIGNMENT PROTOCOL: Draft the MQA acceptance SLA, feedback loop cadence, and lead quality disagreement escalation process. Include the one-page MQA definition document sales must sign off on, and the bi-weekly pipeline review agenda item for MQA quality calibration.

6. MEASUREMENT FRAMEWORK: Define the 8 weekly KPIs to track MQA program health: MQA volume by tier, MQA-to-opportunity conversion rate by tier, MQA-sourced pipeline as % of total pipeline, MQA acceptance rate by sales segment, average deal size from MQA-sourced vs. MQL-sourced pipeline, average MQA-to-close time vs. baseline, cost per MQA vs. cost per MQL, and pipeline coverage ratio from MQA channel.

7. 90-DAY ROLLOUT PLAN: Phase 1 (Days 1–30): Finalize scoring model, align with sales, and configure CRM fields. Phase 2 (Days 31–60): Implement scoring automation, backfill account scores on existing CRM data, and pilot with one sales segment. Phase 3 (Days 61–90): Full rollout, sunset MQL handoff, and publish first MQA performance report to leadership.

Format output as a structured transformation blueprint with specific scoring weights, field names, threshold values, workflow logic, and SLA language. Every recommendation must be immediately executable without additional research.

## Advanced Customizable Version

**ROLE:** You are a VP of Demand Generation and Revenue Operations with 15 years of experience building account-based marketing and qualification programs at B2B SaaS companies ranging from Series B ($10M ARR) to post-IPO ($500M+ ARR). You understand deeply why MQL-based programs break at scale: sales inherits a mix of individual contacts from large enterprise accounts that are not ready to buy, small companies that will never close, and champions with no budget authority — making MQL volume a vanity metric rather than a leading revenue indicator. You have successfully led MQL-to-MQA transitions at three companies, each resulting in a 40–60% improvement in MQL-to-opportunity conversion rates within 90 days. You speak fluent RevOps, and you know how to build scoring models in Salesforce and Marketo that sales actually trusts.

---

**CONTEXT:**

Company overview: [Company name, product category, primary use case]
Business model: [B2B SaaS — describe deal motion: PLG, sales-led, hybrid; describe primary buyer title and department]
Revenue target (current FY): [$X — new logo + expansion breakdown]
Sales structure: [Number of AEs by segment, number of SDRs, segments served: Enterprise / MM / SMB]
Marketing-sourced pipeline target: [X% of total pipeline expected from marketing]
Current attribution model: [First-touch / last-touch / multi-touch / no model]
Stack: CRM [Salesforce / HubSpot], MAP [Marketo / HubSpot / Pardot], Intent data [Bombora / G2 Buyer Intent / 6sense / Demandbase / none], Enrichment [Clearbit / ZoomInfo / Apollo / none]

---

**CURRENT STATE DIAGNOSIS:**

MQL Performance (last 90 days):
- Total MQL volume per month: [X]
- MQL-to-SQL (sales accepted) rate: [X% — if below 40%, this is the core problem]
- SQL-to-Opportunity rate: [X%]
- MQL-sourced opportunity-to-close rate: [X%]
- Average MQL-sourced deal size: [$X]
- Median time from MQL to closed won: [X days]
- Top 3 MQL rejection reasons from sales: [e.g., "wrong company size," "no budget," "not in buying cycle"]
- Current MQL scoring model: [Describe current behavioral and demographic scoring — what actions score points, current threshold to become MQL]
- Current MQL definition (formal): [Paste exact definition from SLA or marketing wiki]

ICP & Account Intelligence:
- Defined ICP: [Company size range, industries, tech stack must-haves, geographic focus, revenue range]
- Current ICP match rate of MQLs: [X% — what % of MQLs come from companies that match ICP firmographics]
- Intent data currently used (if any): [Source + signals monitored]
- Product usage signals available: [Free trial data, freemium usage, product telemetry — describe what's captured]
- Account-level engagement data: [Can you currently aggregate contact-level activity to account-level in CRM? Yes/No]

Sales Feedback (critical for alignment):
- Primary sales complaint about MQL quality: [Be specific — "Enterprise AEs refuse to work MQLs from SMB companies that scored high on our old model"]
- Sales average MQL follow-up time (current): [X hours — target: <4 hours for hot accounts]
- MQL rejection/recycle rate: [X% — healthy: <25%]
- Sales preference for account coverage: [How many contacts per account do AEs typically want before engaging?]

---

**MQA FRAMEWORK DESIGN — FULL BUILD:**

**Section 1: ICP Firmographic Fit Scoring (30 points max)**

Design a 0–30 point firmographic fit score for accounts based on:
- Company size (employee count or ARR if B2B SaaS) — define point tiers: [Perfect fit: 25–30 pts / Good fit: 15–24 pts / Marginal fit: 5–14 pts / Disqualified: 0]
- Industry vertical match — tier the ICP verticals: [Tier 1 industry: 15 pts / Tier 2: 10 pts / Tier 3: 5 pts / Out of ICP: 0]
- Tech stack signals from technographic data: [Required tech in stack = 10 pts / Adjacent tech = 5 pts / Competing tech = −5 pts]
- Geography match: [Primary markets: 5 pts / Secondary markets: 2 pts / Non-target: 0]
- Funding stage or financial profile: [Well-funded / PE-backed / public = 5 pts / Bootstrap with right size = 3 pts]

Scoring threshold guidance:
- Firmographic score ≥ 22: Account is ICP-confirmed — all behavioral signals count toward MQA
- Firmographic score 12–21: Account is ICP-adjacent — behavioral signals count at 50% weight
- Firmographic score < 12: Account is out of ICP — behavioral signals do not trigger MQA; nurture only

**Section 2: Behavioral Engagement Depth Scoring (25 points max)**

Design account-level behavioral scoring by aggregating all contact-level activities within the account over the last 90 days. Weight recency (last 14 days = 1.5x multiplier) and depth (multiple unique contacts engaged = buying committee multiplier of 1.25x for 3+ contacts, 1.5x for 5+ contacts).

High-value behavioral signals (8–10 pts per unique action):
- Pricing page view: [8 pts — strong purchase intent]
- ROI calculator or TCO tool completion: [10 pts — very strong buying signal]
- Competitive comparison page view: [9 pts — in active evaluation]
- Demo request or trial sign-up: [10 pts — highest intent action]
- Case study download (3+ downloads = buying committee research signal): [7 pts each]
- Webinar attendance (live, not recording): [8 pts]
- Contact with Sales or SDR (email reply, call answered): [9 pts per contact engaged]

Mid-value behavioral signals (3–6 pts per action):
- Blog post reads (3+ in 30 days): [3 pts]
- Email open + click sequence (3+ clicks in 30 days): [4 pts]
- Product page or feature page views (3+ unique pages): [5 pts]
- Resource center visit: [3 pts]
- Social engagement (LinkedIn company follow, executive connection): [3 pts]

Low-value signals (1–2 pts):
- Email opens only: [1 pt]
- Homepage single visit: [1 pt]
- Organic search landing without further engagement: [1 pt]

Buying committee depth multiplier: If 3+ unique contacts from the same account have scored behavioral points, apply 1.25x multiplier to total behavioral score. If 5+ contacts, apply 1.5x multiplier. This rewards accounts with deep multi-stakeholder engagement — the pattern that most reliably predicts enterprise deal success.

Signal decay: Apply 50% score decay to any behavioral signal older than 45 days and 0% credit for signals older than 90 days. This ensures the MQA score reflects active buying cycles, not historical interest.

**Section 3: Third-Party Intent Signal Strength (20 points max)**

Score accounts based on intent data from external sources (Bombora, G2 Buyer Intent, 6sense, TechTarget, etc.):
- Surge score on 3+ high-relevance topics (Bombora): [15–20 pts based on surge intensity]
- G2 Buyer Intent — account viewed competitor profiles: [10–15 pts depending on # of competitor profiles viewed]
- 6sense buying stage prediction (Decision or Purchase stage): [18–20 pts]
- 6sense In-Market or Consideration stage: [8–12 pts]
- TechTarget intent activity on relevant content: [8–12 pts]
- Review site research activity (any platform): [5–10 pts depending on recency and depth]

Intent signal context rule: Intent signals without firmographic fit are noise. An out-of-ICP account showing intent should trigger an automated email sequence only — never an SDR call. This rule prevents sales from wasting time on unqualifiable accounts showing research activity.

**Section 4: Product or Trial Engagement Signals (15 points max)**

For companies with PLG, freemium, or trial motion, product signals are the highest-confidence buying indicators:
- Free trial signup and active use (daily active user for 5+ days in 14-day trial): [15 pts]
- Freemium account with >3 active users: [12 pts]
- Trial account that invited teammates (viral growth signal): [14 pts]
- API key generated or integration connected in trial: [13 pts — high activation signal]
- Trial account that hit feature gate (upgrade-ready signal): [15 pts]
- Free plan account using 80%+ of usage limit: [10 pts]
- Product webinar or documentation viewed by trial user: [5 pts]

For companies without a product motion: Substitute with "proof of concept or POC engagement" signals — Security review initiated, DPA or MSA request submitted, IT/procurement stakeholder engaged.

**Section 5: Relationship Warmth & Champion Signals (10 points max)**

Score relationship-based signals that indicate an internal champion is building a business case:
- Existing customer at company (user of previous employer's tool migrating): [10 pts]
- Inbound executive LinkedIn connection to your CEO/VP Sales/CMO: [7 pts]
- Referral from existing customer or partner: [10 pts]
- Executive engaged with your company content 5+ times in 30 days: [8 pts]
- Speaker, panelist, or podcast guest from target account: [6 pts]
- Conference meeting scheduled or attended: [8 pts]
- Former customer employed at target account: [9 pts — champion carry-over]

---

**COMPOSITE MQA SCORE & TIER ACTIVATION:**

Calculate: MQA Score = Firmographic (30 pts) + Behavioral (25 pts) + Intent (20 pts) + Product (15 pts) + Relationship (10 pts)

Apply buying committee multiplier to behavioral component where applicable.

Tier definitions and activation plays:

**Hot MQA — Score 70–100:**
- Routing: Immediate assignment to named AE (or SDR-to-AE fast-track for segments without named coverage)
- SLA: AE must attempt contact within 4 business hours via 3 channels (email, LinkedIn, phone)
- Marketing play: Account enters "Hot MQA air-cover" program — LinkedIn matched audience activated within 24 hours, direct mail sequence triggered within 72 hours, executive sponsor email from CMO or CEO within 5 days
- SDR play: Multi-threaded outreach to all known contacts at account simultaneously — not sequential
- Expected outcome: 55–65% convert to opportunity within 30 days

**Warm MQA — Score 50–69:**
- Routing: Assignment to SDR with 5-business-day SLA for first touch
- SLA: 3 contact attempts across 2 channels within 5 days
- Marketing play: Mid-funnel content sequence (case study + ROI content + competitive comparison), LinkedIn retargeting, webinar invitation
- SDR play: Personalized outreach leveraging the specific intent or behavioral signals that pushed the score above 50 — reference the actual trigger in the message
- Expected outcome: 25–35% convert to opportunity within 45 days

**Developing MQA — Score 30–49:**
- Routing: No SDR assignment — nurture track only
- Marketing play: Automated 60-day nurture sequence (3 emails + 1 LinkedIn ad sequence + 1 webinar invitation), monthly intent re-score
- Escalation trigger: If score increases by 15+ points in 14 days, auto-promote to Warm MQA and trigger SDR assignment
- Expected outcome: 10–15% convert to Warm MQA within 90 days; 3–5% convert to opportunity directly from nurture

---

**CRM IMPLEMENTATION BLUEPRINT:**

Salesforce field architecture (Account object):

| Field Label | API Name | Field Type | Description |
|---|---|---|---|
| MQA Score | MQA_Score__c | Number (3,0) | Composite 0–100 score, auto-calculated |
| MQA Tier | MQA_Tier__c | Picklist | Hot / Warm / Developing / Not Qualified |
| MQA Qualified Date | MQA_Qualified_Date__c | Date | Date account first crossed MQA threshold |
| MQA Last Scored | MQA_Last_Scored__c | DateTime | Timestamp of last score recalculation |
| Firmographic Fit Score | MQA_Firmographic_Score__c | Number (2,0) | 0–30 sub-score |
| Behavioral Engagement Score | MQA_Behavioral_Score__c | Number (2,0) | 0–25 sub-score |
| Intent Signal Score | MQA_Intent_Score__c | Number (2,0) | 0–20 sub-score |
| Product Engagement Score | MQA_Product_Score__c | Number (2,0) | 0–15 sub-score |
| Relationship Score | MQA_Relationship_Score__c | Number (2,0) | 0–10 sub-score |
| Buying Committee Depth | MQA_Contact_Count__c | Number (2,0) | Number of contacts with behavioral activity |
| Last Intent Signal Date | Last_Intent_Signal_Date__c | Date | Date of most recent third-party intent signal |
| MQA Assigned To | MQA_Owner__c | Lookup (User) | AE or SDR assigned to work account |
| MQA Status | MQA_Status__c | Picklist | New / In Progress / Accepted / Rejected / Recycled |
| MQA Rejection Reason | MQA_Rejection_Reason__c | Picklist | Wrong Size / No Budget / Wrong Timing / Bad Data / Other |

Automation triggers to build in Salesforce Flow or Marketo/HubSpot workflow:
1. When MQA_Score__c increases above 70 AND MQA_Tier__c changes to "Hot": Create Task for assigned AE ("Hot MQA — contact within 4 hours"), send Slack alert to AE and their sales manager, trigger LinkedIn matched audience sync via Salesforce → LinkedIn integration
2. When MQA_Score__c increases above 50 AND MQA_Tier__c changes to "Warm": Create Task for assigned SDR with 5-day due date, add account to "Warm MQA Nurture" Marketo/HubSpot campaign
3. When MQA_Status__c = "Rejected" AND MQA_Rejection_Reason__c is populated: Auto-route feedback to marketing operations queue, auto-adjust nurture track based on rejection reason, schedule MQA re-score in 30 days
4. Weekly batch job: Recalculate all MQA scores for accounts with any activity in the last 7 days. Apply decay to signals older than 45 days.

---

**SALES ALIGNMENT PROTOCOL:**

MQA Service Level Agreement (SLA) — excerpt for formal sign-off:

Marketing commits to:
- Deliver only accounts with MQA Score ≥ 50 and firmographic fit score ≥ 22 as actionable MQAs
- Provide at minimum one named contact per MQA account with validated title, email, and phone
- Deliver a one-paragraph "why this account now" brief auto-generated from the scoring signals for every Hot MQA
- Review MQA rejection reasons weekly and adjust scoring model within 30 days if any rejection category exceeds 15% of total MQAs

Sales commits to:
- Attempt contact on all Hot MQAs within 4 business hours of assignment
- Attempt contact on all Warm MQAs within 5 business days of assignment
- Document rejection reason in Salesforce for every MQA that does not convert to opportunity within 30 days
- Attend bi-weekly MQA calibration meeting to review scoring model alignment

Bi-weekly MQA calibration meeting agenda (30 minutes):
1. MQA volume and tier distribution this period (5 min)
2. Hot MQA conversion to opportunity — which converted, which did not, why (10 min)
3. MQA rejection analysis — patterns in rejection reasons (5 min)
4. Proposed scoring model adjustments based on feedback (5 min)
5. Top 10 Hot MQAs for next period — joint review and account strategy (5 min)

---

**MEASUREMENT FRAMEWORK — 8 Weekly KPIs:**

| KPI | Definition | Healthy Benchmark | Alert Threshold |
|---|---|---|---|
| MQA Volume by Tier | Hot + Warm + Developing MQAs created per week | Based on pipeline coverage math | <80% of target |
| Hot MQA to Opportunity Rate | Hot MQAs that convert to open opp within 30 days | 50–65% | <40% |
| MQA Acceptance Rate | MQAs accepted by sales ÷ total MQAs delivered | >80% | <65% |
| MQA Rejection Rate by Reason | % of MQAs rejected by each reason | No single reason >15% | Any reason >20% |
| MQA-Sourced Pipeline | Open pipeline from MQA-originated opportunities | >40% of total marketing-sourced pipeline | <25% |
| Average MQA Deal Size | Avg deal size of MQA-sourced opps vs. historical MQL baseline | 10–30% higher than MQL baseline | Equal to or below MQL baseline |
| Hot MQA Response Time | Average hours from MQA assignment to first contact attempt | <4 hours | >8 hours |
| MQA Pipeline Coverage Contribution | MQA-sourced pipeline as multiple of remaining quota | >1.5x of total 3x coverage target | <1x |

---

**90-DAY ROLLOUT PLAN:**

**Phase 1 — Days 1–30: Design and Alignment**
- Week 1: Conduct MQL rejection analysis — pull last 6 months of MQL rejections, categorize by reason, identify the top 3 patterns driving low acceptance
- Week 1: Run ICP firmographic audit — what % of current MQL database comes from ICP-fit companies? Establish baseline
- Week 2: Draft MQA scoring model in spreadsheet (not CRM yet) — score 50 historical "best fit" closed-won accounts and 50 lost/rejected MQLs using the model to validate that the scoring model discriminates between them correctly
- Week 2: Sales alignment workshop — present MQA model to VP Sales and 3–5 AEs, collect feedback, adjust weights as needed, get formal sign-off on SLA
- Week 3–4: Build CRM field architecture and configure scoring workflows in sandbox environment
- Milestone: Signed MQA SLA document, validated scoring model (closed-won account average score should be 20+ points higher than rejected MQL average score), CRM fields built in sandbox

**Phase 2 — Days 31–60: Implementation and Pilot**
- Week 5–6: Deploy CRM configuration to production, backfill account scores for all accounts with activity in last 90 days using batch scoring job
- Week 6: Configure MAP automation — build Warm MQA nurture track, Hot MQA air-cover program, intent-based escalation triggers
- Week 7: Pilot with one sales segment (recommendation: Mid-Market, as conversion patterns are most predictable) — assign all new MQAs exclusively through MQA model, run in parallel with old MQL model for 2 weeks to compare
- Week 8: First MQA calibration meeting — review pilot results, identify scoring model gaps, adjust
- Milestone: 100% of accounts in pilot segment scoring with MQA model, first comparison data showing MQA vs. MQL acceptance rates

**Phase 3 — Days 61–90: Full Launch and Optimization**
- Week 9: Full rollout to all sales segments — sunset parallel MQL handoff process
- Week 10: Launch MQA performance dashboard in CRM/BI tool, automate weekly KPI report to VP Sales and CMO
- Week 11: Publish first MQA program performance report to leadership — include: MQA volume vs. target, conversion rates vs. MQL baseline, pipeline contribution, sales acceptance rate, and 3 case studies of accounts that moved from Developing to Hot to closed won
- Week 12: Conduct model recalibration — adjust weights based on 90-day data, particularly for signals with unexpectedly high or low predictive power
- Milestone: MQA acceptance rate >70%, Hot MQA-to-opportunity rate >45%, first MQA-sourced deals in pipeline at higher-than-baseline deal size

## Example Input/Output

**Example Input:**

Company: Nexus Analytics — B2B SaaS data observability platform, primary buyer is VP Engineering and Head of Data at companies with 200–5,000 employees in SaaS, Fintech, and Healthcare. Sales-led motion. Average deal size: $48,000 ARR. Average sales cycle: 87 days.

Current MQL program: 340 MQLs per month, 28% MQL-to-SQL acceptance rate (below 40% healthy threshold), 62% of MQL rejections are "company too small" or "wrong buyer persona." Pipeline coverage: 2.2x (below 3x target). CRM: Salesforce. MAP: Marketo. Intent data: Bombora for 14 relevant topics. No PLG / freemium motion.

Sales feedback: "Marketing keeps sending us individual developers from 20-person startups who downloaded a whitepaper. We need to talk to Head of Data at companies that have a real data infrastructure problem. Stop sending us leads — send us accounts."

**Example Output (excerpt — Firmographic Scoring Model for Nexus Analytics):**

Firmographic Fit Score (30 points max):

- Employee count 200–5,000: 15 pts | 100–199 or 5,001–10,000: 8 pts | Under 100 or over 10,000: 0 pts
- Industry: SaaS/Cloud-native: 10 pts | Fintech or Healthcare: 9 pts | E-commerce or Media: 6 pts | Manufacturing/Government/Non-profit: 0 pts
- Tech stack: Has Snowflake, Databricks, or dbt in stack (ZoomInfo technographic): 4 pts | Has AWS Redshift or BigQuery: 2 pts | No data warehouse signal: 0 pts
- Geography: US/Canada/UK/DACH: 1 pt | All other: 0 pts

ICP Confirmation threshold: Firmographic score ≥ 22 required before behavioral signals count toward MQA. 

Immediate impact: Applying this firmographic gate alone eliminates 58% of current MQL volume, primarily the "too small" rejections — raising MQL-to-SQL acceptance rate from 28% to an estimated 49% overnight, even before behavioral scoring improvements.

Priority accounts auto-surfaced from existing Salesforce database after backfill run: 47 accounts already meeting the 70+ Hot MQA threshold that sales has never contacted — representing an estimated $2.3M in unworked pipeline opportunity.

## Success Metrics

The output from this prompt is high-quality if it produces:
- A firmographic scoring model with specific point values that, when applied to the last 6 months of MQL rejections, eliminates >50% of rejected leads at the firmographic gate stage
- An account scoring model where historically closed-won accounts score 20+ points higher on average than lost or rejected accounts (validate by backscoring historical data)
- A CRM field list that maps directly to Salesforce Account object without requiring custom development beyond field creation and Flow automation
- A hot MQA tier that represents no more than 15–20% of total scored accounts (too many "hot" accounts degrades sales urgency)
- An MQA SLA document that your VP of Sales would actually sign without significant negotiation
- A 90-day plan that your marketing ops team could begin executing the first Monday after receiving it

## Related Prompts

- [ABM Campaign Orchestration & Account Intelligence Engine](./ABM-Campaign-Orchestration-&-Account-Intelligence-Engine.md)
- [ABM Intent Data Activation & Buying Signal Prioritization Engine](./ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [AI-Powered ABM Target Account List Building & ICP Scoring Intelligence Engine](./AI-Powered-ABM-Target-Account-List-Building-&-ICP-Scoring-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Demand Generation Program Analytics & Pipeline Coverage Intelligence Engine](../../05_Analytics-&-Performance/Demand-Generation-Program-Analytics/AI-Powered-B2B-SaaS-Demand-Generation-Program-Analytics-&-Pipeline-Coverage-Intelligence-Engine.md)

## Integration Tips

**Salesforce:** Use Salesforce Flow (formerly Process Builder) to build the MQA score recalculation trigger. Create a scheduled Flow that runs nightly to apply signal decay and recalculate composite scores. Use Einstein Activity Capture to ensure all email and calendar activity is captured and counted toward behavioral scores.

**HubSpot:** Use the HubSpot Workflows tool to calculate company-level scores by aggregating contact activity scores at the company level. The "Score" property type natively supports compound scoring logic. Use the "Company Scoring" beta feature (available in Marketing Hub Enterprise) for native account-level scoring.

**Marketo:** Build a custom score field on the Marketo Company record (not just the Lead/Contact record). Use "Score Change" triggers to fire MQA tier promotion workflows. Use the "Interesting Moments" feature to capture the specific signal that triggered an MQA score increase — this auto-populates the "why this account now" brief for AEs.

**Bombora Company Surge:** Map Bombora surge scores to Salesforce custom fields using the native Bombora Salesforce integration. Set up Salesforce Flow to automatically update the MQA Intent Score field when Bombora signals arrive. Configure alerts to notify SDR managers when a known Warm MQA account shows a new Bombora surge on a high-relevance topic.

**6sense:** If using 6sense, leverage the native Salesforce integration to write 6sense buying stage predictions directly to Salesforce Account fields. Map 6sense "Decision" or "Purchase" stage directly to 18–20 points on the Intent Signal Score sub-component.

**Slack:** Create a Salesforce-to-Slack alert via the native Salesforce for Slack integration. When MQA_Tier__c changes to "Hot," trigger a Slack message to the assigned AE and their manager in the team's #hot-accounts channel with account name, MQA score, top signals, and a Salesforce link. This alone reduces average AE response time from 6+ hours to under 90 minutes.

**G2 Buyer Intent:** Map G2 profile view activity to the Intent Signal Score using G2's Salesforce integration. Configure G2 to push account-level intent activity data to Salesforce daily. Set up scoring rules to award 10–15 points when an account views 3+ competitor profiles on G2 within a 14-day window — this is one of the highest-confidence buying signals available.

## Troubleshooting

**Problem: Sales team is skeptical and continues to route around the MQA model, calling the contacts they want to call regardless of account score.**
Fix: Do not fight this directly. Instead, pull a 90-day data comparison showing closed-won rate for AE-selected contacts vs. Hot MQA-routed contacts. When the data shows that Hot MQAs are closing at 2–3x the rate of AE self-sourced contacts at similar deal size, the conversation shifts from opinion to math. Present this data in the QBR with VP Sales present.

**Problem: MQA score is calculated but accounts are not being promoted to Hot tier — the model is producing too many "Developing" accounts and not enough "Hot" accounts.**
Fix: Check whether the firmographic gate (score ≥ 22 required) is eliminating most of your database before behavioral signals can accumulate. Audit whether your Salesforce database has complete firmographic data (employee count, industry) — if data quality is poor, behavioral signals cannot be properly weighted. Run a data enrichment pass with ZoomInfo or Clearbit on all accounts active in the last 90 days before rerunning the scoring model.

**Problem: The model is working but MQA acceptance rate is still below 65%, and sales keeps citing reasons not listed in the MQA rejection picklist.**
Fix: This indicates that the scoring model is letting through accounts that look right on paper but have a disqualifying characteristic not captured in the model. Schedule 5 "win-loss style" calls with AEs who recently rejected MQAs — have them walk through the account and explain what they saw that made it unworkable. The most common hidden disqualifiers are: "already a customer of a direct competitor and locked in a multi-year contract," "company is in acquisition talks and freezing all vendor decisions," or "the contact who engaged is not in any way connected to the buying decision." Add these as negative scoring signals or pre-qualification exclusion criteria.

## Version History
- v1.0: Initial creation (auto-generated)
