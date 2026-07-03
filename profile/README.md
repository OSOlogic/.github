<div align="center">

<img src="https://raw.githubusercontent.com/OSOlogic/platform/main/logos/osologic_logo.png" alt="OSOlogic" width="320">

### The Modern & Open Automation Platform

*An open-source hardware and software initiative to modernize industrial and home automation —
bridging traditional PLC / SCADA / HMI systems and modern, software-defined computing.*

[![Website](https://img.shields.io/badge/web-osologic.com-f48c06.svg)](https://osologic.com)
[![Release: 1.0 Beta](https://img.shields.io/badge/release-1.0%20Beta-f48c06.svg)](https://github.com/OSOlogic/platform#current-status)
[![License: AGPL-3.0](https://img.shields.io/badge/license-AGPL--3.0-blue.svg)](https://github.com/OSOlogic/platform/blob/main/LICENSE)
[![Platform](https://img.shields.io/badge/repo-platform-333.svg)](https://github.com/OSOlogic/platform)

</div>

---

## What is OSOlogic?

OSOlogic is a fully open platform for process automation. At its core is a **real-time,
in-memory data hub** that everything speaks to, wrapped by IEC 61131-3 language engines
(Ladder, ST, FBD, SFC, IL), a universal protocol gateway, open hardware designs, and modern
APIs — so a controller can be as small as a microcontroller or as large as a control room.

- **Open and hackable** — open-source software and hardware, no vendor lock-in.
- **Real-time** — PREEMPT_RT Linux and baremetal targets.
- **Data-centric** — an in-memory hub with adapters to any database.
- **Universal gateway** — Modbus, CAN, EtherNet/IP, PROFINET, OPC-UA, MQTT.
- **Ready for AI** — an MCP interface so agents can reason about and operate the plant.

## Deploy in minutes

From a bare board to a running PLC — flash an image, then run the guided installer:

```bash
sudo oso-setup    # fast ncurses wizard, with a plain-text fallback
```

→ **[Deploy](https://osologic.com/deploy/)** · **[Deployment guide](https://github.com/OSOlogic/platform/tree/main/docs/deployment)**

## Start here

| Repository | Description |
|---|---|
| **[platform](https://github.com/OSOlogic/platform)** | The OSOlogic platform — Community Edition (AGPL-3.0). |

## Editions

The **Community Edition** is a complete, production-capable platform. **OSOlogic Enterprise**
adds optional modules for scale, certification, high availability, advanced security, computer
vision / AI, and multi-axis CNC — see the
[Enterprise overview](https://github.com/OSOlogic/platform/tree/main/docs/enterprise).

## Community

Contributions are welcome — see the platform's
[contributing guide](https://github.com/OSOlogic/platform/blob/main/CONTRIBUTING.md).
For commercial or enterprise licensing, contact **licensing@osologic.com**.

---

<div align="center">

**OSOlogic®** — © 2026 **Roig Borrell S.L.** and **Ibercomp S.L.**

</div>
