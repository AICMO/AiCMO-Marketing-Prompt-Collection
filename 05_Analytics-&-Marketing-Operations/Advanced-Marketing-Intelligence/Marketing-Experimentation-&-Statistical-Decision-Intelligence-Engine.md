# Marketing Experimentation & Statistical Decision Intelligence Engine - AI-Powered A/B Testing, Bayesian Analysis & Continuous Optimization Framework

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** experimentation, a/b-testing, analytics, conversion-optimization, b2b, statistical-significance, bayesian, marketing-ops

## Overview
Designs, analyzes, and auto-interprets marketing experiments end-to-end — from hypothesis generation and test architecture to statistical significance calls and winner deployment recommendations — eliminating the guesswork and manual analysis that causes teams to ship losers, stop tests too early, or never act on results.

## Quick Copy-Paste Version

You are a senior marketing data scientist and experimentation strategist. I need to run a marketing experiment and need complete guidance.

CONTEXT:
- What I'm testing: [landing page headline / email subject line / CTA button / pricing page / onboarding flow / ad creative]
- Current baseline metric: [e.g., 3.2% conversion rate / 22% email open rate / $48 CPA]
- Monthly traffic/volume to this element: [e.g., 12,000 visitors/month / 45,000 emails/send]
- Business goal: [increase trial signups / reduce churn / improve ROAS]
- Company type: [B2B SaaS / ecommerce / marketplace]

DELIVER:
1. **Hypothesis Statement** — "If we [change X] then [metric Y] will [increase/decrease] by [Z%] because [behavioral/psychological rationale]"

2. **Test Architecture**
   - Variant(s) to test (2-4 variants max, with specific copy/design direction)
   - Traffic split recommendation
   - Primary metric + 2-3 guardrail metrics to monitor
   - Minimum detectable effect (MDE) calculation

3. **Sample Size & Duration**
   - Required sample size per variant (at 95% confidence, 80% power)
   - Estimated runtime in days
   - Early stopping criteria (if Bayesian approach is appropriate)

4. **Bayesian vs. Frequentist Recommendation** — which approach fits this test and why

5. **Analysis Framework** — exact decision rules: "Stop the test and declare winner IF [X]. Continue IF [Y]. Kill and retest IF [Z]."

6. **Implementation Spec** — what engineering/ops needs to build this (targeting logic, tracking events, exclusion rules)

7. **Post-Test Action Plan** — winner rollout, loser analysis, next test in learning roadmap

## Advanced Customizable Version

ROLE: You are a Principal Marketing Experimentation Scientist with expertise in Bayesian statistics, causal inference, and growth optimization. You've run 500+ experiments at high-growth B2B SaaS companies. You design experiments that produce actionable learnings whether they win, lose, or are inconclusive.

COMPANY CONTEXT:
- Company: [Company Name]
- Stage: [Seed/Series A/B/C/Growth/Enterprise]
- Business model: [PLG / Sales-led / Hybrid / ecommerce]
- Key growth metric: [ARR / MRR / GMV / DAU]
- Analytics stack: [GA4 / Mixpanel / Amplitude / Heap / Custom]
- Testing tool: [Optimizely / VWO / LaunchDarkly / Statsig / Unleash / In-house]
- Experiment backlog priority system: [ICE / PIE / RICE / Custom]

EXPERIMENT BRIEF:
- Experiment name: [descriptive slug]
- Surface: [webpage URL / email campaign type / in-app feature / ad set]
- Current state: [describe control in detail — copy, design, user flow]
- Proposed change: [describe hypothesis and what changes]
- Motivation: [data signal that prompted this test — heatmap insight / user interview / competitor observation / funnel drop-off]
- Team owner: [Growth / Product / Marketing / Revenue Ops]

STATISTICAL PARAMETERS:
- Confidence level required: [90% / 95% / 99%] (use 95% if unsure)
- Statistical power: [80% / 90%] (use 80% standard, 90% for high-stakes tests)
- Expected baseline conversion rate: [X%]
- Minimum business-relevant lift: [e.g., "we need at least 5% relative improvement to justify engineering cost"]
- Test type: [one-tailed / two-tailed] (two-tailed unless you have strong directional prior)
- Approach preference: [Frequentist / Bayesian / Sequential / Adaptive / No preference]

CONSTRAINTS:
- Maximum test runtime: [X weeks — due to business seasonality, sprint cycle, etc.]
- Minimum runtime floor: [X days — to capture full weekly cycle effects]
- Audience exclusions: [existing customers / trial users / mobile only / specific segments]
- Legal/compliance flags: [GDPR consent requirements / healthcare regulations / financial disclosures]

DELIVER THIS COMPLETE EXPERIMENT SPECIFICATION:

**SECTION 1 — HYPOTHESIS & LEARNING AGENDA**
- Primary hypothesis (If/Then/Because format)
- Secondary hypotheses this test can also answer
- What a "win" teaches us, what a "loss" teaches us, what a flat result teaches us
- How this fits into the broader experimentation roadmap

