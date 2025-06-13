---
layout: publication
title: 'FTP: A Fine-grained Token-wise Pruner For Large Language Models Via Token Routing'
authors: Zekai Li, Jintu Zheng, Ji Liu, Han Liu, Haowei Zhu, Zeping Li, Fuwei Yang, Haiduo Huang, Jinzhang Peng, Dong Li, Lu Tian, Emad Barsoum
conference: "Arxiv"
year: 2024
bibkey: li2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11494"}
tags: ['Pre-Training', 'GPT', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Pruning', 'Large-Scale Training', 'Training Techniques', 'Scaling Laws']
---
Recently, large language models (LLMs) have demonstrated superior performance
across various tasks by adhering to scaling laws, which significantly increase
model size. However, the huge computation overhead during inference hinders the
deployment in industrial applications. Many works leverage traditional
compression approaches to boost model inference, but these always introduce
additional training costs to restore the performance and the pruning results
typically show noticeable performance drops compared to the original model when
aiming for a specific level of acceleration. To address these issues, we
propose a fine-grained token-wise pruning approach for the LLMs, which presents
a learnable router to adaptively identify the less important tokens and skip
them across model blocks to reduce computational cost during inference. To
construct the router efficiently, we present a search-based sparsity scheduler
for pruning sparsity allocation, a trainable router combined with our proposed
four low-dimensional factors as input and three proposed losses. We conduct
extensive experiments across different benchmarks on different LLMs to
demonstrate the superiority of our method. Our approach achieves
state-of-the-art (SOTA) pruning results, surpassing other existing pruning
methods. For instance, our method outperforms BlockPruner and ShortGPT by
approximately 10 points on both LLaMA2-7B and Qwen1.5-7B in accuracy retention
at comparable token sparsity levels.
