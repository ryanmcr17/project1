# Project Title
Impact of US Federal Interest Rate Policy on Forward-Looking Valuations of Large Businesses

## Project Slides
Available via Google Slides (https://docs.google.com/presentation/d/1pjGxOh8FvX1S35TMoEiEba3v-Y6i0WvMh-jHJv1zy38/edit#slide=id.p), PDF copy also included in repo

## Project Writeup
Available in Google Docs ()

## Project Description
Analysis of US interest rate policy relative to large US company valuations. Interest rate policy is represented by effective federal funds rates, set by the Federal Open Market Committee (FOMC) within the Federal Reserve central bank of the US. Forward-looking valuations of large companies are represented by S&P 500 Price-to-Earnings (PE) Ratio data.

Anecdotally, and very generally, businesses typically see stronger revenue/earnings growth when interest rates are lower, at least when other economic conditions are equivalent (employment rates / labor market conditions and inflation rates especially). When the Fed/FOMC 'tightens' interest rate policy by raising their Fed Funds target rate range (i.e. 'raising interest rates') that often negatively impacts future business growth/profits and therefore current forward-looking valuations (in the form of stock prices). However, forward-looking valuations of large US businesses are dependent upon many factors beyond just interest rates, and many of those factors likely impact both valuations as well as federal interest rates themselves (confounding factors). I'm curious to explore the direct relationship mathematically to see how strong it may be, while understanding that a much more thorough analysis would be necessary to truly understand the complex relationship between these two variables and that an especially strong negative correlation (r-value close to -1) is highly unlikely.

## Key questions to analyze/answer:
- What do the distributions of values look like from each individual dataset?
- What values/periods from each dataset could be considered outliers?
- Is there a consistent (negative) correlation between Effective Fed Funds Rates and S&P 500 PE ratios/valuations?
- Do potential outlier data points (whether included or removed) have a significant impact on the level of correlation between the two datasets?

## Additional questions that would be nice to analyze further in the future with additional time/resources:
- Considering the potential time-lag in impact of interest rates on PE ratios, is there a stronger correlation between the two variables if accounting for that time-lag by shifting the x-axis for one of the variables relative to the other?
- What other factors/variables likely impact US company valuations / PE ratios that should be considered through additional analyses? Which of those may also have an impact on interest rate policy / future rates themselves?
- Are there specific sectors / business types that respond more directly/immediately to changes in federal interest rate policy?
- Is there a ‘better’ dependent variable for representing interest rate policy in the US, in terms of showing a closer real-time correlation with PE ratios and therefore higher potential for causality/predictability (i.e. producing an r-value closer to -1)?

## Additional Notes on Project/Plan
Originally considered looking at tech company valuations specifically, via NASDAQ index PE ratios and because interest rates anecdotally seem to have a greater impact on tech company valuations due to longer average time-to-value industry-wide. Went with broader S&P 500 index data because it's available across a much longer time period, and Fed interest rates move quite slowly over years and differently over decades.

## Acknowledgements / Data Sources
- pulling code from week-06/module-06 'WeatherPy' challenge as starting point for data loading
- US federal interest rate data by month obtained from Kaggle (https://www.kaggle.com/datasets/federalreserve/interest-rates)
- S&P 500 PE ratios by month obtained from NASDAQ Data Link API (https://docs.data.nasdaq.com/docs/python-time-series)
