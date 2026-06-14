# Employee Salary Prediction Model

## Overview
This project builds a machine learning pipeline for employee salary prediction using employee-related attributes such as age, experience, education, skills, certifications, work hours, job role, and company type.

## Features
- Data preprocessing and cleaning
- Missing value handling
- Duplicate record removal
- Data validation checks
- Categorical feature encoding
- Feature scaling using StandardScaler
- Exploratory Data Analysis (EDA)
- Correlation analysis between features and salary
- Salary trend analysis based on:
  - Years of Experience
  - Education Level
  - Job Role
  - Skills Score
  - Certifications
  - Company Type

## Dataset Columns
The notebook references the following fields:
- Age
- Gender
- EducationLevel
- JobRole
- YearsOfExperience
- SkillsScore
- Certifications
- WorkHoursPerWeek
- CompanyType
- Salary (Target Variable)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Data Preprocessing Steps
1. Load employee salary dataset.
2. Check dataset shape and structure.
3. Handle missing values:
   - Numerical columns → Median
   - Categorical columns → Mode
4. Remove duplicate records.
5. Perform data validation checks.
6. Encode categorical variables using LabelEncoder.
7. Scale numerical features using StandardScaler.
8. Save the preprocessed dataset.

## Exploratory Data Analysis
The notebook performs:
- Statistical summary generation
- Missing value analysis
- Correlation matrix analysis
- Experience vs Salary analysis
- Education Level vs Salary analysis
- Job Role vs Salary analysis
- Skills Score vs Salary analysis
- Certifications vs Salary analysis
- Company Type vs Salary analysis

## Project Structure
```
salary_prediction_model.ipynb
README.md
employee_salary_dataset.csv
preprocessed_employee_salary_dataset.csv
```

## How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

2. Update the dataset path inside the notebook if required.

3. Run the notebook cells sequentially.

## Output
The notebook generates:
- Cleaned and preprocessed employee salary dataset
- Statistical insights and visual analysis
- Feature relationships with salary
- Processed data ready for machine learning model training

## Future Improvements
- Train multiple regression models
- Hyperparameter tuning
- Feature engineering
- Model evaluation and comparison
- Deployment using Flask or Streamlit

## Author
Mettu Dheeraj Reddy
