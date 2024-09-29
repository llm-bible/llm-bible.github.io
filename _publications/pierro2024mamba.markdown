---
layout: publication
title: 'Mamba-ptq: Outlier Channels In Recurrent Large Language Models'
authors: Pierro Alessandro, Abreu Steven
conference: "Arxiv"
year: 2024
bibkey: pierro2024mamba
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12397"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'Training Techniques', 'Transformer']
---
Modern recurrent layers are emerging as a promising path toward edge deployment of foundation models especially in the context of large language models (LLMs). Compressing the whole input sequence in a finite-dimensional representation enables recurrent layers to model long-range dependencies while maintaining a constant inference cost for each token and a fixed memory requirement. However the practical deployment of LLMs in resource-limited environments often requires further model compression such as quantization and pruning. While these techniques are well-established for attention-based models their effects on recurrent layers remain underexplored. In this preliminary work we focus on post-training quantization for recurrent LLMs and show that Mamba models exhibit the same pattern of outlier channels observed in attention-based LLMs. We show that the reason for the difficulty of quantizing SSMs is caused by activation outliers similar to those observed in transformer-based LLMs. We report baseline results for post-training quantization of Mamba that do not take into account the activation outliers and suggest first steps for outlier-aware quantization.
