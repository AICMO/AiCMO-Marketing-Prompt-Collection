# Marketing Intelligence Knowledge Hub Engine - AI-Powered Strategic Intelligence Layer for CMOs

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** ai, marketing-intelligence, knowledge-management, competitive-intel, market-research, strategy, analytics, automation, b2b, b2b-saas

## Overview
This prompt builds a living, AI-queryable Marketing Intelligence Knowledge Hub — a centralized repository that continuously ingests signals from competitive sources, campaign performance data, customer voice, market research, and content analytics, then synthesizes them into actionable strategic recommendations. Use it when you need a single intelligence layer that answers the question "what should we do next?" without pulling 12 spreadsheets.

## Quick Copy-Paste Version

You are an expert marketing intelligence architect. Build me a complete Marketing Intelligence Knowledge Hub for the following business:

Company: [Your Company] — [e.g., B2B SaaS workflow automation platform targeting mid-market operations teams]
Primary buyers: [e.g., VP Operations, Head of RevOps, IT Directors at companies 200–2,000 employees]
Current intelligence gaps: [e.g., we don't know why we're losing deals to Competitor X, which content themes actually convert, or which segments are churning fastest]
MarTech stack: [e.g., HubSpot CRM, Gong, Semrush, G2, Slack, Google Analytics 4, Notion]
Intelligence consumers: [e.g., CMO, content team, demand gen, product marketing, sales leadership]

Deliver a complete Marketing Intelligence Knowledge Hub system including:
1. Intelligence source map — every signal source I should be ingesting and why, ranked by strategic value
2. Knowledge taxonomy — how to structure and categorize intelligence so AI can retrieve it accurately
3. Five intelligence workflows I can automate this month using my existing stack
4. Weekly intelligence digest template — the exact format to surface the most critical insights to leadership
5. AI query playbook — 20 specific questions my team can ask the knowledge hub to get instant strategic answers
6. Gap analysis — what intelligence I'm currently flying blind on and how to fill those gaps in 30 days

Format as an implementation-ready playbook I can hand to my marketing ops team tomorrow.

## Advanced Customizable Version

ROLE:
You are a Chief Marketing Intelligence Officer with 18+ years of experience building knowledge infrastructure for fast-scaling B2B SaaS and enterprise software companies. You have designed marketing intelligence systems at companies like Gartner, Forrester, HubSpot, and Salesforce. You specialize in converting raw market noise into structured, AI-retrievable intelligence that drives measurable revenue impact. You understand modern MarTech architecture, vector databases, prompt engineering for knowledge retrieval, and how to build intelligence operations with lean teams. Your systems run autonomously — no analyst required to produce a weekly briefing.

CONTEXT:
Company: [Company Name]
Business model: [B2B SaaS / D2C / B2C subscription / marketplace / professional services]
Annual revenue / ARR: [e.g., $8M ARR, growing 85% YoY]
Target market: [e.g., Mid-market financial services companies, 500–5,000 employees, North America]
Primary buyers and influencers: [e.g., CFO economic buyer, Controller champion, FP&A analyst end-user]
Competitive landscape: [e.g., 3 direct competitors, 2 emerging AI-native threats, 1 legacy incumbent]
Current intelligence maturity: [Level 1: Ad hoc research only / Level 2: Scheduled competitor tracking / Level 3: Integrated BI dashboards / Level 4: Proactive AI-driven intelligence]
Team size and roles who consume intelligence: [e.g., CMO, 2 PMMs, 1 content strategist, SDR team of 6]

INTELLIGENCE SOURCES IN SCOPE:
- Competitive intelligence: [Competitor websites, G2/Capterra reviews, LinkedIn job postings, PR/news, pricing pages, product changelogs — specify which competitors]
- Market intelligence: [Industry analyst reports, customer survey data, buyer intent signals from Bombora/G2, earnings calls, industry conferences]
- Customer intelligence: [CRM win/loss data, Gong call recordings, NPS/CSAT responses, support ticket themes, customer interviews, expansion/churn signals]
- Content intelligence: [SEO performance by topic cluster, content engagement metrics, social share velocity, conversion rates by content type and stage]
- Channel intelligence: [Paid media performance by segment and creative, email deliverability and engagement patterns, organic social share of voice]
- Sales intelligence: [Pipeline velocity by segment, objection frequency from Gong, demo-to-close rates by ICP attribute, sales cycle length trends]

