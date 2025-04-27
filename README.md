# EXPLORATORY MACHINE LEARNING FOR BOOKING CANCELLATION PREDICTION
This project applies machine learning to predict hotel booking cancellations, using logistic regression as a baseline model and random forest for enhanced prediction performance. Key features influencing cancellations are identified, and actionable insights are summarized in a stakeholder-focused report. The end-to-end process includes data extraction, cleaning, model training, evaluation, and reporting, reflecting an early structure of MLOps workflows. A custom log file monitors the execution of automation scripts, ensuring traceability and operational control. By combining machine learning techniques, domain expertise, and process automation, this project demonstrates how predictive analytics and structured operational practices can support better decision-making in the hospitality industry.

# DATA COLLECTION
https://www.kaggle.com/datasets/mojtaba142/hotel-booking

# FILES INCLUDED
1) Classification_Metrics_Interpretation.pdf – Provides an overview of classification metrics to refresh your knowledge.
2) Doc_ML_for_Cancel_Prediction.pdf – General documentation for the project.
3) Logistic_Regression_Interpretation.pdf – Created to better understand what odds represent and I’m sharing it here in case it helps.
4) Report_to_Stakeholders.pdf – The final report for stakeholders based on the machine learning results.
5) Full_Project_Explained.pdf – Walks through the workflow used to complete the project. Since it complements the ‘LookerStudioKpiDashboard’ project, it’s also included there.
6) run_all.py – A script that automatically runs preprocessing.py and dashboard_dataframe.py.
7) preprocessing.py – Handles the transformation of the extracted data.
8) dashboard_dataframe.py – This file is only included for run_all.py to work properly and should be ignored. It’s important for the ‘LookerStudioKpiDashboard’ project.
9) cleaning.py – Contains custom functions used in preprocessing.py.
10) testing.py – Contains testing scripts to ensure the proper functioning of some custom functions.
11) dictionaries.py – Helps with manipulating the ‘country’ column.
12) results.py – Includes custom functions for model evaluation and interpretation.
13) run_all.txt – A log file that monitors the successful execution of run_all.py. I added it just to show its format.
14) logistic_regression.ipynb - The jupyter file which includes the baseline model
15) random_forest.ipynb - The jupyter file which includes the advanced ML model
16) This file - readme.txt

# HOW TO SET UP THE ENVIRONMENT
Please note that my scripts are designed to retrieve data from my local PostgreSQL database, so they may not work out-of-the-box on your machine. However, if you'd like to discuss alternative setups or solutions, feel free to connect with me on [Linkedin](https://www.linkedin.com/in/kimon-ioannis-lappas).

