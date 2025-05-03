# Web Scrapping 🕸 Project _ Stock Revenue Data Analysis

## Project Overview

This project extracts and visualizes historical revenue data for Tesla and GameStop using two different methods:
1. **yfinance API**: Leveraging Yahoo Finance's Python library to extract stock information
2. **Web Scraping**: Extracting data directly from web pages using Beautiful Soup, Requests and pandas read_html

The project is part of the IBM Data Science Professional Certificate program (Course 5) focusing on data collection and processing techniques.

## Features

- Extract Tesla (TSLA) stock and revenue data
- Extract GameStop (GME) stock and revenue data
- Visualize stock prices and revenue trends with Matplotlib
- Display historical data in well-formatted dataframes

## Technologies Used

- **Python**: Primary programming language
- **Jupyter Notebook**: Development environment
- **pandas**: Data manipulation and analysis
- **yfinance**: Stock data extraction from Yahoo Finance
- **Beautiful Soup**: Web scraping HTML content
- **Requests**: HTTP library for accessing web content
- **Matplotlib**: Data visualization

## Installation

```bash
# Clone this repository
git clone https://github.com/MrRehanKhanX/Web_Scrapping.git

# Navigate to the project directory
cd Web_Scrapping

# Install required packages
pip install pandas numpy matplotlib yfinance beautifulsoup4 requests
```

## Usage

1. Open the Jupyter Notebook:
```bash
jupyter notebook Web_Scrapping.ipynb
```

2. Run all cells to:
   - Extract stock data using yfinance
   - Scrape revenue data from web sources
   - Generate visualizations comparing Tesla and GameStop performance

## Sample Visualizations

The project generates visualizations that show:
- Stock price history for Tesla and GameStop
- Revenue trends over time
- Comparative analysis between the companies

## Data Sources

- Stock price data: Yahoo Finance (via yfinance API)
- Revenue data: Web scraping from quarterly financial report pages

## Learnings

This project demonstrates key data science skills including:
- Data extraction from APIs
- Web scraping techniques
- Data cleaning and transformation
- Financial data visualization
- Python programming for data analysis

## Future Enhancements

- Add more companies for broader market analysis
- Implement predictive analytics for stock price forecasting
- Create interactive dashboards with Plotly
- Include more financial metrics (e.g., P/E ratio, market cap)

## Acknowledgments

- IBM Data Science Professional Certificate program
- Yahoo Finance for providing the stock data API

---
*This project was completed as part of the IBM Data Science Professional Certificate on Coursera.*
