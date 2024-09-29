---
layout: publication
title: "Loma: Lossless Compressed Memory Attention"
authors: Wang Yumeng, Xiao Zhenyang
conference: "Arxiv"
year: 2024
bibkey: wang2024lossless
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.09486"}
tags: ['Attention Mechanism', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Large Language Models (LLMs) face limitations due to the high demand on GPU memory and computational resources when handling long contexts. While sparsify the Key-Value (KV) cache of transformer model is a typical strategy to alleviate resource usage it unavoidably results in the loss of information. We introduce Lossless Compressed Memory Attention (LoMA) a novel approach that enables lossless compression of the KV cache thereby reducing the memory and computational demands during autoregressive generation. LoMA incorporates a specialized training or fine-tuning precedure alongside an autoregressive generation algorithm optimized for the compressed context. Our method compresses the KV cache after every tc generated tokens with a compression ratio of c and a target compressed length t and this process occurs within a single inference pass without dependency on auxiliary models. We engineered an efficient training scheme involving specific inputs attention masks and position identifiers to instill this compression capability. Experimental validation has demonstrated that LoMA significantly reducing computational consumption and memory usage through achieving lossless KV cache compression.
