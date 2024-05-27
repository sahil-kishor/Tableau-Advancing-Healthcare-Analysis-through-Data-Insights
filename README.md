# Healthcare Analysis Using Tableau

## Objective:

The primary objective of this project is to harness the powerful capabilities of Tableau to create a compelling and insightful narrative from the provided healthcare datasets. This involves meticulous data preparation, intelligent data modeling, and the adept use of calculated fields and Tableau functions for sophisticated analyses. The ultimate goal is to develop an interactive and intuitive Tableau dashboard that effectively communicates key findings, providing actionable insights to optimize healthcare operations and performance.

![Healthcare](https://github.com/sahil-kishor/Tableau-Advancing-Healthcare-Analysis-through-Data-Insights/assets/159517524/58823484-c702-4840-8931-2ae94e45a73f)


## Data Sources:

***1. HealthcareDataset1:***

This dataset contains patient-related information:

**PatientID:** Unique identifier for each patient (Primary Key).

**PatientName:** Name of the patient.

**Age:** Age of the patient.

**Gender:** Gender of the patient.

**BloodType:** Blood type of the patient.

**Diagnosis:** Diagnosis given to the patient.

**Treatment:** Treatment provided to the patient.

**AdmissionDate:** Date of patient admission.

**DischargeDate:** Date of patient discharge.

**TotalBill:** Total bill amount for the treatment.

**Full Prescription Details:** Comprehensive prescription details including medication names, dosages, frequency, and duration.

***2. HealthcareDataset2:***

This dataset provides additional treatment-related details:

**PatientID:** Unique identifier for each patient, corresponding to 'PatientID' in HealthcareDataset1 (Foreign Key).

**Hospital:** Name of the hospital where the patient was treated.

**DoctorName:** Name of the treating doctor.

**RoomNumber:** Assigned room number.

**DailyCost:** Daily cost of the patient's treatment.

**TreatmentType:** Type of treatment provided.

**RecoveryRating:** Patient's recovery rating (out of 10).

## Tasks Performed:

1. **Correlation Analysis between Stay Duration and Recovery Rating:**
  - Investigated the correlation between hospital stay duration and recovery ratings to identify any significant relationships.

2. **Clustering for Patient Treatment Patterns:**
  - Applied clustering techniques to group patients based on their treatment patterns and recovery outcomes.

3. **Advanced Calculations for Prescription Analysis:**
  - Analyzed 'Full Prescription Details' to identify the most commonly prescribed medications for each diagnosis.

4. **Hospital Efficiency Analysis:**
  - Measured hospital efficiency based on average stay duration, recovery ratings, and total bill amounts.

5. **Custom Date Parsing for Admission Trends:**
  - Analyzed admission trends by parsing 'AdmissionDate' into day of the week and month to identify peak times.

6. **Dynamic Filters for Patient Demographics:**
  - Created dynamic filters to explore data based on patient demographics such as age, gender, and blood type.

7. **Time-Series Forecasting for Hospital Admissions:**
  - Utilized Tableau's forecasting features to predict the number of hospital admissions over the next six months based on observed trends in 'AdmissionDate' and diagnoses.

# Dashboards Crafted:

## 1. Comprehensive HealthCare Dashboard
![TB Healthcare Dashboard](https://github.com/sahil-kishor/Tableau-Advancing-Healthcare-Analysis-through-Data-Insights/assets/159517524/366c15aa-ef34-4e8c-a4c5-2a0b45b09ab7)


## 2. Hospital Performance Comparison Dahboard
![TB Hospital Comparison Performance Dashboard](https://github.com/sahil-kishor/Tableau-Advancing-Healthcare-Analysis-through-Data-Insights/assets/159517524/7ebc896b-231a-46bc-88ad-f195bae925b7)


## 3. Time Based Analysis Dashboard
![TB Health Care Trend Dashboard](https://github.com/sahil-kishor/Tableau-Advancing-Healthcare-Analysis-through-Data-Insights/assets/159517524/3f69e199-6b04-4933-925a-52967961eca1)


## 4. Treatment Effectiveness Analysis Dashboards
![TB Treatment Affectiveness DAshboard](https://github.com/sahil-kishor/Tableau-Advancing-Healthcare-Analysis-through-Data-Insights/assets/159517524/ed8f083e-05ae-46c7-8acd-9a6afd4fce6d)


## Key Insights:

- **Patient Demographics**: Over three years, there were 337 female patients, 329 male patients, and 334 patients of other genders.

- **Recovery Trends**: Recovery ratings for diabetes patients have been improving over the years.

- **Forecasting Admissions**: Time-series forecasting projected the number of patients for each diagnosis in the upcoming months.

- **Doctor Performance**: Dr. David Moore treated the highest number of patients.

- **Cost Analysis**: Cedar Senai Clinic is the most expensive hospital, followed by Green Valley Medical Center. Silver Oak Medical Plaza is the least expensive.

- **Hospital Ratings**: Maple Groove Health Facility has the highest overall recovery rating.

- **Specialty Performance** : For diabetes, Dr. Elizabeth Davis at Cedar Senai Clinic has the highest recovery rating.

- **Treatment Trends**: The number of patients opting for mental therapy as a treatment type has been increasing over the years.

## Conclusion:

This project leverages Tableau to perform an in-depth analysis of healthcare data, revealing critical insights into patient demographics, treatment patterns, hospital efficiency, and more. The interactive dashboard provides stakeholders with valuable, data-driven insights for enhancing healthcare operations and improving patient outcomes.


## Author

***Sahil Kishor***

***Email : kishorsahil555@gmail.com***

***LinkedIn : www.linkedin.com/in/sahil-kishor***



