# In-App Product Experience & Activation Intelligence Engine - Design, Automate, and Optimize Your In-Product Onboarding to Drive Time-to-Value at Scale

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** product-led-growth, activation, onboarding, time-to-value, in-app-experience, plg, pendo, appcues, user-activation, b2b-saas, automation

## Overview
Design and automate a complete in-app onboarding and activation system that guides new users to their "aha moment" faster, reduces early churn, and drives product-qualified leads — all without requiring CS intervention. Use this when your trial-to-paid conversion is below 25%, your activation rate is below 40%, or you're scaling a PLG motion and need in-product experience to do the selling.

## Quick Copy-Paste Version

You are a senior product-led growth strategist specializing in in-app onboarding and user activation for B2B SaaS companies.

My business context:
- Company: [Your Company Name]
- Product: [What you sell, e.g., project management platform for creative agencies]
- Pricing model: [Free trial / freemium / reverse trial / paid only]
- Trial length: [e.g., 14 days] | Activation window: [e.g., first 72 hours]
- Current activation rate: [e.g., 31% — users who complete core setup in 7 days]
- Trial-to-paid conversion: [e.g., 18%]
- In-app experience tool: [Pendo / Appcues / Chameleon / WalkMe / Intercom Product Tours / none yet]
- Product analytics: [Mixpanel / Amplitude / Heap / PostHog / other]
- Primary "aha moment": [e.g., the moment a user sees their first project dashboard populate with live data]

Deliver a complete in-app activation system with these components:

1. AHA MOMENT DEFINITION & ACTIVATION MILESTONE MAP
   - Precise definition of the aha moment tied to specific user action + measurable outcome
   - 5-step activation milestone sequence from signup to activated user
   - Leading behavioral indicators that predict whether a user will activate (observable in first 48 hours)
   - Time-to-value benchmarks by persona and use case segment

2. IN-APP ONBOARDING FLOW ARCHITECTURE
   - Welcome experience: first screen logic based on user role/job-to-be-done collected at signup
   - Product tour design: which 3-5 features to show, in what order, with what copy for each tooltip
   - Empty state designs: what to show before users have real data (templates, sample data, guided setup)
   - Progress indicators and checklist design to drive completion without feeling forced
   - Contextual help triggers: when and how to surface in-app help without interrupting flow

3. BEHAVIORAL TRIGGER AUTOMATION
   - 8 specific user behavior triggers with exact in-app message to fire for each
   - Segmentation logic: different flows for different user personas, company sizes, or use cases
   - Day 1 / Day 3 / Day 7 activation milestone messaging if user hasn't hit each checkpoint
   - Dormancy intervention: in-app message sequence for users who've logged in but stalled

4. IN-APP UPGRADE & EXPANSION TRIGGERS
   - Feature gate messaging: how to present premium feature limits without frustrating free users
   - Usage-based upgrade prompts: copy and timing for when users approach plan limits
   - Social proof triggers: when to surface peer benchmarks and customer success stories in-app
   - Conversion moment: the specific in-app experience at the upgrade decision point

5. A/B TESTING ROADMAP
   - 5 highest-impact experiments to run in first 90 days with hypothesis and success metric for each
   - Minimum sample sizes and test duration guidance
   - How to segment test results by user cohort to avoid averaging across different use cases

6. ACTIVATION METRICS DASHBOARD
   - 8 metrics to track with formulas, benchmarks, and Red/Yellow/Green thresholds
   - Activation funnel breakdown and where to find drop-off
   - Weekly review cadence and what decisions each metric should drive

Make every deliverable production-ready with specific copy for tooltips, in-app messages, and modal headlines. Use realistic numbers and tool-specific implementation guidance throughout.

## Advanced Customizable Version

You are a world-class product-led growth architect and UX strategist with 15+ years designing in-app onboarding systems that drive activation at scale. You have built activation frameworks for companies from $500K to $500M ARR, including multiple unicorns. You understand the cognitive psychology of onboarding — progressive disclosure, the Fogg Behavior Model, hook cycles, and how to engineer habit formation in the critical first 72 hours. Your activation systems have moved trial-to-paid conversion rates from sub-15% to above 35% in multiple documented cases.

