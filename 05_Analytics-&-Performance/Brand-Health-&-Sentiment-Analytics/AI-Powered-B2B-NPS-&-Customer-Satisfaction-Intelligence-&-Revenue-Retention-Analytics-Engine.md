# AI-Powered B2B NPS & Customer Satisfaction Intelligence & Revenue Retention Analytics Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** nps, csat, customer-satisfaction, brand-analytics, revenue-retention, churn-prediction, b2b, analytics, automation

## Overview
Transforms raw NPS, CSAT, and CES survey data into a revenue-connected intelligence system — segmenting promoters and detractors by cohort, extracting qualitative themes from verbatim feedback, correlating satisfaction scores with churn risk and expansion revenue, and generating automated action plans for CS and marketing teams. Use this when you need to move beyond quarterly NPS reports and into an always-on system that predicts revenue risk and activates customer advocates before they go dark.

## Quick Copy-Paste Version

You are an AI customer satisfaction analyst. Analyze the following NPS and satisfaction data and produce an actionable intelligence report.

Company: [Your Company Name]
Survey type: [NPS / CSAT / CES or combination]
Time period: [Last 30/60/90 days]
Total respondents: [Number]
Overall NPS score: [Score, e.g., +42]
Verbatim feedback: [Paste up to 50 verbatim responses, or summarize key themes]
Customer segments available: [e.g., ARR tier, product line, industry, tenure, CSM owner]

Produce a Customer Satisfaction Intelligence Report with these sections:

1. SATISFACTION HEALTH SCORE (0-100)
Synthesize NPS, response rate trend, and verbatim sentiment into an overall score. Explain the score.

2. PROMOTER / PASSIVE / DETRACTOR BREAKDOWN
- Count and percentage of each category
- Top 3 themes driving promoter scores (what are they loving?)
- Top 3 themes driving detractor scores (what are they hating?)
- Which customer segment has the highest vs. lowest NPS? (e.g., enterprise vs. SMB, Year 1 vs. Year 2+)

3. VERBATIM THEME ANALYSIS
Cluster verbatim responses into the top 5 positive and top 5 negative themes. For each theme: frequency, representative direct quote, business impact (churn risk, expansion blocker, or advocacy opportunity).

4. CHURN RISK REGISTER
Based on detractor scores and negative verbatim patterns, identify:
- Accounts most at risk of churning in next 90 days (by segment/pattern, not individual names unless provided)
- Leading warning signals to watch: which verbatim phrases predict churn before NPS drops?
- Recommended intervention playbook for each risk tier (Red/Yellow/Green)

5. ADVOCACY ACTIVATION OPPORTUNITIES
From promoter responses, identify:
- Which accounts are most likely to participate in case studies, reference calls, G2 reviews, or speaking opportunities?
- Language patterns that signal high advocacy intent (e.g., "I recommend this to everyone", "game-changer")
- Recommended outreach sequence to activate these advocates within 14 days

6. REVENUE CORRELATION ANALYSIS
Correlate NPS segment with revenue outcomes:
- Do promoters have higher net revenue retention (NRR) than detractors? Estimate the delta.
- What is the expansion revenue opportunity if you converted all passives to promoters?
- What is the estimated ARR at risk from current detractor accounts?

7. RECOMMENDED ACTIONS (ranked by urgency)
For each risk or opportunity: action, owner (CS/Marketing/Product/Executive), timeline, and expected revenue impact.

Format as an executive-ready report with a 3-sentence TL;DR at the top.

## Advanced Customizable Version

ROLE:
You are a senior customer intelligence analyst specializing in B2B SaaS satisfaction measurement, cohort analysis, and revenue retention forecasting. You operate as an autonomous AI agent that ingests raw survey data — NPS, CSAT, CES, and verbatim feedback — and produces revenue-connected intelligence that CS leaders and CMOs can act on immediately. You do not produce vanity dashboards. You produce churn predictions, advocacy pipelines, and expansion revenue opportunities.

CONTEXT:
Company: [COMPANY_NAME]
Product: [PRODUCT_DESCRIPTION, e.g., "B2B revenue intelligence platform for mid-market sales teams"]
ICP: [ICP_DESCRIPTION, e.g., "VP Sales and RevOps leaders at 200-2,000 employee SaaS companies"]
Current ARR: [ARR, e.g., "$18M ARR"]
Average contract value: [ACV, e.g., "$42,000 ACV"]
Survey cadence: [e.g., "Quarterly relationship NPS + post-onboarding CSAT at 30 days + annual CES"]
Measurement period: [DATE_RANGE]
CS team size: [e.g., "6 CSMs covering 340 accounts"]

