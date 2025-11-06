Evaluating Machine Learning Models for Intrusion Detection Using the NSL-KDD Dataset
====================================================================================

This project focuses on building and evaluating machine learning models for intrusion detection using the NSL-KDD dataset. The goal is to classify network connections as normal or malicious based on features such as protocol type, service, flags, byte counts, and connection statistics.

The project includes full data preprocessing, feature engineering, class balancing, training, and evaluation of multiple machine learning models for anomaly detection in cybersecurity environments.

Team
-----
Ahmed BENLAFQIH  
Chinyere CUMMINGS  
Mohamed SAÏDANE  
OCC Group 1 – 4th year students

Project Objectives
------------------
- Load and preprocess the NSL-KDD dataset  
- Encode categorical features and handle class imbalance with SMOTE  
- Train and evaluate multiple machine learning models  
- Compare performance metrics to identify the best classifier  
- Support early intrusion detection in connected and embedded systems

Dataset
-------
NSL-KDD (KDDTrain+.arff / KDDTest+.arff)  
Source: Kaggle

Key Steps
---------
1. Import ARFF files and convert them to CSV  
2. Clean and inspect data  
3. Assign official NSL-KDD feature names  
4. One-hot encode categorical variables  
5. Apply SMOTE to rebalance classes  
6. Scale numerical features  
7. Train/test evaluation using multiple models  
8. Generate metrics and confusion matrices  

Models Implemented
------------------
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- 5-fold Cross-Validation

Features of the Code
--------------------
- Custom ARFF-to-CSV loader  
- Visualizations of class distribution  
- Feature importance plots  
- Consistent preprocessing pipeline  
- Train/test column alignment  
- F1-score based evaluation  

Results
-------
Each model is evaluated on: precision, recall, F1-score, and confusion matrix.  
Models show different strengths depending on feature complexity and balance handling.

Requirements
------------
- Python 3  
- pandas  
- numpy  
- matplotlib  
- scikit-learn  
- imbalanced-learn  
- google.colab (optional)

How to Run
----------
1. Upload NSL-KDD ARFF files to your notebook or environment  
2. Run preprocessing steps  
3. Train models  
4. View metrics and plots  

Purpose
-------
This project contributes to cybersecurity by improving automated intrusion detection and anomaly detection in network traffic, especially for embedded and connected system environments.
