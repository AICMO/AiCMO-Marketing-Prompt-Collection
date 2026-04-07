# AI-Powered Marketing Mix Modeling & Media Investment Intelligence Engine - Prove Marketing ROI Without Cookies Using MMM

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, analytics, attribution, mmm, marketing-mix-modeling, budget-optimization, media-planning, incrementality, cookieless, revenue-operations

## Overview
Designs and runs an AI-assisted Marketing Mix Modeling analysis that quantifies the revenue contribution of every marketing channel — including offline, dark funnel, and brand spend that cookie-based attribution can never measure. Use this when cookie deprecation and iOS privacy changes are rendering your MTA model unreliable, when the CFO demands proof that brand and awareness investments generate revenue, or when you need a statistically defensible budget allocation framework that doesn't collapse the moment a deal takes 90+ days to close.

## Quick Copy-Paste Version

You are a senior marketing analytics strategist specializing in Marketing Mix Modeling (MMM). I need you to design and run an AI-assisted MMM analysis for my business to understand the true revenue impact of each marketing channel and optimize budget allocation.

My business context:
- Company type: [B2B SaaS / Enterprise Software / Professional Services / DTC eCommerce]
- ARR or annual revenue: [$X]
- Annual marketing budget: [$X total, broken down by channel if possible]
- Active marketing channels: [e.g., Google Ads, LinkedIn Ads, organic SEO, events, SDR outbound, brand/PR, email nurture, TV/CTV]
- Current attribution approach: [Last-touch / Multi-touch / Nothing formal]
- Data available: [List what you have — weekly revenue, weekly spend by channel, website traffic, sales pipeline data, seasonality notes]
- Biggest measurement blind spots: [e.g., "can't measure podcast sponsorships," "brand awareness spend has zero attribution"]
- Time period for analysis: [e.g., last 24 months of weekly data]

Please deliver:
1. MMM model design — the right modeling approach for my data volume, channel mix, and business model, with specific rationale (Bayesian vs. frequentist, lag structure, adstock decay assumptions)
2. Data requirements checklist — exactly what data I need to collect, at what granularity, and from which systems, to run this model
3. Baseline model output — for each channel, estimate its revenue contribution %, saturation curve shape, and marginal ROI (revenue generated per next $1K invested)
4. Budget optimization scenario — given my current spend allocation, what's the optimal reallocation? Show the expected revenue impact of moving $X from over-saturated channels to under-invested channels
5. Seasonality and external factor decomposition — break out how much of my revenue growth is attributable to marketing vs. market tailwinds, seasonality, and macro factors
6. 90-day implementation roadmap — how to set up MMM as an ongoing quarterly process rather than a one-time project
7. CFO presentation framework — one page translating MMM output into budget ask language a CFO will approve

## Advanced Customizable Version

ROLE: You are a Director of Marketing Science with 12 years of experience building Marketing Mix Models for B2B SaaS, enterprise software, and DTC brands. You have implemented MMM at companies from Series B ($20M ARR) through post-IPO using both open-source tools (Facebook Robyn, Google Meridian, PyMC-Marketing) and commercial platforms (Analytic Partners, Nielsen, Ekimetrics). You understand Bayesian inference, adstock and saturation transformations, carryover effects, and the specific challenges of B2B MMM — long sales cycles, small deal volumes, and brand investment that pays out over 12-18 months rather than 7 days.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Business model: [B2B SaaS / Enterprise Software / Professional Services / B2B+B2C Hybrid]
- Stage / ARR: [Series B / $18M ARR | Series C / $52M ARR | Post-IPO / $220M ARR]
- Industry vertical: [e.g., Security Tech, HR Tech, FinTech, DevTools, HealthTech]
- ICP: [job titles, company sizes, industries — e.g., VP Engineering at 200-2000 employee SaaS companies]
- ACV: [$X]
- Average sales cycle length: [X days / X months]
- Revenue recognition: [ARR subscription / project-based / usage-based]
- New business vs. expansion revenue split: [X% new logo / X% expansion]

MARKETING CHANNELS & SPEND (provide 24 months of weekly or monthly spend data ideally):
Paid Digital:
- Google Search Ads: [$X/mo average, X% of total budget]
- LinkedIn Ads: [$X/mo average, X% of total budget]
- Meta Ads (Facebook/Instagram): [$X/mo, X% of budget]
- Programmatic Display / Retargeting: [$X/mo]
- YouTube / CTV / Streaming TV: [$X/mo]
- Review site advertising (G2, Capterra): [$X/mo]
- Other paid digital: [$X/mo — specify platforms]

