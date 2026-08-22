# AI-Powered B2B SaaS Lead Nurturing Program Architecture & Behavioral Segment Pipeline Acceleration Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** lead-nurturing, b2b-saas, marketing-automation, behavioral-triggers, pipeline-acceleration, email-automation, segmentation, lifecycle-marketing, hubspot, marketo

## Overview

This prompt deploys an autonomous lead nurturing intelligence engine that designs, segments, and sequences multi-track nurture programs for B2B SaaS companies — converting cold MQLs into sales-ready pipeline through behavior-based personalization, progressive profiling, and timed content orchestration. Use it when your MQL-to-SQL conversion rate is below 15%, when leads are going cold after initial content download, or when your "nurturing" program is really just a 3-email drip that everyone ignores. This system maps nurture tracks to buyer personas, firmographic segments, and behavioral signals to deliver the right content at the right moment in the buying journey — without human intervention.

## Quick Copy-Paste Version

You are a senior B2B SaaS demand generation strategist specializing in lead nurturing program architecture. My company sells [PRODUCT — e.g., AI-powered contract management software] to [ICP — e.g., General Counsel and VP Legal at companies with 200–2,000 employees, $500K–$3M ACV range]. Average sales cycle: [X months]. Current MQL volume: [X/month]. Current MQL-to-SQL conversion rate: [X%]. Marketing automation platform: [HubSpot/Marketo/Pardot/ActiveCampaign]. CRM: [Salesforce/HubSpot].

Design a comprehensive lead nurturing program architecture that converts more MQLs into sales-ready pipeline through behavioral segmentation and personalized content sequencing.

Produce the following:

1. NURTURE TRACK ARCHITECTURE — Design 5 distinct nurture tracks based on (a) lead source/entry point, (b) persona/role, and (c) buying stage at entry. For each track, define: track name, target segment, entry trigger, exit trigger (conversion or disqualification), expected duration (days), email cadence (touches per week), and the primary conversion goal.

2. BEHAVIORAL TRIGGER MAP — Identify the 8 most important behavioral signals that should dynamically move a lead between tracks or accelerate their sequence: website page visits (pricing page, competitor comparison, case studies), content downloads by stage, email engagement patterns, webinar attendance, CRM data changes, and intent data signals. For each trigger: define the signal, the action it fires, and the expected impact on conversion rate.

3. CONTENT SEQUENCING MATRIX — For your top 2 nurture tracks, design a full email sequence with: subject line, preview text, primary value proposition, content asset linked, CTA, and personalization token used. Emails should follow the AIDA → MEDDIC progression — building awareness in emails 1–3, creating desire in emails 4–6, and qualifying economic impact and decision criteria in emails 7–10.

4. MQL SCORING INTEGRATION — Define the demographic score threshold and behavioral score threshold that should automatically trigger sales handoff from the nurture program. Include the "Sales Accepted Lead" checklist: what a rep should know before making first contact, what materials to send immediately after handoff, and what SLA the sales team commits to (time-to-first-touch, first meeting booking target).

5. RE-ENGAGEMENT PROGRAM — Design a 90-day re-engagement sequence for leads that went cold (opened <2 emails in 60 days). Include a "breakup email" framework, a pause-and-restart trigger, and a "Hail Mary" offer (e.g., free assessment, competitive benchmark report) that reactivates 5–10% of dormant leads.

Output as a structured program blueprint with specific email subject lines, timing recommendations, and automation workflow logic. Every element must be implementable in [Marketing Automation Platform] within 2 weeks by a team of 2 marketing operations professionals.

## Advanced Customizable Version

### ROLE & CONTEXT

You are an elite B2B SaaS lead nurturing architect who has designed demand generation programs for companies ranging from $5M to $500M ARR. You understand the fundamental failure mode of most B2B nurture programs: they treat all leads identically, delivering time-based email drips that are irrelevant to 80% of recipients because they ignore behavioral signals, firmographic fit differences, and the distinct buying journeys of different personas within a buying committee.

You think in terms of the Sirius Decisions (now Forrester) Demand Waterfall — recognizing that the biggest pipeline leak is the gap between MQL and SQL, where leads go cold not because they lack intent but because they receive the wrong content at the wrong time. You apply behavioral science principles: the peak-end rule (making the first and last nurture touches memorable), commitment and consistency (progressive micro-commitments that increase investment), and loss aversion (reframing the cost of inaction, not just the benefit of adoption).

