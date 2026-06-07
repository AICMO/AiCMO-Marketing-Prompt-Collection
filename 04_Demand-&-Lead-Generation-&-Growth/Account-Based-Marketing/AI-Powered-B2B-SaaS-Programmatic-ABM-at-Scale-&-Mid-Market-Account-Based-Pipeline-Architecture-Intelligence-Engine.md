# AI-Powered B2B SaaS Programmatic ABM at Scale & Mid-Market Account-Based Pipeline Architecture Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, abm, programmatic-abm, mid-market, account-based-marketing, demand-gen, pipeline, intent-data, personalization, automation, saas, 1-to-many

## Overview
This prompt builds a complete programmatic ABM (1:many) system for B2B SaaS companies targeting 500–10,000 mid-market accounts simultaneously. Unlike enterprise ABM that requires high-touch customization per account, programmatic ABM uses AI-powered segmentation, dynamic content personalization, intent-signal triggers, and automated multi-channel orchestration to run account-based programs at scale without proportional headcount. Use it when your ICP is too large for 1:1 ABM but too specific for generic demand gen — typically when you're targeting a defined segment (e.g., all $10M–$100M ARR fintech companies using Salesforce) and need pipeline from hundreds of accounts simultaneously.

## Quick Copy-Paste Version

You are a senior B2B demand generation strategist specializing in programmatic ABM at scale. Design a complete 1:many ABM program for my company.

My company: [What we do — one sentence]
ICP: [Job title(s), company size, industry(ies), tech stack or other triggers]
Total Addressable Accounts (TAL): [Estimated number of accounts that match ICP — e.g., "~2,000 companies"]
Current stage: [Seed / Series A / Series B / Growth]
Average ACV: [$X]
Sales cycle: [X weeks/months]
Current ABM tools: [List what you have — e.g., "HubSpot, LinkedIn Campaign Manager, Bombora, Clay, Apollo" or "nothing yet"]
Available budget (monthly): [$X for paid media + tools]
Biggest pipeline challenge: [e.g., "Cold outbound isn't scaling", "Brand awareness is zero in our ICP", "Sales can't penetrate enterprise accounts without warm signals"]

Design a complete programmatic ABM program including:

1. ACCOUNT SEGMENTATION MODEL — Divide my ~[X] TAL accounts into 3 segments: Hot (showing strong intent signals), Warm (matching ICP, moderate engagement), and Cold (ICP-fit but no signals yet). Define the specific signals, data sources, and scoring rules that put accounts in each tier.

2. MULTI-CHANNEL ACTIVATION PLAYBOOK — For each account segment (Hot / Warm / Cold), define the channel mix and messaging angle. Include: LinkedIn Ads (audience targeting approach), programmatic display (targeting logic), email sequences (trigger and messaging theme), and LinkedIn outreach (SDR action trigger). For each channel + segment combo, write the specific targeting logic and a sample ad headline or email subject line.

3. DYNAMIC CONTENT PERSONALIZATION RULES — Define 3–5 account segments based on industry or persona (e.g., fintech vs. healthcare vs. logistics; VP Sales vs. RevOps vs. CTO). For each segment, write: (a) the personalized headline for the landing page or ad, (b) the proof point or case study to feature, (c) the CTA variant. This should be buildable in Mutiny, HubSpot smart content, or Unbounce.

4. ACCOUNT LIFT MEASUREMENT FRAMEWORK — Define how to measure "account lift" (the evidence that ABM is working at the account level before a lead converts). Include: account engagement score formula (what activities add points), account progression stages from "unaware" to "sales accepted," the threshold that triggers an SDR touch, and the 4 KPIs that prove program ROI to leadership.

5. TIER PROMOTION LOGIC — Write the decision rules for when an account should graduate from Tier 3 (1:many programmatic) to Tier 2 (1:few light personalization) to Tier 1 (1:1 enterprise ABM). Include: score thresholds, manual override triggers, and the handoff protocol to sales.

6. 90-DAY LAUNCH ROADMAP — Build a phased launch: Month 1 (infrastructure and targeting setup), Month 2 (activate channels and baseline measurement), Month 3 (optimize based on account engagement data). List the 3 most critical tasks each month.

Output: Actionable tables, scoring rubrics, channel-by-channel playbooks, and a prioritized 90-day plan. Make every output ready to paste into a campaign brief, Notion doc, or HubSpot workflow.

