---
layout: publication
title: 'In-context Kv-cache Eviction For Llms Via Attention-gate'
authors: Zihao Zeng, Bokai Lin, Tianqi Hou, Hao Zhang, Zhijie Deng
conference: "Arxiv"
year: 2024
bibkey: zeng2024kv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12876"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
The KV-Cache technique has become the standard for the inference of large
language models (LLMs). Yet, it is widely criticized that KV-Cache can become a
bottleneck of the LLM inference system. This paper enables a novel dynamic
KV-Cache eviction policy by injecting a lightweight module called
Attention-Gate to the model. It accepts the global context as input and yields
eviction flags for each token. The self-attention modules in the model proceed
according to the flags and cache only a subset of the KV states for next token
prediction. The Attention-Gates can yield various flags for different heads and
layers and be easily tuned on top of a pre-trained LLM via continual
pre-training or supervised fine-tuning. The computational and memory overhead
introduced by Attention-Gates can be minimal. We empirically evaluate the
proposed approach across multiple scenarios, showing that effective eviction of
redundant tokens can not only improve efficiency but also enhance performance.
