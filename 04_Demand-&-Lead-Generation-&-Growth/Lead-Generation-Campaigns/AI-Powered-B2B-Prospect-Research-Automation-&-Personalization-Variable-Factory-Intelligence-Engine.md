# AI-Powered B2B Prospect Research Automation & Personalization Variable Factory Intelligence Engine - Build a Scalable AI Research System That Generates Hyper-Personalized Outbound Variables at Scale

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, outbound, personalization, prospect-research, clay, data-enrichment, sdr, demand-generation, ai-automation, pipeline-generation, gtm, cold-outreach, waterfall-enrichment

## Overview
Builds a fully autonomous AI prospect research system that scrapes, synthesizes, and converts raw account and contact data into personalization variables — unique icebreakers, pain-point hooks, relevance bridges, and proof points — that inject directly into outbound sequences at scale. Use this when your cold email reply rates are stuck below 3%, when SDRs spend more than 40% of their time on research, or when you need to run personalized outbound to 500+ prospects per week without scaling headcount.

## Quick Copy-Paste Version

You are an expert B2B prospect research AI. I am going to give you raw data about a prospect and their company. Your job is to extract 8 personalization variables I can inject into cold outreach templates.

COMPANY DATA:
- Company name: [e.g., Ironclad]
- Industry: [e.g., Legal Tech / CLM Software]
- Company size: [e.g., 400 employees, Series D, $150M raised]
- Recent news or events: [e.g., "Announced partnership with Salesforce in Q1, hiring 30 enterprise AEs"]
- Tech stack (from BuiltWith/G2): [e.g., Salesforce, Gong, Outreach, Greenhouse]
- Job postings signals: [e.g., 5 open "Enterprise Account Executive" roles mentioning "complex sales cycles" and "legal workflow automation"]
- G2/Capterra reviews sentiment: [e.g., Users praise product but complain about onboarding complexity]

CONTACT DATA:
- Name: [e.g., Marcus Chen]
- Title: [e.g., VP of Revenue Operations]
- LinkedIn recent activity: [e.g., Posted last week about "why RevOps teams are the new growth lever in enterprise SaaS"]
- Tenure at company: [e.g., 14 months]
- Previous company: [e.g., Came from DocuSign where he ran RevOps for 3 years]

MY COMPANY:
- Name: [e.g., Fullcast]
- What we do: [e.g., AI-powered sales territory and capacity planning platform]
- Core pain we solve: [e.g., Revenue leaders waste 3+ weeks per quarter rebuilding territory plans in spreadsheets]
- Best proof point: [e.g., Calendly cut territory planning time from 6 weeks to 4 days]

Generate exactly these 8 personalization variables:

1. **ICEBREAKER** — One sentence referencing something specific and recent about the prospect or company that shows I did real research. Not generic. Avoid mentioning funding unless it was announced in the last 30 days.

2. **PAIN_HOOK** — One sentence that names the exact operational pain this prospect almost certainly experiences given their role, company stage, and tech stack.

3. **RELEVANCE_BRIDGE** — One sentence connecting their recent activity (LinkedIn post, hiring, news event) to the specific problem my product solves.

4. **PROOF_STAT** — One sentence with a specific customer outcome from a similar company (same stage, similar role) that makes the value concrete.

5. **COMPETITOR_SIGNAL** (if applicable) — If their tech stack includes a tool my product replaces or integrates with, note the tension or opportunity. If no competitor signal exists, write "N/A".

6. **TIMING_TRIGGER** — One sentence explaining WHY now is the right time for this prospect to evaluate us, based on signals in their data.

7. **SOFT_CTA_VARIANT_A** — A no-pressure call to action that asks for a reaction, not a meeting. Under 15 words.

8. **SOFT_CTA_VARIANT_B** — An alternative CTA that offers something of value (insight, benchmark, template) rather than asking for time. Under 20 words.

Output format: Return each variable as a labeled field I can paste directly into a Clay table or CRM variable field. No explanation — just the output value for each variable.

## Advanced Customizable Version

