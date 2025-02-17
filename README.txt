Description: In this project I have implemented the gradient descent algorithm to train a neural network. The algorithm makes use of backpropagation, a technique used to optimize a loss function in neural networks.

What I learned:

Python:
- It is possible to perform operations on objects by creating methods such as __add__, __mul__, and __pow__.
- __call__ is a method that behaves like a mathematical function.
- Graphviz is a library that is used to visualize graphs.
- PyTorch is a library used for deep learning.
    - PyTorch's special data structures called tensors can be used to encode the inputs and parameters of the neural network.

Math:
- AP Calculus concepts, specifically derivatives and the chain rule, are at the heart of backpropagation. As someone who has taken an AP Calculus course, it's amazing to see real world applications of the content I have studied!
- The hyperbolic function tanh is used as an activation function in a neural network.

AI:
- A neural network is simply a complex mathematical function.
- An example of a neural network is a multilayer perceptron (MLP).
    - An MLP has layers and each layer has neurons.
- A neuron in a neural network contains a set of parameters (weights) for each input it receives, a bias value, and an activation function.
- Training process loop using gradient descent algorithm
    - Perform forward pass
        - Weighted sum of all input values
        - Final output: predictions
    - Calculate loss
        - Ex: mean-squared error (MSE)
    - Perform backpropagation
        - Calculates gradient of each parameter using chain rule of calculus
    - Update parameters by a small amount to reduce loss
        - Learning rate
            - Too large: more efficient, risk overstepping
            - Too small: higher accuracy, lower efficiency
        - Learning rate can be changed adaptively
    - Repeat process until desired accuracy is achieved