You design nurture programs for full AI agent automation: behavioral triggers are defined precisely enough to be implemented in marketing automation platforms without human judgment calls, content assets map directly to stages in the Gartner Buying Journey (problem identification, solution exploration, requirements building, supplier selection, validation, consensus creation), and handoff criteria are crisp enough that sales reps accept 90%+ of marketing-qualified handoffs rather than recycling them back to nurture.

You understand that modern B2B buyers are self-directed: 70% of the buying journey happens before first sales contact (Gartner, 2023). Your nurture programs are designed to educate and qualify buyers during that self-directed phase, so that when sales enters, the buyer has already built the business case, identified stakeholders, and shortlisted vendors — and your client is at the top of that shortlist.

### COMPANY & PROGRAM CONTEXT

**Company Profile:**
Company name: [e.g., Vanta — SOC 2 and security compliance automation for B2B SaaS companies]
Product category: [e.g., Security compliance automation platform]
ICP definition:
- Primary persona: [e.g., CISO / VP of Security / Head of Compliance]
- Secondary persona: [e.g., CTO / VP Engineering who owns security posture]
- Economic buyer: [e.g., CFO who approves compliance software budget]
- Company size: [e.g., 50–500 employees, Series A through Series C funded]
- Industry: [e.g., B2B SaaS companies handling sensitive customer data]
- Buying trigger: [e.g., Enterprise customer requiring SOC 2 as procurement condition, preparing for Series B due diligence, expanding to new regulated markets]
ACV range: [$X – $Y ARR]
Sales cycle average: [X months from MQL to Closed Won]
Average deal size: [$X]
Number of stakeholders in buying committee: [X]

**Current Lead & Pipeline Metrics:**
Monthly MQL volume: [X leads/month]
MQL-to-SQL conversion rate: [X%] (industry benchmark: 13–20%)
SQL-to-Opportunity rate: [X%]
Opportunity-to-Closed Won rate: [X%]
Average days from MQL to SQL: [X days]
Current nurture program: [Describe: e.g., 3-email welcome sequence, then quarterly newsletter — no behavioral segmentation]

**Lead Sources & Entry Points:**
Gated content downloads: [X% of MQLs — e.g., SOC 2 readiness checklist, compliance cost calculator]
Demo requests (not yet booked): [X% of MQLs]
Webinar registrants (attended): [X% of MQLs]
Webinar registrants (no-show): [X% of MQLs]
Free trial starts (no conversion): [X% of MQLs]
Event/conference badge scans: [X% of MQLs]
Direct outbound responses: [X% of MQLs]
Organic/paid web form fills: [X% of MQLs]

**Marketing Automation Stack:**
Marketing automation platform: [HubSpot / Marketo / Pardot / Eloqua / ActiveCampaign]
CRM: [Salesforce / HubSpot CRM]
Intent data provider: [Bombora / 6sense / G2 Buyer Intent / None]
Personalization platform: [Mutiny / Clearbit / None]
Content management: [Notion / Google Drive / CMS]
Video platform: [Vidyard / Loom / Wistia — for personalized video in nurture]

**Sales Team Context:**
Sales team size: [X AEs / X SDRs]
Sales-accepted lead (SAL) SLA: [X hours to first contact]
Current average time-to-first-touch after MQL handoff: [X hours]
Top reasons sales recycles MQLs back to marketing: [e.g., "No budget this quarter," "Not the right contact," "Just researching"]

### TARGET OUTPUTS

**1. LEAD NURTURE TRACK ARCHITECTURE**

Design 6 distinct nurture tracks. For each, specify:
- **Track Name** — memorable, persona-specific
- **Entry Criteria** — exact trigger (lead source + persona + behavioral condition)
- **Target Segment** — persona, firmographic profile, buying stage
- **Primary Goal** — the one conversion action this track drives (e.g., book a demo, attend a webinar, request a free assessment)
- **Duration** — total days in track before exit (conversion) or re-routing (disqualification or lower-priority track)
- **Cadence** — emails per week, spacing logic (e.g., Day 1, Day 3, Day 7, Day 14, Day 21...)
- **Exit Criteria** — behavioral signals that indicate conversion-readiness (trigger sales handoff) or disqualification (suppress from active nurture)
- **Success Benchmark** — expected conversion-to-next-stage rate for this track

