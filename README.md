# AI PMO Copilot

**PM AI Fluency Lab**

A single-page tool that turns raw project artifacts into ready-to-share PMO deliverables — with every line traceable back to a source document. Nothing invented.

🔗 **Live demo:** `https://<cherish_22k>.github.io/ai-pmo-copilot/` 

## What it does

Paste real project artifacts — a charter, a risk register, a stakeholder list — into the intake panel, and generate:

- **Status Report** — a weekly status report drafted straight from your inputs
- **Risk Summary** — risks pulled and prioritized (High / Medium / Unknown confidence)
- **Stakeholder Update** — a stakeholder-ready narrative
- **Action Tracker** — action items extracted from the source material
- **What Changed** — a diff-style summary of what's changed since last week

Every generated line is traceable back to the document it came from, so nothing is fabricated or assumed.

## Why it's different

Most AI summarizers optimize for fluent prose. This one optimizes for **trust**:

- Built-in **human review checklist** before anything ships to stakeholders
- **Governance notes** covering what the tool is good at, where it can get things wrong, and what should never be pasted into it
- A confidence model (HIGH / MEDIUM / UNKNOWN) instead of pretending every answer is certain

## Who it's for

Project managers and PMO leads who spend hours turning scattered documents into status reports, risk summaries, and stakeholder updates — and want an AI assist they can actually defend in a steering committee meeting.

## Tech

Single-file HTML/CSS/JS — no build step, no dependencies. Open `index.html` in a browser or serve it via GitHub Pages.

## Running locally

```bash
git clone https://github.com/<your-username>/ai-pmo-copilot.git
cd ai-pmo-copilot
open index.html   # or just double-click the file
```

## Status

Prototype / demo built as part of exploring practical AI fluency workflows for project management. Feedback welcome.

---

Built with [Claude](https://claude.ai).
