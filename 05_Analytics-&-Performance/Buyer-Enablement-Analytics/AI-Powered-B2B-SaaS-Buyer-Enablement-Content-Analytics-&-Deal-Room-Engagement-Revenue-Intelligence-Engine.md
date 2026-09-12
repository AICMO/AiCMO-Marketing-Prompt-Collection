# AI-Powered B2B SaaS Buyer Enablement Content Analytics & Deal Room Engagement Revenue Intelligence Engine - Measure Which Buyer Enablement Assets Actually Close Deals and Compress Sales Cycles by 30%

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b-saas, buyer-enablement, deal-room-analytics, sales-cycle-compression, pipeline-analytics, revenue-attribution, champion-enablement, deal-acceleration, buying-committee, revenue-intelligence

## Overview
Builds a full-stack buyer enablement analytics system that tracks which content, deal room interactions, and champion activation signals correlate with faster close rates and higher win rates — so revenue teams can systematically replicate what works and kill what doesn't. Use this when win rates are below 30% on qualified pipeline, sales cycles are longer than 90 days, or the marketing-to-sales content handoff is a black box with no engagement data.

## Quick Copy-Paste Version

You are a senior B2B SaaS revenue analytics expert specializing in buyer enablement measurement. Your job is to analyze how buyer-facing content and digital deal room engagement drives deal velocity and win rate improvement.

My buyer enablement analytics situation:
- Product ACV: [e.g., $85K average]
- Current sales cycle length: [e.g., 112 days average]
- Digital deal room tool: [e.g., Highspot / Seismic / Accord / Notion / Google Drive]
- Content types we share with buyers: [e.g., ROI calculators, case studies, security questionnaires, executive one-pagers, POC checklists]
- CRM: [Salesforce / HubSpot]
- Win rate on qualified opportunities: [e.g., 27%]
- Biggest deal stall point: [e.g., after technical validation, during finance/legal review]

Build a buyer enablement analytics framework that tells me:

1. DEAL ROOM ENGAGEMENT SCORING — A scoring model that ranks buyer engagement in digital deal rooms from 1–100 based on: (a) pages/content viewed per stakeholder, (b) time spent on economic buyer content vs. technical content, (c) number of unique stakeholders who accessed the room, (d) return visits within 7 days of last activity, (e) champion sharing behavior (did they forward to new contacts?). Tell me which engagement patterns predict closed-won vs. closed-lost.

2. CONTENT EFFECTIVENESS MATRIX — For each content type I share (ROI calculator, case study, security brief, competitive battlecard, pricing page, implementation guide), give me the exact metrics to track: view rate, completion rate, download rate, share rate, and the correlation metric that ties each asset to deal progression (e.g., "accounts that viewed the ROI calculator at Stage 3 closed 2.3x faster").

3. CHAMPION ACTIVATION ANALYTICS — A dashboard framework to measure champion health: how many stakeholders has the champion engaged, how quickly are they responding to shared content, are they creating new internal meetings (a proxy for internal selling activity), and what's the correlation between champion engagement score and final win rate.

4. SALES CYCLE COMPRESSION ATTRIBUTION — A model showing which buyer enablement interventions compress the sales cycle the most: (a) personalized executive one-pager at Stage 2, (b) pre-built security questionnaire response at Stage 3, (c) digital deal room launch at Stage 1, (d) POC success metrics shared at Stage 4. Rank each intervention by average days saved per deal.

5. WIN/LOSS ATTRIBUTION BY CONTENT ENGAGEMENT — An analysis framework for last 50 closed deals: do closed-won deals show a statistically different content engagement pattern than closed-lost? What's the minimum engagement threshold that separates winners from losers?

6. WEEKLY BUYER ENGAGEMENT DASHBOARD — A reporting template I can build in Salesforce/HubSpot that surfaces: (a) deals with no buyer engagement in last 14 days (stall risk), (b) deals with high engagement but no forward movement (process risk), (c) deals where new stakeholders just accessed content (expansion opportunity), (d) top 10 at-risk deals by engagement decay.

