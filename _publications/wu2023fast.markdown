---
layout: publication
title: 'Fast Distributed Inference Serving For Large Language Models'
authors: Bingyang Wu, Yinmin Zhong, Zili Zhang, Shengyu Liu, Fangyue Liu, Yuanhang Sun, Gang Huang, Xuanzhe Liu, Xin Jin
conference: "Arxiv"
year: 2023
bibkey: wu2023fast
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.05920'}
tags: ['RAG', 'GPT', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
Large language models (LLMs) power a new generation of interactive AI
applications exemplified by ChatGPT. The interactive nature of these
applications demands low latency for LLM inference. Existing LLM serving
systems use run-to-completion processing for inference jobs, which suffers from
head-of-line blocking and long latency.
  We present FastServe, a distributed inference serving system for LLMs.
FastServe exploits the autoregressive pattern of LLM inference to enable
preemption at the granularity of each output token. FastServe uses preemptive
scheduling to minimize latency with a novel skip-join Multi-Level Feedback
Queue scheduler. Based on the new semi-information-agnostic setting of LLM
inference, the scheduler leverages the input length information to assign an
appropriate initial queue for each arrival job to join. The higher priority
queues than the joined queue are skipped to reduce demotions. We design an
efficient GPU memory management mechanism that proactively offloads and uploads
intermediate state between GPU memory and host memory for LLM inference. We
build a system prototype of FastServe and experimental results show that
compared to the state-of-the-art solution vLLM, FastServe improves the
throughput by up to 31.4x and 17.9x under the same average and tail latency
requirements, respectively.
