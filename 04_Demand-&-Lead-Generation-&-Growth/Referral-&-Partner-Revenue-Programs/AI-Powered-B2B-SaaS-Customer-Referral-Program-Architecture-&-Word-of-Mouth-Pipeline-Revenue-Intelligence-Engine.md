# AI-Powered B2B SaaS Customer Referral Program Architecture & Word-of-Mouth Pipeline Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** referral-marketing, word-of-mouth, customer-advocacy, b2b-saas, pipeline-generation, plg, nps, champion-activation, partner-revenue, viral-growth

## Overview
Designs and deploys a fully automated B2B SaaS customer referral program that converts high-NPS customers and power users into a systematic pipeline engine. Use it when you want to build a structured, measurable referral motion — not just ad hoc word-of-mouth — that operates with the same rigor as any paid demand generation channel, producing referral-sourced pipeline that closes 3-5x faster and churns 37% less than cold-acquired customers.

## Quick Copy-Paste Version

You are a B2B SaaS growth strategist specializing in customer referral programs. I need a referral program architecture for my company.

My company: [Company Name] — [1-sentence description, e.g., "Revenue intelligence platform for mid-market B2B SaaS sales teams"]
Product: [What it does and who the primary user is]
Current customer base: [e.g., "320 paying customers, ACV $24,000, mostly Series B SaaS companies"]
ICP referral targets: [Who your customers know that you want to meet, e.g., "VPs of Sales and Revenue Operations at 50-500 person SaaS companies"]
Current NPS: [e.g., "52, with 38% promoters"]
CRM: [HubSpot / Salesforce / Pipedrive]
Current referral approach: [None / Informal / Basic refer-a-friend link]

Build me:
1. A tiered referral program structure with clear incentive options for each tier (cash, credit, exclusive access)
2. The 5 highest-signal customer behaviors that predict referral willingness — and how to detect them automatically in my CRM or product analytics
3. A 3-email referral ask sequence for promoter customers, including the exact timing triggers and message angles
4. A lightweight automation workflow I can build in HubSpot or Salesforce to run this without manual effort
5. The 4 KPIs that prove this program is working within 90 days

Output as a ready-to-implement referral program brief.

## Advanced Customizable Version

ROLE:
You are a Senior Growth & Partnerships Strategist with 14+ years designing referral and customer advocacy programs at B2B SaaS companies from $5M to $200M ARR. You have built referral programs at companies like Gong, Lattice, and Rippling — and you understand that the difference between a referral program that generates 8% of pipeline and one that generates 28% is architectural rigor: identifying the right referrers, triggering the ask at the right moment, offering the right incentive, and creating a feedback loop that compounds over time. You think in customer lifetime stages, product usage milestones, referral economics, and CRM automation. You design programs that become evergreen pipeline engines — not one-time campaigns — and you measure them with the same attribution discipline as paid media.

CONTEXT:
Company: [Company Name]
Product description: [What it does, primary use case, measurable customer outcome]
Business model: [SaaS / Usage-based / Hybrid] | ACV: [e.g., "$28,000"] | ARR: [e.g., "$8.5M"]
Customer count: [e.g., "305 active customers"]
Current NPS score: [e.g., "48"] | Promoter % (score 9-10): [e.g., "34%"]
ICP customer profile: [Industry, company size, buyer title, e.g., "B2B SaaS companies, 50-500 employees, VP Revenue Operations or VP Sales"]
Who your customers refer to: [e.g., "Peers at similar-stage SaaS companies — former colleagues, LinkedIn connections, conference relationships"]
Current referral program status: [None / Informal word-of-mouth / Basic link / Structured program]
CRM: [HubSpot / Salesforce / Pipedrive]
Product analytics tool: [Amplitude / Mixpanel / Heap / Pendo / None]
Customer success tool: [Gainsight / ChurnZero / Totango / Intercom / None]
Top 10% power user behavior: [e.g., "Uses product daily, has 3+ team members using it, has logged ROI in our Success Portal"]
Current referral-sourced pipeline %: [e.g., "Estimated 6%, not formally tracked"]
Sales cycle length: [e.g., "45 days, 3-4 stakeholders"]
Primary referral incentive budget: [e.g., "$500-$1,500 per qualified referral, open to non-cash options"]

OBJECTIVE:
Design a complete, launch-ready B2B SaaS customer referral program across seven components:

