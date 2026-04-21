# AI-Powered B2B Vendor Selection Scorecard & Buyer Decision Framework Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** interactive-content, lead-generation, b2b, buyer-enablement, conversion, competitive-positioning, sales-acceleration

## Overview
Builds AI-generated vendor evaluation scorecards and buyer decision frameworks that guide prospects through a structured comparison process, capture intent and qualification signals, and produce champion-ready executive reports buyers can share internally — compressing 4-6 week evaluation cycles into a single high-converting interactive session.

## Quick Copy-Paste Version

You are a senior B2B product marketer. Create a complete vendor selection scorecard for a buyer evaluating solutions in the [CATEGORY] space.

My company: [YOUR COMPANY]
Product category: [e.g., "marketing automation platform", "data security solution", "HR management software"]
Primary buyer title: [e.g., "VP of Marketing at 200-2000 person B2B SaaS company"]
Our top 3 differentiators vs. the market: [LIST THEM]
Top 2 known competitor weaknesses: [LIST THEM]
Typical buying committee roles: [e.g., "VP Marketing, CTO, CFO"]

Build a vendor evaluation scorecard with all of the following components:

1. EVALUATION CATEGORIES (5-6 categories, 80-100 total criteria)
   - Group criteria into business-outcome categories (not feature lists)
   - Suggested categories: Core Capability, Implementation & Time-to-Value, Integration & Technical Fit, Support & Partnership, Security & Compliance, Total Cost of Value
   - Assign % weight to each category (totaling 100%) appropriate for mid-market buyers
   - Scoring rubric per criterion: 0 = missing/fails, 1 = basic/partial, 2 = meets standard, 3 = excellent/exceeds

2. CRITERIA DESIGN RULES
   - Write all criteria as buyer outcome questions ("Does this vendor enable X outcome?" not "Does this vendor have X feature?")
   - Include 5-7 criteria that directly expose our differentiators without naming us
   - Include 3-5 "deal-breaker flags" — criteria where a score of 0 should prompt a hard stop in the evaluation
   - Mark 20% of criteria as MUST-HAVE (binary yes/no, not scored)

3. PERSONA WEIGHTING VARIANTS
   - Create 3 weight adjustment profiles: Technical Buyer, Business/Operations Buyer, Executive/Finance Buyer
   - For each persona, identify which 2 categories get +15% weight and which 2 get -10% weight

4. COMPLETED SCORING EXAMPLE
   - Show our solution vs 2 competitors using realistic but strategically favorable scores
   - Total score formula: (category score / max possible) × category weight × 100
   - Add "recommended to advance" threshold: 72+ out of 100

5. QUALIFICATION DATA CAPTURE (embedded throughout, not a separate form)
   - 8 questions to gather: company size, current solution, contract renewal date, budget range, timeline, decision-maker confirmation, shortlisted vendors, primary pain driving evaluation
   - Identify which answers trigger immediate sales alert (hot lead routing logic)

6. EXECUTIVE SUMMARY OUTPUT TEMPLATE
   - 1-page summary a buyer can forward to their CFO/board
   - Include: top-scoring vendor, score breakdown by category, top 3 decision rationale, pre-written internal approval memo template
   - Include a risk section: "What happens if you delay this decision by 90 days?"

Output the complete scorecard in formatted markdown, ready for implementation in Outgrow, Typeform, or a custom tool.

## Advanced Customizable Version

ROLE: You are a senior B2B product marketing strategist with deep expertise in buyer psychology, competitive displacement, and sales enablement architecture. You understand how enterprise buying committees work, how procurement evaluations are structured, and how to design decision frameworks that ethically guide buyers toward the right conclusion — which happens to be your solution.

