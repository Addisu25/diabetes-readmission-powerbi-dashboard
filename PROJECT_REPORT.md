# 30-Day Hospital Readmission Analytics Dashboard

## Project Title

30-Day Hospital Readmission Analytics Dashboard using Power BI, Python, SQL, DAX, and Power Query

## Executive Summary

This project analyzes diabetes hospital encounter data to monitor 30-day readmissions, identify high-risk patient groups, and support healthcare quality improvement reporting. The dashboard was designed for executive users, clinical quality teams, and operational analysts who need clear insight into readmission trends, patient risk factors, and clinical drivers.

The project analyzed 101,766 hospital encounters and 71,518 unique patients. The overall 30-day readmission rate was 11.2%, with 11,357 encounters resulting in readmission within 30 days.

## Business Problem

Hospital readmissions within 30 days are an important healthcare quality and patient safety indicator. High readmission rates may suggest issues with discharge planning, medication management, follow-up care, or care coordination.

This project addresses the following questions:

- What is the overall 30-day readmission rate?
- Which patient groups have higher readmission risk?
- How does readmission vary by diagnosis group?
- How does length of stay relate to readmission risk?
- Which KPIs should executives monitor regularly?

## Dataset

The project uses diabetes hospital encounter data from 130 US hospitals.

Key fields include:

- Patient number
- Encounter ID
- Age, gender, and race
- Length of stay
- Diagnosis codes
- Admission and discharge indicators
- Medication information
- Prior inpatient, outpatient, and emergency visits
- Readmission status

## Tools Used

- Power BI for dashboard development and visualization
- Python for data cleaning, feature engineering, and risk group creation
- SQL for staging, joins, analytics views, and quality checks
- DAX for KPI measures and readmission calculations
- Power Query for data loading and transformation

## Data Preparation

Python was used to clean and prepare the dataset for dashboard reporting. The workflow included:

- Handling missing values
- Removing duplicate encounters
- Creating a 30-day readmission flag
- Creating length-of-stay groups
- Grouping diagnosis codes into clinical categories
- Creating medication and insulin-use indicators
- Developing patient risk groups using prior inpatient visits, medication changes, insulin use, diagnosis patterns, and length of stay

The processed data was exported into Power BI-ready tables:

- `fact_encounters.csv`
- `dim_patients.csv`
- `dim_diagnoses.csv`

## Dashboard Pages

### 1. Executive Overview

This page summarizes hospital readmission performance using high-level KPIs.

KPIs included:

- Total Admissions
- Unique Patients
- 30-Day Readmissions
- Readmission Rate
- Average Length of Stay
- High-Risk Patients

Main visuals:

- Readmission rate by month
- Readmission rate by risk group
- Readmission rate by diagnosis group
- Readmission rate by length of stay

### 2. Patient Risk Segmentation

This page focuses on identifying patient groups with higher readmission risk.

Visuals included:

- Admissions by risk group
- Readmission rate by risk group
- Readmission rate by prior inpatient group
- High-risk patient table

### 3. Operations Drill-Down

This page supports detailed review of patient encounters.

Fields included:

- Encounter ID
- Patient number
- Age
- Gender
- Race
- Length of stay
- Prior inpatient visits
- Risk score
- Risk group
- Readmission status

## Key Findings And Interpretation

### 1. Overall 30-Day Readmission Rate Was 11.2%

Out of 101,766 hospital encounters, 11,357 resulted in readmission within 30 days. This indicates that readmission is a meaningful quality and patient safety issue in the dataset.

### 2. Very High-Risk Patients Had The Highest Readmission Rate

Patients in higher risk groups showed higher readmission rates. This suggests that risk segmentation can help healthcare teams prioritize patients who may need additional follow-up after discharge.

### 3. Longer Length Of Stay Was Linked With Higher Readmission Risk

Patients with longer hospital stays had higher readmission rates. This may reflect greater clinical complexity and the need for stronger discharge planning and care coordination.

### 4. Diagnosis Group Influenced Readmission Patterns

Readmission rates varied across diagnosis groups. This helps identify clinical areas where targeted quality improvement actions may be useful.

### 5. Prior Inpatient Visits Were Useful For Risk Identification

Patients with previous inpatient visits were more likely to be categorized as higher risk. This supports the use of prior utilization history in readmission monitoring.

## Recommendations

- Prioritize discharge follow-up for high-risk and very high-risk patients.
- Use the dashboard to monitor readmission rate trends over time.
- Review patients with longer length of stay before discharge.
- Investigate diagnosis groups with higher readmission rates.
- Use patient-level drill-down tables to support care coordination and quality improvement discussions.

## Portfolio Value

This project demonstrates practical skills in healthcare analytics, business intelligence, data cleaning, dashboard design, and executive reporting. It shows the ability to move from raw data to actionable insights using Python, SQL, Power BI, DAX, and Power Query.

## Summary

Built an end-to-end healthcare analytics project using Python, SQL, Power BI, DAX, and Power Query to analyze 101,766 diabetes hospital encounters and monitor 30-day readmissions. Created data-cleaning scripts, risk groups, KPI measures, trend analysis, and executive dashboard pages to support patient safety and quality improvement reporting.

