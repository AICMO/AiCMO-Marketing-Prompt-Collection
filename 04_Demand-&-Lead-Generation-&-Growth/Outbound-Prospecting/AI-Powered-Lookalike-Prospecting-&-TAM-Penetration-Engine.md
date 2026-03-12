# AI-Powered Lookalike Prospecting & TAM Penetration Engine - Find Your Best-Fit Prospects at Scale

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, outbound, prospecting, abm, automation, demand-gen, pipeline

## Overview
This engine analyzes the DNA of your best customers — firmographic, technographic, behavioral, and intent signals — to generate a scored, tiered prospect list of lookalike accounts from your total addressable market. Use it when you need to systematically expand pipeline beyond inbound by identifying which untouched accounts most closely resemble your closed-won customers.

## Quick Copy-Paste Version

You are a B2B prospecting intelligence engine. I'll give you my best customer profiles and you'll identify lookalike prospects and generate a prioritized outreach plan.

My company: [Your Company] — we sell [product/service] to [target market].

My top 5 customer profiles (paste CRM data or describe):
1. [Company name, industry, size, tech stack, pain point, deal size, time-to-close]
2. [Company name, industry, size, tech stack, pain point, deal size, time-to-close]
3. [Company name, industry, size, tech stack, pain point, deal size, time-to-close]
4. [Company name, industry, size, tech stack, pain point, deal size, time-to-close]
5. [Company name, industry, size, tech stack, pain point, deal size, time-to-close]

My TAM description: [describe the total universe of companies you could sell to]

Tasks:
1. Extract the top 8-10 "lookalike signals" that appear across my best customers (firmographic patterns, technographic commonalities, growth indicators, buying trigger events)
2. Create a weighted ICP scoring rubric (assign point values to each signal, max 100 points)
3. Generate 15 specific company archetypes I should target, with firmographic criteria for each
4. For each archetype, write a personalized outreach hook that references the specific trigger event or signal
5. Output a prioritization matrix: Tier 1 (80-100pts), Tier 2 (60-79pts), Tier 3 (40-59pts)
6. Identify 3 data sources or tools I should use to find companies matching each archetype

Output format: structured JSON-ready prospect archetypes + outreach hooks + scoring rubric.

## Advanced Customizable Version

ROLE: You are a revenue intelligence analyst and GTM strategist with deep expertise in B2B account-based prospecting, data enrichment, and sales signal interpretation. You specialize in translating closed-won customer patterns into repeatable pipeline generation systems.

OBJECTIVE: Build a complete lookalike prospecting intelligence system that transforms my best-customer DNA into a scalable TAM penetration engine.

COMPANY CONTEXT:
- Company: [Company Name]
- Product/Service: [What you sell]
- ACV/Deal Size: [Average contract value]
- Sales Cycle: [Average length]
- Current ICP (rough): [Your current ICP definition]
- Top competitors: [Competitor 1], [Competitor 2], [Competitor 3]
- Current tech stack used by sales/marketing: [CRM], [MAP], [intent data tool]

BEST CUSTOMER DATA (provide for 5-10 closed-won accounts):
For each customer, provide:
- Company name, industry (NAICS/SIC if known), employee count, ARR/revenue
- Headquarters location and office footprint
- Tech stack (pulled from BuiltWith, G2, or LinkedIn)
- Trigger event that preceded their purchase (hiring surge, funding round, product launch, compliance need, M&A activity, etc.)
- Time from first touch to close
- Deal size and expansion trajectory
- Champion title and buying committee composition
- Key pain point/use case they bought for

ANALYSIS TASKS:

**Phase 1: Pattern Extraction**
1. Identify the top 10 firmographic signals that appear in ≥60% of best customers. Weight each by predictive power (1-10 scale).
2. Identify the top 5 technographic signals (tools they use or have recently replaced).
3. Identify the top 5 buying trigger events that preceded deals (job postings, funding announcements, product launches, compliance deadlines, leadership changes).
4. Identify 3 behavioral intent signals that indicate active evaluation (review site activity, competitor research, content consumption patterns).

**Phase 2: ICP Scoring Model**
Build a 100-point weighted scoring rubric:
- Firmographic fit: [X points]
- Technographic fit: [X points]
- Trigger event present: [X points]
- Intent signal detected: [X points]
- Buying committee identifiable: [X points]
- Deal size potential: [X points]

