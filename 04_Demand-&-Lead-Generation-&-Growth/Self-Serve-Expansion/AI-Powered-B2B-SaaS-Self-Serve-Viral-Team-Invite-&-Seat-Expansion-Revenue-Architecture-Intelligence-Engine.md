# AI-Powered B2B SaaS Self-Serve Viral Team Invite & Seat Expansion Revenue Architecture Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** PLG, viral-growth, seat-expansion, team-invite, network-effects, self-serve, B2B SaaS, product-led-growth

## Overview

Designs and deploys a fully autonomous viral team invite and seat expansion engine that turns every individual user into an internal distribution channel — systematically triggering collaboration invites, optimizing invite-to-accept rates, and converting team adoption into plan upgrades. Use this when your product has multi-user value potential but seat expansion is stalling below 2.5 seats per account or your invite-accept rate is below 55%.

## Quick Copy-Paste Version

You are a product-led growth architect specializing in B2B SaaS viral mechanics and seat expansion. Build a complete autonomous team invite and seat expansion system for the product described below.

PRODUCT: [Your SaaS product name and category]
CURRENT SEATS PER ACCOUNT (avg): [X]
INVITE-TO-ACCEPT RATE: [X%]
PLAN MODEL: [Per-seat / Per-team / Tiered by seats]
COLLABORATION TRIGGER: [The core action that requires or benefits from teammates, e.g., "sharing a report", "assigning a task", "requesting approval"]
CURRENT INVITE MECHANISM: [Email invite / Link sharing / Both / None]
PAID ACCOUNT THRESHOLD FOR TEAM FEATURES: [Free up to X seats / All plans]
CURRENT MONTHLY INVITES SENT: [X]

Deliver:

1. VIRAL INVITE MOMENT MAP — Identify the 5 highest-intent moments in your product where a user naturally needs or wants a teammate. For each moment: the triggering action, the friction that currently blocks an invite, and the optimal invite prompt design (copy + timing + dismiss logic).

2. INVITE FUNNEL AUDIT — Map the full invite funnel: Invite Sent → Email Delivered → Link Opened → Account Created → First Session Completed → Collaboration Event Triggered → Paid Seat Added. Benchmark each stage (industry medians provided) and flag your biggest leaks.

3. INVITEE ACTIVATION SEQUENCE — Write a 5-touch sequence for newly invited users (email + in-app) that drives them from invite acceptance to first collaborative action in under 48 hours.

4. SEAT EXPANSION TRIGGERS — Define 4 automated seat expansion triggers based on account behavior signals (team size, usage patterns, collaboration frequency). Include exact message copy and upgrade path for each.

5. VIRAL COEFFICIENT OPTIMIZATION PLAN — Calculate your current K-factor (invites sent per user × invite-accept rate) and provide 5 specific lever improvements to reach K > 0.3 within 90 days.

6. 30-DAY QUICK WIN EXPERIMENTS — List the top 3 A/B tests to run immediately on your invite flow, ranked by expected lift, with hypothesis and success metric.

Output as a structured implementation plan ready to deploy in your product analytics, in-app messaging, and email automation stack.

## Advanced Customizable Version

ROLE: You are a senior product-led growth architect with 15+ years engineering viral expansion systems for B2B SaaS companies. You have designed viral mechanics at companies like Figma, Loom, Notion, Airtable, and Miro. You combine network effects theory, behavioral economics, and quantitative funnel analysis to build self-sustaining seat expansion engines that operate without SDR intervention below $50K ACV thresholds.

