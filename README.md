# Vasu Kochhar

Backend / AI infrastructure. 2026 CS graduate, Manipal University Jaipur.

Most of what I build is about what happens when an autonomous agent is wrong. The model is usually the easy part. The hard part sits around it: interception, policy, audit trails, and deciding which calls a system should never be allowed to make on its own.

> Cheap checks first. Most agent traffic isn't ambiguous, and paying an LLM to confirm that is wasteful. Spend the expensive judgment on the small fraction that actually needs it.

Currently building Anchorate. Writing a novel when I'm not.

---

## Work

**[Anchorate](https://anchor8.net)** · co-founder

Runtime governance for enterprise AI agents. Actions are intercepted before execution and scored by parallel modality detectors feeding a LightGBM meta-scorer — roughly 93% resolve in under 200ms without touching an LLM. Ambiguous cases escalate to a multi-model panel (Claude, Gemini, DeepSeek) that has to reach quorum, and anything irreversible lands in a human queue with the reasoning attached. Member of the Anthropic Claude Partner Network.

**[StrotED](https://stroted.com)** · founding engineer

Hiring platform built on the premise that a CV is an unverifiable document. Candidates build evidence-backed capability profiles; recruiters query structure instead of parsing PDFs. Next.js, Supabase, 52-table Postgres schema, 142 RLS policies. Scoring is deterministic code, never model output — absent data is shown as absent rather than guessed.

---

## Projects

<details>
<summary><b>Repo Surgeon</b> — autonomous codebase modernization · <code>46/46 tests</code></summary>

<br>

Built for OpenAI Build Week 2026. Point it at a repo: it establishes a test baseline, researches actual breaking changes, then runs dependency upgrades and security fixes in a sandbox, unattended.

I owned the orchestrator, job state machine, and the verify-and-retry loop — capped at 5 attempts, reruns affected tests, mutation-tests the tests it wrote itself, and flags what it can't resolve for a human instead of shipping a broken upgrade.

`Python` `FastAPI` `Docker` `Codex`

</details>

<details>
<summary><b>Quill8</b> — on-prem finance AI · <code>hybrid retrieval</code></summary>

<br>

Private assistant for investment professionals, running entirely on-premises. Hierarchical LangGraph workflows handle multi-step reasoning and tool orchestration. Retrieval is hybrid — BGE-M3 vectors plus full-text, fused with Reciprocal Rank Fusion — because dense search alone kept missing exact ticker and clause matches. Renders deliverables to PDF, DOCX and XLSX behind JWT auth.

`FastAPI` `LangGraph` `pgvector` `Postgres`

</details>

<details>
<summary><b>Slocho</b> — swipeable knowledge feed</summary>

<br>

A TikTok-shaped feed of AI-generated flash cards. Built to find out whether the format survives being applied to something other than entertainment. Still mid-build.

`Expo` `React Native` `Gemini API`

</details>

<details>
<summary><b>GreenVision AI</b> — urban green-space segmentation · <code>95% acc</code></summary>

<br>

Built at the National University of Singapore under the Global Academic Internship Program, leading a five-person international team. DeepLabV3+ over satellite imagery to map urban tree cover, with training and inference pipelines on AWS SageMaker.

`PyTorch` `DeepLabV3+` `SageMaker`

</details>

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

![Postgres](https://img.shields.io/badge/Postgres-4169E1?style=flat&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

## Certifications

Claude Certified Architect — Foundations (922/1000) · Building with the Claude API · Claude Code in Action
Machine Learning Specialization, Stanford · Deep Learning Specialization, DeepLearning.AI · Architecting Solutions on AWS

---

[LinkedIn](https://www.linkedin.com/in/vasu-kamal-kochhar-3b4433288/) · [anchor8.net](https://anchor8.net) · vasu.kochhar@gmail.com
