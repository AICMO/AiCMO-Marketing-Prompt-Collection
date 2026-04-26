# AI-Powered B2B Intent-Signal-Activated Account Advertising & Programmatic ABM Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** programmatic-abm, intent-data, account-based-advertising, b2b, 6sense, demandbase, bombora, demand-gen, pipeline-velocity

## Overview

Builds and deploys an intent-signal-activated programmatic ABM advertising engine that identifies in-market accounts from third-party intent data, triggers coordinated ad campaigns across display, paid social, and CTV, and aligns spend dynamically to accounts showing the strongest buying signals. Use this when launching an account-based advertising motion, standing up a 6sense/DemandBase paid program, or coordinating programmatic spend with sales prospecting to accelerate pipeline from a named target account list.

## Quick Copy-Paste Version

You are a B2B programmatic ABM advertising strategist. Build an intent-signal-activated account advertising program for the following company:

Company: [Your Company Name]
Product/Service: [What you sell and who you sell to]
ICP: [Industries, company sizes, buyer titles]
Target account list size: [Number of named accounts]
Monthly ABM advertising budget: $[X]
Pipeline goal (next 90 days): $[X] in sourced or influenced pipeline
Intent data sources available: [Bombora / G2 / TechTarget / 6sense / DemandBase / None yet]
ABM platform (if any): [6sense / DemandBase / RollWorks / Terminus / None]
Top intent topics/keywords your buyers research: [e.g., "data warehouse migration," "SOC2 compliance," "HR automation"]
Top 3 competitors: [List them]

Deliver:
1. Intent signal tiering framework: how to prioritize accounts by signal strength (Hot / Warm / Cold)
2. Ad campaign triggers: which signals fire which campaign types
3. Channel orchestration plan: how display, LinkedIn, and CTV work together for the same account
4. Creative messaging matrix by buying stage and persona
5. Bid optimization rules: how to increase/decrease spend as account intent signals change
6. 30/60/90-day pipeline contribution forecast with assumptions
7. Sales + marketing alert system: when and how to hand off surging accounts to SDRs
8. Week 1 activation checklist

Format as an executable program brief a demand generation manager can implement immediately.

## Advanced Customizable Version

# ROLE
You are a senior B2B programmatic ABM strategist with deep expertise in intent data activation, account-based advertising orchestration, and revenue attribution. You have built intent-activated paid programs for B2B SaaS companies ranging from $10M to $800M ARR and are fluent in Bombora, G2 Buyer Intent, TechTarget Priority Engine, 6sense, DemandBase, RollWorks, Terminus, The Trade Desk, LinkedIn Campaign Manager, and CTV/OTT platforms. You understand how to connect third-party intent signal data to paid media activation and how to measure programmatic ABM impact on pipeline without relying on last-touch attribution.

# CONTEXT
**Company:** [Company Name]
**Industry vertical:** [e.g., HR Tech, Cybersecurity, FinTech, DevTools, Supply Chain]
**Stage:** [Series B / Growth / Scale / Enterprise]
**ARR / Revenue:** [$X]
**ACV (average contract value):** [$X]
**Sales cycle length:** [X weeks/months]
**ICP definition:**
  - Firmographics: [Industries, company size by headcount/revenue, geographies]
  - Buyer titles: [e.g., CISO, VP of HR, CFO, CTO, Head of Procurement]
  - Technographics: [Tools they use — triggers for displacement or integration]
  - Negative ICP signals: [Company sizes, industries, or technographics to exclude]
**Target account list (TAL):** [X named accounts / Tier 1: X accounts, Tier 2: X accounts, Tier 3: X accounts]
**Monthly ABM advertising budget:** [$X — or "not yet allocated"]
**Pipeline goal (90-day):** [$X sourced pipeline, $X influenced pipeline from ABM program]
**Current attribution model:** [First touch / Last touch / Account-level influence / None]
**Intent data sources available:**
  - Third-party: [Bombora topics, G2 buyer intent, TechTarget Priority Engine, IDG / Activate, Spiceworks / Other]
  - First-party: [Website visitor data via 6sense, DemandBase, Clearbit Reveal, or Koala — or "None"]
  - CRM intent signals: [Salesforce activity, HubSpot page-visit scoring, product trial data]
