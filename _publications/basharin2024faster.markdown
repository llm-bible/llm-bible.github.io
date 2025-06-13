---
layout: publication
title: 'Faster Language Models With Better Multi-token Prediction Using Tensor Decomposition'
authors: Artem Basharin, Andrei Chertkov, Ivan Oseledets
conference: "Arxiv"
year: 2024
bibkey: basharin2024faster
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.17765"}
tags: ['Transformer', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods']
---
We propose a new model for multi-token prediction in transformers, aiming to
enhance sampling efficiency without compromising accuracy. Motivated by recent
work that predicts the probabilities of subsequent tokens using multiple heads,
we connect this approach to rank-\\(1\\) canonical tensor decomposition. By
generalizing it to a rank-\\(r\\) canonical probability decomposition, we develop
an improved model that predicts multiple tokens simultaneously. This model can
also be interpreted as a mixture of experts, allowing us to leverage successful
techniques from that domain for efficient and robust training. Importantly, the
overall overhead for training and sampling remains low. Our method demonstrates
significant improvements in inference speed for both text and code generation
tasks, proving particularly beneficial within the self-speculative decoding
paradigm. It maintains its effectiveness across various model sizes and
training epochs, highlighting its robustness and scalability.
