# AI-Powered B2B SaaS Marketing-SDR Co-Attribution Analytics & Collaborative Pipeline Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, saas, analytics, attribution, sdr, sales-development, pipeline, revenue-operations, marketing-sales-alignment, demand-waterfall

## Overview
Deploys an AI agent to build a fair, data-driven co-attribution model that accurately credits both marketing touches and SDR prospecting activity for pipeline generated — resolving the most common source of marketing-sales friction. Use this when marketing and sales development are fighting over pipeline credit, when leaders can't agree on "who sourced the deal," or when you need a board-ready pipeline attribution framework that incentivizes collaboration over internal competition.

## Quick Copy-Paste Version

You are a senior revenue operations analyst and B2B marketing attribution expert. Build a Marketing-SDR Co-Attribution model for my company and produce a pipeline attribution analysis that gives fair credit to both marketing campaigns and sales development outreach.

My company:
- Product: [What it does]
- ACV: [$X average contract value]
- Sales cycle length: [X days average]
- Sales motion: [Inbound-led / Outbound-led / Hybrid]
- SDR team size: [X SDRs]
- CRM: [Salesforce / HubSpot / other]
- Marketing automation: [Marketo / HubSpot / Pardot / other]

Pipeline data (for a representative sample of 20-50 recently closed deals, describe the pattern):
- Deals that had 3+ marketing touches before first SDR contact: [X%]
- Deals sourced purely through SDR cold outreach with no prior marketing touch: [X%]
- Deals where marketing nurture re-engaged a previously cold prospect: [X%]
- Average number of marketing touches before SDR engagement: [X]
- Average time from first marketing touch to first SDR touch: [X days]

Deliver:

1. CO-ATTRIBUTION FRAMEWORK DESIGN — Recommend the optimal co-attribution model for my business. For each of the following, explain the logic, when it applies, and the revenue operations setup required:
- Marketing Sourced / SDR Influenced (marketing created first intent signal, SDR capitalized on it)
- SDR Sourced / Marketing Influenced (SDR broke through cold, marketing accelerated to close)
- Co-Sourced (both contributed meaningfully in the same buying window, neither could have succeeded alone)
- Channel Sourced (partner/event/community — neither marketing campaign nor SDR directly responsible)
Score each pipeline dollar using weighted attribution: [suggest weights based on my business model].

2. LEADING INDICATOR SCORECARD — Build a weekly Marketing-SDR collaboration scorecard with 8-10 KPIs that incentivize both teams to work together rather than fight over credit:
- Speed-to-SDR-follow-up on marketing-qualified accounts (hours from MQA signal to first SDR touch)
- Marketing campaign-to-SDR coverage rate (what % of accounts in active campaigns have SDR coverage)
- SDR open rate on marketing-primed accounts vs. cold accounts (measures marketing warm-up value)
- Conversion rate: marketing-touched + SDR-contacted vs. SDR-only or marketing-only
- Deal velocity: co-attributed pipeline vs. single-source pipeline (days to close)
- Pipeline coverage ratio: marketing-generated MQAs in SDR territory vs. SDR outbound target accounts
- Revenue attribution agreement rate: % of closed-won deals where marketing and SDR agree on the source story

3. ATTRIBUTION DISPUTE RESOLUTION PROTOCOL — Define clear rules for when attribution is contested:
- Who owns the attribution decision when marketing and SDR disagree?
- What CRM data is definitive (timestamps, contact records, campaign membership dates)?
- How do you handle situations where SDR contacted a prospect 18 months before the marketing campaign that ultimately re-engaged them?
- What happens to attribution when a champion job-changes to a new company and brings the SDR relationship with them?
- How do you attribute inbound demo requests that come in during an active SDR outbound sequence?

4. COLLABORATIVE PIPELINE PLAN — Produce a joint marketing-SDR operating rhythm for the next quarter that turns co-attribution from a metric into a behavior:
- Weekly 1:1 cadence: what marketing shares with SDR pod leads, what SDR leads share back
- Account prioritization meetings: how marketing and SDR align on which accounts to target this week
- Campaign-SDR playbook handoff: what SDR needs from marketing to capitalize on campaign-generated intent
- Feedback loop: how SDRs surface buyer objections back to marketing in real time

5. BOARD-READY ATTRIBUTION NARRATIVE — Write a 3-paragraph executive summary for the quarterly business review that explains the company's pipeline attribution clearly to a CEO or CFO who doesn't know the difference between MQL and SDR:
- Where pipeline is coming from (marketing vs. SDR vs. co-attributed vs. partner)
- What this tells us about our go-to-market efficiency
- What we are optimizing for next quarter

