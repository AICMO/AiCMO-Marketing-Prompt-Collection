# AI-Powered B2B Website CRO Experimentation Program Design & Test Velocity Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** cro, ab-testing, experimentation, website-optimization, conversion-rate, b2b, behavioral-analytics, statistical-significance, pipeline-conversion, growth

## Overview
This engine builds a fully autonomous, AI-orchestrated Conversion Rate Optimization (CRO) experimentation program for B2B websites — from test ideation and prioritization through statistical analysis, winner rollout, and compounding learning loops. Use it when your demo request conversion rate is stuck below industry benchmarks (1.5–3% for B2B SaaS), when you're running fewer than 2 experiments per month, or when you need to turn qualitative session data (Hotjar, FullStory) into a systematic, revenue-attributed test backlog.

## Quick Copy-Paste Version

You are a senior B2B CRO strategist and experimentation program lead with deep expertise in behavioral analytics, A/B test design, and converting B2B website visitors into qualified pipeline. You specialize in companies selling to enterprise and mid-market buyers with ACV above $20K and sales cycles of 30–180 days.

My B2B website CRO context:
- Product/industry: [e.g., procurement automation SaaS for $100M+ enterprises]
- Primary buyer personas: [e.g., VP Procurement, CPO, Head of Procurement Operations]
- Monthly website sessions: [e.g., 28,000 sessions/month]
- Current demo request conversion rate: [e.g., 0.9%]
- Analytics stack: [e.g., GA4 + Hotjar + HubSpot]
- A/B testing tool: [e.g., VWO / Optimizely / Convert / none yet]
- Biggest CRO problem: [e.g., "Pricing page has 2,100 views/month but only 23 demo clicks — people read it and leave"]

Build a complete CRO experimentation program with:

1. CONVERSION AUDIT: Diagnose my top 3 website conversion killers based on my context. For each, identify the behavioral evidence pattern that confirms the problem, the specific GA4 + Hotjar event sequence to validate it, and the expected revenue impact of fixing it (calculate using: sessions × current CVR × ACV × uplift estimate).

2. TEST BACKLOG CREATION: Generate 8 prioritized A/B test ideas using the ICE Score framework (Impact 1-10, Confidence 1-10, Ease 1-10). For each test: hypothesis statement in the format "Because [behavioral evidence], we believe changing [element] to [variation] will [increase/decrease] [metric] by [X%] for [persona segment] resulting in [pipeline impact]," plus the minimum sample size required for 95% confidence.

3. STATISTICAL RIGOR: Provide the exact formulas and decision rules for: (a) calculating minimum detectable effect at 80% statistical power, (b) determining when to stop a test early (peeking rule), (c) segmenting results by ICP vs. non-ICP traffic (since ICP converts at 3-5x non-ICP for B2B), and (d) how to handle tests where mobile and desktop show opposite results.

4. HEATMAP & SESSION RECORDING ANALYSIS: Give me a 10-point session recording analysis protocol for diagnosing demo form abandonment — what to look for in Hotjar/FullStory recordings, the specific behavioral signals that predict form abandonment before it happens, and how to calculate the "field-level drop rate" from Hotjar Form Analytics.

5. WINNER IMPLEMENTATION CADENCE: Design a 12-week CRO sprint program: week-by-week test launch schedule, decision criteria for rolling out winners (include minimum confidence threshold, minimum segment size, and ICP-segment confirmation requirement), and how to build a "Wins Compounding Model" that projects cumulative pipeline impact of a program running 2 tests/month at 15% average uplift for 12 months.

6. REPORTING TEMPLATE: Create a monthly CRO report structure for presenting to a CMO — include the 5 metrics that matter (not vanity stats), how to frame experiment ROI in pipeline terms, and the one-slide "CRO Flywheel" visual to show compounding returns.

Output everything with specific numbers, formulas, and copy-paste-ready frameworks. Assume I have GA4, Hotjar, and basic HubSpot/Salesforce access.

## Advanced Customizable Version

