# 🛡️ SOC Playbook Generator

> AI-powered enterprise incident response playbook generator for Security Operations Centers.

![SOC Playbook Generator](https://img.shields.io/badge/Status-Live-00ff88?style=flat-square&logo=github)
![Powered by Claude](https://img.shields.io/badge/Powered%20by-Claude%20AI-00d4ff?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-a78bfa?style=flat-square)

**Live App →** [falsepositiveguru.github.io/soc-playbook-generator](https://falsepositiveguru.github.io/soc-playbook-generator/)

---

## 🔍 Overview

The SOC Playbook Generator helps security analysts instantly generate comprehensive incident response playbooks from plain-language threat descriptions. Powered by Anthropic's Claude AI, it produces structured, actionable playbooks in seconds — no templates, no manual writing.

---

## ⚡ Features

| Feature | Description |
|---|---|
| 📋 **IR Playbook** | Phase-by-phase incident response steps |
| 🔎 **Detection Rules** | SIEM queries (Splunk SPL / KQL), SOAR actions, IOCs |
| ✅ **Investigation Checklist** | Interactive checklist with progress tracking |
| 🔧 **Remediation Runbook** | Prioritized actions (Immediate / Short-term / Long-term) |
| 🎯 **MITRE ATT&CK Mapping** | Techniques mapped with direct links to attack.mitre.org |
| 📄 **PDF Export** | Print-ready dark-themed playbook export |

---

## 🚀 Getting Started

### Prerequisites
- An [Anthropic API key](https://console.anthropic.com/) (free to create)
- A modern web browser (Chrome, Firefox, Edge, Safari)

### Usage

1. Open the [live app](https://falsepositiveguru.github.io/soc-playbook-generator/)
2. Enter your Anthropic API key in the top field — it saves locally in your browser
3. Describe a threat or incident in plain language, for example:
   ```
   Ransomware detected on Windows endpoints, lateral movement via SMB observed
   ```
4. Click **Generate Playbook** or press `Ctrl + Enter`
5. Browse the generated playbook across 6 tabs
6. Export to PDF for documentation or sharing

---

## 🧪 Example Incidents

- Ransomware on Windows endpoints, lateral movement via SMB detected
- Encoded PowerShell execution from HR workstation
- Brute force on Azure AD — 500+ failed logins in 10 min
- Phishing email with macro-enabled Excel attachment opened

---

## 🔐 Security & Privacy

- Your API key is stored **only in your browser's local storage**
- It is **never sent to any server** other than Anthropic's API directly
- No user data, incidents, or playbooks are stored or logged anywhere
- All API calls go directly from your browser to `api.anthropic.com`

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML, CSS, JavaScript (zero dependencies)
- **AI:** Anthropic Claude (`claude-haiku-4-5`) via REST API
- **Hosting:** GitHub Pages
- **Framework:** None — single `index.html` file

---

## 📁 Project Structure

```
soc-playbook-generator/
├── index.html       # Complete app — single file
└── README.md        # This file
```

---

## 🗺️ Roadmap

- [ ] Playbook history — save and revisit past incidents
- [ ] Team collaboration — share playbooks via URL
- [ ] Custom threat templates (Ransomware, APT, Insider Threat)
- [ ] Slack / email integration
- [ ] Multi-language support

---

## 👤 Author

**Suneel Baba** ([@falsePositiveGuru](https://github.com/falsePositiveGuru))  
Security Operations · Threat Detection · Incident Response

---

## ⚠️ Disclaimer

This tool is intended for authorized security operations use only. Generated playbooks are AI-assisted and should be reviewed by qualified security professionals before execution in production environments.

---

*Built with ❤️ for the SOC community*
