# DATA DICTIONARY

1. **SeriousDlqin2yrs:** This variable indicates whether a person has experienced a serious delinquency in the past two years. A serious delinquency means being 90 days or more late on a credit payment. It's a yes/no value, where "Y" means they have experienced such delinquency, and "N" means they haven't.

2. **RevolvingUtilizationOfUnsecuredLines:** This variable measures how much of a person's available credit they are using on their credit cards and personal lines of credit (excluding mortgages or car loans). It's a percentage that shows how close they are to reaching their credit limits. For example, if the value is 50%, it means they're using half of their available credit.

3. **Age:** This is the person's age in years. It's a whole number that tells us how old they are.

4. **NumberOfTime30-59DaysPastDueNotWorse:** This variable counts the number of times a person has been between 30 and 59 days late on a payment in the last two years. It's a count of how many times they've been in this situation.

5. **DebtRatio:** This ratio shows how much of a person's monthly income is used to pay debts, alimony, and living costs. It's a percentage that indicates their level of financial obligation compared to their income.

6. **MonthlyIncome:** This is the person's monthly income in dollars. It tells us how much money they earn each month.

7. **NumberOfOpenCreditLinesAndLoans:** This variable counts the number of open loans (like car loans or mortgages) and lines of credit (like credit cards) that a person has.

8. **NumberOfTimes90DaysLate:** Similar to the "NumberOfTime30-59DaysPastDueNotWorse," this counts the number of times a person has been 90 days or more late on a payment in the last two years.

9. **NumberRealEstateLoansOrLines:** This variable counts the number of mortgage and real estate loans a person has, including home equity lines of credit.

10. **NumberOfTime60-89DaysPastDueNotWorse:** Like the other similar variables, this counts the number of times a person has been between 60 and 89 days late on a payment in the last two years.

11. **NumberOfDependents:** This variable counts the number of dependents in a person's family, excluding themselves. It includes their spouse, children, and others who rely on them financially.

These variables provide information about a person's credit history, financial situation, age, and family circumstances. They are used to assess the risk associated with lending money to individuals and to predict the likelihood of serious delinquency in loan repayments.

  The target variable in this dataset is "SeriousDlqin2yrs." This variable indicates whether a person has experienced a serious delinquency in the past two years. It's a binary variable with two possible values:

"Y": This value indicates that the person has experienced a serious delinquency (90 days or more past due) in the last two years.
"N": This value indicates that the person has not experienced a serious delinquency in the last two years.
In machine learning terms, the target variable is what we're trying to predict or classify. In this case, the goal is to build a model that predicts whether an individual is likely to experience a serious delinquency in the next two years based on the other variables in the dataset.
