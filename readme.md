# Prosper Loan Data Exploration
## by Chukwume Ijeh


## Dataset

> The Dataset contains 113,917 loans, each loan has information on each borrower's Annual Percentage Rate (APR), status, borrowed amount, debt, etc. Variables that were not used in the exploration and variables with missing values were dropped to make the Dataset more accurate. Outliers were also removed to provide more reliable Data. This investigation considered only entries listed after July 2009 and analyzed factors that could influence borrower's APR.

> The following variables were taken into consideration: Prosper Rating (Alpha), Prosper Score, Term, Loan Original Amount, IsBorrowerHomeOwner, stated Monthly Income and Employment Status.



## Summary of Findings

> From the univariate exploration of variables, it was found that 79.5% of individuals in this data set are Employed. But the APR was highest for borrowers who were Not employed. Most of the entries in this dataset have Term of 36months while 12months is the least Term count.

> Prosper Rating (Alpha), Prosper Score, Loan Original Amount and stated Monthly Income were found to be negatively correlated to Borrower's APR. Adding to that Prosper Rating gave the strongest negative relationship with borrower's APR.

> Borrowers who were home owners showed a slight increase in APR compared to those who were not.

> Interestingly, the relationship between borrower APR and Loan Amount turns from negative to slightly positive when the Prosper Ratings (Alpha) are increased. I also found that the borrower APR decrease with the increase of borrow term for people with HR-D raings. But for people with C-AA ratings, the APR increase with the increase of borrow term.

> Outside of the main variables of interest, I found that the Loan Amount is positively correlated with the stated Monthly Income and Term. I also found that borrowers with better ratings have larger Monthly Income and Loan Amount. 

> There are more 60 month loans on B and C ratings. There is only 36 months loans for HR rating borrowers. 

>With better Prosper rating, the Loan Amount of all three Terms increase, the increase amplitude of loan amount between terms also becomes larger.



## Key Insights for Presentation

> For the presentation, I will be focusing on features that could affect the borrower APR, which are Loan Original Amount, Prosper Rating (Alpha), Prosper Score and if borrower is a homeowner or not.