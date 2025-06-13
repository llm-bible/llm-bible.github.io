---
layout: publication
title: 'Transmamba: Flexibly Switching Between Transformer And Mamba'
authors: Yixing Li, Ruobing Xie, Zhen Yang, Xingwu Sun, Shuaipeng Li, Weidong Han, Zhanhui Kang, Yu Cheng, Chengzhong Xu, Di Wang, Jie Jiang
conference: "Arxiv"
year: 2025
bibkey: li2025flexibly
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.24067'}
tags: ['Attention Mechanism', 'Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Pretraining Methods']
---
Transformers are the cornerstone of modern large language models, but their
quadratic computational complexity limits efficiency in long-sequence
processing. Recent advancements in Mamba, a state space model (SSM) with linear
complexity, offer promising efficiency gains but suffer from unstable
contextual learning and multitask generalization. This paper proposes
TransMamba, a novel framework that unifies Transformer and Mamba through shared
parameter matrices (e.g., QKV and CBx), and thus could dynamically switch
between attention and SSM mechanisms at different token lengths and layers. We
design the Memory converter to bridge Transformer and Mamba by converting
attention outputs into SSM-compatible states, ensuring seamless information
flow at TransPoints where the transformation happens. The TransPoint scheduling
is also thoroughly explored for further improvements. We conducted extensive
experiments demonstrating that TransMamba achieves superior training efficiency
and performance compared to baselines, and validated the deeper consistency
between Transformer and Mamba paradigms, offering a scalable solution for
next-generation sequence modeling.
