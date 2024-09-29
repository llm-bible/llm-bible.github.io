---
layout: publication
title: Training45;free Activation Sparsity In Large Language Models
authors: Liu James, Ponnusamy Pragaash, Cai Tianle, Guo Han, Kim Yoon, Athiwaratkun Ben
conference: "Arxiv"
year: 2024
bibkey: liu2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.14690"}
tags: ['Efficiency And Optimization', 'Quantization', 'Training Techniques']
---
Activation sparsity can enable practical inference speedups in large language models (LLMs) by reducing the compute and memory45;movement required for matrix multiplications during the forward pass. However existing methods face limitations that inhibit widespread adoption. Some approaches are tailored towards older models with ReLU45;based sparsity while others require extensive continued pre45;training on up to hundreds of billions of tokens. This paper describes TEAL a simple training45;free method that applies magnitude45;based activation sparsity to hidden states throughout the entire model. TEAL achieves 4045;5037; model45;wide sparsity with minimal performance degradation across Llama45;2 Llama45;3 and Mistral families with sizes varying from 7B to 70B. We improve existing sparse kernels and demonstrate wall45;clock decoding speed45;ups of up to 1.53× and 1.8× at 4037; and 5037; model45;wide sparsity. TEAL is compatible with weight quantization enabling further efficiency gains.
