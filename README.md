# Saint’s Inc. — Zero Trust Architecture Capstone

Author: Christian J Szadolc  
Western Governors University

![Zero Trust](https://img.shields.io/badge/Zero%20Trust-Implemented-green)
![WGU Capstone](https://img.shields.io/badge/WGU-Capstone-blue)

## 📘 Overview

This capstone project implemented a Zero Trust security architecture for Saint’s Inc., a mid‑sized professional services firm (~250 users, 2 locations). The engagement replaced an outdated perimeter‑based model with identity‑centric controls, network micro‑segmentation, endpoint hardening, encryption, and continuous monitoring (SIEM + EDR).

## 🎯 Objective

Design, deploy, and validate a Zero Trust solution that enforces continuous verification, least privilege, and improved visibility to reduce unauthorized access and improve threat detection and response. The project includes both pre‑action (planning/baseline) and after‑action (results/metrics) reports.

## 🧠 Key Skills Demonstrated

- Zero Trust architecture design & implementation (NIST SP 800‑207)
- Identity & Access Management (IAM), RBAC, and MFA deployment
- Network segmentation & micro‑segmentation (VLANs, firewalls, ACLs)
- Endpoint hardening and EDR deployment
- SIEM deployment, log onboarding, alert tuning, and SOC configuration
- Vulnerability scanning, penetration testing, and control validation
- Project planning using waterfall, risk & vendor management
- Scripting/automation (Python) for reporting and operational support

## 🧰 Tools & Frameworks

- NIST SP 800‑207 (Zero Trust Architecture)
- CISA Zero Trust Maturity Model
- CIS Critical Security Controls v8
- IAM / MFA platforms
- SIEM and EDR solutions
- VLANs, Firewalls, ACLs
- Linux, macOS, Kali Linux (testing)
- Python

## 🔍 Summary of Findings & Outcomes

- Eliminated implicit trust by enforcing continuous identity and device verification alongside policy‑driven access controls.
- Implemented IAM with MFA and RBAC to enforce least‑privilege access across systems and applications.
- Designed and deployed network segmentation to limit lateral movement between security zones.
- Enforced encryption for data in transit and at rest to protect sensitive information.
- Deployed and tuned SIEM and EDR to provide real‑time monitoring, alerting, and incident response support.
- Validated controls through vulnerability scans and penetration testing.

**Measured Results:**

- ~93% reduction in unauthorized access attempts within 30 days (per SIEM logs).
- 100% MFA adoption achieved within 11 days of deployment (per IAM reports).
- Mean detection and response time reduced to ~23 minutes 45 seconds within 30 days (per SIEM/EDR alert data).

## 📄 Repository Contents

- `README.md` — Project overview (this file)

**Documentation**

- `docs/ZeroTrust_Capstone_Task2-3.pdf` — Full capstone report (Task 2 & Task 3: assessment, design, implementation, results).
- `docs/pre_action_report.pdf` — Pre‑action report (baseline assessment, requirements, risk analysis).  
  - Online version: [Pre‑Implementation Report (Google Docs)](https://docs.google.com/document/d/1VULLvQZcXte1Sb2yCEY6QuQSzIlPBRqbrF9cfAhR69M/edit?usp=sharing)
- `docs/after_action_report.pdf` — After‑action report (post‑implementation evaluation, metrics, lessons learned).  
  - Online version: [Post‑Implementation / After‑Action Report (Google Docs)](https://docs.google.com/document/d/1WpH1yQ-vf5CYeaXzoFgcDFlyL3TsDB0l_mwBM2TIgRs/edit?usp=sharing)
- `docs/Implementation_Checklist.md` — Implementation checklist and key deployment steps.
- `docs/timeline_table.png` — Project timeline with planned vs. actual milestone dates.

**Artifacts**

- `artifacts/iam_config.png` — Example IAM configuration and role‑based access control (Appendix 1).
- `artifacts/network_segmentation.png` — Network segmentation diagram showing security zones and enforcement points (Appendix 2).
- `artifacts/siem_dashboard.png` — SIEM security dashboard illustrating real‑time monitoring and key metrics (Appendix 3).

## 📌 How to Review This Project

1. Start with the pre‑implementation report to understand the initial environment, risks, and requirements:  
   - Local: `docs/pre_action_report.pdf`  
   - Online: [Pre‑Implementation Report](https://docs.google.com/document/d/1VULLvQZcXte1Sb2yCEY6QuQSzIlPBRqbrF9cfAhR69M/edit?usp=sharing)
2. Read `docs/ZeroTrust_Capstone_Task2-3.pdf` for detailed architecture, methodology, and implementation phases.
3. Explore the diagrams and screenshots in `artifacts/` for IAM, network segmentation, and SIEM monitoring views.
4. Review the post‑implementation / after‑action report for metrics and lessons learned:  
   - Local: `docs/after_action_report.pdf`  
   - Online: [Post‑Implementation / After‑Action Report](https://docs.google.com/document/d/1WpH1yQ-vf5CYeaXzoFgcDFlyL3TsDB0l_mwBM2TIgRs/edit?usp=sharing)
5. Use `docs/Implementation_Checklist.md` and `docs/Endpoint_Hardening.md` to understand operational handoff and baseline security controls.

## 🧩 Learning Outcomes

- Applied Zero Trust and leading security frameworks end‑to‑end in a realistic enterprise environment.
- Coordinated cross‑functional execution across IAM, networking, endpoint security, and SOC operations.
- Managed vendor issues, schedule slippage, and scope creep while still meeting security objectives.
- Produced measurable security improvements and clear documentation suitable for handoff to operations.
