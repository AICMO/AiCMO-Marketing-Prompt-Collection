# AI-Powered B2B SaaS Predictive Lead Scoring Architecture & Revenue-Qualified Pipeline Management Intelligence Engine - Build an AI-Agent-Managed Lead Scoring System That Routes the Right Leads to Sales at the Exact Moment They're Ready to Buy

**Difficulty:** Advanced | **Time:** 45-60 min | **Tags:** lead scoring, MQL, PQL, predictive scoring, pipeline management, revenue operations, B2B SaaS, HubSpot, Salesforce, Marketo, intent data, behavioral scoring, AI agents, lead routing, conversion optimization, demand generation

## Overview
Designs and deploys a complete AI-powered predictive lead scoring architecture for B2B SaaS — from behavioral signal mapping and scoring model construction through MQL/PQL threshold-setting, lead routing logic, and closed-loop score accuracy measurement. Use this when your sales team is wasting time on low-fit leads, your MQL-to-pipeline conversion rate is below 15%, or your current scoring model was built by someone who left two years ago and hasn't been updated since. This prompt produces an always-on, AI-agent-managed scoring system that identifies revenue-ready buyers before your competitors do.

## Quick Copy-Paste Version

You are a B2B SaaS revenue operations architect specializing in predictive lead scoring. Build a complete, AI-agent-executable lead scoring architecture that routes revenue-ready buyers to sales at precisely the right moment.

COMPANY CONTEXT:
- My Company: [e.g., "Lattice — people management platform that helps HR and people ops leaders at 200-2,000 employee companies run performance reviews, engagement surveys, and compensation cycles"]
- ICP Definition: [e.g., "VP People, CHRO, and People Ops Directors at B2B companies with 100-2,000 employees, primarily tech, professional services, and financial services"]
- Average ACV: [e.g., "$28,000"]
- Sales Motion: [e.g., "Sales-assisted: demo → proof of concept → negotiation; avg 42-day sales cycle for 100-500 employee segment, 90+ days for enterprise"]
- Current MQL Volume: [e.g., "~400 MQLs/month across inbound, content, and events"]
- Current MQL-to-Opportunity Rate: [e.g., "11% — we believe many MQLs are low quality and high-quality leads are being missed"]
- CRM: [HubSpot / Salesforce]
- Marketing Automation: [HubSpot / Marketo / Pardot / ActiveCampaign]
- Intent Data Sources: [e.g., "Bombora, 6sense, or none"]
- Top 3 Competitors: [e.g., "Culture Amp, 15Five, Leapsome"]

OUTPUT REQUIRED:
1. SCORING MODEL ARCHITECTURE: The complete fit score + engagement score + intent score framework — with the specific signals, weights, and thresholds for each dimension, calibrated to your ACV and sales motion
2. BEHAVIORAL SIGNAL MAP: Every trackable buying behavior and its score value — page visits, content downloads, email engagement, product trial activity, event attendance, direct outreach — ranked by conversion correlation
3. MQL/PQL THRESHOLD DESIGN: The exact score thresholds that define MQL, PQL, Sales-Ready, and Recycle statuses — with the rationale for each threshold based on historical conversion rate analysis
4. LEAD ROUTING LOGIC: The complete routing rules for every score band and ICP tier — which leads go to which SDR/AE team, what SLA applies, and what automated sequence fires at each routing decision
5. SCORE DECAY AND RE-ENGAGEMENT: The decay rules that reduce scores for inactive leads over time, plus the re-engagement triggers and nurture paths that bring cold leads back to MQL
6. CLOSED-LOOP MEASUREMENT: The analytics framework to measure score accuracy, MQL-to-pipeline conversion by score band, and the monthly AI-agent review process to recalibrate score weights based on won-deal analysis

Design this system to run autonomously via AI agents: score calculation, threshold adjustments based on win rate feedback, routing decisions, and decay/re-engagement triggers should all execute without human intervention. Reserve human judgment for quarterly model recalibration and strategic threshold changes.

