# Transformations
Do variable distribution affect the outcome of the model ?
The answer is it depends on what kind of model are you using.
For tree based models (Random Forest, XGBoost), Neural Networks or even for Support Vector machine the distribution of variable does not affect the outcome of the model but if you are choosing model Like Liner Regression or Logistic regression the variable distribution can play a vital part because one the assumptions in these models is the distribution of variable should follow a Gaussian Distribution(Bell Curve).
What if the variable does not follow Gaussian distribution, then we can transform them to follow a Gaussian distribution by following methods?
1.	Logarithmic Transformation: It only takes the log of the variable, just remember to add 0 because log(0) is indeterminable.
2.	Reciprocal transformation: We just need to take the reciprocal(1/variable) of the variable same as LT we need to add 1 for obvious reasons.
3.	Square Root Transformation: Just raise the variable to the power 0.5.
4.	Exponential Transformation: Just raise the variable to the power 0.2
5.	BoxCox Transformation: Box Cox transformation is an exponent, lambda (λ), which varies from -5 to 5. All values of λ are considered and the optimal value for your data is selected; The “optimal value” is the one which results in the best approximation of a normal distribution curve
