# Bank Loan Performance Dashboard | Data Dictionary

## Introduction
This data dictionary provides a detailed description of all fields used in the bank loan dataset for this project. It explains the meaning, format, and purpose of each column to ensure clarity, consistency, and correct interpretation during analysis.

The dataset represents a simulated loan portfolio and is used to support data cleaning, exploratory analysis, KPI calculation, and dashboard development. This document serves as a reference for understanding the dataset structure and the business context behind each field.

- id: Unique identifier for each loan record
- member_id: Unique identifier for the customer/applicant
- address_state: State where the applicant resides
- application_type: Indicates whether the loan application is individual or joint
- emp_title: Job title of the applicant
- emp_length: Length of employment of the applicant
- home_ownership: Applicant’s home ownership status (e.g., Rent, Own, Mortgage)
- grade: Assigned loan grade representing overall credit risk
- sub_grade: More granular risk classification within the loan grade
- purpose: Reason for the loan request
- issue_date: Date the loan was issued
- term_months: Loan duration in months
- loan_amount: Amount of money requested/borrowed
- int_rate: Interest rate applied to the loan
- installment: Monthly payment amount
- annual_income: Applicant’s reported annual income
- dti: Debt-to-income ratio of the applicant
- total_acc: Total number of credit accounts held by the applicant
- loan_status: Current status of the loan (e.g., Fully Paid, Charged Off, Current)
- goodloan_v_badloan: Classification indicating good or bad loan outcome
- last_payment_date: Date of the most recent loan payment
- next_payment_date: Scheduled date for the next loan payment
- last_credit_pull_date: Most recent date the applicant’s credit report was accessed
- total_payment: Total amount paid on the loan to date

## Conclusion
Only columns relevant to analysis, KPIs, and dashboards are documented. Derived metrics are calculated using Excel pivot tables and formulas.

