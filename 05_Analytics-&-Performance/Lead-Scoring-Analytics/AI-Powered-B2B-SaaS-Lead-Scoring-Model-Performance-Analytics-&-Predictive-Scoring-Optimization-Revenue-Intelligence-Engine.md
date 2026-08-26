# AI-Powered B2B SaaS Lead Scoring Model Performance Analytics & Predictive Scoring Optimization Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, saas, analytics, lead-scoring, predictive, mql, pipeline-quality, revenue-operations, ai-automation

## Overview
This prompt engineers a complete AI-powered lead scoring analytics and optimization system that continuously measures scoring model accuracy, detects score decay and model drift, calibrates MQL/SQL thresholds against real conversion data, and surfaces actionable recommendations to maximize the pipeline contribution of every marketing-qualified lead — fully automated, zero manual data analysis required. Use it when your lead scoring model was set up more than 90 days ago, when your MQL-to-SQL conversion rate has drifted from baseline, or when your sales team is complaining about lead quality without you having the data to respond.

## Quick Copy-Paste Version

You are a revenue operations analytics expert with 15 years of experience optimizing lead scoring models for B2B SaaS companies.

Analyze my lead scoring model performance and generate a complete optimization plan:

CURRENT STATE:
- Lead scoring platform: [HubSpot / Marketo / 6sense / Salesforce Einstein / custom / other]
- Current MQL score threshold: [e.g., 100 points]
- Current MQL-to-SQL conversion rate: [e.g., 22%]
- Baseline MQL-to-SQL rate when model was built: [e.g., 31%]
- Model age: [e.g., 14 months since last recalibration]
- Monthly MQL volume: [e.g., 340 MQLs/month]
- Average days from MQL to closed-won: [e.g., 67 days]
- Top 3 scoring signals currently used: [e.g., job title fit, email opens, website visits]
- Win rate from marketing-sourced pipeline: [e.g., 18%]

DELIVERABLES:

1. SCORING MODEL HEALTH AUDIT
Evaluate 8 key model health indicators with status (Critical / Warning / Healthy) and immediate action.

2. THRESHOLD CALIBRATION ANALYSIS
Using the conversion data I provide, calculate optimal MQL score thresholds by ICP segment and recommend specific threshold adjustments with projected pipeline impact.

3. SIGNAL QUALITY SCORECARD
Score each current signal type (demographic, behavioral, firmographic, intent) on predictive power, recency bias risk, and decay rate.

4. AI AGENT OPTIMIZATION RULES
Write the conditional logic for an autonomous agent to continuously monitor scoring health, detect drift, and trigger recalibration — no human intervention required.

5. 90-DAY OPTIMIZATION ROADMAP
Prioritize scoring model improvements by revenue impact, with implementation steps for each.

Output as a complete lead scoring analytics report ready to present to the CMO and hand off to the RevOps team for implementation.

## Advanced Customizable Version

ROLE: You are an elite revenue operations analytics engineer and machine learning model auditor specialized in B2B SaaS go-to-market systems. You have rebuilt lead scoring models for 40+ B2B SaaS companies, recovering $2M–$18M in annual pipeline that was being lost to misclassified or over-scored leads. You combine predictive modeling principles, behavioral economics, and GTM system design to build scoring architectures that improve, not degrade, over time.

Your output will be directly used to recalibrate a live lead scoring system affecting an active revenue pipeline. Every recommendation must be specific, data-grounded, and executable by a RevOps team without a data science degree.

═══════════════════════════════════════════
SYSTEM INTELLIGENCE INPUT
═══════════════════════════════════════════

Company: [Company Name]
Industry: [e.g., HR Tech, FinTech, Developer Tools]
ACV: [e.g., $28,000 average annual contract value]
Sales Motion: [Choose: Enterprise field sales / Mid-market hybrid / SMB self-serve / PLG + sales-assist]
Sales Cycle Length: [e.g., 45 days SMB, 90 days mid-market, 180+ days enterprise]

SCORING SYSTEM ARCHITECTURE:
  → Platform: [HubSpot Lead Scoring / Marketo Engagement Score / 6sense Predictive / Salesforce Einstein / MadKudu / custom model]
  → Model Type: [Rule-based / Predictive ML / Hybrid]
  → Last Recalibration: [Date or "Never formally recalibrated"]
  → Current MQL Threshold: [Score value at which a lead becomes an MQL]
  → Current SQL Threshold: [Score at which SDR/AE accepts the lead as sales-ready]

