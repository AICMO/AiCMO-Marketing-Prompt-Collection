# AI-Powered B2B SaaS Customer Success Qualified Lead (CSQL) Architecture & Expansion Revenue Signal Intelligence Engine - Turn Product Usage & Customer Signals Into a Systematic Expansion Pipeline Machine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** csql, expansion-revenue, customer-success, nrr, product-signals, b2b-saas, cs-sales-alignment, pipeline-generation, upsell, ai-automation

## Overview

Build an AI-powered CSQL (Customer Success Qualified Lead) program that transforms product usage telemetry, health signals, and business trigger events into a systematic expansion pipeline — automating the identification, prioritization, and sales-handoff of accounts primed to buy more. Use this when your CSMs are sitting on expansion intelligence buried in dashboards, but lack a repeatable motion to surface it to revenue teams at the right moment.

## Quick Copy-Paste Version

You are a senior Customer Success revenue strategist who specializes in building CSQL (Customer Success Qualified Lead) programs for B2B SaaS companies.

My company context:
- Company: [Your Company Name]
- Product: [What you sell, e.g., AI-powered project management platform for engineering teams]
- Current customers: [e.g., 400 accounts]
- ACV range: [e.g., $18K–$120K]
- CS team size: [e.g., 8 CSMs managing ~50 accounts each]
- Product/CS platform: [e.g., Gainsight + Mixpanel + Salesforce]
- Expansion products available: [e.g., Advanced Analytics add-on, Seats, Premium Support, Enterprise tier]
- Current expansion revenue as % of ARR: [e.g., 22% — goal is 35%]
- Primary expansion blocker: [e.g., CSMs don't know when or how to introduce expansion; sales reps don't trust CS-sourced signals]

Build a complete AI-powered CSQL architecture with:

1. CSQL SIGNAL TAXONOMY
   - Define 5 product usage signals that indicate expansion readiness (e.g., feature adoption hitting a capacity threshold, seat utilization >85%, export/API call frequency spike)
   - Define 3 business trigger signals (e.g., LinkedIn headcount growth >20%, funding round closed, new department mentioned on call)
   - Define 3 relationship health signals (e.g., QBR outcome score, NPS ≥9, executive sponsor re-engaged after silence)
   - For each signal: data source, refresh cadence, and what expansion play it triggers

2. CSQL SCORING MODEL
   - Create a weighted CSQL Score (0–100) combining product signals (40%), business signals (35%), and health signals (25%)
   - Define CSQL tier thresholds: Cold (0–39), Warm (40–64), Hot (65–79), Ready-to-Buy (80+)
   - Explain how to normalize signals across different customer segments (SMB vs. mid-market vs. enterprise)
   - Define a decay function: how signals lose weight over time if no action is taken

3. AUTOMATED CSQL WORKFLOW
   - Map the full automation sequence from signal detection → CSQL score update → sales alert → CSM notification → outreach initiation
   - Write the exact Slack/email alert template sent to the AE when a CSQL hits "Hot" tier
   - Define the CSM briefing package: what 5 data points the CSM delivers to the AE before the expansion conversation
   - Create the internal SLA: AE must respond to Hot CSQL within [X hours], CSM must complete briefing within [Y hours]

4. EXPANSION PLAY LIBRARY — create 3 distinct expansion plays:
   - Play A: "Capacity Ceiling" — triggered when seat/usage hits 85% of plan limit
   - Play B: "New Team Expansion" — triggered by new department or team detected at account
   - Play C: "Success Milestone Upsell" — triggered at post-ROI-realization milestone (e.g., 6 months post-onboarding, first QBR outcome score ≥8)
   For each play: trigger condition, outreach sequence (3 touchpoints), who owns it (CSM vs. AE), message framing, and expected conversion rate

5. CS-TO-SALES HANDOFF PROTOCOL
   - Design a 5-field "CSQL Handoff Card" that CSMs complete in the CRM before passing to sales
   - Write a 90-second CSM-to-AE verbal briefing script
   - Define handoff ownership model: who owns the deal once CSQL is accepted? When does ownership revert?
   - Create a feedback loop: how sales reports back to CS on CSQL quality within 30 days

