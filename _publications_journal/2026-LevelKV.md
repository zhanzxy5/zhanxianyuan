---
title: "LevelKV: Hierarchical KV Cache Pruning for Efficient and Reliable LLM Inference"
collection: publications_journal
permalink: /publication/2026-LevelKV
excerpt: "In IEEE Transactions on Computers. "
date: 2026-9-6
venue: 'IEEE Transactions on Computers'
paperurl: ''
citation: 'Yuan, Y., Kong, R., Xian, B., Li, Y., Cao, T., <b>Zhan, X.</b> Zhang, Y., and Liu, Y., 2025. LevelKV: Hierarchical KV Cache Pruning for Efficient and Reliable LLM Inference. In <i>IEEE Transactions on Computers</i>.'
---

Abstract
---

he performance and functionality of large language model (LLM)-based applications heavily depend on their contextual inputs. As applications become more sophisticated, their contexts grow increasingly complex, leading to two critical challenges: (i) excessive computational and memory overhead—particularly from the key-value (KV) cache—and (ii) heightened security risks arising from heterogeneous and unverified context sources. Existing approaches fail to address both issues simultaneously: context compression methods often discard crucial information, undermining instruction fidelity, while security-oriented defenses typically introduce additional
computational costs. We present LevelKV, a hierarchical KV cache pruning framework that achieves efficient and reliable LLM inference. LevelKV employs a holistic metric to jointly identify critical activations in both Key and Value caches, and introduces a hierarchy-preserving mechanism that structurally prioritizes high-privilege prompts during pruning to maintain reliability. Evaluations on LongBench and SysBench demonstrate that LevelKV achieves state-of-the-art trade-offs between memory efficiency and instruction compliance. Remarkably, it maintains superior reliability even when retaining only 1/10 of the KV cache, enabling robust and efficient LLM deployment on memory-constrained devices.

