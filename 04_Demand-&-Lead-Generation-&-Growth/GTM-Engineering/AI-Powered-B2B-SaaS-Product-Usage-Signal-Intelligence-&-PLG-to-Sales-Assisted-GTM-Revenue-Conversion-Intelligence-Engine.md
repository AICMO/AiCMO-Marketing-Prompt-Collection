# AI-Powered B2B SaaS Product Usage Signal Intelligence & PLG-to-Sales-Assisted GTM Revenue Conversion Intelligence Engine - Turn In-Product Behavior Into Autonomous Pipeline

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** GTM engineering, PLG, product-led growth, product usage signals, Pendo, Amplitude, Mixpanel, Clay, PLS motion, signal-based GTM, trial conversion, freemium, expansion revenue, CRM automation, B2B SaaS

## Overview
Builds a fully automated system that monitors free trial users, freemium accounts, and existing customers for product usage milestones — then routes the right sales play at the exact moment a user's behavior signals buying intent or expansion readiness. Use this when you're running a PLG or hybrid PLG+sales motion and want to eliminate the "spray and pray" sales assist approach by replacing it with precise, behavior-triggered outreach that converts 3-5x better than time-based sequences.

## Quick Copy-Paste Version

You are a GTM Engineering expert specializing in product-led growth (PLG) signal activation for B2B SaaS companies. Design a complete product usage signal detection and sales-assist routing system that identifies when free trial users, freemium accounts, and existing customers hit behavioral milestones indicating upgrade or expansion readiness — and automatically triggers the right human or AI-led revenue play.

COMPANY CONTEXT:
- Company: [e.g., "Fieldvault — AI-powered field service management platform for enterprise operations teams"]
- GTM motion: [e.g., "Freemium self-serve with sales assist at $5K+ ACV deals"]
- Product analytics tool: [e.g., "Amplitude"]
- CRM: [e.g., "HubSpot"]
- Sales assist team: [e.g., "4 AEs covering self-serve pipeline above $5K ACV threshold"]
- Monthly trial starts: [e.g., "380 new trials/month, 12% currently converting to paid"]
- Current conversion lag: [e.g., "Average 22 days from trial start to paid — no consistent sales assist trigger"]

THREE SIGNALS TO SOLVE:

1. POWER USER ACTIVATION SIGNAL → User completes 3+ core actions within 7 days (product aha moment hit) — trigger immediate sales assist outreach while intent is hottest
2. EXPANSION SIGNAL → Existing paid customer's usage crosses tier threshold (e.g., 80% of seat limit, high-frequency feature usage, or integration of premium capability in trial mode) — trigger proactive upgrade conversation before they hit a wall
3. RE-ENGAGEMENT SIGNAL → Trial user goes dormant after initial activation (logged in 3+ times in week 1, then zero activity for 5+ days) — trigger AI-powered re-engagement before trial expires

OUTPUT REQUIRED:
1. SIGNAL ARCHITECTURE: Define the specific product events and thresholds that constitute each signal type for your product
2. ENRICHMENT WATERFALL: How to take a product event and build a complete sales context card (company size, ICP fit, intent overlay, LinkedIn profile of user)
3. THREE PLAY DESIGNS: Full outreach sequence for each signal type with role-specific copy and timing
4. ROUTING LOGIC: When human AE vs. AI SDR vs. in-app messaging handles each signal
5. CRM AUTOMATION: Exact workflow specs to auto-create opportunities and route plays in HubSpot/Salesforce
6. MEASUREMENT FRAMEWORK: How to attribute revenue to specific product signals and optimize signal thresholds over time

## Advanced Customizable Version

ROLE: You are a senior GTM Engineer with deep expertise in product-led growth (PLG) signal activation for B2B SaaS companies scaling from $5M to $100M ARR. You have instrumented product analytics platforms (Amplitude, Mixpanel, Pendo, PostHog) and built Clay-based enrichment waterfalls that transform raw behavioral events into qualified pipeline. You understand that most PLG companies leave 40-60% of conversion opportunities on the table because they trigger sales outreach on time-based schedules (e.g., "email everyone on day 7 of trial") instead of behavior-based signals. You design systems where the product itself is the pipeline qualification engine — humans and AI agents only engage when the signal says "now." You think in event schemas, funnel cohorts, ICP fit scores, and revenue attribution, and you build systems that connect Amplitude/Pendo events to Clay to CRM to Outreach sequences without requiring a human to make a single routing decision.

