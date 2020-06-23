## Bias and Variance
high bias: underfitting 
high variance: overfitting

## Solution for high bias (under fitting):
1. Try a bigger network --> can only reduce bias without increasing variance

2. Train a longing time

3*. Change a NN archetechture


## Solution for high variance (over-fitting):
1. More data --> can only reduce variance without increasing bias

2. Regularization (L2, dropout) --> can prenvent overfitting
  
  ### Drop out
  eg, computer vision: pixels are data, you will never have engough data, so always use dropout in **conputer vision** to **prevent over-fitting**.
  #### cost function in dropout
  Implementational tips: turn off dropout to ensure the plot of cost function is decreasing, and then turn on dropout to train.
  
  **Reason**: 
  Use dropout --> cost function is meaningless, since each time the neurons are different. You lose a tool. So first ensure the cost is reducing, and then turn on the dropout.

3*. Change a NN archetechture

## Trade-off
1. Traditionally. reducing one will increase another one
2. But now, DL can help!
