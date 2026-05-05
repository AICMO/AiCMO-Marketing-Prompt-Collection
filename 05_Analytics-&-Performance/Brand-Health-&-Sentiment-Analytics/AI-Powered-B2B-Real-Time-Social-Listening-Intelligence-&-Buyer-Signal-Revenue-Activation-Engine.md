# AI-Powered B2B Real-Time Social Listening Intelligence & Buyer Signal Revenue Activation Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** social-listening, brand-intelligence, buyer-signals, competitor-monitoring, revenue-activation, sentiment-analytics, automation

## Overview
Continuously monitors brand, competitor, and category mentions across social media, review sites, community forums, news, and dark social channels — then automatically scores each signal for revenue relevance and triggers downstream sales, CS, or marketing actions. Use this when you need to replace fragmented, manual social monitoring with an always-on AI agent that turns market conversations into pipeline.

## Quick Copy-Paste Version

You are an AI-powered social listening revenue intelligence agent. Analyze the following brand and market signals and produce an actionable revenue intelligence brief.

Company: [Your Company Name]
Competitors: [Competitor 1, Competitor 2, Competitor 3]
Product category keywords: [e.g., "sales enablement software", "revenue intelligence platform"]
Data sources: [paste or describe mentions from: Twitter/X, LinkedIn, Reddit, G2, Glassdoor, news, Slack communities, YouTube comments, industry forums]
Time window: Last 7 days

**Step 1 — Signal Classification**
For each mention, classify:
- Signal type: Competitor Pain (customer complaining about a competitor), Buying Intent (researching solutions), Brand Mention (our brand specifically), Category Entry (awareness-stage question), Churn Risk (our customer expressing frustration), Advocacy Opportunity (customer praising us or our category)
- Revenue relevance score: 1 (low) to 10 (high), based on specificity, buyer seniority, and recency
- Recommended action: Outbound outreach / CS alert / Content creation / Influencer engagement / No action

**Step 2 — Revenue Activation Report**
Produce a structured report with:

1. HIGH-PRIORITY SIGNALS (revenue relevance 8-10)
For each: source URL or context, company/person if identifiable, signal type, exact quote or summary, recommended action, ideal responder (SDR / AE / CSM / Content team), and suggested response or message.

2. COMPETITOR VULNERABILITY MAP
List competitors with: number of negative mentions, top recurring complaints, sentiment trend (improving/worsening), and estimated churn opportunity for our sales team.

3. CATEGORY BUYING ACTIVITY
Questions and discussions indicating active evaluation or research in our category. Group by stage: Awareness / Consideration / Decision. For Decision-stage signals, flag as urgent pipeline opportunities.

4. BRAND HEALTH SIGNALS
Positive: sentiment driving organic advocacy to amplify.
Negative: reputation risks requiring marketing or PR response.

5. CONTENT INTELLIGENCE
Top 3 unaddressed questions or pain points from the market this week that we should create content around. Include: recommended format, target keyword/topic, urgency.

6. AUTOMATED ACTION QUEUE
List every signal that warrants an immediate response. Format as:
- Signal ID | Type | Source | Recommended Action | Owner | SLA (hours)

Format the full report as a structured JSON object AND a human-readable executive summary (8-10 bullet points) for the morning standup.

## Advanced Customizable Version

ROLE:
You are an autonomous B2B social listening intelligence agent embedded in the revenue operations stack of a [Company Stage: Series B / Enterprise / PLG SaaS] company selling [Product Description] to [ICP: e.g., VP Sales and Revenue Operations leaders at 200-2000 employee SaaS companies]. Your mandate is to convert market conversations into pipeline, protect revenue from churn, and surface content opportunities — all without human intervention except for final approval of outbound messages.

