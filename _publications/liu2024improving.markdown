---
layout: publication
title: 'Intactkv: Improving Large Language Model Quantization By Keeping Pivot Tokens Intact'
authors: Ruikang Liu, Haoli Bai, Haokun Lin, Yuening Li, Han Gao, Zhengzhuo Xu, Lu Hou, Jun Yao, Chun Yuan
conference: "Arxiv"
year: 2024
bibkey: liu2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01241"}
  - {name: "Code", url: "https://github.com/ruikangliu/IntactKV"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Quantization', 'Has Code', 'Attention Mechanism']
---
Large language models (LLMs) excel in natural language processing but demand
intensive computation. To mitigate this, various quantization methods have been
explored, yet they compromise LLM performance. This paper unveils a previously
overlooked type of outliers in LLMs. Such outliers are found to allocate most
of the attention scores on initial tokens of input, termed as pivot tokens,
which are crucial to the performance of quantized LLMs. Given that, we propose
IntactKV to generate the KV cache of pivot tokens losslessly from the
full-precision model. The approach is simple and easy to combine with existing
quantization solutions with no extra inference overhead. Besides, IntactKV can
be calibrated as additional LLM parameters to boost the quantized LLMs further
with minimal training costs. Mathematical analysis also proves that IntactKV
effectively reduces the upper bound of quantization error. Empirical results
show that IntactKV brings consistent improvement over various quantization
methods across different LLMs and downstream tasks, leading to the new
state-of-the-art for LLM quantization. The codes are available at
https://github.com/ruikangliu/IntactKV.
