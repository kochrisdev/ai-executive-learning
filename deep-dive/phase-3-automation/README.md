# Phase 3: Intelligent Automation

**Day:** Day 2, Morning
**Duration:** 3 hours
**Facilitator:** Lead instructor (automation specialist recommended as co-facilitator)
**Room setup:** Participants need two browser tabs open: Make.com and ChatGPT/Claude

---

## Session Objectives

By the end of this phase, participants will:
- Understand what no-code automation is and how AI fits into it
- Have configured at least one automated workflow in Make.com
- Have set up Fireflies.ai for meeting intelligence
- Identify the 3 highest-value automation opportunities in their own workflow

---

## Agenda

| Time | Activity | Format |
|---|---|---|
| 0:00–0:15 | Phase intro: from manual to automated — the executive's leverage play | Facilitator |
| 0:15–0:30 | What is Make.com — the no-code automation platform | Facilitator demo |
| 0:30–1:00 | Live demo: build a simple automation (email → AI summary → Slack) | Facilitator demo |
| 1:00–1:30 | Hands-on: participants build their first automation in Make.com | Individual exercise |
| 1:30–1:45 | Break | |
| 1:45–2:10 | Fireflies.ai demo: meeting intelligence and action item extraction | Facilitator demo |
| 2:10–2:30 | Numerous AI and browser automation overview | Facilitator demo |
| 2:30–2:50 | Automation opportunity mapping: identify top 3 workflows | Individual exercise |
| 2:50–3:00 | Phase wrap-up | Facilitator |

---

## Key Tools in This Phase (June 2026)

| Tool | Category | Best For |
|---|---|---|
| **Make.com** | Automation platform | Visual no-code automation; 1,000+ integrations; best for non-technical executives |
| **n8n** | Automation platform (open-source) | Self-hostable; AI-native agent workflows; best for regulated industries or engineering-adjacent teams |
| **Fireflies.ai** | Meeting intelligence | Auto-record, transcribe, summarize, extract action items |
| **Numerous AI** | Spreadsheet AI | AI functions inside Google Sheets or Excel |
| **Google NotebookLM** | Knowledge management | Upload document sets and create a queryable knowledge base |
| **Gemini Daily Brief** | Executive AI assistant | Personalized daily digest from inbox, calendar, and tasks |
| Comet | Browser automation | AI-assisted web tasks and form filling |
| Emily (Chrome ext.) | Browser AI | Summarize pages, draft replies in-browser |

### Make.com vs n8n: Which to Use?

Both are excellent. Choose based on your context:

| Factor | Make.com | n8n |
|---|---|---|
| Technical skill required | Low (visual) | Medium |
| Best for | Non-technical executives and teams | Teams with some technical appetite or IT involvement |
| Data privacy | Cloud-hosted | Self-hostable — data never leaves your servers |
| AI-native features | Improving rapidly | Strong AI agent orchestration built-in |
| Cost at scale | Per-operation pricing | Self-hosted: unlimited at infrastructure cost |
| Recommended for this workshop | Yes (easier to demo live) | Recommended as follow-up for regulated industries |

---

## Exercise 1: First Make.com Automation (30 min)

Build a simple 3-step automation:

**Scenario:** When a new email arrives in Gmail with a specific label → Extract the key points using ChatGPT → Send a summary to your Slack or email

**Step-by-step:**
1. Create a free Make.com account
2. Create a new Scenario
3. Add trigger: Gmail — Watch Emails (filter by label)
4. Add module: OpenAI — Create a Completion (prompt: "Summarize this email in 3 bullets")
5. Add module: Gmail/Slack — Send the summary
6. Run the scenario and test

**Alternative (simpler):** New Google Form submission → AI analysis → Google Sheets row

---

## Exercise 2: Automation Opportunity Map (20 min)

Identify your top 3 automation candidates:

| Workflow | Current Process | Trigger | AI Action | Output |
|---|---|---|---|---|
| 1. | | | | |
| 2. | | | | |
| 3. | | | | |

Rate each on:
- **Value:** How much time does this save? (High / Med / Low)
- **Feasibility:** How complex is it to build? (Easy / Medium / Hard)
- **Priority:** Which one do you build first?

---

## Facilitator Notes

- Make.com free tier has 1,000 operations/month — sufficient for the exercise
- Participants will need an OpenAI API key for the Make.com + ChatGPT integration — prepare these in advance or use a shared facilitator key for the demo
- Common blocker: Gmail OAuth permissions. Walk through this step-by-step before the hands-on exercise
- Some participants may not use Gmail — have alternative triggers ready (webhook, Google Forms, Typeform)
- The Fireflies demo is always popular — set it up to record the session itself and show the live transcript as the demo
- Emphasize: the goal is not to automate everything, it is to identify the 1–2 workflows that will save the most time with the least complexity
