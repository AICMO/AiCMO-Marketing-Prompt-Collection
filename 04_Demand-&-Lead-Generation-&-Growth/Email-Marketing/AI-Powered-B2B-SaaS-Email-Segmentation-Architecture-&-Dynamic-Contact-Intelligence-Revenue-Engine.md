# AI-Powered B2B SaaS Email Segmentation Architecture & Dynamic Contact Intelligence Revenue Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** email-marketing, segmentation, personalization, lead-scoring, behavioral-triggers, dynamic-lists, hubspot, marketo, salesforce-marketing-cloud, revenue-operations, b2b-saas, contact-intelligence, first-party-data

## Overview

This prompt builds a comprehensive AI-driven email segmentation architecture that moves beyond basic demographic splits to create living, behavioral-signal-driven contact intelligence — turning your email list into a precision instrument that delivers the right message to the right person at exactly the right moment. Use it when your email program treats all contacts the same, when open rates vary wildly across the list with no clear explanation, when unsubscribes are climbing, or when you're sending 5,000 emails per week to get 40 MQLs and suspect you're leaving 60 more on the table by failing to segment intelligently. This engine produces a complete segmentation architecture: 12–18 dynamic contact segments, behavioral signal triggers, suppression logic, progressive profiling strategy, and a measurement framework that proves the revenue impact of better segmentation within 60 days.

## Quick Copy-Paste Version

You are a senior B2B SaaS email marketing strategist specializing in contact segmentation and behavioral intelligence. My company sells [PRODUCT — e.g., AI-powered procurement automation software] to [ICP — e.g., VP Procurement and CPOs at mid-market and enterprise manufacturers with $200M–$2B revenue]. We use [PLATFORM — e.g., HubSpot Marketing Hub Enterprise] and have [LIST SIZE — e.g., 14,000 opted-in contacts] with [ACTIVE PERCENTAGE — e.g., roughly 35% opening any email in the last 90 days].

Design a complete email segmentation architecture. Produce the following:

1. **SEGMENTATION HIERARCHY** — Define 3 tiers of segmentation (broad demographic, behavioral engagement, intent/lifecycle stage). For each segment: the defining criteria, estimated size as a percentage of list, recommended email frequency, and what type of content each segment should receive. Include suppression rules for contacts who should NOT receive emails at this time.

2. **BEHAVIORAL SIGNAL MAP** — Identify the 15 most important behavioral signals in my marketing stack (website visits, email engagement, content downloads, product trial, webinar attendance, intent data, sales activity) and specify exactly how each signal should change a contact's segment membership or trigger an automated campaign.

3. **DYNAMIC LIST ARCHITECTURE** — Design the specific list rules for the 10 highest-priority dynamic segments. For each: the HubSpot/Marketo/Salesforce enrollment criteria, update frequency, estimated list size, and a plain-English description of who is in this segment and why they matter.

4. **PERSONALIZATION-BY-SEGMENT PLAYBOOK** — For each tier-1 segment, specify: the email subject line approach, content type and length, CTA style, send frequency, and one example subject line that would resonate specifically with this segment versus a generic list blast.

5. **PROGRESSIVE PROFILING STRATEGY** — Design a plan to fill segmentation gaps over time: what data fields are missing that would improve segmentation quality, how to collect them without a form (behavioral inference), and where to use progressive forms to collect the rest without creating friction.

Output as a complete segmentation playbook ready to implement in [PLATFORM] within 3 weeks.

## Advanced Customizable Version

### ROLE & CONTEXT

You are an elite B2B SaaS email marketing architect who has designed contact intelligence systems for companies ranging from $10M ARR Series A startups to $500M ARR public SaaS companies. You have personally rebuilt email segmentation programs that improved email-to-pipeline conversion by 40–120% — not by increasing send volume, but by sending smarter: fewer emails to engaged segments, different messages to different stages, and near-zero emails to disengaged contacts destined to unsubscribe.

You understand the five segmentation failure modes that destroy B2B email performance:

- **Single-list syndrome**: All contacts receive the same email on the same day. The result: average open rates around 22% that mask the reality that 400 highly engaged contacts would have opened anything you sent, while 3,000 semi-engaged contacts opened nothing for six months. Treating them identically destroys deliverability, elevates unsubscribe risk, and dilutes your sender reputation with inbox providers.
- **Persona theater**: Segmentation that exists on paper (Healthcare segment, Financial Services segment, Enterprise segment) but whose criteria don't reflect actual buying behavior. The contact imported from a trade show 18 months ago who hasn't engaged since is still in "Healthcare — High Priority" because no one built re-engagement logic. This is demographic cosplay, not behavioral intelligence.
- **Static segmentation**: Segments built once and never updated. Contacts who converted to customers 6 months ago are still receiving prospect nurture emails. Contacts who just booked a demo are still receiving awareness content. The segment is what it was at import — not what it is today.
- **Signal blindness**: The marketing automation platform is capturing every website visit, email click, and content download — and none of it flows into segmentation logic. A contact who visited the pricing page three times this week and downloaded a competitive comparison guide is still in the same segment as someone who opened a newsletter 4 months ago and never returned.
- **Suppression neglect**: No rules exist to pause emails to contacts who just had a sales conversation, who are in an active deal, who recently unsubscribed and re-subscribed, or who are customers who should be in a different program. The result: sales complaints about marketing emailing their active prospects, and customer complaints about receiving prospecting emails.

