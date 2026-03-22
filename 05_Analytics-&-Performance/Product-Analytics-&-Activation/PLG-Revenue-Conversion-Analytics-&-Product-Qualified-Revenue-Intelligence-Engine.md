# PLG Revenue Conversion Analytics & Product-Qualified Revenue Intelligence Engine - Turn Product Telemetry Into a Predictive Revenue Machine

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** plg, product-analytics, pql, free-to-paid, expansion-revenue, revenue-intelligence, amplitude, mixpanel, posthog, segment, saas, conversion-analytics, ndr

## Overview
Transforms raw product usage data into a predictive revenue intelligence system that automatically identifies which behavioral sequences drive free-to-paid conversion, expansion, and churn — then outputs a prioritized playbook for marketing, sales, and CS teams to act on high-value signals before revenue is lost or left on the table. Use this when your PLG motion generates signups but you struggle to systematically convert them to paying customers, or when you need to prove (and improve) marketing's contribution to product-led revenue.

## Quick Copy-Paste Version

You are a senior PLG revenue analytics strategist specializing in product-qualified revenue (PQR) for B2B SaaS companies. Analyze the following product and revenue data to deliver a complete PLG Revenue Conversion Intelligence report.

My product context:
- Product/service: [describe what your product does and its PLG motion — e.g., "project management tool with freemium, free users can invite unlimited teammates but hit feature gates at 5 projects"]
- Business model: [Freemium / Free trial (days: X) / Reverse trial / Usage-based]
- Current free-to-paid conversion rate: [X% or "unknown"]
- Monthly free signups: [number]
- Monthly new paid conversions: [number]
- Average time-to-conversion: [X days or "unknown"]
- Expansion MRR as % of total new MRR: [X% or "unknown"]
- Top 3 actions free users take before converting (if known): [action 1, action 2, action 3]
- Top 3 reasons free users don't convert (from surveys/support): [reason 1, reason 2, reason 3]
- Analytics tools: [Amplitude / Mixpanel / PostHog / Heap / other]
- CRM: [Salesforce / HubSpot / other]

