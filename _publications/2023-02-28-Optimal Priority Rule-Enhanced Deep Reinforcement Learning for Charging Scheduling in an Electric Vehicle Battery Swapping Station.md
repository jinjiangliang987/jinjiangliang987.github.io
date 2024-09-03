---
title: "Optimal Priority Rule-Enhanced Deep Reinforcement Learning for Charging Scheduling in an Electric Vehicle Battery Swapping Station"
collection: publications
type: "journal-en"
permalink: /publication/2023-02-28-journal-en-Optimal Priority Rule-Enhanced Deep Reinforcement Learning for Charging Scheduling in an Electric Vehicle Battery Swapping Station
date: 2023-02-28
venue: 'IEEE Transactions on Smart Grid'
paper_author: "<b>Jiangliang Jin</b>, Shuai Mao, Yunjian Xu"
corresponding: True
remark: "(SCI)"
paperurl: 'https://ieeexplore.ieee.org/document/10056371'
citation: 'J. Jin, S. Mao and Y. Xu, "Optimal Priority Rule-Enhanced Deep Reinforcement Learning for Charging Scheduling in an Electric Vehicle Battery Swapping Station," in IEEE Transactions on Smart Grid, vol. 14, no. 6, pp. 4581-4593, Nov. 2023,'
---

Abstract:For a battery swapping station (BSS) with solar generation, N charging bays, and an inventory of M batteries, we study the charging scheduling problem under random EV arrivals, renewable generation, and electricity prices. To minimize the expected weighted sum of charging cost (sum of electricity and battery degradation costs) and EV owners’ waiting cost, we formulate the problem as a Markov decision process with unknown state transition probability. Under a mild heavy-traffic assumption, we rigorously establish the optimality of the Less Demand First (LDF) priority rule under arbitrary system dynamics: batteries with less demand shall be charged first. The optimality result enables us to integrate the LDF rule into a state-of-the-art deep reinforcement learning (DRL) method, proximal policy optimization (PPO), reducing the dimensionality of its output from O(M+N) to O(1) , without loss of optimality in the heavy-traffic scenario. Numerical results (on real-world data) demonstrate that the proposed LDF enhanced PPO approach significantly outperforms classical DRL methods and FCFS (first come, first served) priority rule based DRL counterparts.