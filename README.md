Overview

This repository contains the Excel-based interactive Loan Data Analysis Dashboard developed for The Data Immersed (TDI). The dashboard provides actionable insights into loan performance, borrower demographics, and risk management to help TDI make data-driven decisions.

Project Scope

Objective

To create an interactive loan data analysis dashboard that:

Visualizes key loan metrics and trends.

Identifies risk patterns and borrower profiles.

Provides actionable recommendations for optimizing loan processes and profitability.

Key Deliverables

Interactive Excel Dashboard: Highlights metrics such as loan disbursement, repayments, and customer demographics.

Insights:

Loan trends across regions and time.

Borrower demographics and loan purposes.

Risk factors including default rates.

Recommendations: Strategies to improve loan approval rates and mitigate risks.

Features

Dashboard Highlights

Overview Section:

KPI cards for total loans disbursed and repayments.

Donut chart for percentage of loans charged off.

Bar chart for top loan purposes by value.

Loan Trends Analysis:

Line chart visualizing monthly loan request trends.

Seasonal spike identification.

Borrower Demographics:

Geographic loan distribution.

Loan amounts segmented by income and employment length (histograms).

Loan Risk Insights:

Default rates segmented by credit score, loan grade, and purpose.

Interactive slicers for filtering by grade, region, and loan status.

Key Interactive Features

Filters:

Slicers for loan purpose, region, grade, and status.

Drop-down menus for time-period selection.

Visualizations:

Bar charts for regional loan requests and approvals.

Line graphs for repayment trends.

Pie charts for loan purposes.

Data Overview

The Excel file contains:

Dataset Sheet: Loan data for analysis.

Data Dictionary Sheet: Column descriptions for clarity.

Key Columns:

id: Unique loan identifier.

address_state: Borrower’s state.

application_type: Loan applicant type.

emp_length: Employment duration.

emp_title: Job title.

grade & sub_grade: Credit grading.

issue_date: Loan issuance date.

annual_income: Borrower’s income.

dti: Debt-to-income ratio.

loan_amount: Loan principal.

total_payment: Total loan payments made.

Data Cleaning and Transformation

Cleaning Steps:

Data Import and Standardization:

Fixed date formats.

Unified currency formatting.

Missing Values:

Median imputation for critical numeric columns.

Excluded records with incomplete loan purposes or regions.

Duplicate Removal:

Removed 16 duplicate rows based on unique IDs.

Categorical Standardization:

Standardized state abbreviations.

New Columns Added:

Approval Status (Approved/Rejected).

Key Insights

Loan Performance:

Total loans disbursed: $436M.

Total repayments: $473M.

Loan Default:

14% of loans defaulted, primarily due to debt consolidation.

Borrower Demographics:

California leads with 4,104 requests.

Tennessee has the lowest with 4 requests.

Borrowers with over 10 years of employment request the most loans.

Loan Trends:

Steady increase in loan requests; peak in December 2021.

Recommendations

Address Loan Defaults:

Stricter creditworthiness checks for high-risk loans.

Financial literacy programs for managing consolidated debt.

Diversify Loan Purposes:

Reduce reliance on debt consolidation loans.

Promote other loan types like business or education loans.

Optimize Loan Grading:

Assess high approval rates for Grade G loans.

Adjust criteria to align with risk goals.

Regional Expansion:

Target underserved regions like Tennessee.

Tailor marketing and risk strategies for high-demand areas.

Seasonal Trends:

Prepare for December loan request spikes.

Offer promotional interest rates during peak times.

Conclusion

The Loan Data Analysis Dashboard provides actionable insights to enhance TDI’s loan portfolio management. By addressing identified risks and optimizing processes, TDI can achieve sustainable growth and profitability.
