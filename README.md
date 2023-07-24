# Project Title
Impact of Federal Interest Rate Policy on Forward-Looking Valuations of Large Businesses in the US

## Project Description
Analysis of US interest rate policy relative to large US company valuations. Interest rate policy is represented by effective federal funds rates, set by the Federal Open Market Committee (FOMC) within the Federal Reserve central bank of the US. Forward-looking valuations of large companies are represented by S&P 500 Price-to-Earnings (PE) Ratio data.

Anecdotally, and very generally, businesses typically see stronger revenue/earnings growth when interest rates are lower, at least when other economic conditions are equivalent (employment rates / labor market conditions especially). When the Fed/FOMC 'tightens' interest rate policy by raising their Fed Funds target rate range (i.e. they 'raise interest rates') that often negatively impacts business growth/profits and therefore valuations. However, forward-looking valuations of large US businesses are dependent on many factors beyond just intrest rates, and many of those factors likely impact both valuations as well as federal interest rates themselves (confounding factors). I'm curious to explore the direct relationship mathematically to see how strong it may be, while understanding that a much more thorough analysis would be necessary to truly understand the complex relationship between these two variables and that an especially strong negative correlation (r-value close to -1) is highly unlikely.

Key questions to analyze/answer:
- What do the distributions of values look like from each dataset?
- What values/periods from each dataset could be considered outliers?
- Is there a consistent (negative) correlation between Effective Fed Funds Rates and S&P 500 PE ratios/valuations?
- Do potential outlier data points (whether included or removed) have a significant impact on the level of correlation between the two datasets?

Additional questions that would be nice to analyze further in the future with additional time/resources:
- Considering the potential time-lag in impact of interest rates on PE ratios, is there a stronger correlation between the two variables if accounting for that time-lag by shifting the x-axis for one of the variables relative to the other?
- What other factors/variables likely impact US company valuations / PE ratios that should be considered through additional analyses? Which of those may also have an impact on interest rate policy / future rates themselves?

## Addtional Notes on Project/Plan
Originally considered looking at tech company valuations specifically, via NASDAQ index PE ratios and because interest rates anecdotally seem to have a greater impact on tech company valuations due to longer average time-to-value industry-wide. Went with broader S&P 500 index data because it's available across a much longer time period, and Fed interest rates move quite slowly over years and differently over decades.

## Acknowledgements / Data Sources
- pulling starting points for dependencies and data loading from WeatherPy activity (week/module06)
- found datasets via Kaggle (interest rates by month) and NASDAQ Data Link API (S&P 500 PE ratios by month)
