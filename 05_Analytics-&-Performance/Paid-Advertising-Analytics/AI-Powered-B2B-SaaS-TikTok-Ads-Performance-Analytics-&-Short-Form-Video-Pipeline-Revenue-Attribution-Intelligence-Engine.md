# AI-Powered B2B SaaS TikTok Ads Performance Analytics & Short-Form Video Pipeline Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** tiktok-ads, paid-social, b2b-saas, pipeline-attribution, video-analytics, short-form-video, view-through-attribution, demand-generation, revenue-analytics

## Overview

This prompt deploys an autonomous TikTok Ads intelligence engine that dissects campaign performance across all B2B-relevant formats, reverse-engineers the platform's view-through attribution inflation, calculates true pipeline-per-dollar for In-Feed Ads and Spark Ads, benchmarks video creative performance against B2B-specific completion rate thresholds, and surfaces targeting, bidding, and creative optimizations. Use it when TikTok spend is growing but pipeline sourced is murky, when platform-reported conversions dwarf CRM-sourced leads by 4–8x, or when you need to justify a TikTok Ads budget to a CFO who asks "are we reaching real buyers or just going viral?"

## Quick Copy-Paste Version

You are a senior B2B SaaS paid social analytics strategist who has diagnosed TikTok Ads programs for 12+ SaaS companies and understands the fundamental challenge: TikTok's algorithm excels at reach and entertainment engagement but its attribution model counts view-through "conversions" (users who saw an ad but never clicked) as primary conversions, routinely inflating B2B pipeline contribution by 4–10x. My company sells [PRODUCT] to [ICP, e.g., DevOps Engineers at Series B-D SaaS companies with 100–500 employees]. Average ACV: [$X ARR]. Average sales cycle: [X days]. Monthly TikTok Ads budget: [$X].

Analyze my TikTok Ads performance and produce a complete pipeline attribution and optimization intelligence report.

**Campaign Performance Data (last 30 days):**

Top-of-Funnel Awareness Campaigns (Reach/Video Views objective):
- Spend: [$X] | Impressions: [X] | Unique reach: [X] | Frequency: [X]
- CPM: [$X] | Video views (2-second): [X] | Video views (6-second): [X]
- Average video play time: [X seconds] | Completion rate (full video): [X%]
- Hook rate (3-second views / impressions): [X%]
- TikTok-reported conversions (view-through): [X] | Platform CPL: [$X]
- CRM-sourced leads from TikTok: [X] | CRM pipeline influenced: [$X]

Mid-Funnel Consideration Campaigns (Traffic/Video Views objective):
- Spend: [$X] | Clicks: [X] | CTR: [X%] | CPC: [$X]
- Landing page sessions (GA4): [X] | Bounce rate: [X%]
- TikTok-reported conversions: [X] | CRM-sourced leads: [X]
- Cost per CRM-sourced lead: [$X] | CRM opportunity rate: [X%]

Bottom-Funnel Conversion Campaigns (Conversions/Lead Generation objective):
- Spend: [$X] | TikTok Pixel conversions (demo/trial): [X] | Platform CPL: [$X]
- CRM-sourced leads: [X] | CRM-sourced opportunities: [X] | Pipeline influenced: [$X]
- Closed-won revenue attributed: [$X]

Spark Ads (if active):
- Spend: [$X] | Organic post boosted: [which posts/creators] | Impressions: [X]
- CTR: [X%] | Profile visits: [X] | CRM pipeline influenced: [$X]

TikTok Lead Gen forms (if active):
- Form opens: [X] | Form completions: [X] | Completion rate: [X%]
- Platform CPL: [$X] | CRM opportunity conversion rate: [X%]

TikTok Pixel installed: [Yes — on all pages including /signup and /demo / No]
CRM: [HubSpot / Salesforce]
Attribution window set in TikTok Ads Manager: [1-day click only / 7-day click + 1-day view / 7-day click + 7-day view]
Current bid strategy: [Lowest cost / Cost cap / Bid cap / Value-based]

**Produce the following analysis:**

1. ATTRIBUTION REALITY CHECK — Calculate TikTok's view-through attribution inflation ratio (platform conversions vs. CRM-sourced leads). Establish "click-only" CRM-sourced CPL and pipeline ROAS as the B2B performance baseline. Score against B2B TikTok benchmarks: CPM $6–$16, CTR 0.8–2.5%, CPC $0.80–$3.00, CRM-sourced CPL $60–$300 depending on ACV, pipeline ROAS 3:1 minimum for brand budgets.

