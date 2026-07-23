# AI-Powered B2B SaaS Inbound Lead Scoring & Revenue-Qualified Pipeline Architecture Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b-saas, lead-scoring, mql, sql, pipeline-qualification, marketing-operations, revenue-operations, demand-waterfall, ai-scoring, crm-automation, hubspot, salesforce, marketo

## Overview
Designs a complete AI-powered lead scoring system that automatically qualifies inbound leads by combining behavioral engagement scores with firmographic fit scores and real-time intent signals — then routes each lead to the right sales motion with SLA-governed handoffs. Use this when your sales team is wasting time on unqualified MQLs, your MQL-to-SQL conversion rate is below 25%, or you are rebuilding your demand waterfall after a go-to-market pivot.

## Quick Copy-Paste Version

You are a marketing operations and revenue operations expert specializing in AI-powered lead scoring for B2B SaaS companies. Design a complete lead scoring and pipeline qualification system for the company below.

COMPANY SNAPSHOT:
- Company: [Company name and product category — e.g., "Axiom Revenue AI, a revenue intelligence platform for B2B SaaS sales teams"]
- Current ARR: [e.g., $8M ARR]
- Sales motion: [e.g., "Hybrid: inbound self-serve trials + outbound enterprise motion for deals >$30K ACV"]
- ICP definition: [e.g., "VP Sales, CRO, RevOps leaders at B2B SaaS companies, 50–500 employees, Series A–C, US-based"]
- Average deal size: [e.g., "$18K ACV for mid-market / $85K ACV for enterprise"]
- Sales cycle length: [e.g., "Mid-market: 30 days / Enterprise: 90–120 days"]
- Current MQL volume: [e.g., "~400 MQLs/month"]
- Current MQL-to-SQL conversion rate: [e.g., "18% — target is 35%"]
- Current CRM/MAP stack: [e.g., "HubSpot CRM + HubSpot Marketing Hub / Salesforce + Marketo"]
- Key pain: [e.g., "Sales team rejects 60% of MQLs as unqualified — causing marketing/sales tension and pipeline shortfall"]
- Top lead sources (by volume): [e.g., "Content downloads 35%, webinars 25%, paid search 20%, referral 15%, partner 5%"]
- Intent data available: [e.g., "G2 buyer intent via HubSpot, 6sense tier 3 data"]

DELIVERABLES REQUIRED:
1. LEAD SCORING MODEL: Define Engagement Score (behavioral, 0–100) + Fit Score (firmographic, 0–100) + Intent Boost (multiplier). Include every scoring signal with exact point values.
2. MQL/SQL DEFINITIONS: Precise threshold definitions for MQL, Sales-Accepted Lead (SAL), and SQL with score ranges and required qualifying conditions.
3. DEMAND WATERFALL STAGES: Full waterfall from Anonymous Visitor → Known Lead → MQL → SAL → SQL → Opportunity → Closed Won with conversion rate benchmarks at each stage.
4. LEAD ROUTING RULES: Route logic for each score tier (hot/warm/cool/cold) to the right sales motion (immediate SDR call, automated nurture, AE direct, disqualify).
5. SALES/MARKETING SLA: Response time commitments, follow-up cadence by lead tier, escalation triggers if SLA is breached.
6. AI SCORING AUTOMATION: Specific automation workflows to implement in HubSpot or Salesforce that run the scoring model without human intervention.
7. LEAD SCORING DECAY: Rules for degrading scores when leads go cold (time-based decay logic).
8. FEEDBACK LOOP DESIGN: How marketing will receive win/loss data from sales to continuously refine score weights every 30 days.

Every output must be directly implementable — include specific point values, field names, and workflow logic, not conceptual frameworks.

## Advanced Customizable Version

ROLE: You are a Marketing Operations and Revenue Operations architect with 12+ years of experience building AI-powered lead scoring systems for B2B SaaS companies from Seed through Series D. You have designed demand waterfalls for companies including HR tech, security, fintech, and developer tools. You are expert in behavioral psychology (the Fogg Behavior Model), predictive analytics, and the practical realities of CRM data quality. You understand that most lead scoring systems fail because they are built on assumptions rather than closed-loop data — and you know how to design self-correcting scoring models that improve with every deal cycle.

Your north star metric is MQL-to-Closed-Won conversion rate, not MQL volume. You think like the CRO: every MQL that sales rejects is a tax on marketing credibility.

