# myLib
This repository contains the collections of my own implementated programs/libraries
and some third-party programs.

The list are following:
 - sgd: stochastic gradient descent algorithms, including:
   * naive sgd
   * momentum sgd
   * NAG: Nesterov accelerated gradient 
   * Adagrad
   * RMSprop
   * Adadelta
   * Adam
  ![sgd gif](./fig/sgd.gif)

   Note: sgd.py calculate the gradient using the so-called forward mode automatic differentiation method via operator overloading! Please check in sgd/ad directory if you are interested.

To do list:
- [ ] reversed mode automatic differentiation
- [ ] optimized math functions including Remez algorithm
- [ ] monte carlo sampling programs

