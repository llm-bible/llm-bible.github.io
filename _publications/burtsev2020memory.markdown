---
layout: publication
title: Memory Transformer
authors: Burtsev Mikhail S., Kuratov Yuri, Peganov Anton, Sapunov Grigory V.
conference: "Arxiv"
year: 2020
bibkey: burtsev2020memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2006.11527"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Transformer45;based models have achieved state45;of45;the45;art results in many natural language processing tasks. The self45;attention architecture allows transformer to combine information from all elements of a sequence into context45;aware representations. However information about the context is stored mostly in the same element45;wise representations. This might limit the processing of properties related to the sequence as a whole more difficult. Adding trainable memory to selectively store local as well as global representations of a sequence is a promising direction to improve the Transformer model. Memory45;augmented neural networks (MANNs) extend traditional neural architectures with general45;purpose memory for representations. MANNs have demonstrated the capability to learn simple algorithms like Copy or Reverse and can be successfully trained via backpropagation on diverse tasks from question answering to language modeling outperforming RNNs and LSTMs of comparable complexity. In this work we propose and study few extensions of the Transformer baseline (1) by adding memory tokens to store non45;local representations (2) creating memory bottleneck for the global information (3) controlling memory update with dedicated layer. We evaluate these memory augmented Transformers and demonstrate that presence of memory positively correlates with the model performance for machine translation and language modelling tasks. Augmentation of pre45;trained masked language model with memory tokens shows mixed results for tasks from GLUE benchmark. Visualization of attention patterns over the memory suggest that it improves the models ability to process a global context.
