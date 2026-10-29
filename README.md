# 👋 Hi, I'm Bhargav Peddi

📍 Jersey City, NJ | ✉️ [bhargavpeddi25@gmail.com](mailto:bhargavpeddi25@gmail.com) | [LinkedIn](https://www.linkedin.com/in/bhargav-peddi-b29a69178)

---

## 🛠️ Tech Stack

### 🔹 Languages & Analysis
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### 🤖 Machine Learning & AI
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EC6B23?style=for-the-badge)
![SHAP](https://img.shields.io/badge/SHAP-FF0D57?style=for-the-badge)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)

### 📊 BI & Visualization
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)

### 🗄️ Databases & Cloud
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)

---

## 🎓 Education

- **MS in Information Systems**, New Jersey Institute of Technology (NJIT), Newark, NJ (Jan 2025 to Dec 2026)
  - Dean's List: Spring 2025, Spring 2026
- **B.Tech in Information Technology**, Anurag University, Hyderabad, India (Aug 2021 to May 2024)

---

## 🚀 Featured Projects

### 🌲 [Data Mining and Predictive Analytics](https://github.com/bhargavpeddi/data-mining-predictive-analytics)
- 📝 [Read the write-up on Medium](https://medium.com/@bhargavpeddi/do-you-really-need-a-random-forest-benchmarking-3-classic-models-on-4-real-datasets-70c61b49a160)
- Logistic Regression, Decision Tree and Random Forest benchmarked on 4 real datasets (Titanic, Breast Cancer, Penguins, Diamonds)
- **97.4% accuracy** on breast-cancer diagnosis and **R² 0.99** on diamond pricing, with leakage-safe pipelines and 5-fold CV tuning
- **Tech:** Python, pandas, scikit-learn, Matplotlib, seaborn, pytest

### 🍽️ [7-Day Restaurant Demand Forecasting](https://github.com/bhargavpeddi/restaurant-sales-forecasting)
- 📝 [Read the write-up on Medium](https://medium.com/@bhargavpeddi/forecasting-a-week-of-restaurant-demand-with-an-lstm-and-being-honest-about-the-baselines-012b9b67aabb)
- TensorFlow/Keras LSTM ensemble forecasting daily visitors for 4 restaurants, 7 days ahead
- **33% lower error** than a seasonal-naive baseline on a 12-week hold-out (19.6% MAPE)
- **Tech:** Python, TensorFlow/Keras, pandas, NumPy, Matplotlib, seaborn

### 📉 [Customer Churn Prediction](https://github.com/bhargavpeddi/customer-churn-prediction)
- 📝 [Read the write-up on Medium](https://medium.com/@bhargavpeddi/predicting-customer-churn-without-fooling-yourself-smote-xgboost-and-shap-0f65369e73d6)
- XGBoost on the public IBM Telco Customer Churn dataset (7,043 customers), tuned with 5-fold cross-validation
- **80.1% accuracy** and **0.85 ROC-AUC** on a 1,409-customer test set; the top 20% of risk scores contain **50% of all churners** (2.5x lift)
- SHAP explanations: tenure, contract length, fiber optic internet, and electronic-check payments drive churn the most
- **Tech:** Python, pandas, scikit-learn, imbalanced-learn, XGBoost, SHAP

### 🏥 [Patient Readmission Risk Analysis](https://github.com/bhargavpeddi/patient-readmission-risk-analysis)
- 📝 [Read the write-up on Medium](https://medium.com/@bhargavpeddi/where-do-hospital-readmissions-concentrate-a-sql-first-analysis-623689532ce0)
- Row-level validation, then SQL analysis of 10,000 discharge encounters in SQLite
- **14.9%** overall 30-day readmission rate; high-risk segment at **28.9%** vs 8.6% for low risk
- Exports department, monthly, and segment summaries as CSVs ready for Power BI
- **Tech:** Python, SQL, SQLite, matplotlib

### ⚙️ [BI Data Pipeline](https://github.com/bhargavpeddi/realtime-bi-data-pipeline)
- 📝 [Read the write-up on Medium](https://medium.com/@bhargavpeddi/a-data-pipeline-that-rejects-bad-rows-instead-of-loading-them-8e5f8c7b739e)
- Micro-batch ETL across three sources (events, accounts, regional targets), 500 events per batch
- Rejects bad rows with a logged reason: **5,000 loaded, 2 rejected** (duplicate ID, unknown account)
- Transactional loads into SQLite and a daily KPI table by region
- **Tech:** Python, SQL, SQLite, ETL

### 🔔 [Peak Posting Job Alert](https://github.com/bhargavpeddi/peak-posting-job-alert)
- 📝 [Read the write-up on Medium](https://medium.com/@bhargavpeddi/i-built-a-chrome-extension-so-id-see-job-postings-in-the-first-hour-8c38150d3da8)
- Chrome extension (Manifest V3) that checks LinkedIn, Indeed, Dice, Wellfound, and YC Work at a Startup every 15 minutes
- Runs 262 saved searches, keeps only fresh postings, filters out 148 staffing firms and citizenship-only roles, and sends the rest to Slack
- Dashboard with run history, board and region filters, CSV export, and an optional Hunter.io contact lookup
- **Tech:** JavaScript, Chrome Extensions API, Slack webhooks, Hunter.io API

> The readmission and pipeline projects run on seeded, generated datasets. Each project runs end to end with a few commands and includes tests.

---

## 📫 Contact

Open to data science, healthcare analytics, BI, and data engineering roles.
[LinkedIn](https://www.linkedin.com/in/bhargav-peddi-b29a69178) · [Email](mailto:bhargavpeddi25@gmail.com)
