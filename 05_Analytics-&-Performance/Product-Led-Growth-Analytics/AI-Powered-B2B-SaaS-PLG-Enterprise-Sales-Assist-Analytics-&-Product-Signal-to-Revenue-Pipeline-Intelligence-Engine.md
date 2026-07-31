# AI-Powered B2B SaaS PLG Enterprise Sales Assist Analytics & Product-Signal-to-Revenue Pipeline Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** product-led-growth, PLG, PQL, enterprise, sales-assist, pipeline-analytics, product-signals, revenue-intelligence, SaaS-analytics

## Overview
Deploys an AI analytics engine to identify which self-serve product users have crossed the threshold into enterprise-grade usage, measure the revenue contribution of product signals in driving assisted sales pipeline, and build a systematic product-signal-to-sales-handoff motion that accelerates enterprise conversion. Use this when your PLG motion generates strong self-serve adoption but enterprise deals are stalling in the handoff from product to sales, when your SDRs are struggling to prioritize which free or trial accounts to contact, or when you need to measure and prove the revenue contribution of your PLG base to your enterprise ARR.

## Quick Copy-Paste Version

You are a senior PLG-to-enterprise analytics strategist for a B2B SaaS company.

I need an analysis of how our self-serve product usage signals drive enterprise pipeline and revenue. Here is our situation:

Company: [Your Company Name]
Product: [What it does in 1 sentence]
PLG motion: [Freemium / Free trial / Reverse trial / Usage-based free tier]
Enterprise threshold: [What qualifies as an enterprise account — e.g., 25+ seats, $10K+ ACV, specific industries]
Sales-assist trigger: [What currently triggers SDR outreach — e.g., manual, PQL score, account size]
Current free/trial active base: [Number of accounts]
Enterprise ACV range: [$X – $Y/year]
% of enterprise pipeline currently sourced from PLG accounts: [X% or "unknown"]
SDR team size dedicated to PLG expansion: [Number of reps]
Product analytics tool: [Mixpanel / Amplitude / Pendo / Heap / Custom]
CRM: [Salesforce / HubSpot]
Current PQL scoring: [Yes / No / Partial]

Analyze how our PLG base generates enterprise pipeline and produce:

1. PLG-TO-ENTERPRISE PIPELINE CONTRIBUTION ANALYSIS
   - What % of closed enterprise deals in the last 12 months originated from PLG accounts (free/trial/self-serve)?
   - What is the average sales cycle length for PLG-sourced enterprise deals vs. outbound-sourced deals?
   - What is the average ACV of PLG-sourced enterprise deals vs. outbound-sourced deals?
   - What is the win rate for PLG-sourced enterprise opportunities vs. outbound?
   - Calculate the total enterprise ARR contribution from the PLG motion and project it 12 months forward

2. PRODUCT SIGNALS THAT PREDICT ENTERPRISE CONVERSION
   - Identify the top 10 in-product behavioral signals that predict enterprise-scale expansion (beyond individual upgrade to team/org-wide adoption)
   - For each signal: correlation with enterprise deal initiation, median lag from signal to sales conversation, % of enterprise accounts that exhibited this signal before their sales cycle started
   - Identify the "enterprise readiness tipping point": the combination of signals that produces 60%+ probability of an enterprise deal within 90 days

3. SALES-ASSIST TRIGGER ARCHITECTURE
   - Design an enterprise PQL scoring model specifically calibrated for enterprise-scale accounts (different from SMB PQL scoring)
   - Define SDR outreach triggers: which signal combinations should automatically create an SDR task in CRM?
   - Design the optimal SDR outreach message using product usage data as personalization variables
   - Define the SLA for SDR follow-up: what is the maximum acceptable lag between enterprise signal detection and first outreach?

4. PLG-TO-ENTERPRISE FUNNEL METRICS
   - Define the PLG-to-enterprise funnel stages: Free User → Activated User → PQL → SDR Qualified → Enterprise Opportunity → Closed Won
   - For each stage: current conversion rate, revenue at risk if conversion rate improves by 5 percentage points, priority optimization action

5. 90-DAY IMPROVEMENT ROADMAP
   - Week-by-week action plan to improve PLG-to-enterprise pipeline contribution by [target %]
   - Quick wins (low effort, high impact) vs. strategic investments (higher effort, longer payback)

Format output as a PLG Enterprise Intelligence Brief with an enterprise PQL scoring model, signal heatmap, funnel waterfall, and SDR activation playbook.

## Advanced Customizable Version

ROLE: You are an AI-powered PLG Enterprise Revenue Intelligence Engine. You combine the analytical depth of a product data scientist, the pipeline instincts of a VP of Sales, and the customer intelligence of a senior product marketer. Your analysis is designed to be actioned simultaneously by the VP Growth, Head of SDR, VP Sales, and CMO to create a unified product-signal-to-revenue motion.

