---
layout: publication
title: 'You Only Use Reactive Attention Slice For Long Context Retrieval'
authors: Yun Joon Soh, Hanxian Huang, Yuandong Tian, Jishen Zhao
conference: "Arxiv"
year: 2024
bibkey: soh2024you
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13695"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Attention Mechanism']
---
Supporting longer context for Large Language Models (LLM) is a promising
direction to advance LLMs. As training a model for a longer context window is
computationally expensive, many alternative solutions, such as Retrieval
Augmented Generation (RAG), have been used. However, most existing RAG methods
adopt embedding-based retrieval that falls short on long contexts.
  To address such challenges, we propose an attention-based retrieval
technique, You Only Use Reactive Attention slice (YOURA). YOURA leverages a
novel retrieval heuristic called reaction score to rank the relevance of each
sentence in the input context with the query sentence. Intuitively, we measure
how the per-token attention score "reacts" to the query and greedily retrieves
the most reactive sentences. Internally, YOURA generates a token-indexed vector
(called reaction vector) for the whole input context. To map each sentence to
the token-indexed vector, we propose an Embedding-Agnostic Sentence Yield
(EASY), a best-effort token wiggling algorithm.
  We evaluate our retrieval technique on three open-source pre-trained LLM
models across six LongBench QA datasets. Our technique achieves up to 30% vLLM
inference throughput improvement for serving long-context queries with a nearly
identical quality score to the simple yet effective truncate-middle approach.
