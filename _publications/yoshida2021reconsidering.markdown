---
layout: publication
title: Reconsidering The Past Optimizing Hidden States In Language Models
authors: Yoshida Davis, Gimpel Kevin
conference: "Findings of the Association for Computational Linguistics EMNLP"
year: 2021
bibkey: yoshida2021reconsidering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.08653"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
We present Hidden45;State Optimization (HSO) a gradient45;based method for improving the performance of transformer language models at inference time. Similar to dynamic evaluation (Krause et al. 2018) HSO computes the gradient of the log45;probability the language model assigns to an evaluation text but uses it to update the cached hidden states rather than the model parameters. We test HSO with pretrained Transformer45;XL and GPT45;2 language models finding improvement on the WikiText103 and PG45;19 datasets in terms of perplexity especially when evaluating a model outside of its training distribution. We also demonstrate downstream applicability by showing gains in the recently developed prompt45;based few45;shot evaluation setting again with no extra parameters or training data.
