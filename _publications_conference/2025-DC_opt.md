---
title: "Data Center Cooling System Optimization Using Offline Reinforcement Learning"
collection: publications_conference
permalink: /publication/2025-DC_opt
excerpt: "13th International Conference on Learning Representations (ICLR 2025)."
date: 2025-1-23
venue: '13th International Conference on Learning Representations (ICLR 2025).'
paperurl: ''
citation: '<b>Zhan, X.</b>, Zhu, X., Cheng, P., Hu, X., He, Z., Geng, H., Leng, J., Zheng, H., Liu, C., Hong, T., Liang, Y., Liu, Y., Zhao, F. Data Center Cooling System Optimization Using Offline Reinforcement Learning. In the <i>13th International Conference on Learning Representations (ICLR 2025)</i>.'
---

Abstract
---
The recent advances in information technology and artificial intelligence have fueled a rapid expansion of the data center (DC) industry worldwide, accompanied by an immense appetite for electricity to power the DCs. In a typical DC, around 30-40% of the energy is spent on the cooling system rather than on computer servers, posing a pressing need for developing new energy-saving optimization technologies for DC cooling systems. However, optimizing such real-world industrial systems faces numerous challenges, including but not limited to a lack of reliable simulation environments, limited historical data, and stringent safety and control robustness requirements. In this work, we present a novel physics-informed offline reinforcement learning (RL) framework for energy efficiency optimization of DC cooling systems. The proposed framework models the complex dynamical patterns and physical dependencies inside a server room using a purposely designed graph neural network architecture that is compliant with the fundamental time-reversal symmetry. Because of its well-behaved and generalizable state-action representations, the model enables sample-efficient and robust latent space offline policy learning using limited real-world operational data. Our framework has been successfully deployed and verified in a large-scale production DC for closed-loop control of its air-cooling units (ACUs). We conducted a total of 1900 hours of short and long-term experiments in the production DC environment. The results show that our method achieves 14-21% energy savings in the DC cooling system, without any violation of the safety or operational constraints. We have also conducted a comprehensive evaluation of our approach in a real-world DC testbed environment. Our results have demonstrated the significant potential of offline RL in solving a broad range of data-limited, safety-critical real-world industrial control problems.


Other information
---
* [Paper](https://openreview.net/forum?id=W8xukd70cU)