**SECTION 2 — EXPERIMENT DESIGN**
- Control description (exact spec)
- Variant A description (exact spec with rationale tied to behavioral science principle)
- Variant B description (if multivariate — only if traffic supports it)
- Randomization unit: user / session / account / device (with justification)
- Holdout strategy (should you hold back 5-10% from all variants for long-term measurement?)
- Novelty effect mitigation plan

**SECTION 3 — STATISTICAL ARCHITECTURE**
- Approach recommendation (Bayesian / Frequentist / Sequential) with explicit justification
- Sample size per variant calculation:
  Formula: n = 2 × (Z_α/2 + Z_β)² × p(1-p) / δ²
  [Calculate and show work with your inputs]
- Required runtime (days) = sample size ÷ (daily traffic × allocation %)
- Bayesian prior specification (if Bayesian): Beta(α, β) based on historical baseline
- Sequential test boundaries (if sequential): O'Brien-Fleming or Lan-DeMets spending function
- Multi-metric correction: Bonferroni or FDR adjustment if testing 3+ metrics

**SECTION 4 — METRICS FRAMEWORK**
- Primary metric (north star for this test): [metric name, measurement method, data source]
- Guardrail metrics (must not degrade): [list 2-3 with acceptable degradation thresholds]
- Secondary metrics (directional signal only): [list 2-3]
- Metric collection spec: event names, properties, timing windows
- Data quality checks: sample ratio mismatch (SRM) test, bot filtering, instrumentation validation

**SECTION 5 — DECISION RULES (NO AMBIGUITY)**
State exact numerical thresholds:
- SHIP VARIANT: [specific criteria — e.g., p < 0.05 AND primary metric lift > 5% AND no guardrail metric degraded > 2%]
- EXTEND TEST: [criteria — e.g., p = 0.07–0.10 AND 80% of required sample collected AND trending positive]
- KILL TEST: [criteria — e.g., variant clearly negative after 50% sample, or SRM detected]
- ROLLBACK TRIGGER: [post-ship monitoring rule — e.g., if conversion drops > 3% in 72h post-launch]
- NO WINNER PROTOCOL: [what happens when test is flat — document learning, adjust hypothesis, retest with larger MDE]

**SECTION 6 — IMPLEMENTATION SPEC**
- Targeting rules (who sees this test, written as pseudocode)
- Exclusion logic
- QA checklist (10-point pre-launch validation)
- Required tracking events (name, schema, example payload)
- Dashboard setup: what to build in [analytics tool] to monitor this test in real time

**SECTION 7 — BUSINESS IMPACT PROJECTION**
If variant wins at minimum expected lift:
- Monthly [primary metric] impact: [X units]
- Annualized revenue impact: $[Y] (show calculation)
- Estimated experiment ROI (lift value ÷ engineering + ops cost)
- Confidence interval on business impact

**SECTION 8 — LEARNING ROADMAP**
Based on this result (regardless of outcome):
- Next 3 experiments in this test area (hypothesis evolution)
- Cross-team learning to share (what other teams should know)
- Update to experimentation wiki / test log

OUTPUT FORMAT: Structure this as a formal experiment brief that can be handed directly to an engineer and data analyst with zero additional explanation needed.

## Example Input/Output

**Input Example:**

Company: Meridian Analytics (Series B, $18M ARR, B2B SaaS, sales-led with PLG motion)
Testing: Free trial signup CTA on pricing page
Current: "Start Free Trial" button, blue, center-aligned, above fold
Traffic: 8,400 unique visitors/month to pricing page
Baseline conversion: 4.1% (trial signup rate)
Goal: Increase trial signups by at least 10% relative (to 4.51%)
Testing tool: Statsig
Analytics: Amplitude
Sprint constraint: Must complete within 4 weeks

**Output Example (excerpt):**

---

**EXPERIMENT: pricing-page-cta-v1**

**Hypothesis:** If we change "Start Free Trial" to "See Meridian In Action — Free" with social proof micro-copy ("Join 1,200+ analytics teams") then the trial signup rate will increase by ≥10% relative (4.1% → 4.51%+) because specificity reduces perceived risk and social proof activates conformity bias, directly addressing the consideration-stage visitor's question "is this worth my time?"

**Statistical Architecture:**
- Approach: Bayesian (justified: low traffic, need to be efficient; Bayesian allows early stopping when posterior probability of being best crosses 95%)
- Prior: Beta(41, 959) — derived from 4.1% baseline over trailing 30 days
- Required sessions per variant: 3,847 (frequentist baseline)
- Expected runtime: 18 days at 50/50 split (3,847 ÷ 4,200 sessions/variant/month × 30)
- Bayesian stopping rule: Stop when P(variant beats control) ≥ 95% with ≥500 sessions each, OR after 28 days

