# Bank Loan Performance Dashboard | Business Requirement Document (BRD)

## Introduction
Banks manage large portfolios of loans that directly impact profitability, liquidity, and risk exposure. Without a centralized and well-structured reporting system, it becomes difficult to monitor lending performance, assess portfolio quality, and identify emerging risks in a timely manner.

The key business challenge addressed in this project is the **lack of a consolidated analytical view of loan performance**, including application trends, funded amounts, repayment behavior, and loan quality. Decision-makers require clear visibility into how loans perform over time, how borrower characteristics influence outcomes, and how much risk exists within the portfolio.
This project aims to solve that problem by developing a **Bank Loan Performance Dashboard** that enables stakeholders to:
- Track loan demand and growth trends
- Monitor cash inflows and outflows
- Evaluate portfolio health using Good vs Bad Loan metrics
- Identify risk patterns across borrower and loan attributes
- Support data-driven lending and portfolio management decisions
  
## Analytical Objectives
The analysis focuses on answering the following business questions:
- How many loans are being issued, and how is loan demand changing over time?
- How much capital is being deployed, and how much is being recovered through repayments?
- What proportion of loans are performing well versus defaulting?
- Which borrower characteristics (employment length, home ownership, loan purpose) are associated with higher loan activity or risk?
- Are there observable trends or seasonal patterns in lending behavior?
  
## Key Performance Indicators (KPIs)
To address the business problem, the following KPIs were defined and calculated:
### Loan Volume & Growth
- Total Loan Applications
- Month-to-Date (MTD) Loan Applications
- Month-over-Month (MoM) Loan Application Change
### Funding & Cash Flow
- Total Funded Amount
- MTD Funded Amount
- Total Amount Received
- MTD Amount Received
### Risk & Portfolio Quality
- **Good Loan Percentage:** Loans with status *Fully Paid* or *Current*
- **Bad Loan Percentage:** Loans with status *Charged Off*
### Borrower Financial Health
- Average Interest Rate
- Average Debt-to-Income Ratio (DTI)
  
These KPIs provide a balanced view of growth, profitability, and risk.

## Good Loan vs Bad Loan Framework
To evaluate portfolio quality, loans are categorized as follows:
- **Good Loans:** Loans that are either fully repaid or currently active without default.
- **Bad Loans:** Loans that have been charged off due to non-repayment.
  
This classification simplifies credit risk assessment and allows stakeholders to quickly evaluate overall portfolio health.

## Dashboard Structure & Charts
The analysis is presented across two dashboards, each designed to serve a specific analytical purpose.
### DASHBOARD 1: Summary Dashboard
#### Objective
Provide an at-a-glance view of overall lending performance and portfolio health.
#### Key Elements
KPI cards displaying:
 - Total Loan Applications
- Total Funded Amount
 - Total Amount Received
  - Good Loan %
  - Bad Loan %
#### Value to Business
This dashboard allows executives and managers to quickly assess performance without drilling into details.
### DASHBOARD 2: Overview Dashboard (Trends & Distribution)
#### 1. Monthly Loan Trends (Line Chart)
**X-axis:** Issue Date (Month & Year)

**Metrics:**
  - Total Loan Applications
  - Total Funded Amount
  - Total Amount Received
    
**Purpose:**

Identifies growth patterns, seasonality, and long-term trends in lending activity.

#### 2. Regional Loan Analysis (Map)

**Dimension:** 
State

**Metrics:**
  - Loan Applications
  - Funded Amount
  - Amount Received

**Purpose:**

Highlights geographic concentration and regional disparities in lending.

#### 3. Loan Term Distribution (Donut Chart)

**Segments:** 

36 months vs 60 months

**Metrics:**

Loan count or funded amount

**Purpose:**

Shows borrower preference for short-term vs long-term loans.

#### 4. Employment Length Analysis (Bar Chart)

**X-axis:** Employment Length (Years or Bands)

**Y-axis:** Loan Applications / Funded Amount

**Purpose:**

Examines how employment stability correlates with loan activity.

#### 5. Loan Purpose Breakdown (Bar Chart)

**X-axis:** Loan Purpose

**Y-axis:** Loan Applications or Funded Amount

**Purpose:**

Identifies the most common reasons borrowers seek loans.

#### 6. Home Ownership Analysis (Bar Chart)

**Hierarchy:** Own, Rent, Mortgage

**Metric:** Loan Applications or Funded Amount

**Purpose:**

Provides insight into borrower housing status and its relationship to lending.

## Business Value of the Dashboard
This dashboard enables stakeholders to:
- Monitor lending performance 
- Identify rising default risk 
- Understand borrower behavior patterns
- Support strategic decisions related to loan approvals, pricing, and portfolio management
  
## Conclusion
By combining clean data, well-defined KPIs, and intuitive visualizations, this project transforms raw loan data into actionable business insights. The dashboard provides a comprehensive view of loan performance, risk exposure, and borrower characteristics, enabling informed and data-driven decision-making.

