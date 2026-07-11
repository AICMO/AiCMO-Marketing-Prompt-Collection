# AI-Powered B2B SaaS Revenue Conversation Intelligence Analytics & Sales Call-to-Marketing-Insight Revenue Engine - Convert Recorded Sales Conversations Into Systematic Marketing Intelligence

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** b2b, saas, conversation-intelligence, gong, chorus, revenue-analytics, sales-enablement, marketing-insights, win-loss, competitive-intelligence

## Overview
Systematically mines recorded sales conversations at scale — using Gong, Chorus, Clari, Fireflies, or raw transcripts — to extract revenue-predictive patterns, competitive intelligence, buyer language, and marketing content gaps, then converts those findings into weekly marketing intelligence briefs that directly improve campaign positioning, content, and ICP targeting. Designed to run continuously as an always-on intelligence loop between the sales conversation layer and the marketing strategy layer.

## Quick Copy-Paste Version

You are a revenue conversation intelligence analyst specializing in B2B SaaS. I need to build a systematic analytics program that mines our recorded sales conversations to extract marketing and revenue insights.

COMPANY CONTEXT:
- Company name and one-line description: [e.g., "Corvia AI — workflow automation platform for operations and finance teams at mid-market companies"]
- Primary ICP: [e.g., "VP Operations and CFO at $20M-$200M B2B companies, 50-500 employees"]
- Average ACV and sales cycle length: [e.g., "$38K ACV, 55-day average cycle"]
- Sales process stages: [e.g., "Discovery → Demo → Technical Evaluation → Proposal → Contract → Close"]
- Conversation tools available: [Gong / Chorus / Clari / Zoom recordings / Manual transcripts]
- Approx. recorded calls per month: [e.g., "240 calls: 80 Discovery, 60 Demo, 40 Technical Eval, 60 closing-stage"]
- Current win rate: [e.g., "24%"]
- Top 3 competitors mentioned in deals: [e.g., "Zapier, Make.com, UiPath"]
- Primary reasons deals are lost (from your CRM): [e.g., "Price (38%), Chose competitor (29%), No decision/status quo (22%), Budget cut (11%)"]

ANALYSIS OBJECTIVES:
Build a complete conversation intelligence analytics system that produces:

1. CALL CLASSIFICATION & SCORING RUBRIC — a framework to rate each recorded call on engagement quality, deal health, and ICP fit so you can prioritize which calls to analyze deeply vs. skim

2. WIN/LOSS PATTERN MATRIX — the top behavioral, linguistic, and contextual signals that predict deal wins vs. losses at each stage (e.g., "Deals where the buyer mentions ROI in the first 10 minutes close at 3x the rate of deals where ROI is never mentioned")

3. COMPETITIVE INTELLIGENCE LOG — a template and extraction protocol for capturing competitor mentions: what context triggers them, how buyers describe the alternative, what language wins the comparison, and what objections remain unresolved

4. BUYER LANGUAGE BANK — verbatim phrases buyers use to describe their problems, desired outcomes, and evaluation criteria — organized by persona, industry, and deal stage — for direct use in marketing copy, ads, and content

5. CONTENT GAP ANALYSIS — the top 10-15 questions buyers ask in conversations that marketing currently does not answer in any asset, ranked by frequency and deal-stage of occurrence

6. WEEKLY MARKETING INTELLIGENCE BRIEF TEMPLATE — a structured 1-page brief the marketing team receives every Monday, summarizing what the sales conversations from the prior week revealed about buyer sentiment, competitive pressure, messaging resonance, and emerging objections

For each of the above, generate:
- The specific extraction prompt to run against call transcripts (AI-ready — can be pasted into Gong AI, Chorus AI, or directly into ChatGPT/Claude with a pasted transcript)
- The output format and data structure (so output is consistent across hundreds of calls)
- The recommended analysis cadence (real-time per call, daily batch, weekly synthesis)

## Advanced Customizable Version

ROLE: You are a senior revenue intelligence architect with 12+ years of experience connecting sales conversation data to marketing strategy in B2B SaaS companies. You have built conversation intelligence programs at companies using Gong, Chorus, Clari, Outreach, and Salesloft, and you understand both the technical infrastructure of conversation analytics and the strategic application of conversation insights to demand generation, content strategy, competitive positioning, and ICP refinement. You recognize that most companies use conversation intelligence reactively (coaching individual reps) rather than proactively (surfacing macro patterns that improve marketing strategy). Your programs are designed to run at scale — analyzing hundreds of calls per month automatically — and to produce actionable marketing intelligence that does not require a human to sit through recordings.

