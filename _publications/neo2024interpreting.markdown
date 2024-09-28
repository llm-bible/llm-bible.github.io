---
layout: publication
title: Interpreting Context Look-ups in Transformers Investigating Attention-MLP Interactions
authors: Neo Clement, Cohen Shay B., Barez Fazl
conference: "Arxiv"
year: 2024
bibkey: neo2024interpreting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15055"}
tags: ['ARXIV', 'Attention Mechanism', 'GPT', 'Interpretability And Interpretability', 'LLM', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Transformer']
---
In this paper we investigate the interplay between attention heads and specialized next-token neurons in the Multilayer Perceptron that predict specific tokens. By prompting an LLM like GPT-4 to explain these model internals we can elucidate attention mechanisms that activate certain next-token neurons. Our analysis identifies attention heads that recognize contexts relevant to predicting a particular token activating the associated neuron through the residual connection. We focus specifically on heads in earlier layers consistently activating the same next-token neuron across similar prompts. Exploring these differential activation patterns reveals that heads that specialize for distinct linguistic contexts are tied to generating certain tokens. Overall our method combines neural explanations and probing isolated components to illuminate how attention enables context-dependent specialized processing in LLMs.
