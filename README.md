📚📖📝 **In-class activities:**


 This is a public and empty repo to collect in-class activities throughout the semester.
 
 - Week 01: **Estimating the $\lambda$ parameter of Box-Cox transformation through grid-search.**
   
   - Generate $y$ from any non-normal continuous distribution with a desired length.
   - Create a vector of sequence for $\lambda$.
   - For each value of in $\lambda$ vector:
      - Apply Box-Cox transformation and get $y_transformed$
      - Assume that $\text{ytransformed} \sim N(\mu, \sigma^2)$
      - Estimate $\hat{\mu}$ and $\hat{\sigma^2}$ through MLE.
      - Then, calculate the value of $log-likelihood(\lambda,\hat{\mu},\hat{\sigma^2})$ based on the pdf of normal distribution.
      - Store the loglik value and corresponding $\lambda$ value.
    - At the end you will have a matrix of two columns: loglik and $\lambda$.
    - Plot loglik vs corresponding $\lambda$ values. Select the $\lambda$ value which gives the largest loglik. That's the optimum lambda.
    - Get the histogram of $\text{ytransformed}$ under optimum lambda. You will see that it has a bell-shaped curve.
    
  - Week 02: **Consider a simple linear regression model. Estimate $\beta_0$ and $\beta_1$ through maximum likelihood estimation method.**
    
    - Hint: You will see that $\hat{\beta_0}^{OLS}=\hat{\beta_0}^{MLE}$ and $\hat{\beta_1}^{OLS}=\hat{\beta_1}^{MLE}$.

  - Week 03: **What is variance inflation factor? How does it help us to detect multicollinearity?**
  
    - At Week 04, we will do MLR analysis with advertisement data through statsmodels. You can check existence of multicollinearity with
    [outliers_influence.variance_inflation_factor](https://www.statsmodels.org/dev/generated/statsmodels.stats.outliers_influence.variance_inflation_factor.html) method.
  
  