---

CONVERSATION DATA CONTEXT:

*Call Volume & Distribution:*
- Total recorded calls per month: [e.g., "240"]
- Call type distribution: [e.g., "Discovery: 80, Demo: 60, Technical Evaluation: 40, Pricing/Proposal: 35, Closing: 25"]
- Win rate by stage (if known): [e.g., "Stage 1→2: 55%, Stage 2→3: 42%, Stage 3→4: 68%, Stage 4→Close: 71%"]
- Average call length by type: [e.g., "Discovery: 38 min, Demo: 52 min, Technical Eval: 67 min, Closing: 28 min"]
- Conversation tool in use: [Gong / Chorus / Clari / Zoom AI / Fireflies / Otter / Raw transcript export]
- AI/analytics capabilities available in tool: [e.g., "Gong Deals, Smart Trackers, Topic Detection"]
- CRM integration: [Salesforce / HubSpot / Pipedrive — with call data synced Y/N]
- Win/loss data available in CRM: [Yes/No — if yes, what fields are captured]

*Business & ICP Context:*
- Product category and primary value proposition: [e.g., "Workflow automation for operations teams — cuts manual process time by 60% and eliminates data silos between finance, ops, and CS systems"]
- Primary buyer persona(s): [e.g., "VP Operations (economic + technical buyer), CFO (economic buyer, ROI-focused), Senior Operations Manager (champion, daily user)"]
- Top 3-5 competitors named in deals: [e.g., "Zapier (cited by 44% of deals), Make.com (31%), UiPath (18%), Internal engineering build (14%)"]
- Current primary messaging (your homepage headline or positioning statement): [e.g., "The operations platform that replaces your spreadsheets, your manual handoffs, and your bottlenecks — without code"]
- Key objections your sales team encounters most: [e.g., "1. 'We already use Zapier for this' 2. 'Our IT team will build this in-house' 3. 'The price is hard to justify without board approval' 4. 'We need to see integration with [specific tool] first'"]
- Win themes most commonly cited in closed-won CRM notes: [e.g., "1. Best native integrations (ERP + CRM without workarounds) 2. Non-technical setup (ops team can manage without IT) 3. Dedicated onboarding + CSM support"]

---

MODULE 1 — CALL CLASSIFICATION & DEAL HEALTH SCORING

*Purpose: Triage your call library automatically so you know which calls to analyze deeply vs. which to skip*

Generate an AI-ready transcript analysis prompt that classifies each recorded call on the following dimensions:

**Dimension 1: Buyer Engagement Score (1-10)**
- Active listening signals: buyer asks clarifying questions, references prior conversations, takes notes (verbalized)
- Vocabulary signals: buyer uses product category language fluently (vs. needing education on basic concepts)
- Time-on-topic ratio: how much of the call is spent on the buyer's specific use case vs. generic product walkthrough
- Champion signal: buyer volunteers to set up an introduction to another stakeholder OR references internal discussions about the product

**Dimension 2: Pain Crystallization Score (1-10)**
- Has the buyer articulated a specific, named pain with a quantified or personal impact?
- Has the buyer connected the pain to a business outcome they are accountable for?
- Is the pain timeline urgent (active project, upcoming board review, regulatory deadline) or aspirational (someday we should fix this)?

**Dimension 3: ICP Fit Signal (1-10)**
- Firmographic match signals mentioned on the call (company size, industry, tech stack, team structure)
- Budget authority signal: has someone with budget authority participated in or been explicitly mentioned as supporting the evaluation?
- Use case match: does the specific workflow they describe match your sweet spot use cases (not edge cases)?

**Dimension 4: Competitive Pressure Score (1-10 where 10 = highest pressure)**
- Competitor named: which one(s), in what context (actively evaluating, currently using, considering switching from)
- Strength of alternative: is the alternative a serious contender or a fallback option?
- Champion's influence on competitive decision: is your champion also championing the competitor?

**Dimension 5: Deal Risk Score (1-10 where 10 = highest risk)**
- Vague next steps: no specific follow-up scheduled or agreed upon
- Stakeholder gaps: budget owner has not been identified or engaged
- Timeline ambiguity: no clear evaluation timeline or go-live target
- Objections unresolved: active objections were raised and not substantively addressed on the call

