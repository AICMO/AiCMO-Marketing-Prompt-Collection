# AI-Powered B2B SaaS Vendor Evaluation Scorecard & Buyer Decision Intelligence Lead Generation Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** interactive-content, lead-generation, b2b, demand-gen, cro, competitive, buyer-enablement, sales-enablement, product-marketing

## Overview
Designs and deploys an AI-powered interactive vendor evaluation scorecard that captures high-intent "in-evaluation" buyers, educates them on your category's must-have capabilities (subtly positioning your differentiators), and outputs a personalized comparison report they can take internally. Use when you want to intercept buyers during active evaluations and convert anonymous high-intent traffic into qualified, self-identified pipeline.

## Quick Copy-Paste Version

You are a senior B2B product marketing strategist and interactive content architect. Build a complete interactive vendor evaluation scorecard for my category.

My company context:
- Product category: [e.g., "revenue intelligence software", "workflow automation for ops teams", "data observability platform"]
- Top 3 differentiators vs. competitors: [e.g., "AI-native architecture, native CRM integrations, usage-based pricing"]
- Primary ICP: [e.g., "VP Revenue Operations at 200-2,000 employee B2B SaaS companies"]
- Top 3 competitors we win and lose against: [e.g., "Gong, Clari, Chorus"]
- The #1 thing we win on in competitive deals: [e.g., "real-time deal intelligence vs. historical reporting"]

Design a complete interactive evaluation scorecard system including:

1. SCORECARD ARCHITECTURE — 5 evaluation categories with 3-4 criteria each (20 criteria total). Each criterion must be a capability buyers legitimately need AND one we're strong on. Phrase each as a requirement, not a feature ("Does the platform provide real-time pipeline alerts?" not "Does it have alerts?"). Assign weights (must sum to 100%) that reflect actual buyer priorities.

2. SCORING METHODOLOGY — How buyers rate each vendor 1-5 with clear, observable definitions at each score level. Include a "minimum threshold" flag for deal-breaker criteria. Generate a weighted total score and a visual category breakdown.

3. QUALIFICATION LOGIC — Map buyer score inputs to lead qualification intelligence. Which criteria responses indicate: (a) hot lead ready for immediate sales follow-up, (b) mid-funnel lead for nurture sequence, (c) poor-fit lead to disqualify early. Define the data fields to capture alongside scores.

4. PERSONALIZED OUTPUT REPORT — What the buyer receives after completing the scorecard: a one-page PDF/shareable link showing their evaluation results, recommended next steps, and a templated business case summary they can use internally to justify their vendor selection.

5. DISTRIBUTION STRATEGY — Where to embed this tool (dedicated landing page, gated resource, email campaign, LinkedIn ad), what copy drives highest completion rates, and how to use completion data in follow-up sequences.

6. SALES HANDOFF PROTOCOL — The exact data package passed to sales when a buyer completes the scorecard: score summary, gap areas, competitive vendors they're evaluating, their self-reported priorities, and recommended first-call talking points.

Output as a complete build spec a demand gen manager and developer can implement in 4 weeks.

## Advanced Customizable Version

# ROLE
You are a world-class B2B product marketing strategist and interactive content architect with 15+ years of experience building buyer-enabling content experiences for high-growth SaaS companies. You have built vendor evaluation tools that have generated tens of millions in pipeline by intercepting buyers during active evaluations. You understand buyer psychology, competitive positioning, and the mechanics of how modern B2B buyers make vendor decisions — including the internal political dynamics of building consensus across buying committees.

You specialize in designing interactive content that simultaneously educates buyers, qualifies them, captures intent intelligence, and positions your client as the category authority — without feeling like a sales tool.

# CONTEXT

## Company Profile
- Company name and product: [e.g., "Northstar — revenue intelligence platform for mid-market SaaS revenue teams"]
- ARR and growth stage: [e.g., "$18M ARR, Series B, targeting $60M in 24 months"]
- ICP (primary): [e.g., "VP Revenue Operations or VP Sales Operations at 150-2,000 employee B2B SaaS companies with $20M-$300M ARR"]
- ICP (secondary): [e.g., "CRO or VP Sales at same profile who owns the rev ops function"]
- Top 3 differentiators: [e.g., "1) Real-time deal intelligence vs. lagging indicators, 2) Auto-generated coaching insights vs. manual analysis, 3) CRM-native architecture with no data syncing required"]
- Key competitive wins: [e.g., "Win 68% of deals where we're head-to-head with Clari; win 54% against Gong"]
- Primary loss reason: [e.g., "We lose on brand recognition when Gong is preferred by VP Sales before rev ops gets involved"]
- Deal size: [e.g., "$45,000 median ACV, $120,000 enterprise ACV"]
- Sales cycle: [e.g., "45 days median, 90+ days for enterprise deals"]

