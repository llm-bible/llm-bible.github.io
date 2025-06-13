---
layout: publication
title: 'Fast Inference Of Mixture-of-experts Language Models With Offloading'
authors: Artyom Eliseev, Denis Mazur
conference: "Arxiv"
year: 2023
bibkey: eliseev2023fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17238"}
tags: ['Quantization', 'Efficiency and Optimization', 'Model Architecture']
---
With the widespread adoption of Large Language Models (LLMs), many deep
learning practitioners are looking for strategies of running these models more
efficiently. One such strategy is to use sparse Mixture-of-Experts (MoE) - a
type of model architectures where only a fraction of model layers are active
for any given input. This property allows MoE-based language models to generate
tokens faster than their dense counterparts, but it also increases model size
due to having multiple experts. Unfortunately, this makes state-of-the-art MoE
language models difficult to run without high-end GPUs. In this work, we study
the problem of running large MoE language models on consumer hardware with
limited accelerator memory. We build upon parameter offloading algorithms and
propose a novel strategy that accelerates offloading by taking advantage of
innate properties of MoE LLMs. Using this strategy, we build can run
Mixtral-8x7B with mixed quantization on desktop hardware and free-tier Google
Colab instances.
