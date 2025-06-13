---
layout: publication
title: 'How Much Can We Forget About Data Contamination?'
authors: Sebastian Bordt, Suraj Srinivas, Valentyn Boreiko, Ulrike Von Luxburg
conference: "Arxiv"
year: 2024
bibkey: bordt2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03249"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Scaling Laws', 'Large-Scale Training', 'Pre-Training']
---
The leakage of benchmark data into the training data has emerged as a
significant challenge for evaluating the capabilities of large language models
(LLMs). In this work, we challenge the common assumption that small-scale
contamination renders benchmark evaluations invalid. First, we experimentally
quantify the magnitude of benchmark overfitting based on scaling along three
dimensions: The number of model parameters (up to 1.6B), the number of times an
example is seen (up to 144), and the number of training tokens (up to 40B). If
model and data follow the Chinchilla scaling laws, minor contamination indeed
leads to overfitting. At the same time, even 144 times of contamination can be
forgotten if the training data is scaled beyond five times Chinchilla, a regime
characteristic of many modern LLMs. Continual pre-training of OLMo-7B
corroborates these results. Next, we study the impact of the weight decay
parameter on example forgetting, showing that empirical forgetting occurs
faster than the cumulative weight decay. This allows us to gauge the degree of
example forgetting in large-scale training runs, indicating that many LLMs,
including Lllama 3 405B, have forgotten the data seen at the beginning of
training.
