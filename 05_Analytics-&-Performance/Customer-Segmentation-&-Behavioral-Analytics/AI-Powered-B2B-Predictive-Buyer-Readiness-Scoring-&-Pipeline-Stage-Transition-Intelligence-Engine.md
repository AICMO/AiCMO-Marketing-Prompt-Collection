# AI-Powered B2B Predictive Buyer Readiness Scoring & Pipeline Stage Transition Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, saas, analytics, lead-scoring, buyer-readiness, pipeline-velocity, behavioral-data, predictive-analytics, demand-generation, revenue-intelligence

## Overview
Designs a multi-signal buyer readiness scoring model that predicts when a prospect will transition from one pipeline stage to the next, then produces the automated activation playbook and measurement framework to act on those predictions in real time. Use this when your MQL-to-SQL conversion is unpredictable, sales complains about lead quality, or your pipeline stages feel like guesses rather than data-driven milestones.

## Quick Copy-Paste Version

You are a senior B2B revenue intelligence strategist specializing in predictive lead scoring and pipeline analytics. I need a buyer readiness scoring model and stage-transition playbook for my business.

Here is my context:
- Company: [Your Company]
- Product: [One sentence — what it does and who it serves]
- Business model: [SaaS / usage-based / transactional]
- Current pipeline stages: [e.g., Subscriber → MQL → SAL → SQL → Opportunity → Closed Won]
- Average sales cycle: [X days]
- Average deal size: [ACV]
- Lead volume per month: [X]
- Biggest pipeline bottleneck: [Which stage-to-stage transition has the worst conversion or most slowdown?]
- Signals available today: [Check which you have: website visits, email clicks, content downloads, demo requests, product usage (if PLG), intent data (Bombora/G2), LinkedIn engagement, CRM activity log, support tickets, event attendance]
- CRM used: [Salesforce / HubSpot / Pipedrive / other]

Please deliver:

1. READINESS SCORING FRAMEWORK
Design a 0–100 buyer readiness score with three distinct bands (Cold: 0–39, Warm: 40–74, Ready: 75–100). For each band, define: the behavioral signals that qualify it, the implied buyer journey stage, the recommended next action, and the routing logic (nurture vs. marketing follow-up vs. SDR outreach vs. AE engagement).

2. SIGNAL WEIGHT MATRIX
Build a signal weight table with at least 12 specific signals mapped to my business context. For each signal assign: a base point value (1–25), a decay rule (does the signal lose value over time — if so, how fast?), a multiplier condition (e.g., if signal occurs within 48 hours of another high-intent signal, multiply by 1.5x), and a negative signal option (signals that should reduce the score, like unsubscribing or long periods of inactivity).

3. STAGE-TRANSITION TRIGGER PLAYBOOK
For each pipeline stage transition I listed, define: the minimum readiness score threshold required to advance, the combination of signals that must be present (not just score — specific activity fingerprint), the automated action to fire when threshold is crossed (email, alert, task, field update), and the SLA for human follow-up once triggered.

4. SCORE DECAY & RE-ENGAGEMENT ARCHITECTURE
Design the decay model: how should scores drop when a prospect goes dark? At what score floor should a re-engagement sequence fire? Provide the re-engagement sequence trigger logic and the 3 best re-engagement tactics for cold-scored prospects in my context.

5. IMPLEMENTATION ROADMAP
Provide a 6-week implementation plan: Week 1-2 (signal audit and CRM field setup), Week 3-4 (scoring logic build and test), Week 5-6 (sales alignment and threshold calibration). Include the 3 most common mistakes teams make when launching readiness scoring models and how to avoid them.

Output as a complete revenue intelligence brief that both the marketing ops team and VP of Sales can align on.

## Advanced Customizable Version

ROLE: You are a Principal Revenue Intelligence Architect with 14+ years of experience designing predictive scoring models for B2B SaaS companies from Series A through pre-IPO. You have deep expertise in multi-touch attribution, behavioral cohort analysis, intent signal taxonomy design, and the revenue operations stack (Salesforce, HubSpot, Marketo, Pardot, 6sense, Bombora, Clearbit, G2 Buyer Intent, Zoominfo, Outreach, Salesloft). You understand that buyer readiness is not a single score but a composite of: engagement velocity (rate of signal acceleration), intent breadth (how many intent categories are firing), fit alignment (how well the account matches ICP), and relationship depth (how many stakeholders are engaged). Your frameworks are used by revenue teams managing $5M–$150M ARR to reduce sales cycle length by 20–40% and improve MQL-to-SQL conversion by 30–50%.

