# AI-Powered B2B SaaS First-Party Behavioral Intent Analytics & Website Visitor Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** intent-data, first-party-data, website-intelligence, behavioral-analytics, product-led-growth, account-intelligence, pipeline-attribution, revenue-intelligence

## Overview
This prompt builds a fully automated first-party behavioral intent analytics system that converts your website visitor data, product usage signals, email engagement patterns, and in-app behavioral telemetry into a unified account-level intent score — then activates that score into prioritized pipeline. Use it when you want to maximize the intent signals you already own before buying more third-party data, or when you need to operationalize website visitor intelligence tools like RB2B, Leadfeeder/Dealfront, Warmly, or Koala into revenue-attributable pipeline programs.

## Quick Copy-Paste Version

You are a senior B2B revenue intelligence analyst specializing in first-party behavioral intent data. Your task is to build a complete first-party intent analytics system for [Company Name] that ingests owned behavioral signals, scores accounts by purchase readiness, and activates those scores into pipeline.

COMPANY CONTEXT:
- Product: [e.g., AI-powered procurement automation platform for mid-market manufacturing companies]
- ICP: [e.g., VP of Procurement and CFOs at 250-2,500 employee manufacturing and distribution companies]
- Average ACV: [e.g., $58,000]
- Monthly website visitors: [e.g., 12,000 unique visitors, ~1,800 identified accounts]
- Freemium/trial: [e.g., Yes — 14-day trial with 340 active trial accounts]
- CRM: [e.g., HubSpot with Clearbit enrichment and RB2B for visitor identification]

FIRST-PARTY DATA SOURCES AVAILABLE:
- Website behavioral data: page visits, session depth, content downloads, pricing page views, demo request form completions
- Product/trial usage data: feature activation, login frequency, API calls, integrations connected
- Email engagement: open rates, click-through by content type, reply rates on nurture sequences
- CRM behavioral history: meeting cadence, email thread depth, contact response velocity

DELIVERABLES:

1. FIRST-PARTY SIGNAL TAXONOMY
Define and rank every behavioral signal you have by purchase intent predictive value. Categorize signals into: (a) High-intent indicators (pricing page 3+ visits, ROI calculator completion, security/compliance doc downloads, demo request form abandonment), (b) Medium-intent indicators (blog category depth, case study downloads, product page revisits), (c) Low-intent indicators (home page visit, single blog post). Assign a point weight to each signal and explain the weight rationale.

2. ACCOUNT-LEVEL BEHAVIORAL INTENT SCORE
Design a composite scoring formula that aggregates individual contact signals up to the account level, accounts for recency decay (signal freshness), and produces a 0-100 intent score per account. Include: recency weighting formula (signals within 7 days = 1.0x weight, 8-14 days = 0.7x, 15-30 days = 0.4x), volume normalization (prevent single power-user from inflating team-level score), and ICP fit multiplier (score × ICP fit tier: Tier 1 = 1.3x, Tier 2 = 1.0x, Tier 3 = 0.6x).

3. PRODUCT USAGE SIGNAL ACTIVATION
For trial/freemium accounts, build a behavioral engagement ladder: define the specific feature activations, usage frequency thresholds, and integration connections that historically predict trial-to-paid conversion. Map each usage milestone to a specific marketing or sales activation (automated in-app message, CSM outreach, upgrade campaign, or sales-assist trigger).

4. WEBSITE VISITOR INTELLIGENCE WORKFLOW
Design the end-to-end workflow for converting anonymous website visitors into identified accounts: (a) IP-to-company matching tool configuration (e.g., RB2B, Warmly, Leadfeeder), (b) ICP filtering rules (exclude ISPs, universities, competitors, existing customers), (c) Alert routing logic (which accounts go to SDR vs. marketing nurture vs. ABM campaign), (d) Personalization triggers (which landing page experiences or retargeting ads activate based on pages visited).

5. FIRST-PARTY INTENT COHORT ANALYSIS
Segment accounts into four intent cohorts based on behavioral pattern: (a) Surging — score increased 20+ points in last 7 days, (b) Steady — consistent engagement over 30+ days at moderate intensity, (c) Stalling — high score 14+ days ago with no recent activity, (d) Dark — was active, now silent for 21+ days. Define the specific marketing activation for each cohort and the success metric for each program.

