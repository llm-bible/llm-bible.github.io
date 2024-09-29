---
layout: publication
title: Muap\: Multi-step Adaptive Prompt Learning For Vision-language Model With Missing Modality
authors: Dai Ruiting, Tan Yuqiao, Mo Lisi, He Tao, Qin Ke, Liang Shuang
conference: "Arxiv"
year: 2024
bibkey: dai2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.04693"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Recently prompt learning has garnered considerable attention for its success in various Vision-Language (VL) tasks. However existing prompt-based models are primarily focused on studying prompt generation and prompt strategies with complete modality settings which does not accurately reflect real-world scenarios where partial modality information may be missing. In this paper we present the first comprehensive investigation into prompt learning behavior when modalities are incomplete revealing the high sensitivity of prompt-based models to missing modalities. To this end we propose a novel Multi-step Adaptive Prompt Learning (MuAP) framework aiming to generate multimodal prompts and perform multi-step prompt tuning which adaptively learns knowledge by iteratively aligning modalities. Specifically we generate multimodal prompts for each modality and devise prompt strategies to integrate them into the Transformer model. Subsequently we sequentially perform prompt tuning from single-stage and alignment-stage allowing each modality-prompt to be autonomously and adaptively learned thereby mitigating the imbalance issue caused by only textual prompts that are learnable in previous works. Extensive experiments demonstrate the effectiveness of our MuAP and this model achieves significant improvements compared to the state-of-the-art on all benchmark datasets
