# AI-Powered B2B SaaS Revenue Qualified Lead (RQL) Scoring Architecture & Autonomous Pipeline Prioritization Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, saas, analytics, lead-scoring, rql, revenue-operations, pipeline-quality, ai-automation, intent-data, prioritization

## Overview
This prompt engineers a complete Revenue Qualified Lead (RQL) scoring system that goes beyond MQL by combining ICP fit, buying intent signals, engagement velocity, and timing indicators into a composite score that predicts actual revenue conversion — not just pipeline entry. Use it when your MQL-to-Closed-Won rate is under 8%, when your sales team cherry-picks leads because they distrust marketing's scores, or when you want to build an AI-autonomous prioritization engine that routes the right accounts to the right motion (SDR touch, nurture, ABM, or direct AE) without human triage.

## Quick Copy-Paste Version

You are a senior revenue operations architect specializing in AI-powered lead and account scoring for B2B SaaS companies.

Design a complete Revenue Qualified Lead (RQL) scoring system for my company that predicts closed-won conversion, not just pipeline entry:

COMPANY CONTEXT:
- Product: [e.g., "Fieldvision — AI-powered construction project management platform"]
- ICP: [e.g., "General contractors and ENR 400 firms with 200+ employees managing $10M+ projects"]
- Average ACV: [e.g., "$42,000"]
- Sales cycle: [e.g., "60-90 days"]
- Current scoring platform: [e.g., "HubSpot with Bombora intent data"]
- Current MQL-to-Closed-Won rate: [e.g., "4.2%"]
- Monthly MQL volume: [e.g., "280 MQLs/month"]
- Current scoring signals used: [e.g., "job title, email opens, page visits, form fills"]

DELIVERABLES:

1. RQL SCORING ARCHITECTURE
Design a 4-dimension composite scoring model (ICP Fit + Intent Velocity + Engagement Depth + Timing Readiness) with point values for each dimension and the threshold that defines an RQL. Show how this differs from MQL and why it predicts revenue better.

2. SIGNAL WEIGHTING MATRIX
Create a prioritized list of the 15 most predictive revenue signals across first-party (website, product, CRM) and third-party (intent data, technographic, firmographic) sources. Assign weight multipliers based on their proven correlation to closed-won outcomes.

3. AUTONOMOUS ROUTING PLAYBOOK
Define the 4 routing destinations (SDR high-touch, ABM sequence, nurture program, direct AE) and the exact score thresholds and signal combinations that trigger each route — fully automated, no human triage required.

4. INTEGRATION ARCHITECTURE
Specify the exact data flows: which platforms feed scores, how scores update in real-time, where they surface in CRM, and which automated actions trigger at each score threshold.

5. 90-DAY VALIDATION PLAN
Outline how to validate the RQL model within 90 days: what data to collect, how to compare RQL-to-Closed-Won vs MQL-to-Closed-Won, and how to recalibrate scoring weights based on actual outcomes.

Make every section immediately implementable, not conceptual.

## Advanced Customizable Version

SYSTEM ROLE:
You are an AI-native revenue operations architect with 18 years of experience building predictive scoring systems for B2B SaaS companies scaling from $10M to $300M ARR. You have deep expertise in the structural failure of MQL-based lead scoring — the fundamental problem being that MQLs optimize for pipeline entry, not pipeline exit. You've redesigned scoring architectures at 40+ B2B SaaS companies and understand that revenue-predictive scoring requires four independent dimensions that MQL scoring conflates into noise: (1) ICP fit at the account level, (2) intent signal velocity not just presence, (3) engagement depth across the full buying committee, and (4) timing readiness indicators that reflect where the account is in their buying cycle. Your mission is to architect a complete RQL scoring system that an AI agent can execute autonomously — from signal aggregation through routing decision — without requiring a human RevOps analyst to triage every lead.

