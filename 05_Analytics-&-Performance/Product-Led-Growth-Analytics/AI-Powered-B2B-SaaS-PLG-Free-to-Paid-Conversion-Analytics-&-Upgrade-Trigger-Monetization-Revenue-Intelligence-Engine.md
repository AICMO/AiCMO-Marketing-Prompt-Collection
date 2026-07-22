# AI-Powered B2B SaaS PLG Free-to-Paid Conversion Analytics & Upgrade Trigger Monetization Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** product-led-growth, PLG, free-to-paid, monetization, upgrade-triggers, PQL, conversion-analytics, SaaS-revenue, pricing-analytics

## Overview
Deploys an AI analytics engine to identify the precise in-product behavioral signals that predict free-to-paid conversion, quantify upgrade friction at every stage of the monetization funnel, and generate a prioritized playbook for maximizing revenue from your existing free/trial user base. Use this when your PLG motion generates strong activation but free-to-paid conversion remains below 5%, when pricing page visitors aren't converting, or when you need to build a PQL scoring model that reliably surfaces users ready to buy.

## Quick Copy-Paste Version

You are a senior PLG monetization analytics strategist specializing in free-to-paid conversion optimization for B2B SaaS.

I need a comprehensive free-to-paid conversion analysis for my product. Here is our situation:

Company: [Your Company Name]
Product: [What it does in 1 sentence]
PLG motion: [Free trial / Freemium / Reverse trial]
Pricing model: [Per seat / Usage-based / Feature-tiered / Hybrid]
Free plan limitations: [e.g., "5 users, 3 projects, 1,000 API calls/month, no SSO"]
Paid plan entry price: [$X/month or $X/year]
ACV range (paid tiers): [$X – $Y/year]
Current free/trial user base: [Number of active free users]
Monthly new free signups: [Number]
Current free-to-paid conversion rate: [X%]
Average time-to-upgrade (for converting users): [X days from signup]
Top paid feature or limit that drives most upgrades: [e.g., "Seat limit, API quota, SSO, advanced reporting"]
Sales-assist threshold: [Pure self-serve / Sales assist above $X ACV / All accounts get SDR outreach]
Product analytics tool: [Mixpanel / Amplitude / Heap / Pendo / Custom]
CRM: [Salesforce / HubSpot]

Analyze my free-to-paid conversion funnel and produce:

1. CONVERSION RATE BENCHMARKING
   - Benchmark my free-to-paid conversion rate against PLG industry standards: Freemium (2–5%), Free Trial (15–25%), Reverse Trial (12–20%)
   - Identify the revenue gap: (benchmark conversion rate − current rate) × free user base × ACV = annual revenue opportunity
   - Segment conversion rate by: acquisition channel, ICP fit score, company size, signup cohort month, primary use case, geographic region
   - Identify the 3 highest-performing segments by conversion rate and reverse-engineer what makes them convert

2. UPGRADE TRIGGER EVENT IDENTIFICATION
   - Define the 10 in-product behavioral events most correlated with free-to-paid upgrade within 30 days
   - For each trigger event, provide: event name, correlation coefficient with upgrade (scale 0–1), median time between first trigger and upgrade, % of free users who trigger this event, % of users who trigger this event AND upgrade within 30 days
   - Identify the "monetization tipping point": the single combination of events that produces 60%+ probability of upgrade within 14 days
   - Design a PQL (Product Qualified Lead) scoring model using a weighted combination of: recency of activity, depth of feature usage, breadth of feature adoption, team expansion signals, limit-approach signals

3. PAYWALL & FEATURE GATE ANALYTICS
   - Map every paywall encounter in the product: which features are gated, which limits exist, how often users hit each gate
   - For each gate/paywall, calculate: monthly gate-hit rate (% of free users hitting this limit), conversion rate of users who hit this gate within 7 days, revenue generated per gate-hit user
   - Identify the "golden gate": the feature limit whose removal produces the highest free-to-paid conversion rate
   - Identify "false gates": limits that free users hit but don't convert — indicating the limit is either too tight (causing churn) or too loose (not driving urgency)
   - Design a gate-hit personalization sequence: when a user hits a specific paywall, what message, timing, and offer produces highest conversion?

4. PRICING PAGE ANALYTICS
   - Analyze the pricing page funnel: Free user visits pricing page → reads plan comparison → clicks upgrade CTA → enters payment flow → completes purchase
   - Calculate drop-off at each stage and revenue at risk per stage
   - Identify top 3 conversion friction points on the pricing page (e.g., annual vs. monthly toggle, plan confusion, trust signals missing, payment friction)
   - Design 3 pricing page A/B tests with projected conversion lift and ARR impact

5. UPGRADE FLOW ANALYTICS
   - Map the complete upgrade checkout flow: click upgrade → plan selection → seat/usage configuration → payment entry → confirmation
   - Identify the highest drop-off step in the upgrade flow with revenue quantification
   - Calculate upgrade flow completion rate vs. SaaS benchmarks (target: 75%+ completion once initiated)
   - Propose 3 checkout optimizations ranked by estimated conversion lift

