# AI-Powered B2B SaaS Product-Led Growth PQL Pipeline Architecture & Free-to-Paid Revenue Conversion Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, plg, product-led-growth, pql, free-trial, freemium, activation, conversion, saas, demand-gen, pipeline, revenue-expansion, user-onboarding, sales-assist

## Overview
This prompt enables B2B SaaS growth, demand generation, and marketing teams to design a fully AI-powered Product-Led Growth (PLG) pipeline engine — from PQL scoring model architecture and behavioral activation triggers, to automated upgrade sequences, sales-assist handoff orchestration, and expansion revenue motion design. Use it when you have a free trial or freemium product and are converting fewer than 15% of signups to paid, when your sales team is wasting time on low-intent product users, or when you need a systematic framework to turn product usage data into a predictable revenue pipeline without manual intervention.

## Quick Copy-Paste Version

You are a senior B2B SaaS product-led growth strategist with deep expertise in PQL scoring, free-to-paid conversion, and AI-powered user lifecycle automation. Design a complete PLG pipeline architecture for my product.

My company: [What we do — one sentence]
Business model: [Freemium / Free Trial / Reverse Trial / Usage-Based]
Product type: [e.g., collaboration tool, analytics platform, developer tool, CRM]
Monthly signups: [X free users per month]
Current free-to-paid conversion rate: [X%]
Average contract value: [ACV $X]
Ideal Customer Profile: [Job title, company size, industry]
"Aha moment" (the action that predicts conversion): [e.g., "user creates first report", "team invites 3+ members", "API call #1 made within 48 hours"]
Current tech stack: [Product analytics tool, CRM, marketing automation, email tool]

Design the following:

1. PQL SCORING MODEL — Define a Product-Qualified Lead scoring framework with 5–8 behavioral signals. For each signal: signal name, data source, weight (1–10), scoring rationale, and threshold that moves a user from "active" to "PQL." Define three PQL tiers: PQL-1 (self-serve ready), PQL-2 (growth plan candidate), PQL-3 (enterprise sales-assist required).

2. ACTIVATION PLAYBOOK — Map the 5-step activation sequence from signup to "aha moment." For each step: the action required, in-app trigger (modal/tooltip/email), copy direction, fallback if user skips, and the downstream revenue impact if activation succeeds vs. fails.

3. AUTOMATED UPGRADE SEQUENCES — Design 3 email + in-app upgrade sequences for: (a) PQL-1 self-serve upgrade, (b) PQL-2 growth plan expansion, (c) usage-limit-hit urgency conversion. Each sequence: 5–7 touchpoints across email and in-app, timing, CTA, and personalization variable by role/use case.

4. SALES-ASSIST HANDOFF PROTOCOL — Define the rules for routing PQL-3 users to sales: exact scoring threshold, data payload sent to CRM, SDR outreach template pre-loaded with product usage context, and the 48-hour response SLA workflow.

5. EXPANSION REVENUE MOTION — Design the in-product triggers that identify expansion opportunities within existing paid accounts: seat limit approaching, feature gate hit, usage trending toward next tier, and the marketing automation sequences that capture that expansion revenue without requiring an outbound sales call.

6. PLG METRICS DASHBOARD — Define 8 KPIs for measuring PLG engine health: signup-to-activation rate, time-to-aha (median hours), PQL generation rate (% of signups reaching PQL), PQL-to-paid CVR, average days PQL-to-close, self-serve revenue as % of total new ARR, expansion revenue from in-product triggers, and PLG-assisted pipeline (deals where product usage accelerated sales cycle).

Output as numbered sections with ready-to-use scoring rubrics, sequence blueprints, and Notion/Airtable schema for the PQL pipeline tracker.

## Advanced Customizable Version

# ROLE
You are a world-class product-led growth architect with 15+ years designing PLG engines at B2B SaaS companies from $1M to $500M ARR. You have built PQL scoring models at companies including developer tools, collaboration platforms, data/analytics software, and vertical SaaS. You understand that the #1 failure mode in PLG is treating product signups like inbound MQLs — routing them to sales too early, too late, or with no behavioral context. You have deep expertise in: activation funnel design using Jobs-to-be-Done and habit loop psychology, PQL scoring model architecture using Mixpanel/Amplitude/Heap event data, Intercom/Customer.io/Appcues in-app messaging orchestration, HubSpot/Salesforce CRM enrichment from product analytics, and the PLG→Sales-Assist motion that converts high-intent product users into enterprise contracts. Your frameworks combine Reforge's product-led growth curriculum, Wes Bush's PLG methodology, and first-principles revenue math. You design systems that run autonomously — zero manual qualification, zero wasted SDR time on low-intent users.

# CONTEXT

Company & Product Profile:
- Company Name: [Company name]
- Product Description: [One-sentence description of core value prop]
- PLG Model: [Freemium (permanent free tier) / Free Trial (time-limited, full features) / Reverse Trial (full features → downgrades) / Usage-Based (pay per consumption) / Hybrid (freemium + sales-assist for enterprise)]
- Primary Value Metric: [The unit that grows as users get more value — e.g., "seats," "API calls," "reports created," "projects active," "GB processed"]
- ARR: [$X ARR]
- Monthly Product Signups: [X users/month]
- Monthly Active Users on Free Tier: [X users]
- Monthly Paid Conversions (new): [X]
- Current Free-to-Paid CVR: [X%] — industry benchmark for your model: [Freemium: 2–5% | Free Trial: 15–25% | Usage-Based: varies]
- Average Contract Value (self-serve): [$X]
- Average Contract Value (sales-assist enterprise): [$X]
- Top Expansion Revenue Source: [e.g., seat additions / usage tier upgrades / add-on modules]
- Net Revenue Retention (NRR): [X%]