OBJECTIVE: Design a production-ready product usage signal detection and sales-assist routing system that:
- Monitors 100% of active trial and freemium accounts for behavioral signals indicating purchase or expansion intent
- Scores each signal event by sales-assist urgency (immediate AE outreach vs. AI SDR vs. lifecycle email vs. in-app nudge)
- Triggers scenario-specific plays automatically with the right sender, right message, and right timing — within minutes of signal detection
- Routes each play to the correct revenue team member or AI agent based on deal size, ICP fit, and account ownership
- Tracks product-signal-sourced pipeline as a discrete revenue category to prove PLG motion ROI
- Continuously optimizes signal thresholds using cohort conversion data to improve which product events actually predict revenue

---

COMPANY PROFILE:
- Company name & product: [name + one-sentence description]
- Business model: [freemium/free-trial/usage-based + pricing tiers]
- ARR range & stage: [current ARR, Series A/B/C, growth rate]
- PLG motion: [fully self-serve / self-serve + sales assist above threshold / product-qualified lead (PQL) model]
- Sales assist team: [number of AEs and SDRs covering PLG pipeline]
- Monthly trial/freemium accounts: [new signups per month + total active freemium base]
- Current trial-to-paid conversion rate: [%] and average time-to-convert: [days]
- Current expansion revenue motion: [manual CSM-triggered / product-triggered / not formalized]

---

