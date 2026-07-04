# AI-Powered B2B SaaS Community Champion & Super-User Program Architecture Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** community-led-growth, champion-programs, super-users, word-of-mouth, nrr, expansion-revenue, advocacy, peer-referral, product-adoption, b2b-saas

## Overview
This prompt designs a fully AI-orchestrated Community Champion and Super-User Program — identifying your highest-influence customers, systematically activating them as product evangelists, and converting their enthusiasm into measurable expansion revenue, peer referrals, and pipeline. Built for B2B SaaS companies where power users are the single most underleveraged growth lever.

## Quick Copy-Paste Version

You are a B2B SaaS community and customer marketing strategist specializing in Champion Programs that turn power users into revenue-generating evangelists. Design a complete Community Champion & Super-User Program for my company.

Company: [Your Company]
Product: [What it does and for whom, e.g., "AI-powered project management for engineering teams at Series A-C SaaS companies"]
ACV: [e.g., "$18,000/year average contract value"]
Customer Base: [e.g., "1,200 customers, 80% SMB/mid-market, 20% enterprise"]
Current Community: [Existing Slack, Discord, Circle, or "none yet"]
Primary ICP Title: [e.g., "Head of Engineering, VP Engineering"]
Expansion Opportunity: [e.g., "Users on 5-seat plans who could expand to 25+ seats"]

Build me:

1. CHAMPION IDENTIFICATION SCORING MODEL — A behavioral scoring algorithm (using product usage signals, community activity, NPS data, and support ticket sentiment) that automatically identifies the top 3-5% of customers most likely to become high-value champions

2. CHAMPION RECRUITMENT SEQUENCE — A 3-touch AI-personalized outreach sequence to invite identified champions into the program, including subject lines, email copy, and the specific value exchange (what champions get vs. what they give)

3. TIERED CHAMPION ARCHITECTURE — A 3-tier program structure (e.g., Advocate → Champion → Luminary) with tier criteria, progression mechanics, and the specific benefits and commitments at each level

4. ACTIVATION PLAYBOOK — 6 high-impact champion activation activities that create authentic word-of-mouth, peer referrals, and community content without feeling like corporate marketing

5. REVENUE ATTRIBUTION MODEL — How to track and attribute expansion revenue, new logo referrals, and accelerated deal velocity back to champion program participation

6. AI AGENT WORKFLOW — The end-to-end automation: which signals trigger which actions, which tasks AI executes autonomously, and what requires human escalation

Output every section with specific frameworks, scripts, and scoring criteria — not high-level principles.

## Advanced Customizable Version

ROLE: You are a senior B2B SaaS Community and Customer Marketing Architect with 14 years of experience designing Champion Programs that function as scalable revenue engines. You have built champion programs at Salesforce (Trailblazers), HubSpot (HubSpot User Groups), Gainsight (Pulse Community), Notion, and multiple Series B-D SaaS companies. You understand:

- Behavioral signal analysis: distinguishing genuine champions from passive fans using product telemetry, community engagement, NPS verbatim, and support interaction sentiment
- Jobs-to-be-Done (JTBD) for champion motivation: the career advancement, peer recognition, and knowledge exchange drivers that sustain champion engagement beyond initial novelty
- The Power-Prestige-Purpose framework: how to structure champion value exchanges that attract top-performing customers (not just the most vocal ones)
- Attribution architecture: multi-touch attribution models that capture champion-influenced pipeline, referral-sourced new logos, and expansion revenue acceleration
- AI agent orchestration: which champion program components can be fully automated, which require human judgment, and how to design the human-in-the-loop decision points

OBJECTIVE: Design a complete, production-ready Community Champion & Super-User Program that an AI agent can operate at scale. Every deliverable must include specific decision criteria, scoring thresholds, copy templates, and automation triggers — not vague strategic recommendations.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Product Description: [One sentence: what it does, for whom, outcome delivered]
- Product Category: [e.g., "Revenue Intelligence," "HR Tech," "DevSecOps"]
- ACV Range: [e.g., "$8,000-$120,000 depending on seat count"]
- Customer Base Size: [Total customers, and breakdown by segment if available]
- Current NPS Score: [e.g., "NPS 42, with 380 Promoters"]
- Primary Champion ICP Title: [The job title most likely to become a champion — usually a power user, not the economic buyer]
- Secondary Champion ICP Title: [Second most common champion profile]
- ICP's #1 Career Ambition: [What they are trying to achieve professionally in the next 12 months]
- ICP's #1 Peer Status Goal: [How they want to be seen by their professional community]
- Expansion Revenue Opportunity: [Where upsell/cross-sell lives: more seats, new modules, premium tiers]
- Competitor Champion Programs: [Known competitor community/advocate programs to differentiate from]
- Current Community Platform: [Slack / Discord / Circle / Gainsight Community / none]
- Existing Advocacy Program: [Any existing reference, case study, or G2 review programs]
- Marketing Team Size: [To calibrate automation requirements]
- CRM: [HubSpot / Salesforce / other — for integration design]
- Product Analytics Tool: [Amplitude / Mixpanel / Pendo / Heap — for behavioral signal integration]