SCORING SIGNAL INVENTORY:
  List every signal currently used in your model with its current weight:
  
  Demographic/Firmographic Signals:
  → [e.g., Job Title: VP/Director+ = +25 pts, Manager = +15 pts, IC = +5 pts]
  → [e.g., Company Size: 200-2000 employees = +20 pts, 50-199 = +10 pts]
  → [e.g., Industry vertical match = +15 pts]
  → [e.g., Technology stack match (uses Salesforce = +10 pts)]
  
  Behavioral Signals:
  → [e.g., Pricing page visit = +30 pts]
  → [e.g., Email open = +2 pts per open]
  → [e.g., Email click = +8 pts per click]
  → [e.g., Content download = +10 pts per asset]
  → [e.g., Webinar attendance = +20 pts]
  → [e.g., Demo request form = +50 pts]
  → [e.g., Free trial signup = +60 pts]
  
  Third-Party Intent Signals (if applicable):
  → [e.g., 6sense / Bombora / G2 intent surge = +25 pts]
  → [e.g., G2 competitor profile view = +15 pts]
  
  Negative Scoring (score decay):
  → [e.g., No email open in 60 days = -10 pts]
  → [e.g., Unsubscribe from email = -100 pts, disqualified]
  → [e.g., Competitor domain detected = -50 pts]

CONVERSION DATA (provide actuals for 12-month lookback period):
  Total MQLs generated: [X]
  MQLs accepted by sales (SALs): [X] → MQL-to-SAL rate: [X%]
  SALs converted to opportunities (SQLs): [X] → SAL-to-SQL rate: [X%]
  SQLs closed won: [X] → SQL-to-Win rate: [X%]
  
  MQL-to-Won rate by score tier (if available):
  → Score 100-129: [X% won rate, X$ average ACV]
  → Score 130-159: [X% won rate, X$ average ACV]
  → Score 160-189: [X% won rate, X$ average ACV]
  → Score 190+: [X% won rate, X$ average ACV]
  
  MQL-to-Won rate by primary source:
  → Paid Search: [X% MQL-to-Won]
  → Content/Organic: [X% MQL-to-Won]
  → Events/Webinars: [X% MQL-to-Won]
  → Partner/Referral: [X% MQL-to-Won]
  → Outbound-touched Inbound: [X% MQL-to-Won]
  
  MQL-to-Won rate by ICP tier:
  → Tier 1 (Perfect ICP): [X% MQL-to-Won]
  → Tier 2 (Strong ICP): [X% MQL-to-Won]
  → Tier 3 (Weak ICP): [X% MQL-to-Won]

CURRENT PAIN SIGNALS:
  → Sales rejection rate (MQL rejected at triage): [X%] (Healthy: <25%; Warning: 25-40%; Critical: >40%)
  → "Wrong person" rejections: [X% of rejected MQLs]
  → "Not enough intent" rejections: [X% of rejected MQLs]
  → "Right company, wrong timing" rejections: [X% of rejected MQLs]
  → Avg days from MQL to sales first-touch: [X days] (Healthy: <24h; Warning: 24-72h; Critical: >72h)
  → MQL volume trend (last 90 days vs. prior 90): [Up/Down X%]
  → Has sales or RevOps complained about lead quality? [Yes/No, and what specifically]

═══════════════════════════════════════════
DELIVERABLE 1: LEAD SCORING MODEL HEALTH AUDIT
═══════════════════════════════════════════

Evaluate all 8 diagnostic categories. For each: Status (Critical / Warning / Healthy), Evidence from the data provided, and Immediate Action Required.

DIAGNOSTIC 1: MQL THRESHOLD ACCURACY
  Objective: Is the current threshold score actually predictive of sales-readiness?
  
  Analysis Framework:
  → Calculate the "precision" of your current threshold: What % of leads above threshold become closed-won?
  → Calculate the "recall" of your current threshold: What % of closed-won customers were MQL-flagged at the right time?
  → Precision × Recall trade-off: A high threshold catches fewer but better leads; a low threshold catches more but wastes sales capacity
  → Benchmark: Industry-leading B2B SaaS scoring models target Precision ≥ 40% at MQL (i.e., 40%+ of MQLs become closed-won opportunities)
  
  Red Flags for Immediate Recalibration:
  → MQL-to-Won rate < 15% → Threshold is too low; you're flooding sales with noise
  → Sales rejection rate > 40% → Threshold is too low OR signal weights are wrong
  → MQL-to-Won rate > 60% → Threshold is too high; you're starving sales of volume; leaving revenue on the table
  → Score tier data shows higher win rates for Score 130-159 than Score 160-189 → Model is not monotonically predictive (broken)

DIAGNOSTIC 2: SIGNAL DECAY & MODEL DRIFT
  Objective: Are the signals that predicted conversion 18 months ago still predictive today?
  
  Analysis Framework:
  → Model drift occurs when buyer behavior changes but the scoring model doesn't adapt
  → Calculate conversion rate by signal: Do leads with high behavioral scores (email opens, content downloads) still convert at the same rate as when the model was built?
  → Key drift indicators:
    - Email open as a signal: Post-Apple Mail Privacy Protection (MPP), open rates are inflated by machine opens. If email opens are weighted >5 pts each, your model is likely over-scoring passive leads.
    - Webinar attendance score: If you're scoring webinar attendance +20 pts but post-event MQL-to-SQL rate has dropped, the signal has decayed.
    - Content download score: Gated content completion has declined industry-wide; if your model treats all downloads equally regardless of content depth (whitepaper = infographic), re-weight by content type.
  
  Decay Rate Framework:
  → High-decay signals (re-evaluate every 6 months): Email opens, page views, content downloads
  → Medium-decay signals (re-evaluate annually): Job title fit, company size fit, webinar attendance
  → Low-decay signals (stable 12-18 months): Technology stack signals, G2/Bombora intent surge, demo requests, pricing page visits, trial signups