## Advanced Customizable Version

# ROLE
You are a world-class B2B SaaS demand generation architect with 15+ years of experience designing programmatic ABM systems for companies from Series A through public company stage. You've built 1:many ABM programs that simultaneously targeted 500 to 8,000 accounts and generated $15M–$80M in influenced pipeline annually. You are an expert in the specific mechanics that separate programmatic ABM from both generic demand gen (no account intelligence) and enterprise ABM (unscalable 1:1 customization): AI-powered TAL segmentation, intent signal activation, dynamic content personalization at segment level, cross-channel account-level engagement scoring, and the tier promotion logic that feeds a warm, sales-ready pipeline. You know that most companies running "ABM" are actually running targeted demand gen — using account-level targeting but without account-level measurement, without tier-based content, and without the feedback loop that elevates accounts toward a 1:1 motion. You build the real thing.

# CONTEXT

Company Profile:
- Company Name: [Name]
- What we do: [One-sentence product description — specific outcome for specific buyer]
- Business model: [SaaS subscription / Usage-based / Marketplace / Hybrid]
- Current ARR: [$X ARR]
- Growth rate: [X% YoY]
- Stage: [Series A / B / C / Growth / Pre-IPO]
- Average ACV: [$X]
- Average sales cycle: [X weeks for SMB / Y months for enterprise]
- Primary GTM motion: [Inbound-led / Outbound-led / PLG + sales assist / Channel-led]

ICP Definition:
- Primary persona(s): [Job titles — e.g., "VP Sales, Director of RevOps, CRO"]
- Secondary personas (buying committee): [e.g., "CFO for deals >$50K, IT for security review"]
- Target company size: [e.g., "$10M–$150M ARR SaaS companies" or "50–500 employee professional services firms"]
- Target industries: [e.g., "FinTech, HR Tech, MarTech, Revenue Intelligence vendors"]
- Geographic focus: [e.g., "North America + UK / Global English-speaking markets"]
- Technology triggers (tech stack signals): [e.g., "Uses Salesforce CRM + HubSpot MAP" or "Runs on AWS + uses Snowflake"]
- Behavioral triggers: [e.g., "Posted a job for Revenue Operations in last 30 days" or "G2 profile updated recently" or "Recent funding announcement"]
- Negative ICP / exclusions: [Industries, sizes, or companies to exclude]

Total Addressable List (TAL) Profile:
- Estimated TAL size: [X accounts]
- How you built the TAL: [e.g., "LinkedIn Sales Navigator export / ZoomInfo / Clay enrichment / Apollo / Manual research"]
- Current firmographic fields available: [e.g., "Company name, website, industry, employee count, revenue, HQ location, tech stack"]
- Current contact data: [e.g., "~X contacts per account on average" / "limited — need enrichment"]
- Data gaps to fill: [e.g., "Missing technographic data for 60% of accounts" / "Intent data not yet connected"]

Current Program State:
- Current ABM maturity: [None / Beginning / Basic (account targeting only) / Intermediate (tiered program) / Advanced (full orchestration)]
- Active ABM tier structure (if any): [Describe current 1:1 / 1:few / 1:many breakdown]
- Channels currently active: [e.g., "LinkedIn Ads, outbound email, events" / list all]
- Current measurement: [e.g., "MQL-based only" / "Account engagement scoring in 6sense" / "No account-level reporting"]

Tech Stack Available:
- CRM: [Salesforce / HubSpot / Other]
- Marketing Automation: [Marketo / HubSpot / Pardot / Other]
- ABM / Intent Platform: [6sense / Demandbase / Bambora / TechTarget Priority Engine / G2 Buyer Intent / None]
- Data Enrichment: [Clay / ZoomInfo / Clearbit / Apollo / Lusha / None]
- Ad Platforms: [LinkedIn Campaign Manager / Google Display / The Trade Desk / Terminus / RollWorks / None]
- Website Personalization: [Mutiny / Intellimize / HubSpot Smart Content / None]
- Sales Engagement: [Outreach / Salesloft / Apollo Sequences / HubSpot Sequences]
- Analytics: [Salesforce Reports / HubSpot / Looker / Tableau / None]

