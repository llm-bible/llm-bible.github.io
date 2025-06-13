---
layout: publication
title: 'Enhancing Token Filtering Efficiency In Large Language Model Training With Collider'
authors: Di Chai, Pengbo Li, Feiyuan Zhang, Yilun Jin, Han Tian, Junxue Zhang, Kai Chen
conference: "Arxiv"
year: 2025
bibkey: chai2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.00340"}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Tools']
---
Token filtering has been proposed to enhance utility of large language models
(LLMs) by eliminating inconsequential tokens during training. While using fewer
tokens should reduce computational workloads, existing studies have not
succeeded in achieving higher efficiency. This is primarily due to the
insufficient sparsity caused by filtering tokens only in the output layers, as
well as inefficient sparse GEMM (General Matrix Multiplication), even when
having sufficient sparsity.
  This paper presents Collider, a system unleashing the full efficiency of
token filtering in LLM training. At its core, Collider filters activations of
inconsequential tokens across all layers to maintain sparsity. Additionally, it
features an automatic workflow that transforms sparse GEMM into
dimension-reduced dense GEMM for optimized efficiency. Evaluations on three
LLMs-TinyLlama-1.1B, Qwen2.5-1.5B, and Phi1.5-1.4B-demonstrate that Collider
reduces backpropagation time by up to 35.1% and end-to-end training time by up
to 22.0% when filtering 40% of tokens. Utility assessments of training
TinyLlama on 15B tokens indicate that Collider sustains the utility
advancements of token filtering by relatively improving model utility by 16.3%
comparing to regular training, and reduces training time from 4.7 days to 3.5
days using 8 GPUs. Collider is designed for easy integration into existing LLM
training frameworks, allowing systems already using token filtering to
accelerate training with just one line of code.
