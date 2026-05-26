# AI-Powered B2B SaaS Customer Advisory Board (CAB) Architecture & Executive Advocate Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** customer-advocacy, executive-engagement, b2b, enterprise, retention, product-marketing, revenue-expansion

## Overview
Automates the full lifecycle of a B2B SaaS Customer Advisory Board — from AI-driven candidate identification and recruitment outreach to session facilitation, product feedback loops, and converting CAB members into high-ROI marketing assets. Use this when you need to build or scale an executive advocacy program that drives reference revenue, product roadmap signal, and analyst credibility simultaneously.

## Quick Copy-Paste Version

You are a senior customer marketing strategist building a Customer Advisory Board (CAB) program for a B2B SaaS company.

Company context:
- Product: [Your SaaS product and category]
- Current ARR: [ARR]
- Customer base: [Number] customers, primarily [ICP description]
- CAB goal: [Primary goal: product roadmap input / reference pipeline / analyst credibility / upsell acceleration]

Complete the following CAB architecture in full:

1. CANDIDATE SCORING MODEL
Identify the top 15 CAB candidate criteria from this customer data:
- NPS score ≥ 8, account health green, active users last 30 days
- Company revenue $50M–$500M, 2+ years as customer, 3+ seats/licenses
- Champion title: VP or above, actively posts on LinkedIn about our category
Score each criterion 1–5 and output a weighted scoring rubric (100-point scale).

2. OUTREACH SEQUENCE
Write a 3-touch executive recruitment sequence (email + LinkedIn) for the CAB chair to send to shortlisted candidates. Tone: peer-to-peer, exclusive, outcome-focused. No marketing fluff. Each touch under 150 words.

3. CAB CHARTER
Draft a 1-page CAB charter including: purpose, member commitment (time, NDA, exclusivity), company commitments to members (early access, direct product influence, community), governance structure, term length, and offboarding criteria.

4. SESSION AGENDA TEMPLATE
Build a 90-minute CAB session agenda with: pre-read package outline, icebreaker format, structured product feedback methodology (Jobs-to-be-Done interview format), competitive landscape discussion, roadmap priority voting framework, and next-steps documentation template.

5. ADVOCACY ACTIVATION PIPELINE
Map each CAB member to advocacy assets they can produce: case study, analyst reference, conference speaker, sales reference call, co-authored thought leadership, peer review site content. Include ask scripts for each asset type.

6. REVENUE ATTRIBUTION MODEL
Define how to attribute pipeline and closed revenue influenced by CAB members: reference calls completed, co-marketing content views, analyst mentions from CAB introductions. Build a 6-month tracking template.

Output everything as ready-to-use documents. No placeholders left unfilled where context allows inference.

## Advanced Customizable Version

ROLE: You are a Principal Customer Marketing Architect with 15 years of experience building Customer Advisory Board programs at enterprise B2B SaaS companies ($50M–$500M ARR). You have launched CAB programs at [COMPANY_STAGE] stage companies and understand the political dynamics, executive time constraints, and ROI measurement challenges unique to this program type.

COMPANY CONTEXT:
- Company: [COMPANY_NAME]
- Product category: [CATEGORY] (e.g., "revenue intelligence platform", "AP automation software")
- Current ARR: [ARR] | Target ARR in 12 months: [TARGET_ARR]
- Customer count: [COUNT] | ICP: [ICP_DESCRIPTION]
- Existing advocacy assets: [e.g., "12 case studies, 3 analyst references, no formal CAB"]
- CAB program goals (ranked): [1. product roadmap signal / 2. reference pipeline / 3. category thought leadership]
- CAB program owner: [Role, e.g., "VP Customer Success" or "Head of Customer Marketing"]
- Executive sponsor: [C-suite title who will co-chair]
- Budget: [Annual CAB program budget]
- Launch timeline: [Target first CAB session date]

TASK: Build a complete, operational Customer Advisory Board program that an AI agent can manage end-to-end.

---

MODULE 1: CAB CANDIDATE INTELLIGENCE & SCORING

