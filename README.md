# Understanding-Machine-Learning
Look everything in machine learning from a statistical point of view.
Main idea is to compute posterior distribution, maxmimum log likelihood or maximum a posterior. Prior likeliihood is generally taken as a normal distribution for regression and multivariate gaussian distribution for classification. 

### 1.linear regression
Can be solved using bayesian inference where likelihood p(y|x) is considered as a normal distribution, prior is multivariate gaussian distribution of identity variance
Mean square loss is used to calulate a maximum log likelihood of normal distribution. 
### 2. Non linear regression:
1. Generalized linear model:
   apply a feature map on data such that it can be easily differentiate using hyperplane. We can use kernel tricks to do so. Example are Guassian processes and SVM. 
   Note: Guassian process is equivalent to single layer of neural network with infinity neurons.
2. Approximate Non linear function:
   We can use multilayer neural network to approximate the function. The Universal Approximation Theorem states that a neural network with 1 hidden layer can approximate    any continuous function for inputs within a specific range. 
