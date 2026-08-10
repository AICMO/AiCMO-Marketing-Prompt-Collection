# AI-Powered B2B SaaS Content Decay Detection & Evergreen Refresh Prioritization Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** content analytics, SEO, content operations, revenue attribution, content ROI

## Overview

Identifies which content assets in your library are experiencing measurable traffic and conversion decay, scores them against a multi-factor refresh ROI model, and outputs a prioritized refresh queue with specific optimization instructions — fully automated for AI agent execution against Google Search Console, GA4, and your CMS.

## Quick Copy-Paste Version

You are a senior content analytics strategist. Analyze the following content performance data and produce a prioritized content refresh queue.

CONTENT PERFORMANCE DATA:
[Paste a CSV or table with columns: URL, Page Title, Monthly Organic Sessions (current), Monthly Organic Sessions (12 months ago), Avg Position (current), Avg Position (12 months ago), Pipeline-Influenced Opportunities (last 90 days), Backlinks, Word Count, Last Updated Date]

TASK:
1. Calculate the Traffic Decay Score for each URL:
   - Decay % = ((Sessions 12mo ago - Sessions current) / Sessions 12mo ago) × 100
   - Flag any URL with >25% traffic decay as "Decaying"
   - Flag any URL with >50% decay as "Critical Decay"

2. Calculate the Refresh ROI Score (0-100) using:
   - Historical pipeline influence (40% weight) — URLs that drove opportunities before are worth more to refresh
   - Current backlink equity (25% weight) — high-backlink pages recapture value faster
   - Keyword position loss (20% weight) — positions that slipped from top-3 to 4-10 are recovery candidates
   - Content age penalty (15% weight) — content >18 months old that is decaying scores higher

3. Apply the Triage Matrix:
   - REFRESH NOW (score 70-100 + decaying): Full rewrite with new data, examples, and updated sections
   - REFRESH SOON (score 40-69 + decaying): Targeted updates — add new sections, update statistics
   - MONITOR (score <40 + decaying): Low ROI, consider consolidation or canonical redirect
   - PROTECT (not decaying, score >60): Actively maintain and update annually

4. For each REFRESH NOW and REFRESH SOON URL, provide:
   - The specific sections likely causing decay (outdated stats, missing topics, thin content)
   - 3 new H2 sections to add based on current search intent
   - The primary keyword to optimize for
   - Estimated traffic recovery range (conservative/optimistic)
   - Time investment required (hours)

Output format:
- Executive summary table with triage categories and counts
- Ranked refresh queue (highest ROI first) with action cards
- 30/60/90-day refresh roadmap based on effort scoring
- Quick wins list: URLs fixable in <2 hours with high ROI

## Advanced Customizable Version

ROLE: You are a Content Intelligence Analyst specializing in B2B SaaS content performance optimization. You combine SEO expertise, conversion analytics, and content operations to maximize revenue from existing content libraries.

COMPANY CONTEXT:
- Company: [Company Name]
- Industry: [Industry vertical]
- Primary ICP: [ICP description — e.g., "VP Engineering at 200-2000 employee B2B SaaS companies"]
- Content library size: [Total published URLs]
- Revenue model: [ARR range, ACV, deal cycle length]
- Content production capacity: [Hours/week available for refresh work]
- CMS: [WordPress / HubSpot / Contentful / other]
- Primary analytics stack: [GA4 / Mixpanel / etc.] + [Search Console / Ahrefs / Semrush]

PERFORMANCE DATA INPUT:
Provide one or more of these data sources:
A) [Paste GA4 export: URL, sessions, goal completions, avg engagement time — current period vs. YoY]
B) [Paste Search Console export: URL, clicks, impressions, avg position, CTR — current 90 days vs. prior 90 days]
C) [Paste CRM attribution report: URL, influenced pipeline $, influenced deals closed, last 6 months]
D) [Paste CMS content inventory: URL, publish date, last modified date, word count, category/topic cluster]
E) [Paste backlink data: URL, referring domains, DR/authority]

ANALYSIS FRAMEWORK — EXECUTE IN SEQUENCE:

### Phase 1: Content Health Audit

