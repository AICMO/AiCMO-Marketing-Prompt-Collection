# AI-Powered B2B SaaS Micro-Conversion Analytics & Pre-Pipeline Buyer Engagement Scoring Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** micro-conversions, engagement-scoring, behavioral-analytics, pipeline-intelligence, web-analytics, b2b-saas, demand-generation, intent-data

## Overview
Transforms non-form engagement events — video views, ROI calculator completions, resource downloads, pricing page scroll depth, chatbot interactions, webinar attendance — into a predictive buyer engagement score that identifies in-market accounts before they fill out a demo request form. Use this when pipeline is stalling at top of funnel, when SDRs are cold-calling too early, or when you need to activate high-intent anonymous visitors before competitors get to them first.

## Quick Copy-Paste Version

You are a B2B SaaS buyer engagement intelligence expert. Analyze the following micro-conversion event data and build a ranked list of in-market accounts with engagement scores, predicted pipeline probability, and recommended next actions for each account.

MICRO-CONVERSION EVENT DATA (paste from GA4, HubSpot, Amplitude, or your analytics tool):

ENGAGEMENT EVENTS THIS WEEK (list all accounts or anonymous sessions with the following events):
- ROI/value calculator completed: [account name or session ID, date, completion %]
- Pricing page visited: [account, date, scroll depth %, number of visits]
- Product demo video watched: [account, date, % of video watched]
- Competitive comparison page visited: [account, date, pages viewed]
- Case study or customer story downloaded: [account, industry of case study, date]
- Webinar registered or attended: [account, webinar topic, attendance duration]
- Technical documentation or integration pages visited: [account, pages, time on page]
- Blog post read (bottom-funnel topics): [account, topic, time on page, scroll depth]
- Chatbot or AI assistant interaction: [account, questions asked, session duration]
- Free tool or template downloaded: [account, tool name, date]