COMPANY CONTEXT:
- Company name: [Company]
- Product category: [e.g., AI-powered contract management SaaS for mid-market legal teams]
- Go-to-market motion: [PLG / sales-led / hybrid PLG+sales]
- Pricing and trial model: [e.g., 14-day free trial, no credit card required, freemium tier available]
- Target customer: [ICP — role, company size, industry]
- Current activation rate: [X]% (define your activation event: [e.g., user creates first contract template AND invites one team member within 7 days of signup])
- Trial-to-paid conversion: [X]% | Time-to-paid-conversion (average): [X days]
- Monthly signups: [X] | Monthly activated users: [X] | Monthly conversions: [X]
- In-app experience tool: [Pendo / Appcues / Chameleon / WalkMe / Intercom / Userflow / custom-built / none]
- Product analytics: [Tool and key events you currently track]
- Current onboarding: [Describe existing onboarding — email sequence, any in-app tours, welcome wizard, etc.]
- Known friction points: [Where users drop off, if known]
- Primary "aha moment" hypothesis: [Your current belief about the activation moment]
- Key personas (up to 3): [e.g., Legal Operations Manager / General Counsel / Procurement Manager]

OBJECTIVE:
Build a full-stack in-app activation system that increases activation rate by 15+ percentage points and trial-to-paid conversion by 8+ percentage points within 90 days, without increasing CAC or CS headcount. All deliverables must be implementable directly in [your in-app tool] and measurable in [your analytics tool].

---

DELIVERABLE 1: AHA MOMENT & ACTIVATION ARCHITECTURE

PART A — AHA MOMENT FORENSICS

The aha moment is the specific, repeatable action sequence after which a user is statistically unlikely to churn in the first 30 days. To define it precisely:

Step 1 — Behavioral correlation analysis prompt:
"Analyze users who converted to paid (Group A) vs. users who signed up but never converted (Group B). Identify the 3-5 actions Group A users completed in their first 72 hours that Group B users did not. Rank by predictive power."

This prompt should be run against your analytics tool's user cohort data. Provide the output format you expect, including the specific Mixpanel / Amplitude query structure.

Step 2 — Aha moment definition template:
"A user has experienced our aha moment when they have completed [specific action A] AND [specific action B] within [X hours/days] of signup AND have observed [specific measurable outcome — e.g., their first processed contract appear in the dashboard with correct clause extraction]."

Include:
- Primary aha moment (the core value delivery)
- Secondary aha moment (the social/collaborative value delivery — e.g., inviting a teammate, sharing output)
- Leading indicator behaviors that predict aha moment completion (observable in first 24 hours)

PART B — ACTIVATION MILESTONE MAP

Design a 6-stage activation journey from signup to expansion-ready:

Stage 0: Signup Complete (Day 0, Hour 0)
- Trigger: User creates account
- Goal: Get user into product and oriented within 3 minutes
- Success metric: First meaningful action taken within 10 minutes of signup
- Failure signal: User exits without taking any action within 15 minutes

Stage 1: Setup Complete (Day 0, Hours 0-4)
- Define the 1-3 minimum setup actions required before core value is accessible
- Which setup steps are mandatory vs. optional (never show more than 3 mandatory steps)
- Progressive disclosure logic: what to hide until the user is ready

Stage 2: First Value Moment (Day 0-1, Hours 1-48)
- The specific moment the product delivers its first tangible output
- What the user sees, feels, and can share immediately
- Success rate benchmark: >60% of activated users hit this milestone

Stage 3: Habit Formation (Days 2-7)
- The repetitive action loop that creates the weekly usage habit
- How to engineer a variable reward schedule in-product
- Notification strategy: when push notifications or email nudges should supplement in-app experience

Stage 4: Social Proof & Collaboration (Days 3-10)
- The viral/collaborative feature that expands product stickiness beyond one user
- How to prompt collaboration naturally without forcing it
- Network effects trigger: what causes a user to invite colleagues

Stage 5: Expansion Ready (Days 7-14)
- Behavioral signals that indicate a user is ready for upgrade conversation
- PQL (product-qualified lead) definition tied to stage completion
- Hand-off to sales (for sales-assisted PLG) or self-serve upgrade flow

---

DELIVERABLE 2: IN-APP ONBOARDING FLOW ARCHITECTURE

PART A — WELCOME EXPERIENCE DESIGN