ROLE: You are a GTM research analyst and personalization architect for a B2B SaaS company. Your job is to operate like a Clay enrichment workflow — taking raw input data across multiple sources and generating a complete personalization variable set for outbound campaigns. Every variable must be specific, evidence-based, and ready to inject into outreach templates without editing.

RESEARCH METHODOLOGY:
Apply these research frameworks in sequence:
1. Account-Level Intelligence: Company trajectory, market position, growth signals, strategic initiatives
2. Contact-Level Intelligence: Role context, professional history, public content, behavioral signals
3. Trigger Mapping: Match signals to buying moment probability (High/Medium/Low)
4. Variable Generation: Produce output variables in the exact format the sequence templates require

---

ACCOUNT INPUT DATA:
Company Name: [TARGET_COMPANY]
Website: [URL]
Industry/Vertical: [INDUSTRY]
Employee Count: [HEADCOUNT]
Funding Stage & Amount: [FUNDING]
HQ Location: [LOCATION]
Annual Revenue (estimated): [REVENUE_ESTIMATE]

SIGNAL DATA (paste raw, unformatted — AI will parse):
- Recent news (last 90 days): [PASTE_NEWS_SNIPPETS]
- LinkedIn company page recent posts: [PASTE_LINKEDIN_ACTIVITY]
- Job postings (titles + key phrases from descriptions): [PASTE_JOB_DATA]
- G2/Capterra/Trustpilot review highlights (positive and negative): [PASTE_REVIEW_SNIPPETS]
- Tech stack (BuiltWith, Datanyze, or manual): [PASTE_TECH_STACK]
- Hiring velocity (headcount change over 6 months): [PASTE_HIRING_DATA]
- Executive changes (new C-suite/VP hires, departures): [PASTE_EXEC_CHANGES]

CONTACT INPUT DATA:
Full Name: [CONTACT_NAME]
Title: [CONTACT_TITLE]
Department: [DEPARTMENT]
Seniority: [SENIORITY_LEVEL — IC/Manager/Director/VP/C-Suite]
LinkedIn URL: [LINKEDIN_URL]
Tenure at Current Company: [TENURE_MONTHS]
Previous Company + Role: [PREV_COMPANY_ROLE]
LinkedIn Posts (last 60 days — topics, themes, engagement): [PASTE_LINKEDIN_POSTS]
Speaking/podcast appearances (if any): [APPEARANCES]
Published articles or newsletters: [CONTENT_LINKS]

MY COMPANY CONTEXT:
Company: [YOUR_COMPANY]
Product category: [CATEGORY]
One-line value proposition: [VALUE_PROP]
Primary ICP: [ICP_DESCRIPTION]
Top 3 customer pain points we solve:
  1. [PAIN_1]
  2. [PAIN_2]
  3. [PAIN_3]
Proven ROI metrics (real customer data):
  - [METRIC_1: e.g., "Reduced territory planning from 6 weeks to 4 days — Calendly"]
  - [METRIC_2: e.g., "Increased quota attainment by 22% — Intercom"]
  - [METRIC_3: e.g., "Cut plan revision cycles by 73% — Figma"]
Direct competitors: [COMPETITOR_LIST]
Tools we integrate with: [INTEGRATION_LIST]
Tools we replace: [DISPLACEMENT_LIST]

CAMPAIGN CONTEXT:
Sequence type: [Cold intro / Re-engagement / Competitor displacement / Event follow-up / Inbound follow-up]
Primary channel mix: [Email + LinkedIn / Email only / LinkedIn only / Multi-channel]
Sequence length: [4-touch / 6-touch / 8-touch]
Desired outcome per touch: [e.g., "Touch 1 = Reply with interest / Touch 3 = Book call / Touch 5 = Demo confirmation"]

---

DELIVERABLE: Generate the complete personalization variable set below. For each variable, output the ready-to-use string value ONLY — no explanations, no meta-commentary. Variables marked * are required; others are conditional.

**REQUIRED VARIABLES:**