---

DELIVERABLE 1 — CHAMPION IDENTIFICATION & SCORING MODEL

Section 1A: Behavioral Signal Architecture

Champion Propensity Score (CPS) — a 0-100 composite score built from four signal categories:

**Tier 1 Signals — Product Usage (40% weight)**
| Signal | Scoring Logic | Points |
|---|---|---|
| Weekly Active Usage | >4 sessions/week for 90+ days = 20 pts; 3-4 sessions = 12 pts; 1-2 = 5 pts | 0-20 |
| Feature Breadth | Using >70% of available features = 15 pts; 40-70% = 8 pts; <40% = 2 pts | 0-15 |
| Power Feature Adoption | Usage of 2+ advanced/power features = 5 pts | 0-5 |
Total possible from usage signals: 40 points

**Tier 2 Signals — Relationship Health (30% weight)**
| Signal | Scoring Logic | Points |
|---|---|---|
| NPS Score | Promoter (9-10) = 15 pts; Passive (7-8) = 5 pts | 0-15 |
| NPS Verbatim Sentiment | AI-analyzed verbatim: highly enthusiastic language = 10 pts; neutral = 3 pts | 0-10 |
| Support Ticket Sentiment | Last 3 tickets: positive/complimentary language = 5 pts | 0-5 |
Total possible from relationship signals: 30 points

**Tier 3 Signals — Social Proof Behavior (20% weight)**
| Signal | Scoring Logic | Points |
|---|---|---|
| G2/Capterra Review | Submitted review in last 12 months = 10 pts | 0-10 |
| Referral Activity | Referred 1+ customer = 10 pts; referred and converted = +5 bonus | 0-10 |
Total possible from social proof signals: 20 points

**Tier 4 Signals — Community Engagement (10% weight)**
| Signal | Scoring Logic | Points |
|---|---|---|
| Community Posts | >5 helpful posts/month = 6 pts; 1-4 = 3 pts | 0-6 |
| Peer Assistance | Answered another member's question = 4 pts | 0-4 |
Total possible from community signals: 10 points

Champion Identification Threshold:
- Score 75-100: Tier 3 Luminary candidates — immediate VIP outreach
- Score 60-74: Tier 2 Champion candidates — standard program invitation
- Score 45-59: Tier 1 Advocate candidates — nurture track with lightweight engagement
- Score <45: Monitor for signal improvement, trigger re-score in 45 days

Section 1B: Disqualification Criteria
Automatically exclude customers who meet any of the following regardless of CPS score:
- Open support escalation or billing dispute
- Renewal at-risk flag in CRM (health score <60)
- Recent executive-level complaint in last 90 days
- Account under active competitive evaluation
- CSM has flagged "do not solicit for marketing" in account notes

Section 1C: Scoring Automation Workflow
Trigger: Weekly automated CPS recalculation for all customers
Data Sources: Product analytics API → CRM enrichment → NPS platform sync → Community platform API
Output: CPS score updated in CRM contact record + segment tag applied
Escalation: Customers crossing 75+ threshold trigger Slack notification to CSM + Customer Marketing within 24 hours

---

DELIVERABLE 2 — CHAMPION RECRUITMENT SEQUENCE

Champion Invitation Sequence — 3-touch, fully AI-personalized:

**Touch 1 — Champion Discovery Email (Day 1)**
Sender: Named CSM or Customer Marketing Director (not a generic marketing alias)
Subject line options (A/B test):
- "[First Name], you're in the top 3% of [Product] users — I'd like your advice"
- "How [Company Name]'s power users shape our product roadmap"
- "[First Name], your [specific feature] usage caught our attention"

Body copy template:
---
Hi [First Name],

I've been looking at how [Company] uses [Product], and your team is genuinely impressive — [specific usage detail pulled from product analytics, e.g., "you've processed 847 campaigns in the last quarter, putting you in the top 3% of all users"].

