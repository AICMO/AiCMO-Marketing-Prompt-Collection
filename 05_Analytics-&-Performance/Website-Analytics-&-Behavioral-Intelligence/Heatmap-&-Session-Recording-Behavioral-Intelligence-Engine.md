# Heatmap & Session Recording Behavioral Intelligence Engine - AI-Powered UX Diagnostics & Friction Elimination

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** heatmaps, session recording, behavioral analytics, CRO, UX diagnostics, Hotjar, FullStory, Microsoft Clarity, friction analysis, user behavior

## Overview
Transforms raw heatmap data, session recording observations, and form analytics into a prioritized friction elimination roadmap with revenue impact estimates. Use it when you have qualitative behavioral data from tools like Hotjar, FullStory, Microsoft Clarity, or Heap and need to convert observations into a concrete A/B test backlog with ICE-scored priorities — without needing a dedicated UX researcher.

## Quick Copy-Paste Version

You are a senior UX research and CRO strategist with expertise in behavioral analytics, session recording analysis, and conversion optimization. Analyze the following behavioral data and produce a prioritized friction elimination report with specific A/B test recommendations.

BEHAVIORAL DATA TO ANALYZE:
- Tool used: [Hotjar / FullStory / Microsoft Clarity / Heap / Mouseflow]
- Page(s) analyzed: [e.g., /pricing, /demo-request, /homepage]
- Session volume analyzed: [e.g., 850 sessions, last 30 days]
- Primary conversion goal on this page: [e.g., demo request form submission]
- Current conversion rate: [e.g., 3.1%]

HEATMAP OBSERVATIONS:
- Click heatmap: [Describe where users click most, unexpected clicks, non-clickable elements getting clicks]
- Scroll heatmap: [What % reach the fold? Key content? CTA placement?]
- Move/hover heatmap: [Where do users pause, hesitate, read carefully?]

SESSION RECORDING INSIGHTS:
- Most common user paths observed: [describe patterns]
- Rage click locations: [list elements with rage clicks and frequency]
- Dead click locations: [non-interactive elements users try to click]
- U-turn / back navigation patterns: [where do users go back?]
- Error messages or form validation friction: [describe]
- Exit patterns: [where do most users leave?]

FORM ANALYTICS (if applicable):
- Form completion rate: [X%]
- Fields with highest abandonment: [list fields where users drop off]
- Time spent per field: [list any fields taking unusually long]
- Return visits to fix fields: [list fields users correct multiple times]

ADDITIONAL SIGNALS:
- Any user feedback / survey responses from on-page polls: [paste verbatims if available]
- Known technical issues: [e.g., mobile form not scrolling, slow load on certain devices]
- Recent design or copy changes: [what changed recently?]

Deliver:
1. FRICTION SEVERITY MAP: Rank all identified friction points by revenue impact (High/Medium/Low) with estimated monthly conversion loss
2. BEHAVIORAL PATTERN DIAGNOSIS: Explain the "why" behind each friction point using behavioral psychology principles (cognitive load, loss aversion, Fogg Behavior Model, etc.)
3. ICE-SCORED TEST BACKLOG: 8-12 specific A/B tests ranked by Impact × Confidence × Ease (each 1-10)
4. WEEK-1 QUICK WINS: 3 no-developer changes with expected lift and implementation instructions
5. QUALITATIVE-TO-QUANTITATIVE BRIDGE: For each behavioral insight, identify the GA4 metric to validate it and the success threshold for any test

Format every recommendation with: Hypothesis → Test Design → Success Metric → Expected Lift Range → Implementation Complexity.

## Advanced Customizable Version

