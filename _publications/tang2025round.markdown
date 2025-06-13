---
layout: publication
title: 'Round Attention: A Novel Round-level Attention Mechanism To Accelerate LLM Inference'
authors: Yaohua Tang, Zhicheng Hu, Kun Cheng, Fan Mo, Qiheng Lv, Hua Wang, Zhi Chen
conference: "Arxiv"
year: 2025
bibkey: tang2025round
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15294"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Transformer', 'Attention Mechanism']
---
The increasing context window size in large language models (LLMs) has
improved their ability to handle complex, long-text tasks. However, as the
conversation rounds continue, it is required to store a large amount of KV
cache in GPU memory, which significantly affects the efficiency and even
availability of the model serving systems. This paper analyzes dialogue data
from real users and discovers that the LLM inference manifests a watershed
layer, after which the distribution of round-level attention shows notable
similarity. We propose Round Attention, a novel round-level attention mechanism
that only recalls and computes the KV cache of the most relevant rounds. The
experiments show that our method saves 55% memory usage without compromising
model performance.
