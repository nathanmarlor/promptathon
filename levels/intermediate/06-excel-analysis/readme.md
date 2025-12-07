# Level 6: Excel Data Analysis

| | |
|---|---|
| **Difficulty** | ⭐⭐ Intermediate |
| **Time** | 15–20 minutes |
| **Tool** | Microsoft 365 Copilot in Excel |
| **Skill** | Data analysis and insight generation |

---

## Objective

Use Copilot within Excel to analyse data, identify patterns, and generate business insights without writing complex formulas.

---

## Business Context

Copilot in Excel can summarise datasets, answer questions about data, create formulas, and highlight trends—enabling faster analysis without requiring deep Excel expertise.

---

## Prerequisites

- Microsoft 365 Copilot with Excel integration
- Data formatted as a table in Excel (Ctrl+T to convert)

---

## Sample Data

This folder includes sample data files you can use:

| File | Description |
|------|-------------|
| [sample-sales-data.csv](sample-sales-data.csv) | 6 months of sales transactions with regions and products |
| [sample-customer-data.csv](sample-customer-data.csv) | Customer satisfaction scores and engagement metrics |

**To use:** Open the CSV in Excel, select the data, and press Ctrl+T to convert to a table.

---

## Your Task

**Step 1:** Open an Excel workbook with the sample data or your own

**Step 2:** Convert your data to a Table (Ctrl+T)

**Step 3:** Use Copilot to analyse the data and surface insights

**Step 4:** Create visualisations and summaries

---

## Starter Prompts

### Data Exploration

A simple prompt to get oriented:

```
Analyse this data and tell me:
- What are the key trends?
- Are there anomalies or outliers to investigate?
- What are the top 5 insights a business leader would want to know?

Focus on patterns that suggest action, not just description.
```

### Specific Analysis

```
Context: I need to compare performance across [column: Region/Product/Team] 
for [purpose: a leadership review/board presentation/planning session].

Language: Comparative, focused on differences that matter.

Examples: Structure as:
- Top performers (and why)
- Bottom performers (and potential causes)
- Trends over time
- Recommended actions

Audience: [Business leaders] who want actionable insight, not raw data.

Request: Compare performance across [column name]. Show me:
- Which is performing best and worst
- The gap between top and bottom performers
- Notable trends over time
- What this suggests we should do
```

### Formula Generation

```
Create a formula that calculates [specific metric].
Explain what it does and how to use it.
```

Examples:
- "Calculate year-over-year growth percentage for each row"
- "Add a column showing running total of revenue"
- "Calculate what percentage each region contributes to the total"

---

## Success Criteria

✅ Analysis surfaces actionable insights  
✅ Key patterns and anomalies are identified  
✅ Findings connect to business implications  
✅ Visualisations communicate the story clearly  

---

## Key Technique: Question-Led Exploration

> **The insight:** Don't ask AI to "analyse this data." Ask it to answer specific business questions. The question shapes the analysis.

**Weak:** "Analyse this sales data."

**Strong:** "What's causing the revenue decline in the South region? Compare to other regions and identify the top 3 factors."

The question focuses the analysis on what matters rather than producing a generic overview.

---

## Common Mistakes

| Mistake | Problem | Fix |
|---------|---------|-----|
| Data not in table format | Copilot can't engage | Convert to table with Ctrl+T |
| Asking "analyse this" | Output is generic summary | Ask specific questions instead |
| Not verifying numbers | AI may miscalculate | Spot-check key figures manually |
| Accepting first insight | Missing deeper patterns | Ask follow-up questions |

---

## Debrief Questions

1. Did Copilot identify insights you might have missed?
2. How much faster was this than manual analysis?
3. What did you need to verify or correct?

---

**[← Previous: Level 5](../../foundation/05-share-refine/readme.md)** | **[Back to Main Guide](../../../readme.md)** | **[Next: Level 7 →](../07-excel-modelling/readme.md)**