CONTEXT:
- Company: [Company name]
- Product category: [e.g., project management, sales intelligence, contract management]
- Seat pricing model: [Per-seat ($X/seat/month) / Team tiers (1–5 seats: $Y, 6–20: $Z) / Usage-based with seat caps]
- Current avg seats per paid account: [X] vs. industry benchmark for your category [Y]
- Current invite-to-accept rate: [X%] (benchmark: 55–70% for B2B SaaS with strong team value props)
- Monthly unique inviters (users who send ≥1 invite): [X]
- Avg invites sent per inviting user per month: [X]
- Current K-factor (estimated): [X] (benchmark: 0.15–0.40 for healthy PLG)
- Top collaboration trigger: [The #1 action requiring a teammate]
- Current invite channels: [Email / Shareable link / Slack integration / None]
- Invitee conversion to paid seat: [X%]
- Time from invite sent to first collaborative session: [X hours]
- ICP account size: [SMB 1–50 / Mid-Market 51–500 / Enterprise 500+]
- Current in-app messaging stack: [Intercom / Appcues / Pendo / None]
- Email automation platform: [HubSpot / Customer.io / Marketo / Other]
- CRM: [Salesforce / HubSpot / Other]

OBJECTIVE: Build a fully autonomous viral team invite and seat expansion system. Every output must be ready to implement in [chosen stack] without further editing. All expansion nudges under $X ACV must operate without SDR intervention. Above $X ACV, flag for human follow-up.

CONSTRAINTS:
- Invite prompts must not appear more than twice per session
- Invitee onboarding sequence must be suppressed if invitee already has a paid account at your company
- Seat expansion nudges must suppress if account is in an active enterprise sales cycle (CRM flag: `opportunity_stage != null`)
- Comply with CAN-SPAM and GDPR: all invitee emails must include unsubscribe + invitation context ("You were invited by [inviter_name] at [company]")
- No cold outreach to invitees who haven't accepted within 14 days — allow passive expiry only

FRAMEWORKS TO APPLY:
- Network Effects Theory (Metcalfe's Law): Quantify the value inflection points where each additional user multiplies product value — these are your highest-leverage invite moments
- Behavioral Economics: Apply social proof ("Your teammates are already using X"), reciprocity (shared work creates obligation to contribute), and loss aversion ("Your colleague left you 3 comments — don't miss the conversation")
- AARRR × Viral Loop Extension: Model the viral loop as a second acquisition channel alongside paid/organic — track K-factor as a board-level metric
- Jobs-to-be-Done (JTBD): Segment inviters by their job (getting work done faster vs. managing a team vs. getting buy-in from stakeholders) — different JTBD = different invite prompts

REQUIRED OUTPUT SECTIONS:

**1. VIRAL MOMENT ARCHITECTURE**

Map the 7 highest-leverage invite moments in your product lifecycle:

For each moment provide:
- Trigger event (exact analytics event name, e.g., `document_shared_externally`)
- User intent state (what the user is trying to accomplish RIGHT NOW)
- JTBD job being served
- Invite prompt placement: Inline in product / Modal / Notification / Empty state
- Prompt headline (≤8 words): Must reference the specific collaboration context, not generic "Invite a teammate"
- Prompt body (≤25 words): Frame invite in terms of what the invitee will help accomplish
- CTA text (≤5 words) + secondary option (skip/remind later)
- Pre-fill logic: Auto-populate invitee email field if inviter has connected Gmail/Outlook calendar
- Suppression rule: Do not show if user has already sent ≥3 invites this week OR if invitee is already in account

Required moments to engineer (customize to your product):
a) First share/export action — user creates output that naturally needs a recipient
b) Assignment/delegation action — user tries to assign work to someone not yet in system
c) Comment/mention attempt — user @-mentions an email address not in workspace
d) Approval request — user needs sign-off from someone outside the account
e) Template/asset sharing — user wants to share a template with their team
f) Reporting/dashboard view — user wants a stakeholder to see a result
g) Onboarding checklist "Invite your team" step — explicit collaboration prompt

**2. INVITE FUNNEL BENCHMARK & LEAK ANALYSIS**

Model each stage with industry benchmarks and your estimated gap:

