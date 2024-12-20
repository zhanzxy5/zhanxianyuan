---
title: "Network-Wide Traffic States Imputation Using Self-interested Coalitional Learning"
collection: publications_conference
permalink: /publication/2021-KDD_imputation
excerpt: "Published in SIGKDD 2021 (KDD2021). "
date: 2021-5-16
venue: 'Twenty-Seventh ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD2021)'
paperurl: ''
citation: 'Qin, H., <b>Zhan, X.</b>, Li, Y., Yang, X. and Zheng, Y. Network-Wide Traffic States Imputation Using Self-interested Coalitional Learning. In <i>Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD ’21)</i>, August 14–18, 2021, Virtual Event, Singapore. ACM, New York, NY, USA. https://doi.org/10.1145/3447548.3467424.'
---

Abstract
---

Accurate network-wide traffic state estimation is vital to many transportation operations and urban applications. However, existing methods often suffer from the scalability issue when performing real-time inference at the city-level, or not robust enough under limited data. Currently, GPS trajectory data from probe vehicles has become a popular data source for many transportation applications. GPS trajectory data has large coverage area, which is ideal for network-wide applications, but also has the disadvantage of being sparse and highly heterogeneous among different time and locations. In this study, we focus on developing a robust and interpretable network-wide traffic state imputation framework using partially observed traffic information. We introduce a new learning strategy, called self-interested coalitional learning (SCL), which forge cooperation between a main self-interested semi-supervised task and a discriminator as a critic to facilitate main task training while providing interpretability on the results. In our detailed model, we use as a temporal graph convolutional variational autoencoder (TG-VAE) as the reconstructor, which models the complex spatio-temporal pattern in data and solves the main traffic state imputation task. A discriminator is introduced to output interpretable imputation confidence on the estimated results and also help to enhance the performance of the reconstructor. The framework is evaluated using a large GPS trajectory dataset from taxis in Jinan, China. Extensive experiments against the state-of-the-art baselines demonstrate the effectiveness and robustness of the proposed method for network-wide traffic state estimation.


[Slides](http://zhanxianyuan.xyz/files/KDD-SCL_slides.pdf)

[Download the paper](http://zhanxianyuan.xyz/files/KDD2021-SCL.pdf)