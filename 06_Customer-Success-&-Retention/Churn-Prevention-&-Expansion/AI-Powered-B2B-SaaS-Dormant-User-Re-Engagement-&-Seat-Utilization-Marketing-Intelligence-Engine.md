# AI-Powered B2B SaaS Dormant User Re-Engagement & Seat Utilization Marketing Intelligence Engine - Rescue Underused Licenses, Protect Renewal Revenue, and Convert Seat Recovery Into Expansion

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** dormant-users, seat-utilization, re-engagement, churn-prevention, customer-marketing, lifecycle-marketing, b2b-saas, product-led-growth, expansion-revenue, nrr

## Overview
Designs and operationalizes a full marketing-led program to identify, re-engage, and activate dormant users within active paying accounts — protecting renewal revenue, improving product utilization scores, and converting recovered seats into upsell and expansion opportunities. Use this when renewal conversations are threatened by low seat utilization, CSMs are manually chasing inactive users, or your product analytics reveal that 20%+ of licensed seats haven't logged in for 30+ days.

## Quick Copy-Paste Version

You are an expert B2B SaaS customer marketing strategist specializing in product adoption and dormant user re-engagement programs.

I need to design a marketing-led dormant user re-engagement program for my SaaS company. Here's my context:

**Company:**
- Product: [What it does — one sentence focused on the business outcome]
- License model: [e.g., per-seat, per-user, concurrent licenses, named users]
- Total active accounts: [e.g., 280 accounts]
- Average seats per account: [e.g., 18 seats per account, $2,200/seat/year]
- Current seat utilization rate: [e.g., 62% — meaning 38% of licensed seats are dormant]

**Dormancy Definition:**
- Dormant threshold: [e.g., no login in 45+ days]
- Number of dormant users today: [e.g., ~1,950 dormant seats across 210 accounts]
- Estimated ARR at risk from low utilization: [e.g., $2.1M in renewals where utilization is below 50%]

**Known Dormancy Reasons (if available):**
- [e.g., onboarding failure — never completed setup]
- [e.g., role change — moved to a different team]
- [e.g., workflow not fitting daily job]
- [e.g., feature gap — waiting for a specific capability]
- [e.g., competing internal tool being used instead]

**Current Tech Stack:**
- Product analytics: [e.g., Mixpanel, Amplitude, Heap, or in-app events in Salesforce]
- CRM: [e.g., Salesforce, HubSpot]
- CS platform: [e.g., Gainsight, ChurnZero, Totango, or none]
- Email/automation: [e.g., Marketo, HubSpot, Customer.io, Intercom]
- In-app messaging: [e.g., Intercom, Pendo, Appcues, or none]

Build a 60-day dormant user re-engagement program that includes:

1. **DORMANCY SEGMENTATION MODEL** — Classify dormant users into 4-5 cohorts based on dormancy cause (use login patterns, onboarding completion data, support ticket history, and role/title to infer likely reason). Define the audience query for each cohort and the re-engagement hypothesis.

2. **MULTI-CHANNEL RE-ENGAGEMENT SEQUENCES** — For each dormant cohort: a specific 5-touch sequence using email, in-app, and (where warranted) direct outreach. Include exact message angle, CTA, and timing for each touch. Messages must NOT feel like "we noticed you haven't logged in" guilt trips — they must lead with value and new reasons to return.

3. **VALUE TRIGGER CONTENT PLAN** — 6 content assets that give dormant users a compelling reason to return (e.g., new feature they haven't seen, a benchmark showing peer usage patterns, a quick-win use case they haven't tried). Define format, angle, and which dormant cohort each asset targets.

4. **ACCOUNT-LEVEL ESCALATION PLAYBOOK** — Rules for when a dormant user pattern should escalate to CSM or AE for intervention (e.g., "if 60%+ of seats in an account are dormant within 90 days of renewal, trigger CSM alert and pause automated marketing").

5. **RECOVERY-TO-EXPANSION CONVERSION PLAY** — Once a dormant user is reactivated, design a follow-on sequence that converts the momentum into expansion: additional seat recommendation, feature upgrade, or referral ask.

6. **SUCCESS METRICS DASHBOARD** — Define the 6 KPIs that prove this program works (re-engagement rate by cohort, days-to-first-login post-campaign, account utilization score improvement, renewal rate for treated vs. untreated accounts, expansion attributed to reactivated users).

Output should be specific enough for a customer marketing manager to execute without additional guidance from CS or product teams.

