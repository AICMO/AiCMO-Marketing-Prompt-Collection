# AI-Powered B2B SaaS SMS & Mobile Marketing Automation Architecture & High-Intent Buyer Conversion Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-25 min | **Tags:** sms-marketing, mobile-marketing, demand-generation, trial-activation, lead-conversion, lifecycle-automation, b2b-saas, pipeline-velocity, conversational-marketing, revenue-acceleration

## Overview
This prompt architects a complete B2B SaaS SMS and mobile marketing automation system — spanning trial activation sequences, webinar/event confirmation flows, high-intent lead speed-to-lead response, renewal and expansion campaigns, and re-engagement sequences. Use it when you need to add the highest open-rate channel (98% SMS open rate vs. 20% email) to your lifecycle marketing stack or when your free-trial activation rates, webinar show rates, or renewal conversion rates are underperforming and you need a faster-acting engagement layer.

## Quick Copy-Paste Version

You are a senior B2B SaaS lifecycle marketing strategist. Design a complete SMS and mobile marketing automation architecture for my company.

My company context:
- Product: [SaaS product description]
- ICP: [Job title, company size, industry]
- Trial length: [X days] | Trial-to-paid conversion rate: [X]%
- Average ACV: $[X] | Average sales cycle: [X days]
- Current tech stack: [CRM, marketing automation, SMS platform if any]
- Monthly trial signups: [X] | Monthly webinar attendees: [X]
- Key conversion bottlenecks: [e.g., low show rates, slow trial activation, churning at renewal]

Design the following SMS automation programs:

1. TRIAL ACTIVATION SEQUENCE (Day 0–14): A 6-message SMS sequence that drives new trial users from signup to first meaningful product action within 72 hours, with branching logic based on activation status.

2. WEBINAR & EVENT CONFIRMATION FLOW: A 4-message sequence (confirmation, 48hr reminder, day-of reminder, post-event follow-up) that lifts show rates by 20–35%.

3. SPEED-TO-LEAD RESPONSE (Inbound High-Intent): A 3-message SMS sequence triggered within 5 minutes of a high-intent form fill (demo request, pricing page visit + contact), designed to book a call before the prospect contacts a competitor.

4. RENEWAL & EXPANSION SMS CAMPAIGN: A 5-message sequence starting 60 days before renewal with persona-specific value reinforcement, social proof, and escalation to CSM.

5. RE-ENGAGEMENT SEQUENCE: A 4-message sequence targeting dormant trial users (no login in 7+ days) and cold leads (no engagement in 90+ days).

For each sequence deliver: exact message copy, send timing/triggers, character count, opt-out compliance language placement, personalization variables, and A/B test variants for the highest-impact message in the sequence.

## Advanced Customizable Version

**ROLE:**
You are a VP of Growth and Lifecycle Marketing with 12+ years building multi-channel automated marketing systems for B2B SaaS companies from $5M to $300M ARR. You are an expert in SMS marketing compliance (TCPA, GDPR, CASL), platform architecture (Attentive, Klaviyo, HubSpot SMS, Salesmsg, Twilio, SimpleTexting), and the psychology of mobile-first communication. You understand that SMS is the highest-trust channel in a marketer's stack — misuse destroys deliverability and brand trust, while precise, value-first SMS sequences drive 6–8x higher response rates than equivalent email campaigns. You build SMS programs that are legally compliant, psychologically calibrated to the B2B buyer's context, and deeply integrated with CRM and marketing automation workflows for full pipeline attribution. Every message you write has a specific conversion objective, is under 160 characters where possible, and uses plain language — not corporate speak.

**OBJECTIVE:**
Architect a complete SMS and mobile marketing automation system for [Company Name] that drives measurable pipeline acceleration across the full buyer lifecycle: from first-touch trial activation through renewal and expansion.

**CONTEXT INPUT:**

Provide the following to build a precision SMS architecture:

COMPANY & PRODUCT CONTEXT:
- Company: [Name] | Stage: [Seed / Series A / B / C / PE-backed / Public]
- Product category: [e.g., B2B project management, revenue intelligence, HR tech, fintech compliance]
- Primary ICP: [Job title(s), company size range, industries]
- Average ACV: $[X] | Average sales cycle: [X] days | Average trial length: [X] days
- Current trial-to-paid conversion rate: [X]% | Target: [X]%
- Monthly new trial signups: [X] | Monthly inbound demo requests: [X]
- Monthly webinar registrants: [X] | Current show rate: [X]%
- Renewal rate: [X]% | Target: [X]%

CURRENT SMS & MOBILE STATUS:
- Current SMS platform: [None / Attentive / Salesmsg / HubSpot SMS / Klaviyo / Twilio / SimpleTexting / Other]
- SMS opt-in collection method: [Trial signup form / Demo request form / Event registration / None currently]
- Existing consent language: [Paste current opt-in language or "None"]
- Current SMS database size: [X contacts opted in] | Compliance jurisdiction: [US/EU/CA/Global]
- CRM: [Salesforce / HubSpot / Pipedrive / Other] | MAP: [Marketo / HubSpot / Pardot / Klaviyo / Other]

LIFECYCLE CONVERSION BOTTLENECKS:
Identify your top 3 drop-off points by funnel stage:
- Trial signup → First meaningful product action: [X]% complete within 72hrs — Target: [X]%
- Webinar registration → Actual attendance: [X]% show rate — Target: [X]%
- Inbound demo request → Booked meeting: [X]% same-day booking rate — Target: [X]%
- Active trial → Conversion to paid: [X]% by day 14 — Target: [X]%
- Renewal notice → Renewal confirmed: [X]% by 30 days out — Target: [X]%
- Dormant trial → Reactivation: [X]% reactivated within 30 days — Target: [X]%

ICP BEHAVIORAL CONTEXT:
- Primary job titles receiving SMS: [e.g., VP Sales, Head of Marketing, CFO]
- Peak working hours for ICP in primary timezone: [e.g., 8am–6pm ET weekdays]
- ICP mobile usage pattern: [Heavy smartphone users / Desktop-first / Mixed]
- Sensitivity level: [Low — startup operators comfortable with direct outreach / High — enterprise buyers expect formality]
- Competitors known to use SMS: [List any known, or "Unknown"]

PERSONALIZATION DATA AVAILABLE:
Check all that apply:
- [ ] First name
- [ ] Company name
- [ ] Trial signup date / trial days remaining
- [ ] Last login date
- [ ] Feature adoption milestones completed (Yes/No per feature)
- [ ] Webinar registration details (topic, speaker, date)
- [ ] Account executive name assigned
- [ ] Renewal date / days until renewal
- [ ] Usage tier / seats
- [ ] Industry vertical
- [ ] Geographic region / timezone

**OUTPUT ARCHITECTURE:**

Deliver a complete SMS Marketing Automation System with all of the following sections:

---

### SECTION 1: COMPLIANCE & OPT-IN ARCHITECTURE

**1.1 Consent Collection Framework**
For each touchpoint where SMS opt-in should be collected:
- Form/touchpoint location
- Exact opt-in checkbox language (TCPA-compliant for US, CASL-compliant for Canada, GDPR-compliant for EU)
- Double opt-in trigger (if required by jurisdiction)
- SMS welcome message triggered immediately upon opt-in confirmation
- Opt-out keyword handling (STOP, UNSUBSCRIBE, CANCEL — platform configuration)
- Record-keeping requirements for consent documentation

**1.2 Suppression & Frequency Governance**
- Maximum SMS touchpoints per contact per 7-day rolling window
- Hard suppression rules (never SMS these segments: [list])
- Quiet hours enforcement (no sends before 8am or after 9pm local time)
- Global opt-out honor process across SMS + email

---

### SECTION 2: TRIAL ACTIVATION SMS SEQUENCE (Days 0–14)

**Objective:** Drive new trial users to first meaningful product action ("activation event") within 72 hours, which correlates with 3–5x higher trial-to-paid conversion rates.

