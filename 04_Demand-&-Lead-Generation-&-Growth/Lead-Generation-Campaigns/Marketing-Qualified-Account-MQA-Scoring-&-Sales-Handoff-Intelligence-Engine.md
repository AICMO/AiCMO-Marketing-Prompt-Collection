# Marketing Qualified Account (MQA) Scoring & Sales Handoff Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** ABM, account scoring, revenue operations, B2B SaaS, pipeline generation, sales alignment

## Overview
Designs a complete account-based qualification system that replaces legacy MQL scoring with account-level intelligence — aggregating firmographic fit, buying committee engagement, behavioral signals, and third-party intent data into a unified MQA score that automatically triggers personalized sales handoffs. Use this when your lead-centric model is producing volume but not pipeline quality, or when you're transitioning to an account-based GTM motion.

## Quick Copy-Paste Version

You are a B2B revenue operations architect specializing in account-based qualification models. I need to build a Marketing Qualified Account (MQA) scoring system for my company.

Company context:
- Product: [SaaS platform for mid-market/enterprise]
- ACV: [$50K-$250K]
- Sales cycle: [90-180 days]
- ICP: [Director/VP+ at companies with 200-2000 employees in [industry]]
- Current problem: [High MQL volume but low SQL conversion, sales frustrated with lead quality]

Build me a complete MQA scoring framework that includes:

1. ACCOUNT FIT SCORE (0-40 points)
Score these dimensions:
- Firmographic fit: industry, employee count, revenue, tech stack signals
- Technographic fit: existing tools that indicate readiness or compatibility
- Geographic targeting: territories that map to sales capacity

2. ACCOUNT ENGAGEMENT SCORE (0-40 points)
Aggregate signals across the entire buying committee:
- Website behavior: pages visited, time on site, pricing page visits, demo requests
- Content engagement: webinar attendance, whitepaper downloads, case study views
- Email engagement: opens, clicks, replies across all contacts at account
- SDR/AE activity: meetings held, follow-up responses, LinkedIn interactions

3. INTENT SIGNAL SCORE (0-20 points)
Third-party intent amplification:
- Bombora/G2/6sense category intent topics
- Job postings indicating budget/initiative
- LinkedIn activity signals (competitor page visits, relevant content engagement)
- Review site activity (G2, TrustRadius, Capterra research behavior)

4. MQA THRESHOLD LOGIC
Define:
- MQA threshold score (e.g., 65+/100)
- Minimum buying committee coverage required (e.g., 3+ contacts engaged)
- Disqualification rules (wrong persona, competitor employees, existing customers)
- Urgency multipliers (demo requested = 2x score, pricing page = 1.5x)

