---
layout: publication
title: 'Regress, Don''t Guess -- A Regression-like Loss On Number Tokens For Language Models'
authors: Jonas Zausinger, Lars Pennig, Anamarija Kozina, Sean Sdahl, Julian Sikora, Adrian Dendorfer, Timofey Kuznetsov, Mohamad Hagog, Nina Wiedemann, Kacper Chlodny, Vincent Limbach, Anna Ketteler, Thorben Prein, Vishwa Mohan Singh, Michael Morris Danziger, Jannis Born
conference: "Arxiv"
year: 2024
bibkey: zausinger2024guess
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02083"}
  - {name: "Code", url: "https://tum-ai.github.io/number-token-loss/"}
tags: ['Training Techniques', 'Language Modeling', 'Ethics and Bias', 'Pretraining Methods', 'Has Code', 'Applications']
---
While language models have exceptional capabilities at text generation, they lack a natural inductive bias for emitting numbers and thus struggle in tasks involving quantitative reasoning, especially arithmetic. One fundamental limitation is the nature of the Cross Entropy loss, which assumes a nominal scale and thus cannot convey proximity between generated number tokens. In response, we here present a regression-like loss that operates purely on token level. Our proposed Number Token Loss (NTL) comes in two flavors and minimizes either the Lp norm or the Wasserstein distance between the numerical values of the real and predicted number tokens. NTL can easily be added to any language model and extend the Cross Entropy objective during training without runtime overhead. We evaluate the proposed scheme on various mathematical datasets and find that it consistently improves performance in math-related tasks. In a direct comparison on a regression task, we find that NTL can match the performance of a regression head, despite operating on token level. Finally, we scale NTL up to 3B parameter models and observe improved performance, demonstrating its potential for seamless integration into LLMs. We hope that this work can inspire LLM developers to improve their pretraining objectives. The code is available via: https://tum-ai.github.io/number-token-loss/
