---
layout: publication
title: 'Investigating Low-rank Training In Transformer Language Models: Efficiency And Scaling Analysis'
authors: Xiuying Wei, Skander Moalla, Razvan Pascanu, Caglar Gulcehre
conference: "Arxiv"
year: 2024
bibkey: wei2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09835"}
  - {name: "Code", url: "https://github.com/CLAIRE-Labo/StructuredFFN/tree/main"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
State-of-the-art LLMs often rely on scale with high computational costs,
which has sparked a research agenda to reduce parameter counts and costs
without significantly impacting performance. Our study focuses on
Transformer-based LLMs, specifically applying low-rank parametrization to the
computationally intensive feedforward networks (FFNs), which are less studied
than attention blocks. In contrast to previous works, (i) we explore low-rank
parametrization at scale, up to 1.3B parameters; (ii) within Transformer
language models rather than convolutional architectures; and (iii) starting
from training from scratch. Experiments on the large RefinedWeb dataset show
that low-rank parametrization is both efficient (e.g., 2.6\\(\times\\) FFN speed-up
with 32% parameters) and effective during training. Interestingly, these
structured FFNs exhibit steeper scaling curves than the original models.
Motivated by this finding, we develop the wide and structured networks
surpassing the current medium-sized and large-sized Transformer in perplexity
and throughput performance. Our code is available at
https://github.com/CLAIRE-Labo/StructuredFFN/tree/main.
