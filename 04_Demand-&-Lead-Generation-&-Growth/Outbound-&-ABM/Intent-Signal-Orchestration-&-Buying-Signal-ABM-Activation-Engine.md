# Intent Signal Orchestration & Buying Signal ABM Activation Engine - AI-Powered B2B Intent Data Playbook for Pipeline Generation

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** abm, intent-data, b2b, demand-gen, outbound, personalization, 6sense, bombora, pipeline, automation, orchestration

## Overview
Transforms raw buying intent signals (6sense, Bombora, G2, LinkedIn, website behavior, job postings, technographic changes) into fully orchestrated, multi-channel ABM campaigns that reach target accounts at the moment of highest purchase readiness. Use this when you want to stop guessing which accounts to target and start activating outbound only when data says an account is in-market.

## Quick Copy-Paste Version

You are a B2B demand generation strategist specializing in intent-driven ABM. Your job is to design a complete intent signal orchestration system for [Your Company] that automatically detects when target accounts are in-market and activates personalized, multi-channel outreach before competitors do.

Company: [Your Company Name]
Product: [What you sell and the core problem it solves]
ICP: [Target account profile — industry, size, tech stack, job titles of buyers]
Average deal size: [ACV]
Sales cycle length: [Typical weeks from first touch to close]
Current intent data sources: [6sense / Bombora / G2 Intent / LinkedIn Sales Navigator / Website data / None yet]
CRM: [Salesforce / HubSpot / Other]
Outbound channels available: [Email / LinkedIn / Paid Ads / Phone / Direct Mail]

Deliver:
1. Intent signal taxonomy: the 8–12 buying signals that most reliably predict purchase intent for your product category, ranked by signal strength
2. Account scoring model: a 0–100 intent score combining signal types, recency, and account fit
3. Playbook trigger matrix: which outbound sequences activate at which intent score thresholds
4. Personalization rules: how to customize messaging for each signal type detected
5. Channel orchestration sequence: the exact multi-channel cadence for a high-intent account over 21 days
6. Measurement framework: how to attribute pipeline to intent-driven campaigns

Write this as an operational playbook a RevOps team can implement in 30 days.

## Advanced Customizable Version

ROLE: You are a Revenue Operations Architect and ABM Strategist with deep expertise in B2B intent data platforms (6sense, Bombora, TechTarget Priority Engine, G2 Buyer Intent, LinkedIn Sales Insights), marketing automation (HubSpot, Marketo, Pardot), and sales engagement platforms (Outreach, Salesloft, Apollo). You understand the full intent signal ecosystem — how third-party intent aggregates behavioral data across the web, how first-party signals reveal account interest on your own properties, and how to synthesize multiple weak signals into a high-confidence buying indicator. You have built intent-to-pipeline programs that generate 3–5x higher conversion rates than cold outbound.

CONTEXT:
Company: [COMPANY NAME]
Product/Service: [PRODUCT — be specific: "project management software for construction companies" not just "project management software"]
Business Model: [B2B SaaS / Professional Services / Manufacturing / Other]
ICP Firmographic Profile:
  - Industries: [List target industries]
  - Company size: [Employee count or revenue range]
  - Geography: [US / EMEA / Global]
  - Tech stack signals: [Tools they use that indicate fit — e.g., "uses Salesforce," "has HubSpot," "running on AWS"]
Buying Committee: [All personas involved in the purchase — e.g., "VP of Operations (economic buyer), IT Director (technical buyer), Operations Manager (champion), CFO (financial approver)"]
Average Contract Value: [$X ACV]
Sales Cycle: [X weeks typical]
Current Pipeline Problem: [e.g., "SDRs are prospecting cold with low connect rates," "we have accounts in our CRM that have gone dark," "we're missing in-market accounts that are buying from competitors"]
Intent Data Currently Available: [List what you have or "none — recommend what to buy"]
CRM Platform: [Salesforce / HubSpot / other]
Marketing Automation: [Marketo / HubSpot / Pardot / ActiveCampaign / other]
Sales Engagement: [Outreach / Salesloft / Apollo / Groove / none]
Paid Advertising Channels: [LinkedIn Ads / Google / Meta / Programmatic / none]
Monthly Budget for Intent-Driven Programs: [$X or "to be determined — include ROI justification"]
Current Outbound Volume: [SDR capacity — e.g., "4 SDRs sending 50 sequences/week each"]