OBJECTIVE:
Design a production-ready Marketing Intelligence Knowledge Hub that:
1. Ingests and structures intelligence from all in-scope sources with minimal manual effort
2. Creates an AI-queryable knowledge layer that surfaces relevant intelligence on demand
3. Generates automated intelligence digests calibrated to each consumer's strategic priorities
4. Identifies intelligence gaps and proactively flags when signals suggest strategic pivots are needed
5. Operates at 80% automation with a one-person marketing ops owner

DELIVERABLES:

1. INTELLIGENCE SOURCE ARCHITECTURE
   Map every intelligence source with the following schema:
   
   For each source:
   - Source name and URL/tool: [e.g., G2 Competitor Reviews — g2.com/products/[competitor]]
   - Signal type: [Competitive / Market / Customer / Content / Channel / Sales]
   - Collection method: [Manual weekly / API pull / RSS/webhook / Zapier automation / Native integration]
   - Update frequency: [Real-time / Daily / Weekly / Monthly]
   - Strategic value score: [1-10] with rationale
   - Current collection status: [Active / Inactive / Gap]
   - Owner: [Marketing Ops / PMM / Content / Demand Gen]
   
   Prioritize sources by: (a) decision frequency — how often does this intelligence change strategic decisions? and (b) collection cost — how much effort does it require per insight?
   
   Flag the top 5 "quick win" intelligence sources that can be activated this week with no engineering.

2. KNOWLEDGE TAXONOMY & STRUCTURE
   Design the taxonomy for structuring all collected intelligence so AI retrieval is precise and decision-relevant:
   
   **Top-Level Categories:**
   - MARKET: Industry trends, TAM shifts, regulatory changes, analyst coverage
   - COMPETITIVE: Competitor moves, feature gaps, pricing changes, hire signals, win/loss patterns
   - CUSTOMER: Voice of customer, journey friction points, expansion triggers, churn signals, segment behavior
   - CONTENT: Topic performance, format effectiveness, SEO opportunity clusters, competitive content gaps
   - CHANNEL: Paid performance by segment, organic trend signals, email health metrics, channel mix shifts
   - PIPELINE: Conversion patterns, objection frequency, deal velocity anomalies, segment win rates
   
   For each category, specify:
   - Sub-categories and tagging schema (for vector retrieval)
   - Retention policy: [Keep forever / Rolling 12 months / Rolling 90 days]
   - Confidence scoring rubric: [How to rate the reliability of each piece of intelligence]
   - Contradiction handling: [What happens when two sources disagree]
   - Update/invalidation triggers: [What signals indicate a piece of intelligence is outdated]
   
   Include a sample Notion/Airtable/Obsidian schema with field definitions for immediate implementation.

