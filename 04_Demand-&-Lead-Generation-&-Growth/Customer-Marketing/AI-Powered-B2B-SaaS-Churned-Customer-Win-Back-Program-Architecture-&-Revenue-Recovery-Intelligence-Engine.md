# AI-Powered B2B SaaS Churned Customer Win-Back Program Architecture & Revenue Recovery Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** win-back, churn-recovery, customer-marketing, revenue-recovery, lifecycle-marketing, b2b-saas, retention, expansion-revenue, ai-automation, pipeline-generation

## Overview
Designs an end-to-end AI-powered program to systematically identify, prioritize, and win back churned B2B SaaS customers — segmenting by churn reason, recency, and historical value, then orchestrating multi-channel re-engagement campaigns that recover revenue at a fraction of new-customer CAC. Use when you have a growing base of churned accounts and want to convert a predictable percentage back into paying customers using AI-orchestrated, signal-driven outreach rather than ad-hoc win-back blasts.

## Quick Copy-Paste Version

You are a B2B SaaS customer marketing strategist. Design a churned customer win-back program for the following company:

**Company Context:**
- Product: [e.g., "Revenue intelligence platform for mid-market sales teams"]
- ICP: [e.g., "VP Sales / CRO at 100-1,000 employee B2B companies"]
- ACV: [e.g., "$28,000"]
- Average churn reasons (from exit surveys): [e.g., "32% price/budget, 28% switched to competitor, 22% product gaps, 18% org change/champion left"]
- Churned accounts in database: [e.g., "340 accounts churned in last 24 months"]
- New product features/improvements since churn: [e.g., "AI forecasting module, Salesforce bi-directional sync, 40% faster report generation"]
- Competitive context: [e.g., "Primary competitor Chorus.ai raised prices 35% in Q1"]

Build a complete win-back program including:

1. **CHURNED ACCOUNT SEGMENTATION** — Score and tier all churned accounts (Tier 1: High-priority; Tier 2: Medium-priority; Tier 3: Long-tail) based on: historical ACV, time since churn (recency), churn reason win-back addressability, and expansion potential. Provide a scoring matrix.

2. **TRIGGER EVENT MONITORING** — List 8-12 specific trigger events that create win-back opportunities (e.g., "champion returns to a new company," "competitor announces price increase," "new product feature directly addresses their stated churn reason") and how to track them with AI agents.

3. **WIN-BACK CAMPAIGN PLAYBOOKS BY TIER**
   - Tier 1 (5-15% of churned accounts): Concierge re-engagement with CS + AE + executive involvement. Provide a 90-day touchpoint sequence.
   - Tier 2 (20-35%): Automated multi-touch sequence with human escalation triggers. Provide a 60-day sequence (8-10 touchpoints across email, LinkedIn, phone).
   - Tier 3 (50-70%): Evergreen nurture with offer-trigger automation. Provide a 6-month drip with 3 offer triggers.

4. **OFFER AND INCENTIVE ARCHITECTURE** — Design win-back offers by churn reason: migration support package (for competitor switchers), pricing restructure options (for budget churns), roadmap briefings (for product-gap churns), champion re-engagement (for org-change churns). Include guardrails to prevent margin erosion.

5. **WIN-BACK MEASUREMENT DASHBOARD** — Define success metrics: win-back rate by tier, revenue recovered, win-back CAC vs. new-logo CAC, average deal size at win-back vs. original, and time-to-close comparison.

Output as a complete win-back program brief with enough specificity for a customer marketing manager to execute immediately.

## Advanced Customizable Version

ROLE: You are a senior B2B SaaS customer marketing architect with 15+ years of experience building systematic win-back programs at companies from $10M to $300M ARR. You've run win-back programs that consistently recover 8-15% of churned revenue annually, and you know that most companies leave this revenue on the table because they treat win-back as a one-time email blast rather than a systematic, AI-orchestrated program. You understand the psychology of churned customers — the combination of sunk cost awareness, competitive frustration, and "I should have stayed" regret — and how to activate those emotions ethically through intelligent, well-timed outreach. You design programs that marketing executes autonomously with minimal sales involvement until accounts are sales-ready.

