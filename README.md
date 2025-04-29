# Dichotomous-outcome-using-odd-and-risk-ratio

# 🧪 Breast Cancer Recurrence Analysis in R

This project investigates the association between selected clinical factors and the recurrence of breast cancer using statistical analysis in **R**.

##  Summary of Findings

### 1. Menopause Status and Breast Cancer Recurrence
- **Risk Ratio (RR):** 1.07 (95% CI: [0.92, 1.25])
- **Odds Ratio (OR):** 1.26 (95% CI: [0.75, 2.12])
- **Chi-squared p-value:** 0.375
- **Conclusion:** No statistically significant association found between menopause status and cancer recurrence.

### 2. Side of Breast Affected
- **Risk Ratio (RR):** 0.94 (95% CI: [0.80, 1.09])
- **Odds Ratio (OR):** 0.80 (95% CI: [0.48, 1.34])
- **Chi-squared p-value:** 0.391
- **Conclusion:** No statistically significant link between breast side (left or right) and recurrence.

### 3. Irradiation Treatment
- **Risk Ratio (RR):** 1.38 (95% CI: [1.10, 1.74])
- **Odds Ratio (OR):** 2.56 (95% CI: [1.45, 4.53])
- **Chi-squared p-value:** 0.001
- **Conclusion:** Statistically significant association found. Patients who received irradiation had a higher likelihood of recurrence.

## 📝 Conclusion

While menopause status and breast side showed no significant relationship with recurrence, **irradiation treatment** was significantly associated with a higher risk and odds of recurrence. This highlights the need for careful consideration of treatment strategies and monitoring protocols for patients undergoing irradiation.

## 🛠 Tools & Technologies
- **Language:** R
- **Data Handling & Analysis:** base R, dplyr, stats
- **Visualization (if applicable):** ggplot2

## 📂 Project Structure
. ├── data/ # Raw or cleaned dataset 

  ├── scripts/ # R scripts for analysis 
  
  ├── results/ # Output results and plots 
  
  └── README.md # Project documentation
