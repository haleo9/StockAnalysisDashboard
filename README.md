# Stock Analysis and Visualization Dashboard

This project is designed to extract and visualize stock data for Tesla and GameStop. 
The analysis includes retrieving historical stock prices and quarterly revenue data using a combination of yfinance and web scraping. 
The extracted data is then visualized to create an interactive dashboard that compares stock prices and revenues over time.

## Project Structure

The project consists of the following questions:

### Question 1: Extracting Tesla Stock Data Using yfinance
- Uses the yfinance library to extract historical stock data for Tesla (TSLA).
- Data is retrieved and stored in a DataFrame named `tesla_data`.
- The first five rows of the DataFrame are displayed.

### Question 2: Extracting Tesla Revenue Data Using Web Scraping
- Uses the requests library to download Tesla's revenue data from a web page.
- The data is parsed using BeautifulSoup and stored in a DataFrame named `tesla_revenue`.
- The last five rows of the DataFrame are displayed.

### Question 3: Extracting GameStop Stock Data Using yfinance
- Uses the yfinance library to extract historical stock data for GameStop (GME).
- Data is retrieved and stored in a DataFrame named `gme_data`.
- The first five rows of the DataFrame are displayed.

### Question 4: Extracting GameStop Revenue Data Using Web Scraping
- Uses the requests library to download GameStop's revenue data from a web page.
- The data is parsed using BeautifulSoup and stored in a DataFrame named `gme_revenue`.
- The last five rows of the DataFrame are displayed.

### Question 5: Plotting Tesla Stock and Revenue Data
- Uses the `make_graph` function to create an interactive dashboard displaying Tesla's stock prices and revenue data.
- The graph includes historical share prices and revenue over time.

### Question 6: Plotting GameStop Stock and Revenue Data
- Uses the `make_graph` function to create an interactive dashboard displaying GameStop's stock prices and revenue data.
- The graph includes historical share prices and revenue over time.

## Installation

To run this project, you need to install the following Python libraries:
```bash
pip install yfinance
pip install pandas
pip install requests
pip install bs4
pip install plotly
pip install html5lib
pip install lxml
