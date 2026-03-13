# Voice of Customer (VoC) Synthesis & Product Insight Intelligence Engine - Automated Customer Intelligence Platform

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** voc, customer-intelligence, sentiment-analysis, product-marketing, analytics, automation

## Overview

Aggregates and synthesizes customer feedback from NPS surveys, CSAT scores, support tickets, G2/Capterra reviews, win/loss interviews, and churn surveys into structured product and marketing intelligence — completely automatable with AI agents, no manual tagging or analysis required.

## Quick Copy-Paste Version

You are a senior customer intelligence analyst. Analyze the following customer feedback data and produce a comprehensive VoC intelligence report.

FEEDBACK DATA:
[Paste raw feedback: NPS responses, support tickets, reviews, interview transcripts, churn survey responses]

COMPANY CONTEXT:
- Product: [SaaS platform / product name]
- Segment focus: [SMB / Mid-market / Enterprise]
- Time period: [Last 30/60/90 days]

Produce a structured report with:

1. SENTIMENT BREAKDOWN
- Overall sentiment score (0-100) with trend vs. prior period
- Sentiment by customer segment, tenure, and plan tier
- Top 5 positive themes with representative verbatim quotes
- Top 5 negative themes with representative verbatim quotes

2. JOBS-TO-BE-DONE ANALYSIS
- Primary jobs customers are hiring the product to do (rank by frequency)
- Underserved jobs where product falls short (churn signal)
- New jobs emerging in feedback not currently served

3. FEATURE & PRODUCT INTELLIGENCE
- Most-requested features (ranked by frequency + customer segment)
- Friction points causing support escalations or churn risk
- Competitive mentions and displacement threats

4. MARKETING & MESSAGING INTELLIGENCE
- Language customers use to describe value (direct quote mining for copy)
- Proof points and outcomes customers cite (for case studies and testimonials)
- Objections surfaced (for sales enablement and FAQ content)

5. CHURN RISK SIGNALS
- Early warning phrases and sentiment patterns that predict churn
- Segments or cohorts showing elevated dissatisfaction
- Recommended intervention actions per segment

6. EXECUTIVE SUMMARY
- 3 strategic recommendations for product team
- 3 strategic recommendations for marketing team
- 3 strategic recommendations for customer success team
- Priority score (High/Medium/Low) for each recommendation

Format all findings as structured JSON + human-readable summary. Flag any quotes suitable for public testimonials.

## Advanced Customizable Version

ROLE:
You are a Chief Customer Intelligence Officer with 15+ years of experience running VoC programs at B2B SaaS companies scaling from $10M to $500M ARR. You specialize in transforming unstructured customer feedback into product roadmap decisions, marketing messaging, and churn prevention programs.

OBJECTIVE:
Conduct a comprehensive Voice of Customer synthesis across all feedback channels for [COMPANY_NAME], a [DESCRIBE_PRODUCT] serving [TARGET_SEGMENT] customers. Produce board-ready intelligence that drives decisions across product, marketing, customer success, and sales.

COMPANY CONTEXT:
- Product: [PRODUCT_NAME] — [one-line description]
- Pricing tiers: [Starter / Growth / Enterprise at $X/$Y/$Z per month]
- Customer segments: [SMB (1-50 employees) / Mid-market (51-500) / Enterprise (500+)]
- Core use case: [primary job-to-be-done]
- Key competitors: [Competitor A, Competitor B, Competitor C]
- Current NPS baseline: [score] (industry benchmark: [benchmark])
- Analysis period: [START_DATE] to [END_DATE]

INPUT DATA SOURCES (include all available):
---NPS RESPONSES (Promoters/Passives/Detractors)---
[Paste raw NPS open-ends or upload CSV]

---CSAT / SUPPORT TICKETS---
[Paste top 50 support tickets by volume, escalations, or resolution time]

---G2 / CAPTERRA / TRUSTRADIUS REVIEWS---
[Paste review text with star ratings and reviewer company size]

---WIN/LOSS INTERVIEW TRANSCRIPTS---
[Paste transcripts or summaries from sales win/loss debriefs]

---CHURN SURVEY RESPONSES---
[Paste exit survey data from churned customers, last 90 days]

---CUSTOMER INTERVIEW NOTES---
[Paste notes from QBRs, customer advisory board sessions, or CS check-ins]

ANALYSIS FRAMEWORK:

**Phase 1: Thematic Clustering (Jobs-to-be-Done + Kano Model)**
Apply Jobs-to-be-Done framework to classify each piece of feedback:
- Functional jobs (what they're trying to accomplish)
- Emotional jobs (how they want to feel)
- Social jobs (how they want to be perceived)

Apply Kano Model to feature requests:
- Basic needs (must-have, causes dissatisfaction if absent)
- Performance needs (more = better satisfaction)
- Delighters (unexpected, drives loyalty)
- Indifferent (nice-to-have, no real impact)
- Reverse (some customers hate it)

**Phase 2: Sentiment & Signal Analysis**
- Sentiment scoring per theme: -100 (very negative) to +100 (very positive)
- Frequency × Intensity matrix: high-freq/high-intensity = critical priority
- Churn predictor language: identify phrases statistically correlated with churn
- Expansion signal language: identify phrases correlated with upsell/advocacy

**Phase 3: Competitive Intelligence Extraction**
- Extract all competitor mentions (direct and indirect)
- Categorize by: reason for switching TO us / reason for switching FROM us / features compared
- Identify battle card gaps and objection handling needs

**Phase 4: Message Mining**
Extract verbatim customer language for:
- Value proposition validation (how they describe the benefit)
- Outcome language (specific metrics, results, time savings they cite)
- Role-specific language (how a CMO talks about it vs. a RevOps analyst)
- Objection language (for preemptive FAQ and sales enablement)

OUTPUT REQUIREMENTS:

**Section 1: Executive Dashboard (Board-Ready)**
{
  "reporting_period": "",
  "overall_sentiment_score": 0,
  "sentiment_trend": "+/- X points vs prior period",
  "nps_score": 0,
  "top_3_strengths": [],
  "top_3_critical_issues": [],
  "churn_risk_index": "Low/Medium/High",
  "expansion_opportunity_score": 0
}

**Section 2: Theme Intelligence Matrix**
For each of the top 10 themes, provide:
- Theme name and description
- Frequency (# mentions, % of total feedback)
- Sentiment score
- Representative verbatim quotes (3 per theme)
- Affected segments
- Recommended owner (Product / Marketing / CS / Sales)
- Priority: Critical / High / Medium / Low

**Section 3: Jobs-to-be-Done Map**
Primary JTBD ranking with:
- Job statement ("When I [situation], I want to [motivation], so I can [outcome]")
- Frequency rank
- Satisfaction score (how well product serves this job)
- Competitive vulnerability (are competitors better at this job?)

**Section 4: Marketing Intelligence Pack**
A. Value proposition language (direct customer quotes, ranked by resonance)
B. Outcome proof points with specifics (save X hours, reduce Y cost by Z%)
C. Testimonial candidates (flag quotes suitable for public use)
D. SEO/content themes (topics customers research before buying)
E. Objections to address in content and sales collateral

**Section 5: Product Intelligence Pack**
A. Feature request ranked backlog (Kano-classified)
B. Friction map (where users get stuck, with support ticket evidence)
C. Integration requests (what tools customers want connected)
D. Competitive feature gaps (what competitors do that we don't)

**Section 6: Churn Intelligence Pack**
A. Churn prediction language library (phrases that appear in churned customer feedback)
B. At-risk segments (cohort + tenure + plan tier combos showing elevated risk)
C. Intervention playbook: specific actions for CS to take per risk signal

**Section 7: Recommended Actions**
For each recommendation, provide:
- Team owner
- Specific action
- Expected impact
- Implementation difficulty (Easy / Medium / Hard)
- Priority (P0 / P1 / P2)
- Success metric

CONSTRAINTS:
- Use only the provided data — do not hallucinate feedback that wasn't given
- Preserve exact verbatim language in quotes (do not paraphrase customer words)
- Flag any themes with insufficient data (n < 5 mentions) as "Low confidence"
- All recommendations must be actionable within 30 days without additional budget
- Separate out B2B Enterprise feedback from SMB feedback wherever segment data is available

## Example Input/Output

**Company:** Streamline.io — a B2B project management SaaS for marketing agencies, 3 pricing tiers ($49/$149/$399/mo), 850 customers

**Sample Input Feedback (abbreviated):**
- NPS Detractor: "The reporting is terrible. I spend 3 hours every Friday building reports my clients expect. Your competitors have one-click client reporting."
- G2 Review (3 stars): "Love the task management but the time tracking is buggy. Keeps resetting. We almost lost a client because of billing errors."
- Churn Survey: "Switched to Teamwork. They have a dedicated client portal. Our clients complained they couldn't see project status without us sending screenshots."
- NPS Promoter: "Finally, a tool that gets how agencies work. The retainer tracking alone saves me 4 hours a month. Worth every penny."
- Win interview: "We chose you over Asana because your agency templates were ready out of the box. Our team was up and running in a day."

**Sample Output (abbreviated):**

{
  "overall_sentiment_score": 52,
  "sentiment_trend": "-8 points vs Q3",
  "top_3_strengths": [
    "Agency-specific templates (fast onboarding)",
    "Retainer tracking (tangible time savings)",
    "Task management UX"
  ],
  "top_3_critical_issues": [
    "Client reporting (manual, no automation) — HIGH CHURN RISK",
    "Time tracking bugs causing billing errors — CRITICAL",
    "No client portal (competitive gap vs Teamwork)"
  ],
  "churn_risk_index": "High"
}

**Theme: Client Reporting**
- Frequency: 34% of all negative feedback
- Sentiment: -72 (highly negative)
- Kano Classification: Basic Need (absence causes active dissatisfaction)
- Competitive threat: Teamwork and Reportei mentioned as alternatives
- Verbatims: "3 hours every Friday," "clients expect," "one-click"
- Recommended action: Product P0 — ship automated client report export within 60 days

**Marketing Intelligence Extract:**
- Value language to use in ads: "built for how agencies actually work"
- Proof point: "saves 4 hours/month on retainer tracking" (use in landing page)
- Testimonial candidate: "Finally a tool that gets how agencies work" (5-star NPS promoter, approved for use)
- Content gap: Create SEO content targeting "client reporting for marketing agencies" (high-frequency pain point with no current content coverage)

## Success Metrics

- Theme coverage: ≥80% of raw feedback should map to a named theme (low % = prompt needs more context)
- Actionability: Every critical theme should have a named owner and 30-day action
- Verbatim fidelity: Quotes in output should match source data exactly
- Cross-segment consistency: Separate SMB vs. Enterprise intelligence where applicable
- Churn signal validation: Compare predicted at-risk language against actual churned customer cohort — target >70% match rate
- Marketing team usability: At least 3 copy-ready verbatims per value proposition theme
- Time to insight: Full synthesis from raw data paste to complete report in <25 minutes

## Related Prompts

- `../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Social-Listening-Brand-Intelligence-Engine.md`
- `../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Customer-Segmentation-Behavioral-Targeting-Engine.md`
- `../../02_Product-Marketing/Customer-&-Market-Research/Customer-Advisory-Board-CAB-Intelligence-&-Program-Management-Engine.md`
- `../../02_Product-Marketing/Positioning-&-Messaging/AI-Powered-Persona-Messaging-Matrix-&-Dynamic-Personalization-Engine.md`

## Integration Tips

**HubSpot:**
- Pipe churn-risk segments into HubSpot smart lists using contact properties; trigger CS workflows automatically when at-risk language score exceeds threshold
- Map VoC themes to deal lost reasons in CRM for win/loss reporting

**Notion:**
- Create a VoC Intelligence Hub in Notion with database views by theme, priority, and team owner; link to sprint planning databases for product team
- Auto-populate product feedback database using Zapier webhook from Typeform/Delighted NPS survey responses

**Productboard / Linear:**
- Export feature request ranked backlog as CSV and import directly into Productboard with Kano classification tags; map to Linear issues for engineering sprint

**Intercom / Zendesk:**
- Tag support tickets automatically using the churn-risk language library as a keyword filter; trigger high-priority escalation queue when 3+ signals appear in a single ticket

**Google Sheets + Looker Studio:**
- Build a VoC tracking dashboard in Sheets with monthly sentiment scores, NPS trend, and theme frequency; connect to Looker Studio for executive reporting
- Use Apps Script to auto-run sentiment analysis on new Typeform responses weekly

**Zapier Automation:**
- Trigger: New NPS response (Delighted) → Action: AI analysis → Action: Append to Sheets VoC tracker → Action: If detractor, create HubSpot task for CS rep
- Trigger: New G2 review → Action: AI extract themes + sentiment → Action: Post digest to #voc-intelligence Slack channel weekly

## Troubleshooting

**Problem: Themes are too broad or generic (e.g., "product quality" covers everything)**
Fix: Add a specificity instruction — "Break each theme into sub-themes of no more than 15 mentions each. If a theme exceeds 15 mentions, split it into two distinct sub-themes." Also provide competitive context so the model knows what granularity matters.

**Problem: Output mixes Enterprise and SMB feedback, making recommendations unclear**
Fix: Pre-segment your input data before pasting — create two clearly labeled blocks: `---ENTERPRISE FEEDBACK (500+ employees)---` and `---SMB FEEDBACK (<500 employees)---`. Add to the prompt: "Keep Enterprise and SMB analysis strictly separate in all sections."

**Problem: Verbatim quotes are paraphrased rather than exact**
Fix: Add this constraint: "You must copy quotes character-for-character from the source data. Never summarize or rephrase a customer quote. If a quote is too long, truncate with [...] but do not alter the original language." Then validate a sample of 5 quotes against source before using in public-facing materials.

## Version History

- v1.0: Initial creation (auto-generated) — 2026-03-13