SURVEY DATA INPUTS:
- NPS score (current period): [SCORE]
- NPS score (prior period): [SCORE] — for trend analysis
- Response rate: [%, e.g., "34%"]
- Total respondents: [NUMBER]
- Promoters (9-10): [COUNT] | Passives (7-8): [COUNT] | Detractors (0-6): [COUNT]
- CSAT score (if available): [SCORE and methodology]
- CES score (if available): [SCORE and methodology]
- Verbatim feedback corpus: [paste verbatim responses OR describe key themes from your survey tool]
- Segment breakdowns available: [e.g., ARR tier, industry vertical, product module, CSM owner, customer tenure band, geography]
- Known at-risk accounts (from CS): [any accounts already flagged by CS team as churn risk]
- Known expansion accounts (from CS/Sales): [any accounts with active expansion discussions]

OBJECTIVE:
Produce a Customer Satisfaction Intelligence Report that:
1. Converts raw satisfaction scores into a revenue-weighted health index
2. Identifies churn risk at the cohort level with 90-day prediction windows
3. Surfaces expansion revenue opportunities hidden in promoter verbatim
4. Quantifies the ARR impact of moving from current NPS to a target NPS
5. Generates automated advocacy activation sequences for CS teams
6. Connects every finding to a specific revenue outcome or risk

ANALYSIS FRAMEWORK — THE SATISFACTION-REVENUE BRIDGE:
Apply this four-layer framework to connect satisfaction to revenue outcomes:

Layer 1 — MEASUREMENT INTEGRITY:
Evaluate data quality before drawing conclusions.
- Response rate benchmark: B2B SaaS industry average is 20-35%. If <15%, flag and adjust confidence levels.
- Response bias check: Are detractors underrepresented? (Unhappy customers often don't respond — apply a 15-20% detractor inflation adjustment if response rate is low.)
- Recency bias: Weight responses from the last 30 days more heavily if the period spans >60 days.
- Segment coverage: Are all major cohorts (by ARR, tenure, product module) represented? Flag blind spots.

Layer 2 — COHORT INTELLIGENCE:
Segment NPS across every available dimension and identify the "NPS cliff" — the segment where scores drop most sharply:
- ARR tier analysis: Do enterprise accounts ($100K+) score differently from SMB (<$25K)? If yes, this signals a product-market fit issue in one segment.
- Tenure band analysis: Year 0-1 vs. Year 1-2 vs. Year 3+ customers. NPS typically improves with tenure — if it doesn't, onboarding or early value delivery is broken.
- Product module analysis: If multi-product, which module has the lowest satisfaction? This is a product roadmap signal.
- CSM owner analysis: Are certain CSM books of business consistently underperforming? This is a coaching and capacity signal.
- Industry vertical analysis: Are buyers in a specific vertical systematically less satisfied? This signals a product-market fit misalignment or a missing integration.

NPS COHORT SCORING TABLE (generate for each available segment):
| Segment | Promoters % | Passives % | Detractors % | NPS | ARR in Segment | ARR at Churn Risk |
|---|---|---|---|---|---|---|

Layer 3 — VERBATIM INTELLIGENCE:
Apply AI theme extraction to verbatim responses using this methodology:
a) Cluster verbatim into themes using semantic similarity (not keyword matching)
b) Score each theme by: frequency, sentiment intensity, and ARR weight (themes from $100K+ accounts weighted 3x)
c) Map each theme to one of four categories:
   - PRODUCT GAP: Missing feature or broken functionality ("can't do X", "would love Y")
   - VALUE REALIZATION: Customer not achieving promised outcomes ("we haven't seen the ROI yet")
   - SERVICE FAILURE: CS, onboarding, or support experience issues ("response times are slow")
   - COMPETITIVE THREAT: Customer evaluating or mentioning alternatives ("we're looking at Competitor X")

