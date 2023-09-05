# Decision Tree , Random Forest, and AdaBoost Classifier

**Decision Trees** are a popular machine learning algorithm used for both classification and regression tasks.They create a tree-like model of decisions and their possible consequences. Each internal node represents a decision based on a feature, and each leaf node represents an outcome. Decision Trees are easy to interpret and can handle both numerical and categorical data.

**Random Forest** is an ensemble learning method based on Decision Trees. It builds multiple Decision Trees during training, each using a random subset of the data and features. The final prediction is made by averaging or voting on the predictions of individual trees. Random Forests are known for their high accuracy, resistance to overfitting, and robustness.

**AdaBoost** is an ensemble technique that combines multiple weak classifiers into a strong classifier. Weak classifiers are trained sequentially, with each one focusing on the mistakes of the previous ones. AdaBoost assigns weights to the training samples, giving more weight to misclassified samples. The final prediction is a weighted combination of the weak classifiers. AdaBoost is effective for binary classification tasks and can improve performance even with simple base classifiers.

![DTreealgo](https://github.com/JAbhi09/Data-Science/assets/143057373/d14a8bcf-4e65-4999-bd1c-60c4fca35dfd)

Tools: The tools used in this Linear Regression project are essential Here are tools that involved in this porject:

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Snapml

## Project Details

**Project-1 :- Titanic Survival Prediction using Decision Trees** 

*Project Overview* 

In this project, we implemented a Decision Tree classifier to predict the survival outcomes of passengers on the Titanic, a historically significant maritime disaster. The Titanic dataset, containing passenger information such as age, gender, fare, and class, was used to build and evaluate the model. I **Build a Decision Tree classifier From Scratch** to predict passenger survival on the Titanic. Explore data preprocessing techniques, feature engineering, and decision tree construction. Evaluate the model's accuracy and analyze the insights gained from the decision tree. Methodology Data Preprocessing: Cleaned and prepared the dataset, handled missing values, and encoded categorical features. The implemented Decision Tree achieved an accuracy of approximately 80.97% on the test dataset. This suggests the model has learned meaningful patterns from the training data and can generalize reasonably well to new, unseen data. Key features contributing to predictions were identified through the decision tree's structure.

**Conclusion** This project showcased the process of building a Decision Tree classifier to predict Titanic passenger survival. While the achieved accuracy is promising, further model refinement, hyperparameter tuning, and exploration of ensemble methods could potentially enhance predictive performance. The insights gained from the decision tree contribute to understanding factors affecting survival outcomes.

**Project-2 :- Predicting Loan Repayment for LendingClub Investors**

*Project Overview* 

In this project, I aim to analyze publicly available data from LendingClub.com, a peer-to-peer lending platform connecting borrowers and investors. The primary objective is to create a predictive model that assists investors in making informed decisions by classifying borrowers based on their likelihood to fully repay loans. The dataset comprises various features, each offering insights into borrower profiles and loan attributes. These include credit policy adherence, loan purpose, interest rates, monthly installments, income, debt-to-income ratio, FICO credit scores, credit history length, revolving balances, and more. Our main goal is to develop a classification model that categorizes borrowers into two groups: those who fully repay loans and those who do not. This predictive model will help investors identify potentially risky borrowers and make investment decisions that align with their risk tolerance.

**Project-3 :- Credit Card Fraud Detection using Scikit-Learn and Snap ML (Source Coursera IBM course)**

*Project Overview* 

In this Project I will consolidate my machine learning (ML) modeling skills by using popular classification model to recognize fraudulent credit card transactions. The model is: Decision Tree. I will use a real dataset to train each of these models. The dataset includes information about transactions made by credit cards in September 2013 by European cardholders. I will use the model to assess if a credit card transaction is legitimate or not.
In the current Project, I will practice not only the Scikit-Learn Python interface, but also the Python API offered by the Snap Machine Learning (Snap ML) library. Snap ML is a high-performance IBM library for ML modeling. It provides highly-efficient CPU/GPU implementations of linear models and tree-based models. Snap ML not only accelerates ML algorithms through system awareness, but it also offers novel ML algorithms with best-in-class accuracy. 

- **Objectives**

  - Perform basic data preprocessing in Python
  - Model a classification task using the Scikit-Learn and Snap ML Python APIs
  - Train Suppport Vector Machine and Decision Tree models using Scikit-Learn and Snap ML
  - Run inference and assess the quality of the trained models



