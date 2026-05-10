# Bank Loan Performance Dashboard | Domain Knowledge

## Introduction

Bank loans are a fundamental financial product that enables individuals and businesses to meet personal, commercial, and operational needs. From the lender’s perspective, loans represent both an income-generating asset and a source of risk. As a result, banks rely heavily on loan data to evaluate borrower credit worthiness, monitor portfolio performance, and manage default risk.
This project analyses loan data to understand lending patterns, portfolio quality, and repayment performance using structured KPIs and visual dashboards.

## Sources of Loan Data
Banks collect and maintain loan-related data from multiple operational and external sources, including:
- **Loan Applications:** Information provided by borrowers during the application process, such as income, employment details, loan purpose, and requested amount.
- **Credit Records:** Credit history and repayment behavior obtained from credit bureaus to assess borrower risk.
- **Internal Transaction Systems:** Records of loan disbursement, repayment schedules, outstanding balances, and loan status updates.
- **Digital Channels:** Online portals and banking platforms where borrowers apply for loans, make payments, or manage accounts.
- **Third-Party Services:** External verification sources used to validate income, employment, or identity.
Each row in the dataset represents a **single loan issued to a borrower,** along with its associated financial and status attributes.

## Loan Lifecycle Overview
The loan lifecycle typically follows a structured process:
- **Loan Application:** The borrower submits a loan request, providing personal, financial, and employment information.
-  **Application Review & Verification:** The lender verifies identity, income, employment status, and reviews credit history.
- **Risk Assessment:** Borrower risk is assessed using metrics such as credit history, debt-to-income ratio (DTI), and employment stability.
- **Loan Decision:** Based on risk evaluation, the loan is approved or rejected. Approved loans are assigned terms such as interest rate, loan amount, and duration.
- **Loan Disbursement:** Funds are released to the borrower according to agreed terms.
- **Repayment & Monitoring:** Borrowers make scheduled repayments. The lender continuously monitors performance and updates loan status.
- **Loan Closure or Default:** Loans are either fully repaid or classified as defaulted (charged off).
   
## Purpose of Loan Data Analysis
Loan data analysis supports several critical banking functions:
- **Credit Risk Management:** Identifying high-risk borrowers and monitoring default rates.
- **Portfolio Performance Monitoring:** Evaluating how loans perform over time in terms of repayments and status.
- **Operational Decision-Making:** Supporting loan approval, pricing, and term decisions.
- **Profitability Assessment:** Comparing funded amounts with repayments received.
- **Trend Analysis:** Understanding monthly and yearly changes in loan demand and funding.
- **Regulatory & Reporting Support:** Ensuring transparency and accountability in lending operations.
  
## Key Performance Indicators (KPIs)

### Loan Volume & Growth KPIs
- **Total Loan Applications:** Total number of loans issued.
- **Month-to-Date (MTD) Loan Applications:** Loans issued from the beginning of the current month to date.
- **Month-over-Month (MoM) Application Change:** Percentage change in loan applications compared to the previous month.
- **Total Funded Amount:** Total monetary value of loans disbursed.
- **MTD Funded Amount:** Loans funded within the current month.
  
### Repayment & Cash Flow KPIs
- **Total Amount Received:** Total repayments collected from borrowers.
- **Repayment Trend:** Monthly analysis of amounts received over time.
  
### Loan Quality & Risk KPIs
**Good Loan Percentage:**
 Percentage of loans classified as:
- Fully Paid
- Current
  
**Bad Loan Percentage:**
 Percentage of loans classified as:
- Charged Off
  
These metrics are used to assess overall portfolio health and credit risk exposure.

## Key Loan Metrics Explained
- **Loan Amount:** The principal amount funded to the borrower.
- **Interest Rate:** The cost of borrowing expressed as a percentage.
- **Term (Months):** Duration of the loan, typically 36 or 60 months.
- **Installment:** Fixed monthly repayment amount.
- **Annual Income:** Borrower’s reported yearly income.
- **Debt-to-Income Ratio (DTI):** Proportion of a borrower’s income used to service debt.
- **Employment Length:** Number of years the borrower has been employed.
- **Loan Status:** Indicates whether a loan is current, fully paid, or charged off.
  
## Good Loan vs Bad Loan Classification
To assess portfolio quality, loans are grouped into performance categories:

- **Good Loans:** Loans that are either fully repaid or currently active without default.
- **Bad Loans:** Loans that have been charged off due to non-repayment.

This classification provides a simplified but effective measure of credit risk.

## Assumptions & Limitations

- Employment length values were normalized and capped at 10 years based on source definitions.
- Missing employee titles were labeled as “Unknown” to preserve record completeness.
- Outliers were retained to reflect real-world variability unless clearly invalid.
- Analysis is based on historical data and does not predict future loan outcomes.
  
## Conclusion
This domain knowledge framework provides the business context necessary to interpret the loan dataset, understand KPI definitions, and evaluate insights derived from the dashboard. By combining financial metrics, borrower attributes, and loan performance indicators, the analysis offers a comprehensive view of portfolio health and lending behavior.




