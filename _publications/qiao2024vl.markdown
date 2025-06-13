---
layout: publication
title: 'Vl-mamba: Exploring State Space Models For Multimodal Learning'
authors: Yanyuan Qiao, Zheng Yu, Longteng Guo, Sihan Chen, Zijia Zhao, Mingzhen Sun, Qi Wu, Jing Liu
conference: "Arxiv"
year: 2024
bibkey: qiao2024vl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13600"}
tags: ['Multimodal Models', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
Multimodal large language models (MLLMs) have attracted widespread interest
and have rich applications. However, the inherent attention mechanism in its
Transformer structure requires quadratic complexity and results in expensive
computational overhead. Therefore, in this work, we propose VL-Mamba, a
multimodal large language model based on state space models, which have been
shown to have great potential for long-sequence modeling with fast inference
and linear scaling in sequence length. Specifically, we first replace the
transformer-based backbone language model such as LLama or Vicuna with the
pre-trained Mamba language model. Then, we empirically explore how to
effectively apply the 2D vision selective scan mechanism for multimodal
learning and the combinations of different vision encoders and variants of
pretrained Mamba language models. The extensive experiments on diverse
multimodal benchmarks with competitive performance show the effectiveness of
our proposed VL-Mamba and demonstrate the great potential of applying state
space models for multimodal learning tasks.
