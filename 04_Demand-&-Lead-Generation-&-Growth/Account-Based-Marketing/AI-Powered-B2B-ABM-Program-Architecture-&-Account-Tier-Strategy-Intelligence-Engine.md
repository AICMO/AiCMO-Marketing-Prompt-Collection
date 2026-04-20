# AI-Powered B2B ABM Program Architecture & Account Tier Strategy Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, abm, account-based-marketing, pipeline, strategy, tiering, resource-allocation, enterprise

## Overview
Designs the complete architectural blueprint for a B2B Account-Based Marketing program — defining the 1:1, 1:few, and 1:many tier structure, account coverage model, per-tier resource allocation, technology requirements, and 90-day launch roadmap — so marketing and sales enter ABM with a shared playbook instead of conflicting assumptions.

## Quick Copy-Paste Version

You are a senior B2B ABM strategist with 15+ years designing account-based marketing programs for enterprise and mid-market SaaS companies. Design a complete ABM program architecture for the following company:

Company: [Your Company]
Product/Service: [What you sell]
ICP profile: [e.g., "Enterprise SaaS, 500-5000 employees, US/EU, using Salesforce"]
ACV: [Average Contract Value]
Total addressable accounts in CRM: [Number]
Sales team size (AEs): [Number]
Marketing team size dedicated to ABM: [Number, including budget]
Current ABM maturity: [None / Pilot / Established]
Top 3 strategic accounts you'd kill to win this quarter: [Name 3 real accounts or types]

Deliver:

1. TIER DESIGN & ACCOUNT ALLOCATION
Define exactly 3 tiers with precise criteria for each:
- Tier 1 (1:1 Strategic): Maximum account count, minimum ACV threshold, ICP fit score required, strategic criteria (e.g., logo value, market category leadership, reference potential), and the specific signals that qualify an account for this tier
- Tier 2 (1:Few Cluster): Account count range, industry/persona cluster logic, minimum intent signal threshold, and what makes an account right for cluster-based vs. individual treatment
- Tier 3 (1:Many Programmatic): Scale ceiling, segment definition, automated qualification criteria, and when an account graduates from Tier 3 to Tier 2

2. RESOURCE ALLOCATION MODEL
For each tier, specify:
- Marketing hours per account per month
- Content asset requirements per account (custom vs. templatized vs. programmatic)
- Budget allocation per account per quarter
- Required technology stack elements per tier
- SDR/AE marketing support ratio

3. COVERAGE MODEL MATH
Calculate the maximum sustainable account coverage given team size:
- Tier 1 capacity: [X accounts per AE, Y accounts per marketer]
- Tier 2 capacity: [X accounts per cluster, Y clusters per marketer]
- Tier 3 capacity: [X accounts in automated programs]
- Total TAL (Target Account List) ceiling for this team
- Warning flags if current team is trying to cover too many accounts

4. TECHNOLOGY STACK REQUIREMENTS
Map required tools per tier:
- Tier 1: Which tools are non-negotiable vs. nice-to-have (intent data, personalization, direct mail platform, gift, sales intelligence)
- Tier 2: Which tools enable efficient cluster personalization (dynamic content, account-level reporting, LinkedIn matched audiences)
- Tier 3: Which tools enable programmatic scale (MAP automation, programmatic display, firmographic targeting)
- Total estimated technology spend and where to start if budget-constrained

5. LAUNCH ROADMAP (90 DAYS)
Week-by-week plan:
- Days 1-30: Foundation (TAL build, tier assignment, stakeholder alignment, tech setup)
- Days 31-60: Pilot (Run Tier 1 with 5-10 accounts, Tier 3 programmatic launch)
- Days 61-90: Scale (Full Tier 1 activation, Tier 2 first cluster, measurement framework live)

Output as a program blueprint a CMO can present to the CEO and a demand gen manager can hand directly to their team for immediate execution.

## Advanced Customizable Version

ROLE: You are an elite B2B ABM program architect and revenue marketing strategist with 15+ years designing and scaling account-based marketing programs across enterprise SaaS, complex B2B services, and high-ACV manufacturing and professional services firms. You have built ABM programs from scratch (zero to first pipeline in 90 days) and optimized mature programs (from $2M to $20M ABM-influenced pipeline). You understand both the strategic program design and the operational realities of what marketing and sales teams can actually execute without burning out.

