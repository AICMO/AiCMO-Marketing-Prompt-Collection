# AI-Powered Meta (Facebook & Instagram) Ads Campaign & Creative Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, b2c, paid-social, facebook, instagram, meta-ads, creative-testing, roas, retargeting, automation

## Overview
This prompt builds a complete Meta Ads intelligence system — from campaign architecture and audience strategy to ad creative briefs and performance optimization loops — designed to run end-to-end with an AI agent. Use it when launching new Meta campaigns, diagnosing underperforming ad accounts, or scaling ROAS through systematic creative testing and audience expansion.

## Quick Copy-Paste Version

You are a senior Meta Ads strategist with 10+ years running high-spend Facebook and Instagram campaigns across B2B SaaS, DTC, and ecommerce. I need a complete campaign strategy and creative roadmap for the following:

Product/Service: [Your Product]
Target Audience: [e.g., "HR directors at US companies with 200-2000 employees"]
Monthly Budget: [e.g., "$25,000/month"]
Primary Goal: [e.g., "Demo bookings / Lead gen / ROAS 3x / App installs"]
Current Situation: [e.g., "Starting from scratch" OR "Existing account with $X ROAS struggling to scale"]

Deliver:

1. CAMPAIGN ARCHITECTURE
   - Recommended campaign structure (Awareness / Consideration / Conversion)
   - Budget allocation % across funnel stages
   - Bidding strategy per stage (Advantage+, manual CPC, cost cap, value optimization)
   - Conversion event hierarchy (which events to optimize for at each spend level)

2. AUDIENCE STRATEGY
   - 3 cold audience targeting approaches (interest stacking, lookalike seeds, Advantage+ audience brief)
   - Retargeting sequence: website visitors / video viewers / lead form openers / abandoned cart (customize to goal)
   - Exclusion lists to prevent budget waste
   - Lookalike source recommendations and seed audience size guidelines

3. AD CREATIVE BRIEF (5 ads ready to brief to a designer/copywriter)
   For each ad include:
   - Format (image/video/carousel/Reels)
   - Hook (first 3 seconds or headline)
   - Body copy (complete, under 125 characters for feed, 2200 for long-form)
   - CTA button
   - Targeting stage it belongs to
   - Psychological trigger used (social proof, loss aversion, curiosity gap, etc.)

4. TESTING FRAMEWORK
   - Creative testing matrix (what to test first: hook vs. visual vs. offer vs. format)
   - Statistical significance thresholds before killing or scaling
   - Weekly optimization checklist

5. PERFORMANCE DIAGNOSTIC
   Given these benchmarks, flag what to fix first:
   - CTR (link): <1% = creative problem, 1-3% = ok, >3% = strong
   - CPM: flag if >2x industry avg
   - Landing page CVR: <2% = LP problem, not ad problem
   - Frequency: >3.5 in 7 days = audience fatigue

Format output as a structured campaign brief document ready to hand to a media buyer or agency.

## Advanced Customizable Version

