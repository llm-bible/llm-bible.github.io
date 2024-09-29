---
layout: publication
title: MemLong Memory-Augmented Retrieval for Long Text Modeling
authors: Liu Weijie, Tang Zecheng, Li Juntao, Chen Kehai, Zhang Min
conference: "Arxiv"
year: 2024
bibkey: liu2024memlong
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.16967"}
  - {name: "Code", url: "https://github.com/Bui1dMySea/MemLong"}
tags: ['Applications', 'Attention Mechanism', 'Has Code', 'Language Modeling', 'Model Architecture', 'RAG', 'Transformer']
---
Recent advancements in Large Language Models (LLMs) have yielded remarkable success across diverse fields. However handling long contexts remains a significant challenge for LLMs due to the quadratic time and space complexity of attention mechanisms and the growing memory consumption of the key-value cache during generation. This work introduces MemLong Memory-Augmented Retrieval for Long Text Generation a method designed to enhance the capabilities of long-context language modeling by utilizing an external retriever for historical information retrieval. MemLong combines a non-differentiable ret-mem module with a partially trainable decoder-only language model and introduces a fine-grained controllable retrieval attention mechanism that leverages semantic-level relevant chunks. Comprehensive evaluations on multiple long-context language modeling benchmarks demonstrate that MemLong consistently outperforms other state-of-the-art LLMs. More importantly MemLong can extend the context length on a single 3090 GPU from 4k up to 80k. Our code is available at https://github.com/Bui1dMySea/MemLong