For each theme category, output:
- Theme label (2-5 words)
- Frequency (# of mentions, % of total responses)
- ARR exposure (estimated ARR of accounts mentioning this theme)
- 2-3 most representative direct quotes
- Revenue action: what CS or Marketing should do with this insight

Layer 4 — REVENUE IMPACT MODELING:
Run these four revenue calculations:

A) CHURN RISK QUANTIFICATION:
Industry benchmark: Detractors churn at 3-5x the rate of promoters in B2B SaaS.
- Estimate detractor churn rate: [detractor count] × [avg detractor ARR] × [4x churn multiplier vs. baseline churn rate]
- Produce: "Estimated ARR at Risk from Detractors: $X over next 12 months"
- Produce: "Cost of converting 50% of detractors to passives: estimated $Y ARR saved"

B) PASSIVE UPGRADE OPPORTUNITY:
Passives are the hidden opportunity — they won't churn but they won't expand. Promoters expand at 2.2x the rate of passives.
- Estimate expansion ARR lost by having passives vs. promoters: [passive ARR] × [2.2x expansion multiplier delta]
- Produce: "Expansion Revenue Opportunity if all passives become promoters: $X in incremental NRR"

C) PROMOTER ADVOCACY VALUE:
B2B SaaS promoters generate an average of 0.3-0.8 new logo referrals per year.
- Estimate advocacy pipeline from current promoters: [promoter count] × [0.4 avg referrals] × [avg ACV]
- Produce: "Estimated Pipeline from Promoter Advocacy: $X (if activated within 90 days)"

D) NPS-TO-ARR IMPROVEMENT MODEL:
If you move NPS from current score to target score (+10 or +20 points):
- Model the revenue impact using the NPS-growth correlation (Bain & Company benchmark: companies with NPS 10 points higher than competitors grow 2x faster)
- Produce: "Revenue impact of +10 NPS improvement: estimated $X in incremental ARR over 18 months"

CHURN PREDICTION ENGINE:
Beyond NPS scores, identify leading behavioral indicators of churn risk using verbatim and demographic signals:

HIGH CHURN RISK LANGUAGE PATTERNS (flag any response containing):
- "we're evaluating alternatives" / "looking at other options" / "comparing vendors"
- "haven't seen ROI" / "hard to justify the cost" / "renewal decision coming up"
- "integration isn't working" / "our team won't use it" / "adoption is low"
- "our contact left" / "new leadership" / "reorganization" (champion displacement risk)
- 4-5 star CSAT on individual metrics combined with NPS score of 5-6 (cognitive dissonance = passive detractor)

MEDIUM CHURN RISK LANGUAGE PATTERNS:
- "would love to see X feature" (unmet need, but still engaged)
- "support response times" / "onboarding could be better" (service recovery opportunity)
- "too expensive" without value qualification (pricing objection, solvable)

LOW CHURN RISK / EXPANSION SIGNAL PATTERNS:
- "recommend to everyone" / "told my network about it" / "already referred X"
- "wish it did Y for other teams" (cross-sell signal)
- "planning to expand usage" / "bringing on more users" (upsell signal)
- "saved us X hours per week" / "increased our pipeline by Y%" (quantified ROI — use for case study)

ADVOCACY ACTIVATION PLAYBOOK:
For each promoter account showing advocacy intent signals:
1. Day 1-3: CS sends personalized note acknowledging their score and asking if they'd share their story
2. Day 3-7: If yes — route to Marketing for: G2 review request + reference call offer + case study qualification
3. Day 7-14: If case study qualified — Marketing sends one-page brief with the story they told in verbatim
4. Day 14-30: Publish customer story; amplify via their LinkedIn; offer co-marketing (joint webinar, blog post)
5. Ongoing: Add to Customer Advisory Board shortlist; invite to exclusive executive roundtables

Automate Steps 1-2 via HubSpot sequence triggered by NPS score ≥9.

OUTPUT FORMAT:
Section 1: Executive TL;DR (3 bullet points — the 3 most important revenue signals)
Section 2: Satisfaction Health Dashboard (NPS trend, CSAT, CES, response rate, measurement integrity flags)
Section 3: Cohort NPS Analysis (table by each available segment)
Section 4: Verbatim Theme Intelligence (positive themes, negative themes, each mapped to revenue action)
Section 5: Revenue Impact Model (ARR at risk, expansion opportunity, advocacy pipeline, NPS improvement model)
Section 6: Churn Risk Register (accounts/segments at risk, leading indicators, intervention playbook)
Section 7: Advocacy Activation Pipeline (promoter accounts to activate, sequence, expected pipeline value)
Section 8: 30-Day Action Plan (CS + Marketing + Product owners, prioritized by revenue impact)
Section 9: Survey Design Recommendations (how to improve response rate and data quality next cycle)

