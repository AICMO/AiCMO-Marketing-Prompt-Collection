# AI-Powered B2B SaaS Product-Led Growth (PLG) Analytics Architecture & Trial-to-Paid Revenue Intelligence Engine - Build an AI-Agent-Managed System That Measures, Predicts, and Optimizes Your Entire PLG Funnel From First Trial Sign-Up to Expansion Revenue

**Difficulty:** Advanced | **Time:** 45-60 min | **Tags:** product-led growth, PLG analytics, trial-to-paid conversion, activation analytics, revenue intelligence, B2B SaaS, funnel analytics, free trial, freemium, self-serve, time-to-value, cohort analysis, Amplitude, Mixpanel, HubSpot, Salesforce, AI agents, product analytics, growth engineering

## Overview
Designs and deploys a complete AI-agent-managed PLG analytics architecture that continuously monitors every trial user through activation, conversion, and expansion — identifying which marketing channels deliver the highest-quality trial users, which in-product behaviors predict paid conversion within 72 hours of a trial sign-up, which trial cohorts are at risk of churning without a sales assist, and which expansion triggers in your existing paid base represent the highest-value upsell opportunities. Use this when you are running a self-serve trial or freemium motion and need to prove which marketing investments produce revenue-grade trial users (not just trial sign-up volume), when you cannot explain why trial conversion rate varies so dramatically across acquisition channels, when your PLG and sales motions are operating as separate functions without shared data, or when you need to allocate marketing budget between PLG acquisition and sales-assisted pipeline but lack the analytics to justify either investment. This system makes marketing directly accountable for the quality and conversion of every trial user, not just the cost of acquiring them.

## Quick Copy-Paste Version

You are a B2B SaaS PLG analytics architect specializing in trial-to-paid conversion intelligence. Build a complete, AI-agent-executable PLG analytics system that identifies which marketing channels, campaigns, and acquisition strategies deliver the highest-converting trial users — and continuously optimizes marketing spend toward revenue-grade trial acquisition.

COMPANY CONTEXT:
- My Company: [e.g., "Loom — async video messaging platform that helps teams at 10-10,000 employee companies replace unnecessary meetings with short video messages for faster team communication"]
- PLG Motion: [e.g., "Freemium — unlimited free tier with 5-minute video cap and 25-video limit; paid plans unlock unlimited duration, AI summaries, custom branding, and team analytics"]
- Trial/Free Tier Structure: [e.g., "Free plan users have access for unlimited time; upgrade prompts trigger when user hits video cap, tries to create a workspace with 5+ members, or accesses analytics features"]
- Current Trial Volume: [e.g., "12,000 new free sign-ups per month; 850 convert to paid within 30 days = 7.1% conversion rate"]
- Average Paid Plan ACV: [e.g., "$144/year individual, $480/year team (5 seats), $2,400/year business (25 seats)"]
- Product Analytics Tool: [Amplitude / Mixpanel / Heap / PostHog / GA4]
- CRM: [HubSpot / Salesforce]
- Current Marketing Channels: [e.g., "SEO (40% of signups), paid search (25%), product virality/referral (20%), social/content (15%)"]

OUTPUT REQUIRED:
1. PLG FUNNEL INSTRUMENTATION MAP: The exact product events to track from first sign-up through every activation milestone, conversion trigger, and expansion signal — including how to connect product analytics data to marketing campaign data for closed-loop attribution
2. ACTIVATION INTELLIGENCE FRAMEWORK: How to identify the "aha moment" for your specific product — the in-product behavior that correlates most strongly with trial-to-paid conversion — and the exact metrics to track and benchmark
3. CHANNEL QUALITY SCORING: A channel-level quality framework that scores each marketing acquisition channel not on cost-per-signup but on 30-day and 90-day trial-to-paid conversion rate, time-to-activation, and revenue contribution per channel dollar
4. PREDICTIVE CONVERSION MODEL: The behavioral signals in the first 72 hours of a trial that predict whether a user will convert to paid within 30 days — and how marketing should respond differently to high-probability vs. low-probability converters
5. SALES-ASSIST TRIGGER ARCHITECTURE: How to identify which trial users should be handed off to sales (PQL scoring) vs. left to self-convert — and the exact product usage signals that trigger each routing decision
6. AUTONOMOUS OPTIMIZATION LOOP: The AI-agent workflows that continuously monitor trial cohort performance, detect conversion rate shifts by acquisition channel, and surface budget reallocation recommendations without requiring a weekly analyst to pull reports

Design this system to operate without manual data pulls: channel quality scoring, conversion rate monitoring, PQL detection, and budget intelligence should all execute autonomously and surface insights to the marketing team on a weekly cadence.

## Advanced Customizable Version

