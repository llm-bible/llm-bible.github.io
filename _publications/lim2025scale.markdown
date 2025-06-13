---
layout: publication
title: 'Macrag: Compress, Slice, And Scale-up For Multi-scale Adaptive Context RAG'
authors: Woosang Lim, Zekun Li, Gyuwan Kim, Sungyoung Ji, Hyeonjung Kim, Kyuri Choi, Jin Hyuk Lim, Kyungpyo Park, William Yang Wang
conference: "Arxiv"
year: 2025
bibkey: lim2025scale
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.06569"}
  - {name: "Code", url: "https://github.com/Leezekun/MacRAG"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Has Code']
---
Long-context large language models (LC LLMs) combined with retrieval-augmented generation (RAG) hold strong potential for complex multi-hop and large-document tasks. However, existing RAG systems often suffer from imprecise retrieval, incomplete context coverage under constrained windows, and fragmented information from suboptimal context construction. We introduce Multi-scale Adaptive Context RAG (MacRAG), a hierarchical RAG framework that compresses and partitions documents into coarse-to-fine granularities, then adaptively merges relevant contexts through real-time chunk- and document-level expansions. By initiating with finest-level retrieval and progressively incorporating broader, higher-level context, MacRAG constructs effective query-specific long contexts, optimizing both precision and coverage. Evaluations on challenging LongBench expansions of HotpotQA, 2WikiMultihopQA, and Musique confirm MacRAG consistently surpasses baseline RAG pipelines in single- and multi-step generation using Llama-3.1-8B, Gemini-1.5-pro, and GPT-4o. Our results establish MacRAG as an efficient, scalable solution for real-world long-context, multi-hop reasoning. Our code is available at https://github.com/Leezekun/MacRAG.