COMPANY CONTEXT:
- Company name: [COMPANY_NAME]
- Product/service category: [PRODUCT_CATEGORY — e.g., "AI-powered supply chain optimization platform", "enterprise data governance SaaS", "managed security services"]
- Core value proposition: [VALUE_PROP — one sentence]
- ICP definition: [ICP — company size, industry, tech stack signals, geography, business model]
- ACV range: $[ACV_LOW]–$[ACV_HIGH]
- Sales cycle length: [SALES_CYCLE] months
- Sales motion: [SALES_MOTION — e.g., "enterprise field sales", "inside sales + SE", "channel-led with overlay"]
- Win rate overall: [WIN_RATE]%
- Win rate from ABM-influenced opportunities (if known): [ABM_WIN_RATE]%

TEAM CAPACITY:
- Total AEs: [AE_COUNT] (specify enterprise vs. mid-market split if applicable)
- SDRs/BDRs: [SDR_COUNT]
- Marketing headcount dedicated to ABM: [ABM_MARKETING_HEADCOUNT]
- Marketing budget dedicated to ABM: $[ABM_BUDGET]/quarter
- Current MarTech stack: [STACK — list key tools: CRM, MAP, intent data provider, ABM platform if any]
- ABM platform (if any): [PLATFORM — e.g., "6sense", "Demandbase", "Terminus", "none yet"]

PROGRAM HISTORY:
- ABM maturity level: [None / Pilot (1-10 accounts) / Established (50+ accounts) / Scaled (200+ accounts)]
- Biggest ABM failure or frustration to date: [FAILURE — e.g., "sales won't look at our account intel", "accounts don't know they're in our ABM program", "we ran ABM on 500 accounts and got zero pipeline"]
- Biggest ABM win to date: [WIN — e.g., "closed $1.2M deal that started from our Tier 1 account package"]

STRATEGIC OBJECTIVES:
- ABM pipeline target for next 12 months: $[PIPELINE_TARGET]
- Target number of Tier 1 accounts to close this year: [TIER1_CLOSE_TARGET]
- Specific strategic objectives beyond revenue: [OBJECTIVES — e.g., "win 3 Fortune 500 logos", "establish presence in Healthcare vertical", "displace Competitor X from 5 accounts"]

---

DELIVERABLE 1 — ABM TIER ARCHITECTURE & ACCOUNT QUALIFICATION FRAMEWORK

A. Tier Design Philosophy
- Recommended tier model for this company (confirm or challenge the classic 3-tier model based on team size and ACV)
- The single most important criterion for Tier 1 qualification at this company (ACV potential vs. strategic fit vs. intent signal strength vs. relationship capital)
- How to handle "strategic accounts with low revenue potential" (logo accounts, reference accounts, ecosystem anchors)
- Governance model: who owns tier assignment decisions — Marketing, Sales, or RevOps?

B. Tier 1 — Strategic 1:1 Program (Maximum 20–50 accounts)
Qualification Criteria (an account must meet ALL of the following to enter Tier 1):
- Minimum ACV opportunity: $[AMOUNT] (based on average deal size and team capacity math)
- ICP fit score threshold: [SCORE]/100 minimum (using firmographic + technographic + behavioral data)
- Strategic value criteria: [3-5 non-revenue criteria — e.g., "category-defining brand", "references 5+ prospects per year", "VP-level champion already engaged"]
- Intent signal minimum: [SIGNAL — e.g., "6sense showing Stage 4/5 buying stage OR direct outreach OR executive intro from board member"]
- Account exclusion rules: [WHO NEVER QUALIFIES — e.g., "accounts already 18+ months in pipeline without movement", "accounts owned by a partner with exclusivity clause"]

Tier 1 Program Elements (specify which are required vs. optional):
- Custom account research brief (frequency: [X per quarter])
- Personalized outreach from [CEO/CMO/VP Sales] (cadence: [X per quarter])
- Bespoke content asset created specifically for this account (type + quantity)
- Executive roundtable or 1:1 event invitation (cadence)
- Physical direct mail or gifting (trigger: [specific behavior or milestone])
- Account-specific landing page or microsite
- Custom ROI/business case document
- Internal Slack/Teams channel with dedicated AE + SDR + Marketing pod