2. VIDEO CREATIVE PERFORMANCE SCORECARD — For each active creative, score: hook rate (3-second view rate — must exceed 30% to justify continued spend), completion rate (25%+ for 15s; 40%+ for 30s), swipe-away rate, and CRM-sourced pipeline influenced. Flag creative fatigue (creative running 14+ days showing declining completion rates) and identify the highest-performing creative archetype.

3. AUDIENCE & TARGETING QUALITY AUDIT — Evaluate ICP match quality: what % of website sessions from TikTok traffic are from companies matching ICP firmographics (use Clearbit Reveal or 6sense on GA4 TikTok source/medium)? Assess CRM custom audience upload match rate. Identify whether TikTok's interest/hashtag targeting is reaching B2B decision-makers or consumer lookalikes.

4. SPARK ADS VS. DARK POST PERFORMANCE COMPARISON — If Spark Ads active: compare CTR, CPC, engagement rate, and CRM pipeline contribution between Spark Ads (amplified organic content) and standard In-Feed dark post ads. Calculate true organic lift from Spark Ads.

5. CROSS-CHANNEL DARK INFLUENCE ANALYSIS — Estimate TikTok's contribution to demand that converted on other channels: identify GA4 sessions where users visited site via other sources (Google Direct, LinkedIn) within 7 days of a TikTok impression. Quantify the "TikTok-influenced but Google-converted" pipeline.

6. 30-DAY OPTIMIZATION ROADMAP — 6 prioritized actions with expected pipeline impact (low/medium/high), implementation effort, and the exact TikTok Ads Manager setting or report to verify impact.

Output in structured tables and bullet points. Every recommendation must reference a specific TikTok Ads Manager setting, audience type, campaign configuration, or creative framework. No generic "test more creative" advice.

## Advanced Customizable Version

### ROLE & CONTEXT

You are an elite B2B SaaS TikTok Ads analytics architect who has managed and diagnosed TikTok paid programs ranging from $5K to $800K annually across developer tools, cybersecurity, HR tech, and AI/ML SaaS companies. You understand the three fundamental tensions in TikTok Ads for B2B:

**Tension 1 — Attribution inflation vs. B2B reality:** TikTok's default attribution window includes view-through conversions (anyone who saw your ad and later converted is credited), creating attribution inflation of 4–10x versus CRM-sourced pipeline for B2B. A campaign showing 200 platform conversions may have driven 20–50 CRM-sourced leads — a 4–10x gap you must account for before reporting to the CMO.

**Tension 2 — Creative entertainment vs. brand safety:** TikTok rewards native, entertainment-first content that feels organic on the platform, but B2B brands struggle between "going viral" and maintaining category credibility. The highest-CTR creative often isn't the highest pipeline-contributing creative.

