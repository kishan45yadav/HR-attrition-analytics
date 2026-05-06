# HR-attrition-analytics
# 📊 HR Attrition Analytics

> **End-to-end HR analytics pipeline** — from raw data to machine learning predictions and an interactive Power BI dashboard.

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## 🔍 Project Overview

Employee attrition is one of the most expensive challenges organizations face. This project builds a complete analytics pipeline to **identify at-risk employees** and **uncover the key drivers** behind attrition decisions.

**Business Question:** *"Which employees are most likely to leave — and why?"*

---

## 📸 Project Screenshots

> 

### Power BI Dashboard
![image alt](https://github.com/kishan45yadav/HR-attrition-analytics/blob/main/Screenshot%20(68).png?raw=true)
![image alt](https://github.com/kishan45yadav/HR-attrition-analytics/blob/main/Screenshot%20(69).png?raw=true)
![image alt](https://github.com/kishan45yadav/HR-attrition-analytics/blob/main/Screenshot%20(70).png?raw=true)
![image alt](https://github.com/kishan45yadav/HR-attrition-analytics/blob/main/Screenshot%20(71).png?raw=true)

*Interactive Power BI dashboard with department filters, KPI cards, and attrition trends*

### Attrition by Department
![Attrition by Department](https://github.com/kishan45yadav/HR-attrition-analytics/blob/main/chart2_attrition_dept.png?raw=true)
*Bar chart showing attrition rate across all departments*

### Age vs Attrition
![Age vs Attrition](https://github.com/kishan45yadav/HR-attrition-analytics/blob/main/chart3_age_attrition.png?raw=true)
*Box plot comparing age distributions between employees who left vs. stayed*

### Monthly Income vs Attrition
![Income vs Attrition](https://github.com/kishan45yadav/HR-attrition-analytics/blob/main/chart4_income_attrition.png?raw=true)
*Income distribution analysis — lower earners show significantly higher attrition*

### Correlation Heatmap
![Correlation Heatmap](https://github.com/kishan45yadav/HR-attrition-analytics/blob/main/chart5_heatmap.png?raw=true)
*Feature correlation matrix across all numeric HR variables*

### Feature Importance (ML Model)
![Feature Importance](https://github.com/kishan45yadav/HR-attrition-analytics/blob/main/chart8_feature_importance.png?raw=true)
*Top predictors of attrition ranked by Random Forest importance scores*

### Confusion Matrix
![Confusion Matrix](https://github.com/kishan45yadav/HR-attrition-analytics/blob/main/chart7_confusion_matrix.png?raw=true)
*Model evaluation — actual vs. predicted attrition classification results*

---

## 🗂️ Repository Structure

```
hr-attrition-analytics/
│
├── 📓 HR_Analytics.ipynb           # Main analysis notebook
├── 📊 HR_Analytics_Dashboard.pbix  # Power BI dashboard
├── 📄 hr_clean.csv                 # Cleaned dataset (auto-generated)
│
├── 🖼️ images/                      # Project screenshots
│   ├── dashboard_overview.png
│   ├── chart2_attrition_dept.png
│   ├── chart3_age_attrition.png
│   ├── chart4_income_attrition.png
│   ├── chart5_heatmap.png
│   ├── chart7_confusion_matrix.png
│   └── chart8_feature_importance.png
│
├── 📋 requirements.txt             # Python dependencies
└── 📘 README.md
```

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python 3.8+ |
| Data Processing | Pandas |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn (Random Forest) |
| Dashboard | Power BI Desktop |
| Environment | Jupyter Notebook |

---

## 📈 Key Findings

| Finding | Detail |
|---|---|
| 🔴 Top Attrition Driver | **OverTime** — overtime workers are ~3x more likely to leave |
| 💰 Income Effect | Employees earning below median have **2x higher** attrition rate |
| 🏢 Riskiest Department | **Sales** has the highest department-level attrition rate |
| 🎂 Age Risk Group | Employees aged **25–35** are the highest-risk demographic |
| 😞 Satisfaction Link | Level 1 job satisfaction = **~25% attrition rate** vs. ~10% average |

---

## 🤖 ML Model Results

```
Algorithm     : Random Forest Classifier
Estimators    : 100 trees
Train/Test    : 80% / 20% split
Accuracy      : ~86%
Top Feature   : OverTime
```

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/hr-attrition-analytics.git
cd hr-attrition-analytics
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
```bash
jupyter notebook HR_Analytics.ipynb
```
> Run all cells in order — the cleaned CSV and all chart PNGs will be auto-generated.

### 4. Open the Power BI Dashboard
Open `HR_Analytics_Dashboard.pbix` in **Power BI Desktop** for the interactive dashboard.

---

## 📦 Requirements

```
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

Install all at once:
```bash
pip install pandas matplotlib seaborn scikit-learn jupyter
```

---



## 🎯 Skills Demonstrated

- ✅ Data cleaning & preprocessing (Pandas)
- ✅ Exploratory Data Analysis (EDA)
- ✅ Statistical visualization (Matplotlib, Seaborn)
- ✅ Machine learning classification (Random Forest)
- ✅ Model evaluation (accuracy, precision, recall, confusion matrix)
- ✅ Feature importance analysis
- ✅ Business intelligence dashboards (Power BI)
- ✅ End-to-end data science project delivery

---

## 👤 Author

**Your Name**
[![GitHub](https://img.shields.io/badge/GitHub-your--username-181717?style=flat&logo=github)](https://github.com/your-username)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/your-profile)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

> ⭐ If you found this project useful, please give it a star!
