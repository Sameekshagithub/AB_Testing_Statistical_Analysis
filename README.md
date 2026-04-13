# 📊 Statistics & A/B Testing Project

## 📌 Overview

This project demonstrates an end-to-end Statistics and A/B Testing workflow designed to simulate real-world experimentation scenarios. It covers data generation, exploratory data analysis (EDA), hypothesis testing, segmentation analysis, power analysis, and Bayesian A/B testing techniques.

The goal of this project is to showcase practical statistical methods used in data science, product analytics, and experimentation-driven decision making.

---

## 🚀 Sections Covered

### 1. Setup & Data Generation

* Simulates realistic user-level data
* Includes conversions, revenue, session duration, device type, and user segments
* Designed to mimic real-world experimentation datasets

### 2. Exploratory Data Analysis (EDA)

* 6-panel visualization dashboard
* Conversion rate bar charts
* Revenue distribution plots
* Boxplots for session duration
* Device and user segment breakdowns
* Daily trend analysis

### 3. Pre-Experiment Checks

* Sample Ratio Mismatch (SRM) detection using Chi-Square test
* Covariate balance validation
* Ensures experimental reliability before analysis

### 4. Primary Metric: Conversion Rate

* Two-Proportion Z-Test
* Confidence Interval (CI) visualization
* Z-distribution plot for hypothesis testing

### 5. Secondary Metrics Analysis

* Mann-Whitney U Test for revenue (non-parametric analysis)
* Welch's t-test for session duration comparison

### 6. Segmentation Analysis

* Subgroup analysis by:

  * Device type
  * User segment
* Lift heatmap visualization for performance comparison

### 7. Multiple Testing Correction

* Bonferroni correction method
* Benjamini-Hochberg (False Discovery Rate) adjustment
* Reduces risk of false positives

### 8. Power Analysis

* Sample size estimation curves
* Minimum Detectable Effect (MDE) sweeps
* Power vs. sample size visualization

### 9. Bayesian A/B Testing

* Beta-Binomial conjugate model
* Posterior probability distributions
* Sequential monitoring for continuous experimentation

### 10. Executive Dashboard

* KPI summary cards
* Confidence interval visualization
* Trend line analysis
* Business impact estimation ($)
* Final recommendation based on statistical results

---

## 🛠️ Tools & Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* SciPy
* Statsmodels
* Jupyter Notebook

---

## 📂 Project Structure

```
statistics-ab-testing-project/
│
├── data/
├── notebooks/
├── visuals/
├── results/
├── README.md
└── requirements.txt
```

---

## 🎯 Key Learning Outcomes

* Applied statistical hypothesis testing
* Designed and validated A/B experiments
* Performed segmentation and business impact analysis
* Implemented power and sample size calculations
* Used Bayesian methods for decision making

---

## 📈 Use Cases

* Product experimentation
* Marketing campaign testing
* Conversion rate optimization (CRO)
* Data science and analytics portfolios
* Statistics and machine learning projects

---

## 👩‍💻 Author

**Sameeksha Rai**
Computer Science Graduate | Data Science & AI Enthusiast
Passionate about Statistics, Machine Learning, and Data-Driven Decision Making

---

## ⭐ If you find this project useful

Consider giving it a star on GitHub and sharing it with others in the data science community.
