---
layout: publication
title: 'Iterabre: Iterative Recovery-aided Block Reduction'
authors: Haryo Akbarianto Wibowo, Haiyue Song, Hideki Tanaka, Masao Utiyama, Alham Fikri Aji, Raj Dabre
conference: "Arxiv"
year: 2025
bibkey: wibowo2025iterative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.06291'}
tags: ['RAG', 'Pruning', 'Efficiency and Optimization', 'Quantization']
---
Large Language Models (LLMs) have grown increasingly expensive to deploy,
driving the need for effective model compression techniques. While block
pruning offers a straightforward approach to reducing model size, existing
methods often struggle to maintain performance or require substantial
computational resources for recovery. We present IteRABRe, a simple yet
effective iterative pruning method that achieves superior compression results
while requiring minimal computational resources. Using only 2.5M tokens for
recovery, our method outperforms baseline approaches by ~3% on average when
compressing the Llama3.1-8B and Qwen2.5-7B models. IteRABRe demonstrates
particular strength in the preservation of linguistic capabilities, showing an
improvement 5% over the baselines in language-related tasks. Our analysis
reveals distinct pruning characteristics between these models, while also
demonstrating preservation of multilingual capabilities.