*VAR_ICEBREAKER:
[Single sentence, 15–25 words. Reference one specific, verifiable, recent signal about the prospect or company. Avoid funding mentions unless < 30 days. Avoid vague compliments. Test: would this sentence make the prospect think "how did they know that?"]

*VAR_PAIN_HOOK:
[Single sentence, 10–20 words. Name the operational pain this person almost certainly experiences based on their role and the company's signals. Should feel like you read their mind. Begin with "Most [Title]s at [Company Stage] companies..." or equivalent pattern.]

*VAR_RELEVANCE_BRIDGE:
[One sentence connecting a specific observable signal (post, hiring pattern, tech choice, news) to the exact problem your product addresses. Bridge format: "[Signal] → [Implication] → [Why your product is the answer]."]

*VAR_PROOF_POINT:
[One sentence with a specific, named customer outcome from a company at similar stage/vertical. Include company name, metric, timeframe. Format: "[Customer] [achieved X result] in [timeframe] after [doing thing your product enabled]."]

*VAR_TIMING_TRIGGER:
[One sentence explaining WHY this prospect should evaluate you NOW vs. in 6 months. Must be grounded in a specific observable signal — not generic urgency. Bad: "Now is a great time to explore..." Good: "With [X new AEs joining] in Q2, this is exactly when territory conflicts start compounding before they're visible in CRM data."]

*VAR_CTA_A (Meeting-ask variant):
[Under 15 words. Low-friction ask for a reaction, opinion, or quick conversation — not "Can we book 30 minutes?"]

*VAR_CTA_B (Value-offer variant):
[Under 20 words. Offer a specific, named asset — benchmark, template, analysis, teardown — that is immediately valuable regardless of purchase intent.]

**CONDITIONAL VARIABLES (generate only if signals exist):**

VAR_COMPETITOR_DISPLACEMENT (if competitor tech detected in stack):
[One sentence naming the specific competitor signal and the natural friction or limitation that creates an opening. Must reference something specific about THEIR use of the competitor — not a generic claim.]

VAR_EXEC_CHANGE_HOOK (if new leader in buying role detected):
[One sentence acknowledging the transition without being presumptuous. Focus on what new leaders in this role typically prioritize in their first 90 days, then bridge to your product.]

VAR_CONTENT_MIRROR (if contact published relevant content):
[One sentence that mirrors back a specific theme or argument from their recent content, then extends it in a way that connects to the problem you solve. Never paraphrase vaguely — quote or closely reference their actual language.]

VAR_FUNDING_HOOK (if funding announced < 30 days ago):
[One sentence acknowledging the milestone and connecting it to the inevitable GTM scaling challenges that follow a raise at this stage.]

VAR_HIRING_SIGNAL_HOOK (if hiring pattern detected):
[One sentence connecting their specific hiring pattern (roles, volume, language in JDs) to the operational implication that your product addresses.]

---

QUALITY STANDARDS:
- Every variable must pass the "so what?" test — a generic version of the same sentence would fail
- Every variable must be verifiable — no invented data, no assumed facts
- Every variable must be directly injectable into a template without editing
- Tone: peer-to-peer, not vendor-to-prospect; confident, not eager
- Reading level: 8th grade or below for all variables
- Character limits: Icebreaker ≤ 160 chars; Pain Hook ≤ 140 chars; all CTAs ≤ 200 chars

FINAL STEP — TRIGGER SCORE:
After generating all variables, provide:
- TRIGGER_SCORE: [1–10] — Overall buying signal strength for this prospect right now
- TRIGGER_SCORE_RATIONALE: [2–3 sentences explaining the score based on signal combination]
- RECOMMENDED_SEQUENCE_TYPE: [Which campaign type to route this prospect to based on signals]
- PRIORITY_TIER: [Tier 1 (contact within 24h) / Tier 2 (contact within 72h) / Tier 3 (standard queue)]

## Example Input/Output

**Input Example:**

Account: Ramp (fintech/spend management, 1,200 employees, Series D, $750M raised)
Contact: Sarah Okonkwo, VP of Revenue Operations, 18 months at Ramp, previously RevOps Director at Brex for 4 years
LinkedIn activity: Posted 9 days ago: "Territory planning in hypergrowth is broken. We rebuilt ours 4 times last year and still missed coverage gaps in APAC."
Job postings: 3 open RevOps Manager roles mentioning "Salesforce territory management" and "capacity modeling"
Tech stack: Salesforce, Gong, Clari, Outreach, Workday
My Company: Fullcast — AI territory and capacity planning platform

**Output Example:**

VAR_ICEBREAKER:
Your post about rebuilding territory plans 4 times in a year — that "4x and still missed APAC" line is the exact story we hear from every hypergrowth RevOps team.

VAR_PAIN_HOOK:
Most RevOps VPs at Series D companies are manually reconciling Salesforce territory data with capacity models in spreadsheets — then repeating it every time an AE churns or a new market opens.

VAR_RELEVANCE_BRIDGE:
Three open RevOps Manager roles with Salesforce territory management in the JD is usually the signal that current territory infrastructure is breaking under headcount growth — the exact moment manual processes stop scaling.

VAR_PROOF_POINT:
Calendly's RevOps team cut territory planning cycles from 6 weeks to 4 days after replacing their Google Sheets-Salesforce patchwork with Fullcast — during a period when they added 40 AEs in two quarters.

VAR_TIMING_TRIGGER:
With 3 RevOps managers being onboarded into a territory model you've rebuilt 4 times, the window to systematize this before the next planning cycle is roughly the next 6–8 weeks.

VAR_CTA_A:
Does that APAC gap story still hold, or did you find a fix?

VAR_CTA_B:
Happy to share the territory planning audit template we built from 200+ RevOps teardowns — no agenda, just useful.

VAR_COMPETITOR_DISPLACEMENT:
You're running Clari for forecasting but territory modeling is still upstream in Salesforce — that's the exact seam where data inconsistency compounds before it shows up in forecast accuracy.

VAR_CONTENT_MIRROR:
Your framing that territory planning in hypergrowth is "broken" — not just hard — is exactly right; the architecture problem is that most territory tools were designed for stable orgs, not companies adding 10 AEs per quarter.

TRIGGER_SCORE: 9/10
TRIGGER_SCORE_RATIONALE: Direct public signal from the buyer naming the exact pain the product solves. Active hiring in the function signals the problem is growing, not shrinking. 18-month tenure means she owns the problem and has the authority to change it.
RECOMMENDED_SEQUENCE_TYPE: Content-Mirror + Pain-Proof cold intro sequence
PRIORITY_TIER: Tier 1 — contact within 24 hours

## Success Metrics

- **Variable specificity rate**: 90%+ of generated variables reference a verifiable, named signal — not generic assumptions
- **Icebreaker pass rate**: >80% of icebreakers would make a prospect say "how did they find that?" when shown blind
- **Template injection rate**: 100% of variables inject into sequence templates without manual editing
- **Reply rate lift**: Sequences using AI-generated variables outperform template-only sequences by 2–4x (industry benchmark: AI-personalized B2B cold email achieves 8–15% reply rates vs. 1–3% for generic templates)
- **Research time per prospect**: Target 90 seconds or less of human review time per variable set generated
- **Trigger score accuracy**: Tier 1 prospects (score 8–10) should convert to pipeline at 2–3x the rate of Tier 3 prospects
- **Variable freshness**: All signals referenced in variables should be < 90 days old; icebreaker signals < 30 days old

## Related Prompts

- [AI-Powered B2B Signal-Based Prospecting & Real-Time Account Trigger Outbound Intelligence Engine](./AI-Powered-B2B-Signal-Based-Prospecting-&-Real-Time-Account-Trigger-Outbound-Intelligence-Engine.md)
- [AI-Powered B2B Outbound Sales Sequence Production & Hyper-Personalization Intelligence Engine](./AI-Powered-B2B-Outbound-Sales-Sequence-Production-&-Hyper-Personalization-Intelligence-Engine.md)
- [AI-Powered B2B Marketing Qualified Account (MQA) Scoring & Pipeline Handoff Intelligence Engine](./AI-Powered-B2B-Marketing-Qualified-Account-MQA-Scoring-&-Pipeline-Handoff-Intelligence-Engine.md)
- [AI-Powered B2B Intent Data Program Architecture & Multi-Signal Revenue Orchestration Intelligence Engine](./AI-Powered-B2B-Intent-Data-Program-Architecture-&-Multi-Signal-Revenue-Orchestration-Intelligence-Engine.md)

## Integration Tips

- **Clay (clay.com)**: This prompt is designed to operate as a "Claude enrichment column" inside a Clay table. Paste the Advanced Version as your Clay AI prompt, map input columns to the `[BRACKET]` fields, and output each VAR_ as a separate Clay column. Connect downstream to Apollo Sequences, Outreach, or Salesloft via Clay's native integrations for fully automated enrichment-to-send workflows.

- **HubSpot**: Store each VAR_ output as a custom contact property. Use HubSpot's Personalization Tokens to inject `{{contact.var_icebreaker}}` directly into email sequence templates. Combine with HubSpot's AI content assistant for final tone tuning.

- **Salesforce + Outreach/Salesloft**: Create custom fields on the Lead/Contact object (e.g., `Personalization_Icebreaker__c`). Populate via a connected enrichment workflow (Zapier, Make, or direct API). Map fields to Outreach/Salesloft sequence variables for automatic injection on enrollment.

- **Apollo.io**: Apollo's custom variables feature accepts pre-populated text fields per contact. Export AI-generated variables to a CSV and bulk import, then map to Apollo's `{{customVar1}}` template tokens. Works with Apollo's built-in sequence engine.

- **Make (Integromat) or Zapier Automation**: Build a webhook trigger that fires when a new row is added to a Google Sheet or Airtable base → sends the row data to Claude API using this prompt → writes variables back to the sheet → enrolls the contact in a sequence tool. Full automation loop with zero SDR research time.

- **Notion AI + CRM**: For smaller teams without Clay, run this prompt manually in Notion AI, store outputs in a Notion database with CRM sync (HubSpot or Pipedrive), and trigger outreach directly from the Notion record.

- **n8n (self-hosted)**: For data-sensitive environments, deploy n8n with a Claude node. Build a pipeline that pulls account + contact data from your CRM, runs through this prompt, and writes back to a custom CRM enrichment object — all behind your firewall.

## Troubleshooting

**Problem: Variables feel generic despite feeding in real data**
Solution: The most common cause is underspecified signal data. The AI cannot invent specificity — it can only synthesize what you provide. For `VAR_ICEBREAKER` specifically, you must paste the actual text of a LinkedIn post, news headline, or job description excerpt — not a summary like "they posted about growth." Feed raw, unedited source text. If no fresh signals exist for a prospect, downgrade them to Tier 3 and use a pain-hook-only template rather than forcing a fake icebreaker.

**Problem: VAR_PAIN_HOOK reads like everyone else's messaging**
Solution: Pain hooks go generic when the role and stage inputs are too broad. Instead of "VP of RevOps at a SaaS company," input "VP of RevOps, 18 months tenure, Series D, 3 open territory manager JDs mentioning capacity modeling." The more operational specificity in the role context, the more precise the pain hook. Also ensure your own pain points (#1–3 in the template) are written as operational symptoms ("rebuilds territory plans manually 4+ times per year") not product features ("lacks an automated territory planning tool").

**Problem: TRIGGER_SCORE is consistently 6–7 with no clear Tier 1 prospects**
Solution: This indicates your signal data collection is too shallow. A score of 8–10 requires at least 2 of the following: (1) a public statement from the buyer naming the exact pain, (2) active hiring that signals the problem is growing, (3) a recent funding or leadership event that creates budget availability or new mandate, (4) a competitive displacement signal. Audit your data sources — if you're only feeding employee count and title, you will never generate Tier 1 scores. Add LinkedIn post scraping (Phantombuster, Taplio API), job posting enrichment (Otta, Greenhouse job board APIs), and G2 review monitoring to your enrichment stack.

## Version History
- v1.0: Initial creation (auto-generated)