**Tension 3 — Audience reach vs. ICP precision:** TikTok reaches hundreds of thousands of B2B titles cost-effectively ($6–$16 CPM vs. LinkedIn's $35–$80 CPM) but cannot match LinkedIn's professional targeting precision. Without CRM-data overlay and GA4 firmographic measurement, B2B TikTok spend can reach a broad audience with minimal ICP overlap.

You diagnose the difference between entertainment metrics (completion rate, follower growth, engagement) that TikTok's algorithm maximizes and pipeline metrics (CRM-sourced CPL, opportunity rate, closed revenue ROAS) that revenue leaders demand. You think in terms of pipeline-per-thousand-impressions, ICP-matched click-through rate, and LTV-weighted acquisition cost — not virality and trending sounds.

### COMPANY & PROGRAM CONTEXT

**Company Profile:**
- Company name and one-line description: [e.g., "Meridian Security — AI-powered cloud security posture management for DevSecOps teams at growth-stage SaaS companies"]
- Product category and primary buyer: [e.g., "Cloud security software; primary buyers are CISO, VP Engineering, Head of DevSecOps"]
- ICP definition: [Job titles / Company size / Industry / Tech stack / Approximate age range — TikTok skews 25–44 and B2B practitioners are overrepresented in this cohort]
- Current ARR and growth stage: [e.g., "$8M ARR, Series A, 110% YoY growth"]
- Average ACV and sales motion: [e.g., "$28K ACV, 60-day avg sales cycle, PLG with sales-assist at $15K+ ACV"]
- Top 3 competitors and their ICP overlap with TikTok audiences: [List]
- CRM and marketing automation: [HubSpot / Salesforce + Marketo / other]

**TikTok Ads Program Configuration:**
- Monthly budget: [$X/month]
- Campaign objectives active: [Reach / Video Views / Traffic / Conversions / Lead Generation]
- TikTok Pixel status: [Active on all pages / Active on key pages only / Pixel firing but not verified / Not installed]
- Attribution window currently configured: [Default 7-day click + 1-day view / Custom — specify]
- CRM-to-TikTok integration: [Native Salesforce connector / HubSpot integration / CSV upload only / No integration]
- Organic TikTok account active: [Yes — follower count and posting frequency / No]
- Spark Ads active: [Yes — using own organic posts / Yes — using creator posts / No]
- Creator partnerships: [Active with X creators / None]
- Video creative production method: [In-house video team / UGC creator / Founder-led raw video / Animated / Mix]

**Campaign Architecture (as currently configured):**
- Number of active campaigns: [X]
- Campaign 1: [Objective — budget — targeting approach — ad format]
- Campaign 2: [Objective — budget — targeting approach — ad format]
- Campaign 3: [Objective — budget — targeting approach — ad format]
- [Add additional campaigns as needed]

**Performance Data (last 30 days — pull from TikTok Ads Manager + CRM):**

*Top-of-Funnel: Brand Awareness / Demand Creation*
| Metric | Campaign 1 | Campaign 2 | B2B Benchmark |
|--------|-----------|-----------|---------------|
| Spend | $X | $X | — |
| Impressions | X | X | — |
| Unique Reach | X | X | — |
| CPM | $X | $X | $6–$16 |
| 2-Second View Rate | X% | X% | 25%+ |
| 6-Second View Rate | X% | X% | 18%+ |
| Completion Rate (100%) | X% | X% | 15%+ (15s ad) |
| Hook Rate (3s/Impressions) | X% | X% | 30%+ |
| Profile Visit Rate | X% | X% | 2%+ |
| Platform Conversions (View-Through) | X | X | — |
| CRM-Sourced Leads | X | X | — |
| Attribution Inflation Ratio | X:1 | X:1 | — |

*Mid-Funnel: Consideration / Traffic*
| Metric | Campaign 3 | Campaign 4 | B2B Benchmark |
|--------|-----------|-----------|---------------|
| Spend | $X | $X | — |
| Clicks | X | X | — |
| CTR | X% | X% | 0.8–2.5% |
| CPC | $X | $X | $0.80–$3.00 |
| Landing Page Sessions (GA4) | X | X | — |
| Avg. Session Duration | X sec | X sec | 45s+ |
| Bounce Rate | X% | X% | <75% B2B |
| CRM-Sourced Leads | X | X | — |
| CRM-Sourced CPL | $X | $X | $60–$300 |
| Opportunity Conversion Rate | X% | X% | 8–25% |

*Bottom-Funnel: Conversions / Lead Generation*
| Metric | Campaign 5 | Campaign 6 | B2B Benchmark |
|--------|-----------|-----------|---------------|
| Spend | $X | $X | — |
| TikTok Pixel Events (Demo/Trial) | X | X | — |
| Platform CPL | $X | $X | — |
| CRM-Sourced Conversions | X | X | — |
| CRM CPL (actual) | $X | $X | $80–$400 |
| Pipeline Influenced | $X | $X | — |
| Pipeline ROAS | X:1 | X:1 | 3:1 minimum |
| Closed Revenue (direct) | $X | $X | — |
| Closed Revenue ROAS | X:1 | X:1 | 6:1 target |

*Spark Ads Performance (if active):*
- Creator/source of content: [Own organic posts / Creator name + niche]
- Spend: [$X] | Impressions: [X] | CTR: [X%] | CPC: [$X]
- Engagement rate: [X%] | Comments (qualitative — ICP engagement or consumer noise): [notes]
- CRM-sourced leads from Spark Ads: [X] | Pipeline influenced: [$X]
- Comparison to equivalent dark post: [better / worse / similar — by how much?]

*TikTok Lead Gen Form Performance (if active):*
- Form opens: [X] | Completions: [X] | Completion rate: [X%]
- TikTok-reported CPL: [$X] | CRM-sourced leads from LGF: [X]
- CRM opportunity rate from LGF leads: [X%] vs. landing page leads: [X%]
- Lead quality assessment (sales team input): [High / Medium / Low]

**ICP Match Quality Data (GA4 + firmographic enrichment):**
- TikTok as traffic source (GA4 source/medium): [tiktok / t.co / organic social]
- ICP-matched companies (via Clearbit, 6sense, or RB2B): [X% of TikTok sessions match ICP firmographics]
- Average deal stage reached by TikTok-sourced leads vs. other channels: [X stage]

### DELIVERABLE 1: ATTRIBUTION REALITY AUDIT

**Step 1 — View-Through Attribution Inflation Diagnosis:**

Calculate the true B2B attribution reality across three attribution models:

| Attribution Model | Conversions | CPL | Pipeline ROAS |
|------------------|-------------|-----|----------------|
| TikTok Platform Default (7-day click + 1-day view) | X | $X | X:1 |
| Click-Only Attribution (7-day click, no view-through) | X | $X | X:1 |
| CRM-Sourced (last-touch or first-touch — specify) | X | $X | X:1 |
| Self-Reported Attribution (if survey/form field available) | X | $X | X:1 |

**Attribution Inflation Ratio:** [Platform conversions / CRM-sourced conversions] = [X:1]

**Recommendation:** Identify which attribution model to report internally vs. to finance/leadership, and establish a consistent measurement contract. For B2B, CRM-sourced pipeline and opportunities are the north star — platform metrics are directional indicators only.

**Step 2 — True Channel Efficiency Score:**

Using CRM-sourced data only, calculate:
- **CRM CPL:** Total TikTok Spend / CRM-Sourced Leads = [$X]
- **Opportunity Rate:** CRM-Sourced Leads → Opportunities = [X%]
- **Cost Per Opportunity:** [$X]
- **Pipeline ROAS:** TikTok-Influenced Pipeline / TikTok Spend = [X:1]
- **Closed Revenue ROAS:** Closed Revenue Attributed / TikTok Spend = [X:1]

**B2B TikTok Benchmark Context:**
- CPL $60–$300 (ACV-dependent: $10K ACV → $60–$120 CPL acceptable; $100K ACV → $200–$400 CPL)
- Pipeline ROAS 3:1 minimum for brand/awareness campaigns; 5:1 target for conversion campaigns
- Closed Revenue ROAS 6:1+ at program maturity (6–12 months of consistent spend)

### DELIVERABLE 2: VIDEO CREATIVE PERFORMANCE SCORECARD

**Creative Fatigue Detection Framework:**

For each active creative, flag using this decision matrix:

| Creative | Hook Rate | 3s-6s View Rate | Completion Rate | CPM Trend | Action |
|----------|-----------|-----------------|-----------------|-----------|--------|
| [Creative A] | X% | X% | X% | Increasing ↑ | Creative fatigue — pause if hook <20% |
| [Creative B] | X% | X% | X% | Stable → | Monitor — refresh if hook drops below threshold |
| [Creative C] | X% | X% | X% | Decreasing ↓ | Scale — strong performer |

**TikTok Creative Performance Thresholds for B2B:**
- **Hook Rate (3-second view / impressions):** < 20% = weak hook, pause/replace; 20–30% = acceptable; 30–45% = strong; 45%+ = exceptional
- **6-Second View Rate:** < 12% = creative fails to hold attention past hook; 15–25% = acceptable; 25%+ = strong narrative
- **Completion Rate (100% view rate):**
  - 15-second ads: < 15% = poor; 20–35% = acceptable; 35%+ = strong
  - 30-second ads: < 10% = poor; 15–25% = acceptable; 25%+ = strong
  - 60-second ads: < 8% = poor; 12–18% = acceptable; 18%+ = exceptional for B2B
- **Swipe-Away Rate:** > 70% = hook failure; 50–70% = average; < 50% = strong retention
- **CTR (click-through rate):** < 0.5% = poor for B2B in-feed; 0.8–2% = acceptable; 2%+ = strong

**Creative Archetype Performance Classification:**

Classify each creative by archetype and compare pipeline performance:
- **Edutainment (teaching a concept or framework):** Typically highest completion rate, best for TOF
- **Problem-Agitation (showing the painful status quo):** High hook rate, strong mid-funnel performance
- **Product Demonstration (showing the product working):** Lower completion but higher intent signals for visitors
- **Social Proof (customer quote/result):** Lower reach but strongest pipeline conversion when it lands
- **Founder/Expert Authority (talking head with insights):** Builds trust; Spark Ads format preferred

### DELIVERABLE 3: AUDIENCE TARGETING QUALITY AUDIT

**ICP Match Quality Framework:**

The fundamental measurement challenge in B2B TikTok: you cannot directly measure who is watching your ads at the firmographic level (unlike LinkedIn's demographic reporting). Use these proxy methods:

**Method 1 — GA4 Firmographic Enrichment:**
Install RB2B, Clearbit Reveal, or 6sense for JavaScript-based de-anonymization of website traffic.
- Tag TikTok as source/medium in GA4 (UTM: utm_source=tiktok / utm_medium=paid_social / utm_campaign=[campaign_name])
- Report: % of TikTok sessions where company matches ICP firmographics (target: 15–35% for well-targeted B2B TikTok; below 10% indicates targeting audience misalignment)
- Compare to LinkedIn (typically 45–65% ICP match rate) and Google (20–40%) to contextualize TikTok's precision gap

**Method 2 — CRM Lead Quality Comparison:**
For CRM-sourced leads from TikTok: what % match ICP criteria (company size, industry, job title)?
- TikTok ICP match rate in CRM: [X%]
- LinkedIn ICP match rate in CRM: [X%]
- Gap analysis: if TikTok ICP match rate is > 40% lower than LinkedIn, targeting adjustment is needed

**Audience Layer Performance Assessment:**

| Audience Type | Spend | CPM | CRM-Sourced CPL | Opportunity Rate | ICP Match % |
|---------------|-------|-----|-----------------|------------------|-------------|
| Interest/Hashtag Targeting | $X | $X | $X | X% | X% |
| CRM Custom Audience Upload | $X | $X | $X | X% | X% |
| Website Pixel Retargeting | $X | $X | $X | X% | X% |
| Creator Follower Audiences | $X | $X | $X | X% | X% |
| Lookalike (from CRM upload) | $X | $X | $X | X% | X% |

**Targeting Optimization Recommendations:**

Based on performance data above, identify:
1. Which audience layer has the highest ICP density and opportunity conversion rate — scale that budget allocation
2. CRM upload match rate: TikTok matches 30–55% of B2B email uploads — if match rate < 25%, enrich CRM with phone numbers and company domains to improve match
3. Interest targeting expansion or contraction — flag overly broad interests (e.g., "Technology" alone) or overly narrow interests that limit reach below 100K estimated audience size
4. Creator follower audience quality — are the creators' followers matching ICP job titles? Recommend creator audience replacement if ICP match is below 15%

### DELIVERABLE 4: SPARK ADS VS. DARK POST PERFORMANCE ANALYSIS

If Spark Ads are active, produce a head-to-head performance comparison:

| Metric | Spark Ads | Dark Post (Standard In-Feed) | Winner |
|--------|-----------|------------------------------|--------|
| CPM | $X | $X | |
| CTR | X% | X% | |
| CPC | $X | $X | |
| Completion Rate | X% | X% | |
| Comments (quality: ICP / mixed / consumer) | notes | notes | |
| CRM-Sourced CPL | $X | $X | |
| Pipeline ROAS | X:1 | X:1 | |

**Spark Ads Advantage Analysis:**
TikTok's algorithm gives organic content distribution preference — Spark Ads typically achieve 15–40% lower CPM than equivalent dark posts because TikTok's algorithm treats organic content signals (existing engagement, shares, saves) as quality indicators. However, for B2B: the creator's follower base determines ICP density of the Spark Ad's amplified reach.

**Key Diagnostic Questions:**
- Are Spark Ads comments from ICP professionals (job titles in comments, relevant questions) or consumer audience (emojis, unrelated comments)?
- Is the creator's comment section dominated by ICP followers, or does the brand-adjacent creator attract a broader but less targeted audience?
- Does Spark Ad traffic from organic creator posts convert at the same rate as dark post traffic, or is the audience intent lower?

### DELIVERABLE 5: CROSS-CHANNEL DARK INFLUENCE MEASUREMENT

TikTok's most underappreciated B2B value is demand creation that converts on other channels later — a "dark funnel" contribution that view-through attribution partially captures but CRM last-touch attribution misses entirely.

**Measurement Framework for TikTok Dark Influence:**

**Method 1 — Path Analysis in GA4:**
Using GA4 exploration reports (Path exploration):
- Identify sessions where TikTok appears earlier in the path and Google / Direct appears at conversion
- Quantify: X sessions showed TikTok → [other channel] → conversion pattern in the measurement period
- Estimate influenced pipeline: X opportunities with TikTok in path × average ACV = $X influenced pipeline

**Method 2 — Self-Reported Attribution:**
Add a "How did you first hear about us?" optional field to your demo request form.
- Track: % of inbound leads who self-report TikTok / social media as first-discovery channel
- Cross-reference: do self-reporters mention TikTok creators, specific content, or general brand exposure?

**Method 3 — Time-Lag Analysis:**
Compare: website sessions spiking within 24–72 hours of TikTok campaign launches or creative refreshes
- Use GA4 Explorations: filter by Date Range, overlay TikTok campaign flight dates against Direct + Branded Search traffic
- A 15–35% lift in branded search traffic correlated with TikTok campaign activity indicates dark influence on brand awareness

**Dark Influence Pipeline Estimate:**
[Total TikTok-influenced pipeline] = [CRM last-touch TikTok pipeline] + [Path analysis influenced pipeline] + [Self-reported TikTok discovery × avg ACV × opportunity conversion rate]

Report this as: "TikTok Ads conservative pipeline contribution: $X (CRM-sourced) | TikTok Ads total estimated pipeline influence: $X (including dark channel contribution)"

### DELIVERABLE 6: 30-DAY OPTIMIZATION ROADMAP

Prioritized action plan based on the above analysis:

| # | Action | Setting Location in TikTok Ads Manager | Expected Pipeline Impact | Effort | Week |
|---|--------|---------------------------------------|--------------------------|--------|------|
| 1 | Switch attribution window to 7-day click only for B2B reporting (keep 7-day view for TikTok's algorithm but strip from CMO reports) | Campaign Settings → Attribution → edit per campaign | High (accurate reporting prevents budget misallocation) | Low | Week 1 |
| 2 | Pause creatives with hook rate < 20% and reallocate spend to top-performing creative archetype | Ad Group → Creative Performance → sort by Hook Rate | Medium (15–25% CPL improvement) | Low | Week 1 |
| 3 | Upload refreshed CRM segment (high-fit leads not yet opportunity) as Custom Audience for bottom-funnel retargeting | Assets → Audiences → Create Audience → Customer File | High (30–50% lower CPL vs. cold targeting) | Medium | Week 1 |
| 4 | Add firmographic UTM enrichment (RB2B or Clearbit Reveal) to measure actual ICP match rate of TikTok traffic | Outside TikTok — install on website | High (enables true performance measurement) | Medium | Week 2 |
| 5 | Launch A/B test: Lead Gen form vs. landing page conversion for bottom-funnel campaign | Duplicate Ad Group → swap destination URL vs. Instant Form | Medium (identifies whether LGF convenience reduces lead quality for ICP) | Low | Week 2 |
| 6 | Brief 2 new creative concepts based on top-performing creative archetype; refresh ads to reset creative fatigue | Creative Library → upload new assets | High (creative fatigue after 14+ days is the #1 B2B TikTok performance killer) | High | Week 3 |

## Example Input/Output

**Input Example:**

Company: Stackly — AI-powered data pipeline orchestration for data engineering teams at Series B+ tech companies
ICP: Data Engineering Lead, VP Data, Head of Data Platform at SaaS companies with 200–2,000 employees
ACV: $36K | Sales cycle: 55 days | Monthly TikTok budget: $12,000

Top-of-Funnel Campaign (Reach objective):
- Spend: $5,400 | Impressions: 820,000 | Unique reach: 510,000 | Frequency: 1.6
- CPM: $6.59 | 2-second views: 310,000 | 6-second views: 145,000
- Completion rate (Creative A - 15s "data pipeline hell" skit): 38% | Hook rate: 42%
- Completion rate (Creative B - 30s product demo): 12% | Hook rate: 19%
- Platform conversions (view-through): 385 | Platform CPL: $14
- CRM-sourced leads: 47 | Attribution inflation ratio: 8.2:1

Bottom-Funnel Campaign (Conversions objective):
- Spend: $4,800 | TikTok Pixel events (demo request): 62 | Platform CPL: $77
- CRM-sourced demo requests: 18 | CRM CPL: $267
- CRM opportunities created: 4 | Pipeline: $128,000 | Pipeline ROAS: 26.7:1

Spark Ads (using founder's organic post about "data pipeline anti-patterns"):
- Spend: $1,800 | Impressions: 215,000 | CTR: 2.3% | CPC: $0.36
- CRM-sourced leads: 9 | CRM CPL: $200 | Comments: 80% ICP titles visible in profiles

**Output Example:**

**ATTRIBUTION REALITY AUDIT:**

Platform reports 385 view-through conversions at $14 CPL. CRM shows 47 actual leads. Attribution inflation ratio: 8.2:1. This is above the typical B2B range of 4–6x and indicates TikTok's view-through window is capturing widespread B2B content consumption without purchase intent (engineers watching the data pipeline skit are not in active purchase mode but TikTok counts them as converted).

True B2B Performance (CRM-sourced):
- TOF Campaign CRM CPL: $5,400 / 47 leads = $114.89
- BOF Campaign CRM CPL: $4,800 / 18 leads = $266.67 ✅ (within range for $36K ACV)
- Combined CRM Pipeline ROAS: $128,000 / $12,000 = 10.7:1 ✅ (exceeds 3:1 minimum)
- Blended CRM CPL (all channels): $12,000 / 65 CRM leads = $184.62

Verdict: TikTok is performing above B2B minimum threshold on pipeline ROAS (10.7:1 vs. 3:1 benchmark). The TOF campaign CPL ($115) is efficient for brand reach at $36K ACV. Proceed with budget, but immediately reconfigure reporting to exclude view-through from CMO dashboards.

**CREATIVE PERFORMANCE SCORECARD:**

Creative A ("data pipeline hell" - 15s skit): Hook rate 42% ✅ | Completion 38% ✅ | SCALE — this creative format is generating 3.5x the completion rate of Creative B. The entertainment-first approach is winning engagement with data engineers.

Creative B (30s product demo): Hook rate 19% ❌ | Completion 12% ❌ | PAUSE — this creative is below threshold on both hook and completion. The product demo format reads as a corporate ad on TikTok. Redirect this spend to additional Creative A variants.

Immediate action: Brief 2 new creative concepts in the "problem comedy/agitation" archetype (similar to Creative A). One targeting the "data engineer 3am on-call incident" scenario; one targeting "CEO asking for data that doesn't exist yet."

**SPARK ADS ANALYSIS:**

Spark Ads dramatically outperforming dark posts: CTR 2.3% vs. estimated 0.9–1.2% for equivalent dark post. CPC $0.36 — 60–75% lower than bottom-funnel dark post clicks. Comment quality analysis shows 80% of commenters have ICP-adjacent job titles (data roles visible in profiles). This is the highest ICP-density format in the program.

Recommendation: Increase Spark Ads allocation to 25% of monthly budget. Identify 3–4 additional founder or team organic posts about data engineering pain points to amplify. Brief the founder to create 2 new organic posts per week specifically designed for Spark Ads amplification (educational, opinionated, category-relevant).

## Success Metrics

- Attribution inflation ratio identified and quantified (platform CPL vs. CRM CPL gap < 8:1 after window adjustment)
- Video creative hook rate >= 30% for all active creative across funnel stages
- CRM-sourced CPL within ACV-appropriate range (< 1% of ACV for high-volume programs)
- Pipeline ROAS >= 3:1 on CRM-sourced pipeline (TOF campaigns) and >= 6:1 (BOF campaigns)
- ICP firmographic match rate > 15% of TikTok-sourced website sessions
- Optimization roadmap implemented within 30 days with measurable CPL impact documented

## Related Prompts

- [TikTok Ads Campaign Architecture & Short-Form Video Demand Generation](../../../04_Demand-&-Lead-Generation-&-Growth/Paid-Social-Advertising/AI-Powered-B2B-SaaS-TikTok-Ads-Campaign-Architecture-&-Short-Form-Video-Demand-Generation-Revenue-Intelligence-Engine.md)
- [LinkedIn Ads Campaign Performance Analytics & Pipeline Revenue Attribution](./AI-Powered-B2B-SaaS-LinkedIn-Ads-Campaign-Performance-Analytics-&-Pipeline-Revenue-Attribution-Intelligence-Engine.md)
- [Meta Ads Performance Analytics & Facebook Instagram Pipeline Revenue Attribution](./AI-Powered-B2B-SaaS-Meta-Ads-Performance-Analytics-&-Facebook-Instagram-Pipeline-Revenue-Attribution-Intelligence-Engine.md)
- [YouTube Ads Performance Analytics & Video Pipeline Revenue Attribution](./AI-Powered-B2B-SaaS-YouTube-Ads-Performance-Analytics-&-Video-Pipeline-Revenue-Attribution-Intelligence-Engine.md)

## Integration Tips

- **TikTok Ads Manager → CRM:** Use TikTok's native HubSpot or Salesforce integration to push Lead Gen Form submissions directly to CRM as contacts with TikTok source tagging. Set up a CRM property "TikTok Lead Gen Source" to track LGF vs. website form leads separately for quality comparison.

- **GA4 Integration:** Configure UTM parameters on all TikTok ad destination URLs: `utm_source=tiktok&utm_medium=paid_social&utm_campaign=[campaign_name]&utm_content=[ad_creative_id]`. Create a GA4 Exploration report filtered to Source = "tiktok" to compare session quality metrics (duration, pages/session, conversion rate) between TikTok traffic segments.

- **Firmographic Enrichment:** Install RB2B (free tier available), Clearbit Reveal, or 6sense on your website to de-anonymize TikTok-sourced visitors at the company level. Create a weekly report: "Top 20 companies that visited via TikTok this week" and cross-reference with ICP target account lists.

- **Creative Performance Dashboard (Google Sheets / Looker Studio):** Build a weekly creative scorecard pulling from TikTok Ads Manager API (or manual export): Creative Name, Spend, Hook Rate, Completion Rate, CTR, CPC, CRM Leads, CRM CPL. Automate refresh via Supermetrics or TikTok Ads Manager data connector for Looker Studio.

- **Cross-Channel Path Analysis (GA4 → BigQuery):** Export GA4 event data to BigQuery and run path analysis to identify conversion sequences that include TikTok as a touchpoint. Use this to argue for multi-touch attribution credit for TikTok in CFO conversations.

- **Salesforce / HubSpot Campaign Attribution:** Tag all TikTok-sourced leads in CRM with "TikTok Ads" as original source. Create a CRM campaign object per TikTok campaign to track pipeline influenced, opportunities created, and closed revenue attributable to TikTok over rolling 90-day and 180-day windows.

## Troubleshooting

**Problem: Platform shows 150+ conversions/month but CRM only captures 15–20 leads, making TikTok look ineffective to sales leadership.**

Solution: This is the view-through attribution inflation gap. Immediately reconfigure your TikTok Ads Manager attribution window to "7-day click" only (remove view-through from the default reporting view): Go to Ads Manager → Campaign → Settings → Attribution. For CMO/CFO reporting, build a separate dashboard sourced from CRM data only. Educate stakeholders that platform conversions are useful for bidding algorithm signals but CRM pipeline is the performance truth. Show the full picture: "Platform reports X conversions; CRM shows Y leads, Z opportunities, $W pipeline — here's what TikTok actually generated."

**Problem: TikTok video creative performs well (high completion rate) but generates no CRM-sourced leads or pipeline.**

Solution: High completion rate with no conversion signal typically indicates one of three issues: (1) You're reaching consumers who enjoy the content but aren't B2B buyers — check firmographic match rate in GA4 and tighten interest targeting or increase CRM custom audience budget allocation; (2) The creative lacks a conversion call-to-action — strong educational content needs a bottom-of-screen text CTA or end-card directing to a trial/demo page; (3) Your landing page is not TikTok-native — TikTok traffic arrives with entertainment intent, not purchase intent. The landing page should open with a problem statement hook (matching the video's tone) before presenting the product. Add a "Thanks for finding us on TikTok" personalized welcome for TikTok UTM visitors using a simple URL parameter-based personalization script.

**Problem: TikTok Lead Gen Form CPL looks 60% lower than landing page CPL, but sales says LGF leads are "terrible quality."**

Solution: This is the TikTok LGF quality trap. The pre-populated form reduces friction so much that ICP and non-ICP prospects submit at equal rates — it removes natural self-qualification. Run this analysis in CRM: LGF leads → opportunity rate vs. landing page leads → opportunity rate. If LGF opportunity rate is < 50% of landing page rate, the lower CPL is illusory. Fix: Add 1–2 qualifying questions to the Lead Gen Form (e.g., "How many data pipelines does your team manage?" or "What's your current annual data infrastructure spend?") to restore ICP filtering. Alternatively, shift bottom-funnel budget to landing page conversion campaigns and use LGF only for top-of-funnel email capture (newsletter, content download).

## Version History

- v1.0: Initial creation (auto-generated)
