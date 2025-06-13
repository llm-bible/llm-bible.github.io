---
layout: publication
title: 'Efficient Pretraining Length Scaling'
authors: Bohong Wu, Shen Yan, Sijun Zhang, Jianqiao Lu, Yutao Zeng, Ya Wang, Xun Zhou
conference: "Arxiv"
year: 2025
bibkey: wu2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14992"}
tags: ['Transformer', 'Pre-Training', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Recent advances in large language models have demonstrated the effectiveness
of length scaling during post-training, yet its potential in pre-training
remains underexplored. We present the Parallel Hidden Decoding Transformer
(\textit\{PHD\}-Transformer), a novel framework that enables efficient length
scaling during pre-training while maintaining inference efficiency.
\textit\{PHD\}-Transformer achieves this through an innovative KV cache
management strategy that distinguishes between original tokens and hidden
decoding tokens. By retaining only the KV cache of original tokens for
long-range dependencies while immediately discarding hidden decoding tokens
after use, our approach maintains the same KV cache size as the vanilla
transformer while enabling effective length scaling. To further enhance
performance, we introduce two optimized variants: \textit\{PHD-SWA\} employs
sliding window attention to preserve local dependencies, while
\textit\{PHD-CSWA\} implements chunk-wise sliding window attention to eliminate
linear growth in pre-filling time. Extensive experiments demonstrate consistent
improvements across multiple benchmarks.