Ideal Customer Profile:
- Primary Persona (self-serve buyer): [Job title, seniority, company size, tech stack signal]
- Secondary Persona (economic buyer for expansion): [Job title, seniority]
- Company Size — Self-Serve Sweet Spot: [e.g., 10–200 employees]
- Company Size — Enterprise Sales-Assist: [e.g., 500+ employees]
- Industries / Verticals: [List 2–3 primary]
- Disqualifying Signals: [Signals that indicate a user will never convert — e.g., student email, country without billing, wrong job title]

Product Activation Data:
- Defined "Aha Moment": [The single action or milestone that correlates most strongly with long-term retention and paid conversion — e.g., "Users who invite 2+ teammates within 7 days convert at 3.4× the rate of solo users"]
- Current Signup-to-Aha Rate: [X%] (if known)
- Current Time-to-Aha (median): [X hours/days]
- Known Activation Barriers: [2–3 friction points where users churn — e.g., "Setup requires API key that most users don't have ready", "First dashboard is blank and users don't know where to start"]
- Top Churn Reason for Free Users: [Most common reason free users go dark — from exit surveys or support data]

Tech Stack:
- Product Analytics: [Mixpanel / Amplitude / Heap / PostHog / GA4 / other]
- CRM: [HubSpot / Salesforce / Pipedrive / other]
- Marketing Automation: [HubSpot / Marketo / ActiveCampaign / Customer.io / other]
- In-App Messaging: [Intercom / Appcues / Pendo / Userflow / other]
- Email Infrastructure: [SendGrid / Postmark / other]
- Data Warehouse / CDP: [Segment / RudderStack / Snowflake / BigQuery / other]
- Current PQL Tracking Method: [Manual CRM review / Zapier/Make automation / Dedicated PLG tool (Pocus/Toplyne/MadKudu) / None]

Current PLG Gaps:
- Biggest conversion bottleneck: [e.g., "85% of users never reach the aha moment", "Users activate but don't upgrade", "Sales ignores low-ACV PQLs", "No visibility into which accounts have expansion potential"]
- Self-serve revenue vs. sales-assisted revenue split: [X% / X%]
- Sales team sentiment about PLG leads: [e.g., "They ignore product-qualified leads because they have no context", "Sales only wants 500+ seat companies"]
- Current upgrade triggers: [Describe what currently prompts a user to upgrade — or "nothing systematic"]

# OBJECTIVE
Design a complete, AI-powered PLG pipeline architecture that achieves:
- Signup-to-activation rate improvement target: [X% → X%]
- Free-to-paid conversion rate target: [X% → X%]
- Self-serve ARR growth target: [$X new ARR from PLG motion per quarter]
- Reduction in sales time spent on low-intent product users: [target X% reduction in wasted SDR outreach]
- Expansion revenue from in-product triggers: [$X incremental NRR improvement]

All outputs should be designed for AI agent orchestration — no manual steps, no human review queues except for enterprise PQL-3 routing, and no "check with your team" handoffs.

# OUTPUT REQUIREMENTS

## SECTION 1: PQL Scoring Model Architecture

Design a multi-dimensional PQL scoring model using behavioral, firmographic, and engagement signals. The model must run automatically from product analytics data piped into CRM without human scoring.

**BEHAVIORAL SIGNALS (50% of total PQL score):**
Define 6 behavioral events, each with:
- Event name (as it appears in your analytics tool)
- Scoring weight (total behavioral signals sum to 50 points)
- Trigger logic (e.g., "event fired ≥3 times within 14 days of signup")
- Revenue correlation rationale (why does this action predict conversion)
- Data decay rule (does the signal expire if not repeated? When?)

Required behavioral signal categories to cover:
1. **Activation signal** — completion of aha moment action
2. **Depth-of-use signal** — advanced feature adoption beyond basic setup
3. **Collaboration signal** — team/multi-user engagement (most powerful predictor for B2B)
4. **Integration signal** — connecting your product to their existing stack (indicates workflow lock-in)
5. **Frequency signal** — DAU/WAU ratio or return visit pattern within first 30 days
6. **Value-realization signal** — the user has received a measurable output (report generated, data exported, task completed)

**FIRMOGRAPHIC SIGNALS (30% of total PQL score):**
Define 4 firmographic enrichment signals:
- Company size (from Clearbit/Apollo/ZoomInfo enrichment)
- Job title / seniority match to ICP
- Industry vertical match
- Technology stack signal (complementary tools detected via BuiltWith or self-declared)

For each: scoring weight, data source, enrichment trigger timing, and "disqualify" threshold that suppresses PQL even if behavioral score is high.

**ENGAGEMENT SIGNALS (20% of total PQL score):**
Define 3 marketing engagement signals:
- Email open and click engagement rate (nurture sequences)
- Help center / documentation depth of visit (indicates implementation intent)
- Pricing page visit (bottom-funnel intent signal — weighted heavily if visited in first 14 days)

**PQL TIER DEFINITIONS:**

Tier 1 — Self-Serve Ready PQL (Score: 60–74):
- Profile: Individual user or small team (<10 employees) in ICP vertical, reached aha moment, no collaboration signals yet
- Recommended Action: Trigger automated self-serve upgrade sequence (no sales involvement)
- CRM Status: Create as Contact → add to "PLG Self-Serve" sequence in marketing automation
- Upgrade CTA: In-app banner + 3-email automated sequence → direct to pricing/checkout
- Expected CVR from Tier 1: [15–30% self-serve upgrade within 30 days]

Tier 2 — Growth Plan Candidate PQL (Score: 75–89):
- Profile: Small team (10–100 employees) showing collaboration signals, approaching usage limits, ICP fit confirmed
- Recommended Action: Trigger growth-focused upgrade sequence + optional SDR warm outreach
- CRM Status: Create as Account → assign to PLG SDR queue with "Low-Touch Assist" tag
- Upgrade CTA: Personalized email from SDR + in-app expansion offer + optional demo CTA
- SDR Time Investment: Maximum 30 minutes (1 personalized email, 1 follow-up, 1 LinkedIn touch)
- Expected CVR from Tier 2: [30–50% upgrade within 45 days, mix of self-serve and assisted]

