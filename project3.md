[**Home**](/) | [**Previous Project: NYC Safety**](project1) | [**LinkedIn**](https://www.linkedin.com/in/adina-kaplan/) | [**Email**](mailto:adina.kaplan613@gmail.com) | [**Resume**](resume.pdf)

---

# Marketing ROI & High-Profit Target Identification

## Project Overview
Optimizing marketing Return on Investment (ROI) is a primary economic challenge in digital advertising, where "wasted" ad spend on non-converting customers significantly impacts profitability. This project shifts the focus from simple conversion prediction to building a Profitability Classifier. Using a dataset of over 41,000 records from a direct advertising campaign, I contributed to the idea behind the model and led the development of comprehensive visualizations to identify specific customer segments that generate a positive net return.

## Technical Methodology
* **Data Engineering & Cleaning:** Performed rigorous cleaning on the raw dataset, including resolving non-standard "unknown" values, performing median imputation, and applying `StandardScaler` to continuous variables.
* **Feature Engineering:** Implemented business logic to create a binary `Is_Profitable` target variable, assigning a fixed acquisition cost of €5 and conversion revenue of €100.
* **Modeling Strategy:** Implemented a comparative approach using Logistic Regression, Random Forest, and Gradient Boosting.
* **Optimization:** Utilized Random Undersampling to resolve class imbalance and tuned probability thresholds to maximize the F1-Score, ensuring a balance between finding profitable opportunities and avoiding costly false positives.

## My Contributions
* **Vision & Strategy:** Co-contributed to the definition of research questions focused on identifying "Profit Traps" and determining economic thresholds where profit probability drops to zero.
* **Visual Analytics & Business Strategy:** Led the design and development of all project visualizations to translate complex model outputs into an actionable "ROI Strategy Map" while actively collaborating on business strategy.
* **Cross-Functional Collaboration:** Partnered with the team on the predictive modeling process, ensuring the Random Forest champion model effectively captured complex behaviors, while maintaining consistent alignment with team progress and project objectives.

## Key Results & Findings
* **Model Performance:** The Random Forest champion model achieved an AUC-ROC of 0.8145 and an F1-Score of 0.5367.
* **Strategic Accuracy:** The system successfully predicted a total profit from the top 5,000 prospects of €3,940,932.
* **Predictive Capability:** Generated an ROI Strategy Map that allows business leaders to visualize profit probabilities, enabling surgical precision in budget allocation.
* **Final Analysis:** Analysis identified that segments such as `poutcome_success`, `month_mar`, and `month_dec` consistently generate higher mean profits, while providing sales teams with a prioritized list of contacts for immediate action.

## Project Artifacts
* **[Project Methodology](marketing_ROI_project_methodology.pdf):** Initial research framework, domain analysis, and project methodology.
* **[Analysis & Findings](marketing_ROI_analysis_and_findings.pdf):** Full analysis, machine learning implementation, and data visualizations.
* **[Data Cleaning & Engineering Pipeline](marketing_ROI_cleaning_.pdf):** Comprehensive notebook focused on data integrity, feature engineering, and preprocessing.
* **[Model Implementation & Optimization](marketing_ROI_model.pdf):** Python implementation of the machine learning models, including strategic performance and evaluation optimization.
* **Core Technical Stack:** Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn).
