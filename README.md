# NHS_Dataset_WaitingList_Excel## Overview
This repository provides a **mock dataset and analysis** of NHS patient waiting times for educational and analytical purposes. The dataset simulates patient-level records, enabling exploration of waiting time performance across services, trusts, and patient demographics.

The Excel workbook includes:

- **Raw patient data** (100 fictional records)  
- **Pre-calculated key performance indicators (KPIs)**, including:
  - Average and median waiting times  
  - Compliance with the 18-week RTT (Referral to Treatment) standard  
  - Long-wait backlogs (>52 weeks)  
  - Comparisons by NHS Trust and service type  

---

## Workbook Structure

### 🔹 Sheet 1: Raw_Data
This sheet contains the **full source dataset**, including:

- **Patient ID**  
- **NHS Trust** (code + name)  
- **Service type** (Outpatient / Inpatient / Diagnostic)  
- **Referral & appointment dates**  
- **Waiting time in days** and **category** (`<18 weeks`, `18–52 weeks`, `>52 weeks`)  
- **Demographics**: age group, gender, ethnicity  
- **Deprivation quintile** (1 = most deprived, 5 = least deprived)  
- **Month** of referral/appointment  

### 🔹 Sheet 2: Analysis_Results
This sheet provides **pre-calculated KPIs** in a report-ready format:

| Metric | Result | Explanation |
|--------|--------|------------|
| Average waiting time (days) | Calculated | Overall system performance |
| Median waiting time (days) | Calculated | Central tendency, less influenced by extreme waits |
| % seen within 18 weeks | Calculated | Compliance with RTT standard |
| Patients waiting over 52 weeks | Calculated | Indicator of backlog severity |
| Average wait per Trust | Calculated | Comparison across NHS Trusts |
| Average wait per Service Type | Calculated | Outpatient vs Inpatient vs Diagnostic |

Each metric includes an explanation to aid reporting and interpretation.

---

## Pivot Table Overview
A pivot table provides a **comprehensive summary of waiting times** by:

- **NHS Trust**  
- **Age group**  
- **Gender**

This allows quick comparison across trusts and patient groups, supporting further analysis, performance evaluation, and reporting.
