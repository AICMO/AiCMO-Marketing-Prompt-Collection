# AI-Powered B2B SaaS Usage-Based Pricing Analytics & Consumption Revenue Expansion Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** usage-based-pricing, consumption-analytics, b2b-saas, revenue-expansion, ubp, product-led-growth, metered-billing, arr-forecasting, revops, nrr-optimization

## Overview
Transforms product usage telemetry, billing data, and cohort consumption records into a comprehensive usage-based pricing intelligence report — surfacing consumption velocity trends, expansion revenue triggers, at-risk accounts showing usage decline, and tier-fit recommendations that maximize NRR without accelerating churn. Use monthly with your RevOps, Customer Success, and Finance teams to operate a self-serve revenue expansion motion powered by consumption signals rather than manual outreach.

## Quick Copy-Paste Version

You are a senior B2B SaaS revenue analytics expert specializing in usage-based pricing (UBP) and consumption revenue models. Analyze the following usage and billing data to produce a complete consumption revenue intelligence report.

USAGE & BILLING DATA:
[Paste your data here — include: customer ID or segment, current tier/plan, monthly usage (units consumed), usage limit or included units, overage amount this period, committed ARR, expansion ARR from overages, months on platform, industry, employee count, primary use case]

PRICING MODEL CONTEXT:
- Billing unit: [e.g., API calls, active seats, data volume (GB), events processed, messages sent]
- Pricing tiers: [e.g., Starter: 10K units/$499/mo, Growth: 50K units/$1,499/mo, Scale: 250K units/$4,999/mo, Enterprise: custom]
- Overage rate: [e.g., $0.02 per unit above tier limit]
- Commitment structure: [e.g., annual commit with monthly true-up, pure pay-as-you-go, or hybrid]

Produce this analysis:

1. CONSUMPTION HEALTH DASHBOARD (3 bullets: top expansion signal, biggest at-risk pattern, revenue upside this quarter)

2. USAGE COHORT PERFORMANCE:
   - Average % of tier limit consumed by cohort (months 1-3, 4-6, 7-12, 12+)
   - Accounts approaching tier ceiling (>80% consumed): count, ARR, upgrade probability
   - Accounts with declining usage (>20% drop month-over-month): count, ARR at risk, churn probability
   - "Sleeping" accounts (<15% of tier limit used): segment these for activation campaigns

3. EXPANSION REVENUE SIGNALS:
   - Accounts generating overage revenue: list top 10 by overage $ with recommended upgrade tier
   - Estimated ARR uplift if top overage accounts upgrade to appropriate tier
   - Accounts within 1 month of naturally hitting upgrade threshold based on usage trajectory

4. TIER FIT ANALYSIS:
   - Over-tiered accounts (consuming <25% of included units): risk of downgrade, ARR at risk
   - Under-tiered accounts (consuming >80% consistently): quantify upgrade revenue opportunity
   - "Sweet spot" usage range per tier where churn rate is lowest

5. CHURN RISK FROM USAGE SIGNALS:
   - Accounts with 3+ consecutive months of usage decline: flag for CS intervention
   - Accounts who have never reached 30% of their tier limit: likelihood of non-renewal
   - Correlation between onboarding usage velocity (units in month 1) and 12-month retention

6. REVENUE OPTIMIZATION QUICK WINS (3 actions this week, ranked by ARR impact):
   - Specific accounts to contact for upgrade conversation (usage data justification included)
   - Accounts needing activation intervention before next renewal
   - Tier structure adjustment recommendation if usage data reveals a structural gap

7. 90-DAY CONSUMPTION REVENUE ROADMAP — 2 experiments to increase NRR through usage expansion

Format output as a RevOps-ready consumption intelligence brief with specific customer segments, dollar amounts, and prioritized action lists throughout.

## Advanced Customizable Version

ROLE: You are an AI-powered B2B SaaS consumption revenue intelligence engine embedded as a senior analytics partner to the CRO, CFO, and Head of Customer Success. Your mandate is to transform raw product telemetry, billing system data, and cohort consumption records into a precision usage-based pricing analytics framework — maximizing net revenue retention through data-driven tier optimization, expansion signal detection, and proactive churn prevention before renewal conversations begin.

OBJECTIVE: Produce a comprehensive consumption revenue intelligence report that identifies the exact accounts to expand, the exact accounts at churn risk, and the exact pricing tier adjustments that will compound NRR growth quarter-over-quarter — all derived from usage data without reliance on manual CS intuition.

