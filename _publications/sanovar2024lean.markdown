---
layout: publication
title: Lean Attention Hardware45;aware Scalable Attention Mechanism For The Decode45;phase Of Transformers
authors: Sanovar Rya, Bharadwaj Srikant, Amant Renee St., Rühle Victor, Rajmohan Saravan
conference: "Arxiv"
year: 2024
bibkey: sanovar2024lean
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.10480"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Transformer']
---
Transformer45;based models have emerged as one of the most widely used architectures for natural language processing natural language generation and image generation. The size of the state45;of45;the45;art models has increased steadily reaching billions of parameters. These huge models are memory hungry and incur significant inference latency even on cutting edge AI45;accelerators such as GPUs. Specifically the time and memory complexity of the attention operation is quadratic in terms of the total context length i.e. prompt and output tokens. Thus several optimizations such as key45;value tensor caching and FlashAttention computation have been proposed to deliver the low latency demands of applications relying on such large models. However these techniques do not cater to the computationally distinct nature of different phases during inference. To that end we propose LeanAttention a scalable technique of computing self45;attention for the token45;generation phase (decode45;phase) of decoder45;only transformer models. LeanAttention enables scaling the attention mechanism implementation for the challenging case of long context lengths by re45;designing the execution flow for the decode45;phase. We identify that the associative property of online softmax can be treated as a reduction operation thus allowing us to parallelize the attention computation over these large context lengths. We extend the stream45;K style reduction of tiled calculation to self45;attention to enable parallel computation resulting in an average of 2.6x attention execution speedup over FlashAttention45;2 and up to 8.33x speedup for 512k context lengths.
