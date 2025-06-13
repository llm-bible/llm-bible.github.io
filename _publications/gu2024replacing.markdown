---
layout: publication
title: 'Retok: Replacing Tokenizer To Enhance Representation Efficiency In Large Language Model'
authors: Shuhao Gu, Mengdi Zhao, Bowen Zhang, Liangdong Wang, Jijie Li, Guang Liu
conference: "Arxiv"
year: 2024
bibkey: gu2024replacing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.04335'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques']
---
Tokenizer is an essential component for large language models (LLMs), and a
tokenizer with a high compression rate can improve the model's representation
and processing efficiency. However, the tokenizer cannot ensure high
compression rate in all scenarios, and an increase in the average input and
output lengths will increases the training and inference costs of the model.
Therefore, it is crucial to find ways to improve the model's efficiency with
minimal cost while maintaining the model's performance. In this work, we
propose a method to improve model representation and processing efficiency by
replacing the tokenizers of LLMs. We propose replacing and reinitializing the
parameters of the model's input and output layers with the parameters of the
original model, and training these parameters while keeping other parameters
fixed. We conducted experiments on different LLMs, and the results show that
our method can maintain the performance of the model after replacing the
tokenizer, while significantly improving the decoding speed for long texts.
