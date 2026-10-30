# Global Development Clustering using K-Means

<br>

## Overview

This project builds a **K-Means Clustering** model to categorize countries based on socioeconomic, health, and economic indicators. It uses Python, Pandas, NumPy, and Scikit-Learn within a Google Colab environment.

<br>

---

<br>

## Dataset Overview

- **Dataset:** Country Development Dataset (`Country-data.csv`)
- **Features:**
  - child_mort: Death of children under 5 years of age per 1,000 live births
  - exports: Exports of goods and services per capita (% of GDP)
  - health: Total health spending per capita (% of GDP)
  - imports: Imports of goods and services per capita (% of GDP)
  - income: Net income per person
  - inflation: Annual growth rate of the GDP implicit deflator
  - life_expec: Average life expectancy at birth
  - total_fer: Average number of children born to a woman
  - gdpp: GDP per capita
- **Target:** No predefined target (Unsupervised Learning)

<br>

---

<br>

## Tech Stack & Libraries

- Python
- Pandas & NumPy (data handling and preprocessing)
- Scikit-Learn (StandardScaler, K-Means Clustering)
- Google Colab / Jupyter Notebook

<br>

---

<br>

## Workflow & Steps

1. Load dataset using Pandas
2. Remove non-numeric columns such as `country`
3. Standardize features using `StandardScaler`
4. Apply K-Means Clustering with `K = 3`
5. Assign cluster labels to each country
6. Analyze country distribution across clusters
7. Predict clusters for new country data samples

<br>

---

<br>

## Results & Accuracy

- **Model Used:** K-Means Clustering
- **Number of Clusters:** 3
- **Feature Scaling:** StandardScaler
- **Learning Type:** Unsupervised Learning
- **Output:** Countries grouped into clusters based on development indicators
- **Prediction:** New country data can be assigned to the most suitable development cluster

<br>

---

## About

A machine learning project implementing K-Means Clustering in Python to analyze and group countries based on socioeconomic, health, and economic development indicators.
