# AI-Powered B2B SaaS Community-Qualified Lead (CQL) Program Architecture & Community-to-Pipeline Revenue Orchestration Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** b2b, community-marketing, cql, community-led-growth, pipeline-generation, demand-gen, saas, member-engagement, revenue-orchestration, sales-handoff

## Overview
This prompt enables B2B SaaS marketing and community teams to design a fully AI-orchestrated Community-Qualified Lead (CQL) program — transforming community engagement signals into a predictable pipeline channel. Use it when your community has 500+ active members but generates minimal trackable pipeline, when community-to-revenue attribution is a black box for your revenue leadership, or when you want to build a systematic motion that converts engaged community members into qualified sales conversations without manual outreach from community managers.

## Quick Copy-Paste Version

You are a senior B2B SaaS community-led growth strategist with deep expertise in community-qualified leads (CQL), member engagement scoring, and community-to-pipeline orchestration. Design a complete CQL program architecture for my company's community.

My company: [What we do — one sentence]
Community platform: [Circle / Slack / Discord / Bettermode / Khoros / LinkedIn Group / custom]
Community size: [X active members]
Community type: [Customer community / Prospect community / Mixed / Practitioner community]
Monthly new members: [X/month]
Primary community use cases: [e.g., peer support, product feedback, industry networking, learning/certification]
ICP for sales: [Job title, company size, industry]
Average contract value: [ACV $X]
Current community-to-pipeline attribution: [None / Manual / Partial / Strong]
CRM and marketing automation: [HubSpot / Salesforce + Marketo / other]

Design the following CQL program:

1. CQL SCORING MODEL — Define a Community-Qualified Lead scoring framework with 6–8 engagement signals. For each signal: signal name, data source, weight (1–10), intent rationale, and the threshold that moves a member from "engaged" to "CQL." Define two CQL tiers: CQL-1 (warm — enroll in nurture sequence) and CQL-2 (hot — immediate SDR handoff).

2. SIGNAL DETECTION PLAYBOOK — Map the 5 community engagement patterns that most strongly predict purchase intent. For each pattern: what it looks like in the community, how to detect it (automated vs. human observation), and the downstream action that should trigger immediately.

3. CQL NURTURE SEQUENCE — Design a 4-touchpoint sequence that moves a CQL-1 into a sales conversation within 21 days. Include: in-community engagement (DM, mention, event invite), email sequence, and optional SDR personalized outreach. All touchpoints must feel community-native, not sales-y.

4. SDR HANDOFF PROTOCOL — Define the data payload passed to SDR/AE when a CQL-2 is created: engagement history, topics discussed, pain points surfaced, content consumed, and the personal outreach angle that leverages their community identity.

5. COMMUNITY CONTENT PROGRAMMING — Identify 3 high-intent content formats that accelerate CQL generation: event types, post types, or resource types that predictably attract buyers who are actively evaluating solutions.

6. CQL METRICS DASHBOARD — Define 6 KPIs for measuring CQL program health, including: CQL generation rate (% of active members reaching CQL), CQL-to-opportunity rate, community-sourced pipeline as % of total pipeline, average days from join to CQL, and community member LTV vs. non-community customer LTV.

Output as numbered sections with ready-to-use scoring tables, sequence blueprints, and a Notion/Airtable schema for the CQL pipeline tracker.

## Advanced Customizable Version

# ROLE
You are a world-class community-led growth architect with 15+ years building Community-Qualified Lead programs for B2B SaaS companies from $5M to $300M ARR. You have designed CQL programs for practitioner communities, customer communities, and prospect-led communities across HR tech, developer tools, marketing technology, data/analytics, and enterprise software. You deeply understand that the most common community failure is treating community as a brand play with no revenue accountability — and that the solution is building behavioral intelligence infrastructure that translates engagement signals into pipeline without destroying the authentic community experience. Your frameworks draw on Community-Led Growth methodology (Bevy, CMX, Commsor), Salesforce success communities research, and first-principles behavioral psychology applied to B2B buying behavior. You design programs that run autonomously — AI-orchestrated signal detection, automated routing, and human-in-the-loop for only the highest-intent conversations.

# CONTEXT

Community & Company Profile:
- Company Name: [Company name]
- Product/Service: [One-sentence description of core value prop]
- ARR: [$X ARR]
- Average Contract Value: [ACV — self-serve $X / enterprise $X]
- Community Platform: [Circle / Slack / Discord / Bettermode / Khoros / Salesforce Experience Cloud / LinkedIn Group / Discourse / custom]
- Community Name: [Community name]
- Community Type: [Customer-only / Prospect-only / Mixed prospect + customer / Practitioner (industry-wide, not just your customers)]
- Community Mission Statement: [The reason this community exists beyond selling your product]
- Total Members: [X registered members]
- Monthly Active Members (MAU): [X, defined as members who posted/reacted/attended at least once in last 30 days]
- Monthly New Member Joins: [X/month]
- Community Age: [X months/years]
- Primary Member Personas: [Job title(s) most common in community — e.g., "75% Marketing Managers, 15% VPs of Marketing, 10% Founders"]
- Community Health Score (if tracked): [X/100 or "not tracked"]

ICP and Sales Context:
- Ideal Customer Profile: [Job title, company size range, industry, trigger events that predict purchase]
- Minimum Deal Size for SDR Engagement: [$X ACV or X employee count minimum]
- Sales Cycle Length: [X days average]
- Current Primary Pipeline Sources: [e.g., "60% outbound, 25% inbound SEO, 15% events"]
- Community's Current Revenue Contribution: [% of pipeline attributed to community, or "unknown"]

