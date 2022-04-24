# MCForecastTools
This application is a financial planner for retirement. 
Plugin the crypto wallet & details on stocks & bonds( SPY & AGG), the application will calculate if you have enough money in this fund for emergencies. Emergency fund should be 3 * monthly_income. 
It displays a pie chart for your portfolio. 
It uses Alpaca ADK to get closing prices for SPY & AGG.
It simulates 30 year Monte Carlo simulation for 60% for SPY & 40% AGG and calculates the lower & upper cumulative return with 95% confidence. Then checks returns for 10 year simulation with 80% SPY & 20% AGG . 