# AI-Powered B2B Behavioral Intent Scoring & Micro-Segment Revenue Activation Intelligence Engine - Turn Anonymous Buyer Signals Into Precision Revenue Plays

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** behavioral-analytics, intent-scoring, segmentation, revenue-ops, b2b, demand-generation, personalization, automation, martech, crm, map

## Overview
Builds a full-stack behavioral intent scoring system that aggregates multi-signal data (web, email, product, ad, event) into dynamic micro-segments, then automatically triggers the right revenue play for each segment — so every buyer interaction moves a prospect closer to pipeline, not into a generic nurture black hole. Use it when your lead scoring feels static, your nurture sequences feel generic, or your sales team is ignoring marketing-qualified leads.

## Quick Copy-Paste Version

You are a senior B2B revenue analytics strategist with deep expertise in behavioral scoring, marketing automation, and revenue operations. I need to build a behavioral intent scoring system that goes beyond traditional lead scoring — one that uses real-time multi-channel signals to create dynamic micro-segments and automatically triggers the most effective revenue play for each segment.

MY CONTEXT:
- Company: [e.g., "Vantara — B2B SaaS for IT asset lifecycle management, $18M ARR, selling to IT Directors and CIOs at mid-market and enterprise companies"]
- Primary buyer journey signals we can track: [e.g., "website visits, gated content downloads, email opens/clicks, webinar attendance, G2 profile views, paid ad engagement, LinkedIn company page visits, product trial activity"]
- CRM/MAP stack: [e.g., "Salesforce CRM + Marketo + 6sense for intent + Clearbit for enrichment"]
- Current lead scoring approach: [e.g., "basic MQL score in Marketo — 100 points threshold, mostly based on demographics + 3 behavioral actions. Sales ignores 60% of MQLs."]
- Sales team size and segments: [e.g., "8 AEs covering SMB/Mid-Market/Enterprise, 4 SDRs handling inbound"]

Build my complete behavioral intent scoring and micro-segment activation system:

1. **SIGNAL UNIVERSE AUDIT** — Map every behavioral signal I should be capturing across the full buyer journey: anonymous to known, pre-pipeline to closed-won. For each signal, specify: data source, capture method, intent strength (1-5), decay rate (how long the signal stays valid), and which buying stage it most indicates.

2. **MICRO-SEGMENT ARCHITECTURE** — Design 8-12 distinct behavioral micro-segments based on signal combinations. For each segment: name, signal criteria, estimated size as % of database, buyer profile it represents, urgency level, and the ONE revenue play it should trigger automatically.

3. **DYNAMIC SCORING MODEL** — Build a multi-dimensional scoring framework with: Fit Score (ICP firmographic match), Intent Score (behavioral engagement depth), Recency Score (signal freshness), Engagement Velocity Score (rate of engagement acceleration). Include the specific point values, decay curves, and threshold logic that should trigger segment transitions.

4. **REVENUE PLAY LIBRARY** — For each micro-segment, define the specific automated revenue play: email sequence (subject lines, send cadence, content), SDR outreach play (call script angle, LinkedIn message template), ad retargeting strategy (audience, message, landing page), and sales alert (what to tell the AE and why now).

5. **MARTECH ACTIVATION BLUEPRINT** — Map exactly how each signal flows into my CRM/MAP stack, gets scored, triggers segment assignment, and launches the revenue play. Include the specific workflow logic, field mappings, and automation rules I need to build.

6. **MEASUREMENT & OPTIMIZATION FRAMEWORK** — Define the metrics to track system health and ROI: segment-to-pipeline conversion rates, play effectiveness scores, scoring model accuracy (predicted vs. actual buyer behavior), and the monthly optimization cadence.

Output must be immediately actionable — real field names, real workflow logic, real sequences I can build this week.

## Advanced Customizable Version

