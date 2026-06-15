

# 🌍 Global Air Quality & Weather Analytics Platform> A Production-Grade 17-Stage Data Engineering and Non-Linear Predictive Modeling Pipeline.

[![Python](https://shields.io)](https://python.org)
[![Framework](https://shields.io)](https://scikit-learn.org)
## 🚀 Executive Performance Scorecard* **Target Objective:** Quantify and forecast hourly ambient $PM_{2.5}$ concentration levels globally.* **Winning Architecture:** Random Forest Regressor (Variance-Reducing Ensemble Framework).* **Primary Metric Performance:** **$R^2$ Score: 0.84** (Capturing 84% of environmental variance).* **Key Statistical Discovery:** Traditional linear and polynomial models underperformed drastically ($R^2 < 0.003$), proving atmospheric pollutant accumulation is fundamentally governed by complex, multi-variable non-linear feature interactions (Stagnant Wind Speed $\times$ Elevated Relative Humidity).
## 🛠️ System Architecture & Pipeline WorkflowThe data core implements an industry-standard, auditable **17-Stage MLOps Execution Pipeline**:


(Raw Sensor Excel) ──> (Schema & Unit Standardization) ──> (Linear Interpolation Imputation)
│
(Ensemble Inference (R²=0.84)) <── (Feature Engineering (Lags/MA3)) <── (IQR Outlier Capping)


## 📊 Model Scoreboard Comparison
Every candidate engine was cross-validated under identical historical data matrices:

| Model Rank | Core Framework Family | Metric ($R^2$ Score) | Engineering Assessment |
| :--- | :--- | :--- | :--- |
| **Rank 1 (WINNER)**| **Random Forest Regressor** | **0.8416** | **Optimal execution out-of-the-box on constrained data layout.** |
| Rank 2 | LightGBM Regressor | 0.5269 | Underperformed baseline; requires complex hyperparameter tuning. |
| Rank 3 | XGBoost Regressor | 0.5262 | Sequentially over-fit small variance paths before calibration. |
| Rank 4 | Multiple Linear Regression| 0.0023 | Failed totally due to severe structural under-fitting patterns. |

## 💡 Engineering Key Takeaways
1. **Atmospheric Inertia:** Time-series lag feature engineering (`pm25_lag1`) emerged as a dominant predictive driver, validating that past near-term concentration footprints determine subsequent target values.
2. **Apriori Corroboration:** Running unsupervised association rule mining verified an explicit physical relationship pattern—identifying a 51.3% high-confidence co-occurrence metric joining low wind limits with maximum air contamination values.

## 💻 Technical Implementation Details

### 📂 Repository Structure

Global-Air-Quality-Weather-Analytics/
│
├── data/
│ ├── air_quality_clean.csv
│ ├── air_quality_transformed.csv
│ ├── aqi_summary_by_city.csv
│ └── aqi_category_distribution.csv
│
├── notebooks/
│ └── Global-Air-Quality-Weather-Data-Unification.ipynb
│
├── outputs/
│ └── visualizations/
│
├── README.md
└── requirements.txt


### 🔢 Feature Set & Column Schema
The system maps 10 raw features into 16 engineered features:
* `timestamp`: Datetime UTC index.
* `city`: Evaluation metrics location layer (London, Los Angeles, Sydney, Beijing, New Delhi).
* `pm25`: Target $PM_{2.5}$ metric concentration ($\mu g/m^3$).
* `no2` / `o3`: Dynamic secondary environmental markers ($\mu g/m^3$).
* `temperature` / `humidity` / `wind_speed`: System physical weather triggers.
* `AQI` / `AQI_Category`: Piece-wise linear interpolation EPA reference bounds.
* `pm25_ma3`: 3-hour structural moving average calculation.
* `pm25_lag1` / `pm25_lag3`: Multi-hour performance inertia tracking keys.
* `is_polluted`: Analytical flag ($AQI > 100$).

## ⚙️ Execution Lifecycle & Deployment Replication
To launch the end-to-end data analytics pipeline and replicate modeling scorecard metrics, step through the terminal lifecycle sequence below:

```bash
# 1. Clone Version Controlled Core System
git clone https://github.com
cd Global-Air-Quality-Weather-Analytics

# 2. Synchronize Production Virtual Environment Dependencies
pip install -r requirements.txt

# 3. Boot Local Dynamic Notebook Instance
jupyter notebook notebooks/Global-Air-Quality-Weather-Data-Unification.ipynb
```

## 👥 Engineering Team Blueprint
* **Rushikesh Kedar** — *Machine Learning Pipeline Design, Evaluation Core, SHAP Validation Interrogation*.
* **Akash Bhuyan** — *Feature Engineering Optimization, Descriptive Exploratory Analysis (EDA)*.
* **Rahul Atkare** — *Data Profiling Curation, Matrix Imputation Algorithms, Visualizations Layout*.
* **Sujal Khandelwal** — *Business System Framing, Analytical Documentation Auditing*.
* **Project Guides:** Guided under the academic reference loop of Dr. Shubhangi Kale and Dr. Vaishali Wangikar at MIT Academy of Engineering (MITAOE), Pune.

------------------------------
Let me know if you would like me to output the full markdown file for CraveConnect next.

