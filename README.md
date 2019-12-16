# Momentum in Machine Learning

This repo contains my implementation of basic optimization algorithms and it application on basic dataset from sklearn. This may not be optimal implementation.
I only looked at the most common optimizer that use the concept of momentum.
For better explaination and simpler mathematical explaination and reason why we have variant optimization algorithm, please check the Momentum in ML.pdf file, which accompany this code.

### Gradient Descent
The algorithm has many virtues, but speed is not one of them. It is simple — when optimizing a smooth function ff, we make a small step in the gradient direction.
For a step-size small enough, gradient descent makes a monotonic improvement at every iteration. It always converges, albeit to a local minimum. And under a few weak curvature conditions it can even get there at an exponential rate.

### Classic Momentum

Simply put, the momentum algorithm helps us progress faster in the neural network, negatively or positively, to the ball analogy. This helps us get to a local minimum faster.

### Nesterov Accelerated Gradient (NAG)

Classic momentum is like a ball that is rolling down a hill, blindly following the slope. This is not satisfactory for us, we'd like to have a smarter ball, a ball that has a notion of where it is going so that it knows when to slow down before the hill slopes up again.
Nesterov accelerated gradient (NAG) is a way to give our momentum term this kind of superpower.

### RMSprop
RMSprop is an unpublished, adaptive learning rate method proposed by Geoff Hinton in Lecture 6e of his Coursera Class.

### ADAM
Adam is another adaptive learning rate that is basically combining the idea of classical momentum with RMSprop.



