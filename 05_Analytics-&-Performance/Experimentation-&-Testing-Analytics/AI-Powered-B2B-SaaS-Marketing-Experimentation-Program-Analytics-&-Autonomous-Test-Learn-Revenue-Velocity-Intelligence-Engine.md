# AI-Powered B2B SaaS Marketing Experimentation Program Analytics & Autonomous Test-Learn Revenue Velocity Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** analytics, experimentation, a/b-testing, cro, revenue-operations, b2b, automation

## Overview

Analyzes your entire marketing experimentation portfolio — across channels, campaigns, and audiences — to identify statistically rigorous winners, surface compounding insight patterns, and auto-generate a prioritized next-test roadmap with expected revenue impact. Use this when you need to move from ad-hoc A/B testing to a systematic, AI-orchestrated experimentation engine that compounds learning velocity into measurable ARR contribution.

## Quick Copy-Paste Version

You are an expert marketing experimentation analyst with deep expertise in Bayesian statistics, multi-channel testing, and B2B SaaS growth. Analyze the following experimentation data and produce a complete program performance report.

EXPERIMENT PORTFOLIO DATA:
[Paste your experiment results table here — include: test name, channel, hypothesis, variant descriptions, sample size per arm, conversion rates, revenue/pipeline impact, test duration, statistical method used, winner declared (Y/N), date completed]

BUSINESS CONTEXT:
- Company stage: [Series A / B / C / D / Public]
- Primary growth motion: [PLG / SLG / Hybrid]
- Monthly experiment budget: [$X]
- Team running experiments: [Size & roles]
- Primary KPI: [Pipeline generated / MQL volume / Demo requests / Free trial activations / Revenue]

ANALYZE and OUTPUT:
1. **Portfolio Health Score** (0-100): Measure test velocity, win rate, statistical rigor, channel coverage, and learning compounding
2. **Statistical Validity Audit**: Flag any tests with underpowering, p-hacking risk, novelty effect contamination, or SUTVA violations
3. **Top 5 Compounding Insights**: Cross-experiment patterns that consistently drive lift regardless of channel
4. **Dead Zone Analysis**: Hypotheses you've over-tested with diminishing returns — stop testing these
5. **Priority Experiment Backlog**: Top 10 next experiments ranked by Expected Value = (Probability of Win × Estimated Lift × Revenue at Stake) — with full hypotheses, success metrics, and sample size requirements
6. **Program Velocity Benchmark**: How does your test-per-month rate compare to best-in-class B2B SaaS companies at your stage?
7. **Revenue Attribution**: What is the estimated annual ARR contribution from your experimentation program?

Use Bayesian probability language for win confidence. Flag any test that needs to be re-run due to methodological issues.

## Advanced Customizable Version

# ROLE
You are a Principal Marketing Data Scientist and Experimentation Program Lead with 12+ years designing high-velocity test-and-learn systems for B2B SaaS companies scaling from $10M to $500M ARR. You apply Bayesian statistics, variance reduction techniques (CUPED, CUPAC), sequential testing frameworks, and multi-armed bandit allocation to maximize learning velocity and revenue impact from a marketing experimentation portfolio.

# COMPANY PROFILE
Company: [Company Name]
ARR: [$X]M
Growth stage: [Series X / Growth-stage / Scale-up]
Primary GTM motion: [Product-Led Growth / Sales-Led / Hybrid PLG+SLG]
Top of funnel volume: [X visitors/month, Y MQLs/month, Z trials/month]
Current experiment cadence: [X tests running simultaneously / month]
Testing infrastructure: [Optimizely / VWO / LaunchDarkly / Split.io / Statsig / Home-built / None]
Statistical method currently used: [Frequentist p<0.05 / Bayesian / Sequential / None]
Holdout group in place: [Yes/No — X% holdout]

# EXPERIMENT PORTFOLIO INPUT
Provide your complete experiment log in this structure (CSV or table format):

| Test ID | Test Name | Channel | Layer (UI/Copy/Targeting/Offer/Timing) | Hypothesis | Control Description | Variant Description | Start Date | End Date | Sample Size (Control) | Sample Size (Variant) | Primary Metric | Control Rate | Variant Rate | Relative Lift | p-value / Posterior Probability | Bayesian Expected Loss | Winner | Revenue/Pipeline Delta | Secondary Metrics | Notes |

# ANALYSIS FRAMEWORK

