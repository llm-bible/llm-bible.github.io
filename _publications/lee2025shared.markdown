---
layout: publication
title: 'Shared Disk KV Cache Management For Efficient Multi-instance Inference In Rag-powered Llms'
authors: Hyungwoo Lee, Kihyun Kim, Jinwoo Kim, Jungmin So, Myung-hoon Cha, Hong-yeon Kim, James J. Kim, Youngjae Kim
conference: "Arxiv"
year: 2025
bibkey: lee2025shared
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11765"}
tags: ['RAG', 'Reinforcement Learning']
---
Recent large language models (LLMs) face increasing inference latency as
input context length and model size continue to grow. In particular, the
retrieval-augmented generation (RAG) technique, which enhances LLM responses by
incorporating external knowledge, exacerbates this issue by significantly
increasing the number of input tokens. This expansion in token length leads to
a substantial rise in computational overhead, particularly during the prefill
stage, resulting in prolonged time-to-first-token (TTFT). To address this
issue, this paper proposes a method to reduce TTFT by leveraging a disk-based
key-value (KV) cache to lessen the computational burden during the prefill
stage. We also introduce a disk-based shared KV cache management system, called
Shared RAG-DCache, for multi-instance LLM RAG service environments. This
system, together with an optimal system configuration, improves both throughput
and latency under given resource constraints. Shared RAG-DCache exploits the
locality of documents related to user queries in RAG, as well as the queueing
delay in LLM inference services. It proactively generates and stores disk KV
caches for query-related documents and shares them across multiple LLM
instances to enhance inference performance. In experiments on a single host
equipped with 2 GPUs and 1 CPU, Shared RAG-DCache achieved a 15~71% increase in
throughput and up to a 12~65% reduction in latency, depending on the resource
configuration.
