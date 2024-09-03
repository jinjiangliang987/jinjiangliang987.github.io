---
title: "Optimal Policy Characterization Enhanced Actor-Critic Approach for Electric Vehicle Charging Scheduling in a Power Distribution Network"
collection: publications
type: "journal-en"
permalink: /publication/2021-03-01-journal-en-Optimal Policy Characterization Enhanced Actor-Critic Approach for Electric Vehicle Charging Scheduling in a Power Distribution Network
date: 2021-03-01
venue: 'IEEE Transactions on Smart Grid'
paper_author: "<b>Jiangliang Jin</b>, Yunjian Xu"
corresponding: True
remark: "(SCI)"
paperurl: 'https://ieeexplore.ieee.org/document/9211734'
citation: 'J. Jin and Y. Xu, "Optimal Policy Characterization Enhanced Actor-Critic Approach for Electric Vehicle Charging Scheduling in a Power Distribution Network," in IEEE Transactions on Smart Grid, vol. 12, no. 2, pp. 1416-1428, March 2021, '
---

Abstract:We study the scheduling of large-scale electric vehicle (EV) charging in a power distribution network under random renewable generation and electricity prices. The problem is formulated as a stochastic dynamic program with unknown state transition probability. To mitigate the curse of dimensionality, we establish the nodal multi-target (NMT) characterization of the optimal scheduling policy: all EVs with the same deadline at the same bus should be charged to approach a single target of remaining energy demand. We prove that the NMT characterization is optimal under arbitrarily random system dynamics. To adaptively learn the dynamics of system uncertainty, we propose a model-free soft-actor-critic (SAC) based method to determine the target levels for the characterized NMT policy. The proposed SAC + NMT approach significantly outperforms existing deep reinforcement learning methods (in our numerical experiments on the IEEE 37-node test feeder), as the established NMT characterization sharply reduces the dimensionality of neural network outputs without loss of optimality.