COMPONENT 1 — REFERRAL-READY CUSTOMER IDENTIFICATION FRAMEWORK

Build the Referral Propensity Model to automatically score every customer account on their likelihood to refer:

A. TIER 1 — CHAMPION REFERRERS (highest propensity, warm the ask immediately)
For each signal, provide the data source, how to capture it in CRM, and the scoring weight:
- NPS Promoter signal: Customer submits NPS score of 9-10 → triggers within 48 hours of survey submission, highest referral window (NPS promoters who are asked within 72 hours refer at 3.1x the rate of those asked after 2 weeks)
- ROI Milestone signal: Customer achieves documented measurable outcome in your platform (e.g., "Closed first $100K deal with your tool's pipeline intelligence") → CS team logs outcome, triggers referral ask within 7 days
- Power User graduation signal: User surpasses product engagement threshold that correlates with high retention (define this threshold using your own cohort analysis — typically the top 20% engagement decile) → automated trigger from product analytics via webhook to CRM
- Expansion signal: Customer upgrades plan, adds seats, or expands to new team → purchasing behavior indicates satisfaction, ideal referral window before honeymoon period ends (typically 14-30 days post-expansion)
- Unsolicited praise signal: Customer proactively posts positive G2/Capterra review, mentions on LinkedIn, or sends praise via Slack → CS flags in CRM within 24 hours, referral ask appropriateness is highest in this state

B. TIER 2 — WARM REFERRERS (moderate propensity, nurture then ask)
- NPS Passive (score 7-8): Satisfied but not vocal — need a value-delivery moment before the ask
- Tenured customer (12+ months, low support tickets): Longevity signals comfort, but needs a reason to refer
- Multi-stakeholder account: 3+ users active = wider internal network, but ask needs to come from the highest-seniority active user

C. TIER 3 — NOT-YET-READY (do not ask — risks damaging the relationship)
- Recent support ticket (within 30 days of open/critical issue)
- NPS Detractor or score < 7
- Customers in renewal negotiation or at-risk status (per CS health score below 65)
- Account in active churn-risk workflow
- New customers (< 90 days) — excitement exists but credibility for referral hasn't formed yet

REFERRAL PROPENSITY SCORE FORMULA:
Calculate a 0-100 score per account using weighted signals:
- NPS Promoter (active, last 90 days): +35 points
- ROI Milestone documented: +25 points
- Product engagement decile (top 20%): +20 points
- Expansion in last 6 months: +15 points
- Unsolicited public praise (G2, LinkedIn): +10 points
- CS Health Score > 80: +10 points
- Tenure 12+ months: +5 points
DEDUCTIONS:
- Open critical support ticket: -40 points
- NPS score < 7: -50 points (exclude from program)
- In renewal negotiation: -30 points
- Customer success health < 65: -40 points

Trigger the referral ask workflow when score exceeds 60.

COMPONENT 2 — REFERRAL INCENTIVE ARCHITECTURE

Design a three-tier incentive structure that drives behavior without cheapening the relationship or attracting low-quality referrals:

TIER A — RECIPROCAL VALUE (preferred for enterprise accounts where cash gifts create procurement friction)
- Account credit: $[X] applied to next invoice per qualified referral that becomes a customer (recommended: 10-15% of first-year ACV of referred deal, capped at $2,000)
- Executive exclusivity: Referred customer + referrer both receive early access to your next major product release, private beta programs, or annual advisory council invitation
- Co-marketing opportunity: Feature the referrer in a case study, webinar as a guest speaker, or industry report — this works best for enterprise buyers who value thought leadership

TIER B — CASH INCENTIVE (preferred for SMB and self-serve customers where speed of gratification matters)
- Gift card or Visa prepaid: $[X] per qualified lead who takes a demo; $[Y] additional when they become a paying customer (recommended: $150 demo / $350 closed deal for ACV under $15K)
- Charitable donation: For senior executives or compliance-sensitive industries — donate $500 to referrer's charity of choice per closed deal
- Experience reward: High-end dinner, conference sponsorship attendance, or curated gift box for Tier 1 referrers

TIER C — RECOGNITION PROGRAM (zero-cost, highest ceiling for LTV and loyalty)
- Referral Hall of Fame: Annual recognition for top referrers in customer newsletter, LinkedIn post, and company website
- Advisory Board membership: Invite top 5-10 referrers per year to quarterly product advisory sessions — gives them influence, gives you insight
- Customer Council seat: Standing invitation to influence roadmap, test features, and co-develop use cases

