# Churner_Analysis
# Introduction 
In today’s competitive landscape, understanding and mitigating customer churn is crucial for maintaining a strong business position. Churn analysis is a sophisticated analytical method that explores customer behavior to identify why customers leave. By leveraging advanced data analytics and machine learning techniques, businesses can predict potential churn with high accuracy and understand the underlying factors influencing customer decisions. This proactive approach enables companies to address issues early, improve customer experiences, and build stronger loyalty, leading to a sustained competitive advantage and long-term success.


# Project Goals
* Visualize & Analyze Customer Data:
* Demographic
* Geographic
* Payment & Account Info
* Services
* Study Churner Profile: Identify marketing opportunities.
* Predict Future Churners: Use machine learning to forecast churn.
# Tools & Technologies
* Database: Microsoft SQL Server
* Visualization: Power BI
* Machine Learning: Python (Scikit-learn), Jupyter Notebook
* Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, joblib
# Steps
1. ETL Process in SQL Server
* Install SQL Server Management Studio (SSMS): https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16
* Download SSMS
2. Create Database: sql
* CREATE DATABASE datebase_name
3. Import Data:
* Use Import Wizard to load CSV.

4. Data Exploration:
* Check distinct values and null counts.
* Clean and load data into prod_Churn.
* Create views for Power BI.

2. Power BI Transform
1. Data Transformation:
* Add new columns (e.g., Churn Status, Monthly Charge Range).
* Create tables for mapping Age and Tenure groups.
* Unpivot service columns.
2. Create Measures:
A. Total Customers
B. New Joiners
C. Total Churn
D. Churn Rate
3. Visualizations:
F. Summary page
G. Demographics
H. Account Info
I. Geographic analysis
J. Churn Distribution
K. Service Usage

3. Predict Customer Churn
1. Data Preparation:
* Import views from SQL Server into Excel.
* Use Jupyter Notebook for modeling.
2. Machine Learning Model:
* Algorithm: Random Forest
# Steps:
* Preprocess data
* Train model
* Evaluate model
* Predict future churners
3. Export Predictions:
* Save predictions to CSV.
4. Power BI Visualization of Predictions
1. Import Predicted Data:
 * Load data into Power BI or SQL Server.
2. Create Measures:
 * Count of Predicted Churners
3. Churn Prediction Page:
* Display predicted churners by various dimensions (e.g., Demographic, Account Info, Geographic).
