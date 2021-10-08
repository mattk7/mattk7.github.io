---
title: "Deep Learning + Epidemic Modeling"
excerpt: "<center><img src='/images/epi-ml.png' width='30%'><img src='/images/epi-ml-2.png' width='30%'></center> <br/>We combine traditional epidemic modeling approaches with _state-of-the-art_ machine learning and deep learning methods to improve forecasts, accelerate large-scale stochastic simulations, and reconstruct the early stages of an epidemic. [Read more..](/current_projects/02-epi-ML/)"
collection: portfolio
---

<center><img src='/images/epi-ml.png' width='50%'><img src='/images/epi-ml-2.png' width='40%'></center>
<br/>

In this project, we combine traditional mechanistic epidemic models with _state-of-the-art_ machine learning and deep learning approaches to: 1) improve epidemic forecasting; 2) accelerate large-scale stochastic simulations; and 3) reconstruct the early stages of an epidemic.

[_Forecast_] We combine the Global Epidemic and Mobility model (GLEAM) and the higher resolution Local Epidemic and Mobility model for the United States (LEAM-US) with _state-of-the-art_ machine learning frameworks to enhance the prediction performance of the stand-alone mechanistic models by allowing to reduce the bias that exists between the model predictions and the observed noisy surveillance data. 

[_Accelerate_] Stochastic simulations of large-scale, spatiotemporal, age-structured epidemic models are computationally expensive at fine-grained resolution. In this project, we develop a novel spatiotemporal neural process model to mimic LEAM-US dynamics. Our model automatically infers the latent process which describes the intrinsic uncertainty of the epidemic simulator. In practice, we demonstrate our framework can faithfully imitate the behavior of a complex infectious disease simulator with a small number of examples, enabling rapid simulation and scenario exploration.

[_Reconstruct_] Locating the source of an epidemic, or patient zero, can provide critical
insights into the infection’s transmission course and allow efficient resource allocation. In this work, we establish a theoretical limit for the identification of patient zero in
a class of epidemic models, and we evaluate our method against different epidemic models on both synthetic and a real-world contact network considering a disease with history and characteristics of COVID-19.


<br/>

Online dashboards:

- [COVID-19 DeepGLEAM Forecasting dashboard](https://datascience.ucsd.edu/COVID19/)

<br/>


Papers:
- Wu, D., Gao, L., Xiong, X., __Chinazzi, M.__, Vespignani, A., Ma, Y.A., & Yu, R. Quantifying Uncertainty in Deep Spatiotemporal Forecasting (2021). ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD), 2021. <br/> [Read paper here](https://dl.acm.org/doi/abs/10.1145/3447548.3467325)

- Wu, D., __Chinazzi, M.__, Vespignani, A., Ma, Y. A., & Yu, R. (2021). Accelerating Stochastic Simulation with Interactive Neural Processes. arXiv preprint arXiv:2106.02770.<br/> [Read working paper here](https://arxiv.org/abs/2106.02770)

- Wu, D., Gao, L., Xiong, X., __Chinazzi, M.__, Vespignani, A., Ma, Y., & Yu, R. (2021).  DeepGLEAM: a hybrid mechanistic and deep learning model for COVID-19 forecasting. arXiv preprint arXiv:2102.06684.<br/> [Read working paper here](https://arxiv.org/abs/2102.06684)

- Shah, C., Dehmamy, N., Perra, N., __Chinazzi, M.__, Barabási, A. L., Vespignani, A., & Yu, R. (2020). Finding Patient Zero: Learning Contagion Source with Graph Neural Networks. arXiv preprint arXiv:2006.11913.<br/> [Read working paper here](https://arxiv.org/abs/2006.11913)

- Poirier, C., Liu, D., Clemente, L., Ding, X., __Chinazzi, M.__, Davis, J.T., Vespignani, A., & Santillana, M. (2020). Real-time forecasting of the COVID-19 outbreak in Chinese provinces: machine learning approach using novel digital data and estimates from mechanistic models. Journal of Medical Internet Research, 22(8), e20285.<br/> [Read paper here](https://www.jmir.org/2020/8/e20285/)
