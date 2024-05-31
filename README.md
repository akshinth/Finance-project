# Finance-project
In this data project we will focus on exploratory data analysis of stock prices.  We'll focus on bank stocks and see how they progressed throughout the financial crisis all the way to early 2016.
## Objectives:
### Data Retrieval:
Gather historical stock price data for key banks using the yfinance library.
### Data Preparation:
Organize the data into a format suitable for analysis, ensuring it is clean and well-structured.
### Data Analysis:
Conduct various analyses to understand the trends, volatility, and overall performance of these stocks.
### Visualization:
Create informative visualizations to illustrate the findings and provide insights into the stock behaviors over time.
# Data Sources:
### Yahoo Finance:
Historical stock prices are retrieved using the yfinance library, which provides easy access to financial data.
### Banks Analyzed:
Bank of America (BAC)
CitiGroup (C)
Goldman Sachs (GS)
JPMorgan Chase (JPM)

## Steps Involved:
Setting Up the Environment: 
#### Import necessary libraries and configure the environment for data analysis.
### Retrieving Data:
Use the yfinance library to download stock price data for each bank from January 1, 2006, to January 1, 2016.
### Data Preparation:
Combine data into a multi-level DataFrame.
Calculate daily returns for each stock.
### Exploratory Data Analysis:
Calculate basic statistics such as mean, median, and standard deviation of the stock returns.
Identify dates with the highest and lowest returns for each stock.
Analyze the correlation between the stocks.
### Visualization:
Use Seaborn and Matplotlib to create plots that illustrate the distribution of returns, stock price trends, and other relevant analyses.
### Summary and Insights:
Summarize the key findings from the analysis and provide insights into the stock performance during the financial crisis and subsequent recovery.
### Tools and Libraries:
Python: The primary programming language used for data analysis.
yfinance: Library for retrieving financial data.
pandas: Data manipulation and analysis library.
numpy: Library for numerical computations.
seaborn: Statistical data visualization library.
## Conclusion:
This project provides a comprehensive analysis of how major bank stocks behaved during one of the most turbulent periods in recent financial history. By examining the trends and volatility of these stocks, we gain valuable insights into the impact of the financial crisis on the banking sector and its subsequent recovery. This analysis not only showcases technical skills in data manipulation and visualization but also demonstrates the ability to derive meaningful insights from financial data.
