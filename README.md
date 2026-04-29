<!-- ZavetSec GitHub Profile README -->

<div align="center">

```
███████╗ █████╗ ██╗   ██╗███████╗████████╗███████╗███████╗ ██████╗
╚══███╔╝██╔══██╗██║   ██║██╔════╝╚══██╔══╝██╔════╝██╔════╝██╔════╝
  ███╔╝ ███████║██║   ██║█████╗     ██║   ███████╗█████╗  ██║
 ███╔╝  ██╔══██║╚██╗ ██╔╝██╔══╝     ██║   ╚════██║██╔══╝  ██║
███████╗██║  ██║ ╚████╔╝ ███████╗   ██║   ███████║███████╗╚██████╗
╚══════╝╚═╝  ╚═╝  ╚═══╝  ╚══════╝   ╚═╝   ╚══════╝╚══════╝ ╚═════╝
```

**Anonymous SOC/DFIR toolsmith. Open-source. No install. No dependencies. No noise.**

![](https://img.shields.io/badge/focus-SOC%20%2F%20DFIR%20%2F%20Blue%20Team-00ff88?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/stack-PowerShell%20%7C%20Bash%20%7C%20Python-00ff88?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/license-MIT-00ff88?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/reports-dark%20HTML%20%2B%20MITRE%20ATT%26CK-00ff88?style=flat-square&labelColor=0d1117)

</div>

---

## Philosophy

> Single-file tools. Zero installation. No agents, no databases, no persistence.  
> Run once — get a structured HTML report with MITRE ATT&CK mappings.  
> Works in air-gapped environments, incident response, and hardened SOC networks.

---

## Tools

| Tool | Platform | Description |
|------|----------|-------------|
| [**Invoke-ZavetSecTriage**](https://github.com/zavetsec/Invoke-ZavetSecTriage) | Windows / PS 5.1 | Live DFIR triage — 17 modules, MITRE ATT&CK tagging, self-contained HTML report |
| [**ZavetSec-Harden**](https://github.com/zavetsec/ZavetSec-Harden) | Windows / PS 5.1 | Hardening baseline aligned to CIS / DISA STIG / MS Security Baseline — Audit, Apply, Rollback |
| [**ZLT**](https://github.com/zavetsec/ZLT) | Linux / Bash | First-response triage for Linux hosts — 12 modules, auto-analysis, single command |
| [**Invoke-ADSecurityAudit**](https://github.com/zavetsec/Invoke-ADSecurityAudit) | Windows / PS 5.1 | Active Directory security audit — findings, MITRE mapping, remediation guidance |
| [**ZavetSec-NetworkInventory**](https://github.com/zavetsec/ZavetSec-NetworkInventory) | Windows / PS 5.1 | Passive network scanner — asset inventory, banner grabbing, SSL audit, MS17-010 detection |
| [**ZavetSec-NetworkConnections**](https://github.com/zavetsec/ZavetSec-NetworkConnections) | Windows / PS 5.1 | Live connection snapshot — process context, GeoIP enrichment, DNS analysis, risk classification |
| [**ZavetSec-BrowserHistory**](https://github.com/zavetsec/ZavetSec-BrowserHistory) | Windows / PS 5.1 | Forensic browser history extractor — all users, all browsers, one report |
| [**Invoke-MBHashCheck**](https://github.com/zavetsec/Invoke-MBHashCheck) | Windows / PS 5.1 | Hash lookup against MalwareBazaar & ThreatFox with HTML report |
| [**ZavetSec-Vault**](https://github.com/zavetsec/ZavetSec-Vault) | Any browser | Offline password manager — AES-256-GCM, single HTML file, no cloud |

---

## Design Standard

All tools share a consistent output format:

- `#0a0d10` dark background — readable in SOC environments at 3 AM
- `#00ff88` green accent — high contrast, low eye strain
- **JetBrains Mono** for code and data, **Rajdhani** for headers
- Severity tag badges, MITRE ATT&CK references inline
- 100% self-contained HTML — one file, no CDN, no external requests

---

## Coverage

```
Windows Triage ──────────────────── Invoke-ZavetSecTriage
Linux Triage ────────────────────── ZLT
Active Directory ────────────────── Invoke-ADSecurityAudit
Network Discovery ───────────────── ZavetSec-NetworkInventory
Live Connections ────────────────── ZavetSec-NetworkConnections
Browser Forensics ───────────────── ZavetSec-BrowserHistory
Hash Intel ──────────────────────── Invoke-MBHashCheck
Hardening ───────────────────────── ZavetSec-Harden
Secure Storage ──────────────────── ZavetSec-Vault
```

---

<div align="center">

*Tools are provided as-is for defensive security and incident response purposes.*  
*MIT License — use freely, attribute appreciated.*

</div>