CONTEXT:
- Company: [Company Name]
- Stage: [Series A / Series B / Growth / Pre-IPO]
- Total ARR: [Current ARR]
- Enterprise ARR (deals >$X ACV): [$X ARR]
- Self-serve / PLG ARR: [$X ARR]
- PLG motion: [Freemium (feature-limited) / Free Trial (X days) / Reverse Trial / Usage-based free tier / Combination]
- Enterprise definition: [Accounts with X+ seats OR $Y+ ACV OR specific industry/size criteria]
- ICP for enterprise: [Company size, industry, job titles in buying committee]
- Sales-assisted threshold: [Pure self-serve below $X ACV; sales-assist for $X–$Y ACV; named AE for $Y+ ACV]
- Current active free/trial/self-serve accounts: [Number]
- Monthly new self-serve signups: [Number]
- SDR team dedicated to PLG expansion (hunting free accounts): [Number of SDRs]
- % of enterprise pipeline currently sourced from PLG accounts: [X% or "under-measured"]
- Average enterprise sales cycle (from first SDR touch to close): [X days]
- Average enterprise ACV: [$X]
- Current PQL scoring model: [Exists / Does not exist / Partial — describe if exists]
- Product analytics stack: [Mixpanel / Amplitude / Heap / Pendo / Segment CDP / Custom data warehouse]
- CRM: [Salesforce / HubSpot]
- In-app messaging: [Intercom / Appcues / Pendo / Custom]
- Current SDR outreach trigger: [Manual review / Automatic alerts / PQL score threshold / Account size only / No systematic trigger]
- Biggest challenge in PLG-to-enterprise conversion: [e.g., "SDRs don't know which accounts to prioritize", "product signals aren't in CRM", "timing of outreach is off", "messaging doesn't use product context"]

OBJECTIVE: Produce a comprehensive PLG Enterprise Revenue Intelligence Report that: (1) quantifies the current and potential revenue contribution of the PLG base to enterprise pipeline, (2) identifies and ranks the product behavioral signals that predict enterprise-scale conversion, (3) builds a deployable enterprise PQL scoring model calibrated for multi-stakeholder, high-ACV deals, (4) designs the SDR outreach trigger architecture and personalization playbook using product signals, and (5) delivers a 90-day roadmap to improve PLG-to-enterprise pipeline contribution with projected ARR impact.

---

MODULE 1: PLG-TO-ENTERPRISE REVENUE CONTRIBUTION ANALYSIS

Enterprise Pipeline Source Attribution:
Segment your closed enterprise deals over the last 12 months into:
- PLG-originated: account had at least one self-serve free/trial user before the sales cycle initiated
- Partner-sourced: deal first identified through a channel partner
- Outbound-sourced: SDR or AE prospected the account with no prior PLG engagement
- Inbound non-PLG: account came inbound (event, content, referral) without prior product engagement
- Customer expansion: existing paid customer expanding to new department or product line

For PLG-originated enterprise deals, calculate:
- % of total enterprise deals (volume)
- % of total enterprise ARR (revenue weight)
- Average ACV: PLG-originated vs. non-PLG
- Win rate: PLG-originated vs. non-PLG
- Average sales cycle length: PLG-originated vs. non-PLG
- Average days from first free user signup to enterprise deal close (full cycle length)
- Net Revenue Retention at 12 months: PLG-originated customers vs. outbound-sourced customers

Revenue Opportunity Sizing:
Calculate the "PLG revenue multiplier": for every 100 new self-serve accounts you acquire, how many ultimately generate enterprise pipeline, and at what average ACV?

Example calculation framework:
- 100 new self-serve accounts → X accounts reach PQL threshold (X%) → Y accounts enter sales pipeline (Y% of PQL) → Z accounts close as enterprise deals (Z% win rate) → $A ARR contribution per 100 accounts

Identify the "enterprise extraction rate": the % of your total self-serve base that converts to enterprise ACV in a 24-month window. Best-in-class PLG-to-enterprise companies (Notion, Linear, Figma, Canva enterprise) achieve 8–15% enterprise extraction from their self-serve base.

Forward-Looking Revenue Model:
Project enterprise ARR contribution from PLG base over next 12 months under three scenarios:
- Base case: current extraction rate maintained
- Upside case: extraction rate improves 30% through improved signal detection and SDR targeting
- Best case: extraction rate reaches top-quartile benchmark for your category

---

MODULE 2: ENTERPRISE-PREDICTIVE PRODUCT SIGNAL ANALYSIS

Signal Discovery Framework:
Analyze in-product behavioral events to identify the strongest predictors of enterprise-scale expansion within 90 days. Separate from SMB PQL signals — enterprise signals reflect organizational-scale adoption, not just individual-user intensity.

ENTERPRISE SIGNAL CATEGORIES:

