# Level 14: Custom Skill Development

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐⭐ Advanced |
| **Time** | 25–30 minutes |
| **Tool** | Claude ([claude.ai](https://claude.ai)) |
| **Skill** | Design reusable AI capabilities for specific use cases |

---

## Objective

Create custom "skills"—structured prompt frameworks that configure Claude for specialised, repeatable tasks relevant to your work.

---

## Business Context

A custom skill is a detailed instruction set that configures Claude to behave like a specialist for a particular task type. Once developed, skills can be reused and shared.

---

## Sample Materials

| File | Description |
|------|-------------|
| [skill-examples.md](skill-examples.md) | Complete skill definitions to learn from |
| [skill-template.md](skill-template.md) | Template for designing your own skills |

---

## Your Task

**Step 1:** Identify a recurring task suitable for skill development

**Step 2:** Design the skill specification

**Step 3:** Test the skill with a real example

**Step 4:** Refine based on output quality

**Step 5:** Document for reuse

---

## Skill Architecture

```
1. PURPOSE: What task does this perform?
2. PERSONA: What expertise should Claude embody?
3. INPUTS: What information is required?
4. PROCESS: What steps should Claude follow?
5. OUTPUTS: What deliverable is produced?
6. QUALITY: What makes output "good"?
7. GUARDRAILS: What should it NOT do?
```

---

## Key Technique: Persona + Process + Guardrails

> **The insight:** Effective skills combine three elements: who Claude should be, what it should do, and what it should avoid.

**Weak skill:** "Help me write executive summaries."

**Strong skill:**
```
PERSONA: You are a management consultant who writes for time-poor 
executives. You know they want bottom-line-up-front and care about 
implications, not methodology.

PROCESS: When given content, you (1) extract the 3-5 most important 
points, (2) identify the "so what," (3) structure as headline + 
bullets + recommendation.

GUARDRAILS: Never exceed one page. Never include caveats that dilute 
the message. Always surface what decision is needed.
```

The combination produces consistent, high-quality output across different inputs.

---

## Common Mistakes

| Mistake | Problem | Fix |
|---------|---------|-----|
| No persona defined | Generic voice | Describe expertise and perspective |
| Vague process | Inconsistent output | Specify steps explicitly |
| No guardrails | Unpredictable failures | Define what NOT to do |
| Over-complicated skill | Hard to use | Keep to essential elements |

---

## Success Criteria

✅ Skill produces consistent, quality output  
✅ Different inputs yield appropriately different outputs  
✅ Quality standards are met reliably  
✅ Skill is reusable without modification  

---

**[← Previous: Level 13](../13-multi-step-workflows/readme.md)** | **[Back to Main Guide](../../../readme.md)** | **[Next: Level 15 →](../15-strategic-synthesis/readme.md)**

