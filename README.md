# Linear-Regression-model-using-Stochastic-Gradient-Descent
About implement a Linear Regression model using Stochastic Gradient Descent (SGD) from scratch (without use any pre-built ML libraries).
## list 10 types of optimizers
**used in Machine Learning and write a very short
explanation (one line) for each**

Stochastic Gradient Descent (SGD): Updates model parameters using the gradient calculated from a single training example at a time.

Momentum: Helps accelerate SGD in the correct direction by adding a fraction of the previous update vector to the current one.

Nesterov Accelerated Gradient (NAG): A modification of Momentum that calculates the gradient at a "look-ahead" position, often leading to faster convergence.

Adagrad (Adaptive Gradient): Adapts the learning rate for each parameter, performing smaller updates for frequent parameters and larger updates for infrequent ones.

Adadelta: An extension of Adagrad that resolves its aggressively diminishing learning rate by restricting the window of accumulated past gradients.

RMSprop (Root Mean Square Propagation): Also fixes Adagrad's diminishing learning rate by using a moving average of squared gradients instead of summing them all.

Adam (Adaptive Moment Estimation): Combines the ideas of Momentum and RMSprop by using moving averages of both the gradient and its squared value to update parameters.

Adamax: A variant of the Adam optimizer that uses the infinity norm, which can sometimes provide more stable updates.

Nadam (Nesterov-accelerated Adaptive Moment Estimation): Integrates Nesterov accelerated gradient into the Adam optimization algorithm for potentially better performance.

L-BFGS (Limited-memory BFGS): A quasi-Newton method that approximates the second derivative (Hessian matrix) to find a more direct path to the minimum, suitable for smaller datasets.
