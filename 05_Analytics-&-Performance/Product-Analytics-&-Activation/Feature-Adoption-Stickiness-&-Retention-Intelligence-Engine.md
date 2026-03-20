# Feature Adoption, Stickiness & Retention Intelligence Engine - Identify Which Features Drive Long-Term Revenue and Engineer Viral Growth Loops

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** product-analytics, feature-adoption, stickiness, dau-mau, retention, amplitude, mixpanel, posthog, saas, plg, cohort-analysis

## Overview
Analyzes feature-level engagement data to identify which capabilities drive stickiness (DAU/WAU/MAU ratios), long-term retention, and expansion revenue — then builds marketing campaigns and in-product moments that accelerate adoption of your highest-value features. Use this when you need to move beyond aggregate retention metrics and pinpoint the exact product behaviors that separate churned users from power users, or when planning a feature launch marketing campaign that must drive measurable adoption.

## Quick Copy-Paste Version

You are a senior product analytics strategist specializing in B2B SaaS feature adoption and retention engineering. Analyze the following product data and deliver a complete Feature Adoption & Stickiness Intelligence report.

My product context:
- Product/service: [describe what your product does in 2 sentences]
- Business model: [Freemium / Free trial / Subscription / Usage-based]
- Monthly active users: [number]
- Core features available (list 5-10): [feature 1, feature 2, feature 3, ...]
- Current DAU/MAU ratio (stickiness): [X% or "unknown"]
- 30-day retention rate: [X% or "unknown"]
- 90-day retention rate: [X% or "unknown"]
- Top 3 features by usage: [what you know]
- Biggest drop-off point: [where users disengage]
- Analytics tool: [Amplitude / Mixpanel / PostHog / Heap / GA4 / other]

Deliver:
1. **Feature Stickiness Matrix** — rank each feature by (a) adoption breadth (% of users who tried it) and (b) adoption depth (frequency of use among adopters). Classify into: Core Habits, Growth Features, Underperformers, Hidden Gems
2. **Retention Driver Analysis** — identify which feature combinations predict 90-day retention. Which 2-3 features, when used together in week 1, have the highest correlation with retention?
3. **DAU/MAU Improvement Plan** — specific features to promote to increase daily engagement. Include 3 in-product moments and 3 triggered email campaigns with subject lines
4. **Power User Profile** — behavioral fingerprint of your top 10% most engaged users. What do they do differently in days 1-7?
5. **Feature Adoption Funnel** — for each top 3 features: awareness → trial → activation → habitual use rates with intervention points
6. **Feature Launch Marketing Template** — a 6-touch campaign (in-app + email + sales play) to drive adoption of a new or underutilized feature
7. **Expansion Revenue Triggers** — which feature usage thresholds indicate a user is ready for an upsell conversation? Provide 4 specific behavioral signals with recommended sales/marketing follow-up
8. **30-60-90 Day Adoption Acceleration Plan** — prioritized actions by week

Format all analyses in tables. Flag data assumptions clearly.

## Advanced Customizable Version

**ROLE:** You are a Principal Product Analytics Engineer with 12+ years at high-growth B2B SaaS companies (think Salesforce, HubSpot, Figma, Notion). You have deep expertise in cohort analysis, stickiness measurement, feature flagging systems, and connecting product telemetry to automated marketing and sales workflows. You've built retention models that increased NDR by 20%+ through feature adoption campaigns alone.

**COMPANY CONTEXT:**
- Company name: [Company Name]
- Product category: [e.g., revenue intelligence, project management, data pipeline, HR tech]
- Stage: [Seed / Series A / B / C / Growth / Public]
- ARR: [$X]
- Total registered users: [X]
- Monthly active users: [X]
- DAU/MAU ratio: [X%]
- Primary motion: [PLG / Sales-led / Hybrid]
- ICP: [job title, company size, industry]
- Analytics stack: [e.g., PostHog + Segment + Customer.io + Salesforce]
- Product areas/modules (list all): [area 1, area 2, area 3...]

