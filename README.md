

# 🧠 Employee Attrition Risk Prediction

## 📁 Dataset Overview

The dataset used in this project comprises **1,470 employee records** across **35 columns**. It provides demographic, job-related, and behavioral insights that are essential for analyzing employee attrition.

### Key Features:

* **Age** – Age of the employee
* **Gender** – Male or Female
* **Department** – Business unit (e.g., Sales, HR, R\&D)
* **Job Role** – Position title within the organization
* **Monthly Income** – Employee’s monthly salary
* **Attrition** – Whether the employee left the company (Yes/No)
* **Job Satisfaction** – Satisfaction level (1 = Low, 4 = High)
* **OverTime** – Whether the employee works overtime
* **Years at Company** – Tenure with the organization
* **Education** – Education level (scale of 1–5)

---

## ❓ Problem Statement

Employee attrition is a critical concern in workforce management. High turnover rates lead to increased hiring costs, operational disruptions, and loss of valuable talent.

### 🎯 Objective:

To analyze HR data and **predict which employees are at risk of leaving** the organization using **data visualization** and **machine learning models**, thereby enabling timely and informed HR decisions.

---

## ✅ Project Workflow

### 1. 🧹 Data Cleaning using Power BI (Power Query)

Performed essential transformations to prepare the dataset for analysis:

* Removed irrelevant and redundant columns
* Renamed columns for clarity
* Converted data types (numeric, text, date)
* Handled missing values and removed duplicates
* Filtered for logical and relevant records

> **DAX Measures Created**:

* `Total Employees`
* `Average Monthly Income`
* `Total Experience`
* `Employees by Department`
* `Income by Education Level`

---

### 2. 📊 Dashboard Creation (Power BI)

An interactive dashboard was developed using the cleaned data, presenting:

* Total employee count
* Attrition rate
* Department-wise distribution
* Average monthly income
* Salary comparisons by education
* Experience metrics

This dashboard provides **a visual summary** of the organization's workforce status and aids **real-time decision-making**.

---

### 3. 📈 Exploratory Data Analysis (Python)

Used Python libraries `pandas`, `matplotlib`, and `seaborn` for visual analysis of attrition trends:

* **Attrition by Job Role** – Identified roles with high turnover
* **Attrition by Department** – Highlighted department-wise trends
* **Age Band vs Attrition** – Revealed age groups with higher attrition
* **Income vs Attrition** (Box Plot)
* **Distance from Home vs Attrition** (Box Plot)
* **Correlation Heatmap** – Detected feature relationships
* **Attrition Rate by Age Band** – Grouped percentage comparison

These visualizations provided actionable insights for feature selection and workforce planning.

---

### 4. 🤖 Machine Learning Implementation

Two supervised learning models were implemented:

#### 🔹 Model 1 – K-Nearest Neighbors (KNN)

* **Features**: `Age`, `Distance From Home`
* **Preprocessing**: Feature scaling using `StandardScaler`
* **Classifier**: `KNeighborsClassifier (n=5)`
* **Evaluation**: Accuracy & classification report
* **Visualization**: Scatter plot to show attrition distribution

#### 🔹 Model 2 – Decision Tree Classifier

* **Features**: All relevant numeric and encoded features
* **Preprocessing**: Label encoding of categorical variables
* **Classifier**: `DecisionTreeClassifier (max_depth=4)`
* **Evaluation**: Accuracy & decision tree visualization

Both models were trained using a **70:30 train-test split** to evaluate performance.

---

## 💡 Conclusion

This project provides a **complete pipeline** for understanding and predicting employee attrition using:

* **Power BI** for data cleaning and dynamic dashboards
* **Python** for in-depth exploratory data analysis
* **Machine Learning** models (KNN, Decision Tree) for prediction

By identifying high-risk employees, organizations can take **proactive retention measures**, reduce turnover, and improve workforce stability.

---

## ⚙️ Tools & Technologies

* **Power BI (Power Query, DAX)**
* **Python (pandas, seaborn, matplotlib, scikit-learn)**
* **Excel** for raw and cleaned datasets
* **Jupyter/IDLE** environment for Python development

---


