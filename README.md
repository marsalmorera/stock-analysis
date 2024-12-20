# Stock Analysis Dataset

Overview

The S&P 500 dataset provides a comprehensive view of the largest 500 publicly traded companies in the U.S., serving as a benchmark for market performance and long-term investment analysis. This dataset captures daily stock movements, company details, and index trends, offering insights into sector and individual stock performance.

Project Goal

Our primary objective is to analyze the performance of various sectors in the S&P 500, using the stock prices and revenue growth as key metrics. 

Dataset Description

The dataset comprises three primary components:

Index Data: Daily price of the S&P 500 index, representing overall market performance.
Stock Data: Daily stock prices for individual companies.
Company Data: Detailed metrics for each company, including sector, market cap, and financial indicators.
Key Columns
Date: Date of record.
Symbol: Ticker symbol identifying the company.
Sector: Broad industry classification (e.g., Technology, Healthcare).
Currentprice: Most recent stock price.
Volume: Total number of shares traded on a given day.
Marketcap: Total market value of a company’s outstanding shares.
Ebitda: A measure of profitability before interest, taxes, depreciation, and amortization.
Revenuegrowth: Percentage change in revenue between periods.
Weight: Company's market cap weight within the S&P 500.
Insights from the Data

Sector Representation:
Technology: 16%
Industrials: 14%
Financial Services: 13%
Healthcare: 12%
Consumer Cyclical: 10%
Current Price Statistics:
Mean: $230.29
Median: $126.82
Standard Deviation: $521.99
Min: $8.56 | Max: $8,946.33
Interquartile Range: $71.54 (Q1) - $239.19 (Q3)
Observations
Stock prices exhibit high variability, with a positively skewed distribution due to the presence of high-value stocks.
The interquartile range provides a more reliable snapshot of typical prices, excluding outliers.
Next Steps

Perform detailed EDA to identify key trends and sector performance.
Investigate the relationship between sector representation and stock performance.
Explore predictive modeling with currentprice as the target variable.
Data Source

The dataset and additional documentation are available on Kaggle.