6. TIME-TO-UPGRADE DISTRIBUTION & URGENCY OPTIMIZATION
   - Plot upgrade probability as a function of days since signup
   - Identify: median time to upgrade for converting users, peak upgrade windows (day ranges with highest conversion volume), urgency decay curve (at what day does upgrade probability drop by 50%? 80%?)
   - Design a time-based intervention sequence: escalating upgrade nudges triggered by day-since-signup + behavioral signals
   - For trial users: design trial expiry conversion sequence (days 10, 12, 13, 14, and 7-day post-expiry win-back)

7. COHORT MONETIZATION ANALYSIS
   - Analyze conversion rate by signup cohort (monthly): identify months with above/below-average conversion rates and diagnose causes
   - Calculate time-to-upgrade by acquisition channel: which channels produce fastest-converting free users?
   - Identify the "long tail" opportunity: free users who have been on free plan 90+ days but show recent usage spikes — design a re-engagement monetization campaign for this segment
   - Project: if the top 3 monetization improvements are implemented, what is the 12-month ARR impact?

Format output as a PLG Monetization Intelligence Brief with an upgrade trigger heatmap, paywall performance matrix, PQL scoring model, and a 90-day conversion rate improvement roadmap.

## Advanced Customizable Version

ROLE: You are an AI-powered PLG Monetization Intelligence Engine. You combine the analytical precision of a product data scientist, the revenue optimization instincts of a SaaS CFO, and the user psychology expertise of a growth product manager. Your outputs are designed for simultaneous consumption by the CEO, CPO, VP Growth, Head of Pricing, and VP Revenue Operations.

CONTEXT:
- Company: [Company Name]
- Stage: [Seed / Series A / Series B / Growth]
- ARR: [Current ARR]
- Monthly Recurring Revenue from PLG-self-serve: [$X MRR]
- PLG motion: [Freemium (feature-limited) / Free Trial (time-limited, X days) / Reverse Trial (full access → downgrade after X days) / Usage-based free tier]
- Pricing model: [Per seat / Usage-based / Feature-tiered / Hybrid]
- Free plan description: [Limits: X users, Y projects, Z API calls/month; Gated features: list]
- Paid plan tiers: [Plan 1: $X/mo/seat, includes: [features]; Plan 2: $Y/mo/seat, includes: [features]; Plan 3: Enterprise, custom pricing]
- ACV range: [$X – $Y/year]
- Primary ICP: [Job title, company size, industry]
- Secondary ICP: [Job title, company size, industry]
- Sales-assist threshold: [Pure self-serve / Sales assist triggered above $X ACV / SDR outreach for accounts above Y seats]
- Current active free/trial user base: [Number of accounts]
- Monthly new free signups: [Number of accounts]
- Current free-to-paid conversion rate (MoM cohort): [X%]
- Average time-to-upgrade (for converting accounts): [X days]
- Conversion rate by channel (if known): [Organic: X%, Paid: X%, Referral: X%, Product virality: X%]
- Top 3 upgrade trigger events (if known): [e.g., "Hits seat limit, exports first report, invites 5th team member"]
- Biggest objections to upgrade (if known from sales calls/chat): [e.g., "Price too high, need to justify to finance, don't need paid features yet"]
- Product analytics stack: [Mixpanel / Amplitude / Heap / Pendo / Segment CDP / Custom]
- CRM: [Salesforce / HubSpot]
- In-app messaging: [Intercom / Appcues / Userpilot / Chameleon / Custom]
- Email automation: [Customer.io / Braze / HubSpot / Klaviyo]
- Current pricing page URL structure: [Single page / Dedicated /pricing page / In-app upgrade modal]
- Payment processor: [Stripe / Recurly / Chargebee / Zuora]

OBJECTIVE: Produce a comprehensive PLG Monetization Intelligence Report that: (1) diagnoses free-to-paid conversion gaps with full revenue quantification, (2) identifies and ranks upgrade trigger events with a deployable PQL scoring model, (3) maps paywall and pricing page friction with conversion optimization roadmap, (4) designs time-based intervention sequences that convert free users at peak upgrade probability windows, and (5) delivers a 90-day monetization improvement plan with projected ARR impact.

---

MODULE 1: MONETIZATION FUNNEL ARCHITECTURE & REVENUE GAP ANALYSIS

Conversion Rate Benchmarking:
Compare current free-to-paid conversion rate against:
- Industry benchmark for our PLG motion type:
  * Freemium: 2–5% (top quartile: 5–8%)
  * Free Trial (14-day): 15–25% (top quartile: 25–35%)
  * Free Trial (30-day): 8–18% (top quartile: 18–25%)
  * Reverse Trial: 12–20% (top quartile: 20–30%)
  * Usage-based free tier: 3–8% (top quartile: 8–15%)
- Revenue gap calculation: (Benchmark conversion rate − Current rate) × Active free user base × Average ACV = Annual Revenue Opportunity
- Best-in-class PLG companies at our stage (Series A benchmarks: Slack, Figma, Notion, Linear) and their reported conversion strategies

