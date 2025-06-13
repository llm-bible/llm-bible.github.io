---
layout: publication
title: 'Make Lora Great Again: Boosting Lora With Adaptive Singular Values And Mixture-of-experts Optimization Alignment'
authors: Chenghao Fan, Zhenyi Lu, Sichen Liu, Chengfeng Gu, Xiaoye Qu, Wei Wei, Yu Cheng
conference: "Arxiv"
year: 2025
bibkey: fan2025make
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16894"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
While Low-Rank Adaptation (LoRA) enables parameter-efficient fine-tuning for Large Language Models (LLMs), its performance often falls short of Full Fine-Tuning (Full FT). Current methods optimize LoRA by initializing with static singular value decomposition (SVD) subsets, leading to suboptimal leveraging of pre-trained knowledge. Another path for improving LoRA is incorporating a Mixture-of-Experts (MoE) architecture. However, weight misalignment and complex gradient dynamics make it challenging to adopt SVD prior to the LoRA MoE architecture. To mitigate these issues, we propose \underline\{G\}reat L\underline\{o\}R\underline\{A\} Mixture-of-Exper\underline\{t\} (GOAT), a framework that (1) adaptively integrates relevant priors using an SVD-structured MoE, and (2) aligns optimization with full fine-tuned MoE by deriving a theoretical scaling factor. We demonstrate that proper scaling, without modifying the architecture or training algorithms, boosts LoRA MoE's efficiency and performance. Experiments across 25 datasets, including natural language understanding, commonsense reasoning, image classification, and natural language generation, demonstrate GOAT's state-of-the-art performance, closing the gap with Full FT.
