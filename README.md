# Global COVID-19 Vaccination Analysis: SQL & Trend Visualization

## Project Overview
This project analyzes global COVID-19 vaccination trends using **SQL** and **Python**, comparing countries with high and low vaccination numbers. The goal is to provide insights into vaccination progress and trends across different countries, demonstrating SQL querying, data analysis, visualization, and hypothesis testing skills.

## Dataset
- Source: [Our World in Data – COVID-19 Vaccinations](https://github.com/owid/covid-19-data/blob/master/public/data/vaccinations/vaccinations.csv)
- Columns used:
  - `location` – country name
  - `date` – reporting date
  - `total_vaccinations` – cumulative doses administered
  - `people_vaccinated` – number of people who received at least one dose
  - `people_fully_vaccinated` – number of people fully vaccinated
  - `daily_vaccinations` – number of doses administered per day

## Hypothesis
**Question:** Do countries with higher total vaccinations have higher average daily vaccinations?  

- **Null Hypothesis (H₀):** No difference in average daily vaccinations between high-vaccination and low-vaccination countries.  
- **Alternative Hypothesis (H₁):** High-vaccination countries have higher average daily vaccinations.  

## Analysis Steps
1. **Data Cleaning & Preparation**
   - Filter out aggregated regions (World, continents)
   - Fill missing values
   - Convert `date` column to datetime
   - Flag countries as `High Vaccination` or `Low Vaccination`

2. **SQL Analysis**
   - Total vaccinations per country
   - Average daily vaccinations per country
   - A/B-style comparison of high vs low vaccination countries

3. **Visualization**
   - Bar charts for top 10 countries by total vaccinations
   - Average daily vaccinations
   - Comparison of high vs low vaccinated countries

4. **Insights**
   - Highlight top-performing countries
   - Identify trends in daily vaccination rates
   - A/B-style comparison confirms higher daily vaccination rates in high-vaccination countries

## Tools & Libraries
- **Python:** Pandas, Matplotlib, Seaborn  
- **SQL:** SQLite  
- **Notebook:** Google Colab  

## Key Takeaways
- High-vaccination countries maintain higher daily vaccination rates.  
- Trend analysis helps visualize which countries are progressing faster.  
- Demonstrates capability to perform SQL queries, data cleaning, visualization, and hypothesis-driven analysis on global datasets.

## Project Files
- `covid_vaccination_analysis.ipynb` – Colab notebook with SQL queries, Python code, and visualizations.  
- Dataset: Download directly from [Our World in Data](https://github.com/owid/covid-19-data/blob/master/public/data/vaccinations/vaccinations.csv)
