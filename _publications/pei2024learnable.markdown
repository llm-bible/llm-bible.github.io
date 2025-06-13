---
layout: publication
title: 'Fusegpt: Learnable Layers Fusion Of Generative Pre-trained Transformers'
authors: Zehua Pei, Hui-ling Zhen, Xianzhi Yu, Sinno Jialin Pan, Mingxuan Yuan, Bei Yu
conference: "Arxiv"
year: 2024
bibkey: pei2024learnable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.14507'}
tags: ['Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'GPT', 'Fine-Tuning', 'Merging', 'Pruning', 'Multimodal Models', 'Pretraining Methods']
---
Generative Pre-trained Transformers (GPTs) have demonstrated remarkable performance across diverse domains, largely due to the extensive scaling of model parameters. Recent works have observed redundancy within transformer blocks and developed compression methods by structured pruning of less important blocks. However, such direct removal often leads to irreversible performance degradation. In this paper, we propose FuseGPT, a novel methodology designed to recycle pruned transformer blocks, thereby recovering the model's performance. Firstly, we introduce a new importance detection metric, Macro Influence (MI), which evaluates the long-term impact of each transformer block by quantifying the information loss incurred upon its removal. Next, we propose group-level layer fusion, which leverages the parameters from layers of less important blocks and integrates them into the corresponding layers of neighboring blocks. This fusion process is not a one-time operation but is refined through iterative parameter updates by lightweight group-level fine-tuning. Specifically, the injected parameters are frozen but are weighted with learnable rank decomposition matrices to reduce the computational overhead during fine-tuning. Our approach not only works well for large language models but also for large multimodal models. Experimental results indicate that, even with modest amounts of data, FuseGPT surpasses previous methods in both perplexity and zero-shot task performance.