**FEATURE INVENTORY:**
For each feature, provide what you know (leave blank if unknown):
| Feature Name | % Users Who Tried It | Avg Uses/Week (Among Adopters) | Tied to Paid Plan? | Launch Date |
|---|---|---|---|---|
| [Feature 1] | [X%] | [X] | [Yes/No] | [Date] |
| [Feature 2] | [X%] | [X] | [Yes/No] | [Date] |
[Continue for all features...]

**RETENTION DATA:**
- Day 1 retention: [X%]
- Day 7 retention: [X%]
- Day 30 retention: [X%]
- Day 90 retention: [X%]
- Top churn reasons (from surveys/interviews): [list]
- Top expansion triggers (what causes upgrades): [list]

**OBJECTIVE:** [Choose one or more]
- [ ] Identify our "must-have" features to center marketing around
- [ ] Build a feature adoption campaign for [specific feature]
- [ ] Diagnose why our DAU/MAU ratio is low ([current ratio]%) vs. benchmark ([benchmark]%)
- [ ] Create a power user segmentation to inform our PQL scoring
- [ ] Design retention-improving onboarding flows triggered by product behavior

**ANALYTICAL FRAMEWORK TO APPLY:**
Use the following frameworks in your analysis:
- **Breadth vs. Depth Matrix**: Plot each feature on a 2×2 (low/high adoption × low/high frequency)
- **Aha Moment Compression**: What sequence of actions, completed within 72 hours, has highest correlation with 90-day retention?
- **HEART Framework** (Google): Measure Happiness, Engagement, Adoption, Retention, Task success for top 3 features
- **Jobs-to-be-Done Lens**: For each power user cluster, what "job" are they hiring the product to do? How does this inform feature marketing?
- **Bowling Pin Strategy**: Which single feature, if adopted by 80%+ of users, would unlock adoption of 3+ adjacent features?

**DELIVERABLES:**

**1. Feature Stickiness Heatmap**
Create a table ranking all features across:
- Adoption Rate (% MAU who used it this month)
- Frequency Score (average uses per active user per week)
- Stickiness Contribution (estimated impact on DAU/MAU ratio)
- Retention Correlation (estimated correlation with 90-day retention)
- Expansion Correlation (correlation with plan upgrade or seat expansion)
- Classification: [Core Habit / Growth Engine / Support Feature / Underperformer / Hidden Gem]

**2. Retention Driver Regression (Simplified)**
Without raw data access, create a structured analysis:
- Identify 3 "retention-predictive feature clusters" based on product category benchmarks
- For each cluster: which user actions in days 1-3, 4-7, and 8-30 predict long-term retention?
- Benchmark against industry norms (e.g., project management SaaS: 3+ projects created in week 1 → 4× higher 90-day retention)

**3. DAU/MAU Stickiness Improvement Playbook**
- Current DAU/MAU: [X%] vs. category benchmark: [Y%]
- Top 3 features to promote for daily habit formation (with rationale)
- 5 triggered marketing campaigns to increase daily active behavior:
  For each campaign: trigger event → delay → channel → message angle → CTA → expected lift

**4. Power User Behavioral Profile**
- Top 10% user fingerprint: what do they do differently in hours 1-24, days 2-7, weeks 2-4?
- Feature combination most common among power users (the "power stack")
- 3 early behavioral signals that predict power user status by day 7
- Marketing implication: how to identify and fast-track similar users from the same account (expansion opportunity)

**5. Feature Adoption Campaign Architecture**
For your highest-priority underadopted feature, build:
- **Awareness phase**: In-app tooltip + 1 email (subject line + body outline)
- **Trial phase**: Interactive walkthrough trigger + 1 email with social proof
- **Activation phase**: Success celebration moment + 1 email showing value achieved
- **Habit phase**: Weekly digest showing feature-generated value + peer comparison nudge
- **Expansion phase**: Usage threshold trigger → sales alert or upgrade prompt

**6. Expansion Revenue Signal Dashboard**
Define 5 behavioral triggers that indicate expansion readiness:
| Signal | Threshold | Segment | Recommended Action | Owner |
|---|---|---|---|---|
| [e.g., Seats approaching limit] | [e.g., >80% seats used] | [e.g., SMB accounts] | [e.g., Auto-email + CSM alert] | [CS/Marketing] |