Category 1 — Multi-User & Organizational Expansion Signals
These signals indicate that usage is spreading beyond a single champion to become organizational:
- Signal: Multiple departments/teams using the product (detected by email domain diversity of invited users or different workspace structures)
- Signal: Seat count growth rate exceeding X seats per week over a 30-day window
- Signal: Organic invitation velocity — users inviting colleagues without being prompted, at rate of X+/month
- Signal: Multiple distinct job titles active in the account (e.g., both technical and business users)
- Signal: Cross-functional projects created (detected by project tags, names, or integrations with different tools)
- Signal: Admin role assignments to users beyond the original signup (suggests IT/ops involvement)

Category 2 — Enterprise Feature Exploration Signals
These signals indicate the account is evaluating enterprise-grade capabilities:
- Signal: First visit to enterprise/pricing page by a non-primary user (e.g., someone in IT or Finance exploring)
- Signal: SSO/SAML setup attempted (strong signal of IT involvement in evaluation)
- Signal: Audit log or compliance feature accessed
- Signal: Admin console or workspace-level settings accessed by new user (not original signup)
- Signal: API usage exceeding X calls per day (indicates technical integration investment)
- Signal: Integration with enterprise tools (Salesforce, Workday, ServiceNow, SAP) connected

Category 3 — High-Value Use Case Signals
These signals indicate the product is being used for mission-critical or revenue-generating workflows:
- Signal: Project/workspace created with names suggesting strategic importance (e.g., "Q3 Strategy", "Board Review", "Customer X Launch")
- Signal: Volume of data processed or records created crosses a threshold suggesting production-level use
- Signal: Recurring, daily active usage by 5+ users over 30+ consecutive days (habitual dependency signal)
- Signal: Export/report generation frequency suggesting the product output is being shared externally (to clients, leadership, board)

Category 4 — Buying Committee Activation Signals
These signals indicate that people beyond the original champion are evaluating the product for purchase:
- Signal: New user signup from a VP+ or C-suite email domain (e.g., someone with "VP", "Chief", "Director" in their title joins the account)
- Signal: Second-visit pattern from IT security or procurement email domains (evaluating for enterprise purchase)
- Signal: A user requests SSO, compliance documentation, or security review materials through support
- Signal: Account domain matches a known ICP account in your CRM that has no active opportunity (indicates shadow evaluation)

For each signal category, provide:
- Correlation with enterprise deal initiation within 90 days (0–1 scale)
- Median lag from signal occurrence to enterprise deal creation in CRM
- % of enterprise accounts that exhibited this signal before their sales cycle started
- % of non-enterprise accounts that also exhibit this signal (false positive rate)
- Signal tier: Tier 1 (high correlation, low false positive) / Tier 2 (moderate) / Tier 3 (weak or noisy)

Enterprise Readiness Tipping Point:
Identify the specific combination of signals whose co-occurrence produces ≥60% probability of an enterprise deal initiating within 90 days. 

Example tipping point format: "Accounts that have [5+ unique users from 2+ departments] AND [accessed SSO settings or API quota] AND [seat growth rate of 3+ seats in last 30 days] AND [have been active for 45+ days] show enterprise deal initiation at 67% within 90 days."

Provide the SQL or pseudocode query to identify accounts meeting this tipping point in your product analytics warehouse or CRM.

---

MODULE 3: ENTERPRISE PQL SCORING MODEL

Enterprise PQL Scoring Architecture:
Build a composite Enterprise Product Qualified Lead score (0–100) calibrated specifically for enterprise-scale signals. Note: this is distinct from an SMB PQL score — enterprise PQL scores weight organizational breadth, buying committee signals, and enterprise feature engagement more heavily than individual-user activity intensity.

ENTERPRISE PQL SCORING DIMENSIONS:

Dimension 1 — ORGANIZATIONAL BREADTH (0–30 points)
This dimension measures how widely the product has spread within the account, which predicts organizational dependency and enterprise buying committee formation.
- Unique active users in last 30 days:
  * 1–4 users = 0 pts
  * 5–9 users = 10 pts
  * 10–19 users = 20 pts
  * 20+ users = 30 pts
- Departments represented (detected by job title diversity or workspace structure):
  * 1 department = 0 pts bonus
  * 2 departments = +5 pts bonus
  * 3+ departments = +10 pts bonus (cap total dimension at 30)

Dimension 2 — BUYING COMMITTEE SIGNAL STRENGTH (0–25 points)
This dimension detects whether economic buyers, IT, and procurement are actively evaluating the product.
- VP+ or C-suite user active in last 30 days: +15 pts
- IT-domain email user joined the account: +10 pts
- Security review or compliance materials requested via support: +15 pts (cap at 25)
- Pricing/enterprise page visited by non-primary user: +8 pts
- Multiple users from same account visited pricing page in same 7-day window: +12 pts (cap at 25)

