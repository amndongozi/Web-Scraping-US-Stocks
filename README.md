### Web Scraping US Stocks

## Overview
This project focuses on extracting data on US stocks listed in the Dow Jones Industrial Average (DJIA) through two primary methods. It uses web scraping to collect stock names and details from the Dow Jones Wikipedia page and integrates the Yahoo Finance API to retrieve stock prices and other financial data. The resulting datasets are used to analyze investment strategies such as backtesting.

## Features
- Automatically extracts and retrieves stock data.
- Organizes datasets for analysis.

## Instructions
1. **Set Up the Environment**:
   - Ensure you have Python 3.8 or later installed.
   - Install the required libraries:

     pip install requests beautifulsoup4 pandas yfinance
     
2. **Web Scraping**:
   - Open the notebook `US Stocks(Web Scraping).ipynb`.
   - Run the cells to scrape stock data from the Dow Jones Wikipedia page and Yahoo Finance.
   - Save the scraped data.

3. **API Integration**:
   - Open the notebook `US Stocks(API Wrapper).ipynb`.
   - Run the cells to retrieve additional financial data using the Yahoo Finance API.
   - Combine the data with the scraped data for a comprehensive dataset.

4. **Analyze the Data**:
   - Use the processed data to perform initial analysis.

5. **Visualizations**:
   - Visualize data trends using libraries like `matplotlib` or `seaborn`.
   
## Install required Libraries 
- `requests`: For making HTTP requests to web pages.
- `beautifulsoup4`: For parsing and extracting information from HTML and XML documents.
- `pandas`: For data manipulation and organization.
- `yfinance`: For retrieving financial data from Yahoo Finance.

## License
Licensed under the MIT License.


 

 
