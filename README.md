
# D.E.E.G.A. Sentiment ETF #

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
## 3. Description of the ETF / Model.
### a. Stock picking idea Generation propietary Model
	Curated author feeds from Twitter, finds top stock with social sentiment

### b. Portfolio management
	Top 5 stocks selection, based on news sentiment 
	News API
	Vader Model
	BERT model


## 4. Link to our code.