1.1 TRAFFIC DECAY ANALYSIS (using data sources A + B):
Apply the Content Performance Half-Life Model:
- Stage 1 (Healthy): <10% YoY traffic decline, position stable within ±3
- Stage 2 (Early Decay): 10-25% decline OR position slipped 3-7 places
- Stage 3 (Active Decay): 25-50% decline OR position slipped >7 places from historical best
- Stage 4 (Terminal Decay): >50% decline AND position >20 OR <10 clicks/month
- Stage 5 (Zombie): <50 sessions/month, never ranked, no backlinks — consolidation candidate

For each URL, assign decay stage and calculate:
- Traffic delta (absolute sessions lost per month)
- Revenue-equivalent traffic loss (use benchmark: 1 organic session = $[X] in influenced pipeline — calculate from data source C)
- Position recovery probability score (0-10): pages in positions 11-20 score 8-10 (high recoverability), positions 1-10 score 4-7 (protect/expand), positions >20 score 1-3 (requires major investment)

1.2 REVENUE CONTRIBUTION MAPPING (using data source C):
For each URL, calculate:
- Pipeline influence rate = Influenced opportunities / Total sessions × 1000 (opportunities per 1K sessions)
- Revenue attribution tier:
  * Tier 1 (Gold): >2 opportunities per 1K sessions OR >$50K influenced ARR
  * Tier 2 (Silver): 0.5-2 opportunities per 1K sessions OR $10-50K influenced ARR
  * Tier 3 (Bronze): 0.1-0.5 per 1K sessions OR $1-10K influenced ARR
  * Tier 4 (Dark): No CRM attribution but high engagement (>3 min avg session) — potential dark funnel content
  * Tier 5 (Unproven): <0.1 per 1K sessions, low engagement — lowest refresh priority

1.3 CONTENT QUALITY DECAY SIGNALS (using data sources A + D):
Flag each URL for specific quality issues based on behavioral signals:
- HIGH BOUNCE + POSITION DROP: Content no longer satisfies search intent — requires intent realignment
- LOW ENGAGEMENT TIME (<1 min) + TRAFFIC DECLINE: Thin content or outdated information — requires depth expansion
- HIGH ENGAGEMENT + POSITION DROP: Good content poorly optimized — requires on-page SEO update
- GOOD POSITION + LOW CONVERSION: Missing conversion elements — CTA, lead magnet, or intent mismatch
- TRAFFIC STABLE + ZERO CRM ATTRIBUTION: Dark funnel content — requires attribution tracking setup

### Phase 2: Refresh ROI Scoring

For each URL, calculate a Refresh ROI Score (0-100 scale):

SCORE = (Revenue Potential × 0.35) + (Recovery Probability × 0.30) + (Effort Efficiency × 0.20) + (Strategic Alignment × 0.15)

Revenue Potential (0-10):
- Gold tier content with active decay: 10
- Silver tier content with active decay: 7
- Bronze tier content with active decay: 5
- Dark funnel content with decay: 6 (attribution upside)
- Unproven content: 2

Recovery Probability (0-10):
- Position 11-20, Decay Stage 2-3, DA/backlinks ≥ site average: 10
- Position 4-10, Decay Stage 2, strong backlinks: 8
- Position 21-50, Decay Stage 2-3: 6
- Position >50, Decay Stage 4: 3
- Terminal/Zombie content: 1

Effort Efficiency (0-10):
- <2 hours estimated refresh, high recovery probability: 10
- 2-4 hours, medium-high recovery: 7
- 4-8 hours, medium recovery: 5
- >8 hours (major rewrite): 3
Effort estimation:
  * Statistics update only: 1 hour
  * Add 2-3 new sections: 2-3 hours
  * Full structural rewrite: 6-8 hours
  * New examples + case studies: 3-4 hours

Strategic Alignment (0-10):
- Primary ICP topic cluster, product-adjacent: 10
- Secondary ICP cluster: 7
- Adjacent topic, moderate relevance: 5
- Tangential/low-relevance topic: 2

### Phase 3: Competitive Context Analysis

