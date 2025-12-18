# Healthcare-Cost-Driver-Preventive-Intervention-Analysis

## Project Overview:
Rising healthcare costs are often driven by preventable lifestyle and chronic health factors. This project applies data science and machine learning to identify the primary drivers of medical expenditure and propose data-driven preventive interventions to reduce long-term costs.

## Objectives:
* Identify key factors driving healthcare costs
* Perform statistical validation of cost drivers
* Perform statistical validation of cost drivers
* Build predictive models for medical cost estimation

## Tools used:
Python, Pandas, NumPy, Scikit-Learn, Matplotlib

## Dataset Description:
* Records: ~100,000 patients
* Features: 54 demographic, lifestyle, clinical, and utilization variables
* Target Variable: total_medical_cost

## Project Structure:

Healthcare-Cost-Driver-Analysis/
│
├── data/
│   └── medical_insurance.csv(Kaggle)
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_cost_driver_analysis.ipynb
│   └── 04_modeling.ipynb
├── README.md
└── requirements.txt

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

## Key Findings:
* Smoking status, chronic diseases, BMI, age, and healthcare utilization are major cost drivers
* Healthcare costs are highly right-skewed
* Preventive interventions targeting modifiable risks offer high ROI


 

