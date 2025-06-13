---
layout: publication
title: 'Kvcrush: Key Value Cache Size-reduction Using Similarity In Head-behaviour'
authors: Gopi Krishna Jha, Sameh Gobriel, Liubov Talamanova, Alexander Kozlov, Nilesh Jain
conference: "Arxiv"
year: 2025
bibkey: jha2025key
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00022"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Pruning', 'Quantization', 'Applications', 'Attention Mechanism']
---
Key-value (KV) caching has emerged as a crucial optimization technique for
accelerating inference in large language models (LLMs). By allowing the
attention operation to scale linearly rather than quadratically with the total
sequence length, KV caching significantly enhances generation throughput.
However, due to large context lengths in the modern LLMs, the memory footprint
of the KV is a huge bottleneck for model deployment directly impacting the
model's batch size, hindering its ability to deliver high-throughput. Existing
research addresses this challenge using several techniques, such as discarding
low-attention tokens, quantization, and matrix approximation which typically
lead to a negative impact on the model accuracy.
  In this paper, We propose KVCrush technology which can be combined with many
KV compression technologies to improve the model accuracy at a much smaller
memory. KVCrush provides an alternate representation scheme for key-value
states, along with a low-overhead token pruning algorithm that accounts for the
token distribution in the KV cache, which in turn allows for a a smaller
footprint while maintaining the accuracy of the model. Based on our results,
KVCrush reduces LongBench KV Cache size by 4x with less than 1% accuracy drop
and achieves state-of-the-art average accuracy with minimal overhead, incurring
less than 0.5% total inference latency. KVCrush not only outperforms the
accuracy of state-of-the-art importance-based token retention schemes but is
also compatible with typical practical LLM deployments using KV cache paging
schemes such as vLLM and mixed precision quantization.
