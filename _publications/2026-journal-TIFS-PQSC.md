---
title: "Post-Quantum Secure Semantic Communication with Discrete Latent Representations"
collection: publications
category: manuscripts
permalink: publications/2026-journal-TIFS-PQSC
excerpt: ''
date: 2026-02-01
venue: 'IEEE Transactions on Information Forensics and Security '
paperurl: 'https://ieeexplore.ieee.org/document/11570855'
citation: 'Peiyuan Si, Liangxin Qian, Renyang Liu, Jun Zhao, Kwok-Yan Lam, “Post-Quantum Secure Semantic Communication with Discrete Latent Representations”, IEEE Transactions on Information Forensics and Security, vol. 21, 2026.'
---

Abstract: Semantic communication (SemCom) has recently gained attention for its ability to achieve high transmission efficiency with minimal data distortion under limited communication resources. However, the strong correlation between source data and channel input leaves SemCom schemes vulnerable to eavesdropping. Additionally, advances in quantum computing threaten traditional cryptographic methods such as RSA due to Shor’s algorithm. To address these risks, a secure SemCom framework with post-quantum protection is essential. This paper presents a post-quantum secure semantic communication (PQSC) framework by integrating learning with errors (LWE) encryption (widely regarded as quantum-resistant) into a VQ-VAE-based SemCom system. The proposed PQSC framework not only resists quantum attacks but also defends against chosen-plaintext attacks. Experiments show that PQSC consistently outperforms baseline methods across various datasets, channel conditions, and SNR levels. To simulate practical wireless environments, we implement channel coding and modulation using Nvidia Sionna, a GPU-accelerated library for physical layer research. We further examine the trade-off between compression efficiency and computational cost. A downlink use case is modeled to analyze recovery quality, energy consumption, and latency. Our mathematical analysis offers insights into system design and parameter selection for real-world deployment.