OBJECTIVE: Design a fully deployable AI-powered vendor selection scorecard for [COMPANY_NAME]'s [PRODUCT_CATEGORY] that:
1. Gives buyers a genuinely useful, credible evaluation tool they'll complete and share internally
2. Strategically weights and frames criteria to highlight our competitive advantages
3. Captures rich qualification and intent data at every step
4. Produces a champion-ready artifact that enables buyers to sell internally on your behalf
5. Compresses the evaluation phase from 6+ weeks to a single 20-25 minute session

COMPANY INPUT:
- Company: [COMPANY_NAME]
- Product category: [PRODUCT_CATEGORY] (e.g., "AI-powered sales intelligence platform")
- Ideal customer profile: [COMPANY_SIZE] [INDUSTRY] companies, primary buyer = [BUYER_TITLE]
- Top use cases: [LIST 3-5 PRIMARY USE CASES]
- Competitive advantages: [LIST 4-6 DOCUMENTED DIFFERENTIATORS with proof points]
- Competitive set: [LIST 3-5 DIRECT COMPETITORS]
- Known competitor weaknesses (documented, not speculative):
  * [COMPETITOR_1]: [WEAKNESS_1], [WEAKNESS_2]
  * [COMPETITOR_2]: [WEAKNESS_1], [WEAKNESS_2]
  * [COMPETITOR_3]: [WEAKNESS_1], [WEAKNESS_2]
- Average deal size: [ARR]
- Average sales cycle: [DURATION]
- Buying committee composition: [LIST ALL ROLES + their primary evaluation criteria]
- Win/loss data: [TOP 3 REASONS WE WIN, TOP 3 REASONS WE LOSE]

SCORECARD ARCHITECTURE:

SECTION 1 — PERSONA IDENTIFICATION QUIZ (5 questions, shown first)
Design a 5-question quiz that identifies which buyer persona is completing the scorecard.
Personas to detect:
  - The Technical Evaluator (CTO, Head of Engineering, IT Director): Prioritizes integration depth, security architecture, API capabilities, implementation complexity
  - The Business Buyer (VP Operations, Head of Revenue, Director of [FUNCTION]): Prioritizes business outcomes, adoption rate, workflow fit, support responsiveness
  - The Financial Approver (CFO, VP Finance, Procurement): Prioritizes TCO, ROI proof, contract flexibility, vendor stability/risk
  - The Strategic Champion (VP/SVP/C-Suite): Prioritizes strategic fit, scalability, market leadership, reference customers
Questions should feel helpful (not diagnostic), e.g., "What will matter most when you present this evaluation to your leadership team?"
Output: persona assignment + automatic category weight adjustment applied silently

SECTION 2 — EVALUATION CATEGORY FRAMEWORK
Create 6 evaluation categories with default weights (adjustable by persona):

Category 1: Core Capability & Functional Depth (Default weight: 30%)
  - Define 12-15 evaluation criteria covering the must-have functionality spectrum
  - Include 4 MUST-HAVE criteria (binary pass/fail; if fail, recommend vendor be eliminated)
  - Include 8 scored criteria (0-3 scale with specific scoring guidance)
  - Include 3 differentiator criteria where [COMPANY_NAME] scores 3 and typical competitors score 1-2
  - Scoring rubric example: "Criterion: Real-time data processing without batch delays — Score 3: Processes and surfaces data within <1 minute of event; Score 2: <15 minute lag; Score 1: Hourly batch only; Score 0: Daily batch or manual refresh"

Category 2: Implementation & Time-to-Value (Default weight: 20%)
  - Define 10-12 criteria covering onboarding speed, implementation support, training resources, migration complexity
  - Key strategic criteria: average days to first production use (where we win), dedicated implementation team included, customer success model post-launch
  - Include questions about implementation track record and reference availability

Category 3: Integration & Technical Architecture (Default weight: 15%)
  - Define 10-12 criteria covering existing tech stack compatibility, API depth, native integrations vs custom builds required, data model flexibility
  - Tailor to [COMPANY_NAME]'s integration strengths
  - Include: reverse ETL capabilities, webhook support, SDK availability, SSO/SCIM support