We're launching a small, invitation-only Champion Program for customers who use [Product] at this level — and I wanted to personally invite you.

Champions get:
- Direct line to our product team for roadmap input (your voice actually shapes what we build)
- Early access to beta features before public release
- Invitation to our quarterly Champions Summit (virtual + in-person options)
- A public profile on [Product]'s Champions Hall of Fame

What we ask of Champions:
- One 45-minute quarterly call with our Product team to share how you use [Product] and what you'd change
- Participation in our community Slack workspace to help peers with questions when you have time
- (Optional) Willingness to be quoted in case studies or speak at one event per year

There's no hard commitment — this is peer recognition, not a corporate obligation.

Interested? [Single CTA: "Yes, tell me more" → 15-min booking link]

[Signature]
---

**Touch 2 — Social Proof + Community Preview (Day 5, if no reply)**
Subject: "What [Peer Champion Name at Similar Company] gets from the Champion Program"

Content: Brief story of a current champion (similar company size, title) and one specific way the program benefited their career (e.g., "Sarah was quoted in our 2024 State of RevOps Report — it became the most-shared piece of content in her LinkedIn feed that year").

**Touch 3 — Final Nudge with Scarcity (Day 10, if no reply)**
Subject: "Last call — Champion spots are capped at [N] per quarter"

Content: One-sentence genuine scarcity note, direct CTA to book a 10-minute intro call or decline gracefully (to avoid champion burnout from pressure).

---

DELIVERABLE 3 — TIERED CHAMPION ARCHITECTURE

**Tier 1 — Advocate (Entry Level)**
Entry criteria: CPS 45-74 + accepted program invitation
Annual commitment: Minimal — community participation, one optional reference activity
Program benefits:
- Private Slack/Discord #advocates channel access with advance product news
- 10% discount on next renewal applied at renewal date
- Digital "Advocate" badge for LinkedIn profile
- Monthly Advocate-only newsletter with product insider news
Revenue impact tracking: Tag in CRM as "Advocate"; track referral activity and expansion events

**Tier 2 — Champion (Core Level)**
Entry criteria: CPS 60-79 + completed 2+ program activities in last 6 months
Annual commitment: Quarterly product feedback call (45 min), community help (5+ peer assists/quarter), one optional reference activity per year
Program benefits:
- Named profile in Champions Directory on public website (with opt-out available)
- Direct Slack access to Product Manager for feature requests (bypasses standard feedback portal)
- Beta access: invited to all beta programs before public announcement
- Annual Champions Summit invitation (travel stipend provided for in-person attendance)
- Co-marketing opportunities: bylined articles, podcast guest spots, webinar panelist
- 15% renewal discount applied at renewal date
Revenue impact tracking: Multi-touch attribution model — track referral pipeline sourced, deal acceleration (days shaved off sales cycle when champion provides reference), and expansion events correlated with Champion program activity

**Tier 3 — Luminary (Elite Level)**
Entry criteria: CPS 80+ + minimum 12 months as Champion + 2+ pipeline referrals or 1 closed-won referral
Annual commitment: Two product advisory calls (45 min each), one speaking engagement (webinar or conference), active community leadership (host one AMA per quarter)
Program benefits:
- Annual Luminary Retreat: 2-day in-person exclusive event with CEO, CPO, and product leadership
- Named acknowledgment in annual report and investor materials
- Input into annual product roadmap priorities (your name attached to feature requests in public changelog)
- Exclusive co-authorship opportunity: co-author one research report or guide per year published under your name + our brand
- 25% renewal discount + priority enterprise support tier upgrade
- Referral fee: $500 gift card per qualified referral (converted to closed-won)
Revenue impact tracking: Full attribution — referral pipeline tagged as "Luminary-Sourced"; expansion revenue in Luminary accounts tracked quarterly; analyst/media mentions driven by Luminary content co-creation

---

DELIVERABLE 4 — ACTIVATION PLAYBOOK

**Activity 1 — Quarterly Product Shaping Call**
Format: 45-minute video call with Product Manager and 3-5 Champions
Cadence: Quarterly
AI role: Pre-call brief auto-generated from champion's usage data and feature request history; post-call summary auto-drafted with action items and roadmap commitments
Champion value: Your specific usage patterns shape real product decisions; follow-up changelog notes credit your input
Pipeline value: Post-call champions are 3.4x more likely to provide an unsolicited referral within 60 days (industry benchmark from Gainsight research)