You design segmentation architectures around four principles:

- **Behavioral primacy**: Recent behavior is always a stronger signal than static demographics. A contact at a $50M manufacturing company who visited the pricing page twice this week and downloaded two technical white papers is a higher-priority target than a contact at a $500M manufacturing company who filled in a trade show scan 14 months ago. Your segmentation must weight recency and intent over size and title.
- **Engagement-based frequency**: Send frequency should be inversely correlated with disengagement risk. Highly engaged contacts (opened in last 14 days, multiple clicks, progressing in lead score) can receive 3–4 emails per month without fatigue. Contacts who haven't opened in 60+ days should receive no more than 1 email per month — a specifically designed re-engagement message — before being suppressed entirely.
- **Stage-appropriate content**: The message to a contact who just entered your list from a paid search campaign is completely different from the message to a contact who attended your webinar last week, requested a demo, had a discovery call, and went quiet. Segmentation is the mechanism that ensures each contact receives content appropriate to where they are in their actual buying journey, not where you hope they are.
- **Revenue-anchored measurement**: Segmentation improvements are only meaningful if they produce more pipeline. Measure segmentation health not by open rate improvement but by MQL rate per segment, pipeline-per-email-sent by segment, and conversion rate differences between segmented and non-segmented programs. If a segmentation change doesn't improve pipeline contribution within 60 days, redesign it.

You understand the unique data constraints of B2B SaaS email marketing: many contacts have incomplete records (missing company size, title, or industry), behavioral data is often siloed across MAP, CRM, and website analytics tools, intent data from third-party vendors (6sense, Bombora, G2) needs to be mapped to contact-level triggers, and the sales team has relationships with contacts that marketing's segmentation rules must respect.

---

### COMPANY & PROGRAM CONTEXT

**Company Profile:**
- Company name: [e.g., Sourcify AI — AI-powered procurement automation for mid-market manufacturers]
- Product: [e.g., Automates the source-to-pay process, reducing procurement cycle time by 60% and delivering 12–18% cost savings on managed spend]
- ICP: [e.g., VP Procurement, CPO, and CFO at manufacturers with $200M–$2B revenue in North America and Western Europe; typical buying committee includes VP IT/CIO and CFO in addition to the procurement champion]
- ACV: [e.g., $55,000–$180,000/year; average 4.5-month sales cycle]
- Marketing automation platform: [e.g., HubSpot Marketing Hub Enterprise]
- CRM: [e.g., Salesforce Sales Cloud]
- Intent data vendor (if applicable): [e.g., 6sense Revenue AI for Enterprise]
- Total opted-in contacts: [e.g., 14,200]
- Contacts with complete ICP firmographic data (company size, industry, title): [e.g., 58%]
- Active contacts (opened any email in last 90 days): [e.g., 4,900 — 34% of list]
- Current program structure: [e.g., 1 general newsletter (weekly), 3 nurture tracks (awareness, consideration, decision), 4 behavioral triggers (content download, webinar registration, pricing page visit, demo request), 0 re-engagement programs]

**Current Segmentation State:**
- Existing segments: [e.g., By industry vertical (5 segments), by contact title (3 broad buckets), by deal stage (in HubSpot deal stage, not synced to contact segmentation)]
- Known segmentation gaps: [e.g., No behavioral engagement-based segments; no intent signal integration from 6sense; no suppression for contacts with active CRM opportunities; customers receive the same newsletter as prospects]
- Most common sales complaint about email marketing: [e.g., "Sales reps complain that marketing emails prospects the same week they're trying to close them, and the generic nurture content undercuts the customized sales conversation"]

**Priority Segmentation Goal:**
[Choose 1 primary goal — e.g., "Stop emailing the 65% of contacts who never engage and double down on the 35% who do — we'd rather send fewer, better emails" OR "Build segment-specific content tracks that increase MQL-to-SQL conversion by serving stage-appropriate content" OR "Fix the customer-vs-prospect segmentation so CS owns the customer email relationship and marketing owns only prospects"]

**Firmographic Fields Available in MAP/CRM (check which exist):**
☐ Company name | ☐ Industry/vertical | ☐ Company revenue/size | ☐ Employee count | ☐ Country/region | ☐ Technology stack (from Clearbit or similar) | ☐ Customer vs. prospect status | ☐ CRM deal stage | ☐ Lead source/first touch | ☐ Partner/channel flag

**Behavioral Fields Available (check which are tracked):**
☐ Email open history | ☐ Email click history | ☐ Website page visits | ☐ Specific page visits (pricing, case studies, careers) | ☐ Content downloads (gated asset) | ☐ Form submissions | ☐ Webinar registrations/attendance | ☐ Product trial/freemium usage | ☐ Lead score (if configured) | ☐ Third-party intent data (6sense/Bombora) | ☐ Live chat/sales conversation | ☐ CRM sales activity (calls, meetings)

---

### SEGMENTATION ARCHITECTURE REQUIREMENTS

**1. SEGMENTATION HIERARCHY**

Design a 3-tier contact segmentation system:

**Tier 1 — Engagement Status (applies to all contacts, updates dynamically)**

