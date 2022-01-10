# Time Series Analysis - Analyzing Porsche and Volkswagen Closing Stock Prices


### Project Description:
In this project, I'll be analyzing the closing stock prices of Volkwagen (VW) and Porsche in the periods leading up to, and following the official announcements of the buyout of Porsche by Volkswagen.

I'll examine the effects that the buyout had on the closing stock prices, and how they changed in the aftermath of the following official announcements:
1. First official announcement, made on 2009-12-09. The day VW announced they owned 49.9% of Porsche.
2. Second official announcement, made on 2012-07-05. The day VW announced they acquired full ownership (51.1%) of Porsche.

The entire period of study has been divided into three distinct intervals; the split points of which are the dates of the official announcements:
- Interval 1: Before the first official announcement.
- Interval 2: Between the first and second official announcements.
- Interval 3: After the second official announcement.

The analysis will focus on exploring what the effects the buyout had on the following across the 3 intervals:
- The trend in the stock,
- The correlation between the stock,
- How the best fitting models for each stock changed, and
- Volatility of the stocks.

To ensure that all changes in values are stock specific, we need a market benchmark. The ideal choice for this would be some other automobile producer selling stocks on the German market.  
Bayerische Motoren Werke AG (BMW) is chosen to be the benchmark. Therefore the stock prices of BMW in the period of study will be used as the baseline of the analysis.

The objective of this project is to explore and analyse the specific events that have been defined rather than an attempt to forecast future stock prices of VW and Porsche.


### Dataset Description:
- The data is scrapped from yahoo finance using Python package `yfinance`.
- It raw data contains records from as far back as 1996 up till the date it was scrapped, however the analysis will be limited to between period 2009-04-05, and 2014-01-01.
- The three(3) companies, whose equitites were recorded from the German Stock Market, to be examined and their respective tickers are:
    - PAH3.DE Porsche Automobil Holding SE
    - VOW3.DE: Volkswagen AG
    - BMW.DE: Bayerische Motoren Werke AG. (Chosen benchmark for the analysis)
- The currency of the stock prices is the EURO, €.


### Contents:
- PROJECT DESCRIPTION
    - Dataset Description

- DATA PREPARATION AND PRE-PROCESSING
    - Importing the Relevant Packages
    - Importing the Data
    - Defining Key Dates
    - Pre-processing the Data

- EXPLORATORY ANALYSIS
    - Correlation
        - Correlation: Interval 1
        - Correlation: Interval 2
        - Correlation: Interval 3

- FINDING THE BEST FITTING MODELS
    - Stationarity Tests
        - stationarity test for VW
        - stationarity test for Porsche
        - stationarity test for BMW
    - Best Fitting Models for Volkswagen
        - Best Fitting Models for Volkswagen: Interval 1
        - Best Fitting Models for Volkswagen: Interval 2
        - Best Fitting Models for Volkswagen: Interval 3
    - Best Fitting Models for Porsche
        - Best Fitting Models for Porsche: Interval 1
        - Best Fitting Models for Porsche: Interval 2
        - Best Fitting Models for Porsche: Interval 3

- PREDICTIONS
    - Predicting Volkswagen Prices
        - Predicting Volkswagen Prices in Interval 2
        - Predicting Volkswagen Prices in Interval 3
    - Predicting Porsche Prices
        - Predicting Porsche Prices in Interval 2
        - Predicting Porsche Prices in Interval 3

- VOLATILITY
    - Volatility: Volkswagen
    - Volatility: Porsche

- CONCLUSION

- REFERENCES
