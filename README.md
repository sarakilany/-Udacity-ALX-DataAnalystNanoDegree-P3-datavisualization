# Loan Data from Prosper
## by Sara Osama Kilany


## Dataset

The dataset contains information on 113,937 loans with 81 features on each loan. The features include loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

The dataset had missing values in some columns, with some columns having missing values greater than 10%. Thus, these columns were dropped, leaving only columns with missing values less than 10%.

After preprocessing, only 94843 records and the following 17 columns were kept for analysis:

IncomeRange
BorrowerAPR
BorrowerRate
AvailableBankcardCredit
TotalCreditLinespast7years
Occupation
LoanStatus
LoanOriginalAmount
CreditScoreRangeLower
CreditScoreRangeUpper
EmploymentStatus
IsBorrowerHomeowner
DebtToIncomeRatio
Investors
BorrowerState
EmploymentStatusDuration
OccupationGroup
The dataset can be found in [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv),
with feature documentation available [here](https://docs.google.com/spreadsheets/u/0/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing).


## Summary of Findings

During my exploratory analysis, I observed several interesting relationships in the loan dataset. Firstly, I discovered that the majority of borrowers who had defaulted on their loans had lower income ranges. Secondly, I noticed that borrowers who were current on their loans tended to have higher income ranges than those who had completed their loans.

Next, I examined the relationship between loan original amount and borrower income range, and found that borrowers with higher income ranges tended to have larger loan original amounts. Additionally, I observed that the majority of borrowers who completed their loans had lower average loan original amounts compared to those who were still current on their loans.

Furthermore, I investigated the relationship between borrower homeownership status, income range, and loan original amount. I discovered that homeowners tended to have larger loan original amounts than non-homeowners, regardless of their income range. Finally, I observed that borrowers with higher income ranges tended to have a higher average loan original amount compared to those with lower income ranges, regardless of their loan status.


## Key Insights for Presentation


In the presentation, I only talk about how the loan original amount varies across the borrower state, Income range, Is borrower homeowner, and loan status. I begin by showing the distribution of borrowers across different states and their loan original amount, namely the 5 states with the largest number of borrowers. I then investigate both the total and average loan original amount in those states. 

In the second part of the code, the analysis continues by looking at the relationship between loan amounts and income ranges as well as borrower homeowner status. The total loan amount by income range and borrower homeowner status was investigated. In addition, I created a visualization to show the average Loan Amount by Income Range across Borrower Homeowner Status for those top 5 States. Overall, I’ve chosen different colors for each quality variable to make it clear that they’re not the same in different plots.


