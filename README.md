# API-INTEGRATION-AND-DATA-VISUALIZATION

"COMPANY NAME": CODETECH IT SOLUTIONS

"NMAE" : SHAIK SHAMEER

"INTERN ID" : CT04DH281

"DOMAIN" : PYTHON

"DURATION" : 4 WEEKS

"MENTOR" : NEELA SANTHOSH

"DESCRIPTION":

Project Description: Stock Market Analysis Dashboard This project is a Stock Market Analysis Dashboard built using Streamlit, which provides a real-time, interactive interface for analyzing popular stock data. The data is fetched using the Alpha Vantage API, which offers free access to financial market data including time-series prices for various publicly traded companies.

Technologies Used: Streamlit: For building an interactive, user-friendly dashboard interface.

Alpha Vantage API: For fetching real-time stock data.

Pandas: For data manipulation and handling time series data.

Matplotlib & Seaborn: For creating insightful visualizations like line plots and box plots.

Python datetime: For parsing and handling time-based data.

Key Features: Multi-stock Selection: Users can choose from a list of well-known stocks including Apple, Microsoft, Google, Amazon, and Tesla using a multiselect widget. This allows simultaneous analysis of multiple stocks.

Real-Time Data Fetching: The fetch_stock_data function utilizes the Alpha Vantage TIME_SERIES_INTRADAY endpoint with a 60-minute interval to retrieve hourly stock data. It then processes this data into a pandas DataFrame with time indices and relevant price columns (Open, High, Low, Close, Volume).

Caching with @st.cache_data: To reduce API calls and improve performance, the fetched data is cached for one hour. This makes the dashboard efficient by preventing repeated API requests for the same data.

Live Data Table: For each selected stock, the dashboard displays the latest few entries of hourly data in a tabular format using st.dataframe.

Line Chart Visualization: A line chart is created using Seaborn to show how the closing price of each selected stock changes over time. This provides a clear trend of stock performance within the intraday time frame.

Box Plot Analysis: A box plot is displayed to help users analyze the distribution of stock prices for the selected companies. This provides insights into price variability and outliers.

Conclusion: This project demonstrates how to combine data engineering and visualization to produce a powerful tool for stock market analysis. It showcases API integration, data handling, caching, and charting within a Streamlit web application. Ideal for learners and investors, the dashboard is simple yet effective for quick stock comparisons and trend analysis.

"OUTPUT"

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/c4722076-7b16-44df-b7b0-c90c40bbfe6c" />