OBJECTIVE: Design a complete Intent Signal Orchestration System that automatically detects when ICP accounts are in an active buying cycle, scores them based on combined signal strength, and triggers personalized multi-channel outreach sequences — all without manual SDR research. The output must include enough specificity that a RevOps engineer can build the workflow in HubSpot/Salesforce within 30 days.

DELIVERABLES:

1. INTENT SIGNAL TAXONOMY & SIGNAL STRENGTH SCORING
   Map every meaningful buying signal for your product category into a structured taxonomy:

   TIER 1 — HIGH-CONFIDENCE SIGNALS (Direct Purchase Intent)
   These signals indicate an account is actively evaluating solutions in your category right now. Weight: 25–40 points each in your scoring model.

   For each Tier 1 signal, define:
   - Signal name and source (e.g., "G2 Category Page Views — Source: G2 Buyer Intent")
   - What it means: exact behavior this signal captures
   - Lag time: how recently must this signal have fired to be actionable (e.g., "within 7 days")
   - Data delivery method: how it arrives in your system (e.g., "API to Salesforce," "CSV upload weekly," "native HubSpot integration")
   - False positive rate: how often this signal fires without real purchase intent (helps calibrate score weight)

   Common Tier 1 Signals to assess for your product:
   - Third-party intent surge: account consuming 3x+ their baseline content on category topics (Bombora / 6sense / TechTarget)
   - G2 product page views: account contacts or IP addresses viewing your G2 profile or comparing you to competitors
   - Category evaluation page views: account visiting your /pricing, /compare, /vs-competitor, or /demo pages 2+ times in 7 days
   - Champion job change: a known champion at a current customer or warm prospect changes jobs to a new company in your ICP — the #1 highest-converting signal in B2B
   - Competitor contract expiry signal: account's existing contract with a competitor is approaching renewal (inferred from contract data providers or job posts referencing "evaluating alternatives")
   - Trial activation or freemium upsell signal: PLG accounts whose usage indicates upgrade readiness (if applicable)
   - RFP / tender publication: account publishes a formal RFP in your category (source: bidding platforms, procurement databases)

   TIER 2 — MEDIUM-CONFIDENCE SIGNALS (Research & Awareness Intent)
   These signals indicate an account is researching your problem space but has not reached active evaluation. Weight: 10–20 points each.

   Common Tier 2 Signals:
   - Blog/educational content consumption: account IPs reading 3+ educational posts on your site about the problem category
   - LinkedIn engagement: personas at target accounts liking/commenting on your company posts or your team's thought leadership
   - Webinar/event registration: contact from target account registers for your webinar or downloads a top-of-funnel resource
   - Technology adoption signal: account installs or removes a technology adjacent to your product (source: BuiltWith, HG Insights, Datanyze)
   - Hiring signal: account posts jobs for roles that indicate they're building capability in your product's domain (e.g., a company posting for "Head of Revenue Operations" signals RevOps tool buying intent)
   - Executive change: new CXO or VP joins an ICP account — new leaders typically change vendor relationships within 90 days
   - Funding event: account raises a new funding round — Series B/C companies typically expand their tech stack within 60 days of funding
   - Expansion/growth signal: account opens new offices, announces partnerships, or posts significant headcount growth on LinkedIn

   TIER 3 — LOW-CONFIDENCE SIGNALS (Passive Fit Indicators)
   These signals indicate an account fits your ICP profile but shows no active intent. Weight: 3–8 points each.
   
   Examples: company in target industry, matches employee headcount range, uses complementary technology, headquartered in target geography, has been previously engaged (email opened, attended past event)

   SIGNAL COMBINATION RULES:
   Define the logic for how signals compound:
   - "If Tier 1 signal fires → score jumps to minimum 60 regardless of fit score"
   - "If 2 Tier 1 signals fire within 14 days → score floors at 80 (Priority 1 account)"
   - "Tier 2 signals compound: 3 Tier 2 signals in 30 days = treated as 1 Tier 1 signal"
   - "Signal decay: all signals lose 50% of their score weight after 21 days, 100% after 60 days"

