# Level 12: Document Generation

| | |
|---|---|
| **Difficulty** | ⭐⭐⭐ Advanced |
| **Time** | 20–25 minutes |
| **Tool** | Claude ([claude.ai](https://claude.ai)) |
| **Skill** | Generate polished, downloadable documents |

---

## Objective

Use Claude to create professional documents in multiple formats (Word, PowerPoint, Excel, PDF) that can be downloaded and used directly.

---

## Business Context

Claude can generate complete, formatted documents as downloadable files—useful for creating templates, reports, and presentations.

---

## Sample Materials

| File | Description |
|------|-------------|
| [document-briefs.md](document-briefs.md) | Specifications for different document types |
| [sample-inputs.md](sample-inputs.md) | Content to transform into documents |

---

## Your Task

**Choose one track:**

**Track A:** Create a report or briefing document (Word/PDF)  
**Track B:** Build a presentation deck (PowerPoint)  
**Track C:** Design a template or model (Excel)  

---

## Starter Prompts

### Report Generation

```
Context: I need a [report type] for [purpose]. This will be read by 
[audience] and used to [decision/action it supports].

Language: [Professional/executive/technical]. 
Tone: [Balanced/persuasive/analytical].

Examples: Structure as a consulting-quality deliverable:
- Executive summary (1 page)
- Main sections with clear headings
- Supporting detail in appendices if needed

Audience: [Who]—they expect [format/length/style] and will use this to [purpose].

Request: Create a Word document with:
- Table of contents
- [Section 1]: [description]
- [Section 2]: [description]
- [Section 3]: [description]
- Page numbers and headers
- Total length: [X pages]
Make it ready to share without editing.
```

### Presentation

```
Context: I need a presentation on [topic] for [audience/occasion].
Goal: [What should they think, feel, or do after watching?]

Language: [Inspiring/analytical/urgent]. Minimal text—headlines and bullets only.

Examples: Follow assertion-evidence format:
- Headline states the point
- Body provides supporting evidence
- No full sentences in bullets

Audience: [Who]—presenting for [X minutes]. They care about [priorities].

Request: Create a [X]-slide PowerPoint with:
1. [Slide 1 purpose]
2. [Slide 2 purpose]
...
Include speaker notes for each slide.
Export as .pptx
```

---

## Success Criteria

✅ Document is professionally formatted  
✅ Structure follows business conventions  
✅ Downloadable file works correctly  
✅ Minimal editing required  

---

**[← Previous: Level 11](../11-claude-analysis/readme.md)** | **[Back to Main Guide](../../../readme.md)** | **[Next: Level 13 →](../13-multi-step-workflows/readme.md)**