Output as a ready-to-implement analytics framework with specific metric definitions, data source requirements, and the SQL/CRM report logic for each dashboard component.

## Advanced Customizable Version

# ROLE
You are a world-class B2B SaaS revenue intelligence architect with 15+ years of experience building buyer engagement analytics systems at companies scaling from $20M to $500M ARR. You have designed measurement frameworks for buyer enablement programs at companies using Highspot, Seismic, Consensus, Accord, GetAccept, and custom Notion/Salesforce deal rooms. You understand that most B2B SaaS companies track marketing attribution (first touch, last touch, multi-touch) but are completely blind to what happens after the opportunity is created — the buyer enablement black box between demo and close. You build analytics systems that correlate specific buyer actions (content views, deal room logins, stakeholder expansion, POC completion) with revenue outcomes, giving revenue teams the ability to systematically replicate win patterns and intervene before deals stall. You design for full AI agent automation — every metric is pulled from existing tool APIs, every alert is triggered automatically, every insight is surfaced without human analysis overhead.

# CONTEXT
Company and deal profile:
- Company name: [Your company]
- Product category: [e.g., workflow automation, security analytics, data platform]
- Average ACV: [e.g., $95,000]
- ACV range: [e.g., $40K–$300K]
- Average sales cycle: [e.g., 98 days from first demo to close]
- Win rate on qualified pipeline (Stage 2+): [e.g., 29%]
- Average buying committee size: [e.g., 5.3 stakeholders per deal]
- Typical deal stages: [e.g., Discovery → Technical Validation → Business Case → Legal/Finance → Close]
- Stage where deals stall most: [e.g., 42% of stalls happen between Technical Validation and Business Case stages]

Buyer enablement tech stack:
- Digital deal room platform: [Highspot / Seismic / Accord / GetAccept / Consensus / Notified / Notion / SharePoint / custom]
- CRM: [Salesforce / HubSpot — specify edition/plan as it determines available API data]
- Sales engagement platform: [Outreach / Salesloft / Apollo / other]
- Revenue intelligence: [Gong / Chorus / Clari / Aviso / other — if any]
- Marketing automation: [Marketo / HubSpot / Pardot]
- Content creation: [Highspot / Seismic / Showpad / Google Drive]
- Analytics/BI: [Salesforce native / Tableau / Looker / Metabase / Power BI]

Current buyer enablement assets:
- Stage 1 (Pre-Demo): [e.g., personalized outreach sequence, company research brief]
- Stage 2 (Post-Demo): [e.g., executive one-pager, competitive battlecard, ROI snapshot]
- Stage 3 (Technical Validation): [e.g., security questionnaire pre-fill, API documentation, implementation timeline, architecture diagram]
- Stage 4 (Business Case): [e.g., full ROI/business case model, CFO-ready investment summary, customer references, Forrester TEI study]
- Stage 5 (Legal/Finance): [e.g., standard contract redlines, DPA, vendor questionnaire answers, procurement checklist]
- Stage 6 (Post-Signature): [e.g., kickoff playbook, 90-day success plan, onboarding roadmap]

Current measurement gaps:
- What you currently measure: [e.g., email open rates, demo show rates, stage conversion rates]
- What you cannot currently measure: [e.g., which stakeholders view shared content, whether champions are sharing assets internally, POC completion rates, security review cycle time]
- Last known win/loss analysis date: [e.g., Q2 2025 — or "never done a structured win/loss content analysis"]
- Biggest blind spot: [e.g., "We have no idea if our CFO one-pager is ever read or forwarded"]

Revenue targets and context:
- Current quarter pipeline: [e.g., $8.4M pipeline, $2.1M quota]
- Deals at risk (no activity in 30+ days): [e.g., 23 deals / $3.1M]
- Average deal size trend: [e.g., ACV declining 12% YoY as we move upmarket slower than expected]

