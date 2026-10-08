# Tesla vs GameStop: Stock Price and Revenue Analysis

## Project Overview

This project uses Python to extract, clean and visualise historical stock prices and quarterly revenue data for Tesla (TSLA) and GameStop (GME).

Completed as part of the IBM Python Project for Data Science course, the project demonstrates fundamental data analysis techniques including API-based data extraction, web scraping, data cleaning and visualisation.

## Technologies Used

- **Python** — Data extraction and analysis
- **yfinance** — Historical stock market data
- **BeautifulSoup** — Web scraping and HTML parsing
- **Requests** — Retrieving webpage data
- **pandas** — Data cleaning and manipulation
- **Plotly** — Interactive financial visualisations in the original course workflow
- **Jupyter Notebook** — Development and documentation

## Project Workflow

1. Extract Tesla historical share prices using yfinance.
2. Scrape Tesla quarterly revenue data from an HTML table.
3. Extract GameStop historical share prices using yfinance.
4. Scrape GameStop quarterly revenue data.
5. Clean and structure the datasets using pandas.
6. Generate stock price and revenue visualisations for both companies.

## Key Observations

**Tesla:** The historical data shows substantial share price appreciation and revenue growth through the first half of 2021.

**GameStop:** The data captures the dramatic share price volatility of early 2021, alongside a longer-term decline in quarterly revenue from earlier peaks.

These observations illustrate how share prices and underlying business revenue can exhibit very different patterns.

## Skills Demonstrated

- Working with external financial data
- Extracting data through APIs and web scraping
- Cleaning and transforming DataFrames
- Handling missing values and inconsistent formatting
- Building and interpreting time-series visualisations

## Running the Project

Install the required Python packages:

```bash
pip install yfinance pandas requests beautifulsoup4 matplotlib plotly
```

Open `tesla-gamestop-stock-analysis.ipynb` in Jupyter Notebook and execute the cells in sequence.

## Acknowledgements

Developed from the IBM Python Project for Data Science course assignment. Historical revenue datasets were provided through IBM Skills Network educational resources.

## Future Improvements

- Extend the analysis using more recent financial data.
- Calculate daily returns and rolling volatility.
- Compare share price movements with revenue growth.
- Build an interactive dashboard with additional financial metrics.
