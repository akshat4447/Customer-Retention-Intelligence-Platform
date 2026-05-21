# 📊 Customer Retention Intelligence Platform

An end-to-end telecom customer churn analytics system combining ensemble machine learning, SQL data pipelines, operational automation, and business intelligence dashboards.

The platform predicts high-risk churn customers, identifies key retention drivers, and provides interactive business dashboards for stakeholder decision-making.

---

![Dashboard Preview](assets/dashboard.png)

---

# 🚀 Features

## 🔹 Churn Prediction Engine
- Ensemble ML architecture
- Logistic Regression
- Random Forest
- XGBoost
- Probability-based churn scoring

## 🔹 Large-Scale Data Processing
- Processed 500,000+ telecom customer records
- SQL-based extraction and transformation
- Pandas cleaning and feature engineering pipeline

## 🔹 Business Intelligence Dashboard
- Interactive Power BI dashboards
- Tableau visualizations
- Customer segmentation analytics
- Retention KPI monitoring

## 🔹 No-Code Automation Workflow
- KNIME-based prediction pipeline
- Reduced analyst dependency
- Automated scoring workflow for non-technical teams

## 🔹 Retention Analytics
- Churn driver identification
- Customer tenure segmentation
- Contract-type risk analysis
- Monthly revenue impact analysis

---

# 🧠 Machine Learning Models

| Model | Purpose |
|---|---|
| Logistic Regression | Baseline interpretable model |
| Random Forest | Non-linear pattern learning |
| XGBoost | High-performance boosted ensemble |
| Stacked Ensemble | Final production prediction model |

---

# 📈 Model Performance

| Metric | Score |
|---|---|
| AUC | 0.89 |
| Precision | 83% |
| Recall | 81% |
| Holdout Dataset Size | 50,000 records |

---

# 📊 Key Business Insights

- Contract type emerged as the strongest churn predictor
- Low-tenure customers showed significantly higher churn risk
- Monthly charges strongly correlated with customer attrition
- Automated workflows reduced analyst dependency by ~40%

---

# 🏗️ System Architecture

![Architecture](assets/architecture.png)

---

# 📂 Project Workflow

## 1️⃣ Data Extraction
- SQL queries
- Telecom customer datasets
- Multi-table joins and aggregations

## 2️⃣ Data Cleaning & Feature Engineering
- Missing value handling
- Categorical encoding
- Numerical scaling
- Churn feature construction

## 3️⃣ Exploratory Data Analysis
- Churn segmentation
- Revenue distribution analysis
- Customer lifecycle analysis
- Correlation analysis

## 4️⃣ Ensemble Modeling
- Logistic Regression
- Random Forest
- XGBoost
- Stacked predictions

## 5️⃣ Business Intelligence Layer
- Power BI dashboards
- Tableau reporting
- Stakeholder presentation layer

## 6️⃣ Operational Automation
- KNIME no-code scoring workflows
- Automated churn prediction pipeline

---

# 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| ML Framework | Scikit-learn, XGBoost |
| Visualization | Matplotlib, Tableau, Power BI |
| Database | SQL |
| Workflow Automation | KNIME |

---

# 📂 Project Structure

```bash
customer-retention-intelligence-platform/
│
├── data/
├── notebooks/
├── sql/
├── dashboards/
├── knime-workflows/
├── models/
├── reports/
│
├── churn_model.py
├── ensemble_pipeline.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/customer-retention-intelligence-platform.git
cd customer-retention-intelligence-platform
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Prediction Pipeline

```bash
python churn_model.py
```

---

# 📸 Dashboard Screenshots

## Customer Segmentation Dashboard
![Dashboard](assets/dashboard.png)

## Churn Driver Analysis
![Drivers](assets/churn_drivers.png)

## Retention KPI Monitoring
![KPIs](assets/kpi_dashboard.png)

---

# 📈 Business Impact

- Enabled early identification of high-risk churn customers
- Improved retention intelligence through predictive analytics
- Reduced manual analyst dependency using KNIME automation
- Delivered stakeholder-ready dashboards for business teams

---

# 🔮 Future Improvements

- Real-time churn scoring API
- Cloud deployment on AWS
- SHAP explainability integration
- Streaming customer analytics
- Automated retraining pipelines
- Deep learning churn prediction models

---

# 👨‍💻 Author

AK

---

# ⭐ GitHub Topics

```txt
machine-learning
customer-churn
xgboost
powerbi
tableau
sql
predictive-analytics
business-intelligence
telecom-analytics
data-science
customer-retention
ensemble-learning
```
