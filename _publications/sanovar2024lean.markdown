---
layout: publication
title: 'Lean Attention: Hardware-aware Scalable Attention Mechanism For The Decode-phase Of Transformers'
authors: Sanovar Rya, Bharadwaj Srikant, Amant Renee St., Rühle Victor, Rajmohan Saravan
conference: "Arxiv"
year: 2024
bibkey: sanovar2024lean
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.10480"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Transformer']
---
Transformer-based models have emerged as one of the most widely used
architectures for natural language processing, natural language generation, and
image generation. The size of the state-of-the-art models has increased
steadily reaching billions of parameters. These huge models are memory hungry
and incur significant inference latency even on cutting edge AI-accelerators,
such as GPUs. Specifically, the time and memory complexity of the attention
operation is quadratic in terms of the total context length, i.e., prompt and
output tokens. Thus, several optimizations such as key-value tensor caching and
FlashAttention computation have been proposed to deliver the low latency
demands of applications relying on such large models. However, these techniques
do not cater to the computationally distinct nature of different phases during
inference.
  To that end, we propose LeanAttention, a scalable technique of computing
self-attention for the token-generation phase (decode-phase) of decoder-only
transformer models. LeanAttention enables scaling the attention mechanism
implementation for the challenging case of long context lengths by re-designing
the execution flow for the decode-phase. We identify that the associative
property of online softmax can be treated as a reduction operation thus
allowing us to parallelize the attention computation over these large context
lengths. We extend the "stream-K" style reduction of tiled calculation to
self-attention to enable parallel computation resulting in an average of 2.6x
attention execution speedup over FlashAttention-2 and up to 8.33x speedup for
512k context lengths.
