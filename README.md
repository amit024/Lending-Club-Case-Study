# Lending Club Project
> Lending Club, a leading consumer finance marketplace, faces challenges in its loan approval process due to financial losses from "charged-off" loans (borrowers who default). The objective of this case study is to analyze data to identify applicants at risk of default, minimizing losses while maintaining profitability.


## Table of Contents
1. Data Understanding
Problem Statement
Objectives
Understanding the dataset
Dataset Attributes
Dataset Row Analysis
Dataset Column Analysis
Handling missing data
Handling Outliers

2. Data Cleaning and Manipulation
Loading data from loan CSV
Checking for null values in the dataset
Checking for unique values
Checking for duplicated rows in data
Dropping records
Common Functions
Data Conversion
Outlier Treatment
Imputing values in Columns

3. Data Analysis¶
Derived Columns
Univariate Analysis (including Segmented Univariate Analysis)
Bivariate Analysis

4. Multivariate Analysis



## General Information
Lending Club, a consumer finance marketplace specializing in offering a variety of loans to urban customers, faces a significant challenge in optimizing its loan approval process. The company must make sound decisions to minimize financial losses, particularly those arising from loans issued to applicants considered "risky."

The Problem of Credit Losses
Credit losses occur when borrowers fail to repay their loans or default. Borrowers classified as “Charged-Off” contribute significantly to these losses, posing a critical financial challenge for Lending Club

Objectives of the Analysis
The primary goal of this exercise is to help LendingClub reduce credit losses. The challenge stems from two key scenarios:
Potential Profit Loss: Identifying applicants who are likely to repay their loans is crucial, as these individuals generate profits for the company through interest payments. Rejecting such applicants leads to missed business opportunities.
Risk of Financial Loss: Approving loans for applicants who are unlikely to repay or are at risk of default results in substantial financial losses.
The objective is to identify applicants at risk of defaulting on loans, enabling LendingClub to minimize credit losses. This case study seeks to achieve this through Exploratory Data Analysis (EDA) using the provided dataset.

Key Goals
Understand the driving factors (driver variables) behind loan defaults.
Pinpoint variables that strongly indicate the likelihood of default.
Use insights from the analysis to strengthen LendingClub's portfolio and risk assessment strategies.
By identifying these factors, LendingClub can make data-driven decisions to manage its loan approval process more effectively and ensure a balance between minimizing risks and maximizing profits.


## Conclusions
	Implement Stricter Criteria for Grades B, C, and D: Consider implementing stricter risk assessment and underwriting criteria for applicants falling into Grades B, C, and D to minimize default risks.
	Focus on Subgrades B3, B4, and B5: Pay special attention to applicants with Subgrades B3, B4, and B5. Consider additional risk mitigation measures or offering lower loan amounts for these subgrades to reduce default rates.
	Evaluate and Limit 60-Month Loans: Evaluate the risk associated with 60-month loans. Consider limiting the maximum term or adjusting interest rates for longer-term loans to decrease the likelihood of defaults.
	Comprehensive Credit Scoring System: Develop a comprehensive credit scoring system that incorporates various risk-related attributes, as experience alone might not be sufficient to gauge creditworthiness.
	Capitalizing on Market Growth: Capitalize on the market's growth trend observed from 2007 to 2011 by maintaining a competitive edge in the industry while ensuring robust risk management practices.
	Anticipate Peak Periods: Anticipate increased loan applications during peak periods such as December and Q4. Ensure efficient processing to meet customer demands during these busy seasons.
	Careful Evaluation for Debt Consolidation Loans: Carefully evaluate applicants seeking debt consolidation loans, considering potential interest rate adjustments or offering financial counseling services to manage the associated risks.
	Consider Housing Stability: Take housing status into account during the underwriting process to assess housing stability and its impact on the applicant's ability to repay the loan.
	Review Verification Process: Review the verification process to ensure effective assessment of applicant creditworthiness. Consider improvements or adjustments based on the review findings.
	Monitor & Adjust for Regional Risk Trends: Monitor regional risk trends, especially in states like
California, Florida, and New York. Adjust lending strategies or rates accordingly in high-risk regions.
	Thorough Assessment for High Loan Amounts: Conduct more thorough assessments for loan amounts of $15,000 or higher. Consider capping loan amounts for higher-risk applicants to mitigate potential defaults.
	Adjust Interest Rates Based on DTI Ratios: Review the interest rate determination process and consider adjusting rates based on Debt-to-Income (DTI) ratios to align with the borrower's ability to repay.
	Consider Income Levels for Affordability: Consider offering financial education resources and set maximum loan amounts based on annual incomes below $40,000 to ensure loan affordability for borrowers.


## Technologies Used
Python	3.11.4	https://www.python.org/

Matplotlib	3.7.1	https://matplotlib.org/

Numpy	1.24.3	https://numpy.org/

Pandas	1.5.3	https://pandas.pydata.org/

Seaborn	0.12.2	https://seaborn.pydata.org/



<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@amit024] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
