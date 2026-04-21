# AI-Powered B2B Anonymous Visitor Intelligence & ICP Account Engagement Scoring Revenue Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** website-intelligence, visitor-identification, account-scoring, intent-data, 6sense, clearbit, leadfeeder, rb2b, pipeline-attribution, b2b-analytics, ip-resolution, buying-signals

## Overview
This engine transforms your website's anonymous traffic into a scored, prioritized account intelligence system — de-anonymizing B2B visitors using IP resolution and enrichment tools (6sense, Clearbit Reveal, Leadfeeder, RB2B, Koala), scoring engagement by ICP fit and page-level buying signal strength, and triggering SDR outreach at the exact moment accounts hit purchase-ready thresholds. Use it when 95%+ of your website visitors leave without converting, when your SDR team has no visibility into which target accounts are actively researching you, or when you want to close the gap between dark social/direct traffic and pipeline attribution.

## Quick Copy-Paste Version

You are a senior B2B demand intelligence analyst specializing in anonymous visitor de-anonymization, account-level engagement scoring, and website-to-pipeline revenue attribution. You work with B2B SaaS companies selling to mid-market and enterprise buyers who research vendors extensively before contacting sales.

My website intelligence context:
- Product/Industry: [e.g., AI-powered contract lifecycle management SaaS for legal and procurement teams at $200M+ companies]
- Primary ICP: [e.g., General Counsel, VP Procurement, VP Legal Operations at manufacturing, professional services, and technology companies, 500–10,000 employees, US-based]
- Monthly website sessions: [e.g., 42,000 sessions/month — 71% anonymous, 29% identified via form fills]
- Current visitor identification tool: [e.g., Leadfeeder / 6sense / Clearbit Reveal / RB2B / Koala / none yet]
- CRM: [e.g., Salesforce Enterprise]
- MAP: [e.g., Marketo / HubSpot]
- SDR team size: [e.g., 8 SDRs covering named accounts + inbound]
- Average deal ACV: [e.g., $68,000]
- Sales cycle: [e.g., 90–150 days]
- Biggest intelligence gap: [e.g., "We know 800+ target accounts visit us per month but SDRs only reach out to the 12% who fill a form — we're missing 700 warm accounts per month"]

Build a complete anonymous visitor intelligence and account engagement scoring system with:

1. ICP IDENTIFICATION LAYER: Design a 5-filter firmographic scoring model to rank anonymous accounts by ICP fit. Include: (a) company size filter (employee count + revenue range), (b) industry vertical match (specify the SIC/NAICS codes for my top 3 verticals), (c) technographic stack signals (what installed technologies indicate ICP readiness — e.g., DocuSign + SAP + Workday = high-fit legal/procurement buyer), (d) geographic territory filter for SDR coverage, and (e) account tier override (automatic Tier 1 assignment for named accounts already in CRM).

2. BEHAVIORAL ENGAGEMENT SCORING: Build a weighted engagement score (0–100) using these page-level intent signals. Assign point values and justify each: homepage visit (baseline), pricing page visit, competitor comparison page, ROI calculator usage, case study download, demo page visit without conversion, return visit within 14 days, 3+ pages in a single session, time-on-site >4 minutes, and careers page visit (negative signal — job hunting, not buying). Calculate the score threshold at which an account should trigger SDR outreach versus nurture sequence versus ignore.

3. SDR TRIGGER PROTOCOL: Design the exact alert system — which engagement score + ICP fit score combination triggers a same-day SDR task versus a next-business-day task versus an automated email sequence. Write the SDR alert message template that surfaces: account name, ICP score, engagement score, pages viewed (in order), time spent per page, prior CRM history, and a recommended first outreach message personalized to the specific pages they visited. Include the outreach copy framework: "We noticed [Company] has been researching [specific topic based on pages viewed] — here's what companies like yours typically ask us about [that topic]..."

4. REVENUE ATTRIBUTION MODEL: Build the methodology to prove website visitor intelligence ROI to your CFO. Define: (a) the control group approach — SDR outreach to high-ICP anonymous accounts triggered by intelligence alerts vs. accounts that were equally high-ICP but NOT flagged (cold outreach), (b) the pipeline conversion rate comparison between alerted vs. non-alerted accounts, (c) the formula: [Incremental closed deals from alerts × ACV] - [Tool cost + SDR time cost] = Net intelligence ROI, and (d) the reporting cadence for sharing this data with VP Sales and CMO.

