---
layout: publication
title: 'Lightthinker: Thinking Step-by-step Compression'
authors: Jintian Zhang, Yuqi Zhu, Mengshu Sun, Yujie Luo, Shuofei Qiao, Lun Du, Da Zheng, Huajun Chen, Ningyu Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025thinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15589"}
  - {name: "Code", url: "https://github.com/zjunlp/LightThinker"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code']
---
Large language models (LLMs) have shown remarkable performance in complex
reasoning tasks, but their efficiency is hindered by the substantial memory and
computational costs associated with generating lengthy tokens. In this paper,
we propose LightThinker, a novel method that enables LLMs to dynamically
compress intermediate thoughts during reasoning. Inspired by human cognitive
processes, LightThinker compresses verbose thought steps into compact
representations and discards the original reasoning chains, thereby
significantly reducing the number of tokens stored in the context window. This
is achieved by training the model on when and how to perform compression
through data construction, mapping hidden states to condensed gist tokens, and
creating specialized attention masks. Additionally, we introduce the Dependency
(Dep) metric to quantify the degree of compression by measuring the reliance on
historical tokens during generation. Extensive experiments on four datasets and
two models show that LightThinker reduces peak memory usage and inference time,
while maintaining competitive accuracy. Our work provides a new direction for
improving the efficiency of LLMs in complex reasoning tasks without sacrificing
performance. Code will be released at https://github.com/zjunlp/LightThinker.
