# AI-Powered B2B Multi-Signal Account Engagement Score Architecture & Revenue Activation Intelligence Engine - Build the Single Score That Tells You Which Accounts Are Ready to Buy

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, abm, account-engagement-scoring, intent-data, revenue-intelligence, saas, 6sense, bombora, salesforce, hubspot, marketing-analytics, pipeline-prioritization

## Overview
Designs a unified, multi-signal Account Engagement Score (AES) that aggregates marketing touchpoints, sales interactions, product usage, and third-party intent signals into a single composite score per account — then automatically triggers the right sales and marketing actions at each score threshold. Use this when your ABM program lacks a systematic way to decide which accounts deserve SDR outreach vs. paid acceleration vs. executive engagement, or when account engagement data lives in five different systems and nobody can see the full picture.

## Quick Copy-Paste Version

You are a senior B2B revenue analytics architect specializing in account-based marketing measurement. I need you to design a complete multi-signal Account Engagement Scoring (AES) system for my company.

My context:
- Company type: [B2B SaaS / Enterprise Software / Professional Services]
- Total addressable accounts in CRM: [number]
- ABM tiers: [e.g., Tier 1: 50 named accounts, Tier 2: 300 target accounts, Tier 3: 2,000 ICP-fit accounts]
- ACV: [$X]
- Sales cycle: [X days average]
- CRM: [Salesforce / HubSpot]
- Marketing automation: [Marketo / HubSpot / Pardot]
- Intent data provider(s): [6sense / Bombora / G2 / TechTarget / None]
- ABM advertising: [Demandbase / 6sense / LinkedIn / None]
- Product telemetry available: [Yes — Amplitude/Mixpanel/Pendo / No — not a PLG product]
- Current biggest gap: [e.g., "We only score individual leads, not accounts," "Intent data sits in a separate system from marketing engagement," "Sales ignores our lead scores because they don't trust them"]

Please deliver:

1. **Signal taxonomy** — Categorize all engagement signals into 4 layers (First-Party Marketing, First-Party Sales, First-Party Product, Third-Party Intent) with 5-7 specific signals per layer and their relative weight rationale

2. **Scoring architecture** — A composite AES formula that combines all layers into a single 0–100 score per account, with decay logic (how quickly signals lose weight over time) and boost triggers (events that spike scores immediately)

3. **Score band definitions** — Define 5 score bands (Dormant / Aware / Engaged / Active / In-Market) with the specific score ranges, behavioral definitions, and the exact marketing and sales plays triggered at each band

4. **Data model** — The CRM field structure needed to store and calculate the AES in Salesforce or HubSpot, including custom objects, rollup fields, and automation rules

5. **Activation playbook** — For each score band, specify the automated action triggered within 24 hours of a score threshold crossing, the SDR/AE notification format, and the marketing program that runs in parallel

6. **Calibration method** — How to back-test the scoring model against closed-won deals to validate that high AES scores actually correlate with revenue

Provide specific formulas, not principles. I need something I can implement in a CRM admin session, not a whitepaper.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Operations and Marketing Analytics with 12+ years of B2B SaaS experience at companies from $20M to $500M ARR. You have deep expertise in account-based measurement, CRM data architecture (Salesforce and HubSpot), marketing attribution, intent data platforms (6sense, Bombora, TechTarget, G2 Buyer Intent), conversation intelligence (Gong, Chorus), and building scoring models that SDRs and AEs actually trust and act on. You understand the technical implementation — specifically how to build custom scoring models in Salesforce using Process Builder, Flow, or Apex triggers, or in HubSpot using custom score properties and workflows.

---

COMPANY PROFILE:
- Company: [Company Name]
- Stage / ARR: [Series B / $30M ARR | Series C / $85M ARR | Growth / $200M ARR]
- Business model: [SaaS / Usage-based / Hybrid / Services]
- ACV: [$X] | Average sales cycle: [X days] | Win rate: [X%]
- Sales motion: [Inbound-led / Outbound-led / PLG+Sales / Pure Enterprise]
- ICP: [Target company profile: size, industry, tech stack, buyer persona(s)]

---

ABM PROGRAM ARCHITECTURE:
- ABM tiers and account counts:
  - Tier 1 (1:1, named accounts): [X accounts — Fortune 500 / specific named list]
  - Tier 2 (1:few, segment-based): [X accounts — e.g., Series B+ SaaS, $50M-$500M rev]
  - Tier 3 (1:many, programmatic): [X accounts — full ICP TAM]
