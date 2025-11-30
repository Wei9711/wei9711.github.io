---
title: "Learning from the Dark: Boosting Graph Convolutional Neural Networks with Diverse Negative Samples"
collection: publications
category: conferences
permalink: /publication/2022-02-22-learning-from-the-dark
excerpt: 'We propose D2GCN, a method that uses Determinant Point Process (DPP) to select diverse negative samples for graph convolutional neural networks, improving node representation learning and alleviating over-smoothing.'
date: 2022-02-22
venue: 'AAAI 2022'
paperurl: 'https://doi.org/10.1609/aaai.v36i6.20608'
code: 'https://github.com/Wei9711/NegGCNs'
# citation: 'Wei Duan, Junyu Xuan, Maoying Qiao, Jie Lu. (2022). &quot;Learning from the Dark: Boosting Graph Convolutional Neural Networks with Diverse Negative Samples.&quot; <i>Proceedings of the AAAI Conference on Artificial Intelligence</i>, 36(6), 6550-6558.'
---
This paper introduces D2GCN (DFS-DPP-GCN), a novel approach that incorporates diverse negative samples into graph convolutional neural networks. Unlike traditional GCNs that only use positive samples (neighboring nodes), we leverage the Determinant Point Process (DPP) to select diverse negative samples from non-neighboring nodes. This helps improve the quality of node representations and alleviates the over-smoothing problem in deep GCNs.

The key innovation is using DFS paths to explore the "dark world" of non-neighboring nodes and then applying DPP to select a diverse set of negative samples that provide contrasting information to the positive samples while maximizing information diversity.
