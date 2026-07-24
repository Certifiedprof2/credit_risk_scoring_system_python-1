💳 PrimeCredit FinTech: Credit Risk Scoring Model

📌 Project Overview
Whenever digital lending platforms (like Opay, PalmPay, Carbon, or commercial banks) evaluate a loan applicant, they must answer one critical question: "Is this applicant low-risk or high-risk?"

As a Junior Python Developer at PrimeCredit FinTech Ltd., I built this rule-based Credit Risk Scoring System. Designed using core Python fundamentals (Lessons 1–5), this program evaluates an applicant's financial indicators—such as Debt-to-Income (DTI) ratio, total loan exposure, income requirements, and credit history—to automate initial lending decisions and flag high-risk applications for manual review.

🎯 Key Business Logic & Features
Debt-to-Income (DTI) Calculation: Measures what percentage of the applicant's income goes toward debt servicing.

Dynamic Balance Updates: Updates active loan balances using compound assignment operators after recent repayments.

Total Exposure Assessment: Calculates total potential liability (Existing Balance + Requested Amount).

Multi-Condition Eligibility Checks: Evaluates income limits, minimum credit score thresholds, and employment verification status using Python logical (AND, OR) and comparison operators.

Automated Risk Flagging: Determines whether an application can be auto-approved or requires manual review by the Risk Management Team.

🛠️ Python Skills Applied
Data Types & Variables: Strings, Integers, Floats, and Booleans.

Arithmetic Operations: Percentages, totals, and subtraction updates.

Assignment & Comparison Operators: >= evaluation and -= balance updates.


Logical Operators: Combining rules with and / or conditions.
============================================================
             CREDIT RISK SCORING REPORT
============================================================

Applicant Name: Mary Okoro

Monthly Income: ₦450,000
Monthly Loan Repayment: ₦120,000
Debt-to-Income Ratio: 26.67%

Updated Existing Loan Balance: ₦800,000
Requested Loan Amount: ₦1,500,000
Total Loan Exposure: ₦2,300,000

Credit Score: 720 (Minimum Required: 700)
Employment Verified: True

------------------------------------------------------------
ELIGIBILITY VERIFICATION
------------------------------------------------------------
Income Requirement Met: True
Credit Score Requirement Met: True
Basic Credit Eligibility: True
Manual Review Required: False
============================================================

Formatted Reporting: Clean string formatting for financial metrics.
