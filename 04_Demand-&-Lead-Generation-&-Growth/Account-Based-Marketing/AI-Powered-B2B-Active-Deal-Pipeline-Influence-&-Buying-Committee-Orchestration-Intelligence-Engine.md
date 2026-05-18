# AI-Powered B2B Active Deal Pipeline Influence & Buying Committee Orchestration Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** abm, pipeline-influence, buying-committee, deal-acceleration, revenue-marketing, enterprise-b2b, pipeline-marketing

## Overview
Deploys an AI-driven pipeline influence system that scans every open CRM opportunity, scores deal health, and auto-generates deal-specific marketing programs — coordinating personalized content, executive engagement, and competitive counter-moves across each buying committee member to accelerate evaluation cycles and improve win rates without conflicting with AE-led sales activity.

## Quick Copy-Paste Version

You are a senior B2B revenue marketing strategist specializing in pipeline influence programs for enterprise SaaS companies. Design a complete AI-powered pipeline influence system for the following scenario:

Company: [Your Company]
Product/Service: [What you sell]
Target market: [Industry + company size + buyer persona]
Average deal size: [ACV]
Average sales cycle: [Length in months]
Current CRM: [Salesforce/HubSpot/other]
Typical buying committee size: [Number of stakeholders]
Top deal stall reasons: [e.g., "stuck in legal/security review," "champion can't get budget approval," "evaluating a competitor"]
Current marketing influence on open pipeline: [e.g., "marketing touches less than 30% of open deals post-SQL"]

Deliver:

1. DEAL INTELLIGENCE AUDIT SYSTEM
- AI workflow to scan all open opportunities in CRM and extract: deal stage, champion persona, committee size, competitive situation, last marketing touch date, days since last progression
- Risk scoring model: identify which deals are most at risk of stalling or going dark
- Content gap analysis: for each deal, what marketing assets have been shared vs. what the deal needs next

2. BUYING COMMITTEE INFLUENCE MAP
- Framework for mapping all stakeholders in an active deal: Champion, Economic Buyer, Technical Evaluator, Legal/Security, End User Sponsor
- For each role: their primary concern, preferred content type, optimal channel, and influence approach
- Committee heat map template showing engagement level of each stakeholder (red/yellow/green)

3. DEAL-SPECIFIC CONTENT ACTIVATION PLAYBOOKS
For each deal risk type, specify the exact content to deploy and the exact steps to take:
- Economic buyer never engaged: executive briefing template + CFO-ready ROI one-pager
- Technical evaluator blocking: security review acceleration kit + integration architecture guide
- Competitive bake-off risk: battlecard activation + competitive win story assets
- Deal dark >14 days: pattern interrupt campaign options (A/B/C by deal size)
- Contract/legal stalled: procurement acceleration playbook

4. MARKETING-SALES COORDINATION PROTOCOL
- Rules of engagement: what marketing can do WITHOUT asking the AE first
- Escalation triggers: when marketing must coordinate with AE before acting
- Weekly pipeline marketing cadence: how to review all open pipeline and assign actions
- CRM logging taxonomy: how to document marketing touches so sales sees and responds

5. MEASUREMENT FRAMEWORK
- Core metrics: deal velocity lift, win rate on influenced vs. non-influenced deals, EB engagement rate, stall recovery rate
- Weekly pipeline influence brief template (CMO → CRO weekly report)

Output in structured, implementation-ready format a B2B demand gen team can activate within one week.

## Advanced Customizable Version

ROLE: You are an elite B2B revenue marketing architect and pipeline influence specialist with 15+ years of experience aligning marketing and sales motions at enterprise SaaS companies scaling from $20M to $500M+ ARR. You have designed pipeline influence programs that demonstrably reduced average sales cycles by 20-35% and improved win rates by 15-25% at companies where marketing previously had limited deal-level visibility.

COMPANY CONTEXT:
- Company name: [COMPANY_NAME]
- Product category: [PRODUCT_CATEGORY — e.g., "enterprise data governance platform," "AI-powered workforce management"]
- Primary ICP: [PRIMARY_ICP — e.g., "Enterprise companies, 1,000-10,000 employees, VP Engineering or CISO"]
- Average contract value: $[ACV]
- Sales cycle: [SALES_CYCLE] months
- Current win rate: [WIN_RATE]%
- Current marketing influence on open pipeline: [INFLUENCE_% — e.g., "28% of deals have had ≥1 marketing touch post-SQL"]
- Marketing-sales alignment maturity: [LOW/MEDIUM/HIGH]
- Key competitors: [COMPETITORS]
- Top stall reasons (from win/loss analysis): [STALL_REASONS — e.g., "economic buyer not engaged," "security review delays," "no-decision/status quo"]

MARTECH/SALESTECH STACK:
- CRM: [CRM — e.g., Salesforce, HubSpot]
- Marketing Automation: [MAP — e.g., Marketo, HubSpot Marketing Hub]
- Sales Engagement: [SEP — e.g., Salesloft, Outreach]
- Conversation Intelligence: [CONV_INTEL — e.g., Gong, Chorus, or "none"]
- ABM Platform: [ABM_PLATFORM — e.g., 6sense, Demandbase, Terminus, or "none"]
- Direct Mail/Gifting: [DIRECT_MAIL — e.g., Sendoso, Postal.io, or "none"]
- Content Management: [CMS — e.g., Highspot, Seismic, Showpad, or "SharePoint/Google Drive"]
- Revenue Intelligence: [REV_INTEL — e.g., Clari, Gong Revenue, or "none"]

CURRENT PIPELINE METRICS:
- Total open opportunities: [OPP_COUNT] worth $[PIPELINE_VALUE]
- Average days in evaluation stage: [EVAL_DAYS]
- Deal stall rate (no progression >21 days): [STALL_RATE]%
- Marketing's current pipeline influence rate: [INFLUENCE_RATE]%
- Average ACV for won vs. lost deals: $[WON_ACV] vs. $[LOST_ACV]

OBJECTIVE: Design a fully automated AI-powered pipeline influence system that:
1. Increases marketing's measurable influence on open opportunities from [CURRENT]% to [TARGET]% within 90 days
2. Reduces average evaluation-stage duration by [TARGET_REDUCTION]% (days saved per deal)
3. Improves win rate on marketing-influenced deals by [WIN_RATE_TARGET]%
4. Gives the CRO weekly, deal-level visibility into marketing's pipeline contribution

---