For each of the 6 messages, deliver:
- **Trigger:** What action or timer fires this message
- **Segment:** Who receives it (based on activation status)
- **Timing:** Day and hour (relative to signup)
- **Message A (Primary):** Full SMS copy with personalization variables, character count
- **Message B (A/B Variant):** Alternative copy approach for split testing
- **Goal:** Specific action this message drives
- **Success Metric:** What % click/response rate validates this message

MESSAGE SEQUENCE FRAMEWORK:
- Message 1: Welcome + single CTA to activation (Day 0, within 10 minutes of signup)
- Message 2: First value milestone prompt — sent only to non-activated users (Day 1, 10am local)
- Message 3: Social proof + activation shortcut — sent to users not yet activated (Day 3)
- Message 4: Live help offer — sent to users showing login but no activation (Day 5)
- Message 5: Trial expiry urgency — sent to all non-converted (Day 12, 3 days before trial ends)
- Message 6: Final conversion offer — discount or extension offer (Day 14, trial end day)

**Branching Logic Map:**
Provide a decision tree showing:
- Activated user path (suppress remaining sequence, enroll in expansion SMS)
- Partially activated path (continue with modified messaging)
- No activation path (escalate to SDR + continue SMS)
- Converted to paid path (immediately suppress trial sequence, enroll in onboarding SMS)

---

### SECTION 3: WEBINAR & EVENT CONFIRMATION FLOW

**Objective:** Lift webinar show rates from industry average (35–45%) to 55–70% through multi-touch SMS reminders that reduce calendar conflicts and last-minute no-shows.

Deliver 4 messages:
- **Confirmation SMS** (immediately after registration): Confirms registration, adds to calendar CTA, introduces speaker
- **48-Hour Reminder** (2 days before event, 9am): Teases key takeaway/insight they'll miss if they don't attend
- **Day-Of Morning Reminder** (day of event, 8am local): Simple direct reminder with join link
- **1-Hour Before** (60 minutes before start): Final reminder with direct join URL + quick value proposition

For each message: full copy, character count, personalization variables, link strategy (shortened URLs with UTM tracking).

**Post-Event SMS** (within 60 minutes of event end):
- Segment A (Attendees): Thank you + replay link + next step CTA (book demo / download resource)
- Segment B (Registrant No-Shows): "You missed it" + replay link + time-limited offer

---

### SECTION 4: SPEED-TO-LEAD SMS RESPONSE SYSTEM

**Objective:** Contact high-intent inbound leads via SMS within 5 minutes of form submission, before they submit to 2–3 competitors, achieving 40–60% same-day meeting booking rates.

**Trigger Segments (ranked by intent score):**
- Tier 1: Demo request form submission → Immediate SMS within 2 minutes
- Tier 2: Pricing page view + contact form → SMS within 5 minutes
- Tier 3: ROI calculator completion + email capture → SMS within 10 minutes

For each tier, deliver:
- **Initial Contact SMS:** Acknowledge their inquiry, set expectation, offer direct booking link
- **Follow-Up SMS** (if no response in 4 hours): Second touch with different value angle
- **Final SMS** (if no response next morning): Low-pressure final reach with clear opt-out path

**AE/SDR Integration Protocol:**
- How the SMS appears in the sales rep's workflow (Salesforce task, Slack notification, etc.)
- Rep response triggers (if prospect replies to SMS, how rep is notified)
- Handoff from automated SMS to rep-managed conversation

---

### SECTION 5: RENEWAL & EXPANSION SMS CAMPAIGN

**Objective:** Defend renewals and surface expansion opportunities using SMS as a high-attention complement to email renewal campaigns.

**60-Day Renewal Sequence (5 messages):**
- **Day –60:** Health check + value summary (personalized usage stats if available)
- **Day –30:** ROI reinforcement + social proof from similar customers
- **Day –21:** Expansion offer (upgrade tier, add seats, add modules)
- **Day –7:** Urgency + direct CSM/AE introduction ("your account manager [Name] will be in touch")
- **Day –1:** Final renewal reminder + self-service renewal link (for low-ACV accounts)