# OBJECTIVE
Design a complete Buyer Enablement Revenue Intelligence System (BERIS) that:
1. Instruments every buyer touchpoint with measurable engagement data
2. Correlates engagement patterns with revenue outcomes (win rate, cycle length, ACV)
3. Generates predictive signals for deal health and stall risk
4. Surfaces actionable interventions for revenue teams with zero manual analysis
5. Runs fully automated via API integrations and AI agent orchestration

# DELIVERABLES

## 1. BUYER ENGAGEMENT INSTRUMENTATION ARCHITECTURE
For each buyer enablement stage, define:

**a) Data collection points:**
- Which tool captures the engagement event (deal room, CRM, email platform)
- What specific event to track (view, download, share, time-on-page, return visit)
- Which stakeholder role triggered the event (map contacts to buying committee roles)
- Timestamp precision needed (real-time vs. daily batch)

**b) Deal room setup standard:**
- Recommended folder/section structure for each deal stage
- Naming convention for tracking content versions
- Stakeholder access configuration (individual tracking vs. shared link)
- The 3 "engagement tripwires" to set per deal (alerts when high-value content is accessed)

**c) CRM activity logging schema:**
- Custom fields to add to Opportunity object for buyer engagement tracking
- Activity record structure for each buyer event
- The 5 most predictive fields to add to your deal scorecard

## 2. BUYER ENGAGEMENT SCORING MODEL (BESS — Buyer Engagement Signal Score)
A 0–100 composite score calculated per deal using weighted signals:

**Signal categories and weights:**
- Stakeholder breadth (25 pts): Number of unique buyer-side contacts who engaged with content. Score = (unique engagers / expected buying committee size) × 25. Benchmark: ≥4 unique engagers = full score.
- Content depth (25 pts): Did buyer engage with economic buyer content AND technical content? Score = (economic content engagement [0–12.5] + technical content engagement [0–12.5]). A deal where only the champion reads content scores ≤8.
- Engagement recency (20 pts): Recency-weighted engagement. Full score = activity within last 7 days. Score decay: -4 pts per week of inactivity. A deal with no engagement for 28+ days = 0 pts.
- Champion activation (20 pts): Champion-specific signals — did they create a new internal meeting (calendar event with new attendees detected via Gong/email)? Did they forward the deal room to a new contact? Did they download the CFO one-pager (proxy for internal sharing)? Each confirmed signal = 5 pts.
- POC/Evaluation completion (10 pts): If a POC or technical evaluation is in progress, track % complete against the shared success criteria doc. 100% completion = 10 pts. No POC in progress = neutral (not counted).

**Score interpretation:**
- 75–100: High engagement. Predicted win rate: 58–72%. Priority: accelerate close timeline with contract/legal preparation.
- 50–74: Moderate engagement. Predicted win rate: 31–45%. Priority: champion coaching, identify missing stakeholders.
- 25–49: Low engagement. Predicted win rate: 14–22%. Priority: re-engage with new value trigger (case study, reference call offer, executive outreach).
- 0–24: Disengaged. Predicted win rate: <8%. Priority: stall intervention within 72 hours or deprioritize for forecast.

## 3. CONTENT EFFECTIVENESS MEASUREMENT FRAMEWORK

**For each content type, define:**
- Primary metric: the single number that proves the content is working
- Secondary metrics: supporting data points for optimization
- Benchmark threshold: minimum performance to justify maintaining the asset
- Replacement trigger: when to retire or rebuild the asset

**Core content type definitions:**

ROI / Business Case Calculator:
- Primary metric: Completion rate (% of deals where buyer completed the calculator, not just viewed it)
- Secondary: Average time to complete, champion vs. economic buyer completion split, deals where calculator was shared to a new contact
- Benchmark: ≥35% completion rate on deals where shared; ≥18% shared to new stakeholder
- Revenue correlation: Track whether completed ROI calculator deals close faster. If not, the calculator is not compelling enough.
- Replacement trigger: <20% completion rate over 90-day rolling window

