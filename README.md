# -Stock-Data-Analysis-and-Strategy-Development-Using-Moving-Averages

Stock Analysis and Trading Strategy
This project focuses on analyzing stock data from the Nifty 50 index and developing a simple trading strategy. It demonstrates various aspects of financial data analysis, strategy development, and risk management using Python.
Features

Stock Data Analysis

Fetches 6 months of historical stock data for 5 major Nifty 50 companies using yfinance
Calculates and visualizes daily percentage changes
Computes and plots 20-day moving averages


Moving Average Crossover Strategy

Implements a strategy based on 50-day and 200-day moving averages
Generates buy and sell signals
Backtests the strategy against historical data
Compares strategy performance with a buy-and-hold approach


Risk Management

Calculates maximum drawdown for each stock
Implements a 5% stop-loss mechanism
Compares strategy performance with and without stop-loss



Technologies Used

Python
yfinance for data retrieval
pandas for data manipulation
matplotlib for data visualization
numpy for numerical operations

Key Findings

The project analyzes TCS, HDFC Bank, Infosys, ICICI Bank, and Wipro stocks
Visualizations include closing prices, daily percentage changes, and moving averages
The moving average crossover strategy is implemented and backtested for TCS
Risk management techniques are applied to potentially improve strategy performance

Future Improvements

Expand analysis to more stocks or different time periods
Implement more sophisticated trading strategies
Incorporate additional risk management techniques
Add real-time data analysis capabilities
