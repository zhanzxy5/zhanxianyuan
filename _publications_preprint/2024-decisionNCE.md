---
title: "DecisionNCE: Embodied Multimodal Representations via Implicit Preference Learning"
collection: publications_preprint
permalink: /publication/2024-decisionNCE
excerpt: "Preprint, under review."
date: 2024-2-29
venue: 'arXiv.'
paperurl: ''
citation: 'Li, J., Zheng, J., Zheng, Y., Mao, L., Hu, X., Cheng, S., Niu, H., Liu, J., Liu, Y., Liu, J., Zhang, Y. Q., <b>Zhan, X.</b> DecisionNCE: Embodied Multimodal Representations via Implicit Preference Learning. <i>arXiv preprint arXiv:2402.18137</i>.'
---

Abstract
---
Multimodal pretraining has emerged as an effective strategy for the trinity of goals of representation learning in autonomous robots: 1) extracting both local and global task progression information; 2) enforcing temporal consistency of visual representation; 3) capturing trajectory-level language grounding. Most existing methods approach these via separate objectives, which often reach sub-optimal solutions. In this paper, we propose a universal unified objective that can simultaneously extract meaningful task progression information from image sequences and seamlessly align them with language instructions. We discover that via implicit preferences, where a visual trajectory inherently aligns better with its corresponding language instruction than mismatched pairs, the popular Bradley-Terry model can transform into representation learning through proper reward reparameterizations. The resulted framework, DecisionNCE, mirrors an InfoNCE-style objective but is distinctively tailored for decision-making tasks, providing an embodied representation learning framework that elegantly extracts both local and global task progression features, with temporal consistency enforced through implicit time contrastive learning, while ensuring trajectory-level instruction grounding via multimodal joint encoding. Evaluation on both simulated and real robots demonstrates that DecisionNCE effectively facilitates diverse downstream policy learning tasks, offering a versatile solution for unified representation and reward learning.

Other information
---
* [Project page](https://2toinf.github.io/DecisionNCE/)
* [Arxiv version of the paper](https://arxiv.org/pdf/2402.18137.pdf)
* [Code](https://github.com/2toinf/DecisionNCE)