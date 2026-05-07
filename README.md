# tesla-gme-stock-revenue-dashboard-financial-data-analysis-project-IBM
Web scraping and interactive stock market analysis dashboard for TSLA and GME using Matplotlib and Pandas.

# Tesla & GameStop Stock vs. Revenue Dashboard

A data science project that extracts, cleans, and visualizes historical stock prices and revenue data for Tesla (TSLA) and GameStop (GME). This project combines financial data from APIs with web-scraped data to build a comparative visual dashboard.

## Features
* **Stock Data Extraction:** Utilizes `yfinance` to pull historical share prices.
* **Web Scraping:** Uses `requests` and `BeautifulSoup` to parse quarterly financial tables from HTML source files.
* **Data Pipelines & Cleaning:** Standardizes dates, handles missing values, and removes currency formatting using `pandas`.
* **Data Visualization:** Generates dual-subplot line graphs via `matplotlib` to analyze share price trends alongside quarterly revenue.

## Technology Stack
* Python 3
* Pandas
* Matplotlib
* yfinance
* BeautifulSoup4 (bs4)
* Requests

## Dashboard Previews
The visualization scripts automatically apply a historical boundary up to June 2021 to compare the structural growth of both companies during critical market events.

## Setup & Installation
To run this notebook locally, clone this repository and install the required dependencies:

```bash
pip install yfinance pandas matplotlib beautifulsoup4 html5lib lxml requests
```

Open the `.ipynb` file using Jupyter Notebook or JupyterLab to execute the cells.

## Project Origin
This project was developed as part of the **IBM Data Science Professional Certificate** curriculum to demonstrate my foundational data engineering, web scraping, and financial data analysis skills.