**Output Format per Call:**
Call ID: [auto or manual]
Date: [YYYY-MM-DD]
Stage: [Discovery / Demo / Technical Eval / Proposal / Closing]
Outcome (if known): [Won / Lost / Active / No Decision]
Buyer Engagement Score: [1-10] — key evidence: "[verbatim quote from call]"
Pain Crystallization Score: [1-10] — key evidence: "[verbatim quote]"
ICP Fit Signal: [1-10] — key evidence: "[verbatim quote]"
Competitive Pressure Score: [1-10] — competitors named: [list]
Deal Risk Score: [1-10] — primary risk: "[specific signal]"
COMPOSITE INTELLIGENCE VALUE: [Engagement + Pain + ICP - Risk] — prioritize calls scoring 20+ for deep analysis

---

MODULE 2 — WIN/LOSS PATTERN MATRIX

*Purpose: Identify the specific behavioral, linguistic, and contextual signals that statistically predict wins vs. losses at each deal stage*

Generate an analysis framework that, applied across 90 days of call data (minimum 50 won deals and 50 lost deals), produces a win/loss pattern matrix.

**Analysis Prompt (run against each closed-won and closed-lost transcript batch):**

For CLOSED-WON calls, extract:
- The exact moment (early, middle, or late in the call) when the buyer first expressed clear enthusiasm or urgency
- The specific language the buyer used when describing their pain — note verbatim phrases
- Which features or capabilities the buyer referenced as their primary decision criteria
- What the rep said immediately before the buyer's most positive response (the "winning move")
- Whether the buyer volunteered competitive comparison language — and if so, what they said about us vs. the alternative
- Which stakeholders were present on the call at the stage where momentum accelerated
- The buyer's stated or implied timeline for implementation

For CLOSED-LOST calls, extract:
- The last positive signal before deal momentum stalled — what was the turning point?
- What objection was raised most recently before the deal went cold?
- Which competitor was named (if any) — and what specific capability or characteristic did the buyer use to frame their preference for that alternative?
- What question(s) did the buyer ask that the rep could not answer confidently?
- Was there a gap between the buyer's stated use case and the product's documented strength? If so, what was it?
- Were there stakeholders mentioned but never introduced? Who were they and what role did they play?

**Output Format — Win/Loss Pattern Matrix:**

| Signal | Frequency in Won Deals | Frequency in Lost Deals | Win Rate Lift | Stage Where Signal Appears |
|---|---|---|---|---|
| Buyer mentions ROI or cost savings in Discovery | 78% | 31% | +3.2x | Discovery |
| Buyer requests specific integration (named tool) | 62% | 48% | +1.3x | Demo/Tech Eval |
| Champion uses phrase "my team needs this" | 71% | 19% | +3.7x | Any |
| Competitor named: Zapier (as current user) | 44% | 41% | +1.1x | Discovery |
| Competitor named: Internal build (as alternative) | 18% | 39% | -2.2x | Proposal |
| No specific next step set on call | 12% | 67% | -5.6x | Any |
[... complete with actual data from your call analysis]

**Marketing Action Protocol:** For each signal with a Win Rate Lift > 2.0x, generate a corresponding marketing asset recommendation — e.g., if "Champion uses phrase 'my team needs this'" appears in 71% of won deals, marketing should create champion enablement content that helps internal buyers sell their team on the solution.

---

MODULE 3 — COMPETITIVE INTELLIGENCE EXTRACTION

*Purpose: Build a dynamic competitive intelligence database from what buyers actually say in deals*

**Per-Call Competitive Extraction Prompt (run against every call where a competitor is mentioned):**

Extract from this transcript:
1. Which competitor was named? [exact name as buyer stated it]
2. In what context was the competitor mentioned? [currently using / actively evaluating / previously used / mentioned as future option / mentioned by a different stakeholder]
3. What specific capability, feature, or attribute did the buyer associate with the competitor? [exact quote if possible]
4. What was the buyer's emotional tone when mentioning the competitor? [positive / neutral / frustrated / skeptical]
5. What did the rep say in response? [exact quote or paraphrase]
6. What was the buyer's reaction to the rep's response? [accepted / challenged / moved on without resolution / requested more information]
7. Was this competitive objection resolved on this call? [Yes / No / Partially — describe]
8. If unresolved: what would have been the ideal response based on the conversation context?

