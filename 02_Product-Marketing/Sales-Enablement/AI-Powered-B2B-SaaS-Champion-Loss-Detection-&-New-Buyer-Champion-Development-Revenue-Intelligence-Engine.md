# AI-Powered B2B SaaS Champion Loss Detection & New Buyer Champion Development Revenue Intelligence Engine - Detect When Your Champion Leaves and Systematically Build a New One Before the Deal Dies

**Difficulty:** Advanced | **Time:** 30-45 min | **Tags:** pipeline acceleration, champion development, sales enablement, B2B SaaS, deal defense, stakeholder mapping, buyer committee, CRM automation, churn prevention, renewal risk, revenue operations, win rate

## Overview
Designs a complete marketing-and-sales-aligned system that detects when a champion leaves an active pipeline deal or existing customer account, identifies the most viable replacement champion, and executes a structured multi-touch reactivation sequence to rebuild internal sponsorship before the deal stalls or the renewal is lost. Use this when you are losing deals to "no decision" after a contact job change, seeing unexplained deal stalls following personnel transitions at prospect accounts, or experiencing churn at accounts where the original champion departed and no replacement was developed.

## Quick Copy-Paste Version

You are a B2B SaaS revenue marketing strategist specializing in pipeline defense and buyer champion development. Design a complete, production-ready system that detects when a key champion leaves an active deal or customer account, immediately identifies the most viable replacement stakeholder, and executes a coordinated marketing-and-sales campaign to build new internal sponsorship — preventing pipeline collapse or customer churn caused by champion departure.

COMPANY CONTEXT:
- Company: [e.g., "Meridian — AI-powered revenue forecasting platform for enterprise revenue operations and finance teams"]
- ICP: [e.g., "VP Revenue Operations, VP Finance, CRO at B2B SaaS companies $50M-$500M ARR, 200-2,000 employees"]
- ACV: [e.g., "$85,000 | 5-7 month average sales cycle | 5-7 person buying committee"]
- Typical champion profile: [e.g., "VP Revenue Operations or Director of Revenue Ops — the primary day-to-day driver of the evaluation and internal advocate to the CFO and CRO"]
- CRM and signal stack: [e.g., "Salesforce, Outreach, LinkedIn Sales Navigator, ZoomInfo, Gong, 6sense"]

CHAMPION DEPARTURE SIGNALS TO DETECT:
- Signal #1: [e.g., "Champion updates LinkedIn profile to show new company or new role"]
- Signal #2: [e.g., "Champion email bounces back — invalid address"]
- Signal #3: [e.g., "Champion goes dark — 0 engagement for 21+ days after previously consistent communication"]
- Signal #4: [e.g., "AE reports champion mentioned they are 'leaving' or 'transitioning' in a call"]
- Signal #5: [e.g., "ZoomInfo contact record shows job title or employer change"]

OUTPUT REQUIRED:
1. CHAMPION DEPARTURE DETECTION SYSTEM: Signal scoring model and automated monitoring setup that identifies champion departure within 48-72 hours of occurrence, with Salesforce field definitions and CRM alert rules
2. REPLACEMENT CHAMPION IDENTIFICATION FRAMEWORK: A systematic process to map the new likely champion from existing contacts in the account, LinkedIn research, and organizational intelligence — including a ranked shortlist with outreach prioritization
3. NEW CHAMPION DEVELOPMENT PLAYBOOK: A 30-day, 3-phase reactivation campaign (Stabilize → Educate → Re-Anchor) with specific email sequences, content assets, and AE coordination touchpoints for both active pipeline deals and at-risk customer accounts
4. DEAL TRIAGE DECISION TREE: A framework to quickly assess whether to pursue a new champion, pause the deal, or escalate to an executive-to-executive play based on deal stage, ACV, and replacement champion viability
5. CONTENT ARSENAL FOR NEW CHAMPION: The 6 specific content assets needed to bring a new champion up to speed — without requiring them to restart from scratch — with briefs for anything that doesn't yet exist
6. WIN-BACK MEASUREMENT FRAMEWORK: How to track program effectiveness, measure pipeline protected vs. lost, and iterate champion development sequences by deal stage and champion persona

## Advanced Customizable Version

ROLE: You are a senior B2B revenue marketing strategist with 15+ years of experience in pipeline acceleration, buyer champion development, and enterprise deal orchestration at B2B SaaS companies. You have served as VP Product Marketing and VP Revenue Marketing at companies where champion turnover was responsible for 18-24% of all late-stage pipeline loss annually. You have built champion development systems that recovered deals with ACV ranging from $40K to $2M after a champion departed, and you understand the precise window — typically 14-21 days — between when a champion leaves and when a deal permanently stalls or a renewal goes at risk. You design systems that do two things simultaneously: stabilize the deal immediately (buy time while a new champion is found) and systematically build a replacement champion who can own the evaluation internally and survive their own eventual promotion or departure. You treat champion loss as a marketing failure as much as a sales problem — because great champions are built through months of educational content, community, and proof-of-value touch points, not just by AEs asking the champion to "own the deal internally."

OBJECTIVE: Design a complete, production-ready champion loss detection and replacement champion development system that:
- Detects champion departure signals across LinkedIn, email bounce, CRM activity, and call intelligence within 48-72 hours of occurrence
- Executes a 72-hour "deal stabilization" response to prevent the deal from going cold while a replacement champion is identified
- Systematically identifies the highest-probability replacement champion from organizational data, LinkedIn research, and buying committee maps already in Salesforce
- Delivers a 30-day champion onboarding and education sequence specifically designed for stakeholders who are being introduced to a vendor mid-evaluation rather than at the beginning
- Applies distinct playbooks for three scenarios: (a) active pipeline deal, mid-evaluation; (b) active pipeline deal, late-stage pre-close; (c) existing customer account, champion departure before renewal
- Measures champion development effectiveness with deal-outcome attribution and iterates sequences based on win/loss data

