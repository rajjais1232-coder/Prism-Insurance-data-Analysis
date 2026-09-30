🛡️ PRISM Insurance Data Analysis Dashboard

An interactive Power BI Insurance Analytics Dashboard developed for
PRISM Insurance Pvt. Ltd. to analyze policy performance, premium
revenue, coverage, claims, customer demographics, and policy activity.

The project transforms raw insurance records into an interactive
business intelligence dashboard using Power BI, Power Query, DAX, data
modeling, and data visualization.

Project type: Portfolio / analytical project
Data: Insurance dataset used for analysis and dashboard
development

📌 Project Overview

Insurance organizations generate large amounts of policy and claims
data. Without an interactive analytical view, it can be difficult to
understand premium performance, policy activity, claim behavior, and
customer segments.

The PRISM Insurance dashboard provides a centralized view of these areas
through KPI cards, charts, filters, and a summary matrix.

Main Objectives

Analyze total premium, coverage, and claim amounts.

Compare premium performance across policy types.

Monitor active and inactive policies.

Analyze claims by claim status.

Understand claim amounts across customer age groups.

Compare claim status across different policy types.

Provide interactive filtering for policy, claim, and customer
records.

Convert raw insurance data into decision-support insights.

🎯 Business Problem

The objective is to help insurance stakeholders answer questions such
as:

How much premium has been generated?

What is the total coverage amount?

What is the total claim amount?

Which policy type generates the highest premium?

What proportion of policies are active or inactive?

How are claims distributed between pending, rejected, and settled?

Which age groups account for higher claim amounts?

Which policy types have more pending or rejected claims?

How can policy and claims performance be monitored from one
dashboard?

📊 Key KPIs

KPI                                    Value

Total Premium Amount               5.98M
Total Coverage Amount            600.55M
Total Claim Amount                16.91M
Active Policies           5.82K (58.13%)
Inactive Policies         4.19K (41.87%)

These KPIs provide a high-level overview of the insurance portfolio and
claims position.

📈 Dashboard Analysis

1. Premium Amount by Policy Type

The dashboard compares premium amounts across:

Travel

Health

Auto

Life

Home

Observed pattern:

Travel: approximately 2.5M

Health: approximately 1.2M

Auto: approximately 1.0M

Life: approximately 0.7M

Home: approximately 0.6M

Travel is the largest premium category in this dataset.

2. Active vs Inactive Policies

The dashboard tracks policy activity:

Active: 5.82K --- 58.13%

Inactive: 4.19K --- 41.87%

This view can help stakeholders monitor the current policy base and
investigate policy inactivity or renewal opportunities.

3. Claims by Status

Claims are categorized into:

Pending

Rejected

Settled

The dashboard provides a visual comparison of claim volumes across these
statuses.

This can help identify areas that may require further operational
investigation, particularly where pending or rejected claims are
concentrated.

4. Claim Amount by Age Group

Claim amounts are analyzed across age groups such as:

Young Adult

Adult

Elder

The dashboard helps identify which customer age segments account for
higher claim amounts.

5. Policy Type & Claim Status

A matrix provides a detailed breakdown of policy types against:

Pending claims

Rejected claims

Settled claims

This allows users to identify policy categories with different
claim-status patterns.

🔍 Interactive Filters

The dashboard includes slicers/filters for:

Policy Number

Claim Number

Customer ID

Users can select individual records and interact with the visuals to
investigate specific policies, claims, or customers.

🛠️ Tools & Technologies

Technology               Purpose

Power BI Desktop     Dashboard and report development
Power Query          Data cleaning and transformation
DAX                  Measures and analytical calculations
Excel / CSV          Source data
Data Modeling        Organizing insurance data for analysis
Data Visualization   Interactive charts and KPI reporting

🧹 Data Preparation

The raw insurance dataset contains fields such as:

Policy Number

Customer ID

Claim Number

Age

Gender

Premium Amount

Policy Start Date

Policy End Date

Policy Type

Claim Status

Claim Date

Claim Amount

Age Group

Active / Inactive Status

The data was prepared for analysis through data profiling, cleaning,
transformation, and creation of analytical categories.

