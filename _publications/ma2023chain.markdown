---
layout: publication
title: 'Chain-of-skills: A Configurable Model For Open-domain Question Answering'
authors: Kaixin Ma, Hao Cheng, Yu Zhang, Xiaodong Liu, Eric Nyberg, Jianfeng Gao
conference: "Arxiv"
year: 2023
bibkey: ma2023chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.03130"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Applications']
---
The retrieval model is an indispensable component for real-world
knowledge-intensive tasks, e.g., open-domain question answering (ODQA). As
separate retrieval skills are annotated for different datasets, recent work
focuses on customized methods, limiting the model transferability and
scalability. In this work, we propose a modular retriever where individual
modules correspond to key skills that can be reused across datasets. Our
approach supports flexible skill configurations based on the target domain to
boost performance. To mitigate task interference, we design a novel
modularization parameterization inspired by sparse Transformer. We demonstrate
that our model can benefit from self-supervised pretraining on Wikipedia and
fine-tuning using multiple ODQA datasets, both in a multi-task fashion. Our
approach outperforms recent self-supervised retrievers in zero-shot evaluations
and achieves state-of-the-art fine-tuned retrieval performance on NQ, HotpotQA
and OTT-QA.
