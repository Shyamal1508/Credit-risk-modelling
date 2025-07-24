Credit Risk Modelling

Overview

This project focuses on building a credit risk model to assess the likelihood of loan repayment for individual applicants. The model determines whether a loan should be granted based on a dataset containing both categorical and numerical features. The target variable is categorical, divided into three classes: P1 (highly trusted, likely to repay), P2 (moderately trusted), and P3 (least trusted, higher risk of default).

Project Description

The goal of this project is to develop a machine learning model to predict credit risk and assist financial institutions in making informed lending decisions. Key steps include:





Data Preprocessing:





Performed chi-square tests on categorical features to assess their significance.



Checked for multicollinearity among numerical features, followed by ANOVA tests to evaluate their relevance.



Conducted extensive feature engineering to enhance model performance.



Modeling:





Split the dataset into training and testing sets.



Trained a Random Forest Classifier on the training data.



Evaluated the model's performance on the test data.

Repository Contents





credit_risk_modelling.ipynb: The main Jupyter Notebook containing the complete workflow, including data preprocessing, feature engineering, model training, and evaluation.

Installation

To run this project locally, ensure you have the following dependencies installed:





Python 3.x



Jupyter Notebook



Required Python libraries:





pandas



numpy



scikit-learn



scipy



matplotlib (optional, for visualizations)

You can install the required libraries using pip:

pip install pandas numpy scikit-learn scipy matplotlib

Usage





Clone the repository:

git clone https://github.com/Shyamal1508/Credit-risk-modelling.git



Navigate to the project directory:

cd Credit-risk-modelling



Open the Jupyter Notebook:

jupyter notebook credit_risk_modelling.ipynb



Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.

Data

The dataset used in this project is not publicly shared in the repository. It contains both categorical and numerical features, with the target variable categorized into P1, P2, and P3 classes. Ensure you have access to a similar dataset or modify the notebook to work with your own data.

Results

The Random Forest Classifier was trained and tested, achieving satisfactory performance in predicting credit risk. Detailed results, including accuracy and other metrics, can be found in the credit_risk_modelling.ipynb notebook.
