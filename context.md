# context.md — Portfolio Website Project

## Project Overview
A personal portfolio website for Chris Chester to attract employment as an AI Automation Specialist and AI Adoption Trainer / Enablement Architect. Also positioned to attract freelance clients — small and mid-sized teams that have bought AI tools but aren't using them.

## Goals
- Primary: Get hired (stable employment, family to support)
- Secondary: Attract freelance clients
- Show range: automation projects, data analysis, training/adoption skills
- Position Chris as "The Translator" — the person who bridges AI tools and human adoption

## Target Visitor
- Founders and team leads at small/mid-sized businesses struggling with AI adoption
- HR managers and hiring teams at companies adopting AI
- Tech leads or department heads looking for AI integration help

## Tone & Style
- Warm, direct, and approachable — no jargon or catchphrases
- Professional and credible
- Personal — Chris's teaching personality comes through
- NOT: corporate, cold, buzzword-heavy, or generic

## Brand & Positioning
- Brand name: **Chris Chester / Teaches AI**
- Core identity: "The Translator" — AI Enablement Architect
- The ESL background is the unfair advantage: learning to use AI = learning a second language (vocabulary → grammar → fluency)

## Service Tiers (3 Phases)
1. **Audit & Strategy** — Identify what 20% of tasks are leaking time/money. Deliverables: workflow audit report, top-3 automation recommendations.
2. **Build** — Python-backed workflows and pipelines. Deliverables: working prototype or pipeline, handover documentation.
3. **Train & Enable** — Workshops to close the fear gap and ensure ROI. Deliverables: custom prompt library, SOPs, up to 3 training sessions.

## Engagement Packages (3 Ways to Work Together)
1. **AI Quickstart** — For teams just getting started. Workflow audit + proof of concept.
2. **Full Adoption Sprint** — For teams who bought tools that aren't being used. Assessment + training + SOPs.
3. **Custom Build + Train** — For founders who know what they want built. Scoped solution + full documentation + team onboarding.

## Website Pages (Current State)
- **index.html** — Hero, 3 service phases, 3 engagement packages, about band, 2 featured frameworks, diagnostic chatbot + AI Readiness mini-report form
- **about.html** — The Translator narrative, 30-year origin story (Austria → NYC → Germany → World → Valencia), language analogy grid, closing CTA band
- **projects.html** — 4 portfolio cards in Before/Build/Result format with filter bar
- **blog.html** — Article grid with topic filter, 6 placeholder articles across AI Adoption / Workflow Automation / AI Training
- **contact.html** — Email and LinkedIn cards, no form
- **es/** — Full Spanish translation of all 5 pages (index, about, projects, blog, contact) with EN/ES language toggle in nav

## Chatbot & Form (index.html)
- Opening question: "What is your team struggling with from an operational standpoint right now?"
- Quick reply options: "No time to take all calls", "Invoices get lost or double-billed", "Too many emails/chats to handle", "Repetitive admin tasks"
- Bot collects: work description → AI tool history → team size → industry → biggest obstacle
- Generates a personalised 3-paragraph AI Readiness Snapshot using a client-side JS buildReport() function (no API call)
- Parallel 5-step form option for people who prefer structured input

## Design System
- Fonts: Lora (serif), DM Sans (sans), DM Mono (mono) — Google Fonts
- Colors: warm paper tones, terracotta accent (#c05c2b), teal (#2a7a6a), gold (#b87c2a), warm ink (#1c1a16)
- Style: editorial, warm, human — not techno or corporate
- CSS variables used throughout, no framework, no build tools

## Projects Featured
- **Lead Scout** (COMPLETE) — 5-stage AI pipeline: discover → score → classify → find contact → draft cold email. GitHub: https://github.com/PCChester/Lead-Scout
- **Bellabeat Case Study** (COMPLETE) — Google Data Analytics capstone. Key finding: compensatory over-exertion pattern → Burnout Prevention feature recommendation. GitHub: https://github.com/PCChester/Bellabeat-Case-Study
- **Developer Portfolio Scanner** (COMPLETE) — Python scraper scoring developer availability and skills across 25 tech categories. GitHub: https://github.com/PCChester/Developer-Portfolio-Scanner
- **Sales Performance Analyzer** (COMPLETE) — Python + Pandas + Claude API pipeline generating plain-English executive sales reports. GitHub: https://github.com/PCChester/sales-performance-analyzer

## Tech Stack
- Static HTML/CSS/Vanilla JS (site)
- Python (automation projects)
- Claude Code as primary build environment

## Progress Log
- [Session 1] Strategy, tone, target audience discussed; context file system created
- [Session 2] Bellabeat Case Study reviewed, polished, pushed to GitHub; Tableau vizzes rebuilt
- [Session 3+] Website built across multiple sessions (index, about, projects, contact)
- [Session 3+] Brand confirmed: Chris Chester / Teaches AI
- [Session 3+] Design system established (Lora/DM Sans/DM Mono, warm editorial palette)
- [Recent] blog.html added with topic filter bar and 6 placeholder articles
- [Recent] Engagements section added to index.html (3 engagement packages)
- [Recent] Chatbot reworked: new operational-focus opening question, 4-turn flow, fixed context capture
- [Recent] AI Readiness form reworked to match chatbot flow (5 steps)
- [Recent] buildReport() jargon removed — plain language throughout
- [Recent] Full Spanish translation created in es/ folder with EN/ES nav toggle on all pages