CONTEXT:
Company: [Company Name]
Product category: [e.g., "Marketing automation for B2B SaaS"]
ICP definition: [e.g., "Director of Marketing and above at Series A-C B2B SaaS, $5M-$50M ARR"]
Average ACV at time of churn: [e.g., "$22,000"]
Average customer lifetime at churn: [e.g., "14 months"]
Total churned accounts (last 24 months): [e.g., "280 accounts"]
Churned ARR pool: [e.g., "$4.2M in churned ARR potentially recoverable"]
Exit survey data available: [Yes/No — if Yes, include churn reason breakdown]
Primary churn reasons: [e.g., "Price sensitivity: 35%, Product gaps (missing X feature): 25%, Switched to competitor Y: 22%, Champion left/org change: 18%"]
Notable product improvements since churns: [e.g., "Native AI content generation, Zapier integration, new reporting module, 2x speed improvements"]
Competitive landscape shifts: [e.g., "Competitor Y raised prices 28%, acquired smaller player, had 3 outages this quarter"]
CRM system: [e.g., "Salesforce + HubSpot"]
CS platform: [e.g., "Gainsight / ChurnZero / Totango / manual"]
Available channels: [e.g., "Email, LinkedIn Sales Navigator, outbound phone (AEs), direct mail"]
Win-back offer budget: [e.g., "$500 per Tier 1 account, $150 per Tier 2"]

OBJECTIVE: Design a 12-month AI-powered churned customer win-back program that systematically recovers 8-12% of churned ARR through segmented, trigger-activated, multi-channel re-engagement — executed primarily by marketing automation with surgical human involvement at key conversion points.

DELIVERABLE STRUCTURE:

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 1: CHURNED ACCOUNT INTELLIGENCE & SEGMENTATION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Win-Back Potential Score (WBPS) Model:**
Score each churned account 0-100 across five dimensions:

*Dimension 1: Historical Value (0-25 points)*
- ACV at churn × customer lifetime months × expansion potential
- 25 pts: Top quartile ACV + 12+ month tenure + 2+ expansion signals
- 15 pts: Mid ACV + 6-12 months
- 5 pts: Low ACV + under 6 months

*Dimension 2: Recency (0-20 points)*
- 20 pts: Churned 0-3 months ago (pain is fresh, memory of value is strong)
- 15 pts: 3-6 months (still evaluating alternatives)
- 8 pts: 6-12 months (may have settled into competitor)
- 3 pts: 12-24 months (significant re-education needed)
- 0 pts: 24+ months (rebuild from scratch — treat as new logo)

*Dimension 3: Churn Reason Addressability (0-25 points)*
- 25 pts: Product gap now SOLVED by new feature — clear proof point available
- 20 pts: Competitor switcher — competitor has had notable issues/price increase
- 15 pts: Champion left — former champion now at a new company (expansion opportunity)
- 10 pts: Budget cut — company raised new funding or is in growth mode again
- 3 pts: Fundamental strategic misfit — wrong ICP, won't scale

*Dimension 4: Relationship Quality (0-15 points)*
- 15 pts: Multiple internal champions, executive sponsor, high NPS before churn
- 10 pts: Single champion, decent relationship
- 5 pts: Contentious churn, multiple escalations on record
- 0 pts: Fraudulent payment, legal dispute history

*Dimension 5: Competitive Intelligence (0-15 points)*
- 15 pts: Known to be unhappy with current vendor (G2 review posted, LinkedIn complaint, Gong mention of competitor frustration)
- 10 pts: Competitor has publicly stumbled (outage, acquisition, price increase)
- 5 pts: No intelligence available
- 0 pts: Strong public praise of competitor

**Tier Assignment:**
- Tier 1 (WBPS 70-100): White-glove program — concierge re-engagement
- Tier 2 (WBPS 40-69): Automated-first with human escalation triggers
- Tier 3 (WBPS 15-39): Evergreen nurture — low-touch, offer-triggered
- Tier 4 (WBPS 0-14): Archive — remove from active win-back, move to brand nurture

**AI Enrichment Protocol:**
Before any outreach, run each Tier 1 and Tier 2 account through an AI enrichment pipeline:
- LinkedIn: Current champion employment status (still at same company? Promoted? Left for new company?)
- Intent data (6sense / Bombora / G2 Buyer Intent): Is account showing research signals for your category again?
- News monitoring: Funding rounds, leadership changes, M&A activity
- Technographic: Have they changed their tech stack? Any signals of vendor dissatisfaction?
- G2/Capterra: Have they posted reviews of current vendor? What do they say?
Output: An "Account Intelligence Brief" per Tier 1/2 account that is the foundation for personalized outreach.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 2: TRIGGER EVENT MONITORING & REAL-TIME ACTIVATION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**12 Win-Back Trigger Events (AI-Monitored):**