Executive One-Pager:
- Primary metric: Forward/share rate (% of deals where one-pager was accessed by someone other than the champion)
- Secondary: Time-to-first-view after send, number of unique viewers, return visits
- Benchmark: ≥28% forward rate; first view within 24 hours in ≥60% of deals where shared
- Revenue correlation: Deals with one-pager forwarded to economic buyer should show ≥15% higher win rate
- Replacement trigger: Forward rate <15% over rolling 90 days

Security Questionnaire Pre-Fill:
- Primary metric: Security review cycle compression (days from CISO/security team introduction to security sign-off, compared to baseline without pre-fill)
- Secondary: Number of follow-up security questions after pre-fill is shared (lower = better), % of deals where security was never a stall point
- Benchmark: Security review should complete in ≤14 days with pre-fill vs. ≥35 days without
- Revenue correlation: Security stalls represent [X]% of your lost deals — track change in that metric
- Replacement trigger: Follow-up questions >12 per deal on average (pre-fill is incomplete or outdated)

Competitive Battlecard:
- Primary metric: Win rate in deals where battlecard was used vs. not used
- Secondary: Stage at which battlecard is shared (earlier = better), champion engagement rate after battlecard delivery
- Benchmark: ≥8 percentage point win rate lift in competitive deals where battlecard was accessed
- Revenue correlation: Direct win rate delta by competitor (battlecard for Competitor A vs. B vs. C)
- Replacement trigger: No measurable win rate lift over 90 days

Customer Case Study (matched vertical):
- Primary metric: Reference request conversion rate (% of deals where case study was shared that then requested a reference call)
- Secondary: Economic buyer view rate, time-on-page, deals where case study sent triggered new stakeholder introduction
- Benchmark: ≥22% reference request rate after matched case study delivery
- Revenue correlation: Deals where a matched case study was viewed by the economic buyer should close ≥20 days faster
- Replacement trigger: <12% reference request rate; or >6 months since outcome data was last updated

POC/Trial Success Criteria Document:
- Primary metric: Criteria completion rate (% of defined success criteria marked complete at end of POC)
- Secondary: Time-to-criteria-agreement at POC kickoff, number of criteria added by buyer (expansion = good signal), POC-to-close conversion rate
- Benchmark: ≥80% success criteria completion = strong buy signal; ≥70% POC-to-close conversion
- Revenue correlation: POC completion rate should be the single strongest predictor of win rate. If not, the POC design is broken, not the product.
- Replacement trigger: POC-to-close conversion <45% (the POC isn't qualifying, it's just consuming resources)

## 4. CHAMPION ACTIVATION ANALYTICS DASHBOARD

**Champion Health Score (CHS — 0–100):**
A per-deal champion-specific score that measures whether the champion is actively selling internally on your behalf.

Champion action signals (each worth points):
- Introduced you to a new stakeholder (10 pts per new intro, max 30)
- Accessed and forwarded economic buyer content (CFO one-pager, business case) (15 pts)
- Scheduled an internal meeting after you provided content (detectable via Gong/calendar data) (20 pts)
- Responded to your last touchpoint within 48 hours (15 pts)
- Set up or maintained a shared digital deal room and invited colleagues (10 pts)
- Accessed content more than once (return visit = deeper engagement signal) (10 pts)

Champion risk signals (subtract points):
- No activity on any shared content in last 14 days (-20 pts)
- Last meeting had ≤2 attendees and no new stakeholders (-15 pts)
- Champion role changed or left the company (detected via LinkedIn/ZoomInfo signal) (-40 pts, trigger immediate intervention)
- Deal has been in same stage for ≥21 days with no documented champion activity (-25 pts)

CHS Interpretation:
- 75+: Active champion. Predicted close rate 2.1× baseline. No intervention needed.
- 50–74: Moderate champion. Provide fresh "internal selling kit" — pre-written email templates champion can forward to each approver, with personalized subject lines.
- 25–49: Weak champion. Schedule champion coaching call. Provide a specific "next step" with a hard date (e.g., "Can you schedule a 30-min business case review with your CFO by [date]?").
- <25: Champion at risk. Escalate: request executive introduction directly ("Would it make sense for [your CEO/CRO] to connect briefly with [their CPO/CTO]?"). If no response within 5 business days, move to forecast risk bucket.