Resource commitment per Tier 1 account:
- Marketing hours per month: [X hours]
- Budget per account per quarter: $[AMOUNT]
- AE time per week: [X hours of non-selling account planning and coordination]

C. Tier 2 — Cluster-Based 1:Few Program (50–200 accounts per cluster batch)
Cluster Logic Design:
- Primary clustering variable: [VARIABLE — e.g., industry vertical, use case, tech stack, company size band, buying stage]
- Secondary clustering variable: [VARIABLE — for sub-personalization within cluster]
- Maximum cluster size for meaningful personalization: [X accounts]
- Minimum cluster size to justify asset creation investment: [X accounts]

Cluster qualification criteria (an account moves from Tier 3 to Tier 2 when):
- Intent threshold crossed: [SIGNAL]
- Engagement minimum: [ENGAGEMENT — e.g., "2+ website visits from 3+ stakeholders in last 30 days", "email opened + clicked twice in a sequence"]
- Recency filter: [RECENCY — e.g., "active signal in last 60 days"]

Tier 2 Program Elements per cluster:
- Cluster-specific content asset (format + topic angle driven by shared pain for this segment)
- Industry/persona-specific email nurture track (touchpoints, cadence, channel mix)
- LinkedIn matched audience campaign targeting all cluster accounts
- Cluster-specific webinar or executive roundtable (threshold: minimum [X] accounts before hosting)
- SDR outreach sequence specific to this cluster's pain point

Resource commitment per Tier 2 cluster:
- Marketing hours per cluster per month: [X hours]
- Content investment per cluster per quarter: $[AMOUNT]
- SDR sequences to run: [X per account]

D. Tier 3 — Programmatic 1:Many (All remaining TAL accounts)
Automation Architecture:
- Account entry criteria into Tier 3 programmatic (ICP fit score ≥ [X], in CRM as target account)
- Exit criteria (graduate to Tier 2 or disqualify from TAL)
- Automated signals that trigger SDR assignment (without human review)
- Maximum TAL size for this team (the honest ceiling given MarTech stack and SDR capacity)

Tier 3 Program Elements (fully automated):
- Programmatic display / LinkedIn audience targeting (firmographic-based, no intent required)
- Content syndication program (topic filters + lead threshold before routing)
- Automated email cadence (number of touches, cadence, from marketing vs. SDR)
- G2/review site category presence optimization (for accounts researching your category)
- Automated Tier 3 newsletter or nurture track

---

DELIVERABLE 2 — COVERAGE MODEL & CAPACITY MATH

A. Sustainable Coverage Calculation
Show the math for this specific team:
- Tier 1 capacity: ([ABM_MARKETING_HEADCOUNT] × [Hours available for Tier 1 per month]) ÷ [Hours per Tier 1 account per month] = [MAX_TIER1_ACCOUNTS]
- Tier 2 capacity: ([Remaining marketing hours] ÷ [Hours per cluster per month]) × [Average cluster size] = [MAX_TIER2_ACCOUNTS]
- Tier 3 capacity: Technology-limited, not headcount-limited = [TECH_LIMIT]
- Total TAL ceiling: Tier 1 + Tier 2 + Tier 3 = [TOTAL]

B. Red Flag Audit
Flag if the current team is trying to ABM too many accounts:
- Warning threshold: If Tier 1 accounts exceed [X]% of team capacity, ABM quality will collapse
- "ABM theater" risk: Programs spread too thin across too many accounts create the illusion of ABM without the revenue impact
- Recommended correction: How to consolidate accounts and fire bad-fit Tier 1 accounts from the program

C. AE-to-Account Alignment
- Recommended AE account load by tier: Tier 1 = [X] accounts max / AE, Tier 2 = [X] max, Tier 3 = [X] max
- How to handle AEs who have too many Tier 1 accounts (forced triage framework)
- Marketing support ratio: [X] marketing FTEs per [Y] AEs for sustainable Tier 1 execution

---

DELIVERABLE 3 — TECHNOLOGY STACK BLUEPRINT

A. Required vs. Optional Tools by Tier

