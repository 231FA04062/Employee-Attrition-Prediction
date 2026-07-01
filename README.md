# Employee Attrition Prediction using Machine Learning

## Overview

Employee attrition is a major challenge for organizations as it affects productivity, increases recruitment costs, and impacts overall business performance. This project uses Machine Learning techniques to predict whether an employee is likely to leave the company based on various personal and professional attributes.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, model evaluation, and comparison of multiple machine learning algorithms.

---

## Project Objectives

- Analyze employee data to identify patterns related to attrition.
- Perform data preprocessing and feature engineering.
- Visualize important trends using Exploratory Data Analysis (EDA).
- Train multiple machine learning models.
- Compare model performance.
- Predict employee attrition accurately.

---

## Dataset

The dataset contains information about employees, including:

- Age
- Business Travel
- Department
- Distance From Home
- Education
- Education Field
- Environment Satisfaction
- Gender
- Job Involvement
- Job Level
- Job Role
- Job Satisfaction
- Marital Status
- Monthly Income
- Overtime
- Performance Rating
- Relationship Satisfaction
- Stock Option Level
- Total Working Years
- Work Life Balance
- Years at Company
- Years in Current Role
- Years Since Last Promotion
- Years With Current Manager

Target Variable:

**Attrition**
- Yes
- No

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Cleaning
5. Exploratory Data Analysis
6. Correlation Analysis
7. Feature Engineering
8. Train-Test Split
9. Model Training
10. Hyperparameter Tuning
11. Cross Validation
12. Model Evaluation
13. Feature Importance Analysis
14. ROC Curve Analysis
15. Model Comparison

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Cross Validation
- ROC Curve
- AUC Score

---

## Model Performance

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | **87.83%** |
| Support Vector Machine | 86.84% |
| Random Forest | 85.20% |

**Best Performing Model:** Logistic Regression

---

## Project Structure

```
Employee-Attrition-Prediction/
│
├── Employee_Attrition_Prediction.ipynb
├── employee_attrition.csv
├── README.md
├── requirements.txt
└── images/
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/your-username/Employee-Attrition-Prediction.git
```

Move into the project directory

```bash
cd Employee-Attrition-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

## Results

- Successfully analyzed employee data.
- Compared multiple machine learning models.
- Logistic Regression achieved the highest accuracy.
- Generated multiple visualizations for better business insights.
- Performed hyperparameter tuning and cross-validation to improve model reliability.

---

## Future Enhancements

- Deploy the model using Streamlit or Flask.
- Integrate real-time employee data.
- Build an interactive dashboard.
- Improve prediction using XGBoost and LightGBM.
- Implement Explainable AI using SHAP.

---

## Author

**Varshitha**

Machine Learning | Data Science | Python

---

## License

This project is developed for educational and learning purposes.