Community Platform Capabilities:
- Member Profile Data Available: [List fields: name, company, job title, email, LinkedIn URL, etc.]
- Activity Tracking Available: [List: post views, post creations, comments, reactions, direct messages, event attendance, content downloads, etc.]
- CRM Integration: [Native sync / Zapier/Make / API / None]
- Email Integration: [Native / external ESP — HubSpot, Marketo, Customer.io, etc.]
- API Access: [Yes / No / Limited]

Current Community-to-Sales Motion:
- How leads are currently passed from community to sales: [Manual / Automated / No process]
- What information SDRs currently receive about community members: [Describe or "nothing"]
- SDR / community manager relationship: [Describe current collaboration or "none"]
- Biggest blocker to community-sourced pipeline: [e.g., "No data connection between community and CRM", "Sales doesn't trust community leads", "No way to identify who's a prospect vs. customer"]

# OBJECTIVE
Design a complete, AI-orchestrated CQL program that:
- Generates a predictable number of CQLs per month from the active member base: [target X CQLs/month]
- Converts community CQLs to opportunities at a target rate: [X%]
- Attributes community-sourced pipeline with enough data quality to satisfy revenue leadership: [$X community-sourced pipeline per quarter]
- Does this without making members feel sold to — all touches must be community-native and value-first
- Runs autonomously except for high-intent CQL-2 handoffs which require SDR judgment

All outputs designed for AI agent orchestration — automated signal detection, CRM enrichment, sequence enrollment, and pipeline reporting without manual community manager review except for flagged exceptions.

# OUTPUT REQUIREMENTS

## SECTION 1: CQL Scoring Model Architecture

Design a multi-dimensional CQL scoring model using engagement signals, behavioral patterns, and firmographic data. The model must run automatically from community platform data piped into CRM without requiring community manager manual scoring.

**ENGAGEMENT SIGNALS (60% of total CQL score):**

Define 6 community engagement events, each with:
- Signal name (as it appears in your community analytics or API)
- Scoring weight (engagement signals sum to 60 points total)
- Trigger logic (e.g., "member posted in product feedback category ≥2 times in 30 days")
- Intent rationale (why does this action predict purchase readiness, not just engagement?)
- Signal decay rule (does the signal lose weight if not reinforced within X days?)

Required engagement signal categories to cover:
1. **High-Intent Content Engagement** — Interactions with content specifically about evaluating solutions, comparing vendors, or implementation (NOT general industry education)
2. **Product-Adjacent Participation** — Questions, comments, or posts where the member reveals their current pain point or the tool/workflow your product replaces
3. **Event Attendance Pattern** — Attendance at product-focused events (demos as workshops, feature deep-dives, customer story sessions) vs. general educational events
4. **Peer Recommendation Seeking** — Posts or DMs asking community peers for vendor recommendations, tool comparisons, or "what does your team use for X" questions
5. **Direct Product Inquiry** — Any direct question about your product's pricing, capabilities, integrations, or implementation — the highest-intent signal in any community
6. **Power Engagement Frequency** — Volume of engagement (posts + comments + reactions) in the last 30 days relative to historical baseline — acceleration in engagement can indicate active research mode

**PROFILE & FIRMOGRAPHIC SIGNALS (25% of total CQL score):**

Define 4 profile enrichment signals:
- Job title / seniority match to ICP (from member profile or Clearbit/Apollo enrichment on company domain)
- Company size (from enrichment data)
- Industry vertical match to your primary ICP industries
- Technology stack signal (if member mentioned their current tools in onboarding survey, posts, or profile)

For each: scoring weight, data source, enrichment timing, and "disqualify" threshold that removes CQL status even if engagement score is high (e.g., "student email domain," "direct competitor employee," "geography outside sales territory").

**BUYING TRIGGER SIGNALS (15% of total CQL score):**

Define 2 external buying trigger signals that, if detected, should immediately escalate any ICP-fit member to CQL-2 regardless of current engagement score:
- Job change alert: member recently changed to a new company OR new role (job change = budget reset = purchase window open). Source: LinkedIn Sales Navigator, Lusha, Clay.
- Company funding event: member's company raised funding in last 90 days (new budget available, rapid hiring = evaluation mode). Source: Crunchbase, PitchBook, or Apollo/Clay funding alerts.

**CQL TIER DEFINITIONS:**

CQL-1 — Warm Prospect (Score: 50–74):
- Profile: ICP-fit member showing engagement patterns suggesting early-stage research or problem awareness. Not yet actively evaluating solutions.
- Recommended Action: Enroll in community-native nurture sequence (see Section 3). No SDR involvement yet.
- CRM Status: Create Contact record → tag "CQL-1" → add to "Community Warm Prospect" nurture list in marketing automation
- Goal: Move CQL-1 to CQL-2 within 30 days through targeted content invitations, event access, and peer introductions
- Expected progression rate: 20–35% of CQL-1s become CQL-2 within 60 days

CQL-2 — Hot Prospect (Score: 75+ OR any buying trigger signal fired):
- Profile: ICP-fit member showing active evaluation signals — asking product-specific questions, comparing vendors, or revealing they have active budget and initiative to solve their problem
- Recommended Action: Immediate SDR handoff with full community intelligence brief (see Section 4). Within 4 business hours of CQL-2 trigger.
- CRM Status: Create Opportunity in CRM → assign SDR → trigger Slack alert to SDR with intelligence brief → log community engagement history as CRM Activities
- Expected opportunity creation rate: 35–55% of CQL-2 handoffs become active opportunities within 30 days