Tier 1 Non-Negotiables:
- Sales intelligence: [TOOL — e.g., ZoomInfo, Apollo, LinkedIn Sales Navigator for account research]
- Intent data: [TOOL — e.g., 6sense, Bombora, G2 Buyer Intent for knowing when Tier 1 accounts are in-market]
- Account engagement tracking: [TOOL — for knowing when Tier 1 contacts engage with any marketing touchpoint]
- Direct mail / gifting: [TOOL — e.g., Sendoso, Reachdesk, Postal for high-touch physical touchpoints]
- Personalization: [TOOL — e.g., Mutiny, Intellimize for account-specific web experience]

Tier 2 Required:
- Dynamic content / segmentation in MAP: [TOOL — for cluster-specific nurture tracks]
- LinkedIn Campaign Manager Matched Audiences: [Built-in, requires CRM sync]
- Account-level reporting: [TOOL — must show engagement at account level, not contact level]

Tier 3 Minimum:
- Marketing automation platform with firmographic list import: [MAP]
- Programmatic display with ABM targeting: [TOOL — e.g., Demandbase, Terminus, or LinkedIn alone if budget-constrained]
- CRM with TAL field and tier assignment: [CRM]

B. Build Order (if starting from scratch)
Month 1: [Tool 1] — why this is the foundational first investment
Month 2: [Tool 2] — why this is the second priority
Month 3: [Tool 3] — and so on
Total monthly technology spend at full build-out: $[AMOUNT]
Minimum viable tech stack for year one: $[AMOUNT]/month

---

DELIVERABLE 4 — ABM TAL BUILD & TIER ASSIGNMENT WORKFLOW

A. Target Account List Construction Process
Step 1: Start with [DATA SOURCE] to pull all companies matching ICP firmographic criteria
Step 2: Score accounts using [SCORING MODEL] — specify variables and weights
Step 3: Layer in intent data from [INTENT PROVIDER] to elevate in-market accounts
Step 4: Cross-reference with sales CRM — identify accounts already in pipeline vs. cold
Step 5: Executive review — Sales VP and CMO jointly review Tier 1 candidates
Step 6: Freeze TAL for [QUARTER] and commit — no mid-quarter additions to Tier 1

B. Account Scoring Model
Build a weighted score (100 points total) using:
- ICP firmographic fit: [X points] — company size, industry, geography, business model
- Technographic fit: [X points] — tech stack signals that indicate they're a buyer
- Intent data strength: [X points] — researching your category or competitive alternatives
- Engagement history: [X points] — prior marketing touchpoints, website visits, content consumption
- Relationship capital: [X points] — existing champion, executive intro, warm connection from network
- Strategic value: [X points] — logo value, reference potential, market category signal

C. Tier Assignment Decision Rules
Tier 1 if: Score ≥ [X] AND ACV ≥ $[Y] AND at least one executive relationship OR board intro
Tier 2 if: Score ≥ [X] AND in a defined cluster segment with ≥ [Y] peer accounts
Tier 3 if: Score ≥ [X] (ICP fit minimum) but doesn't qualify for Tier 1 or 2
Remove from TAL if: Score < [X] OR 18+ months with zero intent signal

---

DELIVERABLE 5 — 90-DAY LAUNCH ROADMAP

Week 1-2: Foundation
- [ ] Align Sales VP + CMO on tier criteria and resource commitments (the ABM charter)
- [ ] Pull initial TAL from CRM + intent data — score all accounts
- [ ] Executive review and assign first Tier 1 accounts (target: [X] accounts for pilot)
- [ ] Set up CRM fields: Tier assignment, TAL flag, Account owner, ABM entry date
- [ ] Stand up intent data feed and account scoring in [PLATFORM]

Week 3-4: Pilot Preparation
- [ ] Brief AEs on Tier 1 accounts: research brief template, role, and weekly commitment
- [ ] Create first Tier 1 account research package (template + example)
- [ ] Build Tier 3 programmatic infrastructure: LinkedIn matched audience + display targeting live
- [ ] Set up account-level reporting dashboard in [TOOL]
- [ ] Define MQA (Marketing Qualified Account) threshold: what signals trigger SDR outreach

