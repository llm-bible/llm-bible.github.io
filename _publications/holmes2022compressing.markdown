---
layout: publication
title: 'Compressing Pre-trained Transformers Via Low-bit Nxm Sparsity For Natural Language Understanding'
authors: Connor Holmes, Minjia Zhang, Yuxiong He, Bo Wu
conference: "Arxiv"
year: 2022
bibkey: holmes2022compressing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.15014"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pruning', 'Quantization', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Transformer', 'Applications']
---
In recent years, large pre-trained Transformer networks have demonstrated
dramatic improvements in many natural language understanding tasks. However,
the huge size of these models brings significant challenges to their
fine-tuning and online deployment due to latency and cost constraints. New
hardware supporting both N:M semi-structured sparsity and low-precision integer
computation is a promising solution to boost DNN model serving efficiency.
However, there have been very few studies that systematically investigate to
what extent pre-trained Transformer networks benefit from the combination of
these techniques, as well as how to best compress each component of the
Transformer. We propose a flexible compression framework NxMiFormer that
performs simultaneous sparsification and quantization using ADMM and STE-based
QAT. Furthermore, we present and inexpensive, heuristic-driven search algorithm
that identifies promising heterogeneous compression configurations that meet a
compression ratio constraint. When evaluated across the GLUE suite of NLU
benchmarks, our approach can achieve up to 93% compression of the encoders of a
BERT model while retaining 98.2% of the original model accuracy and taking full
advantage of the hardware's capabilities. Heterogeneous configurations found
the by the search heuristic maintain 99.5% of the baseline accuracy while still
compressing the model by 87.5%.
