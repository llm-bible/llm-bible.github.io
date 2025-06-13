---
layout: publication
title: 'Deploying Open-source Large Language Models: A Performance Analysis'
authors: Yannis Bendi-ouis, Dan Dutartre, Xavier Hinaut
conference: "Arxiv"
year: 2024
bibkey: bendiouis2024deploying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.14887'}
tags: ['GPT', 'Tools', 'Model Architecture']
---
Since the release of ChatGPT in November 2022, large language models (LLMs)
have seen considerable success, including in the open-source community, with
many open-weight models available. However, the requirements to deploy such a
service are often unknown and difficult to evaluate in advance. To facilitate
this process, we conducted numerous tests at the Centre Inria de l'Universit\'e
de Bordeaux. In this article, we propose a comparison of the performance of
several models of different sizes (mainly Mistral and LLaMa) depending on the
available GPUs, using vLLM, a Python library designed to optimize the inference
of these models. Our results provide valuable information for private and
public groups wishing to deploy LLMs, allowing them to evaluate the performance
of different models based on their available hardware. This study thus
contributes to facilitating the adoption and use of these large language models
in various application domains.