Deliver:
1. **PQL Behavioral Fingerprint** — Define the specific sequence of 3-5 in-product actions that most strongly predict conversion within 30 days. Include recommended PQL score thresholds (0-100) with sales/marketing trigger actions at each tier (Hot: 80+, Warm: 50-79, Nurture: 20-49)
2. **Conversion Funnel Breakdown** — Map the free-to-paid funnel with drop-off rates at each stage: Signup → Activation (Aha Moment) → Habit Formation → Value Gate Hit → Paid Conversion. Identify the single highest-leverage intervention point
3. **Time-to-Revenue Acceleration** — Identify which onboarding actions compress the average free-to-paid conversion window by 30%+ and build a 7-day "fast lane" sequence (in-app + email + sales touch) for high-PQL users
4. **Expansion Revenue Triggers** — Identify 5 product usage thresholds that indicate a paid customer is ready for upsell. For each: define the trigger, recommended team to action it (marketing automation vs. CS vs. AE), and the specific offer/message
5. **Cohort Conversion Analysis** — Design a weekly cohort tracking framework showing which signup cohorts convert at higher rates and why. Include 3 hypotheses to test next quarter to improve conversion by 20%+
6. **Product-Led Pipeline Report Template** — Create a weekly marketing/sales review template with these metrics: PQL Volume by Tier, MQL-from-PQL Conversion Rate, Time-from-PQL-to-Opportunity, PLG-Sourced ARR, Expansion MRR by Trigger Type
7. **Revenue Leak Detection** — Identify 4 high-intent abandonment patterns (users who showed buying signals but didn't convert) and design automated recovery campaigns for each
8. **30-Day Quick Wins** — List 5 immediately actionable changes (scoring rule adjustments, new trigger emails, gate repositioning, or CS alert criteria) ranked by expected revenue impact

Format all outputs with specific metric benchmarks. Use SaaS industry averages where my data is unknown.

## Advanced Customizable Version

**ROLE:** You are a VP of Revenue Analytics at a series B-D B2B SaaS company with deep expertise in product-led growth measurement, PQL modeling, and connecting product telemetry to marketing automation and CRM revenue data. You have built PQL scoring systems that increased free-to-paid conversion rates from 2% to 8% and reduced time-to-conversion by 40% at companies including Figma-style design tools, Notion-style workspace tools, and Slack-style communication platforms. You think in funnels, cohorts, and revenue attribution — and you output analysis that non-technical marketing and sales leaders can immediately act on.

**COMPANY CONTEXT:**
- Company name: [Company Name]
- Product category: [e.g., revenue intelligence, developer tooling, data pipeline, HR workflow automation]
- Stage: [Seed / Series A / Series B / Series C / Growth / Public]
- ARR: [$X]
- MRR: [$X]
- Primary GTM motion: [Pure PLG / PLG + Sales-Assisted / Hybrid PLG-SLG / Transitioning SLG→PLG]
- ICP: [job title, company size range, industry]
- Free tier structure: [describe what's included/excluded in free tier]
- Trial structure (if applicable): [X-day trial, features available, credit card required Y/N]
- Analytics stack: [e.g., PostHog + Segment + Customer.io + Salesforce + Looker]
- Current PQL definition (if you have one): [describe or "none defined yet"]

**FUNNEL METRICS (fill in what you know; leave blank if unknown):**
| Stage | Current Rate | Industry Benchmark | Gap |
|---|---|---|---|
| Visitor → Signup | [X%] | 2-5% | [+/- X%] |
| Signup → Activated (Aha Moment) | [X%] | 30-60% | [+/- X%] |
| Activated → Habit Formed (Day 7 Return) | [X%] | 20-40% | [+/- X%] |
| Free → Paid (30-day) | [X%] | 2-8% | [+/- X%] |
| Free → Paid (90-day) | [X%] | 5-15% | [+/- X%] |
| Paid Starter → Paid Growth (Expansion) | [X%] | 20-35%/yr | [+/- X%] |
| Net Dollar Retention (NDR) | [X%] | 110-130% | [+/- X%] |

**PRODUCT BEHAVIOR DATA:**
List the top 10 in-product actions users take (or actions you want to analyze):
| Action Name | Description | Available in Free? | Correlated with Conversion? |
|---|---|---|---|
| [Action 1] | [e.g., "invited 3+ team members"] | [Yes/No] | [Yes/No/Unknown] |
| [Action 2] | [e.g., "created first project from template"] | [Yes/No] | [Yes/No/Unknown] |
[Continue...]

**CURRENT SCORING & TRIGGERS:**
- Do you have a PQL score today? [Yes — describe it / No]
- What automated triggers exist today? [e.g., "email sent when user hits 5-project limit"]
- What does sales/CS use to identify expansion candidates? [describe or "gut feel/manual"]
- What product usage data is currently in your CRM? [describe or "none"]

**OBJECTIVE:** [Select all that apply]
- [ ] Build our first PQL scoring model from scratch
- [ ] Improve an existing PQL model that has low prediction accuracy
- [ ] Increase free-to-paid conversion rate from [X%] to [target X%] in [timeframe]
- [ ] Identify expansion revenue triggers to increase NDR from [X%] to [target X%]
- [ ] Build a PLG revenue attribution model for board reporting
- [ ] Design an automated PQL → sales handoff workflow
- [ ] Identify and recover high-intent churned/abandoned free users

**ANALYTICAL FRAMEWORKS TO APPLY:**
Apply all relevant frameworks and clearly label which you're using:

- **PQL Scoring Matrix (Engagement × Intent × Fit)**: Score users on 3 dimensions: (1) Product Engagement Score — depth/frequency/breadth of usage; (2) Buying Intent Score — feature gate hits, pricing page visits, team invite patterns; (3) Ideal Customer Fit — company size signals, job title, tech stack. Combine into composite PQL score with defined action thresholds.

- **Habit Loop Analysis (Cue → Routine → Reward)**: Identify the specific habit loop your best-converting users develop and map the onboarding interventions that establish that loop in days 1-7.

- **Jobs-to-Be-Done (JTBD) Conversion Trigger**: For each user segment, define the functional job they hired your product to do. Map which product actions complete that job (value delivered) — users who complete the JTBD job convert at 3-8x higher rates. Identify the "job completion moment."

- **Expansion Revenue Ladder**: Map the natural expansion path from free → starter → growth → enterprise by product usage intensity, team size, and value consumed. Define the behavioral signals at each rung that indicate readiness to climb.

- **Cohort Decay Analysis**: For monthly signup cohorts, model conversion rate over 7, 14, 30, 60, and 90 days. Identify which cohorts have abnormally high or low decay rates and diagnose root cause.

- **Revenue Attribution Waterfall**: Connect marketing source → signup → PQL tier → opportunity → closed-won revenue. Attribute PLG-sourced ARR by channel, campaign, and ICP segment.

**DELIVERABLES:**

**Section 1: PQL Model Architecture**
Design a complete PQL scoring system with:
- 8-12 behavioral signals with individual point weights (total: 100 points)
- Tier thresholds: Hot PQL (80-100), Warm PQL (50-79), Nurture PQL (20-49), Not Qualified (<20)
- Recommended CRM field mapping for each signal
- Scoring decay logic (how scores age if no activity)
- Confidence interval: what % of Hot PQLs should convert within 14 days (target: 15-25%)

**Section 2: Conversion Funnel Intelligence**
- Full funnel visualization with current vs. benchmark rates at each stage
- Top 3 drop-off points ranked by revenue impact (lost ARR per month at current drop-off rate)
- For each drop-off: root cause hypothesis + 2 interventions to test + expected lift (%)
- "Aha Moment" identification: the single action that, when completed, predicts 30-day retention with 70%+ accuracy

**Section 3: Expansion Revenue Intelligence**
- 6 product usage triggers that indicate expansion readiness (with specific thresholds, not vague "heavy usage")
- Expansion playbook by trigger type: who acts (marketing automation vs. CS vs. AE), what message, what offer, expected conversion rate
- NDR improvement model: if all 6 triggers are actioned with 15% conversion rate, what is the projected NDR uplift?
- Warning signals: 4 product usage patterns that predict downgrade/churn 30-60 days in advance

**Section 4: PLG Revenue Attribution Model**
- Revenue attribution framework connecting marketing source → product conversion → ARR
- Recommended board metrics: PLG-Sourced ARR %, PLG CAC vs. SLG CAC, Product-Led Pipeline Coverage, PQL→Opportunity Conversion Rate
- Weekly/monthly/quarterly reporting cadence with metric owners
- A/B testing roadmap: 4 experiments to run in Q1-Q2 to improve funnel conversion by 30% total

**Section 5: 90-Day Revenue Acceleration Plan**
| Week | Action | Owner | Expected Impact |
|---|---|---|---|
| 1-2 | [Specific action] | [Marketing/Eng/Sales] | [+X% conversion / $X ARR] |
[Continue for 13 weeks...]

**OUTPUT REQUIREMENTS:**
- Every recommendation must include: specific metric it improves, expected % lift, effort level (Low/Medium/High), and a "done-when" definition
- All scoring thresholds must be justified with logic or industry benchmark references
- Separate "quick wins" (implementable in <1 week with no engineering) from "strategic bets" (require product/engineering investment)

## Example Input/Output

**Input (example company):**
- Company: Clausehound — AI contract review platform, Series A, $3.2M ARR
- Motion: Freemium (free tier: 5 contracts/month; paid: unlimited + AI redlining + clause library)
- Free-to-paid conversion: 2.1% (30-day), 4.8% (90-day)
- Monthly free signups: 1,400
- Analytics: Amplitude + Segment → Salesforce
- Top conversion actions (from light analysis): users who run AI redline on ≥3 contracts AND invite 1+ colleague within 14 days convert at 11.2% — but only 8% of free users hit both triggers
- ICP: GC and legal ops at 50-500 person companies, primarily SaaS and fintech

**Output excerpt (PQL Score Architecture):**

**Clausehound PQL Scoring Model v1.0**

| Behavioral Signal | Points | Rationale |
|---|---|---|
| Ran AI Redline on 1st contract | 15 | Aha moment — first value delivery |
| Ran AI Redline on 3+ contracts (cumulative) | 20 | Habit formation threshold |
| Invited 1+ team member | 18 | Strong team-use intent signal |
| Uploaded contract with custom clause | 12 | Power user behavior, rarely done by low-intent users |
| Visited pricing page 2+ times | 15 | Direct buying intent |
| Hit free tier limit (5 contracts) | 20 | Explicit conversion trigger |
| Completed onboarding checklist | 8 | Engagement proxy |
| Used clause library feature | 7 | Feature breadth adoption |
| Logged in 3+ days in first week | 5 | Early habit signal |
| **Maximum Score** | **120** (normalized to 100) | |

**Tier Thresholds:**
- **Hot PQL (80-100):** Immediate SDR outreach within 4 business hours. Expected conversion: 18-22%
- **Warm PQL (50-79):** Marketing automation sequence: 4-touch email + 1 in-app message over 7 days
- **Nurture PQL (20-49):** Weekly product tips email + usage milestone celebrationsconverted at about 2.3% avg
- **Not Qualified (<20):** Onboarding health check email at day 3, no manual resources

**Aha Moment identified:** Users who run their first AI Redline within 72 hours of signup AND see at least 3 clause flags convert at 14.2% vs. 1.8% baseline. Target: compress all users to hit this moment within 48 hours via guided onboarding.

**Top Expansion Trigger identified:** Paid customers who upload 40+ contracts/month AND have 3+ active users show 76% likelihood of upgrading to Growth plan within 60 days. Current CS coverage of this segment: 22%. Opportunity: 41 accounts × estimated $400 ACV uplift = $197K identified expansion ARR not being actively worked.

## Success Metrics

**Your PQL model is working if:**
- Hot PQL → Paid conversion rate ≥15% within 30 days (vs. overall baseline)
- PQL scoring model captures ≥60% of all eventual converters within the Hot + Warm tiers
- Time-from-PQL-Hot-designation to first sales contact ≤4 business hours
- Free-to-paid conversion rate improves ≥25% within 90 days of model deployment
- Expansion triggers fire with ≥80% accuracy (accounts flagged actually upgrade/expand within 60 days)
- NDR improves ≥5 percentage points within 2 quarters of systematic expansion trigger activation
- PLG-sourced ARR is trackable and growing as % of total new ARR

**Model quality indicators:**
- PQL score correlates with conversion rate at r² ≥ 0.65
- Less than 20% of Hot PQLs go cold without a conversion action within 14 days
- Expansion trigger false positive rate < 25%

## Related Prompts

- [`./Feature-Adoption-Stickiness-&-Retention-Intelligence-Engine.md`](./Feature-Adoption-Stickiness-&-Retention-Intelligence-Engine.md) — use first to identify which features should anchor your PQL scoring model
- [`../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Freemium-Conversion-&-PQL-Nurture-Automation-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Freemium-Conversion-&-PQL-Nurture-Automation-Engine.md) — use to build the nurture sequences that activate your PQL tiers
- [`../../02_Product-Marketing/Go-To-Market-Strategy/Product-Led-Sales-Motion-Intelligence-Engine.md`](../../02_Product-Marketing/Go-To-Market-Strategy/Product-Led-Sales-Motion-Intelligence-Engine.md) — use to design the sales overlay motion for Hot PQLs
- [`../Revenue-Forecasting-&-Pipeline-Intelligence/Predictive-Revenue-Forecasting-&-Marketing-Pipeline-Intelligence-Engine.md`](../Revenue-Forecasting-&-Pipeline-Intelligence/Predictive-Revenue-Forecasting-&-Marketing-Pipeline-Intelligence-Engine.md) — use to roll PLG pipeline data into your revenue forecast model

## Integration Tips

**Amplitude/Mixpanel → Salesforce:**
- Create computed traits in Segment (or use Amplitude Destination) to push PQL score as a custom field to Salesforce Lead/Contact object
- Set up real-time score updates: trigger Salesforce workflow rules when PQL score crosses Hot threshold
- Build Salesforce report: "Hot PQLs not contacted in 4 hours" as SDR dashboard alert

**PostHog → HubSpot:**
- Use PostHog's HubSpot integration to sync behavioral events as HubSpot Timeline Events
- Create HubSpot Property: `pql_score` (number), `pql_tier` (dropdown: Hot/Warm/Nurture/Not Qualified)
- Use HubSpot Workflows triggered on `pql_tier = Hot` to auto-enroll in sales sequence and notify assigned rep

**Looker/Metabase PLG Revenue Dashboard:**
Create these 6 views:
1. Weekly PQL Volume by Tier (bar chart, 13-week rolling)
2. PQL → Opportunity Conversion Rate by Tier (line chart)
3. Time-from-PQL-Hot to First Contact (histogram with SLA line)
4. PLG-Sourced ARR % of Total New ARR (time series)
5. Expansion MRR by Trigger Type (stacked bar)
6. Cohort Conversion Curves (7/14/30/60/90-day for each monthly cohort)

**Zapier / Make.com automation:**
- Trigger: PQL score crosses 80 → Slack message to assigned SDR with account context card
- Trigger: Expansion trigger fires → Create Salesforce Task for CSM + add to expansion sequence in Outreach/Salesloft
- Trigger: High-PQL user visits pricing page → Notify SDR in real-time via Slack with session recording link (Hotjar/FullStory)

**Customer.io / Klaviyo lifecycle:**
- Segment free users by PQL tier using behavioral data from Segment CDP
- Build dynamic email sequences that adapt content based on PQL score changes week-over-week
- Implement in-app message triggers using Intercom/Pendo/Appcues tied to PQL tier membership

## Troubleshooting

**Problem: PQL model has low prediction accuracy — many Hot PQLs don't convert**
*Fix:* Over-weighting engagement signals vs. intent signals. Audit your score components: reduce points for passive actions (logins, page views) and increase weight for explicit buying signals (pricing page visits, feature gate hits, billing page visits, team seat additions). Run a logistic regression on your last 6 months of converters vs. non-converters to recalibrate weights. Aim for: engagement signals ≤ 40% of total score, intent signals ≥ 40%, fit signals ≥ 20%.

**Problem: Can't connect product data to CRM — PQL scores not visible to sales**
*Fix:* Use Segment as the bridge (even on free tier for smaller volumes). Create a Segment Source from your analytics tool and a Destination to Salesforce/HubSpot. If Segment is too expensive, use Zapier with a webhook trigger: when Amplitude/PostHog fires a `pql_threshold_crossed` event, Zapier reads the score from your database via API and writes to CRM. Document the field mapping spec before engaging engineering — saves 2-3 sprints.

**Problem: Expansion triggers are firing but CS isn't acting on them**
*Fix:* The problem is almost never data — it's workflow and incentive alignment. Three fixes: (1) Route expansion alerts into the CSM's existing workflow tool (Gainsight/Totango/Salesforce) rather than a new dashboard they don't check; (2) Add expansion-trigger-to-opportunity conversion rate to CSM performance reviews; (3) Create a "CS Hot Sheet" that runs Monday morning via Salesforce report showing each CSM their top 5 expansion opportunities ranked by trigger score × account health — takes 2 hours to build, drives immediate behavior change.

## Version History
- v1.0: Initial creation (auto-generated)
