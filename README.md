# Dissertation Project – Numerical Machine Learning Analysis

## 1. Project Overview

This project focuses on the design, implementation, and evaluation of **numerical machine learning models** applied to structured tabular data. The aim is to analyse how different machine learning techniques perform on real-world numerical datasets using a clear, reproducible, and academically sound workflow.

The project follows a standard machine learning pipeline including dataset selection, data cleaning, exploratory data analysis (EDA), feature preparation, model training, and evaluation. All work is implemented in **Python using Jupyter Notebooks** and version-controlled using **GitHub**.

---

## 2. Repository Structure

The repository is organised as follows:

- `Notebook/` – Jupyter notebooks implementing each stage of the project  
- `data/` – Numerical datasets (excluded from version control where appropriate)  
- `README.md` – Project documentation  

The notebooks are numbered to reflect the logical execution order of the project.

---

## 3. Project Plan and Workflow

The project follows the structured workflow below:

1. Project setup and environment configuration  
2. Dataset selection and justification  
3. Data cleaning and preprocessing  
4. Exploratory data analysis (EDA)  
5. Baseline model development  
6. Model evaluation and comparison  
7. Discussion of results and conclusions  

This workflow ensures clarity, reproducibility, and alignment with academic best practice.

---

## 4. Dataset Shortlist (Numerical Datasets)

In line with supervision guidance, a shortlist of **five numerical datasets** was considered:

1. **Wine Quality Dataset (UCI Machine Learning Repository)**  
   - Physicochemical properties of wine  
   - Regression task predicting wine quality score  

2. **Boston Housing Dataset**  
   - Socioeconomic and housing-related features  
   - Regression task predicting house prices  

3. **Diabetes Dataset (Scikit-learn)**  
   - Medical diagnostic measurements  
   - Regression task predicting disease progression  

4. **Auto MPG Dataset**  
   - Vehicle technical characteristics  
   - Regression task predicting fuel efficiency  

5. **Bank Marketing Dataset**  
   - Customer demographic and financial attributes  
   - Classification task predicting term deposit subscription  

---

## 5. Selected Dataset

The **Wine Quality dataset** was selected for this project due to its numerical nature, moderate size, and widespread academic use.

- Source: UCI Machine Learning Repository  
- Data type: Numerical (tabular)  
- Task: Regression (predicting wine quality score)  

---

## 6. Notebook 01 – Project Setup (Completed)

This notebook establishes the project environment and scope.

Key tasks:
- Importing required Python libraries  
- Verifying the execution environment (Google Colab compatible)  
- Defining project objectives and structure  

Implemented in:  
`Notebook/01_project_setup.ipynb`

---

## 7. Notebook 02 – Dataset Loading and Inspection (Completed)

This notebook loads the selected dataset and performs initial inspection.

Key tasks:
- Loading the Wine Quality dataset  
- Inspecting dataset shape and structure  
- Verifying feature names and data types  

Implemented in:  
`Notebook/02_dataset_loading.ipynb`

---

## 8. Notebook 03 – Data Cleaning and Preprocessing (Completed)

This notebook prepares the dataset for modelling.

Key tasks:
- Handling missing values  
- Verifying numerical features  
- Preparing clean feature and target variables  

Implemented in:  
`Notebook/03_data_cleaning.ipynb`

---

## 9. Notebook 04 – Exploratory Data Analysis (EDA) (Completed)

This notebook explores relationships within the dataset to inform modelling decisions.

Key tasks:
- Descriptive statistics  
- Correlation analysis  
- Feature distribution visualisation  

Insights from EDA guide baseline model selection.

Implemented in:  
`Notebook/04_exploratory_data_analysis.ipynb`

---

## 10. Notebook 05 – Baseline Model Development (Completed)

This notebook implements baseline numerical machine learning models to establish performance benchmarks.

Key tasks:
- Splitting data into training and testing sets  
- Training baseline regression models  
- Evaluating models using RMSE and R² metrics  
- Establishing baseline performance for future comparison  

These results provide a reference point for more advanced models and tuning in later stages.

Implemented in:  
`Notebook/05_baseline_models.ipynb`

---

## 11. Next Steps

The next stages of the project will focus on improving model performance and deepening analysis:

- Advanced regression models (e.g. Random Forest, Gradient Boosting)
- Hyperparameter tuning and cross-validation
- Model comparison and selection
- Interpretation of results and discussion
- Final conclusions and recommendations
---

## 12. Tools and Libraries

Key Python libraries used in this project include:

- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 13. Project Status

- Project scope defined and approved as numerical ML  
- Five numerical datasets shortlisted  
- Wine Quality dataset selected  
- Data cleaning and preprocessing completed  
- Exploratory data analysis completed  
- Baseline regression models implemented  
- Project on track for advanced modelling and evaluation
