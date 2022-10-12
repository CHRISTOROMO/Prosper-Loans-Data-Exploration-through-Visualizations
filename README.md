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

![image](https://user-images.githubusercontent.com/99474042/195408253-3fb44808-d537-4a52-b8a2-55630fa34c2f.png)

From the above observation, we can easily tell that people on mid-range salary levels are the ones requesting most loans and that the most loans are still active.

![image](https://user-images.githubusercontent.com/99474042/195408326-77275198-99a1-456a-beb1-7987dba78eab.png)

From the above, the distribution of the Estimated loss is skewed to the right, while the Estimated return variable is slightly symmetrical. Also most loans are requested by people with a credit score of 700. Also the credit score rating is skewed to the left.

![image](https://user-images.githubusercontent.com/99474042/195408417-bfa7ba9a-d45d-421f-ac1e-4e4dbf6cba08.png)

From the above we can tell from the above that the higher the credit score of a person, the lower the interest rate on the loan.

![image](https://user-images.githubusercontent.com/99474042/195408513-d2a113d2-7c57-473e-b56b-b66855b198e9.png)

From the above, we can also see that most people with higher income levels (i.e $50000 and above) are also homeowners. Also most employed people requesting for the loan are also homeowners.

![image](https://user-images.githubusercontent.com/99474042/195408619-58e1fbbc-3247-4126-96c6-f394d833edb4.png)

From the above, we can tell that original loan amount tend to rise with the increase in the Income Range. The highest income range bracket contains the most diverse request amounts of the original loan amount.

![image](https://user-images.githubusercontent.com/99474042/195408697-33c6245f-6088-46bb-b6e2-b4b7487f8d68.png)

We can see that the BorrowerAPR and the BorrowerRate are highly correlated. Also the EstimatedLoss and the EstimatedReturn are highly correlated.

## License

Distributed under the MIT License. See license.txt for more information.