Conversion Rate Segmentation:
Analyze conversion rate across every available dimension:
- By acquisition channel: Organic search / Paid search / Paid social / Product virality / Referral / Outbound / Affiliate
- By ICP fit score tier: Tier 1 (perfect ICP) / Tier 2 (adjacent) / Tier 3 (off-ICP)
- By company size: 1–10 / 11–50 / 51–200 / 201–1,000 / 1,000+ employees
- By signup cohort month: identify months with >20% above-average conversion and diagnose causes
- By primary use case (if captured at signup)
- By geographic market: identify markets with above/below-average conversion rates
- By days-to-first-activation: users who activate within 24h vs. 24–72h vs. 72h+ vs. never activated

For each segment, calculate:
- Conversion rate (%)
- Conversion rate index vs. overall average (1.0 = average, 2.0 = 2x average)
- Estimated revenue per 100 free signups from this segment
- Strategic implication: should we acquire more of these users, convert more, or deprioritize?

---

MODULE 2: UPGRADE TRIGGER EVENT IDENTIFICATION & PQL SCORING MODEL

Upgrade Trigger Correlation Analysis:
Analyze in-product events to identify the strongest predictors of free-to-paid conversion within 30 days. For each candidate event, provide:

EVENT ANALYSIS TEMPLATE:
- Event name: [e.g., "Creates 5th project", "Exports CSV for the first time", "Invites 3rd team member", "Views pricing page 2+ times", "Hits API rate limit"]
- Event type: Feature adoption / Limit encounter / Collaboration signal / High-intent exploration / Integration trigger
- Correlation with 30-day upgrade (0–1 scale)
- Median lag from event to upgrade (days): how quickly does this event precede conversion?
- Coverage: % of all free users who trigger this event within 90 days of signup
- Precision: % of users who trigger this event AND upgrade within 30 days (avoid false positives)
- Event tier: Tier 1 (high correlation + high precision) / Tier 2 (moderate) / Tier 3 (weak signal)

Identify the top 10 Tier 1 upgrade trigger events ranked by (correlation × precision × coverage) composite score.

Monetization Tipping Point Analysis:
- Define the "conversion tipping point": the specific combination of Tier 1 trigger events whose co-occurrence produces ≥60% upgrade probability within 14 days
- Example: "User who has [triggered Tier 1 event A] AND [triggered Tier 1 event B] AND [has been active for 14+ days] AND [has not yet hit a paywall hard block] converts at 73% within 14 days"
- Design the tipping point detection query (pseudocode for Mixpanel/Amplitude JQL or SQL for data warehouse)

PQL Scoring Model:
Build a composite Product Qualified Lead score (0–100) using weighted behavioral signals:

SCORING DIMENSIONS:
1. ACTIVATION DEPTH (0–25 points)
   - Core feature adoption breadth: # of distinct primary features used in last 30 days
   - Scoring: 0 features = 0pts, 1–2 features = 8pts, 3–4 features = 15pts, 5+ features = 25pts

2. USAGE RECENCY & FREQUENCY (0–20 points)
   - Days active in last 14 days
   - Scoring: 0–2 days = 0pts, 3–5 days = 8pts, 6–9 days = 14pts, 10–14 days = 20pts

3. LIMIT PROXIMITY SIGNALS (0–25 points)
   - Usage as % of free plan limit (seats used / seat limit, API calls / API limit, etc.)
   - Scoring: <50% of limit = 0pts, 50–75% = 10pts, 76–90% = 18pts, >90% = 25pts (imminent limit hit)

4. EXPANSION & COLLABORATION SIGNALS (0–15 points)
   - Team size growth: # of members invited in last 30 days
   - Scoring: 0 invites = 0pts, 1 invite = 5pts, 2–3 invites = 10pts, 4+ invites = 15pts

5. HIGH-INTENT EXPLORATION SIGNALS (0–15 points)
   - Pricing page visits, plan comparison views, upgrade CTA clicks, billing page visits
   - Scoring: 0 high-intent actions = 0pts, 1 action = 5pts, 2–3 actions = 10pts, 4+ actions = 15pts

PQL TIER DEFINITION:
- PQL Score 0–29: Low intent — nurture with product education content
- PQL Score 30–49: Medium intent — enroll in upgrade email sequence
- PQL Score 50–69: High intent — trigger in-app upgrade nudge + sales alert for accounts above [$X ACV threshold]
- PQL Score 70–89: Very high intent — trigger personalized upgrade offer + SDR outreach for mid-market+ accounts
- PQL Score 90–100: Imminent conversion — trigger time-sensitive upgrade incentive + immediate SDR outreach if above enterprise threshold

---

MODULE 3: PAYWALL & FEATURE GATE ANALYTICS

Paywall Performance Matrix:
For every feature gate and usage limit in the product, analyze:

GATE ANALYSIS TEMPLATE:
- Gate name: [e.g., "Seat limit", "Project limit", "API quota", "SSO/SAML", "Advanced analytics", "Custom branding", "Audit log", "Priority support"]
- Gate type: Hard block (cannot continue without upgrading) / Soft gate (can request access or see preview) / Upgrade prompt (voluntary upsell)
- Monthly gate-hit rate: % of active free accounts encountering this gate in a 30-day period
- Post-gate conversion rate (7-day window): % of accounts that upgrade within 7 days of hitting this gate
- Post-gate conversion rate (30-day window): % of accounts that upgrade within 30 days
- Revenue generated per 100 gate-hit accounts (annualized): gate-hit rate × conversion rate × ACV
- Gate effectiveness score: (post-gate conversion rate) / (industry benchmark for this gate type)

Gate Classification:
- GOLDEN GATE: High hit rate + High conversion rate → this gate is your primary monetization engine; optimize the upgrade experience at this gate first
- PRESSURE GATE: Low hit rate + High conversion rate → powerful when triggered; focus on accelerating user journey to this gate
- FALSE GATE: High hit rate + Low conversion rate → either the limit is too restrictive (causing churn before upgrade) or the value proposition for upgrading past this gate is unclear; investigate and either loosen the limit or reframe the upgrade value
- INVISIBLE GATE: Low hit rate + Low conversion rate → gate exists but rarely influences behavior; evaluate whether this gate is even discoverable or relevant

Gate-Hit Personalization Sequences:
For each Golden Gate and Pressure Gate, design a conversion sequence:

SEQUENCE TEMPLATE:
- Gate trigger: [Specific user action that hits the limit]
- Channel 1 — In-app modal (T+0 seconds): [Message headline, body, CTA, social proof element]
- Channel 2 — In-app follow-up (T+24 hours if not converted): [Personalized nudge based on use case]
- Channel 3 — Email (T+48 hours if not converted): [Subject line, body, ROI framing specific to their usage pattern]
- Channel 4 — Sales alert (T+72 hours, only if PQL score ≥50 and ACV estimate above $X): [SDR alert with account context: company, usage data, gate hit, PQL score]
- Personalization variables: [Use company name, number of team members, specific feature being blocked, usage data to show value realized so far]

---

MODULE 4: PRICING PAGE CONVERSION OPTIMIZATION

Pricing Page Funnel Analysis:
Map the complete path from free user to paid customer through the pricing surface:

Stage 1: Pricing page awareness
- % of free users who visit the pricing page at least once within 90 days of signup
- Benchmark: 35–55% of engaged free users visit pricing page within 90 days
- Primary drivers of pricing page visits: direct navigation, in-app upgrade CTAs, email links, hitting a paywall, peer recommendation

Stage 2: Pricing page engagement
- Average time on page (benchmark: 3–5 minutes for high-intent visitors)
- Plan comparison interaction rate (% who expand plan details, toggle annual/monthly)
- % who scroll to FAQ section
- % who click any plan's upgrade CTA
- Pricing page → upgrade CTA click conversion rate (benchmark: 15–25%)

Stage 3: Upgrade flow initiation
- % of CTA clickers who proceed into the checkout/upgrade flow
- Drop-off analysis: who clicks upgrade but never enters payment flow?

Stage 4: Checkout completion
- Upgrade flow completion rate: of users who enter checkout, % who complete purchase
- Benchmark: 70–85% checkout completion for pure self-serve SaaS
- Step-level drop-off in checkout flow

Stage 5: Post-purchase
- Seat/user addition rate in first 30 days post-upgrade (expansion indicator)
- Upgrade-to-churn rate within first 90 days (quality of conversions)

Pricing Page Friction Inventory:
Evaluate every friction point on the pricing page:

FRICTION TYPE 1 — PLAN CONFUSION
- Signals: Long time on page, repeated plan comparison toggling, low CTA click rate despite high traffic
- Fix: Add "Most popular for [job title]" plan badges, decision tree ("Not sure which plan? Answer 2 questions"), use case-specific plan recommendations based on signup data

FRICTION TYPE 2 — PRICE ANCHORING MISMATCH
- Signals: High entry-plan click rate but low conversion, frequent downgrade to free after upgrade
- Fix: Add ROI calculator ("At your current usage, this pays for itself if you save X hours/month"), show team savings at scale (e.g., "5 seats: $X/month vs. $Y if billed separately")

FRICTION TYPE 3 — ANNUAL PLAN HESITATION
- Signals: High monthly plan selection rate, low annual plan adoption despite discount
- Fix: Reframe annual discount as monthly savings ("Save $X every month"), add finance-friendly messaging ("One PO, no monthly approval cycles"), offer extended trial for annual commitment

FRICTION TYPE 4 — SOCIAL PROOF DEFICIT
- Signals: High bounce rate on pricing page from mid-market+ accounts
- Fix: Add tier-specific customer logos and quotes, display trust indicators (SOC 2, GDPR compliance badges), show account count ("Join 4,200 teams on [Plan Name]")

FRICTION TYPE 5 — CHECKOUT PAYMENT FRICTION
- Signals: High checkout initiation → abandonment rate, high error rate at payment entry step
- Fix: Add Apple Pay / Google Pay / ACH options, display security badges at payment step, offer "Request invoice" for enterprise accounts, enable PO number field for procurement-heavy buyers

Pricing Page A/B Test Roadmap:
Design 3 high-priority pricing page tests:

TEST 1: [e.g., Personalized plan recommendation based on signup use case]
- Hypothesis: By surfacing a pre-selected plan recommendation ("Based on your use case, most [job title]s at [company size] start with [Plan Name]"), we expect pricing page → CTA click rate to increase from [X%] to [Y%] because reducing plan choice friction accelerates the upgrade decision
- Primary metric: Pricing page → upgrade CTA click rate
- Secondary metrics: Time on page, plan selection distribution, checkout completion rate
- ARR projection: (Lift % × Monthly pricing page visitors × Checkout completion rate × ACV) = $[X] incremental ARR
- Engineering effort: 3–5 days

TEST 2: [e.g., ROI calculator embedded in pricing page vs. text-only value props]
- Hypothesis: By adding an interactive ROI calculator that uses the user's actual product usage data to calculate their personalized ROI, we expect pricing page → upgrade conversion to increase because it replaces abstract value claims with personalized financial justification
- Primary metric: Pricing page → payment complete conversion rate
- ARR projection: $[X] incremental ARR

TEST 3: [e.g., Annual plan as default vs. monthly plan as default]
- Hypothesis: By defaulting the pricing page toggle to annual billing (vs. monthly), we expect annual plan selection rate to increase from [X%] to [Y%] because anchoring bias favors the displayed default, and the annual discount becomes more salient
- Primary metric: Annual plan adoption rate among new paid customers
- ARR projection: $[X] incremental ARR from LTV improvement (annual customers churn 30–40% less than monthly)

---

MODULE 5: TIME-TO-UPGRADE DISTRIBUTION & INTERVENTION SEQUENCE DESIGN

Upgrade Timing Analysis:
Plot the upgrade probability distribution by day-since-signup:

Upgrade Urgency Curve:
- Day 0–3 (Honeymoon window): % of all eventual upgraders who convert in this window — typically 8–15%
- Day 4–14 (Primary conversion window): typically 35–50% of all eventual upgraders convert here
- Day 15–30 (Secondary conversion window): typically 20–30% convert here
- Day 31–60 (Long-tail window): typically 10–15% convert here
- Day 61–90 (Reactivation window): typically 5–8% convert here
- Day 90+ (Dormant → re-engaged): typically <5% of eventual upgraders; requires active win-back

Urgency Decay Analysis:
- At what day does the probability of upgrading drop below 50% of peak? (Define as "urgency half-life")
- At what day does the probability drop below 20%? (Define as "urgency tail threshold")
- Implication: intervention sequences should be most intensive during the primary conversion window and urgency half-life period

Time-Based Intervention Architecture:
Design a complete day-by-day upgrade intervention sequence calibrated to the urgency curve:

FOR FREEMIUM USERS (unlimited time, no trial expiry):
- Day 7 (post-signup, if activated but not upgraded): Trigger "Value realized" email — show personalized usage stats, calculate value delivered so far, introduce the feature that would unlock the most value for their use case
- Day 14 (if PQL score 30–49): Product usage digest email with "You're hitting the limits of what free can do" message
- Day 21 (if PQL score 50–69): In-app upgrade modal triggered by next login with personalized plan recommendation + team testimonial from similar company
- Day 30 (if PQL score 50–69, not yet converted): "Last chance for X offer" upgrade email with time-limited incentive
- Day 45 (if PQL score ≥70, not yet converted): SDR outreach triggered (for accounts above $X ACV threshold) with personalized video or email using product usage data
- Day 60 (if PQL score ≥50, not yet converted): Re-engagement campaign: new feature announcement + upgrade offer refresh
- Day 90 (if not upgraded but recently active): "We noticed you're still using [specific feature]" personalized reactivation offer

FOR TRIAL USERS (time-limited):
- Day 1 (post-signup): Welcome + "Here's how to get the most out of your [X]-day trial" onboarding sequence
- Day 3 (if not activated): "You haven't tried [core feature] yet" activation nudge — activation before day 7 is strongly predictive of conversion
- Day 7 (trial midpoint): Usage recap — personalized stats on value realized, preview of what paid unlocks
- Day [trial length − 4] (days before expiry): Trial expiry countdown email — "Your trial ends in 4 days" + upgrade CTA with plan recommendation
- Day [trial length − 2]: Final trial reminder — time-sensitive offer (discount, extended trial, or onboarding session)
- Day 0 (trial expiry day): "Your trial has ended" email + access downgrade notification + upgrade reactivation CTA
- Day 3 (post-expiry): Win-back email: "Come back — here's what you'd be missing"
- Day 7 (post-expiry): Final win-back with alternative offer (annual commitment discount, smaller plan, or pause option)

FOR REVERSE TRIAL USERS (full access → downgrade):
- Day 1 (post-downgrade notification): "Your premium access ends in [X] days" — emphasize features they'll lose
- Day [X−3]: Pre-downgrade reminder with list of features being removed, personalized to which features they actually used
- Day [X−1]: Final day email — emotional framing ("You've built [X] workflows, connected [Y] integrations...") + upgrade CTA
- Day 0 (downgrade day): Post-downgrade email: "It doesn't have to end here" + immediate upgrade CTA
- Day 3 (post-downgrade, if used features that are now gated): Re-engagement trigger when they attempt to access a now-gated feature