Business Objectives:
- Primary program goal: [e.g., "Generate $3M in marketing-sourced pipeline from mid-market accounts in H2" or "Increase sales-accepted opportunities from ICP accounts by 40%"]
- Secondary goals: [e.g., "Shorten sales cycle by 15% for accounts touched by ABM" / "Improve MQL-to-SQL rate for ICP accounts"]
- Budget available: [$X/month total — split: $X paid media, $X tools, $X content/creative]
- Time to first results expected: [X months]

# OBJECTIVE
Design a complete, production-ready Programmatic ABM at Scale architecture for [Company Name] that I can begin implementing within 2 weeks, including all segmentation models, channel playbooks, content personalization frameworks, measurement systems, and the tier progression logic. Every output should be specific enough to hand to a marketing ops manager or demand gen lead to execute without additional strategy work.

# OUTPUT REQUIREMENTS

## SECTION 1: TAL SEGMENTATION & ACCOUNT SCORING MODEL

**1A. Intent Signal Taxonomy**
Define the complete signal stack for account scoring. For each signal source below, specify: what data point to capture, what score weight to assign (1–10 points), and what tool/integration captures it:

| Signal Category | Specific Signal | Points | Data Source |
|----------------|----------------|--------|-------------|
| 1st-Party Website | High-intent page visit (pricing, demo, ROI calculator) | 8–10 | HubSpot/GA4 |
| 1st-Party Website | Blog/resource consumption (3+ pages in session) | 3–5 | HubSpot/GA4 |
| 3rd-Party Intent | Bombora surge score spike on target topics | 6–8 | Bombora/6sense |
| G2 Buyer Intent | Viewed your G2 profile or compared you to a competitor | 7–9 | G2 Buyer Intent |
| LinkedIn | Company employees engaged with your ads or organic content | 4–6 | LinkedIn Insight Tag |
| Firmographic Trigger | Company posted a relevant job in last 30 days | 5–7 | Clay/ZoomInfo |
| Funding Event | Series A/B/C announced in last 90 days | 6–8 | Crunchbase/Clay |
| Tech Trigger | Newly adopted or removed a connected tool | 5–7 | HG Data/Clay |
| Email Engagement | ≥2 contacts at account opened email in last 30 days | 4–6 | MAP |
| CRM Activity | Open opportunity or prior closed-lost | 8–10 | CRM |

Fill in the weights based on what matters most for your specific ICP and sales motion.

**1B. Account Tier Classification Rules**
Using the scoring model above, define the threshold for each tier:

- **Tier 1 — Engaged (1:1 Enterprise ABM)**: Score [X]+ AND [specific qualitative criteria, e.g., "Open opportunity exists" or "CSuite contact made" or "Demo requested"]
  - Estimated % of TAL: [X%]
  - Ownership: Named AE + PMM + dedicated content
  
- **Tier 2 — Warm (1:Few Programmatic Personalization)**: Score [X–Y] OR [alternative criteria, e.g., "ICP company + 2+ website visits + job posting signal"]
  - Estimated % of TAL: [X%]
  - Ownership: ABM program automation + SDR outreach sequence

- **Tier 3 — Unaware (1:Many Programmatic Awareness)**: Score [<X] AND confirmed ICP fit
  - Estimated % of TAL: [X%]
  - Ownership: Fully automated — programmatic ads + nurture sequences only

**1C. Account Qualification Criteria (Non-Score Based)**
Beyond scoring, define the hard qualification criteria that place an account in or out of the TAL regardless of score: firmographic minimums, geographic inclusions/exclusions, competitive install disqualifiers, and account status filters (existing customers, current prospects, blacklist).

---

## SECTION 2: MULTI-CHANNEL ACTIVATION PLAYBOOK BY TIER

For each of the 3 tiers, design the specific channel orchestration:

### Tier 3 — Unaware Accounts: Programmatic Awareness Engine

**LinkedIn Ads Strategy**
- Audience targeting method: Company List Matching (upload TAL CSV to LinkedIn Campaign Manager; match rate target: >50%) + Matched Audience layered with job title targeting
- Campaign objective: Brand Awareness → Engagement → Conversion (progression over 90 days)
- Ad formats: [Specify mix — e.g., Single Image Ads for awareness, Document Ads for lead gen, Thought Leader Ads for exec amplification]
- Frequency cap: [X impressions per account per month to avoid ad fatigue]
- Budget allocation: [$X/month for Tier 3 LinkedIn — approximately $[X] CPM × [X] accounts × [X] impressions/account]
- Messaging angle: Problem-awareness and category education; NOT product-specific
- Sample ad headline for [primary ICP persona]: "[Write 3 headline variants testing pain, outcome, and insight angles]"

