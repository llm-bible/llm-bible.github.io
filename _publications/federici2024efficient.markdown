---
layout: publication
title: 'Efficient LLM Inference Using Dynamic Input Pruning And Cache-aware Masking'
authors: Marco Federici, Davide Belli, Mart Van Baalen, Amir Jalalirad, Andrii Skliar, Bence Major, Markus Nagel, Paul Whatmough
conference: "Arxiv"
year: 2024
bibkey: federici2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.01380"}
  - {name: "Code", url: "https://github.com/Qualcomm-AI-research/dynamic-sparsity"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Pruning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
While mobile devices provide ever more compute power, improvements in DRAM
bandwidth are much slower. This is unfortunate for large language model (LLM)
token generation, which is heavily memory-bound. Previous work has proposed to
leverage natural dynamic activation sparsity in ReLU-activated LLMs to reduce
effective DRAM bandwidth per token. However, more recent LLMs use SwiGLU
instead of ReLU, which results in little inherent sparsity. While SwiGLU
activations can be pruned based on magnitude, the resulting sparsity patterns
are difficult to predict, rendering previous approaches ineffective. To
circumvent this issue, our work introduces Dynamic Input Pruning (DIP): a
predictor-free dynamic sparsification approach, which preserves accuracy with
minimal fine-tuning. DIP can further use lightweight LoRA adapters to regain
some performance lost during sparsification. Lastly, we describe a novel
cache-aware masking strategy, which considers the cache state and activation
magnitude to further increase cache hit rate, improving LLM token rate on
mobile devices. DIP outperforms other methods in terms of accuracy, memory and
throughput trade-offs across simulated hardware settings. On Phi-3-Medium, DIP
achieves a 46% reduction in memory and 40% increase in throughput with \\(<\\)
0.1 loss in perplexity when compared to streaming the dense model from Flash.
The open source code for HW simulator, methods, and experiments in this paper
is available at https://github.com/Qualcomm-AI-research/dynamic-sparsity .
