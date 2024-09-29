---
layout: publication
title: Dynamic Context Pruning For Efficient And Interpretable Autoregressive Transformers
authors: Sotiris Anagnostidis, Dario Pavllo, Luca Biggio, Lorenzo Noci, Aurelien Lucchi, Thomas Hofmann
conference: "Arxiv"
year: 2023
bibkey: anagnostidis2023dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2305.15805v3"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Transformer']
---
Autoregressive Transformers adopted in Large Language Models (LLMs) are hard to scale to long sequences. Despite several works trying to reduce their computational cost most of LLMs still adopt attention layers between all pairs of tokens in the sequence thus incurring a quadratic cost. In this study we present a novel approach that dynamically prunes contextual information while preserving the models expressiveness resulting in reduced memory and computational requirements during inference. Our method employs a learnable mechanism that determines which uninformative tokens can be dropped from the context at any point across the generation process. By doing so our approach not only addresses performance concerns but also enhances interpretability providing valuable insight into the models decision45;making process. Our technique can be applied to existing pre45;trained models through a straightforward fine45;tuning process and the pruning strength can be specified by a sparsity parameter. Notably our empirical findings demonstrate that we can effectively prune up to 8037; of the context without significant performance degradation on downstream tasks offering a valuable tool for mitigating inference costs. Our reference implementation achieves up to 2× increase in inference throughput and even greater memory savings.
