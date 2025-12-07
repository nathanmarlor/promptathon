# Analysis Prompt Library for Claude

Detailed prompts for different analysis scenarios.

---

## Business Performance Analysis

```
Context: I've uploaded business performance data covering [time period].
I'm preparing for [meeting type] and need to identify key trends and issues.

Language: Business-focused insights. Lead with implications, not methodology.
Frame findings as "X means we should consider Y."

Examples: Structure findings like:
- "[Region/Product] outperformed by [X%] driven by [factor]"
- "[Metric] declined in [segment], indicating [implication]"

Audience: [Leadership level]. They want actionable insights and 
care about: revenue, margin, growth trajectory.

Request:
1. Summary of overall performance (3-4 key metrics)
2. Best and worst performers by [dimension]
3. Trends over the time period
4. Anomalies or concerns to investigate
5. 3 recommended focus areas with rationale

Create:
- Summary table comparing key metrics
- Trend chart showing performance over time
- Comparison chart by [dimension]
```

---

## Survey/Feedback Analysis

```
Context: I've uploaded employee/customer survey results with [N] responses.
I need to identify themes, concerns, and recommended actions.

Language: Objective about findings, constructive about implications.
Quote actual feedback where it illustrates a point.

Examples: Structure as:
- Theme name
- Frequency/severity
- Representative quotes (2-3)
- Potential root cause
- Recommended action

Audience: [Leadership/HR/Product team] who need to prioritise actions.

Request:
1. Overall satisfaction/sentiment summary
2. Top 5 positive themes (what's working)
3. Top 5 negative themes (what needs attention)
4. Segment analysis (are some groups more/less satisfied?)
5. Correlation analysis (what factors predict satisfaction?)
6. Prioritised recommendations (impact vs effort)

Create visualisations showing:
- Score distribution
- Theme frequency
- Segment comparison
```

---

## Comparative Analysis

```
Context: I need to compare [Group A] vs [Group B] in this data.
The purpose is to understand differences and inform [decision/strategy].

Language: Analytical, balanced. Quantify differences clearly.

Request:
1. Summary statistics for each group
2. Key differences (quantified)
3. Statistical significance of differences (if applicable)
4. Patterns unique to each group
5. Implications: what does this tell us?

Create:
- Side-by-side comparison table
- Visual showing the key differences
```

---

## Anomaly Detection

```
Context: I want to identify anomalies, outliers, and unexpected patterns
in this data that warrant investigation.

Language: Factual about findings, suggestive about causes.

Request:
1. Identify values that deviate significantly from norms
2. Detect sudden changes or trend breaks
3. Find patterns that don't fit expected behaviour
4. For each anomaly:
   - What's unusual (quantified)
   - Possible explanations
   - Recommended investigation

Create:
- Highlight anomalies in context
- Chart showing normal range vs outliers
```

---

## Predictive/Trend Analysis

```
Context: Based on historical data in this file, I want to understand
trends and potential future direction.

Language: Clear about what's historical vs projected.
Acknowledge uncertainty in predictions.

Request:
1. Historical trend analysis (direction, rate of change)
2. Seasonality or cyclical patterns
3. Projection for next [period] (with confidence range)
4. Key assumptions underlying the projection
5. Factors that could change the trajectory

Create:
- Trend chart with historical and projected values
- Confidence interval visualisation
```

---

## Tips for Data Analysis with Claude

1. **Describe your data context** — Claude performs better when it understands business meaning, not just columns
2. **State your questions upfront** — "I want to know X" focuses the analysis
3. **Request specific visualisations** — "Bar chart comparing X by Y" is better than "show me a chart"
4. **Ask for the "so what"** — Request implications and recommendations, not just observations
5. **Verify surprising findings** — Ask Claude to double-check unusual results

