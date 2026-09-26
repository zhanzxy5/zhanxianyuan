---
title: "Higher-Order Action Supervision Makes A Strong Policy Class"
collection: publications_conference
permalink: /publication/2026-1st_Order_Sup
excerpt: "Fortieth Annual Conference on Neural Information Processing Systems"
date: 2026-9-25
venue: 'Fortieth Annual Conference on Neural Information Processing Systems.'
paperurl: ''
citation: 'Cheng, P., Hou, Y., Zhou, Z., Zhang, Q., Huang, C., <b>Zhan, X.</b>. Higher-Order Action Supervision Makes A Strong Policy Class. <i>Fortieth Annual Conference on Neural Information Processing Systems (NeurIPS 2026)</i>.'
---

Abstract
---
Modern data-driven decision-making methods, such as imitation learning (IL) and reinforcement learning (RL), have achieved great success in solving many complex tasks. However, these methods often suffer from serious control instability and robustness issues when applied in real-world applications such as robotics and autonomous driving, posing notable challenges for their practical deployment. We argue that this instability issue stems largely from their limitations on solely supervising and optimizing zeroth-order actions (i.e., the action labels), failing to account for higher-order action dynamics and temporal consistency. In this paper, we show that simultaneously supervising both zeroth- and first-order actions can dramatically enhance policies' performance and control robustness. To achieve this, we introduce a novel and elegant loss scheme supported by formal theoretical guarantees that can equip any off-the-shelf policy model (e.g., deterministic, stochastic, or flow policies) with the capability for higher-order action supervision, without requiring any structural modifications. Moreover, our proposed method can serve as a lightweight plug-and-play module that seamlessly integrates with a broad spectrum of existing offline RL frameworks. Extensive evaluations on OGBench and D4RL demonstrate that our approach yields substantial performance and robustness improvements across a wide range of continuous control environments. Notably, our method can also enhance policies' out-of-distribution (OOD) generalization capability in the challenging low-data regime, making it an ideal tool in tackling many real-world control problems.

Other information
---
* [Paper](https://openreview.net/forum?id=ZusaOFN1fJ)