For each REFRESH NOW candidate, analyze the competitive gap:
- Identify the top 3 ranking URLs for the primary keyword
- List specific content elements they have that your content lacks:
  * Data sources (original research, surveys, benchmarks)
  * Content format advantages (comparison tables, calculators, templates)
  * Depth advantages (additional subtopics covered)
  * Freshness signals (recent statistics, 2024/2025 data)
  * E-E-A-T signals (author credentials, expert quotes, case studies)
- Calculate the "Content Gap Score" (how much investment closes the competitive gap)

### Phase 4: Refresh Roadmap Generation

4.1 TRIAGE CATEGORIES:
- REFRESH NOW (ROI Score ≥ 70): Maximum business impact, schedule within 30 days
- REFRESH SOON (ROI Score 50-69): High value, schedule within 60 days
- REFRESH NEXT QUARTER (ROI Score 30-49): Moderate value, plan for Q+1
- CONSOLIDATE (Stage 4-5 decay, ROI Score <30): Merge into stronger URL or 301 redirect
- RETIRE (Zombie content, no backlinks, no revenue attribution): Noindex or delete

4.2 REFRESH BRIEF (for each REFRESH NOW and REFRESH SOON URL):
Produce a structured brief including:

CONTENT: [URL]
CURRENT STATE: [Decay Stage, Revenue Tier, ROI Score]
TARGET KEYWORD: [Primary keyword + monthly search volume estimate]
CURRENT POSITION: [X] → TARGET POSITION: [Y within 90 days]

MANDATORY UPDATES:
□ Replace statistics older than 18 months with current data
□ Add [X] new H2 sections covering: [list specific topics]
□ Update the [section name] to reflect [specific change needed]
□ Add [specific content element: table/calculator/template/case study]
□ Optimize meta title/description for: [new title recommendation]
□ Add internal links to: [list 3-5 specific URLs from your content library]

CONVERSION OPTIMIZATION:
□ Add lead magnet: [specific recommendation matching buyer stage]
□ Update CTA placement: [specific instruction]
□ Add social proof: [customer quote or case study recommendation]

EFFORT: [X hours] | EXPECTED TRAFFIC RECOVERY: [conservative range] sessions/month within 90 days
PIPELINE IMPACT ESTIMATE: [$X influenced ARR] based on historical pipeline influence rate

4.3 SPRINT ROADMAP:
Week 1-2: Quick wins (all URLs requiring <2 hours, ROI Score ≥ 60)
Week 3-4: High-ROI refreshes (REFRESH NOW, estimated 4-8 hours each)
Month 2: Tier-2 refreshes + consolidation of CONSOLIDATE candidates
Month 3: REFRESH NEXT QUARTER items + performance review of Month 1 refreshes

OUTPUT REQUIREMENTS:
1. Executive dashboard: Total URLs audited, decay distribution by stage, total estimated monthly traffic/revenue at risk
2. Prioritized refresh queue: Full ranked list with triage category, ROI score, and brief summary
3. Top 10 action cards: Detailed refresh briefs for highest-ROI URLs
4. Quick wins list: All URLs with ROI Score ≥ 60 and effort ≤ 2 hours
5. Consolidation recommendations: URLs to merge with target consolidation URLs
6. 90-day performance forecast: Expected aggregate traffic and pipeline recovery
7. Monthly refresh cadence template: Recurring schedule for content health maintenance

FORMATTING: Produce output in structured markdown with tables for the dashboard and queue, and detailed action cards for the top 10. Include a section header for each output component.

## Example Input/Output

**Company:** Northgate HR — HR technology platform for mid-market companies (500-5,000 employees), $1.2M ACV, 6-month deal cycle.

**Input snapshot (10 URLs from a 340-URL content library):**

