# 🌆 Delhi Air Pollution & Public Health: A Data-Driven Study (2015–2020)

This project investigates the link between **monthly air pollution levels** and **respiratory/TB-related deaths** in **Delhi**, India, over a 5-year period. It merges air quality data with public health indicators to uncover trends, assess lagged effects, and explore the burden of pollution on urban mortality.

---

## 🔍 Objective

> Can air pollution indicators like PM2.5 and AQI be associated with respiratory health outcomes in Delhi?

We combine **real-world pollution data** and **government-reported death records** to explore:

- Seasonal trends in air quality and illness
- Correlation between pollutants and mortality
- Potential thresholds where deaths rise sharply
- Lagged impact of pollution on public health

---

## 📊 Methodology

### 1. Data Preparation
- Cleaned and merged monthly AQI + pollutant readings for Delhi
- Filtered HMIS health records to extract pulmonary and TB-related indicators
- Created unified dataframe from April 2015 to March 2020

### 2. Exploratory Data Analysis
- Trend plots of AQI, PM2.5, and death counts
- Seasonal patterns in pollution and health metrics
- Correlation matrix between pollutants and mortality

### 3. Lag Analysis
- Created lagged versions of AQI/PM2.5 (1, 6, 12 months)
- Correlated lagged pollution values with current-month deaths

---

## 💡 Key Insights

- Respiratory deaths are **highest between November–January**, aligning with PM2.5 peaks.
- A **moderate positive correlation (~0.3)** was observed between PM2.5 and respiratory deaths.
- Preliminary lag analysis suggests **AQI spikes may precede death increases by 1–2 months**.
- **Threshold effects** observed — TB and respiratory deaths rise sharply above **PM2.5 = 200 µg/m³**.

---
