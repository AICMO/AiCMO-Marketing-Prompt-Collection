# AI-Powered B2B SaaS PLG New User Onboarding Orchestration & Aha Moment Acceleration Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, plg, onboarding, activation, aha-moment, saas, product-led-growth, lifecycle-marketing, user-activation, email-automation, behavioral-triggers, freemium

## Overview
This prompt designs a complete PLG onboarding orchestration system that engineers the critical path from new signup to first value realization (the "aha moment") to retained, upgrade-ready user. Use it when your free trial or freemium product has strong signup volume but poor activation rates, high Day 1–7 churn, or a time-to-value that kills free-to-paid conversion before users experience your product's core benefit.

## Quick Copy-Paste Version

You are a senior PLG growth architect specializing in onboarding orchestration for B2B SaaS companies. Design a complete new user onboarding system for my product that engineers the path from signup to aha moment to activated, retained user.

My product: [One sentence description of what it does]
Business model: [Freemium / Free trial (X days) / Reverse trial / Usage-based free tier]
Primary user persona: [Role, company size, key job to be done]
Current aha moment hypothesis: [The specific action or outcome that correlates with retention — e.g., "user publishes their first project" or "user completes 3 integrations"]
Current activation rate (signup → aha moment): [X%]
Biggest drop-off point: [Where most users abandon — e.g., "setup wizard step 3" or "Day 2 re-engagement"]
Available onboarding tools: [Intercom / Customer.io / Appcues / Pendo / HubSpot / email only]
Trial length or free tier limits: [X days or X free actions]

Design the complete onboarding orchestration system:

1. AHA MOMENT ARCHITECTURE — Confirm or refine the aha moment based on PLG best practices. Define the exact product event(s) that signal value realization. Break the path to aha moment into 3–5 milestone steps, each with: the user action required, the friction to remove, and the activation content to deliver at that moment.

2. ONBOARDING EMAIL SEQUENCE — Write a 7-email onboarding sequence (Days 0, 1, 3, 5, 7, 10, 14). For each email: subject line, preview text, 3-paragraph body, primary CTA, behavioral send condition (send if [event NOT fired] within [timeframe]), and a suppression rule (suppress if [event fired]).

3. IN-APP MESSAGING SYSTEM — Design 5 in-app messages: (a) welcome modal at first login, (b) empty state message for the core feature, (c) milestone celebration at aha moment, (d) upgrade nudge for users approaching limit, (e) re-engagement banner for users inactive 3+ days. For each: placement, trigger, headline, body, CTA, and dismissal behavior.

4. BEHAVIORAL TRIGGER LIBRARY — Define 6 behavioral triggers that fire automated interventions: 2 positive (user completing key actions), 2 friction (user stuck or abandoning), 2 time-based (inactivity). For each: triggering event + conditions, channel (email / in-app / push), message template, and escalation rule (when does a human CS or AE get notified).

5. ACTIVATION ANALYTICS FRAMEWORK — Define the 5 core metrics to track, with formulas: (a) Activation Rate, (b) Time-to-Aha, (c) 7-Day Retention Rate, (d) Onboarding Completion Rate by step, (e) Assisted vs. Unassisted Activation Rate. Include the cohort analysis approach to identify which onboarding paths produce the highest LTV.

Output as a structured playbook with email templates, in-app message copy, trigger rules, and analytics definitions ready to load into [Intercom / Customer.io / HubSpot] and your product analytics tool.

## Advanced Customizable Version

ROLE: You are a senior PLG Onboarding Architect with 12+ years designing activation systems for product-led B2B SaaS companies. You have built onboarding systems that moved activation rates from 12% to 45%+ at companies like [Notion, Figma, Loom, Calendly, Linear, Vercel]-style products. You combine expertise in behavioral psychology, email marketing, product analytics, in-app UX copywriting, and growth experimentation to engineer onboarding systems that create habitual product users and accelerate free-to-paid conversion.