Week 5-8: Pilot Launch
- [ ] Launch Tier 1 outreach for [X] pilot accounts (AE + SDR + marketing pod coordinated)
- [ ] Launch Tier 3 programmatic display and LinkedIn for full TAL
- [ ] Run first Tier 2 cluster campaign for highest-priority segment
- [ ] Weekly ABM pod standup: 30 min, review account activity, coordinate next actions
- [ ] First pipeline review at Day 45: how many Tier 1 accounts have active pipeline?

Week 9-12: Scale and Optimize
- [ ] Full Tier 1 activation (all accounts assigned, pods running)
- [ ] Tier 2 second cluster launched
- [ ] ABM measurement framework live: pipeline influenced, account engagement score, MQA conversion
- [ ] First retrospective: kill programs that aren't generating engagement after 60 days
- [ ] 90-day board report: ABM pipeline created vs. target, Tier 1 meetings booked

---

DELIVERABLE 6 — MEASUREMENT FRAMEWORK & GOVERNANCE

A. Program-Level KPIs (Reviewed Monthly by CMO + VP Sales)
- Tier 1 account coverage: % of Tier 1 accounts with active pipeline
- ABM-influenced pipeline: $ value of pipeline where ABM program touched the account before opportunity creation
- ABM win rate: Close rate on ABM-touched opportunities vs. non-ABM baseline
- Account engagement score: Average engagement score across Tier 1 TAL
- MQA conversion: % of MQAs that convert to sales-accepted opportunities

B. Tier-Level KPIs (Reviewed Weekly by ABM Manager)
- Tier 1: Meetings booked per Tier 1 account per quarter / Pipeline created per Tier 1 account
- Tier 2: Cluster engagement rate / MQLs per cluster / Pipeline influenced per cluster
- Tier 3: Account-level impression-to-engagement rate / Programmatic MQL volume / Cost per MQA

C. The "ABM Red Line" — When to Kill an Account
- Tier 1 accounts with zero engagement after [X] months → demote to Tier 2 or remove from TAL
- Tier 2 clusters with < [X]% engagement rate after [Y] touches → dissolve cluster and reclassify
- Tier 3 accounts with zero intent signal for [X] months → archive from TAL

D. Quarterly ABM Business Review (QBR) Agenda
1. Pipeline performance: ABM-influenced vs. target
2. Tier health: How many accounts per tier, movement between tiers
3. Program audits: Which Tier 1 accounts to continue vs. retire
4. Budget vs. actuals: CPL, cost per opportunity, ABM ROI vs. non-ABM channels
5. Next quarter TAL refresh: New accounts to add, accounts to remove

---

## Example Input/Output

**Input Example:**
- Company: Veridian Data (enterprise data governance SaaS)
- Product: AI-powered data catalog and governance platform
- ICP: Enterprise companies, 1,000+ employees, US/EU, using Snowflake or Databricks, with a Chief Data Officer or VP of Data Engineering
- ACV: $120,000–$400,000
- Total target accounts in CRM: 1,800
- Sales team: 8 AEs (enterprise), 6 SDRs
- Marketing for ABM: 2 FTEs + $180,000/quarter budget
- ABM maturity: Pilot (running 15 accounts loosely, no formal tier system)
- ABM frustration: "Sales says they're 'doing ABM' on 200 accounts. Nothing is personalized. Pipeline is flat."

**Output Example (excerpt):**

**ABM Tier Architecture for Veridian Data:**

Recommended tier model: 3-tier with a hard Tier 1 cap of 30 accounts (not 50 — at 2 marketing FTEs this is the honest capacity ceiling).

**Tier 1 — Strategic 1:1 (Maximum: 30 accounts)**
Qualification criteria (ALL required):
- ACV opportunity ≥ $200K (minimum, based on the math of 2 FTEs × $6K marketing investment per account per quarter)
- ICP fit score ≥ 80/100 (using Snowflake/Databricks technographic + 1,000+ employees + CDO/VP Data present in CRM)
- One of: Board intro, active champion at Director+ level, or 6sense Tier 4/5 buying stage
- Strategic value: Qualifies as a reference account for the company's top 3 target verticals (Financial Services, Healthcare, or Retail)

Who gets fired from Tier 1 immediately:
- The 8 accounts AEs have "claimed" for 2+ years without active pipeline movement — they get moved to Tier 2
- Any account where the AE hasn't had contact with the champion in 90 days

