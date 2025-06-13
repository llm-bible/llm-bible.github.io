---
layout: publication
title: 'Robust Adaptation Of Foundation Models With Black-box Visual Prompting'
authors: Changdae Oh, Gyeongdeok Seo, Geunyoung Jung, Zhi-qi Cheng, Hosik Choi, Jiyoung Jung, Kyungwoo Song
conference: "Arxiv"
year: 2024
bibkey: oh2024robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17491"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Attention Mechanism', 'Prompting']
---
With a surge of large-scale pre-trained models, parameter-efficient transfer learning (PETL) of large models has garnered significant attention. While promising, they commonly rely on two optimistic assumptions: 1) full access to the parameters of a PTM, and 2) sufficient memory capacity to cache all intermediate activations for gradient computation. However, in most real-world applications, PTMs serve as black-box APIs or proprietary software without full parameter accessibility. Besides, it is hard to meet a large memory requirement for modern PTMs. This work proposes black-box visual prompting (BlackVIP), which efficiently adapts the PTMs without knowledge of their architectures or parameters. BlackVIP has two components: 1) Coordinator and 2) simultaneous perturbation stochastic approximation with gradient correction (SPSA-GC). The Coordinator designs input-dependent visual prompts, which allow the target PTM to adapt in the wild. SPSA-GC efficiently estimates the gradient of PTM to update Coordinator. Besides, we introduce a variant, BlackVIP-SE, which significantly reduces the runtime and computational cost of BlackVIP. Extensive experiments on 19 datasets demonstrate that BlackVIPs enable robust adaptation to diverse domains and tasks with minimal memory requirements. We further provide a theoretical analysis on the generalization of visual prompting methods by presenting their connection to the certified robustness of randomized smoothing, and presenting an empirical support for improved robustness.
