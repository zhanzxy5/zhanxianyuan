---
title: "TESLA: Thermally Safe, Load-Aware, and Energy-Efficient Cooling Control System for Data Centers"
collection: publications_conference
permalink: /publication/2024-Tesla
excerpt: "53rd International Conference on Parallel Processing (ICPP 2024)."
date: 2024-6-12
venue: '53rd International Conference on Parallel Processing (ICPP 2024).'
paperurl: ''
citation: 'Geng, H., Sun, Y., Li, Y., Leng, J., Zhu, X., <b>Zhan, X.</b>, Li, Y., Zhao, F., Liu, Y. TESLA: Thermally Safe, Load-Aware, and Energy-Efficient Cooling Control System for Data Centers. In the <i>53rd International Conference on Parallel Processing (ICPP 2024)</i>.'
---

Abstract
---
The increasing demand for artificial intelligence and cloud computing has led to skyrocketing energy consumption of data centers (DCs). This paper focuses on tackling this energy challenge through cooling control system optimization, which aims to ensure thermal safety with minimal cooling energy consumption. Current industry practice involves human operators, while many data-driven methods have also been proposed. However, human intervention often results in unnecessary energy consumption, particularly in the face of fluctuating server loads, whereas existing data-driven methods struggle to maintain thermal safety in practice. To overcome these issues, we propose TESLA, a thermally safe, load-aware, and energy-efficient cooling control system for data centers. TESLA employs a novel data-driven framework that integrates domain knowledge to predict DC temperature and cooling energy under dynamic server load. Based on these predictions, a Bayesian optimizer (BO) finds the energy-optimal settings for the cooling system at every control step. Besides cooling energy, BO’s optimization objective also includes minimizing cooling interruption that causes rapid temperature rise within the data center and leads to thermal safety violation. We deploy TESLA on a real data-center testbed and show that it achieves on average 10.1% cooling energy saving relative to a fixed cooling system parameter setting and no thermal safety violations relative to previous data-driven methods.
