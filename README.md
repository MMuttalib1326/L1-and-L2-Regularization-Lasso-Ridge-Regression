# L1-and-L2-Regularization-Lasso-Ridge-Regression

L1 and L2 regularization are two common techniques used in linear regression models to prevent overfitting and improve the generalization performance of the model. They are often used in the context of Lasso and Ridge regression, respectively.

Lasso Regression (L1 Regularization):

Lasso regression adds the sum of the absolute values of the coefficients as a penalty term to the loss function during training. The objective of Lasso regression is to minimize the following cost function:
Cost function = Sum of squared errors + λ * (sum of absolute values of coefficients)

Ridge Regression (L2 Regularization):


Ridge regression, on the other hand, adds the sum of squared values of the coefficients as a penalty term to the loss function during training. The objective of Ridge regression is to minimize the following cost function:
Cost function = Sum of squared errors + λ * (sum of squared values of coefficients)

both Lasso (L1 regularization) and Ridge (L2 regularization) regression techniques are used to control the complexity of linear regression models and prevent overfitting. Lasso encourages sparsity by driving some coefficients to zero, while Ridge shrinks the coefficients toward zero without setting them exactly to zero. The choice between Lasso and Ridge regularization depends on the specific characteristics of the dataset and the goals of the modeling task. In some cases, a combination of both (Elastic Net) may be employed to benefit from both types of regularization.

![image](https://github.com/MMuttalib1326/L1-and-L2-Regularization-Lasso-Ridge-Regression/assets/64772188/201a74ce-da9f-41e7-90ed-fbabc696109d)


