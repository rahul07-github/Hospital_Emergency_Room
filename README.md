# Hospital Emergency Room Dashboard Dataset
**A comprehensive dataset for analyzing emergency-room patient flow, wait times, admission rates, and demographic breakdowns.**
## Project Description

This repository contains the raw data behind the **Hospital Emergency Room Dashboard** (visualized in the provided screenshots).  
The data covers **patient visits from 01-April-2023 to 30-October-2024** and includes:

* Individual patient records (ID, name, gender, age, race, admission date, wait time, referral department, admission status)
* Aggregated monthly and consolidated metrics (total patients, average wait time, satisfaction score, referrals, etc.)
* Visual breakdowns by age group, gender, race, department, day-of-week, and hour-of-day.

The dataset is ideal for:
* Building interactive dashboards (Power BI, Tableau, Streamlit, etc.)
* Performing statistical analysis on ER performance
* Training predictive models for wait-time forecasting or admission likelihood

-----
## 📊 Dataset Summary

The dataset contains detailed records of ER patients covering the period April 2023 – October 2024.
Each record includes demographic, operational, and administrative information such as:
| Field                   | Description                                                          |
| ----------------------- | -------------------------------------------------------------------- |
| **Patient ID**          | Unique identifier for each patient                                   |
| **Patient Name**        | Anonymized name of the patient                                       |
| **Gender**              | Male, Female, or Not Confirmed                                       |
| **Age**                 | Age of the patient at the time of admission                          |
| **Race**                | Patient’s self-identified race category                              |
| **Admission Date**      | Date of ER visit or admission                                        |
| **Department Referral** | Department where patient was referred (e.g., Orthopedics, Neurology) |
| **Wait Time (min)**     | Duration between arrival and being attended by a doctor              |
| **Admission Status**    | Whether the patient was Admitted or Not Admitted                     |
| **Satisfaction Score**  | Average satisfaction rating reported by patients                     |

-------
## 🧠 Insights and Patterns
### Key observations from the data visualizations:
* Average Wait Time: ~35–37 minutes, indicating moderate ER load.
* Patient Satisfaction: High average score of 4.7–4.9, showing good service quality.
* Admission Rate: Roughly 50% of total visits result in admission.
* Gender Distribution: Fairly balanced — ~49% male and ~51% female.
* Age Group: Most visits come from the 30–49 age range.
* Race Breakdown: Majority of patients are White (≈28%), followed by African American (22%), and others.
* Peak Hours: Highest patient inflow between 09:00 AM – 03:00 PM, particularly on Wednesdays and Fridays.
* Referral Patterns: Most patients have no referrals (≈60%), while General Practice and Orthopedics are the most common referred departments.

------------
## ⚙️ Dashboard Features

* Monthly View: Focused analysis for a specific month (e.g., Feb 2024).
* Consolidated View: Year-to-date or multi-month overview with trend analysis.
* Patient Details View: Detailed patient-level data table for validation or record tracing.
* Filters: Year, Month, and custom date range slicers for flexible time analysis.
* KPIs: Dynamic cards showing patient count, wait time, satisfaction, and referrals.
* Drill-through Navigation: Buttons and icons for switching between pages.

---------------
## 🧩 Tools and Dependencies
* Power BI Desktop (v2.122 or later)
* Data Source: Hospital ER internal database or CSV import
* Refresh Schedule: Recommended monthly or weekly updates
* System Requirements: Windows 10+, 8 GB RAM minimum for Power BI smooth performance

---------
## 💡 How to Use
1. Open the .pbix file in Power BI Desktop.
2. Refresh data using the “Transform Data” > “Refresh” option if a live connection is available.
3. Use the slicers to filter by Month, Year, or Date Range.
4. Navigate between tabs — Monthly View, Consolidated View, and Patient Details.
5. Export insights as a PDF or Power BI Service report for management presentation.

-----------
## 🧭 Key Insights Summary
* Operational efficiency is consistent with 65% of patients seen within 30 minutes.
* Wednesdays show the highest volume of ER visits.
* Younger and middle-aged adults form the majority of ER patients.
* Department referral data suggests potential improvement in coordination between General Practice and specialty departments.

---------
## 🙏 Acknowledgment
**Special thanks to the Hospital Data Scientist Team for collecting, cleaning, and maintaining the ER dataset. Appreciation is extended to the Health IT Department for integrating the data infrastructure and supporting Power BI deployment.**
