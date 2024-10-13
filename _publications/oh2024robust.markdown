---
layout: publication
title: 'Robust Adaptation Of Foundation Models With Black-box Visual Prompting'
authors: Oh Changdae, Seo Gyeongdeok, Jung Geunyoung, Cheng Zhi-qi, Choi Hosik, Jung Jiyoung, Song Kyungwoo
conference: "Arxiv"
year: 2024
bibkey: oh2024robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17491"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Security', 'Tools']
---
With the surge of large-scale pre-trained models (PTMs), adapting these
models to numerous downstream tasks becomes a crucial problem. Consequently,
parameter-efficient transfer learning (PETL) of large models has grasped huge
attention. While PETL methods show impressive performance, they commonly rely
on two optimistic assumptions: 1) the entire parameters of a PTM are available,
and 2) a sufficiently large memory capacity is equipped for caching all the
intermediate activations to compute gradients. However, in most real-world
applications, PTMs are served as black-box APIs or proprietary software without
explicit parameter accessibility. Besides, it is hard to meet a large memory
requirement for modern PTMs. This work proposes black-box visual prompting
(BlackVIP), which efficiently adapts the PTMs without knowledge about model
architectures and parameters. BlackVIP has two components; 1) Coordinator and
2) simultaneous perturbation stochastic approximation with gradient correction
(SPSA-GC). The Coordinator designs input-dependent visual prompts, which allow
the target PTM to adapt in the wild. SPSA-GC efficiently estimates the gradient
of PTM to update the Coordinator. Besides, we propose a variant, BlackVIP-SE,
which significantly reduces the runtime and computational cost of BlackVIP.
Extensive experiments on 19 datasets demonstrate that BlackVIPs enable robust
adaptation to diverse domains and tasks with minimal memory requirements. We
further provide theoretical analysis on the generalization of visual prompting
methods by presenting their connection to the certified robustness of
randomized smoothing.
