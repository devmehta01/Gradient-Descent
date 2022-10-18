# Gradient-Descent
This is a program to calculate Gradient Descent for a linear regression problem.

A linear function is defined as f(x) = mx+c.
I randomly chose values for m and c and used these values to create a dataset around this line (mx+c) so that the dataset is almost linear.

The aim is to learn the weights w and b such that they come close to m and c that define the actual line. I randomly initialized w and b with some small non-zero values. The learning rate is set to 0.005 and number of epochs is set to 1000. Gradient descent is performed by finding the derivatives of the weight and the bias and then using these derivatives to perform the weight updates.

We finally use the learned w and b to plot the line along with the dataset and we can observe that the line fits the dataset quite well.
