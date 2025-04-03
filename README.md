# thequantscience | Pine Script | TradingView 
Come proprietario del profilo thequantscience su TradingView ho deciso di raccogliere tutti gli script più importanti all'interno di questa raccolta. Il profilo TradingView è ora inattivo ma puoi trovare tutto lo storico dei lavori più importanti rilasciati durante gli anni, molti dei quali Premium e mai pubblicati. Spero che questi script possano aiutare qualcuno durante le proprie ricerche sui mercati finanziari. Tutti gli script sono scritti in linguaggio Pine Script V6 e Pine Script V5. Gli script pubblici sono accompagnati da link per il repository su TradingView, quelli mai pubblicati sono accompagnati ciascuno da una breve descrizione.

Chart Box Indicator https://www.tradingview.com/script/IhMYkTot-Chart-Box-Session-Indicator-The-Quant-Science/
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Autoccorelation Price Forecasting: https://www.tradingview.com/script/AMe7s0ig-Autocorrelation-Price-Forecasting-The-Quant-Science/
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Advanced Portfolio Equity: https://www.tradingview.com/script/KORkHGXh-Advanced-Portfolio-Equity-The-Quant-Science/
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Dip & Rip Patterns: https://www.tradingview.com/script/H2RutLp1-Dip-Rip-Patterns-The-Quant-Science/
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
DCA KUCOIN STRATEGY BACKTESTING [MAI PUBBLICATO]

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