Tier 3 — Enterprise Sales-Assist PQL (Score: 90–100):
- Profile: Mid-market or enterprise account (100+ employees), multiple users active, integration signals present, high ACV potential
- Recommended Action: Immediate routing to dedicated AE with full product intelligence brief
- CRM Status: Convert to Opportunity → assign AE → trigger AE notification with usage dashboard link
- AE Time Investment: Full discovery call, tailored demo, security review support
- Expected CVR from Tier 3: [40–70% close rate, 60–120 day sales cycle]

Include: A scoring rubric table showing all signals, weights, and thresholds in a clean format ready to build in Pocus, Toplyne, or a custom Segment/Snowflake query.

## SECTION 2: Activation Architecture & Aha Moment Engineering

Design the complete activation funnel from first login to aha moment, engineered to maximize the percentage of users who experience value within the first 72 hours.

**ACTIVATION FUNNEL MAP:**

For each of the 5 activation steps, provide:
- Step name and description
- The specific in-product action the user must take
- In-app guidance trigger (type: empty state copy / modal / tooltip / checklist / progress bar / celebration animation)
- Email trigger if user has NOT completed step within [X hours]
- Copy direction for both in-app and email (headline, body, CTA — 2–3 sentences each)
- Metric to track: % of users who complete this step
- Benchmark completion rate: [industry standard for this step]
- Revenue impact of step completion: [e.g., "Users who complete Step 2 convert at 2.1× rate of those who skip"]

**Required 5-Step Activation Sequence:**

Step 1 — **Onboarding Orientation** (0–15 minutes post-signup):
Design the first-login experience. The goal: orient the user to their starting point and the 3 actions they need to take to get value. Specify: welcome modal copy, interactive product tour structure (max 5 steps), empty state UI copy for each core section.

Step 2 — **First Value Action** (0–24 hours):
The first meaningful action that demonstrates the product's core value. Design: in-app empty state CTA, tooltip sequence for first-time users, "quick win" template or sample data that lets users see value without their own data first.

Step 3 — **Aha Moment Achievement** (24–72 hours):
The action that statistically predicts long-term retention. Design: the celebration UI moment (confetti, progress notification, achievement badge), the "share your win" prompt (encourages collaboration invite which is a Tier 2 signal), and the immediate follow-up CTA that deepens engagement.

Step 4 — **Second Session & Habit Formation** (Day 3–7):
The re-engagement trigger that converts a "one-time visitor" to a "weekly active user." Design: Day 2 email with specific call to build on Day 1 progress, Day 4 "you've been busy" email showing their activity back to them, Day 7 milestone email if aha has been achieved (upgrade prompt embedded).

Step 5 — **Collaboration Signal Activation** (Day 7–21):
The team-invite or sharing action. Design: in-app invite prompt (timing: trigger after 3rd aha moment completion, not before), email to inviter about team plan benefits when teammate accepts, in-app notification to inviter when teammate takes first meaningful action.

**ACTIVATION FAILURE RECOVERY:**

For each step dropout scenario, design a recovery intervention:
- **Never logged in after signup** (within 48 hours): Win-back email with "your account is ready" framing + direct deep-link to aha moment action
- **Logged in but didn't complete Step 2** (within 72 hours): Support-triggered check-in email + in-app help widget surfaced on next login
- **Stuck at Step 3 for 7+ days**: Personal-feeling email from "Customer Success" (automated but personalized with their company name and use case) + offer of a 15-minute setup call for high-ICP users

## SECTION 3: Automated Upgrade Sequence Blueprints

Design three complete upgrade sequences. Each sequence must be fully automated — triggered by product signals, personalized by role and use case, and requiring zero manual intervention.

**SEQUENCE A: Self-Serve Upgrade Sequence (PQL Tier 1)**

Trigger: User reaches PQL Tier 1 score (60–74 points)
Goal: Drive self-serve upgrade to entry-level paid plan within 21 days
Sequence type: Email + in-app (no SDR involvement)
Personalization variables: [first_name], [company], [primary_use_case] (inferred from features used), [aha_moment_achieved] (specific action they took)

Touchpoint 1 (Day 0 — trigger day): In-App Upgrade Banner
- Placement: Top of navigation or feature gate moment
- Headline: "[First Name], you've unlocked [X] [value actions] — here's what you can do with more"
- Body: Specific callout of the value they've gotten (from product data), then 1-sentence pitch for the upgrade
- CTA: "Upgrade to [Plan Name] — $[price]/mo"
- Dismissable: Yes, but re-surfaces after 3 days