6. CSQL PROGRAM METRICS & REPORTING
   - Define 6 KPIs to track CSQL program health
   - Create a weekly CSQL pipeline report template for CS leadership
   - Design a monthly CS-sales joint CSQL review agenda (30-minute meeting structure)

Output each section with specific frameworks, example copy, and tool configurations (Gainsight rules, Salesforce field mapping, Slack integration). Make every output immediately actionable — no vague strategy, only executable plays.

## Advanced Customizable Version

ROLE: You are a Revenue Architecture consultant with 15 years of B2B SaaS experience, specializing in CS-led growth motions and the operationalization of CSQL programs across Series B through pre-IPO companies. You have deep expertise in Gainsight, ChurnZero, Salesforce, HubSpot, and product analytics platforms (Mixpanel, Amplitude, Pendo, PostHog).

OBJECTIVE: Design a production-ready AI-powered CSQL (Customer Success Qualified Lead) architecture that systemically converts product usage data, business signals, and relationship health indicators into a managed expansion pipeline — with automated scoring, CS-sales handoff protocols, and closed-loop reporting.

COMPANY CONTEXT:
- Company name: [Your Company]
- Product category: [e.g., Revenue Operations Platform / Security Awareness Training / Data Observability]
- Business model: [e.g., seat-based SaaS / usage-based / module-based]
- ARR: [e.g., $18M]
- Customer count: [e.g., 320 accounts]
- ACV range: [e.g., $25K–$180K]
- Customer segments: [e.g., SMB <$30K, Mid-Market $30K–$100K, Enterprise >$100K]
- CS team structure: [e.g., 10 CSMs + 2 CS Managers + 1 VP CS; CSMs own 30–60 accounts each depending on tier]
- Current tools: [CRM: Salesforce | CS Platform: Gainsight | Product Analytics: Mixpanel | Data Warehouse: Snowflake | Communication: Slack]
- Expansion products: [List all add-ons, tier upgrades, seat packages, professional services SKUs]
- Current NRR: [e.g., 108%]
- Expansion pipeline currently: [e.g., mostly ad hoc; 15% of new expansion deals sourced by CS]
- Primary pain: [e.g., CSMs identify signals too late; AEs don't trust CS leads; no consistent expansion playbook]
- Sales cycle for expansion deals: [e.g., 21 days average]

PART 1 — CSQL SIGNAL INTELLIGENCE FRAMEWORK

Define a three-layer signal architecture:

LAYER 1 — PRODUCT USAGE SIGNALS (data from Mixpanel/Amplitude/Pendo):
For each of the following signal types, specify: signal name, exact data source/event, threshold logic, refresh cadence, and which expansion SKU it maps to:
a) Capacity/saturation signals (seat utilization, API call volume, storage usage approaching limits)
b) Feature adoption velocity signals (power feature first-use + frequency crossing a threshold)
c) Cross-team expansion signals (users from new departments or cost centers activating)
d) Integration depth signals (number of integrations, API write volume, data pipeline activity)
e) Engagement frequency signals (DAU/MAU ratio improvements, weekly active projects, etc.)

LAYER 2 — BUSINESS TRIGGER SIGNALS (data from LinkedIn, news, Bombora, ZoomInfo, CRM):
a) Headcount growth signals (>15% headcount growth in 90 days, new department formed)
b) Funding signals (Series A/B/C announced, PE acquisition, IPO filing)
c) Strategic initiative signals (M&A activity, new market entry, digital transformation news)
d) Title change signals (economic buyer promoted, new department head who uses your product)

LAYER 3 — RELATIONSHIP HEALTH SIGNALS (data from Gainsight/ChurnZero/CRM):
a) NPS trajectory (score ≥9, or improvement of ≥3 points in 60 days)
b) QBR outcome quality (QBR score ≥8/10, ROI confirmed by customer in call notes)
c) Champion engagement (executive sponsor re-activated, new executive sponsor introduced)
d) Support resolution rate (ticket resolution CSAT ≥4.5, no P1 tickets in 90 days)

For each signal: define the exact Gainsight rule or CRM automation trigger that detects it.

PART 2 — CSQL SCORING ALGORITHM

