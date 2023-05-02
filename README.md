# Supdem1
The Shved Supply and Demand indicator is a technical analysis tool designed for MetaTrader 4 (MT4), a popular trading platform for forex, stocks, and other financial instruments. The Shved Supply and Demand indicator aims to identify key areas of supply and demand in the market, which can help traders make informed decisions about entering or exiting positions.

The indicator analyzes historical price data to determine significant levels where the price has previously reacted. These levels may act as potential support or resistance areas in the future. The Shved Supply and Demand indicator plots these levels on the chart as rectangles or zones, with the color-coded representation indicating whether it's a supply or demand zone.

The basic idea behind using this indicator is that when the price approaches a supply zone, it may face selling pressure, and there is a higher probability that the price will reverse or consolidate. Conversely, when the price approaches a demand zone, there may be buying pressure, increasing the likelihood of a price bounce or consolidation.

As with any trading tool, it's important to use the Shved Supply and Demand indicator in conjunction with other technical analysis methods, such as chart patterns and technical indicators, to confirm its signals and manage risks. Additionally, understanding the fundamental factors that drive supply and demand can also help traders make more informed decisions.



“This is MQL5 version of Shved Supply and Demand indicator written by Shved and upgraded by eevviill7 and Behzad Movaghar.

Added history mode to indicator. Set "historyMode" parameter to true then "double click" on any point in price chart to see Support and Resistance zones in that point.

Indicator uses fractals and ATR indicator to find and draw support resistance zones on price chart. Types of zones are:

weak: important high and low points in trend
untested: major turning points in price chart that price still didn't touch the again
verified: strong zones, price touched them before but couldn't break them
proven: verified zone that at least four time price couldn't break it
broken: zones that price breaks them (not applied for weak zones)”

The code provided the implementation of the Shved Supply and Demand indicator, which includes functions to calculate Fast and Slow Fractals, as well as the logic to identify the different types of supply/demand zones such as Weak, Untested, Verified, and Proven.
