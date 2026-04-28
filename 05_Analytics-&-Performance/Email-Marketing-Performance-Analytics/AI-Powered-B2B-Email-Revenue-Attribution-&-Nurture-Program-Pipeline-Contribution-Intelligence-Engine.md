# AI-Powered B2B Email Revenue Attribution & Nurture Program Pipeline Contribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** analytics, email-marketing, revenue-attribution, b2b, pipeline, nurture, marketing-ops

## Overview
This prompt builds a complete email revenue attribution and nurture program analytics system that proves email marketing's pipeline and revenue contribution to leadership — moving beyond open rates to dollars influenced, pipeline velocity by engagement cohort, and revenue-per-nurture-program analysis fully automatable with AI.

## Quick Copy-Paste Version

You are a B2B marketing analytics expert specializing in email revenue attribution. Analyze our email marketing program and produce a complete Revenue Attribution Report.

INPUT DATA (paste from your email platform + CRM):
- Email campaign list (last 90 days): campaign name, send date, recipients, opens, clicks
- Pipeline data: opportunity created date, stage, close date, amount, associated contact IDs
- Nurture sequence enrollment data: sequence name, contact ID, enrollment date, completion status

ANALYSIS TASKS:

1. PIPELINE INFLUENCE SCORING
   - Identify all email sends that touched contacts within 90 days before opportunity creation
   - Calculate email-influenced pipeline using multi-touch linear attribution across the email journey
   - Break down by campaign type: nurture sequences, newsletters, promotional, event invites

2. NURTURE PROGRAM VELOCITY ANALYSIS
   - Compare time-to-opportunity for contacts in active nurture sequences vs. cold contacts of same ICP
   - Calculate average pipeline velocity acceleration (days saved) per nurture program
   - Identify which nurture sequences produce highest-quality opportunities by ACV and win rate

3. REVENUE PER EMAIL COHORT
   - Segment all contacts by 90-day rolling engagement: Highly Engaged (>25% open rate), Engaged (10-25%), Low Engagement (<10%), Dormant (no open in 60+ days)
   - Calculate pipeline created and closed-won revenue for each cohort over last 12 months
   - Produce Revenue Per Active Contact (RPAC) metric for each cohort

4. EMAIL ATTRIBUTION WATERFALL
   - Total email-touched pipeline → email-influenced pipeline (click within window) → email-sourced pipeline (first meaningful touch preceded opp by 30+ days)
   - Show email contribution as percentage of total marketing-influenced pipeline

5. OPTIMIZATION RECOMMENDATIONS
   - Identify top 3 underperforming nurture programs by pipeline contribution vs. enrolled contacts
   - Flag dormant cohort: estimated monthly send cost with zero pipeline return
   - Recommend reallocation of email frequency and suppression actions based on RPAC data

OUTPUT FORMAT:
- Executive Summary (3 bullets: email-influenced pipeline $, pipeline velocity improvement %, email-sourced revenue $)
- Attribution Waterfall table
- Nurture Program Scorecard (program name, enrolled, MQL rate, opportunities created, influenced pipeline $, RPAC, win rate)
- Cohort Revenue Analysis table with recommended action per cohort
- Top 5 Recommendations with estimated revenue impact

## Advanced Customizable Version

ROLE: You are a VP of Marketing Analytics with deep expertise in B2B SaaS email attribution and marketing measurement. You have built email revenue attribution models for companies from $5M to $500M ARR and understand the nuances of multi-touch attribution across long B2B sales cycles with multiple buying committee members.

CONTEXT:
Company: [COMPANY_NAME]
Industry: [INDUSTRY]
Average Sales Cycle: [X] days
Average ACV: $[X]
Email Platform: [HubSpot / Marketo / Pardot / Klaviyo / Other]
CRM: [Salesforce / HubSpot CRM / Other]
Active Email Programs: [list nurture sequences, newsletters, promotional, event campaigns]
Report Audience: [CMO / VP Marketing / Marketing Ops / Board]
Reporting Period: [Last 90 days / Last 6 months / Last 12 months]

DATA INPUTS PROVIDED:
[Email platform export]:
- Campaign performance: sends, deliveries, opens, clicks, unsubscribes by campaign
- Contact-level engagement history for reporting period
- Sequence enrollment data with entry dates, exit dates, completion status, email-level engagement

[CRM export]:
- Opportunities created in reporting period with associated contact IDs
- Pipeline stage progression timestamps (created date, each stage entry date, close date)
- Closed-won and closed-lost outcomes with amounts and primary reason
- Contact activity timeline showing all marketing and sales touches