Dimension 3 — ENTERPRISE FEATURE ENGAGEMENT (0–20 points)
This dimension measures whether the account is using or exploring enterprise-grade capabilities that only matter at scale.
- SSO/SAML setup attempted or completed: +20 pts
- API usage >X calls/day for 7+ consecutive days: +15 pts
- Enterprise integration connected (Salesforce, Workday, SAP, ServiceNow): +15 pts
- Audit log, admin console, or compliance feature accessed: +10 pts
- Custom domain or white-label feature used: +10 pts
(Cap at 20 pts)

Dimension 4 — USAGE VELOCITY & EXPANSION RATE (0–15 points)
This dimension measures whether usage is accelerating, which predicts organizational commitment.
- Month-over-month seat growth rate:
  * <10% MoM = 0 pts
  * 10–25% MoM = 5 pts
  * 25–50% MoM = 10 pts
  * >50% MoM = 15 pts
- Active days in last 14 days (% of users with 5+ active days):
  * <25% = 0 pts bonus
  * 25–50% = +3 pts bonus
  * 50–75% = +5 pts bonus
  * 75%+ = +8 pts bonus (cap at 15)

Dimension 5 — ICP FIT & FIRMOGRAPHIC SIGNALS (0–10 points)
This dimension incorporates external firmographic data to weight accounts that match your enterprise ICP.
- Company size (employees):
  * 1–50 = 2 pts
  * 51–200 = 5 pts
  * 201–1,000 = 8 pts
  * 1,001+ = 10 pts
- Industry match to top 3 enterprise verticals: +3 pts if match
- Known CRM account (in your Salesforce/HubSpot): +2 pts
- Funding round in last 12 months (intent to invest/grow): +2 pts

ENTERPRISE PQL TIER THRESHOLDS:
- Score 0–29: Early Self-Serve — nurture with product education, no SDR outreach
- Score 30–49: Developing — enroll in product-led nurture email sequence; monitor weekly
- Score 50–69: Sales-Ready — create SDR task within 48 hours; priority: medium
- Score 70–84: High Priority — create SDR task within 24 hours; priority: high; assign to most experienced PLG expansion rep
- Score 85–100: Immediate Action — SDR contact same business day; alert AE; flag for CMO weekly review if above $50K ACV threshold

---

MODULE 4: SDR OUTREACH TRIGGER ARCHITECTURE & PERSONALIZATION PLAYBOOK

SDR Trigger Design:
Define the automated triggers that create SDR tasks in CRM when enterprise PQL signals are detected. Design for real-time signal processing — SDR contact should occur within the signal's "action window" (the period of highest conversion probability).

TRIGGER 1 — TIPPING POINT REACHED (Immediate SDR Alert):
Condition: Account reaches the "enterprise readiness tipping point" identified in Module 2
CRM action: Create high-priority SDR task, alert SDR team Slack channel, auto-enrich account with Clearbit/6sense firmographics, attach PQL score breakdown as note
SLA: SDR outreach within 4 business hours
Message framework: [See personalization template below]

TRIGGER 2 — VP/C-SUITE USER ACTIVATION (Same-Day SDR Alert):
Condition: A user with VP+/C-suite job title (detected from LinkedIn enrichment or email domain + title) becomes active in a PLG account for the first time
CRM action: Create SDR task linked to the executive's contact record, pull their LinkedIn profile, note their usage activity in the last 7 days
SLA: SDR outreach within 8 business hours
Message framework: "I noticed [Executive Name] at [Company] started using [Product] recently. Given [Company]'s [specific trigger — e.g., recent Series B, hiring push for [role]], I thought it might be worth connecting to share how similar [ICP description] companies are using [Product] at the enterprise level."

TRIGGER 3 — IT/SECURITY EVALUATION DETECTED (Priority SDR Alert):
Condition: IT-domain email user joins account OR SSO setup attempted OR security review materials requested
CRM action: Route to SDR with enterprise IT experience; flag as "enterprise evaluation in progress"; attach enterprise security documentation to outreach
SLA: SDR outreach within 24 hours
Message framework: Focus on enterprise security, compliance, and IT implementation — "It looks like your team is evaluating [Product] at the enterprise level. I'd love to connect you with our enterprise team who can walk you through our SOC 2 Type II compliance, SSO setup, and dedicated CSM program."

TRIGGER 4 — SEAT EXPANSION THRESHOLD (Automated Enrichment + SDR Alert):
Condition: Account crosses X seats (your defined enterprise threshold) organically without purchasing enterprise plan
CRM action: Auto-enrich account; create SDR task; calculate potential ACV based on seat count and enterprise plan pricing; attach usage summary to task
SLA: SDR outreach within 24 hours
Message framework: Reference their team's growth — "I noticed your team has grown to [X] users on [Product]. Many teams at your stage — [X–Y] users across [departments detected] — find significant value in our Enterprise plan, particularly for [specific feature their team size makes relevant: SSO, audit logs, admin controls, volume pricing]."

