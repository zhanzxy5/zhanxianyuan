---
title: "Revealing the Mystery of Distribution Correction Estimation via Orthogonal-gradient Update"
collection: publications_conference
permalink: /publication/2024-ODICE
excerpt: "12th International Conference on Learning Representations (ICLR 2024)."
date: 2024-1-16
venue: '12th International Conference on Learning Representations (ICLR 2024).'
paperurl: ''
citation: 'Mao, L., Xu, H., Zhang, W., <b>Zhan, X.</b> Revealing the Mystery of Distribution Correction Estimation via Orthogonal-gradient Update. In the <i>12th International Conference on Learning Representations (ICLR 2024)<b>(spotlight)</b></i>.'
---

Abstract
---

In this study, we investigate the DIstribution Correction Estimation (DICE) methods, an important line of work in offline reinforcement learning (RL) and imitation learning (IL). DICE-based methods impose state-action-level behavior constraint, which is an ideal choice for offline learning. However, they typically perform much worse than current state-of-the-art (SOTA) methods that solely use action-level behavior constraint. After revisiting DICE-based methods, we find there exist two gradient terms when learning the value function using true-gradient update: forward gradient (taken on the current state) and backward gradient (taken on the next state). Using forward gradient bears a large similarity to many offline RL methods, and thus can be regarded as applying action-level constraint. However, directly adding the backward gradient may degenerate or cancel out its effect if these two gradients have conflicting directions. To resolve this issue, we propose a simple yet effective modification that projects the backward gradient onto the normal plane of the forward gradient, resulting in an orthogonal-gradient update, a new learning rule for DICE-based methods. We conduct thorough theoretical analyses and find that the projected backward gradient brings state-level behavior regularization, which reveals the mystery of DICE-based methods: the value learning objective does try to impose state-action-level constraint, but needs to be used in a corrected way. Through toy examples and extensive experiments on complex offline RL and IL tasks, we demonstrate that DICE-based methods using orthogonal-gradient updates achieve SOTA performance and great robustness.
Other information

---
* [paper](https://openreview.net/forum?id=L8UNn7Llt4)