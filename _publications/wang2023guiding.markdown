---
layout: publication
title: Guiding Language Model Reasoning with Planning Tokens
authors: Wang Xinyi, Caccia Lucas, Ostapenko Oleksiy, Yuan Xingdi, Wang William Yang, Sordoni Alessandro
conference: "Arxiv"
year: 2023
bibkey: wang2023guiding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05707"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large language models (LLMs) have recently attracted considerable interest for their ability to perform complex reasoning tasks such as chain-of-thought (CoT) reasoning. However most of the existing approaches to enhance this ability rely heavily on data-driven methods while neglecting the structural aspects of the models reasoning capacity. To encourage a more structural generation of CoT steps we propose a hierarchical generation scheme we let the LM generate a planning token at the start of each reasoning step intuitively serving as a high-level plan of the current step and add their embeddings to the model parameters. Our approach requires a negligible increase in trainable parameters (0.001) and can be applied through either full fine-tuning or a more parameter-efficient scheme. We demonstrate our methods effectiveness by applying it to three different LLMs showing notable accuracy improvements across three math word problem datasets and one multihop QA dataset with respect to standard fine-tuning baselines.