TRIGGER 5 — HIGH-VALUE INTEGRATION CONNECTED (Warm Signal SDR Alert):
Condition: Account connects a high-value enterprise integration (Salesforce, Workday, ServiceNow, SAP, Snowflake)
CRM action: Create SDR task; note the specific integration; research the account's likely use case
SLA: SDR outreach within 48 hours
Message framework: "Congrats on connecting [specific integration] to [Product] — that's typically a signal that [Product] is becoming mission-critical for [specific workflow]. Wanted to share how [Similar Company in same industry] structured their enterprise rollout to maximize ROI from this exact integration."

SDR Personalization Playbook Using Product Signals:
Each SDR outreach should use at minimum 3 product usage data points as personalization variables. Provide SDR with a "signal briefing" auto-generated from the CRM:

SIGNAL BRIEFING TEMPLATE (auto-populate via CRM enrichment workflow):
Account: [Company Name] | Enterprise PQL Score: [Score/100] | Tier: [Tier]
Signal Summary:
✅ [X] active users from [Y] departments in last 30 days
✅ [Executive Name] ([Title]) became active [X] days ago
✅ Seat growth: [X]% month-over-month
✅ [Integration name] connected [X days ago]
✅ [Enterprise feature] accessed [X] times in last 14 days
Suggested first message angle: [Auto-generated based on highest-weighted signals]
Best-fit enterprise use case: [Auto-suggested based on their most-used features]
Similar customer references: [Auto-matched from customer success database by industry/size/use case]
ACV potential: [$X–$Y estimated based on seat count and enterprise plan pricing]
Urgency: [Hot/Warm/Cool based on signal recency]

---

MODULE 5: PLG-TO-ENTERPRISE FUNNEL ANALYTICS

Define and measure the complete PLG-to-enterprise conversion funnel with revenue impact at every stage:

STAGE 1: NEW SELF-SERVE ACCOUNT
- Metric: Monthly new free/trial accounts created
- Target: Track by cohort month and acquisition channel
- Revenue connection: % of accounts that ultimately reach enterprise deal stage

STAGE 2: ACTIVATED ACCOUNT
- Definition: Account where at least one user has completed core "aha moment" action within 14 days of signup
- Metric: Activation rate (% of new accounts reaching activation)
- Benchmark: 40–60% activation rate for B2B SaaS at your stage
- Revenue connection: Activated accounts are 3–5x more likely to enter enterprise pipeline vs. unactivated accounts
- Action if below benchmark: Revise onboarding sequence to accelerate time-to-aha-moment

STAGE 3: ENTERPRISE PQL (Score ≥50)
- Definition: Account has crossed the enterprise PQL scoring threshold (Score ≥50) based on organizational breadth, buying committee signals, and enterprise feature engagement
- Metric: Enterprise PQL rate (% of activated accounts reaching PQL status within 90 days)
- Benchmark: 5–12% of activated accounts for a PLG+Enterprise motion
- Revenue connection: Calculate total estimated ACV in your enterprise PQL pool at any given time
- Action if below benchmark: Improve in-app activation paths that lead to organizational expansion signals

STAGE 4: SDR QUALIFIED (SQL)
- Definition: SDR has made contact with the account, confirmed enterprise intent or need, and qualified it as a genuine sales opportunity
- Metric: PQL-to-SQL conversion rate (% of enterprise PQLs that SDR converts to SQL)
- Benchmark: 25–40% PQL-to-SQL for PLG-sourced accounts (higher than outbound-sourced because product validation reduces skepticism)
- Revenue connection: Calculate monthly pipeline generated by PLG-sourced SQLs × win rate × ACV
- Action if below benchmark: Improve SDR outreach timing, personalization, and messaging using product signal playbook

STAGE 5: ENTERPRISE OPPORTUNITY (OPEN DEAL)
- Definition: Opportunity created in CRM with defined value and expected close date
- Metric: SQL-to-opportunity rate; average ACV of PLG-sourced opportunities vs. outbound
- Benchmark: 65–80% SQL-to-opportunity conversion for PLG-sourced accounts
- Revenue connection: Total PLG-sourced pipeline value

STAGE 6: CLOSED WON — ENTERPRISE CUSTOMER
- Definition: Enterprise contract signed
- Metric: Win rate, ACV, sales cycle length, time-from-first-PLG-user-to-close
- Benchmark: PLG-sourced win rates should exceed outbound-sourced by 15–25 percentage points (due to product validation removing risk)
- Revenue connection: Cumulative PLG-sourced enterprise ARR

FUNNEL REVENUE IMPACT ANALYSIS:
For each stage transition, calculate: "If conversion rate improves by 5 percentage points, what is the 12-month incremental ARR impact?"

Example calculation:
- Current: 1,000 activated accounts → 80 Enterprise PQLs (8% rate) → 24 SQLs (30% rate) → 16 opportunities → 9 closed (56% win rate) × $35K ACV = $315K ARR
- If PQL rate improves from 8% to 13%: 130 PQLs → 39 SQLs → 26 opps → 15 closed = $525K ARR (+$210K ARR from improving one stage by 5 pp)