INCENTIVE ECONOMICS MODEL:
- Calculate your referral program break-even: If closed referral deal ACV = $28,000, and referral CAC = $800 (incentive) + $2,100 (sales cost for faster close) vs. cold outbound CAC of $14,000 → referral CAC payback is under 1 month vs. 6 months for outbound
- Design incentive to scale with deal size: Smaller deals = cash/credit; larger deals = credit + exclusivity + recognition

COMPONENT 3 — REFERRAL ASK WORKFLOW AUTOMATION

Map the complete automation sequence from trigger to closed referral:

PHASE 1 — REFERRAL TRIGGER DETECTION (automated)
Step 1: CRM receives signal (NPS score logged, CS notes ROI milestone, product analytics sends engagement webhook)
Step 2: Referral Propensity Score recalculated automatically
Step 3: If score ≥ 60 AND no active open referral ask in last 90 days: enroll account in Referral Ask Sequence
Step 4: Assign referral sequence ownership to CS rep or Account Manager (not SDR — referrals require relationship equity)

PHASE 2 — REFERRAL ASK SEQUENCE (3 touches, 21 days)

EMAIL 1 — THE WARM MOMENT ASK (Day 1 of trigger)
Subject: "[First name], quick question while the win is fresh"
Angle: Celebrate their specific outcome first, then make the ask feel like sharing success, not selling
Key elements:
- Open with specific reference to their recent win ("You just hit [specific milestone] — that's a big deal")
- One sentence on why referrals from people like them matter ("The best people we work with almost always know other [job title]s who'd benefit from what you've built with us")
- Soft, low-friction ask: "Is there one person in your network who's wrestling with [specific problem]? Happy to make a brief introduction easy for you — we'll handle everything from there."
- CTA: Reply with a name, OR click the referral link to submit directly
- PS: Mention the incentive briefly and without pressure ("If they become a customer, we have a [credit/gift] for you — but no pressure, this is purely if it feels natural")

EMAIL 2 — THE MAKE-IT-EASY FOLLOW-UP (Day 8, only if no reply)
Subject: "Making it easy to share [Product Name]"
Angle: Remove friction — give them the exact words to use
Key elements:
- Provide a pre-written LinkedIn DM template they can forward to a colleague in 30 seconds
- Offer to do a 3-way introduction email ("Just reply with a name and I'll handle the whole intro")
- Re-anchor on what their referral gets: "[Product Name] is offering [referred contact's name] a personalized session with our team — no pitch, just value")
- Secondary CTA: Share a specific referral link they can drop in Slack, LinkedIn, or email

EMAIL 3 — THE FINAL TOUCH (Day 21, only if no reply to prior)
Subject: "Last one on this, [First name]"
Angle: Honest, brief, no pressure — preserve the relationship above all
Key elements:
- Acknowledge they may not have anyone in mind right now
- Offer an open-ended door: "If anyone ever comes to mind, here's your personal referral link — it never expires and [incentive description]"
- Pivot to value: Include a new resource or product update that's relevant to their role
- Exit the sequence gracefully — no follow-up after this touch

PHASE 3 — REFERRAL HANDOFF TO SALES
- Referral submitted via link or reply: Auto-create opportunity in CRM with source = "Referral" and referrer account linked
- Assign to AE (not SDR) — referrals deserve AE-level attention from first touch
- CS alerts referrer within 24 hours: "Thanks for the intro — I've reached out to [name] and we're connecting next week"
- Referrer update loop: Send 2 updates (intro scheduled; outcome closed/won) — this closes the feedback loop and increases future referral rates

COMPONENT 4 — REFERRAL PROGRAM LANDING PAGE & SELF-SERVE PORTAL

Design the always-on referral hub customers can access anytime:

PORTAL ELEMENTS:
- Personal referral link generator (unique tracked link per customer)
- Referral status tracker (shows "Referred → Demo Booked → In Evaluation → Closed")
- Incentive balance and reward history
- Pre-written referral copy: LinkedIn message, email intro, Slack message — each 3 sentences
- FAQ: "What counts as a qualified referral?" / "When do I get my reward?" / "What happens after I submit?"
- Leaderboard (optional for competitive markets): Top referrers by quarter

INTEGRATION: Embed in customer portal (Gainsight PX / Pendo / Intercom) or as a standalone page linked from in-product navigation and customer email footer

