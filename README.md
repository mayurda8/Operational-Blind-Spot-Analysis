# Operational-Blind-Spot-Analysis
Decision-focused time-series analysis that identifies operational blind spots where dashboard KPIs appear stable while underlying volatility signals increasing risk.


# 📊 Operational Blind Spot Analysis
## When Stable KPIs Hide Rising Risk

---

## 📖 Overview

Traditional dashboards rely heavily on rolling averages and smoothed KPIs to evaluate system stability. While these metrics reduce noise, they can also obscure underlying instability and create a false sense of security.

This project introduces a **decision-oriented analytical framework** designed to detect *operational blind spots* — periods where dashboard KPIs appear stable while hidden volatility signals increasing risk.

Instead of predicting future outcomes, the focus shifts toward evaluating the **reliability of metrics themselves**, revealing when commonly used KPIs stop reflecting real system behavior.

---

## 🎯 Objectives

- Simulate real-world dashboard KPIs using rolling averages
- Detect hidden instability through volatility analysis
- Identify periods of false stability in time-series metrics
- Transform analytical insights into decision-oriented risk rankings

---

## 📊 Dataset

**Berkeley Earth Global Land Temperature Anomalies**

- Monthly time-series data
- Long historical coverage (1750–present)
- Continuous anomaly signal ideal for KPI behavior simulation

---

## 🧠 Methodology

### 1️⃣ Dashboard KPI Simulation
A 12-month rolling average is used to represent how real dashboards smooth data to monitor trends.

### 2️⃣ Hidden Risk Detection
Rolling standard deviation captures underlying instability that average-based metrics may hide.

### 3️⃣ Blind Spot Identification
A composite score quantifies periods of false stability:



### Blind Spot Score =
Normalized Volatility × (1 − Normalized KPI Change)


High scores indicate scenarios where KPIs suggest stability while risk is increasing.

---

## 📊 Key Outputs

- Dashboard KPI trend visualization
- Hidden volatility signal
- Combined blind-spot visualization
- Ranked periods of false stability
- Decision-ready analysis table

---

## 🔍 Key Insight

Stable averages do not necessarily imply stable systems.

By separating mean behavior from variability, this project demonstrates how dashboards can unintentionally create misleading confidence — and provides a framework to detect when this occurs.

---

## 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

## 🚀 Project Value

This work moves beyond traditional prediction-focused analytics toward **decision-focused metric evaluation**, helping organizations understand when their KPIs stop reflecting underlying reality.