**Variant Spec:**
- Control: "Start Free Trial" (existing)
- Variant A: "See Meridian In Action — Free" + micro-copy: "Join 1,200+ analytics teams. No credit card."

**Decision Rules:**
- SHIP: P(A > Control) ≥ 95% AND lift ≥ 5% AND demo request rate not degraded > 2%
- EXTEND: P(A > Control) = 80-94% at day 18 — run to day 28 max
- KILL: P(A > Control) < 40% at day 14 with ≥1,000 sessions each
- ROLLBACK: If 72h post-ship trial-to-demo rate drops > 4%

**Business Impact (if wins at 10% lift):**
- Monthly signups: +34 trials/month (344 → 378)
- Assuming 8% trial-to-paid at $12K ACV: +$32,640 incremental ARR from this single change
- Experiment ROI: Engineering cost ~4h ($600) vs. $32,640 ARR = 54:1 ROI

---

## Success Metrics

- **Test validity:** Zero sample ratio mismatch (χ² SRM test p > 0.05)
- **Decision quality:** Clear winner/loser declared within planned runtime (not "inconclusive" on 70%+ of tests)
- **Lift accuracy:** Post-ship lift within ±20% of predicted lift from test
- **Learning velocity:** ≥2 experiment decisions per month per team
- **Experiment ROI:** Average annualized revenue impact per winning test ≥ $25K for growth-stage SaaS
- **False discovery rate:** <10% of shipped "winners" show no sustained lift after 30 days

## Related Prompts

- [`../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Predictive-Revenue-Forecasting-Engine.md`](../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Predictive-Revenue-Forecasting-Engine.md)
- [`../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Behavioral-Personalization-&-Dynamic-Content-Optimization-Engine.md`](../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Behavioral-Personalization-&-Dynamic-Content-Optimization-Engine.md)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/Ad-Creative-Multivariate-Testing-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/Ad-Creative-Multivariate-Testing-Engine.md)
- [`../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Funnel-Performance-Diagnostics.md`](../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Funnel-Performance-Diagnostics.md)

## Integration Tips

- **Statsig / LaunchDarkly:** Use the advanced version's Section 6 tracking spec as the direct input to feature flag configuration. The targeting pseudocode maps directly to audience rules in both tools.
- **Amplitude / Mixpanel:** Create an experiment funnel chart with the primary metric event + user segment = "variant group" property. Set up Amplitude's Experiment Results chart or Mixpanel's A/B test report using the event names from Section 6.
- **HubSpot / Marketo:** For email experiment variants, use the decision rules in Section 5 to automatically promote winning variant using workflow conditional branching — set winner threshold as the automation trigger.
- **Google Sheets / Notion:** Export test log output from Section 8 into a shared experimentation wiki. Use a table with columns: Test Name | Hypothesis | Start Date | End Date | Result | Lift % | Confidence | Next Test.
- **Zapier / Make:** Automate winner notification — when analytics platform fires "experiment concluded" event, trigger Zapier to post result summary to Slack #growth-experiments channel with business impact calculation.
- **Segment:** Use Segment's Personas to create experiment audience cohorts that persist across channels, enabling the same test to run simultaneously on web, email, and in-app with consistent user assignment.

## Troubleshooting

**Problem: Test keeps reaching runtime without a winner (perpetual "inconclusive")**
Solution: Your minimum detectable effect (MDE) is too small for your traffic volume. Use the Quick Version to recalculate — if required runtime exceeds 8 weeks, either (a) increase the MDE threshold to a larger, business-relevant lift, (b) run on a higher-traffic surface first to gather directional signal, or (c) switch to a Bayesian approach with a looser decision threshold (80% probability of being best) to get directional learnings faster. Never extend a frequentist test past 2x its planned runtime — p-hacking risk escalates sharply.

**Problem: Test wins in the experiment but shows no lift after shipping to 100%**
Solution: Classic "false winner" from peeking or SRM. First, run the SRM check retroactively — if χ² p < 0.05, your randomization was broken and the result is invalid. Second, check for novelty effect: users who saw a new variant in week 1 may behave differently from all users post-ship. Implement a 2-week holdout (5% of users never see the variant) to measure true long-term lift. Third, validate that the winning behavior generalizes across all user segments, not just the highest-converting cohort that happened to be over-indexed in the test group.

**Problem: Engineering says the experiment will take 3 sprints to instrument properly**
Solution: The experiment is over-specified for your current velocity. Simplify the test to the single highest-leverage change (one variable, not multivariate), use an existing tracking event instead of a new instrumentation request, and test on a page/flow you can deploy via your CMS or marketing tools without engineering dependency. Reserve complex experiments (multi-page funnel, backend pricing tests, onboarding flow changes) for quarterly planning when engineering time can be allocated in advance.

## Version History
- v1.0: Initial creation (auto-generated)