5. WEEKLY INTELLIGENCE BRIEF: Design the automated weekly report format that your SDR team lead receives every Monday morning — top 10 accounts by engagement score change week-over-week, accounts that went from cold to warm (triggered by a visit spike), named accounts from your target account list (TAL) that visited for the first time, and re-engaged accounts (no visit in 90+ days who came back this week).

Output all scoring models with specific point values, all thresholds with justification, and all templates ready to implement in Salesforce + your visitor intelligence tool today.

## Advanced Customizable Version

ROLE: You are a Principal Revenue Intelligence Architect and B2B GTM analytics expert with 16+ years of experience building account-based intelligence programs at B2B SaaS companies. You are a recognized expert in the de-anonymization technology stack (6sense, Clearbit/HubSpot Breeze Intelligence, Leadfeeder/Dealfront, RB2B, Koala, Warmly, Albacross, Lead Forensics), GA4 advanced configuration for B2B account tracking, Salesforce/HubSpot intent data integration, and the science of converting behavioral website signals into sales-ready pipeline. You understand that 97% of B2B website visitors are anonymous, that enterprise buyers conduct 57–70% of their vendor research before contacting sales (Gartner), and that companies who can identify and engage high-intent accounts 2–3 weeks before a form fill gain a decisive first-mover advantage. You design systems that give revenue teams a 20–30% pipeline lift without increasing headcount.

---

COMPANY CONTEXT:

**Company Profile:**
- Company Name: [Company Name]
- Product Category: [e.g., AI-powered contract lifecycle management SaaS / enterprise procurement automation / B2B spend intelligence platform]
- ARR & Growth Rate: [e.g., $18M ARR, growing 72% YoY]
- Average Contract Value (ACV): [e.g., $68,000 — range: $28K mid-market to $240K enterprise]
- Total Addressable Accounts: [e.g., 12,400 companies in the US that match our ICP definition]
- Named Target Account List (TAL) Size: [e.g., 1,800 named accounts prioritized by SDR team]
- Average Sales Cycle: [e.g., 90–150 days mid-market; 180–270 days enterprise]

**Website Traffic Profile:**
- Monthly Sessions: [e.g., 42,000 sessions/month]
- Identified Sessions (form fills / known cookies): [e.g., 29% identified — 12,180 sessions/month]
- Anonymous Sessions: [e.g., 71% — 29,820 sessions/month]
- IP Resolution Tool in Use: [e.g., Leadfeeder (Dealfront) / 6sense Website Intelligence / Clearbit Reveal / RB2B / Koala / Warmly / none — planning to implement]
- Estimated B2B Account Resolution Rate: [e.g., approximately 15–25% of anonymous sessions resolve to a company using IP resolution; rest are ISPs, residential, VPN, or unresolvable]
- Top Traffic Sources: [e.g., 38% organic search, 28% LinkedIn ads, 18% direct/dark social, 11% Google Ads, 5% referral]

**ICP Definition:**
- Employee Count Range: [e.g., 500–10,000 employees]
- Revenue Range: [e.g., $50M–$2B annual revenue]
- Primary Industries (SIC/NAICS codes): [e.g., Manufacturing (NAICS 31-33), Professional Services (NAICS 54), Technology (NAICS 51)]
- Primary Buyer Personas: [e.g., General Counsel (economic buyer), VP Legal Operations (champion), VP Procurement (co-buyer), CISO (security approver for deals >$150K)]
- Key Disqualifiers: [e.g., companies <200 employees; government/public sector (different procurement cycle); pure-play ecommerce (different use case)]

**Go-To-Market Motion:**
- SDR Team: [e.g., 8 SDRs — 5 outbound/named account, 3 inbound response]
- SDR Daily Outreach Capacity: [e.g., 40–60 personalized touches per SDR per day across phone, email, LinkedIn]
- Average SDR Sequence: [e.g., 12 touches over 21 days]
- CRM: [Salesforce Enterprise / HubSpot CRM / other]
- MAP: [Marketo / HubSpot / Pardot / other]
- SDR Alert Tool: [e.g., Outreach.io / Salesloft / direct Salesforce task / Slack webhook]

