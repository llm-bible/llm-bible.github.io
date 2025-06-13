---
layout: publication
title: 'Two Are Better Than One: Context Window Extension With Multi-grained Self-injection'
authors: Wei Han, Pan Zhou, Soujanya Poria, Shuicheng Yan
conference: "Arxiv"
year: 2024
bibkey: han2024two
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.19318'}
tags: ['Attention Mechanism', 'Training Techniques', 'Tools', 'Applications', 'Model Architecture', 'Pre-Training']
---
The limited context window of contemporary large language models (LLMs)
remains a huge barrier to their broader application across various domains.
While continual pre-training on long-context data is a straightforward and
effective solution, it incurs substantial costs in terms of data acquisition
and computational resources. To alleviate this issue, we propose SharedLLM, a
novel approach grounded in the design philosophy of multi-grained context
compression and query-aware information retrieval. SharedLLM is composed of two
short-context LLMs such as LLaMA-2, termed upper model and lower model. The
lower model functions as a compressor while the upper model acts as a decoder.
The upper model receives compressed, multi-grained context information from the
lower model and performs context-aware modeling on the running text.
Information transfer between the compressor and decoder occurs only at the
lowest layers to refrain from long forward paths in the lower model and
redundant cross-attention modules in the upper model. Based on this
architecture, we introduce a specialized tree-style data structure to
efficiently encode, store and retrieve multi-grained contextual information for
text chunks. This structure, combined with a search algorithm, enables rapid
encoding and retrieval of relevant information from various levels of the tree
based on the input query. This entire process, wherein the sender and receiver
are derived from the same LLM layer, is referred to as self-injection.
