# 🛡️ Federal Security Support

**Zero Trust • IL4/IL5 • SNCA • YubiKey PIV • Enclave Access Engineering**

---

## ✨ Overview

This repository showcases engineering work performed in **federal IL4/IL5 and GCC/NSC environments**, focusing on secure access, identity enforcement, endpoint compliance, and Zero Trust authentication workflows. All content is fully sanitized and demonstrates the architecture, automation, and troubleshooting patterns used to support high-assurance federal systems.

---

## ⚡ Quick Start

This repository contains four core areas:

- **📁 [`/docs`](docs/)** — Architecture, deployment workflows, troubleshooting, and data dictionary  
- **📜 [`/scripts`](scripts/)** — SNCA routing validation, posture evaluation, tunnel diagnostics, MFA compliance, and audit SQL  
- **⚙️ [`/config`](config/)** — Sanitized templates for SNCA routing, posture policy, and enclave access rules  
- **🏗️ [`/architecture`](architecture/)** — Zero Trust diagrams, enclave routing layers, and identity flow breakdowns  

---

## 🧾 System Summary

This system secures access to IL4/IL5 and GCC/NSC federal environments by enforcing:

- **Hardware-backed MFA** (YubiKey PIV)
- **Device posture validation** (encryption, endpoint protection, compliance)
- **Zero Trust continuous verification**
- **SNCA v2/v3/legacy identity routing**
- **IL4/IL5 enclave segmentation**
- **Secure tunnels** (Zscaler, GlobalProtect)
- **Full audit logging and compliance monitoring**

Only **trusted users on compliant endpoints** can reach isolated federal enclaves. All authentication, posture, and access events are logged to maintain audit readiness.

---

## 💡 Why This Work Matters

Federal IL4/IL5 environments require high-assurance identity verification, strict device compliance, continuous Zero Trust monitoring, controlled enclave segmentation, and immutable audit trails.

This work ensures uninterrupted mission readiness by validating identity, posture, and access across secure enclaves—supporting operations where reliability and compliance are non-negotiable.

---

## 🎯 Responsibilities & Scope

- Supported IL4/IL5 and GCC/NSC environments with strict compliance requirements
- Implemented and maintained **YubiKey PIV MFA**
- Hardened endpoints and enforced Zero Trust posture policies
- Troubleshot secure access failures across VDI, ServiceNow, and cloud systems
- Ensured alignment with federal baselines and enclave segmentation rules
- Collaborated with IAM, security, and compliance teams to maintain audit readiness

---

## 🛠️ Technologies & Tools

### Platform Stack

| Category | Technologies | Purpose |
|----------|--------------|---------|
| 🔑 **Authentication** | YubiKey PIV, SNCA v2/v3/legacy | High-assurance MFA + identity routing |
| 🏛️ **Federal Environments** | IL4, IL5, GCC High, NSC | Segmented, compliance-aligned tenants |
| 🖥️ **Endpoints** | Windows, VDI | Secure workstation and virtual desktop access |
| 🔐 **Identity & Access** | MFA, RBAC, SSO | Access control and identity enforcement |
| ⚙️ **Automation** | PowerShell | Access validation, posture checks, diagnostics |
| 📊 **Monitoring** | Audit logs, SIEM | Compliance visibility and traceability |
| 📋 **Compliance** | Zero Trust, IL4/IL5 baselines | Federal security alignment |

---

## 🗂️ Repository Structure
```
Federal-Security-Support/
├── architecture/
│   ├── architecture-summary.md
│   ├── architecture-diagram.md
│   ├── architecture-layers.md
|   └── Federal_Zero_Trust_Access_Architecture.png
├── docs/
│   ├── deployment-overview.md
│   ├── troubleshooting-guide.md
│   ├── runbook.md
│   └── data-dictionary.md
├── scripts/
│   ├── access-validation.ps1
│   ├── posture-evaluation.ps1
│   ├── tunnel-diagnostics.ps1
│   ├── yubikey-compliance-check.ps1
│   └── il4-weekend-support-log.sql
├── config/
│   ├── snca-config-template.json
│   ├── posture-policy-template.json
│   └── enclave-access-policy.json
└── Color-coded_IL4-IL5.png
```

