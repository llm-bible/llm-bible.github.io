---
layout: publication
title: 'Blockpruner: Fine-grained Pruning For Large Language Models'
authors: Longguang Zhong, Fanqi Wan, Ruijun Chen, Xiaojun Quan, Liangzhi Li
conference: "Arxiv"
year: 2024
bibkey: zhong2024fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.10594'}
tags: ['Attention Mechanism', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Tools', 'Pruning', 'Reinforcement Learning', 'Pretraining Methods']
---
With the rapid growth in the size and complexity of large language models (LLMs), the costs associated with their training and inference have escalated significantly. Research indicates that certain layers in LLMs harbor substantial redundancy, and pruning these layers has minimal impact on the overall performance. While various layer pruning methods have been developed based on this insight, they generally overlook the finer-grained redundancies within the layers themselves. In this paper, we delve deeper into the architecture of LLMs and demonstrate that finer-grained pruning can be achieved by targeting redundancies in multi-head attention (MHA) and multi-layer perceptron (MLP) blocks. We propose a novel, training-free structured pruning approach called BlockPruner. Unlike existing layer pruning methods, BlockPruner segments each Transformer layer into MHA and MLP blocks. It then assesses the importance of these blocks using perplexity measures and applies a heuristic search for iterative pruning. We applied BlockPruner to LLMs of various sizes and architectures and validated its performance across a wide range of downstream tasks. Experimental results show that BlockPruner achieves more granular and effective pruning compared to state-of-the-art baselines.
