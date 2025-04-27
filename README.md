# EXPLORATORY MACHINE LEARNING FOR BOOKING CANCELLATION PREDICTION
This project uses machine learning to predict hotel booking cancellations. It leverages a dataset with various features related to hotel bookings, such as lead time, market segment, and number of nights. The goal is to identify key factors that contribute to cancellations and build predictive models that can be used by hotel owners to reduce cancellations.

Two machine learning models are used: a logistic regression model as the baseline, and a random forest model for more advanced prediction. The models focus on identifying the most important features that affect cancellations, and the results from both models are analyzed for actionable insights.

An in-depth report is prepared for stakeholders, summarizing the findings from the machine learning models and explaining the factors that lead to booking cancellations. This report helps hotel owners understand the critical factors and provides recommendations for improving their booking processes.

By combining machine learning and domain knowledge, this project demonstrates how predictive analytics can be applied to improve decision-making in the hospitality industry.

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
13) run_all.txt – A log file that monitors the successful execution of run_all.py.
14) hotel_booking.csv – Raw data from Kaggle.

# HOW TO SET UP THE ENVIRONMENT
Please note that my scripts are designed to retrieve data from my local PostgreSQL database, so they may not work out-of-the-box on your machine. However, if you'd like to discuss alternative setups or solutions, feel free to connect with me on [Linkedin](https://www.linkedin.com/in/kimon-ioannis-lappas).