DIAGNOSTIC 3: ICP FIT VS. BEHAVIORAL WEIGHT BALANCE
  Objective: Is demographic/firmographic fit appropriately weighted vs. behavioral engagement?
  
  Analysis Framework:
  → Calculate win rate for leads that are: (a) High ICP + Low Behavior, (b) Low ICP + High Behavior, (c) High ICP + High Behavior
  → Most B2B SaaS models are over-weighted on behavior (easy to measure) vs. firmographic fit (harder to operationalize)
  → Benchmark finding: High-ICP leads with low behavioral scores close at 2–3x the rate of Low-ICP leads with high behavioral scores in the majority of B2B SaaS models
  → Recommended weight split: Firmographic/ICP fit: 35–45% of max score; Behavioral engagement: 45–55%; Third-party intent: 10–20%
  
  Red Flag: If a single behavioral action (e.g., demo request = +50 pts) can push a completely non-ICP lead to MQL status alone, your model has a structural flaw.

DIAGNOSTIC 4: SCORING SIGNAL COMPLETENESS
  Objective: Are high-value buying signals unscored or underscored?
  
  Frequently Missing Signals:
  → Pricing page repeat visits (2+ visits = 3x conversion rate vs. single visit — score +40 pts or more)
  → ROI calculator or TCO tool completion (extremely high intent; often untracked)
  → Competitive comparison page visits ("vs. [Competitor]" pages — 4x conversion rate for high-ICP leads)
  → G2 profile views of your product (if 6sense/G2 Buyer Intent is available)
  → Job change signal: Champion from existing customer joins a new company (often untracked; highest-value warm lead type)
  → LinkedIn employee count change: +30% hiring growth in past 90 days (growth indicator — high expansion potential)
  → Technology add events: New Salesforce, HubSpot, or complementary stack addition detected in technographic data

DIAGNOSTIC 5: NEGATIVE SCORING & DISQUALIFICATION LOGIC
  Objective: Is score suppression and recycling working correctly?
  
  Evaluation Criteria:
  → Are competitor employees properly excluded? (Check: email domain blocklist completeness)
  → Is score decay (time-based negative scoring) implemented? Leads should not retain high scores indefinitely from past engagement.
  → Recommended decay rules: -5 pts per 30 days of no CRM activity above the MQL threshold; reset to [MQL threshold - 20] if no activity for 180 days
  → Are disqualified leads properly excluded from MQL count and not re-triggering the same low-quality sequence?
  → "Zombie lead" detection: Leads that MQL repeatedly (3+ times) without converting — these inflate MQL counts and indicate either a scoring flaw or a CRM hygiene issue

DIAGNOSTIC 6: SCORE DISTRIBUTION HEALTH
  Objective: Is the score distribution bell-curve shaped (healthy) or bimodal/cliff-shaped (broken)?
  
  Interpretation:
  → Healthy distribution: Gradual bell curve peaking around the midpoint of your 0-200 scale, with 15-25% above MQL threshold
  → Cliff distribution (common): Massive spike just above and just below threshold — signals that content/sequences are gaming the system by pushing people just over the line
  → Bimodal distribution: Two peaks — one around 20 pts (passive database) and one around 140 pts (recently engaged) — indicates a recycling or re-engagement trigger pushing cold leads back to scoring visibility without genuine intent change
  → Target: 12-20% of scoreable contacts above MQL threshold at any given time; >30% suggests threshold is too low

DIAGNOSTIC 7: SALES ADOPTION & TRIAGE SPEED
  Objective: Is the scoring model trusted by sales, and are MQLs being acted on quickly?
  
  Metrics to Evaluate:
  → SLA compliance: What % of MQLs receive first-touch contact within 24h? (Best-in-class: >85%)
  → MQL rejection rationale quality: Are rejections tagged with specific reasons (wrong person, wrong company, wrong timing, already a customer)? If not, you cannot improve scoring accuracy without this data.
  → Sales sentiment score: If available from Salesforce rejection notes or SDR feedback, what is the qualitative trust level in MQL quality?
  → First-to-respond time: Studies show leads contacted within 5 minutes convert at 21x the rate of leads contacted after 30 minutes — scoring without SLA enforcement wastes all upstream model investment

DIAGNOSTIC 8: MULTI-TOUCH CONTRIBUTION ACCURACY
  Objective: Are the right marketing programs getting credit for pipeline quality?
  
  Analysis:
  → Programs that generate high-scoring leads: List the top 5 programs by average MQL score
  → Programs that generate high-converting leads (by MQL-to-won rate): List the top 5 programs by conversion quality
  → If these two lists are different, your budget allocation is misaligned with actual revenue contribution
  → Calculate: "Revenue Efficiency Score" = (Won ACV / Marketing Program Cost) × 100 for each MQL source
  → This reveals which programs produce expensive MQLs that don't close vs. programs that produce efficient, high-converting pipeline