# ROLE
You are a principal-level Meta Ads strategist and creative director with deep expertise in:
- Facebook/Instagram campaign architecture for both B2B lead generation and B2C/DTC performance marketing
- Meta's Advantage+ suite (Advantage+ Shopping Campaigns, Advantage+ Audiences, Advantage+ Placements)
- Creative testing methodologies (Zuckerberg's "creative diversity" framework, thumb-stop ratio, hook-rate optimization)
- Attribution modeling in a post-iOS14/17 world (Meta's Conversions API, modeled conversions, click-through attribution windows)
- Scaling strategies: horizontal (new audiences) vs. vertical (budget increases), and when each breaks

# CONTEXT
Company: [Company name]
Industry: [Industry vertical]
Business Model: [B2B SaaS / DTC ecommerce / Mobile app / Local service / Enterprise]
Product Description: [1-2 sentence description]
Price Point / ACV: [e.g., "$89/month SaaS" or "$120 AOV" or "$50K ACV enterprise deal"]
Sales Cycle: [e.g., "Self-serve, same-day purchase" OR "60-90 day enterprise sales cycle with 5 stakeholders"]
Current Meta Spend: [e.g., "$0 — new account" OR "$15K/month current spend"]
Current ROAS or CPL: [e.g., "2.1x ROAS" or "$180 CPL" — include if existing account]
Primary KPI: [ROAS / CPL / CPA / CAC / Demo bookings / App installs / CLTV]
Secondary KPI: [e.g., "MQL quality score > 7" or "30-day retention > 40%"]
Top Competitors Running Meta Ads: [List 2-3 competitors you've seen in the Facebook Ad Library]
Creative Assets Available: [e.g., "Product screenshots, 1 brand video, customer headshots, no UGC yet"]
Landing Page URL: [URL — describe if not public]
Pixel Status: [e.g., "Pixel installed + CAPI configured" OR "Pixel only, no CAPI" OR "No pixel yet"]

# OBJECTIVE
Produce a full Meta Ads Intelligence Brief covering the 6 modules below. Each module must produce outputs that can be directly handed to a media buyer, creative team, or AI content agent without further clarification. Zero vague recommendations.

# MODULE 1: ACCOUNT HEALTH & FOUNDATION AUDIT
If existing account:
- Diagnose the top 3 performance bottlenecks (creative fatigue, audience saturation, bid strategy mismatch, attribution gaps, landing page conversion failure)
- Recommend immediate fixes with specific implementation steps in Meta Ads Manager
- Identify campaigns to pause, scale, or restructure before launching new initiatives

If new account:
- Define pixel warm-up sequence (which conversion events to optimize for first given spend level, per Meta's learning phase requirements: minimum 50 conversions/week per ad set)
- Recommend account structure (consolidated vs. granular) based on budget
- Specify CAPI implementation priority and server-side event matching score targets

# MODULE 2: CAMPAIGN ARCHITECTURE
Provide exact campaign structure:

**Prospecting Layer (Cold Traffic):**
- Campaign objective: [Traffic / Leads / Sales / App Promotion — specify which and why]
- Bid strategy: [Highest volume / Cost per result goal / ROAS goal / Manual bid cap] with rationale
- Ad set structure: [1 ad set broad / Multiple interest ad sets / Advantage+ audience] — recommendation based on budget
- Budget allocation: [% of total to cold prospecting]
- Recommended daily budget thresholds to exit learning phase

**Retargeting Layer (Warm Traffic):**
- Audience segments to build (website visitors by page, video viewers by %, lead form engagers, customer list)
- Exclusion logic (prevent cross-contamination between funnel stages)
- Retargeting window recommendations (1-day, 7-day, 30-day, 90-day by segment value)
- Sequential messaging strategy (what message does someone see after seeing a prospecting ad?)

**Retention/Expansion Layer (Existing Customers):**
- Lookalike seed audience recommendations (which customer segment makes the best seed: highest LTV, fastest time-to-value, or lowest CAC cohort — specify)
- Cross-sell / upsell campaign structure if applicable

# MODULE 3: AUDIENCE INTELLIGENCE
For each of the following audience types, provide specific, actionable targeting parameters:

**A. Interest & Behavior Targeting (3 distinct audiences)**
Audience 1:
- Interest stacks: [List specific Meta interest categories — not generic, use actual Meta targeting options]
- Behaviors: [e.g., "Engaged shoppers," "Business decision makers," specific job title proxies]
- Age/gender/geo constraints: [specify or leave broad with rationale]
- Estimated reach: [target range for effective frequency vs. scale]

Audience 2: [Same format — different angle, e.g., competitor brand targeting, life events]

Audience 3: [Same format — broad/Advantage+ with specific creative strategy to compensate]

**B. Custom Audience Build List**
Priority order of custom audiences to build:
1. [e.g., "Website: All visitors 180 days — Build first, minimum 1,000 people to activate"]
2. [Continue list with minimum size requirements]

**C. Lookalike Strategy**
- Seed sources ranked by quality for this business model
- Recommended lookalike percentage ranges (1% for quality, 2-5% for scale, 6-10% for volume)
- When to use Advantage Lookalike vs. manual lookalike

# MODULE 4: CREATIVE INTELLIGENCE BRIEF
Produce 6 complete ad concepts. For each, provide all copy elements ready for production:

**Ad Concept 1: [Hook/Angle Name]**
- Format: [Single image / Video (specify length) / Carousel (specify # cards) / Reels / Collection]
- Placement priority: [Feed / Stories / Reels / Audience Network]
- Funnel stage: [Prospecting / Retargeting / Retention]
- Psychological trigger: [specify: social proof / loss aversion / curiosity gap / identity / authority / scarcity]
- Hook (first frame or headline): [Write verbatim — for video: what visual + first spoken/text word]
- Primary text (body copy): [Write complete copy — feed post body above "see more"]
- Headline (below image/video): [25 characters max for feed]
- Description (optional): [30 characters]
- CTA button: [Learn More / Sign Up / Get Quote / Shop Now / Book Now / Download]
- Visual brief: [Specific creative direction: colors, content type, text overlay, aspect ratio]
- Why this will work: [1 sentence linking concept to specific audience psychology or platform behavior]

[Repeat for Ad Concepts 2-6, covering: 2 prospecting angles, 2 retargeting angles, 1 testimonial/social proof, 1 direct response/offer]

# MODULE 5: TESTING & OPTIMIZATION FRAMEWORK
**Creative Testing Protocol:**
- Testing variable hierarchy (what to test first, second, third — with rationale)
- Minimum spend per ad before making kill/scale decision: [$X or X days, specify by budget tier]
- Statistical confidence threshold before scaling a winner
- How to structure A/B tests in Meta without audience overlap contamination
- When to use Meta's built-in A/B test tool vs. manual split testing

**Weekly Optimization Checklist (automatable by AI agent):**
Day 1 (Monday): [Specific actions to review and thresholds to flag]
Day 3 (Wednesday): [Mid-week check — specific metrics and actions]
Day 7 (Sunday): [End-of-week — budget reallocations, creative rotation schedule]

**Scaling Decision Rules:**
- When to increase budget on a winning ad set: [specific ROAS/CPL threshold + stability days required]
- When to duplicate vs. increase budget in same ad set
- When to broaden audience vs. find new angles
- Warning signals that indicate you're hitting audience saturation

# MODULE 6: ATTRIBUTION & REPORTING SETUP
**Attribution Configuration:**
- Recommended attribution window for this business model (1-day click / 7-day click / 7-day click + 1-day view)
- Rationale for window choice based on sales cycle
- How to reconcile Meta-reported conversions vs. CRM/GA4 discrepancy
- CAPI implementation priority score (1-10) for this account and what event match quality score to target

**Reporting Dashboard — Weekly KPIs to Track:**
| Metric | Target | Alert If | Optimization Action |
|--------|--------|----------|---------------------|
| [Fill in 10 rows with platform-specific thresholds for this business type]

**North Star Metric for This Account:**
Define the single metric that best predicts profitable scaling for this specific business model, and why.

# CONSTRAINTS
- All recommendations must be executable in Meta Ads Manager today — no beta features without flagging availability
- Budget recommendations must work at the specified monthly budget — no "you need more budget" cop-outs
- If a recommendation requires CAPI or pixel setup to be effective, flag it but provide fallback
- Creative concepts must be producible with the assets described — no recommendations requiring assets not listed
- All copy must comply with Meta's advertising policies (no before/after claims, no discriminatory targeting language)

# OUTPUT FORMAT
Structure as a client-ready Meta Ads Strategy Brief. Use headers, tables, and numbered lists. Include a one-page Executive Summary at the top with: top 3 priorities for the first 30 days, expected performance trajectory (conservative / base / aggressive scenarios), and total estimated setup time.

## Example Input/Output

**Input:**
Company: Fintelo
Industry: B2B Fintech SaaS
Business Model: B2B SaaS
Product Description: AI-powered accounts payable automation that eliminates manual invoice processing for finance teams at mid-market companies ($50M-$500M revenue)
Price Point / ACV: $36,000 ACV
Sales Cycle: 90-day enterprise cycle, 3 stakeholders (CFO, Controller, IT)
Current Meta Spend: $0 — new account
Primary KPI: Demo bookings (MQLs)
Secondary KPI: CPL < $200
Competitors: Tipalti, Bill.com, Stampli
Creative Assets: 3 product screenshots, 1 explainer video (90 sec), 2 customer headshots (no quotes yet)
Pixel Status: Pixel only, no CAPI yet
Monthly Budget: $15,000

**Output (excerpt):**

---
**FINTELO META ADS STRATEGY BRIEF — Q2 2026**

**Executive Summary — First 30 Days:**
1. Install CAPI immediately — your pixel-only setup will miss ~35% of conversions post-iOS17; delay costs you optimization signal
2. Launch with 3 ad sets: 1 broad Advantage+ audience, 1 finance job title interest stack, 1 competitor keyword interest stack — all driving to a demo booking landing page
3. Creative priority: Test the explainer video as a 30-second cut (hook: "Your AP team processes 500 invoices/month by hand — here's the math on what that costs you") vs. a static carousel showing the before/after workflow

**Conservative scenario:** $180 CPL at month 3 after learning phase exits
**Base scenario:** $140 CPL by month 6 with CAPI installed and 3 creative winners identified
**Aggressive scenario:** $95 CPL at month 9 with full retargeting stack, lookalikes from 50+ demos booked, and Creative+ winner library of 12 ads

---

**MODULE 2: CAMPAIGN ARCHITECTURE**

| Layer | Objective | Budget | Bid Strategy |
|-------|-----------|--------|--------------|
| Cold Prospecting | Leads (demo form) | $10,500 (70%) | Highest Volume until 50 leads/week, then Cost Cap at $200 |
| Retargeting | Leads (demo form) | $3,000 (20%) | Cost Cap $150 — warmer audience justifies tighter cap |
| Lookalike (Month 2+) | Leads | $1,500 (10%) | Highest Volume — build signal first |

**Learning Phase Strategy:**
Start with 1 ad set per layer, minimum $350/day prospecting ad set to exit learning phase within 14 days (targeting 50 lead events/week). Do NOT split into multiple ad sets until you have 150+ demo events total.

---

**MODULE 4: CREATIVE BRIEF — Ad Concept 1: "CFO Math Attack"**
- Format: Single image (1:1 for feed, 9:16 crop for Stories)
- Funnel stage: Prospecting
- Psychological trigger: Loss aversion + authority
- Hook/Headline: "Your AP team is costing you $340K/year in manual processing"
- Primary text: "Finance teams at $100M companies spend an average of 22 minutes per invoice. At 500 invoices/month, that's 183 hours — or $28K/month — in labor cost alone. Fintelo automates 95% of that in 30 days. [See the ROI calculator →]"
- CTA: "Learn More" (drives to ROI calculator LP, which then offers demo)
- Visual brief: Dark navy background, large white "$340,000" in center, small red "wasted annually" subtext, Fintelo logo bottom right. No stock photos. Clean fintech aesthetic.
- Why this works: CFOs respond to specificity over vague efficiency claims. Anchoring to a concrete dollar figure triggers loss aversion and earns click-through from the right ICP.

---

## Success Metrics

**30-Day Benchmarks (New Account):**
- Exit learning phase on all active ad sets: Yes/No
- CPM within 20% of industry benchmark for B2B fintech ($18-$35): ✓
- Link CTR > 0.8% on cold audiences (B2B benchmarks are lower than B2C): ✓
- Lead form completion rate > 20% if using native Meta lead forms: ✓
- Demo show rate of leads from Meta > 40% (quality signal): ✓

**60-Day Benchmarks:**
- 3+ creative winners identified (defined as: CPL < target at 95% confidence): ✓
- Retargeting audiences > 1,000 people (minimum viable size): ✓
- Attribution discrepancy between Meta and CRM < 40% (install CAPI to close gap): ✓

**90-Day Benchmarks:**
- CPL trending toward target (not necessarily there yet): ✓
- First lookalike audiences launched from demo-booker seed: ✓
- Creative refresh cycle established (new ads every 3-4 weeks): ✓

**Underperformance Diagnosis Tree:**
- High CPM, low CTR → Audience too narrow or creative not resonating with this audience
- Good CTR, low lead CVR → Landing page problem (not ad problem — check LP separately)
- Good lead CVR, poor demo show rate → Lead quality problem (targeting too broad or offer attracts wrong persona)
- Good demo rate, high CAC → Scale constraints — audience saturating, need new creative angles or audiences

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/AI-Powered-LinkedIn-Ads-B2B-Demand-Generation-&-Pipeline-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/AI-Powered-Google-Ads-Search-Campaign-Performance-&-Conversion-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/AI-Powered-Always-On-B2B-Demand-Generation-Engine.md`
- `../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/AI-Powered-CTV-OTT-Streaming-TV-Advertising-Performance-Analytics-&-Intelligence-Engine.md`

## Integration Tips

**HubSpot:**
- Connect Meta Lead Ads natively via HubSpot's Meta integration (Settings → Marketing → Ad Tracking)
- Map Meta lead form fields to HubSpot contact properties; set Lead Source = "Meta Ads" and add UTM parameters as custom properties
- Create a HubSpot workflow: Meta MQL received → assign to SDR within 5 minutes → auto-enroll in 3-email nurture sequence while SDR reaches out
- Use HubSpot's Ad Attribution report to compare Meta's reported conversions against CRM-tracked contacts

**Salesforce:**
- Use Salesforce's Meta Ads connector (Marketing Cloud Advertising Studio) or a Zapier bridge for standard orgs
- Create Campaign Member records for every Meta lead; track Lead Source Detail = "Meta [Campaign Name]" for granular attribution
- Build a Salesforce report: Meta Leads by Month → Opportunity Created → Closed Won, to calculate true pipeline-to-CAC by audience segment

**Google Sheets / Looker Studio:**
- Use Meta Ads API (via Supermetrics, Porter, or direct API) to pull daily spend, impressions, link clicks, leads, and cost per lead into a master sheet
- Build a Looker Studio dashboard with: Spend by campaign, CPL trend (7-day rolling), Creative performance leaderboard (CTR ranked), Audience frequency heat map
- Set automated weekly email reports from Looker Studio to stakeholders every Monday at 8am

**Zapier Automation:**
- Trigger: New Meta Lead Form submission → Action: Create HubSpot/Salesforce contact + Send Slack notification to SDR channel + Add to Google Sheet performance log
- Trigger: Meta CPL exceeds threshold (via daily Sheets check + Zapier) → Action: Send Slack alert to media buyer with campaign name and recommended action

**Make (Integromat) AI Agent Loop:**
- Schedule a daily agent run: Pull Meta Ads Manager data via API → Run optimization analysis against benchmarks → Post recommended bid/budget changes to Slack for human approval → On approval, execute changes via Meta API
- This creates a human-in-the-loop AI media buying agent with full auditability

## Troubleshooting

**Problem 1: Ad account stuck in learning phase (>14 days)**
- Cause: Too many ad sets splitting conversion volume — Meta needs 50 events/week per ad set to exit learning
- Fix: Consolidate ad sets (merge 4 narrow ad sets into 1-2 broader ad sets); raise daily budget to hit event threshold faster; temporarily optimize for a higher-funnel event (e.g., Landing Page View instead of Lead) to accumulate signal, then switch down-funnel once learning exits

**Problem 2: High CPM with no improvement after creative refresh**
- Cause: Audience saturation — frequency > 4 in 7 days means you've exhausted your addressable audience at current targeting
- Fix: Expand audience (loosen age/interest restrictions or switch to Advantage+ audience); launch new creative with completely different format (if running images, switch to video); introduce a new audience segment to reset frequency; reduce budget temporarily to lower delivery pressure

**Problem 3: Meta reports 3x the conversions shown in CRM (attribution inflation)**
- Cause: Meta's default 7-day click + 1-day view attribution window double-counts conversions from users who converted through other channels; view-through attribution is especially problematic for B2B
- Fix: Switch attribution window to 7-day click only (removes view-through inflation); install Conversions API to improve event match quality (reduces Meta's need to model/estimate conversions); reconcile by comparing Meta "click-attributed" conversions only against UTM-tagged sessions in GA4; accept a 20-35% discrepancy as normal in multi-channel B2B environments

## Version History
- v1.0: Initial creation (auto-generated)