---

MODULE 6: 90-DAY PLG ENTERPRISE IMPROVEMENT ROADMAP

Month 1 — Instrument & Baseline (Revenue impact: foundational):
Week 1: Audit product analytics instrumentation — ensure all enterprise signal events (SSO attempts, API usage, multi-department invitations, enterprise integration connections) are tracked in your analytics platform and syncing to CRM
Week 2: Build the Enterprise PQL scoring model in CRM — implement as a computed field, validate against last 6 months of enterprise deals (check: did accounts that became enterprise customers show PQL scores ≥50 before their sales cycle started?)
Week 3: Train SDR team on product signal playbook — run 2-hour workshop on reading the signal briefing, interpreting enterprise PQL scores, and using the 5 outreach trigger templates
Week 4: Establish baseline metrics — lock current PLG-to-enterprise funnel conversion rates at every stage; set 90-day improvement targets by stage

Month 2 — Activate & Optimize (Revenue impact: first incremental pipeline):
Week 5: Go live with automated SDR trigger system — all 5 enterprise triggers creating real-time CRM tasks with pre-populated signal briefings
Week 6: Launch enterprise PQL nurture track — accounts in Score 30–49 range enrolled in automated email sequence with product-context personalization; accounts in 50–69 range get SDR contact within 48 hours
Week 7: Run first PLG pipeline review — CMO, VP Sales, Head of SDR review first cohort of SDR-contacted enterprise PQLs; calibrate trigger thresholds and message templates based on early results
Week 8: Optimize SDR response time — measure time between trigger firing and first SDR contact; target <24 hours for Score 70+ triggers; identify and fix bottlenecks

Month 3 — Scale & Measure (Revenue impact: 12-month ARR projection):
Week 9: Expand enterprise PQL model to all historical self-serve accounts — identify dormant accounts in your free base that would score 50+ today but were never contacted by SDR; launch targeted reactivation sequence
Week 10: Deploy in-app enterprise upgrade paths — for accounts scoring 50+, create personalized in-app moments (Intercom/Appcues) that acknowledge their team's growth and surface enterprise plan benefits specific to their usage pattern
Week 11: First PLG Enterprise Revenue Review — calculate 30-day incremental pipeline generated from PLG motion improvements; compare to baseline; project 12-month ARR impact; present to executive team
Week 12: Lock H2 roadmap — based on 90-day learnings, prioritize next investments: expand SDR team dedicated to PLG expansion, invest in product improvements that accelerate enterprise signals, or launch ABM overlay for high-scoring PQL accounts

NORTH STAR METRICS:
- Primary: % of enterprise pipeline sourced from PLG accounts (target: increase by [X] percentage points in 90 days)
- Secondary: Average time from first free user signup to enterprise deal close (target: reduce by 20%)
- Secondary: PLG-sourced enterprise win rate (target: maintain above non-PLG benchmark)
- Secondary: Enterprise PQL-to-SQL conversion rate (target: >30%)

---

OUTPUT FORMAT:
Produce the complete PLG Enterprise Revenue Intelligence Report as:

1. EXECUTIVE SUMMARY (1 page)
   - Current % of enterprise pipeline from PLG accounts vs. industry benchmark
   - 12-month enterprise ARR opportunity from improving PLG-to-enterprise motion
   - Top 3 highest-impact actions with projected ARR contribution
   - Single most important action to take this week

2. ENTERPRISE PQL SCORING MODEL
   [Complete scoring rubric: 5 dimensions with point allocations, tier thresholds, and SDR action per tier]

3. PRODUCT SIGNAL HEATMAP
   [Table: Signal | Category | Correlation (0–1) | Lag to Deal | Enterprise Coverage % | False Positive Rate | Tier]

4. PLG-TO-ENTERPRISE FUNNEL WATERFALL
   [Stage → Stage: Current Rate | Benchmark | Revenue at Risk | Priority Fix | Owner]

5. SDR TRIGGER ARCHITECTURE
   [5 trigger types: Condition | CRM Action | SLA | Message Framework | Expected Pipeline Lift]

6. 90-DAY ROADMAP
   [Week-by-week: Action | Owner (Product/SDR/Marketing/RevOps) | Success Metric | ARR Impact Estimate]

Calibrate all benchmarks and recommendations to our specific PLG motion type, enterprise ACV range, team size, and current product analytics maturity level.

## Example Input/Output

**Input Example:**

Company: Structify
Product: AI-powered data extraction and structuring platform for business analysts and data teams
PLG motion: Freemium (feature-limited)
Enterprise definition: Accounts with 20+ seats or $15K+ ACV or Fortune 2000 companies
Sales-assist trigger: Currently manual — SDR managers review free accounts weekly and pick outreach targets
Active free base: 2,100 accounts
Enterprise ACV range: $18K – $120K/year
% of enterprise pipeline from PLG: ~22% (partially tracked)
SDR team for PLG expansion: 2 reps
Product analytics: Amplitude
CRM: Salesforce

