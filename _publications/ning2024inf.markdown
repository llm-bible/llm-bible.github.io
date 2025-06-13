---
layout: publication
title: 'Inf-mllm: Efficient Streaming Inference Of Multimodal Large Language Models On A Single GPU'
authors: Zhenyu Ning, Jieru Zhao, Qihao Jin, Wenchao Ding, Minyi Guo
conference: "Arxiv"
year: 2024
bibkey: ning2024inf
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.09086"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Ethics and Bias', 'Applications', 'Attention Mechanism']
---
Multimodal Large Language Models (MLLMs) are distinguished by their
multimodal comprehensive ability and widely used in many real-world
applications including GPT-4o, autonomous driving and robotics. Despite their
impressive performance, the multimodal inputs always incur long context. The
inference under long context requires caching massive Key and Value states (KV
cache) of previous tokens, which introduces high latency and excessive memory
consumption. Due to this reason, it is challenging to deploy streaming
inference of MLLMs on edge devices, which largely constrains the power and
usage of MLLMs in real-world applications. In this paper, we introduce
Inf-MLLM, an efficient inference framework for MLLMs, which enable streaming
inference of MLLM on a single GPU with infinite context. Inf-MLLM is based on
our key observation of the attention pattern in both LLMs and MLLMs called
"attention saddles". Thanks to the newly discovered attention pattern, Inf-MLLM
maintains a size-constrained KV cache by dynamically caching recent tokens and
relevant tokens. Furthermore, Inf-MLLM proposes attention bias, a novel
approach to enable MLLMs to capture long-term dependency. We show that Inf-MLLM
enables multiple LLMs and MLLMs to achieve stable performance over 4M-token
long texts and multi-round conversations with 1-hour-long videos on a single
GPU. In addition, Inf-MLLM exhibits superior streaming reasoning quality than
existing methods such as StreamingLLM and 2x speedup than H2O.
