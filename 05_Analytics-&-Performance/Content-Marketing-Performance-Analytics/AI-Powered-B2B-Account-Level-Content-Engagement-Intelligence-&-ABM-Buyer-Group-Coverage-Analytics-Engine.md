# AI-Powered B2B Account-Level Content Engagement Intelligence & ABM Buyer Group Coverage Analytics Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** content-analytics, abm, account-engagement, buying-committee, content-intelligence, b2b-saas, marketing-analytics, intent-signals, revenue-marketing

## Overview
Transforms anonymous content consumption data into named-account intelligence — identifying which target accounts are engaging with your content, which buying group roles are covered vs. missing, and exactly when content engagement velocity signals readiness for sales outreach. Use this when your ABM program lacks visibility into whether target accounts are actually reading your content, or when you need content engagement signals to trigger and personalize sales plays.

## Quick Copy-Paste Version

You are a B2B account-based marketing analytics expert specializing in connecting content engagement signals to account intelligence and sales activation. Help me build an account-level content engagement analytics system.

My context:
- Company: [Your Company Name — e.g., B2B SaaS for supply chain teams]
- Target account list size: [e.g., 300 Tier 1 accounts, 800 Tier 2 accounts]
- ICP buying committee: [e.g., VP Supply Chain, IT Director, CFO, Procurement Manager — typical 4-6 roles]
- Average deal size: [$X ACV]
- Sales cycle: [X days average]
- Content types published: [blog posts, white papers, case studies, webinars, product pages, comparison pages]
- Monthly content pieces: [X]
- Tech stack: [e.g., HubSpot/Salesforce + 6sense/Demandbase + GA4 + Clearbit/Apollo]
- Current gap: [e.g., "we publish content but can't tell which target accounts are consuming it," "sales doesn't know when an account is warming up via content," "we have no way to see if all 5 buying committee personas are engaged"]

Please deliver:

1. ACCOUNT CONTENT ENGAGEMENT SCORE — a per-account composite score (0–100) that rolls up individual contact-level content interactions into account-level engagement. Define: weight per content type (case study = 3×, white paper = 2.5×, comparison page = 3×, blog = 1×, webinar = 4×), decay logic (engagement older than 30 days decays 25%/week), and recency multipliers (engagement in last 7 days = 1.5× weight). Specify exactly which CRM + MAP fields to use.

2. BUYING GROUP COVERAGE ANALYSIS — for each target account, identify which buying committee personas have engaged with content vs. which are dark. Define coverage tiers: FULL COVERAGE (5/5 personas engaged in last 90 days) → PARTIAL (2-4/5 engaged) → SINGLE-THREADED (1/5 engaged) → DARK (0 contacts engaged). Output: per-account persona gap report with content recommendations for each un-engaged role.

3. CONTENT ENGAGEMENT VELOCITY TRACKING — measure the rate of engagement increase at each account over rolling 4-week windows. Flag accounts with engagement velocity acceleration ≥ 50% WoW for 2+ consecutive weeks as SURGING — these are your highest-priority accounts for immediate sales activation.

4. CONTENT-TRIGGERED SALES PLAY MATRIX — define the exact content engagement thresholds that trigger specific sales actions:
   - Tier 1 account, champion engages with pricing page + case study within 72 hours → SDR same-day call + AE executive outreach
   - Tier 1 account, 3+ buying committee members engage with same topic cluster within 7 days → AE sends personalized insight email + requests discovery
   - Tier 2 account engagement score crosses 60+ → move to Tier 1 nurture track + add to SDR sequence
   - Any account: C-suite contact engages with competitor comparison page → immediate AE notification

5. ACCOUNT CONTENT GAP ANALYSIS — for each target account that has been in your pipeline for 60+ days without advancing stage, identify: which content types/topics have NOT been consumed, which persona is under-engaged, and recommend 2-3 specific content pieces to deploy via direct outreach or personalized email.

6. DARK ACCOUNT REACTIVATION PRIORITIZATION — rank your target accounts that have ZERO content engagement in the last 90 days by: ICP fit score × firmographic revenue potential × competitor signal strength. Output a top-25 dark account list with personalized content outreach recommendations per account.

Output: Account engagement dashboard spec, weekly sales activation alert format, and 30-60-90 day account warming playbook.

## Advanced Customizable Version

ROLE:
You are a world-class B2B account-based marketing intelligence architect with 14+ years experience running data-driven ABM programs at enterprise SaaS companies. You specialize in translating first-party content consumption signals into actionable account intelligence that sales teams can act on within hours — not weeks. You understand that B2B buying is a group sport, that 67% of buying committee research happens before any contact with sales, and that the companies that win instrument every anonymous and known content touchpoint at the account level. You build measurement systems that make ABM programs provably revenue-generating, not just "awareness-building."