═══════════════════════════════════════════
DELIVERABLE 2: THRESHOLD CALIBRATION & ICP-SEGMENTED SCORING
═══════════════════════════════════════════

Using the conversion data provided, calculate optimal MQL thresholds and segment-specific scoring adjustments.

STEP 1: PRECISION-RECALL OPTIMIZATION

Run this analysis for three threshold scenarios:

Current Threshold Analysis:
  At current threshold [X]:
  → MQL Volume per month: [N]
  → MQL-to-Won rate: [X%]
  → Revenue from MQL-sourced deals: [$X/month]
  → False positive rate (MQLs that never reach opportunity stage): [X%]
  → Sales capacity consumed by false positives: [X hours/SDR/month at Y minutes per MQL triage]

Lower Threshold Scenario (Current - 15%):
  At threshold [X × 0.85]:
  → Projected MQL volume increase: [+X%]
  → Projected MQL-to-Won rate (will drop): [X%]
  → Net revenue impact: [+/- $X]
  → Additional sales triage capacity required: [X hours/SDR/month]

Higher Threshold Scenario (Current + 15%):
  At threshold [X × 1.15]:
  → Projected MQL volume decrease: [-X%]
  → Projected MQL-to-Won rate (will rise): [X%]
  → Net revenue impact: [+/- $X]
  → Pipeline risk of missed qualified leads: [X%]

STEP 2: ICP-SEGMENTED THRESHOLD ARCHITECTURE

Recommend SEPARATE MQL thresholds by ICP segment (most models use a single threshold — this is a major optimization opportunity):

Tier 1 ICP Accounts (Perfect fit: right industry + right size + right tech stack):
  → Recommended MQL threshold: [Current threshold × 0.75] — rationale: ICP fit is itself a major conversion signal; lower behavioral bar required
  → Signal required at minimum: Pricing page OR demo request OR intent surge (at least one high-intent signal)
  → Expected MQL-to-Won rate at this tier: [X%]

Tier 2 ICP Accounts (Strong fit: 2 of 3 ICP dimensions match):
  → Recommended MQL threshold: [Current threshold] — standard threshold applies
  → Expected MQL-to-Won rate at this tier: [X%]

Tier 3 Non-ICP Accounts (1 of 3 ICP dimensions match or none):
  → Recommended MQL threshold: [Current threshold × 1.25] — require substantially more behavioral proof before alerting sales
  → Expected MQL-to-Won rate at this tier: [X%]
  → Alternative: Consider redirecting Tier 3 MQLs to an automated nurture track (no human SDR triage) until score reaches [Tier 1 threshold] OR they self-schedule a demo

STEP 3: SIGNAL WEIGHT RECALIBRATION RECOMMENDATIONS

For each current scoring signal, provide:
| Signal | Current Weight | Recommended Weight | Rationale |
|---|---|---|---|
| Pricing page visit | [+X] | [+X] | [e.g., "2.8x higher conversion rate than avg — underweighted"] |
| Email open | [+X] | [+X] | [e.g., "Post-MPP, opens are machine-inflated — reduce to half current weight"] |
| Content download | [+X] | [+X] | [e.g., "Weight by content funnel stage: TOFU = +5, MOFU = +12, BOFU = +20"] |
| Demo request | [+X] | [+X] | [e.g., "Highest-predictive single signal — confirm current weight is ≥ 50% of MQL threshold"] |
| Webinar attendance | [+X] | [+X] | [e.g., "Distinguish: live attendance = +20; on-demand replay = +10; registered no-show = +5"] |
| Job title seniority | [+X] | [+X] | [e.g., "Stable signal — maintain weight; add economic buyer bonus: C-Suite at ≥500 employees = +15"] |
| Intent surge (3P) | [+X] | [+X] | [e.g., "Intent signals have 2–4 week decay; add time decay: fresh signal +25, >30 days old +10"] |

NEW SIGNALS TO ADD:
| Signal | Recommended Score | Implementation Note |
|---|---|---|
| Pricing page (2nd+ visit within 7 days) | +40 pts | Repeat pricing intent — highest behavioral predictor available |
| ROI calculator completion | +45 pts | Self-qualification signal; high-intent visitor profiling their own use case |
| Competitive comparison page visit | +25 pts | Active evaluation stage; high close urgency |
| Job change signal (champion at existing customer) | +80 pts | Warm lead — existing relationship; 5-8x conversion vs. cold lead |
| Hiring surge signal (+25% headcount in 90 days) | +15 pts | Growth signal; correlates with budget availability |
| G2 profile view (if Buyer Intent enabled) | +30 pts | In-market buyer researching solution category |

═══════════════════════════════════════════
DELIVERABLE 3: SIGNAL QUALITY SCORECARD
═══════════════════════════════════════════

Evaluate each signal category across 4 dimensions (score 1-5):

