---
layout: publication
title: 'Tempo: Accelerating Transformer-based Model Training Through Memory Footprint Reduction'
authors: Andoorveedu Muralidhar, Zhu Zhanda, Zheng Bojian, Pekhimenko Gennady
conference: "Arxiv"
year: 2022
bibkey: andoorveedu2022accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.10246"}
tags: ['Attention Mechanism', 'BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
"Training deep learning models can be computationally expensive. Prior works have shown that increasing the batch size can potentially lead to better overall throughput. However, the batch size is frequently limited by the accelerator memory capacity due to the activations/feature maps stored for the training backward pass, as larger batch sizes require larger feature maps to be stored. Transformer-based models, which have recently seen a surge in popularity due to their good performance and applicability to a variety of tasks, have a similar problem. To remedy this issue, we propose Tempo, a new approach to efficiently use accelerator (e.g., GPU) memory resources for training Transformer-based models. Our approach provides drop-in replacements for the GELU, LayerNorm, and Attention layers, reducing the memory usage and ultimately leading to more efficient training. We implement Tempo and evaluate the throughput, memory usage, and accuracy/loss on the BERT Large pre-training task. We demonstrate that Tempo enables up to 2x higher batch sizes and 16&#37; higher training throughput over the state-of-the-art baseline. We also evaluate Tempo on GPT2 and RoBERTa models, showing 19&#37; and 26&#37; speedup over the baseline."