ROLE: You are a Principal Behavioral Analytics Strategist and UX Research Lead with 12+ years running CRO programs at B2B SaaS, eCommerce, and D2C companies. You specialize in extracting revenue-grade insights from qualitative behavioral data — session recordings, heatmaps, form analytics, and user feedback — and translating them into rigorous A/B test programs. You use frameworks including the Fogg Behavior Model (Motivation × Ability × Trigger), Jobs-to-be-Done, Heuristic Evaluation (Nielsen's 10), and the LIFT Model to diagnose friction. You never recommend changes without a specific behavioral evidence trail.

BUSINESS CONTEXT:
- Company: [Company Name]
- Business model: [B2B SaaS / eCommerce / D2C / Marketplace / SaaS-led growth]
- Target ICP: [Job title, company size, pain profile]
- Page type: [Homepage / Pricing / Demo/Trial landing page / Product page / Checkout / Onboarding]
- Primary conversion event: [Demo request / Free trial signup / Purchase / Activation step]
- Secondary micro-conversions: [Scroll to pricing / Click on testimonial / Video play / Chatbot open]
- Average deal value or AOV: [$X]
- Monthly sessions to this page: [X]
- Current conversion rate: [X%]
- Conversion rate benchmark (industry or your own historical best): [X%]

---

BEHAVIORAL ANALYTICS DATA:

**HEATMAP DATA:**

Click Heatmap:
- Top-5 clicked elements (in order): [element name, click %, expected vs. actual]
- Non-clickable elements receiving clicks (confused intent): [list with click counts]
- CTA button click rate: [X% of sessions clicked primary CTA]
- Navigation vs. content engagement ratio: [X% nav clicks vs. Y% content clicks]
- Above-fold vs. below-fold click distribution: [X% vs. Y%]

Scroll Heatmap:
- % of sessions reaching 25% / 50% / 75% / 100% page depth: [X% / X% / X% / X%]
- Scroll stop zones (where do users linger before scrolling?): [describe sections]
- Content below 50% scroll: [what key content are 40%+ of users missing?]
- CTA position vs. scroll depth: [what % of users see the primary CTA?]

Move/Hover Heatmap:
- Elements with high hover but low click (confusion or hesitation signals): [list]
- Tooltip or label hover patterns: [are users reading explanatory text before deciding?]
- Navigation hover without click (consideration without action): [list menu items]

**SESSION RECORDING ANALYSIS:**

Observation Volume: [X sessions reviewed; X% sampled from converting sessions, X% from non-converting]

Engagement Patterns:
- Median time-on-page: [X seconds]
- Median scroll depth: [X%]
- Most common entry scroll position: [e.g., users reload and land mid-page]

Friction Signals (list each with frequency and severity):
- Rage clicks: [Element | Occurrences/100 sessions | Likely cause]
- Dead clicks: [Element | Occurrences/100 sessions | What user likely expected]
- Hesitation zones (cursor hovering without action for 3+ seconds): [Element | Frequency]
- U-turns / back-button usage: [After viewing which page section?]
- Tab / window switching patterns: [Are users leaving to research competitors or look something up?]
- Mobile-specific friction: [Tap targets too small? Horizontal scroll? Form keyboard issues?]
- Error states observed: [Form validation errors | Frequency | User response (retry, abandon, reload)]
- Unexpected navigation sequences: [Users going to FAQ/Support before converting — signal of anxiety/uncertainty]

Conversion Session Patterns (from recording review of converting sessions):
- Typical scroll depth before converting: [X%]
- Content sections converting users consistently engaged with: [list]
- Time from landing to conversion for typical converter: [X min X sec]
- Any behavioral trigger observed just before conversion (e.g., reading a testimonial, viewing a pricing FAQ): [describe]

Non-Converting Session Exit Patterns:
- Top 3 exit points: [Page section | % of non-converters who exited here]
- Most common last interaction before exit: [e.g., price section scroll, form field focus then abandon]
- Sessions showing research behavior (many pages visited, tab switching): [X% of non-converting sessions]

**FORM ANALYTICS:**
- Form start rate (% of page visitors who interact with form): [X%]
- Form completion rate (of those who start): [X%]
- Overall form conversion rate (page visitors → submission): [X%]
- Field-level abandonment (sorted by drop rate):
  [Field Name | Drop Rate | Avg Time on Field | Return Rate (users who come back to fix)]
- Fields with >30-second average engagement (confusion indicators): [list]
- Multi-step form: step completion rates if applicable: [Step 1 X% → Step 2 X% → Step 3 X%]

**USER FEEDBACK (Polls, Surveys, Heatmap Recordings with Think-Aloud):**
- On-page poll responses (if run): [Question asked | Key response themes with frequency]
- Exit intent survey responses: [What stopped you? | Key verbatims]
- NPS or CSAT comments related to website experience: [paste relevant verbatims]
- Any usability test recordings or transcript excerpts: [paste key observations]

**TECHNICAL OBSERVATIONS:**
- Browser/device breakdown in sessions reviewed: [Desktop X% / Mobile X% / Tablet X%]
- Notable technical errors observed: [JS errors, broken elements, slow sections]
- Page speed perception from recordings: [Does content load visibly slowly before interaction?]
- Mobile UX gaps identified: [list specific mobile-only friction points]

---

DELIVERABLES:

**1. BEHAVIORAL FRICTION AUDIT**
For each identified friction point:
- Evidence: What specific behavioral signals (rage clicks, hesitation, form drops, exit patterns) indicate friction?
- Behavioral Psychology Diagnosis: Apply the relevant framework:
  - Fogg Model: Is Motivation, Ability, or Trigger broken?
  - LIFT Model: Is it a Value Prop, Relevance, Clarity, Anxiety, Distraction, or Urgency issue?
  - Cognitive Load Theory: Is there excessive choice, information overload, or working memory strain?
  - Loss Aversion: Are users more focused on risks than gains from conversion?
- Revenue Impact: Estimated monthly conversions lost from this friction (sessions × drop rate × avg conv rate if fixed × AOV)
- Confidence Level: High / Medium / Low (based on evidence volume)

**2. CONVERTING SESSION BLUEPRINT**
Based on behavioral analysis of sessions that did convert:
- The 3-5 page elements or content sections that converting users consistently engaged with
- The sequence of behaviors that most reliably predicts conversion (behavioral conversion fingerprint)
- Average time-on-page and scroll depth threshold for converter cohort
- What percentage of converting users engaged with social proof, pricing, or specific feature descriptions
- Recommendation: How to design the non-converting path to mirror converting session behavior

**3. ICE-SCORED OPTIMIZATION BACKLOG**
For each test (8-15 tests), format as:

**Test #[N]: [Test Name]**
- Behavioral Evidence: [What specific observation justifies this test?]
- Hypothesis: If we [change X], then [metric Y] will increase by [Z%], because [behavioral insight from recordings/heatmaps]
- Test Design: Control [describe current state] vs. Variant [describe proposed change]
- Primary Metric: [What GA4 event/goal to measure]
- Guardrail Metrics: [What must not decrease — e.g., time-on-page, secondary CTA clicks]
- Expected Lift Range: [X-Y% improvement, based on similar tests in industry]
- ICE Score: Impact [1-10] × Confidence [1-10] × Ease [1-10] = [total]
- Implementation Owner: [Design / Dev / Copywriter / Marketing Ops / No-code]
- Sample Size Required: [Estimated visitors needed per variant for statistical significance at 95% confidence]

Ranked list by ICE score descending.

**4. MOBILE EXPERIENCE GAP ANALYSIS**
If mobile conversion rate < desktop conversion rate:
- Quantify the mobile revenue gap: (Desktop CVR − Mobile CVR) × Monthly Mobile Sessions × AOV = $X/month opportunity
- Top 3 mobile-specific friction points from session recordings
- Mobile-first fixes ranked by implementation effort
- Critical path: Which 2 mobile fixes would close 80% of the conversion gap?

**5. FORM OPTIMIZATION BLUEPRINT**
- Field elimination candidates: Which fields could be removed or deferred (progressive profiling)?
- Field resequencing: Is the most anxiety-inducing field (phone number, company size, budget) appearing before trust is established?
- Microcopy gaps: Which fields need helper text, examples, or format guidance?
- Social proof injection points: Where in the form flow would a testimonial or trust badge have the highest anxiety-reduction impact?
- Form UX quick wins: Autofocus, inline validation, smart defaults, single-column layout adjustments

**6. ANXIETY & TRUST SIGNAL ANALYSIS**
From session recordings of users who showed research behavior (tab switching, hesitation, long pauses):
- What information are users visibly seeking but not finding? (mapped to their last interaction before tab-switch)
- Which objections are not addressed on the page? (cross-reference with form drop fields and exit poll verbatims)
- Trust signal gaps: What social proof, security signals, or risk-reversals are missing or buried below the fold?
- Urgency/scarcity signals: Are conversion triggers present and visible to 75%+ of visitors?

**7. MEASUREMENT & VALIDATION PLAN**
For the top 5 ICE-scored tests:
- GA4 event configuration needed to measure success
- Minimum detectable effect at 80% power and 95% confidence
- Estimated days to reach significance at current traffic volume
- Qualitative validation: After running each test, which session recording behavior to look for to confirm the hypothesis was correct
- Rollout plan: If test wins, what's the full implementation path (design → dev → QA → deploy)?

## Example Input/Output

**Company:** Cascade Security (B2B SaaS, endpoint security compliance, $24K ACV, 45-day sales cycle)
**Page:** /demo-request landing page
**Tool:** Hotjar (1,200 sessions analyzed, 30-day period)
**Current CVR:** 2.8% (33 demo requests/month)

**Input Observations:**
- Rage clicks: "Schedule a Demo" button (48 occurrences/100 sessions) — button has 200ms hover delay before state change
- Dead clicks: Pricing table row headers (31 occurrences/100 sessions) — users expect to expand/click for details
- Scroll heatmap: 67% of users never scroll past the feature list (CTA is below testimonials at 78% scroll depth)
- Form abandonment: "Company Size" dropdown has 41% abandonment rate; "Phone Number" field has 34% abandonment rate
- Exit recordings: 23% of non-converting sessions show users switching tabs after viewing the pricing section
- On-page poll (n=47 responses): "What's stopping you from requesting a demo?" — 38% "Not sure it fits our stack," 29% "Price concerns," 19% "Need to check with IT first," 14% "Not ready yet"
- Mobile CVR: 1.1% vs. desktop 3.6% (mobile = 44% of sessions)

**Output Example:**

**Friction Severity Map:**

1. CTA below 78% scroll depth — HIGH severity
   - Revenue impact: ~67% of visitors never see the primary CTA. If CTA were visible at 40% scroll, conservative 0.6% CVR lift = +7 demos/month = +$168K pipeline/month
   - Fogg Model diagnosis: Trigger failure — high motivation users never encounter the conversion trigger

2. Button interaction delay (rage clicks) — HIGH severity
   - Revenue impact: 48% of sessions clicking primary CTA are experiencing friction. Estimated 15-20% of rage-clickers abandon. Fix = +3-4 demos/month
   - Cognitive Load: Delayed feedback creates uncertainty → re-click → frustration cycle

3. Phone number field requirement — MEDIUM-HIGH severity
   - Revenue impact: 34% of form starters abandon at this field. Making phone optional = +4-5 demos/month = +$96-120K pipeline
   - Loss Aversion: Phone number signals high commitment + cold call fear, breaking the perceived low-risk nature of a demo request

4. Mobile experience gap — HIGH severity
   - Revenue impact: (3.6% − 1.1%) × 528 monthly mobile sessions × $24K ACV × 22% close rate = **$69K/month in mobile revenue gap**

**Top ICE-Scored Tests:**

Test #1: Float CTA button above the fold (sticky CTA or relocated above feature list)
- ICE: Impact 9 × Confidence 8 × Ease 7 = **504**
- Hypothesis: Moving the primary CTA to within first 40% of page scroll will increase demo form starts by 35-50% because 67% of current visitors never encounter the trigger
- Implementation: Design + no-code CMS edit; sticky header variant is a 2-hour dev task

Test #2: Make phone number optional with "We'll use email to schedule" microcopy
- ICE: Impact 7 × Confidence 9 × Ease 9 = **567** ← Highest
- Hypothesis: Removing phone number requirement will increase form completion rate by 25-35% because 34% of starters currently abandon at that field and exit poll confirms "need to check with IT first" is top hesitation (phone implies commitment)
- Implementation: Form field setting change — 15 minutes, no developer

Test #3: Fix button hover delay (reduce to <50ms state change)
- ICE: Impact 6 × Confidence 9 × Ease 8 = **432**
- Implementation: 30-minute developer fix; expected rage click elimination = 3-4% CVR lift

**Week-1 Quick Wins (No Developer):**
1. Make phone number optional: 15-minute form settings change → estimated +0.4% CVR = +5 demos/month
2. Add "What happens after you request a demo?" 3-step visual above form → addresses "not ready" 14% cohort → estimated +0.2% CVR
3. Move one key customer logo/testimonial above the fold (currently at 65% scroll depth) → addresses "not sure it fits our stack" concern (38% of non-converters) → estimated +0.15% CVR lift

## Success Metrics

A high-quality output from this prompt should:
- Identify at least 6 distinct friction points with behavioral evidence (not assumptions)
- Apply at least 2 behavioral psychology frameworks to diagnose each major friction point
- Produce an ICE-scored test backlog of 8-12 tests with specific hypotheses and implementation owners
- Quantify the revenue impact of the top 3 friction points in monthly pipeline dollars
- Deliver a mobile gap analysis with dollar-value opportunity if mobile CVR > 0.5% below desktop
- Include a form optimization blueprint with specific field-level changes
- Provide sample size requirements for statistical significance for top tests

Quality bar: If a recommendation could apply to any website without referencing specific session recording observations or heatmap data from the input, it's too generic. Every test hypothesis must cite the exact behavioral signal that generated it.

## Related Prompts

- `./GA4-Website-Analytics-&-Conversion-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Funnel-Conversion-&-Pipeline-Velocity/Pipeline-Stage-Conversion-Optimization-&-Revenue-Leak-Detection-Engine.md`
- `../../03_Content-&-Creative/Ad-&-Website-Copywriting/CRO-Conversion-Rate-Optimization-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/Marketing-Lead-Quality-&-Sales-Handoff-Intelligence-Engine.md`

## Integration Tips

**Hotjar:**
- Export heatmap screenshots as PNG → describe key click/scroll concentrations in the prompt input
- Use Hotjar's "Highlights" feature to collect tagged session segments (rage clicks, form drops) → summarize themes for the prompt
- Hotjar Surveys: deploy on-exit poll with 1-2 questions → paste verbatim responses as "User Feedback" input
- Hotjar Recordings filter: filter by "Rage clicks = true" OR "U-turns = true" → review top 50 sessions → summarize friction patterns

**Microsoft Clarity (Free):**
- Clarity's "Insights" tab auto-surfaces rage clicks and dead clicks with percentage data — paste directly into prompt
- Clarity's Session Recordings dashboard: filter by "Rage click" segment → review and document patterns
- Clarity + GA4 integration: link accounts to see behavioral segments overlaid on GA4 conversion data

**FullStory / LogRocket:**
- Use FullStory Segments to isolate "frustrated sessions" (rage clicks + short duration + non-convert) → review 20-30 sessions → paste friction patterns
- FullStory DX Data: export frustration signal data as CSV for quantitative analysis; use aggregate percentages as prompt input
- LogRocket: use Funnels feature to identify drop-off points → cross-reference with session recordings of abandoning users

**Google Optimize / Optimizely / VWO / Convert:**
- Feed ICE-scored test backlog directly into A/B testing tool as experiment queue
- Tag each experiment with the behavioral signal that generated the hypothesis for documentation
- Set up GA4 custom events as experiment success metrics; use secondary metrics as guardrails
- After test conclusion: run winning variant's session recordings through this prompt for iteration insights

**HubSpot / Salesforce (Closed-Loop Validation):**
- After implementing a form change, cross-reference lead quality: do new form submissions from the simplified form have the same close rate? (If phone optional led to lower-intent leads, adjust)
- Use HubSpot form analytics to validate field-level abandonment data from Hotjar
- Salesforce campaign reporting: tag leads by A/B test variant → compare pipeline-to-close rates 60 days post-test

**Zapier / Make Automation:**
- Hotjar → Zapier → Google Sheets: auto-log weekly rage click counts and form abandonment rates → feed into prompt as structured input on a cadence
- Weekly behavioral health check: pull Clarity insights summary → format as prompt input → run analysis → post friction score to Slack channel
- A/B test results alert: when VWO/Optimizely test reaches significance → trigger automated post-test analysis prompt

## Troubleshooting

**Problem: "I don't have enough session recordings to identify patterns (low traffic)"**
Fix: With fewer than 200 monthly sessions, focus exclusively on form analytics (field-level abandonment is statistically meaningful even at low volume) and on-page polls (even 20-30 responses reveal the primary objection). For heatmaps, aggregate data over 60-90 days rather than 30. Use qualitative depth over quantitative breadth: review 100% of converting sessions and 50 non-converting sessions rather than sampling.

**Problem: "The output tests are too broad — I can't tell what to actually change on the page"**
Fix: Include specific page element descriptions in your input (not just "the CTA isn't performing" but "the blue 'Request a Demo' button at the bottom of the hero section has X rage clicks and Y% click rate"). Paste the exact on-page copy for elements with friction. The more specific the behavioral evidence description, the more specific the test hypothesis the prompt will generate. Add a screenshot description or paste the page HTML of the element in question.

**Problem: "The revenue impact calculations seem unrealistic for my business"**
Fix: Ensure your AOV/ACV input reflects pipeline value (demos requested × close rate × ACV) rather than only closed revenue — this is what makes CRO improvements feel meaningful to leadership. If you have a long (60+ day) sales cycle, the revenue impact calculation should use pipeline generated, not closed deals. Add your historical form-submission-to-close rate to calibrate the math. Example: "Our demo-to-close rate is 18% over 60 days, ACV is $28K" will produce much more accurate revenue impact estimates.

## Version History
- v1.0: Initial creation (auto-generated)
