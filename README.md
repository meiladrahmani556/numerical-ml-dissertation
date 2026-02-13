# Dissertation Project – Numerical Data Analysis & Machine Learning

## 1. Project Overview

This project focuses on the analysis of **numerical datasets** using machine learning techniques. The aim is to evaluate and compare supervised learning models on structured numerical data.

The project follows a complete data science pipeline, including project planning, dataset selection, exploratory data analysis (EDA), data preprocessing, model development, evaluation, and reporting.

All work is implemented in Python using Jupyter Notebooks and tracked using GitHub.

## 2. Project Aim

The aim of this project is to apply machine learning techniques to numerical datasets and evaluate model performance using appropriate statistical and predictive metrics.

## 3. Project Objectives

- Prepare a formal project plan  
- Propose a shortlist of five numerical datasets for discussion and approval  
- Perform exploratory data analysis (EDA)  
- Clean and preprocess numerical data  
- Develop baseline machine learning models  
- Improve model performance through tuning  
- Evaluate and compare models  
- Document findings and conclusions

## 4. Repository Structure

The repository is organised as follows:

- notebooks/ – Jupyter notebooks for each project stage  
- data/ – Dataset directory (excluded via .gitignore)  
- images/ – Figures and plots used in documentation  
- README.md – Project documentation  

The notebooks are numbered to reflect the logical workflow of the project.

## 5. How to Run This Repository

1. Clone the repository from GitHub  
2. Install the required Python packages  
3. Place the selected dataset inside the data/ directory  
4. Run the notebooks in numerical order  
5. All notebooks are compatible with Google Colab  

## 6. Dataset Shortlist (Numerical)

The following numerical datasets are proposed for discussion and approval:

1. House Prices Dataset – Regression  
2. Wine Quality Dataset – Classification / Regression  
3. Heart Disease Dataset – Classification  
4. Student Performance Dataset – Regression / Classification  
5. Energy Efficiency Dataset – Regression  

The final dataset will be selected following supervisor approval.

## 7. Exploratory Data Analysis (EDA)

Exploratory Data Analysis is conducted to understand the structure and characteristics of the dataset.

This includes:
- Summary statistics  
- Feature distributions  
- Correlation analysis  
- Missing value inspection  

Implemented in:
notebooks/02_eda.ipynb

## 8. Data Cleaning and Preprocessing

This stage includes:
- Handling missing values  
- Feature scaling and normalisation  
- Train-test splitting  

This ensures the dataset is suitable for machine learning models.

Implemented in:
notebooks/03_preprocessing.ipynb

## 9. Machine Learning Model Development

Multiple supervised learning models are developed and compared, including:

- Linear / Logistic Regression  
- Decision Trees  
- Random Forest  
- k-Nearest Neighbours (k-NN)  

A baseline model is implemented first, followed by improved models using tuning techniques.

Implemented in:
notebooks/04_baseline_model.ipynb  
notebooks/05_model_improvements.ipynb

## 10. Model Evaluation

Models are evaluated using appropriate metrics, including:
- Accuracy  
- Precision, Recall, F1-score  
- RMSE / MAE (for regression tasks)  
- Confusion Matrix  

Evaluation results are used to compare model performance.

## 11. Tools and Technologies

- Python  
- Jupyter Notebook / Google Colab  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib / Seaborn  
- GitHub  

## 12. Version Control

All work is version-controlled using GitHub with regular commits.

The data/ directory is excluded from version control.

## 13. Conclusions

This project demonstrates a structured approach to numerical data analysis and machine learning following an end-to-end data science workflow.

## 14. Future Work

- Advanced feature engineering  
- Ensemble learning methods  
- Cross-validation strategies  
- Model deployment

## 15. Known Issues

No critical unresolved issues at the current stage of the project.

