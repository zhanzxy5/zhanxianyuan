---
title: "Discrete Diffusion for Reflective Vision-Language-Action Models in Autonomous Driving"
collection: publications_conference
permalink: /publication/2026-ReflectDrive
excerpt: "14th International Conference on Learning Representations (ICLR 2026)."
date: 2026-1-26
venue: '14th International Conference on Learning Representations (ICLR 2026).'
paperurl: ''
citation: 'Li, P., Zheng, Y., Wang, Y., Wang, H., Zhao, H., Liu, J., <b>Zhan, X.</b>, Zhan, K., Lang, X. Discrete Diffusion for Reflective Vision-Language-Action Models in Autonomous Driving. In the <i>14th International Conference on Learning Representations (ICLR 2026)</i>.'
---

Abstract
---
End-to-End (E2E) solutions have emerged as a mainstream approach for autonomous driving systems, with Vision-Language-Action (VLA) models representing a new paradigm that leverages pre-trained multimodal knowledge from Vision-Language Models (VLMs) to interpret and interact with complex real-world environments. However, these methods remain constrained by the limitations of imitation learning, which struggles to inherently encode physical rules during training. Existing approaches often rely on complex rule-based post-refinement, employ reinforcement learning that remains largely limited to simulation, or utilize diffusion guidance that requires computationally expensive gradient calculations. To address these challenges, we introduce ReflectDrive, a novel learning-based framework that integrates a reflection mechanism for safe trajectory generation via discrete diffusion. We first discretize the two-dimensional driving space to construct an action codebook, enabling the use of pre-trained Diffusion Language Models for planning tasks through fine-tuning. Central to our approach is a safety-aware reflection mechanism that performs iterative self-correction without gradient computation. Our method begins with goal-conditioned trajectory generation to model multi-modal driving behaviors. Based on this, we apply local search methods to identify unsafe tokens and determine feasible solutions, which then serve as safe anchors for inpainting-based regeneration. Evaluated on the NAVSIM benchmark, ReflectDrive demonstrates significant advantages in safety-critical trajectory generation, offering a scalable and reliable solution for autonomous driving systems.

Other information
---
* [Paper](https://openreview.net/pdf?id=XJxXSMLDoZ)