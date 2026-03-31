# AI-Powered Pre-Event Attendee Intelligence & Account Prioritization Engine

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** b2b, events, analytics, abm, pipeline-generation

## Overview
Transforms raw event registration data into a prioritized account engagement plan by scoring attendees against your ICP, surfacing buying signals, and auto-generating personalized pre-event outreach sequences — so your team arrives at every tradeshow knowing exactly who to pursue and why.

## Quick Copy-Paste Version

You are a B2B revenue intelligence engine specializing in tradeshow and conference account prioritization.

I have an upcoming event: [EVENT NAME] on [DATE] in [CITY].

I'm sharing the following data:
- Registered attendee list (name, title, company, LinkedIn): [PASTE OR DESCRIBE]
- My ICP: [e.g., "VP/Director of Marketing or Revenue Ops at B2B SaaS companies, 200-2000 employees, using Salesforce, HubSpot budget $500K+"]
- My product: [BRIEF DESCRIPTION]
- Current pipeline: [# of open opportunities and which accounts are in pipeline]
- Past customers: [LIST TOP 5-10 CUSTOMER COMPANY NAMES]

Perform the following analysis:

1. TIER 1 ACCOUNTS (Must-Meet): Score and rank top 20 accounts that match ICP perfectly, show buying intent signals, or are in active pipeline. Include: company name, key attendees, why they're Tier 1, recommended talk track.

2. TIER 2 ACCOUNTS (High-Value): Next 30 accounts — strong ICP fit but earlier stage. Include recommended touchpoint (booth visit, dinner invite, LinkedIn connect).

3. COMPETITOR ATTENDEES: Flag any attendees from competitor companies and suggest intel-gathering tactics.

4. MEETING TARGETS: For each Tier 1 account, draft a 3-sentence personalized LinkedIn message or email requesting a 15-minute meeting at the event. Reference something specific about their company.

5. BOOTH BRIEFING CARD: For each Tier 1 attendee, create a 50-word briefing card for your sales reps covering: their role, likely pain points, conversation starter, and one thing to avoid.

Output as a structured table first (account tier, company, key contact, meeting priority score 1-10), then individual briefing cards.

## Advanced Customizable Version

ROLE: You are a senior B2B revenue intelligence analyst with expertise in account-based marketing, event sales orchestration, and pre-event pipeline strategy for high-growth SaaS companies.

CONTEXT:
- Event: [EVENT NAME AND TYPE — tradeshow/conference/summit]
- Date: [DATE RANGE]
- Our sponsorship tier: [Platinum/Gold/Silver/Booth/Attending only]
- Team attending: [e.g., "2 AEs, 1 CSM, 1 SDR, CMO"]
- Total meeting capacity: [e.g., "20 scheduled 1:1 meetings, 100 booth conversations"]
- Pipeline goal: [e.g., "$500K new pipeline, 5 qualified opportunities"]

INPUT DATA — provide as many as available:
1. Registered attendee export: [PASTE CSV OR DESCRIPTION]
2. Our CRM data: [accounts in pipeline, past customers, previous event interactions]
3. Intent data signals: [G2, Bombora, 6sense, or describe what you know about in-market accounts]
4. ICP definition:
   - Company: [industry, size, tech stack, funding stage, geography]
   - Persona: [title, seniority, department]
   - Trigger events: [funding rounds, leadership changes, competitor churn signals]

OBJECTIVE: Produce a complete pre-event account intelligence package:

## SECTION 1: ACCOUNT PRIORITY MATRIX
Create a scored table with columns:
| Company | Key Attendee(s) | Title | Account Tier (1/2/3) | ICP Score (1-10) | Intent Score (1-10) | Pipeline Status | Priority Score | Recommended Action |

Scoring rubric:
- ICP Score: 10 = perfect match on all ICP dimensions
- Intent Score: 10 = active buying signals (demo requested, competitor review activity, job posting for your category, recent funding)
- Priority Score = (ICP Score × 0.4) + (Intent Score × 0.4) + (Relationship Score × 0.2)

## SECTION 2: TIER 1 ACCOUNT DEEP-DIVES (top 15-20 accounts)
For each account:
**[COMPANY NAME]** | Priority Score: X/10
- Key attendee: [Name, Title]
- Why they're Tier 1: [2-3 specific signals]
- Known pain points: [based on their role, company stage, tech stack]
- Conversation opener: [specific, non-generic 1-2 sentence opener]
- Relevant customer story: [suggest which customer case study to reference]
- Meeting ask: [what outcome to pursue — demo, intro call, exec alignment]
- Risk/avoid: [what NOT to say or do — e.g., they're Salesforce customers, don't pitch integration limits]

## SECTION 3: PERSONALIZED OUTREACH SEQUENCES
For each Tier 1 account, generate:

**Pre-event LinkedIn message (sent 5-7 days before):**
[Personalized 3-4 sentence message referencing their company, recent news or content, specific event session, non-pushy CTA]

**Day-before text/email (if contact info available):**
[2-sentence confirmation + logistical ease — booth location, calendar link]

**Post-meeting follow-up (sent within 2 hours of meeting):**
[Personalized recap, specific next step, relevant asset attached]

## SECTION 4: TEAM DEPLOYMENT PLAN
Given [TEAM COMPOSITION], recommend:
- Which rep owns which Tier 1 accounts (match rep expertise to account profile)
- Scheduled meeting slots (morning vs. afternoon energy optimization)
- Booth staffing rotation to ensure coverage for Tier 2 walk-ins
- Exec meeting targets for CMO/VP attendance
- Daily debrief structure (what intel to capture in CRM each evening)

## SECTION 5: COMPETITIVE INTELLIGENCE PLAN
- Flag all attendees from [COMPETITOR NAMES] companies
- Suggest 3 competitive intelligence questions to ask mutual customers/prospects
- Identify sessions where competitor leadership is speaking — assign team member to attend and capture messaging
- Post-event: template for competitive intel report to share with sales team

## SECTION 6: SUCCESS METRICS DASHBOARD
Define event success metrics:
- Pre-event: # Tier 1 meetings booked, % of attendee list scored, outreach response rate
- During event: meetings held vs. planned, Tier 2 booth conversations, competitive intel items captured
- Post-event (30 days): pipeline created, opportunities opened, MQLs generated, meeting-to-opportunity conversion rate

CONSTRAINTS:
- All outreach must be genuinely personalized — no "I noticed you're attending [EVENT]" generic openers
- Every recommendation must tie to a revenue outcome
- Assume the sales team has 30 minutes per meeting maximum
- Account for time zones if international event
- Flag any accounts where we have existing relationships that should be leveraged for warm intros

OUTPUT FORMAT: Executive summary (1 page), then full account matrix, then individual account cards, then team deployment calendar.

## Example Input/Output

**Input Example:**
Event: SaaStr Annual 2026, San Jose, CA — September 8-10
Sponsorship: Gold (booth + 2 speaking slots)
Team: 3 AEs (Mid-Market, Enterprise x2), 1 VP Sales, CMO
Meeting capacity: 25 scheduled, ~150 booth conversations
Pipeline goal: $1.2M new pipeline

ICP: VP/Director Revenue Operations or Sales Operations at B2B SaaS, 100-1000 employees,
     Series B+, using Salesforce + HubSpot, currently scaling SDR team

Attendee data: 12,000 registered; exported top 200 matching VP+ at SaaS companies
Intent signals: 6sense showing 47 accounts in "Active" buying stage for "Revenue Operations Software"
CRM: 8 Tier 1 accounts currently in Stage 3 pipeline attending

**Output Example (Tier 1 Account Card):**
ACCOUNT INTELLIGENCE CARD — PRIORITY SCORE: 9.2/10
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Company: Luminara Health (Series C, 450 employees, San Francisco)
Key Attendees:
  • Sarah Chen — VP Revenue Operations (primary target)
  • Marcus Webb — Director of Sales (secondary)

Why Tier 1:
  ✓ 6sense: "Active Buying" stage for RevOps software, 89% intent score
  ✓ Posted "Senior RevOps Analyst" job 3 weeks ago (scaling signal)
  ✓ Currently in Stage 3 pipeline — 47-day deal velocity stall

Pain Points (inferred):
  → Rapid team scaling with Salesforce data hygiene issues (common post-Series C)
  → Manual reporting costing ~15 hrs/week based on team size
  → Sales forecasting accuracy likely <65% at current growth rate

Conversation Opener:
"Sarah, I saw Luminara just crossed $40M ARR — congrats. We've been helping 
a few other Series C health-tech companies fix the Salesforce-to-forecast gap 
that usually shows up right around your stage. Worth 15 minutes?"

Don't Do: Don't mention HubSpot migration — they went all-in on Salesforce Q1.
Reference Customer: MedBridge (similar profile, 11-month payback, 3x pipeline visibility)

Assigned Rep: Jennifer Nakamura (Mid-Market AE, managed MedBridge deal)
Meeting Slot: Tuesday 11:30am (book via calendar link in pre-event message)

Pre-Event LinkedIn Message (send Sept 3):
"Sarah — I've been following Luminara's growth since the Series C announcement. 
The RevOps scaling challenges that come with jumping from 80 to 150 reps are 
genuinely hard to predict. We published a framework specifically for health-tech 
SaaS at your stage — happy to share it, and if you're at SaaStr next week, would 
love to grab 15 min. We're at Booth G-42. No pitch, just the framework and a 
conversation. —[Name]"

## Success Metrics

**Pre-event (measure 7 days before event):**
- Tier 1 meeting book rate: target >60% of outreach getting responses
- Calendar slots filled: >80% of meeting capacity pre-scheduled
- Outreach personalization score: zero generic templates in outreach

**During event (measure nightly):**
- Meetings held vs. booked: >85% show rate
- Average meeting quality score (1-5 rep self-rating): >3.8
- CRM update completion: 100% same-day logging

**Post-event (measure 30 days out):**
- Meeting-to-opportunity conversion: target >40% Tier 1, >15% Tier 2
- Pipeline created per dollar of event spend: target >3x
- Time-to-next-step: avg <48 hours for Tier 1 accounts
- Event ROI: total pipeline / (sponsorship + team travel cost)

## Related Prompts
- [B2B Conference Event Demand Generation Engine](../../04_Demand-&-Lead-Generation-&-Growth/Event-Marketing/B2B-Conference-Event-Demand-Generation-Engine.md)
- [Post-Event Lead Conversion & Pipeline Attribution Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Event-Marketing/Post-Event-Lead-Conversion-&-Pipeline-Attribution-Intelligence-Engine.md)
- [ABM Buying Committee Engagement & Multi-Stakeholder Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Buying-Committee-Engagement-&-Multi-Stakeholder-Intelligence-Engine.md)
- [B2B Event Marketing ROI & Pipeline Attribution Intelligence Engine](B2B-Event-Marketing-ROI-&-Pipeline-Attribution-Intelligence-Engine.md)

## Integration Tips

**CRM (Salesforce / HubSpot):**
- Export your "attending [event]" contact list from CRM, paste directly into prompt
- After running the prompt, create an Event Campaign in Salesforce with Tier codes as campaign member statuses (Tier1-Invited, Tier1-Meeting-Booked, Tier1-Met)
- Map Priority Score field to CRM account record for post-event attribution

**Intent Data (6sense / Bombora / G2):**
- Pull "Active" and "Decision" stage accounts from your intent platform before running prompt
- Include keyword category ("Revenue Operations Software," "Marketing Automation") and intent score in your input data
- Use 6sense segments to auto-populate Tier 1 list before manual review

**Outreach Automation (Outreach / Salesloft / Apollo):**
- Import the personalized pre-event sequences directly into your SEP as one-off tasks
- Set up trigger: meeting held at event → auto-enroll in post-event sequence within 2 hours
- Use event-specific sequence tags for post-event attribution reporting

**Calendar & Logistics (Calendly / Chili Piper):**
- Create event-specific booking page with 30-minute slots blocked only during event hours
- Include in all pre-event outreach — remove friction from meeting scheduling
- Connect to HubSpot or Salesforce to auto-create meeting activities on contact records

**Competitive Intelligence (Crayon / Klue):**
- Log all competitor intel captured in your CI tool during/after event
- Use prompt output's competitive section to update battlecards post-event
- Share debrief summary in Slack #competitive-intel channel within 48 hours

## Troubleshooting

**Problem:** Attendee list doesn't include full registration data (just names/companies, no titles).
**Solution:** Run the company names through LinkedIn Sales Navigator or Apollo to enrich titles before inputting. Even 5 minutes of enrichment dramatically improves Tier scoring accuracy.

**Problem:** Priority scores feel off — too many Tier 1 accounts, not enough differentiation.
**Solution:** Tighten your ICP definition in the prompt. Add one more constraint (e.g., "must have raised funding in last 18 months" or "must be using Salesforce"). Also add hard exclusion rules: "exclude current customers" and "exclude companies under 50 employees."

**Problem:** Pre-event outreach getting low response rates (<15%).
**Solution:** The most common cause is generic openers. Re-run the outreach section with this instruction added: "Each message must reference a specific piece of content this person published, a specific company announcement from the last 30 days, or a specific session they're speaking/attending at the event. No 'I noticed you're attending' openers." Personalization specificity directly correlates with response rate.

## Version History
- v1.0: Initial creation (auto-generated)