---

COMPANY CONTEXT:
- Company name: [COMPANY_NAME]
- Product category: [CATEGORY — e.g., "Revenue intelligence platform for enterprise B2B sales teams"]
- Business model: [BUSINESS_MODEL — SaaS subscription / usage-based / seat-based / transactional]
- Stage: [STAGE — Series A / B / C / Growth / Public]
- ARR: [$ARR]
- Average ACV: [$ACV]
- Average sales cycle length: [SALES_CYCLE_DAYS] days
- Primary buyer persona(s): [PERSONA_1, PERSONA_2 — e.g., "VP Sales, RevOps Director"]
- Secondary stakeholders in buying committee: [STAKEHOLDERS — e.g., "CRO, CFO, IT Security"]
- Sales motion: [SALES_MOTION — Inbound / Outbound / PLG + Sales-Assist / Channel / Hybrid]
- SDR team size: [SDR_COUNT]
- AE team size: [AE_COUNT]
- CRM: [CRM — Salesforce / HubSpot / other]
- Marketing automation: [MAP — Marketo / HubSpot / Pardot / other]
- Intent data providers: [INTENT_PROVIDERS — Bombora / G2 Buyer Intent / 6sense / TechTarget / none]
- Product analytics: [PRODUCT_ANALYTICS — Amplitude / Mixpanel / Heap / Pendo / none — only if PLG/trial]

CURRENT PIPELINE STAGES:
[List all pipeline stages in order, e.g.:]
- Stage 1: [STAGE_NAME] — Definition: [HOW_YOU_CURRENTLY_DEFINE_IT]
- Stage 2: [STAGE_NAME] — Definition: [HOW_YOU_CURRENTLY_DEFINE_IT]
- Stage 3: [STAGE_NAME] — Definition: [HOW_YOU_CURRENTLY_DEFINE_IT]
- Stage 4: [STAGE_NAME] — Definition: [HOW_YOU_CURRENTLY_DEFINE_IT]
- Stage 5: [STAGE_NAME] — Definition: [HOW_YOU_CURRENTLY_DEFINE_IT]

CURRENT STAGE CONVERSION RATES (if known):
- [Stage 1 → Stage 2]: [X%] converting in avg [Y days]
- [Stage 2 → Stage 3]: [X%] converting in avg [Y days]
- [Stage 3 → Stage 4]: [X%] converting in avg [Y days]
- [Stage 4 → Stage 5 / Close]: [X%] converting in avg [Y days]
- Biggest bottleneck stage: [BOTTLENECK_STAGE] — suspected reason: [SUSPECTED_REASON]

SIGNALS AVAILABLE (check all that apply and provide data fidelity level):
Website Behavioral:
- [ ] Page visits tracked at contact level (via cookie/IP matching): [YES/NO — if yes, fidelity: all contacts / known contacts only]
- [ ] High-intent pages tracked: [LIST — e.g., pricing, demo, case studies, comparison pages]
- [ ] Scroll depth / time-on-page tracked: [YES/NO]
- [ ] Chat or chatbot interactions: [YES/NO — platform: Drift / Intercom / other]
- [ ] Reverse IP lookup for anonymous visitors: [YES/NO — provider: Clearbit / 6sense / Demandbase / Albacross]

Email Engagement:
- [ ] Email opens tracked: [YES/NO — note: Apple MPP may inflate opens]
- [ ] Email clicks tracked at URL level: [YES/NO]
- [ ] Email reply tracking: [YES/NO]
- [ ] Unsubscribes / spam reports tracked as negative signals: [YES/NO]

Content & Gated Asset:
- [ ] Content downloads tracked at contact level: [YES/NO]
- [ ] Webinar registrations and attendance: [YES/NO]
- [ ] Free tool / calculator usage: [YES/NO]
- [ ] Interactive assessment completions: [YES/NO]

Sales Activity (CRM):
- [ ] Meeting booked / attended: [YES/NO]
- [ ] Demo attended: [YES/NO]
- [ ] Multi-stakeholder engagement (more than 1 contact from account active): [YES/NO]
- [ ] RFP or security review submitted: [YES/NO]
- [ ] Legal / procurement engaged: [YES/NO]
- [ ] Champion identified and tagged in CRM: [YES/NO]

