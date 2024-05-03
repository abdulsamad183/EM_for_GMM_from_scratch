# EM Algorithm for Gaussian Mixture Model (GMM)

This project implements the Expectation-Maximization (EM) algorithm for Gaussian Mixture Model (GMM) from scratch in Python. The aim is to provide a deeper understanding of the EM algorithm and its application in clustering via GMM. Additionally, the performance of the custom implementation is compared against the inbuilt functions of the scikit-learn library.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Custom Implementation](#custom-implementation)
- [Performance Comparison](#performance-comparison)

## Introduction

The Gaussian Mixture Model (GMM) is a probabilistic model that represents the presence of subpopulations within an overall population. The EM algorithm is an iterative method for finding maximum likelihood estimates of parameters in statistical models, where the model depends on unobserved latent variables. In this project, we delve into implementing the EM algorithm specifically for GMM from scratch in Python.

## Usage

To use this implementation, simply clone the repository:

```bash
git clone https://github.com/abdulsamad183/EM_for_GMM_from_scratch.git
```

## Dependencies

- Python 3.x
- NumPy
- scikit-learn

## Dataset

The Iris dataset is used for training the GMM and comparing performance. It is a classic dataset widely used for classification and clustering tasks. The dataset consists of 150 samples with 4 features each, representing 3 classes of iris plants.

## Custom Implementation

The custom implementation of the EM algorithm for GMM is located in the .ipynb file. It includes functions for initializing parameters, calculating the expectation step, the maximization step, and iterating until convergence.

## Performance Comparison

The performance of the custom implementation is compared with the inbuilt functions provided by the scikit-learn library. The comparison includes metrics such as convergence rate, and clustering accuracy.