**ABM platform:** [6sense / DemandBase / RollWorks / Terminus / Jabmo / None — building from scratch]
**Paid channels currently active:** [Google Display / LinkedIn / The Trade Desk / CTV / Other]
**Sales team structure:** [SDR team size, territory model, AE coverage for target accounts]
**Top intent topic clusters your buyers research:** [List 5–10 topic categories]
**Top 3 competitors to conquest-target:** [Competitor A, B, C]
**Key differentiators:** [What makes you meaningfully better for in-market buyers]
**Available creative assets:** [Banner ads, video, thought leadership content, ROI calculators, case studies]

# OBJECTIVE
Produce a complete, immediately deployable intent-signal-activated programmatic ABM advertising program that:
- Identifies and tiers accounts by real-time buying intent before sales engagement
- Triggers coordinated cross-channel ad campaigns automatically as signal strength changes
- Concentrates spend on accounts with the highest propensity to buy, reducing wasted impressions on non-ICP audiences
- Creates surround-sound awareness across every digital touchpoint a target account's buying committee visits
- Hands off surging accounts to SDR/AE teams with full context on what signals triggered the escalation
- Generates measurable pipeline influence attributable to the ABM advertising motion

# DELIVERABLES

## 1. Intent Signal Intelligence Architecture

Design the full signal-capture and scoring framework:

**Third-Party Intent Signal Sources:**
- Bombora Company Surge: Which topic clusters to monitor (map to your solution categories, competitor names, and pain point terms); surge score threshold for activation (typically 60+ = warm, 80+ = hot)
- G2 Buyer Intent: Categories to monitor; competitive product pages to track; buyer intent signal types (category research, competitive comparison, vendor review)
- TechTarget Priority Engine: Which technology categories and editorial sections indicate in-market buyers; how to sync Priority Engine accounts to your CRM
- Additional sources to evaluate based on ICP: IDG/Activate for enterprise IT buyers; Spiceworks for SMB IT; Bombora B2B Data Co-op topics specific to your vertical

**First-Party Intent Signals:**
- Website engagement scoring: Assign intent scores to page types (pricing page = 25 pts, competitor comparison page = 20 pts, ROI calculator = 30 pts, blog post = 5 pts, careers page = -10 pts)
- Product trial/freemium signals: Time-in-product, feature adoption milestones, team invitations, admin actions
- CRM engagement signals: Opened email sequences, attended webinars, downloaded gated content (score each signal)
- Reverse IP/company identification: 6sense, DemandBase, Clearbit Reveal, or Koala for anonymous visitor account matching

**Intent Score Composite Model:**
Build a composite account intent score combining:
- Third-party intent spike weight: 40%
- First-party website engagement weight: 35%
- CRM historical engagement weight: 15%
- Firmographic ICP fit score weight: 10%

Produce a scoring rubric and threshold definitions:
| Tier | Composite Score | Label | Action |
|---|---|---|---|
| Tier 1 | 85–100 | Active Buying | Immediate SDR outreach + maximum ad spend |
| Tier 2 | 65–84 | Researching | Escalated ad spend + SDR alert |
| Tier 3 | 45–64 | Early Awareness | Base-level ad spend + content nurture |
| Tier 4 | < 45 | Passive | Minimal spend / audience suppression |

## 2. Campaign Trigger Architecture

Define the automated rules that activate, escalate, and pause campaigns based on signal changes:

