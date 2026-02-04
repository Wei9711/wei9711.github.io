---
title: "Bandwidth-constrained Variational Message Encoding for Cooperative Multi-agent Reinforcement Learning"
collection: publications
category: conferences
permalink: /publication/2026-05-01-bandwidth-constrained-variational-message-encoding
excerpt: 'We propose BVME, a variational message encoding module for cooperative MARL that enforces bandwidth constraints while preserving coordination performance.'
date: 2026-05-01
venue: 'AAMAS 2026'
paperurl: 'https://doi.org/10.65109/QXVZ8292'
code: ''
citation: 'Wei Duan, Jie Lu, En Yu, and Junyu Xuan. 2026. Bandwidth-constrained Variational Message Encoding for Cooperative Multi-agent Reinforcement Learning. In Proc. of the 25th International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2026), Paphos, Cyprus, May 25 – 29, 2026, IFAAMAS, 10 pages. https://doi.org/10.65109/QXVZ8292'
---
Graph-based multi-agent reinforcement learning (MARL) enables coordinated behavior under partial observability by modeling agents as nodes and communication links as edges. While recent methods excel at learning sparse coordination graphs—determining who communicates with whom—they do not address what information should be transmitted under hard bandwidth constraints. We study this bandwidth-limited regime and show that naïve dimensionality reduction consistently degrades coordination performance. Hard bandwidth constraints force selective encoding, but deterministic projections lack mechanisms to control how compression occurs. We introduce **Bandwidth-constrained Variational Message Encoding (BVME)**, a lightweight module that treats messages as samples from learned Gaussian posteriors regularized via KL divergence to an uninformative prior. BVME's variational framework provides principled, tunable control over compression strength through interpretable hyperparameters, directly constraining the representations used for decision-making. Across SMACv1, SMACv2, and MPE benchmarks, BVME achieves comparable or superior performance while using 67–83% fewer message dimensions, with gains most pronounced on sparse graphs where message quality critically impacts coordination. Ablations reveal U-shaped sensitivity to bandwidth, with BVME excelling at extreme ratios while adding minimal overhead.

