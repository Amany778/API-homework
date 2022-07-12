# FinTech consultancy firm
this is a tool that helps with retirement financial planning. It is used to assess monthly personal finances, and also forecast a reasonably good retirement plan based on cryptocurrencies, stocks, and bonds.
The first part is a personal finance planner that will allow users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emergency fund.
The second tool is a retirement planning tool that will use the Alpaca API to fetch historical closing prices for a retirement portfolio composed of stocks and bonds, then run Monte Carlo simulations to project the portfolio performance at 30 years. The tool also calculates the expected portfolio returns given a specific initial investment amount.


## Files


Personal Finance Planner 


MCForecastTools toolkit




## Resources
This tool utilizes two APIs:


The Alpaca Markets API is used to pull historical stocks and bonds information.


The Alternative Free Crypto API is used to retrieve Bitcoin and Ethereum prices.


##The documentation for these APIs can be found via the following links:


Free Crypto API Documentation


AlpacaDOCS



## Part 1 - Personal Finance Planner
### This section is the personal finance planner prototype, the following assumptions are made:


The average household income for each member of the credit union is $12,000.


Every union member has a savings portfolio composed of cryptocurrencies, stocks and bonds:


The mount of crypto assets are: 1.2 BTC and 5.3 ETH.


The amount of shares in stocks and bonds: 50 SPY (stocks) and 200 AGG (bonds).





### The following conclusions are drawn:

The portfolio value of cryptocurrencies is calculated and results are printed out.

The value in dollars of the current amount of shares is calculated results are printed out.



## Savings Health Analysis
In this section, we assess the financial health of the credit union's members.





### Assumptions: 
monthly_income is $12000.
mergency fund is equal to three times the monthly income.

If total savings are greater than the emergency fund, the person for having enough money in this fund.
If total savings are equal to the emergency fund, the person is on reaching their financial goal.
If total savings are less than the emergency fund, the person hasn't still reached their goal.





## Part 2 - Retirement Planning
In this section, we use the Alpaca API to fetch historical closing prices for a retirement portfolio and then Use the MCForecastTools toolkit to create Monte Carlo simulations to project the portfolio performance at 30 years. We also use the Monte Carlo data to answer questions about the portfolio.



### Retirement Analysis


The summary statistics of the Monte Carlo is printed out.


Given an initial investment of $20,000, we calculate the expected portfolio return in dollars at the 95% lower and upper confidence intervals.


We also Calculate the expected portfolio return at the 95% lower and upper confidence intervals based on a 50% increase in the initial investment.



Early Retirement
The options for early retirements are investigated with higher initial investment. 

