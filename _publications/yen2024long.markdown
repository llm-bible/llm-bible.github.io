---
layout: publication
title: 'Long-context Language Modeling With Parallel Context Encoding'
authors: Yen Howard, Gao Tianyu, Chen Danqi
conference: "Arxiv"
year: 2024
bibkey: yen2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16617"}
tags: ['Applications', 'Attention Mechanism', 'In Context Learning', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Transformer']
---
"Extending large language models (LLMs) to process longer inputs is crucial for a wide range of applications. However, the substantial computational cost of transformers and limited generalization of positional encoding restrict the size of their context window. We introduce Context Expansion with Parallel Encoding (CEPE), a framework that can be applied to any existing decoder-only LLMs to extend their context window. CEPE employs a small encoder to process long inputs chunk by chunk, enabling the frozen decoder to utilize additional contexts via cross-attention. CEPE is efficient, generalizable, and versatile: trained with 8K-token documents, it extends the context window of LLAMA-2 to 128K tokens, offering 10x the throughput with only 1/6 of the memory. CEPE yields strong performance on language modeling and in-context learning. CEPE also excels in retrieval-augmented applications, while existing long-context models degenerate with retrieved contexts. We further introduce a CEPE variant that can extend the context window of instruction-tuned models using only unlabeled data, and showcase its effectiveness on LLAMA-2-CHAT, leading to a strong instruction-following model that can leverage very long contexts on downstream tasks."
