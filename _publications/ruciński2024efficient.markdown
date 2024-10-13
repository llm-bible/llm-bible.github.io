---
layout: publication
title: 'Efficient Language Adaptive Pre-training: Extending State-of-the-art Large Language Models For Polish'
authors: Ruciński Szymon
conference: "Arxiv"
year: 2024
bibkey: ruciński2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09759"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
This study explores the potential of fine-tuning foundational English Large
Language Models (LLMs) for generating Polish text. The first step involves
Language Adaptive Pre-training (LAPT) on a high-quality dataset of 3.11 GB,
consisting of 276 million Polish tokens. The LAPT is followed by additional
fine-tuning aimed at solving nine KLEJ challenges. Our trained model
Curie-7B-v1 not only generates Polish text with the lowest perplexity of 3.02
among decoder-based Polish models but also closely rivals the performance of
the best Polish encoder-decoder models with a less than 2% gap on 8 out of 9
tasks. Curie-7B-v1 used approximately 2-3% of a typical dataset size to learn
Polish. The LAPT was completed in less than five days using a consumer GPU,
highlighting the method's efficiency. The proficiency of the model in Polish
was significantly enhanced, demonstrating the viability of this approach for
adding new languages to existing LLMs by training just 1.2% of its parameters.
To contribute to the community's collaborative progress, the model has been
released as open-source.