- Current TAL size: [X accounts total across all tiers]
- ICP scoring criteria in use: [Firmographic fit score / None / Describe your ICP model]

---

SIGNAL INVENTORY (check all that apply and note the system they live in):

FIRST-PARTY MARKETING SIGNALS:
- [ ] Website visits (account-level via IP deanonymization) — Tool: [Clearbit/6sense/RB2B/None]
- [ ] Specific page visits (pricing, competitor comparison, ROI calculator) — CMS: [WordPress/Webflow/Other]
- [ ] Content asset downloads (whitepapers, case studies, ROI tools) — MAP: [Marketo/HubSpot/Pardot]
- [ ] Webinar registrations and attendance — Platform: [ON24/Zoom Events/Goldcast/Other]
- [ ] Email engagement (opens, clicks, replies) — MAP above
- [ ] Paid ad engagement (LinkedIn, G2, display impressions/clicks) — [LinkedIn/Demandbase/6sense/Other]
- [ ] Event attendance (conferences, field events, executive dinners) — CRM events object
- [ ] Chatbot conversations — [Drift/Qualified/Other]
- [ ] Free trial signups or demo requests — CRM/MAP

FIRST-PARTY SALES SIGNALS:
- [ ] Outbound email reply rates — [Outreach/Salesloft/Apollo]
- [ ] Call connects and call outcomes — [Gong/Chorus/SFDC Tasks]
- [ ] Demo completed — CRM stage/activity
- [ ] Multi-threading (3+ contacts engaged at same account) — CRM contacts
- [ ] Pricing discussion — Conversation intelligence keyword flag
- [ ] Champion identified and active — CRM custom field
- [ ] Procurement/legal contacted — CRM stage or custom field

FIRST-PARTY PRODUCT SIGNALS (PLG only):
- [ ] Free trial activation — Product analytics tool
- [ ] Feature adoption depth (activated X of Y core features) — [Pendo/Mixpanel/Amplitude]
- [ ] Seat expansion within free tier — Product analytics
- [ ] API key generated or integration connected — Engineering events
- [ ] Power user behavior (daily active usage exceeding threshold) — Product analytics

THIRD-PARTY INTENT SIGNALS:
- [ ] Intent data: researching your category keywords — [Bombora/TechTarget/Demandbase]
- [ ] Competitor research activity — [6sense/G2 Buyer Intent/Other]
- [ ] G2 product profile visits — [G2 Buyer Intent]
- [ ] Job postings indicating buying intent (new RevOps hire, technology budget keywords) — [Bombora/SeekOut/Other]
- [ ] Funding events, M&A activity, leadership changes — [Crunchbase/Apollo/ZoomInfo]
- [ ] Technology install changes (added/dropped competitive technology) — [HG Insights/Bombora technographic]

---

SCORING DESIGN PARAMETERS:
- Score range: [0–100 or custom range]
- Score update frequency: [Real-time / Daily batch / Weekly]
- Decay half-life preference: [Aggressive: 7-day half-life / Moderate: 14-day / Conservative: 30-day]
- Historical lookback window: [30 / 60 / 90 days of signal history]
- Weight philosophy: [Recency-weighted / Volume-weighted / Conversion-rate-weighted]
- Multi-contact aggregation method: [Max score of any contact / Sum of all contact scores / Custom weighted average]

---

ACTIVATION REQUIREMENTS:
- CRM for activation: [Salesforce / HubSpot]
- SDR notification channel: [Slack / Email / CRM task queue / Salesloft/Outreach sequence trigger]
- Sales territory/routing rules: [Round-robin / Territory-based / Account-ownership-based]
- Marketing orchestration layer: [Marketo / HubSpot / 6sense orchestration / Demandbase]
- Budget available for high-score account programs: [$X per account per month or "unknown"]

---

CALIBRATION DATA:
- Number of closed-won deals in past 12 months: [X]
- Do you have historical engagement data for closed-won accounts? [Yes / Partial / No]
- Average engagement activity count pre-close for won deals (if known): [X touchpoints]
- Fastest deal cycle time observed: [X days] | Slowest: [X days]

---

DELIVERABLES:

1. SIGNAL TAXONOMY & WEIGHTING MATRIX
Build a complete signal library organized into 4 tiers (First-Party Marketing, First-Party Sales, First-Party Product, Third-Party Intent). For each signal, specify:
- Signal name and source system
- Raw point value (the base score addition per occurrence)
- Max contribution cap (maximum this signal category can contribute to total AES)
- Decay function (linear decay over X days to zero, or half-life exponential decay)
- Boost multiplier conditions (e.g., "if pricing page visit AND intent data spike: 3x multiplier")
- Implementation: the exact CRM/MAP rule that captures and records this signal

