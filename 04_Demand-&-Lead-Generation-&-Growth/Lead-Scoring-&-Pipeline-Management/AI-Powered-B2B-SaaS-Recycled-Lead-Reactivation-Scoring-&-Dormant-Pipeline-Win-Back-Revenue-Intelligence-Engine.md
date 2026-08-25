# AI-Powered B2B SaaS Recycled Lead Reactivation Scoring & Dormant Pipeline Win-Back Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** lead-recycling, win-back, pipeline-reactivation, lead-scoring, dormant-pipeline, buyer-intent, firmographic-triggers, re-engagement, crm-hygiene, hubspot, salesforce, marketo, clay, 6sense, bombora, b2b-saas, revenue-operations, closed-lost

## Overview

This prompt builds an AI-driven reactivation scoring system that transforms dormant leads and closed-lost opportunities into a predictable second-chance pipeline engine. Use it when your CRM holds thousands of disqualified or cold records that receive no systematic attention, when closed-lost opportunities sit untouched after 90 days, or when your marketing team generates net-new leads while ignoring the 3–10x more revenue potential already in your database. This engine produces a complete reactivation architecture: a multi-signal dormancy scoring model, a tiered win-back campaign system triggered by firmographic and behavioral changes, autonomous re-engagement sequences calibrated to original disqualification reason, and an ROI measurement framework proving the revenue contribution of database reactivation within one quarter.

## Quick Copy-Paste Version

You are a senior B2B SaaS revenue operations strategist specializing in CRM lifecycle management and dormant pipeline reactivation. My company sells [PRODUCT — e.g., AI-powered contract lifecycle management software] to [ICP — e.g., General Counsel and VP Legal at mid-market and enterprise companies with 500–5,000 employees]. We have [CRM PLATFORM — e.g., Salesforce] with approximately [DATABASE SIZE — e.g., 28,000 contacts and 4,200 closed-lost opportunities] accumulated over [TIMEFRAME — e.g., 4 years]. Our average ACV is [ACV — e.g., $42,000] and our sales cycle is [CYCLE — e.g., 3–5 months].

Build a complete lead reactivation architecture. Produce the following:

1. **DORMANCY SCORING MODEL** — Design a 100-point reactivation readiness score. Specify which signals increase the score (firmographic changes like new funding, headcount growth, new leadership hire; behavioral signals like website return visits, content re-engagement, product trial activity; intent data spikes from 6sense or Bombora; technographic changes like adoption of complementary tools; timing signals like elapsed time since disqualification), which signals decrease the score (company contraction, competitive displacement confirmed, contact departed), and at what score threshold each tier (Low/Medium/High/Urgent) triggers an automated reactivation workflow.

2. **SEGMENTATION BY DISQUALIFICATION REASON** — Define reactivation strategies for the 6 most common closed-lost and disqualification scenarios: (a) Budget/timing — not now, revisit in 6–12 months; (b) Competitor chosen — now track for churn or dissatisfaction signals; (c) No champion — contact left, now find replacement; (d) Feature gap — product didn't meet requirements, now monitor for release of relevant features; (e) Internal build decision — track progress signals that suggest project is behind or abandoned; (f) No response / went dark — re-engage with pattern interrupt. For each scenario, specify the reactivation trigger, the first-touch message strategy, and the sequence length.

3. **REACTIVATION CAMPAIGN ARCHITECTURE** — Design a 3-tier campaign system: Tier 1 (score 75–100, Urgent): 1:1 personalized outreach from AE or SDR within 24 hours of trigger, AI-drafted message referencing the original disqualification reason and the new signal; Tier 2 (score 50–74, High): automated 5-touch multi-channel sequence over 21 days; Tier 3 (score 25–49, Medium): low-touch nurture re-entry with monthly touchpoints until score increases. For each tier, specify exact channel mix, message framing, and suppression rules.

4. **TRIGGER SIGNAL PLAYBOOK** — Identify the 12 most valuable reactivation triggers and for each specify: the data source, how to detect it automatically, the recommended response action, and an example first-touch message. Triggers must include: funding round announcement, executive hiring (new VP/C-suite in buyer role), competitor contract expiry estimate, product feature release matching original gap, intent data spike above threshold, website return visit to high-intent pages, contact job change to new ICP company, tech stack change detected via Clearbit or BuiltWith, LinkedIn engagement with company content.