| Signal Type | Predictive Power | Recency Bias Risk | Decay Rate | Gaming Risk | Overall Grade |
|---|---|---|---|---|---|
| Demo Request / Trial Signup | 5/5 | 1/5 (low risk) | Slow | Low | A+ |
| Pricing Page Visit | 5/5 | 2/5 | Medium | Low | A |
| Third-Party Intent (6sense/Bombora) | 4/5 | 3/5 | Fast (2-4 weeks) | Low | A- |
| ROI Calculator / TCO Tool | 5/5 | 1/5 | Slow | Low | A |
| Job Title / Seniority Fit | 4/5 | 1/5 | Slow | Medium | A- |
| Company Size / Firmographic | 3/5 | 1/5 | Very Slow | Low | B+ |
| Technology Stack Match | 4/5 | 1/5 | Medium | Low | A- |
| Webinar Attendance (live) | 3/5 | 2/5 | Medium | Medium | B |
| Content Download (BOFU) | 3/5 | 3/5 | Fast | High | B- |
| Email Click-Through | 3/5 | 4/5 | Fast | High | C+ |
| Email Open | 1/5 | 5/5 (MPP inflation) | Very Fast | Very High | D |
| Page Views (generic) | 2/5 | 4/5 | Fast | High | D+ |

GAMING RISK MITIGATION:
For any signal with Gaming Risk ≥ Medium, implement velocity limits:
→ Email opens: Cap scoring contribution at maximum 10 pts per contact (regardless of open count)
→ Content downloads: Score the first download per asset type only; deduplicate within 30-day window
→ Page views: Cap at +5 pts per unique page per session; do not score repeat visits to same page within 7 days
→ Webinar registrations: Score registration at +5 pts; add remaining +15 pts only upon attendance confirmation

═══════════════════════════════════════════
DELIVERABLE 4: AI AGENT ORCHESTRATION LOGIC — CONTINUOUS SCORING HEALTH MONITORING
═══════════════════════════════════════════

Write complete conditional logic for an autonomous AI agent that monitors the lead scoring system without human intervention:

DAILY MONITORING RULES:

  DRIFT DETECTION (run daily):
    IF [rolling_7day_MQL_to_SAL_rate] drops > 10% below [baseline_MQL_to_SAL_rate]:
      → Flag: "MQL Quality Drift Detected"
      → Trigger: Identify top 5 signal changes in last 30 days (new content launch? New campaign? Channel mix shift?)
      → Action: Pause MQL delivery to sales pipeline for Tier 3 accounts until root cause identified
      → Notify: RevOps Lead via Slack + email with data summary

  VOLUME ANOMALY DETECTION (run daily):
    IF [daily_MQL_count] > [rolling_30day_avg × 1.5]:
      → Flag: "MQL Volume Spike — Quality Risk"
      → Trigger: Audit top 3 signal contributors for last 48h; check for scoring exploit (bulk email campaign inflating scores?)
      → Action: Temporarily reduce weight of any single signal that accounts for >40% of today's MQL triggers by 25%
      → Restore: After 7-day quality confirmation (MQL-to-SAL rate ≥ baseline)

    IF [daily_MQL_count] < [rolling_30day_avg × 0.5]:
      → Flag: "MQL Volume Drought — Pipeline Risk"
      → Trigger: Check signal health (email deliverability? Campaign paused? Intent data feed down?)
      → Notify: Demand Gen team with diagnostic data

  ZOMBIE LEAD DETECTION (run weekly):
    IF [contact.mql_count] ≥ 3 AND [contact.opportunity_created] = FALSE AND [contact.sales_rejection_count] ≥ 2:
      → Action: Remove contact from active scoring; move to "Long-Term Nurture" track
      → Score: Reset to [MQL threshold - 30]; freeze from MQL re-qualification for 90 days
      → Flag: Contact in CRM with tag [zombie_lead]; route to marketing re-qualification sequence, not SDR triage

WEEKLY PERFORMANCE AUDIT (run every Monday, 6 AM — auto-report generated):

  WEEK-OVER-WEEK COMPARISON:
    → MQL volume (this week vs. last week vs. 4-week rolling avg)
    → MQL-to-SAL rate (this week vs. baseline)
    → Average MQL score at time of conversion to opportunity (trending up = healthy; down = model drift)
    → SDR triage speed: Avg hours from MQL timestamp to first sales touchpoint (target: <24h; alert if >48h average)
    → Score distribution percentiles: What % of scoreable contacts are in each decile?

  SIGNAL EFFECTIVENESS TRACKING:
    For each active scoring signal, track weekly:
    → Signal fire rate: How many contacts triggered this signal this week?
    → Signal-to-MQL conversion: Of contacts who triggered this signal, what % became MQLs this week?
    → Signal-to-won correlation (12-week lag): Of contacts who triggered this signal 12 weeks ago, what % are now closed-won?
    → Alert if any signal's 12-week won correlation drops >20% below historical baseline

  THRESHOLD PERFORMANCE VALIDATION:
    Monthly (first Monday of each month):
    → Run Precision-Recall analysis using trailing 90-day conversion data
    → Compare current threshold win rate vs. theoretical optimal threshold
    → If optimal threshold differs from current by >15 points: trigger "Threshold Recalibration Recommendation" alert with supporting data