**Competitive Intelligence Log (updated weekly from call batch):**

Competitor: Zapier
Total mentions this week: 14 (vs. 11 prior week — +27%)
Context breakdown: Currently using (9), Actively evaluating (3), Previously used (2)
Top buyer quotes:
  — "We already use Zapier for simple stuff but it breaks on anything complex" (Discovery, lost deal)
  — "The pricing for Zapier gets really unpredictable at scale" (Proposal, won deal)
  — "My IT team set up Zapier but ops can't manage it themselves" (Demo, won deal — used as win theme)
  — "Zapier just launched something that looks similar" (Closing, deal went dark)

Battle-tested winning responses (from won deals where Zapier was named):
  1. "That's a common starting point — Zapier is great for simple, stable workflows. Where we come in is when those workflows touch your ERP or CRM and need conditional logic, error handling, or audit trails. Want me to show you how that looks?"
  2. "The teams I work with most often have started with Zapier and hit a ceiling — usually around the 6-month mark when the workflows get complex enough that IT has to own them. Is that resonating with your experience?"

Unresolved objection: "Zapier just launched [feature]" — marketing needs a competitive response asset for this development
Action: PMM team to create a rapid competitive response card within 5 business days

---

MODULE 4 — BUYER LANGUAGE BANK

*Purpose: Extract verbatim buyer language for direct use in marketing copy, ad creative, and content*

**Extraction Prompt (run against all Discovery and Demo calls):**

