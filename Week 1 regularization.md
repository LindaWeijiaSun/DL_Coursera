## Why regularization can reduce overfitting?
**Regularization term  is added to coset function `J`**
Reason 1: 
lamda is large, in order to make J smaller, we penalize w nearly into 0 --> which means the coefficient of many hidden units are 0 --> almost like a logistic regression unit
Reason 2:
take activation function `tanh` for example. Note the in `tanh` if `z` is very small, the shape of the function is nearly linear. So same logic, lamda is large --> w is small --> z=wx+b, z is small --> activation function become linear function. If the activation function is linear, no effects no matter how deep the NN is.
