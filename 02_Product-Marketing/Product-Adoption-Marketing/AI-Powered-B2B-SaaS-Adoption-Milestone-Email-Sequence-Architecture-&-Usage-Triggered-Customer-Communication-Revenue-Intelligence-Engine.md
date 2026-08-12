# AI-Powered B2B SaaS Adoption Milestone Email Sequence Architecture & Usage-Triggered Customer Communication Revenue Intelligence Engine - Build the Autonomous Email System That Turns Product Usage Into Retention and Expansion

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** product marketing, adoption marketing, behavioral email, usage-triggered, customer lifecycle, PLG, onboarding, retention, NRR, milestone marketing, B2B SaaS

## Overview
Designs a complete, product-event-driven email sequence system where every communication is triggered by what a customer DID in the product — not by calendar date — mapped across five adoption milestones: activation, first value, habit formation, multi-seat expansion, and power user. Use this when you need to replace generic date-based nurture with intelligent, usage-responsive communication that accelerates time-to-value and measurably improves retention in your first 90-day customer cohort.

## Quick Copy-Paste Version

You are a Product Marketing expert specializing in lifecycle email programs for B2B SaaS companies with product-led growth motions. Design a complete milestone-triggered email sequence system for a new customer's first 90 days that fires based on product usage events, not calendar dates.

COMPANY CONTEXT:
- Company: [e.g., "Vertis — AI-powered financial close automation for mid-market accounting teams"]
- Product: [e.g., "Automates month-end close by connecting to ERP, categorizing transactions, flagging anomalies, and generating board-ready close reports"]
- Business model: [e.g., "Annual SaaS — Starter ($12K/yr, 1-5 users), Growth ($38K/yr, up to 20 users), Enterprise ($95K+/yr, unlimited users)"]
- GTM motion: [e.g., "Sales-assisted PLG — 14-day trial, AE closes, CSM owns post-sale"]
- Email platform: [e.g., "Customer.io for behavioral triggers, HubSpot for marketing"]
- Product analytics: [e.g., "Amplitude, with events piped to HubSpot via Segment"]

FIVE ADOPTION MILESTONES TO SEQUENCE AROUND:

MILESTONE 1 — ACTIVATION: Customer completes the minimum setup required to see the product work (not just log in)
- Define what "activated" means for your product: [e.g., "Connected at least 1 ERP integration AND ran first automated close cycle"]
- Typical time to activation: [e.g., "3-7 days post-contract"]

MILESTONE 2 — FIRST VALUE: Customer gets their first meaningful output or result
- Define first value: [e.g., "Downloaded first AI-generated board close report OR received first anomaly alert that they acted on"]
- Typical time to first value: [e.g., "Day 7-14 after activation"]

MILESTONE 3 — HABIT FORMATION: Customer uses the product as part of their recurring workflow without prompting
- Define habituated use: [e.g., "Ran automated close cycle for 2 consecutive months without CSM nudge"]
- Typical time to habit: [e.g., "Day 45-75"]

MILESTONE 4 — TEAM EXPANSION: Additional users invited or seats activated beyond the initial setup
- Define expansion event: [e.g., "3+ users active within 30 days of contract start"]
- Typical time to expansion: [e.g., "Day 20-45"]

MILESTONE 5 — POWER USER: Customer uses advanced features or reaches usage ceiling for their tier
- Define power user threshold: [e.g., "Used AI anomaly detection on 3+ close cycles AND customized 2+ report templates"]
- Typical time to power user: [e.g., "Day 60-90"]

OUTPUT REQUIRED:
1. TRIGGER LOGIC MAP: Decision tree showing which email fires when, based on which events occur in what order
2. PRE-MILESTONE EMAILS: Emails sent BEFORE a milestone to help customers reach it (proactive)
3. MILESTONE CELEBRATION EMAILS: Emails sent IMMEDIATELY when a milestone is hit (rewarding progress)
4. MISSED MILESTONE ALERTS: Emails sent when expected milestones are overdue (rescue campaigns)
5. BRANCH LOGIC: What happens when customers reach milestones out of order or skip milestones
6. EXIT CRITERIA: What removes a contact from the sequence (milestone hit, CSM escalation, churn signal)

## Advanced Customizable Version

