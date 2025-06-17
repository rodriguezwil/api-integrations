# 🧠 Mental Health Insights Dashboard – Massachusetts

This project explores the **rise of mental health challenges in the state of Massachusetts** using public data sources and API automation. It aims to analyze trends in depression, suicide rates, behavioral health ER visits, and therapy access gaps — with a focus on delivering actionable insights for healthcare organizations, community leaders, and policy makers.

---

## 📌 Project Objectives

- Pull mental health data from public health APIs (CDC, Mass.gov, SAMHSA)
- Track trends over time: suicide rates, ER visits, behavioral diagnoses
- Visualize insights via Power BI or Python dashboards
- Create a weekly data pull and alert automation process
- Provide healthcare stakeholders with digestible summaries

---

## 💻 Tools & Technologies

| Tool | Purpose |
|------|---------|
| `Python` | API data fetch, transformation, alert scripts |
| `Postman` | API testing and endpoint documentation |
| `Pandas` | Data cleaning and aggregation |
| `Matplotlib / Seaborn` | Exploratory visualizations |
| `Power BI` | Final interactive dashboard (optional) |
| `Mass.gov`, `CDC`, `SAMHSA APIs` | Public data sources |

---

## 🔁 Workflow Overview

1. **Connect** to public health API(s) with Python or Postman  
2. **Fetch & clean** mental health statistics (e.g., ER visits, suicide data)  
3. **Analyze** and extract insights using Python  
4. **Visualize** patterns with Jupyter Notebook or Power BI  
5. **[Optional]** Trigger weekly digest alert (email, Slack, or report)

---

## 📂 Project Structure

mental-health-insights/
├── README.md
├── data/
│ ├── raw/ # Raw files (CSV, JSON, etc.)
│ └── cleaned/ # Pre-processed or filtered data
├── scripts/
│ ├── fetch_data.py # Grabs latest mental health data from API
│ ├── summarize_trends.py # Extracts trends from the dataset
│ └── alert_trigger.py # Sends weekly summary (Slack/email)
├── postman/
│ └── mass-public-health-api.postman_collection.json
├── visuals/
│ └── screenshots/ # Static charts or dashboard snippets
├── dashboard/
│ └── MA-MentalHealth.pbix # Power BI dashboard file (optional)

---

## 📊 Sample Insights Tracked

- Suicide rates by age group and Massachusetts county  
- Behavioral health emergency room visits  
- Depression diagnosis trends in youth (ages 12–17) and adults  
- Therapy provider shortages and wait time averages  
- Year-over-year trend comparison (2020–2024)

---

## 🌍 Why This Matters

Mental health needs in Massachusetts — and across the U.S. — have spiked post-pandemic. Communities need tools that highlight vulnerable populations, overwhelmed systems, and where to allocate resources. This dashboard helps support that mission using data and automation.

---

## 🚀 Status

- ✅ Project initialized
- 🟡 Public API research and data pipeline in development
- 🔜 Dashboard + alert automation under construction

---

## 📫 Contact

**Created by:** Wilfredo Rodriguez  
[LinkedIn](https://www.linkedin.com/in/wil-rodriguez) | [Email](mailto:wilrod38@gmail.com)

> “Build with purpose. Lead with clarity. Secure and automate what matters.”





