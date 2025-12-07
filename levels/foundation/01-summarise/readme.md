# Level 1: Summarise

| | |
|---|---|
| **Difficulty** | ⭐ Beginner |
| **Time** | 5–7 minutes |
| **Tool** | Microsoft 365 Copilot |
| **Skill** | Condense information into actionable insights |

---

## Objective

Transform lengthy documents, email chains, or meeting transcripts into clear, executive-ready summaries that enable faster decision-making.

---

## Business Context

Distilling lengthy content into actionable summaries is a common need. This exercise develops capability with AI-assisted synthesis whilst maintaining accuracy and relevance.

---

## Your Task

**Step 1:** Use one of the sample materials in this folder, or find your own:
- A lengthy email thread requiring action
- Meeting notes or transcript from the past week
- A strategy document or report needing review

**Step 2:** Use Copilot to create an actionable summary

**Step 3:** Evaluate the output against your knowledge of the source material

---

## Sample Materials

This folder includes sample content you can use:

| File | Description |
|------|-------------|
| [sample-email-thread.md](sample-email-thread.md) | Multi-party email discussion about a project decision |
| [sample-meeting-transcript.md](sample-meeting-transcript.md) | Meeting notes from a cross-functional review |

---

## Starter Prompts

### Basic Approach

```
Summarise this document in 5 bullet points, focusing on decisions and actions required.
```

### CLEAR Framework Approach

```
Context: I need to brief my direct reports on this email thread before our team standup.
This thread involves a cross-functional decision that affects our Q1 priorities.

Language: Concise, factual, action-oriented. No hedging or unnecessary caveats.

Examples: Structure as:
- Core issue or request (1 sentence)
- Key positions from each stakeholder
- Decision or action required
- Timeline and next steps

Audience: My direct reports who have no context. They need to understand 
implications for their work in under 60 seconds.

Request: Summarise in under 100 words using the structure above.
Highlight any items requiring immediate action.
```

### Meeting Transcript Variant

```
Context: I was unable to attend this meeting and need to catch up before 
a follow-up discussion tomorrow morning.

Language: Factual, neutral—capture what was said, not interpretations.

Examples: Use this structure:
1. Decisions made (with owner if mentioned)
2. Action items (owner + deadline)
3. Open questions requiring follow-up
4. Key discussion points worth noting

Audience: Me—I need to know what affects my responsibilities and any 
commitments made on my behalf.

Request: Extract all decisions, action items, and open questions.
Format as three distinct sections. Flag anything time-sensitive.
```

---

## Success Criteria

✅ Summary captures all critical information from the source  
✅ Output is immediately usable without additional editing  
✅ Length is appropriate for the audience and context  
✅ Action items and owners are clearly identified  

---

## Professional Tips

| Tip | Rationale |
|-----|-----------|
| **Specify exact length** | "5 bullets" or "under 100 words" prevents verbose outputs |
| **Name your audience** | "For the CFO" produces different results than "for the team" |
| **Request structure** | Bullet points, numbered lists, or prose—be explicit |
| **Include purpose** | Why you need the summary shapes what gets emphasised |

---

## Watch For

| Risk | Mitigation |
|------|------------|
| AI may miss implicit context | Verify against your knowledge of the situation |
| Numbers and dates may be incorrect | Always verify quantitative information |
| Nuance may be lost | Check for oversimplification of complex issues |
| Critical items may be omitted | Compare output against source for completeness |

---

## Key Technique: Purpose-Driven Extraction

> **The insight:** Summaries should be shaped by what you'll DO with them.
>
> "Summarise this" produces generic output.  
> "Summarise this so I can brief my manager in 60 seconds" produces actionable output.

**Before:** "Summarise this email thread."

**After:** "Summarise this email thread so I can brief the steering committee on the key decision needed. Focus on: what's being decided, who wants what, and what we need from them."

The same source material should produce different summaries for different purposes.

---

## Common Mistakes

| Mistake | Problem | Fix |
|---------|---------|-----|
| No length constraint | Output is too long | Add "in 5 bullets" or "under 100 words" |
| No purpose stated | Summary is generic | Add why you need it and what you'll do with it |
| Missing structure | Output is disorganised | Provide explicit structure (issue, positions, action) |
| Asking for "everything" | Important items buried | Ask for specific elements only |

---

## Debrief Questions

After completing this level, consider:

1. What percentage of the summary was immediately usable?
2. What did you need to add, remove, or correct?
3. How might you refine your prompt for better results next time?

---

**[← Back to Main Guide](../../../readme.md)** | **[Next: Level 2 →](../02-draft-rework/readme.md)**