1A. CANDIDATE IDENTIFICATION QUERY
Write a CRM query logic (in plain English for Salesforce SOQL or HubSpot filter syntax) to pull candidates matching:
- Account health score: ≥ 75/100 (Gainsight) or equivalent green/yellow status
- NPS: Promoter (9–10) from last survey within 6 months
- Product usage: Daily active users last 30 days, feature adoption depth ≥ 3 core modules
- Relationship depth: Executive sponsor mapped in CRM, 2+ QBR/EBR meetings completed
- Company profile: [Target revenue range], [Target industries], [Headcount range]
- Champion seniority: VP, SVP, EVP, C-suite
- Competitive exposure: Account flagged as competitive renewal risk (ideal: these members become defense assets)

1B. SCORING RUBRIC (100-point weighted model)
Build the complete scoring rubric:
| Criterion | Weight | 5 pts | 3 pts | 1 pt |
Include: strategic influence, advocacy willingness signals (LinkedIn activity, G2 reviews, reference calls completed), company profile fit, relationship warmth, and market visibility.

1C. TOP CANDIDATE DOSSIER TEMPLATE
For each shortlisted candidate, auto-generate a 1-page dossier including:
- Executive bio synthesis (LinkedIn + company website)
- Recent public statements about [CATEGORY] pain points
- Account health snapshot (ARR, renewal date, health score trend)
- Existing advocacy history (references given, content produced)
- Personalization hook for outreach (recent company milestone, LinkedIn post topic, mutual connection)
- Recommended ask tier (Tier 1: Full CAB Member | Tier 2: Advisory Contributor | Tier 3: Reference + Content Only)

---

MODULE 2: EXECUTIVE RECRUITMENT CAMPAIGN

2A. MULTI-CHANNEL OUTREACH SEQUENCE
Build a 4-touch recruitment sequence for each channel:

TOUCH 1 — Direct CEO/CRO/CSO warm email (Day 0)
- From: [Company CEO or CAB Executive Sponsor]
- Subject: personalized to their recent LinkedIn post or company news
- Body: 3 paragraphs — peer recognition, exclusive community framing, specific ask
- CTA: 15-minute discovery call, not a "yes" commitment

TOUCH 2 — CAB Program Owner LinkedIn DM (Day 5)
- Reference the email, add social proof (name-drop 2 existing CAB members from similar companies)
- Include one specific product roadmap area where their expertise is needed
- CTA: Link to CAB landing page or one-pager

TOUCH 3 — Personalized video message (Day 10, Loom/Vidyard format)
- Script: 90 seconds, screen-share the CAB charter document
- Highlight: their specific domain expertise mapped to upcoming roadmap decisions
- CTA: Calendar link for discovery call

TOUCH 4 — Executive sponsor direct outreach (Day 18, if no response)
- C-suite to C-suite outreach
- Subject line formula: "[Mutual contact] suggested I reach out about [Company]'s strategic input"
- CTA: Hard stop — yes or no, no pressure

2B. DISCOVERY CALL SCRIPT
Build a 30-minute discovery call script with:
- Opening: Why them specifically (3 tailored points per persona)
- Program overview: Time commitment, exclusivity, benefits breakdown
- Reciprocity stack: What they get (early access, direct engineering access, industry peer network, speaking opportunities, [COMPANY_NAME] executive relationship)
- Objection handling matrix: "Too busy" / "I'd need to check with legal" / "We already do advisory boards for other vendors" / "What's in it for me beyond being asked questions"
- Commitment close: Soft commitment to next step (charter review), not full join

---

MODULE 3: CAB GOVERNANCE ARCHITECTURE

