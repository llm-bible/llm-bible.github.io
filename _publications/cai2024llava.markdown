---
layout: publication
title: 'Llava-kd: A Framework Of Distilling Multimodal Large Language Models'
authors: Yuxuan Cai, Jiangning Zhang, Haoyang He, Xinwei He, Ao Tong, Zhenye Gan, Chengjie Wang, Xiang Bai
conference: "Arxiv"
year: 2024
bibkey: cai2024llava
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16236"}
  - {name: "Code", url: "https://github.com/Fantasyele/LLaVA-KD"}
tags: ['Fine-Tuning', 'Pre-Training', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models', 'Distillation']
---
The success of Large Language Models (LLM) has led researchers to explore
Multimodal Large Language Models (MLLM) for unified visual and linguistic
understanding. However, the increasing model size and computational complexity
of MLLM limit their use in resource-constrained environments. Small-scale MLLM
(s-MLLM) aims to retain the capabilities of the large-scale model (l-MLLM)
while reducing computational demands, but resulting in a significant decline in
performance. To address the aforementioned issues, we propose a novel LLaVA-KD
framework to transfer knowledge from l-MLLM to s-MLLM. Specifically, we
introduce Multimodal Distillation (MDist) to minimize the divergence between
the visual-textual output distributions of l-MLLM and s-MLLM, and Relation
Distillation (RDist) to transfer l-MLLM's ability to model correlations between
visual features. Additionally, we propose a three-stage training scheme to
fully exploit the potential of s-MLLM: 1) Distilled Pre-Training to align
visual-textual representations, 2) Supervised Fine-Tuning to equip the model
with multimodal understanding, and 3) Distilled Fine-Tuning to further transfer
l-MLLM capabilities. Our approach significantly improves performance without
altering the small model's architecture. Extensive experiments and ablation
studies validate the effectiveness of each proposed component. Code will be
available at https://github.com/Fantasyele/LLaVA-KD.
