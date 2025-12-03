<h1 align="center">
  Clarvynn
</h1>
<p align="center">
  <strong>A Control Plane for OpenTelemetry</strong><br>
  Enforcing Purposeful Observability at the Edge.
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/clarvynn/.github/main/assets/logo.jpg" alt="Clarvynn logo" width="100" />
</p>

<p align="center">
  <a href="https://clarvynn.io">Website</a> • 
  <!-- <a href="https://discord.gg/clarvynn">Community</a> •  -->
  <a href="https://github.com/clarvynn/clarvynn">Python Adapter</a>
</p>

---

## The Mission

We operate on the principle that **observability is a signal-to-noise problem, not a storage problem.** While auditability demands retention, the overwhelming volume of routine telemetry should never consume the **compute and human attention** reserved for critical signals.

Clarvynn exists to solve the "Missing Tooling Gap" in the OpenTelemetry ecosystem: **Source-Level Governance.** Instead of dumping unsampled data into collectors, Clarvynn empowers engineering teams to define **Explicit Intent** and enforce **Deferred Head Sampling** directly within the application process.

**The Goal:** Capture 100% of critical context (errors, latency, golden signals) while aggressively sampling the routine noise before it consumes network or compute resources.

---
## The Ecosystem

Clarvynn is designed as a language-agnostic control plane. Currently, the reference implementation is available for Python, with other languages on the roadmap.

### Application Adapters

| Component | Status | Description |
| :--- | :--- | :--- |
| **[clarvynn-otel-python](https://github.com/clarvynn/clarvynn)** | **Beta** | **Available Now.** Hooks into OTel Python SDK to provide CPL evaluation and the log buffer. |
| **clarvynn-otel-go** | *Planned* | Native Go adapter for high-performance services. |
| **clarvynn-otel-java** | *Planned* | Java agent extension for enterprise workloads. |

### Core Specifications

| Component | Status | Description |
| :--- | :--- | :--- |
| **[CPL (Clarvynn Policy Language)](https://github.com/clarvynn/clarvynn/blob/main/docs/CPL_REFERENCE.md)** | **Spec** | The universal schema for defining observability intent. Currently hosted within the Python adapter repository. |

---

## Community & Governance

Clarvynn is an Open Source project designed to complement OpenTelemetry. We actively track upstream SIGs (Config, Sampling) to ensure our architecture aligns with the future of the standard.

* **Validation:** Our architectural approach addresses gaps identified by OpenTelemetry Governance Committee member.
* **Contribution:** We welcome contributors who want to help build the standard for Purposeful Observability.

---

## 📬 Contact

* **Pilot Inquiries:** [dheerajvanamala@clarvynn.io](mailto:dheerajvanamala@clarvynn.io)

---

<p align="center">
  <sub>Built by <a href="https://github.com/dheeraj-vanamala">@dheeraj-vanamala</a></sub>
</p>
