# 🌍 Global Air Quality & Weather Analytics

An end-to-end data analytics project analysing global air quality
and weather data across multiple cities — built as part of a
guided EDA project in the 2nd year of B.Tech CSE at MITAOE Pune.

---

## 👥 Team

| Name | 
|---|
| Rushikesh Kedar |
| Akash Bhuyan |
| Rahul Atkare |
| Sujal |

**Guided by:** Shubhangi Ma'am & Dr. Vaishali Wangikar Ma'am
MIT Academy of Engineering, Pune

---

## 🧭 Project Overview

This project presents a complete data analytics pipeline on
global air quality and weather data, with primary focus on
**PM2.5 concentration prediction**.

The pipeline covers:
- Data profiling and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Regression and machine learning models
- Time-series forecasting
- Association rule mining (Apriori)

---

## 📦 Dataset

| Property | Detail |
|---|---|
| Cities covered | London, Los Angeles, Sydney, Beijing, New Delhi |
| Air pollutants | PM2.5, NO₂, O₃ |
| Weather features | Temperature, humidity, wind speed |
| Temporal data | Timestamp-based records |
| Spatial data | Latitude, longitude |

### AQI Distribution

| Category | Count |
|---|---|
| Unhealthy | 1,536 |
| Unhealthy (Sensitive) | 817 |
| Moderate | 134 |
| Hazardous | 13 |

### AQI by City

| City | Average AQI |
|---|---|
| London | 146.93 |
| Los Angeles | 145.40 |
| Sydney | 145.40 |
| Beijing | 145.29 |
| New Delhi | 144.98 |

---

## 📁 Repository Structure
```
Global-Air-Quality-Weather-Analytics/
│
├── data/
│   ├── air_quality_clean.csv
│   ├── air_quality_transformed.csv
│   ├── aqi_summary_by_city.csv
│   └── aqi_category_distribution.csv
│
├── notebooks/
│   └── Global-Air-Quality-Weather-Data-Unification.ipynb
│
├── outputs/
│   └── visualizations/
│       ├── data_profiling_cleaning/     # Charts 01–07
│       ├── eda_visualization/           # Charts 08–10
│       ├── interactive_visualization/   # Chart 11
│       ├── regression_models/           # Charts 12–15
│       ├── advance_ml_models/           # Charts 16–18
│       ├── time_series_forecasting/     # Charts 19–20
│       └── association_rule_mining/     # Charts 21–22
│
├── README.md
└── requirements.txt
```

---

## 🔬 Methodology
```
Raw Data
   ↓
Data Profiling & Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Regression Models
   ↓
Advanced ML Models
   ↓
Time-Series Forecasting
   ↓
Association Rule Mining (Apriori)
```

---

## 📊 Models & Visualisations

### Regression Models
| Model | Chart |
|---|---|
| Simple Linear Regression | 12 |
| Multiple Linear Regression | 13 |
| Polynomial Regression | 14 |
| Ridge & Lasso Regression | 15 |

### Advanced ML Models
| Model | Chart |
|---|---|
| Random Forest — Actual vs Predicted | 16 |
| XGBoost & LightGBM Results | 17 |
| R² Score Comparison | 18 |

### Time-Series Forecasting
| Chart | Description |
|---|---|
| 19 | Actual vs Predicted |
| 20 | Residuals & Feature Importance |

### Association Rule Mining
| Chart | Description |
|---|---|
| 21 | Frequent Itemsets |
| 22 | Apriori Association Rules |

**Total visualisations generated: 22**

---

## ⚙️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Static visualisations |
| Plotly | Interactive visualisations |
| Scikit-learn | Regression and ML models |
| XGBoost | Gradient boosting model |
| LightGBM | Gradient boosting model |
| mlxtend | Apriori association rule mining |
| Jupyter Notebook | Development environment |

---

## 🚀 How to Run
```bash
git clone https://github.com/Rushi9234/Global-Air-Quality-Weather-Analytics.git
cd Global-Air-Quality-Weather-Analytics
pip install -r requirements.txt
jupyter notebook notebooks/Global-Air-Quality-Weather-Data-Unification.ipynb
```

---

## 👤 Author

**Rushikesh Baban Kedar**
B.Tech Computer Science Engineering | MIT Academy of Engineering, Pune (2023–2027)
GitHub: [Rushi9234](https://github.com/Rushi9234)
LinkedIn: [rushikesh-kedar](https://linkedin.com/in/rushikesh-kedar-87106b373)

---

## 📄 License

For academic and portfolio purposes only.
```

