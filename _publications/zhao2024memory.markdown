---
layout: publication
title: Galore Memory45;efficient LLM Training By Gradient Low45;rank Projection
authors: Zhao Jiawei, Zhang Zhenyu, Chen Beidi, Wang Zhangyang, Anandkumar Anima, Tian Yuandong
conference: "Arxiv"
year: 2024
bibkey: zhao2024memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03507"}
tags: ['BERT', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Training Large Language Models (LLMs) presents significant memory challenges predominantly due to the growing size of weights and optimizer states. Common memory45;reduction approaches such as low45;rank adaptation (LoRA) add a trainable low45;rank matrix to the frozen pre45;trained weight in each layer reducing trainable parameters and optimizer states. However such approaches typically underperform training with full45;rank weights in both pre45;training and fine45;tuning stages since they limit the parameter search to a low45;rank subspace and alter the training dynamics and further may require full45;rank warm start. In this work we propose Gradient Low45;Rank Projection (GaLore) a training strategy that allows full45;parameter learning but is more memory45;efficient than common low45;rank adaptation methods such as LoRA. Our approach reduces memory usage by up to 65.537; in optimizer states while maintaining both efficiency and performance for pre45;training on LLaMA 1B and 7B architectures with C4 dataset with up to 19.7B tokens and on fine45;tuning RoBERTa on GLUE tasks. Our 845;bit GaLore further reduces optimizer memory by up to 82.537; and total training memory by 63.337; compared to a BF16 baseline. Notably we demonstrate for the first time the feasibility of pre45;training a 7B model on consumer GPUs with 24GB memory (e.g. NVIDIA RTX 4090) without model parallel checkpointing or offloading strategies.
