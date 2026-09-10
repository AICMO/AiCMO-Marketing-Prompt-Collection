# AI-Powered B2B SaaS Multi-Source Intent Signal Aggregation & Cross-Platform Buyer Stage Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** intent-data, b2b, analytics, demand-gen, pipeline-acceleration, abm, revenue-intelligence

## Overview
Autonomously aggregates, normalizes, and correlates buyer intent signals from 6sense, Bombora, G2 Buyer Intent, ZoomInfo Intent, TechTarget Priority Engine, and first-party behavioral data into a unified account-level intelligence layer that ranks accounts by active buying stage, assigns signal confidence scores, and triggers prioritized sales and marketing actions. Use this prompt when you have intent signals from 3+ sources and need to eliminate noise, resolve conflicting signals, and route accounts to the right motion at the right moment.

## Quick Copy-Paste Version

You are a B2B revenue intelligence analyst. I have intent data from multiple sources and need to turn raw signals into a prioritized account list with recommended actions.

My intent sources: [e.g., 6sense, Bombora, G2 Buyer Intent, website behavioral data]
My product category: [e.g., sales intelligence platform]
My ICP: [e.g., RevOps leaders at 200-2000 employee SaaS companies]
Target account list size: [e.g., 500 named accounts + inbound net-new]

For each account showing intent, do the following:

1. SIGNAL INVENTORY: List all active intent signals per account with source, topic cluster, signal strength (1-10), and recency (days since first/last signal).

2. CROSS-SOURCE CORRELATION: Identify accounts showing intent on 2+ sources simultaneously. Flag signal convergence windows (multiple sources spiking within 14 days) as HIGH CONFIDENCE buying events.

3. BUYER STAGE CLASSIFICATION: Assign each account to one of four stages:
   - AWARENESS: 1 source, topic-level intent only, no product/competitor signals
   - CONSIDERATION: 2+ sources OR competitor intent present, researching alternatives
   - EVALUATION: Product-specific intent, pricing/ROI content consumption, demo/trial signals
   - DECISION: Legal/security/compliance research, integration documentation signals, executive stakeholder activation

4. SIGNAL DECAY WEIGHTING: Apply recency multiplier — signals < 7 days = 1.0x, 8-14 days = 0.85x, 15-21 days = 0.70x, 22-30 days = 0.50x, 30+ days = 0.25x. Recalculate adjusted scores.

5. ACTION ROUTING: Based on buyer stage, assign:
   - AWARENESS → Targeted content syndication + LinkedIn ABM ads, no SDR outreach
   - CONSIDERATION → Personalized content sequence + BDR social touch + retargeting
   - EVALUATION → AE-led multi-stakeholder outreach + competitive battlecard + demo offer
   - DECISION → Executive sponsor activation + POC support + deal room creation

6. WEEKLY INTELLIGENCE BRIEF: Generate a prioritized top-20 account list ranked by composite intent score, with one recommended action per account that can be executed within 48 hours.

Output format: ranked table with columns: Account Name | Stage | Top Signal Source | Signal Topics | Composite Score (0-100) | Recommended Action | Assigned Owner (Marketing/SDR/AE).

## Advanced Customizable Version

ROLE: You are a senior revenue intelligence analyst specializing in multi-source intent data orchestration for B2B SaaS companies. You operate at the intersection of data science and go-to-market strategy, with deep expertise in 6sense, Bombora, G2 Buyer Intent, ZoomInfo Intent, TechTarget Priority Engine, and first-party behavioral analytics.