**Programmatic Display / ABM Platform**
- Platform: [RollWorks / Terminus / The Trade Desk / DV360 — specify which based on tech stack]
- Targeting approach: Domain-level targeting (upload TAL domain list); layer with contextual targeting on relevant publication categories
- Creative format: [300×250, 728×90, 160×600 standard display; expand if budget allows]
- Retargeting layer: Website visitors from TAL accounts get escalated to Tier 2 tracking
- Monthly spend: [$X — estimated $[X] CPM × [X] accounts]

**Email Nurture (Marketing Automation)**
- Trigger: Account enters TAL and is classified Tier 3
- Sequence length: [X emails over Y weeks]
- Personalization variables: Company name, industry, persona title
- Email 1 subject line (week 1): "[Write 3 subject line options — insight, question, provocation styles]"
- Email 2 subject line (week 3): "[Build on email 1; add social proof element]"
- Email 3 subject line (week 6): "[Soft CTA — resource offer, not demo request]"
- Unsubscribe / suppression rules: [Any contact who opts out removes their account from active sequences for X days]

**SDR Action Trigger for Tier 3**: NONE. Fully automated. SDR touches Tier 3 accounts only when they cross into Tier 2.

---

### Tier 2 — Warm Accounts: Personalized Activation Engine

**LinkedIn Ads Strategy (Tier 2 escalation)**
- Audience: Tier 2 account list re-uploaded to LinkedIn; add retargeting layer for website visitors from these accounts
- Campaign objective: Lead Generation / Demo Request
- Ad formats: Conversation Ads (for direct outreach to key personas) + Lead Gen Form Ads (gated content offer)
- Messaging angle: Solution-aware; highlight specific use cases matching their vertical or tech stack
- Sample Conversation Ad opening line for [primary ICP persona]: "[Write a direct, personalized opening that references their specific context — e.g., their industry, a pain point signal, or a company trigger]"

**Email Sequences (MAP — Segment-Personalized)**
- Personalization depth: Industry + persona + company size tier
- Sequence length: [X emails over Y weeks; more aggressive than Tier 3]
- Dynamic content rules: [Insert here — e.g., "If industry = FinTech, show payment compliance case study; if industry = HR Tech, show workforce cost reduction case study"]
- Email 1 subject line (triggered by score threshold crossing): "[Write 3 options — reference the specific signal that triggered the escalation, e.g., 'Noticed [Company] is evaluating options for X']"
- CTA escalation: Week 1 → resource offer; Week 3 → ROI calculator; Week 5 → demo request

**SDR Outreach Sequence (Sales Engagement Platform)**
- Trigger: Account reaches Tier 2 score threshold
- SDR action 1 (day 1): Personalized LinkedIn connection request + note referencing a company-specific context (recent news, job posting, or shared connection)
- SDR action 2 (day 3): Personalized email referencing what they've consumed (if known) or their industry pain point
- SDR action 3 (day 7): Phone call + voicemail script
- SDR action 4 (day 14): Break-up email with direct question

**Website Personalization (if Mutiny or equivalent available)**
- Rule: When visitor's IP resolves to a Tier 2 account's domain, activate dynamic content
- Homepage hero variant: Swap generic headline with industry-specific or persona-specific headline
- CTA variant: Change "Book a Demo" to "[Industry]-specific CTA, e.g., 'See how [Similar Company Type] reduced X by Y%'"
- Case study spotlight: Auto-display the most relevant customer story for their vertical

---

### Tier 1 — Engaged Accounts: Enterprise ABM Orchestration

For Tier 1, this program hands off to your 1:1 ABM or enterprise motion. Define the handoff protocol:
- Alert mechanism: CRM task created for named AE + Slack notification with account score and recent signal summary
- Account plan triggered: [Specify what sales gets — e.g., "Account intelligence brief" generated by Clay/6sense/Demandbase]
- Marketing support: Dedicated ABM campaign assets (personalized landing page, custom deck, executive outreach sequence co-developed with AE)
- Executive engagement: CMO/VP-level outreach authorized above $[X] ACV threshold
- Target timeline from Tier 1 classification to first meeting booked: [X business days]

