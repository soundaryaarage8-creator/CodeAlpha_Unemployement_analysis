# CodeAlpha: Unemployment Analysis in India

This repository contains my submission for **Task 3: Unemployment Analysis with Python** as part of the Data Science Internship at CodeAlpha.

## Project Overview
The objective of this project is to perform a rigorous Exploratory Data Analysis (EDA) on the employment landscape in India during the 2020 economic season. The study tracks fluctuations in the **Estimated Unemployment Rate (%)**, **Estimated Employed**, and **Estimated Labour Participation Rate (%)** across various states and geographic sectors to analyze the systemic impact of the COVID-19 lockdown phases.

## Dataset Features Analyzed
* **Region:** The specific Indian State or Territory.
* **Date:** The recorded timeline of the economic metrics.
* **Frequency:** Interval of tracking (Monthly).
* **Estimated Unemployment Rate (%):** The percentage of the labor force currently without work.
* **Estimated Employed:** The absolute volume of citizens actively engaged in workforce positions.
* **Estimated Labour Participation Rate (%):** The proportion of the population active within the job market.
* **Area:** Categorization of region types (**Rural** vs **Urban**).

## Technologies and Data Science Libraries Used
* **Python** (Programming Language)
* **Jupyter Notebook** (Interactive Development Environment)
* **Pandas & NumPy** (Data Preprocessing, Cleaning, Handling missing `NaN` records, and Multi-variable aggregation)
* **Matplotlib & Seaborn** (Advanced Trend Visualization, Boxplots, and Categorical Bar charts)

## Machine Learning & Data Workflow
1. **Data Cleaning Pipeline:** Stripped hidden whitespace vulnerabilities from column headers and dynamically isolated and filtered out empty padding frames utilizing `dropna()` adjustments to protect time-series processing.
2. **Feature Engineering:** Extracted temporal components from raw date strings into standard datetime items to observe monthly behavioral cycles.
3. **Exploratory Data Analysis (EDA):** Generated clear statistical visual distributions including:
   * **Time-Series Line Trends:** Mapping out the immediate macro-economic spike corresponding precisely to the implementation of the national health containment mandates.
   * **State-by-State Aggregations:** Comparative bar rankings showing which regional states sustained the most substantial industrial adjustments.
   * **Sector Sector Boxplots:** A comparative visual analysis highlighting the distinct operational behavior between urban and rural labor populations.

## How to Set Up and Run the Analysis
1. Clone this project repository:
   ```bash
   git clone [https://github.com/soundaryaarage8-creator/CodeAlpha_Unemployment_Analysis.git](https://github.com/soundaryaarage8-creator/CodeAlpha_Unemployment_Analysis.git)
