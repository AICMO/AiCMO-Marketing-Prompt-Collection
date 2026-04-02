# AI-Powered B2B Community-Led Growth & Pipeline Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** b2b, community, growth, demand-gen, pipeline, clg, saas, automation

## Overview
Transforms a B2B brand community (Slack workspace, Discord server, Circle, Discourse, LinkedIn Group) into a fully measurable revenue channel by scoring Community-Qualified Leads (CQLs), automating engagement-to-pipeline workflows, and attributing closed revenue to community touchpoints — without manual SDR intervention.

## Quick Copy-Paste Version

You are a B2B Community-Led Growth strategist. Analyze my community and build a complete CLG revenue engine.

COMPANY CONTEXT:
- Product: [Your SaaS product and category]
- ICP: [Title, company size, industry]
- Community platform: [Slack/Discord/Circle/Discourse/LinkedIn Group]
- Current community size: [number of members]
- Current monthly active members: [number]
- ACV: [average contract value]
- Sales motion: [PLG / sales-assisted / enterprise]

BUILD ME:

1. COMMUNITY-QUALIFIED LEAD (CQL) SCORING MODEL
Score each member 0-100 based on:
- Engagement depth (posts, comments, reactions, DMs with team)
- Content signals (questions asked = buyer intent, answers given = champion potential)
- Profile signals (job title match to ICP, company firmographics)
- Behavioral signals (attended office hours, downloaded resources, tagged colleagues)
- Time-decay factor (recent activity weighted 3x vs. 90-day-old activity)

Define CQL thresholds:
- Hot CQL (score 75+): Route to AE within 24 hours
- Warm CQL (score 50-74): Add to automated nurture sequence, SDR follow-up within 72 hours
- Nurture (score 25-49): Content drip, invite to premium events
- Lurker (score 0-24): Activation campaign

2. COMMUNITY-TO-PIPELINE AUTOMATION PLAYBOOK
For each CQL tier, write the exact trigger → action → message sequence:
- What behavioral event fires the trigger
- Which system receives the signal (CRM, Slack alert, marketing automation)
- The first outreach message (personalized to their community activity)
- Follow-up cadence if no response

3. COMMUNITY CONTENT → PIPELINE STRATEGY
Design a content calendar that creates natural buying signals:
- Weekly live sessions that attract in-market buyers
- Templates and tools that pre-qualify intent
- Peer case study threads that accelerate trust
- "Office hours" format that converts attendance to pipeline

4. REVENUE ATTRIBUTION MODEL
Define how to credit community in your attribution:
- First-touch community attribution rules
- Multi-touch community influence scoring
- How to tag community-sourced deals in CRM
- Monthly CLG pipeline contribution report format

5. COMMUNITY HEALTH → REVENUE FORECAST
Create a leading indicator dashboard:
- Weekly active member growth rate (target: 10% MoM)
- CQL generation rate (target: 3-5% of active members monthly)
- Community-to-opportunity conversion rate benchmark
- Community influence on win rate vs. non-community deals

Output format: Numbered playbook with copy-paste CRM workflow steps, email/Slack templates, and a scoring spreadsheet schema.

## Advanced Customizable Version

ROLE: You are a senior B2B Community-Led Growth architect with deep expertise in the CLG motion pioneered by companies like Notion, Figma, dbt Labs, Salesforce Trailblazers, and HubSpot Academy. You understand community as both a demand generation channel and a revenue acceleration layer.

MISSION: Design and deploy a full-stack Community-Led Growth revenue engine for [COMPANY NAME] that generates measurable pipeline, accelerates deals, and creates defensible competitive moat through network effects.

═══════════════════════════════════════
COMPANY & COMMUNITY PROFILE
═══════════════════════════════════════

Company:
- Name: [Company name]
- Product category: [e.g., "B2B data enrichment platform" / "DevOps automation SaaS"]
- ICP: [Primary buyer persona — title, seniority, company size, industry]
- Secondary personas: [Champions, end users, influencers who affect the deal]
- ACV: [$X — defines effort justified per CQL]
- Sales cycle: [X weeks/months]
- Sales motion: [PLG self-serve / Sales-assisted / Enterprise-direct / Channel]
- Existing PLG loop (if any): [Free tier / trial / freemium — describe]

Community:
- Platform(s): [Slack / Discord / Circle / Discourse / LinkedIn Group / Custom / Multiple]
- Current size: [Total members]
- Monthly active members (MAM): [members posting/reacting in last 30 days]
- Community age: [months/years old]
- Primary community purpose today: [Support / Education / Networking / Product feedback]
- Community manager bandwidth: [hours/week dedicated]
- Current tech stack: [CRM: __ / MAP: __ / Community platform API: __ / Data warehouse: __]

