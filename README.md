# **🎓 Jamboree Education - Graduate Admissions Analysis**

🚀 Dive into the world of graduate admissions with our comprehensive case study on predicting the probability of admission into Ivy League colleges! Using the "Jamboree-Education---Linear-Regression" dataset, we explore key factors influencing graduate admissions and provide data-driven insights to optimize student success.

## 📄 Project Overview

This project focuses on analyzing the factors influencing graduate admissions to Ivy League colleges from an Indian perspective. The aim is to provide Jamboree with insights into key variables that impact admission chances and to predict these chances using linear regression.

## 📊 Dataset Information

**Dataset Link**: Jamboree_Admission.csv

**Columns**:
  - **Serial No.**: Unique row ID
  - **GRE Scores**: Out of 340
  - **TOEFL Scores**: Out of 120
  - **University Rating**: Out of 5
  - **SOP & LOR Strength**: Out of 5
  - **Undergraduate GPA**: Out of 10
  - **Research Experience**: 0 or 1
  - **Chance of Admit**: Ranges from 0 to 1

## 🛠️ Concepts and Techniques

1. **Exploratory Data Analysis (EDA)**: 
   - Analyzed the dataset structure and characteristics.
   - Conducted both non-graphical and graphical analysis to infer relationships between variables.
   - Explored the distribution of variables among graduate applicants.

2. **Linear Regression**:
   - Established relationships between the variables and graduate admission chances.
   - Tested the assumptions of linear regression including:
     - Multicollinearity (checked by VIF score)
     - Mean of residuals
     - Linearity of variables (no pattern in residual plot)
     - Homoscedasticity
     - Normality of residuals
   - Evaluated the model using metrics such as MAE, RMSE, R², and Adjusted R².

## 📈 Analysis Highlights

- **Column Profiling**: Dropped unique row identifiers to avoid skewed model interpretations.
- **Correlation Check**: Identified interrelations among independent variables.
- **Model Evaluation**: Provided detailed analysis of linear regression results, ensuring robustness through various regression models.

## 💡📚 Insights & Recommendations

- Based on the analysis, specific factors like GRE Scores, TOEFL Scores, and Undergraduate GPA were found to be significant predictors of admission chances.
- Recommendations for students and educational consultants include focusing on improving these key areas to enhance admission probabilities.

## 💼 Conclusion

This project not only sheds light on the critical factors influencing graduate admissions but also provides actionable insights for future applicants. The linear regression model developed serves as a predictive tool, offering students a data-driven way to assess their admission chances to Ivy League institutions.
