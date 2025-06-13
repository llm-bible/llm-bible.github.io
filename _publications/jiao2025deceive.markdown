---
layout: publication
title: 'Don''t Deceive Me: Mitigating Gaslighting Through Attention Reallocation In Lmms'
authors: Pengkun Jiao, Bin Zhu, Jingjing Chen, Chong-wah Ngo, Yu-gang Jiang
conference: "Arxiv"
year: 2025
bibkey: jiao2025deceive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09456"}
tags: ['Applications', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models']
---
Large Multimodal Models (LMMs) have demonstrated remarkable capabilities
across a wide range of tasks. However, their vulnerability to user
gaslighting-the deliberate use of misleading or contradictory inputs-raises
critical concerns about their reliability in real-world applications. In this
paper, we address the novel and challenging issue of mitigating the negative
impact of negation-based gaslighting on LMMs, where deceptive user statements
lead to significant drops in model accuracy. Specifically, we introduce
GasEraser, a training-free approach that reallocates attention weights from
misleading textual tokens to semantically salient visual regions. By
suppressing the influence of "attention sink" tokens and enhancing focus on
visually grounded cues, GasEraser significantly improves LMM robustness without
requiring retraining or additional supervision. Extensive experimental results
demonstrate that GasEraser is effective across several leading open-source LMMs
on the GaslightingBench. Notably, for LLaVA-v1.5-7B, GasEraser reduces the
misguidance rate by 48.2%, demonstrating its potential for more trustworthy
LMMs.
