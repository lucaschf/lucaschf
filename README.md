### Lucas Cristovam

Backend engineer at **Dimensa / Evertec**, focused on **software architecture** — Python, Clean Architecture and Domain-Driven Design.

At work I'm the sole maintainer of a **multi-tenant KYC / anti-fraud platform** (FastAPI · MongoDB), owning everything from bounded-context design to the integration layer with external identity providers.

---

#### 🎬 [HomeFlix](https://github.com/lucaschf/homeflix) — self-hosted streaming server

My playground for applying architecture end to end, in production at home.

- **11 bounded contexts**, modular monolith with Screaming + Clean Architecture
- Cross-context reads go through **consumer-owned ports + ACL adapters**, reactions through **domain events**
- **36 ADRs** documenting every significant decision ([docs](https://lucaschf.github.io/homeflix/))
- 150+ REST endpoints · 4,400+ tests · HLS streaming, automatic intro/credits detection, per-profile age and library gates
- React + TypeScript frontend: [homeflix-web](https://github.com/lucaschf/homeflix-web)

`Python 3.12` `FastAPI` `SQLAlchemy 2` `PostgreSQL` `React` `FFmpeg`

#### Also

- 🖨️ [Riso Themes](https://github.com/lucaschf/riso-themes) — dark VS Code themes printed like a risograph, published on the Marketplace

---

#### What I care about

- Drawing bounded-context boundaries that follow the business, not the database
- Anti-Corruption Layers that *translate* provider data instead of making decisions at the edge
- Measuring coupling (strength × distance × volatility) before splitting or merging modules
- Writing ADRs so decisions outlive the people who made them

📚 I write about these in my [knowledge base](https://lucaschf.github.io/knowledge-base/) (in Portuguese) — strategic DDD, boundaries, coupling, with HomeFlix as a case study.

#### Background

Postgraduate degree in Software Architecture · Degree in Internet Systems Technology

[LinkedIn](https://www.linkedin.com/in/lucas-cristovam)
