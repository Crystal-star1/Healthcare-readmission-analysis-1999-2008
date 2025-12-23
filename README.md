# Healthcare Readmission Driver Analysis (1999-2008)

## Project Overview
This project analyzes over 100,000 diabetes patient encounters from 130 US hospitals to identify clinical, demographic, and operational drivers of the network's 46% readmission rate.

**Tools Used:** Python, Pandas, Matplotlib, Seaborn, Google Colab.

## Key Findings & Recommendations

### 1. Clinical Focus: Heart Failure
Heart Failure (ICD-9 428) is the #1 highest volume diagnosis and carries a severe (~50%) readmission risk.
* **Recommendation:** Establish a targeted discharge transition program specifically for heart failure patients.

### 2. Demographic Risk: The Age Factor
Heatmap analysis revealed that age is a universal risk amplifier. Patients over 80 have a >50% probability of returning, regardless of gender.
* **Recommendation:** Implement automatic high-risk geriatric care protocols for all admissions aged 80+.

### 3. Operational Insight: Length of Stay
Data shows a positive correlation between longer hospital stays and higher readmission rates, suggesting that Length of Stay (LOS) is a proxy for patient acuity rather than premature discharge.
* **Recommendation:** Balance LOS reduction targets against patient complexity scores to prevent pushing high-acuity patients out too quickly.

---
*Feel free to open the `Hospital_Readmission_Analysis.ipynb` file above to view the full code and detailed visualizations.*
