# Loan Default Prediction
## Problem statement
A bank's consumer credit department aims to simplify the decision-making process for home equity
lines of credit to be accepted. To do this, they will adopt the Equal Credit Opportunity Act's
guidelines to establish an empirically derivedand statistically sound model for credit scoring.The
model will be based on the data obtained via the existing loan under writing process from recent
applicants who have been given credit.The model will be built from predictive modeling techniques,
but the model created must be interpretable enough to provide a justification for any adverse
behavior (rejections).

## Objective
The objective of this project is to build a classification model to predict clients who are likely to default on their loan and give
recommendations to the bank on the important features to consider while approving a loan.

## Dataset
The HomeEquity dataset(HMEQ) contains baseline and loan performance information for recent
home equityloans. The target(BAD) is a binary variable that indicates whether an applicant has
ultimately defaulted or has been severely delinquent.There are 12 input variables registered for each
applicant.

- BAD: 1 = Client defaulted on loan, 0 = loan repaid
- LOAN: Amount of loan approved
- MORTDUE: Amount due on the existing mortgage
- VALUE: Current value of the property
- REASON : Reason for the loan request (HomeImp = home improvement,DebtCon= debt
consolidation which means taking out a new loan to payoff other liabilities and consumer
debts)
- JOB: The type of job that loan applicant has suchas manager, self, etc.
- YOJ: Years at present job
- DEROG: Numberof major derogatory reports (whichindicates seriousdelinquencyorlate
payments).
- DELINQ: Number of delinquent credit lines (a line of credit becomes delinquentwhen a
borrower does not make theminimum required payments 30 to 60 dayspast thedayon
which the payments were due)
- CLAGE: Age of the oldest credit line in months
- NINQ: Number of recent credit inquiries
- CLNO : Number of existing credit lines
- DEBTINC: Debt-to-income ratio (all monthly debt payments divided by gross monthly
income.This number is one of the ways lenders measure a borrower’s ability to manage the
monthly payments to repay the money they plan to borrow)