KNOWN CONTACT DATA (from MAP or CRM — fill in what's available):
- Known contacts with engagement events this week: [list with job title, company, seniority]
- Anonymous sessions identified as ICP companies (via 6sense/RB2B/Clearbit): [company names]
- Re-engaged contacts (inactive >90 days, now active): [list]

BUSINESS CONTEXT:
- ICP definition: [company size, industry, buyer titles]
- Average sales cycle: [X] weeks
- ACV: $[X]K
- Primary competitor: [name]
- Current MQL threshold (what score triggers SDR outreach): [X points]

ANALYSIS REQUIRED:
1. Score each account on a 0-100 Buyer Engagement Score using signal recency, frequency, and intent depth
2. Classify each account: HOT (score 75+), WARM (45-74), NURTURE (20-44)
3. For each HOT account: identify the specific buying trigger signal, recommended SDR message angle, and urgency timeline
4. For WARM accounts: recommend the next nurture content or re-engagement trigger
5. Identify the 3 micro-conversion events that most strongly correlate with pipeline conversion in your data

Output as: Ranked Account Engagement Heat Map, Engagement Score Breakdown by Account, SDR Action Brief for HOT accounts, and Nurture Recommendations for WARM accounts.

## Advanced Customizable Version

ROLE: You are a senior B2B revenue intelligence analyst and marketing operations architect with 15+ years building predictive engagement scoring systems for high-growth SaaS companies. You specialize in translating anonymous behavioral signals into pipeline-ready account intelligence, constructing multi-signal engagement models that outperform form-fill-only lead scoring, and designing SDR alert workflows that convert engagement data into same-day outbound action. You understand that 67% of the B2B buying journey happens before a prospect contacts a vendor, and you build systems to intercept buyers during that dark research phase.

CONTEXT:
Company: [Company name]
Product: [Brief description — e.g., "AI-powered contract lifecycle management for enterprise legal teams"]
Industry vertical: [e.g., "LegalTech", "HR Tech", "FinTech", "Cybersecurity"]
ICP: [e.g., "VP Legal and General Counsel at 500-5,000 employee companies in financial services and healthcare"]
ACV: $[X,XXX] | Sales cycle: [X] weeks average | Win rate: [X]%
CRM: [Salesforce / HubSpot / Microsoft Dynamics]
MAP: [HubSpot / Marketo / Pardot / ActiveCampaign]
Web analytics: [GA4 / Amplitude / Mixpanel / Heap]
De-anonymization: [6sense / Clearbit Reveal / RB2B / Demandbase / none]
Session recording: [Hotjar / FullStory / Microsoft Clarity]
Analysis period: [Last 7 / 14 / 30 days]

MICRO-CONVERSION EVENT TAXONOMY (fill in all events tracked in your stack):

HIGH-INTENT EVENTS (Score 15-25 points each):
Event Name | Account/Session | Date | Depth/Duration | Recency Weight
ROI Calculator completion (75%+) | [data] | [date] | [X]% complete | [this week = 1.5x, last week = 1.0x, 2 weeks ago = 0.7x]
Pricing page: 3+ visits in 14 days | [data] | [date] | Avg [X]% scroll | [weights above]
Competitive comparison page viewed | [data] | [date] | [X] min on page | [weights above]
Product demo video: 75%+ viewed | [data] | [date] | [X]% watched | [weights above]
Integration/API docs: 10+ min session | [data] | [date] | [X] pages | [weights above]
Security/compliance trust page: 5+ min | [data] | [date] | [X]% scroll | [weights above]
"How to switch from [Competitor]" content | [data] | [date] | [X] min | [weights above]

MEDIUM-INTENT EVENTS (Score 8-14 points each):
Event Name | Account/Session | Date | Depth/Duration | Recency Weight
Case study / customer story download | [data] | [date] | Industry: [X] | [weights above]
Webinar attended (live, 30+ min) | [data] | [date] | [X] min attended | [weights above]
Bottom-funnel blog post (10+ min read) | [data] | [date] | Topic: [X] | [weights above]
Chatbot interaction (3+ message exchange) | [data] | [date] | Topics: [X] | [weights above]
Free tool / template / calculator (any use) | [data] | [date] | Tool: [X] | [weights above]
Newsletter click-through (intent topic) | [data] | [date] | Topic: [X] | [weights above]
Return visit (3+ sessions in 7 days) | [data] | [date] | [X] sessions | [weights above]

LOW-INTENT EVENTS (Score 2-7 points each):
Event Name | Account/Session | Date | Recency Weight
Blog post read (<5 min) | [data] | [date] | [weights above]
Webinar registered (not attended) | [data] | [date] | [weights above]
Ebook/white paper download (top of funnel) | [data] | [date] | [weights above]
Podcast/audio content played | [data] | [date] | [weights above]
Social media click-through to website | [data] | [date] | [weights above]
Single pricing page visit | [data] | [date] | [weights above]

DECAY AND NEGATIVE SIGNALS:
- Score decay: apply 10% decay per week of inactivity (score × 0.9^weeks_inactive)
- Negative signals (reduce score): unsubscribed from email (-15), bounced from landing page in <10s (-5), visited careers page only (-10), visited support/help center only (no penalty — can be sign of evaluation)
- Engagement floor: minimum score of 0 (no negative totals)

FIRMOGRAPHIC MULTIPLIERS (apply to total behavioral score):
- Perfect ICP fit (all criteria match): × 1.4
- Strong ICP fit (3/4 criteria match): × 1.2
- Partial ICP fit (2/4 criteria match): × 1.0
- Poor ICP fit (<2/4 criteria match): × 0.6
- Open opportunity in CRM (active deal): × 1.8 (priority engagement signal for deal support)
- Closed-lost in CRM (<12 months): × 1.3 (re-engagement opportunity)
- Current customer: route to CSM/expansion team, not SDR

ACCOUNT-LEVEL AGGREGATION (for companies with multiple contacts engaging):
- Aggregate all contact engagement scores within the same company
- Buying committee signal: 3+ unique contacts from the same company engaging within 14 days = add 25 bonus points (indicates active internal evaluation)
- Role diversity bonus: if contacts include both economic buyer title AND technical evaluator title, add 15 points
- Senior buyer engagement: if VP+ or C-suite contact engages, multiply that contact's score by 1.5 before aggregation

OBJECTIVE:
Produce a complete pre-pipeline buyer engagement intelligence report that enables marketing ops to trigger real-time SDR alerts, enables demand gen to fire account-based retargeting campaigns, and enables the CMO to quantify the pipeline value of the invisible buying activity happening before form fills.

DELIVERABLES:

1. ACCOUNT ENGAGEMENT HEAT MAP & SCORING SUMMARY
   For each account/company in the dataset, provide:
   - Buyer Engagement Score (0-100) with score breakdown: Behavioral Score + Firmographic Multiplier + Recency Decay Applied + Buying Committee Bonus
   - Tier Classification: 🔴 HOT (75+) / 🟡 WARM (45-74) / 🟢 NURTURE (20-44) / ⚪ COLD (<20)
   - Score Trend: UP (increased >10 points vs. prior period), FLAT (±10), DOWN (decreased >10 points)
   - Primary Intent Signal: the single highest-weight event driving this account's score (e.g., "ROI Calculator completed 92% on Monday" or "3 contacts from buying committee engaged this week")
   - Recommended Action: SDR outreach / ABM retargeting / nurture sequence / monitor
   - Urgency Window: within 24h / 72h / 1 week / next sprint

2. SDR ACTION BRIEF (HOT ACCOUNTS ONLY)
   For each account scoring 75+, produce a complete SDR-ready brief:
   - Account Intelligence Summary: company name, ICP fit score, key firmographic facts (industry, size, tech stack if known)
   - Buying Signal Narrative: "On [date], [contact name or "an anonymous visitor from Acme Corp"] completed your ROI calculator showing [X]% cost savings. Two days later, a second contact from the same company visited the pricing page twice and spent 8 minutes on the enterprise tier. This is a 3-person buying committee doing active vendor evaluation."
   - Personalized Outreach Angle: specific message hook based on the dominant engagement signal (e.g., if they spent time on the security page: lead with compliance/security angle; if they completed the ROI calculator: lead with the specific ROI outcome they modeled)
   - Recommended First Touch: channel (email / LinkedIn / phone / direct mail), timing, and 3-sentence message framework
   - Conversation Starter: a specific, non-creepy question that references the content they engaged with without revealing surveillance-level tracking ("I noticed companies evaluating [category] often care about [topic] — is that on your radar?")
   - Competitive Context: if they visited a competitive comparison page, flag the competitor and provide 2 differentiation points to use in outreach
   - Deal Risk if Not Actioned: estimated probability this account chooses a competitor if not contacted within [urgency window]

3. BUYING COMMITTEE INTELLIGENCE (ACCOUNTS WITH 3+ CONTACTS ENGAGING)
   For each multi-contact account:
   - Stakeholder Map: role of each engaging contact, engagement pattern, and inferred interest by role
   - Decision-Making Stage Hypothesis: based on the types of content consumed, infer where they are in the buying journey (Problem Awareness → Solution Research → Vendor Evaluation → Business Case Building → Final Selection)
   - Content Gap Analysis: what content would a buyer at this stage typically need that they have NOT yet consumed? This reveals gaps in your content coverage and triggers for next nurture content
   - Recommended Multi-Thread Campaign: which team member should contact which role, with what message, through which channel, in what sequence over the next 14 days

4. PREDICTIVE SIGNAL CORRELATION ANALYSIS
   Using the historical data provided (or directional guidance if data is limited):
   - Top 3 Micro-Conversion Events by Pipeline Conversion Correlation:
     Rank each event type by: (accounts that did event X → became pipeline) ÷ (total accounts that did event X) = conversion rate to pipeline
     Provide benchmarks: ROI calculator completion typically converts to pipeline at 18-28% in B2B SaaS; pricing page 3+ visits typically converts at 12-20%
   - Signal Combination Power: which 2-event combinations have highest pipeline conversion rates? (e.g., "ROI Calculator + Pricing Page" converts at 3.2x the rate of either signal alone)
   - Time-to-Pipeline Analysis: how many days after the primary engagement event does the account typically convert to pipeline? Use this to set SDR follow-up urgency windows
   - False Positive Signals: identify any high-frequency engagement events that correlate poorly with pipeline (e.g., "blog reads" may have high volume but low pipeline conversion — helps deprioritize vanity engagement)
   - Score Threshold Validation: recommend optimal score threshold for SDR trigger based on: at Score 75+, what % of accounts become pipeline? At Score 60+? Helps tune the alert threshold to balance SDR capacity with conversion rate

5. ENGAGEMENT SCORING MODEL CALIBRATION GUIDE
   - Current Model Accuracy Assessment: if historical data is available, calculate the Predictive Score vs. Actual Pipeline Conversion Rate by tier:
     HOT accounts (75+): X% converted to pipeline (target: >25%)
     WARM accounts (45-74): X% converted to pipeline (target: 8-15%)
     NURTURE accounts (20-44): X% converted to pipeline (target: 2-5%)
   - Model Refinement Recommendations: 3 specific changes to the scoring weights based on the correlation analysis (e.g., "Increase ROI Calculator weight from 20 to 25 points — it has highest pipeline conversion rate of all events at 31%")
   - Missing Events to Track: what engagement signals are NOT currently tracked that would improve model accuracy? (e.g., if you're not tracking chatbot questions, you're missing high-intent signals from prospects who are actively researching)
   - Decay Rate Recommendation: based on your sales cycle length, recommend the appropriate decay rate (short cycle of 30 days → faster decay; long enterprise cycle of 180 days → slower decay)

6. REAL-TIME ALERT ARCHITECTURE
   Design the automated trigger system to operationalize this scoring model:
   - SDR Alert Thresholds: at what score should an instant Slack/email alert fire to an SDR? (Recommend: 75+ = instant alert, 60-74 = daily digest, 45-59 = weekly summary)
   - Alert Contents: company name, score, primary engagement trigger, contact names if known, firmographic summary, recommended outreach angle, link to CRM record
   - ABM Campaign Triggers: at what score should a LinkedIn or programmatic ad campaign activate for the account? (Recommend: 45+ = enter nurture ad sequence, 60+ = enter high-intent competitor displacement ads)
   - Email Nurture Triggers: define the engagement event that should trigger a specific email (e.g., "ROI Calculator completed → send case study email from AE within 2 hours")
   - Suppression Rules: ensure alerts do NOT fire for current customers, recently closed-lost accounts that explicitly said "not a fit," opted-out contacts, or accounts in active sales cycles (route those to AE, not SDR)
   - Escalation Logic: if SDR doesn't action a HOT account within 24 hours, escalate to SDR manager with "at-risk" flag

7. DARK FUNNEL INTELLIGENCE REPORT
   Quantify the invisible buying activity:
   - Total Anonymous Engagement Volume: X sessions from ICP companies (via de-anonymization tool) that did not convert to known contacts
   - Anonymous Pipeline Opportunity: if de-anonymized ICP sessions convert to pipeline at the same rate as known contacts, how much pipeline is sitting in dark funnel? (Anonymous ICP sessions × known contact → pipeline conversion rate × ACV = dark funnel pipeline estimate)
   - Recommended Investment: make the business case for de-anonymization tool investment if not currently deployed (calculate ROI: dark funnel pipeline value × estimated capture rate of 10-15% with de-anonymization ÷ tool cost)
   - Dark Social Footprint: estimate engagement happening off your owned properties (LinkedIn organic, Slack communities, podcasts, peer referrals) using reverse-engineering of direct/dark social traffic spikes correlated with published content

8. 30-DAY ENGAGEMENT SCORING QUICK-START ROADMAP
   WEEK 1 (Data foundation):
   - Set up GA4 custom event tracking for all high-intent events listed above
   - Create a Google Sheet or Salesforce dashboard with account-level engagement aggregation
   - Define ICP firmographic scoring criteria and integrate with CRM
   - Baseline: pull prior 90 days of engagement data and retroactively score all accounts to identify hidden pipeline
   
   WEEK 2 (Scoring model build):
   - Implement the scoring model in your MAP (HubSpot, Marketo, Pardot) using the point values above
   - Create the account-level aggregation logic (especially multi-contact buying committee detection)
   - Set up Slack alert integration for HOT account triggers
   - Train SDRs on behavioral engagement selling: how to use engagement intelligence without being creepy
   
   WEEK 3 (ABM activation):
   - Connect engagement scores to LinkedIn Matched Audiences (update weekly)
   - Set up automated email triggers based on engagement events
   - Create SDR outreach sequences for each HOT trigger scenario (ROI Calculator, Pricing Page, Competitive Comparison)
   
   WEEK 4 (Measurement and optimization):
   - Measure: what % of SDR-alerted HOT accounts have converted to pipeline in the first 30 days?
   - Calibrate: adjust scoring weights based on first 30 days of data
   - Report: present the CMO with "hidden pipeline discovered" metric — number of accounts that were 75+ score but had never filled out a form

## Example Input/Output

**Input Example:**
Company: "Streamline" — AI-powered procurement automation for mid-market and enterprise companies
ICP: VP of Procurement, CPO, and COO at 250-2,500 employee manufacturing, healthcare, and professional services companies
ACV: $67,000 | Sales cycle: 74 days | Win rate: 22%
Stack: GA4 + HubSpot + 6sense + Hotjar

Weekly engagement data (fictional):
- Acme Manufacturing (anonymized via 6sense): 2 contacts, ROI Calculator completed (87%), pricing page visited 4x, integration docs 12 min, competitive comparison page
- Riverside Health (known contact: Sarah Chen, VP Procurement): Case study download (healthcare vertical), webinar attended 52 min, 3 blog posts (bottom-funnel)
- TechBridge Partners (anonymous): Single pricing page visit, 1 blog post
- Lakewood Consulting (known contact: Mark Torres, COO): ROI Calculator started but abandoned at 40%, pricing page once

**Output Example:**

**ACCOUNT ENGAGEMENT HEAT MAP:**

🔴 **Acme Manufacturing — Score: 89/100 — HOT — Action Required Within 24 Hours**
Score Breakdown: Behavioral Score 72 (ROI Calculator 92% complete: +22pts, Pricing page 4x visits: +24pts, Integration docs 12min: +16pts, Competitive comparison: +20pts) × Firmographic Multiplier 1.4 (perfect ICP fit: manufacturing, 800 employees, procurement tech buyer) + Buying Committee Bonus +25 (2 contacts engaging) = 89 after recency weighting (all events this week: 1.5x recency)
Primary Intent Signal: ROI Calculator completed + competitive comparison page visited same day — this is a vendor evaluation session
Score Trend: UP (was 0 last week — new entrant, moved directly to HOT)

**SDR ACTION BRIEF — ACME MANUFACTURING:**
Buying Signal Narrative: "On Tuesday, two people from Acme Manufacturing's procurement function completed your ROI calculator (87% complete — they stopped right before the email capture gate) and immediately visited the pricing page four times across two separate sessions. The same day, they spent 12 minutes in your API integration documentation, suggesting an IT stakeholder was evaluating technical fit. On Wednesday, they visited your 'Streamline vs. Coupa' comparison page. This is a 3-phase vendor evaluation session: business case building (ROI calc), budget confirmation (pricing), technical validation (API docs), competitive shortlisting (comparison page). They are evaluating you against Coupa right now."

Personalized Outreach Angle: Lead with the ROI they were calculating. Their industry (manufacturing) and company size suggest they're probably managing ~$45M in annual procurement spend. Your calculator likely showed $2.1-2.8M in savings for that spend profile.

Recommended First Touch: Email from AE (not SDR) within 4 hours. Subject line: "Your ROI model for Acme" — reference the savings figure the calculator would have generated for a company of their size. Do NOT mention that you know they visited the website. Instead: "Companies similar to Acme in manufacturing typically see 4.2% savings on addressable spend — I ran the math for a company your size and the number is significant. Worth 20 minutes?"

Competitive Context: They visited the Streamline vs. Coupa comparison page — flag to AE: Coupa is the active competitor. Use differentiation angle #1: implementation time (Streamline averages 47 days vs. Coupa's 4-6 months) and #2: total cost of ownership (Coupa requires 3 FTE to administer; Streamline averages 0.5 FTE).

---

🟡 **Riverside Health — Score: 61/100 — WARM — Action Within 72 Hours**
Score Breakdown: Behavioral Score 47 (Case study healthcare download: +12pts, Webinar 52 min: +13pts, 3 bottom-funnel blog posts: +9pts each = 27pts) × Firmographic Multiplier 1.2 (strong ICP fit, healthcare, known VP Procurement contact) = 61 (no recency decay — all events this week)
Primary Intent Signal: Healthcare case study download followed by long-form webinar attendance — solution education phase
Score Trend: UP (+28 points vs. prior week)
Recommended Action: Enroll in healthcare-specific ABM nurture sequence; trigger LinkedIn Account Spotlight ad for Riverside Health within 24 hours; assign to SDR for warm touchpoint in 72 hours

Recommended SDR Outreach for Sarah Chen (VP Procurement): LinkedIn message referencing the webinar topic she attended: "Sarah — saw the discussion on procurement automation for healthcare compliance in last week's webinar. We're working with three health systems in [her region] on exactly this challenge. Happy to share what we've learned?" (Natural, non-creepy, topically relevant.)

---

⚪ **TechBridge Partners — Score: 12/100 — COLD**
Single pricing page visit (7 pts) + 1 blog post (3 pts) = 10 pts × 1.0 ICP fit multiplier = 12. Monitor only. No SDR action. Enroll in top-of-funnel email nurture sequence if email is known.

---

⚪ **Lakewood Consulting — Score: 24/100 — NURTURE**
ROI Calculator abandonment at 40% (partial credit: 10 pts) + pricing page (7 pts) = 17 pts × 1.4 ICP fit (COO engaged, perfect title) = 24. Score suggests evaluation interest but no commitment signal yet. Recommended action: Send a direct email from a salesperson with a "here's what the calculator would have shown you" email with the relevant number filled in — this re-engages calculator abandoners and often re-ignites evaluation.

---

**TOP PREDICTIVE SIGNALS (from your historical pipeline data):**
1. ROI Calculator completion (75%+) → pipeline conversion: 31% (highest of all signals)
2. Pricing page 3+ visits in 14 days → pipeline conversion: 24%
3. Competitive comparison page viewed → pipeline conversion: 28%
4. Signal combination: ROI Calculator + Pricing 3x = pipeline conversion: 47% (3.1x single-signal rate)
5. False positive signal: Single blog post reads → pipeline conversion: 1.2% (deprioritize in scoring weight)

**SDR Threshold Recommendation:** Set alert at Score 70+. At Score 75+, historical data shows 27% pipeline conversion. At Score 60+, it drops to 14%. Current SDR capacity: 4 SDRs can work 25 alerts/week. At 70+ threshold, you'll generate approximately 18-22 alerts/week — within capacity. Pipeline expected from SDR-alerted accounts this month: 20 alerts × 27% conversion × $67K ACV = **$362K in pipeline expected from engagement scoring program.**

## Success Metrics

- HOT-tier account (75+) to pipeline conversion rate ≥ 25% within 60 days of SDR alert
- Total pipeline generated from engagement-scored accounts vs. form-fill-only leads increases by 40%+ within 90 days
- Average time from primary engagement signal to SDR first touch ≤ 4 hours for HOT accounts
- Buying committee detection rate (3+ contacts from same company identified) reaches 15%+ of all HOT accounts
- Engagement scoring reduces "surprise" inbound demos — percentage of demo requests from accounts with pre-existing engagement score 45+ target: 70% (meaning your scoring is predicting demand, not just reacting to it)
- ROI Calculator completion-to-pipeline conversion rate tracked monthly; if below 20%, review CTA placement and calculator UX
- Anonymous ICP session de-anonymization rate: target 25-35% of ICP company sessions identified within 60 days of de-anonymization tool deployment
- SDR outreach-to-reply rate for HOT engagement-scored accounts target ≥ 18% (vs. cold outbound average of 3-5%)

## Related Prompts

- [AI-Powered B2B SaaS Web Analytics Intelligence & Website Revenue Performance Optimization Engine](./AI-Powered-B2B-SaaS-Web-Analytics-Intelligence-&-Website-Revenue-Performance-Optimization-Engine.md)
- [AI-Powered B2B Anonymous Visitor Intelligence & Account Pipeline Identification Engine](../Website-Analytics-&-Behavioral-Intelligence/AI-Powered-B2B-Anonymous-Visitor-Intelligence-&-Account-Pipeline-Identification-Engine.md)
- [AI-Powered Customer Intent & Buying Signal Detection Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/AI-Powered-Customer-Intent-&-Buying-Signal-Detection-Intelligence-Engine.md)
- [AI-Powered B2B Customer Journey Intelligence & Multi-Touch Buyer Path Optimization Intelligence Engine](../Customer-Journey-Analytics/AI-Powered-B2B-Customer-Journey-Intelligence-&-Multi-Touch-Buyer-Path-Optimization-Intelligence-Engine.md)

## Integration Tips

- **HubSpot:** Create a custom "Buyer Engagement Score" contact and company property. Use HubSpot Workflows to automatically update scores based on engagement events (form fills, email clicks, page views, meeting bookings). Set a Workflow trigger: when Company Engagement Score ≥ 75 → create a task for the assigned SDR, send a Slack notification to #hot-accounts, and enroll the company in the HOT account email sequence. Use HubSpot's company-level scoring (not just contact scoring) to aggregate buying committee engagement across all contacts at the same domain.

- **Salesforce:** Build a custom Salesforce object "Account Engagement Score" with fields for Current Score, Score Trend, Last High-Intent Event, and Primary Contact Name. Use Salesforce Flow to trigger tasks and alerts. Connect to Pardot/Marketing Cloud for the scoring calculation. Build a Salesforce Dashboard "Pre-Pipeline Radar" showing all accounts 45+ that don't have an active Opportunity — this is your SDR's daily prospecting view.

- **GA4 + BigQuery:** Export GA4 event data to BigQuery daily. Write a SQL query that joins `events_*` tables by `user_pseudo_id` (anonymous) and `user_id` (known) to build engagement score at the user level. Join with 6sense company data (via IP lookup in a separate BigQuery table) to aggregate to account level. Schedule the query to run nightly and push results to a Looker Studio "Pre-Pipeline Intelligence" dashboard. This is the full-stack implementation of this prompt's scoring model.

- **6sense / Clearbit Reveal / RB2B:** These tools de-anonymize company-level website visitors. Connect them to GA4 via custom dimensions (use `gtag()` to set `user_properties` when a company is identified). This lets you segment GA4 engagement reports by ICP firmographic data. Set up a webhook: when 6sense identifies a new ICP company visiting, immediately check if they exist in Salesforce. If yes and no open opportunity, fire the SDR alert. If no Salesforce record, create a new Lead/Account automatically.

- **LinkedIn Campaign Manager:** Connect your CRM/MAP to LinkedIn Matched Audiences. Create an audience segment called "High-Engagement Accounts (Score 45+)" — upload company names weekly. Target this audience with competitive displacement ads, executive testimonial video ads, and ROI-focused content ads. This ensures that accounts actively researching you on your website simultaneously see your brand on LinkedIn, creating a surround-sound effect during their evaluation window. Budget: weight 3x more toward this segment vs. cold prospecting.

- **Slack / Teams:** Create a #pre-pipeline-radar Slack channel. Use Zapier or Make to send an automated alert when any account hits Score 75+: "🔴 HOT ACCOUNT: [Company Name] just hit Score [X]. Primary signal: [event]. ICP fit: [match criteria]. Suggested SDR: [@name]. CRM link: [url]. Recommended outreach angle: [2-sentence summary]." This makes engagement intelligence an ambient signal in the SDR team's daily workflow rather than a report they have to proactively check.

- **Outreach / Salesloft / Apollo:** When a HOT account alert fires, automatically create a prospect in Outreach/Salesloft and enroll them in the relevant engagement-based sequence (e.g., "ROI Calculator Sequence," "Competitive Evaluation Sequence," "Pricing Page High-Intent Sequence"). Each sequence should reference the specific engagement signal in the first touchpoint without being surveillance-creepy. The key: reference the topic they engaged with, not the fact that you know they were on your site.

## Troubleshooting

**Problem: The scoring model is generating too many HOT alerts and SDRs are overwhelmed — they're contacting everyone and conversion rates are low, causing them to lose faith in the system.**
Solution: This is a calibration problem, not a model failure. Lower the HOT threshold from 75 to 85 until you've validated the model. Pull the last 90 days of engagement data and calculate what % of accounts at each score tier actually converted to pipeline. If Score 75-84 is only converting at 8% (too low for SDR priority), move those to WARM and raise the HOT threshold. Simultaneously, audit the event weights: if a single low-intent event (e.g., single blog post read) is over-weighted, it can inflate scores for unqualified visitors. The goal is that HOT-tier accounts convert to pipeline at ≥ 20% — if they're converting at 8%, the threshold is too low or the weights are miscalibrated.

**Problem: The de-anonymization tool is identifying companies, but when SDRs reach out, the contacts say they were just doing research and aren't actively evaluating — creating friction in the SDR-prospect relationship.**
Solution: This is a signal interpretation problem. Not every company visiting your website is in an active buying cycle — some are competitors doing research, analysts writing reports, or prospects early in a problem-awareness phase. Add a "buying cycle qualifier" to the SDR brief: before outreach, SDRs should verify the engagement pattern makes sense for a buyer (multiple visits across multiple days = evaluation; single deep session from a known journalist domain = research, not prospect). Also: update outreach language to be exploratory, not assumptive. "I noticed companies like yours often start looking at [solution category] when [business trigger]. Is that relevant to you right now?" beats "I see you've been researching us." The goal is to be helpful during their research, not to call them out.

**Problem: Historical data shows that ROI Calculator completions convert to pipeline at 31%, but after launching the SDR alert program, the conversion rate is only 9% — significantly below the historical benchmark.**
Solution: Three likely causes. First, the historical data may have selection bias — in the past, only highly motivated prospects completed the ROI calculator (because it wasn't actively promoted), creating artificially high conversion rates. Now that you're tracking all calculator completions and following up on all of them, you're capturing more casual explorers whose intent is lower. Fix: add a qualification step post-calculator — a single-question survey ("Are you evaluating procurement automation in the next 6 months?") to filter HOT vs. researching completions. Second, SDR outreach may be too aggressive or too slow — benchmark: contact within 4 hours of calculator completion; contact rate > 4 hours shows 60% lower response rate. Third, outreach messaging may not reference the calculator output effectively. Fix: A/B test subject lines — "Based on your procurement spend, here's what you'd save" vs. "Following up on your efficiency question" and measure reply rates by variant.

## Version History
- v1.0: Initial creation (auto-generated)
