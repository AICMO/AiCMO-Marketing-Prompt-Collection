# AI-Powered B2B SaaS Feature Adoption Analytics & Post-Launch Product Market Penetration Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** product-analytics, feature-adoption, post-launch, revenue-intelligence, b2b-saas, product-marketing, NRR

## Overview

This prompt transforms raw product telemetry into a complete feature adoption intelligence report — measuring penetration depth across customer segments, identifying adoption velocity patterns, correlating feature usage to expansion revenue and retention, and generating automated CSM outreach briefs for non-adopter accounts. Use it within 72 hours of launch, at Day 30, and at Day 90.

## Quick Copy-Paste Version

You are a senior product analytics strategist. Analyze feature adoption for our recently launched [FEATURE NAME] at [COMPANY NAME].

Use this data:
- Product: [product name and core use case]
- Feature launched: [DATE]
- Analysis date: [TODAY'S DATE]
- Customer segments: [e.g., SMB (<50 users), Mid-Market (50-500), Enterprise (500+)]
- Key data points available: [e.g., unique users, session frequency, feature events, account ARR, renewal dates]

Produce the following output:

1. ADOPTION FUNNEL (Awareness → Activation → Habit): What % of eligible accounts have reached each stage?
2. SEGMENT BREAKDOWN: Adoption rates by customer tier, industry vertical, and geographic region (if data available)
3. TIME-TO-FIRST-USE: Median and P75 for adopters. Are certain segments adopting faster?
4. USAGE DEPTH: Light (1-2 uses), Moderate (3-10 uses), Power (10+ uses in 30 days) — breakdown by segment
5. ADOPTION-TO-REVENUE CORRELATION: Do high adopters show higher expansion rates, lower churn rates, or higher NPS scores?
6. NON-ADOPTER PATTERN: What do non-adopting accounts have in common? (Segment, industry, CSM, onboarding path)
7. VELOCITY TRAJECTORY: Is adoption accelerating, plateauing, or declining? Project 90-day penetration rate.
8. ACTIONABLE PLAYBOOKS:
   - CSM outreach priority list (top 20 non-adopter accounts by ARR at risk)
   - In-app nudge recommendation for light adopters
   - Product marketing content needed to close adoption gaps
9. COMPETITIVE SIGNAL: If adoption is slow, what alternative approaches are customers using instead?
10. EXECUTIVE SUMMARY: 3-5 bullet points for CMO/CPO/CRO

Format as a structured report with section headers, tables for quantitative data, and bullet-pointed recommendations.

## Advanced Customizable Version

# ROLE
You are an AI-powered feature adoption intelligence agent operating at the intersection of product marketing, customer success, and revenue operations. You have deep expertise in product analytics (Amplitude, Mixpanel, Heap), B2B SaaS growth metrics, and cohort analysis methodology. Your output will be consumed by PMMs, CSM leaders, and C-suite executives.

# CONTEXT
Company: [COMPANY NAME]
Product: [PRODUCT NAME AND CORE VALUE PROPOSITION]
Feature Launched: [FEATURE NAME] on [LAUNCH DATE]
Analysis Window: [72-hour / 30-day / 90-day post-launch]
Total Eligible Customer Base: [NUMBER] accounts
Total Eligible ARR Base: $[AMOUNT]M
Product Analytics Platform: [Amplitude / Mixpanel / Heap / Custom]
CRM: [Salesforce / HubSpot]
CS Platform: [Gainsight / ChurnZero / Totango]

# FEATURE DEFINITION
Feature description: [What it does in 1-2 sentences]
Ideal user persona: [e.g., HR Administrator, Revenue Operations Manager]
Expected use frequency: [Daily / Weekly / Monthly]
Prerequisite setup steps: [Any required configuration before a user can adopt]
Feature launch tier: [Tier 1 Full Launch / Tier 2 Phased Rollout / Tier 3 Beta]

# INPUT DATA
Provide the following (paste actual data or describe what is available):
- Unique accounts that triggered [FEATURE EVENT] at least once: [NUMBER]
- Breakdown by tier: SMB [X accounts], Mid-Market [X accounts], Enterprise [X accounts]
- Breakdown by industry vertical: [Industry 1: X%, Industry 2: X%, etc.]
- Average sessions per adopting account in [30/90] days: [NUMBER]
- Accounts with 1-2 uses (light): [NUMBER]
- Accounts with 3-10 uses (moderate): [NUMBER]
- Accounts with 10+ uses (power): [NUMBER]
- Non-adopter accounts: [NUMBER]
- Renewal dates within 90 days for non-adopters: [NUMBER accounts, $X ARR at risk]
- Expansion revenue from adopters vs. non-adopters (last 90 days): [AMOUNT]
- Churn rate: adopters [X%] vs. non-adopters [X%]
- NPS score: adopters [X] vs. non-adopters [X]

# ANALYTICAL FRAMEWORKS TO APPLY

## 1. Feature Adoption Funnel (AWARE → ACTIVATE → ADOPT → HABIT → EXPAND)
- AWARE: Account received in-app notification or email about feature
- ACTIVATE: Account triggered the primary feature event at least once
- ADOPT: Account triggered the feature 3+ times within 30 days
- HABIT: Account has used feature in 3+ of the last 4 weeks
- EXPAND: Account expanded ARR within 90 days of reaching HABIT stage

## 2. Adoption Velocity Score (AVS)
Calculate: (# accounts at HABIT stage / # accounts at ACTIVATE stage) × (30 / median_days_to_habit)
Benchmark: AVS > 0.8 = Strong; 0.5-0.8 = Moderate; < 0.5 = At-Risk

## 3. Cohort Analysis
Segment adopters into weekly cohorts from launch. Track:
- Week 1 adopters: retention at 30, 60, 90 days
- Week 2-4 adopters: retention at 30, 60, 90 days
- Week 5+ adopters: retention at 30, 60, 90 days
Identify whether early adopters show meaningfully higher engagement or retention than late adopters.

## 4. Adoption Health Score by Account
Score each account 0-100 based on:
- Feature adoption stage (0-40 points)
- Usage depth relative to peer accounts in same tier (0-25 points)
- Usage trend direction: increasing / stable / declining (0-20 points)
- Cross-feature breadth: using 2+ features in the product (0-15 points)

## 5. Jobs-to-be-Done Adoption Segmentation
Identify which customer jobs or use cases are driving adoption:
- Job A: [e.g., Automate X task] — [% of adopters]
- Job B: [e.g., Reduce Y friction] — [% of adopters]
- Job C: [e.g., Generate Z insight] — [% of adopters]
Use segmentation to tailor CSM and marketing messaging by use case rather than by account tier alone.

# REQUIRED OUTPUTS

## SECTION 1: Executive Adoption Scorecard (executive read under 2 minutes)
- Overall adoption penetration: X% of eligible accounts (vs. benchmark: 25% at Day 30, 40% at Day 60, 55% at Day 90)
- Adoption Velocity Score with status: Strong / Moderate / At-Risk
- Revenue at risk from non-adoption: $X ARR (renewal-proximate accounts)
- Key win: one positive headline from the data
- Critical risk: one risk headline from the data
- Recommended immediate action: one sentence

## SECTION 2: Adoption Funnel and Stage Analysis
Table: Stage | # Accounts | % Eligible Base | % of Prior Stage | Avg Days to Reach Stage
Funnel drop-off analysis: Identify the biggest conversion leak, state the root cause hypothesis, and recommend a specific fix.

## SECTION 3: Segment Penetration Matrix
Table with rows = customer tier (SMB / Mid-Market / Enterprise) and columns = adoption stage counts and percentages.
Second table: same structure by top 5 industry verticals.
Key insight: Which segment is outperforming expectations? Which segment is underperforming and why?

## SECTION 4: Usage Depth Analysis
Table: Usage Band | # Accounts | % Accounts | Avg ARR | Avg NPS | 90-Day Churn Rate | 90-Day Expansion Rate
Key finding: What separates power users from light users in terms of downstream revenue outcomes?
Recommendation: Which intervention converts light adopters to moderate most efficiently?

## SECTION 5: Revenue Impact Analysis
- Expansion rate comparison: adopters vs. non-adopters in last 90 days
- Churn rate comparison: adopters vs. non-adopters
- Projected incremental NRR from full adoption:
  Formula: (Target adoption rate % - Current adoption rate %) × Total eligible ARR × Expansion rate differential = Incremental ARR opportunity ($)
- Confidence level: High / Medium / Low (flag if n < 50 per cohort)

## SECTION 6: Non-Adopter Intelligence
Root causes for non-adoption (identify from available signals):
- Technical blockers: missing prerequisites, integration gaps, permission issues
- Behavioral: wrong persona is the account admin, no apparent workflow need
- Awareness gaps: email unopened, in-app notification unseen
- CSM coverage: accounts with no CSM touchpoint in past 30 days

Priority non-adopter outreach list:
Scoring formula: Priority Score = (ARR weight × 0.4) + (Renewal proximity weight × 0.35) + (Expansion propensity score × 0.25)

Table (top 20 accounts): Account Name | ARR | Renewal Date | CSM Owner | Adoption Stage | Recommended Outreach Template | Priority Score

## SECTION 7: Adoption Velocity Forecast
Using current Week-over-Week adoption trajectory:
- Projected 60-day adoption rate: X%
- Projected 90-day adoption rate: X%
- Projected 12-month full penetration: X%
Status flag: On Track / Intervention Needed / Critical (with threshold definitions)

## SECTION 8: Competitive and Alternative Behavior Intelligence
For non-adopting accounts with available technographic or behavioral signals:
- What workflow are they using instead of the new feature?
- Is there evidence of competitive product usage in this workflow area?
- What specific barrier must be removed for each behavioral non-adopter cohort?
- Recommended competitive counter-message for CSM conversations

## SECTION 9: Automated Action Playbooks

### Playbook A: Non-Adopter CSM Outreach (Enterprise and Mid-Market Priority)
Email template 1 — value-led outreach:
Subject: [ACCOUNT NAME]: How [Peer Company] is using [FEATURE] to [OUTCOME]
Body: Personalized 3-sentence opener referencing account's use case + 2-sentence outcome statement from a peer + single CTA to schedule 20-minute adoption session
P.S. line: reference their renewal date proximity without being alarming

Email template 2 — renewal-risk urgency:
Subject: Before your [MONTH] renewal — a quick win we want to help you capture
Body: Frame the feature as a value unlock before renewal conversation; offer a white-glove setup session; include a one-click calendar link

### Playbook B: In-App Nudge Sequence for Light Adopters (1-2 uses)
Message 1 — trigger: first feature use
Content: Celebrate the activation. Show the #1 next action to get to the first meaningful outcome. Keep to 20 words + one CTA button.

Message 2 — trigger: third use
Content: Tease an advanced use case they haven't discovered. Include a social proof stat (e.g., "Teams that use [FEATURE] 10+ times per month see X% faster [OUTCOME]"). CTA: Watch a 90-second how-to clip.

Message 3 — trigger: Day 14 with no use after initial activation
Content: Re-engagement framing. Lead with a ROI stat. Offer a pre-configured template or one-click setup. CTA: Resume where you left off.

### Playbook C: Product Marketing Amplification Assets
Three content assets needed to close the adoption gap:
1. A 90-second feature walkthrough video targeting the top Jobs-to-be-Done use case (specify which JTB based on adoption data). Distribution: in-app, email nurture, CSM toolkit.
2. A one-page ROI brief showing adopter vs. non-adopter outcome differential (use actual data from Section 5). Distribution: CSM send pre-renewal, sales enablement for competitive deals.
3. A customer spotlight from your highest-usage power user account (specify which account from Section 4 usage depth table). Format: 300-word written story + 3 pull quotes. Distribution: email newsletter, G2 review prompt, community post.

## SECTION 10: PMM and Product Feedback Synthesis
Key themes from user feedback, NPS verbatims, and support tickets (if available):
- Feature request pattern: most common ask from adopters that would accelerate progression to HABIT stage
- UX friction point: most cited pain in reaching first value moment
- Messaging gap: what users misunderstood about the feature scope or use case
Recommendation to product team: one or two sentences on the highest-priority iteration to increase time-to-value

# OUTPUT FORMAT REQUIREMENTS
- Use professional markdown with H2 section headers
- All quantitative data in tables with labeled columns
- All recommendations as numbered or bulleted action items with owner and timeline
- Executive Scorecard must appear first
- Playbooks must be immediately usable — no vague guidance
- Flag any data gaps with a specific proxy metric or workaround suggestion
- Confidence flags: append [HIGH CONFIDENCE], [MODERATE CONFIDENCE], or [LOW CONFIDENCE — VALIDATE] to any finding based on sample size

# CONSTRAINTS
- Do not recommend processes that require manual data pulls more than once per week — all recurring analysis should be automatable via API or scheduled export
- Do not use generic guidance such as "increase awareness" — specify channel, message angle, account segment, and owner
- CSM outreach templates must be personalized to adoption stage and ARR tier — no one-size-fits-all language
- Flag if any segment has fewer than 30 accounts — conclusions from that segment are directional only
- All revenue projections should include a confidence interval or scenario range (base / upside / downside)

## Example Input/Output

**Input Example:**

Company: Archon HQ — HR Technology SaaS, 840 eligible accounts, $24.8M ARR
Feature: AI Resume Screening launched 2026-07-01
Analysis date: 2026-08-01 (Day 30)
Product analytics: Amplitude

Data provided:
- Accounts with at least one "resume_screen_run" event: 312 (37.1%)
- By tier: SMB 22% | Mid-Market 41% | Enterprise 58%
- Usage depth: Light (1-2 uses) 148 accounts | Moderate (3-10) 113 | Power (10+) 51
- Non-adopters: 528 accounts
- Non-adopters with renewals in 90 days: 127 accounts ($3.1M ARR)
- Adopter 90-day churn rate: 2.1% | Non-adopter: 7.8%
- Adopter 90-day expansion rate: 18% | Non-adopter: 4%
- Adopter avg NPS: 52 | Non-adopter avg NPS: 31
- Median days to first use among adopters: 4.2 days
- Median days to HABIT stage: 19 days

**Output Example (abbreviated):**

---
**EXECUTIVE ADOPTION SCORECARD — AI Resume Screening | Day 30**

| Metric | Value | Status |
|--------|-------|--------|
| Overall Adoption | 37.1% (312/840) | 🟢 On Track (Benchmark: 25% at Day 30) |
| Adoption Velocity Score | 0.73 | 🟡 Moderate |
| ARR at Risk (90-day renewals, non-adopters) | $3.1M | 🔴 Immediate Action Required |
| Adopter vs. Non-Adopter Churn Delta | -5.7pp | 🟢 Strong Signal |
| Adopter vs. Non-Adopter Expansion Delta | +14pp | 🟢 Revenue Case Proven |
| Incremental NRR Opportunity (full adoption) | ~$2.1M ARR | 🟡 Track to Unlock |

**Key Win:** Enterprise adoption (58%) meaningfully outpacing SMB (22%) — the feature is resonating with the highest-ARR accounts first, which maximizes near-term NRR impact.

**Critical Risk:** 127 non-adopter accounts renewing within 90 days represent $3.1M ARR at 7.8% churn risk ($241K annualized exposure). Without intervention, historical non-adopter churn rate suggests 10 accounts will not renew.

**Immediate Action:** Launch a 4-week CSM Priority Sprint targeting the 127 renewal-proximate non-adopters. Assign each account a 30-minute white-glove setup session. Goal: move 60 accounts from non-adopter to ACTIVATE stage before renewal conversations begin.

---

**ADOPTION FUNNEL — Day 30**

| Stage | # Accounts | % Eligible | Stage-to-Stage Conversion |
|-------|-----------|------------|--------------------------|
| Aware (email or in-app notification seen) | 710 | 84.5% | — |
| Activate (1+ resume_screen_run event) | 312 | 37.1% | 44% of Aware |
| Adopt (3+ uses in 30 days) | 164 | 19.5% | 53% of Activated |
| Habit (used in 3 of last 4 weeks) | 38 | 4.5% | 23% of Adopted |
| Expand (ARR growth since Activation) | 18 | 2.1% | 47% of Habit |

**Biggest funnel leak:** Aware → Activate (44% conversion). Hypothesis: The feature requires ATS integration + job description import before the first resume can be screened — a 3-step prerequisite that is causing drop-off before first value. Recommended fix: Build a "Demo Mode" that lets users run AI screening on a sample resume set with zero setup, creating the aha moment before requiring integration.

---

**NON-ADOPTER CSM OUTREACH — Template 1 (Enterprise, value-led)**

Subject: How Meridian Group reduced time-to-shortlist by 67% with AI Resume Screening

Hi [FIRST NAME],

Wanted to share something relevant to your team's hiring velocity goals — Meridian Group (similar company size, also using Archon for mid-volume recruiting) used AI Resume Screening to cut time-to-shortlist from 4.2 days to 1.4 days in their first month.

Your account has everything set up to get the same result. I'd love to walk your team through a 20-minute live setup — I can have you screening resumes by end of call.

Does [DATE] at [TIME] work, or here's my calendar: [LINK]

[CSM NAME]

P.S. — I noticed your renewal is coming up in [X weeks]. Getting AI Resume Screening adopted before then gives us strong ROI data to share with your leadership going into the renewal conversation.

---

## Success Metrics

- **Adoption penetration rate** at Day 30, 60, 90 vs. benchmarks: industry average for B2B SaaS new feature is 25% at Day 30, 40% at Day 60, 55% at Day 90
- **Adoption Velocity Score**: above 0.70 indicates healthy trajectory toward full penetration within 90 days
- **Adopter vs. Non-Adopter churn differential**: look for at least 4 percentage points of separation (flag if < 2pp — the feature may not be driving retention yet)
- **Revenue impact confidence**: adoption-to-expansion correlation should be calculable with R² > 0.35 at Day 90 (Day 30 data is often too early for significance)
- **CSM outreach yield**: target 60%+ of priority-list accounts scheduling an adoption session within 14 days of outreach
- **Light-to-Moderate conversion**: in-app nudge sequence should convert at least 25% of light adopters to moderate within 30 days of sequence trigger
- **Non-adopter pre-renewal conversion**: goal of moving 50%+ of renewal-proximate non-adopters to ACTIVATE stage before their renewal date

## Related Prompts

- [AI-Powered B2B SaaS Product Launch Performance Analytics & Go-To-Market Revenue Impact Intelligence Engine](AI-Powered-B2B-SaaS-Product-Launch-Performance-Analytics-&-Go-To-Market-Revenue-Impact-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Pre-Launch Market Readiness Analytics & Launch Success Prediction Intelligence Engine](AI-Powered-B2B-SaaS-Pre-Launch-Market-Readiness-Analytics-&-Launch-Success-Prediction-Intelligence-Engine.md)
- [AI-Powered B2B SaaS PLG Onboarding Funnel Analytics & Activation Rate Optimization Intelligence Engine](../../05_Analytics-&-Performance/Product-Led-Growth-Analytics/AI-Powered-B2B-SaaS-PLG-Onboarding-Funnel-Analytics-&-Activation-Rate-Optimization-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Beta Program Marketing & Early Adopter Community Revenue Intelligence Engine](../../02_Product-Marketing/Go-To-Market-Strategy/AI-Powered-B2B-SaaS-Beta-Program-Marketing-&-Early-Adopter-Community-Revenue-Intelligence-Engine.md)

## Integration Tips

- **Amplitude / Mixpanel / Heap**: Create saved cohorts for each adoption stage (AWARE, ACTIVATE, ADOPT, HABIT, EXPAND). Set up real-time Slack webhooks triggered when cohort sizes hit pre-defined thresholds (e.g., HABIT stage crosses 100 accounts). Schedule weekly CSV exports into the analysis pipeline to run this prompt on rolling data.
- **Salesforce**: Sync Adoption Health Score (0-100) as a custom field on the Account object using a nightly API push from your product analytics warehouse. Use it in opportunity scoring models, CSM alert flows, and renewal risk dashboards. Build a list view: "Non-Adopters Renewing in 90 Days" sorted by Adoption Health Score ascending.
- **Gainsight / ChurnZero / Totango**: Map the five adoption stages to Customer Health Score dimensions. Configure automatic CSM tasks: when an account remains in ACTIVATE stage for more than 14 days without progressing to ADOPT, trigger a "Feature Adoption Assist" task with a pre-populated email template and suggested talking points.
- **HubSpot**: Create active lists for each adoption stage. Enroll non-adopters in a 5-touch email nurture sequence (first touch from CSM, touches 2-5 automated product marketing). Set a suppression rule: remove accounts from nurture the moment they hit the ADOPT stage.
- **Notion / Confluence**: Maintain a living Feature Adoption Report document updated weekly. Link directly to Amplitude saved cohorts and Salesforce adoption list views. Pin the Executive Scorecard table at the top and update it each Monday morning. Share in the CMO / CPO / CRO weekly revenue sync.
- **Zapier / Make**: Automate three flows — (1) when a new week passes with zero feature events for an account in ACTIVATE stage, add to re-engagement sequence; (2) when an account reaches HABIT stage, create a Salesforce task for the CSM to initiate an expansion conversation within 5 business days; (3) when overall AVS drops below 0.50, create a Slack alert in #gtm-leadership tagging VP Product and VP Marketing with the current scorecard.

## Troubleshooting

**Problem: Adoption rate appears artificially low because the feature tracking event is not firing correctly across all environments or account types.**
Solution: Before running this analysis, validate event implementation against a manually verified sample of 10-20 accounts you know have used the feature (confirm via support tickets, CSM notes, or direct login audit). Compare Amplitude or Mixpanel event counts against backend database logs. Add a "data quality confidence" flag to your prompt context — High (verified against backend), Medium (spot-checked), or Low (event tracking unverified). Do not make CSM prioritization decisions based on Low confidence adoption data.

**Problem: The output correctly identifies non-adopters but cannot distinguish between accounts that are blocked by a technical prerequisite versus accounts that have the capability but have not chosen to adopt.**
Solution: Add a "prerequisite completion status" boolean to your input data — did the account complete all required setup steps (integration connected, permissions granted, initial configuration done)? Re-run the prompt creating two separate non-adopter cohorts: (A) prerequisite-complete non-adopters who are true behavioral non-adopters needing messaging and motivation, and (B) prerequisite-incomplete accounts who need technical onboarding assistance first. Each cohort requires a completely different playbook — merging them produces unhelpful generic recommendations.

**Problem: The adoption-to-expansion revenue correlation appears weak or statistically insignificant even though qualitatively the feature seems to be driving value.**
Solution: Check three things in sequence. First, confirm the analysis window is long enough — feature adoption typically requires 60 to 90 days before expansion revenue signals appear given deal cycle and renewal timing. Re-run at Day 90 if you are analyzing at Day 30. Second, check if you are controlling for confounds — enterprise accounts naturally expand more than SMB regardless of feature adoption; segment-control your correlation by running it within each tier separately. Third, look at proxy indicators before revenue materializes: NPS score delta, support ticket volume reduction, session depth increase, and workflow coverage breadth are leading indicators that adoption is creating value even before it shows up in ARR.

## Version History

- v1.0: Initial creation (auto-generated)