Category 4: Support, Service & Partnership Model (Default weight: 15%)
  - Define 8-10 criteria covering support response SLAs, dedicated CSM assignment, professional services model, community/documentation quality
  - Strategic framing: "Does vendor assign you a named success team or route you to a support queue?"

Category 5: Security, Compliance & Enterprise Readiness (Default weight: 10%)
  - Define 8-10 criteria: SOC 2 Type II, GDPR/CCPA compliance, data residency options, SSO/MFA, penetration testing cadence, SLA guarantees and credits
  - Include AI-specific compliance criteria if product uses AI/ML features

Category 6: Total Cost of Value & Commercial Terms (Default weight: 10%)
  - Define 8-10 criteria covering: pricing model transparency, 3-year TCO vs alternatives, contract flexibility, implementation/professional services pricing, renewal escalation caps
  - Include 3-year cost modeling template (our pricing + typical competitor pricing structure)

SECTION 3 — MUST-HAVE CHECKLIST
Before scoring, buyers complete a binary Yes/No checklist of 8-10 non-negotiable requirements.
Design these so that vendors who fail 2+ MUST-HAVES are auto-flagged for elimination.
Strategically include 2-3 MUST-HAVES that competitors frequently fail.
Example: "Vendor must be able to go live within 30 days of contract signing without requiring buyer to hire additional implementation staff."

SECTION 4 — SCORING MATRIX & CALCULATION ENGINE
Design the full scoring matrix with:
- Row: each criterion (grouped by category)
- Column: Your Vendor Name / Competitor 1 / Competitor 2 / Competitor 3 (optional)
- Auto-calculated subtotals per category
- Total weighted score formula: Σ (Category Raw Score / Category Max Score × Category Weight × 100)
- Score interpretation guide:
  * 85-100: Clear winner, fast-track to contract
  * 70-84: Strong candidate, proceed to reference and security review
  * 55-69: Conditional — address gaps before advancing
  * Below 55: Recommend elimination

Pre-fill a completed example showing:
  - [COMPANY_NAME] scoring: target 82-88 range (credible, not implausibly perfect)
  - Primary competitor scoring: 60-70 range (reflecting real documented weaknesses)
  - Secondary competitor scoring: 55-65 range
Include scoring rationale notes for top 20 criteria

SECTION 5 — QUALIFICATION & INTENT DATA CAPTURE
Embed data capture questions at natural break points (between sections 2-3 and 4-5):

Qualification questions (always ask):
  1. What is your company's approximate annual revenue or employee count?
  2. What solution are you currently using for [USE CASE]? When does your contract renew?
  3. What is the primary business problem driving this evaluation?
  4. How many people are involved in this buying decision, and who has final approval?
  5. What is your target go-live date?

Intent signal questions (route to sales if triggered):
  6. Has budget been formally allocated for this initiative? [Yes / In process / Not yet]
  7. What other vendors are you currently evaluating?
  8. Are you open to a technical deep-dive call with a solution architect this week?

Hot lead routing logic (Zapier/workflow trigger):
  - Trigger 1: Score ≥75 AND budget confirmed AND timeline ≤90 days → immediate Slack alert to AE + email to SDR
  - Trigger 2: Score ≥75 AND competitor mentions [TOP COMPETITOR] → route to competitive AE
  - Trigger 3: Renewal date ≤60 days on current vendor → flag as urgent, route to senior AE

SECTION 6 — BUYER'S EXECUTIVE REPORT (auto-generated output)
Design the report buyers receive immediately after completing the scorecard:

Page 1: Executive Summary
  - Headline recommendation: "[YOUR COMPANY] scored X/100 — [Recommended / Conditionally Recommended / Not Recommended for advancement]"
  - Top 3 evaluation findings (auto-generated from highest-impact scored criteria)
  - Score breakdown visual (simple bar chart or table by category)
  - Time/cost comparison summary (if TCO section completed)