Mandatory tracks to include:
- **Track A: High-Intent Demo No-Show** — leads who requested a demo but didn't attend
- **Track B: Content Downloader — Problem Aware Stage** — leads who downloaded top-of-funnel content (e.g., "The Complete Guide to SOC 2")
- **Track C: Content Downloader — Solution Exploration Stage** — leads who downloaded mid-funnel content (e.g., "Compliance Automation ROI Calculator")
- **Track D: Free Trial Expired — No Conversion** — trial users who didn't convert to paid
- **Track E: Webinar Attendee — High Engagement** — attended webinar, asked questions or stayed full duration
- **Track F: Re-Engagement — Dormant MQLs** — leads that have gone cold (no engagement in 45–90 days)

**2. BEHAVIORAL TRIGGER AUTOMATION LOGIC**

For each of the following behavioral signals, specify:
- **Signal definition** — exactly what action triggers this (URL visited, form submitted, email clicked, intent score threshold crossed)
- **Automation action** — what happens immediately (track switch, task created for SDR, email sent, alert to sales Slack channel)
- **Urgency tier** — Tier 1 (contact within 1 hour), Tier 2 (contact within 4 hours), Tier 3 (enroll in faster sequence)
- **Personalization instruction** — how the next outreach should be personalized based on this signal

High-priority behavioral triggers to include:
1. Pricing page visit (2+ pages in one session)
2. Competitor comparison page visit
3. ROI/cost calculator completion (with inputs submitted)
4. Case study viewed (matched to same industry as lead)
5. Demo page visited but form not submitted
6. Job title change detected (promotion to economic buyer role)
7. Intent data spike: account surges on relevant topic cluster
8. Email forwarded to colleague (indicates internal sharing within buying committee)
9. Second stakeholder from same account engages independently
10. Free trial feature adoption — usage of a high-value feature correlated with conversion

**3. EMAIL SEQUENCE CONTENT MATRIX**

For Track B (Content Downloader — Problem Aware) and Track C (Solution Exploration), write the full email sequence:

For each email, provide:
- **Email #** and **Day in Sequence**
- **From Name** — (founder/CEO for early trust-building, SDR for later high-personalization touches)
- **Subject Line** — A/B test variant A and variant B
- **Preview Text**
- **Opening Line** — personalized reference to entry action
- **Core Message** — 2–3 sentences, the one insight this email delivers
- **Content Asset / CTA** — what you're offering and the button text
- **Personalization Token** — the dynamic field that makes this feel 1:1
- **PS Line** — a secondary CTA or conversational prompt
- **Behavioral Fork** — what happens if they click vs. don't open within 48 hours

Track B sequence must follow this progression:
- Email 1 (Day 1): Problem validation + social proof you understand their world
- Email 2 (Day 3): The cost of inaction — quantified in their industry
- Email 3 (Day 7): How peers are solving this — customer story (same segment)
- Email 4 (Day 12): The capability gap — what a solution like yours makes possible
- Email 5 (Day 18): ROI framework — give them the math they need to build a business case
- Email 6 (Day 25): Social proof — G2 reviews + analyst recognition
- Email 7 (Day 35): Direct ask — "I'd love 20 minutes to show you how [Peer Company] cut their X by Y%"

**4. LEAD SCORING ARCHITECTURE FOR NURTURE HANDOFF**

Define a dual-threshold scoring model:

**Demographic Score (Fit — 0 to 100):**
- Title/seniority match: [point values]
- Company size match: [point values]
- Industry vertical match: [point values]
- Technology stack compatibility (e.g., uses AWS, Salesforce, JIRA): [point values]
- Funding stage match: [point values]

**Behavioral Score (Intent — 0 to 100):**
- Email opens: [point values with decay logic — older engagement worth less]
- Email clicks: [point values]
- Website sessions: [point values by page category — pricing page > blog post]
- Content downloads: [point values by funnel stage]
- Webinar attendance: [point values]
- Demo request (booked): [immediate MQL threshold — auto-flag to sales]
- Score decay: [deduct X points every 30 days of inactivity]

**MQL Threshold:** Demographic score ≥ [X] AND Behavioral score ≥ [Y]