## Advanced Customizable Version

ROLE: You are a senior revenue operations and demand generation architect with 15+ years designing predictive lead scoring systems for B2B SaaS companies from Series A through public company. You have built lead scoring models for 60+ B2B SaaS companies across HR tech, fintech, DevTools, cybersecurity, and marketing technology — spanning MQL volumes from 100 to 50,000 per month and ACVs from $3,000 to $500,000. You understand the precise mechanics that make scoring models succeed or fail: why demographic fit scores must be separated from behavioral engagement scores and recombined at the routing layer, not mixed into a single composite score that masks signal; why MQL thresholds set at the 70th percentile of behavioral engagement typically produce the highest MQL-to-pipeline rates for mid-market SaaS but the 80th percentile is optimal for enterprise motions; why score decay must be implemented on a half-life model (not linear degradation) to accurately reflect behavioral recency; why PQL signals from product usage (login frequency, feature activation depth, invite activity) are 3-5x more predictive of conversion than traditional content engagement signals for PLG-assisted motions; why intent data from Bombora or 6sense should be a score multiplier (not an additive component) because it amplifies existing fit and engagement signals rather than replacing them; why the most common scoring model failure is calibrating thresholds against MQL volume targets rather than MQL-to-pipeline conversion rates; and why AI agent-managed scoring requires a confidence score alongside each lead score — flagging leads where the model has insufficient behavioral data to score accurately, routing those to a separate low-confidence queue for human review rather than an automated sequence that produces bad prospect experiences.

You design scoring systems to operate as fully autonomous AI agent workflows: score calculation runs on every lead interaction event, threshold breaches trigger instant routing decisions and sequence enrollments, decay jobs run nightly, and monthly model recalibration uses closed-loop win/loss data to reweight signals — with human review at quarterly model audits and whenever MQL-to-pipeline conversion drops more than 3 percentage points from baseline.

