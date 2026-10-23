# Cortex XDR SecOps & Threat Hunting Playbooks

![Platform](https://img.shields.io/badge/Platform-Cortex%20XDR-blue?style=flat-square&logo=paloaltonetworks)
![Language](https://img.shields.io/badge/Language-XQL-orange?style=flat-square)

A collection of XQL queries, incident response playbooks, and threat hunting methodologies for Cortex XDR. 

These playbooks are built to solve real-world visibility and detection challenges across hybrid environments, particularly when dealing with containerized workloads (Docker/K3s) and non-standard application deployments where static inventory tools often fall short.

> **OPSEC Note:** All queries, hostnames, tags, and architectural references have been strictly sanitized. No proprietary organizational data is included.

---

## 📂 Repository Structure

```text
├── 01-Vulnerability-and-Exposure-Management/   # Rapid CVE footprinting & container runtime inspection
├── 02-Threat-Hunting-and-IOCs/                 # Proactive behavioral & IOC-driven threat hunts
├── 03-Detection-Engineering-BIOCs/             # Custom correlation rules & BIOC logic
└── _templates/                                 # Standardized documentation templates
```