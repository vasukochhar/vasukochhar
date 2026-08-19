<div align="center">

```
██╗   ██╗ █████╗ ███████╗██╗   ██╗
██║   ██║██╔══██╗██╔════╝██║   ██║
██║   ██║███████║███████╗██║   ██║
╚██╗ ██╔╝██╔══██║╚════██║██║   ██║
 ╚████╔╝ ██║  ██║███████║╚██████╔╝
  ╚═══╝  ╚═╝  ╚═╝╚══════╝ ╚═════╝ 

██╗  ██╗ ██████╗  ██████╗██╗  ██╗██╗  ██╗ █████╗ ██████╗ 
██║ ██╔╝██╔═══██╗██╔════╝██║  ██║██║  ██║██╔══██╗██╔══██╗
█████╔╝ ██║   ██║██║     ███████║███████║███████║██████╔╝
██╔═██╗ ██║   ██║██║     ██╔══██║██╔══██║██╔══██║██╔══██╗
██║  ██╗╚██████╔╝╚██████╗██║  ██║██║  ██║██║  ██║██║  ██║
╚═╝  ╚═╝ ╚═════╝  ╚═════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝
```

[![Typing](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2800&pause=900&color=A78BFA&center=true&vCenter=true&width=640&lines=backend+%2F+ai+infrastructure;runtime+governance+for+ai+agents;the+model+is+the+easy+part)](https://anchor8.net)

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vasu-kamal-kochhar-3b4433288/)
[![Anchor8](https://img.shields.io/badge/ANCHOR8-7C3AED?style=for-the-badge&logo=shieldsdotio&logoColor=white)](https://anchor8.net)
[![Email](https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vasu.kochhar@gmail.com)

</div>

---

```yaml
role      : co-founder @ anchorate  ·  cs (ai & ml) '26 @ manipal university jaipur
interests : agent governance  ·  backend systems  ·  retrieval  ·  orchestration
status    : shipping to production, writing a novel between deploys
```

---

Most of what I build is about what happens when an autonomous agent is wrong. The model is usually the easy part. The hard part sits around it: interception, policy, audit trails, and deciding which calls a system should never be allowed to make on its own.

> Cheap checks first. Most agent traffic isn't ambiguous, and paying an LLM to confirm that is wasteful. Spend the expensive judgment on the small fraction that actually needs it.

---

## work

<details>
<summary><b>anchorate</b> · co-founder · <code>&lt;200ms</code> <code>claude partner network</code></summary>

<br>

Runtime governance for enterprise AI agents. Actions get intercepted before execution and scored by parallel modality detectors feeding a LightGBM meta-scorer, so roughly 93% resolve in under 200ms without touching an LLM.

Ambiguous cases escalate to a multi-model panel (Claude, Gemini, DeepSeek) that has to reach quorum. Anything irreversible lands in a human queue with the reasoning attached.

`Python` `FastAPI` `LightGBM` `Postgres` `Docker`

</details>

<details>
<summary><b>stroted</b> · founding engineer · <code>52 tables</code> <code>142 rls policies</code></summary>

<br>

Hiring platform built on the premise that a CV is an unverifiable document. Candidates build evidence-backed capability profiles, recruiters query structure instead of parsing PDFs.

Scoring is deterministic code, never model output. Absent data is shown as absent rather than guessed.

`Next.js` `Supabase` `Postgres` `Node.js` `TailwindCSS`

</details>

---

## projects

<details>
<summary><b>repo surgeon</b> · autonomous codebase modernization · <code>46/46 tests</code></summary>

<br>

Built for OpenAI Build Week 2026. Point it at a repo: it establishes a test baseline, researches actual breaking changes, then runs dependency upgrades and security fixes in a sandbox, unattended.

I owned the orchestrator, job state machine, and the verify-and-retry loop. Capped at 5 attempts, it reruns affected tests, mutation-tests the tests it wrote itself, and flags what it can't resolve for a human instead of shipping a broken upgrade.

`Python` `FastAPI` `Docker` `Codex`

</details>

<details>
<summary><b>quill8</b> · on-prem finance ai · <code>hybrid retrieval</code></summary>

<br>

Private assistant for investment professionals, running entirely on-premises. Hierarchical LangGraph workflows handle multi-step reasoning and tool orchestration.

Retrieval is hybrid, BGE-M3 vectors plus full-text fused with Reciprocal Rank Fusion, because dense search alone kept missing exact ticker and clause matches. Renders deliverables to PDF, DOCX and XLSX behind JWT auth.

`FastAPI` `LangGraph` `pgvector` `Postgres`

</details>

<details>
<summary><b>slocho</b> · swipeable knowledge feed</summary>

<br>

A TikTok-shaped feed of AI-generated flash cards, built to find out whether the format survives being applied to something other than entertainment. Still mid-build.

`Expo` `React Native` `Gemini API`

</details>

<details>
<summary><b>greenvision ai</b> · urban green-space segmentation · <code>95% acc</code></summary>

<br>

Built at the National University of Singapore under the Global Academic Internship Program, leading a five-person international team. DeepLabV3+ over satellite imagery to map urban tree cover, with training and inference pipelines on AWS SageMaker.

`PyTorch` `DeepLabV3+` `SageMaker`

</details>

---

## stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=postgresql&logoColor=white)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

![Postgres](https://img.shields.io/badge/Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## certifications

`Claude Certified Architect, Foundations (922/1000)` · `Building with the Claude API` · `Claude Code in Action`
`Machine Learning Specialization, Stanford` · `Deep Learning Specialization, DeepLearning.AI` · `Architecting Solutions on AWS`
