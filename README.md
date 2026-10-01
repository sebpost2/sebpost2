# Sebastián Postigo

**Full-stack developer · Python · Java · TypeScript · Odoo 19** — Arequipa, Peru (UTC-5).
Open to full-time, contract and remote roles.

🌐 [sebpostigo.vercel.app](https://sebpostigo.vercel.app) · 📄 [CV (ES)](https://sebpostigo.vercel.app/cv.pdf) / [CV (EN)](https://sebpostigo.vercel.app/cv-en.pdf) · 💼 [LinkedIn](https://www.linkedin.com/in/sebpostigo) · 📧 sebpost02@gmail.com

---

### Experience

**Odoo 19 Developer** — Inbrasol Web Services · *Nov 2025 – Apr 2026*
- Custom Odoo 19 modules for 8+ clients (veterinary and IT-hardware retail, facilities services, ISO consulting, mining valves): RUC/DNI lookup, supervisor-approved purchase requests, a supplier price comparison for bulk purchases, product laboratories, dining reservations.
- Built an ISO certification quoting engine (CPQ) that prices by sites, headcount and ISO standard, with nine dynamic proposal and contract templates.
- QWeb invoice, ticket, inventory and transport formats; ported modules from earlier Odoo versions to Odoo 19.
- Built GRE Tipo 31 (SUNAT carrier waybill) XML generation in UBL 2.1 from transport orders (not yet validated with SUNAT).

**Software Developer Intern** — Neo Plus Business · *Feb – May 2025*
- Reorganized a Laravel 11 REST API by domain; JWT + SCRAM-SHA-256 auth with the cryptography kept in the database layer.
- Cut API response sizes by ~60% by replacing JSON with MessagePack.

### Selected projects

| Project | What it shows | Proof |
|---|---|---|
| [rental-dashboard-spring](https://github.com/sebpost2/rental-dashboard-spring) | Java 25 / Spring Boot 4 API: Flyway, JPA, Spring Security (JWT in httpOnly cookie), SQL-side reports | 65 tests on Testcontainers, 80% coverage gate · [demo](https://rental-dashboard-java.vercel.app/login) |
| [sale_tiered_pricing](https://github.com/sebpost2/sale_tiered_pricing) | Installable Odoo 19 addon: volume-discount tiers + aggregate margin guard | 18 TransactionCase tests, runs in Docker |
| [job-alert-agent](https://github.com/sebpost2/job-alert-agent) | Python pipeline: scrapes job boards every 12h, LLM scoring, Notion + Telegram digest | 168 pytest tests, 97% coverage, mypy --strict · [dashboard](https://bevel-rose-8cb.notion.site/Job-Alert-Agent-Live-Dashboard-3674d098c1e7807aafe0cf6a3507e526) |
| [invoice-chat](https://github.com/sebpost2/invoice-chat) | LLM agent with tool use (SQL, aggregates) over receipt data | 24 Promptfoo eval cases · [demo](https://invoice-chat-zeta.vercel.app) |
| [invoice-extractor](https://github.com/sebpost2/invoice-extractor) | Receipt photo → vision LLM → structured data; semantic search on pgvector (HNSW) | CI on every push · [demo](https://invoice-extractor-gules.vercel.app) |

More (with problem → approach → result write-ups) at **[sebpostigo.vercel.app](https://sebpostigo.vercel.app)**.

### Skills

**Backend:** Python (FastAPI, Pydantic), Java (Spring Boot, JPA), PHP (Laravel), Odoo 19 (ORM, QWeb), REST, JWT/RBAC
**Data & AI:** PostgreSQL, pgvector, SQL, Prisma, DuckDB · LLM tool use, embeddings, evals (Promptfoo), Groq, Vercel AI SDK
**Frontend:** TypeScript, React, Next.js, Tailwind
**Quality & infra:** pytest, JUnit + Testcontainers, Vitest, Playwright, mypy --strict · GitHub Actions, Docker, Vercel, Render

### Education

B.Sc. Computer Science — Universidad Católica San Pablo, Arequipa (2020 – 2025) · Spanish (native), English (intermediate)
Also: NASA Space Apps 2023 & 2024 · lead programmer on [Cat-Nip](https://github.com/sebpost2/CAT-NIP-PostreV2), a 2D Godot game.
