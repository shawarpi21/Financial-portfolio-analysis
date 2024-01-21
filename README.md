Financial Portfolio Analysis Project Brief:

Introduction:
The Financial Portfolio Analysis tool assesses the performance of a financial portfolio over time, utilizing historical stock prices for selected securities. It aims to provide valuable insights into investment trends.

Dataset:
- Information: Includes adjusted close prices, various stock indicators (Open, Close, High, Low), dates, unique three-letter security codes (Symbol), and trading volumes.
  
Tools Used:
Python libraries - pandas, numpy, matplotlib.pyplot.

Loading and Preparing Data:
The project begins by loading an Excel file named 'Stock Portfolio.xlsx' into a Pandas DataFrame. Date columns are converted to Pandas datetime values for standardization.

Calculating and Displaying Average Price and Total Average Price:
Average price per security and total average price are calculated by considering opening and closing prices. A subset of the DataFrame displaying symbols and corresponding total average prices is then printed.

Financial Data Aggregation by Symbol and Year:
A "Year" column is created, and the DataFrame is grouped by symbol and year to calculate the sum of volume average prices.

Aggregating Total Volume by Symbol:
Data is organized based on different symbols, and the total volume for each symbol is calculated.

Creating a Portfolio Pie Chart:
A pie chart visually represents the distribution of total trading volume across different symbols in the portfolio.

Plotting High and Low Prices Over Time for Each Symbol:
Line plots are generated for high and low prices of each financial symbol over time, providing a clear visualization of price fluctuations.

Creating Volume Distribution Pie Charts for Each Symbol:
Pie charts illustrate the volume distribution across different years for each financial symbol.

Creating Bar Charts for Average Price Over Time for Each Symbol:
Bar charts are created to visualize the average price fluctuation over time for each financial symbol.

Creating Scatter Plots for Average Price vs Volume for Each Symbol:
Scatter plots show the relationship between average price and trading volume for each financial symbol.

Conclusion:
This Financial Portfolio Analysis project offers a comprehensive understanding of investment trends through key metrics and visualizations. The combination of pie charts, line plots, bar charts, and scatter plots facilitates a nuanced interpretation of the portfolio's performance.
