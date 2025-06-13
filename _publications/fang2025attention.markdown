---
layout: publication
title: 'Attentionrag: Attention-guided Context Pruning In Retrieval-augmented Generation'
authors: Yixiong Fang, Tianran Sun, Yuling Shi, Xiaodong Gu
conference: "Arxiv"
year: 2025
bibkey: fang2025attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.10720"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'RAG', 'Pruning', 'Applications', 'Attention Mechanism']
---
While RAG demonstrates remarkable capabilities in LLM applications, its
effectiveness is hindered by the ever-increasing length of retrieved contexts,
which introduces information redundancy and substantial computational overhead.
Existing context pruning methods, such as LLMLingua, lack contextual awareness
and offer limited flexibility in controlling compression rates, often resulting
in either insufficient pruning or excessive information loss. In this paper, we
propose AttentionRAG, an attention-guided context pruning method for RAG
systems. The core idea of AttentionRAG lies in its attention focus mechanism,
which reformulates RAG queries into a next-token prediction paradigm. This
mechanism isolates the query's semantic focus to a single token, enabling
precise and efficient attention calculation between queries and retrieved
contexts. Extensive experiments on LongBench and Babilong benchmarks show that
AttentionRAG achieves up to 6.3\\(\times\\) context compression while outperforming
LLMLingua methods by around 10% in key metrics.