Design a weighted composite CSQL Score (0–100):
- Product Usage Signals: 40% weight (sum of triggered product signals, normalized 0–40)
- Business Trigger Signals: 35% weight (sum of triggered business signals, normalized 0–35)
- Relationship Health Signals: 25% weight (sum of health signals, normalized 0–25)

Define:
a) Tier thresholds with recommended actions:
   - Developing (0–39): CSM monitors, no sales involvement
   - Emerging (40–59): CSM begins expansion discovery in next scheduled touchpoint
   - Hot CSQL (60–79): CSM briefs AE, creates CSQL record in Salesforce, AE joins next call
   - Ready-to-Buy CSQL (80–100): AE leads expansion motion within 5 business days, CSM plays support role

b) Segment-specific scoring adjustments:
   - SMB multiplier: lower threshold for capacity signals (they hit limits faster)
   - Enterprise adjustment: weight relationship signals higher (deals are more relationship-dependent)
   - PLG adjustment: weight product signals at 60% for self-serve accounts

c) Score decay rules:
   - Product signals decay 10% per 30 days if no new trigger fires
   - Business signals decay 20% per 60 days (business context changes fast)
   - Health signals decay 15% per 45 days

PART 3 — AUTOMATED CSQL DETECTION & ALERT SYSTEM

Design the full automation chain in your tech stack:

Step 1 — Signal ingestion: How Snowflake/Mixpanel data feeds into Gainsight CTAs (Customer Touchpoint Actions) and Salesforce custom fields

Step 2 — Score calculation: Gainsight scorecard rules or Salesforce Flow that calculates composite CSQL Score nightly

Step 3 — Tier promotion alert: When an account crosses into Hot CSQL (60+), trigger:
   a) Gainsight CTA assigned to CSM: "Prepare CSQL Briefing for [Account Name]"
   b) Slack DM to AE: "[Account Name] just hit CSQL Hot tier — [Top 3 signals]. CSM [Name] will brief you by [Date]. Check Salesforce CSQL record."
   c) Salesforce CSQL Opportunity created (Stage: CS Qualified) with auto-populated fields

Step 4 — Write the exact Slack alert message template (max 5 lines, with emoji, signal summary, and action prompt)

Step 5 — Write the Salesforce CSQL Opportunity auto-creation field map (10 fields: Account, ACV potential, signal drivers, CSM owner, target close date, next step)

PART 4 — EXPANSION PLAY LIBRARY

Design 5 expansion plays with full execution detail:

PLAY 1: "CAPACITY CEILING" (triggered when usage ≥85% of plan limits)
- Trigger: Mixpanel event "plan_capacity_alert" fires OR seat utilization field in Salesforce ≥85%
- Message frame: Cost of constraint vs. value of headroom — use the buyer's own growth data
- Outreach sequence: [Day 0] CSM proactive check-in email → [Day 5] CSM-AE joint discovery call → [Day 12] AE sends upgrade proposal
- Write Day 0 email subject + body (150 words, specific, non-pushy)
- Expected close rate: [benchmark from similar plays]
- Who owns: CSM initiates, AE closes

PLAY 2: "NEW TEAM EXPANSION" (triggered by new department activation or headcount signal)
- Trigger: New user from different department activates OR LinkedIn headcount growth >20%
- Message frame: Standardize [Product] across the whole organization — reference ROI already proven in original team
- Outreach sequence: [Day 0] CSM executive sponsor check-in → [Day 7] AE sends "standardization" business case → [Day 14] Joint call to map expansion scope
- Write Day 0 executive outreach email (100 words, executive tone)
- Expected close rate: [benchmark]
- Who owns: AE leads with CSM as trusted advisor

PLAY 3: "SUCCESS MILESTONE UPSELL" (triggered at ROI realization event — 6 months post-onboarding or post-QBR ROI confirmation)
- Trigger: Gainsight milestone "Success Moment" logged OR QBR outcome score ≥8
- Message frame: You've proven value — now scale it. Reference specific ROI metric customer reported.
- Outreach sequence: [Day 0] CSM sends "success summary" with expansion opportunity framing → [Day 3] AE follows up with ROI-based upgrade proposal → [Day 10] Decision call
- Write Day 0 CSM "success summary" email template
- Expected close rate: [benchmark — typically highest of all expansion plays]
- Who owns: CSM-led, AE closes