Page 2: Detailed Scorecard Results
  - Full category-by-category breakdown with scores
  - Gaps identified: criteria where no vendor scored ≥2 (indicates market gap or requirements clarification needed)
  - MUST-HAVE checklist results

Page 3: Risk Assessment
  - Implementation risk analysis (based on implementation scores)
  - Vendor stability signals (years in market, customer base, funding/public status)
  - "Cost of no decision": estimated value leakage per month of delay based on buyer's stated use case

Page 4: Recommended Next Steps (dynamic, based on score)
  - If [COMPANY_NAME] wins: "Schedule your 60-minute technical deep-dive — we'll map our solution to your exact requirements from this evaluation"
  - If score is conditional: "Download our Implementation Proof Pack — 3 customer case studies in your exact industry and company size"
  - CTA with calendar link, specific AE name, and personalized subject line

Page 5: Internal Approval Memo Template
  Pre-written memo buyers can customize and send to their leadership team:
  "Subject: Vendor Recommendation: [PRODUCT CATEGORY] Selection for [BUYER COMPANY NAME]
  After completing a structured evaluation of [X] vendors against [Y] weighted criteria, I recommend [COMPANY_NAME] based on [TOP 3 FINDINGS]. Attached is the full evaluation scoring summary. Key factors: [auto-populated from highest-weighted differentiators]..."

DELIVERY FORMAT:
1. Full scorecard in markdown (implementation-ready)
2. Persona quiz with branching logic
3. Scoring formula and threshold definitions
4. Sample completed report showing realistic buyer output
5. Sales alert/routing trigger logic
6. Tech stack implementation guide (Outgrow, Typeform + Zapier + Documint, or HubSpot native)
7. Launch checklist (A/B test variants, distribution channel plan, sales enablement brief)

QUALITY CONSTRAINTS:
- All criteria must be framed as buyer outcomes, never vendor feature checklists
- Scoring rubrics must be precise enough that two different evaluators score within 10% of each other
- Competitive criteria must be based on publicly documented limitations, not speculative attacks
- Executive report must be printable as a PDF without reformatting
- Target buyer completion time: 20-25 minutes maximum
- Every qualification question must have a clear CRM field mapping defined

## Example Input/Output

**Input Example:**
Company: ClearPath Analytics (B2B revenue intelligence platform)
Product category: Revenue Intelligence & Forecasting
Target ICP: 300-3000 employee B2B SaaS companies, VP of Revenue Operations or Head of Sales
Primary differentiators:
  1. 18-day median implementation vs 60+ day industry average
  2. Native two-way sync with Salesforce, HubSpot, and Gong (competitors require middleware)
  3. AI forecast explainability — every forecast prediction shows the 3 data signals driving it
  4. No-code signal builder (RevOps can create custom intent signals without engineering)
Competitors: Clari, Gong Forecast, Boostup
Competitor weaknesses:
  - Clari: Implementation requires dedicated Clari admin, 3+ month ramp; no native Gong sync
  - Gong Forecast: Only strong if Gong is already deployed; limited RevOps customization
  - Boostup: Strong on forecasting, weak on buyer signal detection; limited CRM write-back
Average deal: $72K ARR, 3.5-month sales cycle
Buying committee: VP RevOps (primary), CRO, VP Sales, CTO (security review)

**Output Example (abbreviated):**

**PERSONA IDENTIFICATION QUIZ:**
Q1: "Who will primarily use the outputs from this platform on a daily basis?" 
  → If "RevOps team building reports and workflows" → Business Buyer persona (+15% weight: Core Capability, Implementation)
  → If "CRO/VP Sales reviewing forecasts" → Executive persona (+15% weight: TCO, Strategic Fit)
  → If "Engineering team managing integrations" → Technical Buyer persona (+15% weight: Integration, Security)

