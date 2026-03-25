# AI-Powered Product-Led Growth Strategy & Self-Serve Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** plg, product-led-growth, self-serve, b2b-saas, revenue-strategy, pql, freemium, go-to-market

## Overview
Designs and audits a full Product-Led Growth (PLG) motion—from freemium/trial architecture to PQL scoring to sales-assist handoff—enabling CMOs to systematically engineer viral, self-serve revenue with AI agents. Use this when transitioning from a sales-led model, stress-testing an existing PLG funnel, or building a PLG layer on top of an enterprise sales motion.

## Quick Copy-Paste Version

You are a PLG strategy consultant with deep expertise in B2B SaaS. Analyze and build a product-led growth strategy for the following company:

Company: [Your Company Name]
Product: [What your product does in 1-2 sentences]
Current GTM motion: [Sales-led / Marketing-led / Hybrid / Early PLG]
Current ARR: [e.g., $5M ARR]
ACV range: [e.g., $3K–$50K]
Target customer: [e.g., DevOps teams at mid-market SaaS companies]
Main competitors and their PLG approach: [e.g., Datadog (free tier), Grafana (open source)]

Build a complete PLG intelligence report with these sections:

1. PLG READINESS ASSESSMENT
   - Score PLG readiness across 5 dimensions: product virality (network effects, sharing), time-to-value, self-serve onboarding friction, freemium/trial economics, and sales-assist compatibility
   - Identify the top 3 blockers to PLG success at this company
   - Recommend: full PLG, PLG-assist, or sales-led with PLG features — and why

2. FREE TIER / TRIAL ARCHITECTURE
   - Design the freemium or free-trial model: what features to gate, usage limits, and the "aha moment" to engineer
   - Specify the "activation event" — the single action that correlates most strongly with paid conversion
   - Recommend trial duration, seat limits, data limits, and integration limits
   - Identify the 2–3 features that should stay paid-only to drive upgrade pressure

3. PRODUCT QUALIFIED LEAD (PQL) SCORING MODEL
   - Define the PQL threshold using usage signals (feature depth, session frequency, team expansion, API calls, data volume)
   - Build a tiered PQL scoring matrix: Cold PQL (score 1-40), Warm PQL (41-70), Hot PQL (71-100)
   - List the top 10 behavioral signals to track and their weight
   - Define the exact trigger conditions for a sales-assist alert

4. SELF-SERVE CONVERSION FUNNEL
   - Map the 6-stage self-serve funnel: Signup → Activation → Habit Formation → Expansion → Conversion → Advocacy
   - Identify drop-off risk at each stage and the in-product intervention to address it
   - Design the upgrade prompt strategy: contextual CTAs, paywall moments, and social proof triggers
   - Specify the email/in-app nurture sequence for free users by stage

5. PLG + SALES-ASSIST MOTION (HYBRID)
   - Define which user segments should go self-serve vs. get sales-assist vs. enterprise outbound
   - Design the handoff playbook: when CS/sales gets involved, what context they receive, and SLA by PQL tier
   - Build the "land and expand" motion: how a free user becomes a team license becomes an enterprise deal
   - Define the expansion triggers: seat growth, department expansion, API usage thresholds

6. VIRAL & NETWORK EFFECTS STRATEGY
   - Identify the strongest virality mechanism for this product (collaboration loops, output sharing, public embeds, referral programs, marketplace listings)
   - Design 1 viral loop with specific mechanic, trigger, and expected k-factor range
   - Recommend the invite/collaboration feature to build first for viral growth

7. PLG METRICS DASHBOARD
   - Define the 10 core PLG KPIs: activation rate, time-to-activation, free-to-paid conversion rate, PQL-to-close rate, viral coefficient, expansion MRR from self-serve, payback period for PLG vs. sales-led
   - Set benchmark targets for a company at this ARR stage
   - Identify the single most important leading indicator of PLG health

8. 90-DAY PLG LAUNCH ROADMAP
   - Week 1–4: Quick wins to implement immediately (no engineering required)
   - Week 5–8: Core PLG infrastructure (what to build, what to buy)
   - Week 9–12: Optimization loop and first PLG performance review

Output everything as a structured strategic brief ready for a CMO-to-CEO presentation.

## Advanced Customizable Version

ROLE: You are a world-class Product-Led Growth architect and revenue strategist. You have helped 12 B2B SaaS companies transition from sales-led to PLG or hybrid motions, including companies that grew from $5M to $50M ARR using self-serve channels. You combine product intuition, behavioral economics, and revenue operations expertise.

