# fraudDetectionMLModelAnalysis
This project was completed in a three-person group project for CIS 5450 at UPenn. This project applies supervised and unsupervised machine learning methods to build effective ML models that detect fraud.  


This project is divided into 6 different parts: 

1. Introduction
2. Data Cleaning
3. Exploratory Data Analysis
-  Time of Day and Fraudulent Rate
-  Relationship Between Transaction Amount and Fraudulent Transaction
-  Fraudulence by Transaction Type
-  Exporing Transaction Frequency
-  Exploring Buyer Gender Using Plots
4. Feature Engineering and Pre-processing
- Dropping Irrelevant Columns and Encoding Categorical Features
- Creating Region Feature Using Clustering
- Feature Correlation Heat Map
5. Modeling
- Logistic Regression (Base Model, Addiging Features with Regularization)
- Random Forest with Grid Search
- Gradient Boosting Classifier
6. Conlcusion
  Key Take-aways:
  - According to the Random Forest model we built, the most important features contributing to fraudulent transactions are 1. purchase amount, and 2. frequency of transactions within a short time frame
  - Random Forest and Boosting Classifier performed better for our dataset than Logistic Regression (Gradient Boosting Classifier model achieved 98.6% accuracy, 97% precision, and 97.3% recall in detecting fraudulent transactions) 
