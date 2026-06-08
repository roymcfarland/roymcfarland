# Roy McFarland

> I spent 15 years on the buying end of enterprise SaaS. Most of it was too big, too slow, and built for everyone instead of for the work in front of my operators. Modern agentic tools changed the equation, so I went back to writing the code myself.

Applied AI implementation leader. Operator-builder. 3x founder, 4x exit operator. Named inventor on patents PCT/US2016/053346.

I run [**Brightline Labs**](https://brightline.io), an applied AI software studio building lightweight, fit-for-purpose tools for the operational workflows enterprise SaaS does not handle well.

## By the numbers

- **6 products shipped in 5 months** across production scheduling, AI job search, agent auditability, task orchestration, decision-support, and open-source utilities
- **11 years on npm** — `recollie` first published in 2015, modernized to v2.0.0 in 2026 (the gap is the point)
- **4 exits across 4 distinct models** — services-firm sale, $20M IPO on CSE, PE platform acquisition, mid-market rollup
- **111 repositories total**, 7 worth featuring (below)

## Where my work sits

- Applied AI implementation
- Enterprise workflow automation
- Production scheduling and inventory planning
- LLM agent observability, replay, and auditability
- Domain-specific internal tools for operators
- Agentic development workflows with independent verification

## Featured work

| Project | What it is | Stack | Status / License |
| --- | --- | --- | --- |
| [CPG Production Scheduler](https://cpgscheduler.com) | Full-stack production scheduling and inventory planning for CPG manufacturers; running daily at a real facility | TypeScript · Next.js 15 · Drizzle · MySQL/TiDB | Private · Commercializing |
| [LLM Workbench](https://llmworkbench.io) | Debug, replay, fork, and audit LLM agent execution against frozen DAG snapshots | TypeScript monorepo · React adapter · IndexedDB + HTTP persistence | Private · Commercializing |
| [Atlas](https://jobfinder.guru) | AI-powered job search with LLM-based relevance scoring and a feedback-learning loop · [▶ 90-sec demo](#see-atlas-in-action) | TypeScript · Next.js · OpenAI API | Private · Commercializing |
| [Atlas Beta Bug Reporter](https://brightlinebugs.com) | Authenticated bug-inbox companion to Atlas — deliberately framework-free | Node.js 20+ · Postgres · Vercel Cron · Resend | Public · MIT |
| [Workflow Blueprint](https://workflowblueprint.io) | Invite-gated agentic task workspace with a key-authenticated external API | Next.js · Prisma · Postgres | Public · PolyForm Noncommercial 1.0.0 |
| [Agentic Daily Digest](https://roymcfarland.news) | Daily decision-support agent that consumes Workflow Blueprint's API and live news RSS | Next.js · Vercel Cron · Resend · Redis/Upstash | Public · PolyForm Noncommercial 1.0.0 |
| [Builder & Verifier Agent Handoff](https://worksmithlabs.com) | Open-source three-LLM methodology: advisor plans, builder ships, verifier reviews before merge | Markdown · TypeScript · Python | Public · MIT |
| [recollie](https://www.npmjs.com/package/recollie) | Dependency-free Node.js client for public US recall APIs · maintained across an 11-year version gap | Node 18+ · TypeScript declarations · zero dependencies | Public · MIT |

The most commercially useful work is private; the public repos are methodology, infrastructure, companion apps, and open-source utilities. The pattern is deliberate: ship the product private, ship the infrastructure around it public.

## See Atlas in action

A 90-second walkthrough of the LLM relevance scoring and feedback loop:

https://github.com/user-attachments/assets/a6457689-59ed-4c00-849e-778c2701c39c

## Why this work, and why now

The useful pattern in my background is not "executive learns to code."

I wrote JavaScript before the current AI wave, published an npm package in 2015, and came back to software because agentic tooling changed what one domain expert can ship. The real edge is that I have lived inside the workflows I now automate — production planning, purchasing, compliance, inventory control, sales operations, executive reporting, and cross-functional operating cadence.

My best software ideas usually start with a sentence I heard, said, or muttered as an operator:

> There has to be a lighter way to do this.

## Operating background

Before Brightline, I led or founded four businesses to exit across four different models:

- **Brightacre Law (founder, 2010–2014)** — professional services firm scaled to 16 attorneys across 3 offices; sold to a national firm
- **PLUS Products (co-founder & COO, 2015–2018)** — regulated CPG manufacturer from concept to IPO on the CSE (CSE:PLUS); $20M raise at ~$100M valuation; named inventor on PCT/US2016/053346
- **Flor Americas (founder & MD, 2019–2022)** — biotech innovation consultancy across 7 countries, $0 → $10M+ peak revenue; sold to a Miami-based PE platform
- **Carbon Chemistry (managing director, 2022–2023)** — specialty-chemicals turnaround; sold to Linde via mid-market rollup

I have run P&Ls, scaled multi-state and multi-country manufacturing, led facility buildouts, implemented ERP / CRM / MRP, raised capital, executed acquisitions, and worked through the operating reality that software is supposed to help.

## How I build

- Domain model before interface polish
- Typed data contracts and explicit validation at every boundary
- Observability for LLM calls and agent behavior, not vibes
- Human-reviewable AI workflows; independent verification before merge
- Lightweight where it can be, framework-free where it should be
- Tools operators can trust on a Monday morning at 7 a.m.

## Stack

- **Languages:** TypeScript · JavaScript · Python
- **Frontend:** Next.js (App Router) · React · HTML / CSS
- **Backend & data:** Node.js · Prisma · Drizzle · Postgres · MySQL/TiDB · Redis/Upstash
- **AI / agents:** OpenAI API · MCP (Model Context Protocol) · custom feedback-learning loops · three-LLM advisor/builder/verifier pipeline
- **Infra & delivery:** Vercel · Vercel Cron · Resend · GitHub Actions
- **Tooling:** Cursor · Codex · Manus

## Ask me about

- Production scheduling built from scratch in Next.js
- The 11-year gap between `recollie` v1 and v2
- Why "lightweight and fit-for-purpose" beats "configurable and comprehensive" almost every time
- Running a three-LLM advisor / builder / verifier pipeline as a real software-delivery process

## Connect

- Website — [brightline.io](https://brightline.io)
- LinkedIn — [linkedin.com/in/roymcfarland](https://www.linkedin.com/in/roymcfarland)
- npm — [npmjs.com/~roymcfarland](https://www.npmjs.com/~roymcfarland)
- Email — [roy@brightline.io](mailto:roy@brightline.io)