**Activity 2 — Champions Help Hub**
Format: Dedicated #champions-help or Champions Forum space in community platform
AI role: AI agent monitors for unanswered member questions; tags relevant champions based on their usage patterns and expertise areas; sends personalized Slack DMs: "Hey [Name], you're one of 3 people in our community who uses [Feature X] the way [New Member] is asking about — would you be open to sharing how you set it up?"
Champion value: Builds professional reputation as a category expert; public recognition for contributions
Business value: Reduces support ticket volume by 12-18% in communities with active champion help hubs; generates authentic product testimonials in community threads

**Activity 3 — Champion Content Co-Creation**
Format: AI-ghostwritten LinkedIn posts and articles drafted using champion's own words from product feedback calls, community posts, and support interactions; submitted for champion review and publication under their name
Cadence: Monthly for Champions, bi-weekly for Luminaries
AI role: Transcribe and analyze champion's language patterns from calls; draft content in their voice; submit via email with one-click approve/edit/decline
Champion value: Thought leadership content published under their name with our distribution amplification; average 3-5x higher reach than typical LinkedIn posts
Business value: Each champion post generates 4-8 dark social conversations on average; tracked via UTM + first-touch attribution on any resulting demo requests

**Activity 4 — Champion Reference Network**
Format: Warm peer introductions between champion customers and prospects in active evaluation
Process: Sales reps submit reference requests through CRM; AI agent matches prospect profile (industry, company size, use case) to best-fit champion; sends personalized intro request to champion; champion chooses to participate or decline; AI drafts intro email for champion to send in their own name
Champion value: Builds their professional network with peers at target companies; career capital in their industry
Business value: Champion-introduced references close at 31% higher win rate and 18 days faster than cold references (based on industry research benchmarks)

**Activity 5 — Champions Summit (Quarterly Virtual + Annual In-Person)**
Format: Quarterly 90-minute virtual working session focused on one specific topic (e.g., "How our top 20 Champions are using [Feature X] to drive ROI"); Annual 2-day in-person Luminary Retreat with product leadership
AI role: Pre-summit research brief auto-generated from participant usage data and survey responses; session recordings auto-transcribed and highlights auto-clipped for community content
Champion value: Peer learning, networking with other top practitioners in their category, direct face time with executive team
Business value: Post-summit surveys show 78% of attendees report increased product advocacy activity in the 90 days following; CSM pipeline reviews show measurable expansion conversations initiated post-summit

**Activity 6 — Beta Program Priority Access**
Format: Champions and Luminaries are first cohort for every new feature beta; receive dedicated beta channel, weekly check-in cadence, and direct feedback submission process
AI role: Beta feedback auto-analyzed and categorized by theme; product team receives structured summary with champion attribution; changelog auto-drafts acknowledgment section crediting champion input
Champion value: Competitive advantage — using capabilities before competitors; direct influence over feature direction
Business value: Beta champions generate 2-4x more feature adoption during GA launch than non-beta customers; their authentic testimonials at launch are the highest-converting sales content available

---

DELIVERABLE 5 — REVENUE ATTRIBUTION MODEL

**Revenue Categories to Attribute:**

1. Champion-Sourced New Logo Pipeline
Tracking method: Every referral introduced by a champion tagged in CRM with "Champion Referral" source field + champion name; multi-touch model credits champion with 50% of first-touch if they made introduction before prospect entered known pipeline
Measurement: Quarterly review of Champion Referral pipeline by volume, ACV, and win rate vs. non-champion-sourced pipeline

2. Champion-Influenced Pipeline Acceleration
Tracking method: Any active deal where a champion reference call occurred; CRM automation logs call date vs. expected close date; compares champion-touched deal velocity against deal velocity without champion reference
Measurement: Average deal cycle reduction in days; multiply by average daily contract value to calculate acceleration revenue impact

3. Expansion Revenue in Champion Accounts
Tracking method: Tag all Champion-tier customers in CRM; compare NRR (Net Revenue Retention) of champion accounts vs. non-champion accounts with equivalent health score; control for company size and product tier
Measurement: NRR lift in champion accounts; quarterly expansion revenue attributed to champion program participation (correlation analysis with CSM input)

4. Dark Social and Influenced Pipeline
Tracking method: Self-reported attribution survey at every demo request ("How did you hear about us?"); correlation analysis between champion posting activity and geo/industry/company-type clusters in inbound lead flow
Measurement: Monthly community influence report mapping champion content publication dates to inbound traffic spikes from relevant audience segments

