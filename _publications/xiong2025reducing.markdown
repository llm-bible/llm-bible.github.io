---
layout: publication
title: 'Uniattn: Reducing Inference Costs Via Softmax Unification For Post-training Llms'
authors: Yizhe Xiong, Wei Huang, Xin Ye, Hui Chen, Zijia Lin, Haoran Lian, Zhenpeng Su, Jungong Han, Guiguang Ding
conference: "Arxiv"
year: 2025
bibkey: xiong2025reducing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.00439'}
  - {name: "Code", url: 'https://github.com/Bostoncake/UniAttn'}
tags: ['Has Code', 'Transformer', 'Training Techniques', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Post-training is essential for adapting Large Language Models (LLMs) to
real-world applications. Deploying post-trained models faces significant
challenges due to substantial memory overhead and noticeable inference latency.
Existing work has identified significant redundancies in LLMs and proposed
efficient architectures, namely intra-layer KV sharing and cross-layer KV
sharing. However, intra-layer KV sharing still results in high inference costs,
while cross-layer KV sharing leads to significant performance degradation. As a
result, both methods remain suboptimal for post-training pre-trained LLMs. In
this paper, we identify that the \texttt\{Softmax\} operation is a primary
bottleneck for LLM inference and discover that it is actually highly redundant
during post-training. We propose Softmax \textbf\{Uni\}fication in
\textbf\{Att\}e\textbf\{n\}tion (\textbf\{UniAttn\}), a novel post-training method
that unifies Softmax activations across transformer blocks to reduce LLM
inference costs. Additionally, UniAttn adopts a linear projection to compensate
for the errors induced by Softmax unification. Experiments show that UniAttn
matches the performance of standard post-training while significantly reducing
inference costs, outperforming existing efficient architectures during
post-training. Our code will be available at
\url\{https://github.com/Bostoncake/UniAttn\}.
