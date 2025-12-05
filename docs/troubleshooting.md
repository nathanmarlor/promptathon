# Troubleshooting Guide

When AI gives you bad output, here's how to fix it.

---

## Quick Fixes

| Problem | CLEAR Component to Strengthen |
|---------|-------------------------------|
| **Too generic** | **Context** — add more situation details |
| **Wrong tone** | **Language** — specify tone, give examples |
| **Bad structure** | **Examples** — show the format you want |
| **Too complex/simple** | **Audience** — clarify their knowledge level |
| **Missing pieces** | **Request** — be more specific about deliverables |
| **Too long** | **Request** — add "Maximum [X] words" |
| **Missed the point** | **Context** + **Request** — restate goal explicitly |

---

## Common Problems & Solutions

### "The output is too vague"

**Why it happens:** Your prompt lacked specific context.

**Fix it:**

```
❌ "Write about our strategy"

✅ "Write a 200-word summary of our market expansion strategy. 
Focus on: the three target markets, investment required, and expected timeline. 
Audience: board members who haven't seen the full plan."
```

**Key additions:**
- Specific topic scope
- Length constraint
- Focus areas
- Audience context

---

### "It's not the right tone"

**Why it happens:** AI defaults to neutral/formal unless told otherwise.

**Fix it:**

```
❌ "Write an email to the team"

✅ "Write an email to the team.
Tone: warm but direct—like a trusted manager giving straight talk.
NOT: corporate jargon, overly formal, or vague."
```

**Tone words that work:**
- Professional but warm
- Direct but diplomatic
- Confident, not arrogant
- Casual, not sloppy
- Urgent but not alarming

---

### "It invented facts"

**Why it happens:** AI fills gaps with plausible-sounding information.

**Fix it:**
- Provide the facts you want included
- Add: "Only use information I provide—do not add external facts"
- Always verify numbers, dates, and names in the output

```
✅ "Based only on the data below, create a summary.
Do not add any statistics or claims not found in this text:
[paste your source material]"
```

---

### "The structure is messy"

**Why it happens:** You didn't specify how you wanted it organised.

**Fix it:**

```
❌ "Summarise this document"

✅ "Summarise this document with the following structure:
1. Executive summary (2 sentences)
2. Key findings (3-5 bullets)
3. Recommendations (numbered list)
4. Risks (bullet points)

Use headers for each section."
```

---

### "It's too long"

**Why it happens:** AI tends toward comprehensive responses.

**Fix it:**

Be specific about length:
- "Maximum 100 words"
- "3 bullet points only"
- "One paragraph"
- "Half a page"

```
✅ "Summarise in exactly 5 bullet points. Each bullet max 15 words."
```

**If it's still too long after:**
```
"This is too long. Cut it by 50%. 
Keep only the most essential points. 
Remove [examples/background/caveats]."
```

---

### "It didn't follow my instructions"

**Why it happens:** Instructions may have been buried or contradictory.

**Fix it:**

Put critical instructions at the START and END of your prompt:

```
✅ "IMPORTANT: Response must be under 100 words.

[Your main request here]

REMEMBER: Maximum 100 words. Do not exceed this."
```

Or use explicit formatting:

```
✅ "Instructions:
1. Keep under 100 words
2. Use bullet points
3. Focus only on financial impact
4. Tone: formal

Task: [your request]"
```

---

### "It keeps hedging and qualifying everything"

**Why it happens:** AI is trained to be cautious and balanced.

**Fix it:**

```
❌ "What should we do?"

✅ "Give me a direct recommendation. 
Don't hedge with 'it depends' or 'on the other hand.'
Pick a position and defend it.
I can handle nuance—give me your best answer."
```

---

### "The output is too basic/obvious"

**Why it happens:** AI assumed a lower knowledge level.

**Fix it:**

```
✅ "I'm an experienced [role] who knows [domain] well.
Skip the basics and 101-level explanations.
Assume I understand [X, Y, Z].
Go straight to advanced insights or non-obvious points."
```

---

## Iteration Techniques

### Build-and-Refine Method

Don't try to get it perfect in one prompt. Build iteratively:

```
PROMPT 1: Get the basic structure
"Outline the key points for [topic]"

PROMPT 2: Develop the content  
"Expand point 2 with more detail about [specific aspect]"

PROMPT 3: Refine the tone
"Rewrite the intro to sound more [confident/diplomatic/etc]"

PROMPT 4: Polish
"Tighten this up. Remove redundancy. Make every sentence count."
```

### The "What's Wrong" Technique

When output is close but not right:

```
"Good start, but here's what needs to change:
1. The second paragraph is too defensive—rewrite it to sound confident
2. You missed [key point]—add it to the first section
3. Cut the last paragraph entirely—it weakens the message

Make these three changes and show me the revised version."
```

### The "Show Me Options" Technique

When you're not sure what approach is best:

```
"Give me three different versions of this:
1. A formal version for external stakeholders
2. A casual version for internal team use
3. A very brief version (under 50 words) for chat/Slack

I'll pick the one that works best."
```

---

## When to Stop and Start Over

Sometimes iteration isn't working. Start fresh if:

- The AI seems "stuck" on a wrong interpretation
- You've iterated 4+ times without improvement
- The output keeps missing the core point

**To start fresh:**

```
"Let's start over. Ignore everything above.

Here's what I actually need:
[Rewrite your request from scratch, more clearly]"
```

---

## Know the Limits

AI is **not good at**:

| Don't Ask AI To... | Instead... |
|-------------------|------------|
| Give you accurate statistics | Provide the numbers yourself |
| Know your company's internal context | Explain the context in your prompt |
| Make decisions for you | Use it to analyse options, then decide |
| Handle highly sensitive/confidential matters | Consider what you're sharing |
| Replace professional advice (legal, medical, financial) | Consult actual professionals |

---

## Pro Tip: The Debugging Prompt

When you can't figure out why the output is wrong:

```
"The output you gave me doesn't meet my needs.
Looking at my original prompt, what parts were unclear or ambiguous?
What assumptions did you make that might have been wrong?
How would you suggest I rewrite my prompt to get better results?"
```

AI can often tell you where your prompt failed.