ROLE: You are the world's leading B2B revenue intelligence architect. You've built behavioral scoring systems for 40+ B2B SaaS companies that collectively added $800M+ in pipeline. You've reverse-engineered how the best go-to-market teams at companies like Gong, Drift, Demandbase, and Gainsight convert behavioral signals into revenue. You are now leading a full-day working session with my marketing and revenue operations teams to build our behavioral intent scoring and micro-segment activation engine from the ground up.

This is not a lead scoring refresh. This is a revenue intelligence operating system. Every signal, every segment, every play must tie directly to pipeline generation and revenue acceleration — not activity metrics, not email opens, not MQL volume.

---

COMPANY PROFILE:
- Company: [NAME] — [one-line business description]
- ARR: [$X] | Stage: [Series A / Series B / Series C / Growth]
- GTM motion: [Inbound-dominant / Outbound-dominant / PLG / ABM / Hybrid]
- ICP: [Primary titles, company sizes, industries — be specific]
- ACV: [$X average] | Sales cycle: [average days from MQL to close]
- Primary buyer problems: [List 3–5 specific pain points that drive urgency]
- Product category & use case: [How buyers describe what you do]

---

CURRENT SCORING INFRASTRUCTURE:
- CRM: [Salesforce / HubSpot / Dynamics / other]
- Marketing automation platform: [Marketo / HubSpot / Pardot / Eloqua / ActiveCampaign / other]
- Intent data: [6sense / Bombora / G2 Buyer Intent / Demandbase / none]
- Enrichment tools: [Clearbit / ZoomInfo / Apollo / Cognism / other]
- Product analytics: [Mixpanel / Amplitude / Heap / Pendo / none]
- Website intelligence: [Warmly / Qualified / Clearbit Reveal / 6sense / none]
- Ad platform data available: [LinkedIn / Google / Meta / programmatic DSP]
- Current scoring model: [Describe how leads are currently scored and segmented — be honest about gaps]
- Sales feedback on current MQLs: [Quote actual objections from your sales team]

---

BUYER JOURNEY SIGNAL INVENTORY (customize which apply):

**Awareness Signals (early intent, low urgency):**
- [ ] Anonymous website visit (homepage, blog, pricing page — differentiate by page)
- [ ] Ad impression or engagement (LinkedIn, Google, programmatic)
- [ ] Email list opt-in (newsletter, gated resource)
- [ ] Social follow or engagement (LinkedIn company page, employee posts)
- [ ] G2 category browsing (not yet your profile)
- [ ] 3rd party intent topic surge (Bombora/6sense dark funnel)

**Consideration Signals (active research, medium urgency):**
- [ ] Gated content download (ebook, guide, research report)
- [ ] Webinar registration or attendance
- [ ] Website multiple-page visit (2+ pages in session)
- [ ] Competitive comparison page visit
- [ ] Pricing page visit (1st time)
- [ ] Case study or customer story consumption
- [ ] G2 product profile view (your brand specifically)
- [ ] Email nurture sequence engagement (3+ emails opened + clicked)
- [ ] Blog post series consumption (topical depth signals expertise gap)
- [ ] Demo video watched (% completion matters)
- [ ] Integration/tech partner page visit
- [ ] Product trial started (freemium/PLG)

**Evaluation Signals (high intent, high urgency):**
- [ ] Pricing page visit (2nd visit within 30 days)
- [ ] ROI calculator interaction
- [ ] Demo request page visit (without submitting)
- [ ] Peer review comparison (G2 vs. competitors side-by-side)
- [ ] Security/compliance documentation download
- [ ] Reference customer page visit
- [ ] Multiple stakeholders from same account showing intent
- [ ] Product trial: activated core feature
- [ ] Product trial: invited a teammate
- [ ] Direct chat or chatbot engagement

**Decision Signals (near-term purchase, very high urgency):**
- [ ] Demo request submitted
- [ ] Pricing page 3+ visit within 14 days
- [ ] Product trial: daily active user (3+ days in a week)
- [ ] Product trial: approaching usage limit
- [ ] Multiple decision-makers from same account engaged
- [ ] Contract/MSA page visit
- [ ] "How to buy" or procurement FAQ page visit