*Champion-Based Triggers (highest urgency):*
- T1: Former champion starts at a new company that matches ICP (LinkedIn job change alert → enroll new company in prospecting AND reach out to old company with new contact)
- T2: Former champion is promoted at same company (increased budget authority → re-engage with expansion pitch)
- T3: New decision-maker joins churned account that wasn't involved in original churn decision (fresh start opportunity)

*Competitive Triggers:*
- T4: Primary competitor announces price increase > 10% (immediate price comparison campaign activation)
- T5: Competitor suffers service outage or security incident (monitor Twitter/LinkedIn/Reddit → activate within 24 hours)
- T6: Competitor announces acquisition (consolidation anxiety → "your tools are safe with us" message)
- T7: Churned account posts negative review of current vendor on G2/Capterra

*Product-Based Triggers:*
- T8: New feature release directly addresses account's stated churn reason (requires tagging churn reasons in CRM to match against product releases)
- T9: Integration partnership announced with a tool the churned account is known to use
- T10: Company benchmark/ROI data published that mirrors churned account's original use case

*Company-Based Triggers:*
- T11: Churned account raises a funding round (new budget, new growth targets → re-evaluate vendor spend)
- T12: Churned account announces new leadership (CRO, CMO, VP Sales hire = platform evaluation moment)

**Monitoring Infrastructure:**
- LinkedIn Sales Navigator: Save all churned company pages and former champion contacts — alerts for job changes, company news
- Google Alerts: Set for "[Competitor name] price" / "[Competitor name] outage" / "[Churned company name] funding"
- G2 Buyer Intent: Activate for category monitoring — flag when churned accounts show review research behavior
- Gong/Chorus keyword alerts: Tag any mentions of churned company names in active sales calls (referrals? CS mentions?)
- Salesforce automation: Trigger win-back workflows when enrichment data updates (funding round, new executive detected)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 3: TIER 1 WIN-BACK PLAYBOOK (CONCIERGE PROGRAM)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Target:** Top 5-15% of churned accounts by WBPS
**Resources:** Dedicated AE + CSM partner + VP/C-level exec sponsorship
**Timeline:** 90-day intensive program

**90-Day Touchpoint Sequence:**

*Week 1 — Intelligence Assembly:*
- Account Intelligence Brief completed (AI-assisted)
- Internal debrief: AE + original CSM review account history, identify win-back angle
- Identify correct current contact (champion may have changed)
- Personalized outreach drafted by AE (not templated)

*Week 2 — Executive-Led Reconnection:*
- Day 8: VP/C-level sends personal video message (Loom, 90 seconds) — acknowledge the gap, reference specific improvements, invite to "an honest conversation"
- Day 10: AE sends personalized email referencing specific pain points from original churn conversation + product proof point
- Day 11: LinkedIn connection request from relevant exec if not already connected

*Week 3-4 — Value Re-Demonstration:*
- Day 15: If no response to Week 2, AE sends "Before you decide to stay with [current vendor] long-term, we've built [X] that solves [exact reason they left]. 15 minutes to show you?" email
- Day 17: AE phone call attempt (leave voicemail with specific product update hook)
- Day 21: Customer Success sends "Here's what's changed since you left" asset — a personalized one-pager (AI-generated from account history + new features) showing specifically what's different

*Week 5-6 — Proof + Offer Introduction:*
- Day 28: If engaged, AE schedules a "product catch-up call" — NOT a sales demo, a peer conversation about what's changed
- Day 30: Send 1-2 mini case studies from companies that left and came back + their outcomes
- Day 35: Win-back offer formally introduced: migration credit, first-year discount, extended trial of premium tier, white-glove onboarding package

*Week 7-10 — Evaluation Support:*
- Expedited security review / procurement documentation if needed
- ROI calculator pre-populated with their historical data to show value at current pricing
- Reference call with a current customer from their industry
- Executive sponsor available for key stakeholder calls

