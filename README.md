# 📚 The Markowitz Portfolio Optimization Model

Quantitative Researcher | [Mustafa MAJJI](linkedin.com/in/mustafa-majji-3a59861a2)

***

## :monocle_face: Description

- The Markowitz model is a classical framework for portfolio optimization, introduced by Harry Markowitz in 1952.

- It is based on the principle that investors seek to maximize expected returns while minimizing portfolio volatility, measured by variance.

- Since the model uses variance as a risk metric, it implicitly assumes that asset returns are normally distributed—an assumption that simplifies analysis but may not always reflect real market behavior.

- However, estimating the expected return vector and covariance matrix from historical data introduces estimation errors, which can lead to poor out-of-sample performance. To address this, various regularization techniques have been developed to stabilize portfolio weights and improve robustness.


## 🛠️ Common Regularization Techniques:

- **Weight Constraints :**  Imposing constraints on portfolio weights (e.g., long-only, maximum position size) is itself a form of regularization that helps reduce overfitting.
- **Resampling Methods:** These methods aim to mitigate estimation error by generating multiple alternative scenarios from the original data:
    - **Monte Carlo Simulation**:Asset returns are simulated from a multivariate normal distribution using the sample mean and covariance matrix.
    - **Bootstrap Resampling**:Returns are randomly drawn with replacement from the original dataset to create new samples.
  
- **L1-Constrained Portfolio (Lasso Regularization)**: Adds an L1 penalty on the portfolio weights, promoting sparsity.
- **L2-Constrained Portfolio (Ridge Regularization)**:Adds an L2 penalty on the weights, encouraging smaller and more evenly distributed allocations.

## :mailbox_closed: Contact
For any information, feedback or questions, please [contact me][Mustafa-email]




[Mustafa-email]: mailto:majji1999@gmail.com
