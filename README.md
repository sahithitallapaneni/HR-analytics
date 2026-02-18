HR Intelligence & Predictive Attrition Dashboard
Strategic People Analytics using Power BI, SQL, and Python
📌 Project Overview
This project transforms raw HR data into a strategic tool for leadership to understand workforce health. Beyond standard descriptive reporting (Headcount, Diversity), this dashboard utilizes Predictive Analytics to identify high-risk flight segments and the root causes of employee turnover.

By analyzing the IBM HR Analytics Dataset, this solution provides actionable insights to reduce regrettable attrition and optimize recruitment costs.

🚀 Key Features & Analytics
Executive Summary: High-level KPIs including Attrition Rate, Avg Tenure, and Monthly Income distribution.

Predictive Attrition Modeling: Integration of a Logistic Regression model (via Python script) to calculate the "Probability of Exit" for current staff.

Root Cause Analysis: Utilization of Power BI’s AI Key Influencers visual to determine how factors like Overtime, JobLevel, and StockOptions impact retention.

Demographic Deep-Dives: Interactive slicing by Department, Education Field, and Distance from Home.

🛠️ Tech Stack & Skills
Data Cleaning: Power Query (M Language) for ETL and data normalization.

Modeling: Star Schema design with a centralized Fact table and optimized Dimension tables.

Advanced DAX:

Attrition Rate % = DIVIDE(SUM('HR_Data'[Attrition_Count]), [Total Employees], 0)

Year-over-Year (YoY) Headcount Growth

Average Salary Benchmarking

Language Integration: Python for advanced statistical distribution and outlier detection.

Visualization: Power BI Desktop (Bookmarks, Tooltips, and Drill-throughs for UX).

📊 Business Insights Uncovered
The "Overtime" Factor: Employees working overtime are 3x more likely to leave the company regardless of salary bracket.

Commute Correlation: Attrition rates spike by 12% for employees living more than 15 miles from the office.

Role Specifics: Sales Representatives show the highest volatility, suggesting a need for revised commission structures or onboarding.

📁 Repository Structure
Plaintext
├── Data/                   # Raw IBM HR Dataset (CSV)
├── Scripts/                # Python scripts used for data enrichment
├── Dashboard/              # .pbix Power BI File
├── Documentation/          # Data Dictionary and DAX Measure list
└── README.md