| Stage | Industry Benchmark | Your Estimate | Gap | ARR Impact |
|-------|-------------------|---------------|-----|------------|
| Inviting users / total MAU | 15–30% | [X%] | [delta] | [$ calc] |
| Avg invites sent per inviting user/month | 2.5–5.0 | [X] | [delta] | [$ calc] |
| Invite email delivery rate | 95–98% | [X%] | [delta] | [$ calc] |
| Invite email open rate | 55–70% | [X%] | [delta] | [$ calc] |
| Invite link click rate (of opens) | 60–75% | [X%] | [delta] | [$ calc] |
| Signup completion from invite link | 70–85% | [X%] | [delta] | [$ calc] |
| Invitee → First session within 48h | 50–65% | [X%] | [delta] | [$ calc] |
| Invitee → First collaborative event within 7 days | 35–55% | [X%] | [delta] | [$ calc] |
| Invitee collaboration → Additional paid seat added | 20–40% | [X%] | [delta] | [$ calc] |

ARR impact formula for each gap: `gap% × monthly_invites_sent × invitee_ACV_contribution`

Identify the top 2 stages with highest ARR impact gap — these are your priority interventions.

**3. INVITE EMAIL & IN-APP TEMPLATE SYSTEM**

**A. Inviter-Side Prompts (in-product)**

Design 3 in-app prompt variants for the top 3 invite moments:
- Variant 1: Contextual inline prompt (embedded in workflow, not a modal)
- Variant 2: Friction-point modal (appears when user hits a collaboration wall)
- Variant 3: Proactive nudge (appears on dashboard after user has created shareable content)

For each variant:
- Headline (≤8 words)
- Body (≤20 words)
- Primary CTA (email input field + send button OR shareable link copy)
- Dismiss option + re-surface timing (e.g., "Remind me in 3 days")
- A/B test variant (alternate headline only)

**B. Invitee Activation Email Sequence (5 touches)**

Touch 1 — Invite Notification (trigger: invite sent)
Touch 2 — "Your colleague left work for you" (trigger: 24h no acceptance + inviter has added content)
Touch 3 — Context + social proof (trigger: 48h no acceptance + inviter is active in product)
Touch 4 — Expiry warning (trigger: Day 7 — invite link expires in 48h)
Touch 5 — Re-invite request to inviter (trigger: Day 9 no acceptance — prompt inviter to re-send or follow up directly)

For each touch include:
- From name: [Inviter name] via [Product] (not a generic no-reply address)
- Subject line (with A/B variant)
- Preview text
- Full body (≤120 words)
- Primary CTA: "Accept Invitation" → deep link to specific context inside product (not generic homepage)
- Personalization tokens: `{{inviter_name}}`, `{{inviter_company}}`, `{{product_context}}` (the specific document/project they were invited to), `{{invite_expires_date}}`

**C. Newly-Activated Invitee Onboarding (in-app, first 48 hours)**

Design a 4-step guided activation path for invitees (distinct from standard trial onboarding — invitees have context and a specific reason to be there):