PRODUCT ANALYTICS INFRASTRUCTURE:
- Primary analytics tool: [Amplitude / Mixpanel / Pendo / PostHog / Heap / Segment]
- Key events instrumented: [list the 5-10 most important product events currently tracked, e.g., "project_created," "integration_connected," "report_exported," "team_member_invited"]
- Aha moment definition (if known): [the specific sequence of events correlated with long-term retention, e.g., "user who creates 1 project AND invites 1 team member within 48 hours has 78% 90-day retention vs. 23% for those who don't"]
- Current seat/usage limits by tier: [free tier limits, paid tier thresholds, enterprise triggers]
- Product events NOT yet instrumented (gaps): [honest list of behaviors you can't currently detect]

---

SIGNAL ARCHITECTURE DESIGN:

For each signal, define the exact product event thresholds that trigger a play. Use cohort analysis data from your analytics tool to validate these thresholds — the goal is signals that are predictive of conversion, not just activity.

SIGNAL TYPE 1: POWER USER ACTIVATION (PQL — Product Qualified Lead)

Define your Aha Moment Sequence (customize based on your product):
- Core action threshold: [e.g., "User completes ≥3 of the following core product actions within first 7 days of trial: project_created, data_imported, report_generated, integration_connected, team_member_invited"]
- Session depth signal: [e.g., "≥5 sessions within first 7 days AND average session duration ≥8 minutes"]
- Feature depth signal: [e.g., "Accessed ≥3 distinct product modules OR triggered at least 1 advanced feature (API call, custom field creation, automation rule)"]
- Social signal: [e.g., "Invited ≥1 team member OR connected a company SSO/workspace identity — indicating organizational commitment"]

Scoring model (customize weights based on your conversion data):
- Aha moment sequence complete: 40 points
- Session depth threshold met: 20 points
- Feature depth threshold met: 25 points
- Social/team signal: 15 points
- Total ≥ 75 points: PQL confirmed → trigger Play 1

ICP enrichment at signal trigger (via Clay):
- Company domain from email → enrich: employee count, industry, tech stack, funding stage, LinkedIn company URL
- Individual user → enrich: job title, seniority level, LinkedIn profile URL, department, buying authority estimate
- CRM check: is this account already tracked? Is there a parent account? Is there an open opportunity?
- ICP fit score: score 0-100 against your defined ICP — only route to human AE if score ≥ 60; below 60 goes to AI SDR or in-app messaging

---

SIGNAL TYPE 2: EXPANSION / UPGRADE INTENT (for existing paid accounts AND freemium accounts hitting limits)

Paid account expansion signals:
- Seat utilization threshold: [e.g., "Account has filled ≥80% of licensed seats AND at least 1 new team_member_invited event in past 14 days (shows active growth, not just stale seats)"]
- Usage tier ceiling: [e.g., "Account has triggered the API rate limit ≥3x in past 30 days OR exported data volume exceeds 75% of plan limit"]
- Premium feature trial behavior: [e.g., "User accessed a feature locked behind next tier ≥5 times in past 7 days AND clicked the upgrade prompt ≥2 times without completing"]
- Executive engagement signal: [e.g., "A contact with VP/Director/C-suite title in the account accessed the admin/billing section for the first time — signals budget conversation may be starting"]

Freemium ceiling signal:
- Hard limit hit: [e.g., "Account has hit freemium plan limit (project count, seat count, storage, API calls) and been shown the upgrade gate ≥3 times in past 14 days"]
- Usage velocity signal: [e.g., "Account's resource consumption grew ≥30% week-over-week for 3 consecutive weeks — they're scaling and will need to upgrade within 30-60 days"]

---

SIGNAL TYPE 3: DORMANCY / RE-ENGAGEMENT (before trial expiration)

Dormancy pattern definition:
- Initial activation confirmed: [e.g., "User logged in ≥3 times in days 1-5 of trial AND completed at least 1 core action"]
- Drop-off detected: [e.g., "Zero product events in past 5+ days, with ≥4 days remaining in trial"]
- High-value dormancy (worth human intervention): [e.g., "Dormant account with ICP fit score ≥70 AND initial session depth ≥8 minutes — user saw value but got stuck or deprioritized"]
- Low-value dormancy (AI/lifecycle email only): [e.g., "Dormant account with ICP fit score <50 OR fewer than 2 core actions completed before drop-off"]

---

THE THREE PLAYS — DETAILED DESIGN:

PLAY 1: POWER USER ACTIVATION → IMMEDIATE SALES ASSIST

Trigger: PQL score ≥ 75 AND ICP fit score ≥ 60
Response SLA: First touch within 60 minutes of signal detection (the highest-intent window)
Sender routing:
- ICP score ≥ 80: AE-led outreach (high-value deal)
- ICP score 60-79: AI SDR first touch (qualify before AE time)
- ICP score <60: In-app message only (no human outreach)

Touch 1 (within 60 minutes — email or LinkedIn, depending on available data):
Sender: AE or AI SDR named persona
Subject formula: "How [Company Name] is using [Product Name]" OR "[First Name] — noticed something in your [Product Name] trial"
Body structure:
- Sentence 1: Acknowledge specific product behavior (reference the actual actions taken — this signals you're watching their success, not batch emailing)
- Sentence 2: Connect their behavior to a specific business outcome (use industry-specific language based on enriched company profile)
- Sentence 3: Offer something of value — a use case walkthrough, a template from a similar company, or a 15-minute "what's working for companies like yours" call
- CTA: Single, specific ask — not "book a demo" (too threatening at this stage) but "reply with your biggest priority for [relevant department] this quarter and I'll send you the exact template [Similar Company] used"

Touch 2 (Day 3 — if no reply to Touch 1):
- Product milestone congratulations + social proof asset: share a case study or ROI benchmark from a company at same stage with similar usage pattern
- Subtle urgency: "teams like yours typically see [X outcome] within [Y timeframe] once they add [next feature they haven't used yet]"

Touch 3 (Day 7 — if no reply):
- Direct offer: 20-minute personalized product walkthrough focused on their specific use case (inferred from product behavior)
- OR: In-app triggered message surfaced on next login — "Want a personalized setup guide for [company type] teams?"

Touch 4 (Day 14 — if no reply):
- Handoff to long-term lifecycle nurture + quarterly check-in
- Internal signal: tag as "High-Intent / No Response" for re-prioritization if they return to active product usage

---

PLAY 2: EXPANSION SIGNAL → PROACTIVE UPGRADE CONVERSATION

Trigger: Paid account expansion signal OR freemium ceiling signal detected
Response SLA: CSM or AE contact within 24 hours
Sender routing:
- Current paid customer: CSM who owns the account (not AE — this is retention-and-expand, not new logo)
- Freemium account with no owner: AE by territory or round-robin

Guiding philosophy: The worst upgrade conversation happens when a customer hits a hard limit and gets blocked. The best upgrade conversation happens 30-60 days before the limit, when you can frame expansion as proactive investment in their growth — not as a forced hand.

Touch 1 (Day 1 after signal — email from CSM or AE):
Subject formula: "[Company Name]'s [Product Name] usage is growing — wanted to flag something proactively"
Body structure:
- Paragraph 1: Specific acknowledgment of their growth metric (seats filled, usage volume, API calls) — framed as a positive signal ("your team is getting serious value from the platform")
- Paragraph 2: Transparent flag — "at your current growth rate, you'll likely hit [limit] within [timeframe]. I wanted to reach out before you hit that wall, not after."
- Paragraph 3: Offer a 20-minute commercial review — not a hard sell, but a "let's map out what the next tier unlocks and whether the math makes sense for where you're going"
- CTA: Single calendar link or reply-to-confirm offer

Touch 2 (Day 5 — if no response from paid customer):
- Internal escalation: flag to VP CS or AE manager if account ARR ≥ [threshold] — high-value expansion at risk
- External touch: different communication channel (LinkedIn DM from AE, if CSM hasn't connected)

Touch 3 (Day 10 — for freemium ceiling accounts):
- If account has hit hard limit and not responded: trigger in-app upgrade prompt at next login with personalized context ("Your team has [X projects / Y seats / Z API calls] — you're at your plan limit. Here's what teams like yours unlock when they upgrade...")
- Simultaneously: create a trial of the next tier for the admin user (if your product allows it) with a personal note from the AE

---

PLAY 3: DORMANCY → RE-ENGAGEMENT BEFORE TRIAL EXPIRES

Trigger: Initial activation confirmed + 5+ days zero activity + ≥4 trial days remaining
Response SLA: Re-engagement touch within 4 hours of dormancy signal detection
Sender routing:
- ICP score ≥ 70: Human AE or AI SDR (high recovery value)
- ICP score <70: Automated lifecycle email sequence only

Dormancy re-engagement philosophy: Most trial drop-off is not intent abandonment — it's friction, confusion, or reprioritization. The goal of re-engagement is to remove the specific barrier that stopped them, not to pitch again.

Touch 1 (within 4 hours — email or in-app message):
Subject formula: "[First Name] — are you stuck anywhere in [Product Name]?" OR "Saw you set up [specific action] — curious if [common barrier] got in the way"
Body structure:
- Opening: Acknowledge the specific point where their activity stopped (use product event data — "I noticed you connected your [integration] but haven't run your first [core workflow] yet")
- Body: Name the 2-3 most common reasons people pause at that exact step, with a micro-solution for each (this shows competence and builds trust instantly)
- CTA: Pick-a-path format — "Reply with the one that matches your situation and I'll send you the 5-minute fix"

Touch 2 (Day 3 — if no response):
- Extend trial by [X days] as a goodwill gesture if your product allows it — mention it in the email ("I added [X] days to your trial so you have time to actually test this")
- Attach a specific quick-win template, checklist, or video walkthrough calibrated to their industry/use case (inferred from enrichment data)

Touch 3 (24 hours before trial expires):
- Urgency-based final touch: "Your trial expires tomorrow — here's what you'd lose access to" (list their specific in-progress work if storable: projects, data, configurations)
- Offer: 15-minute emergency setup call with a product specialist to help them hit their first win before the trial ends

---

ICP FIT SCORING MODEL (for product signal enrichment):

Score each trial or freemium account 0-100 across these dimensions at signal detection:
- Industry match (0-25): [25 = top-tier vertical by win rate, 15 = secondary vertical, 0 = out-of-ICP industry]
- Company size match (0-25): [25 = dead center of ICP headcount range, linear scale outward]
- User seniority (0-20): [20 = economic buyer title, 15 = champion/end user title, 5 = individual contributor, 0 = unidentifiable]
- Tech stack signals (0-15): [presence of complementary tools in your integration ecosystem = active buyer, shared stack = easy sales story]
- Intent overlay (0-15): [Bombora/G2 intent for your category active = in-market now; no intent data = neutral]

Routing thresholds:
- Score 75-100: AE-led play, respond within 60 minutes
- Score 50-74: AI SDR first touch, AE notified but not yet engaged
- Score 25-49: Lifecycle email automation only, no human outreach
- Score 0-24: In-app only, CRM tag for future monitoring

---

CRM WORKFLOW AUTOMATION:

HubSpot setup:
- Custom Contact property: "PQL Score" (numeric, calculated) + "PQL Signal Type" (dropdown: Power User / Expansion / Dormancy) + "PQL Detected At" (datetime)
- Custom Company property: "PLG Stage" (dropdown: Trial / Freemium / PQL - Pending Play / Sales Assist Active / Converted)
- Workflow 1 (PQL trigger): When "PQL Score" ≥ 75 AND "Lifecycle Stage" = Trial → create Deal in "PLG Pipeline" → assign to AE by territory rule → create Task "Reach out within 60 minutes" → send Slack alert to AE
- Workflow 2 (Expansion trigger): When "Expansion Signal Detected" property set to Yes AND Company = Customer → create Task for owning CSM → create "Expansion" deal in CRM linked to existing account
- Workflow 3 (Dormancy trigger): When "Dormancy Signal Detected" = Yes → enroll in re-engagement email sequence → create Task for AE if ICP score ≥ 70
- Pipeline view: Create dedicated "PLG Sales Assist" pipeline with stages: Signal Detected → Play Sent → Meeting Booked → Evaluation → Closed Won / Lost

Salesforce setup:
- Custom Lead field: "PQL Score" + "Signal Type" + "Signal Detected Date"
- Auto-convert Lead to Contact/Account/Opportunity when PQL Score ≥ 75 AND ICP Fit Score ≥ 60
- Lead Assignment Rule: Route by territory + ICP score — top tier leads (score ≥ 80) go to senior AEs, mid-tier go to SDR queue
- Opportunity Source: "PLG - Power User Signal" / "PLG - Expansion Signal" / "PLG - Dormancy Recovery"
- Salesforce Flow: On Opportunity creation with PLG source → auto-create Activity Log "PQL Detected" → send Slack notification to AE + manager

---

MEASUREMENT FRAMEWORK:

Real-time signal monitoring dashboard:
- PQLs detected today / this week / this month (by signal type)
- Plays triggered vs. total PQLs (coverage rate — target ≥ 95%)
- Time from signal detection to first touch (target ≤ 60 min for Play 1, ≤ 4 hours for Play 3)
- Plays open / plays responded / plays converted to meeting

Conversion funnel metrics (weekly):
- PQL → Meeting booked rate: target ≥ 25% for Play 1 (vs. ~8% cold outbound)
- Meeting → Opportunity rate: target ≥ 60% for signal-sourced meetings
- Play 2 → Upgrade rate: target ≥ 35% for expansion signals (customers who upgrade after proactive outreach vs. before hitting hard limit)
- Play 3 → Trial extension conversion: target ≥ 20% of re-engaged dormant users continue to paid

Revenue attribution (monthly):
- PLG-signal-sourced ARR as % of total new ARR
- PLG expansion ARR as % of total expansion ARR
- CAC for PLG-sourced pipeline vs. outbound-sourced pipeline (expect 60-80% lower)
- Payback period comparison: PLG-converted vs. sales-led

Signal threshold optimization (quarterly):
- Cohort analysis: what product events (and at what thresholds) are most predictive of ≥90-day retention?
- A/B test signal thresholds: compare conversion rates for PQL score ≥ 70 vs. ≥ 75 vs. ≥ 80
- False positive rate: what % of PQLs routed to AEs didn't convert to opportunity? (Target <30%)
- Signal-to-revenue latency: average days from signal detection to closed-won by signal type

---

OUTPUT STRUCTURE REQUIRED:

1. PRODUCT EVENT SCHEMA: The exact event names, properties, and threshold values that define each signal for your specific product — formatted as a spec you can hand directly to your product analytics engineer to validate and instrument

2. CLAY TABLE BUILD SPEC: Exact columns, enrichment waterfall steps, ICP scoring formula, and routing logic for each signal type — including which Clay enrichment actions to run and in what order to minimize credit spend

3. THREE PLAY SEQUENCES (full copy): All email touches for Play 1, Play 2, and Play 3 — including subject lines, full body templates with [personalization variables] drawn from product events and enrichment data, and CTA language

4. ROUTING DECISION TREE: A simple if/then logic chart that determines for any given signal: who sends the play (AE / AI SDR / CSM / in-app / lifecycle email), how quickly, and what the escalation path is if no response

5. CRM AUTOMATION SPECS: HubSpot or Salesforce workflow logic, field mappings, Deal/Opportunity creation rules, and Slack alert formats — in plain-English spec ready to hand to a RevOps admin

6. MEASUREMENT DASHBOARD SPEC: Which metrics to track, in which tool, at which cadence — plus how to report "PLG pipeline contribution" at the monthly revenue review so leadership understands the PLG motion's financial value

7. SIGNAL OPTIMIZATION ROADMAP: A 90-day plan for refining signal thresholds using cohort data — including how to run A/B tests on PQL score cutoffs and how to add net-new signals as your product instrumentation matures

## Example Input/Output

**Example Company: Fieldvault (AI-Powered Field Service Management Platform)**

**Input provided:**
- Company: Fieldvault, AI-powered scheduling and compliance platform for enterprise field service operations
- Motion: Freemium (unlimited seats, limited to 3 active job sites) + sales assist for accounts with ≥10 job sites or $8K+ ACV estimate
- Analytics: Amplitude
- CRM: HubSpot Sales Hub Professional
- Sales assist team: 5 AEs covering accounts by geo + deal size
- Monthly trial starts: 290 new freemium signups, 9% converting to paid
- Key product events: job_site_created, crew_scheduled, inspection_completed, report_exported, integration_connected (ServiceTitan, Salesforce Field Service), team_member_invited
- Aha moment: accounts that complete 1 job_site_created + 1 crew_scheduled + 1 report_exported within 10 days retain at 81% vs. 19% for those who don't

**Output excerpt — Play 1 signal definition and Touch 1 for Fieldvault:**

*PQL Signal Architecture:*
- Aha moment threshold: job_site_created ≥1 AND crew_scheduled ≥1 AND report_exported ≥1 within first 10 days = 40 points
- Session depth: ≥4 sessions in first 10 days AND average session duration ≥7 minutes = 20 points
- Feature depth: inspection_completed ≥1 OR integration_connected ≥1 = 25 points
- Social signal: team_member_invited ≥1 = 15 points
- PQL threshold: ≥ 75 points triggers signal

*Detection event:* Marcus Okafor, Operations Director at ClearPath Industrial Services (manufacturing, 340 employees, Denver), triggered PQL score of 88 on Day 8 of freemium trial.

*Clay enrichment result:*
- Company: ClearPath Industrial Services | 340 employees | Manufacturing/Facilities | Series A, $12M raised
- Tech stack: ServiceTitan detected (Fieldvault integration partner) | Salesforce detected
- ICP fit score: 82/100 (manufacturing ✓, 300+ employees ✓, ServiceTitan integration signal ✓, no Bombora intent data available)
- User: Marcus Okafor, Operations Director | LinkedIn confirmed | Buying authority: likely influencer, economic buyer likely VP Operations or COO

*Play 1 triggered — AE Keisha Rodriguez (Mountain West territory) sends within 47 minutes of signal detection:*

**Email Touch 1:**
Subject: How ClearPath is using Fieldvault (and what I'd add next)

"Marcus — I noticed your team has already scheduled crews across a job site and exported your first compliance report in under two weeks. For a manufacturing operation your size, that's fast.

Most operations teams at 300+ employee manufacturers who get that far in Fieldvault have one thing in common: they connected ServiceTitan within the first 30 days and cut their scheduling-to-invoice cycle by 40-60%. I noticed ClearPath is already on ServiceTitan — the two-way sync takes about 20 minutes to set up.

Happy to walk you through exactly how two Denver-area manufacturers did it — including one that handled 8 active job sites simultaneously in their first month.

Reply with your biggest compliance headache right now and I'll send you the template they used."

*Marcus replied within 2 hours:* "Yes — our biggest issue is tracking inspector certifications across sites. Can we talk Friday?"

*Outcome:* Demo booked Day 8, opportunity created at $14,400 ACV. Closed in 38 days.
*Benchmark:* Fieldvault's average cold outbound-to-close: 91 days, $10,200 ACV.

---

**Play 2 example — Expansion signal for existing paid customer:**

*Detection event:* Thorngate Utilities (customer, $22,000 ARR, 8 licensed job sites) triggered expansion signal: 7/8 sites active, crew_scheduled events up 34% week-over-week for 3 consecutive weeks, 2 upgrade_prompt_clicked events in past 7 days.

*CSM Lauren Park's outreach (Day 1 of signal):*

Subject: Thorngate's Fieldvault usage is growing fast — wanted to flag something

"Hi Daniel — Thorngate's team has been incredibly active this month. You're running 7 of your 8 licensed sites at full capacity, and your scheduling volume has grown 34% week-over-week for three straight weeks.

At your current growth rate, you'll hit your site limit within 30-45 days. I wanted to flag that proactively rather than have your team hit a wall mid-operation.

A quick 20-minute review would let us map out what the next tier unlocks (unlimited sites, automated certification tracking, priority support) and whether the numbers make sense for where Thorngate is heading.

I can do Tuesday at 2pm MT or Thursday at 10am MT — which works?"

*Outcome:* Daniel replied same day, upgrade call scheduled. Thorngate expanded from 8 to unlimited sites at $38,000 ARR. NRR impact: +$16,000.

## Success Metrics

**Week 1-4 (system validation):**
- 100% of product analytics events flowing correctly into Clay signal detection table
- PQL detection latency ≤ 15 minutes from product event to CRM record update
- Zero missed PQLs with score ≥ 75 (validate against manual weekly cohort pull)
- Play coverage rate: ≥ 95% of PQL signals receive a play within SLA windows

**Month 1-3 (play performance):**
- Play 1 reply rate: target ≥ 20% (heavily personalized behavioral email outperforms generic trial email by 3-5x)
- Play 1 PQL → meeting booked rate: target ≥ 18%
- Play 2 expansion signal → upgrade/upsell rate: target ≥ 30%
- Play 3 dormancy re-engagement → continued trial rate: target ≥ 18%
- Overall trial-to-paid conversion rate: target 1.5x baseline within 90 days of system launch

**Month 3-12 (revenue impact):**
- PLG-signal-sourced ARR as % of total new ARR: target 25-40% (depending on proportion of business that enters via self-serve)
- CAC comparison: PLG-sourced pipeline should cost 60-80% less per dollar of ARR than outbound-sourced pipeline
- ACV comparison: signal-sourced deals should close at 15-30% higher ACV than cold outbound (signals surface high-intent, high-fit accounts that self-selected into product depth)
- Sales cycle: signal-sourced deals should close 30-50% faster than cold outbound equivalents

**Signal optimization scorecard (quarterly):**
- False positive rate: % of PQLs routed to AEs that did not convert to opportunity within 30 days (target <30%)
- Signal precision score: correlation coefficient between PQL score and actual 90-day retention for converted accounts
- Threshold optimization: has the PQL score threshold been validated or adjusted based on cohort data?

## Related Prompts

- [GTM Engineering Program Architecture](./AI-Powered-B2B-SaaS-GTM-Engineering-Program-Architecture-&-Clay-Powered-Autonomous-Signal-Based-Outbound-Revenue-Intelligence-Engine.md)
- [Champion Job Change Signal Tracking](./AI-Powered-B2B-SaaS-Champion-Job-Change-Signal-Tracking-&-Warm-Revenue-Activation-Intelligence-Engine.md)
- [Website Visitor Intelligence & Account-Based Inbound Pipeline](./AI-Powered-B2B-SaaS-Website-Visitor-Intelligence-&-Account-Based-Inbound-Pipeline-Automation-Revenue-Intelligence-Engine.md)
- [Free Trial Activation Funnel CRO](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Free-Trial-Activation-Funnel-CRO-&-Time-to-Value-Conversion-Intelligence-Engine.md)

## Integration Tips

**Amplitude / Mixpanel / Pendo:**
- Build a dedicated "PQL Signal" chart in Amplitude that tracks the exact event sequence defining your aha moment — set up a Slack alert via Amplitude's built-in notification system when any account crosses the threshold, as a redundant signal layer alongside Clay
- Use Amplitude's cohort export (or Pendo's "Identify" API) to push qualified accounts directly into Clay via webhook or CSV sync — set the export to trigger on cohort membership change (new PQL detected), not on a fixed schedule, so signals arrive in real-time
- In Pendo, use "Guides" (in-app messages) triggered by behavioral conditions as the in-app arm of your Play 1 and Play 3 sequences — coordinate with email timing so in-app and email don't fire simultaneously

**Clay:**
- Build three dedicated Clay tables (one per signal type) to keep enrichment logic clean and credit costs auditable
- For Play 1 PQL enrichment: use Apollo or Clearbit for company firmographic data, LinkedIn for individual title/seniority, Bombora for intent data overlay — run in waterfall order (Apollo first as cheapest, LinkedIn second, Bombora only if company qualifies on ICP score ≥ 50)
- Use Clay's CRM sync (native HubSpot and Salesforce integrations) to push enriched records and signal properties back to CRM within 10 minutes of detection — avoid batch exports that introduce lag

**HubSpot:**
- Create a dedicated "PLG Pipeline" pipeline in HubSpot separate from your AE-sourced and marketing-sourced pipelines — this allows clean attribution and conversion rate tracking by source
- Use HubSpot's "Behavioral Events" (custom event API) to receive product analytics events directly if you don't want to route through Clay — trigger workflows natively in HubSpot off product events for simpler stacks
- Set up a "PLG Signals" dashboard in HubSpot reporting with: PQLs detected this week, plays sent, replies, meetings booked, opportunities created — review weekly in revenue sync

**Salesforce:**
- Use Salesforce's custom Lead fields to store PQL Score and Signal Type, and configure Lead Assignment Rules to route by score threshold + territory — this automates routing without requiring manual AE review of a shared queue
- Build a Salesforce Flow that auto-creates an Opportunity from a Lead when PQL Score ≥ 75 AND ICP Score ≥ 60, populating Lead Source as "PLG Signal - [Type]" — this keeps attribution clean from first signal to close
- Install Amplitude's Salesforce integration (or use Segment as middleware) to stream product events directly into Salesforce Activity history — gives AEs full product context on the Contact/Account record without needing to leave Salesforce

**Outreach / Salesloft:**
- Create dedicated sequences for each play type (Play 1 Power User, Play 2 Expansion, Play 3 Dormancy) in Outreach/Salesloft — configure auto-enrollment via API when CRM workflow triggers, so AE receives a Slack notification AND the contact is already queued in their sequence
- Use Outreach's "Personalization Tokens" or Salesloft's dynamic fields to pull in product event data (the specific actions the user took) directly into email templates — this is the key differentiator between a generic trial email and a behavior-aware message that gets 3x the reply rate

**Slack:**
- Create a #plg-signals Slack channel with bot-posted alerts for every Play 1 PQL: format as: [signal type emoji] [Contact Name] @ [Company] | PQL Score: [X] | ICP Score: [Y] | Play: [Play 1] | Owner: @[AE] | SLA: respond within 60 minutes | [CRM Link]
- Build a daily digest for Plays 2 and 3 posted to #plg-pipeline-review each morning with: expansion signals pending action, dormancy triggers pending re-engagement, and any SLA breaches from prior day

## Troubleshooting

**Problem: PQL score thresholds are generating too many false positives — AEs are getting flooded with low-quality signals and ignoring alerts**
- Fix: Run a cohort analysis in Amplitude/Mixpanel comparing PQL score buckets (60-69, 70-79, 80+) against 90-day retention and revenue conversion rates. Raise the AE-routed threshold to the score level where ≥40% of accounts convert to paid within 60 days. Route the 60-74 score bucket to AI SDR outreach instead of AE. Also add the ICP fit score as a mandatory gate — even a perfect PQL score means nothing if the company is out-of-ICP.

**Problem: Play 1 email reply rates are below target even with personalized product event references**
- Fix: The personalization is likely too generic — "I noticed you scheduled your first crew" is weak. Reference the specific outcome, not just the action: "I noticed you exported a compliance report for [Job Site Name] on [Date]" (use actual property values from the product event, not just the event name). Also check send timing — Play 1 Touch 1 should fire within 60 minutes of signal detection; if your workflow introduces delays of 4+ hours, intent has cooled significantly. Finally, test sending from a human AE name vs. a generic "team@" address — personalized sender consistently outperforms by 40-60%.

**Problem: Play 2 expansion outreach is triggering too late — customers are already hitting hard limits before CSM reaches them**
- Fix: Recalibrate expansion signals to earlier thresholds. If the current trigger is "80% of seat limit reached," move it to 65%. Add a growth velocity signal (e.g., usage growing ≥20% week-over-week for 2 consecutive weeks) as an early trigger before the limit itself is relevant. Also review CSM response SLA — if expansion signals are being created but CSMs aren't acting within 24 hours, the problem is execution, not signal timing. Consider auto-sending Touch 1 from the CSM's name via Outreach/Salesloft as a backup if no manual outreach is logged within 8 business hours of signal.

## Version History
- v1.0: Initial creation (auto-generated)
