# DEEGA-s-ETF


> ## A Social Sentiment based ETF powered by NLP and Sentiment Analysis ##

## 1.Project Outline

3 months of data from news api, bloomberg api, and reddit api


ETF - Portfolio construction
	Idea Generation
		Twitter Data (starting point for Stock idea generation, at least 10 stocks)
	Data sources (3months of data for start), this is to test market sentiment on each stock
Bloomberg API
News API
Reddit API
	Data processing (filter, decision criteria for picking top stocks out of the sample)
		Frequency
		Classification ( positive, neutral, negative), Probably NLP processing
	Stocks selection
		Decision to include positions on 5 out of the 10 stocks
		Frequency + classification ( positive, neutral, negative)

ETF - Prospectus
	PDF document explaining Fund characteristics
	Rebalancing of the portfolio is based on ETF manager discretion, based on data availability

ETF - Benchmarking
	Compare to other sources of analysis, as it is not possible to backtest with the amount of data that we have. No clear path yet, dependent on data results

ETF - performance and results 
	No clear path yet, dependent on data results
	
	
## INVESTMENT OBJECTIVE ## 
DEEGA-S ETF (the “Fund”) is intended to be an actively managed blend ETF that seeks to replicate DEGA’s proprietary US equity sentiment Index with an aim to beat S&P 500 (the “Benchmark) before fees and expenses.

## PRINCIPAL INVESTMENT STRATEGIES ##
Under normal conditions the Fund intends to invest 100% of its net assets in an equally weighted in securities that comprise top 10 of the DEGA’s US Equity Sentiment Index constructed using a proprietary methodology. The companies that qualify to be included in this index are all companies traded on three principal indexes (S&P 500, DJIA, and NASDAQ) with a market cap > USD 2 Billion. Since this is a sentiment bases active investment strategy, the fund managers review the portfolio on a regular basis and rebalance the holdings to reflect the latest composition of the Equity Sentiment Index.

## FUND FEES AND EXPENSES ##
Since fees and expenses play and important part in your overall returns, we aim to keep it low as compared to many of our peers. What enables us to keep our expenses low is the power of machine learning. 
![image](https://user-images.githubusercontent.com/34671710/115122960-c8e8ca00-9f88-11eb-9bfa-4b924765faec.png)


## 2.0 Tools used

```
first Part
pip install tweepy
pip install yfinance 
pip install -U python-dotenv
pip install -U textblob
pip install seaborn
pip install matplotlib.pyplot
pip install regex
pip install requests
pip install datetime
pip install alpaca-trade-api
pip install pandas
News API
	Vader Model
	BERT model
Second Part

```
## 3. Prospectus of the ETF / Model.
### a. Stock picking idea Generation propietary Model
	Curated author feeds from Twitter, finds top stock with social sentiment

### b. Portfolio management
	Top 5 stocks selection, based on news sentiment 
	News API
	Vader Model
	BERT model


## 4. Link to our code.