COMPANY CONTEXT:
Company Name: [Company Name]
Product Description: [One-line description — e.g., "AI-powered compliance automation platform that continuously monitors regulatory changes and updates internal policies across legal, HR, and finance teams"]
ICP Definition:
  Account Profile: [e.g., "Mid-market to enterprise companies in regulated industries (financial services, healthcare, manufacturing) with 500-5,000 employees and active compliance function"]
  Primary Buying Persona: [e.g., "Chief Compliance Officer or VP Compliance (decision maker), General Counsel (sponsor), CFO (budget holder), IT Security (technical evaluator)"]
  Anti-ICP Signals: [e.g., "companies under 100 employees, unregulated industries like pure tech startups, government entities"]
Average Contract Value (ACV): [e.g., "$78,000"]
Sales Cycle Length: [e.g., "75-120 days enterprise, 30-45 days mid-market"]
Revenue Metrics:
  Current MQL-to-SQL conversion rate: [e.g., "28%"]
  Current SQL-to-Closed-Won rate: [e.g., "17%"]
  Current MQL-to-Closed-Won rate: [e.g., "4.8%"]
  Target RQL-to-Closed-Won rate: [e.g., "15%+"]
Current Tech Stack:
  CRM: [e.g., "Salesforce"]
  Marketing Automation: [e.g., "Marketo"]
  Intent Data: [e.g., "Bombora topic surge, 6sense account-level scores, G2 buyer intent"]
  Enrichment: [e.g., "Clay (waterfall: Apollo → ZoomInfo → Clearbit), Demandbase firmographic"]
  Conversation Intelligence: [e.g., "Gong"]
  Website Intelligence: [e.g., "Clearbit Reveal / 6sense X for anonymous visitor identification"]
Current Scoring Problems: [e.g., "Sales team ignores 60% of MQLs, demo show rate is 34%, closed-won from MQL source is $890K/quarter vs $4.1M from outbound"]
Top Converting Accounts (describe 3 closed-won deals): [e.g., "Pinnacle Financial — CCO saw our LinkedIn ad, read 4 blog posts over 3 weeks, attended webinar, replied to SDR cold email same day, closed in 38 days at $112K"]

OBJECTIVE:
Architect a complete Revenue Qualified Lead scoring system that: (1) predicts closed-won conversion at 3x the accuracy of current MQL scoring; (2) operates autonomously — no human triage required; (3) routes each account to the optimal go-to-market motion based on score composition; (4) learns from outcomes and recalibrates automatically every 30 days.

---

DELIVERABLE 1: RQL SCORING ARCHITECTURE — THE FOUR DIMENSIONS

Design a 4-dimension Revenue Qualified Lead model where each dimension is scored independently before combining into a composite RQL score. For each dimension, define: what it measures, the scoring range (0-25 points each, 100 total), the 5 sub-signals within that dimension, how an AI agent evaluates each signal automatically, and why this dimension predicts closed-won better than MQL equivalent signals.

DIMENSION 1: ICP FIT SCORE (0-25 points)
Measures: How closely the account matches your highest-converting customer profile at the company level — not individual contact level.

Signal breakdown (5 points each):
- Industry vertical match: exact vertical vs. adjacent vs. non-ICP (evaluate against firmographic data from enrichment waterfall)
- Employee count band: which headcount ranges convert at 3x average (analyze closed-won cohorts)
- Revenue/funding stage: correlate ARR stage or funding round with deal conversion rate
- Technology stack fit: presence of specific tools that indicate readiness (e.g., existing CRM and MAP stack suggests maturity)
- Growth signal: YoY headcount growth rate, recent funding, job posting velocity (extract from LinkedIn, Crunchbase)

AI evaluation method: Clay enrichment waterfall → normalize to scoring rubric → write dimension score to CRM object field.

DIMENSION 2: INTENT VELOCITY SCORE (0-25 points)
Measures: Not whether intent is present but how FAST intent is accelerating — the rate of change is more predictive than the level.