Revenue context:
- % of current pipeline that mentions community as a touchpoint: [X%]
- Any anecdotal evidence of community-sourced deals: [describe]
- Biggest competitor community (if any): [name and size]

═══════════════════════════════════════
DELIVERABLE 1: COMMUNITY-QUALIFIED LEAD (CQL) FRAMEWORK
═══════════════════════════════════════

Build a CQL scoring model with these exact dimensions:

A. ENGAGEMENT SIGNALS (40 points max)
- Posts a question in product/use-case channel: +8 pts (buyer intent signal)
- Comments on 3+ posts in 30 days: +5 pts (active engagement)
- Attends live office hours or AMA: +10 pts (high intent)
- Reacts to pricing/ROI/case study content: +7 pts (commercial awareness)
- Tags or invites a colleague: +10 pts (expansion signal)

B. PROFILE SIGNALS (30 points max)
- Job title matches primary ICP: +15 pts
- Company firmographics match ICP (size, industry, tech stack signals): +10 pts
- LinkedIn profile indicates budget authority or technical evaluator: +5 pts

C. BEHAVIORAL SIGNALS (20 points max)
- Downloaded a template or tool from community resources: +8 pts
- Clicked a link to pricing page or demo page (via UTM tracking): +12 pts

D. RECENCY MULTIPLIER (10 points max)
- Activity in last 7 days: 1.5x score multiplier
- Activity in last 8-30 days: 1.0x
- Activity 31-90 days ago: 0.5x
- No activity 90+ days: 0x (mark as dormant)

CQL TIERS:
- 🔴 HOT CQL (75-100): Route to AE immediately via Slack alert + CRM task. Personalize outreach referencing their specific community post or question.
- 🟡 WARM CQL (50-74): Enroll in 5-touch automated sequence. SDR outreach within 72 hours. Invite to next executive roundtable or exclusive webinar.
- 🟢 NURTURE (25-49): Monthly value email. Invite to free community events. Flag for SDR review if score increases 15+ points in 7 days.
- ⚪ LURKER (0-24): Activation campaign. Send 3-part "quick win" email series showing immediate product value. Offer free template or audit.

CQL QUALIFICATION GATE: A CQL only passes to sales if score ≥ 50 AND ICP profile match ≥ 15 points. This prevents sales from chasing community fans who can't buy.

═══════════════════════════════════════
DELIVERABLE 2: COMMUNITY → PIPELINE AUTOMATION WORKFLOWS
═══════════════════════════════════════

For each trigger, write the complete automation workflow:

WORKFLOW 1: "Product Question = Buying Signal"
Trigger: Member posts in #product-questions or #use-cases channel
Filter: Member has ICP-matching profile (score ≥ 15 profile points)
Action sequence:
  Step 1 (0 min): Community manager or AI bot replies with helpful answer + relevant case study link (UTM-tagged)
  Step 2 (1 hour): If member clicks case study link → add 12 points to CQL score → check if total ≥ 50
  Step 3 (if score crosses 50): Fire Zapier/Make webhook → create CRM contact/lead → assign to SDR → send Slack alert: "🔥 Community CQL: [Name] at [Company] just hit 52 points. They asked: '[their question]'. Reach out within 24 hours."
  Step 4 (24 hours): SDR sends personalized outreach referencing their community question

Write the exact SDR outreach template:
---
Subject: Re: your question about [TOPIC] in [Community Name]

Hi [First Name],

Saw your post about [SPECIFIC QUESTION THEY ASKED] — great question.

[One-sentence answer that shows expertise]. A few of our customers in [their industry] solved this exact problem with [specific approach/feature].

[Customer Name] at [Similar Company] went from [before state] to [result] in [timeframe].

Worth a 20-minute call to walk through how they did it? [Calendar link]

[Signature]
---

WORKFLOW 2: "Colleague Invite = Expansion Signal"
Trigger: Existing community member invites a colleague via referral link or @mention
Action: Create expansion opportunity in CRM linked to parent account. Alert CSM if existing customer.

WORKFLOW 3: "Office Hours Attendance = High Intent"
Trigger: Member registers AND attends live office hours session
Action: Auto-enroll in 3-email post-session sequence. SDR outreach within 48 hours if ICP match ≥ 15.

