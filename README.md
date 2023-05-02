# Applying Linear regression with gradient descent and MSE loss function from scratch :-

## Linear regression
In statistics, linear regression is a linear approach to modelling the relationship between a dependent variable and one or more independent variables. Let X be the independent variable and Y be the dependent variable. We will define a linear relationship between these two variables as follows:

![alt text](https://www.reneshbedre.com/assets/posts/reg/reg_front.svg)

![alt text](https://miro.medium.com/v2/resize:fit:1400/1*GSAcN9G7stUJQbuOhu0HEg.png)

## MSE Loss Function 
The loss is the error in our predicted value of m and c. Our goal is to minimize this error to obtain the most accurate value of m and c. We will use the mean square error function.

![alt text](https://bigdatafinance.tw/images/20190613_9.png)

## Gradient Descent
Gradient Descent is known as one of the most commonly used optimization algorithms to train machine learning models by means of minimizing errors between actual and expected results. Optimization algorithm refers to the task of minimizing/maximizing an objective function f(x) parameterized by x. Similarly, in machine learning, optimization is the task of minimizing the cost function parameterized by the model's parameters. 

Gradient descent is an iterative optimization algorithm to find the minimum of a function. Here that function is our Loss Function.

So starting with random weights (m, b), get the derivative of the loss function for each of them, then update them.

![alt text](https://static.javatpoint.com/tutorial/machine-learning/images/gradient-descent-in-machine-learning1.png)

### Learning rate

Determines how large the step is

![alt text](https://www.i2tutorials.com/wp-content/media/2019/09/Neural-network-34-i2tutorials.png)