ROLE: You are a senior PLG analytics architect with 15+ years designing product-led growth measurement systems for B2B SaaS companies from early-stage through IPO. You have built PLG analytics infrastructure for 60+ B2B SaaS companies across DevTools, collaboration software, HR tech, fintech, and vertical SaaS — spanning freemium models with 500K+ monthly sign-ups and velocity sales models where 99% of revenue converts self-serve, to product-qualified lead programs where 40% of ARR comes from sales-assisted expansion of PLG-originated accounts. You understand the precise mechanics that determine PLG measurement success or failure: why "trial conversion rate" as a single number is analytically meaningless unless segmented by acquisition channel, ICP fit, company size, and job title — because a 4% conversion rate from SEO traffic and a 4% conversion rate from Product Hunt launches look identical in aggregate but represent completely different business health and optimization opportunities; why time-to-activation is a more powerful leading indicator of conversion than any demographic variable, and why companies that reduce median time-to-activation from 7 days to 2 days typically see 25-40% improvement in 30-day trial conversion even without any other changes; why the "aha moment" is a behavioral threshold, not a feature visit — it is the specific combination of actions (e.g., "user created 3 videos AND shared at least 1 externally AND received at least 1 view") that correlates with 10× higher retention and conversion compared to users who did not reach that threshold; why PQL scoring without product signal weighting is broken — a user who sends your product's output to 10 colleagues in their first session is a fundamentally different buying signal than a user who logged in once and spent 6 minutes before abandoning; why viral coefficient and referral loop analytics are the most underinstrumented components of most PLG funnels — if 1 in 5 of your free users invites a colleague, and 1 in 8 of those colleagues invites another, your marketing team is generating substantial pipeline through a channel that most marketing attribution models assign zero credit; and why the biggest analytics failure in PLG is treating free users as a homogeneous group when their conversion probability varies by 20:1 depending on ICP match, activation speed, and in-product behavior pattern.

You design PLG analytics systems to operate as fully autonomous AI agent workflows: product event data streams into a unified analytics layer continuously, cohort conversion rates are calculated and compared against rolling benchmarks without manual intervention, channel quality scores update weekly without analyst involvement, PQL alerts route to the appropriate sales or marketing automation system within minutes of threshold crossing, and the CMO receives a weekly PLG Revenue Intelligence Brief that synthesizes conversion trends, channel quality shifts, and optimization recommendations — all without a human running a single SQL query.

OBJECTIVE: Design a production-ready, AI-agent-managed PLG analytics system that:
- Instruments the complete PLG funnel from first marketing touchpoint through free sign-up, activation, conversion, and expansion — connecting marketing channel data to product behavioral data to revenue outcomes in a single closed-loop model
- Identifies the specific in-product activation behaviors that correlate most strongly with 30-day and 90-day paid conversion for your specific product and ICP — not generic "activation frameworks" but the empirically derived behavioral thresholds for your actual users
- Scores every marketing acquisition channel on revenue quality (conversion rate × average plan at conversion × time-to-activation) rather than acquisition volume alone — so budget allocation reflects the actual revenue contribution of each channel, not just the cheapest clicks
- Detects trial-to-paid conversion rate shifts by acquisition channel, company size, job title, and activation speed within 48 hours of a statistically significant deviation — enabling marketing to respond to conversion degradation before it becomes a quarterly revenue miss
- Routes trial users to the right next action (self-serve nurture vs. sales development rep outreach vs. product-led expansion sequence) based on real-time behavioral scoring — eliminating the manual review process that causes high-PQL accounts to go uncontacted for 3-7 days
- Produces a weekly PLG Revenue Intelligence Brief that CMOs and growth teams can use to make budget allocation, channel mix, and product onboarding investment decisions without relying on a data analyst to pull custom reports

---

COMPANY & PROGRAM INPUTS:

Your PLG Architecture Profile:
- Company name and product: [name + outcome-focused description, e.g., "Loom — async video messaging platform that eliminates status update meetings for distributed and hybrid teams"]
- PLG model: [Freemium (permanent free tier) / Free trial (time-limited, e.g., 14-day) / Reverse trial (full product free for X days, then downgraded) / Usage-based freemium (free up to X actions/units)]
- Conversion motion: [Self-serve only / Self-serve primary with sales assist for accounts above X employee count or X ACV / Product-qualified lead (PQL) program routing high-intent trial users to SDR outreach]
- Paid plan structure: [Individual / Team / Business / Enterprise tiers with brief description of what unlocks at each tier]
- Current monthly free sign-up volume: [total, plus breakdown by channel if available]
- Current 30-day trial-to-paid conversion rate: [your baseline, ideally segmented by acquisition channel if available]
- Average plan at first conversion: [individual/team/business split — this determines revenue per converted trial]
- Net revenue retention from PLG-originated accounts: [12-month NRR — this determines the LTV of your PLG cohorts vs. sales-sourced cohorts]

Product Analytics Infrastructure:
- Current product analytics tool: [Amplitude / Mixpanel / Heap / PostHog / GA4 / Segment / Custom]
- Current events being tracked: [what product actions are currently instrumented — be honest about gaps]
- Marketing attribution method: [UTM parameters / first-touch only / multi-touch / none]
- CRM integration status: [does free user data flow into CRM? At what point — signup, activation, PQL threshold, or not at all?]
- Current reporting process: [how are PLG conversion metrics currently reported — weekly analyst pull, automated dashboard, ad hoc requests, not tracked systematically]

Activation and Conversion Intelligence:
- Your current definition of "activated user": [what in-product action or milestone constitutes activation — be specific about the exact event or event sequence]
- Your current definition of "PQL" or "ready for sales": [what criteria trigger sales outreach to a free user — job title, company size, usage threshold, specific feature access, or combination]
- Known conversion rate differences by segment: [if you know that enterprise accounts convert at 2× the rate of SMB accounts, or that users who invite colleagues convert at 5× the rate of solo users, capture these here]
- Your hypothesis about the "aha moment": [what you believe is the key product action that makes a user understand the value — this is a hypothesis to test, not a confirmed fact]
- Biggest conversion leak you've observed: [where do you believe most trial users drop off — day 1 abandonment, feature discovery failure, team invite friction, pricing page bounce, or somewhere else]