6. REVENUE ATTRIBUTION MODEL
Prove the ROI of your first-party intent program: calculate (a) first-party intent-sourced pipeline (accounts where behavioral score crossed threshold within 30 days before MQL), (b) intent-assisted pipeline (behavioral score in 60-day window before deal created), (c) conversion rate lift for intent-activated accounts vs. equivalent non-activated ICP accounts, (d) cost-per-intent-activation assuming zero incremental data cost.

Output each section as an immediately deployable framework with specific thresholds, scoring formulas, and activation rules — not conceptual guidance.

## Advanced Customizable Version

SYSTEM ROLE:
You are a principal revenue intelligence architect with 12 years of experience building first-party intent data programs for B2B SaaS companies from Series B through pre-IPO stage. You have led intent data strategy at companies using Clearbit, RB2B, Warmly, Koala, Pocus, and June.so. You specialize in translating raw behavioral telemetry into revenue-attributable pipeline programs. You do not recommend third-party intent data unless first-party signals have been fully operationalized.

COMPANY PROFILE:
Company: [Company Name]
Stage: [e.g., Series C, $28M ARR, growing 45% YoY]
Product category: [e.g., Revenue Operations automation platform]
ICP definition: [e.g., RevOps leaders and VP Sales at B2B SaaS companies 50-500 employees with Salesforce as CRM]
ACV range: [e.g., $24,000-$96,000, median $44,000]
Sales motion: [e.g., Inside sales with 45-day average sales cycle, demo-first]
PLG element: [e.g., Freemium tier with 14-day pro trial]
Monthly unique visitors: [e.g., 18,500 unique visitors, ~2,400 identified via RB2B/Clearbit]
Trial accounts active: [e.g., 520 accounts in trial or freemium]
Current CRM + MAP: [e.g., Salesforce + Marketo + Segment for behavioral data]
Visitor identification stack: [e.g., RB2B (individual identification), Clearbit Reveal (company identification), FullStory (session replay)]
Product analytics stack: [e.g., Amplitude for product analytics, Segment for event tracking, Intercom for in-app messaging]

OBJECTIVE:
Design a comprehensive first-party behavioral intent analytics architecture that:
1. Ingests all owned behavioral signals into a unified account intent score
2. Converts anonymous traffic into identified pipeline opportunities
3. Activates product usage signals into upsell and conversion programs
4. Proves revenue attribution from first-party behavioral programs
5. Operates autonomously via CRM workflows and MAP triggers with minimal manual intervention

DELIVERABLE 1 — COMPREHENSIVE SIGNAL TAXONOMY & WEIGHTING MODEL

Map every owned behavioral signal to a point value using the Intent Signal Scoring Matrix below:

HIGH-INTENT SIGNALS (20-50 points each):
- Pricing page viewed: 35 points (recency-decayed)
- ROI/savings calculator completed: 50 points (strongest single signal)
- Security trust center or compliance documentation downloaded: 30 points
- Demo request form started but abandoned: 40 points
- Customer case study downloaded (2+ in one session): 35 points
- Integration/API documentation viewed (technical evaluation signal): 25 points
- Competitive comparison page viewed: 40 points
- "Book a demo" CTA clicked (even if form not submitted): 30 points

MEDIUM-INTENT SIGNALS (8-18 points each):
- Blog post category depth (3+ posts in same category within 7 days): 15 points
- Feature page revisit (same feature page visited 3+ times): 18 points
- Solution/use-case page viewed: 12 points
- Email nurture click-through to a feature or case study page: 10 points
- Webinar registration: 12 points (attended = 15, no-show = 5)
- Product changelog page viewed: 8 points (signals product research stage)

LOW-INTENT SIGNALS (1-5 points each):
- Home page visit: 2 points
- Single blog post read: 3 points
- Newsletter open without click: 1 point
- Conference/event page viewed: 4 points

RECENCY DECAY FORMULA:
Adjusted Score = Raw Score × Recency Multiplier
- Signal within 0-7 days: 1.0× multiplier
- Signal within 8-14 days: 0.75× multiplier
- Signal within 15-21 days: 0.50× multiplier
- Signal within 22-30 days: 0.25× multiplier
- Signal older than 30 days: 0.10× multiplier (retained for historical pattern)

ACCOUNT SCORE = Sum of all contact-level adjusted scores within the account
FINAL INTENT SCORE = Account Score × ICP Fit Multiplier (Tier 1 = 1.3×, Tier 2 = 1.0×, Tier 3 = 0.6×)

