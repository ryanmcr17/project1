# project1

# Proposal: I plan to analyze the relationship between interest rates in the US (based on the US Federal Open Market Committee (FOMC) effective Fed Funds rate) and the forward-looking valuations of large US businesses (based on S&P500 index price-to-earnings (PE) ratios). Anecdotally it is considered common knowledge that Federal Reserve / FOMC interest rate policy impacts business growth/profits and therefore valuations, but I'm curious to explore the direct relationship mathematically to see how strong it may be.
### Originally considered looking at tech company valuations specifically, via NASDAQ index PE ratios and because interest rates anecdotally seem to have a greater impact on tech company valuations due to longer average time-to-value industry-wide. Went with broader S&P 500 index data because it's available across a much longer time period, and Fed interest rates move quite slowly over years and differently over decades.
### Key questions to analyze/answer:
##### What do the distributions of values look like from each dataset?
##### What values/periods from each dataset could be considered outliers?
##### Is there a consistent correlation between Effective Fed Funds Rates and S&P 500 PE ratios/valuations?
##### Do potential outlier data points (whether included or removed) have a significant impact on the level of correlation between the two datasets?
### Additional questions to consider if time/resources permit:
##### Considering the potential time-lag in impact of interest rates on PE ratios, is there a stronger correlation between the two variables if accounting for that time-lag by shifting the x-axis for one of the variables relative to the other?
##### What other factors/variables likely impact US company valuations / PE ratios that should be considered through additional analyses?

# Notes on datasets / reference sources:
### pulling starting points for dependencies and data loading from WeatherPy activity (week/module06)
### found datasets via Kaggle (interest rates by month) and NASDAQ Data Link API (S&P 500 PE ratios by month)