---

MICRO-SEGMENT DESIGN FRAMEWORK:

For each micro-segment, output:
1. **Segment Name** — Memorable internal name that describes the buyer state (e.g., "The Tire-Kicker," "The Urgent Evaluator," "The Committee Builder")
2. **Signal Criteria** — Specific combination of signals + thresholds that define membership
3. **Buyer Psychology** — What this person is thinking and feeling right now
4. **Urgency Level** — [Critical (< 14 days to act) / High (14–30 days) / Medium (30–60 days) / Low (60+ days nurture)]
5. **Ideal Next Experience** — The single best marketing or sales touch for this segment RIGHT NOW
6. **Revenue Play Trigger** — What automated action fires when someone enters this segment

Mandatory micro-segment types to design (customize for your ICP):
- [ ] High-fit, low-intent (strong ICP match but minimal engagement yet)
- [ ] High-fit, spiking-intent (ICP match + sudden engagement acceleration)
- [ ] Low-fit, high-intent (engaged but outside ideal profile — requires routing decision)
- [ ] Multi-stakeholder cluster (2+ people from same account showing intent)
- [ ] Competitive researcher (visiting competitor comparison or alternatives pages)
- [ ] Pricing urgency (3+ pricing page visits in 30 days without form fill)
- [ ] Trial-activated but stuck (product trial: started but not hitting key activation milestones)
- [ ] Reengagement candidate (60+ days inactive, high-fit account with prior intent)
- [ ] Champion re-engagement (past contact at won or churned account now at new company)
- [ ] Dark funnel surger (6sense/Bombora intent signal, no direct engagement yet)

---

SCORING MODEL ARCHITECTURE:

Build four independent scoring dimensions that combine into a composite score:

**Dimension 1: ICP Fit Score (0–100)**
Weight firmographic and technographic criteria:
- Company size (employees/revenue): [Your target ranges and weights]
- Industry vertical: [Tier 1 / Tier 2 / Tier 3 targets and weights]
- Technology stack (tools that signal pain or compatibility): [Key tech signals]
- Funding stage / growth signals: [Hiring velocity, funding round, etc.]
- Geography: [Primary / secondary markets]

**Dimension 2: Behavioral Intent Score (0–100)**
Map each signal category to a point range:
- Product/pricing engagement signals: [High weight — 15–25 pts each]
- Evaluation content engagement: [Medium weight — 8–15 pts each]
- Consideration content engagement: [Low weight — 3–8 pts each]
- Awareness signals: [Minimal weight — 1–3 pts each]
- PENALTY signals: [Signs of non-buyer behavior — academic research, job seeker patterns]

**Dimension 3: Recency Score (0–100)**
Model signal freshness with exponential decay:
- < 7 days: 100% weight
- 8–14 days: 80% weight
- 15–30 days: 50% weight
- 31–60 days: 25% weight
- > 60 days: 10% weight (near-dormant, triggers reengagement play)

**Dimension 4: Velocity Score (0–100)**
Measure engagement acceleration (rate of change):
- Engagement doubling in past 7 days vs. prior 7: Strong positive velocity
- First 3+ page visit session after 30+ days of silence: Re-emergence signal
- Multiple stakeholders from same account engaging within 7 days: Committee formation

**Composite Score Formula:**
[Customize weightings based on your GTM motion]
- Inbound-led: Fit 25% + Intent 45% + Recency 20% + Velocity 10%
- ABM-led: Fit 40% + Intent 30% + Recency 15% + Velocity 15%
- PLG-led: Fit 20% + Intent 25% + Recency 20% + Velocity 35% (activation velocity matters most)

---

REVENUE PLAY DESIGN:

For each micro-segment, output a complete playbook card:

SEGMENT: [Name]
TRIGGER: [Specific score threshold + signal criteria]
SALES ALERT: [Exact Slack/CRM notification text — what to tell the AE/SDR and why this matters now]

