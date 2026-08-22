```
╭──────────────────────────────────────────────────────────────────────────────╮
│                                                                              │
│   $ whoami                                                                   │
│   > Milad Nalbandi Rezaei                                                    │
│   > Senior Software Engineer · Java / Kotlin · PHP                          │
│   > Düsseldorf, Germany · Open to Remote within Germany                      │
│                                                                              │
╰──────────────────────────────────────────────────────────────────────────────╯
```

[![Website](https://img.shields.io/badge/website-miladnalbandi.com-1f6feb?style=flat-square)](https://miladnalbandi.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-milad--nalbandi-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/milad-nalbandi-562281165)
[![Email](https://img.shields.io/badge/email-m.nalbandi.r%40gmail.com-d14836?style=flat-square&logo=gmail&logoColor=white)](mailto:m.nalbandi.r@gmail.com)

---

### `--- Summary ---`

Senior Software Engineer with **8+ years** of expertise in **Java and PHP**, specializing in event-driven microservices, RESTful APIs, and production AI agent systems on platforms with no acceptable downtime window. Proven track record of owning delivery-domain services across **five European markets** on Domain-Driven Design and hexagonal boundaries, standardizing **15+ third-party integrations** behind asynchronous queues, and leading an internal AI agent platform on **Google ADK** and **Vertex AI** with MCP-grounded tooling. Strong focus on asynchronous architectures, observability, and high-quality, well-tested code in production, with hands-on experience mentoring engineers and running enablement workshops across cross-functional teams.

---

### `--- Technical Expertise ---`

```
Backend & Languages   │ Java · Kotlin · Spring Boot · JPA · Hibernate
                      │ PHP 8 (Symfony 7, Laravel, Doctrine ORM) · Python (FastAPI, asyncio) · SQL · JavaScript · React
APIs & Architecture   │ RESTful API design · SDK design · DDD · Hexagonal Architecture
                      │ Event-driven microservices · Retry, failover & graceful degradation
Async & Concurrency   │ RabbitMQ · Kafka · Symfony Messenger · Google Pub/Sub
                      │ Queue & worker pipelines · Cron/scheduled jobs · Coroutines
AI & Agents           │ Google ADK · Vertex AI · Vertex AI Vector Search · Model Context Protocol (MCP)
                      │ Agent & tool design · RAG pipelines · LLM eval loops · Spec-driven dev with Claude Code & Codex
Databases & ORMs      │ PostgreSQL · MySQL · ClickHouse · Redis · Elasticsearch
                      │ SQL optimization · JPA · Hibernate · Doctrine ORM
Cloud & DevOps        │ GCP (GKE, Pub/Sub, Cloud Functions, IAM) · Kubernetes · Docker
                      │ Argo CD · GitLab CI/CD · GitHub Actions · Jenkins
Observability         │ Grafana · Prometheus · Google Cloud Monitoring · Sentry
                      │ Structured logging · Rate-of-change alerting
Testing & Quality     │ JUnit · PHPUnit · pytest · Code coverage · Quality gates · TDD · Code reviews
```

---

### `--- Currently ---`

**Senior Software Engineer @ METRO Markets GmbH** · *Dec 2022 – Present*
Backend platform engineering and internal AI agent platform for delivery management across **five European markets**.

- ▸ Architected shipment & return services on **DDD + hexagonal boundaries** across five European markets, cutting end-to-end processing time by **20%** via queue-backed workers and targeted profiling.
- ▸ Designed a standardized integration adapter pattern over **RabbitMQ** with retry, failover, and graceful degradation — onboarded **15+ third-party providers**, reducing per-provider onboarding time by **30%**.
- ▸ **Internal tracking SaaS:** designed the SDK + microservice backbone establishing a single source of truth for order state across customer-facing apps and ops tools, with resolvers running behind queues and workers.
- ▸ Shipped a production support agent on **Google ADK + Vertex AI**, integrated over internal systems through **MCP** and deployed into Slack, answering operational questions daily for the delivery team.
- ▸ Built a **RAG pipeline** over the codebase and a Sentry-integrated agent that diagnoses production errors against source, cutting incident tracing time — plus agents for order follow-up and automated report generation, and an agent skill that turns onboarding a new integration into a guided workflow.
- ▸ Defined **AI usage governance** and introduced spec-driven development company-wide at Product & Tech Day; ran workshops on agent design and MCP as the team's AI ambassador.
- ▸ Built observability with **Grafana, Prometheus, Cloud Monitoring** (rate-of-change alerting cut incident detection time by **15%**); runs on **Kubernetes** with automated CI/CD and quality gates, and mentors junior engineers in Scrum delivery.

---

### `--- Open Source ---`

<table>
<tr><td>

#### ⭐ [Ludus Engine](https://github.com/MiladNalbandi/ludus-engine) — *featured*
**Open-source backend engine for 2D games** · Java 21 + Spring Boot · AGPL-3.0

Author maps, entities and behaviours as data in a web editor; your game fetches them at runtime and builds the level from them — ship a balance change without shipping a build. Hexagonal (ports & adapters) codebase where the layering is enforced by the build itself: `engine-domain`/`engine-application` declare no framework dependencies, and ArchUnit guards dependency direction and field injection. Content is JSON validated against a single shared JSON Schema used by the engine, editor, and every client.

`Java` · `Spring Boot` · `PostgreSQL` · `Hexagonal Architecture` · `ArchUnit` · `Docker`

</td></tr>
</table>

<table>
<tr>
<td width="33%" valign="top">

#### 🔒 [Latch](https://github.com/MiladNalbandi/latch)
*The friendly, private clipboard for macOS*

A menu-bar utility that records clipboard history and brings any past copy back instantly through a Spotlight-style panel (**⌘⇧V**) — text, rich text, images, files, links, colors, and code, encrypted on-device with no account, no network, no telemetry. Native AppKit + SwiftUI, no Electron.

`Swift` · `SwiftUI` · `AppKit`

</td>
<td width="33%" valign="top">

#### 🖨️ [ZPL Engine](https://github.com/MiladNalbandi/zpl-renderer)
*JetBrains Plugin & Renderer*

Privacy-by-design ZPL label preview for **PCI/PII-sensitive environments**. Existing tools require uploading shipment data externally or depend on physical printers. ZPL Engine ships an IDE plugin for in-editor preview and an **offline backend renderer** — no external calls, no data exposure.

`Kotlin` · `JetBrains SDK`

</td>
<td width="33%" valign="top">

#### 📦 [Composer Command Helper](https://plugins.jetbrains.com/plugin/27215-composer-command-helper)
*PhpStorm Plugin · JetBrains Marketplace · ~600 active users*

Composer package management inside the IDE — one-click commands, dependency install/remove, project-specific execution. Built with **Kotlin + Coroutines** for non-blocking, async execution. Used in production by ~600 PHP developers.

`Kotlin` · `Coroutines` · `IntelliJ Platform`

</td>
</tr>
</table>

---

### `--- Languages ---`

| Language     | Level             |
| ------------ | ----------------- |
| English      | C1 · Fluent        |
| German       | A2 · Basic         |
| Persian      | Native             |
| Azerbaijani  | Native             |
| Turkish      | B1 · Intermediate  |

---

### `--- Find me elsewhere ---`

- 🌐 **Live CV** — [miladnalbandi.com](https://miladnalbandi.com) *(terminal-style, served from a Kotlin/Ktor backend)*
- 💼 **LinkedIn** — [milad-nalbandi-562281165](https://www.linkedin.com/in/milad-nalbandi-562281165)
- 🛠 **JetBrains Marketplace** — [Composer Command Helper](https://plugins.jetbrains.com/plugin/27215-composer-command-helper)

```
$ echo "Open to senior backend / platform roles in Germany (remote-friendly)."
```
