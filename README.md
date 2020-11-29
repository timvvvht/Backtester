# Backtester
A backtester written in python with NumPy and Pandas, showcasing Dollar-Cost-Averaging (DCA) and DCA with portfolio rebalancing.

## Strategies tested
1. DCA on SPY
2. DCA on SPY and GLD with a 80-20 weighting
3. DCA on SPY and GLD with a 80-20 weighting, rebalancing once every 2 months
4. DCA on SPY and GLD with a 80-20 weighting, rebalancing once every 6 months
5. DCA on SPY and GLD with a 50-50 weighting
6. DCA on SPY and GLD with a 50-50 weighting, rebalancing once every 2 months
7. DCA on SPY and GLD with a 50-50 weighting, rebalancing once every 6 months

![img](https://github.com/timvvvht/Backtester/blob/main/returns.png)

This shows that using a dollar-cost-averaging strategy in the timeframe Jan 2005 to Nov 2020 on only the SPY yields the highest returns out of all other strategies, beating the baseline strategy of no investments by a large margin.