COMPONENT 5 — REFERRAL PROGRAM GTM AND LAUNCH SEQUENCE

30-DAY LAUNCH PLAN:

Week 1 — Build the Foundation
- Export Tier 1 referral-ready accounts (score ≥ 75) from CRM — typically 10-20% of total customer base
- Build referral ask email sequences in HubSpot or Outreach
- Set up referral tracking link system (use PartnerStack, Rewardful, or native HubSpot referral tracking)
- Create referral landing page / portal section
- Brief CS team: Script the conversation for verbal referral asks during QBRs and CSM check-ins

Week 2 — Soft Launch to Tier 1 Accounts
- Manually send referral ask to top 25 Tier 1 accounts (personalized, from CSM or AE — not automated)
- Test referral link tracking and CRM opportunity creation
- Collect first feedback on incentive offer resonance

Week 3 — Automate and Expand
- Activate automated trigger workflow in CRM for all new Tier 1 signal events
- Launch email sequence to next 50 Tier 1 accounts
- Add referral ask to QBR template for CS team

Week 4 — Measure and Iterate
- Review: referral asks sent, responses received, leads submitted, demos booked
- A/B test incentive framing (credit vs. cash) on next cohort
- Send thank-you note to all responders (referred or not)

COMPONENT 6 — REFERRAL PROGRAM MEASUREMENT FRAMEWORK

PRIMARY KPIs (report monthly to CRO and CMO):

1. Referral Participation Rate
Formula: Accounts that submitted ≥1 referral / Total eligible accounts (Propensity Score ≥ 60)
Benchmark: 8-15% participation in first 90 days; mature programs reach 20-30%
Action threshold: < 5% = incentive or ask timing problem; > 25% = scale investment

2. Referral-to-Demo Conversion Rate
Formula: Qualified referrals submitted → demo completed
Benchmark: 55-70% (vs. 15-25% for cold outbound)
Action threshold: < 40% = referral qualification criteria too loose or handoff process broken

3. Referral Pipeline Contribution %
Formula: Referral-sourced pipeline / Total pipeline
Benchmark target: 15-25% of total pipeline within 12 months
Stretch goal: 30%+ at companies with strong community and network effects

4. Referral CAC vs. Channel CAC
Formula: Total referral program spend (incentives + operations) / Total referral-sourced customers acquired
Compare to: Average CAC across other channels
Insight: Referral CAC is typically 70-85% lower than paid CAC; track this to justify program investment

5. Referral Win Rate and Sales Cycle
Formula: Referral opportunities won / Referral opportunities created | Avg days from referral to close
Benchmark: Referral win rates are 2-3x paid channel win rates; cycle is 30-50% shorter
Report to: CEO, CRO — this is your strongest argument for program investment

SECONDARY METRICS:
- Time from trigger to ask sent (target: < 48 hours)
- Referral feedback loop completion rate (% where referrer received closed-won/lost update)
- Repeat referrer rate (% of referrers who submit 2+ referrals) — this is your superfan metric
- NPS correlation: Do high NPS accounts refer more? (validates propensity model)

COMPONENT 7 — ADVANCED REFERRAL PROGRAM EXPANSIONS

Once the core program is running (90+ days, > 10 referrals closed):

A. PARTNER REFERRAL LAYER
Extend the program to include strategic technology partners, integration partners, and ecosystem players:
- Identify 10-20 complementary non-competing tools your customers use (from your integration ecosystem or CRM data)
- Offer partner referral agreements: Mutual referral tracking, revenue share or reciprocal introductions
- Build a co-sell motion: Partner's CS team introduces your product during their own QBRs; you reciprocate

B. INVESTOR PORTFOLIO REFERRAL ACTIVATION
If you have notable VCs or PE investors:
- Work with your investor relations contact to create a "portfolio intro" program
- Offer your investors a referral brief: One page on ideal customer, what to say, why it's valuable for their portfolio companies
- Investors who make introductions often have higher conversion rates than customer referrals due to existing trust

C. ALUMNI CHAMPION TRACKING
When a champion customer leaves their company:
- Automatically detect job change via LinkedIn Sales Navigator or tools like Warmly.ai or Clay
- Trigger a "Welcome to [New Company]" sequence within 30 days of job change
- Former champions at new companies convert at 4-7x higher rate than cold outbound — this is a referral flywheel