ROLE: You are a Principal B2B CRO Strategist and Experimentation Program Architect with 14+ years of experience designing and running conversion optimization programs at B2B SaaS companies ranging from Series B startups to publicly traded enterprises. You are an expert in behavioral analytics interpretation (Hotjar, FullStory, Microsoft Clarity, Heap), A/B testing platform configuration (VWO, Optimizely, Convert, AB Tasty), GA4 advanced segmentation, and the unique psychology of B2B enterprise buyers who evaluate vendors over 60–180 day cycles. You understand that B2B CRO is fundamentally different from B2C: the buyer is often a buying committee, not an individual; micro-conversions (content downloads, tool usage, return visits) predict pipeline better than single-session metrics; and a 0.5% conversion rate lift on a $50K ACV product is worth more than a 5% lift on a $50 DTC product.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Product Category: [e.g., enterprise procurement automation SaaS / AI-powered accounts payable / B2B spend management platform]
- Annual Recurring Revenue (ARR): [e.g., $12M ARR growing 65% YoY]
- Average Contract Value (ACV): [e.g., $42,000 — range: $18K SMB to $180K enterprise]
- Primary Buyer Personas: [e.g., VP Procurement (economic buyer), Procurement Manager (champion), IT Security (influencer), CFO (approver for deals >$100K)]
- Sales Cycle: [e.g., 45–60 days mid-market; 90–150 days enterprise]
- Monthly Website Sessions: [e.g., 31,000 sessions — 68% organic, 22% paid, 10% direct/branded]
- ICP Traffic Estimate: [e.g., approximately 35% of traffic matches ICP (companies $100M+ revenue in manufacturing, logistics, or professional services)]
- Current Primary Conversion Rate (demo request / total sessions): [e.g., 1.1%]
- Current Secondary Conversion Rates: [e.g., content download: 3.2% | free ROI calculator: 0.8% | pricing page CTA click: 4.1%]
- A/B Testing Platform: [VWO / Optimizely / Convert / AB Tasty / Google Analytics 4 A/B (via Experiments) / not yet implemented]
- Analytics & Behavioral Tools: [e.g., GA4 standard + Hotjar Business + HubSpot Marketing Pro]
- CRM: [HubSpot / Salesforce — specify edition and if CRM is connected to analytics]
- Top 3 Highest-Traffic Pages (outside homepage): [e.g., /pricing (4,200 sessions/month), /integrations (2,800 sessions/month), /vs-competitor (1,900 sessions/month)]
- Known Conversion Problem: [e.g., "Pricing page has 4,200 visits/month but only 2.3% CTA click rate; Hotjar shows 78% of visitors scroll below the fold but 62% exit without clicking any CTA"]

PROGRAM DESIGN OBJECTIVES:
- Primary Goal: [e.g., increase demo request rate from 1.1% to 1.8% within 6 months, generating 140+ additional demos/month]
- Secondary Goal: [e.g., improve ICP segment conversion rate specifically — ICP demos convert to pipeline at 3x non-ICP]
- Experiment Velocity Target: [e.g., run 3 concurrent A/B tests at all times; make 1 data-driven decision per week]
- Pipeline Attribution Method: [e.g., first-touch / multi-touch / last-touch — specify what your CRM currently uses]
- ICP Identification Method: [e.g., Clearbit Reveal IP-to-company enrichment / 6sense / manual firmographic filter in GA4]

---

DELIVERABLE 1 — CONVERSION BASELINE & OPPORTUNITY SIZING

Build a complete conversion audit with:

A) FUNNEL STAGE CONVERSION MAP: Map the 6-stage B2B website conversion funnel — Traffic Entry → Homepage Engagement → Category/Pain Education → Solution Evaluation → Vendor Comparison/Pricing → Conversion Action — with current conversion rates at each stage based on my data. For each stage transition, calculate the "Revenue-Per-Visitor" metric (pipeline generated per 1,000 unique visitors who reach that stage). Identify the single biggest leakage point by calculating "Pipeline Lost Per Month" at each stage drop-off using: (visitors who reached stage × stage-to-demo CVR if zero leakage at this point × ACV × historical demo-to-close rate of 22%).

B) BENCHMARK COMPARISON: Provide industry benchmark conversion rates for each funnel stage for a B2B SaaS company with my ACV range and sales cycle. Flag where I am below, at, or above benchmark. For below-benchmark stages, identify the top 3 structural causes based on behavioral patterns common in this product category.

C) OPPORTUNITY SIZING: Calculate the incremental ARR impact of achieving benchmark conversion rates at my top 3 leakage points. Present as: "Closing the [stage] gap from [X%] to benchmark [Y%] would generate [Z additional demos/month] × [22% close rate] × [$42K ACV] = [$X incremental ARR/year]."