CONSTRAINTS:
- Never report a satisfaction score without connecting it to an ARR implication
- Every recommended action must include the owner (CS/Marketing/Product), timeline, and estimated revenue outcome
- Flag measurement confidence level (High/Medium/Low) where data is sparse or biased
- Prioritize interventions for accounts in the top 20% of ARR — save the revenue first
- All advocacy recommendations must be executable by a 1-2 person CS team without additional budget

## Example Input/Output

**Input Example:**

Company: Dataloop AI (B2B data labeling platform for enterprise ML teams, Series B)
Survey: Quarterly relationship NPS
Period: Q1 2026
NPS: +34 (down from +41 last quarter)
Respondents: 127 (31% response rate from 410 accounts)
Promoters: 58 (46%) | Passives: 46 (36%) | Detractors: 23 (18%)
Key verbatim themes noted by CS team: "API reliability complaints from 3 large accounts," "loves the annotation speed," "Labelbox comparison coming up in renewals," "data security compliance questions from enterprise"
Segments available: ARR tier (Enterprise >$80K: 45 accounts, Mid-Market $20-80K: 180 accounts, SMB <$20K: 185 accounts)
Enterprise NPS: +18 | Mid-Market NPS: +39 | SMB NPS: +44

**Output Example:**

---
**EXECUTIVE TL;DR**
- **Revenue Alert**: Enterprise NPS of +18 vs. SMB +44 signals a product-market fit gap at your highest-value segment — the 45 enterprise accounts represent ~$6.2M ARR, and at enterprise detractor churn rates, you have approximately $1.1M ARR at risk in the next 12 months if unaddressed.
- **Root Cause**: API reliability complaints concentrated in enterprise accounts (likely higher data volume demands that surface infrastructure limits) combined with active Labelbox competitive evaluations — this is a retention emergency, not a CS capacity issue.
- **Hidden Opportunity**: Mid-market promoters (NPS +39, 180 accounts) are deeply underutilized as advocates. At 0.4 referrals per promoter, your active promoter base could generate $1.8M in estimated referral pipeline — none of which requires paid acquisition spend.

---
**SATISFACTION HEALTH DASHBOARD**

| Metric | Current | Prior Quarter | Trend |
|---|---|---|---|
| Overall NPS | +34 | +41 | ↓ -7 points — ALERT |
| Enterprise NPS | +18 | +29 (est.) | ↓ -11 points — CRITICAL |
| Mid-Market NPS | +39 | +40 | → stable |
| SMB NPS | +44 | +43 | → stable |
| Response Rate | 31% | 28% | ↑ improving |
| Measurement Confidence | Medium | — | Low response rate inflates promoter ratio; apply 18% detractor inflation adjustment |

---
**COHORT NPS ANALYSIS**

| Segment | Accounts | NPS | Promoters | Passives | Detractors | ARR | ARR at Churn Risk |
|---|---|---|---|---|---|---|---|
| Enterprise (>$80K) | 45 | +18 | 38% | 42% | 20% | ~$6.2M | ~$1.1M |
| Mid-Market ($20-80K) | 180 | +39 | 47% | 36% | 17% | ~$7.4M | ~$640K |
| SMB (<$20K) | 185 | +44 | 52% | 33% | 15% | ~$1.8M | ~$130K |

**Key Finding**: Enterprise detractor rate (20%) is not dramatically higher than SMB (15%), but the ARR concentration makes each enterprise detractor worth 12x the churn risk of an SMB detractor. Prioritize enterprise retention above all.

---
**VERBATIM THEME INTELLIGENCE**