CONTEXT — MY ABM + CONTENT PROGRAM:
Company name: [Company]
Industry / vertical: [e.g., FinTech, Supply Chain SaaS, HR Tech, Cybersecurity]
ICP definition: [e.g., VP Operations + IT Director + CFO at manufacturing companies 1,000–10,000 employees, $500M–$5B revenue]
ARR: [$X]
Average deal size: [$X ACV]
Sales cycle: [X days]

Target account program:
- Tier 1 accounts: [X accounts — highest ICP fit, direct AE coverage]
- Tier 2 accounts: [X accounts — strong ICP, SDR + digital coverage]
- Tier 3 accounts: [X accounts — programmatic/digital-only coverage]
- Total TAL size: [X accounts]

Buying committee structure (your ICP):
- Role 1 (Economic Buyer): [e.g., CFO / VP Finance — final budget authority]
- Role 2 (Champion): [e.g., VP Operations — day-to-day pain owner, internal sponsor]
- Role 3 (Technical Evaluator): [e.g., IT Director / CTO — security, integration, infra review]
- Role 4 (End User): [e.g., Operations Manager — workflow impact assessment]
- Role 5 (Procurement/Legal): [e.g., VP Procurement — contract/vendor negotiation]
- Additional roles (if applicable): [e.g., Compliance Officer, Department Head]

Content library:
- Total published pieces: [X across all formats]
- Core content formats: [blog, long-form guides, white papers, case studies, webinars, product demos, comparison/vs. pages, pricing page, ROI calculator, assessment tools]
- Monthly content production: [X pieces/month]
- Gated assets: [X — list top 5 gated pieces by title]
- Key content clusters (topics): [list 4-6 primary topic clusters aligned to buyer pain]

Tech stack:
- CRM: [Salesforce / HubSpot — including relevant objects: Accounts, Contacts, Opportunities, Activities]
- Marketing Automation Platform: [Marketo / HubSpot / Pardot / Eloqua]
- Intent data: [6sense / Demandbase / Bombora / G2 Buyer Intent / TechTarget Priority Engine]
- Web analytics: [GA4 / Adobe Analytics / Segment / Amplitude]
- Account intelligence / enrichment: [Clearbit / Apollo / ZoomInfo / LinkedIn Sales Navigator]
- Content experience platform: [Pathfactory / Uberflip / Folloze — if applicable]
- CDP: [Segment / Rudderstack / Tealium — if applicable]
- Data warehouse: [Snowflake / BigQuery / Databricks — if applicable]
- BI / reporting: [Tableau / Looker / Power BI / Salesforce Reports]

