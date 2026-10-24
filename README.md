```
$ whoami
> Milad Nalbandi Rezaei
> Senior Software Engineer · backend platforms & AI developer tooling
> Düsseldorf, Germany
```

[![Website](https://img.shields.io/badge/website-miladnalbandi.com-1f6feb?style=flat-square)](https://miladnalbandi.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-milad--nalbandi-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/milad-nalbandi-562281165)
[![Email](https://img.shields.io/badge/email-m.nalbandi.r%40gmail.com-d14836?style=flat-square&logo=gmail&logoColor=white)](mailto:m.nalbandi.r@gmail.com)

I build backend systems for a living (8+ years; Java/Kotlin, PHP/Symfony, Python) and, in the open,
**tools that make AI coding agents write tested, reviewable code** instead of plausible-looking code.

---

### ⚓ [keel](https://github.com/MiladNalbandi/keel-v2) — AI agents write *tested* code for your project; you approve the important steps

<a href="https://github.com/MiladNalbandi/keel-v2"><img src="https://raw.githubusercontent.com/MiladNalbandi/keel-v2/main/docs/keel-tui.gif" width="760" alt="keel's terminal app running a flow"></a>

```
 "show each player's rank"
   1. spec    an agent writes what to build                ◆ you approve
   2. test    an agent writes a test that fails
   3. code    an agent writes code until the test passes   ◆ you approve
   4. review  agents check the whole change                ◆ you approve
   → tested commits on a new branch. keel never pushes.
```

- One Docker container: web dashboard, terminal app, and an **MCP server** for your own AI tools
- Works with **Claude, Codex, GitHub Copilot, Vertex AI** or local models (Ollama, LM Studio, vLLM)
- Small core + plugins (Git, CI/CD, database, code review, Jira), a quality page that tracks each flow per model, and a token budget bar
- Started as a [Claude Code plugin](https://github.com/MiladNalbandi/keel) whose hooks enforce RED → GREEN per acceptance criterion

`Kotlin` · `Python` · `TypeScript` · `MCP` · `Docker`

---

### Other open source

<table>
<tr>
<td width="50%" valign="top">

#### 🎮 [Ludus Engine](https://github.com/MiladNalbandi/ludus-engine)
Open-source **backend for 2D games**: content and player state served over a cacheable HTTP API, so a balance change ships without a new build. Hexagonal codebase where the build itself enforces the layering (framework-free domain modules + ArchUnit). *Early: works end to end for one content type.*

`Java 21` · `Spring Boot` · `PostgreSQL` · `AGPL-3.0`

</td>
<td width="50%" valign="top">

#### 🔒 [Latch](https://github.com/MiladNalbandi/latch)
A private clipboard history for macOS: ⌘⇧V opens a Spotlight-style panel with text, images, files, links and code — encrypted on-device, no account, no network. Native, no Electron. `brew install --cask latch`

`Swift` · `SwiftUI` · `AppKit` · `GPL-3.0`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🖨️ [zpl-renderer](https://github.com/MiladNalbandi/zpl-renderer) · [ZPL Label Viewer](https://github.com/MiladNalbandi/zpl-label-viewer)
A pure-JVM **ZPL II label renderer** (text, Code 128, QR, Data Matrix, graphics) — no printer, no Labelary, no data leaving the machine — plus a JetBrains plugin that previews labels in the editor.

`Kotlin` · `JitPack` · `IntelliJ Platform` · `Apache-2.0`

</td>
<td width="50%" valign="top">

#### 📦 [Composer Command Helper](https://plugins.jetbrains.com/plugin/27215-composer-command-helper)
PhpStorm plugin for Composer: one-click commands and dependency install/remove inside the IDE, non-blocking via coroutines. **~600 active users** on the JetBrains Marketplace.

`Kotlin` · `Coroutines` · `IntelliJ Platform`

</td>
</tr>
</table>

---

### Day job

**Senior Software Engineer @ METRO Markets** (since 2022) — delivery-domain backend services across five
European markets (DDD, hexagonal, RabbitMQ-backed integrations with carriers), and the team's AI ambassador:
internal agents over MCP and spec-driven development with Claude Code.

```
Backend   Java · Kotlin · Spring Boot · PHP 8 / Symfony · Python / FastAPI · SQL
Async     RabbitMQ · Kafka · Symfony Messenger · Pub/Sub
AI        MCP · agent & tool design · RAG · LLM eval loops · Claude Code · Codex
Infra     GCP · Kubernetes · Docker · GitHub Actions · Grafana / Prometheus
```

---

**More:** [miladnalbandi.com](https://miladnalbandi.com) (terminal-style CV, served from Kotlin/Ktor) ·
[blog](https://miladnalbandi.com/blog) · [LinkedIn](https://www.linkedin.com/in/milad-nalbandi-562281165)