PLAY 4: "CHAMPION JOB CHANGE EXPANSION" (triggered when a champion moves to a new company or gets promoted)
- Trigger: LinkedIn job change alert OR title change detected in ZoomInfo enrichment
- Message frame: Two-pronged — (a) protect account with champion successor development, (b) pursue new logo opportunity at champion's new company
- Outreach: [Immediate] CSM reaches out to congratulate champion + introduces successor + warm intro request for new company
- Write the congratulations + warm intro request email (120 words)
- Who owns: CSM for retention play, SDR for new logo play (warm CSQL pass)

PLAY 5: "INTEGRATION DEPTH TRIGGER" (triggered when customer builds deep integrations indicating strategic dependency)
- Trigger: API call volume increases 3x in 30 days OR 3+ new integrations activated
- Message frame: Platform consolidation — they're building their operations around you, upgrade to Enterprise for SLA, dedicated support, and advanced features
- Outreach sequence: [Day 0] CSM business review request → [Day 7] AE + CSM joint "partnership expansion" call → [Day 14] Enterprise proposal sent
- Write AE introductory email for the "partnership expansion" call (100 words)
- Who owns: AE-led, CSM provides technical depth

PART 5 — CS-TO-SALES HANDOFF PROTOCOL

Design a frictionless handoff system:

a) CSQL HANDOFF CARD (5-field Salesforce record CSM completes before passing):
   Field 1: Top 3 CSQL signals (with dates and data)
   Field 2: Expansion opportunity (which SKU, estimated ACV uplift)
   Field 3: Champion name + title + expansion readiness statement
   Field 4: Economic buyer name + title + last engagement date
   Field 5: Recommended expansion play + suggested first outreach approach

b) CSM-TO-AE BRIEFING SCRIPT (90 seconds, verbal handoff before joint call):
   Write the exact script with: account background, signal summary, expansion opportunity, recommended approach, one risk to be aware of.

c) HANDOFF SLA:
   - Hot CSQL: AE acknowledges within 4 hours, schedules discovery within 3 business days
   - Ready-to-Buy CSQL: AE acknowledges within 2 hours, outreaches to customer within 24 hours
   - CSM remains as "trusted advisor" on all expansion deals until closed

d) OWNERSHIP MODEL:
   - Pre-close: AE owns expansion opportunity; CSM co-sells as product/relationship expert
   - Post-close: CSM resumes primary ownership; AE confirms implementation kickoff
   - If CSQL goes stale (no AE action within SLA): CSQL reverts to CSM queue with "AE inaction" flag, CS Manager escalates

e) FEEDBACK LOOP:
   - 30 days post-handoff: AE submits CSQL quality score (1–5) in Salesforce
   - AE provides: was context accurate? Was timing right? What was outcome?
   - Monthly CSQL quality review: CS Manager and Sales Manager review quality scores, adjust signal thresholds

PART 6 — CSQL PROGRAM METRICS & REPORTING

Define 8 KPIs with targets and measurement method:
1. CSQL Volume: # of CSQLs created per month (target: [X% of active accounts])
2. CSQL Acceptance Rate: % of CSQLs accepted by sales within SLA (target: >85%)
3. CSQL-to-Opportunity Conversion: % of accepted CSQLs that become active opportunities (target: >60%)
4. CSQL Win Rate: % of CSQL opportunities closed won (benchmark: should be 2–3x cold outbound win rate)
5. CSQL Average ACV: Average expansion deal size from CSQL motion (track trend)
6. CSQL Cycle Time: Average days from CSQL creation to close (target: <30 days)
7. CS CSQL Contribution to NRR: % of NRR growth attributed to CSQL-sourced deals
8. Signal Accuracy Rate: % of signals that accurately predicted expansion intent (quarterly audit)

WEEKLY CSQL PIPELINE REPORT TEMPLATE:
Create a template with: total active CSQLs by tier, new CSQLs added this week, CSQLs accepted/rejected by AEs, deals in progress, deals closed this week, top 5 priority CSQLs requiring immediate attention.