WORKFLOW 4: "Dormant Reactivation"
Trigger: Member has been inactive 60+ days
Action: Send reactivation email with "What's new in [Community Name]" + exclusive community resource. If they click → add 10 points → re-evaluate CQL tier.

═══════════════════════════════════════
DELIVERABLE 3: COMMUNITY CONTENT ENGINE FOR DEMAND CREATION
═══════════════════════════════════════

Design a 4-week rotating content calendar that creates pipeline-generating conversations:

WEEK 1 — PROBLEM AWARENESS
- Monday: "Pulse poll" — ask community about their biggest challenge with [category problem]. Generates rich VOC data and surfaces in-market buyers.
- Wednesday: Expert AMA with a customer who solved the problem. Invite community via personalized DMs to ICP-matched members.
- Friday: Share a "State of [Category]" stat thread. Track who engages.

WEEK 2 — SOLUTION EDUCATION
- Tuesday: Teardown post — "How [Customer] achieved [Result] using [Method]." Tag the customer for authenticity.
- Thursday: Live product demo office hours (60 min, recorded). Gate the recording behind email capture.

WEEK 3 — PEER VALIDATION
- Monday: Ask for "quick wins" — "Share one thing that improved your [metric] this month." Harvest for case study mini-clips.
- Wednesday: Feature a community member as "Member Spotlight." Builds reciprocity and goodwill.

WEEK 4 — COMMERCIAL INTENT CAPTURE
- Tuesday: "Vendor evaluation checklist" — free downloadable template. UTM-track all downloads.
- Thursday: Exclusive preview of upcoming product feature for community members. Creates FOMO for non-members, urgency for prospects.

═══════════════════════════════════════
DELIVERABLE 4: REVENUE ATTRIBUTION MODEL
═══════════════════════════════════════

COMMUNITY ATTRIBUTION RULES FOR CRM:

1. Community First-Touch: If a contact's first known interaction was through community (invite link, organic join), tag opportunity with "Community First-Touch" source.

2. Community Influence: If a contact was an active community member (MAM status) at any point during the sales cycle, tag opportunity with "Community Influenced."

3. Community Sourced: If the sales cycle was initiated by a CQL trigger (SDR reached out because of CQL score), tag as "Community Sourced Pipeline."

MONTHLY CLG PIPELINE REPORT FORMAT:
---
COMMUNITY-LED GROWTH PIPELINE REPORT — [Month Year]

📊 COMMUNITY HEALTH
- Total members: [X] (MoM change: +X%)
- Monthly Active Members: [X] (MAM rate: X%)
- New members this month: [X]
- CQL generated: [X] (X% of MAM)

💰 PIPELINE IMPACT
- Community-sourced opportunities: [X] worth $[X]
- Community-influenced opportunities: [X] worth $[X]
- CQLs converted to opportunities: [X%]
- Community-sourced win rate: [X%] vs. non-community: [X%]
- Community-influenced deal velocity: [X days] vs. non-community: [X days]

🏆 TOP CQL CONVERSIONS THIS MONTH
1. [Name] at [Company] — $[ACV] — Source: Office hours attendance
2. [Name] at [Company] — $[ACV] — Source: Product question + case study click
3. ...

🚨 PIPELINE AT RISK
- Warm CQLs that haven't been contacted within 72 hours: [X]
- Hot CQLs pending AE assignment: [X]

NEXT MONTH FOCUS: [One strategic initiative]
---

═══════════════════════════════════════
DELIVERABLE 5: COMMUNITY HEALTH → REVENUE FORECAST MODEL
═══════════════════════════════════════

LEADING INDICATOR DASHBOARD (weekly cadence):

Metric | Formula | Target | Red Flag
MAM Growth Rate | (This month MAM - Last month MAM) / Last month MAM | 10% MoM | <3% MoM
CQL Generation Rate | CQLs generated / MAM | 3-5% | <1%
CQL → Opp Conversion | Opportunities created / CQLs | 15-25% | <10%
Community-Sourced Pipeline | $ community-sourced opps / Total pipeline | 15-30% | <5%
Community Influence Rate | % of won deals with community touchpoint | 40-60% | <20%
Community Win Rate Premium | Community win rate - overall win rate | +10-15 pts | <5 pts
Time-to-CQL (new members) | Days from join to first CQL trigger | <30 days | >60 days

REVENUE FORECAST FORMULA:
Projected CLG Pipeline (next quarter) =
  (MAM × CQL rate × Opp conversion rate × ACV × win rate)