**Signal-to-Campaign Trigger Map:**
For each signal event, specify:
- Trigger condition (e.g., "Bombora surge score crosses 75 on 'data warehouse' topic")
- Campaign activated (e.g., "LinkedIn Sponsored Content: 'Why [Company] customers 3x their data query speed'")
- Channel orchestration (which channels activate simultaneously vs. sequentially)
- Budget adjustment (e.g., "Increase account's daily impression share by 40%")
- Duration (e.g., "Run at elevated spend for 21 days, then return to base if no further signals")
- Sales alert (e.g., "Auto-create Salesforce task for assigned AE with signal summary")

**Standard Trigger Scenarios to Define:**
1. New account enters TAL with high ICP fit but no intent signals → TOFU campaign activated
2. Existing TAL account shows first Bombora surge → MOFU campaign escalated + SDR alerted
3. Account visits pricing page or competitor page → BOFU retargeting campaign activated immediately
4. Account shows competitive intent signals (visiting competitor G2 page) → Conquest/displacement campaign triggered
5. Account intent score drops below threshold for 14 days → Campaigns paused / budget reallocated
6. Account becomes closed-won → Immediately suppressed from all acquisition campaigns; onboarding campaign activated

## 3. Cross-Channel Orchestration Plan

Design the "surround-sound" advertising experience for each tier of target account:

**Channel Roles in the ABM Advertising Mix:**

**Programmatic Display (via DSP: The Trade Desk, DV360, or ABM platform native):**
- Role: Brand awareness and content distribution at scale; IP-targeting for accounts on TAL
- Targeting method: IP address targeting (via 6sense/DemandBase account list) + cookie-based retargeting
- Ad formats: 300×250, 728×90, 160×600 (standard IAB); rich media for Tier 1 accounts
- Frequency cap: 15–25 impressions per week per account for Tier 1; 5–10 for Tier 2/3
- Creative strategy: Stage-appropriate messaging (thought leadership for TOFU; proof/ROI for MOFU; urgency/offer for BOFU)
- Publisher quality: Exclude low-quality MFA sites; prioritize endemic B2B publishers (trade pubs for your vertical), news sites, and LinkedIn Audience Network as a supplement

