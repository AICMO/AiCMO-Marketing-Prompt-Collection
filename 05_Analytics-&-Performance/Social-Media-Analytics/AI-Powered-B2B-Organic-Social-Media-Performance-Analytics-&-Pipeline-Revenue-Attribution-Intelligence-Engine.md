# AI-Powered B2B Organic Social Media Analytics & Pipeline Revenue Attribution Intelligence Engine - Prove the ROI of Every LinkedIn Post, Thread, and Executive Content Investment

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, analytics, organic-social, linkedin, dark-social, pipeline-attribution, revenue-attribution, saas, social-proof, content-performance, thought-leadership, executive-brand

## Overview
Builds a comprehensive organic social media analytics system for B2B SaaS companies that attributes pipeline influence to specific organic social content, tracks executive and company page performance across LinkedIn, X/Twitter, and emerging platforms, measures dark social contribution, and produces a board-ready social ROI model. Use this when leadership demands proof that organic social drives revenue (not just vanity metrics), when you need to allocate budget between executive content programs and paid social, or when your organic social strategy is producing engagement but you can't connect it to deals.

## Quick Copy-Paste Version

You are a senior B2B marketing analytics expert specializing in organic social media measurement and pipeline attribution for SaaS companies. I need to build an organic social analytics system that proves pipeline and revenue contribution.

My context:
- Company: [Company Name], selling [product] to [ICP: job titles, company sizes]
- ARR: [$X] | Sales cycle: [X days average] | ACV: [$X]
- Primary social channels: [LinkedIn / X/Twitter / Bluesky / YouTube / Reddit / Other]
- Executive content program: [Yes — X executives posting / No / Informal]
- Company page followers: [LinkedIn: X | X/Twitter: X]
- CRM: [HubSpot / Salesforce]
- Current analytics tools: [Native platform analytics / Sprout Social / Hootsuite / Buffer / LinkedIn Sales Navigator / Other]
- Biggest measurement gap: [e.g., "Can't connect LinkedIn post views to pipeline," "Don't know which executive content drives deals," "Dark social is untracked"]

Please deliver:

1. Organic Social Attribution Framework — A 4-tier attribution model connecting organic social touchpoints (post impressions, profile visits, content shares, DM conversations) to CRM pipeline stages, including how to handle dark social (Slack reposts, screenshots, private shares) using self-reported attribution and survey methods

2. LinkedIn Company Page & Executive Profile KPI Stack — The 12 metrics that actually predict pipeline impact for B2B SaaS, segmented by Awareness (impressions, follower growth rate, share of voice vs. 3 competitors), Engagement (engagement rate by content type, comment sentiment score, saves-to-impressions ratio), and Pipeline (profile-to-website click conversion, content-influenced opportunity rate, deal velocity for social-touched vs. untouched accounts)

3. Content Performance Scoring Model — A weighted scoring formula for ranking every piece of organic content by business impact (not just likes), incorporating: engagement rate, ICP audience match (% of engagers matching buyer persona), link click conversion, pipeline touch rate, and amplification reach (reshares × resharer follower count)