## Advanced Customizable Version

### ROLE
You are a Senior Customer Marketing Architect with 15+ years building post-sale marketing programs at B2B SaaS companies ranging from $15M to $500M ARR. You specialize in product-led retention strategies and have designed dormant user re-engagement programs that have recovered an average of 31% of dormant seats and increased renewal rates by 8-14 percentage points for treated accounts. Your methodology draws on Lincoln Murphy's Customer Success expansion frameworks, Samuel Hulick's user onboarding psychology (users adopt products when they can see themselves succeeding), and Nir Eyal's Hook Model for habit formation. You think in cohorts, A/B test ruthlessly, and attribute everything to pipeline and revenue impact.

---

### CONTEXT

**Company Profile:**
- Company name: [Your company]
- Product description: [One sentence — specific outcome delivered, not feature list]
- Industry / primary verticals served: [e.g., Financial Services, Healthcare IT, HR Tech]
- ARR: [Current ARR]
- Customer count: [Total accounts]
- Average ACV: [e.g., $42K/year]
- License model: [Per-seat / Per-user / Consumption-based / Named user / Concurrent]
- Price per seat or unit: [e.g., $1,800/seat/year]

**Seat Utilization Baseline:**
- Total licensed seats across all accounts: [e.g., 8,400 seats]
- Current overall utilization rate: [e.g., 58%]
- Dormant seat definition: [e.g., zero product sessions in last 30 / 45 / 60 days]
- Total dormant seats today: [e.g., 3,528 dormant seats]
- Accounts with utilization below 50%: [e.g., 94 accounts]
- ARR tied to accounts with utilization below 50%: [e.g., $3.9M]
- Upcoming renewals (next 90 days) where utilization is a risk factor: [e.g., 31 accounts, $1.2M ARR]

**Dormancy Root Cause Data (fill what you know):**
- % of dormant users who never completed onboarding: [e.g., 34%]
- % of dormant users with a known role change (title changed in LinkedIn/SFDC): [e.g., 18%]
- % of dormant users who submitted a support ticket and went dark after: [e.g., 22%]
- % of dormant users with no clear signal (cold): [e.g., 26%]
- Are there known competing internal tools? [e.g., yes — legacy Excel workflows, Notion, homegrown tool]

**Product & Feature Context:**
- Core daily-use features (habits that drive retention): [e.g., dashboard reporting, automated alerts, workflow triggers]
- Recently released features dormant users haven't seen: [e.g., AI summarization launched 6 weeks ago, new mobile app]
- Features most correlated with high utilization (from product analytics): [e.g., users who complete the "team setup" step have 3x higher 90-day retention]
- Self-serve capabilities: [e.g., users can complete onboarding themselves / requires admin setup / requires CSM]

**Current Marketing & CS Capabilities:**
- Does marketing have access to product usage data? [Yes / No / Partial — describe]
- In-app messaging tool: [Pendo / Appcues / Intercom / Chameleon / None]
- Email automation platform: [Marketo / HubSpot / Customer.io / Intercom / Braze / Other]
- CS platform: [Gainsight / ChurnZero / Totango / Planhat / None]
- Can marketing trigger automated emails based on product events? [Yes / No / Requires engineering]
- Existing customer marketing programs: [e.g., quarterly newsletter, NPS follow-up, renewal campaign]
- Marketing team size dedicated to customer/post-sale: [e.g., 1 customer marketing manager, no dedicated headcount]

**Renewal & Expansion Context:**
- Average renewal timeline: [e.g., CSM starts renewal conversation 90 days before contract end]
- Who owns renewal: [AE / CSM / Shared]
- Who owns upsell/expansion: [AE / CSM / Marketing / Self-serve]
- Typical upsell levers: [e.g., seat additions, tier upgrades, add-on modules, usage tier bumps]
- Average upsell deal size: [e.g., $11K incremental ACV]

---

### OBJECTIVE
Design a full marketing-led Dormant User Re-Engagement Program that:
1. Identifies and segments all dormant users by inferred root cause
2. Deploys targeted multi-channel re-engagement sequences per cohort
3. Escalates renewal-risk accounts to CSM/AE at the right threshold
4. Converts reactivated users into expansion pipeline
5. Demonstrates measurable improvement in utilization scores and renewal rates

---

