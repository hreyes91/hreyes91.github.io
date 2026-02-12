---
title: "Strength in Numbers: Optimal and Scalable Combination of LHC New-Physics Searches"
collection: publications
category: journal
permalink: /publication/2023-strength-in-numbers
date: 2023-01-01
venue: "SciPost Physics"
paperurl: "https://doi.org/10.21468/SciPostPhys.14.4.077"
citation: "Araz, J., et al., Reyes-González, H. (2023). 'Strength in Numbers: Optimal and Scalable Combination of LHC New-Physics Searches.' SciPost Phys. 14, 077."
---

Normalizing flows have emerged as a powerful brand of generative models, as they not only allow for efficient sampling of complicated target distributions but also deliver density estimation by construction. We propose here an in-depth comparison of coupling and autoregressive flows, both based on symmetric (affine) and non-symmetric (rational quadratic spline) bijectors, considering four different architectures: real-valued non-Volume preserving (RealNVP), masked autoregressive flow (MAF), coupling rational quadratic spline (C-RQS), and autoregressive rational quadratic spline (A-RQS). We focus on a set of multimodal target distributions of increasing dimensionality ranging from 4 to 400. The performances were compared by means of different test statistics for two-sample tests, built from known distance measures: the sliced Wasserstein distance, the dimension-averaged one-dimensional Kolmogorov–Smirnov test, and the Frobenius norm of the difference between correlation matrices. Furthermore, we included estimations of the variance of both the metrics and the trained models. Our results indicate that the A-RQS algorithm stands out both in terms of accuracy and training speed. Nonetheless, all the algorithms are generally able, without too much fine-tuning, to learn complicated distributions with limited training data and in a reasonable time of the order of hours on a Tesla A40 GPU. The only exception is the C-RQS, which takes significantly longer to train, does not always provide good accuracy, and becomes unstable for large dimensionalities. All algorithms were implemented using TensorFlow2 and TensorFlow Probability and have been made available on GitHub.