---

MODULE 6: COHORT MONETIZATION INTELLIGENCE

Cohort Performance Analysis:
For each monthly signup cohort (last 12 months), analyze:
- 30-day conversion rate (% upgrading within first 30 days of signup)
- 60-day conversion rate
- 90-day conversion rate
- 180-day "long tail" conversion rate (final capture)
- Cumulative 12-month conversion rate (maximum extraction rate for this cohort)
- Average ACV of cohort upgrades
- Cohort ARR contribution: (# upgrades × ACV)

Cohort Anomaly Detection:
- Identify the highest-performing cohort month: what drove above-average conversion? (New feature launch? Better acquisition channel mix? Pricing change? New onboarding flow?)
- Identify the worst-performing cohort month: what suppressed conversion? (Product outages? Competitive pressure? Channel quality degradation? Onboarding friction?)
- Calculate the "cohort quality score": a composite of conversion rate + ACV + 90-day retention for each cohort

Channel Quality for Monetization:
Rank acquisition channels by monetization quality:
- For each channel: conversion rate to paid, average ACV, time-to-upgrade, 90-day retention post-upgrade, cumulative ARR per 100 free signups
- Calculate "Revenue per Free Signup" by channel: which channels produce the highest-value free users?
- Strategic implication: reallocate acquisition budget toward channels producing highest Revenue per Free Signup, not just lowest Cost per Signup

Long-Tail Monetization Opportunity:
Identify the "dormant wealth" segment: free users who:
- Signed up 90+ days ago
- Were activated (reached aha moment) but never upgraded
- Have shown recent usage activity (active in last 30 days)
- Have PQL score ≥40

This segment represents users who find value in the product but haven't been converted — design a targeted win-back monetization campaign:
- Segment size and estimated ARR opportunity
- Personalized campaign message: acknowledge their loyalty, reference their specific usage history, present a compelling upgrade reason tied to their use case
- Offer structure: consider time-limited discount, extended trial of paid features, or free-to-paid migration assistance session

---

MODULE 7: 90-DAY MONETIZATION IMPROVEMENT ROADMAP

Month 1 — Instrument & Diagnose (Revenue: $0 direct, foundation building):
Week 1: Close analytics gaps — ensure upgrade trigger events are tracked in product analytics, connect CRM to product analytics for channel attribution
Week 2: Build PQL scoring model — implement scoring in Segment/Amplitude or CRM; validate against last 90 days of conversion data
Week 3: Gate performance audit — map every paywall, calculate gate-hit rates and conversion rates; identify Golden Gates and False Gates
Week 4: Baseline documentation — lock current free-to-paid conversion rate, time-to-upgrade, and pricing page conversion metrics as baseline

Month 2 — Quick Wins & High-Impact Fixes (Revenue: $[X] projected):
Week 5: Deploy PQL-triggered in-app upgrade sequences for Score 50–69 accounts
Week 6: Fix top pricing page friction point (e.g., add plan recommendation badge, fix checkout payment options)
Week 7: Launch Pricing Page A/B Test 1; deploy gate-hit personalization for Golden Gate
Week 8: Launch time-based intervention sequences for all free user segments

Month 3 — Optimize & Scale (Revenue: $[X] projected):
Week 9: Analyze Pricing Page Test 1 results; roll out winner to 100% of traffic
Week 10: Launch Pricing Page A/B Test 2; begin long-tail dormant user monetization campaign
Week 11: Deploy SDR alert system for PQL Score 70+ accounts; integrate PQL score into CRM for sales prioritization
Week 12: Conduct full 90-day monetization review; project 12-month ARR impact of improvements; plan H2 roadmap

NORTH STAR METRICS:
- Primary: Free-to-paid conversion rate (monthly cohort, 30-day window)
- Secondary: Revenue per 100 new free signups (monetization efficiency)
- Secondary: Time-to-upgrade (median days, for converting accounts)
- Secondary: Pricing page → payment complete conversion rate

TARGET: Achieve benchmark conversion rate for PLG motion type within 90 days
ARR IMPACT TARGET: +$[X] in incremental annual revenue from improved monetization efficiency

---

OUTPUT FORMAT:
Produce the complete PLG Monetization Intelligence Report as:

1. EXECUTIVE SUMMARY (1 page)
   - Current free-to-paid conversion rate vs. benchmark gap
   - Annual revenue opportunity from closing the benchmark gap
   - Top 3 highest-impact monetization improvements with estimated combined ARR lift
   - 90-day target conversion rate
   - Single most important action to take this week

2. UPGRADE TRIGGER HEATMAP
   [Table: Event | Correlation Score | Median Lag to Upgrade | Coverage | Precision | Tier]

3. PQL SCORING MODEL
   [Complete scoring rubric with dimension weights, tier thresholds, and recommended action per tier]

4. PAYWALL PERFORMANCE MATRIX
   [Table: Gate | Gate Type | Monthly Hit Rate | 7-Day Conversion | 30-Day Conversion | Revenue per 100 Hit Accounts | Gate Classification | Priority Action]

5. PRICING PAGE FUNNEL WATERFALL
   [Pricing Page Visit → Plan Comparison → CTA Click → Checkout Entry → Payment Complete]
   [With conversion rates, drop-off %, revenue at risk, and priority fix for each step]

6. TIME-BASED INTERVENTION CALENDAR
   [Day-by-day sequence with trigger conditions, channel, message framework, and expected conversion lift]

7. 90-DAY ROADMAP
   [Week-by-week action items with owner (Product/Engineering/Growth/Marketing/Sales) and success metric]

Calibrate all recommendations to our specific PLG motion, ICP, pricing model, and ACV band. Flag every assumption and provide sensitivity analysis on conversion rate projections (base case, upside case, downside case).

## Example Input/Output

**Input Example:**

Company: Canvassly
Product: AI-powered customer research and interview analysis platform for B2B product teams
PLG motion: Freemium (feature-limited)
Pricing model: Per seat
Free plan: 2 seats, 5 active projects, 10 interview transcripts/month, no team sharing, no custom tags
Paid plans: Pro ($29/seat/month, unlimited projects and transcripts, team sharing, AI tagging); Team ($49/seat/month, SSO, Salesforce integration, admin controls)
Current free user base: 3,800 active accounts
Monthly new free signups: 420 accounts
Current free-to-paid conversion rate: 3.1%
Average time-to-upgrade: 28 days
Top upgrade driver: "Teams hit the 2-seat limit when they try to add a second researcher"
Product analytics: Amplitude
CRM: HubSpot

**Output Example (excerpt):**

**REVENUE GAP ANALYSIS — CANVASSLY**

Current conversion rate: 3.1%
Industry benchmark (Freemium): 4.5% (midpoint)
Revenue gap: (4.5% − 3.1%) × 3,800 accounts × $4,200 ACV (estimated) = **$223,440 annual revenue opportunity at benchmark**

Top quartile conversion benchmark (Freemium): 6.5%
Top quartile revenue opportunity: (6.5% − 3.1%) × 3,800 × $4,200 = **$542,640 annual revenue opportunity at top quartile**

---

**UPGRADE TRIGGER HEATMAP — TOP 5 EVENTS**

| Event | Correlation | Lag to Upgrade | Coverage | Precision | Tier |
|-------|-------------|---------------|----------|-----------|------|
| Invites 2nd seat (hits free limit) | 0.87 | 4.2 days | 34% | 61% | Tier 1 — Golden |
| Views pricing page 2+ times | 0.79 | 3.1 days | 29% | 58% | Tier 1 — Golden |
| Completes 8+ interview analyses | 0.71 | 12.4 days | 41% | 44% | Tier 1 |
| Creates custom tag for first time | 0.63 | 18.7 days | 22% | 39% | Tier 2 |
| Exports insights to Notion/Confluence | 0.59 | 9.8 days | 18% | 37% | Tier 2 |

**Monetization Tipping Point:** Users who have [invited a second seat (triggering the seat limit)] AND [viewed the pricing page 2+ times] AND [have been active for 10+ days] convert at **74% within 14 days** — this is the primary PQL trigger combination.

---

**GOLDEN GATE ANALYSIS: 2-SEAT LIMIT**

- Monthly gate-hit rate: 34% of active free accounts hit the seat limit each month (1,292 accounts)
- 7-day conversion rate post-gate-hit: 18.4%
- 30-day conversion rate post-gate-hit: 26.1%
- Revenue generated per 100 gate-hit accounts: 26.1 × $4,200 = **$10,962 per 100 accounts**
- Current gate-hit sequence: Generic upgrade modal → no follow-up
- Optimized sequence:
  * T+0: In-app modal — "Your team is ready to collaborate. Add [invitee name] to Canvassly Pro." (personalized with the specific person they tried to invite)
  * T+24h email: "Don't leave [invitee name] out. Your team is waiting." + 14-day Pro trial for their additional seat
  * T+72h (if PQL ≥50): HubSpot task created for SDR — "Account hit seat limit, 74% probability of converting within 14 days if called now"
  - Projected lift: +8 percentage points on gate-hit conversion = +$9,200 ARR from this gate alone

---

**PQL SCORE BREAKDOWN — SAMPLE ACCOUNT (Lumen Labs)**

Account: Lumen Labs (47 employees, SaaS, Growth stage)
- Activation Depth Score: 20/25 (uses 4 of 5 core features)
- Recency Score: 20/20 (active 11 of last 14 days)
- Limit Proximity Score: 25/25 (at 100% of seat limit, 95% of transcript limit)
- Expansion Signal Score: 15/15 (invited 2nd seat attempt, active in team channel)
- High-Intent Exploration Score: 15/15 (visited pricing page 4 times, clicked "Compare Plans" 2x)
- **TOTAL PQL SCORE: 95/100 → Imminent Conversion Tier**
- Recommended action: SDR call today + personalized upgrade offer from AE ("I noticed your team is at capacity — here's how Canvassly Pro pays for itself in 60 days")

## Success Metrics

- **Free-to-paid conversion rate improvement**: Monthly cohort conversion rate moving toward PLG benchmark for your motion type (target: 30%+ improvement from baseline within 90 days)
- **Revenue per 100 free signups**: Most important monetization efficiency metric — measures total yield from your free user acquisition machine
- **Time-to-upgrade reduction**: Faster conversions = better cash flow + lower risk of churn-before-conversion; target median time-to-upgrade decrease of 20%+
- **PQL model precision**: % of PQL Score 70+ accounts that actually convert within 30 days (target: 40%+ precision)
- **Gate-hit conversion rate lift**: Improvement in % of users converting within 7 days of hitting a paywall
- **Pricing page funnel improvement**: Pricing page → payment complete conversion rate improvement (target: +3–5 percentage points)
- **Long-tail monetization capture**: # of accounts from the 90-day+ dormant segment successfully converted

## Related Prompts

- [PLG Onboarding Funnel Analytics & Activation Rate Optimization](./AI-Powered-B2B-SaaS-PLG-Onboarding-Funnel-Analytics-&-Activation-Rate-Optimization-Intelligence-Engine.md)
- [PLG Cohort Revenue Retention & Activation Intelligence Engine](./AI-Powered-B2B-SaaS-PLG-Cohort-Revenue-Retention-&-Activation-Intelligence-Engine.md)
- [PLG Product Qualified Lead PQL Pipeline Architecture & Free-to-Paid Revenue Conversion](../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/AI-Powered-B2B-SaaS-Product-Led-Growth-PQL-Pipeline-Architecture-&-Free-to-Paid-Revenue-Conversion-Intelligence-Engine.md)
- [Free Trial Activation Funnel CRO & Time-to-Value Conversion Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Free-Trial-Activation-Funnel-CRO-&-Time-to-Value-Conversion-Intelligence-Engine.md)

## Integration Tips

- **Amplitude/Mixpanel**: Build the PQL scoring model as a computed property or user-level score in your analytics tool — use Amplitude's "Personas" feature or Mixpanel's "User Properties" to auto-assign PQL tier scores based on behavioral events; sync PQL scores to HubSpot/Salesforce via Segment or a direct integration
- **HubSpot/Salesforce**: Create a "PQL Score" custom field on the Company object in your CRM; set up automated workflows that enroll accounts into upgrade sequences when PQL Score crosses thresholds (30, 50, 70, 90); create SDR task queues that surface PQL 70+ accounts that have been free for 14+ days
- **Intercom/Appcues**: Use the gate-hit personalization sequences from Module 3 as Intercom Series or Appcues Flows; trigger them based on product events sent via Segment; personalize with user-level data (invitee name, usage count, company name)
- **Customer.io/Braze**: Deploy the time-based intervention sequences from Module 5 as customer journeys; use event-triggered entry points (gate hit, pricing page visit, PQL score threshold) rather than time-delay-only triggers for higher relevance
- **Stripe/Chargebee**: Analyze checkout abandonment data from your payment processor to identify the specific checkout step with highest drop-off; use Stripe Checkout's built-in analytics or Chargebee's conversion reports as input for Module 4's upgrade flow analysis
- **Notion/Confluence**: Export the 90-day roadmap and PQL scoring model documentation into your team wiki; share the paywall performance matrix with the CPO and pricing team as a standing agenda item in your monthly pricing review

## Troubleshooting

**Problem: I don't have product analytics instrumented well enough to identify upgrade trigger events.**
Solution: Start with the Quick Copy-Paste version using your best estimates — the PQL scoring model will still produce a directionally correct framework you can begin using immediately. Use the instrumentation plan in Module 7 (Month 1, Week 1) to close tracking gaps. Even with imperfect data, you can identify your Golden Gate by looking at what gated feature generates the most upgrade-related support tickets or sales inquiry mentions, then build the sequence around that gate while you improve instrumentation in parallel.

**Problem: My free-to-paid conversion rate is already above benchmark — how should I use this prompt?**
Solution: Shift your focus from baseline conversion improvement to ACV expansion and conversion quality optimization. Modify the Quick Copy-Paste prompt to add: "My conversion rate already exceeds [X]% benchmark. Focus the analysis on: (1) increasing ACV of converting users by improving plan selection (more users on Team/Enterprise vs. Pro), (2) reducing time-to-upgrade from [X days] to [Y days], and (3) improving 90-day retention of PLG-converted customers." The upgrade trigger and PQL scoring sections are particularly valuable for identifying which free users convert to higher-ACV plans.

**Problem: The prompt output recommends SDR outreach, but we're a pure self-serve motion with no sales team.**
Solution: Replace all SDR outreach recommendations with automated in-app and email escalations. Add to your prompt: "We are 100% self-serve with no sales team. Replace all SDR outreach recommendations with automated alternatives: for high-PQL accounts, use: (1) personalized in-app upgrade offers with dynamic content based on usage data, (2) direct Calendly booking link for a 'product expert chat' handled by customer success, or (3) time-limited discount offers triggered automatically at PQL Score 70+."

## Version History
- v1.0: Initial creation (auto-generated)
