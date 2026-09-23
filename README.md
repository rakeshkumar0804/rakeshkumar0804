<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F0C29,50:302B63,100:24243E&height=220&section=header&text=Rakesh%20Kumar&fontSize=48&fontColor=C9A9FF&animation=fadeIn&fontAlignY=38&desc=Full%20Stack%20%7C%20MERN%20Developer&descAlignY=58&descSize=20" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=24&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=Full+Stack+MERN+Developer;Building+Real-World+Web+Applications;B.Tech+CSE+%40+Parul+University;Open+to+Full+Stack+%2F+Backend+Roles" alt="Typing SVG" />

<br/>

![B.Tech CSE](https://img.shields.io/badge/B.Tech-CSE%20%2F%20Parul%20University-6D28D9?style=flat-square&logo=google-scholar&logoColor=white)
![University](https://img.shields.io/badge/University-Vadodara%2C%20Gujarat-4C1D95?style=flat-square&logo=googlemaps&logoColor=white)
![Location](https://img.shields.io/badge/Based%20In-Gurugram%2C%20India-7C3AED?style=flat-square&logo=googlemaps&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-6D28D9?style=for-the-badge&logo=vercel&logoColor=white)](https://developer-portfolio-nu-rouge.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-4C1D95?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rakesh-kumar-520754246)
[![Email](https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rakeshchauhan6651@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-24243E?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rakeshkumar0804)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=rakeshkumar0804&color=8b5cf6&style=flat-square&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/rakeshkumar0804?color=8b5cf6&style=flat-square&label=Followers)
![Stars](https://img.shields.io/github/stars/rakeshkumar0804?color=8b5cf6&style=flat-square&label=Stars)

</div>

---

### 🟣 About Me

I'm a **Software Developer** specializing in **Full-Stack & Backend Systems**, and a recent **B.Tech CSE graduate from Parul University, Vadodara, Gujarat (May 2026)**. Originally from Gurugram, Haryana, I currently reside there. I focus on building production-grade systems — from deterministic AI-assisted engines to real-time collaborative tools — with an emphasis on clean architecture, correctness under load, and shipping things that actually work end-to-end rather than just tutorial clones.

**💼 Open To:** Software Developer • Full Stack Developer • Backend Developer (Node.js/FastAPI) roles (Fresher, Delhi NCR / Remote)
---

### 🟣 Tech Stack

**Languages:** JavaScript · TypeScript · Python · C++ · SQL

**Frontend:** React.js · Next.js · D3.js · Tailwind CSS · HTML5 · CSS3

**Backend & APIs:** Node.js · Express.js · FastAPI · REST APIs · WebSockets · JWT

**Databases & ORM:** PostgreSQL · MongoDB · MySQL · Prisma

**AI/LLM:** Gemini API · Vector Search

**Systems:** Yjs (CRDT) · WebAssembly · Web Workers

**DevTools:** Git · GitHub · Docker · Postman · Pytest · Vercel · Render

---

### 🟣 Featured Projects

<details >
<summary><b>🔍 TRACE — Temporal Root-cause Analysis & Causal Engine</b></summary>
<br/>

A production incident investigation engine that combines deterministic hypothesis scoring with LLM-assisted reasoning to find root causes faster and more reliably than a naive LLM approach.

| Aspect | Detail |
|---|---|
| **Stack** | Python, FastAPI, PostgreSQL (pgvector), Gemini API, Next.js |
| **Core Feature** | Deterministic hypothesis scoring outside the LLM + code-enforced evidence-citation grounding |
| **Benchmark** | 89.5% root-cause accuracy vs. 73.7% naive LLM baseline across 19 hidden-ground-truth incidents |
| **Status** | Deployed — flagship project |
| **Repository** | [GitHub](https://github.com/rakeshkumar0804/trace-rca-engine) |
| **Live Demo** | [trace-rca-engine.vercel.app](https://trace-rca-engine.vercel.app/) |

Built to show that LLMs are more trustworthy for high-stakes reasoning when wrapped in deterministic scoring and enforced citation grounding, rather than trusted to reason freely.

</details>

<details >
<summary><b>📅 CHRONOS — Constraint-Based Timetable Scheduling Engine</b></summary>
<br/>

A scheduling engine built around a hand-written Constraint Satisfaction Problem (CSP) solver, with natural-language input parsing and an animated visualization of the solver at work.

| Aspect | Detail |
|---|---|
| **Stack** | React, TypeScript, Vite, Node.js, Express, PostgreSQL (Prisma), Gemini API (NL parsing), D3.js, GSAP |
| **Core Feature** | Hand-written CSP backtracking solver using MRV, LCV, and forward-checking |
| **Signature Demo** | 2,328 backtracks (naive) vs. 46 nodes (MRV + LCV) on the same constraint set |
| **Status** | Deployed — flagship project |
| **Repository** | [GitHub](https://github.com/rakeshkumar0804/chronos) |
| **Live Demo** | [chronos-web-kappa.vercel.app](https://chronos-web-kappa.vercel.app/) |

Built to demonstrate classical CS algorithms (CSP solving) applied to a real scheduling problem, with the optimization gap visualized live rather than just claimed.

</details>

<details>
<summary><b>🤝 SyncPad — Real-Time Collaborative Code Editor</b></summary>
<br/>

A multi-language collaborative code editor with real-time sync and in-browser sandboxed code execution — no backend execution server required.

| Aspect | Detail |
|---|---|
| **Stack** | Monaco Editor, Yjs (CRDT), y-websocket, Web Workers, Pyodide (WASM) |
| **Core Feature** | Real-time multi-user editing (CRDT-based) + sandboxed execution for JS/TS (Web Workers), Python (Pyodide/WASM), and HTML/CSS (sandboxed iframe) |
| **Status** | Deployed — y-websocket server on Render, client on Vercel |
| **Repository** | [GitHub](https://github.com/rakeshkumar0804/SyncPad) |
| **Live Demo** | [sync-pad-client.vercel.app](https://sync-pad-client.vercel.app/) |

</details>

<details>
<summary><b>🚨 IncidentHub AI — Engineering Incident Intelligence Platform</b></summary>
<br/>

A platform that correlates signals from GitHub and Sentry to generate AI-assisted incident postmortems, built with production-grade auth and multi-tenancy rather than a single-user demo shortcut.

| Aspect | Detail |
|---|---|
| **Stack** | Node.js, WebSockets, Redis, PostgreSQL, real OAuth |
| **Core Feature** | Multi-tenant RBAC, Redis-backed concurrency control, real-time correlation of GitHub/Sentry signals for AI-assisted postmortems |
| **Status** | Completed — demo-seeded with an "Acme Engineering" org |
| **Repository** | [GitHub](https://github.com/rakeshkumar0804/incidenthub-ai) |
| **Live Demo** | [incidenthub-ai-web.vercel.app](https://incidenthub-ai-web.vercel.app/) |

</details>

---

### 🟣 Experience

**Software Development Intern** · Codetech IT Solutions
`Jan 2026 – Apr 2026`

Built a role-aware **Employee Management System** that replaced spreadsheet-based tracking, supporting employee, manager, and admin workflows.

- Secured CRUD REST APIs for employee, department, and role modules with JWT authentication, RBAC middleware, and request validation
- Used Postman to test operations and validate API responses
- Collaborated with senior developers in code reviews and daily stand-ups, incorporating feedback to improve code quality and API consistency

`Node.js` `Express.js` `MongoDB` `JWT` `REST APIs` `Git` `Postman`

---

### 🟣 Achievements

<div align="center">

| 🏆 Recognition | Details |
|---|---|
| AMENTIS Hackathon | IEEE GTBIT — Apr 2025 |
| CodeKshetra Coding Contest | GeeksforGeeks (GD Goenka) — Apr 2026 |

</div>

---

### 🟣 Certifications

**HackerRank**
![SQL Advanced](https://img.shields.io/badge/HackerRank-SQL%20(Advanced)-6D28D9?style=flat-square&logo=hackerrank&logoColor=white)

**OpenEDG**
![CPA C++](https://img.shields.io/badge/CPA-Programming%20Essentials%20in%20C%2B%2B-4C1D95?style=flat-square&logo=cplusplus&logoColor=white)

**Udemy**
![Cybersecurity](https://img.shields.io/badge/Udemy-Cybersecurity-7C3AED?style=flat-square&logo=udemy&logoColor=white)
![Python](https://img.shields.io/badge/Udemy-Python-7C3AED?style=flat-square&logo=python&logoColor=white)
![Full Stack](https://img.shields.io/badge/Udemy-Full%20Stack%20Development-7C3AED?style=flat-square&logo=udemy&logoColor=white)

---

### 🟣 Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-165%2B%20Solved-6D28D9?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-Profile-4C1D95?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://geeksforgeeks.org/)
[![HackerRank](https://img.shields.io/badge/HackerRank-Profile-7C3AED?style=for-the-badge&logo=hackerrank&logoColor=white)](https://hackerrank.com/)
[![CodeChef](https://img.shields.io/badge/CodeChef-Profile-24243E?style=for-the-badge&logo=codechef&logoColor=white)](https://codechef.com/)

</div>

---

### 🟣 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats-fast.vercel.app/api?username=rakeshkumar0804&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=C9C9C9" width="49%"/>
<img src="https://streak-stats.demolab.com/?user=rakeshkumar0804&theme=tokyonight&hide_border=true&background=0D1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA" width="49%"/>

<img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=rakeshkumar0804&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9C9C9" width="49%"/>

</div>

---

### 🟣 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph-phi-ecru.vercel.app/graph?username=rakeshkumar0804&theme=react-dark&hide_border=true&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=C9A9FF" width="95%"/>

</div>

---

### 🟣 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/rakeshkumar0804/rakeshkumar0804/output/github-contribution-grid-snake-dark.svg" width="95%"/>

</div>



---

### 🟣 Current Focus

```yaml
Learning:
  - Distributed systems & scalable backend architecture
  - Advanced testing practices (Pytest) for production-grade systems
Building:
  - Expanding TRACE with multi-incident correlation
Shipped:
  - TRACE — Root-cause analysis engine
  - CHRONOS — Constraint-based scheduling engine
  - SyncPad — Real-time collaborative code editor
  - IncidentHub AI — Engineering incident intelligence platform
Open To:
  - Software Developer / Full Stack / Backend roles (Fresher, Delhi NCR & Remote)
```

---

### 🟣 Connect With Me

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rakeshchauhan6651@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-4C1D95?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rakesh-kumar-520754246)
[![GitHub](https://img.shields.io/badge/GitHub-24243E?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rakeshkumar0804)
[![Portfolio](https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://developer-portfolio-nu-rouge.vercel.app)

</div>

---

<div align="center">

_"Code is the closest thing we have to magic — write it with intent."_

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243E,50:302B63,100:0F0C29&height=120&section=footer" width="100%"/>

</div>
