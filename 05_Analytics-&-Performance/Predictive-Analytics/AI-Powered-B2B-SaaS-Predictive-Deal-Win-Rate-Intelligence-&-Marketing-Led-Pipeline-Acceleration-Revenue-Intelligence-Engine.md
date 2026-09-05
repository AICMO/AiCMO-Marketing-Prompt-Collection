# AI-Powered B2B SaaS Predictive Deal Win Rate Intelligence & Marketing-Led Pipeline Acceleration Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** predictive-analytics, deal-scoring, win-rate, pipeline-acceleration, meddpicc, revenue-intelligence, clari, gong, salesforce, b2b-saas, deal-rescue

## Overview
This prompt builds a predictive win rate model that scores every active pipeline opportunity by likelihood to close — then prescribes specific marketing-led interventions for at-risk deals. It transforms marketing from a top-of-funnel factory into a real-time pipeline rescue function, directly accountable for this-quarter revenue.

## Quick Copy-Paste Version

You are a senior revenue intelligence analyst and deal strategy expert. Help me build a predictive win rate model for our active pipeline and prescribe specific marketing actions to save at-risk deals.

Our pipeline context:
- Total active opportunities: [X deals, $X total ACV]
- Average deal size: $[X] ACV
- Historical close rate (last 12 months): [X]%
- Average sales cycle length: [X] days
- Current quarter close target: $[X]
- CRM stages: [list your deal stages]

Our win/loss signal data (from last 24 months of closed deals):
- POC/trial completed: Win rate with POC = [X]%, without = [X]%
- Economic buyer (CFO/CEO) engaged: With = [X]%, without = [X]%
- Champion identified and active: With = [X]%, without = [X]%
- Competitor in deal: Win rate vs. [Competitor A] = [X]%, [Competitor B] = [X]%
- Buying committee size: 1-2 contacts = [X]%, 3-5 contacts = [X]%, 6+ contacts = [X]%
- Deal stuck in stage beyond average: [X]% close rate when >2x average stage duration

My top 5 at-risk deals:
- [Deal 1]: [Company], $[X] ACV, [Stage], [X] days in stage (avg is [Y]), [what worries me]
- [Deal 2]: [Company], $[X] ACV, [Stage], [X] days in stage (avg is [Y]), [what worries me]
- [Deal 3]: [Company], $[X] ACV, [Stage], [X] days in stage (avg is [Y]), [what worries me]
- [Deal 4]: [Company], $[X] ACV, [Stage], [X] days in stage (avg is [Y]), [what worries me]
- [Deal 5]: [Company], $[X] ACV, [Stage], [X] days in stage (avg is [Y]), [what worries me]

Marketing resources available:
- Customer references available: [X] (industries: [list])
- Analyst reports I can deploy: [list Gartner/Forrester available]
- Case studies by industry: [list]
- Executive sponsor availability: [X calls/month from CMO/CEO]
- ROI calculator: [available for which verticals]

Deliver:
1. WIN RATE SCORE: Score each deal 0-100 with the specific factors driving the score up or down
2. RISK CLASSIFICATION: Green (70+), Yellow (40-69), Red (<40) with top 3 risk factors per deal
3. MARKETING RESCUE PLAYBOOK: For each Red and Yellow deal, week-by-week marketing intervention sequence (assets, channels, stakeholders, timing)
4. BUYING COMMITTEE GAP MAP: Which titles/roles are missing from each at-risk deal and how to engage them through marketing channels
5. COMPETITIVE COUNTER-PLAY: For any deal with a named competitor, specific positioning assets and messaging to deploy in the next 7 days
6. REVENUE FORECAST: Given scored probabilities, expected revenue vs. target and how much the interventions could recover

## Advanced Customizable Version

**ROLE:**
You are a VP of Revenue Intelligence with 13+ years building predictive deal scoring systems for B2B SaaS companies from $8M to $800M ARR. You have deep expertise in MEDDPICC deal qualification, conversation intelligence platforms (Gong, Chorus, Clari), AI-powered pipeline analytics, and the specific mechanics of marketing-led pipeline acceleration in the final 60 days of a deal cycle. You have increased win rates by 15–40% at multiple SaaS companies by systematically deploying marketing assets into at-risk enterprise deals rather than only focusing on top-of-funnel pipeline creation. You think in signal weights, buying committee dynamics, intervention ROI, and quarter-close mechanics.