CONTEXT:
Company: [Company name]
Product description: [What it does, who uses it daily, the core job-to-be-done]
Business model: [Freemium / Free trial (X days) / Reverse trial / Usage-limited free tier]
Pricing tiers: Free ([limits]) → [Growth/Pro] ($[X]/mo) → Enterprise (custom)
Primary ICP: [Role, seniority, company size, industry]
Secondary ICP: [If applicable]
Current monthly signups: [X]
Current activation rate (signup → first key action): [X%]
Current free-to-paid conversion rate: [X%]
Current aha moment hypothesis: [The product milestone you believe correlates with long-term retention — be specific about the product event]
Data confirming aha moment: [Yes/No — if yes, what data; if no, what you suspect]
Biggest drop-off: [Where in the onboarding funnel most users disappear]
Onboarding toolstack: [Product analytics: Amplitude/Mixpanel/PostHog] + [In-app: Appcues/Pendo/Intercom] + [Email: Customer.io/HubSpot/Intercom] + [CRM: Salesforce/HubSpot]
Trial length or free tier limits: [Days or usage limits]
Current onboarding: [Describe existing onboarding: email sequence length, in-app setup wizard, etc.]
Key constraint: [e.g., "no in-app tool yet, only email," "4-step setup wizard we can't change," "no dedicated onboarding team"]

OBJECTIVE: Design a production-ready PLG onboarding orchestration system that maximizes the percentage of new signups who reach and repeat the aha moment, building the habit loop that drives retention, expansion, and free-to-paid conversion — without requiring human intervention for the majority of users.

---

DELIVERABLE 1 — AHA MOMENT ARCHITECTURE

Step 1: Aha Moment Validation
Evaluate the stated aha moment hypothesis using these criteria:
- Specificity: Is it a concrete product event, not a vague feeling? (Bad: "user sees value." Good: "user creates and shares their first published output.")
- Measurability: Can it be captured as a product analytics event with a timestamp?
- Predictiveness: Based on PLG benchmarks, does this type of milestone correlate with 30-day retention?
- Attainability: Can 80%+ of motivated users reach it within their trial period?

If the hypothesis passes: confirm and define the exact product event name + properties to track.
If it fails: propose an alternative aha moment with rationale.

Step 2: Activation Milestone Map
Break the path from signup to aha moment into 3–5 discrete milestones. For each milestone:
- Milestone name (user-facing label, e.g., "Profile Complete," "First Project Live")
- The specific product action required
- Primary friction source at this step (what causes users to abandon)
- Friction removal tactic (in-app copy change, default content, template, or simplified flow)
- Activation content to deliver at this moment (tooltip / modal / email / celebration message)
- Estimated time commitment for motivated user (minutes)
- % of signups who currently complete this step (if known, else use industry benchmark)

Step 3: Habit Loop Architecture
After the aha moment, define the 3-step habit loop that turns one-time use into retention:
- Trigger: What internal or external trigger brings the user back?
- Action: The core action they take (ideally the aha moment repeated)
- Variable Reward: What variable value does the product deliver on return?
- Investment: What makes the product more valuable with each use (data, content, integrations)?

---

DELIVERABLE 2 — ONBOARDING EMAIL SEQUENCE

Design a 14-day behavioral email program with 9 emails. Each email must include:

