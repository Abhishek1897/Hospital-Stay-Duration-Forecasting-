# End-to-End Healthcare Analytics using Snowflake & AWS

## 📌 Project Overview
This project focuses on applying **healthcare analytics** to predict **patient length of stay (LOS)** using **Snowflake** and **AWS SageMaker**. LOS is a critical healthcare metric that impacts patient outcomes, hospital capacity, and costs. By analyzing patient LOS, healthcare providers can proactively identify risks, improve care delivery, and reduce expenses.

The project demonstrates the integration of **Snowflake for data warehousing and analysis**, and **AWS SageMaker for machine learning model development, deployment, and scheduling**.

---

## 🎯 Objectives
- Perform exploratory data analysis (EDA) and feature engineering in **Snowflake**.  
- Build machine learning models to predict **patient length of stay**.  
- Fetch and preprocess data using **Snowflake connectors** in Python.  
- Deploy models in **AWS SageMaker** and perform live scoring.  
- Insert predictions back into **Snowflake** for real-time access.  
- Automate tasks with scheduling and email notifications.

---

## 🏗️ Architecture
The pipeline is designed as follows:

1. **Snowflake** – Data storage, SQL-based preprocessing, and feature engineering.  
2. **Python (SageMaker Notebooks)** – Data preprocessing, feature selection, and model building.  
3. **Machine Learning Models**:
   - Linear Regression  
   - Random Forest Regression  
   - XGBoost Regression  
4. **AWS SageMaker** – Model training, deployment, and scheduling.  
5. **Snowflake** – Store predictions for analysis and reporting.  
6. **Email Notifications** – Task status updates.

---

## 📊 Dataset
- **Training Data**: ~230,000 patient records across various hospitals and regions.  
- **Simulation Data**: ~71,000 patient records for prediction.  
- **Features**: 19 attributes including patient demographics, clinical indicators, and hospital information.  

---

## ⚙️ Tech Stack
- **Tools**: Snowflake, AWS SageMaker  
- **Programming Language**: Python  
- **Libraries**:  
  - `snowflake-connector-python`  
  - `snowflake-sqlalchemy`  
  - `pandas`, `numpy`, `scikit-learn`  
  - `xgboost`  

---

## 📂 Repository Structure
```
├── Data/
│   ├── health_data.csv
│   ├── simulation_data.csv
│
├── Python_Files/
│   ├── preprocessing.py
│   ├── feature_selection.py
│   ├── model_linear_regression.py
│   ├── model_random_forest.py
│   ├── model_xgboost.py
│   ├── scoring.py
│
├── SQL_Queries/
│   ├── data_analysis.sql
│   ├── feature_engineering.sql
│   ├── insert_predictions.sql
│
├── README.md
└── requirements.txt
```

---

## 🚀 Setup & Prerequisites
1. **Snowflake Account** – Setup and load healthcare data.  
   - Reference: [Snowflake Real Time Data Warehouse Project](https://www.projectpro.io/project-use-case/snowflake-real-time-data-warehouse-project-for-beginners)  
2. **AWS Account** – To run SageMaker notebooks.  
3. **Basic SQL Knowledge** – For working with Snowflake queries.  
   - Reference: [SQL Project for Data Analysis](https://www.projectpro.io/project-use-case/sql-project-for-data-analysis-using-subqueries-and-aggregate-functions)

---

## 🔑 Key Steps
1. **Data Analysis in Snowflake**  
   Perform EDA and understand patient LOS trends.  

2. **Feature Engineering**  
   Create derived variables and transformations in Snowflake.  

3. **Data Transfer**  
   Fetch Snowflake data into SageMaker using `snowflake-connector-python`.  

4. **Model Building**  
   Train ML models (Linear Regression, Random Forest, XGBoost).  

5. **Prediction & Scoring**  
   Insert predictions into Snowflake for further reporting.  

6. **Automation**  
   - Schedule SageMaker notebooks.  
   - Send status email notifications.  

---

## 🏆 Project Takeaways
- End-to-end integration of **Snowflake** and **AWS SageMaker**.  
- Applied **machine learning** for real-world healthcare analytics.  
- Learned **feature engineering**, **data preprocessing**, and **model deployment**.  
- Automated workflow with **scheduled scoring and email updates**.  

---

## 📧 Contact
For questions or collaboration opportunities, feel free to reach out or open an issue in this repository.
