---
title: "Flow Matching-Based Autonomous Driving Planning with Advanced Interactive Behavior Modeling"
collection: publications_conference
permalink: /publication/2025-FlowPlanner
excerpt: "Thirty-Ninth Conference on Neural Information Processing Systems (NeurIPS 2025)."
date: 2025-9-18
venue: 'NeurIPS 2025.'
paperurl: ''
citation: 'Tan,T., Zheng, Y., Liang, R., Wang, Z., Zheng, K., Zheng, J., Li, J., <b>Zhan, X.</b>, Liu, J. Flow Matching-Based Autonomous Driving Planning with Advanced Interactive Behavior Modeling. In the <i>Thirty-Ninth Conference on Neural Information Processing Systems (NeurIPS 2025)</i>.'
---

Abstract
---
Modeling interactive driving behaviors in complex scenarios remains a fundamental challenge for autonomous driving planning. Learning-based approaches attempt to address this challenge with advanced generative models, removing the dependency on over-engineered architectures for representation fusion. However, brute-force implementation by simply stacking transformer blocks lacks a dedicated mechanism for modeling interactive behaviors that is common in real driving scenarios. The scarcity of interactive driving data further exacerbates this problem, leaving conventional imitation learning methods ill-equipped to capture high-value interactive behaviors. We propose Flow Planner, which tackles these problems through coordinated innovations in data modeling, model architecture, and learning scheme. Specifically, we first introduce fine-grained trajectory tokenization, which decomposes the trajectory into overlapping segments to decrease the complexity of whole trajectory modeling. With a sophisticatedly designed architecture, we achieve efficient temporal and spatial fusion of planning and scene information, to better capture interactive behaviors. In addition, the framework incorporates flow matching with classifier-free guidance for multi-modal behavior generation, which dynamically reweights agent interactions during inference to maintain coherent response strategies, providing a critical boost for interactive scenario understanding. Experimental results on the large-scale nuPlan dataset demonstrate that Flow Planner achieves state-of-the-art performance among learning-based approaches while effectively modeling interactive behaviors in complex driving scenarios.


Other information
---
* Paper coming soon