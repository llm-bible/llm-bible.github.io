---
layout: publication
title: Accelerating Production LLMs with Combined Token/Embedding Speculators
authors: Wertheimer Davis, Rosenkranz Joshua, Parnell Thomas, Suneja Sahil, Ranganathan Pavithra, Ganti Raghu, Srivatsa Mudhakar
conference: "Arxiv"
year: 2024
bibkey: wertheimer2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.19124"}
tags: ['Efficiency And Optimization', 'Training Techniques']
---
This technical report describes the design and training of novel speculative decoding draft models for accelerating the inference speeds of large language models in a production environment. By conditioning draft predictions on both context vectors and sampled tokens we can train our speculators to efficiently predict high-quality n-grams which the base model then accepts or rejects. This allows us to effectively predict multiple tokens per inference forward pass accelerating wall-clock inference speeds of highly optimized base model implementations by a factor of 2-3x. We explore these initial results and describe next steps for further improvements.
