# AI-Powered B2B SaaS Customer Milestone Marketing & Value Realization Celebration Program Architecture & Expansion Revenue Intelligence Engine - Systematic Conversion of Customer Success Moments Into Expansion Revenue and Net-New Pipeline

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, saas, customer-marketing, customer-success, expansion-revenue, lifecycle-marketing, milestone, advocacy, nrr, upsell, customer-led-growth, automation

## Overview
Designs a complete AI-orchestrated milestone marketing system that automatically detects when customers reach significant value realization moments — first meaningful outcome, power-user threshold, anniversary, ROI benchmark, team adoption surge — and deploys hyper-personalized celebration campaigns that simultaneously deepens loyalty, triggers expansion conversations, and converts satisfied customers into warm referral sources at peak enthusiasm. Use this when your CS platform or product analytics is capturing milestone data but your marketing team isn't systematically converting those moments into revenue-generating touchpoints.

## Quick Copy-Paste Version

You are a B2B SaaS customer marketing strategist specializing in milestone-triggered lifecycle programs. Design a complete customer milestone marketing system that detects value realization moments and converts them into expansion revenue and new logo referrals.

**Company context:**
- Product: [e.g., project management SaaS for engineering teams, revenue intelligence platform, field service management]
- ARR: [$X] | Stage: [Series A/B/C/Growth]
- Average ACV: [$X new logo] | Average expansion event: [$X]
- NRR target: [X%] | Current NRR: [X%]
- Customer base: [#] paying accounts | [#] total users
- CS platform: [Gainsight/ChurnZero/Totango/Planhat/None]
- Product analytics: [Mixpanel/Amplitude/Heap/Pendo/None]
- CRM: [Salesforce/HubSpot] | MAP: [Marketo/HubSpot/Pardot]

**Current state:**
- How milestones are celebrated today: [None / Manual CS outreach only / Automated in-app only / Partial]
- Expansion motion: [Sales-led / CS-led / Marketing-assisted / Product-led]
- Customer-sourced pipeline today: [$X or "not tracked"]
- CS-to-marketing handoff for milestone moments: [None / Ad hoc Slack / Automated]

Design:

1. **Milestone Taxonomy & Prioritization** — define the 8-10 highest-value customer milestones to track, organized by commercial significance (Tier 1: major outcomes, Tier 2: adoption surge, Tier 3: lifecycle anniversaries), how to detect each, and the expansion propensity associated with each

2. **Celebration Campaign Playbooks** — for each milestone tier, design the full campaign sequence: celebration email content and subject line variants, CS touchpoint brief, executive sponsor notification, LinkedIn shoutout template, and in-app acknowledgment — all deployable without human editing

3. **Milestone-to-Expansion Revenue Bridge** — the exact language and plays that convert celebration moments into expansion conversations without triggering "they're just selling me" resistance; include which milestones map to which expansion plays, time delays, and CS vs. marketing automation decision logic

4. **Referral Activation at Peak Satisfaction** — how to embed referral asks into milestone celebrations when customers are at their highest enthusiasm, including ask language using three persuasion frames (social proof, reciprocity, peer help), incentive structure, and tracking mechanism

5. **Executive Sponsor Re-Engagement** — milestone-triggered touchpoints that re-engage the economic buyer above the day-to-day user, creating expansion conversation anchors and advocacy asks at the right moments

6. **Integration Architecture** — the end-to-end webhook/API flow from product analytics → CS platform → CRM → MAP to automate milestone detection and campaign execution with suppression logic for at-risk accounts

Output the specific trigger conditions, exact campaign assets to create, automation rules, and success metrics for each component.

## Advanced Customizable Version

### Role & Context
You are a Senior Customer Marketing Manager at a B2B SaaS company tasked with building a systematic, AI-orchestrated program that turns every significant customer milestone into a revenue-generating moment. Your mandate is twofold: (1) use milestone celebrations to trigger expansion conversations at the exact moment when customers are most satisfied and most likely to say yes, and (2) convert milestone-moment satisfaction into warm referrals that generate net-new pipeline. You measure success by Expansion Revenue Influenced by Marketing (ERIM) and Customer-Sourced Pipeline (CSP) attributable to milestone-triggered programs.

**Company context:**
- Company: [Company Name]
- Product category: [e.g., Revenue Operations / DevOps Platform / CX Automation / HR Tech / Data Platform]
- ARR: [$X] | Stage: [Series B / C / Growth / Pre-IPO]
- Average ACV: [$X new logo] | Average expansion ACV per event: [$X]
- NRR target: [X%] | Current NRR: [X%]
- Customer base: [#] total accounts | Enterprise (>$X ACV): [#] | Mid-Market: [#] | SMB: [#]
- Average contract term: [Monthly / Annual / Multi-year]
- Users per account: [X at deal close] | [X at 90 days] | [X at 1 year]

**Customer success & product data infrastructure:**
- CS platform: [Gainsight / ChurnZero / Totango / Planhat / None]
  - Health score components tracked today: [list]
  - Milestone tracking today: [None / Manual CS notes / Automated with tool X]
- Product analytics: [Mixpanel / Amplitude / Heap / PostHog / Pendo / Custom]
  - Key product events tracked: [list 5-10 events]
  - Cohort analysis available: [Yes/No]
  - Real-time event streaming: [Yes / Near-real-time / Batch daily]
- CRM: [Salesforce / HubSpot]
- MAP: [Marketo / HubSpot / Pardot / Salesforce Marketing Cloud]
- CS-to-marketing handoff process today: [None / Ad hoc Slack / CRM task / Automated campaign trigger]

**Expansion revenue context:**
- Expansion motion today: [Sales-led only / CS-led / Partially marketing-assisted]
- Top 3 historical expansion triggers: [e.g., team headcount growth, new use case adoption, reaching usage cap]
- Average time from expansion trigger to close: [X days]
- Expansion ACV as % of new logo ACV: [X%]
- Seats or usage caps in current contracts: [Yes — describe structure / No]
- Marketing's current role in expansion: [None / Occasional ABM ads / Full program]

**Customer advocacy & referral context:**
- Customer referral program today: [None / Informal / Formal with incentive structure]
- Customer-sourced pipeline last 12 months: [$X / Not tracked]
- Average warm referral close rate: [X% / Unknown]
- G2/Capterra reviews: [# total] | Average rating: [X stars]

---

### Objective
Build a complete milestone marketing system architecture that:
1. Automatically detects the 10 commercially highest-value customer milestones using product + CS data
2. Deploys personalized multi-channel celebration campaigns that reinforce value delivered and deepens emotional commitment
3. Bridges celebration moments to expansion conversations without triggering "they're just trying to upsell me" resistance
4. Activates referral requests at peak satisfaction using proven persuasion frameworks
5. Re-engages executive sponsors at high-satisfaction milestone moments to create advocacy and expansion anchors
6. Measures milestone marketing's contribution to expansion ARR and new logo pipeline with CRM-level attribution

---

### Deliverables Required

**1. Milestone Taxonomy & Commercial Prioritization Matrix**

Design a complete milestone taxonomy organized into 4 tiers:

*Tier 1 — Outcome Milestones (Highest Commercial Value)*
Define 3-4 milestones that signal the customer has achieved a quantifiable business outcome. Examples: "First ROI benchmark hit," "Cost-per-unit reduction target reached," "100% team adoption achieved," "First enterprise-wide rollout completed."
For each:
- Exact detection method: product event combination + CS platform flag + CRM field
- Time-to-occur distribution: what % of customers hit this at 30/60/90/180 days post-close
- Expansion propensity score at this milestone vs. account baseline
- Advocacy readiness score: likelihood of positive response to reference/referral ask at this moment
- Risk of over-selling vs. appropriate expansion bridge

*Tier 2 — Adoption Surge Milestones (High Commercial Value)*
Define 4-5 milestones signaling expanding product adoption breadth or depth. Examples: "Power user threshold crossed (X active users/week)," "3rd distinct use case activated," "API integration gone live," "Manager-level user added," "50th [key action] completed."
For each:
- Detection trigger: specific product event with threshold
- CS intervention required: [Yes / No / Optional based on health score]
- Natural expansion play to attach at this milestone
- Whether economic buyer or end-user receives the celebration

*Tier 3 — Lifecycle Milestones (Moderate Commercial Value)*
Define 3-4 time-based or cumulative volume milestones. Examples: "Day 90 mark," "1-year anniversary," "1,000 actions processed," "5,000th data record synced."
- Automated vs. manual delivery requirement
- Celebration format appropriate for milestone scale (don't over-celebrate low-value moments)
- Whether to include expansion ask, referral ask, or neither

*Tier 4 — Onboarding Micro-Milestones (Engagement Value)*
Define 2-3 early activation signals during first 30 days. Examples: "First workflow created," "First report generated," "First team member invited."
- In-app celebration only vs. email required
- CS Slack alert: Yes/No
- No expansion or referral asks at this tier

**2. Celebration Campaign Playbooks (By Tier)**

For Tier 1 milestones, design the complete 5-touch campaign:

*Touch 1 — Immediate In-App Acknowledgment (0 hours):*
- In-app notification or banner copy (60 words max)
- Visual format: [Achievement badge / Animated confetti / Dashboard highlight]
- CTA: [View milestone summary / Share on LinkedIn / See your impact report]

*Touch 2 — Celebration Email (24-48 hours):*
- Subject line A/B variants (provide 3 options using curiosity, outcome, and social proof frames)
- Email body using the [Outcome-Story-Bridge] structure:
  - Outcome: Name the specific milestone and why it matters
  - Story: Put it in context (benchmark comparison, what it means for their team)
  - Bridge: Open a natural door to the next conversation (NOT a sales pitch)
- Personalization variables: list exact CRM/CS fields to pull
- Email signature: from CSM name, not "The [Company] Team"

*Touch 3 — CS Touchpoint (48-72 hours):*
- Slack alert template to CS team with: milestone name, account name, health score, current contract value, expansion propensity score, and 3-bullet recommended talk track
- Whether call is mandatory, recommended, or optional based on account tier and milestone tier
- Specific expansion opening the CSM should reference from the celebration email

*Touch 4 — Executive Sponsor Notification (Day 3):*
- Email template to economic buyer (not day-to-day user) using business outcome language
- Subject: business-metric framing, not product milestone framing
- Body: "Your team's investment is paying off" framing, 3 sentences, with a data point
- CTA: [Review your ROI dashboard / Schedule a quarterly check-in]

*Touch 5 — LinkedIn Company Celebration (Day 5, permission-based):*
- LinkedIn post template: customer-first narrative, specific outcome, tagged mention of customer champion
- How to get permission: embedded in Day 1 email ("Would you be open to us sharing this milestone publicly? Reply YES and we'll draft for your approval.")
- Amplification plan: ask customer champion to share or comment

For Tier 2: Simplify to Touch 2 (email) + Touch 3 (CS Slack only, no call required).
For Tier 3: Touch 2 (email) only, no CS involvement unless account health < 70.
For Tier 4: Touch 1 (in-app) only.

**3. Milestone-to-Expansion Revenue Bridge Architecture**

For each Tier 1 and Tier 2 milestone, define the specific expansion play:

*Expansion Play Structure:*
- Play name: [e.g., "Power User Surge → Seat Expansion Play"]
- Natural bridge language to embed in celebration email (provide exact copy): uses achievement language to make expanded usage the logical next step, not a sales move
- Expansion asset to link or attach: [Tier comparison one-pager / ROI calculator / Custom usage report / "What's next" guide]
- Automation vs. CS-led decision:
  - If health score > 80 AND time-in-contract > 90 days AND no open support tickets: marketing automation handles
  - If health score 60-80: CS leads with marketing asset support
  - If health score < 60: suppress expansion, route to CS retention play only
- Time delay between celebration send and expansion follow-up: [0 days embedded / 3 days / 7 days based on milestone tier]
- CRM task creation: what fires in Salesforce to create Opportunity or CS task

*Decision Tree:*
Milestone detected → Health score check → Contract term check → Expansion propensity score →
- High propensity (score > 75): MAP triggers celebration + expansion bridge email Day 7
- Medium propensity (score 50-75): MAP triggers celebration; CS receives Slack alert with expansion play; CS owns expansion outreach
- Low propensity (score < 50): MAP triggers celebration only; no expansion ask; CS receives retention alert

**4. Referral Activation Playbook at Peak Satisfaction**

*Which Milestones Trigger Referral Asks:*
- Tier 1 milestones: Yes — at highest satisfaction, highest likelihood to advocate
- Tier 2 milestones: Conditional — only if NPS > 8 or health score > 80
- Tier 3 milestones: No — anniversary is not a satisfaction signal; don't conflate
- Tier 4 milestones: Never — too early in relationship

*Three Referral Ask Frameworks (provide exact copy for each):*

Frame 1 — Social Proof Ask:
"P.S. — We see a lot of [industry] teams trying to solve the same problem your team just cracked. If you know a peer who's wrestling with [specific pain point], we'd love an introduction. We'll make it easy — just reply with their name and email and we'll take it from there. And if they become a customer, we'll add [incentive] to your account as a thank-you."

Frame 2 — Reciprocity Frame:
"One more thing: the reason [Company] is able to serve customers like you is because our best new customers come from referrals from customers like you. If there's someone in your network who could benefit from what you've just achieved, a quick intro would mean a lot to us — and we'd make it worth your while with [incentive]."

Frame 3 — Peer Help Frame:
"You've figured out something that a lot of [role]s are still struggling with. If you know someone dealing with [pain point], you'd be doing them a genuine favor by making an introduction. We'll take care of everything after that — you just need to say the word."

*Incentive Architecture:*
- Cash equivalent: $X credit applied to next invoice (specify amount = 15-20% of ACV, enough to be meaningful without cheapening)
- Recognition: Public acknowledgment in community, featured customer spotlight
- Time-bound: "For the next 30 days, any introduction that becomes a customer earns you [incentive]" — creates urgency without desperation

*Referral Tracking:*
- Customer submits via: [dedicated referral form / reply to email / in-product referral portal]
- CRM creation: New Lead created with Source = "Milestone Referral" + Milestone Type + Referring Account
- Pipeline attribution: Campaign Member record created; milestone-triggered referral flagged on Opportunity
- How to measure: Customer-Sourced Pipeline (CSP) report filtered by Source = "Milestone Referral"

**5. Executive Sponsor Re-Engagement Architecture**

Triggered by Tier 1 milestones only:

*Economic Buyer Notification Email:*
- When: Day 3 after Tier 1 milestone detected
- From: CSM or VP Customer Success (not marketing alias)
- Subject: "[Company] team just hit a major mark — wanted you to know"
- Body: 4 sentences max. Specific business metric achieved. Team recognition. One data point comparing to benchmark. Invitation to a brief call or QBR preview.

*QBR Preparation Trigger:*
- Milestone data auto-populates Gainsight Success Plan or CS platform template with: milestone date, outcome metric, benchmark comparison, recommended expansion play, customer quote/win from CS notes
- CS receives pre-populated QBR slide deck section 48 hours before next scheduled QBR date

*Advocacy Ask from Executive Sponsor:*
- Appropriate milestones: Only Tier 1, only accounts > [X] ACV, only after 2+ Tier 1 milestones achieved (indicating sustained success)
- Specific ask language for: (a) event speaking, (b) case study participation, (c) video testimonial
- Who makes the ask: CSM in a live conversation (never email), using the celebration as context
- Handoff to marketing: CSM Slack alert → Customer Marketing contact schedules production within 5 business days

**6. Technical Integration Architecture**

End-to-end automation flow:

Detection Layer:
[Product Analytics: Event threshold crossed]
    → [CS Platform: Milestone flag auto-created via webhook]
    → [CRM: Account field updated: Milestone_[Type]_Date = TODAY()]

Suppression Check:
[Health Score < 65 OR At-Risk flag OR Contract = Churned]
    → STOP: Route to CS alert only, no marketing campaign

Campaign Execution Layer:
[MAP Enrollment Trigger: Milestone field populated AND suppression check passed]
    → [Branch by Tier and Health Score]
    → [Email Send: Celebration campaign]
    → [CRM Task Created: CS touchpoint assigned]
    → [Slack Alert: CS team notification via webhook]
    → [CRM Campaign Member: Attribution record created]

Expansion Bridge Layer (Day 7):
[MAP Branch: Expansion propensity > 75]
    → [Email: Expansion asset delivery]
    → [CRM: Opportunity Stage = Expansion Identified OR CS Task = Expansion Conversation]

Referral Tracking Layer:
[Customer submits referral via form or email reply]
    → [Zapier/native: Lead created in CRM with Source = Milestone Referral]
    → [Campaign Member: Referral Lead associated with milestone campaign]
    → [Pipeline Report: CSP attribution tracked]

Specific technical requirements:
- Milestone de-duplication: Salesforce boolean field (e.g., `Milestone_500_Actions_Achieved__c = TRUE`) set on first detection; MAP enrollment condition requires field = FALSE to prevent repeat campaigns
- At-risk suppression: Mandatory enrollment condition = Account Health Score ≥ 65 AND CS Risk Flag ≠ At-Risk AND Contract Status = Active
- CS preview window: 24-hour delay between Slack alert and email send; CS can suppress or customize before automated send fires
- Data refresh cadence: Product analytics sync to CRM minimum every 4 hours for Tier 1 milestones; daily for Tier 2-4

**7. Measurement Framework**

*Program-Level KPIs (Monthly Dashboard):*
- Milestone detection rate: % of eligible accounts receiving campaigns within 72 hours of milestone (target: > 85%)
- Celebration email open rate by tier: Tier 1 target > 45%, Tier 2 > 35%, Tier 3 > 25%
- Expansion Revenue Influenced by Marketing (ERIM): $ expansion ARR where milestone campaign fired in prior 60 days
- Milestone-to-expansion time compression: Days from milestone detection to expansion close vs. non-milestone-touched accounts
- Customer-Sourced Pipeline (CSP) from milestone referral asks: tracked in CRM by Source
- CS touchpoint completion rate: % of milestone Slack alerts resulting in CS contact within 72 hours

*Milestone-Level Analytics (Quarterly Review):*
- Per-milestone expansion propensity: % of accounts expanding within 90 days of each specific milestone
- Per-milestone referral submission rate: % of milestone emails generating referral form submission
- Executive sponsor engagement rate: % of Tier 1 milestones resulting in executive sponsor email open + click
- LinkedIn shoutout permission rate: % of milestone emails where customer replies YES to public celebration

*Annual Business Impact Metric:*
- Incremental NRR contribution: Compare NRR cohort of milestone-marketed accounts vs. matched control group that did not receive milestone campaigns

## Example Input/Output

**Input Example:**
- Company: Velotrack (fictional B2B SaaS, field service management platform for HVAC and facilities companies)
- ARR: $8.2M | Stage: Series B
- ACV: $42,000 new logo | $18,000 average expansion per event
- Customer base: 194 accounts | 12,000 total users
- CS platform: Gainsight | Product analytics: Amplitude
- CRM: Salesforce | MAP: HubSpot
- Expansion motion: CS-led with no marketing involvement
- Customer-sourced pipeline: $0 tracked (word-of-mouth happens but untracked)
- Current milestone marketing: None — occasional manual emails from CSMs

**Output Example — Tier 1 Milestone: "First 500 Work Orders Completed":**

*Detection:*
- Amplitude event: `work_order_completed` cumulative count per `account_id` crosses 500
- Gainsight Rules Engine: fires on Amplitude cohort sync → creates Timeline Event "Milestone: 500 WO" → updates Account field
- Salesforce: `Milestone_500WO_Date__c` = TODAY(); triggers HubSpot workflow enrollment

*Celebration Email (48-hour delay, from CSM name):*
Subject A: "Velotrack milestone: 500 work orders completed — your team is in rare company"
Subject B: "The [Company Name] team hit a mark most customers take twice as long to reach"

Body:
"[First Name],

Your team just completed their 500th work order in Velotrack.

That's not a vanity number. The median Velotrack customer reaches 500 work orders at month 8.4 — your team got there in [X] months. That puts [Company Name] in the top quartile of Velotrack accounts by activation speed.

At this volume, our customers typically report [Outcome 1: X% reduction in scheduling errors] and [Outcome 2: Y hours/week saved on dispatch coordination]. We'd love to show you how [Company Name] compares against those benchmarks.

[Button: See Your Benchmark Report] → links to personalized Velotrack dashboard view

One more thing — would you be open to us sharing this milestone publicly? If yes, just reply YES and we'll draft a LinkedIn post for your approval before anything goes live.

Talk soon,
[CSM Name]"

*CS Slack Alert (fires simultaneously):*
"🎯 *Milestone Alert: 500 Work Orders* | Account: [Company Name] | Health: 84 | ACV: $42K | Propensity: HIGH
→ Send celebration email queued for 48h
→ **Recommended expansion play:** 7 days post-celebration, introduce Pro Dispatch tier ($12K/yr add-on) — they're at 85% of Basic tier capacity
→ Talk track: 'Your team's adoption velocity means you'll hit your usage ceiling in about 6 weeks — want to see what Pro Dispatch unlocks before that happens?'"

*Referral Ask (embedded in Day 3 follow-up email):*
"P.S. — Most of our best new customers come from facilities managers who know each other. If you know a peer running HVAC or facilities operations who's still managing work orders in spreadsheets, a quick intro would mean a lot to us — and we'd add two months of Velotrack free to your contract as a thank-you for any intro that becomes a customer."

## Success Metrics
- Milestone detection rate ≥ 85% of eligible accounts receive campaigns within 72 hours of milestone
- Celebration email open rate ≥ 40% (vs. ~22% typical marketing email benchmark for B2B SaaS)
- Expansion influence rate: ≥ 30% of Tier 1 milestone accounts expand within 90 days (vs. baseline rate for non-milestone-touched accounts)
- Referral submission rate: 5-8% of Tier 1 milestone emails generate a referral form submission
- Time-to-expansion compression: Target 15-20 fewer days from trigger to close vs. CS-only baseline
- Customer-Sourced Pipeline (CSP) attributed to milestone program: tracked and growing quarter-over-quarter in CRM
- NRR lift: Milestone-marketed account cohort shows ≥ 3 percentage point NRR improvement vs. matched control

## Related Prompts
- [Customer-Led Growth Program Architecture](./AI-Powered-B2B-SaaS-Customer-Led-Growth-Program-Architecture-&-Customer-Network-Pipeline-Revenue-Intelligence-Engine.md)
- [NPS Signal-Driven Customer Advocacy Activation](./AI-Powered-B2B-SaaS-NPS-Signal-Driven-Customer-Advocacy-Activation-&-Promoter-to-Pipeline-Revenue-Intelligence-Engine.md)
- [Product Usage Signal-Triggered Customer Marketing](./AI-Powered-B2B-SaaS-Product-Usage-Signal-Triggered-Customer-Marketing-Orchestration-&-Lifecycle-Revenue-Intelligence-Engine.md)
- [Customer Marketing Expansion Revenue Campaign Architecture](./AI-Powered-B2B-SaaS-Customer-Marketing-Expansion-Revenue-Campaign-Architecture-&-Cross-Sell-Upsell-Pipeline-Intelligence-Engine.md)

## Integration Tips
- **Gainsight:** Use Rules Engine to detect product event thresholds via Amplitude/Mixpanel cohort sync; create Timeline Events on milestone detection; configure CTAs to fire CS tasks; use Journey Orchestrator to trigger HubSpot enrollment via webhook
- **ChurnZero:** Use ChurnScore and Journey triggers to detect milestones; configure Journey Actions to push data to MAP; set up NPS auto-survey to fire 24 hours after Tier 1 milestone to capture satisfaction at peak moment
- **HubSpot:** Build each milestone as a separate Workflow with Enrollment Trigger = CRM property update; use Branches for health score routing; create custom properties for each milestone date; use Campaign attribution for CSP reporting
- **Salesforce:** Create custom Milestone Date fields on Account object (`Milestone_[Type]_Date__c`); build Flows to create CS Tasks and Campaign Members on field population; use Reports to generate ERIM and CSP dashboards
- **Amplitude:** Configure Computed Properties for cumulative milestone counts; use Amplitude Audiences to sync milestone-qualified accounts to Salesforce in real time; use Amplitude Notify for instant Slack alerts on threshold crossing
- **Pendo:** Use Guides to deliver in-app celebration moments with rich media; use NPS Guide triggered immediately on milestone completion; use Paths analytics to identify fastest routes to Tier 1 milestones for onboarding optimization

## Troubleshooting

**Problem:** Milestone campaigns fire for churned or at-risk accounts, creating tone-deaf celebration emails to customers who are unhappy or have already left.
**Solution:** Add mandatory suppression conditions at workflow entry: Customer Health Score ≥ 65 AND CS Risk Flag ≠ "At-Risk" AND CS Risk Flag ≠ "Red" AND Contract Status = "Active." Implement these as hard enrollment criteria, not email-level suppression, so no campaign is even queued for at-risk accounts. Separately, route at-risk accounts who reach milestones to a CS recovery alert instead.

**Problem:** CS team feels marketing is invading their customer relationships by sending emails without their knowledge, damaging carefully built trust.
**Solution:** Implement a mandatory 24-hour CS preview window. When a milestone fires, Gainsight/CS platform CTA alerts the CSM first. CSM has 24 hours to (a) approve and let automation proceed, (b) customize the email subject/opening line, or (c) suppress the automated send and handle personally. Default if no action within 24 hours: automation proceeds. This preserves CS ownership while maintaining scale.

**Problem:** Customers are receiving milestone celebrations repeatedly as usage fluctuates above and below a threshold (e.g., active user count dropping below threshold then recovering).
**Solution:** Implement a "milestone permanently achieved" boolean field in Salesforce (`Milestone_[Type]_Achieved__c = TRUE`) that is set on first detection and never reset. Make this field a mandatory negative condition for MAP enrollment ("only enroll if Milestone_[Type]_Achieved__c = FALSE"). Once achieved, the account is permanently suppressed from re-enrollment in that specific milestone campaign for the lifetime of the contract.

## Version History
- v1.0: Initial creation (auto-generated)
