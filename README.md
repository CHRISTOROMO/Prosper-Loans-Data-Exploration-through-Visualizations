# Prosper Loans Data Exploration through Visualizations
## by Christopher Toromo


## Dataset

The data set can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) and the variable descriptions 
can be found [here](https://docs.google.com/spreadsheets/u/0/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing).

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. 

## Summary of Findings

I started by doing the descriptive statistics on the numeric columns to get an insight into how the data is distributed. I found out that most loans were of
36 months term period and above and the highest term was 60. The estimated mean return from the loan was -0.182700 which indicates negative returns.
We have more loans on the current status and they tend to have a lower estimated loss. The higher the borrower's annual percentage rate (APR) for the loan, 
the higher the Estimated Loss and Estimated Return. The higher a person's credit score, the lower the interest rate on the loan. Most people requesting 
the loan are on the mid-range salary levels. Most people requesting the loan are on employed status. Most people requesting the loan are 
in the un-categorized job profession. Most people requesting for the loan to consolidate other current loans they have.

## Key Insights for Presentation

![image](https://user-images.githubusercontent.com/99474042/195062174-70b9ac90-ae06-4323-8033-601d7712fbed.png)

We can easily see the loan amount increases with the increase of the IncomeRange

![image](https://user-images.githubusercontent.com/99474042/195062355-a80aa7d5-7507-445e-8b9f-22c6f295bb38.png)

We can also note most employed people requesting the loan are also homeowners and most people with higher income levels (i.e $50000 and above) are also homeowners. 

## License

Distributed under the MIT License. See license.txt for more information.
