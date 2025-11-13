# 📢 Marketing Campaign Analysis Using A/B Testing

A statistics‐centric project designed to analyse the effectiveness of marketing campaigns using A/B testing methodologies to compare control and test groups and derive data‐driven insights.

---

## 📌 Project Overview

This project covers the complete workflow: acquiring campaign dataset(s) with control and treatment groups, performing exploratory statistical analysis, designing and executing A/B tests, interpreting test results to draw business conclusions. The goal is to test hypotheses about marketing campaign variations and recommend the most effective strategy.

---

## 🧰 Tech Stack

* **Language:** Python
* **Libraries:** pandas, numpy, matplotlib, seaborn, scipy, statsmodels
* **Environment:** Jupyter Notebook / Google Colab

---

## 🔄 Workflow Summary

### 1. Data Collection

Dataset containing observations of campaign participants split into groups (e.g., control vs test), features such as campaign variant, user demographics, impressions, conversions or purchase counts, date/time.

### 2. Exploratory Data Analysis (EDA)

* Distribution of conversion rates / outcomes across groups
* Visualization of key features by group (impressions, clicks, conversions)
* Checking group balance (demographics, pre-campaign metrics)
* Identification of missing data, outliers, and bias in sample design

### 3. Hypothesis Definition & Test Design

* Defining null hypothesis (e.g., no difference between control and variant) and alternative hypothesis
* Setting significance level (α), selecting appropriate statistical test (e.g., z-test for proportions, t-test for means)
* Ensuring sufficient sample size and power for the test

### 4. Statistical Testing & Analysis

* Performing testing (e.g., chi-square or z-test on proportions, t-test on numeric outcomes) to compare groups
* Calculating metrics: conversion rates, lift, confidence intervals, p-values
* Interpreting results: is variation statistically significant? what is the effect size?

### 5. Insights & Business Implications

* Identifying which campaign variant delivered higher conversion or outcome metric
* Quantifying uplift, practical significance, and cost-benefit for business
* Deriving actionable recommendations (e.g., roll-out variant, adjust targeting)

---

## 📁 Project Structure

```
Marketing-Campaign-A/B-Testing/
│── data/
│── notebooks/
│── src/
│── README.md
│── requirements.txt
```

---

## 📈 Key Findings

* Conversion rate of treatment group exceeded control by X % (example)
* Statistical significance achieved (p < 0.05) indicating variant effect
* Lift was primarily driven by factor(s) such as ad type, time of contact, user segment
* Balanced group design and sampling were critical for valid inference

---

## 🚀 Future Improvements

* Expand analysis to multivariate testing (more than 2 variants) to test interaction effects. ([Wikipedia][1])
* Implement sequential or adaptive testing (multi-armed bandit) for faster optimisation. ([arXiv][2])
* Incorporate segmentation (user moderate vs high engagement) to test variant effect heterogeneity
* Build dashboard for live monitoring of A/B tests and automatic significance alerts

---

## 🧑‍💻 Author

**[Tajamul Khan](https://www.linkedin.com/in/tajamulkhann/) – Data Scientist & AI Engineer**

[1]: https://en.wikipedia.org/wiki/Multivariate_testing_in_marketing?utm_source=chatgpt.com "Multivariate testing in marketing"
[2]: https://arxiv.org/abs/2506.06316?utm_source=chatgpt.com "A Reinforcement-Learning-Enhanced LLM Framework for Automated A/B Testing in Personalized Marketing"

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