5. **ROI MEASUREMENT FRAMEWORK** — Define the 8 metrics that prove reactivation program value to leadership: reactivation rate by tier, reactivation pipeline generated ($), average days from trigger to reactivation, win rate of reactivated opportunities vs. net-new (benchmark: typically 20–35% higher), ACV difference (benchmark: reactivated deals typically 15–25% larger due to relationship equity), CAC comparison, cost per reactivated opportunity, and contribution as a percentage of total pipeline.

Output as an implementation-ready reactivation playbook I can begin executing in [CRM PLATFORM] within 4 weeks.

## Advanced Customizable Version

### ROLE & CONTEXT

You are an elite B2B SaaS revenue operations architect who has built lead reactivation systems for companies at every growth stage — from $8M ARR Series B startups to $300M ARR public companies. You have personally designed programs that recovered 15–40% of closed-lost pipeline within 12 months of implementation, generating pipeline that converts at 20–40% higher rates than equivalent net-new leads because the relationship equity, contextual understanding, and sales process groundwork already exist.

You understand the seven reasons most reactivation programs fail:

- **Spray-and-pray re-engagement**: Marketing sends a generic "checking back in" email blast to every closed-lost record simultaneously. The result is low engagement, damaged sender reputation, and sales frustration when SDRs receive "we already rejected you twice" responses from prospects who received three automated re-engagement emails in a week.
- **No trigger logic**: Reactivation attempts happen on a fixed calendar schedule (every 90 days) rather than in response to signals that indicate genuine reactivation readiness. A company that raised a $50M Series B two weeks ago and hired a new CFO should receive an outreach today — not in 73 days when the quarterly blast goes out.
- **Disqualification reason blindness**: The re-engagement message makes no reference to why the relationship ended or what has changed. A prospect who said "we chose Competitor X" receives a message about your product features — with zero acknowledgment that the competitive situation may have evolved or that you've shipped capabilities that address what Competitor X was chosen for.
- **No firmographic change monitoring**: The ICP company that was 200 employees and below your enterprise-tier threshold has now grown to 650 employees and raised a Series C. Nothing in the CRM flags this. The closed-lost record sits dormant while the company passes through your ideal buying window.
- **AE ownership limbo**: Closed-lost records technically belong to the AE who lost the deal, who has no financial incentive to reactivate them and who actively resents marketing campaigns that "mess with their accounts." Without a clear reactivation ownership model and compensation alignment, most programs die in internal politics before they produce a dollar.
- **Contact churn blindness**: 30–40% of B2B buyers change jobs within 18 months of a disqualification. The contact who said no may now be at a different company — an ICP company where they have buying authority and relationship equity with you. The "closed-lost" record should trigger a new pipeline opportunity at the contact's new employer. Most CRM configurations make this invisible.
- **No suppression from active sales motion**: The reactivation program re-engages a prospect exactly when the AE is in late-stage conversations with them for a different product line, damaging the relationship and the deal.

You design reactivation architectures around five principles:

- **Signal primacy over calendar cadence**: Reactivation readiness is determined by changes in the buyer's world, not by elapsed time. A closed-lost record that has sat dormant for 18 months with zero new signals deserves exactly zero proactive outreach. A record that has sat dormant for 8 months but triggered a funding announcement, a new VP of Operations hire, and two return visits to your pricing page deserves an AE call within 48 hours. Calendar-based reactivation ignores everything the market is telling you.
- **Disqualification context integrity**: Every reactivation touchpoint must reference the original disqualification reason and the specific signal that suggests the situation has changed. "When we spoke in March, you mentioned budget wasn't available until Q3 — I noticed you raised your Series B last week and wanted to reconnect" is 6–10x more likely to generate a response than "I wanted to touch base and see if things have changed." The context is your competitive advantage.
- **Contact continuity across employers**: A B2B buyer who has worked with your sales team, understood your product, and evaluated your solution carries enormous relationship equity when they move to a new company. A CRM architecture that doesn't actively track and follow ICP contacts across employer changes is leaving high-conversion pipeline in the ground.
- **Ownership clarity before launch**: Reactivation programs require a defined handoff model — who owns re-engaged leads (marketing or sales), at what score threshold they transfer, whether original AE relationship is honored or reassigned, how commission is allocated for reactivated closes, and who is accountable for follow-up SLA. Without this alignment, the most sophisticated scoring model in the world produces orphaned opportunities.
- **Asymmetric patience by tier**: Not all dormant records deserve the same investment. A $250K closed-lost opportunity at a Fortune 500 company that was lost six months ago to a competitor deserves dedicated AE attention and a custom reactivation strategy. A $15K SMB opportunity that went dark after one discovery call deserves a three-touch automated sequence. Resource allocation must match reactivation ROI potential.

You understand the data infrastructure requirements: reactivation programs depend on CRM data that is often incomplete, inconsistent, or siloed. The disqualification reason field is frequently blank or populated with vague reasons ("not a fit") that contain no actionable intelligence. Contact records may belong to ex-employees. Account records may reflect outdated firmographic data. Your architecture must include data quality remediation as the first phase, not an afterthought.

---

### COMPANY & DATABASE CONTEXT

**Company Profile:**
- Company name: [e.g., Argent Contract AI — AI-powered contract lifecycle management for mid-market legal and procurement teams]
- Product: [e.g., Automates contract drafting, review, negotiation, and renewal tracking — reduces contract cycle time by 65% and eliminates 90% of manual legal review for standard agreements]
- ICP: [e.g., General Counsel, VP Legal, Chief Legal Officer, and VP Procurement at companies with 500–5,000 employees across technology, financial services, and professional services; typical ACV $35,000–$75,000; 3–5 month sales cycle]
- CRM platform: [e.g., Salesforce Sales Cloud]
- Marketing automation platform: [e.g., HubSpot Marketing Hub Enterprise]
- Intent data vendor: [e.g., 6sense Revenue AI or Bombora Company Surge]
- Contact intelligence/enrichment: [e.g., Clearbit, Clay, Apollo, or ZoomInfo]
- Social listening / job change tracking: [e.g., LinkedIn Sales Navigator, UserGems, or Champify]

**Database Snapshot:**
- Total contacts in CRM: [e.g., 28,400]
- Total accounts in CRM: [e.g., 6,200]
- Closed-lost opportunities (all time): [e.g., 4,180]
- Disqualified leads / MQLs marked as not qualified: [e.g., 9,600]
- Contacts with no activity in 12+ months: [e.g., 18,000]
- Estimated percentage of records with complete disqualification reason documented: [e.g., 35%]
- Average time since most recent contact with dormant records: [e.g., 16 months]

**Disqualification Reason Breakdown (estimate as best as possible):**
- Budget/timing: [e.g., 38%]
- Chose competitor: [e.g., 22%]
- Feature gap: [e.g., 14%]
- No champion / contact went dark: [e.g., 12%]
- Internal build decision: [e.g., 8%]
- Not ICP fit (company too small, wrong vertical): [e.g., 6%]

**Current State of Reactivation:**
- Existing reactivation programs: [e.g., "None — AEs occasionally reach out to specific closed-lost accounts manually, but there is no systematic program and no data on results"]
- How closed-lost records are currently managed: [e.g., "Records are marked closed-lost with a reason code, then removed from all active sequences and largely forgotten. AEs keep personal track of their most important closed-losts but there is no marketing program touching these records"]
- Sales team's stance on marketing-touched reactivation: [e.g., "Sales leadership is supportive in principle but AEs are protective of their accounts and concerned about marketing 'spamming' prospects they have relationships with"]
- Intent data capabilities: [e.g., "We have 6sense but use it primarily for net-new prospecting, not for monitoring existing closed-lost records"]