CONTEXT:
- Company: [Your Company Name]
- Product Category: [Primary ICP search category, e.g., "customer data platform," "sales engagement platform"]
- ICP Definition: [Title + company size + industry + tech stack signals]
- Total Addressable TAL: [Number of named accounts in your CRM/MAP]
- Intent Budget Allocated: [Monthly spend on intent data, e.g., $8,000/month across 3 vendors]
- CRM: [Salesforce / HubSpot]
- MAP: [Marketo / HubSpot / Pardot]
- Current Intent Vendors: [List all active subscriptions]
- Sales Team Structure: [# of SDRs, AEs, territories]

OBJECTIVE:
Build an autonomous, repeatable intent signal aggregation system that consolidates signals from all active intent vendors plus first-party behavioral data, eliminates false positives, surfaces true in-market accounts, and routes them to the highest-leverage GTM action within a 48-hour window.

TASK 1 — SIGNAL TAXONOMY MAPPING:
Create a master signal taxonomy that maps each vendor's intent topics to a unified category framework. For each vendor:
- Map their topic labels to your product's solution categories (e.g., Bombora "B2B Data Management" → your category "Data Infrastructure")
- Identify POSITIVE SIGNAL topics (active buying intent for your category)
- Identify COMPETITIVE DISPLACEMENT topics (researching named competitors)
- Identify PAIN SIGNAL topics (researching problems your product solves)
- Flag NOISE topics (general industry content with no buyer intent correlation)

Format output as a cross-reference table: Vendor | Their Topic Label | Your Category Mapping | Signal Type (Positive/Competitive/Pain/Noise) | Weight (1.0/0.8/0.6/0.0).

TASK 2 — ACCOUNT-LEVEL SIGNAL AGGREGATION:
For each account with signals in the current 30-day window:
a) Pull all signals from all vendors into a single account record
b) Apply topic weight multipliers from Task 1
c) Apply source credibility multiplier: 6sense = 1.0x, Bombora = 0.9x, G2 = 0.95x, ZoomInfo = 0.85x, TechTarget = 0.90x, First-Party = 1.1x (highest weight — you own this data)
d) Apply recency decay: Days 1-7 = 1.0x | Days 8-14 = 0.85x | Days 15-21 = 0.70x | Days 22-30 = 0.50x
e) Calculate RAW INTENT SCORE = Sum of (Signal Base Score × Topic Weight × Source Credibility × Recency Decay)
f) Normalize to 0-100 scale across all accounts

TASK 3 — BUYER STAGE CLASSIFICATION:
Apply the following deterministic classification logic using signal patterns:

AWARENESS STAGE (Score 15-34):
- Signals from 1 source only
- Topics: category-level education, industry trends
- No competitor signals, no product-specific signals
- Action: Demand creation — awareness content, branded social, educational nurture

CONSIDERATION STAGE (Score 35-54):
- Signals from 2+ sources OR single source with competitor intent
- Topics: solution comparisons, vendor shortlist research, ROI calculators
- Buying committee expansion signals (new titles engaging)
- Action: Demand capture — comparison content, retargeting, SDR social warming

EVALUATION STAGE (Score 55-79):
- Signals from 3+ sources OR strong G2/review site intent
- Topics: product-specific, demo/trial, pricing, implementation requirements
- Champion-level engagement (individual contacts engaging with technical content)
- Action: Pipeline acceleration — demo offer, battlecard delivery, multi-thread outreach

DECISION STAGE (Score 80-100):
- High-frequency signals from 4+ sources, convergence window < 14 days
- Topics: security review, legal/compliance, contract terms, integration docs
- Executive stakeholder activation (C-suite/VP viewing pricing or case studies)
- Action: Deal creation — executive sponsor activation, digital deal room, POC/pilot

TASK 4 — FALSE POSITIVE FILTERING:
Flag and quarantine accounts that match these false positive patterns before routing:
a) COMPETITIVE SELF-RESEARCH: Accounts where your competitor company domains are showing intent (competitor monitoring their own brand)
b) VENDOR RESEARCH: Accounts that are known analysts, press, or competing vendors doing market research
c) EXISTING CUSTOMERS: Pull your current customer list from CRM; existing customers showing intent = expansion signal, not new pipeline — route to CSM team
d) STALE CRM ACCOUNTS: Accounts with a Closed Lost or Disqualified status in CRM in last 90 days — hold for 90-day cooling period unless score > 80
e) LOW-ICP FIT: Accounts with ICP score < 40 in CRM — deprioritize regardless of intent score