2. COMPOSITE SCORE FORMULA
Write the actual mathematical formula:
- AES = (First-Party Marketing Score × W₁) + (First-Party Sales Score × W₂) + (Product Score × W₃) + (Third-Party Intent Score × W₄)
- Where W₁ + W₂ + W₃ + W₄ = 1.0
- Provide recommended weights for 3 company archetypes: Pure Inbound SaaS, Outbound-Led Enterprise, PLG+Sales
- Include the time-decay formula applied to each raw signal point value
- Specify the normalization method to map raw scores to 0–100

3. SCORE BAND DEFINITIONS & ACTIVATION PLAYS

| Band | Score Range | Behavioral Definition | SDR Action | AE Action | Marketing Play |
|------|-------------|----------------------|------------|-----------|----------------|
| Dormant | 0–15 | No meaningful engagement in 90 days | None | None | Nurture sequence, 1x/month |
| Aware | 16–30 | Single-channel engagement, low intent | Soft monitor — no outreach | None | LinkedIn ads, retargeting |
| Engaged | 31–50 | Multi-channel engagement, no clear intent spike | Add to SDR watch list | None | Content acceleration, event invite |
| Active | 51–70 | High engagement + at least 1 intent signal | Priority outreach within 48h | Executive alert | Multi-touch campaign, direct mail |
| In-Market | 71–100 | Consistent high engagement + multiple intent signals | Immediate outreach within 24h; multi-thread | Direct AE involvement + exec sponsor | Full-court press: custom assets, exec dinner, competitive play |

Expand each row with: specific trigger criteria, the automated notification message sent to SDR/AE (template), and the Salesforce/HubSpot workflow that fires.

4. CRM DATA ARCHITECTURE
Provide the complete technical implementation specification:

FOR SALESFORCE:
- New custom fields needed on Account object: [list each with data type, formula or automation source]
- Custom Score Object design (if historical score tracking required): fields, relationships, record trigger
- Flow/Process Builder automation rules: trigger events → score calculation → notification logic
- Reports and dashboard components: the 5 essential views for RevOps, SDR managers, and CMO

FOR HUBSPOT:
- Custom Score properties (Account-level): list each property with calculation methodology
- Workflow triggers: property change events → enrollment → action sequences
- Integration requirements: webhook setup for third-party intent data ingestion
- Dashboard: list report types in custom HubSpot reports for AES monitoring

5. SCORE VELOCITY ANALYTICS
Define score velocity (week-over-week score change) as a secondary signal:
- How to calculate and store score delta in CRM
- Velocity thresholds that override absolute score for prioritization (e.g., "Account scored 35 but +22 points in 7 days → treat as Active")
- Early warning detection: accounts with fast score decline after demo → at-risk deal alert

6. MODEL CALIBRATION & CONTINUOUS IMPROVEMENT
- Back-testing methodology: how to validate the model against 12 months of closed-won/lost data
- The 3 statistical metrics to track (Score Predictive Power: correlation between AES and win rate; Score Distribution: % of accounts in each band; Lead Time Accuracy: days from "In-Market" score to demo request)
- Quarterly model review process: which signals to reweight based on new conversion data
- A/B testing approach for scoring model changes (shadow scoring — run new model in parallel before replacing)

7. MULTI-STAKEHOLDER SCORE AGGREGATION
- How to handle accounts with 5 contacts at different individual engagement levels
- The weighted contact roll-up formula (champion contact score weighted higher than unknown contacts)
- How to detect "buying committee formation" as a distinct engagement event (3+ contacts from same account engage within 14-day window)

---

CONSTRAINTS:
- All automation must be buildable by a marketing operations professional with CRM admin skills — no custom code required unless you explicitly flag it as "engineering-required"
- Include specific field API names for Salesforce (e.g., Account.Account_Engagement_Score__c) and HubSpot property internal names
- Every formula must be mathematically precise — no vague "weight by importance" statements
- Activation plays must be specific and executable, not strategic frameworks

## Example Input/Output

