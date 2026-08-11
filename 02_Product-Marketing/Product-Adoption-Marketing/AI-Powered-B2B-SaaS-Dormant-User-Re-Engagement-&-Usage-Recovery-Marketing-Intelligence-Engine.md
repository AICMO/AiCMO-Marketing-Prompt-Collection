# AI-Powered B2B SaaS Dormant User Re-Engagement & Usage Recovery Marketing Intelligence Engine - Recover Disengaged Users Before They Become Churned Accounts

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** product adoption, dormant users, re-engagement, churn prevention, customer marketing, product-led retention, NRR, seat utilization, B2B SaaS, user lifecycle

## Overview
Builds a fully automated, AI-driven system that identifies dormant users inside active paying accounts, diagnoses why each user stopped engaging, and orchestrates personalized multi-channel re-engagement campaigns to recover usage before disengagement escalates to seat removal, downsell, or account churn. Use this when seat utilization in active accounts is below 60%, when renewal conversations are undermined by "nobody's using it," or when you want to turn product usage data into a proactive retention marketing motion — not a reactive CS fire drill.

## Quick Copy-Paste Version

You are a Product Marketing expert specializing in user re-engagement and usage recovery marketing for B2B SaaS companies. Design a complete dormant user re-engagement system that identifies users who have stopped engaging with the product inside active paying accounts, determines why they disengaged, and deploys targeted multi-channel campaigns to bring them back — before their inactivity becomes a reason to cut seats, downsize, or churn.

COMPANY CONTEXT:
- Company: [e.g., "Veltrix — AI-powered project management platform for mid-market professional services and consulting firms"]
- Product overview: [e.g., "Core product = project planning, time tracking, resource management, client reporting. 3 primary user roles: Project Managers, Consultants/ICs, Finance/Billing Admins"]
- Dormancy definition: [e.g., "Users with 0 login events in the last 30 days who had at least 3 sessions in the 30 days prior"]
- Current seat utilization rate: [e.g., "58% of licensed seats have had at least 1 login in the last 30 days"]
- Target seat utilization: [e.g., "80%+ across all Enterprise accounts"]
- Account structure: [e.g., "280 Enterprise accounts, average 34 licensed seats/account, 40% have 3+ user roles"]
- Tech stack: [e.g., "HubSpot CRM, Gainsight, Customer.io email, Pendo in-app, Slack for internal CS alerts"]

THREE DORMANCY PATTERNS TO SOLVE:
1. LAPSED ONBOARDER — Never fully activated; logged in 1-3 times early, then stopped
2. WORKFLOW DROPOUT — Was an active user, disengaged after a workflow change, role change, or project milestone
3. PASSIVE LICENSE — Account admin added them to the license but they never engaged meaningfully

OUTPUT REQUIRED:
1. DORMANCY SEGMENTATION MODEL: How to classify dormant users by type, recency, and business risk (account health × seat count × renewal proximity)
2. DIAGNOSIS PLAYBOOK: How to determine which dormancy type each user represents using behavioral signals — without asking them to fill out a form
3. CHANNEL PLAYBOOK: Which re-engagement touchpoints to deploy per dormancy type (email, in-app, Slack/Teams notification, CSM-prompted manager outreach)
4. CAMPAIGN COPY: Full message templates for each dormancy type and channel, personalized to user role
5. MANAGER ACTIVATION STRATEGY: How to engage the account's admin/manager to drive team-level usage recovery — not just individual user campaigns
6. MEASUREMENT FRAMEWORK: Seat utilization recovery rate, re-engagement attribution, and correlation between seat utilization and renewal outcomes

## Advanced Customizable Version

ROLE: You are a senior Product Marketing Manager with 13+ years driving user adoption, seat utilization, and product-led retention at B2B SaaS companies from Series B through enterprise scale. You have built dormant user re-engagement systems that lifted seat utilization from 52% to 78% across enterprise accounts in a single quarter — preventing $2.8M in at-risk ARR from being downgraded. You understand a critical distinction that most PMMs miss: account-level churn starts as USER-level disengagement, and by the time a renewal conversation surfaces "we're only using 8 of 40 seats," the window for easy recovery has often closed. You think in user cohorts, disengagement signals, and persona-specific re-activation hooks — and you know that the best re-engagement message isn't "come back" — it's "here's the specific value you've been leaving on the table."

