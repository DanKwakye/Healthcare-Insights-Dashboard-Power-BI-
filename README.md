**🏥 Healthcare Insights Dashboard (Power BI)**

This repository presents an interactive Power BI dashboard project that delivers actionable insights into healthcare operations across multiple hospitals. The project is broken down into three core sections:

Patient Demographics

Key Trends

Treatment & Cost

**📊 1. Patient Demographics**

Overview:
This section focuses on understanding the profile of patients diagnosed with Asthma in March 2020, providing demographic, clinical, and institutional breakdowns.

Key Highlights:
Metric	Value	Change vs 2019
Admitted Patients	59	↓ -88.8%
Rooms/Bedspace	54	↓ -81.8%
Average Billing Amount	23,949.82	↓ -8.4%
Doctors	59	↓ -88.6%
Avg LOS (Days)	15.39	↓ -1.9%
Average Age	51.58	↓ -1.1%

Test Results Distribution:
Normal: 0%

Inconclusive: 0%

Abnormal: 100%

Age & Gender Distribution:
Most affected age groups: 35–49 yrs and 65–79 yrs

Females represented a higher patient count across most age groups.

Top Conditions by Hospital:
Hospital	Asthma Cases	Total Patients
Johns Hopkins Hospital	16	196
UCLA Medical Center	12	50
Cleveland Clinic	5	42

📈 2. Key Trends
Overview:
This view emphasizes overall hospital performance by analyzing patient volume, day-type admissions, and length of stay (LOS) trends.

General Stats:
Metric	Value
Admitted Patients	55,500
Rooms/Bedspace	400
Avg Billing Amount	25,539.32
Doctors	40,341
Avg LOS (Days)	15.51
Average Age	51.54

Admission Trends:
Weekday vs Weekend:

Weekday Admissions: 40K (71.49%)

Weekend Admissions: 16K (28.51%)

Length of Stay (LOS):

Extended Stay (15+ days): 30K patients (53.18%)

Short Stay (1–3 days): 8K (9.91%)

Monthly Admission Patterns:
Peak Month: July (4,919 patients)

Lowest Month: February (4,255 patients)

Admissions are consistent across weekdays, with Friday and Saturday showing slightly higher volumes.

Monthly Billing Trend by Admission Type:
Billing fluctuates across the year, with noticeable peaks in June and October.

Elective admissions showed the highest variability in billing.

💊 3. Treatment & Cost
Overview:
This section breaks down treatment costs by Length of Stay (LOS), Admission Type, Hospital, and Medical Condition, along with detailed drug usage analytics.

Billing by LOS Bucket & Admission Type:
LOS Bucket	Highest Contributor	Total Billing
Extended Stay	All Admission Types	~0.3B
Long Stay	Elective	~0.1B
Moderate/Short	Urgent	Low Impact

Top Hospitals by Total Billing:
Hospital	Dominant Type	Approx Billing
Houston Methodist	Elective	~200M
Johns Hopkins	Emergency	~190M
UCLA	Mixed	~100M

Drug Usage by Condition (Top 3 Conditions):
Condition	Top Drug	Total Prescriptions
Hypertension	Aspirin	13,875
Diabetes	Ibuprofen	13,775
Obesity	Lipitor	12,765

Asthma had the lowest prescription volume among all listed conditions (3,885).

📌 Insights & Recommendations
Chronic Conditions such as hypertension, diabetes, and obesity dominate treatment cost and medication use.

Extended hospital stays are the largest drivers of revenue across all admission types.

Hospitals like Houston Methodist and Johns Hopkins are critical contributors to both patient volume and billing.

Significant year-over-year drops in patient counts and room usage suggest possible impacts from external factors (e.g., pandemics).

📂 Project Features
🔄 Dynamic filters by Year, Medical Condition, Hospital, and Admission Type

📊 Multi-view reports: Demographics, Key Trends, Treatment & Cost

📉 Comparative analysis vs previous year (2019)

💉 Drug impact matrix for condition-specific prescriptions

📅 Monthly, day-wise, and LOS-wise breakdown of hospital activity

🛠️ Technologies Used
Power BI Desktop

DAX

Data Modeling

Interactive Visuals & Filters

Dynamic KPI Cards and Matrix Tables

📎 License
This project is for educational and demonstration purposes. For commercial use or dataset access, please contact the repository owner.