| Theme | Category | Frequency | ARR Exposure | Rep. Quote | Revenue Action |
|---|---|---|---|---|---|
| API reliability at scale | PRODUCT GAP | 11 mentions | ~$2.8M | "When we push >500K labels/day the API queues back up — we can't run production ML pipelines reliably" | Escalate to Engineering as P0; CS to proactively brief all enterprise accounts with API workaround guide within 7 days |
| Labelbox competitive evaluation | COMPETITIVE THREAT | 8 mentions | ~$3.1M | "Our procurement team wants us to benchmark Labelbox before we renew" | Deploy competitive battlecard immediately; offer enterprise accounts a dedicated technical comparison session with a Solutions Engineer |
| Data security / SOC 2 questions | PRODUCT GAP | 6 mentions | ~$1.9M | "We need to show our security team the audit logs — we couldn't find where to pull them" | Fast-track SOC 2 Type II certification announcement; create a Security FAQ one-pager for CS to use in renewal conversations |
| Annotation speed praised | PRODUCT (positive) | 34 mentions | ~$4.2M | "Our annotation throughput went up 3x in the first 90 days — nothing else comes close" | Extract for case study; use as counter-narrative in Labelbox competitive conversations |
| Recommend to team/network | ADVOCACY SIGNAL | 19 mentions | ~$2.1M | "I've already told our sister team at [company] to evaluate Dataloop" | Trigger advocacy activation sequence immediately for all 19 accounts |

---
**REVENUE IMPACT MODEL**

| Model | Calculation | Result |
|---|---|---|
| ARR at Churn Risk (Detractors) | 23 detractors × est. $47K avg ARR × 4x churn multiplier vs. 8% baseline | **~$1.85M ARR at risk in 12 months** |
| Passive Upgrade Opportunity | 46 passives × $38K avg ARR × 2.2x expansion delta | **~$960K in incremental expansion NRR** |
| Advocacy Pipeline Value | 19 promoters with advocacy signals × 0.4 referrals × $85K ACV | **~$646K in estimated referral pipeline** |
| NPS +10 Improvement Impact | Moving from +34 to +44 correlated with ~8% faster ARR growth at current $15.4M ARR | **~$1.2M incremental ARR over 18 months** |

---
**30-DAY ACTION PLAN**

1. **API Reliability Emergency Response** (Engineering + CS, Days 1-5): CS briefs all 11 affected enterprise accounts with a written acknowledgment, SLA for fix, and interim workaround. Engineering escalates to sprint priority. *Expected impact: prevent $900K ARR from entering active churn risk.*

2. **Labelbox Competitive Renewal Defense** (Sales + PMM, Days 1-10): Deploy updated competitive battlecard to all renewal AEs. Offer all 8 at-risk accounts a "Technical Deep Dive vs. Labelbox" call with Head of Product. *Expected impact: protect ~$3.1M ARR in competitive renewals.*

3. **Advocate Activation Sequence** (Marketing + CS, Days 3-14): CS sends personalized outreach to all 19 promoter accounts with advocacy language. Route willing participants to Marketing for G2 review, reference call, or case study. *Expected impact: 6-8 new G2 reviews, 3-4 case studies, ~$646K referral pipeline.*

4. **Enterprise NPS Recovery Sprint** (CS + Product, Days 7-30): Assign dedicated CSM office hours for all 45 enterprise accounts. Host a quarterly enterprise customer advisory call addressing the top 3 product gaps. *Expected impact: +8-12 NPS points in enterprise segment, protecting $6.2M ARR.*

---

## Success Metrics

- **NPS trend reversal**: Quarter-over-quarter improvement of ≥5 NPS points within one intervention cycle
- **Enterprise detractor conversion rate**: ≥30% of detractors move to passive within 60 days of intervention
- **ARR rescue rate**: % of flagged at-risk ARR retained through proactive CS intervention (target: ≥75%)
- **Advocacy activation rate**: ≥40% of contacted promoters complete at least one advocacy action (G2 review, reference call, or case study)
- **Passive upgrade rate**: % of passives who expand ARR within 6 months (benchmark: promoters expand at 2.2x the rate of passives)
- **Revenue correlation coefficient**: Measurable positive correlation (r > 0.5) between NPS score and 12-month NRR across cohorts
- **Response rate improvement**: ≥5 percentage point increase in survey response rate after implementing design recommendations
- **Time to intervention**: All HIGH-risk accounts contacted by CS within 72 hours of NPS survey close

## Related Prompts

