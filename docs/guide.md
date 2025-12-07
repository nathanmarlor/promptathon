# Prompting Guide

Everything you need to know about effective AI prompting.

---

## The CLEAR Framework

A structured approach to writing prompts that produce useful outputs.

| Letter | Component | Purpose |
|:------:|-----------|---------|
| **C** | Context | Situation and background that grounds the AI |
| **L** | Language | Tone, style, and vocabulary |
| **E** | Examples | Patterns or samples to follow |
| **A** | Audience | Who this is for and what they need |
| **R** | Request | Specific deliverable, format, and length |

### Template

```
Context: [situation/background]
Language: [tone/style/vocabulary]
Examples: [patterns to follow or reference]
Audience: [who this is for, what they know]
Request: [specific deliverable, format, length]
```

### Example

**Without CLEAR:**
> "Write an email about the project delay."

**With CLEAR:**
```
Context: Our project will miss its deadline by 3 weeks due to 
vendor delays. First major delay on this initiative.

Language: Professional, confident, solution-oriented. 
Not defensive or apologetic.

Examples: Lead with the issue, brief cause, recovery plan.

Audience: Steering committee (non-technical). They want: 
impact, timeline, risk. Not: technical details.

Request: 200-word email with direct subject line, key message 
first, and clear next steps.
```

---

## Key Techniques

### 1. Purpose-Driven Prompting
Outputs should be shaped by what you'll DO with them.

**Weak:** "Summarise this email thread."

**Strong:** "Summarise this so I can brief my manager in 60 seconds. Focus on: what's being decided, who wants what, what we need from them."

---

### 2. Iterative Refinement
Don't try to get everything right in one prompt. Build incrementally.

```
Prompt 1: "Draft an email about the deadline change"
Prompt 2: "Make it shorter and more direct"
Prompt 3: "The tone is too apologetic—make it confident"
```

Simple prompts iterated 2-3 times usually beat overloaded single prompts.

---

### 3. Permission to Challenge
AI is trained to be balanced. For genuine pushback, give explicit permission.

**Weak:** "What are the considerations for this decision?"

**Strong:** "Play devil's advocate. Argue against my preferred option as strongly as possible. Don't hedge or soften the critique."

---

### 4. Show Don't Tell
Abstract descriptions ("make it professional") are interpreted differently by everyone. Concrete examples are followed more reliably.

**Weak:** "Make it more formal."

**Strong:** "Structure like our Q2 board report—headline first, three supporting points, each with evidence, then a recommendation."

---

### 5. Question-Led Analysis
Don't ask AI to "analyse this data." Ask it to answer specific business questions.

**Weak:** "Analyse this sales data."

**Strong:** "What's causing the revenue decline in the South region? Compare to other regions and identify the top 3 factors."

---

## Fixing Common Problems

| If output is... | Strengthen... | By adding... |
|-----------------|---------------|--------------|
| Too generic | **Context** | More situation details |
| Wrong tone | **Language** | Specific tone + example |
| Poor structure | **Examples** | Sample format to follow |
| Too complex/simple | **Audience** | Their knowledge level |
| Missing elements | **Request** | Specific requirements |

### Iteration Phrases

When output needs work:

- "Good start, but make it [shorter/more direct/less formal]"
- "Keep [X], but rewrite [Y] to focus on [Z]"
- "The tone is [issue]. Make it [desired tone]"
- "Add [missing element] to the [beginning/end]"

---

## When to Use AI (and When Not To)

### Good Uses

| Task | Why AI Helps |
|------|--------------|
| First drafts | Faster to edit than create from scratch |
| Summarising | AI excels at extraction and synthesis |
| Structuring thinking | Turns rough ideas into organised frameworks |
| Exploring options | Rapid generation of alternatives |
| Checking blind spots | "What am I missing?" surfaces overlooked angles |

### Poor Uses

| Task | Why It's Risky |
|------|----------------|
| Decisions requiring judgement | You're accountable; AI provides input, not answers |
| Confidential matters | Check data policies before uploading |
| Verified facts | AI may invent plausible-sounding information |
| Legal/compliance conclusions | AI doesn't understand your specific obligations |

---

## Calibrating Trust

### High Trust (light review)
- Formatting and structure
- Grammar and clarity improvements
- Brainstorming and ideation

### Medium Trust (verify key points)
- Summaries of content you provided
- Analysis of data you uploaded
- Draft communications

### Low Trust (use as input only)
- Strategic recommendations
- Numerical calculations
- External facts and statistics

---

## Spotting Problems

**Red flags in AI output:**
- Specific numbers you didn't provide (likely invented)
- Confident claims about things it couldn't know
- Generic advice that could apply to anyone
- Missing key context you expected

**Always verify:** Numbers, dates, names, facts, quotes

---

## The 80/20 Rule

Expect AI to get you 80% of the way:

- **First drafts:** Usually need tone and specificity adjustments
- **Summaries:** Usually need verification of key facts
- **Analysis:** Usually need validation of assumptions
- **Documents:** Usually need brand/style alignment

Budget time for the 20% that requires your input.

---

## Common Mistakes

| Mistake | Fix |
|---------|-----|
| Over-trusting output | Always scan before using, especially facts and tone |
| Under-investing in context | 30 seconds of context saves 5 minutes of editing |
| One-and-done prompting | Plan for 2-3 iterations as normal |
| Using AI for wrong tasks | Be intentional about what you delegate |

---

## Claude vs Copilot

| Capability | Copilot (M365) | Claude |
|------------|----------------|--------|
| Access your M365 data | ✅ Native | ❌ Upload required |
| Create downloadable docs | Limited | ✅ Word, Excel, PowerPoint |
| Analyse uploaded files | Basic | ✅ Advanced + visualisations |
| Multi-step reasoning | Limited | ✅ Complex workflows |

**Use Copilot for:** Quick tasks on content you already have in M365

**Use Claude for:** Complex analysis, document generation, multi-step work

---

## Getting Value Quickly

### This Week
1. Summarise a long document or email thread
2. Draft a routine communication
3. Structure a decision you're facing

### This Month
1. Start every first draft with AI assistance
2. Use AI to prepare for important meetings
3. Build 3-5 go-to prompts for recurring tasks

### Ongoing
1. Save effective prompts for reuse
2. Share patterns with your team
3. Expand to more complex applications as you build calibration