Include: A scoring table in clean markdown format ready to implement in Common Room, Commsor, Orbit, or a custom Zapier/Make integration with your community platform.

## SECTION 2: Signal Detection Infrastructure & Automation Architecture

Design the complete technical architecture for detecting CQL signals without requiring community manager manual review.

**PLATFORM INTEGRATION OPTIONS (choose one based on your stack):**

Option A — Native Community Platform + Zapier/Make:
- Community platform API or webhook sends activity events to Zapier/Make
- Zapier/Make updates a Google Sheet or Airtable "CQL Score Tracker" with member activity
- Google Sheet formula or Airtable automation calculates running CQL score per member
- When score threshold crossed: Zapier creates CRM contact/opportunity + sends Slack notification
- Cost: $0–$100/month for Zapier Pro. Best for communities with <5,000 members.

Option B — Community Intelligence Platform (Common Room, Orbit, Commsor):
- These platforms natively ingest Slack/Discord/Circle/Discourse/GitHub/LinkedIn data
- Pre-built CQL scoring models or custom signal weighting
- Native CRM integrations (HubSpot, Salesforce) for automatic contact creation and score sync
- AI-powered topic classification: automatically tags member posts with intent categories (product question, competitor mention, vendor evaluation, pain point expression)
- Cost: $500–$2,000/month. Best for communities with 1,000+ members where manual tracking breaks down.

Option C — Data Warehouse + Custom Scoring (dbt + Snowflake/BigQuery + Reverse ETL):
- Community platform raw events → data warehouse via API or Fivetran connector
- dbt models calculate rolling CQL score per member across all signal categories
- Reverse ETL (Census, Hightouch) syncs CQL score to CRM custom field nightly
- HubSpot/Salesforce workflows trigger sequences and notifications based on score threshold
- Cost: Engineering investment upfront, then $500–$1,500/month in tooling. Best for data-engineering-resourced teams needing custom scoring logic.

**AI-POWERED SIGNAL ENHANCEMENT:**

Layer these AI capabilities on top of your detection infrastructure:

1. **Topic Classification AI**: Use LLM classification (GPT-4o or Claude API) to automatically categorize every community post and comment into intent tiers: (a) General industry discussion, (b) Problem awareness, (c) Solution research / vendor evaluation, (d) Direct product inquiry. Only categories (c) and (d) trigger CQL scoring events. This eliminates false positives from active community members who are customers or competitors.

2. **Pain Point Extraction AI**: Weekly LLM batch job reads all community posts from the last 7 days and outputs: (a) Top 5 pain points expressed by members this week, (b) Members who expressed specific pain points that map to your product's core use cases (these members are auto-tagged in CRM), (c) Competitor mentions and sentiment. Output delivered as a weekly Slack digest to SDR team and community manager.

3. **Buying Signal Alert AI**: Real-time webhook processing where each new post or comment is scored for buying intent. Posts that contain buying signal language ("we're evaluating X," "looking for alternatives to Y," "does anyone know if Z integrates with," "our budget just got approved for") trigger an immediate Slack alert to the community manager with recommended response: engage authentically in community thread, then flag as CQL-2 for SDR follow-up.

4. **Member Research Mode Detection**: AI analysis of session patterns — member who visits community 3+ times in a single day (research binge), or who visits "customer stories" or "product updates" sections repeatedly, is identified as being in active research mode regardless of whether they post publicly.

## SECTION 3: Community-Native CQL Nurture Sequence Architecture

Design a 4-touchpoint nurture sequence for CQL-1 members that moves them toward sales readiness within 21 days. Every touchpoint must feel like a genuine community benefit, not marketing automation.

**SEQUENCE DESIGN PRINCIPLES:**
- All outreach must reference specific community activity ("I saw your post about X")
- Invitations provide genuine value, not just a request for a conversation
- Sequence pace: maximum 1 touchpoint every 5 days (community members are NOT marketing database contacts — over-communication destroys community trust)
- All emails sent from community manager alias, NEVER from sales
- Sequence pauses automatically if member replies OR if CQL-2 threshold is crossed

**TOUCHPOINT 1 (Day 0–2 — CQL-1 trigger day): Personalized Connection by Community Manager**

Medium: Direct message within community platform
Purpose: Acknowledge recent community participation and provide a genuine resource
Message framework:
- Opening: Reference their specific recent post or comment by name ("Hey [Name], loved your question about [topic] in the [channel] yesterday")
- Value delivery: Share one specific resource (article, template, event, or peer introduction) directly relevant to the topic they raised
- No ask: Zero mention of your product or a meeting. Pure value.
- Length: 3–4 sentences maximum
- Automation note: AI surfaces the CQL-1 alert with recommended message draft. Community manager reviews and personalizes before sending. (5 minutes of human judgment per CQL-1.)

**TOUCHPOINT 2 (Day 5–7): Exclusive Content or Event Invitation**

Medium: Email (from communityteam@yourcompany.com)
Purpose: Invite CQL-1 to a high-value event or give exclusive access to gated content relevant to their expressed pain point

