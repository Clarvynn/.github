<h1 align="center">
  Clarvynn
</h1>

<p align="center">
  <strong>Application Telemetry, Reimagined.</strong><br>
  Govern what gets observed — before storage, before cost, before chaos.
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/clarvynn/.github/main/assets/logo.jpg" alt="Clarvynn logo" width="100" />
</p>

---

## What is Clarvynn?

**Clarvynn** is a source-level orchestration layer for OpenTelemetry.  
It transforms how developers and SREs manage observability by introducing **Telemetry as Code** — a declarative, language-agnostic approach to define what telemetry gets emitted, when, and why.

Built on top of OpenTelemetry.  
Optimized for clarity, not complexity.

---

## Why Clarvynn?

Clarvynn addresses the root of observability bloat: uncontrolled telemetry generation.  
It gives teams direct control over signal flow — before ingestion, before storage, before cost.

- Telemetry as Code: declarative YAML for structured control  
- No-code instrumentation (Flask, Django, FastAPI supported)  
- Persistent exemplars with source-level trace-metric correlation  
- Native integration with Prometheus, Tempo, Grafana  
- CLI-first, Git-native, built for secure automation  
- Designed to suppress noise while retaining critical signals

---

## What Clarvynn Enables

- Define intent: What signals matter and why  
- Enforce at runtime: Prevent unnecessary telemetry before it leaves the app  
- Capture anomalies reliably, even under sampling  
- Route suppressed data to cold storage (for compliance or audits)  
- Drastically reduce observability costs without losing insights

---

## Current Focus

- Python support (Flask, FastAPI, Django)  
- CLI: `clarvynn run`, `clarvynn init`, `clarvynn validate`  
- OpenTelemetry SDK integration with custom exemplar retention  
- TaC (Telemetry as Code) config validation and runtime injection  
- Production-tested trace-metric correlation via exemplars

---

## Coming Soon

- Language support: Go, Node.js, Java  
- Beyla + Clarvynn integration  
- Log correlation via OTLP  
- Telemetry governance at scale: multi-service, multi-tenant  
- Clarvynn Operator for Kubernetes (with YAML-based control)

---

## The Vision

OpenTelemetry defines the spec.  
Clarvynn defines the experience.

Clarvynn flips observability from reactive analysis to proactive control.  
No more guesswork. No more overload. Just meaningful, intelligent telemetry by default.

If you've ever struggled with dashboards that say too much but explain too little — Clarvynn is for you.

---

## Status

- OSS-first  
- In active development  
- Launching soon  
