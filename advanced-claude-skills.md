# Advanced: Claude Skills & Capabilities

For Levels 6-9, Claude provides capabilities beyond basic chat: file creation, data analysis, document generation, and multi-step workflows.

---

## What Makes Claude Different?

| Capability | Copilot (M365) | Claude |
|------------|----------------|--------|
| Access your M365 data | ✅ Native | ❌ Upload required |
| Create downloadable docs | Limited | ✅ Word, Excel, PowerPoint, PDF |
| Analyse uploaded data | Basic | ✅ Advanced + visualisations |
| Multi-step reasoning | Limited | ✅ Complex workflows |
| Custom file generation | ❌ | ✅ Any format |

**Use Copilot for:** Quick tasks on M365 content you already have  
**Use Claude for:** Complex analysis, document creation, multi-step workflows

---

## File Types Claude Can Create

| Type | Extension | Example Use |
|------|-----------|-------------|
| Word Document | `.docx` | Reports, briefs, proposals |
| PowerPoint | `.pptx` | Presentations, pitch decks |
| Excel | `.xlsx` | Templates, analysis, dashboards |
| PDF | `.pdf` | Formatted reports, forms |
| CSV | `.csv` | Data exports, imports |
| Markdown | `.md` | Documentation, notes |

---

## CLEAR Prompts for Advanced Tasks

### Data Analysis (Level 6)

```
Context: I've uploaded our Q3 sales data (CSV). I need to present 
key findings to the leadership team tomorrow. The data includes 
region, product line, revenue, and units sold.

Language: Business-friendly insights. Explain significance in 
plain terms, not statistical jargon. Lead with "so what" implications.

Examples: Present findings like:
- "Region X outperformed by 23%, driven primarily by Product A"
- NOT: "Mean revenue for Region X was 1.23 standard deviations above..."

Audience: Senior leaders who want actionable insights. They care 
about: which regions/products to focus on, where to investigate 
problems, quick wins vs strategic shifts.

Request:
1. Summarise key trends (5 bullet points max)
2. Create a bar chart comparing revenue by region
3. Identify the top 3 issues or opportunities
4. Recommend 2-3 focus areas for next quarter
5. Export as a 1-page summary I can print
```

### Document Generation (Level 7)

```
Context: I'm presenting our 2025 strategy to the all-hands meeting 
next week. We have 4 strategic pillars and initiatives under each.

Language: Inspiring but grounded. Confident without overpromising. 
Minimal text per slide — visuals and headlines, not paragraphs.

Examples: Follow "assertion-evidence" slide format:
- One key message as the headline
- Supporting evidence below (visual, 3 bullets max, or data point)
- No full sentences in bullet points

Audience: All 200 employees, mixed technical and non-technical. 
They want to know: where we're going, how it affects them, 
what they should do differently.

Request: Create a 10-slide PowerPoint:
1. Title slide
2. "Why change" context slide
3-6. One slide per strategic pillar (4 slides)
7. Key milestones timeline
8. "What this means for you" slide
9. Q&A
Include speaker notes for each slide.
```

### Multi-Step Workflow (Level 8)

```
Context: I've uploaded three files:
1. Our product roadmap (internal doc)
2. Competitor A's recent press releases
3. Competitor B's investor presentation

I need to understand competitive positioning for a strategy session.

Language: Strategic and analytical. Use frameworks like 
"threat/opportunity" rather than feature lists. Be direct 
about weaknesses.

Examples: Structure like a strategy consulting deliverable:
- Comparison matrix
- Capability gaps with severity rating
- Strategic implications
- Recommended actions

Audience: Executive team making investment decisions. They want 
the "so what" — what should we do? — not just the analysis.

Request: Complete this workflow in order:
Step 1: Extract key capabilities from each document
Step 2: Create a comparison matrix (table)
Step 3: Identify our unique strengths
Step 4: Identify gaps (what they have, we don't)
Step 5: Rate gaps by urgency (high/medium/low)
Step 6: Produce a 2-page executive brief with recommendations

Show your working at each step before proceeding.
```

### Custom Template (Level 9)

```
Context: I evaluate partnerships regularly but lack a consistent 
framework. Important factors: strategic fit, financial terms, 
operational complexity, and risk.

Language: Structured and evaluative. Use scoring (1-5) with 
clear definitions.

Examples: Similar to a due diligence checklist or RFP scoring matrix.
Each criterion should have:
- Description
- Scoring rubric (what 1 vs 5 looks like)
- Weight (importance)

Audience: Business development team who will use this for every 
partnership evaluation. Needs to be reusable and consistent.

Request: Create a "Partnership Evaluation Framework" that:
1. Lists all key evaluation dimensions
2. Includes 3-5 questions per dimension
3. Has a scoring rubric with clear definitions
4. Calculates a weighted total score
5. Includes red flags that should be deal-breakers
6. Produces a summary scorecard at the end

Format as an Excel template I can reuse.
```

---

## Tips for Advanced Prompts

### 1. Be Architectural

For complex outputs, describe the structure before content:

```
Create a report with:

SECTION 1: Executive Summary (1 page)
- Must stand alone — someone reading only this gets the key message
- Bottom line up front, then supporting points

SECTION 2: Detailed Analysis (3-4 pages)
- [specific requirements]

SECTION 3: Appendices
- Supporting data, methodology notes
```

### 2. Provide Format Examples

Show exactly what you want:

```
Format each recommendation like this:

**Recommendation 1: [Title]**
- What: [1 sentence description]
- Why: [1 sentence rationale]
- Impact: [quantified if possible]
- Owner: [who should act]
- Timeline: [by when]

Follow this exact format for all 5 recommendations.
```

### 3. Set Quality Gates

```
Before finalising, verify:
- All facts are from the provided materials (no invented data)
- Tone is consistent throughout
- Recommendations are specific and actionable
- Length is within limits

If any of these fail, revise before showing me.
```

### 4. Narrate Multi-Step Workflows

```
Complete these steps in order:

Step 1: [First task]
— Show your output from Step 1

Step 2: [Second task using Step 1 output]
— Show your output from Step 2

Step 3: [Final task]
— Produce the final deliverable
```

---

## Combining Copilot + Claude

A powerful workflow uses both:

1. **Copilot:** "Summarise all emails with [client] from last month"
2. **Copy to Claude**
3. **Claude:** "Based on this summary, create a client relationship brief with recommendations"
4. **Copilot:** "Help me schedule a meeting and draft the agenda"

```
Example Flow:

Copilot (gather) → Claude (analyse + create) → Copilot (distribute)
```

---

## Security Reminders

When using Claude for work:

⚠️ Check your company's AI policy before uploading data  
⚠️ Don't share highly confidential information without authorisation  
⚠️ Review all outputs before sharing externally  
⚠️ Claude doesn't have access to your company systems (unlike Copilot)  
⚠️ Uploaded files are processed but not permanently stored

---

## Troubleshooting Advanced Tasks

| Problem | Solution |
|---------|----------|
| File upload failed | Check file size (<50MB), try different format |
| Analysis missed key data | Be explicit about which columns/fields to focus on |
| Document formatting wrong | Provide a more detailed structure in your Request |
| Workflow lost track | Ask Claude to summarise current state before continuing |
| Output too generic | Add more Context and Examples |

---

## Ready for the Challenge?

Once you're comfortable with Levels 6-9, try **Level 10: Build a Custom Skill** — the capstone challenge where you design and build a reusable skill that solves a real problem for your team.

See the main README for full challenge details and four different tracks to choose from.