Signal breakdown (5 points each):
- Intent surge rate: Bombora/6sense topic surge spike in last 7 days vs. 30-day baseline (velocity, not absolute level)
- Keyword research acceleration: G2 category page visits, competitive comparison page views, pricing page hits — are these increasing week-over-week?
- Competitor review activity: G2/Capterra review reading pattern indicating active vendor evaluation
- Anonymous web session acceleration: Clearbit Reveal or 6sense X session count increase — are more people from this company coming to your site more frequently?
- Content consumption depth: moving from top-of-funnel (blog) to bottom-of-funnel (ROI calculator, security docs, pricing) content within 14 days

AI evaluation method: 6sense intent API or Bombora webhook → calculate 7-day vs. 30-day intent velocity ratio → score acceleration bands.

DIMENSION 3: BUYING COMMITTEE ENGAGEMENT DEPTH (0-25 points)
Measures: Multi-stakeholder coverage and engagement quality across the buying committee, not just one contact's activity.

Signal breakdown (5 points each):
- Contact coverage: number of unique job functions engaged (1 = 0 pts, 2 = 2 pts, 3 = 4 pts, 4+ = 5 pts) from your defined buying committee roles
- Economic buyer engagement: has the CFO, VP Finance, or C-suite equivalent from this account engaged (email open, LinkedIn ad click, event attendance) — yes = full 5 points
- Technical evaluator engagement: has an IT, Security, or Engineering contact engaged with technical content — yes = 3-5 points based on depth
- Champion engagement frequency: primary champion contact score velocity — increasing engagement in last 14 days scores maximum
- Multi-channel engagement: same contact engaging across email + web + event + social = higher multi-touch confirmation of genuine interest

AI evaluation method: CRM contact → account relationship aggregation → buying committee coverage logic → write committee coverage score.

DIMENSION 4: TIMING READINESS SCORE (0-25 points)
Measures: External signals that indicate this account is in an active buying cycle RIGHT NOW — not eventual intent but current urgency.

Signal breakdown (5 points each):
- Budget cycle timing: fiscal year-end or budget cycle initiation (Q4 buyer = higher urgency score, confirmed via job posting patterns for budget-related roles)
- Trigger event detected: leadership change (new buyer persona hired), funding announcement, compliance deadline, contract expiry signal, or company expansion event — each verified trigger adds points
- Contract timing intelligence: do you have intelligence that they're on a competitor contract expiring in 90 days? (source: LinkedIn job postings requesting "replace [Competitor]" or review site timing signals)
- RFP/evaluation signal: outbound inquiry received, RFP portal visit, security questionnaire request, or direct inbound contact from non-nurtured company employee
- Competitive displacement signal: reviewing competitor on G2, searching "[Competitor] alternative" keywords, or G2 buyer intent flagging competitor category engagement

AI evaluation method: trigger event monitoring webhook → enrichment waterfall for firmographic changes → intent platform for competitor signals → assemble timing score.

---

DELIVERABLE 2: RQL COMPOSITE SCORE & THRESHOLD ARCHITECTURE

Define the composite scoring system:
- Total score range: 0-100 (sum of 4 dimensions)
- RQL threshold: the minimum score to qualify as an RQL (recommend starting at 65, validate against historical data)
- Score tier system:
  * Tier 1 RQL (85-100): Immediate SDR outreach + AE notification within 4 hours
  * Tier 2 RQL (70-84): SDR sequence enrollment within 24 hours
  * Tier 3 Emerging (55-69): ABM nurture program + SDR awareness flag
  * Tier 4 Developing (40-54): Marketing nurture only, resurface when score crosses 55
  * Below 40: Marketing automation, no sales touch until score improvement

Dimension minimum thresholds: Design floor scores per dimension to prevent "high-score gaming" where a perfect intent score but zero ICP fit triggers false RQL (e.g., require minimum 12/25 on ICP Fit regardless of other dimensions).

Score decay logic: Define how scores decay when no engagement occurs (e.g., Intent Velocity score drops 3 points per week without new intent signal, Engagement Depth score drops 2 points per week without new contact engagement).

---

DELIVERABLE 3: AUTONOMOUS ROUTING PLAYBOOK

For each of the 4 routing destinations, define exactly: score threshold, dimension composition requirements, the automated action triggered in the CRM/MAP, the SLA for follow-up, and the handoff message format.