COMPANY CONTEXT:
Company Name: [Full name]
Product: [Detailed description — core use case, primary workflow automated, measurable ROI delivered]
Current ARR: [Exact or range]
Growth stage: [Seed / Series A / Series B / Series C / Growth / Pre-IPO]
Sales team composition: [e.g., "4 SDRs, 6 AEs (2 mid-market, 4 enterprise), 2 CSMs"]
Primary ICP — Title: [Exact job titles that buy — e.g., "VP Revenue Operations, Director of Sales Operations, CRO"]
Primary ICP — Company: [Firmographic profile — industry, size range by employees and revenue, funding stage, tech stack signals, geographic focus]
Secondary ICP (if applicable): [Second buyer persona with same structure]
Sales motion(s): [Describe each motion — e.g., PLG self-serve for <$10K ACV, inbound-led AE for $10–50K ACV, outbound enterprise for >$50K ACV]
Average Contract Value by segment: [SMB / Mid-market / Enterprise ACVs]
Sales cycle by segment: [Time from first touch to closed-won by segment]
MarTech stack: [CRM, MAP, enrichment tools, intent data providers, chat, analytics]

Current demand waterfall data (provide actuals or best estimates):
- Monthly website visitors: [X]
- Monthly new leads captured: [X]
- Current MQL volume/month: [X]
- Current MQL-to-SAL rate: [X%] (industry benchmark: 60–75%)
- Current SAL-to-SQL rate: [X%] (industry benchmark: 50–65%)
- Current SQL-to-Opportunity rate: [X%] (industry benchmark: 70–80%)
- Current Opportunity-to-Closed-Won rate: [X%] (industry benchmark: 20–30%)
- Average days from MQL to closed-won: [X]
- % of MQLs rejected by sales ("bad MQLs"): [X%] (if >25%, you have a scoring problem)

Top lead sources by volume and quality: [List with volume % and approximate close rate per source]
Top disqualification reasons from sales: [List the most common reasons sales rejects MQLs verbatim from CRM notes]
Intent data available: [Which providers, what signals they deliver, how they integrate into CRM]
Enrichment tools: [Clearbit, ZoomInfo, Apollo, Cognism, etc. — what data is auto-appended]
Existing scoring model (if any): [Describe current model or state "none"]

SCORING ARCHITECTURE — Build ALL components:

**SECTION 1: ICP FIT SCORE (Firmographic, 0–100)**

Design a firmographic fit scoring model that answers: "Is this company a good fit for what we sell?"

Scoring dimensions to include:
- Company size (employee count): Assign scores for each band [1–10 employees: X pts, 11–50: X pts, 51–200: X pts, 201–1000: X pts, 1001+: X pts]
- Industry vertical: Score each relevant vertical with bonus/penalty for high-win-rate vs. low-win-rate industries
- Annual revenue or funding stage: Define optimal ranges with peak score
- Geographic location: Score by territory priority (e.g., US = 15 pts, Canada/UK/ANZ = 10 pts, EU = 8 pts, other = 3 pts)
- Technology stack signals: Score presence of specific technologies that correlate with your ICP (e.g., "uses Salesforce + Gong + HubSpot = +20 pts")
- Job title/seniority of the lead: Score each relevant title [CRO = 25 pts, VP Sales = 20 pts, RevOps Director = 18 pts, Sales Ops Manager = 12 pts, SDR Manager = 6 pts, etc.]
- Buying committee coverage: Bonus points if multiple contacts from same account are active

Output:
- Complete scoring table with every variable and exact point values
- Maximum possible Fit Score: 100
- Minimum threshold for MQL consideration: [X]
- Data sources for each field (CRM field, enrichment tool, form field)
- Data quality rules: What happens when enrichment data is missing

**SECTION 2: ENGAGEMENT SCORE (Behavioral, 0–100)**

Design a behavioral engagement score that measures demonstrated interest and buying intent. Use the Fogg Behavior Model (Motivation × Ability × Prompt) to assign weights — high-motivation behaviors (watching a demo, requesting pricing, visiting pricing page 3x) score disproportionately higher than low-motivation behaviors (opening one email).

