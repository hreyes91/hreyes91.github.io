---
title: "CaloMan: Fast Generation of Calorimeter Showers with Density Estimation on Learned Manifolds"
collection: publications
category: conferences
permalink: /publication/2022-caloman
date: 2022-01-01
venue: "NeurIPS ML for Physical Sciences Workshop"
paperurl: "https://arxiv.org/abs/2211.15380"
citation: "Caterini, A. L., et al., Reyes-González, H. (2022). 'CaloMan: Fast Generation of Calorimeter Showers with Density Estimation on Learned Manifolds.' NeurIPS ML4PS."
---

Precision measurements and new physics searches at the Large Hadron Collider require efficient simulations of particle propagation and interactions within the detectors. The most computationally expensive simulations involve calorimeter showers. Advances in deep generative modelling - particularly in the realm of high-dimensional data - have opened the possibility of generating realistic calorimeter showers orders of magnitude more quickly than physics-based simulation. However, the high-dimensional representation of showers belies the relative simplicity and structure of the underlying physical laws. This phenomenon is yet another example of the manifold hypothesis from machine learning, which states that high-dimensional data is supported on low-dimensional manifolds. We thus propose modelling calorimeter showers first by learning their manifold structure, and then estimating the density of data across this manifold. Learning manifold structure reduces the dimensionality of the data, which enables fast training and generation when compared with competing methods.
