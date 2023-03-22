# Solving ODE using Neural Networks
## About the project
The idea of solving an ODE using a Neural Network was firstly described by Lagaris et al. The insight behind it is basically training a neural network in order to his solution satisfies the conditions required by a differential equation. In other words, we need to find a function whose derivative satisfies the ODE conditions. In this repo, we will be going through the underlying mathematical foundations of this concept and then we will implement it using TensorFlow 2.0.
We use a one layer NN in which each neuron have differrent activation function and work as bases for making the desired function and we try to predict weights for each neouron to construct the function which satisfies our equation:

<img src="https://github.com/hosnahoseini/Solve_ODE_using_NN/blob/main/description.PNG"></img>
### Files:
- `ODE_NN_step1`: Implement the NN with sigmoid activation functions
- `1.2.ODE_chebyshev`: A try to implement the NN with chebyshev activation functions

### Libraries used:
- tensorflow 
- numpy
- matplotlib
