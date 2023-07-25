# Portfolio Risk Management: Covariance Matrix Shrinkage
Welcome to my GitHub repository! This project revolves around an important concept in portfolio risk management – covariance matrix shrinkage. We have implemented this concept in Python using financial data fetched in real-time from Yahoo Finance.

Financial markets are highly volatile and managing investment portfolio risk is crucial for any investor. Covariance matrix is a fundamental building block for many portfolio optimization algorithms as it captures the volatility in the market and the co-movements of different assets.

However, estimating an accurate covariance matrix is challenging due to the high dimensionality and noisy nature of financial data. A small sample size, outliers, and extreme events can make our covariance matrix estimate unreliable, which can lead to sub-optimal risk assessments.

To address this, I implement a technique called covariance matrix shrinkage. This technique shrinks the sample covariance matrix towards a structured estimator, improving its condition and reducing the chance of extreme weights on a particular asset, hence leading to a more diversified and potentially lower risk portfolio.
