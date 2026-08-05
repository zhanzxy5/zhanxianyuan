---
title: "ODEWorld: A Continuous Predictive Architecture via Physical-Time Flow"
collection: publications_preprint
permalink: /publication/2026-ODEWorld
excerpt: "Preprint, under review."
date: 2026-8-1
venue: 'arXiv.'
paperurl: ''
citation: 'Liu, D., Niu, H., Cheng, P., Gao, Y., Kang, X., Teng, S., Sreenath, K., <b>Zhan, X.</b> ODEWorld: A Continuous Predictive Architecture via Physical-Time Flow. <i>arXiv preprint arXiv:2607.27924</i>.'
---

Abstract
---
In the physical world we inhabit, space and time are fundamentally continuous. However, existing machine learning paradigms for world modeling are largely confined to discrete-time prediction, thereby exhibiting significant inefficiency in capturing the dynamics of physical world. We introduce Physical-Time Flow (<b>PT-Flow</b>), a novel approach that learns a continuous latent velocity field operating in physical time. Crucially, the underlying dynamics of sequential data are parameterized by an ordinary differential equation (ODE) embedded in a well-structured representation space. Under this paradigm, the prediction of future can be recast as temporal integration via an ODE solver in the compressed latent space. Building upon PT-Flow, we construct ODEWorld, a continuous-time latent world model that is both efficient and versatile. By extracting time-variant features and enforcing ODE properties on both the dynamical representation space and the latent velocity field, ODEWorld effectively addresses the long-standing representation collapse issue in latent world model literature. This also enables high-quality image reconstruction even after long-horizon prediction. Moreover, its continuous nature allows for arbitrary temporal resolution and even backward prediction, which is impossible for most discrete-time models. Lastly, ODEWorld can provide rich planning-oriented information to facilitate downstream policy learning. Comprehensive experiments demonstrate that ODEWorld successfully reconciles planning-conducive dynamics abstraction with visual realism, excelling in both video generation and robotic control.


Other information
---
* [Paper](https://arxiv.org/abs/2607.27924)
* [Project Page](https://dstate.github.io/odeworld_website/)