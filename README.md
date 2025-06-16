
# week3-insurance-analytics

# ACIS Insurance Risk Analytics

# 🚗 AlphaCare Insurance Analytics – Week 3 Challenge (10 Academy)

## 📊 Project Overview

This project is part of the 10 Academy Week 3 challenge, focused on insurance analytics. We aim to support AlphaCare Insurance Solutions (ACIS) in building advanced predictive models and risk-based pricing systems. Using historical car insurance data, our objective is to derive actionable insights to:

- Optimize marketing strategies
- Discover low-risk customer segments
- Suggest potential premium reductions to attract more clients

---

## 🎯 Business Objectives

1. **Understand car insurance risk** across various demographics and geographies.
2. **Analyze claims data** to determine high-risk and low-risk profiles.
3. **Perform A/B hypothesis testing** on critical risk factors.
4. **Build machine learning models** to predict claim severity and recommend premiums.
5. **Develop reproducible workflows** using Git, DVC, and GitHub Actions.

---

## 📁 Project Tasks & Deliverables

### ✅ Task 1: Exploratory Data Analysis (EDA)
- Data quality checks
- Loss Ratio (Claims / Premium) by gender, province, vehicle type
- Outlier detection and temporal trend analysis
- Beautiful & insightful visualizations

### ✅ Task 2: Data Version Control (DVC)
- Reproducible data pipeline with DVC
- Local remote storage setup
- Versioned data tracked using Git and DVC

### 🔬 Task 3: Hypothesis Testing
- Statistical tests (t-tests, chi-squared)
- Null hypotheses:
  - No risk differences across provinces or zipcodes
  - No margin difference between regions
  - No gender-based claim differences

### 🤖 Task 4: Machine Learning Modeling
- Regression models for claim severity
- Premium prediction models
- Risk-based pricing framework
- Feature importance analysis using SHAP

---

## 📦 Dataset

**Time Period:** Feb 2014 to Aug 2015  
**Data Source:** Provided by 10 Academy for educational purposes  
**Main Features Include:**

- **Client Info:** Gender, Marital Status, Citizenship, Legal Type
- **Location Info:** Province, PostalCode, Cresta Zone
- **Vehicle Info:** Make, Model, Engine Size, Vehicle Age
- **Policy Info:** Premium, Claim Amount, Cover Type
- **Payment & Claims:** TotalPremium, TotalClaims

---

## ⚙️ Tech Stack

- 🐍 Python (Pandas, Seaborn, Matplotlib, Scikit-learn, Statsmodels)
- 📊 Jupyter Notebooks
- 🗃️ DVC (Data Version Control)
- 🔁 Git & GitHub
- 🧪 Pytest / GitHub Actions (for CI/CD setup)

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/abeni505/week3-insurance-analytics.git
cd week3-insurance-analytics
```

### 2. Create Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Setup DVC

```bash
dvc init
dvc remote add -d localstorage /path/to/your/local/storage
dvc pull
```



## 📂 Folder Structure

```bash

week3-insurance-analytics/
│
├── data/                  # Raw and cleaned datasets (tracked with DVC)
├── notebooks/             # EDA, hypothesis testing, modeling notebooks
├── src/                   # Python scripts and utility functions
├── plots/                 # Saved visualizations
├── dvc.yaml               # DVC pipeline stages (if used)
├── .dvc/                  # DVC config and metadata
├── .github/workflows/     # GitHub Actions config
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── .gitignore             # Files to ignore in Git
```



## Author
Abenezer M. Woldesenbet

