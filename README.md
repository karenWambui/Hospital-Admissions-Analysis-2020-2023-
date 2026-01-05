** Hospital-Admissions-Analysis-2020-2023**
A Power BI project analyzing hospital admission trends and patient readmission patterns to uncover insights that can support better healthcare planning and quality of care.


**Executive Summary:**
Using Power BI,I created a dashboard to track patients admissions,readmissions patterns throughout the years 2020 to 2023 to highlight areas of operational and clinical improvement.
The findings show clear seasonal and year to year admissions variations with certain periods experiencing significantly high patient inflow.Some patients account for multiple admissions indicating potential gap in discahrge planning,chronic disease management and follow-up care.
Using the patterns the dashboard enables hospital managemnt and clinical teams to anticipate demand and therefore allocate staff and resources effectively and design targeted interventions to reduce avoidable readmissions.


**Business Problem**
The Hospital management lacks clear, timely visibility into patient admission volumes and readmission patterns. This makes it difficult to plan resources effectively and identify opportunities to reduce avoidable readmissions. This project addresses that gap by analyzing admissions data to uncover trends and risk areas that can inform operational and clinical decisions.

**Methodology**
I used a Kaggle dataset.
The data was cleaned and transformed in Power BI using Power Query:
-Removed duplicates and invalid records
-Handled inconsistent values
-Formated the the columns by trimming them
-Standardized date formats
-Created star-schema model for data modelling
-Created custom measures using DAX
-Power BI dashboard

**Skills Used**
Power BI: ETL,Dax,Calculated columns,data modelling,data visualization,writing functions

**Results**
**Doctors & Patients**
-Total doctors: 40,105
**Total unique patients**
33,142
**Total admissions**
 39,892
**Revenue**
-Total billed revenue (2020–2023): 1.417 billion.2020 had the highest revenue, driven primarily by obesity-related cases.Medicare was the dominant insurer, covering 7,542 admissions and accounting for 230 million in claims. 
**Admissions Trends**
-August was consistently the month with the highest admissions (peak: 908 in August 2020)
-Emergency admissions were the most frequent type, dominating both admissions and readmissions

**Patient Demographics**
-Patients aged 61+ were the most frequently admitted, reflecting increased healthcare needs among older populations
-Obesity was the condition generating the most revenue in 2020, affecting more males than females.

**Readmissions**
-Total readmissions: ~7,500
-Most readmissions were emergency cases
-In 2020, asthma had the highest readmissions

The hospital dataset shows that older patients and emergency cases dominate admissions and readmissions. Revenue is largely driven by obesity-related treatments, with Medicare being the primary insurer. Peak months and conditions are easily identified, enabling better resource planning and targeted interventions.

**Next Steps**
-Reduce readmissions through providing follow-up care and preventive interventions for the high risk
-Optimized resource allocation especially during peak months to plan staffing and bed capacity in advance as well as plan for emergencuyyu cases
-Advanced analytics and predictive modelling using patients demographics ,medical conditions to predict and avoid readmissions.

**Limitations**
The dataset only covers 2020–2023, with no data available for 2024 and 2025.


