---
title: "Quantum embeddings for machine learning"
collection: publications
permalink: /publications/Embeddings
venue: "ArXiv"
date: 2020-01-10 
citation: 'Seth Lloyd, et al. arXiv:2001.03622 (2020)'
---

[[ArXiv2020]](https://arxiv.org/pdf/2001.03622.pdf)

## Abstract
Quantum classifiers are trainable quantum circuits used as machine learning models. The first part of the circuit implements a quantum feature map that encodes classical inputs into quantum states, embedding the data in a high-dimensional Hilbert space; the second part of the circuit executes a quantum measurement interpreted as the output of the model. Usually, the measurement is trained to distinguish quantum-embedded data. We propose to instead train the first part of the circuit---the embedding---with the objective of maximally separating data classes in Hilbert space, a strategy we call quantum metric learning. As a result, the measurement minimizing a linear classification loss is already known and depends on the metric used: for embeddings separating data using the l1 or trace distance, this is the Helstrom measurement, while for the l2 or Hilbert-Schmidt distance, it is a simple overlap measurement. This approach provides a powerful analytic framework for quantum machine learning and eliminates a major component in current models, freeing up more precious resources to best leverage the capabilities of near-term quantum information processors.
