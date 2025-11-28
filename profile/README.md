<h1 align="center">
  Clarvynn
</h1>
<p align="center">
  <strong>Observability Governance at the Edge</strong><br>
  Stop generating observability data you'll never use.
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/clarvynn/.github/main/assets/logo.jpg" alt="Clarvynn logo" width="100" />
</p>

---

## What Is Clarvynn?

Teams generate terabytes of telemetry they know is wasteful - health checks, debug logs, routine operations. But there's no systematic way to control what gets created at the source.

Clarvynn provides policy-based governance over telemetry generation using CPL (Clarvynn Policy Language):
```yaml
# policy.yaml
sampling:
  base_rate: 0.01  # 1% of routine traffic

conditions:
  - name: server_errors
    when: "status_code >= 500"
  
  - name: slow_requests
    when: "duration_ms > 1000"
  
  - name: critical_endpoints
    when: "path contains '/api/payment'"
```

**Result:** 60-80% cost reduction without losing critical signals.

---

## How It Works

Clarvynn hooks into telemetry generation points and evaluates CPL policies before data leaves your application.

**Starting with:** Python OpenTelemetry adapter for Flask, Django, and FastAPI applications.

**Planned:** Infrastructure log filtering, multi-language support, additional enforcement points.

---

## Why Clarvynn?

Most observability solutions filter telemetry downstream - at collectors or backends. By then you've already paid for network transmission, ingestion, and application overhead.

Clarvynn governs upstream, at the source, before telemetry becomes expensive.

---

## Current Status

**Pre-release.** Building initial implementation:

- Python OpenTelemetry adapter (policy-based sampling at SDK level)
- CPL (Clarvynn Policy Language) specification
- Flask, Django, FastAPI support

---

## Get Involved

Interested in piloting? Email: dheerajvanamala@clarvynn.io

Watch this repository to follow development

---

## License

Apache 2.0

Built by [@dheeraj-vanamala](https://github.com/dheeraj-vanamala)