**Input Example:**
Company: Veridian Security (Series C, $72M ARR)
Product: Identity governance & access management SaaS for enterprise
ACV: $180,000 | Sales cycle: 127 days avg | Win rate: 23%
Sales motion: Outbound-led enterprise, 12 AEs + 18 SDRs
ICP: CISOs and VP-IT Security at 2,500–25,000 employee enterprises
ABM tiers: T1=75 named accounts (Fortune 1000), T2=600 accounts, T3=4,200 ICP-fit
CRM: Salesforce | MAP: Marketo | Intent: Bombora + G2 Buyer Intent
Signals available: Website (Clearbit Reveal), email, webinars, LinkedIn ads, call data (Gong), 
  demo requests, Bombora intent (IAM/Zero Trust/Identity Security topics), G2 profile visits
No PLG component
Gap: "We have all this data in 5 systems but SDRs just work off MQL alerts — they don't know 
  which accounts are heating up before they form-fill."

**Output Example (excerpt):**

**Account Engagement Score Formula for Veridian Security:**

AES = (FM_Score × 0.35) + (FS_Score × 0.40) + (TPI_Score × 0.25)
[No product score — non-PLG company]

FM_Score (First-Party Marketing, max 100 points before normalization):
- Pricing page visit (identified account): +20 pts, 14-day half-life
- ROI Calculator engagement: +25 pts, 21-day half-life
- Webinar attendance: +15 pts, 30-day half-life
- Case study download (security/IAM): +12 pts, 30-day half-life
- LinkedIn ad click (Tier 1/2 account): +8 pts, 7-day half-life
- Email click: +5 pts, 7-day half-life | Email reply: +15 pts, 14-day half-life
- Blog visit (2+ pages, identified): +6 pts, 7-day half-life
FM_CAP: 100 raw points before normalization

FS_Score (First-Party Sales, max 100 points):
- Call connect + positive outcome (Gong "interested" sentiment): +30 pts, 21-day half-life
- Demo completed: +40 pts, 30-day half-life
- Multi-threading (3+ contacts engaged): +20 pts, 30-day half-life
- Pricing discussed (Gong keyword flag): +35 pts, 21-day half-life
- Legal/procurement contact added to CRM: +25 pts, 30-day half-life
FS_CAP: 100 raw points

TPI_Score (Third-Party Intent, max 100 points):
- Bombora surge (IAM/Zero Trust topics, surge score >60): +30 pts, 14-day half-life
- G2 Identity Governance category page visit: +40 pts, 7-day half-life  
- G2 Veridian profile visit: +50 pts, 7-day half-life
- CISO/VP Security job posting (identity/IAM requirements): +15 pts, 30-day half-life
TPI_CAP: 100 raw points

SCORE BAND ACTIVATION EXAMPLE:
When AES crosses 71 ("In-Market"):
→ Salesforce Flow fires: creates Priority Task for Account Owner SDR (due: same day)
→ Slack message to SDR + AE: "@[SDR] @[AE] — [Account Name] just hit In-Market (AES: 74). 
   Signals: G2 profile visit (2 contacts, today), Bombora IAM surge (72), pricing page visit 
   (yesterday). Multi-thread: [Contact 1], [Contact 2] are engaged. Recommended: 
   personal video from AE + exec dinner invite. [Link to account in SFDC]"
→ Marketo program triggered: Account added to "In-Market Direct Mail" campaign, Sendoso 
   gift ($75 personalized book + handwritten note) scheduled for 3-day delivery
→ LinkedIn Campaign Manager: Account added to custom audience for "Executive Roundtable" 
   sponsored content (CISO-targeted creative)

## Success Metrics

- **Score Predictive Power:** AES ≥71 ("In-Market") accounts should convert to demo at 3–5× the rate of non-scored accounts within 60 days — measure this monthly
- **SDR Activation Rate:** % of AES threshold-crossing accounts that receive SDR outreach within the SLA window (target: 90%+ for Active/In-Market)
- **Pipeline from AES-Triggered Plays:** Track "AES-Triggered" as a pipeline source in CRM; target 25–35% of new pipeline influenced by AES-triggered activation
- **Score Distribution Health:** Less than 5% of accounts should be In-Market at any time; if >10%, scoring is too sensitive. Less than 60% should be Dormant; if >80%, scoring model needs recalibration
- **Model Calibration Score (MCS):** Back-test against closed-won deals — target 75%+ of closed-won accounts should have reached Active/In-Market status 30+ days before close

## Related Prompts

