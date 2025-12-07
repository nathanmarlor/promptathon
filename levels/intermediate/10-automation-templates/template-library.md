# Prompt Template Library

Ready-to-use templates for common recurring tasks.

---

## Template 1: Weekly Status Report

**Trigger:** Every Friday afternoon

**Inputs needed:**
- {ACCOMPLISHMENTS}: Key wins and completions
- {BLOCKERS}: Issues encountered
- {NEXT_WEEK}: Coming priorities
- {STAKEHOLDER}: Report recipient

**Prompt:**
```
Context: Generate my weekly status report for week ending [date].
My accomplishments: {ACCOMPLISHMENTS}
Blockers: {BLOCKERS}
Next week priorities: {NEXT_WEEK}

Language: Professional, concise, achievement-focused.
Focus on outcomes, not activities.

Examples: Structure as:
• ACCOMPLISHMENTS (3-5 bullets, outcome-focused)
• BLOCKERS (issues + what I need, or "None")
• NEXT WEEK (3-5 priorities in order)
• CALL-OUTS (anything needing attention)

Audience: {STAKEHOLDER} who scans multiple reports.

Request: Under 200 words. Direct and scannable.
```

**Quality checklist:**
- [ ] Accomplishments focus on outcomes, not tasks
- [ ] Blockers include clear asks
- [ ] Priorities are specific
- [ ] Under 200 words

---

## Template 2: Meeting Summary

**Trigger:** After significant meetings

**Inputs needed:**
- {MEETING_NAME}: Meeting title
- {ATTENDEES}: Who was there
- {NOTES}: Raw notes or transcript

**Prompt:**
```
Context: Summarise this meeting: {MEETING_NAME}
Attendees: {ATTENDEES}
Notes: {NOTES}

Language: Factual, neutral. Capture decisions, not discussion.

Examples: Structure as:
1. KEY DECISIONS (numbered list)
2. ACTION ITEMS (owner + deadline)
3. OPEN QUESTIONS (for follow-up)
4. NEXT MEETING (if scheduled)

Audience: Attendees for confirmation, non-attendees for catch-up.

Request: Maximum 1 page. Bullet format.
Each action item must have an owner.
```

**Quality checklist:**
- [ ] All decisions captured
- [ ] Every action has an owner
- [ ] Open items flagged
- [ ] Would make sense to someone who wasn't there

---

## Template 3: Stakeholder Update

**Trigger:** Monthly or milestone updates

**Inputs needed:**
- {PROJECT}: Project name
- {STATUS}: Current status (On Track/At Risk/Blocked)
- {PROGRESS}: Key progress since last update
- {UPCOMING}: Next milestones
- {RISKS}: Current risks or issues

**Prompt:**
```
Context: Project update for {PROJECT}.
Status: {STATUS}
Progress: {PROGRESS}
Upcoming: {UPCOMING}
Risks: {RISKS}

Language: Confident if on track, direct if not. No hedging.

Examples: Structure as:
• STATUS SUMMARY (1 sentence)
• PROGRESS SINCE LAST UPDATE (3-4 bullets)
• UPCOMING MILESTONES (next 30 days)
• RISKS/ISSUES (if any, with mitigation)
• SUPPORT NEEDED (if any)

Audience: Project stakeholders who want the headlines.

Request: Half-page maximum. Traffic light status prominent.
```

---

## Template 4: Email Response to Complaint

**Trigger:** Customer or stakeholder complaint

**Inputs needed:**
- {COMPLAINT_SUMMARY}: What they're unhappy about
- {ROOT_CAUSE}: Why it happened
- {RESOLUTION}: What we're doing
- {RELATIONSHIP}: Relationship context

**Prompt:**
```
Context: Responding to complaint about {COMPLAINT_SUMMARY}.
Root cause: {ROOT_CAUSE}
Our resolution: {RESOLUTION}
Relationship: {RELATIONSHIP}

Language: Empathetic but not groveling. Solution-focused.
Acknowledge their experience without excessive apology.

Examples: Structure as:
1. Acknowledge the issue (1-2 sentences)
2. Take responsibility (brief)
3. Explain resolution (specific)
4. Prevent recurrence (how)
5. Offer to discuss (optional)

Audience: Frustrated but reasonable stakeholder.

Request: Under 150 words. Professional, warm, solution-oriented.
```

---

## Template 5: Document Executive Summary

**Trigger:** When sending long documents

**Inputs needed:**
- {DOCUMENT}: The full document content
- {RECIPIENT}: Who's receiving this
- {PURPOSE}: Why you're sending it

**Prompt:**
```
Context: Summarising this document for {RECIPIENT}.
Purpose: {PURPOSE}
Document: {DOCUMENT}

Language: Bottom line up front. No preamble.

Examples: Structure as:
• THE POINT (1-2 sentences)
• KEY INFORMATION (3-5 bullets)
• ACTION NEEDED (if any)
• DETAIL LOCATION (where to find more)

Audience: {RECIPIENT} who needs the headlines before deciding 
whether to read the full document.

Request: Maximum 100 words. Would stand alone in an email body.
```

---

## How to Use These Templates

1. Copy the template
2. Replace all {PLACEHOLDERS} with your specific content
3. Adjust language/structure if needed for your context
4. Run and review output
5. Edit as needed—templates get you 80% there

---

## Creating Your Own Templates

See `template-design-guide.md` for how to create templates for your specific needs.