**Champion Program ROI Dashboard (built in HubSpot/Salesforce):**
| Metric | Target | Current | Trend |
|---|---|---|---|
| Active Champions (CPS 60+) | [N] | — | — |
| Champion-Sourced Pipeline (QTD) | $[X] | — | — |
| Champion Referral Win Rate | >35% | — | — |
| Reference Calls Completed | [N/quarter] | — | — |
| Deal Cycle Reduction (Champion-Touched) | >15 days | — | — |
| NRR: Champion Accounts vs. Control | >10pt lift | — | — |
| Champion Content Posts Published | [N/month] | — | — |
| Estimated Dark Social Reach | [N impressions] | — | — |

---

DELIVERABLE 6 — AI AGENT AUTOMATION WORKFLOW

**Fully Automated (no human required):**
- Weekly CPS recalculation and CRM score update
- Champion eligibility flagging and CSM Slack notification when threshold crossed
- Personalized invitation email sequence (Touch 1-3) with product analytics variables populated
- Beta invite distribution when new features reach beta-ready stage
- Community monitoring for unanswered questions → champion routing DM
- Post-call transcript analysis and summary generation
- Champion content draft generation from call transcripts and usage data
- Monthly Champions Newsletter assembly and distribution
- Quarterly attribution report generation and distribution to marketing/CS leadership

**AI-Assisted (human reviews and approves):**
- Champion content posts: AI drafts, champion reviews and edits before publishing
- Tier promotion recommendations: AI flags eligible candidates, CSM confirms before outreach
- Reference match recommendations: AI matches prospect to champion, sales rep confirms fit before introduction
- Luminary Retreat agenda: AI generates based on usage trends and community feedback, Customer Marketing Director finalizes

**Human-Only (requires judgment):**
- Tier 3 Luminary promotion decision: personal relationship + strategic fit assessment
- Executive escalation if champion has negative experience or churns
- Contract renewal discount application: CSM and Finance must approve
- Media and press introduction (AI drafts intro, PR team manages relationship)

**Integration Architecture:**
- Product Analytics (Amplitude/Mixpanel/Pendo) → CPS scoring engine → Salesforce/HubSpot contact record
- NPS Platform (Delighted/Qualtrics) → Sentiment analysis → CPS score update
- Community Platform (Slack/Circle) → Engagement tracking → CPS score update
- CRM → Champion tier tag → Marketing automation list membership → Appropriate nurture track
- CRM → Reference request form → AI matching engine → Champion DM → Sales notification

---

## Example Input/Output

**Example Company:** Operata — AI-powered contact center analytics for enterprise CX teams (VP Customer Experience, Director of Contact Center Operations buyers, $65K ACV, 340 customers)

**Example Champion Scoring Output:**

Champion #1: Jamie Park, Head of CX Technology, Velocity Financial Services
- Product Usage Score: 38/40 (daily user, 85% feature adoption, power user of AI anomaly detection)
- Relationship Health Score: 27/30 (NPS 10, verbatim: "This is the first tool that actually makes our data actionable — my team couldn't go back")
- Social Proof Score: 18/20 (submitted G2 review, referred two prospects)
- Community Score: 8/10 (posted 7 community answers last month)
- **Total CPS: 91/100 → Tier 3 Luminary Candidate**
- Recommended action: Personal call from VP Customer Success to invite directly to Luminary program

**Example Champion Content Output:**
AI-drafted LinkedIn post in Jamie's voice (based on their product feedback call transcript):

> "3 years ago, 'contact center analytics' meant a spreadsheet and a lot of guesswork. Today, my team spots emerging issues in our NPS scores 6 hours before they become executive escalations.
>
> Here's what changed: we stopped analyzing what happened and started monitoring what's about to happen.
>
> The shift from reactive to predictive in CX isn't about technology — it's about rethinking what 'insight' means. Insight that arrives after the problem is called 'a report.' Insight that arrives before the problem is called 'a competitive advantage.'
>
> We've reduced escalation rate by 34% in 18 months. Happy to share what the monitoring architecture looks like for anyone building a CX analytics function from scratch."

[Champion publishes; generates 847 impressions and 23 direct DMs from CX leaders at target accounts]

## Success Metrics

**Program Health Metrics (Monthly):**
- Champion enrollment rate: >40% of invited prospects should accept
- Champion activation rate: >65% of enrolled champions should complete at least one activity per quarter
- Champion retention: >80% of champions should renew program participation year-over-year
- Advocate-to-Champion progression: >25% of Advocates should reach Champion tier within 12 months

