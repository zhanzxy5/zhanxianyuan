---
title: "CSCAD: Correlation Structure-based Collective Anomaly Detection in Complex System"
collection: publications_journal
permalink: /publication/2021-OOD_anomaly
excerpt: "In IEEE Transactions on Knowledge and Data Engineering (TKDE). "
date: 2022-1-13
venue: 'IEEE Transactions on Knowledge and Data Engineering (TKDE)'
paperurl: ''
citation: 'Qin, H., <b>Zhan, X.</b>, and Zheng, Y., 2022. CSCAD: Correlation Structure-based Collective Anomaly Detection in Complex System. In <i>IEEE Transactions on Knowledge and Data Engineering (TKDE)</i>.'
---

Abstract
---

Detecting anomalies in large complex systems is a critical and challenging task. The difficulties arise from several aspects. First, collecting ground truth labels or prior knowledge for anomalies is hard in real-world systems, which often leads to limited or no anomaly labels in the dataset. Second, anomalies in large systems usually occur in a collective manner due to the underlying dependency structure among devices or sensors. Lastly, real-time anomaly detection for high-dimensional data requires efficient algorithms that are capable of handling different types of data (i.e. continuous and discrete). We propose a correlation structure-based collective anomaly detection (CSCAD) model for high-dimensional anomaly detection problems in large systems, which is also generalizable to semi-supervised or supervised settings. Our framework utilize graph convolutional network combining a variational autoencoder to jointly exploit the feature space correlation and reconstruction deficiency of samples to perform anomaly detection. We propose an extended mutual information (EMI) metric to mine the internal correlation structure among different data features, which enhances the data reconstruction capability of CSCAD. The reconstruction loss and latent standard deviation vector of a sample obtained from the reconstruction network can be perceived as two natural anomalous degree measures. An anomaly discriminating network can then be trained using low anomalous degree samples as positive samples, and high anomalous degree samples as negative samples. Experimental results on five public datasets demonstrate that our approach consistently outperforms all the competing baselines.


[arXiv version](https://arxiv.org/abs/2105.14476)