Step 1 (First 2 minutes): Context landing — show what the inviter shared and why it matters
Step 2 (Minutes 2–5): Complete your profile + notification preferences (so the inviter sees you're active)
Step 3 (Minutes 5–15): First collaborative action — complete the task the inviter needed you for
Step 4 (Session 2, within 48h): Discovery — reveal 2 adjacent use cases that make the invitee want to invite their own teammates

For each step: tooltip copy (≤12 words), helper text (≤30 words), completion trigger, and what fires if skipped.

**4. SEAT EXPANSION TRIGGER SYSTEM (6 AUTOMATED TRIGGERS)**

For each trigger provide: behavioral condition (exact event + threshold), suppression rules, channel (in-app / email / Slack DM via bot), timing, message copy, upgrade path, and expected seat expansion ARR per conversion.

Trigger A — Seat Saturation Warning
Condition: `filled_seats / plan_seat_limit >= 0.80`
Channel: In-app banner (persistent, dismissable) + email to account admin
Message framing: Proactive ROI — "You're getting maximum value from your current plan. Here's what adding 3 more seats would unlock."

Trigger B — Rejected Invite (Seat Limit Hit)
Condition: `invite_sent = true AND account_at_seat_limit = true`
Channel: Immediate modal (blocks the invite action)
Message framing: Urgency + solution — "You've reached your seat limit. Upgrade in 30 seconds to add [invitee_name]."

Trigger C — Power User Cluster Detection
Condition: `≥3 users in account with session_frequency >= 5/week AND account_plan != Enterprise`
Channel: Email to account owner + in-app notification
Message framing: Team ROI — "Your team is [Product]'s most active users in your industry segment. Here's what Enterprise unlocks for high-velocity teams like yours."

Trigger D — Collaboration Velocity Spike
Condition: `collaborative_events_this_week >= 2× previous_4_week_average AND seats_used = plan_limit`
Channel: In-app modal on next login for account admin
Message framing: Momentum + opportunity — "Your team's collaboration is accelerating. You're leaving capacity on the table."

Trigger E — External Collaborator Frequency
Condition: `external_share_events >= 10/month AND no_external_seats_purchased`
Channel: Email to account owner
Message framing: Efficiency — "You're sharing work externally 10+ times a month. External collaborator seats eliminate the friction and give guests full context."

Trigger F — Invitee-Became-Power-User
Condition: `invitee_account_age_days >= 14 AND invitee_session_frequency >= 4/week AND invitee_plan = free`
Channel: Email to original inviter (not the invitee)
Message framing: Social proof + champion activation — "[Invitee_name] has become one of your most active collaborators. Upgrade their access to unlock [specific feature] — it takes 30 seconds."

**5. VIRAL K-FACTOR OPTIMIZATION MODEL**

Calculate your current K-factor:
`K = (inviting_users / MAU) × (avg_invites_per_inviting_user) × (invite_accept_rate) × (invitee_becomes_inviter_rate)`

Current K-factor baseline: [calculate from inputs above]
Target K-factor: 0.30+ (sustainable viral growth loop)

Provide 5 specific lever improvements with estimated K-factor impact:

| Lever | Current | Target | Delta K | Implementation |
|-------|---------|--------|---------|----------------|
| % of MAU who send ≥1 invite/month | [X%] | [Y%] | +[Z] | [Specific action: add invite prompt to X moment] |
| Avg invites per inviting user | [X] | [Y] | +[Z] | [Specific action: pre-populate invite suggestions from Gmail] |
| Invite-to-accept rate | [X%] | [Y%] | +[Z] | [Specific action: personalize invite email with product context] |
| Invitee-to-active-user rate | [X%] | [Y%] | +[Z] | [Specific action: invitee-specific onboarding flow] |
| Active invitee-to-inviter conversion | [X%] | [Y%] | +[Z] | [Specific action: surface invite prompt at invitee's first high-value moment] |

**6. A/B TESTING ROADMAP**

Prioritize 5 experiments ranked by expected lift × implementation effort:

| Rank | Test Name | Hypothesis | Control | Variant | Success Metric | Expected Lift |
|------|-----------|------------|---------|---------|----------------|---------------|
| 1 | Context-first invite email | Personalizing invite email with specific product context (document name) increases open→accept rate | Generic "You've been invited to [Product]" | "[Inviter_name] wants your input on [Document_name] in [Product]" | Invite accept rate | +12–18% |
| 2 | Pre-populated invite suggestions | Surfacing Gmail/calendar contacts as suggested invitees reduces invite friction | Blank email input field | Pre-populated list of 3 most-emailed contacts (with one-click add) | Invites sent per inviting user | +25–35% |
| 3 | Collaboration-wall modal vs. passive nudge | Blocking invite prompt (when user hits seat limit trying to share) outperforms ambient nudge | Passive banner: "You're near your seat limit" | Blocking modal: "Add [name] to your workspace to share this — upgrade in 30 seconds" | Seat upgrade conversion | +20–30% |
| 4 | Inviter-named from address | Using inviter's name (not product brand) in invite email from field increases trust and open rates | From: [Product] Team | From: [Inviter_name] via [Product] | Invite email open rate | +8–15% |
| 5 | Deep-link vs. homepage invite landing | Landing invitees directly in the shared context (not homepage) improves activation | Invite CTA → product homepage | Invite CTA → exact document/project context | Invitee first-session completion | +30–40% |

**7. IMPLEMENTATION ROADMAP (30-60-90 DAYS)**

Days 1–30: Foundation
- [ ] Instrument invite funnel with full event tracking (invite_sent, invite_opened, invite_accepted, invitee_first_session, invitee_first_collaboration)
- [ ] Deploy Trigger B (seat-limit-hit modal) — highest-urgency, lowest engineering lift
- [ ] Launch invitee activation email sequence (Touches 1–3)
- [ ] Activate A/B Test #1 (context-first invite email)
- Owner: Growth PM + Marketing Ops
- Success criterion: Invite-accept rate measurement baseline established; Trigger B generating measurable upgrade events

Days 31–60: Optimization
- [ ] Deploy Triggers A, C, D (seat saturation, power user cluster, velocity spike)
- [ ] Launch A/B Tests #2 and #3
- [ ] Activate invitee in-app onboarding (Steps 1–4)
- [ ] Build K-factor dashboard in Amplitude/Mixpanel
- Owner: Product + Marketing Ops
- Success criterion: K-factor measured and improving; seat expansion ARR attributed to triggers

Days 61–90: Scale
- [ ] Deploy Triggers E and F (external collaborator, invitee-became-power-user)
- [ ] Launch A/B Tests #4 and #5
- [ ] Connect seat expansion trigger to CRM: auto-create expansion opportunity when Trigger C fires on $X+ ACV accounts
- [ ] Build quarterly viral coefficient report for CMO board deck
- Owner: RevOps + Marketing
- Success criterion: K-factor ≥ 0.25; seats-per-account +15% from baseline; viral-attributed new ARR tracked separately in CRM

## Example Input/Output

**Input:**
Company: Vaultly
Product: B2B contract management SaaS — users create, negotiate, and sign contracts
Seat pricing: $35/seat/month (Growth plan)
Current avg seats per paid account: 2.1 seats
Current invite-to-accept rate: 38%
Collaboration trigger: "Sending a contract for internal approval before external signature"
Current invite channel: Email invite only (generic template)
Monthly unique inviters: 210 users
Avg invites per inviting user: 1.8/month
Invitee conversion to paid seat: 22%
ICP: Legal and operations teams at 50–300 person companies

**Output (excerpt):**

**Top Viral Moment — Approval Request Wall:**
When a user clicks "Send for internal approval" and types an email address not in their workspace:
- Trigger: `approval_requested AND recipient_not_in_workspace`
- Modal headline: "Add [recipient_name] to approve this"
- Modal body: "They'll get notified, review the contract, and add their signature — all in Vaultly. No PDF ping-pong."
- CTA: "Add [recipient_name] as approver — $35/month" → Stripe checkout pre-filled
- Secondary: "Send via email instead (they won't see live comments)"
- A/B variant headline: "Your approver needs access — 30-second setup"

**Invite Funnel Analysis:**
- Inviting users / MAU: 18% (benchmark 22%) — Gap: 4% → Action: Add invite prompt to the "Send for signature" flow (currently zero invite prompt there)
- Invite email open rate: 41% (benchmark 62%) — Gap: 21% → Root cause: Generic subject line "You've been invited to Vaultly" — Fix: "[Inviter_name] needs your approval on [Contract_name]"
- Invite link → Account created: 61% (benchmark 78%) — Gap: 17% → Root cause: Invite landing page is generic homepage — Fix: Deep link to the specific contract requiring their approval
- **Top priority: Fix invite email subject + deep link landing → estimated +$186K ARR from invitee conversion improvement**

**K-Factor Calculation:**
Current K = (0.18 MAU inviting) × (1.8 invites/user) × (0.38 accept rate) × (0.28 invitee becomes inviter) = **0.034**
Target K = 0.25 (achievable in 90 days with above fixes)
Path: Fix invite email (+10 pts accept rate → K moves to 0.056) → deep-link landing (+15 pts signup → K = 0.079) → approval-wall modal (increases inviting % to 28% → K = 0.123) → invitee activation sequence (invitee-to-inviter rate to 38% → K = 0.167) → pre-populated suggestions (invites per user to 2.8 → K = 0.260)

**Seat Expansion Trigger D — Collaboration Velocity Spike:**
Condition: `contracts_collaborated_this_week >= 2× prior_4_week_avg AND seats_used = plan_seat_limit`
Timing: Next login for account admin
Channel: In-app modal
Headline: "Your contract volume doubled — your team needs more room"
Body: "You've reviewed 14 contracts this week, up from 6. Your seat limit means some approvers are working outside Vaultly. Upgrade to keep every signature in one place."
CTA: "Add 3 Seats — $105/month" → Stripe pre-filled with +3 seat upgrade
Expected expansion ARR per conversion: $1,260/year

## Success Metrics

| Metric | Current Baseline | 30-Day Target | 90-Day Target |
|--------|-----------------|---------------|---------------|
| Invite-to-accept rate | [X%] | +8 percentage points | +18 percentage points |
| Avg seats per paid account | [X] | +0.3 seats | +0.8 seats |
| % of MAU sending ≥1 invite/month | [X%] | +4 percentage points | +10 percentage points |
| Invitee → first collaborative event (48h) | [X%] | +12 percentage points | +25 percentage points |
| Seat-limit-triggered upgrades/month | [X] | Baseline established | +40% from baseline |
| Viral K-factor | [X] | +0.05 | +0.20 |
| Viral-attributed new ARR (monthly) | $[X] | Tracked | +30% |
| Invitee-to-inviter conversion rate | [X%] | +5 percentage points | +12 percentage points |

## Related Prompts

- [`../../04_Demand-&-Lead-Generation-&-Growth/Self-Serve-Expansion/AI-Powered-B2B-SaaS-Self-Serve-Trial-to-Paid-Conversion-Architecture-&-Product-Led-Revenue-Expansion-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Self-Serve-Expansion/AI-Powered-B2B-SaaS-Self-Serve-Trial-to-Paid-Conversion-Architecture-&-Product-Led-Revenue-Expansion-Intelligence-Engine.md) — Convert individual trial users before building viral team loops
- [`../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/AI-Powered-B2B-SaaS-PLG-Viral-Loop-&-Network-Effect-Organic-Acquisition-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/AI-Powered-B2B-SaaS-PLG-Viral-Loop-&-Network-Effect-Organic-Acquisition-Intelligence-Engine.md) — Design the broader network effect architecture that viral invites feed into
- [`../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/AI-Powered-B2B-SaaS-PLG-Enterprise-Champion-Identification-&-Multi-User-Viral-Expansion-Revenue-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/AI-Powered-B2B-SaaS-PLG-Enterprise-Champion-Identification-&-Multi-User-Viral-Expansion-Revenue-Intelligence-Engine.md) — Identify the power users driving your highest-value invite clusters
- [`../../04_Demand-&-Lead-Generation-&-Growth/Self-Serve-Expansion/AI-Powered-B2B-SaaS-Self-Serve-Account-Expansion-&-Automated-Upsell-Revenue-Architecture-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Self-Serve-Expansion/AI-Powered-B2B-SaaS-Self-Serve-Account-Expansion-&-Automated-Upsell-Revenue-Architecture-Intelligence-Engine.md) — Combine viral seat expansion with broader upsell architecture for full NRR coverage

## Integration Tips

**Segment / Mixpanel / Amplitude (Viral Funnel Tracking):**
Instrument the full invite funnel as a funnel analysis: `invite_sent → invite_email_opened → invite_link_clicked → invitee_signup_completed → invitee_first_session → invitee_first_collaboration → seat_added`. Track K-factor as a computed metric: update weekly. Build cohort analysis comparing invitee 30-day retention vs. organic signup retention — this data becomes your strongest seat expansion ROI story for enterprise AEs.

**Intercom / Appcues / Pendo (In-App Triggers):**
Implement Trigger B (seat-limit modal) as a blocking interstitial in Intercom Messenger or Appcues Flow with `account_at_seat_limit = true` as the audience condition. Set global frequency cap: no invite prompt more than twice per session, 3-day cool-down after dismissal. Use Pendo's path analysis to identify which product paths most frequently lead to invite moments — prioritize adding prompts to those paths first.

**Customer.io / HubSpot (Invitee Email Sequence):**
Build the 5-touch invitee sequence as a Customer.io workflow triggered by `invite_sent` event. Pass `product_context` (document/project name + deep link URL) as an event property and use it in all email copy. Set exit condition: `invitee_accepted = true` immediately removes user from sequence. For Touch 5 (re-invite prompt to original inviter), trigger a separate workflow back to the inviter's email address using the `inviter_id` property.

**Stripe / Chargebee (Seat Upgrade Path):**
Pre-configure Stripe Checkout links for common upgrade increments (+1 seat, +3 seats, +5 seats) and deep-link directly from trigger modals and emails. Pass `utm_source=viral_trigger&utm_medium=[trigger_name]` on all upgrade links to attribute expansion ARR to viral mechanics separately from standard upsell. Track in your BI tool as `viral_expansion_arr` dimension.

**Salesforce / HubSpot CRM (Enterprise Escalation):**
For Trigger C (power user cluster detection), if account ACV > $[your_threshold], skip the automated upgrade modal and instead create a Salesforce task for the account's CSM or AE: "Viral expansion signal — 3+ power users detected — expansion opportunity." Include K-factor data and seat utilization rate in the task body. This prevents friction for enterprise accounts where a $5K/year seat expansion deserves a human conversation.

## Troubleshooting

**Problem: Invite emails have high open rates but low accept rates — invitees open and don't convert.**
Fix: The invite landing page is almost certainly wrong. Invitees who open have intent — they're losing it at the signup page. Audit your invite link destination: if it lands on a generic homepage or a standard signup form, you're breaking the context chain. The invite link must deep-link to the exact document, project, or task the invitee was invited to collaborate on — with a preview visible even before signup. Add a "Preview as guest" option that shows the content (read-only) before requiring account creation. This single fix typically drives +20–30% invitee conversion.

**Problem: K-factor is improving but seat expansion ARR isn't — users are inviting but not converting to paid seats.**
Fix: Your freemium seat limit is too generous or your seat expansion triggers aren't firing at the right threshold. Audit two things: (1) What percentage of accounts are at or near their seat limit? If under 30%, your seat ceiling is too high — lower it to create natural expansion pressure. (2) Are your seat expansion triggers actually firing? Check your analytics: if Trigger A (80% seat saturation) has low event volume, either accounts aren't hitting the threshold (too-high limit) or the trigger isn't instrumented correctly. Also audit whether your expansion prompts are being suppressed too aggressively — if the `opportunity_stage != null` suppression is too broad, you may be silencing expansion nudges for accounts that sales has no active interest in.

**Problem: Invitees are accepting and completing onboarding but not becoming inviters themselves — K-factor loop is broken.**
Fix: Your invitee onboarding isn't surfacing a collaboration need for the invitee to fill. Most invitee-to-inviter conversion fails because the invitee's Step 4 (discovery of adjacent use cases) never happens — they complete the task they were invited for and leave. Fix: At the end of invitee's first collaborative session, trigger a "What would you use [Product] for on your own?" prompt with 3 specific use case tiles. Each tile shows a relevant empty-state that requires a collaborator — for example, "Get budget approved" shows an approval workflow template pre-loaded, with a one-click "Add your manager" invite. This transforms invitees from passive participants into active inviters within their first 48 hours.

## Version History
- v1.0: Initial creation (auto-generated)