For each message: copy, personalization variables (renewal date, usage stats, CSM name), escalation triggers (what routes to human CSM).

**Expansion Signal Triggers (separate from renewal sequence):**
- Usage spike (>X% increase in last 30 days) → Expansion SMS
- Feature limit reached → Upgrade prompt SMS
- New buyer joins account (job title match to ICP) → Welcome + relevant use case SMS

---

### SECTION 6: RE-ENGAGEMENT SEQUENCES

**Objective:** Reactivate dormant trial users and cold leads before they're permanently lost.

**6A: Dormant Trial User Sequence (no login in 7+ days)**
- Message 1 (Day 7 of inactivity): Curiosity hook — "What's blocking you, [Name]?"
- Message 2 (Day 10): Specific use case they haven't tried + quick-start link
- Message 3 (Day 13): Extension offer or live walkthrough with human (last chance before trial expires)

**6B: Cold Lead Re-Engagement (no engagement in 90+ days)**
- Message 1: Reference to their original interest + new development (product update, relevant news)
- Message 2 (3 days later, if no response): Social proof from their industry
- Message 3 (5 days later, if no response): Clean breakup message with opt-out ("Should I remove you from our list?") — this reverse psychology message often generates the highest response rates

For each message: full copy, trigger conditions, suppression logic (do not send if contact has unsubscribed from any channel).

---

### SECTION 7: TECHNICAL INTEGRATION ARCHITECTURE

