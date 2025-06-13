---
layout: publication
title: 'ELITE: Embedding-less Retrieval With Iterative Text Exploration'
authors: Zhangyu Wang, Siyuan Gao, Rong Zhou, Hao Wang, Li Ning
conference: "Arxiv"
year: 2025
bibkey: wang2025embedding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.11908"}
tags: ['Fine-Tuning', 'RAG', 'Tools']
---
Large Language Models (LLMs) have achieved impressive progress in natural language processing, but their limited ability to retain long-term context constrains performance on document-level or multi-turn tasks. Retrieval-Augmented Generation (RAG) mitigates this by retrieving relevant information from an external corpus. However, existing RAG systems often rely on embedding-based retrieval trained on corpus-level semantic similarity, which can lead to retrieving content that is semantically similar in form but misaligned with the question's true intent. Furthermore, recent RAG variants construct graph- or hierarchy-based structures to improve retrieval accuracy, resulting in significant computation and storage overhead. In this paper, we propose an embedding-free retrieval framework. Our method leverages the logical inferencing ability of LLMs in retrieval using iterative search space refinement guided by our novel importance measure and extend our retrieval results with logically related information without explicit graph construction. Experiments on long-context QA benchmarks, including NovelQA and Marathon, show that our approach outperforms strong baselines while reducing storage and runtime by over an order of magnitude.