---

## SECTION 3: DYNAMIC CONTENT PERSONALIZATION SYSTEM

Build the personalization matrix that makes your programmatic ABM feel 1:1 even at scale.

**3A. Segment Personalization Matrix**

| Account Segment | Ad Headline Variant | Email Opening Line Variant | Landing Page Hero | Case Study to Feature | Primary CTA |
|----------------|--------------------|--------------------------|--------------------|----------------------|-------------|
| FinTech (50–500 employees) | [Write specific headline] | [Write opening] | [Write hero text] | [Specify customer story] | [Specific CTA] |
| HR Tech / People Analytics | [Write specific headline] | [Write opening] | [Write hero text] | [Specify customer story] | [Specific CTA] |
| MarTech / Revenue Tech | [Write specific headline] | [Write opening] | [Write hero text] | [Specify customer story] | [Specific CTA] |
| Healthcare SaaS | [Write specific headline] | [Write opening] | [Write hero text] | [Specify customer story] | [Specific CTA] |
| Professional Services | [Write specific headline] | [Write opening] | [Write hero text] | [Specify customer story] | [Specific CTA] |

Fill this matrix with real content. The column that most dramatically improves conversion is almost always the "Case Study to Feature" — using proof from the buyer's own industry creates 2–4× higher engagement than generic proof.

**3B. Persona-Level Personalization Layer**
Within each industry segment, layer persona-level messaging for the 2–3 buying committee roles:

- **Economic Buyer (C-Suite / VP)**: Lead with business outcomes, ROI, and strategic risk reduction. Avoid technical details. Feature board-level metrics (ARR impact, CAC reduction, NRR improvement).
- **Champion (Director / Manager / Practitioner)**: Lead with workflow efficiency, ease of use, and personal credibility. Feature peer testimonials and community proof.
- **Technical Reviewer / IT / Security**: Lead with integration, security certifications, and implementation speed. Feature technical documentation and compliance credentials.

**3C. Personalization Technology Stack Implementation**
| Tool | Personalization Use Case | Implementation Complexity |
|------|------------------------|--------------------------|
| Mutiny | Homepage + landing page dynamic content by account | Medium (2–4 weeks to set up) |
| HubSpot Smart Content | Email body personalization by industry token | Low (days to activate) |
| LinkedIn Dynamic Ads | Ad image/copy variation by audience segment | Low (LinkedIn native feature) |
| Clay | Email hyper-personalization at account level using AI research | Medium |
| Demandbase / 6sense | IP-based website personalization | High (requires integration) |

---

## SECTION 4: ACCOUNT LIFT MEASUREMENT FRAMEWORK

The #1 failure mode in programmatic ABM is measuring it with MQL metrics. Account lift is what you measure.

**4A. Account Engagement Score Formula**
Define your composite Account Engagement Score (AES) — a single number that summarizes all buying signals at the account level:

AES = (Website Signal Score × 0.35) 
    + (Intent Data Score × 0.25) 
    + (Email Engagement Score × 0.15) 
    + (Ad Engagement Score × 0.10) 
    + (CRM Activity Score × 0.15)

Weights should be adjusted based on which signals most strongly correlate with pipeline conversion for your specific company. Start with these defaults and revise after 90 days of data.

**4B. Account Progression Stages**
Define the 5 stages of account progression through your ABM program:

| Stage | Name | Definition | Score Range | Target % of TAL |
|-------|------|-----------|-------------|----------------|
| 0 | Unaware | In TAL; no signals detected | 0–10 | 50–60% |
| 1 | Aware | 1st-party ad impression or website visit recorded | 11–25 | 20–25% |
| 2 | Engaged | Multiple signals; content consumption + email open | 26–50 | 10–15% |
| 3 | Active | High intent; pricing/demo page visit or G2 review activity | 51–75 | 5–8% |
| 4 | Sales Ready | Meeting booked, demo requested, or AE-qualified opportunity | 76+ | 2–3% |

**4C. The 4 ABM Program KPIs (Prove ROI to Leadership)**

1. **TAL Coverage Rate**: % of target accounts reached by at least 1 channel this quarter. Target: >70% of TAL in active channels. Measures: Are we actually reaching our market?

2. **Account Progression Rate**: % of Tier 3 accounts that advanced to Tier 2 or higher over 90 days. Target: >15% quarterly progression. Measures: Is the program moving accounts toward revenue?

