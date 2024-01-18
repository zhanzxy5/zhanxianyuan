---
title: "Feasibility-Guided Safe Offline Reinforcement Learning"
collection: publications_conference
permalink: /publication/2024-FISOR
excerpt: "12th International Conference on Learning Representations (ICLR 2024)."
date: 2024-1-16
venue: '12th International Conference on Learning Representations (ICLR 2024).'
paperurl: ''
citation: 'Zheng, Y., Li, J., Yu, D., Yang, Y., Li, S., <b>Zhan, X.</b>, Liu, J. Feasibility-Guided Safe Offline Reinforcement Learning. In <i>12th International Conference on Learning Representations (ICLR 2024)</i>.'
---

Abstract
---

Safe offline reinforcement learning is a promising way to bypass risky online interactions towards safe policy learning. Most existing methods only enforce soft constraints, i.e., constraining safety violations in expectation below thresholds predetermined. This can lead to potentially unsafe outcomes, thus unacceptable in safety-critical scenarios. An alternative is to enforce the hard constraint of zero violation. However, this can be challenging in offline setting, as it needs to strike the right balance among three highly intricate and correlated aspects: safety constraint satisfaction, reward maximization, and behavior regularization imposed by offline datasets. Interestingly, we discover that via reachability analysis of safe-control theory, the hard safety constraint can be equivalently translated to identifying the largest feasible region given the offline dataset. This seamlessly converts the original trilogy problem to a feasibility-dependent objective, i.e., maximizing reward value within the feasible region while minimizing safety risks in the infeasible region. Inspired by these, we propose FISOR (FeasIbility-guided Safe Offline RL), which allows safety constraint adherence, reward maximization, and offline policy learning to be realized via three decoupled processes, while offering strong safety performance and stability. In FISOR, the optimal policy for the translated optimization problem can be derived in a special form of weighted behavior cloning, which can be effectively extracted with a guided diffusion model thanks to its expressiveness.  We compare FISOR against baselines on DSRL benchmark for safe offline RL. Evaluation results show that FISOR is the only method that can guarantee safety satisfaction in all tasks, while achieving top returns in most tasks.

Other information
---
* [paper](https://openreview.net/forum?id=j5JvZCaDM0)
* [code](https://github.com/ZhengYinan-AIR/FISOR)