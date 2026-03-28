
# 🦠 COVID-19 Global Data Analysis

An end-to-end data analysis project exploring COVID-19 trends across **India, United States, Brazil, and the United Kingdom** using Python and real-world data.

---

## 📌 Project Overview

This project covers the full data analyst workflow:
- **Data Collection** — Real-world dataset from Our World in Data (90,000+ rows)
- **Data Cleaning** — Handling missing values, type conversion, feature engineering
- **Exploratory Analysis** — Summary statistics, peak detection, correlation analysis
- **Visualization** — 5 interactive charts built with Plotly, Seaborn, and Matplotlib

---

## 🔍 Key Findings

- 🇺🇸 The **United States** recorded the highest single-day peak of new cases
- 💉 Death rates dropped significantly after vaccine rollouts began in **early 2021**
- 📉 There is a **negative correlation** between vaccination rate and death rate — countries with more vaccinated people had fewer deaths per case
- 🌊 **India's second wave (April–May 2021)** was the sharpest spike in the dataset

> *(Update these findings with your actual numbers after running the notebook!)*

---

## 📊 Charts & Visualizations

| Chart | Description |
|-------|-------------|
| Line Chart | Daily new cases (7-day rolling average) per country |
| Bar Chart | Total deaths by country |
| Scatter Plot | Vaccination rate vs death rate |
| Heatmap | Monthly new cases by country (last 18 months) |
| Line Chart | Death rate over time with vaccine rollout marker |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python 3 | Core programming language |
| pandas | Data loading, cleaning, analysis |
| plotly | Interactive charts |
| seaborn | Heatmap visualization |
| matplotlib | Static charts |
| Jupyter Notebook / Google Colab | Development environment |

---

## 📁 Project Structure

```
covid-data-analysis/
│
├── covid_analysis.ipynb   ← Main notebook (all code + outputs)
├── README.md              ← This file
└── charts/                ← Saved chart images
    ├── chart1_daily_cases.png
    ├── chart2_total_deaths.png
    ├── chart3_vaccination_vs_death.png
    ├── chart4_monthly_heatmap.png
    └── chart5_death_rate_over_time.png
```

---

## 📂 Dataset

- **Source:** [Our World in Data — COVID-19 Dataset](https://github.com/owid/covid-19-data/tree/master/public/data)
- **Size:** ~90,000 rows × 67 columns
- **Coverage:** Global, from January 2020 to present
- **Key columns used:** `date`, `location`, `new_cases`, `total_deaths`, `people_vaccinated_per_hundred`, `population`

---

## 🚀 How to Run This Project

**Option 1 — Google Colab (recommended, no install needed):**
1. Open [colab.research.google.com](https://colab.research.google.com)
2. Click `File → Upload notebook` and upload `covid_analysis.ipynb`
3. Click `Runtime → Run all`

**Option 2 — Local Jupyter Notebook:**
```bash
pip install pandas plotly seaborn matplotlib kaleido
jupyter notebook covid_analysis.ipynb
```

---

## 👤 About Me

I am an aspiring data analyst with skills in **Python, SQL, and Excel**, looking to apply data-driven thinking to solve real business problems.

📧 yashaswinikunder24@gmail.com
🔗 [LinkedIn Profile]([https://linkedin.com/in/](https://www.linkedin.com/in/yashaswini-kunder-0555a2223/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BuL2SpgTAS%2FisZe1y8XYNlQ%3D%3D))

---

*This project was built as part of my data analyst portfolio. Dataset credit: Our World in Data.*