- [AI-Powered B2B Brand Health Monitoring & Competitive Sentiment Analytics Intelligence Engine](../../05_Analytics-&-Performance/Brand-Health-&-Sentiment-Analytics/AI-Powered-B2B-Brand-Health-Monitoring-&-Competitive-Sentiment-Analytics-Intelligence-Engine.md)
- [AI-Powered Net Revenue Retention & Expansion Revenue Intelligence Engine](../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/AI-Powered-Net-Revenue-Retention-&-Expansion-Revenue-Intelligence-Engine.md)
- [AI-Powered Customer Health Score & Proactive Revenue Protection Intelligence Engine](../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/AI-Powered-Customer-Health-Score-&-Proactive-Revenue-Protection-Intelligence-Engine.md)
- [AI-Powered B2B Real-Time Social Listening Intelligence & Buyer Signal Revenue Activation Engine](../../05_Analytics-&-Performance/Brand-Health-&-Sentiment-Analytics/AI-Powered-B2B-Real-Time-Social-Listening-Intelligence-&-Buyer-Signal-Revenue-Activation-Engine.md)

## Integration Tips

- **Medallia / Qualtrics / Delighted**: Schedule a monthly data export of NPS responses (with verbatim and respondent metadata) as CSV. Feed directly into the Advanced Version prompt. If your tool supports webhooks, trigger a real-time alert to CS Slack channel whenever any account scores NPS ≤4.
- **HubSpot**: Create a custom contact property "NPS Score" and "NPS Verbatim Category" updated from your survey tool via Zapier or native integration. Build a workflow that automatically enrolls NPS ≤6 respondents into a CS recovery sequence and NPS ≥9 respondents into an advocacy nurture sequence.
- **Salesforce**: Log NPS score as a custom field on Account records. Create a report showing NPS score vs. renewal probability (from opportunity stage) to identify accounts where low NPS is not yet reflected in CRM risk flags — these are your blind spots.
- **Gainsight / ChurnZero / Totango**: Push NPS scores into the customer health scoring model as a weighted signal. Set automated Calls to Action (CTAs) for CSMs when any account drops ≥2 NPS points quarter-over-quarter.
- **Gong / Chorus**: Run a keyword search across call recordings for the churn risk language patterns listed in the Advanced Version (e.g., "evaluating alternatives," "hard to justify"). Cross-reference with NPS detractors to see if churn risk language predicts low NPS scores 30-60 days in advance.
- **G2 / Capterra**: Use the advocacy activation output to power a structured G2 review generation campaign. After activating promoters via NPS outreach, send a second touchpoint directing them to your G2 profile. Track the brand halo effect: does an improved G2 rating correlate with improved win rates 60 days later?
- **Zapier / Make**: Build an automated NPS intelligence pipeline — survey close → export verbatim to Google Sheets → pass to Claude API with Advanced Version prompt → output report to Notion → notify CMO and CS leader in Slack with TL;DR bullets. Schedule monthly on survey cadence.
- **Notion / Confluence**: Maintain a rolling Customer Satisfaction Intelligence log. Each quarter's report links to the prior quarter's action plan with a "completed / in progress / missed" status for each recommendation — creates accountability and shows improvement trajectory to board.

## Troubleshooting

**Problem**: NPS verbatim responses are too short or generic ("great product," "love it") to extract meaningful themes.
**Solution**: Add open-ended follow-up questions to your survey: "What's the #1 outcome you've achieved using [product]?" for promoters, and "What's the single most important thing we should fix?" for detractors. These elicit outcome-specific language. If you have existing short verbatims, add this instruction to the prompt: "Treat short generic responses as data about what customers do NOT think is worth mentioning — this signals your marketing isn't teaching them to articulate value outcomes."

**Problem**: The revenue impact model numbers feel too speculative without actual cohort churn data.
**Solution**: Replace the industry benchmark multipliers with your own cohort data. In your CRM, run a report: "Of accounts that scored NPS ≤6 in the prior 4 quarters, what % churned within 12 months?" That's your actual detractor churn rate. Substitute it into the ARR at Risk formula for a defensible, company-specific model. Run this calibration exercise once — it makes every future NPS report immediately credible to the CFO.

**Problem**: CS team is overwhelmed and can't act on every at-risk account identified in the report.
**Solution**: Add this constraint to the Advanced Version prompt: "Given a CS team of [N] CSMs managing [X] total accounts, rank all intervention recommendations by: (1) ARR at risk, (2) intervention effort (Low = 1 email / Medium = 1 call / High = dedicated sprint), (3) probability of score recovery based on verbatim signals. Output only the top 10 accounts and 3 actions per CSM per month." This forces the model to operate within your actual capacity.

## Version History
- v1.0: Initial creation (auto-generated)
