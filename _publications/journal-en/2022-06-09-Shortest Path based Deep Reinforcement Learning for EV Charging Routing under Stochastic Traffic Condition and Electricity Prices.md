---
title: "Shortest Path based Deep Reinforcement Learning for EV Charging Routing under Stochastic Traffic Condition and Electricity Prices"
collection: publications
type: "journal-en"
permalink: /publication/2022-06-09-Shortest Path based Deep Reinforcement Learning for EV Charging Routing under Stochastic Traffic Condition and Electricity Prices
date: 2022-06-09
venue: 'IEEE Internet of Things Journal'
paper_author: "<b>Jiangliang Jin</b>, Yunjian Xu"
corresponding: True
remark: "(SCI)"
paperurl: 'https://ieeexplore.ieee.org/document/9792244'
citation: 'J. Jin and Y. Xu, "Shortest-Path-Based Deep Reinforcement Learning for EV Charging Routing Under Stochastic Traffic Condition and Electricity Prices," in IEEE Internet of Things Journal, vol. 9, no. 22, pp. 22571-22581, 15 Nov.15, 2022, '
---

Abstract:We study the charging routing problem faced by a smart electric vehicle (EV) that looks for an EV charging station (EVCS) to fulfill its battery charging demand. Leveraging the real-time information from both the power and intelligent transportation systems, the EV seeks to minimize the sum of the travel cost (to a selected EVCS) and the charging cost (a weighted sum of electricity cost and waiting time cost at the EVCS). We formulate the problem as a Markov decision process with unknown dynamics of system uncertainties (in traffic conditions, charging prices, and waiting time). To mitigate the curse of dimensionality, we reformulate the deterministic charging routing problem (a mixed-integer program) as a two-level shortest-path (SP)-based optimization problem that can be solved in polynomial time. Its low dimensional solution is input into a state-of-the-art deep reinforcement learning (DRL) algorithm, the advantage actor–critic (A2C) method, to make efficient online routing decisions. Numerical results (on a real-world transportation network) demonstrate that the proposed SP-based A2C approach outperforms the classical A2C method and two alternative SP-based DRL methods.