**7.1 Platform Configuration:**
- Recommended SMS platform for [Company's stack] with rationale
- API integration points: CRM ↔ SMS platform, MAP ↔ SMS platform
- Webhook setup for real-time trigger firing
- UTM parameter structure for SMS campaign attribution

**7.2 Data Flow Diagram:**
Provide a step-by-step data flow for the highest-volume sequence (Trial Activation):
- Data fields passed from trial signup form → CRM → SMS platform
- Trigger conditions evaluated in real time
- Opt-out propagation across all systems within 24 hours
- Attribution tracking: SMS → click → conversion → pipeline

**7.3 Reporting Dashboard Design:**
Metrics to track per sequence:
- Delivery rate / opt-out rate / complaint rate (compliance)
- Click-through rate per message
- Conversion rate (message to desired action)
- Pipeline influenced / pipeline sourced by SMS
- Revenue attributed to SMS sequences (last-touch and influenced)

---

### SECTION 8: TESTING & OPTIMIZATION ROADMAP

**Phase 1 (Weeks 1–4):** Launch trial activation + speed-to-lead sequences. Establish baseline metrics.
**Phase 2 (Weeks 5–8):** Launch webinar confirmation flow. A/B test top 3 highest-volume messages from Phase 1.
**Phase 3 (Weeks 9–12):** Launch renewal + re-engagement sequences. Run multivariate test on message timing (morning vs. afternoon sends).
**Phase 4 (Months 4+):** Introduce AI-generated personalization at scale (dynamic content based on feature adoption, industry, role).

**A/B Test Priority Queue:**
1. Message 1 of trial sequence: Direct CTA vs. question-based opener
2. Webinar reminder: Specific insight teaser vs. social proof (attendee count)
3. Speed-to-lead: Rep's name in first SMS vs. brand-signed message
4. Renewal Day –7: Urgency ("expires in 7 days") vs. value ("your team has done X in the last year")

## Example Input/Output

**Input Example:**

Company: Stackline (B2B SaaS for retail analytics)
ICP: VP Ecommerce, Director of Digital, at brands doing $50M–$500M in retail revenue
Trial length: 14 days | Current trial-to-paid: 18% | Target: 28%
SMS platform: None currently | CRM: Salesforce | MAP: HubSpot
Monthly trial signups: 340 | Current webinar show rate: 38% | Target: 55%
Personalization data available: First name, company, trial signup date, last login, webinar topic

**Output Example (Trial Activation — Message 1):**

**Trigger:** Trial signup form submitted (any time of day)
**Segment:** All new trial users who provided mobile number with SMS opt-in
**Timing:** Within 10 minutes of signup, regardless of hour (time-sensitive)
**Message A (Primary):**
> Hi [First Name] — your Stackline trial is live. See your brand's Amazon share of voice in 3 clicks: [shortlink] Questions? Reply here. To opt out, reply STOP.

*Character count: 148 | Personalization: First Name, brand name from signup field*

**Message B (A/B Variant):**
> [First Name], your Stackline trial starts now. Most teams find their first insight in under 5 min — here's where to start: [shortlink] Reply STOP to opt out.

*Character count: 152 | Test hypothesis: "most teams" social proof vs. direct CTA*

**Goal:** Click shortlink → complete first analysis → activation event recorded
**Success Metric:** 35%+ click rate, 20%+ activation within 24 hours of this message

---

**Output Example (Speed-to-Lead — Tier 1 Demo Request):**

**Trigger:** HubSpot form "Request a Demo" submitted
**Timing:** Within 90 seconds via Zapier/HubSpot SMS workflow
**Message:**
> Hi [First Name], it's [AE Name] from Stackline — saw your demo request just come in. I have 15 min open at [Time Option 1] or [Time Option 2] today. Does either work? Book here: [Calendly link] | Reply STOP to opt out.

*Character count: 183 (2 messages at 160 chars each if sent as single SMS) — recommend splitting or using MMS*

**Result benchmark:** Companies implementing sub-2-minute SMS speed-to-lead response see 35–50% same-day meeting booking rates vs. 5–10% for next-day email follow-up alone.

## Success Metrics

**Compliance Health (Monitor Weekly):**
- SMS opt-out rate: Below 2% per campaign (>2% is a red flag for irrelevance or over-messaging)
- Carrier complaint rate: Below 0.08% (above this risks sending domain blacklisting)
- Delivery rate: Above 95% (below indicates list hygiene issues)

**Engagement Performance (Monitor Per Campaign):**
- Trial activation SMS click rate: 25–40% (industry benchmark for B2B SaaS lifecycle SMS)
- Webinar confirmation show rate lift: +15–25 percentage points vs. email-only
- Speed-to-lead response rate within 1 hour: 30–50%
- Renewal SMS contribution to on-time renewal: 10–20% of renewals touched by SMS sequence

**Revenue Attribution (Monitor Monthly):**
- Pipeline influenced by SMS sequences (any SMS touch in 30-day pre-opportunity window)
- Trial-to-paid conversion rate lift with SMS vs. without (A/B holdout test)
- Renewal save rate for accounts that engaged with renewal SMS vs. those who didn't
- SMS-sourced pipeline as % of total marketing-sourced pipeline

**Operational Health:**
- Opt-in rate on trial signup form: Target 40–60% of signups (higher with clear value prop)
- List growth month-over-month: Track new SMS opt-ins vs. opt-outs net
- Sequence completion rate: % of contacts who receive all messages without opting out

## Related Prompts
- [AI-Powered B2B SaaS Inbound Email Marketing Architecture & Behavioral Lead Lifecycle Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing/AI-Powered-B2B-SaaS-Inbound-Email-Marketing-Architecture-&-Behavioral-Lead-Lifecycle-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS WhatsApp Business API Pipeline Marketing Architecture & Conversational Demand Generation Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Conversational-Marketing/AI-Powered-B2B-SaaS-WhatsApp-Business-API-Pipeline-Marketing-Architecture-&-Conversational-Demand-Generation-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Free Trial Activation Funnel CRO & Time-to-Value Conversion Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Free-Trial-Activation-Funnel-CRO-&-Time-to-Value-Conversion-Intelligence-Engine.md)
- [AI-Powered SMS WhatsApp Conversational Marketing Analytics & Revenue Attribution Intelligence Engine](../../05_Analytics-&-Performance/Conversational-Marketing-Analytics/AI-Powered-SMS-WhatsApp-Conversational-Marketing-Analytics-&-Revenue-Attribution-Intelligence-Engine.md)

## Integration Tips

**HubSpot + Salesmsg/SimpleTexting:**
- Connect via native HubSpot integration or Zapier workflow
- Use HubSpot enrollment triggers (workflow → contact property change) to fire SMS sequences
- Map SMS opt-in/opt-out status to a custom HubSpot contact property that syncs bidirectionally
- Build SMS sends into existing HubSpot lifecycle sequences as a parallel track to email
- Attribution: Use UTM parameters on all SMS links (`utm_source=sms&utm_medium=lifecycle&utm_campaign=trial-activation`) and verify they populate HubSpot deal source fields

**Salesforce + Twilio/Salesmsg:**
- Build SMS automation via Salesforce Flow or Process Builder triggered by lead/contact field changes
- Use Twilio's Salesforce connector to create SMS activity records on contact timelines for full attribution visibility
- AE notification: Create a Salesforce task for the owning rep when a prospect replies to an automated SMS — replies should always trigger human handoff within 5 minutes
- Dashboards: Build Salesforce reports segmenting pipeline by "SMS Engaged = True" vs. control group

**Klaviyo (PLG/Ecommerce-Adjacent B2B):**
- Use Klaviyo's native SMS + email combined flows for unified lifecycle marketing
- Leverage Klaviyo's predictive analytics to identify trial users most likely to convert and intensify SMS cadence for that segment
- Build SMS revenue attribution into Klaviyo's native attribution window (customize to 1-day click, 5-day view for B2B SMS)

**Zapier (Multi-Platform):**
- Zap 1: Demo request form → Twilio/Salesmsg → AE Slack notification (sub-90-second response)
- Zap 2: Trial created in product → HubSpot contact update → SMS platform enrollment in trial sequence
- Zap 3: Webinar registration (Zoom/GoToWebinar) → SMS platform → webinar reminder sequence enrollment
- Zap 4: CRM renewal date < 60 days → SMS platform → renewal sequence enrollment

**Compliance Automation:**
- Sync opt-outs from SMS platform → CRM and MAP within 24 hours (automate with native sync or Zapier)
- Use your MAP (HubSpot/Marketo) as the master opt-out suppression list — always query it before any SMS send
- Schedule quarterly TCPA compliance audit in your calendar: review opt-in records, suppression list accuracy, carrier compliance reports

## Troubleshooting

**Problem: High opt-out rate (>3%) on trial activation sequence**
Solution: The sequence is likely too frequent or the messages feel like spam rather than service. Audit: (1) Reduce to max 3 messages in first 7 days of trial. (2) Rewrite openers to lead with value ("You haven't tried [Feature X] yet — it's the one feature teams say changed everything") rather than CTAs. (3) Add explicit expectation-setting in the opt-in moment: "We'll text you 2–3 times during your trial with tips — you can stop anytime." Lower frequency + higher relevance = dramatically lower opt-out rates.

**Problem: Webinar show rate not improving despite SMS reminders**
Solution: SMS reminders alone won't fix a show rate problem caused by poor audience-topic fit or bad timing. Diagnose first: (1) Survey non-attendees (email survey 24 hours post-event) — was it the topic, the time, or they forgot? (2) If it's topic/timing: SMS reminders won't help — fix the program. (3) If it's "I forgot": The problem is your day-of SMS isn't landing. Check: Is it going out at 8am or at 7am local? Is the link working? Is it being filtered by corporate mobile MDM? Try sending day-before reminder at 5pm instead of 48 hours out — closer to when people plan their next day.

**Problem: Speed-to-lead SMS not generating responses — leads go dark after the first SMS**
Solution: The most common cause is the SMS feels automated and impersonal. Fix: (1) Include the AE's actual name and reference the specific thing they requested ("Saw your request for a demo on [product area]"). (2) Offer a specific time slot rather than "let me know when works" — "I have 10am or 2pm ET today, does either work?" forces a yes/no/alternative rather than an open-ended non-response. (3) If your SMS platform supports it, enable two-way messaging and have reps actively monitor and respond to replies within 5 minutes — this is the single biggest driver of meeting booking rates.

## Version History
- v1.0: Initial creation (auto-generated)
