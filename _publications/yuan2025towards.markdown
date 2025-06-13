---
layout: publication
title: 'SAISA: Towards Multimodal Large Language Models With Both Training And Inference Efficiency'
authors: Qianhao Yuan, Yanjiang Liu, Yaojie Lu, Hongyu Lin, Ben He, Xianpei Han, Le Sun
conference: "Arxiv"
year: 2025
bibkey: yuan2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.02458"}
  - {name: "Code", url: "https://github.com/icip-cas/SAISA"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Multimodal Models']
---
Multimodal Large Language Models (MLLMs) mainly fall into two architectures,
each involving a trade-off between training and inference efficiency: embedding
space alignment (e.g., LLaVA-1.5) is inefficient during inference, while
cross-attention space alignment (e.g., Flamingo) is inefficient in training. In
this paper, we compare these two architectures and identify the key factors for
building efficient MLLMs. A primary difference between them lies in how
attention is applied to visual tokens, particularly in their interactions with
each other. To investigate whether attention among visual tokens is necessary,
we propose a new self-attention mechanism, NAAViT (\textbf\{N\}o
\textbf\{A\}ttention \textbf\{A\}mong \textbf\{Vi\}sual \textbf\{T\}okens), which
eliminates this type of attention. Our pilot experiment on LLaVA-1.5 shows that
attention among visual tokens is highly redundant. Based on these insights, we
introduce SAISA (\textbf\{S\}elf-\textbf\{A\}ttention \textbf\{I\}nput \textbf\{S\}pace
\textbf\{A\}lignment), a novel architecture that enhance both training and
inference efficiency. SAISA directly aligns visual features with the input
spaces of NAAViT self-attention blocks, reducing computational overhead in both
self-attention blocks and feed-forward networks (FFNs). Using the same
configuration as LLaVA-1.5, SAISA reduces inference FLOPs by 66% and training
budget by 26%, while achieving superior performance in terms of accuracy.
Comprehensive ablation studies further validate the effectiveness of SAISA
across various LLMs and visual encoders. The code and model will be publicly
available at https://github.com/icip-cas/SAISA.