## 5. SALES CYCLE COMPRESSION ATTRIBUTION MODEL

Track the average deal cycle length for deals where each enablement intervention occurred vs. where it did not. Run a cohort comparison across 50+ historical closed deals.

**Intervention measurement template:**

| Intervention | When Delivered (Stage) | Deals WITH Intervention (avg days to close) | Deals WITHOUT (avg days to close) | Days Saved | Win Rate WITH | Win Rate WITHOUT | Net Revenue Impact |
|---|---|---|---|---|---|---|---|
| Digital deal room launched at Stage 1 | Discovery | [X days] | [Y days] | [X-Y] | [%] | [%] | [$] |
| ROI calculator completed by buyer at Stage 2 | Post-Demo | | | | | | |
| Matched case study delivered at Stage 2 | Post-Demo | | | | | | |
| Security questionnaire pre-fill at Stage 3 | Technical Val | | | | | | |
| Executive one-pager forwarded to CFO at Stage 3 | Business Case | | | | | | |
| POC with written success criteria at Stage 3 | Technical Val | | | | | | |
| Reference call arranged at Stage 4 | Business Case | | | | | | |
| Pre-built contract redlines delivered at Stage 5 | Legal/Finance | | | | | | |

For each intervention, calculate:
- Days saved vs. control group
- Win rate lift (percentage points)
- Revenue impact: (days saved × daily deal value × pipeline volume) + (win rate lift × ACV × pipeline count)
- Prioritization rank: Which interventions have the highest combined days-saved + win-rate-lift × deal volume?

## 6. WEEKLY BUYER ENGAGEMENT INTELLIGENCE REPORT (BEIR)

**Auto-generated every Monday. Distributed to: AEs, Sales Manager, PMM lead.**

**Section 1 — Deal Room Health Summary**
- Total deals with active deal rooms: [N]
- Deals with engagement in last 7 days: [N] ([%] of total)
- Deals with zero engagement in last 14 days: [N] — named list with last activity date and owner
- Deals with new stakeholder access this week: [N] — these are expansion signals, prioritize outreach

**Section 2 — Top 5 Hot Deals (High Engagement, High Value)**
Rank by: BESS score × ACV × stage probability. Surface the 5 deals most likely to close this month. For each: last buyer action, next recommended action, days since last AE activity.

**Section 3 — Top 5 At-Risk Deals (Stall Signals)**
Rank by: BESS score decay rate × deal age. For each: last buyer engagement date, current BESS score vs. score 2 weeks ago (trend), champion health score, recommended intervention (specific action with owner and due date).

**Section 4 — Content Leaderboard (This Week)**
- Most viewed content across all active deal rooms (top 5 assets by view count)
- Most forwarded content (top 3 assets forwarded to new stakeholders by champions — strong signal)
- Content with zero engagement in last 30 days (candidates for retirement or repositioning)

**Section 5 — POC Tracker**
- Active POCs: [N]
- % of POC criteria completed (by deal)
- POCs past due date with <80% completion: [N] — these need intervention
- POC completions this week: [N] — these are close-ready signals, initiate legal/finance prep

**Section 6 — Champion Activity Digest**
- Champions with high CHS (75+): [N] — no action needed
- Champions with declining CHS (dropped >20 pts this week): [N] — immediate coaching
- Champion job change detected this week: [N] — critical: run playbook

# IMPLEMENTATION REQUIREMENTS

For each component of the framework above, provide:
1. **Data source**: Which tool/API provides this data (deal room platform, CRM, Gong, calendar)
2. **CRM field mapping**: Exact Salesforce/HubSpot field names to create or map to
3. **Automation rule**: The trigger → action logic for AI agent execution (e.g., "When BESS drops below 25, create CRM task for AE with intervention script, CC sales manager, send champion a personalized re-engagement email using the [template name] sequence")
4. **Reporting query**: The Salesforce SOQL or HubSpot filter logic for each dashboard view
5. **Benchmark calibration**: How to establish your baseline in the first 30 days before you have historical data (use last 12 months of closed deals as training set)