### CONSTRAINTS
- Marketing must be able to execute this with minimal CS involvement (CS should only be pulled in at escalation thresholds, not for every dormant user)
- Re-engagement messages must NOT feel punitive, guilt-inducing, or surveillance-based — every touchpoint must lead with new value, peer benchmarks, or a genuine "win" the user is missing out on
- All campaign logic must be automatable via the existing MarTech stack (no manual triggers except at escalation)
- Attribution must be built in from day one: tag all re-engagement touches in CRM so marketing can claim credit for renewals and expansions influenced by the program
- Avoid creating a "fake urgency" playbook — if the product hasn't delivered value, no campaign will fix that; include a decision branch for users who should be re-onboarded vs. users who need a CSM escalation

---

### REQUIRED OUTPUT — PRODUCE ALL 8 SECTIONS IN FULL

**SECTION 1: DORMANCY SEGMENTATION MODEL**
Create 5 dormant user cohorts. For each cohort:
- Cohort name and hypothesis (why they went dormant)
- Data signals used to identify them (login data, onboarding steps, support history, role/title, time-to-dormancy)
- Estimated % of total dormant population
- Re-engagement strategy hypothesis (what message angle will work)
- Re-engagement confidence level (High / Medium / Low) and rationale
- CRM/MAP query logic to build the audience segment

**SECTION 2: MULTI-CHANNEL RE-ENGAGEMENT SEQUENCES**
For each of the 5 cohorts, design a 5-touch re-engagement sequence:
- Touch 1-5: channel (email / in-app / LinkedIn DM / direct CSM outreach), message angle, subject line (for email), CTA, timing from trigger
- Overall sequence duration (e.g., 21 days)
- Exit conditions: when does a user exit the sequence (re-engaged = logged in within X days; unresponsive = no action after touch 5)
- What happens at sequence exit (re-engaged path vs. escalation path)

**SECTION 3: VALUE-TRIGGER CONTENT ASSETS**
Design 8 specific content assets to power re-engagement:
For each asset:
- Asset type (email, in-app tooltip, short video, PDF one-pager, benchmark report snippet, feature spotlight)
- Title and hook
- Core message (one paragraph)
- Target dormant cohort(s)
- Distribution channel
- Production effort (Low / Medium / High)

**SECTION 4: ACCOUNT-LEVEL ESCALATION PLAYBOOK**
Define escalation rules for when marketing automation should hand off to human intervention:
- Escalation Tier 1 (Marketing automation): defines when a single dormant user warrants only automated outreach
- Escalation Tier 2 (CSM alert + marketing support): defines account-level thresholds that trigger a CSM notification (e.g., 3+ dormant users in same account; utilization drops below 40%)
- Escalation Tier 3 (AE + CSM joint play): defines renewal-risk scenarios requiring sales involvement (e.g., 60%+ of seats dormant within 90 days of renewal, >$50K ARR at risk)
- CSM enablement kit: what marketing provides to CSM when escalating (account utilization snapshot, dormant user list, re-engagement history, recommended talking points)
- SLA between marketing and CS: response time expectations, ownership handoff process

**SECTION 5: RECOVERY-TO-EXPANSION CONVERSION PLAY**
Once a dormant user logs back in within 14 days of a campaign touch, design the follow-on expansion sequence:
- Reactivation confirmation message (celebrating their return)
- 30-day habit formation sequence: 3 in-app prompts driving users to high-value features correlated with long-term retention
- Expansion trigger logic: if reactivated user hits usage milestones within 30 days, trigger an expansion offer (e.g., "You've been using [Feature X] heavily — teams that unlock [Add-On Y] see 40% faster results")
- Expansion offer design: what to offer, how to frame it, and who delivers it (marketing email vs. CSM call vs. self-serve upgrade)
- Attribution: how to tag this expansion opportunity as marketing-influenced

**SECTION 6: MEASUREMENT FRAMEWORK & SUCCESS METRICS**
Define the full measurement framework:
- Primary KPIs (6 metrics, with baseline, 30-day target, 60-day target)
- Secondary KPIs (4 operational metrics)
- A/B test plan: 2 specific tests to run in the first 30 days (e.g., subject line personalization vs. generic, video vs. text email for "Never Onboarded" cohort)
- Reporting cadence: weekly metrics for marketing team, monthly scorecard for CS leadership, quarterly QBR slide for CMO/VP CS
- How to calculate marketing attribution to renewals influenced by this program