DELIVERABLE 2 — PRODUCT USAGE BEHAVIORAL INTENT LADDER

Define the specific product usage milestones that predict paid conversion for your PLG motion:

ACTIVATION LADDER (Trial/Freemium Accounts):
Level 1 — Activated (Day 1-3): Account has completed onboarding step 1, connected at least one integration, and has 3+ active users logging in within 72 hours of signup
Level 2 — Engaged (Day 4-10): Account has used core feature [X] at least 5 times, exported or shared an output, and at least one user has invited a teammate
Level 3 — Embedded (Day 11-21): Account has run [X] workflows or generated [Y] outputs, usage is on 5+ of last 14 days, and has connected to their primary workflow tool (e.g., Salesforce, Slack, or Zapier)
Level 4 — Blocked (Day 7-21): Account hit a feature limitation, rate limit, or permission wall — these are highest-urgency conversion opportunities
Level 5 — Stalling (Day 14+): Account activated Level 1 but progression stopped — churn risk if not intervened within 72 hours

ACTIVATION TRIGGER MATRIX:
Level 1 → Level 2 stall: Trigger automated in-app guided tour of core feature via Intercom + 1:1 email from CSM
Level 3 + Blocked: Sales-assist trigger — immediate SDR outreach with upgrade CTA and limited-time trial extension offer
Level 4 (Blocked): Direct AE notification in Slack with account context; 30-minute upgrade demo scheduled same day
Stalling at Level 1 after 7 days: Automated win-back sequence (3-email series from founder/CEO with quick-start video)

DELIVERABLE 3 — WEBSITE VISITOR INTELLIGENCE ACTIVATION WORKFLOW

STEP 1 — IDENTIFICATION CONFIGURATION
Tool: RB2B (individual identification via email) + Clearbit Reveal (company-level via IP)
Filtering rules:
- Exclude: ISPs, universities (.edu), government (.gov), existing customers (suppress by CRM domain list), internal IPs, VPN exit nodes (if detectable), competitor domains
- Include: Companies matching ICP firmographic criteria (industry, employee count, revenue estimate)
- De-duplicate: If RB2B identifies an individual who is already a known CRM contact, route to their owner with behavioral context; if net-new, create new lead record

STEP 2 — ROUTING DECISION TREE
Intent Score ≥ 70 + ICP Tier 1 + Not in CRM: → Immediate SDR outreach queue (SLA: 4 business hours)
Intent Score 40-69 + ICP Tier 1 or 2: → ABM nurture sequence enrollment + account-level retargeting activation
Intent Score 20-39 + ICP Tier 1: → Marketing nurture enrollment + SDR watch list (alert if score increases 15+ in 7 days)
Intent Score < 20 or ICP Tier 3: → Broad nurture only, no sales resource allocation

STEP 3 — PERSONALIZATION ACTIVATION
Pricing page visitor (ICP Tier 1-2, not in CRM): Activate LinkedIn retargeting with proof-point ad (customer ROI stat + "See how [Company] achieved X in Y days")
Feature page visitor (3+ sessions): Activate email nurture with relevant feature-specific case study sequence
Competitive comparison page visitor: Activate displacement ad sequence with head-to-head comparison content + SDR competitive outreach sequence

DELIVERABLE 4 — COHORT ACTIVATION PROGRAMS

COHORT 1 — SURGING (Score increased 20+ points in last 7 days):
Program: "Hot Account Sprint"
Marketing: Activate LinkedIn conversation ads to all known contacts at account + direct mail with personalized insert (if address available from Clearbit)
Sales: SDR executes 5-touch sequence in 7 days with intent-informed personalization ("I noticed [Company] has been researching [topic] — timing must feel right")
Success metric: Meeting booked rate ≥ 18% of surging ICP Tier 1 accounts

COHORT 2 — STEADY (Consistent moderate engagement 30+ days):
Program: "Warm Nurture Escalation"
Marketing: Upgrade nurture track from educational content to decision-stage content (case studies, analyst reports, ROI tools)
Sales: SDR quarterly check-in with new value-add asset ("Thought you'd find this relevant given your interest in [topic]")
Success metric: Score increase to 60+ within 30 days of program enrollment

