# AI-Powered B2B SaaS Freemium & PLG Pricing Conversion Analytics & Self-Serve Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** plg-analytics, freemium-conversion, self-serve-revenue, trial-to-paid, pricing-optimization, product-led-growth, pql, saas-analytics, cohort-analysis, revenue-intelligence

## Overview
Transforms product usage data, billing records, and cohort analytics into a comprehensive freemium and self-serve pricing intelligence report — surfacing where free users convert to paid, which pricing tiers capture the most value, what usage thresholds predict conversion, and where pricing friction destroys pipeline. Use monthly to optimize your free-to-paid funnel, tier packaging, and self-serve pricing architecture without relying on sales rep intuition.

## Quick Copy-Paste Version

You are a senior B2B SaaS growth analyst specializing in product-led growth monetization. Analyze the following product usage and billing data to produce a comprehensive freemium and PLG pricing conversion intelligence report — identifying conversion bottlenecks, pricing tier gaps, and the highest-ROI optimization opportunities.

FREE USER & TRIAL DATA (past 90 days):
[Paste your data here — include: number of free/trial accounts created, trial length (days), conversion rate to paid, average time-to-convert (days), most-used features during trial, features that preceded conversion vs. features used by churned trials, team size at signup, industry, company size]

PRICING TIER PERFORMANCE:
- Free tier (if applicable): active free users, % converting to paid within 30/60/90 days, monthly expansion from free to paid
- Starter/Basic tier: conversion rate from trial, average ACV, average usage at tier (seats, usage units, actions), churn rate, upgrade rate to next tier
- Growth/Professional tier: same metrics
- Enterprise/custom: same metrics
- Pricing page visit-to-trial rate, trial-to-paid rate, and primary drop-off reason from exit surveys or support tickets

BUSINESS CONTEXT:
- Pricing model: [e.g., freemium + 3 paid tiers; $0/$49/$199/$499 per month]
- Primary value metric: [e.g., number of seats, API calls, records, projects, GB storage]
- Trial length: [e.g., 14-day full-feature trial vs. freemium with feature limits]
- ICP: [e.g., 10–200 employee SaaS companies, ops/marketing/engineering teams]
- Top conversion trigger you believe exists: [e.g., users who create 3+ projects in first 7 days]

Produce this analysis:

1. EXECUTIVE SUMMARY (3 bullets: conversion funnel health, biggest pricing lever, #1 experiment to run this month)

2. FREE-TO-PAID CONVERSION FUNNEL:
   - Free signup → trial activation rate (used at least once in first 48 hours)
   - Activated trial → converted to paid rate at 30/60/90 days
   - Where the largest drop-off occurs and most likely cause
   - Median time-to-convert for users who do convert — and what they did in the 48 hours before upgrading

3. TIER CONVERSION ANALYSIS:
   - Which tier do most self-serve buyers choose first? What % of revenue does each tier contribute?
   - Upgrade path performance: what % of Starter users upgrade to Growth within 6 months?
   - "Tier ceiling" signals: usage patterns that predict a user is hitting their tier limits and primed for upgrade
   - Tier downgrade and churn rate by plan — which tier has worst retention?

4. USAGE-TO-CONVERSION CORRELATION:
   - Top 3 product actions most correlated with conversion from free/trial to paid
   - "Aha moment" sequence: what does a user who converts in <14 days do in their first session that a churned trial doesn't?
   - Usage thresholds that predict conversion (e.g., "users who trigger Feature X 5+ times convert at 3x the rate")
   - Negative signals: product behaviors that predict churn before trial ends

5. PRICING PAGE & CHECKOUT ANALYTICS:
   - Pricing page visit-to-trial conversion rate — benchmark is 15–25% for B2B SaaS
   - Most common pricing objections from support tickets, exit surveys, or sales-assist conversations
   - Billing friction: failed payment rate, dunning recovery rate, credit card decline patterns
   - Annual vs. monthly plan adoption rate — and NRR differential between annual and monthly cohorts

6. SELF-SERVE REVENUE EXPANSION:
   - Net Revenue Retention (NRR) for purely self-serve cohorts vs. sales-assisted cohorts
   - Seat expansion rate: users who added team members within 90 days of paying (viral coefficient)
   - Feature unlock upgrades: % of expansions triggered by hitting a feature limit vs. proactive upsell notification
   - Average time from first paid to first expansion event

7. OPTIMIZATION QUICK WINS (3 experiments, ranked by projected conversion lift):
   - Experiment name, hypothesis, implementation effort (Low/Medium/High), projected impact

Format output as an executive PLG monetization brief with specific conversion rates, dollar amounts, and a prioritized experiment backlog.

## Advanced Customizable Version

ROLE: You are an AI-powered PLG monetization intelligence engine embedded as a strategic analytics partner to the CPO, CMO, and Head of Revenue. Your mandate is to transform product telemetry, billing system data, CRM records, and user behavior signals into a precision freemium and self-serve pricing intelligence framework — eliminating conversion friction, optimizing tier packaging for maximum NRR, identifying Product Qualified Lead (PQL) scoring opportunities, and designing pricing experiments that compound self-serve revenue without requiring headcount.

OBJECTIVE: Produce a comprehensive freemium and PLG pricing conversion audit that quantifies the revenue impact of every stage in the self-serve funnel, identifies the usage behaviors and pricing signals that predict conversion and expansion, and outputs a prioritized monetization optimization roadmap with projected ARR impact for each recommendation.

---

INPUTS — Provide all available data:

PRODUCT USAGE DATA (past 90 days):
Format: User/Account ID | Signup Date | Plan (Free/Trial/Tier) | Company Size | Industry | Day-1 Actions (feature list) | Day-7 Actions | Day-14 Actions | Convert Date (if converted) | Churned Date (if churned) | Conversion Tier | ACV
[Paste or describe your product analytics export — Mixpanel, Amplitude, Heap, or similar]

BILLING & SUBSCRIPTION DATA:
- MRR by plan tier, broken down by new MRR, expansion MRR, contraction MRR, churn MRR
- Cohort retention curves: % of users on each plan still paying at 1/3/6/12 months
- Annual vs. monthly plan split and NRR differential
- Failed payment and dunning recovery metrics
- Upgrade and downgrade velocity by tier

PRICING PAGE ANALYTICS:
- Unique visitors to pricing page per month (last 3 months)
- Visit-to-trial conversion rate
- Most common exit points on pricing page (heatmap or scroll data if available)
- A/B test results if any have been run on pricing page (tier names, price points, CTA copy)
- Pricing page sources: what channels drive the highest-converting pricing page traffic?

PQL & SALES-ASSIST DATA:
- Definition of PQL at your company (if defined): criteria and score threshold
- % of paying customers who were flagged as PQL before converting
- Time-to-close for PQL-sourced deals vs. inbound demo requests vs. purely self-serve
- Revenue per PQL vs. revenue per non-PQL conversion
- Sales-assist trigger events: which usage patterns prompted SDR or AE outreach?

SUPPORT & VOICE-OF-CUSTOMER DATA:
- Top 10 support tickets or chat conversations about pricing, plan limits, or upgrade questions (last 90 days)
- NPS score by plan tier — do higher-tier users score higher? What are the top themes in free-user NPS detractors?
- Cancellation survey data: top reasons for churning from paid plans

---

ANALYSIS FRAMEWORK — Produce all sections:

**SECTION 1: PLG MONETIZATION HEALTH DASHBOARD**
Score each dimension Green/Yellow/Red with benchmark context:
- Free-to-Paid Conversion Rate: % of free/trial accounts that convert within 30 days (benchmark: 2–5% for freemium, 15–25% for time-limited trials)
- Trial Activation Rate: % of signups who use the product within 48 hours (benchmark: >60%)
- Time-to-Value: median days from signup to first "aha moment" action (benchmark: <3 days)
- Self-Serve NRR: net revenue retention from purely self-serve cohorts (benchmark: >100% for healthy PLG)
- Seat Expansion Rate: % of paid accounts that added users within 90 days (benchmark: >30% for collaborative tools)
- Pricing Page Conversion Rate: visit-to-trial rate (benchmark: 15–25%)

**SECTION 2: CONVERSION FUNNEL FORENSICS**
Map every stage with volume, conversion rate, and revenue implication:

Stage 1 — Signup → Activation (first meaningful product action within 48 hours):
- Activation rate and definition of "activated"
- Fastest path to activation: what did users who activate in <30 minutes do first?
- Activation blockers: setup friction, missing integrations, empty-state UX — flag the top 2 with highest drop-off

Stage 2 — Activation → PQL (hit usage threshold that predicts conversion):
- Define the leading conversion indicators: which 3 product events, when completed together, predict 70%+ conversion probability?
- Time-to-PQL distribution: how long does it take most converted users to hit PQL threshold?
- PQL false negatives: highly engaged users who hit PQL threshold but did NOT convert — what stopped them? (pricing barrier, feature gap, wrong ICP?)

Stage 3 — PQL → Paid Conversion:
- Self-serve conversion rate (no sales touch) vs. sales-assisted conversion rate
- For self-serve conversions: which pricing tier do they choose first? What % choose annual?
- Conversion killers: most common reasons users abandon the upgrade flow mid-checkout
- Credit card friction: what % of intent-to-pay sessions fail due to payment issues?

Stage 4 — Paid → Expansion:
- Expansion triggers: seat additions, feature unlocks, usage-limit hits — which drives most expansion revenue?
- Expansion velocity: median days from first paid to first expansion event
- Proactive vs. reactive expansion: what % of expansions are self-initiated vs. triggered by a limit notification?
- Expansion suppression: users at or near tier limits who did NOT expand — what is the ARR opportunity if they had?

**SECTION 3: PRICING TIER ARCHITECTURE ANALYSIS**
Evaluate whether your tier design maximizes revenue capture:

Tier Fit Analysis:
- For each tier: what is the median usage at the point of paying? Are users hitting their tier limits quickly (under-priced) or using <30% of their limit (over-featured for price)?
- Value metric alignment: does your primary billing metric (seats, usage, projects) correlate with the customer's perceived value? Or do high-value customers pay the same as low-value customers?
- "Good-Better-Best" logic: does each tier have a clear reason to upgrade? Map the 3 most common reasons users upgrade from each tier — are these reasons addressed in your packaging or are they surprises?

Packaging Gap Analysis:
- Features in the free tier that should be gated (giving away too much, suppressing conversion)
- Features locked behind paid tiers that are causing trial abandonment (conversion-blocking gates)
- Missing tier: is there a clear gap in your pricing architecture where a segment of users doesn't fit neatly? (e.g., too big for Starter, too small for Enterprise — the classic "mid-market trap")

Willingness-to-Pay Signals:
- Pricing page behavior: which plan do users hover on or click into most before choosing a lower plan? This reveals WTP above their conversion tier
- Churn-to-compete analysis: users who churned and later re-subscribed — at what price did they return? (reveals true WTP floor)
- Annual upgrade conversations: what % of monthly users, when proactively offered an annual discount, accept? What discount threshold triggers acceptance?

**SECTION 4: PQL SCORING MODEL DESIGN**
Build or validate a Product Qualified Lead scoring framework:

Conversion-Predictive Behaviors (rank by correlation strength):
- List the top 5 in-product events most correlated with 30-day paid conversion
- List the top 3 account-level signals most correlated with expansion revenue within 6 months
- Negative signals: behaviors most correlated with churn before trial end

PQL Threshold Recommendations:
- Recommended PQL score components: event weights, frequency minimums, recency decay
- Score threshold for SDR outreach vs. score threshold for automated upgrade nudge only
- PQL scoring by ICP segment: do PQL behaviors differ by company size, industry, or job function?

PQL-to-Revenue Modeling:
- Estimated revenue per PQL at current conversion rates
- Projected ARR uplift if sales team increases PQL response rate from current to 80% within 24 hours
- Recommended PQL handoff protocol: what context should the SDR have when reaching out? (usage summary, features explored, team size, ICP fit score)

**SECTION 5: SELF-SERVE MONETIZATION EXPERIMENTS BACKLOG**
Prioritize by projected ARR impact and implementation effort:

For each experiment: Hypothesis | Metric to move | Baseline | Target | Implementation effort (Low/Medium/High) | Data needed to validate

Tier 1 Experiments (highest impact):
1. Pricing page redesign: test annually-first pricing display (show annual price as default, not monthly) — benchmark: 20–40% annual plan adoption increase
2. Upgrade trigger timing: A/B test upgrade prompts at 60% of limit hit vs. 90% of limit hit — which drives more conversions with fewer churns from friction?
3. Trial length optimization: 7-day vs. 14-day vs. 21-day trial — model which length produces best conversion × ACV outcome
4. Feature gate adjustment: remove one conversion-blocking gate from free tier and measure trial activation improvement vs. paid conversion rate impact

Tier 2 Experiments (medium impact):
5. Annual plan incentive: test 2-months-free vs. 20%-off framing for annual commitment — which language increases annual adoption?
6. Seat-expansion nudge: automated in-app message when account hits 3+ active users on individual plan ("Add your team") — measure viral expansion coefficient
7. PQL outreach personalization: test usage-context-aware SDR email vs. generic outreach — measure reply rate and conversion rate differential

**SECTION 6: SELF-SERVE REVENUE ARCHITECTURE ROADMAP**
90-day monetization optimization plan with owner, timeline, and projected ARR impact:

Priority 1 (Week 1–2): Quick activation improvements — fix the top 2 activation blockers with no-code or low-code changes
Priority 2 (Week 2–4): Launch the #1 Tier 1 experiment with proper instrumentation
Priority 3 (Month 2): PQL scoring model implementation and SDR workflow integration
Priority 4 (Month 3): Pricing page redesign based on experiment data and WTP signals
Ongoing: Monthly PLG monetization review cadence with this prompt framework

**SECTION 7: CFO/BOARD PLG REVENUE NARRATIVE**
One-page executive summary framing PLG monetization as a revenue multiplier:
- Current self-serve ARR and % of total ARR
- Projected ARR uplift if conversion rate improves to benchmark
- Cost efficiency: CAC for self-serve vs. sales-assisted customers, and LTV/CAC ratio for each
- Top 3 monetization optimizations with payback period and ARR impact
- Leading indicators to track weekly: Trial Activation Rate, Free-to-Paid Conversion Rate, Self-Serve NRR, PQL Volume

OUTPUT FORMAT: Full structured report with executive summary, all 7 sections, a ranked experiment backlog table, and a one-page appendix defining all metrics and their calculation methodology.

## Example Input/Output

**Input Example:**

BUSINESS CONTEXT: Vetrio — B2B SaaS project management and resource planning tool for creative agencies, $0 / $39 / $119 / $299 per user per month (freemium model, no trial expiry). Primary value metric: seats. ICP: creative agencies with 10–100 employees.

PRODUCT DATA (Q2 2026, 2,840 new free signups):
- Activation rate (used at least once in 48 hours): 54%
- 30-day free-to-paid conversion rate: 3.1% (industry benchmark: 3–5%)
- Median time-to-convert: 11 days
- Most common first paid plan: Starter ($39/user/mo) — 71% of conversions
- Top 3 features used before conversion: Project Board (89%), Resource Calendar (67%), Client Portal (42%)
- Users who invited a team member within 7 days: convert at 6.8x vs. solo users

TIER DATA:
- Starter ($39/user): 1,240 accounts, avg 2.3 seats, 12-month retention 61%, upgrade to Growth: 18%
- Growth ($119/user): 380 accounts, avg 6.1 seats, 12-month retention 74%, upgrade to Enterprise: 9%
- Enterprise ($299/user): 44 accounts, avg 18.4 seats, 12-month retention 91%
- Self-Serve NRR: 94% (below 100% benchmark)
- Annual plan adoption: 28% of new paid signups

PRICING PAGE:
- Monthly visitors: 8,400 | Visit-to-signup rate: 14.2% (slightly below 15% benchmark)
- Top exit survey reason: "Price too high for the features I need" (38%), "Not sure which plan is right for me" (29%)

**Output Example:**

EXECUTIVE SUMMARY
• Conversion funnel health: 3.1% free-to-paid is within benchmark but self-serve NRR at 94% signals churn exceeding expansion — the business is leaking as fast as it fills. Priority is fixing Starter tier retention before scaling acquisition.
• Biggest pricing lever: The team-invite signal is massive — users who invite a teammate within 7 days convert at 6.8× the solo-user rate. The free tier does not prompt team invitations early enough. Adding a "Bring your team" moment at Day 2 is the single highest-impact activation change.
• #1 experiment this month: Gate the Resource Calendar feature (currently free, used by 67% of converters) behind the Starter plan. Hypothesis: free users who need Resource Calendar will convert rather than lose access, increasing 30-day conversion rate from 3.1% to 4.5%+ without materially harming activation.

CONVERSION FUNNEL FORENSICS

Stage 1 — Signup → Activation: 54% activation (below 60% benchmark → YELLOW)
Primary blocker: Users who complete Project Board setup activate at 78%; users who skip setup wizard activate at 31%. Onboarding wizard completion rate: 42%. Fix: make Project Board creation mandatory in the onboarding flow before landing on the dashboard. Estimated activation lift: 8–12 points.

Stage 2 — Activation → PQL: Current PQL definition: not formally defined.
Conversion-predictive behaviors (from cohort analysis):
1. Invited at least 1 team member → 6.8× conversion lift
2. Used Resource Calendar 3+ times in first 7 days → 4.1× lift
3. Created a Client Portal → 3.2× lift
Users who complete all 3 behaviors within 14 days: 23% of activated users; they convert at 19.4% (vs. 3.1% overall). Recommended PQL threshold: 2 of 3 behaviors within 14 days → SDR outreach.

Stage 3 — PQL → Paid: 71% choose Starter plan initially. Of those, 22% later express regret they didn't start on Growth (support ticket signal). Pricing confusion accounts for 29% of pricing page abandonment — the plan differentiation is unclear. Recommended fix: rename tiers to agency-specific language ("Solo," "Agency," "Studio") and rewrite comparison table copy to lead with agency workflow outcomes, not feature lists.

SELF-SERVE NRR ANALYSIS: 94% (below 100% benchmark → YELLOW)
Root cause: Starter tier churn rate 39% at 12 months (high). Churned Starter accounts had average 1.8 seats — they signed up as individuals, not teams. Individual users without team adoption churn because the product's core value is collaborative. Recommendation: Require minimum 2 seats on Starter plan. Expected NRR lift: +6–9 points as individual-use churn is eliminated and remaining cohort is inherently collaborative.

## Success Metrics

- Free-to-paid conversion rate reaches or exceeds 4% within 2 quarters of optimization
- Trial/free activation rate improves to >65% within 60 days of onboarding changes
- Self-serve NRR reaches >105% within 3 quarters (expansion outpacing contraction + churn)
- PQL volume grows month-over-month as scoring model is tuned
- Annual plan adoption rate increases to >35% of new paid accounts within 2 quarters
- Pricing page visit-to-signup rate improves to >18% after redesign
- Time-to-first-expansion event decreases by at least 15 days as seat expansion nudges launch

## Related Prompts

- [AI-Powered B2B SaaS Self-Serve Trial-to-Paid Conversion Architecture & Product-Led Revenue Expansion Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Self-Serve-Expansion/AI-Powered-B2B-SaaS-Self-Serve-Trial-to-Paid-Conversion-Architecture-&-Product-Led-Revenue-Expansion-Intelligence-Engine.md)
- [AI-Powered Product-Led Growth Activation & Freemium Conversion Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-Product-Led-Growth-Activation-&-Freemium-Conversion-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Pricing Analytics & Discount Intelligence Engine](./AI-Powered-B2B-SaaS-Pricing-Analytics-&-Discount-Intelligence-Engine.md)
- [CAC Payback & Unit Economics Intelligence Engine](../CAC-Payback-&-Unit-Economics-Analytics/CAC-Payback-&-Unit-Economics-Intelligence-Engine.md)

## Integration Tips

- **Amplitude / Mixpanel / Heap:** Build a conversion funnel chart from Signup → Activated → PQL → Paid → Expanded. Export cohort data as CSV and paste directly into the advanced prompt. Set up automated weekly funnel snapshots delivered to Slack or email for the growth team.
- **Stripe / Chargebee / Recurly:** Pull MRR movement report (new, expansion, contraction, churn) by plan tier on a monthly basis. Use the billing export to calculate self-serve NRR by cohort — this is more accurate than CRM-based NRR for self-serve motions.
- **HubSpot / Salesforce:** Create a PQL object or contact property based on your scoring model outputs. Trigger an SDR task when a contact hits the PQL threshold — include the last 5 product events and account-level usage summary in the task description for personalized outreach.
- **Segment / RudderStack:** Set up event tracking for every PQL-predictive behavior identified in this analysis. Pipe these events into your CRM and email marketing platform to trigger automated upgrade nudges at the right moment without manual SDR intervention.
- **Intercom / Drift / Customer.io:** Design an in-product messaging sequence triggered by PQL behaviors: Day 1 (activate), Day 3 (team invite prompt), Day 7 (feature discovery for conversion-correlated features), Day 12 (upgrade offer with annual incentive). Measure each message's impact on conversion rate independently.
- **Google Analytics 4 / PostHog:** Set up a pricing page funnel with event tracking on each plan's CTA, annual/monthly toggle clicks, and checkout initiation. Use this data to feed the Pricing Page & Checkout Analytics section of this prompt monthly.
- **Zapier / Make:** Automate monthly data collection by pulling Stripe MRR, Amplitude funnel, and HubSpot PQL reports into a Google Sheet. Run the quick prompt via Claude API and auto-generate a PLG monetization brief delivered to the growth Slack channel on the first Monday of each month.

## Troubleshooting

- **Problem:** Product analytics data is sparse — you don't have event-level tracking for most user actions, only aggregate pageview data.
  **Solution:** Use the Quick Copy-Paste version with the data you have (plan counts, MRR by tier, cancellation survey data). The prompt will still surface tier-level conversion and retention insights. In parallel, implement Amplitude or Mixpanel with a starter tracking plan covering 10 core events — prioritize: Signup, Onboarding Step Completed, First Core Action (your product's equivalent of "invite sent" or "project created"), Upgrade Initiated, Upgrade Completed, Team Member Invited. This will enable the full Advanced analysis within 30 days.

- **Problem:** Free-to-paid conversion rate looks healthy (>4%) but revenue growth is stagnant — the business isn't growing despite good conversion.
  **Solution:** The issue is likely upstream (not enough free signups) or downstream (self-serve NRR below 100% with churn outpacing expansion). Run the Self-Serve NRR and Tier Conversion sections in isolation. If NRR is below 100%, the bucket is leaking — expansion optimization and churn reduction will compound faster than acquisition improvements. If NRR is healthy, the problem is acquisition volume — route this analysis to your demand generation team with paid and organic channel data.

- **Problem:** The PQL scoring model identifies users who look ready to convert but sales outreach yields <10% reply rates.
  **Solution:** The outreach message, not the PQL signal, is the problem. Personalize SDR outreach to reference specific product usage: "I noticed your team has been using [Feature X] heavily this week — that's a common pattern before teams unlock [Feature Y] on our Growth plan." Test 3 outreach messages referencing different PQL behaviors and measure reply rate by message variant. Usage-contextualized outreach typically yields 3–5× higher reply rates than generic upgrade emails.

## Version History
- v1.0: Initial creation (auto-generated)
