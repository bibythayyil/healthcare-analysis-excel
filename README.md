# Healthcare Analysis and Insights

> An Excel-based healthcare data analysis project covering data cleaning, medical examination records, hospitalisation details, and an interactive dashboard.

---

## Project Overview

This project performs end-to-end data analysis on a healthcare dataset using Microsoft Excel. Starting from raw, uncleaned data across multiple sheets, the project applies data transformation techniques to produce a clean, consolidated dataset, followed by structured analysis and an interactive dashboard summarizing key healthcare insights.

---

## Workbook Structure

| Sheet | Description |
|---|---|
| Customer Names | Raw customer data — name splitting and transformation applied |
| Medical Examinations | Patient health indicators including BMI, HbA1C, diabetes status, heart issues, transplant history, cancer history, surgeries, and smoking status |
| Hospitalisation Details | Admission records including date, age, charges, hospital tier, city tier, and state — with corrections applied |
| Healthcare | Consolidated and cleaned dataset combining customer, medical, and hospitalisation data |
| Analysis | Pivot table analysis addressing key healthcare questions |
| Dashboard | Interactive visual summary of key findings |

---

## Data Cleaning Performed

- Split combined name column into Title, First Name, and Last Name
- Corrected inconsistent date formats (year, month, date columns)
- Standardised hospital tier, city tier, and state ID fields
- Corrected smoking status inconsistencies
- Fixed NumberOfMajorSurgeries column errors
- Merged cleaned data into a single consolidated Healthcare sheet

---

## Analysis Questions Addressed

1. Distribution of cancer history among smokers vs non-smokers
2. Total major surgeries and average HbA1C for patients with and without transplant history
3. Healthcare charges by weight status and diabetes status
4. Average charges by hospital tier within different states
5. Correlation between age and both BMI and HbA1C
6. Relationship between age and healthcare charges

---

## Key Features

- **Data Transformation** — raw multi-sheet data cleaned and consolidated
- **Pivot Tables** — structured analysis across multiple dimensions
- **Data Validation** — corrected columns alongside original for transparency
- **Dashboard** — interactive visual summary of healthcare metrics
- **Formula-driven** — analysis built on Excel formulas, not hardcoded values

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning, analysis, pivot tables, dashboard |
| Text to Columns | Name splitting and data transformation |
| Pivot Tables | Multi-dimensional analysis |
| Excel Charts | Data visualization |

---

## How to Use

1. Download `Healthcare_Analysis_and_Insights.xlsx`
2. Open in Microsoft Excel (recommended) or Google Sheets
3. Navigate sheets in order: Customer Names → Medical Examinations → Hospitalisation Details → Healthcare → Analysis → Dashboard
4. The Dashboard sheet provides an interactive summary of all key findings

---

## Author

**Bibin T S**

---

## Related Projects

- [Sleep, Stress & Lifestyle Analysis Using Wearable Health Data (Python)](https://github.com/bibythayyil/sleep-stress-lifestyle-analysis-python)
