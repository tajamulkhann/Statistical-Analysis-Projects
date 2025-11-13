# 👥 Employee Attrition Analysis

A statistical analysis project aimed at understanding and predicting employee attrition through demographic, performance, and engagement data.

---

## 📌 Project Overview

This project examines employee data to identify patterns and risk-factors associated with attrition (voluntary or involuntary). It includes exploratory analysis, hypothesis testing, feature engineering, statistical modelling, and actionable insights for HR professionals. The goal is to help organisations understand why employees leave and build strategies to improve retention.

---

## 🧰 Tech Stack

* **Language:** Python
* **Libraries:** pandas, numpy, matplotlib, seaborn, scipy, statsmodels
* **Environment:** Jupyter Notebook / Google Colab

---

## 🔄 Workflow Summary

### 1. Data Collection

Dataset includes features such as: employee ID, age, gender, department, job role, tenure, salary, job satisfaction, years since last promotion, number of trainings, and target variable indicating attrition (Yes/No).

### 2. Exploratory Data Analysis (EDA)

* Distribution of employees who left vs stayed by age, tenure, job satisfaction
* Boxplots/histograms of key features grouped by attrition status
* Correlation matrix for numeric features and attrition flag
* Summary statistics by department and role to identify high-attrition segments
* Check missing values, skewness and outliers

### 3. Hypothesis Testing & Feature Engineering

* Example hypotheses to test: “Employees with fewer trainings are more likely to leave” or “Higher job satisfaction reduces attrition risk”
* Use t-tests or chi-square tests to compare means/proportions between attrited vs retained groups
* Create derived features: e.g., tenure categories, ratio of years since last promotion to total years, training per year
* Encode categorical features (department, job role, gender) and scale numeric features if needed

### 4. Statistical Modelling & Interpretation

* Fit logistic regression or other classification models to predict attrition and interpret coefficients
* Use odds-ratios to quantify effect sizes of key predictors (e.g., odds of leaving if job satisfaction is low)
* Validate model (e.g., via cross-validation) and assess performance (accuracy, precision, recall)
* Analyse residuals and model assumptions

### 5. Insights & Business Application

* Identify top risk factors for attrition: e.g., low job satisfaction, long tenure without promotion, lack of training
* Provide actionable HR recommendations: enhanced training, promotion pathways, targeted retention programmes for high-risk roles
* Segment employees by risk and recommend monitoring or interventions

---

## 📁 Project Structure

```
Employee-Attrition-Analysis/
│── data/
│   ├── raw/
│   └── processed/
│── notebooks/
│   └── attrition_analysis.ipynb
│── src/
│   ├── preprocess.py
│   ├── features.py
│   ├── model.py
│   └── interpret.py
│── README.md
│── requirements.txt
```

---

## 📈 Key Findings

* Employees with **low job satisfaction** and **long tenure without a promotion** had a significantly higher risk of leaving.
* Departments/roles with less frequent training or promotion opportunities showed elevated attrition rates.
* Statistical tests confirmed differences in means/proportions (e.g., training per year) between attrited vs retained employees.
* Logistic regression revealed that an increase in years since last promotion was one of the strongest predictors of attrition (odds-ratio > X).

---

## 🚀 Future Improvements

* Incorporate time-series features: employee engagement trends, performance review history, successive promotions or tenure changes.
* Use survival analysis (time-to-attrition) rather than binary classification to model when attrition occurs.
* Deploy an interactive dashboard (Power BI/Tableau or Streamlit) for HR teams to visualise attrition risk by segment and track interventions.
* Add explainability tools (e.g., SHAP) to show which feature drove each employee’s risk score and support transparent decision-making.
* Validate model on external company data or roll out pilot programme to monitor retention strategy effectiveness.

---

## 🧑‍💻 Author

**[Tajamul Khan](https://www.linkedin.com/in/tajamulkhann/) – Data Scientist & AI Engineer**

---

## Let's Connect <img src="https://github.com/JayantGoel001/JayantGoel001/blob/master/GIF/Handshake.gif" height="30px" style="max-width:100%;">

<div align="center">

<a href="https://www.linkedin.com/in/tajamulkhann/">
<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
<a href="https://www.instagram.com/tajamul.datascientist/" target="_blank">
<img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=instagram&logoColor=white">
</a>
<a href="https://topmate.io/tajamulkhan" target="_blank">
<img src="https://img.shields.io/badge/Topmate-FF0000?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48Y2lyY2xlIGN4PSI1MCIgY3k9IjUwIiByPSI0MCIgZmlsbD0id2hpdGUiLz48L3N2Zz4=&logoColor=white">
</a>
<a href="https://www.whatsapp.com/channel/0029VaYs05jJkK7JKCesw42f">
<img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white">
</a>
<a href="https://t.me/tajamul_khan">
<img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white">
</a>
<a href="https://substack.com/@tajamulkhan">
<img src="https://img.shields.io/badge/Substack-%23006f5c.svg?style=for-the-badge&logo=substack&logoColor=FF6719">
</a>
<a href="https://www.kaggle.com/tajamulkhan">
<img src="https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white">
</a>
<a href="https://github.com/tajamulkhann">
<img src="https://img.shields.io/badge/Github-12100E?style=for-the-badge&logo=github&logoColor=white">
</a>
<a href="https://medium.com/@tajamulkhan">
<img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white">
</a>
<a href="https://www.youtube.com">
<img src="https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white">
</a>
</div>
