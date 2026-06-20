# AI-Powered B2B SaaS Intent Data Waterfall Intelligence & Multi-Source Buyer Signal Orchestration Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** intent-data, demand-sensing, abm, buyer-signals, revenue-intelligence, b2b-saas, automation, orchestration, 6sense, bombora, g2-intent

## Overview
Synthesizes first-party, second-party, and third-party intent signals into a unified scoring waterfall that prioritizes accounts by purchase readiness, routes them to the right marketing program, and triggers AI-orchestrated engagement sequences — all without human intervention. Use this when you need to replace gut-feel account prioritization with a systematic, always-on buying signal intelligence layer that feeds ABM, outbound, and paid programs in real time.

## Quick Copy-Paste Version

You are a senior revenue intelligence analyst specializing in B2B intent data orchestration. Build a comprehensive intent data waterfall model and activation playbook for the following company.

COMPANY CONTEXT:
- My company: [Company name and what we sell]
- ICP: [Industries, company sizes, titles we sell to]
- Average deal size: [$X ACV]
- Sales cycle length: [X days]
- Current intent data tools: [e.g., Bombora, 6sense, G2 Buyer Intent, TechTarget, Demandbase, none]
- CRM: [HubSpot / Salesforce / other]
- Marketing automation: [Marketo / HubSpot / Pardot / other]

INTENT SIGNALS AVAILABLE (check all that apply):
- [ ] 1st party: Website visits, page depth, content downloads, email opens/clicks, trial signups, product usage
- [ ] 2nd party: G2 category page views, TrustRadius comparisons, Capterra shortlist additions, peer review activity
- [ ] 3rd party: Bombora surge topics, TechTarget intent, Aberdeen intent data, IDG/Foundry audience signals
- [ ] Technographic: BuiltWith installs, HG Insights, Slintel stack data
- [ ] Job signals: LinkedIn hiring for roles related to your category, Glassdoor postings
- [ ] Firmographic triggers: Funding rounds, leadership changes, M&A activity, headcount growth
- [ ] Competitive signals: G2 competitor page views, review comparison clicks, social mentions of competitors

Build the following deliverables:

1. INTENT SCORING WATERFALL MODEL
Create a tiered scoring system that combines all available signals into a single Account Intent Score (0-100):
- Signal weights by tier (1st party = highest weight, 3rd party = directional confirmation)
- Score thresholds for each intent tier: Hot (85+), Active (65-84), Surging (45-64), Monitoring (below 45)
- Score decay rules (how quickly scores degrade without new signals)
- Minimum signal requirements for each tier (to prevent false positives)

2. ACCOUNT PRIORITIZATION OUTPUT
For each intent tier, produce:
- Recommended account list criteria (firmographic filters + intent score threshold)
- Expected account volume at each tier per month
- Estimated pipeline coverage this model should generate (based on conversion benchmarks)
- Sales prioritization SLA for each tier (e.g., Hot accounts: SDR outreach within 4 hours)

3. MARKETING PROGRAM ROUTING RULES
Map intent tiers to specific marketing programs:
- Hot (85+): [What campaign/sequence should trigger?]
- Active (65-84): [What nurture program, ABM campaign, or retargeting?]
- Surging (45-64): [What awareness/consideration content?]
- Monitoring (<45): [What low-cost nurture to maintain?]
Include: trigger mechanism, channel, content type, cadence, and handoff point to sales

4. BUYING COMMITTEE SIGNAL AMPLIFICATION
For each hot account, describe how to expand from one contact's intent signal to full buying committee coverage:
- Steps to identify other stakeholders at the account
- Signal types that suggest committee-level engagement has started
- How to personalize outreach per stakeholder role once intent is confirmed

5. INTENT DATA QUALITY RULES
Specify guardrails to prevent poor-quality signal from wasting sales resources:
- Minimum signal recency (e.g., signal must be < 14 days old to qualify for Hot tier)
- Account blacklist criteria (competitors, existing customers, wrong-size accounts)
- Signal spike detection rules (single-day anomalies vs. sustained intent patterns)
- Manual override conditions (when sales can flag intent scores as incorrect)