OBJECTIVE: Produce a board-ready email revenue attribution analysis that:
1. Quantifies email's pipeline and revenue contribution using a defensible multi-touch attribution model
2. Measures nurture program effectiveness by business outcomes, not vanity metrics
3. Identifies revenue optimization opportunities with specific dollar estimates
4. Creates a repeatable monthly measurement framework the team can run autonomously

ANALYTICAL FRAMEWORK:

STEP 1 — ATTRIBUTION MODEL SELECTION
Choose the right model based on sales cycle and ACV:
- ACV > $50K and sales cycle > 60 days: TIME-DECAY attribution with 30-day half-life (recent touches weighted higher)
- ACV $10K–$50K: POSITION-BASED attribution (40% first email click, 40% last email click before opportunity creation, 20% distributed across middle touches)
- ACV < $10K or velocity motion: LAST-CLICK attribution with 7-day lookback window

Attribution rules:
- Lookback window: match to average sales cycle length (minimum 30 days, maximum 180 days)
- Qualifying interaction: email CLICK (not open — eliminates Apple MPP inflation)
- Exclusions: current customers (unless analyzing expansion revenue), internal domains, contacts who unsubscribed prior to opportunity creation, bounced contacts
- Contact association requirement: opportunity must have at least one associated contact with email engagement in window

STEP 2 — PIPELINE INFLUENCE ANALYSIS
For each opportunity in the reporting period:
A) Pull all email interactions for all associated contacts within the attribution window
B) Apply selected attribution model to distribute pipeline credit across email campaigns
C) Tag each attributed campaign by funnel stage intent: AWARENESS (newsletter, thought leadership, industry trends), CONSIDERATION (product education, case studies, ROI content), DECISION (demo follow-up, competitive comparison, pricing, ROI calculator)
D) Calculate and report:
   - Total influenced pipeline by campaign type (awareness vs. consideration vs. decision)
   - Influenced pipeline by nurture program vs. one-off campaigns vs. newsletter
   - Average email touches per opportunity (pre-creation window)
   - Email touch frequency distribution: 1 touch, 2-3 touches, 4-7 touches, 8+ touches

STEP 3 — NURTURE PROGRAM ROI SCORECARD
For each active nurture sequence, calculate:

ENROLLMENT METRICS:
- Contacts enrolled in period
- Completion rate (reached final email)
- Unsubscribe rate (flag if >2%)
- Mid-sequence drop rate (opened first 3, then ghosted)

PIPELINE METRICS:
- MQL conversion rate from sequence (contacts who became MQL within 30 days of any sequence email)
- SQL conversion rate
- Opportunities created (associated contacts who created opp within attribution window of sequence enrollment)
- Average email in sequence at time of opportunity creation (indicates which email breaks through)

REVENUE METRICS:
- Influenced pipeline per enrolled contact (RPAC — influenced)
- Closed-won revenue per enrolled contact (RPAC — won)
- Average ACV of opportunities from sequence vs. non-nurtured ICP contacts
- Win rate comparison: nurtured vs. non-nurtured

VELOCITY METRICS:
- Average days from sequence enrollment to opportunity creation
- Average days from opportunity creation to closed-won
- Compare both metrics to control group: ICP-matched contacts NOT in any nurture sequence

INVESTMENT EFFICIENCY:
- Estimated cost per enrolled MQL (sequence build cost amortized + platform cost per send)
- Cost per influenced pipeline dollar
- Sequence ROI: closed-won revenue attributable / total sequence investment

STEP 4 — COHORT REVENUE ANALYSIS
Segment entire email list by 90-day rolling engagement score:

CHAMPIONS (>35% open rate + at least 1 click in 90 days):
- Pipeline created, closed-won revenue, RPAC, avg ACV, win rate
- Recommended action: Increase send frequency, personalize to buying stage, route to sales with engagement context

ENGAGED (15-35% open rate, any engagement in 90 days):
- Same metrics as above
- Recommended action: Maintain cadence, A/B test send time and subject lines, add personalization variables

PASSIVE (5-15% open rate, no clicks in 90 days):
- Same metrics
- Recommended action: Reduce send frequency by 50%, test reactivation campaign with high-value content offer

DORMANT (0-5% open rate, no engagement in 60+ days):
- Pipeline created (likely near zero), monthly send cost estimate, list percentage
- Recommended action: One final win-back campaign (subject: "Should we break up?"), then suppress if no response

NEVER OPENED (zero opens since subscription or 120+ days):
- Count, percentage of list, estimated monthly cost
- Recommended action: Immediate suppression — protecting sender reputation and reducing waste

STEP 5 — ATTRIBUTION WATERFALL (EXECUTIVE FORMAT)
Build this waterfall for the reporting period:

Total pipeline created: $[X]M (100%)
  ↓ Marketing-influenced pipeline: $[X]M ([X]%)
    ↓ Email-touched pipeline (any email open): $[X]M ([X]% of marketing-influenced)
      ↓ Email-influenced pipeline (click within attribution window): $[X]M ([X]%)
        ↓ Email-sourced pipeline (email was first meaningful touch, 30+ days pre-opp, no prior CRM activity): $[X]M ([X]%)

Closed-won revenue from email-sourced pipeline: $[X]M
Email program ROI: (closed-won revenue / estimated total email program cost) × 100 = [X]%

Industry benchmarks to include:
- B2B email-influenced pipeline: typically 25-45% of total marketing pipeline
- Email-sourced pipeline: typically 10-20% of marketing-attributed pipeline
- Average RPAC for engaged B2B email contacts: $800-$3,500 (varies by ACV)

STEP 6 — STRATEGIC RECOMMENDATIONS
For each of the top 5 findings, structure as:

FINDING: [Specific data observation with numbers]
REVENUE IMPACT: [Conservative estimate of dollar impact if addressed — use 20% improvement assumption]
ACTION: [Specific, executable change with owner and 30-day timeline]
MEASUREMENT: [Exactly how to track improvement in next 90 days]
RISK: [What could go wrong with this change and how to mitigate]

CONSTRAINTS:
- Present all revenue figures as ranges to account for attribution model uncertainty: "[X]M–[Y]M"
- Flag data quality issues that may skew attribution (missing contact associations, duplicate contacts, MPP open inflation)
- Explicitly distinguish email-influenced (correlation) from email-sourced (causation)
- Provide both optimistic (multi-touch influenced) and conservative (last-click sourced) figures in executive summary
- Note confidence level for each major finding: High (>80% data completeness), Medium (60-80%), Low (<60%)

OUTPUT STRUCTURE:
1. Executive Summary — 1 page, board-ready, three headline metrics with context
2. Email Attribution Dashboard — key metrics comparison table (this period vs. prior period)
3. Nurture Program Scorecard — all programs ranked by RPAC (influenced), sortable view
4. Cohort Revenue Analysis — five cohorts with metrics and recommended action
5. Attribution Waterfall — visual waterfall with industry benchmark callouts
6. 90-Day Optimization Roadmap — top 5 actions ranked by estimated revenue impact
7. Methodology Appendix — attribution model logic, exclusions, data quality notes, confidence levels

## Example Input/Output

**Input Example:**
- Company: Meridian Analytics — B2B SaaS marketing intelligence platform
- ACV: $45,000 | Sales cycle: 75 days | Email platform: HubSpot | CRM: Salesforce
- Reporting period: Q1 2026
- Active programs: Demo Follow-Up (6 emails, 14 days), Trial User Onboarding (8 emails, 21 days), Cold Lead Reactivation (5 emails, 30 days), FinTech Vertical Nurture (7 emails, 45 days), Weekly Newsletter
- List size: 24,000 contacts | Active pipeline in Q1: $10.2M

**Output Example:**

*Executive Summary:*
- Email-influenced pipeline in Q1: **$3.1M–$4.0M** (30–39% of total marketing pipeline, above industry benchmark of 25–45%)
- Email-sourced closed-won revenue: **$860K** (17% of marketing-attributed revenue — within benchmark range)
- Demo Follow-Up nurture program reduced time-to-opportunity by **19 days** vs. non-nurtured ICP contacts (75 vs. 94 days)

*Attribution Waterfall:*
| Stage | Pipeline | % of Total |
|---|---|---|
| Total pipeline created | $10.2M | 100% |
| Marketing-influenced | $6.8M | 67% |
| Email-touched (any open) | $4.0M | 39% |
| Email-influenced (click in window) | $3.1M | 30% |
| Email-sourced (first touch) | $1.4M | 14% |
| Email-attributed closed-won | $860K | 8% |

*Nurture Program Scorecard:*
| Program | Enrolled | MQL Rate | Opp Created | Infl. Pipeline | RPAC | Win Rate |
|---|---|---|---|---|---|---|
| Demo Follow-Up | 340 | 42% | 89 | $1.4M | $4,118 | 28% |
| Trial Onboarding | 520 | 31% | 78 | $1.1M | $2,115 | 24% |
| FinTech Vertical | 890 | 18% | 42 | $490K | $551 | 19% |
| Cold Reactivation | 1,200 | 6% | 12 | $264K | $220 | 15% |

*Top 3 Recommendations:*
1. **Pause Cold Reactivation Sequence after email 3** for contacts with zero engagement. Route to programmatic retargeting instead. Estimated savings: $1,800/month in platform costs; estimated pipeline uplift from retargeting investment: $280K over 90 days.
2. **Suppress 8,400 dormant contacts** (no open in 60+ days, zero pipeline in Q1). Estimated send cost savings: $2,100/month. Deliverability improvement projected to lift engaged cohort open rates by 8-12%.
3. **Replicate Demo Follow-Up sequence structure for Trial-to-Paid conversion path** — it outperforms next-best program by 3.6× on RPAC. Estimated incremental pipeline from expanded deployment: $620K over 90 days.