*Week 11-12 — Close or Archive:*
- If opportunity created: AE-led close process with CS hand-off plan
- If no engagement: Tier 1 → Tier 2 evergreen (remove from intensive, add to automated stream)
- Win-back outcome logged in Salesforce for program learning

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 4: TIER 2 WIN-BACK PLAYBOOK (AUTOMATED-FIRST)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Target:** 20-35% of churned accounts
**Execution:** Marketing automation + AE escalation at signal triggers
**Timeline:** 60-day sequence, then evergreen if no conversion

**60-Day Multi-Touch Sequence:**

*Day 1 (Email 1 — Acknowledge + Intrigue):*
Subject: "Since you left, we built [X]" (personalized by churn reason tag)
- Price churns: "We heard the pricing wasn't working. Here's what's changed."
- Product churns: "[Feature they wanted] is now live. Wanted to be the first to let you know."
- Competitor churns: "You made the switch to [Competitor]. Understood — here's why some teams are coming back."
- Champion churns: "We know [Former Champion] moved on. Wanted to reconnect with the new team."
No CTA to book a demo — CTA is "See what changed" (gated or ungated product update page)

*Day 4 (LinkedIn — Connection + Soft Touch):*
AE sends LinkedIn connection request with note: "Hey [Name], [AE Name] from [Company]. Saw we hadn't connected — wanted to stay in touch. No pitch, just staying on your radar."

*Day 8 (Email 2 — Social Proof):*
"3 companies who left [Company] and came back — here's what they said" — lead with peer companies in their industry/size range who returned + specific ROI outcomes

*Day 14 (Email 3 — Direct Win-Back Offer):*
First mention of specific win-back incentive — framed as "we want to earn your business back, not just discount our way back in." Include: migration support, onboarding guarantee, flexible payment terms.

*Day 21 (Phone — AE Reach):*
AE attempts one phone call. Voicemail script: "Hey [Name], [AE] from [Company]. I know we lost you [X] months ago and I'm not going to pretend that didn't happen. We've made some big changes specifically around [churn reason] and I wanted to give you 10 minutes to decide if it's worth a second look. Call me at [number] or just reply to my email. Either way, I appreciate the time."

*Day 28 (Email 4 — Trigger-Specific):*
If trigger event detected (competitor price change, funding round, new exec), send trigger-specific email. If no trigger, send product milestone update with video demo of most relevant new feature.

*Day 35 (LinkedIn DM):*
Short, direct message: "[Name] — sent a couple emails but know inboxes are brutal. Is there a better way to share what's new with [Company] quickly? Happy to send a 2-min Loom."

*Day 42 (Email 5 — Executive Sponsor):*
CMO/VP Customer Success sends brief personal email: "I wanted to personally reach out — I know the experience with [Company] wasn't perfect when you left. Here's what I've changed and what I'd like to offer to make it right."

*Day 50 (Email 6 — Last Touch + Evergreen Opt-In):*
"This will be our last outreach for a while" — clear, honest, no guilt. Offer: "If timing changes or you hit the pain points again, here's a direct line." Include opt-in for monthly product newsletter (low-commit re-engagement channel). Move non-responders to Tier 3 evergreen.

*AE Escalation Triggers (automated to notify AE):*
- Email opened 3+ times without clicking → AE reaches out personally
- "See what changed" page visited → AE follow-up within 24 hours
- Pricing page visited → immediate AE notification
- LinkedIn DM replied → AE takes over from automation

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 5: TIER 3 EVERGREEN NURTURE (ALWAYS-ON)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Target:** 50-70% of churned accounts (lowest WBPS or Tier 1/2 non-responders)
**Execution:** Fully automated, 6-month low-touch program
**Volume:** Monthly product newsletter + 3 campaign moments

*Monthly: "What's New at [Company]" Newsletter*
- Unbranded/low-key design — looks like a product update, not a sales email
- 3 product updates, 1 customer success story, 1 industry insight
- Soft CTA: "See all updates" or "Try [new feature] free for 30 days"
- Auto-remove anyone who hasn't opened in 3 consecutive months (email hygiene)

*Offer Trigger 1 (Month 2): "Come Back" Campaign*
Condition: Auto-activate when competitor pricing change detected, OR 90 days after churn anniversary
Message: Time-limited win-back offer (30-day trial extension, first month free, migration credit)
Auto-expire offer at 30 days — creates urgency without permanent discount erosion