**SECTION 7: 60-DAY PROGRAM LAUNCH PLAN**
Week-by-week execution plan:
- Week 1-2: Data audit, audience segmentation, tech stack configuration, content briefing
- Week 3-4: Content production, sequence build-out in MAP/CS tool, QA testing
- Week 5-6: Soft launch (Tier 1 re-engagement sequences only, with smallest cohort first)
- Week 7-8: Full program launch, A/B tests running, first escalation reviews with CS

**SECTION 8: MARTECH INTEGRATION SPECIFICATIONS**
Define the specific technical integrations needed to run this program:
- Data flow: how product usage data moves from product analytics to MAP/CRM (e.g., Mixpanel → Segment → HubSpot)
- Trigger logic: specific event or property that fires each sequence (e.g., `days_since_last_login >= 30 AND account_health_score < 70`)
- CRM tagging schema: campaign tags, contact fields, and opportunity influence tracking
- In-app vs. email coordination: how to avoid over-messaging users who are being re-engaged on both channels simultaneously
- CSM notification setup: how CS platform alerts are configured and what data they surface

---

### OUTPUT FORMAT
Structure the output as a complete program blueprint. Use headers, numbered lists, and tables where they improve clarity. Every section must be specific enough that a customer marketing manager can begin execution without scheduling a single additional meeting.

## Example Input/Output

**Input Example:**

Company: Solvara — a B2B SaaS workflow automation platform for operations teams at mid-market manufacturing companies ($30K-$90K ACV, per-seat licensing at $1,500/seat/year)

