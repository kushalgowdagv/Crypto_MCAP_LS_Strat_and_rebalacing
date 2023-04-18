# Crypto_MCAP_LS_Strat_and_rebalacing
1. Calculate price average for each coin at month ends as -
    a. [Last 3-day average close price/Last 30-day average close price)]
2. Rank the coins based on this price average ratio.
3. Buy the top 5 ranked coins (go long).
4. Sell the bottom 5 ranked coins (go short).
5. Make an equi-weighted portfolio of these 10 coins (Portfolio will be now 50% long and
    50% short. Gross weight is 100%).
6. Hold the position in these 10 coins till the next month end.
7. Repeat the steps 1-6 every month end to form a new portfolio (monthly rebalance).
8. Generate a daily portfolio time series out of this monthly rebalance strategy since 1-
    Jan-2021 and plot it against BTC.