EMAIL PLAY:
- Email 1 (Day 0): Subject: [Exact subject line] | Angle: [1-sentence description] | CTA: [Specific action]
- Email 2 (Day 3): Subject: [Exact subject line] | Angle: | CTA:
- Email 3 (Day 7): Subject: [Exact subject line] | Angle: | CTA:
- Exit condition: [What stops the sequence — reply, conversion, 14-day silence]

SDR PLAY:
- Call opener: [First 2 sentences the SDR should say — reference the specific signal]
- LinkedIn message: [Exact 3-sentence message referencing their behavior without being creepy]
- Call objective: [Not "book a demo" — what's the ideal outcome of this specific touch]

AD RETARGETING PLAY:
- Audience: [How to define this segment in LinkedIn/Google/Meta Ads]
- Message angle: [What fear/desire this ad should address]
- Landing page: [Which specific page or asset — don't send to homepage]
- Frequency cap: [Max impressions/week to avoid fatigue]

---

MARTECH INTEGRATION BLUEPRINT:

Map the complete data flow:

SIGNAL CAPTURE → ENRICHMENT → SCORING ENGINE → SEGMENT ASSIGNMENT → PLAY TRIGGER → SALES NOTIFICATION

[Data Source] → [Which tool captures it] → [How it enters MAP/CRM] → [Which field it updates] → [Score recalculation trigger] → [Segment evaluation logic] → [Automated action] → [Sales alert]

Include:
- Webhook configurations for real-time signal capture
- CRM field architecture (custom fields, score fields, segment fields, play fields)
- MAP workflow logic (entry criteria, suppression lists, exit conditions)
- Sales notification templates (Slack, CRM activity, email digest)
- De-duplication rules (account-level vs. contact-level scoring)
- GDPR/CCPA compliance guardrails (what signals require consent)

---

MEASUREMENT FRAMEWORK:

**Weekly Metrics (operational health):**
- Segment distribution: % of database in each micro-segment (flag if high-intent segments are underpopulated)
- Play launch rate: # of plays triggered per segment per week
- Signal capture rate: % of website visitors identified (should grow over time)
- Score accuracy: % of SQL conversions that were predicted by high-intent signals 14+ days prior

**Monthly Metrics (model performance):**
- Micro-segment-to-pipeline conversion rate by segment (which segments actually convert?)
- Play effectiveness: Pipeline generated per 100 plays launched, by play type
- Signal-to-close correlation: Which signals best predict closed-won? (Validate and re-weight monthly)
- Sales adoption rate: % of play-triggered alerts actioned by sales within 48 hours

**Quarterly Review: Model Recalibration Protocol**
- Pull cohort analysis: accounts that closed vs. those that went dark — what signals differentiated them?
- Re-weight scoring model based on actual closed-won behavior
- Add/remove signals based on capture quality and predictive value
- Benchmark against industry: compare MQL-to-SQL rate, lead-to-close velocity

---

ADVANCED OPTIONS:

**Account-Level Scoring (for ABM programs):**
Aggregate individual contact scores to a single account score. Include logic for: buying committee detection (3+ contacts from one account in high-intent segments), account momentum scoring (trajectory of engagement over 30 days), and account-based revenue plays (different from contact-level plays).

**AI-Driven Model Evolution:**
Design a closed-loop learning system: feed closed-won/lost data back into the scoring model monthly, use ML to identify non-obvious signal combinations that predict conversion, flag anomaly accounts where behavior doesn't match historical patterns.

**Predictive Churn Signals (for post-sale):**
Extend the scoring model to detect disengagement signals: declining product usage, executive sponsor job change, support ticket velocity increase, competitor review activity — trigger customer success plays before churn becomes inevitable.

## Example Input/Output

**Input Example:**

Company: Fenwick Analytics — B2B SaaS for revenue forecasting automation, $11M ARR, 25 employees. Selling to VP Revenue Operations and CFOs at B2B SaaS companies 50–500 employees. ACV $28,000. Sales cycle 45 days average.

Stack: HubSpot CRM + HubSpot Marketing Hub + G2 Buyer Intent + Clearbit enrichment. No product analytics yet (launching freemium Q3). No paid intent tools beyond G2.

Current scoring: HubSpot's default lead score — 50 points threshold. Demo request gets fast-followed. Everything else goes into "Lead Nurture" workflow. Sales ignores most MQLs. Only 1 in 8 MQLs becomes an SQL.

---

**Output Example (excerpt — Micro-Segment #4: "The Committee Builder"):**

**SEGMENT NAME:** The Committee Builder

**SIGNAL CRITERIA:**
- 2 or more contacts from the same HubSpot company record have engaged in the past 14 days
- At least one contact has visited the Pricing or ROI Calculator page
- Account ICP Fit Score ≥ 65
- Combined account intent score ≥ 140 (aggregate of all contacts' behavioral scores)

**BUYER PSYCHOLOGY:** A buying decision is being socialized internally. The champion is building the business case and pulling in stakeholders. This is the highest-conversion signal in the B2B funnel — when multiple people are researching, purchase probability doubles.

**URGENCY LEVEL:** Critical — Act within 72 hours or lose the window.

**REVENUE PLAY TRIGGER:** HubSpot workflow fires immediately on criteria match → CRM creates "Committee Opportunity" task → SDR receives Slack notification + HubSpot task → 3-email executive multi-threaded sequence launches simultaneously to ALL engaged contacts.

**SDR CALL OPENER:**
"Hi [Name], I noticed a few people from Fenwick have been exploring our forecasting automation platform this week — including what looks like some research into our pricing. Given that multiple teams are often involved in these decisions, I wanted to reach out directly and see if it makes sense to schedule a brief call with the right people together. We have a 30-minute cross-functional overview that CFOs and RevOps leaders typically find most useful. Would that be worth 30 minutes this week?"

**Email 1 to Champion (Day 0):**
Subject: "Quick note — saw your team exploring Fenwick Analytics"
Angle: Acknowledge the multi-stakeholder research without being creepy; offer a buying committee briefing
CTA: Schedule a 30-minute cross-functional overview call

**Email 1 to Stakeholder (Day 0 — simultaneous):**
Subject: "Revenue forecasting: resources for [Company Name]'s evaluation"
Angle: Provide third-party proof assets (G2 reviews from similar companies, CFO ROI calculator link)
CTA: Access the ROI calculator pre-populated with their industry benchmarks

---

**MARTECH WORKFLOW LOGIC (HubSpot):**

Enrollment criteria: "Number of associated contacts with Activity Date in last 14 days ≥ 2" AND "Company ICP Fit Score ≥ 65" AND "Any associated contact has visited /pricing or /roi-calculator"

Branch 1: If no open deal exists → Create deal in stage "Committee Signal" → Enroll in Multi-Thread Sequence A
Branch 2: If deal exists in stage "MQL" or "Discovery" → Move deal to "Active Evaluation" → Send AE alert + enroll in Committee Acceleration Sequence B
Suppression: Do not enroll if deal is in "Closed Won" or "Closed Lost (< 90 days)"

## Success Metrics

- **MQL-to-SQL conversion rate lifts 40–80%** within 90 days of deploying segment-specific plays vs. generic nurture
- **Sales adoption rate ≥ 70%** — if SDRs act on ≥ 70% of play-triggered alerts within 48 hours, the plays are relevant; below 50% means signals need recalibration
- **Signal-to-close accuracy ≥ 60%** — 60% of closed-won accounts should have entered a high-intent segment 2+ weeks before demo request; validates the model is predicting, not just reacting
- **Pipeline per play ≥ 3× generic nurture baseline** — each segment-specific revenue play should generate 3× more pipeline per 100 contacts touched than the old batch nurture approach
- **Composite score distribution is bell-curved** — if 80% of your database is clustered in one segment, your signal capture is broken; healthy distribution means the model is differentiating

## Related Prompts

- [Lead Scoring Model Optimization & Predictive Buying Signal Intelligence Engine](../Lead-Quality-&-Conversion-Analytics/Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md)
- [AI-Powered Next-Best-Action Intelligence & Revenue Moment Personalization Engine](./AI-Powered-Next-Best-Action-Intelligence-&-Revenue-Moment-Personalization-Engine.md)
- [ABM Intent Data Activation & Buying Signal Prioritization Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [Dark Funnel Attribution & Anonymous Buyer Intent Intelligence Engine](../Attribution-&-Revenue-Analytics/Dark-Funnel-Attribution-&-Anonymous-Buyer-Intent-Intelligence-Engine.md)

## Integration Tips

- **HubSpot:** Use custom contact properties for each scoring dimension (FitScore, IntentScore, RecencyScore, VelocityScore, CompositeScore, CurrentSegment, ActivePlay). HubSpot's native scoring tool only supports one score — use custom properties + workflows to run multi-dimensional logic. Set up a daily "Score Recalculation" workflow that fires for any contact with activity in the last 24 hours.

- **Salesforce + Marketo:** Use Marketo for behavioral scoring and segment logic; sync `Behavioral_Segment__c` and `Composite_Score__c` fields to Salesforce. Build Salesforce alerts using Flow Builder that ping SDRs in Slack (via Zapier or native Slack connector) when high-intent segments trigger. Store segment history in a Salesforce custom object to track segment progression over time.

- **6sense / Bombora:** Layer 3rd-party intent topics onto the scoring model as a "Dark Funnel Intent Boost" — add 15–20 points to account-level intent score when Bombora/6sense detects a surge on your core topic clusters. Map 6sense account stages to micro-segment assignments.

- **Zapier/Make:** If your MAP lacks native scoring flexibility, use Zapier to create multi-step scoring logic: (1) catch webhooks from website tools, (2) query enrichment APIs, (3) post to CRM via API, (4) trigger Slack notifications. Less elegant but achieves the same outcome.

- **Google Sheets + Looker Studio (bootstrap option):** If you lack budget for intent tools, use Google Sheets as a lightweight scoring engine — daily export from CRM + MAP, VLOOKUP to apply scores, flag high-intent accounts, share with SDR team. Not scalable but valuable for proving the model before investing in automation.

## Troubleshooting

**Problem: Sales team still ignores play-triggered alerts, claiming the signals are "noise."**
Solution: Run a 30-day retrospective — pull every closed-won deal from the past 90 days and check whether they passed through a high-intent segment before the demo. If 70%+ did, present that data to your VP Sales with the slide: "We predicted 7 of your last 10 deals before the reps called them." Win the data argument before the process argument. If the data doesn't support it, your signal capture is broken — audit which signals are actually being captured vs. which are theoretical.

**Problem: Most of your database is stuck in one segment (usually "Low Intent") and never moves.**
Solution: Signal capture is failing somewhere in the stack. Common culprits: (1) website traffic not being identified — check Clearbit Reveal/6sense coverage rate; (2) email tracking blocked — Apple MPP inflating opens artificially, or link-tracking disabled; (3) HubSpot/Marketo activities not feeding score fields — audit workflow enrollment criteria. Run a manual audit: pick 20 accounts you KNOW are evaluating you (recent demo requests) and trace every signal backwards — where did each data point appear (or not appear) in your MAP?

**Problem: Composite scores don't correlate with actual conversion — high-score accounts aren't converting.**
Solution: Your ICP Fit Score is too generous — you're giving high fit scores to companies that look right on paper but aren't actually buyers. Audit your closed-won cohort vs. your high-score non-converters and identify which firmographic or technographic criteria over-index for non-buyers. Common fix: increase the weight of tech stack signals (the tools someone already uses tells you more about purchase readiness than company size) and add negative scoring for signals that indicate academic/competitive research (blog post patterns, documentation-only browsing, careers page visits).

## Version History
- v1.0: Initial creation (auto-generated)
