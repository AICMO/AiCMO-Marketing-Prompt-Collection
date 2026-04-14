# AI-Powered B2B Marketing-Led Customer Onboarding Campaign & New Customer Revenue Continuity Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** customer-onboarding, marketing-automation, revenue-continuity, lifecycle-marketing, b2b, saas, expansion-revenue, customer-marketing

## Overview
Designs and executes the marketing-owned onboarding campaign infrastructure that runs in parallel with CS onboarding — covering automated nurture sequences, brand continuity communications, expansion seed campaigns, and the revenue handoff orchestration from closed-won to activated customer. Use this when your marketing team needs to own the post-sale communication layer, reduce time-to-value through marketing automation, or prevent silent churn in the first 90 days.

## Quick Copy-Paste Version

You are a senior B2B lifecycle marketing strategist specializing in post-sale customer marketing programs. Design a complete marketing-led onboarding campaign system for a new B2B SaaS customer segment.

COMPANY CONTEXT:
- Product: [Your SaaS product name and category]
- Core customer outcome: [Primary result customers achieve in first 90 days]
- Average contract value: [ACV]
- Typical buyer/champion role: [e.g., VP of Operations, Marketing Director]
- Typical end-user role: [e.g., Marketing Manager, Analyst]
- Sales CRM: [HubSpot/Salesforce]
- Marketing automation platform: [HubSpot/Marketo/Pardot/ActiveCampaign]
- Customer success platform: [Gainsight/ChurnZero/Totango]

BUILD THE FOLLOWING:

1. SALES-TO-MARKETING HANDOFF TRIGGER PROTOCOL
   - Closed-won data fields marketing needs from sales (deal context, use case, champion pain points, competitive displacement info)
   - Automated enrollment trigger conditions into marketing onboarding track
   - Segment assignment logic based on deal characteristics (company size, use case, region, product tier)

2. 90-DAY MARKETING ONBOARDING CAMPAIGN ARCHITECTURE
   For each phase (Days 1-7, Days 8-30, Days 31-60, Days 61-90):
   - Campaign objective and marketing's specific role in that phase
   - Email sequence: subject line, send trigger, body focus, CTA
   - Non-email marketing touchpoints (LinkedIn audience sync, direct mail, branded swag triggers, executive sponsor outreach)
   - Success event that advances customer to next phase

3. CHAMPION VS. END-USER COMMUNICATION TRACKS
   Create distinct messaging tracks for:
   - Executive Champion/Economic Buyer: business ROI milestones, strategic check-ins, expansion conversation seeds
   - Day-to-Day Champion/Power User: product tips, community invitations, certification paths, peer success stories
   - Include fork logic: how marketing automation decides which track each contact receives

4. EXPANSION REVENUE SEED CAMPAIGNS (Days 31-90)
   - Trigger conditions for introducing upsell/cross-sell messaging (usage thresholds, milestone achievements, team growth signals)
   - 3 expansion-seeding email templates with specific copy frameworks (before/after/bridge, value ladder)
   - Account expansion intelligence signals to route to CS for expansion conversation

5. MARKETING-TO-CS HANDOFF TRIGGERS
   - Marketing engagement signals that indicate customer health (email open patterns, webinar attendance, community activity)
   - Automated alerts to CS when marketing detects at-risk signals (email unsubscribe, link click drop-off, no opens for 14 days)
   - Enrichment data marketing sends to CS platform at each milestone

6. PROGRAM MEASUREMENT FRAMEWORK
   - Marketing-owned metrics during onboarding (email engagement rates, activation page visits, community joins, certification starts)
   - How to attribute marketing onboarding campaigns to NRR outcomes
   - 30/60/90-day reporting cadence to CS leadership and CMO

OUTPUT FORMAT: Deliver each section as a ready-to-implement campaign brief with exact copy, trigger logic, and tool configuration instructions. Include specific platform field names for HubSpot or Salesforce where relevant.