**Current State:**
- Anonymous Visitor Problem: [e.g., "We know 800+ target accounts visit us per month based on Leadfeeder data, but our SDRs only receive tasks for the 12% who fill a form — 700 warm accounts/month are never contacted"]
- SDR Pain Point: [e.g., "SDRs spend 2.5 hours/day identifying which cold accounts to prospect — they have no visibility into which accounts are actively researching us right now"]
- Attribution Gap: [e.g., "When an account goes dark for 45 days then suddenly comes back and requests a demo, we have no record of their prior anonymous research sessions — sales walks in blind"]
- Tool Stack: [e.g., GA4 + Leadfeeder + Salesforce + Outreach + LinkedIn Sales Navigator]

---

DELIVERABLE 1 — ICP ACCOUNT IDENTIFICATION & FIRMOGRAPHIC SCORING MODEL

Build a 6-dimension ICP Fit Score (0–100 points total) for de-anonymized accounts:

**A) FIRMOGRAPHIC MATCH SCORE (0–30 points):**

Design the scoring rubric for each dimension:
- Employee Count: [Specify point values — e.g., 500–2,000 = 30 pts; 2,001–10,000 = 25 pts; 200–499 = 15 pts; <200 or >25,000 = 0 pts]
- Revenue Range: [Specify point values aligned to ACV]
- Industry Vertical: [Primary SIC/NAICS = 30 pts; adjacent = 15 pts; unrelated = 0 pts]
- Geography: [Territory coverage match = 10 pts; out-of-territory = 5 pts]
- Company Type: [Private equity-backed = bonus 5 pts; pre-IPO = bonus 3 pts; public company = standard]

For my company context, calculate the PERFECT ICP profile (100-point account) with exact firmographic specifications.

**B) TECHNOGRAPHIC STACK SIGNALS (0–25 points):**

Identify 10 technology stack signals that indicate high purchase readiness for my product category. For each signal, specify:
- Tool name and category
- Point value (1–10)
- Why it indicates ICP readiness (what business process it reveals)
- How to detect it (Clearbit Technographics / BuiltWith / 6sense technographic data)

Example framework: If selling CLM software, accounts using DocuSign (5 pts — they value digital contracts) + SAP or Oracle ERP (8 pts — enterprise procurement process) + no incumbent CLM detected (10 pts — greenfield opportunity) = 23/25 technographic score.

**C) ACCOUNT TIER OVERRIDE:**

Design the tier assignment logic:
- Tier 1 (White Glove): Named accounts on SDR TAL that are also on Fortune 1000 or target prospect list in CRM → automatic SDR outreach within 4 business hours of ANY visit
- Tier 2 (Priority): High ICP Fit Score (70–100) but not on named TAL → SDR outreach within 24 hours if engagement score >40
- Tier 3 (Nurture): Medium ICP Fit Score (40–69) → automated nurture sequence, no SDR
- Tier 4 (Monitor): Low ICP Fit (<40) → log and ignore until re-engagement spike
- Disqualified: Competitors, current customers, job seekers (careers page >2 visits) → suppress from all alerts

---

DELIVERABLE 2 — BEHAVIORAL ENGAGEMENT SCORING ARCHITECTURE

Build a weighted Engagement Score (0–100 scale) using page-level and session-level behavioral signals. For each signal, provide: point value, decay logic, and the B2B buying stage it indicates (Awareness → Consideration → Evaluation → Decision).

**HIGH-INTENT SIGNALS (Decision/Evaluation Stage — 15–20 pts each):**
- Pricing page visit: [Score + decay logic + SDR insight to surface]
- Demo/trial request page (visited but did NOT convert): [Score + why this is the most important single signal]
- Competitor comparison page (/vs-[competitor]): [Score + which specific competitor pages indicate switch intent]
- ROI calculator engagement (>60 seconds on page): [Score + what this reveals about buying stage]
- Security/trust/compliance page: [Score + persona signal — usually indicates IT/security evaluator has entered the process]

