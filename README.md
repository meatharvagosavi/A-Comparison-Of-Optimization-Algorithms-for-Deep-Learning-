# Optimization Algorithms from Scratch for Deep Learning ⚙️

## Overview

This project implements and compares several popular deep learning optimization algorithms entirely from scratch using Python and NumPy. The implementation is inspired by the research paper **"A Comparison of Optimization Algorithms for Deep Learning"** and aims to provide a practical understanding of how different optimizers affect neural network training performance.

## Implemented Optimizers

* Stochastic Gradient Descent (SGD)
* SGD with Momentum
* Adagrad
* RMSProp
* Adadelta
* Adam
* NAdam (Nesterov-accelerated Adam)

## Dataset

The project uses the **Digits Dataset** from Scikit-Learn:

* 1,797 handwritten digit samples
* 10 output classes (0–9)
* Standardized input features
* One-hot encoded labels

## Features

* Complete optimizer implementations without deep learning frameworks
* Manual forward propagation and backpropagation
* Batch training support
* Accuracy evaluation
* Classification reports
* Confusion matrix generation
* Comparative analysis of optimizer performance

## Tech Stack

* Python
* NumPy
* Scikit-Learn

## Project Structure

```text
├── OptimisationAlgorithms.py
├── Output Results
├── README.md
```

## Results

The project evaluates each optimizer based on:

* Training Loss
* Classification Accuracy
* Convergence Speed
* Stability During Training

The comparison demonstrates how adaptive optimization methods such as Adam, RMSProp, and NAdam generally converge faster and achieve better performance than traditional SGD-based methods.

## Research Reference

Derya Soydaner, *A Comparison of Optimization Algorithms for Deep Learning*, International Journal of Pattern Recognition and Artificial Intelligence, 2020.

## Future Improvements

* CNN implementation from scratch
* CIFAR-10 and MNIST benchmarking
* AMSGrad and AdaMax implementations
* Training visualization and loss curves
* Hyperparameter tuning experiments

## Author

Atharva Gosavi

If you found this project useful, consider giving it a ⭐ on GitHub.
