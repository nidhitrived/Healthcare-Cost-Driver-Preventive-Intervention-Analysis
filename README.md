# Healthcare-Cost-Driver-Preventive-Intervention-Analysis

## Project Overview:
This project analyzes the key factors influencing healthcare costs using a medical insurance dataset. Statistical tests and machine learning models were applied to evaluate the impact of lifestyle factors and chronic diseases. A composite “disease burden” feature was introduced to improve predictive performance. The final model demonstrates that cumulative health conditions significantly influence medical costs, although additional variables are needed for high-accuracy predictions.

## Objectives:
* Analyze how smoking, diabetes, and BMI affect medical costs
* Evaluate impact of multiple chronic diseases
* Build predictive models for cost estimation
* Compare models and identify best-performing approach

## Tools used:
Python, Pandas, NumPy, Scikit-Learn, Matplotlib

## Dataset Description:
* Records: ~100,000 patients
* Features: 54 demographic, lifestyle, clinical, and utilization variables
* Target Variable: total_medical_cost

## Methology:

1. Data Cleaning:
   - Fixed header inconsistencies
   - Validated datatype
   - Checked Duplicates and missing values
   
2. Exploratory Data Analysis (EDA):
   - Cost distribution analysis
   - Age, BMI, smoking, and chronic disease impact
   - Reginal Cost Comparison
     
3. Cost Driver Analysis:
   - Correlation Analysis
   - Hypothesis testing (t-test, ANOVA)
   - Identification of statistically significant costs drivers
     
4. Predictive Modeling:
   - Linear Regression (interpretability)
   - Random Forest Regressor (accuracy)
  
## Results
- Best Model: Linear Regression with disease_count
- R² Score: 0.133
- RMSE: 2921

## Key Findings:
* Smoking status, chronic diseases, BMI, age, and healthcare utilization are major cost drivers
* Disease burden is a strong predictor
* Linear models outperform complex models

## Limitations
* Low R² (~0.13) → limited prediction accuracy
* Missing variables like:
  - Treatment history
  - Lifestyle habits
  - Hospital type
* Dataset may not capture real-world complexity fully

## Conclusion
This study demonstrates that lifestyle factors and chronic diseases play a significant role in determining healthcare costs. The introduction of a composite disease burden feature improved predictive performance, highlighting the importance of cumulative health conditions. While the model provides useful insights, future work should incorporate additional variables to enhance prediction accuracy.


 

