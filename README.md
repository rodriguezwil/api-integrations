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

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|---------|
| `Python` | API data fetch, transformation, alert scripts |
| `Postman` | API testing and endpoint documentation |
| `Pandas` | Data cleaning and aggregation |
| `Matplotlib` / `Seaborn` | Exploratory visualizations |
| `Power BI` | Final interactive dashboard (optional) |
| `Mass.gov`, `CDC`, `SAMHSA APIs` | Public data sources |

---

## 🔁 Workflow Overview

1. **Connect** to public health API(s) with Python/Postman  
2. **Fetch & clean** data for key indicators (e.g., ER visits, suicide rates)  
3. **Analyze** trends and summarize key changes  
4. **Visualize** trends with Power BI or Jupyter Notebook  
5. **[Optional]** Trigger weekly email/slack alert with summaries

---

## 📂 Project Structure

```bash
mental-health-insights/
├── README.md
├── data/
│   ├── raw/
│   └── cleaned/
├── scripts/
│   ├── fetch_data.py
│   ├── summarize_trends.py
│   └── alert_trigger.py
├── postman/
│   └── mass-public-health-api.postman_collection.json
├── visuals/
│   └── screenshots/
├── dashboard/
│   └── MA-MentalHealth.pbix




