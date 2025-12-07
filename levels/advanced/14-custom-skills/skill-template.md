# Custom Skill Design Template

Use this template to create your own custom skills.

---

## Skill Definition

```
SKILL: [Name]

PURPOSE:
[What task does this skill perform?]
[When should it be used?]

PERSONA:
[What expertise should Claude embody?]
[What perspective should it take?]
[What does it understand about the task domain?]

INPUTS REQUIRED:
- [Input 1]: [Description and format]
- [Input 2]: [Description and format]
- [Input 3]: [Description and format]

PROCESS:
1. [First step]
2. [Second step]
3. [Third step]
4. [Continue as needed]

OUTPUT:
[Format description]
[Structure/sections]
[Length constraints]
[Required elements]

QUALITY STANDARDS:
- [Standard 1]
- [Standard 2]
- [Standard 3]

GUARDRAILS:
- Do not: [Prohibited action 1]
- Do not: [Prohibited action 2]
- Always: [Required behaviour]

---
USAGE: [Instructions for using this skill]
```

---

## Design Process

### Step 1: Identify the Task

Answer these questions:
- What task do I do repeatedly?
- How often does it occur?
- How long does it take manually?
- What does "good" output look like?
- Who else might use this skill?

### Step 2: Define the Persona

Consider:
- What expertise is needed for this task?
- What perspective should Claude take?
- What should Claude understand about the domain?
- What communication style is appropriate?

### Step 3: Specify Inputs and Outputs

For inputs:
- What information is absolutely required?
- What format should inputs be in?
- What context is needed?

For outputs:
- What deliverable is produced?
- What format and structure?
- What length or scope?
- What elements must be included?

### Step 4: Define Quality and Guardrails

Quality criteria:
- How do you know the output is good?
- What would cause you to reject output?
- What does success look like?

Guardrails:
- What should the skill never do?
- What limitations should it acknowledge?
- What should trigger escalation or warning?

### Step 5: Test and Refine

- Test with 3-5 different inputs
- Check output quality against standards
- Identify failure modes
- Refine until consistent

---

## Skill Documentation

Once your skill works, document it:

```markdown
# Skill: [Name]

## What It Does
[1-2 sentence description]

## When to Use
[Triggering situations]

## How to Use
1. [Step 1]
2. [Step 2]
3. [Step 3]

## Example
[Sample input and output]

## Tips
- [Tip 1]
- [Tip 2]

## Limitations
- [What it doesn't handle well]
```

---

## Skill Ideas to Consider

- **Document type generators:** Board papers, proposals, reports
- **Analysis frameworks:** Decision analysis, risk assessment, comparison
- **Communication preparers:** Meeting prep, feedback scripts, difficult conversations
- **Review assistants:** Proposal review, document critique, policy check
- **Synthesis tools:** Research summary, feedback analysis, input consolidation

