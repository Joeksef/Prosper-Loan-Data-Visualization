# Prosper Loan Data VIsualization.

## By Kolawole Joseph. E.


## The Dataset

The Prosper Loan dataset has 113,937 entries with 81 features. Most variables are numeric in nature, 18 of which are Categorical , 60 are Numerical while 3 are Booleans.

The main feature of interest in the dataset is to derive insights from the dataset. For instance: about the loan repayment defaulters, conditions that affects loan repayment like Employment status, of borrowers, Loan term, Borrower Rate, as well as some other trends in the dataset. And apparently, the LoanStatus, CurrentDelinquencies, AmountDelinquent, DelinquenciesLast7Years, LoanCurrentDaysDelinquent, LoanOriginalAmount, as well as other features will help in this investigative work.


## Summary of Findings

After going through the whole process some of the insights derived are as follows:

* Most Loans are 'currently on' (50%), about 33% have been completed, while 11% are charged off meaning that the loan might likely not be paid. 4% have been flagged as defaulted.

* Prosper Loan is associated with employment status as most peolple on the loan list are employed (60%), 24% are employed full time. The percent of the unemploed and retired is infinitesimally minute and negligible (1%).

* The Prosper Score ranges from 1-10, with 10 being the best, or lowest risk score and 1 being the highest risk. Most loan has score ranging from 3.0 to 9.0. Score 4.0, 6.0 and 8.0 are among the highest frequencies. Though the Prosper Score is only applicable to loans originated after July 2009, score 4.0 have the highest count with 15% frequency.

* BorrowerAPR have some number of outlier values 0.48 to as high as 0.52 with the mean at 0.22. The lowest value lies around 0.0 while its highest value lies somewhere around 0.47 and 25% quartile lies at 0.15.

* Loan Original Amount have a great number of outlier values in them ranging from somewhere around 24,000 to as high as 36,000. Though the mean lies around 6,500. The lowest value lies around 1,000 while its highest value lies somewhere around 24,000 and 25% quartile lies at 4,000. With its 75% quartile lying around 13,500.

* 60% of the loan were given to Employed individuals while 24% were given to Full time employees.

* Prosper loan give more loan amount to Borrower with verifiable income. About 92% of the loan is given to this borrowers.

* Higher percent of CurrentDelinquencies are from borrowers with IncomeVerifiable.

* Since the Prosper Score ranges from 1-10, with 10 being the best, or lowest risk score and 1 being the highest risk. The prosper score has a negative effect on the borrower rate.

* The Loan original amount determines it's monthly payment amount. As the Original loan amount increases, the monthly payment amount increases.

* Borrower Rate has a stong positive correlation with LenderYield. Meaning the BorrowerRate determines the LenderYield. As bthe BorrowerRate increases, the Lender Yield increases.

* The number of investment from friends is a driving force behind the number of recommendations for loans. Both InvestmentFromFriendsCount and Recommendations are positively correlated, hence as more friends invest, the Recommendation count increases. Though this seem to be densely populated only at the origin between the count of 0 to 10 for. This leaves a question at hand if this is a maipulation from the borrower to quickly get loan from Prosper or a somewhat means to get recomendations and investments.

* 'ND' state has the highest number of deliquencies as high as 2.75. This is followed by 'IA' state which is as high as 1.5 and 'TX' state about 1.1 averagely.

* 'DC' state has the highest LoanOriginalAmount as high as 10,000 up to 11,000. This is followed by 'NJ' state which is as high as 9,500 and 'MA' state about 9,400. It is interesting to note here that ND state which has the highest numbers of Current deliquences has the lowest loan amount of about 4,000.

* The highest rating 'AA' has lowest average BorrowerAPR of 5.6, whereas HR which happens to be the lowerest rating has the highest average BorrowerAPR of 22.2. This helps to establish the fact that higher ProsperRating is associated with lower BorrowerAPR and vice versa.

* Here, a pattern can be seen that 12 which is the shortest loan term has the lowest average loan amount. This is followed by 36 and finally 60 (the longest loan term) with the highest average loan amount. Hence we can conclude that the longer the term, the higher the loan amount and vice versa.

* Quite a number of features are correlated either strongly positive or negative. Example of such includes:

    1. BorrowerAPR and BorrowerRate (99.0%)
    2. BorrowerAPR and LenderYield (98.9%)
    3. Recommendations and InvestmentFromFriendsCount (71.8%)
    4. LenderYield and EstimatedLoss (95.4%) etc
    5. BorrowerAPR and ProsperRating (numeric) (-96.2%)
    6. BorrowerRate and ProsperRating (numeric) (-95.3%)
    7. EstimatedLoss and ProsperRating (numeric) (-96.4%)
    8. EstimatedEffectiveYield and ProsperRating (numeric) (-84.8%) etc.

* Aside from year 2009, ProsperRating (Alpha) 'HR' has a higher APR in all years. This is followed by ProsperRating (Alpha)'E' which outperformed HR in year 2009.

* In year 2006 and 2007, most delinquencies are from Borrower whose employment status were not available probably because it was not given. However, from year 2010 to 2012, most delinquencies are from retired borrowers. While more delinquencies are recorded for borrowers whose employment status is a full time one.


## Key Insights for Presentation

It will be worthwhile to note that the number of investment from friends is a driving force behind the number of recommendations for loans. Both InvestmentFromFriendsCount and Recommendations are positively correlated, hence as more friends invest, the Recommendation count increases. Though this seem to be densely populated only at the origin between the count of 0 to 10 for. This leaves a question in mind if this is a manipulation from the borrower to quickly get loan from Prosper or a somewhat means to get recommendations and investments.

Furthermore, the Loan original amount determines it's monthly payment amount. As the Original loan amount increases, the monthly payment amount increases. We can also conclude that the longer the term, the higher the loan amount and vice versa. And this has little but significant thing to do with delinquencies because term 36 which is median when it comes to term has about 50.2% delinquencies whereas term 60, which has more loan amount has only 18% delinquencies. Hence, Prosper Loan should be given for a longer term, so as to enhance repayment.

Moreover, the highest rating of AA has lowest average BorrowerAPR of 5.6%, whereas HR which happens to be the lowerest rating has the highest average BorrowerAPR of 22.2%. This helps to establish the fact that higher ProsperRating is associated with lower BorrowerAPR and vice versa.

Inconclusion, More loans are given to Borrowers whose income are verifiable. And borrowers whose income are verifiable are major defaulters in loan repayment.