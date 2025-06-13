---
layout: publication
title: 'Batchllm: Optimizing Large Batched LLM Inference With Global Prefix Sharing And Throughput-oriented Token Batching'
authors: Zhen Zheng, Xin Ji, Taosong Fang, Fanghao Zhou, Chuanjie Liu, Gang Peng
conference: "Arxiv"
year: 2024
bibkey: zheng2024optimizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.03594'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture', 'Merging', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) increasingly play an important role in a wide
range of information processing and management tasks. Many of these tasks are
performed in large batches or even offline, and the performance indictor for
which is throughput. These tasks usually show the characteristic of prefix
sharing, where different prompt input can partially show the common prefix.
However, the existing LLM inference engines tend to optimize the streaming
requests and show limitations of supporting the large batched tasks with the
prefix sharing characteristic. The existing solutions use the LRU-based cache
to reuse the KV context of common prefix between requests. The KV context that
are about to be reused may prematurely evicted with the implicit cache
management. Besides, the streaming oriented systems do not leverage the
request-batch information and can not mix the decoding tokens with the prefill
chunks to the best for the batched scenarios, and thus fails to saturate the
GPU. We propose BatchLLM to address the above problems. BatchLLM explicitly
identifies the common prefixes globally. The requests sharing the same prefix
will be scheduled together to reuse the KV context the best. BatchLLM reorders
the requests and schedules the requests with larger ratio of decoding first to
better mix the decoding tokens with the latter prefill chunks, and applies
memory-centric token batching to enlarge the token-batch sizes, which helps to
increase the GPU utilization. Finally, BatchLLM optimizes the prefix-shared
Attention kernel with horizontal fusion to reduce tail effect and kernel launch
overhead. Extensive evaluation shows that BatchLLM outperforms vLLM and SGLang
by 1.3\\(\times\\) to 10.8\\(\times\\) on a set of microbenchmarks and a typical
industry workload under different hardware environments.
