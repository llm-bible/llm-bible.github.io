---
layout: publication
title: 'Recurformer: Not All Transformer Heads Need Self-attention'
authors: Ruiqing Yan, Linghan Zheng, Xingbo Du, Han Zou, Yufeng Guo, Jianfei Yang
conference: "Arxiv"
year: 2024
bibkey: yan2024not
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12850"}
tags: ['Transformer', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Transformer-based large language models (LLMs) excel in modeling complex
language patterns but face significant computational costs during inference,
especially with long inputs due to the attention mechanism's memory overhead.
We observe that certain attention heads exhibit a distribution where the
attention weights concentrate on tokens near the query token, termed as recency
aware, which focuses on local and short-range dependencies. Leveraging this
insight, we propose RecurFormer, a novel architecture that replaces these
attention heads with linear recurrent neural networks (RNNs), specifically the
Mamba architecture. This replacement reduces the cache size without evicting
tokens, thus maintaining generation quality. RecurFormer retains the ability to
model long-range dependencies through the remaining attention heads and allows
for reusing pre-trained Transformer-based LLMs weights with continual training.
Experiments demonstrate that RecurFormer matches the original model's
performance while significantly enhancing inference efficiency. Our approach
provides a practical solution to the computational challenges of
Transformer-based LLMs inference, making it highly attractive for tasks
involving long inputs.
