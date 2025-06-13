---
layout: publication
title: 'Meta-chunking: Learning Text Segmentation And Semantic Completion Via Logical Perception'
authors: Jihao Zhao, Zhiyuan Ji, Yuchen Feng, Pengnian Qi, Simin Niu, Bo Tang, Feiyu Xiong, Zhiyu Li
conference: "Arxiv"
year: 2024
bibkey: zhao2024meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12788"}
tags: ['RAG', 'Merging', 'Tools', 'Reinforcement Learning']
---
While Retrieval-Augmented Generation (RAG) has emerged as a promising paradigm for boosting large language models (LLMs) in knowledge-intensive tasks, it often overlooks the crucial aspect of text chunking within its workflow. This paper proposes the Meta-Chunking framework, which specifically enhances chunking quality through a dual strategy that identifies optimal segmentation points and preserves global information. Initially, breaking limitations of similarity-based chunking, we design two adaptive chunking techniques based on uncertainty, namely Perplexity Chunking and Margin Sampling Chunking, by utilizing the logical perception capabilities of LLMs. Given the inherent complexity across different texts, we integrate meta-chunk with dynamic merging, striking a balance between fine-grained and coarse-grained text chunking. Furthermore, we establish the global information compensation mechanism, encompassing a two-stage hierarchical summary generation process and a three-stage text chunk rewriting procedure focused on missing reflection, refinement, and completion. These components collectively strengthen the semantic integrity and contextual coherence of chunks. Extensive experiments demonstrate that Meta-Chunking effectively addresses challenges of the chunking task within the RAG system, providing LLMs with more logically coherent text chunks. Additionally, our methodology validates the feasibility of implementing high-quality chunking tasks with smaller-scale models, thereby eliminating the reliance on robust instruction-following capabilities.
