# Parkinson-s_Disease_Symptom_Severity_Prediction_Model

## Overview

Parkinson's disease is a neurodegenerative disorder characterized by motor and non-motor symptoms that progress over time. Early detection and monitoring of symptom severity are crucial for effective management and personalized treatment plans. 

This project leverages machine learning techniques to predict the severity of Parkinson's disease symptoms, focusing on the `total_UPDRS` (Unified Parkinson's Disease Rating Scale) score. By analyzing voice-based biomarkers, the model provides a data-driven approach to monitor disease progression and support clinical decision-making.

---

## Workflow

1. **Data Preprocessing**:
   - Handled missing values and outliers.
   - Normalized features to ensure uniformity.

2. **Feature Selection**:
   - Employed techniques to identify significant predictors.

3. **Model Development**:
   - Tested algorithms including Linear Regression, Support Vector Machines, and Random Forests.
   - Performed hyperparameter tuning for optimal performance.

4. **Model Evaluation**:
   - Assessed models using metrics like Mean Squared Error and R-squared.

## Results

The Random Forest model outperformed others, achieving:
- **R-squared (R²)**:  0.98

These metrics indicate a high level of accuracy in predicting symptom severity.

## Conclusion

This project demonstrates the potential of machine learning to predict the severity of Parkinson's disease symptoms based on voice biomarkers. The **Random Forest Regressor** model offers a reliable tool for monitoring disease progression, which can have several significant impacts:

1. **Early Intervention**: By predicting symptom severity with high accuracy, the model can help healthcare providers identify worsening conditions early and adjust treatment plans accordingly.
2. **Personalized Treatment Plans**: Insights from the model can be used to tailor treatments based on predicted symptom progression.
3. **Remote Monitoring**: Since the dataset is based on voice recordings, this approach can enable remote monitoring, reducing the need for frequent hospital visits.
4. **Improved Quality of Life**: Accurate monitoring and timely intervention can help patients manage their symptoms more effectively, enhancing their overall quality of life.

This project highlights the transformative role machine learning can play in healthcare, particularly in managing chronic conditions like Parkinson's disease.
