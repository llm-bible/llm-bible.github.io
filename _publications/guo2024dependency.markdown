---
layout: publication
title: 'Dependency-aware Semi-structured Sparsity Of GLU Variants In Large Language Models'
authors: Zhiyu Guo, Hidetaka Kamigaito, Taro Wanatnabe
conference: "Arxiv"
year: 2024
bibkey: guo2024dependency
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01943"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'GPT', 'Pruning']
---
The rapid advancement in Large Language Models (LLMs) has markedly enhanced
the capabilities of language understanding and generation. However, the
substantial model size poses hardware challenges, affecting both memory size
for serving and inference latency for token generation. To address those
challenges, we propose Dependency-aware Semi-structured Sparsity (DaSS), a
novel method for the recent prevalent GLU-based LLMs pruning, which
incorporates structural dependency into the weight magnitude-based unstructured
pruning. We introduce an MLP-specific pruning metric that evaluates the
importance of each weight by jointly considering its magnitude and its
corresponding MLP intermediate activation norms. DaSS facilitates a balance
between the adaptability offered by unstructured pruning and the structural
consistency inherent in dependency-based structured pruning. Empirical
evaluations on LLaMA2, Mistral, and Gemma model families demonstrate that DaSS
not only outperforms both SparseGPT and Wanda in achieving hardware-friendly
N:M sparsity patterns but also maintains the computational efficiency of Wanda.
