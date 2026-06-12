# AI-Powered B2B SaaS Content Refresh & Ranking Recovery Intelligence Engine

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** content-refresh, seo, ranking-recovery, content-decay, organic-pipeline, b2b-saas, e-e-a-t, content-audit

## Overview

This prompt runs a systematic content decay diagnosis and refresh planning workflow for B2B SaaS — identifying which existing blog posts, landing pages, and resource content are losing rankings and organic traffic, then generating AI-powered refresh briefs that recover and improve rankings without building new content from scratch. Use it when organic traffic has plateaued or declined despite a healthy publishing cadence, when a site has 50+ existing content assets and needs to extract more value from them, or when the content team has more to refresh than they have bandwidth to create new.

## Quick Copy-Paste Version

You are a senior B2B SaaS SEO strategist specializing in content performance recovery. Audit the following content inventory and produce a prioritized refresh plan to recover lost rankings and drive organic pipeline.

**Company Context:**
- Company: [Your Company], a [product description] for [ICP]
- Site: [domain.com]
- Blog/resource center URL: [/blog or /resources]
- Primary competitors: [Competitor 1], [Competitor 2], [Competitor 3]

**Content Inventory to Audit (paste your GSC data or list URLs):**
[Paste a list of 10–50 URLs with their current ranking positions, traffic trend (up/down/flat), and original publish date. Format: URL | Primary Keyword | Current Position | 6-Month Traffic Trend | Published Date]

**Deliverables — produce each section:**

1. **Decay Diagnosis** — Classify each piece as: Red Flag (significant ranking drop, immediate action needed), Yellow Flag (stagnating, refresh within 90 days), or Green (performing well, monitor only). For Red and Yellow pieces, identify the primary decay cause from: search intent drift, content thinness, competitor freshness advantage, E-E-A-T signal weakness, or internal linking gaps.

2. **Refresh Priority Stack** — Rank the top 10 pages to refresh first, scored by: current ranking position (closer to page 1 = higher ROI for refresh), monthly search volume of primary keyword, commercial intent strength, and estimated traffic recovery potential.

3. **Refresh Brief per Priority Page** — For each of the top 5 pages, produce a structured refresh brief containing: specific sections to add or expand, outdated facts/statistics to replace, competitor content gaps to close, new internal links to add, and target featured snippet or SERP feature to capture.

4. **E-E-A-T Upgrade Checklist** — For each priority page, list the specific E-E-A-T signals to strengthen: expert author attribution, first-person practitioner insights to add, external citation opportunities, and schema markup to implement.

5. **30-60-90 Day Recovery Roadmap** — Sequence the full refresh workload into: 30-day sprint (top 3 pages, maximum recovery potential), 60-day sprint (next 5 pages), 90-day completion (remaining Yellow flags). Include expected ranking improvement per sprint.

Format all output as structured tables with a one-paragraph executive summary: "Refreshing these [X] pages represents an estimated [Y]% traffic recovery opportunity mapped to approximately [Z] additional MQL opportunities per month."

## Advanced Customizable Version

ROLE: You are a principal B2B SaaS content strategist and SEO recovery specialist. You have diagnosed and recovered organic traffic for 50+ SaaS companies using a systematic content refresh methodology grounded in search intent alignment, E-E-A-T authority building, and competitive displacement analysis. You treat existing content as a depreciating asset that can be re-appreciated — not discarded and replaced. Your recommendations are always tied to pipeline logic, not traffic vanity.

CONTEXT:
Company Name: [Company Name]
Domain: [domain.com]
Product Description: [One sentence — what it does, core mechanism]
ICP Definition:
  - Primary Buyer: [Title, seniority level]
  - Economic Buyer: [Title if different]
  - Company Profile: [Employee count range, ARR range, industry verticals]
Average Contract Value (ACV): $[X]
Sales Cycle: [X months]
GTM Motion: [Inbound / Product-Led / Sales-Led / Hybrid]
Primary Competitors: [List 3–5 with domains]
Content Inventory Size: [Approximate number of blog posts + resource pages]
Current Monthly Organic Sessions: [X]
Peak Monthly Organic Sessions (historical): [X — when was peak?]
Primary Traffic Loss Period: [When did traffic start declining? Month/year]
Google Search Console Access: [Yes / No — if yes, attach 16-week performance export]
Top 10 Declining Pages (URLs + data): [List with: URL, primary target keyword, current avg. position, 6-month sessions change %]
Known Competitor Recent Activity: [Any competitors who published major content recently?]
Content Team Refresh Capacity: [X hours/week or X pages/month]
Pipeline Conversion Rate (organic): [X% organic session-to-MQL]