QUARTERLY FULL MODEL RECALIBRATION TRIGGER:

  Automatically trigger full model recalibration review if ANY of the following are true:
  → MQL-to-Won rate has declined >15% from previous quarter
  → Sales rejection rate has increased >10 percentage points from baseline
  → More than 30% of score distribution is within ±10 points of current threshold (cliff distribution detected)
  → Net new signal types have been identified (new intent provider, new product behavior) but not integrated
  → It has been > 12 months since last formal recalibration

SUPPRESSION AND EXCLUSION MAINTENANCE (run monthly):
  → Refresh domain blocklist: Pull all closed-won and closed-lost accounts; confirm competitor domain list is current
  → Validate ICP tier assignments: Sample 100 random accounts; confirm tier assignments match current ICP definition
  → Audit data source health: Confirm all third-party intent data feeds (6sense, Bombora, G2) are returning data within expected volume ranges
  → Check Salesforce/CRM data cleanliness: Flag contacts with missing company data, invalid email domains, or duplicate records that may be inflating MQL counts

═══════════════════════════════════════════
DELIVERABLE 5: 90-DAY SCORING OPTIMIZATION ROADMAP
═══════════════════════════════════════════

Priority-ordered implementation plan with revenue impact estimates:

WEEK 1-2: EMERGENCY TRIAGE (Zero Development Required)
  → Implement email open score cap: Reduce email open from [current weight] to max +10 pts total per contact
  → Add pricing page repeat visit signal: Configure CRM to detect 2+ pricing page visits within 7 days → +40 pts
  → Update ICP tier tagging: Export your account list, apply Tier 1/2/3 designations based on ICP criteria, import as custom field
  → Projected impact: 10-20% reduction in low-quality MQLs within 30 days

WEEK 3-6: THRESHOLD AND WEIGHT RECALIBRATION
  → Implement ICP-segmented thresholds: Tier 1 at [recommended]; Tier 2 at [current]; Tier 3 at [recommended +25%]
  → Recalibrate signal weights per Deliverable 2 Scorecard
  → Activate zombie lead suppression rule (3+ MQL re-qualifications without conversion)
  → Enable MQL rejection reason tracking in Salesforce (required dropdown: wrong person / wrong company / wrong timing / already a customer)
  → Projected impact: MQL-to-SAL rate improvement of 5-12 percentage points

WEEK 7-10: MISSING SIGNAL INTEGRATION
  → Integrate ROI calculator completion event into scoring
  → Integrate competitive comparison page visit scoring
  → Connect technographic data provider (Clearbit / ZoomInfo) for technology stack signals if not active
  → Implement job change signal via Sales Navigator or Clay.com webhook → score bump + SDR notification
  → Projected impact: 15-25% increase in high-intent MQL identification

WEEK 11-13: AI AGENT DEPLOYMENT & AUTOMATED MONITORING
  → Deploy weekly autonomous health report (Deliverable 4 rules) via HubSpot Workflow + Slack webhook
  → Activate drift detection alert logic
  → Set up quarterly recalibration calendar invite with automated data pull
  → Conduct first full A/B test: Run current model vs. recalibrated model for 30 days on 50/50 new lead split; measure MQL-to-SAL and MQL-to-Won rates
  → Projected impact: Ongoing model improvement velocity; prevents silent model degradation

REVENUE IMPACT PROJECTION (illustrative):
  Starting State: 340 MQLs/month × 22% MQL-to-Won = 75 marketing-influenced deals/year
  Post-Optimization State: 290 MQLs/month (better quality, fewer junk) × 34% MQL-to-Won = 99 deals/year
  Net Impact: +24 additional closed deals/year × $28,000 ACV = +$672,000 incremental revenue/year
  (Revenue impact realized at 6-9 month lag from implementation)

## Example Input/Output

**Input Example:**
Company: Lumenwave — a B2B SaaS revenue intelligence platform for mid-market companies
ACV: $24,000
Model Age: 18 months since last recalibration
Current MQL Threshold: 120 points
Current MQL-to-SAL rate: 58% → MQL-to-SQL: 41% → SQL-to-Won: 29%
Baseline at model build: MQL-to-SAL: 71% → MQL-to-SQL: 54% → SQL-to-Won: 31%
Monthly MQL volume: 287
Sales rejection rate (at triage): 42% ("not enough intent" is most common rejection reason — 61% of rejections)
Top signals: Email click (+8), Content download (+12), Pricing page (+25), Job title VP+ (+20), Demo request (+50)
Email opens: currently scored at +3 per open, no cap

**Sample Output — Diagnostic 1 (Threshold Accuracy):**

STATUS: ⚠️ WARNING — Threshold Recalibration Recommended

Evidence: 
- Current MQL-to-SAL rate has declined 13 percentage points from baseline (71% → 58%) — material quality degradation
- Sales rejection rate of 42% exceeds the 40% critical threshold; 61% of rejections cite "not enough intent" — a signal weighting problem, not an ICP fit problem
- The "not enough intent" rejection pattern suggests email and content engagement signals are overweighted relative to high-intent behavioral signals (pricing page, demo request, competitive comparison)
- Score distribution analysis (if provided) would likely show a cliff shape just above 120 — the current threshold

