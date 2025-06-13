---
layout: publication
title: 'Small Singular Values Matter: A Random Matrix Analysis Of Transformer Models'
authors: Max Staats, Matthias Thamm, Bernd Rosenow
conference: "Arxiv"
year: 2024
bibkey: staats2024small
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.17770'}
tags: ['Transformer', 'Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
As large language models (LLMs) become increasingly central to AI
applications, understanding their inner workings is essential. In this work, we
analyze the spectra of weight matrices in pretrained transformer models through
the lens of random matrix theory (RMT) to uncover learned structures. We find
that certain regions of the weight matrix spectra deviate markedly from RMT
predictions, indicating richer feature encoding. By comparing the corresponding
singular vectors to eigenvectors of activation covariance matrices, we observe
substantial overlap precisely where the spectra deviate from RMT expectations.
Our analysis further reveals the important role of small singular values in
LLMs, showing that these values contain significant information, a claim
supported by increased perplexity when they are removed from the model.
Although these small values may appear unimportant prior to task-specific
fine-tuning, removing them afterward significantly degrades performance,
revealing that fine-tuning refines the model primarily in these spectral
regions. These results emphasize the critical role of small singular values,
suggesting that removing them in an already aligned transformer can be
detrimental, as it may compromise model alignment.
