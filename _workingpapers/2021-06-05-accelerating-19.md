---
title: "Accelerating Stochastic Simulation with Interactive Neural Processes"
collection: workingpapers
permalink: /workingpapers/2021-06-05-accelerating-19
excerpt: ''
date: 2021-06-05
venue: 'arXiv, 2106.02770'
paperurl: 'https://arxiv.org/abs/2106.02770'
citation: 'Wu, D., Chinazzi, M., Vespignani, A., Ma, Y. A., & Yu, R. (2021). arXiv, 2106.02770.'
---

<br/><center><img src='/images/epi-ml.png' width="80%"></center>

# Abstract
Stochastic simulations such as large-scale, spatiotemporal, age-structured epidemic
models are computationally expensive at fine-grained resolution. We propose Inter-
active Neural Process (INP), a Bayesian active learning framework to proactively
learn a deep learning surrogate model and accelerate simulation. Our framework is
based on the novel integration of neural process, deep sequence model and active
learning. In particular, we develop a novel spatiotemporal neural process model to
mimic the simulator dynamics. Our model automatically infers the latent process
which describes the intrinsic uncertainty of the simulator. This also gives rise to a
new acquisition function based on the latent information gain. We design Bayesian
active learning algorithms to iteratively query the simulator, gather more data, and
continuously improve the model. We perform theoretical analysis and demonstrate
that our approach reduces sample complexity compared with random sampling in
high dimension. Empirically, we demonstrate our framework can faithfully imitate
the behavior of a complex infectious disease simulator with a small number of
examples, enabling rapid simulation and scenario exploration.



[Read working paper here](https://arxiv.org/abs/2106.02770)

Recommended citation: Wu, D., Chinazzi, M., Vespignani, A., Ma, Y. A., & Yu, R. (2021).  &quot;Accelerating Stochastic Simulation with Interactive Neural Processes&quot;. <i>arXiv</i>, 2106.02770.

