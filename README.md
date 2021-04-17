# DEEGA-s-ETF


> ## An EFT powered by NLP and Sentiment Analysis ##

## 1. Project Outline ##

This project is aimed at utilizing NLP, ML and cutting-edge sentiment analysis techniques to analyse data from Twitter API, and News API to inform investment decision in order to build and backtest an ETF.
		
## 2. INVESTMENT OBJECTIVE ## 
DEEGA-S ETF (the “Fund”) is intended to be an actively managed blend ETF that seeks to replicate DEGA’s proprietary US equity sentiment Index with an aim to beat S&P 500 (the “Benchmark) before fees and expenses.

## 3. PRINCIPAL INVESTMENT STRATEGIES ##
Under normal conditions the Fund intends to invest 100% of its net assets in an equally weighted in securities that comprise top 10 of the DEGA’s US Equity Sentiment Index constructed using a proprietary methodology. The companies that qualify to be included in this index are all companies traded on three principal indexes (S&P 500, DJIA, and NASDAQ) with a market cap > USD 2 Billion. Since this is a sentiment bases active investment strategy, the fund managers review the portfolio on a regular basis and rebalance the holdings to reflect the latest composition of the Equity Sentiment Index.

## 4. PORTFOLIO MANAGERS ##
David Costa, Evita Louissaint, Esteban Cervantes, Gabriela Galarza, Abhishek Srivastava. 

## 5. PORTFOLIO PERFORMANCE ##

The portfolio performance is based on a 14-day trading cycle. The fund has managed to meet all its targets set by the portfolio managers, including beating the benchmark S&P 500. 
                       
![image](https://user-images.githubusercontent.com/34671710/115123185-ef5b3500-9f89-11eb-8671-acd18ee50f14.png)

![image](https://user-images.githubusercontent.com/34671710/115123309-67c1f600-9f8a-11eb-95f8-973d93f867e3.png)

![image](https://user-images.githubusercontent.com/34671710/115123318-74464e80-9f8a-11eb-8e08-f7bb6689e555.png)

  
## 6. PRINCIPAL RISKS ##
> a)	Concentration Risk: Since market sentiments tend to, at times, favor certain sectors or economy, there is chance that the Funds’ investment can get crowded into a particular sector. The regular reviews of the sector will help in mitigating this risk.
> b)	Market Risk: The investments are exposed subject to the market risk like all investments. The diverse nature of the portfolio will help in mitigating a few of the risks.
> c)	New Fund Risk: The Fund is new type of fund with limited or no operational history and a small asset base. 
> d)	Risk of social media analytics: Social media analytics aim 


## 7. DISCLAIMER ##

This ETF is for only an academic exercise and should not be taken as an investment advice.  



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




## Reference ##
This ETF is build upon a proof of concept exercise conducted under: 
