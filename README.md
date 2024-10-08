Fraud Detection with Machine Learning

Overview:

This project focuses on detecting fraudulent transactions using various machine learning models. The dataset contains anonymized transaction data, and the goal is to develop a model that can accurately predict whether a transaction is fraudulent.

The project includes the use of Logistic Regression, Random Forest, SVM, and Naive Bayes classifiers, with techniques like undersampling to handle class imbalance.

Project Structure:

+ fraud.ipynb: Jupyter notebook containing all the code for data preprocessing, model building, evaluation, and results.

Data: 

The dataset consists of anonymized features related to financial transactions and a binary target variable (Class), where 1 indicates a fraudulent transaction and 0 indicates a legitimate transaction.

Models Used:

1. Logistic Regression
2. Decision Tree Classifier

Key Libraries:

+ Pandas: For data manipulation
+ scikit-learn: For building machine learning models
+ imblearn: For handling class imbalance with undersampling
+ Matplotlib & Seaborn: For data visualization

Steps:

1. Data Preprocessing:
    + Handled missing values, data scaling, and feature selection.
2. Class Imbalance Handling:
    + Used RandomUnderSampler to address the imbalance between fraudulent and non-fraudulent transactions.
3. Model Training & Evaluation:
    + Trained models on the resampled data and evaluated them using accuracy, precision, recall, and F1 score.
    + Confusion matrix was used to visualize performance.#   F r a u d - C r e d i t - C a r d - P r e d i c t i o n  
 