ROUTE A — DIRECT SDR HIGH-TOUCH (Tier 1 RQL: 85-100 with ICP Fit ≥20):
Automated trigger: Salesforce task created for assigned SDR, Slack alert to SDR with account brief generated via AI, Outreach sequence initiated with personalized first email pre-drafted (AI generates using account intelligence), SDR SLA: first touch within 4 business hours. AE also notified with "hot account alert."

ROUTE B — SDR SEQUENCE FAST TRACK (Tier 2 RQL: 70-84 with ICP Fit ≥15):
Automated trigger: SDR sequence enrollment in Outreach, CRM opportunity record created as "Marketing Identified," weekly re-score review, SDR SLA: review AI-generated account brief within 48 hours and either activate or override with reason code.

ROUTE C — ABM ORCHESTRATION (Tier 3 Emerging: 55-69 OR high ICP Fit ≥22 with low intent):
Automated trigger: Account added to 6sense or Demandbase ABM audience, personalized ad sequence initiated, SDR flagged for "soft" LinkedIn engagement (connection + content comment), monthly field marketing event invitation if available in territory. Goal: accelerate score to Tier 2 RQL within 45 days.

ROUTE D — INTELLIGENT NURTURE (Below 55 with ICP Fit ≥12):
Automated trigger: Marketo/HubSpot nurture track enrollment matched to detected buying stage (awareness vs. consideration content), monthly re-score check, territory SDR receives monthly "nurture watchlist" for accounts approaching threshold, trigger-based fast-track to Route B if timing readiness score spikes above 18 in any single week.

EXCLUSION LOGIC — NO ROUTE:
Define disqualification rules that override positive scores: known competitor accounts, existing customers, partners, DNC list, or accounts with active closed-lost opportunities in the last 90 days.

---

DELIVERABLE 4: REAL-TIME INTEGRATION ARCHITECTURE

Map the complete data flow from signal capture to routing action:

SIGNAL INGESTION LAYER:
- 6sense account score webhook → Salesforce Account object [6sense_score] field update, triggers score recalculation workflow
- Bombora topic surge alert → Marketo program token update, triggers intent velocity sub-score recalculation
- Clay enrichment run (triggered daily for accounts in Tier 3-4) → Salesforce Account enrichment fields updated, triggers ICP Fit sub-score recalculation
- Gong call intelligence → post-call AI summary triggers engagement depth update for buying committee contacts involved
- Website session data (Clearbit Reveal / 6sense X) → engagement depth score update for identified company sessions > 5 minutes

SCORE COMPUTATION LAYER:
- Salesforce Flow automation: triggered on any sub-score field update, recalculates composite RQL score, compares to previous score, logs score history in Score_History__c object
- Clay or Zapier orchestration: cross-platform sub-score aggregation when signals come from non-CRM sources
- Recalculation frequency: intent-triggered (real-time for large spikes), nightly batch for all other dimension updates

ROUTING ACTION LAYER:
- Score threshold crossed (automated): Salesforce Workflow Rule or Flow triggers routing action within 15 minutes of score update
- SDR notification: Slack integration sends formatted account brief to SDR Slack channel with score breakdown, top 3 signals, and recommended opening message
- Sequence enrollment: Outreach or Salesloft API triggered from Salesforce to auto-enroll in the correct sequence
- ABM audience sync: Salesforce → 6sense or Demandbase segment membership updated within 4 hours of score update

---

DELIVERABLE 5: 90-DAY VALIDATION & CONTINUOUS LEARNING PROTOCOL

WEEK 1-2: BASELINE CALIBRATION
Backfill scoring against 12 months of closed-won, closed-lost, and stale pipeline data. Calculate: what was each account's RQL score at the time of first sales touch? Identify the score threshold at which closed-won rate exceeds 15%. This sets your initial RQL threshold.

WEEK 3-6: PARALLEL SCORING
Run RQL model in parallel with existing MQL model. Score all new leads on both systems. Do NOT change routing yet — let sales work their normal process. Log RQL scores for all 300-500 leads processed.