**Output Example (excerpt):**

**ENTERPRISE PQL SCORING MODEL — STRUCTIFY**

*Dimension 1 — Organizational Breadth (max 30 pts):*
Structify accounts with 10–19 users across 2+ departments score 25 pts. The most common pre-enterprise pattern: 6–8 analysts invite finance and operations colleagues, reaching 12–15 seats within 45 days of signup before IT gets involved.

*Enterprise Tipping Point Identified:*
Structify accounts that have [12+ unique users from 2+ departments] AND [connected Snowflake or BigQuery integration] AND [admin console accessed by a user with IT/Engineering in their title] AND [been active for 30+ days] initiate enterprise sales conversations at **71% within 90 days** (n=41 enterprise deals in last 12 months, 29 showed this combination).

---

**PLG-TO-ENTERPRISE FUNNEL WATERFALL — STRUCTIFY**

| Stage | Current Rate | Benchmark | Revenue at Risk (5pp improvement) | Priority Fix |
|-------|-------------|-----------|-----------------------------------|--------------|
| New Account → Activated | 52% | 55–65% | +$180K ARR | Improve onboarding for data team job titles |
| Activated → Enterprise PQL (≥50) | 6.2% | 8–12% | +$340K ARR | Add org-breadth signals to PQL model |
| Enterprise PQL → SDR SQL | 18% | 25–40% | +$520K ARR | **Highest priority** — SDRs aren't contacting PQLs fast enough (avg 9-day lag vs. 24-hour SLA) |
| SDR SQL → Opportunity | 71% | 65–80% | N/A — above benchmark | Maintain |
| Opportunity → Closed Won | 49% | 45–60% | +$210K ARR | Improve enterprise proof materials and security review acceleration |

**Key Finding:** Structify's biggest PLG-to-enterprise gap is at the PQL-to-SQL stage. SDRs are leaving 82% of Enterprise PQL accounts untouched due to lack of systematic trigger alerts. By implementing automated SDR triggers with signal briefings, the projected 12-month ARR impact is **+$840K from PLG-sourced pipeline improvements alone.**

---

**ENTERPRISE SIGNAL HEATMAP — TOP 5 SIGNALS (STRUCTIFY)**

| Signal | Correlation | Lag to Deal | Coverage | False Positive | Tier |
|--------|-------------|-------------|----------|----------------|------|
| Snowflake/BigQuery/Databricks integration connected | 0.84 | 18 days | 67% of enterprise deals | 12% of SMB accounts | Tier 1 — Golden |
| IT/Engineering-domain user joins account | 0.79 | 22 days | 58% of enterprise deals | 8% of SMB accounts | Tier 1 — Golden |
| 15+ unique users from 2+ departments active | 0.75 | 31 days | 71% of enterprise deals | 4% of SMB accounts | Tier 1 |
| Admin console accessed by non-primary user | 0.68 | 26 days | 52% of enterprise deals | 11% of SMB accounts | Tier 2 |
| API usage >500 calls/day for 5+ consecutive days | 0.61 | 41 days | 44% of enterprise deals | 19% of SMB accounts | Tier 2 |

## Success Metrics

- **PLG-to-enterprise pipeline % increase**: Enterprise pipeline sourced from PLG accounts grows by 15+ percentage points within 90 days of implementing the trigger architecture
- **SDR response time**: Time from enterprise signal detection to first SDR contact drops below 24 hours (from manual/ad hoc baseline)
- **PQL-to-SQL conversion rate**: % of Enterprise PQL (Score ≥50) accounts converting to qualified sales opportunity increases to 30%+ within 60 days
- **Enterprise PQL pool size**: Total estimated ACV in accounts with Enterprise PQL Score ≥50 grows month-over-month as PQL model matures
- **PLG-sourced enterprise ACV**: Average ACV of PLG-originated enterprise deals remains equal to or above non-PLG-sourced enterprise ACV (quality check)
- **Signal coverage audit**: 80%+ of enterprise deals closed in a validation cohort show at least 2 Tier 1 enterprise signals that would have triggered SDR contact using the new system
- **Time-to-enterprise**: Median days from first free user signup to enterprise deal close decreases by 20% within 6 months of deploying the system

## Related Prompts

- [PLG Free-to-Paid Conversion Analytics & Upgrade Trigger Monetization Revenue Intelligence Engine](./AI-Powered-B2B-SaaS-PLG-Free-to-Paid-Conversion-Analytics-&-Upgrade-Trigger-Monetization-Revenue-Intelligence-Engine.md)
- [PLG Onboarding Funnel Analytics & Activation Rate Optimization](./AI-Powered-B2B-SaaS-PLG-Onboarding-Funnel-Analytics-&-Activation-Rate-Optimization-Intelligence-Engine.md)
- [PLG-to-Enterprise ABM Hybrid Motion & Account Expansion Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/AI-Powered-B2B-SaaS-PLG-to-Enterprise-ABM-Hybrid-Motion-&-Account-Expansion-Revenue-Intelligence-Engine.md)
- [Revenue Operations Analytics & GTM Performance Intelligence Engine](../Revenue-Operations-Analytics/AI-Powered-B2B-SaaS-Revenue-Operations-Analytics-&-GTM-Performance-Intelligence-Engine.md)

