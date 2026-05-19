# Chris Chester — Portfolio Website

> *"I build the AI workflows your team will actually use — and I stay to make sure they know how."*

A personal portfolio site for Chris Chester, AI Enablement Architect and trainer. Built to show the range: the technical side (automation projects, data pipelines, Python) and the human side (25+ years teaching people to communicate across boundaries — most recently, the boundary between humans and machines).

**Live site:** [christeachesai.netlify.app](https://christeachesai.netlify.app/)

---

## What's here

A static, four-page site built with plain HTML, CSS, and a little vanilla JavaScript. No frameworks, no build tools, no dependencies — just files that open in a browser.

| Page | Purpose |
|---|---|
| `index.html` | Hero, service overview, diagnostic chatbot, AI Readiness mini-report form |
| `about.html` | The Translator narrative, origin story, skills breakdown |
| `projects.html` | Portfolio cards in Before → Build → Result format |
| `contact.html` | Scheduling and direct contact |

---

## The diagnostic chatbot

The homepage includes a live **"Am I a good fit for you?"** chatbot, powered by the Anthropic API (Claude). This isn't a gimmick — it's a working demonstration of exactly the kind of thing I build for clients.

**How it works:**
1. The bot opens with a single question about what the team struggles with when adopting new tools
2. Quick-reply buttons cover the four most common friction points (reversion to manual work, prompting gaps, no clear process, fear of replacement) — or the visitor can type freely
3. The bot asks 2–3 follow-up questions to collect context: team size, industry, current AI usage
4. After the third exchange, it sends the full conversation to Claude via the Anthropic API and returns a personalised **AI Readiness Snapshot** — three paragraphs covering where the team likely sits on the adoption curve, the most relevant quick win, and what training typically looks like for a team in that situation

There's also a parallel **5-question form** for people who prefer structured input over conversation. Same context gathering, same kind of report.

Both are live on the homepage. The chatbot is the pitch and the product demo at the same time.

**Stack:** Vanilla JS frontend → Anthropic API (`claude-sonnet`) → response rendered inline

---

## Design

The goal was editorial warmth over tech-cold polish. The kind of site a thoughtful human made, not a template.

- **Fonts:** Lora (serif headlines), DM Sans (body), DM Mono (code/labels)
- **Palette:** Warm cream paper tones, terracotta accent, teal, gold
- **Layout:** Mobile-first, no framework, CSS custom properties throughout

---

## Projects featured

Each card uses a **Before → Build → Result** format — because the point isn't the code, it's the problem it solved.

1. **Job/Client Lead Gen Pipeline** — Finds companies actively adopting AI, identifies the right contact, and surfaces their email via Hunter.io. Built as a practical alternative to Apollo and Clay.
2. **Bellabeat Case Study** — Google Data Analytics capstone. Full pipeline: Google Sheets → SQL (BigQuery) → R/tidyverse → Tableau. Key finding: users who slept poorly trained harder the next day — a compensatory over-exertion pattern that pointed toward a Burnout Prevention feature, not a performance optimisation one. [View on GitHub](https://github.com/PCChester/Bellabeat-Case-Study)
3. **Developer Portfolio Scanner** — A Python scraper that takes a list of portfolio URLs and returns a scored dataset of developer availability and skills, plus PNG charts. Built for recruiters spending hours on manual browsing.
4. **Sales Performance Analyzer** — A Python pipeline that loads a sales CSV, runs Pandas analysis, and sends a structured summary to Claude for a plain-English executive report. Revenue breakdowns, trend analysis, anomaly flagging, and three concrete recommendations — in seconds.

---

## The positioning (in plain English)

I spent 25+ years teaching people to communicate across cultural and linguistic boundaries. ESL. Corporate communication. SCUBA instruction. The job was always the same: take something unfamiliar and make it usable.

AI adoption is exactly the same problem. Teams aren't failing because the tools are wrong — they're failing because nobody stayed long enough to make sure the team understood them, trusted them, and knew what to do when they got a strange answer.

That's the gap. That's where I work.

**The three things I do:**
1. **Audit & Strategy** — Find where your team is losing time and map the 20% of tasks worth automating first
2. **Build** — Design and build the workflow, agent, or pipeline that solves the problem
3. **Train & Enable** — Stay until the team knows how to use it, adapt it, and trust it — that's when the ROI shows up

---

## Tech stack

- HTML5 / CSS3 / Vanilla JS
- Anthropic API (Claude) — powers the diagnostic chatbot
- Google Fonts (Lora, DM Sans, DM Mono)
- No build process, no npm, no framework
- Deployed as static files

---

## Running locally

No setup required for most of the site. Just clone and open:

```bash
git clone https://github.com/PCChester/[repo-name].git
cd [repo-name]
open index.html
```

**Note:** The chatbot requires an Anthropic API key. Add yours to the relevant config or environment variable before testing that feature locally.

---

## Contact

- **Email:** [chriscteacher@gmail.com]
- **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/peter-christopher-chester-8b262353/)
- **Tableau:** [Chris Chester Tableau](https://public.tableau.com/app/profile/chris.chester/vizzes)
