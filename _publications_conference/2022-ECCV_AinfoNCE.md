---
title: "Adversarial Contrastive Learning via Asymmetric InfoNCE"
collection: publications_conference
permalink: /publication/2022-ECCV_AinfoNCE
excerpt: "Accepted in the 17th European Conference on Computer Vision (ECCV 2022)."
date: 2022-7-9
venue: '17th European Conference on Computer Vision (ECCV 2022)'
paperurl: ''
citation: 'Yu, Q., Lou, J., <b>Zhan, X.</b>, Li, Q., Liu, J., Zuo W. and Liu, Y. Adversarial Contrastive Learning via Asymmetric InfoNCE. In the <i>17th European Conference on Computer Vision (ECCV 2022)</i>.'
---

Abstract
---

Contrastive learning (CL) has recently been applied to adversarial learning tasks. Such practice considers adversarial perturbations as additional positive samples of an instance, and by maximizing their agreements with each other, yields better adversarial robustness. However, this mechanism can be potentially flawed, since adversarial perturbations may cause instance-level identity confusion, which can impede CL performance by pulling together different instances with separate identities. To address this issue, we propose to treat adversarial samples unequally when contrasted to positive and negative samples, with an asymmetric InfoNCE objective (A-InfoNCE) that allows discriminating considerations of adversarial samples. Specifically, adversaries are viewed as inferior positives that induce weaker learning signals, or as hard negatives exhibiting higher contrast to other negative samples. In the asymmetric fashion, the adverse impacts of conflicting objectives between CL and adversarial learning can be effectively mitigated. Experiments show that our approach consistently outperforms existing Adversarial CL methods across different finetuning schemes without additional computational cost. The proposed A-InfoNCE is also a generic form that can be readily extended to different CL methods.

Other information
---
[Paper](https://arxiv.org/pdf/2207.08374.pdf)

[Code](https://github.com/yqy2001/A-InfoNCE)