3. INTELLIGENCE AUTOMATION WORKFLOWS
   Design 8 automated workflows using common MarTech tools (Zapier, Make, HubSpot, Slack, Notion):
   
   **Workflow A — Competitive Move Alert:**
   Trigger: [Competitor's G2 review mentions specific feature OR pricing page changes detected via Visualping]
   Action: [Auto-populate competitive intelligence Notion database → Slack alert to PMM channel → Trigger battlecard review task]
   Tools: Visualping + Zapier + Notion + Slack
   Setup time: [2 hours]
   
   **Workflow B — Customer Voice Synthesis:**
   Trigger: [Weekly — every Monday 6am]
   Action: [Pull all new G2/Capterra reviews + Gong call tags + NPS comments from past 7 days → Claude API synthesizes top 5 themes by sentiment → Posts summary to #product-marketing Slack channel]
   Tools: Zapier + Gong API + Delighted/Medallia + Claude API + Slack
   Setup time: [4 hours]
   
   **Workflow C — Win/Loss Intelligence Capture:**
   Trigger: [Deal stage changes to Closed Won or Closed Lost in CRM]
   Action: [Auto-send 3-question email to AE + customer/prospect → Responses logged to knowledge base → Weekly pattern synthesis report to CMO]
   Tools: HubSpot + Typeform + Notion + Make.com
   Setup time: [3 hours]
   
   **Workflow D — Content Performance Intelligence:**
   Trigger: [Weekly — every Tuesday]
   Action: [Pull GA4 + HubSpot blog data → Rank content by pipeline influence (not just traffic) → Flag underperforming high-investment content → Identify emerging topic clusters in top 20 performing pages]
   Tools: GA4 API + HubSpot API + Google Sheets + Claude API
   Setup time: [5 hours]
   
   **Workflow E — Intent Signal Activation:**
   Trigger: [Target account shows 2+ intent signals in rolling 7-day window]
   Action: [Flag in CRM + alert owning AE/SDR with relevant intelligence context (recent content consumed, competitor research activity, company news) + suggest outreach angle]
   Tools: Bombora/G2 Buyer Intent + HubSpot + Slack + Clay.com
   Setup time: [6 hours]
   
   Design 3 additional workflows specific to [Company Name]'s intelligence gaps and MarTech stack.

4. WEEKLY INTELLIGENCE DIGEST SYSTEM
   Design the automated weekly intelligence digest with audience-specific versions:
   
   **CMO DIGEST (Monday 7am delivery):**
   Section 1 — MARKET PULSE (2 bullets max): What changed in the market this week that affects our strategy?
   Section 2 — COMPETITIVE MOVES (3 bullets max): What are competitors doing that we need to respond to?
   Section 3 — PIPELINE HEALTH (2 metrics + trend): Where is the pipeline healthy / at risk?
   Section 4 — CONTENT SIGNAL (1 insight): What content theme is showing breakout performance?
   Section 5 — RECOMMENDED ACTION (1 decision): One specific action CMO should prioritize this week with supporting data
   Max length: 250 words. No dashboards to click through.
   
   **PMM DIGEST (Tuesday 8am delivery):**
   Section 1 — COMPETITIVE INTELLIGENCE: New competitor moves, updated battlecard triggers, feature announcements
   Section 2 — CUSTOMER VOICE THEMES: Top 5 emerging themes from reviews, calls, support tickets
   Section 3 — WIN/LOSS PATTERNS: Closed-period win rate by segment + top 3 win reasons, top 3 loss reasons
   Section 4 — MESSAGING PERFORMANCE: Which value props are resonating in deals vs. falling flat (from Gong data)
   
   **CONTENT TEAM DIGEST (Wednesday 9am delivery):**
   Section 1 — TOP PERFORMING CONTENT: Pipeline-influenced content from past 30 days (not just traffic)
   Section 2 — EMERGING SEARCH OPPORTUNITY: 3-5 high-intent keywords competitors rank for that we don't
   Section 3 — CONTENT GAPS vs BUYER JOURNEY: Where in the funnel does content coverage drop off?
   Section 4 — COMPETITOR CONTENT MOVES: New whitepapers, webinars, or campaigns launched by competitors
   
   Include the exact prompts to feed into Claude/ChatGPT to auto-generate each digest from raw data inputs.

5. AI QUERY PLAYBOOK — 30 STRATEGIC QUERIES
   Design 30 specific questions the marketing team can ask the knowledge hub for instant intelligence retrieval, organized by strategic use case:
   
   **COMPETITIVE STRATEGY (8 queries):**
   - "What are the 5 most common reasons we lose to [Competitor X] and which objections could we neutralize with better positioning?"
   - "How has [Competitor X]'s messaging on [pricing/security/integration] changed in the past 90 days?"
   - "Which customer segments are [Competitor X] targeting with recent job postings that we haven't fully penetrated?"
   - "What features do customers praise most about competitors that we don't yet offer or haven't marketed?"
   - "Which competitor is gaining the most review velocity on G2 and what are reviewers saying they love?"
   - "Are there market segments where we consistently win deals and competitors have no wins? What makes those segments ours?"
   - "What does our win/loss data say about the deals where we beat [Competitor X]? What was the pattern?"
   - "Which competitor announcements from the past 30 days require a marketing response and what should that response be?"
   
   **CONTENT & CAMPAIGN STRATEGY (8 queries):**
   - "Which content topics in our top 20 performing posts have we NOT published a follow-up or update on in 6+ months?"
   - "What are buyers researching in the 30 days before they become a qualified lead? What content addresses those questions?"
   - "Which content assets have the highest pipeline influence ratio (pipeline touched / traffic) and what do they have in common?"
   - "What are the top 10 questions our SDRs get asked in first calls that we don't have good content to answer?"
   - "Which email subject lines in the past 6 months drove the highest reply rates in outbound sequences?"
   - "What content did deals that closed in under 45 days engage with vs. deals that took 90+ days?"
   - "Which topic clusters are competitors investing in heavily that we've ignored? What's the traffic opportunity?"
   - "What content themes are resonating on LinkedIn in our target ICP persona's feed right now?"
   
   **AUDIENCE & SEGMENT INTELLIGENCE (7 queries):**
   - "Which ICP attributes are most predictive of expansion revenue in year 2? What segments should we double down on?"
   - "What pain points show up most frequently in customer discovery calls from the [Financial Services] vertical?"
   - "Which segment has the highest NPS AND the lowest content engagement — where are we dropping the ball on nurture?"
   - "What do customers who churn in the first 90 days have in common (segment, acquisition source, onboarding path)?"
   - "Which buyer personas are underrepresented in our pipeline vs. their frequency in our target market?"
   - "What are the trigger events that predict when a prospect account is about to enter an active buying cycle?"
   - "Which customer segments have the highest referral rates and what marketing do we do with those customers post-close?"
   
   **CHANNEL & BUDGET INTELLIGENCE (7 queries):**
   - "Which paid media channels are delivering the highest pipeline-influenced revenue per dollar invested in the last 90 days?"
   - "What's the pipeline contribution rate of organic content vs. paid media for [specific ICP segment]?"
   - "Where are the biggest conversion rate drop-offs in our funnel by channel and what's causing them?"
   - "Which email sequences have the highest reply-to-meeting conversion rate and what do they do differently?"
   - "If we had to cut our marketing budget 20% tomorrow, which programs should we protect and which should we cut?"
   - "Which campaigns from the past 12 months generated pipeline that actually closed vs. pipeline that stalled?"
   - "What's the marginal cost of generating one additional SQL from each of our active channels right now?"

6. INTELLIGENCE GAP ANALYSIS & 30-DAY ACTIVATION PLAN
   Conduct a systematic gap analysis across all six intelligence categories:
   
   For each gap identified, deliver:
   - Gap description: [What intelligence are we missing?]
   - Strategic impact: [What decisions are we making blindly because of this gap?]
   - Fill method: [Exactly how to collect this intelligence — tool, process, frequency]
   - Time to activate: [Hours of setup required]
   - Cost: [Tool cost or time cost per month]
   - Priority tier: [P1: Activate this week / P2: Activate this month / P3: Activate next quarter]
   
   Identify the "intelligence debt" — the 3 decisions we've made in the past 12 months that would have been different with better intelligence — and use those to prioritize the gap closure roadmap.

OUTPUT FORMAT:
Deliver all 6 sections as an implementation-ready document. For each section, include:
- The strategic framework (what and why)
- The operational implementation (how and who)
- A "start here" callout box identifying the single highest-ROI first action in each section
- Success metrics for the intelligence system itself (how we know it's working)

## Example Input/Output

**Input Example:**

Company: Meridian Analytics — B2B SaaS workforce analytics platform for HR and People teams at enterprise companies (1,000–10,000 employees). Competes with Visier, Workday Prism, and Tableau. $12M ARR, 38% win rate, losing deals mostly to Visier ("they have more HR-specific features") and Workday ("we already have it"). Current intelligence: ad hoc Googling, quarterly analyst subscriptions we don't use, and a shared Notion doc no one updates.

**Output Example (excerpt from CMO Digest):**

---
**MERIDIAN INTELLIGENCE DIGEST — Week of March 9, 2026**
**For: Sarah Chen, CMO**

**MARKET PULSE**
- Visier raised $125M Series E last Tuesday; press release emphasizes "AI workforce planning" — 7 references to AI vs. our 2. Recommend reviewing our AI narrative before their awareness campaign hits.
- 3 enterprise RFPs published on SAP Ariba this week list "workforce analytics with HRIS integration" as Tier 1 requirement — our integration story isn't in the top 3 results for that search term.

**COMPETITIVE MOVES**
- Visier launched "Visier Vee" AI assistant feature (G2 reviews mention it in 4 new reviews this week) — none of our sales battlecards mention it. Escalated to PMM.
- Workday Prism posted 6 new "People Analytics Specialist" job roles in NYC and Austin — likely expanding sales capacity in our top two geographies.
- No significant Tableau moves this week.

**PIPELINE HEALTH**
- Enterprise pipeline (>$100K ACV): $2.1M, +12% vs. last week ✅
- Mid-market pipeline ($25K–$100K ACV): $847K, -8% vs. last week ⚠️ — investigate deal slip in financial services segment

**CONTENT SIGNAL**
- "HR Analytics ROI Calculator" landing page: 340% spike in organic traffic this week (Semrush shows new featured snippet win for "HR analytics ROI"). Recommend immediate CTA optimization and retargeting audience build.

**RECOMMENDED ACTION**
Brief the PMM team on Visier Vee AI feature by EOD Wednesday. Update battlecard Section 3 (AI capabilities comparison) and push updated version to SDR team before Thursday's pipeline review.

---

## Success Metrics
- **Intelligence activation rate:** % of weekly digest recommendations that result in a tracked marketing action (target: >60%)
- **Decision latency reduction:** Time from market event to marketing response (target: <72 hours for Tier 1 signals)
- **Intelligence coverage score:** % of six intelligence categories with active data sources (target: >80%)
- **Win rate lift:** Improvement in win rate for deals where sales team consulted intelligence hub before first call (measure via CRM tagging, target: +8pp lift)
- **Content performance improvement:** Pipeline influence rate of content created using intelligence-derived themes vs. baseline (target: 2x baseline)
- **Digest engagement rate:** % of digest recipients who take a documented action within 48 hours of delivery (track via task creation in project management tool, target: >50%)

## Related Prompts
- `../../05_Analytics-&-Marketing-Operations/AI-Knowledge-Base-Management/Customer-Intelligence-Knowledge-Base.md` — for building the customer-specific intelligence layer that feeds into this hub
- `../../01_CMO-&-Leadership/Strategy-&-Planning/AI-Powered-Competitive-Intelligence-Engine.md` — for deep-dive competitive intelligence collection methodology
- `../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Advanced-Marketing-Analytics-Intelligence-Platform.md` — for the analytics infrastructure that powers intelligence synthesis
- `../../02_Product-Marketing/Customer-&-Market-Research/Voice-of-Customer-Analysis.md` — for structuring the customer voice intelligence stream

## Integration Tips
- **Notion:** Build the knowledge taxonomy as a linked database system. Use Relations to connect COMPETITIVE entries to PIPELINE entries so win/loss data enriches battlecards automatically. Set up Notion AI to answer natural language queries against the database.
- **Slack:** Create a #marketing-intelligence channel and configure all automated digest workflows to post there. Use thread replies to log actions taken — this creates an audit trail of intelligence-driven decisions.
- **HubSpot:** Tag all CRM contacts, deals, and engagements with intelligence-relevant properties (ICP segment, competitor involved, content consumed pre-conversion). This makes intelligence retrieval queryable directly in HubSpot reporting.
- **Zapier / Make.com:** Build the 8 core automation workflows first before adding any manual collection processes. Automate the boring, high-frequency collection tasks; reserve human judgment for synthesis and decision-making.
- **Google Sheets + Claude API:** For companies without enterprise BI tools, a Google Sheets master intelligence log + Claude API for weekly synthesis is a surprisingly robust substitute. Use Apps Script to auto-pull from Semrush API, GA4 API, and G2 RSS feeds.
- **Gong:** Tag calls with intelligence-relevant labels (objection type, competitor mentioned, use case discussed). Build a Gong + Notion integration to auto-log tagged call insights into the knowledge hub's PIPELINE and CUSTOMER categories.
- **Airtable:** Alternative to Notion for teams that prefer spreadsheet-native interfaces. Build intelligence views by category, by owner, and by freshness date. Use Airtable Automations for staleness alerts when intelligence hasn't been updated in 30+ days.

## Troubleshooting
**Problem: The knowledge hub becomes a graveyard — intelligence is logged but no one reads or acts on it.**
Solution: Separate collection from consumption. The hub is the storage layer; the digest is the consumption layer. If people aren't reading the hub, optimize the digest — make it shorter, more opinionated, and pre-answer the "so what?" question. The hub should never require a login to get value; the digest should push insights to where people already work (Slack, email, meeting agendas).

**Problem: Intelligence quality is inconsistent — some sources are gold, others add noise and confusion.**
Solution: Implement a confidence scoring system (High/Medium/Low) for every intelligence entry at the moment of collection. Low-confidence signals (single-source, unverified) should be labeled as "hypothesis" in digests rather than stated as fact. After 90 days, audit which sources generated intelligence that actually influenced decisions vs. which just filled database rows. Eliminate the latter ruthlessly.

**Problem: The system requires too much manual effort to sustain — it's abandoned after 6 weeks.**
Solution: Audit every manual step in the collection process. If any single intelligence category requires more than 2 hours/week of human effort, it's over-engineered. Automate or drop it. The sustainability threshold for a lean marketing team is a total of 3–4 hours/week of human time across the entire intelligence operation. Everything else must be automated or excluded.

## Version History
- v1.0: Initial creation (auto-generated)
