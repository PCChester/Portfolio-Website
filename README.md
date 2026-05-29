# Chris Chester — Portfolio Website

> *"I help small and mid-sized teams adopt AI tools — and actually use them."*

A personal portfolio site for Chris Chester, AI Enablement Architect based in Valencia, Spain. Built to show the full range: automation projects and data pipelines on one side, 25+ years of teaching people to communicate across boundaries on the other — most recently, the boundary between humans and machines.

**Live site:** [christeachesai.netlify.app](https://christeachesai.netlify.app/)

---

## Pages

A static site built with plain HTML, CSS, and vanilla JavaScript. No frameworks, no build tools, no dependencies.

| Page | Purpose |
|---|---|
| `index.html` | Hero, service phases, engagement packages, featured projects, diagnostic chatbot + AI Readiness form |
| `about.html` | The Translator narrative, 30-year origin story, language-learning analogy, closing CTA |
| `projects.html` | Four portfolio cards in Before → Build → Result format with filter bar |
| `blog.html` | Article grid with topic filter pills, placeholder articles across AI Adoption / Workflow Automation / AI Training |
| `contact.html` | Email and LinkedIn cards — no form, no automation |
| `es/` | Full Spanish translation of all five pages, with EN ↔ ES toggle in every nav |

---

## The diagnostic chatbot

The homepage includes a working **AI Readiness chatbot**. It's not a gimmick — it's a demonstration of the kind of interaction design I build for clients.

**How it works:**

1. Opens with an operational question: *"What is your team struggling with from an operational standpoint right now?"*
2. Quick-reply buttons cover the most common pain points (call volume, invoice handling, email overload, repetitive admin) — or the visitor types freely
3. Follows up with four questions: prior AI tool experience, team size, industry, biggest current obstacle
4. After the final exchange it generates a personalised **AI Readiness Snapshot** — three plain-English paragraphs covering where the team likely sits, the most relevant quick win, and what the path forward typically looks like

There is also a parallel **5-step form** for visitors who prefer structured input over conversation. Same questions, same report output.

**Important:** the report is generated entirely client-side by a `buildReport()` JavaScript function — no API call, no backend. The chatbot is a UX demonstration, not a live AI integration.

---

## Design

Editorial warmth over tech-cold polish.

- **Fonts:** Lora (serif headlines), DM Sans (body), DM Mono (labels/code)
- **Palette:** Warm cream paper, terracotta accent (`#c05c2b`), teal (`#2a7a6a`), gold (`#b87c2a`)
- **Layout:** CSS custom properties throughout, no framework, mobile-responsive

---

## Projects featured

Each card uses a **Before → Build → Result** format — because the point isn't the code, it's the problem it solved.

**Lead Scout**
Finds companies in any target area, scores them, identifies a named contact, and drafts a personalised cold email. A five-stage pipeline that replaced hours of manual LinkedIn and Google research.
[GitHub](https://github.com/PCChester/Lead-Scout) · Stack: Python, Flask, Anthropic API, Tavily API, Hunter.io, BeautifulSoup, SSE

**Bellabeat Case Study**
Google Data Analytics capstone. Full pipeline from raw data to strategic recommendation. Key finding: users who slept poorly trained harder the next day — a compensatory over-exertion pattern that pointed toward a Burnout Prevention feature rather than a performance optimisation.
[GitHub](https://github.com/PCChester/Bellabeat-Case-Study) · Stack: SQL (BigQuery), R/tidyverse, Tableau

**Developer Portfolio Scanner**
Takes a list of portfolio URLs and returns a scored dataset of developer availability and skills across 25 tech categories, plus PNG visualisation charts. Built for recruiters losing hours to manual browsing.
[GitHub](https://github.com/PCChester/Developer-Portfolio-Scanner) · Stack: Python, BeautifulSoup, Pandas, Matplotlib

**Sales Performance Analyzer**
Loads a sales CSV, runs Pandas analysis across categories, regions, and monthly trends, then sends a structured summary to Claude for a plain-English executive report — revenue breakdown, trend analysis, anomaly flagging, three concrete recommendations.
[GitHub](https://github.com/PCChester/sales-performance-analyzer) · Stack: Python, Pandas, Anthropic SDK

---

## The positioning

I spent 30 years teaching people to communicate across cultural and linguistic boundaries — ESL, corporate communication, SCUBA instruction across 36 countries. The job was always the same: take something unfamiliar, break down the fear, build fluency.

AI adoption is structurally identical. Teams aren't failing because the tools are wrong. They're failing because nobody stayed long enough to make sure the team understood them, trusted them, and knew what to do when something unexpected came back.

**Three ways I work:**

1. **AI Quickstart** — Workflow audit and one working proof of concept, for teams just getting started
2. **Full Adoption Sprint** — Assessment, custom prompt library, training sessions, and SOPs, for teams with unused tools
3. **Custom Build + Train** — A scoped solution built and handed over with the team fully onboarded

---

## Running locally

No setup required. Clone and open:

```bash
git clone https://github.com/PCChester/Portfolio-Website.git
cd Portfolio-Website
open index.html
```

The Spanish pages are in the `es/` subfolder and work the same way — open `es/index.html` directly or navigate via the ES toggle in any nav bar.

---

## Contact

- **Email:** [chriscteacher@gmail.com](mailto:chriscteacher@gmail.com)
- **LinkedIn:** [Chris Chester](https://www.linkedin.com/in/peter-christopher-chester-8b262353/)
- **Tableau:** [Chris Chester Tableau Public](https://public.tableau.com/app/profile/chris.chester/vizzes)
