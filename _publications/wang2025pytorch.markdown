---
layout: publication
title: 'Leetdecoding: A Pytorch Library For Exponentially Decaying Causal Linear Attention With CUDA Implementations'
authors: Jiaping Wang, Simiao Zhang, Qiao-chu He, Yifan Chen
conference: "Arxiv"
year: 2025
bibkey: wang2025pytorch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02573"}
  - {name: "Code", url: "https://github.com/Computational-Machine-Intelligence/LeetDecoding}{this"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Transformer', 'Has Code', 'Attention Mechanism']
---
The machine learning and data science community has made significant while
dispersive progress in accelerating transformer-based large language models
(LLMs), and one promising approach is to replace the original causal attention
in a generative pre-trained transformer (GPT) with *exponentially decaying
causal linear attention*. In this paper, we present LeetDecoding, which is the
first Python package that provides a large set of computation routines for this
fundamental operator. The launch of LeetDecoding was motivated by the current
lack of (1) clear understanding of the complexity regarding this operator, (2)
a comprehensive collection of existing computation methods (usually spread in
seemingly unrelated fields), and (3) CUDA implementations for fast inference on
GPU. LeetDecoding's design is easy to integrate with existing linear-attention
LLMs, and allows for researchers to benchmark and evaluate new computation
methods for exponentially decaying causal linear attention. The usage of
LeetDecoding does not require any knowledge of GPU programming and the
underlying complexity analysis, intentionally making LeetDecoding accessible to
LLM practitioners. The source code of LeetDecoding is provided at
\href\{https://github.com/Computational-Machine-Intelligence/LeetDecoding\}\{this
GitHub repository\}, and users can simply install LeetDecoding by the command
\texttt\{pip install leet-decoding\}.