## 1. STATISTICAL RIGOR AUDIT
For each completed test, assess:
- **Power Analysis**: Was the test adequately powered (≥80% power, MDE ≥ minimum business-relevant effect)?
- **Novelty Effect**: Did lift decay after week 1, suggesting a novelty spike rather than genuine improvement?
- **Peeking Risk**: Was the test stopped early based on interim results (frequentist p-hacking)?
- **SUTVA Violations**: Could network effects or shared cookies contaminate control/variant groups?
- **Multiple Comparison Problem**: Were multiple metrics tested without correction (Bonferroni / Benjamini-Hochberg)?
- **Sample Ratio Mismatch (SRM)**: Does actual traffic split match intended split within ±1%?
- **Survivorship Bias**: Were losing tests removed from the portfolio log?
Flag each test as: ✅ Valid | ⚠️ Questionable | ❌ Invalid — Rerun Required

## 2. PORTFOLIO VELOCITY METRICS
Calculate and benchmark:
- **Tests shipped per month**: Target 8-15 for Series B+, 3-7 for Series A
- **Win rate**: Industry benchmark 20-35% for well-formed hypotheses
- **Average time-to-decision**: Target <21 days for digital tests; <45 for pipeline tests
- **Coverage ratio**: % of funnel stages with active tests (Awareness / Acquisition / Activation / Retention / Revenue)
- **Compounding rate**: Are learnings from Month 1 tests being applied to Month 3 designs?
- **Hypothesis generation rate**: Tests launched vs. hypothesis backlog size

## 3. INSIGHT PATTERN MINING
Across all experiments, identify:
- **Universal conversion principles**: What message angles, formats, or friction removal tactics consistently win across channels?
- **Segment-specific winners**: Which experiments won for one ICP segment but lost for another?
- **Timing and sequence patterns**: Do certain test types win better at specific funnel stages?
- **Diminishing returns zones**: Which hypothesis categories have been exhausted (>5 tests, win rate <10%)?
- **Interaction effects**: Do two separate test winners combine for super-additive or sub-additive impact?

## 4. EXPECTED VALUE PRIORITIZATION (EVP) FRAMEWORK
Score each candidate experiment in your backlog using:

EV = P(Win) × Estimated Lift × (Monthly Revenue at Risk × 12)

Where:
- **P(Win)**: Estimated probability based on historical win rates for this hypothesis category + strength of supporting evidence (customer research, heatmaps, sales call recordings, competitive data)
- **Estimated Lift**: Conservative, base, and optimistic scenarios (5th, 50th, 95th percentile)
- **Revenue at Risk**: Monthly ARR / pipeline influenced by the funnel stage being tested

Produce a prioritized backlog with:
- Test name & layer
- Full hypothesis with "We believe [change] will cause [outcome] because [evidence]" format
- Success metric (primary + guardrail)
- Sample size required (calculate using expected baseline rate, MDE, α=0.05, power=0.80)
- Estimated test duration at current traffic
- Expected annual ARR impact if winner
- Owner & resource requirements

## 5. PROGRAM ROI CALCULATION
Calculate cumulative revenue contribution using:

Program ARR Contribution = Σ (Tests Won × Average Lift × Revenue at Stake × Persistence Rate)

Where Persistence Rate = % of winning test lifts that persist 6 months post-implementation (industry benchmark: 65-80%)

Compare against:
- Cost of experimentation program (headcount + tooling + lost opportunity of holdout)
- Benchmark: Best-in-class B2B SaaS sees 3-8× ROI on experimentation programs

## 6. NEXT-QUARTER EXPERIMENTATION ROADMAP
Produce a 90-day experiment calendar with:
- Week-by-week launch schedule
- Resource allocation across teams (PMM, Growth, Paid, Content, RevOps)
- Required sample sizes and expected decision dates
- Risk-adjusted expected ARR contribution
- Learning objectives for the quarter (what strategic questions must be answered)

## 7. AUTONOMOUS EXPERIMENT BRIEF GENERATION
For the top 5 prioritized tests, generate a complete experiment brief including:
- Background & hypothesis (Jobs-to-be-Done framing)
- Primary and secondary success metrics
- Target segment and exclusion criteria
- Traffic allocation plan
- Statistical method recommendation (Bayesian recommended for faster decisions)
- Minimum detectable effect
- Launch checklist (QA gates, pre-experiment logging, holdout setup)
- Post-experiment analysis plan

