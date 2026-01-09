# Employee Attrition Analysis 

## Project Overview
This project identifies the specific factors that influence employee attrition and develops a predictive model to estimate turnover rates. By understanding these drivers, organizations can implement data-driven strategies to minimize the negative impacts of employee resignations.

## Objectives
* Observe qualities that correlate with employee resignation.
* Use machine learning to predict attrition rates based on employee data.
* Provide actionable recommendations to improve employee retention.

## Data Preprocessing
To ensure model accuracy, the raw data underwent the following preparation:
* Missing values were replaced with the median for that feature.
* Categorical variables were transformed using One-Hot Encoding.
* Removed unnecessary or cluttering columns to improve model focus.
* Conducted a feature correlation study to identify significant relationships.

## Methodology
1. Standardized the dataset and handled missing entries.
2. Prepared categorical data for machine learning.
3. Built and compared multiple regression and classification algorithms.
4. Created distribution plots and heatmaps to interpret results.

## Model Selection and Performance
We compared a Lasso Regression model against a Random Forest Classifier:

| Model | Metric | Performance | Score Rating |
| :--- | :--- | :--- | :--- |
| Lasso Regression | Mean MAE | 0.127 (0.009) | 87.33 |
| Random Forest | Accuracy | 0.9109 | 70.16 |

Selected Model: The Lasso Regression model was chosen for final predictions due to its significantly higher score rating.

## Key Findings
The model identified several critical variables that drive attrition:
* Time Since Last Promotion: A primary factor in employee turnover.
* Tenure: The total time an employee has been with the company.
* Employee Age: Attrition patterns vary significantly across different age groups.

## Recommendations
* Enhance benefit packages to increase long-term retention.
* Improve the understanding of employee lifestyles and milestones.
* Focus on career progression to address gaps in the promotion cycle.

## Contributors
* Alena
* Keira
* Logan
* Edward
