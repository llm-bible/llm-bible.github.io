---
layout: publication
title: 'Llms On The Line: Data Determines Loss-to-loss Scaling Laws'
authors: Prasanna Mayilvahanan, Thaddäus Wiedemer, Sayak Mallick, Matthias Bethge, Wieland Brendel
conference: "Arxiv"
year: 2025
bibkey: mayilvahanan2025llms
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.12120'}
tags: ['Large-Scale Training', 'Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Scaling Laws', 'Pre-Training', 'Pretraining Methods']
---
Scaling laws guide the development of large language models (LLMs) by
offering estimates for the optimal balance of model size, tokens, and compute.
More recently, loss-to-loss scaling laws that relate losses across pretraining
datasets and downstream tasks have emerged as a powerful tool for understanding
and improving LLM performance. In this work, we investigate which factors most
strongly influence loss-to-loss scaling. Our experiments reveal that the
pretraining data and tokenizer determine the scaling trend. In contrast, model
size, optimization hyperparameters, and even significant architectural
differences, such as between transformer-based models like Llama and
state-space models like Mamba, have limited impact. Consequently, practitioners
should carefully curate suitable pretraining datasets for optimal downstream
performance, while architectures and other settings can be freely optimized for
training efficiency.