3A. CAB CHARTER (Full Document)
Draft the complete charter including:
- Mission statement: One sentence connecting CAB purpose to industry advancement (not just company benefit)
- Membership criteria: Quantitative thresholds (seniority, company size, tenure, health)
- Member commitments: 4 sessions/year (2 virtual, 2 in-person at flagship event), 2 hours pre-read per session, NDA scope, exclusivity clause (cannot simultaneously serve on direct competitor advisory board)
- Company commitments: Quarterly product roadmap briefings 90 days before public announcement, named credit in product changelog, dedicated Slack/community channel with engineering leadership, annual CAB Summit (company-hosted, travel covered), personalized year-in-review impact report showing their specific product suggestions that shipped
- Governance: Chair election process, voting methodology for roadmap priority (dot voting vs. ranked choice), quorum requirements
- Term: 2-year term, renewable once; offboarding trigger criteria (health score drops, company acquisition, role change, advocacy opt-out)
- Legal: NDA template outline, IP ownership of feedback, PR/reference usage rights

3B. MEMBER ONBOARDING SEQUENCE
7-day onboarding automation:
- Day 0: Welcome package delivery (physical kit if budget allows: [Company] branded notebook, CAB member badge/certificate, first session pre-read)
- Day 1: Slack community invitation + dedicated onboarding channel
- Day 2: 1:1 intro call with CAB Program Owner (30 min) — relationship mapping, advocacy preferences, preferred communication style
- Day 3: Engineering/Product introduction email from CPO
- Day 7: First discussion prompt posted to CAB community channel

---

MODULE 4: SESSION DESIGN & FACILITATION SYSTEM

4A. SESSION AGENDA TEMPLATE (90-minute virtual / 3-hour in-person)
Structure each session for maximum executive engagement:

PRE-SESSION (2 weeks before):
- Pre-read package: [Product update summary, competitive landscape brief (2 pages), 3 discussion questions requiring their expertise, session goals document]
- Async poll: Rank top 3 agenda topics using Typeform/Mentimeter
- Personalized AI-generated session brief: "Based on your company's [industry/use case], here are the 2 discussion threads most relevant to your priorities"

SESSION FLOW:
- 0:00–0:10 — Executive sponsor opens with business context (not product pitch): "What's keeping our customers up at night in [industry] this quarter"
- 0:10–0:25 — Structured round-table: Each member shares one priority initiative at their company using the "Challenge / Approach / Desired Outcome" framework (timed, 2 min each)
- 0:25–0:55 — Focused product discussion: Jobs-to-be-Done interview format with 3 pre-selected scenarios. Facilitator asks: "When you're trying to [job to be done], what's the #1 obstacle that makes this hard?" NOT "What features do you want?"
- 0:55–1:10 — Roadmap priority voting: Present 5 upcoming initiatives, members allocate 10 points across them using real-time voting tool. Capture verbatim rationale for top 2 choices.
- 1:10–1:20 — Competitive landscape intelligence: Facilitator shares anonymized competitive deal data, asks "Where are you seeing [competitor] messaging land or fail with your peers?"
- 1:20–1:30 — Peer networking + next-steps: Open networking, action items documented live, preview next session topic for continued engagement

POST-SESSION (within 48 hours):
- Session summary sent to all members: verbatim quotes (attributed with permission), decisions made, product commitments with timeline
- Individual follow-up: Personalized note from CAB Program Owner referencing each member's specific contribution
- Product team debrief: Structured handoff document mapping member feedback to specific engineering tickets

4B. FEEDBACK SYNTHESIS SYSTEM
Build the AI prompt chain to process raw session notes into:
- Executive summary for CPO/CRO (1 page)
- Prioritized product backlog additions (with supporting member quotes)
- Competitive intelligence brief for sales team
- Customer marketing content angles (themes that resonate = content that converts)
- Individual member impact report (what did their input influence)

---

MODULE 5: ADVOCACY ACTIVATION & REVENUE ENGINE

5A. ADVOCACY LADDER FRAMEWORK
Map CAB members across 5 advocacy tiers:

TIER 1 — Reference Assets (immediate, low commitment)
- Sales reference calls: 30-min call with active prospect in same industry/use case
- Peer review site content: Guided G2/Gartner Peer Insights review (AI-drafts based on their session contributions, they edit/approve)
- Quote library: Approved quotes for website, press releases, analyst submissions

