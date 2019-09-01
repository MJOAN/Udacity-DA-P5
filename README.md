
# Prosper Data Exploration

## Dataset

The data consists of loan information of Prosper borrowers with 81 attributes and 113066 unique listings and 113937 loans last updated on march 11, 2014. The dataset is stored in a csv available via an external link [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554484977406000) with feature documentation available [here](https://docs.google.com/spreadsheets/d/1VtTHJgXz_oY8RRVGPKwFeYtN1BR23ZZMLJMqj_DaccQ/edit#gid=0) and click [here](https://www.prosper.com) to learn more about Prosper.


## Summary of Findings

In this exploration, I found there was a strong relationship between the 
Borrower Rate, and Borrower APR along with Estimated Loss and Estimated 
Return. The Borrower Rate and APR, as per [Investopedia](https://www.investopedia.com/ask/answers/100314/what-difference-between-interest-rate-and-annual-percentage-rate-apr.asp), are percentages calculated in addition to the 
loan cost over time, which the borrower is responsible for. The APR will 
include not only interest rate but, also added fees, with other discounts. 
This will affect a customer's decision when thinking about taking out a loan. 

Lastly, features like Estimated Loss, from [Investopedia](https://www.investopedia.com/terms/l/loanlossprovision.asp), is generally a 
provision that Prosper allocates to cover uncollected loans, due to borrower 
default, or bad loans among other options, similar to Estimated Return which 
would be a net positive to Prosper versus a net loss.

Many borrower features were analyzed of which were insightful such as the 
borrower state of residence, occupation, employment status, employment 
duration in days, listing category, delinquent amounts, principals outstanding,
credit grades, loan status, Prosper score, monthly loan payments, and loan
origination amount. Each of the plots on these features were helping to describe
the Prosper borrower and assess a type of profile or risk factor as to if they
would be able to pay off their loans with Prosper. 

In summary, borrower charactersitics were: 
    1. State of California resident
    2. Salary income range of $25000 to $49999 
    3. Not home-owners
    4. Credit grade of 'C' 
    5. Work occupation of 'Other'
    6. Mean Borrower Rate/Borrower APR of 19% , 21%, respectively
    7. Prosper Score of 4
    8. Loan Listing Category of 'Debt Consolidation' 
    9. Loan status of 'Current'
    10. Debt to Income Ratio of 25%
    11. Making on average, monthly payments of $272
    12. Majority considered as 'Employed'


## Key Insights for Presentation

For this presentation, I focus on the features using univariate, bivariate, and 
then multivariate plots to show relation between variables to provide analysis
in helping to understand the Prosper borrower. 

For univariate plots, I used mostly density, count, and histogram plots while
bivariate introduces scatter and facet grid plots. Lastly, for multivariate 
analysis, I used were heatmaps, facet grid plots. 
