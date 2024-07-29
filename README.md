# Algorithmic Fairness Project

This repository contains a series of Jupyter notebooks designed to explore and address issues of fairness in machine learning algorithms specifically pertaining to law school bar passage rates. Each notebook focuses on different aspects of data analysis, model evaluation, and fairness improvement techniques. Below is a detailed description of each notebook and its purpose.

## Notebooks Overview

### 1. EDA Notebook

**Purpose:**  
The Exploratory Data Analysis (EDA) notebook is dedicated to the initial examination and preprocessing of the dataset. Key tasks include:
- **Exploratory Data Analysis:** Understanding the structure, distribution, and relationships within the data.
- **Data Cleaning:** Handling missing values, outliers, and inconsistencies.
- **One-Hot Encoding:** Converting categorical variables into a format suitable for machine learning algorithms.
- **Saving Processed Data:** Storing the cleaned and encoded data for further analysis.

### 2. Baseline Evaluation Notebook

**Purpose:**  
The Baseline Evaluation notebook aims to establish a benchmark for the dataset by evaluating its performance across various groups defined by protected features. Key metrics include:
- **Accuracy:** Overall correctness of the model predictions.
- **False Negative Rate (FNR):** Proportion of actual positives incorrectly classified as negatives.
- **Group-wise Analysis:** Evaluating the metrics separately for each group within the protected features to identify disparities.

### 3. FairPCA Notebook

**Purpose:**  
The FairPCA notebook focuses on implementing and comparing dimensionality reduction techniques to promote fairness in the data. It includes:
- **FairPCA Algorithm:** Computing the projection of the data using the FairPCA algorithm.
- **Model Training and Evaluation:** Training models on the transformed data and evaluating their performance.
- **Comparison with Standard PCA:** Comparing the performance of FairPCA with standard PCA.
- **Correlation Matrices:** Computing and analyzing correlation matrices to assess the fairness of the transformed data.

### 4. SHAP and Counterfactuals Notebook

**Purpose:**  
The SHAP and Counterfactuals notebook is designed to interpret model predictions and explore the impact of feature changes. It includes:
- **SHAP Analysis:** Computing feature importance using the SHAP (SHapley Additive exPlanations) library.
- **Counterfactuals Generation:** Identifying minimal changes required to alter the model's predictions.
- **Evaluation on FairPCA Data:** Assessing the counterfactuals on the FairPCA-transformed data to ensure fairness improvements.


### 5. Fairness_in_law_school Notebook
This is simply a merged notebook of all the notebooks above since I could only submit one for my exam
