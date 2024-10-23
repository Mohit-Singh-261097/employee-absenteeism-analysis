# **Employee Absenteeism Analysis**

### *Leveraging Data Science and Predictive Modeling to Improve Workforce Efficiency*

## **Project Overview**

This project aims to analyze employee absenteeism using data science techniques. The goal is to uncover patterns in absenteeism, build predictive models, and provide insights to help businesses manage absenteeism effectively.

## **Key Steps in Analysis**

1. Data Loading and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Predictive Modeling
5. Model Evaluation and Interpretation
6. Conclusion and Recommendations

---

## **Table of Contents**

- [Introduction](#introduction)
- [Business Problem](#business-problem)
- [Data Overview](#data-overview)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Predictive Modeling](#predictive-modeling)
- [Model Evaluation](#model-evaluation)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [Future Work](#future-work)

---

## **Introduction**

Employee absenteeism is a significant challenge that can lead to reduced productivity, increased operational costs, and employee burnout. This project focuses on analyzing absenteeism data and developing predictive models to understand and address absenteeism trends.

---

## **Business Problem**

Organizations face productivity loss, increased costs, and employee morale issues due to absenteeism. This project aims to identify key factors behind absenteeism and predict absenteeism trends using machine learning models.

---

## **Data Overview**

### Dataset:

The main dataset consists of employee records, including attributes such as Employee Number, Job Title, Department, Length of Service, and Absentee Hours.

### Key Variables:
- **Demographics**: Age, Gender
- **Job Information**: Job Title, Department, Store Location
- **Absenteeism Metrics**: AbsentHours, LengthService

---

## **Exploratory Data Analysis (EDA)**

In this step, we used various visualizations such as histograms, boxplots, heatmaps, and scatterplots to explore the dataset. Key findings include:
- Higher absenteeism in specific job roles and departments.
- Age and Length of Service show different absenteeism trends.

---

## **Feature Engineering**

Key engineered features include:
- **Absenteeism Rate**: Grouping employees based on absenteeism hours.
- **JobTitle_BusinessUnit**: A combined feature to analyze absenteeism across job roles and business units.
  
Various scaling techniques were applied, including **MinMaxScaler**, **StandardScaler**, and **RobustScaler**, to normalize the data.

---

## **Predictive Modeling**

### Regression Task: Predicting Absentee Hours
- **Model Used**: RandomForestRegressor
- **Performance Metrics**:
  - Mean Squared Error (MSE): 0.096
  - Root Mean Squared Error (RMSE): 0.310
  - R-squared: 0.765
  - Mean Absolute Error: 0.237
  - Mean Absolute Percentage Error: 3.47%

### Classification Task: High Absenteeism Prediction
- **Model Used**: RandomForestClassifier
- **Performance Metrics**:
  - F1-Score: 0.88
  - Accuracy: 85.1%
  - Confusion Matrix: True positive and false positive predictions visualized.

---

## **Model Evaluation**

### Model Performance Comparison:

| Model                   | Accuracy | F1-Score | Precision | Recall |
|--------------------------|----------|----------|-----------|--------|
| Random Forest Classifier  | 85.1%    | 0.88     | 0.88      | 0.88   |
| Logistic Regression       | 79.5%    | 0.81     | 0.82      | 0.80   |
| XGBoost Classifier        | 86.2%    | 0.89     | 0.89      | 0.88   |

---

## **Key Insights**

- **Job Titles and Departments**: Some job titles and departments show a higher absenteeism rate, indicating the need for focused interventions.
- **Predictive Models**: Machine learning models like Random Forest and XGBoost are effective in predicting absenteeism, helping HR departments manage staffing better.

---

## **Conclusion**

This project demonstrates how data science can be applied to provide actionable insights into employee absenteeism. By predicting absenteeism trends, organizations can take proactive steps to reduce absenteeism and optimize workforce planning.

---

## **Future Work**

- **Hyperparameter Tuning**: Further optimize model performance.
- **Incorporate External Factors**: Analyze absenteeism based on external data such as commute times or weather conditions.
- **Employee Retention Analysis**: Extend the project to predict employee churn.

---

## **Contact**

For any questions or collaboration opportunities, feel free to connect via:
- [LinkedIn](https://www.linkedin.com/in/mohit-singh-661427181/)
- [GitHub](https://github.com/Mohit-Singh-261097)