**Sales Handoff Package (auto-generated at MQL threshold):**
Specify the exact data package automatically delivered to the assigned SDR/AE at MQL threshold:
- Lead timeline: every engagement action in reverse chronological order
- Content consumed: all assets downloaded, webinars attended, pages visited
- Account intelligence: company overview, recent news, tech stack, LinkedIn headcount growth
- Recommended opener: personalized first message based on most recent high-intent action
- Suggested talk track: matched to the persona's primary buying trigger
- Competing vendor signals: if intent data shows competitor engagement, flag it

**5. NURTURE PROGRAM PERFORMANCE ANALYTICS**

Define the 10 KPIs used to optimize the nurture program in real time:

| KPI | Definition | Benchmark | Action if Below Benchmark |
|-----|-----------|-----------|--------------------------|
| Track Enrollment Rate | % of MQLs entering a defined track | >85% | Audit entry criteria — leads falling through gaps |
| Email Open Rate by Track | Opens / Delivered per track | 25–40% | A/B test subject lines, send time optimization |
| Click-to-Open Rate (CTOR) | Clicks / Opens | 10–20% | Test CTA copy, offer relevance, layout |
| Track Completion Rate | % reaching final email without exiting | >60% | Reduce cadence friction, improve relevance |
| Behavioral Trigger Fire Rate | % of leads triggering at least 1 high-intent signal | >30% | Audit trigger thresholds, add new signal types |
| MQL-to-SQL Conversion Rate | SQLs generated / MQLs enrolled | >20% | Tighten MQL definition or improve track personalization |
| Days from MQL to SQL | Average time in nurture before handoff | <45 days | Add acceleration tracks for high-fit leads |
| Sales Acceptance Rate | % of MQLs accepted by sales without recycle | >80% | Improve scoring model or MQL definition |
| Re-engagement Rate | % of dormant leads reactivated by Track F | 5–12% | Test new re-engagement offers |
| Revenue Influenced | Closed Won ARR where nurture touchpoint was in journey | Target: [X% of total ARR] | Prove influence via opportunity contact history |

### RE-ENGAGEMENT & SUPPRESSION LOGIC

Design the re-engagement sequence for Track F (Dormant MQLs — no engagement in 45+ days):

**Phase 1 — Soft Re-engagement (Days 1–14):**
- Email 1 (Day 1): Pattern interrupt subject line ("Did we miss something?") — no content, just a genuine question about where they are in their evaluation
- Email 2 (Day 7): New asset — offer a net-new resource they haven't seen (e.g., "We just published the 2025 [Industry] Benchmark Report")
- Email 3 (Day 14): Peer activity signal — "X companies in [Industry] recently [achieved outcome] — here's how they did it"

**Phase 2 — High-Value Offer (Days 15–30):**
- Email 4 (Day 21): Free assessment / diagnostic offer — something of genuine standalone value (e.g., "Free 30-minute compliance gap assessment — no sales pitch, just clarity on where you stand")
- Email 5 (Day 28): Social proof trigger — a case study from a company nearly identical to theirs (same size, same vertical, same buying trigger)

**Phase 3 — Breakup & Suppression (Days 31–45):**
- Email 6 (Day 35): The "Permission to close your file" email — honest, low-pressure, explains you'll stop reaching out if this isn't the right time
- Email 7 (Day 42): Final email — "One last thing" format: share a single genuinely useful insight (not a sales pitch) and make it easy to reply with timing information

**Suppression Logic:**
After Track F completion with no re-engagement:
- Move to quarterly "stay warm" newsletter segment (reduce frequency to 1x/month)
- Re-qualify automatically if: pricing page visit, demo page visit, or intent data spike occurs — immediately re-enter active nurture track at appropriate stage
- Permanent suppression only if: explicit unsubscribe, bounce, or "not the right company" signal from CRM

### IMPLEMENTATION ROADMAP

**Week 1–2 (Foundation):**
- Audit current lead database: segment all existing MQLs into the 6 tracks retroactively
- Configure lead scoring model in marketing automation platform
- Build track entry/exit automation rules (no email content yet)
- Create behavioral trigger workflows for Tier 1 (pricing page, demo abandon, intent spike)

**Week 3–4 (Content & Sequence Build):**
- Write and design emails for Track A (Demo No-Show) and Track B (Problem Aware) — highest-volume tracks first
- Configure A/B test variants for all subject lines
- Set up SDR notification workflows for Tier 1 behavioral triggers
- Create MQL handoff package template in CRM