Define Tier 1 (Spear), Tier 2 (Net), Tier 3 (Air Cover) thresholds.

**Phase 3: Prospect Archetypes**
Generate 10-15 distinct company archetypes I should target. For each archetype:
- Archetype name and description
- Firmographic criteria (industry, size, geography, growth stage)
- Technographic criteria (tools they likely use)
- Trigger event to look for
- Estimated TAM size (# of companies matching)
- Outreach personalization angle (what pain/aspiration resonates)
- Example company that fits this archetype

**Phase 4: Outreach Intelligence**
For each archetype, generate:
- A 3-sentence opening hook referencing the trigger event/signal
- One provocative insight or benchmark specific to their situation
- One discovery question that surfaces their specific pain
- Suggested subject line (curiosity-based, not pitch-based)
- LinkedIn connection note (≤300 characters)

**Phase 5: TAM Penetration Strategy**
- Estimate total TAM, SAM, and SOM based on the archetypes
- Recommend a sequenced market penetration approach (which archetype to attack first and why)
- Identify 5 data tools/sources for building prospect lists (e.g., Apollo, Clay, ZoomInfo, Bombora, LinkedIn Sales Nav)
- Define weekly pipeline-generation KPIs for each SDR running this system

OUTPUT FORMAT:
1. Lookalike Signal Matrix (table)
2. ICP Scoring Rubric (weighted rubric)
3. Prospect Archetype Cards (structured JSON-compatible)
4. Outreach Sequence Templates (per archetype)
5. TAM Penetration Roadmap (prioritized by conversion probability × deal size potential)
6. Data Stack Recommendations

CONSTRAINTS:
- All outreach must be personalized to a specific signal, never generic
- Prioritize trigger events over static firmographic criteria (buyers who are actively in a pain moment convert 4x faster)
- Every archetype must have a measurable TAM — no fuzzy segments
- Output should be directly importable into Clay, HubSpot, or Salesforce as a campaign framework

## Example Input/Output

**Input Example:**
Company: Nexus HR — sells AI-powered performance management software to mid-market companies.

Best Customers:
1. Lattice competitor account: 250-employee SaaS company, just hired VP People, using BambooHR, $45K ACV, closed in 45 days
2. Manufacturing firm: 400 employees, recently received Series B ($20M), outgrew spreadsheets, $38K ACV, closed in 60 days
3. Professional services firm: 180 employees, CHRO just joined from enterprise, using Workday too complex, $42K ACV, 30 days
4. E-commerce company: 320 employees, headcount grew 40% YoY, performance chaos, $52K ACV, 38 days
5. FinTech: 210 employees, preparing for SOC 2 audit, needed documentation trail, $48K ACV, 42 days

**Output Example:**

**Lookalike Signal Matrix:**

| Signal | Frequency | Weight | Predictive Score |
|--------|-----------|--------|-----------------|
| 200-450 employees | 5/5 | 9/10 | High |
| Raised Series B in last 18mo | 4/5 | 8/10 | High |
| VP/CHRO People hire in last 6mo | 4/5 | 9/10 | Very High |
| Using BambooHR or Workday Lite | 4/5 | 7/10 | High |
| 30%+ headcount growth YoY | 3/5 | 8/10 | High |
| SOC 2 / ISO 27001 in progress | 2/5 | 7/10 | Medium |
| Engineering + Product team ratio >30% | 3/5 | 6/10 | Medium |

**Top Prospect Archetype — "The Scaling Series B":**
{
  "archetype_name": "The Scaling Series B",
  "description": "Series B SaaS or tech company, 200-450 employees, 12-18 months post-funding, experiencing organizational growing pains",
  "firmographic": {
    "industry": ["SaaS", "FinTech", "E-commerce Tech"],
    "employees": "200-450",
    "funding_stage": "Series B",
    "funding_recency": "6-18 months ago",
    "hq": ["US", "Canada", "UK"]
  },
  "technographic": {
    "likely_using": ["BambooHR", "Rippling", "Lattice (basic plan)"],
    "recently_evaluated": ["15Five", "Leapsome"],
    "signal": "Job posting for 'People Operations Manager' or 'HR Business Partner'"
  },
  "trigger_event": "New VP of People or CHRO hired in last 90 days",
  "tam_estimate": "~4,200 companies globally",
  "outreach_hook": "Congrats on the recent Series B — scaling from 200 to 400 people in 18 months is exactly when performance management systems either accelerate growth or create organizational drag. Most teams at your stage tell us their biggest surprise is how quickly informal feedback loops break down. Worth a 15-minute conversation about what your peers have done?",
  "subject_line": "Your Series B talent scaling playbook",
  "linkedin_note": "Noticed [Company] just closed Series B — saw similar patterns at [peer company] when they hit 250 people. Curious what your performance management setup looks like at this stage."
}

**ICP Scoring Rubric:**
- 200-450 employees: 20 pts
- Series B funded 6-18 months ago: 15 pts
- New People leader hired in last 90 days: 25 pts
- Using BambooHR or basic HRIS: 15 pts
- 30%+ headcount growth signal: 15 pts
- Active job postings in HR/People Ops: 10 pts

**Tier 1 Spear (75-100 pts):** Immediate SDR outreach + executive gifting
**Tier 2 Net (50-74 pts):** Multi-touch sequence + content nurture
**Tier 3 Air Cover (30-49 pts):** Paid retargeting + newsletter subscription capture

## Success Metrics

- **Signal Extraction Quality:** ≥8 distinct, measurable signals identified from customer data
- **Archetype Coverage:** ≥10 distinct archetypes covering ≥80% of estimated TAM
- **Outreach Relevance:** Each hook references a specific, verifiable signal (not a generic pain)
- **Pipeline Impact:** Lookalike campaigns should generate 2-3x higher connect rates vs. spray-and-pray lists
- **Scoring Rubric Accuracy:** Tier 1 accounts should convert at ≥2x the rate of Tier 3 accounts (validate after 90 days)
- **TAM Quantification:** Each archetype has a numeric TAM estimate (± 20% accuracy acceptable)

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/Intent-Driven-Account-Prioritization-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/Buying-Committee-Intelligence-&-Multi-Stakeholder-Outreach-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/Multi-Channel-Outbound-Sequence-Orchestrator.md`
- `../../02_Product-Marketing/Customer-&-Market-Research/ICP-Discovery-Engine.md`

## Integration Tips

- **Clay:** Export the JSON archetype cards as Clay table rows; use Clay's enrichment waterfalls (Clearbit → Apollo → LinkedIn) to find companies matching each archetype's firmographic + technographic criteria automatically
- **Apollo.io:** Translate the ICP scoring rubric into Apollo saved searches with Boolean filters; use the trigger event signals as news/funding filters in Apollo Signals
- **HubSpot:** Create custom contact/company properties mapped to each scoring signal; build a HubSpot score property that auto-assigns Tier 1/2/3 as properties are populated via enrichment
- **Salesforce + Bombora:** Map intent topics from the archetype cards to Bombora topic clusters; create Einstein Account Scoring that weights intent surge + firmographic fit
- **LinkedIn Sales Navigator:** Build Account Lists per archetype using the firmographic criteria; set "Follow" alerts for the trigger events (leadership changes, funding alerts, headcount growth)
- **Zapier/Make:** Automate: (1) New funding announcement → create Clay row → enrich → score → if Tier 1, create HubSpot deal + notify SDR via Slack

## Troubleshooting

**Problem: Best customer sample is too small (fewer than 5 accounts) to extract reliable patterns.**
Solution: Expand the dataset to include "close losses" where the prospect was a good fit but didn't buy, and "expansion accounts" where customers significantly upsold. Patterns from losses reveal buying triggers just as much as wins. Alternatively, use publicly available data about your competitors' case study customers to supplement your own.

**Problem: The archetypes generated are too broad or overlap significantly.**
Solution: Add a sixth dimension to your customer data: "what was the specific pain incident that triggered the buying process?" This incident-based segmentation (e.g., "failed performance review cycle," "board asked for retention data," "key employee quit unexpectedly") creates sharper archetype differentiation than firmographic filters alone.

**Problem: Outreach hooks feel generic despite the personalization framework.**
Solution: Replace company-level signals with individual-level signals. Instead of "you raised Series B," try "I noticed you just posted for three HR Business Partners in the last 30 days while headcount is 300 — that's usually the point where performance management becomes a board-level conversation." Specificity at the individual-trigger level outperforms company-level triggers by 3-4x in reply rates.

## Version History
- v1.0: Initial creation (auto-generated)