# CONSTRAINTS
- Every metric must be measurable from existing tool data — no manual data entry by AEs
- The BESS and CHS scores must auto-update daily via Zapier, native integrations, or a lightweight Python/API script
- All alerts must be actionable: include the specific next step the AE should take, not just a warning
- The weekly BEIR must be auto-generated as a Slack message or email — zero manual compilation
- All recommendations must be validated against historical win/loss data before deployment

## Example Input/Output

**Input Example:**

Company: Meridian DataOps — B2B SaaS data pipeline platform
ACV: $110K average, range $55K–$280K
Sales cycle: 127 days average
Win rate on qualified pipeline: 24%
Deal room: Seismic LiveSend (limited analytics — view counts and time-on-page only)
CRM: Salesforce Enterprise
Revenue intelligence: Gong
Top deal stall point: Technical validation stage — deals sit 38 days on average
Champion profile: VP of Data Engineering
Economic buyer: CTO or CFO depending on deal size
Biggest blind spot: "We have no idea if our champions are actually showing our materials to anyone, or if it's just sitting in their inbox."

**Output Example:**

**BESS Model for Meridian DataOps:**
Score calculation for Deal #SF-2847 (CloudStream Inc., $175K ACV, Stage 3):
- Stakeholder breadth: 3 unique engagers / 5 expected buying committee = 15/25 pts
- Content depth: Economic buyer (CFO one-pager viewed 2× = 10 pts) + Technical (architecture doc downloaded = 12.5 pts) = 22.5/25 pts
- Engagement recency: Last activity 5 days ago = 18/20 pts
- Champion activation: Forwarded deal room to new contact (5 pts), created internal meeting after architecture doc share (5 pts) = 10/20 pts
- POC: 7/10 success criteria complete = 7/10 pts
**BESS Score: 72.5/100 — Moderate engagement zone. Predicted win rate: 41%. Priority: Identify missing 2 stakeholders (likely Procurement and CISO). Recommend: Champion coaching call — provide CISO security brief and procurement pre-fill package this week.**

**Sales Cycle Compression Findings (Hypothetical 90-deal cohort):**
Top 3 highest-impact interventions for Meridian DataOps:
1. Security questionnaire pre-fill delivered at Stage 3: -23 days average (127 → 104 days), +11 pp win rate. Revenue impact: $2.3M annually on current pipeline.
2. Matched case study forwarded to CTO: -14 days, +7 pp win rate. Revenue impact: $1.1M annually.
3. Digital deal room launched at Stage 1 (vs. sending individual files): -9 days, +5 pp win rate. Revenue impact: $680K annually.
**Recommendation: Prioritize security questionnaire automation. Build a library of pre-filled questionnaires for top 8 security question sets. Assign ownership to PMM. Deploy within 30 days.**

## Success Metrics
- BESS score correlation with win rate: Should achieve ≥0.65 Pearson correlation within first 90 days of tracking
- Deal stall early warning accuracy: ≥70% of stalled deals (no activity for 30+ days) should have shown BESS decline ≥15 pts in the preceding 14 days
- Cycle compression attributable to buyer enablement interventions: Target ≥10% reduction in average sales cycle within 6 months of framework deployment
- Champion CHS predictive accuracy: High CHS (75+) deals should close at ≥2× win rate of low CHS (<25) deals
- Content utilization: ≥80% of active Stage 3+ deals should have at least one buyer enablement asset with tracked engagement (vs. untracked email attachments)
- AE adoption rate: ≥75% of AEs should be referencing BEIR insights in their weekly deal reviews within 60 days