OBJECTIVE: Design a production-ready dormant user re-engagement system that:
- Identifies every dormant user across every active account using product usage event data
- Classifies dormancy type (Lapsed Onboarder, Workflow Dropout, Passive License) to deploy the right re-activation intervention — not a one-size-fits-all "we miss you" email
- Deploys persona-matched, role-specific re-engagement campaigns that connect product value to the specific job the user was hired to do
- Activates account admins and managers as re-engagement levers — because a nudge from a manager is 4x more likely to drive login than a vendor email
- Measures seat utilization recovery rate by campaign type, account tier, and user persona, and correlates utilization lift with renewal outcomes to prove Marketing's contribution to NRR
- Runs autonomously as a continuous system, not a one-time campaign, so every new dormant user triggers the right intervention within 7 days of crossing the dormancy threshold

---

COMPANY PROFILE:
- Company name & product: [name + one-sentence description of the product's core value]
- Business model: [seat-based / usage-based / hybrid — include tier breakdown]
- Current ARR: [range — e.g., "$22M–$60M ARR"]
- Stage: [Series B / C / growth stage]
- GTM motion: [Enterprise AE + CSM / Mid-market self-serve with CS overlay / PLG with sales assist]
- Net Revenue Retention target: [current NRR vs. target — e.g., "current 104%, target 115%"]
- Average contract value: [e.g., "$36,000/year"]
- Average seats per Enterprise account: [e.g., "42 licensed seats"]
- Seat utilization floor for downgrade risk: [e.g., "Accounts using <50% of seats for 2+ consecutive quarters are 3x more likely to downsize at renewal"]
- Renewal cycle: [quarterly / annual / multi-year]

---

USER PERSONA PROFILES:
Define 2-4 user personas who hold licensed seats in your product. For each:
- Persona name & title: [e.g., "The Practitioner — Project Manager / Consultant IC"]
- Primary job-to-be-done: [e.g., "Deliver client work on time and on budget without drowning in admin"]
- Core product workflows they should be in 3x/week: [e.g., "Task management, time logging, client status updates"]
- Dormancy signal that matters most for this persona: [e.g., "No time entries logged in 14 days during an active project cycle"]
- Re-engagement hook that works for this persona: [e.g., "Concrete time saved — '6 minutes per day' beats 'streamline your workflow'"]
- What they typically say when they've drifted: [e.g., "'It's easier to just track time in a spreadsheet for now'"]

---

DORMANCY SEGMENTATION MODEL:

Classify every licensed user into one of four states:

STATE 1 — ACTIVE (baseline reference, no campaign):
Definition: ≥1 login event in the last 14 days AND completed a core workflow action (not just a login ping)
Goal: Maintain engagement; enroll in power user development track when usage depth threshold is met

STATE 2 — DRIFTING (early intervention window):
Definition: 0 core workflow actions in the last 7-14 days, but at least 1 action in the prior 30 days
Risk: Low individually, but accounts where >20% of users are Drifting have 2x the renewal downgrade rate
Campaign priority: Lightweight in-app and behavioral email nudge — low friction, high relevance
Goal: Trigger one meaningful product action within 7 days before they cross into Dormant

STATE 3 — DORMANT (primary re-engagement target):
Definition: 0 login events in the last 30 days; had ≥3 sessions in the 30 days prior to dormancy start
Sub-classification by dormancy TYPE (see Diagnosis Playbook below)
Campaign priority: Full multi-channel re-engagement sequence — email, in-app return prompt, manager activation
Goal: Return to Active state within 45 days of dormancy trigger

STATE 4 — ABANDONED (triage and account risk escalation):
Definition: 0 login events in the last 60+ days; never completed a core workflow action at any point
Risk: High — likely a Passive License user; if account has >30% Abandoned seats, flag for CSM-led seat audit before renewal
Campaign priority: Single re-engagement attempt; if no response, flag to CSM for seat reclamation or admin notification
Goal: Either trigger first meaningful activation OR remove from campaign and escalate to CS

---

DORMANCY TYPE DIAGNOSIS PLAYBOOK:

Classify Dormant (State 3) users into one of three types using behavioral signal logic — no survey required:

DORMANCY TYPE 1 — LAPSED ONBOARDER:
Behavioral signature:
- Total lifetime sessions: ≤5
- Completed onboarding checklist: ≤30%
- Never triggered a "core workflow completion" event (e.g., never submitted a time entry, never published a project milestone)
- Time since first login: >21 days

Root cause: Failed onboarding. The product didn't deliver a clear "first value moment" before the user ran out of motivation to figure it out.

Re-engagement approach: Don't ask them to "pick up where they left off" — there's no momentum to resume. Instead, reframe as a 10-minute restart that delivers one concrete, immediate outcome. Remove setup friction entirely: pre-configure a template, pre-populate a sample project, offer a guided activation session.

DORMANCY TYPE 2 — WORKFLOW DROPOUT:
Behavioral signature:
- Total lifetime sessions: ≥6
- Had consistent usage for ≥30 days
- Engagement cliff visible in usage data: sessions/week dropped from 4+ to 0 over a 2-3 week window
- Optional enrichment signals: recent CRM role/title change, account org chart update, project completion milestone around dropout date

Root cause: Life event interrupted their usage pattern. Role change, project transition, team restructuring, or a friction point they hit and didn't overcome. Unlike a Lapsed Onboarder, this user HAD a workflow — they lost it.

Re-engagement approach: Acknowledge the gap with specificity ("You were active on [Project Type] workflows — here's what's changed that makes it even easier now") rather than starting from zero. Focus on reconnecting them to the specific workflow they had built. If role/title signals suggest a job change, reposition the product for their new context.

DORMANCY TYPE 3 — PASSIVE LICENSE:
Behavioral signature:
- Total lifetime sessions: ≤2
- First login was >60 days ago
- No core workflow completion events at any point
- Account admin added them to the license during a bulk seat assignment (signal: added same day as 5+ other users)

Root cause: The user was added to the license as part of a top-down rollout but was never personally motivated or trained. The admin assumed the vendor would handle adoption.

Re-engagement approach: The right first move is NOT to email this user again — they've already ignored multiple onboarding emails. Activate the account admin instead. Surface the utilization gap data to the admin/manager and give them a tool to restart the user — a manager-forwarded invite, a team "getting started" session, or a seat audit recommendation.

---

CHANNEL PLAYBOOK BY DORMANCY TYPE:

LAPSED ONBOARDER re-engagement → CHANNEL MIX:

Email (primary — user-direct):
- Send from CSM or onboarding specialist (not a no-reply marketing address)
- Subject formula: "[First Name], your [product name] setup is 80% done — takes 10 minutes to finish"
- Angle: Reduce perceived effort — "we've set up a [role-specific] template so you don't start from scratch"
- CTA: One link to a pre-configured starting point, not to the homepage

In-app (return prompt on next login):
- If user logs in after dormancy: trigger an onboarding resume modal — "Welcome back. Here's where you left off — [specific incomplete step]. This takes 10 minutes."
- Do NOT show the full onboarding checklist — only the one next action that unlocks first value

Manager/admin activation (secondary — if no response to email in 7 days):
- Alert the account admin: "[X] users on your account haven't completed setup — here's a link to send them a team invite to a 30-minute getting started session"
- Provide the admin with a one-click "nudge your team" email pre-written and ready to send from their address

WORKFLOW DROPOUT re-engagement → CHANNEL MIX:

Email (primary):
- Send from the user's named CSM, not marketing automation (even if automated — use CSM's email address and signature)
- Subject formula: "We noticed you haven't been in [product] in a few weeks — [specific hook tied to their last active workflow]"
- Body: Reference their last known usage context ("The last project you were tracking was [Project Type]...") — personalization at the workflow level, not just the name level
- Include a "what's new" hook: one feature or improvement that directly addresses a pain point common to their user persona and role
- CTA: "Resume [specific workflow] → " with a deep link into the product (not the dashboard — directly to the feature they were using)

