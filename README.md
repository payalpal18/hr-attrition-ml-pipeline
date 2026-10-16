# HR Attrition ML Pipeline

## Project Overview

This project demonstrates an end-to-end Machine Learning pipeline for predicting employee attrition using Python. It focuses on HR Analytics and explores how machine learning techniques can be used to analyse employee data and classify whether an employee stays or resigns.

The project compares Logistic Regression models with and without SMOTENC to demonstrate the impact of handling class imbalance on model performance.

## Objectives

- Build a machine learning classification pipeline for HR attrition analysis.
- Generate and clean synthetic employee data.
- Perform exploratory data analysis (EDA).
- Handle missing values and duplicate records.
- Apply data preprocessing and feature encoding.
- Address class imbalance using SMOTENC.
- Train and compare Logistic Regression models.
- Evaluate model performance using classification metrics.

## Dataset Description

The project uses a synthetic dataset containing 1,000 fictional employee records. Additional duplicate rows and missing values are introduced for data-cleaning practice.

The dataset includes the following features:

| Feature | Description |
|---|---|
| EmployeeID | Unique employee identifier |
| Department | Employee's department |
| WorkMode | Office, Hybrid, or Remote |
| ExperienceYears | Years of professional experience |
| MonthlySalary | Monthly salary in INR |
| SatisfactionScore | Employee satisfaction score |
| OvertimeHours | Overtime hours |
| Absences | Number of absence days |
| Resigned | Target variable: 0 = Stayed, 1 = Resigned |

**Note:** The dataset is synthetic and does not contain real employee records.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Imbalanced-learn
- Joblib
- Jupyter Notebook / Google Colab

## Project Workflow

1. Data generation and loading
2. Data inspection and quality checks
3. Data cleaning and duplicate removal
4. Exploratory Data Analysis
5. Feature selection and train-test splitting
6. Missing-value imputation
7. Numerical feature scaling
8. Categorical feature encoding
9. Class imbalance handling using SMOTENC
10. Logistic Regression model training
11. Model evaluation and comparison
12. Confusion matrix analysis
13. Prediction demonstration
14. Exporting the model and results

## Machine Learning Approach

Logistic Regression is used as the classification algorithm.

Two model configurations are compared:

- **Baseline Model:** Logistic Regression trained without oversampling.
- **SMOTENC Model:** Logistic Regression trained using SMOTENC to address class imbalance in the training data.

Both models are evaluated on the same held-out test set to support a fair comparison.

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

These metrics help assess how well the models classify employee attrition and highlight the trade-offs between identifying employees who resign and incorrectly flagging employees who stay.

## Expected Project Outputs

When the notebook is executed, it generates or saves outputs such as:

- Raw synthetic employee dataset
- Cleaned employee dataset
- Model comparison results
- Classification report visualisation
- Saved preprocessing components and trained model

## How to Run the Project

1. Clone or download this repository.
2. Open the Jupyter Notebook in Google Colab or Jupyter Notebook.
3. Install the required Python libraries if they are not already installed.
4. Run the notebook cells sequentially from beginning to end.
5. Review the data visualisations, model evaluation metrics, and generated output files.

## Key Learning Outcomes

- Understanding the application of Machine Learning in HR Analytics.
- Learning data cleaning and preprocessing techniques.
- Understanding supervised learning and binary classification.
- Applying oversampling techniques to imbalanced datasets.
- Comparing classification models using evaluation metrics.
- Understanding the importance of train-test separation and avoiding data leakage.

## Limitations and Responsible Use

This is an educational project based on synthetic data. Its results do not establish how well the model would perform in a real organisation.

The model is intended for learning and experimentation, not for making employment decisions about real people. Any real-world application would require representative data, fairness and privacy assessments, appropriate validation, and human oversight.

## Author

**Payal Pal**

MBA Student | HR Analytics | Machine Learning | Data Analytics

---

*This project was developed for educational purposes to explore the use of machine learning techniques in Human Resource Analytics.*
