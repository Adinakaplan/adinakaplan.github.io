# Project 2: Predictive Customer Churn Analysis

## Project Overview
This project identifies high-value customer segments at risk of attrition using predictive modeling. By analyzing historical behavior, we developed a framework to calculate churn probability and recommend targeted retention strategies.

## Technical Methodology
* **Model Comparison:** Evaluated **Random Forest** and **XGBoost** architectures; the tuned XGBoost model was selected as the superior performer with an **AUC-ROC of 0.8442**.
* **Optimization:** Conducted **Threshold Optimization** (best threshold: **0.5155**) to maximize the F1-Score for identifying churning customers.
* **Tools:** Python (Pandas, Scikit-learn, XGBoost, Seaborn).

## My Contributions
* **Vision & Strategy:** Defined the business problem of revenue protection through predictive churn modeling.
* **Data Sourcing & Engineering:** Lead for dataset acquisition and cleaning. Performed advanced feature engineering, including the creation of the **Value-at-Risk** and **Service Intensity** metrics.
* **Team Collaboration:** Partnered with Logan McCorkle and the team to refine the pipeline, focusing on one-hot encoding and handling data types for the final XGBoost run.

## Key Findings & Results
* **Churn Probability:** Identified **2,718 high-risk customers**, with top segments showing over **97% probability** of attrition.
* **Model Performance:** Achieved a **0.6336 F1-Score** for the churn class, significantly improving the baseline model's ability to identify "leavers" without over-flagging "stayers."
* **Actionable Output:** Generated a [**High-Risk Customer List**](High_Risk_Customers_for_Retention.csv) sorted by "Value at Risk," allowing management to prioritize high-revenue retention efforts.