Scoring signals to include (assign exact point values to each):
- Page visits: Homepage (1 pt), Product pages (3 pts each), Pricing page (8 pts first visit, 5 pts each repeat), Competitor comparison pages (7 pts), Customer case study pages (5 pts)
- Content downloads: Blog posts (2 pts), Ebooks (5 pts), Research reports (6 pts), ROI calculator completion (12 pts), Interactive assessment (10 pts)
- Webinar/event behavior: Registered but no-show (3 pts), Attended 50%+ (8 pts), Attended 100% + asked question (14 pts), Watched on-demand (5 pts)
- Email engagement: Email open (1 pt per open, max 3 pts per email), Email click (4 pts), Replied to sales email (15 pts), Unsubscribed (-10 pts)
- Product engagement (for PLG): Trial signup (15 pts), Reached activation milestone (20 pts), Invited team member (12 pts), Used product 3+ days in first week (18 pts)
- Demo/sales interactions: Requested demo (25 pts), Attended discovery call (30 pts), Requested pricing (20 pts), Submitted contact form (10 pts)
- Negative signals: Unsubscribed (-10), Visited careers page only (-5), Job title confirmed as student/intern (-20)

Score decay rules:
- No engagement in 14 days: -2 pts/day
- No engagement in 30 days: reduce score by 30%
- No engagement in 60 days: reset to 0 and move to long-term nurture

Output:
- Complete behavioral scoring table with every signal and exact point values
- Decay schedule
- Recency weighting (recent actions score higher than older actions of same type)

**SECTION 3: INTENT BOOST (Signal Multiplier)**

Define how 3rd-party intent data modifies the combined score:

Intent signal tiers:
- Tier 1 Intent (active in-market signal — researching your category, visiting competitor review sites, searching category keywords): Multiply combined score by 1.4
- Tier 2 Intent (topical interest — reading industry publications, engaging with adjacent content): Multiply by 1.2
- Tier 3 Intent (weak signal — company profile match, general industry activity): Multiply by 1.05
- No intent data: Multiply by 1.0

Intent sources to incorporate: G2/TrustRadius buyer intent, Bombora topic surge, 6sense stage prediction, LinkedIn Matched Audiences engagement, Clearbit Reveal account identification.

**SECTION 4: COMPOSITE SCORE & LEAD TIER DEFINITIONS**

Composite Lead Score Formula:
[(Fit Score × 0.45) + (Engagement Score × 0.45) + (Fit Score × Engagement Score × 0.10)] × Intent Boost Multiplier

Lead tier definitions (assign score ranges):
- TIER A — HOT (Score 85–100): ICP fit + high engagement + active intent signal. Route: Immediate SDR outreach within 5 minutes. SLA: First contact <5 min, 3 touches within 48 hours.
- TIER B — WARM (Score 65–84): Good fit + moderate engagement OR great fit + low engagement. Route: SDR outreach within 2 hours. SLA: First contact <2 hours, 5-touch cadence over 10 business days.
- TIER C — COOL (Score 45–64): Marginal fit or low engagement. Route: Automated nurture sequence for 30 days. Trigger SDR if score reaches Tier B during nurture.
- TIER D — COLD (Score 0–44): Poor fit or near-zero engagement. Route: Long-term newsletter nurture only. No SDR time invested.
- DISQUALIFIED: Confirmed wrong ICP, competitor employee, student, invalid contact. Remove from active scoring.

**SECTION 5: DEMAND WATERFALL STAGE DEFINITIONS**

Define each waterfall stage with crystal-clear entry/exit criteria:

1. ANONYMOUS VISITOR: Website visitor with no identified contact record. Action: Pixel tracking, IP-to-company reverse lookup (Clearbit Reveal/RB2B), serve account-based ads.

2. KNOWN LEAD (Contact Created): Form submission, event registration, or enrichment-based import. Requirements: Valid work email, minimum one identified field (name OR company). Scoring begins immediately.

3. MARKETING QUALIFIED LEAD (MQL): Entry criteria: Composite score ≥ [X] AND Fit Score ≥ [X] AND at least one high-value engagement action (pricing page visit, demo request, trial signup, or content download of high-intent asset). SLA trigger: Marketing notifies sales within [X] minutes of MQL threshold crossing.

4. SALES ACCEPTED LEAD (SAL): Sales confirms lead meets ICP within [X] hours of MQL notification. SAL rejection must include a rejection reason (select from defined list) that feeds back to scoring model. SAL-to-MQL feedback loop: If >20% of MQLs from a specific source are rejected, that source's scoring weight decreases automatically.

