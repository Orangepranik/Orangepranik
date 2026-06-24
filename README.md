<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0f172a,100:f97316&text=Orangepranik&fontColor=ffffff&fontSize=58&fontAlignY=40&desc=Systems%20Architect%20%C2%B7%20Full-Stack%20Engineer%20%C2%B7%20Builder&descAlign=50&descAlignY=60&descSize=18" width="100%" />

<a href="https://github.com/Orangepranik">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=F97316&center=true&vCenter=true&width=720&lines=Architecting+an+event-driven+MES%E2%86%92ERP;DDD+%C2%B7+ISA-95+%C2%B7+Event+Sourcing+%C2%B7+52+ADRs;Full-stack%3A+Next.js+16+%2B+FastAPI+%2B+PostgreSQL;%D0%A1%D1%82%D1%80%D0%BE%D1%8E+%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D1%83%2C+%D0%B0+%D0%BD%D0%B5+%D0%BE%D1%87%D0%B5%D1%80%D0%B5%D0%B4%D0%BD%D0%BE%D0%B9+CRUD" alt="typing tagline" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=Orangepranik&color=f97316&style=flat-square&label=Profile+views" alt="profile views" />

</div>

---

### 🧩 About me · Кто я

🏭 I design and build **manufacturing software end-to-end** — from the Postgres schema and the domain model to the last pixel of the UI.
🛠️ Solo founder & systems architect who still writes **every line**: backend, frontend, domain logic, tests, infra.
📐 I treat software like an engineering discipline — decisions are reasoned, documented, and traceable, not improvised.

> *Инженер-архитектор. Проектирую домен, пишу бэкенд и фронтенд сам, держу дисциплину архитектурных решений (ADR) и проверяю всё на работающем приложении.*

---

### 🚀 What I'm building · Что строю — **Vanguard ERP**

A production-grade, **event-sourced ERP/MES** for a real electronics manufacturer (batteries, 5G antennas, remote displays). One **operational truth** — who / what / when / how much — fully traceable per serial number and recomputable after the fact.

- ⚡ **Event store at the core** — every state change emits an immutable event; BI, costing & statuses are *projections* rebuilt from the journal
- 🔬 **Per-SN traceability & actual costing** — lot-pinning, purchase-price variance, ABC overhead absorption
- 📊 **BI & finance** — unit economics, margins, break-even, run-rate, FX, inbound/outbound logistics
- 🗓️ **Monte-Carlo scheduling** — finite-capacity, priority-aware ship-date estimation
- 🗂️ **52 ADRs and counting** — every architectural decision written down with context & consequences

> *Не «складская программка», а цельная система операционной правды: всё трассируется по серийнику и пересчитывается задним числом.*

---

### 🛠️ Tech stack · Стек

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js%2016-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React%2019-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%204-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-FF6B6B?style=for-the-badge)

**Backend**

![Python](https://img.shields.io/badge/Python%203.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic%20v2-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy%202-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis%20%2B%20arq-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-6BA81E?style=for-the-badge)

**Architecture & Practices**

![Event Sourcing](https://img.shields.io/badge/Event%20Sourcing-f97316?style=for-the-badge)
![DDD](https://img.shields.io/badge/Domain--Driven%20Design-f97316?style=for-the-badge)
![ISA-95](https://img.shields.io/badge/ISA--95%20MES%E2%86%92ERP-f97316?style=for-the-badge)
![Modular Monolith](https://img.shields.io/badge/Modular%20Monolith-f97316?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT%20%2B%20RBAC%20%2B%202FA-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

### 🧭 How I work · Как я работаю

- 🧾 **Operational truth over summaries** — event-sourced systems you can audit and replay
- 📐 **ADR discipline** — every architectural decision is written down with its context and trade-offs
- 🧠 **DDD & bounded contexts** — the model mirrors the business, not the database tables
- ✅ **Test-backed & red-teamed** — vitest + pytest, adversarial review before a change is signed
- 🚢 **I ship the whole thing** — schema, API, UI, and the cost model behind it

> *Сначала текстовый proposal — потом код. Каждое архитектурное решение документирую, проверяю на живом приложении, а не только на `tsc`.*

---

<div align="center">

### 📊 GitHub Stats

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Orangepranik&show_icons=true&hide_border=true&title_color=f97316&icon_color=f97316&text_color=cbd5e1&bg_color=0f172a" alt="github stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Orangepranik&layout=compact&hide_border=true&title_color=f97316&text_color=cbd5e1&bg_color=0f172a&langs_count=8" alt="top languages" />

<br/><br/>

### 🤝 Connect · Контакты

<a href="mailto:bundakilya@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email" /></a>
<a href="https://github.com/Orangepranik"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="github" /></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=120&color=0:f97316,100:0f172a" width="100%" />
