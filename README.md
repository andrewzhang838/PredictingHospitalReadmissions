# PredictingHospitalReadmissions

This project aims to develop a predictive model to determine the likelihood of a patient being readmitted to the hospital within 30 days. By analyzing factors such as procedures, prior conditions, age, and test results, the system provides hospitals with insights to optimize resource allocation, monitor high-risk patients, and improve treatment strategies. The model integrates various tools like Pandas, MySQL, scikit-learn, and Tableau to handle data, create predictive models, and visualize trends.

Key highlights include:

Logistic Regression: Initially used for its simplicity in predicting binary outcomes (readmitted: yes/no). Data preprocessing included encoding categorical variables and addressing outliers.
Random Forest Classifier: Adopted to capture complex patterns in the data, achieving better performance metrics compared to logistic regression.
Tableau Dashboard: Visualizations (e.g., bar charts, line graphs) enabled exploration of trends like the correlation between age, test results, and readmission rates.
Insights: Features such as inpatient visits and emergencies were found to be the strongest predictors of readmission.
