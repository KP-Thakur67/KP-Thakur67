<!-- Profile README for https://github.com/KP-Thakur67 -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=240&color=0:0ea5e9,50:6366f1,100:a855f7&section=header&text=Kripal%20Singh&fontColor=ffffff&fontSize=58&fontAlignY=38&desc=Java%20Backend%20Developer%20%7C%20Spring%20Boot%20%7C%20REST%20APIs&descAlignY=58&descSize=20&animation=fadeIn" alt="Kripal Singh - Java Backend Developer, Spring Boot, REST APIs" width="100%" />

<a href="https://github.com/KP-Thakur67">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3200&pause=1000&color=22D3EE&center=true&vCenter=true&width=700&height=45&lines=Aspiring+Java+Backend+Developer;Building+REST+APIs+with+Spring+Boot;Spring+Security+%7C+JWT+%7C+PostgreSQL+%7C+Docker;B.Tech+CSE+%7C+Class+of+2027" alt="Aspiring Java Backend Developer. Building REST APIs with Spring Boot. Spring Security, JWT, PostgreSQL, Docker." />
</a>

**Java · Spring Boot · REST APIs · Spring Security · JWT · PostgreSQL · Docker**

<a href="https://www.linkedin.com/in/kripal-singh-dev/"><img src="https://img.shields.io/badge/LinkedIn-Kripal%20Singh-0A66C2?style=for-the-badge" alt="LinkedIn: Kripal Singh" /></a>
<a href="https://github.com/KP-Thakur67?tab=repositories"><img src="https://img.shields.io/badge/GitHub-KP--Thakur67-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub: KP-Thakur67" /></a>
<img src="https://img.shields.io/badge/Seeking-Backend%20Internships-a855f7?style=for-the-badge" alt="Seeking backend internships" />

</div>

---

## 👨‍💻 About Me

I'm a Computer Science student who builds **Java backends with Spring Boot**: layered REST APIs, JWT-secured endpoints, JPA data models, and Docker-based setups.

