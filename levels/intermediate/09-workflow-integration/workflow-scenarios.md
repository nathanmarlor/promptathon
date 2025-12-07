# Workflow Scenarios

Practice these end-to-end workflows using Copilot across multiple applications.

---

## Workflow 1: Monthly Business Review

**End deliverable:** Executive presentation with supporting analysis

### Step 1: Data Gathering (Excel)

```
Input: Monthly metrics export

Prompt: "Analyse this month's performance data. Calculate:
- Variance to budget for all KPIs
- Month-over-month trend
- Top 3 positive and negative variances
- Create summary table with traffic light indicators"
```

### Step 2: Insight Development (Word)

```
Input: Excel analysis output

Prompt: "Using this data analysis, write a 1-page executive narrative:
- Overall performance assessment (1 paragraph)
- Key highlights and concerns (2-3 paragraphs)
- Actions underway (1 paragraph)
- Outlook (1 paragraph)

Tone: Confident, factual, solution-oriented"
```

### Step 3: Presentation Creation (PowerPoint)

```
Input: Word narrative + Excel visuals

Prompt: "Create a 6-slide monthly review presentation:
1. Performance headline
2. KPI dashboard (use data from Excel)
3. Key wins
4. Areas of focus
5. Actions and owners
6. Outlook

Include the Word narrative in speaker notes."
```

### Step 4: Distribution (Outlook)

```
Prompt: "Draft an email to the leadership team sharing the monthly review.
Highlight the 3 things they most need to know.
Attach the presentation and offer to discuss."
```

---

## Workflow 2: Meeting Preparation

**End deliverable:** Briefing document and agenda

### Step 1: Communication Review (Outlook/Teams)

```
Prompt: "Summarise all communications with [stakeholder/client] in the 
past 30 days. Include:
- Key topics discussed
- Commitments made (by either party)
- Outstanding questions
- Tone of recent exchanges"
```

### Step 2: Background Research (Word)

```
Input: Communication summary

Prompt: "Create a briefing document for my meeting with [stakeholder]:
- Relationship status summary
- Key issues to address
- Likely concerns they'll raise
- Recommended talking points
- Questions I should ask"
```

### Step 3: Agenda Creation (Word/Outlook)

```
Prompt: "Create a meeting agenda that:
- Opens with relationship acknowledgment
- Addresses priority issues in logical order
- Includes time allocations (30-minute meeting)
- Ends with clear next steps
Format for sending to the attendee"
```

---

## Workflow 3: Report from Data

**End deliverable:** Board-ready report document

### Step 1: Data Analysis (Excel)

```
Input: Raw data export

Prompt: "Analyse this data and identify:
- Summary statistics for each category
- Top/bottom performers
- Trend over time
- Anomalies or outliers
Export key findings as a summary."
```

### Step 2: Narrative Writing (Word)

```
Input: Excel summary

Prompt: "Create a board report section covering this analysis:
- Key finding headline
- Supporting data (reference the numbers)
- Implication (so what does this mean)
- Recommendation (what should we do)

Format: Professional, suitable for board papers"
```

### Step 3: Visualisation (Excel → Word)

```
Prompt: "Create appropriate charts for this data:
- Trend chart for performance over time
- Comparison chart for categories
Format for insertion into Word document"
```

---

## Workflow Template

Use this structure to design your own workflows:

```
WORKFLOW: [Name]
PURPOSE: [What deliverable and why]

STEP 1: [Name]
- Application: [Which M365 app]
- Input: [What you start with]
- Prompt: [What you ask Copilot]
- Output: [What you use in next step]

STEP 2: [Name]
- Application: [Which M365 app]
- Input: [Output from previous step]
- Prompt: [What you ask Copilot]
- Output: [What you use in next step]

[Continue as needed]

FINAL OUTPUT: [Description of deliverable]
```