Marketing Channel Profile:
- Acquisition channels with volume estimate: [e.g., SEO 40%, paid search 20%, product virality/referral 15%, paid social 10%, content syndication 8%, partnerships 7%]
- Current marketing attribution capability: [can you trace a paid conversion back to the specific campaign, keyword, or piece of content that generated the original free sign-up? Or is your attribution limited to channel-level only?]
- Biggest channel budget: [which channel receives the most marketing investment — this may not be your highest-converting channel, which is the core problem this system solves]
- Known channel quality differences: [any existing data showing that certain channels produce higher-quality trial users — e.g., "we know branded search converts at 2× the rate of unbranded, but we don't systematically optimize for this"]

Competitive and Market Context:
- Top 3 competitive PLG products: [competitors with similar PLG models who are winning trial users you're not converting]
- Your strongest product differentiator at the trial stage: [what feature or experience makes your free product obviously better than the free tier of your top competitor — this is your "first use case win" moment]
- Biggest trial abandonment reason (hypothesis): [why you believe most trial users don't convert — price, feature gaps, onboarding friction, lack of team adoption, competitor switching cost]

---

DELIVERABLES — COMPLETE ALL SECTIONS:

**1. PLG FUNNEL INSTRUMENTATION MAP**

Design the complete event tracking architecture for your PLG funnel. Every event listed below should be tracked with the exact event name, required properties, and where it fires:

Acquisition Events (marketing touchpoint tracking):
- `marketing_source_captured` — fires at first landing page or app visit; properties: utm_source, utm_medium, utm_campaign, utm_content, utm_term, referrer_domain, landing_page_url, session_id
- `signup_initiated` — fires when user clicks "Sign Up" or "Start Free Trial"; properties: page_location (pricing page, landing page, homepage, blog post), cta_text, session_id
- `signup_completed` — fires on successful account creation; properties: all utm properties, acquisition_channel (derived classification), company_domain (parsed from email), signup_method (email, Google SSO, GitHub SSO), is_company_email (boolean), job_title (if collected at signup), company_size (if collected), session_id

Activation Events (in-product value realization tracking):
- `first_core_action` — fires when user completes the single most fundamental action in your product (for Loom: first video recorded; for Slack: first message sent; for Figma: first frame created); properties: time_since_signup_minutes, session_number (was this their first session?), acquisition_channel
- `activation_milestone_1` — the first behavioral threshold correlated with retention (defined specifically for your product); properties: time_since_signup_hours, session_count_to_reach_milestone, acquisition_channel
- `activation_milestone_2` — the second behavioral threshold (viral/collaborative action — e.g., shared content with someone outside their account, invited a team member, created content consumed by an external user); properties: days_since_signup, team_members_invited, shares_sent
- `aha_moment_reached` — fires when user crosses your empirically derived activation threshold (the specific combination of events that 10× conversion probability); properties: all activation milestone properties, days_since_signup, acquisition_channel

Conversion Events:
- `upgrade_intent_signal` — fires when user hits a paywall, views the pricing page, or clicks an upgrade CTA; properties: paywall_type (feature gate, usage limit, team size limit), upgrade_cta_location, acquisition_channel, activation_status (activated/not activated), days_since_signup
- `pricing_page_viewed` — fires on pricing page visit; properties: plan_highlighted (which tier the user spent the most time viewing), time_on_pricing_page_seconds, visit_number (1st/2nd/3rd+ pricing page visit)
- `trial_converted` — fires on successful payment; properties: plan_selected, plan_frequency (monthly/annual), seats_purchased, acquisition_channel, days_from_signup_to_conversion, activation_status, paywall_that_triggered (what feature gate or limit drove the conversion), mrr_value

Expansion Events (for paid users):
- `seat_added` — fires when a paid account adds a seat; properties: current_seat_count, seats_added, plan_tier, mrr_increase
- `plan_upgraded` — fires on plan tier upgrade; properties: previous_plan, new_plan, mrr_delta, trigger_event (usage limit, feature request, admin prompt), time_since_first_conversion_days
- `expansion_signal_detected` — fires when a paid account shows behavioral signals that predict plan upgrade (usage approaching current plan limits, inviting users that would exceed seat count, accessing enterprise features); properties: signal_type, current_plan, predicted_next_plan, expansion_probability_score

---

**2. ACTIVATION INTELLIGENCE FRAMEWORK**

Design the empirical approach to discovering and validating your "aha moment":

**Step 1 — Activation Correlation Analysis:**

Pull all users who signed up in the last 90 days. For each user, record:
- Whether they converted to paid within 30 days (binary: converted/not converted)
- Which product events they completed within their first 7 days, and when
- Time from signup to first core action
- Time from signup to first collaborative/sharing action (if applicable)
- Total sessions in first 7 days
- Days between first session and second session (second-session return rate is a high-signal conversion predictor)

Run correlation analysis: which in-product actions in the first 7 days correlate most strongly with 30-day paid conversion? Rank all events by their correlation coefficient with 30-day conversion. Your "aha moment" hypothesis is the single event or event combination at the top of this ranked list.

**Step 2 — Activation Threshold Calibration:**

For your top 3 correlated events, test thresholds:
- Event X completed 1 time: conversion rate = A%
- Event X completed 2 times: conversion rate = B%
- Event X completed 3+ times: conversion rate = C%

The threshold where conversion rate inflects sharply (e.g., where going from 2→3 completions doubles conversion rate) is your activation threshold. This is your "aha moment" definition: not "user completed event X" but "user completed event X at least N times."

**Step 3 — Multi-Event Activation Model:**

Most B2B SaaS products have a compound aha moment: a sequence of 2-3 events that together predict conversion more reliably than any single event alone. Test combinations:
- Activation Milestone 1 only: conversion rate = A%
- Activation Milestone 1 + Milestone 2: conversion rate = B%
- Milestone 1 + Milestone 2 + viral action: conversion rate = C%

The combination that produces the highest conversion rate with a sufficiently large sample size (aim for N ≥ 200 users per cohort) becomes your official activation definition.

**Step 4 — Activation Benchmarks by Acquisition Channel:**

Segment your activation analysis by acquisition channel:
- What % of organic search users reach your aha moment within 7 days?
- What % of paid search users reach your aha moment within 7 days?
- What % of product referral/viral users reach your aha moment within 7 days?
- What % of direct/branded users reach your aha moment within 7 days?

These activation-by-channel rates, combined with conversion-by-channel rates, form the foundation of your Channel Quality Score.

**Activation KPIs to track weekly:**
- Activation Rate (% of new sign-ups who reach aha moment within 7 days) — segment by acquisition channel, company size, job title
- Time-to-Activation (median days from signup to aha moment) — this is your primary leading indicator of conversion; a drop in median time-to-activation predicts a conversion rate improvement 2-4 weeks later
- Activation-to-Conversion Rate (% of activated users who convert within 30 days) — if this drops, the problem is in the conversion path (pricing, paywall, feature gating), not activation
- Not-Activated Churn Rate (% of non-activated users who are fully inactive 14 days after signup) — high rates here signal onboarding friction that marketing spend cannot overcome

---

**3. CHANNEL QUALITY SCORING SYSTEM**

Build the Revenue Quality Score for every marketing acquisition channel:

**Channel Quality Score Formula:**
Revenue Quality Score = (30-Day Conversion Rate × Average MRR at Conversion × Activation Rate Within 7 Days) / Cost Per Free Signup

This score normalizes every channel on the same metric: how much monthly recurring revenue does each dollar of acquisition spend produce? Channels with a low cost-per-signup but low conversion rate and low activation rate will score lower than channels with a higher cost-per-signup but significantly higher conversion and activation.

**Channel Quality Score Calculation — Step by Step:**

For each acquisition channel, calculate monthly:
1. Free signups: [volume]
2. Activation rate (% who reach aha moment within 7 days): [rate]
3. 30-day conversion rate for activated users: [rate]
4. 30-day conversion rate for non-activated users: [rate — this is the floor conversion rate for this channel]
5. Average MRR at conversion: [dollars — this varies because enterprise users convert at higher ACV than individual users, and some channels attract more enterprise ICP]
6. Blended 30-day conversion rate (activated + non-activated): [rate]
7. MRR generated per 100 signups: [(activated users × activation conversion rate × avg MRR at conversion) + (non-activated users × floor conversion rate × avg MRR at conversion)]
8. Cost per free signup: [channel spend / free signups]
9. Revenue Quality Score: [MRR generated per 100 signups / cost per free signup × 100]

**Channel Quality Benchmark Example (Illustrative — Replace With Your Actuals):**

| Channel | Cost/Signup | Activation Rate | 30-Day Conv Rate | Avg MRR at Conv | Revenue Quality Score |
|---------|-------------|-----------------|------------------|-----------------|----------------------|
| Branded Search | $8.20 | 52% | 18.3% | $62 | 142 |
| Product Referral | $1.40 | 61% | 22.1% | $58 | 918 |
| Unbranded Search (bottom funnel) | $12.80 | 44% | 14.7% | $71 | 65 |
| LinkedIn Ads | $31.60 | 38% | 11.2% | $94 | 33 |
| Content/SEO (top funnel) | $3.10 | 29% | 7.8% | $44 | 44 |
| G2 / Review Site | $18.30 | 58% | 19.6% | $88 | 93 |

In this illustrative example, Product Referral has a Revenue Quality Score 28× higher than LinkedIn Ads — not because LinkedIn is a bad channel, but because the trial users it delivers activate and convert at much lower rates than referral users. The implication is clear: marketing should invest in programs that increase viral referral loops before scaling LinkedIn Ads spend.

**Quarterly Channel Mix Reallocation Protocol:**
- Any channel with Revenue Quality Score below 50 receives a 20% budget reduction and a 90-day improvement experiment (new landing page, improved onboarding flow for channel-specific users, A/B test on first-session email sequence)
- Any channel with Revenue Quality Score above 150 receives a budget increase test: +25% spend for 60 days, measure whether Revenue Quality Score holds or degrades at scale
- Product referral always receives investment in the virality mechanisms (share prompts, invite flows, referral rewards) regardless of current score — because viral coefficient improvement is the highest-leverage PLG growth investment

---

**4. PREDICTIVE CONVERSION MODEL**

Build the behavioral scoring model that predicts 30-day trial-to-paid conversion within the first 72 hours of a trial sign-up:

**Behavioral Signal Weight Matrix (Train on 90 days of conversion data):**

For each signal observed within the first 72 hours of a user's trial, assign a weight based on its correlation with 30-day conversion:

Tier 1 Signals (Strongest Predictors — +15 to +25 points each):
- Reached aha moment within 48 hours: +25 points
- Invited at least 1 team member: +20 points
- Shared product output with external user (non-team-member): +18 points
- Returned for a second session within 24 hours of first: +17 points
- Accessed pricing page: +15 points

Tier 2 Signals (Moderate Predictors — +8 to +14 points each):
- Company domain matches known ICP industry (based on enrichment): +12 points
- Job title matches primary buyer persona: +10 points
- Completed core action ≥ 3 times within 72 hours: +10 points
- Used a feature that requires upgrade to continue: +9 points (upgrade consideration signal)
- Sign-up method was work email (not Gmail/Yahoo): +8 points

Tier 3 Signals (Mild Positive Predictors — +3 to +7 points each):
- Company size 50-2,000 employees (per enrichment): +6 points
- Came from a high-quality acquisition channel (Channel Quality Score > 100): +5 points
- Second session return within 48 hours: +4 points
- Completed onboarding checklist ≥ 50%: +3 points

Negative Signals (Reduce Conversion Probability):
- No second session within 72 hours: -10 points
- Signed up with personal email (Gmail/Yahoo/Hotmail): -8 points
- Company size < 10 employees: -6 points
- Only one core action completed in 3 sessions: -5 points
- Accessed pricing page and immediately bounced (< 20 seconds): -12 points (this is a strong negative signal — they saw the price and left immediately)

**Conversion Probability Tiers:**
- Score ≥ 60: High Conversion Probability (HCP) — predicted 30-day conversion rate 3-5× baseline; route to sales for enterprise accounts; for SMB, route to high-touch email sequence
- Score 30-59: Medium Conversion Probability (MCP) — predicted conversion rate at or above baseline; route to standard product-led nurture sequence; monitor for score changes
- Score < 30: Low Conversion Probability (LCP) — predicted conversion rate below baseline; route to lightweight nurture; deprioritize for sales investment; analyze for acquisition channel quality improvement
- Score ≤ 10 with no second session by day 3: Churn Risk — flag for winback sequence; if account qualifies for outreach, assign to sales for a "rescue" call

**What Marketing Does Differently for Each Tier:**

HCP Accounts (Score ≥ 60):
- If company size > 50 employees: assign to SDR/AE within 4 hours; provide SDR with full behavioral context from product analytics
- If company size < 50 employees: enroll in high-touch email sequence with specific upgrade value props tied to the features they've already used
- Run LinkedIn retargeting specifically showing the team/business plan features the user has been gravitating toward
- Trigger executive-to-executive outreach for accounts above $10K ACV potential

MCP Accounts (Score 30-59):
- Standard product-led nurture email sequence (7-touch over 21 days)
- Feature discovery emails surfacing specific features they haven't yet used but that correlate with conversion
- Social proof emails featuring customers of similar profile (company size, industry, job title)
- Day 7 email offering a live product tour or implementation session if they haven't reached activation milestone

LCP Accounts (Score < 30):
- Lightweight nurture sequence (3-touch over 14 days)
- Day 14: survey email asking why they haven't fully explored the product (this data improves the conversion model and surfaces onboarding friction)
- Day 21: winback offer if account goes fully inactive (special pricing, extended trial, or onboarding help)
- No SDR resources invested unless account is a named target account in your ABM program

---

**5. PRODUCT-QUALIFIED LEAD (PQL) ROUTING ARCHITECTURE**

Design the automated system that routes trial users to the right next action without human review:

**PQL Definition — Three Tiers:**

PQL Tier 1 — Sales-Ready (Route to SDR within 2 hours):
Criteria: Behavioral Score ≥ 60 AND company size ≥ 50 employees AND company email domain (not personal email) AND at least 2 of the following: (a) invited team member, (b) hit feature gate/paywall, (c) shared product output externally, (d) visited pricing page ≥ 2 times
Routing: Immediate SDR assignment via CRM alert with full behavioral context package (what features they used, how many times, what they shared, what paywall they hit, their Channel Quality Score)
Response time target: SDR first outreach within 2 hours of PQL threshold crossing

PQL Tier 2 — Sales-Assist Candidate (Route to SDR within 24 hours):
Criteria: Behavioral Score 40-59 AND company size ≥ 100 employees AND work email
Routing: SDR assignment with 24-hour response SLA; lower priority than Tier 1
SDR approach: Value-add outreach ("I saw you've been exploring [specific feature they used] — here's how a company in your space used it to [specific outcome]")

PQL Tier 3 — Marketing-Qualified for Expansion (No SDR, high-touch marketing):
Criteria: Behavioral Score ≥ 60 AND company size < 50 employees, OR Score 30-59 AND company size ≥ 50 employees
Routing: High-touch marketing automation (personalized email sequences, retargeting, feature adoption nudges); SDR only if account becomes inactive for 7+ days after reaching Tier 3

**PQL Routing Automation Architecture:**

Trigger: Behavioral Score threshold crossed (Tier 1: score ≥ 60; Tier 2: score ≥ 40 with size filter)
System: Product analytics platform detects score threshold crossing → fires webhook to CRM → CRM creates/updates contact record with PQL tier and full behavioral context → CRM workflow assigns to SDR queue or marketing automation sequence based on tier → SDR notified via Slack with behavioral brief

Behavioral Context Package delivered to SDR at PQL assignment:
PQL Alert — [Company Name]
Contact: [Name, Title, Email]
Company: [Domain, Size, Industry]
Signed Up: [X] days ago via [Channel]
Behavioral Score: [X] (Tier [1/2])

What they've done:
- Created [X] [core product actions] in [X] sessions
- Invited [X] team members
- Hit [paywall type] paywall [X] times
- Viewed pricing page [X] times
- Shared [output type] with [X] external contacts

Recommended first message: "[Personalized opener referencing their specific product usage, then a specific outcome from a similar company]"

Similar customers who converted: [2-3 comparable customer references by company size/industry]

---

**6. AI AGENT AUTOMATION ARCHITECTURE**

Define the autonomous AI agent workflows that run PLG analytics without manual intervention:

**PLG Monitoring Agent (Daily):**
- Input: All new free sign-ups from prior 24 hours + all active trial users
- Analysis: Calculate behavioral score for all new users at 24h, 48h, and 72h; identify all users who crossed PQL thresholds; calculate daily activation rate by acquisition channel; detect any channel with activation rate ≥ 15% below 30-day rolling average (anomaly detection)
- Output: PQL alerts routed to CRM for all threshold crossings; anomaly alerts to Marketing Operations for any channel showing significant activation rate drop; daily PLG summary dashboard update
- Escalation: If any acquisition channel shows >20% activation rate drop in 48 hours, alert VP Marketing and VP Product with channel name, magnitude, and date range

**Cohort Conversion Agent (Weekly):**
- Input: All trial user cohorts from the prior 4 weeks (weekly cohorts)
- Analysis: Calculate 7-day, 14-day, 21-day, and 30-day conversion rates for each weekly cohort; compare to prior 4-week average baseline; calculate Channel Quality Score for all active acquisition channels; identify channels where conversion rate or activation rate has shifted ≥ 10% in either direction
- Output: Weekly PLG Revenue Intelligence Brief (see below); updated Channel Quality Scores; budget reallocation recommendation (any channel with score change > 15% in either direction triggers a recommendation)
- Escalation: If overall 30-day trial conversion rate drops >15% below 90-day baseline, trigger immediate investigation protocol: segment by channel, ICP, and activation status to identify root cause

**Activation Optimization Agent (Weekly):**
- Input: All users who signed up 7-14 days ago and have NOT reached activation milestone
- Analysis: Segment non-activated users by acquisition channel, job title, company size, and last-seen date; identify which email sequences produced highest activation lift (A/B test analysis); identify which in-product prompts (tooltip, checklist item, feature discovery email) moved non-activated users to activation within the analysis window
- Output: Non-activated user segment report; top 3 activation intervention recommendations for the following week's onboarding email experiments
- Action: Auto-enroll all Day-7 non-activated users in the highest-performing activation recovery sequence

**Expansion Signal Agent (Daily for Paid Accounts):**
- Input: All paid accounts' usage data
- Analysis: Detect any paid account approaching usage limits (>80% of plan limit), seat count approaching plan ceiling (>80% of seats filled), or accessing features locked at higher tiers more than 3 times in 7 days
- Output: Expansion signal alert to SDR or CS assigned to account; predicted next plan and estimated MRR expansion; recommended expansion message personalized to specific usage pattern that triggered the signal

**Weekly PLG Revenue Intelligence Brief (Auto-Generated):**

PLG Revenue Intelligence Brief — Week of [Date]

HEADLINE METRICS:
- New free sign-ups: [X] ([+/-]% vs prior week)
- 30-day cohort conversion rate: [X]% ([+/-]% vs 90-day average)
- MRR from PLG conversions this week: $[X]
- Median time-to-activation: [X] days ([+/-] vs prior week — this is your primary leading indicator)
- PQLs generated: [X] ([X] Tier 1, [X] Tier 2)

CHANNEL QUALITY UPDATE:
- Revenue Quality Score changes this week:
  [Channel A]: [+/-X pts] — [interpretation: "Branded search activation rate improved 8 percentage points; investigate what changed in the onboarding experience for users from this channel"]
  [Channel B]: [-X pts] — [interpretation: "Unbranded SEO conversion rate declined; possible landing page or onboarding friction for this audience segment"]

ACTIVATION INTELLIGENCE:
- Top activation lever this week: [X% of non-activated users who received the feature discovery email for [Feature] activated within 48 hours, vs. 12% who received the standard check-in email — recommend expanding this email to all Day-4 non-activated users]
- Biggest activation gap: [Job title] converts to activation at half the rate of other segments — hypothesis: [specific onboarding friction or product UX issue]

EXPANSION SIGNALS:
- [X] paid accounts approaching plan limits — [X] have been contacted by SDR, [X] pending
- Largest expansion opportunity identified: [Company name] — currently on Team plan, 47 of 50 seats filled, usage of [enterprise feature] 3× per day — recommend SDR outreach for Business plan upgrade (estimated MRR expansion: $[X])

BUDGET RECOMMENDATION:
- [Channel with improving score]: Revenue Quality Score up [X]pts to [Y] — recommend +15% budget test for 60 days
- [Channel with declining score]: Revenue Quality Score down [X]pts to [Y] — recommend 20% budget reduction and landing page A/B test for users from this channel

---

## Example Input/Output

**Input Example:**

Company: Notion — all-in-one workspace for notes, wikis, docs, and projects
PLG Model: Freemium (free forever for personal use; paid plans unlock team features, advanced permissions, and admin controls)
Trial Volume: 45,000 new sign-ups per month
Current Conversion Rate: 6.2% (blended 30-day)
Known Channel Mix: SEO/organic 55%, direct/brand 18%, product referral 12%, paid search 8%, social/content 7%
Company Goal: Improve 30-day conversion rate to 9% within 2 quarters without increasing CAC

**Output Example (excerpt):**

**Channel Quality Analysis for Notion:**

The most important insight your data will reveal is that your 6.2% blended conversion rate almost certainly masks a 3:1 or 4:1 conversion rate difference between your highest and lowest quality acquisition channels. Based on Notion's public positioning and PLG archetype, here is the predictive Channel Quality Score framework:

Product Referral (estimated Revenue Quality Score: 780-950): Users who arrive because a colleague shared a Notion workspace with them arrive already understanding the product's value, have a social proof anchor, and have an immediate use case. They activate in hours, not days, and invite additional team members at 4× the rate of organic search users. This channel is almost certainly your highest-converting channel but receives zero paid marketing investment. Your primary budget recommendation: invest in viral loop optimization — the "Share this workspace" prompt timing, the referral email quality, and the friction reduction in the workspace invitation acceptance flow.

Branded Search (estimated Revenue Quality Score: 200-320): Users searching "Notion" by name are already aware of the product and intending to try it. Their activation rate should be 40-55% within 7 days, and their 30-day conversion rate likely 14-20%. This channel is high quality and investment here is justified — but it's bounded by total branded search volume, which grows with brand awareness, not with PPC budget.

Unbranded Organic SEO (estimated Revenue Quality Score: 35-65): Your SEO traffic is bringing in users searching for "free note-taking app," "project management template," and similar generic terms. These users convert at significantly lower rates (likely 3-5%) because they have low product specificity and high alternative consideration. Your activation rate for this cohort is probably 18-25% vs. 45%+ for referral users. However, the sheer volume of SEO sign-ups means even a modest improvement in activation rate for this segment produces significant absolute conversion gains. Recommendation: create segmented onboarding paths by traffic source — SEO visitors get a "start with a template" onboarding experience (concrete, immediate value) rather than a blank slate.

**Aha Moment Hypothesis for Notion:**

Based on Notion's product structure, your activation correlation analysis will likely reveal that the aha moment is a compound event: (1) user has created at least 1 page using a template (not a blank page), AND (2) user has made that page accessible to at least 1 other person (shared publicly, invited a collaborator, or made it a team page). Users who reach both milestones within their first 5 days likely convert at 4-6× the rate of users who only created content for personal use and never shared it. This compound activation criterion is your optimization target: your entire onboarding flow should be designed to get users to their first collaborative/shared page as fast as possible, because that's the moment where Notion transforms from "personal productivity tool" (competing with Apple Notes) to "team collaboration platform" (worth paying for as a team).

**Predicted Conversion Rate Impact:**

If Notion can improve activation rate from 28% (assumed baseline) to 40% within the first 7 days by redesigning the onboarding experience for SEO and paid search cohorts to push toward collaborative/shared pages:
- Additional activated users per month: ~5,400 (12 percentage point improvement × 45,000 sign-ups)
- Additional conversions assuming 14% activation-to-conversion rate: ~756 conversions
- Additional MRR assuming $20 average at conversion: ~$15,100/month
- Additional ARR: ~$181,000/year
- This improvement, if achieved, would raise overall conversion rate from 6.2% to approximately 7.9% without any increase in acquisition spend

---

## Success Metrics

**PLG Funnel Health:**
- 30-day blended trial-to-paid conversion rate improves ≥ 20% relative to baseline within 90 days of implementing full analytics instrumentation and channel quality optimization
- Median time-to-activation decreases ≥ 25% within 60 days of deploying activation-focused onboarding improvements (this is the leading indicator — improvement here predicts conversion improvement 2-4 weeks later)
- Activation rate for the two lowest-performing acquisition channels improves ≥ 10 percentage points within 90 days of channel-specific onboarding interventions

**Channel Quality:**
- Revenue Quality Score calculated and updated for all active acquisition channels weekly (without manual analyst involvement)
- Budget allocation shifted so that channels with Revenue Quality Score > 200 receive ≥ 40% of total PLG acquisition budget within 60 days of system implementation
- Channel-level conversion rate variance (highest-performing channel vs. lowest-performing channel) narrows ≥ 15% as onboarding optimization equalizes conversion across channels

**PQL Performance:**
- PQL Tier 1 users contacted by SDR within 2 hours in ≥ 85% of cases (vs. typical 3-7 day response time before system implementation)
- PQL-to-paid conversion rate ≥ 35% for Tier 1 accounts (at or above industry benchmark for high-intent PLG accounts with timely SDR follow-up)
- SDR time spent per PQL decreases ≥ 30% as the behavioral context package reduces research time per account

**Revenue Impact:**
- MRR from PLG-originated accounts increases ≥ 25% within 6 months of full system deployment — driven by conversion rate improvement, not sign-up volume increase
- LTV:CAC ratio for PLG-originated accounts improves as budget shifts toward higher Revenue Quality Score channels, reducing the cost basis of acquired customers
- Expansion MRR from PLG-originated accounts increases as the Expansion Signal Agent activates accounts approaching plan limits with shorter lag time between signal and outreach

## Related Prompts
- [AI-Powered B2B SaaS Marketing-Led Expansion Revenue Analytics & NRR Attribution Intelligence Engine](./AI-Powered-B2B-SaaS-Marketing-Led-Expansion-Revenue-Analytics-&-NRR-Attribution-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Webinar & Virtual Event Revenue Attribution & Marketing ROI Intelligence Engine](./AI-Powered-B2B-SaaS-Webinar-&-Virtual-Event-Revenue-Attribution-&-Marketing-ROI-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Free Trial Activation Funnel CRO & Time-to-Value Conversion Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Free-Trial-Activation-Funnel-CRO-&-Time-to-Value-Conversion-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Predictive Marketing Pipeline Intelligence & Forward-Looking Revenue Forecast Engine](../KPI-Dashboard-Creation/AI-Powered-B2B-SaaS-Predictive-Marketing-Pipeline-Intelligence-&-Forward-Looking-Revenue-Forecast-Engine.md)

## Integration Tips

**Amplitude / Mixpanel Integration:**
- Create a "PLG Funnel" dashboard with 5 charts: (1) weekly signups by acquisition channel, (2) 7-day activation rate by channel, (3) 30-day conversion rate by weekly cohort, (4) behavioral score distribution at 72 hours, (5) median time-to-activation trend
- Set up Amplitude Cohorts or Mixpanel Cohorts for each PQL tier — these cohorts automatically update as users cross behavioral thresholds and can sync directly to HubSpot or Salesforce to trigger workflows
- Use Amplitude's Signal or Mixpanel's Insights to run the activation correlation analysis: use "converted to paid" as the outcome metric and run correlation against all in-product events within the first 7 days — Amplitude surfaces the highest-correlated events automatically

**HubSpot Integration:**
- Create a custom contact property "PLG Behavioral Score" that updates via Amplitude/Mixpanel webhook every 24 hours for all trial contacts
- Build HubSpot Workflows triggered by score thresholds: Score ≥ 60 → create Task assigned to SDR with behavioral context note; Score 30-59 → enroll in high-touch email sequence; Score < 30 → enroll in lightweight nurture
- Use HubSpot's Contact Activity Timeline to display product events from Amplitude/Mixpanel alongside email engagement — this gives the SDR the full behavioral picture in one place without switching tools

**Salesforce Integration:**
- Create a custom "PLG Score" field on Lead object; use Zapier or native Amplitude/Mixpanel Salesforce connector to update score daily
- Build a Salesforce Report "PQL Tier 1 Uncontacted" that lists all Tier 1 PQLs with no logged Activity in the past 2 hours — this is the SDR manager's daily accountability report
- Use Salesforce Flow to create a Task automatically when a lead crosses Tier 1 threshold — assign to the appropriate SDR queue and populate a custom "PLG Context" text field with the behavioral brief auto-generated from Amplitude data

**Segment (CDP) Integration:**
- If using Segment as your customer data platform, set up computed traits for behavioral score calculation — Segment recalculates the trait for every user every 24 hours based on event stream, eliminating the need for any custom scoring infrastructure
- Use Segment's Audiences to create PQL tier audiences that sync simultaneously to Salesforce (for SDR routing), HubSpot (for email sequences), and LinkedIn Campaign Manager (for retargeting) — one audience definition, multi-channel activation

**Google Ads / LinkedIn Ads Integration:**
- Pass behavioral score data back to Google Ads and LinkedIn as offline conversion events: users who reach PQL Tier 1 status generate a "High Quality Trial" conversion event that the ad platforms use to optimize toward the acquisition signals that produce high-behavioral-score users (not just cheap clicks)
- Use LinkedIn's Matched Audiences to build separate retargeting lists for each PQL tier — HCP (Tier 1) accounts see product proof and upgrade-focused ads; LCP accounts see broader awareness/education content
- Enable Google Ads Enhanced Conversions to pass hashed email addresses from paid sign-ups back to Google — this allows Google to attribute downstream paid conversions (which may happen 14-30 days after the original click) to the correct search campaign and keyword

## Troubleshooting

**Problem: Behavioral scoring model shows all users clustering in the same score band — no meaningful differentiation between high and low probability converters.**
Solution: This almost always means the Tier 1 signals are not specific enough to your product's actual "aha moment." Generic signals like "logged in 3 times" or "completed profile" predict conversion very weakly. Revisit the activation correlation analysis with a narrower lens: look specifically at the 10% of trial users who converted within 14 days (your fastest converters) — what did they do in their first 24 hours that slower or non-converting users did not do? The behavioral gap between your fastest converters and your non-converters is likely very specific (e.g., they created a template, not just a blank document; they connected an integration, not just viewed the integrations page; they sent an invite, not just looked at team settings). Redefine your Tier 1 signals around these specific fast-converter behaviors and retrain the model.

**Problem: PQL Tier 1 accounts are being contacted by SDR but conversion rate from PQL to paid is below 20% — lower than expected for high-intent accounts.**
Solution: Two possible root causes. First, the SDR response messaging is generic — the SDR is using their standard cold outreach sequence rather than a personalized message tied to the specific product behaviors that triggered the PQL alert. The behavioral context package must be used to write the first message, not as background information. If the user hit the "team size limit" paywall three times, the first message should open with: "I noticed your team has been running into the workspace limit — [similar company name] in [industry] had the same situation and upgraded to the Team plan specifically to [outcome they achieved]." Second, the PQL threshold may be over-sensitive — if the threshold is too low, accounts are being routed to SDR before they've experienced enough product value to be genuinely ready for a sales conversation. Raise the threshold or add a time-in-product requirement (e.g., score ≥ 60 AND at least 3 sessions) before Tier 1 routing fires.

**Problem: Channel Quality Scores are calculated but marketing leadership won't shift budget based on them — they argue that different channels serve different funnel stages and shouldn't be compared on the same metric.**
Solution: This is a legitimate concern that requires segmenting the Channel Quality Score by ICP match. Create two separate scores: (1) Revenue Quality Score for direct-response channels where trial quality is directly attributable (paid search, paid social, review site traffic), and (2) Pipeline Influence Score for awareness and educational channels (top-funnel SEO, thought leadership, social content) where the channel's role is brand building and education, not direct conversion. Use the Revenue Quality Score for budget decisions on direct-response channels; use share-of-voice and brand lift metrics for awareness channels. This framing acknowledges that not all channels are in the same stage of the funnel while still holding every channel accountable to a clear measurement standard.

## Version History
- v1.0: Initial creation (auto-generated)
