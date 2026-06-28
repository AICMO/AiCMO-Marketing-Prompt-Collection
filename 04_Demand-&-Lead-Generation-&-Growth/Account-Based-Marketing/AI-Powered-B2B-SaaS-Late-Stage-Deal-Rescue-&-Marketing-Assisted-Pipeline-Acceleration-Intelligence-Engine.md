# AI-Powered B2B SaaS Late-Stage Deal Rescue & Marketing-Assisted Pipeline Acceleration Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** abm, pipeline-acceleration, deal-velocity, sales-marketing-alignment, b2b, revenue-intelligence, late-stage, deal-rescue

## Overview
When a B2B deal stalls in late-stage evaluation, most companies watch time-in-stage metrics spike while hoping sales can push through alone. This prompt engineers an AI-powered system that automatically detects deal stall signals, diagnoses the root cause (silent champion, blocked economic buyer, unresolved technical objection, legal hold, competitive threat), and deploys hyper-targeted marketing interventions — content, campaigns, executive outreach, events, and social proof sequences — designed to unblock the specific deal scenario and accelerate pipeline to close.

## Quick Copy-Paste Version

You are a senior B2B SaaS revenue marketing strategist specializing in pipeline acceleration and deal rescue. I need to build an AI-powered system that detects stalled late-stage deals and automatically deploys targeted marketing interventions to re-engage the buying committee and accelerate deals to close.

Here is our context:
- Product: [describe your SaaS product and target customer]
- Average ACV: [e.g., $65,000]
- Average sales cycle: [e.g., 95 days]
- Deal stages and average time-in-stage: [e.g., "Discovery: 12d, Technical Eval: 22d, Proposal: 18d, Legal/Procurement: 28d, Closed Won"]
- What counts as "stalled": [e.g., "no activity or buyer engagement for 14+ days"]
- Current CRM: [e.g., Salesforce]
- Marketing automation platform: [e.g., HubSpot]
- Sales engagement tool: [e.g., Outreach or Salesloft]
- Number of active opportunities in late-stage pipeline: [e.g., 45 deals worth $3.2M]

Please provide:

1. DEAL STALL DETECTION FRAMEWORK
   - The 7 deal stall signals to monitor in CRM (define each, the threshold that triggers an alert, and the urgency tier: Code Red/Yellow/Orange)
   - How to distinguish genuine stall vs. expected silence (e.g., buyer on vacation, legal review timing)
   - A stall root-cause classification system with 6 root-cause categories and the diagnostic questions to determine which applies
   - The CRM fields and engagement signals to analyze for each root-cause category

2. MARKETING INTERVENTION PLAYBOOKS (one per root-cause)
   For each of these 6 stall scenarios, provide a complete 10-day marketing intervention playbook with specific assets, channels, and messages:
   a) Silent Champion — internal advocate has gone quiet or is blocked
   b) Economic Buyer Not Engaged — CFO/CEO hasn't been reached
   c) Unresolved Technical Objection — security, integration, or scalability concern blocking progress
   d) Competitive Threat — competitor has entered or re-entered the evaluation
   e) Legal/Procurement Hold — contract or compliance issues creating delay
   f) Internal Priority Shift — buyer's priorities have changed due to company news/events

3. BUYING COMMITTEE RE-ENGAGEMENT SEQUENCES
   - A multi-threading email sequence for reaching 3 new stakeholders when the champion goes silent
   - An executive-to-executive outreach framework (CEO/VP to CXO) triggered by stalls over $100K
   - A peer validation sequence using customer references, G2 reviews, and case studies matched to the stalled buyer's industry/persona
   - A "Why Now" urgency sequence tied to real events: quarter-end pricing, product roadmap milestones, or competitor announcements

4. MARKETING ASSET ACTIVATION PROTOCOL
   - Which content types work best at each deal stage and for each stall root-cause (map this in a 6x4 matrix)
   - How to create a deal-specific content package in under 2 hours using AI
   - A digital sales room refresh protocol: what to add/remove/update when a deal stalls
   - How to use intent data signals to verify if a stalled buyer is still actively researching vs. fully disengaged

5. MEASUREMENT & ESCALATION FRAMEWORK
   - The 5 KPIs for measuring marketing's impact on deal rescue (define each metric and target benchmark)
   - An escalation protocol: when marketing intervention alone isn't enough and sales leadership must be pulled in
   - How to build a "deal rescue attribution" report in Salesforce showing marketing's contribution to re-accelerated pipeline
   - A weekly deal rescue review meeting agenda for marketing and sales leaders

