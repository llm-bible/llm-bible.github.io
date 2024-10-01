---
layout: publication
title: '"medium" Lms Of Code In The Era Of Llms: Lessons From Stackoverflow'
authors: Mukherjee Manisha, Hellendoorn Vincent J.
conference: "Arxiv"
year: 2023
bibkey: mukherjee2023lms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.03268"}
tags: ['Applications', 'BERT', 'GPT', 'Model Architecture', 'Multimodal Models', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
"Large pre-trained neural language models have brought immense progress to both NLP and software engineering. Models in OpenAI's GPT series now dwarf Google's BERT and Meta's RoBERTa, which previously set new benchmarks on a wide range of NLP applications. These models are trained on massive corpora of heterogeneous data from web crawls, which enables them to learn general language patterns and semantic relationships. However, the largest models are both expensive to train and deploy and are often closed-source, so we lack access to their data and design decisions. We argue that this trend towards large, general-purpose models should be complemented with single-purpose, more modestly sized pre-trained models. In this work, we take StackOverflow (SO) as a domain example in which large volumes of rich aligned code and text data is available. We adopt standard practices for pre-training large language models, including using a very large context size (2,048 tokens), batch size (0.5M tokens) and training set (27B tokens), coupled with a powerful toolkit (Megatron-LM), to train two models: SOBertBase, with 109M parameters, and SOBertLarge with 762M parameters, at a budget of just \(\\)187\( and \)\\(800\) each. We compare the performance of our models with both the previous SOTA model trained on SO data exclusively as well general-purpose BERT models and OpenAI's ChatGPT on four SO-specific downstream tasks - question quality prediction, closed question prediction, named entity recognition and obsoletion prediction (a new task we introduce). Not only do our models consistently outperform all baselines, the smaller model is often sufficient for strong results. Both models are released to the public. These results demonstrate that pre-training both extensively and properly on in-domain data can yield a powerful and affordable alternative to leveraging closed-source general-purpose models."
