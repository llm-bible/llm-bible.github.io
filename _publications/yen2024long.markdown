---
layout: publication
title: Long45;context Language Modeling With Parallel Context Encoding
authors: Yen Howard, Gao Tianyu, Chen Danqi
conference: "Arxiv"
year: 2024
bibkey: yen2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16617"}
tags: ['Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Transformer']
---
Extending large language models (LLMs) to process longer inputs is crucial for a wide range of applications. However the substantial computational cost of transformers and limited generalization of positional encoding restrict the size of their context window. We introduce Context Expansion with Parallel Encoding (CEPE) a framework that can be applied to any existing decoder45;only LLMs to extend their context window. CEPE employs a small encoder to process long inputs chunk by chunk enabling the frozen decoder to utilize additional contexts via cross45;attention. CEPE is efficient generalizable and versatile trained with 8K45;token documents it extends the context window of LLAMA45;2 to 128K tokens offering 10x the throughput with only 1/6 of the memory. CEPE yields strong performance on language modeling and in45;context learning. CEPE also excels in retrieval45;augmented applications while existing long45;context models degenerate with retrieved contexts. We further introduce a CEPE variant that can extend the context window of instruction45;tuned models using only unlabeled data and showcase its effectiveness on LLAMA45;245;CHAT leading to a strong instruction45;following model that can leverage very long contexts on downstream tasks.