Third-Party Intent:
- [ ] Bombora topic surge data: [YES/NO — topics tracked: LIST]
- [ ] G2 Buyer Intent (profile visits, category comparisons): [YES/NO]
- [ ] 6sense predictive scores: [YES/NO]
- [ ] LinkedIn engagement data (company-level): [YES/NO]
- [ ] Job postings indicating technology buying intent: [YES/NO — provider: Theirstack / Builtwith / other]
- [ ] Technographic signals (competitor in stack, complementary tool added): [YES/NO]

Firmographic Fit Signals:
- [ ] ICP match score (company size, industry, geography): [YES/NO — how calculated?]
- [ ] Funding event (Series raise, PE acquisition): [YES/NO — provider]
- [ ] Leadership change (new CRO, VP Sales, CMO hired): [YES/NO — provider: LinkedIn / Zoominfo]
- [ ] Headcount growth in target department: [YES/NO]

Product / PLG Signals (if applicable):
- [ ] Free trial started: [YES/NO]
- [ ] Activation milestone reached (define it): [ACTIVATION_EVENT]
- [ ] Feature X used (define feature that predicts conversion): [CONVERSION_FEATURE]
- [ ] Seat expansion within trial: [YES/NO]
- [ ] Integration connected: [YES/NO]

NEGATIVE SIGNALS (score reducers):
- [NEGATIVE_SIGNAL_1 — e.g., email unsubscribe, 60 days of no engagement, competitive replacement request]
- [NEGATIVE_SIGNAL_2]
- [NEGATIVE_SIGNAL_3]

HISTORICAL WIN/LOSS PATTERNS (if available):
- Signals most commonly present in Closed Won deals: [LIST_TOP_3 or "unknown"]
- Signals most commonly present in Closed Lost deals: [LIST_TOP_3 or "unknown"]
- Average number of stakeholders engaged in won deals: [X or "unknown"]
- Most predictive activity in the 30 days before a deal closes: [ACTIVITY or "unknown"]

---

DELIVERABLE 1: BUYER READINESS SCORE ARCHITECTURE

Design a composite readiness score (0–100) built from four sub-dimensions:

A. ENGAGEMENT VELOCITY SCORE (0–25 points)
Measures rate of acceleration — not just whether signals are happening, but whether they're happening faster this week than last week. Define:
- The rolling time window for velocity calculation (7-day recommended for most B2B deals)
- The velocity multipliers: if a prospect has 3x more touches this week vs. last 2-week average, what does that add to the score?
- The velocity decay: how does score adjust when velocity slows?
- The "spike alert" threshold that should notify SDR/AE immediately regardless of total score

B. INTENT BREADTH SCORE (0–25 points)
Measures how many distinct intent categories are activated. More categories = more active buying committee. Define:
- The intent categories relevant to [COMPANY_NAME]'s product (use 4–6 specific Bombora/G2 topic categories)
- The point allocation per active intent category
- The diminishing returns curve (each additional category adds slightly less)
- The cross-source bonus: if both first-party behavioral and third-party intent align on the same category, award bonus points

C. ICP FIT SCORE (0–25 points)
Measures firmographic and technographic alignment to ideal customer profile. Define:
- The ICP scoring rubric (company size band, target industry match, geography, funding stage, tech stack fit)
- The fit tier classifications (Perfect Fit: 20–25 / Strong Fit: 14–19 / Moderate Fit: 8–13 / Weak Fit: 0–7)
- The over-ride rule: if fit score is below 8, no amount of engagement score should push the account to SQL-ready status
- The technographic displacement bonus: competitor in stack = additional X points (signals active evaluation)

D. RELATIONSHIP DEPTH SCORE (0–25 points)
Measures multi-threading — how many stakeholders from the account are engaged and at what depth. Define:
- Single contact engaged only: X points
- Two contacts engaged (different departments): X points
- Champion identified + economic buyer engaged: X points
- Legal / procurement or IT security contact added: X points (strong late-stage signal)
- Executive sponsor engaged (C-suite email reply or meeting): X points (maximum depth bonus)

---

DELIVERABLE 2: STAGE-TRANSITION THRESHOLD MAP

For each pipeline stage transition in [COMPANY_NAME]'s model, produce:

