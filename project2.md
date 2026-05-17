[**Home**](/) | [**Previous Project: NYC Safety**](project1) | [**LinkedIn**](https://www.linkedin.com/in/adina-kaplan/) | [**Email**](mailto:adina.kaplan613@gmail.com) | [**Resume**](resume.pdf)

---

# Predictive Customer Churn Analysis

## Project Overview
In the telecommunications industry, the cost of acquiring a new customer significantly exceeds the cost of retention. This project addresses this economic challenge by developing a predictive pipeline to identify at-risk subscribers. Using the IBM Telco dataset (7,043 records), I established the project vision and led the data engineering efforts to transform raw billing and demographic data into actionable features for machine learning.

## Technical Methodology
* **Data Engineering & Cleaning:** Performed critical preprocessing, including converting 'Total Charges' to numeric formats and implementing median imputation. Managed One-Hot Encoding for categorical variables to prevent the dummy variable trap.
* **Feature Engineering:** Developed custom metrics such as **Value-at-Risk**, **Service Intensity**, and **Tenure-to-Charge** ratios to capture complex loyalty patterns.
* **Modeling Strategy:** Implemented a comparative analysis between **Random Forest** and **XGBoost** architectures, utilizing **SMOTE** (Synthetic Minority Over-sampling Technique) to mitigate class imbalance.
* **Optimization:** Applied **Threshold Optimization** (optimized to **0.5155**) to maximize the F1-Score, ensuring the model prioritizes the identification of actual churners.

## My Contributions
* **Vision & Strategy:** Defined the business problem and research questions focused on maximizing the ROI of marketing interventions.
* **Data Sourcing & Engineering:** Lead responsibility for dataset cleaning, handling missing values, and engineering the features that drive model performance.
* **Collaborative Modeling:** Partnered with the team to refine the XGBoost pipeline and evaluate model metrics (AUC-ROC: **0.8442**).

## Key Results & Findings
* **Model Performance:** Achieved a **0.6336 F1-Score** for the churn class and an **AUC-ROC of 0.8442**, significantly improving the ability to distinguish between "leavers" and "stayers" compared to baseline models.
* **Strategic Accuracy:** By prioritizing Recall through threshold tuning, the model is designed to minimize "False Negatives" which is the most expensive error in churn management.
* **Predictive Capability:** The pipeline is architected to output a prioritized risk list, identifying customers with a churn probability of up to **97%** for targeted intervention.
* **Final Analysis:** Feature importance analysis reveals that churn risk is heavily driven by contractual and financial structures rather than basic demographics. The highest-risk customer segment consists of individuals on month-to-month contracts with Fiber Optic internet service, no protective add-ons (Tech Support or Online Security), and high monthly bills exceeding the $70–$80 threshold.

## Project Artifacts
* **[Project Methodology](customer_churn_project_methodology.pdf):** Initial research framework, domain analysis, and project methodology.
* **[Analysis & Findings](customer_churn_analysis_and_findings.pdf):** Full analysis, machine learning implementation, and data visualizations.
* **[Data Cleaning & Engineering Pipeline](Telco_Customer_Churn_Cleaned.html):** Comprehensive notebook focused on data integrity, feature engineering, and preprocessing.
* **[Model Implementation & Optimization](customer_churn_model.html):** Python implementation of the machine learning models, including strategic performance and evaluation optimization.
* **Core Technical Stack:** Python (Pandas, NumPy, Scikit-Learn, XGBoost, Matplotlib, Seaborn).
