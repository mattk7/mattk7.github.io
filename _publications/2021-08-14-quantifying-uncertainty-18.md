---
title: "Quantifying Uncertainty in Deep Spatiotemporal Forecasting"
collection: publications
permalink: /publications/2021-08-14-quantifying-uncertainty-18
excerpt: ''
date: 2021-08-14
venue: 'KDD 21'
paperurl: 'https://dl.acm.org/doi/10.1145/3447548.3467325'
citation: 'Wu, D., Gao, L., Chinazzi, M., Xiong, X., Vespignani, A., Ma, Y., & Yu, R. (2021). KDD 21: Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining.'
---

<br/><img src='/images/quant-unc.png'>

# Abstract
Deep learning is gaining increasing popularity for spatiotemporal forecasting. However, prior works have mostly focused on point estimates without quantifying the uncertainty of the predictions. In high stakes domains, being able to generate probabilistic forecasts with confidence intervals is critical to risk assessment and decision making. Hence, a systematic study of uncertainty quantification (UQ) methods for spatiotemporal forecasting is missing in the community. In this paper, we describe two types of spatiotemporal forecasting problems: regular grid-based and graph-based. Then we analyze UQ methods from both the Bayesian and the frequentist point of view, casting in a unified framework via statistical decision theory. Through extensive experiments on real-world road network traffic, epidemics, and air quality forecasting tasks, we reveal the statistical and computational trade-offs for different UQ methods: Bayesian methods are typically more robust in mean prediction, while confidence levels obtained from frequentist methods provide more extensive coverage over data variations. Computationally, quantile regression type methods are cheaper for a single confidence interval but require re-training for different intervals. Sampling based methods generate samples that can form multiple confidence intervals, albeit at a higher computational cost.


[Read paper here](https://dl.acm.org/doi/10.1145/3447548.3467325)

Recommended citation: Wu, D., Gao, L., Chinazzi, M., Xiong, X.,  Vespignani, A., Ma, Y., & Yu, R. (2021).  &quot;Quantifying Uncertainty in Deep Spatiotemporal Forecasting&quot;. <i>KDD '21</i>: Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining.

