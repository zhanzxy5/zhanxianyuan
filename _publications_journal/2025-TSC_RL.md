---
title: "A Fully Data-Driven Approach for Realistic Traffic Signal Control Using Offline Reinforcement Learning"
collection: publications_journal
permalink: /publication/2025-TSC_RL
excerpt: "In Data Science for Transportation. "
date: 2025-11-3
venue: 'Data Science for Transportation'
paperurl: ''
citation: 'Li, J., Lin, S., Shi, T., Mei, Y., Song, J., <b>Zhan, X.</b> and Li, R., 2025. A Fully Data-Driven Approach for Realistic Traffic Signal Control Using Offline Reinforcement Learning. In <i>Data Science for Transportation</i>, 7(25).'
---

Abstract
---

The optimization of traffic signal control (TSC) is critical for an efficient transportation system. In recent years, reinforcement learning (RL) techniques have emerged as a popular approach for TSC and show promising results for highly adaptive control. However, existing RL-based methods suffer from serious real-world transferability issues and hardly have any successful deployments. The reasons for such failures are mostly due to the reliance on over-idealized traffic simulators for policy optimization, as well as using unrealistic fine-grained state observations and reward signals that are not directly obtainable from real-world sensors. In this paper, we propose a fully data-driven and simulator-free framework for realistic Traffic Signal Control. Specifically, we combine well-established traffic flow theory with machine learning to construct a reward inference model to infer the reward signals from coarse-grained traffic data. With the inferred rewards, we further propose a sample-efficient offline RL method to enable direct signal control policy learning from historical offline data sets of real-world intersections. To evaluate our approach, we collect historical traffic data from a real-world intersection, and develop a highly customized simulation environment that strictly follows real data characteristics. We demonstrate through extensive experiments that our approach achieves superior performance over conventional and offline RL baselines, and also enjoys much better real-world applicability.

Other information
---
[paper](https://link.springer.com/article/10.1007/s42421-025-00139-z)