3. **ABM-Influenced Pipeline**: Total pipeline value from opportunities at accounts in the ABM program. Measure: Pipeline from ABM-touched accounts vs. non-ABM-touched accounts (compare win rate, ACV, and sales cycle length). Target: ABM-touched accounts should show ≥20% higher win rate.

4. **Program ROI**: (Pipeline generated from ABM-influenced deals × average win rate × ACV) ÷ (Total ABM program spend). Target: ≥5× program ROI by month 6.

**4D. Account-Level Reporting Dashboard**
Build a weekly account intelligence view in your CRM or BI tool with these columns for all Tier 2 accounts:
- Account Name | Industry | AES Score | Score Change (WoW) | Tier | Last Signal | Channel Mix Active | AE Owner | Opportunity Status | Days in Current Stage

This dashboard becomes the standing agenda item for your weekly ABM review with sales.

---

## SECTION 5: TIER PROMOTION & DEMOTION LOGIC

**5A. Promotion Rules (Automated)**
Promotion from Tier 3 → Tier 2 triggers automatically when:
- AES crosses [X] point threshold (suggest starting at 30)
- OR: pricing/demo page visited by 2+ contacts from account
- OR: G2 intent signal fires for a competitor comparison with you included
- OR: Account firmographic trigger fires (new funding, new VP hire, technographic change)

When triggered: New account added to Tier 2 list (sync to LinkedIn Campaign Manager + CRM tag + SDR sequence enrollment)

Promotion from Tier 2 → Tier 1 triggers automatically when:
- AES crosses [X] point threshold (suggest starting at 60)
- OR: Demo requested or meeting booked
- OR: AE manually qualifies account based on outreach conversation

When triggered: AE is assigned, account plan is created, Tier 1 campaign assets are deployed, executive alignment activities begin

**5B. Demotion Rules (Automated)**
Demotion from Tier 2 → Tier 3 triggers automatically when:
- No signal activity for 60+ days AND no open opportunity
- Contact opted out of all communications from multiple personas at account
- Account firmographic change makes them out-of-ICP (e.g., acquired by a competitor)

**5C. Hard Suppression Rules**
Remove account from all active programs when:
- Existing customer (add to customer marketing program instead)
- Existing open opportunity (AE owns; no marketing orchestration without AE approval)
- Competitor company (suppress from all programs)
- Blacklisted account (legal, partnership, or executive decision)

---

## SECTION 6: 90-DAY LAUNCH ROADMAP

### Month 1: Infrastructure & Targeting Setup (Days 1–30)

**Week 1–2: Foundation**
- [ ] Export and clean the TAL: deduplicate, enrich with Clay/ZoomInfo, fill firmographic gaps
- [ ] Connect intent data sources (Bombora, G2 Buyer Intent, 6sense) to CRM
- [ ] Define and configure Account Engagement Score formula in CRM (custom field + score triggers)
- [ ] Upload TAL to LinkedIn Campaign Manager and The Trade Desk / RollWorks (verify match rates — target >50% match)

**Week 3–4: Content & Creative**
- [ ] Build the personalization matrix (Sections 3A and 3B) — identify content gaps by segment
- [ ] Create 3–5 ad creative sets for Tier 3 awareness (one per industry or pain-point segment)
- [ ] Write Tier 2 email sequences (3–5 emails per sequence, with industry personalization tokens)
- [ ] Set up LinkedIn Dynamic Ads and Conversation Ad templates
- [ ] Configure Mutiny (or HubSpot Smart Content) for at least 3 homepage personalization rules

**Key Month 1 Milestone**: TAL fully segmented; all tracking live; creative approved; channels ready to activate

---

### Month 2: Channel Activation & Baseline Measurement (Days 31–60)

**Week 5–6: Launch Tier 3**
- [ ] Activate LinkedIn Awareness campaigns for Tier 3 accounts
- [ ] Activate programmatic display for Tier 3 accounts
- [ ] Launch Tier 3 email nurture sequences
- [ ] Enable website personalization for Tier 2 and Tier 3 detected visitors
- [ ] Publish ABM dashboard in CRM; schedule weekly ABM review with sales

