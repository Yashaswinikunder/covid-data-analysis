# COVID-19 Data Analysis: India, US, Brazil, UK

Exploratory analysis of how COVID-19 cases and case fatality changed across four
countries, using Python (pandas, Plotly, Seaborn) and the Our World in Data dataset.

## Dataset
- Source: [Our World in Data COVID-19 dataset](https://github.com/owid/covid-19-data/tree/master/public/data)
- Size: 429,435 rows × 67 columns, 255 countries/regions, Jan 2020 – Aug 2024
- Analysed: India, United States, Brazil, United Kingdom (6,704 rows)

## What the notebook does
- Cleans and filters the data and converts types
- Builds a smoothed daily case fatality rate (CFR = smoothed deaths ÷ smoothed cases)
- Compares median CFR before vaccines (Jun–Dec 2020) and after (Jun 2021 – Jun 2023)
- Produces six charts: smoothed daily cases, total deaths, monthly cases heatmap,
  before/after CFR, CFR over time, and vaccination coverage vs CFR

## Key findings
- Total reported deaths: US 1.19M, Brazil 702K, India 534K, UK 232K.
- Median daily CFR fell in all four countries after vaccine rollout:
  India 1.37% → 0.97%, US 1.57% → 0.93%, Brazil 2.42% → 0.83%, UK 1.94% → 0.75%.
- Reporting dropped sharply after mid-2023, so recent low case counts reflect
  reduced reporting.

## Limitations
- This shows association, not causation. Testing, variants and treatment also
  changed over the same period.
- Some countries report cases in batches, so single-day peaks are unreliable.
  Smoothed values are used instead.

## How to run
1. Open [Google Colab](https://colab.research.google.com) → File → Upload notebook → `covid_analysis.ipynb`
2. Runtime → Run all

## Tools
Python, pandas, NumPy, Plotly, Seaborn, Matplotlib, Google Colab

## Author
Yashaswini · yashaswinikunder24@gmail.com
