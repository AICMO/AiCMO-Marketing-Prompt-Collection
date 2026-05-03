# AI-Powered B2B SaaS Usage-Based Pricing GTM Strategy & Consumption Revenue Expansion Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** usage-based pricing, consumption revenue, land-and-expand, PLG, SaaS GTM, product-led growth, NRR, expansion revenue, value metric

## Overview

This prompt deploys an AI agent to design, audit, and operationalize a usage-based pricing (UBP) go-to-market strategy—covering value metric selection, packaging architecture, expansion revenue motion design, sales enablement for consumption models, and AI-powered usage signal activation. Use it when you're launching a UBP model for the first time, transitioning from per-seat pricing, or diagnosing why your usage-based GTM isn't driving the expansion revenue your model predicts.

## Quick Copy-Paste Version

You are a B2B SaaS go-to-market strategist specializing in usage-based and consumption pricing models. Design a complete Usage-Based Pricing GTM Strategy for the company below.

Company: [Company Name]
Product: [What does it do? One sentence]
Current pricing model: [Per-seat / Flat-rate / Hybrid / New product launch]
Primary value delivered to customers: [e.g., "saves 12 hours/week per engineer", "processes 500K API events/day"]
ICP: [e.g., "Director of Engineering at 200-2,000 employee SaaS companies"]
ACV target: [e.g., $24,000]
Key usage signal(s): [e.g., API calls, documents processed, active users, GB stored, workflows run]

Deliver a complete UBP GTM Strategy including:

1. VALUE METRIC RECOMMENDATION: Identify the single best usage metric to price on, with rationale. Score 3-5 candidate metrics on: (a) alignment with customer value delivery, (b) ease of measurement, (c) natural expansion predictability, (d) competitive benchmarking. Recommend the winner with pricing tier design.

2. PACKAGING ARCHITECTURE: Design 3-4 pricing tiers (Free/Trial → Starter → Growth → Enterprise) with specific usage thresholds, feature gates, and upgrade triggers for each tier. Include the "land" motion and the natural expansion path.

3. EXPANSION REVENUE MOTION: Map the top 5 usage signals that trigger an upgrade conversation. For each signal: define the threshold, the outreach message, the channel, and the expected conversion rate.

4. SALES ENABLEMENT FOR UBP: Write a 1-page UBP sales guide for AEs covering: how to sell consumption instead of seats, how to handle "what if we use less than expected" objections, how to structure pilots and POCs under UBP, and how to forecast customer spend.

5. MARKETING CAMPAIGN: Design a 3-email "expansion trigger" sequence for when a customer hits 80% of their usage limit. Include subject lines, body copy frameworks, and CTA for each email.

6. SUCCESS METRICS: Define the 6 KPIs that prove your UBP GTM is working (e.g., expansion MRR %, usage-to-paid conversion rate, time-to-first-expansion).

Flag any assumptions you made and what data would sharpen the recommendations.

## Advanced Customizable Version

ROLE: You are a Senior Product Marketing Strategist with 15+ years of experience designing usage-based and consumption pricing GTM motions for B2B SaaS companies from Series B through IPO. You have built UBP programs at companies like Snowflake, Twilio, Datadog, and Stripe. You understand the full UBP lifecycle: value metric selection, packaging design, sales motion transformation, expansion revenue engineering, and the dashboard metrics that distinguish healthy UBP companies from those with leaky expansion funnels. You think in terms of Net Dollar Retention as the north star.

---

COMPANY CONTEXT:

Product & Market:
- Company Name: [Company Name]
- Product description: [2-3 sentences: what it does, for whom, core job-to-be-done]
- Industry/category: [e.g., Data Infrastructure / Security Operations / Developer Tools / RevOps]
- Company stage: [Series B / Series C / Growth / Public]
- ARR: [e.g., $22M]
- Target NRR: [e.g., 115% — what does good look like for your category?]
- Current NRR: [e.g., 108%]
- Average ACV: [e.g., $18,000]
- Sales cycle: [e.g., 45 days for SMB, 90 days for mid-market]
- GTM motion: [Sales-led / Product-led / Hybrid — and at what ACV threshold do motions change?]