**OBJECTIVE:**
Build a comprehensive, repeatable predictive deal win rate intelligence system for [Company Name]'s active pipeline that: (1) scores every in-flight opportunity by close probability using MEDDPICC signal weighting, (2) identifies the specific gaps and red flags driving each deal's risk, (3) prescribes precision marketing interventions that marketing can execute autonomously within [X] business days, and (4) delivers a pipeline revenue forecast with confidence intervals.

**CONTEXT:**
- Company: [Company Name], [stage: Series A/B/C/public], [ARR: $X]
- Product/Category: [What you sell and to whom]
- Segments Served: [SMB / Mid-Market / Enterprise / mixed]
- ACV Range: [Low: $X] to [High: $X], Average: $[X]
- CRM: [Salesforce / HubSpot / other — specify deal stage names]
- Conversation Intelligence: [Gong / Chorus / Clari / none]
- Intent Data Active: [6sense / Bombora / G2 Buyer Intent / none]
- Current Quarter: [Q? FY?], [X] days remaining
- Win Rate (last 4 quarters): Q-4: [X]%, Q-3: [X]%, Q-2: [X]%, Q-1: [X]%
- Stage-by-stage conversion rates: [MQL→SAL: X%, SAL→Opp: X%, Opp→Proposal: X%, Proposal→Close: X%]
- Average stage durations: Discovery: [X] days, Technical Evaluation: [X] days, Proposal: [X] days, Negotiation: [X] days
- Top 3 active competitors and historical win rates vs. each: [list]
- Close date distribution in current pipeline: [X deals closing in <30 days, X in 31-60 days, X in 61-90 days]

**FULL ACTIVE PIPELINE:**