**CATEGORY 1: CORE CAPABILITY (Weight: 32% / 28% / 25% by persona)**

MUST-HAVE Criteria:
☐ Platform provides deal-level forecast at individual opportunity granularity (not just roll-up)
☐ AI signals derived from actual buyer engagement data, not rep-entered CRM fields
☐ System generates a forecast recommendation the CRO can defend to the board without manual adjustment

SCORED Criteria (0-3):
- Real-time pipeline change detection and alert speed
  Score 3: Changes in CRM/email/calendar reflected in forecast within 60 minutes
  Score 2: Same-day refresh (<8 hours)
  Score 1: Overnight batch refresh
  Score 0: Manual trigger required to refresh forecast
  [ClearPath: 3 / Clari: 2 / Gong Forecast: 1]

- Forecast model explainability for RevOps
  Score 3: Every forecast shows the top 3-5 signals driving the prediction with plain-language explanations
  Score 2: Category-level explanation available on request
  Score 1: Black-box model, no signal visibility
  Score 0: Forecast provided with no methodology explanation
  [ClearPath: 3 / Clari: 1 / Gong Forecast: 2]

**QUALIFICATION GATE (between sections 2 and 3):**
"Before we calculate your preliminary scores, help us personalize your results:"
→ "What CRM platform is your primary system of record?" [Salesforce / HubSpot / Other]
→ "When does your current revenue intelligence tool contract renew?" [<3 months / 3-6 months / 6-12 months / We have no current tool]
→ "Has budget been approved for this initiative?" [Yes, approved / In planning process / Not yet scoped]
SALES ALERT TRIGGER: If renewal <3 months AND budget approved → immediate hot-lead ping to AE Slack + CRM task

**SAMPLE EXECUTIVE SUMMARY OUTPUT:**
ClearPath Analytics Vendor Evaluation — [Acme Corp]
Completed by: Sarah Chen, VP Revenue Operations — April 21, 2026

RECOMMENDATION: ClearPath Analytics — Score 84/100
Status: RECOMMENDED — Proceed to contract and security review

Top 3 Evaluation Findings:
1. Fastest implementation: ClearPath's 18-day median implementation eliminates the 2-3 month 
   ramp that competing platforms require — critical given your Q2 pipeline review deadline.
2. Only platform with native Gong + Salesforce + HubSpot three-way sync: avoids the $40-80K 
   custom middleware integration your engineering team estimated for Clari.
3. No-code signal builder: your RevOps team can create custom intent signals without filing 
   an engineering ticket — essential given your team's current sprint capacity.

3-Year Total Cost of Value:
ClearPath: $216K ARR platform + $0 implementation + $0 middleware = $648K total
Clari: $195K ARR + $45K implementation + $60K middleware estimated = $696K total

INTERNAL APPROVAL MEMO:
Subject: Vendor Recommendation: Revenue Intelligence Platform Selection

After completing a structured evaluation of 4 vendors against 78 weighted criteria,
I recommend ClearPath Analytics. Key factors: fastest implementation timeline,
lowest 3-year total cost, and only platform that eliminates our middleware requirement.
Full scoring summary attached. Requesting approval to proceed to contract by April 30.

## Success Metrics
- **Completion rate:** Target >42% (industry average for interactive assessments: 20-30%); if below 30%, shorten or add progress bar
- **MQL conversion:** >55% of completions should meet MQL threshold based on embedded qualification data
- **Champion activation rate:** Track how often buyers forward the completed report via email (use trackable links in the report)
- **Sales velocity:** Compare average deal close time for opportunities where scorecard was used vs not used; target 20-35% compression
- **Score calibration:** Your solution's average score from buyers should land 78-88/100 — if consistently above 90, criteria are too easy; if below 70, rebuild differentiator criteria
- **Competitive displacement rate:** Track win rate for deals where scorecard was completed vs pipeline average; expect 15-25% higher win rate
- **Internal sharing:** Measure PDF downloads and internal email opens on the executive report; each internal share = active champion behavior