Produce a complete system I can hand to my revenue marketing team to implement in Salesforce + HubSpot this quarter, with AI automating 80% of the detection and intervention sequencing.

## Advanced Customizable Version

ROLE: You are a principal-level B2B revenue marketing architect with 15+ years of experience building pipeline acceleration programs at high-growth SaaS companies ($20M–$500M ARR). You have deep expertise in Salesforce, HubSpot, Outreach, 6sense, Gong, and Clari. You think exclusively in terms of pipeline dollars at risk and days-to-close compression. You have directly rescued $50M+ in stalled pipeline through systematic marketing intervention programs.

COMPANY CONTEXT:
- Company name and product: [e.g., "Vantage AI — AI-powered contract lifecycle management for mid-market legal and finance teams"]
- Target ICP: [e.g., "General Counsel, VP Legal Operations, and CFO at companies with 200–2,500 employees in financial services, professional services, and healthcare verticals"]
- Average ACV: [e.g., $72,000]
- Average sales cycle from SQL to close: [e.g., 88 days]
- Current pipeline at risk (deals 150%+ of benchmark time-in-stage): [e.g., "$4.8M across 38 deals in stages 3–6"]
- Deal stages with benchmark days and current average: [e.g., "S1 Discovery: 10d/14d, S2 Technical Eval: 21d/31d, S3 Business Case: 18d/27d, S4 Legal/Security: 25d/42d, S5 Negotiation: 12d/19d"]
- CRM: [e.g., Salesforce with Clari overlay for forecasting]
- Marketing automation: [e.g., HubSpot Enterprise]
- Sales engagement: [e.g., Outreach]
- Conversation intelligence: [e.g., Gong for call recording and deal intelligence]
- Intent data: [e.g., 6sense with Bombora third-party intent]
- Avg buying committee size: [e.g., 6.2 stakeholders per deal]
- Current win rate at stage 3+: [e.g., 44%]
- Target win rate improvement from program: [e.g., increase to 54% within 2 quarters]
- Team executing: [e.g., "1 field marketing manager + 1 content marketer; sales team of 12 AEs + 3 SEs"]

PROGRAM OBJECTIVE:
Build a fully automated deal rescue and pipeline acceleration system that:
1. Continuously monitors all late-stage opportunities in Salesforce for stall signals using CRM data, Gong transcripts, digital sales room engagement, and 6sense intent signals
2. Automatically classifies the stall root-cause within 24 hours of detection
3. Triggers the appropriate marketing intervention playbook without requiring manual decision-making
4. Delivers deal-specific, buying-committee-mapped content and outreach within 48 hours of stall detection
5. Measures marketing's contribution to deal re-acceleration and closed revenue with full Salesforce attribution
6. Operates at scale across all 38 at-risk deals simultaneously with one FTE managing the system

DELIVERABLE 1: INTELLIGENT STALL DETECTION ARCHITECTURE

Build a stall detection system with three components:

A) SIGNAL MATRIX (define each signal, data source, threshold, and urgency tier):
   - Time-in-stage signals: [Define 3 threshold tiers for each stage]
   - Engagement decay signals: [Email opens, link clicks, digital sales room visits, Gong call frequency]
   - Intent signal degradation: [6sense score changes, Bombora topic surge drop-off]
   - Competitive threat signals: [6sense competitor surge, G2 category research activity]
   - Internal risk signals: [Champion job change, LinkedIn activity indicating distraction, company news]
   - Economic signals: [Buyer company earnings, layoffs, M&A activity, budget freeze signals]
   - Gong transcript signals: [Sentiment change, objection repetition, executive disengagement]

