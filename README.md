# HR-Analysis

🔍 Project Description — Employee Attrition Analysis (Kaggle HR Dataset)

This project focuses on analyzing employee attrition trends using a Kaggle HR dataset. The aim is to discover the key factors influencing employee turnover and understand how various attributes—such as salary, job satisfaction, and overtime—affect employee retention.

The entire analysis is performed through Excel-based feature extraction and Python exploratory analysis, without using any predictive machine learning models.
Excel was primarily used for correlation analysis, pivot tables, and visual summaries to identify important features linked to attrition.

🎯 Objectives

Explore and analyze HR dataset from Kaggle.

Perform feature extraction in Excel to identify top influencing factors.

Visualize attrition patterns across departments and job roles.

Derive data-driven insights to help HR teams improve employee retention.

🧩 Project Steps

Data Collection

Dataset sourced from Kaggle’s HR Analytics dataset containing attributes such as Age, JobRole, MonthlyIncome, OverTime, JobSatisfaction, and Attrition status.

Data Cleaning

Removed missing values and duplicates.

Verified consistency of categorical variables (e.g., Department, Gender, MaritalStatus).

Feature Extraction in Excel

Used Excel formulas, pivot tables, and conditional formatting for trend analysis.

Calculated correlation between each feature and attrition to find strong relationships.

Identified top influencing factors contributing to employee turnover.

Data Analysis & Visualization

Explored relationships between attrition and:

OverTime

MonthlyIncome

YearsAtCompany

JobSatisfaction

Used charts and heatmaps to visualize patterns and highlight key drivers.

📈 Key Insights
Feature	Correlation with Attrition	Importance
OverTime	0.57	High
MonthlyIncome	-0.41	High
JobSatisfaction	-0.38	Medium
YearsAtCompany	-0.29	Medium
WorkLifeBalance	-0.21	Low

Interpretation:
Employees who frequently work overtime and have lower monthly income are more likely to leave.
Job satisfaction and years of experience also have a moderate influence on attrition.

🛠️ Tech Stack
Tool / Library	Usage
Excel	Data cleaning, correlation, visualization
Python (Jupyter Notebook)	Exploratory data analysis and plotting
Pandas, NumPy	Data manipulation
Matplotlib / Seaborn	Visualization and charts
📊 Results

Conducted end-to-end data analysis and visualization without any machine learning prediction.

Identified OverTime and MonthlyIncome as the most critical features linked to employee attrition.

Provided a clear understanding of HR metrics for decision-making.

🚀 Future Enhancements

Automate Excel feature extraction using Python scripting.

Build an interactive Power BI or Streamlit dashboard for HR teams.

Compare feature correlations across different departments and experience levels.
