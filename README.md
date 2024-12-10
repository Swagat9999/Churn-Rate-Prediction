# Churn-Rate-Prediction

This project is focused on predicting customer churn using machine learning techniques. It uses a dataset of customer information and various features to predict whether a customer is likely to churn.

**Overview**
The model analyzes customer data and predicts churn probability, helping businesses identify at-risk customers. Key steps include data preprocessing, model training, and deployment through a Flask web application.

**Key Features:**
Data Preprocessing: Includes handling duplicates, encoding categorical variables, and scaling numerical data.
Machine Learning Model: Utilizes a decision tree classifier boosted with AdaBoost, fine-tuned using GridSearchCV.
Web App Deployment: Deployed using Flask, where users can input customer data to get churn predictions.
Dataset
The dataset includes information on customer behavior, such as:

CustomerID, Churn status (0 or 1), Tenure, Services used, and more.

**Technologies Used**

Python (pandas, numpy, scikit-learn)
Flask for web deployment
Matplotlib, Seaborn for data visualization
Pickle for model serialization

**Model Evaluation**

The model's performance is evaluated using metrics like accuracy, precision, recall, and F1 score.

Link to the deployed website: https://churn-rate-prediction-4.onrender.com
