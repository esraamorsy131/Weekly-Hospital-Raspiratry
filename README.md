# 🏥 Weekly U.S. Hospital Respiratory Data (2020–2024)

A dataset tracking ICU and inpatient bed usage across U.S. states due to respiratory illnesses (COVID-19, Influenza, RSV) from 2020–2024.

---

## 📁 Dataset Overview

- **Period**: 2020–2024
- **Granularity**: Weekly
- **Scope**: U.S. States
- **Attributes**: 157 columns including admissions, bed capacity, occupancy, etc.

---

## 📊 Exploratory Data Analysis (Python)

The file `respiratory_analysis.ipynb` contains:

- Data loading and initial inspection
- Null value treatment and datatype conversion
- Weekly trend plotting (using matplotlib/seaborn)
- State-level comparison for RSV/COVID/Flu admissions
- Correlation heatmaps and anomaly detection

#### Sample Code Snippet:
```python
import pandas as pd
import matplotlib.pyplot as plt

df = pd.read_csv('raw_weekly_hospital_respiratory_data_2020_2024.csv')
df['week'] = pd.to_datetime(df['week_ending_date'])

plt.figure(figsize=(12,6))
df.groupby('week')['total_adult_inpatient_beds_occupied'].mean().plot()
plt.title("Average Weekly Inpatient Occupancy (2020–2024)")
plt.show()




#### 📈 Interactive Dashboard (Power BI)
A live dashboard was developed to present:

ICU/Inpatient trends over time

RSV/COVID/Influenza admission rates

State-by-state comparisons

Peak occupancy weeks and capacity trends

🔗 Live Power BI Dashboard:
Click to View Dashboard

📷 Dashboard Preview:



🧠 Key Use Cases
Hospital burden forecasting

Respiratory disease seasonality

Real-time public health decision support

Outlier detection for emergency response

🤝 Contributing
Fork the repo and submit your analysis or improvements via pull request!

yaml
Copy
Edit
