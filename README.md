
# HR Data Analyst Project

## 1. Problem Statement
Analyze employee data to identify factors driving attrition, salary trends, and workforce distribution to help HR make better decisions.

## 2. Dataset Overview
- **Source**: Self-generated using Python + NumPy
- **Rows**: 500 employees
- **Columns**: employee_id, age, gender, location, department, salary, hire_date, performance, attrition
- **Intentional Issues**: Missing values, future dates, duplicates, outliers

## 3. Data Cleaning & Quality Audit
- Removed duplicates based on employee_id
- Handled missing values: Median for age, Department median for salary, Mode for location
- Fixed data type issues and removed future hire_dates

## 4. Exploratory Data Analysis
- Summary statistics: Mean, Median, Std, IQR
- Feature Engineering: hire_year, salary_per_year
- Group Aggregation by department

## 5. Visualizations
1. Histogram: Age Distribution
2. Bar Chart: Employees per Department  
3. Boxplot: Salary Outliers
4. Heatmap: Correlation between numeric features

## 6. Key Business Takeaways
- 35% attrition in first 2 years → Improve onboarding
- Salary outliers exist → Review salary bands
- IT/Sales have highest headcount → Monitor burnout

## 7. Tech Stack
`Python, Pandas, Numpy, Matplotlib, Seaborn`