5. SALES QUALIFIED LEAD (SQL): BANT qualification confirmed. Budget: Authority to spend or influence budget decision confirmed. Authority: Primary decision-maker identified or champion with executive access confirmed. Need: Business pain mapped to product capability. Timeline: Evaluating within next 90 days. SQL creation triggers opportunity in CRM.

6. OPPORTUNITY: Active deal with defined next step and close date.

7. CLOSED WON / CLOSED LOST: Deal resolution with mandatory disposition tagging that feeds score model refinement.

**SECTION 6: AUTOMATION WORKFLOWS**

Design the specific CRM automation that makes this run without human intervention:

HubSpot workflow architecture:
Workflow 1 — Real-Time Score Calculator: Triggered by any property change or engagement event. Calculates composite score. Updates "Lead Tier" property. Enrolls in appropriate tier nurture or notifies SDR.
Workflow 2 — MQL Threshold Alert: Triggered when composite score crosses MQL threshold. Creates task in CRM for assigned SDR/AE with lead context snapshot (company, title, recent activity, content consumed, intent signals active). Sends Slack notification to SDR team channel with one-line context.
Workflow 3 — Score Decay: Runs daily at 6 AM UTC. Checks last engagement date for each contact. Applies decay formula. Re-evaluates tier assignment.
Workflow 4 — SAL Rejection Capture: Triggered when SDR sets lead status to "Rejected." Presents rejection reason form (dropdown: wrong company size / wrong industry / wrong job title / no authority / no budget / competitor / other). Logs to custom property. Triggers re-routing to long-term nurture.
Workflow 5 — Monthly Score Model Audit: Triggers on the 1st of each month. Generates a report of: MQL-to-SAL rate by source, SAL-to-SQL rate by source, top rejection reasons, average score of closed-won vs. closed-lost at each stage. Output delivered to CMO + VP Sales Slack channel.

Salesforce + Marketo architecture:
[Provide equivalent architecture for SFDC/Marketo stack]

**SECTION 7: SALES/MARKETING SLA CONTRACT**

Design a binding SLA that both teams sign off on. Include:
- Marketing commitments: MQL quality definition, volume commitments by month, minimum data completeness standards, lead source transparency
- Sales commitments: Response time by tier (A: 5 min, B: 2 hours, C: next business day), SAL acceptance/rejection within 24 hours, rejection reason required, closed-won/lost reporting within 48 hours of deal resolution
- Shared definitions: Agreed definitions of MQL, SAL, SQL, Opportunity that appear in both teams' dashboards
- Escalation protocol: If SLA breach rate exceeds 15% in any week, joint marketing/sales review triggered within 48 hours
- Monthly SLA scorecard: Metrics shared in monthly revenue review (MQL volume, SAL rate, rejection reasons, stage conversion rates, pipeline sourced by marketing)

**SECTION 8: CONTINUOUS IMPROVEMENT LOOP**

Design the AI feedback loop that makes the scoring model smarter over time:

Month 1: Baseline the model using current available data. Implement scoring. Track all stage conversions.
Month 2: First refinement. Pull closed-won deals from past 6 months. Identify which firmographic attributes (company size, industry, title) and behavioral signals (content downloaded, pages visited) were most predictive. Increase weight of predictive signals by 10–15%.
Month 3+: Monthly tuning cycle: Compare scoring model predictions vs. actual conversion. Use correlation analysis to identify over-weighted and under-weighted signals. Adjust weights. Document changes and rationale.

AI model enhancements for companies with >500 MQLs/month:
- Train a logistic regression model on historical MQL → Closed Won data to generate a Predictive Lead Score probability (0–100% likelihood to close)
- Integrate predictive score alongside rule-based composite score
- Route highest predictive score leads to senior AEs regardless of tier

IMPLEMENTATION TIMELINE:
Week 1: Data audit (identify which scoring signals are currently captured in CRM, which require enrichment)
Week 2: Scoring model build in CRM/MAP
Week 3: Automation workflow configuration and testing
Week 4: SDR team training + SLA sign-off
Week 5: Go-live with parallel tracking (run old and new model simultaneously)
Week 6–8: First refinement cycle based on early data

## Example Input/Output

**Input Example:**

