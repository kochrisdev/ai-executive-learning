# Lesson 3.2 — The RACE Framework

**Time:** ~20 minutes

---

## The RACE Framework

A consistent, memorable structure for building high-quality prompts:

```
R — Role
A — Action
C — Context
E — Expectations
```

Apply all four elements and your output quality will improve dramatically on the first pass.

---

## R — Role

Assign the AI a persona. This shapes tone, expertise level, and frame of reference.

**Examples:**
- "You are a McKinsey-trained strategy consultant with 20 years of experience in financial services."
- "You are a world-class copywriter specializing in executive communications."
- "You are a CFO preparing materials for an audit committee."
- "You are a skeptical investor reviewing a business plan."

**Why it works:** The model adjusts its language, assumptions, and approach based on the role. A "strategy consultant" answer is different from a "communications manager" answer to the same question.

---

## A — Action

State precisely what you want the AI to do. Be verb-specific.

**Weak:** "Do something about the product launch."
**Strong:** "Write a 500-word internal announcement, draft a 3-sentence press release quote from the CEO, and create a FAQ with 5 questions customers are likely to ask."

**Common action verbs for executives:**
- Write / Draft / Rewrite / Edit
- Summarize / Distill / Extract
- Analyze / Evaluate / Compare
- Create / Generate / Design
- Identify / List / Rank
- Critique / Stress-test / Devil's advocate

---

## C — Context

Give the AI the background it needs. Assume it knows nothing about your specific situation.

**Include:**
- Company type, size, industry
- The audience for the output
- Relevant background or constraints
- What has already been tried or decided

**Example:**
> "Context: Our company is a 150-person B2B SaaS firm serving mid-market financial services firms. We are entering a new vertical (healthcare) for the first time. The board is skeptical. This document is for internal use only and will be presented in a 30-minute board session."

---

## E — Expectations

Define the format, length, tone, and any constraints.

**Format:**
- "Use bullet points, not paragraphs"
- "Present as a 3-column comparison table"
- "Structure as: Executive Summary → Key Findings → Recommendations"

**Length:**
- "Under 300 words"
- "1 page maximum"
- "5 bullets only"

**Tone:**
- "Formal and board-appropriate"
- "Direct and action-oriented — no fluff"
- "Empathetic — this is sensitive internal news"

**Constraints:**
- "Do not make specific financial projections"
- "Avoid jargon — the audience is non-technical"
- "Cite your reasoning for each recommendation"

---

## Full RACE Example

```
ROLE: You are a senior HR consultant specializing in organizational change management.

ACTION: Write an internal communication announcing a restructuring that will
eliminate one management layer and create 3 new cross-functional teams.

CONTEXT: Our company is a 300-person technology firm. The restructuring is
effective in 6 weeks. 12 manager roles will be eliminated, with affected
individuals receiving severance and outplacement support. The remaining
organization will be largely intact. The CEO will send this message to all staff.

EXPECTATIONS:
- Length: 400-500 words
- Tone: Direct, honest, and empathetic. Acknowledge the difficulty without
  being defensive.
- Structure: Why we're doing this → What is changing → What is not changing
  → Support available → Next steps
- Do not use corporate euphemisms like "rightsizing" or "optimizing our structure"
```

This prompt produces a near-final draft in a single pass.

---

## Practice

Before moving on, write a RACE prompt for one of the tasks you identified in your Module 1 exercise. Keep it — you will use it in the Module 3 exercise.