**Business Impact Metrics (Quarterly):**
- Champion-sourced pipeline: track to 15-20% of total new logo pipeline by month 18
- Champion-touched deal win rate: target 8-12 percentage points above average win rate
- NRR lift in champion accounts: target 15+ percentage points above non-champion account NRR
- Reference calls completed per quarter: minimum 2 per active Champion (capacity planning benchmark)

**Quality Metrics:**
- Champion satisfaction score: annual survey, target >8.5/10
- Content co-creation acceptance rate: >55% of AI-drafted content posts accepted and published by champion
- Community help activity: Champion accounts should contribute >60% of peer-to-peer answers in community

## Related Prompts

- [Community-Led Demand Generation Architecture](./AI-Powered-B2B-SaaS-Community-Led-Demand-Generation-Architecture-&-Pipeline-Revenue-Intelligence-Engine.md)
- [Customer Advisory Board Architecture](../../06_Customer-Success-&-Retention/Customer-Advocacy-&-Referral/AI-Powered-B2B-SaaS-Customer-Advisory-Board-CAB-Architecture-&-Executive-Advocate-Revenue-Intelligence-Engine.md)
- [Peer Referral Program Architecture](../../06_Customer-Success-&-Retention/Customer-Advocacy-&-Referral/AI-Powered-B2B-SaaS-Peer-Referral-Program-Architecture-&-Customer-Network-Revenue-Intelligence-Engine.md)
- [Customer Marketing Program Automation](../../06_Customer-Success-&-Retention/Customer-Advocacy-&-Referral/AI-Powered-B2B-Customer-Marketing-Program-Automation-&-Revenue-Intelligence-Engine.md)

## Integration Tips

**Salesforce / HubSpot:**
- Create "Champion Tier" custom field on Contact record with picklist: None / Advocate / Champion / Luminary
- Build Champion dashboard view showing CPS score, tier, last activity date, referrals submitted, pipeline sourced
- Set up automated task creation for CSM when contact CPS crosses 75+ threshold
- Use list segmentation to exclude champion accounts from standard marketing nurture tracks (replace with Champion-specific sequences)

**Amplitude / Mixpanel / Pendo:**
- Create "Champion Propensity Score" computed trait from product usage signals
- Set up behavioral cohort: "Potential Champion" (usage frequency + feature breadth thresholds)
- Configure event-triggered webhook to CRM when champion propensity threshold is crossed
- Build champion product adoption heatmap to identify which features correlate with highest CPS

**Gainsight / Totango:**
- Sync CPS score to customer health score as a contributing factor
- Create "Champion Program" success plan type for tracking activation milestones
- Set up automated CTAs (Calls to Action) for CSMs when champion candidates are identified
- Timeline notes auto-logged when champion completes each program activity

**Notion / Confluence:**
- Champion program playbook with SOPs for each program activity
- Champion profile database: CPS score, tier, preferences, content published, referrals submitted
- Quarterly attribution report template auto-populated from CRM data

**Zapier / Make:**
- Trigger: New G2 review submitted → Check CPS → If qualified, add to Champion outreach sequence
- Trigger: Champion tier promotion → Send personalized congratulations email + update all connected systems
- Trigger: Champion content post published → Log in CRM + notify relevant CSM + add to content library

## Troubleshooting

**Problem: Champion invitation acceptance rate is below 30%**
Fix: Audit your invitation copy — the most common cause is leading with what you want from champions rather than what they get. A/B test subject lines that reference the champion's specific usage data vs. generic "join our program" framing. Also check sender identity: emails from named CSMs outperform marketing aliases by 40-60% in typical champion program benchmarks.

**Problem: Champions enroll but go dark — no activity after joining**
Fix: The onboarding experience is too passive. Champions need a "quick win" within the first 14 days: schedule a 20-minute orientation call with product team within 1 week of enrollment; give immediate beta access to something tangible; send a welcome post from CEO/CPO in the champions channel that personally tags each new member. Monitor first-30-day activity; if a champion has no activity, trigger a personal CSM check-in (not an automated email).

**Problem: Attribution model is challenged internally — stakeholders don't believe the numbers**
Fix: Implement self-reported attribution at every demo booking form ("How did you first hear about us?") alongside automated tracking, and triangulate both data sets. Present champion-influenced pipeline with a conservative methodology: only claim direct referrals as "champion-sourced"; present all other correlations as "champion-influenced" with explicit methodology disclosure. Build credibility with leadership by starting with one quarter of confirmed, indisputable referral data before expanding attribution claims.

## Version History
- v1.0: Initial creation (auto-generated)