---

## 📋 Key Files

### 📐 Architecture
- **[`architecture-summary.md`](architecture/architecture-summary.md)**
- **[`architecture-diagram.md`](architecture/architecture-diagram.md)**
- **[`architecture-layers.md`](architecture/architecture-layers.md)**
- **[`Federal_Zero_Trust_Access_Architecture.png`](architecture/Federal_Zero_Trust_Access_Architecture.png)**

### 📄 Documentation
- **[`deployment-overview.md`](docs/deployment-overview.md)**
- **[`troubleshooting-guide.md`](docs/troubleshooting-guide.md)**
- **[`runbook.md`](docs/runbook.md)**
- **[`data-dictionary.md`](docs/data-dictionary.md)**

### 🧰 Scripts
- **[`access-validation.ps1`](scripts/access-validation.ps1)**
- **[`posture-evaluation.ps1`](scripts/posture-evaluation.ps1)**
- **[`tunnel-diagnostics.ps1`](scripts/tunnel-diagnostics.ps1)**
- **[`yubikey-compliance-check.ps1`](scripts/yubikey-compliance-check.ps1)**
- **[`il4-weekend-support-log.sql`](scripts/il4-weekend-support-log.sql)**

### ⚙️ Configuration
- **[`snca-config-template.json`](config/snca-config-template.json)**
- **[`posture-policy-template.json`](config/posture-policy-template.json)**
- **[`enclave-access-policy.json`](config/enclave-access-policy.json)**

### 📘 Root Files
- **[`README.md`](README.md)**

---

## 🚀 Deployment Workflow

1. Configure SNCA v2/v3/legacy routing
2. Enforce YubiKey PIV MFA
3. Validate device posture (encryption, endpoint protection, compliance)
4. Establish secure tunnels (Zscaler / GlobalProtect)
5. Apply IL4/IL5 enclave segmentation
6. Validate Zero Trust continuous verification
7. Enable audit logging and compliance pipelines

---

## ✅ Key Outcomes

- Strengthened authentication reliability across IL4/IL5 environments
- Reduced access failures through structured troubleshooting workflows
- Improved compliance alignment with federal baselines
- Enhanced Zero Trust enforcement across VDI and cloud systems
- Supported mission-critical operations requiring high-assurance identity controls

---

## 🔧 Engineering Challenges Solved

- Eliminated MFA loops and SNCA routing mismatches
- Resolved posture drift and non-compliant endpoint states
- Stabilized VDI access across segmented enclaves
- Improved audit traceability for weekend support operations
- Reduced tunnel instability and enclave reachability failures

---

## 🔐 Security & Access Controls

This system enforces:

- Hardware-backed MFA (YubiKey PIV)
- Device compliance (Intune/Jamf)
- Zero Trust posture evaluation
- SNCA identity routing
- IL4/IL5 enclave segmentation
- Continuous session monitoring
- Immutable audit logging

---

## 🔒 Confidentiality Notice

All content is fully sanitized. No internal federal data, proprietary configurations, or sensitive operational details are included. Only high-level engineering patterns and workflows are represented.

---

## 👔 Professional Context  

**Suren Jewels**  
Cloud & Infrastructure Engineer • Security & Automation Specialist  

This repository showcases sanitized engineering patterns and automation workflows used in enterprise ServiceNow environments.

- **LinkedIn:** [https://www.LinkedIn.com/in/SurenA-Jewels/](https://www.LinkedIn.com/in/SurenA-Jewels/)
- **GitHub:** [https://GitHub.com/SurenA-Jewels](https://GitHub.com/SurenA-Jewels)
- **Email:** [SurenJewelsPro@gmail.com](mailto:SurenA.Jewels@gmail.com)