Touchpoint 2 (Day 1): Email — "You're getting real results with [Product]"
- Subject line A: "Your [product] results from this week" | Subject line B: "What [Company Name]'s team could do with [Feature]"
- Content: Mirror their actual usage back at them (# of [value actions] completed, time saved estimate), then show the upgrade unlock
- CTA: View paid plan features
- From name: "[Product] Growth Team" (not sales)

Touchpoint 3 (Day 5): Email — Social proof + outcome focus
- Subject line: "How [Similar Company] [achieved outcome] with [Product] in [timeframe]"
- Content: Short customer story (100 words) with a stat that resonates with their use case, then "here's what they're using that you don't have access to yet"
- CTA: Start free trial of [paid plan] (if reverse trial available) OR See pricing

Touchpoint 4 (Day 8): In-App — Feature gate moment
- Trigger: User attempts to use a paid feature
- Modal: "You've hit the [feature] limit — upgrade to [Plan] to [specific outcome]"
- Show: Side-by-side free vs. paid feature table (keep it to 5 rows max)
- CTA: Upgrade now (primary) | See all plans (secondary)

Touchpoint 5 (Day 12): Email — Value-anchored urgency
- Subject line: "Your [free plan] resets in [X days]" (if trial-based) OR "[Feature] you're not using yet"
- Content: Highlight 2–3 features they haven't tried that directly address their use case (inferred from behavior), with outcome framing
- CTA: Upgrade + unlock these features

Touchpoint 6 (Day 18): Email — Final self-serve nudge
- Subject line: "Quick question about your [Product] setup, [First Name]"
- Content: Conversational tone — "we noticed you've been using [Product] for X weeks and you're getting [value]. If you ever want to [next level of value], here's exactly what's included:" — 3-bullet benefit list
- CTA: Upgrade to [Plan] | Talk to a human (surfaces SDR for high-ICP users)

Touchpoint 7 (Day 21): Decision — Branch logic
- If upgraded: Trigger onboarding sequence for paid plan, log conversion in CRM, suppress from upgrade sequence
- If no action: Move to dormant free user re-engagement sequence (6-month touch cadence) OR escalate to PQL-2 if firmographic score increases

**SEQUENCE B: Growth Plan Expansion Sequence (PQL Tier 2)**

Trigger: User reaches PQL Tier 2 score (75–89) AND team has 2+ active users
Goal: Drive team/growth plan upgrade — mix of self-serve and light SDR assist
Sequence: Email (personalized) + In-app + 1 SDR touch
Key difference from Sequence A: Emphasis on team value, collaboration, and admin-level buyer identification

Touchpoint 1 (Trigger day): Identify the economic buyer
- Logic: Is the user with highest PQL score the admin/billing owner? If no, trigger a "share with your team" in-app prompt that surfaces to the admin
- Admin identification: Query CRM enrichment (Clearbit) or check if user email = company domain with "admin@" / "billing@" / or LinkedIn title includes "Head of" / "VP" / "Director"

Touchpoint 2 (Day 0): Email to Admin (or highest-seniority user)
- Subject: "[X] people on your team are using [Product] — here's what they're doing"
- Content: Team usage summary (# of active users, top use cases from behavior data), then "here's what your team could accomplish with the Growth Plan"
- Frame as: Business outcome for the manager, not feature list for the user
- CTA: See Growth Plan for teams

Touchpoint 3 (Day 2): SDR Outreach (light touch)
- SDR receives CRM alert: "[Company] — [X] users active, PQL score: [Y], top features used: [Z]"
- SDR sends one email (30-second read): "Hey [Admin], noticed your team at [Company] has been [specific product action] — a lot of teams your size also use [Feature] to [outcome]. Happy to walk you through how [Company] → [customer name] did it in 20 minutes. Would Tuesday work?"
- SDR notes: No pitch deck, no PDF attachments, reference their actual product usage in first sentence
- If admin responds: Route to AE for proper discovery
- If no response after 3 days: Back to automated sequence

Touchpoint 4 (Day 5): In-App — Admin dashboard notification
- Location: Admin panel or usage dashboard
- Message: "Your team is growing — here's what the Growth Plan adds for teams of [X]"
- Show: ROI estimate based on their actual usage (e.g., "At your current pace, your team will hit the free limit in [X days]")

Touchpoint 5 (Day 10): Email to admin — Peer benchmark
- Subject: "How teams like yours use [Product] at scale"
- Content: 2–3 micro-case studies from companies in same industry/size. Focus on the team productivity angle (how many users, how quickly they onboarded, what the business outcome was)
- CTA: Book a 20-min Growth Plan walkthrough (optional) OR Upgrade directly

Touchpoint 6 (Day 15): Usage-limit warning
- If team approaching a limit: Trigger in-app banner + email with specific "you'll hit your limit in X days at current pace"
- Include: Cost-per-seat calculation at Growth Plan price (make the math easy)
- CTA: Add seats now | Start team trial

**SEQUENCE C: Usage-Limit-Hit Urgency Conversion**

Trigger: User hits 80% of their free plan limit (seats, API calls, storage, projects — whichever is primary value metric)
Goal: Convert within 7 days while urgency is high
This sequence is the highest-converting PLG trigger — treat it as a separate revenue program

Touchpoint 1 (80% limit hit): In-App Alert — Real-time warning
- Placement: Persistent top bar (cannot be dismissed until limit is resolved)
- Copy: "You've used [80%] of your [free plan limit] — [X] [units] remaining"
- Show: Visual progress bar + estimated days until limit based on current usage pace
- CTA: Upgrade to [Plan] and remove limits (primary) | See all plan options (secondary)
- Also trigger: Immediate email alert to account admin

Touchpoint 2 (80% limit — Email to admin):
- Subject: "⚠️ [Company] is approaching your [Product] limit"
- Content: Current usage vs. limit, estimated date of limit hit, what happens when limit is reached (do NOT threaten data loss — frame as "you'll stop being able to [core action]"), cost of upgrading
- Make the math easy: "For $[X]/month, your team gets [3× the limit] and [top 2 upgrade features]"
- CTA: Upgrade now — takes 2 minutes

Touchpoint 3 (95% limit hit — 24–48 hours after T1): Second In-App Escalation
- Urgency increases: "Almost there — [X units] left. Don't let your work stop."
- Add: Live pricing card with single recommended plan
- Add: "Start in 2 minutes" framing (reduces perceived friction of upgrade)

Touchpoint 4 (100% limit hit): Limit Wall (NOT a hard block — a soft gate)
- Design principle: Never completely block existing work. Users should be able to view existing data/projects but not create new ones.
- In-app state: Prominent upgrade required modal with clear "what you can still do" vs. "what's paused"
- Copy: "Your free plan has reached its limit — upgrade to continue creating [core action]"
- CTA: Upgrade now | Talk to us (for enterprise route)

Touchpoint 5 (Day 3 post-limit): SDR trigger for high-value accounts
- For accounts with 5+ users that hit the limit: SDR receives priority alert
- SDR call script: "Hey [name], I saw [Company] hit your [product] limit — before we figure out the right plan, I want to make sure you don't lose any momentum. Can I walk you through the options in 10 minutes?"
- Goal: Not a sales call — a rescue call that converts to a proper deal

## SECTION 4: Sales-Assist Handoff Protocol & AE Intelligence Brief

Define the complete data payload, routing logic, and outreach protocol for PQL-3 enterprise routing.

**PQL-3 ROUTING TRIGGER:**
- Score threshold: 90+ AND (company size ≥100 employees OR ACV potential ≥$[X]/year based on seat count estimate)
- Routing SLA: AE must act on PQL-3 within 4 business hours of CRM alert
- Escalation: If AE does not act within 4 hours, SDR manager receives a Slack alert

**CRM ENRICHMENT DATA PAYLOAD (auto-populated on PQL-3 creation):**
When a PQL-3 is created in CRM, the record must auto-populate with:

**Account Intelligence:**
- Company name, domain, industry, employee count (Clearbit enrichment)
- Estimated ACV at current headcount (seats × $ACV formula)
- Technology stack: complementary tools detected + potential integration opportunities
- LinkedIn company page URL + recent company news (funding, hiring, product launches)

**Product Usage Intelligence:**
- Total active users on free tier (current)
- Days since first signup
- Total # of aha moment completions
- Top 3 features used (by frequency)
- Integrations configured
- Most recent product activity (last 7 days)
- Usage growth trend: [flat / growing / accelerating]
- Estimated usage-based upgrade timeline (days until they hit free limit at current pace)

**Buyer Intelligence:**
- Primary user (highest activity) — name, title, LinkedIn URL
- Admin/billing contact — name, email, title
- # of email domains active (indicates viral spread within company)
- Previous sales engagement: any prior CRM activity, past demo requests, historical support tickets

**AE-READY OUTREACH TEMPLATE (auto-generated from CRM data):**

Subject: [Company] + [Product] — quick thought on your team's setup

Hi [Admin First Name],

Noticed [X] people at [Company] have been [most frequent product action] with [Product] over the past [X days] — impressive usage for a team your size.

Wanted to reach out personally because [Company] matches the profile of teams we typically help most: [industry, use case inferred from features used, company size]. A few companies similar to yours — [Customer A] and [Customer B] — found that [specific outcome they got with enterprise plan feature].

The main thing your team doesn't have access to yet on the free plan: [Top 2 enterprise features directly relevant to their top feature usage].

Worth a 20-minute call to see if it makes sense? I can walk through what [Company] specifically would get and what teams like yours typically save/gain.

[AE Name]
[Title, Company]

[Calendar link — direct Calendly/Chili Piper, pre-qualified to 25 min]

**P.S.** [Product data personalization: e.g., "Saw you've been creating [X reports] per week — teams at that cadence usually find [Feature] cuts their time in half."]

**48-HOUR RESPONSE WORKFLOW:**
- Hour 0: AE receives CRM alert + Slack notification with PQL intelligence brief
- Hour 4: If no AE action, SDR manager escalation trigger
- Hour 24: If email sent but no reply, AE sends LinkedIn connection request (no message — just connect)
- Hour 48: If still no reply, AE sends 2nd email: 3 sentences, reference specific product activity, single CTA
- Day 5: If no response, route back to PQL-2 automated sequence (light cadence) — AE disengages to protect their time for active pipeline

## SECTION 5: Expansion Revenue Motion Design

Design the systematic framework for identifying and capturing expansion revenue within existing paid accounts using product usage signals — without requiring outbound sales calls for standard expansion plays.

**EXPANSION SIGNAL MONITORING (automated, runs daily):**

Signal 1 — **Seat Ceiling Approach** (75% of seat limit reached):
- Trigger: In-app admin notification + email to admin: "3 more teammates could join your [Product] workspace — here's how to add them"
- Automated action: Suggest adding seats with one-click pricing calculator
- Self-serve expand rate benchmark: 40% of accounts at 75% seat ceiling upgrade within 30 days

Signal 2 — **Power User Concentration** (>40% of activity from 1–2 users on a 5+ seat account):
- Trigger: Email to admin: "Your team has room to grow — [X seats] are still available"
- Frame as: Efficiency opportunity, not a sales pitch — "Teams that spread usage across [X] members get [Y% better outcome]"
- Include: "Activate unused seats" tutorial link

Signal 3 — **Feature Gate Ceiling** (user has hit a paid plan's feature limit 3+ times in 30 days):
- Trigger: In-app tier upgrade prompt + personalized email showing the plan difference
- Context: Show the user's own data — "You've exported [X reports] this month, your plan includes [Y]. Here's what the next tier adds."
- Include: ROI calculation based on their usage pace

Signal 4 — **Cross-Sell Integration Signal** (user connects Product A but not Product B in your suite):
- Trigger: In-app cross-sell banner in Product A: "You're using [Product A] — did you know [Product B] connects directly and [specific outcome]?"
- Email campaign: 3-email sequence showing the combined value, customer story, and trial option for Product B

Signal 5 — **Annual Renewal Expansion Window** (90 days before renewal):
- Trigger: CS alert + marketing automation sequence beginning 90 days before renewal
- Email sequence: Month 1 = QBR invitation, Month 2 = expansion feature demo, Month 3 = renewal + upgrade offer with annual commitment discount
- Goal: Convert monthly-to-annual AND capture seat/feature expansion in same renewal motion

**EXPANSION REVENUE CALCULATOR:**
Provide a formula for estimating in-year expansion revenue from PLG signals:
- Seat expansion revenue per account per year = (Average seat addition per account) × (ACV/seat) × (% of accounts that expand)
- Feature tier upgrade revenue = (Accounts hitting tier limit per month) × (Tier price delta) × (Upgrade CVR %)
- Cross-sell attach rate revenue = (Accounts using Product A) × (Cross-sell attach rate %) × (Product B ACV)

## SECTION 6: PLG Metrics Dashboard & Revenue Intelligence

Define the 8 core KPIs for PLG program health, plus 4 advanced diagnostic metrics. For each KPI:
- Definition and calculation formula
- Benchmark range for your PLG model
- How to report (daily monitoring / weekly review / monthly leadership / quarterly board)
- Leading indicator warning sign that signals a problem before it impacts revenue
- Downstream revenue impact of a 10% improvement in this metric

**CORE 8 KPIs:**

KPI 1 — **Signup-to-Activation Rate**
Definition: % of new signups who complete the defined aha moment within [30/14/7 days — by model]
Formula: (Users who completed aha moment in period) / (Total signups in cohort) × 100
Benchmark: Freemium 20–35% | Free Trial 40–60% | Developer tool 15–25%
Revenue impact: Each 5pp improvement in activation rate = approximately [X]% improvement in paid conversion rate (because activation is the primary predictor of conversion)
Warning sign: If Day-1 activation rate drops >5pp week-over-week, investigate signup source quality or product change impact

KPI 2 — **Time-to-Aha (Median)**
Definition: Median hours/days from first login to first aha moment completion
Formula: Median([timestamp_aha - timestamp_first_login]) across all activating users in period
Benchmark: <24 hours for consumer-grade simplicity | 24–72 hours for most B2B tools | <7 days acceptable maximum
Revenue impact: Each 24-hour reduction in time-to-aha correlates with 8–12% higher 30-day retention (Reforge benchmark)
Warning sign: If median time-to-aha increases >20%, check for onboarding friction, product bug, or sign that activation bar is miscalibrated

KPI 3 — **PQL Generation Rate**
Definition: % of monthly signups that reach PQL threshold (any tier)
Formula: (Total PQLs generated in period) / (Total signups in period) × 100
Benchmark: 5–15% of total signups for most B2B SaaS (varies heavily by ICP quality of signup source)
Revenue impact: PQL rate × close rate × ACV = self-serve new ARR capacity
Warning sign: If PQL rate drops, first check signup source quality (are paid ads bringing worse ICP?), then check activation rate (are users reaching aha?)

KPI 4 — **PQL-to-Paid Conversion Rate**
Definition: % of users who reach PQL status that convert to any paid plan within 60 days
Formula: (PQLs from cohort who converted to paid within 60 days) / (Total PQLs generated in cohort) × 100
Benchmark by tier: PQL-1 self-serve 15–30% | PQL-2 growth 30–50% | PQL-3 enterprise 40–70%
Revenue impact: This is the primary lever — it's the product-led pipeline close rate
Warning sign: If PQL-to-paid drops, segment by tier. PQL-1 drop = pricing/checkout friction. PQL-2 drop = SDR response time or messaging. PQL-3 drop = AE capacity or deal size mismatch.

KPI 5 — **Average Days PQL-to-Close (Velocity)**
Definition: Average days from reaching PQL score to paid conversion
Formula: Mean([date_converted - date_pql_achieved]) for all converted PQLs in period
Benchmark: Self-serve PQL-1: <7 days | Growth PQL-2: 7–21 days | Enterprise PQL-3: 30–90 days
Revenue impact: Each 10% reduction in time-to-close accelerates ARR recognition and improves cash flow
Warning sign: Increasing velocity for PQL-1 but not PQL-3 indicates self-serve product is working but enterprise motion is bottlenecked

KPI 6 — **Self-Serve ARR as % of New ARR**
Definition: Revenue from paid plan upgrades initiated without sales involvement, as % of total new logo ARR
Formula: (Self-serve new ARR in period) / (Total new ARR in period) × 100
Benchmark: Early PLG: 20–30% | Mature PLG: 40–60% | Best-in-class PLG (Notion, Figma model): 60–80%
Revenue impact: Higher self-serve % = lower CAC, higher gross margin, more scalable GTM
Warning sign: If self-serve % declines, check if checkout experience is broken, pricing is increasing, or marketing is sending worse-fit traffic

KPI 7 — **Expansion Revenue from In-Product Triggers**
Definition: Incremental ARR generated from product-usage-triggered expansion (seat additions, tier upgrades, cross-sell) without outbound sales action
Formula: (Expansion ARR from triggered plays) / (Total expansion ARR) × 100
Benchmark: Mature PLG companies capture 25–40% of expansion through automated in-product triggers
Revenue impact: Each $1 of automated expansion saves $0.20–0.40 of sales cost compared to AE-assisted expansion

KPI 8 — **PLG-Assisted Pipeline Contribution**
Definition: % of sales pipeline where product usage data was a contributing factor to deal creation or acceleration
Formula: (Opportunities with documented PLG signal as source or accelerant) / (Total open opportunities) × 100
Benchmark: PLG-first companies: 60–80% | PLG-supplement companies: 20–40%
Revenue impact: Deals with PLG product signal close at 1.3–2.0× the rate of non-PLG deals in most B2B SaaS (because intent is demonstrated, not assumed)

**ADVANCED DIAGNOSTIC METRICS:**

D1 — **Activation Funnel Dropout Analysis**: % of users dropping at each of the 5 activation steps (identify where activation is breaking)
D2 — **PQL Score Distribution**: Histogram of all users by PQL score segment (tells you if your ICP targeting is working — should see bimodal distribution: high-fit users cluster at 80+, low-fit cluster at 0–30)
D3 — **Cohort Conversion Curve**: Cumulative paid conversion rate by days since signup for each monthly cohort (shows if conversion window is stable or shifting)
D4 — **Expansion Revenue Timing**: Average days from paid plan activation to first expansion event (seat add, tier upgrade, cross-sell) — shorter = stronger product adoption engine

**PLG COMMAND CENTER DASHBOARD DESIGN:**

Provide a Notion or Airtable database schema for the PLG Pipeline Tracker with:
- Views: All PQLs (by tier), This Week's New PQLs, Overdue PQL-3 Handoffs (>4 hours without AE action), Conversion Won/Lost this month
- Fields: User name, company, PQL tier, PQL score, top behavioral signals triggered, ACV estimate, days since PQL trigger, sequence enrolled, conversion status, AE/SDR assigned, deal value
- Automations: Slack alert to AE when PQL-3 created, weekly Notion digest of PQL pipeline summary to revenue leadership
- Integration: Bidirectional sync with HubSpot/Salesforce so CRM is single source of truth

## Example Input/Output

**Input Example:**

Company: Vaultify — B2B data room and deal management SaaS for M&A advisory firms and investment banks.
PLG Model: Freemium (permanent free tier, 1 active deal room, 3 users)
Primary Value Metric: "Active deal rooms" (each room = one deal being managed)
ARR: $3.2M, growing 110% YoY
Monthly Signups: 1,200 new users/month (primarily CFOs, M&A analysts, and investment bankers at small advisory firms)
Current Free-to-Paid CVR: 6.8% (target: 15%)
ACV Self-Serve: $4,800/year ($400/month — "Professional" plan, 5 deal rooms, 15 users)
ACV Enterprise: $36,000/year (unlimited rooms, white-label, SSO, audit trail)
Aha Moment: "Inviting an external counterparty to view a deal room for the first time within 7 days of signup"
Aha Rate: 31% currently (target: 50%)
Activation Barrier: Users create a deal room but then manually upload documents one by one instead of using bulk import — 44% of users who hit the one-file-at-a-time friction never return
Tech Stack: Mixpanel, HubSpot, Intercom, Customer.io, Clearbit, Segment

**Output Example (Partial — PQL Scoring Model):**

**Vaultify PQL Scoring Model**

| Signal | Category | Points | Trigger Logic | Revenue Correlation |
|--------|----------|--------|---------------|---------------------|
| External counterparty invited to deal room | Behavioral — Aha Moment | 20 | Event fired ≥1× within 14 days | Users who invite external party convert at 4.2× rate of solo users |
| 3+ documents uploaded to same deal room | Behavioral — Depth of Use | 10 | ≥3 document_upload events in single room within 30 days | Indicates active deal in progress — high urgency to manage it professionally |
| 2+ internal team members added | Behavioral — Collaboration | 15 | team_member_invited fired ≥2× (any role) within 21 days | Multi-user accounts convert at 2.8× solo accounts and churn at 40% lower rate |
| NDA or confidentiality agreement uploaded | Behavioral — Depth of Use | 8 | File tagged "NDA" or "agreement" via ML classifier or user tag | Indicates real deal activity, not experimentation — buyer is in an active transaction |
| Deal room shared via public link | Behavioral — Integration Signal | 7 | public_link_created event | External sharing = real deal pressure = conversion urgency |
| Logged in ≥3× in first 14 days | Behavioral — Frequency | 10 | session_start events ≥3 in first 14 days | 3+ sessions in first 14 days = 2.1× higher 90-day retention |
| Company: 10–500 employees (advisory/PE/IB) | Firmographic | 12 | Clearbit enrichment on signup email domain; industry = "Financial Services" or "Investment Banking" | ICP match predicts 3.5× higher ACV than non-ICP signups |
| Job title includes "Director" / "VP" / "Managing Director" / "Partner" | Firmographic | 8 | LinkedIn title from Clearbit enrichment | Senior buyers have authority to approve spend without committee review |
| Pricing page visited in first 7 days | Engagement | 7 | pricing_page_view event fired in days 1–7 | Early pricing intent = 2.3× higher conversion rate |
| Email click in activation sequence | Engagement | 3 | email_clicked event in HubSpot | Indicates receptivity to nurture — boosts confidence score |

**PQL-3 Threshold Example (Vaultify):**

Score: 94/100
Company: Meridian Capital Partners — 180-person boutique M&A advisory firm
Users: 8 active on free tier (3 Managing Directors, 4 Associates, 1 Compliance Officer)
Top signals: External counterparty invited ×6, 47 documents uploaded across 3 deal rooms, NDA uploaded ×4, logged in on 14 of last 21 days, pricing page visited twice
ACV estimate: $36,000/year (enterprise plan — 180 employees × $200 seat estimate)

CRM Auto-Populated AE Brief:
"Meridian Capital Partners — 8 users active for 31 days, managing 3 live deal rooms, have invited 6 external counterparties. Clear sign they're running active M&A transactions on the free plan. Top feature gap: They're at 3/3 deal room limit. White-label and audit trail features are critical for a firm their size (compliance requirement for FINRA). Estimated ACV: $36K/year. Two Managing Directors (Sarah Chen, James Okafor) are the most active users — both have MDs with deal authority. Outreach angle: 'You've been running live deals on the free plan — let's make sure you don't hit a capacity wall mid-transaction.'"

## Success Metrics

**30-Day PLG Engine Launch:**
- PQL scoring model implemented and syncing from product analytics to CRM automatically
- Upgrade sequences A, B, and C launched in Customer.io or HubSpot
- PQL-3 routing protocol live — AEs receiving intelligence briefs within 4 hours of trigger
- PLG dashboard live in Notion/Airtable with daily data refresh

**90-Day Conversion Improvement Targets:**
- Signup-to-activation rate: +10–20 percentage points above baseline
- Free-to-paid CVR: +3–8 percentage points above baseline (from 6.8% toward 15% example)
- Self-serve ARR from automated sequences: $50K–$150K incremental new ARR (size-dependent)
- PQL-3 AE response time: <4 hours for 95% of PQL-3s triggered

**6-Month PLG Maturity Indicators:**
- Expansion revenue from in-product triggers: 15–25% of total expansion ARR
- PQL-to-paid CVR by tier benchmarked against industry (15–30% / 30–50% / 40–70%)
- PLG contribution to total new pipeline: 30–60% depending on GTM mix
- Activation funnel dropout rate by step identified and improvement experiments running

## Related Prompts

- [AI-Powered B2B SaaS Free Trial Activation Funnel CRO & Time-to-Value Conversion Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Free-Trial-Activation-Funnel-CRO-&-Time-to-Value-Conversion-Intelligence-Engine.md) — Detailed CRO optimization for the trial activation steps in your PLG funnel
- [AI-Powered B2B SaaS Trial Expiry & Free-to-Paid Conversion Marketing Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/AI-Powered-B2B-SaaS-Trial-Expiry-&-Free-to-Paid-Conversion-Marketing-Intelligence-Engine.md) — Email sequence specifics for trial expiry conversion plays
- [AI-Powered B2B SaaS Product-Led Buyer Journey Analytics & PQL-to-Enterprise Revenue Intelligence Engine](../../05_Analytics-&-Performance/Customer-Journey-Analytics/AI-Powered-B2B-SaaS-Product-Led-Buyer-Journey-Analytics-&-PQL-to-Enterprise-Revenue-Intelligence-Engine.md) — Analytics layer for measuring the PLG buyer journey built in this prompt
- [AI-Powered B2B SaaS Growth Experimentation Velocity Program & Rapid Revenue Testing Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-B2B-SaaS-Growth-Experimentation-Velocity-Program-&-Rapid-Revenue-Testing-Intelligence-Engine.md) — Run systematic experiments on your PLG activation funnel to compound conversion improvements

## Integration Tips

**Mixpanel / Amplitude / PostHog → HubSpot / Salesforce:**
Use Segment or RudderStack as the data pipeline. Map behavioral events to CRM custom properties using a Segment "Destination" to HubSpot. Set up HubSpot workflows to recalculate PQL score nightly based on updated event counts. For Salesforce: use Apex triggers or a dedicated PLG tool (Pocus, Toplyne, or MadKudu) that has native Salesforce integration with pre-built PQL scoring models.

**Customer.io / Intercom for Sequence Automation:**
Customer.io is ideal for PLG because it natively ingests product event data via API and allows behavioral triggers on exact event combinations (e.g., "aha_moment fired AND team_members < 2 AND days_since_signup = 5" → enroll in Sequence B). Intercom handles in-app messaging (modals, tooltips, banners) with the same event-based logic. Connect both to your CRM so sequence enrollment and email engagement data appears on the contact record.

**Chili Piper / Calendly for PQL-3 AE Routing:**
Embed a Chili Piper Concierge routing link in every PQL-3 outreach email. This automatically routes to the assigned AE's calendar based on territory, shows real-time availability, and books directly — eliminating the back-and-forth that kills PLG-to-enterprise conversion velocity. Configure routing rules so accounts >500 employees route to enterprise AEs, 100–500 to mid-market AEs.

**Pocus / Toplyne for PLG Signal Intelligence:**
These PLG-native tools sit on top of your product analytics and CRM to provide AEs with a "PLG workspace" — showing them account health, feature adoption, and usage trends without requiring AEs to learn Mixpanel. Use Pocus's "Playbook" feature to auto-surface PQL-3 accounts in the AE's daily digest, ranked by expansion potential. Pocus integrates with Salesforce in <2 hours.

**Notion for PQL Pipeline Tracker:**
Build your PLG command center in Notion using a database with filtered views per SDR/AE. Use Notion's API + Zapier to auto-create records when a new PQL-3 is triggered in HubSpot, and auto-update status when the CRM deal stage changes. Weekly summary: use Notion AI with prompt "Summarize the PQL pipeline this week: total PQLs by tier, conversions, overdue AE handoffs, and top 3 accounts to prioritize."

**Google Sheets for PLG Revenue Math:**
Build a PLG Revenue Calculator spreadsheet with inputs: monthly signups, activation rate, PQL rate, PQL-to-paid CVR by tier, ACV by tier. Outputs: projected self-serve ARR per quarter, projected PLG-assisted pipeline, projected expansion ARR. Share with leadership so PLG program investment is tied to revenue math from day one.

## Troubleshooting

**Problem: PQL score is high but conversion rate remains low — PQLs aren't upgrading.**
Solution: Your PQL model is measuring activity, not intent. Audit which behavioral signals actually predict conversion vs. which just predict engagement. Run a cohort analysis: for users who converted vs. didn't, what was the #1 behavioral difference? Common fix: the "aha moment" is miscalibrated — users are completing it but it's not creating perceived value. Run user interviews with 10 non-converting PQLs and 10 converting PQLs in the same week. The difference will be obvious. Also check: is your pricing visible? Is the checkout flow broken? Is upgrade CTA appearing at the right moment? Use Hotjar or FullStory on your upgrade flow.

**Problem: Sales is ignoring PQL-3 leads — AEs say "these aren't real buyers."**
Solution: This is a data quality and process failure, not a PLG failure. Root cause: AEs don't trust the signal because they've been burned by false-positive "hot leads" before. Fix in 3 steps: (1) Show AEs the data — run a closed/won analysis of the last 20 enterprise deals and show what their PQL score was 30 days before sales engaged. If your model is working, high-PQL accounts close at higher rates. (2) Give AEs a PLG intelligence brief that feels like good research — not a generic "this company visited your website 3 times." The Vaultify example above shows what good looks like. (3) Start with a 30-day pilot: 10 PQL-3 accounts routed to one AE champion. Track the results and use them to convert skeptical AEs.

**Problem: Activation rates are stuck — users sign up but never complete the aha moment.**
Solution: Your onboarding is asking users to do work before they've seen value. The most common PLG activation failure: users are asked to "set up" the product before they can use it. Fix: implement a "demo mode" or "sample data" state that shows users what their experience will look like with real data, before requiring setup. Reference: Superhuman, Loom, and Figma all use this technique — users see a completed, beautiful output on first login, then are asked to recreate it with their own data. Also: reduce setup steps aggressively. Every field you remove from the initial setup increases activation rate by 2–8%. Run a "minimum viable activation" experiment: what is the absolute fewest steps required to reach the aha moment?

## Version History
- v1.0: Initial creation (auto-generated)
