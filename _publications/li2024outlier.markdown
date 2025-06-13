---
layout: publication
title: 'Owlore: Outlier-weighed Layerwise Sampled Low-rank Projection For Memory-efficient LLM Fine-tuning'
authors: Pengxiang Li, Lu Yin, Xiaowei Gao, Shiwei Liu
conference: "Arxiv"
year: 2024
bibkey: li2024outlier
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.18380"}
  - {name: "Code", url: "https://github.com/pixeli99/OwLore"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
The rapid advancements in Large Language Models (LLMs) have revolutionized
various natural language processing tasks. However, the substantial size of
LLMs presents significant challenges in training or fine-tuning. While
parameter-efficient approaches such as low-rank adaptation (LoRA) have gained
popularity, they often compromise performance compared to full-rank
fine-tuning. In this paper, we propose Outlier-weighed Layerwise Sampled
Low-Rank Projection (OwLore), a new memory-efficient fine-tuning approach,
inspired by the layerwise outlier distribution of LLMs. Unlike LoRA, which adds
extra adapters to all layers, OwLore strategically assigns higher sampling
probabilities to layers with more outliers, selectively sampling only a few
layers and fine-tuning their pre-trained weights. To further increase the
number of fine-tuned layers without a proportional rise in memory costs, we
incorporate gradient low-rank projection, further boosting the approach's
performance. Our extensive experiments across various architectures, including
LLaMa2, LLaMa3, and Mistral, demonstrate that OwLore consistently outperforms
baseline approaches, including full fine-tuning. Specifically, it achieves up
to a 1.1% average accuracy gain on the Commonsense Reasoning benchmark, a 3.0%
improvement on MMLU, and a notable 10% boost on MT-Bench, while being more
memory efficient. OwLore allows us to fine-tune LLaMa2-7B with only 21GB of
memory. Code is available at https://github.com/pixeli99/OwLore.
