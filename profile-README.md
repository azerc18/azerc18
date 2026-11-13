# Hi, I'm Toan 👋

**Java Backend Developer** · 3rd-year Software Engineering student at FPT University (HCMC, Vietnam)

I build secure, well-tested REST APIs with **Java & Spring Boot**, and I care about the parts users don't see:
authentication, concurrency, data integrity and automated testing. I also deploy what I build.

- 🎓 B.Sc. Software Engineering, FPT University (2024 – 2028), 100% full-tuition scholarship
- 💼 Fresher at R2S Academy: owned the authentication service of a team microservices project
- 🌱 Currently learning: system design, distributed systems, cloud deployment
- 🎯 Looking for: Java Backend Developer internship

---

## 🚀 Featured Projects

| Project | What it is | Role | Links |
|---|---|---|---|
| **StudyForge** | AI study platform that turns lecture PDFs/slides into practice exams; every question cites its source page | Solo, full-stack | [Live](https://studyforge.duckdns.org) · [Code](https://github.com/azerc18/study-forge) |
| **LegacyVault** | Digital legacy platform that hands over digital assets to beneficiaries via a Dead Man's Switch | Team of 5, backend: project skeleton, auth, admin | [Live](LEGACYVAULT_LIVE_URL) · [Code](https://github.com/azerc18/legacy-vault) |
| **Personal Finance Tracker** | REST API for income/expense tracking, monthly budgets and PDF reports | Solo, backend | [Code](https://github.com/azerc18/personal-finance-tracker) |

**Highlights**
- Asynchronous LLM generation pipeline with a PostgreSQL job queue (`FOR UPDATE SKIP LOCKED`), parallel chunk processing, JSON validation and retry (StudyForge)
- Refresh token rotation with reuse detection that revokes all sessions on token replay (StudyForge)
- Race condition fix in OTP verification with optimistic locking, verified by Testcontainers tests (UAM)
- N+1 query elimination with JPQL fetch joins: 9 → 4 SQL statements per request (Finance Tracker)
- 300+ unit and integration tests on a single project; CI/CD with GitHub Actions to a self-managed VPS

---

## 🛠 Tech Stack

**Backend:** Java · Spring Boot · Spring Security (JWT, OAuth2) · Spring Data JPA / Hibernate · REST API design
**Database:** PostgreSQL · MySQL · Flyway
**Testing:** JUnit 5 · Mockito · MockMvc · Testcontainers
**DevOps:** Docker · Docker Compose · GitHub Actions · Caddy · Ubuntu VPS
**Frontend (basic):** React · TypeScript · Tailwind CSS

---

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/toanle-backend) · [Email](mailto:phuoctoanletran@gmail.com)
