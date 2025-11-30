---
title: "Layer-diverse Negative Sampling for Graph Neural Networks"
collection: publications
category: manuscripts
permalink: /publication/2024-08-01-layer-diverse-negative-sampling
excerpt: 'We propose a layer-diverse negative sampling method for GNNs that uses a sampling matrix within a determinantal point process to generate diverse negative samples, improving learning performance and mitigating over-smoothing and over-squashing issues.'
date: 2024-08-01
venue: 'Transactions on Machine Learning Research'
paperurl: 'https://openreview.net/forum?id=WOrdoKbxh6'
# citation: 'Wei Duan, Jie Lu, Yu Guang Wang, Junyu Xuan. (2024). &quot;Layer-diverse Negative Sampling for Graph Neural Networks.&quot; <i>Transactions on Machine Learning Research</i>, 2024.'
---
Graph neural networks (GNNs) are a powerful solution for various structure learning applications due to their strong representation capabilities for graph data. However, traditional GNNs, relying on message-passing mechanisms that gather information exclusively from first-order neighbours (known as positive samples), can lead to issues such as over-smoothing and over-squashing. To mitigate these issues, we propose a layer-diverse negative sampling method for message-passing propagation. This method employs a sampling matrix within a determinantal point process, which transforms the candidate set into a space and selectively samples from this space to generate negative samples. To further enhance the diversity of the negative samples during each forward pass, we develop a space-squeezing method to achieve layer-wise diversity in multi-layer GNNs. Experiments on various real-world graph datasets demonstrate the effectiveness of our approach in improving the diversity of negative samples and overall learning performance. Moreover, adding negative samples dynamically changes the graph's topology, thus with the strong potential to improve the expressiveness of GNNs and reduce the risk of over-squashing.