COHORT 3 — STALLING (High score 14+ days ago, recent silence):
Program: "Re-engagement Catalyst"
Marketing: Send re-engagement email with new content hook ("A lot has changed in [category] — here's what companies like yours are doing now")
Paid: Activate retargeting with social proof ("Join 340 teams who [achieved outcome]")
Success metric: Return visit within 14 days of program activation ≥ 22%

COHORT 4 — DARK (Was active, silent 21+ days):
Program: "Long-cycle Patient Nurture"
Marketing: Monthly newsletter-style educational email (no sales CTA) to stay top-of-mind
Sales: Remove from active outreach; set 90-day re-evaluation trigger
Success metric: Score re-activation (any contact from account revisits site) within 90 days ≥ 12%

DELIVERABLE 5 — REVENUE ATTRIBUTION FRAMEWORK

FIRST-PARTY INTENT SOURCED PIPELINE:
Definition: Any opportunity where the account's first-party intent score crossed ≥ 50 within the 30 days prior to MQL or opportunity creation
Measurement: Monthly — pull all opportunities created in period, check intent score history in CRM 30 days prior, calculate % with score ≥ 50
Reporting metric: "First-party intent-sourced pipeline: $X (Y% of total pipeline)"

FIRST-PARTY INTENT ASSISTED PIPELINE:
Definition: Any closed-won deal where account had intent score ≥ 30 at any point in the 90-day window before close date
Measurement: Quarterly — pull all closed-won deals, check intent score history in CRM 90 days prior, calculate average deal size and win rate vs. non-intent-assisted deals

LIFT ANALYSIS:
Calculate win rate for: (a) ICP Tier 1 accounts with intent score ≥ 50 at any point in sales cycle, vs. (b) ICP Tier 1 accounts with no behavioral intent score above 30 during sales cycle
Report: "Intent-activated accounts convert at X% vs. Y% for equivalent ICP accounts without behavioral activation — Z× lift"

COST-PER-INTENT-ACTIVATION:
Calculate: (Annual cost of visitor identification tools + MAP automation cost) ÷ (Number of intent-activated accounts that became MQLs in 12 months)
Benchmark target: Intent activation cost-per-MQL should be ≤ 40% of paid media CPL for equivalent ICP quality

DELIVERABLE 6 — OPERATIONAL CADENCE & AUTOMATION ARCHITECTURE

DAILY AUTOMATION:
- RB2B identifies new visitors → CRM enriched automatically via Clearbit → ICP filtering applied → Intent score calculated → Routing decision made → SDR notified or nurture enrolled (all within 2 hours of visit)
- Trial usage events from Amplitude → Segment pipeline → CRM field update → Activation ladder level updated → Triggered if level changes
- Stalling accounts (no new signal for 21 days) → Automated alert to demand gen team → Re-engagement program auto-enrolled

WEEKLY CADENCE:
- Monday AM: Sales team receives "Top 10 surging ICP accounts" digest (Intent score increased 15+ in last 7 days) with: company name, pages visited, recommended first line for outreach, and relevant case study link
- Wednesday: Marketing reviews cohort health dashboard: % of ICP Tier 1 accounts in each cohort, cohort movement rates, program performance vs. benchmarks
- Friday: Automated intent score decay applied (all signal points receive recency discount based on signal age)

MONTHLY REPORTING:
- First-party intent program ROI dashboard: intent-sourced pipeline, intent-assisted closed-won revenue, cost-per-intent-MQL, cohort conversion rates, visitor identification rate (% of visitors successfully identified as ICP accounts)
- Benchmark: Target identifying ≥ 15% of total monthly visitors as named ICP accounts

CONSTRAINTS:
- All automation must operate within GDPR/CCPA compliance frameworks — no tracking of identified individuals without consent mechanism in place
- Intent scoring logic must be documented and auditable for marketing operations review
- SDR outreach triggered by behavioral signals must include appropriate opt-out mechanisms and not reference specific pages visited in outreach copy (privacy-preserving personalization)
- Score calculation must be recalculated at minimum every 24 hours to ensure signal freshness

OUTPUT FORMAT:
Deliver each section as a deployable specification: scoring tables, decision trees, automation workflow diagrams (described in text), and KPI benchmarks. Include a 30-60-90 day implementation roadmap for standing up the full program from scratch.

## Example Input/Output

