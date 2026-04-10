## Hi, I'm Ruslan  
  
In production since 2019. Building open-source tools that close fundamental gaps in the Go ecosystem.  
  
**NIH & Gaps researcher. Open-source tooling author. Tech lead.**  
  
My work is an ecosystem of tools born from real production pain, documented through RFCs, devlogs, and adversarial architecture reviews.  
  
### The Ecosystem (My Public Portfolio)  
  
| Tool | Problem Solved | Artifacts |  
|------|----------------|-----------|  
| **[resilience](https://github.com/thumbrise/resilience)** | Go lacked a composable, zero-dependency resilience toolkit with a Go-native DSL. | [Devlogs](https://thumbrise.github.io/resilience/devlog/), [Adversarial Review](https://thumbrise.github.io/resilience/devlog/007-adversarial-architecture-review), [RFC-002](https://thumbrise.github.io/resilience/references/rfc-002-resilience-stress-debate) |  
| **[multimod](https://github.com/thumbrise/multimod)** | Go has no `cargo-release`. Multi-module monorepos require manual tagging, replace management, and release orchestration. | [Devlogs](https://thumbrise.github.io/multimod/devlog/), [RFC-001](https://thumbrise.github.io/multimod/reference/rfc-001-ecosystem) |  
| **[autosolve](https://github.com/thumbrise/autosolve)** | GitHub issue triage is manual, repetitive, and context-heavy. No self-hosted AI solution existed. | [Devlogs](https://thumbrise.github.io/autosolve/devlog/), [Do Primitive](https://thumbrise.github.io/autosolve/devlog/012-resilience-do-vision) |  
| **[ghset](https://github.com/thumbrise/ghset)** | Setting up a new GitHub repo means clicking through 15 settings tabs. No declarative tool existed for Go. | [Devlog](https://thumbrise.github.io/ghset/devlog/) |  
  
### The Deathbook  
  
Tools emerge from tools. Every GAP gets an entry, every entry eventually gets crossed out.  
  
| # | GAP | Born inside | Status |  
|---|-----|-------------|--------|  
| 1 | Resilience patterns in Go | autosolve | Extracted → [resilience](https://github.com/thumbrise/resilience) |  
| 2 | Task runner lifecycle hooks | resilience | Documented, waiting |  
| 3 | Multi-module release tooling | resilience | Extracted → [multimod](https://github.com/thumbrise/multimod) |  
| 4 | Version bumping from commits | multimod | Planned → version-bumper |  
| 5 | GitHub Release creation | multimod | Planned → ghreleaser |  
| 6 | Declarative repo settings | multimod | Extracted → [ghset](https://github.com/thumbrise/ghset) |  
| 7 | OTel extension reuse | autosolve | Extracted → [otelext](https://github.com/thumbrise/otelext) |  
| 8 | Generic event system | resilience | RFC written → [RFC-002](https://thumbrise.github.io/resilience/references/rfc-002-resilience-stress-debate) |  
| 9 | Fallback chain pattern | resilience | RFC written → [RFC-002](https://thumbrise.github.io/resilience/references/rfc-002-resilience-stress-debate) |  
  
[Full Deathbook with dependency graph and artifact links →](https://thumbrise.github.io/deathbook.html)  
  
### Behind the Code  
  
Since 2019, I've been architecting backend systems in Go (and previously PHP).  
  
- **Leadership**: Led a 6-person backend team, 2023–2025.  
- **Systems**: High-load marketplace, event-driven architecture, observability stack.  
- **Culture**: Introduced adversarial review, ADR processes, and semantic release workflows.  
  
**Stack**: Go, PostgreSQL, Redis, Kafka, Docker.  
  
### Let's Talk  
  
If you're facing ecosystem gaps, scaling engineering culture, or just want to discuss adversarial review over a virtual coffee.  
  
- **Portfolio & Writing**: [thumbrise.github.io](https://thumbrise.github.io)  
- **Contact**: [Email](mailto:ruslan.kokoev.1999@gmail.com) | [Telegram](https://t.me/ruslan_kokoev) | [LinkedIn](https://linkedin.com/in/ruslan-kokoev)
