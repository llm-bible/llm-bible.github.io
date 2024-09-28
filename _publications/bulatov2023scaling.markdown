---
layout: publication
title: Scaling Transformer to 1M tokens and beyond with RMT
authors: Bulatov Aydar, Kuratov Yuri, Kapushev Yermek, Burtsev Mikhail S.
conference: "Arxiv"
year: 2023
bibkey: bulatov2023scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.11062"}
tags: ['ARXIV', 'Applications', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
A major limitation for the broader scope of problems solvable by transformers is the quadratic scaling of computational complexity with input size. In this study we investigate the recurrent memory augmentation of pre-trained transformer models to extend input context length while linearly scaling compute. Our approach demonstrates the capability to store information in memory for sequences of up to an unprecedented two million tokens while maintaining high retrieval accuracy. Experiments with language modeling tasks show perplexity improvement as the number of processed input segments increases. These results underscore the effectiveness of our method which has significant potential to enhance long-term dependency handling in natural language understanding and generation tasks as well as enable large-scale context processing for memory-intensive applications.
