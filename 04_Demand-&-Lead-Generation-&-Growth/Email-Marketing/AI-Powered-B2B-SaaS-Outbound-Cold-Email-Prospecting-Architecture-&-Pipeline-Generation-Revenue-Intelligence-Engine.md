# AI-Powered B2B SaaS Outbound Cold Email Prospecting Architecture & Pipeline Generation Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** cold-email, outbound, prospecting, pipeline-generation, b2b-saas, sales-development, clay, apollo, instantly, personalization-at-scale, email-deliverability, demand-generation

## Overview

This prompt deploys an autonomous outbound cold email prospecting system that designs, sequences, and personalizes high-converting cold email campaigns for B2B SaaS pipeline generation — building net-new pipeline from cold accounts through AI-researched hyper-personalization, multi-touch cadences, and signal-triggered outreach. Use it when you need to generate pipeline beyond inbound, when your SDR team's manual prospecting is not scaling, or when your cold email reply rates are below 3%. This engine designs list-building logic, personalization frameworks, copy sequences, send infrastructure, and deliverability governance so a team of 2 SDRs can execute 1,000+ personalized outbound touches per week with genuine relevance — not spray-and-pray blasting.

## Quick Copy-Paste Version

You are a senior B2B SaaS outbound prospecting strategist with deep expertise in cold email at scale. My company sells [PRODUCT — e.g., AI-powered revenue forecasting software] to [ICP — e.g., VP of Sales and CROs at B2B SaaS companies with 50–500 employees and $5M–$50M ARR]. We need to build net-new pipeline through outbound cold email.

Design a complete outbound cold email prospecting program that generates qualified pipeline from cold accounts. Produce the following:

1. ICP TARGETING & LIST-BUILDING LOGIC — Define the 5 firmographic and technographic filters we should use in Apollo/Clay/LinkedIn Sales Navigator to build a high-fit prospect list. Include: company size (employees and ARR), industry, tech stack signals (e.g., uses Salesforce + Gong), and buying trigger signals (e.g., recent funding round, new VP of Sales hire, job posting for revenue operations roles). Estimate the total addressable list size per filter combination.

2. PERSONALIZATION ENGINE — Design a 3-tier personalization framework:
   - Tier 1 (1:1 deep research, <100 accounts): What AI research to pull per account and how to inject it into the opening line
   - Tier 2 (1:few segment-based, 100–1,000 accounts): What variable fields to populate via Clay waterfall enrichment for semi-personalized openers
   - Tier 3 (1:many pattern-based, 1,000+ accounts): What ICP-level pain point hooks to use as pseudo-personalization without research

3. EMAIL SEQUENCE ARCHITECTURE — Design a 5-touch cold email cadence with:
   - Email 1 (Day 0): Cold opener with personalized hook + single CTA
   - Email 2 (Day 3): Value-add follow-up with a relevant asset or insight
   - Email 3 (Day 7): Social proof angle — reference a customer from their industry
   - Email 4 (Day 14): Challenge/pattern interrupt — something unexpected or provocative
   - Email 5 (Day 21): Breakup email — explicit last touch
   For each email: subject line, preview text, body (under 100 words), CTA, and personalization token used.

4. DELIVERABILITY INFRASTRUCTURE — Outline the email infrastructure required to send at scale without landing in spam: domain configuration (SPF, DKIM, DMARC), number of sending domains needed, mailbox warm-up protocol, sending volume limits per mailbox, and bounce rate thresholds that trigger automatic pause.

5. REPLY HANDLING PLAYBOOK — Define the 4 most common reply types (interested, not now, wrong person, unsubscribe) and the exact response each should trigger — whether a human SDR response, automated workflow, or CRM sequence enrollment.

Output as a structured prospecting program blueprint with specific copy, logic, and implementation steps. Everything should be executable in Clay + Apollo + Instantly (or equivalent) within 2 weeks.

## Advanced Customizable Version

