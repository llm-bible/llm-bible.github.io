---
layout: publication
title: 'GPR: Empowering Generation With Graph-pretrained Retriever'
authors: Xiaochen Wang, Zongyu Wu, Yuan Zhong, Xiang Zhang, Suhang Wang, Fenglong Ma
conference: "Arxiv"
year: 2025
bibkey: wang2025empowering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.00261'}
tags: ['RAG', 'Applications']
---
Graph retrieval-augmented generation (GRAG) places high demands on graph-specific retrievers. However, existing retrievers often rely on language models pretrained on plain text, limiting their effectiveness due to domain misalignment and structure ignorance. To address these challenges, we propose GPR, a graph-based retriever pretrained directly on knowledge graphs. GPR aligns natural language questions with relevant subgraphs through LLM-guided graph augmentation and employs a structure-aware objective to learn fine-grained retrieval strategies. Experiments on two datasets, three LLM backbones, and five baselines show that GPR consistently improves both retrieval quality and downstream generation, demonstrating its effectiveness as a robust retrieval solution for GRAG.