## Evaluation Scorecard Requirements
- Tool name: [e.g., "Revenue Intelligence Platform Evaluation Scorecard"]
- Target buyer stage: [e.g., "Active evaluation — buyer is comparing 3-5 vendors"]
- Completion time target: [e.g., "10-12 minutes — enough depth to deliver value, short enough to maintain completion"]
- Primary deployment channel: [e.g., "Gated landing page, promoted via LinkedIn ads targeting Revenue Operations job titles"]
- Integration requirements: [e.g., "HubSpot for lead capture, Clearbit for enrichment, Slack for sales alerts, Google Sheets for data export"]

# OBJECTIVE
Design a complete, production-ready Interactive Vendor Evaluation Scorecard system that intercepts buyers during active evaluations and converts them into qualified sales pipeline. Every design decision must maximize three outcomes simultaneously: (1) buyer value — they receive genuinely useful evaluation guidance, (2) competitive positioning — your differentiators are embedded in the evaluation criteria as table stakes, and (3) lead intelligence — the data captured accelerates the sales cycle and improves win rates.

# DELIVERABLES

## DELIVERABLE 1: EVALUATION CATEGORY ARCHITECTURE

Design 5-6 evaluation categories with 3-5 weighted criteria each (18-25 total criteria). Categories must:
- Reflect how sophisticated buyers actually evaluate vendors in this category
- Be ordered from foundational to advanced (mirrors buyer thinking progression)
- Carry weights that reflect real-world buyer priorities (validate against win/loss data)

For each category, provide:
- Category name and one-sentence rationale for why this matters to buyers
- Category weight (% of total score)
- 3-5 specific criteria with:
  - Criterion name (action-oriented: "Does the platform..." or "Can the team...")
  - Why this criterion matters (buyer-centric language)
  - Your competitive position (internal note: Strong / Neutral / Weak)
  - Whether this is a potential deal-breaker if below threshold
  - Scoring rubric: 1 (absent), 2 (basic), 3 (functional), 4 (advanced), 5 (best-in-class) — write specific, observable definitions for each level

Example category output format:
---
CATEGORY: Real-Time Pipeline Intelligence (Weight: 25%)
Rationale: Revenue teams that rely on weekly pipeline reports miss 40% of deal risk that develops between reporting cycles. Real-time visibility is the single biggest predictor of forecast accuracy.

Criterion 1: Deal Alert Speed
"Does the platform surface deal risk signals within 24 hours of a trigger event (email silence, stakeholder change, competitive mention)?"
Why it matters: Every day of delayed risk detection costs revenue teams the ability to intervene.
Your position: STRONG
Deal-breaker threshold: Must score ≥3
Scoring:
- 5 (Best-in-Class): Real-time alerts (<1 hour) with AI-prioritized recommended actions
- 4 (Advanced): Same-day alerts with signal explanation
- 3 (Functional): Next-day batch alerts triggered by rule-based conditions
- 2 (Basic): Manual monitoring required; no proactive alerting
- 1 (Absent): No deal risk alerting capability
---

## DELIVERABLE 2: SCORING ENGINE & OUTPUT DESIGN

### Scoring Calculation Logic
- Weighted scoring formula: (Σ criterion score × criterion weight) × 100 = Total Score (0-100)
- Category subscores with visual progress indicators
- Deal-breaker override: If any deal-breaker criterion scores ≤2, flag "Critical Gap" regardless of total score
- Benchmark comparison: "Your evaluation scores Vendor X at [score]/100. The top 25% of teams we work with require ≥75 to proceed."

### Buyer Output Report (what they receive)
Design the complete personalized output report including:

1. EXECUTIVE SUMMARY (1 paragraph): "Based on your evaluation, you've identified [Category A] as your top priority and [Category B] as your biggest risk. Here's what our analysis found..."