🧮 DAX & Analytical Measures

DAX was used to create analytical measures for the dashboard.

Total Premium

Total Premium = SUM(Insurance[PremiumAmount])

Total Coverage

Total Coverage = SUM(Insurance[CoverageAmount])

Total Claim Amount

Total Claim Amount = SUM(Insurance[ClaimAmount])

Active Policies

Active Policies =
CALCULATE(
    COUNTROWS(Insurance),
    Insurance[Active/Inactive] = "Active"
)

Inactive Policies

Inactive Policies =
CALCULATE(
    COUNTROWS(Insurance),
    Insurance[Active/Inactive] = "Inactive"
)

The exact DAX formulas may vary depending on the final Power BI data
model and column names.

🔄 Project Workflow

Raw Insurance Data
        ↓
Data Profiling
        ↓
Data Cleaning
        ↓
Power Query Transformation
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
KPI Development
        ↓
Interactive Visualizations
        ↓
Business Analysis
        ↓
Dashboard

💡 Key Business Observations

Based on the dashboard:

1. Travel has the highest premium contribution

Travel insurance contributes approximately 2.5M in premium amount,
making it the largest premium category in the displayed data.

2. More policies are active than inactive

Approximately 58.13% of policies are active, compared with
41.87% inactive.

3. Claims can be analyzed from multiple dimensions

The dashboard combines claim status, policy type, and age group to
provide a more detailed view of claim behavior.

4. Age-group analysis provides segmentation

Claim amounts vary across Young Adult, Adult, and Elder segments,
allowing analysts to identify segments requiring additional
investigation.

5. Policy-level filtering enables detailed analysis

Policy Number, Claim Number, and Customer ID filters allow users to move
from an overall portfolio view to individual records.

These observations describe patterns visible in the dashboard. They
should not be treated as causal conclusions without additional
statistical or business validation.

📋 Dashboard Components

The dashboard contains:

KPI Cards

Premium by Policy Type chart

Active vs Inactive Policy visualization

Claim Status analysis

Claim Amount by Age Group

Policy Type vs Claim Status matrix

Policy Number slicer

Claim Number slicer

Customer ID slicer

📂 Suggested Repository Structure

PRISM-Insurance-Data-Analysis/
│
├── README.md
│
├── PRISM Insurance Dashboard.pbix
│
├── Data/
│   └── insurance_data.xlsx
│
├── Screenshots/
│   └── prism-insurance-dashboard.png
│
└── Documentation/
    └── project-notes.md

🚀 How to Use

Install Microsoft Power BI Desktop.

Download or clone this repository.

Open the .pbix file in Power BI Desktop.

If required, update the source-data path.

Refresh the dataset.

Use the slicers to filter the dashboard.

Interact with charts to explore policy and claims performance.

🎓 Skills Demonstrated

This project demonstrates practical skills in:

Data Analysis

Business Intelligence

Power BI

Power Query

DAX

Data Cleaning

Data Transformation

Data Modeling

KPI Development

Interactive Dashboard Development

Data Visualization

Business Insight Generation

📸 Dashboard Preview

Add your dashboard screenshot here:

![PRISM Insurance Dashboard](Screenshots/prism-insurance-dashboard.png)

📌 Project Limitations

The dashboard represents an analytical portfolio project.

Business recommendations should be validated against actual company
processes and additional data.

Dashboard observations show relationships and patterns in the
available dataset; they do not establish causation.

Actual results may change when the underlying dataset is updated.

👨‍💻 Author

Raj Jaiswal

B.Tech -- Information Technology
Government Engineering College, Bilaspur

Connect With Me

LinkedIn: https://www.linkedin.com/in/raj-jaiswal-644782336

GitHub: https://github.com/rajjais1232-coder

Portfolio:
https://portfolio-website-8p9oi8tbn-rajjais1232-coders-projects.vercel.app

⭐ Project Purpose

This project is part of my Data Analytics and Business Intelligence
portfolio and demonstrates how Power BI, DAX, Power Query, and data
visualization can be used to transform insurance data into an
interactive analytical dashboard.
