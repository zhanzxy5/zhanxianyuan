---
title: "Towards Robust Zero-Shot Reinforcement Learning"
collection: publications_conference
permalink: /publication/2025-BREEZE
excerpt: "Thirty-Ninth Conference on Neural Information Processing Systems (NeurIPS 2025)."
date: 2025-9-18
venue: 'NeurIPS 2025.'
paperurl: ''
citation: 'Zheng,K.,Teyssier, L., Zheng, Y., Luo, Y., <b>Zhan, X.</b> Towards Robust Zero-Shot Reinforcement Learning. In the <i>Thirty-Ninth Conference on Neural Information Processing Systems (NeurIPS 2025)</i>.'
---

Abstract
---
The recent development of zero-shot reinforcement learning (RL) has opened a new avenue for learning pre-trained generalist policies that can adapt to arbitrary new tasks in a zero-shot manner. While the popular Forward-Backward (FB) representations and related methods have shown promise in zero-shot RL, we found empirically that their non-expressive modeling architecture and extrapolation errors caused by out-of-the-distribution (OOD) actions during offline learning often lead to potentially biased and non-robust representations, eventually causing suboptimal performance. To address these issues, we propose Behavior-Rgularized Zero-shot RL with Expressivity enhancement (BREEZE), an upgraded FB-based framework that simultaneously enhances offline learning stability, FB representation learning quality, and policy extraction capability. Specifically, BREEZE introduces behavioral regularization in zero-shot RL policy learning, transforming policy optimization into a stable in-sample learning paradigm. Additionally, BREEZE employs the expressive self-attention based architectures for forward and backward representations, providing more accurate successor measure estimates that capture the complicated environment-task relationships. Moreover, BREEZE extracts the policy with a guided task-conditioned diffusion model, enabling optimal action synthesis while capturing the highly multi-modal action distributions in zero-shot RL settings. Extensive experiments on ExORL and FrankaKitchen demonstrate that BREEZE achieves state-of-the-art performance while exhibiting superior robustness compared to prior offline zero-shot RL methods.


Other information
---
* Paper coming soon