From this transcript, extract:
1. How did the buyer describe their primary pain or problem? [exact verbatim quote — do not paraphrase]
2. How did the buyer describe what success would look like after solving this problem? [exact verbatim quote]
3. What words or phrases did the buyer use to describe their current state (before using a solution)? [exact verbatim quotes]
4. What external pressure or trigger did the buyer reference as the reason they're evaluating now? [exact verbatim quote]
5. How did the buyer describe their evaluation criteria when comparing options? [exact verbatim quote]
6. What did the buyer say that indicated highest emotional resonance with our value proposition? [exact verbatim quote — note: look for moments where the buyer's speech cadence slows, they ask a follow-up question, or they say something like "that's exactly what we're dealing with"]

**Buyer Language Bank Structure:**

*Pain Language (by persona):*
- VP Operations: [curated quotes that express their operational pain in their own words]
- CFO: [curated quotes that express ROI and risk concerns in their own words]
- Senior Operations Manager: [curated quotes that express day-to-day frustration in their own words]

*Outcome Language (what buyers say they want, verbatim):*
- [quote 1 — note: this is directly usable in ad copy]
- [quote 2 — note: this is directly usable as a case study opener]

*Trigger Language (what caused them to start evaluating now):*
- [triggers most frequently cited — ranked by frequency]

*Evaluation Criteria Language (how buyers describe what they're looking for):*
- [verbatim criteria language organized by decision-making weight]

**Usage Rule:** Every new landing page, ad creative, and case study headline must be audited against the Buyer Language Bank — if the copy uses language that never appears in the Bank, it requires a buyer language justification before approval.

---

MODULE 5 — ICP REFINEMENT FROM CONVERSATION SIGNALS

*Purpose: Use conversation data to sharpen or challenge your ICP definition*

**Monthly ICP Signal Analysis (run quarterly):**

Analyze the last 90 days of call data (all stages, all outcomes) and extract:

**ICP Confirmation Signals** (firmographic and behavioral patterns that appear more frequently in won deals than lost deals):
- Company revenue range: which range wins most often?
- Team size: what operations team size correlates with highest win rates?
- Tech stack: which existing tools predict product fit (and which predict low fit)?
- Growth stage: which company growth phase (Series A, B, C, enterprise) wins most?
- Trigger event: what business event most commonly precedes the start of an evaluation?
- Stakeholder composition: what combination of personas in the buying group predicts highest win rate?

**ICP Challenge Signals** (patterns that appear frequently in your pipeline but not in your won deals — suggest misaligned targeting):
- Which buyer segments are taking meetings but not converting to opportunities?
- Which industries appear more in your pipeline than in your customer base?
- Which stated use cases appear frequently in lost deals but rarely in won deals?

**ICP Expansion Signals** (patterns in won deals that don't match your current ICP definition):
- Are there winning deals from unexpected company sizes, industries, or regions?
- Are there recurring use cases in won deals that aren't reflected in your primary messaging?

**Output:** A quarterly ICP calibration report that marketing uses to update targeting criteria for paid campaigns, ABM lists, and content strategy.

---

MODULE 6 — CONTENT GAP ANALYSIS

*Purpose: Identify buyer questions that marketing doesn't currently answer, ranked by frequency and deal impact*

**Weekly Content Gap Extraction (run against all calls):**

From this transcript, extract every question the buyer asked that:
- Was NOT answered satisfactorily on the call (rep said "let me get back to you" or buyer repeated the question)
- OR was answered but required significant explanation (suggesting a content asset could pre-answer it and accelerate the sale)
- OR touched on a topic (integration, security, compliance, pricing model, implementation timeline) that would benefit from a dedicated asset

**Content Gap Analysis Output (weekly batch):**

| Buyer Question | Frequency (calls/month) | Deal Stage | Outcome Correlation | Current Asset? | Asset Priority |
|---|---|---|---|---|---|
| "How does this integrate with [NetSuite / SAP / Dynamics]?" | 34 | Demo/Tech Eval | Neutral (present in 62% won, 59% lost) | Partial (one-page overview) | Medium |
| "How long does implementation actually take?" | 28 | Proposal | Win-negative (appears 44% more in lost deals) | No dedicated asset | High |
| "What happens if an automated workflow fails?" | 22 | Technical Eval | Win-positive (89% of buyers who got a satisfying answer converted) | FAQ buried in help center | High |
| "Can I try this without involving IT?" | 19 | Discovery | Win-positive (strong ICP signal) | No dedicated landing page | High |
| "What does your security certification cover?" | 17 | Technical Eval | Deal-critical (if unanswered, deal stalls 73% of the time) | SOC 2 doc (not public-facing) | Critical |
[... complete with your actual call data]

**Content Gap Action Protocol:** Top 5 gaps (by Priority × Frequency) are assigned to a content owner within 5 business days of the weekly report. Gap is considered "closed" when a buyer-facing asset exists AND the asset has been tested on 3 live calls without the question recurring.

---

MODULE 7 — WEEKLY MARKETING INTELLIGENCE BRIEF

*Purpose: Convert the week's conversation data into a 1-page brief that the marketing team reads every Monday morning*

**Brief Template:**

---

**CONVERSATION INTELLIGENCE BRIEF**
Week of [DATE] | [X] calls analyzed | [X won, X lost, X active]

**EXECUTIVE SUMMARY** (3 bullets)
- [Most important marketing insight from this week's calls — 1 sentence]
- [Most urgent competitive development surfaced this week — 1 sentence]
- [Top content gap identified this week — 1 sentence]

**WIN THEMES THIS WEEK** (from won deals closed this week)
- [Win theme 1: what the buyer cited as the primary reason they chose us]
- [Win theme 2]
- [Win theme 3]
- Quote of the week: "[verbatim buyer quote from a won deal — usable in marketing copy]"

**COMPETITIVE INTELLIGENCE**
- Competitor mentioned most: [name] — [X calls, up/down X% vs. prior week]
- New competitive development: [any new competitor feature, pricing change, or market move mentioned by buyers]
- Best response used in won deals: "[verbatim rep response that worked]" — [context]
- Unresolved competitive objection requiring a marketing response: [describe]

**BUYER LANGUAGE UPDATE**
- New phrases added to Buyer Language Bank this week: [list]
- Pain language shift: [any new way buyers are describing the problem that differs from prior weeks]

**CONTENT GAPS (NEW THIS WEEK)**
- [Question that surfaced ≥3 times this week with no adequate current asset]
- [Second new gap if applicable]

**ICP SIGNAL UPDATE**
- Strongest ICP signal in won deals this week: [firmographic or behavioral pattern]
- Weakest ICP fit signal in lost deals this week: [what losing buyers had in common]

**MARKETING ACTION ITEMS**
- [ ] [Specific asset to create — assigned owner — due date]
- [ ] [Competitive response to develop — assigned owner — due date]
- [ ] [Targeting adjustment recommendation — assigned owner — due date]

---

CONSTRAINTS:
- Every insight in this prompt must be traceable back to an exact call (call ID, date, stage) — no unverifiable generalizations
- Buyer language must be verbatim or clearly labeled as "paraphrased" — never fabricated
- Win/loss pattern data requires minimum 25 calls per cohort to report a pattern — below that, flag as preliminary signal
- Competitive intelligence must be current (within 60 days) — stale competitive data is labeled with a staleness warning
- Content gap priorities must be set jointly with sales leadership — marketing cannot unilaterally define what constitutes a "critical" gap
- ICP signals require 90-day minimum data window before any targeting change is made — don't over-rotate on small sample sizes

## Example Input/Output

**Input Example:**
- Company: Corvia AI — AI-powered workflow automation for operations and finance teams
- ICP: VP Operations and CFO at B2B companies $15M-$150M ARR, 50-500 employees
- ACV: $34K, Sales cycle: 51 days average
- Calls analyzed this week: 47 (12 Discovery, 18 Demo, 9 Technical Eval, 8 Closing)
- Win rate: 23% trailing 90 days
- Competitors most named: Zapier (44%), Make.com (27%), "We'll build it in-house" (19%)

---

**Output Example (Module 7 — Weekly Intelligence Brief, abbreviated):**

---

**CONVERSATION INTELLIGENCE BRIEF**
Week of July 7, 2026 | 47 calls analyzed | 6 won, 9 lost, 32 active

**EXECUTIVE SUMMARY**
- Buyers at companies going through ERP migrations are showing 3x higher urgency signals than baseline — this is an untapped trigger event for paid campaigns
- Make.com is now being mentioned in early-stage Discovery calls (previously only appeared at Demo+), suggesting they're increasing their awareness spend in our ICP
- The question "Can we run a pilot with one team before rolling out company-wide?" appeared 11 times this week — we have no asset addressing phased implementation

**WIN THEMES THIS WEEK** (6 closed-won deals)
- Win theme 1: Non-technical implementation — "Your team set this up in a day. We spent 3 months with Zapier and still needed IT." (3 of 6 wins cited this)
- Win theme 2: ERP-native integration — buyers at Netsuite shops closed at 2.1x higher rate than average
- Win theme 3: Dedicated CSM included in plan — buyers who had a CSM introduction before signing closed at 1.8x higher rate

Quote of the week (from CFO at a 200-person logistics company, closing call):
*"We're not buying workflow software. We're buying back the 30 hours a week my ops lead is spending on things a computer should handle."*

**COMPETITIVE INTELLIGENCE**
- Competitor mentioned most: Zapier — 21 of 47 calls (+31% vs. prior 4-week average)
- New competitive development: Make.com was mentioned in 4 early Discovery calls as "something we saw an ad for" — previously only appeared post-Demo. Likely a new acquisition campaign targeting our ICP
- Best response used in won deals (against Zapier): "Zapier is excellent for simple, stable 2-app workflows. Where teams run into trouble is complex multi-system processes that touch your ERP — those require error handling, audit logging, and conditional branching that Zapier doesn't do well. I can show you exactly what that looks like in a 10-minute technical walkthrough."
- Unresolved: 3 buyers this week asked about Make.com's "enterprise tier" that was apparently announced last month — marketing needs a competitive comparison card within 7 days

**BUYER LANGUAGE UPDATE**
- New phrases added to Bank:
  - Pain: *"We're basically using spreadsheets to track spreadsheets"* (appeared 5 times)
  - Outcome: *"I want my team working on exceptions, not on the process"* (appeared 4 times)
  - Trigger: *"We're going live on NetSuite in Q3 and we need the integrations to be ready"* (appeared 7 times — ERP migration trigger is significant)

**CONTENT GAP (NEW THIS WEEK)**
- Question: "Can we pilot with one team before company rollout?" — appeared 11 times, no current asset, appeared equally in won (5) and lost (6) deals — critical asset because it's a decision accelerator for buyers, not a red flag

**MARKETING ACTION ITEMS**
- [ ] Create phased implementation one-pager addressing "pilot with one team" question — Content team (Sarah M.) — Due July 14
- [ ] Build Make.com competitive comparison card — PMM (Derek T.) — Due July 14
- [ ] Launch targeted LinkedIn campaign with ERP migration trigger message to NetSuite/SAP Concur user segments — Paid media (Jess K.) — Due July 21

---

## Success Metrics

- **Call intelligence coverage rate:** Percentage of recorded calls analyzed per week vs. total calls recorded — target ≥ 80% coverage within 60 days of program launch; if below 60%, the extraction automation is underbuilt
- **Content gap closure rate:** Of the top 5 content gaps identified each month, what percentage are closed (asset created AND tested on live calls) within 30 days — target ≥ 3 of 5 closed per month
- **Win/loss pattern accuracy:** After 90 days of pattern data, validate your top 5 win signals prospectively — apply them to active deals and measure whether deals with the signal present actually win at the predicted higher rate; target ≥ 70% predictive accuracy
- **Buyer language adoption rate:** Percentage of new marketing assets (landing pages, ads, case studies) that incorporate verbatim or near-verbatim phrases from the Buyer Language Bank — target ≥ 80% of new assets within 90 days of program launch
- **Competitive intelligence response time:** Time from first mention of a competitive development in calls to a marketing response asset being available to reps — target ≤ 7 business days for high-frequency competitive mentions (≥ 5 mentions/week)
- **ICP signal confirmation rate:** Quarterly — do the ICP signals extracted from conversation data (firmographics, tech stack, trigger events) match the actual profile of your best customers in the CRM? Target ≥ 75% alignment; misalignment suggests either conversation data is being mined incorrectly OR your CRM ICP data is stale
- **Marketing brief utilization rate:** Track how often the Marketing Intelligence Brief leads to a documented action (campaign change, asset creation, targeting update) — target ≥ 3 actions per brief; if below 2, the brief isn't actionable enough or isn't reaching the right audience
- **Rep perception score:** Quarterly survey of AEs/SDRs asking "How useful is the marketing intelligence program to your deal-handling?" — target ≥ 7/10 average; below 5/10 means the program is producing insights that aren't reaching or resonating with frontline sellers

## Related Prompts
- [AI-Powered B2B SaaS Sales Enablement Content Analytics & Revenue-Enabling Asset Performance Intelligence Engine](./AI-Powered-B2B-Sales-Enablement-Content-Analytics-&-Revenue-Enabling-Asset-Performance-Intelligence-Engine.md)
- [AI-Powered B2B Sales Enablement Program ROI & Enablement-to-Revenue Impact Intelligence Engine](./AI-Powered-B2B-Sales-Enablement-Program-ROI-&-Enablement-to-Revenue-Impact-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Competitive Messaging Audit & Category Narrative Ownership Intelligence Engine](../../02_Product-Marketing/Competitive-Intelligence/AI-Powered-B2B-SaaS-Competitive-Messaging-Audit-&-Category-Narrative-Ownership-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Continuous Buyer Research Program Architecture & Rapid Insight Synthesis Intelligence Engine](../../02_Product-Marketing/Customer-&-Market-Research/AI-Powered-B2B-SaaS-Continuous-Buyer-Research-Program-Architecture-&-Rapid-Insight-Synthesis-Intelligence-Engine.md)

## Integration Tips

- **Gong:** Use Gong's Smart Trackers to automatically flag calls containing competitor names, objection keywords, and ROI language — this pre-classifies calls for Modules 2, 3, and 4 without manual review. Set up a Gong Workspace called "Marketing Intelligence" and grant your PMM team view-only access to deal-level trackers. Use Gong's Export API to pull weekly transcript summaries into a Google Sheet that feeds the Weekly Brief template. Gong's "Topics" feature surfaces calls where specific themes (integration, pricing, timeline) were discussed — use this to prioritize the call queue for Module 6 (Content Gap Analysis).

- **Chorus (ZoomInfo):** Use Chorus Deal Intelligence to surface calls with anomalous engagement patterns — calls where buyer talk-time drops sharply below 40% are high-risk signals to flag for Module 2 (Win/Loss Analysis). Chorus's "Moments" feature auto-extracts key phrases and questions — configure it with a custom Moments taxonomy mapped to the content gap categories in Module 6. Set up a Chorus Smart Playlist called "Buyer Language Library" that automatically adds clips where buyers use strong emotional language about their pain.

- **Salesforce / HubSpot:** Create a custom field on the Opportunity record called "Conversation Intelligence Score" (from Module 1) that syncs weekly from your call tool via Zapier or native API. Build a Salesforce report called "Win/Loss Intelligence" that segments closed deals by the conversation signals extracted from calls, giving revenue operations a view of which marketing-influenced touchpoints appeared in won vs. lost deals. In HubSpot, use a custom property called "ICP Confidence Score" (derived from Module 5 signals) to filter your target account list for ABM campaigns.

- **Notion / Confluence:** Build a "Conversation Intelligence Wiki" in Notion with four main databases: Buyer Language Bank, Competitive Intelligence Log, Content Gap Tracker, and Win/Loss Pattern Matrix. Each database should have a "Last Updated" field and a "Confidence Level" field (based on sample size). The Weekly Brief should be auto-drafted from these databases using Notion AI or a connected automation. Marketing team members tag relevant entries as they use them in assets, creating a feedback loop on what buyer language actually converts.

- **Slack:** Create a private Slack channel called `#conversation-intelligence` where the Weekly Brief is posted every Monday morning. Create a Gong or Chorus Slack integration that pushes real-time alerts to this channel when a high-priority competitor (e.g., a named strategic threat) is mentioned in any recorded call — this allows PMM to act within hours rather than waiting for the weekly brief. Use a Slackbot to prompt reps after each closed deal (won or lost) to log the primary win/loss reason with a custom emoji taxonomy — this supplements AI-extracted data with seller judgment.

- **Zapier / Make:** Build an automation that: (1) detects when a call is marked as "Closed Won" or "Closed Lost" in the CRM, (2) triggers a transcript pull from Gong/Chorus API, (3) sends the transcript to Claude/ChatGPT with the Module 2 extraction prompt, (4) parses the output into a structured JSON format, and (5) appends the result to a Google Sheet that feeds the weekly pattern analysis. This automation eliminates the manual step of routing transcripts and can process 200+ calls per week with no human intervention.

## Troubleshooting

**Problem: The extraction prompts are producing inconsistent output — some transcripts yield detailed, structured intelligence and others yield vague summaries that aren't actionable**
Solution: Transcript quality is the primary driver of extraction quality. Calls with poor audio, multiple speakers talking simultaneously, or non-verbatim transcription (AI-paraphrased rather than word-for-word) produce low-quality extraction results. Diagnose by running the Module 1 scoring prompt against 20 random transcripts and comparing transcript length (words) to extraction quality — you'll likely find calls under 3,000 words produce poor results regardless of call duration. Short transcripts indicate either poor audio capture or AI compression by the conversation tool. Fix: configure your conversation tool to output verbatim transcripts rather than AI-summarized versions, and ensure all call recordings are set to dual-channel audio. Additionally, pre-process transcripts by removing filler words (um, uh, you know) and standardizing speaker labels (BUYER vs. REP) before running extraction prompts — this improves extraction accuracy by 20-30%.

**Problem: Sales reps are resistant to the conversation intelligence program — they see it as surveillance rather than enablement, and are declining to record calls or record with the microphone off**
Solution: This is a change management problem, not a technical one. Reps resist the program when they believe the output is used to evaluate their performance rather than to improve marketing. Fix this by establishing a clear program charter that states: (1) call recordings used in this program are never used in individual performance reviews, (2) the program extracts aggregate patterns — no individual rep's calls are attributed by name in marketing outputs, and (3) rep names are suppressed from the Weekly Brief before it's shared with marketing. Share the first Monthly Report back to the sales team with a specific section called "What Marketing Did Because of What You Said" — showing exactly which assets were created, which campaigns were launched, and which targeting changes were made based on conversation data. Reps who see their calls producing marketing improvements become advocates for the program within 60 days.

**Problem: The Weekly Marketing Intelligence Brief is being read but not acted on — marketing team members acknowledge receiving it but no assets are being created, no campaigns are being changed**
Solution: Insights without ownership don't become action. The brief is failing not as a document but as an accountability system. Fix by adding two structural changes: (1) each action item in the brief must have a named owner and a specific due date before it leaves the analyst's desk — "Marketing team should consider X" is not an action item; "Sarah M. will draft a one-pager addressing [gap] by [date]" is, and (2) open each Monday team meeting with a 5-minute "last week's brief, this week's actions" review — the analyst reads the top 3 action items from the previous week's brief and confirms completion status before presenting new findings. Teams that skip the accountability review tend to treat the brief as FYI reading. Teams that build it into their weekly ritual consistently execute at 80%+ action item completion rates within 60 days.

## Version History
- v1.0: Initial creation (auto-generated)
