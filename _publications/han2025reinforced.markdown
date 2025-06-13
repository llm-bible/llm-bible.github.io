---
layout: publication
title: 'Reinforced Model Merging'
authors: Jiaqi Han, Jingwen Ye, Shunyu Liu, Haofei Zhang, Jie Song, Zunlei Feng, Mingli Song
conference: "Arxiv"
year: 2025
bibkey: han2025reinforced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.21272"}
  - {name: "Code", url: "https://github.com/WuDiHJQ/Reinforced-Model-Merging"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Merging', 'Has Code', 'Attention Mechanism']
---
The success of large language models has garnered widespread attention for
model merging techniques, especially training-free methods which combine model
capabilities within the parameter space. However, two challenges remain: (1)
uniform treatment of all parameters leads to performance degradation; (2)
search-based algorithms are often inefficient. In this paper, we present an
innovative framework termed Reinforced Model Merging (RMM), which encompasses
an environment and agent tailored for merging tasks. These components interact
to execute layer-wise merging actions, aiming to search the optimal merging
architecture. Notably, RMM operates without any gradient computations on the
original models, rendering it feasible for edge devices. Furthermore, by
utilizing data subsets during the evaluation process, we addressed the
bottleneck in the reward feedback phase, thereby accelerating RMM by up to 100
times. Extensive experiments demonstrate that RMM achieves state-of-the-art
performance across various vision and NLP datasets and effectively overcomes
the limitations of the existing baseline methods. Our code is available at
https://github.com/WuDiHJQ/Reinforced-Model-Merging.