- [ABM Buying Committee Engagement Scoring](AI-Powered-ABM-Buying-Committee-Engagement-Scoring-&-Multi-Stakeholder-Deal-Velocity-Intelligence-Engine.md)
- [ABM Target Account List Quality & ICP Fit Score Optimization](AI-Powered-ABM-Target-Account-List-Quality-&-ICP-Fit-Score-Optimization-Intelligence-Engine.md)
- [Lead Scoring Model Optimization & Predictive Buying Signal Intelligence](../Lead-Quality-&-Conversion-Analytics/Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md)
- [ABM Intent Data ROI Measurement & Signal Quality Analytics](AI-Powered-B2B-ABM-Intent-Data-ROI-Measurement-&-Signal-Quality-Analytics-Intelligence-Engine.md)

## Integration Tips

**Salesforce Implementation:**
- Create `Account_Engagement_Score__c` (Number, 3,0) and `AES_Band__c` (Picklist: Dormant/Aware/Engaged/Active/In-Market) fields on Account object
- Use Salesforce Flow (Record-Triggered, fires on score change) to send Slack notifications via HTTP callout to Slack webhook URL
- Use Campaign Member Status to feed marketing signal points into a rollup summary field on Account
- Connect Bombora via native Salesforce integration or Zapier for intent score ingestion to `Bombora_Surge_Score__c` field

**HubSpot Implementation:**
- Use HubSpot's native Score property (Account-level) for AES — configure individual actions and weights in the Score property editor
- Use Workflows with "Company property changes" trigger to fire when AES score crosses band thresholds
- Install Bombora's HubSpot native app for automatic intent data sync to Company properties
- Connect G2 Buyer Intent via Zapier (G2 Profile View → HubSpot Company Property update)

**6sense Integration:**
- 6sense's account score can serve as your third-party intent layer directly — map 6sense's "In-Market" stage to your TPI_Score input
- Enable 6sense's native Salesforce/HubSpot sync to push buying stage, intent topic, and engagement data as Account fields
- Use 6sense orchestration to trigger ad suppression for In-Market accounts (shift spend to direct mail/executive programs)

**Gong Integration:**
- Use Gong's CRM sync to push call outcome scores and keyword trigger flags (pricing, security, procurement) as Salesforce Activity fields
- Set up Gong trackers for high-value conversation signals: "budget approved," "legal review," "board presentation," "competitor mentioned" — these feed directly into FS_Score

**Slack Notification Template:**
🔥 *In-Market Alert* — [Account Name] | AES: [Score]

📊 *Signals (last 14 days):*
• [Signal 1]: [e.g., "Pricing page: 3 visits by 2 contacts"]
• [Signal 2]: [e.g., "Bombora IAM surge: 78 (↑23 vs. last week)"]
• [Signal 3]: [e.g., "G2 category page: 1 contact visit today"]

👥 *Engaged contacts:* [Contact 1 — Title], [Contact 2 — Title]
📅 *Score velocity:* +[X] pts in 7 days

⚡ *Actions triggered:*
✅ Priority task created for @[SDR]
✅ Sendoso gift queued (3-day delivery)
✅ Added to LinkedIn exec roundtable audience

[View Account in Salesforce →]

## Troubleshooting

**Problem:** Score distribution is heavily skewed — 80%+ of accounts are Dormant and <1% ever reach Active.
**Solution:** Your signal weights are too conservative. Audit which signals are actually firing by running a report of "accounts with any AES-contributing activity in last 60 days." If <20% of your TAM has ANY signals, your data pipeline has gaps — check that website deanonymization is working, that Marketo/HubSpot activities are rolling up to Account level, and that intent data is syncing correctly. Reduce point thresholds by 30% and re-run calibration.

**Problem:** SDRs are ignoring AES alerts because "the score goes up and down randomly and doesn't mean anything."
**Solution:** This is a signal decay problem. If scores are volatile, your decay half-lives are too short (scores spike and collapse within days). Extend all half-lives by 50%, implement a 7-day moving average score (displayed alongside current score), and show SDRs the trend line, not just the current score. Also: run a closed-won analysis — if AES doesn't correlate with win rates, present that data to sales so they see why the model needs recalibration, not abandonment.

**Problem:** Score is dominated by one signal type — e.g., all "In-Market" accounts got there only from intent data spikes with no real sales engagement.
**Solution:** Implement minimum thresholds: an account cannot reach "In-Market" unless it has non-zero scores from at least 2 of the 3 signal categories (or 3 of 4 if PLG). Add a "Signal Diversity" gate: if 90%+ of an account's total AES comes from a single category, cap the band at "Active" regardless of absolute score.

## Version History
- v1.0: Initial creation (auto-generated)