TIER 2 — Content Co-Creation (medium commitment, high ROI)
- Written co-authored thought leadership: AI drafts 800-word article based on their session comments, they edit, published under their byline + your brand
- Podcast guest: 30-min recorded conversation on industry trend (repurposed to blog, LinkedIn, email)
- Customer story/case study: AI-generated first draft from success data + session quotes, approved by their comms team

TIER 3 — Live Validation (higher commitment, highest conversion impact)
- Webinar panelist: 45-min panel discussion, AI generates talking points tailored to their expertise
- Conference speaker support: Submit them for speaking at your user conference or industry events, provide speech writer assistance
- Sales process participation: Join late-stage enterprise deals as executive reference (video call, LinkedIn introduction)

TIER 4 — Market Authority (maximum commitment, category-building)
- Analyst introduction: Warm intro to Gartner/Forrester analysts for inquiry calls (positions them as thought leader, positions you as vendor with sophisticated customer base)
- Co-authored research report: Original research using your platform data + their strategic commentary
- Advisory attribution: Public recognition as "Strategic Advisor" in company materials (with their approval)

TIER 5 — Revenue Partner
- Referral partner: Formal referral agreement with [%] commission or service credits for closed deals
- Partner ecosystem: Explore joint go-to-market if their company sells complementary products

5B. ADVOCACY ASK SCRIPTS
For each tier, write the exact ask script (email or verbal):
- Subject line/opener
- Value framing: "Here's what you get from this"
- Specific ask with clear scope: "This would take X minutes/hours over Y weeks"
- Approval/legal pathway: How to get their comms team to approve without a 3-month review cycle
- Fallback: If they decline, what's the next-tier ask

5C. CONTENT PRODUCTION AUTOMATION
Build the AI workflow for each advocacy content type:
1. AI ingests: CAB session transcript + member's LinkedIn posts + company news + product usage data
2. AI outputs: First draft of case study / thought leadership / podcast questions / webinar talking points
3. Member review: Streamlined 2-round edit process with tracked changes
4. Approval: One-click approval workflow with legal review checklist
5. Distribution: Multi-channel publishing calendar with member's name, company, and social promotion plan

---

MODULE 6: REVENUE ATTRIBUTION & PROGRAM ROI

6A. ATTRIBUTION MODEL
Define influenced revenue tracking:
- Direct: Deals where a CAB member participated in a reference call, and deal closed within 90 days (track in Salesforce with custom field "CAB Reference Influence")
- Assisted: Deals where CAB member content (case study, quote, webinar) appeared in the buyer's journey (track via UTM + intent data)
- Network: Pipeline sourced from CAB member referrals or warm introductions
- Analyst: ARR influenced by analyst reports where CAB member served as reference customer

6B. PROGRAM ROI DASHBOARD
Build the monthly CAB program scorecard:

HEALTH METRICS:
- Member engagement rate: % who attended last session / responded to async polls
- Net Promoter Score of CAB members themselves (meta-NPS)
- Content production velocity: Assets produced per quarter per member
- Churn risk of CAB members: Are the very accounts you're protecting still healthy?

REVENUE METRICS:
- Reference calls completed: # per quarter, close rate of influenced deals
- Pipeline influenced (direct + assisted): $ value, attributed by member
- Upsell/expansion ARR in CAB accounts: Hypothesis — CAB members expand faster due to deeper product relationship
- CAB member logo retention rate vs. non-CAB customer retention rate (control group)

MARKET METRICS:
- Analyst mentions sourced from CAB introductions
- Share of voice: Media mentions featuring CAB member quotes
- Competitive win rate in deals where CAB reference participated vs. no reference

6C. QUARTERLY BUSINESS REVIEW FOR CAB PROGRAM
Template for presenting CAB ROI to executive team:
- Investment: Program cost (events, gifts, staff time, content production)
- Return: Pipeline influenced + retention premium + analyst credibility + product velocity (features shipped from CAB input)
- ROI formula: (Pipeline influenced × close rate × ACV) + (CAB account retention premium × ARR at risk) / total program cost

