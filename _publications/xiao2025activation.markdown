---
layout: publication
title: 'Activation-aware Probe-query: Effective Key-value Retrieval For Long-context Llms Inference'
authors: Qingfa Xiao, Jiachuan Wang, Haoyang Li, Cheng Deng, Jiaqi Tang, Shuangyin Li, Yongqi Zhang, Jun Wang, Lei Chen
conference: "Arxiv"
year: 2025
bibkey: xiao2025activation
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13542'}
tags: ['Attention Mechanism', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Reinforcement Learning', 'Ethics and Bias']
---
Recent advances in large language models (LLMs) have showcased exceptional
performance in long-context tasks, while facing significant inference
efficiency challenges with limited GPU memory. Existing solutions first
proposed the sliding-window approach to accumulate a set of historical
\textbf\{key-value\} (KV) pairs for reuse, then further improvements selectively
retain its subsets at each step. However, due to the sparse attention
distribution across a long context, it is hard to identify and recall relevant
KV pairs, as the attention is distracted by massive candidate pairs.
Additionally, we found it promising to select representative tokens as
probe-Query in each sliding window to effectively represent the entire context,
which is an approach overlooked by existing methods. Thus, we propose
\textbf\{ActQKV\}, a training-free, \textbf\{Act\}ivation-aware approach that
dynamically determines probe-\textbf\{Q\}uery and leverages it to retrieve the
relevant \textbf\{KV\} pairs for inference. Specifically, ActQKV monitors a
token-level indicator, Activation Bias, within each context window, enabling
the proper construction of probe-Query for retrieval at pre-filling stage. To
accurately recall the relevant KV pairs and minimize the irrelevant ones, we
design a dynamic KV cut-off mechanism guided by information density across
layers at the decoding stage. Experiments on the Long-Bench and \\(\infty\\)
Benchmarks demonstrate its state-of-the-art performance with competitive
inference quality and resource efficiency.
