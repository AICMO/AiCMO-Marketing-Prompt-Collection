# AI-Powered LLM Brand Monitoring & Reputation Intelligence Engine - Track, Audit & Improve How AI Systems Represent Your Brand

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** ai-search, brand-monitoring, geo, llm-seo, reputation, b2b, automation

## Overview
This prompt systematically audits how large language models (ChatGPT, Claude, Gemini, Perplexity, Copilot) represent your brand—uncovering hallucinations, competitive displacement, sentiment gaps, and citation opportunities—then generates an actionable remediation roadmap to improve your AI brand footprint and ensure AI systems recommend you at key buying moments.

## Quick Copy-Paste Version
You are an AI brand reputation intelligence analyst. Audit how AI language models currently represent [Your Company Name], a [describe product/category, e.g., "B2B cloud security platform for mid-market SaaS companies"].

Step 1 — BRAND AUDIT QUERIES
Generate 20 high-intent queries that enterprise buyers would ask AI assistants when evaluating solutions in [your category]. Include:
- Category/problem queries: "What is the best [category] for [use case]?"
- Comparison queries: "Compare [Your Company] vs [Top Competitor 1] vs [Top Competitor 2]"
- Feature/capability queries: "Which [category] tools offer [key feature]?"
- Integration queries: "What [category] tools integrate with [HubSpot/Salesforce/Slack]?"
- Trust/validation queries: "Is [Your Company] a good [category] solution for [ICP]?"

Step 2 — REPRESENTATION AUDIT
For each query type above, simulate the most likely AI response and identify:
- Whether [Your Company] is mentioned (yes/no/partial)
- Accuracy of description (correct/partially correct/hallucinated/missing)
- Sentiment (positive/neutral/negative/absent)
- Competitive positioning (leading/secondary/absent)
- Citation sources likely influencing the response

Step 3 — GAP ANALYSIS
Identify the top 5 representation gaps:
- Hallucinations or inaccuracies to correct
- Missing product capabilities or differentiators
- Competitor mentions where you should appear
- Trust signals and social proof gaps
- ICP-specific use case coverage gaps

Step 4 — REMEDIATION ROADMAP
For each gap, generate:
- The specific content piece needed (blog post, comparison page, press release, G2 review campaign, etc.)
- The AI citation trigger it addresses
- Estimated effort (low/medium/high)
- Priority score (1-5) based on buyer intent value

Output a prioritized 30-day AI brand remediation plan.

## Advanced Customizable Version
ROLE: You are a senior AI Search Optimization (AIO) strategist and brand intelligence analyst with deep expertise in how large language models ingest, weight, and surface brand information during the AI-assisted buying process. You understand how LLM training data, RLHF fine-tuning, retrieval-augmented generation (RAG), and real-time web access collectively shape how AI systems represent brands at scale.

COMPANY CONTEXT:
- Company: [COMPANY_NAME]
- Product Category: [CATEGORY, e.g., "revenue intelligence platform for B2B sales teams"]
- ICP: [ICP, e.g., "VP Sales at Series B-D SaaS companies, 50-500 employees"]
- Key Differentiators: [DIFFERENTIATORS, e.g., "real-time deal risk scoring, CRM-native, no-code setup"]
- Top Competitors: [COMPETITOR_1], [COMPETITOR_2], [COMPETITOR_3]
- Primary Revenue Motion: [PLG / SLG / Enterprise / Channel]
- Current Known Presence: [any known G2 ratings, Gartner mentions, key press coverage]

OBJECTIVE: Conduct a comprehensive LLM brand representation audit and generate a full AI reputation improvement program. The output must be actionable by a marketing team within 30 days with zero dependency on AI vendors or model providers.

FRAMEWORK — AI BRAND REPRESENTATION MODEL (ABRM):

LAYER 1: QUERY LANDSCAPE MAPPING
Map the complete universe of AI queries relevant to your brand's buying journey:

A) AWARENESS QUERIES (Buyer doesn't know you yet)
- "What are the top [category] tools in [year]?"
- "Best [category] for [company size/stage]?"
- "How do companies solve [pain point] problem?"
- "What software do [ICP role title] use for [job to be done]?"

B) CONSIDERATION QUERIES (Buyer is evaluating)
- "[COMPANY_NAME] vs [COMPETITOR_1] — which is better for [use case]?"
- "What are the pros and cons of [COMPANY_NAME]?"
- "[COMPANY_NAME] reviews — is it worth it?"
- "Does [COMPANY_NAME] integrate with [tool]?"
- "[COMPANY_NAME] pricing — how much does it cost?"