2. SCORECARD SUMMARY TABLE:
   | Vendor | Category 1 | Category 2 | Category 3 | Category 4 | Category 5 | Total |
   (Pre-populate with typical competitor scores based on your win/loss data, editable by buyer)

3. CRITICAL GAPS ANALYSIS: For any vendor scoring below threshold on deal-breaker criteria, auto-generate a "Questions to ask in your next demo" checklist specific to that gap.

4. EVALUATION NEXT STEPS:
   - If [Your Company] scores highest: "Schedule a technical deep dive to validate your evaluation"
   - If competitor scores highest: "Before finalizing, here are 3 questions you should pressure-test..."
   - If tied: "Here are the tiebreaker criteria that predict long-term outcomes..."

5. INTERNAL BUSINESS CASE TEMPLATE: A one-page summary buyers can adapt for internal stakeholders, including: business problem, evaluation methodology, vendor recommendation with rationale, expected ROI, and implementation risk assessment.

### Lead Intelligence Capture
Alongside the scorecard, capture:
- Company name, role, email (gated before results)
- Which vendors they're evaluating (multi-select, 5-7 named options + write-in)
- Decision timeline (radio: <30 days / 30-90 days / 90+ days / researching only)
- Decision maker involvement (are they the DM, an influencer, or researcher?)
- Top evaluation priority (single select: their #1 category)
- Current solution being replaced (or "no current solution")
- Team size / budget band (firmographic supplement to Clearbit enrichment)

## DELIVERABLE 3: COMPETITIVE POSITIONING LAYER

For each of your top 3 competitors, create:
- Predicted scoring profile (based on your win/loss intelligence): how competitors typically score on each criterion
- The 2-3 criteria where competitor appears strong but has hidden weaknesses
- Recommended "probe questions" buyers should ask competitors at each weakness point
- The specific evidence/proof that demonstrates your superiority on each criterion (case study, G2 data, benchmark study, third-party validation)

This data populates the tool's "Questions to Ask" section and is never explicitly shown as "why you should pick us" — it's framed as "important evaluation questions for any vendor."

## DELIVERABLE 4: DISTRIBUTION & PROMOTION ARCHITECTURE

### Landing Page Copy Framework
- Headline formula: "[Outcome-focused benefit] — How to evaluate [Category] vendors before committing $[Budget Range]"
- Hero value prop: Why this tool exists (position as industry resource, not sales tool)
- Social proof: Who uses this format to make decisions (number of evaluations, company types)
- Objection handling: Why this takes 10 minutes and delivers a personalized report
- CTA: "Start your evaluation →" (progress bar visible from step 1)

### Paid Promotion Strategy
Design LinkedIn ad campaigns targeting buyers in active evaluation:
- Audience: Job titles matching ICP, filtered by companies researching your category (G2 intent data, Bombora, website visitor retargeting)
- Ad creative brief: 3 ad concepts (image, carousel, video) with hook, body, CTA, and expected click-through rate benchmark
- Budget allocation: How to split budget between cold awareness vs. in-market retargeting audiences
- Sequencing: Touchpoint map from ad exposure → landing page → scorecard completion → sales follow-up

### Email Nurture Sequence (Post-Completion)
Write a 4-email sequence for buyers who complete but don't immediately convert:
- Email 1 (Day 0): Delivery of their personalized report + "What to do now"
- Email 2 (Day 3): Deep-dive resource on the category they scored as their #1 priority
- Email 3 (Day 7): "3 questions your current frontrunner can't answer" (based on competitive gaps)
- Email 4 (Day 14): Case study featuring a company with their same evaluation profile + outcome

## DELIVERABLE 5: SALES HANDOFF PACKAGE

When a qualified lead completes the scorecard, auto-generate a sales alert in Slack containing:
- Lead identity and firmographic enrichment (from Clearbit/ZoomInfo)
- Their evaluation score for each vendor (including yours)
- Their stated #1 priority category
- Decision timeline and buyer role
- Critical gaps identified in competing vendors
- Recommended first-call opening: "Based on your scorecard, you flagged [X] as your top priority. Most teams in your position tell us the hardest part is [Y]. Can I show you how [3 customers with your same profile] solved that?"
- Suggested demo flow based on their evaluation priorities
- Competitive trap questions to surface in the call

## DELIVERABLE 6: ANALYTICS & OPTIMIZATION FRAMEWORK

Define the metrics to track and the optimization cadence:
- Completion rate by traffic source (target: >40% for gated tools)
- Lead quality score correlation (do high scorers close faster?)
- Competitive win rate among scorecard completers vs. control group
- Report sharing rate (how often do buyers share their report internally?)
- Time-to-first-meeting (scorecard completers vs. non-completers)
- Monthly optimization: which criteria have the highest "I don't know" response rate (indicates need for education, not evaluation)

# CONSTRAINTS
- All criteria must be genuinely important to buyers — no "gotcha" questions designed only to make competitors look bad
- Scoring rubrics must be objective enough that a competitor could score honestly
- The output report must deliver standalone value even if the buyer never speaks to your sales team
- Every feature/capability in the criteria must be provably true about your product before you publish
- GDPR-compliant data capture only — include consent checkbox and privacy policy reference at gate

# OUTPUT FORMAT
Deliver as a structured implementation brief organized by the 6 deliverables above. Include:
- Wireframe-level description of each scorecard screen
- Complete copy for all questions, scoring rubrics, and output report sections
- Developer handoff checklist with required integrations and data schema
- Launch checklist: 15 steps from brief to live tool
- Expected performance benchmarks at 30/60/90 days

## Example Input/Output

**Input Example:**
Company: Beacon Analytics — product analytics platform for growth-stage SaaS
ICP: Head of Product or VP Product at 50-500 employee SaaS companies
Top differentiators: Auto-generated funnel insights vs. manual query, no-code event tracking, Slack-native alerts
Top competitors: Mixpanel, Amplitude, PostHog
Primary win condition: Win 71% of deals where buyer's #1 complaint about Amplitude is "too complex for non-data teams"

**Output Example (Scorecard Category 1 of 5):**

---
**CATEGORY 1: Implementation Speed & Time-to-Value (Weight: 20%)**
*Why this matters: Every week of delayed insights is a product decision made without data. Teams that go live in <2 weeks outperform those that take 8+ weeks by 3x on adoption.*

**Criterion 1.1: Event Tracking Setup**
"Can non-technical product managers define and track new events without writing code?"
- 5 (Best-in-Class): Visual event tracking via point-and-click; no developer required; live in <30 minutes
- 4 (Advanced): Low-code interface; 1-2 hours with basic technical assistance
- 3 (Functional): SDK implementation with developer support; 1-2 day effort per event type
- 2 (Basic): Full custom development required; 1-2 week sprint per major tracking update
- 1 (Absent): Requires third-party implementation partner
*Deal-breaker: Yes — teams relying on engineering queues for tracking can't sustain an analytics program*

**Criterion 1.2: Pre-Built Dashboard Library**
"Does the platform include 20+ pre-configured dashboards for common SaaS metrics (activation, feature adoption, retention cohorts) that are useful out-of-the-box?"
- 5: 30+ SaaS-specific templates, customizable in <5 minutes
- 4: 15-20 templates covering core metrics
- 3: 5-10 generic templates; significant customization required
- 2: 1-3 basic templates; build-from-scratch for most use cases
- 1: No pre-built templates

**Criterion 1.3: Historical Data Backfill**
"Can the platform ingest 12+ months of historical event data so teams don't start with a blank slate?"
- 5: Automated backfill via API; all historical data available at launch
- 4: Semi-automated with engineer assistance; complete in 1-2 days
- 3: Manual CSV import; limited to structured event logs
- 2: Partial backfill only; historical comparisons unavailable for first 3-6 months
- 1: No backfill capability; fresh start only

**Your Beacon Analytics Position:** STRONG on 1.1 (no-code), NEUTRAL on 1.2, STRONG on 1.3
**Typical Amplitude Score:** 2 on 1.1, 4 on 1.2, 3 on 1.3 → Category score 7.2/10 vs. your 9.1/10
---

**Personalized Report Output for a buyer who scored Amplitude 58/100 and Beacon 77/100:**
"Your evaluation identified Implementation Speed as your top priority. Based on your responses, Amplitude scores 8/20 on this category while Beacon scores 18/20 — primarily driven by the code-required event tracking gap, which your team rated as a deal-breaker. Before finalizing, we'd recommend asking your Amplitude rep: 'Walk me through how a PM without SQL access would add tracking for a new onboarding step this week.' [Get your full report →]"

## Success Metrics

- **Tool completion rate:** ≥40% of visitors who start complete all questions (benchmark for interactive content)
- **Lead-to-MQL conversion:** Scorecard completers convert to MQL at 3-5x higher rate than standard content downloads
- **Sales cycle reduction:** Scorecard-sourced leads close 20-30% faster due to pre-qualification and self-education
- **Competitive win rate lift:** Track win rate for scorecard completers vs. non-completers in competitive deals
- **Internal sharing rate:** ≥25% of completers share their report (tracked via unique shareable link)
- **Content quality:** <10% of respondents select "I don't know" on criteria (high "don't know" = education gap, not evaluation)

## Related Prompts

- [`AI-Powered B2B SaaS Capability Maturity Assessment & Gap Analysis Lead Generation Intelligence Engine`](../../03_Content-&-Creative/Interactive-Content/AI-Powered-B2B-SaaS-Capability-Maturity-Assessment-&-Gap-Analysis-Lead-Generation-Intelligence-Engine.md)
- [`AI-Powered B2B SaaS Buyer Fit Discovery & Personalized Use Case Recommendation Interactive Content Architecture Intelligence Engine`](../../03_Content-&-Creative/Interactive-Content/AI-Powered-B2B-SaaS-Buyer-Fit-Discovery-&-Personalized-Use-Case-Recommendation-Interactive-Content-Architecture-Intelligence-Engine.md)
- [`AI-Powered B2B Competitive Comparison Page & Displacement Content Intelligence Engine`](../../03_Content-&-Creative/Ad-&-Website-Copywriting/AI-Powered-B2B-Competitive-Comparison-Page-&-Displacement-Content-Intelligence-Engine.md)
- [`AI-Powered B2B SaaS Competitive Evaluation Messaging Architecture & Head-to-Head Win-Rate Intelligence Engine`](../../02_Product-Marketing/Messaging-&-Positioning/AI-Powered-B2B-SaaS-Competitive-Evaluation-Messaging-Architecture-&-Head-to-Head-Win-Rate-Intelligence-Engine.md)

## Integration Tips

- **HubSpot/Salesforce:** Push scorecard completion as a contact activity event; map each criterion score to a custom property; trigger automated lead routing workflows based on decision timeline + score threshold
- **Clearbit/Apollo:** Enrich lead data in real-time at gate; auto-populate firmographic fields so buyers only answer the question fields that enrich your data
- **Typeform/Outgrow/Ion Interactive:** Build the interactive experience in a dedicated interactive content platform; embed scoring logic and branching natively; export via webhook to your CRM
- **Notion/Figma:** Use the output report design template to create a shareable PDF; generate unique URLs per completion for tracking internal sharing
- **Slack:** Configure sales alerts via Zapier/Make using a Slack bot that fires when a lead scores above your MQL threshold or identifies your product as their top evaluation choice
- **G2/TrustRadius:** Use peer review category data to validate your scoring rubrics and ensure criteria align with how buyers describe vendor differences in authentic reviews
- **6sense/Demandbase:** Layer intent data on top of scorecard completions to identify accounts in active buying cycles; prioritize sales outreach by combining tool completion + high intent score

## Troubleshooting

**Problem:** Low completion rate (<25%) — buyers abandon mid-scorecard
*Solution:* Reduce to 15 questions max; add a progress bar; gate the report after question 5 (not before); make early questions easy and satisfying to answer; use conditional logic to skip irrelevant sections

**Problem:** High-scoring leads aren't converting to demos
*Solution:* The report output may be too complete — buyers are self-qualifying out. Add a "Talk to an expert" CTA that's triggered by specific response patterns (e.g., if they're evaluating 4+ vendors and have a <30-day timeline). Also audit your follow-up sequence timing — if sales calls too fast it feels surveillance-y; 2-4 hours post-completion is the optimal window.

**Problem:** Competitors are finding the scorecard and gaming it
*Solution:* Focus criteria on outcomes and use cases, not feature checklists (it's harder to fake "Does your product allow non-technical PMs to track new events in under 30 minutes?"). Add a "verify with a free trial" or "request a reference customer" CTA for deal-breaker criteria — this surfaces vendor answers that don't hold up to scrutiny.

## Version History
- v1.0: Initial creation (auto-generated)
