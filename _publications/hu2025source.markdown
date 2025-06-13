---
layout: publication
title: 'Source-primed Multi-turn Conversation Helps Large Language Models Translate Documents'
authors: Hanxu Hu, Jannis Vamvas, Rico Sennrich
conference: "Arxiv"
year: 2025
bibkey: hu2025source
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.10494'}
tags: ['RAG', 'Applications', 'Training Techniques']
---
LLMs have paved the way for truly simple document-level machine translation,
but challenges such as omission errors remain. In this paper, we study a simple
method for handling document-level machine translation, by leveraging previous
contexts in a multi-turn conversational manner. Specifically, by decomposing
documents into segments and iteratively translating them while maintaining
previous turns, this method ensures coherent translations without additional
training, and can fully re-use the KV cache of previous turns thus minimizing
computational overhead. We further propose a `source-primed' method that first
provides the whole source document before multi-turn translation. We
empirically show this multi-turn method outperforms both translating entire
documents in a single turn and translating each segment independently according
to multiple automatic metrics in representative LLMs, establishing a strong
baseline for document-level translation using LLMs.
