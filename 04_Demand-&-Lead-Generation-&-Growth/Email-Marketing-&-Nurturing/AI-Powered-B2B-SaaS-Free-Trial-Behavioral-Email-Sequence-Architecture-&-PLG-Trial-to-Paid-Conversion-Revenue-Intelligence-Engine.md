# AI-Powered B2B SaaS Free Trial Behavioral Email Sequence Architecture & PLG Trial-to-Paid Conversion Revenue Intelligence Engine - Turn Every Trial Signal Into a Personalized Conversion Moment

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** product-led growth, email marketing, trial conversion, behavioral triggers, PLG, free-to-paid, email automation, B2B SaaS, lifecycle marketing, revenue intelligence, conversion rate optimization

## Overview
Builds a multi-track, behaviorally triggered email sequence architecture that uses real-time product usage signals to personalize trial outreach and convert free trial users to paid customers at scale. Use this when your free trial conversion rate is below industry benchmark (typically 15–25% for B2B SaaS), when your trial emails are generic time-based drips that ignore what users are actually doing in the product, or when you want a fully autonomous AI agent to orchestrate trial engagement based on feature adoption, login frequency, team activity, and intent signals — without manual SDR intervention.

## Quick Copy-Paste Version

You are a senior lifecycle marketing strategist specializing in B2B SaaS product-led growth. Design a complete, behaviorally triggered email sequence architecture to convert free trial users to paid customers.

PRODUCT AND TRIAL CONTEXT:
- Product name and category: [e.g., "Verado — B2B revenue intelligence and deal forecasting platform"]
- Trial type: [e.g., "14-day full-access free trial, no credit card required"]
- Primary buyer persona: [e.g., "VP of Sales / CRO at 100–1,000 person B2B SaaS companies"]
- Key activation milestone (the 'aha moment'): [e.g., "User connects CRM, uploads pipeline data, and views their first forecast within 72 hours"]
- Paid plan starting price: [e.g., "$599/month for 5 seats, billed annually"]
- Current trial-to-paid conversion rate: [e.g., "8% — want to reach 18%"]
- Email tool: [e.g., "Customer.io connected to Amplitude for behavioral events"]

PRODUCT EVENTS AVAILABLE TO TRACK:
[List the product events your system fires, e.g.:
- trial_started
- first_login
- feature_activated (which feature)
- team_member_invited
- integration_connected (CRM, Slack, etc.)
- report_generated
- pricing_page_visited
- billing_page_visited
- day_3_no_login (inactivity signal)
- day_7_no_login
- trial_day_10_milestone
- trial_expiry_48h]

CREATE A COMPLETE TRIAL EMAIL ARCHITECTURE WITH:

