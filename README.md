# Benchmarking uncertainty estimation methods on 1D functions and comparison with Gaussian Process models.

This repository contains implementations(experimental source codes) of the following uncertainty estimation methods:
* A General Framework for Uncertainty Estimation in Deep Learning [MCDO_ADF](https://arxiv.org/abs/1907.06890)
* Deep Evidential Regression [DER](https://arxiv.org/abs/1910.02600).
* Homoscedastic and Heteroscedastic Gaussian Process (GP) models

The methods are evaluated the following 1D functions on Negative-Log-Likelihood(NLL), Explained-Variance(EVA) and Root-Mean-Squared-Error(RMSE) with an intent to compare and understand them better:
* $y=sin(3x)/3x$
* $y=0.1x^3+$
* $y=-(1+x)sin(1.2x)$

In order to view outputs of each methods, please uncomment the cell with corresponding function definitions and provide plot parameters accordingly.

More structured version of these source code implementations will be available soon.

Note: A portion of MCDO_ADF's implementation was taken from its [author's repository](https://github.com/mattiasegu/uncertainty_estimation_deep_learning) and loss function used in DER's notebook was taken from Deebul Nair's [blog](https://deebuls.github.io/devblog/about/).