Design 5 mutually exclusive, collectively exhaustive engagement tiers based purely on email behavior and site activity. No contact should be in more than one Tier 1 segment at any time. Contacts automatically move between tiers as their behavior changes.

For each tier, specify:
- **Definition**: Exact criteria for membership (e.g., "Opened ≥1 email in last 14 days AND clicked ≥1 link in last 30 days")
- **Estimated percentage of typical B2B SaaS list at this engagement level**
- **Email frequency cap**: Maximum emails this tier should receive per month
- **Content strategy**: What type of content is appropriate for this tier (new research, product-focused, re-engagement, suppression)
- **Escalation/de-escalation logic**: What behavior moves a contact up or down a tier

Build these 5 engagement tiers:
- **Tier 1A — Champions**: Highest engagement; actively responding, clicking, possibly in sales process
- **Tier 1B — Engaged**: Regular openers; reading content; lead score growing
- **Tier 1C — Passive**: Occasional openers; not clicking; warming
- **Tier 1D — Dormant**: No opens in 60–120 days; at unsubscribe risk
- **Tier 1E — Reactivation Candidate**: No opens in 120+ days; should receive only a specific reactivation sequence before suppression

**Tier 2 — Buyer Journey Stage (overlays Tier 1; determines content type within the frequency cap)**

Design 5 mutually exclusive journey stages that determine what content a contact receives, regardless of their engagement tier. A Dormant contact in "Decision" stage gets a very different re-engagement email than a Dormant contact in "Awareness" stage.

For each stage, specify:
- **Stage definition**: Behavioral and firmographic signals that indicate this stage
- **Content imperative**: What this contact needs to hear (problem awareness, solution education, competitive comparison, social proof, business case, urgency)
- **Average time in stage** for your ICP
- **Exit trigger**: What moves a contact out of this stage to the next

The five stages:
- **Stage A — Awareness**: Problem-aware, not yet solution-aware; typically from paid search, content, events
- **Stage B — Education**: Solution-aware; researching categories; reading blogs, guides, case studies
- **Stage C — Consideration**: Evaluating vendors; comparing features; visiting pricing pages, reading reviews
- **Stage D — Decision**: Active evaluation; in a sales process or close to starting one; reading ROI calculators, requesting demos, comparing implementation requirements
- **Stage E — Customer/Post-Sale**: Converted customer who should be in a separate CS-owned track (suppressed from prospect marketing)

**Tier 3 — Persona/Vertical Overlay (refines content topic and voice within Tier 2)**

Design up to 6 persona or vertical overlays that affect tone, examples, and content topics — but NOT frequency or fundamental message. A "Consideration Stage — VP Procurement" contact gets the same business case email as a "Consideration Stage — CFO" contact, but the language, metrics, and examples are different.

For each overlay: the defining criterion (job title, industry, company size), the content adjustment required (language, examples, regulatory context, peer benchmark), and the minimum data completeness required to apply the overlay (what percentage of contacts in this overlay actually have the data needed to identify them?).

---

**2. BEHAVIORAL SIGNAL MAP**

Map the 15 most important behavioral signals available in this company's stack to specific segmentation and automation responses:

For each signal, specify in a table:

| Signal | Source System | Significance Level (1–5) | Segmentation Response | Automation Response |
|---|---|---|---|---|
| Pricing page visit (1 visit) | Website analytics | 3 — Moderate intent | Move to Stage C (Consideration) if currently in A or B | Enroll in "Pricing Interest" behavioral track with 3-email sequence |
| Pricing page visit (3+ visits in 7 days) | Website analytics | 5 — High intent | Move to Stage D (Decision); flag for BDR outreach | Alert assigned BDR/SDR; enroll in "High Intent" sequence; pause standard nurture |
| [Continue for all 15 signals] | | | | |