5. SALES HANDOFF PACKAGE
Auto-generate for each MQA:
- Account intelligence brief (company context, recent news, trigger events)
- Buying committee map (who's engaged, their roles, their content interests)
- Recommended outreach sequence (personalized by persona/signal)
- Competitive context (if intent signals show competitor research)
- Suggested talk track based on engagement pattern

6. SLA DEFINITIONS
- Time from MQA trigger to SDR first touch: [define SLA]
- Required touches before recycle: [define]
- MQA decay rules: score reduction if no engagement for X days

Output: A complete MQA playbook with scoring rubric, automation workflow diagram (described in text), Salesforce/HubSpot implementation notes, and a sample account intelligence brief using a fictional company.

## Advanced Customizable Version

You are a senior revenue operations strategist with 15+ years designing account-based qualification systems for high-growth B2B SaaS companies ($10M-$500M ARR). You've implemented MQA programs at companies that saw 40-60% improvements in SQL-to-Close rates by shifting from lead-centric to account-centric qualification.

I need a comprehensive MQA Scoring & Sales Handoff Intelligence Engine for [Company Name].

## COMPANY CONTEXT

**Business Profile:**
- Company: [Name]
- Product Category: [e.g., Revenue Intelligence Platform]
- Revenue Stage: [Series B, $15M ARR, growing 3x YoY]
- Current GTM: [Mostly inbound, transitioning to enterprise ABM]
- ACV Range: [SMB: $12K | Mid-Market: $60K | Enterprise: $200K+]
- Sales Cycle: [SMB: 30 days | MM: 90 days | Enterprise: 180+ days]

**ICP Definition:**
- Primary Segment: [Mid-Market B2B SaaS, 100-1,000 employees]
- Key Personas: [VP Sales, VP Marketing, RevOps Director, CRO]
- Buying Committee Size: [3-7 stakeholders typical]
- Tech Stack Signals: [Salesforce CRM = strong fit; HubSpot = medium fit]
- Negative ICP: [Services companies, non-SaaS, SMB < 50 employees]

**Current State Problems:**
- [MQLs: 800/month, SQLs: 80/month (10% conversion), but only 20% of SQLs close]
- [Sales team says 60% of SQLs are not actually ready to buy]
- [No visibility into account-level engagement across contacts]
- [Missing buying committee members — only capturing individual leads]

## FRAMEWORK DESIGN REQUEST

### MODULE 1: Account Fit Scoring Model (0-40 points)

Design a firmographic and technographic scoring matrix:

**Tier 1 Fit Signals (20 points max):**
- Industry vertical match (define scoring by vertical)
- Employee count range (define optimal ranges and scores)
- Estimated ARR/revenue range (proxy indicators)
- Funding stage and recency (Series A-C = sweet spot)

**Tier 2 Fit Signals (12 points max):**
- Tech stack compatibility (CRM type, MAP, data enrichment tools)
- Existing integration ecosystem (Salesforce, HubSpot, Outreach, Gong)
- Territory alignment (maps to active sales territory)

**Tier 3 Fit Signals (8 points max):**
- ICP persona density (% of contacts that match target personas)
- Growth signals (hiring velocity, recent funding, market expansion)
- Technographic intent (recent technology purchases/evaluations)

### MODULE 2: Account Engagement Scoring Model (0-40 points)

Apply the FIRE framework (Frequency, Intent, Recency, Engagement Depth):

**Frequency Score (0-10):**
- Number of unique sessions from account IPs/identified contacts
- Multi-touch frequency across channels (web + email + events + social)
- Velocity trend: is engagement accelerating or decelerating?

**Intent Depth Score (0-10):**
- High-intent pages: pricing, demo, ROI calculator, comparison pages (3x weight)
- Medium-intent: case studies, product pages, integration pages (2x weight)
- Low-intent: blog posts, awareness content (1x weight)

**Recency Score (0-10):**
- Activity in last 7 days: full points
- Activity in 8-14 days: 80% points
- Activity in 15-30 days: 50% points
- Activity in 31-60 days: 20% points
- No activity > 60 days: decay to 0

**Buying Committee Coverage Score (0-10):**
- 1 persona engaged: 2 points
- 2+ personas engaged: 5 points
- Champion + Economic Buyer engaged: 8 points
- Full committee (3+ decision-makers): 10 points

### MODULE 3: Third-Party Intent Signal Amplification (0-20 points)

**Intent Topic Scoring:**
Map these signals to point values (define by data source):
- [Category intent topic surge (Bombora): 5-8 points]
- [G2 competitor profile visits: 3-5 points]
- [G2 product review research: 5-7 points]
- [6sense predicted stage (Decision/Purchase): 8-10 points]

**Trigger Event Signals:**
- New executive hire (CRO, VP Sales, VP Marketing): +5 points
- Funding announcement (Series A-C): +8 points
- Company expansion/new office: +3 points
- Competitor product discontinuation: +10 points
- Job posting for role your product replaces: +6 points

**Competitor Research Signals:**
- Account researching 2+ direct competitors: +5 points (urgency signal)
- Account has existing competitor contract renewal in 60 days: +15 points

### MODULE 4: MQA Threshold & Qualification Logic

**MQA Tiers:**
Design three MQA tiers with different handoff protocols:

Tier 1 — Hot MQA (Score 75-100):
- [Define threshold, required buying committee coverage, handoff SLA]
- [Immediate AE notification, executive outreach, priority queue]

Tier 2 — Warm MQA (Score 55-74):
- [Define threshold, coverage requirements, SDR handoff SLA]
- [24-hour SLA, structured outreach sequence]

Tier 3 — Watch List (Score 35-54):
- [Define monitoring rules, nurture continuation, re-evaluation trigger]
- [Marketing automation continues, sales notified but not required to act]

**Disqualification Rules (automatic recycling to nurture):**
- Competitors researching your product
- Current customers (flag for expansion team instead)
- Wrong persona majority (< 30% ICP contacts)
- Accounts with DNC status or legal restrictions
- Accounts in active sales cycle (prevent duplicate outreach)

**MQA Decay Logic:**
- Define point decay schedule for inactive accounts
- Trigger events that reset decay clock
- Recycle threshold (score drops below X = back to marketing)

### MODULE 5: AI-Generated Account Intelligence Brief

For each triggered MQA, auto-generate a structured handoff package:

**Account Intelligence Summary (auto-populate from enrichment + signals):**
ACCOUNT BRIEF: [Company Name]
MQA Score: [XX/100] | Tier: [1/2/3] | MQA Date: [Date]
Assigned To: [SDR/AE Name]

COMPANY SNAPSHOT
- Industry: | Employees: | HQ: | Founded: | Funding: 
- Tech Stack: CRM=[X], MAP=[X], Key Tools=[X]
- Recent News: [Last 3 relevant company events]

BUYING COMMITTEE MAP
Contact 1: [Name, Title] — [Engagement: X page views, attended webinar on [topic], downloaded [asset]]
Contact 2: [Name, Title] — [Engagement: X email opens, visited pricing page X times]
Contact 3: [Name, Title] — [Engagement: LinkedIn connection with AE, viewed demo request page]
Identified Gaps: [Missing: Economic Buyer/CFO, Technical Evaluator]

ENGAGEMENT STORY
[Narrative summary: "This account discovered us through [channel], and their engagement pattern suggests they're evaluating solutions for [inferred pain point]. Champion appears to be [Name] based on content interest pattern in [topic area].]

INTENT SIGNALS
- [Intent topic surging: [X topic]]
- [Competitor research detected: comparing to [Competitor A] and [Competitor B]]
- [Trigger event: [Company] hired new VP of Sales 3 weeks ago]

RECOMMENDED APPROACH
Personalization Angle: [Based on their specific engagement pattern and trigger events]
Recommended First Touch: [Channel + message angle]
Talk Track Suggestion: [Specific to their inferred pain + competitive situation]
Content to Reference: [Most relevant assets based on engagement history]

### MODULE 6: Automation Workflow Architecture

Design the end-to-end automation in:

**HubSpot Implementation:**
- Workflow logic for real-time score calculation
- Contact-to-account roll-up configuration
- MQA tier assignment and lifecycle stage transitions
- Automated task creation for SDR/AE with brief attached
- Slack notification format and routing rules

**Salesforce Implementation:**
- Account scoring field configuration
- Engagement score roll-up from Contact to Account object
- MQA process builder / flow automation
- Einstein Activity Capture integration for buying signal tracking
- Opportunity influence tracking for attribution

**Data Enrichment Integration:**
- Clearbit/Apollo enrichment triggers for new accounts entering scoring
- Bombora intent data sync schedule and field mapping
- 6sense segment pushes to advertising platforms
- Outreach/Salesloft sequence enrollment automation

### MODULE 7: Performance Measurement Framework

**MQA Program Health Metrics:**
- MQA Volume: [Monthly MQAs by tier]
- MQA-to-SQL Rate: [Target: 40-60%]
- SQL-to-Close Rate: [Target: 25-35%]
- Time-to-First-Touch SLA Adherence: [Target: >95% within SLA]
- MQA Decay Rate: [What % recycle back to marketing]
- Buying Committee Coverage at Handoff: [Target: 3+ personas]

**Scoring Model Accuracy Metrics:**
- Score Distribution Analysis: [Are scores clustering? Bimodal distribution?]
- Predictive Accuracy: [What % of MQAs above 75 become opportunities?]
- False Positive Rate: [MQAs that never convert to SQLs]
- False Negative Rate: [Accounts that become opps without hitting MQA threshold]

**Calibration Schedule:**
- Weekly: Review MQA-to-SQL conversion by tier, adjust threshold if needed
- Monthly: Score distribution analysis, signal weight recalibration
- Quarterly: Full model validation against closed/won data, buyer interview synthesis

## OUTPUT REQUIREMENTS

Deliver:
1. Complete MQA Scoring Rubric (table format with all signals and point values)
2. Account Intelligence Brief Template (populated with fictional example)
3. MQA Tier Playbook (per-tier outreach protocols and SLAs)
4. Automation Workflow Description (step-by-step for HubSpot or Salesforce)
5. 90-Day Implementation Roadmap
6. Measurement Dashboard Spec (KPIs, formulas, reporting cadence)

Format everything as production-ready documentation that can be handed directly to a RevOps engineer for implementation.

## Example Input/Output

**Input (Company Context):**
> Stackline Analytics — B2B SaaS revenue intelligence platform, Series B, $18M ARR. ICP: VP Sales and CRO at mid-market SaaS companies (100-500 employees). ACV: $72K. Current state: 650 MQLs/month, 58 SQLs (9% conversion), only 22% of SQLs close. Sales team reports 55% of leads "aren't ready." HubSpot + Salesforce dual deployment. Using Bombora for intent data.

**Output (Excerpt — Account Intelligence Brief):**

ACCOUNT BRIEF: Catalyst Commerce Inc.
MQA Score: 82/100 | Tier 1 (Hot) | MQA Date: 2026-03-14
Assigned To: Marcus Rivera (SDR), Escalate to: Priya Nair (AE) if meeting booked

COMPANY SNAPSHOT
Industry: B2B SaaS (eCommerce Analytics) | Employees: 340 | HQ: Austin, TX
Founded: 2019 | Funding: Series B ($28M, raised 4 months ago)
Tech Stack: Salesforce CRM, Marketo MAP, Gong, Outreach, Looker

BUYING COMMITTEE MAP
✅ Jamie Torres, VP Sales — 14 page views (pricing x3, ROI calculator x2, case study: "Catalyst-similar company x1"), webinar attendee (Pipeline Velocity Summit), 3 email opens
✅ Devon Kim, RevOps Director — 7 page views (integrations page x4, API docs x2), downloaded "RevOps Stack Guide" 
🔍 Sarah Okonkwo, CRO — Not yet engaged (identify and prioritize)
❌ Missing: Technical Evaluator, Economic Buyer (likely CFO/COO)

ENGAGEMENT STORY
Catalyst found us 23 days ago via organic search ("revenue intelligence platform comparison"). Jamie Torres is actively evaluating — they've returned to our pricing page three times and specifically read our Salesforce integration docs. Devon Kim's focus on the API/integration content suggests they're doing technical due diligence. The CRO (Sarah Okonkwo) is identified on LinkedIn but not yet touched — she's the economic buyer for this deal.

INTENT SIGNALS
🔥 Bombora: Surging on "Revenue Operations Software" and "Sales Forecasting Tools" (top 10% intensity)
⚡ G2: Account visited Clari, Gong Revenue Intelligence, and our G2 profile within 48 hours
📣 Trigger: Catalyst posted VP of Revenue Operations role 2 weeks ago — active budget authority
💡 LinkedIn: Jamie Torres liked 3 posts about "moving from MQL to MQA models" this month

RECOMMENDED APPROACH
Personalization Angle: They're actively building out RevOps maturity post-Series B. The VP of Sales is doing the legwork, but the CRO will approve the budget. Lead with the "RevOps leader's guide to revenue intelligence" narrative.

Recommended First Touch: Email to Jamie Torres, reference their recent G2 research activity (if comfortable) OR their RevOps Director role posting as a growth signal.

Talk Track: "We noticed Catalyst is scaling post-Series B and investing in RevOps infrastructure. Most companies at your stage hit the same bottleneck: Salesforce data exists but forecasting is still spreadsheet-based and sales coaching is reactive. [Customer Name] solved this in 60 days — here's what their VP Sales said..."

Content to Reference: Case study: TechFlow (340-employee SaaS company, similar profile, 34% forecast accuracy improvement)

SLA: First touch required within 4 business hours. If no response in 48 hours, enroll in Tier 1 MQA sequence (5-touch, 12-day cadence).

**Scoring Breakdown for Catalyst Commerce:**
| Category | Score | Notes |
|----------|-------|-------|
| Account Fit | 34/40 | Strong: Series B, right size, Salesforce stack. Moderate: eCommerce vertical (secondary ICP) |
| Engagement | 32/40 | Frequency: high. Intent depth: pricing + ROI pages. Recency: active this week. Committee: 2/4 personas |
| Intent Signals | 16/20 | Bombora surge + G2 research + hiring trigger. Missing: confirmed budget event |
| **Total** | **82/100** | **Tier 1 MQA — Hot** |

## Success Metrics

**Scoring Model Quality:**
- MQA-to-SQL conversion: target >45% (baseline MQL-to-SQL typically 8-12%)
- SQL-to-Close rate from MQAs: target >28% (vs. current 22%)
- Average deal size from MQAs vs. raw MQLs: target 15-25% higher ACV
- Buying committee coverage at handoff: target avg 2.8+ personas engaged

**Operational Metrics:**
- SLA adherence (time-to-first-touch): >95% within defined window
- Account intelligence brief accuracy: >80% score as "useful" in sales survey
- MQA false positive rate: <25% (accounts that never become opportunities)
- Sales satisfaction with handoff quality: >4.0/5.0 in monthly survey

**Business Impact (90 days):**
- Pipeline coverage ratio improvement: target +20% on same lead volume
- SDR ramp time reduction: target -30% (better-qualified accounts = faster learning)
- Marketing-sales alignment score: track via monthly survey

## Related Prompts

- [`../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Campaign-Orchestration-&-Account-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Campaign-Orchestration-&-Account-Intelligence-Engine.md)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Lead-Scoring-Automation.md`](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Lead-Scoring-Automation.md)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/B2B-Pipeline-Acceleration-&-Revenue-Closure-Marketing-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/B2B-Pipeline-Acceleration-&-Revenue-Closure-Marketing-Intelligence-Engine.md)

## Integration Tips

**HubSpot:**
- Use custom `Account Score` property with a calculated score workflow that sums contact-level engagement rolled up to the company object
- Enable `Company-based workflows` to trigger MQA tasks and lifecycle changes when company score crosses threshold
- Build a custom MQA dashboard in HubSpot Reports using `Company Lifecycle Stage = MQA` filter
- Connect Bombora Surge data via HubSpot's Bombora integration or Zapier to populate intent score fields automatically

**Salesforce:**
- Create a custom `MQA_Score__c` field on the Account object; use Process Builder or Flow to calculate from child Contact engagement activities
- Build an `Account Intelligence Brief` rich text field that's auto-populated via a Salesforce Flow triggered on MQA threshold crossing
- Use Salesforce Einstein Activity Capture to ensure all email and meeting activity from Gmail/Outlook is logged for engagement scoring
- Create a `MQA Handoff` task type with required fields that enforce the SDR to review the brief before first contact

**Outreach / Salesloft:**
- Map MQA tier to Outreach sequence enrollment: Tier 1 = Priority Sequence (high-touch), Tier 2 = Standard ABM Sequence
- Use Outreach's `Account-Based` sequences to ensure all contacts at MQA accounts receive coordinated, non-duplicative outreach
- Push MQA tier and brief summary into Outreach Account notes field via API webhook from CRM

**Slack:**
- Set up a `#mqa-alerts` channel with real-time Zapier or Salesforce Slack integration notifications when Tier 1 MQAs trigger
- Format: `🔥 New Tier 1 MQA: [Company] (Score: XX/100) — Assigned to @[SDR] — [Brief link]`
- Create weekly digest of MQA pipeline movement for sales leadership

**Data Enrichment (Clearbit/Apollo/ZoomInfo):**
- Trigger enrichment automatically when net-new company enters scoring model (webhook from form fill or website identity resolution)
- Use enrichment to auto-populate fit scoring fields: employees, industry, revenue estimate, tech stack
- Schedule weekly enrichment refresh for accounts in Watch List (Tier 3) to catch company growth triggers

## Troubleshooting

**Problem: MQA scores are too clustered (everyone scores 55-65, hard to differentiate)**
Fix: Check your signal weight distribution. High-intent signals (pricing page, demo request) should carry 3-5x the weight of low-intent signals (blog reads). Also audit your firmographic scoring — if 80% of accounts are in your ideal employee range, that signal is too broad. Add 2-3 tighter fit criteria (specific tech stack, funding stage, job posting signals) to create more distribution.

**Problem: Sales team ignores MQA handoffs ("these aren't better than our old MQLs")**
Fix: Two issues are usually at play. First, check if the account intelligence brief is actually being viewed — add a Salesforce/HubSpot field `Brief_Reviewed__c` that SDRs must check before marking contacted. Second, do a 30-day win/loss analysis: compare close rates on MQA-sourced opportunities vs. manual ones. Show the data. If close rates aren't better yet, the model needs calibration — bring in 5 recently closed deals and back-calculate what their MQA score would have been to validate the threshold.

**Problem: Buying committee coverage is too low (most MQAs only have 1 contact engaged)**
Fix: This is a contact acquisition problem, not a scoring problem. Implement an "account completion" workflow: when any contact at an ICP account shows high intent, trigger a contact discovery step using Apollo/ZoomInfo to find other buying committee members and enroll them in awareness-stage email nurtures. Also configure your CRMs reverse IP lookup / website visitor identification (Clearbit Reveal, Albacross, or 6sense) to identify anonymous visitors and map them back to accounts so you're capturing engagement from contacts not yet in your database.

## Version History
- v1.0: Initial creation (auto-generated, 2026-03-15)