D. COMMUNITY-EMBEDDED REFERRAL
If you run a customer community (Slack, Circle, Discord):
- Embed referral prompts into community milestones (first post, first answer given, community anniversary)
- Create a "Refer a colleague" channel with social proof from successful referrers
- Feature referral success stories in community newsletter

## Example Input/Output

**INPUT:**
Company: Flowline — AI-powered revenue forecasting platform for B2B SaaS companies
ACV: $32,000 | ARR: $11.2M | Customer count: 350
NPS: 54 | Promoter %: 41%
ICP: VP Revenue Operations and CFOs at 100-600 employee SaaS companies
CRM: Salesforce | Product analytics: Amplitude | CS tool: Gainsight
Current referral-sourced pipeline: ~4%, informal, untracked
Sales cycle: 38 days average

**OUTPUT EXCERPT:**

**Flowline Referral Program: Launch Architecture**

**Tier 1 Referral-Ready Accounts (immediate ask): 63 accounts**
Trigger criteria: NPS 9-10 AND Gainsight health > 80 AND Amplitude engagement top 20% decile

**Top 5 Referral-Ready Accounts to personally reach out to this week:**
1. Meridian SaaS (VP RevOps: Sarah Chen) — NPS 10 submitted 3 days ago, achieved 94% forecast accuracy milestone last month, expanded from 12 to 18 seats in August → Propensity Score: 94
2. Cascade Systems (CFO: David Park) — Posted G2 review 5-star last week, 22 months tenure, 0 support tickets in 90 days → Propensity Score: 89
3. [etc.]

**Referral Incentive Structure for Flowline:**
- Option A (recommended for Enterprise accounts ≥ $40K ACV): $1,500 account credit per closed referral + Advisory Council invitation
- Option B (SMB accounts < $20K ACV): $200 Visa gift card per qualified demo + $400 additional on close
- ROI at target: At $32K ACV, referral CAC = $600 average vs. $13,200 outbound CAC → 22x efficiency ratio

**Email 1 — Referral Ask for Sarah Chen:**
Subject: "Sarah, quick ask while you're at 94% forecast accuracy"
"Hi Sarah — 94% forecast accuracy across Q3 is exceptional, and I know how long it took to get your data sources stitched together properly. The reason I'm reaching out: the best VPs of RevOps we work with almost always know a counterpart at a similar-stage company who's still doing forecast calls in spreadsheets. Is there one person who comes to mind? I'm happy to reach out directly — you just make one intro and we'll handle everything from there. No obligation, but if they become a customer, we'd love to give you $1,500 in Flowline credits as a thank you. Either way, huge congrats on Q3."

**90-Day KPI targets:**
- Referral participation rate: 12% of 63 eligible accounts → 8 referrers
- Referrals submitted: 18 (average 2.2 per referrer in healthy programs)
- Demos completed: 11 (60% referral-to-demo rate)
- Pipeline generated: $352,000 (11 opportunities at $32K ACV)
- Estimated closed-won: 6 deals / $192,000 ARR (55% referral win rate)
- Program cost: ~$3,600 (incentives) + $4,200 (ops time)
- Referral CAC: $1,300 vs. $13,200 blended CAC

## Success Metrics

**Program Health (weekly pulse):**
- Trigger-to-ask latency < 48 hours for 90% of Tier 1 events
- No referral asks sent to accounts with Gainsight health < 65

**Pipeline Quality (monthly):**
- Referral pipeline as % of total > 15% by month 4
- Referral win rate 2x+ blended win rate
- Referral sales cycle < 70% of blended sales cycle

**Program ROI (quarterly):**
- Referral CAC < 20% of blended CAC
- Referral customer 12-month retention > 90% (vs. company average baseline)
- Repeat referrer rate > 20% (signals superfan cohort is growing)

**Champion Relationship Health:**
- Referrer thank-you sent within 24 hours of lead submission: 100%
- Referrer outcome update (won/lost notification) sent: 100%
- Net new referrers added to Tier 1 pool monthly: > 5 (program is sustainable)

## Related Prompts

