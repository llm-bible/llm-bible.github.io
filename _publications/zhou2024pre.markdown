---
layout: publication
title: Pre45;trained Large Language Models Use Fourier Features To Compute Addition
authors: Zhou Tianyi, Fu Deqing, Sharan Vatsal, Jia Robin
conference: "Arxiv"
year: 2024
bibkey: zhou2024pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03445"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Pre45;trained large language models (LLMs) exhibit impressive mathematical reasoning capabilities yet how they compute basic arithmetic such as addition remains unclear. This paper shows that pre45;trained LLMs add numbers using Fourier features 45;45; dimensions in the hidden state that represent numbers via a set of features sparse in the frequency domain. Within the model MLP and attention layers use Fourier features in complementary ways MLP layers primarily approximate the magnitude of the answer using low45;frequency features while attention layers primarily perform modular addition (e.g. computing whether the answer is even or odd) using high45;frequency features. Pre45;training is crucial for this mechanism models trained from scratch to add numbers only exploit low45;frequency features leading to lower accuracy. Introducing pre45;trained token embeddings to a randomly initialized model rescues its performance. Overall our analysis demonstrates that appropriate pre45;trained representations (e.g. Fourier features) can unlock the ability of Transformers to learn precise mechanisms for algorithmic tasks.