**MEDIUM-INTENT SIGNALS (Consideration Stage — 8–14 pts each):**
- Case study/customer story page: [Score + which case study topic maps to which persona]
- Integration/API documentation page: [Score + what it signals about technical evaluation]
- Solutions/use-case page: [Score + how page specificity reveals persona]
- Product feature deep-dive pages: [Score + champion vs. economic buyer signal]
- Email or contact page visit without submission: [Score]

**AWARENESS SIGNALS (Awareness Stage — 2–7 pts each):**
- Homepage entry: [Baseline score]
- Blog/content consumption (>2 articles in session): [Score]
- Return visit (same account, <14 days): [Score — multiply by 1.5x for return visits]
- Session duration >4 minutes: [Score]
- 4+ pages per session: [Score]

**NEGATIVE SIGNALS (Subtract points):**
- Careers page (1–2 visits): [-5 pts — possible job seeker]
- Careers page (3+ visits): [-15 pts — disqualify from alerts, move to Suppressed]
- Support/help center only (no product pages): [-10 pts — existing customer support visit]
- IP resolves to known VPN or ISP: [-20 pts — unresolvable]
- Known competitor domain: [Suppress entirely]

**ENGAGEMENT SCORE DECAY MODEL:**

Design the time-decay function for engagement scores:
- Day 0 (visit day): 100% of score
- Days 1–3: 90% of score (still hot)
- Days 4–7: 70% of score (warm — SDR should still act if not yet contacted)
- Days 8–14: 50% of score (cooling — nurture priority)
- Days 15–21: 30% of score (cold — remove from active alert queue)
- Day 22+: 10% of score (historical record only; re-score on next visit)

The decayed Composite Score = ICP Fit Score (40% weight) + Engagement Score × Decay Factor (60% weight). Accounts above [threshold score — specify] trigger SDR action.

---

DELIVERABLE 3 — SDR ALERT SYSTEM DESIGN & OUTREACH PROTOCOL

Build the exact alert routing logic and outreach templates:

**A) ALERT TIER DECISION MATRIX:**

| Account Tier | Composite Score | Alert Type | SLA |
|---|---|---|---|
| Tier 1 Named | Any visit | Immediate Slack + Salesforce task | 4 business hours |
| Tier 2 Priority | >70 | Same-day Salesforce task | 8 business hours |
| Tier 2 Priority | 50–69 | Next-day Salesforce task | 24 hours |
| Tier 3 Nurture | Any | Add to Marketo/HubSpot sequence | Automated |
| Tier 4 Monitor | Any | Log to CRM, no action | None |

**B) SALESFORCE ALERT RECORD STRUCTURE:**

Design the custom Salesforce activity/task object that gets created for each alert. Specify every field the SDR sees:
- Account Name + Salesforce Account link
- ICP Fit Score (with breakdown by dimension)
- Engagement Score (with decay-adjusted current score)
- Session Details: Date/time of visit, pages viewed in order, time spent on each page, total session duration
- Prior Visit History: Number of previous sessions in last 90 days, first visit date, highest-ever engagement score
- CRM History: Last outreach date, sequence currently enrolled in, opportunity stage if open deal exists, last note from AE
- Technographic Signals: Top 3 installed technologies from Clearbit/6sense
- Recommended Action: [AI-generated suggestion: "This account visited /pricing and /vs-Competitor-X — high purchase intent, recommend immediate personalized outreach referencing their contract management pain point + Competitor X comparison"]

**C) SDR OUTREACH TEMPLATES BY PAGE VISITED:**

Write complete, send-ready email and LinkedIn message templates for each high-intent page scenario. Each template must reference the specific page visited without revealing you tracked them (keep it warm, not creepy). Include subject line, opening hook, value bridge, and soft CTA.