---

MODULE 7: AUTOMATION & TOOLING ARCHITECTURE

7A. TECH STACK CONFIGURATION
Configure the following tools for fully automated CAB operations:

CRM (Salesforce/HubSpot):
- Custom object: "CAB Member" with fields: tier, advocacy preferences, commitments fulfilled, last engagement date, content produced, reference calls completed
- Automated health alerts: Flag CAB members whose account health drops below 70 for immediate CSM intervention
- Pipeline attribution: Custom field "CAB Influenced" on opportunity records

Customer Success Platform (Gainsight/ChurnZero/Totango):
- CAB member segment: Auto-segment for specialized playbook (no standard churn plays for CAB accounts — escalate directly to VP CS)
- Usage correlation: Track if CAB members' product adoption increases after sessions (hypothesis: engagement drives usage)

Community Platform (Slack/Higher Logic/Gainsight PX):
- Dedicated CAB workspace or channel with role-based access
- Automated monthly discussion prompts (AI-generated based on upcoming product releases and industry news)
- Member recognition: Auto-post when a CAB member's suggestion ships in a product update

Content Management (Notion/Confluence):
- CAB knowledge base: Session recordings (with AI-generated transcripts and summaries), member dossiers, charter, advocacy assets
- Advocacy asset library: Searchable by industry, use case, persona, asset type for sales team access

Reference Management (ReferenceEdge/Orca/Influitive):
- Centralized reference request routing: Sales reps request references through tool, AI matches to best-fit CAB member based on prospect profile
- Reference fatigue tracking: Auto-flag CAB members who have completed 3+ reference calls in 90 days for a "thank you and rest" period

7B. AUTOMATED WORKFLOW TRIGGERS
Build n8n/Zapier/Make automation flows:
- TRIGGER: New CAB session completed → AUTO-GENERATE: Session summary, action item list, individual follow-up emails, product team debrief
- TRIGGER: CAB member's company announces funding/acquisition/executive change → AUTO-ALERT: CSM + CAB Program Owner with talking points and next-step recommendation
- TRIGGER: Sales rep submits reference request → AUTO-MATCH: Best CAB member based on prospect industry/size/use case, route request with prep materials
- TRIGGER: CAB member NPS drops below 8 → AUTO-ESCALATE: Executive sponsor + CSM with context and suggested intervention script
- TRIGGER: Product feature requested by CAB ships → AUTO-NOTIFY: Member with personalized "your idea shipped" message and request for updated case study quote

---

## Example Input/Output

**Input:**
Company: NorthernEdge Analytics — B2B SaaS, revenue intelligence platform for community banks and credit unions
ARR: $18M | 240 customers | ICP: Community banks $500M–$5B assets, credit unions $200M–$2B assets
CAB goal priority: 1. Product roadmap signal for AI-driven loan portfolio risk features; 2. Reference pipeline for enterprise deals; 3. Regulatory credibility (FFIEC, CECL compliance messaging)
Budget: $85,000/year | Launch: CAB inaugural session in 11 weeks
Existing assets: 8 case studies, 0 formal advisory board, 14 G2 reviews
CAB Program Owner: Head of Customer Marketing (Sarah Chen)
Executive Sponsor: CEO (David Park)

**Output excerpt — CAB Candidate Dossier:**
CANDIDATE PROFILE: Jennifer Walsh, EVP Chief Risk Officer
Organization: Lakeside Community Bank ($2.1B assets, Milwaukee WI)
NorthernEdge Account Health: 94/100 | NPS: 10 | ARR: $127,000 | Renewal: March 2027

ADVOCACY SIGNALS:
- Published 4 LinkedIn articles in past 6 months on CECL implementation challenges (avg 340 engagements)
- Spoke at ICBA Annual Convention 2025 on AI risk modeling — 200+ attendee session
- Completed 2 reference calls for NorthernEdge (Enterprise Bank of Iowa deal, closed $89K; Pioneer Credit Union deal, in final stages)
- G2 review published March 2025: "Changed how our credit committee thinks about portfolio concentration risk"

