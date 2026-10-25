<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=3000&pause=800&color=E6EDF3&center=true&vCenter=true&width=720&lines=Harshal+Shilwant;LLM+Apps+%E2%80%A2+RAG+%E2%80%A2+Full-Stack;AI+that+answers+from+real+data." alt="Typing headline" />

<br/>

![focus](https://img.shields.io/badge/focus-AI%20%2F%20LLM%20apps-161b22?style=flat-square&labelColor=0d1117)
![currently](https://img.shields.io/badge/currently-building%20DevForge%20AI-161b22?style=flat-square&labelColor=0d1117)
![based in](https://img.shields.io/badge/based%20in-Pune%2C%20India-161b22?style=flat-square&labelColor=0d1117)

</div>

---

## How I build

I build AI apps that answer from real data and say honestly what they don't know.

- Grounded answers over clever prompts: every AI reply should point to its source.
- The app must still work when the AI doesn't: fallbacks, timeouts, retries.
- If it stores user data, isolation and auth come before features.
- Write down what works and what's still stubbed. Honest docs build trust.

---

## What I'm building

### `🧠 DevForge AI`

> Turn learning into measurable engineering skill.

An AI-powered engineering workspace that brings learning, project work and interview prep into one place. Pick a target role, get a competency roadmap, take scored assessments, and track real progress. It works with any OpenAI-compatible model, or falls back to a built-in deterministic grader so it runs without an API key. Secured with Argon2id passwords, HttpOnly sessions, CSRF protection and tested cross-user data isolation.

`AI` · `FastAPI` · `React` · `PostgreSQL` · `Docker` · `CI`

<br/>

### `💬 ChatSage AI`

> Wisdom from every conversation.

A RAG system that turns years of WhatsApp chat history into a searchable knowledge base. Upload chat exports, ask questions in plain language, and get answers grounded in the actual messages, with sources, timestamps and participants. Hybrid search (semantic + keyword + recency), a local LLM via Ollama, analytics dashboards and exports. Parses 34 WhatsApp date formats.

`RAG` · `Qdrant` · `Ollama` · `FastAPI` · `PostgreSQL` · `Redis`

<br/>

### `👗 Clozet`

> Rent the outfit, not the wardrobe.

A fashion-rental marketplace for Pune. Customers rent occasion wear like lehengas, sarees and sherwanis for a date range; sellers list garments; staff handle moderation, fulfilment and payouts through role-based admin panels. All money is handled server-side in paise to avoid rounding errors.

`marketplace` · `FastAPI` · `Next.js` · `PostgreSQL` · `RBAC`

---

## Tech

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=3178C6)
![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=flat-square&logo=javascript&logoColor=F7DF1E)

**AI & LLM**

![OpenAI](https://img.shields.io/badge/OpenAI-0d1117?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-0d1117?style=flat-square&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-0d1117?style=flat-square&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-0d1117?style=flat-square&logo=ollama&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-0d1117?style=flat-square&logo=qdrant&logoColor=DC244C)
![PyTorch](https://img.shields.io/badge/PyTorch-0d1117?style=flat-square&logo=pytorch&logoColor=EE4C2C)

**Backend & Data**

![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=flat-square&logo=fastapi&logoColor=009688)
![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=339933)
![Express](https://img.shields.io/badge/Express-0d1117?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169E1)
![MySQL](https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=4479A1)
![Redis](https://img.shields.io/badge/Redis-0d1117?style=flat-square&logo=redis&logoColor=FF4438)
![Supabase](https://img.shields.io/badge/Supabase-0d1117?style=flat-square&logo=supabase&logoColor=3FCF8E)

**Frontend**

![React](https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-0d1117?style=flat-square&logo=tailwindcss&logoColor=06B6D4)

**DevOps & Cloud**

![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ED)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-0d1117?style=flat-square&logo=githubactions&logoColor=2088FF)
![Vercel](https://img.shields.io/badge/Vercel-0d1117?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-0d1117?style=flat-square&logo=render&logoColor=46E3B7)
![AWS](https://img.shields.io/badge/AWS-0d1117?style=flat-square&logo=amazonwebservices&logoColor=FF9900)

</div>

---

## What I've learned shipping these

```text
An AI answer without a source is just a guess.

The fallback path is part of the product, not an afterthought.

Store money as integers. Floats will betray you.

If one user can see another's data, nothing else matters.

"Works on my machine" ends when docker compose up works for everyone.
```

---

## Projects

| Project | What it does | Stack |
|---|---|---|
| **DevForge AI** | AI workspace: role roadmaps, scored assessments, progress tracking | FastAPI · React · PostgreSQL · Redis |
| **ChatSage AI** | RAG over WhatsApp chat history with cited answers | FastAPI · Qdrant · Ollama · React |
| **Clozet** | Occasion-wear rental marketplace for Pune | FastAPI · Next.js · PostgreSQL |
| [**BoltPe**](https://github.com/shilwantharshal/boltpe) | Self-hosted 0% fee UPI payment gateway | Node.js · TypeScript · SQLite |

*More in the repos.*

---

## Setup

```yaml
editor: VS Code
os: Windows + Docker Desktop
stack: FastAPI + React/Next.js + PostgreSQL
ai: OpenAI / Claude APIs, local models via Ollama
habit: README and tests before calling it done
```

---

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/YOUR-LINKEDIN/)
[![Email](https://img.shields.io/badge/Email-0d1117?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:YOUR-EMAIL@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/shilwantharshal)

<br/>

<sub>— ground it, test it, ship it —</sub>

</div>