**Template 1: Pricing Page Visitor (No Form Fill)**
- Subject: [Write subject line optimized for >35% open rate]
- Email body: [Write 4-sentence email that opens with a relevant business trigger, references pricing-stage buying behavior naturally, provides one piece of insight they wouldn't have found on the pricing page, and offers a specific next step — not "book a demo"]
- LinkedIn variant: [Write 3-sentence InMail version]

**Template 2: Competitor Comparison Page Visitor**
- Subject: [Write subject line that acknowledges evaluation stage]
- Email body: [Write email that validates their evaluation process, provides the one differentiation point that wins most competitive deals for this competitor, and offers a "Decision Framework" asset — not a sales pitch]
- LinkedIn variant: [Write InMail version]

**Template 3: Returning Account (3rd Visit in 14 Days — No Conversion)**
- Subject: [Write subject line that creates urgency without being pushy]
- Email body: [Write email that references the pattern of their research without citing specific pages, positions your company as ready to accelerate their evaluation, and offers a 15-minute "answers-only" call — not a full demo]
- LinkedIn variant: [Write InMail version]

**Template 4: Tier 1 Named Account (Any Visit)**
- Subject: [Write subject line for an account the SDR already knows]
- Email body: [Write email for a warm account where the SDR can reference prior relationship, uses the visit as a natural re-engagement trigger, and offers value based on what they were researching]

---

DELIVERABLE 4 — REVENUE ATTRIBUTION & ROI PROOF FRAMEWORK

Build the business case methodology for proving anonymous visitor intelligence ROI:

**A) CONTROLLED ATTRIBUTION STUDY DESIGN:**

Design a 90-day study to prove the incremental value of visitor intelligence alerts:

- Control Group: High-ICP accounts (ICP Score >60) that visited the website during the study period but were NOT surfaced to SDRs (because their session didn't trigger an alert — perhaps they visited only low-intent pages, or your tool had a data gap)
- Treatment Group: High-ICP accounts that DID trigger an alert and received SDR outreach within the defined SLA

Measure and compare:
- Outreach-to-reply rate (Treatment vs. Control)
- Outreach-to-meeting booked rate
- Meeting-to-opportunity rate
- Opportunity-to-close rate
- Average time from first visit to closed-won (velocity comparison)
- Average ACV of deals influenced by alerts vs. not

**B) ROI CALCULATION FORMULA:**

Annual Visitor Intelligence ROI = 

Gross Pipeline Generated:
  [Avg monthly alerts acted on × 12 months]
  × [Alert-to-meeting rate (e.g., 18%)]
  × [Meeting-to-opportunity rate (e.g., 45%)]
  × [Opportunity-to-close rate (e.g., 22%)]
  × [ACV ($68,000)]
= Gross Annual Pipeline Closed from Intelligence Alerts

Less:
  Tool Annual Cost: [e.g., 6sense $48,000/yr or Leadfeeder $12,000/yr]
  SDR Time Cost: [alerts × avg SDR time per alert (20 min) × SDR fully-loaded hourly cost]

= Net Intelligence ROI
= ROI Multiple (Gross Pipeline / Total Cost)

Build this spreadsheet model with my actual numbers. Show the breakeven point (minimum alert-to-meeting rate needed to justify tool cost) and the 3-scenario analysis: conservative (50% of projected performance), base (as modeled), and aggressive (150% of projected).

**C) BOARD-LEVEL REPORTING:**

Design the one-page monthly board/CMO report for Anonymous Visitor Intelligence program. Include:
- Total accounts identified this month vs. last month (trend)
- Tier 1 alert response rate (SLA compliance %)
- Pipeline sourced from visitor intelligence alerts (this quarter)
- Top 10 accounts currently in active research mode (highest composite score, not yet in pipeline)
- Intelligence-sourced deals closed this quarter (list with ACV and sales cycle length vs. company average)
- Recommendation: 1-2 action items for next month based on the data

---

DELIVERABLE 5 — WEEKLY INTELLIGENCE BRIEF AUTOMATION

Design the automated Monday morning intelligence brief delivered to the SDR team lead via Slack and email. Build the exact format and data logic for each section:

**SECTION 1 — THIS WEEK'S HOT ACCOUNTS (Top 10 by Composite Score Change)**
For each account: Account name | Industry | Employee count | Composite Score (current vs. last week) | Score change (↑ or ↓) | Pages visited this week | Recommended action | Assigned SDR