TASK 5 — ACCOUNT INTELLIGENCE ENRICHMENT:
For each qualified account (passed false positive filter), auto-enrich with:
a) CRM status: Active opportunity / MQL / Cold / No CRM record
b) Last sales touch: Days since last SDR/AE activity
c) Buying committee coverage: Number of unique contacts engaged at this account vs. typical buying committee size
d) Prior engagement history: Has this account engaged with demos, webinars, or case studies in last 180 days?
e) Account-level content consumption score: Pages viewed × Page intent value (pricing=10, case study=8, demo=7, blog=3)

TASK 6 — PRIORITIZED ACTION DISPATCH:
Generate a weekly TOP 20 PRIORITY ACCOUNTS list. For each:
- Composite Intent Score (0-100)
- Buyer Stage
- Top 3 signal topics with source attribution
- Last CRM activity and owner
- Recommended primary action (specific, executable within 48 hours)
- Recommended supporting action (sequence enrollment, ad audience addition, etc.)
- Draft personalization angle (one sentence connecting their specific intent topics to your product's relevant capability)

TASK 7 — SIGNAL VELOCITY ALERTS:
Create a real-time alert system for accounts that cross these thresholds:
- Stage Advancement: Account moves from CONSIDERATION → EVALUATION (trigger immediate SDR notification)
- Score Spike: Account score increases by 25+ points week-over-week (trigger same-day outreach)
- Convergence Window: Account shows intent on 4+ sources within 7 days (trigger executive sponsor review)
- Competitive Signal Surge: Account spikes on competitor topics (trigger competitive battlecard delivery)

TASK 8 — PROGRAM ROI REPORTING:
Monthly report on intent data program ROI:
a) Intent-sourced pipeline: $ value of opportunities where account showed intent pre-opportunity creation
b) Intent-influenced pipeline: $ value of open opportunities with accounts that showed intent during deal cycle
c) Stage conversion rates: Intent-qualified accounts → MQL, MQL → SAL, SAL → SQO vs. non-intent-qualified baseline
d) Source contribution analysis: Which intent vendor contributed to most pipeline? Highest conversion rate? Best LTV correlation?
e) Cost per intent-qualified account by vendor and by stage

OUTPUT FORMAT:
1. Intent Signal Taxonomy Map (table)
2. Account Intelligence Matrix (top 50 accounts, ranked table)
3. Weekly Priority Dispatch List (top 20 accounts, action-ready)
4. Alert Queue (accounts crossing threshold triggers)
5. Monthly ROI Summary (for budget justification)

CONSTRAINTS:
- Every action recommendation must be executable by one person within 48 hours — no "build a new campaign" outputs
- Include specific personalization angles for outreach — no generic messaging
- Flag every recommendation with confidence level: HIGH (3+ sources), MEDIUM (2 sources), LOW (1 source)
- Assume CRM data may be stale — recommend verification step before SDR outreach
- Route expansion signals to CSM immediately, never to sales as new pipeline

## Example Input/Output

**Input Example:**

Company: Clarix Data — B2B SaaS data observability platform
ICP: Data Engineering Managers and VP Data at 300-3000 employee SaaS, fintech, and e-commerce companies
Intent Vendors: 6sense (data infrastructure category), Bombora (data quality, data pipeline, data observability topics), G2 Buyer Intent (data observability category page)
TAL: 400 named accounts

Sample account: **Fenway Financial Technologies** (640 employees, Series C fintech)
- 6sense: "Data Infrastructure" — Score 78, active 4 days
- Bombora: "Data Pipeline Management" — Surge 8/10, "Data Quality Automation" — Surge 7/10, active 6 days
- G2 Buyer Intent: Viewed Clarix profile + 3 competitor profiles (Monte Carlo, Bigeye), active 2 days
- First-party: 4 unique contacts visited pricing page (1x), case study (2x), integration docs (1x) in last 5 days
- CRM status: No active opportunity; last SDR touch 47 days ago; 2 contacts in Salesforce

**Output Example:**

