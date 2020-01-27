# BackTesting

Python notebooks to demonstrate backtesting with Zipline. 

The underlying library behind quantopian https://www.quantopian.com
https://github.com/quantopian/zipline

The notebook StrategySelectionWithCosts.ipynb evaluatates several EMA based momentum strategies, incorporating cost data. 
The notebook MomentumSlowVolAdj.ipynb looks at one particular momentum based strategy. 

# Dependencies

The Talib library is used to calculate the technical indicators used https://github.com/mrjbq7/ta-lib

For demostration purposes the underlying used is BTC-USD as market data for this is freely avaiable from Coinbase Pro with 
the API https://github.com/danpaquin/coinbasepro-python

The final tearsheet used is the pyfolio library https://github.com/quantopian/pyfolio

# Performance measures and Portfolio construction

An excellent book on backtesting strategies and portfolio construction is Systematic Trading by Robert Carver  
https://www.amazon.co.uk/Systematic-Trading-designing-trading-investing-ebook/dp/B014J5LNSY/ref=sr_1_1?keywords=systematic+trading&qid=1580131156&sr=8-1

For more insight into how to use Zipline and Pyfolio try Trading Evolved by Andreas Clenow
https://www.amazon.co.uk/Trading-Evolved-Anyone-Killer-Strategies/dp/109198378X

At the very least always be aware that a backtest on past market data *is not necessarily* indicative of future performance 
and these notebooks contain no financial advice or recommendations. 