First Screen Decision Logic:
Build a branching onboarding entry point based on job-to-be-done data collected at signup (max 2 questions: "What's your primary role?" and "What brings you here today?"). Provide:
- The exact signup micro-survey (2 questions maximum, with answer options)
- How each answer combination maps to a different onboarding track
- What changes between tracks (content shown, features highlighted, empty state copy)

Welcome Modal Design:
- Headline formula: "Welcome, [First Name]. Let's [specific outcome] in [specific timeframe]."
- Supporting copy (max 20 words) — what to promise, specifically
- First CTA: a single, high-momentum action that delivers value immediately
- What NOT to show: skip the feature tour for now, skip settings, skip inviting teammates

PART B — PRODUCT TOUR DESIGN

Architecture principles:
- Show maximum 5 tooltips in the primary product tour
- Each tooltip: one job, one sentence, one action
- Never show a tooltip that explains the UI — only show tooltips that explain the user's outcome
- Tour must be completable in under 4 minutes

For each of the 5 tour steps, provide:
- Feature/area being highlighted
- Tooltip headline (max 6 words)
- Tooltip body (max 20 words, outcome-focused)
- CTA button text (action verb, max 4 words)
- Skip logic: what happens if user dismisses vs. completes

PART C — EMPTY STATE DESIGN

Empty states are where most products lose 40-60% of new users. Design each critical empty state:

For each of the 3-5 main product areas, provide:
- Primary headline (max 8 words — what value awaits, not what's missing)
- Supporting copy (max 25 words — what to do AND what the result will be)
- Primary CTA + ghost CTA (two options: create their own OR use a template/example)
- Sample data or template strategy: what pre-populated example content to show
- Visual illustration direction (describe what the empty state illustration should convey)

PART D — ACTIVATION CHECKLIST DESIGN

The activation checklist is the highest-ROI single UI element in onboarding. Design it:
- Exactly 5 items (not 3, not 7 — 5 creates the right completion psychology)
- Item names must be outcome-oriented ("See your first [output]" not "Complete setup")
- Progress bar vs. step counter vs. completion percentage — which to use and why
- Visibility logic: sticky side panel vs. collapsible widget vs. full-page dashboard section
- Completion incentive: what happens when user completes all 5 items (celebration, unlock, notification)
- Auto-dismiss logic: when does the checklist disappear to reduce UI clutter

---

DELIVERABLE 3: BEHAVIORAL TRIGGER AUTOMATION

Design 10 behavioral triggers with complete in-app message specifications. For each trigger, provide:

Format per trigger:
- Trigger event: [exact event name in analytics tool]
- Trigger condition: [logic, e.g., "User viewed Feature X page but did not create an object within 5 minutes"]
- Audience: [which user segment this applies to]
- Message type: [tooltip / modal / banner / slideout / hotspot]
- Timing: [immediate / after X seconds / next session]
- Headline: [max 8 words]
- Body copy: [max 30 words]
- CTA: [button text + destination]
- Dismissal behavior: [what happens if ignored — snooze, suppress, escalate to email]

Required triggers to design (customize copy for product context):

1. ACTIVATION STALL: User completes signup and setup step 1 but hasn't taken a second meaningful action within 4 hours.

2. EMPTY STATE ENGAGEMENT: User lands on core product area for the first time and sees an empty state without clicking the primary CTA within 60 seconds.

3. AHA MOMENT NEAR-MISS: User completes 4 of 5 steps toward aha moment but stops — most likely to churn without intervention.

4. FEATURE DISCOVERY: User has been active for 5+ days and still hasn't discovered a high-value feature that correlates strongly with retention. Nudge without overwhelming.

5. COLLABORATION MOMENT: User has created meaningful output but has not invited any teammates — prime moment for team expansion.

6. RETURN VISIT ORIENTATION: User returns after 3+ days away. Remind them where they left off and what's new.

7. DORMANCY WARNING: User hasn't logged in for 5 days within their trial window. Last-chance in-app recovery before email sequence fires.

8. PLAN LIMIT APPROACH: User's usage metric is at 75% of plan limit. Natural moment to introduce upgrade without pressure.

9. POWER USER SIGNAL: User has completed all 5 activation checklist items and has returned 3+ times this week. Surface advanced features and upgrade path.

10. TRIAL EXPIRY WARNING: User is 3 days from trial end and has not started upgrade flow. Urgency message without desperation.

---

DELIVERABLE 4: IN-APP UPGRADE & EXPANSION TRIGGERS

FEATURE GATE EXPERIENCE DESIGN:

For every feature gate encounter, the user experience must follow this framework:

Gate Message Formula:
1. Show what they almost got (not what they're blocked from)
2. Explain the specific outcome upgrading unlocks (one sentence, not a feature list)
3. Show social proof — "Used by [number] teams like yours" or "[Specific company] uses this to [outcome]"
4. One clear upgrade CTA + "Remind me later" option
5. No guilt, no countdown timers, no artificial scarcity

Provide complete copy for the 3 most likely feature gate moments in the product.

USAGE-BASED UPGRADE PROMPT SEQUENCE:

When user reaches 75% of plan limit:
- In-app banner with soft notification: exact copy, no modal
- Banner auto-dismisses after 24 hours

When user reaches 90% of plan limit:
- Persistent indicator in navigation + contextual modal when they try to use the affected feature: exact copy
- CTA to upgrade or "Learn about higher plans" (both options presented)

When user hits plan limit:
- Graceful degradation modal (never hard block without explanation): exact copy
- Two paths: Upgrade now (self-serve) or "Talk to us" (sales-assisted for enterprise deals)
- What NOT to do: never delete their work, never lock them out of existing data

SELF-SERVE UPGRADE FLOW DESIGN:
- The exact sequence of screens from "Upgrade" click to payment confirmation
- Pricing page in-app (vs. marketing site) — what to show and omit
- Objection handling copy at the payment screen: what concerns to pre-empt
- Post-upgrade celebration: what to show immediately after successful payment to reinforce the decision

---

DELIVERABLE 5: A/B TESTING ROADMAP (90-DAY PLAN)

For each experiment, provide:

Experiment name | Hypothesis | Control (current state) | Variant | Primary metric | Secondary metrics | Minimum sample size | Test duration | Decision framework

REQUIRED EXPERIMENTS TO PRIORITIZE:

Experiment 1 (Days 1-30): Welcome Experience
- Test: Personalized onboarding track (based on signup micro-survey) vs. universal onboarding
- Hypothesis: Users who receive a role-matched onboarding experience will reach their first value moment 30% faster than users who see the same generic flow
- Primary metric: Activation rate (aha moment completion within 7 days)

Experiment 2 (Days 1-30): First Action Optimization
- Test: Task-oriented first screen ("Let's create your first [X]") vs. exploration-first ("Here's what you can do")
- Hypothesis: Directing new users to a specific, achievable first action will increase Day 1 activation checkpoints by 25%
- Primary metric: First value moment completion rate within first session

Experiment 3 (Days 15-45): Activation Checklist
- Test: 5-item checklist with progress bar (visible) vs. no checklist (users explore freely)
- Hypothesis: Explicit progress tracking will increase 7-day activation completion rate by 15 percentage points
- Primary metric: 7-day activation rate (all 5 checklist items complete)

Experiment 4 (Days 30-60): Upgrade Trigger Timing
- Test: Usage-limit upgrade prompt at 75% vs. at 90% of plan capacity
- Hypothesis: Earlier upgrade prompts (75%) will generate more upgrade conversations while success is top of mind, resulting in 20% more upgrades before limit is hit
- Primary metric: Upgrade conversion rate per plan-limit session

Experiment 5 (Days 60-90): Social Proof Placement
- Test: Customer proof point displayed in feature gate modal vs. no proof point
- Hypothesis: Relevant peer validation at the upgrade decision moment will increase upgrade conversion by 12%
- Primary metric: Modal-to-upgrade conversion rate

STATISTICAL GUIDANCE:
- Minimum detectable effect: 10 percentage points on activation rate, 5 percentage points on conversion rate
- Significance threshold: 95% confidence (p < 0.05) before declaring a winner
- Never run more than 2 simultaneous experiments on the same user population
- Segment all results by: new signup cohort, persona, company size, source channel

---

DELIVERABLE 6: ACTIVATION METRICS COMMAND CENTER

WEEKLY ACTIVATION REVIEW METRICS (Monday, 9am):

Metric 1: New Signup Activation Rate (7-day)
- Formula: Users who completed aha moment event / total signups 7 days ago × 100
- Green: >40% | Yellow: 25-39% | Red: <25%
- Data source: Mixpanel funnel, filtered to signups from 7 days ago
- Decision rule: If Red, audit the most common exit point in the onboarding funnel by segment

Metric 2: Time-to-First-Value (median hours)
- Formula: Median time (in hours) from account creation to aha moment event, rolling 7-day cohort
- Green: <24 hours | Yellow: 24-72 hours | Red: >72 hours
- Decision rule: If Red, check whether new signups are stalling pre-setup or pre-value-moment

Metric 3: Day 1 / Day 3 / Day 7 Retention
- Formula: % of new signups who return to the product on Day 1, Day 3, and Day 7
- Green benchmarks: D1 >50%, D3 >30%, D7 >20%
- Decision rule: D1 drop = signup-to-first-session friction; D3 drop = failed first value delivery; D7 drop = habit formation failure

Metric 4: Activation Funnel Drop-off by Stage
- Format: Stage 1 completion % → Stage 2 → Stage 3 → Stage 4 → Stage 5 (waterfall view)
- Review for the biggest single drop-off step — that's this week's experiment hypothesis
- Segment by persona, company size, and signup source every Monday

Metric 5: In-App Message Engagement Rate
- Formula: Users who clicked CTA on any in-app message / users who saw the message × 100
- Green: >15% CTR | Yellow: 8-14% | Red: <8%
- If Red on any specific trigger: audit copy and timing; replace within 2 weeks maximum

Metric 6: Feature Adoption Depth (30-day cohorts)
- Formula: % of activated users who have used 3+ core features within 30 days of activation
- Green: >55% | Yellow: 35-54% | Red: <35%
- Decision rule: If Red, feature discovery triggers are underperforming — redesign contextual nudge sequence

Metric 7: Trial-to-Paid Conversion Rate
- Formula: Users who converted to paid / trials that expired or converted × 100 (by cohort start date)
- Green: >25% | Yellow: 15-24% | Red: <15%
- Industry benchmark: SaaS median is ~17%; PLG-optimized products target 25-35%

Metric 8: PQL (Product-Qualified Lead) to Close Rate
- Formula: PQLs routed to sales / PQLs that converted to paid within 30 days × 100
- Green: >30% | Yellow: 15-29% | Red: <15%
- Decision rule: If PQL definition is correct but close rate is low, the hand-off from product to sales is broken — audit the sales routing and outreach timing

MONTHLY DEEP-DIVE METRICS:
- Activation rate by acquisition channel (organic search, paid, referral, direct): identify highest-quality traffic sources
- Cohort NPS at Day 30 for activated vs. non-activated users: quantify the activation impact on sentiment
- Revenue per activated user vs. revenue per non-activated converted user: justify activation investment
- Experiment win/loss log: which tests produced results, which did not, and what the cumulative activation rate improvement has been

OUTPUT FORMAT:
All email, tooltip, modal, and in-app copy must be complete and production-ready. The only placeholders should be product-specific variable fields like [Product Name], [Feature Name], [First Name], [Number]. Flag which steps require product engineering vs. can be configured directly in Pendo / Appcues / Chameleon with no-code tooling. Flag which experiments require a feature flag infrastructure vs. can be run natively in your analytics tool.

## Example Input/Output

**Input Example:**

Company: Contractly — AI-powered contract management SaaS for mid-market legal and procurement teams. 14-day free trial, no credit card. Monthly signups: 340. Current activation rate: 28% (activation = user creates and executes at least one contract using AI clause extraction within 7 days). Trial-to-paid: 16%. In-app tool: Appcues. Product analytics: Amplitude. Known friction: Users frequently sign up, upload one contract, get confused by clause tagging interface, and leave. Primary "aha moment" hypothesis: User sees AI-extracted clauses appear in real-time for the first time.

**Output Example (Partial):**

Aha Moment Definition — Contractly:

Primary aha moment: User uploads a contract AND sees at least 5 AI-extracted clauses populate in the clause library within 3 minutes of upload — confirmed by Amplitude event "clause_extraction_viewed" firing with property "clause_count >= 5."

Leading indicators (observable in first 24 hours that predict activation):
1. User uploads file within first session (not just views the upload page): 3.2x more likely to activate
2. User clicks on any extracted clause to view detail: 2.8x more likely to activate
3. User completes the two-field setup wizard (company name + contract type default): 2.1x more likely to activate

Behavioral correlation insight: Users who upload a contract AND click through to the clause detail view in their first session activate at 61% — vs. 12% for users who only browse the dashboard. The clause-click is your real leading indicator, not the upload.

---

Activation Checklist — Contractly (5 items):

1. ✓ Upload your first contract (try a real NDA or vendor agreement)
2. ✓ See your AI-extracted clauses (takes less than 90 seconds)
3. ✓ Flag one clause as "needs review"
4. ✓ Send the contract for e-signature
5. ✓ Invite a teammate to review a contract with you

Checklist design: Right-side collapsible panel (persistent across all pages), 32px wide collapsed. Completion percentage shown as circular progress ring. When 5/5 complete, trigger a confetti animation and unlock "Advanced Clause Library" feature (premium feature preview, not gated — activates 14-day advanced trial extension).

---

Empty State Design — Contracts Dashboard:

Headline: "Your AI contract analyst is ready"
Supporting copy: "Upload any contract and watch Contractly extract every key clause, date, and obligation in under 90 seconds."
Primary CTA: "Upload Your First Contract" [opens file picker, accepts PDF/DOCX/DOC]
Ghost CTA: "Try with a sample NDA" [one-click loads pre-uploaded example contract and runs AI extraction automatically]
Empty state illustration direction: A clean contract page with animated highlight boxes appearing over text — suggesting the AI discovery experience, not an empty void.

---

Behavioral Trigger #3 — Aha Moment Near-Miss:

Trigger event: "clause_extraction_viewed" NOT fired within 8 minutes of "contract_upload_completed"
Trigger condition: User uploaded a contract but has not viewed the clause output (likely confused or lost in the UI)
Audience: All trial users in Days 0-3
Message type: Slideout (bottom-right corner, non-blocking)
Timing: 8 minutes after upload, if clause view event has not fired
Headline: "Your contract analysis is ready"
Body copy: "Contractly finished extracting clauses from your upload. Click the contract to see what our AI found — usually 15-40 clauses with risk flags."
CTA: "View My Clauses" → routes directly to that specific contract's clause view
Dismissal: If dismissed, suppress for 24 hours; if not dismissed and no clause-view event in 30 minutes, escalate to email "Did you see your analysis?" (subject line: "Your Contractly analysis is waiting")

Appcues implementation: Create a "Flow" with slideout style, set to trigger on "contract_upload_completed" event followed by 8-minute timer using Appcues Launchpad, suppress if "clause_extraction_viewed" fires in the interim. Audience segment: "Trial Users" group, Days 0-3.

---

A/B Test 1 — Personalized Onboarding Track Results (Hypothetical 30-day):

Control (universal onboarding): 28% activation rate, 340 new signups, 95 activated users
Variant (role-based onboarding — Legal Ops track vs. Procurement track vs. General Counsel track):
- Legal Ops track: 39% activation (highest — role-specific empty state template "Standard Legal Ops NDA" pre-loaded)
- Procurement track: 36% activation
- General Counsel track: 33% activation
- Blended variant: 36% activation rate — statistically significant improvement of +8 percentage points (p=0.03)
Decision: Ship personalized tracks to 100% of new signups. Estimated impact at current signup volume: 27 additional activated users per month, $43,200 additional ARR at 16% trial-to-paid conversion and $10,800 ACV.

## Success Metrics
- Activation rate improvement: +12-20 percentage points within 90 days of full system implementation
- Time-to-first-value reduction: 40%+ faster aha moment delivery (e.g., 48 hours → 28 hours median)
- Trial-to-paid conversion: +6-10 percentage points within 90 days
- In-app message engagement: >15% CTR on behavioral triggers (industry baseline: 8-10%)
- Day 7 retention lift: +8-12 percentage points for users who receive the optimized onboarding vs. control

## Related Prompts
- [Customer Onboarding Intelligence System](../Customer-Onboarding-&-Activation/Customer-Onboarding-Intelligence-System.md)
- [Product Adoption Acceleration & Feature Engagement Engine](../Customer-Onboarding-&-Activation/Product-Adoption-Acceleration-&-Feature-Engagement-Engine.md)
- [Freemium Conversion & PQL Nurture Automation Engine](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Freemium-Conversion-&-PQL-Nurture-Automation-Engine.md)
- [Product-Led Growth PLG Flywheel & Viral Loop Design Engine](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Product-Led-Growth-PLG-Flywheel-&-Viral-Loop-Design-Engine.md)

## Integration Tips
- **Pendo:** Use Pendo Guides to build the product tour (tooltip sequences), activation checklist (Resource Center), and all behavioral triggers (Guide Rules targeting specific event conditions). Sync Pendo data to Salesforce or HubSpot via native integration to automatically set PQL status when activation milestone events fire. Use Pendo Analytics to measure funnel completion rates without leaving the tool.
- **Appcues:** Build onboarding flows using Appcues Flows for the product tour and behavioral triggers. Use Appcues Checklists for the activation checklist — it natively renders the progress ring UI. Connect Appcues to Amplitude via the Amplitude Destination integration to unify in-app engagement data with full product analytics. Use Appcues Experiences to run A/B tests on onboarding variants natively.
- **Chameleon:** Use Chameleon Tours for the product tour and Launchers for the activation checklist. Chameleon's "Microsurvey" feature handles the signup segmentation questions directly in-app post-signup, enabling role-based onboarding without engineering work. Connect Chameleon to Segment to pipe events into any downstream analytics or CRM tool.
- **Mixpanel / Amplitude:** Build an "Activation Funnel" report with each milestone as a step. Set alerts for when the funnel's Day 7 completion rate drops more than 5 percentage points week-over-week. Create a "New Signups" user cohort and compare behavior across the funnel between activated vs. not-activated users to identify the specific drop-off point for each new onboarding experiment.
- **Intercom:** Use Intercom's Product Tours for lightweight tooltip sequences (better for simpler products than Pendo/Appcues). Use Intercom Outbound Messages with "In-app" channel for behavioral triggers. The advantage: Intercom unifies in-app, email, and chat triggers so dormancy interventions can escalate from in-app to email to live chat in one automated workflow.
- **HubSpot / Salesforce:** Create a custom "Activation Stage" property (values: Not Started / Setup / First Value / Habit Formation / Expansion Ready / Converted). Update this property automatically via webhook from your analytics tool when each milestone event fires. Use this property to: enroll users in the correct email nurture sequence, create PQL deals when Stage = "Expansion Ready," and route to sales for high-ACV trial accounts.
- **Zapier / Make (no-code integration):** If your in-app tool and CRM don't have a native integration, use Zapier to: (1) Watch for activation milestone events in Amplitude/Mixpanel → (2) Update a HubSpot contact property → (3) Enroll in the appropriate email sequence. This 3-step Zap handles 90% of the CRM sync required for a functional PLG+sales hybrid motion.

## Troubleshooting
- **Problem:** In-app tours are being dismissed immediately by users who find them intrusive, and engagement rates are below 5%.
  **Solution:** The tour is firing too early (before the user has formed any mental model of the product) or covering too many features (cognitive overload). Apply two fixes simultaneously: (1) Delay tour trigger to fire only after the user completes one self-directed action, not immediately on login — this signals they have some orientation and are more receptive; (2) Reduce the tour to maximum 3 steps covering only the single most-important action leading to the aha moment. Users who dismiss a 3-step tour lose less value than users who dismiss a 7-step tour.

- **Problem:** Activation rate improves but trial-to-paid conversion remains flat, suggesting activated users are not becoming buyers.
  **Solution:** Activation is necessary but not sufficient for conversion — the issue is usually that your activation definition is too shallow (users are hitting the metric without experiencing deep value) or that the upgrade prompt is firing too late/too early relative to peak intent. Audit two things: (1) Recheck whether your "activated" cohort is actually retaining at Day 30 (if not, your aha moment definition is wrong — surface-level activity, not real value delivery); (2) Run the Experiment 4 timing test — move upgrade prompts to fire 24 hours after activation instead of at plan limit — this catches users at peak enthusiasm before momentum fades.

- **Problem:** Different user personas are activating at very different rates (e.g., Legal Ops at 45% but General Counsel at 18%) and it's unclear how to address without building fully separate products.
  **Solution:** Persona-specific activation gaps almost always come from a mismatch between what the persona expects and what your default empty state and onboarding show them. You do not need separate products — you need persona-specific empty state templates, first-session CTAs, and onboarding checklists. Implement the signup micro-survey (2 questions: role + primary use case) and use those answers to select the appropriate onboarding track. The content is 70% identical — only the examples, templates, and first recommended action differ. This change can be implemented in Appcues or Chameleon without any engineering work in 1-2 days.

## Version History
- v1.0: Initial creation (auto-generated)