Current measurement gaps: [describe what you track today and what's missing]
Sales activation process: [describe how sales currently gets content engagement alerts — or that they don't]
Content engagement goal: [e.g., "get every Tier 1 account to 3+ buying committee touches before SDR reaches out," "use content signals to cut our 90-day sales cycle by 20%"]

---

SECTION 1 — ACCOUNT CONTENT ENGAGEMENT SCORING ARCHITECTURE

1.1 Account Engagement Score (AES) Framework

Build a real-time Account Engagement Score from 0–100 that aggregates all content interactions by known contacts + anonymous IP-matched sessions at each account.

SCORING INPUTS — CONTENT FORMAT WEIGHTS:
Assign base point values by content type (higher value = higher buyer intent signal):

TIER A — HIGHEST INTENT (Base: 15–20 pts per interaction):
- Pricing page visit: 20 pts (explicit commercial intent)
- ROI calculator completion: 20 pts (quantified value exploration = late-stage intent)
- Competitor comparison page visit: 18 pts (active evaluation signal)
- Demo request page visit (without converting): 15 pts (intent-adjacent behavior)
- Case study read (>60% scroll depth): 18 pts (social proof validation = late funnel)

TIER B — HIGH INTENT (Base: 10–14 pts per interaction):
- Webinar attendance (live): 14 pts (active time investment = deep engagement)
- White paper or long-form guide download: 12 pts (gated = willingness to identify)
- Webinar registration (no-show): 8 pts (interest without full commitment)
- Assessment/diagnostic tool completion: 14 pts (self-qualification signal)
- Product demo video watched (>70% completion): 12 pts

TIER C — MODERATE INTENT (Base: 5–9 pts per interaction):
- Blog post read (>60% scroll depth): 7 pts
- Blog post read (<60% scroll): 4 pts
- Email newsletter open + click-through to content: 6 pts
- Webinar recording viewed (>50% completion): 9 pts
- LinkedIn content engagement (comment or share): 6 pts

TIER D — AWARENESS SIGNAL (Base: 1–4 pts):
- Blog post view (<30 seconds, likely bounced): 1 pt
- Email open only (no click): 2 pts
- Social media impression (click without content engagement): 1 pt
- Branded search impression (SEO, no click): 1 pt

RECENCY MULTIPLIERS (apply to all base scores):
- Last 7 days: 1.5× multiplier
- 8–14 days: 1.25× multiplier
- 15–30 days: 1.0× multiplier (full credit)
- 31–60 days: 0.7× multiplier (decay begins)
- 61–90 days: 0.4× multiplier (significant decay)
- >90 days: 0.1× multiplier (near-zero weight — behavioral recency matters)

BUYING COMMITTEE MULTIPLIERS (apply when known contact role is identified):
- Economic Buyer (CFO, CRO, COO, CEO): 2.0× role multiplier (rare, high-signal)
- Champion / Day-to-Day Owner: 1.5× multiplier
- Technical Evaluator: 1.3× multiplier
- End User / Practitioner: 1.0× multiplier (baseline)
- Procurement / Legal: 1.2× multiplier (signals advanced evaluation stage)
- Anonymous IP-matched visitor: 0.7× multiplier (unconfirmed identity)

BREADTH BONUS (aggregate account score modifier):
- 2 unique contacts engaged in last 30 days: +10% to account total score
- 3–4 unique contacts engaged: +20%
- 5+ unique contacts engaged (full buying group signal): +35%
- Same contact has 3+ distinct interactions in 7 days (engagement concentration signal): +15% per recurrence

ACCOUNT ENGAGEMENT SCORE TIERS:
- SURGING (85–100): Full buying committee engaged, high-intent content consumed, within 14-day recency window → IMMEDIATE SALES ACTIVATION
- HOT (65–84): Multiple personas engaged, mix of mid-to-late-stage content → SDR outreach + AE awareness, personalize next content touchpoint
- WARMING (40–64): 2–3 personas showing consistent engagement → Accelerate nurture, route high-intent content directly to un-engaged personas
- AWARE (20–39): Single contact or minimal engagement → Continue nurture, monitor for velocity acceleration
- DARK (0–19): No recent engagement or no known contacts → Reactivation play or cold outreach with high-value asset

1.2 Anonymous Account Signal Integration

For IP-matched anonymous sessions not tied to known contacts:

ANONYMOUS SIGNAL INCORPORATION:
- Use reverse IP lookup (Clearbit Reveal, 6sense, Demandbase, or similar) to map anonymous web sessions to company domains
- Apply 0.7× multiplier to all anonymous sessions (lower confidence than known contact)
- When anonymous signal + intent platform signal (Bombora/6sense surge) align on same account: upgrade anonymous session weight to 1.0×
- Threshold for anonymous-only account flagging: ≥ 3 Tier A content interactions from same account domain within 7 days → flag as INVESTIGATE: send to SDR for contact discovery via LinkedIn Sales Navigator + Apollo

IDENTITY RESOLUTION WORKFLOW:
1. Anonymous IP session → Reverse IP → Match to account domain in CRM
2. If account is on TAL: log activity to account record with "Anonymous Web Engagement" tag
3. If account is NOT on TAL but matches ICP firmographic criteria: auto-add to TAL review queue
4. SDR reviews TAL additions weekly → approves account upgrade or routes to content marketing team to investigate content consumption patterns

---

SECTION 2 — BUYING GROUP CONTENT COVERAGE FRAMEWORK

2.1 Persona Content Coverage Map

For each target account, build a coverage matrix showing which buying committee personas have and haven't engaged with content in the last 90 days.

COVERAGE MAP STRUCTURE (per account):
| Buying Role | Known Contact Name | Last Content Engagement | Content Type | Content Title | Recency | Coverage Status |
|---|---|---|---|---|---|---|
| CFO / Economic Buyer | Jane Smith | 12 days ago | Case Study | "How Acme Cut Costs 35%" | Recent | COVERED |
| VP Operations (Champion) | Michael Torres | 3 days ago | Webinar + Pricing Page | "2025 Supply Chain Benchmark" | High-Recency | HOT |
| IT Director | Unknown | No engagement | — | — | — | DARK |
| Operations Manager | Sarah Chen | 45 days ago | Blog post | "3 Workflow Automation Tips" | Decaying | AWARE |
| Procurement VP | Unknown | No engagement | — | — | DARK |

COVERAGE STATUS DEFINITIONS:
- COVERED (engaged with Tier A or B content in last 30 days): Sales can reference this persona's content engagement as a warm entry point
- AWARE (engaged with Tier C or D content, or Tier A/B content >30 days ago): Nurture with targeted content outreach
- DARK (no known engagement in 90+ days OR unknown contact identity): Requires contact discovery + cold outreach with high-value asset hook
- UNKNOWN (no CRM contact exists for this role at this account): SDR contact discovery priority

PERSONA GAP RECOMMENDATIONS ENGINE:
When a buying committee role is DARK or UNKNOWN at a target account, automatically recommend:

For ECONOMIC BUYER (CFO/CRO) — dark:
→ Content recommendation: [CFO-specific case study with financial metrics] or [ROI calculator] or [Board-ready ROI summary]
→ Outreach channel: Direct AE email referencing champion's engagement + attach financial case study
→ SDR action: LinkedIn connection request from AE → follow with executive brief

For TECHNICAL EVALUATOR — dark:
→ Content recommendation: [Security white paper] or [Integration architecture guide] or [API documentation overview]
→ Outreach channel: IT Director-specific email sequence from SDR with technical deep-dive asset
→ Timing: After champion is engaged (never cold-reach technical evaluator before champion is warm)

For PROCUREMENT — dark:
→ Note: Procurement typically engages late. If champion + economic buyer are already hot, proactively send vendor qualification package + security questionnaire template before procurement initiates their own process.

2.2 Buying Group Content Coverage Score (BGCS)

A single metric per account representing buying committee coverage completeness:

BGCS Formula:
(# of buying committee roles with Tier A/B content engagement in last 60 days) ÷ (Total buying committee roles defined for this account) × 100 = BGCS %

BGCS Tiers:
- 80–100%: FULL COVERAGE → Accelerate to pipeline if not already → AE executive outreach
- 60–79%: STRONG COVERAGE → Identify 1–2 remaining dark personas → deploy targeted content + SDR outreach to fill gaps
- 40–59%: PARTIAL COVERAGE → Needs systematic content gap filling → run 30-day persona-targeted nurture sprint
- 20–39%: THIN COVERAGE → Single-threaded risk → prioritize multi-threading content strategy immediately
- 0–19%: MINIMAL/NO COVERAGE → Account warming campaign required before any sales outreach

TARGET: For all Tier 1 accounts, reach BGCS ≥ 60% before first SDR cold outreach.

---

SECTION 3 — CONTENT ENGAGEMENT VELOCITY & TIMING INTELLIGENCE

3.1 Account Engagement Velocity Algorithm

Measure engagement acceleration to predict buying urgency and optimal sales timing.

VELOCITY CALCULATION:
- Week 1 engagement score: [sum of all interaction points, Week 1]
- Week 2 engagement score: [Week 2 sum]
- Velocity = (Week 2 − Week 1) ÷ Week 1 × 100 = % WoW change

VELOCITY SIGNAL TIERS:
- SURGING (≥50% WoW increase for 2+ consecutive weeks): Account is actively entering buying cycle — immediate sales activation
- ACCELERATING (20–49% WoW increase): Buying cycle beginning — increase content touchpoint frequency + flag for SDR follow-up
- STEADY (±20% WoW): Normal engagement pattern — continue standard nurture
- DECELERATING (-20% to -49% WoW): Engagement cooling — may have bought a competitor, funding frozen, or changed priorities → deploy reactivation content or pause outreach
- DARK (>80% WoW decline): Account has gone silent → check for competitive displacement signals

VELOCITY-BASED TIMING RECOMMENDATIONS:
- SURGING account: Sales contact within 24–48 hours of velocity trigger detection
- ACCELERATING account: SDR outreach within 5 business days with warm context ("I noticed your team has been exploring [topic cluster] — wanted to share a resource that goes deeper")
- DECELERATING account: Pause SDR sequences → route to marketing nurture with fresh perspective content → re-evaluate in 30 days
- DARK account: Trigger re-engagement sequence with high-value, different-angle content asset — do not use same assets the account already ignored

3.2 Content Engagement Sequence Analysis

Map the content consumption sequence that most often precedes deal creation at existing customers.

HISTORICAL PATTERN ANALYSIS FRAMEWORK:
1. Pull all closed-won accounts from past 24 months
2. For each won account, reconstruct the content engagement timeline: first touch → content consumed before MQL → content consumed during opportunity → content consumed in final 30 days before close
3. Identify the top 3 "conversion content sequences" — specific ordered combinations of content types/topics that appear most frequently in won deals
4. Use these sequences as the blueprint for target account nurture orchestration

EXAMPLE OUTPUT FORMAT (to be populated with your actual data):
- Sequence A (appears in 42% of enterprise deals): Thought Leadership Blog → ROI Calculator → Competitor Comparison Page → Case Study → Pricing Page → Demo Request
- Sequence B (appears in 31% of mid-market deals): Webinar Attendance → White Paper Download → Product Demo Video → Case Study → Pricing Page
- Sequence C (appears in 18% of product-led deals): Free Tool Usage → Feature Blog Post → Upgrade Comparison Page → Pricing Page

ORCHESTRATION ACTION: For each target account, identify where they are in a known conversion sequence and ensure the NEXT logical content asset is proactively delivered to the right persona at the right time.

---

SECTION 4 — CONTENT-TRIGGERED SALES PLAY LIBRARY

4.1 Trigger Matrix: Content Signal → Sales Action

Define the complete decision tree that converts content engagement signals into sales activities, fully automatable via CRM workflow rules.

PLAY 1 — ECONOMIC BUYER HIGH-INTENT (EXECUTE WITHIN 24 HOURS):
TRIGGER: CFO/CRO/CEO-level contact at Tier 1 account views pricing page OR downloads financial case study OR completes ROI calculator
ACTION: 
- Immediate AE notification via Slack + CRM alert
- AE sends personalized email within 2 business hours referencing the specific content ("Our VP of Finance at [similar company] had the same question about pricing model flexibility — I thought this [specific resource] would address it directly")
- Executive outreach escalation if AE does not respond within 4 hours
- Log "Economic Buyer High-Intent Signal" activity in CRM opportunity record

PLAY 2 — MULTI-THREADED ACCOUNT SURGE (EXECUTE WITHIN 48 HOURS):
TRIGGER: 3+ distinct contacts at same Tier 1 account engage with content in same topic cluster within 7-day window
ACTION:
- AE receives consolidated "buying committee warming" alert with names, roles, content consumed, and recency
- AE sends multi-stakeholder email to champion: "I noticed your [role] and [role] colleagues have also been exploring [topic] — this tells me there might be broader conversation happening internally that I can help accelerate"
- SDR adds non-engaged buying committee members to targeted outreach sequence
- Marketing: auto-enroll account in account-based ad campaign for un-engaged personas

PLAY 3 — COMPETITOR COMPARISON PAGE VISIT (EXECUTE WITHIN 12 HOURS):
TRIGGER: Any Tier 1 or 2 account contact views competitor comparison page OR googles "[competitor] vs. [your product]" (tracked via intent platform)
ACTION:
- Immediate SDR notification: "COMPETITIVE EVALUATION ALERT — [Contact] at [Account] just visited our [Competitor A] comparison page"
- SDR calls within 2 business hours with: "I saw you were researching the [Competitor A] comparison — happy to share some candid thoughts on where we differ and where they might be a better fit"
- Enroll in competitive displacement nurture sequence (battlecard-based emails over 7 days)
- AE receives competitive intelligence alert to prepare deal defense if already in active opportunity

PLAY 4 — TIER 2 ACCOUNT THRESHOLD CROSS (EXECUTE WITHIN 5 DAYS):
TRIGGER: Tier 2 account Account Engagement Score crosses 65+
ACTION:
- Auto-upgrade account to Tier 1 in CRM (with human review flag)
- Assign dedicated AE from unassigned accounts pool
- AE reviews content engagement history and sends first outreach referencing 2–3 specific pieces consumed
- Marketing: shift account from programmatic ABM to 1:1 ABM content personalization

PLAY 5 — DARK TIER 1 REACTIVATION (EXECUTE MONTHLY):
TRIGGER: Tier 1 account with no content engagement for 60+ days AND has been in active pipeline 90+ days without stage progression
ACTION:
- AE + SDR reactivation play: send fresh, non-repetitive content asset (new format or new angle not previously consumed by this account)
- Options: "State of [Industry] Report," executive brief on a new trend, personalized Loom video from AE, invite to exclusive roundtable
- If no engagement after reactivation content: reduce to Tier 2 and evaluate ICP fit re-qualification

---

SECTION 5 — CONTENT INVESTMENT PRIORITIZATION BY ACCOUNT COVERAGE IMPACT

5.1 Content Gap Priority Matrix

Identify the content assets that, if created or improved, would cover the most buying committee gaps across your target account list.

GAP ANALYSIS METHODOLOGY:
1. Aggregate all DARK buying committee personas across all Tier 1 accounts
2. Map each DARK persona gap to: (a) their most likely content need based on role + ICP pain, and (b) whether you have relevant content today
3. Score each content gap by: (# of Tier 1 accounts missing this persona coverage) × (Account ACV weight) = Revenue Coverage Gap Score
4. Rank content gaps by Revenue Coverage Gap Score — highest score = highest production priority

OUTPUT FORMAT — CONTENT PRODUCTION PRIORITY QUEUE:
| Content Need | Target Persona | Accounts Missing This Coverage | Total ACV at Risk | Priority Score | Production Recommendation |
|---|---|---|---|---|---|
| CFO-focused ROI case study (manufacturing vertical) | CFO / Economic Buyer | 47 Tier 1 accounts | $14.1M | 94 | Build immediately — highest revenue impact |
| IT security architecture white paper | IT Director / CISO | 38 Tier 1 accounts | $11.4M | 81 | Q1 priority |
| Procurement vendor evaluation guide | VP Procurement | 52 Tier 1 accounts | $7.8M | 68 | Q2 production |
| End-user workflow efficiency guide | Operations Manager | 29 Tier 1 accounts | $4.4M | 41 | Repurpose from existing blog series |

5.2 Content Personalization Recommendation Engine

For each WARMING or SURGING account, output a personalized next-content recommendation based on:
- Content already consumed (avoid repetition)
- Current buying stage (inferred from engagement pattern)
- Dark persona gaps (recommend content most likely to engage un-touched roles)
- Competitive context (competitor visit history → route to differentiation content)
- Vertical specificity (use industry-specific content first when available)

RECOMMENDATION FORMAT PER ACCOUNT:
Account: [Meridian Logistics — Tier 1, AES = 74, BGCS = 60%]
Current stage: WARMING → HOT
Champion: VP Supply Chain (HOT — engaged with 2 webinars + pricing page last 14 days)
Gap persona: CFO (DARK — no engagement)
Recommendation:
1. AE send to CFO: "Supply Chain ROI Report: How Meridian's Peers Are Cutting Costs 23% with Automation" (personalize with their vertical and size)
2. Enroll IT Director (AWARE) in: "Enterprise Security Architecture Guide" + "SOC 2 Compliance for Supply Chain SaaS" email sequence
3. Accelerate champion: "2025 Supply Chain Benchmark Report" download offer + invite to exclusive customer advisory group

---

SECTION 6 — REPORTING CADENCE & DASHBOARD SPECIFICATION

6.1 Weekly Sales Activation Report (for AE/SDR team)

A Monday morning report sent to each AE and their SDR covering:
1. TOP 10 ACCOUNTS BY AES CHANGE (highest WoW velocity gain)
2. NEW ECONOMIC BUYER ENGAGEMENTS this week (any CFO/CRO/CEO at TAL accounts)
3. COMPETITIVE COMPARISON PAGE ALERTS (accounts that visited vs. competitor pages)
4. ACCOUNTS CROSSING THRESHOLD (Tier 2 accounts that crossed AES 65 → upgrade to Tier 1 review)
5. DARK TIER 1 ALERTS (accounts at risk of disengagement)
6. NEXT BEST ACTION per account (specific content + outreach recommendation)

FORMAT: Auto-generated Salesforce/HubSpot report + Slack digest channel #abm-content-alerts

6.2 Monthly ABM Content Performance Review (for Marketing leadership)

Review 4 key dimensions:
1. BUYING GROUP COVERAGE IMPROVEMENT: Did average BGCS increase MoM across Tier 1 accounts? (Target: +5% per month)
2. CONTENT-TO-PIPELINE CONTRIBUTION: How many Tier 1 accounts moved from WARMING to HOT → SURGING → active pipeline this month?
3. CONTENT GAP PROGRESS: Were the top 3 priority content gaps addressed? What is the impact on BGCS?
4. CONTENT TRIGGER PLAY PERFORMANCE: Of all triggered sales plays, what % led to meetings booked? What is the meeting-to-opportunity conversion rate for content-triggered plays vs. cold outreach?

6.3 Quarterly Executive Report

Board-ready metrics for CMO and VP Marketing:
- CONTENT-INFLUENCED PIPELINE: Total open pipeline value in accounts with AES ≥ 40 (content-touched accounts)
- MULTI-THREADED ACCOUNT RATE: % of open opportunities with 3+ buying committee contacts engaged with content (benchmark: target ≥ 60%)
- CONTENT-SHORTENED SALES CYCLE: Average days from first content engagement to opportunity creation for accounts with BGCS ≥ 60% vs. <40%
- CONTENT-TRIGGERED PLAY ROI: Total pipeline created from content-triggered sales plays ÷ content production investment

---

## Example Input/Output

**Input:**
Company: Nexflow AI — B2B SaaS for warehouse and distribution operations  
ARR: $12M  
Average deal size: $185,000 ACV  
Sales cycle: 78 days average  
ICP buying committee: VP Operations (Champion), CTO (Technical), CFO (Economic Buyer), Director of Warehousing (End User), VP Procurement (Contract)  
Target accounts: 180 Tier 1 accounts  
Tech stack: Salesforce + HubSpot Marketing + 6sense + GA4 + Apollo  
Content assets: 127 published pieces (48 blog posts, 12 white papers, 8 case studies, 15 webinars, 6 ROI tools, 14 comparison pages, 24 product docs)  
Current gap: "SDRs are reaching out cold to CFOs even when we have no content engagement at that account — we're getting <3% meeting rates. We need to know which accounts are actually warm before we make the call."

**Output (excerpt):**

**NEXFLOW AI — ACCOUNT ENGAGEMENT INTELLIGENCE SUMMARY**
*Report Date: [Current Date] | Reporting Period: Last 30 Days*

**TOP 10 SURGING ACCOUNTS (AES ≥ 85, Past 14 Days):**
| Account | AES | WoW Velocity | BGCS | Hot Persona | Missing Persona | Recommended Action |
|---|---|---|---|---|---|---|
| Hartwell Distribution Group | 91 | +68% | 80% | VP Ops (HOT) + CTO (WARM) | CFO DARK | AE: Send CFO ROI case study TODAY. Book discovery within 48 hrs. |
| Cascade Fulfillment Corp | 88 | +54% | 60% | VP Ops (HOT) | CTO + CFO DARK | SDR: CTO technical outreach + enroll CFO in finance ROI sequence |
| Ridgeline Logistics | 85 | +61% | 80% | VP Ops + Director (HOT) | CFO AWARE only | AE: 3-way meeting request — CFO now receptive given champion heat |

**ACCOUNT DEEP DIVE: Hartwell Distribution Group**
- VP Operations (James Whitmore): Visited pricing page (Nov 12), completed ROI calculator (Nov 14), attended live webinar (Nov 15), downloaded "Warehouse Ops Efficiency Guide" (Nov 16). AES contribution from James: 82 pts → SURGING
- CTO (Sarah Park): Viewed integration architecture page (Nov 13), read security white paper (Nov 14). AES contribution: 31 pts → WARM
- CFO (Robert Chen): ZERO engagement. DARK persona. Revenue risk: blocking factor for deal progression.
- Director of Warehousing: 2 blog reads (Nov 8–10). AES: 11 pts. AWARE.
- VP Procurement: DARK. No contacts identified.

**RECOMMENDED ACTIONS — HARTWELL:**
1. AE Connor Walsh: TODAY — email Robert Chen (CFO) with "How 3 Distribution Companies Similar to Hartwell Reduced Inventory Costs 27% with AI-Driven Operations" case study. Subject line: "James [VP Ops] suggested I reach out about your Q1 operational investment." 
2. AE: Book discovery call with VP Ops James Whitmore within 48 hours — he is fully warmed. Reference pricing page visit + ROI calculator results.
3. SDR: Research VP Procurement identity on LinkedIn — if found, enroll in vendor qualification package sequence.
4. Week 3: If CFO doesn't engage with case study, escalate to AE sending a custom 1-page ROI snapshot calculated from ROI calculator inputs.

**BUYING GROUP COVERAGE IMPROVEMENT PLAYBOOK — NEXT 30 DAYS:**
Of 180 Tier 1 accounts:
- 41 accounts (23%) have FULL COVERAGE (BGCS ≥ 80%) → Focus: velocity acceleration + convert to active pipeline
- 67 accounts (37%) have PARTIAL COVERAGE (40–79%) → Focus: fill persona gaps with targeted content + SDR outreach
- 52 accounts (29%) have THIN COVERAGE (20–39%) → Focus: identify champion + begin warm multi-touch sequence
- 20 accounts (11%) are DARK (BGCS < 20%) → Evaluate ICP fit before investing in content warming

**PRIORITY CONTENT GAPS (by Revenue Coverage Impact):**
1. CFO-focused ROI case study (logistics/distribution vertical): 89 Tier 1 accounts missing CFO coverage = $16.5M ACV exposure → BUILD NOW
2. Technical security & compliance architecture guide: 54 accounts missing CTO coverage = $10M ACV → Q4 production
3. Procurement vendor evaluation template + NDA/MSA starter kit: 71 accounts missing Procurement coverage = $13.1M ACV → Q1 production

---

## Success Metrics

**Buying Group Coverage:**
- BGCS average across Tier 1 accounts: target ≥ 60% within 90 days
- % of Tier 1 accounts with 3+ buying committee personas engaged: target ≥ 50%
- Month-over-month BGCS improvement: target +5–8% per month

**Sales Activation Effectiveness:**
- Meeting rate: content-triggered outreach vs. cold outreach (target: ≥ 2.5× improvement)
- Days from first content engagement to opportunity creation (target: ≤ 25 days for SURGING accounts)
- % of new opportunities with AES ≥ 40 at time of opportunity creation (target: ≥ 70%)

**Pipeline Quality:**
- Win rate: accounts with BGCS ≥ 60% vs. <40% at opportunity creation (target: ≥ 20% win rate delta)
- Sales cycle duration: multi-threaded content-engaged accounts vs. single-threaded (target: ≥ 15% shorter)
- Average deal size: accounts with 5+ buying committee content touchpoints vs. fewer (target: ≥ 10% larger ACV)

**Content Investment Efficiency:**
- Cost per buying committee touchpoint: total content production cost ÷ total BGCS improvements
- Content-triggered pipeline: quarterly pipeline value attributable to content-triggered sales plays
- ROI on account-level content personalization: lift in conversion rate for accounts receiving personalized content outreach vs. generic nurture

---

## Related Prompts

- [Content Marketing Performance Analytics & Content Program ROI](./AI-Powered-B2B-Content-Marketing-Performance-Analytics-&-Content-Program-ROI-Intelligence-Engine.md)
- [B2B Content Asset Attribution & Pipeline Influence](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/B2B-Content-Asset-Attribution-&-Pipeline-Influence-Intelligence-Engine.md)
- [ABM Buying Committee Engagement Scoring & Multi-Stakeholder Deal Velocity](../../05_Analytics-&-Performance/Account-Based-Marketing-Analytics/AI-Powered-ABM-Buying-Committee-Engagement-Scoring-&-Multi-Stakeholder-Deal-Velocity-Intelligence-Engine.md)
- [ABM Intent Data Activation & Buying Signal Prioritization](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)

---

## Integration Tips

**Salesforce:**
- Create custom Account field "Account Engagement Score (AES)" — update via weekly automated report from MAP/BI tool
- Create custom Account field "Buying Group Coverage Score (BGCS)" — auto-calculated from contact-level content activity tags
- Set up Alert Rules: when AES increases by ≥ 30 points in 7 days → trigger "Content Surge Alert" task assigned to account owner
- Build a "Content Engagement Timeline" related list on Account object: log all content interactions (known + anonymous IP-matched) as Activity records with custom type "Content Engagement"

**HubSpot:**
- Use "Company Engagement Score" as base → layer in custom properties for AES and BGCS
- Create Smart Lists: "Tier 1 Accounts — AES 65+" and "Tier 1 Accounts — Economic Buyer Dark" for targeted workflow enrollment
- Workflow trigger: Contact at TAL account views Pricing page → internal notification to account owner + enroll in "Pricing Interest" sales alert task
- Use "Revenue Events" to connect closed-won accounts back to content engagement timeline for historical pattern analysis

**6sense / Demandbase:**
- Sync 6sense Intent Score + Buying Stage signal into Account Engagement Score calculation as a third signal layer (alongside first-party content engagement + contact-level activity)
- Use 6sense "In-Market" signals to validate SURGING accounts from first-party data — double-signal = highest confidence
- Set up 6sense → Salesforce sync to push "Research Stage Change" events as CRM activity records for sales visibility

**Slack:**
- Create #abm-content-alerts channel: auto-post weekly sales activation digest (SURGING accounts, economic buyer engagements, competitive page visits)
- Use Salesforce + Zapier to push real-time alert: "🔥 [Account] just viewed the [Competitor] comparison page — [Contact Name], [Title]" → immediate SDR notification

**Pathfactory / Uberflip (if applicable):**
- Track "Content Journey Length" (total assets consumed per account session) as a standalone engagement depth metric
- Export account-level content journey reports to feed BGCS calculations with structured data on which content clusters each persona has consumed

---

## Troubleshooting

**Problem: Most content engagement is anonymous — we can't link it to specific contacts or accounts.**
Fix: Implement reverse IP lookup (Clearbit Reveal, 6sense, or Dealfront) to map anonymous web sessions to company domains. Even without contact identity, account-level content engagement is actionable for ABM targeting and for alerting SDRs to investigate and discover contacts at actively engaging accounts. Prioritize converting anonymous accounts to known contacts by deploying mid-page CTA offers (gated asset, newsletter signup, demo offer) on your highest-traffic pages consumed by anonymous TAL accounts.

**Problem: Sales ignores content engagement alerts — they don't trust the data or don't know how to use it.**
Fix: Run a retrospective analysis on your last 20 closed-won deals: show sales exactly which content each account consumed before the deal was created and how it correlated with deal progression. Make the data viscerally real with deal examples they know. Then simplify: give each rep a single "call this account NOW" alert per week based on the single highest-velocity account in their territory. One high-confidence, high-relevance alert per week is more actionable than a dashboard of 50 signals.

**Problem: Buying committee contact coverage is too thin — we can't match enough contacts to roles.**
Fix: Run a systematic contact enrichment sprint before launching the BGCS framework. Use LinkedIn Sales Navigator + Apollo + ZoomInfo to identify 3–5 contacts per buying committee role at each Tier 1 account. Create a "Contact Discovery" SDR play where reps spend 30 minutes per account building out the buying committee contact map before beginning any outreach. Prioritize economic buyer and technical evaluator contact discovery since these roles are typically the most impactful and hardest to reach cold.

---

## Version History
- v1.0: Initial creation (auto-generated)
