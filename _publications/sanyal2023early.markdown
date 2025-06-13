---
layout: publication
title: 'Early Weight Averaging Meets High Learning Rates For LLM Pre-training'
authors: Sunny Sanyal, Atula Neerkaje, Jean Kaddour, Abhishek Kumar, Sujay Sanghavi
conference: "Arxiv"
year: 2023
bibkey: sanyal2023early
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.03241"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Pre-Training']
---
Training Large Language Models (LLMs) incurs significant cost; hence, any
strategy that accelerates model convergence is helpful. In this paper, we
investigate the ability of a simple idea checkpoint averaging along the
trajectory of a training run to improve both convergence and generalization
quite early on during training. Here we show that models trained with high
learning rates observe higher gains due to checkpoint averaging. Furthermore,
these gains are amplified when checkpoints are sampled with considerable
spacing in training steps. Our training recipe outperforms conventional
training and popular checkpoint averaging baselines such as exponential moving
average (EMA) and stochastic moving average (SWA). We evaluate our training
recipe by pre-training LLMs, where high learning rates are inherently preferred
due to extremely large batch sizes. Specifically, we pre-trained nanoGPT-2
models of varying sizes, small (125M), medium (335M), and large (770M)on the
OpenWebText dataset, comprised of 9B tokens. Additionally, we present results
for publicly available Pythia LLMs, ranging from 1B to 12B, which were trained
on the PILE-deduped dataset containing 207B tokens.