| URL | Current Sessions | 12mo Sessions | Cur. Position | 12mo Position | Influenced Opps | Backlinks | Last Updated |
|-----|-----------------|---------------|---------------|----------------|-----------------|-----------|--------------|
| /blog/employee-onboarding-checklist | 4,200 | 9,800 | 14 | 4 | 11 | 47 | 18 months ago |
| /blog/hr-software-comparison | 1,100 | 1,050 | 7 | 8 | 8 | 31 | 8 months ago |
| /blog/remote-work-policy-template | 680 | 3,400 | 22 | 9 | 2 | 22 | 24 months ago |
| /blog/performance-review-software | 2,300 | 2,100 | 5 | 6 | 14 | 18 | 4 months ago |
| /resources/employee-engagement-guide | 290 | 1,800 | 31 | 11 | 1 | 8 | 30 months ago |
| /blog/hris-roi-calculator | 3,800 | 3,200 | 3 | 3 | 22 | 29 | 6 months ago |

**Output (abbreviated):**

**EXECUTIVE DASHBOARD:**
- URLs audited: 340 total (10 shown)
- Monthly traffic at risk: ~18,000 sessions/month (3 critical decay URLs)
- Revenue-equivalent at risk: ~$2.1M influenced ARR annually (at Northgate's $117/session pipeline influence rate)
- Quick win count: 4 URLs (<2 hours, ROI Score ≥ 60)

**TOP REFRESH PRIORITY:**

**#1: /blog/employee-onboarding-checklist**
- Decay Stage: 4 (Active Decay — 57% traffic loss, position crashed from 4→14)
- Revenue Tier: Gold (11 influenced opportunities in decay period — was likely 25+ at peak traffic)
- ROI Score: 94/100
- Root Cause: Content references 2022 labor statistics; missing AI-assisted onboarding section (top 3 competitors all have it); no structured checklist/download element
- Mandatory updates:
  * Replace all 2022 workforce statistics with 2025 data (SHRM, Gallup latest)
  * Add H2: "AI-Assisted Employee Onboarding: What's Changed in 2025"
  * Add H2: "30-60-90 Day Onboarding Plan Template" (downloadable)
  * Add H2: "Onboarding Software Comparison: What to Look for in 2025"
  * Optimize meta title: "Employee Onboarding Checklist 2025: Complete Guide + Free Template"
- Effort: 5 hours | Traffic Recovery: 5,000-7,500 sessions/month within 90 days
- Pipeline Impact: $585K-$877K influenced ARR recovered annually

**#2: /blog/remote-work-policy-template**
- Decay Stage: 3 (80% traffic loss, position 9→22)
- ROI Score: 78/100
- Root Cause: "Remote work policy" intent shifted post-2024 to hybrid/AI-work-from-anywhere scenarios; template predates AI tool usage policies
- Mandatory updates:
  * Rename to "Hybrid Work Policy Template 2025"
  * Add: AI tool usage policy section (ChatGPT, Copilot, etc.)
  * Add: "Right-to-disconnect" compliance section (EU/California law updates)
  * Downloadable Word/PDF template gated behind email capture
- Effort: 3 hours | Traffic Recovery: 1,800-2,600 sessions/month

**CONSOLIDATION CANDIDATES:**
- /resources/employee-engagement-guide → 301 redirect to stronger /blog/employee-engagement-software-guide (which ranks position 4) — zero standalone recovery potential

## Success Metrics

**Refresh execution quality:**
- Each completed refresh achieves position improvement within 60 days (target: return to within 3 positions of historical best)
- Traffic recovery rate: ≥40% of lost sessions recovered within 90 days for REFRESH NOW items
- CTA/lead magnet additions increase content conversion rate by ≥0.5 percentage points

**Program-level ROI:**
- Influenced pipeline recovered per hour of refresh investment (benchmark: ≥$50K ARR per 8-hour refresh)
- Cost of content refresh vs. cost of new content producing equivalent traffic (target: refresh should cost <30% of new content creation for equivalent traffic)
- Month-over-month reduction in content in Decay Stage 3-4

**Analytics hygiene:**
- 100% of refreshed URLs have GA4 goal completion tracking verified
- 100% of REFRESH NOW URLs have CRM influence attribution confirmed via UTM or reverse-IP

## Related Prompts

- [Content Marketing Performance Analytics & Pipeline Revenue Attribution](./AI-Powered-B2B-SaaS-Content-Marketing-Performance-Analytics-&-Pipeline-Revenue-Attribution-Intelligence-Engine.md) — upstream analytics for establishing your baseline pipeline influence rates
- [AI Search GEO Content Performance Analytics](./AI-Powered-B2B-SaaS-AI-Search-GEO-Content-Performance-Analytics-&-Generative-Engine-Revenue-Attribution-Intelligence-Engine.md) — layer in AI search visibility decay alongside traditional SEO decay
- [Revenue-Weighted Content Portfolio Audit & Prioritization](../../03_Content-&-Creative/Content-Strategy-&-Calendar/AI-Powered-B2B-SaaS-Revenue-Weighted-Content-Portfolio-Audit-&-Prioritization-Intelligence-Engine.md) — strategic-level portfolio decisions that inform your refresh budget allocation
- [Autonomous Content Performance Optimization Loop](../../03_Content-&-Creative/Content-Strategy-&-Calendar/AI-Powered-B2B-SaaS-Autonomous-Content-Performance-Optimization-Loop-&-Perpetual-Revenue-Content-Intelligence-Engine.md) — automate the recurring monitoring cycle once your refresh program is running

## Integration Tips

**Google Search Console + GA4 (core data pipeline):**
- Export Search Console: Performance → Pages → Last 12 months vs. previous 12 months, filter by Organic Search. Download as CSV.
- Export GA4: Explorations → Path/Funnel with URL dimension, sessions, goal completions, engagement time, 13-month range for YoY.
- Combine with VLOOKUP or a Python/Google Sheets script on URL as key. Feed merged CSV directly into the prompt.

**HubSpot (CRM attribution):**
- Reports → Attribution → Contact Create Attribution → filter by "Original Source = Organic Search" + "First Converting Asset" → export URL + associated deal value
- For influenced pipeline: Deals → filter by "Associated Content" → group by page URL → sum deal amount

**Ahrefs/Semrush (backlink + competitive data):**
- Ahrefs Site Explorer → Top Pages → export with referring domains count
- For competitive gap: Ahrefs Content Gap tool on your REFRESH NOW URLs to identify missing subtopics

**Contentful/WordPress/HubSpot CMS:**
- Export full content inventory with publish date, last modified, word count, and category via API or plugin (WP All Export, HubSpot Content API)
- After refresh: trigger automatic republish date update via webhook to keep "last modified" schema markup current

**Zapier/Make automation:**
- Monthly trigger: GSC API → Google Sheets → run prompt → output refresh queue to Asana/Linear as tasks
- Post-refresh trigger: when CMS article is published, log URL + date to a "refreshed content" sheet to track recovery performance

## Troubleshooting

**"My content analytics don't show a clear revenue link — no pipeline attribution data."**
Use a proxy attribution method: (1) Set up GA4 custom events for high-intent actions (downloaded guide, viewed pricing after reading blog). (2) Use URL parameters on all content CTAs and trace them in HubSpot/Salesforce via first-touch or last-touch. (3) For existing content, use reverse-IP tools (Clearbit, 6sense) to retroactively identify companies that consumed content and match to open deals. Even a 60-day retroactive window often reveals significant dark funnel influence.

**"My highest-traffic content isn't decaying but my organic leads have dropped — which content do I refresh?"**
Traffic stability masking conversion decay is common. Run a separate analysis: filter for URLs where sessions are stable (±10%) but form submissions or CTA clicks have dropped >20% YoY. These URLs have intent drift — searchers are arriving but the content no longer satisfies commercial intent. Refresh intervention: add or update bottom-funnel sections (pricing comparisons, vendor evaluation content, ROI calculators) rather than informational updates.

**"The content refresh queue has 150+ URLs — how do I staff this without overwhelming my team?"**
Apply the 80/20 filter immediately: sort by (Traffic at Risk × Revenue Tier Weight) and take the top 20% of URLs — these typically represent 80% of your recoverable pipeline value. Outsource statistical updates and structural rewrites for Tier 3-4 Bronze content to freelancers using the refresh brief format above. Reserve internal SME time for Gold/Silver tier refreshes that require deep product knowledge or customer insights.

## Version History
- v1.0: Initial creation (auto-generated)
