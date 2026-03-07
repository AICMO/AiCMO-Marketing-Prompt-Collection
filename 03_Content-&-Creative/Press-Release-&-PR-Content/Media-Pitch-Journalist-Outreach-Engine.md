# Media Pitch & Journalist Outreach Engine - AI-Powered PR Relationship Builder

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** pr, media-relations, b2b, content, earned-media, automation

## Overview
Generates hyper-personalized media pitches, journalist research profiles, story angle frameworks, and follow-up sequences that earn earned media coverage — without a PR agency. Use it when you have news to announce, thought leadership to place, or a reactive opportunity (data drop, trend hook, or news-jacking moment).

## Quick Copy-Paste Version

You are a veteran PR strategist who has placed stories in TechCrunch, Forbes, WSJ, and top industry trade publications. Your job is to craft a media pitch that a journalist will actually respond to.

Here's my news:
- Company: [Your Company]
- Announcement: [What you're announcing — product launch, funding, study, milestone, partnership]
- Why now: [What trend, news event, or data makes this timely]
- Proof point: [One specific number or fact that validates the story]

Do the following:

1. STORY ANGLE: Write 3 distinct angles for this story — one for a general business publication (e.g. Forbes), one for an industry trade pub, one for a tech or startup publication. Each angle should be 1 sentence and include a specific hook journalists will care about.

2. SUBJECT LINE: Write 5 subject lines for a cold pitch email — each under 8 words, no buzzwords, no exclamation points. Make them feel like a tip from a peer, not a PR blast.

3. PITCH EMAIL: Write the pitch email using this structure:
   - Line 1: One sentence that references the journalist's recent work (leave [JOURNALIST_RECENT_ARTICLE] as a placeholder)
   - Lines 2-3: The story in plain English — what happened, why it matters right now, who cares
   - Line 4: Your one strongest proof point (a stat, a name, a result)
   - Line 5: The offer (interview, data, exclusive)
   - Sign-off: 2-line bio that establishes credibility without sounding corporate

4. FOLLOW-UP SEQUENCE: Write 2 follow-up emails — Day 5 and Day 10 — that add new value rather than just bumping the original pitch. Each under 75 words.

Output everything clearly labeled. Keep the pitch email under 200 words total.

## Advanced Customizable Version

ROLE: You are a senior PR director with 15+ years of earned media experience across B2B SaaS, fintech, healthtech, and consumer brands. You understand the psychology of journalists — their deadlines, their beats, their need to look smart to their editors. You never send spray-and-pray pitches.

CONTEXT:
- Company name: [Company]
- Industry/vertical: [e.g., B2B HR tech, D2C wellness, fintech]
- Announcement type: [PRODUCT_LAUNCH | FUNDING | DATA_STUDY | PARTNERSHIP | EXECUTIVE_HIRE | MILESTONE | REACTIVE_NEWSJACK]
- Key message: [One sentence — what you want the world to know]
- Audience for coverage: [Who reads the publications you're targeting — e.g., "VP-level HR buyers at mid-market companies"]
- Competitors who have gotten coverage: [Optional — helps identify what worked]
- Embargo/timing: [If applicable]
- Spokesperson: [Name, title, notable credentials]
- Exclusive available: [Yes/No — are you offering one outlet first rights?]

OBJECTIVE: Produce a complete, ready-to-send journalist outreach package.

---

STEP 1 — JOURNALIST TARGETING MATRIX

For each of the 3 publication tiers below, identify the ideal journalist profile (not a specific name — a profile I can use to research):

TIER 1 (Flagship business/tech press — e.g., TechCrunch, Forbes, WSJ, Bloomberg):
- Beat description: [What type of journalist covers this story]
- What they're looking for: [Their editorial incentive]
- Red flags that kill pitches to them: [What to avoid]
- Best time to pitch: [Day of week, time of day based on publication patterns]

TIER 2 (Industry trade publications):
- Which 3 trade categories are most relevant: [e.g., HR Tech Advisor, Fintech Futures, MarTech Series]
- Why trade coverage matters here: [Audience alignment argument]
- Trade pitch angle difference from Tier 1: [How the hook shifts]

TIER 3 (Newsletters and niche media — Substack, podcasts, LinkedIn newsletters):
- Audience size vs. influence tradeoff: [Why smaller can be better here]
- 2 types of newsletter/podcast shows that cover this beat
- What these creators need vs. what traditional journalists need

---

STEP 2 — STORY ANGLE DEVELOPMENT (NEWS FRAMEWORK)

Apply the NEWS framework to generate 4 story angles:
- N (Newsworth): What makes this timely — tie to a market trend, regulatory shift, cultural moment, or competitor move
- E (Exclusive): What insight or data can you offer that no one else has
- W (Well-sourced): What third-party validation or customer proof elevates credibility
- S (Specific): What concrete number, name, or outcome anchors the story

For each angle, write:
- Angle name: [3-word label]
- Target pub type: [Which tier this angle serves]
- Pitch hook: [1 sentence — the "did you know?" opener]
- Narrative arc: [3-bullet story structure: Problem → Proof → Payoff]
- Risk: [What a skeptical journalist might push back on — and your pre-answer]

---

STEP 3 — PERSONALIZED PITCH EMAIL

Write a pitch email for TIER 1 outreach. Apply these rules:
- Max 180 words
- First sentence references the journalist's work (use [JOURNALIST_NAME] and [JOURNALIST_RECENT_PIECE] as placeholders)
- Use the inverted pyramid: biggest news first
- No adjectives that aren't backed by a fact (no "revolutionary," "game-changing," "innovative")
- Include one specific stat or data point in the first 3 sentences
- Clear ask: interview, data access, or exclusive — pick one
- No attachments in first pitch (offer to send press release, data, or media kit on request)

Subject lines (write 7 variations, each under 8 words):
- 2 curiosity-based
- 2 data-led
- 2 trend-hook
- 1 direct/transactional

---

STEP 4 — FOLLOW-UP SEQUENCE (3-TOUCH)

TOUCH 2 (Day 5 — Value-add follow-up):
- Add a new data point, new customer quote, or reference a piece of news that broke after your first pitch that makes your story more relevant
- Never say "just following up" or "bumping this to the top of your inbox"
- Max 80 words

TOUCH 3 (Day 10 — Pivot or close):
- Offer an alternative angle or a different story format (op-ed byline, podcast appearance, data exclusive to a different pub)
- Give a polite deadline ("closing the embargo on [DATE]")
- Max 60 words

TOUCH 4 (Day 21 — Relationship builder, not pitch):
- Drop the ask entirely
- Share a piece of insight, data, or content genuinely useful to their beat
- Plant seeds for a future story
- Max 50 words

---

STEP 5 — REACTIVE NEWSJACKING PROTOCOL

When a relevant news story breaks, activate this protocol within 4 hours:

Trigger: [Describe the breaking news or trend]
Your angle: [How your company/data/executive is uniquely positioned to comment]
Spokesperson credentials: [Why your exec is a credible voice on this]

Generate:
1. A reactive pitch email (max 120 words) that offers your spokesperson as an expert source — not promoting your product
2. A pre-written quote (2-3 sentences) your spokesperson can send immediately if the journalist requests a statement
3. A Twitter/X DM version of the pitch (max 280 characters) for journalists active on social

---

STEP 6 — MEDIA RELATIONSHIP TRACKER (CRM FIELDS)

For each journalist contacted, output a structured data record:

{
  "journalist_name": "",
  "publication": "",
  "beat_keywords": [],
  "last_story_published": "",
  "pitch_date": "",
  "subject_line_used": "",
  "open_status": "[OPENED | NOT_OPENED | UNKNOWN]",
  "response_status": "[NO_REPLY | REPLIED_INTERESTED | DECLINED | COVERAGE_PUBLISHED]",
  "follow_up_dates": [],
  "relationship_notes": "",
  "preferred_contact_method": "[EMAIL | TWITTER | LINKEDIN]",
  "exclusive_offered": false,
  "coverage_url": "",
  "next_action": ""
}

Output one record per journalist. This is ready to import into Notion, HubSpot, or Airtable.

## Example Input/Output

**Input Example:**
Company: Meridian AI (B2B SaaS — AI-powered contract review for legal teams)
Announcement: Releasing a data study: "2026 Contract Risk Report" — analysis of 2.1M enterprise contracts showing that AI-flagged risk clauses are 3.4x more likely to result in litigation than human-only reviewed contracts
Why now: Wave of high-profile contract disputes hitting Fortune 500s post-pandemic; EU AI Act compliance deadline approaching
Proof point: $2.3B in contract-related litigation costs analyzed across dataset
Spokesperson: Dr. Amara Osei, Chief Legal Innovation Officer, former BigLaw partner at Skadden
Exclusive: Offering to WSJ Legal Beat first

**Output Example (abbreviated):**

**Story Angles:**

*Angle 1 — "The $2.3B Blind Spot" (Tier 1: WSJ, Bloomberg Law)*
Hook: "AI contract tools are flagging risk — but companies that rely on AI alone are 3.4x more likely to end up in litigation than those using human-AI review, according to new data from 2.1M contracts."
Arc: Problem (AI review creates false confidence) → Proof (2.1M contract dataset, $2.3B in litigation costs) → Payoff (human-AI hybrid model reduces risk)

*Angle 2 — "EU AI Act Just Changed Legal's Playbook" (Tier 2: Legal Tech News, Above the Law)*
Hook: "With the EU AI Act requiring explainable AI decisions in high-stakes contracts, here's what 2.1M contracts reveal about where AI legal review actually breaks down."

**Subject Lines:**
- AI contract review backfiring — data from 2.1M deals
- $2.3B in litigation: what AI missed in enterprise contracts
- Before the EU AI Act deadline: what your contracts reveal
- New data: AI review is 3.4x riskier than expected
- Legal teams are trusting AI too much

**Pitch Email (WSJ, Tier 1):**
> Hi [JOURNALIST_NAME],
>
> Your piece on [JOURNALIST_RECENT_PIECE] flagged exactly the dynamic we just quantified at scale.
>
> We analyzed 2.1 million enterprise contracts and found something counterintuitive: contracts reviewed exclusively by AI tools are 3.4x more likely to generate litigation than those reviewed by a human-AI team — representing $2.3B in avoidable legal costs across our dataset.
>
> The timing is tight: EU AI Act enforcement begins in 90 days, and most enterprise legal teams don't know their review workflow is out of compliance.
>
> Dr. Amara Osei (former Skadden partner, now Chief Legal Innovation Officer at Meridian) is available for an exclusive interview this week. I can send the full dataset and embargo'd report now.
>
> Worth 20 minutes?
>
> — [Your name], [Title]
> Meridian AI | meridian.ai

**Follow-Up Touch 2 (Day 5):**
> Quick add to my pitch, [JOURNALIST_NAME]: yesterday's Accenture breach settlement ($340M) involved the exact clause type our data flagged as highest-risk in SaaS vendor contracts. Makes the dataset timing feel less coincidental. Full breakdown available if useful.

## Success Metrics
- Journalist response rate > 15% on cold outreach (industry average is 3–8%)
- Coverage-to-pitch ratio: target 1 placement per 10–15 personalized pitches
- Tier 1 placements: 1+ per major announcement cycle
- Follow-up sequence open rate: Day 5 email should outperform Day 1 by 20%+ (curiosity gap)
- Time-to-first-response: under 72 hours indicates strong subject line/angle fit
- Share of voice in target publications: track via Google Alerts + Meltwater/Cision

## Related Prompts
- [Press Release Generation](./Press-Release-Generation.md)
- [Crisis Communication & Emergency Response](../../01_CMO-&-Leadership/Brand-Stewardship/Crisis-Communication-Emergency-Response.md)
- [LinkedIn Thought Leadership Engine](../Social-Media-Content/LinkedIn-Thought-Leadership-Engine.md)
- [Brand Voice Development](../../02_Product-Marketing/Positioning-&-Messaging/Brand-Voice-Development.md)

## Integration Tips
- **Notion**: Import the CRM tracker JSON output directly into a Notion database. Create a `Journalist CRM` table with the fields from Step 6. Add a `Coverage Pipeline` kanban view (columns: Pitched → Opened → Replied → In Progress → Published).
- **HubSpot**: Use the journalist records as HubSpot contacts with a custom `Media Contact` tag. Set up a follow-up sequence using HubSpot Sequences triggered by email open events from Step 4.
- **Airtable**: Paste the JSON output into Airtable's import tool. Add a `Publication Tier` field and a `Story Angle Used` field to track which angles generate responses across journalists.
- **Zapier**: Connect your email open tracking (e.g., Mailtrack or HubSpot) to trigger a Zapier workflow that updates the journalist CRM record and queues the next follow-up touch.
- **Google Sheets**: Use the CRM fields as column headers for a lightweight tracking sheet. Add a `Coverage Value (AVE)` column to calculate estimated advertising value equivalent of earned placements.
- **Slack**: Set up a Google Alerts → Zapier → Slack workflow to surface reactive newsjacking opportunities within minutes of a trigger story publishing.

## Troubleshooting
- **Problem:** Pitches getting no response even after 3 touches.
  **Solution:** The story angle is likely too company-centric. Rerun Step 2 and force yourself to lead with industry data or a contrarian insight — not your product feature. Journalists write about trends, not companies.

- **Problem:** Getting replies asking for information you don't have (proprietary data, customer quotes, third-party validation).
  **Solution:** Before pitching, run Step 2 and pre-identify your weakest evidence link. Either get the asset (a customer quote takes 48 hours to collect) or adjust the angle to one your current evidence supports fully.

- **Problem:** Tier 1 journalists are interested but stories keep getting killed by editors.
  **Solution:** Journalists have editorial constraints you can't see. Offer to make the story more broadly relevant: add an industry-wide data angle, a policy hook, or a competitor contrast. Also offer a byline or op-ed as an alternative — it's more controllable and still earns the placement.

## Version History
- v1.0: Initial creation (auto-generated)
