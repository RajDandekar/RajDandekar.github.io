---
title: "Bayesian Neural Ordinary Differential Equations"
collection: talks
type: "Talk"
permalink: /talks/BayesianNeuralODE
venue: "Languages for Inference (LAFI)"
date: 2021-01-22
location: "remote"
---
[Talk](https://www.youtube.com/watch?v=Rw-CcL_RQQ8)

Recently, Neural Ordinary Differential Equations has emerged as a powerful framework for modeling physical simulations without explicitly defining the ODEs governing the system, but learning them via machine learning. However, the question: Can Bayesian learning frameworks be integrated with Neural ODEs to robustly quantify the uncertainty in the weights of a Neural ODE? remains unanswered. In an effort to address this question, we demonstrate the successful integration of Neural ODEs with two methods of Bayesian Inference: (a) The No-U-Turn MCMC sampler (NUTS) and (b) Stochastic Langevin Gradient Descent (SGLD). We test the performance of our Bayesian Neural ODE approach on classical physical systems, as well as on standard machine learning datasets like MNIST, using GPU acceleration. Finally, considering a simple example, we demonstrate the probabilistic identification of model specification in partially-described dynamical systems using universal ordinary differential equations. Together, this gives a scientific machine learning tool for probabilistic estimation of epistemic uncertainties.
