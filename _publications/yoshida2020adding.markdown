---
layout: publication
title: 'Adding Recurrence To Pretrained Transformers For Improved Efficiency And Context Size'
authors: Davis Yoshida, Allyson Ettinger, Kevin Gimpel
conference: "Arxiv"
year: 2020
bibkey: yoshida2020adding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2008.07027"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Transformer', 'Fine-Tuning']
---
Fine-tuning a pretrained transformer for a downstream task has become a
standard method in NLP in the last few years. While the results from these
models are impressive, applying them can be extremely computationally
expensive, as is pretraining new models with the latest architectures. We
present a novel method for applying pretrained transformer language models
which lowers their memory requirement both at training and inference time. An
additional benefit is that our method removes the fixed context size constraint
that most transformer models have, allowing for more flexible use. When applied
to the GPT-2 language model, we find that our method attains better perplexity
than an unmodified GPT-2 model on the PG-19 and WikiText-103 corpora, for a
given amount of computation or memory.