**SECTION 2 — SURGE ACCOUNTS (Cold → Warm Spike)**
Accounts that had a composite score below 30 as of last Monday and are now above 60. Flag as "Surprise Surge." For each: What triggered the spike? (Which pages were visited in what order?) Was there an external trigger? (Check: Did your company publish a press release this week? Did a competitor get bad press? Is this account's industry in the news?)

**SECTION 3 — NAMED ACCOUNT FIRST VISITS**
TAL accounts that visited for the first time this week. For each: Account name | SDR owner | AE owner | Pages visited | Composite Score | Prior outreach history from CRM | Recommended next step

**SECTION 4 — RE-ENGAGED ACCOUNTS**
Accounts that had not visited in 60+ days and returned this week. For each: Account name | Days since last visit | What changed (new pages visited vs. prior session) | Prior pipeline history | Recommended action

**SECTION 5 — SDR PERFORMANCE METRICS**
- Alert-to-outreach SLA compliance this week (by tier)
- Alerts sent this week: [Tier 1 / Tier 2 / Tier 3]
- Meetings booked from alerts this week
- Sequences enrolled from alerts this week
- Alert-to-meeting rate (rolling 30-day)

**SECTION 6 — INTELLIGENCE QUALITY MONITOR**
- Total accounts resolved this week (IP match rate %)
- Alerts suppressed (competitor/customer/career-seeker filter)
- Top 3 pages driving highest-intent visits this week
- Recommended SDR talking point of the week (based on most-visited content)

---

DELIVERABLE 6 — TECHNICAL IMPLEMENTATION PLAYBOOK

Provide the step-by-step technical configuration guide for the most common stack:

**Stack A: Leadfeeder/Dealfront + HubSpot + Outreach:**
1. Leadfeeder → HubSpot company enrichment setup (field mapping)
2. HubSpot workflow triggers for engagement score thresholds
3. Outreach task creation via HubSpot workflow + Zapier
4. GA4 event tracking for page-level intent signals (specify exact event names and parameters)
5. HubSpot custom property setup for composite scoring
6. Slack integration for real-time Tier 1 alerts

**Stack B: 6sense + Salesforce + Salesloft:**
1. 6sense Website Intelligence → Salesforce lead/account enrichment
2. Salesforce flow for alert routing by tier
3. Salesloft cadence enrollment trigger from Salesforce
4. 6sense Segment creation for ICP filter
5. Dashboard configuration in 6sense for SDR team
6. Revenue attribution reporting setup

For each step, specify: exact tool setting name, where to find it in the UI, any API calls or Zapier steps required, and estimated time to configure.

---

## Example Input/Output

**Input:**
Product: AI-powered contract lifecycle management SaaS
ICP: General Counsel + VP Legal Ops at 500–5,000 employee manufacturing, professional services, and tech companies
Monthly sessions: 42,000
IP resolution tool: Leadfeeder (Dealfront)
CRM: Salesforce
SDR team: 8 SDRs
ACV: $68,000
Sales cycle: 90–150 days
Problem: "800+ target accounts visit us monthly; SDRs only reach out to the 12% who fill a form"

**Output (excerpt — ICP Fit Score for sample account):**

**ACCOUNT INTELLIGENCE ALERT**
Account: Meridian Industrial Group
Tier: 2 — Priority Outreach (24-hour SLA)
Industry: Manufacturing (NAICS 331512) ✓ Primary ICP vertical

**ICP Fit Score: 78/100**
- Employee Count: 2,200 employees → 28/30 pts
- Revenue: ~$380M estimated → 22/25 pts
- Industry: Manufacturing (primary vertical) → 20/20 pts
- Geography: US - Midwest (SDR territory covered) → 5/5 pts
- Technographic: SAP S/4HANA (8 pts) + DocuSign (5 pts) + no CLM detected (10 pts) → 20/25 pts [partial]

**Engagement Score (decayed): 67/100**
Original session score: 82 pts
- Pricing page visit: 20 pts
- /vs-Ironclad comparison page: 18 pts
- Enterprise security page: 15 pts
- 6 pages in session: 8 pts
- 5-min 40-second session duration: 8 pts
- Return visit (2nd visit this week): 13 pts
Decay factor (visit was 3 days ago): × 0.9 = 73.8 → 74 pts raw
Prior session score from 11 days ago (50% decay): +7 pts → **67 decayed**

**Composite Score: 74/100** [(78 × 0.4) + (74 × 0.6) = 31.2 + 44.4]
**Trigger: Priority Outreach — assign to SDR within 24 hours**

**Pages Visited (in order):**
1. Homepage → 1m 22s
2. /solutions/contract-lifecycle-management → 3m 08s
3. /vs-ironclad → 4m 44s ⚡ HIGH SIGNAL
4. /enterprise-security → 2m 15s ⚡ HIGH SIGNAL
5. /pricing → 3m 33s ⚡ HIGH SIGNAL
6. /customers/manufacturing → 1m 52s

**AI Recommended Outreach:**
"Meridian is in active vendor evaluation mode — they've gone from solutions overview → competitive comparison → security review → pricing in one session, which is a classic late-stage evaluation sequence. They spent 4m 44s on the Ironclad comparison page, suggesting they're evaluating us as an Ironclad alternative. The security page visit in a manufacturing company typically means the IT team has been pulled in (indicating deal size >$50K). Recommend: Senior SDR, reference Ironclad comparison + manufacturing case study, lead with the security/compliance differentiation, offer a 'security & compliance overview' call rather than a standard demo."

**Recommended Email Subject:** "How [Meridian's industry] companies are replacing Ironclad — one data point you won't find in G2"

---

## Success Metrics

Evaluate your visitor intelligence program against these benchmarks at 90 days:

| Metric | Baseline (No Intelligence) | Good (Year 1) | Excellent (Year 2+) |
|---|---|---|---|
| Anonymous visitor resolution rate | 0% | 15–25% of sessions | 25–35% of sessions |
| ICP account identification rate | <5% of TAL/month | 20–30% of TAL/month | 40–60% of TAL/month |
| Alert-to-SDR-response SLA compliance | N/A | >80% within SLA | >95% within SLA |
| Alert-to-meeting booked rate | 3% (cold outbound avg) | 12–18% | 20–28% |
| Pipeline influenced by alerts (% of total pipe) | 0% | 15–20% | 25–35% |
| Deals sourced from alerts (% of new logos) | 0% | 10–15% | 20–30% |
| Intelligence ROI multiple | N/A | 4–8× tool cost | 10–20× tool cost |
| Time from first anonymous visit to opportunity creation | No tracking | <21 days (alerted accounts) | <14 days |
| SDR research time saved per week | 0 hours | 6–10 hours/SDR | 8–12 hours/SDR |

**Quality audit checklist (run monthly):**
- [ ] IP resolution tool resolving 15%+ of sessions to named companies
- [ ] >80% of Tier 1 named account visits triggering alerts within 1 hour
- [ ] SDR alert-to-outreach SLA being hit >85% of the time
- [ ] No competitor or customer accounts receiving SDR outreach (suppression filter working)
- [ ] Engagement score thresholds producing a manageable alert volume (target: 15–40 alerts/SDR/week)
- [ ] Revenue attribution model updated monthly with closed-won data

---

## Related Prompts

- [`05_Analytics-&-Performance/Website-Analytics-&-Digital-Experience/AI-Powered-B2B-Website-CRO-Experimentation-Program-Design-&-Test-Velocity-Intelligence-Engine.md`](./AI-Powered-B2B-Website-CRO-Experimentation-Program-Design-&-Test-Velocity-Intelligence-Engine.md) — Design A/B tests to improve conversion rates for the high-intent accounts your intelligence system surfaces
- [`05_Analytics-&-Performance/Website-Analytics-&-Digital-Experience/AI-Powered-B2B-Website-Analytics-Digital-Experience-&-Pipeline-Revenue-Intelligence-Engine.md`](./AI-Powered-B2B-Website-Analytics-Digital-Experience-&-Pipeline-Revenue-Intelligence-Engine.md) — Measure overall website performance and digital experience metrics that contextualize your visitor intelligence
- [`04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/B2B-Website-Personalization-&-Dynamic-Visitor-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/B2B-Website-Personalization-&-Dynamic-Visitor-Intelligence-Engine.md) — Personalize on-site content in real time for the identified accounts your intelligence program flags
- [`05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md`](../Lead-Quality-&-Conversion-Analytics/Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md) — Integrate your account-level engagement scores into the full lead scoring model across all channels

---

## Integration Tips

**6sense Integration:**
- Use 6sense Audience segments as the ICP filter — create a "Website Active Research" segment that auto-qualifies accounts by ICP fit + buying stage prediction
- Sync 6sense account scores directly to Salesforce Account object via native connector
- Enable 6sense's "In-Market Accounts" dashboard for SDRs — it combines anonymous website visits with 3rd-party intent data for the most complete buying signal picture

**Clearbit Reveal / HubSpot Breeze Intelligence:**
- Enable company de-anonymization on all website pages — not just key landing pages — to maximize resolution rate
- Use Clearbit's technographic data to auto-score accounts in HubSpot workflows based on installed technologies
- Configure HubSpot to create a "Company" record automatically when Clearbit resolves an anonymous session meeting minimum ICP criteria

**Leadfeeder / Dealfront:**
- Set up custom Leadfeeder feeds: one per SDR territory, filtered to ICP firmographics + minimum session quality score
- Use Leadfeeder's Salesforce integration to create/update Salesforce Account records with `Leadfeeder_Score` and `Leadfeeder_Last_Visit_Date` custom fields
- Configure Leadfeeder email digest for SDR team leads — daily morning digest of prior day's activity filtered to Tier 1 and Tier 2 accounts

**Salesloft / Outreach Integration:**
- Build a Salesforce flow that creates an Outreach/Salesloft "Person" task when an alert fires, auto-enrolling the primary contact (if known) in a visitor-intelligence-triggered sequence
- Create a dedicated sequence for visitor intelligence outreach — separate from cold outbound — with looser opt-out logic and more personalized first step
- Tag all visitor intelligence outreach in Salesloft/Outreach with `Source: Visitor Intelligence Alert` for downstream pipeline attribution

**Slack Webhook:**
- Configure real-time Slack alerts to `#sdrs-hot-accounts` channel for all Tier 1 events (named account any visit) and Tier 2 accounts with composite score >80
- Format: `🔥 TIER 1 ALERT: [Account Name] ([Industry, Employee Count]) just visited [pages]. Composite Score: [X]. Assigned to: @[SDR name]. SLA: 4 hours. Salesforce link: [link]`
- Pin the weekly intelligence brief to the Slack channel every Monday at 8 AM local time

**Zapier / Make.com (no-code automation):**
- Leadfeeder → Zapier → Salesforce: Create task for SDR when Leadfeeder score exceeds threshold
- 6sense → Zapier → Outreach: Enroll account contact in sequence when 6sense buying stage reaches "Decision"
- GA4 → BigQuery → Looker Studio: Build a real-time visitor intelligence dashboard refreshing every 4 hours

---

## Troubleshooting

**Problem 1: IP Resolution Rate Is Below 10% (Too Few Accounts Being Identified)**

This is the most common issue and usually has 3 causes:
- *Cause*: Most traffic is from mobile devices or VPNs, which block IP resolution. VPN usage among enterprise buyers can be 40–60%.
- *Fix*: Supplement IP resolution with first-party identification — gate your highest-value content (ROI calculators, pricing guides, industry reports) to capture emails, then retroactively match those emails to company domains. Also implement GA4 User-ID tracking for logged-in users to stitch anonymous sessions to known contacts.
- *Cause*: IP resolution tool is only deployed on certain pages.
- *Fix*: Ensure your visitor intelligence JavaScript snippet is firing on ALL pages (homepage, blog, product pages, pricing, docs) — not just landing pages.

**Problem 2: Alert Volume Is Too High — SDRs Are Ignoring Alerts**

- *Cause*: Composite score thresholds are too low, generating 80+ alerts/SDR/day.
- *Fix*: Raise the alert threshold for Tier 2 accounts from 50 to 65 composite score. Audit the most-alerted accounts — are they competitors, current customers, or job seekers who slipped through suppression? Clean the suppression list weekly. Target alert volume: 8–15 actionable alerts per SDR per day.

**Problem 3: Attribution Reporting Shows No Pipeline from Alerts Despite SDR Activity**

- *Cause*: Salesforce opportunity source field is being set to "Inbound" when the contact later fills a demo form — overwriting the intelligence alert source.
- *Fix*: Implement a "First Significant Touch" field in Salesforce that captures the visitor intelligence alert date and cannot be overwritten by subsequent touches. Build pipeline reports that pull from this field, not the standard Lead Source field. Report on "Intelligence-Influenced Pipeline" (any deal where an alert was logged in the 90 days before opportunity creation) as a separate metric from "Intelligence-Sourced Pipeline" (deals where the alert triggered the first outreach).

---

## Version History
- v1.0: Initial creation (auto-generated)
