---
title: "FlexSSL : A Generic and Efficient Framework for Semi-Supervised Learning"
collection: publications_conference
permalink: /publication/2024-FlexSSL
excerpt: "27th European Conference on Artificial Intelligence (ECAI-2024)."
date: 2024-7-4
venue: '27th European Conference on Artificial Intelligence (ECAI-2024).'
paperurl: ''
citation: 'Qin, H., <b>Zhan, X.</b>, Li, Y., Zheng, Y. FlexSSL : A Generic and Efficient Framework for Semi-Supervised Learning. In the <i>27th European Conference on Artificial Intelligence (ECAI-2024)</i>.'
---

Abstract
---
Semi-supervised learning holds great promise for many real-world applications, due to its ability to leverage both unlabeled and expensive labeled data. However, most semi-supervised learning algorithms still heavily rely on the limited labeled data to infer and utilize the hidden information from unlabeled data. We note that any semi-supervised learning task under the self-training paradigm also hides an auxiliary task of discriminating label observability. Jointly solving these two tasks allows full utilization of information from both labeled and unlabeled data, thus alleviating the problem of over-reliance on labeled data. This naturally leads to a new generic and efficient learning framework without the reliance on any domain-specific information, which we call FlexSSL. The key idea of FlexSSL is to construct a semi-cooperative “game”, which forges cooperation between a main self-interested semi-supervised learning task and a companion task that infers label observability to facilitate main task training. We show with theoretical derivation of its connection to loss re-weighting on noisy labels. Through evaluations on a diverse range of tasks, we demonstrate that FlexSSL can consistently enhance the performance of semi-supervised learning algorithms.

* [ArXiv version](https://arxiv.org/abs/2312.16892)