---

INPUTS — Provide all available data:

ACCOUNT-LEVEL USAGE DATA (past 6 months):
Format: Account ID | Segment | Tier | Included Units | Avg Monthly Consumption | Peak Consumption | Months Active | ARR | Overage Revenue (LTM) | Renewal Date | CSM Assigned | Industry | Employee Count | Primary Use Case
[Paste or describe your product analytics / billing system export]

COHORT CONSUMPTION DATA:
- Month-1 usage as % of tier limit, by acquisition cohort (by quarter)
- Usage at month 3, 6, 12 as % of tier limit for each cohort
- % of accounts that crossed the 80% consumption threshold within 12 months (natural upgrade trigger)
- % of accounts that never exceeded 30% consumption within 12 months (structural over-tier risk)

BILLING & EXPANSION DATA:
- Overage revenue by month (LTM): which accounts, which tier, what amount
- Upgrade conversion rate: % of accounts receiving upgrade conversation who actually upgrade within 90 days
- Self-serve upgrade rate: % of accounts who upgraded without CSM intervention (pure product-led expansion)
- Downgrade rate: % of accounts who downgraded at renewal and average ARR impact per downgrade
- Price-per-unit at each tier (calculate effective unit economics): helps identify where margin compression occurs in overage vs. upgrade scenarios

CHURN SIGNAL CORRELATION:
- 12-month retention rate by first-month usage quintile (low usage at onboarding = higher churn signal)
- Retention rate for accounts who generated at least 1 month of overage in their first year vs. those who never did
- Average usage trend slope (MoM % change) for churned accounts in the 3 months before churn — establish the "decline signature"
- Feature adoption breadth correlation: accounts using 1 core feature vs. 3+ features — retention rate difference

COMPETITIVE & PRICING CONTEXT:
- Comparable UBP competitors and their published pricing per unit at scale
- Any customer feedback (NPS verbatims, CS call notes) mentioning pricing model concerns, unit definition confusion, or perceived value misalignment
- List any existing pricing experiments or tier adjustments from the past 12 months and their measured impact

---

ANALYSIS FRAMEWORK — Produce all sections:

**SECTION 1: CONSUMPTION REVENUE HEALTH SCORECARD**
Score each dimension Green/Yellow/Red with benchmark:
- Usage Expansion Rate: % of ARR base generating overage or upgrade revenue in LTM (benchmark: 25–35% for healthy UBP SaaS)
- Tier Fit Score: % of accounts consuming 40–80% of included units (optimal engagement zone — benchmark: 50%+ of base)
- Usage-Weighted NRR: NRR when weighted by consumption velocity cohort (high-usage accounts should skew NRR above reported average)
- Churn Precursor Rate: % of accounts exhibiting 3+ consecutive months of usage decline (threshold: keep below 12%)
- Self-Serve Expansion Rate: % of expansion ARR generated without CSM-initiated conversation (benchmark: 40%+ for PLG-assisted UBP models)
- Overage-to-Upgrade Conversion Rate: % of accounts generating overage who upgrade within 60 days (benchmark: 55%+ with proactive outreach)

**SECTION 2: USAGE COHORT PROGRESSION ANALYSIS**
For each acquisition cohort (by quarter):
- Consumption curve: average % of tier limit consumed at months 1, 3, 6, 9, 12
- Cohort expansion index: expansion ARR generated per $1 of acquisition ARR within 12 months
- "Graduation rate": % of cohort that upgraded at least once within 12 months
- Underperforming cohorts: cohorts whose usage at month 6 is >15% below average — diagnose whether this is a segment issue (wrong ICP), onboarding issue, or product-fit issue
- Leading indicator identification: which month-1 or month-3 usage behaviors most strongly predict 12-month expansion (run correlation analysis)

**SECTION 3: EXPANSION REVENUE SIGNAL MATRIX**
Priority-rank every account in your dataset across four signals:
- SIGNAL A — Tier Ceiling Approach: accounts >75% of included units for 2+ consecutive months → high-urgency upgrade conversation
- SIGNAL B — Overage Pattern: accounts generating overage for 2+ consecutive months without upgrade → price at risk of elasticity damage if overage compounds
- SIGNAL C — Usage Velocity Acceleration: accounts with 15%+ MoM usage growth → proactive expansion before they hit ceiling; creates goodwill vs. reactive bill shock
- SIGNAL D — Feature Adoption Expansion: accounts who activated a new use case or feature in past 60 days → usage ramp likely; set upgrade expectation early