## Success Metrics
- Email-influenced pipeline calculated monthly with methodology documented and repeatable in <4 hours
- Attribution model captures >80% of opportunities with at least one associated contact email record
- RPAC tracked by cohort monthly with 3-month rolling trend visible
- Nurture program scorecard updated within 5 business days of month close
- Dormant suppression policy enforced automatically via email platform suppression lists
- Executive summary delivered in <2 pages with all revenue figures as ranges with confidence levels noted
- Data quality score >85% (opportunities with complete contact-to-email association in CRM)

## Related Prompts
- [Email Automation Sequence Architecture & Revenue Flow Intelligence Engine](./Email-Automation-Sequence-Architecture-&-Revenue-Flow-Intelligence-Engine.md)
- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](../Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [Marketing Funnel Conversion & Pipeline Velocity Intelligence Engine](../Funnel-Conversion-&-Pipeline-Velocity/Marketing-Funnel-Conversion-&-Pipeline-Velocity-Intelligence-Engine.md)
- [Lead Nurture Sequence & Pipeline Acceleration Email Engine](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Lead-Nurture-Sequence-&-Pipeline-Acceleration-Email-Engine.md)

## Integration Tips
- **HubSpot**: Use the Revenue Attribution beta report combined with the Campaign Influence report. Export contact engagement history via the HubSpot Reporting API. Map the nurture program scorecard directly to HubSpot's Campaign Performance view. Automate monthly report pulls using HubSpot's API + Zapier → Google Sheets → this prompt.
- **Salesforce + Pardot/Marketing Cloud**: Use Salesforce Campaign Influence with the Customizable Attribution model. Export Pardot Engagement History for cohort analysis. Build the waterfall in Salesforce Reports using custom summary formulas for each attribution stage.
- **Marketo**: Export Program Performance reports plus Salesforce opportunity influence data. Use Marketo's Revenue Cycle Analytics (RCA) for stage-level attribution mapping to the waterfall structure.
- **Google Sheets + Looker Studio**: Build the attribution waterfall and RPAC cohort tables in Sheets using the AI-generated pivot logic, then connect to Looker Studio for live executive dashboards with auto-refresh.
- **Zapier / Make**: Automate monthly data pull from email platform API → format as prompt input → run Claude analysis → post report summary to Slack channel → save full report to Notion or Confluence.
- **Gong / Chorus**: Cross-reference top RPAC email campaigns with call recordings to identify which email content correlates with buyer readiness language — use findings to improve email copy in decision-stage sequences.

## Troubleshooting

**Problem: CRM doesn't reliably associate contacts to opportunities, making attribution severely incomplete (less than 60% of opps have contact associations).**
Solution: Run a data quality audit before attribution — query opportunities where contact roles = 0 or primary contact = null. For Salesforce, enforce Contact Roles as a required field on opportunity validation rules going forward. For HubSpot, audit the "Associated Contacts" field on deals. Accept that current-period attribution will be conservative and note the confidence level explicitly in your executive summary. Implement a contact association SLA with sales ops: all opportunities must have at least one contact associated within 48 hours of creation.

**Problem: Apple Mail Privacy Protection (MPP) has inflated open rates to 60-80%, making open-based cohort segmentation unreliable.**
Solution: Switch all cohort segmentation and attribution qualifying events from opens to CLICKS only. Use HubSpot's MPP detection filter or Marketo's "opened via machine open" flag to exclude bot opens from your engagement scoring. Rebuild your cohort definitions around click activity and reply rates only. For the RPAC analysis, this will shrink your "Highly Engaged" cohort significantly but make it far more accurate — contacts who actually click are 4–6× more likely to become opportunities than open-only contacts.

**Problem: Leadership challenges the influenced pipeline number as too high — "email gets credit for deals that would have closed anyway."**
Solution: This is the correlation vs. causation challenge. Present both figures (multi-touch influenced and last-click sourced) and frame them explicitly: influenced = "email played a role," sourced = "email likely originated the relationship." To validate causation, add a holdout test: suppress 10% of your nurture-eligible ICP audience from email for 60 days and compare opportunity creation rates to the nurtured group. Industry benchmark: B2B email legitimately influences 25–45% of pipeline but sources 10–20%. If your numbers exceed the upper end, recheck your attribution window and exclusion rules — particularly whether you are excluding existing customers from the analysis.

## Version History
- v1.0: Initial creation (auto-generated)
