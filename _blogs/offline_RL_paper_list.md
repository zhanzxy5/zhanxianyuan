---
layout: archive
title: "Offline RL Paper List"
permalink: /blog/paper-list
author_profile: true

---
# Offline RL papers (continued updating)

## Classic offline RL papers
* Offline Reinforcement Learning: Tutorial, Review, and Perspectives on Open Problems
* Off-Policy Deep Reinforcement Learning without Exploration
* Stabilizing Off-Policy Q-Learning via Bootstrapping Error Reduction
* Advantage-Weighted Regression: Simple and Scalable Off-Policy Reinforcement Learning
* Behavior Regularized Offline Reinforcement Learning
* AlgaeDICE: Policy Gradient from Arbitrary Experience
* An Optimistic Perspective on Offline Reinforcement Learning
* MOPO: Model-based Offline Policy Optimization
* Conservative Q-Learning for Offline Reinforcement Learning
* Keep Doing What Worked: Behavioral Modelling Priors for Offline Reinforcement Learning
* Accelerating Online Reinforcement Learning with Offline Datasets
* Critic Regularized Regression
* Provably Good Batch Reinforcement Learning Without Great Exploration
* Model-Based Offline Planning
* PLAS: Latent Action Space for Offline Reinforcement Learning


## Recent papers on offline RL (2020-2021)
| Title    | Sub-area | Venue    | Theory/Reproducible | Summary       |
| -----    | ------   | ------   | --------            | -----------   |
|BRAC+: Going Deeper with Behavior Regularized Offline Reinforcement Learning | Model-Free | ICLR2021(reject) |  | Improving behavior regularized offline reinforcement learning.|
|Offline Policy Optimization with Variance Regularization | Model-Free | ICLR2021(reject) |  | Variance regularization based on stationary state-action distribution corrections in offline policy optimization.|
|Uncertainty Weighted Offline Reinforcement Learning | Model-Free | ICLR2021(reject) |  | A simple and effective uncertainty weighted training mechanism for stabilizing offline reinforcement learning.|
|Addressing Extrapolation Error in Deep Offline Reinforcement Learning | Model-Free | ICLR2021(reject) |  | We are proposing methods to address extrapolation error in deep offline reinforcement learning.|
|Q-Value Weighted Regression: Reinforcement Learning with Limited Data | Model-Free | ICLR2021(reject) |  | We analyze the sample-efficiency of actor-critic RL algorithms, and introduce a new algorithm, achieving superior sample-efficiency while maintaining competitive final performance on the MuJoCo task suite and on Atari games.|
|Robust Offline Reinforcement Learning from Low-Quality Data | Model-Free | ICLR2021(reject) |  | |
|Reducing Conservativeness Oriented Offline Reinforcement Learning | Model-Free | Preprint |  | |
|Continuous Doubly Constrained Batch Reinforcement Learning | Model-Free | ICML2021(review) |  | |
|Expert-Supervised Reinforcement Learning for Offline Policy Learning and Evaluation | Model-Free | NIPS2020(accept) |  | |
|POPO: Pessimistic Ofﬂine Policy Optimization | Model-Free | NIPS2020(workshop) |  | |
|PLAS: Latent Action Space for Offline Reinforcement Learning | Model-Free | CORL2020(accept) | No theory, easy to reproduce（has code） | |
|Critic Regularized Regression | Model-Free | NIPS2020(accept) | No theory, easy to reproduce（has code） | |
|COMBO: Conservative Offline Model-Based Policy Optimization | Model-Based | ICML2021(review) | Some theory, easy to reproduce（has code） | |
|Offline Model-Based Optimization via Normalized Maximum Likelihood Estimation | Model-Based | ICLR2021(accept) |  | Offline, data-driven optimization using normalized maximum likelihood to produce robust function estimates.|
|Overcoming Model Bias for Robust Offline Deep Reinforcement Learning | Model-Based | AAAI21(reject) |  | |
|MUSBO: Model-based Uncertainty Regularized and Sample Efficient Batch Optimization for Deployment Constrained Reinforcement Learning | Model-Based | ICML2021(review) |  | |
|GELATO: Geometrically Enriched Latent Model for Offline Reinforcement Learning | Model-Based | ICML2021(review) |  | |
|PerSim: Data-Efficient Offline Reinforcement Learning with Heterogeneous Agents via Personalized Simulators | Model-Based | ICML2021(review) |  | |
|Counterfactual Data Augmentation using Locally Factored Dynamics | Data-Aug | NIPS2020(accept) |  | |
|S4RL: Surprisingly Simple Self-Supervision for Offline Reinforcement Learning | Data-Aug | ICML2021(review) |  | |
|Representation Balancing Offline Model-based Reinforcement Learning | Data-Aug | Preprint |  | |
|Representation Matters: Offline Pretraining for Sequential Decision Making | Data-Aug | Preprint |  | |
|AWAC: Accelerating Online Reinforcement Learning with Offline Datasets | Offline2Online | ICLR2021(reject) | No theory, easy to reproduce（has code） | We study RL pretraining from offline datasets and fine-tuning with online interaction, identifying issues with existing methods and proposing a new RL algorithm, AWAC, that is effective in this setting.|
|Addressing Distribution Shift in Online Reinforcement Learning with Offline Datasets | Offline2Online | ICLR2021(reject) |  | We present a simple framework, BRED, that incorporates a balanced replay scheme and an ensemble distillation scheme, for fine-tuning an offline RL agent more efficiently.|
|Fine-Tuning Offline Reinforcement Learning with Model-Based Policy Optimization | Offline2Online | ICLR2021(reject) |  | We present an offline RL approach that leverages both uncertainty-aware models and behavior-regularized model-free RL to achieve state of the art results on the MuJoCo tasks in the D4RL benchmark.|
|OPAL: Offline Primitive Discovery for Accelerating Offline Reinforcement Learning | Offline2Online | ICLR2021(accept) |  | An effective way to leverage multimodal offline behavioral data is to extract a continuous space of primitives, and use it for downstream task learning.|
|Near Real-World Benchmarks for Offline Reinforcement Learning | Benchmark | Preprint | No theory | |
|Offline Reinforcement Learning Hands-On | Benchmark | NIPS2020(workshop) | No theory | |
|RL Unplugged: Benchmarks for Offline Reinforcement Learning | Benchmark | NIPS2020(accept) | No theory | |
|Offline Adaptive Policy Leaning in Real-World Sequential Recommendation Systems | Application | ICLR2021(reject) |  | We propose a new paradigm to learn an RL policy from offline data in the real-world sequential recommendation system.|
|Batch-Constrained Distributional Reinforcement Learning for Session-based Recommendation | Application | ICLR2021(reject) |  | |
|Robust Constrained Reinforcement Learning for Continuous Control with Model Misspecification | Constraints | ICLR2021(reject) |  | This paper presents an approach that is robust with respect to constraint satisfaction in the presence of perturbations to the system dynamics.|
|Offline Learning from Demonstrations and Unlabeled Experience | Imitation | NIPS2020(workshop) |  | |
|Risk-Averse Offline Reinforcement Learning | Robustness | ICLR2021(accept) |  | We propose the first risk-averse reinforcement learning algorithm in the fully offline setting.|
|Batch Reinforcement Learning with Hyperparameter Gradients | Others | ICML2020(accept) |  | |
|Overﬁtting and Optimization in Ofﬂine Policy Learning | Others | Preprint |  | |