CONTEXT:
Brand: [Company Name]
Core value proposition: [1-sentence value prop]
Competitors: [List with their primary weaknesses you've observed]
Category triggers (keywords that indicate active buying): [e.g., "switching from Gong", "alternatives to Salesloft", "best revenue intelligence tool"]
ICP job titles to flag: [e.g., CRO, VP Sales, Head of Revenue Operations, Sales Enablement Manager]
Monitored channels: [Twitter/X, LinkedIn, Reddit r/sales r/salestips r/saastr, G2 reviews, TrustRadius, Gartner Peer Insights, Glassdoor, relevant Slack communities, Hacker News, industry news]
Integration targets: HubSpot CRM / Salesforce / Outreach.io / Salesloft / Slack (for alerts) / Notion (for content backlog)

RAW SIGNAL DATA:
[Paste scraped mentions, alerts, review excerpts, or describe the data you're working with]

OBJECTIVE:
Process all signals through a four-layer revenue intelligence framework:

**LAYER 1 — SIGNAL TRIAGE & ENRICHMENT**
For every signal:
a) Extract: source, author (name/title/company if available), verbatim quote or summary, timestamp, URL
b) Classify using the B2B Revenue Signal Taxonomy:
   - COMPETITOR_PAIN: Customer of competitor expressing dissatisfaction → outbound opportunity
   - ACTIVE_EVALUATION: Prospect publicly researching our category → high-urgency inbound capture
   - CLOSED_LOST_REACTIVATION: Past prospect or churned customer re-engaging with category → re-engagement trigger
   - BRAND_ADVOCACY: Customer or influencer praising our product → amplification opportunity
   - CHURN_SIGNAL: Our customer expressing frustration, exploring alternatives, or going silent → CS alert
   - EXECUTIVE_MOVE: ICP executive changed jobs → outbound trigger (new budget, new mandate)
   - CATEGORY_QUESTION: Unmet educational need in our category → content opportunity
   - COMPETITIVE_ATTACK: Negative content targeting our brand requiring response → PR/marketing escalation
c) Score revenue relevance (1-10) using: buyer seniority (CXO=10, Director=7, Manager=5, IC=3), specificity of pain (product-specific=+3, general complaint=+1), recency (same-day=+2, this week=+1), audience reach (viral=+2, small=0)
d) Enrich with available account data from CRM if company is known prospect or customer

**LAYER 2 — REVENUE ACTION MAPPING**
Apply the following decision logic:

IF signal type = COMPETITOR_PAIN AND score ≥ 7:
→ Draft personalized outbound message acknowledging their specific pain (never mention you saw their post)
→ Suggest: SDR sends LinkedIn connection request + connection message within 4 hours
→ Flag account in CRM as "Hot Competitor Prospect"

IF signal type = ACTIVE_EVALUATION AND score ≥ 6:
→ Identify if account is in CRM (known prospect: alert AE; unknown: enrich and route to SDR)
→ Draft: 3-touch outbound sequence with 48-hour urgency
→ Content to share: relevant case study for their industry + G2 comparison page

IF signal type = CHURN_SIGNAL:
→ Immediate CS alert with verbatim quote, account health score, ARR at risk
→ Draft: CSM save outreach that acknowledges the friction category without revealing you saw the post
→ If ARR > [threshold]: escalate to VP CS within 2 hours

IF signal type = BRAND_ADVOCACY:
→ Draft: personalized thank-you and G2/TrustRadius review request if no recent review exists
→ Flag for: case study pipeline, reference program, speaker opportunity
→ Amplify: share in company Slack #wins channel with context

IF signal type = CATEGORY_QUESTION:
→ Add to content backlog with: topic, recommended format (blog/video/LinkedIn post), target keyword, business value (lead magnet / SEO / thought leadership), suggested author (founder / PMM / domain SME)
→ If question has 20+ upvotes or is from high-authority source: flag as URGENT content gap

**LAYER 3 — COMPETITIVE INTELLIGENCE SYNTHESIS**
Weekly synthesis (run every Monday):
- Competitor share of voice: mention volume vs. 4-week average (trending up/down)
- Competitor sentiment score (positive mentions / total mentions)
- Most-mentioned competitor weaknesses by category: [Price, Reliability, Support, UX, Integration, ROI]
- Competitor win themes: what messaging is generating engagement for each competitor
- Competitive displacement opportunities: accounts publicly dissatisfied + in our ICP + not yet in CRM

