## HR Analytics - Employee Attrition Prediction

![Screenshot 2025-04-08 210156](https://github.com/user-attachments/assets/ba87b312-c829-42f4-9d96-480f777780df)

## Project Overview
This project uses data analytics and machine learning to understand the key factors driving employee attrition and build predictive models to identify at-risk employees. The insights generated help HR departments develop targeted retention strategies to reduce unwanted turnover.

## Objective
Analyze HR data to identify patterns and factors contributing to employee attrition
Build classification models to predict which employees are at risk of leaving
Visualize key attrition trends and insights through interactive dashboards
Develop data-driven recommendations for preventing employee turnover
Dataset

## The dataset includes HR information for 1,480 employees with 38 attributes including:

-Demographics (age, gender, marital status)
-Work-related factors (job role, department, years at company)
-Performance metrics (job satisfaction, performance rating)
-Compensation details (monthly income, stock options)
-Work-life factors (work life balance, overtime, distance from home)

## Tools & Technologies
### Python for data analysis and modeling:
### Pandas for data manipulation
### Seaborn/Matplotlib for exploratory data visualization
### Scikit-learn for machine learning models
### Power BI for interactive dashboard creation

## Methodology
1. Exploratory Data Analysis (EDA)
Data cleaning and preparation
Statistical analysis of key variables
Visual exploration of attrition factors by department, age, education, etc.
Correlation analysis between variables
2. Feature Engineering
Label encoding of categorical variables
Feature selection based on correlation and business relevance
Handling missing values (primarily in YearsWithCurrManager)
3. Model Development
Training classification models:
Logistic Regression (Accuracy: 84.8%)
Random Forest (Accuracy: 85.8%)
Model evaluation using confusion matrices and classification reports
Feature importance analysis
4. Visualization & Dashboard Creation
Interactive Power BI dashboard with key metrics:
Department-wise attrition rates
Attrition by age groups and job satisfaction
Years at company vs. attrition trends
Education field breakdown
## Key Findings
Overall attrition rate is 16.1% (238 out of 1,480 employees)
Age factor: Employees aged 26-35 show highest attrition (116 employees)
Education impact: Life Sciences (37%) and Medical fields (26%) have higher attrition
Years at company: Highest attrition occurs in early years (0-2) and at 10-year mark
Job satisfaction: Significant correlation with retention across roles
Top attrition predictors: Monthly income, overtime, age, distance from home, total working years

##Model Performance
Logistic Regression
Accuracy: 84.8%
Class 1 (Attrition) Precision: 80%
Class 1 (Attrition) Recall: 8%

## Random Forest
Accuracy: 85.8%
Class 1 (Attrition) Precision: 75%
Class 1 (Attrition) Recall: 19%

## Recommendations
The project concludes with actionable recommendations in several key areas:

Compensation and benefits adjustments
Work-life balance improvements including overtime management
Career development opportunities and learning programs
Age and department-specific retention strategies
Engagement and culture initiatives

### Project Structure
HR_Analytics/
│
├── data/
│   └── HR_Analytics.csv          # Raw dataset
│
├── notebooks/
│   ├── HR_EDA.ipynb              # Exploratory data analysis
│
├── visualizations/
│   └── HR_Analytics_Dashboard.pbix # Power BI dashboard file
│
├── reports/
│   ├── Model_Accuracy_Report.pdf   # Model performance details
│   └── Attrition_Prevention.pdf    # Recommended strategies
│
└── README.md                      # Project documentation
Future Enhancements
Implement more advanced models (XGBoost, Neural Networks)
Conduct SHAP value analysis for deeper model interpretability
Develop a real-time attrition risk monitoring system
Integrate survey data for sentiment analysis
Perform cohort analysis to track attrition trends over time



