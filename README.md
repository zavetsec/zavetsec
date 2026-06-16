<div align="center">
  <img src="zavetsec_banner.png" alt="ZavetSec"/>
</div>

<div align="center">

**Anonymous purple-team toolsmith. Single-file tooling and references for air-gapped, incident-response, and hardened environments — defense built on understanding offense.**

`No install. No dependencies. No agents. No telemetry.`

![](https://img.shields.io/badge/team-Purple%20%28Red%20%2B%20Blue%29-00ff88?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/discipline-SOC%20%2F%20DFIR%20%2F%20Pentest-00ff88?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/stack-PowerShell%20%7C%20Python%20%7C%20Bash%20%7C%20C%23%20%7C%20HTML-00ff88?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/license-MIT-00ff88?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/reports-dark%20HTML%20%2B%20MITRE%20ATT%26CK-00ff88?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/knowledge%20base-Pentest%20Codex-00ff88?style=flat-square&labelColor=0d1117)
![](https://img.shields.io/badge/frameworks-NIST%20CSF%202.0-00ff88?style=flat-square&labelColor=0d1117)

*Offensive techniques and the detections that catch them — two halves of one workflow.*

</div>

---

## Why ZavetSec

- **Purple by design** — attack techniques paired with the telemetry and detections that expose them
- Single-file execution — one script (or one HTML), run and done
- No installation, no prerequisites, no admin infrastructure
- Air-gap friendly — works fully offline
- MITRE ATT&CK aligned — both findings and techniques mapped to tactics
- Dark HTML output — structured, self-contained, ready to share

---

## ◣ Blue — Defensive Tooling

Detection, triage, hardening and forensics. Built for SOC/DFIR work in real environments.

### Endpoint Monitoring & DLP

| Tool | Platform | Capability |
|------|----------|------------|
| [**ZavetSec-DLP**](https://github.com/zavetsec/zavetsec-dlp) | Windows / .NET 8 | `Endpoint activity monitoring • keylogger • screenshots • clipboard • USB • DNS • network • web dashboard • EN/RU` |

### SOC / DFIR / Hardening

| Tool | Platform | Capability |
|------|----------|------------|
| [**Invoke-ZavetSecTriage**](https://github.com/zavetsec/Invoke-ZavetSecTriage) | Windows / PS 5.1 | `DFIR triage • 17 modules • MITRE ATT&CK` |
| [**ZavetSec-EVTXHunter**](https://github.com/zavetsec/ZavetSec-EVTXHunter) | Windows / PS 5.1 | `EVTX threat hunting • file & live • 61 rules / 10 chains • entity risk scoring • MITRE ATT&CK` |
| [**ZavetSec-MailInspector**](https://github.com/zavetsec/ZavetSec-MailInspector) | Any / Python 3.8+ | `Phishing & malware triage • .eml / .msg • SPF/DKIM/DMARC + spoofing • URLs + attachments • quishing (QR) • recursive archives • RU/EN` |
| [**ZavetSec-Harden**](https://github.com/zavetsec/ZavetSec-Harden) | Windows / PS 5.1 | `Hardening baseline • CIS / DISA STIG • Audit / Apply / Rollback` |
| [**ZLT**](https://github.com/zavetsec/ZLT) | Linux / Bash | `Linux triage • 12 modules • single command` |
| [**Invoke-ADSecurityAudit**](https://github.com/zavetsec/Invoke-ADSecurityAudit) | Windows / PS 5.1 | `Active Directory audit • findings • remediation` |
| [**ZavetSec-NetworkInventory**](https://github.com/zavetsec/ZavetSec-NetworkInventory) | Windows / PS 5.1 | `Network scanner • asset inventory • offline` |
| [**ZavetSec-NetworkConnections**](https://github.com/zavetsec/ZavetSec-NetworkConnections) | Windows / PS 5.1 | `Live connections • GeoIP • process context • risk` |
| [**ZavetSec-BrowserHistory**](https://github.com/zavetsec/ZavetSec-BrowserHistory) | Windows / PS 5.1 | `Browser forensics • all users • all browsers` |
| [**Invoke-MBHashCheck**](https://github.com/zavetsec/Invoke-MBHashCheck) | Windows / PS 5.1 | `Hash lookup • MalwareBazaar • ThreatFox` |
| [**ZavetSec-Vault**](https://github.com/zavetsec/ZavetSec-Vault) | Any browser | `Offline password manager • AES-256-GCM • no cloud` |

### CSF Kit — SOC Reference Library

The defensive counterpart to the Pentest Codex: a self-contained set of operational references for running a SOC on **NIST CSF 2.0**. Same design standard — one HTML file per document, fully offline, zero dependencies, no trackers. Stack-agnostic by design (tool *classes*, not products).

🌐 **Live:** [zavetsec.github.io/CSFKit](https://zavetsec.github.io/CSFKit/) &nbsp;·&nbsp; 📦 **Repo:** [zavetsec/CSFKit](https://github.com/zavetsec/CSFKit)

| Document | Type | Contents |
|----------|------|----------|
| [**NIST CSF 2.0 for SOC**](https://zavetsec.github.io/CSFKit/nist-csf-soc-framework.html) | Reference / Framework | `Operational model • all 6 functions • category codes • SOC ownership • Tier 1–4 maturity • phased roadmap • metrics catalog • RACI` |
| [**SOC Maturity Self-Assessment**](https://zavetsec.github.io/CSFKit/soc-maturity-self-assessment.html) | Interactive | `31-item maturity check • live Tier scoring • weakest-link logic • copy-out summary • local persistence` |
| [**CSF Detection Coverage Map**](https://zavetsec.github.io/CSFKit/csf-coverage-map.html) | Worksheet | `37 use-cases • CSF × MITRE ATT&CK • data source + tool class • Covered/Partial/Gap status • CSV export` |

### Personal Security & Privacy

| Tool | Platform | Capability |
|------|----------|------------|
| [**opsec-checklist**](https://github.com/zavetsec/opsec-checklist) | Any browser | `OPSEC assessment framework • 70+ items • RU/CIS + US/EU editions` |

---

## ◥ Red — Offensive Reference

The other half: a self-contained library of pentest references — built to **understand the attacks worth defending against**. Same design standard as the tooling: one HTML file per document, fully offline, zero dependencies, no trackers.

### Pentest Codex — Reference Library

🌐 **Live:** [zavetsec.github.io/pentestcodex](https://zavetsec.github.io/pentestcodex/) &nbsp;·&nbsp; 📦 **Repo:** [zavetsec/pentestcodex](https://github.com/zavetsec/pentestcodex)

| Document | Type | Contents |
|----------|------|----------|
| [**Pentest Codex**](https://zavetsec.github.io/pentestcodex/zavetsec-pentest-codex.html) | Reference | `Full kill-chain • every tool explained • every command with flags • 16 sections` |
| [**AD Attack Reference**](https://zavetsec.github.io/pentestcodex/zavetsec-ad-attack-reference.html) | Reference / AD | `ADCS ESC1–ESC16 • delegation • RBCD • Shadow Credentials • ACL abuse • GPO/SCCM • MSSQL lateral` |
| [**Cloud & Identity Reference**](https://zavetsec.github.io/pentestcodex/zavetsec-cloud-identity-reference.html) | Reference / Cloud | `AWS IAM privesc • Azure / Entra ID • token attacks • role abuse • hybrid AD↔Entra • Pacu / CloudFox / ROADtools / AzureHound` |
| [**API Security Reference**](https://zavetsec.github.io/pentestcodex/zavetsec-api-security-reference.html) | Reference / API | `OWASP API Top 10 (2023) • BOLA/IDOR • JWT/OAuth • mass assignment • BFLA • SSRF • injection • GraphQL` |
| [**Container &amp; Kubernetes Security**](https://zavetsec.github.io/pentestcodex/zavetsec-container-k8s-reference.html) | Reference / K8s | `Docker breakout • docker.sock • privileged • RBAC abuse • pod escape • secrets • etcd • EKS/AKS/GKE pivot` |
| [**Pentest Path**](https://zavetsec.github.io/pentestcodex/zavetsec-pentest-path.html) | Roadmap | `Blue→Red progression • PNPT → OSCP → CRTO • labs • habit checklist` |
| [**Arsenal**](https://zavetsec.github.io/pentestcodex/zavetsec-pentest-arsenal.html) | Cheat-sheet | `Command-first reference across the attack phases` |
| [**Kali Linux 2026 Guide**](https://zavetsec.github.io/pentestcodex/zavetsec-kali-2026-guide.html) | Distro | `Install • metapackages • tooling by menu category` |
| [**Parrot OS 7 Guide**](https://zavetsec.github.io/pentestcodex/zavetsec-parrot-7-guide.html) | Distro | `Editions • AnonSurf / privacy • tooling • vs Kali` |

---

## Design Standard

Everything ZavetSec ships — tools and references alike — shares one output format:

- `#0a0d10` dark background — readable in SOC environments at 3 AM
- `#00ff88` green accent — high contrast, low eye strain
- **JetBrains Mono** for code and data, **Rajdhani** for headers
- Severity tag badges, MITRE ATT&CK references inline
- 100% self-contained HTML — one file, no CDN, no external requests

---

## Coverage

```
BLUE — Defensive Tooling
  Endpoint Monitoring   ZavetSec-DLP
  Windows Triage        Invoke-ZavetSecTriage
  Event Log Hunting     ZavetSec-EVTXHunter
  Email / Phishing      ZavetSec-MailInspector
  Linux Triage          ZLT
  Active Directory      Invoke-ADSecurityAudit
  Network Discovery     ZavetSec-NetworkInventory
  Live Connections      ZavetSec-NetworkConnections
  Browser Forensics     ZavetSec-BrowserHistory
  Hash Intel            Invoke-MBHashCheck
  Hardening             ZavetSec-Harden
  Secure Storage        ZavetSec-Vault
  Personal OPSEC        opsec-checklist

BLUE — Frameworks & References
  SOC / NIST CSF 2.0    CSF Kit (zavetsec.github.io/CSFKit)

RED — Offensive Reference
  Pentest Codex         zavetsec.github.io/pentestcodex
```

---

<div align="center">

*Attack-informed defense. Detection-aware offense.*  
*MIT Licensed — open, practical, unrestricted.*

</div>
