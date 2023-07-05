## 1. Volatility - Standard deviation And Variance

- We compute the average of the square of the deviations from the mean

- This measure is called variance and is computed as follows

    - $\sigma_R^2 = {1\over N} \sum({R_i - \bar R})^2$

    - WHERE $\bar R$ is the arithmetic mean of the returns

- This measure is called Standard Deviation and is computed as follows

    - $\sigma_R = \sqrt{{1\over N} \sum({R_i - \bar R})^2}$

    - WHERE $\bar R$ is the arithmetic mean of the returns

## 2. Annualizing Volatility

- We can't compare the volatility from daily data with the volatility from monthly data

    - $\sigma_{ann} = \sigma_p \sqrt{p} $

    - There are approximately 252 trading days per calendar year
    
- Example 
    - The standard deviation of a stock's daily return series is .1%

        - $.001 * \sqrt{252} = 1.58\% $

## 3. Risk adjusted measures

- We should look at its excess return over the risk free rate

- Return on risk ratio = return / volatility

- Sharpe Ratio (P) = $R_p - R_f \over \sigma_p$
