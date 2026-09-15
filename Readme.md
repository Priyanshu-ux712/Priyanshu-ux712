<div align="center">

# Priyanshu Kumar

**B.Tech CSE '28 · Gurugram University · Haryana, India** 🇮🇳

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3200&pause=900&color=22C55E&center=true&vCenter=true&width=760&lines=Climate+data+%C2%B7+Built+environments+%C2%B7+Urban+systems;Four+products+shipped+%E2%80%94+all+of+them+live;Local-first+by+default+%C2%B7+evidence+over+claims;Turning+messy+data+into+decisions+you+can+defend)](https://git.io/typing-svg)

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:priyanshukumar9053@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&labelColor=0A66C2)](https://www.linkedin.com/in/priyanshu-kumar-846b39320/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Priyanshu-ux712)
[![Zenodo](https://img.shields.io/badge/Zenodo-1682D4?style=for-the-badge&logo=zenodo&logoColor=white)](https://zenodo.org/records/18866062)

<br>

![Products live](https://img.shields.io/badge/products_live-4-22C55E?style=flat-square&labelColor=1B1F23)
![Preprints](https://img.shields.io/badge/open--access_preprints-4-1682D4?style=flat-square&labelColor=1B1F23)
![Districts](https://img.shields.io/badge/districts_modelled-758-00C7B7?style=flat-square&labelColor=1B1F23)
![Verification](https://img.shields.io/badge/narrative_verification-92.9%25-7C5CFF?style=flat-square&labelColor=1B1F23)
![Telemetry](https://img.shields.io/badge/telemetry-zero-34D27F?style=flat-square&labelColor=1B1F23)

</div>

---

## ◆ About

> I build software at the intersection of **climate data, built environments, and urban systems** — carrying raw sensor and survey data the whole way to a deployed tool someone can make a decision with.

Two commitments run through everything below:

- **Local-first.** ATARS and TerraSight both run entirely on your machine. No accounts, no cloud round-trip, no telemetry. If the data is sensitive, it never has to leave the room.
- **Evidence-first.** Every number in a generated report is computed by code, not by a language model. The AI layer is allowed to *narrate* what was computed and nothing else — in IGNIS it is architecturally forbidden from overriding the physics core.

🌱 &nbsp;Currently seeking **research internships** in sustainability tech, climate-adaptive built environments, and environmental data systems — open to labs, institutes, and industry globally.

---

## ◆ Shipped

| | Project | What it does | Status | Stack |
|:--|:--|:--|:--|:--|
| `GN-01` | **[Green Nirman](https://greennirman.netlify.app)** | Green-building assessment for every climate zone in India | 🟢 `live` | React · NASA POWER |
| `ATARS-V5` | **[ATARS](https://atars.netlify.app)** | Spreadsheet in, research-grade analysis and report out | 🟢 `v5.4.6` | Python · DuckDB · PyPI |
| `TS-1.1.0` | **[TerraSight](https://github.com/Priyanshu-ux712/Terrasight)** | Ask your documents anything — entirely on your device | 🟢 `v1.1.0` | Python · DuckDB · embeddings |
| `IGN-01` | **[IGNIS](https://ignis-in.netlify.app)** | Simulate a new fuel or engine against real thermodynamics | 🟢 `v1.0` | Python · Cantera · FastAPI |

<br>

### 🏗️ &nbsp;Green Nirman &nbsp;·&nbsp; `GN-01` &nbsp;·&nbsp; the built environment

> **Green-building assessment for every climate zone in India.**

India adds enormous amounts of new floor space every year, and most of it is designed without any early check against energy code or embodied-carbon reality. The assessment arrives at certification — far too late for changing the design to be cheap.

Green Nirman moves that assessment to the **start** of the process. Describe a building, pick its district, and it grades the design against published standards using real climate data for that exact location.

- **Coverage** — 758 districts · 72 real material datasets
- **Standards** — ECBC 2017 · GRIHA
- **Climate data** — NASA POWER reanalysis, resolved per district
- **Output** — a ten-page PDF report you can hand to a client the same afternoon

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![NASA POWER](https://img.shields.io/badge/NASA_POWER-0B3D91?style=flat-square&logo=nasa&logoColor=white)
![jsPDF](https://img.shields.io/badge/jsPDF-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)

**[→ Open Green Nirman](https://greennirman.netlify.app)** &nbsp;·&nbsp; [→ Source](https://github.com/Priyanshu-ux712/GreenNirman)

<br>

### 📊 &nbsp;ATARS &nbsp;·&nbsp; `v5.4.6` &nbsp;·&nbsp; information integrity

> **Drop in a spreadsheet — get instant analysis, charts, ML, and a research-grade report.**

Turning a raw spreadsheet into real analysis normally takes code, a stack of tools, and an analyst's time, so most data simply sits unexamined. The AI tools promising a shortcut cheerfully invent the numbers instead.

ATARS is a desktop analytics studio that cleans, charts, models, forecasts, and writes the report — **computing every figure itself** and letting the AI narrate only what was actually computed. It runs offline in its own window.

- **Data quality** — an 18-step cleaning and profiling engine
- **Modelling** — AutoML with explainable AI · Isolation-Forest anomaly detection · Holt–Winters forecasting
- **Exploration** — in-process SQL over DuckDB · 19 chart types
- **Verification** — a nine-module suite that grounds every AI-written sentence against computed values (**92.9%** grounding rate)
- **Export** — PowerPoint · Word · Excel · CSV · JSON
- **AI layer** — optional, bring-your-own-key
- **Three editions, one engine** — a Windows installer, a Microsoft Store package signed by Microsoft, and `pip install atars`, a free terminal edition for Windows, macOS and Linux

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Licence](https://img.shields.io/badge/licence-proprietary,_free-22C55E?style=flat-square)
[![PyPI](https://img.shields.io/pypi/v/atars?style=flat-square&logo=pypi&logoColor=white&label=pip%20install%20atars&color=3775A9)](https://pypi.org/project/atars/)

#### The terminal edition

```bash
pip install atars
```

The same analysis engine on the command line — one-shot commands, an interactive shell, or a full-screen terminal window with 19 tabs and 17 charts. Windows, macOS and Linux, Python 3.11+.

> It is **deliberately smaller than the app**: no AI analyst, no Advanced Statistics, 17 chart types instead of 19, and no Word / PowerPoint / notebook exports. It exists for servers, SSH sessions and scripted work — and it is currently the only way to run ATARS on macOS and Linux.

**[→ Open ATARS](https://atars.netlify.app)** &nbsp;·&nbsp; [→ Download for Windows](https://github.com/Priyanshu-ux712/ATARS_WEBSITE_APP_DOWNLOAD/releases/latest) &nbsp;·&nbsp; [→ Microsoft Store](https://apps.microsoft.com/detail/9NFRBPL4T2M8) &nbsp;·&nbsp; [→ atars on PyPI](https://pypi.org/project/atars/) &nbsp;·&nbsp; [→ Terminal guide](https://pypi.org/project/atars/#description) &nbsp;·&nbsp; [→ Source](https://github.com/Priyanshu-ux712/ATARS)

<br>

### 🔍 &nbsp;TerraSight &nbsp;·&nbsp; `TS-1.1.0` &nbsp;·&nbsp; data sovereignty

> **Ask your documents anything — and watch it think, entirely on your device.**

Point TerraSight at a folder of PDFs, spreadsheets, reports, or database exports and it becomes a private research instrument: cited Q&A, automatic dashboards, statistics, and one-click reports.

- **Nothing leaves the machine** — files, search index, and embeddings all live and run locally. No cloud, no accounts, no telemetry.
- **Your own key** — connect any OpenAI-compatible provider for the language layer, or leave it empty and keep full offline retrieval and analytics.
- **Beyond answers** — surfaces open questions, contradictions, and testable hypotheses, then prints them as PDF reports.
- **No setup** — a Windows 10/11 installer. No Python, no admin rights.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Embeddings](https://img.shields.io/badge/local_embeddings-7C5CFF?style=flat-square&logo=openaigym&logoColor=white)
![Windows](https://img.shields.io/badge/Windows_10%2F11-0078D4?style=flat-square&labelColor=0078D4)
![Free](https://img.shields.io/badge/price-free-34D27F?style=flat-square)

**[→ Download the installer](https://github.com/Priyanshu-ux712/Terrasight/releases/latest)** &nbsp;·&nbsp; [→ Source](https://github.com/Priyanshu-ux712/Terrasight)

<br>

### 🔥 &nbsp;IGNIS &nbsp;·&nbsp; `IGN-01` &nbsp;·&nbsp; energy and propulsion

> **Imagine a new fuel or engine — IGNIS simulates it against real thermodynamics.**

A virtual propulsion and energy laboratory. IGNIS solves real thermodynamic cycles with genuine chemical-equilibrium combustion through Cantera — so a proposed fuel or engine geometry meets physics before it meets a budget.

- **Real chemistry** — chemical-equilibrium combustion, not curve-fitted approximations
- **Real cycles** — full thermodynamic cycle solving
- **Hard boundary** — the AI layer is *architecturally forbidden* from overriding the physics core
- **Visual** — an interactive 3D engine environment in the browser

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Cantera](https://img.shields.io/badge/Cantera-D9480F?style=flat-square&logo=moleculer&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![react-three-fiber](https://img.shields.io/badge/react--three--fiber-000000?style=flat-square&logo=threedotjs&logoColor=white)

**[→ Open IGNIS](https://ignis-in.netlify.app)** &nbsp;·&nbsp; [→ Download for Windows](https://github.com/Priyanshu-ux712/IGNIS/releases/download/v1/IGNIS-Setup.exe) &nbsp;·&nbsp; [→ Source](https://github.com/Priyanshu-ux712/IGNIS)

<br>

<details>
<summary><b>📈 &nbsp;Data Analytics Projects</b> &nbsp;— a working portfolio in Python, SQL, Excel and Power BI</summary>

<br>

Exploratory analyses, dashboards, and modelling exercises kept as a public record of method rather than as products — the workbench behind the shipped tools above.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&labelColor=F2C811)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&labelColor=217346)

[→ Browse the repository](https://github.com/Priyanshu-ux712/Data-Analytics-Projects)

</details>

---

## ◆ Research

Four open-access preprints on **Zenodo**:

| Preprint | Subject |
|:--|:--|
| [**ATARS v3.1** — Statistical framework, 18-step data-quality engine and a nine-module verification suite](https://zenodo.org/records/21072820) | Trustworthy LLM reporting of urban air quality |
| [**ATARS v2.0** — Automated Time-Series Analysis and Reporting System](https://zenodo.org/records/18866062) | Verified, automated analytical reporting |
| [**Traffic Growth, Air Pollution & Urban Policy**](https://zenodo.org/records/18879723) | A data-driven framework from an Indian megacity |
| [**World Weather Repository**](https://zenodo.org/records/17444480) | Global weather data curation |

---

## ◆ Toolkit

**Data & Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Cantera](https://img.shields.io/badge/Cantera-D9480F?style=for-the-badge&logo=moleculer&logoColor=white)

**Data Infrastructure**

![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![NASA POWER](https://img.shields.io/badge/NASA_POWER-0B3D91?style=for-the-badge&logo=nasa&logoColor=white)

**Application & Web**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)

**Systems & Delivery**

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![Inno Setup](https://img.shields.io/badge/Inno_Setup-264DE4?style=for-the-badge&labelColor=264DE4)

---

<details>
<summary><b>🏅 &nbsp;Certifications</b> &nbsp;<i>(5 — click to expand)</i></summary>

<br>

| Programme | Issuer | Focus | |
|:--|:--|:--|:--|
| **Data Analytics Job Simulation** | Tata · Forage (2026) | AI-powered analytics, EDA, predictive modelling | [`verify`](https://www.theforage.com/completion-certificates/ifobHAoMjQs9s6bKS/gMTdCXwDdLYoXZ3wG_ifobHAoMjQs9s6bKS_69f9a04248dd071e57ff9f88_1780767084264_completion_certificate.pdf) |
| **Data Analytics Job Simulation** | Quantium · Forage | Segmentation, uplift testing, reporting | [`verify`](https://www.theforage.com/completion-certificates/32A6DqtsbF7LbKdcq/NkaC7knWtjSbi6aYv_32A6DqtsbF7LbKdcq_69f9a04248dd071e57ff9f88_1780839311052_completion_certificate.pdf) |
| **Data Science Job Simulation** | British Airways · Forage | Feature engineering, predictive modelling | [`verify`](https://www.theforage.com/completion-certificates/tMjbs76F526fF5v3G/NjynCWzGSaWXQCxSX_tMjbs76F526fF5v3G_69f9a04248dd071e57ff9f88_1781026022901_completion_certificate.pdf) |
| **Build & Deploy Apps with Google AI Studio** | GUVI (2024) | Multilingual AI speech application | [`verify`](http://www.guvi.in/verify-certificate?id=572aU18774pe6749Rz) |
| **Career Edge — Young Professional** | TCS iON (2026) | Professional communication & business skills | [LinkedIn](https://www.linkedin.com/in/priyanshu-kumar-846b39320/details/certifications/) |

</details>

---

## ◆ GitHub

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Priyanshu-ux712&theme=github_dark">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Priyanshu-ux712&theme=default" alt="Priyanshu Kumar — GitHub profile summary and contribution graph" width="820">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Priyanshu-ux712&theme=github_dark">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Priyanshu-ux712&theme=default" alt="GitHub contribution statistics" width="400">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Priyanshu-ux712&theme=github_dark">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Priyanshu-ux712&theme=default" alt="Languages by repository" width="400">
</picture>

</div>

---

<div align="center">

### 🌱 &nbsp;Open to research internships and collaborations, globally.

Sustainability tech · climate-adaptive built environments · environmental data systems

[![Email](https://img.shields.io/badge/priyanshukumar9053@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:priyanshukumar9053@gmail.com)

*Let's build something that matters.* 🌍

</div>