**Account: Fenway Financial Technologies**
| Field | Value |
|---|---|
| Composite Intent Score | 91 / 100 |
| Buyer Stage | DECISION |
| Signal Convergence | 4 sources active within 6-day window |
| Top Signal Topics | Data pipeline management (Bombora), G2 competitive evaluation (Monte Carlo, Bigeye), Pricing page visits (first-party) |
| False Positive Check | PASSED — no competitive overlap, not existing customer, ICP fit: 84/100 |
| Buying Committee Coverage | 4 contacts engaged / est. 6-person committee — needs VP Engineering and CFO coverage |
| CRM Status | No open opportunity — 47 days dark |
| Recommended Primary Action | AE immediate multi-thread outreach — personalize to their G2 competitive evaluation; lead with "Data observability ROI for Series C fintech" angle |
| Recommended Supporting Action | Enroll in DECISION-stage nurture sequence; add to LinkedIn retargeting audience with customer case study creative (fintech vertical) |
| Personalization Angle | "Your team has been evaluating data observability options — most fintech companies at your stage (Series C, 640 employees) prioritize pipeline reliability during transaction volume spikes. Happy to share how [comparable fintech customer] reduced data incident MTTR by 68%." |
| Confidence Level | HIGH (4 sources) |
| Alert Flag | CONVERGENCE WINDOW — 4 sources within 6 days. Recommend VP Sales review. |

---

**Weekly Top 20 Dispatch — Sample Row:**

| Rank | Account | Stage | Score | Top Signal | Last Touch | Action | Owner |
|---|---|---|---|---|---|---|---|
| 1 | Fenway Financial Technologies | DECISION | 91 | G2 competitive eval + pricing | 47 days ago | AE immediate outreach | Sarah K. (AE Enterprise) |
| 2 | Orbital Commerce Inc. | EVALUATION | 74 | Bombora data quality surge + demo page | 12 days ago | SDR multi-thread + demo invite | Marcus L. (SDR) |
| 3 | Prism Health Systems | CONSIDERATION | 52 | 6sense category intent + competitor signal | No CRM record | Create contact + LinkedIn sequence | Jordan M. (SDR) |

## Success Metrics

- **Signal-to-Pipeline Conversion Rate:** Intent-qualified accounts that convert to SAL within 90 days — benchmark: 12-18% for EVALUATION+ stage accounts
- **Composite Score Accuracy:** % of accounts scoring 75+ that open an opportunity within 60 days — target: > 25% (3-4x baseline)
- **Stage Classification Precision:** Of accounts classified as DECISION stage, % that have an active deal in CRM within 45 days — target: > 40%
- **False Positive Rate:** % of dispatched accounts that SDR/AE rejects as not relevant — target: < 15%
- **Source ROI Differential:** Pipeline-per-dollar by intent vendor — identify highest and lowest performers quarterly for budget reallocation
- **Convergence Window Win Rate:** Accounts where 4+ source convergence was detected — compare closed-won rate vs. single-source accounts — target: 2x+ lift
- **Alert Response Time:** Average hours between intent spike alert and first sales touch — target: < 24 hours for DECISION-stage alerts
- **Buying Committee Coverage:** For closed-won deals sourced via intent, average # of contacts engaged before opportunity creation — target: 3+ contacts per account

## Related Prompts

