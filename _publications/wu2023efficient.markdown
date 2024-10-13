---
layout: publication
title: 'Efficient LLM Inference Solution On Intel GPU'
authors: Wu Hui, Gan Yi, Yuan Feng, Ma Jing, Zhu Wei, Xu Yutao, Zhu Hong, Zhu Yuhua, Liu Xiaoli, Gu Jinghui, Zhao Peng
conference: "Arxiv"
year: 2023
bibkey: wu2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.05391"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Transformer based Large Language Models (LLMs) have been widely used in many
fields, and the efficiency of LLM inference becomes hot topic in real
applications. However, LLMs are usually complicatedly designed in model
structure with massive operations and perform inference in the auto-regressive
mode, making it a challenging task to design a system with high efficiency.
  In this paper, we propose an efficient LLM inference solution with low
latency and high throughput. Firstly, we simplify the LLM decoder layer by
fusing data movement and element-wise operations to reduce the memory access
frequency and lower system latency. We also propose a segment KV cache policy
to keep key/value of the request and response tokens in separate physical
memory for effective device memory management, helping enlarge the runtime
batch size and improve system throughput. A customized
Scaled-Dot-Product-Attention kernel is designed to match our fusion policy
based on the segment KV cache solution. We implement our LLM inference solution
on Intel GPU and publish it publicly. Compared with the standard HuggingFace
implementation, the proposed solution achieves up to 7x lower token latency and
27x higher throughput for some popular LLMs on Intel GPU.
