---
layout: page
title: Wireless Network
description: Next-generation wireless communication architectures and mobile applications.
img: assets/img/mesh_net.png
importance: 1
category: research
---

Software-defined, AI-driven Dyanmic mmWave IAB
------
Abstract: Integrated Access and Backhaul (IAB) is an emerging technique to enable cost-effective deployment of dense 5G networks that utilize emerging millimeter-wavelength (mmWave) spectrum. Existing heuristic-based network control/management frameworks are not well-suited for the increasing complexity and uncertainty introduced by mmWave IAB. Machine learning (ML) can help automate network control decisions, but its practical deployment faces new system-level challenges in 5G IAB, including accurate simulation-based training, resolving conflicting objectives from heterogeneous network slices, and efficiently collecting observations for run-time decision making. In this paper, we develop a general framework for effectively deploying reinforcement learning (RL) to control 5G IAB networks. Our framework incorporates a data-driven stochastic simulation scheme to bridge the simulation-to-reality gap, a piecewise reward shaping mechanism to handle competing conflicting performance objectives, and a simple observation selection algorithm to reduce the input size into the RL policy. We validate this framework using real-world network measurements from a mmWave IAB testbed, combined with a large scale ray tracing simulation. Experiments on a set of challenging 5G IAB network control problems demonstrate the effectiveness of our framework to enable practical RL integration into 5G IAB.

ML-based Matrix Optimization in Massive MIMO
------
Abstract: In the downlink of massive MIMO, the transmitter uses precoding technology to reduce interference and improve spectrum efficiency. In this paper, a complex-valued gradient neural network (CVGNN) is proposed to solve the Moore-Penrose inversion of the complex matrix used in massive MIMO precoding algorithms.

Beam Alignment and Tracking for Millimeter Wave Communications via Bandit Learning
------
Abstract: Millimeter wave (mmwave) communications have attracted increasing attention thanks to the abundant spectrum resource. The short wave-length of mmwave signals facilitates exploiting large antenna arrays to achieve large array gains and combat large path-loss. However, the use of large antenna arrays along with narrow beams leads to a large overhead in beam training for obtaining channel state information, especially in dynamic environments. To reduce the overhead of beam training, in this paper we formulate the problem of beam alignment and tracking (BA/T) as a stochastic bandit problem. In particular, to sense the change of the environments, the actions are designed based on the offset of successive beam indexes (i.e., beam index difference), which measures the rate of change of the environments. Then, we propose two efficient BA/T algorithms based on the stochastic bandit learning. To reveal useful insights, the performance of effective achievable rate is further analyzed for the proposed BA/T algorithms. The analytical results show that the algorithms can sense the change of the environments and adjust beam training strategies intelligently. In addition, they do not require any priori knowledge of dynamic channel modeling, and thus are applicable to a variety of complicated scenarios. Simulation results demonstrate the effectiveness and superiority of the proposed algorithms.