Output: Competitive Weekly Intelligence Brief formatted for CRO + CMO morning review

**LAYER 4 — CONTENT & BRAND INTELLIGENCE**
- Top 5 unanswered questions in our category this week (with source URLs)
- Trending topics our competitors are NOT addressing (white space for thought leadership)
- Our brand mention sentiment trend vs. last 4 weeks
- Earned media opportunities: journalists, analysts, or influencers discussing our category
- Dark social signals: mentions in private communities worth monitoring more closely

CONSTRAINTS:
- Never recommend reaching out directly on the platform where you saw the signal (respect platform norms)
- All AI-drafted outreach must be reviewed by a human before sending
- Competitor content must never be used verbatim
- GDPR/CCPA compliance: flag signals involving EU citizens for additional review before outbound
- Escalate any signal involving legal/regulatory risk to General Counsel

OUTPUT FORMAT:
1. Executive Summary (8 bullet points, 90 seconds to read)
2. High-Priority Action Queue (structured table: Signal ID | Type | Account | ARR Impact | Owner | Deadline)
3. Competitor Intelligence Brief (narrative + data table)
4. Content Opportunity Backlog (5-10 prioritized items)
5. Full Signal Database (JSON array for CRM/automation ingestion)
6. Suggested Slack alerts (formatted as Slack message blocks, ready to post)

## Example Input/Output

**Example Company:** Velorant AI — a B2B SaaS company selling AI-powered sales forecasting to VP Sales and CROs at 100-500 employee SaaS companies. ARR $4.2M, Series A. Competitors: Clari, Aviso, People.ai.

**Example Signals Submitted:**
- Reddit r/sales: "We've been on Clari for 18 months and the forecast accuracy has gotten worse, not better. Implementation was a nightmare and support is non-existent. Anyone else experiencing this? Considering switching."  Posted by u/SalesOps_Jenna (bio: "VP Sales Ops @ Vaultly" — 380 employees, SaaS)
- LinkedIn: Sarah Chen, CRO at Meridian Data (450 employees, Series B) posted: "Why is it so hard to trust your pipeline? Spending 3 hours every Friday manually reconciling deals because our forecasting tool doesn't integrate with our comp platform." (43 likes, 12 comments)
- G2 Review for Aviso (posted 2 days ago): "3/5 stars — The AI predictions sound great in the demo but in practice the model needs so much manual calibration it defeats the purpose. Moving our evaluation to other options."
- Existing Velorant customer (AcmeTech, $68K ARR): CSM notes show 2 support tickets in 7 days, both about "integration errors with Salesforce." No QBR scheduled.

**Example Output (High-Priority Action Queue):**

| Signal ID | Type | Account | Potential ARR | Owner | Deadline |
|---|---|---|---|---|---|
| SIG-001 | COMPETITOR_PAIN | Vaultly (via Jenna - VP Sales Ops) | $28K est. | SDR: Marcus R. | 4 hours |
| SIG-002 | ACTIVE_EVALUATION | Meridian Data (Sarah Chen, CRO) | $45K est. | AE: Diana T. | Same day |
| SIG-003 | ACTIVE_EVALUATION | Unknown (G2 reviewer) | Enrich first | SDR | 24 hours |
| SIG-004 | CHURN_SIGNAL | AcmeTech ($68K ARR at risk) | -$68K churn | CSM: James L. | 2 hours |

**Drafted outreach for SIG-001 (SDR Marcus to Jenna):**
Subject: Clari replacement — Vaultly might be timing well
"Hi Jenna — I've been seeing a lot of discussion in the RevOps community lately about teams outgrowing Clari's black-box model, especially when forecast accuracy doesn't improve after year one. We built Velorant specifically for this moment — transparent AI with explainable predictions, and 90-day implementation guarantees. Worth 20 minutes to compare notes? Happy to share a data-driven benchmark from 3 similar-size teams who made the switch."

