---
layout: publication
title: 'Understanding The Skill Gap In Recurrent Language Models: The Role Of The Gather-and-aggregate Mechanism'
authors: Aviv Bick, Eric Xing, Albert Gu
conference: "Arxiv"
year: 2025
bibkey: bick2025understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18574"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Interpretability and Explainability', 'Attention Mechanism']
---
SSMs offer efficient processing of long sequences with fixed state sizes, but
struggle with algorithmic tasks like retrieving past context. In this work, we
examine how such in-context retrieval operates within Transformer- and
SSM-based language models. We find that both architectures develop the same
fundamental Gather-and-Aggregate (G&A) mechanism. A Gather Head first
identifies and extracts relevant information from the context, which an
Aggregate Head then integrates into a final representation. Across both model
types, G&A concentrates in just a few heads, making them critical bottlenecks
even for benchmarks that require a basic form of retrieval. For example,
disabling a single Gather or Aggregate Head of a pruned Llama-3.1-8B degrades
its ability to retrieve the correct answer letter in MMLU, reducing accuracy
from 66% to 25%. This finding suggests that in-context retrieval can obscure
the limited knowledge demands of certain tasks. Despite strong MMLU performance
with retrieval intact, the pruned model fails on other knowledge tests. Similar
G&A dependencies exist in GSM8K, BBH, and dialogue tasks. Given the
significance of G&A in performance, we show that retrieval challenges in SSMs
manifest in how they implement G&A, leading to smoother attention patterns
rather than the sharp token transitions that effective G&A relies on. Thus,
while a gap exists between Transformers and SSMs in implementing in-context
retrieval, it is confined to a few heads, not the entire model. This insight
suggests a unified explanation for performance differences between Transformers
and SSMs while also highlighting ways to combine their strengths. For example,
in pretrained hybrid models, attention components naturally take on the role of
Aggregate Heads. Similarly, in a pretrained pure SSM, replacing a single G&A
head with an attention-based variant significantly improves retrieval.
