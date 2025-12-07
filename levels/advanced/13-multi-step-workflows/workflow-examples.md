# Multi-Step Workflow Examples

Complete workflow patterns to practice with Claude.

---

## Workflow 1: Competitive Analysis

**Input:** Company documents + competitor materials  
**Output:** Strategic brief with recommendations

### Step 1: Extraction

```
I've uploaded three documents:
1. Our product roadmap
2. Competitor A's recent announcements
3. Competitor B's investor materials

Extract from each:
- Key capabilities and features
- Strategic priorities (stated or implied)
- Target markets and positioning
- Recent investments or focus areas

Format as a structured summary for each source.
```

### Step 2: Comparison

```
Using the extracted information, create a comparison matrix:
- Rows: Key capability areas
- Columns: Us, Competitor A, Competitor B
- Rating: Strong / Moderate / Weak / Absent

Identify where we lead, match, and trail.
```

### Step 3: Gap Analysis

```
Based on the comparison:
- What capabilities do competitors have that we lack?
- Rate each gap: customer impact, difficulty to close, urgency
- Which gaps are strategic threats vs nice-to-have?
```

### Step 4: Synthesis

```
Produce a 2-page executive brief:
- Our competitive position (1 paragraph)
- Key strengths to leverage (3 bullets)
- Critical gaps to address (3 bullets, prioritised)
- Recommended actions
- Questions for further investigation
```

---

## Workflow 2: Customer Feedback Synthesis

**Input:** Support tickets + Survey responses + Product backlog  
**Output:** Prioritised improvement recommendations

### Step 1: Categorisation

```
I've uploaded customer feedback data.

Categorise all items by:
- Theme (auto-detect logical groupings)
- Sentiment (positive/negative/neutral)
- Urgency implied
- Customer segment (if identifiable)

Show distribution across themes.
```

### Step 2: Pattern Analysis

```
For each major theme:
- Count of mentions
- Representative quotes (2-3 per theme)
- Trend over time (if dates available)
- Correlation with customer segment

Identify top 5 themes by frequency and severity.
```

### Step 3: Cross-Reference

```
Compare themes against our product backlog:
- What's already planned?
- What's missing from the roadmap?
- Where are we addressing symptoms vs root causes?
```

### Step 4: Prioritisation

```
Create prioritised recommendation list:
- Issue/theme
- Impact (high/medium/low)
- Effort to address (high/medium/low)
- Recommended action
- Suggested owner
```

### Step 5: Deliverable

```
Produce a customer insights report:
- Executive summary
- Methodology note
- Top findings with evidence (quotes)
- Prioritised recommendations
- Appendix: full theme breakdown
```

---

## Workflow 3: Strategic Input Synthesis

**Input:** Multiple stakeholder inputs and research  
**Output:** Strategy discussion document

### Step 1: Inventory

```
I'm uploading multiple documents representing inputs to our strategy.

For each document, extract:
- Source/author
- Key themes raised
- Specific recommendations
- Data points cited

Summarise each in 3-5 bullets.
```

### Step 2: Consolidation

```
Across all inputs, identify:
- Areas of consensus (multiple sources agree)
- Areas of disagreement (conflicting views)
- Gaps (important topics not addressed)
- Outlier views (single source only)
```

### Step 3: Tension Mapping

```
Where disagreements exist:
- Nature of the disagreement
- Underlying assumption difference
- What would resolve it (data, discussion, decision)
```

### Step 4: Question Framework

```
Based on this synthesis, what strategic questions need answers?

For each question:
- Why it matters
- What inputs would help answer it
- Proposed approach to resolution
```

### Step 5: Discussion Document

```
Create a document for the strategy session:
- Summary of inputs received
- Areas of alignment
- Key tensions requiring discussion
- Framework questions to address
- Suggested session agenda
```

---

## Tips for Multi-Step Workflows

1. **Narrate each step:** "Now completing Step 2..." keeps Claude on track
2. **Review before proceeding:** Catch errors before they compound
3. **Save intermediate outputs:** Useful for restart or branching
4. **Be explicit about connections:** "Using the output from Step 2..."