The 15 signals to map (customize for the company's stack):

*Email Engagement Signals:*
1. Email opened (1 email in last 7 days)
2. Email link clicked (any link, 1 click in last 7 days)
3. Email clicked 3+ times in 14 days (champion behavior)
4. No email opened in 60+ days (dormancy signal)
5. No email opened in 120+ days (reactivation candidate)

*Website Behavior Signals:*
6. Pricing page visit (1 visit)
7. Pricing page visit (3+ visits in 7 days)
8. Case study page visit (any)
9. Blog visit (1+ posts in 7 days — topic matters)
10. Career page visit (competitor or content signal — de-prioritize this contact)

*Content & Conversion Signals:*
11. Gated content download (awareness-stage asset)
12. Gated content download (decision-stage asset: ROI calculator, competitive guide, implementation checklist)
13. Webinar registered (upcoming event)
14. Webinar attended (live — high-value signal)
15. Demo request submitted (highest intent signal — hand to sales immediately)

*External / Third-Party Signals (if applicable):*
If intent data is available (6sense, Bombora, G2), add 3 additional signals:
16. Intent surge — buying stage keyword cluster (competitor comparison, pricing, review sites)
17. G2 profile review/competitive comparison page viewed
18. Previous customer of competitor (identified via enrichment)

For each signal: the system it lives in, the field/API that captures it, whether it's available in real-time or batch (daily/weekly sync), and the latency between the behavior and the segmentation response (should this happen within minutes, hours, or is a daily batch sync acceptable?).

---

**3. DYNAMIC LIST ARCHITECTURE**

Design the 10 highest-priority dynamic segments with exact enrollment criteria:

For each segment, provide:

**SEGMENT [N]: [Segment Name]**
- **Plain-English Description**: Who is in this segment and why do they matter?
- **Business Priority**: Why does this segment deserve its own treatment? What revenue opportunity does it represent?
- **Enrollment Criteria** (write exact logic for HubSpot/Marketo):
  - Include rules: [List all AND/OR conditions for inclusion]
  - Exclude rules: [List all suppression conditions]
- **Update Frequency**: Real-time / Hourly sync / Daily batch
- **Estimated Segment Size**: [% of total list]
- **Email Frequency**: [Maximum emails/month for this segment]
- **Content Focus**: [What should this segment receive?]
- **Handoff Rule**: [When/if does this segment trigger a sales notification or SDR task?]

Required segments to design (minimum):

1. **Hot Intent — This Week** (pricing page 2+ visits OR demo request OR decision-stage content in last 7 days; currently in open opportunity)
2. **High Engagement — No Sales Contact** (Champion engagement tier, no CRM opportunity created, no sales activity in last 30 days — marketing should be escalating these)
3. **Competitive Evaluation Active** (visited competitor comparison pages, downloaded competitive content, or triggered competitive intent via 6sense/Bombora in last 14 days)
4. **Webinar Attendees — Not Yet Converted** (attended a webinar in last 60 days, no demo request, no open opportunity)
5. **Content Downloaders — Decision Stage** (downloaded ROI calculator, implementation guide, or security/compliance documentation in last 30 days)
6. **Stalled Opportunities** (in CRM deal, no sales activity in 21+ days, marketing should provide air cover while sales reengages)
7. **Churned Customers — 6–18 Months** (customer who canceled 6–18 months ago; too early to have re-engaged naturally; eligible for win-back program)
8. **Dormant Engaged — Reactivation Window** (no opens in 90–150 days but previously had 60-day+ engaged history; different from never-engaged contacts)
9. **ICP Fit — Never Engaged** (strong firmographic match: right company size, industry, title; never opened an email; needs re-permission or different acquisition approach)
10. **Customer — Expansion Signal** (existing customer showing intent on upsell/add-on features via product usage data or website behavior)

For each segment: the exact HubSpot/Marketo syntax for the enrollment rule, the typical size as a percentage of a 14,000-contact list, and the expected conversion rate premium over a non-segmented blast to the same audience.

---

**4. PERSONALIZATION-BY-SEGMENT PLAYBOOK**

For the 5 most important segments (your choice based on revenue opportunity), design a complete content playbook:

For each segment:

**SEGMENT: [Name]**

*Subject Line Strategy:*
- Psychological frame that works for this segment: [e.g., peer comparison, consequence framing, question, specificity]
- Variables to personalize in subject: [Company name, job title, behavior referenced, industry-specific stat]
- 5 example subject lines (specific to this company's product and ICP):
  1. [Subject line] — Uses: [psychological frame]
  2. [Subject line] — Uses: [psychological frame]
  3. [Subject line] — Uses: [psychological frame]
  4. [Subject line] — Uses: [psychological frame]
  5. [Subject line] — Uses: [psychological frame]

*Email Body Strategy:*
- Opening hook approach: [Problem statement, peer insight, data point, direct question]
- Content length: [Ultra-short <100 words / Standard 150–250 words / Long-form 300–500 words]
- Social proof type: [Named customer logo, specific metric, industry peer story, analyst quote]
- CTA approach: [Low-friction ask / Medium ask / Direct demo request]
- Suppression condition: [When should this segment NOT receive this type of email?]

*Send Cadence:*
- Maximum emails per month: [Number]
- Recommended send days: [e.g., Tuesday and Thursday for decision-stage contacts; avoid Friday for awareness stage]
- Pause rule: [What sales activity should pause this segment's automated sends?]

*Full Email Example (write one complete email for this segment):*
Subject: [Example subject line — specific, not templated]
Preview text: [Preview text that continues the thought from subject]

[Email body — 150–250 words, realistic product and company context, with embedded social proof and a specific CTA]

[Signature block recommendation]

---

**5. PROGRESSIVE PROFILING STRATEGY**

Design a 90-day plan to fill segmentation data gaps:

**Step 1 — Data Audit (Week 1)**

Produce a data completeness table:

| Field | Required for Segmentation | Current Completeness | Gap Impact | Priority to Fill |
|---|---|---|---|---|
| Job title | Tier 3 persona overlay | 61% | High — missing title = generic content for 39% of list | P1 |
| Company revenue | ICP fit scoring | 44% | High — can't score ICP fit without it | P1 |
| Industry vertical | Tier 3 vertical overlay | 73% | Medium — can infer from domain enrichment | P2 |
| [Continue for 8–10 fields] | | | | |

**Step 2 — Behavioral Inference Engine (Weeks 2–4)**

For each high-priority field, design the behavioral inference logic that fills the gap without asking:

*Inferring Job Function from Behavior:*
- Contact visits DevTools/API documentation pages repeatedly → infer: technical buyer (Developer/IT/Engineering function) → apply Technical Persona overlay
- Contact downloads CFO-specific content or clicks on "financial impact" language repeatedly → infer: economic buyer (Finance function) → apply Economic Buyer overlay
- [Continue for 4–5 behavioral inference rules]

*Inferring Buyer Stage from Content Consumption Sequence:*
- Downloaded >2 thought leadership pieces + no product page visits → infer: Awareness stage
- Downloaded 1 thought leadership + visited product page + downloaded case study → infer: Education/Consideration stage
- Visited pricing 2+ times + downloaded ROI calculator → infer: Decision stage

*Inferring Industry from Domain:*
Specify the enrichment tool (Clearbit, Apollo, ZoomInfo), the API call logic, and how the inferred industry value flows into HubSpot/Marketo without overwriting manually entered data.

**Step 3 — Progressive Form Strategy (Weeks 3–6)**

Design 3 progressive form scenarios:

1. **Content Download Gate** — Contact who already has name + email in system and downloads a gated asset: ask 1 additional question. Which question to ask based on what data is missing (prioritized list).
2. **Webinar Registration** — 3-field progressive form that asks a segmentation-relevant question (company size, current solution, primary challenge) beyond name/email/company.
3. **Demo Request Form** — Opportunity to collect 2 deep qualification fields (company revenue, current tool, decision timeline) while the intent is highest.

For each form: the exact field options, the branching logic that shows the most relevant missing field for each existing contact profile, and how HubSpot/Marketo progressive profiling feature implements this.

**Step 4 — Data Enrichment Automation (Weeks 4–8)**

Specify the enrichment vendor and workflow:
- Enrichment trigger: Contact created (new lead) → immediate enrichment call → populate company size, industry, tech stack, LinkedIn profile
- Enrichment cost model: [e.g., $0.05/enrichment at Clearbit scale; calculate monthly cost at this list growth rate]
- Enrichment confidence threshold: Only apply enriched data if confidence score ≥85%; flag below-threshold enrichments for manual review
- Enrichment refresh schedule: Re-enrich contacts annually (job changes, company changes) — specify which field changes should trigger segment re-assignment

---

### SUPPRESSION & PREFERENCE FRAMEWORK

**Universal Suppression Rules (contacts who should never receive standard nurture):**

Design 8 suppression logic rules that apply across all segments:

| Suppression Rule | Criteria | Duration | Override Conditions |
|---|---|---|---|
| Active Sales Opportunity | CRM Deal Stage ≠ Closed and Created Date ≤ 90 days | Until deal is Closed Won or Closed Lost | Sales rep manually approves marketing campaign for their deal |
| Post-Demo — Sales Process Active | Demo Attended ≤ 14 days + CRM Contact Activity (call or meeting) ≤ 14 days | 14 days post-demo | None — no marketing email during active sales period |
| Unsubscribe Grace Period | Recently re-subscribed after previous unsubscribe | 30 days post re-subscription | None |
| Email Harassment Risk | 5+ emails sent in last 7 days from any program | Until 7-day count resets | None |
| [4 additional suppression rules] | | | |

**Preference Center Architecture:**

Design a marketing preference center that allows contacts to self-segment rather than unsubscribing:

- Topic preferences: [e.g., Product updates, Industry research, Events, Best practices — let contacts select the content types they want]
- Frequency preferences: [Monthly digest / Bi-weekly / As-published]
- Channel preferences: [Email only / Email + LinkedIn retargeting / Email + direct mail for high-value accounts]

The preference center reduces unsubscribes by 25–40% in most B2B SaaS programs by giving contacts control over volume without exiting the list entirely. Design the HubSpot/Marketo implementation with specific subscription type configuration.

---

### OUTPUT FORMAT

Deliver the complete Email Segmentation Architecture in this structure:

1. **ARCHITECTURE OVERVIEW** — 1-page visual map of all segments, their relationships, and how contacts flow between them
2. **ENGAGEMENT TIER DEFINITIONS** — 5 tiers with exact criteria, frequency caps, and content strategies
3. **BEHAVIORAL SIGNAL MAP** — 15 signals mapped to segmentation and automation responses
4. **DYNAMIC LIST SPECIFICATIONS** — 10 priority segments with exact enrollment criteria
5. **PERSONALIZATION PLAYBOOKS** — Full content strategy and email examples for top 5 segments
6. **PROGRESSIVE PROFILING PLAN** — 90-day data enrichment and gap-filling roadmap
7. **SUPPRESSION FRAMEWORK** — 8 universal suppression rules + preference center design
8. **IMPLEMENTATION PRIORITY SEQUENCE** — Exactly which segments to build in weeks 1, 2–4, and 5–8
9. **MEASUREMENT DASHBOARD** — KPIs to track segmentation performance improvement

## Example Input/Output

**Input Example:**

Company: Trackwise Industrial — IoT asset monitoring SaaS for heavy manufacturing and oil & gas
ICP: VP Operations, Plant Manager, and Reliability Engineers at facilities with 500+ assets; secondary buyer: CIO/VP IT
Platform: Marketo Engage (Enterprise)
CRM: Salesforce Sales Cloud with 6sense Revenue AI integration
Total contacts: 11,400 opted-in; 38% have opened any email in the last 90 days
Current segmentation: Industry vertical only (3 segments); no behavioral segments; customers and prospects on same list
Sales complaint: "Marketing is emailing our best prospects the same week we're trying to close them — kills credibility"
Primary goal: Stop emailing the 62% who never engage; build behavioral segments for the 38% who do

---

**Output Example (partial — Engagement Tier definitions and two Segment Specifications):**

**TRACKWISE INDUSTRIAL — ENGAGEMENT TIER DEFINITIONS**

**Tier 1A — Champion (estimated 8% of list = ~912 contacts)**

*Definition:*
- Opened ≥3 emails in last 14 days, OR
- Clicked ≥2 links in last 30 days, OR
- Opened ≥1 email in last 7 days AND visited website in last 7 days
- AND NOT: Active CRM opportunity (suppressed from all standard nurture by Suppression Rule 1)

*Frequency cap*: Up to 5 emails/month — these contacts are reading everything

*Content strategy*: Product-forward. This segment is engaged enough for direct product education, customer success stories with specific metrics, and early access invites. They're warm — treat them accordingly.

*Escalation to sales*: If Champion contact has no CRM opportunity after 30 days of Champion-tier engagement, auto-create a Salesforce lead record and assign to the appropriate BDR/SDR based on territory. Champion engagement without sales follow-up is the most common revenue leak in B2B SaaS email programs.

---

**Tier 1D — Dormant (estimated 28% of list = ~3,192 contacts)**

*Definition:*
- No email opened in 60–120 days
- AND NOT: New contact (< 60 days in database)
- AND NOT: Currently in a reactivation sequence

*Frequency cap*: Maximum 1 email per month — a specifically designed "We miss you / here's what's changed" message, not standard nurture

*Content strategy*: Pattern interrupt. Generic nurture fails completely at this engagement level. The only content worth sending is something that breaks the pattern: a specific industry statistic they haven't seen, a provocative question that challenges their current approach, or a peer story from their exact industry vertical. No product features. No CTAs to book a demo.

*Reactivation threshold*: If Dormant contact opens this re-engagement email AND clicks any link, move to Tier 1C (Passive) and enroll in consideration-stage nurture. If Dormant contact does NOT open the re-engagement email within 21 days, move to Tier 1E (Reactivation Candidate) and begin the final 3-email reactivation sequence before suppression.

---

**SEGMENT 3: Competitive Evaluation Active**

*Plain-English Description*: Contacts who are currently comparison-shopping — they've visited competitor pages, downloaded a competitive guide, or (if 6sense is integrated) have triggered a buying-stage intent cluster around your category keywords. These contacts have a vendor-evaluation mental model active right now. They're going to choose someone. The question is whether your email program is influencing that decision or staying silent while your competitor's SDR calls them.

*Business Priority*: Win/loss data shows 60% of Trackwise deals involve at least one other vendor. This segment is in active evaluation — a well-timed, proof-heavy email sequence during the evaluation period can influence shortlist positioning. Every day this segment exists without a specific email program is a lost influence opportunity.

*Enrollment Criteria (Marketo Smart List logic):*

INCLUDE if ALL of the following:
- Smart Campaign: Visited URL containing "/vs/" OR "/compare/" OR "/alternative" in last 14 days
- OR: Downloaded asset tagged "Competitive" in last 30 days
- OR: 6sense Buying Stage = "Decision" in last 7 days (via Marketo-6sense API integration)
- AND: Contact Status = "Prospect" (not customer, not partner)
- AND: Marketo Lead Score ≥ 25 (filters out low-quality contacts who browsed without intent)

EXCLUDE if ANY of the following:
- CRM Opportunity Stage ≠ NULL (active deal — sales owns the competitive narrative)
- Last Sales Call Date ≤ 14 days (sales already engaged)
- Email Preference = "Unsubscribed" or "Marketing Suspended"

*Update Frequency*: Real-time (Marketo webhook triggered by URL visit, asset download, or 6sense alert sync — whichever fires first)

*Estimated size*: 2–4% of list at any time (~230–460 contacts at Trackwise scale); replenishes constantly as new contacts enter evaluation

*Email Frequency*: 3 emails over 14 days — this window is time-sensitive. After 14 days, if no demo request, move back to standard Consideration-stage nurture.

*Content Focus*: Competitive proof sequence. Email 1: Head-to-head comparison framed from the customer's decision criteria (not from Trackwise's features). Email 2: Customer story from the exact industry/use case that competitive prospects care about — include specific metrics (e.g., "Oakley Manufacturing cut unplanned downtime by 43% in Year 1"). Email 3: Risk/consequence framing — the cost of choosing the wrong platform, grounded in implementation risk data.

*Handoff Rule*: If Competitive Evaluation Active contact clicks any link in the 3-email sequence, create Salesforce Task for territory BDR — Priority: High. Alert includes: contact name, company, which competitor pages visited, which assets downloaded, current lead score. This is a hot hand-raise — respond within 4 business hours.

**FULL EMAIL EXAMPLE — Competitive Evaluation Active — Email 1 of 3:**

Subject: How Oakley Manufacturing chose their asset monitoring platform (the 5 criteria they used)

Preview: They were evaluating 3 vendors. Here's what made the difference.

Hi [First Name],

When Oakley Manufacturing's Reliability team set out to replace their legacy CMMS last year, they built a 5-point evaluation framework before they looked at a single vendor demo.

Their criteria (in order of weight):
1. Time-to-first-alert: How fast does the system surface an anomaly before it becomes a failure?
2. False positive rate: How often does it cry wolf? (Their previous system averaged 23 false alerts/day — ops teams had started ignoring it)
3. Integration with SAP PM: Non-negotiable for their ERP-first IT policy
4. Implementation timeline: Could they be live before turnaround season (Q4)?
5. Support model: Who answers the phone at 2am during a production crisis?

They chose Trackwise. Here's the comparison they used.

[Link: Download "The 5-Point Asset Monitoring Evaluation Framework — What Heavy Manufacturers Need to Know Before They Decide"]

This isn't a Trackwise brochure — it's the vendor-neutral criteria their team developed, plus how we scored on each one (and where we don't win, we'll tell you).

Worth 8 minutes of your time if you're in evaluation mode.

[First Name at Sender Company]
[Personalized signature block with direct calendar link]

## Success Metrics

- **Segmentation coverage rate**: ≥80% of contacts assigned to at least 1 Tier 2 (journey stage) segment within 30 days of architecture implementation — contacts that can't be classified need a data enrichment investigation, not a generic blast
- **Engagement tier health**: Champion + Engaged tiers should grow from baseline as better segmentation reduces list dilution; target: 40%+ of active senders in top-2 tiers within 60 days
- **Unsubscribe rate reduction**: Dormant and Reactivation tiers receiving suppressed or minimal sends should produce ≥35% reduction in unsubscribes within 60 days vs. unsegmented program — the biggest unsubscribe driver is always irrelevant email to disengaged contacts
- **MQL rate per segment vs. unsegmented baseline**: The top 3 segments (Champion, High Intent, Competitive Evaluation) should produce ≥3x higher MQL rate than the pre-segmentation program average — if they don't, the segment criteria are wrong
- **Deliverability improvement**: Inbox placement rate and domain reputation scores (monitor via Google Postmaster Tools and Microsoft SNDS) should stabilize or improve within 60 days as low-engagement contacts are suppressed — reduced complaints = improved sender reputation = higher deliverability for engaged segments
- **Sales complaint rate**: Specific tracking metric — how many times per month does a sales rep report that marketing emailed their active prospect? Should drop to near zero within 30 days of implementing CRM opportunity suppression rules
- **Data completeness improvement**: Track the percentage of contacts with complete Tier 3 overlay data (title, industry, company size) monthly; target: 15-percentage-point improvement in 90 days from progressive profiling and enrichment

## Related Prompts

- [Inbound Email Marketing Architecture & Behavioral Lead Lifecycle](./AI-Powered-B2B-SaaS-Inbound-Email-Marketing-Architecture-&-Behavioral-Lead-Lifecycle-Revenue-Intelligence-Engine.md)
- [Email Marketing A/B Testing Architecture & Autonomous Optimization](./AI-Powered-B2B-SaaS-Email-Marketing-AB-Testing-Architecture-&-Autonomous-Email-Optimization-Revenue-Intelligence-Engine.md)
- [Lead Nurturing Program Architecture & Behavioral Segment Pipeline Acceleration](../../Lead-Nurturing/AI-Powered-B2B-SaaS-Lead-Nurturing-Program-Architecture-&-Behavioral-Segment-Pipeline-Acceleration-Revenue-Intelligence-Engine.md)
- [Predictive Lead Scoring Architecture & Revenue Qualified Pipeline Management](../../Lead-Scoring-&-Pipeline-Management/AI-Powered-B2B-SaaS-Predictive-Lead-Scoring-Architecture-&-Revenue-Qualified-Pipeline-Management-Intelligence-Engine.md)

## Integration Tips

**HubSpot Marketing Hub:**
- Use **Active Lists** (not Static Lists) for all behavioral segments — Active Lists update in real-time as contact properties change; Static Lists are frozen at creation and defeat the purpose of dynamic segmentation
- Build **Engagement Score** using HubSpot's **Contact Scoring** feature: assign point values to email opens (+3), email clicks (+7), website visits (+2), pricing page visit (+15), content download (+8), demo request (+40) — decay points automatically using HubSpot's built-in score decay setting (subtract points if no activity in 30 days)
- Create **Suppression Lists** using Active List logic and reference them in every Email Workflow as "Contact is NOT a member of [Suppression List]" — this is the most reliable way to prevent emailing sales-owned contacts
- Use **HubSpot-Salesforce Sync** with bi-directional field mapping to bring CRM opportunity stage into HubSpot in real-time — without this sync, marketing can't suppress based on sales activity
- **HubSpot AI Segmentation (if on Enterprise tier)**: Use the "Predicted Contact Score" feature to identify contacts likely to become MQLs before they show enough explicit intent signals — useful for identifying the top 10% of Passive-tier contacts who should be upgraded to Engaged-tier treatment

**Marketo Engage:**
- **Smart List architecture**: Build a master "Segmentation-Eligible" Smart List as the foundation — all contacts who meet base eligibility (opted-in, not suppressed, not customer) — then all segment Smart Lists use this as an AND condition to prevent suppression overrides
- Use **Marketo Segmentation** feature (under Database → Segmentations) for mutually exclusive tier assignment — this native feature ensures contacts are in exactly one engagement tier at a time and feeds dynamic content blocks in email design
- **Velocity Scripting for personalization**: If you're on Marketo Select or Enterprise, use Velocity scripting to dynamically insert segment-appropriate content blocks, proof points, and CTAs into a single email template — reduces email production time by 60% compared to building segment-specific email variants manually
- **Revenue Cycle Modeler**: Map your Tier 2 journey stages to Marketo's Revenue Stage framework — this enables proper stage-to-stage conversion tracking and connects segmentation health to pipeline attribution reporting

**Salesforce Marketing Cloud:**
- **Journey Builder + Einstein Segmentation**: Use Einstein Engagement Scoring to dynamically move contacts between engagement tier journeys — Einstein continuously re-scores contacts, so a contact who re-engages automatically re-enters the appropriate journey without manual intervention
- **Data Extensions for dynamic segmentation**: Create a master "Contact Intelligence" Data Extension that stores all segment assignment values; update it via Automation Studio daily from Sales Cloud and web analytics data; use this as the source of truth for all journey enrollment criteria
- **Suppression Data Extension**: Create a dedicated "Suppression — Active Opportunity" Data Extension synced from Salesforce Sales Cloud via Marketing Cloud Connect; reference it in every send as an exclusion list — this is the most reliable way to prevent CRM-owned contacts from receiving marketing emails

**Clearbit / Apollo / ZoomInfo (Enrichment):**
- Set up enrichment API calls triggered by new contact creation in your MAP — the first 60 minutes after a contact enters your system is the highest-value enrichment window (they're actively browsing or in a buying process)
- Use enrichment to infer Tier 3 persona overlay for the 30–40% of contacts who submit forms without company size or title — enrichment typically fills 70–85% of missing firmographic fields on new contacts
- Configure enrichment to write to a secondary field ("Enriched Job Title") rather than overwriting the "Job Title" field — preserves any self-reported data while filling gaps where no data exists; your segmentation logic should use "if [Job Title] exists, use it; else use [Enriched Job Title]"

## Troubleshooting

**Problem: Segments are building correctly but the right contacts aren't in the right segments — engagement tier assignments seem wrong (engaged contacts in Dormant tier, dormant contacts in Champion tier).**
Solution: This is almost always an email tracking reliability issue, not a segmentation logic issue. Check three things: (1) Open tracking pixel reliability — Apple Mail Privacy Protection (MPP) inflates open rates by pre-loading pixels on behalf of Apple users, making contacts appear "opened" when they may not have. If 40%+ of your list uses Apple Mail, your "Opened in last 14 days" criterion is including contacts who didn't actually open — add a click-behavior requirement (clicks are not affected by MPP and remain reliable engagement signals). (2) Email send vs. delivered vs. opened attribution — verify your MAP is tracking "opened" based on the email actually reaching and being opened, not a soft bounce being classified as a send. Check your bounce handling rules. (3) Cross-device attribution — a contact who opens on iPhone and clicks on desktop may register as two different engagement events depending on your MAP's cookie/tracking setup; verify your MAP's cross-device identity resolution is functioning.

**Problem: Sales team is still receiving complaints from prospects about receiving marketing emails during active deals — the CRM opportunity suppression isn't working.**
Solution: B2B SaaS CRM-to-MAP sync suppression breaks in three specific scenarios: (1) Opportunity is created after a contact is already enrolled in an active email workflow — check whether your suppression logic fires at enrollment time only (won't catch mid-workflow additions) or re-evaluates at each send step (correct behavior). HubSpot Workflows need a "Re-check enrollment criteria at each step" setting; Marketo needs suppression Smart List checked at each Flow Step. (2) Multiple contacts on the same deal — your CRM opportunity may be associated with an Account, not a Contact; if your MAP syncs at the Contact level, non-primary contacts on the same deal may not be suppressed. Ensure all contacts on a CRM Account with an open opportunity are flagged. (3) Sync latency — if your MAP-CRM sync runs every 4 hours and a rep creates an opportunity at 9am, marketing can send 4 hours of emails before the suppression fires. For critical suppression rules (active opportunity), trigger a real-time webhook from Salesforce on opportunity creation that immediately updates a MAP field — don't rely on scheduled sync for time-sensitive suppression.

**Problem: After implementing segmentation, total email volume dropped significantly and leadership is asking why we're "sending fewer emails" — they're interpreting this as reduced marketing activity.**
Solution: Frame this as a deliberate strategic shift, not reduced activity, with three data points: (1) Show the "suppression portfolio" — break down the new contact distribution across all tiers and show leadership that the 40% of contacts now receiving fewer emails were generating 0.3% of MQLs while consuming 35% of your send budget. You didn't reduce marketing — you eliminated waste. (2) Show the "engagement concentration" metric — total email clicks, form fills, and content downloads from the active/engaged tiers should be maintained or increased even with lower total volume, because you're no longer diluting engagement metrics with thousands of non-openers. (3) Show deliverability improvement — Gmail Postmaster Domain Reputation and inbox placement rates should improve within 30–45 days as the spam-signal contacts receive fewer emails. Higher deliverability for your engaged segments means more emails reaching inboxes where they can generate pipeline. Map deliverability improvement to pipeline opportunity: if inbox placement improves from 88% to 94%, and your current program drives $1.8M/quarter in influenced pipeline, the improved deliverability is worth an estimated additional $122K in pipeline reach per quarter — without any creative or budget change.

## Version History
- v1.0: Initial creation (auto-generated)
