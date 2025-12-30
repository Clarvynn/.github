<h1 align="center">
  Clarvynn
</h1>
<p align="center">
  <strong>Source Governance for OpenTelemetry</strong><br>
  Tail sampling decides what to keep. Source Governance decides what should exist.
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

We operate on the principle that **observability is a signal quality problem, not a storage problem.** While auditability demands retention, the overwhelming volume of routine telemetry should never consume the **compute and human attention** reserved for critical signals.

Clarvynn exists to solve the "Missing Tooling Gap" in the OpenTelemetry ecosystem: **Source-Level Governance.** Instead of dumping unsampled data into collectors, Clarvynn empowers engineering teams to define **Explicit Intent** and enforce **Deferred Head Sampling** directly within the application process.

**The Goal:** Capture 100% of critical context (errors, latency, golden signals) while reducing routine telemetry volume before it consumes network or compute resources.

---
## The Ecosystem

Clarvynn currently supports Python, with other languages on the roadmap.

### Application Adapters

| Component | Status | Description |
| :--- | :--- | :--- |
| **[clarvynn-otel-python](https://github.com/clarvynn/clarvynn)** | **Available** | Hooks into OTel Python SDK to provide CPL evaluation and the log buffer. |
| **clarvynn-otel-go** | *Planned* | Native Go adapter for high-performance services. |
| **clarvynn-otel-java** | *Planned* | Java agent extension for enterprise workloads. |

---

## Community & Governance

Clarvynn is an Open Source project designed to complement OpenTelemetry. We actively track upstream SIGs (Config, Sampling) to ensure our architecture aligns with the future of the standard.

* **Contribution:** We welcome feedback, bug reports, and code contributions.

---

## Contact

* **Contact:** [dheerajvanamala@clarvynn.io](mailto:dheerajvanamala@clarvynn.io)

---

<p align="center">
  <sub>Built by <a href="https://github.com/dheeraj-vanamala">@dheeraj-vanamala</a></sub>
</p>
