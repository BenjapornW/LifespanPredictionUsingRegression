# Life Expectancy Prediction Using Regression Models

## Overview
This project predicts life expectancy based on health and socioeconomic factors using machine learning models. It compares the performance of Polynomial Ridge Regression and Linear Regression, with Polynomial Ridge Regression demonstrating superior accuracy and robustness.

## Dataset
- **Source:** Global Health and Life Expectancy Dataset (WHO)
- **Size:** 2,071 entries, 24 columns
- **Features:** 12 categorical, 12 numerical

## Objectives
- Predict life expectancy (years) as a continuous value.
- Identify key factors influencing life expectancy to inform health policies.

## Methodology
1. **Data Retrieval & Cleaning**
   - Validated data quality (no nulls, standardized formats).
   - Addressed outliers and multicollinearity.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed distributions, relationships, and feature importance.

3. **Data Preprocessing**
   - StandardScaler for feature scaling.
   - Data split: 80% training, 20% validation.

4. **Modeling**
   - **Baseline Model:** Linear Regression
     - R² = 0.762, MSE = 19.69
   - **Advanced Models:**
     - Polynomial Regression
       - R² = 0.849, MSE = 12.45
     - Polynomial Ridge Regression
       - R² = 0.851, MSE = 12.28

## Results
Polynomial Ridge Regression achieved the best performance, balancing predictive power with reduced overfitting through regularization.

## Key Insights
- Factors like education, GDP, and immunization positively impact life expectancy.
- High adult mortality and HIV prevalence significantly lower life expectancy.

## Tools & Technologies
- Python (Scikit-learn, Pandas, NumPy)
- Jupyter Notebook

## Future Improvements
- Address residual patterns for further accuracy.
- Explore additional nonlinear models for complex relationships.

## References
Refer to the report for detailed citations.

---
