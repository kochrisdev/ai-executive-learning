# Lesson 4.1 — Data Privacy Fundamentals

**Time:** ~15 minutes

---

## The Public Model Problem

When you submit text to a consumer AI tool (ChatGPT free tier, Claude free tier), by default that content may be used to improve the model. This means:

- Your data is processed on the vendor's servers
- Depending on the tier and settings, it may be reviewed by humans or used in training
- It could potentially surface in responses to other users (in rare, misconfigured scenarios)

**The mitigation:** Use enterprise tiers (OpenAI Enterprise, Claude for Enterprise) or paid consumer tiers with training opt-out enabled.

---

## Enterprise vs. Consumer AI Tools

| Tier | Data Handling | Use Case |
|---|---|---|
| **Consumer (free)** | May be used for model training | Personal learning, non-sensitive tasks only |
| **Consumer (paid)** | Typically opt-out available | Better for individuals; still not enterprise-grade |
| **Enterprise** | Data stays in your org's tenant, zero retention options, SSO | Safe for business-sensitive work |
| **On-premises / Private** | Runs entirely on your infrastructure | Maximum control; requires engineering resources |

**Rule of thumb:** If the data would be sensitive in an email, it's sensitive in an AI tool.

---

## The Data Classification Framework

Apply this simple framework before submitting anything to an AI tool:

| Data Class | Examples | AI Tool Policy |
|---|---|---|
| **Public** | Industry news, public company info, general concepts | Any tool is fine |
| **Internal** | Meeting notes (generic), general strategy documents | Paid tier with opt-out; check company policy |
| **Confidential** | Customer PII, financial forecasts, legal strategy, IP | Enterprise tier only, or internal model |
| **Restricted** | Passwords, credentials, regulated health/financial data | Never in any AI tool |

---

## Specific Categories to Never Enter

Regardless of tool or tier, never input:
- Customer names, emails, or account numbers
- Employee salaries, performance ratings, or HR records
- Legal strategy, litigation details, or privileged communications
- Unpublished product roadmaps or technical architecture
- API keys, passwords, or authentication tokens
- Personal health information (HIPAA-regulated)
- Financial details subject to insider trading rules

---

## The Practical Safe Habit

Before pasting anything into an AI tool, do a 5-second check:
> "If this text appeared in a newspaper or a competitor's hands, would that be a problem?"

If yes: anonymize, generalize, or use an enterprise tool with appropriate data controls.