## Related Prompts
- [Buyer Enablement Content Architecture & Deal Acceleration](../../04_Demand-&-Lead-Generation-&-Growth/Buyer-Enablement/AI-Powered-B2B-SaaS-Buyer-Enablement-Content-Architecture-&-Internal-Champion-Deal-Acceleration-Revenue-Intelligence-Engine.md)
- [Executive Stakeholder Alignment Package Architecture](../../04_Demand-&-Lead-Generation-&-Growth/Buyer-Enablement/AI-Powered-B2B-SaaS-Executive-Stakeholder-Alignment-Package-Architecture-&-Internal-Champion-Consensus-Building-Revenue-Intelligence-Engine.md)
- [Sales Conversation Intelligence Analytics](../../05_Analytics-&-Performance/Sales-Conversation-Intelligence/AI-Powered-B2B-SaaS-Buying-Committee-Conversation-Intelligence-&-Multi-Stakeholder-Deal-Analytics-Revenue-Intelligence-Engine.md)
- [Pipeline Stage Conversion Optimization](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Pipeline-Stage-Conversion-Optimization-&-Revenue-Velocity-Acceleration-Intelligence-Engine.md)

## Integration Tips
- **Salesforce**: Create a custom "Buyer Engagement" section on the Opportunity page layout with BESS score, CHS score, last buyer activity date, and top missing stakeholder fields. Use Salesforce Flow to auto-calculate BESS daily from deal room API webhook data.
- **HubSpot**: Use HubSpot's Custom Properties + Workflows to mirror the BESS/CHS scoring. Set "Risk Alert" workflow to trigger when BESS drops below 25 or CHS drops below 30 — auto-enroll AE in a task sequence.
- **Seismic/Highspot**: Use native analytics exports (available via API) to pull per-asset engagement data into your CRM nightly. Seismic LiveSend and Highspot SmartLinks both support stakeholder-level tracking — ensure AEs are using trackable links, not email attachments.
- **Gong**: Use Gong Engage's deal intelligence to supplement BESS with conversation signals — if a deal has high deal room engagement but no recent call activity, that's a stall signal. Create a Gong + Salesforce alert: "High BESS, no call in 21 days → nudge AE."
- **Accord/GetAccept**: These platforms natively track mutual action plan completion (equivalent to POC criteria tracking). Use the Accord API or GetAccept webhooks to push POC completion % to your CRM opportunity record daily.
- **Zapier/Make**: Orchestrate the weekly BEIR report using a Zapier multi-step zap: pull data from Salesforce via scheduled report → format in Google Sheets → post formatted summary to #revenue-intelligence Slack channel every Monday at 7am.
- **Notion**: If using Notion as a deal room, install a third-party analytics layer (Notimize or Whaly) to get page-view data per collaborator. Map Notion page visitors to Salesforce contacts for stakeholder tracking.

## Troubleshooting
- **Problem:** AEs aren't using trackable deal room links — sending email attachments instead, making engagement invisible.
  **Solution:** Make deal room creation a required Salesforce field to progress to Stage 2. Build a Salesforce validation rule that blocks stage advancement unless "Deal Room URL" field is populated. Run a 15-min AE training session showing the BESS score difference between tracked vs. untracked deals.

- **Problem:** BESS score isn't predicting win rate — tracked deals and untracked deals are winning at the same rate.
  **Solution:** First check sample size (need ≥40 closed deals per cohort for statistical significance). Second, audit whether deal room links are actually being opened by buyers vs. just by the AE testing the link. Third, check if your deal room is set to require login (which suppresses organic sharing) — switch to passcode-only access to reduce friction.

- **Problem:** Champion CHS is consistently high but deals are still stalling and losing.
  **Solution:** The champion is engaged but not influential. Audit whether champion introductions are actually reaching economic buyers (CHS measures activity, not authority). Add a new CHS signal: "Economic buyer has directly engaged content" (worth 25 pts, overrides other signals). If champion CHS is high but economic buyer content engagement is zero, trigger an executive-to-executive outreach offer immediately.

## Version History
- v1.0: Initial creation (auto-generated)
