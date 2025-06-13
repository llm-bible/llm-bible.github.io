---
layout: publication
title: 'Activation-informed Merging Of Large Language Models'
authors: Amin Heyrani Nobari, Kaveh Alimohammadi, Ali Arjomandbigdeli, Akash Srivastava, Faez Ahmed, Navid Azizan
conference: "Arxiv"
year: 2025
bibkey: nobari2025activation
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.02421'}
tags: ['Efficiency and Optimization', 'Security', 'Merging']
---
Model merging, a method that combines the parameters and embeddings of
multiple fine-tuned large language models (LLMs), offers a promising approach
to enhance model performance across various tasks while maintaining
computational efficiency. This paper introduces Activation-Informed Merging
(AIM), a technique that integrates the information from the activation space of
LLMs into the merging process to improve performance and robustness. AIM is
designed as a flexible, complementary solution that is applicable to any
existing merging method. It aims to preserve critical weights from the base
model, drawing on principles from continual learning~(CL) and model
compression. Utilizing a task-agnostic calibration set, AIM selectively
prioritizes essential weights during merging. We empirically demonstrate that
AIM significantly enhances the performance of merged models across multiple
benchmarks. Our findings suggest that considering the activation-space
information can provide substantial advancements in the model merging
strategies for LLMs with up to 40% increase in benchmark performance.