**Tier 1 program per account:**
- Monthly research brief: 2 hours marketing to produce, AE reviews on Monday standup
- One executive outreach per quarter: CEO or CMO personal email to CDO/CTO at the account — not a template
- One bespoke content asset per quarter: Account-specific data maturity benchmark comparing their industry peers
- Sendoso gift triggered by: Champion advancing to next stage in deal OR champion sharing our content externally
- Account microsite on Mutiny: Personalized homepage showing their industry + tech stack language
- Monthly 30-min ABM pod standup: AE + SDR + Marketing discussing next actions

**Resource math:**
- Marketing capacity for Tier 1: 2 FTEs × 160 hours/month = 320 hours total. Tier 1 allocation = 50% = 160 hours ÷ 30 accounts = 5.3 hours per account per month. This is sustainable but leaves no slack — hire a third ABM specialist within 6 months.
- Budget per Tier 1 account: $180K/quarter × 40% Tier 1 = $72K/quarter ÷ 30 accounts = $2,400 per account per quarter. This covers: $800 Sendoso, $600 intent data allocation, $1,000 content production.

**Tier 2 — Cluster 1:Few (150 accounts across 5 clusters)**
Cluster 1: Financial Services data leaders at banks/insurers using Snowflake (30 accounts)
Cluster 2: Healthcare analytics and data engineering teams under HIPAA compliance pressure (25 accounts)
Cluster 3: Retail/e-commerce CDOs managing ML/AI data pipelines (30 accounts)
Cluster 4: Snowflake-first companies where 6sense shows Stage 3 intent (35 accounts)
Cluster 5: Accounts where a champion recently changed jobs to a new company (30 accounts — champion tracking list)

**Tier 2 per cluster program:**
- Cluster-specific white paper: "The [Industry] CDO's Data Governance Benchmark 2026" — 4 versions, one per industry cluster
- LinkedIn matched audience campaign: All 30-35 accounts in the cluster, document ad driving to benchmark report
- SDR sequence: 5-touch industry-specific sequence (not a generic sequence — references industry regulation or trend)
- Webinar invitation: Virtual roundtable for each cluster (minimum 10 RSVPs before hosting)

**Tier 3 — Programmatic (remaining 1,620 accounts)**
- LinkedIn: Firmographic-matched audience (job titles: CDO, VP Data Engineering, VP Analytics, Head of Data Governance at 1,000+ employee companies)
- Programmatic display via 6sense: All 1,800 TAL accounts, zero intent signal required
- Content syndication: Topic category "data governance" + "data catalog" on TechTarget, with lead threshold set at 50-point MAP score before routing to SDR
- Automated email: Monthly newsletter with data governance industry content — no selling, pure education

**The honest truth:**
Veridian's current "200 account ABM program" is Tier 3 programmatic at best. By concentrating resources into 30 true Tier 1 accounts with proper investment per account, pipeline conversion should increase 3–4x compared to the spray-and-pray approach. The key organizational change: Sales VP must agree that AEs can only "own" 5 Tier 1 accounts maximum — not 25.

---

## Success Metrics

- Tier 1 account coverage rate ≥ 80% (active pipeline exists in ≥ 80% of Tier 1 accounts within 6 months)
- ABM-influenced win rate ≥ 1.5× company baseline win rate
- ABM-influenced ACV ≥ 1.3× non-ABM ACV (account focus drives larger deal sizes)
- Tier 1 meeting booked rate ≥ 60% of accounts within 90 days of program entry
- MQA-to-SQL conversion ≥ 35% (ABM MQAs should be much higher quality than standard MQLs)
- Tier 2 cluster engagement rate ≥ 25% of cluster accounts showing measurable engagement within 60 days
- ABM pipeline as % of total pipeline ≥ [target based on headcount investment — if 30% of marketing effort goes to ABM, pipeline contribution should be ≥ 40% given higher win rate]

## Related Prompts

- [ABM Target Account List Building & ICP Scoring Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-ABM-Target-Account-List-Building-&-ICP-Scoring-Intelligence-Engine.md)
- [ABM Buying Committee Engagement & Multi-Stakeholder Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Buying-Committee-Engagement-&-Multi-Stakeholder-Intelligence-Engine.md)
- [ABM Program Measurement & Revenue Attribution Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Program-Measurement-&-Revenue-Attribution-Intelligence-Engine.md)
- [Named Account Hyper-Personalization & 1-to-1 ABM Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/Named-Account-Hyper-Personalization-&-1-to-1-ABM-Intelligence-Engine.md)