OBJECTIVE: Design a production-ready, AI-agent-managed predictive lead scoring architecture that:
- Identifies revenue-ready buyers at the moment of peak intent — before they raise their hand or contact sales — using a combination of ICP fit, behavioral engagement, and third-party intent signals
- Separates low-fit high-engagement leads (tire-kickers, competitors, students) from high-fit low-engagement leads (in-market buyers who haven't yet engaged) with explicit routing logic for each
- Produces MQL-to-pipeline conversion rates 40-60% above the current baseline by routing only high-confidence, high-fit leads to sales as true MQLs
- Runs score recalibration autonomously using won-deal signal analysis — continuously updating signal weights based on which behaviors actually predicted revenue, not which behaviors were easiest to track
- Integrates natively with your CRM and marketing automation platform — every score update, routing decision, and status change writes to the lead/contact record in real time with full audit trail

---

COMPANY & PROGRAM INPUTS:

Your Company Profile:
- Company name and product: [name + outcome-focused description, e.g., "Lattice — people management platform that consolidates performance management, OKRs, engagement surveys, and compensation benchmarking for HR leaders at 100-2,000 employee companies"]
- Business model and ACV by segment:
  * SMB (1-100 employees): [ACV and typical sales motion — self-serve or low-touch sales]
  * Mid-market (100-1,000 employees): [ACV and sales motion — SDR-sourced or inbound demo request]
  * Enterprise (1,000+ employees): [ACV and sales motion — strategic AE, multi-stakeholder, 90+ day cycle]
- Current ARR and growth target: [context for scoring model investment priority]
- Product motion: [PLG (free trial/freemium with expansion) | sales-led | PLG-assisted sales]

ICP Definition for Fit Scoring:
- Ideal buyer titles (primary economic buyer and champion personas): [e.g., "Primary: VP People, CHRO, Chief People Officer. Champion: Director of People Operations, HR Business Partner Lead, Head of Talent"]
- Company size sweet spot: [employee count or revenue range — be specific about the tier with highest LTV]
- Industries with highest conversion rates: [your top 3-5 verticals by win rate — this is the foundation of industry fit scoring]
- Disqualifying company signals: [signals that predict non-ICP leads, e.g., "government/public sector (procurement cycles incompatible), non-profits under 50 employees (budget constraints), staffing agencies (use case mismatch)"]
- Technology stack signals: [tech stack indicators that predict higher fit — e.g., "companies using BambooHR or Workday are mid-implementation of HR ops transformation and more likely to expand to performance management"]
- Firmographic data sources: [Clearbit / ZoomInfo / Apollo / Cognism — specify which enrichment tools write to your CRM]

Behavioral Engagement Signal Inventory:
- High-intent web pages (score 15-25 points each): [pricing page, ROI calculator, integration pages, case study pages, demo request page — list the specific URLs]
- Mid-intent content assets (score 8-15 points each): [benchmark reports, product webinars, comparison guides, detailed product pages — list gated and ungated assets separately]
- Low-intent content assets (score 2-7 points each): [blog posts, top-of-funnel awareness content, social follows — these signal interest but not active evaluation]
- Email engagement signals (score 3-12 points): [email open, click, click-to-specific-page — weight click-to-pricing higher than generic click]
- Direct sales engagement (score 20-40 points): [booked demo, attended demo, requested pricing conversation, responded to outbound SDR — these are highest-weight signals]
- Event signals (score 10-20 points): [webinar registration vs. attendance vs. asked a question; in-person event badge scan vs. booth conversation vs. demo station interaction]
- Competitive research signals (score 15-20 points): [visited competitor comparison page, downloaded competitive battlecard, engaged with "vs. [Competitor]" content — these indicate active evaluation]
- Product trial signals (if applicable): [login frequency, features activated, team members invited, integrations connected, data volume — each mapped to a score value reflecting PLG conversion correlation]

Third-Party Intent Data Inputs:
- Intent data provider: [Bombora / 6sense / G2 Buyer Intent / Demandbase / none]
- Intent topics tracked: [your top 5-10 Bombora topics or 6sense keywords that map to in-market buyer behavior for your category, e.g., "performance management software, employee engagement platform, OKR software, 360 review tools"]
- Intent signal scoring logic: [how intent data should modify scores — e.g., "Surge score 60+ on primary topic cluster: multiply engagement score by 1.5; G2 competitor profile visit: add 20 points; 6sense buying stage 'Decision': override threshold and route immediately regardless of engagement score"]
- Ideal surge window: [the window within which intent surge predicts conversion — typically 30-90 days for mid-market SaaS]

Current State Assessment:
- Current MQL definition: [what currently constitutes an MQL — is it a form fill, a score threshold, or sales rep judgment?]
- Current MQL-to-opportunity rate: [your baseline — what % of MQLs become pipeline opportunities?]
- Current MQL-to-closed-won rate: [% of MQLs that eventually close — this is the ground truth metric your scoring model must optimize]
- Top sales objection to marketing leads: [what does your sales team say about MQL quality? "Not senior enough," "wrong company size," "already using a competitor and not evaluating," "just downloaded content with no real intent" — these complaints map directly to scoring model gaps]
- Historical won-deal profile: [if you have it — what do your won deals look like in terms of engagement signals before they converted? What pages did they visit? What content did they download? This is the training data for your scoring model]

---

DELIVERABLES — COMPLETE ALL SECTIONS:

**1. FIT SCORE ARCHITECTURE (0-100 scale)**

Design the complete firmographic and technographic fit scoring model:

Tier 1 — Ideal ICP (Fit Score 70-100):
- Title fit scoring matrix: [exact job titles and their fit scores — VP People = 25 points, Director People Ops = 20 points, CHRO = 25 points, HR Business Partner = 15 points, individual contributor HR = 5 points]
- Company size fit: [exact employee ranges and scores — e.g., 200-500 employees = 25 points (sweet spot), 500-2,000 = 20 points, 50-200 = 15 points, 2,000+ = 10 points (longer cycle/lower conversion), <50 = 5 points]
- Industry fit: [top industries by score — e.g., SaaS/tech = 20 points, financial services = 18 points, professional services = 16 points, healthcare = 12 points, manufacturing = 8 points]
- Technology stack fit: [CRM, HRIS, and tech stack signals that predict ICP fit — BambooHR user = 8 points, Workday = 10 points, Greenhouse ATS = 7 points]
- Geography fit: [if applicable — NA = 15 points, EMEA = 10 points, APAC = 5 points]

Tier 2 — Acceptable ICP (Fit Score 40-69): Define where the score model draws the line between Tier 1 and Tier 2 based on historical conversion rate data.

Tier 3 — Poor Fit (Fit Score 0-39): Define the signals that produce low fit scores and whether these leads should enter a nurture track or be immediately disqualified.

Negative Fit Signals (score subtractions): [competitor domain (−50 points), student email (−30 points), Gmail/Yahoo personal email (−15 points), company size outside any ICP range (−20 points)]

**2. ENGAGEMENT SCORE ARCHITECTURE (0-100 scale, decays over time)**

Design the complete behavioral engagement scoring model:

High-Intent Signals (15-30 points each):
- Pricing page visit: [score + recency multiplier — visited in last 7 days = full value; 8-30 days = 75%; 31-60 days = 50%; 60+ days = 25%]
- ROI calculator completion: [score value + what data capture to trigger]
- Demo request form fill (not yet booked): [score + immediate routing trigger]
- Demo attended: [score + CRM outcome field requirements]
- Competitor comparison page visit: [score + SDR alert trigger]
- Integration page visits (3+ in single session): [score + signal of active technical evaluation]

Mid-Intent Signals (8-15 points each):
- Gated benchmark report download: [score value]
- Product webinar attendance (live): [score vs. on-demand view — live = higher weight]
- Email click to high-intent page: [score differential vs. generic click]
- Return visit within 7 days: [velocity signal — rapid return indicates active evaluation]
- Multiple stakeholders from same company engage: [buying committee signal — add 20 points per additional unique contact from same account who reaches MQL threshold]

Low-Intent Signals (2-7 points each):
- Blog post view: [score]
- Newsletter open: [score]
- Social follow or LinkedIn connection: [score]
- Webinar registration (not attended): [score]

Score Decay Model:
- Half-life decay: [engagement score decays by 50% every 30 days of inactivity for SMB/mid-market; 45 days for enterprise (longer consideration cycles)]
- Reset triggers: [any high-intent action resets the decay clock and restores score to current activity level]
- Full decay floor: [engagement score floors at 0, never negative — prevents leads from being actively penalized in ways that mask future re-engagement]

**3. COMPOSITE SCORE AND MQL THRESHOLD ARCHITECTURE**

Design the threshold logic that combines Fit and Engagement into routing decisions:

Composite Score Formula:
- MQL Score = (Fit Score × 0.4) + (Engagement Score × 0.6) [for sales-led motions where engagement is more predictive]
- Adjust weighting toward Fit Score (60%) for enterprise motions where behavioral data is sparse due to longer research cycles

MQL Threshold Design:
- Sales-Ready MQL (Composite ≥ 75): Route immediately to SDR or AE based on company size tier. SLA: 5-minute response during business hours, 1-hour SLA evenings/weekends.
- Standard MQL (Composite 55-74): Route to SDR queue. SLA: 4-hour business hours response. Enroll in SDR outreach sequence simultaneously.
- Nurture-Qualified Lead (Composite 35-54): Do NOT route to sales. Enroll in segment-specific nurture track. Re-score weekly. Route to MQL queue if score crosses 55 within 90 days.
- Recycle (Composite < 35 or Fit Score < 40 regardless of engagement): Remove from active pipeline. Tag for reactivation campaign in 90 days if engagement signals resurface.

Intent Override Rules:
- 6sense Buying Stage "Decision" + Fit Score ≥ 50: Override threshold, route immediately to senior AE regardless of engagement score
- Bombora Surge Score 80+ on primary topic + Fit Score ≥ 60: Elevate to Sales-Ready MQL regardless of engagement score (intent data compensates for low engagement in dark-funnel research phase)
- G2 competitor profile visit from known contact: Add 20 points to engagement score, flag as "competitive evaluation in progress" in CRM, alert assigned SDR/AE within 15 minutes

**4. LEAD ROUTING AND SLA ARCHITECTURE**

Design the complete routing decision tree:

By ICP Tier and Company Size:
- Tier 1 Enterprise (1,000+ employees, Fit ≥ 70, Composite ≥ 75): Route to Enterprise AE + notify CSM if existing customer contact. Skip SDR entirely. AE SLA: 15 minutes to acknowledge.
- Tier 1 Mid-Market (200-1,000 employees, Fit ≥ 70, Composite ≥ 55): Route to SDR for qualification call, then AE. SDR SLA: 4 hours. Include full behavioral history in route notification.
- Tier 1 SMB (50-200 employees, Fit ≥ 60, Composite ≥ 65): Route to SMB AE or pooled SDR depending on volume. High-velocity motion: demo within 24 hours of MQL.
- Tier 2 Any Size (Fit 40-69, Composite ≥ 55): Route to pooled SDR queue with lower priority. Automate first 2 touches before human handoff.
- Existing Customer Contact (any score): Route to CSM for expansion conversation, not SDR. Flag as expansion opportunity in CRM.

Routing Notification Contents (what the SDR/AE receives):
- Lead name, title, company, fit score, engagement score, composite score
- Top 5 behavioral signals (pages visited, content downloaded, emails clicked) with timestamps
- Company firmographic snapshot (size, industry, tech stack)
- Intent data summary (if available)
- Recommended first outreach talking point based on most recent high-intent action
- Links to relevant case studies and battlecards pre-populated for their industry

**5. SCORE DECAY AND RE-ENGAGEMENT ARCHITECTURE**

Decay Rules:
- Nightly decay job: runs at 2 AM in each region, applies half-life decay formula to all engagement scores inactive for 30+ days
- Decay notification: when composite score drops below MQL threshold, automatically move lead from MQL status to Nurture status, pause any active SDR sequences, enroll in long-cycle nurture track
- Hard expiry: leads with Fit Score < 40 and engagement score at 0 for 180 days are tagged "Dormant" and excluded from active scoring to reduce noise in MQL pipeline reports

Re-Engagement Architecture:
- 90-day reactivation campaign: Dormant leads with Fit Score ≥ 60 receive quarterly reactivation email with new benchmark content. Any engagement above 5-point threshold restarts the scoring clock.
- Website return detection: Dormant contact identified via IP/cookie/known email — triggers re-engagement alert and restores behavioral scoring from zero
- Company-level signal trigger: If any contact at a Dormant account shows buying intent via intent data, re-activate all Dormant contacts at that account and route account to SDR for account-level outreach

**6. AI AGENT AUTOMATION ARCHITECTURE**

Define the autonomous AI agent workflows:

Real-Time Score Calculation Agent:
- Trigger: every trackable lead interaction event (page view, form fill, email click, etc.)
- Action: recalculate composite score, update CRM record, check threshold crossing, trigger routing if MQL threshold breached
- Latency requirement: score update and routing decision within 60 seconds of triggering event

MQL Routing Agent:
- Trigger: composite score crosses MQL threshold
- Action: look up routing rules based on fit tier and company size, assign to correct owner in CRM, create task with SLA timestamp, enroll in correct post-MQL sequence, send routing notification with behavioral context
- Escalation: if SLA missed (no activity logged within SLA window), auto-escalate to manager with alert

Score Recalibration Agent (Monthly):
- Input: closed-won and closed-lost deals from prior 90 days with full lead score history
- Analysis: calculate MQL-to-opportunity rate and MQL-to-closed-won rate by composite score band; identify which behavioral signals were most correlated with closed-won outcomes
- Output: recommended signal weight adjustments for human review; auto-apply adjustments within ±10% of current weights without human approval; flag larger adjustments for quarterly model review

Score Quality Monitoring Agent (Weekly):
- Alert triggers: MQL-to-opportunity rate drops below baseline by 3+ percentage points; average fit score of MQLs drops by 10+ points; SDR accept rate of MQLs drops below 70%
- Action: auto-generate diagnostic report identifying which signals or threshold changes drove the quality shift; route to VP Marketing and RevOps for review

**7. MEASUREMENT AND CLOSED-LOOP ANALYTICS FRAMEWORK**

Primary KPIs (weekly scorecard):
- MQL volume by source (inbound, content, events, SDR-sourced, intent-triggered)
- MQL-to-opportunity conversion rate by score band and ICP tier
- MQL-to-closed-won rate by score band
- Average days from MQL to opportunity creation
- SDR MQL accept rate (% of MQLs accepted vs. rejected by sales)
- Score accuracy index: % of MQLs above 75 composite that convert to opportunity within 30 days

Secondary KPIs (monthly model health):
- False positive rate: MQLs that sales rejected or that never converted to opportunity
- False negative rate: opportunities created from leads that were below MQL threshold (indicates model is too conservative)
- Score decay effectiveness: re-engagement rate of leads that decayed out of MQL and re-entered via reactivation campaigns
- Intent data lift: MQL-to-pipeline conversion rate for intent-triggered overrides vs. standard MQL routing

Quarterly Model Audit:
- Full won-deal signal analysis: map all behavioral signals of closed-won deals from prior quarter, identify signals that were underweighted or missing from current model
- Lost-deal signal analysis: identify common behavioral patterns in closed-lost deals that the model incorrectly elevated to MQL status
- Competitive landscape update: add new competitor comparison pages, new product features, and new intent topics to scoring model
- Threshold recalibration: adjust MQL thresholds based on current conversion rate data

---

## Example Input/Output

**Input Example:**

Company: Mosaic — financial planning and analysis (FP&A) SaaS for finance teams at 100-2,000 employee companies
ACV: $35,000 mid-market, $95,000 enterprise
Sales Motion: Demo → 2-week PoC → proposal → close; avg 38 days mid-market, 90 days enterprise
MQL Volume: 280/month
Current MQL-to-Opportunity Rate: 9% (extremely low — sales team complains about lead quality constantly)
CRM: Salesforce
Marketing Automation: Marketo
Intent Data: Bombora (topics: FP&A software, financial planning tool, budgeting software, CFO tech stack)
Top Sales Objection: "Most MQLs are analysts who downloaded a template — not finance leaders with authority to buy"

**Output Example (excerpt):**

**Fit Score Architecture for Mosaic:**

Title Fit Matrix:
- CFO: 30 points (highest — economic buyer with budget authority)
- VP Finance: 28 points (primary buyer for mid-market)
- Controller: 22 points (strong evaluator influence, sometimes buyer at SMB)
- Director FP&A: 25 points (champion persona — most likely to drive internal evaluation)
- Finance Manager: 15 points (influencer, not buyer — route to nurture, not sales)
- Financial Analyst: 5 points (end user with zero budget authority — this is the MQL quality problem; DO NOT route to sales)

Company Size Fit:
- 200-1,000 employees: 25 points (mid-market sweet spot, highest conversion rate)
- 1,000-3,000 employees: 22 points (enterprise, longer cycle but higher ACV)
- 50-200 employees: 16 points (possible, but lower ACV makes unit economics marginal)
- <50 employees: 3 points (not ICP — route to self-serve, do not involve sales)
- >5,000 employees: 8 points (typically have in-house FP&A or incumbent vendor)

Industry Fit:
- SaaS / technology: 20 points (largest TAM segment, fast decisions)
- Financial services: 18 points (high urgency, strong FP&A investment)
- Professional services: 16 points
- Healthcare / life sciences: 14 points

Root Cause of 9% MQL-to-Opp Rate:
The current scoring model treats all behavioral signals equally — meaning a financial analyst downloading a free forecasting template scores identically to a CFO visiting the pricing page. The fix: implement title fit as a hard gate. Any contact with Fit Score < 35 (analysts, coordinators, ICs) should be auto-routed to a self-serve nurture track, never to SDR queue. Implementing this alone is projected to improve MQL-to-Opportunity rate from 9% to 22-28% by reducing SDR waste on non-buyers.

MQL Threshold Recommendation:
- Current estimated threshold: score ≥ 40 (too low, causing quality problem)
- Recommended threshold: Fit Score ≥ 55 AND Composite Score ≥ 70
- This will reduce MQL volume by ~35% initially but increase MQL-to-Opportunity rate from 9% to an estimated 22-28%
- Net pipeline impact: positive — 180 fewer MQLs but generating 2.3× more opportunities from those MQLs

Bombora Intent Configuration:
- Surge Score ≥ 65 on "FP&A software" or "financial planning tool" + Fit Score ≥ 60: override threshold, route immediately to AE with alert "CFO/VP Finance at ICP company showing active buying intent — prioritize today"
- This intent override is estimated to capture 20-30 additional high-intent accounts per month that were previously invisible because the finance leader hadn't yet visited Mosaic's website

## Success Metrics

**Model Performance:**
- MQL-to-opportunity conversion rate ≥ 20% within 60 days of deployment (vs. industry average of 12-15%)
- Sales team MQL accept rate ≥ 80% (SDRs accept and work the lead vs. returning as poor quality)
- Average composite score of converted opportunities ≥ 70 (confirms model is accurately identifying high-value leads)
- False positive rate ≤ 15% (MQLs that don't convert to opportunity within 60 days)

**Revenue Impact:**
- Pipeline generated per MQL increases 30-50% compared to pre-implementation baseline
- SDR productivity: hours saved per week no longer spent on low-fit leads
- Marketing-sourced pipeline increases as higher-quality MQLs close at higher rates
- Time-from-MQL-to-closed-won decreases as sales focuses on buyers with demonstrated intent

**Model Health:**
- Score decay effectiveness: ≥ 25% of re-engaged dormant leads convert to MQL within 90 days
- Intent data lift: intent-triggered MQLs convert to opportunity at 1.8× the rate of standard MQLs
- Monthly recalibration keeps MQL-to-pipeline rate within ±2 percentage points of target

## Related Prompts
- [AI-Powered B2B SaaS Demand Generation Waterfall Architecture](../Demand-Generation-Operations/AI-Powered-B2B-SaaS-Demand-Generation-Waterfall-Architecture-&-Marketing-Funnel-Conversion-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Marketing Automation Architecture & Lifecycle Campaign Revenue Intelligence Engine](../Demand-Generation-Operations/AI-Powered-B2B-SaaS-Marketing-Automation-Architecture-&-Lifecycle-Campaign-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Intent Data Vendor Evaluation & Buyer Signal Stack Architecture](../Demand-Generation-Operations/AI-Powered-B2B-SaaS-Intent-Data-Vendor-Evaluation-&-Buyer-Signal-Stack-Architecture-Revenue-Intelligence-Engine.md)
- [AI-Powered ABM Intent Data Activation & Buying Signal Prioritization Engine](../Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)

## Integration Tips

**Salesforce Integration:**
- Use Salesforce Lead Scoring fields (custom number fields) for Fit Score, Engagement Score, and Composite Score — update via Marketing Automation platform or direct API write
- Build Process Builder / Flow automation to trigger routing assignments when Composite Score crosses MQL threshold
- Create a Salesforce dashboard with MQL-to-Opportunity conversion rate sliced by Composite Score band — run weekly to monitor model health
- Implement Salesforce "MQL Reject Reason" picklist to capture why sales rejects MQLs — this closed-loop data is gold for monthly recalibration

**HubSpot Integration:**
- Use HubSpot's native lead scoring tool for engagement signals; supplement with custom properties for Fit Score components
- Build HubSpot Workflows triggered by composite score thresholds to assign lead owner, create tasks, and enroll in sequences
- Use HubSpot Playbooks to deliver routing notification context (behavioral history, recommended talk tracks) to assigned SDR/AE
- Connect HubSpot to Databox or Looker Studio for real-time MQL quality dashboards

**Marketo Integration:**
- Use Marketo's multi-dimensional scoring (Demographic Score + Behavioral Score) as the native framework for Fit and Engagement scores respectively
- Build Marketo Smart Campaigns triggered on score threshold breaches to execute routing logic and sequence enrollment
- Connect Marketo to Salesforce via native sync — write lead score data back to Salesforce in real time for AE/SDR visibility
- Use Marketo Revenue Cycle Analytics to build the MQL-to-Opportunity funnel velocity report

**Intent Data Integration:**
- Bombora: ingest surge data via CSV or API daily; build automation rule that adds intent score bonus when primary topic surge exceeds threshold
- 6sense: use 6sense's native Salesforce/HubSpot integration to write buying stage data; build routing override rule for "Decision" stage accounts
- G2 Buyer Intent: connect via Zapier or native integration; trigger SDR alert within 15 minutes of G2 profile visit by known contact

**Enrichment Integration:**
- Clearbit or ZoomInfo: auto-enrich new leads at creation to populate firmographic data for fit scoring; build enrichment workflow that fires on every new lead created from form fill, chat, or import
- Apollo: use Apollo's company data to backfill firmographic scores on existing database contacts
- Cognism: for EMEA-focused scoring, use Cognism for GDPR-compliant firmographic enrichment

## Troubleshooting

**Problem: MQL-to-Opportunity Rate is still low despite implementing the scoring model.**
Solution: The most common cause is that MQL thresholds were set based on desired MQL volume targets ("we need 300 MQLs/month") rather than conversion rate analysis. Pull a cohort report of the last 90 days of closed-won deals and trace each back to their composite score at MQL creation. If your closed-won deals were concentrated in composite scores 75-100 but you're passing everything above 55 as MQL, raise your threshold. Accept fewer MQLs and watch pipeline per MQL increase. Sales team acceptance of this trade-off requires CMO-CRO alignment.

**Problem: Sales team is rejecting MQLs and routing them back to marketing as "not ready."**
Solution: Implement mandatory MQL rejection taxonomy — require SDRs to select a reason from a dropdown (Not senior enough title / Company too small / Already a customer / Competitor / Not in market / Wrong industry / Other) when returning an MQL. After 30 days of rejection data, run a breakdown: if "Not senior enough title" represents 30%+ of rejections, your title fit scoring is too permissive. If "Already a customer" is top, you need a customer contact exclusion rule. Each rejection reason maps directly to a scoring model fix.

**Problem: The scoring model produces very different results for inbound vs. outbound leads.**
Solution: This is expected and correct — inbound leads self-select by engaging with your content, which inflates their behavioral engagement score. Outbound leads have the same firmographic fit but lower behavioral engagement. For outbound-sourced contacts, apply a "cold outbound" modifier: weight Fit Score at 70% and Engagement Score at 30% (reverse of inbound weighting) for the first 30 days. After 30 days of outbound engagement, revert to standard composite formula. This prevents outbound leads from perpetually failing to reach MQL thresholds due to low behavioral data, while still requiring some engagement signal before routing to AE.

## Version History
- v1.0: Initial creation (auto-generated)