6. MEASUREMENT FRAMEWORK
Define the KPIs to prove the waterfall model is working:
- Intent-to-opportunity conversion rate by tier
- Time-from-intent-signal-to-pipeline-creation
- Revenue influenced by intent-triggered programs
- Signal accuracy rate (% of Hot accounts that eventually convert)

Format as a structured intelligence playbook with tables, scoring matrices, and clear routing logic. Flag any data gaps that would significantly improve model accuracy.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Operations and Marketing Intelligence with 15+ years of experience building intent data infrastructure for B2B SaaS companies. You have implemented multi-source intent orchestration at scale using 6sense, Demandbase, Bombora, and G2 Buyer Intent, and you specialize in translating raw signal data into automated GTM actions that generate pipeline without adding headcount. You understand the nuances of signal quality, data decay, false positive management, and cross-functional alignment between marketing, sales, and customer success on shared account intelligence.

---

COMPANY PROFILE:
- Company name: [Your company]
- Product category: [e.g., Revenue Intelligence Platform / HR Software / Cybersecurity / FinTech]
- Business model: [SaaS / Usage-based / Hybrid]
- ARR stage: [e.g., $15M Series B / $80M Series D]
- GTM motion: [Inbound / Outbound / ABM / PLG / Channel / Hybrid — specify primary]
- Average ACV: [$X for SMB / $Y for mid-market / $Z for enterprise]
- Sales cycle: [X days average, broken down by segment if different]
- Target segments:
  - Segment 1: [Name] | Industries: [X, Y] | Headcount: [X-Y] | Buyer titles: [A, B, C]
  - Segment 2: [Name] | Industries: [X, Y] | Headcount: [X-Y] | Buyer titles: [A, B, C]
  - Segment 3: [Name] (optional) | Industries: [X, Y] | Headcount: [X-Y] | Buyer titles: [A, B, C]
- TAL size: [Total addressable accounts in CRM / TAM]
- Current CRM: [Salesforce / HubSpot / other]
- Marketing automation: [Marketo / HubSpot / Pardot / other]
- Outbound sequencing tool: [Outreach / Salesloft / Apollo / other]
- Paid retargeting: [LinkedIn / 6sense DSP / Demandbase / Google / other]

---

INTENT DATA STACK:
List all available intent sources with data freshness and coverage:

First-Party (owned signals — highest fidelity):
- Website: [GA4 / Segment / Heap / other — pages tracked, session depth, form fills]
- Product: [Amplitude / Mixpanel / Pendo / in-house — trial behavior, feature usage, upgrade triggers]
- Email: [HubSpot / Marketo / other — open rates, click patterns, content engagement sequences]
- Events: [Webinar attendance, virtual event engagement, in-person event badge scans]
- Content: [Gated asset downloads, video completion rates, interactive tool usage]
- Support: [Zendesk / Intercom ticket themes, product feedback signals]

Second-Party (partner/publisher signals — high fidelity for category intent):
- G2: [Buyer Intent — category pages, comparison pages, competitor pages, shortlist additions]
- TrustRadius: [Category research intent, vendor comparison intent]
- Capterra / GetApp / Software Advice: [Category listing traffic, demo requests for competitors]
- TechTarget / IDG Foundry: [Priority Engine — active IT research topics]
- Peer community signals: [Slack communities, Discord, LinkedIn groups where ICP researches]

Third-Party (anonymized panel data — directional intent, needs corroboration):
- Bombora: [Company Surge topics — list your top 15-20 intent topics]
- Aberdeen: [Intent data on specific technology categories]
- Slintel / ZoomInfo Intent: [Technographic and intent combined signals]
- LinkedIn Matched Audiences: [Retargeting based on website visits and content engagement]

Technographic Signals (stack intelligence — purchase readiness indicators):
- HG Insights / BuiltWith / Slintel: [Competitor installs, adjacent tech stack, renewal timing]
- Job postings scraping: [Roles being hired that signal budget and initiative]

