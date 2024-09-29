---
layout: publication
title: Refining Packing And Shuffling Strategies For Enhanced Performance In Generative Language Models
authors: Chen Yanbing, Wang Ruilin, Yang Zihao, Jiang Lavender Yao, Oermann Eric Karl
conference: "Arxiv"
year: 2024
bibkey: chen2024refining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09621"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'Training Techniques']
---
Packing and shuffling tokens is a common practice in training auto45;regressive language models (LMs) to prevent overfitting and improve efficiency. Typically documents are concatenated to chunks of maximum sequence length (MSL) and then shuffled. However setting the atom size the length for each data chunk accompanied by random shuffling to MSL may lead to contextual incoherence due to tokens from different documents being packed into the same chunk. An alternative approach is to utilize padding another common data packing strategy to avoid contextual incoherence by only including one document in each shuffled chunk. To optimize both packing strategies (concatenation vs padding) we investigated the optimal atom size for shuffling and compared their performance and efficiency. We found that matching atom size to MSL optimizes performance for both packing methods (concatenation and padding) and padding yields lower final perplexity (higher performance) than concatenation at the cost of more training steps and lower compute efficiency. This trade45;off informs the choice of packing methods in training language models.