Content options (choose based on their pain point signal):
- Private expert roundtable (10-person, curated, peer-to-peer): "We're hosting a small gathering of [job title]s discussing [their pain point topic]. Based on your experience with [topic they discussed], I thought you'd be a perfect fit. Spots are limited."
- Gated benchmark report: "We just released our [Year] State of [Their Profession] report — community members get early access before public launch."
- Customer story specific to their use case: "Thought you'd find this useful — [Similar Company] was dealing with [their exact pain point] and here's how they approached it." [1-page PDF attached, NOT a sales landing page link]

Subject line options: "[Name], thought of you for this" | "[Exclusive] Early access to [resource] for community members"
CTA: Single — RSVP to event OR download the resource. No meeting request.

**TOUCHPOINT 3 (Day 12–14): Peer Introduction or Community Recognition**

Medium: Community platform (post or DM) + optional email
Purpose: Create a peer connection that elevates the CQL-1's status and deepens community investment

Approaches:
- Peer introduction: "I wanted to connect you with [Customer/Member Name] at [Company] — they solved a similar [problem] last year and have been generous about sharing what worked. [Peer's name], meet [CQL-1 name] — both of you are working through [topic]." (Requires pre-approval from peer being introduced)
- Community spotlight: Invite the CQL-1 to share their expertise in a community post, AMA forum, or as a co-host of a community event. This deepens community investment and surfaces more intent signals.
- Recognition: Acknowledge them as a "community expert" on a topic they have been active on. Recognition deepens community identity and creates positive brand association.

Note: This touchpoint is highest-value when it creates a peer relationship between a CQL-1 and a happy customer at a similar company. The customer peer typically does more authentic selling than any SDR call.

**TOUCHPOINT 4 (Day 18–21): Soft Product Relevance Bridge**

Medium: Email
Purpose: The only touchpoint in the sequence that references your product — done in value-first, peer-proof framing

Message framework:
- Reference their community journey: "You've been an incredible contributor to the [Community Name] community — your [specific post/topic] sparked a great discussion."
- Problem acknowledgment: "I know from your posts that you're thinking about [specific challenge they raised]. A few other community members facing the same challenge have found [your product] helpful — specifically for [use case directly relevant to their posts]."
- Social proof anchor: Mention 1–2 community members (with permission) who are customers and faced the same challenge
- Soft CTA: "If you're ever curious how they're approaching it, I'm happy to set up a peer conversation or give you a quick look at how [your product] handles [their specific use case]. No pressure — but I wanted to make sure you knew the option was there."
- P.S.: Acknowledge they may not be in evaluation mode — "If the timing isn't right, no worries — you're always welcome in the community either way."

**SEQUENCE BRANCH LOGIC:**
- If member replies to ANY touchpoint: Community manager reviews → if low-intent reply, sequence continues → if high-intent reply (asks about product, pricing, or demo), immediately escalates to CQL-2 and SDR takes over
- If member attends Touchpoint 2 event: Triggers immediate score increase → may cross CQL-2 threshold → SDR takes over with event-specific context
- If no engagement after 4 touchpoints: Member enters 60-day quiet period → monitor for future signals but no active outreach

## SECTION 4: CQL-2 SDR Handoff Protocol & Intelligence Brief

Define the complete data payload, routing logic, and outreach protocol for CQL-2 handoffs that convert community intelligence into pipeline.

**CQL-2 ROUTING TRIGGER:**
- Score threshold: 75+ points OR any buying trigger signal fires for any ICP-fit member
- Routing SLA: SDR must review and take action within 4 business hours of CQL-2 alert
- Routing logic: Territory-based — same rules as inbound MQLs, SDR assigned based on company size and geography

**CQL INTELLIGENCE BRIEF (auto-generated, delivered via Slack + CRM record):**

**Community Identity Summary:**
- Member name, job title, company, LinkedIn URL
- Time in community (member since [date])
- Engagement summary: Total posts, comments, events attended (last 90 days)
- Community reputation: Active contributor, lurker who recently became active, or new joiner who immediately showed high intent?
- AI-generated top 3 topic tags from their post history

**Buying Signal Summary:**
- The specific trigger that created CQL-2 status (exact signal fired)
- Verbatim quotes from their highest-intent community posts or comments
- Questions they asked the community that reveal their evaluation criteria
- Competitor mentions: which tools they mentioned by name
- Pain points they explicitly described in their own words

**Personal Research Profile:**
- Content they engaged with (articles read, resources downloaded, customer stories viewed)
- Events attended (with event topics — e.g., "Attended: Product Deep Dive Workshop" = high intent)
- Previous touchpoints from CQL-1 nurture sequence (if applicable) and any responses

**Company Intelligence:**
- Company name, size, industry, HQ location
- Clearbit/Apollo enrichment: tech stack detected, recent news, funding
- Estimated ACV potential based on employee count and plan tier
- Buying trigger context (funding round amount and date, or new role context if job change triggered)

**Recommended Outreach Angle:**
- AI-generated suggested first line of SDR email referencing their community identity: "I saw your post in [Community Name] about [topic] — your point about [specific insight from their post] really resonated..."
- One sentence connecting their expressed pain point to your product's core use case
- Recommended social proof: which customer story or peer reference is most relevant to their situation
- Suggested meeting framing: peer roundtable invite OR product-specific demo OR customer introduction (based on community signals)

**CQL-2 SDR OUTREACH TEMPLATE:**

Subject: Your question about [topic from their community post]

Hi [Name],

I'm [SDR name], part of the [Company] team that runs the [Community Name] community. I noticed your [post/question] about [their specific pain point] — and thought I should reach out directly rather than just responding in the community thread.