4. Executive Content ROI Calculator — How to measure the individual and aggregate pipeline contribution of executive LinkedIn accounts, including: attributed pipeline per executive post, cost-per-influenced-opportunity vs. paid social CPL, network overlap analysis (which executive's audience has highest ICP concentration), and estimated earned media value vs. paid ad equivalent

5. Dark Social Capture System — Specific tactics to intercept dark social traffic including UTM-tagged "share this" links, Slack community monitoring, self-reported attribution dropdowns on forms, and LinkedIn post comment mining for account intelligence

6. 90-Day Measurement Roadmap — Prioritized instrumentation steps to go from organic social tracking in native analytics to a CRM-connected pipeline attribution dashboard

## Advanced Customizable Version

ROLE: You are a VP of Marketing Analytics and Revenue Intelligence with 12+ years of B2B SaaS experience building organic social measurement systems and connecting content performance data to pipeline and revenue outcomes. You have built social attribution programs at companies from $10M to $1B ARR, and you understand that organic social operates largely in the dark funnel — where LinkedIn post views become Slack conversations, screenshots become sales meeting talking points, and DMs become sourced pipeline. You specialize in multi-touch attribution with dark social capture, executive content program ROI measurement, competitive social share of voice analysis, and producing CFO-grade social ROI models that justify organic social investment against paid alternatives. You know that "engagement rate" is a vanity metric that gets social programs defunded, and you've built the systems that replace it with pipeline influence rate, deal velocity correlation, and social-sourced revenue.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Product description: [1-2 sentences on what you sell and who buys it]
- ARR: [$X] | Stage: [Seed / Series A / Series B / Series C / Growth]
- ICP: [Job titles] at [Company sizes] in [Industries]
- ACV: [$X average] | Average sales cycle: [X days]
- Revenue model: [Subscription SaaS / Usage-based / Seat-based / Hybrid]
- CRM: [HubSpot / Salesforce] | MAP: [Marketo / Pardot / HubSpot / Braze / Other]
- Data warehouse: [Snowflake / BigQuery / Redshift / None]

ORGANIC SOCIAL PROGRAM INVENTORY:
- LinkedIn Company Page: [URL] | Followers: [X] | Posting frequency: [X/week]
- LinkedIn Executive Profiles actively posting: [List: Name — Title — Follower count — Posting frequency]
- X/Twitter: [Handle] | Followers: [X] | Active? [Yes/No]
- Bluesky: [Handle] | Followers: [X] | Active? [Yes/No]
- YouTube: [Channel] | Subscribers: [X] | Upload frequency: [X/month]
- Reddit: [Subreddits you participate in] | Approach: [organic community participation / AMA / none]
- Other platforms: [Specify]
- Monthly organic social content volume: [X posts total across all channels and profiles]
- Team: [X dedicated social media managers / shared with content team / founder-only / none]
- Annual organic social investment (staff time + tools): [$X estimated]

CURRENT MEASUREMENT STATE:
- Native analytics accessed: [LinkedIn Analytics / X Analytics / Other]
- Third-party social analytics tool: [Sprout Social / Hootsuite / Buffer / Brandwatch / Oktopost / None]
- CRM connection to social: [LinkedIn Sales Navigator synced / Manual tagging only / No connection]
- UTM parameters on social links: [Systematic / Inconsistent / None]
- Dark social tracking: [Self-reported attribution form / None / Unknown]
- Current social reporting: [Weekly team report / Monthly to CMO / Ad hoc / None]
- Biggest attribution gap: [e.g., "High LinkedIn impressions, no idea if it's reaching ICPs," "Executive posts get great engagement from practitioners but not buyers," "Can't prove social is influencing deals in pipeline"]

COMPETITIVE CONTEXT:
- Primary competitors active on LinkedIn/social: [List 3-5 competitor company pages or executive profiles to benchmark against]
- Your current estimated share of voice vs. competitors: [Unknown / roughly X%]
- Competitive content categories they dominate: [e.g., "They own 'AI automation' topic," "They get 3x our engagement on product announcements"]

OBJECTIVE:
[Choose one or specify custom objective]
- [ ] Build a full organic social pipeline attribution model from scratch
- [ ] Prove (or disprove) ROI of executive content program to justify continued investment
- [ ] Create a competitive social share of voice dashboard for weekly monitoring
- [ ] Identify which content types and topics drive ICP audience engagement vs. practitioner engagement
- [ ] Build a dark social capture system to quantify unattributed pipeline from social
- [ ] Design a board-ready organic social ROI model for CFO/CEO consumption

Please deliver a comprehensive Organic Social Media Analytics & Pipeline Attribution System including:

**1. B2B Organic Social Attribution Model Architecture**

Design a 5-tier attribution framework for organic social:

*Tier 1 — Direct Attribution (cleanest signal):*
- Prospect clicks a UTM-tagged link in a LinkedIn post → lands on website → fills demo form → creates Opportunity in CRM
- Attribution: 100% social-sourced (first or last touch depending on your model)
- Required tracking: UTM parameters on every link, form-hidden-field capture of `utm_source`, `utm_medium`, `utm_campaign` stored on CRM Contact/Lead record
- UTM taxonomy for organic social:
  - `utm_source`: `linkedin_company` | `linkedin_[exec_name]` | `twitter` | `bluesky` | `youtube` | `reddit`
  - `utm_medium`: `organic_social`
  - `utm_campaign`: [content_topic_slug] (e.g., `ai_automation_series`, `product_launch_q2`)
  - `utm_content`: [post_id or content_type] (e.g., `carousel_01`, `video_product_demo`)

*Tier 2 — Influenced Attribution (regression-based):*
- Account has 2+ LinkedIn post impressions from company or executive content in the 90 days before Opportunity creation
- Method: LinkedIn Analytics company page data → export impressions by company (available for company page, not individual posts) + LinkedIn Sales Navigator "who viewed your profile" → match to CRM account list → flag as "social-influenced" accounts
- Attribution weight: 0.3× pipeline credit in multi-touch model (social as supporting touchpoint)
- Tool options: Oktopost (native LinkedIn CRM sync), Zapier + LinkedIn API (technical), or manual monthly cohort analysis in spreadsheet

*Tier 3 — Self-Reported Attribution (dark social proxy):*
- "How did you first hear about us?" dropdown on demo request and contact forms includes: LinkedIn (organic post), LinkedIn (executive content — specify name), Twitter/X, Other social, Podcast, Dark social / word of mouth
- Analysis: Monthly tally of self-reported social attribution → calculate % of new opportunities that self-attribute to organic social → apply to total opportunity volume as dark social multiplier
- Benchmark: B2B SaaS companies with active organic social programs report 15-35% of new pipeline self-attributes to social/word-of-mouth when asked directly

*Tier 4 — Engagement-to-ICP Correlation (proxy signal):*
- For every piece of organic content, export LinkedIn post analytics → cross-reference engagers' job titles and company sizes against ICP definition
- ICP Engagement Rate = (Engagers matching ICP job title + company size criteria) ÷ Total Engagers × 100
- Target: ICP Engagement Rate >40% for any individual post to be considered pipeline-generative
- Tool: LinkedIn native post analytics → manual export or Taplio/Shield/Breaker for individual profile analytics

*Tier 5 — Pipeline Velocity Correlation (statistical signal):*
- Segment all Opportunities into two cohorts: accounts that engaged with your organic social content (company page followers, post engagers, executive profile followers) vs. accounts with zero social engagement
- Compare: Average days-to-close, win rate, and ACV between the two cohorts using CRM report
- Expected finding at well-run social programs: Social-engaged accounts close 15-25% faster and have 8-15% higher win rates — use this as social ROI proof point

**2. LinkedIn Analytics KPI Stack by Business Stage**

*AWARENESS METRICS (report weekly):*
| Metric | Definition | How to Access | B2B SaaS Benchmark |
|--------|-----------|----------------|-------------------|
| Organic Impressions (Company Page) | Total impressions on all company posts | LinkedIn Analytics → Content tab | 0.5-2% of follower count per post |
| Follower Growth Rate | Net new followers ÷ Starting followers | LinkedIn Analytics → Followers tab | 2-5% MoM for growth-stage companies |
| Follower ICP Match Rate | % of new followers with ICP job titles | LinkedIn Analytics → Follower Demographics | Target: >35% in your ICP job function |
| Competitive Share of Voice | Your estimated mention/engagement volume ÷ (yours + top 3 competitors) | Brandwatch / Mention.com / manual tracking | Establish baseline, target 5% MoM improvement |
| Content Topic Reach Concentration | % of total impressions from top 3 content topics | Export monthly post data, pivot by topic tag | Top 3 topics should drive 50-60% of total impressions |

*ENGAGEMENT METRICS (report weekly):*
| Metric | Definition | Target | Alert Threshold |
|--------|-----------|--------|----------------|
| Engagement Rate (ER) by Content Type | (Reactions + Comments + Reposts) ÷ Impressions | Carousel: 3-6% / Video: 4-8% / Text: 1-3% / Document: 5-9% | <1% for any content type consistently |
| Comment Quality Score | % of comments that are substantive (>10 words, not "Great post!") ÷ Total comments | Target: >60% substantive | <30% substantive = your content is attracting the wrong audience |
| Saves-to-Impressions Ratio | Post saves ÷ Impressions (LinkedIn provides save data) | >0.3% | <0.1% = content not perceived as reference-worthy |
| ICP Engagement Rate | Engagers matching ICP criteria ÷ Total engagers | >40% ICP-matched engagement | <20% = content is reaching practitioners, not buyers |
| Executive Content Amplification Rate | Company page reposts of executive content ÷ Total company posts | 20-30% of company posts should amplify executive content | — |

*PIPELINE METRICS (report monthly):*
| Metric | Definition | How to Calculate |
|--------|-----------|-----------------|
| Social-Touched Opportunity Rate | Opportunities where contact/account had prior LinkedIn engagement ÷ Total Opportunities | CRM report: Opportunities where Contact has `LinkedIn_Engaged = TRUE` field |
| Content-Influenced Pipeline ($) | Sum of ACV for Opportunities with social touch attribution (Tier 1-3) | Multi-touch attribution model in CRM |
| Social-Sourced Pipeline ($) | Sum of ACV for Opportunities where first touch was organic social (Tier 1 direct only) | CRM: Opportunities where `Lead_Source = LinkedIn Organic` or similar |
| Executive Content Pipeline Per Post | Total pipeline influenced by executive / Number of executive posts in period | Monthly calculation: attribute % of social-influenced pipeline to executive vs. company content |
| Social-Engaged Account Win Rate | Win rate for Tier 2 accounts (social-engaged) vs. non-engaged accounts | CRM cohort comparison |

**3. Content Performance Scoring Model (Content ROI Score)**

Replace "most likes" with a weighted business impact score for every post:

**Content ROI Score (CRS) Formula:**
CRS = (ICP Engagement Rate × 0.30) + (Saves Rate × 0.20) + (Link Click Rate × 0.25) + (Comment Quality Score × 0.15) + (Amplification Score × 0.10)

Where:
- **ICP Engagement Rate**: % of engagers matching ICP definition (job title + company size) — scored 0-100
- **Saves Rate**: Post saves ÷ Impressions × 1000 — scored relative to your baseline (your median = 50)
- **Link Click Rate**: Link clicks ÷ Impressions × 100 — scored 0-100 against benchmark of 0.5-2% for B2B
- **Comment Quality Score**: % of comments >10 words — scored 0-100
- **Amplification Score**: (Reposts × 2) + (Quotes × 3) ÷ Impressions × 1000 — scored relative to baseline

CRS Interpretation:
- CRS ≥ 70: High-performing content — identify the topic, format, and hook pattern; create 3 variations
- CRS 50-69: Average-performing — test format changes or distribution boost (employee advocacy amplification)
- CRS 30-49: Below average — analyze why: wrong topic, wrong format, or wrong audience reach
- CRS <30: Underperforming — archive the pattern; do not repeat

**Monthly Content Audit Process:**
Export all posts from last 30 days → score each on CRS → rank top 10 and bottom 10 → identify patterns in top performers (topic clusters, content formats, post length, hook types, day/time of posting) → encode patterns into next month's content calendar.

**4. Executive Content Program ROI Framework**

*Individual Executive Performance Dashboard:*

For each executive posting on LinkedIn, track monthly:
| Metric | Exec A | Exec B | Exec C | Target |
|--------|--------|--------|--------|--------|
| Posts published | — | — | — | 8-12/month |
| Total impressions | — | — | — | — |
| Follower growth (net) | — | — | — | +200-500/month for Series B+ |
| ICP Engagement Rate | — | — | — | >35% |
| Pipeline-influenced ($) | — | — | — | 5-10× annual content investment |
| Content CRS (average) | — | — | — | >55 |
| Sales Navigator profile views from ICP | — | — | — | — |

*Executive Content ROI Calculation:*

**Cost Side:**
- Executive time cost: Hours spent writing/recording per month × fully-loaded hourly rate
- Ghostwriter/editor cost: Monthly agency or contractor fee
- Creative support: Graphic designer hours for carousels, video editing
- Tool cost: Taplio/Shield/Breaker analytics subscription ÷ 12
- Total monthly investment per executive: Sum of above

**Revenue Side:**
- Self-reported attribution pipeline: From "How did you hear about us?" form data, attribute pipeline to specific executive where named
- LinkedIn Sales Navigator data: Profile views from ICP accounts in 30 days before Opportunity creation → % that converted → apply to total ICP profile views
- Earned media value: Executive post organic reach × equivalent LinkedIn ad CPM ($8-15 for B2B audiences) = Advertising Value Equivalency (AVE)
- Deal acceleration value: For closed-won accounts that engaged with executive content, calculate average sales cycle reduction vs. non-engaged accounts × (ACV ÷ average sales cycle in days) = value of accelerated closure

**Executive Content ROI Ratio:**
ROI = (Self-attributed pipeline × win rate × ACV + AVE + Deal acceleration value) ÷ Total monthly investment
Target: 5:1 minimum ROI ratio for executive content programs to be CFO-justifiable

**Network Composition Analysis:**
Use LinkedIn Analytics → Follower Demographics for each executive:
- Top 5 job functions of followers
- Top 5 industries of followers
- Top 5 company sizes of followers
Compare against ICP definition → calculate ICP Audience Match Score per executive
→ Prioritize ghostwriting investment on executives with highest ICP audience match, not highest follower count

**5. Dark Social Capture & Quantification System**

Dark social represents 70-80% of B2B organic social referrals that appear as "direct" traffic in Google Analytics. Here is a multi-layer system to intercept and quantify it:

*Layer 1: Self-Reported Attribution (highest priority, lowest cost):*
Add to ALL demo request, contact, and trial signup forms:
"How did you first hear about [Company]?" with options:
- LinkedIn (company page post)
- LinkedIn (executive post — which person?)
- LinkedIn (private message / DM)
- X/Twitter
- Shared in Slack community / private Slack group
- Forwarded by a colleague
- Other social media
- Podcast (which one?)
- Search engine
- Word of mouth / colleague recommendation
- Other

Monthly analysis: Calculate social dark social rate = Social self-attribution ÷ Total responses. For B2B SaaS companies with active organic social: expect 20-40% social attribution when you provide specific options.

*Layer 2: UTM-Tagged Shareable Links:*
For every high-stakes piece of content (pillar posts, research reports, product launches):
- Create a Bitly or Rebrandly short link with `utm_medium=dark_social&utm_source=linkedin_share`
- Add a "Copy shareable link" button to the published content (blog, landing page)
- Track Bitly click-through data to measure shares in private channels

*Layer 3: Slack/Community Monitoring:*
Use tools like Talkwalker, Brandwatch, or manual monitoring in LinkedIn social feed for:
- Brand mentions shared with "Sharing this with our team"
- Screenshots of your posts being referenced in comments on other posts
- Your content being cited in LinkedIn newsletters and articles

Monthly: Record every instance of brand content being organically amplified beyond its original post → build a "viral coefficient" tracker for organic social content.

*Layer 4: LinkedIn Comment Intelligence Mining:*
Export comments from top-performing posts → run through AI analysis prompt:
"Analyze these LinkedIn post comments. For each comment, identify: (1) commenter's job title and company, (2) whether they indicate they will share this content, (3) whether they ask a sales-qualifying question, (4) whether they mention a specific pain point or use case. Output a table with: Commenter Name | Company | Title | ICP Match | Intent Signal | Action Required."

Route high-intent commenters to SDR for DM follow-up within 24 hours — this converts dark social engagement into direct pipeline.

*Layer 5: "Direct Traffic" Organic Social Attribution:*
In Google Analytics 4, direct traffic includes dark social. To recapture attribution:
- Set GA4 referral exclusion list to exclude social platforms (prevents GA4 from mis-attributing referral traffic)
- Use GA4 Exploration → Traffic Source report → filter by "Session source = (direct)" → cross-reference traffic spike dates against your high-performing post publication dates
- Correlation analysis: If your LinkedIn post published Tuesday received 50K impressions and direct traffic spiked 35% on Tuesday-Thursday, apply estimated social attribution multiplier (typically 0.25-0.45 of direct traffic spike correlating to social dark social traffic)

**6. Competitive Social Share of Voice Dashboard**

*Weekly Competitive Tracking Protocol:*

Competitors to track: [List 3-5] | Your handles: [List]

*Manual tracking (free):* 
Every Monday, record for Company Page:
- Your LinkedIn company page follower count (from LinkedIn Analytics)
- Competitor follower counts (from their public company pages)
- Your post count and average reactions for the week (LinkedIn Analytics → Content)
- Competitor post count and average reactions (visit their page, count manually or use Shield/Taplio if they have personal profiles)

*Automated tracking (paid tools):*
- **Brandwatch or Mention.com**: Set up brand monitoring for your company name + top 3 competitor names → track weekly mention volume, sentiment, and share of voice percentage
- **Sprout Social Competitive Reports**: If on Sprout, use the competitive benchmarking report for LinkedIn company pages
- **Oktopost**: B2B-specific social analytics with competitive benchmarking

*Share of Voice Formula:*
SOV = Your LinkedIn Engagement Volume ÷ (Your Volume + Competitor A + Competitor B + Competitor C) × 100

Track weekly. Alert threshold: SOV drops >5 percentage points in a single week (indicates competitor viral content or major brand event).

*Competitive Content Intelligence:*
Monthly: Identify your competitors' top 5 LinkedIn posts by engagement (sort their company page by "Most Recent" and manually check the previous month, or use Brandwatch). For each top competitor post:
- Topic and format
- Engagement volume
- Audience response themes (read top comments)
- Whether it's a content category where you're absent → identify content gaps

**7. Board-Ready Organic Social ROI Model**

For quarterly business reviews and CFO/CEO presentations, produce this single-page social ROI summary:

**Organic Social Investment Summary:**
- Total quarterly investment in organic social (staff + tools + creative): [$X]
- Posts published: [X] | Total organic impressions: [X] | Follower growth: [+X]

**Pipeline Attribution (3 methods, presented as a range):**
| Attribution Method | Pipeline Attributed | Confidence Level |
|-------------------|-------------------|-----------------|
| Tier 1 Direct (UTM-tracked) | $[X] | High |
| Tier 2 Influenced (CRM cohort) | $[X] | Medium |
| Tier 3 Self-Reported Dark Social | $[X] | Medium |
| Total Attributed Pipeline Range | $[Low] – $[High] | — |

**Conservative ROI (using only Tier 1 direct pipeline × win rate):**
ROI = (Direct pipeline × win rate × ACV) ÷ Quarterly investment

**Full Attribution ROI (including influenced and dark social):**
ROI = (Total attributed pipeline range midpoint × win rate × ACV) ÷ Quarterly investment

**Earned Media Value (paid ad equivalent):**
Organic impressions × $[CPM equivalent for your ICP on LinkedIn] ÷ 1000 = $[Advertising Value Equivalency]

**Narrative Frame for Executives:**
"Our organic social program generated $[X] in conservatively attributed influenced pipeline at a [X:1] ROI vs. content investment. Paid LinkedIn ads at equivalent impression volume would cost $[X] in media spend alone — meaning our organic social program delivered $[X] in advertising value equivalency beyond pipeline attribution. Executive content from [Executive Name] accounted for [X%] of total impressions and is our highest-performing content with [X%] ICP audience match rate."

**8. 90-Day Measurement Implementation Roadmap**

*Days 1-30: Foundation Instrumentation*
- Week 1: UTM taxonomy audit — implement consistent UTM parameters on all social links (create a UTM builder spreadsheet for social team use). Add `utm_source` hidden field to all CRM forms. Add self-reported attribution dropdown to demo/contact forms.
- Week 2: CRM field setup — create custom fields: `LinkedIn_Engaged (boolean)`, `Social_First_Touch_Source (text)`, `Social_Self_Reported (text)`. Define process for populating these fields.
- Week 3: Baseline measurement — export last 3 months of LinkedIn Analytics data. Calculate baseline ER, ICP Engagement Rate (manual review of top posts), and follower ICP match. Establish competitive SOV baseline.
- Week 4: Executive profile setup — if using Taplio or Shield, connect all executive LinkedIn profiles. Pull 90-day historical data for CRS scoring.

*Days 31-60: Attribution Model Build*
- Week 5-6: CRM cohort analysis — identify all Opportunities created in the last 6 months. Tag accounts that have LinkedIn company page followers or known LinkedIn post engagers using Sales Navigator data. Calculate preliminary social-touched opportunity rate.
- Week 7: Dark social baseline — run a one-month self-reported attribution analysis from form data. Estimate dark social contribution to total pipeline.
- Week 8: Content performance scoring — score all posts from last 60 days using CRS formula. Identify top and bottom performers. Document patterns.

*Days 61-90: Dashboard & Reporting*
- Week 9-10: Build dashboards — LinkedIn Analytics native + CRM custom report for social-influenced pipeline. If using BI tool, build organic social attribution model in Looker Studio or Metabase.
- Week 11: First competitive SOV report — establish weekly tracking cadence. Share competitive intelligence digest with content team.
- Week 12: Board-ready ROI model — compile quarterly organic social ROI presentation. Present to CMO with recommended budget adjustment based on ROI findings.

## Example Input/Output

**Input Example:**

Company: Meridian AI, B2B AI workflow automation platform for mid-market operations teams
ARR: $22M | Series B | ICP: VP of Operations and Chief Operating Officers at 200-2,000 employee companies in logistics, manufacturing, and professional services
ACV: $42,000 | Sales cycle: 58 days average
LinkedIn Company Page: 6,800 followers | Posting 4×/week
Executive profiles posting: CEO (Sarah Chen, 14,200 followers, 3×/week), VP Sales (Marcus Reyes, 3,400 followers, 1×/week)
CRM: HubSpot | No UTM tracking on social links | No self-reported attribution form field
Current reporting: Monthly screenshot of LinkedIn Analytics sent to CMO with total impressions and follower count
Biggest gap: "Sarah's posts get 15-30K impressions each but we have no idea if any of those people are buying"

**Output Example (partial):**

**Executive Content Diagnosis: High Reach, Unknown Buyer Penetration**
Sarah Chen's 15-30K impressions per post are impressive for a $22M ARR company, but impressions from LinkedIn include followers across all demographics — your challenge is unknown ICP penetration. Before assuming her content isn't converting, you need to measure it.

**Immediate Instrumentation (this week):**

Step 1: Install Shield Analytics (meridianai-shield.app) connected to Sarah's LinkedIn profile — $25/month. Within 48 hours, you'll have: follower demographics breakdown, post-level analytics including reactions by job function, and 90-day content performance history.

Step 2: Create the Meridian UTM builder spreadsheet. Every link Sarah posts now uses:
`utm_source=linkedin_sarahchen&utm_medium=organic_social&utm_campaign=[content_topic]`

Add to HubSpot: Custom Contact property "Social First Touch" (single-line text). Create HubSpot workflow: If form submission hidden field `utm_source` contains "linkedin", copy value to "Social First Touch" on Contact record.

Step 3: Add to your demo request form: "How did you first hear about Meridian AI?" with the dropdown options listed above. This takes 30 minutes to implement and will immediately start capturing dark social.

**Predicted ICP Engagement Rate Hypothesis:**
Based on Sarah's content (AI workflow automation, operational efficiency) and your ICP (VP Ops, COOs), we hypothesize her ICP Engagement Rate is 25-40%. If >35% of her engagers are VP Ops or C-suite at 200-2,000 person companies, her content is highly pipeline-generative. If <20%, she's reaching tech enthusiasts and AI hobbyists — a real but common problem.

**30-Day Content Performance Analysis (example CRS scoring):**

| Post Topic | Impressions | ER | ICP ER (estimated) | Saves Rate | Link Clicks | CRS |
|-----------|-------------|-----|---------------------|------------|-------------|-----|
| "How we cut our ops team's tool count from 12 to 3" | 28,400 | 4.2% | 42% (est.) | 0.8% | 1.1% | 74 |
| "AI doesn't replace ops people — it replaces meetings" | 22,100 | 6.8% | 31% (est.) | 0.4% | 0.3% | 61 |
| Company culture post (office photos) | 18,900 | 3.1% | 12% (est.) | 0.1% | 0.2% | 28 |

Pattern identified: Posts with specific operational efficiency data and process transformation narratives score CRS 70+. Culture/lifestyle posts score CRS <35 despite solid raw engagement. Recommendation: Deprioritize culture content on CEO profile; shift to operational transformation case studies and "ops leader to ops leader" format.

**Dark Social Capture Quick Win:**
Pull Meridian's last 90 days of "direct" traffic in GA4. Cross-reference traffic spikes with Sarah's top post dates. If you see direct traffic spikes of 20-40% on days Sarah published high-performing content, you have statistical evidence of dark social contribution. Use the correlation to estimate dark social multiplier: if direct traffic averaged 850 sessions/day before her top post and spiked to 1,200 sessions the day after, that 350-session spike (41% increase) is partially attributable to dark social from her post.

**First Month Pipeline Attribution Forecast:**
Based on 6-month HubSpot Opportunity data for Meridian:
- Pull all Contacts associated with Opportunities (last 6 months)
- Check LinkedIn Company Page follower export against those email addresses (manual match or Sales Navigator)
- Expected finding: 15-30% of your pipeline Contacts are LinkedIn followers or engagers
- Conservative attribution (10% credit for social awareness): 20% of Contacts × 10% credit × $22M ARR pipeline contribution = estimated social-influenced pipeline

## Success Metrics

- UTM coverage reaches 90%+ of organic social links within 30 days (vs. 0% baseline)
- Self-reported social attribution rate measured within 60 days — expect 15-35% of new Opportunities cite social as first-heard channel
- ICP Engagement Rate measured for all executive content — top executive achieves >35% ICP engagement rate
- Content performance scoring identifies top 3 content patterns driving CRS >65 — editorial calendar aligned to those patterns within 45 days
- Social-touched opportunity rate calculated — target: 20-35% of new Opportunities have prior social engagement touchpoint
- Executive content ROI ratio calculated — CFO-presentable report showing ROI range with conservative and full attribution scenarios delivered within 90 days
- Competitive SOV tracked weekly — target 5% SOV improvement vs. primary competitor within 90 days

## Related Prompts

- [AI-Powered B2B Brand Health Sentiment Intelligence & Share of Voice Revenue Correlation Engine](../Brand-Health-&-Sentiment-Analytics/AI-Powered-B2B-Brand-Health-Sentiment-Intelligence-&-Share-of-Voice-Revenue-Correlation-Engine.md)
- [AI-Powered B2B Multi-Platform Organic Social Content Velocity & Pipeline Intelligence Engine](../../03_Content-&-Creative/Social-Media-Content/AI-Powered-B2B-Multi-Platform-Organic-Social-Content-Velocity-&-Pipeline-Intelligence-Engine.md)
- [Dark Funnel Attribution & Anonymous Buyer Intent Intelligence Engine](../Attribution-&-Revenue-Analytics/Dark-Funnel-Attribution-&-Anonymous-Buyer-Intent-Intelligence-Engine.md)
- [AI-Powered Founder Led Pipeline Generation & Social-To-Revenue Attribution Intelligence Engine](../../03_Content-&-Creative/Founder-Brand-Content/AI-Powered-Founder-Led-Pipeline-Generation-&-Social-To-Revenue-Attribution-Intelligence-Engine.md)

## Integration Tips

**LinkedIn Analytics + HubSpot:**
LinkedIn does not offer a native HubSpot integration for organic post engagement data. Use Oktopost ($500-2,000/month) as the bridge — it syncs LinkedIn post engagement data to HubSpot contact records, enabling you to create HubSpot lists of contacts who engaged with specific posts and enroll them in SDR sequences. Alternatively, use LinkedIn Sales Navigator to manually identify post engagers, then use the HubSpot Sales Navigator integration to log profile view activity on contact records.

**LinkedIn Analytics + Salesforce:**
Oktopost has a Salesforce integration that creates Social Activity records on Leads and Contacts. For teams without Oktopost, use LinkedIn Sales Navigator for Salesforce (native integration) — set up alerts for "ICP accounts that engaged with your company posts" and route those alerts to SDRs for outbound follow-up within 24 hours.

**Shield or Taplio + Google Sheets:**
Export weekly post analytics from Shield (individual LinkedIn profiles) to Google Sheets. Create a master social performance tracker with columns: Post Date | Content Type | Topic Tag | Impressions | ER | Estimated ICP ER (manual review) | Saves | Link Clicks | CRS Score. Review top 10 performers each month to build pattern library. Share with content team as editorial intelligence.

**Brandwatch + Slack:**
Set up Brandwatch brand monitoring alerts piped to a dedicated Slack channel (#social-intelligence). Configure real-time alerts for: brand mentions with high reach, competitor mentions trending up, dark social signals (your content being referenced in other posts). Route high-intent signals to #sales-alerts for SDR action.

**GA4 Dark Social Analysis:**
In GA4 → Explore → Blank exploration → add Dimensions: Session Source, Session Medium, Date → add Metrics: Sessions, New Users, Events (form submissions). Filter: Session Source = "(direct)" AND Session Medium = "(none)". Plot by date and overlay with your top LinkedIn post publication dates. This reveals the dark social traffic signature of your highest-performing organic content.

## Troubleshooting

**Problem: LinkedIn Analytics shows high impressions but organic social links drive almost no website traffic (link clicks consistently <0.2%).**
Solution: B2B LinkedIn content is a dark social medium — most value is generated through impression-based awareness and offline/DM conversations, not click-throughs. Stop optimizing for click rate on every post. Instead, run a 30-day experiment: publish 8 posts without links (pure value, no CTA) and 8 posts with a single UTM-tagged link. Compare CRS scores and measure whether link-free posts generate more ICP profile visits to your executives via Sales Navigator data. The optimal LinkedIn content strategy for pipeline generation is typically 70% no-link thought leadership posts + 30% link posts with specific offers (reports, demo invites, tool access). Measure the no-link posts' contribution by self-reported attribution and Sales Navigator profile view spikes rather than click data.

**Problem: Executive is posting consistently but follower growth has stalled and ICP engagement rate is declining.**
Solution: This is an audience composition drift problem — the executive's existing audience is engaging but it's becoming self-referential (practitioners engaging with practitioners, not buyers finding the content). Run a Shield follower demographics analysis: if the new followers in the last 90 days are predominantly in job functions outside your ICP (junior roles, other industries, students), the algorithm is distributing content to a non-ICP audience. Tactical fix: Change content strategy to include more direct references to buyer pain points (not "here's an interesting thought about AI" but "as a VP Operations, here's what I'd do if..."). Buying-signal language in content triggers LinkedIn's algorithm to distribute to similar job function audiences. Also add 2-3 targeted comments per week on posts from ICP-profile executives in your target accounts — this surfaces the executive's profile to the right audience via comment section discovery.

**Problem: Self-reported attribution form field shows 30%+ of new leads citing LinkedIn/social, but CRM lead source data shows only 3% LinkedIn attribution — creating a credibility gap in reports.**
Solution: This is the classic last-touch vs. dark social attribution conflict. Your CRM lead source (3%) is capturing last-click attribution — the final touchpoint before form submission. The self-reported attribution (30%) is capturing first-memory attribution — where the prospect first became aware. Both are true; they measure different things. In your reporting, present both explicitly: "Our UTM tracking captures [X%] last-click attribution to organic social. Self-reported data indicates [X%] of new leads cite organic social as their first awareness channel. The gap between these numbers represents organic social's contribution to top-of-funnel awareness that converts to pipeline through multiple subsequent touchpoints — this is the dark social problem, and it means our organic social ROI is likely [1.5-3×] our conservative UTM-only measurement."

## Version History
- v1.0: Initial creation (auto-generated)