*Offer Trigger 2 (Month 4): "Feature You Asked For" Campaign*
Condition: Auto-activate when product release matches account's tagged churn reason
Message: Personalized one-liner: "[First Name], you left partly because of [X]. We built it. Seriously. Here's a quick demo." — link to 3-minute feature demo video (ungated)
CTA: "Book a 15-min catch-up" — soft ask, not "Request a Demo"

*Offer Trigger 3 (Month 6): "Re-Evaluate Us" Campaign*
Condition: Auto-activate if account's CRM record updated with new funding/leadership OR if Bombora shows category intent spike
Message: "A lot has changed in [X] months. Has your situation changed too? If you're evaluating options again, we'd love to be on the shortlist." 
CTA: Offer a 14-day pilot (limited functionality, no migration required) — lowest friction entry point

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 6: OFFER ARCHITECTURE & PRICING GUARDRAILS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Win-Back Offer Design by Churn Reason:**

*Price/Budget Churns (35% of churned accounts):*
- Core offer: Restructured contract — monthly billing option (reduce barrier), 20-25% win-back discount year 1 (vs. negotiating down new-logo price), or add-ons bundled into base
- Migration support: Free data migration, 60-day implementation support at no cost
- Risk: Don't train all price-sensitive accounts to churn and return for discounts — add 12-month minimum commitment to win-back contracts

*Product Gap Churns (25%):*
- Core offer: Early access / beta program for any remaining roadmap gaps + free feature training sessions
- Proof point: "Here's exactly what [Feature X] can do for your use case" — personalized demo using their historical data (if retained in your system)
- Pricing: No discount needed if product gap is genuinely solved — offer extended onboarding support instead

*Competitor Switchers (22%):*
- Core offer: "Competitive migration package" — free migration from Competitor X, 90-day parallel run period (they can test both), connector/API support
- Timing: Activate within 72 hours of trigger event (competitor outage, price increase, review posted)
- Pricing: Match or beat on value, not necessarily on sticker price — emphasize TCO (total cost of ownership including implementation, training, and churn risk of switching again)

*Champion/Org Change Churns (18%):*
- Core offer: Fresh-start executive briefing — "You weren't here when we worked with [Company] before. Let me show you what we can do for you specifically."
- Approach: Reset the relationship entirely — don't reference the previous churn too heavily
- Fast-track: Skip standard demo → offer a paid pilot (1/3 of normal ACV) with success guarantee
- Pricing: Full pricing, possibly with pilot structure — don't discount for an account where the relationship issue has already been resolved by personnel change

**Offer Approval Framework:**
- Tier 1 offers: VP Revenue approval required for any discount > 30% or concessions > $5K value
- Tier 2 offers: AE + CS Manager approval; pre-approved playbook options only
- Tier 3 offers: Fully automated, no approval required (pre-set offer parameters)
- Never: Discount below cost-to-serve; waive minimum commitments for accounts with payment history issues; offer free perpetual licenses

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 7: MEASUREMENT & REVENUE ATTRIBUTION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Primary Win-Back KPIs:**

*Volume Metrics:*
- Total churned accounts in active program: [Count]
- Accounts by tier: T1 / T2 / T3 split
- Engagement rate by tier: Opens, clicks, meeting books per tier
- Trigger events activated per month

*Conversion Metrics:*
- Win-back rate by tier: T1 target 15-25%; T2 target 6-12%; T3 target 2-4%
- Win-back rate by churn reason: Identify which reasons are most recoverable
- Average time-to-win-back: Days from first outreach to closed-won
- Win-back deal size vs. original: Expansion or contraction at win-back?

*Revenue Metrics:*
- ARR recovered (monthly and quarterly): Direct revenue impact
- Win-back CAC vs. new-logo CAC: Win-back should cost 30-60% less
- Win-back LTV vs. new-logo LTV: Track 12-month post-win-back retention
- Net Revenue Recovery Rate: ARR recovered ÷ Total addressable churned ARR

*Program Health Metrics:*
- Unsubscribe rate from win-back emails (target < 1.5% — if higher, messaging is too aggressive)
- Blacklist additions (accounts who opt out permanently — honor immediately)
- Sales team satisfaction with MQL quality from win-back program (survey quarterly)

