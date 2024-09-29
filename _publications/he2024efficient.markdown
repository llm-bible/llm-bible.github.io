---
layout: publication
title: Efficient LLM Inference With Kcache
authors: He Qiaozhi, Wu Zhihua
conference: "Arxiv"
year: 2024
bibkey: he2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.18057"}
tags: ['Applications', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models(LLMs) have had a profound impact on AI applications particularly in the domains of long-text comprehension and generation. KV Cache technology is one of the most widely used techniques in the industry. It ensures efficient sequence generation by caching previously computed KV states. However it also introduces significant memory overhead. We discovered that KV Cache is not necessary and proposed a novel KCache technique to alleviate the memory bottleneck issue during the LLMs inference process. KCache can be used directly for inference without any training process Our evaluations show that KCache improves the throughput of popular LLMs by 4037; with the baseline while keeping accuracy.
