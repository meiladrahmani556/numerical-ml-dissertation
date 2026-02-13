# Dissertation Project – Numerical Machine Learning Analysis

## 1. Project Overview

This project focuses on the application of machine learning techniques to numerical datasets. The aim is to analyse real-world numerical data and compare the performance of multiple supervised machine learning models on a prediction or classification task.

The project follows a structured machine learning workflow including dataset selection, exploratory data analysis (EDA), data preprocessing, model development, evaluation, and comparison.

All work is implemented in Python using Jupyter Notebooks and tracked through GitHub version control.

## 2. Project Scope and Requirements

This project has been designed to align with the agreed supervision requirements:

- The dataset used is numerical in nature
- The project applies supervised machine learning techniques
- Multiple machine learning models are implemented and compared
- A formal project plan is defined and followed
- A shortlist of numerical datasets is proposed for approval

The project does not involve image or text-based data and focuses exclusively on structured numerical datasets.

## 3. Repository Structure

The repository is organised as follows:

- notebooks/ – Jupyter notebooks implementing each stage of the project  
- data/ – Dataset directory (excluded via .gitignore)  
- README.md – Project documentation  

The notebooks are numbered to reflect the logical execution order of the project.

## 4. How to Run This Repository

1. Clone the repository from GitHub.
2. Install the required Python packages.
3. Open the notebooks using Google Colab or Jupyter Notebook.
4. Run the notebooks in numerical order inside the notebooks/ directory.

All notebooks are designed to be executable in Google Colab.

## 5. Project Plan

The project is structured into the following stages:

1. Project setup and dataset selection  
2. Exploratory Data Analysis (EDA)  
3. Data cleaning and preprocessing  
4. Baseline machine learning model  
5. Improved models and hyperparameter tuning  
6. Model comparison and evaluation  
7. Discussion of results and limitations  

This plan ensures steady progress towards the interim report and final dissertation submission.

## 6. Proposed Numerical Dataset Shortlist

The following numerical datasets are proposed for discussion and approval:

1. California Housing Prices – Regression  
2. UCI Wine Quality Dataset – Regression / Classification  
3. UCI Heart Disease Dataset – Binary Classification  
4. Credit Card Fraud Dataset (Kaggle) – Binary Classification  
5. House Prices Dataset (Kaggle) – Regression  

Final dataset selection will be confirmed following supervisor approval.

## 7. Exploratory Data Analysis (EDA)

Exploratory Data Analysis is conducted to understand the dataset structure and guide modelling decisions. This includes:

- Dataset dimensions and feature overview  
- Summary statistics  
- Missing value analysis  
- Feature distributions  
- Correlation analysis  

EDA is implemented in:

notebooks/02_exploratory_data_analysis.ipynb

## 8. Data Cleaning and Preprocessing

Data preprocessing includes:

- Handling missing values  
- Feature scaling and normalisation  
- Encoding categorical variables (if present)  
- Train, validation, and test splitting  

This ensures fair training and unbiased model evaluation.

Implemented in:

notebooks/03_data_preprocessing.ipynb

## 9. Machine Learning Model Development

Multiple supervised machine learning models are developed and compared, including:

- Linear / Logistic Regression  
- Decision Trees  
- Random Forests  
- Support Vector Machines (SVM)  

Models are trained using consistent evaluation protocols to ensure fair comparison.

## 10. Model Evaluation Strategy

Model performance is evaluated using appropriate metrics such as:

- Accuracy (classification)
- Precision, Recall, and F1-score
- RMSE and MAE (regression)
- Confusion matrices where applicable

Cross-validation and hyperparameter tuning are applied to improve generalisation performance.

## 11. Python Packages Used

Key Python libraries used include:

- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook

## 12. Version Control and Engagement

All work is tracked using GitHub with regular commits to demonstrate:

- Continuous engagement  
- Progressive project development  
- Clear documentation and structure

## 13. Conclusions

This project applies supervised machine learning techniques to numerical data using a structured and well-defined pipeline. Model comparison provides insight into the strengths and limitations of different algorithms on real-world numerical datasets.

## 14. Future Work

Future work may include:

- Advanced ensemble methods  
- Feature selection techniques  
- Model explainability methods  
- Deployment of results using a simple interface

## 15. Known Issues / Risks

There are no unresolved technical issues at the current stage. Dataset selection is pending final supervisor approval.
