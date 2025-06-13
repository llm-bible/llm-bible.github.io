---
layout: publication
title: 'Token-picker: Accelerating Attention In Text Generation With Minimized Memory Transfer Via Probability Estimation'
authors: Junyoung Park, Myeonggu Kang, Yunki Han, Yanggon Kim, Jaekang Shin, Lee-sup Kim
conference: "Arxiv"
year: 2024
bibkey: park2024token
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.15131'}
tags: ['Attention Mechanism', 'Language Modeling', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Pruning', 'Reinforcement Learning', 'Pretraining Methods']
---
The attention mechanism in text generation is memory-bounded due to its
sequential characteristics. Therefore, off-chip memory accesses should be
minimized for faster execution. Although previous methods addressed this by
pruning unimportant tokens, they fall short in selectively removing tokens with
near-zero attention probabilities in each instance. Our method estimates the
probability before the softmax function, effectively removing low probability
tokens and achieving an 12.1x pruning ratio without fine-tuning. Additionally,
we present a hardware design supporting seamless on-demand off-chip access. Our
approach shows 2.6x reduced memory accesses, leading to an average 2.3x speedup
and a 2.4x energy efficiency.
