---
layout: publication
title: medium Lms Of Code In The Era Of Llms Lessons From Stackoverflow
authors: Mukherjee Manisha, Hellendoorn Vincent J.
conference: "Arxiv"
year: 2023
bibkey: mukherjee2023lms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.03268"}
tags: ['Applications', 'BERT', 'GPT', 'Model Architecture', 'Multimodal Models', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large pre45;trained neural language models have brought immense progress to both NLP and software engineering. Models in OpenAIs GPT series now dwarf Googles BERT and Metas RoBERTa which previously set new benchmarks on a wide range of NLP applications. These models are trained on massive corpora of heterogeneous data from web crawls which enables them to learn general language patterns and semantic relationships. However the largest models are both expensive to train and deploy and are often closed45;source so we lack access to their data and design decisions. We argue that this trend towards large general45;purpose models should be complemented with single45;purpose more modestly sized pre45;trained models. In this work we take StackOverflow (SO) as a domain example in which large volumes of rich aligned code and text data is available. We adopt standard practices for pre45;training large language models including using a very large context size (2048 tokens) batch size (0.5M tokens) and training set (27B tokens) coupled with a powerful toolkit (Megatron45;LM) to train two models SOBertBase with 109M parameters and SOBertLarge with 762M parameters at a budget of just 187 and 800 each. We compare the performance of our models with both the previous SOTA model trained on SO data exclusively as well general45;purpose BERT models and OpenAIs ChatGPT on four SO45;specific downstream tasks 45; question quality prediction closed question prediction named entity recognition and obsoletion prediction (a new task we introduce). Not only do our models consistently outperform all baselines the smaller model is often sufficient for strong results. Both models are released to the public. These results demonstrate that pre45;training both extensively and properly on in45;domain data can yield a powerful and affordable alternative to leveraging closed45;source general45;purpose models.