B) STALL ROOT-CAUSE CLASSIFICATION ENGINE:
   For each of 8 stall root-cause categories, provide:
   - Diagnostic signals that confirm the root cause
   - Confidence scoring methodology (how to confirm vs. hypothesize the cause)
   - Clarifying questions for the AE to validate classification
   - Estimated pipeline risk score (probability of losing deal if intervention doesn't occur within 14 days)
   
   Root causes to cover:
   1. Champion Silenced or Blocked (internal politics, leadership change, project deprioritized)
   2. Economic Buyer Unconvinced (ROI case not landed, CFO skeptical, no executive sponsor)
   3. Technical Objection Unresolved (security review blocked, integration complexity, scale uncertainty)
   4. Competitive Displacement Risk (identified competitor re-engagement, pricing pressure)
   5. Legal/Procurement Process Delay (contractual terms, vendor risk assessment, compliance)
   6. Internal Priority Disruption (company reorganization, budget reallocation, M&A distraction)
   7. Evaluation Fatigue (buying committee decision-making stalled, no clear internal champion for closing)
   8. Missing Stakeholder (undiscovered blocker or influencer not yet engaged)

C) AUTOMATED DETECTION WORKFLOW:
   - Salesforce flow/process builder logic to flag stalled deals automatically
   - HubSpot workflow triggers for marketing intervention queue
   - Slack/email alert to field marketing manager within 2 hours of stall classification
   - Clari integration for forecast impact scoring of each at-risk deal
   - Weekly automated deal rescue pipeline report to CMO and CRO

DELIVERABLE 2: INTERVENTION PLAYBOOK LIBRARY (one per root cause)

For EACH of the 8 root-cause categories, produce a complete 14-day marketing intervention playbook that includes:

TIMELINE STRUCTURE:
- Day 1-2: Intelligence gathering and AE alignment
- Day 3-5: First-wave content and outreach deployment
- Day 6-9: Buying committee multi-threading expansion
- Day 10-12: Urgency amplification and executive involvement
- Day 13-14: Escalation decision point and next-phase planning

For each playbook, specify:
1. OUTREACH SEQUENCE: Channel-by-channel sequence (email, LinkedIn, phone, direct mail) for each buying committee role
2. CONTENT PACKAGE: Exact content types to create or pull from library (case study, ROI model, reference call, competitive one-pager, etc.), matched to root cause
3. EXECUTIVE PLAY: Conditions under which VP/CEO outreach from your side is triggered and script framework
4. REFERENCE ACTIVATION: How to rapidly mobilize a customer reference in the same industry/use case within 48 hours
5. EVENT/EXPERIENCE PLAY: If a 1:1 experience (executive dinner, site visit, innovation briefing) is warranted and how to fast-track it
6. COMPETITIVE COUNTER: If competitive threat is present, the specific counter-positioning and proof points to deploy
7. EXIT CRITERIA: What signals indicate the intervention is working vs. when to escalate or stand down

DELIVERABLE 3: BUYING COMMITTEE INTELLIGENCE & CONTENT PERSONALIZATION ENGINE

A) STAKEHOLDER MAPPING FOR STALLED DEALS:
   - Template for rapidly mapping all buying committee members in Salesforce (role, engagement level, sentiment score, last touchpoint, days since last engagement)
   - Algorithm for identifying "dark" stakeholders not yet in CRM using LinkedIn, intent data, and email domain signals
   - Persona-specific content recommendation matrix: for each of 8 buying roles (Economic Buyer, Technical Evaluator, Champion, Legal/Compliance, Security, Finance, End User, Executive Sponsor), specify:
     * Top 3 content types that move them forward
     * Top 3 objections to address at this deal stage
     * Preferred outreach channels
     * Psychological trigger most likely to prompt re-engagement

B) DEAL-SPECIFIC CONTENT PACKAGE GENERATION:
   - A step-by-step AI prompt workflow for creating a custom deal package in under 90 minutes:
     * How to feed deal intelligence (Gong transcripts, email threads, discovery notes) into AI to extract specific objections and motivations
     * AI prompt sequence for creating a deal-specific one-pager (company name, use case, ROI model, peer validation)
     * How to generate a custom ROI calculator pre-populated with the buyer's actual numbers from CRM
     * How to create a competitive analysis that specifically addresses the alternatives the buyer mentioned
   - Digital sales room update protocol: which sections to add, refresh, or retire based on stall root cause
   - Personalized video script template for AE + marketing to produce a 90-second re-engagement video in 30 minutes

C) SOCIAL PROOF MOBILIZATION PROTOCOL:
   - How to identify the closest customer reference (industry, company size, use case, persona match) within 60 seconds using Salesforce
   - Reference request email template that secures a 20-minute peer call within 48 hours (with a 70%+ acceptance rate)
   - How to compile a "proof stack" — 3 customer quotes, 1 video testimonial, 2 G2 reviews, 1 analyst citation — all specific to the buyer's profile, within 2 hours
   - Case study rapid-match protocol: how to surface the 3 most relevant case studies from your library based on the buyer's industry, pain point, and company stage

