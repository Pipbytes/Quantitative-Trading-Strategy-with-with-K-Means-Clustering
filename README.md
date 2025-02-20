# Quantitative-Trading-Strategy-with-K-Means-Clustering
This project demonstrates a quantitative trading strategy development process using stock price data. The strategy incorporates feature engineering, feature selection, clustering, and signal generation. The final output evaluates the strategy’s profitability with detailed trade-wise results.


## Data Preparation
- Using price data to calculate features

## Conducted stationarity checks and correlation analysis
- Non-stationary features.
- Features with correlations above 0.7.

## Data Splitting and Scaling
- Split the data into training and testing sets.
- Applied scaling to normalize feature distributions.

## Clustering
- Used K-Means clustering to find optimal clusters in the dataset.
- Determined the number of clusters using the Elbow Method.

## Signal Generation
- Generated trading signals based on cluster labels and user-defined future returns.

## Strategy Evaluation:
- Computed strategy profitability.
- Presented detailed trade-wise Profit and Loss (P&L) analysis.

Note:
I'm currently rewriting the trading strategy code using Object-Oriented Programming (OOP) principles to enhance the backtesting process. This approach will modularize the code, improve its scalability, and make it easier to integrate new features like custom strategies, risk management, and performance evaluation. The refactor will also facilitate cleaner, more maintainable code for future development.
