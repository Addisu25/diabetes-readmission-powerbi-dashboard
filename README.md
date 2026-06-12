# 30-Day Hospital Readmission Analytics Dashboard
## Project Overview
This project analyzes 30-day hospital readmissions among diabetes patients using Power BI, Python, SQL, DAX, and Power Query. The goal is to help healthcare teams monitor readmission performance, identify high-risk patient groups, and support patient safety and quality improvement reporting.
## Business Problem
Hospital readmissions within 30 days are an important healthcare quality indicator. High readmission rates may suggest issues with discharge planning, medication management, follow-up care, or care coordination.
This dashboard answers:
- What is the 30-day readmission rate?
- Which patient groups are at higher risk?
- How does readmission rate vary by diagnosis group?
- How does length of stay relate to readmission?
- Which trends should executives monitor?
## Dataset
The project uses diabetes hospital encounter data from 130 US hospitals.

 Processed dataset summary:
- Total admissions 101,766 
- Unique patients 71,518 
- 30-day readmissions  11,357 
- 30-day readmission rate 11.2% 
- Average length of stay 4.4 days 
- High-risk patients 36,593 

## Tools Used
- Power BI
- Python
- SQL
- DAX
- Power Query
## Project Workflow
1. Cleaned and prepared hospital encounter data using Python.
2. Created readmission flags for 30-day readmissions.
3. Built patient risk groups using length of stay, prior inpatient visits, medication changes, insulin use, and diagnosis patterns.
4. Built DAX measures for KPIs and dashboard visuals.
5. Designed Power BI dashboard pages for executive and clinical reporting.
## Dashboard 

<img width="772" height="436" alt="30 days Hospial Readmission Dshbaord" src="https://github.com/user-attachments/assets/9b70381c-e825-4b3d-8496-260330b7ce1c" />


## Key Insights
- The overall 30-day readmission rate was 11.2%.
- Very high-risk patients had the highest readmission rate.
- Patients with longer hospital stays showed higher readmission risk.
- Diagnosis group and prior inpatient visits were useful for identifying readmission patterns.
- Executive KPI cards help summarize hospital quality performance quickly.
