# Pulse of Prevention: Heart Disease Analysis

## Project Overview
Pulse of Prevention is an exploratory data analysis (EDA) project focused on understanding the factors contributing to heart disease. Using a dataset of 1,025 patients, this analysis identifies key risk factors, explores patient profiles, and provides insights for early interventions to improve patient outcomes.

## Objective:
- Identify key factors contributing to heart disease
- Develop profiles of high-risk patients
- Suggest actionable preventive measures
- Provide insights for healthcare providers to optimize patient care

## Dataset
Source: [Heart Disease Dataset - Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

Size: 1,025 entries, 14 features

Features include:
- Demographics: Age, Sex
- Clinical measurements: Blood pressure (trestbps), Cholesterol (chol), Max heart rate (thalach), ST depression (oldpeak)
- Medical history: Fasting blood sugar (fbs), Thalassemia (thal), Exercise-induced angina (exang)
- Diagnostic results: Chest pain type (cp), Resting ECG (restecg), Slope of ST segment (slope), Number of major vessels (ca)
- Outcome: Heart disease presence (target)

## Key Findings
1. Demographics & Clinical Insights
- Average age: 54 years
- Male patients: 59%, Female patients: 41%
- Average blood pressure: 132 mmHg
- Average cholesterol: 246 mg/dL
- 15% of patients have high fasting blood sugar (>120 mg/dL)
 
2. Heart Disease Risk Factors
- Strongest predictors: Chest pain type (cp), Exercise-induced angina (exang), ST segment slope (slope), Max heart rate (thalach)
- Patients with fixed thalassemia defects (thal=2) are at higher risk
- Age, cholesterol, and blood pressure are contributing factors, especially when combined with other risk indicators

3. Age & Risk Trends
- Heart disease prevalence is significant in the ages 40–60
- Early 40s and late 50s are critical windows for preventive interventions

4. Predictive Modeling
- Logistic Regression using all features achieved ~81% accuracy
- Model effectively identifies at-risk patients for early intervention
- Clinical & Business Impact
- Targeted screening for high-risk patients improves early detection
- Personalized interventions based on ECG, thalassemia, and clinical measurements enhance patient outcomes
- Data-driven insights guide resource allocation and preventive healthcare strategies

## Exploratory Data Analysis
- Distribution Analysis: Age, gender, chest pain types, thalassemia types
- Correlation Analysis: Identifying key relationships between variables and heart disease presence
- Risk Factor Combinations: Most common profiles in heart disease patients
- Clinical Measurement Comparison: Differences between patients with and without heart disease
Visualizations Used:
Histograms, Bar Charts, Line Plots, Pair Plots, Heatmaps

## Conclusion
This EDA highlights the critical factors influencing heart disease and demonstrates the potential for data-driven preventive healthcare. Combining demographic data, medical history, and clinical measurements enables targeted interventions and improved patient outcomes.

## Future Work
- Include time-to-event data for true survival analysis
- Apply advanced predictive models (Random Forest, XGBoost) for higher accuracy
- Explore lifestyle and environmental factors for a more comprehensive risk assessment

## Technologies
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Power BI
 
## Dashboard View
![Dashboard]()

## Author
BuiltbyAmiee