For each deal, provide:
| Field | Details |
|-------|---------|
| Deal Name | |
| Company | |
| ACV | |
| Current Stage | |
| Days in Current Stage | |
| Stage Average (benchmark) | |
| Champion Identified | Yes/No/Unclear |
| Champion Title | |
| Champion Engagement (last 7 days) | Active/Gone quiet/Never strong |
| Economic Buyer (CFO/CEO) Met | Yes (X times) / No |
| Technical Evaluator Identified | Yes/No |
| Legal/Security Review Started | Yes/No |
| POC/Trial Status | Completed (score: X/10) / In progress / Not started |
| Competitor(s) in Deal | [Names] or None identified |
| Total Contacts Engaged | [X] unique individuals |
| Marketing Touches (last 30 days) | [X] touches across [channels] |
| Last Inbound Engagement | [X days ago] |
| Forecasted Close Date | |
| Sales Rep Assessment | [Commit / Upside / Pipeline] |
| Known Risk Flags | [Your read on what's wrong] |

**HISTORICAL WIN SIGNAL WEIGHTS** (populate from your closed-won/closed-lost data):

| Signal | Win Rate With | Win Rate Without | Weight in Model |
|--------|--------------|-----------------|-----------------|
| POC completed with score 7+/10 | [X]% | [X]% | [High/Med/Low] |
| Economic buyer engaged 2+ times | [X]% | [X]% | |
| Champion sent internal email thread | [X]% | [X]% | |
| 5+ unique contacts engaged | [X]% | [X]% | |
| Mutual action plan signed | [X]% | [X]% | |
| Legal review started by [stage] | [X]% | [X]% | |
| Deal stuck >2x avg stage duration | [X]% | [X]% | |
| Competitor Vendor A in deal | [X]% win rate | — | |
| No competitor identified | [X]% win rate | — | |
| CMO/CEO executive sponsor introduced | [X]% | [X]% | |

**MARKETING RESOURCES AVAILABLE FOR DEPLOYMENT:**

Tier 1 (can deploy in <48 hours):
- Digital assets: [List case studies, ROI calculators, competitive comparisons, analyst reports available]
- LinkedIn Thought Leader Ads targeting specific accounts: [Budget available: $X/week]
- Targeted email sequences: [Capacity to create: X/week]
- Champion enablement content: [Business case templates, internal selling decks]

Tier 2 (can deploy in 3-5 days):
- Custom one-pagers or solution briefs: [Industries/use cases available]
- Customer reference calls: [Number available this quarter, industries: list]
- Executive briefing center/virtual EBC: [Slots available: X/month]
- Custom ROI models: [Capacity: X/week]

Tier 3 (requires 7-10 days):
- Executive sponsor calls (CMO/CEO): [Slots available: X/month — save for highest ACV]
- Joint co-marketing with customer advocates: [Partners available]
- Custom competitive battle kits: [For which competitors]

**DELIVERABLES REQUIRED:**

**1. PREDICTIVE DEAL SCORING TABLE (Non-Negotiable)**
For every deal in pipeline:
- Score 0-100 using weighted MEDDPICC + behavioral signal model
- Color classification: Green (70+) / Yellow (40-69) / Red (<40)
- Top 3 specific risk factors driving score down
- Single highest-leverage intervention to increase score
- Estimated close probability this quarter (%)
- Recommended action urgency: Immediate (this week) / Near-term (2-3 weeks) / Monitor

**2. DEAL RESCUE PLAYBOOKS — RED DEALS FIRST (Priority 1)**
For each deal scoring below 40, deliver a 3-week intervention plan:

*Week 1 — Diagnose & Stabilize:*
- Specific diagnostic question for AE to ask to confirm root cause
- Marketing asset to send to champion this week (exact asset name)
- Specific stakeholder to engage and through which channel (email, LinkedIn, exec intro)
- Signal to watch: what would confirm the intervention is working?

*Week 2 — Accelerate:*
- Second-tier escalation if Week 1 signals are still negative
- Executive resource to deploy (reference call, EBC, sponsor intro) if warranted
- Competitive counter-asset if a competitor is present
- Buying committee gap: which missing stakeholder to target and how

*Week 3 — Force a Decision:*
- Marketing-supported urgency creation (timeline, pricing milestone, customer event)
- Final proof asset to deploy (case study from peer company, analyst quote, benchmark)
- Walk-away trigger: if [X] signals remain absent after 3 weeks, deprioritize this deal

**3. BUYING COMMITTEE COVERAGE MAP (Priority 1)**
For each at-risk deal:
- Which MEDDPICC roles are currently covered (Champion, Economic Buyer, Technical Evaluator, End User, Legal/Security, Influencer)
- Single highest-value missing role to engage (by title, function, and why they matter in this deal)
- Recommended engagement approach for missing role:
  - Marketing channel (LinkedIn personalized InMail, targeted ad, email sequence, peer intro)
  - Content hook tailored to their likely concern (ROI for economic buyer, security for CISO, ease-of-use for end user)
  - Template or script for champion to use to broker the introduction
- Timeline to engage this stakeholder: [X] business days

**4. COMPETITIVE DEFENSE BRIEF (Priority 2)**
For each deal with an identified competitor:
- Our win rate history vs. this specific competitor and what it means
- The 3 things that competitor is almost certainly saying about us (and how to counter each)
- Marketing assets to place in front of the champion within 48 hours (specific documents)
- 1-page "Champion Talking Points" for using our differentiation in internal meetings
- Paid media tactic: Should we run competitive retargeting against this account? If yes, what creative angle and budget?

**5. PIPELINE REVENUE FORECAST WITH CONFIDENCE INTERVALS (Priority 2)**
- Base case: Sum of (ACV × win probability) for all deals
- Upside case: If marketing interventions move all Yellow deals +15 points (historical avg lift from intervention)
- Downside case: If all deals stuck >2x stage average slip one quarter
- Coverage ratio: Current pipeline ACV ÷ remaining quota
- Marketing-recoverable gap: How much revenue is theoretically rescuable through intervention vs. requires new pipeline creation

**6. REPEATABLE WEEKLY PIPELINE RESCUE RITUAL (Priority 3)**
A templated workflow marketing can run every Monday morning:
- Data inputs to pull from CRM (deal stage movement, days-in-stage, engagement signals)
- Score refresh: which signals to re-check weekly
- Decision tree: at what score threshold does each escalation tier trigger?
- Intervention assignment: who on the marketing team owns which deal types?
- Sales communication template: weekly deal support email from marketing to AE
- Success tracking: how to measure intervention lift week-over-week

**CONSTRAINTS:**
- All interventions must be deployable within [X] business days — no multi-week content projects
- Executive sponsor resources (CEO/CMO calls) limited to [X] per quarter — allocate only to deals ≥$[X] ACV
- Total marketing intervention cost per deal should not exceed [X]% of deal ACV
- All competitive claims must be defensible with public evidence (analyst reports, review sites, benchmarks) — no unsupported attack messaging
- In the final [X] days of the quarter, do not recommend interventions that require sales rep outreach changes — focus on async marketing channels only (ads, email, content drops)

**OUTPUT FORMAT:**
- Executive summary (5 bullets, max 150 words)
- Deal scoring table (all active deals, sorted Red → Yellow → Green)
- Red deal rescue playbooks (full 3-week plans, one per Red deal)
- Yellow deal intervention summaries (condensed 1-week actions)
- Competitive defense briefs (one per competitor present in pipeline)
- Pipeline revenue forecast model with three scenarios
- Weekly ritual template (copy-paste ready)

## Example Input/Output

**Example Input:**

Company: Luminary Analytics (Series B, $42M ARR)
Product: Enterprise data governance & observability platform
ACV Range: $75K–$420K, Average: $165K
Segments: Mid-Market and Enterprise
Win Rate: 38% overall; 54% when POC scores 8+; 23% when no economic buyer engaged
Top Competitors: DataTrust Pro (our win rate vs them: 44%), Collibra (win rate: 31%)
Quarter: Q3 FY2026, 34 days remaining
Q3 Close Target: $2.4M

Top 3 At-Risk Deals:

Deal 1 — Meridian Health System
$310K ACV | Negotiation stage | 41 days in stage (avg: 11 days)
Champion: VP of Data Architecture (active, enthusiastic)
Economic buyer (CFO): Met once 90 days ago, no engagement since
Competitor: DataTrust Pro actively in deal
POC: Completed, scored 8.5/10 by technical team
Contacts engaged: 7 unique individuals
Risk flags: CFO has gone dark; DataTrust Pro submitted competing proposal last week

Deal 2 — Apex Industrial Manufacturing
$195K ACV | Technical Evaluation | 28 days in stage (avg: 16 days)
Champion: unclear — CTO and IT Director both loosely engaged but neither owns the project
Economic buyer: Not identified
Competitor: None identified
POC: Not started
Contacts: 3 unique individuals
Risk flags: No clear champion, no executive sponsorship, evaluation stalling

Deal 3 — Coastal Private Equity (GP)
$385K ACV | Proposal Review | 52 days in stage (avg: 9 days)
Champion: CTO (engaged but engagement has dropped to 0 touches in last 3 weeks)
Economic buyer: Managing Director (met twice in discovery)
Competitor: None identified
POC: Completed, scored 9/10
Contacts: 11 unique individuals, but last inbound activity was 22 days ago
Risk flags: Complete engagement silence after strong start — buying committee fragmentation suspected; potential internal budget reallocation

---

**Example Output:**

**EXECUTIVE SUMMARY**
- Three deals totaling $890K ACV are at elevated risk; combined interventions could recover $520K in Q3 revenue
- Coastal PE ($385K) is the highest-value rescue opportunity — engagement ghost pattern after strong POC suggests internal realignment, not loss; exec sponsor bridge call must happen within 5 days
- Meridian Health ($310K) is in active competitive battle — CFO gap is the single deal killer; peer CFO reference from Atrium Health must deploy by Wednesday
- Apex Industrial ($195K) lacks a champion entirely; fast-track champion development or qualify out by Day 14 to protect team bandwidth
- Marketing can directly influence $520K recovery with interventions totaling approximately $3,200 in paid media and ~22 hours of team time

---

**DEAL SCORING TABLE**

| Deal | ACV | Score | Status | Top 3 Risk Factors | Win Probability | Urgency |
|------|-----|-------|--------|-------------------|-----------------|---------|
| Coastal PE | $385K | 38/100 | Red | 1. Engagement silence 22 days; 2. Buying committee fragmentation; 3. Deal velocity dead | 28% | Immediate |
| Meridian Health | $310K | 42/100 | Yellow | 1. CFO dark 90 days; 2. Competitor submitted proposal; 3. 4x avg stage duration | 34% | Immediate |
| Apex Industrial | $195K | 22/100 | Red | 1. No champion; 2. No economic buyer; 3. No POC started | 14% | Qualify or rescue by Day 10 |

---

**DEAL RESCUE PLAYBOOK — COASTAL PRIVATE EQUITY ($385K) — Red**

*Root Cause Hypothesis:* Engagement silence after a 9/10 POC is almost never a "no" — it typically signals one of three things: (1) internal budget fight pulled decision authority to a stakeholder we haven't met, (2) a competing internal priority emerged that paused the project, (3) the champion is facing internal resistance and doesn't know how to navigate it. Do NOT let the sales team interpret silence as a soft no.

**Week 1 — Diagnose & Re-Engage:**

Day 1 (Sales + Marketing, joint play):
- AE sends champion (CTO) the following message: *"Hi [Name] — I want to make sure we're making this easy for you. I know things get complex internally on projects like this. Can we grab 15 minutes this week — not to sell, just to understand where things stand from your end and whether there's anything I can help you navigate?"* — this is a diagnostic call, not a follow-up
- Marketing simultaneously deploys a LinkedIn Thought Leader Ad targeting the Managing Director's LinkedIn profile with the Luminary "Data Governance ROI for Financial Services" case study ($600 budget for 7-day run)
- Marketing sends CTO a "Customer Evidence Pack" (no sales pitch): three 1-page client outcome stories from PE/financial services firms — frame as "I thought these might be useful as you're working through internal conversations"

Day 3:
- If no response from CTO: Marketing escalates to CMO sponsor intro email, targeting Managing Director directly: *"I wanted to personally share a brief note — we rarely reach out at this stage, but given the strength of your team's evaluation, I wanted to ensure you have everything you need..."*
- Marketing creates a one-page "Internal Business Case Summary" tailored to Coastal PE's stated priorities (compliance, portfolio company data visibility) — give to champion to use in their internal discussions

Day 5:
- Signal check: Did CTO respond? Did Managing Director open the CMO email or LinkedIn ad?
- If still silent: escalate to Tier 3 — schedule virtual executive briefing center session as a "strategic conversation about data governance trends in PE" — position as exclusive, not a sales call

**Week 2 — Prove Value Independently:**
- If champion re-engages, provide them a "stakeholder map template" — coach them to identify who is blocking internally and share with AE
- Deploy peer reference call: arrange intro between Coastal PE Managing Director and similar PE firm CFO who is a reference customer — frame as peer conversation about industry trends, not a sales reference call
- Marketing runs a retargeting campaign to ALL 11 identified contacts in the account with "Why 14 of the Top 25 PE Firms Choose Luminary" — use LinkedIn Matched Audiences, $800 for 10-day run

**Week 3 — Force Resolution:**
- If engagement resumes: accelerate with a "Decision Readiness Workshop" — 45-min virtual session with key stakeholders to finalize implementation approach and review mutual action plan
- If engagement remains dark: AE sends a professionally honest close-out email to Managing Director: *"We've genuinely enjoyed this process and believe Luminary is the right fit. I want to respect your team's time — could you give me 5 minutes to understand if the timing has shifted? We can absolutely revisit when the moment is right."*
- Walk-away trigger: If no senior stakeholder engagement by Day 21, move deal to Q4 pipeline and reallocate intervention resources to Meridian

---

**DEAL RESCUE PLAYBOOK — MERIDIAN HEALTH SYSTEM ($310K) — Yellow (Urgent)**

*Root Cause:* CFO has been dark for 90 days while a competitor just submitted a competing proposal. The champion (VP Data Architecture) is a strong technical advocate but has no financial sponsorship. DataTrust Pro almost certainly has an executive relationship we don't. This is a CFO-gap competitive rescue — every day we wait costs us.

**Immediate (This Week):**

- Day 1: Marketing identifies the right CFO peer reference — search reference library for health system CFOs; Atrium Health and Piedmont Healthcare CFOs are both in the reference library and have spoken publicly about data governance ROI
- Day 1: Marketing creates a "CFO Decision Brief" — a 2-page document (not a sales deck) that quantifies Meridian's specific compliance cost exposure and maps to our ROI model; include a 1-page Atrium Health financial outcome summary
- Day 2: AE provides champion with the CFO Brief and this script: *"[CFO Name] — I know you've had a lot on your plate. [VP Data Architecture] suggested I send you this brief summary of how similar health systems have justified this investment. Happy to walk you through the numbers in 20 minutes whenever works."*
- Day 3: Marketing deploys LinkedIn Thought Leader Ad targeting Meridian CFO's profile specifically with a 60-second executive video from our CMO on "The Hidden Compliance Cost of Data Silos in Healthcare" — $400 budget, 7-day run
- Day 4: Provide champion with competitive talking points against DataTrust Pro: three specific areas where our platform outperforms (HIPAA audit trail granularity, time-to-deployment for Epic integration, total cost of ownership over 3 years with benchmarks from Gartner) — format as a 1-page "Questions to Ask Any Vendor" document champion can use internally without it looking like attack marketing

**Week 2 — Secure CFO Engagement:**
- If CFO responds: book a CMO-to-CFO "peer conversation" call — 20 minutes, position as a strategic discussion about healthcare data governance trends, not a vendor pitch
- If CFO still silent after champion outreach: deploy Executive Sponsor intro from our CEO to Meridian CEO-level stakeholder — only for a deal of this size and competitive urgency — *"I wanted to personally make sure Meridian's executive team has our perspective as you finalize your evaluation..."*
- Deploy Peer Review Package: 5 G2 reviews from healthcare system customers + 2 Gartner Peer Insights quotes specific to our Epic integration capability — send to champion for distribution to CFO and technical evaluators

---

**BUYING COMMITTEE COVERAGE MAP — APEX INDUSTRIAL ($195K)**

Current Coverage:
- Champion: Not identified — CTO and IT Director both loosely engaged; neither owns the project (Critical Gap)
- Economic Buyer: Not identified (Critical Gap)
- Technical Evaluator: IT Director loosely engaged
- End Users: Not engaged
- Legal/Security: Not started

Highest-Leverage Missing Role: Project Champion (someone who will own this internally)

Champion Development Sequence (Days 1-10):
- Day 1: AE diagnostic call with BOTH CTO and IT Director together — objective is to identify who has the budget authority and organizational mandate for this project; use question: *"If this project gets a green light, who would own the success metrics internally?"*
- Day 3: Marketing sends both contacts the "Data Governance Maturity Assessment" interactive tool — whoever completes it first and shares results with colleagues is likely the champion
- Day 5: Based on response signal, direct all subsequent marketing touches to the higher-engagement contact; send them "Internal Project Kickoff Guide" — a template for how to build internal alignment around a data governance initiative
- Day 7: If neither takes ownership: escalate to qualify out — send a polite email asking Apex to "identify the right executive sponsor for us to engage with" — if they can't, this deal is not real this quarter

Walk-Away Trigger: If no champion and no economic buyer identified by Day 10, recommend moving Apex to Q4 pipeline and replacing with a higher-confidence opportunity.

---

**COMPETITIVE DEFENSE BRIEF — DataTrust Pro (Active in Meridian)**

DataTrust Pro's Likely Pitch Points Against Luminary:
1. *"Luminary is newer and less proven in enterprise healthcare"* — Counter: Deploy our 47 healthcare reference customers list; share the Atrium Health case study with 18-month implementation timeline and 340% ROI
2. *"DataTrust Pro has deeper Epic integration"* — Counter: Our Epic integration is Certified and was built in partnership with Epic; provide the 2-page "Luminary + Epic Architecture Overview" technical brief to IT Director
3. *"Luminary is more expensive"* — Counter: Deploy the 3-year TCO comparison model showing our lower total cost when implementation services and admin overhead are included; have CFO reference available to speak to actual cost experience

Champion Talking Points for Internal Meetings:
*"When evaluating DataTrust Pro vs. Luminary, the questions you should be asking are: (1) How long did their last healthcare implementation take, and can they provide customer references for it? (2) What is the all-in total cost including services, training, and ongoing admin? (3) Which system handles Epic audit trails at the field level — not just the record level? We've been very specific about our capabilities in each area."*

Paid Media Competitive Play:
- Run LinkedIn Sponsored Content targeting Meridian's full 7-contact buying committee with the title: "Why 14 Health Systems Chose Luminary Over DataTrust Pro for Their Governance Programs"
- Budget: $500 for a 7-day run targeting the Meridian account specifically via LinkedIn Matched Audiences

---

**PIPELINE REVENUE FORECAST — Q3 SCENARIOS**

| Scenario | Coastal PE | Meridian | Apex | Total Forecasted | vs. $2.4M Target |
|----------|-----------|---------|------|-----------------|------------------|
| Base (no intervention) | $108K (28%) | $105K (34%) | $27K (14%) | $240K from these 3 | -$2.16M gap |
| With Interventions (+15pt avg lift) | $165K (43%) | $155K (50%) | $39K (20%) | $359K | +$119K recovered |
| Upside (interventions succeed fully) | $270K (70%) | $217K (70%) | $39K (20%) | $526K | +$286K recovered |
| Downside (all slip) | $0 (Q4) | $62K (20%) | $0 (Q4) | $62K | -$178K vs. base |

**Marketing-Recoverable Revenue This Quarter (Realistic):** ~$119K additional from these 3 deals through intervention.
**Coverage Assessment:** These 3 deals represent $890K of potential ACV. Current pipeline must be reviewed for additional Green deals that can accelerate to cover Q3 gap.

---

**REPEATABLE WEEKLY PIPELINE RESCUE RITUAL (Every Monday 9am)**

**Step 1 — Data Pull (15 min):**
- Export from Salesforce: all deals with close date in next 90 days; flag deals stuck in any stage beyond 2x the average stage duration; flag deals with zero marketing touches in past 14 days
- Pull Gong report: deals where champion engagement has dropped >50% week-over-week
- Pull 6sense/Bombora intent: which pipeline accounts have increased intent signals (may indicate competitive research)

**Step 2 — Score Refresh (10 min):**
- Recalculate scores for any deal where: stage changed, new contact engaged, POC status updated, competitor identified/removed, days-in-stage crossed a threshold

**Step 3 — Intervention Decisions (15 min):**
- Any deal newly scored Red: assign deal rescue playbook lead (marketing team member) and notify AE within the same day
- Any Yellow deal with negative trajectory (score dropped vs. last week): escalate one tier in intervention
- Any Green deal with no change: confirm AE is tracking to close date, no marketing action required

**Step 4 — Intervention Assignment (5 min):**

| Score | Action | Owner | Timeline |
|-------|--------|-------|----------|
| <40 (Red) | Full rescue playbook | Senior PMM + AE | Immediate |
| 40-55 (Low Yellow) | 1-week targeted intervention | Marketing Ops | This week |
| 56-69 (High Yellow) | Monitor + 1 asset deployment | Content/Demand | Within 10 days |
| 70+ (Green) | No marketing action | AE-owned | — |

**Step 5 — AE Communication (5 min):**
Send weekly "Marketing Pipeline Support" Slack message to each AE with at-risk deals:
*"[AE Name] — here's what marketing is deploying this week to support your [Deal Name] opportunity: [specific asset/campaign]. Here's what I need from you: [specific ask — e.g., confirm champion name, broker intro to CFO]. Let me know if you want to talk through the play."*

## Success Metrics

- **Win rate lift:** Compare close rate on deals where rescue playbook is applied vs. historical baseline for similar deal profiles (target: +12–25% improvement)
- **Revenue recovered:** Total ACV closed on Yellow and Red deals that received interventions vs. model prediction without intervention
- **Champion re-engagement rate:** % of dark deals where engagement resumes within 10 days of intervention (target: >50%)
- **Competitive win rate improvement:** Track win rate vs. each named competitor before/after competitive defense plays are systematic
- **Score accuracy:** Calibrate model by comparing predicted win probability scores to actual outcomes each quarter; refine weights when model is >15 points off actual outcomes
- **Time-to-intervention:** Measure how quickly marketing responds to Red classification; target: intervention deployed within 3 business days of deal going Red
- **Marketing-attributed pipeline rescue:** Total ACV from deals classified Red or Yellow that closed, where marketing logged specific interventions — track this as a formal marketing metric in QBR

## Related Prompts

- [Predictive Pipeline Health & Revenue Gap Forecasting](./AI-Powered-B2B-SaaS-Predictive-Pipeline-Health-&-Revenue-Gap-Forecasting-Intelligence-Engine.md)
- [Win-Loss Analysis & Competitive Deal Intelligence](../Revenue-Operations-Analytics/AI-Powered-B2B-SaaS-Win-Loss-Analysis-&-Competitive-Deal-Intelligence-Revenue-Engine.md)
- [Deal Velocity Analytics & Sales Cycle Compression](../Revenue-Operations-Analytics/AI-Powered-B2B-SaaS-Deal-Velocity-Analytics-&-Sales-Cycle-Compression-Intelligence-Engine.md)
- [Pipeline Review Intelligence & Deal Coaching](../../02_Product-Marketing/Sales-Enablement/AI-Powered-B2B-Pipeline-Review-Intelligence-&-Deal-Coaching-Revenue-Acceleration-Intelligence-Engine.md)

## Integration Tips

**Salesforce:** Create a custom "Marketing Win Score" field (number, 0–100) on the Opportunity object. Build a Salesforce Flow that fires a Slack notification to the marketing channel when any deal drops below 40. Use Salesforce Reports to pull the weekly pipeline data extract in Step 1 of the ritual. Build a Marketing Pipeline Rescue dashboard for the CMO showing Red deal count, total ACV at risk, and marketing interventions logged.

**Gong:** Use Gong Deals to track conversation engagement scores per deal. Configure alerts when a champion's call engagement score drops >30% week-over-week. Export Gong trackers (competitor mentions, economic buyer talk time, champion enthusiasm score) into your deal scoring model as automatic signal inputs. Use Gong Engage to send tracked email sequences from marketing as part of rescue plays.

**Clari:** If using Clari, map your predictive score model to Clari's risk flags — your model should run in parallel with Clari's AI score. When Clari flags a deal as "at risk," trigger the marketing rescue ritual automatically. Use Clari's deal inspection data (last activity, engagement, forecast category) as inputs to your scoring table.

**HubSpot:** For HubSpot CRM users, build a custom deal property for "Marketing Win Score" and a workflow that enrolls deals in a "Pipeline Rescue" email sequence when score drops below 40. Use HubSpot's Account Insights to track company-level engagement across all contacts, not just the primary contact. Set up LinkedIn Matched Audiences through HubSpot's LinkedIn integration to run account-specific ads.

**LinkedIn Campaign Manager:** Use LinkedIn Matched Audiences to upload your at-risk account list and serve Thought Leader Ads to all identified contacts at those companies. Create separate audiences by deal tier (Red vs. Yellow) and serve differentiated creative. Budget $300–800 per account for a 7-10 day run. Track engagement lift by account in LinkedIn's analytics.

**Slack:** Build a #pipeline-rescue Slack channel where the weekly score refresh results are posted automatically via Salesforce webhook or Zapier. Route Red deal alerts to AE + marketing DM simultaneously. Create a /rescue command that pulls the latest intervention playbook for a given deal name.

## Troubleshooting

**Problem: My sales team doesn't share deal signal data, so I can't populate the scoring model.**
Solution: Start with the signals you CAN extract automatically from CRM (days in stage, contact count, last activity date) and treat manual MEDDPICC fields as "unscored/unknown" which default to a penalty score of -15 per missing field. Create a 5-question "deal health check" that AEs complete during Monday pipeline calls — make it the price of entry for getting marketing support on a deal. Over 4–6 weeks, you'll have enough data to build meaningful scores even from partial signal sets.

**Problem: My historical win/loss data is incomplete or unreliable, so I can't calibrate the signal weights accurately.**
Solution: Start with published B2B SaaS win rate benchmarks as proxies: POC completion +22 points on average, economic buyer engagement +18 points, 3+ contacts engaged +14 points. Run your model with these proxy weights for one quarter, then compare your predicted scores to actual outcomes and recalibrate. Even a rough model outperforms gut feel — the objective is directional accuracy, not statistical perfection. Document your weight assumptions so you can improve them iteratively.

**Problem: Sellers feel marketing is "interfering" with their deals when we deploy rescue interventions, causing friction.**
Solution: Never deploy a rescue intervention without AE awareness and explicit opt-in (the Monday ritual Slack message accomplishes this). Frame all marketing interventions as "AE-authorized" — the champion sees assets from "the Luminary team" that the AE has personally approved, not an unsolicited marketing blast. Hold a brief "marketing pipeline partnership" training session with sales leadership that shows the win rate lift data — sellers adopt marketing assistance when they see it close deals, not when it's mandated from above.

## Version History
- v1.0: Initial creation (auto-generated)