DELIVERABLE 4: CAMPAIGN ORCHESTRATION & AUTOMATION ARCHITECTURE

A) HUBSPOT WORKFLOW DESIGN:
   - End-to-end workflow map from Salesforce stall detection → HubSpot intervention trigger → multi-step outreach sequence → re-engagement tracking → deal stage update back to Salesforce
   - Enrollment logic for each intervention playbook (which stall root cause triggers which workflow)
   - Branch logic for adjusting sequence based on buyer engagement signals (if buyer opens email within 24h vs. no opens at 7 days, branch accordingly)
   - Suppression logic to prevent over-contact (max touch frequency per stakeholder per week)
   - Handoff rules: when HubSpot automation pauses and AE takes over manually

B) OUTREACH.IO SEQUENCE LIBRARY:
   - Naming convention and folder structure for 8 intervention sequences in Outreach
   - Step count and timing for each sequence type
   - Subject line formulas for re-engagement emails (context-aware openers referencing last conversation or company news)
   - LinkedIn InMail templates for 4 buying committee personas when email goes unresponsive
   - Call script framework for AE to use when breaking silence: the 90-second voicemail, the opening line, and the bridge to next step

C) GONG INTELLIGENCE INTEGRATION:
   - How to use Gong's "Topics Tracker" to automatically flag calls where specific objections appear (e.g., "pricing," "security," "timeline," "competitor name")
   - Alert workflow: Gong objection flag → Salesforce field update → HubSpot enrollment in intervention playbook
   - Post-call action prompt for AEs to trigger same-day marketing content deployment based on what was said on the call
   - Deal risk scoring model using Gong sentiment + CRM activity + intent signal combined score

DELIVERABLE 5: MEASUREMENT FRAMEWORK & EXECUTIVE REPORTING

A) DEAL RESCUE ATTRIBUTION MODEL:
   - Define marketing's contribution to rescued pipeline using multi-touch attribution:
     * "Marketing Assisted" — deal closed where marketing intervention occurred during stall period
     * "Marketing Accelerated" — deal where time-in-stage dropped after intervention vs. historical average
     * "Marketing Saved" — deal forecasted to churn that was re-engaged and ultimately closed
   - Salesforce campaign association logic for tagging deal rescue activities to opportunity records
   - How to calculate "Pipeline Value Rescued" as a monthly marketing KPI

B) KEY METRICS & BENCHMARKS:
   - 8 metrics to track for the program (define each with formula, data source, and quarterly benchmark target):
     1. Stall detection accuracy rate (% of true stalls caught vs. missed)
     2. Intervention trigger time (hours from stall signal to marketing activation)
     3. Re-engagement rate (% of stalled buyers who respond within 14 days of intervention)
     4. Deal rescue rate (% of intervened deals that advance to next stage within 30 days)
     5. Win rate improvement on intervened deals vs. control group
     6. Time-in-stage reduction (days saved at each stage after marketing intervention)
     7. Pipeline value rescued per month (dollar value of deals re-accelerated)
     8. Revenue marketing ROI (closed revenue from rescued deals / cost of program)

C) EXECUTIVE DASHBOARD & REPORTING CADENCE:
   - Weekly deal rescue standup agenda for marketing + sales (25-minute format)
   - Monthly CMO/CRO pipeline rescue report: metrics, deals rescued, win rate impact, revenue attribution
   - Quarterly program retrospective framework: what playbooks worked, what content drove re-engagement, which signals were most predictive
   - Board-level narrative for presenting marketing's impact on pipeline velocity and win rate

CONSTRAINTS & REQUIREMENTS:
- Everything must integrate with Salesforce, HubSpot, Outreach, Gong, and 6sense
- The system must scale to manage 50+ simultaneous at-risk deals with minimal manual oversight
- All content personalization must use AI to reduce AE prep time to under 30 minutes per deal
- Attribution must be CRO-defensible — measurable in Salesforce, not just marketing's internal tracking
- Every intervention must respect the buyer's relationship with the AE — no outreach that would undermine trust or feel automated/impersonal

## Example Input/Output

