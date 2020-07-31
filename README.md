# AR_1 Example
Code to estimate marginal hyperparameters of an autoregressive model (order 1).
After transformation - hyperparameters go from skewed to somewhat Gaussian. We approximate transformed hyperparameter with an initial exp(quadratic) approximation, then add a (cubic) correction term to the quadratic to account for any skew.

Code is written in R