ROLE: You are a senior Product Marketing Manager with 12+ years designing lifecycle email programs and adoption campaigns for B2B SaaS companies at Series B through post-IPO stage. You have personally architected usage-triggered email systems that cut time-to-first-value by 40%, increased 90-day retention by 18 percentage points, and generated measurable expansion revenue by detecting and amplifying natural expansion signals before CSMs noticed them. You understand that date-based nurture is the enemy of adoption marketing — the right email at the wrong moment (too early before activation, too late after the customer gave up) destroys trust and burns deliverability. Every email in your system fires because of something the customer DID or DIDN'T DO in the product, never because 7 days passed on a calendar.

OBJECTIVE: Design a production-ready, milestone-triggered email sequence system that:
- Maps every significant product event to an email trigger decision
- Sends proactive "reaching milestone" emails to customers approaching — but not yet at — each milestone, reducing friction
- Celebrates milestone achievement with emails that reinforce the right behavior and set up the next milestone
- Detects milestone stall (customer activated but hasn't hit first value in 10 days) and deploys rescue campaigns automatically
- Branches correctly when customers advance out of sequence or skip milestones
- Feeds back into CSM platforms (Gainsight, ChurnZero) to create escalation tasks when email rescue campaigns fail
- Produces outputs a developer can implement in Customer.io, Iterable, Klaviyo, or Braze without further specification

---

COMPANY PROFILE:
- Company name & product: [name + one-sentence description]
- Industry vertical & ICP: [e.g., "Mid-market accounting and finance teams at manufacturing companies with $50M–$500M revenue"]
- Business model & tiers: [tier names, price points, user limits]
- GTM motion: [trial + AE close / sales-assisted PLG / fully self-serve / enterprise with CSM]
- CS-to-account ratio: [e.g., "1 CSM per 80 accounts" — determines how much CSM can cover vs. email must handle]
- Contract length & renewal cadence: [monthly / annual / multi-year]
- Average contract value: [e.g., "$28,000/year"]
- Current 90-day retention rate: [e.g., "84%"] — target after this system: [e.g., "91%"]

---

PRODUCT EVENT TAXONOMY:

Define the product events that correspond to each milestone. Your email system is only as intelligent as the events it can see.

SETUP & ACTIVATION EVENTS:
- account_created
- first_login (admin)
- integration_connected: [specific integration name — e.g., "NetSuite", "QuickBooks Online"]
- team_member_invited
- first_workflow_configured
- ACTIVATION EVENT: [your defined activation event — e.g., "first_close_cycle_completed"]

VALUE DELIVERY EVENTS:
- first_report_generated
- first_anomaly_flagged
- first_export_downloaded
- first_result_shared_externally
- FIRST VALUE EVENT: [your defined first value event — e.g., "board_report_downloaded"]

HABIT FORMATION EVENTS:
- workflow_run_without_prompt (no CSM calendar invite or email click preceding it)
- second_consecutive_monthly_cycle_completed
- HABIT EVENT: [your defined habit event — e.g., "close_cycle_completed_month_2"]

EXPANSION EVENTS:
- second_user_activated
- third_user_activated
- usage_approaching_tier_limit (>80% of tier's usage ceiling)
- EXPANSION EVENT: [your defined expansion event — e.g., "seat_count_exceeds_tier_included_count"]

POWER USER EVENTS:
- advanced_feature_used: [e.g., "custom_report_template_created"]
- api_connection_made
- workflow_customized_beyond_default
- POWER USER EVENT: [your defined threshold — e.g., "anomaly_detection_used_3x + 2_custom_templates_created"]

RISK EVENTS (trigger rescue campaigns):
- no_login_7_days_post_activation
- activation_stall: integration_connected but first_close_cycle_completed NOT fired within 5 days
- first_value_stall: ACTIVATION EVENT fired but FIRST VALUE EVENT NOT fired within 10 days
- habit_stall: FIRST VALUE EVENT fired but HABIT EVENT NOT fired within 30 days
- team_contraction: active_user_count drops by 2+ compared to 14-day peak

---

TRIGGER LOGIC ARCHITECTURE:

Map every email to a trigger condition using this format:

EMAIL NAME | TRIGGER CONDITION | SEND DELAY | SUPPRESSION RULE | EXIT CONDITION

PRE-ACTIVATION SERIES (fires after account_created, before ACTIVATION EVENT):

Email A1 — "Your setup checklist" 
→ TRIGGER: account_created
→ SEND: Immediately
→ SUPPRESSION: Suppress if ACTIVATION EVENT already fired (admin activated before email sent)
→ CONTENT: Step-by-step setup checklist, specific to their integration type. Not a generic welcome — it should know which integration they connected (or haven't yet) and give the NEXT action.
→ CTA: [specific action — e.g., "Connect your NetSuite account →"]

Email A2 — "Most teams connect in under 20 minutes"
→ TRIGGER: account_created + 48 hours elapsed + integration_connected NOT fired
→ SEND: 48 hours after A1
→ SUPPRESSION: Suppress if integration_connected fired at any point
→ CONTENT: Social proof + friction removal. "87% of accounting teams connect their ERP in under 20 minutes. Here's what usually slows teams down — and how to skip it." [Link to 3 common connection issues + solutions]
→ CTA: [e.g., "Resume your setup →"] — deep link directly into the integration setup flow, not the dashboard

Email A3 — "Can we help you connect? [CSM name]"
→ TRIGGER: account_created + 5 days elapsed + ACTIVATION EVENT NOT fired
→ SEND: Day 5 post-signup (if activation stall)
→ SUPPRESSION: Suppress if ACTIVATION EVENT fired
→ CONTENT: Personal-feeling note from CSM (or PMM using CSM name/photo). "I noticed your team hasn't completed your first close cycle yet — sometimes there's an integration issue or a config question we can answer in 15 minutes." 
→ CTA: [Calendar link — "Book a 15-minute setup session with [CSM Name]"]
→ PARALLEL ACTION: Create Gainsight/ChurnZero alert for CSM: "Activation stall Day 5 — email sent, follow up if no response by Day 7"

---

POST-ACTIVATION / PRE-FIRST VALUE SERIES (fires after ACTIVATION EVENT, before FIRST VALUE EVENT):

Email B1 — "You're live — here's what happens next"
→ TRIGGER: ACTIVATION EVENT fires
→ SEND: Within 15 minutes of event (near real-time)
→ SUPPRESSION: None — this always fires
→ CONTENT: Celebrate the activation milestone + set up the next one. "You just completed your first automated close cycle. Here's what to expect in the next 24 hours: [specific outputs they'll see — e.g., "Your board close report will be ready to download by [time]", "Any anomalies in your March data will appear in your Anomaly Feed by tomorrow morning"]"
→ CTA: [e.g., "View your close report →"] — deep link to the specific output they just generated

Email B2 — "Your first close report is ready"
→ TRIGGER: first_report_generated event fires
→ SEND: Within 5 minutes of event
→ SUPPRESSION: None
→ CONTENT: Direct. "Your board close report for [month] is ready. It took [X minutes] to generate — compare that to your previous process." [Link to report] + "Next step: share it with [CFO/Controller/Board] to show them what's changed."
→ CTA: [e.g., "Open your report →"] + [e.g., "Share with your team →"] (adds seat invitation prompt)

Email B3 — "You haven't downloaded your report yet"
→ TRIGGER: first_report_generated + 24 hours + first_export_downloaded NOT fired
→ SEND: 24 hours after B2
→ SUPPRESSION: Suppress if first_export_downloaded fired
→ CONTENT: Light reminder with a "why it matters" hook. "Your March close report has been ready for 24 hours. Teams that share their first AI-generated report with stakeholders within 3 days are 3x more likely to have their CFO request access — which is usually what triggers the team to fully switch over from the old process."
→ CTA: "Open your report →"

---

POST-FIRST VALUE SERIES (fires after FIRST VALUE EVENT, before HABIT EVENT):

Email C1 — "Your team's first win"
→ TRIGGER: FIRST VALUE EVENT fires
→ SEND: Within 15 minutes
→ SUPPRESSION: None
→ CONTENT: Celebration + next goal framing. "You just generated your first board-ready close report with Vertis. [If anomaly data available]: Your AI scan flagged [X] items that would have required manual review — saving an estimated [Y hours] of reconciliation time. Next milestone: run your second close cycle next month without a setup call — that's when most teams realize they've actually changed how they close."
→ CTA: [e.g., "Add next month's close to your calendar →"] (creates a calendar invite with the product workflow pre-filled)

Email C2 — "Three things that separate teams that stick with it"
→ TRIGGER: FIRST VALUE EVENT + 7 days + HABIT EVENT NOT yet fired
→ SEND: Day 7 after first value
→ SUPPRESSION: Suppress if HABIT EVENT fires before send
→ CONTENT: Behavioral insights. "Teams that get the most from Vertis in month 2 all have three things in common: [1] They added close automation to their monthly calendar, not just their occasional workflow. [2] They set up at least one anomaly alert threshold specific to their business. [3] They looped in at least one additional team member before month 2. Is your team set up for all three?"
→ CTA: [Series of 3 micro-CTAs — one per habit, each deep linking to the relevant product setup step]

Email C3 — "What happened to your close workflow?" [Rescue]
→ TRIGGER: FIRST VALUE EVENT + 21 days + HABIT EVENT NOT fired + no login in last 7 days
→ SEND: Day 21 if stall detected
→ SUPPRESSION: Suppress if any product event in last 7 days OR if CSM has logged a call in last 14 days (via Gainsight sync)
→ CONTENT: Direct intervention. "Your team used Vertis for your February close — but we haven't seen you since. We see this pattern sometimes: the first close goes well, but the team doesn't fully transition until month 2 feels as smooth as month 1. Here's what usually gets teams back on track: [2-3 specific common stall reasons + solutions]. Want 20 minutes to troubleshoot?"
→ CTA: [Calendar link to CSM] + [Link to "common month-2 setup issues" help article]
→ PARALLEL ACTION: Escalate to CSM in Gainsight if C3 is sent and no login occurs within 48 hours: "Habit stall — escalation required"

---

TEAM EXPANSION EMAILS:

Email D1 — "Add your team before month-end"
→ TRIGGER: ACTIVATION EVENT + 10 days + only 1 user logged in + team_member_invited NOT fired
→ SEND: Day 10 post-activation
→ SUPPRESSION: Suppress if 2+ users have logged in
→ CONTENT: Expansion nudge. "Right now, only [Admin Name] is using Vertis on your account. Teams that add at least 2 additional users in their first 30 days see [X%] faster time to habit — because the close process involves multiple people, and adoption follows the team, not just the admin."
→ CTA: [e.g., "Invite your team →"] — deep link to user invitation flow with suggested roles pre-populated (Controller, Staff Accountant, CFO)

Email D2 — "Your team just hit a milestone" [Expansion celebration]
→ TRIGGER: third_user_activated event fires
→ SEND: Within 30 minutes
→ SUPPRESSION: None
→ CONTENT: "Your team is growing on Vertis — [N] people are now using the platform. Teams with 3+ active users close [X days] faster than single-user accounts. [If approaching tier limit]: You're at [X] of [Y] included seats — here's how to add more if you need them."
→ CTA: [If approaching tier limit: "Talk to us about upgrading →"] [If not: "Keep your team collaborating →"]

---

POWER USER / PRE-EXPANSION EMAILS:

Email E1 — "You're in the top 15% of Vertis users"
→ TRIGGER: POWER USER EVENT fires
→ SEND: Within 1 hour
→ SUPPRESSION: None
→ CONTENT: Status elevation + expansion seed. "Your team has customized [X] report templates and run [Y] anomaly detection workflows — that puts you in the top 15% of Vertis accounts by feature depth. Teams at this level typically have one of two next steps: (1) roll Vertis out to more teams beyond [current team], or (2) explore our API for connecting Vertis into your broader finance stack."
→ CTA: [e.g., "Explore multi-team rollout →"] (routes to an AE-booked expansion conversation) + [e.g., "View API docs →"]

---

SUPPRESSION & GOVERNOR RULES (critical for deliverability):

1. MAX FREQUENCY RULE: Never send more than 2 emails per week to any contact, regardless of how many events fire. Queue overflow emails for the next available slot.
2. CSM SYNC RULE: Suppress any automated email if a CSM has had a meeting with the contact in the last 7 days — Gainsight sync required.
3. UNSUBSCRIBE RESPECT: All emails carry one-click unsubscribe. Contacts who unsubscribe are immediately added to a "CSM-only communication" segment — their CSM is notified to take over manually.
4. ROLE-BASED ROUTING: Admin/IT-persona contacts (identified by job title in CRM) suppress product value emails; they receive only technical setup and configuration emails. Economic buyer contacts (CFO, VP Finance) suppress setup emails; they receive only outcome and ROI emails.
5. TRIAL SUPPRESSION: During active trial period, suppress all milestone emails and run trial-specific onboarding sequence instead. Milestone emails activate at contract execution.

---

OUTPUT STRUCTURE REQUIRED:

1. TRIGGER LOGIC MAP (decision tree format): Every email with its trigger event, suppression rules, timing, and downstream action — in a format a marketing ops team can implement in Customer.io or Iterable without interpretation

2. COMPLETE EMAIL COPY LIBRARY: Full subject line, preview text, body copy, and CTA text for every email in the sequence — written for your specific product and ICP, not generic placeholders

3. BRANCH SCENARIOS: How the sequence handles customers who (a) skip milestones, (b) regress (usage drops after habit formation), (c) expand faster than expected, (d) go silent after any milestone

4. GAINSIGHT / CHURNZERO INTEGRATION SPEC: Which emails should generate CS platform alerts, what those alerts should say, and when the system should escalate from automated email to human CSM intervention

5. A/B TEST ROADMAP: The 5 most impactful tests to run once the base system is live — with test construct, metric, sample size required, and expected lift

6. 90-DAY PERFORMANCE FORECAST: What the expected sequence performance looks like by milestone — open rates, click rates, milestone conversion rates — with the methodology for proving that this email program (not time or other factors) drove adoption improvement

## Example Input/Output

**Example Company: Vertis (AI Financial Close Automation)**

**Input provided:**
- Company: Vertis — AI-powered month-end close automation for mid-market accounting teams
- Product: Connects to ERP (NetSuite, Intacct, QuickBooks Online) → auto-categorizes transactions → flags anomalies → generates board-ready close reports in hours instead of days
- ICP: Controllers and CFOs at manufacturing and distribution companies, $50M–$500M revenue, 5-20 person finance teams
- Business model: Annual SaaS — Starter ($9,600/yr, 3 users), Growth ($36,000/yr, 12 users), Enterprise ($84,000+)
- GTM motion: AE-closed, CSM-led post-sale, 1 CSM per 65 accounts
- Email platform: Customer.io (behavioral), HubSpot (marketing)
- Product analytics: Amplitude events → Customer.io via Segment CDP

**Activation Event defined as:** `close_cycle_completed` (ERP connected + first automated close cycle run to completion)
**First Value Event defined as:** `board_report_downloaded` (close report exported or sent to stakeholder)
**Habit Event defined as:** `close_cycle_completed` fires for second consecutive month without CSM-logged meeting preceding it
**Power User Event defined as:** `custom_template_saved` fired 2+ times AND `anomaly_alert_configured` fired

---

**Sample output — Email B1 (Post-Activation, fires within 15 minutes of close_cycle_completed):**

*Subject: Your February close is done — here's what Vertis found*
*Preview text: First automated cycle complete. Your board report is generating now.*

*Body:*

Hi [First Name],

Your February close just ran — automatically.

Here's what happened in the last [X minutes]:
- **[N] transactions** categorized and reconciled
- **[X] anomalies flagged** for your review (see the Anomaly Feed)
- Your **board close report** is generating now — it'll be ready in your dashboard in approximately [time estimate]

Your report will include:
→ P&L summary with variance explanations
→ Balance sheet reconciliation status
→ Open items requiring Controller sign-off before close

**[Open your close report →]**

One more thing: the 3 teams on your plan who close fastest all do one thing in their first month — they share the AI-generated report with their CFO or board before month-end. It changes the conversation from "how close are we?" to "here's what we found." If you want to share it externally, just click the share icon at the top of the report.

Talk soon,
[CSM Name]
Customer Success, Vertis

---

**Sample Trigger Logic Entry (Customer.io implementation-ready):**

CAMPAIGN: B3 — Report Not Downloaded Rescue
TRIGGER: Event "board_report_generated" fires AND 24 hours elapse
ENTRY CONDITION: "board_report_downloaded" event has NOT fired in the 24-hour window
SUPPRESSION: Suppress if contact has fired "board_report_downloaded" at any point since campaign entry
SUPPRESSION: Suppress if contact has been sent 2 emails in the last 7 days (global frequency cap)
SEND TIME: Immediately upon qualifying (not batched)
GOAL EVENT (exits campaign): "board_report_downloaded" fires
TIMEOUT GOAL: 5 days — if no download, do not resend; instead flag contact in HubSpot as "First Value Stall" custom property = TRUE, which triggers Gainsight webhook to create CSM CTA

---

**Outcome simulation (based on comparable deployment at a 180-account SaaS company):**

| Milestone | Pre-system baseline (date-based nurture) | Post-system (event-triggered) | Improvement |
|-----------|----------------------------------------|-------------------------------|-------------|
| Activation within 7 days | 61% | 78% | +17 pts |
| First value within 14 days of activation | 44% | 67% | +23 pts |
| Habit formation by day 75 | 38% | 57% | +19 pts |
| 3+ users active by day 30 | 29% | 41% | +12 pts |
| 90-day retention rate | 82% | 91% | +9 pts |

## Success Metrics

**Week 1-2 (system validation):**
- Email A1 (activation checklist) open rate: target ≥52% — if below, subject line and sender name need testing
- Activation rate within 7 days for new cohort: compare to prior 60-day baseline — target +12 percentage points
- B1 (post-activation celebration) click-through rate: target ≥38% — the deep link to first output should be irresistible

**Month 1 (milestone conversion):**
- % of activated customers reaching First Value within 14 days: target ≥65% (baseline: benchmark your current rate before launching)
- Rescue email C3 send rate (habit stall): this number should DECREASE month-over-month as the pre-habit emails do their job — if it's rising, your Milestone 3 pre-emails are failing
- Email frequency cap violations (contacts hitting the 2/week governor): should be <5% of contacts — if higher, your trigger logic is over-firing

**Quarter 1 (business impact):**
- 90-day retention for the first cohort to go through the system: measure against matched cohort from prior quarter
- Net Revenue Retention impact: track expansion events (seat additions, tier upgrades) sourced from D1/D2/E1 emails — these are marketing-sourced expansion pipeline
- CSM escalations resolved by email vs. requiring human call: target — email rescue campaigns should deflect 40%+ of routine activation and first value escalations, freeing CSM capacity for higher-value conversations

**PMM reporting metric:**
- "Adoption Milestone Lift" — for each milestone, report: (baseline %) → (post-system %) → (delta) attributed to marketing email program. This is your PMM contribution to NRR.

## Related Prompts

- [AI-Powered B2B SaaS New Customer Product Activation Sprint & First Value Moment Marketing](AI-Powered-B2B-SaaS-New-Customer-Product-Activation-Sprint-&-First-Value-Moment-Marketing-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Feature Adoption Campaign Architecture & Product-Led Retention](AI-Powered-B2B-SaaS-Feature-Adoption-Campaign-Architecture-&-Product-Led-Retention-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Dormant User Re-Engagement & Usage Recovery Marketing](AI-Powered-B2B-SaaS-Dormant-User-Re-Engagement-&-Usage-Recovery-Marketing-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Customer Marketing Expansion Revenue Campaign Architecture](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Customer-Marketing-Expansion-Revenue-Campaign-Architecture-&-Cross-Sell-Upsell-Pipeline-Intelligence-Engine.md)

## Integration Tips

**Customer.io:**
- Use Customer.io's "Event-Triggered Campaigns" as the backbone — each email maps to a trigger event or an event ABSENCE condition (e.g., `activation_event NOT fired within 5 days of account_created`)
- Use Customer.io's "Goals" feature to auto-exit contacts from campaigns when they hit the target milestone — this prevents celebrating an already-achieved milestone and avoids the "why are you telling me to do something I already did?" experience
- Build a master "Adoption Lifecycle" series with Campaign Groups so contacts can be in multiple milestone campaigns simultaneously (a contact can be both receiving the first-value rescue AND the team expansion nudge)

**Gainsight / ChurnZero:**
- Set up a bidirectional sync: Customer.io writes "Last Behavioral Email Sent" and "Current Adoption Milestone" back to the Account object in Gainsight/ChurnZero so CSMs can see the customer's email journey without switching tools
- Use Gainsight's Timeline feature to auto-log every rescue email (C3, A3) as a Timeline event: "System sent habit stall rescue email on [date] — CSM follow-up recommended if no product event in 48 hours"
- Build a Gainsight Report: "Accounts in Rescue Campaign > 5 Days" — weekly digest to CS leadership so manual intervention can be triaged

**Segment CDP:**
- Pipe Amplitude (or Mixpanel/Heap/PostHog) product events into Customer.io via Segment to ensure near-real-time event availability (target: <5 minute event latency for milestone-celebration emails — a 15-minute lag on "you just completed your first close" kills the moment)
- Use Segment Personas to maintain an "Adoption Milestone" trait on each user, synced to both Customer.io AND HubSpot — so sales reps can see adoption status in HubSpot and CSMs see it in Gainsight without duplicate tracking logic

**HubSpot:**
- Create a custom property on the Contact object: "Current Adoption Milestone" (Enum: Not Activated / Activated / First Value / Habituated / Power User / Expansion)
- Create a custom property: "Days Since Last Milestone" — this is the signal for AEs to identify expansion-ready accounts (contacts who reached "Power User" milestone 30+ days ago but haven't had an upgrade conversation)
- HubSpot Workflow: When "Current Adoption Milestone" = "Power User" for 30+ days → create AE Task: "[Account] reached Power User status 30 days ago — expansion conversation recommended"

**Slack (internal alerts):**
- #adoption-rescue channel: automated weekly digest — "This week: [N] accounts entered A3 (activation stall), [N] entered C3 (habit stall). CSMs tagged below."
- Format: 🟡 ACTIVATION STALL | [Account] | [CSM] @handle | Account created: [date] | No activation in [N] days | [Link to Gainsight account page]
- #adoption-wins channel: automated post when any account reaches Power User milestone — "🏆 [Account] just hit Power User status! [CSM] — expansion conversation opportunity." (Builds team culture around adoption wins, not just churn risk)

## Troubleshooting

**Problem: Events are firing but emails are sending hours later — the "you just completed your first close" email arrives the next morning, killing the celebratory effect**
Solution: Near-real-time event delivery is the most common implementation failure. Check your Segment pipeline latency first — if Amplitude events are batched hourly to Customer.io, switch to real-time event streaming. Customer.io processes events within seconds once received; the delay is almost always upstream. If real-time streaming is not immediately achievable, set the activation celebration (B1) to fire with a 0-minute delay from the event — even a 2-hour gap is far better than 12 hours. As an interim measure, use Customer.io's "Send at next available time" setting with a 9am–6pm send window so the email arrives during the workday rather than 2am.

**Problem: The rescue campaigns (A3, C3) are sending at high rates — far more accounts are entering rescue than expected**
Solution: This means your milestone conversion rates at earlier stages are lower than expected — which is actually valuable diagnostic data, not a failure. First, audit each milestone definition: is your "Activation Event" actually achievable in the intended timeframe, or is there a setup friction point (a broken integration, a confusing first-time configuration, a missing piece of the onboarding checklist) that's blocking activation? Use your product analytics (Amplitude/Mixpanel) to identify WHERE in the activation funnel customers are dropping — the email rescue is a symptom; the product friction is the root cause. Second, temporarily suppress the rescue emails while you fix the underlying issue — sending 5-day rescue emails to 60% of your accounts is both a deliverability risk and a signal to customers that something is broken.

**Problem: CSMs are complaining that the automated emails are "conflicting" with their personal outreach — contacts receive a rescue email the same day a CSM sends a custom note**
Solution: Implement a mandatory CSM-sync suppression rule. The system should check whether a CSM has logged any activity (call, email, meeting) in the CS platform within the last 7 days before sending any rescue campaign email. Gainsight and ChurnZero both support webhook-based suppression via Customer.io or Iterable. This requires a bidirectional sync: CS platform activity → Customer.io contact attribute update → Customer.io suppression condition. Set this up in the first sprint. Additionally, create a #no-email-override Slack command that CSMs can use to pause automated emails for specific accounts for 14 days — this gives CSMs control without requiring them to navigate the email platform.

## Version History
- v1.0: Initial creation (auto-generated)