CONTEXT:
- Company: [Company Name]
- Founded: [Year]
- Current ARR: [$ Amount]
- ARR Growth Rate: [% YoY]
- ACV: [Average Contract Value]
- NRR: [Net Revenue Retention %]
- CAC (Sales-Led): [$ Amount]
- CAC Payback Period: [Months]
- Current GTM: [Sales-Led / Marketing-Led / Hybrid / Early PLG]
- Free Tier Exists: [Yes/No — describe if yes]
- Trial Exists: [Yes/No — describe terms if yes]
- Primary ICP: [Job title, company size, industry]
- Secondary ICP: [Optional]
- Product Category: [e.g., Observability, RevOps, CMS, Data Pipeline]
- Pricing Model: [Per seat / usage-based / flat / tiered]
- Competitors with PLG: [List them and describe their approach]
- Key Integration Ecosystem: [e.g., Slack, Salesforce, GitHub, AWS]
- Engineering Bandwidth for PLG: [Low / Medium / High]
- Board/Investor Pressure: [Growth / Efficiency / Both]

OBJECTIVE: Produce a complete PLG Strategy Intelligence Brief that a CMO can present to the board and hand to product + engineering to execute. Every recommendation must be specific, actionable, and tied to revenue impact.

CONSTRAINTS:
- Do not recommend generic PLG advice. Every recommendation must account for this company's ACV, sales motion, and competitive context.
- If ACV > $30K, always recommend PLG-assist (not pure self-serve) and explain the hybrid architecture.
- Ground all conversion benchmarks in real PLG SaaS data (e.g., Notion, Figma, Calendly, Datadog, Grafana, dbt Labs, Postman).
- Flag any PLG recommendation that requires >3 months of engineering — note it as Phase 2 or Phase 3.
- Include the "anti-patterns" — 3 PLG mistakes that commonly fail at this company's stage.

OUTPUT FORMAT: Structured brief with 8 sections (headers in ALL CAPS). Each section: executive summary (2–3 bullet points), detailed recommendation, implementation specifics, and success metric.

---

SECTION 1: PLG READINESS SCORE & GTM RECOMMENDATION

Evaluate PLG readiness across these 5 dimensions (score each 1–10):

A. PRODUCT VIRALITY
- Does the product create shareable outputs (reports, dashboards, embeds, templates)?
- Are there natural collaboration surfaces (multi-user workflows, @mentions, shared workspaces)?
- Is there a network effect (value increases with more users/connections)?
- Virality Score: [1-10]

B. TIME-TO-VALUE (TTV)
- Can a new user reach the "aha moment" in < 5 minutes without a sales call?
- Is there a pre-built template or sample data for instant value?
- TTV Score: [1-10]

C. SELF-SERVE ONBOARDING COMPLETENESS
- Can the product be configured without a human?
- Are there integration connectors that work via OAuth (no API key setup)?
- Is there an interactive product tour or guided setup?
- Onboarding Score: [1-10]

D. FREE TIER / TRIAL ECONOMICS
- Is there a natural usage limit that drives upgrade without blocking value?
- Can the company afford to give away meaningful value for free given CAC?
- Economics Score: [1-10]

E. SALES-ASSIST COMPATIBILITY
- Does the existing sales team have capacity to work PQLs?
- Is the CRM instrumented to receive product usage signals?
- Sales-Assist Score: [1-10]