---

DELIVERABLE 2 — TEST BACKLOG ARCHITECTURE

Generate a prioritized experiment backlog of 12 A/B test ideas using the RICE Score framework (Reach × Impact × Confidence ÷ Effort). For each test:

A) HYPOTHESIS STATEMENT: Follow the format: "Because [specific behavioral evidence from GA4/Hotjar, e.g., '71% of pricing page visitors exit without clicking the CTA, and session recordings show they scroll past the CTA block without pausing'], we believe changing [specific element, e.g., 'the CTA from "Request a Demo" to "See [Product] in 15 Minutes — Book Now"] will increase [metric, e.g., pricing page CTA click rate] by [X%, e.g., 20–35%] for [segment, e.g., returning visitors who have viewed 2+ pages], resulting in [pipeline impact, e.g., 18 additional demos/month worth $756K ARR]."

B) STATISTICAL REQUIREMENTS: For each test, calculate:
- Required sample size per variation (use 95% confidence, 80% power, your current CVR as baseline, and your expected MDE)
- Estimated days to reach significance at my current traffic volume
- Whether the test is ICP-segment-valid (minimum 500 ICP-qualified sessions required to segment results)

C) TEST COMPLEXITY RATING: Classify each test as (1) No-code change (copy/CTA only — developer not required), (2) Low-code change (CSS/layout — front-end resource 1–2 hours), or (3) Development change (logic, form, or backend — requires sprint inclusion). Prioritize no-code and low-code tests first for velocity.

D) SUCCESS METRICS: Define for each test: primary metric (conversion rate change), secondary metrics (pipeline-connected: demo show rate, SQLs generated from variation), and guardrail metrics (bounce rate, session duration — must not deteriorate significantly).

---

DELIVERABLE 3 — BEHAVIORAL DATA ANALYSIS PROTOCOL

Build a standard operating procedure (SOP) for extracting CRO insights from behavioral tools:

A) HOTJAR SESSION RECORDING ANALYSIS PROTOCOL:
Provide a 12-point structured observation checklist for reviewing session recordings of users who visited the demo request form but did not convert. For each observation point, specify: what to look for, what it indicates about friction or intent, and the A/B test hypothesis it generates. Include: rage click patterns, scroll depth on form page, time-on-page vs. conversion correlation, field-by-field interaction rate, device type differences, and referral source correlation.

B) HEATMAP INTERPRETATION FRAMEWORK:
Define how to interpret click maps, scroll maps, and move maps specifically for B2B pages. Provide the "CRO Signal Hierarchy" — ranking 8 behavioral signals from highest to lowest predictive value for conversion intent. Include the specific thresholds that signal a CTA placement problem (e.g., "if fewer than 12% of scroll map reach the CTA position, it is below the effective fold for this audience").

C) GA4 FUNNEL EXPLORATION CONFIGURATION:
Provide step-by-step instructions for building 3 GA4 Funnel Explorations: (1) Demo request funnel from first-session-start to form-submission, (2) Content engagement funnel from blog-entry to form-submission across multiple sessions (using User ID if available, or session_start as proxy), and (3) ICP vs. non-ICP conversion funnel comparison (using GA4 audiences fed by Clearbit Reveal or similar enrichment). Include the exact GA4 event names to define at each step.

D) FORM ANALYTICS DEEP-DIVE:
Using Hotjar Form Analytics, define how to calculate: (1) Field-level drop rate = (users who interacted with field N but did not reach field N+1) ÷ total form starters, (2) Return rate = users who left the form and returned to complete it (proxy for high intent), (3) Correction rate per field (proxy for confusing or friction-heavy field labels). Provide decision rules: at what drop rate thresholds should a field be removed, simplified, or moved later in the form sequence.

---

DELIVERABLE 4 — STATISTICAL RIGOR & DECISION FRAMEWORK

Provide the complete statistical framework for running experiments with integrity:

A) SAMPLE SIZE & POWER CALCULATION:
Provide the formula for minimum sample size per variation: n = (Z_α/2 + Z_β)² × (p₁(1-p₁) + p₂(1-p₂)) ÷ (p₁ - p₂)² where Z_α/2 = 1.96 (95% confidence) and Z_β = 0.84 (80% power). Calculate the required sample size for my baseline CVR (1.1%) at 3 MDE levels: 15% relative lift, 25% relative lift, and 40% relative lift. Show days-to-significance at my current ICP traffic volume.