PERSONALIZATION HOOK FOR OUTREACH:
Jennifer's January LinkedIn post on Basel III endgame concerns for community banks aligns precisely with NorthernEdge's upcoming liquidity stress-testing feature (Q3 release). Reference this specifically — she is already thinking about exactly what we're building.

ADVOCACY TIER RECOMMENDATION: Tier 1 (Full CAB Member)
BEST ADVOCACY ASSETS SHE CAN PRODUCE:
1. Speaking slot at NorthernEdge FinConnect Summit (she's an established speaker)
2. Co-authored white paper: "AI-Driven Risk Modeling for the Community Bank C-Suite"
3. Gartner analyst reference (she's credible, regulatory-fluent, C-suite)
4. Sales reference for 3 enterprise prospects currently in final stages with similar CECL use cases

OUTREACH APPROACH: CEO David Park → EVP Jennifer Walsh direct (peer-to-peer). Reference her ICBA session. Ask for her perspective on how AI will reshape FFIEC examination expectations — frame CAB as industry thought leadership, not vendor advisory.

CANDIDATE SCORE: 91/100

**Output excerpt — JTBD-Structured Session Discussion:**
SESSION 3 DISCUSSION GUIDE: "When AI Risk Models Meet Regulatory Examiners"

Pre-framing (facilitator, 60 seconds):
"We're going to explore a specific job you're all hired to do: convincing your examiner that your AI-assisted risk models are sound. Not feature requests for NorthernEdge — what's the actual job, and where does the current workflow break down?"

JTBD Interview Questions (2 minutes each, all members respond):
1. "Walk me through the last FFIEC examination prep cycle where you used model documentation. What was the most time-consuming step that felt completely manual?"
2. "When an examiner questions a model output — say, an unexpected loan concentration flag — what's the first thing you reach for to explain it? What's missing from that process?"
3. "Imagine you're onboarding a new Chief Examiner who has never seen AI-assisted risk tools before. What's the one thing you'd want them to understand that you can't explain with current documentation?"

INSIGHT CAPTURE PROTOCOL:
- Recorder tags each response: [PAIN_POINT] [WORKAROUND] [UNMET_JOB] [COMPETITIVE_MENTION]
- After all responses: "Does anyone see a pattern here that surprises you? What are we NOT saying?"
- Product team observing async — no speaking, only note-taking

## Success Metrics

**Program Health (Monthly):**
- CAB member attendance rate: ≥ 80% per session (best-in-class programs hit 90%+)
- Advocacy fulfillment rate: ≥ 60% of members produce ≥ 1 advocacy asset per quarter
- Member retention: ≤ 10% voluntary exits per year (involuntary = account churn or role change)

**Revenue Impact (Quarterly):**
- CAB-influenced pipeline: Target ≥ 15% of new ARR touches a CAB member reference or content asset
- Reference call close rate lift: Deals with CAB reference close should close ≥ 15% faster or at higher ACV than non-reference deals
- CAB account expansion rate: CAB members should expand at 1.2–1.5× the rate of comparable non-CAB accounts

**Product Value (Per Release Cycle):**
- % of shipped features traceable to CAB feedback: Target ≥ 25% of quarterly releases influenced by explicit CAB input
- Time from CAB session to engineering ticket: ≤ 2 weeks for high-priority feedback

**Market Authority:**
- Analyst citations sourced from CAB introductions: ≥ 2 per year
- Conference speaking slots landed by CAB members: ≥ 4 per year

## Related Prompts

- `../../06_Customer-Success-&-Retention/Customer-Advocacy-&-Referral/Customer-Reference-Program-&-Peer-Validation-Intelligence-Engine.md`
- `../../06_Customer-Success-&-Retention/Customer-Advocacy-&-Referral/AI-Powered-CS-Sourced-Pipeline-&-Warm-Introduction-Revenue-Intelligence-Engine.md`
- `../../06_Customer-Success-&-Retention/Customer-Success-Automation/AI-Powered-B2B-SaaS-Executive-Sponsor-Program-Architecture-&-CXO-Relationship-Revenue-Intelligence-Engine.md`
- `../../02_Product-Marketing/Customer-&-Market-Research/AI-Powered-B2B-SaaS-Voice-of-Customer-Program-Architecture-&-Continuous-Buyer-Intelligence-Engine.md`

## Integration Tips

**Salesforce:**
- Create custom "CAB Member" object linked to Contact and Account records
- Build a "CAB Reference Request" flow: Sales rep fills form → Salesforce auto-queries CAB members matching prospect's industry/size/use case → routes request to CAB Program Owner with prep materials and member availability
- Report: "CAB Influenced Pipeline" — filter opportunities where "CAB Reference" field is populated, track to close

**Gainsight:**
- Create CAB member segment in Gainsight CTAs: flag for specialized handling (no auto-churn plays; escalate any health dip to VP CS within 24 hours)
- Configure Milestone tracking: "CAB Member Since [Date]" as a relationship milestone, auto-generate annual impact summary
- Timeline entries: Log every advocacy action (reference call completed, content approved, session attended) for CS visibility

**Notion/Confluence:**
- CAB Knowledge Base template: Member roster (with dossiers), session archive (recordings + AI-generated summaries), advocacy asset library, product feedback tracker (linked to Jira/Linear)
- Advocacy Asset Library: Searchable database with filters for industry, company size, use case, asset type — shared with sales team in Slack via daily digest of newly available references

**Zoom + Chorus.ai/Gong:**
- Record all CAB sessions; configure Gong/Chorus to auto-generate transcript and flag: [PAIN_POINT], [FEATURE_REQUEST], [COMPETITIVE_MENTION], [ADVOCACY_SIGNAL]
- Post-session AI summary delivered to CPO and CSM team Slack channel within 2 hours of session end

**Influitive or ReferenceEdge:**
- Automate reference matching: When sales submits request, tool auto-ranks CAB members by match score (industry, use case, deal size proximity) and tracks reference fatigue (max 3 calls per member per 90 days)
- Gamification: Track "advocacy points" per member; top advocates get VIP treatment at annual summit

**Zapier/Make Automation:**
- Monitor CAB members' LinkedIn posts → flag posts about [your category] to CAB Program Owner for comment/share within 2 hours (relationship warmth signal)
- When a product feature ships that matches a CAB member's logged feedback → trigger personalized "your idea shipped" email from CPO with request to update G2 review

## Troubleshooting

**Problem: CAB members attend sessions but produce zero advocacy assets**
Fix: The ask is too vague and the process is too heavy. Switch to "micro-advocacy" — identify the single lowest-friction asset each member can produce (usually a revised G2 review or a 2-sentence updated quote). Build a self-serve portal where members can preview, edit, and approve their own AI-generated draft in under 10 minutes. Add a quarterly recognition program that publicly celebrates members who contributed assets — social proof within the CAB community drives others to participate.

**Problem: Executive sponsors deprioritize CAB program when pipeline pressure increases**
Fix: Reframe the CAB as a revenue defense tool, not a product research program. Send the executive sponsor a monthly "CAB Revenue Report" showing: reference calls completed, pipeline influenced, specific deals where a CAB member accelerated close. Make the ROI undeniable in the same language used for sales forecasting. If a CAB member's reference call helped close a $200K deal, that belongs in the weekly revenue review.

**Problem: Product team ignores CAB feedback and members disengage after 2 sessions**
Fix: The credibility of your CAB collapses if members see their input disappear into a black hole. Implement a mandatory "CAB Feedback Disposition" step in the product sprint planning process — every piece of CAB feedback gets one of four statuses: "Shipped in [version]", "On roadmap for [quarter]", "Declined — here's why", "Under investigation". Share this disposition report with all CAB members within 30 days of each session. Even a "declined" response with honest reasoning builds more trust than silence.

## Version History
- v1.0: Initial creation (auto-generated)
