# 🚀 Copilot & Claude Mini-Hackathon

A hands-on workshop for Executive Leadership Teams to build practical AI prompting skills using Microsoft 365 Copilot and Claude.

| | |
|---|---|
| **Duration** | 45 minutes (core) / 2+ hours (with advanced levels) |
| **Format** | Try it → See the limits → Leave with prompts you'll actually use |
| **Tools** | Microsoft 365 Copilot, Claude |

---

## 📋 Quick Navigation

| Level | Task | Tool | Time | Difficulty |
|:-----:|------|:----:|:----:|:----------:|
| [1](#level-1-summarise) | Summarise | Copilot | 5-7 min | ⭐ |
| [2](#level-2-draft--rework) | Draft & Rework | Copilot | 7-10 min | ⭐ |
| [3](#level-3-decide) | Decide | Copilot | 7-10 min | ⭐ |
| [4](#level-4-function-specific) | Function-Specific | Copilot | 10 min | ⭐⭐ |
| [5](#level-5-share--refine) | Share & Refine | Group | 5-10 min |  |
| [6](#level-6-data-analysis--visualisation) | Data Analysis | Claude | 15-20 min | ⭐⭐ |
| [7](#level-7-document-generation) | Document Generation | Claude | 15-20 min | ⭐⭐ |
| [8](#level-8-multi-step-workflows) | Multi-Step Workflows | Claude | 20-30 min | ⭐⭐⭐ |
| [9](#level-9-custom-automation) | Custom Automation | Claude | 20-30 min | ⭐⭐⭐ |
| [10](#level-10-challenge) | 🏆 Custom Skill Challenge | Claude | 30-45 min | ⭐⭐⭐⭐ |

**Jump to:** [CLEAR Framework](#the-clear-framework) · [Quick Reference](#quick-reference) · [Resources](#resources)

---

## Overview

This isn't a demo—it's a chance to **use AI on your actual work**. By the end of this session, you'll have:

✅ Tested Copilot/Claude on real tasks  
✅ Discovered what works (and what doesn't)  
✅ Built prompts you'll use beyond this session  
✅ Learned the CLEAR framework for better results

### Before You Start

| Tool | Access |
|------|--------|
| **Microsoft 365 Copilot** | Available in Teams, Outlook, Word, PowerPoint, Excel |
| **Claude** | [claude.ai](https://claude.ai) (for Levels 6-10) |

---

## The CLEAR Framework

Better prompts = better results. Use this framework every time:

| Letter | Component | What It Means |
|:------:|-----------|---------------|
| **C** | **Context** | What's the situation? Background info that grounds the AI. |
| **L** | **Language** | What tone, style, vocabulary? Formal? Casual? Technical? |
| **E** | **Examples** | Show, don't just tell. Provide samples or patterns to follow. |
| **A** | **Audience** | Who's this for? Their knowledge level, needs, concerns. |
| **R** | **Request** | What exactly do you want? Format, length, deliverable. |

<details>
<summary><strong>📖 See CLEAR in Action (click to expand)</strong></summary>

### ❌ Weak prompt:
> "Can you help me with this email?"

### ✅ CLEAR prompt:

```
Context: I need to inform the board about a project delay. 
This is the first major delay on a high-visibility initiative.

Language: Professional but direct. No jargon. Solution-oriented, 
not defensive.

Examples: Similar to how we communicated the Q2 budget revision — 
issue first, brief cause, recovery plan.

Audience: Non-technical board members who care about impact and 
timeline. They have 2 minutes to read this.

Request: Write a 3-paragraph email:
1. Lead with the issue and new timeline
2. Explain the cause briefly (2-3 sentences)
3. Close with the recovery plan and next update
```

### Quick Template

```
Context: [situation/background]
Language: [tone/style/vocabulary]
Examples: [patterns to follow or reference]
Audience: [who this is for, what they know]
Request: [specific deliverable, format, length]
```

</details>

📄 **[Full CLEAR Framework Guide →](docs/CLEAR-framework.md)**

---

## Core Levels (1-5)

Work through these at your own pace. Start with **Level 1** and progress as time allows.

---

<a name="level-1-summarise"></a>
<details>
<summary><strong>Level 1: Summarise</strong> · <code>⏱️ 5-7 min</code> <code>⭐ Beginner</code></summary>

#### Goal
Condense a long document, email chain, or meeting into key points.

#### Your Task

1. Find something lengthy in your inbox or files:
   - A long email thread
   - Meeting notes or transcript
   - A strategy document or report

2. Ask Copilot/Claude to summarise it.

#### Starter Prompts

**Basic:**
```
Summarise this document in 5 bullet points.
```

**Better (CLEAR):**
```
Context: I need to brief my manager on this email thread before our 1:1.

Language: Concise, factual, action-oriented.

Examples: Structure as: Core issue → Key positions → Decision needed.

Audience: My manager, who has no context and 1 minute to read.

Request: Summarise in under 100 words:
- The core issue or request
- Key positions from each party
- What action is needed and by when
```

**For meeting transcripts:**
```
Context: I missed this meeting and need to catch up quickly.

Language: Factual, neutral — no editorialising.

Examples: Use this structure:
1. Decisions made
2. Action items (owner + deadline)
3. Open questions

Audience: Me — I need to know what affects my work.

Request: Extract all decisions, action items, and open questions. 
Format as three separate lists.
```

#### 💡 Tips

- **Be explicit about length** — "5 bullets" or "under 100 words"
- **Specify your audience** — "for my manager" changes the output
- **Ask for structure** — bullet points, numbered lists, or prose

#### ⚠️ Watch Out For

- AI may miss nuance or context you know implicitly
- Verify key facts, especially numbers and dates
- Check that nothing critical was omitted

</details>

---

<a name="level-2-draft--rework"></a>
<details>
<summary><strong>Level 2: Draft & Rework</strong> · <code>⏱️ 7-10 min</code> <code>⭐ Beginner</code></summary>

#### Goal
Create or improve written communications.

#### Your Task

Choose one:
- **Draft from scratch:** An email, message, or announcement you need to send
- **Rework existing:** Something you've written that needs polish

#### Starter Prompts

**Drafting:**
```
Context: I need to [situation]. This is [urgent/routine/sensitive].

Language: [professional/friendly/urgent/diplomatic]. 
Avoid [specific words or phrases].

Examples: Similar in tone to [reference], or structure like:
- Opening: [what to lead with]
- Body: [key points]
- Close: [call to action]

Audience: [who], who [what they know/care about].

Request: Draft a [length] email that [specific goal — what should 
they DO after reading?].
```

**Reworking:**
```
Context: I wrote this message but it's [too long/wrong tone/unclear].

Language: Make it [more concise/more confident/less aggressive].

Examples: Keep the structure but [specific change needed].

Audience: [who] — they need to [action].

Request: Rewrite to be:
- [Specific improvement 1]
- [Specific improvement 2]
- Maximum [length]
```

**Changing tone:**
```
Context: This message sounds [defensive/aggressive/weak].

Language: Rewrite to sound [confident/diplomatic/warm] while 
keeping the same core points.

Examples: Change phrases like "[example]" to something like "[better example]".

Audience: [who] — our relationship is [context].

Request: Same message, different tone. Show me what you changed.
```

#### 💡 Tips

- **State the goal** — What should the reader DO after reading?
- **Specify what's wrong** — "too long" or "sounds aggressive"
- **Iterate** — First draft is rarely final. Use follow-up prompts.

#### Example Iteration

```
1st: "Draft a message to the team about the deadline change"
2nd: "Make it shorter and add urgency"
3rd: "Actually, lead with the 'why' before the new date"
```

</details>

---

<a name="level-3-decide"></a>
<details>
<summary><strong>Level 3: Decide</strong> · <code>⏱️ 7-10 min</code> <code>⭐⭐ Intermediate</code></summary>

#### Goal
Get structured options and trade-offs for a real decision you're facing.

#### Your Task

Think of a decision you're mulling over:
- A vendor choice
- A strategy question
- A resource allocation problem
- A process change

#### Starter Prompts

**Option analysis:**
```
Context: I'm deciding between [Option A] and [Option B] for [situation].
Constraints: [budget/timeline/resources].

Language: Analytical, balanced. Present trade-offs fairly.

Examples: Structure as a comparison table, then a recommendation.

Audience: [who will review this decision].

Request: For each option, give me:
- 3 pros and 3 cons
- Key risks
- What questions I should ask before deciding
- Your recommendation (if you had to choose)
```

**Structured comparison:**
```
Context: Comparing three approaches to [problem]:
1. [Approach 1]
2. [Approach 2]
3. [Approach 3]

Language: Systematic, evaluative. Use ratings where helpful.

Examples: Format as a table with criteria as rows.

Audience: [decision-makers] who care most about [priorities].

Request: Evaluate on: cost, speed, risk, and team impact.
Recommend which to pursue and why.
```

**Devil's advocate:**
```
Context: I'm leaning toward [decision]. I want to stress-test it.

Language: Direct and challenging. Don't soften the critique.

Examples: Structure as:
1. Strongest arguments against
2. What could go wrong
3. What I might be missing

Audience: Me — I need honest pushback.

Request: Play devil's advocate. What are the strongest arguments 
against this choice? Be specific, not generic.
```

#### 💡 Tips

- **Give context** — AI can't read your mind about constraints
- **Ask for structure** — Tables, pros/cons lists, or frameworks
- **Request the counter-argument** — Avoid confirmation bias

#### ⚠️ Watch Out For

- AI doesn't know your company's politics, culture, or history
- Outputs are generic unless you provide specifics
- Use this as input to your thinking, not a replacement for it

</details>

---

<a name="level-4-function-specific"></a>
<details>
<summary><strong>Level 4: Function-Specific</strong> · <code>⏱️ 10 min</code> <code>⭐⭐ Intermediate</code></summary>

#### Goal
Apply AI to a task specific to your role.

#### Choose Your Track

<details>
<summary><strong>💼 Sales & Commercial</strong></summary>

**Proposal Review:**
```
Context: I've attached a proposal we're sending to [customer type]. 
Deal size: [X]. Competitive situation: [context].

Language: Critical but constructive. Flag issues clearly.

Examples: Structure feedback as:
1. Strengths to keep
2. Gaps to address
3. Specific improvements

Audience: Me and my team — we need to strengthen this before sending.

Request: Review and suggest:
- Where to strengthen our value proposition
- Gaps a procurement team might flag
- How to differentiate from [competitor]
```

**Customer Insights:**
```
Context: I've pasted recent communications with [customer].

Language: Analytical. Identify patterns and signals.

Examples: Structure as: Concerns → Buying signals → Recommended actions.

Audience: Me preparing for a meeting with them.

Request: What are their key concerns? What buying signals do you see?
What should I address proactively?
```

</details>

<details>
<summary><strong>⚙️ Operations</strong></summary>

**Process Analysis:**
```
Context: Here's a description of our [process name] process.
We're looking to improve efficiency.

Language: Analytical, practical. Focus on actionable improvements.

Examples: Categorise findings as: Quick wins / Medium effort / Strategic.

Audience: Operations leadership evaluating improvement options.

Request: Identify:
- Bottlenecks or inefficiencies
- Automation opportunities
- Quick wins vs longer-term improvements
```

**Risk Register:**
```
Context: I'm planning a [project type] project. Timeline: [X]. 
Key dependencies: [Y].

Language: Structured, comprehensive. Use standard risk categories.

Examples: Format as a risk register table with: Risk, Likelihood, 
Impact, Mitigation, Owner.

Audience: Project governance stakeholders.

Request: Create a risk register with:
- 10-15 likely risks for this type of initiative
- Suggested mitigations for each
- Recommended owners by function
```

</details>

<details>
<summary><strong>👥 People & HR</strong></summary>

**Job Description Review:**
```
Context: We're hiring for [role]. Here's the draft JD.
Market: [competitive/niche/etc].

Language: Critical, inclusive-aware. Flag issues diplomatically.

Examples: Structure as: What works / What to change / Suggested rewrites.

Audience: Hiring manager and HR partner.

Request: Review for:
- Inclusive language
- Realistic requirements (or inflated?)
- What might deter good candidates
- Comparison to market standard
```

**Org Change Comms:**
```
Context: We're announcing [org change]. Impact: [who's affected].
Sensitivity: [high/medium/low].

Language: Transparent, empathetic, clear. No corporate-speak.

Examples: Structure as: What's changing → Why → What it means for you 
→ What happens next → Who to ask.

Audience: [affected employees]. They'll be [worried/curious/relieved].

Request: Draft the announcement. Anticipate the top 3 questions 
they'll have and address them proactively.
```

</details>

<details>
<summary><strong>📊 Finance</strong></summary>

**Variance Explanation:**
```
Context: I need to explain this variance analysis to non-finance 
stakeholders. Key variance: [X].

Language: Plain English. No jargon unless defined. Lead with impact.

Examples: Structure as: What changed → Why it matters → What to do.

Audience: [Business leaders] who understand the business but not 
accounting details.

Request: Explain in under 200 words. Focus on business impact, 
not accounting mechanics.
```

**Business Case Review:**
```
Context: Here's a business case summary for [initiative]. 
Investment: [X]. Expected return: [Y].

Language: Critical, thorough. Challenge assumptions.

Examples: Structure as: Questions to ask / Assumptions to test / 
Likely CFO concerns.

Audience: Me preparing to present this to finance leadership.

Request: 
- What assumptions should I stress-test?
- What questions will the CFO likely ask?
- Where is the case weakest?
```

</details>

<details>
<summary><strong>🧑‍💼 General Leadership</strong></summary>

**Feedback Script:**
```
Context: I need to give feedback to [person] about [issue].
Relationship: [direct report/peer/etc]. History: [context].

Language: Direct but supportive. Use SBI model.

Examples: Structure as:
- Situation (when/where)
- Behaviour (what specifically they did)
- Impact (effect it had)
- Request (what to do differently)

Audience: Me delivering this feedback.

Request: Draft a script. Include how to open the conversation 
and how to handle likely responses.
```

**1:1 Prep:**
```
Context: I have a 1:1 with [stakeholder] about [topic].
Background: [situation].

Language: Thoughtful, strategic. Help me prepare.

Examples: Structure as: Questions to ask / Points to make / 
Landmines to avoid.

Audience: Me preparing for this meeting.

Request: 
- What questions should I ask them?
- What might they be concerned about?
- What should I make sure to cover?
```

</details>

</details>

---

<a name="level-5-share--refine"></a>
<details>
<summary><strong>Level 5: Share & Refine</strong> · <code>⏱️ 5-10 min</code> <code>⭐ Group Activity</code></summary>

#### Goal
Learn from others and tighten your prompts.

#### Part A: Share with the Group

1. **What worked?** Share a prompt that gave you something useful.
2. **What failed?** Where did AI miss the mark? What did you have to fix?
3. **What surprised you?** Better or worse than expected?

#### Part B: Refine Together

Take a prompt that partially worked and improve it as a group:

1. **Review the output** — What's wrong or missing?
2. **Apply CLEAR** — Which component was weakest?
3. **Rewrite the prompt** — Try again with improvements
4. **Compare results**

#### Prompt Improvement Template

```
ORIGINAL PROMPT:
[paste it]

WHAT WAS WRONG WITH THE OUTPUT:
[describe]

IMPROVED PROMPT (using CLEAR):
Context: [add situation]
Language: [specify tone/style]
Examples: [add reference patterns]
Audience: [clarify who it's for]
Request: [be more specific]
```

#### Discussion Questions

- Which CLEAR component made the biggest difference?
- What patterns do you notice in prompts that work well?
- What tasks is AI surprisingly good/bad at?

</details>

---

## Advanced Levels (6-10) — Claude Required

> **⚠️ Levels 6-10 require Claude** at [claude.ai](https://claude.ai) with file creation and analysis capabilities. These are more technical and extend beyond the core 45-minute session.

---

<a name="level-6-data-analysis--visualisation"></a>
<details>
<summary><strong>Level 6: Data Analysis & Visualisation</strong> · <code>⏱️ 15-20 min</code> <code>⭐⭐ Intermediate</code></summary>

#### Goal
Upload data and get Claude to analyse it, find patterns, and create visualisations.

#### Prerequisites
- Access to Claude at [claude.ai](https://claude.ai)
- A data file (CSV, Excel) — use your own or generate sample data

#### Your Task

1. Upload a spreadsheet or CSV to Claude
2. Ask Claude to analyse the data and surface insights
3. Request specific visualisations or charts

#### CLEAR Prompts for Data Analysis

**Exploratory Analysis:**
```
Context: I've uploaded our Q3 sales data. I need to present findings 
to the leadership team tomorrow.

Language: Business-friendly insights, not statistical jargon. 
Explain significance in plain terms.

Examples: Focus on patterns like "Sales in Region X grew 15% while 
Region Y declined" rather than correlation coefficients.

Audience: Senior leaders who want actionable insights, not methodology.

Request: 
1. Summarise the key trends (3-5 bullet points)
2. Identify any anomalies or outliers worth investigating
3. Create a bar chart comparing performance across regions
4. Recommend 2-3 areas to focus on next quarter
```

**Comparative Analysis:**
```
Context: This spreadsheet contains customer feedback scores from 
two product lines over 12 months.

Language: Analytical but accessible. Use percentages and comparisons.

Examples: Structure findings like "Product A scores 23% higher on 
ease-of-use but 15% lower on value perception."

Audience: Product managers who need to prioritise improvements.

Request:
1. Compare the two product lines across all metrics
2. Create a visualisation showing the trend over time
3. Identify which product has the most urgent issues
4. Export findings as a formatted report
```

#### Generate Sample Data

If you don't have data handy:
```
Generate a sample CSV with 100 rows of sales data including:
- Date (last 6 months)
- Region (North, South, East, West)
- Product category (A, B, C)
- Revenue
- Units sold

Include realistic patterns and a few anomalies for me to find.
```

#### 💡 Tips
- **Be specific about dimensions** — "Compare by region" vs "Compare by month"
- **Ask for the 'so what'** — What should we DO with this insight?
- **Request exports** — Claude can create downloadable Excel/CSV files

</details>

---

<a name="level-7-document-generation"></a>
<details>
<summary><strong>Level 7: Document Generation</strong> · <code>⏱️ 15-20 min</code> <code>⭐⭐ Intermediate</code></summary>

#### Goal
Have Claude create polished, downloadable documents — Word, PowerPoint, Excel.

#### Your Task

Choose one:
- **Board pack** — Executive summary document
- **Presentation** — Slide deck for an upcoming meeting
- **Report** — Structured analysis document
- **Spreadsheet** — Template with formulas

#### CLEAR Prompts for Document Generation

**PowerPoint Presentation:**
```
Context: I'm presenting our 2025 strategy to the all-hands meeting 
next week. We have 4 strategic pillars.

Language: Inspiring but grounded. Confident without overpromising. 
Minimal text per slide.

Examples: Follow "assertion-evidence" format:
- One key message as the headline
- Supporting evidence below (visual, 3 bullets max)
- No full sentences in bullets

Audience: All 200 employees, mixed technical/non-technical. 
They want to know where we're going and how it affects them.

Request: Create a 10-slide PowerPoint:
1. Title slide
2. "Why change" context slide
3-6. One slide per strategic pillar
7. Key milestones timeline
8. "What this means for you" slide
9. Q&A slide
Include speaker notes for each.
```

**Word Document Report:**
```
Context: I need to document our project post-mortem. The project 
ran 3 weeks late and 15% over budget but delivered successfully.

Language: Objective and balanced. Acknowledge issues without blame. 
Forward-looking on lessons learned.

Examples: Structure like a consulting deliverable:
- Executive summary up front
- Details in body
- Appendices for supporting data

Audience: Project governance board and future project managers.

Request: Create a Word document with:
- Executive summary (1 page)
- Project overview (scope, timeline, budget)
- What went well (3-5 items)
- What didn't go well (3-5 items with root causes)
- Lessons learned and recommendations
- Appendix: detailed timeline comparison

Include headers, page numbers, and table of contents.
```

**Excel Template:**
```
Context: I need a reusable template for monthly business reviews.

Language: Clear labels, built-in instructions.

Examples: Like a financial model:
- Inputs clearly marked
- Calculations protected
- Outputs summarised on dashboard

Audience: Regional managers with varying Excel skills.

Request: Create an Excel workbook with:
- Instructions tab
- Data input tab (with validation and dropdowns)
- Calculations tab (with formulas)
- Dashboard tab (summary metrics, conditional formatting)
Include sample data showing how it works.
```

#### 💡 Tips
- **Be architectural** — Describe structure before content
- **Specify format details** — Headers, page numbers, fonts
- **Request editability** — "Make it easy to modify section 3"

</details>

---

<a name="level-8-multi-step-workflows"></a>
<details>
<summary><strong>Level 8: Multi-Step Workflows</strong> · <code>⏱️ 20-30 min</code> <code>⭐⭐⭐ Advanced</code></summary>

#### Goal
Chain multiple analysis steps together — upload, process, analyse, synthesise, output.

#### Your Task

Take a complex problem that requires:
1. Understanding source material
2. Processing or transforming it
3. Analysing for insights
4. Synthesising findings
5. Producing a polished output

#### CLEAR Prompts for Workflows

**Competitive Analysis Workflow:**
```
Context: I've uploaded three documents:
1. Our product roadmap (internal)
2. Competitor A's recent press releases
3. Competitor B's investor presentation

I need to understand where we're differentiated and where we're at risk.

Language: Strategic and analytical. Use "threat/opportunity" framing.

Examples: Structure like a strategy consulting deliverable with 
clear "so what" implications.

Audience: Executive team making investment decisions.

Request: Complete this workflow:
Step 1: Extract key capabilities from each document
Step 2: Create a comparison matrix across all three companies
Step 3: Identify our unique strengths (things only we have)
Step 4: Identify gaps (things competitors have that we don't)
Step 5: Assess which gaps are urgent vs nice-to-have
Step 6: Produce a 2-page executive brief with recommendations

Show your working at each step before moving to the next.
```

**Customer Feedback Synthesis:**
```
Context: I've uploaded:
- 6 months of support tickets (CSV)
- NPS survey responses (Excel)
- Product improvement backlog (document)

Language: Customer-centric. Quote actual customer language where powerful.

Examples: Structure like a "voice of customer" report — themes with evidence.

Audience: Product and CX leadership who need to prioritise investments.

Request: Complete this workflow:
Step 1: Categorise support tickets by theme (auto-detect themes)
Step 2: Map NPS verbatims to the same themes
Step 3: Cross-reference with product backlog — what's already planned?
Step 4: Identify top 3 unaddressed pain points
Step 5: Estimate impact based on frequency and sentiment
Step 6: Produce prioritised recommendations with:
   - Theme summaries
   - Representative quotes
   - Recommended actions
   - Quick wins vs bigger investments
```

#### 💡 Tips
- **Narrate the workflow** — "Step 1... Step 2..." helps Claude track state
- **Ask for working** — "Show your analysis before conclusions"
- **Build iteratively** — Complete one step, review, then continue

</details>

---

<a name="level-9-custom-automation"></a>
<details>
<summary><strong>Level 9: Custom Automation</strong> · <code>⏱️ 20-30 min</code> <code>⭐⭐⭐ Advanced</code></summary>

#### Goal
Create reusable prompts, templates, or mini-apps you can use repeatedly.

#### Your Task

Build something you'll use beyond this session:
- A **prompt template** for a recurring task
- A **document template** with your company's structure
- A **checklist generator** for your domain
- An **analysis framework** you can re-run on new data

#### CLEAR Prompts for Automation

**Reusable Prompt Template:**
```
Context: I frequently prepare briefing documents before client meetings. 
Each time I start from scratch and quality varies.

Language: Professional, adaptable to different clients and meeting types.

Examples: Include placeholders like [CLIENT_NAME], [MEETING_OBJECTIVE] 
that I fill in each time.

Audience: Me, before client meetings. Sometimes shared with my team.

Request: Create a reusable "Client Meeting Brief" prompt template that:
1. Has clear sections I fill in (client context, meeting purpose, etc.)
2. Produces a consistent 1-page brief every time
3. Includes: background, relationship history, objectives, concerns, 
   talking points, desired outcomes
4. Works whether I have 5 minutes or 30 minutes to prep

Make the template itself something I can save and reuse.
```

**Analysis Framework:**
```
Context: My team evaluates partnerships regularly but lacks a 
consistent framework.

Language: Structured, evaluative. Use scoring where appropriate.

Examples: Like a due diligence checklist — comprehensive but efficient.

Audience: Business development team, for every partnership evaluation.

Request: Create a "Partnership Evaluation Framework" that:
1. Lists all key dimensions (strategic fit, terms, complexity, risk)
2. Includes 3-5 questions per dimension
3. Has a scoring rubric (1-5) with clear definitions
4. Produces a summary scorecard
5. Includes red flags that should be deal-breakers

Format as a template I can apply to any opportunity.
```

#### 💡 Tips
- **Think recurring** — What do you do weekly/monthly that could be templated?
- **Design for reuse** — Clear placeholders, modular structure
- **Test immediately** — Build the template, then use it on a real case

</details>

---

<a name="level-10-challenge"></a>
<details>
<summary><strong>Level 10: 🏆 Challenge — Build a Custom Skill</strong> · <code>⏱️ 30-45 min</code> <code>⭐⭐⭐⭐ Expert</code></summary>

#### Goal
Design and build a custom Claude skill that solves a real problem for your team.

This is the capstone challenge. You'll create something that extends Claude's capabilities for a specific use case — something you or your team can use repeatedly.

---

#### What is a Custom Skill?

A custom skill is a structured set of instructions that teaches Claude how to perform a specialised task consistently. Think of it as creating a "specialist mode."

**Examples:**
- **Board Pack Generator** — Takes raw inputs, produces formatted board document
- **Deal Reviewer** — Analyses contracts against your standard terms
- **Competitor Monitor** — Processes announcements, extracts strategic implications
- **Onboarding Assistant** — Answers employee questions using your policies
- **Meeting Synthesiser** — Turns transcripts into structured notes

---

#### Choose Your Track

<details>
<summary><strong>Track A: The Document Factory</strong></summary>

**Challenge:** Create a skill that generates a specific document type your team produces regularly.

**Requirements:**
1. Define the document type and purpose
2. Specify all required sections and format
3. Include quality checks
4. Handle variations (audiences, lengths)
5. Produce downloadable output

**Example Skill:**
```
Context: Creating a skill for Investment Committee memos. 
We write 3-5 per week in a strict format.

Language: Formal, analytical. Precise terminology, no fluff.

Examples: Structure always follows:
1. Executive Summary (1 para, max 100 words)
2. Investment Thesis (3 bullets: why now, why this, why us)
3. Deal Terms (table)
4. Risk Factors (numbered, with mitigations)
5. Recommendation (approve/reject/defer)

Audience: IC members who review 10+ memos per meeting.

Request: Create a skill that:
1. Asks for key inputs (company, terms, thesis, risks)
2. Generates complete memo in our format
3. Flags missing information
4. Produces downloadable Word doc
5. Includes quality check summary
```

**Success Criteria:**
- [ ] Consistent output format every time
- [ ] Handles missing info gracefully
- [ ] Output ready to use (minimal editing)
- [ ] Downloadable in right format

</details>

<details>
<summary><strong>Track B: The Analyst</strong></summary>

**Challenge:** Create a skill that analyses inputs and produces structured insights.

**Requirements:**
1. Define accepted inputs
2. Specify analysis performed
3. Structure output format
4. Include confidence levels
5. Produce actionable recommendations

**Example Skill:**
```
Context: Creating a skill for customer churn analysis. 
I receive CRM exports and need to identify at-risk accounts.

Language: Analytical, precise. Flag urgency levels clearly.

Examples: Structure as:
- Overall risk summary (1 para)
- High-risk accounts table (name, score, warning signs)
- Pattern analysis (what predicts churn?)
- Recommended interventions per tier

Audience: Customer Success managers prioritising outreach.

Request: Create a skill that:
1. Accepts CSV of customer data
2. Analyses engagement, tickets, usage
3. Calculates churn risk score per account
4. Groups into risk tiers
5. Generates prioritised action list
6. Exports as Excel with multiple tabs
```

**Success Criteria:**
- [ ] Consistent, structured analysis
- [ ] Handles messy data gracefully
- [ ] Actionable recommendations
- [ ] Explains reasoning

</details>

<details>
<summary><strong>Track C: The Assistant</strong></summary>

**Challenge:** Create a skill that acts as a specialised assistant for a domain.

**Requirements:**
1. Define domain expertise
2. Specify how to handle questions
3. Include guardrails
4. Design interaction pattern
5. Handle edge cases

**Example Skill:**
```
Context: Creating an HR Policy Assistant. Managers ask policy 
questions constantly; answers are scattered across documents.

Language: Helpful, clear. Careful not to give legal advice. 
Say "based on the policy documents..." and recommend HR for complex cases.

Examples: When asked about leave:
- Quote relevant policy section
- Explain in plain language
- Flag exceptions
- Suggest who to contact

Should NOT: Make up policies, give legal advice, handle grievances.

Audience: People managers who need quick answers.

Request: Create a skill that:
1. Can be "loaded" with policy documents
2. Answers by referencing specific policies
3. Admits when something isn't covered
4. Provides document source for every answer
5. Escalates appropriately
6. Maintains helpful, non-bureaucratic tone
```

**Success Criteria:**
- [ ] Accurate, sourced answers
- [ ] Knows limits of knowledge
- [ ] Maintains guardrails
- [ ] Feels helpful, not robotic

</details>

<details>
<summary><strong>Track D: The Workflow</strong></summary>

**Challenge:** Create a skill that orchestrates a multi-step process.

**Requirements:**
1. Define workflow stages
2. Specify inputs/outputs per stage
3. Include decision points
4. Handle errors
5. Produce final deliverable

**Example Skill:**
```
Context: Creating a QBR preparation workflow. Currently takes 
2-3 days of scattered work; we often miss things.

Language: Structured, guiding. Like a helpful PM keeping you on track.

Examples: Five stages:
1. Data Gathering — collect metrics
2. Analysis — identify trends, wins, issues
3. Narrative — build the story
4. Deck Building — create presentation
5. Review — check for gaps

Each stage has: inputs required, tasks, quality checks, time estimate.

Audience: Regional managers preparing QBRs, varying experience levels.

Request: Create a workflow skill that:
1. Guides through all 5 stages
2. Asks for inputs at each stage
3. Produces intermediate outputs
4. Won't proceed until requirements met
5. Generates final PowerPoint
6. Includes readiness checklist
```

**Success Criteria:**
- [ ] Clear stage progression
- [ ] Handles different skill levels
- [ ] Usable intermediate + final outputs
- [ ] Catches errors early

</details>

---

#### How to Build Your Skill

**Step 1: Define the Problem (5 min)**
```
What task do I do repeatedly that:
- Takes significant time?
- Requires consistency?
- Could benefit from AI?
- Others on my team also do?
```

**Step 2: Design the Skill (10 min)**

Use the CLEAR structure:
```
Context: [What situation is this skill for?]
Language: [What tone/style should outputs have?]
Examples: [What does "good" look like? Provide samples.]
Audience: [Who will use this? What do they need?]
Request: [What should the skill do, step by step?]
```

**Step 3: Build & Test (15-20 min)**
- Give Claude your skill definition
- Test with a real example
- Note what works and what doesn't
- Refine based on results

**Step 4: Document & Share (5 min)**
- Write a brief "how to use" guide
- Share with the group

---

#### Skill Design Template

```markdown
# Skill Name: [name]

## Purpose
[One sentence: what problem does this solve?]

## When to Use
[Situations where this skill is helpful]

## Inputs Required
- [Input 1]
- [Input 2]

## Outputs Produced
- [Output 1: format, length]
- [Output 2: format, length]

## The Skill Definition
[Full CLEAR prompt]

## Quality Checks
- [ ] [Check 1]
- [ ] [Check 2]

## Known Limitations
- [What this skill can't do]
```

---

#### Share Your Skill

Be ready to share:
1. What problem does it solve?
2. Quick demo
3. What worked well?
4. What would you improve?
5. Who else could use this?

</details>

---

## Quick Reference

### CLEAR Cheat Sheet

| Component | Question | Example |
|-----------|----------|---------|
| **Context** | What's the situation? | "I'm preparing for a board meeting about..." |
| **Language** | What tone/style? | "Professional but warm, no jargon" |
| **Examples** | What should it look like? | "Structure like our Q2 report" |
| **Audience** | Who's this for? | "Non-technical executives" |
| **Request** | What exactly do you want? | "3 bullets, under 100 words" |

### Fix Common Problems

| If output is... | Strengthen... |
|-----------------|---------------|
| Too generic | **Context** |
| Wrong tone | **Language** |
| Bad structure | **Examples** |
| Too complex/simple | **Audience** |
| Missing pieces | **Request** |

### Prompt Template

```
Context: [situation/background]
Language: [tone/style/vocabulary]
Examples: [patterns to follow]
Audience: [who this is for]
Request: [specific deliverable]
```

📄 **[Full Quick Reference Card →](docs/quick-reference.md)**

---

## Resources

### Documentation
- 📄 [CLEAR Framework Guide](docs/CLEAR-framework.md)
- 📄 [Prompt Library](docs/prompt-library.md)
- 📄 [Quick Reference Card](docs/quick-reference.md)
- 📄 [Troubleshooting Guide](docs/troubleshooting.md)
- 📄 [Advanced Claude Skills](docs/advanced-claude-skills.md)

### External Links
- [Microsoft Copilot Documentation](https://learn.microsoft.com/en-us/copilot/)
- [Claude User Guide](https://docs.anthropic.com/)
- [CLEAR Framework (AiPromptsX)](https://aipromptsx.com/prompts/frameworks/clear)

### Next Steps
- **Save your best prompts** — Build a personal library
- **Experiment daily** — 10 minutes/day builds fluency
- **Share with your team** — What works for you might help them

---

## Feedback

After the session:
- What worked well?
- What would you change?
- What topics need a deeper dive?

---

*Created for ELT Training*  
*Facilitator: Nathan*
