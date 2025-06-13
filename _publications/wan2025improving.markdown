---
layout: publication
title: 'Pipeoffload: Improving Scalability Of Pipeline Parallelism With Memory Optimization'
authors: Xinyi Wan, Penghui Qi, Guangxing Huang, Jialin Li, Min Lin
conference: "Arxiv"
year: 2025
bibkey: wan2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01328"}
  - {name: "Code", url: "https://github.com/sail-sg/zero-bubble-pipeline-parallelism}{this"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Has Code']
---
Pipeline parallelism (PP) is widely used for training large language models
(LLMs), yet its scalability is often constrained by high activation memory
consumption as the number of in-flight microbatches grows with the degree of
PP. In this paper, we focus on addressing this challenge by leveraging the
under-explored memory offload strategy in PP. With empirical study, we discover
that in the majority of standard configurations, at least half, and potentially
all, of the activations can be offloaded with negligible overhead. In the cases
where full overload is not possible, we introduce a novel selective offload
strategy that decreases peak activation memory in a better-than-linear manner.
Furthermore, we integrate memory offload with other techniques to jointly
consider overall throughput and memory limitation. Our experiments proves that
the per-device activation memory effectively reduces with the total number of
stages, making PP a stronger alternative than TP, offering up to a 19%
acceleration with even lower memory consumption. The implementation is
open-sourced at
\href\{https://github.com/sail-sg/zero-bubble-pipeline-parallelism\}\{this url\}.