**Attribution Model:**
- Primary: First program touch to win-back opportunity creation (sourced)
- Secondary: Last touch before close (influenced)
- Track in Salesforce: Create "Win-Back Program" Campaign, log all touches as Campaign Members, set Campaign Influence = true
- Report: Monthly "Win-Back Revenue Dashboard" in Salesforce showing ARR recovered, open pipeline from win-back, and program ROI

**Program ROI Calculation:**
Win-Back Program ROI = (ARR Recovered × Gross Margin %) ÷ (Program Cost: team time + offer cost + tooling)
Target: 5-8x ROI (every $1 spent on win-back generates $5-8 in margin)

## Example Input/Output

**Input Example:**
Company: Clarifio — B2B SaaS workflow automation platform for RevOps teams
ACV: $32,000
ICP: Director of RevOps / VP Sales Ops at 200-2,000 employee B2B companies
Total churned accounts (last 24 months): 187 accounts, $5.1M churned ARR
Churn reasons: 38% price/budget, 30% switched to Zapier, 22% missing CRM integrations, 10% champion left
New product improvements: Native Salesforce bi-directional sync (Q1), AI workflow builder, 50+ new integrations
Competitive context: Zapier raised pricing 40% in Q2

**Output Example (Module 3, Tier 1 Outreach Email 1):**

*Subject: Clarifio update for [Company Name] — week 1 since Zapier's price increase*

Hi [First Name],

I know you moved to Zapier about [X] months ago — at the time, the pricing made sense.

I also know Zapier just increased their prices by 40%. I wanted to reach out personally, not with a sales pitch, but because I think the math has changed.

Since you left, we shipped two things specifically for teams like yours: native Salesforce bi-directional sync (the thing our sales team told me you were waiting for) and an AI workflow builder that cuts setup time by 60%.

I'm not going to pretend our old product was perfect. But I'd like 15 minutes to show you what's changed — and if you give us a fair look, I'll personally make sure the migration is painless.

Would Thursday or Friday work?

— [AE Name]

P.S. If now isn't the right time, I completely understand. We have a standing migration offer: switch back within 90 days of Zapier's price increase and we'll cover your implementation costs, no strings.

## Success Metrics