**Week 7–8: Activate Tier 2**
- [ ] Review first wave of Tier 3 accounts that crossed the Tier 2 threshold score
- [ ] Enroll qualified Tier 2 accounts in LinkedIn Conversation Ad sequences
- [ ] Begin SDR outreach sequences for top 20–30 Tier 2 accounts
- [ ] Test first round of Tier 2 emails; record open rates, click rates, and reply rates

**Key Month 2 Milestone**: All channels active; first SDR meetings booked from ABM program; account progression data in dashboard

---

### Month 3: Optimization & Scaling (Days 61–90)

**Week 9–10: Data Analysis & Optimization**
- [ ] Run 30-day account lift analysis: which accounts advanced from Tier 3 to Tier 2 or higher?
- [ ] Identify the highest-performing signal combination (what did accounts that progressed have in common?)
- [ ] A/B test ad creative: compare top 2 performing segments for winning messaging insight
- [ ] Calibrate AES thresholds based on observed progression data — adjust if too few or too many accounts are progressing

**Week 11–12: Scale & Systemize**
- [ ] Expand Tier 2 activation to next batch of qualified accounts
- [ ] Identify top 10 Tier 1 candidates; hand off to AE with account intelligence brief
- [ ] Create the first quarterly ABM program business review deck for CMO/VP Sales
- [ ] Document 3 winning signals, 3 winning messages, and 3 optimization lessons in the ABM playbook for future campaigns

**Key Month 3 Milestone**: First ABM-influenced opportunities in pipeline; account progression rate calculated; program ROI modeled; 90-day review delivered to leadership

---

## Example Input/Output

**Input Example:**
Company: Relatrix — AI-powered compensation planning software for scaling SaaS companies
ICP: VP People, CHRO, and Director of Total Rewards at B2B SaaS companies with 100–1,000 employees
TAL: ~2,200 accounts (pulled from ZoomInfo — SaaS companies, 100–1,000 employees, US + UK)
ACV: $48,000
Sales cycle: 6 weeks
Tools: HubSpot, LinkedIn Campaign Manager, Bombora (basic), Apollo, Clay
Budget: $18,000/month total ($12,000 paid media + $6,000 tools)
Challenge: Cold outbound response rates below 2%; brand unknown in mid-market HR Tech segment

**Output Example (Excerpt — Account Segmentation):**

**Tier 3 (Unaware) — ~1,500 accounts**
Signal threshold: <25 AES | ICP fit confirmed but no behavioral signals

Activation: LinkedIn Awareness ads (message: "Compensation planning in spreadsheets is costing your best people") + Bombora topic monitoring active + monthly educational newsletter sequence

**Tier 2 (Warm) — ~550 accounts**
Signal threshold: 25–60 AES OR (Bombora surge score >65 on topic "compensation benchmarking" OR "HR software") OR (2+ employees at account opened emails in last 30 days)

Current accounts estimated in Tier 2: 220 based on Bombora data + website visitor intelligence

Activation: LinkedIn Conversation Ads (opener: "I noticed [Company] has grown [X%] in headcount — curious how you're approaching comp benchmarking at that scale") + SDR sequence starting day 3 + website personalization showing SaaS-specific comp planning case study

**Tier 1 (Engaged) — ~30 accounts**
Signal threshold: AES >60 AND (demo page visited OR pricing page visited by 2+ contacts)

AE assignment: Immediate. Account plan built within 24 hours. First personalized outreach within 48 hours. Executive gifting authorized ($150 budget) if ACV > $60K projected.

## Success Metrics

- **TAL match rate on LinkedIn**: >50% (if below, enrich company data before re-upload)
- **Tier 3 → Tier 2 progression rate**: >12% of Tier 3 accounts advance in 90 days
- **ABM-sourced pipeline**: 15–25% of total pipeline is ABM-program-influenced by Month 4
- **ABM account win rate vs. non-ABM**: >20% higher win rate for ABM-touched accounts
- **Cost per account engaged**: <$80/account/quarter for Tier 3; <$200 for Tier 2
- **SDR meeting rate from Tier 2 outreach**: >8% (vs. typical 2–3% cold outbound)
- **Program ROI by Month 6**: >4× spend

## Related Prompts

