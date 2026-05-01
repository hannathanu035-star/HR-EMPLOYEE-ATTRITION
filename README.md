# 📊 HR Employee Attrition Analysis

## 🧾 Overview

Employee attrition is a critical challenge for organizations, impacting productivity, morale, and operational costs.
This project performs an **exploratory data analysis (EDA)** on an HR dataset to identify patterns and factors influencing employee turnover.

The analysis leverages Python-based data science tools to generate actionable insights through statistical summaries and visualizations.

---

## 🎯 Objectives

* Analyze employee attrition trends
* Identify departments with higher turnover rates
* Examine the relationship between salary and attrition
* Understand workforce demographics such as age distribution
* Explore correlations between numerical features

---

## 📁 Dataset

* **Name:** HR Employee Attrition Dataset
* **File:** `WA_Fn-UseC_-HR-Employee-Attrition.csv`
* **Features include:**

  * Demographics (Age, Gender)
  * Job-related attributes (Department, Job Role)
  * Compensation (Monthly Income)
  * Attrition status (Yes/No)

---

## 🛠️ Tech Stack

| Tool       | Purpose                        |
| ---------- | ------------------------------ |
| Python     | Core programming               |
| Pandas     | Data manipulation & analysis   |
| NumPy      | Numerical computations         |
| Seaborn    | Statistical data visualization |
| Matplotlib | Plotting and charting          |

---

## 🔍 Methodology

### 1. Data Loading & Inspection

* Imported dataset using Pandas
* Reviewed structure, columns, and sample records
* Checked for missing values

### 2. Data Preprocessing

* Converted categorical target variable:

  * `Attrition → Attrition_num` (Yes = 1, No = 0)

### 3. Exploratory Data Analysis (EDA)

* Computed:

  * Average employee age
  * Average monthly income
* Grouped analysis:

  * Department-wise attrition rate
  * Job role-wise salary distribution

### 4. Data Visualization

* **Count Plot:** Attrition distribution
* **Histogram:** Age distribution
* **Box Plot:** Monthly income vs attrition
* **Heatmap:** Correlation between numerical features

---

## 📊 Key Insights

* Attrition varies significantly across departments
* Employees with lower income ranges tend to show higher attrition
* Workforce age distribution is centered around mid-career professionals
* Certain features exhibit meaningful correlations, aiding further predictive modeling

---
