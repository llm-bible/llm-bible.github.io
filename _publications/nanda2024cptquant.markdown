---
layout: publication
title: 'Cptquant - A Novel Mixed Precision Post-training Quantization Techniques For Large Language Models'
authors: Amitash Nanda, Sree Bhargavi Balija, Debashis Sahoo
conference: "Arxiv"
year: 2024
bibkey: nanda2024cptquant
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.03599"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Language Modeling', 'Pruning', 'Quantization', 'BERT']
---
Large language models have transformed the comprehension and generation of
natural language tasks, but they come with substantial memory and computational
requirements. Quantization techniques have emerged as a promising avenue for
addressing these challenges while preserving accuracy and making energy
efficient. We propose CPTQuant, a comprehensive strategy that introduces
correlation-based (CMPQ), pruning-based (PMPQ), and Taylor decomposition-based
(TDMPQ) mixed precision techniques. CMPQ adapts the precision level based on
canonical correlation analysis of different layers. PMPQ optimizes precision
layer-wise based on their sensitivity to sparsity. TDMPQ modifies precision
using Taylor decomposition to assess each layer's sensitivity to input
perturbation. These strategies allocate higher precision to more sensitive
layers while diminishing precision to robust layers. CPTQuant assesses the
performance across BERT, OPT-125M, OPT-350M, OPT-1.3B, and OPT-2.7B. We
demonstrate up to 4x compression and a 2x-fold increase in efficiency with
minimal accuracy drop compared to Hugging Face FP16. PMPQ stands out for
achieving a considerably higher model compression. Sensitivity analyses across
various LLMs show that the initial and final 30% of layers exhibit higher
sensitivities than the remaining layers. PMPQ demonstrates an 11% higher
compression ratio than other methods for classification tasks, while TDMPQ
achieves a 30% greater compression ratio for language modeling tasks.