**Input Example:**

Company: Meridian Data — Data governance and cataloging platform for enterprise data teams.
ACV: $85,000 | Sales cycle: 105 days | Current stage: S4 Technical Evaluation (32 days in stage, benchmark is 19 days)
Deal details: VP of Data Engineering at $2.1B manufacturing firm. Champion is the data engineering lead (Sarah Chen). Economic buyer is CDO (Jim Walsh) — only attended 1 of 4 calls, showed hesitation on migration complexity. Gong flagged "migration risk" mentioned 4 times in last call. 6sense intent score dropped from 82 to 41 in 2 weeks. No email engagement from CDO or VP in 11 days. Competitive threat: Collibra re-entered evaluation per AE.

**Output Example (excerpt):**

**STALL CLASSIFICATION: Dual-Threat — Technical Objection (Primary) + Competitive Re-Entry (Secondary)**

Confidence: HIGH (87%) — Migration risk flagged 4x in Gong, intent score collapse, CDO disengagement pattern matches "economic buyer unconvinced" signature.

**INTERVENTION PRIORITY: CODE RED — $85K deal at 65% risk of loss if no intervention in 7 days.**

---

**14-DAY MERIDIAN DATA DEAL RESCUE PLAYBOOK**

**DAY 1-2: INTELLIGENCE & ALIGNMENT**
- AE debrief call (20 min): Extract every migration concern raised; confirm whether Collibra has scheduled a technical deep-dive; identify Sarah Chen's internal blockers
- Pull Collibra competitive one-pager from library (update with Meridian's migration accelerator launched last month)
- Identify closest customer reference: [Pull from Salesforce: manufacturing company, 500K+ records migrated, data engineering team of 5–15, Collibra evaluated — match: Redline Industries, contact: Dave Park, previous reference for 2 other deals]

**DAY 3-5: FIRST-WAVE DEPLOYMENT**

Content package for Sarah Chen (Technical Champion):
1. "Meridian Migration Playbook: The 90-Day Data Governance Implementation for Manufacturing Data Teams" — custom PDF using their specific ERP integrations (SAP + Snowflake) from discovery notes
2. Case study: "How Harrington Manufacturing Migrated 840K Assets in 47 Days with Zero Downtime" — pulled from library; matches industry and scale
3. ROI model pre-populated: $2.1B revenue, estimated 3,200 governed assets, calculate 340 hours/month saved in data request processing at $95/hr loaded cost = $386K/year → $32K/month → payback in 2.6 months at $85K ACV

Email from AE to Sarah Chen (Subject: "Something I should have sent 2 weeks ago — migration risk"):
"Sarah — I heard 'migration complexity' come up several times in our last call and I haven't done enough to address it directly. I've put together a 6-page migration playbook specifically for SAP + Snowflake environments that shows exactly how we handled this at [Harrington Manufacturing]. I'd also like to connect you with Dave Park, their Data Engineering Lead, who went through a near-identical migration 14 months ago. Would a 20-minute peer call with Dave this week help move things forward? I can have him available by Thursday."

Content package for Jim Walsh (CDO / Economic Buyer):
1. "The CDO's Risk Framework for Data Governance Platform Selection" — 2-page executive brief with 4 migration risk scenarios and how each is handled
2. Custom executive summary: 1-page "Business Case for Meridian Data at [Company Name]" with their specific KPIs and Q3 regulatory compliance deadline surfaced in discovery
3. Peer validation: G2 review from CDO at similar-size manufacturing firm + LinkedIn message from Meridian CEO to Jim Walsh

LinkedIn message from Meridian CEO (template for SDR to draft, CEO to approve in <5 min):
"Jim — Ryan here from Meridian. I saw you and Sarah have been evaluating data governance platforms and I wanted to reach out directly. I've connected dozens of CDOs in manufacturing with our migration team and peer references, and I'd love 15 minutes to hear your specific concerns. The migration risk question is the one I get most — happy to walk you through how we've handled it at companies very similar to yours."

**Collibra Counter-Play:**
- Prepare "Meridian vs. Collibra: Manufacturing Data Governance" comparison one-pager (update from template: add Meridian's SAP-native connector, highlight Collibra's 8.5 month average implementation timeline vs. Meridian's 3.2 months, pull 3 recent Collibra G2 reviews mentioning implementation delays)
- AE script for next call: "I know Collibra has been back in touch. I actually want to help you make the best decision — here's an honest comparison of the two approaches for a manufacturing environment your size. Can we schedule a 30-minute technical comparison call with our SE and your engineering team?"

**DAYS 6-9: BUYING COMMITTEE EXPANSION**
[continues...]

---

## Success Metrics

- **Re-engagement rate**: 60%+ of stalled deals show buyer activity within 14 days of intervention
- **Deal advance rate**: 45%+ of intervened deals advance to next stage within 30 days
- **Win rate lift**: Intervened deals close at 52%+ vs. 44% baseline
- **Time-in-stage reduction**: 30%+ reduction in average days at stalled stage
- **Pipeline rescue ROI**: $8–15 rescued revenue for every $1 invested in marketing intervention program
- **Content utilization**: 80%+ of AEs actively use deal-specific content packages from marketing within 48 hours of delivery

## Related Prompts

- `../../05_Analytics-&-Performance/Revenue-Operations-Analytics/AI-Powered-B2B-SaaS-Deal-Velocity-Analytics-&-Sales-Cycle-Compression-Intelligence-Engine.md`
- `../../02_Product-Marketing/Sales-Enablement/AI-Powered-B2B-Pipeline-Review-Intelligence-&-Deal-Coaching-Revenue-Acceleration-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-B2B-Active-Deal-Pipeline-Influence-&-Buying-Committee-Orchestration-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Sales-Enablement-Analytics/AI-Powered-B2B-SaaS-Sales-Cycle-Compression-Analytics-&-Marketing-Deal-Velocity-Intelligence-Engine.md`

## Integration Tips

- **Salesforce**: Create a custom "Deal Rescue" campaign type and associated campaign members for every marketing touch during intervention; build a "Pipeline Rescue Dashboard" with metrics by AE, stage, and root-cause category
- **HubSpot**: Use Workflow enrollment triggers based on Salesforce field syncs (Stall Root Cause, Days In Stage); tag all deal rescue contacts with a Deal Rescue list for suppression management and cohort reporting
- **Outreach**: Create a "Deal Rescue" sequence folder with sequences named by root-cause (e.g., "RESCUE — Champion Silent," "RESCUE — Technical Objection"); set governor limits of 3 touches/week per contact during rescue window
- **Gong**: Configure Topic Trackers for 12 stall-indicator phrases (migration risk, pricing concern, timeline, competitor name, internal alignment, budget freeze, etc.); auto-trigger Salesforce field update when tracked
- **6sense**: Create an "At Risk — Intent Declining" segment for accounts where intent score drops 30%+ in 30 days; sync to HubSpot for additional nurture layer while AE-driven rescue sequence runs
- **Slack**: Use Salesforce-to-Slack integration (or Zapier) to post a deal rescue alert in a `#deal-rescue` channel when a stall is detected, with deal context, root cause, and first recommended action
- **Clari**: Add "Deal Rescue Initiated" as a custom flag in Clari to track impact on forecast accuracy; compare forecast outcomes for deals with vs. without marketing intervention

## Troubleshooting

**Problem**: AEs resist using marketing-provided content because it feels generic or doesn't match their specific deal context.
**Solution**: Implement a 30-minute "Deal Intelligence Handoff" meeting between AE and marketing manager for every Code Red deal. Use Gong transcript summaries and AE notes to customize content before delivery. Never deploy the generic template — always personalize at least 3 elements (company name, specific pain point, named stakeholder reference).

**Problem**: Buyers feel the outreach is coordinated or too "marketing-ish" and it undermines the AE relationship.
**Solution**: All external-facing communication must appear to come from the AE, not marketing. Marketing creates the content and sequences; AE sends everything personally. Use Outreach's personalization tokens to make every message look hand-written. Never mention "our marketing team created this for you" — it destroys authenticity.

**Problem**: Stall detection triggers false positives (flagging deals that are actually progressing normally through legal or procurement review).
**Solution**: Build a "Stall Exclusion" field in Salesforce that AEs can check with an expected re-engagement date when a deal is in a known hold (e.g., legal review week of 8/15, buyer vacation until 9/3). Exclude these deals from the automated stall detection algorithm. Review exclusion list weekly to ensure it's not being used to hide at-risk deals.

## Version History
- v1.0: Initial creation (auto-generated)