### ROLE & CONTEXT

You are an elite B2B SaaS outbound demand generation architect who has built cold email prospecting programs generating $10M–$100M in pipeline across companies ranging from early-stage startups to public SaaS companies. You understand the fundamental failure modes of most B2B cold email programs: generic "spray and pray" messaging that destroys domain reputation, irrelevant targeting that wastes SDR time on low-fit accounts, and pitch-first sequences that get deleted before the second line.

You think in signals, not lists. You understand that a cold email is only "cold" if it lacks relevance — and that in 2025, there is no excuse for sending an email that doesn't reference something specific about the recipient's company, role, or recent behavior. You design outbound programs around three principles:

- **Trigger-based targeting**: Reach out when there's a buying signal, not just because someone fits a firmographic profile. Recent funding, new executive hire, tech stack change, competitor contract expiry, or company growth signals all indicate a window of receptivity.
- **Relevance over volume**: A 500-account list with genuine 1:1 personalization outperforms a 5,000-account blitz every time on revenue per email sent. Design the program so AI does the research — humans write the strategy and review samples.
- **Infrastructure discipline**: Cold email success is 60% deliverability, 30% targeting, 10% copy. Without proper domain infrastructure, even brilliant copy lands in spam. You build infrastructure-first.

You design outbound programs for full AI agent automation: Clay waterfall enrichment pulls company intelligence, recent news, tech stack data, and hiring signals; AI writes first-line personalizations at scale; sequences run in Instantly or Smartlead with automatic reply detection; and CRM enrollment happens without human intervention for positive replies.

You understand legal compliance requirements: CAN-SPAM (US), GDPR (EU — B2B contact data requirements), CASL (Canada), and CCPA (California). Your programs are designed to be compliant in all operating geographies.

---

### COMPANY & PROSPECTING CONTEXT

**Company Profile:**
Company name: [e.g., Forecastly — AI-powered revenue forecasting and pipeline intelligence for B2B SaaS sales teams]
Product category: [e.g., Revenue intelligence and AI forecasting platform]
ICP definition:
- Primary persona: [e.g., VP of Sales / CRO — owns forecast accuracy and pipeline visibility]
- Secondary persona: [e.g., Revenue Operations Manager — owns the forecasting tools and CRM hygiene]
- Economic buyer: [e.g., CRO / CFO — approves revenue tech stack investment]
- Company size: [e.g., 50–500 employees, $5M–$75M ARR, Series A through Series C]
- Industry: [e.g., B2B SaaS companies with a field or inside sales motion, 10+ AEs]
- Tech stack signals: [e.g., Uses Salesforce CRM, has Gong or Chorus installed, uses HubSpot Marketing]
- Anti-ICP signals: [e.g., Under 10 employees, uses HubSpot CRM only (no Salesforce), transactional/ecommerce companies]
ACV range: [$X – $Y ARR]
Sales cycle average: [X months]
Differentiators vs. competitors: [e.g., vs. Clari: real-time AI, not rule-based; vs. Bowtie: built for teams under 500]

**Current Outbound State:**
Current SDR headcount: [X SDRs]
Current cold email volume: [X emails/week]
Current reply rate: [X%] (industry benchmark: 3–8% for well-personalized outbound)
Current booked meeting rate: [X% of replies = meetings booked]
Current pipeline sourced from outbound: [$X/month]
Sending infrastructure: [Apollo / Outreach / Salesloft / Instantly / Smartlead / None yet]
Enrichment tools: [Clay / Apollo / ZoomInfo / Clearbit / None]
Intent data: [6sense / Bombora / G2 Buyer Intent / None]