| | |
|---|---|
| 🎯 **Role** | Aspiring Java Backend Developer / Software Engineer |
| 🎓 **Education** | B.Tech Computer Science & Engineering, Sanskriti University (graduating 2027) |
| 📍 **Location** | India |
| 🛠️ **Focus** | REST API design, Spring Security + JWT, PostgreSQL, Docker, clean backend architecture |
| 🔭 **Best examples** | [AI Receptionist backend](https://github.com/KP-Thakur67/ai-receptionist) and [InternVerify](https://github.com/KP-Thakur67/offer-letter-verification-backend) |

## 🧱 Backend Architecture I Build

The [AI Receptionist backend](https://github.com/KP-Thakur67/ai-receptionist) follows this request flow (taken from its actual package structure):

```mermaid
flowchart LR
    C([Client]) --> F[JWT filter<br/>Spring Security]
    F --> CT[Controller<br/>REST + validation]
    CT --> S[Service<br/>business logic<br/>tenant guard]
    S --> R[Repository<br/>Spring Data JPA<br/>Specifications]
    R --> DB[(PostgreSQL)]
    CT -. DTOs and mappers .-> C
    S -. custom exceptions .-> E[Global exception handler]
```

## 🛠️ Technical Skills and Technology Stack

<div align="center">

**Core stack, used in my projects**

<img src="https://skillicons.dev/icons?i=java,spring,maven,postgres,mysql,docker,git,github,idea&theme=dark" alt="Java, Spring, Maven, PostgreSQL, MySQL, Docker, Git, GitHub, IntelliJ IDEA" />

**Also used in smaller projects**

<img src="https://skillicons.dev/icons?i=py,ts,html,css,js&theme=dark" alt="Python, TypeScript, HTML, CSS, JavaScript" />

</div>

<details>
<summary><b>Text version of the stack</b> (in case icons do not load)</summary>

- **Core:** Java, Spring Boot, Spring Security, Spring Data JPA, Maven, PostgreSQL, MySQL (configuration option), Docker, Git, GitHub, IntelliJ IDEA
- **Also used:** Python, TypeScript, HTML, CSS, JavaScript

</details>

## ⚙️ Backend Development Skills

| Area | What I have implemented |
|---|---|
| **REST API design** | Resource controllers, request/response DTOs, mappers, pagination, and filtering with JPA Specifications |
| **Security** | Stateless JWT authentication with a Spring Security filter chain, plus role-based access (`ADMIN`, `OWNER`, `DENTIST`, `RECEPTIONIST`) |
| **Backend architecture** | Controller, service, repository, entity, DTO and mapper layers; clinic-scoped (multi-tenant) data access with a tenant guard |
| **Persistence** | Spring Data JPA with PostgreSQL; H2 in-memory for development; MySQL configuration option |
| **Error handling** | Custom exceptions with a global exception handler and a consistent API response format |
| **API documentation** | OpenAPI and Swagger UI through springdoc |
| **Integrations** | Google Gemini API for field extraction, Apache PDFBox for PDF text |
| **Containers** | Multi-stage Dockerfile and Docker Compose with a PostgreSQL 17 service |

## 🧰 Tools and Technologies

<div align="center">

<img src="https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 21" />
<img src="https://img.shields.io/badge/Spring%20Boot-3.5-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot 3.5" />
<img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" alt="Spring Security" />
<img src="https://img.shields.io/badge/JWT-Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Swagger-OpenAPI-85EA2D?style=flat-square&logo=swagger&logoColor=black" alt="Swagger OpenAPI" />
<img src="https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white" alt="Maven" />
<img src="https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini API" />

</div>

## 🚀 Featured Projects

### 🦷 AI Receptionist SaaS: Backend
> Multi-tenant Spring Boot backend for dental clinics: patients, dentists and appointment scheduling.

<img src="https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 21" />
<img src="https://img.shields.io/badge/Spring%20Boot-3.5.6-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot 3.5.6" />
<img src="https://img.shields.io/badge/PostgreSQL-17-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL 17" />
<img src="https://img.shields.io/badge/JWT-Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT" />
<img src="https://img.shields.io/badge/Docker-Compose-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker Compose" />

| ✅ Implemented in the code | 🚧 Not yet in the code |
|---|---|
| Modules for auth, users, clinics, dentists, patients, appointments, dashboard summary and global search | The AI / voice receptionist layer (no AI integration exists in the current source) |
| Four roles and a tenant guard that keeps each clinic's data separate | Automated test suite beyond the default context-load test |
| Appointment statuses (`BOOKED`, `CONFIRMED`, `COMPLETED`, `CANCELLED`, `NO_SHOW`) with conflict detection | |
| Filtering with JPA Specifications, pagination, Swagger UI | |
| Docker Compose for app and database, with a multi-stage Dockerfile | |

🔗 **[View repository](https://github.com/KP-Thakur67/ai-receptionist)**

---

### 🔎 InternVerify: Offer Letter Verification System
> Full-stack app that helps candidates check whether a job offer letter looks genuine.

<img src="https://img.shields.io/badge/Java-17-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 17" />
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
<img src="https://img.shields.io/badge/JWT-Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT" />
<img src="https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini API" />
<img src="https://img.shields.io/badge/H2%20%7C%20MySQL-Database-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="H2 and MySQL" />

| ✅ Implemented in the code | 🚧 Planned (listed as future work in the repo) |
|---|---|
| Upload an offer letter PDF, extract its text with PDFBox, then extract fields (company, CIN, email, salary) with the Gemini API | Live MCA API integration (today it checks a bundled registry dataset) |
| Rule-based verification score: company match, email-domain match, salary sanity check, and MCA registry match (CIN or company name) | Advanced AI fraud detection |
| JWT register/login, an admin API for managing companies, public company-search and scam-report endpoints | Cloud deployment (AWS / Render) |
| Plain HTML/CSS/JS frontend served by the app; H2 in-memory database for development | User dashboard and analytics |

🔗 **[View repository](https://github.com/KP-Thakur67/offer-letter-verification-backend)**

---

### 🛡️ Cynbit Backend Audit
> Passive, ethical backend and security review of a public website, written as an internship assessment.

<img src="https://img.shields.io/badge/Docs-Markdown-083FA1?style=flat-square&logo=markdown&logoColor=white" alt="Markdown" />
<img src="https://img.shields.io/badge/Reference%20Code-Java%2021-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 21 reference code" />

- Findings are labelled **Confirmed**, **Partially verified** or **Hypothesis**, so each claim traces back to evidence.
- Includes a sanitized evidence log and a Spring Boot reference implementation of the recommended fixes. The reference code is illustrative, not the audited site's code.

🔗 **[View repository](https://github.com/KP-Thakur67/cynbit-backend-audit)**

<!--
  TODO: RepoAudit AI - add only after the real repository URL is known.
  ### RepoAudit AI
  > One-line description based on the repository README
  | Implemented | Planned |
  🔗 **[View repository](https://github.com/KP-Thakur67/REPO_NAME)**
-->

## 📊 GitHub Statistics

<div align="center">

<a href="https://github.com/KP-Thakur67"><img src="https://github-readme-stats.vercel.app/api?username=KP-Thakur67&show_icons=true&hide_border=true&bg_color=0D1117&title_color=22D3EE&icon_color=A855F7&text_color=C9D1D9&text_bold=false" alt="KP-Thakur67 GitHub stats card (see the live numbers on my GitHub profile)" width="48%" /></a>
<a href="https://github.com/KP-Thakur67?tab=repositories"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KP-Thakur67&layout=compact&hide_border=true&bg_color=0D1117&title_color=22D3EE&text_color=C9D1D9&langs_count=6" alt="Most used languages card (Java is my main language; see my repositories)" width="48%" /></a>

<sub>Cards are generated live by github-readme-stats. If they do not load, see my <a href="https://github.com/KP-Thakur67?tab=repositories">repositories</a> directly.</sub>

</div>

## 🔥 Contribution Streak

<div align="center">

<a href="https://github.com/KP-Thakur67"><img src="https://streak-stats.demolab.com?user=KP-Thakur67&hide_border=true&background=0D1117&ring=A855F7&fire=22D3EE&currStreakLabel=22D3EE&sideLabels=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=8B949E" alt="GitHub contribution streak card (see my profile for current numbers)" width="80%" /></a>

</div>

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KP-Thakur67/KP-Thakur67/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/KP-Thakur67/KP-Thakur67/output/github-snake.svg" />
  <img alt="Contribution snake animation, generated daily by a GitHub Actions workflow" src="https://raw.githubusercontent.com/KP-Thakur67/KP-Thakur67/output/github-snake-dark.svg" width="100%" />
</picture>

</div>

## 🏆 Assignments and Case Studies

These are real submissions in my public repositories:

- 🧩 [**Bynry backend case study**](https://github.com/KP-Thakur67/bynry-backend-case-study): backend engineering case study with a code review and debugging section.
- 🛒 [**1Fi Marketplace**](https://github.com/KP-Thakur67/onefi-marketplace): full-stack SDE intern assignment with a TypeScript frontend, REST APIs and PostgreSQL (product variants and EMI plan selection).
- 💸 [**Affiliate Payout System**](https://github.com/KP-Thakur67/affiliate-payout-system): low-level design in Python covering advance payout, reconciliation, withdrawal control and recovery workflow.

<!-- Add certifications here only when you have a verifiable credential link. -->

## 🌱 Currently Learning

- ☁️ Cloud deployment of Spring Boot services (AWS / Render)
- 🧪 Automated testing for service and security layers
- 🧠 LLM agents, through [llm-agent-world-cl](https://github.com/KP-Thakur67/llm-agent-world-cl)
- 📐 Low-level system design patterns

## 🤝 Let's Connect

<div align="center">

Open to talking about **Java, Spring Boot and backend engineering**, and to internship or entry-level opportunities.

<a href="https://www.linkedin.com/in/kripal-singh-dev/"><img src="https://img.shields.io/badge/Connect%20on-LinkedIn-0A66C2?style=for-the-badge" alt="Connect on LinkedIn" /></a>
<a href="https://github.com/KP-Thakur67?tab=repositories"><img src="https://img.shields.io/badge/Browse-Repositories-6366f1?style=for-the-badge&logo=github&logoColor=white" alt="Browse repositories" /></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:0ea5e9,50:6366f1,100:a855f7&section=footer" alt="" width="100%" />

</div>
