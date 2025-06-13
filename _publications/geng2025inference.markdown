---
layout: publication
title: 'Zip2zip: Inference-time Adaptive Vocabularies For Language Models Via Token Compression'
authors: Saibo Geng, Nathan Ranchin, Yunzhen Yao, Maxime Peyrard, Chris Wendler, Michael Gastpar, Robert West
conference: "Arxiv"
year: 2025
bibkey: geng2025inference
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.01084'}
tags: ['Language Modeling', 'Efficiency and Optimization', 'Tools', 'Tokenization', 'Pretraining Methods']
---
Tokenization efficiency plays a critical role in the performance and cost of large language models (LLMs), yet most models rely on static tokenizers optimized for general-purpose corpora. These tokenizers' fixed vocabularies often fail to adapt to domain- or language-specific inputs, leading to longer token sequences and higher computational costs. We introduce zip2zip, a framework that enables LLMs to dynamically adjust token vocabulary at inference time, allowing for fewer generated tokens and thus faster inference. zip2zip consists of three key components: (1) a tokenizer based on Lempel-Ziv-Welch (LZW) compression that incrementally compresses tokens into reusable "hypertokens" on the fly; (2) an embedding layer that computes embeddings for newly formed hypertokens at runtime; and (3) a causal language modeling variant that trains the model to operate on hypertokenized, compressed sequences. We show that an existing LLM can be zip2zip-fied in 10 GPU-hours via parameter-efficient finetuning. The resulting zip2zip LLMs effectively learn to use hypertokens at inference time, reducing input and output sequence length by 20-60%, with significant improvements in inference latency.
