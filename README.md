🧠 Employee Attrition Risk Prediction

 📁 Dataset Overview

This project utilizes a structured HR dataset comprising records of 1,470 employees across 35 features. Each entry represents a unique employee and includes both personal and job-related attributes. The dataset provides valuable insights into workforce dynamics and enables predictive modeling to anticipate employee attrition.

 📊 Key Features:

  Age – Age of the employee
  
  Gender – Male or Female
  
  Department – The department in which the employee works (e.g., Sales, HR, R&D)
  
  Job Role – The employee’s specific job title or function
  
  Monthly Income – The employee’s monthly salary
  
  Attrition – Indicates whether the employee has left the organization (Yes/No)
  
  Job Satisfaction – Satisfaction level on a scale from 1 (Low) to 4 (High)
  
  OverTime – Whether the employee works overtime (Yes/No)
  
  Years at Company – Total number of years spent at the company
  
  Education – Education level on a scale from 1 to 5

---

❓ Problem Statement

Employee attrition is a pressing concern for human resource departments across industries. High turnover can lead to increased recruitment costs, loss of skilled personnel, and reduced organizational performance.

 🎯 Objective:

To analyze HR data and **predict the likelihood of employee attrition** by leveraging data visualization and machine learning techniques. The goal is to support proactive strategies aimed at improving employee retention and workplace satisfaction.

---

 ✅ Methodology

 1. 🧹 Data Cleaning (Power BI – Power Query)

The raw dataset was cleaned and transformed using Power BI’s Power Query Editor. Key steps included:

 Removal of irrelevant or redundant columns
 Renaming of fields for clarity and consistency
 Conversion of data types to appropriate formats
 Handling of missing or null values
 Elimination of duplicate entries

---

 2. 📊 Dashboard Development (Power BI)

An interactive HR dashboard was created to provide a comprehensive overview of employee trends and attrition metrics. Key visualizations include:

 Total employee count
 Overall attrition rate
 Department-wise employee distribution
 Income distribution by education level
 Average monthly income
 Total experience across employees
 These visuals enable stakeholders to make real-time, data-driven decisions and identify high-risk segments within the organization.

---

 3. 📈 Exploratory Data Analysis (Python)

Python libraries such as `pandas`, `matplotlib`, and `seaborn` were used to perform detailed exploratory data analysis, including:

Attrition by Job Role
Attrition by Department
Attrition by Age Band
Monthly Income vs. Attrition (Box Plot)
Commute Distance vs. Attrition (Box Plot)
Correlation Heatmap (to identify feature relationships)

 These analyses helped uncover patterns and potential drivers of attrition within the workforce.

---

 4. 🤖 Machine Learning Implementation

A classification model was built to predict employee attrition risk using selected features. The model supports:

* Identification of high-risk employees
* Development of targeted retention strategies
* Reduction of overall employee turnover

---
 💡 Final Outcome & Impact

This project delivers an integrated solution that combines business intelligence and predictive analytics to address the challenge of employee attrition. The insights obtained empower HR professionals to:
 Intervene early in at-risk cases
 Implement data-informed retention programs
 Enhance overall employee engagement and satisfaction

 In conclusion, the project highlights how data science can effectively support HR decision-making and workforce optimization.