## Related Prompts
- [AI-Powered B2B TCO Calculator & Competitive Cost Displacement Intelligence Engine](./AI-Powered-B2B-TCO-Calculator-&-Competitive-Cost-Displacement-Intelligence-Engine.md)
- [B2B Buyer Assessment Quiz Lead Generation Engine](./B2B-Buyer-Assessment-Quiz-Lead-Generation-Engine.md)
- [AI-Powered B2B Sales Diagnostic Tool & Personalized Action Plan Intelligence Engine](./AI-Powered-B2B-Sales-Diagnostic-Tool-&-Personalized-Action-Plan-Intelligence-Engine.md)
- [AI-Powered Competitive Battlecard Automation & Real-Time Objection Handling Intelligence Engine](../../02_Product-Marketing/Sales-Enablement/AI-Powered-Competitive-Battlecard-Automation-&-Real-Time-Objection-Handling-Intelligence-Engine.md)

## Integration Tips
- **Outgrow or Ion Interactive:** Best-in-class platforms for scored, branching interactive assessments with built-in persona detection, real-time score calculation, and PDF report generation; native HubSpot and Salesforce integrations
- **Typeform + Zapier + Documint:** Build the assessment in Typeform Pro (branching logic, hidden fields), use Zapier to calculate weighted scores, trigger Documint to auto-generate branded PDF executive report; send via email automatically
- **HubSpot:** Map each scorecard criterion to a custom contact/deal property; build score-based workflows that trigger sales sequences, route to specific AE queues, or enroll in nurture tracks; use score in smart content personalization
- **Salesforce:** Create a custom object for "Vendor Evaluation" to store all criterion scores at the opportunity level; build a lead scoring model that factors in scorecard score alongside traditional demographic/behavioral signals; trigger Tasks and Alerts via Process Builder
- **Clearbit + 6sense:** Enrich scorecard leads with firmographic data to auto-qualify without requiring buyers to answer every qualification question; use intent data to pre-warm your AEs before the scorecard is even completed
- **Slack:** Configure instant alerts to AE/BDR channels when hot-lead criteria are met; include buyer name, company, score, top differentiators that won, and competitor on shortlist
- **Notion + Airtable:** Maintain the master scorecard criteria library in Notion (version-controlled, linked to product roadmap); export live scoring data to Airtable for analysis by PMM and sales leadership

## Troubleshooting

**Problem:** Buyers complete the scorecard but your solution doesn't score highest
*Solution:* Run a criteria audit against recent win/loss data. Pull the last 20 won and 20 lost deals, map them against the scorecard criteria, and identify which criteria genuinely predict wins. Rebuild category weights to reflect actual win factors, not hypothetical differentiators. If you're genuinely losing on core capability criteria, involve product leadership — no scorecard fixes a real product gap.

**Problem:** Completion rate below 25% despite traffic to the scorecard page
*Solution:* Audit the first 3 screens — 80% of drop-off happens before screen 4. Add a live "preview score" counter that moves as buyers answer (psychological momentum). Reduce the first section from 15+ questions to 5 questions, gating the rest behind a soft-submit. Add social proof ("347 RevOps leaders evaluated vendors using this framework this quarter"). Ensure mobile experience is fully responsive.

**Problem:** Sales team dismisses scorecard leads as "too early" despite high scores
*Solution:* The qualification triggers are miscalibrated to sales' actual readiness criteria. Run a 2-hour workshop with your top 3 AEs to define exactly what makes a lead "sales-ready" in their view; rebuild the hot-lead routing logic around those specific criteria. Also create a "scorecard-started" sequence that allows marketing to continue nurturing buyers who began but haven't completed, keeping them engaged until they're ready for sales contact.

## Version History
- v1.0: Initial creation (auto-generated)