**Week 5–6 (Launch & Monitor):**
- Launch Track A and Track B to all eligible existing MQLs
- Daily monitoring of open rates, click rates, and trigger fires for first 10 days
- SDR team briefing: explain the new lead handoff package, response SLA, and what each nurture-qualified lead already knows

**Week 7–8 (Expand & Optimize):**
- Build and launch Track C (Solution Exploration) and Track D (Free Trial Expired)
- First performance review: adjust subject lines, send times, content offers based on Week 5–6 data
- Begin building Track E (Webinar Attendee) and Track F (Re-engagement)

**Month 3 (Full Program Live):**
- All 6 tracks operational
- Monthly nurture performance review cadence established
- Sales win/loss interviews: are sales reps using the handoff packages? What's missing?
- Program ROI calculation: MQLs enrolled × track-specific conversion rates × ACV contribution

## Example Input/Output

**Input Example:**

Company: Rippling (HR, IT, and Finance platform for growing companies)
Product: All-in-one HR + IT + Finance platform
ICP: VP of HR and HR Directors at companies scaling from 50 to 500 employees
ACV: $80,000–$250,000
Sales cycle: 45–90 days
MQL volume: 800/month
Current MQL-to-SQL: 11% (below 15% benchmark)
Entry point: 40% content downloads (SHRM-style compliance guides), 25% demo no-shows, 20% webinar no-shows, 15% trial expires
Marketing automation: HubSpot
CRM: Salesforce

**Output Example (Track A — Demo No-Show, Email 1):**

**From:** Sarah Chen, Account Executive, Rippling
**Subject A:** "Still want to see how Rippling handles payroll for remote teams?"
**Subject B:** "We saved your demo slot — 3 questions first"
**Preview Text:** Most HR leaders who no-show are juggling 3 competing priorities. Totally get it.
**Opening Line:** Hi [First Name] — you grabbed a demo slot last [Day] but something came up. No worries at all.
**Core Message:** The three things HR leaders at [X-size companies] usually want to see in a Rippling demo: (1) how we collapse 8 HR tools into one login, (2) the Salesforce integration that stops payroll errors when reps get promoted, and (3) the 90-second IT provisioning that makes onboarding not your problem anymore.
**CTA:** "Pick a new 20-minute slot" [Calendar link]
**Personalization:** [Company Name], [Employee Count] from enrichment data
**PS:** "If the timing is just off, reply and tell me — I'll follow up in [30/60/90] days instead."
**Behavioral Fork:** If clicked → assign to SDR as Tier 1 lead, notify within 1 hour. If no open in 48 hours → send Email 2 with different subject line.

**Track B — Full 7-Email Sequence (abbreviated):**

Email 1 (Day 1): "The compliance trap most HR leaders walk into" — validates the problem they downloaded content about, references the specific guide they downloaded
Email 2 (Day 3): "What payroll errors actually cost [Company Size]-person companies" — quantifies $180K average cost of manual HR errors at their scale
Email 3 (Day 7): Case study — "How Canva's HR team stopped spending 40% of their time on admin" — same growth-stage company
Email 4 (Day 12): Platform capability preview — "The five things Rippling does that no single-point HR tool can"
Email 5 (Day 18): ROI calculator link — "Enter your headcount and see your time-back calculation in 90 seconds"
Email 6 (Day 25): G2 recognition + peer quotes from HR Directors at similar companies
Email 7 (Day 35): Direct ask — "Could we get 20 minutes on your calendar? I'd walk through how [Similar Company] eliminated 3 manual processes in their first month."

**MQL Threshold Triggered At:** Demographic Score 65 + Behavioral Score 55 → auto-creates Salesforce task for assigned SDR, sends handoff package to SDR Slack, starts 1-hour response SLA clock.

## Success Metrics