WEEK 7-8: FIRST CALIBRATION
Analyze: for all leads where RQL score was 65+ at first touch, what is their 60-day conversion to opportunity rate? Compare to equivalent MQL cohort. Adjust dimension weights: if Intent Velocity score is weakly correlated to opportunity creation, reduce its weight by 20% and increase Timing Readiness weight.

WEEK 9-12: CONTROLLED ROUTING TEST
Apply RQL routing for 50% of new qualified accounts (A/B test). Compare: 
- Show rate: RQL-routed vs. MQL-routed accounts
- Opportunity creation rate: 30 days after first touch
- Average deal size: RQL-routed vs. MQL-routed
- Time-to-opportunity: faster in RQL cohort?

30-DAY CONTINUOUS RECALIBRATION:
Once live, implement monthly automated recalibration:
- Gong call AI analyzes discovery call transcripts for language patterns correlating to later Closed-Won — feed these back as intent signal weight adjustments
- Closed-Won accounts in last 30 days: audit their score trajectory — what was the score 7 days before they converted? Raise the weight of signals that were high in that window
- Churned RQL accounts: accounts that were scored as Tier 1 RQL but went dark within 45 days — analyze which dimension had false-positive scores and adjust floor thresholds

---

## Example Input/Output

**Input Example:**

Company: Veritas Legal AI — AI-powered contract review platform for enterprise legal teams
ICP: Companies with 1,000+ employees in financial services, insurance, or healthcare with in-house legal departments of 5+ attorneys
ACV: $95,000
Sales Cycle: 80-100 days
Current MQL-to-Closed-Won: 3.1%
Stack: Salesforce + Marketo + Bombora + 6sense + Gong + Clay

**Output Example (Dimension Scores for Sample Account — Athena Financial Group):**

ICP FIT SCORE: 23/25
- Industry vertical (Financial Services): 5/5 — exact match
- Employee count (4,200 employees): 5/5 — within highest-converting band (1,000-10,000)
- Revenue stage ($1.2B revenue, public): 5/5 — enterprise deal size confirmed
- Technology stack fit (Salesforce, NetSuite, DocuSign detected via BuiltWith): 4/5 — strong stack maturity signal
- Growth signal (14% headcount growth YoY, Series E equivalent): 4/5 — growth indicates budget availability

INTENT VELOCITY SCORE: 19/25
- Bombora intent surge rate: 4/5 — 340% surge in "contract management" and "AI legal" topics vs. 30-day baseline
- Keyword research acceleration: 5/5 — 6sense detected 4 unique contacts from Athena hitting pricing page within 7 days
- Competitor review activity: 4/5 — G2 buyer intent: 2 contacts reading Ironclad vs. [Competitor] comparison pages
- Anonymous session acceleration: 3/5 — 6 sessions from Athena in last 14 days (up from 1)
- Content consumption depth: 3/5 — downloaded ROI calculator, viewed security whitepaper (good depth, no pricing contact yet)

BUYING COMMITTEE ENGAGEMENT DEPTH: 15/25
- Contact coverage: 3/5 — 2 unique functions engaged (Legal Ops Director + IT Security Manager)
- Economic buyer engagement: 0/5 — no CFO or GC engagement detected yet (flag: need champion to facilitate)
- Technical evaluator engagement: 5/5 — IT Security Manager watched full security compliance webinar
- Champion engagement frequency: 5/5 — Legal Ops Director Jordan Kwan engaged 7 times in 14 days (spike)
- Multi-channel engagement: 2/5 — email + web but no event attendance yet

TIMING READINESS SCORE: 18/25
- Budget cycle timing: 4/5 — Q4 fiscal year (confirmed via LinkedIn posting for "2027 Budget Planning Analyst" role)
- Trigger event detected: 5/5 — new General Counsel hired 3 weeks ago (Bombora trigger alert)
- Contract timing intelligence: 3/5 — LinkedIn job posting mentions "transitioning from legacy contract management system" suggesting near-term replacement intent
- RFP signal: 2/5 — inbound contact form submission from Jordan Kwan requesting "product capabilities overview"
- Competitive displacement signal: 4/5 — G2 buyer intent flagging active Ironclad evaluation

