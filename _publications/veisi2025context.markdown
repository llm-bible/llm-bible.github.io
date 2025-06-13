---
layout: publication
title: 'Context-aware Biases For Length Extrapolation'
authors: Ali Veisi, Hamidreza Amirzadeh, Amir Mansourian
conference: "Arxiv"
year: 2025
bibkey: veisi2025context
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.08067'}
  - {name: "Code", url: 'https://github.com/axiomlab/cable'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'Training Techniques', 'BERT', 'Model Architecture', 'GPT', 'Ethics and Bias', 'Pretraining Methods']
---
Transformers often struggle to generalize to longer sequences than those seen during training, a limitation known as length extrapolation. Most existing Relative Positional Encoding (RPE) methods attempt to address this by introducing either fixed linear biases or globally learned biases, which lack the capacity to adapt to different input contexts. In this work, we propose an additive RPE, Context-Aware Biases for Length Extrapolation (CABLE), a method that learns token-specific, context-aware biases for each attention head in transformers. By dynamically adjusting positional biases based on the input sequence, CABLE overcomes the rigidity of fixed RPEs. When evaluated on sequences longer than originally trained with, GPT-2 Medium (334M parameters) with CABLE achieves lower perplexity than counterparts using other widely adopted positional encoding methods. Additionally, by applying CABLE to the BERT base model we improved performance in long-context retrieval tasks. Our method significantly enhances the extrapolation performance of existing RPE methods tested on the FineWeb-Edu10B and WikiText-103 datasets. Code is available at: https://github.com/axiomlab/cable
