# Predictive-Analytics-and-Readmission-Analysis-for-Diabetes-Management
Description
This project presents a comprehensive machine learning pipeline designed for the effective management of diabetes. It integrates advanced data imputation techniques, predictive modeling for diabetes risk, and an in-depth analysis of hospital readmission rates among diabetic patients. The primary goal is to leverage data-driven insights to facilitate early intervention, optimize treatment strategies, and ultimately reduce healthcare costs by minimizing readmissions.

At the core of this project is a Logistic Regression model trained to predict the likelihood of diabetes based on key clinical features. To ensure the robustness and accuracy of our predictive model, we employed a K-Nearest Neighbors (KNN) imputation method to intelligently handle missing data points, a common challenge in real-world medical datasets. The model's performance was rigorously evaluated using a suite of metrics, including accuracy, precision, recall, and the ROC-AUC score, to provide a holistic view of its predictive power.

Furthermore, this project extends beyond prediction to include a critical analysis of patient readmission. Utilizing a secondary dataset, we conducted a detailed investigation into the factors influencing hospital readmission rates for diabetic patients. This analysis specifically scrutinizes the impact of HbA1c measurements and subsequent medication adjustments. Through bivariate and trivariate statistical analyses, we uncovered significant relationships between these clinical actions, the patient's primary diagnosis, and the probability of readmission. The insights derived from this analysis are visualized through heatmaps and clustered bar plots, offering a clear and compelling case for the importance of regular monitoring and proactive patient management.

Key Features
• Advanced Data Imputation: Utilizes K-Nearest Neighbors (KNN) to accurately and intelligently fill in missing clinical data, ensuring a complete and reliable dataset for modeling.

• Predictive Modeling: Implements a Logistic Regression classifier to predict the onset of diabetes, achieving an accuracy of 76.19%.

• Comprehensive Model Evaluation: The model's performance is thoroughly assessed using key metrics:

    • Precision: 67.92%

    • Recall: 48.65%

    • ROC-AUC Score: 0.836

• In-depth Readmission Analysis: Conducts a detailed analysis of a secondary dataset to identify the primary factors affecting hospital readmission rates in diabetic patients.

• Insightful Data Visualization: Employs heatmaps and clustered bar plots to effectively communicate the significant relationships between HbA1c levels, medication changes, and patient readmission rates.
