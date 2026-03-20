# GuardRail — BlackRoad Road Fleet

**Proprietary Software — BlackRoad OS, Inc.**

## What is GuardRail?

GuardRail is BlackRoad's sovereign AI safety and content guardrails solution, forked from BlackRoad (custom). It runs on BlackRoad hardware as part of the Road Fleet — our self-hosted infrastructure stack that eliminates cloud dependency.

## Why GuardRail?

Commercial AI safety services are black boxes — you don't know what they filter or why, and they can change rules without notice. GuardRail is our own safety layer built from the ground up, running locally with transparent rules we control. Every guardrail decision is auditable.

## Part of the Road Fleet

| Road Name | Upstream | Purpose |
|-----------|----------|---------|
| RoadCode | Gitea | Git hosting |
| OneWay | Caddy | TLS edge & reverse proxy |
| TollBooth | WireGuard | Encrypted mesh VPN |
| PitStop | Pi-hole | DNS filtering |
| Passenger | Ollama | Local AI inference |
| RearView | Qdrant | Vector database |
| Curb | MinIO | Object storage |
| RoundAbout | Headscale | Mesh coordination |
| CarPool | NATS | Pub/sub messaging |
| OverPass | n8n | Workflow automation |
| BackRoad | Portainer | Container management |
| GuardRail | (custom) | AI safety guardrails |

## License

This software is proprietary to BlackRoad OS, Inc. See [LICENSE](LICENSE) for full terms.

Public code is not open source. You may view and learn from this code. Commercial use, forking, and redistribution are prohibited.

---

**BlackRoad OS — Pave Tomorrow.**

*Copyright 2024-2026 BlackRoad OS, Inc. All Rights Reserved.*
