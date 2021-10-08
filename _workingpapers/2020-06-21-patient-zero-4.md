---
title: "Finding Patient Zero: Learning Contagion Source with Graph Neural Networks"
collection: workingpapers
permalink: /workingpapers/2020-06-21-patient-zero-4
excerpt: ''
date: 2020-06-21
venue: 'arXiv, 2006.11913'
paperurl: 'https://arxiv.org/abs/2006.11913'
citation: 'Shah, C., Dehmamy, N., Perra, N., Chinazzi, M., Barabási, A. L., Vespignani, A., & Yu, R. (2020). arXiv, 2006.11913.'
---

<br/><img src='/images/patient-zero.png'>

# Abstract
Locating the source of an epidemic, or patient zero (P0), can provide critical insights into the infection's transmission course and allow efficient resource allocation. Existing methods use graph-theoretic centrality measures and expensive message-passing algorithms, requiring knowledge of the underlying dynamics and its parameters. In this paper, we revisit this problem using graph neural networks (GNNs) to learn P0. We establish a theoretical limit for the identification of P0 in a class of epidemic models. We evaluate our method against different epidemic models on both synthetic and a real-world contact network considering a disease with history and characteristics of COVID-19. We observe that GNNs can identify P0 close to the theoretical bound on accuracy, without explicit input of dynamics or its parameters. In addition, GNN is over 100 times faster than classic methods for inference on arbitrary graph topologies. Our theoretical bound also shows that the epidemic is like a ticking clock, emphasizing the importance of early contact-tracing. We find a maximum time after which accurate recovery of the source becomes impossible, regardless of the algorithm used.


[Read working paper here](https://arxiv.org/abs/2006.11913)

Recommended citation: Shah, C., Dehmamy, N., Perra, N., Chinazzi, M., Barabási, A. L., Vespignani, A., & Yu, R. (2020). &quot;Finding Patient Zero: Learning Contagion Source with Graph Neural Networks&quot;. <i>arXiv</i>, 2006.11913.