**Reactivation Program Goals:**
- Primary goal: [e.g., "Generate $2M in reactivated pipeline within 12 months from a $0 baseline, without increasing headcount or marketing budget"]
- Secondary goal: [e.g., "Build a systematic program with AE buy-in that runs autonomously and requires less than 4 hours per week of marketing management time"]
- Constraints: [e.g., "Cannot re-engage records marked as 'Do Not Contact.' Must preserve AE relationship ownership for any account where the original AE is still at the company. Must not conflict with active sales sequences."]

**Technical Capabilities:**
☐ CRM with custom fields for disqualification reason, reactivation score, last signal date
☐ Marketing automation platform with behavioral tracking and dynamic list membership
☐ Intent data monitoring for named accounts (6sense, Bombora, G2)
☐ Contact job change tracking (UserGems, Champify, LinkedIn Sales Navigator)
☐ Data enrichment/firmographic refresh (Clearbit, ZoomInfo, Apollo, Clay)
☐ Technographic data (BuiltWith, Clearbit, Datanyze)
☐ Funding/news monitoring (Crunchbase, Owler, news APIs)
☐ CRM-to-MAP bidirectional sync
☐ Slack or Teams alerts for Urgent-tier reactivation triggers

---

### OBJECTIVES

Produce a complete, implementation-ready reactivation architecture with the following outputs:

**Output 1: Reactivation Readiness Score Model (0–100)**

Design a weighted scoring model. For each signal below, specify the exact point value (+/-), data source, and how to detect it automatically:

*Positive signals (add points):*
- Company raised funding round (Series A/B/C/D, amount by tier)
- New executive hire in buyer persona role (C-suite: +25, VP: +20, Director: +12)
- Company headcount growth above threshold (>20% YoY: +15, >40% YoY: +22)
- Intent data spike: topic cluster match above 80th percentile (Bombora/6sense)
- Return visit to high-intent pages: pricing, integrations, security/compliance, case studies
- Contact returned to email engagement (opened 2+ emails in 14 days after dormancy)
- Competitive technographic trigger: added a complementary tool that pairs with your product
- Estimated competitor contract expiry window (based on known average contract length)
- Product feature release that addresses the original disqualification reason (feature gap closes)
- Original contact job change to a new ICP company (triggers new account opportunity)
- News trigger: company acquisition target, IPO filing, major expansion announcement
- LinkedIn engagement: liked or commented on company or executive content

*Negative signals (subtract points):*
- Company headcount decline >15%
- Confirmed competitive displacement with multi-year contract (known competitor lock-in)
- Contact listed as DNC in CRM
- Company entered bankruptcy proceedings or was acquired out of ICP
- Industry-level downturn signal (sector-specific, e.g., fintech regulatory freeze)

*Score thresholds and actions:*
- 0–24 (Dormant): Monthly nurture newsletter only, no direct outreach
- 25–49 (Warm): Enter low-touch nurture re-engagement sequence (automated)
- 50–74 (Hot): Automated multi-touch sequence with SDR awareness alert
- 75–100 (Urgent): Immediate AE/SDR alert via Slack; AI-drafted personalized outreach within 24 hours

**Output 2: Disqualification Reason Reactivation Playbooks**

For each of the 6 primary disqualification reasons, design:
- Primary reactivation trigger (the most reliable signal that the situation has changed)
- Secondary trigger (the second-best signal)
- First-touch message strategy: what angle to lead with, what NOT to say, how to reference the original context without being awkward
- Sequence structure: number of touches, channel mix (email, LinkedIn, phone, direct mail), and message evolution across the sequence
- Hard stop criteria: when to give up and re-disqualify rather than continuing to invest

**Output 3: Campaign Architecture by Reactivation Tier**

*Urgent Tier (score 75–100): 1:1 AE/SDR-Assisted Reactivation*
- Trigger to outreach SLA: maximum 24 hours
- Alert format: Slack message to AE + BDR with signal summary, original opportunity context, and AI-drafted first touch for review/send
- Message framework: acknowledge original context → name the specific signal → reframe value without re-pitching → low-friction CTA (15-minute call, not demo)
- Escalation if no response: 3-touch sequence over 10 days before dropping to Hot tier