## Success Metrics

**Signal Processing Quality:**
- Revenue relevance score accuracy: % of flagged "high-priority" signals that result in actual pipeline within 90 days (target: >25%)
- False positive rate: % of high-urgency alerts that turn out to be irrelevant (target: <15%)

**Revenue Impact:**
- Pipeline sourced from social listening signals per quarter
- Churn saves: ARR protected by CS alerts triggered from sentiment signals
- Content performance: organic traffic and leads from content created from category signal insights

**Operational Efficiency:**
- Time from signal detection to sales alert (target: <1 hour for 8+ score signals)
- Coverage: % of monitored channels with at least 1 signal processed daily
- SDR adoption: % of AI-drafted outreach used with <20% edit rate (indicates quality)

## Related Prompts

- `../../05_Analytics-&-Performance/Brand-Health-&-Sentiment-Analytics/AI-Powered-B2B-Brand-Health-Monitoring-&-Competitive-Sentiment-Analytics-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Demand-Sensing-&-Market-Intelligence/AI-Powered-Demand-Sensing-&-Market-Signal-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-&-Cold-Outreach/AI-Powered-B2B-Intent-Signal-Triggered-Outbound-&-Buying-Trigger-Pipeline-Intelligence-Engine.md`
- `../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/AI-Powered-B2B-At-Risk-Account-Marketing-Rescue-&-Churn-Prevention-Campaign-Intelligence-Engine.md`

## Integration Tips

**Zapier / Make.com:**
- Trigger: Mention.com or Brand24 webhook fires when keyword match detected
- Action: Run this prompt via Claude API → parse JSON output → route to HubSpot (new deal), Slack (alert), or Outreach (sequence enrollment)

**HubSpot:**
- Create custom property "Social Signal Score" on Contact and Company records
- High-score competitor pain signals auto-create a Contact + Task for SDR review
- Churn signals trigger a HubSpot workflow: update lifecycle stage → assign CSM task → send internal Slack alert

**Salesforce:**
- Use Einstein Activity Capture + custom fields to log signal source and score
- Flow builder: if Signal_Type = "CHURN_SIGNAL" AND ARR > 50000 → create Case assigned to VP CS

**Notion:**
- Content opportunity signals automatically append to Content Backlog database with fields: Topic, Format, Urgency, Source Signal, ICP fit
- Weekly competitive brief auto-populates Competitive Intelligence page

**Slack:**
- Dedicated channel #signal-intelligence for all high-priority alerts
- Format: Signal type emoji (🔥 Competitor Pain, ⚠️ Churn Risk, 💡 Content Gap) + one-line summary + owner tag + action link

## Troubleshooting

**Problem: Too many false positives — irrelevant mentions flooding the queue**
Fix: Tighten keyword targeting with Boolean operators (e.g., `"Clari" AND ("switching" OR "frustrated" OR "alternative")`) and add exclusion terms (e.g., `-"Clari Fai"` to exclude a person's name). Raise the minimum revenue relevance threshold from 6 to 8 for outbound actions.

**Problem: SDRs ignoring AI-drafted outreach — low adoption**
Fix: The most common cause is tone mismatch. Have 3 top-performing SDRs review 20 AI drafts, identify the voice gap, and add 5 example "approved messages" as few-shot examples in the prompt. Also add a direct CRM link so SDRs can one-click approve from their daily task view.

**Problem: Churn alerts arriving too late — customer already gave notice**
Fix: Add early warning signals beyond support tickets: (1) product usage drop tracked via Mixpanel/Amplitude webhook, (2) champion job change alert via LinkedIn API, (3) competitor review posted by a known customer account. Layer these as additional Zapier triggers feeding the same intelligence pipeline.

## Version History
- v1.0: Initial creation (auto-generated)
