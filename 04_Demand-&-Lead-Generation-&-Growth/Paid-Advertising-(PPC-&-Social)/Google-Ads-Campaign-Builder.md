# Google Ads Campaign Builder - Full-Funnel PPC Campaign Architecture

**Difficulty:** Intermediate | **Time:** 20 min | **Tags:** google-ads, ppc, b2b, saas, paid-search, demand-gen, conversion

## Overview
Generates a complete, launch-ready Google Ads campaign structure — including campaign type selection, ad group architecture, keyword strategy, match types, negative keywords, ad copy variants, bidding strategy, and conversion tracking plan. Use it when launching a new product, entering a new market, or rebuilding underperforming paid search accounts.

## Quick Copy-Paste Version

You are a senior Google Ads strategist with 10+ years managing B2B SaaS accounts spending $500K–$5M/year.

Build a complete Google Ads campaign for the following product:

Product: [Your Product Name]
One-line description: [What it does and who it's for]
Target audience: [Job title / company size / industry]
Monthly budget: $[X]
Primary conversion goal: [Demo request / free trial / contact sales]
Top 3 competitors: [Competitor 1, Competitor 2, Competitor 3]
Geographic target: [US / UK / APAC / etc.]

Deliver:
1. Campaign structure (campaign types, ad groups, and rationale)
2. Keyword list: 15–20 high-intent keywords per ad group, with match types labeled [Exact] [Phrase] [Broad]
3. Negative keyword list (20+ terms)
4. 3 Responsive Search Ad (RSA) headlines (15 total) and descriptions (4 total) for the top ad group
5. Recommended bidding strategy with rationale (Target CPA, Maximize Conversions, etc.)
6. Conversion tracking setup checklist
7. 30-day optimization roadmap (weeks 1–4 actions)

Format each section with clear headers. Be specific — include actual keywords, not categories.

## Advanced Customizable Version

ROLE: You are a performance marketing director who has managed Google Ads budgets exceeding $10M annually for B2B SaaS companies. You specialize in full-funnel paid search strategy, Quality Score optimization, and revenue-attributed campaign architecture.

CONTEXT:
Company: [Company Name]
Product category: [e.g., "Project management software for engineering teams"]
ICP (Ideal Customer Profile):
  - Title: [e.g., VP Engineering, CTO, Engineering Manager]
  - Company size: [e.g., 50–500 employees]
  - Industry: [e.g., FinTech, HealthTech, SaaS]
  - Pain points: [e.g., sprint planning chaos, missed deadlines, engineering-PM misalignment]
Monthly Google Ads budget: $[X]
Current MQL cost target: $[X] or "unknown"
Sales cycle length: [e.g., 30–90 days]
Primary CTA: [Free trial / Book demo / Get pricing / Download guide]
Current top organic keywords (if known): [keyword1, keyword2, keyword3]
Top 3 competitors: [Competitor 1, Competitor 2, Competitor 3]
Landing page URL style: [e.g., dedicated campaign pages / homepage / product page]
Geo targets: [Countries / cities / radius]
Remarketing lists available: [Yes/No — if yes, describe: website visitors 30/60/90 days, demo abandoners, etc.]

OBJECTIVE: Build a complete, launch-ready Google Ads account architecture for a new campaign sprint. Output should be implementable directly in Google Ads Editor.

DELIVERABLES:

1. CAMPAIGN ARCHITECTURE
   - Recommend 3–5 campaigns with types (Search, Performance Max, Display Remarketing)
   - Justify each campaign's role in the funnel (TOFU/MOFU/BOFU)
   - Budget allocation recommendation per campaign (% of total budget)
   - Network settings, device bid adjustments, ad scheduling rationale

2. AD GROUP STRUCTURE (for primary Search campaign)
   - 4–6 tightly themed ad groups
   - Theme name + 3-sentence rationale for each
   - Search intent alignment (informational / commercial / transactional)

3. KEYWORD STRATEGY
   For each ad group, provide:
   - 8–12 keywords with match types: [E] Exact, [P] Phrase, [B] Broad Modified
   - Estimated monthly search volume tier (High >10K / Mid 1K–10K / Low <1K)
   - Intent score (1–5, where 5 = "ready to buy")
   - First-page bid estimate range where knowable

4. NEGATIVE KEYWORD LIST
   - 30+ negatives across 5 categories: competitor mismatches, job seekers, DIY/free-seekers, irrelevant industries, informational-only terms
   - Specify negative match type for each

5. AD COPY (RSA FORMAT)
   For the highest-priority ad group:
   - 15 unique headlines (30 chars max each) — include 3 using JTBD framing, 3 with social proof, 3 with urgency/offer
   - 4 unique descriptions (90 chars max each) — one per funnel angle: pain, solution, proof, CTA
   - Pinning recommendations (which headlines/descriptions to pin and why)
   - 2 ad copy variants for A/B testing (change one element: headline 1 or description 1)

6. EXTENSIONS (Assets)
   - Sitelink assets: 6 sitelinks with headlines + 2-line descriptions
   - Callout assets: 8 callouts
   - Structured snippet: header + 4–6 values
   - Call asset: recommended call hours and bid adjustment
   - Lead form asset (if applicable): 3 qualifying questions to include

7. BIDDING STRATEGY ROADMAP
   - Week 1–2: recommended starting strategy + why (usually Maximize Clicks or Manual CPC)
   - Week 3–4: transition trigger (e.g., "once 30 conversions tracked, switch to Target CPA")
   - Target CPA calculation: [formula based on CLV and close rate]
   - Target ROAS calculation: [formula based on average deal size]

8. CONVERSION TRACKING PLAN
   - Primary conversions to track (demo form, free trial signup, chat initiation)
   - Secondary conversions (page scroll depth, video views, pricing page visits)
   - Google Tag Manager implementation checklist (7–10 steps)
   - Attribution model recommendation with rationale

9. QUALITY SCORE OPTIMIZATION CHECKLIST
   - Landing page relevance actions (5 items)
   - Ad relevance actions (5 items)
   - Expected CTR improvement actions (5 items)

10. 60-DAY OPTIMIZATION ROADMAP
    Week 1: [specific actions]
    Week 2: [specific actions]
    Week 3–4: [specific actions]
    Week 5–8: [specific actions]
    Key metrics to review weekly: [list]
    Kill criteria: [when to pause an ad group or keyword]

CONSTRAINTS:
- Use only features available in Google Ads as of 2025 (RSAs standard, ETAs deprecated)
- All keywords must be specific — no vague category terms
- Ad copy must pass Google's editorial policies
- Budget recommendations must sum to 100%
- Include at least one competitor keyword campaign strategy

OUTPUT FORMAT: Use markdown with numbered sections and sub-bullets. Provide a "Quick Launch Checklist" summary at the end with 10 checkbox items.

## Example Input/Output

**Input Example:**
Company: Rootly
Product: Incident management platform for DevOps/SRE teams
ICP: VP Engineering, Site Reliability Engineers, DevOps leads at 100–1000 person tech companies
Budget: $15,000/month
Primary CTA: Book a demo
Competitors: PagerDuty, Opsgenie, FireHydrant
Geo: United States
Landing pages: Dedicated campaign pages exist
Remarketing: Website visitors 30/60 days available

**Output Example (excerpt):**

**Campaign Architecture:**
- Campaign 1: Brand Defense Search ($1,500/mo, 10%) — Protects against competitor conquesting on "Rootly" terms
- Campaign 2: High-Intent Solution Search ($7,500/mo, 50%) — Captures "incident management software," "on-call alerting tool," "pagerduty alternative" searches
- Campaign 3: Competitor Conquesting Search ($3,000/mo, 20%) — Targets searchers actively evaluating PagerDuty, Opsgenie, FireHydrant
- Campaign 4: Performance Max ($2,250/mo, 15%) — Automated placement across Search, Display, YouTube, Gmail for TOFU awareness
- Campaign 5: Remarketing Display ($750/mo, 5%) — Re-engages 30/60-day website visitors who did not convert

**Ad Group: Incident Management Software (High-Intent)**
Keywords:
- [E] "incident management software" — Mid volume, Intent: 5
- [E] "incident management platform" — Mid volume, Intent: 5
- [P] "on-call management tool" — Mid volume, Intent: 4
- [P] "incident response software for devops" — Low volume, Intent: 5
- [E] "pagerduty alternative" — Mid volume, Intent: 5
- [B] incident management saas devops — Low volume, Intent: 4

**RSA Headlines (excerpt):**
1. Incident Management for SREs (28 chars)
2. Resolve Incidents 60% Faster (29 chars)
3. Cut MTTR. Book a 20-Min Demo (29 chars)
4. Trusted by Notion, Brex & Canva (31 chars)
5. Free Trial — No Credit Card (28 chars)

**30-Day Roadmap:**
- Week 1: Launch campaigns on Manual CPC, establish baseline CTR/CPC data, add negative keywords daily
- Week 2: Review search term reports, add 20+ negatives, A/B test headlines
- Week 3: Enable Maximize Conversions once 15+ conversions tracked, pause keywords with 0 conversions at $50 spend
- Week 4: Activate remarketing campaign, submit Performance Max asset group, review impression share vs. budget

## Success Metrics

- **Click-Through Rate (CTR):** Target >5% for branded, >3% for non-branded search
- **Quality Score:** Average 7+ across all keywords (indicates ad relevance and landing page alignment)
- **Cost Per Lead (CPL):** Track against MQL target; typical B2B SaaS benchmark $150–$400 for demo requests
- **Conversion Rate:** Landing page CVR >3% (industry average 2.35%; top quartile 5.31%)
- **Search Impression Share:** >60% for branded, >30% for core non-branded terms
- **ROAS/Revenue Attribution:** Connect to CRM pipeline to measure cost-per-opportunity and cost-per-closed-won

## Related Prompts

- [`../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/Landing-Page-Generation/Landing-Page-Generator.md`](../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/Landing-Page-Generation/Landing-Page-Generator.md) — Generate high-converting landing pages for each campaign
- [`../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Conversion-Rate-Optimization.md`](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Conversion-Rate-Optimization.md) — Optimize post-click conversion rate
- [`../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md`](../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md) — Attribute pipeline revenue to Google Ads spend
- [`../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/A-B-Testing-Automation.md`](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/A-B-Testing-Automation.md) — Structure A/B tests for ad copy and landing pages

## Integration Tips

- **Google Ads Editor:** Export the keyword list and ad copy output as CSV and import directly — saves 2–3 hours of manual entry
- **HubSpot / Salesforce:** Set up UTM parameters (`utm_source=google&utm_medium=cpc&utm_campaign=[Campaign Name]`) on all final URLs; map to Contact Source field in CRM to close the revenue loop
- **Google Analytics 4:** Link GA4 to Google Ads for enhanced conversion import; use GA4 audiences (high-intent visitors, pricing page viewers) as remarketing lists
- **Google Tag Manager:** Use GTM for all conversion tag deployment — keeps tracking centralized and editable without developer involvement
- **Looker Studio:** Build a live PPC dashboard pulling Google Ads, GA4, and CRM data to report CPL, pipeline influenced, and ROAS in one view
- **Zapier / Make:** Trigger Slack alert when daily spend exceeds budget threshold or when cost-per-conversion spikes 50% above baseline

## Troubleshooting

**Problem: Low impression volume despite sufficient budget**
Solution: Check that keyword match types are not too restrictive — add Phrase variants alongside Exact. Verify campaigns are not limited by ad approval (check Policy Manager). Review geographic and device targeting for unintentional exclusions.

**Problem: High CTR but low conversion rate (<1%)**
Solution: Audit landing page message match — the headline on the landing page should mirror the search query and ad headline. Check page load speed (target <2s). Confirm the CTA form has fewer than 5 fields. Run a 5-second test to verify value proposition clarity.

**Problem: Quality Scores stuck at 3–4 despite relevant ads**
Solution: Create tighter single-theme ad groups where every keyword in the group would plausibly trigger the same ad. Ensure the landing page contains exact keyword phrases in H1, meta description, and above-the-fold copy. Improve historical CTR by pausing lowest-performing ad variations.

## Version History
- v1.0: Initial creation (auto-generated)