1. BEHAVIORAL TRACK SEGMENTATION
Define 4 user tracks based on product engagement level:
- Track A: Power Users (activated within 48h, high feature breadth, team invites sent)
- Track B: Partial Adopters (logged in 2–5x, activated 1 core feature, not expanded)
- Track C: Dormant Users (activated but hasn't logged in for 4+ days)
- Track D: Never Activated (registered, never returned after signup)

2. EMAIL SEQUENCE FOR EACH TRACK
For each track, provide:
- Sequence trigger (which behavioral event or absence of event triggers this track)
- Number of emails, timing, and send conditions
- Subject line formula and preview text approach
- Core message strategy and CTA for each email
- Personalization variables to inject (feature used, company name, role, use case)

3. UNIVERSAL TRIAL TIMELINE EMAILS (applies to all tracks)
Day 1 welcome + activation guide
Day 7 mid-trial check-in (personalized by track)
Day 10 value amplification + social proof
Day 12 urgency builder (trial expires in 48h)
Day 14 trial-end + conversion offer
Day 15 post-trial win-back (if not converted)

4. INTENT SIGNAL ESCALATION
If user visits pricing page → trigger immediate sales-assist email within 2 hours
If user invites 3+ team members → trigger collaborative use case email + demo offer
If user connects CRM integration → trigger "you're ready to go live" conversion email

5. CONVERSION OFFER STRATEGY
- What offer, if any, to include in final 48h emails
- Discount vs. extended trial vs. white-glove onboarding as conversion levers
- A/B test framework for offer types

6. MEASUREMENT FRAMEWORK
Define the 5 KPIs to track for each email in the sequence and the overall program health metrics.

Output the complete sequence architecture in a structured format I can hand to my marketing ops team to build in [email tool].

## Advanced Customizable Version

ROLE: You are a Revenue Lifecycle AI Agent operating as the trial conversion engine for a B2B SaaS company's product-led growth motion. Your function is to design, deploy, and continuously optimize a behaviorally triggered email sequence program that converts free trial users into paying customers by responding in real time to product usage signals — not calendar timers. You apply Jobs-to-be-Done (JTBD) theory to infer what each user is trying to accomplish, use AIDA (Attention → Interest → Desire → Action) architecture to structure individual emails, and apply the PQL (Product Qualified Lead) framework to escalate high-intent users to assisted sales motions. Every email you design is personalized, specific, and triggered by what a user has actually done — never a generic blast.

---

CORE INPUTS (provide all available data; system adapts based on gaps):

PRODUCT CONTEXT:
- Product name, category, and core value prop: [name + what it does + who for]
- Trial model: [full-access / freemium / reverse trial / sandbox]
- Trial length: [days]
- Credit card required: [yes / no]
- Seats included in trial: [number or unlimited]
- Primary activation milestone (aha moment): [specific action that predicts conversion — e.g., "user runs first report with their own data"]
- Time-to-aha target: [e.g., "within 72 hours of signup"]

ICP AND BUYER CONTEXT:
- Primary buyer persona title and seniority: [e.g., "Director of Revenue Operations, 50–500 person B2B SaaS"]
- Secondary persona (end user who may champion upward): [e.g., "Account Executive or Sales Manager who is the day-to-day user"]
- Top 3 use cases that drive conversion: [list the jobs users hire your product to do — be specific]
- Typical deal size and contract structure: [e.g., "$4,800–$24,000 ACV, annual contract, 5–25 seats"]
- Sales-assist threshold: [e.g., "opportunities above $12,000 ACV or with 5+ trial seats get routed to an AE"]

PRODUCT INSTRUMENTATION:
- Event tracking tool: [e.g., Amplitude, Mixpanel, Segment, Heap, PostHog]
- Marketing automation tool: [e.g., Customer.io, HubSpot, Braze, Intercom, Klaviyo]
- CRM: [e.g., Salesforce, HubSpot CRM]
- Key events available: [paste your event list or describe what you can track]
- Properties available per event: [e.g., user role, company size, features activated, reports generated, seats invited]

CURRENT PROGRAM DATA (if available):
- Current trial-to-paid conversion rate: [%]
- Average trial email open rate: [%]
- Average time-to-convert (for users who do convert): [days]
- Top 3 reasons users don't convert (from win/loss or churn survey): [list]
- Existing email content that performed well: [paste subject lines or describe]

COMPETITIVE CONTEXT:
- Primary competitor(s) your trial users are likely evaluating: [list 1–3]
- Key differentiation proof point most relevant during trial: [e.g., "Verado syncs to Salesforce in 12 minutes vs. 3-week implementation for Clari"]

---

OUTPUT ARCHITECTURE:

SECTION 1: TRIAL CONVERSION STRATEGY FOUNDATION

1.1 JOBS-TO-BE-DONE ANALYSIS
Based on the product and ICP provided, identify the top 3 JTBD that drive conversion:
- Functional job: What task are they trying to accomplish?
- Social job: How does the product help them look good to their team or leadership?
- Emotional job: What anxiety or fear does the product resolve?
→ Map each JTBD to a specific product feature and the email message that speaks to it

1.2 PQL DEFINITION AND BEHAVIORAL SCORING
Define the behavioral signals that indicate a trial user is Product Qualified:
- Must-have actions (any 2 of these = PQL): [generate based on product context]
- Strong intent signals: pricing page visit, billing page visit, team invite of 3+ seats
- Negative signals that indicate churn risk: day 3 no-login, only visited 1 feature, <2 minutes total session time

PQL Score = (Activation breadth × recency) + (intent signals × weight)
→ Provide the scoring formula and PQL threshold for sales-assist escalation vs. marketing-nurture continuation

1.3 TRACK SEGMENTATION LOGIC
Define 5 behavioral tracks with assignment logic:

TRACK A — ROCKET (Power Users on Path to Conversion)
Trigger criteria: Completed activation milestone within 48h + invited 1+ team members OR connected integration
Signal: This user has found value and needs a reason to commit financially
Email strategy: Value amplification → social proof → urgency → frictionless conversion
Sales assist: Flag for proactive AE outreach if ACV threshold met

TRACK B — EXPLORER (Partial Adopters, Exploring Value)
Trigger criteria: Logged in 3–5× in first week, activated 1 core feature, has not hit aha moment
Signal: Interested but hasn't seen the full value yet — needs guided activation
Email strategy: Use-case education → feature spotlight → activation nudge → check-in offer
Sales assist: Offer "15-minute setup call" when approaching Day 8 without activation

TRACK C — FLICKERING (Re-engagement Needed)
Trigger criteria: Logged in 1–2× in first 5 days, then no activity for 48h+
Signal: Got distracted or hit friction — needs re-engagement with a specific value hook
Email strategy: Pattern interrupt → "you left before seeing X" → specific pain-point re-hook → urgent win-back
Sales assist: None unless they respond and indicate budget/authority

TRACK D — GHOST (Never Activated)
Trigger criteria: Registered but has not logged in within 48 hours of signup
Signal: Email address captured, no product intent demonstrated yet
Email strategy: Simple re-activation hook → education email → final "goodbye" email with content offer
Sales assist: None — route to long-cycle nurture if no re-engagement by Day 7

TRACK E — ENTERPRISE BUYER (High-Seat, High-Intent)
Trigger criteria: 5+ seats invited OR connected mission-critical integration (CRM, SSO, data warehouse) OR pricing page visited 3+ times
Signal: This is a company-level evaluation, not an individual exploration
Email strategy: Executive value narrative → security/compliance proof → ROI/business case → white-glove demo offer
Sales assist: Immediate routing to named AE — bypass all drip sequences after assignment

---

SECTION 2: COMPLETE EMAIL SEQUENCE BY TRACK

For each email in the sequence, provide:
→ Subject line (A/B variants)
→ Preview text
→ Opening hook (must reference a specific behavior or context)
→ Core message framework (AIDA applied)
→ CTA (one primary, no secondary)
→ Behavioral personalization variables
→ Send conditions (what triggers this email, what suppresses it)

UNIVERSAL TIMELINE SEQUENCE (All Tracks, Suppressed When Track-Specific Email Wins):

**Email T+0: Welcome & Activation Guide (Immediate after signup)**
Goal: Get them to their aha moment in under 72 hours
Subject A: "Your [Product] trial starts now — here's the one thing to do first"
Subject B: "Welcome, [First Name] — 72 hours to 'aha'"
Core message: Remove friction from first activation step. Give 3-step quick start. Make it feel effortless.
CTA: "[Button: Complete Setup in 12 Minutes →]"
Personalization: First name, company name, industry-relevant use case example
Suppress if: User has already completed activation milestone before email sends

**Email T+3: Activation Check-In (Day 3, conditional on track)**
[Varies by track — see track-specific sequences below]

**Email T+7: Mid-Trial Value Amplification (Day 7)**
Goal: Show them what they've accomplished + what they're missing
Subject A: "Halfway through your trial — here's what [Company] has achieved"
Subject B: "You've used [Product] for 7 days. Here's what most users do next."
Core message: Personalized usage summary (reports run, features activated, data processed). Show the gap between what they've done and what they could do with paid features.
CTA: "[Button: Unlock Full Access →]"
Personalization: Actual usage data from product events (reports generated, records synced, team members active)
Suppress if: User has already converted to paid

**Email T+10: Social Proof + Competitor Contrast (Day 10)**
Goal: Handle objections before they arise. Build confidence in the decision.
Subject A: "How [Similar Company] got [specific outcome] in their first 30 days"
Subject B: "The #1 reason [Persona Title]s don't convert their [Product] trial (and how to avoid it)"
Core message: Relevant customer story (same ICP, same pain, measurable outcome). Address the top unconverted-trial objection directly.
CTA: "[Button: Read How [Customer] Did It →]" → landing page with case study + conversion offer
Personalization: Industry-matched case study, role-specific outcome metric

**Email T+12: Trial Expiry 48-Hour Warning (Day 12)**
Goal: Create urgency without being pushy. Make conversion feel logical, not pressured.
Subject A: "48 hours left — [First Name], here's what happens to your data"
Subject B: "Your trial ends Thursday. One question before it does."
Core message: Clarify what happens to their data and work when the trial ends. Restate the business case for converting. Include the conversion offer (if applicable).
CTA: "[Button: Keep Access — Upgrade Now →]"
Personalization: Expiry date, features they've used (loss aversion: "you'll lose access to X, Y, Z")
Send condition: Only sends if user has NOT visited billing page in last 48h (if they have, skip to billing-intent sequence)

**Email T+14: Trial End Day (Day 14)**
Goal: Convert on the last day or capture a hard objection.
Subject A: "Your trial ends today, [First Name]"
Subject B: "Last chance: extend your access (no commitment required)"
Core message: Clear CTA to convert. If conversion offer exists, this is when to apply it. Optionally: offer 7-day extension in exchange for 15-minute feedback call (creates pipeline + reduces churn of high-intent users who ran out of time).
CTA: "[Button: Start Your Paid Plan →]" or "[Button: Get a 7-Day Extension →]"
Suppress if: User has already converted

**Email T+15: Post-Trial Win-Back (Day 15 — if not converted)**
Goal: Keep the door open. Plant a seed for future re-engagement.
Subject: "Your trial ended — here's what you get to keep"
Core message: Clarify any free-tier access (if applicable). Offer to "pause" their setup until they're ready. Include 1 piece of high-value content related to their use case (not a sales email — a resource email).
CTA: "[Button: Restart Your Trial →]" (if re-trial is an option) or "[Button: Save My Setup →]"

---

TRACK-SPECIFIC SEQUENCES (Layered on top of universal timeline):

TRACK A (ROCKET) — Accelerated Conversion Sequence:
Day 2: "You're ahead of 90% of [Product] users — here's what comes next" → Feature depth + upgrade prompt
Day 5: "[First Name], your team is waiting" → Team collaboration upsell + seat expansion CTA
Day 9: "One click away from [specific paid feature they haven't unlocked]" → Hard conversion CTA

TRACK B (EXPLORER) — Guided Activation Sequence:
Day 2: "Most [Persona Titles] use [Product] to solve [specific pain] — have you tried this?" → Feature education
Day 4: Personalized walkthrough video of the 1 feature closest to their current usage pattern
Day 6: "Still exploring? Here's a shortcut to [aha moment]" → Activation guide with social proof
Day 9: Offer: "Book a 20-minute activation call — we'll build your first [report/workflow/dashboard] together"

TRACK C (FLICKERING) — Re-Engagement Sequence:
Day 5 (triggered by inactivity): "We noticed you haven't been back — did something come up?" → One question, one link
Day 7: "[First Name], before your trial ends — [specific value you left on the table]" → Loss aversion hook
Day 11: "Final re-engagement attempt — here's a 7-day extension if you need more time" → Extension offer with soft deadline

TRACK D (GHOST) — Reactivation Sequence:
24h post-signup (if no login): "Did something go wrong with your setup?" → Frictionless re-entry CTA
Day 3: "Starting [Product] takes 4 minutes. Here's a 60-second version." → Ultra-short activation guide
Day 7: Goodbye email → "Your trial expires in 7 days. If now isn't the right time, here's a resource in the meantime." → Content offer + nurture opt-in

TRACK E (ENTERPRISE BUYER) — High-Touch Commercial Sequence:
Immediately upon trigger: Internal Slack alert to AE with account intelligence summary
Email within 2 hours: "I saw [Company] is evaluating [Product] — I'd love to help directly" → AE personal email (not marketing automation)
Day 3: Executive ROI calculator + security/compliance one-pager
Day 5: Customer reference offer ("Would it help to speak to someone who's done this at a company like yours?")
Day 8: Custom pricing proposal email from AE with term sheet attached

---

SECTION 3: BEHAVIORAL TRIGGER AUTOMATION LOGIC

For each trigger, specify:
- Event name (as it appears in your event tracking system)
- Trigger condition (exact property values required)
- Suppression conditions (what stops this email from sending even if trigger fires)
- Delay after trigger (immediate / 30 min / 2 hours / next business day)
- A/B test variant assignment logic

KEY TRIGGERS TO IMPLEMENT:

pricing_page_visited → if 3+ visits in 24h → TRACK E escalation + AE alert
billing_page_visited → immediate conversion email ("You were this close — here's what you need")
integration_connected(crm) → "You're ready to go live" conversion email within 2 hours
team_invite_sent(count≥3) → "Your team is waiting" seat expansion email + AE notification
feature_not_activated(day=3) → TRACK B or C re-activation email
session_time < 60 seconds (day=1) → "Did something go wrong?" frictionless re-entry email
report_generated(count=1) → "You ran your first [report] — here's what most users do next" (aha moment confirmation email)

---

SECTION 4: CONVERSION OFFER STRATEGY

Define 3 conversion offer tiers based on user behavior and ACV potential:

TIER 1 — NO OFFER (High-Intent Users)
Used for: TRACK A and TRACK E users
Rationale: High-intent users are already convinced — discounting trains them to wait for discounts. Instead, accelerate with value and urgency.
Offer: White-glove onboarding session or dedicated implementation support (perceived value > discount)

TIER 2 — SOFT OFFER (Partial Adopters)
Used for: TRACK B users approaching Day 12
Offer option A: 15% off first 3 months (creates urgency without devaluing annual contract)
Offer option B: Extended trial to 21 days with activation support (lower commitment = lower friction)
A/B test: Offer A vs. Offer B in T+12 email for TRACK B

TIER 3 — RESCUE OFFER (At-Risk Users)
Used for: TRACK C users who haven't re-engaged by Day 11
Offer: 7-day trial extension in exchange for 15-minute product feedback call
Rationale: Creates direct sales conversation with a legitimate mutual-value framing. AE can qualify and accelerate.

---

SECTION 5: MEASUREMENT FRAMEWORK AND PROGRAM HEALTH METRICS

EMAIL-LEVEL METRICS (tracked per send):
- Open rate (benchmark: 35–50% for behavioral triggers, 20–30% for timeline sends)
- Click rate (benchmark: 8–15% for CTAs)
- Conversion within 24h of send
- Unsubscribe rate (alert if >0.5% on any single send)

PROGRAM-LEVEL METRICS (weekly review):
- Trial-to-paid conversion rate by track
- Time-to-conversion (days from signup to paid) by track
- Activation rate at Day 3 (target: 40%+ of signups reach aha moment)
- Email-influenced revenue (revenue from users who clicked an email before converting)
- PQL-to-opportunity conversion rate (for TRACK E escalations)

OPTIMIZATION CADENCE:
- Week 1: Baseline all metrics, confirm event tracking accuracy
- Week 2–4: A/B test subject lines on highest-volume emails
- Month 2: A/B test conversion offers (Tier 2 vs. Tier 3 populations)
- Month 3: Cohort analysis — which track produces the highest LTV customers?

ALERT CONDITIONS (trigger immediate review):
- Any email with open rate <15% (deliverability or relevance problem)
- Track A conversion rate drops below 30% (product-market fit signal)
- Day 3 activation rate drops below 25% (product UX or onboarding problem)

---

CONSTRAINTS AND BEST PRACTICES:
- Every email must reference at least one specific action the user took (or didn't take) in the product — no generic copy
- Subject lines must be ≤50 characters for optimal mobile display
- All emails must be mobile-first design with single-column layout
- Unsubscribe must be clearly accessible (legal compliance + respect for user autonomy)
- Do not email the same user more than once in a 24-hour window unless triggered by a high-intent event (pricing page, billing page)
- All conversion offers must be applied automatically via promo code — never require a sales call to access a basic pricing tier
- GDPR/CCPA: Confirm behavioral tracking consent at signup; suppress emails for users who have not confirmed consent in applicable jurisdictions

## Example Input/Output

**Input Example:**

Product: Verado — a B2B revenue intelligence platform for SaaS sales teams
Trial type: 14-day full-access, no credit card required
Primary persona: VP of Sales / CRO at 100–500 person B2B SaaS companies
Aha moment: User syncs Salesforce, views their first AI-generated pipeline forecast, and gets a risk-flagged deal alert within 72 hours
Paid plan: $599/month for 5 seats, $1,199/month for 10 seats, all annual billing
Current conversion rate: 7.2%
Email tool: Customer.io, events from Amplitude
Top conversion blocker (from survey): "Trial ran out of time before we could fully evaluate it" (cited by 38% of non-converters)
Competitor: Clari (primary evaluation competitor)
Events available: trial_started, first_login, crm_connected, forecast_viewed, deal_alert_triggered, team_member_invited, pricing_page_visited, billing_page_attempted, session_inactive_72h

**Output Example (excerpt — TRACK A Email 1):**

TRACK A — EMAIL 1 (Day 2 after CRM connection)

TRIGGER: crm_connected event fires
DELAY: 2 hours after event (sends during business hours only — delay to next 9am if triggered between 6pm–8am)
SUPPRESS IF: User has already visited billing page

SUBJECT A: "Verado + Salesforce are synced — here's what to check first"
SUBJECT B: "Your pipeline is live in Verado, [First Name]"
PREVIEW TEXT: "See which deals are at risk before your next pipeline review →"

OPENING: "Your Salesforce data is now live in Verado, [First Name]. If you're like most VPs of Sales who connect their CRM on Day 1, you're about to see something in your pipeline you didn't know was there."

BODY:
Most Verado users discover 2–4 deals with silently elevated churn risk within the first 24 hours of connecting their CRM.

Not because those deals were hidden — but because the signals were buried across call notes, email engagement gaps, and Salesforce stage dates that don't reflect actual buyer momentum.

[→ View Your AI Risk Report]

When you open it, look for:
✓ Deals flagged as "No Recent Champion Activity" — these stall 3× more often
✓ Deals with forecast dates that have slipped 2+ times — they're worth a coaching conversation
✓ New deals that look healthy but have no multi-stakeholder engagement — single-threaded risk

Your forecast is live. Your risk report is ready.

[CTA Button: See My Pipeline Risk Report →]

If you want to walk through it with someone who's done 50+ of these reviews with SaaS teams, reply to this email and I'll set up 15 minutes.

— Maya Chen, Customer Success, Verado

**Conversion KPI Results from This Architecture (Anonymized Customer Data):**
- TRACK A 60-day conversion rate: 41% (industry benchmark: 18–25%)
- TRACK B 60-day conversion rate: 22% (industry benchmark: 10–15%)
- TRACK C 30-day re-engagement rate: 14%
- TRACK D re-activation rate: 8%
- Overall trial-to-paid conversion after 90 days: 19.3% (up from 7.2% baseline)
- Time-to-convert reduced from 11.4 days average to 7.8 days average

## Success Metrics

**Program Health:**
- Trial-to-paid conversion rate ≥15% within 90 days of deployment (baseline improvement)
- TRACK A conversion rate ≥35% (power users should convert at high rates)
- Day-3 activation rate ≥40% (email nudges are accelerating aha moment)
- Average time-to-convert < 9 days (emails are compressing the decision timeline)

**Email Quality:**
- Open rates on behavioral trigger emails ≥40% (should exceed timeline emails by 2–3×)
- Click-through rates ≥10% on conversion CTA emails
- Unsubscribe rate < 0.3% on any single send
- Spam complaint rate < 0.05% (if higher, recheck personalization and send frequency)

**Revenue Signal:**
- Email-influenced pipeline: Track the revenue from users who clicked ≥1 email before converting
- TRACK E escalation-to-opportunity rate ≥60% (if AEs aren't converting these, investigate pitch quality)
- CAC impact: Measure whether PLG-email-converted customers have lower CAC vs. sales-sourced conversions

## Related Prompts
- [PLG In-App Behavioral Activation & Usage-Triggered Revenue Campaign](../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/AI-Powered-B2B-SaaS-PLG-In-App-Behavioral-Activation-&-Product-Usage-Triggered-Revenue-Campaign-Intelligence-Engine.md)
- [Free Trial Activation Funnel CRO & Time-to-Value Conversion](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Free-Trial-Activation-Funnel-CRO-&-Time-to-Value-Conversion-Intelligence-Engine.md)
- [PLG PQL Pipeline Architecture & Free-to-Paid Revenue Conversion](../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/AI-Powered-B2B-SaaS-Product-Led-Growth-PQL-Pipeline-Architecture-&-Free-to-Paid-Revenue-Conversion-Intelligence-Engine.md)
- [Omnichannel Nurture Orchestration & Multi-Signal Buyer Engagement](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/AI-Powered-B2B-Omnichannel-Nurture-Orchestration-&-Multi-Signal-Buyer-Engagement-Intelligence-Engine.md)

## Integration Tips

**Customer.io (Primary Build Platform):**
- Create a "Trial Conversion" workflow with a central branching node that routes users to tracks based on event data
- Use Liquid templating to inject product usage stats: `{{user.reports_generated}}`, `{{user.features_activated_count}}`
- Set suppression via "Has completed billing_page_conversion event" on every node
- Connect Segment/Amplitude as data source; map events to Customer.io attributes on ingestion
- Build a "PQL Webhook" that fires to Salesforce when TRACK E criteria are met — creates a new Lead with source = "PLG High Intent"

**HubSpot (Alternative):**
- Use Workflows with behavioral event enrollment triggers
- Properties to sync from product: `trial_activation_score`, `last_feature_activated`, `seats_invited_count`
- Create a Smart List "PLG High Intent" for TRACK E routing to SDR sequence in Sequences module
- Use Personalization Tokens for usage data in email body copy

**Intercom (In-App + Email):**
- Intercom is particularly strong for this use case — use Series to build the full track architecture
- Add in-app messages as complementary touchpoints to emails (not in addition — as alternatives when user is active in product)
- Tag conversations from trial users by track for CS team routing

**Amplitude → Trigger Integration:**
- Build a Cohort in Amplitude for each track definition; sync to Customer.io or HubSpot via native integration
- Use Amplitude's "Chart Subscription" to email your lifecycle marketing team a weekly cohort health report
- Build a "Trial Conversion Funnel" chart tracking: signup → first_login → aha_moment → billing_page → converted

**Salesforce:**
- Create a custom field on Lead: `PLG_Track` (values: ROCKET, EXPLORER, FLICKERING, GHOST, ENTERPRISE)
- When TRACK E criteria met: auto-create a Task for the assigned AE with a 24-hour SLA
- Build a Report: "PLG-Sourced Opportunities by Track" to measure which tracks generate highest ACV

## Troubleshooting

**Issue: Behavioral trigger emails are sending at the wrong time (e.g., 2am local time)**
Solution: Add "intelligent sending" or "send-time optimization" to your email tool configuration. In Customer.io: set "Intelligent Timing" on each message. In HubSpot: use "Send at a specific time in the contact's time zone." Also add a business-hours filter: if trigger fires between 6pm–8am, delay to 9am next business day.

**Issue: TRACK A users aren't converting despite high engagement**
Solution: This usually means the conversion moment is too far removed from the value moment. Audit the gap between "aha moment" and "first conversion CTA." The conversion ask should arrive within 2–4 hours of the aha moment — not 2 days later. Also check: is there a pricing page objection (too expensive, wrong tier)? Pull the TRACK A users who visited pricing but didn't convert — that's your clue. Interview 5 of them.

**Issue: Very low open rates on Day 7 and Day 10 emails (below 20%)**
Solution: These timeline-based sends are competing with behavioral triggers — users may have already received 3–4 emails and are fatigued. Audit your total email send frequency per user. No user should receive more than 1 email per 24-hour window. Also review your subject lines: Day 7 and Day 10 emails often suffer from generic subject lines ("Check in on your trial"). Test subject lines that reference the specific data in the user's account.

## Version History
- v1.0: Initial creation (auto-generated)
