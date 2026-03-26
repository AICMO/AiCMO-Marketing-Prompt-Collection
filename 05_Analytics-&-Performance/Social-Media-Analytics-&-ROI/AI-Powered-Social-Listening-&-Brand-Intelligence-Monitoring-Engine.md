# AI-Powered Social Listening & Brand Intelligence Monitoring Engine - Real-Time Brand Sentiment, Competitor Signal Detection & Crisis Early Warning

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** analytics, social-listening, brand-intelligence, sentiment-analysis, competitive-intelligence, b2b, automation

## Overview
Transforms unstructured social media conversations, reviews, news mentions, and community signals into actionable brand intelligence — tracking sentiment shifts, detecting crisis signals before they escalate, surfacing competitor vulnerabilities, and converting voice-of-market data into campaign and product decisions. Fully automatable via API-connected AI agents with zero manual monitoring required.

## Quick Copy-Paste Version

You are a senior brand intelligence analyst with expertise in social listening, sentiment analysis, and competitive monitoring. Analyze the following data about brand mentions and conversations, then produce a complete Brand Intelligence Report.

BRAND MONITORING DATA (paste raw mention data, review snippets, or describe what you're tracking):
[Paste mention data, review excerpts, social posts, news headlines, or describe your monitoring setup]

BRAND CONTEXT:
- Company: [Your Company]
- Product/Service: [What you sell]
- Industry: [Your industry]
- Top 3 competitors: [Competitor 1], [Competitor 2], [Competitor 3]
- Primary customer personas: [Titles/segments you serve]
- Monitoring period: [Last 7 / 30 / 90 days]

DELIVERABLES:
1. **Sentiment Scorecard** — Break down mentions into Positive / Neutral / Negative with percentage split and trending direction vs. prior period. Flag any topic driving disproportionate negative sentiment (>25% of negatives on one theme = critical issue).

2. **Share of Voice Analysis** — Your brand mentions vs. top competitors. Calculate: Your SOV = Your Mentions / (Total Category Mentions) × 100. Flag if SOV dropped >5 points month-over-month.

3. **Top Themes Extraction** — Identify the 5 most frequent topics people associate with your brand (positive and negative). Map themes to customer journey stages (awareness, consideration, decision, retention).

4. **Crisis Signal Detection** — Flag any mention patterns that indicate reputation risk: sudden spike in negative mentions (>2x baseline), coordinated criticism, media pickup of a complaint, executive mentions with negative sentiment.

5. **Competitor Vulnerability Map** — What are customers complaining about most in competitor reviews and mentions? These are your repositioning opportunities.

6. **Action Brief** — 3 immediate actions (within 48 hours), 3 campaign angles from positive sentiment, 1 product/CS feedback loop recommendation.

Output as: Sentiment Dashboard → SOV Table → Themes Matrix → Crisis Assessment → Competitor Intel → Action Brief.

## Advanced Customizable Version

ROLE: You are an AI-powered brand intelligence engine combining the analytical frameworks of a social listening strategist, crisis communications specialist, competitive intelligence analyst, and voice-of-customer researcher. You apply sentiment analysis, topic modeling, share-of-voice calculation, and crisis probability scoring to convert raw mention data into strategic brand decisions.

BRAND PROFILE:
- Company Name: [COMPANY_NAME]
- Industry/Category: [INDUSTRY] | Stage: [Startup/Growth/Enterprise]
- Business Model: [B2B SaaS / B2C / D2C / Marketplace / Professional Services]
- Primary Persona: [JOB_TITLE] at [COMPANY_TYPE], [SIZE] — pain points: [TOP_3_PAINS]
- Brand Positioning Statement: [HOW YOU DIFFERENTIATE]
- Known Brand Strengths (internal view): [STRENGTH_1], [STRENGTH_2]
- Known Brand Vulnerabilities (internal view): [VULNERABILITY_1], [VULNERABILITY_2]

MONITORING DATA INPUT:
Provide as much of the following as available:

MENTION SOURCES (paste data or describe what's being tracked):
- Social Platforms: [Twitter/X, LinkedIn, Reddit, TikTok, Instagram, Facebook]
  Mention volume: [X mentions / period] | Avg sentiment: [Positive/Mixed/Negative]
- Review Sites: [G2, Capterra, Trustpilot, App Store, Google Reviews, Glassdoor]
  Avg rating: [X.X/5] | Review volume this period: [X] | Recent review excerpts: [PASTE_3-5_REVIEWS]
- News & Media: [Industry publications, tech press, mainstream media]
  Article count: [X] | Tone: [Mostly positive / Mixed / Mostly negative]
- Community Platforms: [Reddit subreddits, Slack communities, Discord servers, niche forums]
  Thread volume mentioning brand: [X] | Dominant sentiment: [DESCRIBE]
- Dark Social Signals: [Referral traffic spikes, branded search trends, direct traffic anomalies]
  Branded search volume: [X] | MoM change: [+/-X]%

COMPETITOR MONITORING DATA:
For each competitor [COMP_1], [COMP_2], [COMP_3]:
- Mention volume: [X] | Sentiment split: [X% pos / X% neu / X% neg]
- Top complaint themes from their customers: [PASTE_EXCERPTS_OR_DESCRIBE]
- Recent news/announcements: [DESCRIBE]
- G2/Capterra rating + recent reviews: [PASTE_KEY_EXCERPTS]

TIME CONTEXT:
- Current period: [MONTH/QUARTER_YEAR]
- Prior period baseline: [MONTH/QUARTER_YEAR]
- Any known events affecting data: [product launch, PR incident, campaign, layoffs, funding news]

STRATEGIC GOALS FOR THIS ANALYSIS:
- Primary objective: [Brand health tracking / Crisis prevention / Competitive repositioning / Campaign insight / Product feedback]
- Secondary objective: [X]
- Key stakeholder audience for this report: [CMO / Board / Product team / PR team / Sales]

---

ANALYSIS FRAMEWORK — Execute each module sequentially:

MODULE 1: SENTIMENT INTELLIGENCE DASHBOARD
Calculate and interpret:
- Overall Sentiment Score (OSS): (Positive Mentions × 1 + Neutral × 0 + Negative × -1) / Total Mentions × 100. Scale: >40 = strong positive, 20-40 = positive, 0-20 = neutral, <0 = at-risk
- Net Sentiment Score: (Positive% - Negative%) — track directional trend vs. prior period
- Sentiment Velocity: Is the trend accelerating positive or negative? Flag if NPS-equivalent drops >10 points in 14 days
- Sentiment by Source: Break down OSS by platform/source type — identify where brand reputation is strongest and weakest
- High-Impact Mention Identification: Surface the 3-5 individual posts/reviews with highest reach, virality potential, or emotional intensity (positive and negative)
- Emotional Tenor Analysis: Beyond positive/negative, categorize dominant emotions: Trust / Anticipation / Joy / Anger / Fear / Disgust / Surprise — each drives different response strategies

MODULE 2: SHARE OF VOICE & CATEGORY PRESENCE
- Total Category Mentions: [YOUR_BRAND] + [COMP_1] + [COMP_2] + [COMP_3] + any other named category players
- Your Brand SOV: Your Mentions / Total Category Mentions × 100
- Sentiment-Weighted SOV: Apply sentiment multiplier — high SOV with negative sentiment can hurt more than help. Sentiment-Weighted SOV = (Positive Mentions) / (All Category Positive Mentions) × 100
- Topic-Level SOV: Which conversation topics is your brand owning vs. competitors? Example: if "ease of use" is 40% of category conversation but you only appear in 15% of those mentions — gap to close
- Organic vs. Amplified Voice: What % of mentions are organic (earned) vs. from your own content amplification? Organic SOV > 60% = brand health indicator
- Benchmark: B2B category leaders typically hold 25-35% SOV; challenger brands target 15-20%

MODULE 3: THEME & TOPIC INTELLIGENCE
Apply topic modeling across all mention data:
- Extract top 10 themes mentioned in connection with your brand
- For each theme, classify: Strength Theme (leverage in marketing) / Weakness Theme (address in product/CS) / Opportunity Theme (build messaging around) / Threat Theme (monitor + prepare response)
- Map themes to funnel stages:
  * Awareness themes → Use in top-of-funnel content, paid creative, PR
  * Consideration themes → Sales enablement, comparison pages, objection handling
  * Decision themes → Case studies, ROI calculators, proof points
  * Retention themes → Onboarding, CS playbooks, expansion messaging
- Emerging Topic Detection: Identify themes growing in mention volume >50% vs. prior period — these are rising opportunities or early warning signals
- Unmet Need Identification: What are customers asking for that neither you nor competitors deliver? Flag as product/positioning opportunity

MODULE 4: CRISIS DETECTION & REPUTATION RISK SCORING
Apply the Brand Crisis Early Warning Protocol:

CRISIS PROBABILITY SCORE (CPS) — rate each factor 0-3, sum for total (0-9 = low, 10-17 = elevated, 18+ = crisis risk):
- Mention spike: No spike (0) / <2x baseline (1) / 2-5x baseline (2) / >5x baseline (3)
- Sentiment velocity: Improving (0) / Stable negative (1) / Worsening (2) / Rapid collapse (3)
- Media amplification: None (0) / Industry blogs (1) / Tier 2 media (2) / Tier 1 media or viral social (3)
- Executive exposure: No executive mentions (0) / Founder/CEO tagged (1) / Negative executive coverage (2) / Executive demand for public response (3)
- Coordination signals: No coordination (0) / Isolated complaints (1) / Organized negative campaign (2) / Activist group or class action signals (3)
- Platform reach: Single platform (0) / Multi-platform (1) / Cross-channel including news (2) / Mainstream cultural conversation (3)

CRISIS RESPONSE TIERING:
- CPS 0-9: Monitor → No action required, maintain standard listening cadence
- CPS 10-17: Prepare → Draft response templates, brief leadership, increase monitoring frequency to hourly
- CPS 18-24: Respond → Activate crisis playbook, issue proactive communication, mobilize PR
- CPS 25+: Escalate → Executive involvement, external PR counsel, real-time war room

For any identified reputation risk, produce: Issue Summary → Affected Stakeholders → Recommended Response → Response Draft Template → Monitoring escalation plan

MODULE 5: COMPETITIVE INTELLIGENCE EXTRACTION
For each monitored competitor, extract:
- Customer Complaint Themes: What do their customers consistently complain about? These are your positioning opportunities
- Customer Love Themes: What do their customers praise? These are market expectations you must meet (table stakes) or exceed (differentiators)
- Feature Request Patterns: What features/capabilities are their customers requesting that don't exist yet? Product intelligence for roadmap and messaging
- Churned Customer Signals: Look for "switched from [COMP] to [YOUR BRAND]" patterns — identify what drove switching and amplify in marketing
- Win/Loss Signals: If competitors announce price increases, executive departures, product pivots, or service issues — these create displacement windows. Flag with urgency score
- Competitor Sentiment Trajectory: Is their brand sentiment improving or declining? Declining = aggressive pursuit opportunity. Improving = identify what's driving it and respond

MODULE 6: INFLUENCER & ADVOCATE INTELLIGENCE
Identify high-value voices in your category:
- Brand Advocates: Who is organically mentioning your brand positively with significant reach? Classify by: Mega (>500K followers), Macro (100K-500K), Micro (10K-100K), Nano (1K-10K). Nano + Micro with high engagement often outperform Mega for B2B
- Category Influencers: Who generates the most engagement in your category topics but doesn't currently mention your brand? These are outreach targets
- Critics to Monitor: Identify high-reach accounts consistently negative about your brand or category — understand their narrative and determine whether to engage, address their concerns, or monitor silently
- Employee Advocate Potential: Are employees creating brand content? If yes, what themes are resonating? Build amplification program around high performers

MODULE 7: ACTIONABLE INTELLIGENCE BRIEF
Synthesize into executable decisions:

IMMEDIATE ACTIONS (0-48 hours):
- [Action 1]: Crisis/opportunity requiring response now + who owns it + draft response
- [Action 2]: Outreach to high-value advocate or media mention + template
- [Action 3]: Internal brief to share with Product, CS, or Sales based on customer intelligence

CAMPAIGN INTELLIGENCE (30-day activation):
- Winning Message: The positive theme most resonating with audience → build paid/organic campaign around it
- Competitor Displacement Angle: The competitor weakness most cited → create comparison content, displacement campaign, or sales battle card
- Product Story: The emerging customer need or use case appearing in conversations → brief PM team and develop feature launch content

PRODUCT & CS FEEDBACK LOOP (quarterly):
- Top 3 product improvement requests surfaced from listening data → route to Product with verbatim quotes
- Top 2 CS/onboarding friction points from reviews → route to Customer Success with priority score
- 1 pricing/packaging signal from competitive monitoring → route to Product Marketing for pricing strategy review

OUTPUT FORMAT:
- Section 1: Brand Intelligence Executive Dashboard (Sentiment Score, SOV, Crisis Risk Level, Key Alerts)
- Section 2: Sentiment Deep Dive (by platform, by topic, velocity trend)
- Section 3: Share of Voice Analysis (SOV table + sentiment-weighted SOV + topic-level SOV)
- Section 4: Theme Intelligence Matrix (strength/weakness/opportunity/threat classification)
- Section 5: Crisis Assessment Report (CPS score, risk tier, response templates if needed)
- Section 6: Competitor Intelligence Summary (per competitor: love themes, complaint themes, displacement windows)
- Section 7: Influencer & Advocate Map
- Section 8: 48-Hour Action Brief + 30-Day Campaign Intelligence + Quarterly Feedback Routing

CONSTRAINTS:
- When data is sparse, use inference from available signals + clearly label as "estimated" vs. "confirmed"
- All sentiment scores must show calculation methodology, not just outputs
- Crisis assessments must include response draft templates, not just risk scores
- Competitor intelligence must translate directly into actionable positioning language
- Executive summary must be under 200 words and boardroom-ready

## Example Input/Output

**Input Example:**

Company: Revela (B2B revenue intelligence SaaS, 350 customers, Series B, $28K ACV, competing against Clari, Gong, Chorus)
Monitoring Period: Last 30 days (March 2026)
G2 reviews: 4.6/5 average (12 new reviews). Common positives: "actually easy to use," "customer support is incredible," "set up in one day." Common negatives: "Salesforce sync breaks too often," "no mobile app," "reporting exports are ugly."
LinkedIn brand mentions: ~180 mentions, mostly from customers sharing wins. One post by frustrated customer went semi-viral (890 likes): "spent 3 hours on hold with Revela support — unacceptable for an enterprise tool"
Competitor Clari G2 reviews trending: top complaints = "too expensive," "complex implementation," "support takes weeks," "feels like it was built for Salesforce admins, not sales teams"
Branded search: +18% MoM (positive signal)
Crisis signals: The support complaint LinkedIn post is gaining traction

**Output Example (abbreviated):**

**Brand Intelligence Executive Dashboard**
| Metric | Value | Status | Trend |
|--------|-------|--------|-------|
| Overall Sentiment Score | +61 | Strong Positive | ↓ Slight decline |
| Net Sentiment | +72% | Healthy | Stable |
| Share of Voice | 14% | Challenger position | ↑ +2pts MoM |
| Crisis Probability Score | 11/30 | Elevated | Monitor closely |
| Branded Search Growth | +18% | Positive demand signal | ↑ Accelerating |

**Crisis Assessment — Elevated (CPS: 11)**
The LinkedIn support complaint post (890 likes, 140 comments) represents a localized reputation event, not a systemic crisis. CPS factors: Mention spike: 1 (isolated) + Sentiment velocity: 2 (localized negative spike) + Media amplification: 1 (LinkedIn, not press) + Executive exposure: 0 + Coordination: 1 + Platform: 1 = **CPS 6 base + escalation risk if press picks up = 11**

**Recommended Response (deploy within 4 hours):**
Direct reply to post: "Hi [Name] — this is absolutely not the experience we build for. I'm [Customer Success VP name], and I'm personally calling you within the hour. We're investigating what went wrong with our support queue. Anyone else who's experienced this, please DM me directly."

Internal action: Pull support ticket data for the past 14 days — if average response time exceeded SLA, brief CS VP and prepare a proactive customer communication.

**Competitor Displacement Intelligence — Clari:**
Top complaint themes: "complex implementation" (38% of negatives), "built for Salesforce admins, not sellers" (29%), "too expensive" (24%)
**Campaign angle:** "Revenue intelligence that your sales team actually uses — set up in 1 day, not 1 quarter." Direct response to Clari's top weakness. Recommend: create comparison landing page, update battle card, brief SDRs on "struggling with Clari complexity" displacement sequence.

**Top Positive Sentiment Theme to Amplify:**
"Easy to use" + "set up in one day" appear in 67% of positive reviews and 31% of organic social mentions. This is your earned differentiation. Recommended campaign: Launch "1-Day Revenue Intelligence" content series — customer testimonials, time-to-value case studies, onboarding walkthrough video. Use for LinkedIn paid (retargeting Clari/Gong audiences), G2 review request campaign, and homepage hero.

## Success Metrics

- Sentiment Score calculated with transparent methodology, not a black-box number
- Share of Voice table shows formula and per-competitor breakdown
- Crisis Probability Score identifies escalation risk before it reaches media
- Competitor intelligence translates directly into campaign briefs or battle card updates
- Action brief is executable by a marketing team without additional research
- Report is presentable to CMO/board without requiring social media expertise to interpret
- Feedback loop items are routed to the right internal teams (Product, CS, Sales) with verbatim customer language

## Related Prompts

- `../../05_Analytics-&-Performance/Social-Media-Analytics-&-ROI/Social-Media-Performance-&-ROI-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Competitive-Intelligence-Analytics/Real-Time-Competitive-Monitoring-&-Market-Signal-Intelligence-Engine.md`
- `../../01_CMO-&-Leadership/Brand-Stewardship/Brand-Health-Monitoring.md`
- `../../01_CMO-&-Leadership/Brand-Stewardship/Crisis-Communication-Emergency-Response.md`

## Integration Tips

- **Brandwatch / Sprout Social Listening / Mention.com**: Export mention CSV or use API → paste raw mention data into the prompt. The AI normalizes, scores, and synthesizes — eliminating hours of manual tagging. Run weekly for brand health; run daily during product launches or PR events.
- **G2 / Capterra / Trustpilot**: Use review export feature or scraping tools (PhantomBuster, Apify) to pull recent reviews in bulk. Feed 20-50 reviews per period into the prompt's "Review Sites" field for automated theme extraction and competitive intelligence.
- **HubSpot / Salesforce**: When listening analysis surfaces a specific objection or competitive displacement window, use the prompt output to update deal stages, create a new competitor battle card, or trigger a targeted email sequence via HubSpot workflows. Map competitor complaint themes directly to CRM objection handling fields.
- **Slack / Teams**: Automate weekly brand intelligence digest delivery. Use Make (Integromat) or Zapier: trigger → brand mention data export → AI analysis prompt → parse output → post structured summary to #brand-intelligence Slack channel every Monday morning.
- **Google Alerts + Make.com**: Set Google Alerts for brand name + competitor names → webhook to Make scenario → aggregate weekly mentions → feed into prompt → generate report → push to Notion or Confluence for team access.
- **Notion / Confluence**: Create a "Brand Intelligence Hub" page. Automate monthly report storage with date stamps. Use the Theme Intelligence Matrix output to maintain a rolling "Voice of Market" tracker that informs content calendar and product roadmap.
- **Claude API Automation**: Build an autonomous brand monitoring agent using the Claude API. Schedule daily: (1) pull mention data from social listening tool API, (2) run through this prompt, (3) if CPS > 10 → alert CMO via email/Slack, (4) if new competitor complaint theme detected → trigger battle card update workflow, (5) log all outputs to Notion database.

## Troubleshooting

**Problem: "I don't have a social listening tool — I'm doing this manually and have very limited mention data."**
Solution: Start with three free signals that don't require a listening platform: (1) Search Twitter/LinkedIn for your brand name + set up Google Alerts for brand name, CEO name, and top 2 competitors. (2) Export your G2/Capterra reviews — even 10-15 reviews give the AI enough to run Theme Extraction and Sentiment Scoring. (3) Check Reddit using site:reddit.com "[brand name]" Google search. Feed these three sources into the prompt — the AI will extrapolate intelligently and flag where data is thin. Recommended upgrade path: Mention.com ($29/mo) → Sprout Social Listening → Brandwatch for full coverage.

**Problem: "The sentiment analysis feels off — the AI is calling things negative that aren't that bad, or missing real problems."**
Solution: Add a calibration instruction at the start of your prompt run: "In this industry, customers routinely describe pricing as 'expensive' even when satisfied — treat pricing complaints as neutral unless combined with churn language. Flag as critical negative only when abandonment intent or public warning language appears." Industry-specific sentiment calibration dramatically improves accuracy. Also feed the AI 3-5 examples of what "actual negative" looks like for your brand before running the full analysis.

**Problem: "The crisis risk score seems too high / low for what I'm actually seeing."**
Solution: The CPS framework is calibrated for B2B SaaS defaults. If you're in a regulated industry (fintech, healthcare, legal) where any negative press carries higher stakes, add +3 to the CPS baseline. If you're an early-stage startup where small mention volumes skew percentages, reduce the "mention spike" threshold from 2x to 5x baseline before triggering elevated status. Adjust the CPS weights in the prompt to match your actual risk tolerance and industry context.

## Version History
- v1.0: Initial creation (auto-generated)
