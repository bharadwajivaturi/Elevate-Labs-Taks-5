# Elevate-Labs-Taks-5
Data Analysis on CSV Files
## Project Summary: Cryptocurrency Data Analysis

This project performs a basic exploratory data analysis on cryptocurrency data using Python's Pandas and Matplotlib libraries.

**Dataset:**

The analysis uses a CSV file named `Crypto.csv` with the following columns:

*   `name`: Name of the cryptocurrency
*   `abbr`: Abbreviation of the cryptocurrency
*   `crypturl`: URL on crypto.com
*   `price`: Current price
*   `volume24hrs`: 24-hour trading volume
*   `marketcap`: Market capitalization
*   `circulatingsupply`: Circulating supply of coins
*   `maxsupply`: Maximum supply of coins
*   `totalsupply`: Total supply of coins
*   `date_taken`: Date the data was recorded

**Analysis Performed:**

1.  **Data Loading and Inspection:** The code loads the data into a Pandas DataFrame and performs basic checks on its shape, data types, and missing values.
2.  **Data Cleaning:** The `marketcap` column, which contained commas and was read as an object type, was cleaned by removing commas and converting it to a numeric type. Other relevant columns were also converted to numeric.
3.  **Top Cryptocurrencies by Market Cap:** A bar plot is generated to show the top 10 cryptocurrencies based on their market capitalization.
4.  **Price Distribution:** A histogram is plotted to visualize the distribution of cryptocurrency prices, using a logarithmic scale for better visualization of skewed data.
5.  **Volume vs. Market Cap Analysis:** A scatter plot is created to explore the relationship between 24-hour trading volume and market capitalization, using logarithmic scales for both axes.
6.  **Correlation Analysis:** A heatmap is generated to visualize the correlation matrix of key numerical metrics (price, volume24hrs, marketcap, circulating supply, max supply, total supply).
7.  **Price Volatility Analysis:** A bar plot is generated to show the top 10 most volatile cryptocurrencies based on the standard deviation of their prices.
8.  **Price Trend Analysis:** The price trend of Bitcoin (BTC) over time is plotted as a line chart.

**How to Use:**

1.  Upload the `Crypto.csv` file to your Google Colab environment.
2.  Run the provided code cells in a Jupyter Notebook or Google Colab.
3.  The code will output basic data information and generate plots visualizing the analysis results.

This analysis provides initial insights into the cryptocurrency market based on the provided dataset. Further analysis could include time-series forecasting, more in-depth correlation studies, or incorporating data from other sources.