Root Cause Hypothesis:
Your email open signal (+3 per open, uncapped) is the primary culprit. Post-Apple MPP, email open rates have inflated by 25-40% industry-wide due to machine pre-loading. A contact who receives 15 emails over 6 months now accumulates +45 pts from email opens alone — before taking any genuine interest action. Combined with a whitepaper download (+12) and VP+ job title (+20), that's 77 points (64% of MQL threshold) from signals that require zero genuine buying intent.

Immediate Action (Week 1):
1. Cap email open contribution: Maximum +10 pts per contact total (regardless of open count). Implement retroactively — this will immediately drop approximately 30-40% of borderline MQLs below threshold, resolving the volume problem without touching threshold.
2. Add "not enough intent" rejection code to Salesforce: Mandatory for all SDR rejections this week. You need this data to validate recalibration impact in 30 days.
3. Run the Precision-Recall calculation with 12-month historical data to confirm optimal threshold recommendation before making threshold changes.

**Sample Output — Signal Weight Recalibration Excerpt:**

| Signal | Current Weight | Recommended Weight | Rationale |
|---|---|---|---|
| Email open | +3 pts (uncapped) | +2 pts (max +10 total) | MPP inflation; uncapped creates 45-pt phantom engagement for passive contacts |
| Email click | +8 pts | +10 pts | Genuine intent; click requires human choice; slight increase justified |
| Pricing page (first visit) | +25 pts | +30 pts | Underweighted vs. conversion data; pricing intent is strongest predictive behavioral signal |
| Pricing page (2nd+ visit, 7 days) | Not tracked | +40 pts | Repeat pricing research = active evaluation; add this net-new signal |
| Demo request form | +50 pts | +55 pts | Highest-intent signal; raise to ensure it single-handedly MQLs any ICP-fit contact |
| Content download (TOFU) | +12 pts | +6 pts | Awareness-stage assets provide weak intent signal; cut in half |
| Content download (BOFU: ROI guide, comparison sheet) | +12 pts | +20 pts | Differentiate by content intent stage; BOFU downloads are 3x more predictive |

## Success Metrics

**Model Health Targets (post-optimization, 90-day window):**
- MQL-to-SAL rate: Recover to within 5 percentage points of original baseline (e.g., from 58% back to ≥66%)
- Sales rejection rate: Below 25% (from current 42%); "not enough intent" rejections below 30% of all rejections
- MQL volume: Acceptable reduction of 10-20% (higher quality > higher volume)
- Average hours from MQL to first-touch: ≤24h for 85%+ of MQLs (an SDR SLA enforcement metric, not a scoring metric — but scoring quality drives trust and speed)

**Business Impact Indicators:**
- MQL-to-Won rate (12-month trailing): Target improvement of 8-15 percentage points from pre-optimization baseline
- Revenue efficiency per MQL: (Closed ACV from MQL-sourced pipeline) / (Total MQL count) — this should increase as model quality improves
- Marketing budget reallocation: With improved source-level conversion data, identify which programs to increase vs. cut based on MQL quality score (not just volume)

**AI Agent Monitoring KPIs (weekly):**
- Drift detection alerts generated: Target 0 per month (alerts = problems); track alert frequency as leading indicator of system health
- Zombie lead suppression rate: How many contacts are being suppressed per month — high rates indicate acquisition quality issues upstream
- Threshold auto-recalibration triggers: Should fire 0-1 times per year; more frequent triggering indicates unstable data environment

## Related Prompts
- [Predictive Lead Scoring Architecture & Revenue Qualified Pipeline Management](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Scoring-&-Pipeline-Management/AI-Powered-B2B-SaaS-Predictive-Lead-Scoring-Architecture-&-Revenue-Qualified-Pipeline-Management-Intelligence-Engine.md)
- [Full-Funnel Demand Generation Analytics & Revenue Pipeline Performance](../Demand-Generation-Analytics/AI-Powered-B2B-SaaS-Full-Funnel-Demand-Generation-Analytics-&-Revenue-Pipeline-Performance-Intelligence-Engine.md)
- [Marketing-to-Sales Funnel Handoff Analytics & Revenue Accountability](../Revenue-Operations-Analytics/AI-Powered-B2B-SaaS-Marketing-to-Sales-Funnel-Handoff-Analytics-&-Revenue-Accountability-Intelligence-Engine.md)
- [Demand Waterfall Analytics & Lead Stage Conversion Intelligence](../Demand-Generation-Program-Analytics/AI-Powered-B2B-SaaS-Demand-Waterfall-Analytics-&-Lead-Stage-Conversion-Intelligence-Engine.md)

## Integration Tips