*Hot Tier (score 50–74): Automated Multi-Touch Sequence*
- Total sequence length: 5 touches over 21 days
- Channel mix: 3 emails + 1 LinkedIn connection/message + 1 direct mail (for ACV >$30K accounts)
- Touch 1 (Day 1): Email — signal-specific re-engagement ("noticed X, wanted to share Y")
- Touch 2 (Day 5): LinkedIn — connection request or comment on their recent activity
- Touch 3 (Day 9): Email — a single new insight, report, or case study relevant to their disqualification reason
- Touch 4 (Day 14): Email — social proof from a company similar to theirs that was in a similar situation
- Touch 5 (Day 21): Email — explicit "closing the loop" message with easy opt-back-in
- SDR notification at Touch 3 if email opens exceed 2 without click

*Warm Tier (score 25–49): Automated Nurture Re-Entry*
- Re-entry into standard nurture program with suppression of irrelevant content tracks
- Monthly newsletter with content personalized to their original disqualification reason and industry
- Score monitoring: if score increases to Hot, exit nurture and enter Hot sequence automatically
- Annual "are you still in role?" data refresh email for contacts not seen on LinkedIn in 6+ months

**Output 4: Contact Job Change Reactivation Playbook**

Design a specific sub-program for the highest-ROI reactivation scenario — a contact who previously evaluated and understood your product, but left the account before a decision was made or after the loss, and is now at a new ICP company:

- How to detect: UserGems / Champify / LinkedIn Sales Navigator job change alerts
- Qualification criteria: new company must meet ICP criteria (size, vertical, tech stack)
- CRM action: create new Contact at new Account, link original opportunity for context, create new net-new opportunity with "recycled contact" source tag
- First-touch message: acknowledge shared history without implying they're being followed, lead with new value framing, reference what's changed since you last spoke
- Success metric: compare win rate of recycled-contact opportunities vs. cold-start opportunities (benchmark: 2–4x higher win rate)

**Output 5: Implementation Roadmap**

Week 1–2: Data quality sprint
- Audit disqualification reason field: identify % blank, % using vague codes, % with actionable detail
- Standardize disqualification reason taxonomy to 6–8 categories
- Enrich top 500 closed-lost accounts with current firmographic data using Clay/ZoomInfo
- Define DNC vs. eligible-for-reactivation criteria; tag all records

Week 3–4: Score model build and alert system
- Build custom Reactivation Score field in CRM
- Configure intent data feed from 6sense/Bombora for closed-lost accounts
- Set up job change tracking for all contacts in closed-lost opportunities
- Build Slack alert workflow for Urgent-tier triggers
- Create email templates for each disqualification reason scenario

Month 2: Pilot launch
- Launch Urgent tier manually: 20–30 highest-scoring records, AE-assisted outreach
- Launch Hot tier automated sequence for records 50–74
- Warm tier nurture re-entry for records 25–49
- Baseline all metrics: volume, response rates, meetings booked, pipeline created

Month 3+: Optimize and scale
- Review sequence performance by disqualification reason; kill or revise underperforming sequences
- Expand to full eligible database
- Report reactivation pipeline contribution monthly to leadership

## Example Input/Output

**Company Profile:**
Argent Contract AI — AI-powered contract lifecycle management for mid-market and enterprise legal teams. ACV: $48,000 average. Salesforce + HubSpot + 6sense + UserGems. CRM contains 3,800 closed-lost opportunities from the past 3.5 years.

**Sample Record:**
- Account: Meridian Financial Partners (independent RIA, 900 employees, Boston)
- Original opportunity: $52,000 ACV, closed-lost 14 months ago
- Disqualification reason: "Chose LegalSifter — faster implementation timeline, price point was $12K lower"
- Original champion: Sarah Chen, VP Legal (still at company per LinkedIn)
- Current data: Company raised $85M Series C 6 weeks ago; added 200 employees in past 4 months; 6sense shows 78th percentile intent on "contract automation" and "CLM software" topics; Sarah Chen engaged with our CEO's LinkedIn post last week

