---
layout: publication
title: 'LARES: Latent Reasoning For Sequential Recommendation'
authors: Enze Liu, Bowen Zheng, Xiaolei Wang, Wayne Xin Zhao, Jinpeng Wang, Sheng Chen, Ji-rong Wen
conference: "Arxiv"
year: 2025
bibkey: liu2025latent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16865"}
  - {name: "Code", url: "https://anonymous.4open.science/r/LARES-E458/"}
tags: ['Fine-Tuning', 'Pre-Training', 'Agentic', 'Tools', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'RecSys', 'Training Techniques', 'Has Code']
---
Sequential recommender systems have become increasingly important in real-world applications that model user behavior sequences to predict their preferences. However, existing sequential recommendation methods predominantly rely on non-reasoning paradigms, which may limit the model's computational capacity and result in suboptimal recommendation performance. To address these limitations, we present LARES, a novel and scalable LAtent REasoning framework for Sequential recommendation that enhances model's representation capabilities through increasing the computation density of parameters by depth-recurrent latent reasoning. Our proposed approach employs a recurrent architecture that allows flexible expansion of reasoning depth without increasing parameter complexity, thereby effectively capturing dynamic and intricate user interest patterns. A key difference of LARES lies in refining all input tokens at each implicit reasoning step to improve the computation utilization. To fully unlock the model's reasoning potential, we design a two-phase training strategy: (1) Self-supervised pre-training (SPT) with dual alignment objectives; (2) Reinforcement post-training (RPT). During the first phase, we introduce trajectory-level alignment and step-level alignment objectives, which enable the model to learn recommendation-oriented latent reasoning patterns without requiring supplementary annotated data. The subsequent phase utilizes reinforcement learning (RL) to harness the model's exploratory ability, further refining its reasoning capabilities. Comprehensive experiments on real-world benchmarks demonstrate our framework's superior performance. Notably, LARES exhibits seamless compatibility with existing advanced models, further improving their recommendation performance. Our code is available at https://anonymous.4open.science/r/LARES-E458/.