**7. Feature Adoption OKRs**
- Objective: Increase feature depth to drive NDR improvement
- KR1: [specific metric and target]
- KR2: [specific metric and target]
- KR3: [specific metric and target]
- Weekly tracking dashboard: 6 metrics to monitor in [analytics tool]

**8. 90-Day Feature Adoption Roadmap**
| Week | Action | Owner | Success Metric |
|---|---|---|---|
| 1-2 | [e.g., Instrument feature-level event tracking] | Engineering | All top 10 features tracked in PostHog |
| 3-4 | [e.g., Run power user interview series] | Product Marketing | 10 interviews completed, themes documented |
[Continue through week 12...]

## Example Input/Output

**Example Input:**
- Product: Claros AI — an AI writing assistant for B2B marketing teams (blog posts, email sequences, landing pages)
- Business model: Freemium → paid plans at $49/mo (Solo), $149/mo (Team)
- MAU: 12,400
- DAU/MAU ratio: 18% (below 25% benchmark for AI writing tools)
- Core features: AI Draft Generator, Brand Voice Trainer, SEO Optimizer, Team Collaboration (comments + version history), Content Calendar, Performance Tracker, Template Library (50+ templates)
- Top feature by usage: AI Draft Generator (78% MAU adoption)
- Lowest feature by usage: Performance Tracker (9% adoption), Brand Voice Trainer (14% adoption)
- 30-day retention: 41%, 90-day retention: 22%
- Churn reasons: "Not using it enough to justify cost," "Forgot it existed"

**Example Output (excerpt):**

**Feature Stickiness Matrix for Claros AI:**

| Feature | Adoption Rate | Avg Uses/Week | Stickiness Impact | Retention Correlation | Classification |
|---|---|---|---|---|---|
| AI Draft Generator | 78% | 4.2 | High | Moderate | Core Habit |
| Template Library | 54% | 2.8 | Medium | Moderate | Growth Engine |
| Brand Voice Trainer | 14% | 0.4 | **Very High (if adopted)** | **High** | **Hidden Gem ⭐** |
| SEO Optimizer | 31% | 1.1 | Medium | High | Growth Engine |
| Team Collaboration | 22% | 3.1 | High | Very High | Growth Engine |
| Content Calendar | 19% | 0.6 | High | High | Hidden Gem ⭐ |
| Performance Tracker | 9% | 0.2 | Very High (if adopted) | Very High | Underperformer |

**Key Insight:** Brand Voice Trainer has low adoption (14%) but users who adopt it have 3.1× higher 90-day retention. This is the #1 "Bowling Pin" feature — users who set up Brand Voice are 4× more likely to activate Content Calendar and 2× more likely to invite a teammate. Every onboarding flow should drive Brand Voice setup within 48 hours of signup.

**Aha Moment Sequence (predicted):** AI Draft → Brand Voice setup → SEO Optimizer on same content → 90-day retention probability jumps from 22% to ~58%

**DAU/MAU Improvement Plan — Top Campaign:**
- **Trigger:** User generates 3+ AI drafts but has never opened Brand Voice Trainer
- **Day 0:** In-app modal: "Your drafts sound great. Want Claros to always write in YOUR voice?" → CTA: "Set up Brand Voice (2 min)"
- **Day 2 (if not activated):** Email subject: "The 2-minute setup that made [similar company] 40% more productive"
- **Day 5 (if not activated):** Email subject: "Here's what your drafts could sound like with Brand Voice" → show before/after example using their actual draft language
- **Expected lift:** 14% → 35% Brand Voice adoption within 60 days; projected DAU/MAU improvement: +4-6 percentage points

**Expansion Signal — Team Collaboration:**
- Trigger: Solo plan user creates a document with a comment or share link
- Action: Auto-email to user + alert to CSM: "You're collaborating — unlock Team features"
- Subject: "Looks like you have teammates. Here's what they're missing."
- Expected conversion: 8-12% upgrade rate on this segment

## Success Metrics

A high-quality output from this prompt should achieve:
- **Feature Classification Accuracy**: All features correctly categorized with data-backed rationale (not guesses)
- **Actionability**: Every insight has a specific campaign, message, or product change tied to it
- **Quantified Uplift Estimates**: DAU/MAU improvement target, retention improvement %, and revenue impact from each initiative
- **Specificity**: Campaign triggers use exact feature event names, not generic descriptions
- **Timeline Realism**: 90-day roadmap accounts for engineering dependencies and team bandwidth
- **Benchmark Context**: All metrics compared to industry category benchmarks (AI tools, project management, data tools, etc.)