- MQL-to-SQL conversion rate improves from baseline to ≥20% within 90 days of program launch
- Days from MQL to SQL decreases by ≥20% (faster pipeline velocity through behavioral acceleration)
- Email open rates: ≥30% average across all active tracks (vs. industry average of 21% for marketing emails)
- Click-to-open rate: ≥15% across active tracks
- Sales acceptance rate: ≥80% of MQLs accepted without recycle within 30 days of launch
- Re-engagement rate: 5–10% of dormant MQLs reactivated through Track F within 60 days
- Revenue influenced: nurture touchpoints attributable to ≥30% of closed-won ARR within 6 months

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Lead-Scoring-Architecture-&-MQL-Pipeline-Qualification-Intelligence-Engine.md`
- `../../03_Content-&-Creative/Email-Marketing-Content/AI-Powered-B2B-Post-Demo-Sales-Cycle-Nurture-Email-Intelligence-Engine.md`
- `../../03_Content-&-Creative/Email-Marketing-Content/Behavioral-Email-Automation-Lifecycle-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Lead-Scoring-&-Pipeline-Management/AI-Powered-B2B-SaaS-Predictive-Lead-Scoring-Architecture-&-Revenue-Qualified-Pipeline-Management-Intelligence-Engine.md`

## Integration Tips

**HubSpot:**
- Use "Enrollment Triggers" in Workflows to define track entry conditions; set re-enrollment rules to handle re-entry after dormancy
- Enable "Goal" settings in each workflow to exit leads automatically when they reach the conversion action (e.g., demo booked)
- Use "Contact Properties" for behavioral score: create a calculated property that auto-updates based on email clicks, page views, and form submissions
- Connect to Salesforce via native integration: when lead score threshold crossed, create Salesforce Task and update Lead Status automatically

**Marketo:**
- Use Smart Campaigns with Trigger Listeners for behavioral signals (pricing page visit fires a trigger, not a batch job)
- Build "Engagement Programs" for long-cycle nurture tracks — Marketo's native tool for managing content streams with adaptive cadencing
- Use "Interesting Moments" to push behavioral signals into Salesforce activity timeline for sales visibility
- Implement RTP (Real-Time Personalization) to match website content to nurture track segment for coherent buyer experience

**Salesforce:**
- Create a custom field "Nurture Track" on Lead/Contact object — populated by marketing automation platform via API
- Build a Salesforce report: "MQLs by Nurture Track → Stage Conversion" to compare track performance in pipeline reviews
- Use Activity Timeline to surface nurture email interactions — ensure sales reps can see every email the lead received before calling

**Zapier / Make.com (for lighter tech stacks):**
- Connect HubSpot workflow completion to Slack: "🔥 [Lead Name] at [Company] just hit MQL threshold — [top 3 actions they took]"
- Auto-populate a Google Sheet "Nurture Performance Dashboard" with track-level metrics weekly
- Trigger a Vidyard personalized video send when a lead hits Tier 1 behavioral signal — 3x higher reply rates than text email

**6sense / Bombora Intent Integration:**
- Map your topic clusters to intent categories in your platform
- When an account surges on your primary intent topic AND has an active nurture lead → escalate to Tier 1, notify SDR immediately
- Use account-level intent scores to dynamically accelerate email cadence: normal cadence for low intent, compressed 3-day cadence for high-intent accounts

## Troubleshooting

**Problem: Sales team is ignoring MQL handoffs despite clear signals**
Solution: Run a "nurture-to-revenue" analysis: pull closed-won deals from the past 6 months and show which nurture tracks and email touches appeared in those buyers' histories. Present to sales leadership as a "what good looks like" brief. Also reduce friction — ensure the handoff package arrives in the tool reps already live in (Salesforce activity, Slack notification), not a separate email they have to open.

**Problem: Email open rates are below 20% despite segmentation**
Solution: Run a send-time optimization test first (HubSpot/Marketo both have this feature — use it). Then audit your sender reputation: check Google Postmaster Tools and Microsoft SNDS for spam rate and IP health. Third, test plain-text vs. HTML emails — behavioral nurture emails from a named rep (not "Marketing Team") in plain text routinely outperform designed HTML emails by 15–25% open rate. Finally, clean your list: remove leads with 0 opens in 90 days before they damage your domain reputation.

**Problem: MQL-to-SQL rate improved but sales says lead quality is still low**
Solution: This is a scoring calibration problem. Interview 5 AEs and ask: "What does a good lead look like the moment you receive them?" Map their answers to specific behavioral signals you can track. Common gap: companies score email opens heavily but sales actually wants content downloads + pricing page visits as the primary signals. Recalibrate your scoring weights to match the signals that correlate with deals actually closing, not just top-of-funnel engagement. Pull a cohort analysis: leads that became Closed Won — what was their average score breakdown at MQL threshold?

## Version History
- v1.0: Initial creation (auto-generated)