Slack / Microsoft Teams (if integrated):
- If the company uses your product's Slack or Teams integration, send a direct message via the bot: "Hey [First Name] — you've got [X] pending items in [Product Name]. [Deeplink: See them now]"
- Teams with Slack/Teams integrations see 40-60% higher re-engagement rates from in-channel nudges vs. email

In-app (return prompt):
- If user logs in: personalized "Welcome back" modal — "You were last working on [workflow/project type]. [Button: Pick up where you left off]"

Paid retargeting (optional, for accounts >$50K ACV):
- Serve LinkedIn ads to the specific user's job title/company with role-specific messaging ("For [Title] at [Industry] companies: [Product Name] now does [specific improvement relevant to their role]")

PASSIVE LICENSE re-engagement → CHANNEL MIX:

Do NOT lead with a user-direct email for Passive License users. They have a near-zero response rate because they were never personally invested in the product.

Manager/admin activation (primary):
- Alert the account admin via in-app notification AND email: "Seat utilization report for your [Product Name] account: [X] of [Y] licensed users have never logged in. Here's what you can do:"
- Provide three clear options: (1) Schedule a team onboarding session (calendar link), (2) Reassign unused seats to active team members, (3) Deactivate unused seats before your renewal date to right-size your contract
- Frame it as admin empowerment, not vendor complaint — "You're paying for [X] seats. Here's how to make sure your team is getting value from all of them."

