# social-media-mental-health-project
# 📱 Student Social Media and Mental Health Impact: Exploratory Data Analysis & Modeling

An end-to-end data science project exploring the relationship between student social media usage habits, academic patterns, and mental health metrics using Python.

---

## 🚀 Project Overview
With the rapid integration of digital platforms into daily life, understanding how social media consumption affects student well-being is critical. This project performs rigorous data cleaning, statistical skewness analysis, univariate/bivariate visualizations, and builds a machine learning pipeline to evaluate and predict mental health scores based on behavioral habits.

---

## 🛠️ Technologies Used
* **Language:** Python 
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn (`SimpleImputer`, `StandardScaler`, regression metrics)
* **Environment:** Jupyter Notebooks (`.ipynb`) / VS Code

---

## 📊 Key Analysis Steps
1. **Data Cleaning & Preprocessing:** Handling missing values, checking data types, and setting up automated imputation and scaling pipelines.
2. **Exploratory Data Analysis (EDA):** 
   * Analyzing statistical skewness of numerical features.
   * Visualizing distributions using histograms, boxplots (for outlier detection), and correlation heatmaps.
3. **Machine Learning Pipeline:** 
   * Splitting data into Training, Validation, and Test sets.
   * Building a robust pipeline to predict mental health impact scores and evaluating performance using $R^2$ and RMSE metrics.

---

## 📂 Repository Structure
```text
social-media-mental-health-project/
│
├── student_mental_health_analysis.ipynb   # Main Jupyter Notebook containing EDA & ML pipeline
├── .gitignore                             # Ignored system and environment files
└── README.md                              # Project documentation