Company: Meridian Analytics — a $12M ARR workflow intelligence platform for operations teams at mid-market manufacturers (200–2,000 employees). Series B. Sales team: 3 SDRs, 5 AEs (all mid-market). ACV: $24K. Sales cycle: 45 days. Stack: Salesforce + Pardot + Clearbit + Bombora. Current MQL volume: 280/month. MQL-to-SAL: 22% (target: 50%). Top rejection reason from sales: "Contact is an analyst, not a decision-maker."

**Output Example (Condensed):**

**ICP FIT SCORE — Meridian Analytics**

| Signal | Value | Points |
|---|---|---|
| Company size: 200–500 employees | Peak ICP | 25 pts |
| Company size: 501–2,000 employees | Good ICP | 20 pts |
| Company size: 2,001–5,000 | Stretch | 10 pts |
| Company size: <200 or >5,000 | Poor fit | 0 pts |
| Industry: Manufacturing | Peak ICP | 20 pts |
| Industry: Distribution / Logistics | Strong | 15 pts |
| Industry: Healthcare manufacturing | Moderate | 10 pts |
| Industry: Tech / Finance / Media | Weak | 3 pts |
| Title: VP Operations / COO / Director of Operations | Primary buyer | 25 pts |
| Title: Operations Manager / Plant Manager | Champion | 15 pts |
| Title: Business Analyst / Operations Analyst | Influencer | 8 pts |
| Title: IT Director / CTO (no ops in title) | Evaluator | 5 pts |
| Title: Marketing / HR / Finance | Wrong persona | 0 pts |
| Geography: US / Canada | Primary territory | 10 pts |
| Geography: UK / DACH / ANZ | Secondary | 7 pts |
| Tech stack: SAP or Oracle ERP | High signal | 10 pts |
| Tech stack: Salesforce | Moderate | 5 pts |
| Funding stage: Bootstrapped/PE-backed | Good fit | 8 pts |
| **Max Fit Score** | | **98 pts (cap at 100)** |

**ENGAGEMENT SCORE — Top Signals (abbreviated)**

| Behavior | Points |
|---|---|
| ROI Calculator completed | 18 pts |
| Demo requested (any form) | 25 pts |
| Pricing page: 2+ visits in 7 days | 14 pts |
| Attended webinar 80%+ | 12 pts |
| Downloaded "State of Manufacturing Operations" report | 8 pts |
| Visited customer case study (manufacturing vertical) | 7 pts |
| Replied to SDR email | 18 pts |
| Score decay: No activity 14 days | -2/day |

**MQL Threshold for Meridian Analytics:**
- Fit Score ≥ 55 AND Engagement Score ≥ 40 AND at least one of: demo request, pricing page visit, ROI calculator, or webinar attendance
- Composite: [(55×0.45) + (40×0.45)] = 42.75 minimum = Tier B entry

**Root Cause of 22% MQL-to-SAL Rate:**
The "analyst" rejection pattern indicates the Fit Score currently does not penalize analyst/individual contributor titles enough. Recommendation: Set analyst/coordinator/specialist titles to 3 pts MAX (vs. current 8 pts), and add a disqualification trigger if title contains "analyst" AND company size is <500 employees with no accompanying senior title from the same account.

**Month 1 Projected Impact:** MQL volume decreases from 280 to ~190/month (fewer poor-fit leads surface), but MQL-to-SAL rate increases from 22% to an estimated 44–52% based on title filtering alone. Net SALs: increases from 62 to 84–99/month (+35–60%).

## Success Metrics

