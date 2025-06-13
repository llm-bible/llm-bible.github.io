---
layout: publication
title: 'MMKB-RAG: A Multi-modal Knowledge-based Retrieval-augmented Generation Framework'
authors: Zihan Ling, Zhiyao Guo, Yixuan Huang, Yi An, Shuai Xiao, Jinsong Lan, Xiaoyong Zhu, Bo Zheng
conference: "Arxiv"
year: 2025
bibkey: ling2025mmkb
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.10074'}
tags: ['RAG', 'Security', 'Tools']
---
Recent advancements in large language models (LLMs) and multi-modal LLMs have
been remarkable. However, these models still rely solely on their parametric
knowledge, which limits their ability to generate up-to-date information and
increases the risk of producing erroneous content. Retrieval-Augmented
Generation (RAG) partially mitigates these challenges by incorporating external
data sources, yet the reliance on databases and retrieval systems can introduce
irrelevant or inaccurate documents, ultimately undermining both performance and
reasoning quality. In this paper, we propose Multi-Modal Knowledge-Based
Retrieval-Augmented Generation (MMKB-RAG), a novel multi-modal RAG framework
that leverages the inherent knowledge boundaries of models to dynamically
generate semantic tags for the retrieval process. This strategy enables the
joint filtering of retrieved documents, retaining only the most relevant and
accurate references. Extensive experiments on knowledge-based visual
question-answering tasks demonstrate the efficacy of our approach: on the E-VQA
dataset, our method improves performance by +4.2% on the Single-Hop subset and
+0.4% on the full dataset, while on the InfoSeek dataset, it achieves gains of
+7.8% on the Unseen-Q subset, +8.2% on the Unseen-E subset, and +8.1% on the
full dataset. These results highlight significant enhancements in both accuracy
and robustness over the current state-of-the-art MLLM and RAG frameworks.