COMPOSITE SCORE: [Average / 10]
GTM RECOMMENDATION: [Full PLG / PLG-Assist / Sales-Led with PLG Features]
PRIMARY RATIONALE: [2–3 sentences grounded in the company's ACV and competitive context]

---

SECTION 2: FREE TIER & TRIAL ARCHITECTURE

FREEMIUM vs. TRIAL DECISION:
- Freemium Model: Best when [conditions]. Recommended if [criteria met].
- Free Trial Model: Best when [conditions]. Recommended if [criteria met].
- Recommendation: [Which one and why for this company]

FREE TIER DESIGN (if applicable):
- Usage Limits: [Specific limits — e.g., "3 projects, 1 seat, 1,000 API calls/month, 30-day data retention"]
- Feature Gates: [Exact features that are free vs. paid — list 5 free, 5 paid-only]
- The "Aha Moment": [The single in-product event that correlates with retention — e.g., "User completes first dashboard and shares it with a teammate"]
- Time-to-Aha Target: < [X] minutes from signup

UPGRADE PRESSURE ARCHITECTURE:
- Soft Limit: [Notify user when approaching limit — e.g., "You've used 80% of your project slots"]
- Hard Limit: [What happens when limit is hit — e.g., "Read-only mode, no new projects"]
- Value Lock-In: [The feature or data that makes it painful to leave — e.g., "Historical analytics data only accessible in paid plan"]
- Viral Trigger: [The free action that exposes the product to new users — e.g., "Share report link"]

---

SECTION 3: PQL SCORING MODEL

BEHAVIORAL SIGNAL TAXONOMY:
Define signals in 4 categories:

1. DEPTH SIGNALS (product engagement quality)
   - [Signal 1]: Weight [%]
   - [Signal 2]: Weight [%]
   - [Signal 3]: Weight [%]

2. BREADTH SIGNALS (expansion indicators)
   - [Signal 4]: Weight [%]
   - [Signal 5]: Weight [%]
   - [Signal 6]: Weight [%]

3. FREQUENCY SIGNALS (habit formation)
   - [Signal 7]: Weight [%]
   - [Signal 8]: Weight [%]

4. INTENT SIGNALS (buying intent)
   - [Signal 9]: Weight [%] — e.g., viewed pricing page 2+ times
   - [Signal 10]: Weight [%] — e.g., attempted to use a paid feature

PQL SCORING MATRIX:
| Score Range | Tier | Action | Owner | SLA |
|-------------|------|--------|-------|-----|
| 0–40 | Cold PQL | Automated email nurture sequence | Marketing | 48hr |
| 41–70 | Warm PQL | CS outreach + in-app chat trigger | CS | 24hr |
| 71–85 | Hot PQL | SDR call + personalized email | Sales | 4hr |
| 86–100 | Sales-Ready PQL | AE immediate outreach | AE | 1hr |

NEGATIVE SIGNALS (reduce PQL score):
- [e.g., Only logged in once in 30 days]: -15 pts
- [e.g., Only admin, no end-user adoption]: -10 pts
- [e.g., Integration connected but no active data flow]: -20 pts

---

SECTION 4: SELF-SERVE CONVERSION FUNNEL

Map each funnel stage with:
- Stage definition
- Success metric (benchmark)
- Top drop-off reason
- AI-automated intervention

STAGE 1 — ACQUISITION (Traffic → Signup)
- Success Metric: Signup conversion rate [benchmark: 2–5% for B2B SaaS]
- Top Drop-Off: [Company-specific reason]
- Intervention: [Specific tactic — e.g., "Social proof wall on signup page showing logos of companies in their industry using the product"]

STAGE 2 — ACTIVATION (Signup → Aha Moment)
- Success Metric: Activation rate [benchmark: 25–40% in 7 days]
- Top Drop-Off: [Company-specific reason]
- Intervention: [e.g., "Interactive 3-minute guided setup flow triggered at signup that creates a pre-populated dashboard using the user's own data via OAuth"]

STAGE 3 — HABIT FORMATION (Aha Moment → Weekly Active User)
- Success Metric: D7 retention rate [benchmark: 30–50% for B2B tools]
- Top Drop-Off: [Company-specific reason]
- Intervention: [e.g., "Weekly digest email auto-generated by AI showing user's top insights from the week — personalized per account"]

STAGE 4 — EXPANSION (Single User → Multi-Seat)
- Success Metric: Teams with 2+ users at Day 30 [benchmark: 20–35%]
- Top Drop-Off: [Company-specific reason]
- Intervention: [e.g., "In-product collaboration prompt: 'This report would be more valuable with your manager — invite them (free)'"]

STAGE 5 — CONVERSION (Free → Paid)
- Success Metric: Free-to-paid conversion rate [benchmark: 2–8% for freemium; 15–25% for free trial]
- Top Drop-Off: [Company-specific reason]
- Intervention: [e.g., "Contextual paywall triggered when user attempts to export — shows ROI calculator based on their own usage data"]

STAGE 6 — ADVOCACY (Customer → Referring User)
- Success Metric: Viral coefficient k [benchmark: 0.3–0.7 for B2B SaaS]
- Top Drop-Off: [Company-specific reason]
- Intervention: [e.g., "Post-activation referral prompt with incentive: 'Invite a colleague and both of you get 2 months free'"]

---

SECTION 5: PLG + SALES-ASSIST HYBRID MOTION

SEGMENTATION FRAMEWORK:
| Segment | Criteria | Motion | Playbook |
|---------|----------|--------|----------|
| Self-Serve SMB | <50 employees, ACV < $5K | 100% automated | Email + in-app |
| PLG-Assist Mid-Market | 50–500 employees, ACV $5K–$30K | PQL-triggered sales | SDR + CS |
| Enterprise | >500 employees, ACV > $30K | Sales-led with PLG POC | AE + solution engineer |

LAND-AND-EXPAND PLAYBOOK:
1. LAND: [Describe the typical free user entry point — e.g., "Individual IC from engineering team signs up via self-serve"]
2. EXPAND TEAM: [Trigger for expansion — e.g., "IC shares dashboard with manager; manager invites 2 more teammates — team now at 4 users"]
3. HIT LIMIT: [Natural limit hit — e.g., "Team hits 5-seat limit or 10K event cap"]
4. SALES-ASSIST: [What CS/sales does — e.g., "CS sends personalized email: 'Your team is getting strong value — here's an ROI summary. Want to talk about a team plan?'"]
5. CLOSE: [Close motion — e.g., "AE runs 30-minute ROI review, proposes team license at $18K/yr, closes within 14 days"]
6. EXPAND DEPT: [Next expansion — e.g., "6 months post-close, AE uses product usage data showing 3 other teams accessing the tool to propose enterprise license"]

SALES-ASSIST HANDOFF SPEC:
When a Hot PQL is identified, the CRM record must auto-populate with:
- Total sessions (last 30 days)
- Features used (depth score)
- Number of team members invited
- Departments represented
- Integration connections active
- Last 3 in-product actions
- Predicted ACV based on company size + usage pattern

---

SECTION 6: VIRAL & NETWORK EFFECTS STRATEGY

VIRALITY MECHANISM AUDIT:
Evaluate these 5 virality types for fit:
1. Collaboration Virality (users invite others to work together) — Fit score: [H/M/L]
2. Output Virality (users share reports/results publicly) — Fit score: [H/M/L]
3. Embed Virality (product widget embedded on external sites) — Fit score: [H/M/L]
4. Marketplace Virality (templates/integrations others discover) — Fit score: [H/M/L]
5. Word-of-Mouth Virality (NPS-driven referral program) — Fit score: [H/M/L]

RECOMMENDED VIRAL LOOP:
Mechanic: [Specific mechanic — e.g., "When user publishes a dashboard, it generates a shareable link with product branding. Recipient can view for free but must sign up to edit or save"]
Trigger: [What triggers sharing — e.g., "User completes a report and clicks 'Share with stakeholder'"]
Expected k-factor: [e.g., 0.4 — meaning 40% of new signups invite at least 1 additional user]
Time to implement: [e.g., "2 sprints — requires shareable link feature and signup interception"]

PHASE 1 VIRAL FEATURE (no engineering required):
[e.g., "Add 'Powered by [Product]' badge to all exported PDFs/CSV emails with UTM-tracked URL. No engineering needed — update export template in Figma and push to design team"]

---

SECTION 7: PLG METRICS DASHBOARD

CORE 10 PLG KPIs:
| Metric | Formula | Benchmark (Seed→Series B) | Your Target |
|--------|---------|--------------------------|-------------|
| Activation Rate | Users hitting Aha Moment / Signups | 25–40% | [Target] |
| Time-to-Activation | Median minutes to Aha Moment | < 10 min | [Target] |
| Free-to-Paid Conversion | Paid converts / Total free users | 2–8% (freemium) / 15–25% (trial) | [Target] |
| PQL-to-Close Rate | Closed PQLs / Total PQLs | 20–35% | [Target] |
| Self-Serve MRR % | Self-serve MRR / Total MRR | 20–60% by Series B | [Target] |
| Viral Coefficient (k) | Invites sent × Invite-to-signup rate | 0.2–0.7 | [Target] |
| Product-Qualified Pipeline | PQL pipeline value | [ARR × 0.3 minimum] | [Target] |
| Expansion MRR (Self-Serve) | MRR expansion from PLG → paid | 15–30% of net new MRR | [Target] |
| PLG CAC | Total PLG program cost / PLG new logos | < 30% of sales-led CAC | [Target] |
| PLG Payback Period | PLG CAC / (ACV / 12) | < 6 months | [Target] |

NORTH STAR METRIC: [e.g., "Weekly teams hitting activation milestone" — the single metric that predicts revenue growth 60–90 days ahead]

LEADING INDICATORS (predict next quarter's PLG revenue):
1. [e.g., "Month-1 activation rate cohort — predicts free-to-paid conversion at Day 30"]
2. [e.g., "Invite-acceptance rate — predicts expansion and team-license revenue"]
3. [e.g., "PQL score velocity — rate of score increase in Days 7–14 predicts 30-day conversion"]

---

SECTION 8: 90-DAY PLG LAUNCH ROADMAP

WEEKS 1–4: FOUNDATION (NO ENGINEERING REQUIRED)
☐ Define and document the Aha Moment with product analytics data
☐ Audit current signup-to-activation flow; identify top 3 drop-off points
☐ Configure PQL scoring in existing product analytics tool (Mixpanel / Amplitude / Heap)
☐ Set up PQL → CRM sync via Zapier or native integration
☐ Launch 3-email activation sequence for new free signups
☐ Add product usage context to all CRM contact records
☐ Brief sales/CS on PLG motion and PQL handoff SLA

WEEKS 5–8: CORE PLG INFRASTRUCTURE
☐ Build activation onboarding checklist in-product (Pendo / Appcues / custom)
☐ Implement contextual paywall at top upgrade friction points
☐ Launch invite/collaboration feature (if not yet built)
☐ Set up in-app messaging for Hot PQL trigger (Intercom / Pendo)
☐ Configure weekly usage digest email (product analytics → email tool)
☐ Instrument viral loop #1 (shareable link or branded export)

WEEKS 9–12: OPTIMIZATION & FIRST REVIEW
☐ Run first PLG cohort analysis (Week 1 signups vs. activation vs. conversion)
☐ A/B test 2 paywall designs (contextual vs. feature-gate)
☐ Review PQL-to-close rate; recalibrate PQL thresholds based on conversion data
☐ Present PLG performance to board: activation rate, PQL pipeline, self-serve conversion
☐ Finalize Phase 2 roadmap based on data

PLG ANTI-PATTERNS TO AVOID:
1. [e.g., "Gating too aggressively: free tier so limited users can't reach the Aha Moment — they churn before ever converting"]
2. [e.g., "No PQL-to-sales handoff SLA: PLG creates pipeline but sales ignores it — PQL-to-close rate < 10%"]
3. [e.g., "Building virality before activation: optimizing invite flow when activation rate is still < 20% is wasted leverage — fix activation first"]

## Example Input/Output

**Example Input:**
- Company: Flowstate Analytics (B2B SaaS, data pipeline observability)
- ARR: $8M, growing 85% YoY
- ACV: $12K (range: $4K–$60K)
- Current GTM: Sales-led (SDR + AE team of 8)
- Free tier: None (14-day trial, requires credit card)
- ICP: Data engineers at Series B–D SaaS companies
- Competitors: Monte Carlo (enterprise, sales-led), Great Expectations (open source PLG), dbt (developer PLG)

**Example Output (Section 3 — PQL Model):**

BEHAVIORAL SIGNAL TAXONOMY FOR FLOWSTATE ANALYTICS:

DEPTH SIGNALS (40% weight)
- Connected first data source via OAuth: 15 pts
- Created first pipeline health dashboard: 12 pts
- Set up at least 1 alert/threshold: 13 pts

BREADTH SIGNALS (25% weight)
- Invited a second user (teammate): 15 pts
- Connected 3+ data sources: 10 pts

FREQUENCY SIGNALS (20% weight)
- Logged in 5+ times in 14-day trial: 12 pts
- Daily active for 7 consecutive days: 8 pts

INTENT SIGNALS (15% weight)
- Visited pricing page 2+ times: 10 pts
- Attempted to add a user past trial seat limit: 5 pts

PQL SCORING:
Hot PQL threshold: 71+ points
Trigger: SDR call + personalized email within 4 hours
CRM context auto-populated: data sources connected (3), dashboards created (2),
  alerts configured (1), invited teammate (1), visited pricing (2x), estimated
  pipeline volume based on source types → predicted ACV $14K

Sales note auto-generated: "Data engineer at Mosaic Software (Series C, 180 employees).
Connected Fivetran + Snowflake + dbt sources. Built 2 dashboards, set up 3 alerts.
Invited their data team lead. Visited pricing twice. High activation signal — 
likely evaluating for team use. Recommended approach: ROI angle on pipeline
downtime cost prevention."

## Success Metrics

- **Activation Rate**: ≥30% of free/trial signups reach the defined Aha Moment within 7 days
- **Free-to-Paid Conversion**: ≥5% (freemium) or ≥20% (free trial) within 30 days
- **PQL-to-Close Rate**: ≥25% of Hot PQLs converted to paid within 45 days
- **PLG CAC**: < 40% of sales-led CAC within 6 months of PLG launch
- **Self-Serve MRR Contribution**: ≥15% of net new MRR from PLG channel within 12 months
- **Viral Coefficient**: k ≥ 0.3 (meaning each new user generates ≥0.3 additional signups)
- **Time-to-Activation**: Median < 10 minutes from first login to Aha Moment
- **NPS of PLG Converts**: ≥45 (PLG converts tend to be more product-educated and higher NPS)

## Related Prompts

- [`../../01_CMO-&-Leadership/Strategy-&-Planning/Marketing-Sales-Revenue-Alignment-&-SLA-Engine.md`](../../01_CMO-&-Leadership/Strategy-&-Planning/Marketing-Sales-Revenue-Alignment-&-SLA-Engine.md)
- [`../../01_CMO-&-Leadership/Strategy-&-Planning/Marketing-Channel-Mix-Strategy-Engine.md`](../../01_CMO-&-Leadership/Strategy-&-Planning/Marketing-Channel-Mix-Strategy-Engine.md)
- [`../../02_Product-Marketing/Go-To-Market/`](../../02_Product-Marketing/Go-To-Market/)
- [`../../05_Analytics-&-Performance/Funnel-Conversion/`](../../05_Analytics-&-Performance/Funnel-Conversion/)

## Integration Tips

- **Amplitude / Mixpanel / Heap**: Define the Aha Moment as a custom event; build the PQL scoring model as a computed trait or user property; export PQL scores to Segment for downstream routing
- **HubSpot**: Use Custom Behavioral Events to log PQL score milestones; build a PLG Enrollment Workflow triggered at PQL ≥ 71 that assigns an SDR task and populates a PLG deal in the pipeline
- **Salesforce**: Create a PLG Score field on the Lead object synced from Segment or Amplitude via MadKudu or Hull; build a triggered task for PLG reps with pre-populated email template using merge fields from usage data
- **Intercom**: Configure behavioral triggers to show in-app messages at key drop-off points (e.g., if user has not connected a data source after 3 sessions, trigger "Need help connecting? Book 15 min with our team" banner)
- **Pendo / Appcues**: Build the activation checklist as a guided flow; use feature tagging to map behavioral signals to PQL dimensions automatically
- **Zapier**: Connect your product analytics tool to CRM using a PLG Zap: "When PQL score crosses 71 in Amplitude → Create or update Lead in HubSpot → Create SDR task → Send Slack notification to PLG rep"
- **Notion**: Create a PLG Strategy workspace using the output of Section 8 (90-day roadmap) as a project database with owner, due date, and status fields

## Troubleshooting

**Problem: Activation rate is < 15% despite having a free tier.**
Fix: The Aha Moment is likely defined wrong (too early, before real value) or too far (requires too many setup steps). Run a cohort analysis comparing users who converted to paid vs. churned free users — find the divergence point. Redesign onboarding so 80% of users hit that event in the first session. Often the fix is pre-populating data (sample datasets, templates) rather than building new features.

**Problem: Hot PQLs aren't converting — PQL-to-close rate < 10%.**
Fix: Either the PQL threshold is miscalibrated (scoring noise, not signal) or the sales-assist motion is broken (no SLA, wrong rep, generic outreach). Audit the last 20 closed PLG deals — what signals did they share? Recalibrate PQL scoring to weight those signals higher. Fix outreach: sales reps must open with specific product usage context ("I saw you connected your Snowflake instance and built 3 dashboards") not generic "just following up."

**Problem: Freemium is cannibalizing sales-led deals — enterprise prospects are starting free instead of booking demos.**
Fix: This is a segmentation problem, not a PLG problem. Add company size and domain enrichment at signup (Clearbit, 6sense, Bombora). If a signup matches your enterprise ICP (>500 employees, target vertical), route them directly to an AE within 1 hour — do not let them self-serve. The free tier is for SMB/mid-market. Protect your enterprise pipeline with a clear "Talk to Sales" prompt on the signup page for large accounts.

## Version History
- v1.0: Initial creation (auto-generated)