**Input Example:**
Company: ProcureIQ (AI-powered procurement analytics for mid-market manufacturers)
ICP: VP of Procurement, CFO, and Operations Directors at 200-2,000 employee manufacturing companies
ACV: $52,000 | Sales cycle: 55 days | 14-day trial available
Website: 9,200 monthly visitors, ~1,100 identified via Clearbit Reveal
Trial accounts: 180 active, 34 expired in last 30 days
Stack: HubSpot CRM, Marketo, Amplitude, RB2B, Clearbit, FullStory

**Output Example:**

*Signal Taxonomy (excerpt):*
| Signal | Raw Points | Recency Multiplier (7-day) | Adjusted Score |
|--------|-----------|---------------------------|----------------|
| ROI Calculator Completed | 50 | 1.0× | 50 pts |
| Pricing Page (3+ visits) | 35 × 3 = 105 | 1.0× | 105 pts |
| Competitive Comparison Page | 40 | 0.75× (day 10) | 30 pts |
| Integration Docs Viewed | 25 | 1.0× | 25 pts |
| Blog Post: "How to Cut Procurement Costs" | 3 | 1.0× | 3 pts |
| **Account Total (ICP Tier 1: 1.3× multiplier)** | | | **276 pts → Score: 92/100** |

*Product Usage Ladder (excerpt):*
Midwest Manufacturing Co. — 180 trial accounts analyzed:
- 34% reach Level 1 (Activated)
- 21% reach Level 2 (Engaged) — converting at 11% trial-to-paid
- 8% reach Level 3 (Embedded) — converting at 67% trial-to-paid
- **Insight: Every account connecting their ERP integration (Level 3 trigger) within the first 14 days converts at 3.2× the rate of accounts who don't. Prioritize in-app guidance to push ERP connection above all other onboarding steps.**

*Routing example:*
Account "Hartwell Distribution Co." — 580 employees, VP Procurement identified via RB2B:
- Pricing page: 4 visits in 5 days (35 × 4 = 140 pts × 1.0× recency = 140)
- ROI Calculator completed: 50 pts
- Competitive comparison page: 40 pts
- **Account Intent Score: 230 → Normalized to 87/100 × 1.3× ICP multiplier = 91/100**
- **Routing decision: Immediate SDR queue — SLA 4 hours — outreach talk track: "I saw Hartwell has been evaluating procurement analytics options — many manufacturers your size are seeing 8-12% reduction in indirect spend in first 90 days. Worth 15 minutes to see if we'd get you there?"**

*30-Day Attribution result:*
- 1,100 identified accounts → 142 crossed intent score ≥ 50 threshold
- 28 became MQLs within 30 days of crossing threshold (20% intent-MQL conversion)
- 11 became active opportunities (39% MQL-to-Opp conversion vs. 18% for non-intent-activated ICP accounts)
- Intent activation lift: **2.2× higher MQL-to-opportunity conversion rate**

## Success Metrics

- **Visitor identification rate:** ≥ 15% of monthly unique visitors successfully identified as named ICP accounts
- **Intent-activated MQL conversion rate:** Intent-activated ICP accounts should convert to MQL at 1.5-3× the rate of equivalent non-activated ICP accounts
- **SDR outreach timing:** ≥ 80% of Surging Tier 1 accounts contacted within 4 business hours of crossing intent threshold
- **Trial activation ladder progression:** ≥ 35% of trial accounts reach Level 2 (Engaged) within 10 days
- **Stalling cohort re-engagement:** ≥ 20% of Stalling accounts return to active engagement within 30 days of re-engagement program
- **Intent-sourced pipeline:** First-party intent program should account for ≥ 15% of total marketing-sourced pipeline within 90 days of full deployment
- **Cost-per-intent-MQL:** Should be ≤ 40% of equivalent paid media CPL for same ICP quality tier
- **Score model accuracy:** Quarterly calibration — accounts that scored ≥ 70 should have a ≥ 2× higher win rate than accounts scoring < 30, controlling for ICP fit

