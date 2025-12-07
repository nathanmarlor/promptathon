# Level 3: Decide

| | |
|---|---|
| **Difficulty** | ⭐⭐ Intermediate |
| **Time** | 7–10 minutes |
| **Tool** | Microsoft 365 Copilot |
| **Skill** | Structure decision analysis and evaluate trade-offs |

---

## Objective

Use AI to structure complex decisions, surface trade-offs, and stress-test your thinking before committing to a course of action.

---

## Business Context

Complex decisions benefit from structured analysis. AI can accelerate option evaluation, surface trade-offs, and challenge assumptions—but the decision remains yours.

---

## Your Task

**Step 1:** Use one of the sample scenarios provided, or identify a real decision you're currently facing

**Step 2:** Use Copilot to structure your analysis

**Step 3:** Evaluate whether the AI-generated analysis adds genuine value

---

## Sample Materials

| File | Description |
|------|-------------|
| [sample-decision-scenario.md](sample-decision-scenario.md) | A vendor selection decision with full context |
| [sample-strategic-choice.md](sample-strategic-choice.md) | A market expansion decision requiring analysis |

---

## Starter Prompts

### Options Analysis

```
Context: I'm deciding between [Option A] and [Option B] for [situation].
Key constraints: [budget/timeline/resources/political considerations].
This decision needs to be made by [date].

Language: Analytical, balanced, direct. Present trade-offs fairly but don't 
hedge excessively. Give me your assessment, not just "it depends."

Examples: Structure as:
1. Comparison table (criteria as rows, options as columns)
2. Key risks for each option
3. Questions to answer before deciding
4. Recommendation with rationale

Audience: [Who will review/approve this decision].
They care most about: [priorities].

Request: For each option, provide:
- Top 3 advantages
- Top 3 disadvantages
- Key risks and mitigations
- What questions I should ask before deciding
- Your recommendation if you had to choose

Be specific to my situation, not generic.
```

### Devil's Advocate

```
Context: I'm leaning toward [decision]. Before committing, I want to 
stress-test this thinking. I may be subject to confirmation bias.

Language: Direct and challenging. Don't soften the critique or hedge.
I want genuine pushback, not diplomatic agreement.

Examples: Structure as:
1. Strongest arguments against this choice (specific, not generic)
2. What could go wrong and likely impact
3. What I might be missing or underweighting
4. Under what conditions this would be the wrong choice
5. Alternative approaches worth considering

Audience: Me—I need honest, rigorous challenge.

Request: Play devil's advocate. Argue against my preferred choice as 
strongly as possible. Assume I'm making a mistake and help me see why.

Don't qualify with "this is a good choice but..." Just argue the other side.
```

---

## Success Criteria

✅ Analysis surfaces considerations you hadn't thought of  
✅ Trade-offs are clearly articulated and genuinely balanced  
✅ Output is specific to your situation, not generic advice  
✅ You can use this analysis directly in decision discussions  

---

## Key Technique: Permission to Challenge

> **The insight:** AI is trained to be balanced and cautious. To get genuine pushback, you must explicitly request it and give permission to be direct.

**Weak:** "What are some considerations for this decision?"

**Strong:** "Play devil's advocate. Argue against my preferred option as strongly as possible. Don't soften the critique or qualify with 'this is a good choice but...' Just argue the other side."

Without explicit permission, AI will hedge. With permission, it will challenge.

---

## Common Mistakes

| Mistake | Problem | Fix |
|---------|---------|-----|
| No constraints provided | Analysis ignores real-world limits | Include budget, timeline, political factors |
| Asking for "balanced" view | Everything sounds equal | Ask for a recommendation, not just options |
| Generic decision framing | Output is generic advice | Add specific context about your situation |
| No counter-argument | Confirmation bias | Explicitly request the case against your preference |

---

## Debrief Questions

1. Did the analysis surface genuinely new considerations?
2. How would you describe the quality of the recommendation?
3. What context would have improved the output?

---

**[← Previous: Level 2](../02-draft-rework/readme.md)** | **[Back to Main Guide](../../../readme.md)** | **[Next: Level 4 →](../04-function-specific/readme.md)**