[1–2 sentences connecting their stated problem to a specific customer outcome: "We actually had [Customer Company] tackle the exact same challenge last quarter — they [specific measurable outcome]. Happy to share the details."]

I know you're probably not looking for a sales call — but I could set up a 20-minute peer conversation with [customer name] at [customer company] who solved the same problem, or give you a quick look at how [your product] handles [their specific use case]. Either way, I want to make sure you have the information you need.

Would Thursday or Friday work for a quick call?

[SDR Name]
[Title] — [Company] Community Team

P.S. [Reference specific community contribution: "Your post on [topic] last week sparked a great discussion — [specific thing that was valuable about their contribution]."]

**48-HOUR RESPONSE WORKFLOW:**
- Hour 0: SDR receives Slack alert with full CQL intelligence brief. CRM opportunity auto-created.
- Hour 2: SDR reviews brief and personalizes outreach email using provided template + sends
- Hour 24: If no reply, SDR sends LinkedIn connection request (personalized note: "I run the [Community Name] community — wanted to connect here too")
- Hour 48: If no reply, SDR sends 2-sentence follow-up referencing specific product activity and single CTA
- Day 5: If no response, return to community monitoring. Community manager re-engages at natural community opportunity. No further SDR outreach for 30 days.

## SECTION 5: Community Content Programming for CQL Acceleration

Design 3 high-performing community content formats that predictably attract buyers in active evaluation mode and generate CQL signals at higher rates than general community programming.

**FORMAT 1: The Evaluation Workshop (Disguised as Practitioner Education)**

What it is: A live, intimate community event (15–30 attendees) that teaches practitioners how to evaluate and select tools in your category — not "why buy [your product]," but "how to evaluate ANY [category] tool for your team."

Why it works for CQL generation: Only members actively considering purchasing solutions in your category will attend a 1-hour session on vendor evaluation frameworks. Non-buyers have zero motivation to attend. Every attendee is a self-selected, high-intent prospect.

Program structure:
- Opening (10 min): Facilitated discussion — "What evaluation criteria matter most? What has failed in previous evaluations?"
- Content (30 min): Teach a genuine vendor evaluation framework, including criteria where competitors are strong — authenticity is the trust signal
- Customer guest (10 min): Happy customer describes their evaluation process as peer dialogue, not testimonial
- Wrap-up (10 min): Q&A and optional "if you want to see how [your product] stacks up against these criteria, here's how to request a technical review"
- CQL trigger: All attendees auto-elevated to CQL-1 (or CQL-2 if already engaged + ICP-fit)
- Cadence: Monthly or bimonthly

**FORMAT 2: The Peer Comparison Thread (AI-Amplified)**

What it is: A structured community thread format where the community manager seeds a vendor comparison discussion: "Has anyone compared [your category tools]? What were your criteria and results?" — designed to surface members in active evaluation mode.

Why it works: Members in active buying research always participate in comparison threads because they are looking for peer intelligence. Passive members rarely engage with comparison content. Participation = self-identification as an active buyer.

Execution:
- Post once per month in the most relevant channel
- AI agent monitors all replies for explicit buying signals (evaluation criteria mentions, budget references, timeline references, competitor preferences)
- Community manager adds value by tagging relevant customer members to share their experience
- All reply-posters added to CQL scoring pipeline with elevated scores for vendor comparison engagement
- LLM summarizes the thread weekly and surfaces to SDR team: "7 members are evaluating [your category]. Key criteria: [X, Y, Z]. Competitor mentioned most: [Competitor A]. Highest-intent members: [Names with quotes]."

**FORMAT 3: The Customer-Led Use Case Deep Dive**

What it is: Monthly live session where a customer presents how they use your product for a specific workflow, facilitated as peer education — not a testimonial or sales session.

Why it works: Practitioners attend to learn a workflow, not hear a pitch. But the outcome is powerful: attendees see exactly what the product does in a real context, understand the before/after, and ask questions that reveal their own evaluation criteria.

Program structure:
- "Practitioner to Practitioner" framing — customer is presenter, your team is facilitator only
- Topic is use-case specific: "How [Customer] Built Their [Specific Workflow] Using [Your Product]"
- 20 min presentation: customer-owned, authentic (include challenges and workarounds)
- 25 min Q&A: buyers ask specific technical or workflow questions that reveal implementation readiness
- 5 min optional "want to see if this works for your context" — soft product CTA by community manager
- CQL trigger: All attendees auto-elevated to CQL-1. Attendees who ask specific product questions during Q&A immediately flagged as CQL-2.
- AI enhancement: LLM transcribes Q&A and identifies members who asked purchase-intent questions. Outputs within 1 hour: "Post-session CQL alert: 4 members asked high-intent questions. Verbatim questions and recommended follow-up angles attached."

## SECTION 6: CQL Program KPI Dashboard & Revenue Intelligence

Define the 6 core KPIs for CQL program health, plus 3 advanced diagnostic metrics. For each KPI:
- Definition and formula
- Benchmark range
- Reporting cadence
- Leading indicator warning sign
- Revenue impact of 10% improvement

**CORE 6 KPIs:**

KPI 1 — **CQL Generation Rate**
Definition: % of monthly active community members who reach CQL-1 or CQL-2 threshold in a given month
Formula: (New CQLs created in period) / (Monthly Active Members in period) × 100
Benchmark: 3–8% of MAU for a healthy B2B practitioner community
Warning sign: If CQL rate drops below 3%, check new member quality (paid ads attracting wrong ICP?) or scoring model calibration
Revenue impact: Each 1pp improvement = direct pipeline increase at your opportunity creation rate × ACV

