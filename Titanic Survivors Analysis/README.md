# 🚢 Titanic Survivors Analysis

A statistical analysis project focused on exploring passenger data from the Titanic sinking disaster to understand survival factors and patterns.

---

## 📌 Project Overview

This project follows a complete workflow: loading passenger data (demographics, class, ticket fare, cabin, embarked), cleaning and exploring data, performing hypothesis testing and regression modelling, and deriving actionable insights about survival factors. The goal is to understand what factors correlated with survival on the Titanic and how modelling can quantify those influences.

---

## 🧰 Tech Stack

* **Language:** Python
* **Libraries:** pandas, numpy, matplotlib, seaborn, scipy, statsmodels
* **Environment:** Jupyter Notebook / Google Colab

---

## 🔄 Workflow Summary

### 1. Data Collection

Dataset comprised of Titanic passenger records: features such as passenger class (Pclass), age, sex, siblings/spouses aboard, parents/children aboard, ticket fare, cabin, embarked port, and target variable indicating survival (Survived = 0 or 1).

### 2. Exploratory Data Analysis (EDA)

* Distribution of survivors vs non-survivors by gender and class
* Visualisations of age and fare by survival status
* Heatmap of feature correlations and missing value analysis
* Investigation of survival across embarkation ports and family relations

### 3. Feature Engineering

* Handling missing values (e.g., age imputation by median or predictive model)
* Encoding categorical variables (sex, embarked, cabin prefix)
* Creating derived features such as family size (SibSp + Parch), fare per person, age buckets
* Scaling numerical features if required
* Preparing data for modelling with train/test split

### 4. Statistical Testing & Modelling

* Hypothesis tests: for example, comparing survival rates by sex or class using chi-square or z-tests
* Logistic regression to model likelihood of survival and interpret odds ratios
* Possibly tree-based models for deeper insight into non-linear relationships

### 5. Insights & Business Application

* Identification of key survival factors (e.g., female, first class, younger age)
* Quantified effect sizes from regression model (e.g., odds of survival for females vs males)
* Actionable recommendations for data storytelling or educational purposes: how to use statistical analysis to interpret historic events

---

## 📁 Project Structure

```
Titanic-Survivors-Analysis/
│── data/
│── notebooks/
│── src/
│── README.md
│── requirements.txt
```

---

## 📈 Key Findings

* Females and first-class passengers had significantly higher survival rates
* Family size and fare per person showed meaningful patterns in survival outcomes
* Derived features improved interpretability and modelling accuracy over base features alone
* The logistic regression model provided clear odds ratio insights for stakeholders

---

## 🚀 Future Improvements

* Include interaction terms in regression (e.g., class × sex) to capture combined effects
* Explore survival prediction with tree-based methods and compare with logistic regression
* Deploy interactive visualization dashboard (e.g., Streamlit or Tableau) to explore survival patterns dynamically
* Incorporate additional historic context variables (e.g., deck level, lifeboat location) if available
* Include fairness/bias analysis (e.g., survival disparity across nationalities) for deeper insight

---

## 🧑‍💻 Author

**[Tajamul Khan](https://www.linkedin.com/in/tajamulkhann/) – Data Scientist & AI Engineer**

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
