<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:1a0b2e,50:6d28d9,100:a78bfa&height=220&section=header&text=Lucas%20Berns&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Computer%20Science%20Student%20%2D%20GenAI%20Automation%20and%20ML&descAlignY=58&descSize=18)


<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=CS+Student+%40+IFSC+Campus+Lages;R%26D+Intern+%40+iMaps+Analytics;n8n+%2B+Generative+AI+Automation;Python+%7C+Java+%7C+SQL" alt="Typing SVG" />
</a>

<br/>

![IFSC](https://img.shields.io/badge/IFSC-Campus_Lages-6d28d9?style=flat-square)
![Location](https://img.shields.io/badge/Location-Lages,_SC,_Brazil-4c1d95?style=flat-square&logo=googlemaps&logoColor=white)
![English](https://img.shields.io/badge/English-C1_(London_Exchange)-7c3aed?style=flat-square&logo=googletranslate&logoColor=white)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-8b5cf6?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/lucasberns)
[![Email](https://img.shields.io/badge/Email-Contact-6d28d9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lucas.alexandre.berns.oliveira@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-4c1d95?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lucasberns)

![Profile Views](https://komarev.com/ghpvc/?username=lucasberns&color=6d28d9&style=flat-square&label=Profile+Views)

</div>

---

### 📖 About Me

I'm a Computer Science student at **IFSC Campus Lages** (2025–2029), with international experience from a cultural and educational exchange program in **London (C1 English)**.

I currently intern in **Innovation & R&D at iMaps Analytics**, building production automations with **n8n** and integrating **generative AI models (Gemini, Anthropic)** into real workflows — an email-parsing scheduling agent, an automation-viability scoring tool with executive analysis, and pipelines for competitive analysis and content generation.

My next step is moving from orchestrating third-party APIs to **training and evaluating models myself** — I'm currently studying and practicing this outside of work, through independent projects on AI evaluation (LLM-as-Judge).

Previously, I interned in **IT Support at the Santa Catarina State Judiciary (TJSC)**.

**Open to:** internships in GenAI / AI-automation engineering, with a long-term trajectory toward Machine Learning Engineering.

---

### 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-14354C?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Databases**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Automation, AI Integration & Tools**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_API-191919?style=flat-square&logo=anthropic&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github&logoColor=white)

---

### 💼 Experience

**iMaps Analytics** — Innovation & R&D Intern
`Apr 2026 – Present`

- Built production generative AI automations with n8n, including an agent that reads emails via the Anthropic API to organize weekly schedules and pending tasks.
- Designed and implemented an automation-viability assessment tool (**AUTO-Avaliador**) with AI-generated scoring and executive analysis.
- Integrated multiple APIs (Gemini, Anthropic, RapidAPI) and OAuth authentication into competitive-analysis pipelines and multi-profile content generation.

`n8n` `Gemini API` `Anthropic API` `Process Automation` `Webhooks`

<br/>

**Santa Catarina State Judiciary (TJSC)** — IT Support Intern
`Jun 2025 – Mar 2026`

- Resolved technical issues related to hardware and software, ensuring continuity of operations.
- Provided direct user support, reducing average response time on internal tickets.

`Technical Support` `Troubleshooting` `Ticketing Systems`

---

### 🚀 Featured Projects

<details open>
<summary><b>📊 Wine Price Regression</b> — Small-Sample Case Study</summary>

<br/>

A study on how linear regression behaves with very little data (25 rows, the classic Bordeaux wine dataset from Ashenfelter's 1990 paper). The real question wasn't "can I fit a regression" — it was whether wild swings in cross-validation R² across folds meant overfitting, or were just noise from a 5-row validation set.

**Why it's interesting:** first read of the fold-by-fold R² (`0.766, 0.820, 0.711, 0.535, 0.252`) looked like classic overfitting. But checking training R² across the same folds (`0.813, 0.798, 0.832, 0.855, 0.868` — stable, no gap) ruled that out. Train/val gap analysis showed the real explanation: a couple of validation folds happened to land on unusual vintages, not the model memorizing data. The initial hypothesis was wrong, and the analysis says so directly instead of forcing the data to fit the expected story.

| | |
|---|---|
| **Stack** | Python, scikit-learn |
| **Dataset** | Bordeaux wine dataset (Ashenfelter, 1990) — 25 vintages, 4 features |
| **Key finding** | Fold-level R² volatility ≠ overfitting when training scores stay stable — it's a small-sample artifact |
| **Repo** | [regression-study-case](https://github.com/lucasberns/regression-study-case) |

</details>

---

### 🎓 Education

**Federal Institute of Santa Catarina (IFSC)** — Bachelor's in Computer Science
`2025 – 2029`

**EF International Language Campuses** — English Course & Cultural Exchange Program, London
`2023`

---

### 📌 Currently

```yaml
learning:
  - Machine Learning fundamentals (independent study, outside coursework)
  - Data Structures (sorting algorithms, hash tables)
  - Operating Systems (memory management, file systems)
  - Computer Networks

building:
  - LLM-as-Judge evaluation harness (independent project, Python)
  - AUTO-Avaliador improvements at iMaps Analytics
  - Personal PWA tools (fitness, hair care)

exploring:
  - AI evaluation methodology and applied ML
  - Personal finance systems and budgeting frameworks

open_to:
  - GenAI / AI-automation engineering internships
  - Long-term trajectory: Machine Learning Engineering
```

---

### 🏆 Achievements

<div align="center">

| Recognition | Details |
|---|---|
| **REUNI Challenge 2025 — Finalist** | Finalist team representing IFSC Campus Lages in the 2025 (6th) edition of REUNI Challenge, Brazil's largest university entrepreneurship competition — 23 teams from 21 institutions competed, 11 reached the final round. |

</div>

---

### 📫 Connect

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lucas.alexandre.berns.oliveira@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/lucasberns)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lucasberns)

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:a78bfa,50:6d28d9,100:1a0b2e&height=120&section=footer)

</div>
