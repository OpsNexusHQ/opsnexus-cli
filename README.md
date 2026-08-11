# OpsNexus CLI (`opsnexus-cli`)

[![Release](https://img.shields.io/badge/release-v0.5.0-blue.svg)](https://github.com/OpsNexusHQ/opsnexus-cli/releases/tag/v0.5.0)
[![Go Version](https://img.shields.io/badge/go-1.25+-00ADD8.svg)](https://golang.org)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

Command-line interface utility for managing **OpsNexus** infrastructure, querying telemetry, inspecting firing alerts, and registering nodes directly from the terminal.

---

## ⚡ Status & Roadmap (v0.5.0)

> [!NOTE]
> `opsnexus-cli` is currently in **preview stage** as part of the v0.5.0 release candidate suite. Full feature completion is scheduled for v0.6.0.

### Planned Commands (v0.6.0)
```bash
opsnexus status               # Check backend status and connectivity
opsnexus agent list           # List registered agents and health
opsnexus agent inspect <id>   # Display detailed telemetry for an agent
opsnexus alert list           # List active firing and acknowledged alerts
opsnexus alert ack <id>       # Acknowledge an incident with comment
```

---

## 🚀 Building from Source

```bash
git clone https://github.com/OpsNexusHQ/opsnexus-cli.git
cd opsnexus-cli
go build -o opsnexus ./cmd/opsnexus
```

---

## 📄 License

Part of the [OpsNexus](https://github.com/OpsNexusHQ) ecosystem. Licensed under the MIT License.
