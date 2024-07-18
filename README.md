# Lending-Dataset-Analysis-A-Comprehensive-Predictive-Modeling-Approach

## Overview:

This repository contains a series of predictive modeling projects centered around the Lending Dataset from 2014. The analyses include various machine learning techniques such as Logistic Regression, Linear Regression, Ridge vs. Lasso, Decision Tree, Bagging, Boosting, Naive Bayes, Neural Networks, and Principal Component Analysis (PCA). Each project aims to explore different aspects of the dataset, optimize prediction accuracy, and provide insights into loan status and investment strategies. The repository includes detailed reports and data dictionaries to facilitate understanding and reproducibility.

## Objectives:

* To clean and preprocess the Lending Dataset for predictive modeling.
* To apply various machine learning techniques and compare their performance.
* To identify significant predictors and understand their relationships with loan status and return on investment (ROI).
* To develop investment strategies based on predictive modeling outcomes.

## Repository Structure:

* **docs/:** Directory containing the project reports and data dictionary.
  * **DataDictionaryLendingDataset.xlsx:** Data dictionary for the Lending Dataset.  
  * **Bagging_Boosting_DT.docx:** Report on Decision Tree, Bagging, and Boosting models.
  * **LendingCaseStudy.pdf:** Case study on data-driven investment strategies for peer-to-peer lending.
  * **Lending_Linear_Regression.docx:** Report on Linear Regression models.
  * **Logistic_Linear_Regression.docx:** Report on Logistic Regression models.
  * **Naive_Bayes.docx:** Report on Naive Bayes model.
  * **NeuralNetwork.docx:** Report on Neural Network models.
  * **Ridge_vs_Lasso.docx:** Report comparing Ridge and Lasso regression models.

## Projects and Key Components:

### 1. Bagging, Boosting, and Decision Trees:

* **Objective:** To compare the performance of Decision Tree, Bagging (Bootstrap Forest), and Boosting models.
* **Key Findings:**
  * Decision Tree Model with 30 splits gave the best output for validation data.
  * Bootstrap Forest (Bagging) had a high AUC for validation data (69.21%).
  * Boosted Trees Model had a slightly lower AUC compared to Bagging but showed no signs of overfitting.

### 2. Linear Regression Models:

* **Objective:** To build multiple linear regression models to predict the rate of return (ROI) using pessimistic and optimistic methods.
* **Key Findings:**
  * Detailed step-by-step data cleaning process.
  * Pessimistic and optimistic models were developed with significant predictors identified.

### 3. Logistic Regression Models:

* **Objective:** To calculate the logistic regression of loan status and evaluate model performance.
* **Key Findings:**
  * Iterative process to refine the model by removing variables with high p-values.
  * Final model showed significant predictors with low p-values and acceptable VIF values.
  * Confusion matrix, gains, and lift charts were used to evaluate model performance.

### 4. Naive Bayes Model:

* **Objective:** To build and evaluate a Naive Bayes model for loan status prediction.
* **Key Findings:**
  * Naive Bayes model had the lowest AUC among the compared models.
  * Model comparison highlighted the strengths and weaknesses of Naive Bayes relative to other models.

### 5. Neural Networks:

* **Objective:** To explore different neural network architectures and their performance.
* **Key Findings:**
  * Various architectures were tested, including models with different layers and nodes.
  * The model with 2 layers and 9 nodes each using TanH Linear and Gaussian activation functions performed the best.

### 6. Ridge vs. Lasso Regression:

* **Objective:** To compare Ridge and Lasso regression models using the Lending Dataset.
* **Key Findings:**
  * Lasso model showed slightly better performance metrics (AUC, R2, RMSE) compared to Ridge.
  * Both models were compared to the baseline logistic regression model.

### 7. Principal Component Analysis (PCA):

* **Objective:** To apply PCA on the dataset to reduce dimensionality and identify key components.
* **Key Findings:**
  * First two principal components retained about 48.92% variability.
  * Correlation analysis showed that the principal components were orthogonal and captured different data aspects.

### 8. Investment Strategies:

* **Objective:** To use historical loan data to develop data-driven investment strategies for peer-to-peer lending.
* **Key Findings:**
  * Detailed case study exploring various investment metrics and strategies.
  * Recommendations for selecting loans and minimizing risk based on data analysis.

## Conclusion:
The Lending Dataset Analysis repository provides a comprehensive exploration of various predictive modeling techniques applied to peer-to-peer lending data. Each project highlights different aspects of the dataset, offering valuable insights into loan status prediction, ROI estimation, and investment strategies. Through detailed reports and comparisons, the repository serves as a valuable resource for understanding and applying machine learning techniques in finance.

## References:

* Pankaj Prakash, OPIM5604 Predictive Modeling, University of Connecticut.
* Lending Dataset (2014).
