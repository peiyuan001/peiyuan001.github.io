---
title: "Model Inversion Attacks on Homogeneous and Heterogeneous Graph Neural Networks"
collection: publications
category: conferences
permalink: /publication/2023-conference-LiuRY
excerpt: ''
date: 2023-10-19
venue: 'International Conference on Security and Privacy in Communication Systems'
paperurl: 'https://arxiv.org/pdf/2310.09800'
citation: 'Renyang Liu, Wei Zhou, Jinhong Zhang, Xiaoyuan Liu, Peiyuan Si, Haoran Li, “Model Inversion Attacks on Homogeneous and Heterogeneous Graph Neural Networks.” International Conference on Security and Privacy in Communication Systems, 2023.'
---
Abstract: Recently, Graph Neural Networks (GNNs), including Homogeneous Graph Neural Networks (HomoGNNs) and Heterogeneous Graph Neural Networks (HeteGNNs), have made remarkable progress in many physical scenarios, especially in communication applications. Despite achieving great success, the privacy issue of such models has also received considerable attention. Previous studies have shown that given a well-fitted target GNN, the attacker can reconstruct the sensitive training graph of this model via model inversion attacks, leading to significant privacy worries for the AI service provider. We advocate that the vulnerability comes from the target GNN itself and the prior knowledge about the shared properties in real-world graphs. Inspired by this, we propose a novel model inversion attack method on HomoGNNs and HeteGNNs, namely HomoGMI and HeteGMI. Specifically, HomoGMI and HeteGMI are gradient-descent-based optimization methods that aim to maximize the cross-entropy loss on the target GNN and the 1st and 2ndorder proximities on the reconstructed graph. Notably, to the best of our knowledge, HeteGMI is the first attempt to perform model inversion attacks on HeteGNNs. Extensive experiments on multiple benchmarks demonstrate that the proposed method can achieve better performance than the competitors.