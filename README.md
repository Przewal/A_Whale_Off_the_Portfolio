# Portfolio Analysis and Comparison - A Whale Off the Port(folio)

__Python File:__ `whale_analysis.ipynb`

## Background
In this project, I embarked on an extensive journey to analyze and compare the performance of various investment portfolios. My dataset comprised historical daily returns for a diverse set of portfolios, ranging from algorithmic trading strategies to the renowned "whale" investors' portfolios and major hedge and mutual funds. My primary mission was to identify the portfolio that outshines the rest, considering key metrics such as volatility, returns, risk, and Sharpe ratios.

Additionally, I ventured into creating a custom portfolio, carefully selecting 3 stocks (took the available ones) from the vast stock market, and meticulously evaluating its performance.The ultimate goal was to determine whether the custom portfolio could stand toe-to-toe with the giants of algorithmic trading.

## Reference datasets

* `whale_returns.csv`: Contains returns of some famous "whale" investors' portfolios.

* `algo_returns.csv`: Contains returns from the in-house trading algorithms from Harold's company.

* `sp_tsx_history.csv`: Contains historical closing prices of the S&P TSX 60 Index.

* `l_historical.csv`: Contains historical closing prices of the "L" Symbol.

* `otex_historical.csv`: Contains historical closing prices of the "OTEX" Symbol.

* `shop_historical.csv`: Contains historical closing prices of the "SHOP" Symbol.

## My Journey in Three Acts

### Act I: Reading and Wrangling Returns Data
My journey commenced with the vital task of collecting and cleaning the historical daily returns data for each portfolio. Data wrangling skills were put to good use to ensure my dataset was in pristine condition for further analysis.

### Act II: Evaluating the Success of Each Portfolio
With my data prepared, I delved into the heart of the analysis, striving to determine the success of each portfolio. Armed with mathematical prowess, I calculated and compared critical metrics, including returns, volatility, risk, and the esteemed Sharpe ratios.

### Act III: Crafting and Evaluating the Custom Portfolio
In the final act, I created a custom portfolio. With Google Finance as my guide, I handpicked a selection of 3 stocks (I used the ones provided in the resources - points for being lazy), meticulously balancing risk and return. The newly formed custom portfolio was subjected to rigorous evaluation, including the calculation of weighted returns and an array of quantitative analyses.

## The Quest for Knowledge: Quantitative Analysis

### Performance Analysis

* I meticulously calculated and charted daily returns for every portfolio, unraveling their day-to-day performance.
* To gauge the true champions, I examined cumulative returns, eagerly searching for any portfolio outperform the S&P TSX 60 Index.

### Risk Analysis

* With box plots as my visual aides, I visualized the risks associated with each portfolio.
* Standard deviation allowed me to pinpoint portfolios riskier than the steadfast S&P TSX 60.
* The Annualized Standard Deviation revealed the long-term risk outlook, providing deeper insights into portfolio stability.

### Rolling Statistics
* With rolling windows, I unveiled the ever-changing landscape of risk. The 21-day rolling standard deviation plot uncovered the portfolios navigating turbulent waters.
* Usage of correlationhelped understand which portfolios mirrored the movements of the S&P TSX 60 Index.
* In the quest for beta, I selected Warren Buffet's portfolio and embarked on a 60-day rolling beta calculation, comparing its performance to the stalwart S&P TSX 60.
* I additionally explored the Exponentially Weighted Moving Averages rolling statistics.


### Sharpe Ratios
* Recognizing that returns alone do not tell the full story, I turned to the Sharpe ratios to assess the return-to-risk trade-off. A bar plot elegantly visualized these ratios.
* The age-old question of whether algorithmic strategies could outshine the market and the whales portfolios found its answer by plotting Sharpe ratios.

### Crafting the Custom Portfolio

* The data wrangling and manipulation part was carried similar to the above.
* Assuming an equal number of shares per stock, and the custom portfolio was added to the previous data ensemble.
* Quantitative analyses, akin to brushstrokes on a canvas, unfolded for the custom portfolio, revealing its unique performance characteristics.

### The Grand Finale

My journey culminated in a grand finale, where the stars of my analysis took their bows.

* Algorithm-1 emerged as the undisputed champion, outperforming all other portfolios.
* The custom portfolio held its own, outshining the majority of portfolios but yielding to Algorithm-1's dominance.