User-direct email (secondary — only after admin activation attempt):
- Subject: "[Colleague Name] invited you to get started on [Product Name]" (even if the admin didn't personally send it — the proxy sender creates urgency)
- Keep it under 80 words. One CTA. Pre-built starting template waiting for them.

CSM escalation (tertiary — for accounts where >35% of seats are Abandoned):
- CSM receives Gainsight CTA: "Seat utilization risk — [Account Name] has [X] Abandoned users. Renewal in [Y] days. Recommended action: proactive seat audit conversation."
- CSM agenda template: "I wanted to review your team's usage data before your renewal — I have a report showing which seats are active vs. unused. Let's make sure you're getting full value, or right-size if some roles have changed."

---

RE-ENGAGEMENT CAMPAIGN COPY TEMPLATES:

LAPSED ONBOARDER — Email Touch 1, Day 7 of dormancy:

Subject: [First Name], your [Product] setup is 80% done — here's the missing piece

"Hi [First Name],

I noticed you signed into [Product] a few weeks ago but haven't been back. That's actually really common — the first few sessions can feel like you're doing more setup than actual work.

So we've done most of it for you.

I've set up a [role-specific template — e.g., "consulting project tracker"] for a team your size. It takes about 10 minutes to add your real projects and start getting value.

→ [Button: Open your pre-built template]

If you'd rather have someone walk you through it, I have 20-minute slots this week: [Calendar link]

[Signature: Onboarding Specialist / CSM Name]"

---

WORKFLOW DROPOUT — Email Touch 1, Day 10 of dormancy:

Subject: You haven't been in [Product] for a while — [specific hook]

"Hi [First Name],

Quick note — it looks like you haven't logged into [Product] in about [X] weeks.

Last time you were active, you were [using time tracking for client projects / managing [Project Type] workflows / etc.]. A few things have changed since then that I think you'll actually find useful:

→ [Specific new feature or improvement relevant to their workflow and role — e.g., "We added one-click time entry from Slack — no more switching windows mid-work"]

If the reason you stepped back was [common friction point for their persona — e.g., "time tracking felt too manual"], this directly fixes that.

[Button: See the update → ] or [Button: Pick up where you left off →]

And if something else got in the way, I'd genuinely like to know. Just reply to this email.

[Signature: CSM Name, direct email]"

---

PASSIVE LICENSE — Admin Notification Email:

Subject: Seat utilization report for [Company Name]'s [Product] account

"Hi [Admin First Name],

I wanted to share your team's usage data for [Product]:

✅ Active users (logged in last 30 days): [X] of [Y] licensed seats ([Z]%)
⚠️ Users who've never logged in: [N] seats

Before your renewal on [Date], I wanted to make sure you have options:

1. Schedule a 30-minute team onboarding session — I'll run it, you just invite your team: [Calendar link]
2. See which specific users are inactive: [Link to utilization report in-app or PDF export]
3. Talk to us about right-sizing your license if some roles have changed: [Link: Schedule a review call]

Most teams that do a quick utilization review 60+ days before renewal are able to either activate their unused seats or reallocate budget to where it creates more value.

[Signature: CSM Name]"

---

MANAGER RE-ACTIVATION SCRIPT (for CSM-led calls with account admins of high-ACV accounts):

Opening (30 seconds):
"I wanted to connect before your renewal because I pulled your team's usage data and I'm seeing something worth discussing — about [X%] of your licensed seats haven't logged in, in the last 30+ days. I want to help you either get those users activated or make sure you're only paying for what's being used."

If admin is surprised by the data:
"That's actually really common after a tool rollout — especially if it was a top-down decision where individual users weren't personally involved in choosing the product. The fix isn't hard, but it takes a few intentional steps. Can I walk you through what's worked for other teams your size?"

If admin knows about the usage gap:
"Good that you're aware. Can you tell me more about why those users haven't engaged? That helps me give you the right recommendation — it could be a training session, a workflow template, or honestly, a seat right-size if some roles genuinely don't need the tool."

Closing ask:
"Here's what I'd suggest: let's schedule a 30-minute team session I'll run where I show [specific user group] exactly how [Product] fits into their day-to-day. You send the calendar invite — your name, not ours — and the attendance rate will be much higher. Can we put that on the calendar before [date 3 weeks out]?"

---

MEASUREMENT FRAMEWORK:

Leading indicators (measure weekly):
- # of Drifting users who returned to Active before crossing Dormant threshold (early intervention success rate)
- # of Dormant users re-engaged per campaign type per week (Lapsed Onboarder vs. Dropout vs. Passive License)
- Email reply rate on CSM-sent re-engagement emails (target: >8% — higher than average because personalization increases replies)
- Admin activation rate: % of admins who took action (scheduled session, viewed utilization report, or sent team nudge) after receiving seat utilization alert

Seat utilization metrics (measure monthly):
- Account-level seat utilization rate: % of licensed seats with ≥1 core workflow event in last 30 days — measure across all accounts and by tier
- Utilization recovery rate: % of Dormant users who returned to Active within 45 days of re-engagement campaign start
- Re-engagement source attribution: which campaign type (Lapsed Onboarder email, Dropout CSM outreach, Admin activation) is driving the most recoveries?
- Manager activation conversion: % of admin seat utilization alerts that result in a scheduled team session or measurable utilization lift within 30 days

Revenue impact metrics (measure quarterly):
- Downgrade prevention: $ ARR retained in accounts where seat utilization was below downgrade-risk threshold and recovered before renewal
- Renewal rate: accounts with ≥75% seat utilization vs. <50% — target ≥18 percentage point renewal rate gap
- NRR delta: do accounts with utilization recovery programs show higher NRR in the following 2 quarters?
- Churn early signal accuracy: % of churned accounts that had >35% Abandoned seats in the quarter before churn — use to calibrate Abandoned user escalation thresholds

---

AUTOMATION ARCHITECTURE:

Gainsight / ChurnZero / Totango:
- Sync product event data: Push "last login date," "last core workflow action date," "lifetime session count," and "dormancy state" (Active / Drifting / Dormant / Abandoned) as custom fields to every User record in your CS platform
- CTA logic: When any account crosses 35% Dormant seats → auto-create a "Seat Utilization Risk" CTA for the assigned CSM, with priority based on renewal proximity and ACV
- Journey: For Drifting users → auto-enroll in a lightweight 3-touch email nudge sequence (without CSM involvement) — resolve the easy ones before they require human attention
- Scorecard: Add "Seat Utilization Score" (% active seats) as a health score component — accounts below 60% utilization should score ≤40 on this metric, which pulls their overall health score into yellow or red

Customer.io / Iterable / Braze:
- Trigger-based campaigns using product event data via CDP (Segment, RudderStack) or direct API:
  → Dormancy trigger: When user crosses 30-day threshold with no login → enter Dormancy Type diagnosis branch
  → Type-specific sequence: Route to Lapsed Onboarder, Workflow Dropout, or Passive License sequence based on behavioral classification logic
  → Exit condition: When user logs in AND completes a core workflow action → exit campaign, log re-engagement event, suppress from further dormancy outreach for 14 days
- Dynamic content: Use user role/persona field to serve role-specific copy in every email — a Project Manager and a Finance Admin receive different body copy, different CTAs, and different product value framing even within the same campaign sequence

Pendo / Appcues / WalkMe:
- Return prompt: When a Dormant user logs in, trigger role-appropriate "Welcome back" modal — suppress standard dashboard and surface the one highest-priority action for their persona
- Lapsed Onboarder guided flow: Pre-built 3-step interactive walkthrough that fires automatically on return — gets them to first value moment in the session without requiring them to remember where they were

Salesforce / HubSpot (for AE and CS coordination):
- Custom object: "User Engagement Record" — tracks dormancy state, campaign enrollment, re-engagement date, re-engagement source, and pre/post utilization for each licensed user
- Account rollup: Aggregate user-level dormancy data to the Account object: "Dormant User Count," "Dormant Seat %," "Seat Utilization Score," "Utilization Risk Flag" (yes/no)
- AE alert: When "Utilization Risk Flag" is set on an account with renewal <120 days away → notify AE via Salesforce task: "[Account] seat utilization at [X%] — potential downsize risk at renewal. CSM notified. Consider executive sponsor outreach."

Slack (for internal CS/Marketing coordination):
- #seat-utilization-alerts channel: Daily automated digest showing accounts that crossed dormancy risk thresholds in the last 24 hours — "3 new accounts entered Seat Utilization Risk status today: [Account A] (renewal Feb 20, 61% dormant), [Account B]..."
- Weekly recovery report: "This week's re-engagement wins: 14 dormant users recovered across 8 accounts. [CSM Name] led 4 recoveries via direct outreach. Automated email recovered 10."

---

OUTPUT STRUCTURE REQUIRED:

1. DORMANCY AUDIT: Pull product usage data to populate all four states across every licensed seat — organized by account tier, CSM book of business, and renewal timeline — with counts and account-level risk flags for immediate action

2. CAMPAIGN SEQUENCE CALENDAR: Full trigger logic and message sequence for each Dormancy Type — specifying the day offset from dormancy trigger, channel, sender identity, message angle, and exit/success criteria

3. FULL COPY LIBRARY: All email touches (subject + body), in-app return prompts (modal copy + CTA), and admin notifications — organized by Dormancy Type and user persona (role-specific variants for each message)

4. MANAGER ACTIVATION PLAYBOOK: Seat utilization report template (what to show admins), the three options/CTAs to present, and CSM talk track for high-ACV accounts with severe utilization gaps

5. MEASUREMENT DASHBOARD SPEC: Metrics, source of truth for each, reporting frequency, and how to present "dormant user re-engagement ROI" at monthly NRR review — including the seat utilization vs. renewal rate correlation analysis

6. ESCALATION PROTOCOL: Decision tree for when a Dormant user or account moves from Marketing campaign territory into CS-led intervention — including the specific account signals (seat %, ACV, renewal proximity) that trigger each escalation level

## Example Input/Output

**Example Company: Veltrix (AI-Powered Project Management for Professional Services)**

**Input provided:**
- Company: Veltrix — project planning, time tracking, resource management, and client reporting for mid-market consulting and professional services firms
- Dormancy definition: 0 login events in last 30 days; had ≥3 sessions in prior 30 days
- Current seat utilization: 54% (151 of 280 accounts below 70% utilization threshold)
- Account structure: 280 Enterprise accounts, average 38 licensed seats, 3 primary personas (Project Manager, Consultant/IC, Finance/Billing Admin)
- Stack: HubSpot CRM, Gainsight, Customer.io, Pendo, Slack integration active in 60% of accounts
- Renewal timing: 74 accounts renew in next 90 days; 31 of those are below 60% utilization

**Dormancy audit output (sample):**

| Dormancy State | Count (users) | Count (accounts affected) | Renewal risk accounts |
|---|---|---|---|
| Active | 5,840 (54%) | — | — |
| Drifting | 1,920 (18%) | 187 accounts | 44 renewing <90 days |
| Dormant — Lapsed Onboarder | 1,240 (12%) | 203 accounts | 28 renewing <90 days |
| Dormant — Workflow Dropout | 890 (8%) | 156 accounts | 19 renewing <90 days |
| Abandoned (Passive License) | 930 (8%) | 171 accounts | 51 accounts flagged for CSM seat audit |

**Sample automated campaign output — Workflow Dropout, Day 10 email:**

*Sent from: marcus.reyes@veltrix.com (CSM name, automated via Customer.io)*
*To: Jennifer Park, Senior Consultant, Halcyon Group*
*Subject: You haven't been in Veltrix for a few weeks — one thing that changed*

"Hi Jennifer,

Quick note — it looks like you haven't logged into Veltrix in about 3 weeks.

Last time you were active, you were logging time against the Calloway Manufacturing engagement. I'm guessing things got hectic at a project close, or the workflow felt like one more thing to juggle.

We just shipped something I think you'll actually find useful: you can now log time directly from Slack with a one-line command (/log 2h Calloway quarterly review). No tab switching. No remembering to enter it at end of day.

→ [Try it now: See the Slack time entry guide]

If something else got in the way, I'd genuinely like to hear it — just reply to this email.

Marcus Reyes
Customer Success, Veltrix"

*Re-engagement outcome (simulated based on comparable deployments):*
- Jennifer opens the email Day 11. Clicks the Slack guide link.
- Logs first Slack time entry Day 12.
- Returns to 4+ sessions/week by Day 20.
- At renewal (Day 64): account utilization at 71%, up from 52%. Contract renewed at full seat count.

**Sample admin notification — Passive License account (Meridian Consulting Group):**

*Sent from: Gainsight → email to Account Admin (CFO/Operations Director)*

"Hi David,

Here's your Veltrix seat utilization summary for Meridian Consulting Group:

✅ Active users (last 30 days): 9 of 24 licensed seats (38%)
⚠️ Users who have never completed a time entry or project update: 11 seats
ℹ️ Users who've partially set up but haven't logged in since initial week: 4 seats

Before your renewal on March 14th, here are your options:

1. [Schedule a 30-minute team onboarding session — I'll run it →] Pick a time that works for your Consultants
2. [View the full utilization breakdown →] See exactly which team members are active vs. inactive
3. [Book a renewal review call →] If some roles have changed, let's right-size before the invoice date

Teams that close this utilization gap before renewal see an average of 22% higher adoption by end of Q1.

Marcus Reyes | Customer Success, Veltrix"

*Outcome: David schedules team session (Day 4). 7 new users complete first time entry in the session. Utilization goes from 38% to 67% within 3 weeks. Renewal secured at full seat count.*

## Success Metrics

**Month 1 (system launch validation):**
- Dormancy audit complete: all licensed users classified into State 1-4 with Dormancy Type for State 3 users
- Drifting intervention: 35%+ of Drifting users return to Active before crossing Dormant threshold (early intervention win)
- Campaign deployment: Lapsed Onboarder and Workflow Dropout sequences live and triggering for all new Dormant users within 7 days of dormancy threshold
- Admin notifications: 80%+ of accounts with >35% Abandoned seats received admin seat utilization alert

**Month 2 (re-engagement acceleration):**
- Dormant user recovery rate: 30%+ of Dormant (State 3) users return to Active state within 45 days of campaign trigger
- Lapsed Onboarder recovery: 25%+ complete first core workflow action after email Touch 1 or Touch 2
- Workflow Dropout recovery: 40%+ return to consistent usage (≥2 sessions/week) within 30 days of CSM-sent email
- Admin activation rate: 45%+ of admins who received utilization alert took at least one action (booked session, viewed report, replied)

**Month 3 (business impact):**
- Accounts above 70% seat utilization: increase from [baseline] to [target] — measure across all accounts and specifically for the 74 accounts renewing in 90 days
- Renewal rate for accounts that crossed utilization recovery threshold (≥70%) before renewal vs. those that didn't: target ≥20 percentage point gap
- $ ARR downgrade risk mitigated: sum of ACV for Dormant-risk accounts that recovered before renewal — report as "Marketing-sourced retention"
- NPS/CSAT correlation: do accounts with higher seat utilization score higher on satisfaction? Use as qualitative evidence alongside quantitative retention data

## Related Prompts

- [AI-Powered B2B SaaS Feature Adoption Campaign Architecture & Product-Led Retention Intelligence Engine](./AI-Powered-B2B-SaaS-Feature-Adoption-Campaign-Architecture-&-Product-Led-Retention-Intelligence-Engine.md)
- [AI-Powered B2B SaaS New Customer Product Activation Sprint & First Value Moment Marketing Intelligence Engine](./AI-Powered-B2B-SaaS-New-Customer-Product-Activation-Sprint-&-First-Value-Moment-Marketing-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Churned Customer Win-Back Program Architecture & Revenue Recovery Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Churned-Customer-Win-Back-Program-Architecture-&-Revenue-Recovery-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Renewal Marketing Program Architecture & At-Risk Account Churn Prevention Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Renewal-Marketing-Program-Architecture-&-At-Risk-Account-Churn-Prevention-Revenue-Intelligence-Engine.md)

## Integration Tips

**Gainsight:**
- Build a "Seat Utilization" Scorecard metric that automatically updates from product event data synced via your data warehouse — a score of 0-100 where 100 = 100% of seats Active. Set health thresholds: <50 = Red, 50-74 = Yellow, ≥75 = Green. This pulls seat utilization into every CSM's daily health dashboard without requiring manual reporting.
- Use Gainsight Journey Orchestration to handle Drifting and Passive License outreach autonomously — route only Workflow Dropouts and Segment A accounts (high ACV + high dormancy + renewal <90 days) to CSM-created CTAs. Let automation handle the volume; humans handle the revenue-critical accounts.
- Gainsight's "People" module — track individual user health alongside account health. Build a custom view that shows each CSM their accounts ranked by "% dormant users" so re-engagement is visible in the same workflow they use for renewal management, not a separate report they have to remember to pull.

**Customer.io / Iterable:**
- Build separate campaign journeys for each Dormancy Type — do not consolidate them into one "re-engagement" campaign. The subject line, sender, angle, and CTA are fundamentally different for a Lapsed Onboarder vs. a Workflow Dropout, and a single campaign template will underperform both.
- Use Customer.io's Liquid templating to insert the user's last known product context dynamically — last project name, last workflow type, last login date expressed as "X weeks ago" — this level of personalization consistently doubles click-through rates compared to first-name-only personalization.
- Set hard suppression rules: if a user re-engages (core workflow action logged) within a campaign sequence, exit them immediately and suppress from all dormancy campaigns for 21 days. Nothing destroys re-engagement trust faster than receiving a "we miss you" email after you've already come back.

**Pendo / Appcues:**
- Use Pendo's Paths analysis to map what active users do in their first 10 minutes of a session vs. what Lapsed Onboarders did in their last session before going dormant — the gap between those paths reveals exactly where the activation friction is. Fix the product path before optimizing the re-engagement campaign.
- Build a "Welcome Back" Guide specifically for returning dormant users — segment by Dormancy Type using Pendo's user properties, and serve different modal content to a Lapsed Onboarder (guided restart) vs. a Workflow Dropout (resume prompt with "what's new" highlight). One returning-user modal that serves everyone will underperform both audiences.

**HubSpot (for mid-market companies):**
- Create a custom Contact property "Dormancy State" that syncs from your product event data via Segment CDP or HubSpot's native API — update it in real time as users cross thresholds. Build an Active List for each state and use HubSpot Workflows to enroll users into the correct campaign sequence based on state changes.
- Build a HubSpot Dashboard for Marketing + CS leadership: "Seat Utilization Health" — showing % of licensed contacts in each state across all accounts, trend over time, and top 10 accounts by dormant seat count. Make this the opening slide at monthly NRR review to prove Marketing's contribution to retention.

**Slack / Microsoft Teams (if your product has an integration):**
- If your product integrates with Slack or Teams, in-channel nudges from your product bot have dramatically higher open and action rates than email for Workflow Dropout users — because they receive the nudge inside the tool they ARE using instead of interrupting a different workflow. Prioritize building a "dormancy re-engagement" bot message for Workflow Dropouts before over-investing in email sequence optimization for this segment.
- For admin activation, send the seat utilization alert as a Slack DM to the account admin if they're connected — admins respond to Slack messages 3-4x faster than emails, and the speed of admin response is the single biggest driver of Passive License re-engagement outcomes.

## Troubleshooting

**Problem: Product usage data is incomplete or delayed — can't reliably classify all users into Dormancy Types**
Solution: Start with account-level utilization data (% of seats with any login in 30 days) rather than individual user behavioral classification — this is almost always available from basic product analytics. Use it to identify Dormant-risk accounts, then have CSMs manually ask the admin "which users on your team haven't engaged?" as part of the next check-in. As you invest in better event data piping (via Segment CDP or direct warehouse sync), replace the manual step with automated classification. A system running on 70% data quality is dramatically better than waiting for perfect data — just be honest with stakeholders about the classification confidence level.

**Problem: Re-engagement emails are going to the right user but response rates are low — the "it's been a while" angle isn't working**
Solution: Shift from generic re-engagement language to high-specificity product context. Instead of "we miss you," use the user's actual last-known workflow as the subject hook ("The [Project Type] tracker you set up..."). If you don't have workflow-level personalization in your email platform yet, segment by user persona (Job Title field) and serve role-specific copy that speaks to their day-to-day pain — a Project Manager and a Finance Admin have completely different reasons to care about re-engaging. Generic personalization (first name + company name) performs 30-50% below persona-matched content for re-engagement campaigns because dormant users have already filtered out your generic outreach.

**Problem: CSMs are getting the utilization alerts but aren't acting on them — the re-engagement system is running but human-touch accounts aren't being worked**
Solution: This is a prioritization and incentive problem, not a process problem. Three fixes: (1) Add "Seat Utilization Rate in Book of Business" to CSM quarterly scorecards — it won't get done if it isn't measured. (2) Reduce the action required: the Gainsight CTA should include a one-click "Send admin notification" button that fires the pre-written admin email from the CSM's address — the path of least resistance should be the right action. (3) Make the business case visible: at the next CS team meeting, show one concrete example of a re-engagement win (account where utilization recovery prevented a downsize) with the $ ARR saved — CSMs act on social proof from their peers faster than process mandates.

## Version History
- v1.0: Initial creation (auto-generated)
