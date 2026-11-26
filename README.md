# Fathir Hidayah Ramadhan

**AI Engineer • LLM Engineering • Autonomous Agents • Full-Stack Development**

![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=900&color=7C3AED&center=true&vCenter=true&width=820&lines=Building+AI-powered+products+that+ship.;LLM+engineering%2C+RAG%2C+and+autonomous+agents.;Production-grade+full-stack+systems+in+Next.js+%2B+Python.)

[![Profile views](https://komarev.com/ghpvc/?username=fathirramadhan-web&label=Profile+views&color=7C3AED&style=flat-square)](https://github.com/fathirramadhan-web)
[![GitHub followers](https://img.shields.io/github/followers/fathirramadhan-web?label=Followers&style=flat-square&color=7C3AED)](https://github.com/fathirramadhan-web?tab=followers)
[![Portfolio](https://img.shields.io/badge/Portfolio-fathirramadhan--web.github.io-7C3AED?style=flat-square)](https://fathirramadhan-web.github.io/portfolio/)
[![Location](https://img.shields.io/badge/Location-Indonesia-7C3AED?style=flat-square)](#)

[![Email](https://img.shields.io/badge/Email-fathirhidayahramadhan%40gmail.com-7C3AED?style=flat-square&logo=gmail&logoColor=white)](mailto:fathirhidayahramadhan@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-fathirhidayahramadhan-7C3AED?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fathirhidayahramadhan)
[![Live product](https://img.shields.io/badge/Live-clipperin.vercel.app-7C3AED?style=flat-square)](https://clipperin.vercel.app)
[![Live product](https://img.shields.io/badge/Live-gaskarir.my.id-7C3AED?style=flat-square)](https://gaskarir.my.id)

## About

I build AI-powered products and autonomous agent systems, then ship them as real, production-grade software. My main technical interest is **LLM engineering** — turning language-model capabilities into reliable, user-facing features through prompt design, output parsing, multi-provider fallback, and strict validation.

My work spans two directions. On one side, **applied AI**: transcription and content-analysis pipelines, legal RAG over hundreds of Indonesian statutes, and classical machine learning with proper evaluation and explainability. On the other, **full-stack engineering**: the Next.js frontends, FastAPI/Laravel backends, databases, and deployment pipelines that put those models in front of real users.

I care about reliability by design — fallback strategies, validation at every trust boundary, and verification before output. A model is only useful once it is running inside a real system: an API, a database, a job queue, a deployment.

```
DATA → MODEL → PROMPT → API → DATABASE → JOB QUEUE → FRONTEND → DEPLOYMENT
```

I am a recent Informatics Engineering graduate from **Telkom University Purwokerto** (GPA 3.72/4.00), with internship experience in web development (Dinas Komunikasi dan Informatika Kabupaten Cirebon) and quality assurance (PT Telkomsel).

## Current Focus

```
AI Engineering   → LLM integration, prompt design, structured output, provider fallback
RAG              → Hybrid retrieval (semantic + BM25), local embeddings, grounded generation
Autonomous Agent → Browser automation agents, agentic coding agents, tool use, recovery loops
Machine Learning → Feature engineering, imbalance handling, model tuning, SHAP explainability
Full-Stack       → Next.js (App Router), React, FastAPI, Laravel, Supabase, Prisma, PostgreSQL
Reliability      → Rate limiting, CSRF protection, row-level security, idempotent retries
Deployment       → Vercel, Docker, GitHub Actions, Cloudflare R2, Neon / Supabase
```

**Shipping / recently shipped**

```
Clipperin        — AI video clipping: long-form to vertical clips with auto captions
Latview/Gaskarir — AI career platform: CV builder, mock interview, assessment, tracker
TanyaNusa        — Indonesian legal RAG over 340+ statutes with hybrid retrieval
browser-qa-agent — AI agent for exploratory browser QA with screenshot evidence
Coursera Agent   — Autonomous agent solving graded quizzes via page-state reasoning
GitHub Engineer  — Agent that reproduces and fixes real GitHub issues, verified by tests
MetaPrediction   — Dota 2 meta prediction with leakage-safe expanding-window ML
Aksaraku         — Medium-style poetry & writing platform, zero-database cost
SIMASET          — Government asset management system (Laravel)
```

## Technical Maturity

```
CORE
Python · TypeScript · Next.js · React · Machine Learning (Scikit-learn, XGBoost)

APPLIED
LLM Engineering · Prompt Engineering · RAG (Hybrid Retrieval) · Autonomous Agents
FastAPI · Laravel · Supabase · Prisma · PostgreSQL · MySQL · Playwright · FFmpeg

DEVELOPING
Model deployment at scale · MLOps · Vector database infrastructure · Agent orchestration
```

## Featured Projects

**AI / LLM Engineering**

| Project | Description | Stack |
|---|---|---|
| **Clipperin** | AI-powered video clipping platform — turns long-form video into ready-to-publish vertical clips with automatic captioning and 9:16 cropping. Event-driven pipeline with LLM moment analysis and a rule-based fallback. Live at [clipperin.vercel.app](https://clipperin.vercel.app). | [Next.js](https://github.com/fathirramadhan-web/clipperin) · TypeScript · Inngest · Whisper · GPT-4 · FFmpeg · Neon PostgreSQL |
| **Latview / Gaskarir** | AI career platform: CV builder, mock interview with text-to-speech, skill assessment, and application tracking. Multi-provider LLM with fallback, validated API routes. Live at [gaskarir.my.id](https://gaskarir.my.id). | Next.js 16 · React 19 · TypeScript · Supabase · Gemini · OpenAI · Zod |
| **TanyaNusa** | Legal RAG assistant over 340+ Indonesian statutes. Hybrid retrieval (FastEmbed multilingual + BM25) with a pluggable LLM layer and retrieval-only fallback to reduce hallucination. | Python · FastAPI · React · FastEmbed · BM25 · OpenRouter/Ollama · Docker |
| **MetaPrediction** | Dota 2 hero meta prediction. Full ML pipeline with leakage-safe expanding-window validation across 8 patches, imbalance handling, and SHAP explainability. | Python · Scikit-learn · XGBoost · imbalanced-learn · SHAP |

**Autonomous Agents**

| Project | Description | Stack |
|---|---|---|
| **[GitHub Engineer](https://github.com/fathirramadhan-web)** | Agent that reads a real GitHub issue, explores the codebase, reproduces the bug, writes a fix, and verifies it with the project's own test suite — all inside isolated git worktrees. | Python · LLM agents · pytest · Playwright · git worktrees |
| **Coursera Agent** | Autonomous agent that navigates Coursera modules and solves graded single/multi-select quizzes by reading page state instead of brittle selectors. | Python · Playwright · LLM reasoning |
| **[browser-qa-agent](https://github.com/fathirramadhan-web/browser-qa-agent)** | AI agent that explores web apps in a real browser and produces consolidated QA reports with severity, reproduction steps, and screenshot evidence. | Python · browser automation |

**Full-Stack**

| Project | Description | Stack |
|---|---|---|
| **Aksaraku** | Medium-style poetry and writing platform with an animated GSAP landing page, reader accounts, and admin dashboard. Runs on file-based JSON storage for zero database cost. | Next.js App Router · React 19 · TypeScript · GSAP |
| **[SIMASET](https://github.com/fathirramadhan-web/Simaset)** | Asset management system for a government office — digitizes the full asset borrowing cycle with multi-role access, Excel import/export, and a statistics dashboard. | Laravel 10 · MySQL · PHPSpreadsheet |

## Tech Stack

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=python,tensorflow,sklearn&theme=dark" />
</a>

**AI Application**

`LLM Engineering` `RAG (Hybrid Retrieval)` `Structured Output` `Multi-Provider Fallback` `Browser Automation`

**Programming**

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=ts,js,python,php,mysql&theme=dark" />
</a>

**Backend & Database**

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=nextjs,fastapi,laravel,nodejs,postgres,supabase,prisma,sqlite&theme=dark" />
</a>

**Frontend**

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,js,html,css&theme=dark" />
</a>

**Agents & Automation**

`Playwright` `pytest` `git worktrees` `Inngest` `FFmpeg`

**DevOps / Deployment**

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=vercel,docker,githubactions,aws,redis&theme=dark" />
</a>

## Experience

**Web Developer Intern — Dinas Komunikasi dan Informatika Kabupaten Cirebon** · Jan 2026 – Feb 2026
Built SIMASET to digitize the office asset borrowing process with multi-role access, end-to-end workflow tracking, and reporting with Excel import/export.

**Quality Assurance Intern — PT Telkomsel** · Jul 2025 – Sep 2025
Performed manual testing on internal digital products, designing and executing test cases to catch bugs and usability issues before release, within the Strategic Delivery workstream.

## Goals

- Ship autonomous agents that operate safely on real repositories and real workflows
- Deepen RAG infrastructure: better chunking, hybrid retrieval, and citation grounding
- Move from model experimentation to reproducible, monitored deployment pipelines
- Publish technical write-ups on applied LLM engineering and agent design
- Build AI products that stay functional under provider degradation, not just in the demo

## Support My Work

If my projects help you, consider leaving a star or reaching out to collaborate.

*"I don't just call model APIs — I build the reliable systems around them."*

Fathir Hidayah Ramadhan · Informatics Engineering, Telkom University Purwokerto · Indonesia

---

![GitHub stats](https://github-readme-stats.vercel.app/api?username=fathirramadhan-web&show_icons=true&hide_border=true&bg_color=0D1117&title_color=7C3AED&icon_color=7C3AED&text_color=c9d1d9)

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=fathirramadhan-web&layout=compact&hide_border=true&bg_color=0D1117&title_color=7C3AED&text_color=c9d1d9)

![Pac-Man contribution graph](https://raw.githubusercontent.com/fathirramadhan-web/fathirramadhan-web/refs/heads/output/pacman-contribution-graph.svg)
