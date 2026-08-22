# global-sustainable-wellbeing-powerbi
Interactive Power BI dashboard analyzing global well-being trends, GDP contributions, and key socio-economic drivers across 143 countries (2019-2025).

---

## 📌 1. What (Project Overview)

This repository contains the **Global Sustainable Well-Being Dashboard**, an interactive business intelligence project built with **Power BI and Power Query**.

The dashboard analyzes **991 validated country-year observations** across 2019–2025, focusing on:

- **Life Evaluation Index** – overall well-being
- **Economic Factors** – Log GDP per Capita
- **Social & Institutional Factors** – Social Support, Freedom of Choice, Perceptions of Corruption, and Healthy Life Expectancy

The dashboard allows users to explore country-level differences, global trends, and benchmark selected countries across multiple indicators.

---

## 🎯 2. Why (Motivation & Research Objectives)

GDP is widely used as a measure of economic performance, but it does not fully capture differences in human well-being.

This project aims to:

- **Go Beyond GDP:** Explore how economic prosperity relates to subjective well-being alongside social and institutional factors.
- **Analyze Global Trends:** Examine well-being and economic trajectories across pre-pandemic, pandemic, and recovery periods from 2019–2025.
- **Benchmark Countries:** Compare **Malaysia** with **Finland** and **Singapore** across economic, social, and institutional indicators.

---
## ⚙️ 3. How (Technical Architecture & ETL)

### ETL & Data Cleaning

Power Query was used to prepare and validate the dataset before visualization.

- **Structural Filtering:** Removed **14 countries** with severe missingness, where only 1–2 years of observations were available, to maintain usable longitudinal coverage.
- **Targeted Missing-Value Handling:** Applied forward-fill to selected country-indicator combinations with isolated missing observations.
- **Data Preparation:** Standardized country-level observations and chronological ordering to support consistent year-over-year analysis.

### Dashboard & Visual Architecture

The dashboard contains:

- **Country Slicer:** Multi-country selection for dynamic comparison.
- **Global Trends:** Line charts tracking changes in well-being and economic indicators over time.
- **World Map:** Geographic comparison of country-level well-being indicators.
- **Trajectory Analysis:** Scatter plot examining the relationship between GDP and well-being.
- **Benchmarking:** Comparison of Malaysia, Finland, Singapore, and global performance.
- **Dynamic KPI Cards:** Life Evaluation, GDP, Health, and Social Support metrics.
- **Top 10 Leaders:** Ranking countries by well-being performance.

### Interactive Features

Selecting countries, chart elements, or map regions dynamically updates related visualizations through Power BI cross-filtering.

---

## 📊 4. Results & Key Insights

### Diminishing Returns of Economic Factors

Higher economic performance does not necessarily correspond to proportionally higher well-being.

For example, **Singapore** records a higher economic factor score than **Finland**, while Finland achieves a substantially higher well-being score.

This suggests that social and institutional factors may also play an important role in well-being once countries reach higher income levels.

### Malaysia's Benchmarking Gap

Malaysia shows relatively strong social support but performs below Finland and Singapore on selected institutional and well-being indicators, particularly **Freedom of Choice** and **Perceptions of Corruption**.

### Policy Implication

The findings suggest that improving national well-being may require attention to social and institutional factors alongside continued economic development.

---

## 📷 Dashboard Preview

![Global Sustainable Well-Being Dashboard](screenshots/dashboard_overview.png)

---

## 🛠️ Tools & Technologies

- **Power BI** – Data modeling, DAX measures, interactive visualization, and dashboard development
- **Power Query** – Data cleaning, transformation, filtering, sorting, and missing-value handling
- **DAX** – Dynamic measures and KPI calculations
- **CSV** – Structured source and processed dataset




