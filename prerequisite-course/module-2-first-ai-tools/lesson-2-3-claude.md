# Lesson 2.3 — Claude: When to Use It Instead

**Time:** ~20 minutes

---

## How Claude Differs from ChatGPT (June 2026 Update)

Both are excellent AI assistants. The differences matter for executive use:

| Dimension | ChatGPT (GPT-4o) | Claude (Opus 4.8) |
|---|---|---|
| **Document length** | ~128K tokens | 1 million tokens (~750,000 words) |
| **Tone** | Direct, confident, sometimes overconfident | Nuanced, careful, 4× less likely to leave errors unacknowledged |
| **Reasoning** | Strong (o3 model for complex tasks) | Exceptionally strong for multi-step analysis and agentic tasks |
| **Agentic capability** | Agent mode via Operator | 84% on real-world web automation benchmarks (Opus 4.8) |
| **Code** | Excellent | Excellent; stronger on self-critique and error flagging |
| **Sensitive topics** | Sometimes over-cautious | Well-calibrated with honesty improvements in 4.8 |
| **Data privacy (paid)** | Training opt-out available | Pro/Max/Enterprise: no training on conversations |
| **Speed** | Fast | Fast Mode is 2.5× faster in Opus 4.8 |

### Tier Options (June 2026)

| Tier | Price | Best For |
|---|---|---|
| Claude.ai Free | $0 | Light experimentation |
| Claude Pro | $20/month | Daily executive use — standard context and usage |
| Claude Max | $100/month | Power users needing 5–20× higher usage limits and priority access |
| Claude Enterprise | Custom | Organization-wide deployment with data governance and SSO |

**Use Claude when:**
- You are uploading a long document (contract, report, transcript) for analysis — 1M context handles entire document sets
- You want careful, nuanced reasoning rather than fast confident answers
- You are running multi-step agentic tasks and need reliability
- You are working on something sensitive and want thoughtful, uncertainty-flagging treatment
- You want well-structured long-form output (strategy documents, reports, board materials)

---

## Your First Task in Claude: Document Analysis

This is where Claude genuinely excels. Try this:

**Step 1:** Find a recent document you've read — an article, a report, or a meeting transcript (use a non-confidential one for now).

**Step 2:** Upload it using the paperclip icon in the Claude interface.

**Step 3:** Use this prompt:
```
You are a senior strategy advisor. I've attached a document for your review.

Please:
1. Summarize the key findings in 5 bullet points
2. Identify the top 3 strategic implications for a mid-size B2B company
3. Flag any claims that seem unsubstantiated or require verification
4. Suggest 3 follow-up questions I should investigate further
```

**Step 4:** Observe how Claude structures its response — notice the caveats and uncertainty flags. This is intentional and valuable.

---

## Claude's Projects Feature

Claude Pro includes "Projects" — persistent workspaces where you can:

- Upload documents that Claude references in every conversation in that project
- Store context about a specific initiative (e.g., "Q3 Strategy Review")
- Maintain a consistent working relationship with Claude on long-running work
- With the 1M token context, you can upload an entire quarter's worth of meeting transcripts, reports, and strategy documents into a single project

**Try it:** Create a Project called "My AI Learning" and upload a relevant document or paste in background about your role.

## Claude's Agent Mode (2026)

Like ChatGPT's Operator, Claude now has agent capabilities:

- Can take multi-step actions: research → synthesize → draft → format in one flow
- Achieves 84% accuracy on a 542-task benchmark of real-world web automation
- Used via Claude.ai or via API for developers
- **Executive use case:** "Research the latest 10-K filings of our top 3 competitors, extract the sections on risk factors, and produce a comparison table" — Claude does the browsing, extraction, and synthesis autonomously

As with all agent modes: review before enabling on sensitive accounts, and always verify outputs on high-stakes work.

---

## Side-by-Side Comparison

For the exercise in this module, you will ask the same question to ChatGPT and Claude and compare. Watch for:

- Which one is more confident vs. more cautious?
- Which produces better-structured output?
- Which one asks clarifying questions vs. just answering?
- Which output would you trust more for a board-level decision?

---

## Key Takeaway

Do not pick one and ignore the other. Senior AI users typically have both open and route tasks based on what each handles best. Long documents, nuanced analysis → Claude. Quick drafts, research, creative tasks → ChatGPT. Over time, you'll develop an intuition for this.
