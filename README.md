# Mobile Usage Behavior Analysis
## Project Overview
### This project aims to analyze and predict mobile app usage behavior based on users' demographic and usage patterns. The analysis focuses on understanding the relationship between factors such as age, gender, and location and their impact on total app usage. The project also leverages machine learning to predict Total App Usage Hours based on age.

Project Objectives
Analyze mobile usage behavior across different demographics.
Identify patterns in screen time, app usage categories (Social Media, Productivity, Gaming).
Build a predictive model to estimate Total App Usage Hours based on users’ age.
Dataset
The dataset contains the following columns:

User_ID: Unique identifier for each user
Age: Age of the user
Gender: Gender of the user
Total_App_Usage_Hours: Total hours of app usage per day
Daily_Screen_Time_Hours: Average daily screen time in hours
Number_of_Apps_Used: Number of different apps used by the user
Social_Media_Usage_Hours: Hours spent on social media apps
Productivity_App_Usage_Hours: Hours spent on productivity apps
Gaming_App_Usage_Hours: Hours spent on gaming apps
Location: Geographic location of the user
Methodology
Data Preprocessing
Cleaning missing values, outlier detection, and encoding categorical variables.
Normalizing continuous variables to improve model performance.
Exploratory Data Analysis (EDA)
Analysis of screen time distribution by age and gender.
Visualization of app usage patterns across social media, productivity, and gaming categories.
Feature Engineering
Creation of new features, such as app usage ratio per category.
Predictive Modeling
Machine Learning Model: Built models to predict Total App Usage Hours based on age using algorithms such as Linear Regression and Random Forest.
Evaluation Metrics: Mean Absolute Error (MAE) and R-squared.
Results
Key insights derived from EDA:
Younger users tend to have higher gaming usage compared to other age groups.
Productivity app usage is generally higher in older age groups.
Predictive Model:
The Random Forest Regressor achieved the best performance with an R-squared score of X.XX and MAE of X.XX.
Future Work
Expanding the dataset with more demographic factors, such as occupation and income.
Improving the model by incorporating additional behavioral factors.
Deploying the model as a web application for interactive user insights.