2. ACCOUNT INTENT SCORE MODEL (0–100)
   Build the composite scoring formula:

   SCORE COMPONENTS:
   A. Fit Score (30% of total):
      Based on firmographic and technographic match to ICP. Score 0–30.
      - Industry match: [+15 / +8 / +0 depending on tier]
      - Size match: [+10 / +5 / +0]
      - Tech stack match: [+5 per matching technology, max +10]
      - Geography match: [+5 / +0]

   B. Intent Score (50% of total):
      Sum of all active intent signals, capped at 50.
      - Tier 1 signals: [25–40 points each, describe specific value for each]
      - Tier 2 signals: [10–20 points each]
      - Tier 3 signals: [3–8 points each]
      - Signal decay applied

   C. Relationship Score (20% of total):
      Measures depth of existing relationship with account. Score 0–20.
      - Known contact in CRM: +5
      - Contact has been previously engaged (opened email, attended event): +5
      - Contact has 2-way conversation history: +7
      - Champion identified and active: +10
      - Account previously lost or churned: -10

   SCORE THRESHOLDS AND PRIORITY TIERS:
   | Score Range | Tier | Label | Action |
   |-------------|------|-------|--------|
   | 80–100 | P1 | 🔥 Buying Now | Immediate SDR + AE joint outreach; all channels activate within 24 hours |
   | 60–79 | P2 | ⚡ High Intent | SDR sequence starts within 48 hours; LinkedIn ads + retargeting activate |
   | 40–59 | P3 | 👀 Researching | Automated nurture sequence; SDR review weekly; LinkedIn ads only |
   | 20–39 | P4 | 🌱 Early Stage | Marketing nurture only; appear in retargeting; SDR checks quarterly |
   | 0–19 | P5 | 💤 Dormant | No active outreach; monitor for signal changes |