Brand & Awareness:
- Content marketing / SEO: [$X/mo — team cost + tools]
- PR / earned media: [$X/mo — agency + distribution]
- Podcast sponsorships: [$X/mo]
- Events & field marketing: [$X/mo — specify in-person vs. virtual]
- Executive thought leadership / speaking: [$X/mo]
- Analyst relations (Gartner, Forrester briefings): [$X/mo]

Outbound & Pipeline Generation:
- SDR / BDR team cost: [$X/mo]
- Sales engagement tools (Outreach, Salesloft): [$X/mo]
- Intent data platforms (Bombora, 6sense): [$X/mo]
- ABM platform: [$X/mo]

EMAIL & LIFECYCLE:
- Email marketing / nurture: [$X/mo — team + tools]
- Customer marketing / expansion campaigns: [$X/mo]

OUTCOME DATA AVAILABLE (specify time range and granularity — weekly preferred):
- Weekly/monthly new ARR bookings: [Yes / No / Partial]
- Weekly/monthly pipeline created ($): [Yes / No]
- Weekly/monthly MQLs / SQLs: [Yes / No]
- Weekly website sessions by channel: [Yes — GA4 / No]
- Weekly marketing spend by channel: [Yes — from ad platforms / Partial]
- Seasonality / external events calendar: [List known events — major conferences, product launches, economic shocks]
- Minimum data history available: [X months of weekly data]

MODELING OBJECTIVES (rank your top 3):
☐ Understand true revenue contribution of brand / awareness investment
☐ Optimize budget allocation across channels before next planning cycle
☐ Defend marketing budget to CFO using revenue contribution evidence
☐ Measure saturation — identify which channels have hit diminishing returns
☐ Understand marketing's contribution versus macro/market tailwinds
☐ Build a repeatable quarterly MMM process to replace annual one-off analysis
☐ Compare marketing ROI across channels that can't be measured with MTA
☐ Plan incremental budget scenarios (what happens if budget increases 20% or decreases 30%?)

CURRENT MEASUREMENT CHALLENGES:
- Primary attribution failure point: [e.g., "our 90-day sales cycle means MTA gives all credit to the last SDR touch," "iOS14 wiped 60% of our Meta conversion data"]
- Channels with zero attribution today: [e.g., podcast sponsorships, executive events, LinkedIn thought leadership, PR]
- CFO's current objection to marketing budget: [e.g., "I can't see a direct line from your spend to revenue," "Google Ads is the only channel with measurable ROI"]
- Biggest budget decision you need MMM to answer: [e.g., "Should we invest $500K in a brand campaign?" "Should we cut LinkedIn and increase Google?"]

---

DELIVERABLES REQUIRED:

**Section 1: MMM Model Design & Architecture**

Recommend the optimal MMM architecture for my context. Evaluate and recommend between:

| Approach | Description | Best For | Data Requirements | My Fit |
|---|---|---|---|---|
| Frequentist OLS | Ordinary Least Squares regression with transformations | High-volume DTC, large datasets, first-time MMM | 2+ years weekly data, 5+ channels | [score 1-10] |
| Bayesian MMM (PyMC / Google Meridian) | Prior distributions + likelihood function, posterior sampling | B2B SaaS, smaller datasets, uncertainty quantification | 1+ year weekly data, prior industry knowledge | [score] |
| Facebook Robyn (Ridge Regression + Nevergrad) | Open-source, automated hyperparameter optimization | Mid-market companies without data science team | 1+ year weekly data, R or Python capability | [score] |
| Hierarchical Bayesian | Multi-level model with region/segment decomposition | Multi-market, multi-product, enterprise | 2+ years, significant data engineering | [score] |
| Vendor/Commercial Platform | Analytic Partners, Nielsen, Ekimetrics | Enterprise, limited internal capability | Varies | [score] |