- [Customer Advocacy Program Analytics & Referral Revenue Attribution](../../05_Analytics-&-Performance/Customer-Advocacy-&-Referral-Analytics/AI-Powered-B2B-SaaS-Customer-Advocacy-Program-Analytics-&-Referral-Revenue-Attribution-Intelligence-Engine.md)
- [Community-Led Growth & Pipeline Revenue Intelligence](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-B2B-Community-Led-Growth-&-Pipeline-Revenue-Intelligence-Engine.md)
- [Channel Partner Marketing & Partner-Sourced Pipeline](../../02_Product-Marketing/Go-To-Market-Strategy/AI-Powered-Channel-Partner-Marketing-&-Partner-Sourced-Pipeline-Intelligence-Engine.md)
- [Influencer & Creator-Led Demand Generation](../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/AI-Powered-B2B-Influencer-&-Creator-Led-Demand-Generation-Intelligence-Engine.md)

## Integration Tips

**Salesforce:**
- Create a custom object: "Referral Program Enrollment" linked to Account record
- Add custom fields: Referral_Propensity_Score__c, Last_Referral_Ask_Date__c, Total_Referrals_Submitted__c, Referral_Incentive_Balance__c
- Build a Flow that auto-enrolls accounts when propensity score crosses 60 and no ask has been sent in 90 days
- Use Salesforce Process Builder to link referred Opportunities to the referrer Account with Source = "Customer Referral"

**HubSpot:**
- Use HubSpot Workflows to trigger referral ask enrollment based on NPS response property + health score custom property
- Create a "Referral Program" pipeline in HubSpot Deals to track referral opportunities separately
- Use HubSpot's native referral link tracking or integrate with PartnerStack via Zapier for link-level attribution

**PartnerStack / Rewardful / Impact.com:**
- For link-based tracking, use PartnerStack (B2B-native) or Rewardful (SaaS-focused) to generate unique referral links per customer
- Integrate with Stripe or your billing system to auto-trigger incentive payouts on deal close
- PartnerStack reports sync to Salesforce via native integration

**Gainsight / ChurnZero:**
- Add a "Referral Ask Sent" Timeline Event in Gainsight so CSMs can see when automated asks went out
- Create a Gainsight CTA: "Referral Propensity Score ≥ 75 — Initiate referral conversation in next QBR"
- Block referral ask CTAs from firing if customer health score < 65

**Amplitude / Mixpanel:**
- Build a behavioral cohort: Users in top 20% engagement decile in last 30 days
- Export cohort to CRM via webhook when user crosses threshold → triggers propensity score update
- Track referral link click and submission events in Amplitude to close the loop on which in-product moments correlate with referral willingness

**Zapier Automation:**
- Zap 1: NPS Promoter submitted (Delighted/Typeform) → Update Salesforce propensity score → Enroll in HubSpot referral sequence
- Zap 2: Referral submitted (PartnerStack) → Create Salesforce Opportunity → Alert AE via Slack → Send referrer thank-you email
- Zap 3: Referral deal closed-won (Salesforce) → Trigger PartnerStack incentive → Notify CSM → Send referrer update email

## Troubleshooting

**Problem: Referral participation rate is < 5% despite high NPS**
Diagnosis: Ask timing is wrong (asking too early or too late after the signal), incentive is mismatched to customer type, or the ask itself creates friction
Fix: Audit the time between NPS submission and email send — it should be < 48 hours. Survey a sample of non-participating promoters: "We noticed you gave us a 10 — would you ever consider referring a colleague? What would make that easy?" The answers will tell you exactly what's blocking participation.

**Problem: Referral leads aren't converting to demos (< 40% referral-to-demo rate)**
Diagnosis: Referral quality is low (referrers are sending unqualified contacts), or the first touch from sales is too cold and not leveraging the referral relationship
Fix: Tighten the referral submission form to capture more qualifying information (company size, job title, their specific pain). Require AEs to open every referral outreach with a direct reference to the shared relationship: "Sarah Chen suggested we connect — she thought you might be dealing with the same forecast accuracy problem they had before Flowline."

**Problem: Getting referrals from the same 3-4 customers repeatedly; program isn't expanding**
Diagnosis: The Tier 1 trigger criteria is too narrow, the program isn't visible to a broad enough customer base, or the non-superfan ask sequence isn't working
Fix: Expand the trigger criteria to include Tier 2 accounts (NPS 7-8 + tenure 12 months). Add a passive always-on referral CTA to every customer-facing touchpoint: email footer, in-product navigation, customer newsletter, and monthly CS check-in call script. Run a quarterly "Referral Month" with a time-limited bonus incentive (doubles the reward for 30 days) to reactivate the Tier 2 pool.

## Version History
- v1.0: Initial creation (auto-generated)
