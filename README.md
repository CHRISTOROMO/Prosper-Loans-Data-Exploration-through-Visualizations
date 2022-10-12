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

![image](https://user-images.githubusercontent.com/99474042/195343189-30da520b-0926-431a-9675-e42487e28c58.png)

From the above observation, we can easily tell that people on mid-range salary levels are the ones requesting most loans and that the most loans are still active.

![image](https://user-images.githubusercontent.com/99474042/195343307-0e3f1bce-f3a1-4942-9942-c9c299c1da77.png)

From the above, the distribution of the Estimated loss is skewed to the right, while the Estimated return variable is slightly symmetrical. Also most loans are requested by people with a credit score of 700. Also the credit score rating is skewed to the left.

![image](https://user-images.githubusercontent.com/99474042/195343393-22e7a75c-4764-402f-bd65-6c53228f88b7.png)

From the above we can tell from the above that the higher the credit score of a person, the lower the interest rate on the loan.

![image](https://user-images.githubusercontent.com/99474042/195343468-056e831f-a666-4846-bd24-73e0e838d84d.png)

From the above, we can also see that most people with higher income levels (i.e $50000 and above) are also homeowners. Also most employed people requesting for the loan are also homeowners.

![image](https://user-images.githubusercontent.com/99474042/195343570-e541393a-2c20-482e-ae7f-dfddd4a6da75.png)

From the above, we can tell that original loan amount tend to rise with the increase in the Income Range. The highest income range bracket contains the most diverse request amounts of the original loan amount.

![image](https://user-images.githubusercontent.com/99474042/195343664-0593dbc6-5356-46de-a409-5ebbef196db2.png)

We can see that the BorrowerAPR and the BorrowerRate are highly correlated. Also the EstimatedLoss and the EstimatedReturn are highly correlated.

## License

Distributed under the MIT License. See license.txt for more information.