OBJECTIVE: Conduct an expert-level content decay audit and produce a pipeline-prioritized refresh program that maximizes ranking recovery per unit of content team effort. Every recommendation must be grounded in commercial logic — which refreshes will recover the most pipeline-generating traffic fastest.

FRAMEWORK — Execute each phase with expert depth:

**PHASE 1: CONTENT DECAY CLASSIFICATION**

Assess each submitted URL across five decay dimensions. Assign a severity score (1–5) for each dimension, then compute a Decay Risk Score (weighted average):

A. Search Intent Drift (Weight: 30%)
- Has Google's interpretation of the target keyword changed since the page was published?
- Does the current SERP show a different content format dominates (listicle vs. guide vs. landing page)?
- Is the page's structure misaligned with what currently ranks in positions 1–3?
- Severity 5 = Complete format mismatch; Severity 1 = Minor drift, structure still mostly aligned

B. Content Freshness Gap (Weight: 25%)
- Are there statistics, product data, pricing, or market facts that are now outdated (>18 months old)?
- Do competitor pages in top-3 positions have a more recent publish or update date prominently displayed?
- Does the content reference tools, integrations, or workflows that have been superseded?
- Severity 5 = Multiple outdated facts; entire narrative stale; Severity 1 = One or two data points to update

C. Competitive Depth Deficit (Weight: 25%)
- Do pages currently ranking above this URL cover significantly more subtopics, examples, or depth?
- Run a content gap analysis: identify 3–5 specific sections the ranking competitors include that this page lacks
- Is the word count materially lower than the top-3 ranking pages (>30% shorter)?
- Severity 5 = Competitors are comprehensive, this page is surface-level; Severity 1 = Minor gaps only

D. E-E-A-T Signal Weakness (Weight: 10%)
- Does the page lack byline attribution, expert credentials, or first-person practitioner perspective?
- Are there no external citations, studies, or data sources linked?
- Is there no schema markup (Article, FAQ, HowTo) implemented?
- For YMYL-adjacent topics (finance, compliance, security): does the author lack credentials?
- Severity 5 = Anonymous, uncited, no schema; Severity 1 = Strong signals with one minor gap

E. Internal Linking Isolation (Weight: 10%)
- Does this page receive fewer than 3 internal links from other site pages?
- Does it fail to link internally to related high-converting pages (demo, pricing, case studies)?
- Has it not been linked from any newer content published in the last 12 months?
- Severity 5 = Orphaned or near-orphaned; Severity 1 = Well-linked with recent link additions

**DECAY CLASSIFICATION OUTPUT:**
For each URL, produce:

| URL | Intent Drift | Freshness Gap | Depth Deficit | E-E-A-T | Internal Links | Decay Risk Score | Classification |
|-----|-------------|---------------|---------------|---------|----------------|-----------------|----------------|

Classification tiers:
- **CRITICAL** (Decay Score 4.0–5.0): Immediate refresh required — at risk of falling off page 1 or already on page 2+
- **HIGH** (Decay Score 3.0–3.9): Refresh within 30 days — meaningful traffic recovery available
- **MEDIUM** (Decay Score 2.0–2.9): Refresh within 60–90 days — stabilization and incremental improvement
- **LOW** (Decay Score 1.0–1.9): Monitor quarterly — minimal intervention needed

**PHASE 2: REFRESH ROI SCORING**

Score each CRITICAL and HIGH priority page on a Refresh ROI Index to determine sequencing:

Refresh ROI Score = 
  (Ranking Recovery Potential × 0.35) +     // 35%: How much traffic will come back if we reach position 3–5?
  (Commercial Intent Strength × 0.30) +      // 30%: Is recovered traffic pipeline-relevant?
  (Refresh Effort Estimate × 0.20) +         // 20%: Low effort refresh = higher ROI (inverse: low effort = high score)
  (Competitive Feasibility × 0.15)           // 15%: Can we realistically displace current position 1–3 holders?

For each component:
- Ranking Recovery Potential (1–10): Based on current position × monthly search volume of primary keyword
- Commercial Intent Strength (1–10): BOFU = 9–10, MOFU = 6–8, TOFU = 2–5 (refreshing BOFU pages first = faster pipeline ROI)
- Refresh Effort Estimate (1–10 inverse): Quick structural refresh = 9–10, full rewrite = 1–3
- Competitive Feasibility (1–10): Assess whether current top-3 pages are from high-authority domains or weaker competitors