Discard the output if it: gives generic advice like "increase feature awareness," fails to rank features quantitatively, or doesn't connect feature adoption to specific revenue outcomes.

## Related Prompts

- [`../../05_Analytics-&-Performance/Product-Analytics-&-Activation/Product-Analytics-&-Activation-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Product-Analytics-&-Activation/Product-Analytics-&-Activation-Intelligence-Engine.md) — PQL scoring and activation milestone design
- [`../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/Cohort-Based-LTV-&-Revenue-Retention-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/Cohort-Based-LTV-&-Revenue-Retention-Intelligence-Engine.md) — cohort-based LTV and revenue retention
- [`../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Freemium-Conversion-&-PQL-Nurture-Automation-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Freemium-Conversion-&-PQL-Nurture-Automation-Engine.md) — converting free users to paid via product signals
- [`../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Product-Led-Growth-PLG-Flywheel-&-Viral-Loop-Design-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Product-Led-Growth-PLG-Flywheel-&-Viral-Loop-Design-Engine.md) — designing viral loops powered by product behavior

## Integration Tips

**Amplitude / Mixpanel / PostHog:**
- Build a "Feature Stickiness" chart: set X-axis = % of MAU who used each feature, Y-axis = avg frequency among users who used it. Screenshot and paste the image URL into the prompt with "Analyze this chart" to get AI interpretation.
- Create a Compass chart (Amplitude) or Funnel report (Mixpanel) for your Aha Moment sequence and paste the numbers into the Advanced prompt.

**HubSpot / Marketo:**
- Map expansion signals to workflow triggers: create a contact property "Feature Adoption Score" and use the behavioral signals from this prompt to set score thresholds that enroll contacts into upsell sequences.
- For each triggered campaign in the output, create a HubSpot Workflow: Enrollment trigger = product event (via Segment/API) → delay → email send.

**Intercom / Pendo / Appcues:**
- Use the in-product message recommendations directly in Intercom Series or Pendo Guides. The prompt outputs copy-ready message text and trigger logic.
- Pendo: Create a Feature Adoption dashboard using the Feature Stickiness Matrix as your KPI template.

**Segment:**
- Create a Segment Trait for "Power User Fingerprint Score" based on the behavioral signals identified. Feed this into HubSpot, Salesforce, and Intercom simultaneously.
- Build a Segment Audience for "Hidden Gem Feature Non-Adopters" and sync to all downstream tools for coordinated campaigns.

**Salesforce / Gainsight:**
- Add expansion signals as Gainsight Health Score rules or Salesforce Account score fields.
- Create a Salesforce report: "Accounts with expansion signal triggered in last 7 days" for weekly CSM review.

**Notion / Confluence:**
- Paste the 90-day roadmap output directly into a Notion database with checkboxes. Tag each action with owner, week, and metric.

## Troubleshooting

**Problem: "I don't have feature-level tracking — I only have page views and login counts."**
Solution: Use the Quick Copy-Paste version with estimated or hypothetical data to get the framework, then treat it as your instrumentation roadmap. The prompt will output the events you SHOULD be tracking. Use this list as your ticket to your engineering team. Prioritize instrumenting the top 5 events it identifies.

**Problem: "The output is too generic — it doesn't know our specific features well enough."**
Solution: In the Advanced version, fill in the Feature Inventory table as completely as possible. Even rough estimates (e.g., "maybe 20% of users have tried this") give the model enough signal to differentiate. Also add 2-3 verbatim quotes from customer interviews or churn surveys — qualitative data dramatically improves specificity.

**Problem: "I got feature adoption campaigns but they're all email — I need in-product messages too."**
Solution: Add to the prompt: "For each campaign touchpoint, provide both an email version AND an in-app version (tooltip, modal, or banner). Format in-product messages for Intercom/Pendo/Appcues with: message copy (max 80 words), placement (where in the UI), trigger condition, and dismiss/CTA buttons."

## Version History
- v1.0: Initial creation (auto-generated)
