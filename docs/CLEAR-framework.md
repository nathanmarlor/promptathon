# The CLEAR Framework

A practical guide to writing better AI prompts using **Context, Language, Examples, Audience, Request**.

---

## What is CLEAR?

CLEAR is a framework for crafting prompts that produce naturally adaptable, high-quality outputs. Unlike frameworks focused on technical specifications, CLEAR emphasises the *communicative* aspects of prompting — ensuring AI-generated content feels appropriate, well-targeted, and useful.

| Letter | Component | Purpose |
|:------:|-----------|---------|
| **C** | Context | Ground the AI in the right situation |
| **L** | Language | Shape the voice, tone, and vocabulary |
| **E** | Examples | Demonstrate what you want (show, don't tell) |
| **A** | Audience | Calibrate complexity and assumptions |
| **R** | Request | Focus on specific deliverables |

---

## The Five Components

### C — Context

**Establish the situation and background that grounds the AI in the right environment.**

Context answers:
- What's the situation where this content will be used?
- What relevant background should the AI know?
- What constraints or opportunities exist?
- What prompted the need for this?

**Example:**
> "I'm preparing for a quarterly business review with our largest client. The relationship has been strained recently due to delivery delays on two projects. The meeting is tomorrow and I need to strike the right tone — acknowledging issues while maintaining confidence in our partnership."

**Without context:** The AI guesses your situation (often wrong).  
**With context:** The AI tailors output to your actual circumstances.

---

### L — Language

**Specify the communication style, tone, vocabulary level, and terminology.**

Language answers:
- What tone and style should the content use?
- What vocabulary level is appropriate?
- Are there specific terms to use or avoid?
- How formal or casual should it be?

**Example:**
> "Use professional but warm language. Avoid corporate jargon ('synergies', 'leverage', 'ecosystem'). Be direct without being blunt. Acknowledge challenges honestly but frame everything constructively."

**Helpful tone specifications:**
| Tone | Description |
|------|-------------|
| Professional but warm | Competent, approachable, not stiff |
| Direct but diplomatic | Clear, not aggressive, tactful |
| Confident, not arrogant | Assured, humble enough to acknowledge limits |
| Urgent but calm | Important, not panicked |
| Casual but substantive | Relaxed, still meaningful |

---

### E — Examples

**Provide references, samples, or patterns that guide the output.**

This is the most powerful component. Showing is always better than telling.

Examples answer:
- What existing content can serve as a model?
- How should complex concepts be illustrated?
- What analogies or metaphors would work?
- What patterns should the AI follow?

**Example:**
> "Structure the response like our Q2 board report:
> - Lead with the 'so what' headline
> - Use exactly 3 supporting points  
> - Each point: assertion + evidence + implication
> - Close with a clear ask or recommendation
> 
> Do NOT use bullet points within paragraphs — keep it prose-based."

**Why examples matter so much:**
- Abstract descriptions ("make it friendly") are interpreted differently by everyone
- Concrete examples reduce misinterpretation dramatically
- The AI can pattern-match from your sample

---

### A — Audience

**Define who will receive or benefit from the content.**

Audience answers:
- Who is the primary audience?
- What's their knowledge level on this subject?
- What are their interests, needs, or concerns?
- What assumptions can you make about their background?

**Example:**
> "The audience is our executive committee — 5 people, non-technical backgrounds, very time-poor. They've heard about this project but don't know the details. They care about: financial impact, risk to reputation, and whether this affects the strategic plan. They do NOT want: technical deep-dives, historical context they already know, or hedging language."

**Audience dimensions to consider:**
| Dimension | Questions |
|-----------|-----------|
| Knowledge | What do they already know? What don't they know? |
| Concerns | What are they worried about? |
| Priorities | What do they care about most? |
| Preferences | How do they like to receive information? |
| Authority | Can they act, or do they advise others? |

---

### R — Request

**Clearly state what you want created — the specific deliverable.**

Request answers:
- What specific content do you need?
- What format should it take?
- What elements must be included?
- How will success be measured?

**Example:**
> "Create a 1-page briefing document with:
> - Executive summary (3 sentences max)
> - Situation overview (1 paragraph)
> - Options table (3 options, with pros/cons/risks)
> - Recommended action (1 paragraph)
> - Next steps (3-5 bullet points with owners)
> 
> Total length: fits on one page when printed."

**Be specific about:**
- Format (document, email, bullets, table, slides)
- Length (word count, pages, number of items)
- Structure (sections, headings, flow)
- Required elements (what MUST be included)
- Exclusions (what should NOT appear)

---

## Putting CLEAR Together

### Template

\`\`\`
Context: [situation/background]
Language: [tone/style/vocabulary]
Examples: [patterns to follow or reference]
Audience: [who this is for, what they know]
Request: [specific deliverable, format, length]
\`\`\`

### Before and After

**❌ Before CLEAR:**
> "Write an email about the project delay."

**✅ After CLEAR:**
> **Context:** Our cloud migration project will miss its March deadline by 3 weeks due to unexpected integration issues. This is the first major delay on this initiative. I need to inform the steering committee before tomorrow's standup.
> 
> **Language:** Professional and confident, but not dismissive of the issue. Acknowledge the problem directly — no burying the lead. Solution-oriented rather than defensive.
>
> **Examples:** Structure like the email Sarah sent about the Q3 budget revision — issue first, cause briefly, recovery plan, ask for support. Not like the apologetic tone we used for the vendor issue last year.
>
> **Audience:** Steering committee (CFO, CTO, COO). They've been supportive of this project but are tracking it closely. They'll want to know: how does this affect go-live? What's the budget impact? Should they be worried? They have 2 minutes to read this.
>
> **Request:** Write a 200-word email with:
> - Subject line that's direct but not alarming
> - First sentence: the key message (delay and new date)
> - Brief explanation of cause (2-3 sentences)
> - Impact assessment (timeline, budget, dependencies)
> - Recovery actions we're taking
> - Specific ask (if any) or next communication timing

---

## Common Mistakes

### 1. Skipping Examples

**Problem:** Relying on abstract descriptions ("make it professional") instead of showing what you want.

**Fix:** Include 2-4 specific examples showing format, tone, or structure.

### 2. Generic Audience Definition

**Problem:** "Write this for executives" or "for the team" without specifics.

**Fix:** Define knowledge level, concerns, preferences, and what they'll do with this content.

### 3. Vague Requests

**Problem:** "Create something good" or "write a summary" without specifying format and length.

**Fix:** Specify format, length, structure, required elements, and success criteria.

### 4. Mismatched Language and Audience

**Problem:** Requesting technical jargon for a non-technical audience (or vice versa).

**Fix:** Ensure Language and Audience components align.

### 5. Overloading with Too Many Examples

**Problem:** 10 different examples that conflict with each other.

**Fix:** Use 2-4 consistent examples that reinforce the same direction.

---

## CLEAR for Different Tasks

### Summarising
- **Context:** What's the source? Why do you need the summary?
- **Language:** Factual? Interpretive? Action-oriented?
- **Examples:** "Structure like an executive brief" or "use the Issue-Action-Impact format"
- **Audience:** Who will read it? What do they need to do with it?
- **Request:** Length, format (bullets/prose), specific elements to extract

### Drafting Communications
- **Context:** What situation prompts this message?
- **Language:** Tone, formality, words to use/avoid
- **Examples:** Reference past communications that hit the right note
- **Audience:** Recipients, their relationship to you, what they'll do with this
- **Request:** Type of message, length, sections, call to action

### Analysis & Decisions
- **Context:** The decision you're facing, constraints, timeline
- **Language:** Analytical, balanced, evaluative
- **Examples:** Frameworks to use (pros/cons, SWOT, weighted scoring)
- **Audience:** Who's deciding? What factors matter to them?
- **Request:** Options to compare, criteria to evaluate, output format

### Document Generation
- **Context:** Purpose of the document, how it will be used
- **Language:** Formal/informal, industry conventions
- **Examples:** Structure, similar documents to emulate
- **Audience:** Readers, their expectations, what they'll do with it
- **Request:** Document type, sections, page length, formatting

---

## Quick Reference

| Component | One-Line Prompt |
|-----------|-----------------|
| **Context** | "I'm [situation]. I need this because [reason]." |
| **Language** | "Use [tone] language. Avoid [terms]. Include [vocabulary]." |
| **Examples** | "Structure it like [reference]. See this sample: [example]." |
| **Audience** | "This is for [who]. They know [X] but not [Y]. They care about [Z]." |
| **Request** | "Create [format] with [elements]. Length: [constraint]. Must include: [items]." |

---

## Further Reading

- CLEAR Framework at [AiPromptsX](https://aipromptsx.com/prompts/frameworks/clear)
- Compare with other frameworks: APE, RACE, COAST