Firmographic Triggers (event-driven signals — timing windows):
- Funding events: [Seed / Series A–D / PE buyout triggers]
- Leadership changes: [New CXO / VP hires in buyer functions]
- M&A activity: [Acquisitions, mergers creating platform consolidation opportunities]
- Headcount growth: [Rapid expansion signals budget availability]
- Contract renewal cycles: [Competitor renewal windows from ZoomInfo / Slintel]

---

COMPETITIVE INTELLIGENCE LAYER:
- Primary competitor 1: [Name] | Intent topics that signal consideration: [X, Y, Z] | G2 profile URL to monitor: [URL]
- Primary competitor 2: [Name] | Intent topics: [X, Y, Z] | G2 profile: [URL]
- Primary competitor 3: [Name] | Intent topics: [X, Y, Z] | G2 profile: [URL]
- Key displacement signals: [What behaviors suggest a prospect is unhappy with a competitor?]

---

DELIVERABLE 1 — INTENT SCORING WATERFALL ARCHITECTURE

Build a complete scoring model with the following structure:

**Signal Weight Matrix:**
| Signal Source | Signal Type | Base Score | Recency Multiplier | Frequency Boost | Max Contribution |
|---|---|---|---|---|---|
| 1st party: High-value page (pricing, demo) | Own | 25 pts | 1.5x if <48hrs | +5 per repeat visit | 40 pts |
| 1st party: Trial/PLG product activation | Own | 35 pts | 1.0x (evergreen) | N/A | 35 pts |
| 1st party: Email — 3+ clicks in sequence | Own | 15 pts | 1.2x if <7 days | N/A | 18 pts |
| 2nd party: G2 category + competitor page | Partner | 20 pts | 1.3x if <7 days | +3 per additional page | 30 pts |
| 3rd party: Bombora surge (matched topics) | Panel | 12 pts | 1.0x | +2 per additional topic | 20 pts |
| Technographic: Competitor install detected | Stack | 15 pts | 0.7x if >90 days | N/A | 15 pts |
| Firmographic: Funding round in past 30 days | Event | 10 pts | 0.5x decay after 60 days | N/A | 10 pts |
| Job posting: Relevant budget-owning role | Event | 8 pts | 0.8x decay after 45 days | +2 per additional role | 12 pts |
| Firmographic: New CXO hire in buyer dept | Event | 10 pts | 1.4x if <30 days | N/A | 14 pts |

**Intent Tier Definitions:**
- **TIER 1 — HOT (85-100 pts):** Active in-market buyer. Multiple corroborating signals from ≥2 sources. ≥1 first-party signal required. Immediate sales engagement + ABM personalization.
- **TIER 2 — ACTIVE (65-84 pts):** In consideration phase. Researching category or comparing vendors. ABM advertising + personalized content + SDR sequence.
- **TIER 3 — SURGING (45-64 pts):** Early-stage interest or trigger event detected. Awareness campaigns, intent-targeted ads, content nurture.
- **TIER 4 — MONITORING (<45 pts):** Weak or single-source signal. Low-cost programmatic nurture only. No SDR resources allocated.

**Score Decay Rules:**
- Tier 1 signals (first-party behavioral): decay 10 pts/week without new activity
- Tier 2 signals (second-party publisher): decay 5 pts/week
- Tier 3 signals (third-party Bombora): decay 3 pts/week
- Trigger events (funding, hire): fixed decay schedule — 100% weight for 30 days, 50% for days 31-60, 10% for days 61-90, retired at 91 days

**False Positive Prevention Rules:**
- Exclude: Existing customers (tag in CRM), competitors, accounts <50% ICP score fit
- Minimum signal: No account enters Tier 1 from third-party signal alone — requires ≥1 first-party or second-party corroboration
- Spike filter: Single-day signal anomalies (1 Bombora surge topic, 1 page visit) are logged but don't advance tier until sustained ≥3 days
- Bot traffic exclusion: Filter sessions <10 seconds on high-value pages

---

DELIVERABLE 2 — ACCOUNT PRIORITIZATION & ROUTING PLAYBOOK

For each intent tier, specify the complete marketing and sales response:

**TIER 1 — HOT ACCOUNT PLAYBOOK:**
Marketing Actions (automated):
- Trigger: Real-time webhook from intent platform → CRM field update → Salesforce/HubSpot workflow fires
- LinkedIn: Move account into 1:1 ABM LinkedIn campaign with decision-maker-specific creative (within 2 hours)
- 6sense/Demandbase DSP: Activate premium display retargeting for all known contacts at account (budget: $X/day cap per account)
- Website personalization: Flip homepage headline + CTA for recognized IP to buyer-specific message (if using Mutiny/Clearbit Reveal)
- Content: Surface highest-converting case study for account's industry via email or direct mail
Sales Actions:
- SLA: SDR must action within 4 business hours of Tier 1 trigger
- Research package: AI-generated account research brief delivered to SDR/AE (firmographics, recent news, stakeholder map, talking points)
- Outreach sequence: Launch 7-touch, 14-day sequence — email Day 1, LinkedIn Day 2, call Day 3, email Day 5, LinkedIn Day 8, call Day 10, email Day 14
- Escalation: If no response after 7-touch, AE sends personalized video (Vidyard/Loom) to economic buyer
CS Actions (if existing customer adjacent):
- Alert CSM if account is a subsidiary or acquirer of existing customer

**TIER 2 — ACTIVE ACCOUNT PLAYBOOK:**
Marketing Actions (automated):
- LinkedIn Matched Audiences: Add all known contacts to ABM retargeting campaign (consideration-stage creative)
- Email nurture: Enroll in intent-specific email track (competitor comparison content, ROI calculators, peer testimonials)
- Content syndication: Prioritize Tier 2 accounts in content syndication targeting (TechTarget, IDG)
- Webinar: Auto-invite to next relevant webinar via HubSpot workflow
Sales Actions:
- SLA: SDR must action within 48 business hours
- Outreach: 5-touch, 21-day sequence — lighter cadence, more educational, less "buy now"
- Research: AI-generated brief, lighter version — top 3 talking points and relevant content to share

**TIER 3 — SURGING ACCOUNT PLAYBOOK:**
Marketing Actions (automated):
- Programmatic advertising only: Low-CPM display via 6sense or LinkedIn to maintain awareness
- Content: If email address known, enroll in 60-day educational drip sequence
- No SDR resources allocated
Sales Actions:
- No proactive outbound; inbound response SLA applies if they contact us

**TIER 4 — MONITORING PLAYBOOK:**
Marketing Actions:
- Quarterly email newsletter only
- Passive retargeting at low frequency cap
- Watch for tier promotion events

---

DELIVERABLE 3 — BUYING COMMITTEE SIGNAL EXPANSION PROTOCOL

When a Tier 1 or 2 account is identified, execute this buying committee mapping sequence:

**Step 1 — Stakeholder Discovery (Day 0-2):**
- Use LinkedIn Sales Navigator: Search account for roles matching buyer persona titles
- ZoomInfo/Apollo: Pull contact list for account, filter by seniority and department
- AI enrichment: Run account through Clay/Clearbit to add email, phone, LinkedIn profile
- Output: Buying committee map with 4-7 contacts — economic buyer, technical evaluator, end user champion, procurement/legal (if enterprise)

**Step 2 — Multi-Threaded Engagement (Day 3-7):**
- Connect with each stakeholder on LinkedIn (personalized message based on their role-specific pain point)
- Enroll each contact in role-appropriate email sequence (VP-level: business value message; technical evaluator: security/integration message; end user: productivity/ease-of-use message)
- Add each contact to LinkedIn Matched Audiences for role-specific ad creative

**Step 3 — Committee-Level Intent Confirmation (Ongoing):**
- Upgrade account from Tier 1 to "Committee-Level Hot" when ≥3 stakeholders show independent signals (separate email clicks, G2 page visits from different IP segments, or LinkedIn engagement from multiple contacts)
- Trigger: AE involvement + executive alignment outreach from internal sponsor (CEO/CRO email to economic buyer)