Format: Numbered sections with subsections. Include specific metrics, formulas, and CRM field names where relevant. All frameworks must work in Salesforce or HubSpot without custom engineering.

---

## Advanced Customizable Version

ROLE: You are a Principal Revenue Operations Architect and B2B Marketing Attribution Specialist with 12+ years building GTM measurement systems for B2B SaaS companies from Series A through IPO. You have deep expertise in demand waterfall design, Salesforce revenue operations, and the organizational dynamics between marketing and sales development teams.

CONTEXT:
Company: [Company Name]
Stage: [Series A / B / C / Public]
ARR: [$X]
ACV: [$X average, $X median]
Sales motion: [Inbound-led / Outbound-led / Hybrid — describe the primary motion]
SDR structure: [Inbound SDRs vs. Outbound SDRs — same team or separate? How many of each?]
Marketing-SDR relationship: [Describe current state: collaborative, siloed, or actively conflicted]
Primary attribution dispute: [Describe the specific disagreement causing the most friction — e.g., "SDRs claim all pipeline because they make the first call; marketing claims credit for all MQL-sourced deals even when SDR outreach pre-dated the MQL"]
CRM setup: [Salesforce / HubSpot, describe key objects: Lead, Contact, Account, Opportunity, Campaign Member]
Marketing automation: [Name and describe key objects used for tracking touches]
Current attribution model: [First touch / Last touch / Linear / Custom — and why it's failing]

PIPELINE SAMPLE — Analyze the following representative closed-won deals and extract the co-attribution pattern:
[Paste 10-20 deal summaries or describe the data: include first marketing touch date, first SDR touch date, deal stage progression, close date, ACV, and who the SDR and marketing programs involved were]

ORGANIZATIONAL CONSTRAINTS:
- [e.g., SDR team is compensated on SQL creation, not revenue — creates incentive to claim all credit]
- [e.g., Marketing is measured on MQL volume, not pipeline — creates incentive to over-attribute to campaign]
- [e.g., SDR and marketing report to different executives — VP Sales vs. CMO — who have different P&Ls]
- [e.g., Company is preparing for Series C fundraise and needs clean attribution for investor diligence]

OBJECTIVE: Design and implement a Marketing-SDR Co-Attribution Analytics System that:
1. Accurately reflects the contribution of both teams to pipeline and revenue
2. Creates shared incentives that reward collaboration over internal competition
3. Can be maintained in the existing CRM without custom code
4. Produces board-ready reporting that a non-technical CFO can understand
5. Resolves the specific attribution dispute described above

DELIVERABLES:

━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SECTION 1: CO-ATTRIBUTION MODEL ARCHITECTURE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━

1.1 ATTRIBUTION TAXONOMY
Define five mutually exclusive pipeline source categories with precise CRM-based definitions:

A. MARKETING SOURCED (MS)
Definition: Prospect engaged with a marketing asset or campaign and raised their hand (inbound) before any SDR outreach. SDR's role was to qualify and convert an already-interested prospect.
CRM criteria: [Specify exact conditions — e.g., "Contact/Lead had Campaign Member record with 'Responded' status dated before the Opportunity Creation Date AND before first SDR Activity logged"]
Weight to marketing: [Recommend % — e.g., 80%]
Weight to SDR: [Recommend % — e.g., 20%]
SDR credit rationale: [Why SDR gets partial credit even in MS scenarios — e.g., speed-to-follow-up, qualification quality, discovery that expanded deal scope]

B. SDR SOURCED (SS)
Definition: SDR created demand through outbound prospecting with no prior marketing intent signal from this account in the current buying window. Prospect had not engaged with marketing in the prior [X days].
CRM criteria: [Specify exact conditions]
Weight to marketing: [e.g., 15% — for brand awareness and content that supported the SDR's credibility]
Weight to SDR: [e.g., 85%]

C. CO-SOURCED (CO)
Definition: Marketing campaign and SDR outreach were both active and contributed meaningfully within the same [30/60/90-day] buying window — neither could reasonably claim sole credit.
CRM criteria: [Specify: e.g., "Marketing touch AND SDR Activity both recorded within 60 days prior to Opportunity Creation Date"]
Weight to marketing: [e.g., 50%]
Weight to SDR: [e.g., 50%]
Tie-breaking rule: [What happens when both happened on the same day?]

D. PARTNER/EVENT SOURCED (PE)
Definition: Pipeline originated from a third-party referral, channel partner, or event where neither marketing campaign nor SDR prospecting was the primary driver.
Sub-categories: [Partner referral / Conference introduction / Community referral / Customer referral]
Weight to marketing: [For event/community — marketing organized the event, so partial credit]
Weight to SDR: [For partner referrals — SDR relationship with partner drove the intro]

E. SELF-SERVE/PLG SOURCED (PLG) — if applicable
Definition: Prospect signed up for a trial or freemium tier and converted to a sales opportunity without SDR or marketing campaign involvement.
[Include only if company has PLG motion]

1.2 ATTRIBUTION WINDOW RULES
Define the lookback window for marketing touches that qualify for attribution:
- Standard window: [Recommend based on average sales cycle — e.g., 90 days for 60-day sales cycle]
- Extended window exceptions: [When does a 12-month-old marketing touch still get credit? — e.g., if the prospect demonstrated re-engagement signal like webinar attendance]
- Job-change exception: [How to handle when a champion moves companies — does the SDR's relationship follow the person or the account?]
- Stale touch depreciation: [Do older touches get less weight? Recommend a decay model if ACV > $50K]

1.3 ACCOUNT-LEVEL VS. LEAD-LEVEL ATTRIBUTION
[Explain the difference and recommend the right level of granularity for this company's motion]
- For ABM motions: attribution must be at the Account level (multiple contacts from same account count as one buying group signal)
- For transactional motions: Lead-level attribution may be sufficient
- CRM implementation: [Specific field names and logic for the recommended approach]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SECTION 2: CO-ATTRIBUTION SCORECARD & KPIS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━

2.1 MARKETING PERFORMANCE METRICS (as inputs to SDR success)
- MQA Coverage Rate: % of Tier 1 target accounts with active marketing engagement (campaign member, ad retargeting, website visit) in last 30 days
- Marketing Warm-Up Rate: difference in SDR open/reply/meeting rates on marketing-primed accounts vs. cold accounts (benchmark: 2-4x lift expected)
- Campaign-to-SDR Handoff Speed: hours from MQA score threshold crossed to SDR first touch (target: < 4 hours for Tier 1 accounts)
- Content Consumption Depth: average number of marketing assets consumed per account before first SDR outreach (leading indicator of deal quality)
- Marketing-Influenced Pipeline: total pipeline value where marketing touch preceded SDR engagement

2.2 SDR PERFORMANCE METRICS (as inputs to marketing intelligence)
- SDR-to-Marketing Feedback Rate: number of substantive product/objection insights surfaced to marketing per week per SDR
- Account Intelligence Enrichment: % of target accounts enriched with SDR-discovered firmographic/technographic data not in CRM
- Warm-Up Asset Utilization: % of SDR sequences that reference a specific marketing asset the prospect engaged with (demonstrates SDR using marketing intelligence)
- SDR-Influenced Content Requests: number of content pieces or campaign ideas originated from SDR feedback in last quarter

2.3 COLLABORATIVE METRICS (measured together, celebrated together)
- Co-Attributed Pipeline Velocity: days to close for CO-type deals vs. MS-only or SS-only (hypothesis: co-attributed deals close faster because buyer has more trust signals)
- Marketing+SDR Win Rate: win rate for accounts with both active SDR outreach AND active marketing campaign vs. single-channel accounts
- Joint Account Penetration Rate: % of Tier 1 target accounts with both SDR multi-touch outreach AND marketing campaign engagement in same quarter
- Shared Pipeline Coverage Ratio: joint pipeline from co-attributed sources as % of quarterly revenue target

━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SECTION 3: DISPUTE RESOLUTION PROTOCOL
━━━━━━━━━━━━━━━━━━━━━━━━━━━━

3.1 ATTRIBUTION ARBITER ROLE
[Define who owns attribution decisions — recommend RevOps as neutral arbiter, not marketing or SDR leadership]
- Primary arbiter: [VP Revenue Operations / Head of Marketing Operations]
- Escalation path: [CRO or CMO for disputes > $[X] ACV]
- Decision timeline: [24 hours for standard disputes, 72 hours for complex cases]

3.2 EVIDENCE HIERARCHY
When attribution is contested, the following CRM data is definitive (in order of priority):
1. Opportunity Created Date (timestamp — this anchors all other timestamps)
2. Campaign Member Created Date + Response Date (marketing's evidence)
3. Activity Logged Date + Activity Type (SDR's evidence — call, email, LinkedIn)
4. Lead Created Date (who first entered this prospect into the system)
5. Contact Owner field (who "owned" the relationship at deal creation)

3.3 COMMON DISPUTE SCENARIOS & RULINGS
[Provide clear rulings for each scenario:]

Scenario A: SDR emailed a prospect 6 months ago (no response), prospect then downloaded a whitepaper, SDR followed up and booked a meeting. Attribution?
Ruling: [CO-Sourced — marketing re-activated a cold SDR outreach; split credit]

Scenario B: Prospect filled out "Request a Demo" form (MS signal), but SDR had already sent 3 cold emails that week before the form fill. Attribution?
Ruling: [Marketing Sourced — inbound intent signal supersedes simultaneous outbound. SDR credit for speed-to-follow-up but not sourcing]

Scenario C: SDR booked a meeting from a cold call. During discovery, prospect mentions they saw our CMO speak at a conference last month. Attribution?
Ruling: [SDR Sourced — event attendance is brand awareness, not a tracked marketing touch. SDR gets credit. Marketing gets brand credit but not pipeline credit]

Scenario D: Champion from existing customer moves to a new company. SDR had a relationship with the champion. Marketing ran a targeted campaign to the champion's new company. Attribution?
Ruling: [CO-Sourced — existing relationship (SDR) + active campaign (marketing) combined to accelerate the deal]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SECTION 4: JOINT OPERATING RHYTHM
━━━━━━━━━━━━━━━━━━━━━━━━━━━━

4.1 WEEKLY MARKETING-SDR SYNC (30 minutes)
Attendees: Marketing demand gen lead, SDR manager
Agenda:
- [10 min] Top 10 MQA accounts from past week: which SDRs are covering, what's the engagement status
- [10 min] Active campaigns: which account segments are in-flight, what outbound sequences should SDRs run in parallel
- [10 min] Feedback loop: what objections did SDRs hear that marketing needs to know about; what content performed best when referenced in SDR outreach

4.2 MONTHLY ATTRIBUTION REVIEW (45 minutes)
Attendees: VP Marketing, SDR Manager, RevOps lead, optionally CRO
Agenda:
- Pipeline attribution report: how pipeline was sourced this month (MS / SS / CO breakdown)
- Anomaly analysis: any accounts where attribution was unexpected or disputed
- Co-attribution trend: is CO% increasing over time? (goal is to increase co-attribution because it indicates better marketing-SDR collaboration)
- Incentive alignment review: are current comp structures rewarding collaboration or incentivizing credit-taking?

4.3 QUARTERLY PLANNING SESSION (2 hours)
- Align on target account list for next quarter (jointly selected)
- Campaign-to-SDR playbook: for each major campaign launching next quarter, design the SDR outreach sequence that runs in parallel
- Attribution target setting: set CO-type pipeline target as a team goal (not just MS or SS individually)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SECTION 5: CRM IMPLEMENTATION BLUEPRINT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━

5.1 SALESFORCE IMPLEMENTATION (if Salesforce CRM)
Required custom fields on Opportunity object:
- Pipeline_Source_Category__c (picklist: Marketing Sourced / SDR Sourced / Co-Sourced / Partner-Event Sourced / PLG Sourced)
- Marketing_Attribution_Weight__c (percent field: 0-100%)
- SDR_Attribution_Weight__c (percent field: 0-100%)
- First_Marketing_Touch_Date__c (date field, populated by automation)
- First_SDR_Touch_Date__c (date field, populated by automation)
- Attribution_Confidence__c (picklist: High / Medium / Low — flags deals that need human review)

Required automation (Flow or Apex):
- Trigger: On Opportunity Create, look back [90] days on the Account for Campaign Member records with 'Responded' status → populate First_Marketing_Touch_Date__c
- Trigger: On Opportunity Create, look back [90] days for Activity records of type Call/Email with Status = 'Completed' → populate First_SDR_Touch_Date__c
- Logic: Set Pipeline_Source_Category__c based on the date comparison rules defined in Section 1

Required reports:
- Pipeline by Source Category (for QBR)
- Marketing Attribution by Campaign (for marketing team)
- SDR Attribution by Rep (for SDR team)
- Co-Attributed Pipeline Velocity (pipeline source vs. days to close)

5.2 HUBSPOT IMPLEMENTATION (if HubSpot CRM)
[Same structure with HubSpot-specific field names and workflow logic]
Required properties on Deal object:
- pipeline_source_category (dropdown)
- marketing_attribution_weight (number)
- sdr_attribution_weight (number)
- first_marketing_touch_date (date)
- first_sdr_touch_date (date)

Required workflows:
- [Describe HubSpot workflow logic equivalent to Salesforce automation above]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SECTION 6: EXECUTIVE ATTRIBUTION NARRATIVE TEMPLATE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Produce a 200-word executive summary for the quarterly board deck pipeline slide that answers: Where is pipeline coming from? What does it tell us about GTM efficiency? What are we changing next quarter?

Format as three paragraphs:
Paragraph 1: Pipeline source breakdown with concrete numbers (no jargon)
Paragraph 2: What the attribution mix tells us about GTM health and marketing-SDR collaboration quality
Paragraph 3: One clear action we are taking next quarter to improve the co-attribution rate and pipeline efficiency

OUTPUT FORMAT: Produce all six sections with specific, actionable content. Where you recommend a specific metric, provide the formula. Where you reference a CRM implementation, use actual field names and logic. Where you provide an executive narrative, write it in plain business language a non-marketer can present at a board meeting.

## Example Input/Output

**Input Example:**

Company: Meridian Analytics — B2B SaaS data observability platform
ACV: $42,000 average, $28,000 median
Sales cycle: 45 days average
Sales motion: Hybrid (inbound-qualified + outbound ABM)
SDR team: 6 SDRs (3 inbound, 3 outbound)
CRM: Salesforce
Marketing automation: HubSpot connected to Salesforce
Current dispute: SDR team claims 80% of pipeline because "they make the call that books the meeting." Marketing claims 70% because "every deal touched a campaign." Both are partly right but the org is paralyzed.
Pipeline sample: 40 closed-won deals last quarter, average 3.2 marketing touches before first SDR call, 22% were pure inbound demo requests, 18% were cold SDR breaks with no prior marketing touch, 60% had both SDR outreach and marketing campaign active simultaneously.

**Output Example (partial):**

**Co-Attribution Framework for Meridian Analytics:**

Your 60% co-sourced deal rate is actually a sign of an exceptionally well-coordinated marketing-SDR team — the dispute is organizational, not factual. Based on your 45-day average sales cycle, here are the recommended source categories:

**Marketing Sourced (MS) — 22% of your pipeline:**
CRM criteria: Campaign Member 'Responded' date is > 14 days before any SDR Activity date on same Account, AND Opportunity Created Date is within 90 days of first Campaign Member date.
Recommended split: Marketing 80% / SDR 20%
SDR's 20%: Qualified the inbound request, ran discovery, expanded deal scope — this work has measurable value even when marketing created the intent.

**SDR Sourced (SS) — 18% of your pipeline:**
CRM criteria: No Campaign Member 'Responded' record on Account in prior 90 days before first SDR Activity. First SDR Activity pre-dates Opportunity Created Date by < 30 days.
Recommended split: SDR 85% / Marketing 15%
Marketing's 15%: Brand awareness, website credibility, social proof — your SDR isn't selling into a complete information vacuum even when no campaign touched this account.

**Co-Sourced (CO) — 60% of your pipeline:**
CRM criteria: Both Campaign Member 'Responded' date AND SDR Activity date exist on Account within 60-day window before Opportunity Created Date.
Recommended split: 50/50 (equal credit acknowledges that neither team could have achieved this pipeline rate independently)
Key insight: Your co-sourced win rate (calculate this) is almost certainly higher than either MS or SS alone — prove this and both teams will stop fighting over credit and start celebrating the model.

**Co-Attribution KPI Dashboard for Next Quarter:**
1. Marketing Warm-Up Rate: SDRs currently booking meetings with X% open rate on cold accounts. After marketing runs campaign against those same accounts, target open rate should increase to Y%. Measure the delta — that's marketing's ROI on SDR efficiency, not just pipeline.
2. Campaign-to-SDR Coverage Rate: Of the 250 accounts in your current ABM campaign, how many have an SDR touching them in the same window? Target: >85% coverage on Tier 1, >60% on Tier 2.
3. Joint Pipeline Velocity: Track time-to-close for CO-type deals vs. MS-only vs. SS-only. Hypothesis: CO deals close 30% faster because buyers have more trust touchpoints. If true, this data ends the attribution fight because CO becomes the most valuable motion — and it requires both teams.

## Success Metrics

- **Attribution agreement rate:** >90% of closed-won deals have no attribution dispute between marketing and SDR leadership
- **Co-attribution trend:** CO-type pipeline grows as a % of total quarter-over-quarter (signals improving collaboration)
- **Velocity differential:** Co-attributed pipeline closes 20%+ faster than single-source pipeline
- **Marketing warm-up lift:** SDR open/reply rates on marketing-primed accounts are 2-4x higher than cold accounts
- **Joint pipeline coverage:** >80% of Tier 1 target accounts have both active marketing and SDR coverage in same quarter
- **Attribution reporting time:** CRM automation reduces manual attribution reconciliation from 4+ hours/week to <30 minutes

## Related Prompts

- `../../05_Analytics-&-Performance/Sales-Development-Analytics/AI-Powered-B2B-SaaS-Marketing-Qualified-Lead-MQL-Quality-Analytics-&-Demand-Waterfall-Conversion-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Revenue-Operations-Analytics/AI-Powered-B2B-SaaS-Marketing-to-Sales-Funnel-Handoff-Analytics-&-Revenue-Accountability-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Lead-Scoring-&-Pipeline-Management/AI-Powered-B2B-SaaS-Sales-Marketing-Revenue-Alignment-Architecture-&-Closed-Loop-Lead-Intelligence-Engine.md`

## Integration Tips

**Salesforce:**
- Build the attribution model using Process Builder or Flow — no custom Apex required
- Use Campaign Influence (standard feature) as the foundation, then add the co-attribution overlay
- Build a custom Opportunity Dashboard with pipeline source breakdown for the QBR slide — SDR managers and marketing leaders should be able to self-serve this without RevOps pulling reports

**HubSpot:**
- Use the Attribution Reports tool (Enterprise tier) as a starting point, then add co-attribution fields via custom properties
- Create a shared HubSpot Dashboard with marketing and SDR KPIs side-by-side — physical proximity of metrics on the same screen changes the cultural dynamic from competition to collaboration
- Connect HubSpot Sequences to Campaign reporting to automatically flag accounts where both are active

**Gong / Chorus (Conversation Intelligence):**
- Configure topic trackers for keywords that indicate marketing-warmed vs. cold outreach ("I saw your webinar" / "I downloaded your guide" vs. "I'm not familiar with your company")
- Use call data to validate attribution: if prospect mentions marketing content in discovery call, it's a co-attribution signal even if CRM data is ambiguous

**Outreach / Salesloft:**
- Tag sequences as "Marketing-Primed Sequence" vs. "Cold Outbound Sequence" — this creates an automatic classification layer on top of your CRM attribution logic
- Sequence reply rate by type becomes direct evidence for the warm-up lift metric

**Slack + Zapier:**
- Build a Slack notification when an MQA account reaches the co-attribution threshold — auto-notify the assigned SDR that they're in a "co-sourced window" and should reference the marketing content the prospect engaged with
- Weekly digest to both marketing lead and SDR manager showing joint coverage rate across Tier 1 accounts

## Troubleshooting

**Problem:** SDR leadership refuses to participate because any co-attribution model reduces their team's "sourced pipeline" metric that they're compensated on.
**Solution:** Separate the attribution model from compensation — attribution describes reality, compensation can still reward SDRs for meetings booked and SQLs created regardless of marketing credit. Reframe co-attribution as proof of territory quality: "your SDRs work better territories because marketing heats them up" is a better story than "marketing is stealing your credit."

**Problem:** CRM data is too dirty to run the attribution model — SDRs aren't logging activities, marketing campaign data isn't connected to accounts.
**Solution:** Don't try to rebuild historical data — start clean with a 90-day implementation sprint. Run attribution manually for one quarter using a spreadsheet to establish the pattern, then automate once the org believes the model is fair. Dirty data disputes almost always mask a trust problem, not a data problem.

**Problem:** Co-attributed pipeline actually has a lower win rate than SDR-sourced pipeline (which would undermine the marketing case).
**Solution:** Segment by ACV and sales cycle — it's likely that co-attributed pipeline is at higher ACV (because marketing warms up enterprise accounts while SDRs pursue mid-market). Win rate comparison without ACV segmentation is misleading. If co-attributed pipeline is higher ACV with lower win rate, that's actually valuable intelligence: marketing is surfacing enterprise interest but the sales team isn't equipped to win those deals — a different problem to solve.

## Version History
- v1.0: Initial creation (auto-generated)
