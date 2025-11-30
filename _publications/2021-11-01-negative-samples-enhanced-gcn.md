---
title: "Negative Samples-enhanced Graph Convolutional Neural Networks"
collection: publications
category: conferences
permalink: /publication/2021-11-01-negative-samples-enhanced-gcn
excerpt: 'We propose NegGCNs, where negatively sampled nodes are directly incorporated into the message passing mechanism and used to update new node feature vectors, improving graph node classification accuracy.'
date: 2021-11-01
venue: 'ISKE 2021'
paperurl: 'https://doi.org/10.1109/ISKE54062.2021.9755440'
---
Graph neural networks (GNNs) have shown great success in graph representation learning by extracting high-level features from nodes and their topology. Many previous studies have used the message passing mechanism to fuse neighborhood information with an assumption that neighbors should share some similar behaviors and then have positive correlations. Therefore, the neighbor nodes can be considered as positive samples and most of existing methods can be viewed as using these positive samples to update new feature vectors. Along with these positive samples, there are also some hidden negative samples (non-neighborhood nodes) which also contains information for a certain node but has been ignored so far. In addition, existing studies on negative sampling for graphs only fuse the sampling results into the loss function for the model training.

In this paper, we propose a Negative Samples-enhanced Graph Convolutional Neural Networks (NegGCNs), where the negatively sampled nodes are directly incorporated into the message passing mechanism and used to update new node feature vectors. We further investigated the effects of negative sampling rate and the number of negatively sampled nodes on the classification accuracy of graph nodes. Experiments on citation network datasets suggest that the proposed NegGCNs model can improve the accuracy of graph node classification with a specific negative rate compared to GCNs.