KPI 2 — **CQL-to-Opportunity Rate**
Definition: % of CQL-2 handoffs that convert to active pipeline opportunities within 30 days
Formula: (CQL-2s that became Opportunities) / (CQL-2s created) × 100
Benchmark: 30–50% for well-designed community-sourced leads (should significantly outperform cold outbound)
Warning sign: If rate drops below 25%, investigate SDR response time (>4 hours kills connect rate), intelligence brief quality, or scoring model false positives
Revenue impact: Community-sourced leads close at 2–4× the rate of cold outbound (Forrester B2B community research)

KPI 3 — **Community-Sourced Pipeline as % of Total Pipeline**
Definition: ARR value of open pipeline where first touch or significant influence touch came from community engagement
Formula: (ARR of community-influenced open pipeline) / (Total ARR of open pipeline) × 100
Benchmark: Best-in-class programs: 15–30% of total pipeline influenced. Target for Year 1: 5–10%.
Warning sign: If community pipeline % stagnates despite growing CQL volume, investigate attribution model (community may be influencing deals attributed to other channels)
Revenue impact: Programs crossing 20% threshold typically secure dedicated community headcount and budget

KPI 4 — **Average Days to CQL (Member Journey Velocity)**
Definition: Average days from community join to reaching CQL-1 threshold for the first time
Formula: Mean([date_CQL1_reached − date_join]) for all members who become CQLs
Benchmark: <30 days for high-intent joiners (actively evaluating when they joined); 60–90 days for practitioners who join for education and later evaluate
Warning sign: If avg days to CQL is increasing, new member quality may be declining or content programming needs more evaluation-stage topics
Revenue impact: Each 10-day reduction in time-to-CQL accelerates pipeline velocity and improves quarterly community pipeline targets

KPI 5 — **Community Member Customer LTV vs. Non-Community Customer LTV**
Definition: Average customer lifetime value for customers who were active community members before or during purchase vs. customers with no community engagement
Formula: LTV = ACV × (1 / Monthly Churn Rate) calculated separately for each segment
Benchmark: Community members typically show 20–40% higher LTV due to deeper adoption, peer reinforcement, and lower churn (CMX/Bevy research)
Warning sign: If community customer LTV is not meaningfully higher than non-community LTV, investigate whether post-purchase community engagement is actually driving adoption
Revenue impact: Higher LTV justifies community investment as both a pipeline AND a retention program — important for CMO budget defense with CFO

KPI 6 — **CQL Program ROI**
Definition: Revenue generated from community-sourced closed-won deals vs. total cost of community program (headcount + platform + content production)
Formula: (Community-sourced closed-won ARR) / (Total community program cost) × 100 = ROI%
Benchmark: Year 1: ROI may be negative (investment phase). Year 2: 2–5× ROI. Year 3+: 5–10× ROI for well-run programs
Warning sign: If ROI is strongly positive in Year 1, either attribution is overcounting OR program is underinvested — both warrant investigation
Revenue impact: Each $1 of community investment should generate $3–8 of closed-won ARR at program maturity

**ADVANCED DIAGNOSTIC METRICS:**

D1 — **Signal-to-CQL Conversion Rate**: Of all members who fire at least one engagement signal, what % cross the CQL-1 threshold? Low rates indicate signal weighting is miscalibrated or ICP filtering needs tightening.
D2 — **Community Influence in Won Deals**: Of all closed-won deals this quarter, what % included any community touch? Tracks "dark community influence" beyond formal CQL attribution.
D3 — **SDR Community Acceptance Rate**: Of CQL-2 leads passed to SDR, what % were actively worked vs. marked "not a fit"? Consistently low SDR acceptance means scoring model or ICP filtering needs work.

**CQL COMMAND CENTER DASHBOARD (Notion/Airtable Schema):**

Fields for CQL Pipeline Tracker:
- Member Name, Company, Job Title, LinkedIn URL
- CQL Tier (CQL-1 / CQL-2)
- CQL Score (running total, updated automatically)
- Top 3 Signals Triggered (with dates)
- Notable Posts/Comments (2–3 AI-extracted verbatim quotes)
- Sequence Status (T1 Sent / T2 Sent / T3 Sent / T4 Sent / Paused / Escalated to SDR)
- SDR Assigned (for CQL-2)
- Opportunity Created (Yes/No + CRM Opportunity ID)
- Days Since CQL-1 Creation
- Pain Points Expressed (AI-extracted topic tags)
- Competitor Mentions

Views:
- New This Week (all CQL-1 and CQL-2 created in last 7 days)
- Overdue SDR Handoffs (CQL-2 created >4 hours ago without SDR action)
- At Risk of Going Cold (CQL-1 in sequence for >21 days with no progression)
- Won from Community (closed-won opportunities that originated as CQLs — pipeline attribution)

Automations:
- Slack @mention to assigned SDR when CQL-2 created
- Monday morning digest of all CQL-1s in active sequence + status update
- Weekly community-sourced pipeline summary to CMO/VP Marketing

## Example Input/Output

**Input Example:**