For each signal tier, provide:
- Account count and total ARR
- Average upgrade ARR if moved to next tier
- Recommended outreach script angle (data-driven: "Your usage shows X, which means Y value delivered — you're 3 weeks from your limit")
- Priority scoring: SIGNAL A+B accounts = immediate CSM outreach; SIGNAL C+D = automated in-app nudge + email sequence

**SECTION 4: CHURN RISK EARLY WARNING SYSTEM**
Identify accounts at churn risk from usage signals alone — before renewal conversations:

- RISK TIER 1 (Critical): 3+ consecutive months of >15% MoM usage decline AND renewal within 90 days → immediate ES/CSM escalation
- RISK TIER 2 (High): Usage below 20% of tier limit for 4+ months (structural over-tier, likely considering downgrade or churn) → repackaging conversation needed
- RISK TIER 3 (Moderate): First month of usage decline after 6+ months of stable consumption → investigation call, may be seasonal or org change
- RISK TIER 4 (Watch): New accounts (months 1–3) who have not yet reached 25% of tier limit → onboarding intervention before pattern cements

For each risk tier, provide:
- Account list (sorted by ARR at risk)
- Recommended intervention (CS call, executive outreach, in-app activation campaign, repackaging offer)
- Win-back probability estimate based on usage signal severity
- Revenue recovery projection if intervention succeeds at 60% conversion

**SECTION 5: TIER ARCHITECTURE OPTIMIZATION**
Analyze whether your current tier structure is causing revenue leakage or churn through poor fit:

- Unit economics by tier: effective ARR per unit consumed at each tier — identify where you are under-monetizing at scale vs. overcharging at entry
- Usage distribution gap analysis: if >20% of accounts cluster below 30% of their tier's included units, your bottom tier is too large (or your activation is broken) — quantify ARR at downgrade risk
- Tier boundary dead zones: usage ranges where accounts are "stuck" — too big for current tier but not big enough to justify next tier cost — these are the churners. Quantify and recommend a bridge SKU or intermediate tier pricing.
- Optimal tier sizing recommendation: based on usage percentile distribution, define ideal tier boundaries where median account uses 55–65% of included units (engagement without ceiling anxiety)
- Overage pricing efficiency: if overage revenue is significant but conversion to upgrades is low, your overage rate may be undershooting (cheap overages reduce upgrade urgency) or overshooting (creating bill shock and churn risk at renewal)

**SECTION 6: CONSUMPTION-LED EXPANSION PLAYBOOK**
Build a repeatable, data-driven expansion motion:

- In-app expansion triggers: define the exact usage thresholds that should trigger automated in-app upgrade prompts (e.g., "You've used 78% of your monthly limit — upgrade now to avoid slowdown")
- Email expansion sequences: usage-milestone-triggered emails at 50%, 75%, 90% of consumption — provide subject lines and CTAs based on usage urgency level
- CSM alert configuration: define the Salesforce/HubSpot alert rules for each signal tier so CS receives daily digest of accounts crossing expansion thresholds
- Self-serve upgrade flow optimization: for accounts on SIGNAL A/B, what friction points prevent self-serve upgrade? (pricing page clarity, upgrade confirmation UX, credit card requirements) — audit and recommend
- Expansion QBR template: for accounts in the "optimal engagement zone" (40–80% usage), a QBR narrative that reinforces value delivered per unit and seeds the next expansion conversation 60 days before renewal

**SECTION 7: CFO/BOARD CONSUMPTION REVENUE NARRATIVE**
One-page executive summary framing usage-based pricing as a compounding NRR asset:
- Current Usage Expansion Rate vs. benchmark and trend (improving or declining?)
- ARR upside from converting top overage accounts to appropriate tiers (conservative: 50% conversion; optimistic: 75% conversion)
- ARR at risk from churn-signal accounts (quantified by risk tier)
- Net expansion revenue projection: expected NRR from consumption expansion alone in next 2 quarters
- 3 pricing governance recommendations with timeline and projected ARR impact
- Monthly metrics to track: Usage Expansion Rate, Tier Fit Score, Overage-to-Upgrade Conversion Rate, Churn Precursor Rate

