# GRC Risk Engine

> **A fully interactive, AI-powered cloud security risk assessment tool.**  
> Built in vanilla JavaScript. No frameworks. No backend.  
> Open the file. It works.

![Register](https://github.com/user-attachments/assets/4d0db5b0-d0d7-4919-8572-344d8046ea73)

---

## Why this exists

Most GRC tools cost thousands of dollars, require a backend, need a login, and take a week to set up.

This does the same job. It's one HTML file. It runs offline. It exports professional reports. It has AI.

---

## What it does

| Feature | Description |
|---------|-------------|
| 🤖 AI Risk Suggestions | Detects your company type and auto-generates relevant risks |
| ⚡ Live Risk Scoring | Likelihood × Impact → auto-calculates score and severity in real time |
| 🗺️ Interactive Heatmap | Click any cell to see which risks live at that L×I coordinate |
| 📊 Dashboard | Donut chart + bar chart + NIST coverage bars, all live |
| 🎯 AI Remediation | Click "AI Fix" on any risk → get 5 actionable remediation steps |
| 🗺️ Roadmap Generator | Auto-builds a prioritized remediation timeline from your register |
| 📊 Export to Excel | Downloads a full `.xlsx` with Risk Register + Summary tabs |
| 📄 Export HTML Report | Generates a professional report with cover page and findings |
| 🖨️ Print to PDF | One click → browser print dialog → save as PDF |
| 🔍 Search & Filter | Filter by severity level or search by keyword across all risks |

---

## Screenshots

**Risk Register — live scoring as you type**
![Register](https://github.com/user-attachments/assets/4d0db5b0-d0d7-4919-8572-344d8046ea73)

**Dashboard — real-time charts and NIST coverage**
![Dashboard](https://github.com/user-attachments/assets/ede4e0b2-1547-414d-9bf8-88fd35207915)

**Heatmap — clickable Likelihood × Impact matrix**
![Heatmap](https://github.com/user-attachments/assets/fce5b57b-2a48-4fc8-b386-8c339dbe1e14)

**Roadmap — auto-generated remediation timeline**
![Roadmap](https://github.com/user-attachments/assets/642417f0-2488-4202-9117-b5079ddd0ab2)

**Export — Excel, HTML report, and PDF**
![Export](https://github.com/user-attachments/assets/7e23ce06-2b1d-4284-af09-b2c10fa94881)

---

## How to use

```bash
# Option 1 — just download
# Click "Code" → "Download ZIP" → open index.html

# Option 2 — clone
git clone https://github.com/SuryaTeja2002-design/grc-risk-engine.git
cd grc-risk-engine
open index.html
```

No npm install. No pip install. No Docker. No `.env` file. Just open it.

---

## Frameworks used

None.

| Tool | Purpose |
|------|---------|
| Vanilla JavaScript | All logic, state, rendering |
| Chart.js | Donut and bar charts |
| SheetJS (xlsx) | Excel export |
| CSS Grid + Flexbox | Layout |
| Google Fonts | Typography (Space Mono + Syne) |

No React. No Vue. No Angular. No Tailwind. This is what understanding fundamentals looks like.

---

## Frameworks supported

The tool supports four major GRC frameworks out of the box:

- **NIST CSF 2.0** — the gold standard for US cybersecurity
- **ISO 27001** — international information security standard
- **SOC 2 Type II** — for SaaS and cloud service providers
- **CIS Controls** — practical, prioritized security controls

---

## Risk scoring methodology

```
Risk Score = Likelihood (1–5) × Impact (1–5)

Score 20–25  →  CRITICAL  →  Immediate action within 7 days
Score 12–19  →  HIGH      →  Remediate within 30 days
Score 5–11   →  MEDIUM    →  Remediate within 90 days
Score 1–4    →  LOW       →  Monitor quarterly
```

This is the same methodology used by real GRC consultants and auditors.

---

## AI features

The tool includes two AI-powered features:

**Risk Suggestion Engine**  
Detects keywords in your company name (hospital, bank, retail, tech) and surfaces the most relevant risks for that industry. One click adds them to your register with pre-filled severity scores.

**Remediation Generator**  
Select any risk and click "AI Fix" — the engine maps the risk category to a curated set of 5 actionable remediation steps based on real-world security best practices.

---

## What this covers (portfolio context)

This project was built as part of a cybersecurity portfolio covering:

- [x] Project 2 — Cloud Security Risk Assessment (GRC) ✅ ← this tool
- [x] Project 4 — Network & Host Scanning with Nmap ✅
- [x] Project 5 — Web App Scanning with OWASP ZAP ✅
- [ ] Project 1 — Active Directory Setup & User Management
- [ ] Project 3 — Log File Analysis / SIEM Virtualization

---

## Roadmap

- [ ] Real Claude API integration for dynamic AI suggestions
- [ ] LocalStorage persistence (save/load sessions)
- [ ] Multi-user cloud sync
- [ ] Risk library with 100+ pre-built risks per industry
- [ ] CVE feed integration for real-time threat intelligence
- [ ] Compliance gap scoring per framework

---

## Author

**Suryateja Gorthi**  
Cybersecurity | AI | Business Intelligence  
Building at the intersection of data, intelligence, and security.

---

> *"Most people in cyber know security but can't do data. Most people in BI know data but don't understand threats. This project sits at the intersection of both."*

---

## Disclaimer

This tool is built for portfolio and educational purposes. It demonstrates GRC methodology and professional risk documentation practices. Always consult a qualified security professional for production risk assessments.
