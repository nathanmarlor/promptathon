# Template Design Guide

How to create effective, reusable prompt templates.

---

## Why Templates?

Templates work because:
- Recurring tasks have consistent structure
- Good prompts take iteration to develop
- Reuse saves that iteration time
- Consistency improves quality

---

## Template Design Process

### 1. Identify the Task

Ask:
- What task do I do repeatedly?
- How often? (Weekly, monthly, triggered by event?)
- How long does it take manually?
- Is quality variable? (Templates help consistency)

**Good candidates:**
- Weekly status reports
- Meeting summaries
- Document reviews
- Email responses
- Analysis patterns

### 2. Define Inputs and Outputs

**Inputs:** What varies each time?
- Content (data, text, context)
- Parameters (audience, length, tone)

**Outputs:** What should be produced?
- Format (email, document, bullets)
- Length (word count, page count)
- Structure (sections, order)

### 3. Write the Template

**Fixed elements:** Same every time
- Structure requirements
- Tone specifications
- Format expectations

**Variable elements:** Change each use
- Use {PLACEHOLDER} notation
- Be clear what goes in each placeholder

### 4. Test and Refine

- Run with 3-5 different inputs
- Check output quality
- Identify where it fails
- Refine prompt until consistent

---

## Template Structure

```
TEMPLATE: [Name]
VERSION: [Date]

PURPOSE:
[What this template produces]

TRIGGER:
[When to use this template]

INPUTS REQUIRED:
- {INPUT_1}: [what this is]
- {INPUT_2}: [what this is]

PROMPT:
---
Context: [Fixed context + {variables}]

Language: [Fixed tone/style requirements]

Examples: [Fixed structure expectations]

Audience: [{VARIABLE} or fixed audience]

Request: [Fixed deliverable specification]
---

QUALITY CHECKLIST:
- [ ] [Check 1]
- [ ] [Check 2]

KNOWN LIMITATIONS:
- [What this doesn't handle well]

TIPS:
- [Advice for getting best results]
```

---

## Best Practices

### Be Specific About Structure

```
❌ "Summarise this meeting"

✅ "Summarise this meeting as:
1. DECISIONS (numbered)
2. ACTIONS (with owners)
3. OPEN ITEMS"
```

### Include Quality Criteria

```
Request: Create summary that:
- Is under 200 words
- Has owner for every action
- Flags any decisions made
```

### Handle Edge Cases

```
NOTES:
- If no blockers, say "None" not blank
- If deadline unknown, say "TBD (to clarify with [person])"
```

### Version Your Templates

Templates improve over time. Track versions:
- v1.0: Initial version
- v1.1: Added structure for risks section
- v2.0: Major revision after testing

---

## Template Library Organisation

Organise templates by:
- Frequency (daily/weekly/monthly)
- Type (communication/analysis/documentation)
- Function (sales/ops/finance)

```
MY TEMPLATES/
├── Weekly/
│   ├── status-report.md
│   └── team-meeting-agenda.md
├── Communications/
│   ├── complaint-response.md
│   └── announcement.md
└── Analysis/
    ├── decision-documentation.md
    └── options-analysis.md
```

---

## Measuring Template Value

Track:
- Time saved per use
- Number of uses per week/month
- Quality consistency
- Editing required after generation

**If a template needs heavy editing every time, improve it.**