**Buying Trigger Signals Available:**
[Select all that apply — these are the signals you can detect and act on]
☐ Recent funding round (Series A/B/C announced in last 90 days)
☐ New VP Sales / CRO hire (LinkedIn signal — new executive started in last 60 days)
☐ Job postings for revenue operations or sales analyst roles (indicates scaling)
☐ Competitor review activity (G2 reviews of your competitors in last 30 days)
☐ Tech stack addition (new Salesforce, Gong, or HubSpot detected via BuiltWith/Datanyze)
☐ Company headcount growth >20% in last 12 months
☐ Conference attendance (LinkedIn badge scans, session registrations at Dreamforce, SaaStr)
☐ Content engagement (downloaded competitor's ebook, commented on relevant LinkedIn post)
☐ Company news signal (press release announcing sales team expansion, new market entry)

**Geographic & Compliance Requirements:**
Primary target geography: [e.g., US, UK, Canada, DACH, APAC]
Compliance requirements: [CAN-SPAM / GDPR / CASL / all three]
Opt-out mechanism: [Single-click unsubscribe link required in all emails — Y/N]

---

### DELIVERABLE 1: ICP TARGETING & ACCOUNT SCORING ARCHITECTURE

Build a tiered account scoring model with 3 tiers:

**Tier 1 — High Priority Targets (send within 48 hours of signal detection)**
Firmographic filters: [5 specific criteria]
Technographic filters: [3 specific tech stack signals]
Trigger signal required: [Which buying triggers must be present]
Estimated accounts in addressable pool: [X accounts/quarter]
Personalization level: Deep 1:1 (AI-researched opener, reference specific company news)

**Tier 2 — Medium Priority Targets (weekly batch sending)**
Firmographic filters: [Modified criteria — slightly relaxed thresholds]
Technographic filters: [2 specific signals]
Trigger signal: [Preferred but not required]
Estimated accounts in addressable pool: [X accounts]
Personalization level: Segment-based (industry + persona pain point hook)

**Tier 3 — Broad Market (monthly campaigns, pattern-based)**
Firmographic filters: [ICP minimum criteria only]
Technographic filters: [1 signal — e.g., Salesforce user]
Trigger signal: Not required
Estimated accounts in addressable pool: [X accounts]
Personalization level: Persona-level pain point hook

For each tier, define:
- Clay enrichment waterfall (which data providers to cascade through for each field)
- AI research prompt for first-line personalization generation
- Sequence variant to use (separate sequences per tier)
- Expected reply rate benchmark per tier (Tier 1: 5–10%, Tier 2: 3–6%, Tier 3: 1–3%)

---

### DELIVERABLE 2: PERSONALIZATION ENGINE DESIGN

**Clay AI Research Prompt Template for Tier 1 Accounts:**
Design the exact Clay "Claygent" AI prompt to research each account and generate a personalized first line. The prompt should instruct the AI to:
- Pull the most recent company news or milestone (funding, product launch, expansion, executive hire)
- Identify the specific pain point our product solves for this company's current growth stage
- Reference the prospect's LinkedIn profile for a specific detail (recent post, career milestone, shared connection)
- Output a 1–2 sentence personalized opener that sounds human, references something specific, and creates a bridge to our product value prop

**Variable Field Map for Tier 2 Segment Personalization:**
Define 5 Clay variable fields that create semi-personalized emails at scale:
- {company_pain_point}: AI-generated based on tech stack + company size + industry
- {competitor_they_likely_use}: Inferred from tech stack signals
- {relevant_customer_similar_to_them}: Matched customer reference from our case study library
- {industry_stat}: Relevant benchmark stat for their vertical
- {growth_signal}: What growth indicator we detected (hiring, funding, expansion)

**Persona-Level Hook Library for Tier 3:**
Write 3 opening hooks for each of your top 2 personas (VP Sales, RevOps Manager) that require zero account-specific research but feel relevant because they reference universal pain points of that persona at the ICP company size:

VP Sales Hooks:
1. [Hook addressing forecast accuracy problem at Series B+ stage]
2. [Hook addressing pipeline coverage anxiety going into board meetings]
3. [Hook addressing rep performance visibility problem]

RevOps Manager Hooks:
1. [Hook addressing CRM data quality problem that breaks forecasting]
2. [Hook addressing manual reporting time sink problem]
3. [Hook addressing cross-system data reconciliation problem]

---

### DELIVERABLE 3: EMAIL SEQUENCE ARCHITECTURE (Full Copy)

**Sequence A — Trigger-Based (Tier 1: Recent Funding Round)**

**Email 1 — Day 0: Signal-triggered opener**
Subject: [Personalized — references funding news]
Preview: [Teases the relevant problem]
Body: [Max 80 words — references funding, connects to scaling pain, single CTA]
CTA: [Specific ask — 15-min call, "worth a quick look?", reply with yes/no]
Personalization tokens: {first_name}, {company_name}, {funding_round}, {amount_raised}, {investor_name}

**Email 2 — Day 3: Value-add follow-up**
Subject: [New subject — don't thread, re-engage]
Preview: [Hints at insight or resource]
Body: [70 words — shares a relevant insight, stat, or short case study from a similar company that scaled through Series B. No pitch.]
CTA: [Soft — "thought this might be relevant" + link to relevant resource]

**Email 3 — Day 7: Social proof from their world**
Subject: [References a company similar to theirs]
Preview: [Specific outcome — pipeline number, forecast accuracy improvement]
Body: [75 words — brief case study sentence + outcome + bridge to their situation]
CTA: [Offer to share the full story — "happy to send the 2-pager if relevant"]

**Email 4 — Day 14: Challenge / pattern interrupt**
Subject: [Provocative question or counterintuitive statement]
Preview: [Continues the intrigue]
Body: [60 words — shares a contrarian take on a commonly held belief in their role, e.g., "Most CROs I talk to blame their CRM data. The real problem is usually…"]
CTA: [Invite a 10-minute conversation to validate their situation]

**Email 5 — Day 21: Breakup email**
Subject: ["Closing your file" or "Last email from me"]
Preview: [Honest and human]
Body: [50 words — explicit last touch, no hard sell, leaves the door open. Optionally gives them a self-serve resource to explore on their own timeline.]
CTA: [Binary — "just reply 'not now' if timing is off and I'll reach back in 6 months"]

**Sequence B — Persona-Based (Tier 2: VP Sales, no specific trigger)**
[Repeat structure with 5 emails using segment-level personalization only]

**Sequence C — Broad Market (Tier 3: Pattern-based)**
[Repeat structure with 3 emails only — shorter sequence for lower-priority accounts]

---

### DELIVERABLE 4: DELIVERABILITY INFRASTRUCTURE BLUEPRINT

**Domain Configuration:**
Primary sending domains needed: [Formula: 1 domain per 3 mailboxes; at 150 emails/day/mailbox, calculate total domains for target volume]
Domain naming convention: [e.g., tryforecastly.com, getforecastly.com, forecastly.io — never the primary company domain]
DNS records required: SPF, DKIM (2048-bit), DMARC (p=quarantine → p=reject after 30 days), MX records

**Mailbox Warm-Up Protocol:**
Week 1–2: [X emails/day, warm-up tool: Instantly Warmup / Mailreach / Lemwarm]
Week 3–4: [X emails/day — ramp schedule]
Week 5+: [Maximum send volume per mailbox]
Warm-up pool size required: [Minimum X accounts in warm-up network]

**Sending Limits & Safety Thresholds:**
Max emails per mailbox per day: [X — recommend 40–50 for cold outbound]
Max new domains to start per week: [X — to avoid Google/Microsoft flagging]
Bounce rate threshold to pause: [>3% hard bounces triggers automatic sequence pause]
Spam complaint threshold: [>0.1% = immediate infrastructure audit]
Reply rate below which to pause and revise: [<1% after 100 sends = copy problem, not deliverability]

**List Hygiene Protocol:**
Email verification: [ZeroBounce / NeverBounce / Debounce — validate all lists before import]
Catch-all domain handling: [Strategy for domains where all emails appear valid]
Suppression list maintenance: [Unsubscribes, bounces, competitors, existing customers — all auto-suppressed]

---

### DELIVERABLE 5: REPLY CLASSIFICATION & HANDLING PLAYBOOK

**Reply Type 1 — Positive Interest ("Yes, interested / tell me more / what does it cost")**
Auto-detect trigger: [Keywords: "yes", "interested", "tell me more", "demo", "pricing"]
Action: [Immediately pause sequence + assign to SDR for personalized follow-up within 2 hours]
SDR response template: [30-second reply confirming understanding of their interest + Calendly link + 1 sentence of social proof]
SLA: [SDR must respond within 2 business hours]

**Reply Type 2 — Not Now ("Reach out in Q2 / we're not a priority right now")**
Auto-detect trigger: [Keywords: "later", "next quarter", "not now", "timing"]
Action: [Auto-acknowledge, remove from active sequence, add to "Resurface in 90 days" CRM task]
Auto-response template: [5-sentence reply: acknowledge, express understanding, set a specific callback date, provide a self-serve resource, close warmly]

**Reply Type 3 — Wrong Person ("Not the right person / try John in RevOps")**
Auto-detect trigger: [Keywords: "not the right", "you should talk to", "wrong person", "try"]
Action: [Extract referred name + title from reply via AI parsing → enrich in Clay → add to Tier 1 sequence with referral mention]
Auto-research trigger: [Clay lookup on referred contact, add "{referral_name} suggested I reach out" as personalized opener]

**Reply Type 4 — Unsubscribe / Not Interested ("Remove me / stop emailing / not interested")**
Auto-detect trigger: [Keywords: "unsubscribe", "remove", "stop", "not interested", "do not contact"]
Action: [Immediate sequence stop, add to global suppression list, no re-engagement for 12 months]
CRM update: [Log as "Outbound Suppressed" status, note date and reason]
Compliance requirement: [GDPR/CAN-SPAM: unsubscribe must be honored within 10 business days, recommend within 24 hours]

---

### DELIVERABLE 6: PROGRAM MEASUREMENT FRAMEWORK

**Weekly KPIs to Track:**
- Emails sent: [Target X/week]
- Deliverability rate: [Target >95%]
- Open rate: [Target 45–65% — note: Apple MPP inflates opens, use reply rate as primary metric]
- Reply rate: [Target 3–8% for well-personalized outbound]
- Positive reply rate: [Target 1–3% — replies indicating genuine interest]
- Meeting booked rate (of positive replies): [Target 50–70%]
- Meeting booked per SDR per week: [Target 3–8 qualified meetings]
- Meetings to pipeline conversion: [Target 30–50% qualify to opportunity]
- Pipeline sourced per SDR per week: [$X based on ACV × conversion rate]

**Monthly Health Checks:**
- Domain reputation audit (Google Postmaster Tools, Microsoft SNDS)
- Bounce rate review by domain and list source
- Sequence variant performance (A/B test subject lines, CTA variants, email length)
- Reply quality scoring (% of positive replies that convert to qualified opportunities)
- Copy refresh: Any sequence running >90 days should be revised to avoid audience fatigue

**Attribution Model:**
- Outbound pipeline attribution: [Opportunity created within 30 days of first cold email touch]
- Assisted pipeline: [Opportunity where prospect received outbound touch AND inbound marketing touch before converting]
- SDR-to-AE handoff criteria: [X signals required before handoff: booked meeting + BANT qualification + confirmed authority]

## Example Input/Output

**Input Example:**

Company: **Forecastly** — AI-powered revenue forecasting for B2B SaaS sales teams
ICP: VP of Sales and CROs at B2B SaaS companies, $10M–$75M ARR, 25–300 employees, Series A–C
Current state: 0 outbound program, 2 SDRs doing manual LinkedIn outreach, ~20 meetings/month from inbound only
Goal: Build a cold email program generating 30 additional qualified meetings/month within 90 days

**Output Example:**

**Tier 1 Account Profile (sample):**
Company: DataStax (B2B SaaS, 180 employees, Salesforce + Gong on stack, raised $115M Series D)
Signal detected: New CRO hired 45 days ago (LinkedIn signal from Clay)
First-line personalization (AI-generated): "Congrats on bringing on Marcus Hill as CRO last month — companies at DataStax's stage often find the biggest challenge in his first 90 days is getting a clean forecast picture across 3 different pipeline stages. That's exactly where we've helped teams like Drift and Clari's own customers cut forecast variance by 40%."

**Email 1 Subject:** "Your new CRO's first 90-day headache (and a fix)"

**Email 1 Body (78 words):**
Marcus Hill just started as your CRO — congrats. In our experience working with CROs at Series D SaaS companies, the first 90 days are defined by one painful truth: the forecast is a lie. Not because reps aren't updating Salesforce, but because the rollup logic hasn't been tuned for where your business is today.

We built Forecastly to solve that specific problem. Would a 15-minute look at how we do it be worth your time?

**Reply after 4 days:** "Actually yes — we're three weeks into a forecast audit. Can you do Thursday at 2pm?"

Result: Meeting booked in Email 1, no follow-up needed. Pipeline opportunity created: $48,000 ACV.

**Deliverability Setup (Week 1 sample):**
- Domains registered: tryforecastly.com, getforecastly.com, forecastly.ai
- Mailboxes per domain: 3 (9 total mailboxes for 2 SDRs + 1 marketing sender)
- Warm-up started: Instantly Warmup at 20 emails/day per mailbox
- Target: Full send volume (45/day/mailbox) by Day 28

**Week 4 Program Metrics:**
- Emails sent: 1,840
- Reply rate: 5.2%
- Positive reply rate: 1.9%
- Meetings booked: 22
- Pipeline sourced: $312,000

## Success Metrics

- **Primary:** Positive reply rate >2% (indicates message-market fit)
- **Primary:** Qualified meetings booked per SDR per week ≥3
- **Primary:** Outbound-sourced pipeline ≥ 30% of total new pipeline within 90 days
- **Secondary:** Email deliverability rate >95% (Google Postmaster "Good" reputation)
- **Secondary:** Bounce rate <3% per campaign
- **Secondary:** Sequence-to-opportunity conversion rate >15%
- **Leading indicator:** Reply rate on Email 1 within first 48 hours (if <1%, rewrite the opener before sending more)
- **Health signal:** SDR acceptance rate of AI-personalized sends >90% (if SDRs are editing every AI line, the personalization prompt needs revision)

## Related Prompts

- [`../../04_Demand-&-Lead-Generation-&-Growth/Lead-Nurturing/AI-Powered-B2B-SaaS-Lead-Nurturing-Program-Architecture-&-Behavioral-Segment-Pipeline-Acceleration-Revenue-Intelligence-Engine.md`](../Lead-Nurturing/AI-Powered-B2B-SaaS-Lead-Nurturing-Program-Architecture-&-Behavioral-Segment-Pipeline-Acceleration-Revenue-Intelligence-Engine.md) — Once cold prospects reply and become MQLs, deploy this nurture program to advance them toward SQL status
- [`../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-ABM-SDR-Prospecting-Playbook-&-Account-Based-Sales-Development-Intelligence-Engine.md`](../Account-Based-Marketing/AI-Powered-ABM-SDR-Prospecting-Playbook-&-Account-Based-Sales-Development-Intelligence-Engine.md) — For Tier 1 named accounts, combine cold email with LinkedIn + direct mail ABM orchestration
- [`../../02_Product-Marketing/Sales-Enablement/AI-Powered-B2B-SaaS-Sales-Objection-Intelligence-&-Autonomous-Objection-Handling-Revenue-Playbook-Engine.md`](../../02_Product-Marketing/Sales-Enablement/AI-Powered-B2B-SaaS-Sales-Objection-Intelligence-&-Autonomous-Objection-Handling-Revenue-Playbook-Engine.md) — Build the objection-handling responses your SDRs use when prospects reply with concerns
- [`../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Omnichannel-Inbound-Lead-Response-Architecture-&-Speed-to-Revenue-Conversion-Intelligence-Engine.md`](../Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Omnichannel-Inbound-Lead-Response-Architecture-&-Speed-to-Revenue-Conversion-Intelligence-Engine.md) — Design the post-reply meeting booking and handoff experience to ensure no warm lead goes cold

## Integration Tips

- **Clay**: Use Clay as your enrichment and personalization engine. Build a "Claygent" AI agent to research each Tier 1 account and generate the opening line. Waterfall through Apollo, LinkedIn, Clearbit, and BuiltWith for firmographic, technographic, and contact data. Export enriched lists with all variable fields populated directly to Instantly or Smartlead.
- **Instantly / Smartlead**: Use these as your sending platform — not Outreach or Salesloft, which are designed for warm outbound, not cold prospecting at volume. Set up automatic reply detection to pause sequences and route positive replies to HubSpot/Salesforce as new leads.
- **Apollo.io**: Use Apollo for list building and initial contact discovery when Clay is not yet set up. Apollo's "Play" feature allows trigger-based prospecting (e.g., auto-add contacts when a company raises funding). Sync directly to your sending platform via native integration.
- **HubSpot / Salesforce CRM**: All positive replies should auto-create a Contact + Lead record in your CRM with source "Outbound Cold Email" and the sequence name as a property. This enables proper pipeline attribution and prevents SDRs from duplicate outreach.
- **Google Postmaster Tools + Microsoft SNDS**: Monitor domain reputation weekly. Set up alerts for reputation drops to "Bad" — pause all sending from that domain immediately and investigate. These free tools are non-negotiable for programs at scale.
- **Zapier / Make.com**: Automate the "Not Now" reply workflow — parse reply text, extract callback date mentioned by prospect, create a CRM task with the exact date, and enroll in a 90-day re-engagement drip sequence.

## Troubleshooting

**Problem: Reply rate below 1% after 200+ sends**
Solution: This is almost always a copy problem, not a deliverability problem (check deliverability first — if open rate is >30%, delivery is fine). Audit your Email 1 opener: is the first line genuinely about them, or is it about you? Replace any opener that starts with "I" or "We" — it should start with something specific about the prospect's company, role, or situation. A/B test 3 different opener styles simultaneously: (a) trigger-based news hook, (b) persona pain point hook, (c) provocative question. Pause the underperforming variants after 100 sends each.

**Problem: Emails going to spam / open rate below 15%**
Solution: Check Google Postmaster Tools immediately. Common causes: (a) sending too fast from new domains — reduce to 30 emails/day/mailbox and extend warm-up period by 2 weeks; (b) poor list quality with >5% bounce rate — run all lists through ZeroBounce before importing; (c) spam trigger words in subject line — avoid "free", "guarantee", "100%", "limited time offer", "no obligation"; (d) DMARC not configured correctly — verify DNS records in MXToolbox. Never use the primary company domain for cold outreach — use secondary domains only.

**Problem: High reply rate but low meeting conversion (replies saying "not interested" or "already have a solution")**
Solution: Your targeting is off — you're reaching companies that already have a competing solution or are clearly not in the market. Add negative firmographic filters: explicitly exclude companies where job postings mention your top 3 competitors as required experience (signals incumbent vendor). Add technographic exclusions: if they already have your specific category product on their stack, remove them from Tier 1–2 and either deprioritize or create a "competitive displacement" variant sequence with messaging designed for competitive situations.

## Version History
- v1.0: Initial creation (auto-generated)