## Advanced Customizable Version

ROLE: You are a VP of Customer Marketing at a B2B SaaS company with deep expertise in post-sale lifecycle marketing, marketing automation architecture, and revenue continuity programs. You understand the organizational tension between marketing and customer success, and you design programs that create tight marketing-CS collaboration without stepping on CS ownership of the customer relationship.

COMPANY PROFILE:
- Company: [Company name]
- Product category: [e.g., Revenue Intelligence, HR Tech, Security Analytics]
- Product: [Product name]
- ICP: [Target customer description — industry, size, tech stack]
- Customer segments by ACV: [e.g., SMB <$15K, Mid-Market $15K-$100K, Enterprise >$100K]
- Primary buyer persona: [Title, responsibilities, key KPIs they own]
- Primary end-user persona: [Title, how they use the product daily]
- Current onboarding NPS score: [If known]
- Current 90-day churn rate: [If known]
- Key "aha moment" (first value event): [e.g., "First automated report shared with leadership"]
- Current marketing stack: [List key tools — MAP, CRM, CDP, analytics]
- Current CS stack: [CS platform, health scoring system]
- Marketing-CS relationship maturity: [Siloed / Collaborative / Fully Integrated]

STRATEGIC CONTEXT:
- Primary onboarding challenge: [e.g., low adoption by end-users, champions going dark post-signature, slow time-to-first-value]
- Expansion revenue target: [% of revenue from expansion, NRR target]
- Resources available: [FTEs dedicated to customer marketing, automation capabilities]
- Compliance/communication restrictions: [e.g., enterprise customers prefer fewer emails, regulated industries]

DELIVERABLE 1: MARKETING ONBOARDING CAMPAIGN STRATEGY BRIEF
Produce a strategic brief (board-ready, 1 page equivalent) covering:
- Marketing's defined role in onboarding (where marketing owns vs. supports CS)
- The Revenue Continuity Promise: how marketing ensures brand experience and ROI narrative continues seamlessly from deal close through 90-day activation
- 3 strategic bets for marketing's onboarding contribution (e.g., community-led activation, peer proof content delivery, executive relationship nurture)
- How this program ladders to NRR and expansion ARR targets

DELIVERABLE 2: CUSTOMER SEGMENTATION & TRACK ARCHITECTURE
Using the Jobs-To-Be-Done framework, define 3-4 onboarding tracks based on:
- Primary job the customer hired your product to do (Strategic JTBD, Operational JTBD, Compliance JTBD)
- Company size and CS coverage model (high-touch, tech-touch, digital-led)
- Deal origin (inbound self-identified vs. outbound sourced vs. partner-referred)

For each track, define:
- Track name and enrollment trigger
- Marketing communication intensity (number of touches per month)
- Tone and content focus (e.g., ROI storytelling for executives, tactical tutorials for users)
- Graduation criteria to standard customer marketing cadence

DELIVERABLE 3: COMPLETE 90-DAY CAMPAIGN CALENDAR
Structure as a day-by-day campaign calendar with:

WEEK 1 (Days 1-7): THE COMMITMENT REINFORCEMENT PHASE
Objective: Confirm buyer's decision, eliminate post-purchase dissonance, establish marketing relationship with both champion and end-users
- Day 0: Closed-won trigger — CRM workflow activates, marketing enriches contact record, adds to onboarding audience segment
- Day 1: [Champion] Welcome email from CMO/VP Customer Marketing (NOT automated CS welcome — this is personal, strategic)
  * Subject line formula: Affirm the decision + hint at what's ahead
  * Body framework: Acknowledge what they're solving → validate their selection logic → one concrete next step → introduce peer community
  * Signature: Senior marketing or executive (not generic company email)
- Day 1: [End Users] Product-first welcome from marketing automation
  * Subject: "Your [Product] is ready — here's your 5-minute quick start"
  * Body: One action, social proof from similar user, link to community