For my recommended model:
- Specify the exact mathematical structure (dependent variable, independent variables, transformation functions)
- Define the adstock (carryover) decay assumption for each channel — what percentage of this week's spend carries forward to next week? (e.g., Google Search: 20-30% carryover; Brand / PR: 50-70% carryover; Events: 40-60% carryover)
- Define the saturation curve shape for each channel (Hill function parameters α and γ) — at what spend level does each channel hit 50% of its maximum effectiveness?
- Specify required priors for Bayesian model (informed by industry benchmarks where my data is sparse)
- Identify the minimum viable dataset: if I only have 12 months of data instead of 24, what do I lose in model reliability?

**Section 2: Data Collection Architecture**

Build the complete data collection plan:

Dependent Variable (the outcome I'm modeling):
- Primary: Weekly new ARR booked ($) — explain how to handle long sales cycles (do I use pipeline created as a leading indicator or deal close as the definitive signal?)
- Secondary options if ARR data is noisy at weekly granularity: pipeline created ($), MQLs, or website conversion events
- How to handle data lag: for a 90-day average sales cycle, what is the correct lag structure between marketing spend and revenue recognition?

Independent Variables — for each channel, specify:
- Data source (ad platform API, Google Analytics 4, CRM, manual)
- Extraction method (API, CSV export, data warehouse query)
- Granularity required (daily preferred, weekly acceptable, monthly insufficient)
- Known data quality issues and how to handle them (e.g., Meta attribution window mismatches, GA4 sampled data, ad platform click-fraud inflation)

External Control Variables to include:
- Seasonality controls: specify Fourier terms (sin/cos waves) to capture weekly and annual seasonality patterns
- Market conditions: how to incorporate macro signals (GDP growth, industry hiring trends, tech investment climate)
- Competitive activity: if competitor spend data is available (via SimilarWeb, SEMrush), how to incorporate as a control variable
- Company-specific events: product launches, major press mentions, executive hires — how to encode as binary dummy variables

Data pipeline architecture:
- Recommended data warehouse setup (BigQuery / Snowflake / even Google Sheets for small teams)
- ETL process to standardize spend data from ad platforms + outcome data from CRM
- Data validation checks before running the model (outlier detection, missing data imputation rules)

**Section 3: Model Output Interpretation**

For each active marketing channel, deliver:

**Channel Revenue Contribution Table:**

| Channel | Annual Spend | Revenue Contribution ($) | Revenue Contribution (%) | Baseline ROI ($/$ spent) | Marginal ROI (next $1K) | Saturation Status |
|---|---|---|---|---|---|---|
| Google Search Ads | $X | $X | X% | X:1 | $X | Under-saturated / At saturation / Over-saturated |
| LinkedIn Ads | $X | $X | X% | X:1 | $X | [status] |
| Organic SEO / Content | $X | $X | X% | X:1 | $X | [status] |
| Events / Field | $X | $X | X% | X:1 | $X | [status] |
| SDR Outbound | $X | $X | X% | X:1 | $X | [status] |
| Brand / PR | $X | $X | X% | X:1 | $X | [status] |
| [All other channels] | | | | | | |
| **Baseline (non-marketing)** | — | $X | X% | — | — | — |
| **Total** | $X | $X | 100% | | | |

Explain:
- **Baseline revenue:** The revenue the company would generate without any marketing spend (repeat customers, word of mouth, brand inertia) — typically 40-60% of B2B SaaS revenue
- **Incremental revenue:** The revenue directly attributable to marketing activity above the baseline
- **Adstock visualization:** For each channel, show the carryover effect — how many weeks after a spend event does that channel's revenue contribution decay to <10% of peak?
- **Saturation curves:** For each channel, plot (or describe in table format) the relationship between weekly spend and weekly revenue contribution — where is the inflection point where additional spend yields diminishing returns?

**Section 4: Budget Optimization Scenarios**

Run three budget optimization scenarios:

**Scenario A: Same total budget, optimized allocation**
- Redistribute current total budget to maximize revenue contribution
- Show exactly which channels to increase, which to decrease, and by how much
- Quantify the expected revenue uplift from reallocation (% and $)
- Identify channels to exit (ROI below 1:1 even at minimum viable spend)

**Scenario B: Budget reduction (-25%)**
- If forced to cut 25% of total marketing budget, which channels to cut first?
- Prioritize cuts by: (1) lowest marginal ROI, (2) highest saturation, (3) longest time to revenue recovery
- Quantify expected revenue impact of each cut scenario
- Identify the "last to cut" channels — those where cuts cause disproportionate revenue loss

**Scenario C: Budget increase (+30%)**
- If given 30% more budget, where should the marginal dollar go?
- Rank investment priorities by marginal ROI (highest return on next dollar)
- Flag channels with high diminishing returns where increased investment would be wasted
- Recommend the investment pace (should the 30% increase be deployed immediately or ramped over 2 quarters?)

For each scenario, produce:
- Summary table: Channel | Current Spend | Scenario Spend | Delta | Expected Revenue Impact
- One-paragraph CFO narrative: "By shifting $X from [Channel A] to [Channel B and C], we expect to generate $X in additional revenue while maintaining the same total budget. Here's why the model supports this recommendation..."

**Section 5: Decomposition Analysis**

Decompose what's actually driving my revenue growth into its root causes:

| Revenue Driver | $ Contribution | % of Total Revenue |
|---|---|---|
| Baseline (organic demand, brand inertia, customer retention) | $X | X% |
| Marketing (all paid + owned channels combined) | $X | X% |
| Seasonality | $X | X% |
| Market growth tailwinds (macro) | $X | X% |
| Competitive dynamics | $X (positive or negative) | X% |
| Product improvements / pricing changes | $X | X% |

Key insight to answer: Of the revenue growth we've achieved over the past 24 months, how much was marketing's actual contribution vs. the company growing because the market grew? This is the number the CFO needs to see before approving a budget increase.

**Section 6: Ongoing MMM Operations Cadence**

Design the quarterly MMM operations process (because one-time MMM is a one-time insight; ongoing MMM is a competitive capability):

Monthly data refresh:
- Automated data pipeline to update channel spend and revenue data
- Model re-run triggers: when to re-run the model vs. when to use existing coefficients
- Anomaly detection: flags for when actual vs. model-predicted revenue diverges >15%

Quarterly model refresh:
- Full model re-estimation incorporating last quarter's data
- Coefficient stability check: are channel effectiveness estimates changing? Why?
- Prior updates for Bayesian model: how to incorporate new industry benchmarks

Annual model rebuild:
- Full structural review — are the right channels included? Has the business model changed?
- Channel mix evolution: add new channels, retire deprecated channels
- Benchmarking against industry MMM studies (LinkedIn B2B Benchmark, Google LightHouse MMM studies)

Governance and stakeholder engagement:
- Who owns MMM at the company (RevOps, Marketing Analytics, Finance)?
- Quarterly "MMM readout" meeting structure — who attends, what decisions get made?
- How to handle CFO/CEO skepticism: "Why should I trust this model over our Google Ads dashboard?"

**Section 7: MMM vs. MTA — When to Use Each**

Produce a decision framework for when to rely on MMM vs. multi-touch attribution vs. incrementality testing:

| Question | Best Measurement Method | Why |
|---|---|---|
| "Did this specific LinkedIn campaign generate leads?" | MTA (last-touch or multi-touch) | Event-level attribution for a specific campaign |
| "Is our $2M annual marketing budget generating positive ROI?" | MMM | Portfolio-level, long-horizon revenue impact |
| "Does our brand campaign actually lift pipeline?" | Incrementality test (geo-holdout) | Causal proof for a single intervention |
| "Should we increase Google Ads by $50K/mo?" | MMM saturation curves + incrementality | Marginal ROI at current saturation level |
| "Which content assets influence deal closure?" | MTA (content attribution model) | Touchpoint-level analysis within the pipeline |
| "How much of our growth is marketing vs. market?" | MMM decomposition | Baseline vs. incremental decomposition |
| "Did our podcast sponsorship work?" | MMM + brand lift survey | Immeasurable by MTA; MMM captures aggregate signal |

---

OUTPUT FORMAT: Produce a Marketing Mix Modeling Intelligence Report structured in the 7 sections above. Include an executive summary (250 words, written for a CFO audience), detailed analytical content for each section with tables and worked examples, a one-page "MMM Playbook" summarizing the modeling approach and data requirements for a new marketing analyst joining the team, and a "Next 30 Days" action checklist of the exact steps needed to begin data collection and model setup.

## Example Input/Output

**Input Example:**

Company: Callibra (B2B SaaS, Series C, $48M ARR)
ICP: VP of Revenue Operations and CFO at 500-5000 employee B2B companies
ACV: $72,000 | Sales cycle: 92 days average | Buyer committee: 5 stakeholders
Annual marketing budget: $4.2M across: Google Ads ($840K), LinkedIn Ads ($630K), Content/SEO ($420K), Events ($504K), SDR team ($1.05M), Brand/PR ($210K), Podcast sponsorships ($126K), Retargeting ($420K)
Current attribution: HubSpot last-touch (contact-level)
Data available: 26 months of weekly Google Ads and LinkedIn spend, monthly revenue from Salesforce, weekly GA4 sessions, quarterly event calendar
Key problem: "Our CFO is about to cut $1.2M from our budget. Last-touch attribution makes events look like they generate zero ROI and makes podcast sponsorships invisible. We know from customer interviews that 60% of our customers heard of us through an event or podcast before they ever clicked an ad, but we can't prove it with data."

**Output Example (excerpt):**

**MMM Model Recommendation for Callibra:**

*Recommended approach:* **Bayesian MMM using PyMC-Marketing** (open-source Python library)

Rationale: Callibra's 92-day sales cycle is the defining constraint. Frequentist OLS assumes contemporaneous effects — that this week's Google Ads spend generates this week's revenue. With a 92-day cycle, that's structurally wrong. Bayesian MMM allows us to incorporate lag structures where marketing spend in week 1 influences revenue 8-14 weeks later, with proper uncertainty quantification at each step. With 26 months of weekly data (~112 observations), Bayesian priors borrowed from industry benchmarks will stabilize estimates for low-frequency channels (events, podcasts) that don't have enough individual data points for frequentist estimation.

---

**Adstock Decay Parameters (Callibra-specific estimates):**

| Channel | Adstock Decay Rate | Interpretation | Half-Life |
|---|---|---|---|
| Google Search Ads | 0.25 | 25% of this week's effect carries to next week | 3.1 weeks |
| LinkedIn Ads | 0.35 | Brand recall and retargeting effects persist longer | 5.1 weeks |
| Content / SEO | 0.60 | Evergreen content generates compounding organic traffic | 14.9 weeks |
| Events & Field | 0.55 | Post-event follow-up and word-of-mouth extends effect | 12.6 weeks |
| Podcast Sponsorships | 0.50 | Listener recall and delayed action is characteristic of audio | 10.0 weeks |
| SDR Outbound | 0.20 | Immediate pipeline effect; minimal carryover | 2.5 weeks |
| PR / Brand | 0.65 | Brand equity builds and depreciates slowly | 18.1 weeks |
| Retargeting | 0.15 | Immediate conversion intent; rapid decay | 1.9 weeks |

*This is why events and podcasts look terrible in last-touch attribution.* Last-touch captures only the final touchpoint before demo booking — almost always a Google Ad click or SDR email. But events have a 12.6-week half-life in the MMM model: a prospect who attended your conference in March has a 55% residual probability of still being meaningfully influenced by that event in June when they finally click an ad and book a demo. Last-touch gives Google Ads 100% of the credit. MMM correctly apportions it.

---

**Revenue Contribution Output (Callibra, 12-month trailing):**

| Channel | Annual Spend | Revenue Contribution | ROI | Marginal ROI | Saturation Status |
|---|---|---|---|---|---|
| Google Search Ads | $840K | $3.2M | 3.8:1 | $1.4 per $1 | **Over-saturated** — at 78% of max effectiveness; next $100K yields only $140K |
| LinkedIn Ads | $630K | $2.8M | 4.4:1 | $2.6 per $1 | At saturation — strong ROI but marginal returns declining |
| Content / SEO | $420K | $4.1M | 9.8:1 | $7.2 per $1 | **Under-invested** — massive headroom; evergreen content compounds |
| Events & Field | $504K | $3.7M | 7.3:1 | $5.8 per $1 | **Under-invested** — high carryover effect systematically undercounted in MTA |
| SDR Team | $1.05M | $5.4M | 5.1:1 | $3.2 per $1 | Approaching saturation in current ICP — new segment expansion would reset |
| Podcast Sponsorships | $126K | $980K | 7.8:1 | $6.1 per $1 | **Under-invested** — audience quality exceptional; marginal ROI 3x Google Search |
| Brand / PR | $210K | $1.2M | 5.7:1 | $4.9 per $1 | Under-invested — long-horizon brand equity building |
| Retargeting | $420K | $890K | 2.1:1 | $0.6 per $1 | **Over-saturated** — hitting same prospects repeatedly; frequency has crossed into ad fatigue |
| **Baseline** | — | $12.8M | — | — | — |
| **Total** | $4.2M | $35.1M | 8.4:1 | — | — |

**Key MMM finding:** $1.26M (30%) of Callibra's current budget is allocated to over-saturated channels (Google Search + Retargeting). Reallocating $600K from those channels to Content/SEO ($300K increase) and Podcast Sponsorships ($300K increase) is projected to generate $2.1M in incremental annual revenue — without increasing total budget.

**CFO narrative:** "Our last-touch attribution showed that events and podcasts generated zero measurable ROI. Marketing Mix Modeling shows the opposite: events have a 7.3:1 ROI and podcasts have a 7.8:1 ROI — both higher than our Google Ads investment. The reason last-touch missed this is structural: our 92-day sales cycle means prospects attend an event in Q1, consider alternatives for 2 months, then click a Google Ad and book a demo in Q3. Last-touch gives Google Ads 100% of the credit; MMM correctly identifies the event as the primary acquisition driver. The proposed budget reallocation reduces Google Ads and retargeting (both over-saturated) by $600K and reinvests in content and podcasts, where marginal ROI is 5-7x higher. Expected annual revenue uplift: $2.1M. Payback period: 4.2 months."

## Success Metrics

- **Model fit (R²):** Target R² >0.85 — model explains >85% of weekly revenue variance; below 0.70 indicates missing variables or structural model problems
- **Channel coefficient stability:** Re-run model on 80% of data (holdout the most recent 20%) — channel ROI estimates should not change by more than ±25%; instability indicates overfitting or insufficient data
- **Decomposition sanity check:** Baseline (non-marketing) revenue should represent 40-65% of total B2B SaaS revenue; if baseline is below 30%, likely model misspecification
- **Directional validation:** MMM channel rankings should broadly align with sales team's qualitative assessment of "what's actually driving pipeline" — major disagreements deserve investigation, not dismissal
- **Budget decision quality:** Did the MMM output actually change a budget decision? The ultimate success metric is whether Finance acts on the model, not whether the model is statistically perfect
- **Incremental validation:** Run a geo-holdout experiment on one channel (e.g., pause events in 30% of territories for one quarter) — compare actual revenue impact against MMM's predicted effect; within ±20% counts as validation
- **Quarterly model drift:** Track whether channel ROI coefficients drift >30% between quarterly model runs without a corresponding change in strategy — significant drift indicates model instability or a genuine channel effectiveness shift worth investigating

## Related Prompts

- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](./Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [AI-Powered Incrementality Testing & Causal Revenue Attribution Intelligence Engine](./AI-Powered-Incrementality-Testing-&-Causal-Revenue-Attribution-Intelligence-Engine.md)
- [Revenue-Backed Demand Generation Planning & Campaign Architecture Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Revenue-Backed-Demand-Generation-Planning-&-Campaign-Architecture-Intelligence-Engine.md)
- [Marketing Budget Defense & CFO Finance Intelligence Engine](../../01_CMO-&-Leadership/Reporting-&-ROI/Marketing-Budget-Defense-&-CFO-Finance-Intelligence-Engine.md)

## Integration Tips

- **Google Meridian (open-source Bayesian MMM):** Google's official open-source MMM library (released 2024) uses JAX and NumPyro for Bayesian inference. Install via `pip install google-meridian`. Input format: CSV with columns `date`, `revenue`, `[channel_spend]`, `[control_variables]`. Output: posterior distributions for each channel's contribution and ROI. Best for: teams with Python fluency and >18 months of weekly data. Documentation at google.github.io/meridian.
- **Facebook Robyn (open-source Ridge MMM):** Meta's R-based MMM package (Robyn) uses ridge regression with automated hyperparameter optimization via the Nevergrad library. Install via `remotes::install_github("facebookexperimental/Robyn")`. Input: data frame with date, revenue, spend by channel, organic variables. Output: Pareto-optimal model configurations with channel decomposition plots. Best for: teams with R fluency, DTC or mixed B2B/B2C models.
- **PyMC-Marketing (Bayesian MMM):** Python-native Bayesian MMM library built on PyMC. Supports adstock transformations, Hill saturation functions, and full posterior uncertainty quantification. Install via `pip install pymc-marketing`. Ideal for B2B companies where uncertainty quantification matters for CFO credibility — instead of "LinkedIn ROI is 4.4:1," you can say "LinkedIn ROI is 4.4:1 with 90% confidence interval of 3.1:1 to 5.8:1."
- **Google BigQuery + Looker Studio:** Build the MMM data pipeline in BigQuery — one table per data source (ad platform spend, CRM revenue, GA4 traffic), one unified mart view joining them by week. Export weekly data to Python/R for modeling, write results back to BigQuery, visualize channel contribution and saturation curves in Looker Studio. This creates a reusable, quarterly-refreshable infrastructure rather than a one-time spreadsheet analysis.
- **HubSpot + Salesforce data export:** For revenue data, export weekly closed-won deal values from Salesforce (Reports > New Report > Opportunities > Group by Close Date Week > Sum Amount). For HubSpot, use the Deals Report filtered to Closed Won, grouped by Close Date. Feed into the MMM as the dependent variable with a lag offset matching your average sales cycle (e.g., for 90-day sales cycle, offset spend data by 13 weeks when correlating with revenue).
- **Northbeam / Rockerbox (commercial platforms):** If building an in-house MMM exceeds team capability, Northbeam and Rockerbox offer commercial MMM alongside MTA — providing both granular touchpoint attribution and portfolio-level mix modeling in one platform. Northbeam is particularly strong for DTC and B2C; Rockerbox has strong B2B capabilities including offline channel modeling. Both integrate directly with ad platforms, GA4, and major CRMs, eliminating the data engineering requirement.

## Troubleshooting

**Problem: MMM shows drastically different channel ROIs than MTA — Sales and CFO trust MTA dashboards and dismiss MMM as "theoretical."**

Solution: Don't try to replace MTA — position MMM as answering a different question. MTA answers "which touchpoint preceded this specific conversion?" MMM answers "at the portfolio level, what drives revenue?" Both are correct for their intended question. Run a structured validation session: pull 10 closed-won deals from CRM, ask the sales rep "what actually drove this deal?" and then show how MTA and MMM each credit those deals. In most cases, sales reps will describe an awareness journey (event → thought leadership → comparison → demo) that MTA compresses to one last-touch event, while MMM's channel decomposition matches their narrative. Concrete deal examples are more persuasive than model statistics. Present MMM as "the model that finally confirms what our best salespeople already knew."

**Problem: 24 months of weekly data doesn't exist — the company is too young, the data warehouse wasn't set up, or channel mix changed dramatically mid-period (e.g., switched from outbound-led to inbound-led).**

Solution: Start with what you have. 12 months of weekly data (52 observations) is the absolute minimum for a credible Bayesian MMM — use strong priors from industry benchmarks (LinkedIn B2B Benchmark studies, Analytic Partners published MMM research) to stabilize coefficient estimates for channels with sparse data. For structural breaks (major GTM pivots), split the model — run separate models for pre- and post-pivot periods rather than forcing a single model to fit a structurally different business. If fewer than 12 months of data exist, shift to incremental geo-holdout experiments as the primary measurement method and use MMM only as a planning tool with explicit uncertainty acknowledgment: "Our model has low data confidence — treat these as directional estimates, not precise ROI calculations."

**Problem: The model attributes a large percentage of revenue to "baseline" (organic demand) — leaving marketing with only 25-35% of revenue contribution, which feels like it undersells marketing's value.**

Solution: High baseline is actually a sign of a strong brand and product, not weak marketing — reframe it as a strategic asset. Present it this way: "Our brand has generated $12M in revenue this year with zero incremental marketing spend — that's the equity we've built. Marketing's 35% contribution represents $8.7M in incremental revenue from $4.2M in investment, a 2.1:1 return. The question isn't 'why is baseline so high?' but 'what marketing activities built the brand strength that enables that baseline?'" Then link the brand investment channels (PR, thought leadership, events) to baseline growth over time — showing that brand investment in year 1 becomes baseline revenue in years 2-3 is the most powerful marketing ROI argument you can make to a CFO.

## Version History
- v1.0: Initial creation (auto-generated) — 2026-04-07
