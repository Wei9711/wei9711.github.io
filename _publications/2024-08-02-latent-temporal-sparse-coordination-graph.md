---
title: "Inferring Latent Temporal Sparse Coordination Graph for Multiagent Reinforcement Learning"
collection: publications
category: manuscripts
permalink: /publication/2025-08-01-latent-temporal-sparse-coordination-graph
excerpt: 'We propose LTS-CG, a method that infers latent temporal sparse coordination graphs for MARL by leveraging historical observations, addressing limitations of existing graph learning methods and improving agent coordination.'
date: 2025-08-01
venue: 'IEEE Transactions on Neural Networks and Learning Systems'
paperurl: 'https://doi.org/10.1109/TNNLS.2024.3513402'
code: 'https://github.com/Wei9711/LTSCG'
# citation: 'Wei Duan, Jie Lu, Junyu Xuan. (2025). &quot;Inferring Latent Temporal Sparse Coordination Graph for Multiagent Reinforcement Learning.&quot; <i>IEEE Transactions on Neural Networks and Learning Systems</i>, 36(8), 14358-14370.'
---
Effective agent coordination is crucial in cooperative multiagent reinforcement learning (MARL). While agent cooperation can be represented by graph structures, prevailing graph learning methods in MARL are limited. They rely solely on one-step observations, neglecting crucial historical experiences, leading to deficient graphs that foster redundant or detrimental information exchanges. In addition, high computational demands for action-pair calculations in dense graphs impede scalability. To address these challenges, we propose inferring a latent temporal sparse coordination graph (LTS-CG) for MARL. The LTS-CG leverages agents' historical observations to calculate an agent-pair probability matrix, where a sparse graph is sampled from and used for knowledge exchange between agents, thereby simultaneously capturing agent dependencies and relationship uncertainty. The computational complexity of this procedure is only related to the number of agents. This graph learning process is further augmented by two innovative characteristics: Predict-Future, which enables agents to foresee upcoming observations, and Infer-Present, ensuring a thorough grasp of the environmental context from limited data. These features allow LTS-CG to construct temporal graphs from historical and real-time information, promoting knowledge exchange during policy learning and effective collaboration. Graph learning and agent training occur simultaneously in an end-to-end manner. Our demonstrated results on the StarCraft II benchmark underscore LTS-CG's superior performance.