B) ANTI-PEEKING PROTOCOL:
Explain the "peeking problem" (inflated false positive rate from checking results before sample size is reached) and provide 3 guardrails: (1) Bayesian credible interval approach for early stopping, (2) Sequential testing / alpha spending method for valid early analysis, (3) Fixed-horizon rule with a physical calendar commitment. Specify which guardrail is appropriate for each of my traffic volume levels (low-traffic pages under 200 conversions/month vs. high-traffic pages over 1,000 conversions/month).

C) SEGMENTATION RULES:
Define when and how to segment test results by: ICP vs. non-ICP, new vs. returning visitor, traffic source (organic vs. paid vs. direct), device type, and geographic region. Provide the minimum segment size requirement for each sub-group result to be actionable (suggest 200+ conversions in the winning segment variation). Explain what to do when the overall result is neutral but the ICP segment shows strong positive lift.

D) MULTIPLE TESTING CORRECTION:
When running 3 concurrent tests with shared traffic pools, apply Bonferroni correction (α_corrected = 0.05 ÷ 3 = 0.0167) or explain why sequential testing eliminates this requirement. Provide a decision tree for when to use Bonferroni vs. sequential testing based on test independence.

---

DELIVERABLE 5 — EXPERIMENT VELOCITY OPERATING SYSTEM

Design the operational infrastructure for running 3 concurrent tests continuously:

A) 12-WEEK CRO SPRINT CALENDAR:
Build a week-by-week schedule for a 12-week CRO program launching with 0 active tests. Include: Week 1-2 (audit and backlog creation), Week 3 (Test 1 launch — no-code, highest RICE score), Week 4 (Test 2 launch), Week 5-6 (Test 3 launch + first decision on Test 1 if significance reached), and so on. Define the standard 2-week decision cycle for no-code tests and 3-week cycle for low-code tests.

B) WINNER ROLLOUT PROTOCOL:
Define the 5-step winner rollout checklist: (1) Confirm 95% statistical significance with minimum 400 conversions in winning variation, (2) Validate ICP-segment directional alignment (winning variation must not hurt ICP CVR even if overall uplift is positive), (3) Confirm guardrail metrics are within ±5% of control, (4) Deploy winner as permanent control within 48 hours of decision, (5) Document hypothesis confirmation and add to "Wins Library" with revenue attribution.

C) COMPOUNDING WINS MODEL:
Build a 12-month compounding projection model. Assumptions: 2 tests/month launched, 35% of tests produce a winner, average 20% relative CVR lift per winning test, winners are compounded (each winner becomes the new baseline for the next test). Calculate: starting CVR (1.1%) after 12 months of compound improvement = [formula]. Calculate total additional demos generated and ARR impact at $42K ACV. Present as a table showing monthly CVR, monthly demos, and cumulative additional ARR.

D) WINS LIBRARY FORMAT:
Provide a template for the CRO Wins Library — a shared Notion or Google Sheets document that captures every experiment result. Include fields: Test ID, Page, Hypothesis, Control Screenshot URL, Variation Screenshot URL, Statistical Result (significant/not), Relative Lift %, Absolute Lift Pts, Additional Demos/Month, Annualized ARR Impact, Date Rolled Out, Lesson Learned (why did this work). This library becomes training data for the next round of AI-generated hypotheses.

---

DELIVERABLE 6 — CMO & STAKEHOLDER REPORTING

Design the CRO program reporting cadence:

A) MONTHLY CRO DASHBOARD (5 PIPELINE-CONNECTED METRICS):
1. Demo Request Conversion Rate (total sessions → demo form submitted) — trend vs. last 3 months
2. ICP-Segment CVR — same metric, ICP traffic only
3. Experiment Velocity — tests launched and decisions made this month
4. Cumulative ARR Impact from Rolled-Out Winners — calculated as: (lift in demos from winning tests) × ACV × close rate × months active
5. Top Experiment in Progress — current test, hypothesis, days to significance

B) CRO FLYWHEEL ONE-PAGER:
Write the narrative and visual description for a "CRO Flywheel" slide for CMO/board use. The flywheel shows: Behavioral Data → Hypothesis Generation → Prioritized Backlog → Experiment Launch → Statistical Winner → Rollout & Compound → More Data for Better Hypotheses → repeat. Each stage should include the tool, the AI role, and the time investment. Include 3 key proof points: starting CVR, current CVR, and projected 12-month CVR.

