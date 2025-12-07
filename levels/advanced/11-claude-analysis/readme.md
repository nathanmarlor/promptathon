# Level 11: Claude Data Analysis & Visualisation

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐ Advanced |
| **Time** | 20–25 minutes |
| **Tool** | Claude ([claude.ai](https://claude.ai)) |
| **Skill** | Upload data for analysis, pattern recognition, and visualisation |

---

## Objective

Use Claude to analyse uploaded data files, identify patterns, generate insights, and create visualisations—capabilities that extend beyond Copilot's in-app functions.

---

## Business Context

Claude can accept file uploads (CSV, Excel, PDF) and perform sophisticated analysis including pattern detection, anomaly identification, and chart generation with downloadable outputs.

---

## Prerequisites

- Access to Claude at [claude.ai](https://claude.ai)
- A data file to analyse (samples provided)

---

## Sample Materials

| File | Description |
|------|-------------|
| [sample-analysis-data.csv](sample-analysis-data.csv) | Multi-dimensional business data for analysis |
| [sample-survey-results.csv](sample-survey-results.csv) | Employee survey data with sentiment patterns |
| [analysis-prompts.md](analysis-prompts.md) | Detailed prompts for different analysis types |

---

## Your Task

**Step 1:** Upload a dataset to Claude

**Step 2:** Ask Claude to explore and summarise the data

**Step 3:** Request specific analyses and visualisations

**Step 4:** Export findings in a usable format

---

## Starter Prompts

### Initial Exploration

A simple prompt to get oriented before detailed analysis:

```
I've uploaded [data description]. Before I ask specific questions:

1. Describe the structure of this data
2. Summarise key statistics
3. Identify any data quality issues
4. Suggest 3-5 questions this data could answer
```

Use the CLEAR framework (below) when you need specific, actionable analysis.

### CLEAR Framework for Analysis

```
Context: I've uploaded [data type] covering [scope].
I need findings for [meeting/report/decision].
Key question: [what you want to answer]

Language: Business-focused insights, not statistics.
Lead with implications.

Examples: Present findings like:
"[Metric] increased 23% driven by [factor]"

Audience: [Who]. They want actionable insights.

Request:
1. Key trends (5 bullets max)
2. Anomalies to investigate
3. Visualisation showing [comparison]
4. 2-3 recommended focus areas
```

---

## Key Technique: Framing Before Uploading

> **The insight:** Tell Claude what kind of analysis you need BEFORE uploading data. This shapes how it approaches the file.

**Weak:** [Upload data] "Analyse this."

**Strong:** "I'm going to upload our Q3 sales data. I need to find what's driving the revenue decline in the South region for a board presentation tomorrow. Focus on regional comparisons and product mix. Flag anything that would concern a CFO." [Then upload]

The framing primes Claude to look for what matters rather than producing a generic summary.

---

## Common Mistakes

| Mistake | Problem | Fix |
|---------|---------|-----|
| Upload without context | Generic analysis | Explain purpose before uploading |
| Trusting statistics blindly | AI may miscalculate | Verify key numbers manually |
| Accepting first output | Missing depth | Ask "what else should I investigate?" |
| No action orientation | Just observations | Ask "what should we do about this?" |

---

## Success Criteria

✅ Analysis answers your starting questions  
✅ Insights are specific, not generic  
✅ Visualisations communicate clearly  
✅ Findings suggest action  

---

**[← Previous: Level 10](../../intermediate/10-automation-templates/readme.md)** | **[Back to Main Guide](../../../readme.md)** | **[Next: Level 12 →](../12-document-generation/readme.md)**

