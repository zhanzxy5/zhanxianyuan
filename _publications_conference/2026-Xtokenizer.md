---
title: "X-Tokenizer: A Multimodal Action Tokenizer for Vision-Language-Action Model Pretraining"
collection: publications_conference
permalink: /publication/2026-Xtokenizer
excerpt: "10th Annual Conference on Robot Learning
date: 2026-9-4
venue: '10th Annual Conference on Robot Learning.'
paperurl: ''
citation: 'Kang, X., Shi, Y., Liang, Y., Gan, R., Liu, D., Zhang, P., Chen, D., Qin, X., Zheng, Y., Zheng, J., Wang, H., <b>Zhan, X.</b>, Su, H. X-Tokenizer: A Multimodal Action Tokenizer for Vision-Language-Action Model Pretraining. <i>10th Annual Conference on Robot Learning (CoRL 2026)</i>.'
---

Abstract
---
 Modern Vision-Language-Action (VLA) models must bridge pretrained vision-language reasoning and precise continuous robot control. Existing action tokenizers discretize actions primarily for reconstruction, producing codes that preserve motion geometry but provide only weak semantic supervision to the backbone. We therefore formulate action tokenization not as mere compression, but as semantic interface learning between multimodal reasoning and executable control. To this end, we introduce X-Tokenizer, a lightweight encoder--Semantic Residual Quantization (SRQ)--decoder architecture that provides a shared action interface across diverse robotic arm embodiments. Its key component, SRQ, imposes an asymmetric structure on residual vector quantization: the first level is trained with Masked Action Modeling (MAM) to form a discrete action language that captures coarse motion intent, while deeper levels remain reconstruction-oriented residuals that preserve fine-grained details. To further align action tokens with multimodal semantics, X-Tokenizer is pretrained with contrastive alignment to the representation space of a pretrained foundation model and with next-frame vision-language feature prediction. Pretrained on 2.4M trajectories (2.0B action frames), a single frozen X-Tokenizer plugs into a mixed discrete-continuous VLA as a representation-shaping supervision signal. X-Tokenizer achieves top real-world aggregate and strong RoboTwin 2.0 simulation results. Outperforming FAST in multimodal grounding (+13.5%) and long-horizon tasks (+8.25), it shows that action tokenizers serve as semantic interfaces for VLA pretraining beyond mere action compression.

Other information
---
* [Paper](https://openreview.net/forum?id=mG3eBTsBiG)