Company: Meridian — B2B SaaS for HR Operations and People Analytics at mid-market and enterprise companies. Helps HR teams consolidate employee data across fragmented HRIS, ATS, and payroll systems into a unified people data platform.
ARR: $8.4M, growing 85% YoY
Community: "People Ops Hub" — 2,800 members (HR Managers, HR Directors, VPs of HR, HRBPs) on Circle platform. Mixed prospect and customer community (60% prospects, 40% customers). Monthly active members: 680.
ICP: Companies 200–2,000 employees, HR teams managing 5+ disconnected systems, triggered by M&A, rapid hiring, or failed HR transformation projects
ACV: $48,000/year
Current community → pipeline: Zero formal process. Community manager occasionally mentions promising members to SDR team via Slack, approximately 2 times per month.

**Output Example (CQL Scoring Model Excerpt):**

**Meridian People Ops Hub — CQL Scoring Table**

| Signal | Category | Points | Trigger Logic | Intent Rationale |
|--------|----------|--------|---------------|-----------------|
| Asked community for HR data integration recommendations | Engagement — Peer Recommendation | 20 | Post contains "recommend," "looking for," "alternatives," or "switched from" + HRIS/integration keywords | Direct vendor evaluation signal — buyer in active research mode |
| Posted about HR system fragmentation pain | Engagement — Pain Point | 15 | AI classifier detects frustration with data silos, manual reporting, or mismatched HR systems | Their pain is Meridian's core use case — high correlation with purchase intent |
| Attended Evaluation Workshop | Engagement — Event | 15 | Event attendance logged for "HR Data Stack Evaluation Framework" session | Only active buyers attend vendor evaluation workshops — auto-qualifies for CQL-1 |
| Asked specific question about Meridian | Engagement — Direct Inquiry | 25 | Post mentions Meridian + contains pricing, capabilities, integrations, or implementation question | Highest intent signal — immediate CQL-2 escalation regardless of total score |
| Posted about hiring growth or recent acquisition | Engagement — Trigger | 12 | AI detects "we're scaling," "just went through an acquisition," "hired 150 people last year" | Business trigger = active problem creation = purchase window opening |
| Viewed customer case study 3+ times | Engagement — Content | 8 | Platform analytics show 3+ visits to customer proof content | Repeated return to proof content = active evaluation, not casual browsing |
| Company: 200–2,000 employees in target industries | Firmographic | 15 | Clearbit: size AND (industry = Technology, Healthcare, Financial Services, or Professional Services) | ICP match multiplies conversion probability 3.5× vs. non-ICP |
| Director, VP, or Head of People / HR title | Firmographic | 10 | Job title contains "VP," "Director," "Head of" + function = HR or People | Budget authority + initiative ownership — economic buyer, not just influencer |

CQL-1 Threshold: 50 points → Enroll in community nurture sequence
CQL-2 Threshold: 75+ points OR Direct Inquiry signal fired → Immediate SDR handoff

**CQL-2 Intelligence Brief Example:**

Member: Priya Sharma, VP of People at StackForge Labs (850 employees, B2B SaaS, Series B, recently acquired a 200-person startup)
Community Since: 47 days ago | CQL-2 Score: 82/100 | Triggered: [Date] 2:14pm

**Key Signals:**
Post 3 days ago: "Does anyone have experience consolidating HR data after an acquisition? We just absorbed [Company] and now we have Workday, Rippling, and two different ATS systems. The reporting is a nightmare." [Verbatim — lead with this in SDR outreach]
Attended "HR Data Stack Evaluation Framework" workshop last Tuesday.
Visited HealthScale case study twice in 3 days.
Company raised $45M Series B (Clay alert, 12 days ago).

**Recommended SDR Angle:**
"Priya described Meridian's exact use case in her own words — post-acquisition data consolidation across mismatched HR systems. She is in active pain right now. Reference the acquisition directly. Lead with the HealthScale story (similar company size, same post-M&A HR data situation). Offer a peer conversation with the HealthScale HRBP before any product demo. Do not pitch features — speak to the chaos of post-M&A people data and how quickly teams can get visibility back."

**Suggested First Line:**
"Priya, I caught your post about the Workday/Rippling situation after your acquisition — that exact scenario is something we've helped a few HR teams navigate in the past year."

## Success Metrics

**30-Day CQL Program Launch:**
- CQL scoring model live with at least 5 signals tracking automatically from community platform API or Zapier integration
- CQL-1 nurture sequence set up in marketing automation (4 touchpoints scheduled and tested)
- CRM integration live — CQL records auto-creating in HubSpot or Salesforce when threshold crossed
- SDR team trained on community intelligence brief format and 4-hour CQL-2 response SLA

**90-Day CQL Program Health Targets:**
- CQL generation rate: 3–5% of MAU becoming CQL-1 per month
- CQL-2 handoff volume: 5–15 per month (size-dependent on community ICP density)
- CQL-to-opportunity rate: >30% of CQL-2 handoffs creating active pipeline
- First attributable community-sourced pipeline: $50K–$200K ARR (ACV-dependent)

**6-Month CQL Program Maturity:**
- Community-sourced pipeline = 8–15% of total open pipeline
- Average days to CQL trending downward as content programming optimization compounds
- SDR acceptance rate >80% (SDRs trust and prioritize CQL-2 leads over cold outbound for same territory)
- Ability to defend community program ROI to CFO with closed-won ARR numbers and LTV differential data

## Related Prompts