Context:
- 340 active accounts, 6,200 total licensed seats
- Current utilization: 54% (2,852 dormant seats, defined as no login in 45+ days)
- Accounts with utilization below 50%: 112 accounts ($4.1M ARR)
- Renewals at risk next 90 days: 28 accounts ($980K ARR), avg utilization 41%
- Known dormancy reasons: 38% never fully onboarded (setup stalled at step 3 of 7), 24% had a role change (manager-level users replaced by new hires), 19% submitted a support ticket about a workflow limitation and went dark, 19% unknown
- New feature released 8 weeks ago: AI-powered exception detection (dormant users haven't seen it)
- Tech stack: Mixpanel (product), Salesforce (CRM), Gainsight (CS), HubSpot (email/marketing), Pendo (in-app)
- Marketing can access Mixpanel data via Salesforce connector; HubSpot workflows can be triggered by Salesforce field changes
- 1 customer marketing manager owns post-sale marketing

**Output Example (Partial — Section 1: Dormancy Segmentation Model):**

---

**COHORT 1: The Stalled Onboarder (38% of dormant users — ~1,083 users)**

*Hypothesis:* These users licensed Solvara but stalled during setup — specifically at Step 3 of 7 (first workflow build). Without completing this step, they never experienced the core "aha moment" (seeing their first automated exception flagged). They didn't fail — they just got busy and never came back.

*Data signals:*
- Onboarding completion step in Mixpanel: `onboarding_step_completed <= 3`
- Login history: 1-3 sessions total, last session > 45 days ago
- Support ticket: none (they didn't hit a problem — they just didn't finish)
- Time to dormancy: typically within first 21 days of license provisioning

*CRM/HubSpot audience query:*
`Contact Property: onboarding_step_completed IS LESS THAN 4 AND days_since_last_login IS GREATER THAN 45 AND total_sessions IS LESS THAN 5 AND support_ticket_count EQUALS 0`

*Re-engagement hypothesis:* Remove the setup friction. Give them one thing to do in 5 minutes that gets them to Step 4. Lead with social proof: "Your peers who completed setup in week 1 processed 340 exceptions automatically in their first month."

*Re-engagement confidence:* HIGH — This cohort has high intent (they licensed and started). The barrier is inertia, not dissatisfaction.

---

**COHORT 2: The New Hire Orphan (24% of dormant users — ~684 users)**

*Hypothesis:* The original user who licensed Solvara changed roles or left, and their replacement (a new hire or promoted peer) inherited the seat but was never onboarded. These are "ghost licenses" — the seat is active but the human behind it doesn't know what Solvara is.

*Data signals:*
- LinkedIn title change detected within 60 days of dormancy onset (via Salesforce enrichment/Clay)
- OR: Contact title contains "new" or hire date in HRIS/Salesforce is more recent than last login
- Login history: 0 sessions in 60+ days
- Account-level signal: admin user is different from licensed user (if trackable)

*CRM/HubSpot audience query:*
`Contact Property: days_since_last_login IS GREATER THAN 60 AND (job_change_detected EQUALS TRUE OR days_since_contact_created IS LESS THAN 90) AND total_sessions EQUALS 0`

*Re-engagement hypothesis:* Treat these users as new users, not dormant users. Don't reference "we noticed you haven't logged in." Start with "Welcome to Solvara" framing. Pair with a 1:1 CSM or AE intro where account size warrants.

*Re-engagement confidence:* MEDIUM — High potential if we reach them, but we may have wrong contact info or they may not be empowered to use the tool without manager buy-in.

---

**[Section 2 excerpt — Cohort 1 Sequence: The Stalled Onboarder]**

**Touch 1 (Day 0 — Email):**
Subject: "The part of Solvara that saves [Company] teams 4 hours/week is 8 minutes away"
Angle: Specific, outcome-focused. Reference their industry (manufacturing ops) and the exact workflow they started building. CTA: "Finish Setup in 8 Minutes" → deep link to Step 4 of onboarding.

**Touch 2 (Day 5 — In-App via Pendo):**
Tooltip triggered on login: "Pick up where you left off → Build your first exception rule (takes 8 min)." Only fires if they log in. If no login by Day 7, proceed to Touch 3.

**Touch 3 (Day 8 — Email):**
Subject: "3 exceptions [Peer Company in their vertical] caught in week 1 with Solvara"
Angle: Peer benchmark social proof. Include a mini case study (2 paragraphs) from a similar manufacturing ops account. CTA: "See how they set it up."

**Touch 4 (Day 14 — Email):**
Subject: "Something new in Solvara you haven't seen yet"
Angle: New feature reveal — AI exception detection launched after they went dormant. "Your account is already configured to use it — log in to activate." CTA: "See AI Detection in Action" → product tour video (90 seconds).

**Touch 5 (Day 21 — Direct CSM Outreach, if account ACV > $25K):**
CSM sends personalized email or LinkedIn message referencing their specific workflow. Provides 15-minute offer to "finish setup together." For accounts below $25K: automated email from "Your Customer Success Team" with same offer in digital format.

*Exit condition (Re-engaged):* User logs in and completes Step 4 within 21 days → exits to Recovery-to-Expansion sequence.
*Exit condition (Unresponsive):* No login after Touch 5 → flag in Gainsight as "Re-engagement Attempt 1 Failed" → 30-day pause → Escalation Tier 2 review if renewal within 90 days.

---

**Metrics snapshot at Day 60 (projected for Solvara):**

| KPI | Baseline | Day 30 Target | Day 60 Target |
|---|---|---|---|
| Overall seat utilization rate | 54% | 59% | 65% |
| Dormant seat re-engagement rate | 0% | 18% | 31% |
| Accounts moved from <50% to >60% utilization | 0 | 22 | 44 |
| Renewal rate: treated accounts | 71% (historical) | — | 83% (projected) |
| Expansion pipeline from reactivated users | $0 | $85K | $220K |
| CSM escalation actions triggered | — | 18 accounts | 28 accounts |

## Success Metrics

- **Dormant user re-engagement rate**: % of targeted dormant users who log in within 21 days of first campaign touch. Target: 20-35% for high-confidence cohorts (Stalled Onboarders, New Hire Orphans); 8-15% for low-confidence cohorts (Unknown).
- **Account utilization score improvement**: Average utilization rate change for accounts in the program vs. a matched control group not receiving campaigns. Target: +10-15 percentage points within 60 days.
- **Renewal rate delta**: Compare renewal rate for accounts that received re-engagement campaigns vs. accounts that did not. Target: 8-12 percentage point improvement.
- **Escalation accuracy rate**: % of escalated accounts where CSM confirms the escalation was justified (utilization issue confirmed, renewal risk real). Target: >70%.
- **Recovery-to-expansion conversion rate**: % of reactivated users who generate an expansion opportunity within 90 days of reactivation. Target: 12-18%.
- **Marketing attribution to expansion ARR**: Expansion pipeline and closed ARR from accounts where marketing's re-engagement campaign was a touchpoint. Target: 15-25% of total expansion ARR influenced.

## Related Prompts

- [NRR Marketing Program Architecture & Expansion Revenue Campaign](./AI-Powered-B2B-SaaS-NRR-Marketing-Program-Architecture-&-Expansion-Revenue-Campaign-Intelligence-Engine.md)
- [Customer Lifecycle Marketing Orchestration & Milestone-Triggered Revenue Intelligence](../Customer-Success-Automation/AI-Powered-B2B-SaaS-Customer-Lifecycle-Marketing-Orchestration-&-Milestone-Triggered-Revenue-Intelligence-Engine.md)
- [Product Usage Signal & Expansion Revenue Trigger Intelligence](../Customer-Success-Automation/AI-Powered-B2B-Product-Usage-Signal-&-Expansion-Revenue-Trigger-Intelligence-Engine.md)
- [Marketing-Led Customer Onboarding Campaign & New Customer Revenue Continuity](../Customer-Onboarding-&-Activation/AI-Powered-B2B-Marketing-Led-Customer-Onboarding-Campaign-&-New-Customer-Revenue-Continuity-Intelligence-Engine.md)

## Integration Tips

- **Gainsight / ChurnZero / Totango**: Create a custom Success Plan type called "Re-engagement Program" that auto-populates when marketing flags an account for Tier 2/3 escalation. Sync utilization score and re-engagement campaign history to the CS timeline view so CSMs don't re-contact users already in an automated sequence.
- **HubSpot / Marketo**: Build a dedicated re-engagement enrollment list using product usage data synced from Mixpanel or Amplitude via Segment. Use smart lists with `days_since_last_login` as a rolling field so the audience auto-updates daily. Tag all enrolled contacts with `Campaign: Dormant_Reengagement_Q[X]` for attribution reporting.
- **Pendo / Appcues / Intercom (In-App)**: Suppress in-app messages for users who are already receiving email re-engagement on that same day (use a "do not disturb" tag synchronized between platforms). Coordinate in-app sequences for Day 5 touches only — not as a parallel channel that runs independently.
- **Salesforce**: Add a custom Contact field `Dormant_Reengagement_Status` with picklist values: `Identified | Sequence Active | Reengaged | Escalated | Failed`. Use this field for CSM notifications via Gainsight rules and for marketing attribution reporting in the Opportunity Influence model.
- **Segment / CDP**: If using a CDP, create a "Dormant User" audience trait that combines product usage data, login recency, and account health signals. Push this audience to HubSpot, Pendo, and Gainsight simultaneously to ensure all channels are synchronized on who is in-program.
- **LinkedIn Sales Navigator**: For Tier 3 escalations (enterprise accounts at renewal risk), AEs should use Sales Navigator to identify if the dormant contact is still at the company or has moved on — critical for the "New Hire Orphan" cohort where the original champion may have departed.

## Troubleshooting

**Problem: Re-engagement emails are getting very low open rates (<10%) and the dormant users aren't responding at all.**
Solution: Most re-engagement campaigns fail because they lead with "we noticed you haven't logged in" language that feels surveillance-based or guilt-inducing. Audit your subject lines: every subject line must promise a specific outcome or new piece of value, never reference login recency. A/B test a subject line that leads with a peer benchmark ("Companies like yours automated X hours/week in the first 30 days") vs. a new feature reveal. Also check deliverability: dormant users are more likely to have stale email addresses or inbox rules that send marketing into spam — consider a plain-text, from-a-person email for Touch 3 or 4 to bypass filters.

**Problem: CSMs are frustrated that marketing is re-engaging their accounts without them knowing, and customers are getting conflicting messages.**
Solution: This is a coordination failure, not a marketing failure. Implement a "Marketing Suppression List" that CSMs can add accounts to at any time, preventing automated sequences from firing on accounts the CSM is actively managing. Conversely, build a weekly Slack digest (or Gainsight email) that gives every CSM a list of their accounts currently in re-engagement sequences, with the specific sequence name and last touch date. Run a 30-minute enablement session for CS leadership to explain the program logic and escalation thresholds before launch.

**Problem: Dormant user re-engagement improves login rates briefly, but users go dormant again within 30 days — the program isn't creating lasting behavior change.**
Solution: A single login is not reactivation — habit formation is. If your re-engagement sequence gets a user to log in once but doesn't connect them to the core behavior loop (the "hook"), they'll churn again within weeks. Review your Recovery-to-Expansion sequence: are the in-app prompts guiding users to the specific feature most correlated with long-term retention? If not, work with product and CS to identify the 1-2 actions that predict 90-day retention (typically available in your product analytics cohort data), and rebuild your post-reactivation sequence to drive those specific actions within the first 7 days of return.

## Version History
- v1.0: Initial creation (auto-generated)
