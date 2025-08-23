
🏥 Healthcare Data Insights Dashboard 

📋 Project Overview

This project transforms raw healthcare data into an interactive Power BI dashboard powered by SQL, DAX, and data modeling.
It provides deep insights into patient demographics, admissions, hospital operations, and financial performance.

🎯 Client Problem (Scenario)

The healthcare facility faced challenges in:

Manual, time-consuming reporting on admissions and billing.

Limited visibility into department-wise revenue & patient volume.

Difficulty tracking readmission rates and average length of stay.

🏆 Objectives

Build a comprehensive hospital performance dashboard.

Track patient admissions, demographics, and conditions.

Monitor total cost, average cost, and high-cost cases.

Provide time-based insights (2021–2024) for trend analysis.

⚙️ Approach

1. SQL Data Preparation

Removed duplicates and standardized medical condition names.

Filled missing charges with average imputation ($25.5K).

Normalized patient demographic attributes (Age Groups, Gender).

2. Power BI Modeling & DAX

KPIs:

Patients: 36,794

Hospitals Covered: 27,600

Doctors Tracked: 28,165

Average Length of Stay (LOS): 15.5 days

Total Cost: $940M

Highest Cost (Single Patient): $52.8K

Average Cost per Patient: $25.5K

Created measures for cost vs length of stay, readmission risk, and spending trends.

Built star schema with Patients, Admissions, Billing, and Medical Conditions.

3. Dashboard Features

📊 Admissions Overview – Monthly & yearly patient trends.

👥 Demographics Analysis – Gender (Female: 50.01%, Male: 49.99%) & Age groups (Adults: 30.83%, Middle Age: 29.4%).

💰 Financial Overview – Monthly spending ($60–100M range).

⚠️ High-Cost Patient List – Top cases exceeding $52K.

🏥 Medical Condition Insights – Diabetes, Hypertension, Cancer, Asthma breakdown.

📊 Key Results

Total 36,794 patients analyzed (2021–2024).

Identified high-cost conditions (Diabetes & Cancer most expensive).

Highlighted average LOS of 15.5 days with outliers linked to chronic conditions.

Automated reporting → reduced manual report generation time by ~70%.

✅ Business Impact

Enabled real-time hospital & cost monitoring.

Helped management target high-risk, high-cost conditions for intervention.

Improved budget allocation and patient care efficiency.
