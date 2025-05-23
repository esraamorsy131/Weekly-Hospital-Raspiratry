# Weekly U.S. Hospital Respiratory Data (2020–2024)

This repository contains a dataset compiled from weekly hospital reports across U.S. states, spanning from 2020 to 2024. It focuses on inpatient and ICU bed availability and usage, particularly for respiratory illnesses such as COVID-19, Influenza, and RSV (Respiratory Syncytial Virus).

---

## 📁 Dataset Overview

* **Time Range**: 2020 to 2024 (weekly granularity)
* **Geographic Scope**: U.S. states
* **Columns**: 157 attributes including:

  * Inpatient/ICU beds (total, adult, pediatric)
  * Bed occupancy rates
  * Weekly admissions related to COVID-19, Influenza, RSV
  * Percentage changes from prior weeks

---

## 🧠 Potential Use Cases

* Epidemiological studies and time-series trend analysis
* Forecasting healthcare resource needs
* Public health dashboards
* Comparative studies across states and age groups

---

## 📊 Example Analyses

* Weekly trends in ICU occupancy and inpatient occupancy : dentify trends over time for hospital capacity, occupancy, and admissions for COVID-19, Influenza, and RSV.
* Correlation between bed availability and RSV/COVID/Influenza outbreaks:Examine how different illnesses contributed to hospital burden.
* State-by-state capacity tracking : Analyze differences in respiratory illness metrics across Regions
* Seasonal analysis for three disease admission :Determine seasonal patterns in hospital admissions
* Hospital Utilization Metrics: Assess hospital strain over time by comparing capacity and occupancy.
* Outlier Metrics: Identify unexpected spikes or dips in hospitalizations and admissions.
  

---

## 💡 Getting Started

You can load and explore the data using Python (e.g., with `pandas`):

```python
import pandas as pd

df = pd.read_csv('raw_weekly_hospital_respiratory_data_2020_2024.csv')
print(df.head())
```

---

## 📜 Dynamic Dasboard

Link:https://app.powerbi.com/groups/02b66986-42c9-4a1b-9090-459956b4a268/reports/922a1754-ca09-4707-99c2-5820f50cf3d5/96eb662db00011d8308b?experience=power-bi
---

## 🤝 Contributing

Contributions and analyses are welcome. Feel free to fork this repo and share your insights or visualizations!
 