Output: Ranked Refresh Priority Stack showing the top 15 pages ordered by Refresh ROI Score with recommended refresh type (Light Edit, Structural Refresh, Full Rewrite with Preserved URL) and estimated content hours.

**PHASE 3: REFRESH BRIEF GENERATION**

For each CRITICAL and HIGH priority page, produce a detailed Refresh Brief:

---
**REFRESH BRIEF: [Page Title]**

**URL:** [/page-url]
**Target Keyword:** [primary keyword]
**Current Position:** [X] | **Target Position:** [3–5]
**Refresh Type:** [Light Edit / Structural Refresh / Full Rewrite]
**Estimated Hours:** [X hours]
**Priority:** [CRITICAL / HIGH]

**Search Intent Re-Alignment:**
[Describe the current page's format vs. the format Google is currently rewarding for this keyword. E.g., "Currently structured as a how-to guide. Top 3 results are all comparison lists. Restructure as a ranked comparison with an intro section."]

**Outdated Elements to Replace:**
- Statistic: "[Current stat from page]" → Replace with "[More recent data source/approach]"
- Reference: "[Outdated tool/product/workflow]" → Update to "[Current equivalent]"
- Publish date: Update to current date AND add "Last Updated: [Month Year]" prominently

**Competitive Gap Sections to Add:**
1. [Section title]: [Competitor X] covers this with [brief description] — add a [X00-word] section covering [specific angle]
2. [Section title]: Missing from all competitor pages but directly relevant to buyer JTBD — add to establish differentiation
3. [Section title]: [Competitor Y] ranks a featured snippet with [format] — create a [definition box / numbered list / comparison table] to compete for this snippet

**E-E-A-T Upgrade Actions:**
- [ ] Add expert byline: "[Author Name], [Title/Credential], [Company Name] — [X years experience in this domain]"
- [ ] Add practitioner insight callout box: "[First-person insight or case stat from internal SME]"
- [ ] Add/update citations: Link to [specific studies, regulatory guidance, or industry reports]
- [ ] Implement [Article / FAQ / HowTo] schema markup
- [ ] Add "Key Takeaways" section at top summarizing expert-validated recommendations

**Internal Linking Updates:**
- Add inbound links FROM: [List 3 existing pages that should link to this page with suggested anchor text]
- Add outbound links TO: [List 2–3 related pages this content should link to, including at least one conversion-intent page: demo, pricing, or case study]
- Update CTA: Replace [current CTA] with [stronger conversion CTA aligned to BOFU intent]

**SERP Feature Opportunity:**
[Identify the specific featured snippet, People Also Ask, or SERP feature to target and the exact format required to compete for it]

**Freshness Signal Tactics:**
- Add "Last Updated" date in visible header
- Update the meta description to include current year
- Add a "What's Changed in [Year]" section at top if content is >2 years old
- Reference recency in intro: "In [Year], [emerging trend] has changed how [ICP job title] approaches [topic]"

**Expected Outcome:** Position [current] → Position [target] within [X] weeks. Estimated traffic recovery: [X] additional monthly sessions. Pipeline impact at [X]% conversion rate: [Y] incremental MQLs/month.
---

**PHASE 4: E-E-A-T AUTHORITY BUILDING PROGRAM**

Beyond page-level tactics, produce a site-wide E-E-A-T uplift plan:

A. Author Authority Architecture
- Recommend an author profile system: [Name, credential, LinkedIn, X posts, schema markup structure]
- Identify which content categories require the highest expertise signals (compliance, security, financial ROI claims)
- Produce author bio template that signals expertise without feeling generic

B. Citation & Data Strategy
- Identify the top 10 authoritative external sources to cite consistently across priority content (industry reports, regulatory bodies, research institutions)
- Flag pages making unsubstantiated claims ("studies show," "research indicates") and recommend specific citations
- Produce a "data freshness calendar" — which statistics in your content expire annually vs. quarterly

C. Schema Markup Implementation Priority
- For each refresh priority page, specify the exact schema type (Article, FAQ, HowTo, Product, Review) and the 3 most important properties to implement
- Identify FAQ opportunities: queries in People Also Ask where no current page has FAQ schema implemented

D. Trust Signal Enrichment
- Identify where to add: customer logos, integration badges, security certifications, analyst citations, award logos
- These signals improve conversion rate of recovered traffic — critical for BOFU refresh pages

**PHASE 5: INTERNAL LINKING ARCHITECTURE REBUILD**

A structural internal linking audit for all refreshed content:

A. Link Equity Flow Map
- Identify your 5 highest-authority pages (most external backlinks) — these are your link equity sources
- Map which priority refresh pages currently receive zero links from these high-authority sources
- Output: Link injection plan — which links to add to which source pages to pass equity to priority targets

B. Pillar-Cluster Linking Structure
- Identify 3–5 "pillar" pages (broad, high-volume topic pages) that should anchor clusters of related content
- For each pillar, identify 5–10 supporting cluster pages that should link back to the pillar
- Flag any cluster pages that compete with (cannibalize) their own pillar — recommend consolidation vs. differentiation

C. Conversion Path Optimization
- Trace the user journey from each refresh priority page to the nearest conversion point
- For pages more than 2 clicks from a demo or pricing CTA: redesign the internal linking to shorten conversion path
- Add in-content CTAs at the 60% content scroll point for BOFU and MOFU pages

**PHASE 6: RECOVERY MEASUREMENT FRAMEWORK**

Establish a tracking system for refresh ROI measurement:

A. Baseline Snapshots (capture before each refresh)
- Current average position, impressions, clicks (Google Search Console — trailing 28 days)
- Sessions from organic search (Google Analytics — trailing 28 days)
- Conversion events attributed to page (form fills, demo requests, content downloads)

B. Recovery Milestones to Track (post-refresh)
- Week 2: Googlebot recrawl confirmed (check GSC Coverage report)
- Week 4: First ranking movement detected (±3 positions)
- Week 8: Stabilized new ranking position established
- Week 12: Full traffic recovery measured and compared to baseline
- Week 16: Pipeline contribution measured in CRM (MQLs and opportunities sourced from refreshed pages)

C. Refresh ROI Dashboard Metrics
- Sessions Recovered: (Post-refresh monthly sessions) − (Pre-refresh monthly sessions)
- MQLs Recovered: Sessions Recovered × [organic conversion rate]
- Pipeline Recovered: MQLs Recovered × [pipeline conversion rate] × [ACV]
- Refresh Investment: [Hours spent × blended content cost per hour]
- Content Refresh ROI: Pipeline Recovered ÷ Refresh Investment × 100

D. Decision Rules for Full Rewrites
- If ranking hasn't moved at 8 weeks post-refresh: escalate to full rewrite with new URL slug redirect (maintain link equity via 301 redirect)
- If traffic recovered but conversion didn't: CTA and offer audit required — SEO problem is solved but conversion problem remains
- If page is position 15–25 and didn't recover after refresh: evaluate external link building as the bottleneck

**OUTPUT FORMAT:**

Section 1: Executive Summary (5–6 sentences: total traffic opportunity, critical pages requiring immediate action, projected pipeline recovery at full execution, estimated content team hours required)
Section 2: Full Content Decay Classification Table (all submitted URLs)
Section 3: Refresh Priority Stack with ROI Scores (top 15 ranked by Refresh ROI Index)
Section 4: Detailed Refresh Briefs (top 5 CRITICAL/HIGH pages)
Section 5: E-E-A-T Authority Building Program
Section 6: Internal Linking Architecture Rebuild Plan
Section 7: Recovery Measurement Dashboard Setup
Section 8: 90-Day Execution Calendar (weekly tasks for content team)

## Example Input/Output

**Input Example:**

Company Name: Signalio
Domain: signalio.com
Product Description: Revenue intelligence platform that automatically captures buyer signals from email, calendar, and web activity to surface deal risk and forecast pipeline accuracy for B2B sales teams.
ICP:
  - Primary Buyer: VP of Sales, Revenue Operations Director
  - Economic Buyer: CRO, CFO
  - Company Profile: 200–2,000 employees, Series B–D SaaS, technology and financial services verticals
ACV: $72,000
Sales Cycle: 3–5 months
Competitors: Gong, Clari, Chorus, Salesloft
Current Monthly Organic Sessions: 8,400 (down from 14,200 peak 11 months ago)
Content Team Capacity: 3 refreshes/month
Top 5 Declining Pages:
  1. /blog/revenue-intelligence-tools | "revenue intelligence tools" | Position 14 | −62% sessions | Published Jan 2023
  2. /blog/sales-forecasting-accuracy | "improve sales forecast accuracy" | Position 19 | −48% sessions | Published Mar 2022
  3. /blog/pipeline-management-best-practices | "pipeline management best practices" | Position 11 | −31% sessions | Published Aug 2023
  4. /resources/sales-call-analysis-guide | "sales call analysis" | Position 22 | −55% sessions | Published Nov 2022
  5. /blog/gong-alternative | "Gong alternative" | Position 8 | −18% sessions | Published Jul 2023

**Output Example (abbreviated):**

**Executive Summary:**
Signalio has lost an estimated 5,800 monthly organic sessions over the past 11 months — approximately $312,000 in annualized pipeline at current conversion benchmarks ($72K ACV, 2.1% organic-to-MQL, 24% close rate). The root cause is concentrated in three decay patterns: search intent drift on comparison pages (Google is now rewarding table-based comparison formats over narrative reviews), content freshness gaps on posts citing 2022 data in a fast-moving AI-sales-tech category, and competitive depth deficits against Gong and Clari who have tripled their content investment since Q1 2024. Recovering the top 5 priority pages represents a recoverable 3,800 sessions/month opportunity. At current team capacity of 3 refreshes/month, full recovery is achievable in 60 days — delivering an estimated 80 additional MQLs/month and $690,000 in net new quarterly pipeline.

**Top 3 Refresh Priority Briefs (abbreviated):**

---
**REFRESH BRIEF: Revenue Intelligence Tools (Comparison Page)**

**URL:** /blog/revenue-intelligence-tools
**Target Keyword:** "revenue intelligence tools"
**Current Position:** 14 | **Target Position:** 3–5
**Refresh Type:** Structural Refresh
**Estimated Hours:** 6 hours
**Priority:** CRITICAL

**Search Intent Re-Alignment:**
Page is currently formatted as a narrative review (long paragraphs, no comparison table). Current positions 1–3 are all structured as numbered listicles with a comparison table in the first scroll. Restructure the intro + add a 10-tool comparison table above the fold. Keep narrative depth in body.

**Outdated Elements to Replace:**
- "According to 2022 Salesforce State of Sales..." → Replace with 2025 Salesforce State of Sales (or CSO Insights equivalent)
- Gong and Clari pricing references → All pricing changed Q3 2023; mark as "pricing varies — contact vendor" or link to verified current pricing
- Update pub date and add "Last Updated: June 2026" banner

**Competitive Gap Sections to Add:**
1. "How to Evaluate Revenue Intelligence Tools: A Buyer's Checklist" — Gong's alternative page includes a 12-point evaluation framework; add a similar checklist (positions us as authoritative guide, not just a vendor)
2. "Revenue Intelligence vs. Conversation Intelligence: Key Differences" — 4 of top 5 competitors lack this distinction; our buyers consistently confuse these categories (sourced from Gong call review data)
3. Add an interactive "Which revenue intelligence tool fits your team?" decision tree — no competitor has this; targets featured snippet for "best revenue intelligence tool for [team size]"

**E-E-A-T Upgrade Actions:**
- [ ] Add byline: "Written by [RevOps Director Name], 9 years in enterprise sales operations"
- [ ] Add customer proof callout: "Signalio customers improve forecast accuracy by 34% in 90 days — [Customer Name], VP Sales, [Company]"
- [ ] Cite: Forrester Wave: Revenue Intelligence Platforms, 2025
- [ ] Implement Article + FAQ schema (target FAQ schema for 4 People Also Ask queries identified in SERP)

**Expected Outcome:** Position 14 → Position 4–6 within 8 weeks. Estimated recovery: +680 monthly sessions. Pipeline impact: +14 MQLs/month.
---

## Success Metrics

- **Ranking Recovery Rate:** 70%+ of CRITICAL pages recover to target position within 12 weeks of refresh
- **Traffic Recovery:** Total organic sessions return to within 85% of peak within 90 days of completing all CRITICAL/HIGH refreshes
- **MQL Recovery:** Organic-sourced MQLs from refreshed pages increase by 25%+ within 60 days of refresh publication
- **Content Refresh ROI:** Each refresh achieves positive pipeline ROI (pipeline attributed to refreshed page exceeds content team cost) within 90 days
- **E-E-A-T Progress:** Average Google Search Console "impressions" for refreshed pages increases 40%+ within 30 days of refresh (signal that Google is re-crawling and re-indexing with higher confidence)
- **SERP Feature Captures:** At least 2 of the top 5 refreshed pages capture a featured snippet or People Also Ask inclusion within 60 days
- **Conversion Rate on Refreshed Pages:** Post-refresh, BOFU and MOFU pages show ≥15% improvement in organic visitor-to-conversion rate

## Related Prompts

- [AI-Powered B2B SaaS Keyword Research & Buyer Intent Mapping Intelligence Engine](./AI-Powered-B2B-SaaS-Keyword-Research-&-Buyer-Intent-Mapping-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Technical SEO Audit & Organic Performance Intelligence Engine](./AI-Powered-B2B-SaaS-Technical-SEO-Audit-&-Organic-Performance-Intelligence-Engine.md)
- [AI-Powered B2B SaaS SEO Demand Generation Program Architecture & Organic Pipeline Revenue Intelligence Engine](./AI-Powered-B2B-SaaS-SEO-Demand-Generation-Program-Architecture-&-Organic-Pipeline-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Organic Search Performance Analytics & Content-to-Pipeline Revenue Attribution Intelligence Engine](../../05_Analytics-&-Performance/SEO-Organic-Performance-Analytics/AI-Powered-B2B-SaaS-Organic-Search-Performance-Analytics-&-Content-to-Pipeline-Revenue-Attribution-Intelligence-Engine.md)

## Integration Tips

- **Google Search Console:** Export your "Pages" performance report (last 16 weeks, filtered to organic search) and paste the data directly into the Advanced Version's context block. GSC data gives you real click and impression trends that make the decay classification far more precise than estimates.
- **Ahrefs / SEMrush:** Use the "Content Gap" tool on competitor domains to populate Phase 3's competitive gap sections. Export competitor top pages sorted by organic traffic and paste as context — the AI will identify which competitor content you're being displaced by.
- **Screaming Frog:** Run a crawl to identify internal link counts per page. Export the "Inbound Links" column and paste it into the prompt to power Phase 5's internal linking architecture audit with real data.
- **Clearscope / Surfer SEO / Frase:** After generating the Refresh Brief, paste the brief into Clearscope or Surfer to create a content optimization score target. Use the AI-generated section recommendations as your content brief, then use Clearscope to ensure keyword coverage meets threshold.
- **HubSpot / Salesforce:** Tag refreshed pages with UTM parameters or page-level attribution in your CRM. Create a "Content Refresh" campaign in HubSpot to track MQL and opportunity attribution from each refreshed URL — this builds the data to prove refresh ROI to leadership.
- **Notion / Confluence:** Paste each Refresh Brief as a Notion document and assign it directly to a content team member. Use the "Estimated Hours" field to populate sprint planning. Create a Notion database tracking all refreshes with Status (Briefed / In Progress / Published / Measuring) and pipeline recovery metrics.
- **Google Analytics 4:** Create a GA4 custom segment for "Refreshed Content" — include all updated URLs. Compare organic traffic and conversion rates before and after refresh date. Build a GA4 Exploration report to see the recovery curve week-over-week.
- **Zapier:** Automate refresh triggers — set a GSC alert in Zapier: when a priority page drops below position 12, create a Notion task for a content refresh sprint and notify the SEO lead via Slack.

## Troubleshooting

**Problem: The AI generates generic refresh recommendations ("add more statistics," "update the date") without specificity about which sections to actually change or what competitive gaps to close.**
Solution: Paste 3–5 competitor URLs into the prompt context alongside the target URL, explicitly instructing the AI to "compare the structure, depth, and subheadings of these competitor pages against the target URL." Without competitor context, the AI can't identify specific gaps. Also provide the actual current content from your page (paste the full text) — not just the URL, which the AI can't browse.

**Problem: Rankings don't recover after 8 weeks despite implementing all refresh recommendations.**
Solution: The bottleneck is likely external link authority, not content quality. Check your Ahrefs or SEMrush link data: if the top-3 ranking pages have 3x or more referring domains than your refreshed page, content quality alone won't win — you need a link building campaign targeting this URL specifically. Add to the prompt: "Given that this page has [X] referring domains and competitors have [Y], what link building tactics will accelerate ranking recovery?"

**Problem: The decay classification identifies too many CRITICAL pages — more than the team can refresh in 90 days.**
Solution: Apply a commercial triage filter on top of the decay score. Add to the prompt: "Among all CRITICAL pages, further filter to only those where the primary keyword has BOFU or MOFU commercial intent AND where current ranking position is 8–20 (already close enough to page 1 to benefit from a refresh)." This focuses refresh effort on the highest-ROI subset and avoids burning resources on pages that are position 30+ where a refresh alone won't be sufficient.

## Version History
- v1.0: Initial creation (auto-generated)
