---
title: " GraphGarment: Learning Garment Dynamics for Bimanual Cloth Manipulation Tasks"
collection: publications
permalink: /publication/graphgarment
excerpt: '**Wei Chen**, Kelin Li, Dongmyoung Lee, Xiaoshuai Chen, Rui Zong and Petar Kormushev'
date: 2025-3-1
venue: 'The 2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2025)'

---






Physical manipulation of garments is often crucial when performing fabric-related tasks, such as hanging garments. However, due to the deformable nature of fabrics, these operations remain a significant challenge for robots in household, healthcare, and industrial environments. In this paper, we propose GraphGarment, a novel approach that models garment dynamics based on robot control inputs and applies the learned dynamics model to facilitate garment manipulation tasks such as hanging. Specifically, we use graphs to represent the interactions between the robot end-effector and the garment. GraphGarment uses a graph neural network (GNN) to learn a dynamics model that can predict the next garment state given the current state and input action in simulation.
To address the substantial sim-to-real gap, we propose a residual model that compensates for garment state prediction errors, thereby improving real-world performance.
The garment dynamics model is then applied to a model-based action sampling strategy, where it is utilized to manipulate the garment to a reference pre-hanging configuration for garment-hanging tasks. 
We conducted four experiments using six types of garments to validate our approach in both simulation and real-world settings. 
In simulation experiments, GraphGarment achieves better garment state prediction performance, with a prediction error 0.46 cm lower than the best baseline. Our approach also demonstrates improved performance in the garment-hanging simulation experiment—with enhancements of 12\%, 24\%, and 10\%, respectively. Moreover, real-world robot experiments confirm the robustness of sim-to-real transfer, with an error increase of 0.17 cm compared to simulation results. Supplementary material is available at: \href{https://sites.google.com/view/graphgarment}{https://sites.google.com/view/graphgarment}.


[Download paper here]([https://arxiv.org/pdf/2401.10702.pdf](https://arxiv.org/pdf/2503.05817)) | [Website]([https://sites.google.com/view/gripperongripper](https://sites.google.com/view/graphgarment))


