#📈 Extracting and Visualizing Stock Data
🧩 Coursera Final Project — IBM Data Science Professional Certificate

This project demonstrates how to extract, clean, and visualize financial data using Python. The goal is to collect historical stock prices and revenue data for Tesla (TSLA) and GameStop (GME), then visualize their trends using interactive graphs.

🚀 Project Overview

In this assignment, we use Python libraries such as yfinance, requests, BeautifulSoup, and plotly to:
Extract stock data using the Yahoo Finance API.
Scrape revenue data from online sources.
Clean and structure the data into pandas DataFrames.
Create interactive line charts to visualize stock performance over time.

📚 Libraries and Tools Used
pandas — Data manipulation and analysis
yfinance — Extracting stock data from Yahoo Finance
requests — Downloading HTML web pages
BeautifulSoup (bs4) — Parsing and scraping web content
plotly.express — Interactive graph visualization
html5lib / html.parser — HTML parsing

🧠 Key Steps
Extract Stock Data
Used yfinance.Ticker() to get Tesla and GameStop data.
Saved the full historical dataset using history(period="max").
Scrape Revenue Data
Downloaded revenue tables from provided URLs using requests.
Parsed HTML with BeautifulSoup to extract the "Quarterly Revenue" tables.
Data Cleaning
Reset DataFrame indices and formatted columns.
Ensured date consistency for analysis up to June 2021.
Visualization
Created interactive graphs using plotly.express showing stock price trends.

📊 Results
Plotted Tesla Stock Price up to June 2021.
Plotted GameStop Stock Price up to June 2021.
Demonstrated the correlation between stock price movements and revenue data.
