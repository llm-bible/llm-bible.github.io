---
layout: publication
title: 'Interpreting And Controlling Vision Foundation Models Via Text Explanations'
authors: Haozhe Chen, Junfeng Yang, Carl Vondrick, Chengzhi Mao
conference: "Arxiv"
year: 2023
bibkey: chen2023interpreting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.10591'}
tags: ['Interpretability and Explainability', 'Transformer', 'Security', 'Model Architecture', 'Tools', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods']
---
Large-scale pre-trained vision foundation models, such as CLIP, have become
de facto backbones for various vision tasks. However, due to their black-box
nature, understanding the underlying rules behind these models' predictions and
controlling model behaviors have remained open challenges. We present a
framework for interpreting vision transformer's latent tokens with natural
language. Given a latent token, our framework retains its semantic information
to the final layer using transformer's local operations and retrieves the
closest text for explanation. Our approach enables understanding of model
visual reasoning procedure without needing additional model training or data
collection. Based on the obtained interpretations, our framework allows for
model editing that controls model reasoning behaviors and improves model
robustness against biases and spurious correlations.