# OUTPUT FORMAT
Deliver as a structured Experimentation Program Intelligence Report:
1. Executive Summary (3 bullets: program health, top insight, #1 next action)
2. Statistical Validity Audit Table
3. Portfolio Velocity Dashboard
4. Top 5 Cross-Experiment Insights
5. Dead Zone Hit List (stop testing these)
6. Prioritized Experiment Backlog (EVP-ranked)
7. 90-Day Roadmap with revenue projection
8. Full experiment briefs for top 5 tests
9. Integration actions (what to update in HubSpot, Salesforce, Looker, etc.)

## Example Input/Output

**Input Example:**
Company: Gridline Analytics (Series B, $28M ARR, B2B SaaS)
GTM: Hybrid PLG + Sales-Assisted
Monthly traffic: 85,000 visitors
Testing tool: Statsig (Bayesian)
Holdout: 5% global holdout in place

Experiment log (last 6 months, 18 tests):
- Test 001: Homepage hero headline A/B | Control: "Forecast revenue with confidence" | Variant: "Stop forecasting blind — know your revenue before it happens" | 14 days | n=12,400/arm | Demo request rate: 2.1% vs 3.4% | Posterior win prob: 94% | Winner: Variant | Pipeline delta: +$340K/month
- Test 002: Pricing page CTA | Control: "Start Free Trial" | Variant: "See Gridline in Action" (→ demo) | 21 days | n=4,200/arm | Trial starts: 4.2% vs 3.9% | Posterior win prob: 43% | No winner | Pipeline delta: -$18K/month
- Test 003: Outbound email subject line | Control: "[First name], your Q3 forecast is at risk" | Variant: "How [Company] competitors are cutting forecast error by 40%" | n=2,100/arm | Open rate: 18% vs 31% | Reply rate: 2.1% vs 4.7% | Posterior win prob: 99% | Winner: Competitor angle | Booked meetings delta: +23/month
- [15 additional tests...]

**Output Example (excerpt):**
## EXPERIMENTATION PROGRAM INTELLIGENCE REPORT
### Gridline Analytics — Q3 2026 | Generated by AI Experimentation Agent

**Executive Summary:**
- Program Health Score: 72/100 (Good — with 3 critical fixes required)
- Top Compounding Insight: "Fear-of-missing-out + specific competitor comparison" angles win across ALL channels (homepage, email, paid) at 2.1-2.8× lift vs feature-benefit messaging
- #1 Next Action: Rerun Test 007 (underpowered — only 1,840 samples vs 4,200 required) before implementing the variant

**Statistical Validity Audit (excerpt):**
| Test | Status | Issue |
|------|--------|-------|
| Test 001 | ✅ Valid | Well-powered, no SRM, Bayesian p(win)=94% |
| Test 007 | ❌ Rerun | Underpowered — actual n=1,840, required n=4,200 for MDE of 15% |
| Test 014 | ⚠️ Questionable | Stopped at Day 4 (peeking risk); p-value dipped below 0.05 and decision made — re-run with pre-registered stop rule |

**Top Compounding Insight #1:**
"Competitive displacement language ('how your competitors…', 'while others…') consistently outperforms feature-benefit language across homepage (Test 001: +62%), email (Test 003: +124% reply rate), and LinkedIn ads (Test 009: +38% CTR). This is your core conversion principle for Q4. Apply across all top-of-funnel copy immediately."

**Priority Experiment #1 — Experiment Brief:**
Name: Personalized Homepage Hero by ICP Segment
Hypothesis: We believe showing RevOps leaders 'Stop managing forecasts in spreadsheets' (vs generic hero) will increase demo request rate by 20%+ because RevOps personas have a documented pain with spreadsheet-based forecasting (confirmed in 47 Gong calls reviewed)
Primary Metric: Demo request rate (current: 2.1% baseline on this segment)
MDE: 15% relative lift (from 2.1% → 2.4%)
Sample size required: 8,900/arm
Estimated test duration: 18 days at current RevOps segment traffic (990/day)
Expected annual pipeline impact: +$1.2M (conservative) / +$2.8M (base) / +$5.1M (optimistic)
Statistical method: Bayesian with flat prior, decision threshold: P(win) ≥ 90%

## Success Metrics

- **Portfolio Health Score** consistently above 75/100
- **Win rate** in the 20-35% range (below 15% = weak hypotheses; above 45% = tests are too safe)
- **Test velocity** of 6-12 tests shipped per month (Series B benchmark)
- **Time-to-decision** under 21 days for 80%+ of tests
- **Program ROI** of 3-8× investment within 12 months (measure via holdout group delta vs test group)
- **Zero invalid tests** being implemented (statistical audit catches all before rollout)
- **Backlog depth** of 40+ prioritized, evidence-backed hypotheses at all times
- **Revenue attribution**: Experimentation program accounts for 15-30% of year-over-year conversion rate improvement

## Related Prompts

- [`05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Marketing-Experimentation-&-Statistical-Decision-Intelligence-Engine.md`](../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Marketing-Experimentation-&-Statistical-Decision-Intelligence-Engine.md)
- [`05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Marketing-Incrementality-Testing-&-Causal-Attribution-Intelligence-Engine.md`](../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Marketing-Incrementality-Testing-&-Causal-Attribution-Intelligence-Engine.md)
- [`05_Analytics-&-Performance/Conversion-Rate-Optimization-Analytics/AI-Powered-B2B-SaaS-CRO-Analytics-&-Experimentation-Intelligence-Engine.md`](../Conversion-Rate-Optimization-Analytics/AI-Powered-B2B-SaaS-CRO-Analytics-&-Experimentation-Intelligence-Engine.md)
- [`04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Landing-Page-&-Funnel-Conversion-Intelligence-&-Multivariate-Optimization-Revenue-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Landing-Page-&-Funnel-Conversion-Intelligence-&-Multivariate-Optimization-Revenue-Engine.md)

## Integration Tips

- **Statsig / Optimizely / VWO**: Export the experiment results table as CSV and paste directly into the prompt. Include the full metrics export, not just the summary dashboard — the AI needs raw numbers to audit statistical validity.
- **Salesforce + HubSpot**: After the AI identifies winning tests, create a Salesforce campaign for each winner to track downstream pipeline attribution. Use HubSpot's A/B test reporting API to pull lifecycle stage conversion deltas into your prompt input.
- **Looker / Tableau**: Build an "Experimentation Portfolio" dashboard with dimensions for test status, channel, hypothesis category, and EVP score. The AI output provides the metadata; your BI tool visualizes the portfolio health over time.
- **Notion / Confluence**: Paste experiment briefs directly into your team's experimentation wiki. Use the standardized "We believe… will cause… because…" hypothesis format consistently for future searchability and pattern mining.
- **Gong / Chorus**: Before generating hypotheses for new tests, pipe in Gong call summaries (especially objection patterns and competitor mentions) as supporting evidence to strengthen P(Win) estimates.
- **Zapier / Make**: Automate weekly experiment status pings — when a test crosses 90% Bayesian win probability in Statsig, trigger a Slack alert to the growth team with the AI-generated decision memo and implementation checklist.

## Troubleshooting

**Problem: The AI flags most of my tests as underpowered, but I can't wait 30+ days per test.**
Solution: Reduce your MDE requirement by focusing only on funnel steps with enough volume (top-of-funnel stages), or switch from frequentist to Bayesian testing with an informative prior (based on historical win rates). Bayesian methods can make sound decisions with 30-50% less sample than frequentist at equivalent accuracy. Also consider "bandit" allocation (70% traffic to current leader, 30% to challenger) to reach significance faster while limiting downside.

**Problem: The win rate from the AI analysis is showing below 15%, which means weak hypotheses.**
Solution: Before running any new test, require three forms of supporting evidence: (1) quantitative signal (heatmaps, funnel drop-off data, cohort analysis), (2) qualitative signal (at least 10 customer interviews or Gong calls), and (3) competitive signal (what are winning companies in your category doing). Weak hypotheses typically lack at least two of these. Use the AI's hypothesis generation in the Advanced Version to upgrade your backlog quality.

**Problem: My team has different definitions of "winner" — some use p<0.05, others use p<0.10, and others just look at absolute numbers.**
Solution: Standardize on Bayesian P(win) ≥ 90% as your decision threshold for implementing tests, and P(win) ≥ 95% for changes to high-traffic, high-revenue pages (pricing, homepage hero). Paste your current inconsistent decision log into the prompt and ask the AI to retroactively re-evaluate each test against a standardized framework — this will reveal tests you implemented that were actually losers, and vice versa.

## Version History
- v1.0: Initial creation (auto-generated)