- **Win-back rate by tier:** Tier 1: 15-25%; Tier 2: 6-12%; Tier 3: 2-4% (industry benchmark for B2B SaaS)
- **Revenue recovered:** 8-12% of addressable churned ARR per year
- **Win-back CAC:** 30-60% lower than new-logo CAC (existing knowledge of product, no education required)
- **Time-to-win-back:** Tier 1 average 45-60 days; Tier 2 average 60-90 days (vs. 180-270 day new-logo sales cycle)
- **Win-back retention:** Won-back customers who stay 90+ days show 20-30% higher 12-month retention vs. first-time customers (they know what they had and why they want it)
- **Program ROI:** 5-8x (every $1 in win-back program costs generates $5-8 in recovered gross margin)
- **Unsubscribe rate:** < 1.5% (measures whether outreach feels relevant, not harassing)

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Renewal-Marketing-Program-Architecture-&-At-Risk-Account-Churn-Prevention-Revenue-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/AI-Powered-B2B-SaaS-Closed-Lost-Recovery-&-Long-Cycle-Pipeline-Reactivation-Email-Architecture-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Customer-Marketing-Expansion-Revenue-Campaign-Architecture-&-Cross-Sell-Upsell-Pipeline-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Churn-Prevention-&-Retention-Analytics/AI-Powered-B2B-SaaS-Predictive-Churn-Intelligence-&-Marketing-Led-Retention-Revenue-Recovery-Analytics-Engine.md`

## Integration Tips

**Salesforce:**
- Create a "Win-Back Program" record type on Campaign — use Salesforce Campaign Hierarchies to organize T1/T2/T3 sub-campaigns under one parent "Win-Back FY[Year]" campaign
- Build a Salesforce report: "Closed-Won Opportunities where Account.Win_Back_Tier__c = T1/T2/T3" to measure program revenue contribution monthly
- Add custom field `Win_Back_Eligible__c` (checkbox) and `Win_Back_Tier__c` (picklist) to Account object — populate via Flow when churn date is logged
- Set up a Process Builder / Flow: when Opportunity is Closed-Won AND Account.Win_Back_Eligible = true → log in "Win-Back Revenue Recovered" custom field

**HubSpot:**
- Create "Churned Customers" Static List — manually populated or synced from Salesforce via integration
- Build Win-Back Enrollment Workflows triggered by: (1) List membership, (2) Trigger event property update (e.g., `competitor_price_increase_detected = true`), (3) Date-based (churn anniversary)
- Use HubSpot Sequences (Sales Hub) for Tier 1 — allows AEs to run personalized sequences with manual steps (calls, LinkedIn) alongside automated email steps
- Create Smart Lists segmenting by churn reason property — enables trigger-specific email sends without manual list management

**LinkedIn Sales Navigator:**
- Save all Tier 1 and Tier 2 churned accounts as "Account Lists" in Navigator — get automated alerts for new hires, leadership changes, growth signals
- Save former champions as "Lead Lists" — job change alerts trigger T1 trigger event (Champion T1: former champion at new ICP company)
- Use Navigator's "TeamLink" feature to identify mutual connections with churned accounts for warm introduction opportunities

**Gainsight / ChurnZero:**
- Tag all churned accounts in CS platform with win-back tier and churn reason at time of offboarding
- Set automated CS Health Score alerts: if a formerly churned customer's health score drops below 60 in first 90 days post-win-back → trigger immediate CSM intervention to prevent second churn
- Build a Gainsight "Win-Back Playbook" for post-win-back onboarding (different from standard — acknowledges they know the product, focus on what's NEW)

**Zapier / Make (Integromat):**
- G2 Review Monitor: Zapier webhook watches for new G2 reviews from known churned account domains → auto-create task in Salesforce for AE to review + potentially trigger T1/T2 outreach
- Funding Round Alert: Crunchbase API → Zapier → update HubSpot property `recent_funding_round = true` → enroll in Trigger 3 workflow
- LinkedIn Job Change Alert: Use Phantombuster or People Data Labs API to monitor former champion LinkedIn profiles → Zapier → HubSpot property update → T1 trigger activation

## Troubleshooting

**Problem: Win-back email open rates are high (20%+) but meeting books are near zero — no one is converting despite engaging with content.**
Solution: The gap between interest and action usually means one of two things: (1) The offer isn't compelling enough relative to their switching costs — people know what it takes to migrate back and need a stronger incentive. Test a "zero-migration" offer: you do all the technical migration work at no cost, they just say yes. Or (2) The timing is wrong — they're interested but locked into a contract with their current vendor. Add a "Remind me in 90 days" CTA that auto-snoozes their enrollment and re-activates at 90 days. Track "interested but not ready" separately from "not interested" — the former should get a dedicated contract-expiry follow-up campaign.

**Problem: Sales team is skeptical of the win-back program — they say "these accounts already rejected us once, why would they come back?" and aren't following up on win-back leads.**
Solution: Pull data to show the ROI gap: calculate what a win-back close costs in AE time vs. a new-logo close. Win-backs should require 40-60% fewer touchpoints because product education is already done. Build a "Win-Back Closed-Won" Salesforce report and share it in the weekly sales meeting — concrete revenue evidence changes behavior faster than philosophy. Also, brief the AE team on the specific win-back angles: churned customers who return do so for reasons — price, product updates, competitor frustration — and the AE's job isn't to "sell them again" but to present a specific resolution to the specific reason they left. That's a fundamentally different (and easier) conversation than a cold pitch.

**Problem: Our churn data in CRM is a mess — we don't have clean "churn reason" tags, churn dates are inconsistent, and we can't segment the program properly.**
Solution: Before launching the full program, run a "Win-Back Data Cleanup Sprint" — dedicate one week to: (1) Identify all accounts where Opportunity Stage = "Closed-Lost" or "Churned" in the last 24 months, (2) Reach out to original AEs/CSMs for the top 50 accounts to capture churn reasons verbatim (90 minutes total if you do it via Slack poll), (3) Use AI to categorize verbatim churn reasons into your 4-5 standard categories, (4) Populate the `Win_Back_Tier__c` and `Churn_Reason__c` fields retroactively. This cleanup is a one-time cost that unlocks a systematic, scalable program — without it you're guessing on personalization and your best win-back angles are invisible.

## Version History
- v1.0: Initial creation (auto-generated)