- **MQL-to-SAL rate:** Should reach 45–65% within 60 days of implementation (industry benchmark: 50–70%)
- **SAL-to-SQL rate:** Should reach 55–70% (benchmark: 50–65%)
- **MQL rejection rate by sales:** Should fall below 20% (from typical 40–60% before scoring)
- **Time from MQL to first sales contact:** Tier A leads: <5 minutes for 90% of leads
- **Score model accuracy:** Correlation between composite score and closed-won rate should increase >0.35 within 90 days
- **Pipeline sourced per MQL:** Revenue-weighted pipeline / total MQLs — should increase 20–40% as low-quality MQLs are removed from the mix
- **Marketing-sales SLA adherence:** Sales response within committed SLA window >85% of the time

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Demo-Request-Conversion-Architecture-&-Pipeline-Qualification-Velocity-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md`
- `../../05_Analytics-&-Performance/Demand-Sensing-&-Market-Intelligence/AI-Powered-B2B-SaaS-Intent-Data-Waterfall-Intelligence-&-Multi-Source-Buyer-Signal-Orchestration-Revenue-Intelligence-Engine.md`
- `../../02_Product-Marketing/Customer-&-Market-Research/AI-Powered-ICP-Signal-Intelligence-&-Continuous-Customer-Profile-Refinement-Engine.md`

## Integration Tips

**HubSpot:**
- Create custom Contact properties: `composite_lead_score`, `fit_score`, `engagement_score`, `lead_tier`, `intent_boost_multiplier`, `score_last_calculated`, `last_scoring_change_date`
- Use HubSpot Workflows with "Calculate property value" actions to run arithmetic on score components in real time
- Use Lists to segment by Lead Tier — connect each list to its corresponding email nurture sequence and SDR notification workflow
- HubSpot's native Lead Scoring tool can handle behavioral signals; use custom calculated properties for the composite formula
- Enable Slack integration to push Tier A lead alerts directly to #hot-leads channel with one-click to contact record

**Salesforce + Marketo:**
- Build Fit Score as a Salesforce formula field calculated from standard + enriched fields (Industry, Employee Count, Title, State)
- Use Marketo Smart Campaigns for behavioral score increments — create a dedicated Engagement Score field that Marketo writes to on each qualifying action
- Build a Salesforce Process Builder (or Flow) that calculates composite score whenever Marketo updates the engagement field
- Use Marketo's Revenue Cycle Model to map each waterfall stage and track stage-by-stage conversion automatically
- Create a Salesforce dashboard with Marketing Funnel Report showing stage conversion rates — share with Marketing and Sales leadership every Monday

**Clearbit / ZoomInfo / Apollo (Enrichment):**
- Configure enrichment to auto-append company size, industry, and technology stack on form submission
- Set up dynamic enrichment that re-enriches contacts every 90 days to capture company growth/changes
- Use enrichment confidence scores — do not use low-confidence data for scoring; mark as "unscored on firmographic" until verified

**6sense / Bombora (Intent Data):**
- Map 6sense buying stage predictions to your Intent Boost multiplier (6sense "Decision" stage = 1.4x, "Evaluation" = 1.25x, "Awareness" = 1.1x)
- Suppress Tier D leads from paid campaigns but add them to intent-triggered nurture that activates when they enter Tier 2 intent
- Use Bombora topic surge data to identify previously cold accounts re-entering the market — trigger a "re-engagement" scoring event

**Zapier / Make (No-Code Automation):**
- Build a Zap that sends a formatted lead summary to the assigned SDR's Slack DM when a Tier A lead is created: includes company name, contact name, title, score, last 3 behaviors, and one-click to CRM record
- Build a monthly score audit report exported to Google Sheets automatically for analysis

## Troubleshooting

**Problem:** Sales team still rejects 40%+ of MQLs after implementing new scoring model.
**Solution:** Run a "rejection reason audit" — export all rejected MQLs for the past 30 days and categorize rejection reasons. If >30% are for the same reason (wrong title, wrong company size), that specific variable is under-weighted in your Fit Score. Increase its penalty weight by 50% and re-evaluate. Also check if data enrichment is failing — if company size field is blank for 25%+ of leads, your Fit Score is running without that dimension.

**Problem:** Score decay is removing warm leads too aggressively — SDRs are missing reconnection opportunities.
**Solution:** Add a "Decay Pause" trigger: if a previously high-scoring lead opens an email or visits the website, pause decay for 14 days and notify the assigned SDR with a re-engagement alert. Set a minimum floor score of 20 for any lead that previously reached Tier B — they should never fall back to Tier D without a confirmed disqualification.

**Problem:** Model produces great MQL-to-SAL rates but Opportunity-to-Close rate is still low — pipeline quality is still poor.
**Solution:** Your current model is optimizing for Sales engagement (SAL) but not for deal quality. Shift the scoring model's training target from MQL→SAL conversion to MQL→Closed Won conversion. This requires 6+ months of historical deal data. In the interim, add a "Closed Won" retrospective: for every deal closed in the last 90 days, pull their lead score at MQL creation and identify patterns (what score range, which specific behaviors, what firmographic profile). Use those patterns to increase weights on signals that appeared in won deals but not lost deals.

## Version History
- v1.0: Initial creation (auto-generated)
