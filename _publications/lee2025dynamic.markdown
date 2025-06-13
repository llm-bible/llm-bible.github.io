---
layout: publication
title: 'Cachefocus: Dynamic Cache Re-positioning For Efficient Retrieval-augmented Generation'
authors: Kun-hui Lee, Eunhwan Park, Donghoon Han, Seung-hoon Na
conference: "Arxiv"
year: 2025
bibkey: lee2025dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11101"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Language Modeling', 'RAG', 'Pruning', 'Applications']
---
Large Language Models (LLMs) excel across a variety of language tasks yet are
constrained by limited input lengths and high computational costs. Existing
approaches\textemdash such as relative positional encodings (e.g., RoPE, ALiBi)
and sliding window mechanisms\textemdash partially alleviate these issues but
often require additional training or suffer from performance degradation with
longer inputs. In this paper, we introduce \textbf\{\textit\{CacheFocus\}\}, a
method that enhances length normalization and reduces inference latency without
any further training. Our approach leverages query-independent, offline caching
to efficiently reuse a Context KV Cache Store. We address the amplification of
abnormal token distributions problem by re-positioning cached keys and
introducing Layer-Adaptive Cache Pruning to discard low-relevance caches during
pre-filling. Additionally, our Adaptive Positional Allocation Strategy
dynamically reassigns cache positions to maximize the use of the available
positional encoding range. Experiments on the Natural Questions and TriviaQA
datasets demonstrate that CacheFocus outperforms alternative methods even when
inputs exceed the \\(4\\)K limit of the \texttt\{LLaMA-2\} model, emphasizing its
practical effectiveness for long-context LLMs. Moreover, even with large
maximum input length of \texttt\{Qwen2\}, the performance of CacheFocus shows
that it maintains consistent performance even as the number of documents
increases, effectively managing long-text generation without degradation.