- [AI-Powered B2B SaaS Community-Led Demand Generation Architecture & Pipeline Revenue Intelligence Engine](./AI-Powered-B2B-SaaS-Community-Led-Demand-Generation-Architecture-&-Pipeline-Revenue-Intelligence-Engine.md) — Strategic architecture for the broader community-led demand gen program this CQL system plugs into
- [AI-Powered B2B SaaS Community Champion & Super-User Program Architecture Revenue Intelligence Engine](./AI-Powered-B2B-SaaS-Community-Champion-&-Super-User-Program-Architecture-Revenue-Intelligence-Engine.md) — Design the champion program that generates peer-selling fuel for CQL nurture sequences
- [AI-Powered B2B Community Qualified Lead CQL Scoring & Sales Handoff Intelligence Engine](../../05_Analytics-&-Performance/Community-Analytics/AI-Powered-B2B-Community-Qualified-Lead-CQL-Scoring-&-Sales-Handoff-Intelligence-Engine.md) — Analytics companion to this prompt for ongoing CQL score calibration and performance measurement
- [AI-Powered ABM SDR Prospecting Playbook & Account-Based Sales Development Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-ABM-SDR-Prospecting-Playbook-&-Account-Based-Sales-Development-Intelligence-Engine.md) — Align your CQL-2 handoff protocol with the broader SDR prospecting motion

## Integration Tips

**Circle / Bettermode → HubSpot via Zapier:**
Create a Zapier multi-step workflow: Circle "New Comment" or "New Post" trigger → send post content to OpenAI (GPT-4o) or Anthropic (Claude) API for intent classification → if classified as "vendor evaluation" or "product inquiry," update HubSpot Contact with signal tag and increment CQL score property → trigger HubSpot workflow when threshold crossed → create CQL-2 opportunity and Slack-notify assigned SDR. Cost: Zapier Teams (~$50/month) + LLM API (~$5–20/month for classification at typical community volume).

**Common Room → Salesforce:**
Common Room natively ingests Circle, Slack, Discord, LinkedIn, and GitHub signals and provides a "Signals" feature that functions as a real-time CQL score. Create custom "Journeys" in Common Room that alert Salesforce (via native integration) when a member crosses CQL-2 tier. Common Room's AI automatically surfaces "buying signals" detected in community posts. Configure Salesforce Lead Assignment Rules to route CQL-2 leads by territory. Common Room integrates with Salesforce in under 2 hours.

**Slack Community → HubSpot:**
Install Orbit + Slack or Common Room + Slack to track message frequency by channel topic. Create a Zapier Slack trigger that fires when a member posts in specific high-intent channels (e.g., "vendor-recommendations," "tools-we-use"). Pipe those posts to an LLM for intent classification → create HubSpot contact with CQL tag and signal note if buyer intent detected. For communities primarily on Slack, this is the fastest path to automated CQL detection without a dedicated community intelligence platform.

**Google Sheet CQL Tracker (zero-budget option):**
For communities with fewer than 500 MAU and no community intelligence platform budget: Create a Google Sheet with columns for each signal category. Update from community platform exports weekly (most platforms offer CSV export of activity data). Use Google Sheets formulas to calculate running CQL scores. Use a "threshold exceeded" column trigger to activate a Zapier action that creates a HubSpot contact and sends a Slack notification. Requires 2–3 hours per week of community manager time but costs $0 beyond Zapier Basic.

**Orbit (open-source option):**
For communities on Slack or GitHub, Orbit is an open-source community management platform with native CRM integrations. Connect Orbit to your platform, assign "Orbit levels" (engagement scores) based on activity, and create Zapier integrations that push high-level ICP-fit members to HubSpot or Salesforce as CQL records. Free up to 1,000 members tracked.

## Troubleshooting

**Problem: SDRs are ignoring CQL-2 leads — they say community leads "aren't real buyers."**
Solution: The root cause is that SDRs don't trust lead quality from community because historically community referrals have been vague. Fix by making the intelligence brief undeniably specific: include verbatim quotes from community posts, exact signal history with dates, and a recommended first line that is clearly more personalized than anything achievable from a cold database. Run a 30-day pilot: have one SDR champion prioritize CQL-2s exclusively and track their connect rate, opportunity rate, and close rate vs. their cold outbound baseline. In the vast majority of cases, community leads outperform cold outbound on every metric. Use that data to convert skeptical SDRs with revenue proof, not community philosophy arguments.

**Problem: CQL scoring is generating too many false positives — high-scoring members who are not actually buyers.**
Solution: The three most common false positive sources are: (1) Existing customers who are active community members (harmless but wastes SDR time — add a "customer" CRM tag that suppresses CQL routing for paid accounts), (2) Active contributors who are practitioners at companies too small for your ICP (add a firmographic disqualifier: if company size < your minimum threshold, suppress CQL regardless of engagement score), (3) Community partners, resellers, or competitor employees (add a "partner" or "competitor" tag that routes to partner team or suppresses entirely). Review your last 20 false positives, find the pattern, and add the appropriate suppression rule.

**Problem: Community members are complaining that SDR outreach felt intrusive or damaged the community experience.**
Solution: Pull the specific outreach that triggered complaints and audit it against the CQL-2 outreach protocol. The most common violations: SDR pitched the product in the first sentence (never acceptable for community-sourced leads), SDR did not reference community context in their message (makes outreach feel like random surveillance), or SDR followed up more than twice after no response (community members deserve a more respectful cadence than cold outbound). Fix: retrain SDRs on the community-native outreach template, add a "community member" tag in CRM that enforces a slower and more human follow-up cadence, and have the community manager audit all CQL-2 outreach for the first 30 days to catch protocol violations before they damage the community's trust in your brand.

## Version History
- v1.0: Initial creation (auto-generated)