3. PLAYBOOK TRIGGER MATRIX
   For each priority tier, define the exact automated workflow:

   P1 TRIGGER PLAYBOOK — "BUYING NOW" (Score 80–100)
   Trigger: Account reaches score 80+ or fires a single Category-Match Tier 1 signal

   IMMEDIATE ACTIONS (0–4 hours):
   - CRM Task: Create high-priority task for assigned SDR + AE pair; include "INTENT ALERT" tag
   - Research Package: Auto-generate AI research brief on the account including: recent news, LinkedIn activity of key contacts, tech stack changes, reason for high score (which signals fired)
   - Slack Alert: Send automated Slack message to SDR + AE with research brief summary and direct CRM link
   - LinkedIn Ads: Add account to P1 LinkedIn Matched Audience — activate personalized ad creative relevant to detected signal
   - Retargeting: Activate account-based retargeting on all channels at maximum bid

   DAY 1 ACTIONS (SDR-executed, AI-written content):
   - Email 1 (SDR-personalized): Reference the specific intent signal naturally without revealing surveillance. Template: "[Contact name], saw [trigger: e.g., 'you're evaluating [category] solutions' / 'congrats on the Series B' / 'welcome to [company] — wanted to reach out']. [1-sentence value prop tied to signal]. [Specific proof point: customer name + outcome]. [Single clear ask: 15-minute call]."
   - LinkedIn Connection Request: Personalized note from SDR referencing the same signal context
   - AE Research: AE reviews account and identifies if any executive-level relationships exist (warm intro path)

   DAY 3 ACTIONS:
   - Email 2: Value-add email — send relevant case study (match to account's industry), ROI calculator, or relevant blog post. No direct ask.
   - LinkedIn InMail: If connection not accepted, send InMail with compressed version of email 1

   DAY 7 ACTIONS:
   - Email 3: Social proof email — 3 customers similar to this account + specific outcomes. Direct ask: demo booking link.
   - Phone call attempt (if SDR has capacity): 30-second voicemail script using intent signal context
   - Gifting trigger (if ACV > $50K and no response): Activate Sendoso or Postal physical touch — personalized item relevant to their industry

   DAY 14 ACTIONS:
   - Email 4: "Break-up" email with genuine no-pressure close. Offer: self-serve content (demo video, pricing guide) as alternative to call.
   - SDR + AE sync: If no response after 14 days on a P1 account, AE attempts executive outreach (CEO/VP to VP outreach)

   DAY 21 ACTIONS:
   - Email 5: Final email from AE (VP-level sender) to economic buyer persona if available. Subject: "[Company] + [Their Company]: Worth 15 minutes?"
   - Move to P2 nurture if no response; re-escalate immediately if score rises again

   P2 TRIGGER PLAYBOOK — "HIGH INTENT" (Score 60–79)
   [Define 14-day, 4-touch sequence with similar detail level]
   
   Key difference from P1: SDR-only (no AE involvement until a meeting is booked); no direct mail; 5-day gaps between touches; lighter personalization

   P3 TRIGGER PLAYBOOK — "RESEARCHING" (Score 40–59)
   [Define automated 30-day nurture sequence]
   
   Key difference: Fully automated (no manual SDR touches until score rises); focus on educational content; LinkedIn ads and retargeting only paid channels; goal is to move account to P2 within 45 days

4. PERSONALIZATION RULES BY SIGNAL TYPE
   For each detected intent signal, define the messaging angle that should dominate outreach:

   | Signal Detected | Messaging Angle | Proof Point Type | CTA |
   |-----------------|-----------------|------------------|-----|
   | G2 profile view (comparing to Competitor X) | Competitive displacement messaging — lead with "Why companies switch from [Competitor X] to [Your Product]" | Customer who switched from Competitor X + quantified improvement | Schedule a migration briefing |
   | Job change — champion from customer | Relationship continuation — "Saw you moved to [New Company] — congrats. Wanted to reach out as you settle in" | Results at previous company where they were a champion | Quick intro call |
   | Hiring for [relevant role] | "We help companies like yours [specific outcome] so you can [do what the job posting describes] faster/cheaper/better" | Companies who achieved the hiring goal using your product | ROI analysis tailored to headcount growth |
   | Funding announcement | Congratulate + connect to scale narrative — "New capital usually means new infrastructure needs" | Customers at same funding stage + what they built with you | Growth planning conversation |
   | Tech stack change (added adjacent tool) | Integration/ecosystem play — "[New Tool] + [Your Product] is a common combo for [outcome]. We have a native integration" | Integration case study | Integration demo |
   | Contract renewal approaching (competitor) | Timing-based urgency — "Evaluation season for [category] is a good time to compare your current ROI" | Total cost of ownership comparison | ROI comparison analysis |
   | New executive hire (CXO/VP) | Change moment play — "New [Title] often means reevaluating the [category] stack. Here's what others in your role do in the first 90 days" | New leader success story | Strategy conversation (not product demo) |
   | High intent surge (Bombora/6sense) | Problem-aware educational lead — do NOT reveal you have intent data; write as if reaching out because they match your ICP profile | Industry benchmark data or relevant research | Problem discussion, not product pitch |

5. CHANNEL ORCHESTRATION SEQUENCE (21-DAY P1 ACCOUNT EXAMPLE)
   Full timeline for a P1 account with no prior relationship:

   | Day | Channel | Action | Owner | Content Type |
   |-----|---------|--------|-------|-------------|
   | 0 (trigger) | LinkedIn Ads | Add to matched audience; activate signal-relevant creative | Marketing (automated) | Programmatic ad |
   | 0 | Retargeting | All channels retargeting activated at 2x bid cap | Marketing (automated) | Display/social ads |
   | 1 | Email | Personalized email to primary contact (champion persona) | SDR (AI-drafted, SDR reviewed) | Signal-personalized cold email |
   | 1 | LinkedIn | Connection request to primary contact and 1 adjacent contact | SDR | Personalized connection note |
   | 3 | Email | Value-add email with case study or relevant asset | SDR (automated with asset selection logic) | Nurture email |
   | 3 | LinkedIn | Like or comment on target contact's recent LinkedIn post | SDR | Engagement (authentic — no pitch) |
   | 5 | Phone | Voicemail if connected; note attempt in CRM if no answer | SDR | 30-second voicemail script |
   | 7 | Email | Social proof email (3 similar customers + outcomes) | SDR | Proof email |
   | 7 | LinkedIn | InMail if connection not yet accepted | SDR | Compressed cold email version |
   | 10 | Direct Mail | Trigger Sendoso send if ACV > $50K and no response | Marketing (automated via Sendoso API) | Personalized physical gift |
   | 14 | Email | AE-sent email to economic buyer persona (different contact from SDR target) | AE | Executive-to-executive approach |
   | 14 | LinkedIn Ads | Rotate to new creative (proof/ROI-focused vs. awareness) | Marketing | Ad creative rotation |
   | 17 | Phone | Second call attempt | SDR or AE | Voicemail + email same day |
   | 21 | Email | Final email from AE; offer self-serve content as graceful exit | AE | Break-up email |
   | 21 | Score review | If still P1 score but no response, AE escalates to AE's VP for peer-to-peer outreach | AE + AE manager | Executive escalation |

6. MEASUREMENT FRAMEWORK & ROI ATTRIBUTION
   Build the reporting infrastructure to prove intent-driven programs outperform cold outbound:

   A. Campaign-Level Metrics
   - Intent-to-pipeline conversion rate: % of P1/P2 accounts that convert to an open opportunity (benchmark: P1 = 15–25%, industry leading; P2 = 8–15%)
   - Signal-to-contact speed: Average hours from intent signal detected to first outreach touch (target: < 4 hours for P1)
   - Multi-touch response rate: % of accounts that respond to the 21-day P1 sequence (benchmark: 8–15% for well-personalized intent-driven sequences vs. 1–3% for cold outbound)
   - Average time to opportunity: Days from intent signal detected to opportunity created (intent-driven should be 40–60% faster than cold outbound)
   - Pipeline velocity: Compare deal velocity (days from opportunity to close) for intent-sourced vs. cold-outbound-sourced opportunities

   B. Signal Accuracy Metrics (Validate Your Scoring Model)
   - Signal-to-close correlation: Track which specific Tier 1 signals have the highest win rates (refine score weights quarterly)
   - False positive rate per signal: % of P1 triggers that produce zero engagement in 21 days (high false positive = signal needs de-weighting)
   - Signal decay validation: Is 21-day decay appropriate? Test 14-day vs 28-day windows using cohort analysis
   - Score threshold calibration: Monthly review — what % of P1 accounts convert to pipeline? If < 10%, lower the threshold; if > 30%, threshold may be too high

   C. Revenue Attribution Model
   - First-touch attribution: Assign full credit to the intent signal and the channel that generated first response
   - Multi-touch linear attribution: Credit all touches proportionally (use for understanding channel contribution)
   - Pipeline sourced by intent programs: Track in CRM using campaign source tags — "Intent-P1," "Intent-P2," "Intent-Nurture"
   - Cost per pipeline dollar: Total spend on intent data licenses + SDR time + ad spend ÷ pipeline generated

   D. Monthly Reporting Dashboard (Recommended Metrics)
   Build in Salesforce/HubSpot + Looker Studio or Tableau:
   - Intent Funnel: Accounts Scored → P1/P2 Triggered → Engaged → Opportunity Created → Closed Won
   - Intent Data ROI: Pipeline generated / Intent program cost (target: 5–10x ROI within 6 months)
   - Signal Performance Table: Each signal type → trigger count → pipeline sourced → win rate → average ACV
   - SDR Performance by Intent Tier: Response rate / meeting rate / pipeline conversion segmented by P1 vs P2 vs cold outbound (proves intent program value to sales leadership)

## Example Input/Output

**Input Example:**
Company: Luminary (B2B SaaS — workforce scheduling and labor optimization for multi-location retail and hospitality companies)
ICP: Operations Directors and HR VPs at retail/hospitality brands with 500–10,000 employees, 20+ locations
Average ACV: $85,000
Sales cycle: 4–6 months
Intent data: 6sense (existing), considering adding Bombora
CRM: Salesforce
Current problem: SDRs are booking meetings but 60% of deals stall after discovery — wrong accounts getting time

**Output Example (excerpt):**

**TOP TIER 1 SIGNALS FOR LUMINARY:**

| Signal | Source | Score Weight | Trigger Logic | Why It Works for Luminary |
|--------|--------|-------------|---------------|--------------------------|
| Job posting: "Workforce Management Specialist" or "Scheduling System Implementation" | LinkedIn Jobs API / Predictleads | +35 points | Account posts 2+ relevant jobs in 30 days | Indicates they're building out WFM capability — exactly when they're evaluating platforms |
| G2 profile comparison view: Luminary vs. Kronos/UKG/Infor | G2 Buyer Intent | +38 points | Any view of comparison pages | Actively evaluating vendors; highest-intent signal |
| 6sense "Buying Stage" reaches Active Evaluation | 6sense | +40 points | Stage change detected | Direct purchase intent signal from behavioral data aggregation |
| New Operations VP or VP HR hired | LinkedIn Sales Navigator | +28 points | LinkedIn title change detected | New leaders change systems; 70% of enterprise software deals happen in first 90 days of new exec tenure |
| Competitor contract renewal approaching (UKG / Kronos) | Vendr / G2 + firmographic correlation | +32 points | Inferred from contract data or job posting mentioning "evaluating alternatives" | Classic timing play — catch them during renewal evaluation window |

**P1 ACCOUNT ACTIVATION — FIRST 48 HOURS (for account that hits 6sense Active Evaluation + Job Posting signals simultaneously):**

Day 0, Hour 1 (automated):
- Salesforce: New high-priority task created for SDR Marcus Chen + AE Jennifer Okafor
- Research brief auto-generated: "Fieldstone Hospitality Group — PRIORITY ALERT. Signals: 6sense Active Evaluation (workforce management category), 3 new job postings for WFM roles in last 14 days. ICP fit: 847 locations, 12,000 employees, currently running legacy UKG system (from BuiltWith). Key contacts identified: Dana Whitfield (VP Operations, likely champion), Robert Saenz (Chief People Officer, economic buyer). Recent news: $180M Series D announced Nov 2025 — scale play underway."
- Slack message to Marcus + Jennifer: "🔥 P1 INTENT ALERT — Fieldstone Hospitality. 6sense just flagged Active Evaluation + 3 WFM job posts. Dana Whitfield (VP Ops) is your champion target. ACV opportunity: estimated $220K+ (847 locations at standard pricing). CRM: [link]. Research brief: [link]. SLA: first outreach within 4 hours."

Day 1, Email 1 from Marcus (SDR):
Subject: Fieldstone scaling WFM — a few thoughts

"Dana, saw Fieldstone is expanding operations — hiring a WFM Specialist and two scheduling coordinators [linked to job posts naturally: "saw you're building out the team"]. Companies at your scale often hit a ceiling where manual scheduling and legacy systems create real labor cost leakage across locations.

Operators with 800+ locations working with Luminary are cutting scheduling errors by 34% and labor cost variance by 18% — the difference shows up fast at scale.

Worth a 15-minute conversation to see if the math makes sense for Fieldstone? Here's my calendar: [link]"

**LUMINARY SIGNAL ACCURACY BASELINE (Month 1 targets):**
- P1 accounts → meeting rate: 18% (vs. current cold outbound rate of 4%)
- P1 accounts → opportunity conversion: 22% (vs. current 8%)
- Time from signal to outreach: < 2 hours
- False positive rate (P1 triggers with zero engagement): < 35%

## Success Metrics

- **Signal-to-meeting conversion rate:** % of P1 accounts that book a meeting within the 21-day sequence. Strong: > 12%. Excellent: > 20%. Benchmark cold outbound: 2–5%.
- **Intent-sourced pipeline as % of total pipeline:** Target 30–50% of total pipeline influenced by intent signals within 6 months of program launch. Measures program scale.
- **Average deal velocity (days to close):** Intent-sourced deals should close 30–50% faster than cold-outbound-sourced deals — measure by CRM opportunity source tag at close.
- **SDR efficiency ratio:** Meetings booked per SDR per week using intent-prioritized queue vs. cold outbound (target: 2–3x improvement with intent data — fewer dials, higher conversion).
- **Intent data ROI:** Total pipeline generated from intent-triggered campaigns ÷ total intent program cost (data licenses + tech stack + SDR time allocated). Target: 5–10x ROI within 90 days of full operation.
- **Score model accuracy:** Quarterly calibration — what % of P1 accounts convert to opportunity? If below 10%, scoring model needs threshold adjustment. Above 25% means you're leaving P2 accounts underserved.

## Related Prompts
- [`Account-Based-Experience-ABX-Personalization-Engine.md`](./Account-Based-Experience-ABX-Personalization-Engine.md) — Once intent is detected, personalize the full buyer experience across channels
- [`Account-Based-Marketing-Automation.md`](./Account-Based-Marketing-Automation.md) — Build the broader ABM program infrastructure this engine plugs into
- [`../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/CRM-Revenue-Operations-Intelligence-Engine.md`](../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/CRM-Revenue-Operations-Intelligence-Engine.md) — Set up the CRM data architecture that makes intent signal routing possible
- [`../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/Marketing-Data-Enrichment-&-Lead-Intelligence-Engine.md`](../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/Marketing-Data-Enrichment-&-Lead-Intelligence-Engine.md) — Enrich account data to maximize signal interpretation accuracy

## Integration Tips

- **6sense / Bombora → Salesforce:** Use native integrations or the Fivetran connector to sync intent scores and signals as custom Account fields in Salesforce. Create a workflow rule: when "Intent Score" field updates to 80+, create a high-priority task for the account owner and trigger the P1 Salesforce cadence in your sales engagement tool.
- **HubSpot:** Use the 6sense HubSpot integration (native) to sync buying stage and intent topics to HubSpot Company properties. Build workflows: Company "Buying Stage" = "Active Evaluation" → enroll in P1 Sequence + add to LinkedIn P1 audience + notify SDR via internal notification + assign task.
- **Outreach / Salesloft:** Create intent-specific sequences (separate from cold outbound sequences) that are triggered programmatically by CRM workflow when an account hits score thresholds. Never manually enroll P1 accounts — manual enrollment creates 4–8 hour delays that cost meetings.
- **LinkedIn Campaign Manager:** Create a "P1 Intent Accounts" and "P2 Intent Accounts" LinkedIn Matched Audience using company list uploads from Salesforce (automate via Zapier: when Salesforce Account "Intent Tier" = P1 → add to LinkedIn CSV → upload to Campaign Manager weekly). Run different creative per tier — P1 gets proof/comparison ads; P2 gets educational/problem-aware ads.
- **Sendoso / Postal (Direct Mail):** Create a webhook trigger: when a P1 account reaches Day 10 with zero response (tracked in Outreach/Salesloft activity data) → trigger Sendoso API to send a personalized gift. Use Salesforce opportunity ACV to set budget thresholds: ACV > $50K = $75 gift; ACV > $100K = $150 gift; ACV > $250K = $300 gift.
- **Slack:** Build a RevOps Slack bot (via Zapier or native Salesforce for Slack integration) that posts to a shared #intent-alerts channel when P1 accounts trigger. Include: company name, signal summary, estimated ACV, assigned SDR + AE, and direct CRM link. SDR and AE both tag themselves to confirm receipt — creates accountability without requiring daily CRM review.
- **Google Sheets + Looker Studio:** Build a weekly Intent Program Performance dashboard in Looker Studio connected to Salesforce: rows = intent tier (P1/P2/P3), columns = triggered this week / engaged / meeting booked / opportunity created / pipeline value. Share with marketing + sales leadership weekly to prove program ROI and secure ongoing investment.

## Troubleshooting

- **Problem:** Intent signals are firing frequently but SDR outreach is generating very low response rates (< 3%).
  **Solution:** The personalization isn't matching the signal well enough. Audit your email templates: are SDRs explicitly (or implicitly) referencing the intent signal in the opening line? If email 1 reads like a generic cold email, intent data is wasted. Implement strict template rules: email 1 MUST reference a specific, observable trigger (job posting, recent news, funding, LinkedIn activity) — never a generic opener like "Hope this finds you well." Also check signal timing: if outreach is happening 5+ days after the signal fires, purchase intent may have already moved elsewhere. Target < 4-hour response to Tier 1 signals.

- **Problem:** High P1 meeting rates but deals are stalling — intent data is generating meetings but not pipeline.
  **Solution:** Intent signals are getting the right meetings, but discovery and qualification are misaligned. The intent signal tells you WHEN an account is looking — it doesn't guarantee they're a fit. Audit the 10 most recent intent-triggered meetings that stalled: were they actually ICP accounts, or did intent data flag accounts that match your category keywords but don't match your ICP fit requirements? Add a 30-point minimum Fit Score floor to your P1 trigger logic so only high-fit accounts get P1 treatment. Also review if SDRs are properly diagnosing the intent signal during discovery calls — knowing "they're evaluating workforce management tools because they just raised funding and are opening 200 locations" changes the discovery question structure entirely.

- **Problem:** Intent data costs $4K–$8K/month and leadership wants to see clear ROI attribution before renewing.
  **Solution:** Build a pipeline contribution report comparing two cohorts — accounts that received intent-triggered outreach vs. accounts that were worked via cold outbound with no intent data (matched by ICP profile, company size, and time period). Measure: meetings per account touched, opportunity conversion rate, average ACV, and days to close. Intent-driven programs at mature deployments typically show 3–5x better meeting conversion and 40–60% faster cycle time — if yours doesn't, the issue is execution (signal-to-outreach speed, personalization quality, or SDR capacity) not data quality. Present the cohort analysis to leadership as an A/B test result, not anecdotal evidence.

## Version History
- v1.0: Initial creation (auto-generated)
