 Loan Default Analysis Dashboard – Power BI

 
📌 Project Overview

The Loan Default Analysis Dashboard is an interactive Power BI solution designed to analyze loan performance, applicant demographics, and financial risk metrics. The dashboard enables financial institutions to identify default patterns, understand borrower characteristics, and monitor lending performance through dynamic visualizations and KPIs.

The report is divided into three analytical pages, each focusing on a different aspect of the lending business:

Loan Default Overview
Applicant Demographics & Financial Profile
Financial Risk Metrics
🎯 Business Problem

Financial institutions process thousands of loan applications every year. Understanding:

Which customers are more likely to default
Which loan categories contribute the highest lending amount
How employment, income, education, and credit score affect default risk

is essential for minimizing financial losses and improving lending decisions.

This dashboard helps stakeholders make data-driven decisions by providing interactive insights into loan performance and borrower behavior.

Dashboard Pages

1️⃣ Loan Default Overview

<img width="1918" height="990" alt="image" src="https://github.com/user-attachments/assets/bedfada8-767a-40aa-abbb-9b1cd7feeac9" />

Purpose

Provides an executive summary of loan performance and default trends.

Visualizations
Loan Amount by Purpose
Average Income by Employment Type
Default Rate (%) by Employment Type
Average Loan Amount by Age Group
Default Rate Trend by Year
Key Insights
Compare loan distribution across different purposes.
Identify employment categories with higher default rates.
Analyze average applicant income.
Monitor yearly default trends.
Compare loan amounts across different age groups.
2️⃣ Applicant Demographics & Financial Profile

<img width="1919" height="983" alt="image" src="https://github.com/user-attachments/assets/e811bd14-11f3-4ae5-b3b9-ae84f2d92ba5" />

Purpose

Analyzes applicant characteristics and their relationship with loan amount.

Visualizations
Median Loan Amount by Credit Score Bins
Average High Credit Loan Amount by Age Group & Marital Status
Total Loan by Credit Score Bins
Total Loan by Mortgage & Dependents
Number of Loans by Education Type
Key Insights
Study how credit score affects loan approval amount.
Compare borrowers across age groups.
Understand the impact of marital status.
Analyze education-wise loan distribution.
Evaluate mortgage ownership and dependent information.

3️⃣ Financial Risk Metrics

<img width="1919" height="980" alt="image" src="https://github.com/user-attachments/assets/46aae929-c80f-4571-8332-c089ad8375bd" />

Purpose

Measures lending performance over time using advanced financial KPIs.

Visualizations
Year-over-Year (YOY) Loan Amount Change
Year-over-Year Default Loan Change
YTD Loan Amount by Credit Score & Marital Status
Income Bucket vs Employment Type (Decomposition Tree)
Key Insights
Track yearly growth in loan amounts.
Monitor yearly changes in defaulted loans.
Analyze YTD lending performance.
Drill down loan distribution by income and employment.
📊 KPIs Covered
Total Loan Amount
Average Loan Amount
Default Rate (%)
Average Applicant Income
Number of Loans
Median Loan Amount
YOY Loan Growth
YOY Default Growth
YTD Loan Amount
Loan Distribution by Credit Score
Loan Distribution by Education
Loan Distribution by Employment Type
📈 Dashboard Features
Interactive Filters
Cross Filtering
Drill-down Analysis
Dynamic Measures using DAX
Responsive Dashboard Layout
Year-over-Year Analysis
Year-to-Date (YTD) Analysis
Decomposition Tree Analysis
🛠 Tools & Technologies
Technology	Usage
Power BI Desktop	Dashboard Development
Power Query	Data Cleaning & Transformation
DAX	Measures & KPIs
Data Modeling	Relationship Management
Excel/CSV	Data Source
📚 DAX Concepts Used
CALCULATE()
SUM()
AVERAGE()
MEDIAN()
DIVIDE()
FILTER()
YEAR()
YTD Calculations
YOY Calculations
Context Transition
Time Intelligence Functions
📂 Dashboard Structure
Loan Default Analysis
│
├── Loan Default Overview
│     ├── Loan Amount by Purpose
│     ├── Default Rate by Employment
│     ├── Income Analysis
│     └── Default Trend
│
├── Applicant Demographics
│     ├── Credit Score Analysis
│     ├── Education Analysis
│     ├── Marital Status
│     └── Mortgage Analysis
│
└── Financial Risk Metrics
      ├── YOY Loan Growth
      ├── YOY Default Growth
      ├── YTD Loan Amount
      └── Decomposition Tree
📸 Dashboard Preview
Loan Default Overview

Add Screenshot Here

Applicant Demographics & Financial Profile

Add Screenshot Here

Financial Risk Metrics

Add Screenshot Here

💡 Business Value

This dashboard enables financial analysts and lending teams to:

Identify high-risk borrower segments.
Monitor loan portfolio performance.
Improve credit risk assessment.
Analyze borrower demographics.
Support strategic lending decisions.
Reduce potential loan defaults through data-driven insights.
🚀 Future Enhancements
Predictive Loan Default Model using Machine Learning
Customer Risk Scoring
Real-time Data Refresh
Geographic Loan Analysis
Loan Recovery Tracking
AI-powered Key Influencers Visual
📁 Repository Structure
Loan-Default-Analysis-Dashboard/
│
├── Dashboard.pbix
├── Dataset/
│   └── Loan_Default.csv
├── Images/
│   ├── Loan_Default_Overview.png
│   ├── Applicant_Demographics.png
│   └── Financial_Risk_Metrics.png
├── README.md
└── LICENSE
⭐ Skills Demonstrated
Power BI Dashboard Development
Data Modeling
Power Query (ETL)
DAX Calculations
Time Intelligence
Financial Analytics
Risk Analysis
Data Visualization
Business Intelligence
Interactive Reporting
