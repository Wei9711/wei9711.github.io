---
permalink: /
title: "Wei Duan"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! I am a PhD student at the [University of Technology Sydney](https://www.uts.edu.au/), working under the supervision of [Prof. Jie Lu](https://www.uts.edu.au/staff/jie.lu) and [Dr. Junyu Xuan](https://www.uts.edu.au/staff/junyu.xuan).

Research Interests
======
## Graph-based MARL

My work on Multi-agent Reinforcement Learning (MARL) focuses on addressing coordination challenges in cooperative multi-agent systems. The core idea is **learning dynamic effective graphs in MARL**, where graph-based coordination mechanisms capture agent dependencies and enable effective knowledge exchange through adaptive interaction structures.

<details>
<summary><strong style="font-size: 0.85em;">Related Publications</strong></summary>

<div markdown="1">

- **[LTS-CG (IEEE TNNLS 2025)](/publication/2025-08-01-latent-temporal-sparse-coordination-graph)**: Proposed a latent temporal sparse coordination graph method that infers sparse coordination graphs from historical observations, addressing limitations of existing graph learning methods that rely solely on one-step observations. The approach incorporates Predict-Future and Infer-Present mechanisms to construct temporal graphs, promoting effective agent collaboration. [[Paper](https://doi.org/10.1109/TNNLS.2024.3513402)] [[Code](https://github.com/Wei9711/LTSCG)]

- **[GACG (IJCAI 2024)](/publication/2024-08-03-group-aware-coordination-graph)**: Proposed a group-aware coordination graph method that captures both agent-pair relations and group-level dependencies from behavior patterns. The approach uses graph convolution for information exchange and introduces a group distance loss to promote group cohesion and specialization. [[Paper](https://www.ijcai.org/proceedings/2024/434)] [[Code](https://github.com/Wei9711/GACG)]

- **[BayesG (NeurIPS 2025)](/publication/2025-12-01-bayesian-ego-graph-inference)**: Proposed a decentralized actor-critic framework for networked MARL that learns sparse, context-aware interaction structures via Bayesian variational inference. Each agent operates over an ego-graph and samples a latent communication mask to guide message passing and policy computation, enabling agents to jointly learn both interaction topology and decision-making strategies. [[Paper](https://openreview.net/forum?id=3qeTs05bRL)] [[Code](https://github.com/Wei9711/BayesG)]

- **[BVME (AAMAS 2026)](/publication/2026-05-01-bandwidth-constrained-variational-message-encoding)**: Introduced a bandwidth-constrained variational message encoding module that treats inter-agent messages as samples from Gaussian posteriors regularized via KL divergence, enabling principled control over communication bandwidth while preserving coordination performance in cooperative MARL. [[Paper](https://doi.org/10.65109/QXVZ8292)]
</div>

</details>

## Diverse Negative Sampling in GNNs

My work on Graph Neural Networks (GNNs) focuses on addressing fundamental limitations of traditional message-passing GNNs, particularly over-smoothing and over-squashing problems. The core idea is **using Determinant Point Process (DPP) to achieve diverse negative sampling**, which helps alleviate these problems by incorporating contrasting information from non-neighboring nodes into graph convolution operations. 

<details>
<summary><strong style="font-size: 0.85em;">Related Publications</strong></summary>

<div markdown="1">

- **[D2GCN (AAAI 2022)](/publication/2022-02-22-learning-from-the-dark)**: Introduced a Determinant Point Process (DPP)-based approach using DFS paths to select diverse negative samples from non-neighboring nodes, improving node representation learning. [[Paper](https://doi.org/10.1609/aaai.v36i6.20608)] [[Code](https://github.com/Wei9711/NegGCNs)]

- **[SDGCN (IEEE TNNLS 2024)](/publication/2024-12-01-gcn-diverse-negative-samples)**: Proposed a shortest-path-based method with decomposed DPP to efficiently obtain diverse negative samples, significantly improving computational efficiency while maintaining performance. [[Paper](https://doi.org/10.1109/TNNLS.2023.3312307)] [[Code](https://github.com/Wei9711/NegGCNs)]

- **[Layer-diverse Negative Sampling (TMLR 2024)](/publication/2024-08-01-layer-diverse-negative-sampling)**: Developed a layer-diverse negative sampling framework that uses space-squeezing techniques to achieve layer-wise diversity in multi-layer GNNs, dynamically changing graph topology to enhance expressiveness and reduce over-squashing. [[Paper](https://openreview.net/forum?id=WOrdoKbxh6)]

</div>

</details>

Education
======
* **PhD in Computer Science**, University of Technology Sydney, 2022 – Present
* **M.S. in Computer Science**, University of Technology Sydney, 2020 – 2022
* **B.S. in Computer Science**, Tongji University, 2016 – 2020

<!-- News
======
* [Add your recent news, awards, or updates here] -->