1. Minimum total readiness score to trigger consideration for advancement
2. Mandatory signal fingerprint (which specific signals MUST be present — score alone is insufficient)
3. Blocking conditions (which negative signals prevent advancement even if score threshold is met)
4. Automated action sequence triggered at threshold crossing:
   - CRM field updates (stage, score, trigger date, signal fingerprint record)
   - Internal alert (who is notified, via what channel, within what SLA)
   - Outbound action (automated email, SDR task, AE notification)
   - Content asset to serve (most relevant asset for the buyer's current readiness band)
5. SLA clock: from threshold crossing to human action, maximum acceptable response time (in hours, not days)
6. Failure mode: what happens if the SLA is missed — escalation path and score impact

---

DELIVERABLE 3: SCORE DECAY & DARK PROSPECT RE-ENGAGEMENT SYSTEM

Design the decay architecture:

PASSIVE DECAY MODEL:
- Define score half-life: after how many days of zero activity does score drop by 50%?
- Define floor thresholds by segment: what is the minimum score that preserves a prospect's current pipeline stage without requiring re-qualification?
- Define the "dormant" trigger: at what point does the system move a prospect from active pipeline to dormant nurture?

RE-ENGAGEMENT TRIGGER PLAYBOOK:
For prospects who have decayed below the warm band (score < 40), design:
- Trigger 1 (Behavioral Re-Engagement): Which content asset or free tool experience is most likely to reactivate a cold prospect? Produce the subject line and email body for the trigger email (2–3 sentences max, no pitch, pure value).
- Trigger 2 (Intent Signal Re-Engagement): If third-party intent data shows renewed activity on relevant topics while first-party score is low (the "dark social" buyer), what is the action sequence?
- Trigger 3 (Life Event Re-Engagement): If a champion changes jobs (detected via LinkedIn), design the "new job congratulations + soft re-intro" outreach sequence (3 touches, multi-channel).
- Trigger 4 (Competitor Event Re-Engagement): If a competing vendor announces a price increase, acquisition, or major product issue, design the automated win-back sequence for cold prospects who previously lost to that competitor.

---

DELIVERABLE 4: SIGNAL CALIBRATION & MODEL HEALTH FRAMEWORK

Design the ongoing model governance system:

MONTHLY CALIBRATION RITUAL:
- Which 3 data pulls determine if the model is working? (Win/loss correlation analysis, score-at-close distribution, score-at-loss distribution)
- How often should signal weights be recalibrated? Define the trigger for an off-cycle recalibration (e.g., if win rate drops more than 10 points MoM)
- Define the "leading indicator" that proves the model is predictive BEFORE deals close (e.g., score-to-demo conversion rate)

A/B TESTING PROTOCOL:
Design a 90-day model validation test:
- Control group: current scoring model (or no scoring)
- Test group: new readiness scoring model
- Primary metric: stage-conversion rate improvement
- Statistical significance threshold for declaring winner
- How to split test without biasing the sales team's behavior

REPORTING DASHBOARD DESIGN:
Define the 5 KPIs that should appear on the Revenue Intelligence Dashboard:
- Score distribution heatmap: where is the pipeline concentrated by readiness band?
- Stage-transition velocity: average days to advance by readiness band
- Signal leakage report: which high-scoring prospects are NOT being acted on within SLA?
- Model accuracy score: % of high-readiness prospects (75+) that advanced to next stage within 30 days
- Re-engagement ROI: % of reactivated dormant prospects that re-entered active pipeline

---

DELIVERABLE 5: SALES & MARKETING ALIGNMENT PROTOCOL

The model fails if sales doesn't trust it. Design the alignment plan:

SALES ADOPTION PLAYBOOK:
- How to present the readiness score to AEs without it feeling like "marketing's opinion"
- The 3 objections sales will raise and the data-backed responses to each
- The threshold calibration session: a 2-hour workshop design where sales reviews the first 30 days of scored leads and tunes the thresholds collaboratively
- The "score explains the why" framework: for every SDR touchpoint, how to reference the score in a way that makes the outreach feel personalized, not robotic

FEEDBACK LOOP MECHANISM:
- How AEs provide win/loss signal back to the model (CRM field + 2-click feedback form)
- How that feedback auto-adjusts signal weights over time
- How marketing reviews AE feedback in the weekly pipeline review to detect systematic false positives (high-score prospects that don't close) or false negatives (low-score prospects that close unexpectedly)

---

DELIVERABLE 6: IMPLEMENTATION ROADMAP

Produce a phased 8-week build plan for [COMPANY_NAME]:

Week 1–2: Signal Audit & Data Infrastructure
Week 3–4: Scoring Logic Design & CRM Configuration
Week 5: Sales Enablement & Threshold Calibration Workshop
Week 6: Soft Launch (scoring visible in CRM but not yet triggering automations)
Week 7: Full Launch with Automated Triggers Active
Week 8: First Calibration Review & Score Weight Adjustment

For each phase: primary owner (Marketing Ops / RevOps / Sales Enablement), key deliverable, success criteria, and top risk with mitigation.

Output as a complete strategic implementation document that can be handed directly to the Marketing Operations and RevOps team to begin build immediately.

## Example Input/Output

**Input Example:**

- Company: Meridian CX (AI-powered customer experience platform for enterprise financial services)
- Business model: SaaS subscription, seat-based
- Stage: Series C, $28M ARR
- ACV: $85,000
- Sales cycle: 94 days average
- Pipeline stages: Lead → MQL → SAL → SQL → Technical Eval → Commercial Negotiation → Closed
- Biggest bottleneck: SAL → SQL (only 31% converting, avg 27 days stuck)
- Signals available: HubSpot MAP, website tracking (known contacts only), Bombora (5 topics), G2 Buyer Intent, LinkedIn engagement, Salesforce CRM activity
- ICP: Financial services firms 1,000–10,000 employees, VP/Director CX or CCO buyer, US/UK

**Output Example (excerpt):**

**BUYER READINESS SCORE ARCHITECTURE — MERIDIAN CX**

Composite Score (0–100) built from four sub-dimensions:

**A. Engagement Velocity Score (0–25)**
Rolling 7-day velocity window. Baseline: contact average touches per week over prior 28 days.
- Velocity ratio 1.0–1.4x (slight uptick): +5 points
- Velocity ratio 1.5–2.4x (meaningful acceleration): +12 points
- Velocity ratio 2.5x+ (spike — buyer actively researching): +20 points + immediate SDR spike alert
- Spike alert threshold: 3x velocity in any 72-hour window triggers Slack notification to assigned SDR within 15 minutes
- Velocity decay: score reduced by 3 points for every 5 business days of zero activity below baseline

**B. Intent Breadth Score (0–25)**
Bombora topics monitored: "Customer Experience Software," "AI Contact Center," "CCaaS," "Financial Services Technology," "CX Transformation"
- 1 topic surging: +8 points
- 2–3 topics surging: +16 points (first topic: 8 pts, each additional: 4 pts)
- 4+ topics surging: +22 points (diminishing returns above 3)
- Cross-source bonus: Bombora surge + G2 profile visit in same 14-day window: +5 bonus points
- G2 category comparison visit (vs. Genesys, NICE, Verint): +10 points (active vendor comparison signal)

**SAL → SQL STAGE-TRANSITION THRESHOLD:**
Minimum total readiness score: 68
Mandatory signal fingerprint (ALL must be true):
  ✓ Pricing page visited at least once in prior 14 days
  ✓ At least 2 contacts from the account active in the past 21 days (multi-threading)
  ✓ At least one demo or discovery call completed (CRM activity log)
  ✓ G2 Buyer Intent OR Bombora surge on 2+ topics
Blocking conditions:
  ✗ Unsubscribe event in the past 30 days
  ✗ Sales marked "Not a fit" or "Disqualified" in prior 90 days
  ✗ No response to last 3 outreach attempts (all channels) in the past 21 days

Automated trigger at threshold crossing:
  1. CRM: Stage field auto-updated to SQL, timestamp logged, signal fingerprint stored in custom object
  2. Slack alert to AE: "Meridian alert: [Account] just crossed SQL readiness threshold (score: 74). 2 contacts active, G2 comparison visit 3 days ago, pricing page 2x. Recommended opener attached."
  3. AE task created: "Reach out with ROI calculator + CCX benchmark report" — SLA: 4 business hours
  4. Automated email to primary contact (from AE's address): Value-add resource — not a follow-up, a "thought you'd find this relevant" send tied to the specific intent signal detected

---

## Success Metrics

- **Model Accuracy Rate:** % of prospects scoring 75+ that advance to next pipeline stage within 30 days — target: ≥55% (vs. baseline without scoring)
- **SAL→SQL Conversion Improvement:** Target 20–35% lift in stage conversion rate within 90 days of model launch
- **Sales Cycle Compression:** Reduction in average days-stuck at bottleneck stage — target: 15–25% reduction
- **SDR Efficiency:** % of SDR outreach to 75+ score prospects vs. total outreach — target: ≥60% of capacity directed to high-readiness accounts
- **False Positive Rate:** % of SQL-advanced accounts that stall or lose in next 60 days — target: <30%
- **Re-Engagement Success Rate:** % of dormant prospects reactivated by triggered re-engagement sequences that re-enter active pipeline — target: ≥12%
- **Score-at-Close Distribution:** Median readiness score at Closed Won deals — target: ≥72; if median is below 60, model needs recalibration

## Related Prompts

- [Lead Scoring Model Optimization & Predictive Buying Signal Intelligence Engine](../../05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md)
- [AI-Powered Customer Segmentation & Behavioral Cohort Intelligence Engine](../../05_Analytics-&-Performance/Customer-Segmentation-&-Behavioral-Analytics/AI-Powered-Customer-Segmentation-&-Behavioral-Cohort-Intelligence-Engine.md)
- [ABM Intent Data Activation & Buying Signal Prioritization Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [Marketing Funnel Conversion & Pipeline Velocity Intelligence Engine](../../05_Analytics-&-Performance/Funnel-Conversion-&-Pipeline-Velocity/Marketing-Funnel-Conversion-&-Pipeline-Velocity-Intelligence-Engine.md)

## Integration Tips

- **Salesforce:** Create a custom Score object with fields for Total Score, sub-dimension scores, signal fingerprint JSON, last score date, and decay status. Use Salesforce Flow to trigger stage-advancement tasks and Slack alerts when thresholds are crossed. Install the Bombora Salesforce integration to ingest intent surges directly into account records.
- **HubSpot:** Use the HubSpot Lead Scoring tool for foundational scoring, then layer advanced logic via Workflows. Set up custom contact properties for each sub-dimension score. Use HubSpot's predictive lead score as a baseline, then layer the manual signal weights on top via calculated properties.
- **6sense:** Map 6sense buying stage predictions (Awareness / Consideration / Decision) to your readiness bands. Use 6sense's segment builder to auto-surface accounts in the "Decision" stage as readiness score inputs. Configure 6sense to push account-level scores into Salesforce/HubSpot via native integration.
- **Bombora:** Subscribe to 8–12 topics most relevant to your product category. Use Bombora's Company Surge API to pull weekly topic surge data and map surges to the Intent Breadth Score. Set up a weekly data refresh job via Zapier, Make, or a direct API connector to your CRM.
- **Outreach / Salesloft:** Create readiness-band sequences (Cold, Warm, Ready) as distinct playbooks. Use Outreach's triggers to auto-enroll contacts into the appropriate sequence when CRM score field crosses a threshold. Configure "spike alert" sequences for contacts whose score jumps 20+ points in a 72-hour window.
- **Google Sheets / Notion:** For teams without advanced MarTech, build a manual scoring calculator in Google Sheets. Use a weighted formula (SUMPRODUCT of signal presence × weight) that outputs a readiness score. Sync to CRM weekly via Zapier.

## Troubleshooting

**Problem: Sales team ignores the readiness score and still reaches out to low-scoring accounts.**
Solution: Run a 60-day win-rate analysis by readiness band and present it in the next sales QBR. When AEs see that accounts scoring 75+ close at 2x the rate of accounts scoring below 40, behavioral change accelerates. Create a "score badge" in the Salesforce/HubSpot contact view so the score is impossible to miss during daily prospecting. Tie SDR comp or leaderboard metrics to average score of contacted accounts to create natural incentive alignment.

**Problem: Score inflation — nearly every prospect ends up in the 65–80 range, making it hard to prioritize.**
Solution: Apply score normalization: after running the model for 30 days, check the score distribution. If more than 40% of active pipeline is in the 75+ band, your signal weights are too generous. Reduce base point values for passive signals (email opens, page views under 30 seconds) and increase weight for high-intent signals (pricing page, demo page, G2 comparison visit, multi-stakeholder engagement). Introduce a percentile-rank score (top 10%, top 25%, etc.) as a secondary priority layer when absolute scores cluster.

**Problem: Score doesn't account for deal size, and high-score SMB leads get prioritized over lower-score enterprise accounts that are worth 10x more.**
Solution: Apply a Revenue Impact Multiplier: multiply the readiness score by an ACV Weight factor (e.g., ACV <$10K = 0.8x, $10K–$50K = 1.0x, $50K–$150K = 1.2x, $150K+ = 1.5x) to produce a Revenue-Adjusted Readiness Score (RARS). Use RARS — not raw readiness score — for SDR and AE prioritization. This ensures that a $200K enterprise account at score 58 (RARS: 87) outranks a $5K SMB account at score 78 (RARS: 62.4).

## Version History
- v1.0: Initial creation (auto-generated)
