---
layout: publication
title: 'Interpreting Context Look-ups In Transformers: Investigating Attention-mlp Interactions'
authors: Clement Neo, Shay B. Cohen, Fazl Barez
conference: "Arxiv"
year: 2024
bibkey: neo2024interpreting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15055"}
tags: ['Transformer', 'Applications', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods', 'Prompting']
---
Understanding the inner workings of large language models (LLMs) is crucial
for advancing their theoretical foundations and real-world applications. While
the attention mechanism and multi-layer perceptrons (MLPs) have been studied
independently, their interactions remain largely unexplored. This study
investigates how attention heads and next-token neurons interact in LLMs to
predict new words. We propose a methodology to identify next-token neurons,
find prompts that highly activate them, and determine the upstream attention
heads responsible. We then generate and evaluate explanations for the activity
of these attention heads in an automated manner. Our findings reveal that some
attention heads recognize specific contexts relevant to predicting a token and
activate a downstream token-predicting neuron accordingly. This mechanism
provides a deeper understanding of how attention heads work with MLP neurons to
perform next-token prediction. Our approach offers a foundation for further
research into the intricate workings of LLMs and their impact on text
generation and understanding.
