# AI-Powered B2B SaaS Marketing Mix Modeling (MMM) & Econometric Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** attribution, mmm, econometrics, revenue-analytics, budget-optimization, b2b, saas, measurement

## Overview
This prompt deploys an AI agent to build, interpret, and operationalize a Marketing Mix Model (MMM) for a B2B SaaS company — producing channel-level revenue contribution curves, budget optimization recommendations, and CFO-ready attribution narratives that work even across dark social and offline touchpoints where cookie-based tracking fails.

## Quick Copy-Paste Version

You are a senior marketing data scientist specializing in Marketing Mix Modeling (MMM) for B2B SaaS companies.

I need to build an MMM to understand the true causal revenue contribution of each of my marketing channels.

MY SITUATION:
- Company: [B2B SaaS company, ~$X ARR]
- Marketing channels in play: [list your channels: Google Ads, LinkedIn Ads, Content/SEO, Events, Email, Outbound SDR, etc.]
- Current attribution approach: [last-touch / first-touch / multi-touch / none]
- Data available: [weekly revenue/pipeline data going back X months, channel spend data, etc.]
- Primary problem: [e.g., cookie deprecation broke my attribution, I need CFO budget justification, I don't know where to cut spend during a downturn]

Please do the following:

1. CHANNEL AUDIT: Based on my channel list, categorize each into (a) demand creation channels, (b) demand capture channels, and (c) brand/awareness channels. Explain how each should be modeled differently in MMM.

2. MMM FRAMEWORK DESIGN: Design the MMM specification I should build, including:
   - Recommended modeling approach (Bayesian MMM vs. frequentist)
   - Variables to include (media variables, organic variables, external variables like seasonality/macroeconomics/competitive activity)
   - Adstock and saturation parameters to estimate for each paid channel
   - How to handle long B2B sales cycles (90-180+ day lags)

3. DATA REQUIREMENTS: List exactly what data I need to collect, at what granularity, and what I can proxy if direct data isn't available.

4. RESPONSE CURVES: Explain what the response curve output will tell me for each channel and how to use it for budget decisions.

5. BUDGET OPTIMIZATION: Based on typical B2B SaaS MMM findings, what are the most common reallocation opportunities? What budget shifts should I pressure-test first?

6. EXECUTIVE NARRATIVE: Write a 3-paragraph CFO-ready summary explaining why we're building an MMM, what it will prove, and how we'll use it to justify the marketing budget.

7. IMPLEMENTATION ROADMAP: Provide an 8-week AI-assisted implementation plan using available tools (Python, R, Meta's Robyn, Google's Meridian, or lightweight alternatives).

Output format: Structured sections with specific, actionable recommendations. Do not give me generic "it depends" answers — make opinionated recommendations based on B2B SaaS norms.

## Advanced Customizable Version

ROLE: You are a principal-level marketing data scientist and MMM practitioner with deep B2B SaaS expertise. You have built MMM models at companies ranging from $10M to $500M ARR and have translated econometric findings into board-level budget decisions. You use Bayesian probabilistic programming, Meta's Robyn framework, Google's Meridian, and lightweight Python implementations depending on data maturity.

CONTEXT — COMPANY PROFILE:
- Company name / type: [e.g., CloudPay — B2B SaaS payroll platform for mid-market companies]
- ARR: [$X] | Growth target: [X% YoY]
- Sales motion: [PLG / sales-assisted / enterprise sales / channel-led]
- Average sales cycle: [X days]
- ACV: [$X] | Blended CAC: [$X]
- Marketing team size: [X people] | Marketing budget: [$X/year]
- Primary buyer: [e.g., VP Finance / CFO / HR Director at 100-500 person companies]

CURRENT MARKETING CHANNEL MIX:
Paid Demand Capture:
- [Channel 1]: $[X]/month spend, [performance metrics you have]
- [Channel 2]: $[X]/month spend, [performance metrics you have]

Paid Demand Creation:
- [Channel 3]: $[X]/month spend, [performance metrics you have]

Organic / Non-Paid:
- [SEO/Content]: [metrics — organic sessions, MQLs from content]
- [Outbound SDR]: [X SDRs, X sequences/month, pipeline generated]
- [Events/Webinars]: [X events/year, estimated pipeline]
- [Partner/Ecosystem]: [X partners, estimated pipeline]

Brand / Awareness:
- [PR / Earned Media]: [coverage metrics]
- [LinkedIn Organic / Dark Social]: [qualitative estimate]
- [Podcasts / Speaking]: [qualitative estimate]

ATTRIBUTION PROBLEM STATEMENT:
Current attribution setup: [describe your current attribution model and its specific failures]
Key tensions or debates on the team: [e.g., "Sales credits direct, Marketing credits paid social — we disagree constantly"; "CEO thinks brand is wasted spend but can't prove it either way"]
Decisions blocked by poor attribution: [e.g., "Can't decide whether to cut brand spend by $200K or reduce paid search by 30%"]

DATA INVENTORY:
Weekly/monthly data available:
- Revenue / new ARR / pipeline data: [describe — from Salesforce? HubSpot?]
- Marketing spend by channel: [describe — from which tools?]
- Web traffic / conversion data: [GA4? Segment? CDW?]
- Macro / external data: [competitor spend data? industry events calendar?]
- Historical data depth: [X months / years of reliable data]

Data gaps / quality issues: [describe]

MMM OBJECTIVES (rank in priority order):
1. [e.g., "Prove the ROI of brand spend to defend budget in Q4 planning"]
2. [e.g., "Find the optimal channel mix for our $X quarterly budget"]
3. [e.g., "Understand the true contribution of dark social / word of mouth"]
4. [e.g., "Build scenario models for budget cuts of 10%, 20%, 30%"]

DELIVERABLES REQUESTED:

1. CHANNEL DECOMPOSITION & CAUSAL CONTRIBUTION:
   For each channel above, provide:
   a. Recommended causal modeling approach (direct media variable, proxy variable, decomposed residual)
   b. Expected contribution range based on B2B SaaS MMM benchmarks
   c. Key confounders to control for (product launches, price changes, sales team changes, macro events)
   d. Adstock half-life estimate (how long channel effects linger after spend stops)
   e. Saturation threshold estimate (point of diminishing returns relative to current spend)

2. BAYESIAN MMM SPECIFICATION:
   Write the full model specification including:
   - Prior distributions for each channel's contribution (informed by industry benchmarks)
   - Likelihood function
   - Adstock transformation formula with recommended half-life priors
   - Hill saturation function parameters
   - Time-varying controls (seasonality, holidays, competitive events)
   - How to model the B2B sales cycle lag between marketing touchpoint and closed revenue
   - Code outline for implementation in Python (PyMC or Meridian) or Meta's Robyn in R

3. RESPONSE CURVES & BUDGET OPTIMIZATION:
   For each channel, define:
   - Current position on the response curve (under-invested? over-invested? optimal?)
   - Marginal ROI at current spend level
   - Optimal spend range for maximum efficiency
   - Budget scenario models: flat budget reallocation, +20% budget, -20% budget
   - Specific reallocation recommendation with projected ARR impact

4. DARK SOCIAL & UNMEASURED CHANNEL METHODOLOGY:
   Describe how the MMM should quantify:
   - LinkedIn organic / dark social demand creation
   - Podcast / speaking / earned media halo effects
   - Word-of-mouth / referral pipeline
   - Community-driven demand generation
   Include a "decomposed residual" approach for attributing unmeasured channels

5. HOLD-OUT VALIDATION STRATEGY:
   Design the geo-based or time-based hold-out test we should run to validate the MMM before relying on it for budget decisions.

6. CALIBRATION WITH LIFT TESTS:
   List 3 specific incrementality / geo lift tests I should run in parallel with the MMM build to calibrate channel contribution estimates. Include experiment design and sample size recommendations.

7. OPERATIONALIZATION PLAN:
   - How to refresh the MMM quarterly as a lightweight "always-on" measurement system
   - How to integrate MMM outputs into marketing planning workflows (budget cycles, channel reviews)
   - Dashboard specifications for ongoing monitoring
   - How to present MMM findings to: (a) CFO, (b) Board, (c) Sales leadership, (d) Channel owners

8. IMPLEMENTATION TIMELINE:
   Week-by-week 12-week implementation plan with:
   - Data collection and preparation milestones
   - Model build and validation milestones
   - Stakeholder review gates
   - Tool/platform requirements
   - Skills required (internal vs. external)

FORMAT: Lead each section with the most important insight or recommendation. Be specific — use actual numbers, formulas, and parameter ranges based on B2B SaaS industry norms. Do not generalize to the point of uselessness.

## Example Input/Output

**Input Example:**

Company: Veridian Analytics — B2B SaaS data observability platform  
ARR: $22M | Target: $35M next year  
Sales cycle: 90 days | ACV: $48K | Team: 8 marketers, $2.4M/year budget

Channels:
- Google Ads: $40K/month (demand capture — high-intent keywords)
- LinkedIn Ads: $25K/month (demand creation — enterprise targeting)
- Content/SEO: $15K/month fully-loaded cost (organic search + blog)
- Outbound SDR: $30K/month (4 SDRs)
- Events/Webinars: $20K/month average
- Brand/PR: $10K/month

Problem: "Last-touch attribution credits Google Ads for 68% of our revenue, but our ICP tells us they found us on LinkedIn or from a peer recommendation first. CEO wants to cut LinkedIn Ads because 'it doesn't convert.' We think we'll destroy pipeline if we cut it."

---

**Output Example (excerpt):**

**Channel Decomposition — Veridian Analytics:**

| Channel | Modeled Contribution Range | Adstock Half-Life | Saturation Status | Marginal ROI |
|---|---|---|---|---|
| Google Ads | 28–34% of influenced revenue | 2–3 weeks | Near saturation above $35K/month | $1.80 per $1 spent |
| LinkedIn Ads | 18–24% of influenced revenue | 6–10 weeks | Under-invested — room to scale to $38K | $2.40 per $1 spent |
| Content/SEO | 14–20% of influenced revenue | 12–20 weeks | Long-term compounding — efficient | $3.10 per $1 spent |
| Outbound SDR | 16–22% of influenced revenue | 1–2 weeks | Optimal band | $1.60 per $1 spent |
| Events | 8–12% of influenced revenue | 4–6 weeks | Likely over-invested at current pace | $1.20 per $1 spent |
| Brand/PR + Dark Social | 12–18% of residual contribution | 16–26 weeks | Underweighted in planning | Unmeasured but significant |

**Key Finding:** Google Ads' last-touch dominance (68%) is a measurement artifact — the same buyers were influenced by LinkedIn content 47–90 days earlier and conducted Google searches only in the final 2 weeks of their evaluation. The MMM's Adstock model, with LinkedIn's 7-week half-life, captures this compounding influence that last-touch attribution completely misses.

**CFO Summary (excerpt):**

"Our current attribution model is legally accurate but strategically misleading. It tells us what a customer did in the last 72 hours before becoming a lead — not what caused them to enter our funnel in the first place. Marketing Mix Modeling uses 24 months of weekly spend and revenue data, alongside econometric controls for seasonality and competitive activity, to estimate the causal revenue contribution of every channel — including brand programs and dark social that cookies can't track.

The initial MMM results show LinkedIn Ads generates 2.4x return per dollar at current spend levels and is under-saturated — suggesting we could profitably increase investment by $13K/month. Meanwhile, Google Ads, despite dominating last-touch reports, is operating near its saturation point. Reallocating $15K/month from Google to LinkedIn and Content is projected to generate $1.8M in additional influenced pipeline over the next 12 months with no budget increase.

We will validate this recommendation with a 6-week geo hold-out test before implementing the full reallocation, ensuring the board sees causal evidence before any budget shift is made."

## Success Metrics

- **MMM model fit:** R² ≥ 0.85 on the training window; out-of-sample MAPE ≤ 15% on hold-out period
- **Channel contribution believability:** Internal stakeholder alignment that decomposed contributions "feel right" based on first-principles channel knowledge (a smell test that Bayesian priors help pass)
- **Lift test validation:** MMM channel estimates within ±20% of geo-based incrementality test results
- **Budget decision confidence:** CMO and CFO aligned on reallocation within 90 days of model completion
- **Planning integration:** MMM outputs incorporated into next annual budget cycle with documented scenario models
- **Dark social quantification:** Residual/unmeasured contribution estimated and acknowledged in board reporting, even if not perfectly attributed
- **Reallocation ROI:** Actual pipeline and revenue 6 months after MMM-driven reallocation shows improvement directionally consistent with MMM predictions

## Related Prompts

- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](./Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [AI-Powered Incrementality Testing & Causal Revenue Attribution Intelligence Engine](./AI-Powered-Incrementality-Testing-&-Causal-Revenue-Attribution-Intelligence-Engine.md)
- [Dark Funnel Attribution & Anonymous Buyer Intent Intelligence Engine](./Dark-Funnel-Attribution-&-Anonymous-Buyer-Intent-Intelligence-Engine.md)
- [CAC Payback & Unit Economics Intelligence Engine](../CAC-Payback-&-Unit-Economics-Analytics/CAC-Payback-&-Unit-Economics-Intelligence-Engine.md)

## Integration Tips

- **Google Meridian / Meta's Robyn:** Both are open-source Bayesian MMM frameworks. Meridian (Python, TensorFlow Probability) is recommended for teams with Python data science capability. Robyn (R, nevergrad optimizer) is better for teams already working in R. Both can be run inside your existing data stack.
- **Snowflake / BigQuery / Redshift:** Pull weekly aggregated spend and revenue data directly into your MMM pipeline via dbt models. Keep raw tables separate from MMM-ready aggregate tables to make refresh cycles fast.
- **Salesforce / HubSpot CRM:** Export Opportunities with Creation Date, Close Date, Channel Source, Amount into the modeling dataset. Apply a lag transformation (typically 60–180 days for B2B SaaS) to align marketing spend with eventual revenue recognition.
- **Google Analytics 4 + BigQuery Export:** Use GA4's BigQuery export to build session-level conversion funnel data as a proxy demand signal when direct revenue data has lag issues.
- **Supermetrics / Funnel.io / Windsor.ai:** Automate weekly spend data pulls from all paid channels into a single Google Sheet or warehouse table — the MMM data foundation. Set up refresh every Monday to keep the model current.
- **Sigma / Looker / Tableau:** Build the MMM output dashboard in your existing BI tool. Key views: channel contribution waterfall, response curves by channel, budget scenario planning table (input budget → output projected pipeline), and model accuracy trend over time.
- **Notion / Confluence:** Store the MMM narrative documentation — prior rationale, model versions, validation results, and budget decision log — in your internal wiki so new CMOs and CFOs can audit the methodology.

## Troubleshooting

**Problem: The MMM says a channel contributes 0% or near-0% — but we know it drives pipeline.**  
**Solution:** This usually means the channel's weekly spend variation is too low (flat budget = no signal for the model to detect). Try one of: (a) deliberately vary spend on that channel by ±30% for 8 weeks to create signal; (b) use informative Bayesian priors anchored to industry benchmarks to prevent the model from zeroing out the channel; (c) incorporate a proxy variable (e.g., LinkedIn impressions or branded search volume) as a leading indicator even if spend is flat.

**Problem: The model shows conflicting results from one quarter to the next — the reallocation recommendation flips.**  
**Solution:** Instability typically signals multicollinearity (channels with correlated spend patterns) or insufficient data (fewer than 18 months of weekly observations). Fix by: (a) extending the data window; (b) using ridge regularization or informative priors to stabilize coefficients; (c) running the model at weekly granularity rather than monthly; (d) explicitly decorrelating channels in the model spec using PCA or channel-level instrumental variables.

**Problem: The CFO doesn't believe the MMM output because it conflicts with last-touch attribution reporting.**  
**Solution:** Run the models side by side for one quarter and let outcomes arbitrate. If the MMM says "reduce Google Ads by 20% and increase LinkedIn by 20%," implement this change in one geo/cohort while holding the other constant. Compare pipeline outcomes after 90 days. The geo hold-out experiment provides causal evidence that converts skeptics faster than any model explanation. Frame this to the CFO as a "measurement validation experiment" with a $0 net budget change.

## Version History
- v1.0: Initial creation (auto-generated)
