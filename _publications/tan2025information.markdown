---
layout: publication
title: 'Tokencarve: Information-preserving Visual Token Compression In Multimodal Large Language Models'
authors: Xudong Tan, Peng Ye, Chongjun Tu, Jianjian Cao, Yaoxin Yang, Lin Zhang, Dongzhan Zhou, Tao Chen
conference: "Arxiv"
year: 2025
bibkey: tan2025information
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.10501'}
  - {name: "Code", url: 'https://github.com/ShawnTan86/TokenCarve'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Training Techniques', 'Merging', 'Multimodal Models', 'Reinforcement Learning']
---
Multimodal Large Language Models (MLLMs) are becoming increasingly popular,
while the high computational cost associated with multimodal data input,
particularly from visual tokens, poses a significant challenge. Existing
training-based token compression methods improve inference efficiency but
require costly retraining, while training-free methods struggle to maintain
performance when aggressively reducing token counts. In this study, we reveal
that the performance degradation of MLLM closely correlates with the
accelerated loss of information in the attention output matrix. This insight
introduces a novel information-preserving perspective, making it possible to
maintain performance even under extreme token compression. Based on this
finding, we propose TokenCarve, a training-free, plug-and-play, two-stage token
compression framework. The first stage employs an
Information-Preservation-Guided Selection (IPGS) strategy to prune
low-information tokens, while the second stage further leverages IPGS to guide
token merging, minimizing information loss. Extensive experiments on 11
datasets and 2 model variants demonstrate the effectiveness of TokenCarve. It
can even reduce the number of visual tokens to 22.2% of the original count,
achieving a 1.23x speedup in inference, a 64% reduction in KV cache storage,
and only a 1.54% drop in accuracy. Our code is available at
https://github.com/ShawnTan86/TokenCarve.