**LinkedIn Ads (Matched Audiences + Account Targeting):**
- Role: Precision targeting of named buying committee members by title at target accounts
- Targeting method: Company name list upload (TAL) combined with job title/seniority targeting; Matched Audiences from CRM contact list
- Campaign types:
  - TOFU: Thought Leader Ads (executive posts boosted to target accounts' personas); Sponsored Content (carousel or single image)
  - MOFU: Lead Gen Forms for ungated case studies or assessment tools; Conversation Ads for Tier 1 accounts
  - BOFU: Message Ads (InMail) to economic buyers at accounts with high intent score; Sponsored Content with direct demo CTA
- Frequency cap: 4 ads per week per member for Tier 1 accounts
- Bid strategy: Cost Cap for Tier 1 (protect CPL), Maximum Delivery for Tier 2/3 TOFU

**Connected TV / OTT (for accounts with ACV > $50K):**
- Role: Executive-level awareness; breaks through ad blindness by reaching buyers in non-work contexts
- Targeting method: IP-based household targeting matched to TAL account IP ranges; streaming platform partnerships (Hulu, Paramount+, streaming sports)
- Creative format: 15-second and 30-second non-skippable video
- Use case: Tier 1 accounts only; activate when account enters "Active Buying" tier
- Expected reach: 60–75% of target accounts' executive buying committee members in a given month
- Measurement: Brand lift study (aided awareness) for accounts exposed vs. not exposed; pipeline influence by exposed-account cohort

**Retargeting (cross-channel):**
- Website pixel retargeting: Segment by page visited (pricing vs. blog vs. competitor page vs. careers)
- Suppression rules: Exclude current customers, open opportunities (once AE engaged), and employee IP ranges
- Duration: 90-day retargeting window for standard visitors; persistent targeting for TAL accounts regardless of last visit date

## 4. Creative Messaging Matrix

Build a creative brief for each buying stage × persona combination:

**For each cell in the matrix, specify:**
- Primary message angle
- Proof point / social proof to lead with
- CTA (primary and secondary)
- Ad format fit
- Landing page destination

| Buying Stage | Economic Buyer (e.g., CFO/VP) | Technical Buyer (e.g., CTO/IT Director) | End User Champion (e.g., Manager/Analyst) |
|---|---|---|---|
| **TOFU (Unaware / Early Research)** | "Industry benchmark: [Relevant Stat about their pain]" → Benchmark Report | "How [Competitor Stack] companies are switching to [Category]" → Technical Deep Dive | "The [Role] Guide to [Solving Pain]" → Practical Guide |
| **MOFU (Actively Researching)** | "[Customer Logo] reduced [business metric] by X% in 90 days" → Case Study | "Architecture overview: How [Product] integrates with [Their Stack]" → Technical Docs / Sandbox | "Step-by-step: How I [achieved outcome] with [Product]" → Practitioner Story |
| **BOFU (Evaluating Vendors)** | "See [Product] ROI in your numbers: Free 30-min CFO briefing" → Executive Briefing | "Start free, deploy in 48 hours. No procurement required." → Free Trial / POC | "[Your Company] vs. [Competitor]: Side-by-side for [their use case]" → Comparison Page |
| **Competitive Displacement** | "[Competitor] customers report: Top 3 reasons they switched" → Switch Report | "Migration from [Competitor] takes 2 weeks. Here's the playbook." → Migration Guide | "[Competitor] renewal coming up? Here's what [Role] wish they knew." → Switcher Guide |

**Creative Production Requirements per Tier:**
- Tier 1 (Active Buying): Custom creative per account for top 10–20 accounts (personalized with company logo/name in ad; ABM platform dynamic creative)
- Tier 2 (Researching): Persona-level creative (4–6 variants per persona)
- Tier 3 (Early Awareness): Category-level creative (2–3 variants per funnel stage)

## 5. Budget Architecture & Dynamic Spend Optimization

**Base Budget Allocation by Tier:**
| Account Tier | % of Total Budget | Monthly $ | Rationale |
|---|---|---|---|
| Tier 1 (Active Buying) | 50% | $X | Maximum share-of-voice during active evaluation window |
| Tier 2 (Researching) | 30% | $X | Accelerate pipeline entry before competitor mind-share solidifies |
| Tier 3 (Early Awareness) | 15% | $X | Build brand recall so your name is in-set when evaluation begins |
| Reallocation Reserve | 5% | $X | Dynamic reallocation fund for signal surges and test campaigns |

**Dynamic Spend Rules:**
- If Tier 1 account count grows > 25% month-over-month: Transfer 10% from Tier 3 budget to Tier 1
- If an individual account's intent score jumps by ≥ 30 points in one week: Increase that account's CPM target by 50% for 14 days
- If account has no impressions delivered in 14 days (frequency cap/inventory issue): Switch from DSP display to LinkedIn-only for that account
- If account enters pipeline (opportunity created in CRM): Maintain ad exposure but shift creative to "accelerate close" messaging; pause lead generation CTAs

**CPM and CPL Benchmarks by Channel:**
| Channel | Expected CPM | Expected CPL | ABM-Adjusted Target |
|---|---|---|---|
| Programmatic Display (ABM-targeted) | $18–35 | N/A (awareness) | $22 CPM for Tier 1 |
| LinkedIn Sponsored Content | $60–90 CPM | $200–500 | $280 CPL for Tier 1 accounts |
| LinkedIn Lead Gen Forms | N/A | $150–350 | $200 CPL with TAL targeting |
| CTV (Tier 1 accounts) | $35–65 CPM | N/A (awareness) | $45 CPM |
| Retargeting Display | $4–8 CPM | $80–180 | $6 CPM base |

## 6. Sales-Marketing Account Alert System

Define the full handoff protocol between the ABM advertising program and the SDR/AE team:

**Alert Types and Channels:**
- **Immediate Alert (Slack + Salesforce task):** Account enters Tier 1 (Active Buying) for the first time; account visits pricing or demo page; account's economic buyer engages with a LinkedIn Message Ad
- **Daily Digest (Email to AE/SDR):** Summary of all Tier 1 and Tier 2 account signal changes in their territory; top 5 accounts with highest intent score increase in last 24 hours
- **Weekly ABM Intelligence Brief:** Accounts trending up or down by tier; new accounts entering TAL; accounts approaching renewal or competitive review cycle (from Bombora "competitive displacement" topic signals)

**Account Intelligence Package for Sales (auto-generated per Tier 1 account):**
For each account escalated to Tier 1, auto-generate a 1-page account brief containing:
1. Intent signal summary: Which topics they're researching and for how long
2. Channels they've been exposed to: Impressions by channel; ad creative they engaged with
3. Buying committee members identified: Names/titles of people at the account who saw or clicked ads (via LinkedIn insight tag or 6sense person-level data)
4. Recommended outreach angle: Top 1–2 message angles based on which signal triggered the escalation
5. Competitor risk flag: If G2 competitor intent or Bombora competitive topics are present

**Handoff SLA:**
- SDR must attempt first touch within 24 hours of account entering Tier 1
- If no response in 5 business days, advertising shifts to "stale Tier 1" protocol: reduce frequency, add a "re-engagement" creative variant
- If account responds and books a meeting: Immediately suppress from advertising; shift to deal-acceleration creative for stakeholders not yet engaged

## 7. Measurement & Pipeline Attribution Framework

**Primary KPIs for ABM Advertising Program:**
- Account engagement rate: % of TAL accounts with ≥ 1 ad impression per week
- Account pipeline penetration rate: % of TAL accounts that created an opportunity within 180 days
- Pipeline influenced: Total pipeline from opportunities where target accounts received ≥ 3 ad impressions in the 30 days before opportunity creation
- Pipeline velocity uplift: Average days-to-opportunity for ad-exposed accounts vs. non-exposed TAL accounts
- Win rate lift: Win rate for accounts in ABM advertising program vs. outbound-only accounts of equivalent ICP fit

**Attribution Model for ABM Advertising:**
Use an account-level influence model (not contact-level last touch):
- Mark any opportunity where the account appeared in the TAL and received ≥ X impressions within a lookback window (90–180 days) as "ABM Influenced"
- Do not claim "sourced" unless the first pipeline-creating touch came from a paid ad click (rare in ABM; most value is influence, not source)
- Build a matched cohort: Compare accounts in the ABM program against similar ICP accounts not in the program — measure pipeline creation rate difference as the lift attributable to the program

**Weekly Reporting Dashboard (buildable in Salesforce + Tableau/Looker):**
| Metric | Source | Frequency |
|---|---|---|
| Total accounts reached (impressions delivered) | DSP + LinkedIn reporting | Weekly |
| Accounts by tier distribution | ABM platform / CRM | Weekly |
| New accounts entering Tier 1/2 | ABM platform | Daily |
| Pipeline opportunities from TAL accounts | Salesforce | Weekly |
| ABM-influenced pipeline (running total) | Salesforce campaign influence | Weekly |
| Account intent score trends (top 20 accounts) | ABM platform | Weekly |
| Creative performance by stage/persona (CTR, CPL, engagement rate) | Channel platforms | Weekly |

## 8. Pipeline Velocity Forecast Model

**Baseline Assumptions:**
- TAL size: [X accounts]
- % of TAL reached with ≥ 10 impressions per month: Target 70% reach in Month 1, 85% by Month 3
- % of reached accounts that show intent signal escalation: Typically 15–25% of TAL in any given quarter
- % of Tier 1 accounts that convert to pipeline within 90 days of entering Tier 1: Typically 8–15% for well-executed ABM programs (vs. 3–5% for outbound-only)
- Average time from Tier 1 entry to opportunity creation: 21–45 days (dependent on sales cycle and SDR responsiveness)

| Month | Accounts Reached | Tier 1 Accounts | Opportunities Created | ABM-Influenced Pipeline |
|---|---|---|---|---|
| Month 1 | 60–70% of TAL | 8–12% of TAL | 2–4% of TAL | [$ACV × opps created] |
| Month 2 | 75–85% of TAL | 12–18% of TAL | 4–7% of TAL | Cumulative + new |
| Month 3 | 85%+ of TAL | 15–22% of TAL | 6–10% of TAL | Cumulative + new |

**Conservative / Base / Aggressive Scenarios:**
Calculate for each:
- Conservative: 50% of Tier 1 accounts generate pipeline; ACV at 80% of average
- Base: 65% of Tier 1 accounts generate pipeline; ACV at average
- Aggressive: 80% of Tier 1 accounts generate pipeline with strong SDR follow-through; ACV at 115% of average (ABM programs tend to skew larger deal size)

## Example Input/Output

**Example Input:**
Company: Latticework HR
Product: AI-powered workforce planning and headcount analytics platform for mid-market and enterprise
ICP: Chief People Officer, VP of HR, Workforce Planning Director at companies 1,000–10,000 employees in Tech, Financial Services, and Healthcare
Target account list: 350 named accounts (Tier 1: 50, Tier 2: 150, Tier 3: 150)
Monthly ABM advertising budget: $28,000/month
Pipeline goal: $2.1M influenced pipeline in 90 days
ACV: $95,000 | Sales cycle: 3–5 months | MQL→SQL: 22%
Intent data: Bombora (topics: "workforce analytics," "headcount planning," "HR tech"), G2 Buyer Intent (Workforce Management category)
ABM platform: 6sense (Tier 1 accounts with high intent), LinkedIn for all tiers
Top competitors: Workday Adaptive Planning, Anaplan, Planful
Differentiators: Deploys in 6 weeks (vs. 6-month average), native HRIS integrations with BambooHR/Rippling/HiBob, self-service scenario modeling without BI dependency

**Example Output (abbreviated):**

**Account Tier Snapshot (Month 1 projection):**
- Tier 1 (Active Buying, score 85+): 22 accounts showing Bombora surge on workforce analytics topics + G2 category research
- Tier 2 (Researching, score 65–84): 67 accounts showing early-stage signals
- Tier 3 (Early Awareness): 261 accounts at base-level exposure

**Campaign Trigger Example — Tier 1 Account: GlobalFinance Corp (2,800 employees, FinServ):**
- Signal detected: Bombora surge on "headcount planning software" (score: 87) + 3 employees visited competitor's G2 review page
- Trigger fired: LinkedIn Message Ad to VP of HR + Director of Workforce Planning ("How 4 Financial Services firms cut planning cycles by 60% with Latticework") + Programmatic display activated at 20 impressions/week to GlobalFinance IP range + SDR Slack alert created with account brief
- Budget allocated: $480 additional this month for GlobalFinance above base programmatic
- Creative personalized: Dynamic display banner shows "For [Financial Services] teams" header with FS-specific customer logo

**90-Day Pipeline Forecast (Base Case):**
| Month | Tier 1 Accounts | Opp Created | ABM-Influenced Pipeline |
|---|---|---|---|
| Month 1 | 22 | 3 | $285,000 |
| Month 2 | 31 | 5 | $475,000 |
| Month 3 | 38 | 8 | $760,000 |
| **Total** | — | **16** | **$1,520,000** |

*Conservative case: $890K. Aggressive case with strong SDR response rate: $2.3M (38 opps at higher ACV)*

**Budget Allocation:**
| Tier | Monthly $ | Channels |
|---|---|---|
| Tier 1 (50 accounts) | $14,000 (50%) | LinkedIn (60%), Programmatic display (25%), CTV (15%) |
| Tier 2 (150 accounts) | $8,400 (30%) | LinkedIn (70%), Programmatic display (30%) |
| Tier 3 (150 accounts) | $4,200 (15%) | Programmatic display (80%), LinkedIn (20%) |
| Reserve | $1,400 (5%) | Signal surge response fund |

**Week 1 Launch Checklist:**
- [ ] Day 1: Export TAL to CSV; upload to 6sense as target account list; sync to LinkedIn Matched Audiences (allow 24–48hr for matching)
- [ ] Day 1: Install Bombora topics in your intent platform; set alert thresholds (surge score 70+ = Tier 2 alert, 85+ = Tier 1 escalation)
- [ ] Day 1: Connect G2 Buyer Intent to CRM via native integration or Zapier (sync G2 intent accounts daily to Salesforce custom field)
- [ ] Day 2: Create 6sense segments by tier; verify account matching rate (target > 70% of TAL matched to 6sense device graph)
- [ ] Day 2: Build LinkedIn Sponsored Content campaigns per tier with TAL company list targeting; create Message Ad template for Tier 1 direct outreach
- [ ] Day 3: Set up programmatic display campaigns in DSP (or 6sense native display); load banner creative sets; configure frequency caps by tier
- [ ] Day 3: Configure Salesforce workflow rules: when account intent field changes to "Tier 1," auto-create task for assigned AE with account brief template
- [ ] Day 4: Create Slack integration for real-time Tier 1 alerts (6sense webhook → Zapier → Slack channel #abm-hot-accounts)
- [ ] Day 5: QA end-to-end: Verify a test account flows from intent signal → tier assignment → campaign activation → SDR alert. Confirm UTM parameters populate in CRM correctly. Check Salesforce campaign influence is capturing ABM-sourced touchpoints.

## Success Metrics

**Green (ABM program on track):**
- TAL reach: ≥ 70% of target accounts receiving impressions by end of Month 1
- Tier 1 account rate: ≥ 12% of TAL in Active Buying tier by Month 2
- Pipeline penetration: ≥ 6% of TAL converts to opportunity within 90 days
- Account engagement rate: ≥ 25% of Tier 1 accounts show a website visit within 7 days of ad exposure
- SDR follow-through: ≥ 80% of Tier 1 accounts receive first sales touch within 48 hours

**Yellow (investigate):**
- TAL match rate < 55% on LinkedIn or DSP (account list quality or firmographic mismatch)
- Tier 1 accounts not generating pipeline after 45 days (intent data may be lagging; signal quality issue)
- SDR follow-through < 60% (sales and marketing alignment problem)
- LinkedIn CPL rising > 30% above target (audience too narrow; creative fatigue)

**Red (program restructure required):**
- < 40% of TAL accounts reached after 60 days (targeting infrastructure broken; verify IP matching and list sync)
- ABM-influenced pipeline < 40% of forecast (review account tier accuracy; check if intent signals are correlating with actual sales conversations)
- Zero opportunities created from Tier 1 accounts in Month 2 (intent data may not be calibrated to your ICP; run a win/loss analysis on accounts that churned out of Tier 1 without converting)

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Paid-Media-&-Advertising/AI-Powered-B2B-Full-Funnel-Paid-Media-Campaign-Architecture-&-Budget-Velocity-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md`
- `../../05_Analytics-&-Performance/Account-Based-Marketing-Analytics/AI-Powered-ABM-Account-Intelligence-&-Revenue-Attribution-Engine.md`
- `../../05_Analytics-&-Performance/Competitive-Intelligence-Analytics/AI-Powered-Competitor-Ad-Intelligence-&-Counter-Campaign-Strategy-Engine.md`

## Integration Tips

**6sense / DemandBase:**
- Sync your TAL to 6sense as a "segment" — set up automatic tier assignment rules based on intent score thresholds; this drives campaign activation without manual intervention
- Use 6sense's native display advertising as the primary programmatic layer for Tier 1 accounts; it handles IP matching, frequency caps, and creative sequencing automatically
- Enable 6sense → Salesforce sync to push account tier and intent score into the Account object as custom fields; this powers Salesforce workflow alerts for SDRs

**LinkedIn Campaign Manager:**
- Upload your TAL as a "Company List" in LinkedIn Matched Audiences — use company name + website URL for best match rates (target > 70% match)
- Sync your CRM contact list as a "Contact List" to reach known buying committee members directly via Message Ads for Tier 1 accounts
- Install LinkedIn Insight Tag with company-level event tracking to capture account-level engagement data and feed it back into your intent scoring model

**Salesforce + HubSpot:**
- Create a custom Account field "ABM Intent Tier" (picklist: Active Buying / Researching / Early Awareness / Not in Program) synced from your ABM platform
- Build a Salesforce campaign for the ABM program; use Campaign Influence to track every opportunity touched by the program
- Set up a workflow: when ABM Intent Tier = "Active Buying" AND no open Opportunity exists → create a Salesforce Task for the assigned SDR with priority = High and due date = today + 1 business day

**The Trade Desk / DV360:**
- Import your account list as an IP-targeted audience segment; use The Trade Desk's B2B integrations with Bombora to layer intent data on top of IP targeting for highest-precision programmatic delivery
- Set frequency caps at the account level (not cookie level) to prevent oversaturation of individual accounts

**Zapier / Make:**
- Trigger: New account reaches Tier 1 in 6sense → Action: Post to #abm-hot-accounts Slack channel with account name, intent score, triggered topics, and assigned AE/SDR name
- Trigger: Account clicks LinkedIn Message Ad → Action: Update Salesforce account field "Last ABM Engagement" with date and ad content type
- Trigger: Opportunity created for TAL account → Action: Pause all acquisition ad campaigns for that account in LinkedIn and DSP via API call

## Troubleshooting

**Problem: TAL match rate on LinkedIn is only 35–45%, meaning most target accounts are not being reached.**
Fix: LinkedIn match rate depends on how well your account list maps to LinkedIn's company graph. Improve match rates by uploading both company name AND website URL for each account. For accounts with fewer than 200 employees, LinkedIn may have limited data — supplement with programmatic display via IP targeting (6sense or DemandBase can reach accounts that LinkedIn misses). Also verify you're uploading a CSV with the required LinkedIn format (Company Name, Website URL); even minor formatting issues drop match rates significantly.

**Problem: Bombora intent scores are high for many accounts, but none of these accounts are converting to pipeline even after 60 days.**
Fix: High Bombora intent scores indicate research activity, not purchase intent. Validate that the intent topics you're monitoring actually correlate with in-market buyers at YOUR stage: interview your last 10 customers and ask what topics they were researching before buying — recalibrate your topic list based on actual buyer behavior. Also check your account ICP fit: Bombora intent + poor ICP fit = noise. Layer a firmographic fit filter (company size, industry, technographic) on top of intent to create a "fit × intent" score matrix. Run a 90-day retrospective: of your last 20 closed-won deals, how many showed Bombora signals in the 60 days before opportunity creation? If the answer is < 40%, the Bombora data may not be calibrated to your category.

**Problem: SDR team is not following up on Tier 1 alerts, undermining the program's pipeline potential.**
Fix: This is a sales-marketing alignment failure, not a technology problem. Three root causes are common: (1) Alert volume is too high — if SDRs are getting 50+ Tier 1 alerts per week, they stop treating them as urgent; tighten your Tier 1 threshold or limit alerts to genuinely top accounts. (2) Alert context is insufficient — SDRs need to understand WHY an account is hot, not just that it is; enrich alerts with the specific topics, pages visited, and recommended outreach angle. (3) There is no accountability — build a simple SLA dashboard showing SDR follow-through rate by rep; review it in weekly pipeline calls. Offer a 30-minute program briefing to the SDR team explaining what the intent signals mean and how to use them in cold outreach.

## Version History
- v1.0: Initial creation (auto-generated)
