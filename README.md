# Jeterio — Releases

**Pure Offline. Private by Design.**

Jeterio is a **free offline-first desktop toolkit** for Windows, macOS, and Linux. It packs **200
practical tools** across 12 categories — utilities, productivity, business, finance, wellness,
health care, home & family, education, security, creativity, transport, and safety — plus an
**optional offline AI workspace** with local chat models and a Knowledge Base that reads your own
documents.

Everything runs on your device. **No accounts. No subscriptions. No telemetry.** If you need the
internet to do something, Jeterio tells you — it never silently phones home.

---

## Download

The latest installers live on the **[Releases](https://github.com/jetherweb/jeterio-releases/releases)**
page of this repository. Download the file for your operating system:

| Platform | What you get |
| --- | --- |
| **Windows** | NSIS installer (`.exe`) and portable build |
| **macOS** | Disk image (`.dmg`) |
| **Linux** | AppImage and `.deb` package |

Prefer the official site? The **[Jeterio download page](https://jeterio.jetherweb.com/download)**
always points at these same files and includes the full checksum table.

### Verify your download

Every release includes a `SHA256SUMS.txt` with the checksums of the published files. Verify before
installing (recommended):

```sh
# macOS / Linux
shasum -a 256 Jeterio_*.dmg          # or .AppImage / .deb
# Windows (PowerShell)
Get-FileHash Jeterio_*.exe -Algorithm SHA256
```

Compare the output to the value in `SHA256SUMS.txt`.

---

## What's new

Plain-language release notes for each version are published with every release. See the
**[changelog](https://jeterio.jetherweb.com/changelog)** on the website, or open **About →
What's new** inside the desktop app (fully offline).

---

## Privacy

Jeterio processes everything locally. Tool inputs, history, and Knowledge Base files stay on your
device. AI models are optional and downloaded only when you choose them; there is **no cloud
fallback** — ever. Read the full model at
**[jeterio.jetherweb.com/privacy](https://jeterio.jetherweb.com/privacy)**.

---

## About this repository

This is the **public download hub** for Jeterio. Installers, checksums, and release notes are
published here automatically from our private build pipeline — the Jeterio source code itself is
not public. Developed & maintained by **[JetherWeb](https://jetherweb.com)**.

---

*© 2026 Jeterio — Pure Offline. Private by Design. All rights reserved.*