MONTHLY CS-SALES JOINT CSQL REVIEW AGENDA (30 minutes):
- [5 min] CSQL Volume & Quality Metrics Review
- [10 min] Top 5 Hot CSQL accounts — CSM presents signals, AE shares deal status
- [5 min] Closed CSQL wins & learnings
- [5 min] Signal accuracy audit — what signals predicted correctly, what didn't?
- [5 min] Action items & threshold adjustments for next month

CONSTRAINTS:
- Every workflow step must map to a specific tool action (Gainsight rule, Salesforce automation, Slack webhook)
- Every email template must be <150 words and ready to copy-paste
- Every scoring formula must be computable without a data science team
- Every play must include a "skip condition" — when NOT to run this play even if the score is high enough

OUTPUT FORMAT: Use numbered sections with sub-bullets. Include exact email templates in blockquotes. Provide Gainsight/Salesforce field names where possible. End each section with a "Quick Start Action" — the single most important thing to implement first if you're starting from scratch.

## Example Input/Output

**Input Example:**
Company: Meridian Analytics — B2B SaaS for supply chain visibility
Product: Seat-based platform ($35K base, $12K Analytics add-on, Enterprise tier $90K+)
ARR: $14M, 280 accounts
CS Team: 7 CSMs, ~40 accounts each, Gainsight + Salesforce
Current NRR: 104% (goal: 115% in 12 months)
Current expansion: Mostly AE-driven, reactive; CS contributes ~8% of expansion deals
Primary pain: CSMs know which customers are ready to expand but have no structured way to pass to sales; AEs ignore ad hoc Slack messages
Segments: SMB 150 accounts ($25K–$45K ACV), Mid-Market 100 accounts ($45K–$90K ACV), Enterprise 30 accounts ($90K–$200K ACV)
Expansion products: Analytics Add-on ($12K), Additional Seats ($500/seat/year), Enterprise Upgrade ($55K incremental), Professional Services ($15K)

**Output Example (excerpt):**

**CSQL Signal: Capacity Ceiling — Seat Utilization**
- Data Source: Salesforce custom field "Seat_Utilization_Pct" (synced nightly from Meridian product DB via Snowflake → Gainsight → Salesforce)
- Trigger: Seat_Utilization_Pct ≥ 85% for 7+ consecutive days
- Gainsight Rule Name: "CSQL_Capacity_Ceiling_Trigger"
- Mapped Expansion SKU: Additional Seats ($500/seat/year)
- CSQL Score Contribution: +18 points (Product Usage Signal, Layer 1)
- Decay: -2 points per week after 30 days if no additional seats purchased or inquiry logged

**Capacity Ceiling Outreach — Day 0 CSM Email:**
> Subject: Quick thought on your Meridian seat capacity, [Name]
>
> Hi [Champion Name],
>
> I was reviewing your Meridian usage this week and noticed your team is running at 87% seat capacity — which is actually a good sign, it means the platform is embedded deeply across [Team Name].
>
> I wanted to flag it proactively before it becomes a blocker. A few of our customers at similar scale added a seat block before the quarter closed to avoid any friction during peak periods.
>
> Happy to share a quick breakdown of what's being used most heavily and what a small expansion would unlock. 15 minutes this week?
>
> [CSM Name]

**CSQL Score for Meridian Account "Apex Logistics" (Mid-Market, $52K ACV):**
- Seat Utilization at 91%: +18 pts
- Analytics Feature Adoption (power users crossed threshold): +14 pts
- LinkedIn headcount +22% in 90 days: +28 pts
- NPS score 9 submitted last week: +16 pts
- **Total CSQL Score: 76 → Hot CSQL tier**
- Recommended Play: Capacity Ceiling + New Team Expansion (combo)
- Estimated ACV uplift: $18K–$30K (seats + Analytics add-on)
- AE Alert generated: 11:02am Monday, Slack DM to AE Sarah Chen with briefing card

## Success Metrics

- **CSQL acceptance rate** ≥ 85% (AEs accepting and acting on CSQLs within SLA)
- **CSQL-to-close rate** ≥ 45% (benchmark: 2–3x cold outbound win rate)
- **Time-to-close for CSQL deals** < 25 days (vs. 45+ days for AE-sourced expansion)
- **NRR impact**: CS-sourced expansion as % of total NRR improvement increases by ≥10 percentage points within 6 months
- **Signal accuracy**: ≥70% of Hot CSQLs result in a sales conversation within 30 days
- **CSM adoption**: ≥90% of eligible CSMs creating ≥2 CSQLs/month within 90 days of program launch