Example: 500 MAM × 4% CQL rate × 20% opp conversion × $25,000 ACV × 25% win rate = $250,000 projected CLG revenue next quarter

═══════════════════════════════════════
DELIVERABLE 6: CLG COMPETITIVE MOAT STRATEGY
═══════════════════════════════════════

Design the network effects that make your community defensible:

1. KNOWLEDGE MOAT: All community-generated insights, templates, and playbooks live exclusively in your community. Content quality improves as member count grows.

2. PEER NETWORK MOAT: The more buyers in your ICP join, the more valuable the community becomes to other buyers. Design referral mechanics that reward members for inviting peers.

3. PRACTITIONER IDENTITY MOAT: Create a certification or recognition program (e.g., "[Product] Certified Expert") that gives members professional identity tied to your platform.

4. DATA MOAT: Community behavioral data (who's engaging with what, what problems are trending) feeds product roadmap and sales intelligence unavailable to competitors.

Describe how each moat specifically applies to [COMPANY NAME]'s competitive situation.

OUTPUT REQUIREMENTS:
- All templates must be copy-paste ready
- All scoring models must be exportable to Google Sheets or Salesforce custom fields
- All automation workflows must specify the exact tool stack (Zapier/Make trigger, CRM field update, Slack notification format)
- Revenue projections must show best case, base case, and downside scenarios

## Example Input/Output

**Input Example:**

Company: Mosaic Analytics — B2B financial analytics SaaS for CFOs at Series B-D companies
ICP: VP Finance / CFO, 100-500 employees, SaaS or tech-enabled services
Community: Slack workspace "The CFO Collective" — 1,200 members, ~180 MAM
ACV: $48,000
Sales motion: Sales-assisted (AE closes, but buyer self-educates heavily)
CRM: Salesforce, MAP: HubSpot, Community: Slack with Zapier integrations

**Output Example (excerpt):**

CQL SCORING FOR "THE CFO COLLECTIVE"

HOT CQL EXAMPLE — Score: 82/100
Member: Sarah Chen, VP Finance @ Buildwise (Series C, 280 employees)
Score breakdown:
  - Posted in #financial-modeling-help (question about rolling forecasts): +8
  - Attended CFO office hours last Tuesday: +10
  - Company firmographics match ICP perfectly: +10
  - Job title = exact ICP: +15
  - Clicked "How Mosaic reduced close time by 40%" case study link: +12
  - Tagged colleague Marcus (Controller) in thread: +10
  - All activity within last 7 days (1.5x multiplier applied): Final score 82
  
ACTION: AE receives Slack alert at 9:02 AM Wednesday:
"🔴 HOT CQL: Sarah Chen (VP Finance @ Buildwise, 280 employees) — Score 82. 
She asked about rolling forecasts in #financial-modeling-help, attended Tuesday's office hours, AND invited her Controller. 
Suggested opener: Reference her rolling forecast question and connect it to how Catalyst (similar company) solved it. Calendar: [link]"

SDR EMAIL SENT 10:15 AM:
Subject: Rolling forecasts in Mosaic — Buildwise context

Hi Sarah,

Your question Tuesday about rolling forecast update frequency — it's one of the most common pain points we hear from finance teams scaling past 200 people.

[3 sentences of specific tactical answer]

Catalyst Software ran into the same thing at Series C. They automated their 13-week cash flow model in Mosaic and cut their weekly close prep from 6 hours to 45 minutes. Their CFO wrote about it here: [link]

Given Buildwise's growth trajectory, I suspect you're hitting similar friction. Worth a 20-minute walkthrough of how they set it up?

[Calendar link] | [AE Name]

RESULT: Sarah booked a demo within 4 hours. Opportunity created: $48,000 ACV.
Community attribution: "Community Sourced" + "Community First-Touch" (Sarah joined Slack before any other touchpoint).

## Success Metrics

- **CQL volume**: 3-5% of monthly active members generate a CQL each month; below 1% indicates content isn't surfacing buying intent
- **CQL → opportunity conversion**: Target 15-25%; below 10% means scoring model needs recalibration or sales isn't following up fast enough
- **Community-sourced pipeline %**: Target 15-30% of total pipeline after 6 months of CLG motion; track quarter-over-quarter trend
- **Community win rate premium**: Community-influenced deals should close at 10-15 percentage points higher than non-community deals due to trust acceleration
- **Time-to-value for new members**: Measure days from join to first valuable engagement action; target under 7 days, red flag at 30+ days
- **Community influence on deal velocity**: Track average sales cycle for community vs. non-community deals; target 20-30% shorter for community-touched opportunities
- **MAM growth rate**: Monthly Active Member growth of 10%+ MoM indicates healthy community flywheel; below 3% signals content or engagement problem

## Related Prompts

- [`../../06_Customer-Success-&-Retention/Customer-Advocacy-&-Referral/Customer-Community-Building-&-Engagement-Intelligence-Engine.md`](../../06_Customer-Success-&-Retention/Customer-Advocacy-&-Referral/Customer-Community-Building-&-Engagement-Intelligence-Engine.md) — Build the community infrastructure and engagement programs that feed the CLG revenue engine
- [`../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Developer-Led-Growth-DLG-&-Technical-Community-Demand-Generation-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Developer-Led-Growth-DLG-&-Technical-Community-Demand-Generation-Engine.md) — Apply CLG principles specifically to developer and technical communities
- [`../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Ecosystem-Led-Growth-ELG-&-Partner-Qualified-Pipeline-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Ecosystem-Led-Growth-ELG-&-Partner-Qualified-Pipeline-Intelligence-Engine.md) — Extend CLG to partner ecosystems for multiplied pipeline generation
- [`../../03_Content-&-Creative/Founder-Brand-Content/Founder-Brand-Community-Building-&-Pipeline-Conversion-Intelligence-Engine.md`](../../03_Content-&-Creative/Founder-Brand-Content/Founder-Brand-Community-Building-&-Pipeline-Conversion-Intelligence-Engine.md) — Use founder-led community building to seed the early CLG motion

## Integration Tips

- **Salesforce**: Create custom fields `Community_Score__c`, `Community_Source__c`, `Community_First_Touch_Date__c`, and `CQL_Tier__c` on Contact/Lead objects. Set up workflow rules to auto-assign CQL tasks when score exceeds threshold
- **HubSpot**: Use custom contact properties for CQL score and tier. Build workflows triggered by score thresholds using HubSpot's native scoring tool combined with community data via API or Zapier
- **Slack (community platform)**: Use Slack's Events API to capture message_posted, reaction_added, and channel_joined events. Pipe to Zapier/Make with filters for ICP-matching users
- **Circle / Discourse**: Both offer webhooks for member activity. Circle has native Zapier integration; Discourse uses its official webhook system to fire on post creation and topic participation
- **Zapier / Make**: Build the scoring aggregation logic as a multi-step Zap or Make scenario. Store running scores in a Google Sheet or Airtable as the lightweight scoring database before syncing to CRM
- **Segment / mParticle**: If using a CDP, create a community_engagement event type and feed it into your existing customer scoring models for unified behavioral profile
- **Gong / Chorus**: Tag calls that originate from community CQLs with a "CLG" call tag. Pull win rate and deal velocity analytics by tag to prove ROI to leadership quarterly
- **Looker / Tableau**: Build the CLG Pipeline Report as a live dashboard pulling from CRM UTM data, community platform webhook logs, and Salesforce opportunity data

## Troubleshooting

**Problem: CQL scores are high but conversion to opportunities is below 10%**
Solution: The scoring model is likely over-weighting engagement signals and under-weighting buying intent signals. Recalibrate: reduce points for passive engagement (reactions, reads) and increase points for commercial signals (pricing page clicks, demo requests, ROI-content engagement). Also audit whether SDRs are following up within the required 24-72 hour windows — delayed follow-up dramatically reduces conversion.

**Problem: Community is growing but MAM rate is declining (more lurkers than active members)**
Solution: Activate lurkers with a personalized "quick win" sequence. Segment members who joined but never posted and send a 3-email series: email 1 = personalized welcome with a specific resource matching their job title, email 2 = an open question they can answer easily ("What's your biggest challenge with X?"), email 3 = an invitation to a small-group office hours with 5-8 people. Also review whether your community content is primarily broadcast (announcements) vs. conversation-starting — CLG communities need 70%+ conversation-starting content.

**Problem: Sales team is skeptical of community-sourced pipeline quality and not prioritizing CQL follow-up**
Solution: Run a 90-day "Community Win Rate Experiment" — tag all community-touched opportunities and track win rate vs. non-community. Present the data in a sales team meeting with specific examples of deals that closed faster or at higher ACV due to community trust. Create a leaderboard showing which AEs have the highest CQL conversion rate. Make community follow-up a formal SLA in the sales playbook with a manager-reviewed weekly report on CQL response times.

## Version History
- v1.0: Initial creation (auto-generated)