**COMPOSITE RQL SCORE: 75/100 — Tier 2 RQL**

**AUTONOMOUS ROUTING DECISION:**
Route B triggered → SDR sequence fast-track enrollment
- Salesforce opportunity record created: "Athena Financial Group — Marketing Identified"
- Outreach sequence: "Legal AI — GC Change Play" enrolled for Jordan Kwan (AI-generated first email personalization: references new GC hire + Q4 budget cycle)
- SDR Slack alert: "HOT ACCOUNT — 75 RQL Score. New GC at Athena Financial, 4 contacts on site this week, competitor evaluation underway. Jordan Kwan (Legal Ops Director) requested product overview. Review AI brief and activate within 24hrs."
- ABM: Athena Financial added to 6sense "Tier 2 Active Evaluation" segment → serving LinkedIn ads targeting GC + CFO personas
- Recalibration trigger: if Buying Committee score increases to 20+ within next 14 days (GC or CFO engages), auto-upgrade to Tier 1 RQL and create SDR task for same-day outreach

## Success Metrics

**Model Accuracy:**
- RQL-to-Closed-Won rate ≥ 12% (vs. 3-5% MQL baseline) within 90 days
- RQL-to-Opportunity creation rate ≥ 35% within 45 days of routing
- Tier 1 RQL demo show rate ≥ 70% (vs. typical 40-50% for MQL-routed)

**Efficiency Gains:**
- Human triage time eliminated: 100% of RQL routing decisions automated
- SDR outreach time-to-first-touch: Tier 1 ≤ 4 hours, Tier 2 ≤ 24 hours (automated sequence enrollment reduces delay)
- SDR meeting-booked rate from RQL accounts: ≥ 18% (vs. 8-12% from MQL-routed)

**Revenue Impact:**
- Marketing-sourced pipeline quality improvement: 30%+ increase in marketing-sourced ACV within 2 quarters
- Average deal size of RQL-sourced pipeline: within 15% of outbound-sourced deals (indicates qualification quality parity)
- Score model drift indicator: MQL-to-Closed-Won rate for non-RQL accounts should remain stable (confirms RQL is selecting better accounts, not just all accounts)

**System Health:**
- Score computation latency: 100% of scores updated within 15 minutes of trigger signal
- Routing action latency: 100% of routing decisions executed within 30 minutes of score threshold crossed
- Dimension floor violations caught: 0% of Tier 1 RQL accounts with ICP Fit < 12 (confirms disqualification logic working)

## Related Prompts

- [Lead Scoring Model Performance Analytics & Optimization](./AI-Powered-B2B-SaaS-Lead-Scoring-Model-Performance-Analytics-&-Predictive-Scoring-Optimization-Revenue-Intelligence-Engine.md)
- [First-Party Behavioral Signal Scoring & Buyer Intent Analytics](./AI-Powered-B2B-SaaS-First-Party-Behavioral-Signal-Scoring-&-Buyer-Intent-Analytics-Revenue-Intelligence-Engine.md)
- [Multi-Source Intent Signal Aggregation & Cross-Platform Buyer Stage Intelligence](../../05_Analytics-&-Performance/Intent-Data-Analytics/AI-Powered-B2B-SaaS-Multi-Source-Intent-Signal-Aggregation-&-Cross-Platform-Buyer-Stage-Revenue-Intelligence-Engine.md)
- [ABM Buying Committee Engagement Scoring & Multi-Stakeholder Deal Velocity](../../05_Analytics-&-Performance/Account-Based-Marketing-Analytics/AI-Powered-ABM-Buying-Committee-Engagement-Scoring-&-Multi-Stakeholder-Deal-Velocity-Intelligence-Engine.md)

## Integration Tips