DELIVERABLE 1: DEAL INTELLIGENCE & RISK SCORING SYSTEM

Build a comprehensive AI workflow for continuously analyzing all open CRM opportunities:

A. CRM Data Ingestion & Normalization
Define the exact CRM fields to extract for each opportunity:
- Opportunity ID, Account Name, Stage, Created Date, Expected Close Date
- ACV, Probability, Last Activity Date, Next Step field
- Contact roles: Champion (name, title, email, LinkedIn), Economic Buyer, Technical Evaluator, Security/Legal, End User Sponsor
- Activity history: calls logged, emails sent, meetings held (last 30/60/90 days)
- Marketing engagement: last email open date, last content downloaded, last event attended
- Competitive: competitor(s) mentioned in notes, battlecard shared (Y/N)
- Deal notes: summary of last 3 call notes (pulled from Gong transcript summary or CRM notes field)

B. Deal Risk Scoring Matrix
Score each opportunity on 5 dimensions (1-5 scale each, 25 points max):

Dimension 1: Engagement Recency (5 = activity in last 7 days; 1 = no activity in 30+ days)
Dimension 2: Committee Coverage (5 = 4+ stakeholders engaged by marketing; 1 = only champion identified)
Dimension 3: Marketing Influence Depth (5 = 5+ marketing touches post-SQL; 1 = zero marketing touches since SQL)
Dimension 4: Competitive Exposure (5 = no known competition; 1 = active bake-off against 2+ named vendors)
Dimension 5: Deal Progression Velocity (5 = advancing 1+ stage per month; 1 = stalled 3+ weeks with no movement)

Risk Band Definitions:
- 20-25: HEALTHY — monitor weekly, deploy standard influence content
- 15-19: AT RISK — prioritize marketing support this week
- 10-14: STALLED — immediate intervention required (pattern interrupt + exec escalation trigger)
- 5-9: DARK — emergency rescue program + AE escalation in same business day
- 1-4: LOST-RISK — CMO/CRO joint notification + last-resort save play

C. AI-Powered Deal Note Analysis
Design an LLM prompt that reads the last 5 CRM notes or Gong call summaries for each opportunity and outputs a marketing action recommendation. Run this prompt for every open deal during the weekly Monday scan:

You are an expert B2B revenue intelligence analyst. Analyze the following CRM activity data for open opportunity [OPP_ID] and produce a marketing action recommendation.

DEAL CONTEXT:
- Company: [ACCOUNT_NAME] | Industry: [INDUSTRY] | Employees: [EMPLOYEE_COUNT]
- ACV: $[ACV] | Stage: [STAGE] | Days in current stage: [DAYS_IN_STAGE]
- Champion: [CHAMPION_TITLE] (last marketing touch: [CHAMPION_LAST_TOUCH])
- Economic Buyer: [EB_TITLE] (last marketing touch: [EB_LAST_TOUCH])
- Competitor mentioned: [COMPETITOR or "none"]
- Recent call notes summary: [CALL_NOTES_SUMMARY — last 3 notes, 100 words max each]

