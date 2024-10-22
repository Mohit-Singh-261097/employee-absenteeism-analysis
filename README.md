
# **Employee Absenteeism Analysis**

### *Leveraging Data Science and Predictive Modeling to Improve Workforce Efficiency*

![Absenteeism](https://github.com/Mohit-Singh-261097/employee-absenteeism-analysis/blob/main/enhanced_absenteeism_by_job.png)

## **Table of Contents**
- [Introduction](#introduction)
- [Business Problem](#business-problem)
- [Data Overview](#data-overview)
- [Project Workflow](#project-workflow)
- [Installation and Setup](#installation-and-setup)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Feature Engineering](#feature-engineering)
- [Predictive Modeling](#predictive-modeling)
- [Model Performance](#model-performance)
- [Key Insights](#key-insights)
- [Future Work](#future-work)
- [Conclusion](#conclusion)

---

## **Introduction**

Employee absenteeism is a key challenge faced by organizations, often leading to reduced productivity and increased operational costs. This project aims to analyze employee absenteeism data and develop predictive models to help businesses understand the patterns and reasons behind absenteeism.

The insights gained from this project can assist in:
- Reducing absenteeism.
- Improving workforce planning.
- Supporting HR decision-making processes.

## **Business Problem**

Companies are often challenged with high levels of absenteeism which impacts:
1. **Productivity Loss:** Lower employee presence directly affects work output.
2. **Operational Costs:** Temporary workers or overtime compensation increase expenses.
3. **Morale:** Employees covering for absent colleagues may experience burnout.

### Objective
To address these issues, this project focuses on:
- **Identifying key factors** associated with absenteeism.
- **Predicting absenteeism trends** based on historical data using machine learning models.
- Providing **data-driven insights** to enable proactive decision-making.

---

## **Data Overview**

### Datasets:
1. **MFGEmployees4.csv**: The core dataset containing employee records with variables such as Employee Number, Age, Job Title, Department, Length of Service, and Absentee Hours.
2. **new_data1.csv**: An extended dataset used to supplement and enhance analysis.

### Key Variables:
- **Employee Demographics**: Age, Gender.
- **Work Information**: Job Title, Department, Store Location, Division.
- **Absenteeism Metrics**: AbsentHours, LengthService (in years).

#### Data Insights
- Over **20,000 records** detailing employee absenteeism patterns.
- Includes employees across multiple departments and geographic locations.

---

## **Project Workflow**

This project follows a structured Data Science approach:
1. **Data Preprocessing**: Handling missing values, data transformations, and encoding categorical variables.
2. **Exploratory Data Analysis (EDA)**: Identifying patterns in absenteeism by visualizing data trends.
3. **Feature Engineering**: Creating new features like absenteeism rates and tenure categories to improve model performance.
4. **Predictive Modeling**: Building machine learning models to predict absenteeism and classify employee behavior.
5. **Model Evaluation**: Using metrics like accuracy, precision, recall, and F1-score to evaluate model effectiveness.

---

## **Installation and Setup**

### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab

### Setup
To set up this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/employee-absenteeism-analysis.git
   cd employee-absenteeism-analysis
   ```

2. **Install dependencies**:
   Install the required packages using the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebooks**:
   Open Jupyter and run the analysis from the provided notebooks:
   ```bash
   jupyter notebook
   ```

---

## **Exploratory Data Analysis (EDA)**

### Key Findings:
- **High absenteeism** is observed in certain job roles like *Baker* and *Clerk*.
- **Length of Service** has a **non-linear relationship** with absenteeism. New employees and employees with longer tenure have different absenteeism trends.
- **Age**: Younger employees tend to have slightly higher absenteeism.

![Absenteeism Analysis](https://image-link-eda.png)

The EDA was conducted using statistical and visualization techniques to understand the dataset's structure, relationships, and outliers.

---

## **Feature Engineering**

Key features engineered include:
- **Absenteeism Rate**: Grouping employees based on absenteeism hours.
- **Tenure Grouping**: Categorizing employees by their years of service to uncover trends across different experience levels.
- **Binary Encoding**: Encoding categorical variables such as job title and department to improve model training.

---

## **Predictive Modeling**

Multiple models were trained to predict absenteeism, with a focus on understanding the best model for the task:
- **Random Forest Classifier**: A robust ensemble method used for classification.
- **Logistic Regression**: A baseline model to compare performance.
- **XGBoost**: A powerful gradient boosting model to enhance prediction accuracy.

#### Model Pipeline:
1. **Data Splitting**: Train-test split (80%-20%) to evaluate model performance.
2. **Model Training**: Using cross-validation and hyperparameter tuning.
3. **Evaluation**: Metrics such as accuracy, precision, recall, and F1-score were used to assess model effectiveness.

---

## **Model Performance**

| Model                   | Accuracy | F1-Score | Precision | Recall |
|--------------------------|----------|----------|-----------|--------|
| Random Forest Classifier  | 85.1%    | 0.88     | 0.88      | 0.88   |
| Logistic Regression       | 79.5%    | 0.81     | 0.82      | 0.80   |
| XGBoost Classifier        | 86.2%    | 0.89     | 0.89      | 0.88   |

### Key Observations:
- The **Random Forest** and **XGBoost** models performed well with high F1-scores.
- **Logistic Regression**, while simple, provided a reasonable baseline.

---

## **Key Insights**

- **Tenure and Job Role** are critical factors contributing to absenteeism.
- **Department-specific absenteeism** highlights the need for targeted interventions in departments like *Bakery* and *Clerks*.
- **Predictive models** can help HR departments forecast absenteeism and proactively manage staffing requirements.

---

## **Future Work**

- **Hyperparameter Tuning**: Fine-tune models for optimal performance.
- **Incorporate External Factors**: Introduce external data (e.g., weather, commute distance) to capture absenteeism influenced by external variables.
- **Employee Retention Analysis**: Extend the analysis to predict employee churn and retention.

---

## **Conclusion**

This project demonstrates how data science techniques can provide actionable insights into workforce absenteeism. By predicting absenteeism trends, organizations can take proactive steps to reduce absenteeism and optimize workforce planning. 

---

## **Contact**

For questions or collaboration, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/mohit-singh-661427181/) or [GitHub](https://github.com/Mohit-Singh-261097).
