---
layout: publication
title: 'Parallel Key-value Cache Fusion For Position Invariant RAG'
authors: Philhoon Oh, Jinwoo Shin, James Thorne
conference: "Arxiv"
year: 2025
bibkey: oh2025parallel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.07523"}
tags: ['Tools', 'Applications', 'RAG', 'Merging', 'Security']
---
Recent advancements in Large Language Models (LLMs) underscore the necessity
of Retrieval Augmented Generation (RAG) to leverage external information.
However, LLMs are sensitive to the position of relevant information within
contexts and tend to generate incorrect responses when such information is
placed in the middle, known as `Lost in the Middle' phenomenon. In this paper,
we introduce a framework that generates consistent outputs for decoder-only
models, irrespective of the input context order. Experimental results for three
open domain question answering tasks demonstrate position invariance, where the
model is not sensitive to input context order, and superior robustness to
irrelevent passages compared to prevailing approaches for RAG pipelines.