**Stakeholder Intent Signal Matrix:**
| Stakeholder Role | High-Signal Behaviors | Recommended First Touch |
|---|---|---|
| Economic Buyer (CEO/CFO/CRO) | LinkedIn profile visits your page, downloads ROI content, G2 comparison | Executive-to-executive email from your CRO/CEO |
| Technical Evaluator (IT/Security/Engineering) | Documentation page visits, integration page, security whitepaper download | Technical SDR with product deep-dive angle |
| End User Champion (Dept Head/Manager) | Feature comparison, case study download, webinar registration | BDR with peer success story + product demo offer |
| Procurement/Legal | Pricing page + T&C page visits | Send procurement guide proactively via direct mail or email |
| Influencer (Analyst/Consultant) | Category research pages, competitor comparison | Partner/channel team outreach for co-sell opportunity |

---

DELIVERABLE 4 — INTENT DATA MEASUREMENT FRAMEWORK

**Primary KPIs (measure monthly):**
| Metric | Definition | Target Benchmark | Current Baseline |
|---|---|---|---|
| Intent-to-Opportunity Rate | % of Tier 1 accounts that become pipeline opportunities within 90 days | >25% for Tier 1 | [Your current %] |
| Signal-to-Pipeline Time | Days from first Tier 1 signal to opportunity creation | <21 days | [Your current days] |
| Intent-Influenced Revenue | Revenue from accounts that were in Tier 1 or 2 before opportunity creation | >40% of total new ARR | [Your current %] |
| Tier Accuracy Rate | % of Tier 1 accounts that take a meaningful sales meeting within 60 days | >35% | [Your current %] |
| False Positive Rate | % of Tier 1 accounts that never engage despite SDR outreach | <50% (target <30%) | [Your current %] |
| Multi-Source Signal Rate | % of Tier 1 accounts with signals from ≥2 data sources | >60% | [Your current %] |
| Score Decay Health | % of accounts that maintain Tier 1+ for >14 days (sustained vs. spike) | >40% | [Your current %] |

**Segmented Analysis (run quarterly):**
- Intent model performance by ICP segment (does the waterfall work equally well for SMB vs. enterprise?)
- Signal source contribution (which sources most reliably predict conversion — prune poor performers)
- Buying committee coverage rate (what % of Tier 1 accounts have ≥3 contacts engaged?)
- Revenue per intent tier (validate that Tier 1 generates meaningfully more revenue than Tier 2)

**Attribution Model:**
- Tag all intent-triggered programs with UTM + CRM campaign source for attribution
- Build intent-influenced pipeline report in Salesforce/HubSpot: any account that was Tier 1 or Tier 2 within 90 days before opportunity creation counts as intent-influenced
- Separate from intent-sourced: intent-sourced = intent signal preceded any first contact; intent-influenced = signal occurred during active sales cycle

---

DELIVERABLE 5 — IMPLEMENTATION ROADMAP

**Phase 1 (Days 1-30): Foundation**
- Audit existing data sources and fill coverage gaps (goal: have at least 1st party + 1 second or third party source)
- Configure CRM fields: Account Intent Score (numeric), Intent Tier (picklist), Signal Sources (multi-select), Last Intent Update (date), Intent Tier Change Date (date)
- Build CRM workflows to auto-update fields when intent platform sends data
- Define TAL (Total Addressable List) in CRM — all accounts within ICP that will be scored

**Phase 2 (Days 31-60): Scoring & Routing**
- Configure intent scoring rules in 6sense/Demandbase/HubSpot
- Build Tier 1 alert workflow: Slack notification to SDR manager + rep assignment
- Build marketing routing workflows: auto-enroll by tier into respective programs
- QA: Run waterfall model for 30 days, review Tier 1 list manually for false positive rate

**Phase 3 (Days 61-90): Optimization & Scale**
- First model review: Adjust signal weights based on real conversion data
- Add buying committee enrichment workflow (Clay/Apollo auto-enrichment on Tier 1 trigger)
- Build intent performance dashboard (Salesforce/Tableau/Looker) for weekly review
- Train SDR team on intent-first prospecting model and new SLAs
- Scale to full TAL coverage

**Phase 4 (Ongoing): Intelligence Compounding**
- Monthly signal weight review based on conversion data
- Quarterly intent data vendor review (add/remove sources based on ROI)
- Annual TAL refresh and ICP re-scoring
- AI-driven model refinement: use conversion data to auto-adjust weights (6sense predictive, Demandbase AI scoring)

