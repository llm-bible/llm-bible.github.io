---
layout: publication
title: 'Iceformer: Accelerated Inference With Long-sequence Transformers On Cpus'
authors: Yuzhen Mao, Martin Ester, Ke Li
conference: "Arxiv"
year: 2024
bibkey: mao2024accelerated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.02842"}
  - {name: "Code", url: "https://yuzhenmao.github.io/IceFormer/"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Pretraining Methods', 'Transformer', 'Has Code', 'Attention Mechanism']
---
One limitation of existing Transformer-based models is that they cannot
handle very long sequences as input since their self-attention operations
exhibit quadratic time and space complexity. This problem becomes especially
acute when Transformers are deployed on hardware platforms equipped only with
CPUs. To address this issue, we propose a novel method for accelerating
self-attention at inference time that works with pretrained Transformer models
out-of-the-box without requiring retraining. We experiment using our method to
accelerate various long-sequence Transformers, including a leading LLaMA
2-based LLM, on various benchmarks and demonstrate a greater speedup of 2.73x -
7.63x while retaining 98.6% - 99.6% of the accuracy of the original pretrained
models. The code is available on our project website at
https://yuzhenmao.github.io/IceFormer/.
