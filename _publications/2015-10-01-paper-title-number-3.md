---
title: "Bayesian Neural Ordinary Differential Equations"
collection: publications
permalink: /publications/Bayesian_NeuralODE
venue: "Languages for Inference (LAF1) 21"
date: 2021-01-22
citation: '<b>Raj Dandekar</b>,  Vaibhav Dixit, Mohamed Tarek, Aslan Garcia-Valadez, Chris Rackauckas<i>LAFI 2021.</i>'
---

[[PDF]](https://RajDandekar.github.io/files/Bayesian_NeuralODE.pdf)

## Abstract
Recently, Neural Ordinary Differential Equations has emerged as a powerful framework for modeling physical simulations without explicitly defining the ODEs governing the system, but instead learning them via machine learning. However, the question: "Can Bayesian learning frameworks be integrated with Neural ODE's to robustly quantify the uncertainty in the weights of a Neural ODE?" remains unanswered. In an effort to address this question, we primarily evaluate the following categories of inference methods: (a) The No-U-Turn MCMC sampler (NUTS), (b) Stochastic Gradient Hamiltonian Monte Carlo (SGHMC) and (c) Stochastic Langevin Gradient Descent (SGLD). We demonstrate the successful integration of Neural ODEs with the above Bayesian inference frameworks on classical physical systems, as well as on standard machine learning datasets like MNIST, using GPU acceleration. On the MNIST dataset, we achieve a posterior sample accuracy of 98.5% on the test ensemble of 10,000 images. Subsequently, for the first time, we demonstrate the successful integration of variational inference with normalizing flows and Neural ODEs, leading to a powerful Bayesian Neural ODE object. Finally, considering a predator-prey model and an epidemiological system, we demonstrate the probabilistic identification of model specification in partially-described dynamical systems using universal ordinary differential equations. Together, this gives a scientific machine learning tool for probabilistic estimation of epistemic uncertainties.
