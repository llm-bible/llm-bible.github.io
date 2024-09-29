---
layout: publication
title: You Only Cache Once Decoder-decoder Architectures For Language Models
authors: Sun Yutao, Dong Li, Zhu Yi, Huang Shaohan, Wang Wenhui, Ma Shuming, Zhang Quanlu, Wang Jianyong, Wei Furu
conference: "Arxiv"
year: 2024
bibkey: sun2024you
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.05254"}
  - {name: "Code", url: "https://aka.ms/YOCO"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
We introduce a decoder-decoder architecture YOCO for large language models which only caches key-value pairs once. It consists of two components i.e. a cross-decoder stacked upon a self-decoder. The self-decoder efficiently encodes global key-value (KV) caches that are reused by the cross-decoder via cross-attention. The overall model behaves like a decoder-only Transformer although YOCO only caches once. The design substantially reduces GPU memory demands yet retains global attention capability. Additionally the computation flow enables prefilling to early exit without changing the final output thereby significantly speeding up the prefill stage. Experimental results demonstrate that YOCO achieves favorable performance compared to Transformer in various settings of scaling up model size and number of training tokens. We also extend YOCO to 1M context length with near-perfect needle retrieval accuracy. The profiling results show that YOCO improves inference memory prefill latency and throughput by orders of magnitude across context lengths and model sizes. Code is available at https://aka.ms/YOCO.