OUTPUT FORMAT: Full structured report with executive summary, all 7 sections, a prioritized account action list (top 20 accounts sorted by combined expansion opportunity + churn risk), and a one-page appendix showing the consumption analytics methodology for RevOps implementation.

## Example Input/Output

**Input Example:**

ACCOUNT DATA (Q1 2026, 340 active accounts):
Pricing unit: API calls (millions)
Tiers: Starter (5M calls/$599/mo), Growth (25M calls/$1,799/mo), Scale (100M calls/$5,999/mo), Enterprise (custom)
Overage rate: $0.08 per 1K calls above tier limit
Distribution: Starter (180 accounts, avg $7,200 ARR), Growth (120 accounts, avg $21,600 ARR), Scale (40 accounts, avg $71,988 ARR)
Overage LTM: $312,000 across 47 accounts
Accounts >80% of tier limit for 2+ months: 38 accounts, $892,000 ARR
Accounts <20% of tier limit for 4+ months: 62 accounts, $445,000 ARR
3+ months consecutive usage decline: 24 accounts, $614,000 ARR at risk

**Output Example:**

CONSUMPTION HEALTH DASHBOARD
• Top expansion signal: 38 accounts totaling $892K ARR are consuming >80% of their tier for 2+ consecutive months — upgrading even 60% of these to next tier generates $1.1M net new ARR this quarter with zero new customer acquisition cost
• Biggest at-risk pattern: 24 accounts ($614K ARR) showing 3+ months of usage decline; 11 of these renew within 90 days — immediate CS escalation required; historical model shows 42% save rate with executive outreach at this stage vs. 8% if contacted at renewal notice
• Revenue upside this quarter: $1.4M ARR expansion opportunity (upgrades + overage-to-upgrade conversions) against $258K ARR churn risk from decline-signal accounts — net expansion potential of $1.14M if playbook executes at 55% efficiency

TIER FIT ANALYSIS:
Starter tier: 34% of accounts consuming <15% of 5M call limit → 61 accounts are structurally over-tiered; at $599/mo, downgrade risk to a hypothetical Micro tier (~1M calls/$199/mo) would cost $194K ARR. RECOMMENDATION: Launch usage-based activation campaign targeting these accounts to drive consumption before their annual renewal — show them ROI through usage, not just sell them on staying.

Growth tier: Optimal engagement zone (40–80% utilization) contains 44% of tier accounts — healthy. 31% are >80% utilization → SIGNAL A accounts; 25% are <25% utilization → activation risk.

EXPANSION REVENUE SIGNAL — TOP 10 ACCOUNTS (SIGNAL A):
1. TechFlow Inc. | Growth tier | 94% utilization 3 months straight | $21,600 ARR → upgrade to Scale = +$50,388 ARR | Contact: Marcus Webb (VP Eng) | Talking point: "At current velocity you hit ceiling in 2–3 weeks; locking in Scale now saves 23% vs. overage rate"
2. DataStream Corp. | Growth tier | 88% utilization | $21,600 ARR → upgrade to Scale = +$50,388 ARR | Renewal: 47 days | URGENT
3. Nexus Analytics | Starter tier | 91% utilization | $7,200 ARR → upgrade to Growth = +$14,400 ARR | Self-serve eligible, no CSM needed — trigger in-app upgrade prompt at next login

CHURN RISK — CRITICAL TIER (RISK TIER 1):
Pinnacle Software | Scale tier | $71,988 ARR | Usage declined 31% over 3 months | Renewal: 61 days
→ Usage pattern matches churner signature (steep decline + no new feature activation in 60 days)
→ Action: VP-level outreach within 48 hours; lead with value audit ("Here's what your team built with 847M API calls last year") before addressing usage decline
→ Win-back probability at this stage: 44% with executive engagement vs. 9% at renewal notice

## Success Metrics

- Usage Expansion Rate reaches 28–35% of ARR base generating upgrade or overage conversion within 2 quarters
- Overage-to-Upgrade Conversion Rate exceeds 55% within 60 days of overage trigger with proactive outreach
- Churn Precursor Rate (accounts with 3+ months usage decline) stays below 12% of base
- Tier Fit Score: >50% of accounts in the 40–80% utilization "optimal engagement zone"
- Self-Serve Expansion Rate exceeds 35% of expansion events (less CSM dependency = scalable NRR)
- NRR improvement of 8–15 points within 3 quarters of implementing consumption-led expansion playbook

