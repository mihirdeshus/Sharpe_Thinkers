IQF Mid-Term Project

Team: Sharpe Thinkers

Development Note:
This project was developed locally using Visual Studio Code and then uploaded to GitHub as a complete file. As a result, the repository does not reflect a detailed commit history, since the development process occurred offline rather than through incremental Git commits.

Project Overview:
This project investigates whether a higher Sharpe Ratio truly indicates a superior portfolio, using Indian equity market data across different economic regimes.

Step-by-Step Methodology:

1. Data Collection:
   Retrieved historical stock price data (2014–2024) using Yahoo Finance. Selected representative large-cap stocks across sectors such as technology, financials, and manufacturing.

2. Data Processing:
   Converted daily price data into monthly prices and computed monthly returns for all assets.

3. Risk-Free Rate Definition:
   Assumed a constant 6% annual risk-free rate based on RBI Treasury Bills and converted it into a monthly rate.

4. Portfolio Construction:
   Designed four portfolios: Tech Heavy, Financial Heavy, Manufacturing Heavy, and Equal Weight. Assigned weights based on sector emphasis.

5. Performance Metrics:
   Computed Sharpe Ratio (monthly and annualised), average returns, volatility, skewness, kurtosis, and maximum drawdown.

6. Market Regime Analysis:
   Divided the timeline into Pre-COVID (2014–2019), COVID Crisis (2020), and Post-COVID (2021–2024), and evaluated portfolio performance across each regime.

7. Statistical Testing:
   Used Spearman rank correlation to test the stability of Sharpe rankings and conducted Welch t-tests to compare returns between top and bottom portfolios.

8. Visualization:
   Generated plots including Sharpe ratios across regimes, rank heatmaps, rolling Sharpe ratios, return distributions versus a normal curve, and cumulative returns.

9. Key Findings:
   Sharpe rankings are not stable across market regimes. Portfolio performance is highly regime-dependent. Returns are not normally distributed, violating Sharpe assumptions. Higher Sharpe ratios do not necessarily imply statistically superior returns.

Conclusion:
The project shows that while the Sharpe Ratio is useful, it should not be treated as a definitive indicator of portfolio superiority across different market conditions.