## Related Prompts
- [Third-Party Intent Data Analytics Engine](./AI-Powered-B2B-SaaS-Third-Party-Intent-Data-Intelligence-&-Signal-to-Pipeline-Revenue-Activation-Analytics-Engine.md)
- [ABM Target Account List Building & ICP Scoring](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-ABM-Target-Account-List-Building-&-ICP-Scoring-Intelligence-Engine.md)
- [Predictive Lead Scoring Architecture](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Scoring-&-MQL/AI-Powered-B2B-SaaS-Predictive-Lead-Scoring-Architecture-&-MQL-Revenue-Pipeline-Intelligence-Engine.md)
- [Full-Funnel Journey Stitching & Revenue Intelligence](../Customer-Journey-Analytics/AI-Powered-B2B-Full-Funnel-Journey-Stitching-&-Anonymous-to-Pipeline-Revenue-Intelligence-Engine.md)

## Integration Tips

- **HubSpot:** Use HubSpot's custom property fields to store intent score, cohort classification, and last signal date. Build workflows that auto-update contact/company records when Segment pushes behavioral events. Use HubSpot's predictive lead scoring as a secondary layer on top of your behavioral score.
- **Salesforce:** Create a custom object "Account Intent Score" with fields for raw score, ICP-adjusted score, cohort classification, and score history (last 90 days). Use Salesforce Flow to route high-intent accounts to SDR queues and trigger tasks. Connect Amplitude or Segment via Zapier or a native connector.
- **RB2B:** Configure RB2B's Slack integration to send real-time alerts to your #hot-accounts channel with visitor name, company, pages visited, and LinkedIn profile link. Build a Zap that creates a HubSpot or Salesforce task from each RB2B alert.
- **Marketo:** Use Interesting Moments to log first-party behavioral signals (pricing page visit, calculator completion) as trackable milestones. Create Smart Lists that segment accounts by intent score tier for targeted campaign enrollment. Use Marketo's API to push intent scores from your scoring engine back into the platform.
- **Amplitude/Segment:** Define a "Product Intent Score" computed trait in Segment Personas that aggregates product usage events into a score. Sync this trait to your CRM daily. Set up Amplitude cohorts for each activation ladder level and sync to Braze or Intercom for triggered messaging.
- **Clearbit/Warmly:** Use Clearbit's reverse IP lookup to enrich anonymous sessions with company-level data before individual identification. Warmly's intent tiles can display real-time visitor context for SDRs reviewing active accounts. Connect Warmly alerts to your SDR prospecting queue via their Salesforce or HubSpot native integration.
- **Retargeting activation:** Connect your CRM cohort lists (Surging, Steady, Stalling) to LinkedIn Matched Audiences and Google Customer Match for cohort-specific ad creative. Refresh cohort membership weekly to ensure ads show only to accounts in the target intent stage.

## Troubleshooting

**Problem: Low visitor identification rate (< 8% of visitors identified as named accounts)**
Solution: IP-to-company identification tools typically identify 10-20% of B2B traffic. If you're below 8%, check: (a) Is your ICP predominantly remote/WFH workers using home ISPs? If so, supplement with RB2B's individual email identification (which captures individuals regardless of IP). (b) Are you filtering too aggressively? Review your exclusion list and ensure you're not excluding entire cloud provider IP ranges. (c) Review your traffic quality — if organic SEO traffic is heavy on informational queries attracting non-ICP researchers, your ICP identification rate will naturally be lower. Focus identification budget on high-intent page visitors only.

**Problem: Intent score model is generating too many false positives (high-score accounts aren't converting)**
Solution: This usually means signal weighting is calibrated to activity volume rather than purchase correlation. Run a retrospective analysis: pull your last 50 closed-won deals and examine what their first-party behavioral pattern looked like 60 days prior. Identify the 3-5 signals that appeared in ≥ 60% of those pre-close patterns and increase their weight by 1.5×. Simultaneously, pull your last 20 high-score accounts that went dark without converting — identify which signals they share that winners don't, and reduce those signal weights. Recalibrate monthly for the first quarter.

**Problem: SDR team isn't using the behavioral context in outreach (just generic sequences despite intent signals)**
Solution: The problem is friction in the workflow, not motivation. Fix the format: instead of asking SDRs to check a dashboard, push intent context directly into the outreach tool they're already using. If using Outreach or Salesloft, create a custom field that auto-populates with "Last high-intent action: [pricing page visit on Monday, ROI calculator completed Tuesday]" in the sequence step. Build a Slack alert that formats the behavioral context as a ready-to-use first line ("Hi [Name] — noticed [Company] has been evaluating procurement automation options recently — curious what's driving the timing?"). Reduce the cognitive load to zero.

## Version History
- v1.0: Initial creation (auto-generated)
