---
title: "Bayesian Ego-graph Inference for Networked Multi-Agent Reinforcement Learning"
collection: publications
category: conferences
permalink: /publication/2025-12-01-bayesian-ego-graph-inference
excerpt: 'We propose BayesG, a decentralized actor-critic framework that learns sparse, context-aware interaction structures via Bayesian variational inference for networked multi-agent reinforcement learning.'
date: 2025-12-01
venue: 'NeurIPS 2025'
paperurl: 'https://openreview.net/forum?id=3qeTs05bRL'
code: 'https://github.com/Wei9711/BayesG'
# citation: 'Wei Duan, Jie Lu, Junyu Xuan. (2025). &quot;Bayesian Ego-graph Inference for Networked Multi-Agent Reinforcement Learning.&quot; <i>Proceedings of the Thirty-Ninth Annual Conference on Neural Information Processing Systems (NeurIPS 2025)</i>.'
---
In networked multi-agent reinforcement learning (Networked-MARL), decentralized agents must act autonomously under local observability and constrained communication over fixed physical graphs. Existing methods often assume static neighborhoods, limiting adaptability to dynamic or heterogeneous environments. While centralized frameworks can learn dynamic graphs, their reliance on global state access and centralized infrastructure is impractical in real-world decentralized systems. We propose a stochastic graph-based policy for Networked-MARL, where each agent conditions its decision on a sampled subgraph over its local physical neighborhood. Building on this formulation, we introduce **BayesG**, a decentralized actor–critic framework that learns sparse, context-aware interaction structures via Bayesian variational inference. Each agent operates over an ego-graph and samples a latent communication mask to guide message passing and policy computation. The variational distribution is trained end-to-end alongside the policy using an evidence lower bound (ELBO) objective, enabling agents to jointly learn both interaction topology and decision-making strategies. BayesG outperforms strong MARL baselines on large-scale traffic control tasks with up to 167 agents, demonstrating superior scalability, efficiency, and performance.

