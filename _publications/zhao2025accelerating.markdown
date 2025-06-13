---
layout: publication
title: 'Codeswift: Accelerating LLM Inference For Efficient Code Generation'
authors: Qianhui Zhao, Li Zhang, Fang Liu, Xiaoli Lian, Qiaoyuanhe Meng, Ziqian Jiao, Zetong Zhou, Borui Zhang, Runlin Guo, Jia Li
conference: "Arxiv"
year: 2025
bibkey: zhao2025accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17139"}
tags: ['Efficiency and Optimization', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Applications']
---
Code generation is a latency-sensitive task that demands high timeliness, but
the autoregressive decoding mechanism of Large Language Models (LLMs) leads to
poor inference efficiency. Existing LLM inference acceleration methods mainly
focus on standalone functions using only built-in components. Moreover, they
treat code like natural language sequences, ignoring its unique syntax and
semantic characteristics. As a result, the effectiveness of these approaches in
code generation tasks remains limited and fails to align with real-world
programming scenarios. To alleviate this issue, we propose CodeSwift, a simple
yet highly efficient inference acceleration approach specifically designed for
code generation, without comprising the quality of the output. CodeSwift
constructs a multi-source datastore, providing access to both general and
project-specific knowledge, facilitating the retrieval of high-quality draft
sequences. Moreover, CodeSwift reduces retrieval cost by controlling retrieval
timing, and enhances efficiency through parallel retrieval and a context- and
LLM preference-aware cache. Experimental results show that CodeSwift can reach
up to 2.53x and 2.54x speedup compared to autoregressive decoding in
repository-level and standalone code generation tasks, respectively,
outperforming state-of-the-art inference acceleration approaches by up to 88%.
