# Diabetes-Analytics-Dashboard-Power-BI-
This project presents a Power BI dashboard built on a diabetes dataset to analyze patient health indicators and identify risk patterns.

## Dataset Description
  The dataset contains health-related attributes of patients:
  - Age – Age of the patient
  - Pregnancies – Number of pregnancies
  - Glucose – Glucose level
  - BloodPressure (mg/dL) – Blood pressure level
  - SkinThickness – Skin fold thickness
  - Insulin – Insulin level
  - BMI – Body Mass Index
  - DiabetesPedigreeFunction – Diabetes hereditary score

## Data Cleaning & Transformation
  The following preprocessing steps were performed:
  - Renamed columns for better readability
  - Standardized column naming (capitalization)
  - Assigned appropriate data types
  - Replaced invalid/zero values with null
  - Corrected scaling issues in selected columns

## Dataset Enrichment
  ### Calculated Columns:
  - BMI Category
  - Age Group
  - Glucose Category
  - Risk Score
  ### Measures:
  - Total Patients
  - Average BMI
  - Average Glucose
  - Average Blood Pressure
  - High Risk Patients
  - High Risk %
  - Average Insulin
  - Average Pregnancies
  - Average Risk Score

## Visualizations
  ### KPI Cards:
  - Total Patients
  - Average Blood Pressure
  - Average Risk Score
  - Average Insulin
  - High Risk Patients
  ### Donut Charts:
  - Patients by BMI Category
  - Patients by Glucose Category
  - Pregnancies by Age Group
  ### Gauge Charts:
  - Average Glucose
  - Average BMI
  - Average Risk Score
  ### Tree Map:
  - Patients by Age Category
  ### Area Chart:
  - High Risk Patients by Age
  ### Matrix:
  - BMI vs Glucose
  - Age vs Glucose
