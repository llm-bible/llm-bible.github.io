---
layout: publication
title: 'SD\(^2\): Self-distilled Sparse Drafters'
authors: Mike Lasby, Nish Sinnadurai, Valavan Manohararajah, Sean Lie, Yani Ioannou, Vithursan Thangarasa
conference: "Arxiv"
year: 2025
bibkey: lasby2025self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.08838'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Speculative decoding is a powerful technique for reducing the latency of Large Language Models (LLMs), offering a fault-tolerant framework that enables the use of highly compressed draft models. In this work, we introduce Self-Distilled Sparse Drafters (SD\\(^2\\)), a novel methodology that leverages self-data distillation and fine-grained weight sparsity to produce highly efficient and well-aligned draft models. SD\\(^2\\) systematically enhances draft token acceptance rates while significantly reducing Multiply-Accumulate operations (MACs), even in the Universal Assisted Generation (UAG) setting, where draft and target models originate from different model families. On a Llama-3.1-70B target model, SD\\(^2\\) provides a 1.59\\(\times\\) higher Mean Accepted Length (MAL) compared to layer-pruned draft models and reduces MACs by over 43.87% with a 8.36% reduction in MAL compared to a dense draft models. Our 1.5B and 3B unstructured sparse drafters outperform both dense and layer-pruned models in terms of end-to-end latency improvements; highlighting the potential of sparsity-aware fine-tuning and compression strategies to improve LLM inference efficiency while maintaining alignment with target models.
