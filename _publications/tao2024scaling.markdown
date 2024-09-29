---
layout: publication
title: Scaling Laws With Vocabulary Larger Models Deserve Larger Vocabularies
authors: Tao Chaofan, Liu Qian, Dou Longxu, Muennighoff Niklas, Wan Zhongwei, Luo Ping, Lin Min, Wong Ngai
conference: "Arxiv"
year: 2024
bibkey: tao2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.13623"}
tags: ['Efficiency And Optimization', 'Large Scale Training', 'Model Architecture', 'Reinforcement Learning', 'Scaling Laws', 'Training Techniques']
---
Research on scaling large language models (LLMs) has primarily focused on model parameters and training data size overlooking the role of vocabulary size. We investigate how vocabulary size impacts LLM scaling laws by training models ranging from 33M to 3B parameters on up to 500B characters with various vocabulary configurations. We propose three complementary approaches for predicting the compute-optimal vocabulary size IsoFLOPs analysis derivative estimation and parametric fit of the loss function. Our approaches converge on the same result that the optimal vocabulary size depends on the available compute budget and that larger models deserve larger vocabularies. However most LLMs use too small vocabulary sizes. For example we predict that the optimal vocabulary size of Llama2-70B should have been at least 216K 7 times larger than its vocabulary of 32K. We validate our predictions empirically by training models with 3B parameters across different FLOPs budgets. Adopting our predicted optimal vocabulary size consistently improves downstream performance over commonly used vocabulary sizes. By increasing the vocabulary size from the conventional 32K to 43K we improve performance on ARC-Challenge from 29.1 to 32.0 with the same 2.3e21 FLOPs. Our work emphasizes the necessity of jointly considering model parameters and vocabulary size for efficient scaling.