**HubSpot:**
- Access Lead Scoring under CRM → Contacts → Lead Scoring; rebuild weights using Contact-based scoring properties
- Create custom Contact properties: `mql_count`, `last_mql_date`, `cumulative_mql_rejections`, `lead_tier` (Tier 1/2/3), `zombie_lead` (boolean)
- Build the Drift Detection workflow using HubSpot Workflows with "Contact score changes" enrollment trigger; add Slack notification step via native Slack integration
- Use HubSpot's "Calculate property" feature to compute `days_since_mql_to_sal` for SLA tracking
- Report on scoring performance using the Custom Report Builder — filter by `lead_tier` to see Tier 1 vs. Tier 3 MQL-to-Won rates side by side

**Marketo:**
- Rebuild scoring program using the "Default Program" container with separate scoring streams per ICP tier
- Use Smart Campaigns with "Score Changes" trigger to fire AI agent alerts via webhook to Slack or PagerDuty
- Leverage Marketo's "Engagement Program" to move zombie leads automatically to long-term nurture track based on `mql_count` threshold
- Connect Marketo to Salesforce with bi-directional sync: Salesforce rejection reason → Marketo activity log → informs next scoring recalibration

**Salesforce Einstein Lead Scoring:**
- Enable Einstein Lead Scoring in Setup → Feature Settings → Sales → Lead Scoring
- Einstein automatically identifies conversion predictors from your CRM data — use its top factors list to validate or challenge your manual signal weights
- Create custom fields: `marketing_iq_tier` (ICP tier), `scoring_model_version` (for A/B test tracking), `mql_rejection_reason` (picklist: wrong person / wrong company / wrong timing / other)
- Build a Flow to auto-tag zombie leads: Criteria: Opportunity count = 0 AND MQL count ≥ 3 AND Created Date > 12 months ago

**6sense / Bombora (Intent Data Layer):**
- Map intent topic surges to scoring events using 6sense's CRM sync or Bombora's HubSpot/Salesforce connector
- Weight intent signals with time decay: Fresh surge (< 7 days old) = full score; 8-21 days = 50% weight; > 21 days = 0 (suppress signal)
- Use 6sense's Account Reach & Engagement Score as a lead scoring input rather than individual contact signals for ABM-adjacent scoring models

**Zapier / Make (No-code implementation):**
- Webhook trigger from CRM → Zapier → OpenAI GPT API call to classify rejection reason quality → update CRM field
- Schedule: Every Monday 6 AM → Zapier → Pull CRM report → Calculate MQL health metrics → Post summary to Slack channel via Zap
- Automation: When `mql_count` field = 3 and `opportunity_created` = false → Zapier → Update `zombie_lead` = true → Enroll in long-term nurture campaign

**Clay.com (for enrichment-powered scoring):**
- Build a Clay table that auto-enriches new MQLs with: technographic data (Clearbit/BuiltWith), LinkedIn headcount growth (for hiring surge signal), job change signals (People Data Labs), G2 review activity
- Connect Clay output → CRM via webhook → auto-update scoring fields within minutes of MQL creation
- Use Clay's built-in AI column to classify ICP tier (Tier 1/2/3) based on enriched firmographic data before lead reaches SDR queue

## Troubleshooting

**Problem: Sales continues to reject high-scored leads even after recalibration**
Solution: The issue is likely a trust deficit, not a model deficit. Do three things: (1) Run a "lead quality retrospective" with SDR leadership — pull the last 90 days of closed-won deals and show where they scored at the time of MQL; this demonstrates model accuracy with real revenue data and rebuilds trust. (2) Create a "Sales Feedback Loop" report: every week, publish SDR rejection reason data back to the marketing team; make lead quality a shared metric, not a marketing-owned metric. (3) Shadow a weekly SDR triage call — watch how leads are being evaluated in real time; you will discover nuanced rejection criteria that aren't in the scoring model and cannot be identified from data alone.

**Problem: MQL volume drops dramatically (>40%) after implementing signal caps and threshold increases**
Solution: This is expected in the short-term and reflects the model catching up to reality — the previous inflated volume was false signal. To manage the transition: (1) Communicate to sales leadership that you are intentionally trading MQL volume for MQL quality — present the projected MQL-to-Won improvement as the business case. (2) Identify which nurture programs are generating leads that score just below the new threshold and amplify high-intent content (pricing guides, ROI calculators, competitive comparisons) to organically move the right leads over the bar. (3) Add the new high-intent signals (pricing page repeat visit, ROI calculator, job change) as fast as possible — these will generate new, genuinely high-scoring MQLs to offset volume reduction.

**Problem: The AI agent drift detection fires false positives (alerts every week due to normal variance)**
Solution: The detection window is too tight. Adjust the drift detection rules to use a 21-day rolling average instead of 7-day, and increase the alert threshold from 10% decline to 15% decline before flagging. Also add a minimum volume floor: the drift alert should only fire if the comparison period includes at least 50 MQLs (smaller samples produce statistically meaningless variance). Finally, add a "trend confirmation" rule: the alert fires only if MQL-to-SAL rate has been below baseline for 3 consecutive weeks — single-week dips are almost always sampling noise, not structural model failure.

## Version History
- v1.0: Initial creation (auto-generated)
