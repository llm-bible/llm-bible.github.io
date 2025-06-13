---
layout: publication
title: 'PARM: Multi-objective Test-time Alignment Via Preference-aware Autoregressive Reward Model'
authors: Baijiong Lin, Weisen Jiang, Yuancheng Xu, Hao Chen, Ying-cong Chen
conference: "Arxiv"
year: 2025
bibkey: lin2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.06274"}
  - {name: "Code", url: "https://github.com/Baijiong-Lin/PARM"}
tags: ['Fine-Tuning', 'GPT', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Multi-objective test-time alignment aims to adapt large language models (LLMs) to diverse multi-dimensional user preferences during inference while keeping LLMs frozen. Recently, GenARM (Xu et al., 2025) first independently trains Autoregressive Reward Models (ARMs) for each preference dimension without awareness of each other, then combines their outputs based on user-specific preference vectors during inference to achieve multi-objective test-time alignment, leading to two key limitations: the need for \textit\{multiple\} ARMs increases the inference cost, and the separate training of ARMs causes the misalignment between the guided generation and the user preferences. To address these issues, we propose Preference-aware ARM (PARM), a single unified ARM trained across all preference dimensions. PARM uses our proposed Preference-Aware Bilinear Low-Rank Adaptation (PBLoRA), which employs a bilinear form to condition the ARM on preference vectors, enabling it to achieve precise control over preference trade-offs during inference. Experiments demonstrate that PARM reduces inference costs and achieves better alignment with preference vectors compared with existing methods. Additionally, PARM enables weak-to-strong guidance, allowing a smaller PARM to guide a larger frozen LLM without expensive training, making multi-objective alignment accessible with limited computing resources. The code is available at https://github.com/Baijiong-Lin/PARM.