C) QUARTERLY BUSINESS REVIEW (QBR) SECTION:
Provide the template for the CRO section of the quarterly marketing review. Include: experiments run (table), decisions made (table), ARR attributed to CRO program, biggest learning of the quarter, next quarter's focus areas, and budget required to scale test velocity (engineering hours, tool costs, analyst time).

---

OUTPUT FORMAT:
- All formulas must be in copy-paste-ready spreadsheet format (Google Sheets / Excel syntax)
- All sample sizes and revenue calculations must use my actual numbers, not placeholders
- Provide decision trees as bulleted "If [condition] → Then [action]" structures
- All test hypotheses must be specific to my product category (procurement automation), not generic
- Include tool-specific configuration steps for GA4, Hotjar, and VWO/Optimizely where referenced
- Every ROI calculation must trace back to pipeline: demos × close rate × ACV, not engagement metrics

## Example Input/Output

**Input Example:**
- Company: NovaCraft AI (procurement automation SaaS, $100M+ enterprise buyers)
- ACV: $42,000
- Monthly sessions: 31,000 (35% ICP-qualified)
- Current demo CVR: 1.1% (341 demos/month)
- Pricing page: 4,200 visits/month, 2.3% CTA click rate
- Tools: GA4 standard, Hotjar Business, HubSpot Marketing Pro, VWO

**Output Example (excerpt from Test Backlog):**

**Test #1 — RICE Score: 312 (Highest Priority)**
- Page: Pricing page (/pricing)
- Hypothesis: "Because Hotjar heatmaps show 71% of pricing page visitors scroll past the CTA block without pausing (0.8 second average dwell on CTA zone), and session recordings reveal that 44% of exiting visitors pause on the pricing tier comparison table before leaving, we believe adding a contextual CTA below the pricing tier table that reads 'See how [Tier Name] maps to your procurement volume — Book a 15-min walkthrough' will increase pricing page CTA click rate from 2.3% to 3.4% (48% relative lift) for returning visitors who have viewed 2+ pages, resulting in 22 additional demos/month worth $924K ARR."
- Required sample: 1,847 per variation (currently 4,200 pricing sessions/month → reach significance in 14 days)
- Complexity: No-code (CTA copy + placement only)
- Primary metric: Pricing page CTA click rate
- Secondary metrics: Demo requests attributed to /pricing (HubSpot), SQL rate from this cohort
- Guardrail: Bounce rate must not increase >5% from current 38%

**Test #2 — RICE Score: 248**
- Page: Demo request form (/demo)
- Hypothesis: "Because Hotjar Form Analytics shows a 67% drop rate at field #4 ('Company Size'), with a 2.1× higher correction rate than other fields, indicating buyers are uncomfortable disclosing company size before understanding our qualification criteria, we believe replacing the 'Company Size' dropdown with 'Annual Purchase Volume' (more relevant to their role) and moving it to position #6 in the form sequence will reduce form abandonment rate from 58% to 44% for first-time form starters, generating 34 additional form completions/month worth $1.4M ARR."
- Required sample: 2,200 form starters per variation (currently 680 form starters/month → reach significance in 97 days — flag as LONG TIMELINE, run concurrent with faster tests)

**Compounding Returns Projection:**

| Month | CVR | Monthly Demos | Cumulative ARR Impact |
|-------|-----|---------------|-----------------------|
| 0 (baseline) | 1.10% | 341 | $0 |
| 3 | 1.32% | 409 | $668K |
| 6 | 1.58% | 490 | $1.8M |
| 9 | 1.90% | 589 | $3.4M |
| 12 | 2.28% | 707 | $5.7M |

*Assumptions: 2 tests/month, 35% win rate, 20% average relative lift per winner, 22% demo-to-close rate, $42K ACV*

## Success Metrics

- **Experiment velocity**: ≥2 experiments launched per month within 30 days of program start
- **Win rate**: ≥25% of experiments produce a statistically significant winner (industry average is 20–35%)
- **Primary conversion rate trend**: Measurable upward trend in demo CVR within 90 days
- **ICP-segment CVR**: ICP conversion rate improving faster than blended rate (indicates quality improvement, not just volume)
- **Pipeline attribution**: CRO program attributed to ≥15% of incremental demos within 6 months
- **Statistical hygiene**: 100% of decisions made at 95% confidence with pre-specified sample sizes (zero peeking decisions)
- **Wins Library**: ≥12 documented experiments with revenue attribution within 12 months

