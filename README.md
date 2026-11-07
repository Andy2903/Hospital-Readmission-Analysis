# Hospital Readmission Analysis & Risk Prediction

An end-to-end data project focused on analyzing 30-day hospital readmissions across multiple facilities to improve quality of care and reduce Medicare payment penalties.

## 📌 Project Objective & Problem Statement
Hospital readmissions within 30 days of discharge serve as an indicator of hospital quality and heavily impact the cost of care due to Centers for Medicare & Medicaid Services (CMS) payment penalties. 

Using a consolidated healthcare dataset featuring standardized ICD codes, this project cleans patient records through Python and builds an interactive visualization layer in Power BI. The ultimate goal is to identify the critical drivers behind 30-day readmissions to help hospitals optimize patient outcomes and mitigate financial penalties.

## 🛠️ Tech Stack & Project Workflow

1. **Data Cleaning & Wrangling (Python):** 
   - Handled missing values, formatted data types, and validated standardized ICD codes using Pandas.
   - Performed exploratory data analysis (EDA) with inline visual checkpoints to understand data distributions before reporting.
   - Core file: `Hospital readmission Analysis.ipynb`

2. **Data Visualization & Analytics (Power BI):**
   - Imported the dataset cleaned to create columns/measures using conditions and DAX to design an interactive executive dashboard.
   - Tracked critical healthcare KPIs, patient risk distributions, and clinical factors influencing return rates.
   - Core file: `HRA.pbix`

---

## 📊 Key Data Insights from Dashboard

Analyzing a cohort of **100K total patients** revealed several critical operational trends:

* **High-Risk Diagnoses:** Circulatory and respiratory health conditions consistently represent the highest patient volumes (surpassing 30K patients), driving the majority of hospital volume and readmission risk.
* **Age & Care Complexity:** Patient volume heavily peaks in the **[70-90] age brackets** (up to 25K individuals). Older patients maintain a higher Average Length of Stay (~4 days), reflecting escalating clinical complexity.
* **Service Utilization Metrics:** Patients experiencing a 30-day relapse require a substantially higher average number of days utilizing hospital services (**2.01 days**) compared to stable, non-readmitted patients (**0.74 days**).
* **Medication Interventions:** Patients requiring adjustments to their medical regimens manage a significantly higher average baseline of medications (**18.12**) and complex secondary diagnoses (**7.52**).

---

## 📁 Repository Structure
* `Hospital readmission Analysis.ipynb` - Python notebook containing data extraction, processing steps, and exploratory visual analysis notes.
* `HRA.pbix` - Complete, interactive Power BI dashboard file.
