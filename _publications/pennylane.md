---
title: "PennyLane: Automatic differentiation of hybrid quantum-classical computations"
collection: publications
permalink: /publications/pennylane
venue: "ArXiv"
date: 2022-07-29 
citation: 'Ville Bergholm et al. PennyLane: Automatic differentiation of hybrid quantum-classical computations. 2018'
---

[[ArXiv2022]](https://arxiv.org/abs/1811.04968)

## Abstract
PennyLane is a Python 3 software framework for differentiable programming of quantum computers. The library provides a
unified architecture for near-term quantum computing devices, supporting both qubit and continuous-variable paradigms.
PennyLane’s core feature is the ability to compute gradients of variational quantum circuits in a way that is compatible with
classical techniques such as backpropagation. PennyLane thus extends the automatic differentiation algorithms common in
optimization and machine learning to include quantum and hybrid computations. A plugin system makes the framework
compatible with any gate-based quantum simulator or hardware. We provide plugins for hardware providers including
the Xanadu Cloud, Amazon Braket, and IBM Quantum, allowing PennyLane optimizations to be run on publicly accessible
quantum devices. On the classical front, PennyLane interfaces with accelerated machine learning libraries such as TensorFlow,
PyTorch, JAX, and Autograd. PennyLane can be used for the optimization of variational quantum eigensolvers,
quantum approximate optimization, quantum machine learning models, and many other applications.
