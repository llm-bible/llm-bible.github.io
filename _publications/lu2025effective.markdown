---
layout: publication
title: 'Effective Length Extrapolation Via Dimension-wise Positional Embeddings Manipulation'
authors: Yi Lu, Wanxu Zhao, Xin Zhou, Chenxin An, Chenglong Wang, Shuo Li, Yuming Yang, Jun Zhao, Tao Ji, Tao Gui, Qi Zhang, Xuanjing Huang
conference: "Arxiv"
year: 2025
bibkey: lu2025effective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18857"}
tags: ['Tools', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism']
---
Large Language Models (LLMs) often struggle to process and generate coherent
context when the number of input tokens exceeds the pre-trained length. Recent
advancements in long-context extension have significantly expanded the context
window of LLMs but require expensive overhead to train the large-scale models
with longer context. In this work, we propose Dimension-Wise Positional
Embeddings Manipulation (DPE), a training-free framework to extrapolate the
context window of LLMs by diving into RoPE's different hidden dimensions.
Instead of manipulating all dimensions equally, DPE detects the effective
length for every dimension and finds the key dimensions for context extension.
We reuse the original position indices with their embeddings from the
pre-trained model and manipulate the key dimensions' position indices to their
most effective lengths. In this way, DPE adjusts the pre-trained models with
minimal modifications while ensuring that each dimension reaches its optimal
state for extrapolation. DPE significantly surpasses well-known baselines such
as YaRN and Self-Extend. DPE enables Llama3-8k 8B to support context windows of
128k tokens without continual training and integrates seamlessly with Flash
Attention 2. In addition to its impressive extrapolation capability, DPE also
dramatically improves the models' performance within training length, such as
Llama3.1 70B, by over 18 points on popular long-context benchmarks RULER. When
compared with commercial models, Llama 3.1 70B with DPE even achieves better
performance than GPT-4-128K.