- Day 3: [Champion] "Your Success Roadmap" email
  * Attach/link: Personalized success plan doc (auto-populated from CRM deal data)
  * Include: Industry peer benchmark (from marketing's research library)
- Day 5: [End Users] First value tip email
  * Framework: Before/After/Bridge — show the outcome they'll achieve with one specific feature
- Day 7: [Champion + End Users] Week 1 milestone check + community invitation

WEEK 2-4 (Days 8-30): THE ACTIVATION ACCELERATION PHASE
Objective: Drive end-user adoption, reinforce champion's ROI thesis internally, seed expansion awareness
- Every 3-4 days: Alternating champion and end-user emails
- Day 10: Case study delivery — industry-matched customer success story (automated segment-based selection)
- Day 14: [Champion] "Mid-point momentum" email — preview of value realized, ROI calculation preview, introduce expansion capability awareness (soft, non-salesy)
- Day 17: [End Users] Power user tip — advanced feature that drives stickiness
- Day 21: Webinar/product workshop invitation (segment-specific)
- Day 28: [Champion] "30-Day Value Preview" — teaser for 30-day business review, marketing-generated ROI summary to share with their leadership

MONTH 2 (Days 31-60): THE VALUE AMPLIFICATION PHASE
Objective: Turn individual adoption into team/department adoption, create internal champion for expansion
- Day 31: [Champion] "Expand your team's impact" campaign — introduce additional seat/user expansion value prop
- Day 35: Customer community highlight — feature a power user success story from their industry
- Day 42: [Champion] Executive sponsor check-in email — from C-level or senior VP (personalized, 3 sentences max)
- Day 45: Certification program invitation (if applicable)
- Day 50: ROI story template — help champion draft their internal business case for expanded investment
- Day 55: Peer benchmark report — "How companies like yours are using [Product] at 90 days"

MONTH 3 (Days 61-90): THE RENEWAL CONFIDENCE & EXPANSION ACTIVATION PHASE
Objective: Solidify renewal confidence, activate expansion conversation, convert customer to advocate
- Day 60: [Champion] Early renewal communication (if <12 month contract) OR expansion conversation opener
- Day 70: Customer success story request — marketing team asks for participation in case study/reference program
- Day 75: Community leadership invitation — invite power users to speak at user group or webinar
- Day 80: [Champion] Pre-renewal/expansion briefing email — value summary, renewal terms preview, expansion ROI calculator link
- Day 85: G2/Gartner Peer Insights/Capterra review request — timed to peak satisfaction moment
- Day 90: [Champion] 90-day anniversary email — celebrate milestones, introduce dedicated customer marketing newsletter enrollment

DELIVERABLE 4: CAMPAIGN COPY LIBRARY
Write full copy for these 8 high-leverage emails:

EMAIL 1: Day 1 Champion Welcome (from CMO/VP)
[Full subject line, preview text, opening line, 3 body paragraphs using STAR framework: Situation they were in → Transformation they've committed to → Action they need to take → Result they can expect, PS line with community link]

EMAIL 2: Day 14 Champion Mid-Point Momentum
[Full copy — acknowledge activation progress, preview expansion capability, include social proof from similar company at same stage, soft CTA to expansion conversation]

EMAIL 3: Day 28 Value Preview (pre-QBR primer)
[Full copy — marketing-generated ROI data points, slide template link, "here's what to tell your leadership" framing]

EMAIL 4: Day 50 ROI Story Template
[Full copy + template for champion to use internally — make it easy for them to tell your story to their CFO/CEO]

EMAIL 5: Day 60 Expansion Conversation Opener
[Full copy — use the "before/after/bridge" framework to introduce expansion ROI, NOT a sales pitch but a strategic value-add]

EMAIL 6: Day 70 Case Study/Reference Request
[Full copy — WIIFM for customer: visibility, networking, speaking opportunities; reduce friction by outlining exact commitment required]

EMAIL 7: Day 85 Review Request
[Full copy — timed to maximum satisfaction, specific platform request, make it 2-minute easy, incentive if allowed]

EMAIL 8: Day 90 Anniversary
[Full copy — milestone celebration, 90-day metrics summary (auto-populated), introduce ongoing customer community, enrollment in customer advisory board nomination]

DELIVERABLE 5: MARKETING-CS INTEGRATION ARCHITECTURE
Design the bi-directional data flow between marketing and CS:

MARKETING → CS SIGNALS (what marketing tracks and pushes to CS):
- Email engagement scoring model (open rate + click rate + time-spent = engagement tier)
- At-risk signal triggers: 0 opens in 10 days = yellow flag; unsubscribe = red flag; no community join by Day 30 = orange flag
- Expansion intent signals: clicked pricing/upgrade page, opened expansion email 2+ times, attended expansion webinar
- Advocacy readiness signals: opened case study request, clicked review link, referred a colleague

CS → MARKETING SIGNALS (what CS provides to marketing for personalization):
- Health score tier (drives email intensity and tone)
- Product usage milestones achieved (triggers celebration and advancement emails)
- QBR outcomes (drives ROI story personalization)
- Expansion conversations in progress (suppresses marketing expansion emails to avoid conflicting with sales process)
- Churn risk flag (routes to specialized churn-prevention marketing track — see related prompt)

AUTOMATION WORKFLOW ARCHITECTURE:
Define the exact trigger/action/condition logic for your MAP:
- Enrollment trigger: Opportunity Stage = Closed Won + Contact Role = Champion/End User
- Segment branching: [Deal size field] determines track assignment
- Suppression rules: Active CS-led expansion conversation suppresses marketing expansion emails
- CS platform sync: Push engagement score to [Gainsight/ChurnZero] health score field daily
- Alert routing: At-risk signals create CS task in platform within 2 hours

DELIVERABLE 6: MEASUREMENT & ATTRIBUTION FRAMEWORK
Define marketing's accountability for onboarding program outcomes:

MARKETING-OWNED KPIs (90-day targets):
- Email engagement rate during onboarding: [benchmark: 35%+ open rate, 8%+ CTR for onboarding sequences vs. 22% / 3% for batch campaigns]
- Community enrollment rate by Day 30: [target: 40%+ of new customers]
- Certification starts by Day 60: [target: 25%+ of power users]
- Review submission rate by Day 90: [target: 15-20% of new customers]
- Expansion pipeline sourced by marketing in onboarding window: [dollar target]

SHARED KPIs (Marketing + CS co-owned):
- 30-day activation rate (product milestone): [target based on historical baseline]
- 90-day NPS score: [target improvement over current baseline]
- 90-day churn rate: [target reduction]
- Time-to-first-value: [target reduction in days]

ATTRIBUTION MODEL:
- Multi-touch attribution crediting marketing onboarding emails to NRR outcomes
- How to measure marketing's contribution to expansion revenue sourced in onboarding window
- Reporting cadence: Weekly email metrics → Monthly program review → Quarterly NRR attribution report

OUTPUT REQUIREMENTS:
- All email copy must be written in full, not in template/placeholder format
- Trigger logic must be specific enough for a marketing ops manager to implement in HubSpot/Marketo without additional research
- Metrics must include benchmarks so the team knows what "good" looks like
- Frame every deliverable around marketing's accountability to revenue, not marketing's activity

## Example Input/Output

**Input Example:**

Company: Meridian AI (Series B, $28M ARR)
Product: AI-powered sales forecasting and pipeline intelligence platform
ICP: Mid-market B2B SaaS companies, 100-500 employees, VP of Sales or CRO as buyer
ACV: $42,000 average
Aha moment: "First AI-generated forecast accepted by leadership in weekly revenue review"
Current 90-day churn: 8% (target: <4%)
Marketing stack: HubSpot, Clearbit, Segment, Amplitude
CS stack: Gainsight, Slack (for customer Slack channels)
Primary challenge: End-users (sales managers) not adopting the platform after champion (CRO) signs

**Output Example (partial — Day 1 Champion Email):**

**Subject:** Meridian is live — here's what the next 90 days look like for [Company Name]
**Preview text:** Your forecast accuracy goal is now on the calendar.

Hi [First Name],

You made a decision that most CROs I talk to are still debating — moving from gut-feel forecasting to AI-verified pipeline intelligence. That decision is going to look very smart in Q[next quarter].

Here's what happens now: Over the next 90 days, your team is going to achieve three things that will change how your leadership team runs revenue reviews. By Day 30, you'll have your first AI-generated forecast ready to present. By Day 60, every one of your sales managers will be running their pipeline reviews inside Meridian. By Day 90, you'll have 90 days of forecast accuracy data that makes your board conversation in [Month] significantly more confident.

I'll be sending you a short note every two weeks to make sure you have what you need from us — and to connect you with other CROs at companies like yours who are 90 days ahead of where you are today. You can always reach me directly at this email.

One thing before you dive in: Your success team is setting up your Meridian Slack channel today. That's where you'll have a direct line to your CSM and where other CROs in our community share what's working. Join it when you get the invite — it's the fastest way to accelerate your team's adoption.

To your best forecast yet,
[CMO/VP Customer Marketing Name]
[Title] at Meridian AI

P.S. — The Meridian Customer Community has 340 CROs and VP of Sales who share pipeline intelligence best practices. You'll get an invitation tomorrow. It's worth 15 minutes a week.

---

**Expansion seed email — Day 60 Output (partial):**

**Subject:** [Company Name]'s next chapter with Meridian
**Preview text:** Here's what companies at your stage typically unlock next.

Hi [First Name],

At 60 days, CROs in your position are usually thinking about one of two things: expanding Meridian to their enterprise accounts team, or adding deal intelligence features to catch at-risk deals earlier.

[Company at similar stage] started exactly where you are and expanded from 12 seats to 47 seats in 4 months after activating deal intelligence. Their RevOps team now runs their weekly board pipeline review entirely from Meridian data.

I've asked [CSM Name] to share a quick ROI model showing what expanding from [current seat count] to your full sales team would look like for [Company Name]'s forecast accuracy. No pressure — just the data so you have it when the conversation comes up in your next QBR.

[CSM Name] will reach out to walk you through it this week if you want.

Best,
[Name]

## Success Metrics

**Program Health Metrics (track weekly):**
- Onboarding email open rate: Target 40%+ (industry average for lifecycle: 25%)
- Onboarding email click rate: Target 10%+ (industry average: 3-4%)
- Community enrollment by Day 30: Target 35%+
- At-risk signals flagged and routed to CS: 100% within 2 hours of trigger

**Revenue Impact Metrics (track quarterly):**
- 90-day churn rate reduction vs. control group: Target 30-50% reduction
- Time-to-first-value improvement: Target 20-30% reduction in days
- Marketing-sourced expansion pipeline in onboarding window: Target 15% of expansion ARR
- NPS at 90 days vs. baseline: Target +12 NPS points improvement

**Attribution Proof Points:**
- Multi-touch credit to marketing for closed expansion deals where marketing onboarding email was in the path
- Revenue continuity score: % of customers who maintained continuous engagement from deal close through 90 days

## Related Prompts

- [Customer Onboarding Intelligence System](./Customer-Onboarding-Intelligence-System.md)
- [AI-Powered Customer Value Realization & Success Milestone Intelligence Engine](./AI-Powered-Customer-Value-Realization-&-Success-Milestone-Intelligence-Engine.md)
- [AI-Powered B2B At-Risk Account Marketing Rescue & Churn Prevention Campaign Intelligence Engine](../Churn-Prevention-&-Expansion/AI-Powered-B2B-At-Risk-Account-Marketing-Rescue-&-Churn-Prevention-Campaign-Intelligence-Engine.md)
- [Behavioral Email Trigger Lifecycle Automation Engine](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Behavioral-Email-Trigger-Lifecycle-Automation-Engine.md)

## Integration Tips

**HubSpot Configuration:**
- Create a dedicated "Marketing Onboarding" workflow triggered by Deal Stage = Closed Won
- Use Contact Properties: `onboarding_track`, `onboarding_day`, `cs_health_score` (synced from Gainsight via API)
- Build List: Active Onboarding Customers (Days 1-90) — use for LinkedIn Matched Audience sync for retargeting reinforcement
- Set up internal notification workflow: if `email_opens_last_10_days = 0`, create task assigned to CS owner in HubSpot

**Gainsight / ChurnZero Integration:**
- Push HubSpot engagement score to Gainsight custom field: `marketing_engagement_score` (update daily via Zapier or native integration)
- Configure Gainsight CTA trigger: when `marketing_engagement_score` drops below threshold, auto-create "Marketing flagged at-risk" CTA for CSM
- Pull Gainsight health score into HubSpot for segmentation: use in email personalization token `{{contact.cs_health_tier}}`

**Salesforce Integration:**
- Map Closed Won Opportunity fields to Contact enrollment properties: `use_case`, `competitor_displaced`, `deal_source`, `product_tier`
- Use opportunity data to auto-select onboarding track and personalize email templates
- Create Campaign Member records for every onboarding email sent — enables pipeline influence attribution in Salesforce Campaigns

**Segment / CDP Integration:**
- Create Onboarding Audience in Segment — sync to LinkedIn Campaign Manager for brand awareness ads during onboarding window (reduces "buyer's remorse" from seeing competitor ads post-purchase)
- Track custom onboarding events: `onboarding_email_opened`, `community_joined`, `certification_started` — feed back to HubSpot for behavioral trigger logic

**Zapier Automation (for teams without native integrations):**
- Trigger: New Closed Won in Salesforce → Action: Enroll contact in HubSpot onboarding workflow + create Slack notification in #customer-wins channel with deal context
- Trigger: HubSpot contact property `at_risk_flag = true` → Action: Create task in Gainsight + send Slack DM to CSM

## Troubleshooting

**Problem: CS team pushes back on marketing communicating with "their" customers**
Solution: Present this as a marketing-owned layer that augments (not replaces) CS communication. Show CS leaders the data: marketing onboarding emails have 3-4x higher open rates than CS operational emails because they come from a different sender and are less transactional. Agree on a communication calendar with CS so both teams see all touchpoints, and establish explicit suppression rules when CS is in active conversation. Frame marketing's role as "brand and community" while CS owns "product and success."

**Problem: Email engagement is high but product adoption (actual aha moment) isn't improving**
Solution: Misalignment between marketing content and the specific activation milestone. Audit which emails get the highest click-through and ensure those CTAs link directly to the activation action (not a blog post or generic product page). Add behavioral triggers: if a contact opens the Day 7 email but doesn't complete the activation milestone, suppress standard track and send a specific "one thing" email with a single friction-free CTA. Loop in CS to understand what's blocking in-app adoption — marketing content can reinforce the fix.

**Problem: No data from sales to personalize onboarding campaigns**
Solution: This is a CRM data quality issue. Implement a Closed Won checklist in Salesforce/HubSpot: required fields before deal can advance to Closed Won stage (use case selected, primary persona tagged, competitor field filled). Marketing ops should run a weekly "blank fields" report and work with sales leadership to enforce. In the interim, use company firmographic data (industry, size, location) from Clearbit/Apollo to power basic personalization until richer deal data is available.

## Version History
- v1.0: Initial creation (auto-generated)
