---
layout: publication
title: 'Exploring The Limitations Of Mamba In COPY And Cot Reasoning'
authors: Ruifeng Ren, Zhicong Li, Yong Liu
conference: "Arxiv"
year: 2024
bibkey: ren2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03810"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Transformers have become the backbone of modern Large Language Models (LLMs); however, their inference overhead grows linearly with the sequence length, posing challenges for modeling long sequences. In light of this, Mamba has attracted attention for maintaining a constant inference size, with empirical evidence demonstrating that it can match Transformer performance in sequence modeling while significantly reducing computational costs. However, an open question remains: can Mamba always bring savings while achieving performance comparable to Transformers? In this paper, we focus on analyzing the expressive ability of Mamba to perform our defined COPY operation and Chain of Thought (CoT) reasoning. First, inspired by the connection between Mamba and linear attention, we show that constant-sized Mamba may struggle to perform COPY operations while Transformers can handle them more easily. However, when the size of Mamba grows linearly with the input sequence length, it can accurately perform COPY, but in this case, Mamba no longer provides overhead savings. Based on this observation, we further analyze Mamba's ability to tackle CoT tasks, which can be described by the Dynamic Programming (DP) problems. Our findings suggest that to solve arbitrary DP problems, the total cost of Mamba is still comparable to standard Transformers. However, similar to efficient Transformers, when facing DP problems with favorable properties such as locality, Mamba can provide savings in overhead. Our experiments on the copy and CoT tasks further demonstrate Mamba's limitations compared to Transformers in learning these tasks.
