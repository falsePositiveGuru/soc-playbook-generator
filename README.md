# 🛡️ SOC Playbook Generator

> AI-powered enterprise incident response playbook generator for Security Operations Centers. Supports multiple AI providers — including free tiers.

![Status](https://img.shields.io/badge/Status-Live-00ff88?style=flat-square)
![Providers](https://img.shields.io/badge/AI%20Providers-4-00d4ff?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-a78bfa?style=flat-square)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-ffbb33?style=flat-square)

**🌐 Live App →** [falsepositiveguru.github.io/soc-playbook-generator](https://soc-playbook-generator.ksuneelbaba9.workers.dev)

---

## 🔍 Overview

The SOC Playbook Generator helps security analysts instantly generate comprehensive incident response playbooks from plain-language threat descriptions. Powered by your choice of AI provider, it produces structured, actionable playbooks in seconds — no templates, no manual writing, no backend required.

---

## ⚡ Features

| Feature | Description |
|---|---|
| 🤖 **Multi-LLM Support** | Choose from Anthropic, OpenAI, Groq, or Gemini |
| 📋 **IR Playbook** | Phase-by-phase incident response steps |
| 🔎 **Detection Rules** | SIEM queries (Splunk SPL / KQL), SOAR actions, IOCs |
| ✅ **Investigation Checklist** | Interactive checklist with live progress tracking |
| 🔧 **Remediation Runbook** | Prioritized actions — Immediate / Short-term / Long-term |
| 🎯 **MITRE ATT&CK Mapping** | Techniques mapped with direct links to attack.mitre.org |
| 📄 **PDF Export** | Dark-themed, print-ready playbook export |
| 🔐 **Privacy First** | API keys stored only in your browser — never sent to any server |

---

## 🤖 Supported AI Providers

| Provider | Model | Free Tier | Get API Key |
|---|---|---|---|
| **Anthropic** | claude-haiku-4-5 | No (pay per use) | [console.anthropic.com](https://console.anthropic.com/) |
| **OpenAI** | gpt-4o-mini | No (pay per use) | [platform.openai.com](https://platform.openai.com/api-keys) |
| **Groq** | llama-3.3-70b-versatile | ✅ Yes — generous free tier | [console.groq.com](https://console.groq.com/keys) |
| **Gemini** | gemini-1.5-flash | ✅ Yes — free tier available | [aistudio.google.com](https://aistudio.google.com/app/apikey) |

> 💡 **Recommended for new users:** Start with **Groq** or **Gemini** — both have free tiers and no credit card required.

---

## 🚀 Getting Started

### 1. Open the app
Visit **[falsepositiveguru.github.io/soc-playbook-generator](https://falsepositiveguru.github.io/soc-playbook-generator/)**

### 2. Choose your AI provider
Click one of the four provider buttons in the sidebar — Anthropic, OpenAI, Groq, or Gemini.

### 3. Enter your API key
Paste your API key — a direct link to get each provider's key is shown in the sidebar. Keys are saved in your browser's local storage automatically.

### 4. Describe an incident
Type a plain-language threat description, for example:
```
Ransomware detected on Windows endpoints, lateral movement via SMB observed
```

### 5. Generate & explore
Click **Generate Playbook** or press `Ctrl + Enter`. Browse across 6 tabs and export to PDF when done.

---

## 🧪 Example Incidents

- Ransomware on Windows endpoints, lateral movement via SMB detected
- Encoded PowerShell execution from HR workstation
- Brute force on Azure AD — 500+ failed logins in 10 min
- Phishing email with macro-enabled Excel attachment opened
- Insider threat — unusual data exfiltration to personal cloud storage
- Supply chain compromise via third-party software update

---

## 📋 Playbook Tabs

| Tab | Contents |
|---|---|
| **Summary** | Severity, threat type, MITRE tactic overview, incident summary |
| **IR Playbook** | Phased response steps (Identification → Containment → Eradication → Recovery) |
| **Detection** | SIEM rules, SOAR automation actions, Indicators of Compromise |
| **Checklist** | Interactive investigation checklist with progress tracking |
| **Remediation** | Prioritized runbook steps with Immediate / Short-term / Long-term labels |
| **MITRE ATT&CK** | Mapped techniques with tactic context and mitigation recommendations |

---

## 🔐 Security & Privacy

- Your API key is stored **only in your browser's local storage**
- Keys are **never transmitted** to any server other than your chosen AI provider directly
- No incident data, playbooks, or user information is stored or logged anywhere
- All API calls go directly from your browser to the provider's API endpoint
- Each provider's key is stored separately — switching providers never mixes keys

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML, CSS, JavaScript — zero dependencies
- **AI:** Your choice of Anthropic / OpenAI / Groq / Gemini via REST API
- **Hosting:** GitHub Pages
- **Build tools:** None — single `index.html` file, works out of the box

---

## 📁 Project Structure

```
soc-playbook-generator/
├── index.html       # Complete app — single self-contained file
└── README.md        # This file
```

---

## 🗺️ Roadmap

- [ ] Playbook history — save and revisit past incidents
- [ ] Share playbooks via URL
- [ ] Custom threat templates (Ransomware, APT, Insider Threat, DDoS)
- [ ] Slack / email integration for team alerts
- [ ] OpenRouter support (access 100+ models with one key)
- [ ] Multi-language playbook output

---

## 👤 Author

**Suneel Baba** ([@falsePositiveGuru](https://github.com/falsePositiveGuru))  
Security Operations · Threat Detection · Incident Response

---

## ⚠️ Disclaimer

This tool is intended for authorized security operations use only. Generated playbooks are AI-assisted and should be reviewed by qualified security professionals before execution in production environments. The tool does not store, log, or transmit any incident data beyond your chosen AI provider's API call.

---

*Built with ❤️ for the SOC community · Star ⭐ the repo if you find it useful!*