**Reactivation Score Calculation:**
- Series C funding: +25
- New VP hire (no, same champion, but retained): 0
- Headcount growth >20%: +15
- 6sense intent spike (78th percentile): +18
- Contact LinkedIn engagement: +8
- Return website visit: not yet detected — 0
- Estimated competitor contract expiry (14-month lock-in): +12
**Total: 78 — Urgent Tier**

**AI-Drafted First Touch (for AE review/send, sent within 24 hours of trigger):**

Subject: Meridian's Series C + where things stand on CLM

Sarah —

Congratulations on the $85M raise — impressive momentum, especially for a firm growing this quickly (I saw you're approaching 900 employees now).

When we spoke last year, the decision came down to timeline and price, and LegalSifter made sense for where Meridian was at the time. A lot has changed since then — both for Meridian (scale and complexity clearly increasing) and for us (we've reduced average implementation to 6 weeks and restructured our mid-market pricing).

I'm not assuming the situation has changed, but given the growth you're navigating, I wanted to reconnect. Would a 20-minute conversation be worthwhile to see if things are different now?

**[AE Name]**

---

**Outcome after 30-day sequence:**
Sarah responded to Touch 1 within 3 days. Meridian was frustrated with LegalSifter's renewal support and had been internally discussing alternatives. Meeting booked within 7 days, opportunity re-opened at $67,000 ACV (company has grown; expanded scope). Closed in 11 weeks. This account would have been invisible without the reactivation program.

## Success Metrics

**Program-level KPIs (report monthly to marketing and sales leadership):**
- **Reactivation pipeline generated ($)**: total ARR of opportunities created from previously dormant records; target $2M–$5M annually per 5,000 eligible records
- **Reactivation rate by tier**: % of records in each tier that convert to active opportunity; benchmarks — Urgent: 18–30%, Hot: 8–15%, Warm: 2–5%
- **Trigger-to-outreach SLA compliance**: % of Urgent-tier triggers actioned within 24 hours; target >90%
- **Recycled-contact win rate vs. cold-start win rate**: target 20–40% higher win rate for recycled contacts

**Sequence performance KPIs (report weekly, optimize monthly):**
- **Email open rate by sequence touch**: benchmark >35% for signal-specific messages; <20% indicates wrong trigger or wrong message angle
- **Response rate by disqualification reason**: which reason-specific playbooks are working; kill anything <3% response rate after 50+ sends
- **Meeting booked rate**: from first contact to meeting; benchmark 6–12% for Urgent, 3–8% for Hot
- **Days from trigger to meeting**: should decrease over time as sequence optimization improves

**Revenue impact KPIs (report quarterly to CMO and CFO):**
- **Reactivation pipeline as % of total marketing-sourced pipeline**: target 8–15% within 12 months
- **CAC of reactivated opportunities vs. net-new**: reactivated CAC should be 60–80% lower due to existing relationship equity
- **ACV of reactivated deals**: typically 15–25% higher than equivalent net-new due to expanded scope at companies that have grown
- **Payback period of reactivation program investment**: should be <1 quarter if database is >2,000 eligible records

## Related Prompts

- [AI-Powered B2B SaaS Predictive Lead Scoring Architecture & Revenue Qualified Pipeline Management Intelligence Engine](./AI-Powered-B2B-SaaS-Predictive-Lead-Scoring-Architecture-&-Revenue-Qualified-Pipeline-Management-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Buying Committee Scoring & Account-Level MQA Pipeline Architecture Revenue Intelligence Engine](./AI-Powered-B2B-SaaS-Buying-Committee-Scoring-&-Account-Level-MQA-Pipeline-Architecture-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Email Segmentation Architecture & Dynamic Contact Intelligence Revenue Engine](../Email-Marketing/AI-Powered-B2B-SaaS-Email-Segmentation-Architecture-&-Dynamic-Contact-Intelligence-Revenue-Engine.md)
- [AI-Powered B2B SaaS Third-Party Intent Data Orchestration & Buyer Signal Activation Revenue Intelligence Engine](../Demand-Generation-Operations/AI-Powered-B2B-SaaS-Third-Party-Intent-Data-Orchestration-&-Buyer-Signal-Activation-Revenue-Intelligence-Engine.md)

## Integration Tips

**Salesforce:**
- Create a custom field `Reactivation_Score__c` (number, 0–100) on the Contact and Lead objects
- Build a custom Report Type joining Opportunities (closed-lost) → Contacts → Account activity to surface all trigger signals in one view
- Use Salesforce Flows to auto-update reactivation score when trigger conditions are met and route Urgent-tier records to a "Reactivation Queue" assigned to RevOps for AE routing

**HubSpot:**
- Create a custom contact property `Reactivation Readiness Score` and a dynamic smart list called "Reactivation — Urgent Tier" (score ≥75) that auto-enrolls contacts into the Urgent outreach notification workflow
- Build separate email sequences in HubSpot Sales for each disqualification reason, using contact property tokens to dynamically insert the original disqualification context
- Use HubSpot's `Last Activity Date` and `Original Source` properties to identify the original touchpoints for personalization

**Clay:**
- Build a Clay table pulling all closed-lost accounts with a waterfall enrichment flow: Clearbit → Apollo → ZoomInfo for firmographic refresh; flag accounts where headcount has grown >20% since original close-lost date
- Add a column running a Perplexity or news API lookup for funding announcements and M&A activity in the past 90 days
- Connect Clay to Slack via Zapier to push high-score trigger alerts to the AE channel

**6sense or Bombora:**
- Sync your closed-lost account list as a named-account segment in 6sense; monitor for intent spikes on your primary topic clusters
- Set a 6sense alert when any closed-lost account exceeds 70th percentile intent; push alert to Salesforce as a Task for the account owner and to the CRM's reactivation score field

**UserGems or Champify:**
- Configure to track all contacts in closed-lost opportunities; set alerts when they move to a new company that matches ICP criteria (industry, size, tech stack)
- Route job-change alerts to a dedicated Salesforce queue "Recycled Contact — New Account" for SDR follow-up within 5 business days

**Zapier / Make (Integromat):**
- Build a multi-step Zap: Trigger = 6sense alert OR UserGems job change → Action = update Salesforce reactivation score → Condition = if score ≥75 → Action = send Slack alert to AE and BDR with AI-drafted message using OpenAI API

## Troubleshooting

**Problem: AEs resist marketing touching their closed-lost accounts and refuse to act on Urgent-tier alerts.**
Solution: Solve the political problem before the technical one. Run a 30-day pilot with 2–3 supportive AEs who get full credit for any reactivated close. Produce a one-page case study showing pipeline and revenue generated per AE from the pilot. Present to sales leadership. Then renegotiate the ownership model — offer AEs first right of refusal on Urgent-tier records for 48 hours, after which SDRs take over. The competitive element (AEs seeing each other generate easy pipeline) typically drives voluntary adoption within 60 days.

**Problem: The reactivation score is triggering Urgent-tier alerts for accounts that are obviously not ready (false positives undermining AE trust).**
Solution: The most common cause is an over-weighted single signal. A company appearing on a generic funding news list triggers a score of 80 even though the funding was for an unrelated division and the original contact left the company. Add a contact-validity gate: if the original contact is no longer at the company AND a replacement hasn't been identified, reduce score by 30 regardless of company signals. Also add a "manual disqualification confirmed" flag that freezes score updates for records where a human reviewer has confirmed reactivation is not appropriate (e.g., permanent competitive displacement, acquisition out of ICP).

**Problem: 60–70% of closed-lost records have no usable disqualification reason, making personalized reactivation impossible.**
Solution: Run a data remediation sprint before launch. Export all closed-lost opportunities with no reason or vague reasons (e.g., "lost", "no response") to a Clay table and use an AI enrichment column to infer probable disqualification reason from deal notes, email snippets, and last activity type. For the remaining unclassifiable records, apply a "reason unknown" sequence that leads with curiosity rather than assumed context: "We've been in touch before — I'd love to understand what's changed in how [Company] is thinking about [problem category]." Treat data remediation as a one-time investment before launch; enforce disqualification reason as a required field for all new closed-lost records going forward.

## Version History
- v1.0: Initial creation (auto-generated)
