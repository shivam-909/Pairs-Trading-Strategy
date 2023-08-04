**Introduction/Hypothesis:**

In this project, we've implemented a pairs trading strategy on Exxon Mobil (XOM)
and Chevron (CVX), two major oil companies operating within the same industry.
The principle behind pairs trading is the expectation of mean reversion when the
spread between two correlated stocks diverges significantly. We've
operationalized this by defining conditions based on the z-scores of the spread
to trigger our long and short positions.

**Analysis:**

The chart presents the dynamic performance of our pairs trading strategy over
time. From 2015 to 2020, the strategy struggled, with cumulative returns dipping
as low as -50%. This could have been due to a variety of factors such as changes
in the oil market, lack of mean reversion in the spread, or other macroeconomic
variables affecting the correlation between the stocks.

However, in 2020, the outbreak of the COVID-19 pandemic had significant impacts
across all sectors, including oil. The strategy's performance dramatically
improved during this period, with cumulative returns skyrocketing to 250%. This
sudden upswing may have been driven by increased mean reversion in the stock
prices, potentially due to shared responses to the industry-specific factors or
broader economic trends induced by the pandemic.

Despite a significant pullback to 100% and a subsequent bounce to 200% in
2021-2022, the strategy experienced another drawdown to 50% followed by a
substantial rise to 300% in 2022-2023. The extreme volatility during this period
coincided with geopolitical tensions, including Russia's invasion of Ukraine in
2022, which led to a significant surge in oil prices.

**Conclusion:**

The performance of the pairs trading strategy has been highly volatile and
appears to be significantly influenced by major global events. The periods of
high returns during the COVID-19 pandemic and following Russia's invasion of
Ukraine suggest that the strategy can capitalize on market volatility induced by
such events. However, the periods of losses underline the potential risks and
the importance of careful risk management.

It would be beneficial to investigate these periods further to understand how
these global events affected the correlation and mean reversion of the two oil
stocks and consider if and how the strategy could be improved to mitigate risks
during other periods.

Furthermore, it would be worthwhile to test the strategy on other pairs, adjust
the z-score thresholds, or modify the lookback period for calculating the mean
and standard deviation to see if the performance can be improved.

As always, all investment strategies carry risk, and past performance does not
guarantee future results. Thorough backtesting, consideration of transaction
costs, and portfolio diversification are essential for risk management.