OUTPUT REQUIREMENTS (respond in this exact format):
1. Primary buyer concern right now: [one sentence]
2. Marketing influence gap: [what's missing — e.g., "economic buyer has never engaged with marketing," "no ROI proof shared," "no competitive displacement content deployed"]
3. Recommended next marketing action: [asset type] → [stakeholder to target] → [channel] → [urgency: HIGH/MED/LOW]
4. Rationale: [one sentence]
5. Risk band: [HEALTHY / AT RISK / STALLED / DARK / LOST-RISK]

---

DELIVERABLE 2: BUYING COMMITTEE ORCHESTRATION FRAMEWORK

Design a systematic approach to multi-stakeholder influence across every active enterprise deal:

A. Stakeholder Persona Intelligence Map

For each of the 5 core buying committee roles, provide the full marketing intelligence profile:

CHAMPION (typically VP/Director-level functional or technical leader):
- Primary fear: losing political capital if the project fails or the vendor underdelivers
- Content that drives action: peer validation, implementation success stories, "how others like them did it" case studies with named outcomes
- Channel: email from AE + coordinated marketing follow-up within 48 hours, LinkedIn engagement
- Influence strategy: arm them with internal selling tools — executive summary, ROI model pre-populated with their data, board-ready one-pager they can forward without editing
- Content types to deploy: implementation guide, customer peer reference introduction, internal presentation template, ROI calculator, change management checklist

ECONOMIC BUYER (C-suite: CFO, COO, CEO, or budget-holder):
- Primary fear: wasted investment, project failure, disruption to operations, audit risk
- Content that drives action: analyst-validated ROI analysis, CFO-to-CFO peer references, Gartner/Forrester excerpts, pre-built business case with their company's numbers
- Channel: executive-to-executive direct outreach (your CMO/CEO to their CFO/CEO), peer reference call, NOT marketing automation
- Influence strategy: bypass champion when deal is stalled 21+ days — reach EB directly with executive peer validation
- Content types: CFO-ready ROI model, licensed analyst report, executive case study authored by a C-suite peer, 1-page investment justification, total cost of ownership comparison

TECHNICAL EVALUATOR (Architect, IT, DevOps, Security):
- Primary fear: implementation failure, security vulnerabilities, integration complexity, vendor lock-in, support quality
- Content that drives action: technical documentation, security review pre-fill packets, integration architecture guide, API documentation, DevOps runbooks, SOC2 report
- Channel: technical webinar invitation, direct email with technical attachments, engineering community engagement (GitHub, Slack communities)
- Influence strategy: proactively eliminate technical risk — provide security questionnaire pre-fill, architecture review session, integration sandbox access, reference technical contacts at similar companies
- Content types: security & compliance one-pager, API documentation, integration reference architecture, SOC2 Type II + executive summary, penetration test results (redacted), implementation timeline by tech stack

LEGAL/PROCUREMENT (General Counsel, VP Procurement, Vendor Management):
- Primary fear: contract risk, regulatory non-compliance, vendor viability, data liability
- Content that drives action: standard contract terms summary (eliminating negotiation delays), legal FAQ, compliance certifications, vendor risk assessment pre-fill, DPA
- Channel: formal email with attachments, procurement portal submission — not LinkedIn, not phone
- Influence strategy: provide everything they need before they ask for it — proactive package reduces back-and-forth from 6 rounds to 2
- Content types: Master Service Agreement summary (plain English), Data Processing Agreement (your standard version, pre-signed), compliance certifications index, legal FAQ with 20 most common questions answered, vendor security assessment pre-fill (80% answered), reference contacts from your legal team

END USER SPONSOR (Manager/Director who leads the team using the product):
- Primary fear: adoption failure, workflow disruption, training burden, looking bad to their team
- Content that drives action: role-specific demo video, change management guide, quick-win milestones, "day in the life after implementation" content, early access / beta invitation
- Channel: email, in-product demo, user community events, webinar
- Influence strategy: build grassroots enthusiasm that creates internal bottom-up pull — users advocating creates pressure on the economic buyer from inside
- Content types: role-specific use case demo, user quick-start guide, power user community invitation, success milestone templates, implementation FAQ for end users

B. Committee Coverage Heat Map
Scoring model for each individual stakeholder on an active deal:

Individual Stakeholder Score (0-10):
- 9-10: Highly Engaged (attended event, downloaded 3+ assets, replied to emails, met with marketing)
- 7-8: Engaged (opened emails, downloaded 1-2 assets, attended 1 webinar or meeting)
- 5-6: Aware (on mailing list, opened some emails, no content downloaded)
- 3-4: Cold (minimal email opens, no content engagement, receiving marketing but not acting)
- 1-2: Dark (never engaged with any marketing, email in system but no opens ever)
- 0: Unknown (contact not yet identified or added to CRM for this deal)

Account-Level Committee Coverage Score:
Formula: Sum of individual stakeholder scores / Number of identified stakeholders = Coverage Score
Target: ≥6.5 committee coverage score on all active enterprise deals over [ACV_THRESHOLD]
Critical Alert: Any deal where Economic Buyer score ≤3 AND deal age >45 days → immediate escalation to CMO

C. Influence Action Matrix
For each combination of [Stakeholder Role × Deal Risk Band], specify the marketing action. Example entries from the full 25-combination matrix:

Champion × STALLED:
- Asset: "Internal Champion Toolkit" — pre-built executive summary + ROI model with [ACCOUNT_NAME] data pre-populated
- Channel: AE forwards on behalf of marketing (more credible than marketing alias)
- Timing: Within 24 hours of stall detection
- Success trigger: Champion forwards toolkit to EB or requests updated ROI model with revised assumptions

Economic Buyer × STALLED:
- Asset: CFO peer reference letter (1 page, written by a CFO at a comparable company) + pre-populated ROI model
- Channel: Your CMO sends personal email to EB directly (not marketing automation — the sender matters)
- Personalization: Reference a peer CFO at a company matching [EB_COMPANY] in size and industry; include ROI line items that match [EB's stated priorities from call notes]
- Timing: Deploy within 24 hours of stall detection
- Success trigger: EB replies to CMO, forwards to champion, or requests a meeting

Technical Evaluator × COMPETITIVE RISK:
- Asset: Side-by-side technical comparison document (your platform vs. [COMPETITOR]) + migration guide from [COMPETITOR]
- Channel: Email from technical marketing or Solutions Engineer (not the AE — technical credibility matters)
- Timing: Same day as competitive mention detected in Gong or CRM notes
- Success trigger: Technical evaluator requests architecture review session or integration sandbox

Legal/Procurement × DARK:
- Asset: "Procurement Acceleration Package" — everything legal needs in one zip file before they ask
- Channel: Formal email to Legal contact (if known) OR through Champion with instruction to forward
- Timing: Day 22+ in legal review
- Success trigger: Legal/procurement acknowledges receipt and signals timeline to completion

---

DELIVERABLE 3: DEAL-SPECIFIC CONTENT ACTIVATION PLAYBOOKS

Complete step-by-step playbooks for the 5 most common deal stall scenarios:

PLAYBOOK 1: ECONOMIC BUYER NEVER ENGAGED
Trigger: Champion score ≥7 but EB score ≤2, deal age >30 days
Goal: Get economic buyer directly engaged within 10 business days

Step 1 (Day 0): AE or risk score alert triggers marketing: "EB not engaged on [OPP_ID]"
Step 2 (Day 1): Marketing prepares EB engagement package:
  - Company-specific ROI model: AI pulls [ACCOUNT_NAME] revenue/headcount from Clearbit/ZoomInfo → pre-populates model inputs with realistic assumptions
  - Peer reference selection: AI queries customer database → identifies 2-3 reference customers in same industry + similar company size → pulls outcome metrics
  - Executive summary: 1-page "[PEER_COMPANY] chose [YOUR_PRODUCT] because..." framed for a C-suite reader — outcomes only, no technical jargon
Step 3 (Day 1): CMO or VP Marketing sends direct personal email to EB:
  Subject: "How [PEER_COMPANY_CFO_NAME] at [PEER_COMPANY] justified this investment"
  [See Example section for full email template]
Step 4 (Day 3): If no EB response → champion receives: "Here's how to bring [YOUR_PRODUCT] to your [CFO/COO] — a ready-to-send internal business case deck"
Step 5 (Day 5): CMO follows EB on LinkedIn, comments on a recent post with a relevant insight (not promotional — just credibility-building)
Step 6 (Day 7): If EB still unresponsive → trigger executive briefing invitation from your CEO or CRO to EB + Champion together ("10 CISOs/CFOs in [INDUSTRY] are joining us for a private discussion on [RELEVANT_TOPIC]")
Step 7 (Day 10): If no engagement after Day 7 → AE escalation Slack: "EB completely dark at [ACCOUNT]. Recommend you ask [CHAMPION] for a direct EB introduction in your next call — here's a suggested ask: '[EXACT SCRIPT FOR AE TO USE]'"

PLAYBOOK 2: COMPETITIVE DISPLACEMENT RISK
Trigger: Competitor name mentioned in 2+ CRM notes or Gong transcripts, or probability drop ≥15%, or "bake-off" noted explicitly
Goal: Neutralize competitive risk within 7 business days

Step 1 (Day 0): AI detects competitive signal from Gong keyword tracker or CRM note search → Slack alert to Marketing + AE: "⚠️ [COMPETITOR] mentioned in [ACCOUNT] deal. Risk band elevated to COMPETITIVE."
Step 2 (Day 0): Marketing sends AE the relevant battlecard + competitive displacement one-pager within 2 hours
Step 3 (Day 1): Champion receives: "Questions buyers ask when comparing [YOUR_PRODUCT] vs. [COMPETITOR]" — structured as an FAQ, not a trash-talk document. Tone: confident, factual, peer-informed.
Step 4 (Day 2): Technical evaluator receives: "Technical architecture comparison: [YOUR_PRODUCT] vs. [COMPETITOR]" — focuses on capabilities, integration depth, and implementation time differences without disparaging language
Step 5 (Day 3): Activate a competitive win reference: a customer who switched FROM [COMPETITOR] to [YOUR_PRODUCT] sends a peer reference email or LinkedIn message to a counterpart at [ACCOUNT]
  - AI selects reference based on: same industry, similar company size, switched from same competitor
  - Marketing drafts reference email for customer to review and send (or marketing sends with customer's permission)
Step 6 (Day 5): Marketing sends review evidence to champion: curated G2/Capterra reviews from former [COMPETITOR] customers who switched to [YOUR_PRODUCT] — include 3 specific quotes with outcomes
Step 7 (Day 7): Economic buyer receives total cost of ownership comparison: [YOUR_PRODUCT] vs. [COMPETITOR] at [ACCOUNT] employee scale — AI generates with real pricing data and estimated implementation costs for both

PLAYBOOK 3: SECURITY/LEGAL REVIEW STALL
Trigger: Opportunity stage = "Legal Review" or "Security Review" for >21 days
Goal: Cut time in security/legal review by 50% — from industry average of 45 days to ≤22 days

Proactive Security Package (deploy BEFORE security review formally starts — prevents stall entirely):
  - Pre-filled vendor security questionnaire: AI generates answers to the 80% of questions that are standard (pulled from your security knowledge base); send to champion with note: "Here's our pre-filled VSAQ — usually eliminates the first 3 rounds of back-and-forth with your security team"
  - SOC2 Type II report + 1-page executive summary (non-technical language for the CFO/COO level)
  - GDPR/CCPA compliance documentation index with direct links
  - Data Processing Agreement — your standard version, already countersigned by your General Counsel
  - Penetration test results — most recent, redacted appropriately
  - Reference contacts: 3 customers who completed security review in <21 days — offer to connect their Head of Security directly

If already stalled in security review:
Week 1: Marketing orchestrates a "Security Fast-Track" package delivery via champion
  - Message to champion: "I know security reviews can drag. We've helped [PEER_COMPANY] complete their review in 14 days by providing everything up front. Can I get you the full package to hand to your security team this week?"
Week 2: If still stalled → request a 30-minute "security office hours" call between your CISO/Head of Security and their security evaluator — direct technical peer conversation eliminates review cycles
Week 3: If still stalled → CMO/CEO flags to legal team: "This deal has been in security review for [X] days. What's the one remaining blocker?" — direct executive-level problem-solving

PLAYBOOK 4: DEAL GOING DARK (NO ACTIVITY 14+ DAYS)
Trigger: Last CRM activity >14 days ago AND champion email not opened in past 10 days AND no meeting scheduled
Goal: Re-engage champion within 5 business days using a pattern interrupt (NOT a "just checking in" email)

Three pattern interrupt options, scaled to deal size:

OPTION A — High-Value Content Interrupt (ACV <$75k):
"We just published the [INDUSTRY] State of [PRODUCT_CATEGORY] Report — [ACCOUNT_NAME] was part of the data set. Here's the section most relevant to your team. [PERSONALIZED_FINDING based on their stated pain point]."
Deploy simultaneously: email + LinkedIn DM + paid retargeting (ad appears on LinkedIn with same report headline as the email subject line — reinforces the message across channels without duplicating outreach)

OPTION B — Peer Intelligence Share (ACV $75k-$149k):
"[PEER_COMPANY_CONTACT_NAME]'s [PEER_TITLE] just shared how they [ACHIEVED_OUTCOME_IN_ONE_SENTENCE]. Given what you mentioned about [CHAMPION_STATED_GOAL in last call note], I thought this was directly relevant."
AI matching logic: query open deal context → find customer with closest match (same industry + use case + company size) → pull outcome metric + contact name → draft personalized message

OPTION C — Executive Event Invitation (ACV >$150k):
Your CEO or VP of Product hosts a private dinner or roundtable for [NUMBER] senior leaders in [INDUSTRY]. [CHAMPION] and their [EB_TITLE] are personally invited.
Trigger: AE approves event-based reach to this account → Marketing generates personal invitation from your CEO

All three options follow this principle: they're unexpected, high-value, and persona-specific. The pattern interrupt works because it gives the prospect a reason to re-engage that benefits THEM — not a "just checking in" that benefits the seller.

PLAYBOOK 5: BUDGET FREEZE / DELAYED DECISION
Trigger: Champion explicitly cites "budget cycle," "need to wait until Q[X]," "board approval required," or probability drops to 20-40% with close date pushed by 90+ days
Goal: Keep deal warm, arm champion for budget approval, accelerate close when budget releases

Month 1 — Arm the Champion for Internal Selling:
- Deliver board-ready business case deck: AI generates company-specific version using their industry, company size, and the outcomes data from similar customers
- CFO justification kit: pre-populated ROI model + 1-page "why now vs. waiting" urgency argument (cost of inaction, risk if delayed, competitor activity in their space)
- Peer pressure lever: share a case study of a company in their industry that delayed a similar decision and the competitive consequence
- Marketing action: 1 high-value email to champion per month (not automated cadence — handwritten by VP Demand Gen or CMO)

Month 2 — Executive-Level Relationship Building:
- Invite champion + EB to exclusive executive advisory event (not a product webinar — a genuine peer-exchange event)
- Offer a "priority access" commitment: "If you close before [DATE], you're in our [Q/YEAR] implementation cohort with [NAMED_CSM]"
- Deploy LinkedIn executive engagement: CMO follows EB + champion, engages meaningfully with their content once per week (not promotional — relationship-building)

Month 3 — Implementation Urgency Creation:
- Pre-build an implementation timeline customized for [ACCOUNT_NAME]: "Your preferred go-live date is [DATE from call notes]. Here's the implementation schedule working backwards — kickoff needs to start by [DATE] to hit that target."
- Send this to champion with note: "I wanted to give you something concrete to work with when you go back to [CFO NAME] for budget approval — this shows exactly what happens from contract signature to value delivery."
- This creates legitimate urgency based on their own stated goal, not artificial pressure

---

DELIVERABLE 4: MARKETING-SALES COORDINATION SYSTEM

A. Rules of Engagement — Marketing Can Act WITHOUT AE Approval

Marketing may act immediately (inform AE after, don't ask before):
- Sending educational/thought leadership content (white papers, industry reports, webinars) to any identified deal contact
- Inviting deal contacts to third-party industry events (not company-hosted events)
- Running retargeting ads to account domains for all open opportunities (standard practice)
- Deploying paid social to job titles at active accounts
- Sending deal contacts content that matches their stated role/pain point from call notes
- Publishing review/reference requests to peer customers (not the deal contact)

B. Rules of Engagement — AE Approval Required Before Marketing Acts

Marketing must Slack the AE and wait for a thumbs-up (4-hour SLA for AE response):
- Any direct email from CMO, CEO, or CRO to an Economic Buyer or C-suite contact
- Sending competitive displacement content to any stakeholder
- Initiating executive briefing, roundtable, or dinner invitations
- Physical mail or gifting campaigns to specific contacts
- Activating a customer peer reference call or reference letter
- Any content that implies the deal is at a specific evaluation stage ("as you finalize your vendor selection...")
- Account-specific custom content (pre-populated ROI models, personalized executive summaries)

C. Weekly Pipeline Marketing Cadence

Monday 6am: AI automated scan runs → Pipeline Influence Brief generated for all open opportunities → posted to Slack #pipeline-marketing-weekly
Monday 9am: Marketing team reviews brief (async) — each marketer claims action items on their assigned deals
Tuesday 30-min standup: Marketing + RevOps review top 10 at-risk deals, confirm actions, resolve any AE coordination needed
Wednesday-Friday: Deploy approved actions. For each action: Slack AE before deploying (if approval required), log completion in CRM immediately.
Friday 4pm: Weekly CRM log audit — confirm all deployed touches are logged with correct activity type and outcome field

D. CRM Activity Logging Taxonomy

Every marketing touch on an open opportunity MUST be logged as a CRM activity with these exact fields:
- Activity Type: "Marketing: Pipeline Influence" (custom activity type — create this in your CRM)
- Subtype: [Content Sent / Exec Outreach / Reference Activated / Event Invitation / Pattern Interrupt / Competitive Response]
- Asset/Action Description: exact name of content sent or action taken
- Contact Targeted: which stakeholder received the touch
- Marketing Owner: who deployed it
- Outcome: [Opened / Replied / Attended / Downloaded / No Response / Bounced] — update within 72 hours
This logging enables the win-rate and velocity analysis in Deliverable 6 without any manual reporting.

---

DELIVERABLE 5: AUTOMATION ARCHITECTURE

A. Weekly CRM Scan & Score Automation (runs every Monday 6:00am)

Technical workflow (built in Zapier, Make, or native CRM automation):
1. Query CRM: Pull all Opportunities WHERE Stage NOT IN ['Closed Won', 'Closed Lost'] AND Close Date > [TODAY]
2. For each opportunity: calculate Risk Score using Deliverable 1 formula
   - Fetch: last activity date, contact role list, marketing engagement history, CRM notes (last 5)
   - Apply: 5-dimension scoring matrix → compute total score → assign risk band
3. Update CRM custom fields: "MktPipelineRiskScore" (numeric) + "MktPipelineRiskBand" (picklist: HEALTHY/AT RISK/STALLED/DARK/LOST-RISK)
4. Run LLM deal analysis prompt (Deliverable 1C) for all deals in STALLED or DARK bands
5. Auto-generate Pipeline Influence Brief (populate template with extracted data)
6. Post to Slack #pipeline-marketing-weekly + email to CMO, VP Demand Gen, RevOps Manager
7. Create CRM tasks for marketing team: one task per AT RISK, STALLED, or DARK deal — assigned to deal owner in marketing (or CMO for EB outreach)

B. Trigger-Based Playbook Activation Automations

Playbook 1 Trigger (EB Not Engaged):
IF: Opportunity Age > 30 days AND Contact Role "Economic Buyer" has Marketing Engagement Score ≤2
THEN:
  → CRM task created for marketing: "Prepare EB engagement package for [OPP_NAME] by [DATE+2 days]"
  → Enrichment call to Clearbit/ZoomInfo: pull EB name, title, LinkedIn URL for [ACCOUNT_DOMAIN]
  → Customer reference query: find 3 customers in same [INDUSTRY] + [EMPLOYEE_COUNT_BUCKET] → extract outcome metrics
  → LLM drafts CMO outreach email (inputs: EB name, company, industry, peer references, stated pain point from call notes)
  → Draft posted to Slack DM to CMO: "[OPP_NAME] EB has never engaged — here's a draft email. Approve with 👍 or edit and reply."

Playbook 2 Trigger (Competitive Risk):
IF: Gong keyword tracker fires [COMPETITOR_NAME] on a call for [ACCOUNT] OR CRM notes updated with [COMPETITOR_NAME] mention
THEN:
  → Immediate Slack alert to Marketing + AE: "⚠️ [COMPETITOR] mentioned in [ACCOUNT] ([OPP_NAME], $[ACV])"
  → CRM field "Competitor" updated automatically
  → Marketing Risk Score recalculated: Competitive Exposure dimension forced to 1 → overall score decremented
  → CRM task created: "Deploy Competitive Playbook — [COMPETITOR] — [OPP_NAME] — due in 24 hours"
  → Battlecard for [COMPETITOR] retrieved from Highspot/Seismic → linked in Slack alert for AE

Playbook 4 Trigger (Deal Going Dark):
IF: Last CRM Activity Date > 14 days AND last marketing email opened by champion > 10 days
THEN:
  → Classify ACV tier → select Pattern Interrupt option (A/B/C)
  → For Options A and B (ACV <$150k): auto-generate pattern interrupt email using LLM → deploy without AE approval; send Slack to AE: "Marketing deployed pattern interrupt to [CONTACT] at [ACCOUNT] — [CONTENT DESCRIPTION]. Let us know if you speak with them."
  → For Option C (ACV >$150k): generate event invitation draft → route to AE for approval in Slack before sending
  → Log in CRM: "Marketing: Pattern Interrupt" activity under the opportunity

C. Content Personalization Engine

ROI Model Auto-Personalization Workflow:
Inputs needed: [ACCOUNT_NAME], [INDUSTRY], [EMPLOYEE_COUNT], [ANNUAL_REVENUE_ESTIMATE from Clearbit], [CHAMPION_STATED_GOAL from CRM notes], [TYPICAL_ROI_FOR_INDUSTRY from your internal ROI data]

LLM prompt:
Generate a personalized 3-year ROI model introduction for [ACCOUNT_NAME].

CONTEXT:
- Company: [ACCOUNT_NAME] | Industry: [INDUSTRY] | Size: [EMPLOYEE_COUNT] employees, ~$[REVENUE_ESTIMATE] revenue
- Champion's stated goal: [CHAMPION_GOAL from CRM notes]
- Our typical ROI for similar companies: [ROI_DATA — e.g., "23% reduction in [METRIC], 14-month payback period"]
- Reference company to cite: [REFERENCE_COMPANY] achieved [REFERENCE_OUTCOME] in [TIMEFRAME]

OUTPUT:
1. One-paragraph CFO-ready ROI summary (no jargon, business outcomes only, [ACCOUNT_NAME]-specific numbers)
2. Three top-line ROI claims for [ACCOUNT_NAME] based on their size and industry (specific percentages/dollars)
3. Suggested subject line for the email that delivers this model to the EB

Case Study Selection & Personalization Workflow:
Inputs: [ACCOUNT_INDUSTRY], [ACCOUNT_EMPLOYEE_COUNT], [CHAMPION_PAIN_POINT from CRM], [COMPETITOR in deal if any]

Ranking formula: Select case study that maximizes: Industry match × 0.40 + Company size match × 0.30 + Pain point match × 0.30. If competitive displacement needed: add filter: same competitor mentioned in case study = required.

LLM generates 2-paragraph "why this case study is relevant to [ACCOUNT_NAME]" intro customized for the champion.

---

DELIVERABLE 6: MEASUREMENT & REPORTING FRAMEWORK

CORE METRICS WITH FORMULAS:

1. Pipeline Influence Rate
Definition: % of open opportunities with ≥1 marketing touch post-SQL
Formula: (Opportunities with ≥1 post-SQL marketing activity logged) / (Total open opportunities) × 100
Target: ≥75% of all open opportunities
Data source: CRM activity log filtered by Activity Type = "Marketing: Pipeline Influence"

2. Economic Buyer Engagement Rate
Definition: % of enterprise deals (>$[ACV_THRESHOLD]) where the EB has received ≥1 marketing touch
Formula: (Enterprise deals with EB contact score ≥3) / (Total enterprise deals) × 100
Target: ≥50% of enterprise deals within 60 days of opportunity creation

3. Deal Velocity Lift (Influenced vs. Not)
Definition: Average days from SQL to Close Won for highly-influenced deals vs. low-influence deals
Formula: avg(days_to_close WHERE influence_touchcount ≥5) vs. avg(days_to_close WHERE influence_touchcount ≤1)
Target: ≥20% faster close for heavily-influenced deals
Report quarterly — needs 20+ closed deals per cohort for statistical significance

4. Win Rate by Influence Tier
Definition: Win rate segmented by marketing influence intensity
Tiers: Heavy (≥5 marketing touches), Moderate (2-4 touches), Light (1 touch), None (0 touches)
Formula: Won / (Won + Lost) for each tier
Target: Heavy-influence win rate ≥15 percentage points higher than None tier

5. Stall Recovery Rate
Definition: % of STALLED or DARK deals that advance to the next stage within 21 days of a marketing intervention
Formula: (Deals that advanced stage within 21 days post-marketing action) / (Total marketing interventions on STALLED/DARK deals) × 100
Target: ≥35% stall recovery rate

6. Competitive Win Rate with Displacement Playbook
Definition: Win rate on competitive deals where marketing deployed Playbook 2
Formula: Competitive deals won WITH playbook deployed / All competitive deals WITH playbook deployed × 100
Benchmark: Compare to win rate on competitive deals where NO playbook was deployed
Target: ≥15 percentage point lift vs. no-playbook competitive deals

7. Multi-Stakeholder Coverage Rate
Definition: % of enterprise deals where ≥3 buying committee members have been engaged
Formula: (Enterprise deals with ≥3 contacts at ≥5 engagement score) / (Total enterprise deals) × 100
Target: ≥60% for deals over $[ACV_THRESHOLD]

8. Marketing-Influenced Pipeline Value
Definition: $ value of open pipeline with active marketing influence (marketing touch in last 30 days)
Formula: Sum of ACV for all opportunities with last marketing activity date ≤30 days ago
Target: Track as a CRO-facing metric alongside "Marketing-Sourced Pipeline" — this is "Marketing-Influenced Pipeline"

CMO → CRO WEEKLY PIPELINE INFLUENCE BRIEF TEMPLATE:

Pipeline Influence Brief — Week of [DATE]

HEADLINE METRICS (vs. last week):
- Open pipeline: $[VALUE] across [COUNT] deals
- Pipeline influence rate: [X]% → [↑↓→ vs. last week]
- Deals with no marketing touch in 21+ days: [COUNT] (worth $[VALUE])
- Deals with EB not engaged: [COUNT]
- New competitive threats detected: [COUNT]
- Deals in STALLED or DARK band: [COUNT]

TOP 5 PRIORITY ACTIONS THIS WEEK:
1. [DEAL NAME] ($[ACV], [STAGE], Day [X] in stage) — Risk: [BAND] — Action: [RECOMMENDED_ACTION] — Owner: [MARKETING_OWNER]
[repeat for 5 deals]

MARKETING ACTIONS THAT MOVED DEALS LAST WEEK:
1. [OPP_NAME]: [Marketing action deployed] → Deal advanced from [STAGE_A] to [STAGE_B] — [X] days since last movement
[repeat]

DEALS TO WATCH (approaching 21-day stall threshold):
[List deals at risk of entering STALLED band within 7 days]

REPORTING CADENCE:
- Monday 6am: Automated Pipeline Influence Brief → Slack + email
- Monthly: CMO presents pipeline influence metrics to CRO in pipeline review meeting (15-min standing agenda item)
- Quarterly: Full attribution analysis — cohort of closed deals, win rate by influence tier, velocity lift, ROI of pipeline marketing investment

## Example Input/Output

**Input Example:**

Company: Vaultara (fictional enterprise data governance & compliance platform)
ICP: CISO, VP of IT, CDO at financial services companies (2,000-15,000 employees)
ACV: $285,000
Sales cycle: 6.2 months average
CRM: Salesforce
Current open pipeline: $18.5M across 47 deals
Marketing influence rate: 28% (only 13 of 47 deals have had any marketing touch post-SQL)
Top stall reasons: Security review delays (avg 52 days in review), Economic buyer not engaged (champion can't get CFO approval independently)
Stack: Salesforce, Marketo, Gong, Highspot, Sendoso

---

**Output Example — Week 1 Pipeline Influence Brief:**

Pipeline Influence Brief — Week of May 18, 2026 — Vaultara

HEADLINE METRICS:
Open pipeline: $18.5M | 47 deals
Pipeline influence rate: 28% ↓ (target: 75%)
Deals with no marketing touch in 21+ days: 31 (worth $12.8M) ⚠️
Deals with EB not engaged: 22 ⚠️
New competitive threats (Varonis, Collibra in Gong): 4 deals
Deals in STALLED or DARK: 8

TOP 5 PRIORITY ACTIONS THIS WEEK:

1. DEAL: Meridian Capital Group ($620k, Stage: Security Review, Day 38)
   RISK: STALLED — security review at 38 days (benchmark: <22 days possible)
   ACTION: Deploy Security Fast-Track package today
   OWNER: Sarah Chen (Demand Gen)
   PLAYBOOK: Playbook 3 | Expected impact: reduce remaining review time by 2-3 weeks

2. DEAL: Nexion Financial ($445k, Stage: Evaluation, Day 61)
   RISK: DARK — no CRM activity 18 days, champion (VP IT) email unopened 3 weeks
   ACTION: Pattern Interrupt — Option B (Peer Intelligence Share)
   OWNER: Sarah Chen + AE James Torres (Slack James first — he may have context)
   DRAFT SLACK TO AE: "James — Nexion has gone dark on me. Before I send a pattern interrupt, any reason NOT to reach out now? Planning to send [CHAMPION] the Pinnacle Bancorp case study — their VP IT had the same Q3 deadline pressure. Approve with 👍?"

3. DEAL: Hartwell Insurance ($390k, Stage: Technical Evaluation, Day 29)
   RISK: AT RISK — CFO (EB) score = 0, never touched by marketing. Champion is Director-level, insufficient budget authority for $390k.
   ACTION: CMO outreach to CFO — prepare EB package + ROI model today
   OWNER: Rebecca Walsh (CMO) — personal email, not Marketo
   SUBJECT LINE DRAFT: "How Pacific Insurance's CFO justified $380K in data governance investment"

4. DEAL: Blackridge Asset Management ($510k, Stage: Vendor Shortlist, Day 14)
   RISK: COMPETITIVE — Varonis mentioned twice in Gong transcripts from 5/14 call. Explicitly "down to 2 vendors."
   ACTION: Deploy competitive displacement playbook (Varonis) immediately — AE already on alert
   OWNER: Sarah Chen + AE Mike Davis
   DELIVERABLE: Technical comparison (Vaultara vs. Varonis) to CISO + IT Architect by Wednesday

5. DEAL: Cornerstone Group ($195k, Stage: Evaluation, Day 44)
   RISK: AT RISK — Committee coverage score: 3.2. Only champion engaged. IT Architect and Head of Compliance are at score 0 (not identified in Salesforce).
   ACTION: Identify and add IT Architect + Head of Compliance to CRM. Deploy role-specific content to each.
   OWNER: Sarah Chen
   HOW: Pull LinkedIn profiles from Sales Navigator for Cornerstone → add to CRM with correct contact roles

MARKETING ACTIONS THAT MOVED DEALS LAST WEEK:
1. Pinnacle Bancorp ($380k): CMO sent peer CFO reference letter from Gulf Coast Savings Bank → Deal advanced from "Pending Internal Approval" to "Contract Review" in 6 days (had been stalled 19 days)
2. Tidewater Capital ($210k): Pattern interrupt (State of Data Governance 2026 Report) re-engaged dark champion after 23-day silence → Meeting scheduled for May 22

---

**Example CMO → CFO Outreach Email (Playbook 1, Hartwell Insurance):**

From: Rebecca Walsh, CMO, Vaultara
To: [CFO First Name], Hartwell Insurance

Subject: How Pacific Insurance's CFO justified $380K in data governance investment

[CFO NAME],

Our team has been working with your colleagues on a data governance initiative, and I wanted to reach out directly with something that might make your evaluation process faster.

Pacific Insurance's CFO faced the same question you're likely considering: how do you justify a significant data governance investment when the ROI isn't immediately obvious?

Their approach: they quantified their actual regulatory exposure under NYDFS ($2.3M in potential fines based on their current audit gap) against the implementation cost — and got board approval in three weeks.

I've attached two things that might be useful:
1. Pacific Insurance's investment justification framework (1 page — their CFO approved us sharing this)
2. A pre-populated ROI model built for Hartwell's employee count and regulatory profile

I'm happy to walk through it in 20 minutes, or if a conversation with Pacific's CFO would be more useful, I can arrange that directly.

Rebecca Walsh
CMO, Vaultara
[Direct phone] | [LinkedIn]

P.S. If it's easier, I can also work with your team to build out the business case materials your team needs for an internal board presentation — we've done this for 12 financial services clients in the past 18 months.

## Success Metrics

- **Pipeline influence rate**: Reach ≥75% of open opportunities touched by marketing post-SQL within 90 days (typical baseline: 25-35%)
- **Economic buyer engagement**: ≥50% of enterprise deals (>$100k ACV) have a marketing touch to the EB within 60 days of deal creation
- **Deal velocity lift**: 20-30% reduction in average days in evaluation stage for deals with ≥5 marketing touches vs. ≤1 touch
- **Win rate improvement**: ≥15 percentage point higher win rate on deals with heavy marketing influence vs. no influence — validated across a minimum 20-deal cohort per quarter
- **Stall recovery**: ≥35% of STALLED/DARK deals advance to next stage within 21 days of marketing intervention
- **Competitive win rate lift**: ≥15 percentage point improvement in win rate on competitive deals where Playbook 2 was deployed vs. competitive deals where it was not
- **CMO-CRO alignment**: Marketing's pipeline influence metrics are a standing 15-minute agenda item in the weekly CRO pipeline review — marketing can defend every active deal's influence status
- **Content-to-velocity correlation**: Top 3 influence content assets identified by correlating CRM activity logs with stage progression events — quarterly update to the content roadmap based on findings

## Related Prompts

- [ABM Buying Committee Engagement & Multi-Stakeholder Intelligence Engine](./ABM-Buying-Committee-Engagement-&-Multi-Stakeholder-Intelligence-Engine.md)
- [AI-Powered ABM Executive Engagement & C-Suite Relationship Intelligence Engine](./AI-Powered-ABM-Executive-Engagement-&-C-Suite-Relationship-Intelligence-Engine.md)
- [AI-Powered ABM Target Account List Building & ICP Scoring Intelligence Engine](./AI-Powered-ABM-Target-Account-List-Building-&-ICP-Scoring-Intelligence-Engine.md)
- [AI-Powered B2B Pipeline Acceleration & Late-Stage Deal Marketing Intelligence Engine](../Lead-Generation-Campaigns/AI-Powered-B2B-Pipeline-Acceleration-&-Late-Stage-Deal-Marketing-Intelligence-Engine.md)

## Integration Tips

- **Salesforce**: Create a custom object "Mktg Pipeline Influence" linked to Opportunity; add custom fields: "MktPipelineRiskScore" (number), "MktPipelineRiskBand" (picklist), "EBEngagementScore" (number), "CommitteeCoverageScore" (formula field); use Flow Builder to auto-create tasks when risk band = STALLED or DARK; add Marketing Influence Score to the Opportunity layout so AEs see it on every deal page; use Einstein Analytics (or Tableau CRM) to build the pipeline influence dashboard with cohort win rate analysis
- **HubSpot**: Use Deals-based workflows with "Days in Stage" and custom properties for risk scoring; create Deal lists for each risk band (used for bulk action by marketing team); use HubSpot's Activity Feed on the Deal record for marketing touch logging; Sequences tool (Sales Hub) for coordinated marketing + SDR touches on BOFU deals
- **Gong**: Set up trackers for competitor names, key objection phrases ("legal review," "budget freeze," "evaluating vendors"), and buying committee keywords ("get CFO approval," "bring to the board") — these auto-trigger playbook alerts when detected in any call recording for an active deal; use Gong Engage for marketing-coordinated email sequences where marketing content is embedded in AE-sent cadences
- **6sense/Demandbase**: Sync account intent scores and buying stage from your ABM platform to Salesforce as custom opportunity fields; use account engagement score as an input to the Marketing Risk Score (high intent from ABM platform + no CRM activity = accelerated dark detection); create retargeting audiences from active opportunity accounts and ensure all open pipeline accounts are in a LinkedIn/Google remarketing audience at all times
- **Highspot/Seismic**: Enable "Content Engagement" tracking linked to Salesforce contacts — when a deal contact views a specific asset from Highspot, auto-log a CRM activity; use content performance reports to identify which assets correlated with deals that advanced stage; build dedicated "Pipeline Influence" content collections by playbook type (competitive, EB engagement, security review, etc.) so marketing can find and deploy assets in seconds
- **Sendoso/Postal.io**: Configure Zapier trigger: when Opportunity custom field "PatternInterruptType" = "C" (executive option) AND ACV >$150k AND AE approves → auto-generate gift send via Sendoso API with personalized note drafted by LLM; set per-deal budget cap ($250 max) and require AE approval for all physical sends; use QR code on physical mailer linking to a personalized landing page (Mutiny or Qualified) for attribution tracking
- **Clari/Gong Revenue**: Export Clari's AI-generated deal risk flags weekly into Salesforce as a custom field; run a correlation analysis quarterly to measure alignment between Clari's risk score and your Marketing Risk Score — deals where both flag risk simultaneously should be your highest-priority interventions; use Clari's "deal activity" module to supplement (not replace) marketing touch logging

## Troubleshooting

**Problem: Sales team is frustrated — they feel marketing is "touching their deals" without permission and creating confusion with prospects who receive conflicting messages**
Solution: The root cause is almost always marketing acting without AE visibility, or sending the wrong content at the wrong deal stage. Fix this with two changes: (1) implement the "AE Approval Required" rules from Deliverable 4B strictly — no exceptions for any outreach that is account-specific, executive-level, or competitive; (2) build a shared Slack channel (#pipeline-marketing-sync) where every marketing action on an open deal is announced to the AE before it deploys: "About to send [CONTACT] at [ACCOUNT] our security FAQ — anything I should know first?" Run this for 30 days. Most AE resistance disappears when they realize marketing is helping them close, not competing with them for the relationship. If resistance persists, pull win rate data: show AEs that their deals with heavy marketing influence close 20% faster and at 15% higher win rates. Data almost always wins the culture argument.

**Problem: CRM data quality is too poor to run the risk scoring model — contact roles aren't filled, activity notes are thin, and the "last activity date" doesn't reflect actual AE communication because reps log in their email tool, not Salesforce**
Solution: Don't wait for perfect data — run the model on the 2-3 dimensions you DO have. Start with Days in Stage + ACV alone; those two inputs alone will surface 80% of your at-risk deals. In parallel, run a focused data quality sprint: (1) Ask RevOps to build a Salesforce report showing all open opportunities missing "Champion" and "Economic Buyer" contact roles — share this with the AE team and their manager as a weekly task ("fill in contact roles for your top 5 deals by Friday"); (2) Use Gong's integration to auto-populate CRM notes from call transcripts — this eliminates the "reps don't log notes" problem entirely; (3) Use Clay, ZoomInfo, or Apollo to enrich missing contact data for open accounts automatically. Within 4-6 weeks you typically have sufficient data quality to run the full model.

**Problem: Marketing is running pipeline influence activities and logging them in CRM, but the CRO doesn't believe marketing contributed to deals — they say "those deals would have closed anyway"**
Solution: This is a correlation vs. causation problem that requires a control group methodology. Pull the last 6 months of closed-won and closed-lost deals. Segment into four cohorts by marketing influence touchcount (0 touches, 1-2, 3-5, 6+). Calculate win rate and days-to-close for each cohort. If your influence program is working, you'll see a clear positive correlation between touchcount and win rate — and that data is difficult for a CRO to dismiss. For deals where marketing deployed a specific playbook (e.g., EB engagement), also pull Gong call transcripts from the week after the EB outreach: if prospects mention the content marketing sent ("I shared that ROI model with my CFO and it helped her understand the value"), capture those quotes verbatim and include them in your monthly CMO → CRO report. Qualitative evidence of marketing contribution, cited in buyer's own words, is often more persuasive to a CRO than any regression analysis.

## Version History
- v1.0: Initial creation (auto-generated)