- [ABM Intent Data Activation & Buying Signal Prioritization Engine](./ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [AI-Powered ABM Target Account List Building & ICP Scoring Intelligence Engine](./AI-Powered-ABM-Target-Account-List-Building-&-ICP-Scoring-Intelligence-Engine.md)
- [AI-Powered ABM Buying Committee Engagement Scoring & Multi-Stakeholder Deal Velocity Intelligence Engine](../../05_Analytics-&-Performance/Account-Based-Marketing-Analytics/AI-Powered-ABM-Buying-Committee-Engagement-Scoring-&-Multi-Stakeholder-Deal-Velocity-Intelligence-Engine.md)
- [AI-Powered B2B ABM Program Architecture & Account Tier Strategy Intelligence Engine](./AI-Powered-B2B-ABM-Program-Architecture-&-Account-Tier-Strategy-Intelligence-Engine.md)

## Integration Tips

**HubSpot Integration**
- Create a custom Account object property "ABM Tier" (values: Tier 1 / Tier 2 / Tier 3 / Suppressed)
- Build a workflow that auto-updates the tier field when the AES composite score crosses thresholds
- Use Smart Content rules in email templates to swap case study sections based on account Industry property
- Create an ABM Contacts list that syncs to LinkedIn Campaign Manager via native integration (HubSpot → LinkedIn Matched Audiences) — refreshes automatically as accounts are added or promoted

**Salesforce Integration**
- Create a custom field on Account object: `ABM_Tier__c` (picklist) and `ABM_Engagement_Score__c` (number)
- Use Salesforce Flow to trigger alerts to AE when an account moves from Tier 2 → Tier 1
- Build an ABM Dashboard using Account as the primary object, with related campaign influence records
- Connect 6sense or Demandbase directly to Salesforce for real-time intent score sync

**Clay Integration (for enrichment and personalization at scale)**
- Build a Clay table with your TAL; pull firmographic data, recent job postings, LinkedIn employee count growth, and news mentions
- Use Clay's AI column to write personalized email opening lines at account level (one per account, referencing a specific company signal)
- Output the personalized lines as a CSV; import into HubSpot/Outreach/Salesloft as a custom property for SDR sequence personalization

**LinkedIn Campaign Manager**
- Upload TAL as a Company List (requires 300+ companies minimum for match; upload all 2,000+)
- Create a separate campaign for each tier with matching budget, objectives, and creative
- Enable LinkedIn Insight Tag on your website to capture all company-level visitors from your TAL
- Use the Matched Audience retargeting feature to escalate engaged companies (those who visited your website) to a separate Tier 2 campaign

**Bombora / Intent Data**
- Configure topic clusters around your top 5 buyer pain points (not your product name — the problems you solve)
- Set weekly alerts for accounts showing surge scores above 60 — these are your Tier 2 escalation candidates
- Export Bombora data weekly; match to your TAL by domain; update AES in CRM automatically via Zapier or native integration

## Troubleshooting

**Problem: LinkedIn account match rate below 30%**
Solution: Your company list data quality is too low for LinkedIn to match. Fix in this order: (1) Add "LinkedIn Company URL" field to your TAL using Clay or ZoomInfo Enrichment — LinkedIn matches on URL far more accurately than company name; (2) Clean company name spelling against LinkedIn's exact naming; (3) Split your TAL into batches of 500–1,000 accounts per upload (LinkedIn matches better in smaller, cleaner batches).

**Problem: Tier 3 accounts aren't progressing to Tier 2 after 60 days**
Solution: This is usually a channel reach problem, not a messaging problem. Check: (1) What % of your Tier 3 accounts are actually seeing your LinkedIn ads? (Impression share in Campaign Manager — target >3 impressions/account/month); (2) Are your Bombora topics configured correctly? Test by checking if known ICP accounts are showing surge on your topics; (3) Is your email deliverability healthy? Run a sender reputation test — if inbox placement is below 85%, your sequence is landing in spam before it can create signals.

**Problem: SDRs aren't prioritizing ABM-sourced Tier 2 accounts over regular outbound**
Solution: This is a behavior change problem, not a data problem. Fix: (1) Build the ABM account list directly into the SDR's daily task view in Salesloft/Outreach — don't make them pull a separate report; (2) Set up a Slack alert that fires when a Tier 2 account crosses a score threshold, notifying the AE or SDR directly; (3) Share monthly ABM-sourced meeting conversion rates vs. cold outbound rates in the weekly sales standup — when SDRs see the data showing ABM accounts convert at 3× the rate, they prioritize automatically.

## Version History
- v1.0: Initial creation (auto-generated)
