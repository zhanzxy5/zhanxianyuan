---
title: "A-Rescue 2.0: A High Fidelity, Parallel, Agent-based Evacuation Simulator"
collection: publications_journal
permalink: /publication/2018-A-Rescue_2.0
excerpt: "Published in Journal of Computing in Civil Engineering, 2018. "
date: 2018-11-26
venue: 'Journal of Computing in Civil Engineering'
paperurl: ''
citation: 'Gehlot, H., <b>Zhan, X.</b>, Qian, X., Thompson, C., Kulkarni, M. and Ukkusuri, S. V., 2018. A-Rescue 2.0: A High Fidelity, Parallel, Agent-based Evacuation Simulator. <i>Journal of Computing in Civil Engineering</i>, 33(2), 04018059.'
---


Abstract
---
Effective evacuation of residents in hurricane-affected areas is essential in reducing the overall damage and ensuring public safety. However, traffic flow patterns in evacuation contexts is far more complex than normal traffic and is usually accompanied with severe congestion due to the presence of evacuees. In such scenarios, agent-based simulation can accurately capture evacuation traffic patterns, which can be extremely useful in evacuation management. However, existing simulators are not fully capable of simultaneously handling highly detailed household behaviors as well as large-scale traffic in evacuation contexts. In this study, we develop a parallelizable, large-scale version of A-RESCUE (an agent-based regional evacuation simulator coupled with user-enriched behavior) called A-RESCUE 2.0. Detailed household evacuation behaviors are modeled using a comprehensive decision-making module. Computation loads induced by the large number of evacuation vehicles are distributed by a parallelization scheme that involves partitioning the road network into subnetworks such that traffic updates in each subnetwork are simultaneously updated in parallel. Dynamic load balancing among different subnetworks is ensured by periodically repartitioning the network using a mutilevel graph partitioning algorithm. A predictive network-weighing scheme is developed that assigns weights (reflecting computational load) to the roads of a network based on current and predicted future network traffic loadings. An on-demand routing strategy is also developed that allows effective rerouting computation based on changing traffic patterns. A-RESCUE 2.0 is capable of representing nonevacuee background traffic, as well as uncertain events on the network like road closures. In addition, real-time monitoring of traffic patterns is made possible using a visualization module that is connected to the simulator through an efficient data communication layer. Comprehensive experiments are conducted on the Miami-Dade County network to validate the applicability of the developed simulator on real-world networks. Findings from experimental tests confirm that the parallelization scheme is effective in improving computational performance.

---
[Download the paper](http://zhanxianyuan.xyz/files/A-Rescue_2.0.pdf)

