---
layout: publication
title: "FIRST: Faster Improved Listwise Reranking With Single Token Decoding"
authors: Reddy Revanth Gangi, Doo Jaehyeok, Xu Yifei, Sultan Md Arafat, Swain Deevya, Sil Avirup, Ji Heng
conference: "Arxiv"
year: 2024
bibkey: reddy2024faster
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15657"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Language Modeling', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have significantly advanced the field of information retrieval particularly for reranking. Listwise LLM rerankers have showcased superior performance and generalizability compared to existing supervised approaches. However conventional listwise LLM reranking methods lack efficiency as they provide ranking output in the form of a generated ordered sequence of candidate passage identifiers. Further they are trained with the typical language modeling objective which treats all ranking errors uniformly--potentially at the cost of misranking highly relevant passages. Addressing these limitations we introduce FIRST a novel listwise LLM reranking approach leveraging the output logits of the first generated identifier to directly obtain a ranked ordering of the candidates. Further we incorporate a learning-to-rank loss during training prioritizing ranking accuracy for the more relevant passages. Empirical results demonstrate that FIRST accelerates inference by 5037; while maintaining a robust ranking performance with gains across the BEIR benchmark. Finally to illustrate the practical effectiveness of listwise LLM rerankers we investigate their application in providing relevance feedback for retrievers during inference. Our results show that LLM rerankers can provide a stronger distillation signal compared to cross-encoders yielding substantial improvements in retriever recall after relevance feedback.
