<!-- BlackRoad SEO Enhanced -->

# guardrail

> Part of **[BlackRoad OS](https://blackroad.io)** — Sovereign Computing for Everyone

[![BlackRoad OS](https://img.shields.io/badge/BlackRoad-OS-ff1d6c?style=for-the-badge)](https://blackroad.io)
[![BlackRoad-OS-Inc](https://img.shields.io/badge/Org-BlackRoad-OS-Inc-2979ff?style=for-the-badge)](https://github.com/BlackRoad-OS-Inc)

**guardrail** is part of the **BlackRoad OS** ecosystem — a sovereign, distributed operating system built on edge computing, local AI, and mesh networking by **BlackRoad OS, Inc.**

### BlackRoad Ecosystem
| Org | Focus |
|---|---|
| [BlackRoad OS](https://github.com/BlackRoad-OS) | Core platform |
| [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc) | Corporate |
| [BlackRoad AI](https://github.com/BlackRoad-AI) | AI/ML |
| [BlackRoad Hardware](https://github.com/BlackRoad-Hardware) | Edge hardware |
| [BlackRoad Security](https://github.com/BlackRoad-Security) | Cybersecurity |
| [BlackRoad Quantum](https://github.com/BlackRoad-Quantum) | Quantum computing |
| [BlackRoad Agents](https://github.com/BlackRoad-Agents) | AI agents |
| [BlackRoad Network](https://github.com/BlackRoad-Network) | Mesh networking |

**Website**: [blackroad.io](https://blackroad.io) | **Chat**: [chat.blackroad.io](https://chat.blackroad.io) | **Search**: [search.blackroad.io](https://search.blackroad.io)

---


> GuardRail — Sovereign uptime monitoring. Fork of Uptime Kuma. Fleet health for 41 pages, 7 nodes, 18 domains. Proprietary BlackRoad OS.

Part of the [BlackRoad OS](https://blackroad.io) ecosystem — [BlackRoad-OS-Inc](https://github.com/BlackRoad-OS-Inc)

---

# GuardRail — Sovereign Uptime Monitoring

> Forked from [Uptime Kuma](https://github.com/louislam/uptime-kuma). Fleet health visualization for BlackRoad OS.

**GuardRail** monitors every service across the BlackRoad fleet — 41 web pages, 7 nodes, 15 Workers, 18 domains.

## Features
- **HTTP/TCP/DNS monitoring** for all endpoints
- **Status pages** at status.blackroad.io
- **Alerts** via RoundTrip chat (no Slack dependency)
- **Fleet dashboard** showing node health, temps, disk, load
- **Incident history** with root cause tracking

## Monitored Services
- 41 blackroad.io pages
- 7 fleet nodes (5 Pi + 2 DO)
- 18 custom domains
- 15 self-hosted Workers on Octavia
- Ollama inference endpoints
- Qdrant vector DB
- PostgreSQL databases

## Deploy
```bash
docker compose up -d  # runs on Alice
# Access at monitor.blackroad.io
```

---
© 2026 BlackRoad OS, Inc. Fork of Uptime Kuma (MIT). BlackRoad customizations proprietary.