Pricing Context:
- Current pricing model: [Per-seat / Flat-rate annual / Consumption / Hybrid — describe current structure]
- Reason for UBP transition or launch: [e.g., "Competitors are moving to consumption", "Our best customers expand 5x in year 2", "We want to lower the land cost to accelerate trials"]
- Pricing sensitivity: [e.g., "Buyers balk at >$500/mo to start", "Enterprise buyers want predictable annual contracts"]
- Current packaging (if any): [Describe tiers, limits, included features]

Customer Data:
- ICP primary: [Job title, company size, industry, pain point]
- ICP secondary: [If applicable]
- Average customer usage at 12 months vs. month 1: [e.g., "Customers use 8x more API calls by month 12 than month 1"]
- Top 3 jobs-to-be-done your product solves: [Be specific — "Process vendor invoices 3x faster", not "improve efficiency"]
- Churn profile: [Who churns? At what usage level? What's the save rate?]
- Expansion triggers observed: [What behavior or event precedes an upsell conversation in your best accounts?]

Competitive Context:
- Primary competitors: [Name + their pricing model — per-seat, flat-rate, consumption, freemium]
- Competitor pricing transparency: [e.g., "Competitor A publishes pricing, Competitor B is quote-only"]
- UBP advantages vs. competitors: [Where does your consumption model win?]
- UBP vulnerabilities: [Where does a buyer prefer predictable seat-based pricing?]

Technical Context:
- Usage data available in product: [What signals can you measure? e.g., "API call volume, active users per workspace, GB ingested, reports generated"]
- CRM/CDP stack: [e.g., Salesforce + HubSpot + Segment + Amplitude]
- Billing infrastructure: [e.g., Stripe Billing, Zuora, Chargebee — what's your current metering capability?]
- Customer-facing usage dashboard: [Yes/No — can customers see their own usage in real-time?]

---

ANALYSIS FRAMEWORK — Apply all five sections:

SECTION 1: VALUE METRIC SELECTION & VALIDATION

Apply the Value Metric Framework:
A great usage-based value metric must satisfy all four criteria:
(a) VALUE ALIGNMENT — Does the metric scale linearly with the value the customer receives? (not just activity)
(b) CUSTOMER PREDICTABILITY — Can the customer estimate their spend before committing? Low predictability = sales objections
(c) EXPANSION PREDICTABILITY — Does natural product usage drive organic growth in the metric? (Twilio's API calls, Snowflake's compute)
(d) COMPETITIVE DEFENSIBILITY — Does this metric create switching costs or a pricing moat vs. per-seat competitors?

For each candidate usage metric provided:
- Score each criterion 1-5
- Calculate composite score
- Identify the metric's Achilles heel (what makes buyers nervous about it)
- Identify the metric's expansion flywheel (what drives organic growth)

Recommend the PRIMARY value metric and a SECONDARY check metric (for customer health monitoring, not necessarily for pricing).

Provide a pricing sensitivity analysis:
- At what usage threshold does UBP become cheaper than a per-seat alternative for the buyer?
- At what threshold does it become more expensive? (design packages to avoid this cliff)
- What is the "land" price point that removes friction for trial/initial land?

SECTION 2: PACKAGING ARCHITECTURE

Design 4-tier packaging using the Land-Expand-Defend framework:

TIER 0 — FREE / TRIAL TIER (optional but recommended):
- Purpose: Remove evaluation friction, create product-qualified leads (PQLs)
- Usage limit: [Set at the minimum to demonstrate core value — not too generous]
- Feature gates: [What does free NOT include that creates upgrade urgency?]
- Time limit: [30/60 days, or usage-capped with no time limit?]
- PQL threshold: [Define the usage event or depth of engagement that signals sales-readiness]

TIER 1 — STARTER (land motion):
- Target customer: [Who starts here? What's their job title and company size?]
- Usage limit: [Set at 60-70% of average initial customer need — room to grow]
- Price: [Monthly or annual? What's the credit card threshold vs. sales-touch threshold?]
- Included features: [Core value — enough to create stickiness]
- Natural upgrade trigger: [What usage behavior makes this tier feel limiting?]

TIER 2 — GROWTH (primary expansion target):
- Usage limit: [3-5x Starter limit]
- Price: [Target price that justifies sales motion, typically $12K-$50K ACV for sales-led]
- Feature unlocks: [What does Growth include that Starter doesn't? Advanced analytics, team features, integrations, SSO]
- Time-to-Growth: [Target: 40% of Starter customers upgrade to Growth within 12 months]

TIER 3 — ENTERPRISE:
- Structure: [Usage-based with minimum annual commit, or negotiated contract with overages?]
- Minimum commit: [What floor protects revenue predictability for you?]
- Add-ons: [What enterprise-only capabilities command premium pricing?]
- Customer success investment: [At what ACV does a dedicated CSM become ROI-positive?]

For each tier, specify:
- The LAND motion (who buys, how they find you, sales vs. self-serve)
- The EXPAND trigger (what usage threshold or event triggers an upgrade conversation)
- The DEFEND play (what locks this customer into your tier and prevents downgrade)

SECTION 3: EXPANSION REVENUE MOTION DESIGN

Map the full Expansion Revenue Trigger System:

For each of the following trigger categories, define the specific threshold, detection method, response playbook, and expected conversion rate:

USAGE TRIGGERS (in-product signals):
- Approaching limit trigger: [Define % of tier limit, e.g., 80% consumed]
  → Response: automated in-app notification + CS alert + email sequence
  → Expected upgrade conversion: [e.g., 35% within 30 days of trigger]
  → Owner: [CS / Product / Growth Marketing]

- Limit breach trigger: [Customer exceeds tier limit]
  → Response: overage email (non-punitive framing) + upgrade CTA within 24 hours
  → Hard limit vs. soft limit policy: [Do you cut off or auto-upgrade?]

- Usage momentum trigger: [Usage growing >25% month-over-month for 2 consecutive months]
  → Response: expansion email + CS outreach + ROI recap
  → Expected upgrade conversion: [e.g., 42%]

- New use case trigger: [Customer activates feature/integration not used before]
  → Response: in-app upgrade prompt + email nurture about advanced capabilities

BUSINESS EVENT TRIGGERS (external signals):
- Funding announcement: [Target account raises capital — trigger outbound expansion play]
- Headcount growth: [Account adds >20% headcount in ICP department — suggests more usage]
- Champion job change: [Power user leaves — trigger executive re-engagement]
- Contract renewal (90 days out): [Trigger ROI recap + expansion proposal]

For each trigger: write the first-touch message (email subject line + 3-sentence body) that drives the expansion conversation without being pushy.

SECTION 4: SALES ENABLEMENT FOR UBP

Create a UBP Sales Playbook covering:

A. THE UBP PITCH: How to explain consumption pricing in 30 seconds without confusion
   - Avoid: "you pay for what you use" (too vague)
   - Use: "You start at $X/month, which covers [X units]. As your team [grows/processes more/builds more], the price grows proportionally — our best customers spend 3x their initial contract by year 2 because they're getting 5x the value."

B. OBJECTION HANDLING SCRIPTS:
   For each objection below, write a 3-5 sentence response:
   1. "We need predictable costs — can you give us a flat rate?"
   2. "What happens if we use way less than expected?"
   3. "Your competitor charges per seat — that's easier to budget"
   4. "Can you cap our maximum spend?"
   5. "How do we know what we'll use before we buy?"

C. PILOT / POC STRUCTURE under UBP:
   - Recommended pilot duration: [30/60 days]
   - Pilot pricing: [Free, discounted, or full price with refund guarantee?]
   - Success criteria to define at pilot start: [What usage threshold proves value?]
   - Conversion mechanism: [How does a successful pilot convert to paid without a new procurement cycle?]

D. DEAL STRUCTURING GUIDE:
   - Minimum annual commit strategy: [When to push for an annual commit vs. month-to-month]
   - Overage pricing: [How to price overages so they feel fair, not punitive]
   - Discounting policy: [What to discount — not price per unit, but commit size or prepaid credits]
   - Multi-year deal incentives: [Credit bundles, locked-in rates, added features]

SECTION 5: MARKETING CAMPAIGN ARCHITECTURE

Design the following UBP-specific campaign assets:

ASSET 1 — USAGE LIMIT APPROACH EMAIL SEQUENCE (3 emails):

Email 1 (at 80% limit):
Subject: [Write subject line — curiosity/value-led, not alarming]
Body: [3-4 sentences: acknowledge their usage growth as a positive signal, introduce upgrade option, soft CTA]
CTA: [e.g., "See your upgrade options" → pricing page]

Email 2 (at 90% limit, 3 days after Email 1):
Subject: [Write subject line — more urgent but not pressure-based]
Body: [Introduce the ROI of what they've achieved at current usage. Frame upgrade as protecting that momentum. Social proof from similar company.]
CTA: [e.g., "Book a 15-minute call to discuss options" → Calendly]

Email 3 (at 100% limit or day of limit breach):
Subject: [Write subject line — direct, action-oriented]
Body: [Clear status update. Two paths: upgrade now (self-serve link) or talk to us (AE CTA). No judgment framing.]
CTA: [Dual CTA: Upgrade Now (link) | Talk to Us (Calendly)]

ASSET 2 — NEW CUSTOMER EXPANSION ONBOARDING SEQUENCE (30/60/90 day):
Design a 3-milestone email sequence that plants the expansion seed during onboarding:
- Day 30: Celebrate early wins, introduce "power user features" in next tier
- Day 60: Share benchmark data ("customers like you typically expand usage by X% at this stage")
- Day 90: Trigger ROI report + expansion offer

ASSET 3 — PRICING PAGE MESSAGING FRAMEWORK:
Write the 3 headline copy options for the pricing page hero section that address the #1 UBP objection (unpredictability) while emphasizing the value of the consumption model.

---

OUTPUT STRUCTURE — Deliver in this exact format:

## UBP GTM Executive Summary
[6 bullet points: key recommendations, estimated NRR impact if executed, biggest risk, top priority action]

## Value Metric Analysis
[Table: Metric | Value Alignment | Predictability | Expansion Pull | Defensibility | Total Score | Achilles Heel | Expansion Flywheel]
[Recommendation with rationale]
[Pricing sensitivity crossover analysis]

## Packaging Architecture
[Full tier table: Tier | Target Customer | Usage Limit | Price | Feature Gates | Upgrade Trigger | Expected Time-to-Upgrade]
[Land/Expand/Defend summary per tier]

## Expansion Revenue Trigger Map
[Table: Trigger | Threshold | Detection Method | First-Touch Message | Owner | Expected Conversion Rate]
[All email subject lines and 3-sentence message bodies written out]

## UBP Sales Playbook
[Full objection handling scripts]
[Pilot structure guide]
[Deal structuring decision tree]

## Marketing Campaign Assets
[All 3 usage approach emails: subject line + full body]
[Onboarding expansion sequence: milestones + message framework]
[3 pricing page headline options]

## Implementation Roadmap
[30/60/90 day action plan: What to build, what to test, what to measure at each milestone]
[Owner for each action: Product / Sales / Marketing / CS / RevOps]

## UBP Health Dashboard Spec
[8 metrics to track weekly: metric name | formula | data source | healthy range | alert threshold]

---

CONSTRAINTS:
- Never recommend "pay as you go" without a minimum commit option — pure PAYG destroys revenue predictability for both parties
- Always design for the buyer who wants predictability: offer annual commits with overages as the default structure
- Every objection handling script must include a proof point (customer story, stat, or benchmark)
- All email copy must be written for a non-sales reader — use value language, not vendor language
- Flag any recommendation that requires >3 months of technical implementation — these need to be on a later-phase roadmap
- Distinguish between recommendations for PLG (self-serve, low ACV) vs. sales-led (high ACV, enterprise) motion

## Example Input/Output

**Input Example:**

Company: Axlera (B2B SaaS, data pipeline automation for engineering teams)
ARR: $14M | ACV: $21,000 | Current NRR: 109% | Target NRR: 125%
Current model: Per-seat (5 seats minimum, $350/seat/month)
Primary value: Reduces data pipeline build time from 3 weeks to 2 days
ICP: Senior Data Engineers and Data Platform teams at 150-1,500 employee SaaS/fintech companies
Usage signals available: pipeline runs/month, GB processed, connectors activated, active users
Competitors: Fivetran (per-connector pricing), dbt Cloud (per-seat), Airbyte (open source + cloud seats)
Current expansion behavior: 62% of customers add connectors within 6 months; 31% add users in year 1

**Output Example (abbreviated):**

**UBP GTM Executive Summary:**
- Pipeline runs/month is the strongest value metric — it scales with engineering team output and directly correlates with the "reduce pipeline build time" job-to-be-done
- Transitioning from per-seat to pipeline-run consumption is estimated to increase NRR from 109% to 122%+ within 18 months, based on current expansion behavior cohort data
- The land price drops from $1,750/month (5-seat minimum) to $299/month (Starter: 500 runs/month) — expected 3x increase in trial-to-paid conversion
- Biggest risk: AEs default to discounting run volume instead of structuring annual commits; requires sales training before launch
- Top priority (Day 1): Build in-app usage meter visible to customers — without it, expansion triggers are invisible and conversion rates drop 60%
- Recommended minimum annual commit: $9,600 at Starter tier to protect against month-to-month churn

**Value Metric Analysis (sample rows):**
| Metric | Value Align | Predictability | Expansion Pull | Defensibility | Score | Achilles Heel |
|--------|------------|----------------|----------------|---------------|-------|---------------|
| Pipeline runs/month | 5/5 | 4/5 | 5/5 | 4/5 | 18/20 | Buyers unsure of their run volume upfront |
| GB processed | 3/5 | 3/5 | 4/5 | 3/5 | 13/20 | Penalizes efficient customers; feels punitive |
| Active users | 2/5 | 5/5 | 2/5 | 2/5 | 11/20 | Reverts to per-seat — no expansion pull from usage |
| Connectors activated | 4/5 | 5/5 | 3/5 | 4/5 | 16/20 | Caps expansion once connector set is stable |

**Packaging (Starter tier example):**
Tier: Starter | Usage: 500 runs/month | Price: $299/month ($3,588 annual commit)
Upgrade Trigger: 80% of monthly runs consumed OR 3 consecutive months of >400 runs
Expected Time-to-Upgrade: 7 months median for customers with growing pipeline complexity
Land Motion: Self-serve signup → credit card → 14-day free trial at Growth limits
Expand Trigger: Automated email at 400 runs + in-app banner + CS alert if ACV > $10K

**Usage Approach Email 1 (at 80% limit):**
Subject: Your pipelines are running strong — here's what's next for Axlera
Body: "Your team has processed [X] pipeline runs this month — you're at 80% of your Starter plan. That's a strong signal your data infrastructure is scaling. When you're ready to remove the cap, our Growth plan unlocks unlimited runs plus advanced scheduling and team analytics. Take a look at what's included: [link]. No urgency — just wanted you to have the full picture."
CTA: Compare plans →

## Success Metrics

**Primary KPIs (measure monthly):**
- Net Dollar Retention (NRR): Target 120%+ for healthy UBP — segment by cohort and tier to identify which segment drives expansion
- Usage-to-Paid Conversion Rate: % of free/trial users who convert to paid — benchmark: 15-25% for PLG, 40-60% for sales-assisted
- Time-to-First-Expansion: Median days from initial purchase to first tier upgrade — target: ≤180 days
- Expansion MRR %: Expansion MRR ÷ Total MRR — healthy UBP companies see 25-40% of new MRR from expansion
- Overage Rate: % of customers exceeding their tier limit each month — target: 8-15% (too low means limits are too loose; too high means limits are too aggressive)
- Land ACV Efficiency: (Expansion ACV at 24 months) ÷ (Initial Land ACV) — target: 3x+

**Leading Indicators (weekly):**
- Usage growth rate per cohort: MoM % change in usage metric per tier
- 80% limit trigger volume: How many accounts hit the expansion trigger each week
- Expansion email open and click rates: Early signal for whether messaging is resonating

**Prompt Quality Check:**
A strong output will: (1) recommend a specific value metric with scored reasoning, (2) write complete email copy (not just frameworks), (3) distinguish PLG vs. sales-led motion recommendations, (4) include a NRR impact estimate with stated assumptions, and (5) flag any technical dependencies that require product/engineering work.

## Related Prompts

- [SaaS Pricing Strategy & Packaging Intelligence Engine](SaaS-Pricing-Strategy-&-Packaging-Intelligence-Engine.md)
- [Pricing Page Conversion Optimization & A/B Testing Intelligence Engine](Pricing-Page-Conversion-Optimization-&-A-B-Testing-Intelligence-Engine.md)
- [AI-Powered B2B Usage-Based CLV Modeling & Consumption Revenue Intelligence Engine](../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/AI-Powered-B2B-Usage-Based-CLV-Modeling-&-Consumption-Revenue-Intelligence-Engine.md)
- [Upsell Cross-Sell Revenue Intelligence Engine](../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/Upsell-Cross-Sell-Revenue-Intelligence-Engine.md)

## Integration Tips

**Salesforce:**
- Add custom Opportunity field: "UBP Tier at Close" (Starter / Growth / Enterprise) — enables cohort analysis on expansion by initial tier
- Build Salesforce report: "Accounts by Current Usage % of Tier Limit" — refreshes daily from billing system data via API integration
- Workflow: When account usage_pct > 0.80 in Salesforce, create a Task for the AE with subject "Expansion Opportunity" and link to pricing page — eliminates manual monitoring

**HubSpot:**
- Create Lifecycle Stage: "Usage-Qualified Account (UQA)" for customers hitting 75%+ of tier limit — triggers automated expansion workflow
- Smart List: Customers in Starter tier + usage growth rate > 20% MoM for 2 months → enroll in "Expansion Nurture" email workflow
- Use HubSpot Behavioral Events to log "pricing_page_visit_post_purchase" — customers who visit pricing after purchase are 3x more likely to expand within 30 days

**Stripe Billing / Chargebee / Zuora:**
- Set up usage-based billing webhooks to push consumption data to Salesforce and HubSpot in real-time — Zapier or Workato can bridge if no native integration
- Configure Stripe's "usage_record" API to emit events when customers cross 50%, 80%, and 100% of their plan limit — these events trigger your expansion sequences automatically
- Chargebee users: Enable "Usage & Revenue Reporting" module → connect to Looker Studio for the UBP health dashboard

**Amplitude / Mixpanel / Segment:**
- Define "Power User Event" in Amplitude: customer performs the core value action (e.g., pipeline run) more than N times in a session — auto-surface to CS in Gainsight
- Build Segment Persona: "Expansion-Ready Customer" = customers in Starter tier + usage_metric > 400/month for 2+ months + has_team_invite = false (hasn't unlocked team features yet)
- Mixpanel Funnel: Free Trial → First Value Event → 50% Limit → 80% Limit → Upgrade — this funnel identifies where your UBP conversion is leaking

**Notion / Google Sheets:**
- UBP Weekly Dashboard (Google Sheets): Pull Stripe usage data via API → calculate tier utilization by cohort → visualize in Looker Studio → share with CS and Sales leads every Monday
- Notion pricing documentation: Create a "UBP Pricing Calculator" page (embed a Google Sheet with usage estimator) — link from pricing page so buyers can self-estimate spend before talking to sales

## Troubleshooting

**Problem: "Our sales team keeps discounting the run volume instead of the price, effectively giving customers more usage for the same money — our expansion economics are breaking."**
Solution: Lock usage limits in Salesforce as non-negotiable fields (requires VP Sales approval to override). Instead, train AEs to discount by offering prepaid credit bundles: "I can offer you $10,000 in prepaid runs at a 15% discount versus pay-as-you-go overages" — this increases ACV while preserving the usage expansion floor. Discounting credit bundles (not tier limits) protects your NRR model.

**Problem: "Customers are angry about surprise overage charges — it's damaging retention even though we're technically right about their usage."**
Solution: Switch from hard-limit billing to "soft limit + 7-day grace period" architecture: when a customer exceeds their tier limit, grant 7 days of overage access at no charge while triggering an upgrade conversation. Customers who feel surprised and penalized churn; customers who feel informed and supported expand. Add a customer-facing real-time usage meter in-product — this single change reduces overage-related support tickets by 40-60% at most UBP companies.

**Problem: "We can't get accurate usage data into our CRM — the expansion trigger emails are firing too late or on wrong accounts."**
Solution: This is a data infrastructure problem, not a marketing problem. Prioritize three connections: (1) billing system → Salesforce sync via Zapier/Workato (daily refresh minimum, real-time preferred), (2) product analytics tool → HubSpot via Segment identify() calls for key usage events, (3) build a "usage health score" field in Salesforce that calculates tier utilization % automatically. Until this is live, run a weekly manual report: export usage data from billing system → VLOOKUP against Salesforce accounts → flag 80%+ accounts for CS review. Imperfect but better than no trigger system.

## Version History

- v1.0: Initial creation (auto-generated)