## Integration Tips

- **Amplitude/Mixpanel**: Build the enterprise signal events as custom event properties with account-level grouping (use Amplitude's "Account Analytics" or Mixpanel's "Group Analytics" to aggregate individual-user events to the account level); create a computed property for "Enterprise PQL Score" that automatically updates as behavioral signals occur; set up Amplitude/Mixpanel → CRM sync via Segment to push PQL scores to Salesforce/HubSpot in real time
- **Salesforce**: Create a custom "Enterprise PQL Score" field on the Account object; build a Process Builder or Flow that auto-creates a Task for the assigned SDR when score crosses 50, 70, and 85 thresholds; use the signal briefing template as the Task description, auto-populated using Salesforce formulas pulling from product analytics fields; integrate with Slack to send SDR alerts to a dedicated #plg-enterprise-signals channel
- **HubSpot**: Use the Workflows tool to create enrollment triggers based on the Enterprise PQL Score custom property; build a dedicated HubSpot dashboard for PLG-to-enterprise funnel visibility that shows each stage conversion rate, updated weekly; use HubSpot Sequences to automate the tier-based SDR outreach cadences with product signal personalization tokens
- **6sense / Bombora / Demandbase**: Layer intent data on top of product signals — accounts showing enterprise-grade product signals PLUS third-party intent for your category are highest priority; use 6sense account scores as the "ICP Fit & Firmographic" dimension in your Enterprise PQL model to avoid building that data in-house
- **Clearbit / Apollo.io**: Enrich account records with firmographic data (company size, industry, funding) automatically when an account is created or when it first crosses a signal threshold; use enriched job titles to detect VP+/C-suite and IT-domain users in the buying committee without requiring manual SDR research
- **Intercom / Appcues**: Use the enterprise PQL score to trigger in-app moments specifically for accounts scoring 50+; show "Your team is ready to scale" banners that surface enterprise plan benefits specific to their most-used features; use the signal briefing data to personalize message content (e.g., "With [X] users across your team using [most-active feature], here's how enterprises like yours unlock [specific enterprise capability]")
- **Gong / Chorus**: After enterprise PLG accounts convert to sales conversations, analyze call recordings to identify which product signal combinations the SDR referenced that resonated most with buyers; use this to continuously refine which signals to include in the signal briefing template

## Troubleshooting

**Problem: Our product analytics aren't instrumented at the account level — we track individual users, not companies, making it impossible to detect multi-user enterprise signals.**
Solution: Start by implementing Segment (or a similar CDP) to group individual user events into account-level aggregates using email domain as the account identifier. In the interim, run weekly SQL queries against your user database to manually identify accounts that have had 3+ distinct users active in the last 30 days — this is enough to start manual SDR outreach targeting while you build proper account-level instrumentation. Add "account ID" as a property on all events in your product analytics tool within the next sprint; this is table-stakes infrastructure for any PLG-to-enterprise motion and should be treated as a P0 engineering task.

**Problem: Our SDR team is skeptical about the quality of PLG-sourced accounts and resists prioritizing them over traditional outbound targets.**
Solution: Run a 30-day retrospective analysis: pull all enterprise deals closed in the last 12 months and check whether the accounts had any self-serve free users before the sales cycle. Share this data — including the win rate comparison, ACV comparison, and sales cycle length difference — with the SDR team in a dedicated working session. SDRs respond to data that shows their quota attainment potential; if PLG-sourced accounts close at 2x the win rate of outbound, SDRs will prioritize them. Additionally, give each SDR a "warmth score" in their signal briefing: "This account has 14 users who have been using [Product] for 47 days — your first call has pre-existing product validation, not a cold pitch."

**Problem: We have enterprise PQL accounts, but SDR outreach isn't converting — accounts ignore or decline the outreach.**
Solution: The most common cause is timing or relevance mismatch. Analyze which specific trigger event the SDR contacted each account on, and cross-reference with conversion rate by trigger type. If outreach tied to "IT user joined account" converts at 3x the rate of "15+ users reached," concentrate SDR resources on the highest-converting triggers and defer or fully automate lower-converting triggers with in-app + email sequences instead. Also review SDR messaging: outreach that explicitly references product usage data ("I noticed your team has grown to 18 users and you recently connected Snowflake") converts at 2–4x higher rates than generic outreach. If reps aren't using the signal briefing, mandate it as part of activity logging in CRM.

## Version History
- v1.0: Initial creation (auto-generated)