## Related Prompts

- [AI-Powered CS-Sourced Pipeline & Warm Introduction Revenue Intelligence Engine](../../06_Customer-Success-&-Retention/Customer-Advocacy-&-Referral/AI-Powered-CS-Sourced-Pipeline-&-Warm-Introduction-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Customer Expansion Revenue Intelligence & Upsell Opportunity Identification Engine](../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/AI-Powered-B2B-SaaS-Customer-Expansion-Revenue-Intelligence-&-Upsell-Opportunity-Identification-Engine.md)
- [AI-Powered B2B SaaS NRR Marketing Program Architecture & Expansion Revenue Campaign Intelligence Engine](../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/AI-Powered-B2B-SaaS-NRR-Marketing-Program-Architecture-&-Expansion-Revenue-Campaign-Intelligence-Engine.md)
- [AI-Powered B2B Product Usage Signal & Expansion Revenue Trigger Intelligence Engine](../../06_Customer-Success-&-Retention/Customer-Success-Automation/AI-Powered-B2B-Product-Usage-Signal-&-Expansion-Revenue-Trigger-Intelligence-Engine.md)

## Integration Tips

- **Gainsight**: Use Timeline Activities to log CSQL signal events. Build a custom CTA type called "CSQL Hot" with a Cockpit priority override so CSMs see it immediately. Use Journey Orchestrator to automate the Day 0 email trigger for Capacity Ceiling plays.
- **Salesforce**: Create a custom CSQL Opportunity Stage ("CS Qualified") before "Discovery." Add a "CSQL Score" numeric field and "CSQL Signal Summary" text field on the Opportunity object. Build a Flow that auto-creates the CSQL Opportunity when Gainsight pushes score ≥60.
- **HubSpot**: Use Deal Pipeline custom stages and Workflow triggers on custom contact/company properties for CSQL scoring. Connect Mixpanel via HubSpot's Events integration to pass product usage data.
- **Slack**: Use Gainsight's Slack integration or Zapier to send formatted CSQL alerts to a dedicated #csql-pipeline channel with @mention to the AE. Include a direct link to the Salesforce CSQL record.
- **Mixpanel/Amplitude**: Create a cohort called "CSQL Candidate" based on the product signal logic. Export this cohort to Salesforce/Gainsight daily via their native data connectors.
- **ChurnZero**: Use ChurnZero "ChurnScores" as the product signal layer. Build plays that trigger when a ChurnScore crosses into the green zone combined with a capacity event.
- **Snowflake**: If using a data warehouse, build a CSQL_SCORE view that CS Ops can query directly, and set up a daily dbt model that pushes the score back to Salesforce via Hightouch or Census.

## Troubleshooting

**Problem: AEs ignore CSQL alerts and don't act within SLA**
Solution: Escalate accountability to Sales leadership — add CSQL acceptance rate to AE performance scorecards. Change Slack alerts to DM both the AE AND their manager. Host a monthly "CSQL wins showcase" where CS calls out expansion deals that AEs won from CSQL leads. Start with a 30-day pilot where a single AE runs every CSQL — use their results to build social proof with the rest of the team.

**Problem: Signal thresholds generate too many false positives (Hot CSQLs that aren't actually ready)**
Solution: Run a 60-day signal calibration sprint. For every CSQL that hits Hot tier, track the actual outcome (purchased, not ready, still in pipeline). Calculate signal accuracy by type. Increase thresholds for low-accuracy signals, decrease weight for noisy signals. Consider adding a "CSM confirmation gate" — a one-click confirmation where the CSM validates the CSQL before it triggers an AE alert.

**Problem: CSMs don't complete the CSQL Handoff Card, so AEs have no context**
Solution: Make the Handoff Card a blocking step — the Gainsight CTA cannot be closed as "Complete" until all 5 fields are filled in Salesforce. Add a 1-hour async training video showing CSMs how to fill the card in under 5 minutes. Create a "CSQL Briefing Template" in Salesforce as a pre-filled template CSMs just edit rather than write from scratch.

## Version History
- v1.0: Initial creation (auto-generated)
