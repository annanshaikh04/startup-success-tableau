# Unveiling Startup Success Patterns: Regional Insights for Smart Investments

> **The Data‑Driven Startups Success Playbook** — Insights into early funding, sector efficiency, longevity, and regional growth dynamics.

[![View in Tableau Public](https://img.shields.io/badge/Tableau%20Dashboard-View%20Interactive%20Demo-blue)](https://public.tableau.com/views/YOUR_VIZ_NAME/Overview)
[![Made with Tableau](https://img.shields.io/badge/Made%20with-Tableau-informational)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🔗 Live Demo & Downloads
- **Interactive Dashboard (Tableau Public):** 👉 [https://public.tableau.com/views/YOUR_VIZ_NAME/Overview](https://public.tableau.com/views/YOUR_VIZ_NAME/Overview)
- **Workbook (.twbx) Download:** See [`/workbook/`](./workbook/) in this repo.

> Everything on Tableau Public is visible to anyone; the `.twbx` here is provided for reviewers who want to open the workbook locally.

---

## 📸 Preview
<p>
  <img src="assets/01_cover.png" alt="Cover — Data‑Driven Startups Success Playbook" width="49%" />
  <img src="assets/06_growth_timeline.png" alt="Funding & Success Timeline by Sector" width="49%" />
</p>
<p>
  <img src="assets/07_industry_impact.png" alt="Industry Insights & Early vs Delayed Funding Impact" width="49%" />
  <img src="assets/09_longevity_map.png" alt="Sector Efficiency vs Longevity + Regional Map" width="49%" />
</p>
<p>
  <img src="assets/11_ecosystem_strength.png" alt="Ecosystem Strength vs Success by Region" width="49%" />
  <img src="assets/12_regional_comparison.png" alt="US & Canada Regional Comparison" width="49%" />
</p>

> Screenshots are in `/assets/`. Filenames above are suggestions—update if you use different names.

---

## 🧭 Story at a Glance
This project is structured as a **3‑Act narrative**:
1. **ACT 1 — Unveiling the Startup Growth Surge:** Decades‑long funding patterns and sector dominance (technology, e‑commerce, biotech).  
2. **ACT 2 — Exploring Industry & Funding Insights:** Early vs. delayed funding and their impact across sectors (education, healthcare, technology, retail, finance).  
3. **ACT 3 — Regional Ecosystem Impact:** How ecosystem/network strength correlates with success across US & Canada.

---

## 🔍 Dataset
- **Source:** Crunchbase (1902–2014), ~50,000 startups across ~750 industries  
- **Fields:** funding rounds, geographic information, startup status, industry/sector categories  
- **Key Definitions:**
  - *Startup Success:* active or acquired startups  
  - *Early Funding:* raised within first 2 years  
  - *Delayed Funding:* raised after 2 years  
  - *Longevity:* years from founding to closure/acquisition  
  - *Funding Efficiency:* success per unit of funding

### ⚠️ Caveats
- Data ends in **2014** → no COVID‑era effects or recent trends  
- Bias toward **well‑documented/larger startups**  
- **Geographic gaps** for emerging regions  
- **Industry ambiguity** (overlapping categories)  
- **Missing/incomplete** early‑year records

---

## 🧠 Key Findings
- **Funding Patterns & Sectoral Growth**
  - Technology & e‑commerce dominate post‑1990, driven by venture capital influx.  
  - Biotechnology is a consistent growth leader across decades.
- **Impact of Early Funding**
  - Highest success rates with early funding in **Education (≈97.1%)** and **Healthcare (≈96.0%)**.  
  - **Delayed funding** provides resilience in **Technology (≈93.9%)**.
- **Regional Ecosystems**
  - **Atlantic Canada** achieves ~100% success with modest funding → **efficient resource use**.  
  - Strong ecosystems (**>2 funding rounds**) predict success better than market size/location.

---

## ✅ Actionable Recommendations
- **Sectors:** Prioritize **early funding** in Education & Healthcare for cost‑effective growth; maintain **delayed funding** strategies in Technology for resilience.
- **Regions:** Invest in **underfunded high‑potential** areas like Atlantic Canada & the US Midwest; build **accelerators/support orgs** in emerging regions.
- **Ecosystems:** Strengthen **funding networks** (>2 rounds) and encourage **collaboration** among startups, investors, & policy‑makers.

---

## 🕹️ How to Use the Dashboard
- **Filters:** Sector/Industry, Funding Type (Early vs Delayed), Timeframe (decades), Region (US & Canada), Success Rate range.  
- **Map:** Hover for funding & success by state/province; use success rate slider to focus on top performers.  
- **Bubbles:** Size = longevity or funding; color = sector or region.  
- **Tooltips & Click‑to‑Focus** for deeper drill‑downs.

---

## 🛠️ Open Locally
1. Install **Tableau Desktop** (or Tableau Public app).  
2. Download the `.twbx` from [`/workbook/`](./workbook/) and open it.  
3. If data is embedded, you’re good. If extracts are expected, refresh as needed.

---

## 📂 Repository Structure
```
startup-success-tableau/
├─ README.md
├─ workbook/
│  └─ Startup_Success_Playbook.twbx
├─ assets/
│  ├─ 01_cover.png
│  ├─ 06_growth_timeline.png
│  ├─ 07_industry_impact.png
│  ├─ 09_longevity_map.png
│  ├─ 11_ecosystem_strength.png
│  └─ 12_regional_comparison.png
└─ LICENSE
```

---

## 🙋🏽‍♂️ Author
**Annanahmed Furkanahmed Shaikh** — MS in Data Science, Wentworth Institute of Technology  
- Email: shaikha4@wit.edu  
- LinkedIn: https://www.linkedin.com/in/annanahmed-shaikh  
- Portfolio: https://annanshaikh04.github.io

---

## 📝 License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
