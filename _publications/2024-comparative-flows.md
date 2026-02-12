---
title: "Comparative Study of Coupling and Autoregressive Flows through Robust Statistical Tests"
collection: publications
category: manuscripts
permalink: /publication/2024-comparative-flows
date: 2024-01-01
venue: "Symmetry"
paperurl: "https://doi.org/10.3390/sym16080942"
citation: "Coccaro, A., Letizia, M., Reyes-González, H., Torre, R. (2024). 'Comparative Study of Coupling and Autoregressive Flows through Robust Statistical Tests.' Symmetry 16, 942."
---

Normalizing flows have emerged as a powerful brand of generative models, as they not only allow for efficient sampling of complicated target distributions but also deliver density estimation by construction. We propose here an in-depth comparison of coupling and autoregressive flows, both based on symmetric (affine) and non-symmetric (rational quadratic spline) bijectors, considering four different architectures: real-valued non-Volume preserving (RealNVP), masked autoregressive flow (MAF), coupling rational quadratic spline (C-RQS), and autoregressive rational quadratic spline (A-RQS). We focus on a set of multimodal target distributions of increasing dimensionality ranging from 4 to 400. The performances were compared by means of different test statistics for two-sample tests, built from known distance measures: the sliced Wasserstein distance, the dimension-averaged one-dimensional Kolmogorov–Smirnov test, and the Frobenius norm of the difference between correlation matrices. Furthermore, we included estimations of the variance of both the metrics and the trained models. Our results indicate that the A-RQS algorithm stands out both in terms of accuracy and training speed. Nonetheless, all the algorithms are generally able, without too much fine-tuning, to learn complicated distributions with limited training data and in a reasonable time of the order of hours on a Tesla A40 GPU. The only exception is the C-RQS, which takes significantly longer to train, does not always provide good accuracy, and becomes unstable for large dimensionalities. All algorithms were implemented using TensorFlow2 and TensorFlow Probability and have been made available on GitHub.