---

CONSTRAINTS:
- All routing workflows must be executable without human intervention (full automation)
- Any action requiring sales must have SLA defined and monitored
- Intent scores must update in CRM within 4 hours of new signal ingestion
- No budget allocated to any account below Tier 2 threshold
- GDPR/CCPA compliance: Only use intent data from vendors with compliant data collection practices; honor opt-outs in all triggered sequences

## Example Input/Output

**Example Input:**

Company: Nexus Analytics — a B2B data observability platform for data engineering teams
ICP: Series B+ companies, 200-2000 employees, industries: FinTech, Healthcare Tech, E-commerce
Buyer titles: VP Data Engineering, Head of Data Platform, Chief Data Officer
ACV: $85,000 average
Sales cycle: 67 days average
Intent tools: G2 Buyer Intent (active), Bombora (30-day trial starting), HubSpot for 1st party
Bombora topics purchased: "Data observability," "data pipeline monitoring," "data quality management," "DataOps," "dbt," "Snowflake data management," "Monte Carlo alternatives," "Soda alternatives"
Competitors to monitor: Monte Carlo, Soda, Great Expectations (open source)

**Example Output (Tier 1 Account Alert):**

**Account: Meridian Capital Markets**
- Intent Score: 92/100 — TIER 1 HOT
- Signal sources (3 active):
  - 1st party: Pricing page visited 4x in 7 days from 3 different contacts (14 pts, 1.5x recency boost = 21 pts)
  - 2nd party: G2 — Monte Carlo product page + Nexus Analytics comparison page viewed same session (23 pts, 1.3x recency boost = 30 pts)
  - 3rd party: Bombora surge on "data observability" + "data pipeline monitoring" (Week 3 of sustained surge) (24 pts)
  - Job signal: 2 open Data Engineering Manager roles posted (8 pts)
  - Total: 83 base + 9 boost = 92 pts

- Buying committee identified (via LinkedIn Sales Navigator):
  - Priya Mehta, VP Data Engineering — primary decision maker (visited pricing page 3x)
  - Marcus Wei, Head of Data Platform — technical evaluator (visited integration docs page)
  - Rebecca Torres, CDO — economic buyer (not yet engaged — priority to add)

- Recommended actions (next 4 hours):
  1. SDR: Assign to Jordan Kim (FinTech segment) — deliver AI research brief
  2. LinkedIn: Launch personalized ad campaign targeting Priya + Marcus + 5 additional data team contacts at Meridian
  3. Email: Enroll Priya in "Monte Carlo Migration" sequence (specifically for competitor comparison intent)
  4. Direct mail: Send FinTech Data Observability ROI Report to Priya (physical, via Sendoso — $45 item)
  5. AE alert: Jake Sullivan to prepare for warm handoff this week

- AI-generated SDR talking point:
  *"Priya, I noticed Meridian is actively evaluating data observability solutions — specifically comparing Monte Carlo with alternatives. We just helped First National Bank reduce data incident response time by 73% in 60 days. Worth a 15-minute conversation this week?"*

## Success Metrics

Your intent waterfall model is working when:
- **Tier 1 accuracy >35%:** More than 1 in 3 Tier 1 accounts take a qualified meeting within 60 days
- **Intent-to-pipeline rate >20%:** 1 in 5 Tier 1 accounts becomes a pipeline opportunity within 90 days
- **Signal-to-pipeline time <21 days:** Hot accounts move to pipeline in under 3 weeks on average
- **Multi-source confirmation >60%:** Majority of Tier 1 accounts have signals from at least 2 independent sources
- **Intent-influenced revenue >35% of new ARR:** Demonstrating that intent-triggered programs contribute meaningfully to bookings
- **False positive rate trending down:** Month-over-month improvement in Tier 1 conversion rates as model is refined
- **SDR SLA compliance >90%:** Sales team responds to Tier 1 accounts within the 4-hour window

## Related Prompts

