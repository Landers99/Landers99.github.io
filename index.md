---
layout: default
title: Jonathan Landrey Smith — Software Engineer
description: .NET & iOS engineer. I build reliable, offline-first systems with SLO-guarded rollouts.
---

# Jonathan Landrey Smith
**.NET & iOS engineer** — I build reliable, offline-first systems and **SLO-guarded rollouts** that auto-rollback in under 2 minutes.

<div style="display:flex; gap:12px; flex-wrap:wrap; margin:12px 0;">
  <a href="https://github.com/Landers99/canary-platform" class="btn">Flagship: Canary Platform</a>
  <a href="https://youtu.be/<demo-id>" class="btn">3-min Demo Video (coming Friday)</a>
  <a href="https://raw.githubusercontent.com/Landers99/resume/main/Jonathan%20Landrey%20Smith%20Resume-master.pdf" class="btn">Resume (PDF)</a>
  <a href="https://raw.githubusercontent.com/Landers99/canary-platform/main/docs/one-pager.pdf" class="btn">One-Pager</a>
</div>

---

## Why this matters
- **Guarded rollouts** with live SLO checks (latency/error).  
- **Auto-rollback < 2 minutes** when error budget burns.  
- **Observability built-in**: traces, metrics, logs, dashboards.

> _I used AI tools for tests/docs only; core logic is hand-written and benchmarked. See `AI_USAGE.md`._

---

## Featured Projects

### 1) Canary Platform — Feature Flags + Auto-Canary with SLO Guardrails
- REST API + .NET SDK; iOS sample client with offline fallback  
- OpenTelemetry dashboards (p50/p95/p99), error rate, RPS  
- Reliability: health checks, retries with jitter, circuit breaker, chaos drill & postmortem  
- **Numbers:** rollback median 1m47s, p95 latency −18% after cache

**Links:**  
- Repo: <https://github.com/Landers99/canary-platform>  
- Demo: *(coming Friday)*
- Case study: *todo*

### 2) redis-lite (BYOX) — protocol + AOF + LRU + mini YCSB
- RESP parser, GET/SET, persistence, eviction  
- Bench graphs vs baseline; property tests

**Links:** <https://github.com/Landers99/redis-lite>

---

## Demos & Posts
- 🎥 Demo #1: Canary rollback under SLO breach (3:12)  
- 📝 Blog #1: SLO-guarded rollouts that save your error budget  
- 🎥 Demo #2 (coming): iOS offline toggle + background refresh

---

## About & Contact
Sammamish, WA · Open to backend, platform, and iOS roles  
**Email:** smithlandrey@gmail.com · **LinkedIn:** <https://www.linkedin.com/in/jonathan-l-smith/>

<style>
a.btn { background:#0366d6; color:white !important; padding:8px 12px; border-radius:8px; text-decoration:none; }
a.btn:hover { opacity:0.9; }
</style>