**Salesforce:**
- Create custom object `RQL_Score_History__c` to log every score change with timestamp, dimension breakdown, and triggering signal — enables model recalibration and audit trail
- Use Salesforce Flows (not Process Builder) for score-triggered routing actions: Flows handle the conditional logic for tier assignment, routing destination, and downstream automation triggers
- Build Einstein Analytics (CRM Analytics) dashboard showing RQL score distribution, conversion rates by tier, and dimension-level correlation to Closed-Won

**Marketo / HubSpot:**
- Sync RQL composite score as a custom person/account field — use it as the primary lead assignment criteria in your MAP routing rules
- Create smart list segments based on RQL tier for reporting: "Tier 1 RQL Sourced Pipeline" as a named Marketo segment gives you instant attribution visibility
- Use program status progression in Marketo to track: MQL → RQL → Opportunity → Closed-Won as distinct program statuses for cohort analysis

**Clay:**
- Build a Clay table that runs enrichment waterfalls triggered by Salesforce webhook when an account enters "Emerging" tier (score 40-55) — enrich for buying committee contacts, technographic fit, and growth signals to accelerate their score to RQL
- Set up Clay "watchers" on key ICP accounts to detect trigger events (funding, leadership change, job postings) and push score updates back to Salesforce

**6sense / Demandbase:**
- Map your 4 RQL tiers to 6sense buying stage keywords: Tier 1 (Decision stage), Tier 2 (Evaluation stage), Tier 3 (Solution stage), Tier 4 (Awareness stage)
- Use 6sense audience segments directly as ABM ad targeting layers — accounts in Tier 3 receive awareness ads, Tier 2 receive feature-specific proof ads, Tier 1 receive competitor displacement ads

**Gong:**
- Install Gong Initiative "RQL Closed-Won Patterns" — train Gong to flag discovery call transcripts where champion language matches patterns from your highest-scored closed-won accounts
- Gong → Salesforce score update: when Gong scores a call as "strong discovery" (positive outcome prediction), trigger a +5 point boost to Buying Committee Engagement Depth dimension via Salesforce Flow

**Slack:**
- Build a dedicated `#rql-alerts` Slack channel: Tier 1 alerts post with account brief, score breakdown, and AI-generated SDR opening message; Tier 2 posts daily digest of new RQL accounts
- SDR override workflow: SDR can react with specific emojis in Slack to log routing overrides (🚫 = disqualify, ✅ = accepted, ⏳ = defer 30 days) which write back to Salesforce for model recalibration

## Troubleshooting

**Problem: RQL scores are high but Closed-Won rates aren't improving after 60 days**
Diagnosis: Your threshold is too low, or one dimension is masking poor quality (a perfect intent score can inflate composite score despite poor ICP fit). Solution: Implement dimension floor minimums — require ICP Fit ≥ 15 and Timing Readiness ≥ 12 as hard prerequisites for any RQL designation regardless of composite score. Analyze which dimension was highest in your closed-lost RQL cohort and reduce its weight by 25%.

**Problem: Sales team is still ignoring RQL-routed accounts at the same rate as old MQLs**
Diagnosis: The score isn't visible or credible enough, and SDRs don't trust it yet. Solution: Run a 30-day "proof period" — send SDR team a weekly report showing: "Accounts that were Tier 1 RQL this week, contacted within SLA: X% became opportunities. Accounts that were Tier 1 RQL but not contacted: 0% became opportunities." Make the data visceral and rep-specific. Also simplify the score display in Salesforce: show the 3 top signals driving the score, not just the number — SDRs trust signals they recognize, not opaque AI scores.

**Problem: Score computation is delayed — accounts are crossing thresholds but routing actions are firing hours later**
Diagnosis: You're using Salesforce Process Builder (now sunset) or batch-mode Flows instead of record-triggered Flows on field updates. Solution: Rebuild routing actions as Salesforce record-triggered Flows that fire immediately when the RQL_Composite_Score__c field crosses a defined threshold. For cross-platform signals (6sense, Clay, Bombora), use their native webhook/API integrations to push updates in real-time rather than relying on nightly batch syncs.

## Version History
- v1.0: Initial creation (auto-generated)
