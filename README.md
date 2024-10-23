# Employee Absenteeism Analysis

## Project Overview
This project aims to analyze employee absenteeism data to predict future trends and identify patterns across various departments, job titles, and demographic groups. By utilizing machine learning models, we can forecast absenteeism, helping organizations to reduce costs and improve workforce management.

### Key Insights:
- **Absentee Hours** by department and job title show distinct trends across various sectors of the company.
- **Feature Engineering** improved the accuracy of predictions and allowed us to uncover deeper insights into the data.
- **Machine Learning Models** used include Random Forest, XGBoost, and others, all fine-tuned through cross-validation and hyperparameter tuning.
  
## Project Structure
- `Data/`: Contains raw and processed data files.
- `Notebooks/`: Jupyter notebooks with exploratory data analysis (EDA), feature engineering, and model building.
- `Models/`: Saved machine learning models and results.
- `Visualizations/`: Contains plots and Tableau dashboard exports.
  
## Machine Learning Models
The models used in this project include:
1. **RandomForestClassifier**: Achieved high accuracy in predicting absenteeism with fine-tuned parameters.
2. **XGBoost**: Provided robust performance, handling imbalanced classes effectively.
3. **Logistic Regression**: Baseline model for comparison.
  
## Tableau Dashboard
We have also created an interactive dashboard to visualize absenteeism patterns across departments, job titles, and other factors. 

You can explore the interactive Tableau dashboard here: [Tableau Dashboard](<Insert_Link_to_Tableau>)

## Results
- The Random Forest model showed the highest accuracy, reaching nearly 99% in classification tasks.
- Key predictors of absenteeism include job title, department, age, and absentee hours.
- The Tableau dashboard presents these insights in a visual and interactive manner for easy interpretation.

## Installation
To run this project locally, clone the repository and install the required dependencies:
```bash
git clone https://github.com/your-repository-link.git
cd your-repository-folder
pip install -r requirements.txt