## Integration Tips

- **Salesforce**: Add custom fields for "ABM Tier" (picklist: Tier 1 / Tier 2 / Tier 3 / Not in TAL), "TAL Entry Date", "ABM Pod Owner" (marketing contact), and "Account Engagement Score" — use these to filter reports, build SDR queues, and trigger assignment rules. Create an ABM Dashboard using these fields so sales and marketing share a single view of account status.
- **HubSpot**: Use Company Properties to tag ABM tier, then build Workflows that automatically enroll companies into tier-specific email sequences, update list memberships for LinkedIn Matched Audiences, and notify the ABM pod owner via Slack when a Tier 1 company reaches an engagement threshold.
- **6sense or Demandbase**: Use the platform's account scoring + intent data to auto-populate Tier 3 eligibility and surface Tier 2 graduation candidates. Set up weekly Slack digest: "These 5 Tier 3 accounts hit intent threshold this week — review for Tier 2 promotion."
- **LinkedIn Campaign Manager**: Build one Matched Audience per ABM tier — upload CRM lists segmented by tier. Tier 1 gets highest frequency cap and most personalized creative; Tier 3 gets broad awareness creative at lower spend per account. Refresh lists every 30 days as tier assignments change.
- **Sendoso or Reachdesk**: Program trigger-based gifts: Tier 1 account champion views your ROI calculator → trigger review alert for AE → AE approves → Sendoso sends curated gift automatically. No manual process needed.
- **Gong / Chorus**: Build an "ABM Call Intelligence" tracker in Gong — tag all calls from Tier 1 accounts, track which accounts have had executive-level conversations vs. SDR-only contact, surface accounts where the conversation went cold (no calls in 30+ days as a warning flag).
- **Notion or Confluence**: Build an ABM Account Wiki — one page per Tier 1 account with: research brief, stakeholder map, prior outreach log, open pipeline opportunities, and next actions. Zapier or Make can auto-populate the page template from Salesforce data when an account is promoted to Tier 1.
- **Zapier or Make**: Automate tier change notifications — when an account's ABM Tier field changes in Salesforce, trigger: Slack notification to the ABM pod, email enrollment change in HubSpot, LinkedIn audience list refresh, and Notion page creation/archive.

## Troubleshooting

**Problem: Sales claims to be "doing ABM" on 200+ accounts but pipeline conversion hasn't improved and marketing feels like they're running a glorified email blast**
Solution: This is "ABM theater" — the most common ABM failure mode. Run the coverage math from Deliverable 2 and show the leadership team exactly how many hours of personalized attention your team can sustainably provide per account. At 2 marketing FTEs, genuine Tier 1 ABM on more than 30-40 accounts is mathematically impossible. The fix requires organizational courage: fire 80% of the "Tier 1" accounts back to Tier 3 programmatic, and invest deeply in the remaining 20-30. This conversation is easier when backed by the math.

**Problem: ABM-influenced pipeline numbers look great in the dashboard but revenue conversion isn't improving — closed deals from ABM aren't materially different from non-ABM**
Solution: This usually means the ABM program is adding engagement theater (impressions, clicks, content downloads) without actually changing the sales dynamic at the account. Audit Tier 1 program execution: Are AEs actually using the account intelligence briefs? Are executive connections being made or just being noted as "planned"? Are champions being mobilized internally or just receiving nurture content? Shift Tier 1 KPIs from engagement metrics to "executive meetings held" and "champion-sourced internal intros" — behaviors that actually compress sales cycles and change win probability.

**Problem: Tier assignment keeps changing — accounts move between tiers monthly, creating program instability and AE frustration**
Solution: Implement a "TAL freeze" policy — tier assignments are locked for the quarter except in cases of extreme signal change (account acquired, champion leaves company, etc.). Run a quarterly TAL refresh in the last 2 weeks of each quarter, promote/demote at quarter boundaries, not ad hoc. This predictability lets AEs plan their account strategy and lets marketing build content without it being obsoleted by tier reassignment.

## Version History
- v1.0: Initial creation (auto-generated)
