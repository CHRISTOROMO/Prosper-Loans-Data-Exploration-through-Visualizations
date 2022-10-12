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

![image](https://user-images.githubusercontent.com/99474042/195328231-90e38e51-1712-4323-92cf-c668b84df1c5.png)

From the above we can easily tell that people on mid-range salary levels are the ones requesting most loans.

![image](https://user-images.githubusercontent.com/99474042/195328526-7ce872c8-5704-4e34-b723-4ed9defc2722.png)

From the above, the distribution of the Estimated loss is skewed to the right, while the Estimated return variable is slightly symmetrical.

![image](https://user-images.githubusercontent.com/99474042/195329136-c2607dff-1fab-4c00-9097-9b0bed363b04.png)

From the above we can tell from the above that the higher the credit score of a person, the lower the interest rate on the loan.

![image](https://user-images.githubusercontent.com/99474042/195329360-50ca75d3-f34f-44d9-9dd6-4e254c976785.png)

From the above, we can also see that most people with higher income levels (i.e $50000 and above) are also homeowners.


## License

Distributed under the MIT License. See license.txt for more information.
