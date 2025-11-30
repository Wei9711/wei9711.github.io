---
title: "Graph Convolutional Neural Networks With Diverse Negative Samples via Decomposed Determinant Point Processes"
collection: publications
category: manuscripts
permalink: /publication/2024-12-01-gcn-diverse-negative-samples
excerpt: 'We propose SDGCN, a method that uses quality-diversity decomposition in determinant point processes (DPPs) with shortest-path-based sampling to efficiently obtain diverse negative samples for graph convolutional neural networks.'
date: 2024-12-01
venue: 'IEEE Transactions on Neural Networks and Learning Systems'
paperurl: 'https://doi.org/10.1109/TNNLS.2023.3312307'
code: 'https://github.com/Wei9711/NegGCNs'
# citation: 'Wei Duan, Junyu Xuan, Maoying Qiao, Jie Lu. (2024). &quot;Graph Convolutional Neural Networks With Diverse Negative Samples via Decomposed Determinant Point Processes.&quot; <i>IEEE Transactions on Neural Networks and Learning Systems</i>, 35(12), 18160-18171.'
---
Graph convolutional neural networks (GCNs) have achieved great success in graph representation learning by extracting high-level features from nodes and their topology. Since GCNs generally follow a message-passing mechanism, each node aggregates information from its first-order neighbor to update its representation. As a result, the representations of nodes with edges between them should be positively correlated and thus can be considered positive samples. However, there are more non-neighbor nodes in the whole graph, which provide diverse and useful information for the representation update. Two non-adjacent nodes usually have different representations, which can be seen as negative samples. Besides the node representations, the structural information of the graph is also crucial for learning. 

In this article, we used quality-diversity decomposition in determinant point processes (DPPs) to obtain diverse negative samples. When defining a distribution on diverse subsets of all non-neighboring nodes, we incorporate both graph structure information and node representations. Since the DPP sampling process requires matrix eigenvalue decomposition, we propose a new shortest-path-base method to improve computational efficiency. Finally, we incorporate the obtained negative samples into the graph convolution operation. The ideas are evaluated empirically in experiments on node classification tasks. These experiments show that the newly proposed methods not only improve the overall performance of standard representation learning but also significantly alleviate over-smoothing problems.