## Related Prompts

- [AI-Powered B2B Website Analytics, Digital Experience & Pipeline Revenue Intelligence Engine](./AI-Powered-B2B-Website-Analytics-Digital-Experience-&-Pipeline-Revenue-Intelligence-Engine.md)
- [Pipeline Stage Conversion Optimization & Revenue Leak Detection Engine](../Funnel-Conversion-&-Pipeline-Velocity/Pipeline-Stage-Conversion-Optimization-&-Revenue-Leak-Detection-Engine.md)
- [AI-Powered B2B Marketing Experimentation Program & Compound Growth Intelligence Engine](../Marketing-Experimentation-&-Revenue-Intelligence/AI-Powered-B2B-Marketing-Experimentation-Program-&-Compound-Growth-Intelligence-Engine.md)
- [AI-Powered B2B Conversion Rate Benchmarking & Funnel Stage Optimization Intelligence Engine](../Funnel-Conversion-&-Pipeline-Velocity/AI-Powered-B2B-Conversion-Rate-Benchmarking-&-Funnel-Stage-Optimization-Intelligence-Engine.md)

## Integration Tips

- **VWO / Convert / AB Tasty**: Connect your A/B testing platform to HubSpot/Salesforce via native integration or Zapier — tag each lead with the experiment variation they converted from so you can measure pipeline-to-close rate by variation, not just conversion rate
- **GA4 Custom Dimensions**: Create a custom dimension "Experiment_Variation" (session-scoped) populated from your testing platform's JS snippet — enables segmenting all GA4 reports by test variation and correlating with downstream pipeline events
- **Hotjar → Slack Integration**: Use Zapier to trigger a Slack alert when a session recording from a target account (IP-matched via Clearbit/6sense) shows a rage click on the demo CTA or a form abandonment — creates real-time CRO signal from high-value accounts
- **HubSpot / Salesforce Pipeline Attribution**: Create a custom contact/deal property "First CRO Test Variation" to track which experiment cohort each deal originated from — enables quarterly CRO ARR attribution reports
- **Notion Wins Library**: Build your CRO Wins Library in Notion with database views sorted by ARR impact — link each entry to the Loom recording of the test decision call and the GA4 exploration that confirmed significance
- **Google Looker Studio**: Connect GA4 + HubSpot data to build a real-time CRO dashboard with pipeline-connected metrics; use the GA4 Looker Studio connector with the Session Default Channel Group and Landing Page dimensions to filter by experiment traffic

## Troubleshooting

**Problem: Tests are taking 45–90 days to reach statistical significance because traffic volume is too low.**
Solution: Focus your first 3 months exclusively on your 2 highest-traffic pages (typically homepage and pricing page). Raise your MDE from 15% to 25% relative — this reduces required sample size by ~55%. Use Bayesian testing (available in VWO and Convert) which provides valid decisions at smaller samples without the false positive inflation of frequentist peeking. For pages under 200 conversions/month, consider multi-armed bandit testing (traffic automatically routes to the better performer) rather than fixed-horizon A/B testing.

**Problem: Tests show positive results overall but the ICP segment (target accounts) shows neutral or negative results.**
Solution: Stop the test and roll back — an overall positive result that hurts your ICP segment is a net negative for revenue (ICP demos are worth 3–5× non-ICP demos). Re-analyze the session recordings specifically from ICP visitors to identify what is causing divergence. Common cause: B2C-style urgency/scarcity copy works for non-ICP SMB buyers but creates credibility damage with enterprise buyers. Run a new test variant specifically designed for enterprise buyer psychology.

**Problem: The sales team is skeptical that CRO-generated demos are lower quality than outbound demos.**
Solution: This is a critical alignment issue. Pull a cohort analysis in Salesforce/HubSpot comparing demo-to-SQL rate, SQL-to-close rate, and ACV for demos originating from CRO-optimized variations vs. your control period baseline. Present the data in a joint marketing-sales QBR. If CRO demos genuinely show lower quality, add a qualifying question to the form ("What is your annual purchase volume?") that filters out non-ICP submissions — a small CVR decrease in exchange for a large SQL rate increase is a net win.

## Version History
- v1.0: Initial creation (auto-generated)