COMPANY PROFILE:
- Company name and product: [name + one-sentence product description]
- Business model: [SaaS / usage-based / hybrid + ACV range + deal size distribution]
- Sales motion: [AE-led enterprise / PLG-to-enterprise / inbound-assisted / outbound-led]
- ICP: [primary buyer titles, company size, verticals — be specific]
- Typical champion persona: [title, responsibilities, what they care about, how they present internally]
- Buying committee composition: [economic buyer, champion, IT, procurement, end users — and their relationships to each other]
- Average sales cycle: [by deal size tier]
- CRM: [Salesforce / HubSpot + stage definitions and field configuration capability]
- Signal tools: [LinkedIn Sales Navigator, ZoomInfo/Apollo, Gong/Chorus, 6sense/Bombora, email delivery monitoring]
- Champion departure history: [% of deals affected annually, typical deal outcome after champion loss — if known]

---

### PHASE 1: CHAMPION DEPARTURE DETECTION ARCHITECTURE

**Multi-Signal Monitoring Framework:**

Build a composite "Champion Stability Score" for every active pipeline deal and customer account within 60 days of renewal:

TIER 1 — HIGH-CONFIDENCE DEPARTURE SIGNALS (each worth 50 points):
- Champion LinkedIn profile shows new employer or "Open to Work" status: [Configure LinkedIn Sales Navigator "Job Change" alert for all contacts flagged as Champion in Salesforce — alert fires within 24-48 hours of profile update]
- Champion email hard-bounces on any outbound send: [Marketing automation email delivery failure for Champion-role contact triggers Salesforce task and Slack alert to AE + marketing ops within 4 hours]
- AE logs explicit departure in Gong call transcript: [Configure Gong Smart Tracker for phrases: "leaving the company," "my last day," "I'm transitioning," "you'll be working with [name] going forward" — auto-creates Salesforce field update "Champion Departure Risk: Confirmed"]
- ZoomInfo or Apollo contact record shows employer change: [Configure ZoomInfo intent alert: "Contact Record Updated: Employer Changed" for all champion-role contacts across active pipeline + renewal accounts — webhook to Salesforce]

TIER 2 — MEDIUM-CONFIDENCE SIGNALS (each worth 30 points):
- Champion engagement drops to zero for 21+ consecutive days after a period of consistent weekly engagement: [Salesforce calculated field: "Champion Engagement Gap (Days)" — triggers alert when gap exceeds 21 days for Stage 3+ deals or renewal accounts within 90 days]
- AE reports in call notes or Slack that champion is "hard to reach" or "delayed responding" without a stated reason: [CRM field: "Champion Responsiveness" picklist — AE updates weekly on 5+ stage deals]
- Champion LinkedIn activity increases sharply on competitor content, recruitment posts, or "career milestone" posts (promotion, work anniversary at new company): [LinkedIn Sales Navigator activity alert — high-volume engagement signal on non-company content]
- Champion stops opening emails after previously opening >60% of communications: [Marketing automation engagement scoring — Champion-role email open rate drops to <20% for 14 days after being >60% previously]

TIER 3 — EARLY WARNING SIGNALS (each worth 15 points):
- Champion stops attending scheduled calls or reschedules twice without clear reason: [Gong call activity report — Champion not present on last 2 scheduled calls; configured as a Salesforce activity tracking field]
- Champion suddenly introduces new stakeholder into process without explanation ("CC'ing my colleague from now on"): [Gong transcript pattern alert: new name introduced by champion with handoff language]
- Champion's title disappears from LinkedIn without a new role listed: [LinkedIn Sales Navigator — profile becomes sparse or experience section changes without a new employer]

CHAMPION STABILITY SCORE THRESHOLDS:
- Score 0-29: Healthy — no action, monitor weekly
- Score 30-59: Watch — AE prompted to confirm champion status on next call; Salesforce reminder task created for AE: "Confirm champion engagement status with [Champion Name]"
- Score 60-89: At Risk — marketing activates 72-hour stabilization protocol; AE explicitly briefed; buying committee expansion begins
- Score 90+: Departure Confirmed or Near-Certain — full champion development playbook activated; deal triage decision tree executed

SALESFORCE AUTOMATION SETUP:
- Custom field: "Champion Stability Score" (auto-calculated from signal inputs via Flow)
- Custom field: "Champion Status" (picklist: Healthy / Watch / At Risk / Departed / Replacement Identified / Replacement Active)
- Custom field: "Champion Departure Date" (date field — populated when departure confirmed)
- Custom field: "Replacement Champion Name" and "Replacement Champion Title" (text fields populated by AE or research)
- Flow trigger: When Champion Stability Score reaches 60, create AE task "Verify Champion Status" due within 48 hours; notify Revenue Marketing via Slack
- Flow trigger: When Champion Status = "Departed," create Marketing task "Activate Champion Recovery Playbook" with priority = High; create Slack thread in #deal-defense channel with deal context
- Dashboard: "Champion Risk Tracker" — all pipeline deals and renewal accounts with Stability Score ≥30, sortable by ACV and departure risk level; owned jointly by Revenue Marketing and Sales Leadership

---

### PHASE 2: REPLACEMENT CHAMPION IDENTIFICATION FRAMEWORK

**Rapid Contact Discovery Protocol (execute within 72 hours of departure confirmation):**