## Related Prompts

- [AI-Powered B2B SaaS Pricing Analytics & Discount Intelligence Engine](./AI-Powered-B2B-SaaS-Pricing-Analytics-&-Discount-Intelligence-Engine.md)
- [AI-Powered Net Revenue Retention & Expansion Revenue Intelligence Engine](../Customer-Lifetime-Value-Analytics/AI-Powered-Net-Revenue-Retention-&-Expansion-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B Product Usage Signal & Expansion Revenue Trigger Intelligence Engine](../../06_Customer-Success-&-Retention/Customer-Success-Automation/AI-Powered-B2B-Product-Usage-Signal-&-Expansion-Revenue-Trigger-Intelligence-Engine.md)
- [AI-Powered Product-Led Growth Activation & Freemium Conversion Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-Product-Led-Growth-Activation-&-Freemium-Conversion-Intelligence-Engine.md)

## Integration Tips

- **Snowflake / BigQuery / Databricks:** Query your product event tables to build a consumption_monthly_summary table with account_id, period, units_consumed, tier_limit, utilization_pct, and overage_units — this becomes the core dataset for every section of this prompt. Schedule it as a weekly dbt model refresh.
- **Stripe / Chargebee / Maxio (formerly SaaSOptics):** Pull metered usage records and subscription invoices via API — join on customer_id to get contracted ARR + overage ARR by account in a single dataset. Most billing platforms export this as a CSV from the Revenue Recognition or Usage Billing report section.
- **Amplitude / Mixpanel / PostHog:** Build a "Consumption Velocity" user property that tracks rolling 30-day unit consumption and fires events when accounts cross 50%, 75%, 90% thresholds — pipe these events into your CRM to trigger the expansion playbook automatically without manual analysis.
- **Salesforce / HubSpot:** Create a custom "Usage Utilization %" field on the Account object, synced daily from your data warehouse — build workflow rules that create CS tasks when any account crosses 80% or drops below 25% for 30 days. This makes the expansion playbook operational rather than a monthly spreadsheet exercise.
- **Intercom / Pendo / Appcues:** Configure in-app messages triggered by your Amplitude/Mixpanel "75% threshold crossed" event — show a contextual upgrade prompt with current utilization and pricing comparison. A/B test the CTA: "Upgrade now" vs. "See Scale plan" vs. "Talk to our team."
- **Zapier / n8n / Make:** Build an automated weekly digest: pull utilization data from Salesforce → identify SIGNAL A/B accounts → generate personalized upgrade outreach email via Claude API → route to assigned CSM for review and 1-click send. Reduces CSM prep time from 2 hours to 10 minutes per account.

## Troubleshooting

- **Problem:** Usage data is fragmented — billing system shows contracted units but product analytics tracks different usage metrics, making it hard to calculate true utilization %.
  **Solution:** Establish a single "canonical consumption unit" that matches what appears on invoices (the billing unit is the source of truth). Map all product analytics events to this unit with a conversion factor (e.g., 1 API request = 1 unit, 1 batch job = 500 units). Build a reconciliation check: if product analytics consumption deviates >10% from billing system consumption for the same period, flag for engineering review before running analysis.

- **Problem:** Output identifies many expansion-signal accounts but CS team says "we already know about those" — the report isn't adding value beyond existing intuition.
  **Solution:** The report's value is in quantification and prioritization, not discovery. Re-frame the output around: (1) dollar value at stake per account ranked by urgency, (2) predicted expansion timing based on usage trajectory (not just current state), and (3) accounts the team is NOT currently focused on that usage data flags as high-priority. Ask CS to compare their current priority list against SIGNAL A/B accounts — gaps between intuition and data are where the largest recoverable revenue lives.

- **Problem:** Accounts show consistently high utilization but never upgrade despite CSM outreach — the expansion signal exists but conversion is failing.
  **Solution:** Audit the upgrade path for friction: Is self-serve upgrade available, or does it require a contract amendment? Is the next tier price anchored against the overage cost (overage is often 2–3x more expensive per unit than upgrading, but customers don't see the comparison)? Build a "cost of NOT upgrading" calculator — show the account their last 90 days of overage charges vs. the upgrade cost delta. When the math is visible, conversion rates typically increase 40–60%.

## Version History
- v1.0: Initial creation (auto-generated)
