# Hospital-Administration-Analysis
## Reducing Readmissions: Excel-Based Data Analytics Case Study

## Project Overview
This project focuses on analyzing hospital admission data to **reduce unnecessary readmissions** and improve patient care quality using **Microsoft Excel**. The hospital observed increasing readmission rates, leading to higher costs and potential patient care issues. The goal of this analysis is to uncover patterns, trends, and factors associated with readmissions to guide hospital interventions.

**Scenario:** As a data analyst in Novartis' hospital administration, you are tasked with understanding the causes of readmissions and recommending actionable solutions to improve patient outcomes and operational efficiency.

### Key Columns Analyzed
| Column | Description |
|--------|-------------|
| `encounter_id`, `patient_id` | Unique identifiers |
| `age`, `gender`, `race` | Patient demographics |
| `time_in_hospital` | Length of stay |
| `medical_specialty` | Specialty of admitting physician |
| `num_lab_procedures`, `num_procedures`, `num_medications` | Interventions performed |
| `number_outpatient`, `number_emergency`, `number_inpatient` | Past year visit counts |
| `diag_1`–`diag_5` | Diagnoses codes |
| `change`, `diabetesMed` | Medication info |
| `readmitted` | Target variable (<30 days = 1, else 0) |


## Analysis Performed in Excel
- **Data Cleaning & Preprocessing:**  
  - Handled missing values (`weight`, `num_medications`, etc.)  
  - Standardized categorical variables (`race`, `gender`, `medical_specialty`)  
- **Descriptive Analysis:**  
  - Readmission rates by **age, gender, race, and weight categories**  
  - Average **length of stay by medical specialty**  
  - Distribution of **emergency, outpatient, and inpatient visits**  
  - Diabetes-related readmission analysis  
- **Trend & Correlation Analysis:**  
  - Relationships between **lab procedures, number of medications, and readmission**  
  - Correlation of **past visits** with readmission rates  
  - Seasonal trends in readmission rates  
- **Pivot Tables & Charts:**  
  - Interactive pivot tables for summarizing readmissions  
  - Bar charts, line charts, and pie charts for visual insights  
  - Conditional formatting to highlight high-risk categories
 
## Key Insights
- Patients aged 70–90 show the highest readmission rate (58.8%), indicating that elderly patients are more likely to return to the hospital after discharge.

- Patients with a higher number of emergency visits have a greater likelihood of readmission, often due to more severe or unstable health conditions.

- Diabetic inpatients experience higher readmission rates than non-diabetic patients, as diabetes can slow the healing and recovery process.

- Patients with frequent outpatient visits tend to have higher readmission rates, which may indicate ongoing or chronic health problems.

- Patients with multiple diagnoses are more likely to be readmitted, suggesting that complex health conditions increase the risk of returning to the hospital.

- Patients taking a higher number of medications generally have longer hospital stays, as they often have more serious or multiple medical conditions.

- Diagnosis code 283 shows high healthcare utilization, since blood-related disorders often require frequent monitoring and emergency care.

- Patients who undergo more laboratory tests tend to have slightly lower readmission rates, possibly due to better diagnosis and closer medical monitoring.

## Deliverables
- **Excel File with Analysis:** Pivot tables, charts, and calculations  
- **Insights Summary:** Actionable conclusions for hospital administration  
- **Recommendations:** Targeted interventions for high-risk patient groups  

## Autor
**Saransh Goyal**  
**Email:** goyalsaransh61@gmail.com  
**LinkedIn:** [linkedin.com/in/saranshgoyal007](https://www.linkedin.com/in/saranshgoyal007/)  
**GitHub:** [github.com/Saransh3041](https://github.com/Saransh3041)