Format for each:
- Send trigger: [Behavioral condition: "Send if [event NOT fired] within [X hours] of signup" OR "Send at [Day X] if user has not reached [milestone]"]
- Suppression rule: [Suppress this email if [event fired] — prevents irrelevant messages to activated users]
- Subject line: [8 words max, curiosity/value-driven, no "welcome to [Product]" clichés]
- Preview text: [Extends the subject, 50 chars max]
- Email structure: Opening hook (1 sentence addressing the user's job-to-be-done), Body (2–3 sentences max per paragraph, total 3 paragraphs), CTA (single, specific action — not "log in," but "create your first [X]")
- Dynamic personalization variables: [List 2–3 variables to pull from user profile or product data]
- A/B test hypothesis: [One element to test in this email and the hypothesis]

Email schedule:
- Email 1 — Day 0, within 5 minutes of signup: Welcome + immediate value delivery
- Email 2 — Day 1, if Milestone 1 NOT completed: Activation nudge for first milestone
- Email 3 — Day 2, triggered by Milestone 1 completion: Milestone celebration + guide to Milestone 2
- Email 4 — Day 3, if aha moment NOT reached: Social proof + "what great looks like" example
- Email 5 — Day 5, if aha moment NOT reached: Objection handling + simplification offer (template, quick-start guide, or "do it for me" option)
- Email 6 — Day 7, if aha moment NOT reached: Urgency / trial limitation awareness (for trial products)
- Email 7 — Day 7, if aha moment IS reached: Deepen engagement + introduce next high-value feature
- Email 8 — Day 10, upgrade nudge for users approaching free tier limit
- Email 9 — Day 14, trial end / free tier recap: "Here's what you built" personalized summary + upgrade offer

---

DELIVERABLE 3 — IN-APP MESSAGING SYSTEM

Design 8 in-app messages that guide users through activation without overwhelming them. For each:
- Message type: [Modal / Tooltip / Banner / Spotlight / Empty state / Toast notification]
- Trigger: [First login / Specific page visit / Action completed / X days of inactivity / Approaching limit]
- Targeting: [All new users / Users who have NOT completed [milestone] / Users in [role] ICP / etc.]
- Headline: [6 words max, outcome-focused]
- Body copy: [2 sentences max — what to do and why it matters]
- Primary CTA: [Action button text — verb + noun, e.g., "Create Your First Report"]
- Secondary CTA or dismissal: [Skip for now / Remind me later / View example]
- Dismissal behavior: [Reshow after X days / Permanent dismiss / Escalate to email if dismissed twice]
- Success condition: [Remove this message when [event fired]]

Messages to design:
A. Welcome modal (first login): Product orientation + path to first value
B. Empty state — core feature: When the main canvas/workspace is empty, show the user what to build first
C. Setup progress indicator: Persistent progress bar showing milestone completion (show until aha moment reached)
D. Milestone 1 celebration: Toast/modal when first key action is completed — celebrate + point to next step
E. Aha moment celebration: Full-screen moment of delight when aha moment is reached — include share/invite hook
F. Inactivity rescue banner: Shown on Day 3 re-login after period of inactivity — personalized "pick up where you left off"
G. Upgrade nudge — feature gate: Non-intrusive notice when user attempts a paid-only feature
H. Upgrade nudge — limit approaching: Banner when user reaches 80% of free tier limit

---

DELIVERABLE 4 — BEHAVIORAL TRIGGER LIBRARY

Define 8 behavioral triggers with complete automation specs:

POSITIVE TRIGGERS (user doing well — accelerate their progress):
Trigger 1 — Power Start Signal: User completes [milestone 1] within 30 minutes of signup
- Action: Fire Milestone 1 Celebration email (from Deliverable 2, Email 3) immediately + skip scheduled Email 2
- In-app: Show tooltip pointing to Milestone 2 within the UI
- Goal: Capitalize on high-intent moment by shortening the path to aha moment

Trigger 2 — Aha Moment Achieved: User fires the core aha moment event
- Action: Suppress all remaining activation emails, enroll in post-activation sequence
- In-app: Show aha moment celebration modal with invite/share CTA
- CRM signal: Log "Activation_Status = Activated" on contact record, set PQL_Score baseline
- Goal: Pivot immediately from activation to habit formation and expansion

FRICTION TRIGGERS (user stuck — remove obstacles):
Trigger 3 — Setup Abandonment: User starts setup wizard but does not complete within 24 hours
- Action: Send Email 2 variant ("Still setting up? Here's a shortcut") + surface in-app tooltip at the abandoned step on next login
- Escalation: If user does not complete within 48 hours after trigger, notify CS via Slack alert for high-ICP accounts (company size > [X])

Trigger 4 — Feature Exploration Without Action: User visits the core feature page 3+ times but never creates anything
- Action: Trigger in-app modal offering a pre-built template or "start from example" option
- Email: Send "Start with this template" email with a one-click import link for a sample project
- Goal: Lower the blank-canvas fear that kills activation for non-technical users

TIME-BASED TRIGGERS (inactivity — rescue before churn):
Trigger 5 — Day 3 Lapse: User signed up 3 days ago, completed <2 milestones, has not logged in for 48 hours
- Action: Send Email 5 ("The 5-minute [Product] setup — no starting from scratch")
- In-app: Prepare personalized banner for next login showing their saved progress
- Escalation: High-ICP accounts (filtered by company size/domain) get SDR soft outreach

Trigger 6 — Day 7 Dark: User has not logged in for 7 days and has not reached aha moment
- Action: Send Email 6 (urgency + limit reminder if on trial) OR a "we miss you" email with a success story
- Escalation: Route to churned-before-activation segment for win-back campaign after Day 14

EXPANSION TRIGGERS (activated users — grow revenue):
Trigger 7 — Limit Threshold: Free-tier user reaches 80% of usage limit (seats, projects, API calls, etc.)
- Action: Show upgrade nudge in-app (Deliverable 3, Message H) + enroll in upgrade email sequence (Email 8 variant)
- CRM: Set PQL_Stage = "Limit_Approaching" — SDR notified for high-ACV accounts

Trigger 8 — Invite Sent: Activated user invites a colleague to the workspace
- Action: Send "Thanks for growing your team" email with guide on multi-user workflows
- In-app: Show "Collaboration features" spotlight to educate on team-level value
- CRM: Log invite event as viral expansion signal — increase PQL Score

---

DELIVERABLE 5 — ACTIVATION ANALYTICS FRAMEWORK

Define the complete measurement system for onboarding performance:

CORE METRICS (define formula, data source, and acceptable benchmark for each):

1. Activation Rate
- Formula: (Users who complete aha moment event / Total signups in cohort) × 100
- Cohort window: Measured at Day 7 and Day 30
- Data source: Product analytics tool (Amplitude / Mixpanel / PostHog)
- B2B SaaS PLG benchmark: 25–40% at Day 7 (varies by product complexity)
- Alert threshold: Flag if drops >5pp week-over-week

2. Median Time-to-Aha (T2A)
- Formula: Median(timestamp of aha moment event − signup timestamp) for activated users
- Why median not average: Prevents skew from power users who activate instantly
- Target: <24 hours for self-serve-optimized products; <72 hours for complex workflows
- Segment by: Acquisition channel, persona, company size to identify which sources activate fastest

3. Onboarding Funnel Completion Rate by Milestone
- Formula: Users completing Milestone N / Users who completed Milestone N−1
- Report as: Step-by-step funnel with drop-off % at each stage
- Update frequency: Weekly cohort comparison, daily monitoring during A/B tests
- Action trigger: Any single step with <60% completion rate gets immediate experimentation priority

4. 7-Day and 30-Day Retention Rate (Post-Activation)
- Formula: Activated users who return and complete core action in Day 2–7 window / Total activated users
- Segment by: Onboarding path (assisted vs. unassisted, email engaged vs. not)
- Why this matters: Retention at Day 7 is the leading indicator of month-1 conversion
- Target: 50%+ of activated users return within 7 days of aha moment

5. Onboarding Email Engagement → Activation Lift
- Formula: Activation Rate of email-engaged users / Activation Rate of email-unengaged users
- This measures whether emails are causal or just correlated with activation
- Run holdout experiment: Withhold Email 3 (aha moment guidance) from 10% of users to measure true lift
- Report: Monthly, broken down by email in the sequence

COHORT ANALYSIS APPROACH:
Build a weekly signup cohort table showing:
- Cohort (week of signup)
- Day 1 activation rate / Day 7 activation rate / Day 30 activation rate
- Median T2A
- 30-day retention rate
- Free-to-paid conversion rate
Color-code: Green (at or above benchmark) / Yellow (5–15% below) / Red (15%+ below)
Use this table in weekly growth reviews to identify if an onboarding change improved or hurt a cohort.

ACTIVATION SEGMENTATION MATRIX:
Segment all signups into 4 quadrants by Day 7:
- Activated + Retained: Champions — model their onboarding path, build referral programs around them
- Activated + Churned: Habit not formed — audit what they did vs. retained users; add Day 7–14 engagement sequences
- Not Activated + Active: Stuck — identify friction point; high priority for in-app rescue
- Not Activated + Inactive: Lost — rescue campaign window closes at Day 14; transition to win-back sequence

---

DELIVERABLE 6 — RESCUE SEQUENCE ARCHITECTURE

For users who reach Day 10 without activating, design a 3-touch rescue program before transitioning to churned status:

Rescue Touch 1 — Day 10 email: "Let's do this together"
- Offer: Personalized 20-minute onboarding call with a product specialist (for high-ICP accounts) OR video walkthrough of the exact steps to reach aha moment
- Format: Short, direct, no excuses email — acknowledge they haven't gotten started, make it easy to begin
- CTA: "Book a 20-min setup call" (Calendly) OR "Watch the 3-minute setup video" (Loom)

Rescue Touch 2 — Day 12 in-app (on next login): "Pick up where you left off"
- Personalized banner showing their progress: "You completed Step 1 of 3. Here's your shortcut to Step 2."
- One-click deep link that bypasses the setup wizard and drops them at the next required action
- Include social proof: "347 teams like yours got started last week"

Rescue Touch 3 — Day 14 email: Last chance + alternative path
- For trial products: Trial expiration reminder with extension offer (3 more days) gated behind completing Milestone 1
- For freemium: "You're staying on free — here's what you're missing" with specific feature list locked behind activation
- Alternative offer: "Not a good time? We'll be here when you're ready." + automated re-engagement trigger set for 30 days

Post-Rescue Transition:
- Day 14+ non-activated users: Move to cold re-engagement segment (quarterly touchpoint)
- Notify SDR for accounts with company size >100 employees or domain scoring as high-ICP
- Log "Churned_Before_Activation" in CRM as distinct segment from post-activation churn

OUTPUT FORMAT: Structured playbook with milestone map, full email copy, in-app message specifications, trigger rules with event names, and analytics dashboards. All email and in-app templates must include [bracketed_variable_names] for dynamic personalization. Default toolstack assumed: PostHog (product analytics) + Customer.io (email) + Intercom (in-app) + HubSpot (CRM), with notes for Amplitude + Appcues + Marketo alternatives.

## Example Input/Output

**Input Example:**
Company: Koda — a no-code internal tool builder that lets operations and product teams build custom dashboards and approval workflows without writing code
Business model: Freemium (up to 3 internal tools, 5 users) → Pro ($149/mo for unlimited tools, 25 users) → Enterprise (custom)
Primary ICP: Operations Managers and Product Ops at 50–500 person B2B SaaS companies
Current aha moment hypothesis: "User creates and previews their first internal tool (dashboard or form)"
Current activation rate: 18% at Day 7
Biggest drop-off: 63% of signups never get past the blank canvas on Step 2 of the setup wizard
Toolstack: PostHog + Customer.io + Intercom + HubSpot
Trial length: Freemium (no time limit, but feature limit)

**Output Example (excerpt):**

**Refined Aha Moment:** Confirmed — but tightened to: "User creates AND shares their first internal tool with at least one teammate." The sharing action triggers the social confirmation loop that converts single users into team accounts, which is the activation pattern that correlates with 30-day retention in no-code tools. Sharing = value delivered to others = product now has social capital in the organization.

**Activation Milestone Map:**

| Milestone | Required Action | Primary Friction | Removal Tactic | Activation Content |
|-----------|----------------|-----------------|----------------|-------------------|
| M1: Connected | User connects first data source (Google Sheets, Airtable, or HubSpot) | "I don't know which data source to pick" | Default to Google Sheets (most common); show 3 options max | Tooltip: "Most Koda users start with Google Sheets. Connect it in 30 seconds." |
| M2: Built | User drags 3+ components onto the canvas | Blank canvas paralysis | Launch with "Start from template" default — 6 curated templates visible immediately | Empty state: "Pick a template or start blank. Either way, you'll have something live in 10 minutes." |
| M3: Previewed | User clicks "Preview Tool" button | Perfectionism — users over-engineer before previewing | Add auto-preview prompt after 5 minutes of editing: "Looks great so far. Preview it?" | Toast notification: "You built something. Want to see it live?" |
| M4: Shared (Aha) | User sends tool link to a teammate | "It's not ready yet" / don't know how to share | Add share button in preview mode with pre-filled message: "Here's the [tool] I built for us in Koda" | Aha Modal: "🎉 Your first tool is live. Share it with your team — they can use it right now." |

**Email 1 — Day 0, within 5 minutes of signup:**
*Subject:* Your first internal tool — built in 10 minutes
*Preview:* Here's the fastest path to something your team can use today
*Trigger:* Send immediately on signup completion
*Suppression:* Suppress if user completes M1 (data source connected) within 5 minutes

"Welcome to Koda — you're [X] minutes from having your first internal tool live.

The fastest path: connect Google Sheets → pick a dashboard template → share the link with your team. Most new users complete all three in under 10 minutes, even without technical experience.

Click below and you'll land exactly where you need to be to start."

CTA: "Connect My First Data Source →" [deep link to data source connector page]
A/B Test: Test "Connect My First Data Source" vs. "Start from a Template" — hypothesis: template CTA reduces blank canvas fear and improves M2 completion.

**Behavioral Trigger 3 — Setup Abandonment (day 2 example):**
Trigger condition: User completes M1 (data source connected) but has NOT completed M2 (canvas component dropped) within 48 hours of M1 completion
Email send: "Stuck on the blank canvas? Use ours."
Body: "You connected your Google Sheets data to Koda — the hard part is done. The next step is adding components to your canvas, and we know the blank page can feel overwhelming. So we built you a head start: here's a Operations Dashboard template pre-wired to a Google Sheets schema exactly like yours. One click and it's populated with your data."
CTA: "Load My Pre-Built Template →" [deep link to template with user's data source pre-connected]
In-app: On next login, show spotlight on "Templates" button in the sidebar with copy: "Start here — not from scratch."

## Success Metrics

**Onboarding System Health KPIs:**
- **Activation Rate at Day 7:** % of signups who reach aha moment within 7 days. Target: >35% (industry benchmark: 25–40% for no-code/workflow tools). Measure weekly by cohort.
- **Median Time-to-Aha:** Target <48 hours from signup for motivated ICP users. Segment by acquisition channel — paid search signups should activate faster than organic (higher intent).
- **Email Sequence Engagement Lift:** Activated users who engaged with onboarding email sequence vs. those who did not. Expect 2–3x higher activation rate for email-engaged cohort. Run monthly holdout test to confirm causality.
- **Step-by-Step Funnel Completion:** Each milestone should show >65% completion from prior step. Any step below 60% is a product/copy problem requiring immediate A/B test.
- **Rescue Sequence Recovery Rate:** % of Day 10 non-activated users who activate within 7 days of rescue sequence. Benchmark: 15–25% recovery rate from this cohort.
- **Onboarding-Assisted Conversion Rate:** % of activated users who convert to paid within 30 days vs. industry benchmark (3–8% for B2B SaaS PLG).

**Quality Signals:**
- Activation-to-retention ratio: >50% of activated users return within 7 days (signals habit loop is forming)
- Email sequence suppression accuracy: >90% of messages correctly suppressed for users who already completed the relevant milestone
- In-app message dismissal rate: <30% dismissal rate on setup guidance messages (high dismissal = wrong timing or wrong message)

## Related Prompts
- [PLG In-App Behavioral Activation & Product Usage-Triggered Revenue Campaign](./AI-Powered-B2B-SaaS-PLG-In-App-Behavioral-Activation-&-Product-Usage-Triggered-Revenue-Campaign-Intelligence-Engine.md)
- [PLG PQL Pipeline Architecture & Free-to-Paid Revenue Conversion](./AI-Powered-B2B-SaaS-Product-Led-Growth-PQL-Pipeline-Architecture-&-Free-to-Paid-Revenue-Conversion-Intelligence-Engine.md)
- [Product-Led Sales (PLS) Motion Architecture](./AI-Powered-B2B-SaaS-Product-Led-Sales-PLS-Motion-Architecture-&-Product-Signal-to-Revenue-Sales-Assist-Intelligence-Engine.md)
- [Customer Onboarding Intelligence System](../../06_Customer-Success-&-Retention/Customer-Onboarding-&-Activation/Customer-Onboarding-Intelligence-System.md)

## Integration Tips

**PostHog + Customer.io (Recommended PLG stack for <$10M ARR):**
- Define milestone events in PostHog as custom events (e.g., `tool_shared`, `data_source_connected`)
- Use PostHog's Destinations to sync user properties to Customer.io in real time via webhook
- Build behavioral email triggers in Customer.io using "Event triggered campaigns" — set trigger to `tool_shared NOT fired` within 72 hours of `signup_completed`
- Use Customer.io's Liquid templating to inject PostHog-synced properties into email copy (e.g., `{{customer.company_name}}`, `{{customer.data_source_type}}`)

**Intercom (In-app messages + email in one tool):**
- Use Intercom Series to build the full onboarding sequence with branching logic based on product events
- Connect PostHog or Amplitude via native integration or Segment to fire Intercom messages on product events
- Use Intercom's "Tour" feature for the milestone guidance tooltips (Deliverable 3, Messages A–C)
- Set up Intercom Bots for the Day 3 rescue to offer live chat with a specialist — converts high-ICP stuck users at 3–5x email rate

**Amplitude + Braze (Enterprise PLG stack):**
- Build Activation Funnel in Amplitude as a saved chart — share with product and growth teams in weekly standup
- Use Amplitude's Cohort Sync to push non-activated Day 5 users to Braze as a real-time audience
- Trigger Braze Canvas flows when cohort membership changes — ensures rescue emails fire immediately on segment entry, not on batch schedule
- Use Amplitude's Experiment tool to run holdout tests on email sequences (withhold Email 5 from 10% of users to measure causal lift)

**HubSpot (All-in-one for SMB PLG teams):**
- Use HubSpot Custom Events (Operations Hub) to track product milestones via server-side API calls
- Build HubSpot Workflows triggered on custom event "NOT fired within X days of contact creation"
- Use HubSpot's Sequences for the rescue program (Deliverable 6) — CSM or SDR manually reviews high-ICP accounts before sending
- Connect HubSpot to Intercom via native integration so in-app conversations populate CRM contact timeline

**Zapier automation (for lean teams without engineering support):**
- PostHog → Zapier → Customer.io: Use PostHog's webhook feature to fire a Zapier trigger on each milestone event; Zap updates Customer.io contact properties and enrolls/suppresses email sequences
- Calendly → HubSpot: When rescue-sequence prospect books onboarding call, log activity on HubSpot contact and remove from automated rescue emails

## Troubleshooting

**Problem: Activation rate improved but 30-day retention didn't — users reach aha moment once and never return**
*Solution:* The aha moment is likely a setup action (creating an account, building one thing) rather than a recurring value delivery. Redefine the aha moment as a repeatable action: not "user creates first tool" but "user's tool is used by a teammate 3+ times in the first week." Also audit whether the habit loop (trigger → action → variable reward → investment) is present in your product. If the product doesn't naturally pull users back, add external triggers: weekly digest emails showing their tool's usage stats, or notifications when teammates interact with their tools.

**Problem: Onboarding emails have high open rates but no activation lift — emails are being read, not acted on**
*Solution:* The CTA is the problem, not the subject line. Audit whether every email CTA deep-links to the exact next step (bypassing homepage or dashboard navigation) or asks the user to "log in and figure it out." Replace generic CTAs like "Get Started" with action-specific CTAs like "Add Your First Column →" with deep links. Also test reducing email length to 3 sentences maximum — long emails are read but not acted on; short emails are acted on.

**Problem: In-app messages have high dismissal rates (>50%) — users are closing guidance without reading**
*Solution:* Three likely causes: (1) Wrong timing — showing messages immediately on login before users have oriented; delay all non-welcome messages by 30–60 seconds of session activity. (2) Message overload — if users see >2 messages per session, all get dismissed; enforce a 1-message-per-session cap. (3) Wrong placement — tooltips pointing to features the user hasn't navigated to yet create confusion; ensure tooltip triggers only fire when the user is on the relevant page.

## Version History
- v1.0: Initial creation (auto-generated)