C) DECISION QUERIES (Buyer is ready to buy)
- "Is [COMPANY_NAME] SOC2 compliant / enterprise-ready?"
- "[COMPANY_NAME] case studies in [vertical]?"
- "How long does [COMPANY_NAME] implementation take?"
- "[COMPANY_NAME] ROI — what results do customers see?"

D) DISPLACEMENT QUERIES (Competitor-led, where you should appear)
- "Alternatives to [COMPETITOR_1]"
- "[COMPETITOR_1] competitors"
- "Why companies switch from [COMPETITOR_1]"

Generate 5 queries per category = 20 total priority queries.

LAYER 2: REPRESENTATION AUDIT PROTOCOL
For each query, conduct a structured audit across five AI systems:
- ChatGPT (GPT-4o) — highest consumer volume
- Perplexity AI — highest citation transparency
- Google Gemini — integrated with search intent
- Microsoft Copilot — B2B enterprise penetration
- Claude — growing enterprise adoption

For each AI × query combination, score:
1. MENTION RATE: Is brand mentioned? (0=not mentioned, 1=briefly mentioned, 2=substantively mentioned, 3=recommended/led)
2. ACCURACY SCORE: Is information correct? (0=hallucinated, 1=partially correct, 2=mostly correct, 3=fully accurate)
3. SENTIMENT SCORE: How is brand framed? (-1=negative, 0=neutral, 1=positive, 2=recommended)
4. COMPETITIVE RANK: Where does brand rank vs competitors? (1=leader, 2=mentioned alongside leaders, 3=secondary mention, 4=absent)
5. CITATION QUALITY: Are credible sources (G2, Gartner, TechCrunch, industry analysts) driving the response?

Output as a scored matrix with overall AI Brand Presence Score (ABPS) = average across all dimensions.

LAYER 3: HALLUCINATION & MISINFORMATION AUDIT
Identify and categorize all inaccurate representations:
- PRICING HALLUCINATIONS: Wrong price points or tiers stated as fact
- FEATURE GAPS: Missing or incorrectly described capabilities
- USE CASE MISMATCH: Wrong ICP or industry associations
- COMPANY FACTS: Wrong funding stage, headcount, founding year, leadership
- COMPETITIVE MISCLASSIFICATION: Placed in wrong category or competitive set

For each hallucination, identify the likely root cause:
- Missing/outdated owned content (fix: update website, blog, docs)
- Lack of third-party validation (fix: press releases, analyst briefings, G2 reviews)
- Competitor content displacement (fix: SEO/AIO content targeting that query)
- No structured data markup (fix: JSON-LD schema implementation)

LAYER 4: COMPETITIVE DISPLACEMENT ANALYSIS
For each competitor mention where your brand is absent:
- Identify the specific query pattern
- Map the content/source driving competitor presence
- Design the counter-narrative content piece
- Prioritize by buyer intent value (Decision > Consideration > Awareness)

Apply the AI CITATION PYRAMID framework:
Tier 1 (Highest LLM weight): G2/Gartner/Forrester mentions, TechCrunch/Forbes/WSJ coverage
Tier 2 (Medium LLM weight): Industry analyst blogs, comparison sites (Capterra, GetApp), LinkedIn articles
Tier 3 (Lower LLM weight): Your own blog, case studies, website content

LAYER 5: REMEDIATION ROADMAP GENERATION
For each identified gap, generate a specific remediation action:

FORMAT PER ACTION:
- GAP: [Description of what's wrong or missing]
- ROOT CAUSE: [Why AI systems don't represent this correctly]
- ACTION: [Specific content piece or PR action]
- PLACEMENT TARGET: [Where this content should appear for maximum LLM ingestion]
- CONTENT BRIEF: [3-bullet outline of the content piece]
- EFFORT: [Low = 1-2 hours / Medium = 1 day / High = 3+ days]
- PRIORITY: [1-5, where 5 = highest buyer intent impact]
- AI CITATION TARGET: [Which AI system this is most likely to influence]
- SUCCESS METRIC: [How to verify AI representation improved after 30 days]

LAYER 6: AI BRAND MONITORING SYSTEM DESIGN
Design an ongoing monitoring cadence:

WEEKLY PULSE CHECK (15 min):
- 5 core brand queries across ChatGPT and Perplexity
- Log representation changes in tracking spreadsheet
- Flag new competitor mentions or hallucinations

MONTHLY FULL AUDIT (2 hours):
- Full 20-query audit across all 5 AI systems
- ABPS score tracking vs prior month
- Remediation action completion review

QUARTERLY STRATEGIC REVIEW (4 hours):
- New query landscape mapping (buyer language evolves)
- Competitive displacement refresh
- Content calendar update for next quarter

OUTPUT FORMAT:
1. Executive Summary (ABPS score, top 3 wins, top 3 gaps)
2. Full Query Audit Matrix (scored table)
3. Hallucination Registry (all inaccuracies found with fix assigned)
4. Competitive Displacement Map (where competitors outrank you and why)
5. 30-Day Remediation Sprint Plan (prioritized actions with owners/effort)
6. AI Brand Monitoring Dashboard Template (copy-paste into Notion/Google Sheets)
7. Monthly Progress Tracking Template

CONSTRAINTS:
- All recommendations must be executable without API access to LLM providers
- Focus on earned and owned content strategies (not paid model training)
- Prioritize actions with measurable citation impact within 60 days
- Include specific query testing instructions the team can execute manually

## Example Input/Output

**Input Example:**
- Company: Clarifai (fictional variant: "Clarion Revenue AI")
- Category: Revenue intelligence platform for B2B SaaS sales teams
- ICP: VP Sales / CRO at Series B-D SaaS, $10M-$100M ARR
- Differentiators: Real-time deal risk scoring, HubSpot-native, 5-minute setup, no data science required
- Competitors: Gong, Clari, People.ai
- Known presence: 4.7/5 on G2 (82 reviews), featured in SaaStr blog, no Gartner coverage

**Output Example (Excerpt):**

**AI Brand Presence Score (ABPS): 2.1 / 5.0**
*Benchmark: Gong = 4.3, Clari = 3.8, People.ai = 2.9*

**Top 3 Wins:**
- G2 reviews drive accurate representation in 70% of product comparison queries on Perplexity
- HubSpot-native positioning correctly cited in integration queries
- Positive sentiment in "alternatives to Gong for SMB" queries

**Top 3 Critical Gaps:**

**Gap #1: Absent from awareness queries**
- Query: "Best revenue intelligence tools for SaaS companies"
- Current AI response: Mentions Gong, Clari, Chorus.ai — Clarion not mentioned
- Root cause: No third-party analyst coverage; limited Tier 1 press citations
- Remediation: Pitch SaaStr, G2 Report submission for "Revenue Intelligence" category, guest post on Sales Hacker
- Priority: 5 | Effort: High | Timeline: 30 days

**Gap #2: Pricing hallucination on ChatGPT**
- Query: "How much does Clarion Revenue AI cost?"
- Current AI response: "Clarion starts at $299/user/month" (incorrect — actual: $150/user/month)
- Root cause: Outdated pricing page and no structured pricing FAQ content
- Remediation: Update pricing page with FAQ schema markup, publish "Clarion Pricing Guide" blog post with JSON-LD
- Priority: 5 | Effort: Low | Timeline: 3 days

**Gap #3: Missing from "Clari alternatives" displacement query**
- Query: "Alternatives to Clari for smaller SaaS companies"
- Current AI response: Mentions Gong, People.ai, Boostup — not Clarion
- Root cause: No comparison content targeting this query; Boostup has a "Clari vs Boostup" page driving citation
- Remediation: Create "Clarion vs Clari: Which is better for early-stage SaaS?" comparison page with SEO + schema
- Priority: 5 | Effort: Medium | Timeline: 5 days

**30-Day Sprint Plan:**

| Week | Action | Owner | Effort | Priority |
|------|--------|-------|--------|----------|
| Week 1 | Fix pricing hallucination: update page + add FAQ schema | Web team | 3 hrs | 5 |
| Week 1 | Submit G2 report nomination for Revenue Intelligence category | Marketing | 1 hr | 5 |
| Week 1 | Create "Clarion vs Clari" comparison page | Content | 1 day | 5 |
| Week 2 | Pitch SaaStr "Top Revenue Intelligence Tools" roundup | PR | 2 hrs | 5 |
| Week 2 | Publish "HubSpot-native revenue intelligence: complete guide" | Content | 2 days | 4 |
| Week 3 | Add JSON-LD schema to all product pages | Engineering | 4 hrs | 4 |
| Week 3 | Run G2 review campaign: target 20 new reviews in 30 days | CS | Ongoing | 4 |
| Week 4 | Publish case study: "How [Customer] reduced deal slippage 34%" | Content | 2 days | 4 |
| Week 4 | Conduct full 20-query ABPS re-audit | Marketing | 2 hrs | 5 |

**Projected ABPS After Sprint: 3.2 / 5.0** (target: match People.ai within 60 days)

## Success Metrics
- **AI Brand Presence Score (ABPS):** Target ≥3.5/5.0 within 90 days (start with current baseline, measure monthly)
- **Mention Rate Lift:** Brand mentioned in ≥70% of category awareness queries within 60 days
- **Hallucination Rate:** Zero pricing/feature hallucinations within 30 days of remediation
- **Competitive Displacement Coverage:** Brand present in ≥3 of top 5 competitor displacement queries within 60 days
- **Citation Tier Improvement:** ≥2 Tier 1 citations (G2 report, major press) driving LLM representation within 90 days
- **Organic Pipeline from AI Search:** Track UTM-tagged traffic from AI referral sources (Perplexity, ChatGPT browse) monthly

## Related Prompts
- [AI-Brand-Presence-Builder](./AI-Brand-Presence-Builder.md) — foundational AI brand visibility setup
- [Commercial-Intent-AEO-&-AI-Answer-Visibility-Engine](./Commercial-Intent-AEO-&-AI-Answer-Visibility-Engine.md) — optimizing for AI answer engine results
- [AI-Citation-Authority-&-Earned-Media-Intelligence-Engine](./AI-Citation-Authority-&-Earned-Media-Intelligence-Engine.md) — building citation authority for LLM ingestion
- [../../05_Analytics-&-Performance/Competitive-Intelligence-Analytics/Real-Time-Competitive-Monitoring-&-Market-Signal-Intelligence-Engine.md](../../05_Analytics-&-Performance/Competitive-Intelligence-Analytics/Real-Time-Competitive-Monitoring-&-Market-Signal-Intelligence-Engine.md) — broader competitive intelligence framework

## Integration Tips
- **Notion:** Create the AI Brand Monitoring Dashboard as a Notion database with query, AI system, date, ABPS score, and notes columns. Assign a team member to run weekly pulse checks and log results
- **Google Sheets:** Use the scored audit matrix template as a Google Sheet with conditional formatting to highlight gaps (red = score <2, yellow = 2-3, green = >3). Share with leadership for monthly review
- **HubSpot:** Tag contacts sourced from Perplexity/AI referral traffic with a custom property "AI-Assisted Discovery" to track AI-influenced pipeline attribution over time
- **Zapier + Perplexity API:** Automate weekly brand query checks by connecting Perplexity API to a Google Sheet via Zapier — log AI responses weekly without manual testing
- **Slack:** Set up a dedicated #ai-brand-monitoring Slack channel. Post weekly ABPS updates and tag the content team when new hallucinations or gaps are detected
- **Linear/Jira:** Convert each remediation action into a ticket in your content/marketing backlog with priority, effort, and the specific AI citation target as acceptance criteria

## Troubleshooting

**Problem:** AI responses keep changing week-to-week — tracking is inconsistent and hard to measure progress
**Solution:** Standardize your query list to exactly 20 fixed queries and test the same queries in the same AI system (same session, no prior context) each week. Use Perplexity for the most consistent citation transparency since it shows sources. Keep a version-dated Google Sheet rather than overwriting prior results.

**Problem:** Remediation content was published 4 weeks ago but AI representations haven't improved
**Solution:** LLM representation lag is real — most models update training data on 3-6 month cycles. Focus on RAG-based systems (Perplexity, Copilot with Bing) where web-indexed content influences responses within days/weeks, not months. Prioritize getting into live-indexed sources: G2 reviews, updated press coverage, and comparison pages that Perplexity actively crawls.

**Problem:** The audit keeps surfacing the same competitor (e.g., Gong) dominating every query — feels overwhelming
**Solution:** Don't try to displace the market leader everywhere at once. Use the ICP filter: identify queries where your specific ICP (company size, stage, use case) is most likely to be the asker, and win those first. A $15M ARR SaaS company asking "best revenue intelligence for Series B" is more addressable than "best enterprise revenue intelligence" — focus your content there first and build from the niche out.

## Version History
- v1.0: Initial creation (auto-generated)
