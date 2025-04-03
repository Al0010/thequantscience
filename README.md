# thequantscience | Pine Script | TradingView 
As owner of **thequantscience** profile on TradingView I decided to provide best scripts in this collection. My TradingView profile is now inactive but you can find the entire history of the most important scripts released over the years, many of them premium and never published. I hope these scripts can help someone during their research on the financial markets. All scripts are written in Pine Script language V6 and Pine Script V5. The public scripts are provided by links to the repository on TradingView, the never published ones are each provided by a short description here on Git Hub. Please note that this is only a collection, many more scripts are public in the Scripts section of my TradingView profile. Leave a star if you have enjoyed my work in the field of algorithmic trading.

**Documentation List**

**1. Chart Box Indicator https://www.tradingview.com/script/IhMYkTot-Chart-Box-Session-Indicator-The-Quant-Science/**
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**2. Autoccorelation Price Forecasting: https://www.tradingview.com/script/AMe7s0ig-Autocorrelation-Price-Forecasting-The-Quant-Science/**
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**3. Advanced Portfolio Equity: https://www.tradingview.com/script/KORkHGXh-Advanced-Portfolio-Equity-The-Quant-Science/**
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**4. Dip & Rip Patterns: https://www.tradingview.com/script/H2RutLp1-Dip-Rip-Patterns-The-Quant-Science/**
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**5. DCA KUCOIN STRATEGY BACKTESTING [NEVER PUBLISHED]**

GENERAL OVERVIEW
Backtesting software developed on the DCA strategy offered by KuCoin Exchange. This software exactly replicates the logic used by the KuCoin algorithm, giving you the ability to backtest correctly before investing.

LOGIC
As anticipated, we have planned the exact investment logic used by KuCoin's DCA bot and every day we continue to work hard to update the software and bring it in line with the new releases.

Understanding the DCA (Dollar Cost Average).
Working with a DCA strategy means split the investment over specific intervals by averaging the entry price. This strategy optimize the investment avoiding a single market price entry and incurring the risk of buying 100% of the capital at too high price.

Imagine investing USDT 1,000 every 30 days for 5 months. If the prices at the end of each month were 100 USDT, 90 USDT, 70 USDT, 95 USDT the average entry price would be 85.5 USDT. If we had invested the full amount in the first month the entry price would have been 100 USDT.

Price with average - 85.5 USDT
Price without average - 100 USDT

Keep in mind that the above example is only meant to give you an understanding of how a DCA strategy works. Let us now look at how exactly the DCA strategy offered by KuCoin works.

KuCoin's strategy applies a DCA model on time intervals. The first order is executed at the first price close when the position balance is zero, and then new orders are opened at each new time interval.

When the position balance is zero, the first order called 'START DCA' is executed.

https://www.tradingview.com/x/KqRcWY8m/

Starting from the price of the initial order, new positions are opened until the maximum capital to be invested is exhausted.

https://www.tradingview.com/x/5vLZDsZB/

The entire investment is closed on a single exit condition, take profit percentage calculated on equity.

https://www.tradingview.com/x/Uh3uuPUr/

Specifics of this software.
This software allows you to backtest with DCA strategies on time intervals offered by the global exchange KuCoin. You can choose and adjust all features such as time interval, order size and maximum investment. Investment closing is based on take profit.

This software includes:
1) Backtesting
2) Professional user interface

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**6. 3COMMAS DCA STRATEGY BACKTESTING [NEVER PUBLISHED]**

GENERAL OVERVIEW
Backtesting software developed on the DCA strategy offered by 3Commas. This software exactly replicates the logic used by the 3Commas algorithm, giving you the opportunity to perform proper backtesting before investing.

Understanding the DCA (Dollar Cost Average).
Working with a DCA strategy means split the investment over specific intervals by averaging the entry price. This strategy optimize the investment avoiding a single market price entry and incurring the risk of buying 100% of the capital at too high price.

Imagine investing USDT 1,000 every 30 days for 5 months. If the prices at the end of each month were 100 USDT, 90 USDT, 70 USDT, 95 USDT the average entry price would be 85.5 USDT. If we had invested the full amount in the first month the entry price would have been 100 USDT.

Price with average - 85.5 USDT
Price without average - 100 USDT

Keep in mind that the above example is only meant to give you an understanding of how a DCA strategy works. Now let's look at exactly how the DCA strategy offered by 3Commas works.

The 3Commas strategy defines an entry trigger, which can be defined as a single market condition or a set of market conditions. An example could be the RSI indicator crossing down 35, a price crossover of the weekly average or the simple closing of a candle on the previous one, or even all three of these conditions grouped together.

When the condition is true, the entry trigger is activated and the 3Commas DCA strategy opens the first order called the 'Base Order'.

https://www.tradingview.com/x/tOwnYRQm/

Starting from the initial order price, new positions are opened for a user-definable maximum number. All new orders are calculated on the initial price and are therefore not executed based on the starting condition. The calculation depends on the functionality activated and the parameters set. You can find all details in the official documentation of this software. Each new order after the first one is called a 'Safety Order'.

https://www.tradingview.com/x/Wzx3P4UA/

The entire investment is closed out on an exit condition, which can be a specific indicator condition, a take profit or a stop loss. Depending on the configuration set by the user.

https://www.tradingview.com/x/HFus9H9p/

Specifics of this software.
This software allows you to backtest with 5, 10 and 20 safety order long or short DCA strategies. You can choose a single entry trigger based on technical indicators such as RSI, MACD or Stochastic. Investment closing is based on take profit and stop loss.

This software includes:
1) Backtesting
2) Premium RSI Indicator
3) Premium MACD Indicator
4) Premium Stochastic Indicator
5) Professional user interface

