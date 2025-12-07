# Level 7: Excel Financial Modelling

| | |
|---|---|
| **Difficulty** | ⭐⭐ Intermediate |
| **Time** | 15–20 minutes |
| **Tool** | Microsoft 365 Copilot in Excel |
| **Skill** | Build and enhance financial models with AI assistance |

---

## Objective

Use Copilot to accelerate the creation and enhancement of financial models, templates, and analytical frameworks in Excel.

---

## Business Context

Copilot can help build model components, create dynamic formulas, and add analytical capabilities—reducing manual effort whilst maintaining rigour.

---

## Sample Materials

| File | Description |
|------|-------------|
| [sample-budget-data.csv](sample-budget-data.csv) | Budget vs actual data for modelling exercises |
| [model-requirements.md](model-requirements.md) | Sample specifications for models to build |

---

## Your Task

**Choose one track:**

**Track A:** Create a new model from requirements  
**Track B:** Enhance existing data with calculations and scenarios  
**Track C:** Build a template for recurring analysis  

---

## Starter Prompts

### Building Model Components

```
Context: I need a [model type] model for [purpose]. This will be used 
[frequency: monthly/quarterly] by [who].

Language: Clear structure, well-labelled. Follow financial modelling best practices.

Examples: Structure as:
- Inputs section (highlighted, editable)
- Calculations section (formulas, protected)
- Outputs section (summary dashboard)

Audience: [Who will use this]—they have [skill level] Excel skills.

Request: Create a [model type] model with:
- Input section for: [list key inputs]
- Calculation section that: [describe calculations]
- Output section showing: [list key outputs]

Use best practices: clear input cells, named ranges, summary at top.
```

### Scenario Analysis

```
Context: I have a model that needs scenario capability for [decision/planning].
Key variables that could change: [list 2-3 variables].

Language: Clear labelling of scenarios and assumptions.

Examples: Three scenarios:
- Base case (current assumptions)
- Upside case (optimistic)
- Downside case (pessimistic)

Audience: [Decision-makers] who need to understand range of outcomes.

Request: Add scenario analysis capability to this model:
- Base case: [current assumptions]
- Upside case: [optimistic assumptions]
- Downside case: [pessimistic assumptions]
Create a dropdown to toggle between scenarios.
```

---

## Success Criteria

✅ Model structure follows best practices  
✅ Inputs, calculations, and outputs are clearly separated  
✅ No hardcoded numbers in calculations  
✅ Model is documented and understandable  

---

## Key Technique: Describe the Logic, Not the Formula

> **The insight:** Ask for what the model should DO, not what formula to use. AI can translate business logic into Excel formulas.

**Weak:** "Create a SUMIFS formula for this data."

**Strong:** "I need to calculate total revenue by region, but only for deals that closed this quarter. Show me the formula and explain how to adapt it for different filters."

Describing the business requirement lets AI choose the right approach and explain it in context.

---

## Common Mistakes

| Mistake | Problem | Fix |
|---------|---------|-----|
| No clear input/output separation | Model becomes hard to audit | Specify "inputs section" and "outputs section" |
| Hardcoded numbers in formulas | Model breaks when assumptions change | Ask for named ranges and input cells |
| Too complex in one prompt | Model structure gets confused | Build incrementally: structure first, then calculations |
| No documentation request | Others can't understand or maintain | Ask for comments and a documentation tab |

---

## Debrief Questions

1. Could someone else use this model without explanation?
2. What would break if assumptions changed?
3. How would you improve the model structure?

---

**[← Previous: Level 6](../06-excel-analysis/readme.md)** | **[Back to Main Guide](../../../readme.md)** | **[Next: Level 8 →](../08-presentation-building/readme.md)**