- [`../../05_Analytics-&-Performance/Intent-Data-Analytics/AI-Powered-B2B-SaaS-First-Party-Behavioral-Intent-Analytics-&-Website-Visitor-Revenue-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Intent-Data-Analytics/AI-Powered-B2B-SaaS-First-Party-Behavioral-Intent-Analytics-&-Website-Visitor-Revenue-Intelligence-Engine.md) — First-party behavioral foundation for intent stacking
- [`../../05_Analytics-&-Performance/Intent-Data-Analytics/AI-Powered-B2B-SaaS-Third-Party-Intent-Data-Intelligence-&-Signal-to-Pipeline-Revenue-Activation-Analytics-Engine.md`](../../05_Analytics-&-Performance/Intent-Data-Analytics/AI-Powered-B2B-SaaS-Third-Party-Intent-Data-Intelligence-&-Signal-to-Pipeline-Revenue-Activation-Analytics-Engine.md) — Third-party intent vendor evaluation and activation
- [`../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md) — ABM activation layer downstream of intent signal aggregation
- [`../../05_Analytics-&-Performance/Account-Based-Marketing-Analytics/AI-Powered-B2B-ABM-Intent-Data-ROI-Measurement-&-Signal-Quality-Analytics-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Account-Based-Marketing-Analytics/AI-Powered-B2B-ABM-Intent-Data-ROI-Measurement-&-Signal-Quality-Analytics-Intelligence-Engine.md) — ROI measurement for your intent data investment

## Integration Tips

- **6sense + Salesforce:** Use 6sense's native Salesforce integration to write composite intent scores as a custom Account field. Set up Salesforce process builder to auto-assign accounts to the right sales queue based on stage classification output from this prompt.
- **Bombora + HubSpot:** Map Bombora Surge scores to HubSpot Contact Properties via the native integration. Create smart lists that segment by stage classification for automated workflow enrollment.
- **G2 Buyer Intent + Slack:** Configure G2's Slack notifications to trigger when a named account views competitor profiles. Feed this into your alert queue from Task 7 — auto-post to #intent-alerts with the account's composite score context from this system.
- **Zapier Automation:** Build a Zap that fires when an account's composite intent score crosses 75: (1) creates a task in Salesforce for the account owner, (2) adds account to LinkedIn Campaign Manager audience, (3) sends a Slack DM to the assigned SDR with the personalization angle from Task 6.
- **Google Sheets Reporting:** Export Task 8 monthly ROI report to a Google Sheet with live charts for vendor-by-vendor pipeline contribution. Share read-only link with VP Sales and CFO for budget review meetings.
- **Clearbit/Apollo Enrichment:** Before routing new accounts (no CRM record) to SDR, auto-enrich with Clearbit or Apollo to validate ICP fit score. Prevents wasted SDR time on poorly-fit accounts that happen to be browsing.
- **Salesforce Campaigns:** Tag every intent-influenced opportunity with the source campaign "Intent-Qualified — [Stage]" to enable clean pipeline reporting in Salesforce. This powers the Task 8 ROI calculations without manual data reconciliation.

## Troubleshooting

**Problem: Composite scores are consistently high (80+) but very few convert to pipeline — false positive rate exceeding 25%.**
Solution: Audit your Topic Weight table from Task 1. Likely your NOISE topics are still included and inflating scores. Re-run the taxonomy mapping and aggressively mark general industry research topics (e.g., "digital transformation," "cloud computing") as 0.0x weight. Also verify your existing customer and competitor domain exclusion lists are current — this single fix often reduces false positives by 30-40%.

**Problem: 6sense and Bombora disagree on the same account — one shows DECISION, the other shows AWARENESS.**
Solution: This is common because vendors use different methodology and panel sources. Do not average — use the HIGHEST stage signal as the primary signal and flag the discrepancy for human review. Also check signal timing: if 6sense signal is 2 days old and Bombora signal is 22 days old, apply recency decay — the older signal may reflect a prior research cycle that has passed, not the current buying event. Always weight first-party data as the tiebreaker.

**Problem: SDRs are ignoring the priority dispatch list and continuing to work their own lead lists.**
Solution: This is a change management issue, not a data problem. Three fixes: (1) Share closed-won data showing intent-qualified accounts converted at 2-3x rate vs. non-intent — make the ROI undeniable. (2) Have VP Sales mandate that intent-qualified accounts in the dispatch list must receive a first touch within 24 hours or they get reassigned. (3) Simplify the output — SDRs are most responsive to a single-sentence "why outreach now" message, not a data table. Feed the Task 6 personalization angles directly into Salesloft/Outreach sequences so outreach is one click away.

## Version History
- v1.0: Initial creation (auto-generated)