STEP 1 — EXISTING CONTACT AUDIT (0-24 hours):
Pull all existing contacts in the Salesforce account record. For each contact, score their "Champion Potential":
- Title similarity to departed champion (same function, adjacent seniority): +30 points
- Prior meeting or call attendance on record (they've already seen your product): +25 points
- Email engagement history with your company (opened emails, clicked content): +20 points
- Known relationship to departed champion (direct report, peer, manager): +15 points
- Active LinkedIn profile with visible engagement on relevant topics: +10 points

STEP 2 — ORGANIZATIONAL RESEARCH (24-48 hours):
If existing contacts score below threshold or are limited in number, AE + marketing ops jointly run:

LINKEDIN SALES NAVIGATOR RESEARCH PROTOCOL:
- Search: [Company Name] + [Function: Revenue Operations / Finance / IT / Operations — matching departed champion's function]
- Filter: "Decision Maker" or "Senior" level; Connected to your company's network within 2 degrees
- Review: Who posted, engaged with, or shared content in the last 30 days — active LinkedIn users are more likely to respond to cold outreach
- Identify: 3-5 candidates who match the champion persona (same title range, same function, ideally appear to report to or work closely with your existing economic buyer contact)

ZOOMINFO / APOLLO ORG CHART PULL:
- Request org chart data for [Company] in the departed champion's department
- Identify: Direct reports of departed champion (they may inherit the project), the champion's manager (could become the new champion or is now the actual economic buyer), or a peer who was already involved in the evaluation peripherally
- Flag: Anyone whose title indicates they are the "backup" for the departed champion's role (VP of RevOps interim, Chief of Staff, etc.)

GONG / CHORUS CALL ARCHIVE REVIEW:
- Pull all recorded calls for this deal. Review transcript for any names mentioned by the champion: "I've been sharing this with [Name]," "My colleague [Name] also looked at this," "Our [Title] has been involved in similar evaluations" — these are warm contacts who already have indirect awareness of your evaluation

REPLACEMENT CHAMPION RANKED SHORTLIST:
Produce a ranked list of 3-5 candidates with the following for each:
1. Full name, title, LinkedIn URL, email (if available)
2. Champion Potential Score (from above framework)
3. Recommended outreach approach: (a) warm re-introduction via existing account contact, (b) direct AE outreach with context, or (c) marketing-led educational outreach before AE contact
4. Key context to personalize first outreach: what do they already know about your product? What is their likely primary concern given their title?
5. Recommended sequencing relative to other candidates: who gets contacted first and why

---

### PHASE 3: CHAMPION DEVELOPMENT PLAYBOOK (30-DAY, 3-PHASE)

Apply distinct versions for three scenarios:

---

**SCENARIO A: ACTIVE PIPELINE DEAL — MID-EVALUATION (Deal Stage 2-3)**

PHASE A1 — STABILIZE (Days 0-7): Prevent deal from going cold while replacement champion is identified

Day 0-2 (72-Hour Stabilization Response):
- If departed champion has a known last day: AE sends a warm, brief personal email: "I heard you're moving on — congratulations on the next chapter. Before your last day, I'd love to set up a brief handoff call so the work you've put into this evaluation isn't lost for your team. Would 20 minutes work this week?" [Goal: get an introduction to the replacement contact directly from the champion]
- If champion departure is unconfirmed (At Risk status): AE sends a personal re-engagement email: "Checking in — noticed we haven't connected in a few weeks. Wanted to make sure everything is going well on your end, and I'm here if there are any updates or changes on your side." [Lower pressure — creates a natural opening for champion to disclose departure or give an alternative contact]
- Marketing activates: LinkedIn retargeting to ALL existing buying committee contacts at the account — serving value reinforcement content (customer outcome stories, ROI proof, solution overview). Goal: ensure awareness is maintained across the buying committee even while champion transition is underway
- Marketing queues: "Relationship Insurance" email to economic buyer contact (if one exists in Salesforce) — a brief check-in from a senior person on your side (VP or executive): "Wanted to personally connect as you move through your evaluation — I'm here as a resource if your team has any questions." Goal: establish a second thread into the account at the economic buyer level

Day 3-7 (Replacement Champion Identified):
- AE makes first contact with the highest-scoring replacement champion candidate (Scenario: warm introduction from departing champion if obtained, OR a personalized cold outreach with full evaluation context)
- Outreach framing: "I wanted to reach out directly — [Departed Champion's Name] was leading an evaluation of [Your Product] for [Company] and I didn't want the work your team has already invested to be lost in the transition. I have a quick 20-minute summary of where things stood and what the next step looked like — would it make sense to connect briefly so you have full context?"
- Marketing deploys: "New Stakeholder Welcome" email to replacement champion from marketing (NOT from AE — different sender, more objective framing): "I wanted to make sure you have everything you need to get up to speed on [Company]'s evaluation — I've put together a brief summary of where things are and the most important materials. Happy to answer any questions." [Include: 2-page evaluation summary document, your top 3 customer proof points for their persona, and a direct calendar link for a 20-minute "catch up" call with the AE]

PHASE A2 — EDUCATE (Days 8-21): Bring replacement champion from 0 to "confident internal advocate" on an accelerated timeline

Day 8-14:
- AE conducts: Rapid-context discovery call with replacement champion — goal is NOT to re-pitch but to understand: (a) how much do they know about the evaluation so far?, (b) what are THEIR personal priorities and concerns?, (c) do they have the authority and motivation to champion this internally? Use MEDDPICC discovery framework adapted for re-entry context
- Marketing deploys: Persona-specific education sequence — 3 emails over 7 days, each addressing a key concern from the replacement champion's title perspective. Example for "VP Finance replacing VP RevOps champion": Email 1 — "The Financial Case for [Product]: ROI framework and payback period your team has already modeled." Email 2 — "How [Product] fits your existing tech stack: what IT reviewed and approved." Email 3 — "What other finance-led evaluations looked like: case study from a peer company in your space."
- Marketing activates: LinkedIn retargeting to replacement champion specifically (matched audience with their email) — serve content specifically relevant to their function and title, not generic brand content
- Provide: "Evaluation Resumption Kit" — a purpose-built 1-page document that summarizes: (a) where the evaluation stood when the previous champion left, (b) what has already been decided and what is still open, (c) the proposed next step, and (d) the 3 most important things for the new champion to know. Frame it as something the AE created for them specifically, not as generic marketing collateral

Day 15-21:
- AE conducts: Second call with replacement champion — this time, focused on their specific concerns (surfaced in Day 8-14 call). Present: any new proof points, a revised business case if needed, and a clear "what happens next" proposal with timeline
- Champion milestone check: Has the replacement champion introduced the AE to any other stakeholders? Are they forwarding content? Are they re-engaging the economic buyer with updates? These are signs that champion development is working
- If yes (champion is developing): Progress to Phase A3
- If no (champion is disengaged or appears unlikely to champion): Execute "Deal Triage Decision Tree" (Phase 4)

PHASE A3 — RE-ANCHOR (Days 22-30): Establish new champion as the active internal driver; rebuild deal momentum toward close

Day 22-28:
- Marketing delivers: "Executive Briefing Package" for the replacement champion to share with their economic buyer — a one-page executive summary that: (a) reframes the evaluation through the lens of their company's specific business goals (not your product features), (b) includes the champion's name as a "prepared by" contributor so they look like the expert, not just forwarding vendor content, (c) recommends specific next steps including timeline to decision
- AE proposes: A joint call with the replacement champion AND the economic buyer — "to make sure [Economic Buyer] has full context on what your team has built together in this evaluation and where the mutual action plan stands." This is the signal that the replacement champion has enough internal credibility to bring their exec into the conversation
- Marketing maintains: LinkedIn retargeting to all buying committee members — serving "final stage" proof content (ROI calculators, implementation timelines, G2/peer reviews), reinforcing confidence across the entire committee as deal approaches re-close

Day 29-30 (Outcome Assessment):
- Assess deal health: Is the replacement champion actively driving toward a decision? Is the economic buyer re-engaged? Has a new close date been proposed? Has the deal progressed in Salesforce stage?
- If healthy: Deal is on track — continue standard pipeline acceleration support
- If stalled: Escalate to executive-to-executive outreach; consider competitive defense protocol if silence suggests competitor is gaining ground; or pause and set a 60-day reactivation cadence

---

**SCENARIO B: ACTIVE PIPELINE DEAL — LATE STAGE (Deal Stage 4-5, pre-close)**

A champion departure at late stage is an emergency, not a standard delay. Different urgency and tactics:

Day 0-3 (EMERGENCY RESPONSE):
- AE immediately notifies CRO or VP Sales — deal must be reviewed at next pipeline call with specific recovery plan
- Marketing activates FULL buying committee outreach simultaneously — not sequentially. Every identified stakeholder in the account receives personalized outreach within 72 hours:
  - Economic buyer: Personal email from AE + executive at your company ("We know [Champion] has transitioned — we wanted to reach out directly to ensure the work your team invested in this evaluation isn't lost")
  - IT/security: Reminder of completed security review and compliance approvals already secured
  - End users: Brief "what happens next" summary — reassurance that the transition doesn't restart the evaluation clock
- AE proposes: Emergency 30-minute "transition briefing" call with anyone still available on the prospect side — goal is to find even one stakeholder who is willing to be the bridge to the replacement champion or the economic buyer

Day 4-14 (Accelerated Champion Development):
- Compress the 30-day playbook into 14 days — less education, more validation
- Replacement champion outreach focuses immediately on: "What would you need to see to feel confident recommending we move forward?" — skip re-education, go directly to objection handling and confidence-building
- Deploy: "Final Decision Package" to replacement champion — everything they need to make a recommendation to the economic buyer without re-running the evaluation: the original evaluation scoring, a reference customer match (peer company who went through the same evaluation), a draft mutual action plan showing exactly what happens between "decision" and "go live"
- Executive play: Your CEO or CRO reaches out directly to the prospect's economic buyer: brief, peer-level note: "I wanted to personally reach out as [Champion] transitions — I'm committed to ensuring this evaluation continues to be a positive experience for your team. Happy to connect at any point."

---

**SCENARIO C: EXISTING CUSTOMER ACCOUNT — CHAMPION DEPARTS BEFORE RENEWAL**

Champion loss in a customer account is primarily a churn risk, not a pipeline risk. Different playbook:

Day 0-3 (Account Stabilization):
- CS team is primary owner — marketing supports
- Marketing activates: Account retargeting across all contacts at the company (not just the departed champion) — serve: expansion ROI content, customer community content, certification content (things that create value independent of who holds the champion role)
- CS: Conducts immediate outreach to all other stakeholders in the account who have any relationship with your company — goal is to find the "shadow champion" who was adjacent to the original champion and now needs to step up
- Check: Is renewal within 90 days? If yes, emergency protocol. If no, steady champion development protocol

Day 4-30 (Replacement Champion Development for Renewal):
- Identify the replacement champion using the same Organizational Research Protocol above — but optimized for existing customer context (ZoomInfo org chart, LinkedIn, CS call records, support ticket history showing other users)
- The first message to a replacement champion at an existing customer is different: "I wanted to reach out as [Departed Champion] transitions — your company has been a customer for [X years] and I want to make sure you have everything you need to feel confident in the value [Product] is delivering and what the next phase of our partnership looks like."
- Deliver: "Value Realized" summary — a personalized document showing the ROI and outcomes already achieved for their company: specific metrics, business impact, usage data translated into business language. This is the most powerful tool for building a new champion who didn't buy the product but now needs to believe in it
- Host: An "executive business review" (EBR) proactively before the renewal window — bring in your CS executive, their new champion (whoever emerges), and ideally their economic buyer. Agenda: what value has been delivered, what the roadmap looks like, and what the renewal offers for the next phase. This turns the replacement champion into a renewed advocate before they even have to make a renewal recommendation

---

### PHASE 4: DEAL TRIAGE DECISION TREE

When replacement champion identification or development isn't yielding results by Day 14, execute the triage framework:

ASSESSMENT QUESTIONS:
1. Is a viable replacement champion identified? (Y/N)
2. Has the replacement champion responded to outreach? (Y/N)
3. Is there an economic buyer contact in Salesforce who is reachable? (Y/N)
4. Is the deal ACV above your "enterprise defense threshold"? (e.g., >$100K) (Y/N)
5. Is the deal within 45 days of projected close? (Y/N)

DECISION PATHS:

All Yes → FULL RECOVERY PROTOCOL: Activate executive-to-executive play, deploy full content arsenal, AE + marketing joint war room until deal resolves

Champion identified but unresponsive + Economic buyer reachable → SKIP-LEVEL PLAY: Bypass champion development; AE reaches directly to economic buyer with a brief, respectful note explaining that they want to ensure continuity and respect the buyer's time — offer an executive peer-to-peer meeting to assess fit for continuing the evaluation

No viable champion + No economic buyer contact → PAUSE PROTOCOL: Stop active sales/marketing investment; set a 60-day "trigger-based" reactivation: if LinkedIn signals show new VP RevOps or relevant hire at the company, auto-trigger a personalized outreach sequence; if 6sense/Bombora shows the account returns to active intent research on your category, trigger an AE re-engagement task

High ACV + No champion + Late stage → ESCALATION: CMO or CRO makes direct contact with the account's CEO or highest available executive — brief, peer-level, transparent: "I know there's been some team transitions — I wanted to personally reach out to make sure the evaluation your team ran is not lost. I'm happy to invest 20 minutes to understand whether this is still a priority for your company."

Low ACV + No viable champion → ARCHIVE WITH REACTIVATION TRIGGER: Close the deal as "Champion Departed — Reopen When New Hire" in Salesforce; set up a ZoomInfo/LinkedIn alert for the company to notify AE when a new contact with the champion-profile title joins

---

### PHASE 5: CHAMPION CONTENT ARSENAL

Six assets that do the heavy lifting of bringing a new champion up to speed without requiring them to restart:

1. **The "Where We Left Off" Summary (per deal):** 2-page personalized document created by AE + marketing ops from the CRM deal record. Contains: (a) original evaluation goals as stated by the previous champion, (b) what your product has already been evaluated against and the outcome of each review, (c) what remains open, and (d) the agreed-upon mutual action plan from where the previous champion left things. This document allows a new stakeholder to say "I have full context" after reading 10 minutes rather than requiring a 3-hour re-pitch. Champion-ready: they can forward this to their own team. [Create: template in your content system populated by CRM fields; AE customizes in <30 minutes per deal]

2. **Persona-Specific Fast-Track Briefing (per champion persona type):** 1-page "What [Title] Needs to Know" document tailored to the most common replacement champion personas (e.g., CFO replacing VP RevOps; CTO replacing Director of Engineering; COO replacing VP Operations). Focuses on: what this product does from their perspective specifically, what the financial case is, what IT/security already reviewed, and what peers in similar roles at similar companies have decided. Not a re-pitch — a peer briefing document that feels like something an informed colleague wrote for them. [Create: 3-5 persona versions; update quarterly]

3. **"Decision Package" for the Economic Buyer (universal):** A 3-page executive summary that the new champion can use to brief their economic buyer without needing to understand the full technical depth of the evaluation. Contains: business problem, your solution's approach in non-technical language, customer ROI proof (specific numbers from relevant case studies), proposed implementation timeline, and recommended next steps. Formatted to be presentable at an executive team meeting. [Create: template + 3-4 industry variants; AE customizes the ROI numbers for the prospect in <20 minutes]

4. **"Evaluation Defense" Competitive Summary (per competitor):** If a competitor has been, or is likely to be, introduced by the replacement champion (who wasn't part of the original evaluation and may have their own vendor preferences), deploy a concise "comparison framework" that shows head-to-head differentiation — framed as an evaluation tool, not vendor marketing. "Here's how we compare on the criteria your team defined during the evaluation." [Reuse from competitive intelligence program; ensure the 3 most common competitors are covered]

5. **Reference Customer Fast-Match:** When a new champion is identified, immediately match them to the closest existing customer advocate — same industry, company size, and champion title. Deploy: a brief intro email from marketing: "I wanted to connect you with [Name] from [Company] — she went through a similar evaluation as [Company]'s VP of RevOps and is happy to share her experience. Would a 20-minute peer call be helpful?" Reference calls are the single most effective accelerant for a new champion who has no prior relationship with your company and needs peer validation to justify championing the deal internally. [Create: a "reference customer index" organized by champion persona + industry + competitor evaluated; maintained by customer marketing]

6. **"What Happens After You Sign" Timeline:** A concrete, visual implementation timeline showing what the onboarding experience looks like — week by week for the first 90 days. New champions often hesitate because they're inheriting a deal they didn't start and fear they'll be blamed if implementation is painful. This asset preemptively addresses that fear. Include: who does what, what your team handles vs. what they handle, how long until first business outcome is visible, and 2-3 testimonial quotes specifically about the implementation experience from customers with similar company sizes. [Create: one universal version + variations by deal size/complexity tier]

---

### PHASE 6: WIN-BACK MEASUREMENT FRAMEWORK

PRIMARY CHAMPION RECOVERY METRICS:

Deal Outcome by Departure Scenario:
- Win rate: deals where champion departed vs. deals where champion stayed through close [Baseline measurement — isolates the impact of champion loss on win rate]
- Win rate: deals where marketing activated champion recovery playbook vs. deals where only sales acted [Core program effectiveness metric]
- Deal outcome by departure timing: champion departed at Stage 2 vs. Stage 3 vs. Stage 4-5 — which stage makes champion loss most survivable? [Guides where to invest most deeply in the playbook]

Champion Development Speed:
- Average days from champion departure detected to replacement champion first response [Target: <10 days]
- Average days from replacement champion first contact to first internal champion action (forwarding content, adding new meeting attendee, scheduling joint call) [Target: <21 days]
- % of replacement champion outreaches that result in at least one response within 14 days [Target: ≥55%]

Revenue Protected:
- Total ACV of deals where champion recovery was activated [Track by quarter]
- Total ACV of deals recovered (reached close stage after champion departure) vs. total ACV lost [The "revenue protected" metric that justifies program investment to the CRO]
- Customer ACV retained in renewal accounts where CS + marketing ran champion development protocol after departure [Churn prevention measurement]

Content Effectiveness:
- "Where We Left Off" document engagement: % of new champions who open, read, and respond after receiving the document [Target: ≥65%]
- Reference customer call arrangement rate: % of replacement champion outreaches where a peer reference call is offered and accepted [Target: ≥40%]
- "Fast-Track Briefing" forwarding rate: % of replacement champions who forward the persona-specific briefing to another internal stakeholder [Proxy for champion development success]

FEEDBACK LOOP:
- Post-close (won): "When did you first feel confident in this decision?" and "What content or touchpoint was most useful during the evaluation restart?" [Identifies which recovery assets actually move champions]
- Post-close (lost, champion-related): "When the evaluation changed hands, what would have helped our team maintain momentum?" [Honest loss analysis; survey sent by neutral third party or CS/post-sale team]
- Quarterly review: Which champion personas develop fastest? Which content assets have highest engagement? Which replacement champion search approaches yield the best candidates? Update playbook and content arsenal based on data

REPORTING CADENCE:
- Weekly: Active champion risk tracker (all deals with Stability Score ≥30, departure confirmations, replacement champion status)
- Monthly: Champion recovery program results — deals saved, deals lost, ACV recovered vs. lost, content engagement rates
- Quarterly: Full program review with CMO, CRO, VP Product Marketing — playbook iteration, content arsenal update, investment justification

## Example Input/Output

**Input Example:**
- Company: Meridian — AI-powered revenue forecasting platform for enterprise RevOps and finance teams
- ICP: VP Revenue Operations, Director of Revenue Ops, CFO at B2B SaaS companies $50M-$500M ARR
- ACV: $85,000 | 5-7 month sales cycle | 6-person buying committee
- Champion who departed: Dana Park, Director of Revenue Operations at Apex Dynamics — had been the primary evaluation driver for 4 months; introduced Meridian to CFO 3 weeks ago and was 30 days from close
- Departure signal: LinkedIn shows Dana now lists a new company; email sent by AE bounced with a "no longer with Apex" auto-reply
- Deal stage: Stage 4 — verbal approval from CFO pending signed MSA
- Existing contacts in Salesforce: CFO (Sarah Chen, met once 3 weeks ago), IT Director (Marcus Webb, completed security review), 1 RevOps Analyst (Jordan Lee, end user in demos)

**Output Example:**

**CHAMPION STABILITY SCORE: 100 (DEPARTURE CONFIRMED — EMERGENCY RESPONSE)**
Signal breakdown: LinkedIn employer change detected (+50), email hard-bounce confirmed (+50)
Deal stage: Stage 4 | ACV: $85,000 | Days to projected close: 28 | Emergency Protocol: Activated

**TRIAGE ASSESSMENT:**
- Viable replacement champion identified: YES — Jordan Lee (RevOps Analyst) is the highest-scoring candidate among existing contacts; their manager title (post-Dana vacancy) makes them the likely interim RevOps lead
- Economic buyer reachable: YES — CFO Sarah Chen is in Salesforce with a direct contact record from the joint call 3 weeks ago
- ACV above enterprise defense threshold ($75K): YES
- Deal within 45 days of projected close: YES
→ DECISION: FULL RECOVERY PROTOCOL — Activate executive play + compressed champion development + full content arsenal

**72-HOUR RESPONSE ACTIVATED:**

Hour 0-4 (today, 3:00 PM):
- AE Outreach to Dana Park (departure-informed, warm): "Dana — heard you're moving on, congrats on the next step. Is there any chance we could connect briefly this week? I'd love to understand who on your team will be taking over the RevOps function at Apex so we can make sure the work you invested in this evaluation isn't lost." [Goal: get a warm introduction to the replacement contact from Dana herself]
- Marketing: LinkedIn retargeting activated for all 3 existing Apex contacts (Sarah Chen, Marcus Webb, Jordan Lee) — serving "CFO-level" ROI content + implementation timeline content across all contacts simultaneously
- AE: Sends "checking-in" email to CFO Sarah Chen: "Hi Sarah — I wanted to reach out personally. I understand there's been a leadership transition at Apex in the RevOps function, and I want to ensure the strong momentum we had coming out of our last conversation isn't disrupted. I'm here to support however is most useful — would a brief 15-minute call make sense this week to discuss next steps?" [Goal: establish a direct thread to the economic buyer, not dependent on champion]

Hour 4-24:
- Marketing deploys "New Stakeholder Welcome" package to Jordan Lee (identified replacement champion candidate): "Hi Jordan — I wanted to make sure you have everything you need as Apex transitions the RevOps evaluation forward. I've put together a brief summary of where the Meridian evaluation stood and the key materials that will help you get up to speed quickly. Happy to answer any questions." [Attach: "Where We Left Off" summary (AE-created in 2 hours from CRM data), Fast-Track Briefing for RevOps Analyst persona, reference customer match: "Meet Kate from similar-sized SaaS company whose RevOps Analyst drove the final evaluation"]
- AE: Sends a separate, brief email to Jordan Lee from AE directly — lighter, more personal: "Hey Jordan — I know things are transitioning at Apex and I wanted to make sure you knew I'm available as a resource. You've been in the demos and know the product well. Happy to connect if you want to discuss where things stand."

Hour 24-48:
- Your VP Sales (Meridian) sends personal email to CFO Sarah Chen: "Sarah — I wanted to reach out personally as you navigate the team transition. I know Dana put significant time into this evaluation and I'm committed to making sure that investment isn't lost. I'm available anytime to connect at whatever level is most useful. If it would help, I can also arrange a brief call with [customer name] — our RevOps VP at [peer company] — who navigated a similar evaluation and can speak to the value from a CFO's perspective." [Executive play — peer reference offer directly to economic buyer]
- Marketing: Delivers "Decision Package for Economic Buyer" to Jordan Lee (with instruction to share with Sarah Chen): "I've put together a 3-page executive summary of the evaluation for you to share with Sarah — it captures everything your team built over the last 4 months and what the recommended next step looks like from a business case perspective. You can forward this as-is." [Designed to make Jordan look capable and prepared to their CFO, accelerating their champion emergence]

Day 7 Outcome Projection:
- Based on Meridian's historical data: Deals where champion departed at Stage 4 but CFO contact existed AND a replacement champion was identified within 72 hours have a 61% win rate — vs. 22% win rate for Stage 4 champion departures without an activation protocol
- Expected value of this recovery program for the $85K Apex deal: +$33,150 in expected ACV vs. no recovery attempt
- Probability of close within 14 days of original target: 41%; within 30 days: 61% if Jordan Lee is engaged by Day 7

## Success Metrics

**Champion Recovery Rate:**
- % of champion-departure deals that resulted in a confirmed replacement champion within 14 days [Target: ≥70% of deals where a viable replacement candidate existed]
- % of champion-departure deals that ultimately closed (won) vs. historical win rate for the same deal stages [Target: ≥25 percentage point improvement vs. unmanaged departures]
- Average days-to-new-champion-engagement after departure confirmed [Target: ≤10 days]

**Pipeline Revenue Protected:**
- Total ACV recovered through champion development program per quarter [Track as a dedicated revenue-protected metric for CMO and CRO reporting]
- Deal outcome distribution: Won / Lost / Paused-Reactivate / Archive — by ACV tier [Guides where to invest most in the playbook]

**Content Performance:**
- "Where We Left Off" summary: % opened + % of recipients who respond or take a next meeting [Target: ≥60% open, ≥35% response rate]
- Reference customer offer acceptance rate: % of replacement champions offered a peer call who accept [Target: ≥40%]
- "Decision Package" forwarding rate: % of replacement champions who forward the economic buyer package to their exec [Target: ≥45%]

**Detection Speed:**
- Average hours from champion departure occurrence to Salesforce alert firing [Target: ≤48 hours using LinkedIn Sales Navigator + ZoomInfo alerts]
- % of champion departures detected by marketing signal (LinkedIn, email bounce) before AE reported manually [Target: ≥60% — marketing detecting before sales tells you is the North Star]

## Related Prompts

- [AI-Powered B2B SaaS Late-Stage Competitive Deal Defense & Rapid-Response Displacement Prevention Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Pipeline-Acceleration/AI-Powered-B2B-SaaS-Late-Stage-Competitive-Deal-Defense-&-Rapid-Response-Displacement-Prevention-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Pre-Meeting Account Intelligence Briefing & Enterprise Deal Context Revenue Intelligence Engine](../../02_Product-Marketing/Sales-Enablement/AI-Powered-B2B-SaaS-Pre-Meeting-Account-Intelligence-Briefing-&-Enterprise-Deal-Context-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS NPS Signal-Driven Customer Advocacy Activation & Promoter-to-Pipeline Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-NPS-Signal-Driven-Customer-Advocacy-Activation-&-Promoter-to-Pipeline-Revenue-Intelligence-Engine.md)
- [Digital Deal Room & Buyer Enablement Content Engine](../../02_Product-Marketing/Sales-Enablement/Digital-Deal-Room-&-Buyer-Enablement-Content-Engine.md)

## Integration Tips

**LinkedIn Sales Navigator + Salesforce:**
- Configure Sales Navigator "Job Change" alerts for every contact flagged as "Champion" role in Salesforce — use the TeamLink or Sales Navigator for Salesforce native integration to push job change alerts directly to Salesforce as activity records, triggering the Champion Stability Score Flow automatically
- Create a dedicated "Champion Watch" saved search in Sales Navigator for all Champion-role contacts across your open pipeline + renewal accounts within 90 days — review this list weekly in your pipeline review meeting as a standing agenda item
- Set up "Relationship Intelligence" alerts for high-ACV accounts: when a Champion-role contact adds a new connection at a competitor, increases LinkedIn activity, or receives a promotion congratulation from outside your network, AE receives a "champion watch" Slack message immediately

**ZoomInfo / Apollo Org Chart Automation:**
- Configure ZoomInfo "Scoops" or "Contact Change" alerts for all Champion-role contacts — these fire when ZoomInfo's data team detects an employer change in their own database (typically 2-4 weeks faster than LinkedIn in some cases, and often catches contacts who don't update LinkedIn immediately)
- Use ZoomInfo's org chart data to pre-populate a "Likely Replacement Champion" field in Salesforce when a Champion departure is confirmed — automated query: "Show me all contacts at [Company] with title matching [champion persona titles] who are NOT already in Salesforce" — gives AE a research head start within minutes

**Gong / Chorus + Salesforce Smart Trackers:**
- Configure Gong Smart Trackers for departure language: "my last day," "I'm leaving," "transitioning to," "you'll be working with [Name]," "no longer going to be at the company," "I've taken a new role" — set sensitivity to medium (catch partial matches)
- When a Smart Tracker fires in a call with a Champion-role contact, auto-create a Salesforce Task for AE: "Champion Departure Language Detected — Verify Status Within 24 Hours" and send a Slack message to the AE's deal defense channel
- Quarterly: Pull Gong call analytics to find the average "last call before deal went dark" — this gives you a behavioral fingerprint of what champion disengagement looks like in call data BEFORE LinkedIn or email signals fire

**Marketo / HubSpot Email Monitoring:**
- Configure email hard-bounce handling to automatically update Salesforce contact record "Email Status" = "Invalid" AND check if that contact has the Champion role in any open opportunity — if yes, trigger the Champion Stability Score Flow with a +50-point signal
- Set up Marketo / HubSpot lead activity monitoring: when a Champion-role contact's email engagement drops to 0 for 21+ days after a period of consistent engagement (>60% open rate for prior 30 days), trigger a "Champion Engagement Gap" alert in Salesforce
- For replacement champion outreach sequences: use Marketo / HubSpot for the marketing-sent version of the "New Stakeholder Welcome" email — track open rates and click-to-action rates separately for each of the 6 content assets in the Champion Content Arsenal to identify which performs best by champion persona

**Slack + Revenue Operations Workflow:**
- Create a #champion-risk Slack channel — all Champion Stability Score alerts (Score ≥30), departure confirmations, and replacement champion identification updates flow here automatically
- AE can post a 🔴/🟡/🟢 reaction to each alert: 🔴 = "confirmed departure, playbook needed," 🟡 = "uncertain, monitoring," 🟢 = "false alarm, champion is still engaged" — this feeds signal quality data back into the detection system for tuning
- Weekly on Fridays: Post the "Champion Risk Summary" to your sales channel — all deals with Stability Score ≥30, sorted by ACV; gives the whole team visibility on where champion risk is concentrated and prompts AEs to proactively check in before a departure becomes confirmed

**6sense / Bombora Intent Data:**
- After a champion departs, monitor the account for changes in intent signals: if account-level buying intent INCREASES after a champion departure, that's a strong signal that the replacement champion is actively researching — it may indicate they were already evaluating alternatives. Fast-track your replacement champion outreach for accounts showing intent surge
- If account-level buying intent DECREASES after a champion departure, that may indicate the evaluation has been paused internally — shift to "Pause Protocol" rather than aggressive recovery and set intent-spike reactivation triggers

## Troubleshooting

**Problem: LinkedIn Sales Navigator job change alerts fire 3-4 weeks after the champion actually left — by the time marketing detects the departure, the deal is already stalled and the AE has lost contact**
Solution: Build a human early-warning layer alongside the automated signals. Add one standing question to your AE's weekly 1:1 template: "Any contacts in your top 10 deals who have mentioned anything about job changes, promotions, or team restructures?" AEs hear hints in calls — "I might be moving teams," "we're reorganizing RevOps" — that never get logged to Salesforce. The automated signals catch the departure; the human check catches the signal 3-6 weeks earlier. Also: configure Gong Smart Trackers for softer departure signals ("exploring other opportunities," "between you and me," "things are uncertain here") — these often precede a confirmed departure by weeks.

**Problem: Replacement champion outreach feels intrusive — new stakeholders who didn't start the evaluation report feeling "handed off" or "cold-called" by a vendor they didn't choose to engage, creating a negative first impression**
Solution: The framing is everything. Never lead with "I know you've taken over [Departed Champion]'s responsibilities" — that makes the replacement feel like a backup. Instead, lead with the VALUE ALREADY CREATED for their company: "Your team has invested 4 months building something here — I'd hate for that work to be lost in the transition. I've put together a brief summary of where things stood." This positions you as helping them protect THEIR company's investment, not continuing your sales process. In the first touch, your job is to be useful to the new stakeholder — not to close them. Suppression rule: never activate 3+ outreaches to the same replacement champion in the first 7 days. One from marketing, one from AE — that's it, and then wait for a response before the next touch.

**Problem: The "Where We Left Off" summary document takes 3+ hours to create per deal — it's becoming a time bottleneck and AEs aren't doing it consistently**
Solution: Build a Salesforce-native generation template. Create a Salesforce Report + Document merge template that auto-populates the "Where We Left Off" summary using existing CRM fields: Opportunity name, current stage, stage history, Contact roles with their engagement dates, last 5 activities (calls + emails), Opportunity notes (free text field that AEs maintain weekly), and the Mutual Action Plan (if you use a custom MAP object). AE reviews and edits the auto-generated draft in <15 minutes rather than creating from scratch. Treat this as a pipeline hygiene issue, not a champion-recovery issue — AEs who maintain CRM discipline create this asset automatically; AEs who don't will always be slow. Pair the champion recovery playbook with a CRM quality audit program: deals with complete contact records and weekly note updates get 87% faster recovery asset creation.

## Version History
- v1.0: Initial creation (auto-generated)
