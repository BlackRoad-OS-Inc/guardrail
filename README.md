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