- [AI-Powered Demand Sensing & Market Signal Intelligence Engine](./AI-Powered-Demand-Sensing-&-Market-Signal-Intelligence-Engine.md)
- [ABM Intent Data Activation & Buying Signal Prioritization Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [AI-Powered ABM Daily Account Intelligence Brief & Buying Signal Flash Report Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-ABM-Daily-Account-Intelligence-Brief-&-Buying-Signal-Flash-Report-Intelligence-Engine.md)
- [AI-Powered B2B Full-Funnel Journey Stitching & Anonymous-to-Pipeline Revenue Intelligence Engine](../Customer-Journey-Analytics/AI-Powered-B2B-Full-Funnel-Journey-Stitching-&-Anonymous-to-Pipeline-Revenue-Intelligence-Engine.md)

## Integration Tips

**Salesforce:**
- Create custom Account fields: `Intent_Score__c` (Number), `Intent_Tier__c` (Picklist: Hot/Active/Surging/Monitoring), `Intent_Signal_Sources__c` (Multi-select), `Intent_Last_Updated__c` (DateTime), `Days_in_Current_Tier__c` (Formula)
- Build Process Builder / Flow: When `Intent_Tier__c` changes to "Hot," create a Task assigned to account owner with 4-hour due date, send Slack alert to SDR manager channel
- Reports: Build "Intent-Influenced Pipeline" report — filter Opportunities where Account had Intent_Score > 65 within 90 days before Close Date

**HubSpot:**
- Use Custom Properties for intent scoring; build Workflows triggered by property updates
- Connect 6sense or Bombora via native HubSpot integration or Zapier webhook
- Build Smart Lists: "Tier 1 Accounts (Last 7 Days)" for real-time SDR prioritization view
- Sequences: Tag intent-triggered sequences separately from standard outreach for performance comparison

**6sense / Demandbase:**
- Use native AI scoring model as primary Tier 1/2 signal, layer Bombora surge topics as confirmation
- Configure 6sense Segments to feed directly into LinkedIn Matched Audiences for real-time ad activation
- Connect 6sense predictive model output to Salesforce via native connector — no manual export needed

**Bombora + Zapier:**
- Weekly Bombora Company Surge report → Zapier → Google Sheets → HubSpot/Salesforce bulk update via API
- Set up topic alerts for top 10 intent topics; route surge accounts into CRM scoring workflow

**Clay.com:**
- Build automated enrichment waterfall: New Tier 1 account → Clay waterfall (ZoomInfo → Apollo → LinkedIn) → populate buying committee contacts → push to CRM + outreach sequencer
- Add AI-generated personalization fields based on company news, job postings, and intent signal type

**Slack Alerts:**
- Configure #intent-alerts channel: Post when account moves to Tier 1 with one-click SDR claim button
- Weekly digest: Top 10 new Tier 2 accounts promoted this week, top signal movers

## Troubleshooting

**Problem: Tier 1 list is too large (>50 accounts/month) and SDR team can't work them all**
- Root cause: Signal weights too permissive or minimum signal requirements too low
- Fix: Raise Tier 1 threshold from 85 to 90+ AND require ≥2 corroborating sources for Tier 1 eligibility. This should cut Tier 1 by 40-60% while keeping highest-confidence accounts. Move displaced accounts to Tier 2 marketing automation.

**Problem: Intent signals appear but accounts never convert — high false positive rate**
- Root cause: Third-party intent data (Bombora) is creating false urgency without first-party corroboration; or TAL includes out-of-ICP accounts inflating signal
- Fix: Remove Bombora-only accounts from Tier 1 eligibility (require first or second-party corroboration). Audit TAL for ICP fit — remove accounts below 70% ICP fit score regardless of intent signal. Consider purchasing 6sense AI model instead of raw Bombora signals for better prediction accuracy.

**Problem: SDRs are ignoring intent alerts and following their own prospecting lists**
- Root cause: SDRs don't trust the model, don't understand the signals, or have misaligned incentives
- Fix: Run a 30-day A/B test — have half of SDR team work intent-prioritized accounts vs. their self-sourced list. Share conversion data weekly. Celebrate wins from intent-triggered outreach in team standups. If SDR compensation is entirely self-source-incentivized, align with RevOps to add "intent response SLA" as a performance metric in SDR scorecards.

## Version History
- v1.0: Initial creation (auto-generated)
