# Predicting Type 2 Diabetes Risk using NHANES Data

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Source](#data-source)
3. [Methodological Approach](#methodological-approach)
    - [Logistic Regression](#logistic-regression)
    - [Generalized Estimating Equations (GEE)](#generalized-estimating-equations-gee)
4. [Key Findings](#key-findings)
    - [Influential Risk Factors](#influential-risk-factors)
    - [Sociodemographic Insights](#sociodemographic-insights)
    - [Clinical Indicators](#clinical-indicators)
5. [Recommendations](#recommendations)
    - [Clinical Intervention Priorities](#clinical-intervention-priorities)
    - [Population Health Strategies](#population-health-strategies)
    - [Resource Allocation](#resource-allocation)
    - [Screening Protocol Updates](#screening-protocol-updates)
6. [Model Performance Considerations](#model-performance-considerations)
7. [Future Directions](#future-directions)
8. [Conclusion](#conclusion)

## Project Overview
Type 2 Diabetes (T2D) is a global health crisis, with the number of affected adults projected to rise to 783 million by 2045. As a leading healthcare company focused on defeating diabetes, Novo Nordisk is committed to leveraging data science to drive early intervention and targeted prevention strategies.

This project aims to develop a robust, data-driven proxy for T2D risk using the National Health and Nutrition Examination Survey (NHANES) dataset (2015-2016). By applying advanced analytical techniques, we seek to uncover key risk factors and create a predictive model that can identify high-risk individuals before the onset of symptoms. The insights gained from this work can inform Novo Nordisk's strategies for personalized prevention and guide the development of targeted interventions.

## Data Source
The National Health and Nutrition Examination Survey (NHANES) is a comprehensive, nationally representative dataset that captures a wide range of health, nutrition, and sociodemographic data for the U.S. population. This rich resource provides an invaluable opportunity to study the complex interplay of factors contributing to type 2 diabetes risk.

## Methodological Approach

### Logistic Regression
Logistic regression was employed to identify the most influential predictors of T2D risk. This approach enabled us to quantify the relative importance of each risk factor and produce a ranked list of variables based on their coefficients and statistical significance.

### Generalized Estimating Equations (GEE)
To account for the clustered nature of the NHANES data, we utilized Generalized Estimating Equations (GEE) modeling. GEE allowed us to assess the statistical significance of the relationships between predictors and the binary T2D risk outcome, while appropriately handling the clustering within the data.

## Key Findings

### Influential Risk Factors
- Obesity emerged as the strongest predictor, with a coefficient of 9.36, indicating a substantial increase in T2D risk for obese individuals.
- Age was a crucial factor, with older age groups (60+ years and 46-60 years) showing significantly higher risk.
- Smoking, hypertension, and elevated blood pressure were also identified as important clinical indicators of T2D risk.

### Sociodemographic Insights
- Education level was an important social determinant, with lower education (less than 9th grade) associated with higher T2D risk.
- Income (measured by INDFMPIR) was inversely correlated with risk, suggesting that lower-income populations face a greater burden of T2D.
- All racial/ethnic minority groups showed elevated risk compared to the reference group.

### Clinical Indicators
- Stage 2 hypertension was a strong predictor, with a coefficient of 1.86.
- Both systolic and diastolic blood pressure contributed to increased T2D risk.

## Recommendations

### Clinical Intervention Priorities
- Implement targeted screening programs for obese patients, older adults, individuals with hypertension, and current smokers.

### Population Health Strategies
- Focus preventive resources on communities with lower education levels and income.
- Develop tailored interventions for specific age groups, with increased attention to the 46+ population.
- Implement smoking cessation programs, especially for high-risk groups.

### Resource Allocation
- Allocate resources to identify and engage high-risk segments, such as obese patients with hypertension, older adults with limited education, and lower-income communities.
- Prioritize the development of personalized prevention strategies based on the identified risk factors.

### Screening Protocol Updates
- Consider more frequent screening for patients with multiple risk factors.
- Establish risk-stratified screening frequencies based on BMI category, age group, blood pressure, and socioeconomic indicators.

## Model Performance Considerations
- The model demonstrates strong discrimination, with a high recall of 0.93 for high-risk cases.
- The false negative rate of 7% is relatively low but still requires attention in clinical settings.
- Implementing a lower threshold for high-risk classification may be beneficial in specific high-risk populations.

## Future Directions
- Explore the integration of additional data sources, such as electronic health records, to enhance the predictive power of the model.
- Investigate the potential for machine learning techniques, like ensemble methods or neural networks, to further improve the model's performance.
- Conduct prospective studies to validate the model's predictive ability and assess its real-world impact on early intervention and prevention strategies.

## Conclusion
This project has demonstrated the power of data science in addressing the global challenge of type 2 diabetes. By leveraging the NHANES dataset and applying advanced analytical techniques, we have developed a robust predictive model that can identify high-risk individuals. The insights gained from this work can inform strategies for personalized prevention and guide the development of targeted interventions, ultimately contributing to the company's mission of defeating diabetes and other serious chronic diseases.
