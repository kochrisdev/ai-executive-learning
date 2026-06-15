# Lesson 4.2 — AI Hallucinations & Verification

**Time:** ~15 minutes

---

## What Is a Hallucination?

An AI hallucination occurs when the model generates content that is factually incorrect but stated with complete confidence. The model does not "know" it is wrong — it is pattern-matching toward a plausible-sounding answer, not retrieving verified facts.

**Classic examples:**
- Inventing citations for academic papers that do not exist
- Stating specific statistics (revenue figures, market share, dates) incorrectly
- Fabricating quotes from real people
- Getting legal, medical, or regulatory details wrong in ways that sound authoritative

---

## Why It Happens

LLMs are trained to produce fluent, coherent text — not to be factually accurate. When the model encounters a gap in its knowledge, it fills the gap with statistically plausible text rather than saying "I don't know."

This is not a bug being fixed — it is a fundamental characteristic of how language models work. It will improve over time, but it will not disappear.

---

## The Verification Calibration Framework

Not all AI outputs carry the same risk. Calibrate your verification effort accordingly:

| Output Type | Risk Level | Verification Required |
|---|---|---|
| Brainstorming, ideas, frameworks | Low | Light or none — quality matters, facts less so |
| Internal drafts (memos, emails) | Low–Medium | Review for accuracy before sending |
| External communications | Medium | Verify any specific claims before publishing |
| Competitor or market data | High | Cross-check against primary sources |
| Legal, financial, or regulatory content | High | Always verify with qualified human expert |
| Anything that will be quoted or cited | High | Verify every specific fact, statistic, or citation |

---

## Practical Verification Habits

1. **The specifics rule:** If the output contains a specific number, name, date, or citation — verify it. Generalities are usually safe; specifics are where hallucinations hide.

2. **The "how do you know?" test:** Ask the AI to provide its source for a specific claim. If it cannot, or if the source does not check out — flag it.

3. **Perplexity as a check:** Run factual claims through Perplexity, which provides live citations, to verify AI-generated assertions.

4. **Never cite without checking:** Never forward or publish AI-generated content with specific claims you have not personally verified.

---

## The Right Mental Model

Think of AI as a very fast junior analyst who is brilliant at synthesis and drafting but occasionally makes things up with total confidence. You would never submit a junior analyst's work without review. Same rule applies here.

The value of AI is not that it is always right — it is that it eliminates the blank-page problem, structures thinking quickly, and gets you to 80% in seconds. The final 20% — verification, judgment, and accountability — is yours.
